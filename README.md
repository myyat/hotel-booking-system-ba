# hotel-booking-system-ba
Business Analysis case study of an Online Hotel Booking System

1. Project Overview
Project Name: StayEase — Online Hotel Booking Platform
StayEase is an online hotel booking platform that connects travelers with hotel owners across Southeast Asia. The platform enables users to search, compare, and book accommodations, while allowing hotel owners to list properties, manage availability, and handle reservations through a centralized digital system.

2. Project Objectives
- Enable hotel owners to list, manage, and update property details, room availability, and pricing through a self-       service digital platform
- Allow travelers to search, compare, and book hotel accommodations with instant confirmation
- Support secure online payments and automated booking notifications
- Provide administrators with tools to manage users, listings, and transactions
- Reduce reliance on manual booking processes and high-commission third-party platforms

3. Problem Statment
   
For Travelers:
Travelers currently lack a reliable online platform to search and compare hotel accommodations. Without real-time visibility into room availability and pricing, booking decisions become difficult and time-consuming. Additionally, there is no automated confirmation system, requiring users to follow up manually to verify their reservation status.

For Hotel Owners:
Hotel owners have no dedicated digital platform to list and manage their properties online. Reservations are handled manually through phone calls or walk-in inquiries, leading to inefficiencies and risk of double bookings. Furthermore, owners lack digital tools to track occupancy rates and monitor revenue performance.

StayEase Solution:
StayEase addresses these challenges by providing a centralized platform where travelers can search, compare, and book accommodations with real-time availability and instant confirmation, while hotel owners can manage listings, reservations, and performance metrics through a single digital system.

4. Stakeholders
   
External Users
- Hotel Guest – Searches, compares, and books hotel accommodations through the platform
- Hotel Owner – Lists properties and manages room availability, pricing, and reservations

Business Stakeholders
- Product Owner – Defines business goals and approves system features
- Customer Support Team – Handles user inquiries, complaints, and booking issues

Technical Stakeholders
- Business Analyst – Gathers and documents system requirements
- Developers – Build and maintain the system
- QA/Testers – Test system functionality and ensure quality
- System Administrator – Manages system operations and user access

External Systems
- Payment Gateway – Processes online payments securely
- Notification Service – Sends booking confirmations via email/SMS

5. Requirements Elicitation (Stakeholder Questions)
This section includes assumed questions that a Business Analyst would ask stakeholders to understand system requirements for the Online Hotel Booking System.

4.1 Hotel Guest (User) Questions
- Who are the target users of the system?
- Can users search hotels without logging in?
- What filters should be available for hotel search (location, price, rating, dates)?
- Can users view hotel details without making a booking?
- Can users book instantly or require approval?
- How will users receive booking confirmation (email, SMS, or in-app notification)?
- What is the cancellation policy for bookings?
- Is refund allowed in case of cancellation? If yes, will it be full or partial?

4.2 Hotel Owner Questions
- How do hotel owners register on the platform?
- Can hotel owners manage their own listings?
- Can they update room availability and pricing in real time?
- How are bookings assigned or notified to hotel owners?
- Can hotel owners view and manage booking history?
  
4.3 Business & Product Questions
- Will the system be developed as a web application, mobile application, or both?
- What is the business model (commission-based, subscription, or both)?
- Is online payment mandatory for booking confirmation?
- What payment methods will be supported (card, digital wallet, etc.)?
- Which regions or countries will the platform support (local or global)?
- Are there any promotional or discount features required?
  
4.4 System / Technical Questions
- How does the system handle double bookings for the same room?
- What happens if room availability changes during the booking process?
- What should happen if a payment transaction fails?
- What external systems are required (payment gateway, notification service)?
- Should the system support real-time updates for availability and booking status?
- How will system notify users (email/SMS/app)?

These questions are based on assumptions for learning purposes and simulate real-world requirement gathering in a Business Analysis project. No real stakeholder interviews were conducted.

5. System Scope
In Scope (What system includes)
- Users can search hotels by location and dates
- Users can view hotel details (price, rooms, amenities)
- Users can book available rooms
- Users can make online payments
- Users can cancel bookings (based on policy)
- Hotel owners can add and manage hotel listings
- Hotel owners can update room availability and pricing
- System sends booking confirmation notifications

Out of Scope (What system does NOT include)
- Flight booking functionality
- Travel package or tour services
- Loyalty or reward programs (for now)
- Offline payment (cash handling)
- Third-party integrations beyond basic payment and notification
