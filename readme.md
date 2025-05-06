## KIRANAWALA : The Quick Commerce 🛒

An e-commerce platform for buying grocery items, offering users a seamless online shopping experience for their daily needs.

## 📋 Features

- 🚀 **Login/Sign Up**: Users can create accounts or log in to existing ones.
- 🔐 **Forgot Password**: Forgot your password? No problem! Users can reset their passwords via email.
- 🔒 **Update Password**: Users can change their passwords for added security.
- 📝 **Customer Reviews**: Customers can leave reviews for products.
- ✏️ **Update Reviews**: Customers can edit or delete their reviews.
- 📦 **Product Lists**: Browse and view product listings.
- 🔍 **Filter Products**: Filter products by category, price, or other attributes.
- 🔎 **Search Products**: Search for specific products by name or keywords.
- 🛒 **Cart Items**: Add products to the cart for purchase.
- 🛍️ **Order Summary**: Review and confirm orders before checkout.
- 📄 **Order Details**: View order history and details.
- 👨‍💼 **Admin Functionality**: Special features for administrators to manage products and users.

## Technologies

- 📦 **MongoDB**: A NoSQL database for storing data.
- ⚙️ **Express.js**: A web application framework for Node.js.
- ⚛️ **React**: A JavaScript library for building user interfaces.
- 🚀 **Node.js**: A JavaScript runtime for server-side development.
- 🔑 **JWT**: JSON Web Tokens for user authentication.
- 🔒 **bcrypt**: A library for hashing user passwords.
- 💌 **Resend**: A library for sending email.
- ☁️ **Cloudinary**: A cloud-based image and video management service.

## Configuration

1. Create a `.env` file in the `server` directory with the following environment variables:

   ```env
   FRONTEND_URL = frontend_host_url
   MONGODB_URI = your_mongodb_uri
   RESEND_API = resend_email_api_key

   SECRET_KEY_ACCESS_TOKEN = jwt_secret_key
   SECRET_KEY_REFRESH_TOKEN = jwt_refresh_secret_key

   CLODINARY_CLOUD_NAME = your_cloudinary_cloud_name
   CLODINARY_API_KEY = your_cloudinary_api_key
   CLODINARY_API_SECRET_KEY = your_cloudinary_api_secret

   STRIPE_SECRET_KEY =  your_stripe_payment_secret_key
   ```

2. Create a `.env` file in the `client` directory with the following environment variables:

   ```env
   BACKEND_URL = backend_host_url
   STRIPE_PUBLIC_KEY =  your_stripe_payment_public_key
   ```

## 🚀 Getting Started

### Prerequisites
- Node.js: Ensure you have Node.js installed on your machine.
- MongoDB: Set up a MongoDB database.

### Installation

 1. **Clone the repository:**
    ```bash
    git clone https://github.com/alokmht07/KIRANAWALA.git
    cd KIRANAWALA
    ```
 2. **Install dependencies:**
    ```bash
    cd client
    yarn install
    # or
    npm install
    ```
   
 3. **Run the frontend:**
    ```bash
    yarn dev
    # or
    npm run dev
    ```
    
 4. **Start the Backend Server:**
    ```bash
    cd server
    yarn install
    # or
    npm install

    yarn dev
    # or
    npm run dev

5. Access the application in your web browser at `http://localhost:5173`.

<br/>

## Contribution Guide
We welcome contributions to the Food Copilot project! Feel free to report bugs, suggest features, or submit pull requests. Follow these steps to get started:

 1. Fork the Repository - Navigate to the Food Copilot Repository, click on the Fork button to create a copy of the repository in your GitHub account.
 
 2. Clone Your Fork - Clone the forked repository to your local machine.

 3. Run the project on your local machine, check the Getting Started section to setup the project.
 4. Commit your changes with clear commit messages.
 5. Push your changes to your forked repository.
 6. Create a pull request with your changes and details.

### Give a Star ⭐
If you find this project helpful or interesting, please consider giving it a star on GitHub! 
