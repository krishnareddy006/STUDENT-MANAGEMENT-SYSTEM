# Student Management System

## Overview
The **Student Management System** is a web-based application that allows students and teachers to manage student records and attendance efficiently. This system provides login access for both students and teachers, enabling them to add, view, and update student data and attendance records.

## Features
- **User Authentication**: Secure login for students and teachers.
- **Student Data Management**: Add, update, and view student records.
- **Attendance Tracking**: Teachers can record and manage student attendance.
- **Database Integration**: Stores data in MySQL for efficient record-keeping.
- **Responsive UI**: Built with HTML, CSS, and JavaScript for a smooth user experience.

## Tech Stack
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Python (Flask)
- **Database**: MySQL

## Installation
### Prerequisites
Ensure you have the following installed:
- Python 3.x
- MySQL
- Flask and required dependencies

### Steps to Install and Run
1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/student-management-system.git
   cd student-management-system
   ```

2. **Create a virtual environment (Optional but recommended)**
   ```bash
   python -m venv venv
   source venv/bin/activate  # For MacOS/Linux
   venv\Scripts\activate  # For Windows
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Configure Database**
   - Create a MySQL database.
   - Update `config.py` with your database credentials.
   - Run database migrations if applicable.

5. **Run the application**
   ```bash
   python main.py
   ```

6. **Access the web application**
   Open your browser and visit:
   ```
   http://127.0.0.1:5000
   ```

## Usage
- **Students**: Log in and manage their data.
- **Teachers**: Log in, add students, and manage attendance.




## Contact
For any queries, contact [Saikam Krishna Reddy](mailto:saikamkrishnareddy@gmail.com).
