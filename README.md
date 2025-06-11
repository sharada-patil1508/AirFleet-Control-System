AirFleet-Control_System is a desktop-based airline management application developed using Java Swing for the user interface and MySQL for the backend database. The system provides a seamless experience for managing flight operations, including secure user login, flight details via drop-down menus, adding user information, handling payments, viewing journey details, and flight cancellations. With a responsive and interactive GUI, this application is designed to offer a reliable and user-friendly solution for managing airline services efficiently on a desktop environment.

![alt image](https://github.com/sharada-patil1508/AirFleet-Control-System/blob/090b86ce40fb984ae18bf89860c4e6355eeda2bb/Login%20Page.png)

🔐 Login Page

The application begins with a user-friendly Login Page built using Java Swing, featuring input fields for Username and Password. It includes three interactive buttons:

Submit: Validates the credentials and proceeds to the main dashboard.

Reset: Clears the input fields.

Close: Exits the application safely.

This GUI ensures secure access to the system and provides a smooth start to the user workflow.

![alt image](https://github.com/sharada-patil1508/AirFleet-Control-System/blob/d514dafd39d06efa8ee0fadc95bf2f0ce145a353/Welcome%20Page.png)

🎉 Welcome Page


After a successful login, users are greeted with a Welcome Page designed using Java Swing. This page provides a friendly introduction to the AirFleet-Control_System, often displaying the user's name or role along with navigation options. It acts as the central hub, guiding users to various features like flight information, user management, bookings, and more. The intuitive design ensures a smooth transition into the main application.

![alt image](https://github.com/sharada-patil1508/AirFleet-Control-System/blob/53cf11097b243099f2062a0377d24fd12fd54f17/DashBoard.png)

🖥️ Dashboard


The Dashboard serves as the control center of the application, built using Java Swing for a smooth and interactive user experience. From this screen, users can access all major functionalities of the system through clearly labeled buttons or menu options:

✈️ Flight Information: View and manage details about available flights, including timings, destinations, and seat availability.

👤 Add Customer Details: Input and store customer data such as name, age, contact info, and travel preferences.

🧳 Journey Details: Track journey information like departure and arrival cities, dates, and travel status.

💳 Payment Details: Record and manage payment-related information for flight bookings.

❌ Cancellation: Cancel booked flights and update all related records in the database.

This centralized dashboard allows for efficient workflow and seamless navigation across all airline operations.

![alt image](https://github.com/sharada-patil1508/AirFleet-Control-System/blob/d86ffdbdb91cc828735a8d591ef740b9708f3ca6/Flight_info.png)

🔍 Flight Information Lookup


The system allows users to enter a Flight Code and click on the "Show" button to retrieve detailed information about the respective flight. Once submitted, the following details are displayed in the interface:

🛫 Source

🛬 Destination

👥 Capacity

🏷️ Class Name

🆔 Class Code

This feature helps users quickly access and verify flight details stored in the backend MySQL database, improving operational efficiency and decision-making.

![alt image](https://github.com/sharada-patil1508/AirFleet-Control-System/blob/1d68d8c382ba3e263aba57645d0eecfeb639529d/Customer_details.png)

🧾 Customer Details Entry


The system provides a dedicated section to add customer details linked to a specific flight. Users can input all essential passenger information, which is then stored securely in the MySQL database. The following fields are included in the form:

✈️ Flight Code – Links the customer to a specific flight

🛂 Passport Number – Unique ID for international identification

🎫 PNR Number – Passenger Name Record for tracking the booking

🏠 Address – Residential address of the customer

🌍 Nationality – Country of citizenship

👤 Name – Full name of the passenger

🚻 Gender – Male/Female/Other

📞 Phone Number – Contact information for communication

This form ensures accurate and complete passenger data collection, which is vital for ticketing, security, and record management.

![alt image](https://github.com/sharada-patil1508/AirFleet-Control-System/blob/6209f89462dbad1e19c13db8055067b396c77b9e/Payment.png)

💳 Payment Details

The Payment Details module enables users to securely record and manage flight booking payments. Once the customer and flight information is confirmed, the system collects essential payment-related inputs through an interactive Java Swing form. The following fields are typically included:

🧾 PNR Number – Links the payment to a specific passenger and booking

💸 Amount Paid – Total fare paid by the customer

💳 Payment Mode – Options such as Credit Card, Debit Card, UPI, or Net Banking

📅 Payment Date – Automatically captured or selected by the user


![alt image](https://github.com/sharada-patil1508/AirFleet-Control-System/blob/a3a4758d729134a64be8e63d8464966879c2a6d0/Journey%20Details.png)

🧳 Journey Details


The Journey Details module allows users to fetch travel-specific information by entering the Source and Destination cities. Once the inputs are provided and the "Show" button is clicked, the system retrieves and displays all relevant journey details from the MySQL database, including:

✈️ Flight Code

⏰ Departure Time

🕓 Arrival Time

📅 Travel Date

👥 Available Seats

💰 Fare

🏷️ Class Type

This feature helps passengers and administrators quickly identify available flight options between two locations, making the travel planning process fast and efficient.
