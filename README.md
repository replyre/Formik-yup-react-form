# Registration Form Application
![image](https://github.com/user-attachments/assets/b0a298ad-aae7-4269-8cab-271733b82bb4)

This is a simple registration form built using **Vite** and **React** with form handling and validation using **Formik** and **Yup**. The form includes fields for name, email, password, and confirm password. It provides feedback to the user for invalid inputs and disables the submit button until the form is filled correctly.

## Features

- User-friendly registration form
- Real-time form validation using **Formik** and **Yup**
- Displays error messages for invalid input
- Disables the submit button until all fields are valid and filled
- Shows a success message on successful form submission

## Technologies Used

- [Vite](https://vitejs.dev/) - Fast build tool for modern web applications
- [React](https://reactjs.org/) - JavaScript library for building user interfaces
- [Formik](https://formik.org/) - Form handling library for React
- [Yup](https://github.com/jquense/yup) - JavaScript schema validation for forms
- [Styled-components](https://styled-components.com/) - Styling React components
- [React-Toast](https://github.com/jossmac/react-toast) - Toast notifications

## Installation

Follow these steps to set up and run the project locally.

### Prerequisites

- **Node.js** installed on your system. You can download it from [Node.js](https://nodejs.org/).

### Steps

1. **Clone the repository**:
   ```bash
   git clone https://github.com/replyre/Formik-yup-react-form
   cd registration-form-app
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Start the development server**:
   ```bash
   npm run dev
   ```

4. **Open the app**:
   Open your browser and navigate to `http://localhost:5173` to see the registration form in action.


## Form Validation

The form validation is handled using **Formik** and **Yup**. Here's a quick summary of the fields:

- **Name**: Required
- **Email**: Must be a valid email format and is required
- **Password**: Minimum length of 6 characters and is required
- **Confirm Password**: Must match the password and is required

The form will disable the "Sign Up" button until all fields are correctly filled and there are no validation errors.

## How It Works

- As the user types into the form fields, **Formik** tracks the form state.
- **Yup** provides validation rules to check the user input.
- The submit button is disabled until all the fields are valid and modified.
- On successful submission, the form resets, and a success toast notification appears.
