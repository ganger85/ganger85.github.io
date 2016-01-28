---
layout: post
tags : [tutorial,git]
---
# git quick cheatsheet



### add remote repository

Esto es especialmente útil cuando trabajamos con Pull Request

Así 

- origin -> repo personal en el server de git
- upstream -> repo del proyecto sobre el que van las Pull Request
- collaborator-1-N -> cuando compartimos tareas o hay que pasar código sin ensuciar master

~~~
git remote add <name> <url>
~~~
~~~
git fetch <name>
~~~
~~~
git remote -v
~~~