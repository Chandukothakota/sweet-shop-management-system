sweet-shop-management/
├── backend/
│   ├── prisma/
│   │   ├── schema.prisma
│   │   └── migrations/
│   ├── src/
│   │   ├── app.ts
│   │   ├── server.ts
│   │   ├── config/
│   │   │   ├── db.ts
│   │   │   └── env.ts
│   │   ├── middlewares/
│   │   │   ├── auth.middleware.ts
│   │   │   └── role.middleware.ts
│   │   ├── modules/
│   │   │   ├── auth/
│   │   │   │   ├── auth.controller.ts
│   │   │   │   ├── auth.service.ts
│   │   │   │   └── auth.routes.ts
│   │   │   ├── sweets/
│   │   │   │   ├── sweets.controller.ts
│   │   │   │   ├── sweets.service.ts
│   │   │   │   └── sweets.routes.ts
│   │   ├── utils/
│   │   │   └── jwt.ts
│   │   └── tests/
│   │       ├── auth.test.ts
│   │       └── sweets.test.ts
│   ├── .env
│   ├── package.json
│   └── jest.config.js
│
├── frontend/
│   ├── src/
│   │   ├── api/
│   │   │   └── axios.ts
│   │   ├── pages/
│   │   │   ├── Login.tsx
│   │   │   ├── Register.tsx
│   │   │   ├── Dashboard.tsx
│   │   │   └── AdminPanel.tsx
│   │   ├── components/
│   │   │   └── SweetCard.tsx
│   │   ├── App.tsx
│   │   └── main.tsx
│   ├── .env
│   └── package.json
│
└── README.md
