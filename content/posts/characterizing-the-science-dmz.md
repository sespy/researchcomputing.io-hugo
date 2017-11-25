---
title: "Characterizing the Science DMZ"
description: ""
tags: [ "science", "strategy", "architecture" ]
lastmod: "2017-09-16"
date: "2017-01-01"
categories:
  - "Strategy"
  - "Architecture"
slug: "characterizing-the-science-dmz"
draft: false
---



## What is it ?

A "Science DMZ" is an on-premises network segment designed for high-throughput resarch activitiies to the exclusion of enterpise computing activities. It is structured to be secure, but without the permformance limits of a firewall, traffic shapers, and other middle-boxes.

It's a neighborhood where systems lean towards agility and experimentation, where there is less concern of disrupting the more sensitive "business" neighborhoods.

It represents a codification of best practices of the scientific networking and systems community.



>### Sidebar... What is a DMZ?

> A DMZ is a place in a network that is kept safe from others (or vice-versa). 
> The most common form is a "public" DMZ, which is an area of a network accesble 
> by the public, from which a more private network is kept protected. Imagine a 
> public web server in a public DMZ, but that server, while in the data ceterr, 
> is kept isolated from the data center nodes.

> A DMZ is defined by what traffic is allowed from one location to another.

> The "www" server for cnn.com may be located in the data center, and allows 
> incoming network http traffic from anyone to the host, and can resond with 
> datagrams to the world. But it is undoubtedly separated from the network 
> infrastructure where cnn's payroll application is hosted.



### Not very exciting. Why is this a thing?

There are decades of best practices that have been developed, discarded, and recreated that have led to the current state of enterprise, business computing. It makes little sense to argue that these principles be set aside to enable research computing.

Instead, 



>From [Fasterdata] (https://fasterdata.es.net/science-dmz/):

>A Science DMZ integrates four key concepts into a unified whole that together 
>serve as a foundation for this model.  These include:

>* A network architecture explicitly designed for high-performance applications, where the science network is distinct from the general-purpose network
>* The use of dedicated systems for data transfer
>* Performance measurement and network testing systems that are regularly used to characterize the network and are available for troubleshooting
>* Security policies and enforcement mechanisms that are tailored for high performance science environments







### The Case for a Science DMZ

Who wants it, and why

What are the benefits, characteristics
if it is so great why doesnt everone have one

One capability that is optionally enbaled: fast point-to-point data transfers
hndles hi voleme data trasnfers


It is the solution to this problem/



firewall protects intental enterpise network from external internet. FW maintains request stated and analyssys trafffic content.at transport and applicaiton laers

DTN data transfer node. asperta or  grisFtp

Sdmz is a dmz model where hpc is moved to its own dmz. traffic allowed to and from whitelist desst and soruce.

supports big data if transfers are needed on internet



### A Use Case, take 1

Use case: A biostatistician (ben) has composed a few steps of an analysis pipeline he would like to use. The expected perl modules in CPAN are dependencies, but good info-sec guindance prevents nodes in the data center forom downlaoading and runnning arpiraty code.

### A Use Case, take 2

Use case: While downloading a pair of bams totalling a 1/4 TB takes 3x longer than if Emily did it at home. But at home you dont have a big, managed firewall. 

### A Use Case, take 3

Use case: the operations managerOscar is a little hesitent to give previleges to parm sci post-doc Phil who wants to install some fun stuff to experiment with.


### The common thread


In each case there are two conflicting insticnts/logic sets but both are correct, and they are unreconciable. The failure to reconciel them stifles innovation in a a nontrivvial way.



### How do you make one?

what are the enabling technologes and prerequised?



### Why not?
Are there good reasons not to?
What are the obstaceles?




### Do folks really do this? Who has this? 



such that the equipment, configuration, and security policies are optimized for high-performance scientific applications rather than for general-purpose business systems or “enterprise” computing. 



* Everything is "external"; google approach to that notion
* Self-service VMs: Do you need them if you have all the CaaS you can eat?
* role of software defined newtorks in the SD?


















