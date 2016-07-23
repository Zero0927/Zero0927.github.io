---
layout: post
title: Structures Arrays FileI/O
fullview: true
categories: [C]
tags: [C, Individual project,file I/O]
---
Write a program that reads in one file and writes to two output files.

The input file contains a list of items purchased by the customers of a store.   
Each line looks like this:             
Smith 5 sweater $12.50                The line contains   
- the name of the customer     
- the number of items ordered     
- the name of the item    
- the price of one item

The program read in the data in this type of input file and store it in an array of customer structures.   
Each customer structure must have the customer's name and an array of the items purchased by that customer. 
The items in the item array must be structures too.  
Each item structure must include the name of the item, how many were ordered, and the price for one item.   
It also can Add more fields to either structure (customer or item).

After storing all this data, the program create two output files, the chronological listing and the financial listing.

<a class="btn btn-default" href="https://github.com/godofhand/TCSS-333-Structure-Arrays-FileI-O">Check my code here</a>
