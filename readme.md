# toolbox scss

toolbox scss is a framework aimed at generating a toolbox of reusable 
single-purpose classes.

This generally works the best with non-dynamic parts such as layout, text 
styles, spacing, etc.

Bootstrap (v4) Grid is included by default for columns and some responsive
utility classes.

## Contents

The framework includes some utility functions to deal with arrays and loops for
class generation based on variables.

## Usage

The usage of framework can be summarised in this order:

1. Identify the design system of your front-end - color palettes, text styles 
(font families, sizes, weights), spacing, borders and any other re-usable
patterns, such as transitions, and capture them in SASS variables.

Examples of this can be found in the /variables folder.

2. Build SASS arrays of those variables, then use SASS loops to generate classes
to create the toolbox of classes.

3. 





