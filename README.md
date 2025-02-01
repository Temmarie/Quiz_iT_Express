---

# **Quiz It Backend 🏆**  
This is the **Express.js backend** for **Quiz It!**, handling the **leaderboard system, user scores, and API endpoints**.  

## 🚀 **Live API**  
👉 **[Backend API](https://quiz-it-express.onrender.com)** 
---

## 📌 **Features**  
✅ Store and retrieve quiz leaderboard scores  
✅ Secure API endpoints using **Clerk authentication**  
✅ Connects to **Supabase** for database management  
✅ Easily deployable on **Render, Vercel, or Railway**  

---

## 🛠 **Tech Stack**  
- 🚀 **Express.js** – Server-side framework  
- 🛢 **Supabase** – Database for storing leaderboard scores  
- 🔐 **Clerk** – Authentication & user management
- ☁️ **Render** - Deployment and hosting

---

## 🏗 **Setup & Installation**  

### **1️⃣ Clone the Repository**  
```bash
git clone https://github.com/Temmarie/Quiz_iT_Express.git
cd Quiz-iT_Express
```

### **2️⃣ Install Dependencies**  
```bash
npm install
```

### **3️⃣ Set Up Environment Variables**  
Create a `.env.server` file in the root directory and add the following:  
```env
SUPABASE_URL=your_supabase_url
SUPABASE_KEY=your_supabase_key
CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key
```
_(Replace with actual API keys from **Supabase** and **Clerk**)_

### **4️⃣ Start the Server**  
```bash
node server.js
```
Your API should now be running at **`http://localhost:3000/`**  

---

## 🔥 **API Endpoints**  
| Method | Endpoint         | Description                     |
|--------|-----------------|---------------------------------|
| GET    | `/leaderboard`  | Fetch all user scores          |
| POST   | `/leaderboard`  | Add a new score                |
| GET    | `/user/:id`     | Get user-specific score        |
| DELETE | `/leaderboard/:id` | Delete a user's score       |

_(More endpoints can be added as needed)_  

---

## 👤 **Author**  
**Grace Tamara Ekunola**  

- 🏠 **GitHub**: [@Temmarie](https://github.com/Temmarie)  
- 🐦 **Twitter**: [@TemmarieW](https://twitter.com/TemmarieW)  
- 💼 **LinkedIn**: [Grace Tife Ekunola](https://www.linkedin.com/in/grace-tife-ekunola/)  

---

## 🤝 **Contributing**  
Got ideas? Found a bug? Feel free to fork the repo, make a **pull request**, or check the [issues page](issues/).  

---

## 📜 **License**  
This project is licensed under the **MIT License**.  

---

### 🎉 **Thank you for contributing to Quiz It! 🚀**  
