# 🎓 Face Recognition Attendance System

A comprehensive **face recognition-based attendance system** that automates the process of marking attendance using **computer vision**, **machine learning**, and **web technologies**.

---

![Face Recognition](https://img.shields.io/badge/Face-Recognition-blue)
![Python](https://img.shields.io/badge/Python-3.8%2B-green)
![OpenCV](https://img.shields.io/badge/OpenCV-4.5%2B-orange)
![System](https://img.shields.io/badge/System-Attendance-brightgreen)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)
![jQuery](https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white)
![XAMPP](https://img.shields.io/badge/XAMPP-FB7A24?style=for-the-badge&logo=xampp&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-0078D4?style=for-the-badge&logo=visualstudiocode&logoColor=white)

---

## 📋 Table of Contents
- [Overview](#-overview)
- [Features](#-features)
- [Installation](#-installation)
- [Python Libraries Used](#-python-libraries-used)
- [Usage](#-usage)
- [Applications](#-applications)
- [Project Structure](#-project-structure)
- [Technologies Used](#-technologies-used)
- [Contributing](#-contributing)
- [License](#-license)
- [Contact](#-contact)
- [Important Notes](#-important-notes)
- [Future Enhancements](#-future-enhancements)

---

## 🎯 Overview
The **Face Recognition Attendance System** replaces traditional manual attendance with an **automated, contactless, and accurate** solution.  
Using advanced **facial recognition algorithms**, the system identifies individuals and records their attendance in **real-time**.

---

## ✨ Features
- 🕵️ **Real-time Face Detection:** Detect faces via live webcam feed  
- 👤 **Face Recognition:** Identify individuals using trained ML models  
- 🕒 **Automated Attendance:** Instantly mark attendance when faces are recognized  
- 📊 **Data Export:** Export attendance reports in CSV, Excel, or PDF  
- 👥 **User Management:** Add, edit, and manage employee/student profiles  
- 💻 **Cross-Platform:** Works on Windows, Linux, and macOS  
- 🗃️ **Database Integration:** Secure MySQL backend for storing attendance  
- 🔊 **Voice Feedback:** Announces attendance success using `pyttsx3`  
- 🧾 **Reports:** Generate analytics and insights for management or teachers  

---

## 🚀 Installation

### **Prerequisites**
- Python **3.8 or higher**
- A working **Webcam**
- Installed **XAMPP / WAMP** for PHP & MySQL backend
- Required Python libraries (see below or use `requirements.txt`)

---

### **Step-by-Step Installation**

```bash
# Clone the repository
git clone https://github.com/sakib92s/FACE-RECOGNITION-ATTEDENCE-SYSTEM.git
cd FACE-RECOGNITION-ATTEDENCE-SYSTEM

# Create a virtual environment (recommended)
python -m venv venv

# Activate it
# On Windows
venv\Scripts\activate
# On Linux/Mac
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt
