The dataset consists of six files each with 104 corresponding lines:

QueryCategory.tsv:      Text indicating the query category.
QueryEN.tsv:	     	English query.
QueryFR.tsv:	     	French query.
QueryFR2EN.tsv:	     	English query (machine translated from French).
GroundTruthEN.tsv:   	English ground truth.
GroundTruthFR.tsv:   	French ground truth.

For the GroundTruth*.tsv files, the sub-answers are separated by a pipe (|).
The ground truth lines also sometimes include parenthetical information, to be used as additional clarification for human annotators.

For more information, refer to Knowles et al., "Évaluer et atténuer les différences de performance des GML pour les tâches de génération de textes français et anglais" (TALN 2026).

---

Le jeu de données comporte six fichiers, contenant chacun de 104 lignes (une par requête) :

QueryCategory.tsv : texte indiquant la catégorie de requête.
QueryEN.tsv : requête anglaise.
QueryFR.tsv : requête française.
QueryFR2EN.tsv : requête anglaise (traduite automatiquement du français).
GroundTruthEN.tsv : sous-réponses vérifiées (en anglais).
GroundTruthFR.tsv : sous-réponses vérifiées (en français).

Dans les fichiers GroundTruth*.tsv, les sous-réponses sont séparées par une barre verticale (|).
Les sous-réponses vérifiées incluent aussi parfois des informations entre parenthèses, à des fins de clarification pour les annotateurs humains.

Pour plus d'informations, consultez Knowles et al., "Évaluer et atténuer les différences de performance des GML pour les tâches de génération de textes français et anglais" (TALN 2026).

---

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
