# Build a Secure User Authentication System using Node.js 

This project provides a fully functional Login, Register, and Logout system built with Node.js. It aims to offer a secure and robust user authentication system that can be integrated into various web applications.It aims to offer a secure and robust user authentication system that can be integrated into various web applications.

## Features

- **User Registration**: Allows users to create a new account with a secure password.
- **User Login**: Enables users to log in to the application using their registered credentials.
- **User Logout**: Provides a secure way for users to log out of the application.
- **Password Encryption**: Ensures all user passwords are properly hashed and encrypted for security.
- **Session Management**: Utilizes Passport for managing user sessions.

## Getting Started

Follow these instructions to set up the project locally.

### Prerequisites

Ensure you have the following installed:

- [Node.js](https://nodejs.org/en/download/)
- [npm](https://www.npmjs.com/get-npm)

### Configuration

1. Download or clone the repository to your local machine.
2. Navigate to the project directory:

    ```bash
    cd user-authentication-system
    ```

3. Install the dependencies:

    ```bash
    npm install
    ```

4. Create a `.env` file in the root directory of the project and add the following environment variables:

    ```bash
    PORT=3000
    SESSION_SECRET=your_secret_key
    ```

    Make sure to replace `your_secret_key` with a strong secret key for session management.

### Running the Application

1. Start the application:

    ```bash
    npm start
    ```

2. Open your browser and navigate to `http://localhost:3000`.

## Usage

- **Register**: Visit `/register` to create a new account.
- **Login**: Visit `/login` to log in with your credentials.
- **Logout**: Click the logout button to end the session.

## Security Considerations

- All passwords are hashed using [bcryptjs](https://www.npmjs.com/package/bcryptjs) to ensure they are stored securely.
- Sessions are managed using secure cookies to prevent unauthorized access.

## Documentation

For further details on the technologies used in this project, refer to the following documentation:

- [Node.js Documentation](https://nodejs.org/en/docs/)
- [Express Documentation](https://expressjs.com/)
- [Passport Documentation](http://www.passportjs.org/docs/)
- [bcryptjs Documentation](https://www.npmjs.com/package/bcryptjs)
- [express-session Documentation](https://www.npmjs.com/package/express-session)
- [express-validator Documentation](https://express-validator.github.io/docs/)
- [MySQL Documentation](https://dev.mysql.com/doc/)
