Here's the **final README.md** with the screenshot included at the start:  

---

# 🔐 AuthGuard - User Authentication Full Stack Application  

![AuthGuard Screenshot](./screenshot.png)  

A **MERN stack** authentication system with secure login, registration, password hashing, JWT-based authentication, and user role management. The frontend is fully **responsive** and designed for a seamless user experience.  

---

## 🚀 Features  

✅ **User Registration & Login** – Secure sign-up and sign-in.  
✅ **JWT Authentication** – Token-based authentication for security.  
✅ **Password Hashing** – Uses bcrypt for secure password storage.  
✅ **Role-Based Access** – Different permissions for users & admins.  
✅ **Fully Responsive UI** – Works across all devices.  
✅ **RESTful API** – Handles authentication, user data, and authorization.  

---

## 📂 Project Structure  

```
/AuthGuard
│── /AuthGuard-frontend   # React Frontend
│── /AuthGuard-Backend    # Node.js Backend
│── /assets               # (Optional) Store screenshots/images
```

---

## 🛠 Installation Guide  

### 🔹 Step 1: Clone the Repository  

```sh
git clone https://github.com/your-username/AuthGuard.git
cd AuthGuard
```

### 🔹 Step 2: Setup Backend  

```sh
cd AuthGuard-Backend
npm install      # Install dependencies
npm run dev      # Start backend server on PORT 4000
```

Create a `.env` file inside `AuthGuard-Backend` and add the required environment variables:  

```sh
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
BCRYPT_SALT=10
```

### 🔹 Step 3: Setup Frontend  

```sh
cd ../AuthGuard-frontend
npm install      # Install dependencies
npm start        # Start frontend server on PORT 3000
```

---

## ⚡ Running the Application  

After running both frontend and backend, visit:  

👉 **Frontend:** `http://localhost:3000`  
👉 **Backend API:** `http://localhost:4000/api`  

---

## 📌 Technologies Used  

- **Frontend:** React.js, Redux, Tailwind CSS  
- **Backend:** Node.js, Express.js, MongoDB  
- **Authentication:** JWT (JSON Web Token), bcrypt for password hashing  
- **Other:** REST API, User Roles, Secure Authentication  

---

## 📷 Screenshot  

If your screenshot is stored in an `assets` folder, update the image path like this:  

```md
![AuthGuard Screenshot](./assets/screenshot.png)
```

Or, upload the screenshot to an online hosting service and use the URL:  

```md
![AuthGuard Screenshot](https://your-image-url.com/screenshot.png)
```

---

## 🌟 Contributing  

Feel free to fork the repository, create a new branch, and submit a pull request.  

---

## 📜 License  

This project is **open-source** and available under the **MIT License**.  

---

Let me know if you need any further modifications! 🚀
