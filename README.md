# BUS-MANAGEMENT-SYSTEM
The following code in this depository is from MySQL and created for a databases project where three group members and I had to design and create a bus reservation database. The database would store information that allowed users to create accounts, make reservations, and purchase tickets from a bus station. The following gives a description of each aspect of the project from which I had to write the SQL code for.
LOGIN - checks if the given username and password combination is in the database, and checks if the user is a customer or a manager.

NEW USER REGISTRATION - Checks if the username is taken. Inserts new login into the database.

ADD SCHOOL INFO - Updates the boolean flag to show that the new customer if a student if the email ends in '.edu'

VIEW BUS SCHEDULE - Gets information for all the routes that a user inputted bus numbmer takes.

SEARCH  BUS/SELECT DEPARTURE - Outputs the bus number and the departure route based on the customer's preferred departure location, arrival location, and departure date.

TRAVEL EXTRAS AND PASSENGER INFO - Saves the number of bags a customer will take.

MAKE RESERVATION - If it is the user's first ticket, a new reservation is created for the customer. Also outputs the bus number, time (duration), departs from, arrives from, class, price, number of bags, and passenger name all in the reservation. The total cost is then calculated and a reservation can be deleted if the user chooses to. If the user accepts the reservation, the new reservation with a given ID is created and stored in the database.

UPDATE RESERVATION - Given the user's reservation ID, a customer can view their reservation of bus tickets where they can select a ticket to update with a new depature date, and the new total cost is calculated.

CANCEL RESERVATION - A customer can cancel a reservation and the amount to be refunded is calculated as follows: 80% of the original total cost will be refunded if the customer cancelled the reservation more than 7 days earlier than the earliest departure date, 50% of the original total cost will be refunded if the customer cancelled the reservation more than 1 day but less than 7 days earlier than the earliest departure date. A $50 cancellation fee will be deducted from the refund.

GIVE/VIEW REVIEWS - A customer can choose to either view bus reviews or give one themselves.

VIEW REVENUE REPORT - This report shows the total revenue of each month (only shows the previous three months).

VIEW POPULAR BUS ROUTES - This report shows top 3 most popular bus (calculated by number of reservations) of each month.
