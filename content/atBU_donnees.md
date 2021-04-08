
# Zenodo, Figshare, etc.: rechercher et partager des données de recherche grâce aux entrepôts de données

## Sommaire

<!-- MDTOC maxdepth:1 firsth1:0 numbering:0 flatten:0 bullets:1 updateOnSave:1 -->

- [Sommaire](#sommaire)   
- [1. Introduction](#1-introduction)   
- [2. Critères de choix d'un entrepôt de données](#2-critères-de-choix-dun-entrepôt-de-données)   
- [3. Trouver un entrepôt de données généraliste](#3-trouver-un-entrepôt-de-données-généraliste)   
- [4. Trouver un entrepôt de données spécialisé](#4-trouver-un-entrepôt-de-données-spécialisé)   
- [5. Trouver des jeux de données existants](#5-trouver-des-jeux-de-données-existants)   
- [6. Citer les jeux de données](#6-citer-les-jeux-de-données)   
- [7. Conclusion](#7-conclusion)   

<!-- /MDTOC -->

<div style="page-break-after: always;"></div>

## 1. Introduction

### Que sont pour vous les "données de recherche" et comment les partagez-vous?

![exe](img/foster_icone_exercises.png) Nous prenons quelques minutes pour préparer ce tour de table.

Pouvez-vous réfléchir à propos du dernier article que vous avez lu/écrit : quel était le matériel supplémentaire (tableaux, figures, etc.)?

Pouvez-vous noter des **exemples** et des types de données de recherche pertinents pour votre domaine de recherche?

Quels **modes de partage** des fichiers de données sont-ils utilisés dans votre domaine?

🔇 Si vous n'avez pas de micro ou ne souhaitez pas prendre la parole, répondez dans la conversation Zoom.

### Modes de partage des données de recherche

| Méthode       | Avantage     | Inconvénient     |
| :------------- | :---------- | ----------- |
|  Publier les données sur un **site web** (d'un projet, d'un laboratoire, etc.) | Les données sont facilement accessibles pour les autres </br> </br>DIssémination plus large de la recherche  | Requiert une maintenance de la part du groupe de recherche </br></br> Pas de contrôle sur qui accède aux données </br></br> Incapacité à attribuer un DOI ou un autre identifiant pérenne au jeu de données   |
| Soumettre les données à une **revue** ou publier un **article de données** ou _data paper_ 	| Les données sont associées à l'article publié au sujet de ces données </br></br> Les données sont partagées avec les pairs | Les données peuvent ne pas donner lieu à un article mais devoir quand même être partagées </br></br> En fonction de la revue, l'accès peut être restreint aux chercheurs bénéficiant d'un abonnement à la revue|
| Répondre aux **demandes** de données 	| Conserver le contrôle sur qui utilise les données 	| Accès très limité aux données </br></br> Peut ne pas être une méthode acceptable pour les agences de financement </br></br> Peut être chronophage	|
| Déposer les données dans un **entrepôt de données** | En fonction des entrepôts, accès paramétrable : fermé >> restreint >> sous embargo >> ouvert </br></br> Ne requiert aucune maintenance par le groupe de recherche </br></br> Capacité à attribuer un DOI ou un autre identifiant pérenne au jeu de données </br></br> Les données sont partagées avec les pairs | Les limitations peuvent varier en fonction des entrepôts : soumission limitée à certains utilisateurs, soumission payante, nécessité de respecter un format de données et/ou de métadonnées, etc. |


Adapté de : Llebot, C. Research Data Services : Sharing Your Data. _Oregon State University Libraries_. Repéré à https://guides.library.oregonstate.edu/research-data-services/data-sharing

### Terminologie

#### Données de recherche
> **Data**
>
> Data in the sense used here are all digitally available objects (simple or complex) that emerge or are the result of the research process.

_On entend ici par données tous les objets (simples ou complexes) disponibles sous forme numérique qui émergent ou sont le résultat du processus de recherche._

#### Entrepôt de données

> **Repository**
>
> Repository is defined as the infrastructure and corresponding service that allows for the persistent, efficient and sustainable storage of digital objects (such as documents, data and code).

_Un entrepôt est défini comme l'infrastructure et le service correspondant qui permet le stockage persistant, fiable et durable des objets numériques (tels que les documents, les données et le code)._

Ces deux définitions sont tirées du [glossaire](https://book.fosteropenscience.eu/en/06Glossary/) du livre suivant :

Bezjak, S. et al. (2018). _Open Science Training Handbook_. Hannover : FOSTER Plus Consortium. Repéré à https://book.fosteropenscience.eu/

## 2. Critères de choix d'un entrepôt de données

![fair](img/foster_fair.png)

![flèche](img/foster_icone_arrow.png) En fonction du contexte, les critères de choix peuvent différer et la démarche d'identification et de choix d'un entrepôt de données suivre différentes étapes.

### Exemples de jeux de données dans des entrepôts de données

Quels critères pouvons-nous inférer des exemples ci-dessous?

### Exemple 1

**Dépôt dans [Open Science Framework](https://osf.io)**

Reynolds, N., & Green, C. (2019). Spatiotemporal modelling of radiocarbon dates using linear regression does not indicate a vector of demic dispersal associated with the earliest Gravettian assemblages in Europe [Data set]. _Open Science Framework_. https://doi.org/10.17605/OSF.IO/6XRTS

👉 Il s'agit des données liées à l'article suivant :

Reynolds, N., & Green, C. (2019). Spatiotemporal modelling of radiocarbon dates using linear regression does not indicate a vector of demic dispersal associated with the earliest Gravettian assemblages in Europe. _Journal of Archaeological Science: Reports_, _27_, 101958. https://doi.org/10.1016/j.jasrep.2019.101958

Depuis la page de cet article sur ScienceDirect, pouvez-vous accéder à ces données dans OSF? Comment?

### Exemple 2

**Dépôt dans [Zenodo](https://zenodo.org)**

Reviers, N., Aline, R., & Vandekerckhove, R. (2017). Dutch Audio Description Corpus [Data set].  _Zenodo_. https://doi.org/10.5281/zenodo.1035175


### Exemple 3 en spectométrie

**Dépôt dans [4TU.Centre for Research Data](https://data.4tu.nl/repository/)**

Plomp, E., Von Holstein, I., Koornneef, J., & Davies, G. (2019). Neodymium and strontium isotope analysis of modern human dental enamel using Thermal Ionization Mass Spectrometry (TIMS) [Data set]. _4TU.Centre for Research Data_. https://doi.org/10.4121/uuid:d541a402-2701-47b2-ac6a-eaaa14c8c111

### Exemple 3 en psychologie

**Dépôt dans [UK Data Archive ReShare](https://reshare.ukdataservice.ac.uk)**

Biggart, L. P. (2016). Emotional intelligence in social work [Data set].  _UK Data Archive_. UK Data Archive ReShare. https://doi.org/10.5255/UKDA-SN-852431


### Exemple 4 en écologie

**Dépôt dans [ACEAS Data Portal](http://aceas.tern.org.au/knb/) (ACEAS = Australian Centre for Ecological Analysis and Synthesis)**

Haberle, S. et al. (2014). Weekly pollen count data for for the University of Tasmania, Hobart [Data set]. _ACEAS_. https://doi.org/10.4227/05/5344E9A41A124

### Exemple 4 en linguistique

**Dépôt dans [TROLLing](https://dataverse.no/dataverse/trolling) (TROLLing = The Tromsø Repository of Language and Linguistics)**

Rainsford, T. (2020). Table of transcribed forms for : Syllable Structure and Prosodic Words in Old French [Data set]. _The Tromsø Repository of Language and Linguistics (TROLLing)_. https://doi.org/10.18710/xymxpc


### Identifier et hiérarchiser vos critères

Voici quelques exemples de critère qui peuvent être pris en compte.

_Le renvoi vers les exemples n'est pas exhaustif._

* L'entrepôt est-il **certifié**?

En savoir plus sur la certification _CoreTrustSeal_ :

RDA France. (2019). Entrepôts de données de confiance : Critères de conformité. Repéré à https://www.rd-alliance.org/system/files/documents/CoretrustsealFR.pdf

👉 exemples 4 en linguistique, 3 en spectométrie

* L'entrepôt gère-t-il différents **types d'accès**? Permet-il par exemple un accès restreint ou sous **embargo**?

👉 exemple 2

* L'entrepôt prend-il en charge un **format de données** particulier?

👉 exemple 3 en spectométrie

* Quelles sont les exigences ou possibilités en termes de **précision et structuration de la description des données déposées**? Devrez-vous ou pourrez-vous fournir des métadonnées riches?

👉 exemples 4

Comme nous l'avons vu dans les exemples, les entrepôts de données fournissent des services variables et peuvent avoir différents niveaux d'exigence, concernant par exemple la description des données déposées. Cette description peut rester très sommaire ou au contraire devoir être très complète et structurée.

### Critères et ressources complémentaires

#### Suivre les pratiques de votre communauté

Privilégier un entrepôt spécialisé pour votre discipline, ou l'entrepôt généraliste utilisé par votre communauté.

#### Suivre les recommandations ou obligations

Ces recommandations ou ces obligations peuvent émaner de différentes parties prenantes.

#### D'un organisme de financement
*  [ERC - European Research Council](https://erc.europa.eu/sites/default/files/document/file/ERC_info_document-Open_Research_Data_and_Data_Management_Plans.pdf) : liste commentée d'entrepôts spécialisés par discipline - p. 9 et suiv.
* [Commission européenne](https://open-research-europe.ec.europa.eu/for-authors/data-guidelines) : liste d'entrepôts généralistes et spécialisés par discipline - ces _Data Guidelines_ comportent en outre des recommandations pour la préparation des données (notamment tabulaires).
* [Fonds national suisse pour la recherche scientifique](http://www.snf.ch/fr/leFNS/points-de-vue-politique-de-recherche/open_research_data/Pages/depots-de-donnees.aspx) : liste d'entrepôts généralistes et spécialisés par discipline fréquemment utilisés par la communauté scientifique suisse  et qui remplissent les critères Open Research Data (ORD) du FNS.

#### D'un éditeur
* [PLoS](https://journals.plos.org/plosone/s/recommended-repositories) : liste d'entrepôts généralistes et spécialisés par discipline (peu adapté pour les SHS)
* [Springer-Nature](https://www.springernature.com/gp/authors/research-data-policy/repositories/12327124)  : liste d'entrepôts généralistes et spécialisés par discipline (pas de rubriques _Humanities_, rubrique _Social sciences_ plus étoffée que celle de PLoS)
* [Cambridge University Press](https://www.cambridge.org/core/services/authors/open-data/where-to-share-your-data) : sélection d'entrepôts généralistes, renvoi vers politique de chaque revue

#### Ressources complémentaires

DoRANum. (2018). Du choix de l’entrepôt au dépôt des données. _DoRANum_. Repéré à https://doranum.fr/depot-entrepots/choix-entrepot-depot-donnees/

_Cette infographie interactive guide la démarche de choix d'un entrepôt en regroupant les critères en trois sous-ensembles de caractéristiques, celles liées **aux données**, **au partage** et **à l'entrepôt**._

Whyte, A. (2016). _Where to keep research data_ (Rapport No. v. 1.1). Edinburgh : Digital Curation Centre. Repéré à http://www.dcc.ac.uk/resources/how-guides-checklists/where-keep-research-data/where-keep-research-data#3

_Pour chacune des questions, le guide définit 3 niveaux de capacité de service. Il met en avant également des points à considérer pour chacune des questions._

> The checklist that follows addresses the five key questions posed in this guide:
> 1. is the repository reputable?
> 2. will it take the data you want to deposit?
> 3.  will it be safe in legal terms?
> 4.  will the repository sustain the data value?
> 5.   will it support analysis and track data usage?

## 3. Trouver un entrepôt de données généraliste

Vous souhaitez en savoir plus concernant un entrepôt de données généraliste recommandé par une revue ou un financeur? Vous souhaitez avoir une vue plus complète concernant les entrepôts de données généraliste?

L'outil en ligne d'aide à la décision [Trouver un entrepôt de données](http://busec2.u-bordeaux.fr/aide-choix-entrepot) vous aide à identifier l'entrepôt de données généraliste qui réponde le mieux à vos besoins, à partir de la réponse aux 4 questions suivantes :

* Allez-vous publier des données dont l'accès doit être restreint?
* Recherchez-vous un entrepôt avec des options de dépôt gratuit?
* Souhaitez-vous pouvoir définir librement les conditions d'utilisation de vos données?
* Souhaitez-vous que votre dépôt de données soit relu avant d'être mis en ligne?

Une brève fiche descriptive accompagne chacun des huit entrepôts de données comparés : Fighsare, , B2SHARE, ,  et Harvard Dataverse.

* **Entrepôts de données généralistes utilisés par ce service**
  * [4TU.ResearchData](https://data.4tu.nl/)
  * [Figshare](https://figshare.com/)
  * [Harvard Dataverse](https://dataverse.harvard.edu/)
  * [Dryad](http://www.datadryad.org/)
  * [Mendeley Data](https://data.mendeley.com/)
  * [Open Science Framework (OSF)](https://osf.io/)
  * [B2SHARE](https://b2share.eudat.eu/)
  * [Zenodo](https://zenodo.org/)

  ![exe](img/foster_icone_exercises.png) Nous prenons quelques minutes  pour que vous puissiez tester cet outil.

## 4. Trouver un entrepôt de données spécialisé

### Trouver un entrepôt de données avec re3data

Registry of Research Data Repositories. https://doi.org/10.17616/R3D // citation simplifiée : re3data - https://www.re3data.org/

Il s'agit de la ressource de référence, indexant plus de 2000 entrepôts.

On peut naviguer dans re3data par :

* [sujet](https://www.re3data.org/browse/by-subject/),
* [type de contenu](https://www.re3data.org/browse/by-content-type/),
* [pays](https://www.re3data.org/browse/by-country/).

![flèche](img/foster_icone_arrow.png) [Afficher la liste complète des entrepôts référencés dans re3data](https://www.re3data.org/search?query=)

De nombreux filtres permettent ensuite d'affiner les listes de résultats, en fonction par exemple des critères suivants.

* **Certificates** : par quelle certification l'entrepôt est-il qualifié?
* **Accès** : gradient de valeurs de fermé à ouvert - se décompose en 3 types d'accès :
  *  **Database access** : accès à l'entrepôt de données lui-même : sous quelles conditions un utilisateur peut-il accéder à la base de données en général?
  * **Data access** : accès aux jeux de données déposés dans un entrepôt de données spécifique : sous quelles conditions un utilisateur peut-il accéder à un jeu de données?
  * **Data upload** : accès à la soumission de données : sous quelles conditions un utilisateur peut-il soumettre des données ?
* **Versioning** : les jeux de données peuvent-ils être versionnés?


![exe](img/foster_icone_exercises.png) Nous prenons quelques minutes  pour la recherche suivante.

En filtrant la recherche sur les entrepôts intégrant la fonctionnalité d'**attribution de DOI**, trouvez-vous un entrepôt spécialisé dans votre domaine?

🔇 Si vous n'avez pas de micro ou ne souhaitez pas prendre la parole, répondez dans la conversation Zoom.

### Outils complémentaires

Des services d'aide au choix et à la décision ont été développés, principalement à partir des données de re3data, et proposent des fonctionnalités supplémentaires.

#### FAIRsharing

![gears](img/foster_icone_gears.png)

[FAIRsharing.org](https://fairsharing.org/) répertorie non seulement des entrepôts mais également des standards, des méthodes, des vocabulaires, etc. Pour chaque ressource sont notamment spécifiés les critères suivants.
* Le **statut** : en développement / opérationnel / incertain / déprécié
* La **recommandation** : nom de l'éditeur, de la revue, etc. qui recommande

En savoir plus concernant FAIRsharing :

Sansone, S.-A. et al. (2019). FAIRsharing as a community approach to standards, repositories and policies. _Nature Biotechnology_, _37_(4), 358‑367. https://doi.org/10.1038/s41587-019-0080-8

#### Data Deposit Recommendation Service

![gears](img/foster_icone_gears.png)

[Data Deposit Recommendation Service](https://ddrs-dev.dariah.eu/ddrs/)  est développé par [l'infrastructure DARIAH](https://www.dariah.eu/) et spécialisé pour les **sciences humaines**. Il utilise les données de re3data. 2 critères peuvent être spécifiés:

* le pays - > choisir _European Union_ pour obtenir des réponses satisfaisantes,
* la discipline.

Pour certains entrepôts, il est possible de soumettre une demande de dépôt à partir de la fiche de cet entrepôt, par exemple [CLARIN-ERIC](https://ddrs-dev.dariah.eu/ddrs/selectRepository?id=100010209).


#### Repository Finder

![gears](img/foster_icone_gears.png)

[Repository Finder (DataCite)](https://repositoryfinder.datacite.org/) est développé dans le cadre du [projet Enabling FAIR Data](http://www.copdess.org/enabling-fair-data-project/), porté par la _Coalition for Publishing Data in the Earth and Space Sciences_. Il permet d'identifier un entrepôt référencé dans re3data ou parmi les 208 entrepôts sélectionnés par le projet.

Ce service diffère des 2 précédents dans la mesure où on ne spécifie pas de critères de choix.

## 5. Trouver des jeux de données existants

### Interroger directement un entrepôt de données

Il s'agit de l'une des approches possibles : interroger directement un entrepôt disciplinaire de son domaine de recherche, ce qui peut permettre de bénéficier de fonctionnalités de recherche spécifiques.

Cela rejoint les astuces 2, 4 et 8 des 11 astuces recensées ci-dessous.

Gregory, K. et al. (2018). Eleven quick tips for finding research data. _PLOS Computational Biology_, _14_(4), e1006038. https://doi.org/10.1371/journal.pcbi.1006038

> Tip 1: Think about the data you need and why you need them.
>
> Tip 2: Select the most appropriate resource.
>
> Tip 3: Construct your query strategically.
>
> Tip 4: Make the repository work for you.
>
> Tip 5: Refine your search.
>
> Tip 6: Assess data relevance and fitness -for -use.
>
> Tip 7: Save your search and data- source details.
>
> Tip 8: Look for data services, not just data.
>
> Tip 9: Monitor the latest data.
>
> Tip 10: Treat sensitive data responsibly.
>
> Tip 11: Give back (cite and share data).


### Trouver des jeux de données en lien avec les publications

En plus du _data availability statement_ (parfois non accessible sans abonnement à la revue), des outils intégrés aux bases de données bibliographiques sont disponibles.

Dans le nouveau **[PubMed](https://www.ncbi.nlm.nih.gov/pubmed/?otool=ifruvsblib)**, il s'agit de l'attribut _Associated data_, disponible sous la forme d'un filtre à partir d'une liste de résultats.

Dans **[Scopus](http://docelec.u-bordeaux.fr/login?url=http://www.scopus.com)**, il s'agit de l'encart _Related Research Data_, accessible depuis la notice d'un article en particulier. Cette fonctionnalité est donc très limitée, puisqu'elle ne permet pas de sélectionner un ensemble d'articles ayant des données associées.

Le **type de publication** peut également être exploité comme critère de recherche ou de filtre. Il permet en effet d'identifier les articles de données, ou _data papers_. Les valeurs associées diffèrent en fonction des bases de données.
* Scopus -> choisir la valeur _data paper_
* PubMed -> choisir la valeur _dataset_

###  Les moteurs de recherche spécialisés

Le principal moteur de recherche spécialisé est [DataCite Search](https://search.datacite.org).

ℹ️ Vous trouverez une présentation détaillée de DataCite et d'autres moteurs spécialisés dans le support de la formation [_Data sharing_ : trouver, réutiliser et citer des données de recherche ](https://github.com/fflamerie/ED_datasharing/blob/master/content/ED_datasharing_COURS.md) (formation du Collège des écoles doctorales de l'université de Bordeaux).

## 6. Citer les jeux de données

### Où les données sont-elles citées?

De plus en plus d'éditeurs incitent les auteurs à citer les jeux de données au même titre que les articles dans leur bibliographie, dans une rubrique dédiée ou dans la bibliographie principale.

Voir par exemple pour une politique d'éditeur :

STM Publishing News. (2017, 14 septembre). Wiley announces new Data Sharing and Citation policies to improve transparency in research. _STM Publishing News_. Repéré à http://www.stm-publishing.com/wiley-announces-new-data-sharing-and-citation-policies-to-improve-transparency-in-research/

La politique de citation des données dans _Scientific Data_ est détaillée dans cet éditorial :

Data citation needed. (2019). _Scientific Data_, _6_(1), 27. https://doi.org/10.1038/s41597-019-0026-5

Exemple de données citées dans la bibliographie principale, référence n° 21 :

Power, A. M. et al. (2019). Field-recorded data on habitat, density, growth and movement of Nephrops norvegicus. _Scientific Data_, _6_(1), 7. https://doi.org/10.1038/s41597-019-0013-x

![citation_donnees_biblio](img/citation_donnees_biblio.png)

### Comment citer un jeu de données?

#### Avec un logiciel de gestion bibliographique, Zotero

* Enregistrer les jeux de données sous le type de document "Article de revue"
* Spécifier : `type: dataset` dans le champ `Extra`

![zotero_dataset](img/zotero_extra_dataset.png)

* Choisir un style bibliographique qui prend en charge le type de document "Dataset", par exemple [APA](http://owl.english.purdue.edu/owl/resource/560/01/) ou Vancouver

#### Avec l'outil Citation Formatter fourni par DataCite

Ce service en ligne est accessible à l'adresse : https://citation.crosscite.org/

A partir d'un DOI et du choix d'un style bibliographique et de la langue, il génère automatiquement une citation correctement mise en forme.

## 7. Conclusion

Reprenons la conclusion de l'article

Gregory, K. et al. (2018). Eleven quick tips for finding research data. _PLOS Computational Biology_, _14_(4), e1006038. https://doi.org/10.1371/journal.pcbi.1006038

> Regardless of whether you are acting as a data seeker or a data creator, remember that ‘data discovery and reuse are most easily accomplished when: (1) data are logically and clearly organized; (2) data quality is assured; (3) data are preserved and discoverable via an open data repository; (4) data are accompanied by comprehensive metadata; (5) algorithms and code used to create data products are readily available; (6) data products can be uniquely identified and associated with specific data originator(s); and (7) the data originator(s) or data repository have provided recommendations for citation of the data product(s)’

### Les enjeux en image

![enjeux](img/Higman_2017_Talking_carrots_and.jpg)

Source : Higman, R. (2017). Talking carrots and sticks for RDM at the #datastewards networking day, sharing the graphic on reasons to share we use in @UoMRDMService trainingpic.twitter.com/bMsj6h57RG [Tweet]. _@RosieHLib_. Repéré à https://twitter.com/RosieHLib/status/936587668607160320

### La grande image de la science ouverte

![os_taxonomy](img/os_taxonomy.png)

Source : Bezjak, S. et al. (2018). _Open Science Training Handbook_. Hannover : FOSTER Plus Consortium. Repéré à https://book.fosteropenscience.eu/


# Crédits

<a rel="license" href="http://creativecommons.org/licenses/by-sa/3.0/fr/"><img alt="Licence Creative Commons" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/3.0/fr/88x31.png" /></a><br />Ce document est mis à disposition selon les termes de la <a rel="license" href="http://creativecommons.org/licenses/by-sa/3.0/fr/">Licence Creative Commons Attribution -  Partage dans les Mêmes Conditions 3.0 France</a>.

**Auteur**

Frédérique Flamerie

![orcid_logo](img/orcid_logo.png) [orcid.org/0000-0001-6014-0134](https://orcid.org/0000-0001-6014-0134)


**Visuels et icônes**


Bezjak, S. et al. (2018). _Open Science Training Handbook_. Hannover : FOSTER Plus Consortium. Repéré à https://book.fosteropenscience.eu/ - [CC-Zero]
