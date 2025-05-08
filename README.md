# 💼 Job Khoji – Job Portal Website

**Job Khoji** is a fully functional online job portal built using Django. The platform connects job seekers with recruiters by providing job listings, application management, and admin controls. It allows recruiters to post and manage jobs, while users can apply for them by uploading their resumes.

---

## 🌐 Website Features

### 👨‍💼 For Job Seekers (Users)
- Register, log in, and manage their profile
- Search and apply for jobs
- Upload resumes
- View latest job alerts

### 🏢 For Recruiters
- Register, log in, and manage job listings
- Post new jobs
- Edit or delete posted jobs

### 🛠️ For Admin
- Manage users and recruiters
- View user/recruiter details
- Delete user/recruiter accounts
- Control website content and access

---

## 🚫 Not Included in Current Version
- Application tracking system
- Mobile app
- Premium services (resume writing, career counseling)
- Company reviews and ratings

---

## 🌍 Job Coverage
- Offers jobs in all types of industries
- International job listings supported

---

## 🛠️ Tech Stack

- **Backend**: Django (Python)
- **Frontend**: HTML, CSS, Bootstrap
- **Database**: SQLite (development), PostgreSQL/MySQL (optional for production)
- **Authentication**: Django's built-in auth system

---

## 🚀 Getting Started

Follow these steps to run the project locally:

### 1. Clone the Repository

```bash
git clone https://github.com/saugatpoudel100/job-khoji.git
cd job-khoji
```

### 2. Create Virtual Environment

```bash
python -m venv env
```

### 3. Activate Virtual Environment

- Windows:
  ```bash
  env\Scripts\activate
  ```
- macOS/Linux:
  ```bash
  source env/bin/activate
  ```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

> If there's no `requirements.txt`, install manually:
```bash
pip install django
```

### 5. Run Migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### 6. Create Superuser

```bash
python manage.py createsuperuser
```

### 7. Run the Server

```bash
python manage.py runserver
```

Visit: [http://127.0.0.1:8000](http://127.0.0.1:8000)

---

## 🛠️ Key Django Commands Used

| Command | Description |
|--------|-------------|
| `django-admin startproject jobkhoji` | Create a new Django project |
| `python manage.py startapp core` | Create a new Django app |
| `python manage.py makemigrations` | Prepare migration files |
| `python manage.py migrate` | Apply migrations to the database |
| `python manage.py createsuperuser` | Create admin user |
| `python manage.py runserver` | Start local development server |
| `pip install django` | Install Django framework |
| `python -m venv env` | Create virtual environment |

---

## 🧠 Future Enhancements

- Advanced job matching algorithm
- Application tracking dashboard for recruiters
- Mobile-responsive design
- Notifications and messaging system
- Premium membership plans

---



---

## 🙋 Contact

For suggestions, bugs, or collaboration opportunities, feel free to contact at:  
📧 [sauggupoudel10@gmail.com]  
🔗 GitHub: [https://github.com/saugatpoudel100](https://github.com/saugatpoudel100)

