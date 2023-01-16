# verziókezelés alapjai
## 1. git letöltés
- [git for windows](https://gitforwindows.org/)
- git scm
## 2. konfigurációs parancsok
- git config --global user.name
- git config --global user.email
- git config --global credential.helper
## 3. repozitori létrehozása
- git init
## 4. állomány hozzáadása a stage-hez (staging area)
> A stage-en lévőállományokról tudunk állapotfelvételt (commit-ot) készíteni
> Üres mappa nem kerül a stage.be
- git add állomány_neve
- git add .   (összes állományés mappa hozzáadása)
## 5. állapotfelvétel (commit) készítése
- git commit -m "commit message"
## 6. állapot és log lekérdezése
- git status
- git log
## 7. lokális változtatások szinkronizálássa a távoli repba
- git push
## 8. távoli repó másolása a helyi repóba
- git clone "távoli repó url címe"
## 9. ágak (branches) kezelése
> lokális ágak listázása
- git branch
>lokális és távoli ágak listázása
- git branch -av
> ág llétrehozása
- git branch új_ág_neve
- git checkout -b új_ág_neve
> váltás másik ágra
- git checkout másik_ág_neve
> ágak törlése 
- git branch -d ág_neve
> változások átvezetése
- git checkout ahovakerulnekavaltozasok
- git merge ahonnan-athozzuk-a-valtozasokat
- 