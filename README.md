# View Deployment (with the front-end)

https://react-todo-list-33.herokuapp.com/

# View Deployment (if you want to see the json from the api)

https://stark-sea-73979.herokuapp.com/api/v1/todos

## Run Locally

To run this app locally, you will want to clone both this repo and the front-end which can be found at https://github.com/rjackson21/todo-app-frontend

Within 'TodosContainer.js' you will want to change the api call. Currently, for the app to be deployed properly, the api is also deployed, and the app is calling to the deployed api. Change all api calls to './api/v1/todos' with both the rails serve and the front-end server running. 

To run the back-end locally, use:

### rails s 

To run the front-end locally, use:

### yarn start
