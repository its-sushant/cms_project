# Content Management System

This is a simple Content Management System (CMS) built using Django. The CMS allows users to view, create, update, and delete blog posts. Users need to register and log in to create, edit, or delete posts, but anyone can view the posts.

## Features

1. View all posts available on the website.
2. Register as a new user.
3. Log in to create, update, and delete your own posts.
4. User authentication and authorization to ensure users can only modify their own posts.

## Requirements

- Python
- Django

## Setup Instructions

### Clone the Repository

```bash
git clone git@github.com:its-sushant/cms_project.git
cd cms_project
```

### Create a Virtual Environment

```bash
python3 -m venv venv
source venv/bin/activate
```

### Apply Migrations

```bash
python manage.py migrate
```

### Run the Development Server

```bash
python manage.py runserver
```

## Usage

### Viewing Posts
- Go to the homepage to see the list of all posts.
- Click on a post title to view its details.
### Creating, Editing, and Deleting Posts
- Register a new account or log in with an existing account.
- Use the navigation links to create a new post.
- Edit or delete your own posts from the post detail page.

## Contributing
Feel free to fork this repository and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

