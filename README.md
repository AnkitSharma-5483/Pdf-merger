# Pdf-merger

📄 PDF Merger (Node.js + Express)

A simple web application built with Express.js that allows users to upload two PDF files and merge them into a single PDF.

The merged file is automatically generated and made available for download.

🚀 Features

Upload two PDF files

Merge PDFs instantly

Automatic file generation

Download merged PDF from browser

🛠️ Technologies Used

Node.js

Express.js

Multer

pdf-merger-js

📦 Installation

Clone the repository

Install dependencies:

npm install

▶️ Run the Project

Start the server:

node index.js


Open in browser:

http://localhost:3000

📁 Project Structure
project
│
├── uploads/        # Uploaded PDFs
├── public/         # Generated merged PDFs
├── template/       # HTML frontend
├── index.js        # Express server
├── merge.js        # PDF merge logic

📄 How It Works

User uploads two PDF files.

Files are handled using Multer.

The server merges them using pdf-merger-js.

A new merged PDF is generated.

The user is redirected to download the merged file.
