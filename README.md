# CarDeals
Car Deals App
The Car Deals App is a platform that allows users to buy, sell, and browse cars within a seamless and intuitive mobile interface. Built using Kotlin and Firebase, the app enables users to easily manage car listings, view available cars for sale, and manage their profiles.

Features
User Authentication: Sign up, log in, and password recovery using Firebase Authentication.
Car Listings: Browse through cars for sale, with detailed information about each vehicle.
Sell Cars: Users can post their own cars for sale by providing make, model, price, and other relevant details.
Profile Management: Edit user details and update password.
Progress Dialog: Displays a loading indicator while data is being fetched from Firebase.
User-friendly UI: Displays car listings in a scrollable format using RecyclerView.
Firebase Integration: Real-time data synchronization with Firebase Database to manage cars and user data.
System Requirements
Hardware Requirements
Device: Smartphone or Tablet with Android 5.0 (Lollipop) or higher.
Screen Size: Minimum of 5 inches (larger screens provide a better experience).
Storage: At least 100 MB of free internal storage.
RAM: 2 GB RAM or more for smooth operation.
Processor: ARM-based processors (e.g., Qualcomm Snapdragon, MediaTek).
Software Requirements
Operating System: Android OS version 5.0 (Lollipop) or higher.
Development Environment:
Android Studio for app development.
Java Development Kit (JDK) version 8 or higher.
Android SDK for required libraries and tools.
Libraries and Tools
Firebase SDK for authentication, real-time database, and user management.
RecyclerView to display the list of cars in a scrollable format.
ProgressDialog to show a loading indicator when fetching data.
ViewBinding to simplify UI element references in the code.
Database
Firebase Realtime Database for storing car listings and user data.
Firebase Authentication for user login and registration.
Network Requirements
Wi-Fi or Mobile Data: Required for Firebase services to authenticate users and fetch real-time data.
Installation
Clone the repository
bash
Copy code
git clone https://github.com/your-username/CarDealsApp.git
Setup Firebase
Go to the Firebase Console.
Create a new project or use an existing one.
Add your Android app to the Firebase project and download the google-services.json file.
Place the google-services.json file in the app/ directory of your project.
Enable Firebase Authentication and Firebase Realtime Database in the Firebase Console.
Open the project in Android Studio
Open Android Studio.
Select Open an existing project and navigate to the folder where you cloned the repository.
Sync the project with Gradle files and let Android Studio download the necessary dependencies.
Usage
Sign Up: Open the app and create an account by entering your name, username, email, and password.
Log In: After registration, use your credentials to log in to the app.
Browse Cars: Once logged in, you’ll be shown a list of cars available for sale.
Post a Car for Sale: If you wish to sell a car, enter the car details (make, model, price) to list it in the app.
Manage Profile: View and edit your personal details or change your password.
Password Recovery: If you forget your password, you can reset it using the password recovery feature.

