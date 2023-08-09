# blog-website

This is a simple blog website built using **Node.js, Express, MongoDB, and the EJS templating engine**. The website allows users to read and create blog posts.

### Home
![blog_app_preview](https://github.com/charlenexu20/blog-website/assets/113628879/9b7b7edf-f1a0-4e28-a863-569959568db0)


### Compose
![blog_app_preview](https://github.com/charlenexu20/blog-website/assets/113628879/27c9fd34-31b0-4407-b86d-52d3d2c7269d)


### Post detail
![blog_app_preview](https://github.com/charlenexu20/blog-website/assets/113628879/e0da1157-a566-4a99-a314-31402c90af42)

## Usage:

- Homepage (http://localhost:3000): This is the default page where you can see the list of posts. Clicking "read more" takes you to the detailed view of a post.
- Compose (http://localhost:3000/compose): Create a new post by adding a title and content on this page.
- Post Detail (http://localhost:3000/posts/<:postId>): View a specific post using its unique post ID in the URL.

## Project Structure

- views/ folder contains EJS templates for different pages.
- public/ folder holds static assets (e.g., CSS files).
- app.js is where routes are established, the database is configured, and various server operations are handled.

## Technologies Used

- EJS
- Express.js
- MongoDB
- Node.js
