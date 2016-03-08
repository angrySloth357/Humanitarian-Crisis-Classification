## Humanitarian-Crisis-Classification in the Security Domain

This repository os part of a team effort to predict a country's vulnerability to a humanitarian crisis.  The complete repository is located [here](https://github.com/emilyhoughkovacs/humanitarian_unrest_classifier).

* [Slide Presentation](https://docs.google.com/presentation/d/1WgImQ5wSHe1FLMHrILH3z1NhyZJJyY8n57uhn4r5kzI/edit#slide=id.p4)
* [d3 Graphic](http://bit.ly/RefugeeMap)

This repository details a supervised machine learning model for predicting a country's vulnerability to a humanitarian crisis using features in the Security domain as a predictor.  This is part of a stacked classification model that also included Economic, Political, Environmental,

Welcome to Project McNulty. Our goal is to identify areas in the world that may be susceptible to humanitarian unrest, specifically focusing on crises that might prompt a mass migration of refugees.

The number of refugees moving out of a country will be standardized by their population and classified a value of 'at stress' (1) or 'not at stress' (0).

Our team will create supervised machine learning models to examine key factors that may lead to humanitarian unrest: economic, environmental and climatic, terrorism and national security, political and population demographics, and food. We will use pre-processing methods, choose an appropriate model, and use the output of individual predictions as features for a final model.

This project will be beneficial to anyone with interest in geopolitics. Both firms and individuals with international interests could use this graph to make educated business, travel, and life decisions. We hope to package the project as an easy-to-navigate interactive infographic.

We are sharing our data on a single database on one ec2 server. We are using Postico, a graphical interface, to locally connect to this shared postgres database.

Security & Terrorism

This feature is developed from a number of indices developed by think tanks and nonprofits such as the Institute for Economics and Peace (IEP) and the Council on Foreign Releations (CFR) that cover acts of terrorism, insurgencies, and border disputes. IEP's Global Peace Index (GPI) is also included in this feature. The data is sourced from a wide range of respected sources, including the International Institute of Strategic Studies, The World Bank, various UN Agencies, peace institutes and the EIU. Each of these indices are combined in a weighted model to produce an overall Security & Terrorism score.

Sources:

* Council on Foreign Relations (CFR), Invisible Armies Insugency Tracker
* Institute for Economics and Peace (IEP), Global Peace Index 2015, Global Terror Index 2015
* Uppsala Universitet, Depaterment of Peace and Conflict Research, Conflict Data Program - UCDP/PRIO Armed Conflict Dataset v.4-2015, 1946 – 2014

Additional Background Reading on Internally Displaced Persons and Refugees:

* Internal Displacement Monitoring Centre (IDMC)
* United Nations High Commission on Refugees
* Uppsala Universitet, Depaterment of Peace and Conflict Research, Conflict Data Program
