+++
title = "Bilan carbone mobilités professionnelles"
weight = 79
description = "Calcul et visualisation du bilan carbone des communes d'Île de France, lié à leurs déplacements professionnels."
icon = "/img/work/icon_w79.jpg"
image = "/img/work/image_w79.jpg"
logo_client = "/img/clients/icon_odc_stormy.jpg"
translationKey = "work_79"
+++

<!-- Client -->
<div class="row">
	<div class="col-sm-3"><h4>Client:</h4></div>
	<div class="col-sm-3"><a href = "https://www.open-dc.com" target="_blank"> <img src="/img/clients/icon_odc_stormy.svg" width="150px"/></a></div>	
</div>	

<!-- Partner -->
<div class="row">
	<div class="col-sm-3"><h4>Partenaires:</h4></div>
	<div class="col-sm-3">-</div>	
</div>	

<!-- Sector -->
<div class="row">
	<div class="col-sm-3"><h4>Secteur:</h4></div>
	<div class="col-sm-3"> <h4>Développement web</h4></div>
	<div class="col-sm-3"></div>
</div>	

{{<video autoplay="yes" src="/img/work/video_w79.webm" controls="yes">}}<br>
<br></br>

<h4>Le contexte :</h4> 
<p>

Les émissions de gaz à effet de serre liées aux transports représentaient 31% des émissions en France en 2019, dont la quasi-totalité provient du transport routier. Comprendre ces déplacements (origine et destination du trajet de bout en bout, mode de transport (voiture, métro etc.) emprunté, régularité, motif etc.) permettrait d’aider à prendre les mesures nécessaires afin de baisser ces émissions sur un territoire donné. Le secteur des transport présente de nombreux motifs de déplacements. Parmi eux, le motif domicile-travail (DT) est significatif en termes de volume. Surtout, c’est un type de déplacements pour lequel des données de qualité sont disponibles.
Une fusion entre les données de déplacements DT par mode de transport, des données de distances de déplacements et des données d’émissions carbone moyennes par km et type de véhicule nous permettrait de calculer le bilan carbone généré par chaque déplacement DT et donc le bilan carbone global de chaque commune, lié aux déplacements DT de ses résidents ou de ses employés.

</p>

<h4>Notre apport :</h4>
<p>

Nous avons collecté et fusionné trois sources de données : les données de déplacements domicile-travail de l’<a href="https://www.insee.fr/fr/statistiques/5395749?sommaire=5395764#consulter" target="_blank" >INSEE 2018</a>, les données d’émissions carbone moyennes par mode de transport issues de l’<a href="https://avenirclimatique.org/calculer-empreinte-carbone-trajet/" target="_blank" >ADEME</a> (toutes deux en open data), ainsi que les données de distances entre villes issues de l’<a href="https://developers.google.com/maps/documentation/directions/" target="_blank" >API Direction de Google Maps</a>. Cette fusion a permis le calcul (simplifié !) du bilan carbone de chaque couple origine-destination (OD) en région parisienne. L’agrégation des OD a permis le calcul du bilan carbone moyen de chaque ville, qu’il soit lié au déplacement de ses résidents ou de ses employés (les différences sont intéressantes !).
Nous avons ensuite développé une application web en React (<a href="https://mobpro-carbone.com" target="_blank" >mobpro-carbone.com</a>), permettant à tout utilisateur d’extraire un maximum d’information de ces données fusionnées de façon simple et ergonomique.

</p>

<h4>Les bénéfices pour notre client :</h4>
<p>

L’application web est accessible gratuitement et la méthodologie de calcul y est documentée de façon exhaustive. Cette application permet à toute ville de région parisienne de voir où elle se situe en comparaison avec les autres villes en termes d’émissions carbone liées à ses déplacements DT. Cette application met également à disposition les données sources de flux, temps de parcours et distances.

Lien vers l’application : <a href="https://mobpro-carbone.com" target="_blank" >mobpro-carbone.com</a>.

</p>
