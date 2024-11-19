# Project-Management-System

The MERN Stack Task Management Application project, available on the provided GitHub link, is a web-based application built using the MERN stack (MongoDB, Express.js, React.js, and Node.js). Here's a detailed explanation of the project:

Purpose This project is designed to help users manage tasks efficiently. It allows users to perform CRUD (Create, Read, Update, Delete) operations on tasks, ensuring seamless task management and tracking.

Key Features User Authentication: Implements a secure authentication system to register and log in users. Task Management: Add new tasks. Edit existing tasks. Delete tasks. Mark tasks as completed or pending. Responsive UI: Provides a user-friendly interface built with React.js. Real-Time Updates: Data updates dynamically on the front end as users interact with the application. Backend API: RESTful APIs built with Node.js and Express.js handle the application's core functionalities.

Technologies Used Frontend: React.js: For creating interactive user interfaces. CSS/Bootstrap: For styling and responsive design. Backend: Node.js: For server-side logic. Express.js: To build RESTful APIs. Database: MongoDB: For storing user and task data in a NoSQL format. Other Tools: JWT (JSON Web Token): For secure user authentication. Axios: For HTTP requests between the frontend and backend.

Project Structure Frontend: src/: Contains React components such as task forms, task lists, and authentication forms. App.js: Main application file managing routes and rendering components. Backend: routes/: Defines API endpoints for authentication and task management. models/: Contains MongoDB schemas for users and tasks. server.js: Main server file that initializes the application and connects to the database. Database: MongoDB stores user credentials and task details.

Workflow User Registration/Login: Users create an account or log in using existing credentials. JWT tokens are generated for session management. Task Operations: Authenticated users can add, edit, or delete tasks. Tasks are retrieved from the MongoDB database and displayed on the React frontend. State Management: Frontend uses state to manage task lists and user sessions, ensuring smooth interaction.

How to Run the Project Clone the Repository: bash Copy code git clone https://github.com/VikasPaspula/Project-Management-System.git cd MERN_STACK_TASK_MANAGEMENT_APPLICATION Install Dependencies: Backend: bash Copy code cd backend npm install Frontend: bash Copy code cd frontend npm install Set Up Environment Variables: Create a .env file in the backend folder with necessary configurations like MongoDB URI, JWT secret, etc. Run the Application: Backend: bash Copy code npm start Frontend: bash Copy code npm start Access the Application: Open the browser and navigate to http://localhost:3000.

Potential Enhancements Add role-based access control (e.g., admin and regular users). Introduce notifications or reminders for task deadlines. Enhance the UI/UX with animations and additional customization options. Integrate a calendar view for task management. Implement unit and integration tests for backend APIs and frontend components.


![Screenshot 2024-11-19 023407](https://github.com/user-attachments/assets/ce149ed8-90f0-4228-9619-9b295e4d8ae4)
![Screenshot 2024-11-19 023255](https://github.com/user-attachments/assets/230e93a4-dc68-4e7b-ba23-5de9d91463ed)
![Screenshot 2024-11-19 023837](https://github.com/user-attachments/assets/14d0b765-574b-41e2-a544-d1b80c280bc8)
![Screenshot 2024-11-19 023754](https://github.com/user-attachments/assets/effe6a64-416d-4ca1-bddd-ecd340dcf6f6)
![Screenshot 2024-11-19 023430](https://github.com/user-attachments/assets/ba3a533b-9626-4629-a160-72cef7e81fe5)

