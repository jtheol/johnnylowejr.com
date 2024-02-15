---
title: Projects 
menu: "main"
weight: 2
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
      Extracted structured information from unstructured text data related to ransomware negotiations
  and 60,000+ internal ransomware group conversations and applied exploratory and natural language processing methods to obtain
  meaningful insights. Analyzed quantitative information on global ransomware attacks across multiple industries and ransomware
  strains.
    </p>
  </li>

  <li class="project">
    <h3>Topic Modeling in Customer Feedback: Insights from Comcast Complaints</h3>
    <p>Examined consumer complaints about Comcast using a data set spanning from 2000-2016</p>
  </li>

  <li class="project">
    <h3>Analysis and Classification of Tor Network Traffic</h3>
    <p>Analyzed data and built a model to classify Tor traffic with using data
collected by the Canadian Institute for Cybersecurity</p>
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
    <h3>(WIP) Supply Chain Insights: Exploring Q3 FY2023 Shipments by LESO</h3>
    <p>This project aims to gain insights into the shipment data from the Law Enforcement Support Office (LESO) during the third quarter of the fiscal year 2023 (Q3 FY2023). LESO plays a crucial role in supporting law enforcement agencies by providing excess Department of Defence equipment and supplies to federal, state and local law enforcement agencies, making it essential to understand the shipment dynamics for better resource allocation and operational efficiency. The data used is during April 1 - June 30, 2023.</p>
  </li>
  <li class="project">
    <h3>Identifying Crime in New York City</h3>
    <p>The project involved analyzing data sourced from the Office of Management Analysis and Planning, cataloging criminal complaints since 2006. The dataset encompassed various attributes including crime type, location, age, gender, race, and enforcement time, amounting to 7.8 million records. To focus on recent events, we narrowed the timeframe to January 1, 2019, through July 15, 2022, resulting in 256,797 records.</p>
  </li>
  <li class="project">
    <h3>Fit Distributions Web-App</h3>
    <p>Built a web-app experiment to fit and visualize data to multiple distributions using the fitter library and plotly dash.</p>
  </li>
</ul>

</body>
</html>
