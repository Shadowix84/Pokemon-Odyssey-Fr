# Publication

Chaque dossier contient ce qu'il faut pour publier une version :

- `Odyssey_patch_FR4.x.x.bps` : le patch ;
- `release.md` : le texte de la release ;
- `README.md`, `CHANGELOG.md`, `CONTRIBUTING.md` (facultatifs) : les nouvelles versions de ces pages, copiées à la racine du dépôt au moment de la publication.

Pour publier : onglet **Actions** → **Publier une release** → **Run workflow** → taper la version (ex. `FR4.1.6`) → **Run workflow**.

En un seul clic : la page d'accueil (README) et le journal des modifications sont mis à jour, puis la release est créée avec le tag `FR4.x.x`, le titre « Odyssey FR4.x.x », le texte et le patch joint, et marquée « Latest ».

Le patch à télécharger pour jouer est toujours dans les [Releases](https://github.com/Shadowix84/Pokemon-Odyssey-Fr/releases).

## Issues

- À l'ouverture d'une issue, un message confirme qu'elle est bien reçue et en cours de traitement.
- Quand l'étiquette « corrigé – prochaine version » est ajoutée, un message explique pourquoi (selon l'étiquette de type : texte coupé, faute de traduction, texte en anglais, bug bloquant, suggestion) et annonce la correction pour la prochaine mise à jour.
- À la publication d'une version, ces issues sont listées dans la rubrique « Corrigé » de la release, puis fermées avec le lien du patch.
