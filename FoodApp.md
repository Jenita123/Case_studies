## FoodieDelight

*FoodieDelight* is an intuitive web application aimed at connecting enthusiastic food lovers with a diverse range of restaurants. It allows users to seamlessly navigate through various restaurants, explore menus, check out reviews, place orders, and monitor their delivery in real-time. To enhance the user experience, we've integrated features like dietary preferences, real-time tracking, and a loyalty rewards program.

**Primary Features**:
1. **User Authentication**: Secure sign-up, login, and profile management using JWTs.
2. **Dynamic Restaurant Listings**: Browse, filter by location, cuisine, or user ratings.
3. **Interactive Menu Display**: Menus are accompanied by vivid images, descriptions, and prices.
4. **Ordering & Checkout System**: Add to cart, select delivery location, and complete payment.
5. **Order Tracking**: Users can see the real-time status of their delivery.
6. **Feedback Mechanism**: Post meal, users can rate and review their experience.
7. **Rewards and Promotions**: Loyalty points and promotions to incentivize frequent orders.

**Technologies Used**:

1. **Front-end**:
   - **React.js**: The heart of our application. Allowed for component-based architecture and a dynamic user interface.
   - **Redux**: For state management, making sure the UI reflects data changes uniformly.
   - **Styled-components**: For adding a touch of modern and adaptive styling to the components.
   - **React Router**: For navigation and ensuring smooth transitions between pages.

2. **Back-end**:
   - **Node.js**: The runtime environment powering our server.
   - **Express.js**: Simplified API creation and integrated middleware functionalities.
   - **MongoDB**: Database chosen for its scalability and schema-less nature. Perfect for varied restaurant data.
   - **Mongoose**: ORM to define models and facilitate data interaction between our server and MongoDB.

3. **Authentication**:
   - **JSON Web Tokens (JWT)**: Maintained user sessions and secured API endpoints.
   - **OAuth**: Integrated social logins (like Google and Facebook).

4. **Payments**:
   - **Stripe API**: A robust solution to handle online payments and ensure transaction safety.

5. **Real-time Functionality**:
   - **Socket.io**: Incorporated for bidirectional communication, enhancing features like live order tracking.

6. **Development Tools & QA**:
   - **Webpack**: Bundled and optimized our code for production.
   - **Babel**: Ensured our modern JavaScript code is backward compatible.
   - **Jest and React Testing Library**: For unit and component testing.
   - **Postman**: Tested, documented, and validated our API routes.

7. **Deployment**:
   - **Docker**: Containerized our application ensuring a consistent environment.
   - **Cloud Provider (e.g., AWS, Heroku, etc.)**: Deployed and maintained our web infrastructure.
