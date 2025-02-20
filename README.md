## 1Store Dashboard - Powerful Backend for the Seamless Frontend

### Key Features:

- 🏗️ ShadCN UI for the admin panel  
- 🖥️ CMS, Admin, and API in one dashboard  
- 🏬 Manage multiple stores with auto-generated APIs  
- 📂 CRUD for categories  
- 📦 CRUD for products  
- 🖼️ Upload & update product images  
- 🎨🔠 Manage filters like "Color" & "Size"  
- 🏷️ CRUD for billboards (category or standalone)  
- 🔍📄 Search with pagination  
- 🌟 Feature products on the homepage  
- 📊📦 View orders & sales  
- 📈 Revenue graphs  
- 🔐 Clerk authentication  
- 🛒 Order management  
- 💳 Stripe checkout  
- 🔄 Stripe webhooks  
- 🗄️ MySQL + Prisma  

### Prerequisites

**Node version 14.x**

### Cloning the repository

```shell
git clone https://github.com/HarshalHarle/1store-dashboard.git
```

### Install packages

```shell
npm i
```

### Setup .env file


```js
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/

DATABASE_URL=

NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=

STRIPE_API_KEY=
STRIPE_WEBHOOK_SECRET=

FRONTEND_STORE_URL=
```

### Setup Prisma

Add MySQL Database

```shell
npx prisma generate
npx prisma db push
```

### Start the app

```shell
npm run dev
```

## Available commands

Running commands with npm `npm run [command]`

| command         | description                              |
| :-------------- | :--------------------------------------- |
| `dev`           | Starts a development instance of the app |
