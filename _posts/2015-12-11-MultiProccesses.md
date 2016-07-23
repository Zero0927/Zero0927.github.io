---
layout: post
title: MultiProccesses
fullview: true
categories: [Java]
tags: [Java, Individual project,Multi Processes]
---
  In this project, I set up some process pairs(no more than ten). In each pair one process will be a producer and other will be a consumer. These processes are just like all the others except that they are created in pairs and have some additional functions to handle their special jobs.

For no deadlock the processes should work as follows:

Process A type                                                           Process B type

lock mutex R1 (resource 1)                                          lock mutex R1

lock mutex R2 (resource 2)                                          lock mutex R2

print to trace that both resources are used                  print to trace that both resources are used

unlock mutex R2                                                           unlock mutex R2

unlock mutex R1                                                           unlock mutex R1

proceed around the loop                                              proceed around the loop


<a class="btn btn-default" href="https://github.com/godofhand/TCSS-422-MultiProcesses">Check my code here</a>
