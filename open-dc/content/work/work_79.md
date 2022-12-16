+++
title = "Commuters carbon emissions"
weight = 79
description = "Visualisation dashboard of commuter flows carbon emission in the Paris Region."
icon = "/img/work/icon_w79.png"
image = "/img/work/image_w79.png"
logo_client = "/img/clients/icon_odc_stormy.svg"
translationKey = "work_79"
+++

<!-- Client -->
<div class="row">
	<div class="col-sm-3"><h4>Client:</h4></div>
	<div class="col-sm-3"><a href = "https://www.open-dc.com" target="_blank"> <img src="/img/clients/icon_odc_stormy.svg" width="150px"/></a></div>	
</div>	

<!-- Partner -->
<div class="row">
	<div class="col-sm-3"><h4>Partners:</h4></div>
	<div class="col-sm-3">-</div>	
</div>	

<!-- Sector -->
<div class="row">
	<div class="col-sm-3"><h4>Sector:</h4></div>
	<div class="col-sm-3"> <h4>Web development</h4></div>
	<div class="col-sm-3"></div>
</div>	

<h4>The context:</h4> 
<p>

The world global warming and current energy crisis are pushing us, people, companies and public bodies to limit our carbon emissions. To do so, we first need to understand their sources before being able to reduce them. In France, 30% of the carbon emissions come from the transport industry. The transport in France has many purposes, the commute being a significant one in terms of volume. Our chance is that quality data about commuting flows is available as open data. A fusion between commute volume and mode choice data, distance data and average carbon emission per transport mode data would enable us to estimate the carbon emissions of each commute trip in the Paris region and hence of each city.

</p>

<h4>What we did:</h4>
<p>

We have collated and merged three data sources, commuters data from <a href="https://www.insee.fr/fr/statistiques/5395749?sommaire=5395764#consulter" target="_blank" >INSEE</a> and average carbon data from <a href="https://avenirclimatique.org/calculer-empreinte-carbone-trajet/" target="_blank" >ADEME</a> (both open data), and distance data from the <a href="https://developers.google.com/maps/documentation/directions/" target="_blank" >Google Maps Direction API</a>. This merge enabled the (simplified!) calculation of the carbon emission of any city origin-destination couple in the Paris region. Then for each city, we have computed the global average, whether the carbon emissions were made by the city residents or employees (interesting differences show up!).
We have then developed a React application, available to anyone at <a href="https://mobpro-carbone.com" target="_blank" >mobpro-carbone.com</a> that offers a user-friendly interface enabling the access to all insights from the full dataset.

</p>

<h4>The value for our client:</h4>
<p>
The React application has been made freely available to anyone and the methodology is fully documented in the application. This application enables any city of the Paris region to benchmark against other cities in terms of carbon emissions, but also gives the keys to understand the reasons behind a high carbon emission (travel times, number of commuters, mode shares).

More info at <a href="https://mobpro-carbone.com" target="_blank" >mobpro-carbone.com</a>.

</p>
