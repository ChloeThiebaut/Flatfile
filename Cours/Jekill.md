# Jekill #

Jekyll est un générateur de site codé en Ruby. De plus, les sites en HTTPS sont mieux référencés.
L'objectifs de jekyll et de permettre de voir les modifications sans passer par GitHub. 

## Commande ##

commande d'insatallation

gem install jekyll
sudo apt install jekyll
gem install bundler -> gestion de paquet

jekyll serve -> lance le serveur
jekyl build -> creation d'uun dossier avec l'ensemble du site

les fichiers "_nomdossier" ne sont pas généré par le site. De ce fait il ne faut pas travailler dans ce genre de fichier.

## Layout ##

Le layout est un gabarit. cela permet de concerver des données sur les pages souhaiter sans avoir à recopier le code pour chaque page.

mkdir _layouts -> creation d'un repertoire layout 
touch default.html -> creation dans le répertoire layout le fichier default 

Dans ce fichier, il faut écrire le code corresepondant au directive voulu et correspondant au gabarit souhaité. 
Pour laisser la place au contenu (le main) on écrit: {{ content }}. Puis dans le fichier index on écrit en plus du main et entre les lignes en pointillées ce code-ci : layout: default
