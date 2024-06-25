			CAR-PARK APPLICATİON
Carpark is an innovative mobile application that enables companies and individual users to easily manage their car parking needs within the city. 
The GPS-based car park locator shows users the nearest car parking spaces and available free parking spaces in real time.

System Requirements and Preliminaries:
  Operating System: Windows-based systems.
  RAM: At least 4GB (8GB recommended).
  Required Tools: Android Studio, Java Development Kit (JDK).
  Database we use: Firebase
  Firebase Account: For integration with Firebase, a Firebase account must be created.
  There is a firebase account and application id that we have already used for the first versions of the application.
  The necessary information about the database accounts of the project will be transferred with the application codes after the purchase.
  
Installation Process:
	Installing Android Studio:
  	Step 1: Go to the Official Website of Android Studio.
    Step 2: Click on "Download Android Studio" and accept the terms of use.
    Step 3: After the download is complete, run the downloaded .exe file and follow the steps of the installation wizard.
  Loading Carpark Project:
    Step 1: Download the file containing the source codes of the Carpark project. This will be provided to you as a .zip file.
    Step 2: Open the .zip file you downloaded and extract the contents to a folder.
    Step 3: Open Android Studio and click "Open an existing Android Studio project".
    Step 4: In the window that opens, locate and select the Carpark project folder you extracted.
  Firebase Integration:
    Step 1: Visit the Firebase Console website and create an account or log in with your existing database.
    Step 2: If you are creating a new database, create a new project and enter the name of your project.
    Step 3: Associate your Firebase project with the Carpark project in Android Studio. To do this, follow the instructions in the Firebase Console.
  Installing Dependencies and Configuring the Project:
    Step 1: In Android Studio, open the build.gradle (Module: app) file.
    Step 2: Add the necessary dependencies to the file and save it. Try to stick to the gradle file we provided to avoid some problems caused by the gradle version.
    Step 3: Apply the changes by clicking the "Sync Project with Gradle Files" button on the top menu of Android Studio.
    
Running and Testing the Application:
  Running the App on an Android Emulator or a Real Device:
  Step 1: Creating an Emulator (If Not Already Created)
  In Android Studio, click on the "AVD Manager" (Android Virtual Device Manager) icon in the upper right corner.
  Click "Create Virtual Device" and select a device profile for your device (e.g. Pixel 3).
  Download the desired Android version and complete the AVD configuration.
  Click the "Play" icon to launch the created AVD.
  Step 2: Running the Application
  Click on the "Run" button in the top menu of Android Studio.
  If the application behaves unexpectedly or gives errors, observe the errors using the "Logcat" section at the bottom of Android Studio.
  Errors are usually shown in red text. Examine the error messages and the line at which the application crashes.
  
Notes:
  If you are using a real Android device instead of an emulator, make sure to enable "USB Debugging" under "Developer Options" on your device.
  It is important to test the app's performance and user interface on a variety of devices and screen sizes to ensure its suitability for a wide range of users.
  
Application Features and Settings
  User Registration and Login System: The login of the users is done with the username and password specified by the user on the registration screen.
  Map and Car Park Listing: Using Google Maps API, showing users the car parks and empty parking spaces near them.
  Directions (Planned): A feature that will provide users with directions to the destination car park (under development).
  also has user profile editing feature.
  
  Our application is already a good example for users, although most APIs are paid and most features have not yet been developed. Users and companies can contact us at carpark290@gmail.com for any questions, feedback or suggestions.
