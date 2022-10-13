# An End-to-End Industrial IoT (IIoT) Predicitve Maintenance System

## Overview:

This repo documents a one-semester Independent Study project and community cooperative engagement project on Industrial IoT Preventative Maintenance for a local fabrication factory. It presents an innovate approach synthesizing academic study, professional software industry experience and delivering value to clients facing real-world technology challenges/opportunities.



## Academic Schedule


| Week | Topic |
| --- | --- |
| Week 1-2 | **Research** | 
| | General: IIoT Problem Definition |
| | General: IIot Best Practices |
| | General: Reference Implementation(s) |
| | Specific: Client-specific workflow, constraints, priorities |
| Week 3-4 | **Design Document** |
| | Feasibility Study |
| | Candidate Software/Hardware |
| | Project Scope, Deliverables & Cost Estimates |
| | First Draft: Design Document |
| Week 5-6 | Theory: Time Series Analysis & ML Predictive Models |
| | Identify Sample Datasets |
| | Time Series: Engineering, Mathematical & Statistical Properties (Noise Filtering, Anomaly Detection, Regime Shifts, etc)|
| | Time Series: Software Libraries |
| | Time Series: Forecast Models |
| Week 7-8 | End-to-End (Phase 1): Mock Backend Static Data Store |
| | Mock REST API serving static data |
| | Persistant Datastore |
| | Real-Time Time Series Pipeline: Clean, Transform, Analyze, Report, Alert |
| Week 9-10 | End-to-End (Phase 2): IoT Sensors and Real-Time Streaming Collection |
| | Integrate full End-to-End Pipeline from IIoT to Report/Alert
| Week 11-12 | Cloud Infrastructure:  |
| | Port Pipeline Componets to Cloud Service(s) |
| | Performance Audit |
| | Reliabilty Audit |
| | Security Audit |
| Week 13-14 | Reporting/Analytics Dashboard UI |
| | Add Human-facing UX Analytics Dashboard |




# Resources

