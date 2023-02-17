![cover-node js](https://user-images.githubusercontent.com/56506919/219757505-28223f79-45ea-4f62-be3d-ca0f0b3da48b.png)

## 🖥️ Challenge 01: Node.js Concepts

Application to manage tasks

- Create a new task.
- List all tasks.
- Change the `title` and `deadline` of an existing task.
- Mark a task as done;
- Delete a task.

<br />

## 🚀 Technologies

This project was developed with the following technologies:

- [Express](https://expressjs.com/)
- [Nodemon](https://nodemon.io/)
- [Uuid](https://www.npmjs.com/package/uuid)
- [Jest](https://jestjs.io/)
- [Supertest](https://www.npmjs.com/package/supertest)

<br />

## 🛣️ Application routes

<table>
  <tr>
    <th>Method</th>
    <th>Path</th>
    <th></th>
  </tr>
  <tr>
    <td>POST</td>
    <td>/users</td>
    <td>
      Register a new user
    </td>
  </tr>
  <tr>
    <td>GET</td>
    <td>/todos</td>
    <td>
      List all tasks according to username
    </td>
  </tr>
  <tr>
    <td>POST</td>
    <td>/todos</td>
    <td>
      Register a new task
    </td>
  </tr>
  <tr>
    <td>PUT</td>
    <td>/todos/:id</td>
    <td>
      Edit a task
    </td>
  </tr>
  <tr>
    <td>PATCH</td>
    <td>/todos/:id/done</td>
    <td>
      Mark a task as done
    </td>
  </tr>
  <tr>
    <td>DELETE</td>
    <td>/todos/:id</td>
    <td>
      Delete a task
    </td>
  </tr>
</table>

<br />

## 🧪 Tests

- Users
    - Should be able to create a new user
    - Should not be able to create a new user when username already exists
- Todos
    - Should be able to list all user's todos
    - Should be able to create a new todo
    - Should be able to update a todo
    - Should not be able to update a non existing todo
    - Should be able to mark a todo as done
    - Should not be able to mark a non existing todo as done
    - Should be able to delete a todo
    - Should not be able to delete a non existing todo

<br />

## ℹ️ How To Use
```bash
# Clone the repository
$ git clone https://github.com/kaikySantos/todo-node-ignite-challenge.git

# Go into the directory
$ cd todo-node-ignite-challenge

# Install dependencies
$ npm i

# Run the application
$ npm run dev

# Run the tests
$ npm run test
```

<br />

---

Made with ♥ by Kaiky 👋🏻
