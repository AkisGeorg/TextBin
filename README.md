# TextBin: A Minimalist Pastebin Application 📝

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

TextBin is a simple yet powerful pastebin application built with Node.js, Express, MongoDB, and EJS. It allows users to create, share, and manage code snippets and text pastes effortlessly.

## ✨ Features

* **Create Pastes:**
    * Title, content, syntax highlighting (plaintext by default), expiration time, and visibility settings.
    * Syntax highlighting for multiple programming languages.
    * Expiration: 10 minutes, 1 hour, 1 day, or never.
    * Visibility: public or private.
* **View Pastes:**
    * Syntax highlighting and metadata (creation date, syntax).
    * Private pastes: creator-only or invite code access.
    * Automatic paste expiration.
* **Recent Pastes:**
    * 10 most recent public pastes.
    * Title, syntax, creation date, and creator (if available).
* **User Authentication:**
    * Registration and login.
    * Secure password hashing (bcrypt).
    * User profiles with created pastes.
* **Private Pastes & Invite Codes:**
    * Private pastes are exclusive.
    * Invite codes for sharing.
* **User Profiles:**
    * List of user-created pastes.
* **Notifications:**
    * Flash notifications for registration/login.
* **Database Persistence:**
    * MongoDB with Mongoose.
    * MongoDB session storage.
* **Responsive UI:**
    * Clean, minimalist design.

## 🚀 Getting Started

1.  **Clone the Repository:**

    ```bash
    git clone [repository URL]
    cd TextBin
    ```

2.  **Install Dependencies:**

    ```bash
    npm install
    ```

3.  **Set Up MongoDB:**

    * Ensure MongoDB is running.
    * Update the connection string in `server.js`.

4.  **Run the Application:**

    ```bash
    node server.js
    ```

5.  **Open in Browser:**

    * Navigate to `http://localhost:3000`.

## 🛠️ Technologies Used

* **Node.js:** Server-side runtime.
* **Express:** Web application framework.
* **MongoDB:** Database.
* **Mongoose:** MongoDB object modeling.
* **EJS:** Templating engine.
* **bcrypt:** Password hashing.
* **express-session & connect-mongo:** Session management.
* **connect-flash:** Notification messages.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues to improve TextBin.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
