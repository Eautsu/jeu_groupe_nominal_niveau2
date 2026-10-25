# Le Défi du Groupe Nominal, niveau 2

Jeu de grammaire pour le **cycle 2 et le cycle 3** (du CE1 au CM2). Au niveau 2, chaque carte porte **un seul mot** : un déterminant, un nom, un adjectif ou un verbe. Les élèves trient ces mots selon leur **genre et leur nombre**, selon leur **nature**, ou selon leur **compatibilité** (déterminant + nom, nom + adjectif). Après un défi réussi, ils peuvent gagner un bonus en **reconstituant une vraie phrase** avec des cartes et en conjuguant le verbe.

La version en ligne (`index.html`) se joue au TNI ou sur un ordinateur, de 1 à 4 joueurs, sans connexion.

**Jouer en ligne : [eautsu.github.io/jeu_groupe_nominal_niveau2](https://eautsu.github.io/jeu_groupe_nominal_niveau2/)**

**Générateur de phrases (pour l'adulte) : [generateur_phrases_types.html](https://eautsu.github.io/jeu_groupe_nominal_niveau2/generateur_phrases_types.html)**

Le niveau 1 (cartes « déterminant + nom », tri par genre et nombre) est dans un autre dépôt : [jeu_groupe_nominal](https://github.com/Eautsu/jeu_groupe_nominal).

---

## 1. Ce que l'élève apprend

- **Le genre et le nombre** des déterminants, des noms et des adjectifs.
- **La nature des mots :** reconnaître un déterminant, un nom, un adjectif, un verbe.
- **L'accord dans le groupe nominal :** quels noms vont avec « mon », quels adjectifs vont avec « chat ».
- **La phrase :** compléter une phrase avec un groupe nominal sujet, un verbe conjugué au bon temps et un groupe nominal complément, et accorder le verbe avec le sujet.

---

## 2. Règle du jeu (résumé)

1. **Le contrat.** Le joueur pioche un Joker, puis choisit une **pile de cartes Défi**. On ne voit que les points. La carte révèle la consigne et le nombre de cartes (6, 12 ou 16).
2. **Le corpus.** L'ordinateur étale les cartes-mots, côté texte. Il y a toujours au moins 2 cartes valides et 2 distracteurs.
3. **Le tri.** Le joueur retourne les cartes qu'il pense valides. 1ʳᵉ erreur : il continue. 2ᵉ erreur : le défi est perdu.
4. **L'omission.** Quand il dit « J'ai fini », s'il reste une carte valide sur la table, le défi est perdu.
5. **Les points.** Un défi réussi rapporte les points de la carte. Un défi perdu rapporte 1 point par carte valide trouvée.
6. **Le bonus.** Après un défi réussi, le joueur peut reconstituer une vraie phrase de la banque avec des cartes, dont certaines sont des pièges, et écrire le verbe conjugué au temps demandé. Le jeu vérifie la grammaire et le sens (2 ou 3 essais, au choix dans les paramètres ; après le dernier, il montre la phrase de départ), ou un adulte valide si l'option est cochée : +1 point par carte posée et pour le verbe. Une phrase refusée ne fait pas perdre de point.

**Les 46 cartes Défi**

| Famille | Exemple de consigne | Points |
|---|---|---|
| Genre et nombre | « masculin », « féminin singulier » | 4, 6, 16, 20, 24 |
| Nature | « déterminants », « verbes » | 4, 8, 12 |
| Compatibilité | « déterminant masculin : liste les noms compatibles » | 6, 8, 16 |

**Les 16 jokers**

- *Rejoue sans risque* : 3 vies au lieu de 2 ;
- *Tu doubles les points* ;
- *Une seule erreur et le défi est perdu* ;
- *Annule la dernière action* ;
- *Échange une carte* de la table avec la pioche ;
- *Échange toutes les cartes* de la table ;
- *Transforme un mot* : féminin ↔ masculin, singulier ↔ pluriel, s'il existe dans le jeu.

---

## 3. Les choix pédagogiques et leurs raisons

### Un mot par carte

Au niveau 1, les cartes portent un groupe nominal entier (*des chats*) et l'élève s'appuie sur le déterminant. Au niveau 2, le mot est seul (*chats*, *grandes*, *mes*).

**Pourquoi :** l'élève doit trouver le genre et le nombre **dans le mot lui-même** : la marque du pluriel, le *-e* du féminin, la forme du déterminant. C'est l'étape suivante de l'accord.

### Deux informations au dos : la couleur et le symbole

- **La couleur** donne le genre et le nombre : violet, rouge, vert, jaune. Deux couleurs signalent un mot épicène (*élève*, *triste*) ou invariable (*nez*, *gris*), quatre couleurs un mot qui va partout (*marron*).
- **Le symbole** donne la nature : ★ déterminant, ✿ nom, ● adjectif, 🍃 verbe.
- **Les verbes ont un fond blanc :** ils n'ont ni genre ni nombre.
- **Deux symboles** signalent un mot à double nature : *plat* est un adjectif (un œuf plat) ou un nom (un plat).
- **Pour les daltoniens :** de petits visages dans les coins répètent le genre et le nombre (triangle = masculin, rond = féminin ; 1 = singulier, 2 = pluriel).

**Pourquoi :** la correction reste immédiate et autonome. L'élève voit aussi que la nature et l'accord sont deux questions différentes.

### Les distracteurs choisis exprès

Dans un défi de genre et de nombre, quelques verbes se glissent parmi les mots. Dans un défi de compatibilité, la plupart des distracteurs sont de la bonne nature mais mal accordés (*mon* … *maison*).

**Pourquoi :** le tri n'a de sens que si les mauvaises cartes ressemblent aux bonnes. Un verbe parmi les mots rappelle qu'un verbe n'a pas de genre.

### Les défis de compatibilité

Le jeu tire un mot de référence, par exemple « mon » ou « chat ». L'élève retourne les noms qui vont avec ce déterminant, ou les adjectifs qui vont avec ce nom.

**Pourquoi :** c'est l'accord dans le groupe nominal, vécu comme un essai à voix haute (« mon chat ? mon maison ? »). Le mot de référence rend la consigne concrète.

Les mots dont la forme dépend du mot suivant ne sont pas utilisés dans ces défis : *cet*, *l'*, les noms qui commencent par une voyelle avec un déterminant de référence (*mon école* est juste alors qu'*école* est féminin), *bel*, *nouvel*, *vieil*. Ainsi, la compatibilité ne dépend que du genre et du nombre, ce que le défi travaille.

### Le bonus : reconstituer une vraie phrase

Après un défi réussi, le jeu propose une **vraie phrase de la banque**, choisie et validée par l'adulte avec le générateur. Il choisit de préférence une phrase qui reprend des mots du défi.

- La phrase s'affiche avec des **cases** à la place du groupe nominal sujet, du verbe et, s'il y en a, du complément, de l'adjectif ou du **complément introduit par une préposition** (*Le coq joue avec [la poule].*, *Le garçon va à [l'école].*) : *Hier, [ ] [ ] [ ] [ ] dans le jardin.*
- La **réserve** contient les bonnes cartes, des **pièges d'accord** (autre forme du même mot : *le / les*, *petit / petite*, *chat / chats*) et quelques cartes du défi.
- L'élève **écrit le verbe conjugué** : au temps imposé par un mot comme *hier* ou *demain* (surligné), sinon au présent, au futur, à l'imparfait ou au passé composé.
- Points : 1 par carte posée, plus 1 pour le verbe. Si la banque est vide, le bonus n'est pas proposé.

