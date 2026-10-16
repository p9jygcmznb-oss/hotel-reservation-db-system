# Hotel Reservation Management System - Sun City Hotel Resort

**Information Systems 1.2 - Database Project**

### Business Overview
Sun City Hotel Resort, Rustenburg - 120 rooms. This project replaces a manual booking book / Excel system that caused double bookings and revenue loss.

### 10 Entities (3NF)
1. DEPARTMENT
2. STAFF
3. ROOM_TYPE
4. ROOM
5. CUSTOMER
6. RESERVATION
7. PAYMENT
8. INVOICE
9. SERVICE
10. SERVICE_BOOKING

### Key Business Rules
- One ROOM_TYPE -> Many ROOMS
- One CUSTOMER -> Many RESERVATIONS
- CheckOut_Date > CheckIn_Date
- Room cannot be booked if Status = 'Maintenance'

### Tech Stack
- DBMS: MySQL
- Design Tool: draw.io