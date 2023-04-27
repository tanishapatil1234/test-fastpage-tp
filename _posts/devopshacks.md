---
toc: true
layout: post
description: Hacks for DevOps 04/24.
categories: [markdown]
title: Hacks for DevOps 04/24.
---
# Hacks for DevOps 04/24.
## KASM HACKS
- Virtual desktop allows users to access a desktop environment using any device. Virtual desktops can allow teachers and students (in an APCSP environment) to access programming tools without requiring specific hardware or software installations on individual devices.
- KASM Installation Attempt: 
<img width="935" alt="image" src="https://user-images.githubusercontent.com/111611921/234737437-76128b44-1cdc-47dc-ab6f-3be3b2174fbd.png">

## AWS DATABASE HACKS
### Quiz 1
What is the main difference between relational and non-relational databases?
- Answer: C. Relational databases are based on tables and use SQL, while non-relational databases are based on collections and use JSON-like documents.
- Explanation: Relational databases store data in formats using rows and columns, such as SQL while non relational databases don't and store it in like JSON formats. 

Which AWS database service is best suited for applications that require low-latency speed?
- A. Amazon ElastiCache
- Explanation: Low latency applications process high volumes of data with minimal delay or latency. Thus ElastiCache is the most suitable option.  

What is the purpose of the code example provided in the lesson?
- C. To provide an example of how to connect to a database instance in RDS using Python.

### Quiz 2
Which of the following is not an AWS database option?
- C. SQLite
- Explanation: SQLite is not an option AWS database

Which of the following is a file-based, lightweight RDBMS?
- D. SQLite

Which AWS service enables you to store and query highly connected datasets?
- C. Amazon Neptune
- Explanation: Neputune allows to store data and query entagnled datasets. 

## DUCKDNS HACKS 
1. HACK 1: Create a diagram (Canva). What are the pros and cons of using DuckDNS? Show a diagram of an application running on AWS using a DuckDNS system.
<img width="455" alt="image" src="https://user-images.githubusercontent.com/111611921/234720237-9547031d-a846-4109-8842-94f4744a86ab.png">
2. Write a reflection. Why do we use DNS? How does DuckDNS work? What makes DuckDNS unique? How is DuckDNS useful for our projects? What are the steps to setup DuckDNS?
DNS also known as domain name system and allows for IP addresses to be user friendly. DuckDNS allows users to assign a domain name to a dynamic IP address. DuckDNS in unique because it is a free service. It is useful for projects because it provides a stable hostmane that can be used to access our devices from anywhere. 

> Steps to setup:
- create free account 
- choose hostname
- configure oruter to update IP adrdress with DuckDNS custum domain name 
- Test hostname through brower

3. HACK 4: In 2-3 complete sentences, talk about any outdated Nginx/Docker functionalities that may need to be addressed or any confusions you may have in regards to the deployment process from Trimesters 1 and 2.
Some difficulties in the deployment process I had was version compatibility issues and managing my dependencies. 

4.  HACK 5: Create a Venn Diagram comparing Nginx with Lighttpd.
<img width="610" alt="image" src="https://user-images.githubusercontent.com/111611921/234728163-3c07b5db-0be7-4b94-a3ab-48d13aaa506d.png">

5. HACK 6: Complete the Python quiz and attach your output from the notebook (should be done once you do the quiz.)
<img width="676" alt="image" src="https://user-images.githubusercontent.com/111611921/234735913-659283a5-3ee5-4465-ae19-ee6a9ec944af.png">

## CERTBOT HACKS
1. Could not get part one sudo certbot command to work
2. Research and compare the security features of OpenSSL and LibreSSL, and write about the recent vulnerabilities within it. 
OpenSSL and LibreSSL are open-source implementations of SSL/TLS protocols to secure internet communications. LibreSSL is more secure than OpenSSL, as OpenSSL has had many vulnerabilities. While LibreSSL isn't perfectly secure, as a fork of OpenSSL it may be more secure. 




