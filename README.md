📚Django Library Management System

A clean and minimal Library Management System built with Django.  
This project focuses on functionality — models, CRUD, filters, search, and pagination — without any frontend styling.

---

 ✨ Features

- Manage **Books**, **Authors**, and **Genres**  
- Add, edit, and delete books  
- Assign books to authors and multiple genres  
- Mark books as *available* or *unavailable*  
- Search books by **title** or **author**  
- Filter books by **genre** and **availability**  
- Pagination for long lists of books (5 per page)  
- Aggregations: Count books per author and per genre  
- Fully customized Django Admin for easy management

---

📁 Project Structure

library_project/
├── library_app/
│ ├── models.py
│ ├── admin.py
│ ├── views.py
│ ├── forms.py
│ ├── urls.py
│ └── templates/library_app/
│ ├── base.html
│ ├── book_list.html
│ ├── add_book.html
│ └── edit_book.html
├── library_project/
│ ├── settings.py
│ ├── urls.py
│ └── wsgi.py
├── manage.py
└── README.md

yaml
Copy code

---

 🚀 Getting Started

 Prerequisites

- Python 3.x  
- pip installed  
- Virtual environment (recommended)

 Installation

1. **Clone the repository**  
   ```bash
   git clone https://github.com/banumariwan/django_library_management.git
   cd django_library_management/library_project
Create and activate a virtual environment

Windows:

bash
Copy code
python -m venv env
.\env\Scripts\activate
Mac/Linux:

bash
Copy code
python3 -m venv env
source env/bin/activate
Install dependencies

bash
Copy code
pip install -r requirements.txt
Apply migrations

bash
Copy code
python manage.py migrate
Create a superuser (admin)

bash
Copy code
python manage.py createsuperuser
Run the development server

bash
Copy code
python manage.py runserver
Open your browser:

App: http://127.0.0.1:8000

Admin: http://127.0.0.1:8000/admin

🛠️ Usage
Use the admin panel to add authors and genres

Use the Books page to add, edit, or delete books

Filter and search to find specific books

Pagination limits 5 books per page

✅ Purpose
Practice Django ORM (filters, Q objects, annotations)

Build real CRUD functionality

Implement pagination and combined search + filter

Customize Django Admin for better management

📈 Future Improvements
Add user authentication (login/register)

Implement borrowing/lending system

Build a REST API with Django REST Framework

Add styling with Bootstrap or Tailwind CSS

Dashboard analytics for books and users

💬 Contributing
Fork the repo

Create a new branch: git checkout -b feature/my-feature

Make changes & commit: git commit -m "Add feature"

Push to branch: git push origin feature/my-feature

Open a pull request

📄 License
This project is licensed under the MIT License.

📣 Author
Banu Mariwan
GitHub: banumariwan
