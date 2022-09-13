# OC-P05-Optimiser_la_gestion_des_données

[![Language](https://img.shields.io/badge/Python-darkblue.svg?style=flat&logo=python&logoColor=white)](https://www.python.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-darkgreen.svg?style=flat&logo=jupyter&logoColor=white)](https://jupyter.org/)
[![Framework](https://img.shields.io/badge/Pandas-darkorange.svg?style=flat&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Framework](https://img.shields.io/badge/Seaborn-red.svg?style=flat&logo=seaborn&logoColor=white)](https://seaborn.pydata.org/)
[![Framework](https://img.shields.io/badge/Plotly-430098?style=flat&logo=plotly&logoColor=white)](https://plotly.com/)

Optimisation de la gestion des données d'une boutique grâce à Python. Retrouver dans ce repo les fichiers:
- Le notebook *Projet5.ipynb*;
- Les données.

On retrouve dans ce projet une analyse de données, fusion de dataframe, analyse du chiffre d'affaires ainsi qu'une analyse des Outliers selon différentes méthodes (Ecart interquartile, Z-score, average absolute deviation...)

## Scénario du projet
Aujourd’hui est un grand jour, vous commencez votre mission en tant que data analyst freelance chez BottleNeck, un marchand de vin très prestigieux. Votre manager sur cette mission (Laurent) vous accueille chaleureusement et vous propose de partager un petit café avec le reste de l’équipe du service Numérique. L’ambiance est bonne, et vous voilà déjà parfaitement intégré dans cette équipe détendue mais professionnelle.


### Besoins de l'entreprise:
Actuellement, pour gérer nos ressources, nos clients, etc., on utilise un ERP qui n’est absolument pas relié à notre site de vente en ligne. Pour être tout à fait honnête, les outils en place sont vraiment artisanaux et dans ces conditions, la gestion des stocks est vraiment complexe et notre visibilité en termes d’analyse des ventes sur le Net est vraiment réduite, car très peu de personnes ont accès au back-office. En attendant une solution plus centralisée, un rapprochement entre les 2 bases, même manuel, pourrait être très utile…

Ta première mission se passe en 3 points.

Premièrement, j’ai besoin que tu rapproches deux exports : un export de l’ERP contenant les références produit, leur prix de vente et leur état de stock, et un export d’une table de l’outil de CMS contenant les informations des produits commercialisés en ligne (nom, description, nombre de ventes...).

L’export issu de la boutique en ligne contient le nombre de ventes pour chaque produit depuis sa mise en ligne, il ne permet pas d’analyser l'évolution des ventes dans le temps.

Je vais t’envoyer un mail dès la fin de notre entretien avec ces 2 exports en pièce jointe.

En plus de ces 2 exports, tu vas bénéficier d’une aide précieuse car Sylvie, notre ancienne stagiaire, a réalisé un travail de fourmi. Elle a créé un tableau Excel qui permet d’établir le lien entre la référence du produit dans l’ERP (product_id) et la référence du même produit dans la base de la boutique en ligne (SKU). 

Deuxièmement, une fois le rapprochement effectué, je souhaiterais avoir le chiffre d’affaires par produit, ainsi que le total du chiffre d’affaires réalisé en ligne.

Troisièmement et pour finir, je me demande s’il n’y a pas eu des erreurs de saisie dans certains prix des produits. J'aimerais que tu effectues une analyse sur cette variable afin de détecter d’éventuelles valeurs aberrantes, de les lister et d’en faire une représentation graphique pour plus de lisibilité.

Nous voudrions présenter tes résultats lors de la prochaine réunion de COPIL. Cela permettrait de montrer nos progrès. Je peux t’épargner le travail d’une présentation par slides, il me faut juste un notebook que tu présenteras à l’assemblée pour expliquer ta démarche. Tu peux utiliser R ou Python comme tu préfères, nous n'avons pas de préférence de notre côté.

### **Livrable:**
1. Le Notebook permettant de répondre à l'ensemble des demandes.