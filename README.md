# Blog Project

## Overview

The Blog Project is a web application developed as part of the IT course using the SCRUM methodology. The project implements a simple blogging platform where users can perform CRUD (Create, Read, Update, Delete) operations on blog posts. The application is built with HTML, CSS version control was handled through Git.


## Tech Stack

- Frontend: HTML, CSS
- Database: SQLite
- Version Control: Git

## Functional Requirements

The core functionalities of the application include:

- Create: Users can create new blog posts.
- Read: Users can view a list of all blog posts.
- Update: Users can edit existing blog posts.
- Delete: Users can delete blog posts.

## Non-Functional Requirements

- Performance: The application must load pages within 3 seconds.
- Security: Basic security measures such as input validation and user authentication have been implemented.
- Scalability: The application is designed to handle up to 1,000 simultaneous users.

## Installation Instructions

1. Clone the repository:
   
```bash
git clone 
```

2. Navigate to the project directory:
   
```bash
cd blog-project
```

2. Make sure to setup a new virtual environment:

```bash
python -m venv venv
```

3. Activate your new environment:

```bash
.\venv\Scripts\activate
```

3. Install required dependencies:
   
```bash
pip install -r requirements.txt
```   

4. Make the database migrations:
   
```bash
python manage.py makemigrations
```

5. Migrate the database:

```bash
python manage.py migrate
```

5. Start the development server:
   
```bash
python manage.py runserver
```

6. Open your browser and visit your localhost at http://127.0.0.1:8000/ to view the application.

## Project Structure

- Frontend: HTML and CSS.
- Backend: Django.
- Database: SQLite database used by default.

## Documentation

- The README provides an overview of the project, installation instructions, and project structure.

## Project Status

- Frontend: The frontend has been completed and is fully functional.
- Backend: The CRUD operations are fully implemented and tested.
- Demonstration: The project is now ready for demonstration and submission.
