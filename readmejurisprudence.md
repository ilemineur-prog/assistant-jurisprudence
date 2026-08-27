# Assistant Référencement — Jurisprudence belge — Documentation

## Objectif

Outil pédagogique destiné aux étudiant·e·s en droit pour les aider à rédiger correctement les références de **jurisprudence belge**, conformément au *Guide des citations, références et abréviations juridiques* (Wolters Kluwer / Kluwer).

L'application génère automatiquement la référence complète et correctement formatée (avec italiques) à partir des informations encodées dans un formulaire. Elle se présente sous la même forme que l'assistant *Législation*, dans un thème **bordeaux**.

---

## Utilisation

1. Ouvrir `assistant-jurisprudence.html` dans un navigateur web (aucune installation requise).
2. Choisir le **niveau de juridiction** : **Jurisprudence internationale**, **Jurisprudence européenne** (toutes deux *en construction*) ou **Jurisprudence nationale (belge)** — seule partie disponible pour l'instant.
3. Dans la partie nationale, choisir la **catégorie** via les onglets : **Ordre judiciaire**, **Cour constitutionnelle** ou **Conseil d'État**.
4. Sélectionner le **type de juridiction** dans le menu déroulant (onglet Ordre judiciaire).
5. Compléter les champs qui apparaissent dynamiquement.
6. Cliquer sur **▶ Générer la référence** (ou sur **↻ Effacer** pour vider le formulaire).
7. Copier la référence via le bouton **Copier (avec mise en forme)** pour conserver l'italique lors du collage dans Word ou LibreOffice (un bouton **texte simple** est également disponible).

---

## Structure par niveaux

Un écran d'accueil propose trois niveaux :

- **Jurisprudence internationale** — 🚧 en construction ;
- **Jurisprudence européenne** — 🚧 en construction ;
- **Jurisprudence nationale (belge)** — disponible, décrite ci-dessous.

---

## Périmètre couvert (jurisprudence nationale)

Cette version couvre la **jurisprudence belge** (chapitre 1 du Guide). La jurisprudence européenne et internationale, ainsi que la doctrine, feront l'objet de versions ultérieures.

### 1. Ordre judiciaire — règle générale (n° 131)

Juridictions couvertes :

- **Cour de cassation** — `Cass.` (pas de mention du siège)
- **Cour d'appel** — ville seule (Anvers, Bruxelles, Gand, Liège, Mons)
- **Cour du travail** — `C. trav.` + ville
- **Cour d'assises** — `Cour ass.` + province
- **Tribunal de première instance** — sections civile (`Civ.`), correctionnelle (`Corr.`), famille (`Trib. fam.`), jeunesse (`Trib. jeun.`), application des peines (`T.A.P.`), ou générique (`Trib.`)
- **Tribunal de l'entreprise** — `Trib. entr.` (référencé comme le tribunal de la famille : siège, division, mention `fr.`/`néerl.` à Bruxelles)
- **Tribunal de commerce** — `Comm.` (ancienne dénomination)
- **Tribunal du travail** — `Trib. trav.`
- **Tribunal de police** — `Pol.`
- **Justice de paix** — `J.P.` + canton
- **Tribunal d'arrondissement** — `Trib. arr.`

Éléments gérés, dans l'ordre du Guide :

1. abréviation de la juridiction ;
1bis. mention linguistique `fr.` / `néerl.` pour les juridictions bruxelloises (depuis le 31 mars 2014) ;
2. siège (en toutes lettres, sauf Cassation) ;
2bis. division territoriale (`div. …`) ;
2ter. canton pour la justice de paix (`2e cant.`, `siège de …`) ;
3. chambre (n° ou nature, entre parenthèses) ;
4. date du prononcé (jour en chiffres, mois en toutes lettres, année en chiffres — formatage automatique) ;
5. revue (en italique, abrégée) ;
6. année de la revue ;
6bis. numéro de livraison (le cas échéant : `2024/4`) ;
7. page ;
7bis. ministère public : **conclusions** (`concl.`), **avis** ou **rapport** (`rapp.`), + fonction du magistrat + nom éventuel ;
7ter. note ou observations (`note` / `obs.` + auteur éventuel).

