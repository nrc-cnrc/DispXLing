These directories correspond to the data used in Knowles & Goutte (2026).

The data/ directory contains 7 files all with the same number of corresponding lines:

    queries.en:	    Queries in English
    queries.fr:	    Queries in French
    queries.fr2en:  Queries in English (machine translated from French)
    
    responses.en:	Gold responses in English
    responses.fr:	Gold responses in French

    category.txt:	Category label
    category-index.txt:	Within-category ID number
    


The llm-output/ directory contains jsonl files (one json object per line).

Each llm-output filename consists of the following information:
     [MODEL]-[CATEGORY]-[LANGUAGE].jsonl
     LANGUAGE indicates the language of the query/response pair and can be any of the following:
     	      en: English query, expected English response
	      fr: French query, expected French response
	      fr2en: English query machine translated from original French query, expected English response
	      fr2en2fr: Original French query paired with a French response produced by machine translating the fr2en (English) response into French

Each json object in the jsonl files contains the following information:
     model: model name
     query: query text
     category: category label
     query-id: within-category ID number
     llm-response: full text of the LLM response



The annotations/ directory contains majority annotations for each query-response pair

The majority.tsv file in the annotations/ directory contains tab-separated data:

COMPLETENESS	 ERRORS	 NUM_ANNOTATORS	  CATEGORY  LANGUAGE MODEL    ID

COMPLETENESS 	 is either COMPLETE or INCOMPLETE
ERRORS 		 is either ERROR or NO-ERROR
NUM_ANNOTATORS	 is the number of annotators who contributed to the annotation
CATEGORY	 is the category label
LANGUAGE	 is the language, one of en, fr, fr2en2fr
MODEL		 is the model name, one of gpt-4.1, gpt-5-chat, or aya:35b
ID		 is the within-category ID number (query-id)


The KNOWN_LIMITATIONS.txt file outlines some known limitations of the query set and corresponding verified responses.

---

Ces dossiers contiennent les données utilisées dans Knowles & Goutte (2026).

Le dossier data/ contient 7 fichiers, tous avec le même nombre de lignes (une par requête) :

    queries.en : Requêtes en anglais
    queries.fr : Requêtes en français
    queries.fr2en : Requêtes en anglais (traduites automatiquement du français)

    responses.en : Réponses vérifiées en anglais
    responses.fr : Réponses vérifiées en français

    category.txt : Étiquette de catégorie
    category-index.txt : Numéro d'identification dans la catégorie



Le dossier llm-output/ contient des fichiers jsonl (un objet json par ligne).

Chaque nom de fichier dans ce dossier comprend les informations suivantes :
       [MODÈLE]-[CATÉGORIE]-[LANGAGE].jsonl
       LANGUAGE indique la langue de la paire requête/réponse et peut être l'un des suivants :
       		en : requête anglaise, réponse anglaise attendue
		fr : requête française, réponse française attendue
		fr2en : requête anglaise (traduction automatique de la requête originale en français), réponse anglaise attendue
		fr2en2fr : requête française originale associée à une réponse française produite par la traduction automatique de la réponse fr2en (anglais) en français

Chaque objet json dans les fichiers jsonl contient les informations suivantes :
       model : Nom du modèle
       query : texte de la requête
       category : étiquette de catégorie
       query-id : numéro d'identification dans la catégorie
       llm-response : texte intégral de la réponse GML



Le dossier annotations/ contient les annotations majoritaires pour chaque paire requête-réponse

Le fichier majority.tsv dans le dossier annotations/ contient des champs séparés par des tabulations :

COMPLETENESS	 ERRORS	 NUM_ANNOTATORS	  CATEGORY  LANGUAGE MODEL    ID

COMPLETENESS 	 est soit COMPLETE (complet), soit INCOMPLETE (incomplet)
ERRORS		 est soit ERROR (erroné), soit NO-ERROR (sans erreur)
NUM_ANNOTATORS	 est le nombre d'annotateurs ayant contribué à l'annotation
CATEGORY	 est l'étiquette de catégorie
LANGUAGE	 est la langue, parmi {en, fr, fr2en2fr}
MODEL		 est le nom du modèle, parmi {gpt-4.1, gpt-5-chat, aya:35b}
ID		 est le numéro d'ID dans la catégorie (query-id)


Le fichier KNOWN_LIMITATIONS.txt souligne certaines limites connues de l’ensemble de requêtes ainsi que des réponses vérifiées correspondantes.