**Pourquoi :**
- **Des phrases qui ont du sens.** Laisser l'élève assembler des mots au hasard produit des phrases justes mais absurdes (*des pains chantent*). Ici, le point de départ est une phrase validée par l'adulte.
- **Le sens reste vérifié si l'élève change de mot.** Un autre nom ou un autre adjectif est accepté s'il convient au verbe et au nom, d'après les **étiquettes de sens** du corpus (*un chat joue* oui, *la table joue* non). Le message l'explique : « « table » ne peut pas faire l'action « jouer » ».
- **La grammaire reste le cœur du travail.** Les pièges obligent à vérifier l'accord dans le groupe nominal (*les petit chat*), l'accord du verbe avec le sujet (et pas avec le complément du nom : *le chat de mes amis saute*), la place de l'adjectif (*un petit chat*, *un chat noir*), les formes *bel / vieil / nouvel*, *ce / cet*, *mon école*, l'élision.
- **Le verbe suit le programme 2025.** L'élève conjugue lui-même *être*, *avoir* et les verbes réguliers du 1er groupe dès le CE1 ; *faire, aller, dire, venir, pouvoir, voir, vouloir, prendre* à partir du CE2 ; les formes en *-geait*, *-çait* et les autres verbes à partir du CM1. En dessous de ce niveau, la forme est donnée toute écrite (*Hier, les enfants **mangeaient** des pommes*) : l'élève choisit alors un sujet qui s'accorde avec elle. *Les enfants mangent des pommes* reste à conjuguer au CE1. Le générateur l'indique sous chaque phrase.
- **L'orthographe du radical n'est pas sanctionnée.** *manjaient* est accepté (la terminaison est juste) et le jeu montre « on écrit *mangeaient* ». Une terminaison fausse est refusée : *mangent* avec un sujet singulier, *manges*, *mangé* sans auxiliaire, *mange* avec *hier*.
- **L'adulte en option :** la case « Phrase bonus validée par un adulte » remplace la vérification automatique.

