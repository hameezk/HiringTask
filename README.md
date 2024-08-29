# Flutter Hiring Task

Hi Flutter developers! Here’s your hiring task involving the creation of four screens. The primary goal is to implement a functional login feature using an API and to set up a basic signup flow with validation. Below are the detailed requirements for each screen:

## 1. Login Screen

**Purpose**: To allow users to log in using their email and password.

**Requirements**:
- Implement two text fields for email and password input.
- Validate the email field to ensure it is in a proper email format.
- Validate the password field to ensure it is not empty and meets any specified requirements (e.g., minimum length).
- Use the static credentials for login:
  - **Email**: `user@speedforce.com`
  - **Password**: `password`
- Call a mock API to simulate a login and fetch user details if the credentials match.
- Display an error message if the login fails due to incorrect credentials or any other validation error.
- Navigate to the home screen upon successful login.

## 2. Signup Screen

**Purpose**: To allow new users to register for the application.

**Requirements**:
- Include fields for user registration such as name, email, password, and confirm password.
- All fields should be validated:
  - The name should not be empty.
  - The email should be in a valid email format.
  - The password should meet security requirements (e.g., minimum length).
  - Confirm password should match the password field.
- The signup button does not need to connect to an API but should validate all input fields.
- Upon clicking the signup button after successful validation, navigate to the home screen.

## 3. Home Screen

**Purpose**: To serve as the landing page after a successful login or signup.

**Requirements**:
- Display a welcome message with the user’s email (use the static email `user@speedforce.com` for demonstration).
- The header should show the basic details and total earnings.
- The body should show an invitation to join the app.

## 4. Profile Screen

**Purpose**: To display user profile details.

**Requirements**:
- Show user information fetched from the mock API used in the login process (use the same data for display purposes).
- Include a button to navigate back to the home screen.

## General Requirements

- The app should be built using Flutter and Dart.
- The app should follow the UI as provided in the Figma design.
- Follow best practices for Flutter development, including using appropriate widgets, managing state effectively, and structuring the codebase.
- Ensure a clean and user-friendly UI/UX design for all screens.
- The login API should be a mock service that simulates an actual API call.
- The app should handle all errors gracefully, including network issues and input validation errors.
- Make sure the app is responsive and works on different screen sizes and orientations.

## Submission Requirements

- Provide a Git repository link with your code and clear instructions on how to run the app.
- Include a `README` file detailing your approach, any assumptions made, and instructions for setting up any necessary mock APIs.
- Briefly explain any design or architectural decisions in your `README`.

We look forward to seeing your implementation of these features!

## Important Links

- **Figma**: [Speedforce Digital Flutter Hiring Task](https://www.figma.com/design/clSTtfKux4d8CxqjDHA6Di/Speedforce-Digital-Flutter-Hiring-Task?node-id=0-1&m=dev&t=gq3TNGgRaWo3bt3j-1)
- **GitHub**: [GitHub Repository](https://github.com/hameezk/HiringTask)
- **Login API**: [GET](https://my-json-server.typicode.com/hameezk/HiringTask/login)

Best of luck!
