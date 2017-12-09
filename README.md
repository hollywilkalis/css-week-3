# CSS Week 3 Review Project

#### For this project I chose to continue working on a rehab of a landing page for a small organization I volunteer with.

#### By Holly Wilkalis

## Description

This is a mockup of a new landing page for the Portland Old Time Music Gathering.

## Setup/Installation Requirements

* Using your Terminal (or other similar tool) navigate to the location where you would like to save the project files.
* Run command: $ git clone https://github.com/hollywilkalis/css-week-3
* Run this command to change into the project directory: $ cd css-week-3
* You can now view and edit all the files used for this project.

To view a live version of this site, visit: http://hollywilkalis.github.io/css-week-3

## Known Bugs

The slideshow is not yet 100% functional.

## Support and contact details

If you have questions about the project (or want to talk about stringband music!), e-mail me at holly.wilkalis@gmail.com.

## Technologies Used

This project uses MaterializeCSS, HTML, Javascript, and SCSS.

### License

Licensed MIT

Copyright (c) 2017 Holly Wilkalis

### Project Thoughts and Feedback
This was a frustrating two days. I think we started out okay, by sketching out several ideas for layouts, but then we stumbled a little over the requirement to identify SASS elements to be used.

We did use the 7-1 pattern (though didn't wind up having elements in all 7) and I think it might have helped to at least write out what major elements would go in each so there wasn't so much confusion on this as we went.

My partner really wanted to use media queries for all responsive elements. I wanted to make more use of the Bootstrap grid to place elements of the page. This was hard. In the end we wound up splitting up the work so she was writing media queries to move the major components of the page and I was starting to work on the elements that went within those. This in retrospect was not a good approach - lesson learned.

I still think using a Bootstrap grid or at least making use of the looping example would have been the better approach to what we were trying to do, but we should have found a better compromise. As it was we wound up having an aha moment right at the end of the day and were able to salvage the page, but it took a lot of pain to get to that point. We definitely had some communication issues that I tried to work on, but I don't feel like I was that successful.

### Today's approach
Today I want to try a simpler version of the page, one that makes better use of a framework for things like the nav bar and a slideshow, so that fewer things have to be custom built. I'm not sure yet how I want to create the grid yet - maybe going back to the Monday exercises. I will definitely be focusing more on building one element at a time, and completing one media query at a time (I hope!).

### SASS elements used
| Mixin              | Used to create custom "brand" colors to be reused across a variety of elements.                                                |
| Operators          | Used to create custom element sizes                                                                                            |
| Extend/inheritance | Used to create certain base styles for a series of similar elements, in this case the styling of the three parts of our footer |
| Partials           | We definitely made use of partials to organize our SCSS.                                                                       |
| Nesting            | We intended to use nesting for some elements of the nav bar but we never got that built out.                                   |