### Le générateur de phrases (fichier à part)

[`generateur_phrases_types.html`](https://eautsu.github.io/jeu_groupe_nominal_niveau2/generateur_phrases_types.html) est un outil pour l'adulte, séparé du jeu.

1. **Tirer des cartes**, comme une table de jeu (16 cartes du niveau choisi, le maximum du jeu).
2. Le générateur **propose les phrases possibles avec ce tirage**, en respectant les étiquettes de sens (qui peut faire l'action, ce qu'on peut manger, ce qu'un adjectif peut qualifier). S'il manque une carte (un déterminant, un verbe), il la prend dans le corpus et l'indique. Pour chaque phrase : **👍 Garder** ou **👎 Non**.
3. **Construire sa phrase** : toucher les cartes pour l'écrire, avec les parties de l'élève entre crochets : *Hier, [le petit chat] [a mangé] [une souris] dans le jardin.* Un groupe placé juste après une préposition (*avec, dans, sur, sous, vers, à…*) devient un complément introduit par une préposition : *[Le coq] [joue] avec [la poule].* Après *à*, seuls *la*, *l'*, *un*, *une* sont possibles dans la case (*au*, *aux* restent dans le texte fixe). Le générateur vérifie la grammaire et le temps.
   - **Complément du nom** après le sujet : *[Le chat] de [la voisine] [joue].* L'élève reconstitue les deux groupes ; le jeu refuse *de le*, *de les* (qui s'écrivent *du*, *des*) et un verbe accordé avec le complément du nom. Le générateur en propose aussi de lui-même : *le sac de mon ami*, *le chat de ma voisine*.
   - **Complément après l'adjectif** : *[Le pull] [est] [mouillé] après [la pluie].* (après, avant, pendant, à…)
   - **Prépositions en deux mots** : *près de [la gare]*, *loin de*, *à côté de*, *par-dessus*. Le générateur sort le « de » du crochet de lui-même, et refuse un complément direct après un verbe qui n'en prend pas (*il ira [la baignoire]* → il propose *dans*).
4. **Ajouter une carte libre** : le générateur vérifie si le mot est dans le corpus. Sinon, il propose de l'**ajouter au corpus avec toute sa famille** : un nom au singulier et au pluriel (avec son genre et son sens), un adjectif sous ses quatre formes (avec sa place et ce qu'il peut qualifier), un verbe en -er. Un aperçu (*une pierre · des pierres*, *un sac rouge · une table rouge…*) permet de vérifier avant d'ajouter. Le niveau proposé est CE1.
5. **Enregistrer pour le jeu**, puis déposer `banque_phrases_types.json` dans le dépôt.

