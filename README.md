# **Django Authentication API with TDD & Flake8**  

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue)](https://www.python.org/)
[![Django](https://img.shields.io/badge/Django-4.2%2B-green)](https://www.djangoproject.com/)
[![Django REST](https://img.shields.io/badge/Django%20REST-3.14%2B-red)](https://www.django-rest-framework.org/)
[![Docker](https://img.shields.io/badge/Docker-✓-blue)](https://www.docker.com/)
[![TDD](https://img.shields.io/badge/TDD-✓-brightgreen)](https://en.wikipedia.org/wiki/Test-driven_development)
[![Flake8](https://img.shields.io/badge/Flake8-✓-yellow)](https://flake8.pycqa.org/)

🔒 **Django Authentication API** is a secure and production-ready authentication system built with **Django REST Framework**, featuring **Token authentication**, **user registration**, **email verification**, and **password reset**. The project follows **Test-Driven Development (TDD)** principles and enforces **code quality** with **Flake8 linting**.  

🚀 **Dockerized** for easy setup and consistent development environments.  

---

## **📌 Key Features**  
✔ **Token Authentication** (Access & Refresh Tokens)  
✔ **Custom User Model** (Extensible for additional fields)  
✔ **Test-Driven Development (TDD)** with `pytest`  
✔ **Flake8 Linting** for PEP8 compliance  
✔ **Docker & Docker Compose** for seamless deployment  
✔ **PostgreSQL** support (with environment variables)  

---

### **Prerequisites**  
- Python 3.10+  
- Docker & Docker Compose  
- PostgreSQL (or SQLite for development)  

The API will be available at:  
🌐 **http://localhost:8000/api/**  

---

## **🧪 Testing & Code Quality**  

### **Run Tests (TDD Approach)**  
```bash
docker-compose run --rm app sh -c "python manage.py test"  # Inside Docker
```

### **Flake8 Linting**  
```bash
flake8 .
```

---

## **📂 Project Structure**  
```plaintext
DjangoAuthenticationAPI_withTDD_and_Flake8/
├── api/                     # Core authentication logic
│   ├── models.py            # Custom User model
│   ├── serializers.py       # DRF serializers
│   ├── views.py             # API endpoints
│   ├── tests/               # Unit & integration tests
│   └── ...
├── .env.example             # Environment template
├── docker-compose.yml       # Docker setup
├── Dockerfile               # Backend container config
├── requirements.txt         # Python dependencies
└── README.md                # Documentation
```

---

## **🔧 API Endpoints**  
http://localhost:8000/api/docs/ (see with Swagger, after you up server and build the app)

---

## **🤝 How to Contribute**  
1. **Fork** the repository  
2. Create a **feature branch** (`git checkout -b feature/new-endpoint`)  
3. **Commit** changes (`git commit -m "Add new feature"`)  
4. **Push** to the branch (`git push origin feature/new-endpoint`)  
5. Open a **Pull Request**  

---

## **📬 Contact**  
👤 **Thiago Klem**  
📧 thiagoparanhosklem@outlook.com  
🌐 [GitHub Profile](https://github.com/klemthiago)  

---

🚀 **Happy coding!** If you find this project useful, consider giving it a ⭐ on GitHub!
