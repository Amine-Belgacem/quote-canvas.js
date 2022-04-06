# Quote-canvas.js
Vanilla .js library for generating social media quote posts. Quote-canvas is a drawing library that supports touch events.

## Main Methods Reference

 - `drawBG(color)`
       Fills the background with a color of type color.
 - `drawRect(color, position, size, fixed)`
       Draws a filled rectangle at position with size.
 - `drawBGImage(path, callback)`
       Draws a background image specified by the path parameter and calls a callback.
 - `drawImage(path, style, position, size, callback, fixed)`
       Draws an image with style, position and size then call a callback.
 - `drawText(str, style, position, width, fixed)`
       Draws a string with style, position and width.
 - `move(elmentId, position)`
       Moves and element specified by elementId to a position then updates and redraws.
  - `update(elmentId, update)`
       Updates the element object specified by elementId.
  - `erase(elmentId)`
       Erasees the element object specified by elementId then redraws.   
  - `redraw()`
       Redraws all elements of the canvas.  
