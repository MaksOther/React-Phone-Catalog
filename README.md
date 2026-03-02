# 📱 Phone Catalog

A modern full-stack Phone Catalog web application built with React, TypeScript, Supabase, and Node.js.

This project provides a dynamic product catalog, advanced search, internationalization, animations, delivery API integration, and secure Stripe payments.

---

# 🚀 Tech Stack

## Frontend
- React
- Vite
- TypeScript
- SCSS Modules
- Framer Motion
- Swiper.js
- i18next
- Fuse.js

## Backend & Services
- Node.js
- Supabase (Database, Authentication, Storage)
- NovaPoshta API (Delivery integration)
- Stripe (Payment processing)

---

# ✨ Features

- Product catalog with detailed phone pages
- Fuzzy search using Fuse.js
- Multi-language support with i18next
- Smooth UI animations using Framer Motion
- Shopping cart functionality
- Secure Stripe checkout
- Delivery integration via NovaPoshta API
- Supabase authentication and database
- Responsive design for all devices

---

# 📁 Project Structure

```
phone-catalog
│
├── public
│
├── src
│   ├── assets
│   ├── components
│   ├── pages
│   ├── services
│   ├── hooks
│   ├── utils
│   ├── styles
│   ├── App.tsx
│   └── main.tsx
│
├── server
│   └── index.js
│
├── .env
├── package.json
├── tsconfig.json
└── README.md
```

---

# ⚙️ Installation

## 1 Clone the repository

```bash
git clone https://github.com/Team-Project-Phone-catalog/team-project-phone-catalog.github.io.git
cd team-project-phone-catalog.github.io
```

## 2 Install dependencies

```bash
npm install
```

or

```bash
yarn install
```

---

# 🔐 Environment Variables

Create a `.env` file in the root directory and add:

```
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
VITE_STRIPE_PUBLIC_KEY=your_stripe_public_key
NOVAPOSHTA_API_KEY=your_novaposhta_api_key
```

---

# ▶️ Run the Project

## Development

```bash
npm run dev
```

## Build

```bash
npm run build
```

## Preview production build

```bash
npm run preview
```

---

# 🧪 Stripe Test Card

Use this card for testing payments:

```
Card Number: 4242 4242 4242 4242
Expiration: Any future date
CVC: Any 3 digits
```

---

# 🌍 Internationalization

Translations are stored in:

```
public/locales
```

To add a new language:

1. Create a new folder inside `/locales`
2. Add translation JSON files
3. Register the language in the i18next configuration

---

# 📦 API Integrations

## NovaPoshta API

Used for:

- City search
- Warehouse selection
- Delivery data

## Stripe

Used for:

- Checkout
- Payment processing
- Order confirmation

---

# 🛠 Supabase

Supabase is used for:

- Authentication
- Product database
- Storage
- Backend functionality

If running Supabase locally:

```bash
supabase start
```

---

# 🤝 Contributing

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature/your-feature
```

3. Commit changes
4. Push to your branch
5. Open a Pull Request

---

# 📄 License

MIT License

---

# 👨‍💻 Authors

Team Project — Phone Catalog

---

⭐ If you like the project, please give it a star on GitHub.
