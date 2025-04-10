# 📝 Basic Quora Homepage Clone
This is a simple CRUD (Create, Read, Update, Delete) application built using Node.js and Express.js. It allows users to view, create, edit, and delete posts dynamically. Each post includes a username and a short content message.


# 🚀 Features
📜 View all posts
➕ Add a new post
🔍 View individual post details
✏️ Edit a post
❌ Delete a post


# 🧰 Tech Stack
- Node.js
- Express.js
- EJS – for templating
- UUID – to generate unique post IDs
- Method-Override – to support PATCH and DELETE HTTP verbs in forms
- HTML & CSS – for basic UI (in the public/ directory)


# ⚙️ Middleware & Utilities
- express.urlencoded() – Parses incoming form data.
- method-override – Enables HTML forms to use PUT, PATCH, and DELETE.
- uuid – Generates a unique ID for each post.


# ✅ To-Do / Future Improvements
- Use a database like MongoDB instead of in-memory storage
- Add user authentication
- Implement flash messages for feedback
- Improve frontend design and responsiveness