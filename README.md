# Project-Management

To run this project
npm install
npm run dev
This is a project management website build using react.

https://dreamy-taffy-56ff47.netlify.app/





# Project Management Application

## Overview

This project is a simple task and project management application built using React. It allows users to create projects, add tasks to the projects, and manage tasks and projects through an intuitive user interface.

## Features

1. **Add New Projects**: Users can create new projects by providing a title, description, and due date.
2. **Task Management**: Each project allows users to add and delete tasks.
3. **Project Selection**: Users can view tasks and details of the selected project from a sidebar displaying all projects.
4. **Delete Projects**: Users can delete selected projects.
5. **Modal**: If the user provides incomplete project data, an error modal is displayed.

## Components

### 1. `App`
This is the main component that maintains the state of projects and tasks. It handles the logic for adding, selecting, and deleting tasks and projects.

### 2. `NewProject`
This component provides a form to create a new project. It includes input fields for the project title, description, and due date, with a validation check.

### 3. `SelectedProject`
Displays the details of the selected project, including the tasks, and allows users to delete the project or add new tasks.

### 4. `ProjectsSidebar`
A sidebar that lists all available projects. Users can select a project or create a new one.

### 5. `Tasks`
This component displays the list of tasks in the selected project and allows users to add or delete tasks.

### 6. `NoProjectSelected`
This component displays a message when no project is selected and provides an option to create a new project.

### 7. `Modal`
A reusable modal component used to display error messages when required fields are left empty during project creation.

### 8. `Button`
A reusable button component used throughout the app.

### 9. `Input`
A reusable input component used for project creation, supporting both text input and textarea.

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd project-management-app
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Open the application in your browser at `http://localhost:3000`.

## Usage

- **Create a New Project**: Click "Create Project" from the sidebar, fill in the project details, and click "Save."
- **Add Tasks**: In a selected project, type in the task details and click "Add Task."
- **Delete Task**: Click the "Clear" button next to a task to delete it.
- **Select a Project**: Click on a project from the sidebar to view or manage tasks.
- **Delete Project**: Click "Delete" in the selected project to remove the project.

## Folder Structure

```
src/
  ├── components/
  │   ├── Button.jsx
  │   ├── Input.jsx
  │   ├── Modal.jsx
  │   ├── NewProject.jsx
  │   ├── NewTask.jsx
  │   ├── NoProjectSelected.jsx
  │   ├── ProjectsSidebar.jsx
  │   ├── SelectedProject.jsx
  │   ├── Tasks.jsx
  ├── assets/
  ├── App.jsx
  ├── index.js
```

## Dependencies

- React
- React DOM

