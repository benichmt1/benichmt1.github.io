---
layout: project
type: project
image: images/raffle.png
title: KingPhisher Template
permalink: projects/kingphisher
date: 2015
labels:
  - Security
  - Phishing
  - VBA
  - Powershell
summary: Created various public and internal King Phisher templates
---

KingPhisher is an open-source tool developed by members of SecureState. In order to extend the functionality of this application, I created several Excel templates that were designed to deliver a Powershell Empire payload while bypassing typical antivirus controls. One template made publicly available was a raffle ticket template, where users press a button to generate a number but a powershell payload is dropped silently in the background.

At the time of testing, email filters were flagging on the Auto_Open() functionality of a macro. By creating a button to perform the action, the payload was able to slip past the automatic testing of certain vendors.


[Blog post](https://warroom.securestate.com/bypassing-gmails-malicious-macro-signatures/)

[Reddit discussion](https://www.reddit.com/r/netsec/comments/4tkwp6/bypassing_gmails_malicious_attachment_filter_with/)

<a href="https://github.com/securestate/king-phisher-templates/tree/master/Email_Templates/Shell/Ticket_Raffle"><i class="large github icon"></i>Github</a>



