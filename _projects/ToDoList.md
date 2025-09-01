---
layout: page
title: ToDoList
description: To Do List web app with user authentication - full stack project - unique list for every user - todo.ianchenn.com
img: assets/img/ToDoList1.png
importance: 2
category: personal
related_publications: true
---

## This project

This is my first full stack project using docker. 

It is the basic `to do list` beginner project to practice CRUD operations and RESTful API development but I added some cool features like users authentications with JWT, so every user can have their own list :)

Then I deployed this project on my Home Server and can be accessed on [todo.ianchenn.com](https://todo.ianchenn.com).

And finally I documented all on my [GitHub Repository](https://github.com/ianchu0317/ToDoList).

<div class="row">  
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/ToDoList1.png" title="example image" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    Screenshot main page after login
</div>


---

## Features
- Create / read / update / delete tasks
- Toggle task completion
- User creation and authentication
- Unique list for every user
- Persistent data using MySQL
- Responsive frontend
- Dockerized for easy deployment

---

## Technologies used
- Python (FastAPI)
- MySQL
- Docker + Docker Compose
- Vite + React + Tailwind CSS
- Apache2
- Cloudflare

