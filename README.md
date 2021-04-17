# Web Development Homework 1: Code Refactor

### Welcome to my code-refactor repositiry
Inside you will find:

* **starter_code** 
    * Unaltered starter code for this assignment
    * A READEME.md file of the assigment instuctions

* **my_code**
    * My assignment submission with starter code alterations
    
----

### Refactoring Changes

* Noted that this page mostly uses `<div>` tags

* Changed `<title>` from "website" to "Horiseon | Home Page"

* Changed `<div>` element of `class="header"` to a `<header>` element
    * Inside new `<header>` slement, changed `<div>` element to `<nav>`
    * Updated CSS for these new tags

* Changed `<div>` element of `class="content"` to a `<main>` element
    * Inside new `<main>` element, changed three `<div>` elements of `class="search-engine-optimization"`, `class="online-reputation-management"`, and `class="social-media-marketing"` to `<section>` elements.
        * Placed each `<img>` element inside each new `<section>` element inside a `<figure>` element
    
* Changed `<div>` element of `class="benefits"` to an `<aside>` element
    * Inside new `<aside>` element, changed three `<div>` elements of `class="benefit-lead"`, `class="benefit-brand"`, and `class="benefit-cost"` to `<section>` elements

* Added alt attributes to `<img>` elements 

* Changed `<div>` element of `class="footer"` to a `<footer>` element

---

*Image of assignment webpage*

![Assingment Webpage](webpage_image/01-html-css-git-homework-demo.png "Assignment Webpage")


