# DispXLing

## Overview

This repository contains data associated with work on evaluating crosslingual disparities in LLM performance in English and French.

## Structure

The repository contains a directory for each version of the released data, each of which contains a README file along with the data.

`data-release-v0/` corresponds to the data used in "Évaluer et atténuer les différences de performance des GML pour les tâches de génération de textes français et anglais" (Knowles et al., 2026)

`data-release-v1/` (**newest version**) corresponds to the data used in "Crosslingual Disparities in LLM Performance: Challenges for MT as Mitigation" (Knowles & Goutte, 2026)

## Licence

The contents of this repository are released under a [CC-BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/) licence.

---

## Résumé

Ce dépôt contient des données associées à des travaux sur l'évaluation des disparités interlinguistiques dans les performances des GML en anglais et en français.

## Structure

Le dépôt contient un dossier par version des données publiée, incluant chacun les données et un fichier README.

`data-release-v0/` contient les données utilisées dans « Évaluer et atténuer les différences de performance GML pour les tâches de génération de texte en français et en anglais » (Knowles et al., 2026)

`data-release-v1/` (**dernière version**) contient les données utilisées dans « Crosslingual Disparities in LLM Performance : Challenges for MT as Mitigation » (Knowles & Goutte, 2026)

## Licence

Le contenu de ce dépôt est publié sous licence [CC-BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/).

---

## Citing this work / Comment citer ce travail

```bibtex
@inproceedings{Knowles-Azadi-Simard-Lo-Larkin-Tessier-Goutte:CORIA-TALN:2026,
    author = "Knowles, Rebecca and Azadi, Fatemeh and Simard, Michel and Lo, Chi-kiu and Larkin, Samuel and Tessier, Marc and Goutte, Cyril",
    title = "Évaluer et atténuer les différences de performance des GML pour les tâches de génération de textes français et anglais",
    booktitle = "Actes de CORIA-TALN 2026. Actes des 33ème Conférence sur le Traitement Automatique des Langues Naturelles.  Volume 1 : articles scientifiques originaux",
    month = "6",
    year = "2026",
    address = "Nantes, France",
    publisher = "Association pour le Traitement Automatique des Langues",
    pages = "238-258",
    note = "",
    abstract = "Les grands modèles de langue (GML) sont généralement entraînés sur des données linguistiquement déséquilibrées, ce qui mène à de meilleures performances en anglais que dans d'autres langues. Dans cet article, nous construisons manuellement un ensemble de 104 requêtes (appariées en anglais et en français) portant sur des sujets liés à la sécurité et à la réglementation, dans des contextes canadiens.
Les requêtes sont associées à des réponses de référence extraites manuellement de sources fiables. Une annotation humaine des réponses de trois GML révèle que les réponses en français souffrent d'un déficit de précision factuelle, comparativement aux réponses en anglais. L'utilisation de la traduction automatique permet d'atténuer cet écart de performance, mais n'est pas toujours une solution acceptable.",
    keywords = "Grands modèles de langue, sécurité et réglementation, biais linguistique",
    url = "https://talnarchives.atala.org/TALN/TALN-2026/42.pdf"
}
```

```bibtex
@inproceedings{knowles-goutte-2026-crosslingual,
  title = "Crosslingual Disparities in LLM Performance: Challenges for MT as Mitigation",
  author = "Knowles, Rebecca  and
      Goutte, Cyril",
  booktitle = "Proceedings of the Seventeenth Conference of the Association for Machine Translation in the Americas",
  year = "2026",
  address = "Quebec City, Quebec, Canada",
}
```
