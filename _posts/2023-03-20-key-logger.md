---
layout: post
title: Keylogger Script with Email Support
subtitle: The Data Transfer Problem
thumbnail-img: /assets/img/keylogger.jpg
tags: [Projects]
---

Back in 2018 I began exploring the world of Computer Science through the field of Cybersecurity. My interest eventually compelled me to learn my first programming language, Python, and with it I decided to develop a key logger program. The basic workflow of this tool is as follows: an attacker physically places the key logger script onto a victims computer, the script records all "keystrokes" that the victim types and then sends that recorded data to the attacker. The problem that I encountered in the implementation of my program was that it had no mechanism for delivering the data to another device on a another network. The implication here is that an attacker would have to revisit the infected computer in order to retrieve the information from the victim's system, or be on the same network as the victim's computer. My solution to this obstacle was to implement an email framework within the script. I used the SMTP services provided in the [SMTP Python Library](https://docs.python.org/3/library/smtpd.html) to add email functions to the program. For more information on the program visit the [source code](https://github.com/DaltonBaum/Key-logger-with-Email-Capabilities.git).
