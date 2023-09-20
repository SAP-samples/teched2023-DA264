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

The requirements to follow the exercises in this repository are...

1) SAP Datasphere Instance - [You may use SAP Datasphere Free Tier.](https://developers.sap.com/tutorials/data-warehouse-cloud-1-begin-trial.html)
2) Google Cloud Platform account [Create a Google Cloud Platform Trial account.](https://cloud.google.com/free) with relevant authorization for user to use Google BigQuery
3) Google BigQuery Service Instance with your web Google Analytics Data (you can also follow along by copying the public Google Analytics set into your BigQuery space) 
4) Demo data for executing/deploying the application of this mission
Attached is a demo CSV file that can be referenced for what S4 data might look like in the source system. Data is based on the Google Analytics public data set. For productive use, typically a connection to an SAP backend is required:
5) SAP source (S/4HANA, Marketing Cloud, etc) containing desired data. Data examples: Discount Information Stock Data Additional Sales Information Connecting SAP source to Datasphere is not part of this mission but please refer to the above links for how to do so.

## Exercises

Provide the exercise content here directly in README.md using [markdown](https://guides.github.com/features/mastering-markdown/) and linking to the specific exercise pages, below is an example.

- [Getting Started](exercises/ex0/)
- [Exercise 1 - First Exercise Description](exercises/ex1/)
    - [Exercise 1.1 - Exercise 1 Sub Exercise 1 Description](exercises/ex1#exercise-11-sub-exercise-1-description)
    - [Exercise 1.2 - Exercise 1 Sub Exercise 2 Description](exercises/ex1#exercise-12-sub-exercise-2-description)
- [Exercise 2 - Second Exercise Description](exercises/ex2/)
    - [Exercise 2.1 - Exercise 2 Sub Exercise 1 Description](exercises/ex2#exercise-21-sub-exercise-1-description)
    - [Exercise 2.2 - Exercise 2 Sub Exercise 2 Description](exercises/ex2#exercise-22-sub-exercise-2-description)

  
**OR** Link to the Tutorial Navigator for example...

Start the exercises [here](https://developers.sap.com/tutorials/abap-environment-trial-onboarding.html).

**IMPORTANT**

Your repo must contain the .reuse and LICENSES folder and the License section below. DO NOT REMOVE the section or folders/files. Also, remove all unused template assets(images, folders, etc) from the exercises folder. 

## Contributing
Please read the [CONTRIBUTING.md](./CONTRIBUTING.md) to understand the contribution guidelines.

## Code of Conduct
Please read the [SAP Open Source Code of Conduct](https://github.com/SAP-samples/.github/blob/main/CODE_OF_CONDUCT.md).

## How to obtain support
Support for the content in this repository is available during the actual time of the online session for which this content has been designed. Otherwise, you may request support via the [Issues](../../issues) tab.

## License
Copyright (c) 2023 SAP SE or an SAP affiliate company. All rights reserved. This project is licensed under the Apache Software License, version 2.0 except as noted otherwise in the [LICENSE](LICENSES/Apache-2.0.txt) file.
