# 🖥️ University Management System — React Frontend

![React](https://img.shields.io/badge/React-19.2-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-7.2-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Lucide Icons](https://img.shields.io/badge/Lucide--React-Icons-F05032?style=for-the-badge)

A modern, responsive Single Page Application (SPA) frontend for the University Management System. Built with **React 19**, **Vite**, and **Lucide Icons**, providing dedicated interfaces for **Administrators**, **Faculty Members**, and **Students**.

---

## 🎨 Role Portals & Components

```text
src/components/
├── login/
│   ├── LoginPage.jsx               # Role-switchable login (Admin/Faculty/Student)
│   └── ForgotPasswordPage.jsx      # Password reset flow
│
├── admin/
│   ├── AdminDashboard.jsx          # Admin overview metrics
│   ├── ManageStudents.jsx          # Student registration and profile management
│   ├── ManageFaculty.jsx           # Faculty appointments and department tagging
│   ├── ManageCourses.jsx           # Course catalog and prerequisite builder
│   ├── AssignCourses.jsx           # Faculty section assignment matrix
│   ├── StudentEnrollment.jsx       # Student enrollment approvals
│   └── ViewRecords.jsx             # Comprehensive audit reports
│
├── faculty/
│   ├── FacultyDashboard.jsx        # Faculty schedule and announcement feed
│   ├── ViewAssignedCourses.jsx     # Active teaching courses
│   ├── ViewStudents.jsx            # Course rosters and contact lists
│   ├── SubmitGrades.jsx            # Grade entry interface
│   └── UpdateGrades.jsx            # Grade amendment workflow
│
└── student/
    ├── StudentDashboard.jsx        # Student home with notifications
    ├── ViewEnrollment.jsx          # Course registration window
    ├── ViewGrades.jsx              # Semester grade reports
    ├── AcademicHistory.jsx         # Transcript and CGPA calculations
    └── ClassScheduleWidget.jsx     # Weekly timetable calendar view
```

---

## 🚀 How to Run Locally

1. **Install dependencies**:
   ```bash
   npm install
   ```

2. **Start the development server**:
   ```bash
   npm run dev
   ```

3. **Access the application**:
   Open `http://localhost:5173` in your browser.

4. **Production Build**:
   ```bash
   npm run build
   ```

---

## 🔗 Backend API Integration
Connects to the Django REST API running at `http://127.0.0.1:8000/`. Seed login credentials can be found in the backend documentation.

