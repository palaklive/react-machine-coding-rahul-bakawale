# React JS Machine Coding Round
# Hello Sir, please review my code at the following link
https://github.com/Rahul-bakawale/viitorcloud

## Project Overview

Build a React JS application that supports user registration, login, and a secure dashboard. The dashboard will display a customer table sourced from static JSON data with search, filtering, and custom pagination features. This assignment tests your ability to design and develop a complete, functional, and well-structured React application using modern best practices.

---

## Functional Requirements

### 1. Registration Page

- **Form Fields:**
  - **Username:** Text input.
  - **Email:** Text input with email format validation.
  - **Password:** Password input.
  - **Confirm Password:** Password input to verify that it matches the password.

- **Validations:**
  - All fields must be filled in.
  - The email must follow a valid email format.
  - The password and confirm-password fields must match.
  - Both username and email should be unique. (Simulate uniqueness by checking against the locally stored user list.)

- **Functionality:**
  - On form submission, perform validations and if successful, store the user details locally (e.g., in local storage or in memory for simulation).
  - Display appropriate error messages for validation failures.

---

### 2. Login Page

- **Form Fields:**
  - **Username/Email:** Single input that accepts either the username or the email.
  - **Password:** Password input.

- **Validations:**
  - Verify that the entered username/email and password match an existing user record.
  - Display error messages for incorrect credentials.

- **Functionality:**
  - On successful login, redirect the user to the Dashboard.
  - Maintain authentication state (e.g., using React Context or any state management library).
  
---

### 3. Dashboard (Private Page)

- **Access Control:**
  - The dashboard is a private route; only accessible after a successful login.
  - If an unauthorized user tries to access this page, automatically redirect them to the login page.

- **Customer Table:**
  - **Data Source:** Use static JSON data to populate the customer table.
  - **Features:**
    - **Search:** Allow users to search across the entire table.
    - **Filtering:** Enable filtering based on specific fields such as name, number, email, and status.
    - **Custom Pagination:** Implement custom pagination controls to navigate through the customer data.
  - **UI Considerations:** Ensure the table is responsive and presents the data clearly.

---

## Technical Requirements

- **React Setup:**
  - Use React JS (functional components and hooks are recommended).
  - Utilize React Router for navigation and route protection.

- **State Management:**
  - Manage application state efficiently (React Context or any other state management library is acceptable).

- **Code Quality:**
  - Write modular, reusable, and well-documented code.
  - Follow best practices for component structuring and file organization.

- **UI/UX:**
  - Provide a clean and minimalistic UI.
  - Ensure responsiveness across devices.
  - Provide clear visual feedback on user actions (e.g., form validations and error states).

- **Testing:**
  - Include basic tests to ensure that validations and routing work as expected (if possible within the scope of the round).

---

## Additional Considerations

- **Data Handling:** Since there is no backend, simulate uniqueness checks and data storage locally.
- **Error Handling:** Gracefully handle and display errors (e.g., for invalid inputs or failed login attempts).
- **Extensibility:** Code should be written in a way that allows easy addition of features (like more fields or additional filters in the future).
