# Initiat a Schematic Project

## project configuration
create following folder and files:
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

* initiate the project using [desktop github](https://desktop.github.com):
  1. from `file` select `Clone Repository`
  2. select the `test_version` branch
  3. from `Repository` select `Pull`

* initiate the project using git bash (in [windows](https://git-scm.com/downloads)) or bash (in [linux](https://www.liquidweb.com/kb/install-git-ubuntu-16-04-lts/)):
```
 1. git clone https://gitlab.com/hamidrexa/[project_name].git
 2. git remote add origin https://gitlab.com/hamidrexa/[project_name].git
 3. git remote -v
 4. git fetch origin
 5. git pull origin master --allow-unrelated-histories
 6. git checkout test_version
 7. git push test_version test_version
```
check the current status in any step using `git status`






