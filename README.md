# Web Development Homework 1: Code Refactor

### Welcome to my code-refactor repositiry
Inside you will find:

* **instructions** 
    * A READEME.md file of the assigment instuctions

* **index.html**
    * My assignment submission for improved webpage accessibility

* **assets**
    * Folder containing CSS and images
    
----

### Refactoring Changes

* Noted that this page mostly used `<div>` tags

* Changed `<title>` from "website" to "Horiseon | Home Page"

* Changed `<div>` element of `class="header"` to a `<header>` element
    * Inside new `<header>` slement, changed `<div>` element to `<nav>`
    * Updated CSS for these new tags

* Changed `<div>` element of `class="content"` to a `<main>` element
    * Inside new `<main>` element, changed three `<div>` elements of `class="search-engine-optimization"`, `class="online-reputation-management"`, and `class="social-media-marketing"` to `<section>` elements.
    
* Changed `<div>` element of `class="benefits"` to an `<aside>` element
    * Inside new `<aside>` element, changed three `<div>` elements of `class="benefit-lead"`, `class="benefit-brand"`, and `class="benefit-cost"` to `<section>` elements

* Added alt attributes to `<img>` elements 

* Changed `<div>` element of `class="footer"` to a `<footer>` element

* In CSS
    * Rewrote header rules with header selector instead of with "header" class
    * Many rules were able to be condensed under classes "content" and "benefits"

---

*Image of assignment webpage*

![Assingment Webpage](webpage_image/01-html-css-git-homework-demo.png "Assignment Webpage")


