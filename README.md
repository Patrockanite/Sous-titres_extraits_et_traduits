# Sous-titres_extraits_et_traduits
En construction
Le fichier Traitement*************.py (pas encore en ligne) contient un script Python me sert à extraire un sous-titrage d'une vidéo.MP4 dans sa langue d'origine si il n'existe pas.
Il génére un sous-titrage dans la langue d'origine 'sousTitre.srt' et un sous-titrage en français. (peut-être dans la langue du système d'exploitation : a voir)
Les fichiers seront contenus dans un répertoire nommé "Sorties" et auront les noms mis en argument à l'appel du script
Pour l'utiliser il faut demander un Tocken pour l'API Deepl chez https://www.deepl.com
Pour l'instant, il vaut mieux copier le fichier Traitement*************.py à côté de la vidéo
et lancer par la commande python : python Traitement .... avec en arguements les noms souhaités des ficiers*.srt à créer
exemple : python Traitement........py mon_sousTitre.srt mon_sousTitre_FR.srt
Le script va demander où se trouve la vidéo. Il faut indiquer le chemin sans mettre de quote ou de double quote (apostrophe ou guillement) avant et après le chemin.
Le script est juste un essai pour débutant et ne demande qu'à être amélioré.

Patrockanite
