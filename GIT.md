# GIT käsud

| Käsk | Kirjeldus |
| --- | --- |
| --- | **REPO LOOMINE** |
| ``git init`` | Uue lokaalse repo loomine. |
| ``git clone [REPO_URL]`` | Klooni olemasolev repo. |
| --- | **Lokaalsed muudatused** |
| ``git status`` | Repo oleku kuvamine. |
| ``git diff`` | Näita viimaseid muudatusi failides. |
| ``git add [File-Name]`` | Lisa reposse antud fail *[File-Name]* |
| ``git add .`` | Lisa reposse kõik muudetud failid. |
| ``git commit -m "Kirjeldus"`` | Salvesta lisatud failid reposse versioonina. |
| ``git commit --amend`` | Lisa viimati lisatud failid viimasele versioonile, koos sõnumi muutmisega. |
| ``git commit --amend --no-edit`` | Lisa viimati lisatud failid viimasele versioonile, jättes viimase sõnumi muutmata. |
| --- | **Versioonide ajalugu** |
| ``git log`` | Näita repos olevat versioonide ajalugu. |
| ``git log -p [File-Name]`` | Näita repos olevat versioonide ajalugu antud failile. |
| ``git blame [File-Name]`` | Näita kes on antud failile teinud muudatusi ja milliseid. |
| --- | **Haru ja tag** |
| ``git branch -av`` | Näita kõiki olemasolevaid harusid repos. |
| ``git checkout [BRANCH-NAME]`` | Aktiveeri antud repo haru. |
| ``git branch [NEW BRANCH-NAME]`` | Loo reposse uus haru. |
| ``git branch -d [BRANCH-NAME]`` | Kustuta haru repost. |
| ``git tag [TAG-NAME]`` | Lisa versioonile nö nimetus ehk tag. |
| --- | **Kaugserver** |
| ``git remote -v`` | Näita kõiki repo kaugühendusi. |
| ``git remote show [REMOTE-NAME]`` | Näita antud kaugühenduse infot. |
| ``git remote add [REMOTE-NAME] [REMOTE-URL]`` | Lisa uus kaugühendus antud nimega (Esimene on vaikimisi *origin*). |
| ``git fetch [REMOTE-NAME]`` | Tõmba alla kõik kaugserveri muudatused kuid ära salvesta neid lokaalsesse versiooni. |
| ``git pull [REMOTE-NAME] [BRANCH-NAME]`` | Tõmba alla kõik kaugserveri muudatused ja seo need lokaalsesse versiooni. |
| ``git push [REMOTE-NAME] [BRANCH-NAME]`` | Saada lokaalsed versioonid kaugserverisse. |
| ``git branch -dr [REMOTE-NAME/BRANCH-NAME]`` | Kustuta haru kaugserverist. |
| ``git push [REMOTE-NAME] --tags`` | Saada kõik versioonide tagid/nimed kaugserverisse. |


# Lingid
[Git Cheat Sheet](https://www.git-tower.com/blog/git-cheat-sheet/)
