# Automatisation de fichier Excel
Une de mes missions annexes a été d'automatiser certains processus via Excel.  
Le but étant de faire gagner du temps aux employé(e)s sur certains points qui étaient réalisés à la main.
   
La mise en place de fichier automatisé inclus :  
- l’application à chaque feuille d’une mise en page adaptée    
  - Mise en forme conditionnelle  
  - définition/cadrage de la données dans des tableaux   
 - le traitement et la manipulation des données
  - conversion de type de données (exemple: texte vers date, texte vers nombre, ajout de pourcentage et de signes monétaires, etc)  
  - la sélection du nombre de caractères à afficher
- Chargement des données via la source de données (tableau, logiciel, autre feuilles Excel, etc)  
   
     
Les principales demandes émanaient du service supply-chain ainsi que du service ventes.  
 
Le service **supply-chain** avaient plusieurs demandes à réaliser.  
La première concernait le suivi des demandes de documents à nos fournisseurs et châteaux. 
Il fallait arriver à associer, à l'aide d'un autre fichier Excel, le bon courtier au bon vin, et au bon millésime.
Pour automatiser celle-ci, les données existantes ont été stockées dans un tableau Excel dans lequel on vient ajouter des lignes dès qu'une nouvelle demande est à faire.  
L'association courtier-vin-millésime est faite grâce à plusieurs formules Excel.
Une mise en forme conditionnelle est également appliquée.   
Cela permet de distinguer l'état du suivi de demande de document (traiter, à traiter, en attente).  
Afin de voir si chaque ligne est valide, une colonne cachée a été rajoutée.  
  
La seconde demande était de réaliser un classement des codes GAAC (numéro d'identification du vin) par article (vin et millésime).
C'est-à -dire de trouver si le code GAAC associé à notre article est valide ou non.  
Si celui-ci n'est pas correct alors une mise en page conditionnelle est appliquée.  

La demande principale du service **achat** concernaient le suivi des livraisons des transporteurs.
Les données sont stockées dans un tableau puis écrasées par les nouvelles données.  
Puis à l'aide de Microsoft Power Query, on réalise un modèle de données qui s'actualisera selon le tableau des données. Ce modèle permet de traiter la donnée (le type de données, la constitution, l'ordre des colonnes, les tries, etc).  
La demande se constitue d'un affichage de toutes les livraisons à J-2 (livraisons réalisées, non réalisées, annulées ou récupérées par un particulier). Cette affichage devait être fait par entité de vente, date, client et par numéro de commandes.  
Une fois ces étapes réalisées, une mise en forme est appliquée afin de trier par date, par type de livraisons, et par état de livraisons.

