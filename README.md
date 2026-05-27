# 🏗️ AI Site Builder Platform

An AI-powered full-stack website builder platform built using React, TypeScript, and Express.js. This application allows users to generate modern websites using simple text prompts powered by OpenAI models.

Users can describe the type of website they want, and the platform automatically generates layouts, UI sections, and website content using AI. The project includes authentication, responsive UI, backend API integration, and AI-powered website generation workflows.

---

# 🚀 Features

## 👤 User Features

- User authentication
- Generate websites using prompts
- AI-powered content generation
- Dynamic website layouts
- Responsive generated UI
- Real-time generation experience
- Clean modern interface
- Prompt-based customization

---

## 🤖 AI Features

- AI website generation
- AI section/content generation
- Prompt-to-UI workflow
- OpenAI model integration
- Dynamic content creation
- AI-powered design assistance

---

## 🛠️ Backend Features

- REST API with Express.js
- AI prompt processing
- OpenAI API integration
- PostgreSQL database support
- Authentication handling
- Stripe integration support

---

# 🧰 Tech Stack

## Frontend
- React.js
- TypeScript
- Vite
- Tailwind CSS
- Axios
- React Router DOM

## Backend
- Node.js
- Express.js
- TypeScript
- Prisma ORM
- PostgreSQL

## Authentication
- Better Auth

## AI Integration
- OpenAI API

## Payments
- Stripe

---

# 📂 Project Structure

```bash
project-root/
│
├── client/         # React Frontend
├── server/         # Express Backend
│
└── README.md
```

---

# ⚙️ Environment Variables

## Frontend `.env`

Create a `.env` file inside the `client` folder and add:

```env
VITE_BACKEND_URL=http://localhost:5000
```

---

## Backend `.env`

Create a `.env` file inside the `server` folder and add:

```env
TRUSTED_ORIGINS=
BETTER_AUTH_URL=
NODE_ENV=
DATABASE_URL=
BETTER_AUTH_SECRET=
AI_API_KEY=
STRIPE_SECRET_KEY=
STRIPE_WEBHOOK_SECRET=
```

---

# 🔧 Installation & Setup

## 1️⃣ Clone Repository

```bash
git clone https://github.com/ahemad02/Site-Builder.git
```

---

## 2️⃣ Move Into Project Folder

```bash
cd site-builder
```

---

# ▶️ Frontend Setup

## Go to client folder

```bash
cd client
```

## Install dependencies

```bash
npm install
```

## Start frontend server

```bash
npm run dev
```

Frontend will run on:

```bash
http://localhost:5173
```

---

# ▶️ Backend Setup

## Open new terminal

## Go to server folder

```bash
cd server
```

## Install dependencies

```bash
npm install
```

## Setup Prisma

```bash
npx prisma generate
```

## Run database migrations

```bash
npx prisma migrate dev
```

## Start backend server

```bash
npm run server
```

or

```bash
npm start
```

Backend will run on:

```bash
http://localhost:5000
```

---

# 🤖 AI Website Generation

Users can:
- Describe websites using prompts
- Generate layouts instantly
- Create landing pages
- Generate AI content sections
- Build responsive website structures

Example prompts:
- "Create a modern SaaS landing page"
- "Generate a portfolio website"
- "Build an ecommerce homepage"

---

# 🔐 Authentication

Authentication is implemented using Better Auth.

Features include:
- User registration
- User login
- Secure sessions
- Protected routes

---

# 💳 Stripe Integration

The platform supports Stripe integration for:
- Premium plans
- Subscription billing
- Paid AI usage features

---

# 🗄️ Database

Prisma ORM is used with PostgreSQL for:
- User management
- Website data storage
- Authentication handling
- Billing management

---

# 📸 Main Functionalities

- AI Website Builder
- Prompt-Based Generation
- User Authentication
- Responsive UI
- AI Content Creation
- Database Integration
- Stripe Billing
- Modern Dashboard

---

# 📱 Responsive Design

The application is fully responsive and optimized for:
- Desktop
- Tablet
- Mobile Devices

# 🧪 Future Improvements

- Drag & drop editor
- Export generated websites
- Multi-page website generation
- Theme customization
- AI color palette generation
- Custom domain support
- Website publishing
- Real-time collaborative editing

---

# 🤝 Contributing

Contributions are welcome.

## Steps to Contribute

1. Fork the repository

2. Create feature branch

```bash
git checkout -b feature-name
```

3. Commit changes

```bash
git commit -m "Added new feature"
```

4. Push branch

```bash
git push origin feature-name
```

5. Create Pull Request

---

# 📄 License

This project is created for learning and portfolio purposes.


# ⭐ Support

If you liked this project:
- Star the repository
- Fork the project
- Share feedback
