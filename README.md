# API-TESTING-POSTMAN
# 📘 Book Management API Testing – Postman Collection

This Postman collection is designed to test the endpoints of the **Simple Books API** (https://simple-books-api.glitch.me). It includes organized requests for performing CRUD operations on books.

**Important Note**:  
The actual [Simple Books API](https://simple-books-api.glitch.me) is **read-only for `/books`** — it does **not support POST, PUT, PATCH, or DELETE** on `/books`. These requests are included in this collection only for learning/demo purposes and will return `Cannot <METHOD> /books`.

---

## Collection Structure

### GET APIs

- **Retrieve all books**
  - `GET /books`
  - Returns a list of available books.

- **Get Book by ID**
  - `GET /books/{id}`
  - Returns information for a specific book.

---

### POST APIs

- **Add Book**
  - `POST /books`
  - **Not supported by Simple Books API** – included for demo/testing structure.

---

### PUT APIs

- **Update Book**
  - `PUT /books/{id}`
  - **Not supported** – simulates a full update.

---

### PATCH APIs

- **Partial Update**
  - `PATCH /books/{id}`
  - **Not supported** – simulates a partial update (e.g., changing availability).

---

### DELETE APIs

- **Delete Book**
  - `DELETE /books/{id}`
  - **Not supported** – included to show proper delete request structure.


