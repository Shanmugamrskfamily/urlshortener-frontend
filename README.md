# URL Shortener Frontend

This project hosts the frontend codebase for a URL Shortener application.

## Description

The URL Shortener application aims to take long URLs and create shorter, more manageable links that direct to the original long URLs. The frontend provides user-friendly interfaces for user registration, login, URL shortening, a dashboard displaying URL statistics, and a list of shortened URLs.

## Technologies Used

- React.js
- React Router
- Chart.js
- Axios
- SweetAlert2

## Getting Started

### Prerequisites

Ensure you have the following installed before running the project:

- Node.js
- npm (Node Package Manager)

### Installation

1. Clone this repository.
2. Navigate to the project folder in your terminal.
3. Run `npm install` to install all dependencies.
4. Create a `.env` file and set the appropriate environment variables, such as the backend URL.
5. Run `npm start` to start the development server.

### Deployment

The frontend is deployed on Netlify and accessible at [URL Shortener Frontend on Netlify](https://url-shortner-rsk.netlify.app/).

## Structure

The frontend project structure is organized as follows:

- `public` contains the main HTML file, icons, and other static assets.
- `src` houses the application source code including components, styles, and other resources.

## Components

The application is divided into various components:

- `Main`: Navigation bar and basic layout for the app.
- `Signup`, `Login`: User registration and login components.
- `Shortener`: Allows users to shorten URLs.
- `Dashboard`: Displays statistics based on URL creation.
- `Urls`: Shows a list of all created URLs.
- `EmailVerify`, `ForgotPassword`, `PasswordReset`: Components for user account verification and password reset.

## Usage

The project has various functionalities accessible via the UI:

- **Signup and Login**: User authentication.
- **URL Shortening**: Convert long URLs into short, shareable links.
- **Dashboard**: Shows statistics based on the URLs created.
- **URL List**: Displays a list of all shortened URLs and their information.

## Contributing

Contributions are welcome! If you have suggestions or improvements, please open an issue or a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

---

For detailed information and further API endpoints, refer to the associated backend repository.

If you have any questions or need assistance, please feel free to contact the maintainers.
