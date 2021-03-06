Formats de fichiers
======================

Formats de fichiers spécifiques d'osu!
-----------------------------------------

### Archive

| Format du fichier                           | Usage                                                                                            |
|---------------------------------------------|--------------------------------------------------------------------------------------------------|
| [.osz][Osz Link]       | Fichier beatmap exécutable.                                                                        |
| [.osk][Osk Link]       | Fichier skin exécutable.                                                                            |
| [.db][Db Link]        | Fichier de base de données.                                                                              |

### [Éditeur de beatmap](/wiki/Beatmap_Editor)

| Format du fichier                           | Usage                                                                                            |
|---------------------------------------------|--------------------------------------------------------------------------------------------------|
| [.osu][Osu Link]        | [Compose](/wiki/Compose), [Timing](/wiki/Timing), [Song Setup](/wiki/Song_Setup). |
| [.osb][Osb Link]       | [Design](/wiki/Design).                                                                     |

### Replay

| Format du fichier                                 | Usage                                                                                            |
|---------------------------------------------|--------------------------------------------------------------------------------------------------|
| [.osr][Osr Link]       | Fichier replay exécutable (n'est pas décompressable).                                        |

Créer un fichier .osz/.osk
----------------------------

.osz/.osk est une extension de fichier lié spécifiquement pour osu!.exe. Quand ouverts, les fichiers .osz seront extraits par osu!.exe et transférés au dossier "Songs" tandis que les fichiers .osk seront extraits et transférés au dossier "Skins". Par défaut, les fichiers beatmaps téléchargés directement depuis le site officiel seront généralement au format .osz. Créer un fichier .osz/.osk est une connaissance essentielle pour la communauté du beatmapping/storyboarding et du skinning.

### Depuis un logiciel d'archivage

**Programmes nécessaires :**

-   Logiciel d'archivage des fichiers (WinRAR, 7zip)
-   osu! (Afin de tester et pour l'icone d'osu!)

**Procédure**

1.  Compilez vos fichiers dans un dossier (.mp3, .flv, .osu, SB, etc. dans le dossier) et nommez-le.

    Pour des raisons d'explication, le dossier sera nommé "Amigo Fiesta".

2.  Faites un clic droit sur le dossier et choisissez d'archiver le dossier (Ajouter à l'archive...).

    Vous pouvez aussi choisir d'ouvrir le logiciel d'archivage et de faire glisser le dossier à l'intérieur.

3.  Vérifiez les paramètres. Réglez la méthode d'archivage en ".zip" (pas .7z, .rar) et renommez l'extension du dossier en .osz manuellement dans la boîte de dialogue.

    Amigo Fiesta.zip -&gt; Amigo Fiesta.osz, Méthode d'archivage : ".zip"

4.  Laissez l'archivage se faire. Un fichier .osz sera produit avec l'icône distinctive d'osu! pour le fichier.
5.  Faites de même pour d'autres archives. Pour le skinning, utilisez l'extension .osk.

**Exemples en images** (anglais, remerciment au [tutoriel de Skinning](https://osu.ppy.sh/forum/t/51694) de [MLGnom](https://osu.ppy.sh/u/46620))

-   [WinRAR](http://puu.sh/1MBV)
-   [7-zip](http://puu.sh/1MBW)
    -   Pour les beatmaps, utilisez l'extension .osz.

### Depuis le jeu

**Programmes nécessaires :**

-   osu! (et rien d'autre, puisque le jeu peut créer des .osz/.osk)

**Procédure**

1.  Comme ci-dessus, compilez vos fichiers dans un dossier.
    - Normalement, si vous avez édité la beatmap auparavant, tout sera prêt à être converti en .osz. Pour les skins, vous devez obligatoirement compiler les fichiers avant.

2.  Ouvrez osu!.
3.  Si vous voulez créer un .osz, alors :
    - Allez dans "Edit" et choisissez la beatmap à convertir en .osz.
    - Cliquez sur "File", puis sur "Export Package..."
    - Le fichier .osz sera créé et placé dans le dossier "Exports" du dossier d'osu!.

4.  Si vous voulez créer un .osk, alors:
    - Premièrement, soyez sûrs que votre skin possède tous les fichiers que vous voulez compiler. Vous pouvez vérifier en cliquant sur "Open Skin Folder" si vous utilisez le skin à convertir.
    - Puis dans le menu "Options", cliquez sur "Sélectionner un Skin".
    - Sur l'écran de sélection du skin, choisissez le skin que vous voulez et cliquez sur "Exporter en .osk".
    - Le fichier .osk sera créé et placé dans le dossier "Exports" du dossier d'osu!.

[Osz Link]: /wiki/osu!_File_Formats/Osz_(file_format)
[Osk Link]: /wiki/osu!_File_Formats/Osk_(file_format)
[Db Link]: /wiki/osu!_File_Formats/Db_(file_format)
[Osu Link]: /wiki/osu!_File_Formats/Osu_(file_format)
[Osb Link]: /wiki/osu!_File_Formats/Osb_(file_format)
[Osr Link]: /wiki/osu!_File_Formats/Osr_(file_format)
