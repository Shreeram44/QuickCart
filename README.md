# QuickCart E-commerce Application

QuickCart is a full-featured e-commerce platform built with the MERN stack, providing a seamless online shopping experience. This application allows users to browse products, add them to their cart, and complete purchases with real-time payment processing using Braintree. Administrators can manage products, categories, and other aspects of the store through a dedicated admin panel.

## Features

### Admin Features
- **Manage Categories**: Add, edit, and delete product categories to keep the store organized.
- **Manage Products**: Create new products, upload images, and update product details such as names, descriptions, and pricing.
- **Delete Products**: Easily remove outdated or unwanted products from the store.
- **Upload Images**: Upload and manage product images to showcase items visually.
- **Detailed Product Management**: Provide detailed information about each product, including specifications and availability.

### User Features
- **User Registration and Authentication**: Secure sign-up and login functionality for users.
- **Shopping Cart**: Users can add products to their cart, adjust quantities, and proceed to checkout.
- **Order Placement**: Seamlessly place orders with multiple payment options.
- **Filter and Search**: Use advanced filters to find products based on categories and price ranges.
- **Real-Time Payments**: Integrated Braintree for secure and real-time payment processing with PayPal and credit cards.
- **Profile Management**: Users can update their profile information, including name, address, email, and password.

## Tech Stack

### Frontend
- **React**: For building a responsive and dynamic user interface.
- **Redux**: For state management.
- **Bootstrap**: For styling and responsive design.

### Backend
- **Node.js**: Server-side JavaScript runtime environment.
- **Express**: Web application framework for Node.js.
- **MongoDB**: NoSQL database for storing product, user, and order information.
- **Mongoose**: Object Data Modeling (ODM) library for MongoDB and Node.js.
- **Braintree**: Payment gateway integration for handling payments securely.

### Other Libraries
- **Axios**: For making HTTP requests from the frontend to the backend.
- **JWT (JSON Web Token)**: For user authentication and authorization.
- **Cloudinary**: For image upload and management.
- **Nodemailer**: For sending confirmation and notification emails.

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/quickcart.git
   ```
   
2. **Navigate to the project directory:**
   ```bash
   cd quickcart
   ```

3. **Install dependencies for both frontend and backend:**
   ```bash
   cd frontend
   npm install
   cd ../backend
   npm install
   ```

4. **Set up environment variables:**
   - Create a `.env` file in the backend directory with the following variables:
     ```
     MONGO_URI=your_mongodb_uri
     JWT_SECRET=your_jwt_secret
     BRAINTREE_MERCHANT_ID=your_braintree_merchant_id
     BRAINTREE_PUBLIC_KEY=your_braintree_public_key
     BRAINTREE_PRIVATE_KEY=your_braintree_private_key
     ```

5. **Run the application:**
   - Start the backend server:
     ```bash
     cd backend
     npm run dev
     ```
   - Start the frontend:
     ```bash
     cd frontend
     npm start
     ```

## Usage

1. **Admin Access**: Log in as an admin to manage categories and products.
2. **User Access**: Users can browse products, add items to their cart, and place orders.
3. **Payment Processing**: Use PayPal or a credit card for real-time payments through Braintree.

## Contributing

Contributions are welcome! Please submit a pull request or open an issue to discuss changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

![Screenshot 2024-08-31 015617](https://github.com/user-attachments/assets/98c91183-29b8-44a0-8f20-b525152f19ad)
![Screenshot 2024-08-31 015731](https://github.com/user-attachments/assets/28f95c7e-4ee6-489b-ac32-f59374531131)
![Screenshot 2024-08-31 015628](https://github.com/user-attachments/assets/9fc55824-0a20-42c0-8824-dd44b003da80)
![Screenshot 2024-08-31 015642](https://github.com/user-attachments/assets/07d1a070-db25-4bd1-b9a8-9fccbd49a4c1)
![Screenshot 2024-08-31 015650](https://github.com/user-attachments/assets/1ad13779-459a-4150-98e9-62ca61f02a69)
![Screenshot 2024-08-31 015707](https://github.com/user-attachments/assets/cb4a0f6a-338d-4baa-9089-c3f8e36eeb01)
![Screenshot 2024-08-31 015718](https://github.com/user-attachments/assets/f04d7dc5-ca2b-4103-9b69-805e807e7d8b)
![Screenshot 2024-08-31 015747](https://github.com/user-attachments/assets/18f602d6-7be0-487b-8ff4-410af37bf0f9)
