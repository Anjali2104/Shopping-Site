# E-Commerce Website with ReactJS, Node.js, MongoDB, Express

Welcome to the **E-Commerce Website** repository! This project showcases a full-stack e-commerce website built using ReactJS for the frontend and Node.js, MongoDB, and Express for the backend. It enables users to browse products, add items to their cart, place orders, and make payments using Stripe. The project also includes admin features for product management, order tracking, and sales analytics.


![E-Commerce Website Screenshot](https://github.com/Anjali2104/Shopping-Site/assets/86160355/6fa0cba8-0782-4f49-8ed2-d98810949b24)
![category](https://github.com/Anjali2104/Shopping-Site/assets/86160355/4126085b-83d5-40a7-8065-a9237a63c1b6)


## Features

### User-Facing Features

- **Browse Products:** Users can view a wide range of products available on the website.

- **Product Details:** Each product has a dedicated page displaying its details, including images, descriptions, and prices.

- **Shopping Cart:** Users can add products to their cart, review the cart, and proceed to checkout.

- **User Authentication:** Secure user registration and login functionality for order tracking and profile management.

- **Stripe Integration:** Seamless payment processing using Stripe API for secure and convenient transactions.

### Admin-Facing Features

- **Product Management:** Admin users can add new products, update existing product details, and remove products from the catalog.

- **Order Tracking:** Admin users can view and manage orders, including order status and fulfillment.

- **Sales Analytics:** Detailed insights into sales, revenue, and product performance to make informed business decisions.

- **Firebase Integration:** Product images are stored and served using Firebase storage, ensuring efficient and reliable image management.

## Getting Started

Follow these instructions to set up the project locally on your machine.

### Prerequisites

- [Node.js](https://nodejs.org/) installed on your system.
- [MongoDB](https://www.mongodb.com/) database setup.
- [Stripe](https://stripe.com/) account for payment processing.
- [Firebase](https://firebase.google.com/) account for image storage.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Anjali2104/Shopping-Site.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Shopping-Site
   ```

3. Install frontend dependencies:

   ```bash
   cd client
   npm install
   ```

4. Install backend dependencies:

   ```bash
   cd ../server
   npm install
   ```

5. Set up environment variables:

   Create a `.env` file in the `server` directory and provide the following variables:

   ```
   PORT=5000
   DB_URI=your_mongodb_connection_string
   STRIPE_SECRET_KEY=your_stripe_secret_key
   FIREBASE_API_KEY=your_firebase_api_key
   FIREBASE_STORAGE_BUCKET=your_firebase_storage_bucket
   SESSION_SECRET=your_session_secret
   ```

6. Start the application:

   ```bash
   npm start
   ```

7. Open your web browser and navigate to `http://localhost:3000` to access the e-commerce website.

## Contributing

Contributions are welcome! If you encounter issues or have suggestions, please feel free to open an issue or submit a pull request.

Before contributing, please review the [Contributing Guidelines](CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

We would like to acknowledge the following resources for their guidance and inspiration during the development of this project:

- [Stripe Documentation](https://stripe.com/docs)
- [Firebase Documentation](https://firebase.google.com/docs)
- [React Documentation](https://reactjs.org/docs)

For any inquiries, please contact [anjali@example.com](mailto:anjali@example.com).

---

Happy shopping and selling!