##  1. **Week 1-2: Research**
  * Business Perspective
    - [Analytics in Manufacturing](https://www.youtube.com/watch?v=BHP6rpN-2Uc)
    - [Leveraging Industrial IoT and advanced technologies for digital transformation](https://www.mckinsey.com/~/media/mckinsey/business%20functions/mckinsey%20digital/our%20insights/a%20manufacturers%20guide%20to%20generating%20value%20at%20scale%20with%20iiot/leveraging-industrial-iot-and-advanced-technologies-for-digital-transformation.pdf) by Andreas Behrendt (McKinsey & Co) et. al (Oct 2020)
  * Research Papers
    - [Industrial Internet of Things: A Review](https://www.researchgate.net/publication/336439752_Industrial_Internet_of_Things_A_Review) by Avish Karmakar (RCCIIT)
 et. al. (Mar 2019)
    - [Key Challenges and Emerging Technologies in Industrial IoT
Architectures: A Review](https://www.mdpi.com/1424-8220/22/15/5836) by Akseer Ali Mirani (Munster Tech U) et. al. (Jun 2022)
    - [Structuring Reference Architectures for the Industrial Internet of Things](https://www.mdpi.com/1999-5903/11/7/151) by Sebastian R. Bader et. al (Jun 2019)
  * Code
    - [IoT For Beginners Curriculum](https://github.com/microsoft/IoT-For-Beginners)
    - [Awesome IoT/phodal](https://github.com/phodal/awesome-iot)
    - [Awesome IoT/HQarroum](https://github.com/HQarroum/awesome-iot)
    - [IoT Resources](https://github.com/kevinwlu/iot)

## 2. Week 3-4: Design Document
  * Introduction to Consulting
    - [The Consulting Bible, 2nd Ed](https://learning.oreilly.com/library/view/the-consulting-bible/9781119776871/) by Alan Weiss, Wiley 2021
    - [Advanced Consulting: Earning Trust at the Highest Level](https://learning.oreilly.com/library/view/advanced-consulting/9781523088089/) by Bill Passmore, Berrett-Koehler, 2020
    - [Writing Great Specifications](https://learning.oreilly.com/library/view/writing-great-specifications/9781617294105/) by Kamil Nicieja, Manning 2017
- * Architectural Patterns
    - [The Industrial Internet of Things, Vol G1 Reference Architecture](https://www.iiconsortium.org/pdf/IIRA-v1.9.pdf) by Industrial Internet Consortium, 2019
    - [Proposal for an IIoT Device Solution According to Industry
4.0 Concept](https://pubmed.ncbi.nlm.nih.gov/35009868/) by Andrea Vaclavova et al, Jan 2022
  * Trade Publications
    - [IoT and Edge Computing for Architects](https://learning.oreilly.com/library/view/iot-and-edge/9781839214806/) by Perry Lea, Packt 2020
    - [Hands-On Industrial Internet of Things](https://learning.oreilly.com/library/view/hands-on-industrial-internet/9781789537222/) by Giacomo Veneri, Antonio Capasso, Packt 2018
    - [Auditing IT Infrastructures for Compliance, 3rd ed](https://learning.oreilly.com/library/view/auditing-it-infrastructures/9781284236613/) by Robert Johnson, et al, Jones and Bartlett Learning, 2022
    - 
## 3. Week 5-6: Theory: Time Series Analysis & ML Predictive Models
  * Video Overviews
      - [What is predictive maintenance on electric motors - low power motors (4:17)](https://www.youtube.com/watch?v=cFlY6L1igKY)
      - [Predictive Maintenance with MATLAB and Simulink (35:54)](https://www.youtube.com/watch?v=hEYv3iN70ic)
      - [Predictive Maintenance, Part 1: Introduction (WATCH ALL 5 PARTS)](https://www.youtube.com/watch?v=RmVWKLbLq2Y)
      - [AWS vs Azure IoT for Industry (22:59)](https://www.youtube.com/watch?v=eyDcWPic0Do&t=1s) pro-AWS comparison between leading IoT SaaS cloud integrators
      - [The Key Differences Between OPC UA And MQTT Sparkplug](https://www.hivemq.com/blog/iiot-protocols-opcua-vs-mqtt-sparkplug-digital-transformation/)
      - [Industry 4.0 Demo Project w/ Ignition MQTT, Raspberry Pi, Arduino, and Kepware IoT Gateway (32:00)](https://www.youtube.com/watch?v=spE6IpOU-2w) - Reference implementation with both FOSS and closed-source integrator supervisory software overlay
  * Trade Publications
      - [Time Series Analysis with Python Cookbook](https://learning.oreilly.com/library/view/time-series-analysis/9781801075541/) by Tarek A. Atwan, Packt 2022
      - [Machine Learning for Time Series Analysis](https://learning.oreilly.com/library/view/machine-learning-for/9781801819626/) by Ben Auffarth, Packt 2021
      - [Time Series Analysis on AWS](https://learning.oreilly.com/library/view/time-series-analysis/9781801816847/) by Michael Hoarau, Packt 2022
      -  ML/AI Models for Time Series (Regime Change, Anomalies, Feature Detections, etc)
- 
## 4. Week 7-8: End-to-End (Phase 1): Mock Backend Static Data Store
  * AWS Cloud Resources
    - [AWS Architecture Blog: IoT](https://aws.amazon.com/blogs/architecture/category/internet-of-things/aws-iot-platform/)
    - [AWS IoT Solution Repository](https://aws.amazon.com/iot/solutions/?iot-solution-repository-cards.sort-by=item.additionalFields.headline&iot-solution-repository-cards.sort-order=asc&awsf.iot-solution-repository-filter-industry=*all&awsf.iot-solution-repository-filter-products=*all&awsf.iot-solution-repository-filter-usecase=*all&awsf.iot-solution-repository-filter-solution-type=*all)
    - [AWS Real-Time IoT Device Monitoring with Kinesis Data Analysis](https://docs.aws.amazon.com/solutions/latest/real-time-iot-device-monitoring-with-kinesis/architecture.html)
    - [Getting Started Architecting on AWS](https://aws.amazon.com/architecture/?cards-all.sort-by=item.additionalFields.sortDate&cards-all.sort-order=desc&awsf.content-type=*all&awsf.methodology=*all&awsf.tech-category=*all&awsf.industries=*all)
  * Trade Publications
    - [Raspberry Pi and MQTT Essentials](https://learning.oreilly.com/library/view/raspberry-pi-and/9781803244488/) and [Github Repo](https://github.com/PacktPublishing/Raspberry-Pi-and-MQTT-Essentials)
    - [Arduino 2.0 IDE](https://www.arduino.cc/en/software)
    - [Programming the Internet of Things](https://learning.oreilly.com/library/view/programming-the-internet/9781492081401/) by Andy King, O'Reilly 2021
    - Real-Time Streaming Data Broker
    - Long-term Storage (SQL DB and/or Time Series DB)
## 5. Week 9-10: End-to-End (Phase 2): IoT Sensors and Real-Time Streaming Collection
  * Trade Publications
    - [Raspberry Pi and MQTT Essentials](https://learning.oreilly.com/library/view/raspberry-pi-and/9781803244488/)
    - [Commerical and Industrial IoT Applications with Raspberry Pi: Prototyping IoT Solutions: Chp 1 - Internet of Things Overview](https://learning.oreilly.com/library/view/commercial-and-industrial/9781484252963/html/481978_1_En_1_Chapter.xhtml) by Ioana Culic et al, Apress 2022
    - [Internet of Things, 2nd ed](https://learning.oreilly.com/videos/internet-of-things/9780137592135/) by Robert Barton and Jerome Henry, LiveLesson 2021
    - [Practical Python Programming for IoT](https://learning.oreilly.com/library/view/practical-python-programming/9781838982461/) Gary Smart, Packt 2020
    - [Demystifying IoT Security](https://learning.oreilly.com/library/view/demystifying-internet-of/9781484228968/) by Sunil Cheruvu, Apress 2019
## 6. Week 11-12: Cloud Infrastructure: 
  * Cloud Providers
    - [Industry 4.0 IIoT Cloud: AWS vs MS Azure](https://www.youtube.com/watch?v=eyDcWPic0Do)
    - [Industrial IoT Architecture Patterns](https://docs.aws.amazon.com/whitepapers/latest/industrial-iot-architecture-patterns/industrial-iot-architecture-patterns.pdf) AWS Whitepaper 2022
    - [Designing the IoT Solutions with Azuer: Chp 5 - IoT Applications in Manufacturing](https://learning.oreilly.com/library/view/designing-internet-of/9781484260418/html/491651_1_En_5_Chapter.xhtml) by Nirnay Bansal, Apress 2020
## 7. Week 13-14: Reporting/Analytics Dashboard U
  - BI Dashboard
    - [Building IoT Visualizations with Grafana](https://learning.oreilly.com/library/view/building-iot-visualizations/9781803236124/) by Rodrigo Juan Hernandez, Packt 2022
    - [Web Application Development with Streamlit: Develop and Deploy Secure and Scalable Web Applications to the Cloud Using a Pure Python Framework](https://learning.oreilly.com/library/view/web-application-development/9781484281116/) by Mohammed Khorasani, et al, Apress 2022
    - [Learning Tableau 2022](https://learning.oreilly.com/library/view/learning-tableau-2022/9781801072328/) by Joshua N. Milligan et al, Packt 2022


