# Programmation efficace

## Introduction
Ce cours s'inscrit dans le cursus de licence informatique de l'UVSQ en 3ème année au semestre 5.

## Construction du cours
Pour construire le cours, les outils suivants doivent être installés sur le système.
* bundler
* rake
* graphviz (pour les diagrammes)

Remarque : la version 4.1 d'asciidoctor-revealjs ne semble pas compatible avec la version 4 de revealjs d'où l'usage de la version 3.9.

### Installation des dépendances (gems)
```
$ bundle install
```

### Construction du cours
```
$ bundle exec asciidoctor -r asciidoctor-diagram -D html/ src/index.adoc
```

## Références
* Cours de Stanford [CS 110L: Safety in Systems Programming](https://reberhardt.com/cs110l/) ([blog](https://reberhardt.com/blog/2020/10/05/designing-a-new-class-at-stanford-safety-in-systems-programming.html))
* Article dans Nature qui compare l'impact carbone de différents langages de programmation pour des codes d'astrophysique, [The Ecological Impact of High-performance Computing in Astrophysics](https://arxiv.org/pdf/2009.11295.pdf)
* Article dans SLE qui mesure l'efficacité énergétique de plusieurs langages de programmation, [Energy efficiency across Programming Languages](https://greenlab.di.uminho.pt/wp-content/uploads/2017/09/paperSLE.pdf)
* Cyrille Bonamy, Cédric Boudinet, Laurent Bourgès, Karin Dassas, Laurent Lefèvre, et al.. [Je code : les bonnes pratiques en éco-conception ...](https://hal.archives-ouvertes.fr/hal-03009741/). 2020. ⟨[hal-03009741](https://hal.archives-ouvertes.fr/hal-03009741/)
