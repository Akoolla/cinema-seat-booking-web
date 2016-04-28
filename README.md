
# Web interface for a cinema booking system

## Technology/Architecture Overview
* Layout and stylng utilising bootstrap (3.3.6)
* Business logic including bookings to be carried out by REST calls to a seperate service, ajax and jscript using jquery(1.11.2)
* Where possible validation should occur client side
* Mobile web first design approach, but should be responsive design and look fine at higher resoloutions

## Epics
* Browse and select a film screening
* Reserve seats, see cost, make booking
* Be able to cancel a booking
* View list of bookings for a screening and check those bookings in by cinema staff
* Reporting

## TODO's

- Browse and select a film screening
  - [x] Define and use rest call to retreive number of available seats for booking
  - [x] Define and use rest call to retreive cost of seats for specfic screening
  - [x] Write jscript to update total cost of screening based on screening seat costs and seats booked
  - [ ] Enable rest call to make booking, deal with issue of seats maybe being booked in the meantime
  - [x] Something I've done...
