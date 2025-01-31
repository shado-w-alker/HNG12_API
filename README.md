# HNG12 Public API

## Overview

This is a **public API** that provides basic information, including:

- My registered **HNG12 Slack email**.
- The **current datetime** in ISO 8601 format (UTC).
- The **GitHub repository URL** of this project.

This API is built using **Node.js and Express**, supports **CORS**, and returns responses in **JSON format**.

## Features

- ✅ **Fast & Lightweight** – Simple GET request returns structured JSON.
- ✅ **CORS Support** – Accessible from any origin.
- ✅ **Deployed on Render** – Publicly available.

## 📌 **API Endpoint**

### **1️⃣ Get API Information**

- **Method:** `GET`
- **URL:**

https://hng12-api-1b9h.onrender.com

### **Response Format (200 OK)**

```json
{
  "email": "your-email@example.com",
  "current_datetime": "2025-01-30T09:30:00Z",
  "github_url": "https://github.com/yourusername/your-repo"
}
```

### **Headers**

| Key          | Value            |
| ------------ | ---------------- |
| Content-Type | application/json |

---

## 🎯 **Example Usage**

### **📌 Using cURL**

```sh
curl -X GET https://hng12-api-1b9h.onrender.com
```

### **📌 Using JavaScript (Fetch API)**

```javascript
fetch("https://hng12-api-1b9h.onrender.com")
  .then((response) => response.json())
  .then((data) => console.log(data))
  .catch((error) => console.error(error));
```

---

## 📝 **Postman API Documentation**

The full API documentation is available at:

[![Run in Postman](https://run.pstmn.io/button.svg)](https://documenter.getpostman.com/view/21773885/2sAYX3q3QL)

Explore and test the API directly in Postman.

---

## 🔧 **Installation & Local Setup**

To run the API locally, follow these steps:

### **1️⃣ Clone the Repository**

```sh
git clone https://github.com/yourusername/your-repo.git
cd your-repo
```

### **2️⃣ Install Dependencies**

```sh
npm install
```

### **3️⃣ Start the Server**

```sh
node server.js
```

The API will be available at:

```
http://localhost:3000/
```

---

## 🌍 **Deployment**

This API is deployed on **Render**. You can access it publicly at:

```
https://hng12-api-1b9h.onrender.com
```

---

## 📌 **Contributing**

1. Fork the repository.
2. Create a new branch:
   ```sh
   git checkout -b feature-branch
   ```
3. Commit changes and push:
   ```sh
   git commit -m "Added new feature"
   git push origin feature-branch
   ```
4. Open a **Pull Request**.

---

## 💼 **Hire Me**

For **freelance Node.js development**, check out my profile:  
👉 [Hire Node.js Developers - HNG](https://hng.tech/hire/nodejs-developers)

---

## 📜 **License**

This project is licensed under the **MIT License**. See the [`LICENSE`](LICENSE) file for details.
