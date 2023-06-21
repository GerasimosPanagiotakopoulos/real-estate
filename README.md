# Real Estate Project

This project, called "Real Estate," was developed between __[Gerasimos Panagiotakopoulos](https://github.com/GerasimosPanagiotakopoulos)__ and __[Anastasia Panopoulou](https://github.com/anastasia1pan)__  as the final project for the Data Analytics Course by Big Blue Data Academy (BBDA). The project aimed to analyze and visualize real estate data extracted from a website using webscraping techniques.

## Table of Contents
- [Project Overview](#project-overview)
- [Installation](#installation)
- [Features](#features)
- [License](#license)

## Project Overview
<a name="project-overview"></a>
The "Real Estate" project involved collecting data from "Χρυσή Ευκαιρία", a real estate website with housing ads for both sale and rent. We utilized the power of webscraping by employing the `requests` library along with `BeautifulSoup` to extract data from the website. The data was collected over a span of five days, and multiple datasets were obtained.<br><br>

These datasets were subsequently cleaned and consolidated into a single dataset for further analysis. The focus of the project was to provide insights into the real estate market by examining various factors influencing property prices.

## Installation
<a name="installation"></a>
1. Clone the repository:<br>
`git clone https://gitlab.bigblue.academy/data-science-training/da2023.03-final-projects/real-estate.git`

2. Install the dependencies:<br>
`cd real-estate`<br>
`conda env create --name real-estate --file real-estate.yml`

## Features
<a name="features"></a>
- Interactive Dashboard: The project offers an interactive dashboard built using `plotly` and `Dash`. Users can explore the real estate dataset and gain insights into various factors affecting property prices.
- Geospatial Visualization: The dashboard includes a `folium` map that displays the locations of the listed houses, allowing users to visualize their distribution geographically, as well as a `Choropleth` where the user can visualize the spatial distribution of the average price per area.
- Price Analysis: Users can analyze the relationship between different factors and property prices through intuitive visualizations and interactive plots.

## License
<a name="license"></a>
This project is licensed under the MIT License. Feel free to modify and use the code for your own purposes.
For any questions or inquiries, please contact gerasimospan@gmail.com or panopoulou.anastasia1@gmail.com .
