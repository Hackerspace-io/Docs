# Initiat a Schematic Project

## create following folder and files:
* Borad
  * [project_name].PrjPcb
  * [project_name]_PCB.PcbDoc
  * [project_name]_SCH.SchDoc
* Docs
* README.md 

the `Docs` folder includes datasheets and other documentations.

## sync the project with github
every project defined in the following repository:
https://github.com/hamidrexa/[project_name].git
using git bash (in [windows](https://desktop.github.com/)) or bash (in [linux](https://www.liquidweb.com/kb/install-git-ubuntu-16-04-lts/))
```
1. git clone https://gitlab.com/hamidrexa/[project_name].git
2. git remote add origin https://gitlab.com/hamidrexa/[project_name].git
3. git remote -v
4. git fetch origin
5. git pull origin master --allow-unrelated-histories
6. git push origin master
```
check the current status in any step using `git status`






