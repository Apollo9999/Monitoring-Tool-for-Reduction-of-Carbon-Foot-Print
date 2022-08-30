
#Monitoring and Reduction of Carbon and Methane Gas Leaks

The world is moving to a Low carbon centered economy. The countries on the planet and top 500 companies are already voluntary commited to reach net zero carbon. More carbon will mean higher prices. The price of the carbon credits will increase every year. Net Zero carbon is important. We are Witnessed over the last 2 decades before climate change becomes irreversible. Methane is a large contributor to global warming 84 times more potent than CO2 and there is a lack of accountability for large pollution events, especially by the coal/fossil and gas industry

With the advent of Latest Technology satellite imaging has recently allowed to keep track of methane emissions close to real-time. However, access to the data and the potential methane leak event is still complicated. We think we can make that simpler so people can be aware of new leaks as they arrive and enable them to take actions.

Objectives Achieved In This Project So Far are listed below 

practical, affordable, fast which also could give real time statistics of the world about carbon, at level of individuals and companies, countries, supporting to reach goals of carbon reduction and against climate change, in a world economy based on carbon. 5ire: the carbon exchange market the world needs.

What  Our Solution does

The Project  tool motive and intent  uses satellite data from (Sentinel 5P and other sources) to automatically detect new potential methane leaks by clustering abnormal emissions and linking them to the fossil infrastructure.

An easy UI allows then everyone to look at recent methane events and get more information on what happens: criticality of event, size, location, visual images.

We hope that gives an easy tool for people to track and then easily raise awareness on such events as they unfold
How we built it

    Use Google Earth Engine to access Methane (CH4), IR and wind data
    Detect methane anomalous level and extract all hotspots
    Link these "hotspots" to the fossil infrastructure (mines, plants and pipelines)
    Assess the link between the event and the infrastructure and create a criticality score for events
    Automate the pipeline using Azure function so it refreshes daily
    Create a user-friendly UI to be able to monitor all events detected with all required contextual information

Ideation to Prototype Stage Challenging Aspects 

 Google Earth Engine is not so user friendly and exporting data from it is challenging
 Identifying methane clusters was challenging. We think we can still improve the detection with more complex logic by better including infrared and with more complex models

Solution possibilities 
  Detect model for Methane hotspot linked to fossil infrastructure
  Developed an E2E pipeline on Azure for daily refresh
  An easy-to-use UI that run and gets refreshed automatically that can already be used

Latest Technologies Used 

Working with Geosatellite data is difficult due to the size and geospatial subtleties
Methane data is hard to access and any initiative to make it easier to work on it will be helpful to others.


Future Scope  for Reduction of Carbon and  Methane Leaks 

    Get feedback on current tools
    Work on improving model and especially how to best link detected events with a precise source
    Add a way to easily share detected hotspots to social medias (e.g. Twitter)
