# 🎓 Student Management REST API

A clean and structured **Student Management REST API** built with **Node.js and Express.js** for performing CRUD operations on student records.

This project demonstrates core backend development concepts including **RESTful API design, routing, middleware, request validation, error handling, and JSON-based responses**.

---

## 🚀 Features

* 📚 Get all students
* 🔍 Get a student by ID
* ➕ Add a new student
* ✏️ Update student information
* 🗑️ Delete a student
* 🛡️ Custom middleware
* ✅ Request validation
* ⚠️ Centralized error handling
* 📦 JSON-based API responses
* 🚫 Handling of unsupported routes
* 🔎 Invalid ID handling
* ❌ Student-not-found handling
* 💥 Server error handling

---

## 🛠️ Tech Stack

| Technology                   | Purpose                      |
| ---------------------------- | ---------------------------- |
| **Node.js**                  | JavaScript runtime           |
| **Express.js**               | Backend framework            |
| **JavaScript**               | Application logic            |
| **JSON**                     | Data storage & API responses |
| **Postman / Thunder Client** | API testing                  |

---

## 📁 Project Structure

```text
WEB-DEV-ASSIGNMENT-2/
│
├── data/
│   └── student.js
│
├── middleware/
│   └── ...
│
├── routes/
│   └── ...
│
├── app.js
├── package.json
├── package-lock.json
└── README.md
```

---

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/hammer-dev/WEB-DEV-ASSIGNMENT-2.git
```

### 2. Navigate to the project

```bash
cd WEB-DEV-ASSIGNMENT-2
```

### 3. Install dependencies

```bash
npm install
```

### 4. Start the server

```bash
node app.js
```

The API will be available at:

```text
http://localhost:3000
```

---

## 🔗 API Endpoints

### Get All Students

```http
GET /students
```

Returns a list of all available students.

---

### Get Student by ID

```http
GET /students/:id
```

Returns the student associated with the specified ID.

**Example:**

```http
GET /students/1
```

---

### Add a New Student

```http
POST /students
```

Creates a new student record.

Example request body:

```json
{
  "name": "Rahul",
  "age": 20,
  "course": "B.Tech CSE"
}
```

---

### Update Student

```http
PUT /students/:id
```

Updates the information of an existing student.

**Example:**

```http
PUT /students/1
```

---

### Delete Student

```http
DELETE /students/:id
```

Deletes a student record using the specified ID.

**Example:**

```http
DELETE /students/1
```

---

## 🧪 API Testing

The API can be tested using:

* **Postman**
* **Thunder Client**
* Any REST API testing client

The project includes handling for common API errors such as:

```text
Invalid ID
Missing fields
Student not found
Unsupported routes
Server errors
```

---

## 🧩 Concepts Demonstrated

This assignment focuses on practical backend development concepts:

* REST API architecture
* Express.js routing
* HTTP methods
* Route parameters
* Middleware
* CRUD operations
* Request validation
* Error handling
* HTTP status codes
* JSON request and response handling

---

## 📌 HTTP Methods Used

| Method   | Operation         | Endpoint        |
| -------- | ----------------- | --------------- |
| `GET`    | Get all students  | `/students`     |
| `GET`    | Get student by ID | `/students/:id` |
| `POST`   | Create student    | `/students`     |
| `PUT`    | Update student    | `/students/:id` |
| `DELETE` | Delete student    | `/students/:id` |

---

## 📷 Testing

You can use Postman or Thunder Client to send requests to the API and verify the returned JSON responses and HTTP status codes.

---

## 👨‍💻 Author

**Hammaz**

GitHub: [@hammer-dev](https://github.com/hammer-dev)

---

## 📄 License

This project was created for **educational and academic purposes** as part of a Web Development assignment.
