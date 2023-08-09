# blog-website

This is a simple blog website built using **Node.js, Express, MongoDB, and the EJS templating engine**. The website allows users to read and create blog posts.

### Home
![blog_app_preview](https://github.com/charlenexu20/blog-website/assets/113628879/a2c4b14d-4b43-4d1d-8e0f-29ef709e550f)


### Compose
![blog_app_preview](https://github.com/charlenexu20/blog-website/assets/113628879/ffacdd85-8dfb-463d-86a7-89e6041f03e4)


### Post detail
![blog_app_preview](https://github.com/charlenexu20/blog-website/assets/113628879/3d967196-bfba-4a12-bec3-0a7e5876f44f)

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
