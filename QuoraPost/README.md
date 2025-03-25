# QuoraPost

QuoraPost is a simple Express.js application that allows users to create, read, update, and delete (CRUD) posts. Each post includes a username and content, and is identified by a unique ID.

## Features

- View all posts
- Add a new post
- View a single post
- Edit a post
- Delete a post

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/mritunjaypandey2k24/Project.git
    ```

2. Navigate to the project directory:
    ```sh
    cd Project/QuoraPost
    ```

3. Install the dependencies:
    ```sh
    npm install
    ```

## Usage

1. Start the server:
    ```sh
    node index.js
    ```

2. Open your browser and navigate to `http://localhost:8080/posts` to view all posts.

## Routes

- `GET /posts` - View all posts
- `GET /posts/new` - Form to add a new post
- `POST /posts` - Add a new post
- `GET /posts/:id` - View a single post by ID
- `GET /posts/:id/edit` - Form to edit a post by ID
- `PATCH /posts/:id` - Update a post by ID
- `DELETE /posts/:id` - Delete a post by ID

## Dependencies

- express
- uuid
- method-override
- ejs

## Project Structure

```
QuoraPost/
├── index.js
├── views/
│   ├── edit.ejs
│   ├── index.ejs
│   ├── new.ejs
│   ├── show.ejs
├── public/
├── node_modules/
├── package.json
└── package-lock.json
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Author

Mritunjay Pandey
```