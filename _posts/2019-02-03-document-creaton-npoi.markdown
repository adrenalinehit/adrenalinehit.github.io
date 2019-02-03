---
layout: post
title:  "Creating documents using NPOI"
date:   2019-02-03 12:20:00 +0100
categories: dotnet hacking npoi documents
---

Write up of creating documents using NPOI and dotnet core.

# Challenge

* Create a word document (doc, docx etc) server side from a template document
* Replace tokens thus building a personalised document
* Must work in dotnet core land

# Solution

Looked into various libraries, but the favorite was NPOI, simply because:

* it's free
* lots of examples online
* works in dotnet core land

# Credits / resources

[Java version of the replacer](https://stackoverflow.com/questions/22268898/replacing-a-text-in-apache-poi-xwpf)
[Nuget package for DotNetCore NPOI](https://www.nuget.org/packages/DotNetCore.NPOI)

# Code

On github [here](https://github.com/adrenalinehit/npoi-example)

Enjoy.

