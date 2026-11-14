## Pokémon Odyssey – Traduction française FR4.1.30

Traduction française non officielle de **Pokémon Odyssey COMPLETE v4.1.1 (EXPANDED BAG)**.
**Traduction complète.** Dans le menu principal, « Continue v4.1.1 » devient « Continuer v4.1.30 » (le numéro de la version FR4.1.30).

> ⚠️ **Mise à jour importante : toutes les versions précédentes (FR4.1.2 à FR4.1.28) ont des bugs.** Remplace ta version par celle-ci. **Ta sauvegarde reste compatible** : garde ton fichier `.sav`/`.srm`, change seulement la ROM.

### Bugs corrigés

L'outil de traduction avait modifié par erreur quelques octets qui ne sont pas du texte (morceaux de code du jeu, scripts, graphismes). Un audit complet de la ROM les a tous trouvés :

| Bug | Versions touchées |
|---|---|
| **Le jeu se fige** quand un Pokémon de l'équipe resté hors du combat monte de niveau (Multi Exp., capture, Pokémon resté dans l'équipe) | FR4.1.5 à FR4.1.28 |
| Deux autres morceaux du code du jeu abîmés (plantage possible) | FR4.1.5 à FR4.1.28 |
| Le combat contre le Garçon de la Sixième Strate (texte d'intro cassé, plantage possible) | FR4.1.14 à FR4.1.28 |
| La scène où l'on reçoit Lokhlass à la Station Aqua (le PNJ reçoit du texte à la place de ses déplacements) | FR4.1.14 à FR4.1.28 |
| Quelques données du jeu légèrement abîmées (graphismes, sons) | toutes les versions |

L'outil exige maintenant une preuve avant de modifier une adresse, et chaque version est testée sur émulateur (parties automatiques avec détection des blocages).

### Autres nouveautés

Cette version regroupe FR4.1.29 et FR4.1.30.

- Le message de fin de combat « Posipi gagne 24 points EXP. ! » est traduit (il était resté en anglais).
- Les descriptions du SAC ne dépassent plus à droite de l'écran.
- Fenêtre de sauvegarde et carte de dresseur : « Temps » (au lieu d'« Heure ») et « Argent » (au lieu d'« Équilibre »).
- Écran Continuer : « Équipe » et « Temps » traduits.

### Installation

1. Pars de ta ROM anglaise **« 1636 - Pokémon Fire Red (U)(Squirrels) »** (la version française de Rouge Feu ne marche pas).
2. Télécharge le hack **Pokémon Odyssey COMPLETE v4.1.1 (EXPANDED BAG)** (liens dans le [README](https://github.com/Shadowix84/Pokemon-Odyssey-Fr#comment-jouer)) : c'est un dossier avec `HOW_TO_PLAY.txt` et le patch `Odyssey.ups`.
3. Avec [Rom Patcher JS](https://www.marcrobledo.com/RomPatcher.js/), applique `Odyssey.ups` sur `Pokémon Fire Red (U)(Squirrels).gba`. Tu obtiens la ROM Odyssey v4.1.1 en anglais (CRC32 `6C5EE1B2`).
4. Télécharge `Odyssey_patch_FR4.1.30.bps` ci-dessous et applique-le, toujours avec Rom Patcher JS, sur la ROM Odyssey de l'étape 3.
5. Lance la ROM obtenue sur émulateur ou console. Pour continuer ta partie, donne à ta sauvegarde le même nom que la nouvelle ROM.

> Le patch FR s'applique directement sur la ROM Odyssey v4.1.1 : inutile d'appliquer les versions FR précédentes avant.
> Aucune ROM n'est distribuée ici.

### Limites connues

Une centaine de libellés de menu (ex. « NOUVEAU NOM », « Point de cueillette ») peuvent encore être coupés à l'écran. Ils sont en cours de vérification en jeu.
Restent en anglais : l'en-tête du menu des quêtes annexes (« Side Quest / Prev. / Next ») et le « Here you are! Thank you! » de la boutique.
Les tailles des Magicarpe et des Scarhino restent en pouces : c'est le jeu qui fait le calcul.

### Bugs et fautes

À signaler dans les [issues GitHub](https://github.com/Shadowix84/Pokemon-Odyssey-Fr/issues/new/choose), avec le formulaire de signalement. Indique ta version (FR4.1.30), ton émulateur, et joins une capture d'écran si possible.

---

**In English:** unofficial French translation patch for Pokémon Odyssey COMPLETE v4.1.1 (EXPANDED BAG). **Important bug-fix update: all previous versions (FR4.1.2 to FR4.1.28) can freeze or corrupt some game data — please update; save files are compatible.** First apply the hack's `Odyssey.ups` patch to "1636 - Pokémon Fire Red (U)(Squirrels)", then apply `Odyssey_patch_FR4.1.30.bps` to the resulting Odyssey v4.1.1 ROM (CRC32 `6C5EE1B2`) with [Rom Patcher JS](https://www.marcrobledo.com/RomPatcher.js/). No ROM included. Bugs: [issues](https://github.com/Shadowix84/Pokemon-Odyssey-Fr/issues/new/choose).
