# Projet Git et Github
Github est un serveur d'hébergement
Git est un explorateur qui permet de travailler sur un même code à plusieurs

## Pour créer des clefs
ssh-add ~/.ssh/id_ed25519
ssh-keygen -t ed25519-sk -C "your_email@example.com"

### Process pour ajouter commits
### Les étapes
1. Faire une modif en local (ex: sur vscode)
2. git add .       (le '.' est pour add tout le répertoire)
3. git commit -m "message de commit" (mettre un vrai message)
4. git push origin main (pousser les modifications locales vers github)


#### Pour un nouveau projet
echo "# Temp1" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:MalikCyril38/Temp1.git
git push -u origin main

##### Travail collaboratif
S brancher
Résolution de conflit