# Promptopia - Share AI Prompts

Welcome to Promptopia, a web application where users can share and explore AI prompts. Whether you're looking for inspiration or want to showcase your creative ideas, Promptopia is the perfect platform to connect with like-minded individuals and engage in collaborative brainstorming. This README.md file provides essential information about the application, its technologies, setup, and deployment.

## Table of Contents

- [Introduction](#promptopia---share-ai-prompts)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Configuration](#configuration)
- [Authentication](#authentication)
- [Database Setup](#database-setup)
- [Running the Application](#running-the-application)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)

## Features

Promptopia comes packed with a variety of features to create a seamless and enjoyable experience for users:

- **Prompt Submission**: Users can create and submit AI prompts to the platform.
- **Explore Prompts**: Users can browse and explore a diverse collection of AI prompts shared by others.
- **Search Functionality**: Easily search for specific prompts or topics of interest.
- **User Authentication**: Securely log in and register using Next Auth with Google.
- **User Profiles**: Users have personalized profiles to manage their submitted prompts.
- **Responsive Design**: The application is responsive and optimized for various devices.

## Technologies Used

The following technologies were used to build Promptopia:

- **ReactJS**: A JavaScript library for building user interfaces.
- **TailwindCSS**: A highly customizable CSS framework for modern web development.
- **NextJS**: A React framework for server-side rendering and static site generation.
- **MongoDB**: A NoSQL database for storing prompt data.
- **Next Auth by Google**: An authentication library for NextJS applications with Google OAuth integration.
- **Vercel**: A platform for deploying web applications.

## Getting Started

To run Promptopia locally, follow these steps:

### Prerequisites

- Node.js (at least version 12) and npm installed on your machine.
- A MongoDB instance or access to a MongoDB database (you can use a cloud-based service like MongoDB Atlas).

### Installation

1. Clone this repository to your local machine:

```bash
git clone https://github.com/your-username/promptopia.git
cd promptopia
```

2. Install the required dependencies:

```bash
npm install
```

## Configuration

Before running the application, you need to configure some environment variables. Create a new file `.env.local` in the root directory of the project and add the following variables:

```
MONGODB_URI=your-mongodb-connection-uri
GOOGLE_CLIENT_ID=your-google-client-id
GOOGLE_CLIENT_SECRET=your-google-client-secret
NEXTAUTH_URL=http://localhost:3000 (Update this URL for production)
```

Replace `your-mongodb-connection-uri` with your actual MongoDB connection URI. To obtain `your-google-client-id` and `your-google-client-secret`, you need to set up a project on the Google Developers Console and enable the Google OAuth API.

## Authentication

Promptopia uses Next Auth with Google for user authentication. Users can sign in using their Google accounts.

## Database Setup

Promptopia uses MongoDB to store prompt data. Make sure you have a MongoDB database set up and the connection URI configured in the `.env.local` file.

## Running the Application

To start the development server, run the following command:

```bash
npm run dev
```

The application will be accessible at `http://localhost:3000`.

## Deployment

Promptopia is ready to be deployed using Vercel. Make sure your GitHub repository is set up with the necessary credentials. Push your code to GitHub, and Vercel will handle the rest.

## Contributing

We welcome contributions from the community! If you'd like to contribute to Promptopia, please fork the repository, make your changes, and submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

---

We hope you enjoy using Promptopia! If you have any questions or encounter any issues, feel free to open an issue on the GitHub repository. Happy prompting!
