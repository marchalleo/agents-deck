# agents-deck — Cahier des charges
**Statut** : ✅ validé le 23/11/2026 · **Mis à jour** : 23/11/2026

**En une phrase** : un tableau de bord qui montre d'un coup d'œil où en sont toutes tes sessions Claude Code (au travail, en attente de toi, terminées). Il est basé sur le projet [brushknight/agents-deck](https://github.com/brushknight/agents-deck), qu'on adapte à l'agence.

| | |
|---|---|
| **Pour qui** | Léo, usage purement privé |
| **Budget** | 0 € pour la V1 · environ 33 $ pour l'écran 4″ (V3) · du filament pour le boîtier |
| **Contraintes** | Mac à puce Apple sous macOS 26.6 · sessions sur le Mac seulement (pas celles du cloud) · projet de l'auteur sans licence, donc usage privé uniquement |
| **Dépôt** | Fork **public** de l'auteur, sur ton compte GitHub, sous le nom `agents-deck` (renommable plus tard) |
| **Équipe** | 🧭 🎨 💻 🛠️ + expert 🔌 ingé électronique (pour l'écran ESP32) |

## V1 — « Ça tourne chez moi »
Ce qu'elle fait :
- La version de l'auteur est installée sur ton Mac, **sans rien modifier**.
- Tes sessions Claude Code apparaissent dans la **barre de menu**, avec leur état : au travail, t'attend, terminé.
- Tu peux répondre à une demande de permission directement depuis le tableau.
- Tu tiens une **liste « ce que je veux changer »** pendant l'essai.

C'est fini quand : tu lances une session Claude Code dans `~/Leamaginarium`, tu la vois apparaître dans la barre de menu, et tu acceptes une demande de permission depuis le tableau.

**➜ Décision à la fin de la V1** : garder le fork et suivre l'auteur, ou refaire notre propre version, plus légère. On la prend selon tes essais et l'activité de l'auteur.

## V2 — « À notre image »
- **Interface en français**. Si on garde le fork : on ajoute un fichier de traductions. Si on refait notre version : textes bilingues dès le départ.
- **Style** : couleurs, polices, créatures et mascottes, identité Leamaginarium, disposition. On le précisera dans un brainstorm, à partir de ta liste d'envies.
- **Un nom à nous**.

## V3 — « Sur le bureau »
- **Écran carré 4″** (Waveshare ESP32-S3-Touch-LCD-4), flashé et branché en USB. Il affiche les mêmes tuiles que le Mac.
- **Boîtier imprimé en 3D** autour de l'écran.
- *La V2 et la V3 peuvent s'inverser selon le moment où tu achètes l'écran.*

## Plus tard
- Page web, la moins prioritaire des façons d'afficher le tableau.
- Voir le tableau sur le téléphone, si l'auteur construit son app.
- Voir aussi les sessions cloud, si c'est faisable : étude à mener.
- Un site web.

## Hors périmètre
- Lien avec Zee.
- Traduire la documentation et les commentaires du code.
- Contacter l'auteur.
- Windows et Linux.

## Note d'organisation
Les fichiers de l'agence (`brainstorm.md`, `cahier-des-charges.md`, `decisions.md`, `etat.md`, plus un petit `CLAUDE.md` qui renvoie aux règles techniques de l'auteur dans `AGENTS.md`) sont ajoutés à la racine du fork. On ne touche à aucun fichier de l'auteur, pour pouvoir récupérer ses mises à jour sans conflit.
