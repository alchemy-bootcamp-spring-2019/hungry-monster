Hungry Monster
===

Make the monster grow by feeding it disgusting or disturbing things, and then have it writhe or contort in joy.



## Page Design

There are three main parts to the page:

1. The buttons for each kind of food to feed the monster. 
Place an image inside your HTML button to show what it is. Give each 
button a `value` attribute with the name of the food. 
1. The monster head and body segments. The body segments are color 
coded based on the type of food the monster was feed. Use the food type 
as a CSS class so you can style appropriately
1. The buttons to make the monster "dance" the corresponding body segments. Give each
of these button a `value` attribute with the name of the food as well.

_New T&C:_

1. **HTML Elements**: `<h2>`, `<span>`
1. **HTML Attributes**: `value="apple"`
1. **CSS Styling**: `padding`, `border-style`, `cursor`, `line-height`, `background`
1. **CSS Styling**: `display: inline-block`, `height`, `width`
1. **CSS Styling**: negative margins: `margin-left: -12px;`

## Feed the Monster

On each food button click, add one new body segment to the monster. 
You'll want to look at your statically design segments to figure out:
1. What type of element to create
1. What classes it needs

_New T&C:_

1. **DOM Traversal**: use css selector to get DOM elements via `document.querySelectorAll('.class')
1. **Control Flow:** for loop with `index`
1. **Lists:** access items by index: `list[index]`
1. **DOM Nodes**: create new elements with `.createElement('tag')`
1. **DOM Nodes**: add new element to existing element with `.appendChild(node)`
1. **App Design:** function as unit of work (`feedMonster`)

## Monster Dance/Writhe/Slither

When each dance button is clicked:

1. Remove the `.dance` class from all the body segments
1. Add the `.dance` class to those body segments that have the matching food class

The `.dance` class should cause the segment to move using a CSS `transform`. You can also
add a `transition` to animate the dance move.


_New T&C:_

1. **Strings:** concatenate string to make css selector
1. **CSS Styling**: `transform`, `transition`

## Dynamic Buttons (STRETCH)

Instead of having the food buttons statically defined in the HTML, create them from
a list (array) of food names. Start with dance buttons, then try the food buttons (which require the creation of an `<img>` as well that needs to be appended to each
button)

_New T&C:_

1. **Lists:** array of strings
1. **Lists**: access array item by index `array[index]`
