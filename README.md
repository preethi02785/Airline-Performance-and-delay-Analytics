# Airline-Performance-and-delay-Analytics
**Overview**

This project provides an end-to-end analysis of airline operations by integrating four interconnected datasets: Flights, Airlines, Airports, and Aircraft. Rather than looking at delays and cancellations from a single perspective, the dashboard combines information from all these sources to uncover how airlines, routes, airports, and even aircraft age contribute to overall flight performance.

The goal of the project is to answer questions such as:

- Which airlines experience the highest delays?
- How do delays vary throughout the week and by time of day?
- Which routes are most frequently delayed?
- Which airports have the highest cancellation rates?
- Does aircraft age impact delays and cancellations?
- Which airlines maintain the best on-time performance?
---
**Data Model**

✈️ Flights Dataset: Contains the features such as airline_id, origin, arrival & departure dates, delays, enabling comparison with other datasets.

🏢 Airlines Dataset: Provides airline details for differentiating delay patterns, cancellation trends, and on-time performance across carriers.

🛫 Airports Dataset: Contains airport information used to identify airports with high cancellation rates and frequently delayed routes.

🛠 Aircraft Dataset: Provides aircraft age and characteristics, allowing the analysis of how ageing fleets influence delays and reliability.

These datasets are connected through common identifiers, creating a unified view of airline operations.
