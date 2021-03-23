# css Grid 

What is a grid?
A grid is a set of intersecting horizontal and vertical lines defining columns and rows.
Elements can be placed onto the grid within these column and row lines.

The Grid container
We create a grid container by declaring display: grid or display: inline-grid on an element. 
As soon as we do this, all direct children of that element become grid items. 

For external content or internal layout?
There is another way to determine the appropriate system that you should choose when trying to choose between
the flexible parts system and the grid system, in addition to the method that we have previously known about 
and centered on the difference between working in one or two dimensions.

Flexbox based on external content. Among the methods of use for this system is when you have a group of 
items and want to distribute them evenly over an area of a container. As the size of the content of each
element is the first determinant of the space it will occupy (that is, the occupied area is proportional to
the size of the element's content). When the items move to a new line, they will organize themselves
based on their size and the available space on this new line.

The grid system is based on internal coordination. That is, when we work with the network system, 
we define a pre-set layout and define it, and then we put these elements inside this format (or network).
It is also possible to use the automatic positioning features that distribute the elements inside the network 
in specific cells by following the tight grid system. It is also possible to create flexible paths that adapt
to the size of the content, this technique makes the path size completely change. (Note that the path
will take the size of the element with the largest content).

If you are using Flex and feel that you are losing some of the flexibility it provides, then there is 
a good chance that you need to use Grid. For example, if you specify a percentage value for the width 
of one of the elements of the Flex system to take the same size as the elements on the top line, 
in this case you should use the Grid system.

![image](https://user-images.githubusercontent.com/77915248/112232322-0899eb80-8c41-11eb-8edb-9700056d6835.png)

RULES FOR USING grid-template-areas
There are a few rules when creating a layout in this way. Breaking the rules will make the value invalid 
and therefore your layout will not happen. The first rule is that you must describe a complete grid, i.e. every cell on your grid must be filled.

If you do want to leave a cell (or cells) as empty space, you do this by inserting a . or series such as ... with no space between them.

You can only define each area once, meaning that you can’t use this property to copy content into two places on the grid!
So the following value would be invalid and cause the entire property to be ignored as we have duplicated the area three:



grid-template-areas: "one one three three"
                     "one one two two"
                     "three three four four"
                     "three three four four";








