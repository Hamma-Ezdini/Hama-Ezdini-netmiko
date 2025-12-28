Mon Projet Netmiko
mkdir mohamed-ezdini-netmiko
cd mohamed-ezdini-netmiko
git init
touch README.md
git add README.md
git commit -m "Ajout du fichier README"
touch main.py
git log --oneline
pip install netmiko
git add main.py interfaces.txt
git commit -m "Ajout de la fonction acces_netmiko"
git checkout main
git merge feature/netmiko
git remote add origin https://github.com/Hama-Ezdini/mohamed-ezdini-netmiko.git
git push -u origin main
git fetch origin
git checkout -b feature/salut origin/feature/salut
git add main.py
git commit -m "Ajout de la fonction dire_salut"
git push origin feature/salut
git pull origin main


