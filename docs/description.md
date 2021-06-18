# EcoSafe: Industrial Water Effluent Monitoring Dashboard

## Problem Statement

Nearly 80% of world’s wastewater is dumped in rivers, lakes, and oceans. In most cases this wastewater is untreated, thereby affecting the quality of water worldwide. Industries discharge an estimated 300-400 megatonnes of waste into water bodies every year. Re-use of wastewater in agriculture is important for livelihoods of millions but is associated with serious health risks. Hence, improving the quality of water by effective monitoring of industrial waste effluents is the problem we are trying to solve.


## Solution

We are offering an Industrial Water Effluent Monitoring Dashboard, which has the ability to track water toxicity levels, alert the factory owners and government of the danger levels, ability to track the action taken and open a faster channel of communication between the concerned authorities.

This is a prospective approach towards identifying the industrial factories that are at danger levels to pollute river water and intimate the regulatory bodies and track the action taken by each stakeholder. 

Our solution requires installation of sensors in the exit pipelines of large industrial factories. These sensors would detect various parameters like pH, ammonia, chlorine, BOD etc in the wastewater. Through GPS signals, we would capture this data and aggregate it at a factory level. Using data science, we would clean and modify the data with the threshold values set as guidelines by the government and generate a Machine learning model to train on the said data, to determine threat level based on govt. standards. 


## Dashboard View

This data would then be used to generate heat maps for the factories and display them in different formats on the dashboard. 

- 1st format: Heat Map of the city with all the factories, indicating the threat level. As we zoom in to the specific location, we would be able to track a factory by its name and clicking on it will open a modal window, which would indicate the parameters and their value in comparison to the threshold limits decided by CPCB and SPCB. 

- 2nd format: It will be a tabular format, which would list all the factories covered, along with columns indicating the threat level, date of alert and the action taken. Clicking on a particular factory name would show additional data in relation to the parameters being monitored. 


## Communication Channel (Access level based)

- Based on the threat level, auto alerts will be triggered to the factory owners and the government, and the same is reflected on the dashboard with high. 
- These alert statuses of each factory are available to the public in the communication channel.
- Factory owners, only, can update any action taken by them and the government can directly track it and communicate on the same portal, to ensure speedy resolution of the problem.
- The updates on the actions taken are also updated in the channel for the public to view. 


## Public Access 

General public has access to only the Map and tabular view, with no access to the contact information or the on-going communication between factory and government. They can still see the status of the areas near each factory, their quality indexes and if the response action taken by the factory to mitigate the pollution through the dashboard.


### Private Access (Role based Access)

- Factory Owner: They can login to the app and view the alerts and update action taken by them. Access historical data pertaining to their individual factory.

- Government: They can login and track the action taken by factories and send emails to the factory from this portal. Government has access to data of all factories.
