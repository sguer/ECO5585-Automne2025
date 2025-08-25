# ECO5585-Automne2025

## Description

Ce répertoire contient les données et le code associés à la synthèse ciblée de mon relevé de notes, en vue de ma demande d’inscription à ECO 5585 – Économétrie I. Le document RMarkdown (ECO5585_Prereqs.Rmd) présente :

- Un survol des cours pertinents de mon baccalauréat en Mathématiques financières et économie.

- Le calcul de la Moyenne Pondérée Cumulée (MPC) globale et récente pour illustrer ma progression académique.


## Contenu du répertoire

| Fichier                        | Description                                                                         |
| ------------------------------ | ----------------------------------------------------------------------------------- |
| `ECO5585_Prereqs.Rmd`          | Script principal en RMarkdown générant le PDF de synthèse.                          |
| `mpc.xlsx`                     | Jeu de données construit à partir du relevé de notes, utilisé pour calculer la MPC. |
| `ECO5585_Prereqs_8851496.pdf`  | Version compilée du document (optionnelle, si générée).                             |
| `README.md`                    | Présent fichier, expliquant l’organisation et l’usage des fichiers.                 |


## Instructions pour reproduire les résultats

### Installer les packages R nécessaires :

install.packages(c("tidyverse","knitr","readxl"))


### Placer le fichier mpc.xlsx dans le même répertoire que ECO5585_Prereqs.Rmd ou adapter le chemin dans le script.

Ouvrir ECO5585_Prereqs.Rmd dans RStudio et Knit pour générer le PDF.

## Remarques

Les données sont manuelles et anonymisées, construites à partir de mon relevé de notes non-officiel.

Ce complément est destiné à illustrer ma progression académique et mes compétences quantitatives pertinentes pour ECO 5585.
