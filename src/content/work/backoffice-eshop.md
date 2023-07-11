---
title: Backoffice eShop
publishDate: 2023-04-23 00:00:00
img: /assets/backoffice_eShop.png
img_alt: Backoffice homepage of In the Shoes website with 2 columns, category list and product list
description: |
  In the Shoes e-commerce backoffice website with data processing permissions
tags:
  - PHP
  - Permissions
  - Security
---

## Designing a website backoffice

The code is available from <a href="https://github.com/Christelle-Hidoine/BackOffice-EShop">GitHub</a>.

As part of my training, I developed the backoffice of an e-commerce website, using the SCRUM Agile method in 3 sprints.

### CRUD

Set up all methods for managing website data: list, create, update, delete.

### Security

Security is at the heart of this website.

Routes are accessible according to the permissions granted using an Access Control List (ACL), which is checked at each authentication.

Tokens also play an important role in sending data to our database. They are placed in each form and on data deletion links to ensure the most secure use of this site and to prevent the form being returned a second time (to counter CSRF attacks).

Data is filtered and processed before being transmitted to our database (to counter XSS attacks).

### Structure

This site has been designed according to the MVC (model, view, controller) architecture and uses namespaces.

### Technology

The technologies used to make it : PHP 7.4, Bootstrap 5.1, HTML5, CSS3
