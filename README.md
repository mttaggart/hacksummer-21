# HackSummer 21 Curriculum

## Overview

Welcome to the second year of #HackSummer! Just like the first iteration, the objective of HackSummer is provide free, interactive technology training for all curious minds. In 2020, we focused on the Python programming language. This year, we'll be putting on our sysadmin hats and diving into the Linux operating system. That might sound boring, but Linux is a powerful tool. Once mastered, it can become anything you want it to be. A hacker's weapon of choice? Sure. The basis of the next killer app? Absolutely. Even...

The brain of a helicopter on Mars.

To master Linux is to understand fundamental concepts about how computers and networks operate. Investing the time in learning how to set it up and manage it sets you miles ahead of the average technologist.

## Course Prerequisites

Having used a computer before will be helpful, but there are no formal prerequisites for this course. 

## Materials

### Required

1. A hunger for learning!
2. A reasonably modern computer. Doesn't have to be a beast, but at least 8 GB of RAM.
3. An internet connection.
4. [VirtualBox](https://www.virtualbox.org/)
5. Time to commit to viewing the lectures and attempting the challenges 

## Learning Objectives

### Understandings

By the end of this course, you will understand:

* What Linux is
* How Unix-like operating systems differ from other OSes
* Linux file representations
* Linux file permissions
* Basic networking
* Shell scripting
* Client/server architecture
* Linux security concepts

### Skills

By the end of this course, you will be able to:

* Navigate the Linux filesystem
* Use built-in commands to manipulate Linux via the command line
* Install and configure new services
* Connect to other remote systems to perform administrative tasks
* Write scripts to automate tasks
* Secure systems against common vulnerabilities

## Course Structure:

HackSummer 21 is arranged like a fairly traditional course, except streamed over Twitch and YouTube. Each day, we'll begin by reviewing the challenges from the previous lesson, going over any questions asked either in live chat or the Discord. Then, we'll cover new material with examples and demonstrations to prepare you for the next set of challenges.

## Challenge VM

The Challenge VM is aligned with the material covered during the streams. The VM has several users, each with a separate password. Completing the quiz/challenge for each user unlocks the password for the next. 

The virtual appliance is configured to forward port 9000 from your host computer to 22 on the VM, allowing you to use SSH to access each user account in turn. Once the Challenge VM is downloaded and set up in Virtualbox, simply run this command to get started:

`ssh cmd01@localhost -p 9000`

The password for this user is `HS21{lets_begin}`

### Quizzes

Quizzes are simple knowledge checks to make sure you're absorbing the material. They often have simple answers or only require single commands to be run. A 100% on the quiz will unlock the next user password. Wrong answers will generate feedback to help answer the questions. Don't hesitate to ask for help on the Discord! We won't give answers, but there will always be help available.

### Challenges

Challenges involve practical applications of the knowledge covered during the streams. The objective will be to change the state of the VM in some way, whether modifying a config file, installing a package, or some combination of operations to achieve the objective. The challenge user will have a `test` executable in the user home directory that will check for expected state. If the state fails, feedback will be provided to help progress. If the tests pass, the next user password will be provided.
