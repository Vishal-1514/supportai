# 🤖 SupportAI – AI Chatbot SaaS Platform

A full-stack AI Chatbot SaaS platform that enables businesses to create and deploy AI-powered chatbots on their websites. Built with **Next.js**, **MongoDB**, **Scalekit**, and **Vercel**, the platform supports multi-tenant organizations, secure authentication, and an embeddable chatbot widget.

## 🚀 Live Demo

🔗 https://supportai-ia6a.vercel.app/

---

## 📌 Features

- 🏢 Multi-tenant SaaS architecture
- 🔐 Secure Authentication with Scalekit
- 👥 Organization and workspace management
- 💬 AI-powered chatbot
- 🌐 Embeddable chatbot widget for external websites
- 📊 Admin dashboard for chatbot management
- 💾 MongoDB database for users, organizations, and chat history
- ⚡ Built using Next.js App Router
- ☁️ Deployed on Vercel
- 📱 Responsive UI

---

## 🛠️ Tech Stack

### Frontend
- Next.js 15+
- React.js
- Tailwind CSS
- TypeScript

### Backend
- Next.js API Routes
- Node.js

### Database
- MongoDB
- Mongoose

### Authentication
- Scalekit

### Deployment
- Vercel

---

## 📂 Project Structure

```
supportai/
│
├── app/                 # Next.js App Router
├── components/          # Reusable UI Components
├── lib/                 # Utility Functions
├── models/              # MongoDB Models
├── actions/             # Server Actions
├── hooks/               # Custom Hooks
├── public/              # Static Assets
├── styles/              # Global Styles
└── middleware.ts
```

---

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/your-username/supportai.git
```

### Navigate into project

```bash
cd supportai
```

### Install dependencies

```bash
npm install
```

### Configure Environment Variables

Create a `.env.local` file and add:

```env
MONGODB_URI=

SCALEKIT_CLIENT_ID=
SCALEKIT_CLIENT_SECRET=
SCALEKIT_ENV_URL=

JWT_SECRET=

NEXT_PUBLIC_APP_URL=
```

> Replace the values with your own credentials.

---

## ▶️ Run Locally

```bash
npm run dev
```

Visit:

```
http://localhost:3000
```

---

## 🚀 Deployment

Deploy easily using **Vercel**.

```bash
npm run build
```

Push your code to GitHub and import the repository into Vercel.

---

## 💡 How It Works

1. User signs in securely.
2. Creates an organization/workspace.
3. Configures chatbot settings.
4. Generates an embeddable widget.
5. Adds the widget to their website.
6. Visitors chat with the AI assistant.
7. Conversations are stored in MongoDB.
8. Dashboard displays chatbot and organization data.

---

## 📸 Screenshots

> Add screenshots of:

- Login Page
- Dashboard
- Organization Management
- Chat Interface
- Embedded Chat Widget

Example:

```
/screenshots/dashboard.png
/screenshots/chatbot.png
```

---

## 📈 Future Improvements

- AI model customization
- Chat analytics dashboard
- Custom branding
- File upload support
- Multiple AI providers
- Role-based permissions
- Knowledge base integration
- Real-time notifications

---

## 👨‍💻 Author

**Vishal Verma**

- LinkedIn: https://linkedin.com/in/your-profile
- GitHub: https://github.com/Vishal-1514

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

---

## 📄 License

This project is licensed under the MIT License.
