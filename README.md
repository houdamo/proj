# proj
## l'architecture globale de l'application:#
# la page d'accueil#
https://user-images.githubusercontent.com/44181362/48804842-01334200-ed16-11e8-9f46-91d8973726f7.PNG

<p align="center">
  <img src="C:\Users\pc\Desktop" width="350"/>
  <img src="C:\Users\pc\Desktop\Capture.png" width="350"/>
  Le client est rendu à la page d’accueil et télécharger son document puis choisi le type de conversion et cliqué sur le bouton convertir.
  Après l’opération de confirmation est terminé ,elle envoi un lien vers la page de resultat status qui contient état de statut et le temps passé.enfin, l’utilisateur est téléchargé le document converti avant 5 mn sinon il sera supprimé. 
  </p1>
  <p1 align="center">
  <img src="C:\Users\pc\Desktop" width="350"/>
  <img src="C:\Users\pc\Desktop\page2.png" width="350"/>
  </p1>
  ## l'archtecture de la couche donnée # 
  <p align="center">
  <img src="C:\Users\pc\Desktop" width="350"/>
  <img src="C:\Users\pc\Desktop\diagramme.png" width="350"/>
   </p>
  ## la manière de gestion des demandes #
  <p>
   Pour la manière de gestion des demandes des clients on utilisant les threads, car cette unité d'exécution fonctionne de façon autonome et parallèlement à d'autres threads. Le principal avantage des threads est de pouvoir répartir différents traitements d'un même programme en plusieurs unités distinctes pour permettre leurs exécutions "simultanées" ,car dans notre application il faut traiter plusieurs demandes des clients en même temps.
    Pour implémenter cette application en utilisant la plateforme JEE car elle sera déployée et exécutée.
    </p>
