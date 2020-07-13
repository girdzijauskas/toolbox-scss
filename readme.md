# Toolbox SCSS

toolbox scss is a framework aimed at generating a toolbox of reusable 
single-purpose classes.

This generally works the best with non-dynamic parts of your front-end such as 
layout, text styles, spacing, etc.

*Bootstrap (v4) Grid is included by default for columns and some responsive
utility classes.*

## Contents

The framework includes some utility functions to deal with arrays and loops for
class generation based on variables, as well as some Bootstrap components such
as grid and some utilities.

## Usage

The usage of the framework can be summarised in this order:


1. Prerequisites

   a. Identify the individual elements of your front-end - color palettes, text styles 
(font families, sizes, weights), spacing, borders and any other re-usable
patterns, such as transitions, and capture them in SASS variables. Examples of
this can be found in the /variables folder.

   b. Identify the default styles for your design system. Good defaults to cover are
things like text styles (h1, h2, ...), form and input elements, buttons, links,
etc. 

2. Apply your default styles using HTML elements (form, input, button, a, h1, ...), 
and generate classes that can apply the same styles. (For example, a .button
class that can style a link or another element in the fashion of a button.) 

3. Generate utility classes for your color palettes and font-sizes.

