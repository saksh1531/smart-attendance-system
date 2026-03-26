# Smart Attendance System

This project is a simple and smart way to manage attendance using QR codes.
Instead of marking attendance manually, the system scans a QR code and automatically records the attendance with date and time.

---

## What this project does

* Generates QR codes for students
* Scans QR codes using camera (OpenCV)
* Marks attendance automatically
* Stores data in Excel/CSV
* Provides login/register system with dashboard

---

## Features

* User Login and Registration
* QR Code Generation
* Real-time QR Scanning
* Automatic Attendance Tracking
* Admin and Student Dashboard
* Data stored for future use

---

## Technologies Used

* Python
* Flask
* OpenCV
* Pandas
* HTML, CSS, JavaScript

---

## How to run the project

1. Clone the repository

```
git clone https://github.com/saksh1531/smart-attendance-system.git
cd smart-attendance-system
```

2. Install required libraries

```
pip install flask opencv-python pandas qrcode
```

3. Run the application

```
python app.py
```

4. Open in browser

```
http://127.0.0.1:5000
```

---

## Project Structure

* `app.py` → main backend file
* `templates/` → frontend pages
* `static/` → QR codes and assets
* `attendance.xlsx` → attendance data

---

## What I learned

* How to build a full-stack project using Flask
* Basics of computer vision with OpenCV
* Connecting frontend with backend
* Handling real-time data

---

## Future Improvements

* Add face recognition (AI)
* Add email notifications
* Improve UI design
* Deploy project online

---

## Author

Sakshi Mankape
GitHub: https://github.com/saksh1531

---

Thanks for checking out this project 😊
