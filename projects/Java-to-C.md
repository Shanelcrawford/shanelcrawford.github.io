---
layout: project
type: project
image: images/java-vs-c.jpg
title: Java to C
permalink: projects/java-to-c
# All dates must be YYYY-MM-DD format!
date: 2021-01-17
labels:
  - C
summary: For my ICS 212 class we were required to convert Java into C for the basics of learning the C language.
---


Java to C is a mini project to take java code which was provided and converting it into the C language. 

This is done to start learning the C language and to adjust from the java language to the C language.

Below is a sample of the code which was written from java to c:

```c

int main(int argc, char* argv[])
{
    int num;
    int i;
    for (i = 0; i < 6; i = i + 1) 
    {
        if (i < 2) 
            printf("Hello\n");
        else if (i < 4)
            printf("World\n");
        else
            printf("!!!\n");
    }
    
    num = 0;
    while (num < 3) 
    {
        printf("While loop!\n");
        num = num + 1;
    }

    num = 0;
    do 
    { 
        printf("Do-while loop!\n");
        num = num + 1;
    } while (num < 3);
    return 0;
    
}




```

You can learn more at the [UH ICS 212 Website](http://www2.hawaii.edu/~tidota/212s21/hw/hw1/hw1.html).



