<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <title>ToDo List Using Django Framework</title>
  </head>
  <body>
    <h1>ToDo List Using Django Framework</h1>
    <h2>Introduction</h2>
    <p>This is a simple ToDo list application using Django framework. After user login or register he/she is allowed you to add, edit, delete and view their own tasks.</p>
    <h2>API Endpoints</h2>
    <ul>
      <li>GET / - Get all todos</li>
      <li>GET /detailed/:id - Get detailed todo</li>
      <li>POST /createTodo/ - Create a todo</li>
      <li>POST /updateTodo/:id - Update a todo</li>
      <li>DELETE /deleteTodo/:id - Delete a todo</li>
      <li>POST /signup - Create a user</li>
      <li>POST /login - Login a user</li>
      <li>GET /logout - Logout a user</li>
      <li>GET /completedTodos - Get all completed todos</li>
    </ul>
    <h2>Requirements</h2>
    <ul>
      <li>Python 3.6</li>
      <li>Django 2.0.2</li>
    </ul>
    <h2>Installation</h2>
    <ol>
      <li>Clone the repository</li>
      <li><code>git clone https://github.com/MarwaAbdelAal/TodoList-Django.git</code></li>
      <li>Create a virtual environment and activate it</li>
      <li><code>python3 -m venv env</code></li>
      <li><code>source env/bin/activate</code></li>
      <li>Install the requirements</li>
      <li><code>pip install -r requirements.txt</code></li>
    </ol>
    <h2>Usage</h2>
    <ol>
      <li>Run the server</li>
      <li><code>python manage.py runserver</code></li>
      <li>Open the browser and go to <a href="http://localhost:8000">http://localhost:8000</a></li>
    </ol>
  </body>
</html>
