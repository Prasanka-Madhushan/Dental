# Dental Appointment Booking Website

A comprehensive web application designed to streamline the process of booking dental appointments for patients and managing schedules for dental practices.

## Features

- **Patient Registration and Login:** Secure patient accounts with authentication.
- **Appointment Scheduling & Management:** Users can book, view, and manage appointments.
- **Admin Dashboard:** Administrative interface for managing appointments, patient data, and system settings.
- **Email Notifications:** Automated email reminders for upcoming appointments.
- **Responsive Design:** Optimized for both desktop and mobile devices.
- **Secure Authentication:** Utilizes JSON Web Tokens (JWT) for secure user authentication.

## Technologies Used

- **Frontend:** React.js
- **Backend:** Node.js with Express.js
- **Database:** MongoDB Atlas
- **Authentication:** JWT (JSON Web Tokens)
- **Styling:** Tailwind CSS
- **Deployment:** Vercel (Frontend), Heroku (Backend)

## Installation

### Prerequisites

Before you begin, ensure you have the following installed on your system:

- [Node.js](https://nodejs.org/) and npm (Node Package Manager)
- A [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) account
- Vercel and Heroku accounts for deployment

### Steps to Set Up the Project

1. **Clone the Repository**

    ```bash
    git clone https://github.com/your-username/dental-appointment-booking.git
    cd dental-appointment-booking
    ```

2. **Install Dependencies**

   - **Server-side (Backend)**

     Navigate to the server directory and install the required packages:

     ```bash
     cd server
     npm install
     ```

   - **Client-side (Frontend)**

     Navigate to the client directory and install the necessary packages:

     ```bash
     cd client
     npm install
     ```

### Running the Application

To run the application locally, follow these steps:

1. **Start the Backend Server**

   ```bash
   cd server
   npm start
   
2. **Start the Frontend**

   ```bash
   cd client
   npm run dev

### Accessing the Application
- **Client:** http://localhost:3000
- **Admin Dashboard:** http://localhost:3000/admindash

## Contributing
Contributions are welcome! If you'd like to contribute, please open an issue or submit a pull request. Make sure to follow the project's code of conduct.

## License
This project is licensed under the MIT License.

## Acknowledgments
- **Frameworks & Libraries:** React.js, Node.js, Tailwind CSS, Express.js
- **Database:** MongoDB Atlas
- **Deployment:** Vercel, Heroku
