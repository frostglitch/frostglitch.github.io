---
layout: project
type: project
image: images/piggythumb.png
title: Bank database
permalink: 
# All dates must be YYYY-MM-DD format!
date: 2020-10-10
labels:
  - C
  - Unix
  - Putty
summary: A program which prompts the user to input their data into a bank database as a project for ICS 212.
---

<img class="database image" src="../images/example.png">

This was the first project that was done for my class in ICS 212. In this project we first had to make the user interface for the user to see and prompts the user to pick the options shown on their screen. They have the option to add record, find record, print all the records, delete records, or to quit the program. I also had to make the database to hold the records that the user decides to create, find, or delete. The entire code was built using C code on unix in vim. 

The picture above is an example of the user-interface.

This project has taught me a lot of skills and assets I can use in the future. It has tested my knowledge of C programming and has taught me a lot on how to be self-directed. Coding the database showed me how linkedlists work and how to get read and write file into my code. It has greatly showed me how to manage my time wisely since this project required a lot of patience and thinking into this project. 

Down below is an example of some code used to make the bank database.

```c
void printAllRecords(struct record * start)
{
    if (start == NULL)
    {
        printf("there are no records at the moment\n");
    }
    else
    {
        while (start != NULL)
        {
            printf("accountno:%d\n", (*start).accountno);
            printf("name:%s", (*start).name);
            printf("address:%s\n\n", (*start).address);
            start = (*start).next;
        }
    }
}
```

Source code: TBA in the future
