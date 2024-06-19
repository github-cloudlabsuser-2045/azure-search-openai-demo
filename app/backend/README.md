# Backend Application

This directory contains the backend application for the ChatGPT + Enterprise data + document security project. It's built using Quart, a Python framework for asynchronous web applications, and integrates with Azure Cognitive Search and OpenAI for data retrieval and processing.

## Overview

The backend serves as the core logic layer, handling requests from the frontend, processing them with the help of Azure Cognitive Search and OpenAI, and returning the processed data back to the frontend. It supports document level access control, ensuring that data is only accessible to authorized users.

## Features

- **Document Level Access Control**: Integrates with Microsoft Entra ID Apps for authentication and authorization.
- **Data Retrieval and Processing**: Uses Azure Cognitive Search for data retrieval and OpenAI for natural language processing.
- **Asynchronous Web Application**: Built with Quart for efficient handling of asynchronous operations.

## Getting Started

To get started with the backend application, ensure you have Python 3.11 installed. Then, follow these steps:

1. Install dependencies:

```sh
pip install -r requirements-dev.txt
```

2. Set up environment variables as described in the Environment Variables Reference section of the main documentation.

3. Run the application:
```sh
quart run
```

## Customization
You can customize the backend to suit your needs. The primary code for customization is located in the approaches folder, which contains classes for different RAG (Retrieval Augmented Generation) approaches. For more details on customizing the backend, refer to the Customizing the backend section in the documentation.

## Testing
For testing the backend application, refer to the tests directory at the root of the project. Ensure you follow the best practices for testing asynchronous web applications.

## Contributing
Contributions are welcome! Please refer to the CONTRIBUTING.md file for more information on how to contribute to this project.



## License
This project is licensed under the terms of the MIT license. See LICENSE for more information. ```

