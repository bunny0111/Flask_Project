# 📚 Flask Student Result Calculator

A simple Flask web application that calculates a student's average marks and displays the final result (Pass/Fail). This project demonstrates the fundamentals of Flask routing, HTML forms, template rendering, redirects, and handling GET/POST requests.

---

## 🚀 Features

- User-friendly HTML form for entering marks
- Calculates the average score of four subjects
- Displays the final result in a structured table
- Uses Flask routing and template rendering
- Demonstrates HTTP GET and POST methods
- Redirects using `url_for()` and `redirect()`

---

## 🛠️ Tech Stack

- **Backend:** Python, Flask
- **Frontend:** HTML5, CSS3
- **Template Engine:** Jinja2

---

## 📂 Project Structure

```
Flask_Project/
│
├── main.py                 # Main Flask application
├── README.md
│
├── templates/
│   ├── index.html          # Student marks input form
│   └── result.html         # Displays final result
│
├── static/
│   ├── css/
│   │   └── style.css
│   └── script/
│       └── script.js
│
└── .venv/                  # Virtual environment (optional)
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/bunny0111/Flask_Project.git
```

### 2. Navigate to the project

```bash
cd Flask_Project
```

### 3. Create a virtual environment (Optional)

**Windows**

```bash
python -m venv venv
venv\Scripts\activate
```

**Linux / macOS**

```bash
python3 -m venv venv
source venv/bin/activate
```

### 4. Install Flask

```bash
pip install flask
```

or

```bash
pip install -r requirements.txt
```

*(if a requirements.txt file is added later)*

### 5. Run the application

```bash
python main.py
```

---

## 🌐 Application Flow

1. Open the application in your browser.

```
http://127.0.0.1:5000/
```

2. Enter marks for:

- Science
- Mathematics
- C Programming
- Data Science

3. Click **Submit**.

4. The application calculates the average marks.

5. The result page displays:

| Score | Result |
|-------:|--------|
| 75 | PASS |
| 42 | FAIL |

---

## 📌 Flask Concepts Demonstrated

- Flask Application Initialization
- Routing (`@app.route`)
- Dynamic URL Parameters
- HTML Forms
- HTTP GET & POST Requests
- Request Object
- Template Rendering
- Redirects
- `url_for()` Function
- Jinja2 Templates

---

## 📸 Screenshots

### Home Page

> Add a screenshot of the marks entry form here.

### Result Page

> Add a screenshot of the result page here.

---

## 🔮 Future Improvements

- Input validation
- Better UI using Bootstrap
- Store student records in a database
- User authentication
- Subject-wise grade calculation
- Responsive design
- Export results as PDF
- REST API support

---

## 📖 Learning Objectives

This project is suitable for beginners learning Flask and covers:

- Flask basics
- Template rendering
- Form handling
- Request processing
- Redirects
- Dynamic routing
- Basic project structure

---

## 👨‍💻 Author

**Bunny0111**

GitHub: https://github.com/bunny0111

---

## 📄 License

This project is created for educational and learning purposes.
Feel free to fork, modify, and use it for practice.

---

⭐ If you found this project helpful, consider giving it a **Star** on GitHub.
