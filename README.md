# README #

Simple outil Python permettant d'obtenir tout mot ou toute phrase en français sous la forme d'une série de Katakanas japonais arrangés pour donner à l'ensemble une sonorité similaire au texte d'origine.
Cette présente méthode d'appareillement linguistique via le système API (alphabet phonétique international) est en grande partie basée sur les travaux de recherche de Shigeko Shinohara dans "Analyse phonologique de l'adaptation japonaise de mots étrangers", thèse publiée en 1997, https://theses.fr/1998PA030058

* Pourquoi ?
  * Pourquoi pas ? Les sonorités françaises étant bien plus proches de celles japonaises que ne le sont les anglaises, de même que le sont, dans une certaine mesure, celles italiennes ou allemandes, voir et entendre comment une langue peut être reproduite dans une autre peut être ludique en soi.
  * Pour rapidement obtenir le texte pour faire chanter vocaloids et utaloids dans la langue de Molière.
  * Et les Hiraganas ? Certains sons français exigent d'utiliser des charactères de la table étendue. Celle des Hiraganas étant restreinte, une grande partie des phonèmes typiques au français ne sont disponibles que dans la table étendue des Katakanas, notamment grâce aux systèmes suggérés par le Cabinet du Japon et l'ANSI, et au formatage de romanisation Hepburn, dédié à pareil exercice.

* Comment s'en servir ?
  * Insérer le texte à traduire dans [texte=""].
  * Lancer, le résultat sera affiché par un print().
  * Dûe à la limitation des bibliothèques de reconnaissance de phonèmes et à la grande variété des sons dans la langue française, une lecture critique des résultats de cet outil, qui restent à titre d'aide informative, est impérative, et des modifications ou corrections manuelles peuvent être nécessaires.

* Bibliothèques nécessaires
  * Python 3
  * gruut, la bibliothèque de reconnaissance de phonèmes de l'API; "pip install gruut"
  * gruut_fr, la sous-bibliothèque pour les phonèmes et agencements de phonèmes français; "pip install -f 'https://synesthesiam.github.io/prebuilt-apps/' gruut[fr]"
