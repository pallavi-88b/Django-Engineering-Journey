# 👋 Personal Welcome Website

<p align="center">
  <b>A Beginner-Friendly Django Project</b><br>
  Learning URLs, Views and HTTP Responses
</p>

---

## 📌 About the Project

Personal Welcome Website is a beginner-level Django project created to understand how URL routing works and how Django views return responses to a browser.

The project contains different pages connected through URL patterns.

## ✨ Features

- Home page with a welcome message
- About page
- Contact page
- Services page
- Separate URLs for different pages
- Text responses using Django's `HttpResponse()`

## 🛠️ Tech Stack

- Python
- Django

## 📚 Django Concepts Practiced

- Django project and app setup
- `urls.py`
- `views.py`
- `path()`
- URL routing
- View functions
- `HttpResponse()`

## 📂 Project Structure

```text
Personal-Welcome-Website/
├── manage.py
├── project_folder/
│   └── urls.py
└── app_folder/
    ├── views.py
    └── urls.py
```

*Note: Replace the example folder names with your actual project and app names.*

## 🔗 Example URLs

| Page | Example URL |
|---|---|
| Home | `/` |
| About | `/about/` |
| Contact | `/contact/` |
| Services | `/services/` |

These examples assume the corresponding routes exist in your code.

## 🚀 Run Locally

1. Install Django:

   ```bash
   python -m pip install django
   ```

2. Open the project directory containing `manage.py`.

3. Start the development server:

   ```bash
   python manage.py runserver
   ```

4. Open the local development URL shown in the terminal.

## 🎯 Learning Outcome

Learned how Django receives a URL request, matches it with a URL pattern, calls the associated view function, and returns an HTTP response.

---

**Project:** Personal Welcome Website  
**Category:** Django Practice  
**Focus:** URLs and Views  
**Status:** Completed
