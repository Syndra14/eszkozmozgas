# # A projekt könyvtáradba lépj be:
cd path/to/eszkozmozgas

# Git inicializálása és csatlakozás a GitHub repo-hoz:
git init
git remote add origin https://github.com/FELHASZNALO/eszkozmozgas.git

# Kiegészítjük a repo-t hasznos fájlokkal:
echo "Flask QR-eszköz mozgatás" > README.md
echo "eszkozok.db" > .gitignore
echo "flask" > requirements.txt

# Fájlok hozzáadása és commit:
git add .
git commit -m "Initial commit – QR eszköz mozgatás Raspberry Pi-re"

# Feltöltés GitHubra:
git push -u origin master
