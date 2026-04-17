# Data Storytelling des exoplanètes

Ce projet utilise la visualisation de données pour explorer le catalogue Open Exoplanet Catalogue. À travers des graphiques statiques et interactifs, nous révélons les lois physiques, les structures cachées et les biais observationnels qui façonnent notre compréhension des exoplanètes.

## Structure du projet

Le récit est organisé en quatre actes, chacun répondant à une question spécifique.

### Acte I : De l’ordre dans le chaos 

À première vue, la visualisation brute révèle une apparente distribution aléatoire. Les points
semblent dispersés sans ordre évident couvrant l’ensemble de la voûte céleste. Cette impression
de chaos soulève une question fondamentale : Existe-t-il un ordre caché dans ces données ?

- Masse vs Rayon : Une loi de puissance sépare les mondes rocheux des géantes gazeuses.
- Période vs Demi-grand axe : Les exoplanètes suivent la troisième loi de Kepler, tout comme notre Système Solaire.
- Distribution des masses stellaires : La plupart des planètes détectées orbitent autour d'étoiles semblables au Soleil (biais observationnel).

### Acte II : Structures cachées

Les exoplanètes forment-elles naturellement des familles ?

- Nettoyage des outliers : L'algorithme Local Outlier Factor (LOF) nettoie le jeu de données.
- Choix du K optimal : Méthode du coude (Elbow) et coefficient de silhouette.
- Clustering K-Means : Révèle trois groupes interprétables.


### Acte III : Biais de détection 

Comment nos instruments influencent-ils ce que nous découvrons ?

- Diagramme en barres : Le transit et la vitesse radiale dominent très largement.
- Évolution temporelle : La mission Kepler a déclenché une explosion des transits après 2009.
- Masse-Rayon par méthode : Le transit détecte les petites planètes, la vitesse radiale cible les géantes.

### Acte IV : Carte 3D galactique

- Carte 3D interactive construite à partir des coordonnées célestes (ascension droite, déclinaison, distance en parsecs).
- Couleur = méthode de détection, taille = masse de la planète.
- Le Soleil au centre comme point de repère.


## Dataset

Source: Open Exoplanet Catalogue

Taille : Environ 5 000 exoplanètes confirmées + les planètes du Système Solaire

Colonnes clés : mass, radius, period, semi_major_axis, eccentricity, discovery_method, host_star_mass, host_star_temp, ra_string, dec_string, distance_pc

## Conclusion

Le data storytelling transforme les catalogues bruts en connaissances scientifiques. Ce projet montre que les exoplanètes ne forment pas une population homogène. Elles constituent des familles naturelles, suivent des lois universelles et sont révélées par des instruments biaisés. La carte 3D nous rappelle que chaque nouvelle mission réécrit notre atlas cosmique.

## Authors

Ndoumbé BAYO et Tania Admane - 2025/2026