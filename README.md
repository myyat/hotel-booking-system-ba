# hotel-booking-system-ba
Business Analysis case study of an Online Hotel Booking System

## 1. Project Overview
   
**Project Name:** StayEase — Online Hotel Booking Platform

StayEase is an online hotel booking platform that connects travelers with hotel owners across Southeast Asia. The platform enables users to search, compare, and book accommodations, while allowing hotel owners to list properties, manage availability, and handle reservations through a centralized digital system.

## 2. Project Objectives
   
- Enable hotel owners to list, manage, and update property details, room availability, and pricing through a self-       service digital platform
- Allow travelers to search, compare, and book hotel accommodations with instant confirmation
- Support secure online payments and automated booking notifications
- Provide administrators with tools to manage users, listings, and transactions
- Reduce reliance on manual booking processes and high-commission third-party platforms

## 3. Problem Statment
   
For Travelers:
Travelers currently lack a reliable online platform to search and compare hotel accommodations. Without real-time     visibility into room availability and pricing, booking decisions become difficult and time-consuming. Additionally, there is no automated confirmation system, requiring users to follow up manually to verify their reservation status.

For Hotel Owners:
Hotel owners have no dedicated digital platform to list and manage their properties online. Reservations are handled manually through phone calls or walk-in inquiries, leading to inefficiencies and risk of double bookings. Furthermore, owners lack digital tools to track occupancy rates and monitor revenue performance.

StayEase Solution:
StayEase addresses these challenges by providing a centralized platform where travelers can search, compare, and book accommodations with real-time availability and instant confirmation, while hotel owners can manage listings, reservations, and performance metrics through a single digital system.

## 4. Stakeholders
   
### 4.1 External Users
- Hotel Guest – Searches, compares, and books hotel accommodations through the platform
- Hotel Owner – Lists properties and manages room availability, pricing, and reservations

### 4.2 Business Stakeholders
- Product Owner – Defines business goals and approves system features
- Customer Support Team – Handles user inquiries, complaints, and booking issues

### 4.3 Technical Stakeholders
- Business Analyst – Gathers and documents system requirements
- Developers – Build and maintain the system
- QA/Testers – Test system functionality and ensure quality
- System Administrator – Manages system operations and user access

### 4.4 External Systems
- Payment Gateway – Processes online payments securely
- Notification Service – Sends booking confirmations via email/SMS

## 5. Requirements Elicitation (Stakeholder Questions)

This section includes assumed questions that a Business Analyst would ask stakeholders to understand system requirements for the Online Hotel Booking System.

### 5.1 Hotel Guest Questions & Answers

Q: Who are the target users of the system?  
A: The primary target users are travelers across Southeast Asia looking to search and book hotel accommodations           online. 

Q: Can users search hotels without logging in?  
A: Yes. Users can search and browse hotel listings without an account. Login is only required at the booking stage.

Q: What filters should be available for hotel search?  
A: The search feature will support filters including location, price range, star rating, and check-in/check-out dates.

Q: Can users view hotel details without making a booking?  
A: Yes. Users can view full hotel details, room types, and pricing without being required to make a booking.

Q: Can users book instantly or is approval required?  
A: Instant booking is supported. No manual approval from hotel owners is required.

Q: How will users receive booking confirmation?  
A: Users will receive booking confirmation via in-app notifications and email.

Q: What is the cancellation policy?  
A: Users can cancel bookings up to 24 hours before the check-in date for a full refund.

Q: Is refund allowed in case of cancellation?  
A: Yes. Full refund is provided if cancellation is made within the allowed cancellation period.

### 5.2 Hotel Owner Questions and Answers

Q: How do hotel owners register on the platform?  
A: Hotel owners can register by providing their business name, contact information, and email address. After account verification by the system administrator, they can proceed to list their properties.

Q: Can hotel owners manage their own listings?  
A: Yes. Hotel owners have full control over their listings, including updating hotel descriptions, room types, photos, and pricing.

Q: Can they update room availability and pricing in real time?  
A: Yes. Hotel owners can update room availability and pricing in real time through their dashboard.

Q: How are bookings assigned or notified to hotel owners?  
A: Hotel owners receive instant booking notifications via their dashboard and email whenever a new reservation is made.

Q: Can hotel owners view and manage booking history?  
A: Yes. Hotel owners can view past and current reservations, track booking status, and manage bookings through their dashboard.
  
### 5.3 Business & Product Questions and Answers

Q: Will the system be developed as a web or mobile application?  
A: Both. StayEase will be developed as a web and mobile application, allowing users to access the platform on their preferred device.

