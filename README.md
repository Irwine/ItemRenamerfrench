# ItemRenamerFrench
Est la traduction du patch Synthesis éponyme pour skyrim. Celui-ci permet de modifier le nom des objets et sorts par l'intermédiaire d'un fichier de configuration utilisateur, dans l'optique de mieux trier ou ajuster le nom des objets selon votre liste de mod.

Un fichier de configuration par défaut est fourni, il contient les informations du jeu de base et de ses DLCs. D'autres fichiers utilisés par l'auteur sont disponibles. Je rajouterais sans doute les miens avec le temps.

# Liste des mods supportés
- Beyond Skyrim - Bruma
- Mysticism

# Configuration
Pour que d'autres mods soient supportés, créez un ou plusieurs fichiers json dans le data du patcher. Ils seront lus par ordre alphabétique.
Pour des instances vous pouvez créer un fichier nommé  CustomRules.json dans le dossier ```C:/../Synthesis/Data/Skyrim Special Edition/ItemRenamer``` .

Si pour une instance vous souhaitez modifier pièces d'or par septims, ajoutez sur une ligne sans oublier les guillemets "" d'ouverture et de fermeture.

```"00000F:Skyrim.esm": "Septim",```

À noter que les dialogues entre autres ne seront pas affectés. Dans cet exemple 00000F est le FormID de l'objet pièces d'or tel qu'il est vu dans xEdit, sans l'index de l'ordre de chargement, et Skyrim.esm est le plugin ou le fichier maître qui définit l'objet à l'origine. La dernière partie de la ligne est le nom que vous souhaitez donner à l'objet ou au sort. Enfin, n'oubliez pas d'ajouter des virgules après toutes les lignes sauf la dernière, ainsi que des accolades ouvrantes et fermantes pour chaque fichier.

Je vous invite à consulter les fichiers du dossier default, lui-même inclus dans le dossier data afin de voir davantage d'exemples.

