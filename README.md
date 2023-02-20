# Next-Shop

Next-Shop is a sample e-commerce web application built with Next.js and PayPal. It features a responsive UI, product catalog, shopping cart, checkout process, and order confirmation page. The application also integrates with the PayPal API to handle payments and manage orders.

## Technologies Used
Next-Shop uses the following technologies:


* **Next.js** - A React-based framework for building server-side rendered (SSR) web applications.
* **PayPal** - A payment processing platform for accepting online payments.
* **React** - A JavaScript library for building user interfaces.
* **Tailwind CSS** - A utility-first CSS framework for building responsive designs.
* **MongoDB** - A NoSQL document-oriented database for storing product and order data.
* **Node.js** - A JavaScript runtime environment for building server-side applications.

## Installation
To install and run Next-Shop, follow these steps:

Clone the repository:

```bash
git clone https://github.com/yogeshmishra667/Next-Shop.git
```
Install dependencies:
```bash
cd Next-Shop
npm install
```
Set up environment variables:
Create a .env file in the root directory of the project with the following variables:

```makefile
PAYPAL_CLIENT_ID=<your_paypal_client_id>
MONGODB_URI=<your_mongodb_uri>
```

Replace **<your_paypal_client_id>** and **<your_mongodb_uri>** with your actual values.

Start the development server:
```bash
npm run dev
```
The application will be available at http://localhost:3000/.

## Usage
Next-Shop provides a simple e-commerce experience for users. They can browse the product catalog, add items to their shopping cart, and complete the checkout process. Once an order is confirmed, users will be directed to an order confirmation page where they can view their order details.

As an administrator, you can log in to the application by visiting the /admin route. From there, you can manage products, orders, and other settings.

## Contributing
Contributions to Next-Shop are welcome! To contribute, follow these steps:

* Fork the repository.
* Create a new branch for your changes.
* Make your changes and commit them with descriptive commit messages.
* Push your changes to your forked repository.
* Create a pull request with a clear description of your changes.

## License
Next-Shop is released under the MIT License.
