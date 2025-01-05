# Django REST Framework Blog API

A powerful REST API built with Django REST Framework that allows users to create, read, update and delete blog posts with authentication.

## Features

- User Registration & Authentication
- User Profile Management
- Blog Post CRUD Operations
- Pagination Support
- Permission-based Access Control

## API Endpoints

### Authentication
- `POST /register/` - Register new user
- `PUT /update-profile/` - Update user profile (requires authentication)

### Blog Operations
- `GET /blogs/` - List all blogs (paginated)
- `POST /create-blog/` - Create new blog post (requires authentication)
- `PUT /update-blog/<pk>/` - Update specific blog post (requires authentication)
- `POST /delete-blog/<pk>/` - Delete specific blog post (requires authentication)

## Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/django-blog-api.git
