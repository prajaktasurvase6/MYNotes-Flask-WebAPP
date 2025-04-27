# 📝 Flask MyNotes WebApp

A full-stack **Flask** web application for managing personal notes, built with **TailwindCSS** and **FontAwesome** for a modern, clean UI.

---

## 🚀 Features

- User authentication (Sign Up, Login, Logout)
- Create, view, and delete notes
- Categorize notes by type (Work, Personal, Study, Other)
- Responsive mobile-friendly UI
- Clean modern design using TailwindCSS
- Database powered by SQLite and SQLAlchemy

---

## 🛠 Setup & Installation

Make sure you have Python 3.8+ installed.

1. Clone the repository:

```bash
git clone https://github.com/prajaktasurvase6/Flask-MyNotes-WebAPP.git
cd Flask-MyNotes-WebAPP
```

2. Create and activate a virtual environment:

```bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Run the application:

```bash
flask run
```

Visit [http://127.0.0.1:5000](http://127.0.0.1:5000) in your browser.

---

## 🗂 Project Structure

```
Flask-MyNotes-WebAPP/
├── website/
│   ├── static/
│   ├── templates/
│   ├── __init__.py
│   ├── auth.py
│   ├── models.py
│   ├── views.py
├── venv/
├── requirements.txt
├── README.md
```

