# Seoul Subway Stations Network Visualization
This project demonstrates the creation of a visual representation of the Seoul subway network using a modified dataset that contains station information and geospatial coordinates. The dataset has been curated to provide a simplified version of the full subway network, with stations translated from Korean to English and distances between stations calculated and added.

## Dataset
The dataset used for this project is based on Seoul Subway Geospatial Data, originally sourced from Kaggle by Lee Y. (2020). 
The dataset was modified in the following ways:

**Reduced Number of Stations and Lines:** The number of stations and subway lines was reduced for simplicity.

**Station Names Translated:** Station names were translated from Korean to English for better accessibility to non-Korean speakers.

**Distance Column Added:** A new column with distances between stations was added. The distances were calculated using the Haversine formula, which computes the distance between two points on a sphere given their latitudes and longitudes.

CSV file URL: https://drive.google.com/file/d/19yVeLwB9RVwsLClpm5W-HkGPLc_O_FQH/view?usp=sharing

## Project Structure
This project visualizes the Seoul subway network using NetworkX and Matplotlib. It performs the following tasks:

**1. Loading the Dataset:** The CSV file containing station details, including latitude, longitude, line information, and distances between consecutive stations.

**2. Building the Graph:** Each subway station is added as a node in the graph, while the connections between stations are represented as edges. The distances between stations are also added as edge attributes.

**3. Visualization:** Using NetworkX and Matplotlib, the subway network is visualized with nodes representing stations and edges representing connections between them. Each subway line is color-coded, and labels for station names and distances between stations are displayed.


### Acknowledgements:

Lee Y. (2020). Seoul subway geospatial data. Kaggle. https://www.kaggle.com/datasets/ninetyninenewton/seoul-subway-
coordinates/data
