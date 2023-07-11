---
title: Task Management
publishDate: 2023-04-06 00:00:00
img: /assets/task-manager.png
img_alt: Task list on black/purple background, with a category and tags to define each task, and a "new task" button to add a new task.
description: |
  An application for managing personal and/or professional tasks, as required. It lets you save, edit and delete tasks, and add categories and/or tags to make them easier to recognize.
tags:
  - Laravel
  - API REST
  - Single Page Application
---

## Designing a task management application

The code is available from <a href="https://github.com/Christelle-Hidoine/Task-Management">GitHub</a>.

Development of a task management application by creating a **API REST** and using the **SPA** (Single Page Application) concept.

### CRUD

Set up all methods for managing website data in the form of REST APIs: list, create, update, delete.

### Structure

This site has been designed according to the MVC (model, view, controller) architecture and uses namespaces.

The LARAVEL framework is used to manage endpoints (API access routes) and all database handling in a \backend folder.

Javascript is used to create the frontend in Single Page Application format, to achieve the best page-loading performance and user experience.

### Relational database schema

ManyToMany relationship when using tags and OneToMany when processing categories.

Test data retrieval in json format.

### Responsive design

This site was created in Mobile First and also has a visual adapted for the tablet and desktop format.

Use of Media Queries in the CSS section.

### Technology

The technologies used to make it : PHP 7.4, Laravel 8, Javascript, HTML5, CSS3.
