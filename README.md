# Todo App with React

This project is a simple and responsive Todo App written in React using Hooks, leaning back onto Mate Academy API.

# App Documentation

1. The `index.tsx` file initializes basic CSS and creates the root.
1. The `App.tsx` file initializes the rest of the page and handles most of the app's states.
1. The `api` folder contains the `todos.ts` file, which is responsible for API calls to the Mate Academy API.
1. The `styles` folder contains CSS styling for individual BEM blocks.
1. The `types` folder contains `.ts` files with data types in them, such as `FilterTypes` or `Todo`.
1. The `utils` folder contains API call logic used by the `todos.ts` from the api folder.
1. The `components` folder contains individual parts of the site, including:
    - `Notification`, which is a popup informing of any potential erros in case the API rejects the request, for example when the server is facing downtime.
    - `TodoList`, which is the main section of the page, passing down props and structure to:
        - `TodoItem`, which is every individual Todo in the list,
        - `NewTodo`, which is the field at the top of the list, responsible for text input and pushing new todos into the list,
        - `Footer`, which is the bottom part of the page, including the counter of active Todos, as well as the
            - `Filter`, which contains filter option buttons, allowing the filtering of the Todo list by completion status.

# [App Demo](https://kacper-lyczba.github.io/react-todo-app)
