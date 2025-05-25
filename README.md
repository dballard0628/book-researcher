# 📚 Book Researcher

**Book Researcher** is a web application that allows avid readers to search for books using the Google Books API, create an account, and save their favorite titles for future reference. This app provides a seamless way to explore new books and manage a personalized reading list.

---

## 🚀 Features

- 🔍 Search for books by title, author, or keyword
- 📖 View detailed search results with title, author, description, cover image, and a link to Google Books
- 🔐 User authentication via Signup and Login
- 💾 Save favorite books to a personal account
- 🗑 Remove saved books from your collection
- 🧭 Dynamic navigation based on login state

---

## 🧑‍💻 User Story

> **AS AN** avid reader  
> **I WANT** to search for new books to read  
> **SO THAT** I can keep a list of books to purchase

---

## ✅ Acceptance Criteria

- **GIVEN** a book search engine  
  - **WHEN** I load the search engine  
    - **THEN** I am presented with a menu containing "Search for Books" and "Login/Signup", along with a search input field and submit button

- **WHEN** I click "Search for Books"  
  - **THEN** I am presented with an input field and a submit button

- **WHEN** I am **not logged in** and perform a search  
  - **THEN** I see results including title, author, description, cover image, and a link to Google Books

- **WHEN** I click "Login/Signup"  
  - **THEN** a modal appears with toggle options for logging in or signing up

- **WHEN** I choose "Signup"  
  - **THEN** I see inputs for username, email, password, and a signup button

- **WHEN** I choose "Login"  
  - **THEN** I see inputs for email, password, and a login button

- **WHEN** I sign up with valid information  
  - **THEN** my account is created and I am logged in

- **WHEN** I log in with valid credentials  
  - **THEN** the modal closes and I am logged in

- **WHEN** I am logged in  
  - **THEN** the menu updates to "Search for Books", "Saved Books", and "Logout"

- **WHEN** I search while logged in  
  - **THEN** results also show a "Save" button

- **WHEN** I click "Save" on a book  
  - **THEN** it is saved to my account

- **WHEN** I click "Saved Books"  
  - **THEN** I see my saved books with all details and a "Remove" button

- **WHEN** I click "Remove"  
  - **THEN** the book is deleted from my saved list

- **WHEN** I click "Logout"  
  - **THEN** I am logged out and returned to the initial view

---

## 🛠 Tech Stack

- **Frontend**: React, Vite, TypeScript
- **Backend**: Node.js, Express, Apollo Server (GraphQL)
- **Authentication**: JWT-based login/signup
- **API Integration**: Google Books API
- **Database**: MongoDB (via Mongoose)
- **Hosting**: Render

---

## 📦 Installation

```bash
git clone https://github.com/dballard0628/book-researcher.git
cd book-researcher/client
npm install
npm run dev

book-researcher/
├── client/          # React frontend
├── server/          # Express backend with GraphQL
├── README.md

🔗 Live Demo
https://book-researcher-u8fp.onrender.com/

📄 License
This project is licensed under the MIT License.

📬 Contact Me
Feel free to reach out with questions, feedback, or collaboration ideas:

Name: [Danah B]

Email: [dball@gmail.com]

GitHub: https://github.com/dballard0628/book-researcher

