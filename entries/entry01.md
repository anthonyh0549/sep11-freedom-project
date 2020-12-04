# Entry 1
##### 11/16/20

This is my first entry so I will explain what my idea/concept is. I want to make a program or app that automatically cleans out your inbox. So after some research into google app scripts, it's clear that it can support my idea as there's code with functions that allow for such as actions that can retrieve all gmails under spam. I will most likely need some form of this code to retrieve emails that meet a certain requirement.

// Find starred messages with subject IMPORTANT
var threads = GmailApp.search('is:starred subject:"IMPORTANT"');

For example, the code above searches your email for anything that is starred and is under the subject "IMPORTANT" and this 'function' is assigned to the variable "threads". So the variable "threads" when used searches the Gmail app-GmailApp.search- for anything that is starred and under the subject of "IMPORTANT"-('is:starred subject:"IMPORTANT"');-.

The engineering design process states you first ask a question to identify a problem, here it is my Gmail being unorganized and I ask "How can I fix that?". Now I have to work to understand how I can utilize "Google app script" to create a way to clean my inbox. Since "Google app script" works with my account there are already establish functions I can use to do this, I plan to split my concept into 3 categories. Find what I want to be cleaned or deleted, How am I going to delete it, and when I want it deleted.

Sources

https://developers.google.com/apps-script/reference/gmail/gmail-app?hl=en#search(String)

https://developers.google.com/apps-script/overview

[Next](entry02.md)

[Home](../README.md)
