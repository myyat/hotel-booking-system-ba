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
I want to 
