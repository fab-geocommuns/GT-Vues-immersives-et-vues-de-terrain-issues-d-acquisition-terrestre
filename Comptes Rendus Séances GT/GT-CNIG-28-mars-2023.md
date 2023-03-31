## GT CNIG 28 mars 2023

#### Tour de table des membres présents

- Michaël Galien (Gard)
- Pierre-Alain Bonin (FNCCR)
- Nathalie Temin (Val-de-Marne)
- David Larquet (Esri France)
- Jean-Louis Zimmermann (Vaucluse / OSM-FR)
- Valentin Jérémie (Montpellier)
- Gilles Cébélieu (IGN)
- Mathilde Ferrey (SE Panoramax)
- Christian Quest (SE Panoramax + OSM-FR)
- Camille Salou (SE Panoramax / IGN)
- Christophe Munoz (Val Parisis)
- Florian Boret (Lunel)
- Gaëtan Lavenu (ESRI)


#### Objectifs de la séance 

##### Objectifs du GT ce jour : 
- reformaliser le mandat du GT, en préciser le périmètre exact 
- Eclaircir les processus pour participer entre 2 rendez-vous. 

Rappel du mandat de départ : 

*Le groupe de travail “Panoramax” est chargé de contribuer à la concertation et coordination des acteurs dans l’objectif de standardiser les données du géocommun de vues immersives libres. Pour Panoramax, la standardisation est un pré-requis à la réutilisation effective des données par tous, pour des usages divers, et pour assurer l’interface avec des systèmes tiers.*

##### Echanges sur le périmètre de Panoramax et du GT - entrants et sortants 

C'est l'**interopéralibilité en sortie de Panoramax pour faciliter les réutilisations** qui est essentiellement visée. Mais cette standardisation aura forcément un impact sur les attentes pour les entrants.

Il faudrait clarifier une position initiale de Panoramax sur le champs des possibles (ex. nuit ou indoor).

Vues prises du sol uniquement? 
Le travail sera effectué autour des acquisitions terrestres d'images.

Elargi aux vues immersives et de terrain en général y compris hors Panoramax? 
Il faut trouver le plus petit dénominateur commun pour permettre l'inter-opérabilité.
 
**Globalement le groupe est partant pour essayer d'avoir une réflexion générique au-delà du commun sur le sujet vues immersives et vues prises du terrain.** 

* Avantage : si le standard est suivi, rationalisation des plugIn et outils gérant les vues immersives (aujourd'hui 1 solution de prise de vues = 1 plugIn par exemple dans un SIG)
* Inconvénient : plus facile de se projeter sur quelque chose de concret et cadré (par exemple Panoramax) que sur des solutions possibles encore inexistantes. Panoramax servira d'exmple

**Proposition post réunion : Le GT sera renommé GT Vues immersives et vues de terrain issues d'acquisition terrestre.**

Nouvelle formulation proposée du mandat : 
*Le groupe de travail Vues immersives et vues de terrain issues d'acquisition terrestre est chargé de contribuer à la concertation et coordination des acteurs dans l’objectif de standardiser les données autour des dites vues. La standardisation de ce type de données est un pré-requis à la réutilisation effective des données par tous, pour des usages divers, et pour assurer l’interface avec des systèmes tiers.*

Le travail effectué profitera au géocommun Panoramax en facilitant sa réutilisation et son intégration dans des systèmes tiers et aussi la contribution au commun puisque n'importe quelle vue ou ensemble de vues suivant les standards définis sera compatible et donc facilement intégrable dans Panoramax.

L'objet du GT sera plus le profilage de formats standards ou solutions existantes pour servir et diffuser au mieux les données relatives au sujet, que la création d'un nouveau standard en lui-même.


#### En mode collaboratif, identifier les éléments / données qui doivent être standardisés dans le cadre du projet


1 - sur colibri, indiquer vos réponses via les post-it (le champs est libre !) https://postit.colibris-outilslibres.org/GT%20CNIG%20:%20sur%20quoi%20allons-nous%20travailler


<media-tag src="https://files.cryptpad.fr/blob/92/928f1e4ee18a26fd9aa82d6c75ea7516a1969d3926ba60f6" data-crypto-key="cryptpad:8H98dXIqkv5iILNkvS+6YH42ZEP9XNl4zShy6gBj6Qc="></media-tag>

2 - Retour sur les éléments identifiés, rassemblement des post-it semblables et échanges
Les sujets à standardiser au sein du GT sont :
- **les formats de catalogue d'images et API/Protocoles pour les interroger**
Des propositions ouvertes de format de catalogues d'images orientées et d'API sont disponibles du côté d'ESRI. https://github.com/Esri/oriented-imagery
Le format STAC et les APIs dédiées pourraient aussi être une proposition intéressante (c'est la piste explorée pour le moment par l'équipe de la SE Panoramax).https://stacspec.org/en/

- **les formats d'images**
JPEG, TIFF, WEBP
- **les métadonnées éventuellement en 2 catégories : métadonnées du cliché et métadonnées d'enrichissement**

Il faudra définir un minimun facilement accessible pour ne pas freiner la contribution (n'obliger à rien) : où et quand? (par exemple, le qui pouvant venir naturellement au moment de la contibution (authentification)) - Idéalement les infos minimales sont créées lors de la prise de vue (contenu EXIF ou équivalent).

Pour la réutilisation facilitée pouvoir compter sur un certain nombre de métadonnées clairement définies est important, mais effectivement contrairement à un système de tag par clé-valeur, le champ des possibles se limite souvent aux usages envisagés dès le départ.

Idéalement, il faudrait un socle minimal réduit obligatoire, des métadonnées proposées par défaut recommandées mais pas obligatoires, et un système complémentaire de métadonnées par clé-valeur (lien vers un wikidata) pour ouvrir à des usages non imaginés au départ. => aboutir à un mix équilibré entre les systèmes de référentiels classiques type IGN et les systèmes plus libres type OSM.

Idées de métadonnées à intégrer par Stéphane sur : https://forum.geocommuns.fr/t/metadonnees-possibles-sur-les-photos-ou-sequences-de-photos/522

Informations données par ESRI (Gaetan) : 
Schéma des catalogues d'imagerie orientée
https://github.com/Esri/oriented-imagery/blob/master/OrientedImageryCatalog_Schema.pdf
Spécification de l'API d'accès aux catalogues d'imagerie orientées
https://github.com/Esri/oriented-imagery/blob/master/OrientedImagery_API.pdf

*Des questions à traiter : précision de la licence des données, conditions de diffusion, statistiques de contribution (liée au commun, question ciblée Panoramax?)*




3 - Absence de vote cette séance sur les éléments identifiés => Proposer un vote d'ici la prochaine réunion du GT pour voir le premier sujet à aborder. https://postit.colibris-outilslibres.org/GT%20CNIG%20Tableau%201 

#### Eclaircir les processus pour participer entre 2 rendez-vous. 

Le débat et le partage d'idées en séance est intéressant, mais il empêche les absents de participer à la réflexion et de pouvoir prendre du recul sur les informations délivrées en séance.

Pour permettre à chacun de participer à son rythme, un travail asynchrone dont le résultat pour être discuté en séance est proposé via 2 canaux : le forum des Géocommuns avec un fil dédié et un projet github sur lequel chacun peut contribuer, faire des propositions, poser des questions, déposer de la documentation.

Un prochain rendez-vous sera proposé en mai-juin pour continuer le travail.
 
