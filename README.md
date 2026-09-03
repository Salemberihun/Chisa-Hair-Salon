PROJECT NAME:
Chisa-Hair-Salon

PROBLEM:
Helps businesses show all their services to their customers and make it easier for customers find the service they want without needing to call the salon for every booking  instead, they can  find services, pick a date and time then book an appointment.

USERS:
- Customer
- Admin

MVP:
    CUSTOMER:
- Home Page
- Registration
- Login
- Booking Services
- Appointment Date Page
- Appointment Available Time
- Customer Booked Appointments Notification page
        ADMIN:
- Customers Appointment Management
- Services Management
- 

DATABASE:

- Service: 
profile_image_url,
service_name,
service_description,
duration,
service_price,
service_status,
service_status,
service_id(primary key)
  
- Bookings: 
service_id(foreign key),
Booking_id(primary key),
user_id(foreign key),
Booking_status(complete,pending,cancelled),
Booking_time, 
Booking_date
  
- Users: 
First_Name,
Last_name ,
Email, 
Phone_number,
Password,
User_id(primary key), 
role,
is_active

- Database connections:
    A user can make many appointments/bookings
    A Booking can have many services
  

  


















TECHNOLOGY USED:
 - Flask, PostgreSQL, SQLAlchemy, React, and TypeScript.
