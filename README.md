<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Railway Ticket Reservation System</title>
    
</head>
<body>

    <header>
        <h1>Railway Ticket Reservation System</h1>
    </header>

    <section id="features">
        <p>This project is a backend implementation of a Railway Ticket Reservation System, developed using .NET Framework and C# language.
        It provides functionalities for both users and administrators to manage train schedules, seat details, and ticket bookings.</p>
        <h2>Features</h2>
        <h3>Admin Panel</h3>
        <ul>
            <li>CRUD operations for train details</li>
            <li>CRUD operations for seat details</li>
            <li>Authentication and authorization for admin access</li>
            <li>Secure endpoints using JWT authentication</li>
            <li>Integration with SMTP email service for notifications</li>
        </ul>
        <h3>User Dashboard</h3>
        <ul>
            <li>Ticket booking functionality</li>
            <li>Ticket cancellation feature</li>
            <li>Password reset option</li>
            <li>Update user profile details</li>
            <li>Secure authentication with JWT tokens</li>
        </ul>
    </section>

    <section id="technologies">
        <h2>Technologies Used</h2>
        <ul>
            <li>.NET Framework</li>
            <li>C# Programming Language</li>
            <li>Microsoft SQL Server for database management</li>
            <li>JWT authentication for secure user access</li>
            <li>SMTP email sending for notifications</li>
        </ul>
    </section>

    <section id="installation">
        <h2>Installation and Setup</h2>
        <ol>
            <li>Clone the repository to your local machine.</li>
            <li>Open the project in Visual Studio.</li>
            <li>Configure the connection string in the <code>appsettings.json</code> file to connect to your MSSQL Server.</li>
            <li>Run the database migrations to create the necessary tables.</li>
            <li>Build and run the application.</li>
        </ol>
    </section>

    <section id="usage">
        <h2>Usage</h2>
        <ul>
            <li>As an admin, log in to access the admin panel where you can manage train and seat details.</li>
            <li>As a user, log in to book tickets, cancel bookings, update profile information, and reset passwords.</li>
        </ul>
    </section>

    <section id="contributions">
        <h2>Contributions</h2>
        <p>Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.</p>
    </section>

    <footer>
        <p>&copy; 2024 Railway Ticket Reservation System. All rights reserved.</p>
    </footer>

</body>
</html>
