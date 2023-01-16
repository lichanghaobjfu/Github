# How to use Github

**commit** -><br>
**repgitository** ->Project, or the folder/place where your project is kept<br>
**branch** ->

**Project on Github** <br>

        git clone

**What need to see**<br>
README.md<br>
issue<br>
LICENSE<br>

**Download a repository**<br>

        git clone 'link of code'
        git init (only used when you download the zip file)

找开源项目的一些途径<br>
https://github.com/trending/<br>
https://github.com/521xueweihan/HelloGitHub<br>
https://github.com/ruanyf/weekly<br>
https://www.zhihu.com/column/mm-fe

特殊的查找资源小技巧-常用前缀后缀<br>
* 找百科大全 awesome xxx<br>
* 找例子 xxx sample<br>
* 找空项目架子 xxx starter / xxx boilerplate<br>
* 找教程  xxx tutorial

**commit the file**

        commit -A
        commit -m"fisrt commit"

**check the edit history**

        git log --stat

**undo the change**

        git checkout filename<br>

**retract after commit**

        git reset HEAD^1

**create a new branch**

        git checkout -b branchname

**list all the branch**

        git branch

**switch to another branch**

        git checkout branchname

**delete a branch**

        git branch -D branchname

**merge branch**

        git merge branchname

**Git & Github**

        git push
        git pull
