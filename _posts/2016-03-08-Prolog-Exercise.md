---
layout: post
title: Prolog Exercise
fullview: true
categories: [Prolog]
tags: [Prolog, Exercise]
---
First exercise for Prolog and logical programming language.

Write a predicate second(X,List) which checks whether X is the second element of List .

Write a predicate swap12(List1,List2) which checks whether List1 is identical to List2 , except that the first two elements are exchanged.

Suppose we are given a knowledge base with the following facts:

   tran(eins,one). 
   tran(zwei,two). 
   tran(drei,three). 
   tran(vier,four). 
   tran(fuenf,five). 
   tran(sechs,six). 
   tran(sieben,seven). 
   tran(acht,eight). 
   tran(neun,nine).
Write a predicate listtran(G,E) which translates a list of German number words to the corresponding list of English number words. 

Write a rule 
solve(X, Y, P, N) :- ... 
that will find a path P (all visited intersections as a list) of length N (if one exists) from intersection X to intersection Y. 
The intent is that the user will invoke solve as a query, specifying X and Y as constants and P and N as variables. 
Note that passageways are bi-directional; Avoid any cycles.

<a class="btn btn-default" href="https://github.com/godofhand/Prolog_exercise">Check my code here</a>
