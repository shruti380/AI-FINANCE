
# AI Finance Platform 💰

A full-stack AI-powered finance platform built with **Next.js**, **Tailwind CSS**, **React**, **Gemini AI**, **Prisma**, and **Shadcn UI**.

---

## 🔧 Tech Stack

- **Next.js**
- **Tailwind CSS**
- **Prisma**
- **Clerk** (Authentication)
- **Gemini AI**
- **Resend API**
- **Shadcn UI**

---

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/shruti380/AI-FINANCE.git

````

### 2. Install Dependencies

```bash
npm install
```

### 3. Create `.env` File

Create a `.env` file in the root with these variables:

```env
DATABASE_URL=
DIRECT_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

GEMINI_API_KEY=
RESEND_API_KEY=
ARCJET_KEY=
```

### 4. Prisma Setup

```bash
npx prisma generate
npx prisma db push
```

### 5. Start the Project

```bash
npm run dev
```

---

## 📌 Notes

* Make sure your database is running and accessible.
* Clerk handles authentication routes automatically.
* Gemini AI powers finance-related smart features.

---

