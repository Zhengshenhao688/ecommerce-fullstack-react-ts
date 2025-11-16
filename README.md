# 🛍️ Full-Stack E-Commerce Project (React + TypeScript + Node.js)

A complete **full-stack E-Commerce system**, containing:

- 🖥️ **Frontend:** React + TypeScript + Vite
- 🔗 **Backend:** Node.js + Express + SQLite
- 🧪 **Testing:** Vitest + React Testing Library
- 🛒 **Features:** Full shopping cart, checkout flow, orders, tracking timeline, and full UI/UX.

---

# 📂 Project Structure

```
ecommerce-project-ts/
│
├── frontend/       # React + TypeScript + Vite SPA
├── backend/        # Node.js + Express API server (SQLite DB)
└── README.md       # Main documentation
```

---

# 🚀 Features

## 🖥️ Frontend (React + TypeScript)
- Product grid and detailed product pages  
- Full shopping cart (add, update, remove)  
- Delivery options with estimated dates  
- Checkout summary (subtotal, tax, delivery fee, total)  
- Order confirmation  
- Orders list page  
- Order tracking timeline  
- Axios API integration  
- Component / page tests using Vitest 
- Fully typed with TypeScript  

## 🔗 Backend (Node.js + SQLite, course-provided)

The backend for this project was **provided as part of the course** and serves as the API layer for the React frontend.

It includes:

- A Node.js server (`server.js`)
- A local **SQLite** database (`database.sqlite`)
- A REST-style API used by the frontend
- Route handlers under `/routes` and database models under `/models`
- Official backend documentation located at:

```
backend/documentation.md
```
---

# 🛠️ Tech Stack

### Frontend
- React 18  
- TypeScript  
- Vite  
- React Router  
- Axios  
- CSS Modules  
- Vitest  
- React Testing Library  
- user-event  

### Backend
- Node.js  
- Express  
- SQLite  
- CORS  
- Nodemon  

---

## 🖼️ Preview

### 🏠 Home Page
![Home](assets/home.png)

### 🛒 Checkout Page
![Checkout](assets/checkout.png)

### 📦 Orders Page
![Orders](assets/orders.png)

### 🚚 Tracking Page
![Tracking](assets/tracking.png)

---

# 🧪 Running Tests (Frontend)

```sh
cd frontend
npx vitest
```

Tests include:
- Component testing  
- Page testing  
- User interaction flows  
- Cart and checkout logic  

---

# 📁 Detailed Structure

```
ecommerce-project-ts/
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── assets/
│   │   ├── components/
│   │   ├── pages/
│   │   │   ├── home/
│   │   │   ├── checkout/
│   │   │   ├── orders/
│   │   │   ├── tracking/
│   │   │   └── notfound/
│   │   ├── types/
│   │   ├── utils/
│   │   ├── App.tsx
│   │   ├── main.tsx
│   │   ├── index.css
│   │   └── vite-env.d.ts
│   ├── package.json
│   ├── vitest.config.ts
│   ├── setupTests.js
│   └── README.md
│
├── backend/
│   ├── backend/
│   ├── defaultData/
│   ├── routes/
│   ├── models/
│   ├── patches/
│   ├── images/
│   ├── server.js
│   ├── database.sqlite
│   ├── package.json
│   ├── documentation.md
│   ├── troubleshooting.md
│   └── README.md
│
└── README.md
```

---

# ▶️ Getting Started

## 1️⃣ Clone the repository

```sh
git clone https://github.com/zhengshenhao688/ecommerce-project-ts.git
cd ecommerce-project-ts
```

---

# ▶️ Running the Backend

```sh
cd backend
npm run dev
```

Backend will start at:

```
http://localhost:3000
```

### API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | /products | Get all products |
| GET | /products/:id | Get one product |
| GET | /delivery-options | Shipping options |
| POST | /cart | Submit cart |
| GET | /orders | All orders |
| GET | /orders/:id | Order details |

---

# ▶️ Running the Frontend

```sh
cd frontend
npm install
npm run dev
```

Frontend runs at:

```
http://localhost:5173
```
---

# 📄 Future Improvements

- JWT authentication  
- Admin dashboard  
- Stripe-like payment integration  
- Docker deployment  
- CI/CD pipeline  
- Image uploading  
- Database migrations  

---

