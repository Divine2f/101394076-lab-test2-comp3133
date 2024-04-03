# Angular Space App
#### 101394076-lab-test2-comp3133

This Angular application provides an interface to view a list of SpaceX launches, allowing users to filter launches by year, and delve into detailed information about each mission.

## Application Features

- **Mission List**: Displays SpaceX launches in an informative list.
- **Launch Year Filter**: Users can filter the list of launches by year.
- **Mission Details**: Detailed information about each SpaceX mission is presented.
- **REST API Service**: Retrieves launch data from the SpaceX API.
- **Data Models**: Utilizes TypeScript interfaces or classes for structured data representation.
- **UI Design**: Employs Angular Material for an aesthetically pleasing user interface.

## Getting Started

### Prerequisites

You should have Node.js and Angular CLI installed on your system.

### Installation

1. Clone the repository:
git clone <GitHub_repository_link>

vbnet
Copy code
2. Navigate to the project's directory:
cd studentid-lab-test2-comp3133

markdown
Copy code
3. Install the required dependencies:
npm install

markdown
Copy code
4. Start the Angular application:
ng serve

markdown
Copy code
The application will be available at `http://localhost:4200`.

## Deployment

The application has been deployed and can be accessed at [Hosted_Application_URL].

## SpaceX API Integration

The following endpoints from the SpaceX API are integrated:
- All launches endpoint: `https://api.spacexdata.com/v3/launches`
- Filter launches by year endpoint: `https://api.spacexdata.com/v3/launches?launch_year={{year}}`
- Individual launch details endpoint: `https://api.spacexdata.com/v3/launches/{{flight_number}}`

Remember to replace `<GitHub_repository_link>` and `[Hosted_Application_URL]` with the actual links to your GitHub repository and the URL of the hosted application.

### Fork the Project
Create your Feature Branch (git checkout -b feature/AmazingFeature)
Commit your Changes (git commit -m 'Add some AmazingFeature')
Push to the Branch (git push origin feature/AmazingFeature)
Open a Pull Request

### License
Distributed under the MIT License. See LICENSE for more information.

### Acknowledgements
- Angular
- TypeScript

### Author
Divine Iyalla Falola
