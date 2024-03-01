---
title: Projects
# description: About Me
date: '2024-02-26'
aliases:
  - projects
license: CC BY-NC-ND
lastmod: '2024-02-26'
menu:
    main: 
        weight: -90
        params:
            icon: archives
---

<style>
.project-list {
  list-style-type: none;
  padding: 0;
}

.project {
  border: 1px solid #ccc;
  padding: 20px;
  margin-bottom: 20px;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.project:hover {
  transform: translateY(-5px);
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);
}

</style>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Project Showcase</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>

<ul class="project-list">
  <li class="project">
    <h3>Insights Into Ransomware</h3>
    <p>
Extracted structured information from unstructured text data related to ransomware negotiations and 60,000+ internal ransomware group conversations. Applied exploratory and natural language processing methods to obtain meaningful insights. Analyzed quantitative information on global ransomware attacks across multiple industries and ransomware strains.

The capstone project analyzed datasets related to ransomware, including global ransomware attacks from 2018-2023, anonymized negotiation chats between victims and 11 ransomware groups, and leaked internal chat messages from the Conti group. Analysis showed the healthcare industry experienced the most attacks, while utilities paid higher average ransoms. The project focused on Conti given their success and available data, mapping their negotiators and analyzing time-based patterns. Topic modeling extracted key themes like user support, negotiations, data leakage, and infiltration methods. Overall the project compiled and analyzed multiple ransomware datasets to gain insights into how groups like Conti operate.

The project utilized two topic modeling techniques - Latent Dirichlet Allocation (LDA) and BERTopic using class-based TF-IDF - to extract key topics from the ransomware negotiation chat datasets. Topic modeling identifies common themes in text documents by analyzing frequently used words.

BERTopic produced more interpretable topics including files stolen, user support, negotiation process, threats of data leaks, and infiltration methods. LDA found similar topics but BERTopic's visualizations provided better representation.

Topic modeling results were used to identify documents of interest for further analysis, excluding less relevant topics. Main limitations were the amount of available negotiation data and quality of translations.

Overall, topic modeling provided a useful unsupervised method to extract important themes from the ransomware negotiations and surface documents for further exploration.
    </p>
  </li>

  <li class="project">
    <h3>iFood Marketing Customer Behavior Analysis (WIP)</h3>
    <p>
      iFood, the foremost food delivery app in Brazil, operates across over a thousand cities, relying heavily on sustaining robust customer engagement to solidify its market leadership. Data Analysts within the company's data team face the perpetual challenge of furnishing valuable insights through open scope projects. This case study presents a sample dataset, simulating meta-information on customer interactions with iFood campaigns. Your task is to decipher the data, unearth business opportunities, and derive insights to optimize campaign outcomes and drive value for the company. By performing robust exploratory analysis and leveraging advanced analytics tools, you're expected to uncover actionable insights and propose data-driven strategies aimed at enhancing campaign effectiveness and bolstering customer engagement, aligning with iFood's strategic imperative of data-centric decision-making and continuous optimization.
    </p>
    <p>Key Objectives</p>
    <ul>
        <li>Conduct thorough data exploration to uncover insights, establish relationships, and enhance comprehension of customer characteristics.</li>
        <li>Propose and articulate a customer segmentation strategy derived from observed customer behaviors.</li>
        <li>Engineer and validate a predictive model to empower the company in maximizing profits from upcoming marketing campaigns.</li>
    </ul>
  </li>

  <li class="project">
    <h3>Topic Modeling in Customer Feedback: Insights from Comcast Complaints</h3>
    <p>Examined consumer complaints about Comcast using a data set spanning from 2000-2016.

Firstly, we preprocess the data and divides complaints based on their ratings. Then, we employ TF-IDF vectorization to identify the most common words in negative comments, focusing on topics like Comcast packages and customer support wait times.

Utilizing Latent Dirichlet Allocation (LDA), identify topics within the negative complaints and prints key terms per topic, and further examine complaints related to customer service.

Lastly, utilize BERTopic, a state-of-the-art topic modeling technique, to identify and visualize topics within negative complaints, notably highlighting issues similar to customer service complaints.

The process provides an insightful exploration of consumer sentiments, shedding light on prevalent issues and sentiments within Comcast consumer complaints.
</p>
  </li>

  <li class="project">
    <h3>Analysis and Classification of Tor Network Traffic</h3>
    <p>Analyzed data and built a model to classify Tor traffic with using data
collected by the Canadian Institute for Cybersecurity.

The process of building the model was initially loading and preprocessing network traffic data, including encoding categorical variables and removing potential sources of data leakage. Subsequently, splitting the dataset into training, validation, and testing sets.

Two models, Logistic Regression and Random Forest, are trained and evaluated. For both models, learning curves are plotted to visualize performance and detect signs of overfitting.

Hyperparameter tuning is performed for the Random Forest model using GridSearchCV to optimize its performance. The best parameters are identified and applied to the model, and validation curves are plotted to assess the impact of varying parameters.

