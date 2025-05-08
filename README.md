# 🚀 React Form App

This is a single-page React application built to demonstrate core features such as routing with React Router, form handling and validation, lazy loading with React's `Suspense` and `lazy`, and responsive styling using React Bootstrap. The app is deployed using Netlify and includes three main pages: Home, Form, and About.

---

## 📄 Pages

### 🏠 Home Page
A simple landing page that welcomes users and provides navigation links to other pages via a navigation bar.

### 📝 Form Page
Includes a form with the following validation rules:
- All fields are required
- The email must follow a valid email format
- The password must be at least 8 characters long

Validation is handled using controlled components and basic HTML5 input constraints.

### ℹ️ About Page
A static informational page describing the purpose and structure of the application.

---

## 🧠 Features

- ✅ **React Router v6**: Enables seamless navigation between multiple pages without page reloads.
- 🚀 **Lazy Loading**: Uses `React.lazy` and `Suspense` to asynchronously load the Form and About pages, improving performance.
- 🔒 **Form Validation**: Implements basic client-side validation using HTML input types and custom logic.
- 🎨 **React Bootstrap Styling**: Provides a clean, responsive UI using Bootstrap components like forms, buttons, and the navbar.
- 🌐 **Netlify Deployment**: The app is hosted live using Netlify.

---

## 🔧 Tech Stack

- **React** – Frontend JavaScript library for building UI
- **React Router DOM** – For routing and navigation
- **React Bootstrap** – Bootstrap components in React
- **Bootstrap** – CSS framework for responsive design
- **Netlify** – For continuous deployment and hosting

---

## 📁 File Structure

src/
├── components/
│ └── NavbarComponent.js # Navigation bar using React Bootstrap
├── pages/
│ ├── Home.js # Home page component
│ ├── FormPage.js # Form with validation
│ └── About.js # Static About page
├── App.js # Root component with routes
└── index.js # Entry point of the React app


---

## 🛠️ Getting Started

Follow these steps to run the project locally.

### ✅ Prerequisites

Before you begin, ensure you have the following installed:
- [Node.js](https://nodejs.org/) (v14 or later)
- npm (comes with Node.js)
- A code editor like [VS Code](https://code.visualstudio.com/)

### 📥 Installation

1. **Clone the repository:**
```bash
   git clone https://github.com/mohammadshakirsaifi/React-Form-App.git

2. ** Navigate to the project folder:**

   cd React-Form-App

3. ** Install dependencies:**
   npm install

4. ** Start the development server:**
   npm start
