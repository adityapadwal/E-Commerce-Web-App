
# E-Commerce Web Application

Welcome to the E-Commerce Web Application repository! This project is a comprehensive and robust E-commerce platform developed with a focus on scalability and user-friendly features. The application is built using Node.js and Express.js for the backend, MongoDB for the database, and EJS for the frontend.


## Demo

![finalGIF](https://github.com/adityapadwal/E-Commerce-Web-App/assets/97524745/c78a343c-c54a-4321-8b42-e88b44e5bb45)




## Key Features

Our E-Commerce Web Application provides a range of essential functionalities:

1. User Authentication and Authorization: Secure user registration and login processes with hashed passwords, ensuring only authorized users can access certain features.
2. Shopping Cart Functionality: Users can add and remove products to/from their shopping cart, simplifying the online shopping experience.
3. Order Processing: Seamless order processing for users, allowing them to review and confirm their purchases.
4. Invoice Generation: Automatic invoice generation using the pdfkit module of Node.js, providing users with detailed order summaries.
5. Pagination: Efficiently handle large product lists with pagination, enhancing user experience and reducing loading times.
6. Session Management using Cookies: Employ cookies for managing user sessions, maintaining user data across requests.
7. MVC Architecture: Follow the Model-View-Controller (MVC) architecture for a well-structured and maintainable codebase.

## More Functionalities
Our E-Commerce Web Application offers even more functionalities to enhance the user experience:

1. Password Reset via Email: Utilize the SendGrid API to send password reset emails to users who forget their passwords, ensuring account security.
2. Welcome Email on Sign Up: Send a welcome email to users upon successful registration using the SendGrid API, providing a personalized touch.
3. Payment Processing: Leveraging the Stripe API for secure and efficient payment processing, enabling smooth and reliable transactions.
4. Admin Panel: Provide an intuitive UI for admins to manage products, including adding, deleting, and modifying product details.
5. CSRF Protection: Implement Cross-Site Request Forgery (CSRF) protection to safeguard user data and prevent unauthorized actions.
6. Secure Password Storage: Use the uuid npm package to encrypt and securely store user passwords in the MongoDB database.
7. Database Management: Systematically store user data, orders, products, and sessions in the MongoDB database, ensuring data integrity and security.
## Tech Stack

**Front-End:** EJS templating engine

**Server:** Node, Express

**Database:** MongoDB

## APIs Used
Our E-Commerce Web Application integrates the following APIs to power its functionalities:

1. Stripe: For seamless and secure payment processing, ensuring smooth transactions for users.
2. SendGrid: To handle user authentication and authorization email services, delivering password reset and welcome emails.

## Improvements and Future Scope
While the E-Commerce Web Application is already feature-rich, there are several areas for potential improvement and future enhancements:

1. MERN Stack Migration: Consider migrating the frontend from EJS to React.js to achieve a more scalable, robust, and powerful MERN (MongoDB, Express, React, Node.js) web application.
2. Dark/Light Mode: Implement a user-friendly dark/light mode toggle to cater to users' preferences for a personalized browsing experience.
3. Enhanced Frontend: Invest more efforts into refining the frontend design and user interface to elevate the overall user experience.
4. Separate UI for Client and Admin: Create distinct UIs for clients and admins by determining the role at login time, streamlining user-specific functionalities.
## Contributing

Contributions to this project are highly appreciated! If you have any ideas for new features, find any issues, or want to improve the existing functionality, please feel free to create a pull request. Working together, we can make this E-Commerce Web Application even better!

Please adhere to this project's `code of conduct`.


## Installation

To set up the project locally, follow these steps:

1. Clone the repository to your local machine:
```bash
  git clone https://github.com/adityapadwal/E-Commerce-Web-App.git
```
2. Navigate to the project directory:
```bash
  cd E-Commerce-Web-Application
```
3. Install the required dependencies:
```bash
  npm install
```
4. Start the development server:
```bash
  npm start
```
5. Open your web browser and visit http://localhost:3000 to explore the E-Commerce Web Application.
## Screenshots

![Screenshot (75)](https://github.com/adityapadwal/E-Commerce-Web-App/assets/97524745/c4bb7a0a-94d7-447f-b776-dca163287fbe)

![Screenshot (76)](https://github.com/adityapadwal/E-Commerce-Web-App/assets/97524745/33ca16cb-f887-4af1-86aa-b07f8813ea25)

![Screenshot (78)](https://github.com/adityapadwal/E-Commerce-Web-App/assets/97524745/426f46cb-d270-4c92-ae98-be0dc71268c3)

![Screenshot (80)](https://github.com/adityapadwal/E-Commerce-Web-App/assets/97524745/97e388da-55cf-4401-9672-06e3451d55bd)


## Feedback

If you have any feedback, please reach out to us at aditya.padwal3102@gmail.com
Thank you for your interest in the E-Commerce Web Application. We hope you find it useful and we look forward to your contributions!





