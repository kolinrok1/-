﻿# GIT #

## тут ты найдешь все, что нужно знать ##

>Git — это набор консольных утилит, которые отслеживают и фиксируют изменения в файлах. Изначально Git был создан Линусом Торвальдсом при разработке ядра Linux. Однако инструмент так понравился разработчикам, что в последствии, он получил широкое распространение и его стали использовать в других проектах. С его помощью вы можете сравнивать, анализировать, редактировать, сливать изменения и возвращаться назад к последнему сохранению. Этот процесс называется контролем версий.

>Git является распределенным, то есть не зависит от одного центрального сервера, на котором хранятся файлы. Вместо этого он работает полностью локально, сохраняя данные в директориях на жестком диске, которые называются репозиторием. Тем не менее, вы можете хранить копию репозитория онлайн, это сильно облегчает работу над одним проектом для нескольких людей. Для этого используются сайты вроде github и bitbucket.


## Команды: ##
1.   **git init** - создать репозиторий 
2.   **git add** - добовляетя файл для отслеживаниея
3.  **git commit** - создание контрольной точки  
* **-m** - добавить сообщение 
* **-a** - все файлы в директории
4. **git status** - проверить статус файлов
>Нужно придумать что написать ))

>И что-то еще написать))
5. **git log** - просмотр версий  
6. **git diff** - посмотреть изменения 
7. **git checkout** - переход между версиями или ветками
> Git checkout позволяет нам переключаться как между удаленными, так и меду локальными ветками. Это один из способов получить доступ к работе коллеги или соавтора, обеспечивающий более высокую продуктивность совместной работы. Однако тут надо помнить, что пока вы не закомитили изменения, вы не сможете переключиться на другую ветку. В такой ситуации нужно либо сделать коммит, либо отложить его, при помощи команды git stash, добавляющей текущие незакоммиченные изменения в стек изменений и сбрасывающей рабочую копию до HEAD'а репозитория.

7. **git checkout** - переход между версиями
8. **git branch** - вывод списка веток
7. **git merge** - слияние веток

## Слияние веток с ошибкой