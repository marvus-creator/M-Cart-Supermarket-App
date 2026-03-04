# 🛒 M-Cart Supermarket App - Admin Dashboard

**New Generation Academy | Web Development - Assignment 02**
**Instructors:** Eric Tuyishimire & Emmanuel Niyongabo
**Developer:** Malvyn

## 📝 Project Description
M-Cart is a full-stack Supermarket Application dashboard. This assignment is split into two parts: a backend REST API and a frontend UI. The project successfully implements fully functional Products CRUD operations using Node.js, Express, and MongoDB, alongside a responsive, premium frontend interface built with HTML, Tailwind CSS, and the vanilla JavaScript Fetch API. 

As an additional feature beyond the core requirements, a complete JWT Authentication system (User Registration and Login) has been integrated to secure the backend architecture.

## 🚀 Tech Stack
* **Frontend:** HTML5, Tailwind CSS (via CDN), Vanilla JavaScript
* **Backend:** Node.js, Express.js
* **Database:** MongoDB, Mongoose
* **Security & File Handling:** JWT (JSON Web Tokens), bcryptjs, Multer (for multipart/form-data image uploads), CORS

## ✨ Key Features
* **Complete Products CRUD:** Create, Read, Update, and Delete supermarket inventory.
* **Image Uploads:** Handled seamlessly via `multer` and served statically from the `/uploads` directory.
* **Premium UI:** Designed using Figma and implemented with Tailwind CSS utility classes.
* **Authentication (Bonus):** Secure user registration, password hashing, and login endpoints.

## 🛠️ Setup Instructions
Follow these steps to run the project locally on your machine.

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/M-Cart-Supermarket-App.git](https://github.com/YOUR_USERNAME/M-Cart-Supermarket-App.git)
   cd M-Cart-Supermarket-App
   ```

2. **Install Dependencies:**
   Run the following command in your terminal to install all required packages (including express, mongoose, dotenv, multer, and cors):
   ```bash
   npm install
   ```

## 🔐 How to Configure `.env`
Create a file named `.env` in the root directory of the project. **Do not commit this file to GitHub.** Add the following configuration variables:

```env
PORT=5000
MONGO_URI=mongodb://127.0.0.1:27017/mcart_assignment
JWT_SECRET=mcart_super_secret_key_2026
```

## 🚦 How to Start the Server
Once the dependencies are installed and the environment variables are set, start the backend server by running:

```bash
npm run dev
```
The server will start on `http://localhost:5000` and connect to the local MongoDB instance. 
To view and interact with the frontend UI, simply open the `index.html` file in your web browser.

## 🎨 Figma Design Link
[Click here to view the official Figma Design](https://www.figma.com/proto/G4Q5GkU0jrBf655Yxfb5Wn/Supermarket--App-Figma?node-id=0-1&t=rfWN139Ttqne5b7T-1)

## 🧪 API Testing
A complete `postman_collection.json` file is included at the root of this project, containing all tested endpoints including image upload examples. Screenshots of successful Postman tests for all routes are available in the `/screenshots` folder.
