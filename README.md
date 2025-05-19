FileX
FileX is a file-sharing application where users can upload files and receive a link that can be shared with others for downloading the uploaded file. It's an efficient and user-friendly way to share files.

Features
File Upload: Upload any file using the "Upload" button.
Shareable Link: After uploading, a unique link is generated for the file, which can be shared with anyone.
File Download: The recipient of the link can download the uploaded file.
How It Works
Upload a File: Use the upload button to select and upload a file.
Get a Shareable Link: Once the file is uploaded, a link is provided.
Share the Link: Share this link with others so they can download the file.
Download the File: Anyone with the link can download the file.
Technologies Used
Frontend: React
Backend: Node.js, Express.js
Database: MongoDB (for storing file metadata like file name, size, and upload time)
File Uploading: multer (for handling file uploads in Node.js)
Getting Started
Prerequisites
Node.js and npm installed
MongoDB (installed and running)
Installation
Clone the repository:

git clone https://github.com/umeshyadav7988/FileX.git
Navigate to the project directory: cd FileX

Install the backend dependencies: cd server npm install

Install the frontend dependencies: cd ../client npm install

Set up MongoDB: Ensure MongoDB is running locally or connected to a cloud instance (e.g., MongoDB Atlas).
