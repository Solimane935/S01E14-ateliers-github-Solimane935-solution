# Instruction de l'atelier épisode 14 de Solimane

-**Préparer l'environnement de travail:**<br>

- Création d'un dossier  dans "C:\user\student\DWAQILIN\s01" qui s'appellera"E14".
  
-**Cloner le projet:**<br>

- Se connecter sur le repo, cliquer sur l'onglet "Code" et sous l'onglet "SSH" copier l'url du Repo.
- Ouvrir un terminal positionné dans le répertoire "E14".
- Utiliser la commande Git clone avec comme argument l'Url (<git@github.com:O-clock-Ra/S01E14-atelier-github-Solimane935.git>) du repo.
- Détacher le projet local du projet distant (casser le lien Github)
- Supprimer le dossier .git/
- Si on veut supprimer le dossier par le terminal, on utilise la commande ``rm -R .git/``, il faut valider avant en tapant ``yes``

-**Créer un nouveau repo sur Github**:

- se rendre sur organisation: <https://github.com/O-clock-Ra/S01E14-atelier-github-Solimane935>
- Créer un repo privé sans cocher la case readme.md qui sera nommé <br>
S01E14-atelier-github-votrepseudo-solution vous devriez avoir ceci: ![instructions repo](image.png)
- Ouvrir la console et taper ces commandes:
  
```
   git init

   git add README.md

   git commit -m "first commit"

   git remote add origin git@github.com:O-clock-DWA-Session1/test-charly.git (à    git push -u origin master
   ```

-**Rédiger le fichier instructions.md**

- creer le fichier
- si on souhaite creer le fichier avec le terminal: touch instructions.md
- ouvrir le fichier instructions.md avec vscode et travailler dessus.

-**Sauvegarder son repo local surGithub**

- git add . : indexer les fichiers modifiés
- git commit -m "message de commit": créer le commit
- git push: envoyer la sauvegarde vars github