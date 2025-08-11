# RJS Payroll System: Comprehensive HR & Payroll Management System

RJS Payroll System is a modern, full-stack web application designed to streamline Human Resources and payroll processes for small to medium-sized businesses. Built with a powerful and scalable tech stack, this platform provides a centralized hub for managing employee data, attendance, leave, financials, and payroll, all accessible through a clean, role-based user interface.

## Key Features

- **Role-Based Access Control (RBAC)**: A secure system with distinct roles for 'Administrator' and 'User' (Employee), ensuring users only have access to relevant information and functionalities.
- **Interactive Admin Dashboard**: Provides administrators with an at-a-glance overview of key metrics, including total employees, active employees, pending leave requests, and the date of the next payroll run.
- **Employee Directory**: A comprehensive and searchable directory of all employees, with filtering capabilities. Admins can add, view, and edit detailed employee profiles.
- **Detailed Employee Profiles**: Each employee has a personal profile page displaying their job information, contact details, salary, and financial IDs. Users can view their own profiles, and admins can view all profiles.
- **Time & Attendance Management**: Features a daily time clock for employees to log their morning, lunch, and afternoon in/out times. The system supports custom work shifts and calculates work hours.
- **Leave Management System**: A complete workflow for leave requests. Employees can apply for various types of leave, and administrators can review, approve, or reject these requests. An integrated company calendar visually displays all approved leaves and holidays.
- **Financial & Payroll Processing**:
  - **Payroll Generation**: Admins can run payroll for specific periods (semi-monthly or full month) and for specific groups of employees.
  - **Dynamic Calculations**: The system automatically calculates gross pay, deductions (including statutory contributions like SSS, PhilHealth, Pag-IBIG), and net pay based on configurable rates.
  - **Payslip Management**: Automatically generates detailed payslips for each employee after a payroll run. Both admins and employees can view their historical payslips.
- **Company Customization**:
    - **Holiday Management**: Admins can add and manage company-wide holidays, which are reflected in the company calendar and attendance calculations.
    - **Benefits & Loans**: A dedicated module for tracking employee loans and managing company benefits.
    - **Payroll Settings**: Admins have full control to configure deduction rates, tax brackets, and other payroll-related settings.
- **Communication & Support**:
    - **Announcements**: Admins can create and publish company-wide announcements, with support for comments and replies.
    - **Help Desk**: A simple ticketing system for employees to submit support requests.
    - **Real-time Notifications**: A site-wide notification system alerts users to important events like leave request updates and new payslips.
- **User Experience & Customization**:
    - **Appearance Settings**: Users can customize their experience by choosing different color themes (Default, Green, Purple) and font sizes.
    - **Dark Mode**: A fully supported dark theme for user comfort.
    - **Avatar Selection**: Users can select a profile picture from a predefined library of hosted images.

## Technology Stack

- **Frontend**:
  - **Framework**: Next.js (App Router)
  - **Language**: TypeScript
  - **UI Library**: React
- **Styling**:
  - **CSS Framework**: Tailwind CSS
  - **Component Library**: ShadCN UI, providing beautiful and accessible components.
  - **Icons**: Lucide React
- **Backend & Database**:
  - **Platform**: Firebase
  - **Database**: Firestore (for real-time, NoSQL data storage)
  - **Authentication**: Firebase Authentication (for secure user login and management)
- **State Management & Forms**:
  - **Client-Side State**: React Context API, React Hooks (`useState`, `useEffect`, `useMemo`)
  - **Form Handling**: React Hook Form with Zod for robust validation.
- **AI Integration (Planned)**:
  - **Framework**: Genkit (Google's Generative AI toolkit) is integrated, providing the capability to add AI-powered features in the future.

## Roles & Permissions

The system is designed with two primary roles:

1.  **Administrator**:
    - Has full access to all features.
    - Manages all employee data, including adding new employees and editing profiles.
    - Runs and manages payroll, configures payroll settings, and views all payslips.
    - Approves or rejects leave requests and manages company holidays.
    - Views all company-wide reports and analytics.
    - Publishes announcements and manages help desk tickets.

2.  **User (Employee)**:
    - Has limited access focused on personal information.
    - Can view their own dashboard, profile, and payslip history.
    - Can apply for leave and view the status of their requests.
    - Can view the company calendar and published announcements.
    - Can customize their own appearance settings.
    - Can submit help desk tickets.
  

#THANK YOU!
