[![REUSE status](https://api.reuse.software/badge/github.com/SAP-samples/teched2023-DA264)](https://api.reuse.software/info/github.com/SAP-samples/teched2023-DA264)

# DA264 - Cross-Cloud Modeling with SAP Datasphere and Hyperscaler Data Sources

## Description

This repository contains the material for the SAP TechEd 2023 session called DA264 - Cross-Cloud Modeling with SAP Datasphere and Hyperscaler Data Sources. 

## Overview

Data on multiple scattered source systems (external and SAP) make analysis of category performance difficult. The inability and the high cost of bringing data sources together make root cause analysis of online sales a burdensome process.

This session introduces attendees the Unified data federation architecture allows customers to combine external data sources (Google Analytics and Google BigQuery) with SAP data sources for live category analysis without business data replication and with state-of-the-art performance in one central location.

You are going to analyze Category Performance for digital/online sales by combining external source systems like Google Analytics and sales, discounts and stock data from SAP System.
With a data federation architecture, it is possible to leave data in its source system and access it in one location without replication. With this Hand-on session you can combine their Big Query and SAP data to derive new insights 

## Requirements

The requirements/ Existing SetUp to follow the exercises in this repository are:

1. A [SAP Datasphere System](https://www.sap.com/india/products/technology-platform/datasphere.html), configured with spaces and users with assigned roles. 
To get started, sign up for your [SAP Datasphere free tier tenant.](https://www.sap.com/products/technology-platform/datasphere/trial.html)

2. A [SAP Analytics Cloud account](https://www.sap.com/india/products/technology-platform/cloud-analytics.html) with live data connections to SAP Datasphere system to access SAP Datasphere Analytic Model or Perspective within SAP Analytics Cloud.
To get started, sign up for your [SAP Analytics Cloud Trial.](https://www.sap.com/products/technology-platform/cloud-analytics/trial.html)

3. A [Google cloud account](https://cloud.google.com) with a google cloud project enabled with the BigQuery API. If you're new to Google Cloud, [create a Google cloud account](https://cloud.google.com/free/) and create a [Google Cloud project](https://developers.google.com/workspace/guides/create-project). For new Projects, the BigQuery the BigQuery API is automatically enabled. 

## Exercises

- [Getting Started](exercises/ex0/)
- [Exercise 1 - Build and expose data views on SAP Datasphere](exercises/ex1/)
    - [Exercise 1.1 - Creating a new view of "Product Sales Country"](exercises/ex1#exercise-1--creating-a-new-view-of-product-sales-country)
- [Exercise 2 - Creating a new view of "Product Sales Country Discount"](exercises/ex2/)
- [Exercise 3 - Creating a new analytical model for "Product Sales Country Discount"](exercises/ex3/)
- [Exercise 4 - Create a Category Management Dashboard on SAP Analytics Cloud](exercises/ex4/)
    - [Exercise 4.1 - Creating the Layout for the Category Management Dashboard](exercises/ex4#exercise-41-creating-the-layout-for-the-category-management-dashboard)
    - [Exercise 4.2 - Assigning the data from SAP Datasphere to Dashboard](exercises/ex4#exercise-42-assigning-the-data-from-sap-datasphere-to-dashboard)
- [Exercise 5 - Creating the Charts in Category Management Dashboard for displaying Data](exercises/ex5/)
    - [Exercise 5.1 - Creating the first Chart for displaying **Quantity per Product Category**](exercises/ex4#exercise-51-creating-the-first-chart-for-displaying-quantity-per-product-category)
    - [Exercise 5.2 - Creating another Chart for displaying **Discount per Product Category**](exercises/ex5#exercise-52-creating-another-chart-for-displaying-discount-per-product-category)
    - [Exercise 5.3 - Creating the last Chart for displaying **Sales Quantity over Time** ](exercises/ex5#exercise-53-creating-the-last-chart-for-displaying-sales-quantity-over-time)
- [Exercise 6 - Creating **Input Controls** for the dashboard](exercises/ex6/)

## Contributing
Please read the [CONTRIBUTING.md](./CONTRIBUTING.md) to understand the contribution guidelines.

## Code of Conduct
Please read the [SAP Open Source Code of Conduct](https://github.com/SAP-samples/.github/blob/main/CODE_OF_CONDUCT.md).

## How to obtain support
Support for the content in this repository is available during the actual time of the online session for which this content has been designed. Otherwise, you may request support via the [Issues](../../issues) tab.

## License
Copyright (c) 2023 SAP SE or an SAP affiliate company. All rights reserved. This project is licensed under the Apache Software License, version 2.0 except as noted otherwise in the [LICENSE](LICENSES/Apache-2.0.txt) file.
