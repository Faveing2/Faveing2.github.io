---
title: "Introduction to GasSimulation"
date: '2025-07-22T19:01:53-07:00'
draft: true 
ShowToc: true
tags: [dev]
mathjax: true
---

# Introduction

I was once a computer science major however I decided to switch to physics. One of my big motivations for this change was the idea of combining both my passion for computer science and physics, thus my interest in computational physics was born. While doing my undergrad I had many amazing oppurtunities to explore this interest of mine. Working with MC particle simulations such as GEANT and making my own simulation of our muon detectors. Now that I'm out of undergrad I want to explore this interest on my own. That's exactly what this project aims to be. I intend it to be a starting point for me developing and practicing my skills in this field. I also want this project to be simpler to start off, computational physics can be a very deep subject. 

Basically I want to create a general purpose particle/gas simulation in python that's easy to configure and produce meaningful results from. 

# The simulation

### The Elements

| Class Variables | type |
| --------------- | ---- |
| mass        | float (kg)|
| radius        | float (A)|

### The Particles

Each particle object will need to contains it's current velocity, position, mass (which comes from the element), element, size. The elementType will be a simple object that contains the properties of the particle, for example if the particle is a O2 molecule. 

| Class Variables | type |
| --------------- | ---- |
| velocity        | vector[3] |
| position        | vector[3] |
| element         | elementType |

