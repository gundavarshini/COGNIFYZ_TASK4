# COGNIFYZ_TASK4

Complex Form Validation & Dynamic DOM Manipulation

📌 Project Overview

This project is Level 2 – Task 4 of the Cognifyz Technologies internship. It demonstrates a professional registration interface with complex form validation, dynamic DOM manipulation, real-time user feedback, and client-side routing.

The application is designed to provide a smooth and interactive registration experience while validating user inputs using JavaScript.

🎯 Objectives

Implement advanced form validation rules.

Validate password strength in real time.

Provide immediate feedback for invalid inputs.

Dynamically update webpage elements using JavaScript.

Implement client-side navigation without unnecessary page reloads.

Create a clean, responsive, and user-friendly interface.


✨ Key Features

1. Complex Form Validation

The registration form validates:

Full Name

Email Address

Phone Number

Password

Confirm Password

Terms & Conditions


2. Password Strength Validation

The password must satisfy the following requirements:

At least 8 characters

At least one uppercase letter

At least one lowercase letter

At least one number

At least one special character


The password requirements are displayed dynamically to help users create a strong password.

3. Dynamic DOM Manipulation

JavaScript is used to dynamically:

Display validation messages

Update password strength indicators

Show or hide passwords

Update interface elements based on user actions

Provide real-time feedback


4. Client-Side Routing

The application provides navigation between:

🏠 Home

📝 Register

ℹ️ About


Navigation is handled on the client side without unnecessary page reloads, providing a smoother user experience.

🛠️ Technologies Used

HTML5 – Structure of the web pages

CSS3 – Styling and responsive design

JavaScript – Form validation and DOM manipulation

Node.js – Server-side environment

Express.js – Web application framework

EJS – Dynamic HTML templating


📂 Project Structure

project/
│
├── public/
│   ├── css/
│   │   └── style.css
│   └── js/
│       └── script.js
│
├── views/
│   ├── index.ejs
│   ├── register.ejs
│   └── about.ejs
│
├── app.js
├── package.json
└── README.md

> Update the file names above if your actual project structure is different.



⚙️ How to Run the Project

1. Clone the repository

git clone <YOUR-GITHUB-REPOSITORY-LINK>

2. Navigate to the project folder

cd <PROJECT-FOLDER>

3. Install dependencies

npm install

4. Start the application

node app.js

Or, if your project uses a start script:

npm start

5. Open in browser

http://localhost:5000

🧪 Validation Flow

User enters details
        ↓
Form validation starts
        ↓
Check name, email & phone
        ↓
Check password strength
        ↓
Confirm password matching
        ↓
Check Terms & Conditions
        ↓
All conditions satisfied?
      /     \
    No       Yes
    ↓         ↓
Show error   Create Account
message      successfully

📸 Project Screens

The project includes:

Home Page – Introduction to the application and key features.




Registration Page – Advanced registration form with password validation.

About Page – Information about the task, features, and technologies used.


📚 Learning Outcomes

Through this task, I gained practical experience in:

JavaScript form validation

Regular expressions

DOM manipulation

Event handling

Password-strength validation

Client-side routing

EJS templating

Express.js

Building interactive web interfaces

Improving user experience through real-time feedback

👩‍💻 Internship Task

Organization: Cognifyz Technologies

Level: Level 2 – Intermediate

Task: Task 4 – Complex Form Validation and Dynamic DOM Manipulation

🚀 Future Enhancements

Connect the registration form to a database.

Add user authentication and login functionality.

Implement email verification.

Add stronger security and server-side validation.

Improve accessibility and mobile responsiveness.


📄 License

This project was developed for educational and internship purposes as part of the Cognifyz Technologies internship program.
