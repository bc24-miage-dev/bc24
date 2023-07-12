---
title: Présentation
layout: landing
data: 'Présentation générale du Méta Projet'
image: assets/images/presentation.jpg
nav-menu: true
---

<!-- Main -->
<div id="main">

<!-- One -->
<section id="one">
	<div class="inner">
		<header class="major">
			<h2>Objectif</h2>
		</header>
		<p>L'objectif principal de ce méta projet est de réunir les différentes promotions des L3, M1 et M2 afin de réaliser un POC d'un système de traçabilité de fabrication de produits, de manière totalement sécurisée. Un POC c'est un "Proof Of Concept", autrement dit c'est l'étude de la faisabilité et de la viabilité d'un projet avant de s'y engager.
		<br>
		Pour ce faire, nous allons utiliser des tag NFC afin d’identifier les différentes ressources, des raspberry pi pour la lecture de celles-ci, des NTFs qui vont être reliées aux différents tags NFC ainsi qu’une blockchain ou nous allons stocker tous nos NFTs ce qui va nous permettre d'avoir un suivi complet des ressources ainsi que des artefacts.</p>
	</div>
</section>

<!-- Two -->
<section id="two" class="spotlights">
	<section>
		<a href="generic.html" class="image">
			<img src="{% link assets/images/Raspberry_Pi.jpg %}" alt="" data-position="center center" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Raspberry Pi</h3>
				</header>
				<p>C’est un nano ordinateur monocarte qui peut également être utilisé comme lecteur NFC. Pour ce faire, on a besoin d’un module nfc (une carte d’extension ou un module USB) puis le raspberry pi va pouvoir scanner les puces nfc grâce à un script afin de lire et/ou traiter les différentes données. </p>
				<ul class="actions">
					<li><a href="generic.html" class="button">Learn more</a></li>
				</ul>
			</div>
		</div>
	</section>
	<section>
		<a href="generic.html" class="image">
			<img src="{% link assets/images/NFC_tag.png %}" alt="" data-position="top center" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Tag NFC</h3>
				</header>
				<p>C'est une technologie de communication sans fil qui est utilisée pour l’échange d’informations entre appareils compatibles NFC. En général nous utilisons cette technologie afin de faire des paiements mobile (apple pay), des transferts de données ou encore des accès sécurisé (verrouillage/déverouillage de porte).
</p>
				<ul class="actions">
					<li><a href="generic.html" class="button">Learn more</a></li>
				</ul>
			</div>
		</div>
	</section>
	<section>
		<a href="generic.html" class="image">
			<img src="{% link assets/images/nft.jpg %}" alt="" data-position="25% 25%" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>NFT</h3>
				</header>
				<p>Un NFT est un token numérique unique qui est utilisé pour représenter la propriété ou la provenance d’un bien immatériel dont le droit d'usage ou de propriété est rattaché au patrimoine d'une personne
(actif numérique). Lorsqu’un NFT change de propriétaire, la transaction est enregistrée dans une blockchain, ce qui permet de suivre la propriété et l’historique des transactions de celui-ci. Chaque NFT peut être vérifié de manière transparente pour confirmer son authenticité, sa provenance et sa propriété. Ainsi un NFT est unique, indivisible et identifiable.
 </p>
				<ul class="actions">
					<li><a href="generic.html" class="button">Learn more</a></li>
				</ul>
			</div>
		</div>
	</section>
</section>

<!-- Three -->
<section id="three">
	<div class="inner">
		<header class="major">
			<h2>Use cases</h2>
		</header>
		<div class="table-wrapper">
	<table>
		<thead>
			<tr>
				<th>Cas d'utilisations</th>
				<th>Description</th>
			</tr>
		</thead>
		<tbody>
			<tr>
				<td>Cas 1</td>
				<td>En tant que constructeur, je peux prendre possession d’une ressource en scannant son tag NFC. (Change le propriétaire du NFT et ajoute un nouveau bloc avec le propriétaire actuel)
</td>
			</tr>
			<tr>
				<td>Cas 2</td>
				<td>En tant que constructeur, je peux consommer les NFTs des ressources pour les combiner dans un nouveau NFT d’artefact. Ce NFT est bien entendu associé à un tag NFC.</td>
			</tr>
			<tr>
				<td>Cas 3</td>
				<td>En tant qu’acheteur d’artéfact, je peux obtenir des informations de traçabilité sur toutes les ressources utilisées pour la création de mon artefact juste en scannant le tag NFC correspondant.
</td>
			</tr>	
		</tbody>
	</table>
</div>
		<ul class="actions">
			<li><a href="home.html" class="button next">Retour</a></li>
		</ul>
	</div>
</section>

</div>
