# Integration Flow Creator - Frontend

Welcome to the frontend repository of the Integration Flow Creator web application. This project is part of a comprehensive solution that enables users to create integration flows with ease.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The Integration Flow Creator frontend is designed to provide a user-friendly interface for creating and managing integration flows. Users can define source and destination systems, and configure the flow of data between them. This repository contains the code for the frontend part of the application.

## Features

- User Authentication: Secure user registration and login using ASP.NET Core Identity.
- Integration Flow Creation: Users can easily create integration flows with source and destination systems.
- File Handling: Integration with Azure Blob Storage for handling file uploads.
- Workflow Orchestration: Backend integration with Durable Functions for orchestrating integration flows.
- User-Friendly Interface: A responsive and intuitive UI for creating and managing integration flows.

## Tech Stack

- **Frontend**: ASP.NET Core Razor Pages or ASP.NET Core MVC for the user interface.
- **Backend**: ASP.NET Core for the backend, Durable Functions for workflow orchestration.
- **Database**: Entity Framework Core for data access.
- **Authentication**: ASP.NET Core Identity for user authentication.
- **File Handling**: Azure SDK for .NET for handling file uploads and storage.

## Getting Started

To set up and run the frontend project locally, follow these steps:

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/venkymanda/Integration-Flow-Creator-FrontEnd.git

2. Open the project in Visual Studio.

3. Ensure you have the necessary dependencies installed.

4. Configure the connection to the backend server and Azure Blob Storage in the app settings.

5. Build and run the project.

## Usage

 - Register or log in as a user.

 - Use the user-friendly interface to create and manage integration flows.

 - Follow the provided step-by-step guide for creating integration flows.

 - Test and validate your integration flows.


## Contributing

We welcome contributions from the community. If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.

2. Create a new branch for your feature or bug fix: git checkout -b feature/your-feature-name.

3. Make your changes and commit them: git commit -m 'Your commit message'.

4. Push your changes to your fork: git push origin feature/your-feature-name.

5. Create a pull request against the main repository.

6. Our team will review your contribution and provide feedback.

7. Once your pull request is approved, it will be merged into the main project.

## License
This project is licensed under the MIT License.