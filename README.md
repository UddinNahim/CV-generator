# 🧾 CV Generator

A web application built with **Django**, **HTML**, **CSS**, and **Bootstrap** that allows users to quickly create and download a professional CV in **PDF format** using **pdfkit**.

---

## 📚 Table of Contents
- [About](#about)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## 🧩 About

**CV Generator** is a simple and user-friendly web application designed to help users create professional CVs instantly.  
Users can fill out their personal details, education, and experience — and with one click, generate a downloadable **PDF version** of their CV.

---

## 🚀 Features

- 📝 Fill out personal information through a web form  
- ⚡ Instantly generate a CV in PDF format  
- 💻 Responsive design using Bootstrap  
- 🧱 Built with Django and pdfkit  
- 🎯 Easy to use and customizable  

---

## 🛠️ Tech Stack

| Layer | Technologies |
|--------|----------------|
| **Frontend** | HTML, CSS, Bootstrap |
| **Backend** | Django (Python) |
| **PDF Engine** | pdfkit (wkhtmltopdf) |
| **Database** | SQLite (default) |

---

## ⚙️ Installation

### 1️⃣ Clone the repository
```bash
git clone (https://github.com/UddinNahim/CV-generator.git)
cd CV-generator

###  2️⃣ Create and activate a virtual environment
```bash
python -m venv venv
venv\Scripts\activate   # Windows
source venv/bin/activate  # macOS/Linux

###  3️⃣ Install dependencies
```bash
pip install -r requirements.txt
###  4️⃣ Install wkhtmltopdf

You must install wkhtmltopdf to use pdfkit.
Follow installation instructions from:
👉 https://github.com/JazzCore/python-pdfkit/wiki/Installing-wkhtmltopdf

### 5️⃣ Run the Django server
```bash
python manage.py runserver

```
Open your browser and visit:
🔗 http://127.0.0.1:8000/

## 💻 Usage

Open the CV Generator web app.

Fill in your Name, Email, Phone, Education, Experience, and Skills.

Click Generate CV.

Your CV will automatically download as a PDF file.

## 📸 Screenshots

Add screenshots of your app here:

![Homepage](image/CV_input_Form.png)
![Generated CV](image/generates cv.png)

## 🤝 Contributing

Contributions are welcome!
To contribute:

1. Fork the repository
2. Create a new branch (git checkout -b feature-name)
3. Make your changes and commit (git commit -m 'Add feature')
4. Push to your branch (git push origin feature-name)
5. Open a Pull Request

## 📜 License

This project is licensed under the MIT License — feel free to use and modify it.

## 📞 Contact

Author: Nahim Uddin
GitHub: https://github.com/UddinNahim
LinkedIn: https://www.linkedin.com/in/nahimuddin/ 
Email: nahim.211902019@gmail.com
