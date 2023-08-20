# Smart Attendance System Using Face Recognition

<p align="center">
  <img src="[https://giphy.com/gifs/face-recognition-fingerprint-l46CdUMvPpvT5V984](https://giphy.com/embed/l46CdUMvPpvT5V984" width="480" height="480" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/face-recognition-fingerprint-l46CdUMvPpvT5V984)" alt="Logo" width="300">
</p>

The **Smart Attendance System Using Face Recognition** is an innovative project designed to streamline and automate attendance management in various settings, including educational institutions, corporate offices, and events. This system leverages cutting-edge facial recognition technology to accurately identify and record individuals' attendance.

Traditionally, attendance management has been a manual and time-consuming task, involving physical sign-ins or RFID card scans. This smart attendance system revolutionizes the process by employing sophisticated facial recognition algorithms to instantly recognize and verify the identity of individuals as they enter a designated area.

## Demo

See the system in action:

<p align="center">
  <img src="https://github.com/sanjay-munde/Smart-Attendance-System-Using-Face-Recognition/blob/main/Images_GUI/Attendance%20gif.gif" alt="Attendance Demo" width="600">
</p>

## Features

### ▷ Project Features:

- **Real-time Face Detection:** The system provides real-time face detection capabilities, ensuring accurate identification.

- **Secure Login System:** A secure login system with username and password authentication to protect sensitive data.

- **Home Page:** The user-friendly home page offers multiple functionalities:

  - i) **Student Management System:** Allows you to save, capture photos, update, delete, and clear student records.

  - ii) **Train Photo Samples:** Enables the training of photo samples for facial recognition.

  - iii) **Take Attendance with Face Detection:** Effortlessly take attendance using face detection technology.

  - iv) **Attendance Report Generation:** Generate attendance reports in both Excel files and MySQL databases.

  - v) **Exit:** Gracefully exit the application.

### ▷ Algorithms Used:

- **Haarcascade OpenCV (Object Detection):** Used for object detection, particularly for detecting faces.

- **LBPH OpenCV (Face Recognition):** Employed for facial recognition.

## Deployment

Follow these steps to set up and deploy the Smart Attendance System Using Face Recognition project on your local machine:

### Prerequisites

Make sure you have the following prerequisites installed on your system:

- Python 3.x (Recommended: Python 3.7 or higher)
- `pip` package manager

### Clone the Repository

First, clone this repository to your local machine using the following command:

```bash
git clone https://github.com/sanjay-munde/Smart-Attendance-System-Using-Face-Recognition.git
```

### Install Dependencies

Navigate to the project directory:

```bash
cd Smart-Attendance-System-Using-Face-Recognition
```

Install the required dependencies by running:

```bash
pip install -r requirements.txt
```

This will install the necessary packages: OpenCV, NumPy, and opencv-contrib-python.

### Start the Server

Run the following command to start the server for the attendance system:

```bash
python login.py
```

The server will begin running, and you will see output indicating that it's up and running. This will usually include information about the server's IP address and port number.

### Access the System

Open your web browser and enter the following URL:

```
http://localhost:5000
```

This will take you to the home page of the Smart Attendance System.

### Usage

1. Log in using the provided secure login system with your username and password.
2. Utilize the various functionalities available on the home page:
   - Manage student records (save, capture photos, update, delete, clear).
   - Train photo samples for facial recognition.
   - Take attendance using face detection.
   - Generate attendance reports in Excel files and MySQL databases.
   - Gracefully exit the application.

### Database Setup

The project uses MySQL for database management. Refer to the [MySQL documentation](https://dev.mysql.com/doc/) for instructions on setting up and configuring MySQL on your system.

Feel free to reach out if you encounter any issues or require further assistance with deploying the system.
