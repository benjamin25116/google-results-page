# google-results-page
_An assignment project from The Odin Project._

I've decided to go with the extended version of the assignment since I have had a little experience with CSS and HTML by the time I started this assignment. Here are a couple of reflections on what I would do differently in another project.

## BEM Naming Convention
I stumbled upon this from Kevin Powell on YouTube after looking up information on "box-sizing: border box". I've come to realise that naming elements consistently and coherently across a simple document like a Google results page is immensely difficult. Names that made sense in the beginning suddenly became inadequate to describe the level of nesting. I found myself changing the class names of elements a couple of times in order to be able to access the nested elements. At many points in the project I just used the right-angle selector to get to the required element. But I found this to be hard to follow when the nesting is a couple of level deep. 

According to Kevin Powell, using the BEM (block-element-modifier. https://en.bem.info/methodology/naming-convention/) naming convention, it would help make the function of class names more apparent right in the naming of it. I'll definitely try using this in my next project. 

## CSS Variables
I did not start out with a colour palette in mind (or since I'm cloning the Google results page, I did not get comprehensive swatches of all the colours used on the page). Because of that, the colours were added as I wrote the code for the project, resulting in various RGB values being used left, right and centre. At many points in writing the code, I've lost track of what each RGB value corresponds to and where it should be used. Worst of all, when I thought that a particular shade of gray should have been lighter or darker, I dare not change it because the same colour has been used in various locations and it would be a hassle to go through and change all of it. 

## Box-sizing
This is another thing that I stumbled upon while looking up information on CSS. It seems that by changing the default behaviour of box-sizing to "border box" instead of "content box", I would be able to control the sizing of the elements in a more predictable fashion since the actual sizing of the box will be based on the borders of it, not the content. I did not do this in the initial reset and only learnt of it much later, so I did not want to break all the sizing and positioning that I've done in the project thus far.

All in all it's been a great learning experience.
