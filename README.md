# CinemaBookingApp

CinemaBookingApp is an Android application designed for a small cinema, providing customers with the ability to view the current movie lineup, book tickets and receive the ticket confirmation via their email address. Additionally, the app offers employees the capability to efficiently manage the movie list and related information. This application is developed as a solo university project for a software engineering class.

## Features

- User registration and authentication
- Three user types: User, Employee, Admin
- Browse and search for movies
- Convenient movie ticket booking process
- Different ticket options available for adults, students, and kids, with corresponding pricing for each category
- Automatic ticket delivery to the customer's email address
- Employees have access to detailed customer information for each movie reservation
- Efficient management of the movie list by employees
- Administrative control over user types, including employee management
- Multi-language support: English and Greek

## Getting Started

These instructions will help you get a copy of the project up and running on your local machine for development and testing purposes. You can also download the APK file to explore the app without setting up your own database.

### Prerequisites

- Android Studio: [Download and install Android Studio](https://developer.android.com/studio)
- Git: [Download and install Git](https://git-scm.com/)

### Installation

1. Clone the repository:
git clone https://github.com/DSukhan/PTMO_MAIN.git

2. Open the project in Android Studio.

3. Build and run the app on an emulator or a physical device.

### Note: Database Configuration

This project requires a database for storing and retrieving data. To set up the database for the application, please follow these steps:

1) Create a new database instance or use an existing one.
2) Obtain the necessary database credentials.
3) Open the config_template.xml file located in app/src/main/res/values/.
5) Update the database configuration values in the config_template.xml file with your own database credentials and remove the comments to make it work.
6) Rename the config_template.xml to config.xml if you wish.

By following these steps, you can configure the application to use your own database and ensure the proper functioning of the app. Please note that the config.xml file is not included in the repository for security reasons, and you need to provide your own database credentials.


## Technologies Used

- Android
- Kotlin
- Firebase Authentication
- Firebase Realtime Database
- Firebase Cloud Firestore
- Firebase Storage
- JavaMail API

## Future Enhancements

- Ticket Booking History: I would like to implement a feature that allows customers to view their past ticket bookings, providing them with a convenient way to track their movie-going history.
- Movie Details Editing: Currently, employees need to remove a movie and add a new one to update movie details. To improve efficiency, I aim to develop a functionality that enables employees to edit existing movie details directly, avoiding the need for redundant actions.
- Booking Modification: I intend to introduce a functionality that allows customers to modify their bookings. This will include options such as changing seats or adding more tickets to an existing booking, providing greater flexibility and convenience to the customers.

These planned enhancements will further enhance the usability and functionality of the application, providing an improved experience for both customers and employees.

## Contributing

Contributions are welcome! If you find any issues or want to add new features, feel free to submit a pull request.
