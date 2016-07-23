---
layout: post
title: Private Heap
fullview: true
categories: [C]
tags: [C, Individual project,heap]
---
 Initially the private heap contains a single free block that has the same size as the call to create_pool.
 
  this initial block will somtimes be split into smaller pieces and these pieces must later be recombined whenever possible. 
  At any given time, some of the blocks will be in use because malloc has given them to a caller, or they will be free,
  meaning they are (back) in the private heap.
  
Build a single linked list to keep track of all the blocks, whether they are free or not.   
Each node will keep track of a storage block taken from the private heap.  
For each block, track     
- where it starts  (a memory address)            
- how big it is (a number of bytes)              
- whether it is free or not

<a class="btn btn-default" href="https://github.com/godofhand/TCSS-333-Private-Heap">Check my code here</a>
