# random-number-generator

An element that generates one or more pseudo-random integers within a specified
range.   This element can generate duplicates or be directed to generate unique
values.  The results are store in an array called 'results' and can be bound to
if using the element within a Polymer app; otherwise, you can access the results
property from Javascript.


## Usage Example
<random-number-generator unique start="1" end="10" numberofresults="4"
results="{{numbers}"></random-number-generator>

This will generate 4 random, unique integers and store them in the results
property of the element.
