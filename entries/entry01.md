# Entry 1
##### 11/16/20

This is my first entry so I will explain what my idea/concept is. I want to make a program or app that automatically cleans out your inbox. So after some research into google app scripts it's clear that it can support my idea as there's code with fuctions that allow for such as actions that can retrieve all gmails under spam. 
I will most likley neeed some form of this code to retieve gmails that meet a certain requirement. 

// Find starred messages with subject IMPORTANT
var threads = GmailApp.search('is:starred subject:"IMPORTANT"');

For example the code above searches your email for anything that is starred and is under the subject "IMPORTANT" and this 'function' is assigned to the variable "threads". 
So the variable "threads" when used searches the Gmail app-GmailApp.search- for anything that is starred and under the subject of "IMPORTANT"-('is:starred subject:"IMPORTANT"');-.

[Next](entry02.md)

[Home](../README.md)
