# 🖥️ University Management System — Frontend (React + Vite)

![React](https://img.shields.io/badge/React-19.2-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-7.2-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Lucide Icons](https://img.shields.io/badge/Lucide--React-Icons-F05032?style=for-the-badge)
![Axios](https://img.shields.io/badge/Axios-HTTP%20Client-5A29E4?style=for-the-badge&logo=axios&logoColor=white)

A modern, responsive Single Page Application (SPA) frontend for the University Management System. Engineered with **React 19**, **Vite**, and **Lucide Icons**, offering dedicated interfaces for **Administrators**, **Faculty Members**, and **Students**.

---

## 🎨 Role Portals & Components

```text
react-frontend/src/components/
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

## 📁 Repository Structure

```text
UniversityManagementSystem_Frontend/
├── react-frontend/                  # React + Vite application workspace
│   ├── src/
│   │   ├── assets/                 # Brand logos and illustrations
│   │   ├── components/             # Reusable and role-specific UI components
│   │   ├── styles/                 # Modular CSS stylesheets
│   │   ├── App.jsx                 # Global auth state and routing controller
│   │   ├── main.jsx                # React DOM entry point
│   │   └── index.css               # Global typography and theme variables
│   ├── public/                     # Static web assets
│   ├── package.json                # Project dependencies and npm scripts
│   ├── vite.config.js              # Vite bundler configuration
│   └── frontend_analysis.txt       # Frontend technical specification notes
├── University_Management_System.postman_collection.json # API endpoints collection
└── README.md                       # Project documentation
```

---

## 🚀 Getting Started

### 1. Prerequisites
* [Node.js](https://nodejs.org/) (v18.0.0 or higher recommended)
* npm or yarn

### 2. Installation
Navigate into the `react-frontend` directory and install dependencies:

```bash
cd UniversityManagementSystem_Frontend/react-frontend
npm install
```

### 3. Start Development Server
```bash
npm run dev
```
Open your browser and visit:
```text
http://localhost:5173
```

### 4. Build for Production
To create an optimized production build:
```bash
npm run build
```

---

## 🔗 Backend API Integration

The application connects with the Django REST backend. To point to your running API instance:
* Default Backend Base URL: `http://127.0.0.1:8000/`
* In `src/App.jsx` or your Axios client configuration, configure the base URL to match your backend port.
* Use the included [`University_Management_System.postman_collection.json`](file:///C:/Users/HP/Downloads/Ayon/UniversityManagementSystem_Frontend/University_Management_System.postman_collection.json) to test all backend endpoints alongside the UI.

