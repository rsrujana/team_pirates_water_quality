# EcoSafe: Industrial Water Effluent Monitoring Dashboard

[![License](https://img.shields.io/badge/License-Apache2-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0)  [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/rsrujana3/team_pirates_water_quality/main?urlpath=Code%2FWater-Quality-main.ipynb)

Eco Safe, is a dashboard and a prospective approach towards identifying the industrial factories that are at danger levels to pollute river water and intimate the regulatory bodies and track the action taken by each stakeholder. This has been made and presented as part of a [hackathon](https://wit-ace.com/events/marquee/detail/660433-she-the-force-wit-ace-hackathon)

_Read this in other languages: [English](README.md), [한국어](./docs/README.ko.md), [português](./docs/README.pt_br.md)._


# Contents

- ECO Saver
  - Contents
  - [Short description](#short-description)
    - [What's the problem?](#whats-the-problem)
    - [How can we help?](#how-can-technology-help)
    - [The idea](#the-idea)
  - [Demo video](#demo-video)
  - [The architecture](#the-architecture)
  - [Project Wireframes](#project-wireframes)
  - [Long description](#long-description)
  - [Getting started](#getting-started)
  - [Built with](#built-with)
  - [Contributing](#contributing)
  - [Versioning](#versioning)
  - [License](#license)
  - [Acknowledgments](#acknowledgments)


## Short description

### What's the problem?

Nearly 80% of world’s wastewater is dumped in rivers, lakes, and oceans. In most cases this wastewater is untreated, thereby affecting the quality of water worldwide. Industries discharge an estimated 300-400 megatonnes of waste into water bodies every year. Re-use of wastewater in agriculture is important for livelihoods of millions but is associated with serious health risks. Hence, improving the quality of water by effective monitoring of industrial waste effluents is the problem we are trying to solve.

### How can we help?

We are offering an Industrial Water Effluent Monitoring Dashboard, which has the ability to track water toxicity levels, alert the factory owners and government of the danger levels, ability to track the action taken and open a faster channel of communication between the concerned authorities.

This is a prospective approach towards identifying the industrial factories that are at danger levels to pollute river water and intimate the regulatory bodies and track the action taken by each stakeholder. 

### The idea

Our solution requires installation of sensors in the exit pipelines of large industrial factories. These sensors would detect various parameters like pH, ammonia, chlorine, BOD etc in the wastewater. Through GPS signals, we would capture this data and aggregate it at a factory level. Using data science and AI, we would compare and clean the data, with the thresholds and generate ML model to build the logic to determine threat level based on govt. standards and train the model. 


## Demo video

[Shorter version](https://www.youtube.com/watch?v=8_0N5XBqOcY)
[longer version](https://www.youtube.com/watch?v=mZVQnQq41ek)


## The architecture

[Project Flowchart](https://github.com/rsrujana3/team_pirates_water_quality/blob/main/images/flowchart.PNG)

1. Collect the information sent periodically by the sensor systems fixed at factories outlets, which will be stored in database like IBM cloud.
The user navigates to the dashboard and search for the location they choose to look at.
2. They are re-directed to the map view where they can see the visualisations of real-time data, plotted as a geaographical heat map. 
3. There is also an information section to the right with the details of the risk level around factories, along with options to filter based on risk level and parameters.
4. The data will be processed and then be used for ML model training, which renders the details shown in the dashboard.


## Project Wireframes

Given here is the link to [wireframes](https://www.figma.com/file/SrxA8MCdMpyrGGfi7h8TRt/EcoSaver?node-id=0%3A1) , as to how the dashboard is supposed to look like.


## Long description

[More detail is available here](https://github.com/rsrujana3/team_pirates_water_quality/blob/main/docs/description.md)


## Getting started

In this section you add the instructions to run your project on your local machine for development and testing purposes. You can also add instructions on how to deploy the project in production.

- Open the Jupyter notebook [here](https://mybinder.org/v2/gh/rsrujana3/team_pirates_water_quality/main?filepath=Code%2FWater-Quality-main.ipynb)
- Sample-IBM-dashboard [here](https://dataplatform.cloud.ibm.com/dashboards/00f33ee8-db27-44f0-86b0-29ee3d7d6d7c?project_id=bbbbb04a-d210-467c-8836-66c64ea5262a&context=cpdaas&mode=consumption)


## Built with

- [IBM Cloud Functions](https://cloud.ibm.com/catalog?search=cloud%20functions#search_results) - The compute platform for handing logic and dashboard
- [Jupyter Notebook](https://mybinder.org/v2/gh/rsrujana3/team_pirates_water_quality/main?filepath=Code%2FWater-Quality-main.ipynb) - The Jupyter notebook for data visualization


## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.


## Versioning

For the versions available, see the [tags on this repository](https://github.com/your/project/tags).


## License

This project is licensed under the Apache 2 License - see the [LICENSE](LICENSE) file for details.
