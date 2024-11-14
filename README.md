# ProjectVerse - A Platform for Uploading and Selling Projects

Welcome to **ProjectVerse**! This platform allows developers, tech enthusiasts, and entrepreneurs to upload, showcase, and sell their projects. Whether you're building an innovative new tool or a personal project, ProjectVerse offers a simple way to showcase your work and potentially monetize it. With an easy-to-use interface and built-in payment integration, ProjectVerse aims to connect creators with buyers in a seamless, efficient way.

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

**ProjectVerse** is a web platform built with **React.js** and **Node.js**. It enables users to upload their projects, list them for sale, and handle transactions securely. Buyers can browse through the projects, make payments using **Razorpay**, and get access to the content immediately after purchase. The platform provides a simple search functionality, pagination, and a clean interface for both sellers and buyers.

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
