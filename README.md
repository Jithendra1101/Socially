# ✨ Socially is a Social Media App



---

## 📖 Table of Contents

1. [Tech Stack](#-tech-stack)  
2. [Features](#-features)  
3. [Repository Structure](#-repository-structure)  
4. [Setup Instructions](#-setup-instructions)  
5. [Usage](#-usage)  
6. [Roadmap](#-roadmap)  
7. [Contributing](#-contributing)  
8. [License](#-license)  

---

## 🧩 Tech Stack

- **Next.js** (App Router, Server & Client Components)  
- **TypeScript**  
- **Tailwind CSS** + **Shadcn UI**  
- **PostgreSQL** via **Prisma ORM**  
- **Clerk** for authentication  
- **UploadThing** for image/file uploads  
- **Next.js Server Actions**, suspense/loading states, and **optimistic UI** updates  

---

## ✨ Features

- Nested layouts with `loading.tsx`, `error.tsx`, and `not-found.tsx`  
- Full authentication flow (signup, login, session management)  
- Create/read posts with optional image uploads  
- Responsive UI loading states and error handling  
- Instant, optimistic updates on user interactions  
- Prisma-powered database schema and queries  
- Turnkey styling and UI components via Tailwind & Shadcn  

---

---

## 🔧 Setup Instructions

Follow these steps to run the project locally:



```bash
git clone https://github.com/Jithendra1101/Socially
cd nextjs-course

2. Install dependencies
bash
Copy
Edit
npm install

3. Configure environment variables
Copy the .env template file:

bash
Copy
Edit
cp .env.example .env
Then open the .env file and add your values:

env
Copy
Edit
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
DATABASE_URL=
UPLOADTHING_TOKEN=

4. Initialize the database
Run the Prisma migration (and optionally seed the database):

bash
Copy
Edit
npx prisma migrate dev
npx prisma db seed

5. Launch the development server
bash
Copy
Edit
npm run dev

6. Explore the app
Open your browser and visit:
👉 http://localhost:3000

