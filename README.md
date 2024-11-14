# ProjectVerse - A Platform for Projects and Hiring Developers

**ProjectVerse** is a versatile online platform where users can browse and find paid and unpaid projects, as well as hire developers for custom project development and software solutions. It aims to connect project seekers and developers in a seamless way, enabling collaboration, knowledge sharing, and growth. Whether you're looking for ready-made projects or seeking a developer to build a new one, **ProjectVerse** provides an all-in-one platform to meet your needs.

## Table of Contents
1. [Project Description](#project-description)
2. [Features](#features)
3. [Tech Stack](#tech-stack)
4. [Installation](#installation)
5. [Frontend Setup](#frontend-setup)
6. [Backend Setup](#backend-setup)
7. [Usage](#usage)
8. [Contributing](#contributing)
9. [License](#license)
10. [Acknowledgements](#acknowledgements)

## Project Description

**ProjectVerse** is an online platform that bridges the gap between developers and businesses. It allows users to:
- Find **paid projects** that they can work on and earn from.
- Browse through **unpaid projects** to contribute to and gain experience.
- Hire **freelance developers** for custom project work and software solutions.

The platform enables a smooth browsing experience for both clients looking to hire developers and developers seeking new challenges. Buyers can pay for projects through a secure payment gateway, and developers can list their services to work on customized solutions.

### Features
- **User Authentication**: Secure login and registration using Firebase Authentication.
- **Search Functionality**: Easy-to-use search bar for filtering projects based on name or description.
- **Project Listings**: Creators can upload and list their projects with descriptions, images, and prices.
- **Payment Integration**: Seamless integration with Razorpay for processing payments.
- **Pagination**: Pagination functionality for browsing multiple projects efficiently.
- **Responsive Design**: The site is fully responsive and works well on all screen sizes.
- **More Details Button**: A feature under development to provide further details about projects.
- **Toast Notifications**: Informative pop-ups to alert users about actions like payment status or errors.

---

## Tech Stack

The tech stack used in this project includes:

- **Frontend**:
  - React.js
  - Tailwind CSS
  - Firebase (for user authentication)
  - React Icons (for UI icons like the search icon)
  - Axios (for API requests)

- **Backend**:
  - Node.js
  - Express.js
  - Razorpay API (for payment integration)
  - Firebase (for storing project data and user authentication)

---

## Installation

To set up this project locally, you will need to install both the **frontend** and **backend** repositories. The instructions below will guide you through the installation and setup process.

### Prerequisites
- Node.js (v14 or above) installed on your machine.
- Git (for cloning the repository).

### Clone the Repository

First, clone the main repository (which contains both the frontend and backend) to your local machine.

```bash
git clone https://github.com/your-username/ProjectVerse.git
cd ProjectVerse
```

## Frontend Setup

1. Navigate to the frontend folder

After cloning the repository, navigate to the frontend folder:

```bash
cd frontend
```

2. Install Dependencies

Install the required dependencies using npm or yarn.

```bash
npm install
```

Or, if you’re using yarn:

```bash
yarn install
```

3. Run the Frontend

To start the development server and run the frontend:

```bash
npm start
```

This will run the frontend application at http://localhost:3000.

## Backend Setup

1. Navigate to the backend folder

After setting up the frontend, navigate to the backend folder:

```bash
cd ../backend
```

2. Install Dependencies

Install the required dependencies for the backend:

```bash
npm install
```

3. Set Up Environment Variables

Before running the backend, make sure to set up the required environment variables. Create a .env file in the backend directory and configure the necessary environment variables like:

```bash
RAZORPAY_API_KEY=your-razorpay-api-key
RAZORPAY_SECRET_KEY=your-razorpay-secret-key
FIREBASE_API_KEY=your-firebase-api-key
FIREBASE_AUTH_DOMAIN=your-firebase-auth-domain
FIREBASE_PROJECT_ID=your-firebase-project-id
```

4. Run the Backend

To start the backend server:

```bash
npm start
```

This will run the backend server at http://localhost:5001.

## Usage

1. Creating an Account: Users can sign up using their email and password via Firebase Authentication.
2. Upload Projects: Creators can upload new projects through the admin dashboard.
3. Browsing Projects: Buyers can search and filter through a list of available projects.
4. Purchasing Projects: Buyers can securely purchase a project using Razorpay, and they will receive access to the project after the payment is processed.

## Contributing

We welcome contributions to improve ProjectVerse! Here’s how you can contribute:

1. Fork the Repository: Click the “Fork” button on the repository page.
2. Clone Your Fork: Clone your fork to your local machine.
3. Create a New Branch: Create a new branch for your feature or bug fix.
4.	Make Changes: Implement your changes and test them.
5.	Commit Changes: Commit your changes with a meaningful commit message.

```bash
git commit -m "Implemented feature XYZ"
```

6. Push to GitHub: Push your branch to your forked repository.

```bash
git push origin feature/your-feature
```

	7.	Create a Pull Request: Go to the original repository and open a pull request to merge your changes.

Please ensure that your code adheres to the project’s coding style and includes appropriate tests where necessary.

## Acknowledgements

- Razorpay: Payment gateway for secure transactions.
- Firebase: Used for authentication and project data storage.
- React.js: JavaScript library for building the user interface.
- Tailwind CSS: Utility-first CSS framework used for styling.
