# Todo List

A rails api for a simple react todo list app. View the app at https://react-todo-list-33.herokuapp.com/.
The todo list data can be viewed at https://stark-sea-73979.herokuapp.com/api/v1/todos.

## Running the application
1. Clone this repository & the front-end which can be found at https://github.com/rjackson21/todo-app-frontend
2. `cd` into it and run the migrations (`bundle exec rake db:migrate`)
3. Install the dependencies by running `bundle`
4. Within `TodosContainer.js`, change the calls being made to the api. Currently, for the app to be deployed properly, the api is also deployed, and the app is calling to the deployed api. Change all api calls to './api/v1/todos'.
5. Start the Rails server by running `rails server` in the project root
6. Start React with `yarn start`
