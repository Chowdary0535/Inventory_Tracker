# 📦 Inventory Tracker

A full-stack Inventory Management System built using Node.js, Express.js, MySQL, HTML, CSS, and JavaScript. The application allows users to manage inventory efficiently through a simple and responsive interface with complete CRUD operations.

---

 🚀 Features

- ➕ Add new inventory items
- 📋 View all available items
- ✏️ Update existing item details
- 🗑️ Delete inventory items
- 🔍 Search items instantly
- ⚠️ Low stock indicator for items with quantity ≤ 5
- 💾 MySQL database integration
- 🌐 RESTful API architecture
- 📱 Responsive user interface

---

## 🛠️ Tech Stack

### Frontend
- HTML5
- CSS3
- JavaScript (Vanilla)

### Backend
- Node.js
- Express.js

### Database
- MySQL

### Packages Used
- Express
- MySQL2
- Dotenv
- CORS
- Nodemon (Development)

---

## 📂 Project Structure

```
inventory-tracker/
│
├── config/
│   └── db.js
│
├── routes/
│   └── items.js
│
├── public/
│   ├── index.html
│   ├── style.css
│   └── script.js
│
├── schema.sql
├── server.js
├── package.json
├── .env.example
└── README.md
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/inventory-tracker.git
```

### 2. Navigate to the project folder

```bash
cd inventory-tracker
```

### 3. Install dependencies

```bash
npm install
```

---

## 🗄️ Database Setup

Open MySQL and execute:

```bash
mysql -u root -p < schema.sql
```

This creates:

- Database: `inventory_tracker`
- Table: `items`
- Sample inventory records

---

## 🔐 Environment Variables

Create a `.env` file in the project root.

```env
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=your_password
DB_NAME=inventory_tracker
PORT=5000
```

---

## ▶️ Run the Application

Start the server

```bash
npm start
```

Development mode

```bash
npm run dev
```

Open your browser:

```
http://localhost:5000
```

---

## 📡 API Endpoints

| Method | Endpoint | Description |
|---------|----------|-------------|
| GET | `/api/items` | Retrieve all items |
| GET | `/api/items/:id` | Retrieve item by ID |
| POST | `/api/items` | Add a new item |
| PUT | `/api/items/:id` | Update an item |
| DELETE | `/api/items/:id` | Delete an item |

---

## 📊 Database Fields

| Field | Type |
|--------|------|
| id | Integer |
| name | Varchar |
| category | Varchar |
| quantity | Integer |
| price | Decimal |
| supplier | Varchar |
| created_at | Timestamp |
| updated_at | Timestamp |

---

## 🔮 Future Enhancements

- User Authentication (JWT)
- Dashboard Analytics
- Export Inventory to Excel/PDF
- Category Management
- Supplier Management
- Barcode Scanner Integration
- Pagination & Sorting
- Dark Mode
- Stock Reports
- Email Notifications for Low Stock

---

## 📚 Learning Outcomes

This project demonstrates:

- REST API Development
- CRUD Operations
- MySQL Database Integration
- Express Routing
- Environment Variables
- Frontend & Backend Integration
- Responsive Web Design

---

## 👨‍💻 Author

Nmae:Vinay Kumar Duggineni
Companny:CODTECH IT SOLUTIONS
ID:CITS7256
Mentor:Neela Santhosh Kumar
Full Stack Web Development Project

