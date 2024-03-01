---
layout: home
permalink: index.html

# Please update this with your repository name and title
repository-name: eYY-4yp-project-template
title:
---

[comment]: # "This is the standard layout for the project, but you can clean this and use your own template"

# Detection and Repair Data Quality Issues in Process Mining

#### Team

- E/18/170, Kavinda Karunarathne, [email](mailto:e18170@eng.pdn.ac.lk)
- E/18/276, Jayathu Rajasooriya, [email](mailto:e18276@eng.pdn.ac.lk)
- E/18/412, Sanjaya Gihan, [email](mailto:e18412@eng.pdn.ac.lk)

#### Supervisors

- Prof. Roshan G. Ragel, [email](mailto:roshanr@eng.pdn.ac.lk)
- Dr. Asitha Bandaranayake, [email](mailto:asithab@eng.pdn.ac.lk)
- Dr. Damayanthi Herath, [email](mailto:damayanthiherath@eng.pdn.ac.lk)

#### Table of content

1. [Abstract](#abstract)
2. [Introduction](#introduction)
3. [Related works](#related-works)
4. [Methodology](#methodology)
5. [Experiment Setup and Implementation](#experiment-setup-and-implementation)
6. [Results and Analysis](#results-and-analysis)
7. [Conclusion](#conclusion)
8. [Publications](#publications)
9. [Links](#links)

---

<!-- 
DELETE THIS SAMPLE before publishing to GitHub Pages !!!
This is a sample image, to show how to add images to your page. To learn more options, please refer [this](https://projects.ce.pdn.ac.lk/docs/faq/how-to-add-an-image/)
![Sample Image](./images/sample.png) 
-->


## Abstract

In today's digital age, organizations accumulate vast amounts of data through their operational systems, capturing valuable insights into their processes. Process mining, a burgeoning field at the intersection of data analytics and process management, harnesses these data streams to uncover hidden patterns, bottlenecks, and inefficiencies within organizational workflows. However, amidst this wealth of data lie imperfections known as imperfection patterns, which can distort analysis and compromise decision-making.

Imperfection patterns encompass various anomalies within event logs, such as duplicate entries, missing timestamps, and incomplete data, hindering the accuracy and reliability of process mining analyses. Addressing these imperfections is critical to extracting meaningful insights and fostering data-driven decision-making.

Our project aims to develop an innovative algorithm and accompanying plugin for a Process Data Quality (PDQ) framework, designed to detect and rectify imperfection patterns in event logs. By leveraging advanced data mining techniques and process expertise, our solution seeks to enhance the quality and reliability of process data, empowering organizations to make informed decisions and drive continuous improvement initiatives.

## Introduction

### What is Process Mining?

Process mining is a cutting-edge discipline that extracts insights from the digital footprints left by organizational processes. By analyzing event logs and transactional data captured within information systems, process mining techniques unveil the inner workings of business processes, revealing their execution paths, variations, and performance metrics.

Through process discovery, conformance checking, and performance analysis, process mining enables organizations to gain a deep understanding of their operations, identify inefficiencies, and optimize workflows for enhanced productivity and efficiency. By bridging the gap between data analytics and process management, process mining empowers organizations to make data-driven decisions, streamline operations, and drive continuous improvement initiatives.

### Event logs and Data quality issues

Event logs are fundamental to process mining, capturing sequences of events representing process executions. Each event is associated with a case identifier, activity label, and timestamp for event ordering. Event logs may require additional attributes like resource information. They are compiled from raw source logs and formalized as a set of events, allowing relational algebraic operations.

To assess event log quality, a suitable quality model is crucial. Data quality dimensions include accuracy, completeness, consistency, currency, timeliness, volatility, and synchronization. Understanding and evaluating these dimensions enable the identification and resolution of data quality issues, ensuring reliable and trustworthy data for decision-making.

Patterns, popularized by Christopher Alexander, capture common problems and their solutions, applicable across various domains. Initially utilized in architecture and later in object-oriented programming, patterns offer practical solutions derived from experience. The "Rule of Three" dictates that a solution becomes a pattern after successful application in multiple contexts, emphasizing their practicality and adaptability.

## Related works

Existing research on data quality in process mining emphasizes the significance of quality event logs and proposes methods to address common issues like noise removal. The Process Mining Manifesto underscores the importance of high-quality event logs for analysis. Bose et al. categorize event log quality issues into missing, incorrect, imprecise, and irrelevant data categories. Mans et al. introduce a process mining data spectrum to categorize event data within a Hospital Information System (HIS), highlighting challenges arising from varying data granularity and accuracy. Noise in event logs can lead to complex and misleading models. Various studies propose frequency analysis to detect noise and identify unusual patterns. Event log imperfection patterns extracted from diverse fields offer insights into recurring issues, detection strategies, affected data quality dimensions, consequences on analysis outcomes, and remedial actions. These patterns enhance the reliability and usability of event logs for process mining analysis.

### Identified Imperfection Patterns

1. Form-based Event Capture 
2. Inadvertent Time Travel
3. Unanchored Event
4. Scattered Event
5. Elusive Case
6. Scattered Case
7. Collateral Events
8. Polluted Label
9. Distorted Label
10. Synonymous Labels 
11. Homonymous Label

Goal of this project is to develop and algorithm to detect and repair one or more of these imperfection patterns.

## Methodology

## Experiment Setup and Implementation

## Results and Analysis

## Conclusion

## Publications
[//]: # "Note: Uncomment each once you uploaded the files to the repository"

<!-- 1. [Semester 7 report](./) -->
<!-- 2. [Semester 7 slides](./) -->
<!-- 3. [Semester 8 report](./) -->
<!-- 4. [Semester 8 slides](./) -->
<!-- 5. Author 1, Author 2 and Author 3 "Research paper title" (2021). [PDF](./). -->


## Links

[//]: # ( NOTE: EDIT THIS LINKS WITH YOUR REPO DETAILS )

- [Project Repository](https://github.com/cepdnaclk/repository-name)
- [Project Page](https://cepdnaclk.github.io/repository-name)
- [Department of Computer Engineering](http://www.ce.pdn.ac.lk/)
- [University of Peradeniya](https://eng.pdn.ac.lk/)

[//]: # "Please refer this to learn more about Markdown syntax"
[//]: # "https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet"
