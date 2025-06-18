# airbnb-clone-project

Welcome to the Airbnb clone. This is an application that simulates the features of a hotel booking platform.

# Technology Stack
- Django for api creation
- APIs to handle payments
- Database Management Systems (MySQL, PostgreSQL)
- CI/CD Pipelines
- Docker for containerization

# Tasks

This application should;
- handle user profile creation and management
- user authentication
- allow users to view available listings
- allow users to pay using a safe payment method
- update available bookings
- deletion of unavailable properties

# Database Design

Key Entities include;
- Customer
    Fields include; CustomerName,
    CustomerId,
    BookingHistory

- Hotel Manager
    Fields include; ManagerName,
    ManagerId,
    Rating

- Property Listings
    Fields include; PropertyName,
    PropertyId,
    Availability

- Bookings
    Fields include; HotelId,
    HotelName,
    Location

- Reviews
    Fields include; ReviewId,
    Rating,
    RatingId

- Payments
    Fields include; PaymentHistory,
    PaymentId,
    Time

# Feature Breakdown
- User Management;
    Users shall be able to sign up to the platform and create profiles to track preferences, booking history and payments.
    Users shall also be able to log in securely with proper authentication to boost security.

- Property Management;
    Managers shall be able to create new property listings and delete old ones.
    Users shall also see available bookings in their area.

- Booking System;
    Users shall see which properties are available at a given time.
    Users shall be able to select properties they intend to rent out including duration.
    They shall also be able to leave reviews and ratings for the hotels.
    Managers shall recieve notifications for desired hotels.
    They shall also be able to communicate the availability of the hotels.

- Payments;
    An API shall be evoked to track and handle user payments securely.
    Managers and Users shall be notified whenever payments are made.

# Team Roles
*According to ITRex Group Blog
1. Business Analyst
- Understands customer's business processes
- Translates business needs into requirements

2. Product owner
- Holds responsibility for a product vision and evolution
- Makes sure the final product meets customer requirements

3. Project manager
- Makes sure a product or its part is delivered on time and within budget
- Manages and motivates the software development team

4. UI/UX designer
- Transforms a product vision into user-friendly designs
- Creates user journeys for the best user experience and highest conversion rates

5. Software architect
- Designs a high-level software architecture
- Selects appropriate tools and platforms to implement the product vision
- Sets up code quality standards and performs code reviews

6. Software developer
- Engineers and stabilizes the product
- Solves any technical problems emerging during the development lifecycle

7. QA engineer
- Makes sure an application performs according to requirements
- Spots functional and non-functional defects

8. Test automation engineer
- Designs a test automation ecosystem
- Writes and maintains test scripts for automated testing

9. DevOps engineer
- Facilitates cooperation between development and operations teams
- Builds continuous integration and continuous delivery (CI/CD) pipelines for faster delivery

Thank you.