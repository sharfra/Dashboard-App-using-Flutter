# Dashboard-App-using-Flutter
This is a simple Flutter application designed to demonstrate the creation of a user-friendly dashboard screen. The app includes features for displaying, searching, and sorting a list of users, as well as navigating to secondary screens for reports and user creation.

This project was created to fulfill the requirements outlined in the provided assignment details.



## Features
#### 1. Dashboard Screen :
- Displays a scrollable list of user cards.
- Each card shows basic user details (name, email).
- Search Functionality: A search bar to filter users by name (case-insensitive).
- Sort Functionality: A button to toggle sorting the user list alphabetically (A-Z / Z-A).
#### 2. Report Screen :
- Accessible from the dashboard.
- Displays a static list of predefined reports.
#### 3. Create User Screen :
- A simple form to simulate creating a new user.
- Includes fields for name and email with basic validation.


## Technical Details
- #### State Management : 
  Uses  `StatefulWidget`and basic state management (`StatefulWidget`) for simplicity.
- #### Navigation : 
  Implements named routes (Navigator.pushNamed) for clear and decoupled screen transitions.
- #### UI : 
  Built with standard Material Design widgets, including `ListView`, `Card`, `TextField`, and `ElevatedButton`.
- #### No External Dependencies :
  The project uses only the core Flutter SDK.


## Deployment
To deploy this project follow below steps:
#### 1. Clone the repository :
```bash
  https://github.com/sharfra/Dashboard-App-using-Flutter.git
```
#### 2. Navigate to the project directory :
```bash
  cd Dashboard-App-using-Flutter
```
#### 3. Install dependencies :
```bash
  flutter pub get
```
#### 4. Run the app :
```bash
 flutter run
```
