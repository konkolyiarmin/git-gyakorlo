# verziókezelés alapjai
## 1. git letöltés
- [git for windows](https://gitforwindows.org/)
- [git scm]
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
- 