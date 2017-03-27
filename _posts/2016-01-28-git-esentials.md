---
layout: post
title:  "Git esentials"
subtitle: "Tips and tricks"
author: "Ganger"
avatar: "img/authors/ganger.jpg"
image: "img/git.png"
date:   2017-02-25 12:12:12
tags : [recipe,git]
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

[@Ganger85](http://twitter.com/ganger85)
