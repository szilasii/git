# Mi az a GIT és GITHub?

## Git
A git egy elosztott verziokezelő rendser, amelyet Linus Torvald fejlesztett 2005-ben. Lehetővé teszi:
- Kódválátozások nyomon követését.
- Korábibbi kódverziókhoz való visszatérést
- Párhuzamos fejlesztést branch-eken
- Offline munka a teljes projekt történelmével

## GitHub
A GitHub egy felhőalapú platform Git repository-k tárolására és kezelésére. Funkciói:
- Repository hosting
- Egyműködési eszközök (Issue, Pull Request)
- CI/CD Integráció (GitHub Actions)
- Projektmenedzsment (Projects, Milestones)
- Kód review és biztonság

> Összefoglalva</br>
**Git** = verziókezelő eszköz a gépeden **GitHub** = onlene platform a repository-k tárolására

## Miért érdemes megtanulni?
 - Csapatmunka (Több fejlesztő dolgozhat ugyanazon a projekten)
 - Biztonság (Kód biztonságos tárolása, pl nem vész el)
 - Történet  (Minden változás visszakövethető)
 - Visszaállítás (Bármikor visszatérhetünk a korábbi verzióhoz)
 - Iparági standard (A legtőbb cég **elvárja** a Git ismeretét)

 ## Telepítés

 ### Ellenörzés

 >git --version
 >git version

 ## Git alapvető parancsok

 ### Lokális repository létrehozása

 git init

 git add .

 git commit -m ""

 git log

 git reset HEAD~1

 git status

git remote add origin https://github.com/szilasii/git.git
git branch -M main
git push -u origin main
 

