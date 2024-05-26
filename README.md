# Task Management System

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Available Scripts](#available-scripts)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Introduction
This Task Management System is a robust web application built using **React** and **Redux**. It provides users with the ability to create, edit, and manage tasks efficiently. The application focuses on maintaining a simple and clean user experience for better productivity.

## Features
- Add new tasks with ease
- Edit and update existing tasks
- Mark tasks as completed
- Filter tasks based on status (All, Completed, Pending)
- Persistent state management with Redux

## Installation
To set up the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/Ms-Ngari/task-management-system.git
   ```

2. Navigate to the project directory:
   ```bash
   cd task-management-system
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Start the development server:
   ```bash
   npm start
   ```

The app will be available at [http://localhost:3000](http://localhost:3000).

## Usage
1. Open the application in your web browser.
2. Add tasks using the input form.
3. Use the filters to view tasks by status.
4. Click on a task to mark it as completed or edit its details.

## Project Structure
```
.
├── public
├── src
│   ├── components
│   ├── features
│   │   └── tasks
│   ├── store
│   ├── App.js
│   └── index.js
└── package.json
```

- **components/**: Reusable UI components.
- **features/**: Redux slices and business logic.
- **store/**: Configuration for the Redux store.
- **App.js**: Main application component.
- **index.js**: Entry point of the application.

## Available Scripts
In the project directory, you can run:

### `npm start`
Runs the app in the development mode.

### `npm test`
Launches the test runner.

### `npm run build`
Builds the app for production.

### `npm run eject`
Ejects the project configuration (use with caution).

## Technologies Used
- **React**: Frontend framework
- **Redux**: State management
- **Redux Toolkit**: Simplified Redux setup
- **React Router**: Navigation management
- **CSS Modules/Tailwind**: Styling

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch-name`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch-name`).
5. Open a pull request.

## License
This project is licensed under the [MIT License](LICENSE).

