# Todos List

A React application for managing a list of todos. It loads todos from an API,
lets you filter them by title and completion status, and shows extended
information about each todo (including its author) in a modal window. The app
state is managed with Redux Toolkit.

## Live Preview

[Open the live demo](https://redfield-mp.github.io/todos-list/)

## Technologies Used

- React 18 + TypeScript
- Redux Toolkit & React Redux
- React Router DOM
- Bulma & Sass (SCSS)
- Font Awesome
- React Transition Group
- classnames
- Vite
- ESLint, Prettier, Stylelint
- Cypress (e2e tests)

## Getting Started

Clone the repository:

```bash
git clone https://github.com/redfield-mp/todos-list.git
cd todos-list
```

Install dependencies:

```bash
npm install
# or
yarn install
```

Run the project locally:

```bash
npm start
# or
yarn start
```

## Features

- Loads todos from a remote API with a loading indicator.
- Filters todos by title (search query) and by status: all / active / completed.
- Opens a modal with todo details and information about its author.
- Centralized state management with Redux Toolkit slices (todos, filter,
  current todo).