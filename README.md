# Git_Command

## Список корисних команд для роботи з git

1. git init - ініціалізує папку як локальне сховище для роботи з GIT. (До нього буде додано прихований підкаталог .git.)
2. git clone - копіює репозиторій(папку з файлами) на компютер
3. git branch "branchName" - створює гілку з назвою "branchName"
4. git checkout "branchName" - переходить на гілку з назвою "branchName"
5. git checkout -b "branchName" - створюємо гілку з назвою "branchName" і переходимо на неї
6. git add . - зберігаємо зміни в файлах
7. git commit -m "commit message" - підписуємо збереженні зміни в файлах
8. git push - відправляємо зміни на сайт github
9. git pull - отримуємо останні зміни з сайту github
10. git status - показуємо статус проекту
11. git branch - показуємо список гілок в проекті
12. git branch -r - показуємо список гілок на сайті github
13. git branch -a - показуємо список гілок на компютері та на сайті github
14. git fetch - отримуємо зміни з сайту github
15. git stash - зберігаємо не збережені зміни в файлах і кладемо їх в буфер обміну
16. git stash apply - вставляємо збережені зміни з буфера обміну
17. git merge "banchName" - зливаємо гілку з назвою "branchName" в поточну гілку
18. git merge --abort - відміняємо зливання гілок
19. git branch -d branchName - видаляє гілку локально з проекту
20. git push origin --delete name - видаляє гілку з сайту github
21. git diff - показує відрізки рядків між двома версіями файлу (між двома комітами)
22. git log - показує історію комітів
23. cd gitTutorial - переходимо в папку gitTutorial

Для того щоб вийти з режиму перегляду комітів використовуйте клавішу q (стосується команди №20 і №21)

GIT CONFLICT

Accept Current Change - Прийняти поточні зміни
Accept Incoming Change - Прийняти вхідні зміни
Accept Both Changes - Прийняти обидві зміни
Compare Changes - Порівняти зміни
