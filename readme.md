# Git verziókezelés

## Helyi repo létrehozása

- helyi repo inicializálása
    >git init
- ellenőrzés:
    >git status
- előkészítjük a commit-ra(a verzió létrehozására):
    >git add .
- ellenőrzés
    > git status
- commit:
    >git commit -m "first commit"
- a commit-ok listázása:
    >git log

## Helyi repo összekepcsolása a távoli repo-val
- távoli repo létrehozása
-a helyi repo összekapcsolása a távolival:
    >git remote add origin ...\\token@github.com...
- a legelső alkalommal a  push:
    >git push -u origin master
- a továbbiakban
    >git push
### Helyi repoba rendbe tenni és feltölteni a végleges verziót!