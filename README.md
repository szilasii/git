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

| Szempont | Előny |
| :--- | :--- |
| Csapatmunka |	Több fejlesztő dolgozhat ugyanazon a projekten |
| Biztonság | A kód biztonságosan tárolva, nem vész el |
| Történet |	Minden változás visszakövethető |
| Visszaállítás |	Bármikor visszatérhetsz korábbi verzióhoz |
| Iparági standard |	A legtöbb cég elvárja a Git ismeretét |


 # Telepítés és beállítás

 ## 1. Windows

 Töltsd le a telepítőt: [Letöltés](https://github.com/git-for-windows/git/releases/download/v2.52.0.windows.1/Git-2.52.0-64-bit.exe)

 ## 2. Linux (ubuntu / debian)

 ```
    sudo apt update
    sudo apt install git
 ```
 

 ### Ellenörzés

```
    git --version
    git version
```
 
## 2. GitHub fiók létrehozása
1. Látogass el a github.com/signup oldalra
2. Add meg az email címed (vagy használd a google fiókod és akkor az utóbbiak nem szükségesek)
3. Válassz felhasználónevet és jelszót
4. Erősítsd meg az email címed
 

## 3. Git konfiguráció (Ezeket érdemes beállítani mi nem csináltuk meg)
A GitHub fiókod összekapcsolása a Git-tel:
```
    # Felhasználónév beállítása
    git config --global user.name "Felhasználóneved"

    # Email beállítása (ugyanaz, mint a GitHub-on)
    git config --global user.email "email@example.com"

    # Alapértelmezett branch neve
    git config --global init.defaultBranch main

    # Beállítások ellenőrzése
    git config --list
```
 
# Git alapvető parancsok

 Repository létrehozása (lokális)
```
    # Új repository inicializálása
    git init

    # Meglévő repository klónozása
    git clone https://github.com/user/repo.git

    # SSH-val klónozás
    git clone git@github.com:user/repo.git

```

- ## Alapvető műveletek
```
 # 1. Állapot ellenőrzése
git status

# 2. Fájlok hozzáadása a staging area-hoz
git add .                    # Minden fájl
git add filename.php         # Egy fájl
git add src/                 # Egy mappa

# 3. Változások commitolása
git commit -m "Add: új funkció leírása"

# 4. Feltöltés GitHub-ra
git push origin main
```

- ##  Létező lokális repo hozzárendelése egy távoli repository-hoz
```
    git remote add origin https://github.com/szilasii/git.git
    git branch -M main
    git push -u origin main
```
> CTRL + SHIFT + P code parancsok megnyítása<br>
> CTRL + SHIFT + V Markdown file előnézete


