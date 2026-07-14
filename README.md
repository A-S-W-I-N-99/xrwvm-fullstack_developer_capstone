# Car Dealership Application

## Project Description

The Car Dealership Application is a Full Stack web application developed as part of the IBM Full Stack Software Developer Capstone Project.

The application allows customers to browse car dealerships across the United States, filter dealerships by state, read customer reviews, create an account, log in securely, and submit reviews for dealerships. Customer reviews are analyzed using IBM Watson Natural Language Processing to determine sentiment.

---

## Features

- User Registration and Login
- Django Authentication
- View all Dealerships
- Filter Dealerships by State
- View Dealer Details
- View Customer Reviews
- Add New Reviews
- IBM Watson Sentiment Analysis
- React Frontend
- Django Backend
- Express.js Dealer API
- MongoDB Database
- SQLite Database
- Docker Containerization
- Kubernetes Deployment
- GitHub Actions CI/CD

---

## Technologies Used

### Frontend
- React
- Bootstrap
- JavaScript
- HTML5
- CSS3

### Backend
- Django
- Python
- Express.js
- Node.js

### Database
- SQLite
- MongoDB

### Cloud & DevOps
- Docker
- Kubernetes
- IBM Cloud Code Engine
- GitHub Actions

---

## Project Structure

```
ibm-fullstack_developer_capstone/
│
├── server/
│   ├── djangoapp/
│   ├── frontend/
│   ├── database/
│   ├── manage.py
│   └── requirements.txt
│
├── Dockerfile
├── deployment.yaml
├── README.md
└── .github/workflows/
```

---

## Installation

Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/ibm-fullstack_developer_capstone.git
```

Move into the project

```bash
cd ibm-fullstack_developer_capstone/server
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run migrations

```bash
python manage.py migrate
```

Start Django

```bash
python manage.py runserver
```

---

## Microservices

### Django Services

- `/get_cars`
- `/get_dealers`
- `/get_dealers/<state>`
- `/dealer/<id>`
- `/reviews/dealer/<id>`
- `/add_review`

### Express Services

- `/fetchDealers`
- `/fetchDealer/<id>`
- `/fetchReviews`
- `/fetchReviews/dealer/<id>`
- `/insertReview`

### Sentiment Analysis

- `/analyze/<text>`

---

## CI/CD

- GitHub Actions
- Docker
- Kubernetes Deployment

---

## Author

**Aswin S**

IBM Full Stack Software Developer Capstone Project
