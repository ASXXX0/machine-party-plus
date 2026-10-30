# Machine Party Overtime

Mod non officiel pour **Machine Party** (Steam). Ajoute 24 mini-jeux, réactive 3 mini-jeux coupés, et ajoute une
finale, un saut, des provocations, des fantômes, des pannes d'usine, des titres de fin, 3 accessoires et le
changement des touches, et **L'Atelier** : crée tes propres cartes (21 pièces) et partage-les sur le **Store** en ligne (menu principal).

## Telecharger

**[TELECHARGER MACHINE PARTY OVERTIME (mpplus-13)](https://github.com/ASXXX0/machine-party-plus/raw/main/MachinePartyPlus.zip)**  
Toutes les versions : [Releases](../../releases).

## Installer

1. Télécharge le zip ci-dessus (`MachinePartyPlus.zip`).
2. Ferme Machine Party, décompresse le zip et double-clique sur `Installer.bat`.
3. Lance le jeu depuis Steam. En bas à droite du menu, la version doit commencer par `mpplus-`.

Ensuite, le jeu propose lui-même les nouvelles versions (bouton « Mettre à jour » au menu principal).
Pour jouer ensemble, tout le monde doit avoir la même version.

`Desinstaller.bat` remet le jeu comme avant.

## Ce que fait l'installateur

Le zip ne contient aucun fichier du jeu. L'installateur trouve le jeu dans ta bibliothèque Steam, télécharge
[GDRE Tools 2.7.4](https://github.com/GDRETools/gdsdecomp/releases/tag/v2.7.4) (vérifié par SHA-256),
décompile depuis ta propre copie les quelques scripts que le mod modifie, applique les modifications et ajoute
`override.cfg` à côté de `Machine Party.exe`. Aucun fichier d'origine n'est modifié.

`latest.json` décrit la dernière version ; le mod le lit pour proposer les mises à jour.

Mod réalisé avec l'aide d'une IA (Claude). Non affilié aux auteurs de Machine Party.
