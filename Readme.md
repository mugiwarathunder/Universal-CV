22 июня в знойный жаркий день мы с Мастером начали проект. Шаблон сайта About
git

# DEV Log
## v001
- PROJECT CREATED DATE 2025.06.22
- connected index.html with style.css
- added 2 main containres with flex-grow
-  


# Github CHEATSHEET
## Create new repository
git init  
git add .  
git commit -m "added 2 main containres with flex-grow"  
gh repo create  

## Load last updates and replace existing local files
git fetch origin; git reset --hard origin/master; git clean -fd  

## Select a hash from the last 10 commits
git log --oneline -n 10  

## Use the hash to get that exact version locally
git fetch origin; git checkout master; git reset --hard 1eaef8b; git clean -fdx  

## Update repository
git add .  
git commit -m "COMMENT NAME"  
git push