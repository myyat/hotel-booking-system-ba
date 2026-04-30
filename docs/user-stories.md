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
  Then the system confirms the payment and completes the booking

- Given the user submits payment  
  When the payment processing fails  
  Then the system displays an error message and prompts the user to retry

- Given the user is on the guest details page  
  When the user submits payment with invalid payment details  
  Then the system displays a validation message 

  









