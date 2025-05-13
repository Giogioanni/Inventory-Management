# Inventory Management Android Application

This Android application provides a basic inventory management system for small businesses or personal use. It allows users to:

* **Manage Inventory:** Add, edit, and delete inventory items, tracking item names, quantities, and dates.
* **User Authentication:** Securely manage access with user login and account creation.
* **Low Stock Alerts:** Configure notifications to be alerted when item quantities fall below a specified threshold.  Optionally, receive SMS alerts (permission required).
* **Settings:** Customize notification settings, such as the item to monitor and the threshold quantity.
* **Data Storage:** Utilizes an SQLite database for persistent storage of inventory and user data.

## Key Features:

* User authentication (login/create account)
* Inventory item CRUD (Create, Read, Update, Delete) operations
* Low stock notifications (local and SMS)
* Configurable settings for low stock alerts
* SQLite database integration
* Mixed UI: XML layouts and Jetpack Compose (for login)
* Runtime permission handling for SMS

## Technologies Used:

* Java
* Kotlin
* Android SDK
* SQLite
* Jetpack Compose
* AndroidX Libraries

## Permissions:

* SEND_SMS (optional, for SMS alerts)

## Setup:

1.  Clone the repository.
2.  Open the project in Android Studio.
3.  Build and run the application on an Android emulator or device.

## Future Enhancements:

* Implement more robust error handling and input validation.
* Add sorting and filtering to the inventory list.
* Improve UI/UX with a consistent design language.
* Explore cloud-based data storage options.
* Add reporting features (e.g., inventory summaries).

Giogioanni Morales
```
