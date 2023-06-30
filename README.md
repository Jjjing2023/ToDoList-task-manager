# TodoList App

This is a simple TodoList application built using Node.js and MongoDB. It allows users to create, manage, and organize their tasks in a convenient way.

## Features

- Create a new task
- Mark tasks as completed
- Delete tasks
- Create custom task lists

## Technologies Used

- Node.js
- Express.js
- MongoDB Atlas (cloud-hosted MongoDB database)
- Mongoose (MongoDB object modeling for Node.js)
- EJS (Embedded JavaScript templates)
- HTML/CSS

## Usage

1. Clone the repository:
```
git clone https://github.com/Unknownfanzh/TodoList-app
```

2. Install dependencies:
```
cd todolist-app
npm install
```

3. Set up MongoDB Atlas:

   - Create a MongoDB Atlas account (if you don't have one).
   - Create a new cluster and get the connection URL.
   - Replace the `mongodb+srv://<username>:<password>@<cluster-url>/todolistDB` connection URL in `app.js` with your MongoDB Atlas connection URL.

4. Start the application:
```
npm start
```

5. Open your web browser and go to http://localhost:3000 to access the TodoList app.

## Deployment

The application is deployed to Heroku. You can access the deployed app by visiting the following URL: [Your Heroku App URL](https://tranquil-hollows-73226.herokuapp.com).

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.
