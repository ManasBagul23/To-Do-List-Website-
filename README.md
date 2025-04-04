"# To-Do-List-Website-" 
To-Do List Application (Django)

Overview

This is a simple To-Do List web application built using Django. It allows users to add, update, delete, and mark tasks as completed.

Features

Add new tasks

Update tasks

Delete tasks

Mark tasks as completed

Responsive UI

Installation

Prerequisites

Ensure you have the following installed:

Python (>=3.8)

Django (>=4.0)

Virtualenv (optional but recommended)

Steps

Clone the repository:

git clone https://github.com/ManasBagul23/To-Do-List-Website
cd todo-list-django

Create a virtual environment (optional but recommended):

python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

Install dependencies:

pip install -r requirements.txt

Apply migrations:

python manage.py migrate

Create a superuser (for admin access):

python manage.py createsuperuser

Run the development server:
