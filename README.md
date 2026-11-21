# Suivi export — conteneurs de sanitaire

![Tableau de bord du suivi export](assets/export-conteneurs.png)

Un classeur de pilotage export pour l'écoulement d'un stock de baignoires, receveurs et robinetterie (Jacob Delafon) revendu à l'export, en Afrique de l'Ouest.

Contexte : une SARL montée à cinq associés pour reprendre un gros stock et le revendre. J'ai pris en charge tout le processus export, de l'usine à la réception client : plan de chargement, volumétrie, dossier douanier, transitaire, suivi et encaissement.

## Les quatre chiffres

| Indicateur | Valeur |
|---|---|
| Conteneurs expédiés | 12 (40'HC et 20'GP) |
| Taux de remplissage moyen | 90,8 % |
| Valeur marchandise | 1,1 M€ |
| Marge transport | 91 923 €, soit 8,4 % |

## Ce que contient le classeur

- **Lecture** — le contexte et la règle d'or.
- **Conteneurs** — 12 expéditions : destination, contenu, type, valeur, fret, marge, statut.
- **Volumétrie** — volume utile contre volume chargé, taux de remplissage, coût au m³. Un conteneur mal chargé, c'est du vide payé au prix du fret.
- **Douane** — valeur FOB, fret, assurance, valeur en douane, transitaire, bon pour paiement, statut documentaire.
- **Paiements** — factures, échéances, encaissements, soldes et retards.
- **Tableau de bord** — les six indicateurs qui comptent.

## La logique, en trois règles

1. **Coût au m³** : fret divisé par le volume réellement chargé. C'est l'indicateur qui dit si le conteneur est rentable.
2. **Valeur en douane** : FOB + fret + assurance.
3. **Solde dû** : montant facturé moins encaissé, avec le retard en jours.


## Le dossier d'expédition, sept pièces

Un envoi, ce n'est pas une facture. C'est un dossier où chaque pièce doit répondre aux autres au chiffre près.

[Ouvrir le dossier complet (PDF, 7 pages)](documents/dossier-expedition.pdf)

1. **Facture export** — désignation bilingue, poids net, quantité, prix unitaire, montant, puis EXW, fret et total.
2. **Colisage** — ce qui était commandé, ce qui est réellement parti, et l'écart assumé : sept palettes restées à quai, quarante-deux receveurs indisponibles.
3. **Reçu de commande** — la confrontation vendeur / acheteur, échéances et lignes en attente, signée des deux côtés.
4. **Avoir** — la contrepartie financière des lignes non expédiées, valorisées au prix de la facture d'origine.
5. **Ordre de transport** — la réservation passée à Maersk : booking, navire, ports, conteneur, pré-transport, fret.
6. **Dossier douane** — le bordereau de transmission au commissionnaire : neuf pièces, données déclarées, valeur en douane.
7. **Choix de l'incoterm** — la note de décision : ce que chaque incoterm met à la charge du vendeur, et pourquoi FOB ici.

C'est cette cohérence que je tenais : le colisage justifie la facture, le reçu explique l'écart, l'avoir le solde, le booking fixe le départ, le dossier douane autorise l'embarquement.

## Comment l'ouvrir

Télécharger `Suivi-export-conteneurs-sanitaire.xlsx` et l'ouvrir dans Excel, LibreOffice ou Google Sheets.

L'étude de cas complète est dans [ETUDE-DE-CAS.md](ETUDE-DE-CAS.md).

## Auteure

**Fahima Behillil** — chargée de projet IA & automatisation
[LinkedIn](https://linkedin.com/in/fahima-be) · [GitHub](https://github.com/Fahima94) · horizonsdatas@gmail.com

> Données de démonstration, calibrées sur les volumes réels. Aucun tarif fournisseur ni nom de client réel.
