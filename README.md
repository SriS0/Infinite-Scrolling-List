
<img src="https://mooditude.app/wp-content/uploads/2022/01/aimless-scrolling.jpeg" alt="Alt text" title="Optional title" height="500" width="900">

# Infinite Scrolling Contact List
This is a web application built using React that displays an infinite scrolling list of contacts. The contacts are loaded dynamically from an external API as the user scrolls down the list.

## Table of Contents

- [Infinite Scrolling Contact List](#infinite-scrolling-contact-list)
  - [Table of Contents](#table-of-contents)
  - [Installation](#installation)
  - [Features](#features)
  - [Functionality](#functionality)
  - [Contributing](#contributing)
  - [Dependencies](#dependencies)
  - [Documentation](#documentation)
  - [Tech Stack](#tech-stack)
  - [API Reference](#api-reference)
  - [License](#license)
  - [Badges](#badges)

## Installation
To get started with the Project, you'll need to have Node.js installed on your machine. Once you have those installed, follow these steps:
```bash
1. Clone the repository to your local machine: git clone https://github.com/your-username/infinite-scrolling-contact-list.git
2. Navigate to the project directory: cd infinite-scrolling-contact-list
3. Install the required dependencies: npm install
4. Start the development server: npm start
5. Open a web browser and go to http://localhost:3000 to view the application.rt
```
## Features

The following features are available in the API:

- Infinite scrolling: contacts are loaded as the user scrolls down the list
- Responsive design: the application is optimized for desktop and mobile devices

## Functionality
The Contact List App has the following requirements:
``` bash
1. The app requires users to log in with fake credentials (username: foo, password: bar) before accessing the main list of contacts.
2. The app checks the username and password entered by the user, and if they match the expected values, the user is granted access to the main list of contacts.
3. After successful login, users will be redirected to the '/home' route where the main list of contacts will be displayed. 
4. The list of contacts displays user profiles, each with their photo and other relevant details, such as their name, email address, phone number, and location.
5. The list of contacts is sourced from a free random user API. 
6. The app uses the API to load a partial list of contacts initially, and as the user scrolls to the end of the list, it will show loading feedback and load more contacts after a delay of 1 second. The app implements infinite scrolling to provide a smooth user experience.
7. The app will display a logout button on all logged in pages. Clicking on this button will log the user out of their account and redirect them to the login page.
```
## Contributing

Contributions are welcome! To contribute to the project, follow these steps:
```bash
1. Fork the repository and create a new branch for your changes.
2. Make your changes and test them locally.
3. Create a pull request with a description of your changes.
4. Wait for a code review and approval before merging.
```
**Note**: Please ensure that your code adheres to the existing style and passes the unit tests before submitting a pull request.

## Dependencies
The following dependencies are required to run the Infinite-Scrolling-List:

```bash
    "bootstrap": "^5.2.3",
    "react": "^18.2.0",
    "react-bootstrap": "^2.7.2",
    "react-dom": "^18.2.0",
    "react-icons": "^4.7.1",
    "react-loading-skeleton": "^3.1.1",
    "react-router-dom": "^6.0.2",
```

## Documentation
This are the Documentation for all dependencies for your references:
- [React Documentation](https://reactjs.org/docs/getting-started.html)
- [React-bootstrap](https://react-bootstrap.github.io/)
- [React-dom](https://reactjs.org/docs/react-dom.html)
- [React-icons](https://react-icons.github.io/react-icons/)
- [React-loading-skeleton](https://github.com/dvtng/react-loading-skeleton)
- [React-router-dom](https://reactrouter.com/docs)

## Tech Stack
The application was built using the following technologies:
```bash
1. React: A JavaScript library for building user interfaces. React is used to create reusable UI components that can be combined to create complex web applications.

2. React Bootstrap: A popular CSS framework that provides pre-built UI components for use in React applications. React Bootstrap is used to style the contact list and make it look great on any device.

3. React Router: A routing library for React applications. React Router is used to manage the navigation between different views in the application.

4. React Icons: A collection of popular icons for use in React applications. React Icons is used to display icons in the search and sorting buttons.

5. React Loading Skeleton: A library for displaying loading indicators in React applications. React Loading Skeleton is used to display a loading indicator while the contact list is being fetched from the API.
```

## API Reference
The application uses the Random User API to fetch contact data. This API generates random user data, including names, email addresses, and profile pictures. The application makes API requests to this service as the user scrolls down the contact list, allowing it to display an unlimited number of contacts without performance issues.

## License
- [MIT](https://choosealicense.com/licenses/mit/)

## Badges
[![React](https://img.shields.io/badge/React-17.0.2-blue)](https://reactjs.org/)

[![React Router](https://img.shields.io/badge/React_Router-5.2.0-green)](https://reactrouter.com/)

[![React Bootstrap](https://img.shields.io/npm/v/react-bootstrap.svg)](https://www.npmjs.com/package/react-bootstrap)

[![React Loading Skeleton](https://img.shields.io/npm/v/react-loading-skeleton.svg)](https://www.npmjs.com/package/react-loading-skeleton)

[![React Icons](https://img.shields.io/npm/v/react-icons.svg)](https://www.npmjs.com/package/react-icons)
