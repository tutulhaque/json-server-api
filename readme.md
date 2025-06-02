# HR-App JSON Server API

This is a simple fake REST API for an HR app. It uses [json-server](https://github.com/typicode/json-server) to create a backend with employee data. It's useful for testing and building frontend apps.

## 🔗 Live API Link

You can see the API in action here:

👉 [https://json-server-api-production-20d9.up.railway.app/employees](https://json-server-api-production-20d9.up.railway.app/employees)

---

## 🚀 Why I Chose Railway Instead of Render

At first, I used **Render** to host the server, but it had some problems:

- It was **slow to load** (sometimes 10 to 30 seconds)
- Sometimes it **showed empty data** when I tried to fetch from the API

That’s why I moved to **Railway**.

With Railway:

- The API **loads faster**
- It **works more reliably**

This made it much easier to use with my frontend app.

---

## 🌐 Frontend on Netlify

I built the frontend using **React and Vite**. I used **Netlify** to host it because it’s really simple.

Here’s how I deployed it:

1. Run `npm run build` to create the production files
2. Upload the `dist` folder to Netlify
3. That’s it — the website is live!

---

## 📚 What This API Can Do

Here are some example routes:

- `GET /employees` → Get all employees
- `GET /employees/:id` → Get one employee
- `POST /employees` → Add a new employee
- `PATCH /employees/:id` → Update an employee

---

## 🛠 Tools Used

- **json-server** → for the fake REST API
- **Railway** → to host the backend
- **React + Vite** → for the frontend
- **Netlify** → to host the frontend

---
