# appdev_finalproject


## Features and Widgets

### Main Dart (`main.dart`)

- **Entry Point**: `void main()` initializes the app.
- **DesktopHomeScreen Widget**:
  - **`SingleChildScrollView`**: Allows the screen content to be scrollable.
  - **`Center`**: Centers the content on the screen.
  - **`Column`**: Arranges widgets vertically.
  - **`Container`**: Used for the background image of the screen.
    - **`BoxDecoration`**: Sets the background image with `DecorationImage`.
  - **`Padding`**: Adds padding around the "Services" title.
  - **`Text`**: Displays static text such as titles and service prices.
  - **`SingleChildScrollView`**: Enables horizontal scrolling for the service cards.
  - **`Row`**: Aligns service cards horizontally.
  - **`Card`**: Creates a card UI for each service with border and rounded corners.
  - **`ElevatedButton`**: Provides a button for booking a service.
  - **`AlertDialog`**: Displays booking confirmation and service info dialogs.

- **MobileHomeScreen Widget**:
  - **`Scaffold`**: Provides the basic structure for the home screen with an AppBar and body.
  - **`AppBar`**: Displays the title of the app.
  - **`ListView`**: Allows vertical scrolling for a list of services.
  - **`Container`**: Used for the background image with a fixed height.
  - **`Padding`**: Adds padding around various elements.
  - **`Text`**: Displays the "Services" title and service details.
  - **`Row`**: Aligns service cards horizontally within a scrollable view.
  - **`Card`**: Creates a card UI for each service with a border and rounded corners.
  - **`ElevatedButton`**: Allows users to book a service, leading to a dialog for booking confirmation.

### Login Dart (`login.dart`)

- **LoginScreen Widget**:
  - **`Scaffold`**: Provides the structure for the login screen with an AppBar.
  - **`AppBar`**: Displays the title of the login screen.
  - **`Padding`**: Adds padding around the form fields.
  - **`TextFormField`**: Collects user input for username and password.
    - **`TextEditingController`**: Controls the text being edited.
    - **`InputDecoration`**: Customizes the appearance of text fields.
  - **`ElevatedButton`**: Used for the login button.
  - **`Snackbar`**: Displays login success or error messages.

### Profile Dart (`profile.dart`)

- **ProfileScreen Widget**:
  - **`Scaffold`**: Provides the structure for the profile screen with an AppBar.
  - **`AppBar`**: Displays the title of the profile screen.
  - **`Padding`**: Adds padding around the profile fields.
  - **`TextFormField`**: Allows users to edit profile details.
  - **`ElevatedButton`**: Saves the updated profile information.
  - **`Text`**: Displays profile details and labels.

### Appointment Dart (`appointment.dart`)

- **AppointmentScreen Widget**:
  - **`Scaffold`**: Provides the structure for the appointment screen with an AppBar.
  - **`AppBar`**: Displays the title of the appointment screen.
  - **`Padding`**: Adds padding around the appointment fields.
  - **`TextFormField`**: Collects user input for service selection, date, and time.
    - **`InputDecoration`**: Customizes the appearance of text fields.
  - **`IconButton`**: Opens date and time pickers.
  - **`showDatePicker`**: Allows users to select a date.
  - **`showTimePicker`**: Allows users to select a time.
  - **`ElevatedButton`**: Books the appointment and shows a confirmation dialog.
  - **`AlertDialog`**: Displays appointment booking confirmation and details.

## Getting Started

To set up and run this project locally, follow these steps:

1. **Clone the repository:**

   ```sh
   git clone <repository-url>

2. **Navigate to the project directory:**
   ```sh
   cd <project-directory>

3. **Install dependencies:**
   ```sh
   flutter pub get

4. **Run the application**
   ```sh
   flutter run

Dependencies
    This project uses Flutter and its core dependencies. Ensure that you have Flutter installed and configured on your machine. If additional dependencies are used, they should be listed in the pubspec.yaml file.

Contact
    For questions or feedback, contact jeromerivera0820@gmail.com
