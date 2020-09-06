# 13sz osztály bemutatkozása
Osztály projekt a git technológia bemutatása céljából.

## Meghívás kollaborátornak
A projekt github oldalán meghívjuk a tanulókat a projektbe

## Klónozás
A tanulók klónozzák a projektet `git clone url`

## Felhasználói adatok beállítása
Conzol ablakban beállítják a felhasználói adatokat.  
User név: `git config --global user.name xy`  
Email: `git config --global user.email xy@gmail.com`

## Új branch létrehozása
Például Csontos Krisztián `git checkout -b csontos`  
Branch lekérdezése (azon állunk-e?): `git branch`

## A bemutatkozás oldal elkészítése
- legyen a html oldal nevével egyező mappában a képpel együtt
- legyen címe
- legyen title
- tartalmazzon egy rövid bemutatkozó szöveget, 
- legyen benne egy fotó,
- legyen rajt egy link az index.html-re.

## Színpad, commit, push
`git add .`  
`git commit -m "bemutatkozó oldal létrehozás"`  
`git push -u origin branchnév` (ekkor a github-on is keletkezik (-u) egy ilyen nevű branch)  
további push esetén már nem kell -u: `git push origin branchnév`

## A github-on pull request, és merge
A github-bon annak gazdája a keletkezett branch-eken végigmegy és pull request segítségével mergeli az összeset.

## Tanulók: push
Ha kész az összes merge, akkor a tanulók átváltanak master-re: `git branch master`  
Utána pull-al lehúzzák saját repójukba a végeredményt: `git pull`


## Tanulók, branch nevek, bemutatkozás oldalak

- Csontos Krisztián
  - branch: csontos
  - csontos.html
- Farkas Cintia
  - branch: cintia
  - cintia.html
- Horváth Márió
  - branch: mario
  - mario.html
- Juhász Gábor
  - branch: gabor
  - gabor.html
- Nagy János Péter
  - branch: janos
  - janos.html
- Nagy Zoltán Albert
  - branch: gabor
  - zoltan.html
- Orsós Ákos
  - branch: akos
  - akos.html
- Szakács Elek
  - branch: elek
  - elek.html
- Thoma Krisztián József
  - branch: krisztian
  - krisztian.html
- Tóth Lajos Szabolcs
  - branch: lajos
  - lajos.html
- Urbán Tibor
  - branch: tibor
  - tibor.html
