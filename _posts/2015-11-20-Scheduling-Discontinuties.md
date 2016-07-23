---
layout: post
title: Scheduling Discontinuties
fullview: true
categories: [Java]
tags: [Java, Scheduling,Individual project]
---
  In this project, I use a single FIFO queue(not a priority queue) for the ReadyQueue and several more similar queues for kernal service and I/O processes.

Print to the screen every time a process generates an event and the results of that event. 

For example:

PID: 332A MutexLock(m1) - Blocked at quantum 1765 of 3345 total

PID: 127 Printer output - Blocked at quantum 435 of 1200 total - awaiting completion

PID: 431 I/O completion interrupt keyboard input - back in ready queue at quantum 7643 of 4800 total

<a class="btn btn-default" href="https://github.com/godofhand/TCSS-422-Scheduling-Discontinuities">Check my code here</a>

