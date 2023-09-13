## Настройка репозитория
```
репозитории помечаются двумя инициалами:
1) S3 - сеиестр №3
2) lab1 - лабораторная №1
конечное представление названия репозитория [S3-lab1]
```
## Первый Push кода в организацию
1) переходим в расположение папки проекта и прожимаем по ней *Git Bash here*
2) git init
3) git add .
4) git commit -m "название коммита"
5) git branch имя_аккаунта_с_которого_пушат_проект
6) git checkout имя_аккаунта_с_которого_пушат_проект
7) git push origin -u имя_аккаунта_с_которого_пушат_проект
Пример:
```
git init
git add .
git commit -m "Final commit" 
git branch krovinosets
git checkout krovinosets
git push origin -u krovinosets
```
## Обновление кода своей ветки в организации
Пример:
```
git init
git add .
git commit -m "Final commit" 
git push origin -u krovinosets
```
