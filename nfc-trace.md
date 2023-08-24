---
layout: post
title: NFC-Trace
image: assets/images/nfc_Trace.jpg
nav-menu: true
---

<h2 id="content">Objectif de NFC-Trace </h2>
<hr />
<p> L’objectif du projet est de mettre en place un système permettant la lecture et l’écriture des tags NFC à l’aide du Raspberry Pi, d’un module NFC et de tags NFC. Ce système permettra aux étudiants d'interagir avec les ressources associées aux tags NFC de manière pratique et efficace.</p>
<div class="row">
	<div class="6u 12u$(small)">
		<h3>Étude du matériel</h3>
		<p>Cette tâche consiste à établir une évaluation approfondie du matériel nécessaire pour l’intégralité du projet NFC-Trace. Ici, les élèves devront réaliser un examen détaillé du matériel en prenant en compte la fonctionnalité et la compatibilité de ceux-ci. Si certains de ces composants s’avèrent non fonctionnels, incompatibles ou problématiques. Les élèves devront identifier et indiquer le nouveau matériel à utiliser afin d’assurer le bon déroulement du projet. Cette tâche est fondamentale pour garantir que tous les éléments du projet sont non seulement réalisables, mais aussi efficaces et sûrs.
</p>
	</div>
	<div class="6u$ 12u$(small)">
		<h3>Définir le format de lecture</h3>
		<p>Cette tâche consiste à déterminer la manière dont les informations stockées dans le tag NFC seront organisées et structurées afin de permettre une lecture correcte et une interprétation des données par le lecteur NFC.Plusieurs questions vont donc être posées.</p>
            <ul>
                <li>type de données ? ( url - texte - métadonnées …)</li>
                <li>structure de données ? (JSON - XML - … )</li>
            </ul>
	</div>


  
<div class="4u 12u$(medium)">
		<h3>Configurer les Raspberry Pi</h3>
		<p>Cette tâche consiste principalement à préparer les raspberry pi pour qu’ils puissent remplir leurs rôles spécifiques dans ce projet. Ici ils vont être utilisés pour lire des tags NFC via des modules NFC, afficher une interface utilisateur sur un écran tactile et potentiellement utiliser une caméra pour prendre en photos les ressources.</p>
	</div>
	<div class="4u 12u$(medium)">
		<h3>Implémentation de la lecture d'un Tag NFC</h3>
		<p>Cette tâche consiste à lire le contenu d’un tag NFC	en faisant communiquer un Raspberry pi avec un module NFC. Cette tâche nous permet d’avoir un système capable d'interagir avec des tag NFC avec pour but de récupérer des informations stockés dans ces Tags.</p>
	</div>
	<div class="4u$ 12u$(medium)">
		<h3>Implémentation de l'écriture d'un Tag NFC</h3>
		<p>Cette tâche consiste à créer le programme nécessaire sur un rasPberry Pi pour interagir avec un module NFC et écrire du contenu dans un tag NFC. Le but final de cette tâche est de faire en sorte que le Raspberry Pi soit capable de modifier les informations stockées dans un tag NFC conformément à la logique et aux données définies dans le programme.</p>
	</div>

 <h5>Une fois le projet terminé</h5>
 <div class="box">
	<p>Les étudiants pourront utiliser le Raspberry Pi équipé du module NFC pour lire les informations stockées dans les tags NFC. Grâce à cette lecture, les étudiants pourront vérifier à quelle ressource  un tag est relié. De plus, ils pourront également utiliser le Raspberry Pi pour écrire des informations dans les tags NFC. Cela leur permettra d'associer un tag NFC à une ressource spécifique ou de mettre à jour les données stockées dans le tag en fonction des besoins du projet.</p>
</div>
	<a href="https://docs.google.com/spreadsheets/d/1n8Yd__z0773qt-cNkLsTYXXuelVUgRiy4jZWDAqDDBY/edit#gid=674376377" target="_blank"><h2>Voir le diagramme sur google sheet</h2> </a>
	<br>
</div>
	<h2 id="content">Les Tags NFC </h2>
	<p>Les tags NFC (Near Field Communication) sont des dispositifs de communication sans fil qui permettent aux appareils électroniques de communiquer entre eux lorsqu'ils sont à proximité l'un de l'autre. Ils sont utilisés dans une variété d'applications allant des paiements sans contact aux accès sécurisés et bien plus encore. Nous allons explorer les caractéristiques, les avantages et les différences entre les tags NFC et la RFID (Radio-Frequency Identification).</p>
	<div class="row">
	<div class="10u 12u$(medium)">
		<h3>Qu'est-ce que le tag NFC et quel est son intérêt ?</h3>
		<p>Le tag NFC est un petit dispositif qui contient une puce électronique et une antenne. Il fonctionne en utilisant la technologie sans fil à courte portée pour établir une connexion avec d'autres appareils compatibles NFC. Le principal avantage du NFC réside dans sa simplicité d'utilisation, car il suffit de rapprocher deux appareils pour qu'ils communiquent, sans avoir besoin d'une alimentation externe pour le tag.</p>
<p>Selon SpringCard, le tag NFC Forum Type 2 (norme ISO/IEC 14443-3A) est particulièrement intéressant car il permet de stocker une petite quantité de données et est compatible avec une large gamme d'appareils NFC.

</p>
	</div>
	<div class="10u$ 12u$(medium)">
		<h3>Différences entre la RFID et le NFC</h3>
		<p>La RFID est une technologie similaire au NFC, mais elle présente quelques différences importantes. Selon Omnitec Systems, la principale différence réside dans la distance de communication et les applications pour lesquelles elles sont optimisées.</p>
		<ul>
			<li>Distance de communication : Le NFC fonctionne généralement à une distance maximale de quelques centimètres, tandis que la RFID peut fonctionner sur de plus grandes distances, allant jusqu'à plusieurs mètres, voire plus. </li>
			<li>Applications : Le NFC est principalement utilisé pour des applications nécessitant une communication de proximité, telles que les paiements sans contact et le partage d'informations entre appareils mobiles. La RFID, quant à elle, est utilisée pour le suivi d'objets ou d'animaux sur de plus grandes distances, comme dans la logistique ou l'identification d'animaux domestiques.</li>
		</ul>
	</div>
	<div class="10u$ 12u$(medium)">
		<h3>Avantages des tags NFC</h3>
		<p>Les tags NFC offrent plusieurs avantages significatifs :</p>
		<ul>
			<li>Simplicité d'utilisation : Comme mentionné précédemment, le simple fait de rapprocher deux appareils suffit pour établir une communication, ce qui rend l'utilisation du NFC très intuitive.</li>
			<li>Sécurité : Le NFC utilise des protocoles de sécurité avancés pour empêcher toute interception ou falsification des données échangées, ce qui en fait une option sûre pour les paiements et autres transactions sensibles. 
</li>
			<li>Compatibilité universelle : Les tags NFC fonctionnent avec une grande variété d'appareils, notamment les smartphones, les tablettes et les autres dispositifs compatibles NFC. </li>
			<li>Coût abordable : Les tags NFC sont généralement abordables, ce qui les rend accessibles à de nombreuses applications, y compris celles à faible budget.</li>
		</ul>
	</div>
 </div>

