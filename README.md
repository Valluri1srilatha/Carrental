# 🚘 Car Rental Management System

A complete **Car Rental Web Application** built using **Java EE (Servlets + JSP)** and **Hibernate (JPA)** with a **PostgreSQL database**.  
It allows **admins** to manage car inventory and bookings, while **users** can view available cars and place bookings easily through a clean interface.

---

## 📋 Features

### 👥 User Features
- View all available cars.
- Book a car by entering name, start date, and end date.
- Receive real-time updates on car status.

### 🧑‍💼 Admin Features
- Register new cars into the system.
- View list of all bookings.
- Cancel a booking (which makes the car available again).

---

## 🏗️ Project Structure

carrentalsystem/
│
├── src/main/java/carrentalsystem/
│ ├── Avaliablecars.java # Displays available cars
│ ├── Bookcar.java # Handles booking logic
│ ├── Booking.java # Booking entity
│ ├── Car.java # Car entity
│ ├── Changestatus.java # Cancels booking & updates car status
│ ├── Listofbooking.java # Lists all bookings
│ └── Registercar.java # Registers new cars
│
├── src/main/webapp/
│ ├── index.jsp # Dashboard (home page)
│ ├── availablecars.jsp # Displays all available cars with booking form
│ ├── listofbooking.jsp # Shows all current bookings
│ └── registercar.jsp # Form for registering a new car
│
├── pom.xml # Maven configuration file
└── persistence.xml # JPA and database configurations

## ⚙️ Tech Stack

| Layer        | Technology Used |
|---------------|----------------|
| **Frontend**  | JSP, HTML5, CSS3 |
| **Backend**   | Java Servlets (JEE) |
| **Database**  | PostgreSQL |
| **ORM**       | Hibernate (JPA) |
| **Build Tool**| Apache Maven |
| **Server**    | Apache Tomcat 9 |

## 🗄️ Database Setup

1. Install **PostgreSQL** and create a database named `carrental`.
2. Configure `persistence.xml`

🚀 How to Run
 1.Clone the repository:
 2.git clone https://github.com/YourUsername/CarRentalSystem.git
 3.Open in Eclipse or IntelliJ as a Maven Project.
 4.Ensure dependencies from pom.xml are downloaded.
 5.Deploy on Apache Tomcat 9.
 6.Open in browser:

  http://localhost:8080/carrental/


  🧩 Application Flow
 1.Dashboard → Choose action: register car, view available cars, or list bookings.
 2.Register Car → Admin adds a new car.
 3.Available Cars → Users view cars and book them.
 4.Booking → Car status changes to "booked".
 5.List of Bookings → Admin can cancel bookings; car becomes available again.

 👩‍💻 Author

 Valluri Srilatha
Java Web Developer | PostgreSQL | Hibernate

🔮 Future Enhancements
 1.User login & authentication.
 2.Email notifications for bookings.
 3.Car search and filter options.
 4.Car image upload support.
 
