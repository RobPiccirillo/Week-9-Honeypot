# Week-9-Honeypot

# Project 9 - Honeypot

Time spent: **8** hours spent in total

> Objective: Setup a honeypot and intercept some attempted attacks in the wild.

Overview
In this assignment, you will stand up a basic honeypot and demonstrate its effectiveness at detecting and/or collecting data about an attack. Guided instructions for doing this using specific software are provided below, but you are free to take any approach you wish that demonstrates the following basic principles:

Successful configuration and deployment of a network-accessible honeypot server with two primary features:
An attack surface that is vulnerable or exposed in some way to network-based attacks
A network security feature such as an IDS configured to detect and log such attacks
Illustration of at least one attack against the honeypot that can be detected or logged in a way that captures information about the attack or the attacker


<img
src='https://github.com/RobPiccirillo/Week-9-Honeypot/blob/master/honeypotAttacks.gif'
title='Video Walkthrough' width='' alt='Video Walkthrough' />


Question #1: **Which Honeypot(s) you deployed**
  
  * Honeypot #1: Dionaea with HTTPS
  
  * Honeypot #2: Snort
  
  * Honeypot #3: Shockpot
  
  * Honeypot #4: ElasticHoney

Question #2: **Any issues you encountered**
  * Setup was extremely long. Took a majority of the time, to be honest. 
  * In addition to this, both my Shockpot and ElasticHoney honeypot's showed as having had 0 attacks, despite me Nmapping both of their      IPs and it showing as having been successful.

Question #3: **A summary of the data collected: number of attacks, number of malware samples, etc.**
 At the time of writing, there have been 3,806 attacks in the past twenty-four hours:
  * Dionaea - 3,709 
  * Snort - 97 
  * Shockpot - 0  
  * ElasticHoney - 0
  
 Top three attacked ports were:
  * Port 3389 (97 times)
  * Port 5060 (51 times)
  * Port 23 (37 times)
  
  Top three attacker IPs were:
  * 147.4.36.73 (3,186 attacks)
  * 191.101.167.37 (52 attacks)
  * 46.17.98.45 (40 attacks)
  
  Top three attacks signatures:
  * ET DROP Dshield Block Listed Source group 1 (28 times)
  * ET CINS Active Threat Intelligence Poor Reputation IP TCP group 3 (14 times)
  * ET CINS Active Threat Intelligence Poor Reputation IP TCP group 4 (7 times)

Question #4: **Any unresolved questions raised by the data collected**
  * Is the internet really this dangerous? It didn't take long at all for my honeypot's to be "attacked".
