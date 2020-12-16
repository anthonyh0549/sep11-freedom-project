# Entry 2
11/28/20 X/X/XX

This is my second entry and I will be going over the concept up to now. I wanted to create a product that can help clean my inbox and organize everything. The main issue is that my inbox gets a lot of mail and going over it to know what to rid of can be a tedious and time consuming process. So I decided on my project to create a program that cleans the inbox for you depending if the reqirements are met for mail to be deleted. After some looking into Google App Script I found out that much of everything is already there since it's linked to many of the other google services. Such as the code that I mentioned in my last post already has functions for looking into my email and setting conditions for a email to be deleted. 

// Find starred messages with subject IMPORTANT var threads = GmailApp.search('is:starred subject:"IMPORTANT"');

Another peiece of code I plan to intergrate works to move messages to the trash and than force a refresh. This is key in getting rid of the messages themseleves part. 

// Move first two messages in your inbox to trash
var firstThread = GmailApp.getInboxThreads(0,1)[0];
var messages = firstThread.getMessages();
var toDelete = [messages[0], messages[1]];
GmailApp.moveMessagesToTrash(toDelete);


[Previous](entry01.md) | [Next](entry03.md)

[Home](../README.md)
