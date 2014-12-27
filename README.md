Pattern Requirements

This document will describe the structure of each pattern and its behavior under varius screen sizes.

---

## The Grid System

**Description**

- 12 columns
- Responsive, fluid
- columns will be wrapped in a container .row
- each column will have the class of .col-$
- Also create a .container class that wraps all content and centers it on the page. the container must be fluid in width.

**Responsive Behavior**

- In smaller screen sizes (<1024px) the columns will have their gutter width halved
- In mobile sizes (<768px) all columns will get a 100% width

## Typography

** Elements **

- Headings
- Paragraphs
- Bold, Em, Strike, Link
- Code blocks
- Lists
- Blockquotes

## Buttons

**Description**

- 2 styles: default, primary
- 3 sizes: small default and large
- styles for all HTML elements: <a>, <button>, <input type="button">, <input type="submit">

**elements**

- inputs
- radio and checkboxes (custom controls)
- pre-made forms: sign-in, sign-up, contact

## Icons

**Description**

- 4 messages boxes: information, success, error, warning

## Navigation

**Elements and Characteristics**

-Navbar
- Contains logo on the left side and menu on the right side
- The menu will be powered by the SuperFish jQuery plugin

**Responsive Behavior**

- At page load, the main menu will be cloned via jQuery into a responsive menu
- in mobile sizes (<768px) the main menu will be hidden, the logo moved to the center and the responsive menu will be displayed below the logo

## Animations

**Description**

-Custom controls

## Carousels

** Description **

-Will use the Cycle2 jQuery Plugin
