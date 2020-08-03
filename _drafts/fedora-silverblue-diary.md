---
layout: post
title: "Fedora Silverblue Beginners Diary"
author: "Frank Zimmer"
categories: journal
tags: [documentation,review]
image: silverblue-logo.svg
---

## Introduction

Fedora Silverblue is an immutable, minimal version of the standard Fedora Workstation based on Gnome. Other desktops environments are in 
the [work](https://discussion.fedoraproject.org/t/kinoite-a-kde-and-now-xfce-version-of-fedora-silverblue/147/163).

This post is a structured as a kind of diary of my first days with [Fedora Silverblue](https://silverblue.fedoraproject.org).

## Day 1

### Install and upgrade process

I downloaded the Fedora Silverblue image a while ago, before F32 was released in April 2020. My intention was to try-out the upgrade process with freshly system. One could argue that this is the easy case compared to a fully fleshed out system, but I caould already learn something from this simple case. 

Automatic updates is the default behavior when it comes to software updates in Silverblue. This process started immediately after the first login into the system. However, my intention was to
upgrade the system using Gnome Software immediately to F32. Pressing the "Download" button in Gnome
Software returned an error message while the automatic update process of the installed software was still ongoing. After the update process finished I pressed the button again and the Download process started. That this is was the case was not at all obvious because no progress bar was shown in
the GUI. I only could verify this by checking the network using System Monitor. Finally, if I'm not 
mistaken the System automatically reboot without notifying the user. This was an unexpected behavior. 

### First steps with Toolbox 

If you're used to working in container environment Toolbox is a great tool, because it allows you 
to keep you system clean.