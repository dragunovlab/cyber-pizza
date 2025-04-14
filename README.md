# Cyber Pizza 🍕

**Cyber Pizza** is a retro-inspired, pixel-art-themed pizzeria that brings the nostalgia of classic video games to your plate.  
Built with **Next.js**, **TypeScript**, **Prisma**, and **YooKassa**, it merges old-school aesthetics with modern full-stack technologies.  
Features include product filtering, authentication, real-time UI microinteractions, and smooth online payments.

---

## 🍕 Cyber Pizza — A Retro-Modern eCommerce Platform for Pizza Ordering

Step into the pixelated world of **Cyber Pizza**, where the charm of 8-bit games meets next-gen web development.  
This full-stack project showcases:

- 💾 A retro gaming-inspired **UI/UX**
- ⚙️ Advanced **Next.js 14** architecture
- 🛠️ Full integration with payment and email systems
- 📱 Optimized experience for both desktop and mobile users

From pixel-art pizza icons to microanimations and neon glow buttons, every detail is designed to teleport you to a cyber-arcade pizza parlor — and back again with a real-world order.

![Screenshot](./public/preview.png)

---

## 🔗 Figma Prototype

👉 **View the pixel-perfect design in Figma:**  
- [Open Figma Prototype](https://www.figma.com/proto/Ny6HqEo3oFM1DXkWustwAH/Untitled?node-id=156-2&t=Zn6Z12Dtzh9vL8yY-1)

---

## 🚀 Features

- ✅ **Server-side product filtering** with URL parameters  
- ✅ **Product view**, **add to cart**, **checkout**  
- ✅ **Authentication** via email/password, GitHub, Google  
- ✅ **Account confirmation** via email  
- ✅ **Profile editing** and **order history**  
- ✅ **Payment via YooKassa**  
- ✅ **Email notifications** (registration, order, payment) via Resend  
- ✅ **Parallel Routes support** (modal or separate product view)  
- ✅ **Real-world use** of Client and Server components  
- ✅ **Deployment on Vercel**, PostgreSQL database  
- ✅ **Pixel-art themed UI** and **responsive animations**

---

## 🎮 UX/UI Design

The experience is built to delight:

- 🎨 Pixel-art style combined with **TailwindCSS** + **ShadCN UI**
- 🕹️ Retro fonts, vibrant colors, and 8-bit-inspired components
- ⚡ Microinteractions using `react-hot-toast` and `nextjs-toploader`
- 📱 Mobile-friendly layout with intuitive navigation
- 🧠 Fast, reactive state changes with **Zustand**
- 🧾 Clean, clear checkout and order flow

---

## 🛠 Technologies Used

| Technology                   | Purpose                                                  |
|-----------------------------|----------------------------------------------------------|
| **Next.js 14**              | App Router, Parallel Routes, Server Actions              |
| **TypeScript**              | Safe and scalable development                            |
| **TailwindCSS + ShadCN UI** | Fast styling and ready-made UI components                |
| **Prisma + PostgreSQL**     | ORM and database                                         |
| **NextAuth**                | Authentication and sessions                              |
| **React Hook Form + Zod**   | Forms and data validation                                |
| **Zustand**                 | Simple global state management                           |
| **Resend**                  | Email notifications                                      |
| **YooKassa**                | Online payments                                          |

> Also used: `lucide-react`, `react-use`, `react-hot-toast`, `react-insta-stories`, `nextjs-toploader`.

---

## 📸 Screenshots

### 🏠 Home Page  
<img src="./public/screenshot1.png" width="600" alt="Home page">

### 🍕 Product Page  
<img src="./public/screenshot2.png" width="600" alt="Product page">

---

## ⚙️ How to Run the Project

1. Clone the repository and install dependencies:

```bash
git clone https://github.com/your-username/cyber-pizza.git
cd cyber-pizza
npm install

2. Create a .env file based on .env.example and add your keys:

cp .env.example .env

3. Generate Prisma and set up the database:

npx prisma generate
npx prisma db push

4. Run the project:

npm run dev

5. Open the app in the browser at http://localhost:300
