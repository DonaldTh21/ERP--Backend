This is the backend API for a mobile + web application designed for ERP--Small 
---

## ⚙️ Tech Stack

- Node.js + Express.js
- PostgreSQL with Knex.js
- Modular architecture for clean separation of concerns
- Ready for future expansion: Auth, PDF, Analytics, etc.

---

## 📁 Folder Structure
```bash
src/
├── config/ # DB config and setup
├── controllers/ # Route handler logic
├── routes/ # API route definitions
├── middlewares/ # For auth, error handling (future)
├── utils/ # Utility functions (future)
└── server.js # Entry point
knexfile.js
.env
```

## Get started

1. Install dependencies

   ```bash
   npm install
   ```

## Set up environment variables

Create a .env file in the root directory:

```bash
PORT=5000

DB_HOST=localhost
DB_USER=postgres
DB_PASS=yourpassword
DB_NAME=business_app
DB_PORT=5432

JWT_SECRET=supersecretkey

```

## Run Server

```bash
npm run dev      # Development mode (with nodemon)
# or
node src/server.js
```