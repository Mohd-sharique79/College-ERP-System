# COLLEGE ERP SYSTEM

College ERP using MERN Stack

Overview
The College ERP system is a comprehensive solution built using the MERN stack to streamline and automate processes such as student and faculty management, course scheduling, attendance tracking, and more. This project leverages modern web technologies to deliver a seamless experience for administrators, faculty, and students, ensuring efficient management of academic and administrative tasks.

# Setup
1. Create a .env file in server folder.
    - Example of .env file
    - CONNECTION_URL=mongodb+srv://username:<Password>@cluster0.tuuez.mongodb.net/?retryWrites=true&w=majority&appName=Cluster0
    - PORT=5001
2. Copy the content of .env.example to the newly created .env file
3. Change the MONGODB_URI to your MongoDB atlas URI
4. Open a terminal in client folder and run "npm run start"
5. Open another terminal in server folder and run "npm run start"
6. Go to "localhost:3000/login/adminlogin"
7. After successfully running the server, a dummy admin should be created.
8. Dummy admin username = ADMDUMMY, password = 123

# TechStack

1. Frontend: React.js, Tailwind CSS, Material UI Icons
2. Backend: Node.js, Express.js
3. Database: MongoDB
4. State Management: Redux
5. Authentication: JSON Web Tokens (JWT)

# Features

- Admin
1. Manage students, faculty, and other admins (Add, Delete, View).
2. Add new departments, courses, and subjects.
3. Create and manage notices.
4. Update profile details and change passwords.

- Faculty
1. Update profile details and change passwords.
2. Create new tests, mark attendance, and upload test marks.

- Student
1. Update profile details and change passwords.
2. View attendance, marks, and subject lists.

- General Features
1. Modern user interface with intuitive navigation.
2. Error handling with form validation.
3. JWT-based secure authentication.
4. Role-based access control (Admin, Faculty, Student).

# Features to be added later in the future

1. Mobile Responsiveness
2. Sections other than academics
3. More freedom to admin while adding new students,admins,faculties or subjects

# Setup Instructions

1. https://github.com/Mohd-sharique79/College-Erp-System

2. Clone the above repo

3. Set up the environment variables:
    - Navigate to the server folder and create a .env file.
    - Copy the content from .env.example into the .env file.
    - Update MONGODB_URI with your MongoDB Atlas URI.

4. Install dependencies:

    - For the client:
        - bash
        - Copy code
        - cd client
        - npm install

    For the server:
        - bash
        - Copy code
        - cd server
        - npm install

5. Run the application:

    - Start the client:
        - bash
        - Copy code
        - cd client
        - npm start
    - Start the server:
        - bash
        - Copy code
        - cd server
        - npm start

6. Access the application:

    - Open your browser and go to http://localhost:3000/login/adminlogin.
    - Use the dummy admin credentials to log in:
    - Username: ADMDUMMY
    - Password: 123


# Roles and Responsibilities as a Frontend Developer
- Developed rich interactive user interfaces using React.js and Tailwind CSS to create a modern and intuitive user experience.
- Collaborated with the design team to implement website mockups and wireframes, ensuring consistency in UI/UX design.
- Assisted with cross-browser testing, debugging issues in various browsers to ensure compatibility and responsiveness.
- Optimized web applications for multiple devices and screen sizes using responsive design techniques.
- Integrated front-end components with back-end services through RESTful APIs, ensuring seamless functionality across the application.
- Implemented role-based access control (RBAC) to manage permissions and user-specific functionalities.

# Future Enhancements
- Mobile responsiveness for all pages.
Expanding the scope to include non-academic sections.
- Allowing more customization options for admins while managing entities like students, faculties, and subjects.