# Airbnb Clone Backend - Use Case Diagram

## Overview
This document provides an overview of the use case diagram for the Airbnb Clone backend project. The diagram visualizes the interactions between various actors and the system, focusing on key functionalities such as user registration, property booking, and payment processing.

## Use Case Diagram Explanation

### Actors
The system involves several key actors:

- **Guest**: A user who can search for properties, register an account, book properties, leave reviews, and receive notifications.
- **Host**: A user who can add, edit, and delete property listings, manage bookings, and respond to reviews.
- **Admin**: A user responsible for monitoring the overall system, managing users, listings, and payments.
- **Payment System**: An external service that handles payment processing and confirmations.

### Use Cases
The use cases represent the functionalities that each actor can perform within the system. Below are the main categories of use cases:

1. **User Management**
   - **User Registration**: Guests and hosts can create an account to access the platform.
   - **User Login**: Allows users to log into their accounts using credentials.
   - **Profile Management**: Users can update their profile information.

2. **Property Listings Management**
   - **Add Listings**: Hosts can create new property listings to make them available for booking.
   - **Edit Listings**: Hosts can modify existing listings.
   - **Delete Listings**: Hosts can remove listings that are no longer available.

3. **Search and Filtering**
   - Guests can search for properties based on various criteria such as location, price range, number of guests, and amenities.

4. **Booking Management**
   - **Booking Creation**: Guests can book properties for specified dates.
   - **Booking Cancellation**: Both guests and hosts can cancel bookings when necessary.
   - **Booking Status Tracking**: Users can check the status of their bookings.

5. **Payment Integration**
   - **Payment Processing**: Guests can make payments for their bookings.
   - **Payment Confirmation**: The payment system confirms successful transactions.

6. **Reviews and Ratings**
   - Guests can leave reviews for properties they have booked, and hosts can respond to these reviews.

7. **Notifications System**
   - Users receive notifications for important events such as booking confirmations and cancellations.

8. **Admin Dashboard**
   - Admins can monitor user activities, manage property listings, and oversee payments.

## Diagram Visualization
The use case diagram visually represents the interactions between the actors and the system's use cases. Each oval in the diagram corresponds to a use case, while the stick figures represent the actors. Lines connect the actors to the use cases they interact with.

## Conclusion
This use case diagram serves as a foundational document for understanding the interactions within the Airbnb Clone backend system. It outlines the essential features and functionalities that will guide the development of the backend services.

## Future Work
As the project progresses, additional use cases may be identified and added to ensure comprehensive coverage of system functionalities.