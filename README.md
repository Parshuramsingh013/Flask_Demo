# Flask App Routing Demo
This repository contains a simple Flask application that demonstrates basic routing, variable rules, form handling, and API creation. This project is a beginner-friendly introduction to Flask, showcasing how to build a web application that can handle different routes, process user input from forms, and return JSON responses through an API.
---
---
## Features
### 1. Welcome Page
- **Route**: '/'
- **Method**: 'GET'
- **Description**: The home page of the application, welcoming users with a simple message.

### 2. Index Page
- **Route**: '/index'
- **Method**: 'GET'
- **Description**: A secondary page that provides a welcome message.

### 3. Success and Fail Pages
- **Route**: '/success/<int:score> and /fail/<int:score>'
- **Method**: 'GET'
- **Description**: Dynamic routes that display a message based on a user's score, indicating whether they have passed or failed.

### 4. Form Handling and Result Calculation
- **Rout**e: '/form'
- **Method**: 'GET', 'POST'
- **Description**:
  - **GET**: Renders a form where users can input their marks for Maths, Science, and History.
  - **POST**: Calculates the average marks based on the form input. If the average is 50 or above, the user is redirected to the success page; otherwise, they are redirected to the fail page.

### 5. API for Sum Calculation
- **Route**: '/api'
- **Method**: 'POST'
- **Description**: An API endpoint that receives two values (a and b) in JSON format and returns their sum.

--- 

## How to Run the Project

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/flask-app-routing-demo.git
   cd flask-app-routing-demo

2. **Install the Dependencies**
   ```bash
   pip install Flask

3. **Run the Application**
   ```bash
   python app.py