## Machine learning algorithms for traffic count data anomaly detection

* The context

Our client operates the road network in the Val-de-Marne department, bordering Paris. Over the past years, they contracted multiple suppliers to survey vehicle counts on their network. This data has been provided in different formats for each supplier, and for some of them, no quality checks were carried out on the final data.
Our client wanted to consolidate all this data into a unified database and implement automated testing to verify the quality of the count data and, where possible, automatically correct the outliers.

* What we did

We first developed dedicated scripts to ingest the data from the various suppliers. Over 1,000 Excel files were ingested, with their relevant information extracted and structured.
We developed a machine learning process based on time-series analysis to detect inconsistencies and outliers in the data. When possible, we corrected the data using trends derived from past and future observations. We delivered a structured, unified database containing all historical count data, maintaining both the raw and corrected data.

* The value for our client

The information provided by several suppliers over the past years could now be evaluated, checked, and reused. Our client can use the structured and corrected data in their own GIS environment, allowing them to query all their historical traffic count data from a single source. This has made appraising their traffic reduction policy much easier and more scientific.

## Paris 2024 Transport and Mobility team

* The context

The organisation of the Paris 2024 Olympic Games required outstanding expertise in transport and crowd modelling, GIS processing, and project management. The Transport and Mobility (TRM) team contacted OpenDC's director a year before the Games to discuss the opportunity of joining the team until the event.

* What we did
 
Working on the organisation of the Olympics in Paris is a once-in-a-lifetime opportunity. OpenDC's director accepted this proposal and reduced OpenDC's activity for a year to assist the TRM team with organising transportation for spectators and accredited personnel during the Games.
We collaborated with local authorities across all the host cities (Paris, Marseille, Nice, Lyon, Saint-Étienne, etc.) to create the spectators' transport plan. We assisted the team with technical tasks such as managing and building the GIS database, estimating travel times during the Games (considering Olympic Lanes), locating and designing the wayfinding signage, and defining optimal itineraries for athletes' travel, among other responsibilities.

* The value for our client

Transportation during the Paris Olympics was widely recognised as a major success. This was the result of strong collaboration between all stakeholders—public and private—and a committed team within the Olympic Committee, where every member, including OpenDC's director, brought their skills and dedication.

## Crowd modelling for multi-education site in Paris

* The context

The French top-tier agronomic engineering school AgroParisTech relocated in 2022 from the 5th arrondissement of Paris to the scientific cluster of Plateau de Saclay (south of Paris). The historic building in central Paris was ceded to [Galileo Global Education](https://www.ggeedu.fr/) and will host various educational institutions, ranging from business schools to the renowned theatre programme "Cours Florent."
The expected number of students is substantial, as are the site constraints, including narrow corridors, doors, and a protected building structure.
Our client contacted OpenDC to conduct a crowd modelling analysis to ensure that the environment's design could accommodate the arrivals and departures of staff and students during peak times.

* What we did

We gathered all assumptions regarding space design and student schedules. We developed a dynamic pedestrian flow model to simulate peak-time arrivals and departures of students, highlighting bottlenecks and estimating potential congestion and delays.
We ran multiple scenarios to propose routing solutions that minimised crowd density and ensured comfort and safety for students throughout the building.

* The value for our client

Thanks to our analysis, our client was able to anticipate congestion risks and their locations. They subsequently updated their building circulation plan. The quantitative analysis based on the revised circulation plan reassured stakeholders that the planned schedule and available space would guarantee a high level of comfort and safety for future students and staff.

****Web platform for traffic count data analysis and visualisation

* The context

Our client has been collecting traffic count data for the past 30 years in the Paris region and across France. This invaluable data source is spread across hundreds of thousands of files, making it cumbersome to locate historical data for a given location on the road network.
They approached OpenDC for assistance in consolidating and structuring this data and enabling access through a secure web platform.

* What we did

We developed a process to extract the data from multiple files and structured it into a unified database. Additionally, we created a web application and an API to secure access to the platform, enable ingestion of new data from local files, and provide intuitive and seamless data visualisation and analysis through the platform's user interface.
The front-end was developed with React.js, the API and back-end with Flask. The Prophet library for time series analysis was used to detect and correct inconsistencies in the count data.

* The value for our client

Our client now has easy access to their data for developing models and conducting analyses. They can also grant access to the platform to their end clients, allowing them to retrieve traffic count data they have purchased. This eliminates the risk of data loss caused by individuals leaving the organisation and taking with them knowledge about the data's storage locations.