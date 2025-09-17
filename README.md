# 📚 Book Management System

A simple, lightweight web-based book management system built with vanilla HTML and JavaScript. This application allows users to add, view, and edit book records with an intuitive interface.

## ✨ Features

- **Add Books**: Add new books with details including name, author, description, and page count
- **View Collection**: Display all books in a clean, organized format
- **Edit Books**: Modify existing book entries with ease
- **Input Validation**: Ensures all required fields are filled before adding books
- **Responsive Design**: Works seamlessly across different devices

## 🚀 Demo

![Book Management System Screenshot](screenshot.png)


## 📋 Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional installations required!

## 🛠️ Installation & Setup

1. Clone this repository:
   ```bash
   git clone https://github.com/Amson-tECH/book-management-system.git
   ```

2. Navigate to the project directory:
   ```bash
   cd book-management-system
   ```

3. Open `index.html` in your web browser:
   ```bash
   # On Windows
   start book-system.html
   
   # On macOS
   open book-system.html
   
   # On Linux
   xdg-open book-system.html
   ```

   Or simply double-click the `book-system.html` file in your file explorer.

## 📁 Project Structure

```
book-management-system/
│
├── book-system.html          # Main HTML structure
├── book_system.js      # JavaScript functionality
└── README.md          # Project documentation
```

## 🎯 How to Use

1. **Adding a Book**:
   - Fill in the book name, author name, description, and number of pages
   - Click the "Add Book" button
   - The book will appear in the books list below

2. **Editing a Book**:
   - Click the "Edit" button next to any book entry
   - The book details will populate in the form fields
   - Make your changes and click "Add Book" to save

3. **Viewing Books**:
   - All added books are automatically displayed below the form
   - Each book shows complete details including name, author, description, and page count

## 💻 Technical Details

- **Frontend**: HTML5, JavaScript (ES6+)


## 🔧 Code Structure

### Main Functions:

- `addBook()`: Validates input and adds new book to collection
- `showbooks()`: Renders book list in the DOM
- `editbook(index)`: Loads book data into form for editing
- `clearInputs()`: Clears all form fields

### Data Structure:
Each book object contains:
```javascript
{
    name: "Book Title",
    authorName: "Author Name", 
    bookDescription: "Book Description",
    pagesNumber: 123
}
```

## 🚀 Future Enhancements

- [ ] Add local storage persistence
- [ ] Implement delete functionality
- [ ] Add search and filter capabilities
- [ ] Include book categories/genres
- [ ] Add book cover image upload
- [ ] Export/import book data (JSON/CSV)
- [ ] Add reading status tracking
- [ ] Implement book rating system

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the project
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



## 👨‍💻 Author

**Reuben Korsi Amuzu**
- GitHub: [@Amson-tECH](https://github.com/Amson-tECH)
- Email: reubenamuzu23@gmail.com

## 🙏 Acknowledgments

- Built with vanilla JavaScript for simplicity and learning purposes
- Inspired by the need for a simple book tracking solution

---

⭐ If you found this project helpful, please give it a star!
