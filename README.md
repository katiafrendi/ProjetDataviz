# ProjetDataviz: 
## Origine et traitement des données sur les radars en france 
Les données concernats les radars a été extrat du site www.data.gouv.fr , j'ai pu effectuer un sprint qualité affin d'évaluer la qualité de ses donnée de pouvoir les épuré, généralment les données sont de qualité nous remarquons l'absence de certaines données pour les dernières ligne de monfichier ce qui n'est pas très impactant car c'est relatif à la diretion auxquel sont rataché les radars.J'ai retiré également,j'ai égalment retiré la colone "longueur_troncon_km" car elle n'était pas renseigné pour tout les radars
NB: la vitesse limité par le radar n'est pas renseigné pour les radars de type "feu rouge" mais plutot pour les radars "fixe"
## Pourquoi les radars 
1/La décision d’implanter un radar s’effectue sur des sites où se produisent un nombre d’accidents corporels supérieur à la moyenne, où la vitesse est souvent en cause dans la survenance de ces accidents et où les contrôles sont difficiles à réaliser avec des moyens humains.
2/Le déploiement de radars automatiques en France est intervenu dès 2003 dans l’optique de réduire le nombre de tués sur les routes.

Les dates-clés du contrôle automatisé
https://www.securite-routiere.gouv.fr/radars/chiffres-radars/historique-des-radars
## Visalaisation de la répartition des radars sur l'ensemble du teriitoir francais 
## Radars et baisse de la mortalité routière
Les conducteurs ont considérablement réduit leur vitesse moyenne, passant de 91 km/h à 80 km/h. Cela a contribué à une baisse moyenne des accidents mortels à proximité des radars de 66 %. En 10 ans, entre 2003 et 2012, les radars ont permis de sauver 23 000 vies. 
#Utilisation des outils de datavisualiation 
##utilisation de l'outil paladio cependant les données traité par l'outil sont non exportablee donc en sois l'outil m'a permis de mieux comprendre et assimilité les données, avoir une première impression des données et vérifier la qualité de mes données = > capture video avec les filtres paladio 
je passe à l'utilisation de l'outil rawgraph avec l'avantage d'exporter les donnée s
