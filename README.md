# Vuex Todo Manager

This is a simple todo web application built with Vue.js and Vuex. It allows users to add, delete, and limit the number of todos showing up on the page. The data is retrieved from JSONPlaceholder, a free online REST API for testing and prototyping.

This project inspired by vuex course of Brad Traversy.

## Project setup

Clone the repository and navigate to the project directory:

```
git clone https://github.com/ozgur-okt/vuex-todo-app.git
cd vuex-todo-app
```

Install the project dependencies:

```
npm install
```

Start the Vue development server:

```
npm run serve
```

Open your browser and navigate to http://localhost:8080/ to access the application.

## Usage

### Adding todos
To add a new todo, simply enter the todo details in the input field at the top of the page and press Enter or click the "Add" button. This will add the todo to the list.

### Deleting todos
To delete a todo, click the delete icon next to the todo item. This will immediately remove the todo from the list.

### Limiting todos
To limit the number of todos showing up on the page, select one of the options (5, 50, 100, or 200) from the dropdown menu. This will filter the todos accordingly.

### Changing todo color
To change the color of a todo when it is completed, double click on the todo item. This will toggle the "completed" status of the todo and change its background color to green. Double clicking on a completed todo will toggle it back to its original state.

## Acknowledgements

This project was built using the following technologies:

* Vue.js (https://vuejs.org/)
* Vuex (https://vuex.vuejs.org/)
* JSONPlaceholder (https://jsonplaceholder.typicode.com/)

## License
This project is licensed under the MIT License. See the LICENSE file for details.
