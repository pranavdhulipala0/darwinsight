# Darwinsight

## Introduction

Darwinsight is a powerful API Tracker designed to monitor and visualize various metrics, including performance, counts, search, and location data. Integrated seamlessly into developers' projects, Darwinsight facilitates data collection through API requests, providing valuable insights for informed decision-making. The platform features an intuitive dashboard accessible to registered users, allowing them to track and analyze key metrics effortlessly.

## Features:

- **Metric Tracking:** Darwinsight tracks a wide range of metrics, including performance, counts, search, and location data, providing developers with comprehensive insights into their API usage.

- **Visualization:** The platform offers interactive visualizations of tracked metrics through Google Charts, enhancing users' understanding and analysis of their data.

- **User Authentication:** Registered users can securely access the dashboard to view and analyze tracked metrics, ensuring data privacy and confidentiality.

- **Integration Support:** Darwinsight seamlessly integrates into developers' projects, allowing for easy implementation and data collection through API requests.

- **Admin Panel:** Authorized users can access the admin panel to perform administrative tasks, such as managing user accounts, monitoring system health, and configuring settings.

## Technologies & Frameworks Used:

- ReactJS
- Node.js
- Express.js
- MongoDB
- Tailwind CSS
- Flowbite
- Google Charts
- Reverse Geocoding API
- AWS EC2

## Code Usage

To run the Darwinsight application, follow these steps:

1. Clone the repository from GitHub:
    ```bash
    git clone <repository_url>
    ```

2. Navigate to the project directory:
    ```bash
    cd darwinsight
    ```

3. Install dependencies:
    ```bash
    npm install
    ```

4. Start the server:
    ```bash
    npm start
    ```

Alternatively, for development purposes, you can use nodemon for automatic server restart:
    ```bash
    npm run dev
    ```

**Note:** Ensure that MongoDB is installed and running locally or configure the connection string in the application settings.

## Deployment

Darwinsight can be deployed using AWS EC2 or any other suitable hosting provider. Follow these general steps for deployment:

- Set up an AWS EC2 instance.
- Clone the repository onto the EC2 instance.
- Install dependencies and start the server as outlined in the Code Usage section.
- Configure the necessary environment variables, such as database connection strings and API keys.
- Set up a domain name and configure DNS settings if required.
- Ensure security measures are in place, such as HTTPS encryption and proper access controls.
- Monitor the deployed application for performance and stability.

## Additional Notes

- The application utilizes Tailwind CSS and Flowbite for frontend styling, providing a modern and responsive user interface.
- Reverse Geocoding API is used for location data processing, enabling geospatial analysis and visualization.
- Continuous integration and testing processes can be implemented using GitHub Actions or other CI/CD tools to ensure code quality and reliability.
