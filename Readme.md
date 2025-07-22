# Tailblocks Template - Real Estate Website

A modern, responsive real estate website template built with **Tailwind CSS**. Features a secure contact form with Google Sheets backend, client/server-side validation, and best practices for frontend-backend integration.

---

## 🚀 Tech Stack

- **HTML5**: Semantic markup
- **Tailwind CSS**: Utility-first CSS framework for rapid UI development
- **JavaScript (ES6+)**: Form validation and AJAX submission
- **Google Apps Script**: Serverless backend for form handling and Google Sheets integration
- **Google Sheets**: Stores contact form submissions
- **VS Code Live Server**: For local development and testing

---

## 📁 Project Structure

```
tailblocks-template/
├── index.html          # Main HTML file
├── js/
│   └── main.js         # Handles form validation and AJAX
├── style/
│   └── style.css       # Custom styles (if any)
├── Readme.md           # Project documentation
```

---

## 🛠️ Features

- **Responsive Layout**: Works on all devices
- **Form Validation**: 
  - Name: 2-40 alphabets/spaces
  - Phone: Indian 10-digit mobile (starts with 6-9)
  - Email: Standard format
  - Message: 1-500 chars
- **AJAX Form Submission**: No page reload, user feedback via alerts and status messages
- **Google Apps Script Backend**: 
  - Validates input
  - Token-based authentication
  - Saves data to Google Sheets with IST timestamp

---

## ⚡ Quick Start

1. **Clone the repo**
   ```bash
   git clone https://github.com/pradeepyadav949/tailblocks-template.git
   cd tailblocks-template
   ```

2. **Open `index.html` with Live Server**  
   (Recommended: VS Code Live Server extension)

3. **Set up Google Apps Script**
   - Copy the provided backend script to a new Apps Script project
   - Deploy as Web App (access: Anyone)
   - Update the webhook URL in `js/main.js`

---

## 🔒 Security & Best Practices

- **All validation is duplicated server-side**
- **Timestamp in IST**: All entries in Google Sheets are time-stamped in Indian Standard Time

---

## 📝 Customization

- Update form fields and validation in `index.html` and `js/main.js` as needed
- Adjust Google Apps Script for additional backend logic or storage

---

## 📄 License

MIT License

---

**Built with Tailwind CSS and Google Apps Script.**