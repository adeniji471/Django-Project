# Django-Project: My Tennis Club

# A simple  Django web application

## Features
- List all club memers
- View memer details
- Add / Update / Delete members
- Django Admin panel

## Tech Stack
- Python 3.x
- Django 5.x
- SQLite3
- HTML / Django Templates

## Installation

1. clone the repo:
...bash
git clone https://github.com/adeniji471/Django-Project.git
cd Django-Project


2. Create virtual environment:
- python -m venv my_venv
- my_venv\Scripts\activate # on windows


3. Install dependencies:
- pip install -r requirements.txt

4. Run migration:
- python manage.py migrate

5. Start server:
- python manage.py runserver
- open 127.0.0.1:8000 in your browser.



Project Structure
Django-Project/
├──  manage.py
├──  my_Tennis_club  # main project setting
├──  members/        # members app
├──  requirements.txt 
└── README.md


Author
Adeniji Michael-@adeniji471
