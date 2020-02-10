# Comprendre Fantstatic
Le README.md a pour objectif de répondre à ses questions : 
- A quoi sert le "framework" ?
- Quand s'en servir ? 
-  Les améliorations possible ?

## Premièrement : Fantstatic à quoi ça sert ? 
Fantstatic est un framework coté front-end. Il permet de développer l'interface de vos applications avec simplement du **HTML, JS, SASS / CSS**. 

Ici pas de framework Javascript comme React.js, Vue.js etc... La volonté de Fantstatic est d'utilisé au mieux les technologies **native du web** afin d'éviter de surcharger les applications avec des surcouches supplémentaires parfois injustifié.

Fantstatic embarque avec lui **une structure défini et scalable** pour vos applications ainsi que les principaux outils qui viendront **simplifier le développement** ainsi que **l'optimisation de l'application**.

Concrètement voici ce que permet le framework : 
- HTML: 
	- Structure **découpé en pages**.
	- Création de **composant réutilisable**.
	- Possibilité de **passer des données** dans les composants HTML grâce aux **props**.

- CSS : 
	- Implémentation de **Tailwindcss**.
	- Développement en **SASS** qui sera compilé ensuite en CSS.
	- **Le style est découpé** pour chaque composants ainsi que pour chaque pages. 

- JS : 
	- Un dossier **main** qui contient **tous les scripts** qui interviendront sur **toutes les pages** du site web.
	- Un dossier **spécifique** qui lui au contraire permet d'utiliser **des scripts** pour **une page en particulier**.
	- Utilisation de **Babel** comme compilateur, donc possibilité de coder en **ES6**.

- IMGS :
	- **Compression** et **optimisation** automatique des **images**.

En résumé, Fantstatic est **un cadre de développement** pour vos applications front-end, **optimisé**, **préconfiguré** et sans surcouche.

**Le petit bonus :**  

> N'hésitez pas à vous approprier le framework et à le personnaliser
> comme bon vous semble. Le minimum a été installé et configuré donc
> rien ne vous empêche d'ajouter par exemple Jquery, ou bien de jouer
> avec les optimisations Babel.
> :)

## Deuxièmement :  Quand s'en servir ? 
Il est nécessaire de **bien comprendre** quand est-ce qu'il est optimal et intéressant pour vous de se servir de Fantstatic. 

Là où Fantstatic est le plus intéressant c'est dans la création de **site web statique**. En effet, au vu des différents outils incorporer au framework il devient **très rapide** de concevoir une **application statique** et **optimisé**.

Le second type d'application qui fonctionne bien avec Fantstatic sont les applications utilisant des **APIs externes** pour **l'implémentation de données**. 

Un exemple concret serait **un site web portfolio** où les différents projets sont **gérés par une API**. On pourrait donc facilement allez **récupérer les données avec Javascript** et pourquoi pas même créer des **fonctionnalités de recherche / filtrage très simple et rapide**.

**Note d'intention :**  
> L'objectif n'est pas de vous convertir et que vous utilisiez Fantstatic sur chacun de vos projets. 
> L'objectif est que vous utilisiez Fantstatic intelligemment et sur les projets adéquats !


## Dernièrement : Les améliorations possible du framework ?

Fantstatic est un projet qui ne possède pas que des qualités et qui ne révolutionne pas non plus le monde du développement web. 

Ce framework est à la base un projet personnel qui a été amené a évolué selon mes besoins de développeurs web. C'est pourquoi il reste pleins de choses qui sont perfectibles. Je vais d'ailleurs vous faire une liste de ce que je pense implémenter par la suite et qui sont actuellement un cruel manque à Fantstatic :

- La gestion des urls entre le "/dev" et le "/dist" avec nottament l'utilisation d'un "~/".
- Gérer la gestion de module Javascript par les imports et export au lieu de "tricher" avec la compilation.
- Séparer les fichiers de configuration dans un dossier dédié.
- Incorporer un outil pour mesurer les optimisations de l'application lorsqu'elle est build (actuellement disponible uniquement pour la compression d'images)

> Merci d'avoir lu jusqu'au bout ! :)
> Si vous avez des suggestions ou des améliorations possible n'hésitez pas !