Le **tribunal de l'entreprise** (`Trib. entr.`) est disponible ; le tribunal de première instance générique a été retiré du menu.

Pour la **justice de paix**, l'outil gère les cantons à plusieurs sièges : après le nom du canton, on précise le siège (`, siège de …` / `, siège d'…` avec élision automatique devant une voyelle). Ex. : `J.P. Audenarde-Kruishoutem, siège d'Audenarde`, `J.P. Hannut-Huy, siège de Huy`.

### 2. Cour constitutionnelle (n° 150)

- Dénomination `C.C.` (ou `C.A.` pour la Cour d'arbitrage, avant le 7 mai 2007)
- Date de l'arrêt
- Numéro d'arrêt (`n°112/2012`) — si l'étudiant·e omet le `/année`, l'outil l'ajoute **d'office** à partir de l'année de la décision
- Considérant / passage précis (`B.2.2`)
- Publication en revue et note facultatives (le site étant présumé connu, aucune mention de publication n'est requise par défaut)

### 3. Conseil d'État (n° 156)

- `C.E.`
- Chambre entre parenthèses (`11e ch. réf.`, `ass. gén.`)
- Date de l'arrêt
- Numéro d'arrêt (`n°230.432`) — si le **point de milliers** est omis (`230432`), il est ajouté d'office
- Nom du / des requérant·e·s **en caractères romains** (pas d'italique) — les majuscules saisies sont automatiquement corrigées (`MANSOUR` → `Mansour`)
- **Avis de l'auditeur** (facultatif) : l'auditeur du Conseil d'État remet toujours un *avis* ; on choisit la fonction — `aud.` (auditeur) ou `Prem. aud. c.s.` (premier auditeur chef de section) — et la mention « avis » est ajoutée automatiquement (ex. `avis aud. A. Henkes`)
- **Publication en ligne** (facultatif) : si la décision n'est publiée que sur le site du Conseil d'État, celui-ci n'est **pas** reproduit (présumé connu) ; seul un **autre** site figure dans la référence (« disponible sur … »)
- Considérant / passage précis et publication en revue facultatifs

---

## Cas transversaux pris en charge

- **Publication sur internet** (n° 164) : `, R.G. n° …, disponible sur [site]`
- **Décision inédite** (n° 166) : `, inéd., R.G. n° …`
- **Décision citée en sommaire** (n° 167) : `(somm.)` en fin de référence
- **Pasicrisie antérieure à 1999** (n° 171) : tome en chiffre romain entre l'année et la page
- **Conclusions du ministère public** : fonctions usuelles proposées (Proc. gén., prem. av. gén., Av. gén., Aud., subst. proc. Roi…)
- **Note / observations de doctrine**

---

## Règle de ponctuation appliquée

Conformément au Guide, certains éléments se **collent** à l'élément précédent **sans virgule** : la mention linguistique (`fr.` / `néerl.`), le siège et la chambre (entre parenthèses). Tous les autres éléments sont précédés d'une virgule. Le premier élément (nom de la juridiction) n'est jamais précédé d'une virgule.

Exemples produits par l'outil :

- `Comm. Charleroi (1re ch.), 15 mai 2006, J.L.M.B., 2006, p. 1092.`
- `Civ. fr. Bruxelles (9e ch.), 24 mars 2015, J.T., 2015, p. 507.`
- `C. trav. Gand, div. Bruges, 22 mai 2015, N.J.W., 2015, p. 647, note C. Van Severen.`
- `J.P. Mons, 2e cant., 9 octobre 2015, J.L.M.B., 2015, p. 1876.`
- `Cass. (1re ch.), 7 octobre 2011, Pas., 2011, p. 2164, concl. Av. gén. A. Henkes.`
- `C.C., 14 juillet 2016, n°112/2012, B.2.2.`
- `C.E. (11e ch. réf.), 6 mars 2015, n°230.432, Mansour.`

---

## Règles typographiques appliquées

- Le **nom de la revue** est systématiquement mis en *italique*.
- Le **nom du requérant** devant le Conseil d'État reste en caractères **romains**.
- La **date** est mise en forme automatiquement (jour en chiffres, mois en toutes lettres).
- L'**intitulé de la chambre** saisi en toutes lettres est automatiquement remplacé par son abréviation officielle (`saisies` → `sais.`, `référé` → `réf.`, `chambre de la jeunesse` → `jeun.`, `chambre du conseil` → `ch. cons.`, `1re chambre` → `1re ch.`, etc.). Une suggestion s'affiche en direct sous le champ.
- Un **chiffre seul** saisi pour la chambre est mis en **ordinal avec « e » en exposant** et complété : `2` → `2ᵉ ch.`, `11` → `11ᵉ ch.`, `1` → `1ʳᵉ ch.`. Les ordinaux déjà saisis (`9e ch.`) reçoivent aussi l'exposant. L'exposant est conservé lors de la copie avec mise en forme.
- Le **nom des auteurs** (note, observations, ministère public) et des **requérants** est normalisé : minuscules avec majuscule initiale, tandis que les **initiales** restent en majuscules (`JEAN DUPONT` → `Jean Dupont`, `A. Henkes` reste `A. Henkes`).
- La mise en forme (italique) est conservée lors de la copie via le bouton **Copier (avec mise en forme)** (format HTML dans le presse-papiers).

---

## Choix de la revue

Le champ « Revue » accepte **deux modes de saisie** :

- l'**abréviation** directement (liste exhaustive du Guide, p. 239 — proposée en autocomplétion) ;
- le **nom complet** de la revue (Guide, p. 209) : l'outil affiche alors l'**abréviation suggérée** et l'utilise dans la référence.

La liste embarquée reprend l'ensemble des périodiques du Guide (près de **300 revues**, listes des p. 209 et 239), dont la nouvelle **R.F.R.L. — Revue de fiscalité régionale et locale**. Toute abréviation non répertoriée saisie par l'utilisateur est reprise telle quelle.

Pour les **auteurs de notes** (et les observations), le champ demande l'**initiale du prénom + le nom** (ex. `C. Van Severen`) ; laissé vide si l'auteur est inconnu, la mention « note » figure alors seule. Le champ « Page » est intitulé **« Page ou numéro »** (certaines revues, comme la *R.G.A.R.*, numérotent les décisions plutôt que les pages), et le champ « Tome / partie » n'est plus réservé à la *Pasicrisie* (donnée à titre d'exemple).

---

## Règle relative aux requérants (Conseil d'État)

Le nom du / des requérant·e·s est formaté automatiquement selon le nombre saisi (noms séparés par des virgules) :

- **1** requérant : nom seul ;
- **2 ou 3** requérants : reliés par « et » ;
- **4 et plus** : premier nom suivi de « et crts. » ;
- **anonyme** : remplacé par « X » (case à cocher).

---

---

## Note sur les données

Les abréviations et les revues sont extraites de la liste du Guide (Livre III, « Les abréviations », p. 209 et 239). Les **abréviations** (l'élément qui figure dans la référence) ont été vérifiées ; quelques **noms complets** longs peuvent comporter une césure mineure, sans incidence sur la référence produite. L'étudiant·e peut toujours saisir librement une abréviation absente de la liste, et toute revue manquante peut être signalée.

---

## Notes techniques

- Application **100 % client-side** : un seul fichier HTML, sans dépendance externe, sans serveur.
- Compatible avec tous les navigateurs modernes (Chrome, Firefox, Edge, Safari).
- Aucune donnée n'est transmise à un tiers.

---

*Document rédigé à l'usage des étudiant·e·s en droit — HE2B / Isabelle Lemineur*
