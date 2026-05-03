## Epic 1: Guest / User Booking System 
### User Story-1: Search Hotels 
As a traveler,  
I want to search for hotels by location and travel dates,   
so that I can find suitable accommodations that meet my preferences. 

**Acceptance Criteria**
- Given the user is on search hotels page  
  When the user enters location,travel dates and clicks search  
  Then the system displays a list of available hotels based on user's criteria

- Given the user is on search hotels page  
  When the user clicks search without entering location or travel dates  
  Then the system displays a validation message "Please enter location and travel dates"

- Given the user is on search hotels page  
  When no hotels match the search criteria  
  Then the system displays a message "No results found" 

### User Story-2: View hotel details
As a traveler,  
I want to view the hotel details  
so that I can decide if the hotel is suitable for me.

**Acceptance Criteria**
- Given the user is on the hotel details page  
  When the user views the hotel details  
  Then the system displays detailed information including price, room type, location, amenities, and reviews

- Given the user is on the hotel details page  
  When the page loads  
  Then the system displays accurate and up-to-date hotel information including price, room type, location, amenities,   and reviews

### User Story-3: Book a hotel
As a traveler,  
I want to book a hotel  
so that I can stay during my trip

**Acceptance Criteria** 
- Given the user is on the hotel booking page  
  When the user selects a room type, number of rooms and clicks "Book"  
  Then the system temporarily locks the selected room and displays the guest details page

- Given the user is on the guest details page  
  When the user enters required information and selects a payment method  
  Then the system proceeds to payment processing

- Given the user is on the hotel booking page  
  When the user clicks "Book" without selecting a room type and number of rooms  
  Then the system displays a message "Please select a room type and number of rooms"

- Given the user is on the guest details page  
  When the user clicks "Book" without selecting a payment method  
  Then the system displays a message "Please select a payment method"

- Given the selected room is no longer available   
  When the user attempts to book  
  Then system displays a message "This room is no longer available" 

### User Story-4: Make a payment 
As a traveler,   
I want to make a payment  
so that I can confirm my booking. 

**Acceptance Criteria**
- Given the user is on the guest details page   
  When the user submits payment  
  Then the system processes the payment securely 

- Given the user submits payment  
  When the payment is processed successfully  
  Then the system confirms the payment 
  And completes the booking
  And sends a confirmation via email and in-app notification
  
- Given the user submits payment  
  When the payment processing fails  
  Then the system displays an error message and prompts the user to retry

- Given the user is on the guest details page  
  When the user submits payment with invalid payment details  
  Then the system displays a validation message 

### User Story-5: Cancel Booking
As a traveler,  
I want to cancel my booking  
so that I can manage my travel plans and receive refund if eligible

**Acceptance Criteria**
- Given the user is on the booking details page  
  When the user cancels the booking within the allowed cancellation period  
  Then the system confirms the cancellation  
  And displays a message "Booking cancelled"  
  And the system issues a full refund according to cancellation policy

- Given the user is on the booking details page  
  When the user cancels the booking after the allowed cancellation period  
  Then the system rejects the cancellation 
  And displays a message "This booking cannot be cancelled at this time" 

- Given the user cancels the booking within the allowed cancellation period
  When the system processes the refund
  The system issues the refund
  And notifies the traveler via email and in-app notification 

## Epic 2: Hotel Owner Management System 
### User Story-1: Register as a Hotel Owner
As a hotel owner,
I want to register on the platform 
so that I can list my hotel and receive bookings.

**Acceptance Criteria**
- Given the hotel owner is on the hotel registration page  
  When the hotel owner enters requierd information including business name, contact information, email and password     and clicks "Register"
  Then the system creates the account 
  And set the account status to "Pending Review"  
  And notifies the hotel owner "Your registration is under review" via email or in-app notification 

- Given the hotel owner is on the hotel registration page  
  When the hotel owner clicks "Register" without entering requierd information 
  Then the system prevents submission
  And displays a message "Please enter all required information to complete registration" 

- Given the email is already registered  
  When the hotel owner attempts to register again 
  Then the system displays a message "This account is already registered" 

### User Story-2: Add hotel details
As a hotel owner,  
I want to add hotel details  
so that I can list my property on the platform for travelers to view and book

**Acceptance Criteria**
- Given the hotel owner is on the hotel details page  
  When the hotel owner enters required information including hotel name, location, amenities, prices, photos and        clicks "Submit"  
  Then the system saves the hotel information  
  And displays a message "Hotel details added successfully"   

- Given the hotel owner is on the hotel details page  
  When the hotel owner clicks "Submit" without entering required information  
  Then the system displays a message "Please fill in all required hotel details to complete"

- Given a hotel with the same name and location already exists  
  When the hotel owner attempts to add the same hotel  
  Then the system displays a message "This hotel is already listed" 

### User Story-3: Manage Rooms and Pricing
As a hotel owner,
I want to manage rooms and pricing 
so that I can update room types and adjust prices according to demand or seasons

**Acceptance Criteria**
- Given the hotel owner is on the room management page  
  When the hotel owner adds or updates room types, prices, availability and clicks "Save"  
  Then the system saves the room details  
  And displays a message "Room details updated successfully"

- Given the hotel owner is on the room management page  
  When the hotel owner enters invalid price (e.g., negative value)  
  Then the system displays a message "Invalid price. Please enter a valid amount"  

- Given the hotel owner is on the room management page  
  When the hotel owner clicks "Save" without entering required information  
  Then the system displays a message "Please fill in all required room details"  

- Given the hotel owner is on the room management page  
  When the hotel owner clicks "Save" without making any changes  
  Then the system displays a message "No changes were made"  
  And does not update the room details

 ### User Story-4: Manage Bookings
As a hotel owner,
I want to manage bookings, 
so that I can view, track and handle customer researvations efficiently.

**Acceptance Criteria**
- Given the hotel owner is on the booking management page  
  When the system loads bookings  
  Then the system displays a list of bookings with details such as customer name, room type, booking dates and status

- Given the hotel owner is on the booking management page  
  When the hotel owner selects a booking  
  Then the system displays detailed booking information

- Given the hotel owner is on the booking management page  
  When there are no bookings available  
  Then the system displays a message "No bookings found"

## Epic 3: Admin Management System 
### User Story-1: Review Registration
As an admin, 
I want to review registrations, 
so that I can verify and decide whether to approve or reject them based on platform rules






