# Devoir-rendre

**Question de cours **

Le terminal. : Un terminal est une interface textuelle avec l'ordinateur. 
Elle sert à taper des commandes, manipuler des fichiers, exécuter des programmes et aussi ouvrir des documents. 

Element de mise en page README.md : 
 Le titre (heading) sert à rendre le texte plus lisible et aident à diviser les sujets. Pour créer un titre, il suffit d'ajouter un à six symboles  diez (#) avant le texte de titre. Le nombre de diez que ajoutez détermine la taille de l'intitulé.
L’hyperlien (hyperlink) sert à retirer un utilisateur sur un autre site. Un lien est créé par  en plaçant le texte du lien entre crochets [ ], puis en plaçant l'URL entre parenthèses ( ). Il est aussi possible d' utiliser  le raccourci clavier Command+K pour créer un lien. Lorsqu’un texte a été sélectionné, on peut  coller une URL à partir de votre presse-papiers pour créer automatiquement un lien à partir de la sélection.
L'image est utilisée pour afficher une information pictoriale. Pour insérer une image, on peut ajouter un point d’exclamation (!) et en entourant le texte alt de [ ]. Ensuite, mettre le lien de l'image entre parenthèses ().

PX, VW et EM
Les trois éléments mentionnés ci-dessous sont des unités de CSS qui permettent de spécifier la taille, telles que la taille de la police, la largeur, la hauteur, la largeur de la bordure, le rayon de la bordure, etc. 
	PX renvoie au mot pixel qui désigne les petits points ou carrés qui composent une image sur un écran d'ordinateur. Plus il y a de pixels, plus l'image semble réelle ou précise. Inventé en 1969, le mot pixel vient de “pictures” en anglais , ou “pics”. En css, les px sont des unités de taille fixe qui ne changent pas avec la taille de l'écran et ne sont pas personnalisables. Dans ce cas on parle de l’unité “absolue”. Il a été déterminé que chaque écran à sa propre taille de pixel em : taille relative à l’élément parent ; 1em = 16px %. 

	VW vw signifie Viewport Width (largeur de la fenêtre) et représente un pourcentage de la largeur de la fenêtre. Le nombre placé avant vw est le pourcentage de la largeur de la fenêtre d'affichage que représente cette longueur. Par exemple, si on écrit 10vw, cela représente une longueur de 10 % de la largeur de votre fenêtre.
La fenêtre d'affichage n'est qu'un terme fantaisiste pour désigner la taille de votre écran. Ainsi, si vous êtes sur un grand ordinateur de bureau d'une largeur de 1920px, 10vw représente 192px. En revanche, sur un téléphone mobile d'une largeur de 300px, 10vw ne représente que 30px.

	L'em est une mesure de police de caractères qui a été définie à l'origine comme une mesure entre le haut et le bas du "M" majuscule. Cependant, aujourd'hui, un em est une mesure dynamique basée sur la valeur de la taille de point de la propriété de taille de police. Par exemple, en CSS, si vous définissez la taille de la police de H1 à 1,2em, la taille de son texte sera supérieure de 20 % à la taille de la police qu'il hérite de l'élément parent ou de la propriété de police par défaut.  La taille de police dans est souvent utilisée pour les caractéristiques typographiques telles que les en-têtes, les textes, les articles, et les caractéristiques typographiques telles que les marges, le padding, ainsi que le contenu.	
Par exemple dans un cas où la taille habituelle de la police dans Google Chrome est fixée à 16 px, 1 em = 16 pixels. Donc, mathématiquement, la taille de la police du h2 est de 48px (16 * 3), et de 32px pour le h3 (16 * 2).

API 
Nous avons ici un API du site https://www.univ-fcomte.fr/
Cette API renvoie un une vidéo de bienvenue issue de youtube incorporée dans le site https://www.univ-fcomte.fr/. Elle sert à récolter les informations des internautes sur le site en ce qui concerne les heures de visite, la durée de vue, la localisation, le type de navigateur et appareil etc. 

devtools://devtools/bundled/devtools_app.html?remoteBase=https://chrome-devtools-frontend.appspot.com/serve_file/@603c1cb86aff29563721da2a6351c0d08865350d/&can_dock=true#:~:text=https%3A//www.youtube,Xqzmszoh6fBgxQJc5meaZQ%26vm%3DCAQQARgCOjJBTzY4R1pHalJ1VXQ3cEtDTWZOOGxPd1ZhZ1lWSG5iRl9LUVQ5NmFJTVVUOE9tb2VxZ2JXQVBta0tESklWaGNnNnRjXzdfY2xvV0tTVHdjeExTM2VvZG1EYUZvdXU0akRLTGhoRkNvbXdCLTIyb0dtN2JUaDdCcVRNRmNXbWtkMVgwdllJaGwyTmxJaAE

Commit :  La commande "commit" est utilisée pour enregistrer des modifications dans un dépôt local.
Il est important d'indiquer explicitement à Git les changements à  inclure dans un commit avant de lancer la commande "git commit". Cela signifie qu'un fichier ne sera pas automatiquement inclus dans le prochain commit juste parce qu'il a été modifié. Au lieu de cela, il est impératif d’utiliser la commande "git add" pour marquer les changements souhaités.
Un commit n'est pas automatiquement transféré au serveur distant. L'utilisation de la commande "git commit" ne fait que sauvegarder un nouvel objet commit dans le dépôt Git local. L'échange de commits doit être effectué manuellement et explicitement (avec les commandes "git fetch", "git pull" et "git push").

**##Travaux pratiques##**

<!DOCTYPE html>

<html langue="fr">
<head>
	<title>Devoir à rendre</title>
</head>
<body>

	<h1>Besançon</h1>
	 <ul>
		<li>Ville</li>
			
		<li>Mairie</li>

		<li>Services</li>
	 </ul>
	<h2>Plus d'info</h2>

		<a href="http://besancon.fr">Decouvrir la ville</a>
		
		<p><font color="red"><font colour="00FF00">Besançon est une commune de l'Est de la France, préfecture du département du Doubs et siège du</font></p>
		<p>conseil régional de Bourgogne-Franche-Comté. Située en bordure du massif du Jura à moins d'une</p>
		<p>soixantaine de kilomètres de la Suisse, elle est entourée de collines et traversée par le Doubs</p>
		<p>Capitale de la région historique et culturelle de Franche-Comté, Besançon constitue aujourd'hui un</p>
		<p>pôle administratif important au sein de la région administrative de Bourgogne-Franche-Comté en</p>
		<p>accueillant le siège du conseil régional et de la région académique ainsi qu'un certain</p>
		<p>nombre de directions régionales.</p>

	<img src="file:///C:/Users/Random/OneDrive/Desktop/HTML%20Chinedu/Besan%C3%A7on3.png.png" height="350" alt="Centre ville" title="Pont de doubs">
</body>
</html>
