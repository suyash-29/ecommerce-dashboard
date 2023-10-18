# E-Commerce Dashboard 

Welcome to the README for the Dashboard of your E-Commerce Store. This dashboard is a powerful and versatile admin panel that serves as a Content Management System (CMS), Admin interface, and API generator for managing multiple vendors and stores. Whether you're running a "Shoe store," a "Laptop store," a "Suit store," or any other e-commerce business, this dashboard is your all-in-one solution.

## Deployed Website
Visit our E-Commerce dshboard at [Store-link](https://ecommerce-dashboard-dun.vercel.app/).

## Table of Contents

1. [Overview](#overview)
2. [Features](#features)
3. [Getting Started](#getting-started)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Stripe Payment Integration](#stripe-payment-integration)
7. [Thank you](#Thank you)
## Overview

This E-Commerce dashboard is a modern, user-friendly, and secure platform for online shopping. It is built using React.js and Next.js for a fast and efficient user experience. The website incorporates clerk authentication integration to ensure secure and convenient login . Using this you will be able manage  products, orders, and other data of the e-commerce store, which can be found in another repository on my GitHub.

## Features

-**Single CMS for Multiple Vendors/Stores:** This dashboard allows you to control multiple vendors or stores through a single CMS. You can easily manage distinct stores 
                                           such as "Shoe store," "Laptop store," or "Suit store" from a centralized location. The CMS generates API routes for each store 
                                            individually.
- **Category Management:** Create, update, and delete product categories effortlessly. Organize your products for easy navigation.
- **Product Management:** Handle product listings with ease. You can create, update, and delete products as well as upload multiple product images, giving you the flexibility to change them whenever necessary.
- **Filter Creation:** Create, update, and delete filters such as "Color" and "Size" to categorize your products effectively. Match these filters with product attributes in the creation form.
-**Billboard Management**: Manage prominent messages and announcements on top of your store pages. Attach them to a single category or use them as standalone billboards. The dashboard generates API routes for all these cases.
- **Powerful Search**: Easily search through all categories, products, sizes, colors, billboards, and more. The search feature includes pagination for seamless navigation.
- **Featured Products:** Highlight specific products as "featured" to display them prominently on the homepage, improving visibility and sales.
- **Order and Sales Management:** Keep track of your orders and sales, including the ability to create, view, and analyze sales data. Visualize your revenue through graphs and gain insights into your store's performance.
- **Clerk Authentication:** Learn about **Clerk** Authentication, a secure and efficient way to manage user authentication and access control.
- **Order Creation:** Streamline the order creation process, making it easy to manage customer orders and fulfill them promptly.
- **Stripe Checkout:** Utilize Stripe integration for secure and convenient checkout processes.
- **Stripe Webhooks:** Handle Stripe webhooks to ensure smooth payment processing and order management.
- **Database Stack:** The dashboard is built using **MySQL**, **Prisma**, and **PlanetScale** to provide a robust and scalable database solution.
- **Dark mode:** you switch between dark , light and system mode from a button on navbar .
- **Image Upload:** imges of billbaord and products will be handled using **Cloudinary**.

## Getting Started

Before running the project, make sure you have Next.js and npm (Node Package Manager) installed on your system.

## Installation

1. Clone the repository for the E-Commerce dashboard:
   ```bash
   git clone https://github.com/suyash-29/ecommerce-dashboard/
   ```
2. Navigate to the project directory:
   ```bash
   cd ecommerce-dashboard
   ```
3. Setup Environement variables
   ```bash
   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
   CLERK_SECRET_KEY=
   NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
   NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
   NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
   NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/
   DATABASE_URL=
   NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=
   STRIPE_API_KEY=
   FRONTEND_STORE_URL=http:
   STRIPE_WEBHOOK_SECRET=
   ```
   
5. Install the project dependencies:
   ```bash
   npm install
   ```

6. Database genration:
   ```bash
   npx prisma generate
   npx prisma db push
   ```
6. Start the development server:
   ```bash
   npm run dev
   ```

## Usage

Once you've set up the project, you can access the E-Commerce dashboard website locally at http://localhost:3000.

Customize the content, product listings, and design to suit your business needs from the dashboard.

## Stripe Payment Integration

Stripe has been integrated into the project to handle payments securely. You'll need to set up your Stripe account and add your API keys in the appropriate configuration files(.enc file). Stripe will confrim payment from store and pass true in orders if payment is successful  and add phone number  and address of the customer if not will return false For more details on Stripe integration, please refer to the Stripe documentation.

## Thank you

Thank you for choosing our E-Commerce Store Website template. If you have any questions or need further assistance, please don't hesitate to contact us.

Happy Selling! 🛒🚀
