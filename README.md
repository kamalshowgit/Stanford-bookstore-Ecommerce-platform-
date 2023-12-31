# Stanford Bookstore E-commerce Website

Welcome to the README for the **Stanford Bookstore E-commerce Website** project. This is a Django-based e-commerce platform designed to provide a seamless online shopping experience for book enthusiasts. The project incorporates all the necessary features of an e-commerce website, including a user-friendly interface, product catalog, shopping cart, user authentication, and a secure PayPal payment method.

## Features

1. **User Authentication and Accounts**: Users can create accounts, log in, and manage their profiles. This allows for a personalized experience, order history tracking, and easy communication with the bookstore.

2. **Product Catalog**: The website features an extensive catalog of books from various genres. Each book listing includes details such as title, author, cover image, description, and price.

3. **Product Search and Filtering**: Users can easily search for specific books using keywords, and they can also filter results by categories, genres, and other attributes.

4. **Shopping Cart**: A shopping cart system lets users add and remove items, adjust quantities, and view a summary of their selected products. The cart persists across sessions for user convenience.

5. **Order Management**: Users can review and finalize their orders before proceeding to checkout. The website provides a clear breakdown of items, quantities, and total costs.

6. **Checkout Process**: The checkout process is designed to be intuitive and user-friendly. Users enter their shipping details and choose the PayPal payment option for a secure transaction.

7. **PayPal Payment Integration**: The website is equipped with PayPal payment integration, ensuring a safe and seamless payment process for customers. Users are redirected to PayPal's platform to complete their transactions securely.

8. **Order Confirmation and Tracking**: After a successful transaction, users receive order confirmation emails containing details about their purchase. They can also track the status of their orders through their accounts.

9. **Responsive Design**: The website's responsive design ensures a consistent and visually appealing experience across various devices, including desktops, tablets, and smartphones.

## Installation and Usage

1. Clone the repository to your local machine.
   ```
   git clone https://github.com/kamalshowgit/Stanford-bookstore
   ```

2. Navigate to the project directory.
   ```
   cd Stanford-bookstore
   ```

3. Install the required dependencies using pip.
   ```
   pip install -r requirements.txt
   ```

4. Set up your database by running migrations.
   ```
   python manage.py migrate
   ```

5. Create a superuser account for admin access.
   ```
   python manage.py createsuperuser
   ```

6. Run the development server.
   ```
   python manage.py runserver
   ```

7. Access the website through your browser at `http://127.0.0.1:8000/`.

### User Workflow Screenshots

1. **Home Page**
![Home Page](ss/1.png)
_Description: This is the landing page of the Stanford Bookstore E-commerce Website where users can explore featured books._

2. **Book Detail View**
![Book Detail View](ss/2.png)
_Description: This page provides detailed information about a selected book, including its title, author, and a description._

3. **Login Page**
![Login Page](ss/3.png)
_Description: Users can log in to their accounts to access personalized features and view their order history._

4. **Checkout Page**
![Checkout Page](ss/4.png)
_Description: This page displays the items in the user's cart and allows them to proceed with the checkout process._

By following this approach, you'll be able to provide a clear visual representation of your project's workflow using annotated screenshots. Just remember to replace "link-to-your-image-X.png" with the actual URLs of your uploaded images.



## Contributing

Contributions to this project are welcome! If you find any bugs or have suggestions for improvements, please feel free to open issues or submit pull requests.

## License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute the code according to the terms of this license.

Enjoy your experience with the Stanford Bookstore E-commerce Website! If you have any questions or need assistance, feel free to contact us.

---
