# Amazon Replica App

## Overview
The **Amazon Replica App** is a fully functional e-commerce web application built using **React.js**. It replicates core features of Amazon, including product browsing, user authentication, shopping cart functionality, and checkout.

## Features
- **User Authentication**: Sign-up, login, and logout functionality with Firebase authentication.
- **Product Listing**: Display a list of products with images, descriptions, and prices.
- **Search Functionality**: Users can search for products using keywords.
- **Shopping Cart**: Add, update, and remove items from the cart.
- **Checkout Process**: A streamlined checkout process for placing orders.
- **Payment Integration**: Secure payments using Stripe API.
- **Order History**: View previously placed orders.
- **Responsive Design**: Optimized for both desktop and mobile devices.

## Tech Stack
- **Frontend**: React.js, Redux for state management, Tailwind CSS for styling
- **Backend**: Firebase (Authentication, Firestore Database)
- **Payment Gateway**: Stripe API
- **Hosting**: Firebase Hosting

## Installation
### Prerequisites
Ensure you have **Node.js** and **npm** installed on your machine.

### Steps
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/amazon-clone.git
   ```
2. Navigate to the project directory:
   ```sh
   cd amazon-clone
   ```
3. Install dependencies:
   ```sh
   npm install
   ```
4. Set up Firebase:
   - Create a Firebase project.
   - Enable Firestore and Authentication.
   - Obtain your Firebase configuration keys and add them to a `.env` file.

5. Start the development server:
   ```sh
   npm start
   ```
6. Open the app in the browser:
   ```
   http://localhost:3000
   ```

## Usage
- Browse products on the homepage.
- Sign in or create an account.
- Add items to the shopping cart.
- Proceed to checkout and make a payment using the Stripe test card.
- View order history after successful purchases.

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch:
   ```sh
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```sh
   git commit -m "Added new feature"
   ```
4. Push to the branch:
   ```sh
   git push origin feature-name
   ```
5. Open a Pull Request.

## Contact
For any questions or suggestions, reach out at(ojhavipul0204@gmail.com).

