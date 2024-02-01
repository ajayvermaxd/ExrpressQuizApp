
Quiz Application Frontend
This repository contains the frontend code for a Quiz Application API with User Management. The application is built using HTML, CSS, and JavaScript to provide a user-friendly interface for students and administrators.

Problem Statement
The goal is to extend the existing backend API to include user management functionalities. Users, including both students and administrators, should be able to sign up and log in. Administrators should also have the ability to manage quiz questions by adding and removing them.

Getting Started
Clone this repository to your local machine:

bash
Copy code
git clone https://github.com/your-username/quiz-app-frontend.git
Open the index.html file in your preferred web browser.

Features
User Authentication
Student Signup and Login: Students can create an account and log in with their credentials.
Admin Signup and Login: Administrators have separate signup and login functionalities.
Quiz Question Management
Add Question (Admin): Administrators can add new quiz questions.
Remove Question (Admin): Administrators can remove existing quiz questions.
Implementation Details
Mock Data Arrays
javascript
Copy code
// Mock User Data Array
const users = [
  { id: 1, username: 'student1', password: 'student1password', role: 'student' },
  { id: 2, username: 'student2', password: 'student2password', role: 'student' },
  { id: 3, username: 'admin1', password: 'admin1password', role: 'admin' }
];

// Mock Quiz Question Data Array
const quizQuestions = [
  {
    id: 1,
    question: 'What is the capital of France?',
    options: ['Paris', 'London', 'Berlin', 'Madrid'],
    correctOption: 0
  },
  {
    id: 2,
    question: 'Which planet is known as the Red Planet?',
    options: ['Mars', 'Venus', 'Jupiter', 'Mercury'],
    correctOption: 0
  },
  // Add more quiz questions
];
Testing
Test the complete API using tools like Postman to ensure that all implemented features work correctly. Test scenarios include login, signup, question management, and quiz functionalities.

By completing these tasks, you'll have a fully functional Quiz Application frontend that interacts seamlessly with the backend API, providing a comprehensive user experience for both students and administrators.