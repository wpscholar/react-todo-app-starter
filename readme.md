# React To Do Application - Starter

This repository is meant to serve as a starting point for building your own React / Redux To Do Application. The tooling, markup and styling is already in place. All you have to do is turn it into a working application.

## Background

This application was created using Facebook's `create-react-app` project (https://github.com/facebookincubator/create-react-app). Here is a quick overview of the setup steps we've already taken care of for you:

- Install Facebook's `create-react-app` tool by running `npm install -g create-react-app`.
- Generate an app by running `create-react-app react-todo-app-starter`.
- Install additional project dependencies by running `npm install --save redux react-redux redux-logger immutable lodash classnames`.
- Added custom markup to the render method of the App component in the `App.js` file.
- Added custom styling to the `index.css` and `App.css` files.
- Deleted the `src/logo.svg` file.

## Getting Up and Running

- Clone this repository
- Run `npm install` from the repository's root directory.
- Run `npm start` to run the React application and development server. A browser window will open automatically to http://localhost:3000/

## Next Steps

Start editing the files in the `src/` directory to create a working application. As you change files, the application will automatically reload in the browser.

## Goals

- Split out existing markup into three additional components: CreateTask, TaskList and Task
- Pass in existing tasks to the application on instantiation.
- Implement ability to switch a task into edit mode by double-clicking the task name.
- Utilize Redux to create a data store and wrap the existing app in a provider.
- Implement ability to edit a task name within edit mode.
- Implement ability to delete a task.
- Implement ability to toggle a task between complete and incomplete.
- Implement ability to create a task.
- Ensure the task list doesn't display if there are no tasks.
- Store application data in local storage.

## On Completion

Once you've completed all of the goals listed above and have a working application, or if you get stuck and need a working example, you can see the final product here: https://github.com/wpscholar/react-todo-app