Feature importances are analyzed to uncover the most influential variables in the Random Forest model. Finally, the model's performance is evaluated on the test set, and a confusion matrix is generated to assess its classification accuracy.
</p>
  </li>

  <li class="project">
    <h3>Humanitarian Aid Worker Security Incidents</h3>
    <a href="https://public.tableau.com/app/profile/johnny.lowe/viz/HumanitarianAidWorkerSecurityIncidents/HumanitarianAidWorkerSecurityIncidents?publish=yes">View on Tableau Public</a>
    <p>Built a Tableau dashboard to visualize humanitarian aid worker security incidents,
with functionality to analyze trends in tactics, total incidents, and the countries where they were affected most
    <div class='tableauPlaceholder' id='viz1707515706175' style='position: relative'>
   <noscript><a href='#'><img alt='Humanitarian Aid Worker Security Incidents ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;CT&#47;CT9M3CP3R&#47;1_rss.png' style='border: none' /></a></noscript>
   <object class='tableauViz'  style='display:none;'>
      <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' />
      <param name='embed_code_version' value='3' />
      <param name='path' value='shared&#47;CT9M3CP3R' />
      <param name='toolbar' value='yes' />
      <param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;CT&#47;CT9M3CP3R&#47;1.png' />
      <param name='animate_transition' value='yes' />
      <param name='display_static_image' value='yes' />
      <param name='display_spinner' value='yes' />
      <param name='display_overlay' value='yes' />
      <param name='display_count' value='yes' />
      <param name='language' value='en-US' />
      <param name='filter' value='publish=yes' />
   </object>
</div>
<script type='text/javascript'>                    var divElement = document.getElementById('viz1707515706175');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else { vizElement.style.width='100%';vizElement.style.height='1877px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>
</p>
  </li>
  <li class="project">
    <h3>Employee Churn Overview Dashboard</h3>
    <a href="https://public.tableau.com/app/profile/johnny.lowe/viz/EmployeeAttritionDashboard_17081491530210/AttritionDashboard">View on Tableau Public</a>
    <p> Developed a dashboard to give an overview of employee churn.
<div class='tableauPlaceholder' id='viz1708150472309' style='position: relative'><noscript><a href='#'><img alt='Attrition Dashboard ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Em&#47;EmployeeAttritionDashboard_17081491530210&#47;AttritionDashboard&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='EmployeeAttritionDashboard_17081491530210&#47;AttritionDashboard' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Em&#47;EmployeeAttritionDashboard_17081491530210&#47;AttritionDashboard&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1708150472309');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else { vizElement.style.width='100%';vizElement.style.height='1077px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>

</p>
  </li>


  <li class="project">
    <h3>New York City Real Estate</h3>
    <a href="https://public.tableau.com/app/profile/johnny.lowe/viz/NewYorkCityRealEstateDashboard/Dashboard">View on Tableau Public</a>
    <p> Developed a dashboard to analyze new york real estate. 
    <div class='tableauPlaceholder' id='viz1708356123899' style='position: relative'><noscript><a href='#'><img alt='Dashboard ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ne&#47;NewYorkCityRealEstateDashboard&#47;Dashboard&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='NewYorkCityRealEstateDashboard&#47;Dashboard' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ne&#47;NewYorkCityRealEstateDashboard&#47;Dashboard&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1708356123899');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else { vizElement.style.width='100%';vizElement.style.height='2027px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>
</p>
  </li>



  <li class="project">
    <h3>Identifying Crime in New York City</h3>
    <p>The project involved analyzing data sourced from the Office of Management Analysis and Planning, cataloging criminal complaints since 2006. The dataset encompassed various attributes including crime type, location, age, gender, race, and enforcement time, amounting to 7.8 million records. To focus on recent events, we narrowed the timeframe to January 1, 2019, through July 15, 2022, resulting in 256,797 records.</p>
  </li>
  <li class="project">
    <h3>Fit Distributions Web-App</h3>
    <p>The tool empowers data scientists to explore and analyze the probability distributions of their numerical data, aiding in the selection of appropriate distribution models for their datasets.

Data Upload: Users can upload CSV or Excel files containing numerical data. The tool parses the data and provides insights such as the number of numeric features and the total number of distributions available for fitting.

Distribution Fitting: Users can select specific distributions to fit to their data from a dropdown menu. They can also choose criteria for selecting the best distribution, such as sumsquare error, AIC, or BIC.

Visualization: After selecting distributions and criteria, users can visualize the fitted distributions along with relevant statistics like sumsquare error, AIC, and BIC. The tool displays the best distribution selected based on the chosen criteria.

Interactivity: The tool offers interactivity through dropdown menus, input fields, and buttons, allowing users to explore different distributions and fitting options.

Integration: It utilizes the Dash framework for creating interactive web applications in Python. The backend logic handles data processing, distribution fitting, and visualization, while the frontend provides a user-friendly interface for interacting with the tool.
    </p>
  </li>
</ul>

</body>
</html>
