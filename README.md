==================================================
t3_Meilhan
==================================================

Extension de gabarit avec deux colonnes 2/3 et 1/3.

==================================================
Minimal Dependencies
==================================================

* TYPO3 CMS 7.6 or greater
* Bootstrap_package 7 or greater
* indexed_search 7.6 or greater

==================================================
Usage et Parametrage
==================================================

Pour cette extension, des constantes sont utilisés pour faciliter le parametrage et les modifications de contenus en fonction des besoins.
On les retrouvent au chemin suivant : t3_Meilhan/Configuration/TypoScript/constants.txt


* Le bandeau : - Création d'une page Bandeau de type Carousel qui va contenir un ou plusieurs Carousel Item.
               - Après création cette page possède un ID qu'il faut retranscrire dans le fichier énoncé plus haut.
Ne pas oublier dans le fichier Resources/Private/Layouts/Page/Default.html de faire appel à cette lib.

* La localisation : - Fil d'ariane dont les 2/3 des redirections ne changeront jamais. Utilisation des constantes (url/title/text) pour les 1/3 restants qui correspondent à la communauté de communes et la commune.                                                                                                                                                           
Ne pas oublier dans le fichier Resources/Private/Layouts/Page/Default.html de faire appel à cette lib.

* Bienvenue : - Message de bienvenue personnalisable.
Ne pas oublier dans le fichier Resources/Private/Layouts/Page/Default.html de faire appel à cette lib.
