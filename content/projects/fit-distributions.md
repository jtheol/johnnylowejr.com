+++
author = "Johnny"
title = "Distribution Fitting Webapp"
date = "2024-03-26"
description = "Experiemnt built using plotly-dash and Fitter library"
tags = [
    "eda",
    "statistics",
    "visualization"
]
+++
The tool empowers data scientists to explore and analyze the probability distributions of their numerical data, aiding in the selection of appropriate distribution models for their datasets.

Data Upload: Users can upload CSV or Excel files containing numerical data. The tool parses the data and provides insights such as the number of numeric features and the total number of distributions available for fitting.

Distribution Fitting: Users can select specific distributions to fit to their data from a dropdown menu. They can also choose criteria for selecting the best distribution, such as sumsquare error, AIC, or BIC.

Visualization: After selecting distributions and criteria, users can visualize the fitted distributions along with relevant statistics like sumsquare error, AIC, and BIC. The tool displays the best distribution selected based on the chosen criteria.

Interactivity: The tool offers interactivity through dropdown menus, input fields, and buttons, allowing users to explore different distributions and fitting options.

Integration: It utilizes the Dash framework for creating interactive web applications in Python. The backend logic handles data processing, distribution fitting, and visualization, while the frontend provides a user-friendly interface for interacting with the tool.