# Entry 4
##### 4/25/22

## Review / Sources
As of this week, I have completed my project within terms of planning. I understand the tool to a sufficient extent. As for practice, I have been following videos, specifically <a href="https://www.youtube.com/watch?v=Pgfbl_o9WvM">tutorials</a> for what the limits and uses of the tool are.  

The tool I am using is <a href="https://developers.google.com/apps-script">Google App Script</a>, which makes use of Google apps such as Docs, Drive, and Gmail and uses a modern JS platform to edit and automate such apps by the user. It does this by connecting to the users' Google account and helps do certain actions in place of the user. There were plentiful of <a href="https://www.youtube.com/watch?v=Nd3DV_heK2Q">YouTube tutorials</a> on the basics functions of the Google App Script. Using these, I have made mini-projects or small tasks to practice.

## Engineering Design Process (EDP)
The Engineering Design Process (EDP) is a <b>7-step process of planning, designing, creating, testing, and then improving on</b>. In a sense, the process doesn't end as there are always ways to improve upon your design. I'm currently at stage 4, planning on an accessible solution for myself and others to use to keep control and organize their Gmail apps.

To begin I have to recognize the problem, hard to maintain Gmail inboxes. First I have to understand why inboxes remain hard to manage, after some <a href="https://hbr.org/2012/02/stop-email-overload-1">research</a> to observe what other companies are doing or saying to combat inbox overload. The common trend is for people to try and go through or organize new emails early in the morning or set time aside to do this. As well as organizing emails in categories to make sorting through your inbox easier. Programs such as <a href="https://mailstrom.co/MailStorm">MailStrom</a> does this, categorizing or groups emails and identifies bundles of related mail, and make it easy for you to act on them as a group. Understanding this is important because you want to clear emails in mass to prevent overflow.
At the same time, I also don't want to fully automate the cleanup as I want the user to feel in full command of what gets purged and prevent any unintentional loss of important emails. The most important part is creating a program that allows the user to regain control over their inbox. The most important part to me is that the user maintains control over their inbox still. Essentially all I want is for automation for the inbox. 

 

## Knowledge

The Tool I'm using is <b><a href="https://developers.google.com/apps-script">Google App Scripts</a></b> which a free extension for Google apps that anyone can use to automate apps such as Gmail, Docs, and Sheets. This is done by allowing access and linking them to the popular language JavsScript on a cloud-based platform.

My project is based on organization, though the idea not unique, is very useful. I've noticed that many established programs that follow a similar concept are over-complicated, don't stick to what most people are looking for, and most importantly are costly for a purchase that may or may not work in the way the buyer intends.

Part of the learning process is messing around with the language, reading up on what you can do, and watching many videos on what to start on to grasp a solid understanding. A great addition to the learning of the tool is that there are plenty of sources to pull from.  Here is some code I used to try out different things and make use of the different google apps. Gauging an understanding of how to manipulate the apps. 


//function DocumentApp() 


The important part of this code snippet is the "DocumentApp", essentially what it is doing is selecting the document app, google docs. To which I make a function after I can add what I need to add to tell the system what to do after selecting the document app whether it should be adding or writing. 

//var doc = DocumentApp.openById('ID')
 
This helps the system understand what doc is being selected. One important note about google is that it is pretty organized so everything has some form of ID to help the system know what it is choosing. 

//logger.log(doc.getBody().appendParagraph('text'))

This goes in the body of the document and goes to the end of the paragraph, ".appendParagraph" and depending on what you put adds that. This is just a small code to gain an understanding of how to access and go through the Google apps. 

//function SlideApp() 
//var slide = SlideApp.openById('ID') or you can use 
//var slide = SlideApp.openByUrl('URL')

 ## Skills

Skills that I have to use is <b>time management</b> and <b>analysis.</b>

Using the skill of time management as I have a lot to do outside of my code class, such as the real estate program, Scholars program, and other things. Developing that time management skill helps me balance all these things. Keeping myself healthy both mentally and physically. Developing my skills in analysis helps me take in information effectively. Seeing the bigger picture or in this case, the end product helps me understand the steps needed to reach the end product. Combining these two skills promotes efficiency and effectiveness.

[Previous](entry03.md) | [Next](entry05.md)

[Home](../README.md)
