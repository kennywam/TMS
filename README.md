# Task Management System

A web-based application built with React, TypeScript, and C# ASP.NET Core for efficient task management. This application allows users to create, manage, and track tasks with various features like task creation, editing, sorting, filtering, notifications, and more.

## Features

- User Registration and Login
- Create, Edit, and Delete Tasks
- Task Sorting and Filtering
- Task Details and Deadline Notifications
- User Profile Customization
- Search Functionality 
- Data Visualization

## Technologies Used

- Frontend: React, TypeScript, HTML, CSS
- Backend: C# ASP.NET Core
- Database: SQL Server
- Authentication: JWT (JSON Web Tokens)
- Frontend State Management: Redux or React Context
- API Requests: Axios
- Data Validation: FluentValidation (C#), Formik (React)
- Testing: Jest, React Testing Library (for unit tests)

## Getting Started

1. Clone this repository: `git clone https://github.com/kennywam/TMS.git`
2. Navigate to the project directory: `cd task-management-system`
3. Set up the backend (C# ASP.NET Core): Refer to backend-setup.md for instructions on the backend repo.
4. Set up the frontend (React): Refer to frontend-setup.md for instructions.
5. Start both the backend and frontend development servers.

## Directory Structure

- `src/` contains the frontend source code.
  - `components/` houses all React components.
  - `styles/` includes CSS styles.
  - `services/` contains the API service (Axios requests).
  - `contexts/` for React context setup.
- `backend/` contains the C# ASP.NET Core project files.
- `tests/` holds unit tests for your application.

## Usage

1. Register a new user account or log in.
2. Create tasks with titles, descriptions, deadlines, and categories.
3. Edit, mark as complete, or delete tasks as needed.
4. Use sorting, filtering, and search features to manage your tasks.
5. Customize your user profile and set up task notifications.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork this repository.
2. Create a new branch for your feature or bug fix: `git checkout -b feature/your-feature-name`
3. Commit your changes: `git commit -m "Add your feature description"`
4. Push to the branch: `git push origin feature/your-feature-name`
5. Open a pull request to the `main` branch.

## License

This project is licensed under the MIT License. Feel free to use and modify it according to your needs.

## Acknowledgements

- This project was inspired by [Carolyne Ndunge](https://github.com/cashy-tech).
- Special thanks to [Cashy](https://github.com/cashy-tech) for her contributions.

