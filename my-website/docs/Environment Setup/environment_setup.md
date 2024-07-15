---
sidebar_position: 1
title: Environment Setup
slug: /
---

How to setup your development environment to build using the Interject API

## Interject API Server

**With Existing Bluegrass Code |
[GitHub Download](https://github.com/kipland-m/BGSCS-InterjectAPI)**

**Fresh SDK |
[GitHub Download](https://github.com/kipland-m/Interject_API)**

This GitHub repository contains everything necessary to get the Interject API server up and running. This includes a lot of controllers that I have written myself that are communicating with different softwares.

## Editor

**[Visual Studio Code Download](https://code.visualstudio.com/download)**

This is what I use for Interject development. I have a configured debugger already so it is really 
plug and play. The debugger can be immensely helpful at some points during your development. Sometimes
bugs are a nightmare even with the debugger.

## Interject Add-in

**[Interject Download](https://docs.gointerject.com/wAbout/SingleUser.html#overview)**

You will need the Interject add-in for Excel in order to build and pull your data.
Yes. This is documentation that links to documentation. Hey Siri, what's recursion?

## Git

**[Git Bash Download](https://git-scm.com/downloads)**

If you are using Windows, you will need to download git to your machine via the above link.
On Linux, this should be a default installation and accessible through the shell.


## Postman

**[Postman Download](https://www.postman.com/downloads/)**

Postman is used to test API endpoints in a nice GUI rather than using a command line tool or your browser.
Most APIs will provide a Postman 'collection' to download that has most of the endpoints you would want to access in it as well
as example queries. I will include the Intacct and Mcleod Postman collections below.

## Postman Collections

**[Intacct Postman Collection Download](https://developer.intacct.com/downloads/Intacct_API_Postman_Collection.zip)**

## Python

**[Python Download](https://www.python.org/downloads/)**

Python is the programming language of choice for the Interject API server. If you are not familiar with Python (I'd hope you are), then
you must download the Python interpreter onto your machine in order to execute Python code.

## Python Packages

There will be a requirements.txt file inside of the project directory that details all the required packages.
