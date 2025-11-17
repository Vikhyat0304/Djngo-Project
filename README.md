🌟 STUDENT MANAGEMENT & ATTENDANCE SYSTEM – Django Project

A complete, modern, and fully functional Student Management & Attendance Tracking System built using Django, designed to streamline student records, attendance tracking, feedback collection, and teacher–student interaction.

This system provides separate roles for Admins, Teachers, and Students, ensuring smooth workflow, maximum security, and a premium user experience.

📌 Features at a Glance
🎓 Student Module

Login & role-based access

View your profile

Mark attendance (student card view)

Submit feedback

See attendance history

👨‍🏫 Teacher Module

Login & role-based access

Mark attendance using student cards slider UI

View attendance records

Manage students

Restrict feedback page (exclusive to students)

🛠 Admin Module

Manage students

Manage teachers

View feedback

View attendance records

Add/update/delete records

🚀 Tech Stack
Component	Technology
Backend	Django (Python)
Frontend	HTML, CSS, Bootstrap 5, JavaScript
Database	SQLite (default) / MySQL (optional)
Auth System	Django Auth
Icons / UI	Bootstrap Icons / Custom Cards UI
📂 Project Structure
attendance_project/
│── core/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   ├── forms.py
│   ├── templates/core/
│── attendance_project/
│── static/
│── db.sqlite3
│── manage.py

⚙️ Installation & Setup
✅ 1. Clone the repository
git clone https://github.com/yourusername/student-management-system.git
cd student-management-system

✅ 2. Create virtual environment
python -m venv venv
venv\Scripts\activate  # Windows

✅ 3. Install dependencies
pip install -r requirements.txt

✅ 4. Apply migrations
python manage.py migrate

✅ 5. Create superuser
python manage.py createsuperuser

✅ 6. Run the server
python manage.py runserver

🎨 UI Highlights
✔ Modern Student Cards
✔ Premium dashboard layouts
✔ Slide-based attendance UI
✔ Beautiful feedback UI
✔ Mobile responsive
✔ Clean, modern Bootstrap-based layout
🔐 Role Based Access
Role	Features
Student	Feedback + Attendance History
Teacher	Mark Attendance + View Students
Admin	Full CRUD on students/teachers/attendance
📝 Major Modules Explained
1️⃣ Attendance System

Teachers can mark attendance using a swipeable card slider

Students appear as cards with Present / Absent buttons

Database stores daily attendance records

2️⃣ Feedback System

Students only

Teachers/admin restricted

Student auto-detected based on logged-in account

Clean UI form

Stored in Feedback model

3️⃣ Authentication System

Custom login

Redirect students → Home Page

Redirect teachers → Teacher Dashboard

Redirect admin → Admin Panel

🗄️ Database Models
✔ Student
✔ Teacher
✔ Attendance
✔ Feedback
✔ User (Django Auth)

Each model is optimized with proper foreign keys, indexes, and relational integrity.

🧪 Testing

The project supports:

Functional testing

Unit testing

UI testing

Role-based access testing

🛡 Security Features

Secure authentication

CSRF protection

Form validation

Protected student feedback (no teacher misuse)

SSL-compatible

📸 Screenshots (Add yours)
/screenshots
    home_page.png
    student_cards.png
    attendance_marking.png
    feedback_form.png
    teacher_dashboard.png

📘 Future Enhancements

Auto-generated attendance reports (PDF)

AI-based student performance analytics

SMS/Email notifications for absentees

Biometric attendance integration

Dark mode for UI

🤝 Contributing

Pull requests are welcome.
Feel free to open issues for suggestions or bug fixes.

🧑‍💻 Developer

Vikhyat Singh
B.Tech CSE, Lovely Professional University
GitHub: your_username
Email: your_email@example.com

⭐ Support

If this project helped you, don’t forget to ⭐ the repository!
