# sf-docker
Ouvrez un terminal et naviguez vers le dossier contenant votre projet Docker WordPress.
Lancez les services en exécutant : docker-compose up -d. Docker télécharge les images nécessaires et lance les conteneurs.
Accédez à WordPress en ouvrant http://localhost:8000 dans votre navigateur. Suivez les instructions pour compléter l'installation de WordPress.
Pour gérer la base de données via une interface graphique, accédez à phpMyAdmin à http://localhost:8080.
Arrêt et Nettoyage :
Pour arrêter les conteneurs et supprimer les réseaux créés, exécutez : docker-compose down.
Pour supprimer les données persistantes et repartir de zéro, ajoutez l'option -v : docker-compose down -v.
