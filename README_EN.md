### 📒"Eatly" Project Documentation

:globe_with_meridians: The project is hosted on [Netlify](https://eatly-fe17.netlify.app/).
:email: E-mail: <eatly.supp@gmail.com>

---

### *Project Overview and Goals*

---

**The "Eatly" Project** - is a path to incredible culinary experiences, where everyone can order their favorite food from various restaurants with just one touch. Convenience, variety, and speed - these are the three components that make our app the perfect choice for those who value refined taste and comfort in every order.

### *Requirements*

---

* #### *Functional requirements implemented in the application*

  * Users have the ability to register (create an account), authorize both through the form provided by the app and using Google authorization, and track their favorite dishes. Both authorized and unauthorized users can create orders. The ability to restore passwords by sending a temporary link that leads to a new password entry form has been implemented.
  * Authorized users have the ability to add selected dishes to their favorites list to conveniently track them and quickly find them during subsequent orders.
  * Search is available both for partner restaurants and for offered dishes.
  * Dish filtering is available to users by category, price, rating, and popularity.
  * Users can easily sort dishes by selected parameters.
  * A mini-cart is implemented, allowing users to track their order without leaving the page with selected filters, which in turn saves user time and creates the most favorable conditions for comfortable and quality ordering.
  * Users can independently choose the payment method for their order.
  * Notifications with order description, amount, estimated delivery time, and feedback option are sent to the user's email in the most pleasant and friendly format.
  * The app implements user support in the form of feedback correspondence.
  * Authorized users have the ability to leave service reviews with ratings. Every app user can view all reviews in chronological order starting from the newest.
  * During registration, authorization, order placement, adding items to cart, and successful review submission, the service accompanies users with informational messages about successful actions. An informational alert is also displayed to users when no dishes are found for selected filter parameters.

* #### *Non-functional requirements*

  * Performance: the system ensures fast filter processing and page display for users even under heavy load. Pagination is applied for partial loading and display of dishes and service reviews.

  * Security: Users can be confident in the security of their personal data and payment operations.

  * Architectural flexibility: The system is extensible and capable of easy integration with other services.

### *System Architecture*

---

The "Eatly" system is based on client-server architecture and uses modern technologies to ensure reliability and performance. The main system components include:

**Client Interface:** Developed using React and Material-UI, providing users with a convenient interface for viewing and ordering food. The app layout is responsive to different devices, providing the same capabilities to users on computers, mobile devices, and tablets.

**Server Side** uses three-tier architecture built on Node.js and Express.js for reliability and efficiency. With these technologies, we ensure fast request processing, reliable operation, and high performance, creating a solid foundation for our project.

Database: A document-oriented database management system MongoDB is used to store information about users, restaurants, dishes, and orders, ensuring efficient and scalable data management.

### *Interface Design*

---

The "Eatly" interface design is developed with attention to user experience. It includes clear page layouts, use of pleasant colors, page interactivity, and intuitive element placement in the web application.

### *Database*

---

The "Eatly" system database is built on the NoSQL database management system MongoDB, which is based on a document-oriented model and includes the following main components:

***Users***: data about registered users, including their personal information (except passwords) and order history.

***Restaurants***: information about restaurants that partner with the "Eatly" platform, including their address, establishment description, rating, and menu.

***Dishes***: information about dishes, cost, categories, ratings, and images of dishes offered in restaurants.

***Favorite dishes***: each user has their own list of favorite dishes, which can be changed and displayed when authorized on the site.

***Cart***: a registered user will never lose items added to the cart, even in unforeseen circumstances. The cart is always updated and stored in the database.

***Orders***: content, number, and cost of orders and user data.

***Reviews***: each review will be useful for new users and for improving the app service.

### *Algorithms and Logic*

---

Using **Redux Toolkit** for efficient application state management.

Implementation of server interaction through **Axios** for executing requests, processing responses, and updating application state based on received data.

Integration of **Material-UI** components for fast and convenient interface development, using styles configured for the app's GlobalTheme and ready-made design elements.

Using **Formik** libraries for form state management and **Yup** for input data validation, providing users with convenient and secure information input.

Using **React Router** for implementing navigation in the app and URL interception, ensuring correct component display based on paths.

Application of **Redux Persist** for saving certain parts of the application state in local storage to ensure information preservation between sessions.

**ESLint** is used to improve code quality and detect errors and stylistic inconsistencies. Establishing code standards and their automatic execution ensured consistency and facilitated the development team's work.

**Netlify** is used for fast and simple application deployment, providing automatic code deployment from GitHub, automatic building, and CDN distribution for improved performance and project accessibility.

Using the **Swiper** library.

*These algorithms and logical approaches contribute to developing a productive, convenient, and functional application.*

---

The "Eatly" system is a modern online platform for ordering food from various restaurants and cafes. It simplifies the process of selecting and ordering dishes, providing users with access to diverse culinary offerings. Together with a convenient interface and extensive functionality, "Eatly" makes culinary adventures even more delicious and comfortable.

We hope this documentation gives you a clear understanding of the "Eatly" system and contributes to better understanding of its functions and capabilities. If you have additional questions or comments, please contact our team at <info@eatly.com>. We are ready to listen and provide necessary support.

***Thank you for using "Eatly" and we wish you pleasant culinary experiences!***


**Version 1.0 (current version)**
