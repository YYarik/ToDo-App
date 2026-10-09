# ToDo-App — Task Management App

A responsive and modern Todo application created for managing daily tasks. This project was built to demonstrate the practical application of React, TypeScript, and Bulma CSS. It is fully adaptive, handles dynamic API operations (CRUD), and provides a seamless user experience across mobile, tablet, and desktop devices.

DEMO LINK (https://YYarik.github.io/ToDo-App/)

🚀 How to run locally

To run this project on your local machine, follow these steps:

Clone the repository:
```bash
git clone https://github.com/YYarik/ToDo-App.git
```

Navigate to the project folder:
```bash
cd ToDo-App
```

Install dependencies:
```bash
npm install
```

Start the development server:
```bash
npm start
```

## Technologies Used

### Frontend & Styling
- React (Functional components, Hooks)
- TypeScript (Static typing and safety)
- Bulma CSS (Responsive CSS framework)
- SCSS (Sass preprocessor for custom styles)

### API & State Management
- REST API integration for CRUD operations (GET, POST, PATCH, DELETE)
- Fetch API Client for asynchronous networking
- Dynamic UI states (loading spinners, disabled controls during requests)
- Error handling with dismissible notification banners

### Tooling & Testing
- Vite (Fast development server and bundling)
- Cypress (End-to-end testing)
- ESLint & Stylelint (Code linting and formatting standards)

## Project Features & Architecture
- **Interactive Editing**: Double-click to rename a task with automatic save on blur or Enter, and cancel on Escape.
- **Bulk Actions**: Select all tasks to toggle completion status, or clear all completed tasks with one click.
- **Client-Side Filtering**: Easily filter tasks by their completion status (All, Active, Completed).
- **Resilient UI**: Disables input fields and shows visual loading states during network requests to prevent duplicate submissions, with error notifications on API failure.
- **Adaptive Design**: Fully responsive layout designed to look great on screens of any size.
