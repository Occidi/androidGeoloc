# Geoloc &amp; Google maps


Les Activity/Res se trouvent ici : https://github.com/Occidi/androidGeoloc/tree/master/app/src/main


MainActivity gère toute la géolocalisation de l'utilisateur en temps réel à intervalle fixe et renvoie de ses données à la MapsActivity

MapsActivity et HttpHandler gèrent l'affichage de la GoogleMap, connexion asynchrone à l'api, création de marqueurs en fonction des data et lors du clic sur la fenetre d'info d'un marqueur renvoie vers une autre Activity