**Une banque unique.** Le fichier `banque_phrases_types.json` du dépôt contient les phrases gardées, les phrases refusées (qui ne sont plus proposées) et les mots ajoutés au corpus. Le jeu le lit à chaque ouverture : tous les ordinateurs ont la même banque et les mêmes mots, sans rien importer. Le générateur part aussi de ce fichier et signale ce qui n'est pas encore enregistré ou déposé. Si des phrases de la banque commune manquent dans la liste (par exemple dans un autre navigateur), il le signale et propose de les remettre avant d'enregistrer. Une phrase retirée de la liste passe dans les phrases refusées.

**Les étiquettes de sens** (catégorie de chaque nom, sujets et compléments de chaque verbe, noms que chaque adjectif peut qualifier) sont une proposition, à valider dans `etiquettes_de_sens.xlsx`.

### Les jokers qui transforment les mots

« Transforme un mot masculin en mot féminin », « singulier en pluriel »… Le joueur choisit une carte et elle change de forme : *grand* devient *grande*, *cheval* devient *chevaux*.

**Pourquoi :** l'élève manipule la flexion des mots au lieu de seulement la reconnaître. Il voit aussi qu'un mot épicène ou invariable ne change pas.

### Les paramètres du tirage

Ils sont réservés à l'enseignant ou aux parents :
- **le niveau des mots** (CE1, CE2, CM1, CM2, 6e), d'après le corpus de référence ;
- **les cas particuliers** (mots épicènes, mots invariables, mots à double nature) ;
- **les familles de défis** (genre et nombre, nature, compatibilité). Pour commencer, il vaut mieux n'en cocher qu'une, par exemple « Genre et nombre », puis ajouter les autres quand les élèves sont à l'aise ;
- **le mode simple**, sans sons ni animations.

**Pourquoi :** le même jeu suit la progression de la classe. Le jeu écarte de lui-même les défis impossibles avec les mots choisis.

**Pendant une partie**, le niveau des mots, les cas particuliers et les familles de défis sont verrouillés 🔒 : ils se changent entre deux parties. Seuls le mode simple et la validation de la phrase peuvent changer à tout moment. Sinon, une partie commencée avec certains défis pourrait se retrouver sans les mots pour les jouer.

### Le journal des réussites et des erreurs

Il distingue les erreurs de **genre**, de **nombre** et de **nature**, les oublis, et les phrases bonus.

**Pourquoi :** l'enseignant voit ce qu'il faut retravailler avec chaque élève. Rien n'est envoyé ni exporté.

---

## 4. Le corpus

Les mots viennent du *Corpus de référence v3* (818 cartes, du CE1 à la 6e). Pour la version en ligne, quelques erreurs de classement ont été corrigées, et les mots présents à deux niveaux ont été réunis en une seule carte. Les verbes *être*, *raconter* et *rouler* ont été ajoutés (CE1), et *avoir* est passé du CM1 au CE1, comme au programme de CE1. Trois noms d'instruments ont été ajoutés pour la phrase bonus (« jouer du piano ») : *piano, violon, flûte* et leurs pluriels, niveau CE1. Le déterminant *l'* est passé du CM1 au CE1. Pour le CE1, le corpus suit le programme 2025 (être, avoir et verbes réguliers du 1er groupe, sans -cer, -ger, -yer) : 20 verbes en -er ajoutés (*danser, crier, voler, parler, monter, entrer, rentrer, rester, tourner, laver, fermer, couper, coller, colorier, ramasser, cacher, montrer, toucher, aider, préparer*) et 10 descendus au CE1 (*arriver, glisser, grimper, pleurer, marcher, attraper, compter, quitter, traverser, habiter*) ; adjectifs ajoutés (*vert, jaune, lent, plein, fatigué*) ou descendus au CE1 (*joli, content, triste, gros, long, doux, méchant, gentil, beau, jeune, rapide*). Le déterminant *l'* est passé du CM1 au CE1. Pour le CE1, le corpus suit le programme 2025 (être, avoir et verbes réguliers du 1er groupe, sans -cer, -ger, -yer) : 20 verbes en -er ajoutés (*danser, crier, voler, parler, monter, entrer, rentrer, rester, tourner, laver, fermer, couper, coller, colorier, ramasser, cacher, montrer, toucher, aider, préparer*) et 10 descendus au CE1 (*arriver, glisser, grimper, pleurer, marcher, attraper, compter, quitter, traverser, habiter*) ; adjectifs ajoutés (*vert, jaune, lent, plein, fatigué*) ou descendus au CE1 (*joli, content, triste, gros, long, doux, méchant, gentil, beau, jeune, rapide*). Les formes *vieil, vieille, vieilles* ont été ajoutées (CM1), pour que *vieux* fonctionne comme *beau / bel* et *nouveau / nouvel* (*un vieil arbre*). Les mots ajoutés par l'enseignante avec le générateur sont intégrés au corpus : *élèves, enfants, oreilles, journée(s), nuit(s), cabane(s), cercle(s), pierre(s), pluie(s)* ; les adjectifs *rouge(s)*, *rayé(e)(s)*, *mûr(e)(s)*, *drôle(s)* ; les verbes *aimer, porter, tracer*.

