# Week-9-Honeypot

# Project 9 - Honeypot

Time spent: **7** hours spent in total

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
  * In addition to this, both my Shockpot and ElasticHoney honeypot's showed as having had 0 attacks, despite me Nmapping both of their      IPs.

Question #3: **A summary of the data collected: number of attacks, number of malware samples, etc.**
  * At the time of writing, 3,

Question #4: **Any unresolved questions raised by the data collected**
  * Is the internet really this dangerous? It didn't take long at all for my honeypot's to be "attacked".
