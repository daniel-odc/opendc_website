+++
title = "Data Lake Network Rail"
weight = 87
description = "Analyse SIG pour déduire des géolocalisations d'infrastructure ferroviaire"
icon = "/img/work/icon_w87.png"
image = "/img/work/image_w87.svg"
logo_client = "/img/clients/icon_network_rail.png"
# next_page = "/work/work_02.html"
# prev_page = "/work/work_94.html"
translationKey = "work_87"
+++

<!-- Client -->
<div class="row">
	<div class="col-sm-3"><h4>Client:</h4></div>
	<div class="col-sm-3"><a href = "https://www.networkrail.co.uk/" target="_blank"/> <img src="/img/clients/icon_network_rail.svg" width="150px"/></a></div>
	<!-- <div class="col-sm-3"></div> -->
</div>	

<!-- Partner -->
<div class="row">
	<div class="col-sm-3"><h5>Partenaires:</h4></div>
	<!--  <div class="col-sm-3"> <h5><a href = "http://www.cdvia.fr/" target="_blank">CDVIA</a> </h4> </div>-->
	<div class="col-sm-3"><a href = "http://www.cpmsgroup.com/" target="_blank"/> <img src="/img/clients/icon_cpms.svg" width="96px"/></a></div>
	<div class="col-sm-3"><a href = "https://www.ey.com/en_uk" target="_blank"/> <img src="/img/clients/icon_ey.svg" width="96px"/></a></div>
</div>	

<!-- Sector -->
<div class="row">
	<div class="col-sm-3"><h5>Secteur :</h4></div>
	<div class="col-sm-3"> <h5>Géoprocessing et analyse de données</div>
	<div class="col-sm-3"></div>
</div>	

<h4>Le contexte :</h4> 
<p>
Notre client Network Rail gère l’infrastructure ferroviaire au Royaume Uni. Les propriétés de son matériel (rails, caténaires etc.) sont recensées dans une base de données centralisée. Par ailleurs, des systèmes de mesure modernes embarqués sur les trains empruntant l’infrastructure permettent de mesurer certaines propriétés du matériel, comme la hauteur ou le désaxage des caténaires par exemple. Ces systèmes permettent de mesurer de façon précise la géolocalisation du matériel mais échouent en général à identifier la référence du matériel. La base de données centrale en revanche, contient la référence du matériel mais rarement sa géolocalisation. Notre équipe (CPMS, EY et OpenDC) a développé un process innovant permettant de déduire l’information manquante à l’échelle du Royaume Uni dans les deux sources et les mettre à disposition de notre client dans un tableau de bord sécurisé.
</p>

<h4>Notre apport :</h4>
<p>
Nous avons collecté des données historiques de mesures disponibles dans plusieurs centaines de fichiers Excel fournis par Network Rail. Nous avons nettoyé cette donnée et développé un algorithme de géoprocessing permettant de déduire les informations de géolocalisation manquantes dans la base de données centrale. Nous avons pour cela combiné l’utilisation d’expressions régulières, détection de motifs, opérations géométriques basiques et des algorithmes de process SIG avancés pour déduire et compléter la grande majorité de l’information manquante dans la base de données centrale.
</p>

<h4>Les bénéfices pour notre client :</h4>
<p>
Notre produit permet désormais à notre client d’identifier les structures dont les mesures présentent des défauts. La référence et la géolocalisation de la structure peuvent facilement être extraites et ainsi du personnel peut être envoyé sur site pour réparer ou remplacer la structure défectueuse. Ceci limite grandement le risque de casse, qui lorsqu’il arrive, peut entraîner des coûts pour notre client de plusieurs millions de livres.
</p>
