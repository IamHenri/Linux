# 55 commandes utiles - https://www.youtube.com/watch?v=We3qE8phJWA
# Navigating and Managing Files
## ls -la 
Lister le contenu d'un dossier

## pwd 
savoir où on se trouve: dans quel répertoire
## cd = change directory
cd / cd .. / cd ~
## mkdir rmdir
mkdir dossier : créer le folder nommé dossier
rmdir = remove
## touch
touch file.txt = créer le fichier file.txt
## cp 
cp file1 file2
cp file1 dir/file1 : copie de la ravine à dir le fichier file1
## mv = move
déplacer un fichier ou le renommer
mv file1 file2 = renomme file1 en file2
## rm
pour remove
rm -rf dir = supprime le dossier dir et tout ce qui se trouve dedans
# Viewing and Finding Files
## cat 
cat bigfile.txt lecture du contenu du fichier en mode texte
## less
less file.txt * permet de scroller dans le fichier file.txt
## head -20 file.txt 
donne les 20 premières lignes d'un fichier
## tail 

## wc -l largefile.txt 
nombre de lignes d'un fichier

# Power User Tools & Automation
## echo "text"
Affiche text dans le shell
## find . -name '.py"
trouve tous les fichiers d'extension .py et présente le nom dans le dossier courrant
## grep label file
cherche le texte label dans le fichier file
## locate file1
donne le chemin vers le fichier file1
# Permission and Archiving
## chmod 755 script.sh
Permissions sur le script 
## chown user file
change le propriétaire de file 
## tar -cfz backup.tar.gz folder_name/
compresse folder_name 
tar -xfz backup.tar.gz pour décompresser
## zip -r project.zip folder_name/
compresse pour tout le monde le dossier récursivement
unzip projet.zip pour décompresser

# Process and System Management
## ps -aux = détail des process en cours
top version dynamique
htop version visuelle

# System, User, and Network Info
## df - h
espace sur le disc -h = human readable
## du -sh *
disk usage dans le répertoire courant : liste des fichiers et de leur taille
## free -h
montre l'usage de la mémoire
## uname -a
donn eles infos du pc
## whoami
nom d'utilisateur dans le système
## id
ensemble de mes id dans le système
## uptime
depuis combien de temps le système est ouvert
## ping url ou IP
donne le résultat du ping 
## wget url
télécharge l'élément sous url dans le répertoire courant
## sudo apt update et sudo apt upgrade 
maintenir son système à jour
## sudo useradd username
ajout de l'utilisateur username
## su - username
permet de switcher sur l'utilisateur username
## systemctl status nginx 
statut du service
## systemctl start nginx
démarrer un service
## sudo journalctl -u nginx 
sudo nécessaire
journal de log du service
## history
liste de toutes mes dernière commandes saisies
## crontab -e
editer les cron
## which python3
donne le chemin vers l'exécutable
## sed 's/error/noerro/g' largefile.txt
remplace error par noerror dans le fichier 
