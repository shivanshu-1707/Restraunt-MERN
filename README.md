# 🌟 Restaurant Website - MERN Stack 🌟

Welcome to the **Restaurant Website** project built using the **MERN stack** (MongoDB, Express, React, Node.js). This application provides a fully functional platform for users to explore and manage restaurant-related features.

## 📚 Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [License](#license)

## ⚡ Features

- **User Authentication**: Secure login and registration functionality.
- **Menu Management**: Dynamic menu management for restaurants.
- **Order Processing**: Users can place orders directly through the website.
- **Payment Integration**: Secure payment processing using Stripe.
- **Responsive Design**: Modern UI created using ShadCN UI & Tailwind CSS.
- **SEO Optimization**: Improved discoverability on search engines.
- **Advanced Searching**: Efficient search functionality for restaurants and dishes.

## 🛠️ Technologies Used

- **Frontend**: React, TypeScript, Vite, ShadCN UI, Tailwind CSS
- **Backend**: Node.js, Express, MongoDB, Mongoose
- **Payment Processing**: Stripe
- **Email Sending**: Mailtrap
- **State Management**: Zustand
- **Schema Validation**: Zod
- **Version Control**: Git, GitHub

## 🚀 Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
   ```

2. **Install backend dependencies**:
   ```bash
   cd server
   npm install
   ```

3. **Install frontend dependencies**:
   ```bash
   cd ../client
   npm install
   ```

## 💻 Usage

1. **Set up your MongoDB database** and update the connection string in the `.env` file in the `server` directory.

2. **Start the backend server**:
   ```bash
   cd server
   npm start
   ```

3. **Start the frontend development server**:
   ```bash
   cd ../client
   npm start
   ```

4. Open your browser and navigate to `http://localhost:3000` to view the application.

## ⚙️ Configuration

Make sure to configure the following in the `.env` file in the `server` directory:

```bash
MONGODB_URI=your_mongodb_connection_string
STRIPE_SECRET_KEY=your_stripe_secret_key
MAILTRAP_USER=your_mailtrap_username
MAILTRAP_PASS=your_mailtrap_password
```

## 📜 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

Feel free to contribute or reach out if you have any questions! Let's build amazing things together! 🚀✨
