# rn-assignment4-11144085
Jobizz App
Description
Jobizz is a React Native application designed to help users find job opportunities. It features a login screen and a home screen that displays featured and popular job listings. The app allows users to search for jobs, view detailed job information, and navigate between different screens.

Components
App
File: App.js
Description: The root component of the application. It sets up the navigation stack with two screens: LoginScreen and HomeScreen.

LoginScreen
File: screens/LoginScreen.js
Description: The login screen where users can enter their name and email to log in. It also provides options for social media logins (Facebook, Google, and Twitter).
Props:
navigation: Used to navigate to the HomeScreen with the user's name and email as parameters.

HomeScreen
File: screens/HomeScreen.js
Description: The home screen that displays the user's name and email. It also showcases featured and popular job listings. Users can search for jobs using the search bar and filter results.
Props:
route: Contains the parameters passed from LoginScreen (user's name and email).

Screens
1.LoginScreen
Usage:
Collects the user's name and email.
Navigates to the HomeScreen upon successful login.

2.HomeScreen
Usage:
Displays a personalized greeting with the user's name and email.
Shows a list of featured jobs in a horizontal scrollable list.
Displays a list of popular jobs in a vertical list.
Allows users to search for jobs using a search bar.
Includes a filter button for additional search options (not yet implemented).

Styles
File: styles.js
Description: Contains the styling information for all components. Uses the StyleSheet API from React Native to define styles for various elements like containers, text, images, and buttons.

Setup and Installation
Clone the repository.
Install the required dependencies using npm install or yarn install.
Run the application on an iOS or Android emulator using npm start or yarn start.

Usage
Start the application.
On the LoginScreen, enter your name and email.
Press the "Log in" button to navigate to the HomeScreen.
On the HomeScreen, view featured and popular job listings.
Use the search bar to find specific job positions.

Future Enhancements
Implement the filter functionality in the HomeScreen.
Add detailed job descriptions and application options.
Improve the UI/UX design for better user experience.
Integrate real job data from an API.


SCREENSHOT
![WhatsApp Image 2024-06-19 at 23 18 21_0e8824e4](https://github.com/Bansah-Kplorla/rn-assignment4-11144085/assets/170067731/f9b55cd4-4d86-4a78-9d91-e422760cadf1)


![WhatsApp Image 2024-06-19 at 23 22 22_f64f4914](https://github.com/Bansah-Kplorla/rn-assignment4-11144085/assets/170067731/67fa5c99-6151-404d-bc0b-9dcfbecbe591)




