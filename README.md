# Vehicle Scenario Management System

This is a React application for managing vehicle scenarios. It allows users to add, edit, and delete scenarios and vehicles, and view all scenarios.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup and Installation](#setup-and-installation)
- [Running the Application](#running-the-application)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- Add, edit, and delete scenarios.
- Add vehicles to scenarios.
- Edit and delete vehicles.
- View all scenarios and their details.

## Technologies Used

- **Frontend**: React, Semantic UI, Framer Motion
- **Routing**: React Router
- **HTTP Client**: Axios
- **Notifications**: React Toastify
- **Forms**: React Hook Form
- **Icons**: React Icons

## Setup and Installation

### Prerequisites

- Node.js and npm installed on your machine.

### Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/jithendhar1435/vehicle-scenario.git
   cd vehicle-scenario-management



# install dependencies:
-npm start

# running the application
-npm start
-the application will start on http://localhost:3000.



# project structure

vehicle-scenario-management/
├── public/
│   ├── index.html
│   └── ...
├── src/
│   ├── components/
│   │   ├── AddScenarioForm.js
│   │   ├── AddVehiclesForm.js
│   │   ├── AllScenarios.js
│   │   ├── DeleteAlert.js
│   │   ├── Home.js
│   │   ├── Navbar.js
│   │   ├── ScenarioEditBody.js
│   │   ├── ScenarioItem.js
│   │   ├── VehicleEditBody.js
│   │   ├── VehicleItem.js
│   │   └── ...
│   ├── contexts/
│   │   └── ActivePageProvider.js
│   ├── App.css
│   ├── App.js
│   ├── index.js
│   └── ...
├── .env
├── package.json
├── README.md
└── ...


Usage
Adding a Scenario
Navigate to the "Add Scenario" page by clicking on "New Scenario" in the navbar.
Fill in the scenario details and click "Save".
Viewing All Scenarios
Go to the "All Scenarios" page to see a list of all scenarios. You can edit or delete scenarios from this page.
Adding Vehicles to a Scenario
From the "All Scenarios" page, click the "Add Vehicles" button next to the desired scenario.
Fill in the vehicle details and click "Save".
Editing or Deleting Vehicles
Edit or delete vehicles directly from the scenario view by clicking the respective icons next to each vehicle.
Contributing
Contributions are welcome! Please follow these steps to contribute:

Fork the repository.
Create a new branch (git checkout -b feature-branch).
Make your changes.
Commit your changes (git commit -m 'Add new feature').
Push to the branch (git push origin feature-branch).
Open a pull request.

