+++
title = "Transport modelling QGIS Plugin"
weight = 98
description = "QGIS plugin development of transport modelling data in specific coordinate systems."
icon = "/img/work/icon_w98.jpg"
image = "/img/work/image_w98.jpg"
# logo_client = "/img/clients/icon_XXX.jpg"
# next_page = "/work/work_02.html"
# prev_page = "/work/work_94.html"
translationKey = "work_98"
+++

<!-- Client -->
<div class="row">
	<div class="col-sm-3"><h4>Client:</h4></div>
	<div class="col-sm-3"><a href = "https://www.cdvia.fr/" target="_blank"> <img src="/img/clients/icon_cdvia.svg" width="150px"/></a></div>	
</div>	

<!-- Partner -->
<div class="row">
	<div class="col-sm-3"><h4>Partners:</h4></div>
	<div class="col-sm-3">-</div>	
</div>	

<!-- Sector -->
<div class="row">
	<div class="col-sm-3"><h4>Sector:</h4></div>
	<div class="col-sm-3"> <h4>GIS processing automation</h4></div>
	<div class="col-sm-3"></div>
</div>	

<h4>The context:</h4> 
<p>
Our client uses an internal traffic modelling tool to model the private and public transportation demand and network in the Paris region. This internal tool uses its own coordinate system and all data it uses can only be visualised and processed within the internal tool. This was becoming an issue when their end clients were asking to be able to integrate their modelling assumptions in their own GIS software.
</p>

<h4>What we did:</h4>
<p>
We developed a dedicate <a href = "https://qgis.org/en/site/" target="_blank">QGIS</a> plugin where our client can load their modelling data (transport network and demand injection nodes) and that operates the coordinates conversion operations to transform the internal coordinate system into the French official “Lambert 93” coordinate system and export the data into standard ESRI Shapefile format files, that could be loaded by any GIS software. The plugin also processes other operations such as modelling results aggregation and formatting.
We finally documented the plugin with an installation and use tutorial.

</p>

<h4>The value for our client:</h4>
<p>
Our client software solution became compatible with the GIS industry standards and all outputs could easily be shared with their end clients, which turned it more competitive. The use of a QGIS plugin meant that it could be used by any people in the company at no extra cost. All other QGIS functionalities can also be used to improve styles for more attractive outputs for their end clients.
</p>
