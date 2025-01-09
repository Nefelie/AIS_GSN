# AIS Global Shipping Network
This project focuses on enhancing maritime situational awareness by building a Global Shipping Network (GSN) using AIS data. 

Objectives:
- extract vessel routes and destinations from AIS data
- represent shipping lanes and their junctions in a global network
- identify and analyse global maritime traffic patterns


An unsupervised graph extraction methodology from AIS data is proposed, consisting of:
- vessel destination extraction (ports, terminals): KNN, DBSCAN
- ship trajectory compression: Ramer–Douglas–Peucker algorithm
- waypoint clustering to form nodes: HDBSCAN
- node-to-node representation of vessel routes with additional attributes such as number of trips, to mean and standard deviation of time and distance

The resulting graph structure provides insights on vessel behaviour along key shipping lanes and the maritime supply chain at both country and port levels.

[Poster](https://github.com/Nefelie/AIS_GSN/blob/main/Nefelie%20Hemrich%20IP%20Poster.pdf)
