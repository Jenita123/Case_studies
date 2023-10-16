1. Python:
   - Python is a high-level, interpreted programming language known for its simplicity and readability. It can be used for web development, data analysis, artificial intelligence, and more.
   - Zomato Example
        - Python can be used as the primary backend programming language to handle user requests, manage the database, and perform other server-side operations.

2. Flask:
   - Description: A tool in Python to build web applications.
   - **Example for Zomato app:**
        - Using Flask, one could set up routes (URL endpoints) for:
            - Displaying a list of restaurants
            - Fetching details of a specific restaurant
            - Placing an order
            - Checking out and making payment


3. MongoDB:
   - Description: A place to store data.
   - Zomato Example: Keeps information on restaurants, menus, and user profiles.

4. Redis:
   - Description: A fast storage to remember frequent data.
   - Zomato Example: Remembers the top restaurants so the website can show them quickly.
   - Redis can be used to cache frequently accessed data like:
        - Top-rated restaurants in a city to quickly display on the home page
        - The most ordered dishes in a particular restaurant

5. JWT(JSON Web Tokens):
   - Description: A secure ticket given to users.
   - Zomato Example: After you log in, JWT ensures you remain logged in as you use the app.

6. Nginx:
   - Description: A traffic director for web requests.
   - Zomato Example: Makes sure when you ask for a restaurant list, it shows you the list and not something else.
   - Nginx can be set up to route traffic:
        - /user/* routes go to the User Service
        - /restaurants/* routes go to the Restaurant Service

7. Docker:
   - Description: A box that contains everything the app needs to run.
   - Zomato Example: Ensures Zomato works the same everywhere, be it on a phone or computer.

8. Kubernetes:
   - Description: A manager for running many boxes (containers) efficiently.
   - Zomato Example: If many people use Zomato at once, Kubernetes makes sure the app doesn't slow down.

9. Microservices:
   - Description: Breaking the app into smaller parts.
   - Zomato Example: Separate parts of Zomato handle user logins, show restaurant lists, and manage orders.
    - Instead of having a monolithic backend, Zomato could be split into several microservices:
    - User Service: Manages user profiles, authentication, etc.
    - Restaurant Service: Manages restaurant listings, menus, etc.
    - Order Service: Handles orders, payments, etc.
    - Review Service: Manages user reviews and ratings.

