[![GitHub last commit](https://img.shields.io/github/v/release/deuza/fortunes-MultiDeskOS?style=plastic)](https://github.com/deuza/fortunes-MultiDeskOS/commits/main)
![GitHub Release Date](https://img.shields.io/github/release-date/deuza/fortunes-MultiDeskOS)
[![GitHub last commit](https://img.shields.io/github/last-commit/deuza/fortunes-MultiDeskOS?style=plastic)](https://github.com/deuza/fortunes-MultiDeskOS/commits/main)
![GitHub commit activity](https://img.shields.io/github/commit-activity/t/deuza/fortunes-MultiDeskOS)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/deuza/fortunes-MultiDeskOS)
[![License: CC0](https://img.shields.io/badge/license-CC0_1.0-lightgrey.svg?style=plastic)](https://creativecommons.org/publicdomain/zero/1.0/)
[![License: WTFPL](https://img.shields.io/badge/license-WTFPL_2.0-lightgrey.svg?style=plastic)](https://www.wtfpl.net/)

![Hack The Planet](https://img.shields.io/badge/hack-the--planet-black?style=flat-square\&logo=gnu\&logoColor=white)
![Built With Love](https://img.shields.io/badge/built%20with-%E2%9D%A4%20by%20DeuZa-red?style=plastic)
[![X (formerly Twitter) Follow](https://img.shields.io/twitter/follow/DeuZa42?style=social)](https://x.com/DeuZa42)

# fortunes-MultiDeskOS

> *"Les plus grands génies sont souvent passés pour des fous ou des cons."*
> -- Jayce - Je suis sur le chemin du Panthéon

## C'est quoi ?

Un fichier de fortunes Unix compilant les meilleures citations de **Jayce**, créateur de **MultiDeskOS** un projet informatique légendaire de la scène francophone des années 2000-2003, né sur les newsgroups `fr.*`.

MultiDeskOS se voulait simultanément un OS, un langage de programmation, une plateforme domotique, un concurrent de Windows/Linux/Mac/BeOS, un format vidéo, un protocole réseau et une intelligence artificielle. Le tout codé en Pascal Inline par un seul homme, sans études, "comme Einstein".

Le projet n'a jamais vraiment vu le jour. Les citations, elles, sont éternelles.
Internet n'oublie pas <3

## Le légendaire Jayce en quelques stats

- **255** perles de sagesse collectées
- **1** concurrent sérieux de Microsoft identifié (lui-même)
- **0** compilateur produit
- **∞** certitude de sa propre révolution informatique

## Quelques pépites

```
MultiDeskOS est plus ou moins open source.
  -- Jayce - Je me tâte

Sous Linux, je ne connais pas de langage de programmation, ni le C++.
  -- Jayce - Inconvénients

Ok. Mais pour calculer Pi, on fait comment ?
  -- Jayce - Zatiz ze couèchone

> Tu pourrais aussi créer une façon d'encoder ces caractères sans prendre
> trop de place et en restant compatible avec l'ASCII, et l'appeler UTF-42.
Oui, ca me semble être un bon principe. Merci.
  -- Jayce - Découvre le monde
```

## Installation

```bash
# Debian/Ubuntu (adapté l'installation à votre système ...)
apt install fortune-mod

# Copier le fichier dans le répertoire hébergeant les fichiers du programme fortune en le renommant au passage
cp multideskos.fortune /usr/share/games/fortunes/multideskos

# Générer ensuite l'index
cd /usr/share/games/fortunes/
strfile multideskos

# Vérifier que l'index est bien en place
ls ./multideskos.dat

# Tester
cd
fortune multideskos
```

### Dans votre `.bashrc` / `.bash_profile` ou `.zshrc` 

```bash
fortune multideskos
```

Jayce vous accueillera désormais à chaque ouverture de terminal avec la sagesse qu'il vous faut pour démarrer la journée ! :)

## Format du fichier

Format standard `fortune(6)`, compatible `strfile(8)`.    
Chaque citation est séparée par un `%` seul sur sa ligne :

```
Citation de Jayce
  -- Jayce - Contexte savoureux
%
Autre citation
  -- Jayce - Autre contexte
%
```

## Origine des données

Les citations sont extraites des échanges originaux issus des newsgroups `fr.*` et des forums Yahoo de l'époque.

La collecte et l'archivage de la majorité de ces citations ont été réalisés par le mainteneur de ce dépôt, acteur à la retraite de la scène USENET francophone des années 1990.

## Contribuer

Si vous avez des citations de Jayce qui ne figurent pas encore ici, les PR sont les bienvenues. Le patrimoine culturel de l'internet francophone nous appartient à tous.

## Licence

Les citations appartiennent à leur auteur. Ce fichier de compilation est distribué sous licence **CC0** - domaine public.

---

*"De toute facon, je compte bien être très connus partout dans le monde, créer un MultiDeskOS qui bousille tout."*
-- Jayce - Cauchemar


## Star History

<a href="https://www.star-history.com/?repos=deuza%2Ffortunes-MultiDeskOS&type=timeline&legend=top-left">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/image?repos=deuza/fortunes-MultiDeskOS&type=timeline&theme=dark&legend=top-left" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/image?repos=deuza/fortunes-MultiDeskOS&type=timeline&legend=top-left" />
   <img alt="Star History Chart" src="https://api.star-history.com/image?repos=deuza/fortunes-MultiDeskOS&type=timeline&legend=top-left" />
 </picture>
</a>

<p align="center">With ❤️ by <a href="https://github.com/deuza">DeuZa</a></p></sup></sub>


