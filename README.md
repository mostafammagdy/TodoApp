# TodoApp

![image](https://github.com/mostafammagdy/TodoApp/assets/43654437/fec3dc91-827d-4967-bbd5-fd8c6dcff785)
<!-- Replace with an actual screenshot if available -->

TodoApp is a minimalistic task management application built using the MERN stack (MongoDB, Express.js, React, Node.js). It allows users to create, manage, and complete tasks effectively.

## Features

- **Task List:** View a list of tasks with options to mark them as complete and delete tasks.
- **Add Task:** Easily add new tasks to the list with a user-friendly interface.
- **Task Completion:** Mark tasks as complete or incomplete with a single click.
- **Responsive Design:** Enjoy a seamless experience on different devices with a responsive layout.
- **Real-time Updates:** Changes to tasks (completion status, addition, deletion) are reflected instantly.

## Getting Started

To run TodoApp locally on your machine, follow these steps:

### Prerequisites

- Node.js and npm installed. You can download them from [here](https://nodejs.org/).
- MongoDB running locally or accessible through a connection string.

### Installation

1. Clone the repository: `git clone https://github.com/mostafammagdy/TodoApp.git`
2. Navigate to the project directory: `cd TodoApp`
3. Install dependencies for the frontend and backend:
   - For the frontend:
     ```sh
     cd client
     npm install
     ```
   - For the backend:
     ```sh
     cd api
     npm install
     ```
4. Configure MongoDB:
   - Modify the MongoDB connection string in `backend/server.js` to match your setup.

5. Run the application:
   - Start the frontend development server:
     ```sh
     cd client
     npm start
     ```
   - Start the backend server:
     ```sh
     cd api
     npm start
     ```

6. Access the app in your web browser at `http://localhost:3000`.

## API Endpoints

The backend server handles API requests for managing tasks. Here are the available endpoints:

- `GET /todos`: Get a list of all tasks.
- `POST /todo/new`: Add a new task.
- `DELETE /todo/delete/:id`: Delete a task by ID.
- `GET /todo/complete/:id`: Mark a task as complete or incomplete.

## Contributing

Contributions are welcome! To contribute, follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature-name`
3. Make your changes and test them thoroughly.
4. Commit your changes: `git commit -m "Add your commit message"`
5. Push to your branch: `git push origin feature/your-feature-name`
6. Create a Pull Request detailing your changes.

Please follow coding conventions and provide clear commit messages.
You can freely use and modify the code.

## Acknowledgments

- Inspiration for this project came from various open-source Todo applications, including:
  - [Complete-MERN-TODO-app](https://github.com/SamiurRahmanMukul/Complete-MERN-TODO-Application)
  - [MERN Tasks App](https://github.com/Azim-Ahmed/MERN--TODO)

---

Feel free to [open an issue](https://github.com/mostafammagdy/TodoApp/issues) for any questions, feedback, or bug reports. I hope TodoApp simplifies your task management process!

