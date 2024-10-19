
# Electro E-Commerce

Electro is a modern e-commerce platform offering a wide range of electronics such as laptops, mobiles, monitors, and headphones. This platform allows users to browse, filter, and purchase products with ease. The platform is built with the MERN stack, incorporating a responsive design and secure authentication.


## Additional Resources

- [Live Demo](https://electroecommerce.netlify.app/)
- [Client Repository](https://github.com/Rakibulislam-emon/Electro_Client)
- [Server Repository](https://github.com/Rakibulislam-emon/Electro_Server)



## Features

- **User Authentication**: Secure login and registration with Firebase.
- **Product Search & Filtering**: Advanced search functionality with filtering options by categories and price ranges.
- **Sorting & Pagination**: Sort products by price, ratings, or date of creation, with pagination for easier browsing.
- **Shopping Cart**: Add products to the cart, view item count and subtotal instantly using React Query and Axios.
- **Payment Integration**: Secure payment with Stripe.
- **Admin Dashboard**: Manage products, view purchases, and handle customer queries.
- **Responsive Design**: Optimized for all devices.


## Tech Stack

- **Frontend**: React.js, Tailwind CSS
- **Backend**: Node.js, Express.js, MongoDB
- **Database**: MongoDB
- **Payment**: Stripe for payments(in future will be added)
- **Deployment**: 
  - Frontend hosted on Netlify
  - Backend hosted on Vercel


## Installation

### Prerequisites

- Node.js installed
- MongoDB Atlas account
- Stripe account for payment integration

### Steps to Run Locally

 
 1. Clone the repository:

```bash
 git clone https://github.com/Rakibulislam-emon/elctro-e-commerce
cd electro-ecommerce

```

2. Install dependencies:
 ```bash
  npm install

```
3. Create a .env file in the root directory with the following variables:
 ```bash
  DB_USERNAME=<Your MongoDB Username>
  DB_PASSWORD=<Your MongoDB Password>
  JWT_SECRET=<Your JWT Secret Key>
  MONGO_URI=<Your MongoDB URI>
```
4. Start the backend server:
 ```bash
  npm run dev

```
5. Start the frontend:
 ```bash
  npm run dev

```





