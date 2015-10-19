---
title: 'From data to information'
subtitle: 'An introduction to using remote sensing data for analysis of foreshore characteristics'
font-import: 'https://fonts.googleapis.com/css?family=Fira+Sans'
font-family: 'Fira Sans'
author:
- company: University of Cadiz
  github: https://github.com/edwardpmorris
  name: Edward P. Morris
  twitter: '@EdwardPMorris'
  www: http://rnm214.uca.es/CV/emorris/cvepmorris
- company: NIOZ
  name: Bas Oteman
date: "Delft Software Days 2015-10-19"
logo        : UCA-ceimar-NIOZ-FAST-logo-1100-198-transparent.png
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : prettify      # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {selfcontained, standalone, draft}
knit        : slidify::knit2slides
---

--- .class1 #id1 bg:url(assets/img/background_black.png);background-size:cover;background-color:black

<iframe width="565" height="315" src="https://www.youtube.com/embed/gF9UlTYR5d0?rel=0&amp;controls=0&amp;showinfo=0" frameborder="0" allowfullscreen></iframe>

https://youtu.be/gF9UlTYR5d0

also: https://youtu.be/-WXM9ulaBng?list=PLbyvawxScNbus9n8rmw0GElhPqrCwcsiD


--- .class1 #id2 bg:url(assets/img/background_space.png);background-size:cover

## Remote sensing terminology [15 min]

--- .class1 #id3 bg:url(assets/img/background_white.png);background-size:cover

## Platform, sensor and resolution {class: nobackground fill}

testing dark background

--- .class1 #id3 bg:url(assets/img/background_white.png);background-size:cover 

## Electromagnetic radiation

--- .class1 #id3 bg:url(assets/img/background_white.png);background-size:cover
## Passive visible

--- .class1 #id3 bg:url(assets/img/background_white.png);background-size:cover
### Applications
Contains information on...

--- .class1 #id3 bg:url(assets/img/background_white.png);background-size:cover
## Active radio

--- .class1 #id3 bg:url(assets/img/background_white.png);background-size:cover
### Applications
Contains information on...

--- .class1 #id4 bg:url(assets/img/comic_scientist_screen.png);background-size:cover
# How to get access to remote sensing data

---
## Data availability
+ a table giving overview of some platform sensors, type of information and availability

---
## NASA 
+ MERIS
+ Landsat 8 OLI
+ Landsat 7
+ EarthExplorer

---
## Copernicus 
+ The Sentinels
+ Sentinel 1 C-Band SAR
+ Sentinel 2 MSI
+ SentinelHub

---
# How to process images

---
## Basic concepts
+ georectifying
+ calibration
    + at-instrument
    + top-of-atmosphere
    + surface
+ morphological operations [filtering, changing resolution]
+ course classification [clouds, shadows, water]

---
## Sentinel Application Platform (SNAP) | A common architecture for all Sentinel Toolboxes
+ open-source
+ sucsessor of the mature BEAM software
+ Java
+ Python bindings
+ Sensor specific toolboxes

---
## Getting help 
+ Toolbox tutorials
+ The SNAP forum; a shared user experience
+ SNAP development; how to contribute

---
## The power of the Graph Builder and Graph Processing Tool
+ building workflows [graphs]
+ applying to single image
+ batch processing
+ access via the commandline
+ access via Python

---
# Practical examples [45 min, exercises on PC]

---
# Using Sentinel 1 toolbox (S1TBX) to get information about coastal systems [15 min, examples to be defined!]

---
# Using Sentinel 2 toolbox (S2TBX) to get information about coastal systems [15 min, examples to be defined!]

---
# Together is better! Synergy products [15 min, examples to be defined!]

---
