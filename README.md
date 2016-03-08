## Humanitarian-Crisis-Classification in the Security Domain

This repository os part of a team effort to predict a country's vulnerability to a humanitarian crisis.  The Security domain is based on a number of indices developed by think tanks and nonprofits such as the Institute for Economics and Peace (IEP), the Council on Foreign Releations (CFR), and the Uppsala Universitet, Department of Peace and Conflict Research.  The data is sourced from a wide range of respected sources, including the International Institute of Strategic Studies, The World Bank, various UN Agencies, peace institutes and the EIU. Each of these indices are combined in a weighted model to produce an overall Security & Terrorism score.

The complete project repository is located [here](https://github.com/emilyhoughkovacs/humanitarian_unrest_classifier).

* [Slide Presentation](https://docs.google.com/presentation/d/1WgImQ5wSHe1FLMHrILH3z1NhyZJJyY8n57uhn4r5kzI/edit#slide=id.p4)
* [d3 Graphic](http://bit.ly/RefugeeMap)

Humanitarian crises are often short-notice, highly volatile events that leave national policymakers, non-governmental organizations, and other humanitarian aid providers making decisions reactively. This approach not only has a high financial cost; it is also costly in terms of the hidden and enduring social issues that arise out of these crises.

For example, since 2012, the United States government has allocated over $4.5 billion USD in unplanned spending for foreign assistance to Syrian refugees. European countries are also diverting funds from their budgets to deal with the burgeoning costs of the growing Syrian refugee crisis. Had policymakers been advised of the impending crisis early enough, they could make proactive decisions to tackle the crisis.

For our project, we investigated and developed several proof-of-concept classification models to identify nations at stress and therefore vulnerable to humanitarian crises if (or when) a precipitating event, such as war, economic recession, political turmoil, environmental or natural disaster, etc., occurs.

What is a nation at stress? For this study, we accepted the Norwegian Refugee Council (NRC) Internal Displacement Monitoring Centre’s model on displacement that identified four drivers (root causes or stressors) and a precipitating tipping point (trigger):

* Environmental: including desertification and damming of tributaries.
* Social: such as limited education opportunities; inter-communal tensions
* Political: for example, poor urban planning and corruption.
* Economic: including poverty and lack of access to markets.

The tipping point:

* Proximate precipitating events that leave people with little choice but to flee their homes. These are visible events in the wider environment that can threaten people’s physical or economic security.

The intent of this effort is not to predict the tipping points, but to identify those nations in which the drivers for human displacement are present. Follow-on development could see a dynamic and live-feed classification methodology to identify nations at stress 2-3 years out, affording governments and NGO’s opportunities to implement directed risk mitigation programs as applicable.
Security & Terrorism

#Data Sources:

* Council on Foreign Relations (CFR), [Invisible Armies Insugency Tracker](http://www.cfr.org/wars-and-warfare/invisible-armies-insurgency-tracker/p29917)
* Institute for Economics and Peace (IEP), [Global Peace Index 2015](http://economicsandpeace.org/wp-content/uploads/2015/06/Global-Peace-Index-Report-2015_0.pdf),  [Global Terror Index 2015](http://economicsandpeace.org/wp-content/uploads/2015/11/Global-Terrorism-Index-2015.pdf)
* Uppsala Universitet, Depaterment of Peace and Conflict Research, Conflict Data Program - [UCDP/PRIO Armed Conflict Dataset v.4-2015, 1946 – 2014](http://www.pcr.uu.se/research/ucdp/datasets/ucdp_prio_armed_conflict_dataset/)

#Additional Background Reading on Internally Displaced Persons and Refugees:

* [Internal Displacement Monitoring Centre (IDMC)](http://www.internal-displacement.org/)
* [United Nations High Commission on Refugees](http://www.unhcr.org/cgi-bin/texis/vtx/home)
* [Uppsala Universitet, Depaterment of Peace and Conflict Research, Conflict Data Program](http://www.pcr.uu.se/research/ucdp/)
