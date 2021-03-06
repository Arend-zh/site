---
layout: single
title: Download
toc: true
toc_label: Download
toc_sticky: true
---

You need to have JRE 8 installed on your computer to use Arend.
Arend is available either as an [IntelliJ IDEA plugin](#intellij-idea-plugin) or as a [console application](#console-application).

## IntelliJ Arend

{% include intellij-arend.md %}

You can read more about IntelliJ IDEA [here](https://www.jetbrains.com/help/idea/discover-intellij-idea.html).
To create an Arend project, follow instructions [here](/documentation/getting-started#intellij-arend).

## Console Application

{% include console-application.md %}

To create an Arend project, follow instructions [here](/documentation/getting-started#console-application).

## Standard Library

The standard library contains a number of essential definitions and proofs, in particular, in constructive algebra and homotopy theory.
It can be downloaded from [GitHub](https://github.com/JetBrains/arend-lib/releases/latest/download/arend-lib.zip).
It should be unpacked and the directory `arend-lib` should be put in some specific directory `libs` in which all Arend libraries are stored.
The path to `libs` can be specified either with command line option `-L` in the console application or in module settings in IntelliJ IDEA.
