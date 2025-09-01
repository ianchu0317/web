---
layout: page
title: Led API
description: LED control through web app using API - Raspberry PI + Arduino
img: assets/img/led-api-1.jpg
importance: 3
category: personal
related_publications: true
---

## This project

This project let you control a set of LEDs through an responsive and intuitive frontend web app. 
I've built this to practice Arduino development and API development with Raspberry PI (because I'm interested on learning domotics and DIY projects).

The source code and documentation can be found on its GitHub [link](https://github.com/ianchu0317/LED-control-API). 

I've also uploaded a demostration video [on TikTok](https://www.tiktok.com/@_ianchuuu/video/7478852104531037495).

<div class="row">  
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/led-api-1.jpg" title="Led API image" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/led-api-3.jpg" title="breadboard diagram" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    Physical electronic connection on breadbard and connection diagram
</div>


The downside of this project is that I didn't know `docker` in that time so all the software configuration on the Raspberry PI (backend API + frontend) have to be done manually using the bash script provided on the GitHub Repo.


---

## Features
- Control effect change through fisical button or web page
- Control effect velocity through web page
- Beautiful and easy to install

---

## Technologies used
- `Raspberry PI` 
- `Arduino` 
- `FastAPI (Python)` for API and RPi.GPIO
- `HTML, CSS, JS` for frontend web 
- `Bash` for scripting and automation of initial config