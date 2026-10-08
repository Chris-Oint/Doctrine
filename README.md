# Doctrine — cahier de charge

Recueil thématique établi à partir du corpus de brochures **Shekinah + VGR**
(1 597 sermons de William Branham, 406 472 paragraphes).

## Les huit thèmes

| Thème | Passages |
|---|---|
| L'enlèvement (le ravissement de l'Église) | 812 |
| La seconde venue (le retour visible de Christ) | 267 |
| L'ouverture du Livre et des Sceaux | 1 763 |
| Les sept tonnerres (Apocalypse 10) | 354 |
| L'ordre : enlèvement ↔ ouverture du Livre | 147 |
| Différence entre la seconde venue et l'enlèvement | 238 |
| La fin du temps de grâce / la rédemption terminée | 274 |
| Le Millénium (les mille ans) | 741 |

**4 596 passages** retenus au total.

## Règle de sélection

Un passage n'est retenu que si **le contexte du thème est présent d'abord**,
puis le mot :

1. le paragraphe porte un **mot décisif** du thème (« enlèvement »,
   « seconde venue », « sceaux », « tonnerres », « temps de grâce »,
   « Millénium »…) ;
2. et le **contexte** confirme : un autre terme de la même famille dans le
   paragraphe, ou dans les deux paragraphes qui l'entourent ;
3. les thèmes de relation (ordre, différence) exigent la présence des deux
   familles dans le passage ou son voisinage immédiat ;
4. les paragraphes géants (conversion défectueuse) et les sens hors sujet
   (« scellés par le Saint-Esprit ») sont écartés.

Chaque passage est cité avec **le paragraphe qui précède et celui qui suit**
(le fil de la pensée), la référence complète (code, titre, date, édition,
numéro de paragraphe) et, quand elle est citée, la référence biblique.

## Utilisation

Le fichier `index.html` est **autonome** : il fonctionne hors ligne, sans
connexion. Il suffit de le télécharger et de l'ouvrir dans un navigateur.

En ligne : <https://chris-oint.github.io/Doctrine/>

Fonctions :

- recherche plein texte (mots, versets, code de sermon) ;
- filtres par thème, par édition (VGR / Shekinah), par année ;
- tri par pertinence, par date ou par code ;
- marquage « lu » avec barre de progression (mémorisé sur l'appareil) ;
- copie d'un passage avec sa référence et son lien profond ;
- mode nuit, impression ;
- installation comme application (bouton « Installer l'application » ou
  « Ajouter à l'écran d'accueil »).

## Télécharger et installer

- **En ligne** : <https://chris-oint.github.io/Doctrine/> — le bouton
  **Installer l'application** (ou « Ajouter à l'écran d'accueil ») pose le
  cahier sur le téléphone ; il s'ouvre ensuite **sans connexion**, avec le
  même logo que l'application Bible.
- **Fichier autonome** : `Doctrine-cahier-de-charge.html` (13 Mo) — un seul
  fichier, à mettre sur une clé USB ou à envoyer ; il s'ouvre par double-clic
  et fonctionne hors ligne.
- **Archive complète** : `Doctrine-cahier-de-charge.zip` — le fichier, le
  manifeste, le service worker et les icônes (pour l'installation hors ligne).

Les deux se trouvent dans les **pièces jointes de la version** :
<https://github.com/Chris-Oint/Doctrine/releases/latest>

À l'ouverture, le cahier présente le même écran d'animation que l'application
(portrait, panneau qui se déroule, texte qui s'écrit) ; le bouton
**Passer l'animation** l'abrège, et il ne rejoue plus ensuite dans le même
onglet.

## Travailler dans le cahier

Chaque passage porte trois boutons :

- **Lien ⧉** — affiche le lien profond du passage ; on peut le **copier** ou
  le **télécharger** (`60-1231 §52.html` : un fichier qui ouvre le passage
  directement dans l'application, et dont on peut recopier l'adresse pour la
  coller dans un autre navigateur) ;
- **✎ Note** — ouvre un champ d'annotation personnel par passage
  (remarque, réponse, renvoi) ; le passage annoté est marqué « ✎ Note ✓ » ;
- **Copier** — copie la citation complète (référence + texte + lien).

En haut de la page :

- **Mes notes** — n'affiche que les passages annotés ;
- **Exporter mon travail** — télécharge un fichier JSON
  (`doctrine-mon-travail-AAAA-MM-JJ.json`) avec les passages lus et toutes
  les notes, pour les mettre de côté ou les passer à un collaborateur ;
- **Importer** — recharge ce fichier JSON et fusionne avec le travail
  déjà fait sur l'appareil.

Tout est conservé **sur l'appareil** (mémoire locale du navigateur) : rien
n'est envoyé sur un serveur. L'export sert de sauvegarde.

## Passerelle vers l'application

Le bouton **Passerelle ⇄** ouvre la passerelle :

- **Ouvrir §… ↗** (sur chaque passage) ouvre le sermon dans l'application,
  descend au paragraphe et le surligne quelques secondes, **sans animation
  d'ouverture** ;
- **Bible** : les références bibliques détectées dans le texte sont
  cliquables et ouvrent le verset dans l'application, surligné ;
- **À partager** : le lien du cahier, à copier pour un collaborateur.

Format des liens profonds :

- brochure : `https://chris-oint.github.io/Elie-le-Prophete-Shekinah-VGR/#b=63-0317E&p=307&ed=Shekinah`
- verset : `https://chris-oint.github.io/Elie-le-Prophete-Shekinah-VGR/#v=65-10-7`
  (`65` = Apocalypse, `10` = chapitre, `7` = verset)

Le cahier **n'est pas** intégré à l'application Bible : la passerelle sert à
tester la circulation entre les deux, sans modification de la Bible.
