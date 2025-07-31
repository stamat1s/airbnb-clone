# Airbnb Clone 🏠

A full-stack Airbnb clone built with **Next.js**, **React**, **TypeScript**, **Tailwind CSS**, **Prisma**, and **MongoDB**. Includes user authentication, listing creation, bookings, interactive maps, and more.

---

## 🚀 Features

- ✅ User Authentication (Sign Up / Login / Logout)
- ✅ Create and manage property listings
- ✅ Book listings with availability checks
- ✅ Interactive maps with Leaflet
- ✅ Responsive UI using Tailwind CSS
- ✅ MongoDB database with Prisma ORM
- ✅ Secure API with error handling and validation

---

## 🧰 Tech Stack

- **Frontend**: Next.js, React, TypeScript
- **Styling**: Tailwind CSS
- **Maps**: Leaflet (OpenStreetMap)
- **Backend**: Next.js API Routes
- **Database**: MongoDB with Prisma
- **Authentication**: NextAuth or custom JWT
- **Deployment**: Vercel / Railway / Render

---

## 📦 Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/stamat1s/airbnb-clone.git
   cd airbnb-clone
   ```
2. **Install dependencies**

   ```npm install``` and install all other required libraries

3. **Set environment variables**

   Create a .env.local file in the root directory and add:
   
- DATABASE_URL=MONGODB_URI
- NEXTAUTH_SECRET = your-super-secure-random-secret
- GITHUB_ID =
- GITHUB_SECRET =
   
- GOOGLE_CLIENT_ID = 
- GOOGLE_CLIENT_SECRET = 
   
- NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME = ""
(Also, set ```uploadPreset``` prop in ImageUpload.tsx from Cloudinary CDN.)

4. **Run database generate and initialization**

   ```npx prisma db generate```
   ```npx prisma init```

6. **Start the development server**

   ```npm run dev```
