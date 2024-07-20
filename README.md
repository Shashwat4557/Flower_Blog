# Django Blog Website

## Table of Contents

1. [Introduction](#introduction)
2. [Technologies Used](#technologies-used)
3. [Features](#features)
4. [Project Structure](#project-structure)
5. [Setup Instructions](#setup-instructions)
6. [Usage](#usage)
7. [Future Scope](#future-scope)
8. [References](#references)

## Introduction

A Django-based blog website that allows users to create, read, update, and delete blog posts. The site includes user authentication, media management, and social media sharing capabilities.

## Technologies Used

- **Django**
- **SQLite**
- **Bootstrap 4**
- **Boxicons**

## Features

- User Authentication (login/logout)
- CRUD operations for blog posts
- Media management for images
- Social media sharing (Facebook, Twitter)
- Responsive design with Bootstrap 4

## Project Structure

- **blogging**: Main project folder
  - **settings.py**: Configuration file
  - **urls.py**: URL mapping
- **gallery**: Application folder
  - **models.py**: Database models
  - **views.py**: Request handling
  - **templates/gallery**: HTML templates

## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Shashwat4557/django-blog-website.git
   cd django-blog-website
   ```

2. **Install dependencies**:
   ```bash
   pip install django
   ```

3. **Setup the database**:
   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```

4. **Create a superuser**:
   ```bash
   python manage.py createsuperuser
   ```

5. **Run the server**:
   ```bash
   python manage.py runserver
   ```

## Usage

1. **Login**: Access the login page to enter the admin dashboard.
2. **Manage Posts**: Create, edit, or delete blog posts from the dashboard.
3. **View Posts**: Browse the homepage for a list of blog posts.
4. **Share Posts**: Use share buttons on each post to share on social media.

## Future Scope

- Comments system
- User profiles
- Analytics dashboard
- Performance optimization (caching)
- Enhanced security (role-based access control)

## References

- [Django Documentation](https://docs.djangoproject.com/)
- [Bootstrap 4 Documentation](https://getbootstrap.com/docs/4.0/getting-started/introduction/)
- [Boxicons](https://boxicons.com/)

## Contact

- Email :- shashwat1326@gmail.com
- Linkedin :- www.linkedin.com/in/shashwat-srivastava-b03389224
