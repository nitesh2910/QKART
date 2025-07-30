# QKart‑Frontend

**QKart** is a React‑based e‑commerce application enabling users to browse and purchase a wide range of products, featuring user registration, login, search, responsive cart functionality, and seamless checkout flows.

---

## Tech Stack

- **Frontend**: React.js  
- **Routing**: React Router  
- **State & Hooks**: useState, useEffect  
- **UI Library**: Material‑UI or Ant Design Grid (customizable)  
- **Networking**: REST APIs (fetch / axios)  
- **UX Enhancements**: Debounced search input, form validation, conditional rendering  
- **Storage**: localStorage (session persistence)  
- **Styling**: CSS / Material‑UI / responsive design  
- **Deployment**: Vercel

---

<img width="613" height="401" alt="image" src="https://github.com/user-attachments/assets/75e17f89-d1be-4887-9eba-1b16b1306c07" />

## ⚙️ Features & Implementation Details

### 1. Registration & Login

- Built form-based **user registration** with input validation and real-time error feedback  
- Integrated registration and login flows using backend APIs  
- Stored authenticated user state in **localStorage** to maintain session between visits  
- Secured protected routes (e.g. checkout) for authenticated users only

### 2. Routing & Navigation

- Implemented routing via **React Router** for navigation between pages: Home, Products, Cart, Checkout, etc.  
- Redirects and route protection implemented for login/logout flows

### 3. Product Listing & Search

- Fetched product data from backend REST APIs using `useEffect` for optimized loading  
- Search bar implemented with **debouncing** to reduce unnecessary API calls and improve UX  
- Displayed results using responsive Material‑UI grids

### 4. Shopping Cart & Checkout

- Integrated **add-to-cart**, **remove-from-cart**, and **quantity update** functionality  
- Cart operations made via authenticated POST/GET API calls  
- Cart view adapted responsively for mobile and desktop  
- Checkout flow includes selecting or adding a delivery address and order placement logic

### 5. Deployment

- Deployed frontend application to **Vercel**  
- Automatic deployment on every push to the main branch  
- Optimized for fast global delivery via Vercel’s CDN  
- Vercel handles routing for SPA (Single Page Application) paths seamlessly  
- Live URL: [https://your-qkart.vercel.app](https://qkart-frontend-gray.vercel.app/)
