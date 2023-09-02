Files Manager
This project is a summary of this back-end trimester: authentication, NodeJS, MongoDB, Redis, pagination and background processing.

The objective is to build a simple platform to upload and view files:

User authentication via a token
List all files
Upload a new file
Change permission of a file
View a file
Generate thumbnails for images
You will be guided step by step for building it, but you have some freedoms of implementation, split in more files etc… (utils folder will be your friend)

Of course, this kind of service already exists in the real life - it’s a learning purpose to assemble each piece and build a full product.

Enjoy!

Requirements
Applications
Node.js
Yarn (the package manager/resource negotiator)
APIs
A Google API should be created with at least an email sending scope and a valid URL (e.g.; http://localhost:5000/) should be one of the redirect URIs. The credentials.json file should be stored in the root directory of this project.
Environment Variables
The required environment variables should be stored in a file named .env and each line should have the format Name=Value. The table below lists the environment variables that will be used by this server:
