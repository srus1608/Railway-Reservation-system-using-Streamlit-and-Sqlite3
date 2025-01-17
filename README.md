### Railway Reservation System using Streamlit and SQLite3
This project is a Railway Reservation System built using Streamlit for the frontend and SQLite3 for the backend. It provides a simple, interactive web interface where users can check for available trains, book tickets, and view the reservation history. All the data is stored in an SQLite database (railway.db).

## Project Structure
1. main.py: The main Python script containing the logic for the Railway Reservation System. It uses Streamlit to create an interactive user interface and SQLite3 to manage the database.
2. railway.db: The SQLite3 database containing tables for storing train details, user reservations, and ticket information.
   
## Installation
Clone the repository:

git clone https://github.com/srus1608/Railway-Reservation-system-using-Streamlit-and-Sqlite3.git
Navigate into the project directory:

cd Railway-Reservation-system-using-Streamlit-and-Sqlite3

Run the application: Once the dependencies are installed, you can run the application using the following command:

streamlit run main.py
Access the application: After running the command above, open your browser and go to:

http://localhost:8501
The Streamlit app should now be running, allowing you to interact with the Railway Reservation System.

### Features
1. Train Search: Users can search for available trains based on the source and destination stations.
2. Ticket Booking: Users can book tickets for available trains by entering passenger details.
3. Reservation History: Users can view a history of their reservations and track their bookings.
4. Interactive Interface: The app uses Streamlit to create an intuitive, easy-to-use interface for users.
   
## Files
1. main.py: The main Python file that handles the logic for the user interface and interactions with the SQLite database.
2. railway.db: The SQLite database file that contains the train and reservation data. This file is automatically created if not already present.
3. main.py (File Overview)
4. 
This file contains the following sections:

1. Streamlit UI Elements: The main interface for interacting with the system.
2. Database Integration: Functions to interact with railway.db for retrieving and storing train and reservation data.
3. Train Search and Booking: Logic to allow users to search for trains, book tickets, and view their reservation history.
   
railway.db (Database Overview)
The database contains the following tables:

1. trains: Stores train information including train number, source, destination, and availability.
2. reservations: Stores user reservation details including the user's name, train number, and number of tickets.

   
## Technologies Used
1. Streamlit: For creating the interactive web interface.
2. SQLite3: For managing the backend database.
3. Python: The main programming language for the logic and data handling.
   
## Example Usage
Once the app is running, the user can:

1. Search for trains: Enter the source and destination stations to find available trains.
2. Book a ticket: Select a train, enter personal details (e.g., name, number of passengers), and confirm the booking.
3. View reservation history: Check the list of previous reservations made by the user.
4. Cancel Tickets.
