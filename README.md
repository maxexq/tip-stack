# 🚀 TipStack – Fast & Lightweight Dev Tips Manager  

TipStack is a **fast and lightweight** web app for storing development tips, code snippets, and best practices. Built using **Astro** for the frontend and **Go Fiber** for the backend, this project supports Markdown-based tip storage with an API and full-text search.  

## 📌 Features  
✅ **Markdown Support** – Easily paste and save tips in Markdown format  
✅ **Fast API** – Powered by **Go Fiber** for high performance  
✅ **Monorepo Architecture** – Managed with **Turborepo**  
✅ **Full-Text Search** – Quickly find stored tips  
✅ **Lightweight & Scalable** – Optimized for speed  

---

## 🏗 Tech Stack  
- **Frontend:** [Astro](https://astro.build/) ⚡  
- **Backend:** [Go Fiber](https://gofiber.io/) 🏎️  
- **Database:** SQLite / PostgreSQL (Pluggable) 🗄️  
- **Monorepo:** Turborepo for efficient development 🔥  

---

## 🚀 Getting Started  

### 1️⃣ Clone the Repository  
```sh
 git clone https://github.com/yourusername/tipstack.git
 cd tipstack
```

### 2️⃣ Install Dependencies  
```sh
 npm install
```

### 3️⃣ Start the Backend (Go Fiber)  
```sh
 cd apps/backend
 go run main.go
```

### 4️⃣ Start the Frontend (Astro)  
```sh
 cd apps/frontend
 npm run dev
```

Now visit **http://localhost:4321** to access TipStack! 🚀  

---

## 📂 Project Structure  
```
tipstack/
│── apps/
│   ├── frontend/  (Astro Frontend)
│   ├── backend/   (Go Fiber API)
│── packages/
│   ├── shared/    (Shared types and utilities)
│── turbo.json     (Turborepo config)
│── package.json   (Project dependencies)
```

---

## 📌 API Endpoints  

### **1️⃣ Create a New Tip**  
**`POST /tips`**  
```json
{
  "title": "CSS Flexbox",
  "content": "Use `display: flex` to create a flexible layout."
}
```

### **2️⃣ Get All Tips**  
**`GET /tips`**  
Response:  
```json
[
  {
    "id": 1,
    "title": "CSS Flexbox",
    "content": "Use `display: flex` to create a flexible layout."
  }
]
```

### **3️⃣ Search Tips**  
**`GET /tips/search?q=flexbox`**  
Returns tips matching the query.  

---

## 🛠 TODO / Future Improvements  
- ✅ **Authentication (JWT)** for user-based storage  
- ✅ **Tagging System** for categorizing tips  
- ✅ **Docker & CI/CD** for deployment  

---

## 📜 License  
This project is licensed under the **MIT License**.  

💡 **Contributions are welcome!** Feel free to open an issue or submit a PR. 🚀

