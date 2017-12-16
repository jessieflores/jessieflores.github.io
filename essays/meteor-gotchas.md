---
layout: essay
type: essay
title: "Meteor Gotchas"
date: 2017-10-19
labels:
  - Software Engineering
  - Meteor
---


A problem that I had encountered when I was first running meteor to do the assignment digits was the extremely long 'meteor npm run start' in the command line. I am using windows for meteor so in comparison to the past modules of the class, I did not expect to have much support since almost everything that MAC users had ran exceptionally faster. But yes, running the command shown at the top would yield extremely long extraction times so naturally I wondered If I was doing something wrong. 

<img class="ui medium image" src="../images/windows-vs-mac.jpg">

After a thorough google search, I had found many other users report this problem and one solution that did work for me was disabling the anti-malware systems on your computer. I had read that because of the many files meteor extracts, your anti-virus goes through a plethora of them thus yielding slow run times. I had also read that if you run the processes app on your windows during running your meteor app, you can actually see that the anti-virus takes up the majority of the processes.

<img class="ui medium image" src="../images/scanning.jpg">

As far as problems with functionality or finding problems with meteor that deter assignments, I have not found anything other than the problem I talked about above. There are still some run time issues but are negligible as they only take up less than 5 minutes. For example, when you first instialize a meteor app, it takes a decent amount of time and also when you are making it for the first time on IntelliJ, it takes a decent amount of time to index the files. 

