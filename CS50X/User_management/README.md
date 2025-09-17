# User Management
#### Video Demo:  <URL HERE>
#### Description:
---

## 🧑‍💻 User Management System — Django Project

This project is a Django-based web application designed to handle user authentication and management in a clean and intuitive way. It provides a foundational structure for any web platform that requires user accounts, session tracking, and secure access control.

### ✨ Features

- **User Authentication**: Includes fully functional login, signup, and logout views using Django’s built-in authentication system.
- **Homepage Display**: Authenticated users are displayed on the homepage, offering a real-time view of who is currently logged in.
- **Session Management**: Ensures users stay logged in across sessions and handles logout securely.
- **Form Validation**: Signup and login forms include basic validation to prevent incorrect or incomplete submissions.
- **Routing & Navigation**: Clean URL structure and navigation between pages for a smooth user experience.

### 🛠️ Technologies Used

- **Django** (Python web framework)
- **HTML/CSS** for basic frontend structure
- **SQLite** as the default database (can be swapped with PostgreSQL or MySQL)
- **Django Templates** for rendering dynamic content

### 📦 Project Structure

```
user_management/
├── accounts/           # App handling user-related views and models
│   ├── views.py
│   ├── urls.py
│   ├── templates/
│   │   ├── login.html
│   │   ├── signup.html
│   │   ├── home.html
├── user_management/    # Main project settings
│   ├── settings.py
│   ├── urls.py
├── db.sqlite3          # Default database
```

### 🚀 How to Run

1. Clone the repository
2. Create a virtual environment and activate it
3. Install dependencies: `pip install -r requirements.txt`
4. Run migrations: `python manage.py migrate`
5. Start the server: `python manage.py runserver`
6. Visit `http://127.0.0.1:8000/` in your browser

### 📌 Use Cases

This project can be used as a starting point for:
- Social platforms
- Admin dashboards
- Membership-based websites
- Internal tools requiring user access control

---
