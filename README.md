# Booking-Ticket-Flight-SQL
SQL - Microsoft Access

# ERD
![ERD](https://github.com/user-attachments/assets/4bb260f1-d909-40da-9d3e-1917e15deae3)

# RELATIONAL SCHEMA
1. CABINCREW (CabinCrewID, CabinFName, CabinLName, CabinNoPhone)
2. PASSENGER (PassID, PassFirstName, PassLastName, PassAdd, PassNo, PassCity, PassState, PassGender, CabinCrewID*)
3. BOARDINGPASS (BoardingPassID, Gate, Seat, Class, CabinCrewID*)
4. MEAL (MealID, MealName, MealPrice
5. FLIGHT (FlightID, DepartDate, ArrivalDate, DepartTime, ArrivalTime, FlightFrom, FlightTo)
6. PAYMENT (PaymentID, PaymentTotal, PaymentDate, PaymentType, MealID*, PassID*)
7. BOOKING(PassID*, BoardingPassID*, FlightID*, TicketID*)
