# CRUD App with Node.js + Express + SQLite

## 🚀 How to Run
1. Clone the repo
2. Run `npm install`
3. Start server: `node index.js`
4. API available at `http://localhost:3000`

## 📌 Endpoints

### Students
- `GET /students` → List all students
- `GET /students/:id` → Get student by ID
- `POST /students` → Create student `{ "name": "Alice", "age": 20 }`
- `PUT /students/:id` → Update student
- `DELETE /students/:id` → Delete student

### Courses
- `GET /courses` → List all courses
- `GET /courses/:id` → Get course by ID
- `POST /courses` → Create course `{ "title": "Math", "credits": 3 }`
- `PUT /courses/:id` → Update course
- `DELETE /courses/:id` → Delete course
