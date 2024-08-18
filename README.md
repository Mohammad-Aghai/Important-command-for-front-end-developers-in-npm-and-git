#npm commands
1. cd address => thats meen change directory
2. cd ../ => one step up 
3. mkdir folderName => create a folder in address
4. clear => clear the terminal  area
5. rmdir folderName => remove a file or folder 
6. ls => shows the list of file and folders
7. npm init => inistall package.json with all questions 
8. npm init --yes or npm init -y install all package without questions
9. npm i packageName => for install package like : npm i bootstrap
10.npm uninstall packageName => for delete a package from project 
11. npm i or npm install => installing all package in package.json and made node-modules folder
12. npm i packageName@version => with this command we can install old version of package for
example : npm install bootstrap@4.3.3  the patch in this case referce to the top one
version mean => (Majore) . (minor) . (patch or bug fix)
13. npm i bootstrap --save-dev => this install the package dvelopment dependebce mode
14. npm i packageName -g => install package global and access to it everyware
15. npm i packageName packageName => install several package in one try
16. npm list => showing all dependensies with thire dependencies
17. npm list --depth 0 => showing just the project owen dependencies
18. npm config set init-author-name "yourName" => config allways author name "yourName"
19. npm config set init-licanse "MIT" => config allways licanse "MIT"
20. npm get init-licanse => get the licanse name for knowing it
21. npm run test => with this command we can accsess in see the scripts
22. npm run-script test => like prev command 
23. node index.js => we can run in nodejs the files and see the logs in terminal with this command 
24. tsc app.js => translate the typescript file to javascript in other file just like app.js file
25.simpel before version  meaning 
^4.6.1 =>  ^ last version 4.9.9 maens package can update both patch and menore not major
~4.6.1 => last version 4.6.9 measn the package just update patch 
*4.6.1 => update package in last version and update every part of versions
26. npx consay "text" => some package thire can be run without installing this happend with npx
27. npm audit => find all apckage with vulnerabilities آسيب پذيري 
28. nom audit fix => if your packages had vulnerabilites this command mabe can fix it 
---------------________--------------
npm install epress --save
npm i express --save
npm install express
npm i express
****************
npm install jest --save-dev
npm i jest --save-dev
npm install jest -D
npm i jest -D
****************
npm uninstall nodemon
npm un noddemon 
npm remove nodemon
npm rm nodemon
****************
npm i react-icons --global
npm i react-icons -g
npm rm raect-icons -g


#git commands
1. cd projecat addresses
2. git init
3. git add .
4. git commit -m "commit name"
6. short commit and add = git commit -am "commit name"
7. ignore the file with a fille .ignore and confrime the files we want to ignore them
8. create branch =  git branch nameOfbranch
8. change the branch name => git branch -m newName
9. switch in branch =  git switch branchname
10. create and switch branch shortcut = git switch -c branchname
11. git log 
12. git log --oneline
13. git log --all
14. git log --graph
15. git log --all --oneline --graph 
16. git diff
17. git diff brnachname..branchname or commitHash..commitHash
18. git --version
19. git status
20. git rm --catch
21. git marege branchname
22.git diff --staged
23.git diff --HEAD
24. git checkout commitName 
25. fore get back to the master  after checkout => git switch yourHeadName
26. git checkout HEAD
27. tow step before HEAD => git cheackout HEAD~2 
28. get back to the HEAD those thire commited => git checkout HEAD yourFilename
29. get back to the HEAD those thire commited => git restore yourFilename
30. git restore --source commitHash FileName 
31. git reset commitHash
32. git reset --hard commitHash
33. git revert  commitHash  +> git add . +> git revert --continue
34. git stash save "massage"
35. git stash pop
36. git stash apply
37. git stash list
38. git stash apply stash@{id}
39. git stash drop stash@{id}
40. git stash clear
41. git rebase branchName => this is like merege branches but in this case commite creaeting time its not matter
42. git rebase 	-i --root => edite and delete commites
43. git rebase -i HEAD~5 => edite and delete commites choose the commit before editor opening
44. git tag lable => lightweight tage this is a lablae make for commit we can use it for version of our application 
45. git tag -a lable =>Annotated tags this is like this is like lightweight tags but we can leave the coomment for commit too
46  git tag > return all the tags we have
47. git tag  -f v1.0.2(most be the old version name you want to change) commit hash change the git tag to other commits
48. git tag show tagName => return tag information like tag comment 
49. git tag tagName commitHash
50. get the tag => git tag -l "v2*" => return the v2 tages 
51. detach with tags => fit checkout tagname
52. git diff fore tags => git diff firsttagname..secondTagName
53. delete tag from commit => git tag -d tagname 



GIT AND GITHUB
1. git clone {github or gitlab project url}
2. git remote add lableName  gitHubUrl
3. git remote -v
4. git push {remoteName} {branchName}
5. web site for making README file  markdown-it.github.io 
6. README Type RADME.md
7. git branch -r  => this code refers to remote branchs
9. with git switch {branchName} you can craete and use your remote branch and there is no problem
10. git push remotName branchName
12. git pull remoteName branchName
13. git fetch remoteName branchName 
14. git push --set-upstream remoteName branchName => if your branch is not exist in your git hub and you want to push the branch use -u or --set-upstream
15. pull request in git hub => then pull it 
16. git push origin tagname => push the tag in github repasitory
17. git push origin --tag => push all tages in github repasitory


___git area___
working directory => vscode Change
stage area => for changing in git
repasitory => commit and save in git all steps


