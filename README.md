# [S11] SELECTION BTS

[![PHP Version](https://img.shields.io/badge/php-%3E%3D%208.0.13-%37278AB)](https://www.php.net/)
[![Application Version](https://img.shields.io/badge/version-1.0.0-9cf)](https://github.com/25thMaxouuu/s11-selection)
[![Bulma Version](https://img.shields.io/badge/dynamic/json?color=%2300D1B2&label=Bulma&query=%24.version&url=https%3A%2F%2Fraw.githubusercontent.com%2Fjgthms%2Fbulma%2Fmaster%2Fpackage.json)](https://bulma.io/)

## FR

### Description

S11 Selection est une solution web PHP faite pour automatiser la création d'une grille d'évaluation d'un étudiant puis de les rassembler pour en faire un classement. Cette application est un projet d'école individuel fait lors de ma première année.

### Installation

> PHP 8 ou + est requis !

Un template de la base de donnée prêt à importer est disponible dans `./docs/selection.sql`. Les 3 comptes sont `admin@admin`, `teacher@teacher` & `secr@secr`.\
Créez ensuite un fichier nommé `config.php` dans `./config` et copiez coller y le code suivant :

```php
<?php

define("DB_HOST", "");
define("DB_NAME", "");
define("DB_USER", "");
define("DB_PWD", "");

```

Complétez les valeurs par vos données personnelles. Le fichier est ajoutée dans `.gitignore`, vos informations resteront en local.
L'application est ensuite prête à être utilisée.

### Caractéristiques :page_facing_up:

1. Portail d'authentification
2. Espace évaluateur
   1. Remplir une grille d'évaluation
   2. Modifier une grille
   3. Voir le classement
3. Espace secrétaire
   1. Voir et télécharger le classement au format CSV
4. Espace administrateur
   1. Créer un compte
   2. Modifier un compte
   3. Supprimer un compte 

### Caractéristiques techniques

:computer: PHP orienté objet sous architecture MVC.\
:pencil2: Framework CSS : [Bulma](https://bulma.io/documentation/overview/start/).\
:arrow_forward: Icone de l'application : [Grille Icons8](https://icons8.com/icon/64044/grille).

### À propos :information_source:

Projet réalisé de début Octobre 2020 à début Décembre 2020. Projet retravaillé à partir du 9 décembre 2021 pour mes examens.

Créé par **NOIZET Maxence** <noizetmax08@orange.fr>\
Licence : [Licence MIT](https://opensource.org/licenses/MIT)

## EN

### Description

S11 Selection is a PHP web solution designed to automate the creation of a student's evaluation grid and then gather them to make a ranking. This application is an individual school project done during my first year.

### Setup

> PHP 8 or higher is required !

A ready-to-import database template is available in `./docs/selection.sql`. The 3 accounts are `admin@admin` & `teacher@teacher` & `secr@secr`.\
Then create a file named `config.php` in `./config` and copy and paste the following code:

```php
<?php

define("DB_HOST", "");
define("DB_NAME", "");
define("DB_USER", "");
define("DB_PWD", "");

```

Fill in the values with your personal data. The file is added in `.gitignore`, your information will remain in local.
The application is then ready to use.

### Features :page_facing_up:

1. Authentication portal
2. Evaluator's area
   1. Filling in an evaluation grid
   2. Update a grid
   3. View the ranking
3. Secretary's area
   1. View and download the ranking in CSV format
4. Administrator area
   1. Create an account
   2. Update an account
   3. Delete an account

### Technical characteristics

:computer: Object-oriented PHP under MVC architecture.\
:pencil2: CSS Framework : [Bulma](https://bulma.io/documentation/overview/start/).\
:arrow_forward: App icon : [Grille Icons8](https://icons8.com/icon/64044/grille).

### About :information_source:

Project carried out from early October 2020 to early December 2020. Project reworked from 9 December 2021 for my exams.

Created by **NOIZET Maxence** <noizetmax08@orange.fr>\
Lisense : [MIT License](https://opensource.org/licenses/MIT)
