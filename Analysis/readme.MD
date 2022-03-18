#French version below

The main objective of our project was to better understand the causes of abstention, which is a witness to a democratic crisis that makes people react at every election. We wanted to understand it in order to be able to propose solutions that a government could have implemented. When it came time to decide how to study this variable, we had several choices. Were we going to study it nationally and temporally or were we going to study it territorially? We chose the second option: there are fewer studies on this subject, and therefore potentially more things to discover. The idea was to build a dataset on territorial data, and then to regress and understand why some groups of people go to the polls less than others.

What territorial breakdown should we choose? We had the choice between several scales: regions, departments or communes. Choosing a fine division would have provided us with a large amount of data, but at the cost of difficulties in aggregating and cleaning it. A regional breakdown would have allowed easy access to clean data, but the analysis of the causes of abstention would probably have lacked finesse. We therefore opted for a departmental breakdown. We started from scratch, with the entire dataset to be constructed. We chose to aggregate the abstention data from the last four presidential elections, and to add all the relevant characteristics we could find.

We quickly realized the complexity of building such a dataset. For each feature or departmental characteristic, we had to find the data on the internet, do a thorough cleanup, and then ensure the compatibility of these data with our dataset under construction. Most of the data were public, but lacked quality and especially uniformity. Finally, the construction of the dataset and the summary map of our data took about 60% of our time.

We still managed to build a usable and consistent dataset, but we were not able to add enough characteristics and features to refine our identification of the causes of abstention. (Indeed, many data were only available for a specific year, or for a specific department or regional group). As a result, our modeling and analysis of causes lacked performance. Many of the features present were poorly correlated with abstention, and highly correlated with each other.

With hindsight, it appears that focusing on 2017 would have allowed us to add a large number of features fairly quickly (crime, number of sports centers, domestic violence figures etc.). This would have allowed us to identify the causes more thoroughly. We could even have put ourselves in the shoes of a government and proposed various territorial arrangements to optimize the ratio of cost of the measure to the decrease in abstention.


L’objectif principal de notre projet était de mieux comprendre les causes de l’abstention, 
témoin d’une crise démocratique qui fait réagir à chaque élection. 
Nous voulions la comprendre pour pouvoir proposer des pistes de résolution qu’un gouvernement aurait pu mettre en oeuvre. 
Au moment de choisir sous quel angle étudier cette variable, plusieurs choix s'offraient à nous. 
Allions-nous l'étudier nationalement et de façon temporelle ou allions-nous l'étudier de façon territoriale ? 
Nous avons choisi la deuxième option : il y a moins d'études là dessus, et donc potentiellement plus de choses à découvrir. 
L'idée était donc de construire un dataset sur des données territoriales, pour ensuite régresser et comprendre pourquoi certains groupes de personnes vont moins aux urnes que d'autres.

Quel découpage territorial choisir ? 
Nous avions le choix entre plusieurs échelles : régions, départements ou communes. 
Choisir un découpage fin nous aurait assuré une grande quantité de données, mais au prix de difficultés d’agrégation et de clean. 
Un découpage régional aurait permis un accès facile à des données propres, mais l’analyse des causes de l’abstention aurait probablement manqué de finesse. 
Nous avons donc opté pour le découpage départemental. 
Nous sommes partis de zéro, avec tout le dataset à construire. 
Nous avons choisi d’agréger les données de l’abstention des quatre dernières élections présidentielles, 
et d’y ajouter toutes les caractéristiques pertinentes que nous pourrions trouver. 

Nous nous sommes vite rendus compte de la complexité de construire un tel dataset. 
Pour chaque feature ou caractéristique départementale, il fallait trouver les données sur internet, faire un clean conséquent, 
puis assurer la compatibilité  de ces données avec notre dataset en construction. 
La plupart des données étaient publiques, mais manquait de qualité et surtout d’uniformité. 
Finalement, la construction du dataset et de la carte récapitulative de nos données nous ont pris environ 60% du temps. 

Nous sommes malgré tout parvenus à construire un dataset exploitable et conséquent, 
mais nous n’avons pas pu ajouter suffisamment de caractéristiques et de features permettant d’affiner notre identification des causes de l’abstention. 
(en effet beaucoup de données n’étaient disponibles que pour une année spécifique, ou pour un département ou groupe régional spécifique). 
Dès lors notre modélisation et analyse des causes a manqué de performance. 
Beaucoup des features présentes étaient peu corrélées avec l’abstention, et très corrélées entre elles. 

Avec du recul, il apparait que se concentrer sur 2017 aurait permis d’ajouter un grand nombre de features assez rapidement (criminalité, nombre de centres sportifs, chiffre des violences conjugales etc.). 
Nous aurions ainsi pu identifier les cause de façon plus approfondie.
Nous aurions même pu, ensuite, nous mettre à la place d’un gouvernement et proposer divers aménagements territoriaux pour optimiser le rapport Coût de la mesure/ baisse de l’abstention. 
