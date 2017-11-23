---
title: Cours Statistique Bayésienne 01 dec. 2017
---

## Statistique bayésienne

- [Josephine Merhi Bleik](mailto:josephine.merhi-bleik@utc.fr)
- [Wang GAO](mailto:wang.gao@utc.fr)

Le 1er déc. 2017

### Résumé

Considérons un modèle statistique paramétrique $f(x\right\vert\theta)$.

#### Approche classique

Le modèle classique attribue à $\theta$ une vraie valeur, certes inconnue, mais conceptuellement unique, c'est-à-dire ___inconnue, mais certaine___. Pour l'estimer, l'analyse construit une statistique dont les paramètres dépendent de $\theta$.

On se place dans un espace probabilité paramétrique classique :

$$X \in (\mathcal{X}, \, \mathcal{A}, \left \{ P_{\theta},\theta \in \Theta \right \} )$$

$\mathcal{X}$ désigne l'espace des données, $\Theta$ celui des paramètres $\theta$.

Le but de l'analyse statistique est de faire de l'inférence sur $\theta$, c'est-à-dire décrire un phénomène passé ou à venir dans un cadre probabiliste.

#### Approche bayésienne

L'idée centrale de l'analyse bayésienne est de ___considérer le paramètre inconnu $\theta$ comme aléatoire___ : l'espace des paramètres $\Theta$ est muni d'une probabilité $\pi$ tel que $(\theta, \mathcal{B},\pi)$ est un espace probailisé. Nous noterons $\theta \sim \pi$.

$\pi$ est appelée loi a priori. Intuitivement et en termes informationnels, elle détermine ce qu'on sait et ce qu'on ne sait pas avant d'observer $X$.

#### Différence

L'approche bayésienne se différencier donc de l'approche classique dans le sens où le paramètre $\theta$ du modèle statistique, $f(x\right\vert\theta)$, n'est plus considéré comme étant totalement inconnu; il est devenu une v.a. dont le comportement est supposé connu. On fait intervenir dans l'analyse statistique une distribution associée à ce paramètre.

----

### Mots clés

Modèle paramétrique ; inférence statistique ; théorème de Bayes ;
Loi *a priori* ; Loi *a posteriori* ;  vraisemblance

### Plan provisoire du cours

1. Rappel de probabilité
    - Théorème de Bayes

2. Problème d'estimation des paramètres

- Approche classique
    1. Rappel de la fonction de vraisemblance
    3. Estimation ponctuelle
    4. Estimation par l'intervalle de confiance
    5. Exercices
    5. Présenter les limitations de cette approche

- Approche bayésienne
    1. Lois a priori
    1. Lois conjuguées
    1. Lois impropres
    1. Lois non informatives
    1. Estimateurs ponctuels : Maximum *a posteriori*, moyenne *a posteriori*
    1. Exercices


