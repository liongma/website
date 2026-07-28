---
title: Thermocouple
date: 2022-12-26
summary: A one-line description for the projects list
tags:
  - python
  - react
cover:
  image: cover.png
  alt: inverter-module
  caption: 50kW Inverter Module
  relative: true
---
When making my cloud chamber, i wanted to measure the very low base plate temperatures continuously. Why not make something to measure it? Unfortunately, thermistors are fairly nonlinear meaning they're not so accurate, especially at low temperatures. Whats typcically used for the job is thermocouples, which use voodoo physics to measure precise temperature differentials. I plugged this into an arduino and shoved it into a small tin with an OLED, and it definitely did the job. The next big thing to do would have been to then tune it but that would require buying actual equipment :(