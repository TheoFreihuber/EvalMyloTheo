# Collaborateur
Theo Freihuber
Mylo Wierez

# Date de début du projet
23/10/2025 - 11:28

# Journal des commandes 

Mylo : git clone https://github.com/TheoFreihuber/EvalMyloTheo.git  ( clonnage en local du projet github )
Mylo : cd EvalMyloTheo/ ( je suis rentré dans le dossier du projet )
Mylo : nano README.md ( puis j'ai écrit toute les étapes si dessus)


Theo : git checkout --track origin/travail (Je crée une nouvelle branch en local avec le meme nom que la branch distante travail et le lie les deux, de plus je me met sur la branch travail)
Theo : touch todolist.txt (crée un fichier todolist.txt)
Theo : nano todolist.txt (j'ai rempli le txt des etapes du tp)
Theo : git add . (pour ajouter toutes les modifications a l'index)
Theo : git commit (pour commit tout ce qui se trouve dans l'index, cela ouvre un editeur de texte permettant d'écrire une description du commit (on peut egalement faire -m 'le message' ) 
Theo : git push pour envoyer toutes les modifications sur la branch travail en distante

Mylo : git checkout origin/travail ( joindre la branche de théo ) 
Mylo : touch presentation.txt ( création du fichier ) 
Mylo : nano presentation.txt ( modification )
Mylo : git add . ( ajoute tout à l'index )
Mylo : git commit ( dire ce que j'ai modifié )
Mylo : git push ( envoyer tout sur le github )

Theo & Mylo : git checkout -b "le nom très gentil de notre nouvelle branch" (création et déplacement vers une nouvelle branche)
Theo & Mylo : git nano "blablaDe<nomRespectif>" (création d'un fichier et ouverture de l'editeur de text pour inscrire du blabla) 
Theo & Mylo : git push origin/"le nom toujours très gentil de notre branch" (envoie au distant nos nouvelles branch)
Theo : git checkout --track origin/"le nom de la branch adorable" (pour des raisons obscure cette commande n'a pas marché, a donc suivi en guise de contournement les commandes suivantes)
Theo : git checkout -b "le nom de la branch de mylo" (crée une branch a destination du contenu de la branch de mylo)
Theo : git branch -u "le nom de la branch de mylo" (pour des raisons obscure cette commande non plus n'a pas fonctionné)
Theo : git fetch (soyons honnête, cette commande a tout debug, mais je n'ai aucune idée de se qu'elle fait)
Theo : git branch -u "le nom de la branch de mylo" (pour des raisons obscure cette commande a ENFIN décider de fonctionné)
Theo : git pull (on ne présente plus cette commande .... vraiment ya besoin ? .. bon elle récupère tout les fichier de la branche lié au distant (donc la branch que mylo a mit au distant plus tôt))
Theo : git checkout main (pour aller sur la branch principal)
Theo : git merge "le nom de la branch de mylo (pour merge sur la branch principal le contenu de la branch de mylo )
Same shit but avec ma branch a moi
Theo : git add . 
Theo : git commit -m "le message"
Theo : git push (ET C'EST ENFIN FINI)

puis ya les modifications que je suis entrain de faire sur le readme.md directement dans le main parce que j'ai la flemme into add . -> commit "j'ai modifier le readme voila voila" -> push et voilà au revoir 