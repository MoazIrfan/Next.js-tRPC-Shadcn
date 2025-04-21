# tRPC App

**Next.js (App Router) tRPC TailwindCSS shadcn/ui**

This Mini Order Status Tracker app is built using Next.js (App Router), tRPC, TailwindCSS, and Shadcn UI.

An end-to-end **Order Status Tracker**.

Focuses on type safety, scalable architecture, and seamless developer experience.

[![📟](https://raw.githubusercontent.com/MoazIrfan/wc-cli/main/.github/ordertracker.gif)](./../../)

## Demo
https://www.loom.com/share/c9886124ec344654a252a23992346f00?sid=a083f674-e351-4964-9ea3-12660700f3c7

---

[![⚙️](https://github.com/MoazIrfan/wc-cli/raw/main/.github/usage.png)](./../../)
## Tech Stack

> Bootstrapped with [**Create T3 App**](https://create.t3.gg/) — the full-stack typesafe framework.

- **Frontend**
  - [Next.js](https://nextjs.org/) (App Router)
  - [React Table (TanStack Table v8)](https://tanstack.com/table/v8) — powerful, headless tables
  - [shadcn/ui](https://ui.shadcn.dev/) — customizable UI components
  - [Tailwind CSS](https://tailwindcss.com/) — utility-first CSS framework
  - [Lucide-react](https://lucide.dev/) — icon library

- **Backend**
  - [tRPC](https://trpc.io/) — end-to-end type-safe APIs
  - [Prisma ORM](https://www.prisma.io/) — database access toolkit
  - [Zod](https://zod.dev/) — runtime schema validation

- **Database**
  - [PostgreSQL](https://www.postgresql.org/) — production-ready relational database

- **Utilities**
  - [TypeScript](https://www.typescriptlang.org/) — static typing
  - [ESLint + Prettier](https://eslint.org/) — linting and formatting

---

[![📟](https://github.com/MoazIrfan/wc-cli/raw/main/.github/install.png)](./../../)
## Install

Follow these steps to run the project locally:

### 1. Clone the Repository

```bash
git clone https://github.com/MoazIrfan/Next.js-tRPC-Shadcn.git

cd Next.js-tRPC-Shadcn
````

### 2. Install Dependencies

```bash
npm install
````

### 3. Push Prisma Schema and Seed Database

```bash
npx prisma db push

npm run seed
````

### 4. Run Development Server

```bash
npm run dev
````

your app will be running at http://localhost:3000

---


## ✨ Features

- 📋 **React Table (TanStack v8)** for flexible table handling.

- 🔍 **Server-side Search** by Customer Name.

- 🔎 **Server-side Filter** by Fulfillment Status.

- 🔄 **Server-side Pagination** Data in small chunks.

- 🎨 **Status with Color Tag** for easy visual cues (Pending, Fulfilled, Cancelled, etc).

- ⚡ **Optimized API Calls** via tRPC.

- 📊 **shadcn/ui** for consistent, accessible components.

- 🛠️ **Prisma ORM** for smooth database queries.

- 🛡️ **Strict Type Safety** from DB to UI.

- 🚀 **modern** UI.
---


## 🧪 Project Structure

```bash
/
├── src/
│   ├── app/
│   │   ├── _components/
│   │   │   └── OrdersTable.tsx
│   │   ├── api/
│   │   │   └── trpc/
│   │   │       └── routes
│   │   ├── layout.tsx
│   │   └── page.tsx
│   ├── components/
│   │   ├── ui/
│   │   │   ├── button.tsx
│   │   │   ├── input.tsx
│   │   │   ├── loader.tsx
│   │   │   ├── select.tsx
│   │   │   └── table.tsx
│   ├── lib/
│   ├── prisma/
│   ├── server/
│   │   └── (trpc backend logic)
│   ├── styles/
│   └── utils/
├── prisma/
│   └── schema.prisma
├── public/
├── .env
├── package.json
├── README.md
└── next.config.mjs

```
<<<<<<< HEAD

<br>

[![📃](https://raw.githubusercontent.com/MoazIrfan/wc-cli/main/.github/license.png)](./../../)
## License

MIT © [Moaz Irfan](https://twitter.com/MoazIrfan/)

<br>

[![🙌](https://github.com/MoazIrfan/wc-cli/raw/main/.github/connect.png)](./../../)

## Connect

<div align="left">
    <p>
    <a href="https://github.com/MoazIrfan">
        <img alt="GitHub @MoazIrfan" align="center" src="https://img.shields.io/badge/GITHUB-gray.svg?colorB=6cc644&style=flat" />
    </a>&nbsp;
    <a href="https://twitter.com/MoazIrfan/">
        <img alt="Twitter @MoazIrfan" align="center" src="https://img.shields.io/badge/TWITTER-gray.svg?colorB=1da1f2&style=flat" />
    </a>&nbsp;
    <a href="https://moazirfan.com/">
        <img alt="Site: moazirfan.com" align="center" src="https://img.shields.io/badge/MY%20SITE-gray.svg?colorB=4D2AFF&style=flat" />
    </a>&nbsp;
    <a href="https://www.linkedin.com/in/moazirfan/">
        <img alt="LinkedIn @MoazIrfan" align="center" src="https://img.shields.io/badge/LINKEDIN-gray.svg?colorB=0077b5&style=flat" />
    </a>&nbsp;
</p>
</div>
=======
>>>>>>> dad171898a12d6e7b8e6e3bddee5510e04594416