**Les mots à double nature.** Certains mots ont la même forme comme adjectif et comme nom : *plat, blanc, grand, petit, froid, jeune, dernier, voisin…* Ils sont acceptés dans les deux natures, comme une carte deux couleurs est acceptée dans les deux genres. Ils sont **réservés au cycle 3 par défaut** : la case est décochée quand seuls CE1 et CE2 sont choisis, et se coche dès qu'on ajoute le CM1, le CM2 ou la 6e. L'enseignant peut toujours changer ce choix.

**Oublier un mot à double nature n'est pas une faute** quand il ne répond à la consigne que par sa seconde nature (*petits* dans un défi « noms »). Ce mot est d'abord un adjectif : exiger qu'un élève pense à « les petits » (les enfants) ferait échouer le défi pour une raison qui n'est pas celle travaillée. Retourné, il est gagné et la mascotte explique pourquoi ; oublié, il apparaît à la fin avec l'étiquette « ≈ possible aussi », sans pénalité. Il ne compte pas non plus dans le minimum de 2 cartes valides par défi.

**Les mots écartés.** *Fin, rose* et *orange* (et leurs pluriels) changent de genre selon leur nature (*la fin* / *un trait fin*, *une rose* / *le rose*). Ils ne sont pas utilisés : la carte serait juste et fausse à la fois.

---

## 5. Limites connues

- **La vérification automatique des phrases** accepte quatre temps (présent, futur simple, imparfait, passé composé), à la 3ᵉ personne. Le sens est vérifié d'après les étiquettes de sens, qui restent approximatives : les mots fixes de la phrase (*dans le jardin*) ne sont pas contrôlés quand l'élève change de mot.
- **Les verbes ajoutés au corpus** avec le générateur doivent être des verbes en -er réguliers.
- **La place de l'adjectif** est contrôlée par une liste d'adjectifs qui se placent avant le nom.
- **La banque importée** reste dans le navigateur de l'ordinateur où elle a été importée.
- **Les transformations** ne fonctionnent que si la forme cherchée existe dans le corpus.
- **Navigateurs :** le jeu a été testé sous Chrome.
- **Le journal** reste dans le navigateur de l'ordinateur utilisé.

---

## 6. Informations techniques

- **Un seul fichier, entièrement hors ligne :** `index.html` contient tout, y compris les polices d'écriture (Fredoka et Open Sans, sous licence SIL Open Font License) et la banque de phrases types.
- **Le générateur** (`generateur_phrases_types.html`) est lui aussi un fichier unique, hors ligne.
- **Fichiers du dépôt :** `index.html` (le jeu), `generateur_phrases_types.html`, `banque_phrases_types.json` (la banque commune : phrases, refus, mots ajoutés), `README.md`, `LICENSE`, `LICENSE-NOTICE`.
- **Ce qui dépend de l'ordinateur :** les emoji et la voix de la lecture à voix haute.
- **Statistiques de visite :** la page contient le compteur GoatCounter, qui ne compte que les visites et ne dépose pas de cookie.

---

## 7. Licence

Le jeu (règle, textes des cartes et code) est sous licence **[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.fr)**. Voir `LICENSE` et `LICENSE-NOTICE`.

La version en ligne a été réalisée avec l'aide d'une intelligence artificielle (Claude, Anthropic), à partir du jeu, des cartes et des consignes de l'auteure.

---

*Conception du jeu et des cartes : Eautsu.*
