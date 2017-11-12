# enron-machine-learning

Le  dossier maildir_test contient les deux premiers sous-repertoires de la dataset initiale

On lance un ls sur le dossier de mail et on obtient dans un fichier les noms/noms de dossiers des personnes
 `ls ../maildir_test >  list_of_persons_dir.txt`

## Technos

Python 2.7
Spark 2.2
Jupyter

## data discovery

Le dossier contient deux scripts qui effectuent quelques exemples d'extractations sur les fichiers de mail.

## Next step

1. Je pense que utiliser le module mail.Parser() dans fichier arborescence_maildir  est plus pratique que la fonction faite à la main de l'autre fichier.A voir si le body du  mail est mieux conservé; en tout cas c'est pratique d'avoir des listes et de les écrire dans des fichiers.
2. Appliquer TF-IDF de MLlib pour clusteriser le contenu des mails. A la rigueur on pourrait faire un petit algo supervisé aussi parce qu'on a certains labels ^^


`
