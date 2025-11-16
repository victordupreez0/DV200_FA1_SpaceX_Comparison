
<div align="center">
  
# SpaceX Launch Tracker

> A React-powered data visualization platform for exploring SpaceX launch history, rocket specifications, and payload information using the SpaceX REST API.

**Repository:** [formative_one_spacex](https://github.com/victordupreez0/formative_one_spacex)

![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=for-the-badge&logo=chartdotjs&logoColor=white)

</div>

---

## Table of Contents

- [About the Project](#about-the-project)
  - [Project Description](#project-description)
  - [Built With](#built-with)
  - [API Documentation](#api-documentation)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [How to Install](#how-to-install)
- [Features and Functionality](#features-and-functionality)
- [Concept Process](#concept-process)
  - [Ideation](#ideation)
  - [Wireframes](#wireframes)
- [Development Process](#development-process)
  - [Implementation Process](#implementation-process)
  - [Highlights](#highlights)
  - [Challenges](#challenges)
- [Reviews and Testing](#reviews-and-testing)
  - [Feedback from Reviews](#feedback-from-reviews)
  - [Unit Tests](#unit-tests)
- [Future Implementation](#future-implementation)
- [Final Outcome](#final-outcome)
  - [Video Demonstration](#video-demonstration)
- [Conclusion](#conclusion)
- [Contributing](#contributing)
- [Contact](#contact)
- [Acknowledgements](#acknowledgements)

---

## About the Project

### Project Description

SpaceX Launch Tracker is a comprehensive React application that leverages the SpaceX REST API (by jackwmeyer) to provide an interactive exploration of SpaceX's launch history. The platform enables users to browse launch data, compare rocket specifications and payload information, and visualize trends through dynamic charts and timelines. Built with modern web technologies, it offers an engaging way to explore SpaceX's achievements through multiple data endpoints including launch details, rocket specifications, payload information, and historical trends.

### Built With

* ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) - Component-based UI library
* ![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=flat-square&logo=javascript&logoColor=F7DF1E) - Core programming language
* ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white) - JavaScript runtime
* ![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=flat-square&logo=chartdotjs&logoColor=white) - Data visualization library

### API Documentation

This project uses the SpaceX REST API: [SpaceX API Documentation](https://github.com/r-spacex/SpaceX-API)

---

## Getting Started

The following instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Ensure that you have the latest version of Node.js installed on your machine.
```bash
node --version  # v14.0.0 or higher
npm --version   # v6.0.0 or higher
```

### How to Install

#### Clone Repository

Run the following in the command-line to clone the project:
```bash
git clone https://github.com/victordupreez0/formative_one_spacex.git
cd formative_one_spacex
```

#### Install Dependencies

Run the following in the command-line to install all the required dependencies:
```bash
npm install
```

#### Start the Development Server

Run the application:
```bash
npm start
```

#### Access the Application

Open your browser and navigate to: `http://localhost:3000`

---

## Features and Functionality

### Home Page

<div align="center">
  <img src="path/to/home-page-screenshot.png" alt="Home Page" width="70%" />
</div>

* **API Dataset Showcase** - Browse comprehensive SpaceX launch data
* **Recent Launches** - View the most recent SpaceX missions
* **Search Functionality** - Find specific launches using advanced search
* **Featured Launch Section** - Highlighted mission with detailed information and imagery

### Compare Page

<div align="center">
  <img src="path/to/compare-page-screenshot.png" alt="Compare Page" width="70%" />
</div>

* **Payload Theoretical Data** - Compare payload capacity and theoretical specifications
* **Payload Orbital Data** - Analyze orbital parameters across different missions
* **Rocket Data Comparison** - Side-by-side rocket specification analysis

### Timeline Page

<div align="center">
  <img src="path/to/timeline-page-screenshot.png" alt="Timeline Page" width="70%" />
</div>

* **Launches Over Time** - Visualize launch frequency trends
* **Payloads Launched** - Track payload deployment history
* **Launch Success Rate** - Chart success rates over time
* **Core Reusability** - Monitor rocket core reuse statistics

---

## Concept Process

### Ideation

The concept for SpaceX Launch Tracker originated from the desire to create an interactive and visually engaging way to explore SpaceX's launch data. The goal was to transform raw API data into meaningful insights through comparison tools and timeline visualizations, making complex aerospace information accessible to enthusiasts and researchers alike.

### Wireframes

![Wireframes](https://github.com/victordupreez0/formative_one_spacex/blob/main/documentation/Wireframes/Wireframes.png)

The wireframing process focused on creating three distinct page layouts: a data-rich home page for browsing launches, a comparison interface for analyzing specifications, and a timeline view for visualizing trends. The design prioritized clear data presentation and intuitive navigation between different views.

---

## Development Process

The Development Process outlines the technical implementations and functionality developed for the application.

### Implementation Process

* **React Component Architecture** - Built modular, reusable components for launches, rockets, and payloads with proper state management
* **API Integration** - Integrated multiple SpaceX API endpoints using fetch with async/await patterns for data retrieval
* **Chart.js Visualization** - Implemented interactive charts and graphs to visualize launch trends, success rates, and payload data
* **Search Functionality** - Developed search system using POST method for filtering and querying launch data
* **Responsive Design** - Created mobile-friendly layouts that adapt across different screen sizes
* **Featured Launch Section** - Designed spotlight component showcasing mission details with high-quality imagery

### Highlights

* **Featured Launch Section** - The standout feature on the home page that beautifully showcases mission details with compelling imagery and comprehensive information
* **Visual Design** - The overall aesthetic and imagery throughout the application creates an immersive space exploration experience
* **Data Visualization** - Chart.js integration provides clear and interactive ways to understand SpaceX's launch history
* **Comparison Tools** - The ability to compare rockets and payloads side-by-side offers valuable insights for users
* **Clean UI/UX** - Intuitive navigation and organized data presentation makes complex information accessible

### Challenges

* **React Learning Curve** - As the first React project, understanding component lifecycle, state management, and hooks required significant learning and experimentation
* **Search Implementation** - Implementing search functionality proved challenging with the GET method. While it works perfectly with POST, future iterations should explore more advanced GET-based search methods
* **API Rate Limiting** - Managing multiple API calls efficiently without hitting rate limits required careful optimization
* **Chart Configuration** - Configuring Chart.js with the right data structures and visualization options took several iterations
* **Data Transformation** - Converting raw API responses into formats suitable for comparison and timeline views required complex data manipulation

---

## Reviews and Testing

### Feedback from Reviews

Peer Reviews were conducted by fellow students and the lecturer. The following feedback was found useful:

* **Enhanced Navigation** - Suggested adding breadcrumbs or a clearer navigation system between pages
* **Loading States** - Recommended implementing loading indicators when fetching data from the API
* **Error Handling** - Feedback on improving user experience when API calls fail or data is unavailable
* **Mobile Optimization** - Suggestions for better mobile responsiveness, particularly for comparison charts
* **Additional Filters** - Users wanted more filtering options beyond basic search

### Unit Tests

Unit Tests were conducted to establish working functionality. Here are all the tests that were run:

* **API Connection** - Testing successful connection to SpaceX API endpoints and handling response data
* **Component Rendering** - Testing that all React components render correctly with various data inputs
* **Search Functionality** - Testing search queries with different parameters and validating results
* **Chart Generation** - Testing Chart.js implementation with different data sets and configurations
* **Navigation Flow** - Testing routing between pages and proper state preservation
* **Error Scenarios** - Testing application behavior with invalid data, failed API calls, and edge cases

---

## Future Implementation

* **Real-time Updates** - Implement WebSocket connection for live launch tracking and countdowns
* **Advanced Filtering** - Add comprehensive filtering by rocket type, launch site, mission outcome, and date ranges
* **User Favorites** - Allow users to save and track specific launches or rockets
* **3D Visualizations** - Integrate Three.js for 3D rocket models and orbital path visualizations
* **Launch Predictions** - Add upcoming launch schedule with countdown timers
* **Comparison Export** - Enable exporting comparison data and charts as PDF or image files
* **GET Method Search** - Implement advanced search functionality using GET requests
* **Social Sharing** - Add ability to share interesting launches and comparisons on social media
* **Dark Mode** - Implement theme toggle for better viewing experience

---

## Final Outcome

### Mockups

<img width="1000" height="1000" alt="Image" src="https://github.com/user-attachments/assets/cbca480f-7af9-4e7c-97c9-5d4b01bd2aaa" />

<img width="1000" height="1000" alt="Image" src="https://github.com/user-attachments/assets/f1234702-6852-4472-96ef-1d8f21b829f2" />

### Video Demonstration

To see a run through of the application, click below:

[View Demonstration](https://drive.google.com/file/d/10c54lFJmnr71fEkgjyU9WEEk7oaRrIhF/view?usp=sharing)

## Conclusion

SpaceX Launch Tracker successfully transforms complex aerospace data into an accessible and engaging user experience. The application demonstrates the power of React for building data-driven interfaces while leveraging the comprehensive SpaceX REST API. Through interactive comparisons, timeline visualizations, and a featured launch showcase, users can explore SpaceX's achievements in an intuitive and visually appealing way. This project served as an excellent introduction to React development, API integration, and data visualization techniques.

---

## Contributing

Contributions are what makes the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## Authors

**Victor du Preez** - [victordupreez0](https://github.com/victordupreez0)

---

## Contact

**Victor du Preez**
* Email: victor.dupreez0@gmail.com
* GitHub: [@victordupreez0](https://github.com/victordupreez0)
* Project Link: [https://github.com/victordupreez0/formative_one_spacex](https://github.com/victordupreez0/formative_one_spacex)

---

## Acknowledgements

* [SpaceX REST API by r-spacex](https://github.com/r-spacex/SpaceX-API)
* [React Documentation](https://react.dev/)
* [Chart.js Documentation](https://www.chartjs.org/)
* [Node.js Documentation](https://nodejs.org/)
* [SpaceX](https://www.spacex.com/) - For making space exploration exciting and accessible
