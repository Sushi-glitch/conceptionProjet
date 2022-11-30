Balle en prisonniers est un jeu vidéo basé sur le tir des projectiles. C’est un jeu collectif de genre sportif et action qui se joue entre deux équipes avec un projectile rebondissant. 
L’objectif est de faire prisonnier tous les joueurs de l’équipe d’adversaire par le lancement des projectifs sur eux, si le projectile touche une personne ce dernier ira aux prisons.
L’équipe gagnante est celle qui a réussi à mettre tous les joueurs adverses en prison.

Pour l'installer:
1 - Telecharger eclipse :https://www.eclipse.org/downloads/download.php?file=/oomph/epp/2022-09/R/eclipse-inst-jre-win64.exe qui permet de compiler, de générer un projet, de débugger et d’exécuter
2 - Décompressez l’archive dans un dossier git https://github.com/Sushi-glitch/conceptionProjet. 
3 - ajoute l'independance de java fx :
	a- Ouvrir Eclipse -> Aide -> Eclipse Marketplace
	b- Cherche "javafx"
	c- installe e(fx)eclipse.
	d- Apres installation, reouvre eclipse
	e- cree new project File > New > Project.
	d- selectionne JavaFX > JavaFX Project
	f- clique Next, donne un nom au projet et appuyer sur fermer
	g- vous allez voire "The import javafx cannot be resolved"
	h- telecharge JavaFX de JavaFX 'https://gluonhq.com/products/javafx/'
	i- extracter le dossier et le telecharger
	j- dans eclipse, cliquez avec le bouton droit sur le projet et sélectionnez les propriétés
	k- Choisissez le chemin de compilation Java
	l- Sélectionnez ensuite l'onglet Bibliothèques (vous verrez des onglets en haut)
	m- Vous verrez Classpath> JavaFX SDK
	n- Cliquez sur Classpath, puis cliquez sur Ajouter des fichiers JAR externes à droite.
	o- à partir du téléchargement JavaFX (placé dans le dossier des téléchargements ou quelque part que vous avez placé).
	p- Choisissez tous les fichiers .jars dans Downloads/javafx-sdk-11.0.2/lib/(tous les fichiers .jar(s)) et cliquez sur Ouvrir.
	q- Cliquez ensuite sur Appliquer et sur Appliquer et fermez.
	r- vous n'obtiendrez pas de soulignements rouges ou (erreur).
	s- cliquez droit sur projet > Exécuter en tant que > Exécuter la configuration
	t- Choisissez l'onglet arguments et saisissez-le dans les arguments de la machine virtuelle.
    		--module-path /path/to/JavaFX/lib  --add-modules=javafx.controls,javafx.fxml
	q- (Important) Décochez ensuite la case qui dit "Use the -XstartOnFirstThread..."
	v- Cliquez sur Appliquer et exécuter.

4 - Compilez et Executer le jeu balleauprisonnier afin de commence de jouer 