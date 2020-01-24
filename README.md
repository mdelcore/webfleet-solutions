# webfleet-solutions

### Background:

Consider the attached image as part of the about us section of our website. The bar chart reflects the amount of vehicles equipped with our solution across the globe.

Each year, this graphic requires an update reflecting the new business results which is time consuming hence requiring a better solution.

### Task:

* Implement the bar chart via HTML/CSS. The bars should scale relatively to each other while the size/width of the largest bar (regardless of whether it’s most recent year or not) is always 100% of the width of the wrapping container. Don’t worry about the height of the wrapping container.

* Implement a feature which allows to define the business figures outside of the HTML template in a certain data structure (e.g JS object or array)dynamically show the past $x years which should be defined in a configuration object or array. In case the amount of years to show is higher than the available business figures, only show these figures available. E.g. in case you got the figures for the past 3 years and the configuration for this template is to show the last 5, show only the last 3.

* Bonus: Enrich the snippet with CSS/JS transitions/animations. E.g. fade-in container and bars nicely.
 

### Settings:

**Use the following colors:**

* #455560 (dark grey)
* #bed52e (lime green)

**Use the following figures:**

* 2014: 463.000
* 2015: 600.000
* 2016: 670.000
* 2017: 785.000
* 2018: 848.000

Show the past 3 years
 

### Requirements:

* Code should be lightweight and sustainable (easily scale up)
* Browser compatibility Edge+
* Not necessary to consider mobile break points
* Prevent using any libraries (no CSS or JS frameworks/libraries)
