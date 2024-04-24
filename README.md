# Laravel Blog and Chat App with Node.js

---

## Description:
This repository contains a Laravel application for a Blog CRUD functionality with a real-time chat application with Node.js integration. This project is a code-along learning project from the [Let's Learn Laravel: A Guided Path For Beginners](https://www.udemy.com/course/lets-learn-laravel-a-guided-path-for-beginners) Udemy course.

# Laravel and Node.js Chat App with Blog Posts CRUD

---

## Description:
This repository contains a Laravel and Node.js application for a real-time chat application with blog posts CRUD functionality, user authentication, access control, and email features. The application allows users to chat with each other in real-time using Pusher for WebSocket-based communication, create, read, update, and delete blog posts, and manage user access with authentication.

## Features:
- Blog posts CRUD (Create, Read, Update, Delete)
- Real-time chat functionality with Pusher for WebSocket-based communication
- User authentication and authorization
- Access control for different user roles (e.g., admin, user)
- Follow user functionality
- Search functionality
- Cache functionality
- Email functionality for site recap and new post notifications
- API Authentication

## Technologies Used:
- Laravel
- PHP
- MySQL
- Blade Template engine
- Node.js
- Pusher (for real-time communication)

## Installation:
1. Clone this repository to your local machine.
`git clone https://github.com/nilufarshaikh/laravel-chat-application.git`

2. Navigate to the project directory.
`cd laravel-chat-application`

3. Install composer dependencies.
`composer install`

4. Create a copy of the `.env.example` file and rename it to `.env`.
`cp .env.example .env`

5. Generate the application key.
`php artisan key:generate`

6. Set up your pusher, mailer and database configuration in the `.env` file.

7. Run database migrations.
`php artisan migrate`

8. Install Node.js dependencies.
`npm install`

9. Build and run the NPM server.
`npm run build`
`npm run dev`

10. Serve the Laravel application.
`php artisan serve`

11. Open your web browser and navigate to http://localhost:8000 to view the app.

## Usage:
1. Run to clear cache: 
`php artisan cache:clear`

2. Run to send created post emails:
`php artisan queue:work`

3. Run to send Recap site email:
`php artisan schedule:work`

## Resources:
[Official Laravel Documentation](https://laravel.com/docs/)
[Let's Learn Laravel: A Guided Path For Beginners](https://www.udemy.com/course/lets-learn-laravel-a-guided-path-for-beginners) by Brad Schiff

---
