---
layout: essay
type: essay
title: Crafting the Design Patterns
# All dates must be YYYY-MM-DD format!
date: 2021-04-29
labels:
  - Design Patterns
  - Singleton
  - Observer
  - Minecraft
---

## Introduction

In the world of code there are problems that we have to solve but each of these problems come with many different ways of solving it. This term of defining that there are unique reusable ways to solve a problem is called a design pattern. We use design patterns as a way to describe a format of the many solutions to solve coding problems. But what if we could also apply this to a simple entertainment game like the sand-box adventure game known as Minecraft.

## Minecraft

<img class="ui tiny left floated image" src="../images/minecraft-logo-2.jpg" style="width:256px;height:144px;">

Design Patterns in a way can be applied to minecraft the same way it can be applied to coding. The goal of minecraft is to just survive but there are many different ways or design patterns for that goal specifically. Since minecraft is a sand-box game, it allows the player many different ways to solve the problem on how to survive similarly to code where the coder is given many different ways to solve bugs and issues that would appear in their program.

## A Singleton Spider-farm

An option that players can do in minecraft is a spider-farm which can be easily done by trapping it with blocks. Players can utilize this to intialize cobweb farming as material for the players to use. The downside to this is if not managed correctly or watched over well, the spiders can very easily attack the players back unexpectedly and could hypothetically kill them if not prepared well enough to fight them back. This is similar to a singleton where it is a global variable that can be accessed by any files but could lead to negative consequences if not watched over carefully since it can be accessed and changed very easily.

```
#include<stdio.h>
#include<string.h>
#include<stdlib.h>
#include"record.h"
extern int debugmode;
```

Above is an example of a singleton in C language where it is a external integer named debugmode that could be accessed by any file in my project1 directory. 

## Redstone Observer

In minecraft you can make all types of mechanics and machinery with the power of redstone. One of the redstone machines you can craft in minecraft is called an observer. Observers can be used to help alert and check on certain mechanics in their survival. It's quite a funny coincidence since this has the exact same functionality and name as the design pattern which is called observer. They both check whether a state change has appeared but they have a small difference. The observer in minecraft checks for changes in terms of block placement while an observer checks in terms of state of a specific variable in the code. This is similar to the code I put in C++ where the variable "lever" is currently 0 and the while loop can be seen as the "observer", checking if lever is 0. When lever is changed to 1 after the user inputs "quit" it will change lever to 1 which the observer is notified and ends the while loop.

```
while(lever == 0)
{
            if (strncmp (letters, "quit", value) == 0 || strncmp (letters, "Quit", value) == 0)
            {
                cout << "Have a nice day :)\n";
                lever = 1;
                status = 2;
            }
}
```

## The sights of design patterns

Design patterns in a way are not restricted to just video games and coding. It could be applied to other problems like what are the different ways to get dressed or how does one get from point A to point B on the map. There are many ways that problems can be solved and in a way, each problem has its own design pattern template that people branch off to come up with more innovative solutions for them. If not for design patterns in coding, then we would not have this amazing technology that we utilize today.
