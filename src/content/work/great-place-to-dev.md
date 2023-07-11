---
title: Great Place To Dev
publishDate: 2020-06-28 00:00:00
img: /assets/great-place-to-dev.png
img_alt: A world map with markers on the capitals of each country covered by the website and an open filter on the left of the page with selectors by criterion.
description: |
  An application offering a comparative website of cities around the world for working remotely with a list of criteria corresponding to the preferences of the searcher.
tags:
  - Search
  - Filter
  - Javascript
---

## Group project using the SCRUM Agile method

This project lasted 1 month and involved us working in groups of 4 people over 4 sprints using the SCRUM Agile method.

The code is available from <a href="https://github.com/Christelle-Hidoine/great-place-to-webdev">GitHub</a>.

<details><summary>Drawing up specifications</summary>

- Definition of an MVP (minimum viable product) with essential features
- Addition of possible evolutions once the MVP has been completed
- Creation of wireframes
- Study of the website tree structure
- Choice of technologies to be used
- Determination of compatible browsers
- Graphic charter and layout of main website pages
- List of front and back routes
- Creation of data dictionary, MCD and MLD
- Accessibility-oriented choices for the graphic charter (colors, contrasts, font size, typeface, HTML attributes)
- Consideration of SEO
- Creation of logo/slogan
- Choice of graphics
- Determination of permissions/roles for access to site pages
- Use of Trello to create and monitor User Stories

</details>

### Creating a Database

Consideration of relational schemas for the creation of the database according to the plan established in the specifications

### Setting up security

With the Symfony framework, routes are secured using ACLs (access control lists) and role hierarchies are defined.

Data retrieved from forms is filtered and validated according to the validation constraints defined in entities and during form creation.

Templates only display links that are accessible according to authorized roles (e.g.: bookmark access button, backoffice access link).

Tokens are automatically implemented in each form and verified through the UserAuthenticator.

### Structure

The project is organized according to the MVC method.

Templates are separated by category and divided into partials for better site maintainability.

### Performance

We use custom DQL queries (with Doctrine) to retrieve only the data needed for each view and improve website performance.

### Technology

PHP 7.4, Symfony 5.4, Tailwind 3, CSS 3, HTML 5, Javascript, NoUiSliders, Leaflet, AmCharts, KNP Paginator
