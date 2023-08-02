# TodoList App in React and TypeScript
This is a simple TodoList application built using React and TypeScript. The app allows you to add, edit, delete, and mark tasks as completed. It also includes drag-and-drop functionality to reorder tasks and move completed tasks to a separate section.

## Instructions for Running the App
To run the TodoList app locally on your machine, follow these steps:

Make sure you have Node.js and npm (Node Package Manager) installed on your computer.

## Clone the repository or download the project files.

Open a terminal or command prompt and navigate to the project directory.

## Install the project dependencies by running the following command:

Copy code
npm install
After the installation is complete, start the development server:
sql
Copy code
npm start
The app will automatically open in your default web browser at http://localhost:3000.
Components

## The TodoList app consists of the following components:

App.tsx: The main component that handles the overall layout and state management of the app. It includes the InputField component for adding new tasks and the TodoList component for displaying the active and completed tasks.

InputField.tsx: A component responsible for rendering the input field and the "GO" button to add new tasks. It receives the todo, setTodo, and handleAdd props from the parent App component.

TodoList.tsx: This component renders the list of active tasks and the completed tasks. It receives the todos, setTodos, CompletedTodos, and setCompletedTodos props from the parent App component. It uses the SingleTodo component to render each individual task.

SingleTodo.tsx: A component responsible for rendering a single todo item. It allows the user to edit, delete, and mark the task as done. It uses the Draggable component from react-beautiful-dnd to enable drag-and-drop functionality for reordering tasks.

models.ts: Contains the interface definition for the Todo type, which represents the structure of a single todo item.

## Dependencies
The project uses the following external dependencies:

react: A JavaScript library for building user interfaces.
react-dom: Provides DOM-specific methods that can be used at the top level of your app.
react-scripts: A set of scripts and configuration used by Create React App.
react-beautiful-dnd: A library to create smooth and powerful drag-and-drop experiences for your React applications.
react-icons: Provides a set of customizable icons for your React applications.