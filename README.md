---

# Inizio - Event Management System

## Introduction
Welcome to the **Inizio** Event Management System repository! This system is designed to streamline the process of organizing, managing, and promoting a wide range of events, catering to various needs and preferences. Whether you're planning a professional conference, educational seminar, engaging workshop, lively social gathering, or any other event, this system provides the comprehensive tools and features necessary to ensure your event's success.

In addition to facilitating traditional event management tasks such as scheduling, registration, and attendee management, our system goes a step further by addressing the needs of public events. We understand the importance of securing sponsors and reaching a broader audience for your program. Therefore, our platform offers seamless integration to help you easily connect with potential sponsors and attract a diverse audience to your events.

## Key Features
- **Comprehensive Event Management:**
  - From event creation to attendee registration and feedback collection, our system offers end-to-end event management capabilities.

- **Public Event Support:**
  - Simplify the process of finding sponsors and promoting your public events to attract a larger audience.

- **Nearby Events:**
  - Quickly discover and engage with ongoing events in your vicinity, allowing for greater participation and community involvement.

Whether you're an event organizer, sponsor, or attendee, our Event Management System aims to enhance your experience and maximize the success of every event. Join us in revolutionizing the way events are planned, managed, and enjoyed!

## Technologies Used
- **Backend:** PHP
- **Frontend:** HTML, JavaScript
- **Database:** SQL

## Installation

### Prerequisites
Ensure you have the following installed:
- [XAMPP](https://www.apachefriends.org/index.html)
- [MySQL Workbench](https://www.mysql.com/products/workbench/)

### Steps
1. **Clone the Repository:**
   ```sh
   git clone https://github.com/yourusername/inizio.git
   ```

2. **Navigate to the Project Directory:**
   ```sh
   cd inizio
   ```

3. **Install PHP Dependencies:**
   ```sh
   composer install
   ```

4. **Set Up the Database:**
   - Open MySQL Workbench.
   - Create a new database.
   - Import the SQL schema provided in the `database` directory:
     ```sh
     mysql -u yourusername -p yourpassword yourdatabase < database/schema.sql
     ```

5. **Configure Environment Variables:**
   - Rename `.env.example` to `.env`.
   - Update the database credentials and other configuration settings in the `.env` file.

6. **Start the XAMPP Server:**
   - Open the XAMPP Control Panel.
   - Start Apache and MySQL services.

7. **Place Project Files in XAMPP Directory:**
   - Move the project directory to the XAMPP `htdocs` directory.
     ```sh
     mv inizio /path/to/xampp/htdocs/
     ```

8. **Access the Application:**
   - Open your web browser and navigate to `http://localhost/inizio` (or the appropriate URL for your setup).

## Usage

### User Guide
- **Attending an Event:**
  - Register for an account.
  - Browse the list of available events.
  - Click on an event to view details and register to attend.

- **Organizing an Event:**
  - Register as an organizer.
  - Create a new event by providing necessary details (title, date, location, etc.).
  - Manage registered attendees and communicate updates.

- **Sponsoring an Event:**
  - Register as a sponsor.
  - Browse events looking for sponsorship.
  - Select an event and choose a sponsorship package.

## Documentation
You can find the SDS and SRS documents uploaded above in the repository.
