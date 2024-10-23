
# **MY BLOGS** 📚📝

Welcome to **MY BLOGS**! This is a simple yet dynamic blog posting platform that allows users to create, edit, and delete blog posts—without a database. Built with a clean interface and API-driven operations, this project demonstrates the use of HTTP methods like GET, POST, PATCH, and DELETE. 🚀

---

## **Features** 🌟

- **Add New Posts:** Easily create new blog posts through an intuitive interface with the "New Post" button.
- **Update Posts:** Modify existing posts with a simple click using the "Edit" feature.
- **Delete Posts:** Remove blog posts instantly with the "Delete" button.
- **Date Display:** Each post shows its creation or update date to keep track of content.
- **Real-Time Simulation:** All operations (Add, Update, Delete) are temporary and reset upon refresh since no database is used.

---

## **Tech Stack** 🛠️

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Node.js, Express.js
- **Protocols:** HTTPS for secure data transfer
- **Ports:**
  - **Server** runs on **port 4000**.
  - **Application** is managed via **port 3000**.

---

## **API Routes** 🔌

1. **GET** `/posts` – Retrieve all blog posts
2. **POST** `/posts` – Add a new blog post
3. **PATCH** `/posts/:id` – Update an existing blog post
4. **DELETE** `/posts/:id` – Delete a blog post

---

## **Installation Guide** 📥

1. **Clone the repository:**
   ```bash
   git clone https://github.com/sheftechdad/myblogs.git
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Run the server on port 4000:**
   ```bash
   node server.js
   ```

4. Open your browser and visit **http://localhost:4000** to ensure the server is running.

5. Once the server is confirmed to be running, visit **http://localhost:3000** to access the application interface.

---

## **Future Enhancements** 🔮

- Add a persistent database for storing blog posts.
- Implement user authentication.
- Improve post formatting with a rich text editor.

---

## **Contributing** 🤝

Feel free to open issues or submit pull requests if you have ideas for improvement or run into any problems. All contributions are welcome!

---

## **License** 📄

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Enjoy using **MY BLOGS**! Happy coding! 🎉

---

