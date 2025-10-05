# HelpDesk Mini - Server

Minimal Express + MongoDB backend.

## Quick Start

1. Clone the repo
`
git clone https://github.com/MohamadxMortuz/Server_HelpDesk-Mini.git 
cd Server_HelpDesk-Mini/server
`

2. Configure environment
Create server/.env with:
- MONGO_URI=your-mongodb-connection-string
- JWT_SECRET=your-secret
- PORT=5000

3. Install dependencies
`
npm install
`

4. Run the server
`
npm run start
`

## Project Structure
```text
server/
├── config/
│   └── db.js
├── controllers/
│   ├── authController.js
│   ├── commentController.js
│   └── ticketController.js
├── middleware/
│   ├── auth.js
│   ├── errorHandler.js
│   ├── idempotency.js
│   └── rateLimit.js
├── models/
│   ├── Activity.js
│   ├── Comment.js
│   ├── Ticket.js
│   └── User.js
├── routes/
│   ├── authRoutes.js
│   ├── commentRoutes.js
│   └── ticketRoutes.js
├── seed.js
├── server.js
└── package.json
```
## Useful Commands
- npm run start  Start the server
- npm run seed   Seed sample data
