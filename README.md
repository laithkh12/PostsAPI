# Blog API Project

This project consists of a simple blog API and a front-end client that allows users to create, read, update, and delete blog posts. The API is built with Node.js and Express, while the client uses EJS for rendering views.

## Features
- Create new blog posts
- Read all blog posts or a specific post by ID
- Update existing blog posts
- Delete blog posts
- Front-end interface to interact with the API

## Technologies Used
- Node.js
- Express
- Body-parser
- EJS
- Axios

## Setup Instructions
Clone the repository:
```bash
git clone <repository-url>
cd <repository-directory>
```

## Install dependencies
```bash
npm install
```
## Run the API server
```bash
cd api
node index.js
```
## Run the client server
```bash
cd client
node server.js
```
## Access the application
- Open your browser and go to http://localhost:3000 to access the client interface.

## API Endpoints
Blog Posts :
- GET /posts: Retrieve all blog posts.
- GET /posts/: Retrieve a specific post by ID.
- POST /posts: Create a new post. Body: { "title": "Post Title", "content": "Post content", "author": "Author Name" }
- PATCH /posts/: Update a specific post by ID. Body: { "title": "New Title", "content": "Updated content", "author": "New Author" }
- DELETE /posts/: Delete a specific post by ID.

## Usage
To create a new post, fill in the form on the "New Post" page and submit. To edit an existing post, click on the "Edit" link next to the post. You can delete a post by clicking the "Delete" link next to the post.

## Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue.
