# Étude de cas — exporter 12 conteneurs de sanitaire

## Le contexte

Une SARL montée à cinq associés, avec un objectif simple : reprendre un important stock de baignoires, receveurs et robinetterie Jacob Delafon et le revendre. On m'a parachutée sur ce projet pour en tenir toute la partie export.

Pas de service structuré, pas de process existant : il fallait construire la méthode en marchant, et surtout ne pas se tromper. Un conteneur parti avec les mauvais documents reste bloqué en douane, et c'est le client qui ne reçoit pas sa marchandise.

## L'enjeu

Trois risques, tous coûteux.

**Le vide dans le conteneur.** Le fret se paie au conteneur, pas au mètre cube. Un chargement mal préparé, et on paie du vide sur 10 000 km.

**Le dossier douanier.** Valeur FOB, fret, assurance, valeur en douane, facture pro forma, bon pour paiement : une pièce manquante et le conteneur attend.

**L'encaissement.** Livrer sans être payé, c'est financer le client. Il fallait suivre chaque facture, chaque échéance, chaque retard.

## La méthode

### 1. Calculer le chargement avant de charger

Pour chaque conteneur, je comparais le volume utile (76,3 m³ en 40'HC, 33,2 m³ en 20'GP) au volume réellement occupé par les palettes et les cartons. J'ajustais ensuite avec du petit sanitaire pour combler les vides.

Résultat sur la série : **90,8 % de remplissage moyen**, avec un point bas assumé sur un conteneur de baignoires fonte, limité par le poids et non par le volume.

### 2. Tenir le coût au mètre cube

Fret divisé par volume chargé : **76,57 €/m³ en moyenne**. C'est le chiffre qui permet de dire si une expédition est rentable, et de arbitrer entre un 20 pieds et un 40 pieds selon le volume réel.

### 3. Monter le dossier avant le départ

Pour chaque conteneur : valeur FOB, fret, assurance calculée à 0,35 %, valeur en douane, transitaire (Maersk le plus souvent, CMA CGM pour deux départs), puis le bon pour paiement qui débloque l'expédition.

### 4. Suivre l'argent

Douze factures, échéances échelonnées, encaissements partiels. Le tableau isole le solde dû et les retards : **364 000 € restant à encaisser, deux factures en retard** sur la série.

## Les résultats

- 12 conteneurs expédiés vers Abidjan, Dakar, Douala, Cotonou et Lomé.
- 1,1 M€ de valeur marchandise.
- **91 923 € de marge transport, soit 8,4 %**, au-dessus de l'objectif de 8 %.
- 824 600 € encaissés à date.

## Ce que ce projet démontre

Je sais tenir une chaîne logistique complète : chiffrer, documenter, expédier, suivre, relancer. Et je sais construire l'outil qui rend cette chaîne lisible — ici un classeur à six onglets, avec des formules qui recalculent le coût au m³, la valeur en douane et les soldes.

Pour un poste de chargée de projet ou d'appui PMO, c'est la même compétence : suivre des engagements, prévenir les blocages, et tenir un tableau de bord que tout le monde comprend.

## Les limites

Données de démonstration, calibrées sur les volumes réels de l'opération. Les noms de clients et les tarifs fournisseurs ne figurent pas dans le fichier. Les numéros de conteneurs sont fictifs.

---

**Fahima Behillil** — [LinkedIn](https://linkedin.com/in/fahima-be) · [GitHub](https://github.com/Fahima94) · horizonsdatas@gmail.com
