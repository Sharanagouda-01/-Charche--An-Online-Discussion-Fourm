Charche - Online Discussion Forum

Overview

Charche is an online discussion forum built using the Django web framework. It allows users to engage in discussions, ask questions, and share knowledge on various topics. Users can create discussion threads, comment on posts, and interact with each other in a collaborative environment.

Features

User Registration and Authentication: Users can register, log in, and manage their accounts securely.
Create and Manage Topics: Users can start new discussions by creating topics with relevant tags for categorization.
Commenting System: Users can comment on topics and engage in discussions.
Responsive UI: The platform is designed to be mobile-friendly and responsive across various devices.

Tech Stack

Backend:

Django (Python)
SQLite (default database for development)
Django ORM for database interactions

Frontend:

HTML, CSS, JavaScript
Bootstrap for responsive design

Installation and Setup

To run the project locally, follow these steps:

Prerequisites
Python 3.x: Ensure that Python is installed on your system. You can download it from here.
Django: Install Django using pip if not already installed.

Steps

Clone the Repository:

git clone https://github.com/Sharanagouda-01/-Charche--An-Online-Discussion-Fourm.git

cd -Charche--An-Online-Discussion-Fourm

Create a Virtual Environment:

python -m venv venv

source venv/bin/activate  # On Windows use `venv\Scripts\activate`

Apply Migrations:


python manage.py migrate

Run the Development Server:


python manage.py runserver

Open your browser and navigate to http://127.0.0.1:8000/.

Contributing
If you would like to contribute to this project, feel free to submit a pull request. For major changes, please open an issue to discuss the changes first
