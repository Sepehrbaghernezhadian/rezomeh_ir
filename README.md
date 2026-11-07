# Personal Resume Website | وب‌سایت رزومه شخصی

A personal resume and portfolio website built with **Django** and **Python**, showcasing my skills, projects, and contact information.

وب‌سایت رزومه شخصی من که نمونه‌کارها، مهارت‌ها و راه‌های ارتباطی‌ام در آن نمایش داده می‌شود.

## ✨ Features

- 📄 Personal resume and about section
- 💼 Portfolio / projects showcase
- 📬 Contact form (messages are stored in the database)
- 🔐 Django admin panel for managing content and messages
- 📱 Responsive design

## 🛠 Tech Stack

- **Backend:** Python, Django
- **Frontend:** HTML, CSS
- **Database:** SQLite (Django default)

## 🚀 Installation

```bash
# Clone the repository
git clone https://github.com/sepehrbaghri13851386-rgb/rezomeh_ir.git
cd rezomeh_ir/sepi_project

# Create and activate virtual environment
python -m venv venv
venv\Scripts\activate        # Windows
# source venv/bin/activate   # Linux / macOS

# Install dependencies
pip install -r requirements.txt

# Apply migrations
python manage.py migrate

# Create admin user
python manage.py createsuperuser

# Run the server
python manage.py runserver
```

Then open: `http://127.0.0.1:8000`

Admin panel: `http://127.0.0.1:8000/admin`

## 📸 Screenshots

> Add screenshots of the home page, projects and contact form here.

## 📫 Contact

- GitHub: [@sepehrbaghri13851386-rgb](https://github.com/sepehrbaghri13851386-rgb)
- Website: https://sepehrbaghernezhadian.ir

## 📄 License

This project is open source and available under the MIT License.
