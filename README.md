# Package Tracking System
Overview
The Package Tracking System is designed to streamline the process of managing and tracking packages for businesses and couriers. The system facilitates order creation, assignment to couriers, and status tracking, making it easier for businesses to deliver their packages and for customers to stay informed about their deliveries.

Built with Go for the backend, React for the frontend, and deployed on # OpenShift, the application provides scalability and reliability through containerization and cloud deployment.

# Features
# User Features
User Registration:

Register accounts with name, email, phone number, and password.
Secure backend validation and account creation.
User Login:

Login interface for registered users.
Authentication via secure endpoints.
Create Orders:

Input package details (pickup/drop-off locations, package weight, delivery preferences).
Save orders in the database.
My Orders:

View a list of orders placed by the user, including order status and delivery progress.
Order Details:

Detailed view of specific orders, including courier assignment and package status.
Option to cancel pending orders.
# Courier Features
Assigned Orders:

View a list of assigned orders with status indicators.
Options to accept or decline orders.
Update Order Status:

Interface to update the status of a package (e.g., picked up, in transit, delivered).
# Admin Features
Manage Orders:

View, update, and delete orders via an admin panel.
Reassign orders to different couriers.
Assign Orders to Couriers:

Manage the assignment of packages to couriers.
Reassign orders when necessary.
# Technologies Used
Backend
Go: RESTful API implementation.
MySQL: Database for managing users, orders, and couriers.
Frontend
React: Responsive and dynamic user interface.
Deployment
Docker: Containerization for backend, frontend, and database.
OpenShift: Deployment and management of containers in a cloud environment.