Q: What is the business model?  
A: StayEase operates on a commission-based model, where a percentage fee is charged to hotel owners for each successful booking made through the platform.

Q: Is online payment mandatory for booking confirmation?  
A: Yes. Online payment is mandatory to confirm a booking. Reservations are only secured upon successful payment.

Q: What payment methods will be supported?  
A: The platform will support major credit/debit cards and popular digital wallet options.

Q: What happens if a payment transaction fails?  
A: If payment fails, the booking will not be confirmed, and users will be prompted to retry the payment or choose a different payment method.

Q: Which regions will the platform support?  
A: The platform will initially focus on travelers across Southeast Asia.

Q: Are there any promotional or discount features required?  
A: Yes. The platform will support basic promotional features including promo codes and seasonal discounts.
  
### 5.4 System / Technical Questions and Answers

Q: How does the system handle double bookings?  
A: The system displays real-time room availability. When a user initiates a booking, the selected room is temporarily locked during the booking and payment process. Once the booking is confirmed and payment is completed, the room is marked as unavailable, preventing other users from booking the same room. Users attempting to book an unavailable room will receive a notification.

Q: What happens if room availability changes during the booking process?  
A: If room availability changes during the booking process, the system will notify the user that the selected room is no longer available and prompt them to select an alternative.

Q: What external systems are required?  
A: The platform integrates with a payment gateway to process online transactions securely and a notification service to deliver booking confirmations and alerts via in-app notifications and email.

Q: Should the system support real-time updates?  
A: Yes. The system supports real-time updates for room availability and booking status, allowing users to make informed booking decisions.

Q: How will the system notify users?  
A: Users will receive notifications through their profile dashboard and registered email address.
These questions are based on assumptions for learning purposes and simulate real-world requirement gathering in a Business Analysis project. No real stakeholder interviews were conducted.

## 6. System Scope

### 6.1 In Scope 
- User registration and login
- Hotel search and filtering
- View hotel details and room availability
- Online booking with instant confirmation
- Booking cancellation and refund processing
- Secure online payment integration
- Booking management for users and hotel owners
- Hotel listing and management for owners
- Real-time availability updates
- Notifications (in-app and email)
- Admin management of users, listings, and bookings
- Hotel review and rating system

### 6.2 Out of Scope 
- Flight booking and transportation services
- Loyalty programs and reward systems
- Advanced analytics and reporting dashboards
- Integration with third-party travel platforms
- Multi-language support
- Offline payment processing 

## 7. System Flow
### 7.1 User Flow 
1. User opens the platform and searches hotels by location and date
2. System displays a list of available hotels based on user criteria 
3. User selects a hotel 
4. System displays hotel details including room types, prices and availablity 
5. User selects a room and proceed to booking 
6. System prompts the user to log in or create an account (if not already loggedin) 
7. User logs in or registers
8. System temporarily locks the selected room during the booking process
9. User selects a payment method and makes payment
10. System processes the payment
11. If payment is successful 
- System confirms the booking
- User receives confirmation via email or in-app notifications
12. If payment fails
- User is notified to retry or select a different payment method
13. User cancels the booking within the allowed period (up to 24 hours before checkin)
14. System processes the cancellation and issues a full refund
  
### 7.2 Hotel Owner Flow
1. Hotel owner opens the platform and registers as a business partner
2. System records the registration and notifies the owner the account is under review
3. Admin reviews and approves the account
4. System notifies the hotel owner of successful registration
5. Hotel ownner adds hotel and room details including location, room types, pricing, guest capacity, extra bed charges, amenities and property policies
6. System saves hotel information
7. Hotel owner updates room availabilty and pricing through the dashboard
8. System saves updated information
9. When a booking is made, system notifies the owner via in-app notification
10. Hotel owner views and manages booking history through the dashboard

### 7.3 Admin Flow
1. Admin logs in to the system
2. System displays the admin dashboard
3. Admin reviews hotel owner registration requests
4. Admin approves or rejects based on the following criteria
   - If required information is complete and valid, registration is approved
   - If information is incomplete, invlaid or suspicious, registration is rejected
5. System updates the account status and notifies to the hotel owner
6. Admin monitors the hotel listings on the platform
7. Admin can edit, suspend, or remove listings that violate platform policies and notify the owner
8. Admin monitors bookings and transactions
9. System displays booking and payment records to the admin
10. Admin manages user accounts (view, suspend or deactivate users if necessary)






















oon- Offline payment (cash handling)
- Third-party integrations beyond basic payment and notification
