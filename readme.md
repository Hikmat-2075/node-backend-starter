# Express Prisma Backend Starter

Production-ready Express.js backend starter template using Prisma ORM, JWT authentication, and a modular domain-based architecture.

This template is designed to help you quickly build scalable and maintainable Node.js backend applications.

---

## 🚀 Features & Tech Stack

- Node.js (>= 18)
- Express.js
- Prisma ORM
- JWT Authentication
- Modular / Domain-based structure
- Soft delete support
- Request validation (Joi)
- Logging (Winston)
- File upload (Multer)
- WebSocket (Socket.IO)
- Babel build system
- Jest testing ready

---

## 📁 Project Structure

src/
├─ domains/ # Business domains (controller, service, repository)
├─ middlewares/ # Express middlewares
├─ routes/ # API routes
├─ utils/ # Helpers & utilities
├─ config/ # App configuration
├─ prisma/ # Prisma schema & client
└─ server.js # Application entry point


---

## ⚙️ Setup & Installation

Clone repository:
```bash
git clone https://github.com/USERNAME/REPOSITORY.git
cd REPOSITORY
Install dependencies:

npm install
Create .env file:

NODE_ENV=development
PORT=3000

DATABASE_URL="postgresql://user:password@localhost:5432/db_name"

JWT_SECRET="your_jwt_secret"
JWT_EXPIRES_IN="1d"
🧪 Prisma Commands
npx prisma init
npm run prisma:generate
npm run prisma:migrate
npm run prisma:studio
🛠 Development & Production
Run development server:

npm run dev
Build project:

npm run build
Run production build:

npm start
🧩 CLI Utility
Generate a new domain module:

npm run make:domain
📄 License
ISC License

👤 Author
Hikmat Arif Nugraha

⭐ Feel free to fork and use this template for your projects