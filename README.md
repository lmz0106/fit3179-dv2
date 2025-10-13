# fit3179-dv2

Aussie Weather Myths: A Data-Driven Visualisation
This project is a data visualisation created for the FIT3179 Data Visualisation 2 assignment at Monash University. It explores and challenges common weather stereotypes of Australia's three largest east coast cities: Melbourne, Sydney, and Brisbane.

Live Demo: https://lmz0106.github.io/fit3179-dv2/

🌦️ About the Project
It’s a classic Aussie debate: Is Melbourne's weather truly unpredictable? Is Sydney secretly the 'wettest' city? Is Brisbane in a perpetual state of summer?

This project moves beyond anecdotal beliefs to provide a data-driven narrative that tests these long-held myths. Using daily weather data from 2024 and domestic tourism data from 2023, this visualisation guides the user through a story that compares rainfall, temperature patterns, and the potential correlation between 'pleasant weather' and tourism.

The entire project is built as a single-page scrolling narrative, using Vega-Lite for all charts and maps as required by the assignment brief.

📊 Visualisation Idioms Used
Grouped Bar Chart: To directly compare two different metrics (total rainfall vs. number of rainy days) across the three cities.

Layered Interactive Map: To spatially locate the cities and provide details-on-demand about their temperature patterns via tooltips.

Scatter Plot: To investigate the potential relationship between pleasant weather and the volume of domestic tourism.

💾 Data Sources
This project integrates data from two distinct, authoritative Australian government sources:

Weather Data: Sourced from the Australian Bureau of Meteorology (BOM). Daily observations for 2024 were collected for rainfall, temperature, and solar exposure.

Tourism Data: Sourced from Tourism Research Australia (TRA), specifically the quarterly National Visitor Survey results for 2023,2024.

🛠️ Tools & Technologies
Visualisation Library: Vega-Lite

Core Technologies: HTML, CSS, JavaScript

Data Processing: Python with the Pandas library was used to clean and merge the initial datasets.

Fonts: Merriweather and Lato sourced from Google Fonts.

🚀 How to Run Locally
Because this project loads local data files (.csv and .json), you cannot simply open the index.html file directly in your browser due to browser security policies (CORS).

The best way to run this project locally is by using a live server. If you are using Visual Studio Code, I highly recommend the Live Server extension.

Install the Live Server extension.

Open the index.html file in VS Code.

Click the "Go Live" button in the bottom-right corner of the status bar.

👤 Author
Meize Li

This project was created as part of the FIT3179 course at Monash University, Semester 2, 2025.
