---
title: 'From data to information'
subtitle: 'An introduction to using remote sensing data and open-source tools for analysis of foreshore characteristics'
font-import: 'https://fonts.googleapis.com/css?family=Fira+Sans'
font-family: 'Fira Sans'
author:
- Edward P. Morris (UCA-CEIMAR) and Bas Oteman (NIOZ)
#- company: University of Cadiz
#  github: https://github.com/edwardpmorris
#  name: Edward P. Morris
#  twitter: '@EdwardPMorris'
#  www: http://rnm214.uca.es/CV/emorris/cvepmorris
#- company: NIOZ
#  name: Bas Oteman
date: "Delft Software Days 2015-10-20"
logo        : UCA-ceimar-NIOZ-FAST-logo-1100-198-transparent.png
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : prettify      # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {selfcontained, standalone, draft}
knit        : slidify::knit2slides
---

--- .class1 #id1 bg:black

<iframe width="565" height="315" src="https://www.youtube.com/embed/gF9UlTYR5d0?rel=0&amp;controls=0&amp;showinfo=0" frameborder="-1" allowfullscreen></iframe>

<div style="position: absolute; left: 200px; top:625px; z-index:10; font-size:14px">
    <p>https://youtu.be/gF9UlTYR5d0</p>
</div>


--- .class1 #id1 bg:black

<iframe width="560" height="315" src="https://www.youtube.com/embed/28hImDyJXu0?list=PLbyvawxScNbs9ET50PFwZTworudkNsnH_" frameborder="0" allowfullscreen></iframe>

<div style="position: absolute; left: 200px; top:625px; z-index:10; font-size:14px">
    <p>https://youtu.be/28hImDyJXu0?list=PLbyvawxScNbs9ET50PFwZTworudkNsnH_</p>
</div>

--- .segue #id2 bg:url(assets/img/background_space.png);background-size:cover

## Remote sensing terminology

--- .class1 #id3 bg:url(assets/img/background_white.png);background-size:cover

## Platform, sensor and resolution


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

--- .segue #id4 bg:url(assets/img/background_scientist_marsh.png);background-size:cover
## How to get access to remote sensing data

--- .class1 #id5 bg:url(assets/img/background_white_scientist.png);background-size:cover
## Data availability
+ a table giving overview of some platform sensors, type of information and availability

--- .class1 #id5 bg:url(assets/img/background_white_scientist.png);background-size:cover
## NASA 
+ MERIS
+ Landsat 8 OLI
+ Landsat 7
+ EarthExplorer

--- .class1 #id5 bg:url(assets/img/background_white_scientist.png);background-size:cover
## Copernicus 
+ The Sentinels
+ Sentinel 1 C-Band SAR
+ Sentinel 2 MSI
+ SentinelHub

--- .segue #id6 bg:url(assets/img/background_scientist_screen.png);background-size:cover;background-color:604c3f;

## How to process images

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
