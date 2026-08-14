# FastAPI Calculator

A modern web-based calculator application built with **FastAPI**, **HTML5**, **CSS3**, and **JavaScript**. The project demonstrates how a FastAPI backend can be integrated with a responsive frontend to perform mathematical calculations through a simple and user-friendly interface.

## 🚀 Features

- Basic arithmetic operations
- Addition, subtraction, multiplication, and division
- Clean and responsive user interface
- FastAPI-powered backend
- Interactive JavaScript frontend
- Static file handling with FastAPI
- Jinja2 template rendering
- Lightweight and easy to deploy
- Structured project architecture

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Backend programming |
| FastAPI | Web framework and API backend |
| Uvicorn | ASGI server |
| Jinja2 | HTML template rendering |
| HTML5 | Webpage structure |
| CSS3 | User interface styling |
| JavaScript | Frontend interaction |
| Git & GitHub | Version control and project hosting |

## 📂 Project Structure

```text
fastapi-calculator/
│
├── main.py
├── requirements.txt
├── .gitignore
│
├── templates/
│   └── index.html
│
└── static/
    ├── style.css
    └── script.js

⚙️ Installation & Setup
1. Clone the Repository
git clone https://github.com/nitaj3876-pixel/fastapi-calculator.git
2. Navigate to the Project
cd fastapi-calculator
3. Create a Virtual Environment
python -m venv .venv
4. Activate the Virtual Environment

Windows:

.venv\Scripts\activate

macOS / Linux:

source .venv/bin/activate
5. Install Dependencies
pip install -r requirements.txt
▶️ Run the Application

Start the FastAPI development server:

uvicorn main:app --reload

The application will be available at:

http://127.0.0.1:8000

Open the URL in your web browser to use the calculator.

📡 API

FastAPI automatically provides interactive API documentation.

Swagger UI
http://127.0.0.1:8000/docs
ReDoc
http://127.0.0.1:8000/redoc
🌐 Deployment

This project can be deployed using cloud platforms such as Render.

Render Configuration

Build Command:

pip install -r requirements.txt

Start Command:

uvicorn main:app --host 0.0.0.0 --port $PORT
🔒 Project Structure & Best Practices

The project follows a simple separation of responsibilities:

main.py — FastAPI backend and application routes
templates/ — HTML templates
static/ — CSS and JavaScript assets
requirements.txt — Python dependencies
.gitignore — Prevents unnecessary files such as virtual environments from being committed
🎯 Project Objective

The main objective of this project is to demonstrate the development of a lightweight web application using FastAPI and to understand backend–frontend integration, template rendering, static file management, and web application deployment.

🔮 Future Enhancements

Possible improvements include:

Scientific calculator functions
Calculation history
Keyboard input support
Dark/light theme
REST API endpoints
User authentication
Database integration
Advanced mathematical operations
Improved mobile responsiveness
👨‍💻 Author

Nitaj

GitHub:
https://github.com/nitaj3876-pixel

📄 License

This project is created for educational and development purposes.
