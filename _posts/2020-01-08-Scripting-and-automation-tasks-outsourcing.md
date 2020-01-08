---
layout: single
author_profile: true
author: "Gidi Marcus"
title:  "Scripting and automation tasks outsourcing"
tags: [NetApp,Pure Storage,Microsoft,PowerShell,Srctipts,Runbooks]
---

Most organizations have some repetitive tasks that the IT department or a consultant have to spent long time doing again and again, these processes sometime depend on an approval or tasks done by other team - that an expensive IT resource have to spend in time chasing ,  all that while an actual business process is pending.  And when it finally completes you might find it was done in a non-standard or consistent way. 

Automation can solve these issues. Sometime in a much lower cost then the organization spending on the manual task in a very short period. It of course improves the overall productivity and increase the individual’s satisfaction from the process being more efficient. We tried to answer some of the questions you may have regarding automation:

<h3>Can any process be (or should be) automated?</h3>
Yes, every process can be automated. But it’s important to analyse if and how to automate it, and whether if there’s an off-the-shelf product or a ready function/module that do this task more efficiently then building a custom in-house solution. 
We will be happy to work with you to analyse the exact processes that can benefit from automation, and to match it to the right automation and scripting technologies.  
<center><img src="/assets/images/Code_snippt.jpg"></center>
<h3>Can you give an example of process you’ve automated?</h3>
Sure, there’s many examples where we used existing automation technologies, but here some scripts we written from ground up, some of these publicly available online in our <a target="_blank" rel="noopener noreferrer" href="https://github.com/MGidi"> GitHub repositories </a> (Where not created for specific client or used client hours).
{::nomarkdown}
<ul>
  <li>Creation and decommission of standardised shares, and permissioned folders within a DFSn structure, on multiple platforms (Windows cluster, Windows S/A file server, NetApp cluster Mode).</li>
  <li>Automation of a few file servers migration, some consists from hundreds of shares and 10’s millions of files, over a very short downtime. </li>
  <li>Disaster recovery failover runbook for NetApp shares and DFSn. Allowing to short the manual failover process from days to minutes in a safe and consistent manner.</li>
  <li>Automate a custom ticket creation for 1st line processing when a storage or other IT equipment triggers an alert, along with mechanism to add custom instructions for known issues and to match the incident priority to the alert severity.</li>
  <li>Alerting on <a target="_blank" rel="noopener noreferrer" href="https://github.com/MGidi/PureStorage_Volume_Growth_Alerts"> abnormal growth of volumes on a storage system. </a></li>
  <li>Clean up of old computer accounts, DNS entries and DNS zones consolidation. </li>
  <li>Querying different API’s, filtering and <a target="_blank" rel="noopener noreferrer" href ="https://github.com/MGidi/UKPropertySearchesUsingAPIs"> reporting on UK properties for sale.<a></li>
    <li>Simple on-demand reports – Consolidated storage and compute capacity, AD group membership, Leftover files in datastores, breach of storage vendor best practice on servers and many more.</li>
    <li><a target="_blank" rel="noopener noreferrer" href="https://github.com/MGidi/NetAppCdotBestPracticeReportForNAS"> Standard alignment reports </a> – Following implementation of new solution, a report created to enforce and alert of breach of each one of the 17 standards written in the solution manual.</li>
</ul>
{:/}
And many more…

<h3>What tools do you use?</h3>
We believe in finding the right tool for the task, while trying to utilize existing assts and technologies the organization already have. The tools we mainly used so far are PowerShell, VBS, AutoIT, Microsoft SC Orchestrator, NetApp WorkFlow Automation (WFA), VisualCron,  Microsoft DSC, Windows GPO and more… 
