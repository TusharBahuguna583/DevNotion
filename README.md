# Dev Notion

Dev Notion is an ED Tech (Education Technology) web application developed using the MERN stack.

## Note

This project is intended as a learning tool and can be used as a sample project for educational or personal projects.

---

## Features

- User Authentication: Dev Notion provides secure user registration and authentication using JWT (JSON Web Tokens). Users can sign up, log in, and manage their
  profiles with ease.
- Courses and Lessons: Instructors can create and edit created courses. Students can enroll in courses, access course materials, and track their progress.
- Progress Tracking: Dev Notion allows students to track their progress in enrolled courses. They can view completed lessons, scores on quizzes and
  assignments, and overall course progress.
- Payment Integration: Dev Notion integrates with Razorpay for payment processing. Users can make secure payments for course enrollment and other services
  using various payment methods supported by Razorpay.
- Search Functionality: Users can easily search for courses, lessons, and resources using the built-in search feature. This makes it convenient to find relevant
  content quickly.
- Instructor Dashboard: Instructors have access to a comprehensive dashboard to view information about their courses, students, and income. The
  dashboard provides charts and visualizations to present data clearly and intuitively. Instructors can monitor the total number of students enrolled in
  each course, track course performance, and view their income generated from course sales.

---

## Screenshots

![Screenshot 2023-07-25 210844](https://github.com/TusharBahuguna583/DevNotion/blob/main/src/assets/Screenshot%202025-06-06%20215013.png)
![Screenshot 2023-07-25 211309](https://github.com/TusharBahuguna583/DevNotion/blob/main/src/assets/Screenshot%202025-06-06%20215400.png)

<details>
  <summary>More screenshots</summary>
  
![Screenshot 2023-07-25 211451](https://github.com/TusharBahuguna583/DevNotion/blob/main/src/assets/Screenshot%202025-06-06%20215827.png)
![image](https://github.com/TusharBahuguna583/DevNotion/blob/main/src/assets/Screenshot%202025-06-06%20215713.png)
</details>

---

## Important

- Backend is in the server folder.
- Before uploading courses and anything create the categories e.g. web dev, Python, etc. (without categories courses cannot be added). To create categories create an Admin account and go to dashboard then admin panel.
- To create an Admin account first sign up with a student or instructor account then go to your Database under the users model and change that 'accountType' to 'Admin'.

## Installation

1. Clone the repository to your local machine.

   ```sh
   git clone https://github.com/TusharBahuguna583/DevNotion
   ```

2. Install the required packages.

   ```sh
   cd DevNotion
   npm install

   cd server
   npm install
   ```

3. Set up the environment variables:

   Create a .env file in the root directory and /server
   Add the required environment variables, such as database connection details, JWT secret, and any other necessary configurations check .env.example files for more info.

4. Start the development server.

   ```sh
   npm run dev
   ```

5. Open the project in your browser at [`http://localhost:3000`](http://localhost:3000) to view your project.

The project is set up to use `postcss-cli` to process your CSS files. You can add your own `tailwind.config.js` file to customize your Tailwind setup.
