
# E-Commerce Frontend

A simple Next.js shopping website with cart, checkout, and multiple payment options.

## What Does This Do?

**CUSTOMER FEATURES:**

✓ Browse products  
✓ Search and filter  
✓ Add to cart  
✓ Checkout (COD, Card, bKash, Nagad)  
✓ View orders  

**ADMIN FEATURES:**

✓ Manage products  
✓ View orders  
✓ Manage customers  

---

## What You Need

- **Node.js 18+** - Download from https://nodejs.org/
- **npm** - Comes with Node.js
- **Backend** - Spring Boot running on port 8080

---

## Quick Setup

### STEP 1: Download

git clone https://github.com/smrefat02/Ecommerce-Frontend-part.git
cd Ecommerce-Frontend-part



### STEP 2: Install

npm install



*(Wait 2-3 minutes)*

### STEP 3: Create .env.local File

Create `.env.local` in root folder:

NEXT_PUBLIC_API_BASE_URL=http://localhost:8080
NEXT_PUBLIC_USE_API_PROXY=true
API_PROXY_TARGET=http://localhost:8080



### STEP 4: Start Backend

Make sure backend is running on: http://localhost:8080

### STEP 5: Start Frontend

npm run dev


**Open browser:** http://localhost:3000

**Done!** 



---

## Commands

| Command | What It Does |
|---------|--------------|
| `npm run dev` | Start development (port 3000) |
| `npm run build` | Build for production |
| `npm start` | Start production server |

---

## Technology

- Next.js 15
- React 19
- TypeScript
- CSS3

---

## Troubleshooting

**Problem:** npm not found  
**Solution:** Install Node.js from nodejs.org

**Problem:** Cannot connect to backend  
**Solution:** Start backend on port 8080

**Problem:** Port 3000 in use  
**Solution:** Run `npm run dev -- -p 3001`

---

## How to Use

**Customers:**
1. Browse products → Add to cart
2. Go to checkout → Select payment
3. Place order → View in orders

**Admin:**
1. Login as admin
2. Manage products and orders

---

## Payment Options

✓ Cash on Delivery (COD)  
✓ Credit/Debit Card  
✓ bKash  
✓ Nagad  

---

## Backend

This frontend needs a **Spring Boot backend** running on port 8080.

**Backend Repo:** [https://github.com/smrefat02/E-Commerce-Backend-Part]

---

## Deployment

**Deploy to Vercel:**
1. Push to GitHub
2. Go to vercel.com
3. Import repository
4. Add environment variables
5. Deploy!

---

## Need Help?

- **GitHub:** https://github.com/smrefat02/Ecommerce-Frontend-part
- **Email:** s.m.refat03@gmail.com

