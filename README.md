
# 🧩 Kanban Board App

## Description

### What is the project motivation?
This project was developed to implement a secure and private task management system that uses a Kanban board layout. It allows authenticated users to visualize and organize their tasks efficiently. The main goal was to combine user authentication using JSON Web Tokens (JWT) with a modern, interactive front-end experience.

### Why did you build this project?
To create a full-stack application where users can log in and access a personal or shared Kanban board. It also served as a practice project to strengthen my knowledge in authentication, protected routes, state management, and UI/UX in web applications.

### What problem does it solve?
This application solves the need for a private, easy-to-use task management tool. It ensures that only authenticated users can access or manipulate data, providing a centralized and secure solution to manage ongoing projects or to-do items.

### What did you learn?
- JWT-based authentication and secure session handling.
- Protecting API routes and frontend views based on authentication state.
- State management across components using React hooks.
- Handling forms and real-time updates in a React app.
- Creating drag-and-drop interactions for tasks in a Kanban layout.
- Structuring and deploying a full-stack app with modern tools.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Contributing](#contributing)
- [Test](#test)
- [License](#license)
- [Questions](#questions)
- [Deployed Page](#deployed-page)

## Installation

To install the project, run the following command to clone the repository:

```sh
git clone https://github.com/DoctorLeQuack1/KanbanBoard
```

Then, navigate to the project folders and install the dependencies:

```sh
# Backend installation
npm install
```

## Usage

To start the application locally, use the following commands:

```sh
npm run start:dev
```

### Features

- **Login with JWT:** Secure login system using JWT to authenticate users.
- **Protected API and frontend routes:** Only users with valid tokens can access the board.
- **Kanban Board Layout:** Tasks are displayed in draggable columns (To Do, In Progress, Done).
- **Task Creation & Management:** Users can create, edit, delete, and move tasks across columns.
- **Responsive Design:** Fully responsive layout built with Tailwind CSS.
- **Modern UI:** Clean, minimalist design focused on usability and accessibility.

## Contributing

Currently, contributions are not actively being accepted. However, feel free to fork the repository and submit a pull request if you'd like to suggest improvements or add features.

## Test

Testing is currently not implemented but is planned for future development. The next phase will include:
- Unit tests for API routes
- Integration tests for frontend components
- End-to-end testing for login and task management flows

## License

This project is covered under the MIT License. For more information, visit:  
[MIT License](https://opensource.org/licenses/MIT)

## Questions

Check out my other projects on GitHub: [DoctorLeQuack1](https://github.com/DoctorLeQuack1)  
For any questions regarding this project, feel free to reach out to me at:  
📧 [sergioa430@gmail.com](mailto:sergioa430@gmail.com)

## Deployed Page

You can access the deployed version of the Kanban app at:  
🌐 [Kanban Board App](https://sergio-web-portfolio.web.app/)
