# Ift3913_Tp1

etudiant: Maya Moussaoui matricule: 20157653
etudiant: Tassadit Bibi matricule: 20221732


lien github: https://github.com/Mentor64355/Ift3913_Tp1.git
IMPORTANT: avant de rouler le code sur le terminal, bien faire en sorte de rouler la fonction javac pour toutes les classes

- javac Jls.java
- javac Nvloc.java
- javac Icsec.java
- javac Egon.java

ensuite vous pouvez utiliser chacune des classes individuellement si souhaite pour les tester de la sorte :

exemple pour javac Jls.java faire "java Jls folderPath"

UTILISATION : 
*** toutes les operations suivantes doivent etre effectuees sur la console 
- appelez en premier Jls afin d'avoir le fichier csv (jls.csv) en sortie qui va etre pris comme argument pour Icsec
    - Entre : Jls prend comme argument le chemin d'acces du dossier qui contient le code Java 
    - Sortie : jls.csv 
- appelez ensuite Icsec afin d'avoir le fichier csv (Iscec.csv) en sorte qui va etre pris comme troisieme argument pour Egon
    - Entre : Icsec prend comme arguments le chemin d'acces d'un dossier et le fichier jls.csv
    - Sortie : Icsec.csv
- appelez maintenant Egon afin d'avoir le fichier csv (egon.csv) en sortie qui contient les classes divines
    - Entre : arg[0]: chemin d'acces d'un dossier qui continet le code java - arg[1]: le seuil en % - arg[2]: fichier de sortie de Icsec (Icsec.csv)
    - Sortie : egon.csv dans le cas ou on trouve des classes divines sinon un message," aucune classe suspectee divine ", va s'afficher.
    3.1. essayez avec les seuils suivant : 1%,5%,10%
- Nvloc est directement teste a partir de Egon, par contre elle peut etre testee individuellement en prenant comme entree le chemin vers un fichier qui contient du code java
    - Entre : chemin d'un fichier avec du code java
    - Sortie : nombre de ligne de code non vide sans inclure les commentaires 
