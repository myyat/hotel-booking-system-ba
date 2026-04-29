## Epic 1: Guest / User Booking System 
### User Story-1: Search Hotels 
As a traveler, 
I want to search for hotels by location and travel dates, 
So that I can find suitable accommodations that meet my preferences. 

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

**Acceptance Criteria 
- Given the user is on the hotel booking page
  When the user selects room type, number of rooms and clicks "Book"
  Then the system temporarily locks the selected room and displays the guest details page

- Given the user is on the guest details page
  When the user enters requiered information and selects a payment method
  Then the system proceeds to payment processing

- Given the user is on the guest details page
  When the payment completes payment successfully
  Then the system confirms the booking and displays a message "Booking confirmed"

- Given the user is on the hotel booking page
  When the user clicks "Book" without selecting a room type, number of rooms
  Then the system displays a message "Please select a room type and number of rooms"

- Given the user is on the guest details page
  When the user clicks "Book" without selecting a payment method
  Then the system displays a message "Please select a payment method"

- Given the user is on the guest details page
  When the payment transaction fails
  Then the system displays an error message and prompt the user to retry or select a different paymethod

- Given the user is on the hotel booking page
  When the user attempts to book and given the selected room is no longer available
  The system displays a message "This room is no longer available" 











