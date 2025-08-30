# 📚 Library Management System (React + Redux Toolkit Query + TypeScript)

A minimal **Library Management System** built with **React**, **Redux Toolkit Query (RTK Query)**, and **TypeScript**.  
This project demonstrates **state management, UI design, and CRUD operations** with a clean and responsive interface.  

---

## 🚀 Project Overview
This system allows users to:
- View a list of books
- Add, edit, and delete books
- Borrow books with quantity & due date
- View a simple **borrow summary**  

⚡ **No authentication, category filters, or payment integration** — just the core book management and borrowing features.

---

## ✨ Features

### 🔓 Public Routes
- All pages are accessible without login.
- Focus is on **book management & borrowing**.

### 📖 Book Management
- **Book List Table**: Shows all books with columns → Title, Author, Genre, ISBN, Copies, Availability, and Actions.
- **Actions**:
  - ✏️ **Edit Book** → Update book info. If `copies = 0`, the book is marked unavailable.
  - 🗑️ **Delete Book** → Confirmation dialog before removal.
  - 📗 **Borrow Book** → Opens a borrow form.
- **Add New Book**:
  - Fields: Title, Author, Genre, ISBN, Description, Copies, Available (default: true).
  - Redirects to book list after creation.



## 🖼️ Landing Page Components
- **Navbar** → Links to All Books, Add Book, Borrow Summary.
- **Book Table** → Displays books with actions.
- **Footer** → Standard footer with site info or credits.

---

## 📄 Pages
| Route             | Description                                   |
|-------------------|-----------------------------------------------|
| `/books`          | List all books (view, edit, delete, borrow). |
| `/create-book`    | Add a new book.                              |
| `/books/:id`      | Detailed single book view.                   |
| `/edit-book/:id`  | Edit an existing book.                       |
| `/borrow/:bookId` | Borrow form for a book.                      |
| `/borrow-summary` | Aggregated summary of borrowed books.        |

---



## 🛠️ Tech Stack
- **Frontend**: React + TypeScript + Vite
- **State Management**: Redux Toolkit Query (RTK Query)
- **Styling**: Tailwind CSS
- **Icons**: Lucide React
- **Animations**: Framer Motion (optional)

---

## 📦 Installation & Setup
```bash
# Clone the repo
git clone https://github.com/codermdshakil/assignment4-client.git

# Navigate to project
cd assignment4-client

# Install dependencies
npm install

# Start development  
npm run dev

```
