---
layout: post
title: "Reaction Time Python Project"
date: 2025-01-20
categories: [Python, Development]
tags: [Jekyll, Chirpy, Blogging, coding]
---
---

## The code
from random import *
from time import* 

print("Welcome to reaction time test, press R in the module to know your reaction time. Press r and then space after you see go in the module. ")

ready = input("Ready?")
if ready == "yes":
    start_timer = time()
    tester=input("Go (ENTER R) \n")
elif ready == "no":
    print("Ok")
else:
    print("Restart the code")
    
if tester == "r":
    end_timer = time()
    elapsed = end_timer - start_timer
    if elapsed > 4 :
        print("Too slow")
        print(elapsed)
        print("seconds")
    else :
        print("You are fast")
        print(elapsed)
        print("seconds")
else :
    print("Type r next time")




---
