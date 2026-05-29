# 2b. Revising AA Triggers (FR)

## 2 Co-conception de déclencheurs AA révisés

### Guide utilisateur de l’outil « Sliders »

Pour améliorer notre réponse aux risques signalés par les communautés, nous devons examiner comment les décisions relatives aux critères de déclenchement se traduisent en résultats concrets. Notre objectif est d’optimiser la rentabilité de la politique du Plan  d'Action Précoce (PAP), en veillant à ce que les ressources soient affectées aux moments et aux lieux où les communautés en auraient eu le plus besoin. Pour ce faire, nous procédons à une analyse rétrospective de la conception de la politique PAP, en traduisant les connaissances des communautés en recommandations concrètes sur le moment et la manière de mesurer les risques climatiques.
Afin de faciliter cette analyse, nous avons conçu l'Outil d'Aide à la Décision (OAD) suivant :
https://columbia-desdr.github.io/Sliders-madagascar-red-cross/ 
Cette section décrit l'utilisation de cet outil et propose quelques exercices ciblés sur la manière dont il peut être utilisé pour évaluer différentes options de conception de politiques en matière de PAP. 

![](image5.png)

L'OAD analyse deux aléas : la sécheresse et les précipitations excessives. Pour chaque aléa, l'OAD utilise les estimations de précipitations du CHIRPS au niveau des districts, les agrège sur une période de l'année choisie par l'utilisateur (« fenêtre ») et calcule les années historiques pour lesquelles les précipitations cumulées sur cette période auraient été les plus faibles (sécheresse) ou les plus élevées (excès). Il s'agit des années au cours desquelles le Plan d’Action Précoce (PAP) aurait pu être déclenché.
Le OAD intègre les données issues de l'enquête climatique communautaire menée récemment. Ces données servent à évaluer la pertinence du PAP potentiel de deux manières : 1) la concordance entre les périodes d'intervention et les moments de l'année cruciaux pour l'agriculture des communautés, et 2) la concordance entre les années de déclenchement historiques et les années où les communautés ont subi les pires conséquences des catastrophes. 
En arrière-plan, l'outil calcule toutes les informations nécessaires pour traduire les choix de l'utilisateur en paramètres de déclenchement PAP. L'utilisateur peut utiliser l’OAD pour explorer différentes options de conception de déclencheurs, évaluer leur pertinence et enregistrer ses choix dans une base de données afin d'y revenir ultérieurement ou de les utiliser pour une analyse plus approfondie. 
Les sections suivantes décrivent plus en détail l'interface utilisateur de l'outil. Celui-ci se compose de trois parties : la barre de connexion et de sélection de la région en haut de l'écran, l'analyse saisonnière dans le panneau de gauche et l'analyse historique dans le panneau de droite. 
Pour activer ou désactiver un élément de l'interface, cliquez sur la couche située à côté de celui-ci. Pour obtenir plus d'informations sur la fonction d'un élément, passez la souris sur l'icône « i » située à côté de son nom. 
Barre de connexion et de sélection

![](image29.png)

Saisissez votre nom dans le champ « Connexion… », puis cliquez sur « Connexion » pour accéder à l'outil avec votre compte utilisateur. Tous les choix que vous avez précédemment enregistrés à l'aide de l'outil seront chargés lors de votre connexion. 
Si vous souhaitez enregistrer la configuration de la politique pour la région que vous consultez actuellement, cliquez sur « Enregistrer ». Si vous souhaitez exporter vos choix de paramètres et les données qui en résultent afin de les examiner ou de les analyser plus en détail, cliquez sur « Exporter ».
Pour sélectionner la région à analyser, utilisez le menu déroulant. 
Groupe d'analyse saisonnière
Le panneau de gauche présente des informations sur le calendrier saisonnier des mesures de risque liées au PAP (« fenêtres ») et sur la manière dont ce calendrier s'articule avec les pratiques culturales des communautés et l'évolution des précipitations au cours d'une saison type. 
Les périodes indiquées apparaissent sous forme de superpositions colorées sur chaque graphique. Elles correspondent aux risques de sécheresse et d'excès d'eau en début et en fin de saison, soit un total de quatre périodes saisonnières pour l'évaluation des risques.
 Toutes les courbes sont organisées par périodes de 10 jours de l'année agricole, également appelées « décades ». Nous définissons l'année agricole comme s'étendant de juillet à juin de l'année suivante. 

