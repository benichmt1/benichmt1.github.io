---
layout: project
type: project
image: images/empirelogo.png
title: Powershell Empire
permalink: projects/empire
date: 2015
labels:
  - Python
  - Powershell
summary: Various contributions to the PsEmpire project, an offensive Powershell framework.
---

## MS16-032
<img class="ui medium right floated rounded image" src="../images/ms16.png">

MS16-032 is a Windows privilege escalation exploit that I adapted to work with Powershell Empire. Although I did not create the proof of concept or the official module, I modified the concept in such a way that it could be loaded as an external source from the framework.

[Blog post](https://warroom.securestate.com/leveraging-ms16-032-powershell-empire/)

[Reddit discussion](https://www.reddit.com/r/netsec/comments/4rique/leveraging_ms16032_with_powershell_empire/)

<a href="https://gist.github.com/benichmt1/af52401c7f2d6984dea6ba60b44aa1aa#file-ms16-032-ps1"><i class="large github icon"></i>Github</a>
 
## WLRMDR Licensing Balloon Module

<img class="ui medium right floated rounded image" src="../images/wlrmdr.png">
Created a module for Empire that can be used for social engineering attempts. This module utilizes the Windows logon reminder service to launch a customized balloon reminder in a user's taskbar.

<a href="https://github.com/EmpireProject/Empire/pull/447"><i class="large github icon"></i>Github</a>

## Get_Subnet_Ranges Module

<img class="ui medium right floated rounded image" src="../images/Screenshot from 2018-05-07 09-03-57.png">
Added recon module for discovering subnets based on AD information. The script pulls domain computers, resolves their DNS, determines if they are reachable, and then categorizes them into subnets.

<a href="https://github.com/EmpireProject/Empire/pull/1103"><i class="large github icon"></i>Github</a>
