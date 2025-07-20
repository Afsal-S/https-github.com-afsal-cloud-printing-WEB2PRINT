Web2Print — Automated Local Network Printing System
Purpose
Web2Print is an automated printing system designed to digitize and streamline the traditional document printing process. The core goal is to eliminate manual file handling in printing stores by providing a cloud-enabled, on-premise web platform that connects users and store-side printers efficiently. This reduces human error, saves time, and ensures secure file handling.
Key Features & Functionality:

* User Portal: Users can upload documents through a secure web interface.
* Store Selection: An interactive map lets users choose a nearby printing store based on location.
* File Storage: Uploaded files are encrypted and stored securely using a cloud storage service (e.g., Cloudinary).
* Automated Print Execution: The selected store’s printer system fetches the file automatically from the cloud and prints it without manual intervention by staff.
* Real-Time Order Tracking: Users can track their print job’s status updates until completion.
* Security: AES encryption ensures file privacy during upload, storage, and retrieval.
  
Implementation Details:
* Frontend: Built with React, providing a user-friendly interface for uploads, store selection, and status tracking.
* Backend: Developed with Django (Python) for handling file uploads, encryption, store management, and order tracking.
* Database: Uses PostgreSQL for storing user data, order details, and store information.
* File Storage: Integrates Cloudinary for secure cloud storage of uploaded files.
* Store-Side Printing: A Python script or local application runs in the store to fetch files from Cloudinary and automatically send them to the printer on a first-come, first-serve basis.

Deployment & Platform:
* Runs as an on-premise web application, accessible over a local network by both users and store printers.
* Supports cross-platform access — users can access it from any desktop or mobile browser.
* Combines local network integration with cloud storage, ensuring flexibility and scalability.
Impact:

* 80% reduction in manual order processing time.
* Minimizes human involvement in repetitive tasks.
* Improves efficiency, accuracy, and customer convenience in document printing services.
