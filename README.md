# 🏕️ Campers Shop Front-End

## 🤖 Introduction

Campers Shop is an e-commerce website dedicated to providing all the necessary
and fun items for camping enthusiasts. The design is user-friendly and visually
appealing, offering a wide range of camping gear to meet the needs of outdoor
adventurers.

## 🔗 Live URL

[Campers Shop](https://camper-shop-client-iota.vercel.app/products)

## 📝 Project Description

Campers Shop is designed to offer camping enthusiasts a comprehensive and
enjoyable shopping experience. The website allows users to browse, search, and
filter a variety of camping products. Users can view detailed product
information, manage their shopping cart, and complete purchases with ease. The
goal is to create a seamless and engaging online shopping experience tailored to
the needs of campers.

## 🔋 Features

- 🌟 User-friendly and visually appealing interface
- 🏠 Homepage with hero section, best-selling products, categories, featured
  products, and unique sections like testimonials
- 🛍️ Products Page with search, filter, and sorting functionalities
- 🔍 Detailed Product Page with information, ratings, and image magnifier
- 📦 Product Management for creating, updating, and deleting products
- 🛒 Cart Page with quantity controls, remove product button, and dynamic
  pricing details
- 💳 Checkout Page with user details form and payment methods
- 📄 About Us Page with contact information, map, social media links, mission
  statement, and team members
- 📱 Responsive design and state management using Redux
- ⚡ Fast loading times and intuitive navigation
- ♿ Accessibility features and interactive elements

## ⚙️ Technology Stack

- 🔧 **Front-End:**

  - [React](https://react.dev/)
  - [Redux](https://redux-toolkit.js.org/)
  - [TypeScript](https://www.typescriptlang.org/)
  - [React Router](https://reactrouter.com/en/main)
  - [Tailwind CSS](https://tailwindcss.com/)
  - [dotenv](https://www.npmjs.com/package/dotenv)

- 🔧 **Backend:**

  - [Node.js](https://nodejs.org/en/)
  - [Express](https://expressjs.com/)
  - [TypeScript](https://www.typescriptlang.org/)
  - [MongoDB](https://www.mongodb.com/)
  - [Mongoose](https://mongoosejs.com/)
  - [JWT (JSON Web Token)](https://www.npmjs.com/package/jsonwebtoken)
  - [dotenv](https://www.npmjs.com/package/dotenv)

- 🔨 **Development Tools:**

  - [VS Code](https://code.visualstudio.com/)
  - [Postman (API testing)](https://www.postman.com/)
  - [ts-node-dev](https://www.npmjs.com/package/ts-node-dev)
  - [Vite](https://vitejs.dev/)

## 🤸 Installation Guideline

Follow these steps to set up the project locally on your machine.

### 📚 Prerequisites

Make sure you have the following installed on your machine:

- 🖥️ [**Node.js**](https://nodejs.org/en) installed on your machine (v18 or
  higher recommended)
- ✏️ A code editor like [**VSCode**](https://code.visualstudio.com/)
- ✅ [**TypeScript**](https://www.typescriptlang.org/) installed
- ✅ [**npm**](https://www.npmjs.com/) installed

### 🛠️ Installation Steps

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Shahin992/Camper-shop-client
   cd Campers-Shop-client
   ```

2. **Install the project dependencies using npm:**

   ```bash
   npm install
   ```

3. **Set up environment variables:**

   Create a new file named .env in the root of your project and add the
   following content:

   ```bash
   VITE_IMAGEBB_API_KEY=your_secret
   ```

4. **Start the development server:**

   ```bash
   npm run dev
   ```

## Configuration

Create a .env file in the root directory of the project and add the following
configuration variables:

```bash
VITE_IMAGEBB_API_KEY=your_secret
```

## Usage

1. **Homepage:** Browse the hero section, best-selling products, categories,
   featured products, and unique sections like video blogs and testimonials.

   ![Homepage page](./src/assets/images/home.png)

2. **Products Page:** Use the search bar to find products by name or
   description. Apply filters for categories and price range, and sort products
   by price.

   ![Products page](./src/assets/images/products.png)

3. **Product Details Page:** View detailed information about a product,
   including name, price, stock-quantity, description, category, ratings, and
   images. Use the image magnifier effect for a closer look.

   ![Product details page](./src/assets/images/product-details.png)

4. **Cart Page:** Manage your cart by adjusting quantities, removing products,
   and viewing dynamic pricing details. Place your order if the product is in
   stock. ![Cart page](./src/assets/images/cart.png)


6. **About Us Page:** Find contact information, map location, social media
   links, mission statement, and team member bios.

   ![About page](./src/assets/images/about.png)