# 🏫 Hall Allocation System

A web-based **Hall Allocation System** developed to simplify and automate the process of assigning examination halls to students. The system helps administrators efficiently manage hall allocations while reducing manual effort and errors.

---

## 📌 Features

- 🔐 User Authentication (Admin Login)
- 👨‍🎓 Student Management
- 🏫 Hall Management
- 📝 Automatic Hall Allocation
- 📊 View Allocated Halls
- 🔍 Search and Filter Records
- 📱 Responsive User Interface

---

## 🛠️ Tech Stack

### Frontend
- HTML
- CSS
- JavaScript
- React.js (if used)

### Backend
- Node.js
- Express.js

### Database
- MongoDB

---

## 📂 Project Structure

```
Hall-Allocation-System/
│
├── frontend/          # Frontend source code
├── backend/           # Backend source code
├── database/          # Database configuration
├── public/            # Static files
├── package.json
└── README.md
```

---

## 🚀 Installation

### 1. Clone the repository

```bash
git clone https://github.com/Sona-Ahirwar/Hall-Allocation-System.git
```

### 2. Navigate to the project

```bash
cd Hall-Allocation-System
```

### 3. Install dependencies

For Backend

```bash
cd backend
npm install
```

For Frontend

```bash
cd frontend
npm install
```

### 4. Configure Environment Variables

Create a `.env` file inside the backend folder.

Example:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

---

## ▶️ Run the Project

### Start Backend

```bash
cd backend
npm start
```

### Start Frontend

```bash
cd frontend
npm start
```

The application will run at:

```
Frontend: http://localhost:3000
Backend: http://localhost:5000
```

---

## 📖 How It Works

1. Admin logs into the system.
2. Student and hall details are added.
3. The system processes available halls.
4. Students are allocated based on capacity.
5. Allocation results are displayed.
6. Admin can search and manage allocated records.

---

## 🎯 Future Enhancements

- Faculty Login
- Student Login
- PDF Hall Ticket Generation
- Email Notifications
- Excel Import/Export
- Seat-wise Allocation
- Multiple Department Support

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a new branch.

```bash
git checkout -b feature-name
```

3. Commit your changes.

```bash
git commit -m "Added new feature"
```

4. Push to GitHub.

```bash
git push origin feature-name
```

5. Create a Pull Request.

---

## 👩‍💻 Author

**Sona Ahirwar**

GitHub: https://github.com/Sona-Ahirwar

---

## ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.
