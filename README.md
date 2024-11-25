# Examen


git init
git add .

git commit -m "1er commit"


git remote add origin https://github.com/Hunaee/Examen.git

git push -u origin master

git checkout -b formulaire-contact
git add .
git commit -m "Ajout du formulaire de contact"


git push origin formulaire-contact

git checkout main
git merge master
git merge formulaire-contact
