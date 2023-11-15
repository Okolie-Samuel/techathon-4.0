# HTML

# Introduction to HTML

=========================

HTML - Hypertext Markup Language.
HTML is the standard markup language for Web pages.
HTML consists of a series of elements
HTML elements tell the browser how to display the content
how HTML looks like.
The <!DOCTYPE html> declaration defines that this document is an HTML5 document
The <html> element is the root element of an HTML page
The <head> element contains meta information about the HTML page
The <title> element specifies a title for the HTML page (which is shown in the browser's title bar or in the page's tab)
The <body> element defines the document's body, and is a container for all the visible contents, such as headings, paragraphs, images, hyperlinks, tables, lists, etc.
HTML element - <tagname> Content goes here... </tagname>
Nested elements examples.
headings and paragraph
attributes
styling, block and inline elements
comments

# Lists, classes and IDs

========================
ordered list (list that are numbered orderly), unordered list (not numbered as the name suggests)
class and id attributes(.className, #ID)-
.getElementsByClassName, .getElementById
brief on html semantics

# Links, images

===============
links and link bookmarks
images
background images

# Tables, Forms, and Iframes

============================
Table borders, size, headers, padding, row and col span.
Form attributes - action, target, method
Form elements - input, select, textarea, button
Iframes

# CSS

# Introduction to CSS

=====================
CSS stands for Cascading Style Sheets
CSS describes how HTML elements are to be displayed on screen, paper, or in other media
CSS saves a lot of work. It can control the layout of multiple web pages all at once
External stylesheets are stored in CSS files
css syntax
selcetor {
property: value;
}

# CSS selctors and comments

==============================
Simple selectors (select elements based on name, id, class)
universal selctor
grouping selector (p,h2, .hello)
combinator selector:
decendant selector -
div p {
background-color: yellow;
}
Child selector (selects all elements that are children of a specified element.) -
div > p {
background-color: yellow;
}

Pseudo class (defines a special state of an element.)
div:hover {
background-color: blue;
}

# Styling

==========
Borders - width, style, color
border radius
Margins and Paddings - top, right, bottom, left
box-sizing - border box
css backgrounds (bg img, bg position, bg repeat, bg size) and colors (hex, rgb, hsl, gradients), max width
css display - block, inline, none

# Responsive

============
Media queries
flex-box
grid

# JavaScript

=============
Introduction to JavaScript - syntax

# JavaScript fundamentals

Js outputs - innerHTML, document.write(), alert(), prompt(), console.log()
Variables - var, let, const
Data types (string, number, null, undefined, boolean), operators (arithmetic, assignment, logical, comparison), Js Maths and Random
JS events, functions and ES6 syntax
JS conditionals, Loops
Data structures - Arrays and objects (various methods involved in them)
Document Object Model (DOM)
