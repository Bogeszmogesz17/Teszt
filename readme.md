#hello
…or create a new repository on the command line
echo "# Teszt" >> README.md #fájl létrehozása, az első sorba "#teszt"kerül
git init #git mappa inicializálása
git add README.md #stagig changes , azaz a változások mentése
git commit -m "first commit" #változások jóváhagyása, és megjelölés beküldésre
git branch -M main #fejlesztési ág átnevezése main-re
git remote add origin https://github.com/Bogeszmogesz17/Teszt.git
git push -u origin main #távoli repo hozzádása origin néven
…or push an existing repository from the command line #a fejlesztési ág feltöltése első alkalommal
git remote add origin https://github.com/Bogeszmogesz17/Teszt.git
git branch -M main
git push -u origin main #feltölti az origin nevű repoba a commitokat

További terminál parancsok
git pill origin main #a friss repo letöltése
git remote -v #aktuális távoli repo lekérdezése
git status #change, stage, commitállapotának lekérdezése
git config --global --list #globális beállítások listázása
cd <directory name>#ChangeDirectory
cd ... #egy mappával feljebb lép
mkdir <directory name> #make directory
rmdir <directory name> #remove directory
ls #list - könyvtár listázása
