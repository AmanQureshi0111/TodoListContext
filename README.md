# TodoListContext

A simple React + Vite based to-do list application using React Context for state management.
## Screenshot
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/82960cfb-d2d7-4d23-8804-a422657c7834" />

## Overview

This project is a lightweight to-do list app built with React and Vite. It demonstrates how to manage global state in a React application using the Context API, rather than prop drilling or using heavier state management libraries.

## Features

- Add, edit, and remove to-do items  
- Mark tasks as completed or incomplete  
- Persist tasks (if implemented, e.g. via `localStorage`)  
- Clean UI and responsive layout  

## Tech Stack

- **React** — UI library  
- **Vite** — build tooling and dev server  
- **JavaScript / JSX**  
- **ESLint** — linting  
- (Optional) **localStorage / browser storage** for persistence  

## Getting Started

### Prerequisites

Make sure you have the following installed:

- Node.js (v14 or above recommended)  
- npm or yarn  

### Installation

1. Clone the repo:

   ```bash
   git clone https://github.com/AmanQureshi0111/TodoListContext.git
   cd TodoListContext
2.Install dependencies:

npm install

3.Start the development server:

npm run dev


Then open your browser and navigate to http://localhost:3000 (or the port Vite shows).

To build for production:

npm run build

To preview the production build:

npm run preview

Project Structure (example)
```
TodoListContext/
├── public/
│   └── index.html
├── src/
│   ├── components/
│   │   ├── TodoItem.jsx
│   │   ├── TodoList.jsx
│   │   └── TodoInput.jsx
│   ├── context/
│   │   └── TodoContext.jsx
│   ├── App.jsx
│   └── main.jsx
├── .gitignore
├── package.json
├── vite.config.js
└── README.md
```

src/context/TodoContext.jsx: Defines the Context provider and logic for managing todo state.

components/: Reusable UI components (input, list, item).

App.jsx: Main UI shell.

main.jsx: Entry point that renders <App /> inside Context provider.

##Usage

Once running, you can:

Add new tasks via the input form

Toggle tasks between completed / not completed

Delete tasks

(If implemented) Reload the page and still have tasks persist

You can modify or extend it—for example, add categories, deadlines, or drag-and-drop reordering.

##Contributing

Contributions are welcome! You can:

Fork this repository

Create your feature branch (git checkout -b feature/YourFeature)

Commit your changes (git commit -m "Add some feature")

Push to the branch (git push origin feature/YourFeature)

Open a pull request

Please make sure your changes are well tested and documented.
