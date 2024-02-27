---
title: Datasets
# description: About Me
date: '2024-02-26'
aliases:
  - datasets
license: CC BY-NC-ND
lastmod: '2024-02-26'
menu:
    main: 
        weight: -70
        params:
            icon: categories
---

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Varela&display=swap" rel="stylesheet">
    <title>Interesting Datasets</title>
    <style>
        .container {
            font-family:"Varela", sans-serif;
            font-size:12px;
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background-color: #1D1F22;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            height: 400px; /* Set a fixed height for the container */
            overflow-y: auto; /* Enable vertical scrolling */
        }
        ul {
            list-style: none;
            padding: 0;
        }
        li {
            padding: 10px 0;
            border-bottom: 1px solid #ccc;
            display: none; /* Hide list items by default */
        }
        li.show {
            display: block; /* Show list items that match the search */
        }
        a:hover {
            text-decoration: underline;
        }
        input[type="text"] {
            font-family:"Varela", sans-serif;
            width: 100%;
            padding: 12px;
            margin-bottom: 15px;
            box-sizing: border-box;
            border: 1px solid #ccc;
            border-radius: 4px;
            outline: none;
            font-size: 16px;
            transition: border-color 0.3s ease;
        }
        input[type="text"]:focus {
            border-color: #007bff;
        }
    </style>
</head>
<body>
    <h1>Curated Dataset Collection</h1>
    <input type="text" id="searchInput" placeholder="Start typing to search datasets...">
    <div class="container">
        <ul id="datasetList">
            <li>
                <a href="https://www.aidworkersecurity.org/incidents/search format=csv">Humanitarian Aid Worker Security Incidents</a>
                <p>
                    The AWSD (Aid Worker Security Database) is a global compilation of reports detailing major security incidents involving deliberate acts of violence against aid workers. Incident data is collected from public sources through systematic media filtering using a data scraper tool, as well as directly from aid organizations and security entities. Incidents are crosschecked and verified annually, and the database includes parameters such as date, location, number of aid workers affected, institutional affiliation, and outcome of the incident.
                </p>
                <p>Humanitarian Outcomes, Aid Worker Security Database, aidworkersecurity.org</p>
            </li>
            <li>
                <a href="https://www.comparitech.com/blog/information-security/global-ransomware-attacks/">Global Ransomware Attacks</a>
                <p>The dataset presents information on ransomware attacks worldwide, spanning from 2018 to the present day. It includes details such as attack locations, affected sectors (healthcare, education, government, and business), ransom amounts, payment statuses, targeted entities, industries, and ransomware strains. Researchers compile data from country reports, industry news, and cybersecurity databases to document the latest ransomware incidents impacting businesses, healthcare organizations, educational institutions, and government agencies globally.</p>
                <p>https://www.comparitech.com/</p>
            </li>
            <li>
                <a href="https://data.cityofnewyork.us/City-Government/Parking-Violations-Issued-Fiscal-Year-2024/pvqr-7yc4/data_preview">NYC Parking Violations</a>
                <p>The dataset offers information on Parking Violations Issued from July 1, 2023, to June 30, 2024, aligning with the fiscal year cycle of New York City. It outlines violations issued within this timeframe, capturing their status at the time of issuance without reflecting subsequent updates such as payments, dismissals via hearings, or other status changes. Users seeking current status updates on outstanding parking violations are directed to consult the Open Parking & Camera Violations dataset.</p>
                <p>NYC OpenData</p>
            </li>
            <li>
                <a href="https://www.dla.mil/Portals/104/Documents/DispositionServices/LESO/ShipmentsCancellationsQTR1FY24.xlsx">LESO Shipments & Cancellations</a>
                <p>
The update provides the latest quarterly report on accountable property held by participating agencies, categorized into Controlled and Non-controlled. Controlled property remains on the LESO (Law Enforcement Support Office) property book and remains accountable to the Department of Defense (DoD). Conversely, Non-controlled property comprises common items sold to the general public by DLA (Defense Logistics Agency). The data offers a snapshot of Non-controlled property, representing the majority of transfers, and after one year, Non-controlled items become the property of the law enforcement agency and are removed from the LESO database.</p>
                <p>Defense Logistics Agency</p>
            </li>
            <li>
                <a href="http://205.174.165.80/CICDataset/ISCX-Tor-NonTor-2017/">Tor Network Dataset</a>
                <p>The "Tor-nonTor dataset (ISCXTor2016)" is a comprehensive collection designed to represent real-world traffic diversity, encompassing various communication channels and browsing activities. It features categorized traffic types, including browsing, email, chat, audio streaming, video streaming, FTP, VoIP, and P2P. Browsing traffic consists of HTTP and HTTPS sessions, while email encompasses Thunderbird client and Gmail accounts using SMTP/S, POP3/SSL, and IMAP/SSL protocols. Chat traffic includes Facebook, Hangouts, Skype, IAM, and ICQ via the Pidgin application. Additionally, audio and video streaming are represented by Spotify, YouTube (HTML5 and flash versions), and Vimeo. FTP sessions involve Skype file transfers, SFTP, and FTPS, while VoIP traffic covers Facebook, Hangouts, and Skype voice calls. P2P traffic represents file-sharing protocols such as BitTorrent, derived from Kali Linux distribution torrents and captured with Vuze application across various upload and download speeds.</p>
                <p>Canadian Institute for Cybersecurity</p>
            </li>
            <!-- Add more datasets as needed -->
        </ul>
    </div>
    <script>
        document.getElementById('searchInput').addEventListener('input', function() {
            var searchValue = this.value.toLowerCase();
            var listItems = document.querySelectorAll('#datasetList li');
            listItems.forEach(function(item) {
                var text = item.textContent.toLowerCase();
                var isVisible = text.includes(searchValue);
                item.classList.toggle('show', isVisible);
            });
        });
    </script>
</body>
</html>