![](image18.png)

Ce graphique présente la climatologie, c'est-à-dire l'évolution typique des précipitations, pour le district sélectionné.

![](image7.png)

Ce graphique présente le calendrier agricole déclaré par les communautés, organisé en fonction du début et de la fin des activités clés : les semis et la croissance des cultures (floraison). Si une communauté a déclaré avoir semé une culture à plusieurs reprises, la deuxième date de semis est indiquée par la mention « semis2 ». Si la communauté a déclaré cultiver plusieurs cultures, chacune d'entre elles est représentée dans un panneau distinct. Pour afficher une autre fokotany, utilisez le menu déroulant. 

![](image37.png)

Ces curseurs permettent à l'utilisateur de choisir les périodes de mesure des précipitations sous-saisonnières, également appelées « fenêtres », pour le déclenchement du plan d'action d'urgence (EAP). Les deux premiers curseurs concernent la sécheresse, et les deux suivants les précipitations excessives. Nous proposons deux fenêtres pour chaque aléa : une pour le début de la saison et une pour la fin de la saison. Faites glisser l'une des extrémités du curseur pour modifier le début ou la fin de la fenêtre. 

Panel d'analyse historique

La partie droite du graphique OAD présente une analyse historique des moments où chaque fenêtre de mesure des risques du plan d'action environnemental (EAP) aurait déclenché une intervention, ainsi que la correspondance entre ces années et les années les plus difficiles signalées par les communautés en termes d'impact de la sécheresse et des inondations

![](image26.png)

Faites glisser l'une ou l'autre extrémité du curseur « Année de début » pour modifier les années de début et de fin de l'analyse historique. 
Faites glisser le curseur « fréquence » pour modifier la fréquence ciblée des événements déclencheurs. Par exemple, une fréquence de 0,10 correspond aux 10 % des années les plus défavorables, ou, en d'autres termes, aux 3 années les plus défavorables sur les 30 dernières. Le curseur de fréquence détermine le seuil de déclenchement du PAP ainsi que les mauvaises années de la communauté qui sont mises en évidence. La fréquence par défaut est de 0,25.  

![](image25.png)

Ce graphique présente l'historique des performances de la stratégie EAP sélectionnée, en fonction des paramètres de durée et de fréquence saisis par l'utilisateur. L'axe des Y indique la gravité comparative (1 = pire), et l'axe des X indique les années. Chaque couleur du graphique correspond à la gravité d'une période de mesure de sécheresse ou de précipitations excessives sélectionnée dans le volet « Variables » (ou « fenêtre »). La couleur « combined_severity » correspond à la gravité moyenne sur l'ensemble des quatre fenêtres. 
Pour comparer les années de déclenchement historiques du Plan d’Action Précoces (PAP) aux années d'impact signalées par les collectivités, cochez les cases « Années de pluviosité excessive » et/ou « Années de sécheresse grave ». Pour comparer ces données aux prévisions de sécheresse saisonnière du DGM, cochez la case « Prévisions de sécheresse saisonnière ».

![](image6.png)

Enfin, ce tableau montre dans quelle mesure chaque source de données historiques correspond aux autres. La source de données de « référence » figure dans les colonnes du tableau, tandis que la source de données « prédictive » apparaît dans les lignes. Le chiffre indiqué dans chaque cellule correspond à l'indicateur de correspondance. Trois indicateurs de correspondance sont actuellement disponibles : 
Vrai positif : pourcentage des années « mauvaises » de référence au cours desquelles le prédicteur se serait déclenché.
Vrai négatif : pourcentage des années « correctes » de la série de référence au cours desquelles le prédicteur ne se serait PAS déclenché.
Moyenne de correspondance : moyenne pondérée des taux de vrais positifs et de vrais négatifs.

### Revising Drought and Excess Triggers

**Now it’s your turn \- we will use this process to evaluate some potential ways of improving the drought and excess AA triggers.** 

**Moving from the near term to the longer term – how likely are we in the future to see more disaster events like the ones that communities remembered?** 

**What processes drive these extreme events, and how predictable are they?** 

<div id="slide-config" data-type="kobo" data-next="../riskscenarios/" data-kobo-id="6gATXUan" data-width="100%"> </div>

