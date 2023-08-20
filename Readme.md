# Ecriture automatique

Ce projet permet d'afficher du texte de manière automatisée, simulant une machine à écrire. L'utilisateur peut également ajuster la vitesse de défilement du texte.

L'application utilise JavaScript pour manipuler le contenu HTML et simuler l'effet d'écriture automatique.
Le projet utilise également un fichier CSS pour styliser la page. 


# Fonctionnalités :

* Affichage Progressif : L'application affiche le contenu d'une chaîne de texte caractère par caractère, simulant ainsi l'effet d'une machine à écrire.
-> Un index est initialisé à 1, qui indique le nombre de caractères à afficher jusqu'à présent.
-> La fonction "typeWriter" est définie pour mettre à jour le contenu affiché progressivement. 
Si l'index est inférieur ou égal à la longueur du texte, un extrait du texte est affiché, puis l'index est incrémenté.
-> Une fois que tout le texte a été affiché, l'index est réinitialisé à 1 pour recommencer le défilement.

* Contrôle de la Vitesse : La vitesse de défilement est calculée en fonction de la valeur de l'élément d'entrée "speed". La relation est inversement proportionnelle, c'est-à-dire que plus la valeur est grande, plus la vitesse est rapide.

# Aperçu :
Vous pouvez consulter ce projet ici : https://codepen.io/SalouaE/pen/WNLbbgR