<style type="text/css">
h1, h2, h3, h4 { color:#bd052d!important;}
footer {
	height:70px;
	min-width:302px;
	background-image : url("logo.png");
	background-repeat: no-repeat;
    padding-left:350px;
    line-height:35px;
    font-style:italic;
}
pre { font-size: 0.7em!important; }
</style>
<!-- page_number: true -->
<!-- footer: Les APIs du web en recherche -->


Les APIs du web en recherche
============================

Thibault Clérice, Février 2019 

École Nationale des Chartes

------------

# Qu'est-ce qu'une API ?

Une interface de communication avec un logiciel pour un autre logiciel.

-------------

# Qu'est-ce qu'une API web ?

- Une interface 
	- pour récupérer des données ciblées d'un site de manière automatique
	- pour utiliser le service d'un site.
- Simplification pour la réutilisation en interne ou en externe 
	- Pas besoin de reprendre le code source et de le convertir dans un autre langage
	- Pas besoin de fournir nécessairement des *dumps* pour explorer les données


-------------
## Cas particuliers : 

- Distributed Text Services & Canonical Text Services
- IIIF

## Standards

- OpenAPI ( Swagger.io )
- JsonAPI ( jsonapi.org )

-------------------

# API de Service

Exemple : http://localhost:8888/notebooks/Deucalion%20-%20Exemple.ipynb

-------------------

# API de données : DTS

Documentation : https://w3id.org/dts/

Exemple : http://localhost:8888/notebooks/DTS.ipynb

------------------

# API de données : IIIF

Documentation : https://iiif.org

Ressources : https://github.com/IIIF/awesome-iiif

Exemple : http://localhost:8888/notebooks/IIIF-Image.ipynb
Exemple : http://localhost:8888/notebooks/IIIF-Manifest.ipynb

---------------

# API de données : JsonAPI

Documentation : jsonapi.org

Exemple : https://portal.ehri-project.eu/api/v1

----------------

# GraphQL

Exemple : https://portal.ehri-project.eu/api/graphql

----------------

# OpenAPI

Documentation : swagger.io

Exemple : https://rise.mpiwg-berlin.mpg.de/pages/doc_for_resource_providers