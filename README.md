# Periodic Tables

[Test Out the App](https://www.markdownguide.org)

---
**Technologies used:*** *PostgreSQL, Express, Knex, React, Bootstrap, CSS*

---

This application exists for the restaurant industry. The typical user would be the employee(s) in charge of managing reservations and tabling at a restaurant. With Periodic tables, the user can easily: 

- See existing reservations
- Record a new reservation
- Update an old reservation with new information
- Enter a new table
- "Seat" a reservation at a free table, thus making that table "occupied"
- "Finish" a reservation's tabling when they have completed their meal. This moves the table back from "occupied" to "free" and removes the reservation from the database.

## Dashboard 

![dashboard-image](./front-end/readme-screenshots/Dashboard.png)

**The data that populates both tables is retreived from a PostgreSQL database using an Express and Knex-based API.**

Upon startup, the application loads the Dashboard page, which is set to display both the "reservations" table and "tables" table. The Dashboard defaults to today's date, so it will only load reservations that are set for today. 

## Create/Update Forms

![table-form-image](./front-end/readme-screenshots/Table-Form.png)

![reservation-form-image](./front-end/readme-screenshots/Reservation-Form.png)
