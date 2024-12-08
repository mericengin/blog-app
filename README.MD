# Flask Blog Application

This is a simple Flask-based blog application where users can register, log in, create, edit, delete, and comment on blog posts. The application uses Flask-Login for authentication, SQLAlchemy for database management, and Flask-Bootstrap for styling.

## Features

- **User Registration and Login**: Users can register an account, log in, and access the blog content.
- **Blog Post Management**: Admin users can create, edit, and delete blog posts.
- **Comments Section**: Logged-in users can add comments to individual blog posts.
- **Admin-Only Access**: Certain actions like creating, editing, and deleting posts are restricted to admin users.
- **Responsive Design**: The application is designed to be fully responsive using Bootstrap 5.

## Tech Stack

- **Flask**: A micro web framework used to create the backend of the application.
- **Flask-SQLAlchemy**: Used for database management and ORM (Object-Relational Mapping).
- **Flask-Login**: Used for handling user authentication and session management.
- **Flask-Bootstrap**: Provides a nice and responsive UI using Bootstrap 5.
- **Flask-CKEditor**: Provides a rich text editor functionality for creating blog posts.
- **SQLAlchemy**: Used for ORM and managing interactions with the database.

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/blog-app.git
cd blog-app