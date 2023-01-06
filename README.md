# Exercice 3 de github  
******************************  
  
liste des commandes utilisé :  
  
echo "bonjour, je suis le fichier de la branche master" > fichier_branche_master.txt  
git init  
git remote add origin https://github.com/aferedye/exercice3.git  
git branch -M main  
git add *  
git commit -m "first commit"  
git push -u origin main  
git checkout -b antoine  
echo "bonjour, je suis le fichier de la branche antoine" > fichier_branche_antoine.txt  
git add *  
git commit -m "second commit"  
git push -u origin antoine  
