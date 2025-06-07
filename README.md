# Cloudflare Temp Mail 🌐✉️

![GitHub Repo Size](https://img.shields.io/github/repo-size/amad890/cloudflare-temp-mail)
![GitHub Stars](https://img.shields.io/github/stars/amad890/cloudflare-temp-mail)
![GitHub Forks](https://img.shields.io/github/forks/amad890/cloudflare-temp-mail)
![License](https://img.shields.io/github/license/amad890/cloudflare-temp-mail)

Welcome to **Cloudflare Temp Mail**! This project provides an API to create temporary email addresses using your own Cloudflare domain. With this tool, you can enhance your privacy and manage email routing efficiently.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Installation](#installation)
- [Contributing](#contributing)
- [License](#license)
- [Releases](#releases)

## Features

- **Custom Domain**: Use your own Cloudflare domain to generate temporary email addresses.
- **Easy Integration**: Simple REST API for seamless integration into your applications.
- **Privacy Focused**: Protect your personal email from spam and unwanted messages.
- **Docker Support**: Easily deploy the application using Docker.
- **Lightweight**: Built with Flask and Python, ensuring a fast and efficient service.

## Getting Started

To get started with Cloudflare Temp Mail, you can visit the [Releases](https://github.com/amad890/cloudflare-temp-mail/releases) section to download the latest version. Follow the instructions below to set up the project on your local machine.

## Usage

Once you have the API running, you can create temporary email addresses. The API allows you to manage these addresses effectively. You can retrieve, delete, and list emails using simple HTTP requests.

## API Endpoints

Here are the main API endpoints available in this project:

### Create Temporary Email

- **Endpoint**: `POST /api/create`
- **Description**: Creates a new temporary email address.
- **Parameters**:
  - `domain`: Your Cloudflare domain.
  
### Retrieve Emails

- **Endpoint**: `GET /api/emails`
- **Description**: Lists all emails associated with the temporary address.
  
### Delete Email

- **Endpoint**: `DELETE /api/delete`
- **Description**: Deletes a specific email address.
- **Parameters**:
  - `email`: The email address to delete.

## Installation

To install and run Cloudflare Temp Mail, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/amad890/cloudflare-temp-mail.git
   cd cloudflare-temp-mail
   ```

2. **Install Dependencies**:
   You can use pip to install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Application**:
   Start the Flask application:
   ```bash
   python app.py
   ```

4. **Using Docker**:
   Alternatively, you can run the application using Docker:
   ```bash
   docker build -t cloudflare-temp-mail .
   docker run -p 5000:5000 cloudflare-temp-mail
   ```

## Contributing

We welcome contributions! If you want to contribute to Cloudflare Temp Mail, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your branch to your fork.
5. Create a pull request.

Please ensure your code adheres to the project's coding standards and includes relevant tests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Releases

To get the latest version of Cloudflare Temp Mail, visit the [Releases](https://github.com/amad890/cloudflare-temp-mail/releases) section. Download the appropriate file and execute it to set up the application.

## Conclusion

Cloudflare Temp Mail offers a robust solution for generating temporary email addresses with your own domain. It emphasizes privacy and ease of use. We hope you find this project useful and welcome any feedback or contributions.

For any questions or issues, feel free to open an issue in the repository. Happy coding!