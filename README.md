# DataAnalyst_Project4_Operation-analytics_sales-data
Décorticage les jeux de données commerciale pour faciliter la prise de décision appuyée sur data: 
sortir les business insights, identifier les anomalies et des opportunités 

**Highlights**
- Statistique descriptive: 
 - sur les indicateurs de tendance centrale et de dispersion ;
 - analyse de concentration, via une courbe de Lorenz et un indice de Gini
 - analyse bivariée des variables 
 - tests de corrélation
- Nettoyage et traitement des jeux de données: 
 - identifier les données manquantes et érronées, 
 - choisir la méthode appropriée de traitement en vue de minimiser l’impact sur l’ensemble 

--------------------------------------------------------------
**Prérequis**

Les prérequis pour ce projet sont de connaître au choix les langages R ou Python, en sachant manipuler principalement les Dataframes (natifs en R, ou disponibles par la librairie Pandas en Python). Il vous faudra également connaître les bases de la statistique descriptive (moyenne, médiane, variance, représentations graphiques, tests de corrélation, analyse bivariée, etc.).

 
**Scénario**

Vous êtes data analyst d'une grande chaîne de librairie, fraîchement embauché depuis une semaine ! Vous avez fait connaissance avec vos collègues, votre nouveau bureau, mais surtout, la machine à café high-tech :

Mais revenons à votre mission : il est temps de mettre les mains dans le cambouis ! Le service Informatique vous a donné l’accès à la base de données des ventes. À vous de vous familiariser avec les données, et de les analyser. Votre manager souhaite que vous réalisiez une présentation pour vous "faire la main".

Comme vous l'avez appris dans vos recherches avant de postuler, votre entreprise, "Rester livres" s'est d'abord développée dans une grande ville de France, avec plusieurs magasins, jusqu'à décider d'ouvrir une boutique en ligne. Son approche de la vente de livres en ligne, basée sur des algorithmes de recommandation, lui a valu un franc succès !

**Les données**

Vous avez accès à ces données, extraites directement de la base de l’entreprise vers les fichiers CSV. Voici les fichiers à votre disposition :

les ventes (appelées “Transactions”) ;
la liste des clients ;
la liste des produits.
Téléchargez le jeu de données à cette adresse.

**Vos missions**

**Mission n° 1**

Avant de pouvoir entrer dans le vif du sujet, il vous faudra faire un peu de nettoyage ! Par exemple, vous devrez faire des choix quant au traitement des valeurs manquantes et des valeurs aberrantes.

**Mission n° 2**

Ensuite, vous réaliserez l’analyse des données. Une grande liberté vous est laissée sur ce plan, mais à vous de trouver les informations qui ont du sens pour mieux comprendre les ventes.

Vous devrez y utiliser au moins :
- des indicateurs de tendance centrale et de dispersion ;
- une analyse de concentration, via une courbe de Lorenz et un indice de Gini ;
- des représentations graphiques, dont au moins un histogramme, une représentation avec des "boîtes à moustaches",
- une représentation de série temporelle (c’est-à-dire un graphique dont l’axe des abscisses représente des dates)des analyses bivariées.

**Mission n° 3**

Voici quelques questions supplémentaires, que votre manager vous a posées :
Y a-t-il une corrélation entre le sexe des clients et les catégories de produits achetés ?
Y a-t-il une corrélation entre l'âge des clients et :
Le montant total des achats ;
La fréquence d’achat (ie. nombre d'achats par mois par exemple) ;
La taille du panier moyen (en nombre d’articles) ;
Les catégories de produits achetés.

