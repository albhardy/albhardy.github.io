---
layout: project
title: SIA App Challenge
image_path: 
orderid: 23
date: 2017-10-21
blurb: 'Develop Airline Serviceware inventory tracking and optimisation to minimise wastage'
---
{% include image-full.html file="/2017/4/sia-1.jpg" alt="SIA AppChallenge Participants" height="450px" type="full"%}
<p class='sublead'>The 3rd SIA App Challenge is a coding competition which require participants to build an application that would solve actual airline customer and operational business challenges. </p> 
<!--more-->
The challenges cover following areas: 

1. Customer Challenges:
- Digital Singapore Stopover Holiday
- Cabin Seats Display
- Gamification of the KrisFlyer Programme
- Accurate Contact Information for Timely Flight Updates

2. Operations Challenges:
- Cargo Shipment Management
- Tracking Inventory to Reduce Wastage
- Cabin Defects Management

Based on theme “Be Part of SIA’s Digital Transformation”, over 80 teams took part in the Open and Student Category to create fresh solutions.

### Challenge Brief: Tracking Inventory to Reduce Wastage
Currently, there is no tracking of the actual usage or disposal of high value serviceware (crockery, cutlery, glassware) once they are issued out from airline caterers’ warehouses worldwide, and used on the flights. In ensuring a constant supply of these items, airline need to reduce wastage and optimise utilisation through practical yet sustainable technology. _How can airline track such serviceware and optimise airline inventory to minimize wastage?_

### Learning points
The logistics complexity and wastage from inflight services is noteworthy:
- A single, long-haul Boeing 747 has over 40,000 items loaded on to it before it flies. 
- According to the IATA, airlines produced 5.2 million tons of product and food waste last year (i.e. more than the weight of ten thousands of 747) - and will produce over 10 million tons annually by 2030! 
- The total in-flight waste was estimated to be up to 500kg per flight, largely contributed by onboard catering.  

Unfortunately, limited inventory visibility and accounting has led to inefficient inventory levels and cost escalations. 
As such, there's significant impact, efficiencies and economy of scale if we can improve and account for the catering logistics. 

### Idea: Aircounter
{% include image-full.html file="/2017/4/screenshots-app.png" alt="App Demo" height="350px" %}
"Aircounter" is designed to deliver practical counting mechanism for simultaneous inventory tracking. 
Using Computer Vision (i.e. Tensorflow Object Detection API) technology, our solution is able to wirelessly determine and count what an object is simply by pointing a mobile phone camera at it. 

{% include image-full.html file="/2017/4/sia-2.jpg" alt="Team Airfly" height="350px" %}

As compared to RFID, our solution will not incur additional cost and time for purchasing and applying electronic tags or sensors which will further mitigate electronic waste. This approach can be applied to a diverse range of objects, including assets that are too small for the use of barcodes. 

Aircounter also provide Web based Interface that allows user inspect and confirm the number of articles received based on pre-registered information. Images recorded can also be used for auditing shipments. Through this approach we aim to improve the logistic efficiency and accountability.

Reference: [SIA App Challenge 2017](https://nusenterprise.medium.com/flying-high-with-the-winners-of-the-sia-app-challenge-2017-c9333c5d3d1d)