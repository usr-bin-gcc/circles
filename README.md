# circles

I wrote this program to help understand the way in which RiscOS desktop applications are redrawn if a window changes size, scrolls, is occluded or iconized.  The application produces two windows, a main window containing some randomly place circles and a monitor window, which displays the rectangular area to be redrawn at each step and displays the circles that must be redrawn in green and those that need not in red.  Understanding the size and behaviour of the redraw rectangles was useful to me in thinking about how to implement redraw efficiently.

I've only recently started learning RiscOS desktop programming, so I expect the code is rather un-idiomatic and could be improved in a variety of ways.  Constructive feedback is always welcome.
