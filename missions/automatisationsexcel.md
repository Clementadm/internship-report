# Automatisation de fichier Excel
Une de mes missions annexes à été d'automatiser certains processus via Excel.  
Le but étant de faire gagner du temps aux employé(e)s sur certains points qui était réalisé à la main.
   
La mise en place de fichier automatisé inclus :  
- l’application à chaque feuille d’une mise en page adaptée    
  - Mise en forme conditionnelle  
  - définition/cadrage de la données dans des tableaux   
 - le traitement et la manipulation de la données
  - conversion de type de données (exemple: texte vers date, texte vers nombre, ajout de pourcentage et de signes monétaires, etc)  
  - la sélection du nombre de caractères à afficher
- Obtention de la données via la source de données (tableau, logiciel, autre feuilles excel, etc)  
   
     
Les principales demandes émanaient du service supply-chain ainsi que du service ventes.  
 
Le service **supply-chain** avaient plusieurs demandes à réaliser.  
La première concernait le suivi des demandes de documents à nos fournisseurs  et château. 
Il fallait arrivé à associer à l'aide d'un autre fichier excel le bon courtier au bon vins et au bon millésimes.
Pour automatiser celle-ci, les données existantes ont été stockées dans un tableau excel dans lequel on vient rajouter des lignes dès qu'une nouvelle demande est à faire.  
l'association courtier-vin-millésimes est faite grâce à plusieurs formules Excel.
Une mise en forme conditionnelle est également appliquée.   
Cela permet de distinguer l'état du suivi de demande de document (traiter, à traiter, en attente)  
Afin de voir si chaque ligne est valide, une colonne cachée à été rajoutée.  
  
La seconde demande était de réaliser un classement des codes GAAC par article (vin et millésime).
C'est-à -dire de trouver si le code GAAC associé à notre article est valide ou non.  
Si celui-ci n'est pas correct alors une mise en page conditionnelle est appliquée 

La demande principale pour le service **achat** concernaient le suivi des livraisons des transporteurs.
Les données sont stockées dans un tableau puis écrasées par les nouvelles données.  
Puis à l'aide de Power Query on réalise un modèle de données qui s'actualisera selon le tableau des données. Ce modèle permet de traiter la données (le type de données, la constitution, l'ordre des colonnes, les tries, etc).  
La demande se constitue d'un affichage de toutes les livraisons à J-2 (livraisons réalisées, non réalisées, annuler ou récupérer par un particulier). Cette affichage devait être fait par entités de vents, date, clients et par numéro de commandes.  
Une fois ces étapes réalisées, une mise en forme est appliquée afin de trier par date, par type de livraisons, et par état de livraisons.

