css follows -> selector { properties : value ;}
Mainly two things Selector and Properties
example        div.bolt-text { font-weight: 500;}
example        * { color: purple }; // paints everything purlpe

Types of selectors Type , class id .

Type selector selects all tags of same id 
class selector , creates a new class attrib and define in css . It is prefixed by . (period)
Id selector , same as class but prefixed by #

An element can have only one id and cannot be repeated on same page again WHere as class has no such restraints

selectors can be grouped for avoiding repeatation of code . Done by .one , .two {properties}

selectors can be chained , works with id and class too . This is dont by .one.two {properties}

Various properties (expanding list )

color , backgroud-color  , font-family , font-size , font-weight , text-align

In multi selectors chained overrides single and id overrides class .

parent class properties are inherited b the child tags


How to add css to html
 External <link rel="stylesheet" href="styles.css"> keeps code clean and segmented
 Inline   Embedded in the tags declaration itself > code looks messy and harder to manage 
 Internal css declared and defined in html page it

 Box model 
 Padding = space between box border and text
 border = border size
 margin = space between box border and browser border 
 Most elements are blocks which are stacked on top of each other display:block
 Where as inline elements start on the new line 
 Div is block-level element by default and is used as a container for other elements
 Dive allows division of page into different blocks and apply styling to these blocks

 more on boxes later

 Flex box
 make a container and add some items which follows its rules
 flexbox flex-wrap etc
 display: flex /inline enables flex 
 flex 1 means flex-grow 1, flex-shrink 1, flex-basis 0
 grow allows to consume all space 
 shrink allows to shrink on less space
 basis leaves extra space blank 
 flex-wrap:wraps all elements inside the flex container nowrap / wrap / reverse
 flex-direction : column / row / reverse
 justify-content : flext-start / flex-end / flex-center / space-between / space-around /space-evenly distributes item on x axis
 align-items flex-start / flex-end / center / baseline / strech  
 align-content : flex-start / flex-end / center / space-between / space - around / strech distributes on y axis
 
 Children -
 order :integer number allows to set order as required
 flex-grow 1 /2 /3 allows element to grow size x times 
 align-self sets alignment for individual items 
 gap adds gap
 margin 
 widht 
 height 
 padding 
 
