# Car Analytics

## Table of Contents

- [About The Project](#about-the-project)  
- [Built With](#built-with)   
- [Usage](#usage)  
- [Demo](#demo)     
- [Team members](#team-members)   


## About The Project

This **Car Analytics Dashboard** project is designed to help market owners manage and analyze car data efficiently. It provides an intuitive interface for displaying car information, allowing users to interact with data through dynamic charts, tables, and dropdowns. 

The key features of this project include:

- **Data Visualization**: Easily view and interpret car data with interactive Pie Charts and Stacked Bar Charts.
- **User-Friendly Interface**: Built with React.js and Bootstrap for a responsive and modern design.
- **Efficient Data Management**: Use of local storage to persist user data and preferences.
- **Interactive Filtering**: Dynamic dropdowns and search functionality for a seamless user experience.
- **Highlight Feature**: Users have the flexibility to easily add or remove cars from their highlighted list, allowing for a customized and focused view of specific cars of interest.

The goal of this project is to provide an effective tool for car data analysis and management, making it easier for market owners.


## Built With

This project is built with the following technologies:

- [![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
- [![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white)](https://reactrouter.com/)
- [![Chart.js](https://img.shields.io/badge/Chart.js-F5788D?style=for-the-badge&logo=chart.js&logoColor=white)](https://www.chartjs.org/) 
- [![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)](https://getbootstrap.com/) 
- [![PrimeReact](https://img.shields.io/badge/PrimeReact-0C4CCF?style=for-the-badge&logo=primereact&logoColor=white)](https://www.primereact.org/) 
- [![Local Storage](https://img.shields.io/badge/Local%20Storage-4AB197?style=for-the-badge)](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage)


## Usage

To use the **Car Analytics Dashboard** application, follow these steps:

1. **Clone the Repository**:
   Start by cloning the repository to your local machine using the following command:

   ```bash
   git clone https://github.com/LwinTharaphi/CarAnalytics.git
   ```
   Go to the project repository
   ```bash
   cd CarAnalytics
   ```
   Install Dependencies
   ```bash
   pnpm install
   npm install chart.js
   npm install react-bootstrap bootstrap
   npm install primereact
   npm install react-router-dom
   ```
   Run Locally
   ```bash
   pnpm run dev
   ```
   Build Production
   ```bash
   pnpm run build
   ```



## Demo

Here are some screenshots showcasing the **Car Analytics Dashboard** application:

### Dashboard View
- [Table](#table)  
- [Pie chart](#pie)   
- [Bar chart](#bar) 

This screenshot displays the main dashboard, including various charts and data visualizations.<br/>

There is a drop-down menu where users can select the model of each respective car brand. The car price and number of cars available will dynamically change based on the selected model. Additionally, there is a clickable button that allows users to view and add the selected car to their highlighted page.

## ![Table](https://i.ibb.co/hWrbL8H/dashboard-table.png)

This is the Pie chart on the dashboard.

## ![Pie](https://i.ibb.co/VVJcCt4/dashboard-pie.png)

This is the Bar chart on the dashboard.

## ![bar](https://i.ibb.co/hBFftRk/dashboard-bar.png)

### Car Details and add cars to the highlighted page
After clicking the view button on the dashboard car table, users are redirected to the car details page. This page provides in-depth information about the specific car model. Users also have the option to highlight the car, adding it to their personalized list.

![car details](https://i.ibb.co/XY7kKwc/car-details.png)

### Highlighted Cars
This page shows the highlighted cars feature, where users can add or remove cars from their personalized list.

 ![highlighted cars](https://i.ibb.co/ZzNNJ5v/hightlighted-cars.png)


### Confirm removal
This is a confirmation pop-up that appears when users attempt to remove cars from their highlighted cars list. Users have the option to click the "Cancel" button to prevent the removal.

![confirm removal](https://i.ibb.co/pzGfF82/confirm-removal.jpg)

---


## Team members
- [Wutyee Win, 6540064](https://github.com/AeliaWin/aeliawin.github.io)  
- [Tharaphi Lwin, 6540040](https://github.com/LwinTharaphi/LwinTharaphi.github.io)
