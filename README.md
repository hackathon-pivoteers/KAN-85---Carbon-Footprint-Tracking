```mermaid
graph LR

A(User) -- Inputs carbon data --> B(Front-end) 
B -- Sends data to server --> C(Server)
C -- Processes data and stores in database --> D(Database)
D -- Retrieves data and sends to client --> C
C -- Sends data to front-end --> B
B -- Displays carbon data to user --> A
```
# Carbon Footprint Tracking System

This repository contains the code for developing a comprehensive Carbon Footprint Tracking system. The goal of this project is to measure, monitor, and manage the environmental impact of the organization's operations, products, and services.

## Table of Contents

- [Project Description](#project-description)
- [Installation and Running](#installation-and-running)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)

## Project Description

The objective of this project is to develop a comprehensive Carbon Footprint Tracking system that enables the organization to measure, monitor, and manage their environmental impact. The key features of this system include:

### Data Collection and Integration

- Collects data on energy consumption, transportation, waste generation, and other relevant activities.
- Integrates with IoT devices, energy meters, and external databases for automated data collection.

### Emission Factors Database

- Builds a database of emission factors specific to different industries and activities.

### Carbon Calculation Engine

- Develops a robust calculation engine to quantify carbon emissions based on collected data and emission factors.

### Real-time Monitoring and Alerts

- Implements real-time monitoring features to track carbon emissions continuously.
- Sets up alerts for stakeholders to receive instant feedback on significant emission events.

### Mobile Application

- Develops a mobile application to provide on-the-go access to carbon footprint data and insights.

## Installation and Running

To install and run the Carbon Footprint Tracking system, follow the below steps:

1. Clone the repository:

    ```
    git clone https://github.com/your-username/carbon-footprint-tracking.git
    ```

2. Install the required dependencies:

    ```
    npm install
    ```

3. Set up the necessary configuration files, including API keys and database credentials.

4. Run the application:

    ```
    npm start
    ```

## Usage

To utilize the Carbon Footprint Tracking system, follow the instructions below:

1. Ensure that the system is properly installed and running (refer to the [Installation and Running](#installation-and-running) section).
2. Access the web application or mobile application.
3. Sign in using your credentials or create a new account.
4. Begin inputting relevant data on energy consumption, transportation, waste generation, etc.
5. Explore the dashboard and visualizations to gain insights into your carbon footprint.
6. Utilize the benchmarking and goal-setting features to set targets and track progress.
7. Receive real-time alerts and notifications for significant emission events.

## Credits

This project was developed by the following team members:

- John Doe - [GitHub](https://github.com/johndoe) - [LinkedIn](https://www.linkedin.com/in/johndoe)
- Jane Smith - [GitHub](https://github.com/janesmith) - [LinkedIn](https://www.linkedin.com/in/janesmith)

We would like to acknowledge the following resources that helped us during the development of this project:

- [Resource 1](https://www.example.com)
- [Resource 2](https://www.example.com)

## License

This project is licensed under the [MIT License](LICENSE.txt). Please see the [License File](LICENSE.txt) for more information.

For any questions or inquiries, please contact [team@carbonfootprinttracking.com](mailto:team@carbonfootprinttracking.com). 

## JIRA KAN-86 Update
<p><strong>Carbon Footprint Calculation Engine:</strong></p>
<p><strong>Objective:</strong> Develop a robust engine to accurately calculate carbon emissions based on input data and emission factors.</p>
<p><strong>Code Implementation:</strong></p>
<ol>
<li><strong>Algorithm Design:</strong> Design precise algorithms for carbon emission calculations considering energy consumption, transportation, and waste generation.</li>
<li><strong>Emission Factors Database Integration:</strong> Integrate the engine with the Emission Factors Database to retrieve relevant factors for different activities.</li>
<li><strong>Data Input Processing:</strong> Implement mechanisms to process and validate input data from various sources, accounting for missing or inaccurate data.</li>
<li><strong>Calculation Logic Implementation:</strong> Implement core logic using separate functions to calculate emissions based on energy consumption, transportation, and waste generation.</li>
</ol>
<p><strong>Stakeholders:</strong></p>
<table>
<thead>
<tr>
<th style="text-align:center">Stakeholder</th>
<th style="text-align:center">Role/Responsibility</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">Ioana</td>
<td style="text-align:center">Engine Developer</td>
</tr>
<tr>
<td style="text-align:center">Hakan</td>
<td style="text-align:center">Emission Factors Database Manager</td>
</tr>
<tr>
<td style="text-align:center">Pavel</td>
<td style="text-align:center">Country Director</td>
</tr>
</tbody>
</table>
<p><strong>Conclusion:</strong> The Carbon Footprint Calculation Engine enables accurate quantification of carbon emissions by utilizing algorithms, data processing, database integration, and calculation logic. The involvement of stakeholders such as Ioana, Hakan, and Pavel contributes to the successful development and implementation of the engine.</p> 

## JIRA KAN-86 Update
<h2>Carbon Emissions Calculation Engine</h2>
<p>The Carbon Emissions Calculation Engine is a robust feature within the Carbon Footprint Tracking system. It enables the quantification of carbon emissions based on collected data and emission factors. The following sub-tasks were completed:</p>
<ul>
<li>Algorithm Design: Designed algorithms to calculate carbon emissions considering factors such as energy consumption, transportation, and waste generation</li>
<li>Emission Factors Database Integration: Integrated the calculation engine with the Emission Factors Database to retrieve relevant emission factors</li>
<li>Data Input Processing: Implemented mechanisms to process and validate data inputs from multiple sources, addressing missing or inaccurate data through error-handling mechanisms</li>
<li>Calculation Logic Implementation: Developed the core logic for accurately and reliably calculating carbon emissions based on the algorithms and input data, along with thorough testing</li>
</ul>
<p>Hakan is a developer.</p>