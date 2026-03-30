# 📚 Library Management System

A comprehensive command-line Library Management System built in Python that helps librarians manage books, members, and book issuance/returns efficiently.

## 📋 Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Data Structure](#data-structure)
- [Modules](#modules)
- [Team Structure](#team-structure)
- [Contributing](#contributing)
- [License](#license)

## ✨ Features

### Book Management
- Add new books with details (ID, title, author, genre, copies)
- View all books in the library
- Search books by title or author
- Delete books (with safety check for issued copies)
- Track available copies

### Member Management
- Register new members (ID, name, email, phone)
- View all registered members
- Member information management

### Issue/Return System
- Issue books to members with automatic due date (14 days)
- Return books with late fine calculation (Rs. 5/day)
- Track issued books and their status
- Prevent issuing unavailable books
- Prevent deletion of books with issued copies

### Reports & Monitoring
- View all currently issued books
- Check overdue status automatically
- Display availability status of books

## 🚀 Installation

### Prerequisites
- Python 3.6 or higher
- No additional libraries required (uses only standard library)

### Setup

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/library-management-system.git
cd library-management-system
