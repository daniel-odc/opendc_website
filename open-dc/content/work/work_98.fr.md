+++
title = "Plugin QGIS modélisation de trafic"
weight = 98
description = "Développement d’un plugin QGIS pour l’analyse de données de modélisation transports à système de coordonnées exotique."
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
	<div class="col-sm-3"><h4>Partenaires:</h4></div>
	<div class="col-sm-3">-</div>	
</div>	


<!-- Sector -->
<div class="row">
	<div class="col-sm-3"><h4>Secteur:</h4></div>
	<div class="col-sm-3"> <h4>Automatisation de process SIG</h4></div>
	<div class="col-sm-3"></div>
</div>	

<h4>Le contexte :</h4> 
<p>
Notre client a développé en interne un logiciel de modélisation de trafic routier et transports en commun sur la région Île de France. Cet outil utilise un système de coordonnées qui lui est propre et toute donnée générée ne peut être visualisée que par l’outil. Ceci posait problème quand les clients finaux demandaient de pouvoir visualiser les hypothèses et résultats des études commandées sur d’autres systèmes SIG.
</p>

<h4>Notre apport :</h4>
<p>
Nous avons développé un plugin <a href = "https://qgis.org/en/site/" target="_blank">QGIS</a> dédié permettant à notre client de charger ses données de modélisation (réseau de transport et points d’injection de demande) pour ensuite effectuer les opérations de conversions de coordonnées géographiques et transformer le système interne de notre client en système officiel français « Lambert 93 », et exporter les données au format standard ESRI Shapefile, reconnu par tout logiciel SIG. Le plugin permet aussi d’effectuer d’autres opérations telles que des agrégations et du formatage de données modélisées.
Nous avons finalement documenté le plugin, en termes d’installation et d’utilisation.

</p>

<h4>Les bénéfices pour notre client :</h4>
<p>
La solution logicielle de notre client est devenue compatible avec les standards de l’industrie SIG et toutes ses sorties sont maintenant facilement visualisées, améliorées et partagées via QGIS, ce qui le rend d’autant plus compétitif vis-à-vis de ses concurrents du marché. Le développement sous forme de plugin QGIS implique qu’il peut être utilisé par un nombre illimité d’employés sans coût supplémentaire. Toutes les autres fonctionnalités de QGIS peuvent également être utilisées pour rendre les résultats de sortie plus communicants pour leurs clients finaux.
</p>
