https://bethwelkipruto.github.io/simple-blog/
# Simple Blog Post

A simple blog application built with **HTML**, **CSS**, and **JavaScript**, using **JSON Server** as a mock backend for storing and retrieving blog posts.

## Features

- View all blog posts
- Create new blog posts
- Edit and delete existing posts
- Responsive design for desktop and mobile
- Data persistence using JSON Server

## Technologies Used

- **HTML5**: Structure of the web pages
- **CSS3**: Styling and layout
- **JavaScript (ES6+)**: Dynamic functionality and DOM manipulation
- **JSON Server**: Mock REST API for blog data

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/)
- [JSON Server](https://github.com/typicode/json-server)

### Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/simple-blog.git
    cd simple-blog
    ```

2. **Install JSON Server globally (if not already installed):**
    ```bash
    npm install -g json-server
    ```

3. **Start JSON Server:**
    ```bash
    json-server --watch db.json --port 3000
    ```
    This will start the mock API at `http://localhost:3000`.

4. **Open `index.html` in your browser:**
    - You can use Live Server extension in VS Code or simply open the file directly.

## Project Structure

```
simple-blog/
├── db.json          # JSON Server database
├── index.html       # Main HTML file
├── styles.css       # CSS styles
├── app.js           # JavaScript logic
└── README.md        # Project documentation
```

## API Endpoints

- `GET /posts` - Fetch all blog posts
- `POST /posts` - Create a new post
- `PATCH /posts/:id` - Update a post
- `DELETE /posts/:id` - Delete a post

## Usage

1. **Add a new post:** Fill out the form and submit to add a new blog post.
2. **Edit a post:** Click the edit button on a post to modify its content.
3. **Delete a post:** Click the delete button to remove a post.

## Customization

- Modify `db.json` to change initial blog data.
- Update `styles.css` for custom styles.
- Extend `app.js` to add more features (e.g., comments, likes).

## License

This project is licensed under the [MIT License](LICENSE).

---

