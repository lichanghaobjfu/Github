# How to use Github

123321

**commit** -><br>
**repository** ->Project, or the folder/place where your project is kept<br>
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

# markdown
#### The quarterly results look great!

- Revenue was off the chart.
    - Profits were higher than ever.

 *Everything* is going according to **plan**.

 > a
 >
 >>b%20c<br>
 c

 [link](f%20c)

超链接Markdown语法代码：[超链接显示名](超链接地址 "超链接title")

![这是图片](3081672.jpg "picture")

[![这是图片](3081672.jpg "有链接的图片")](https://markdown.com.cn/basic-syntax/images.html)

[link](AT&amp;T)
