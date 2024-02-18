## Parallax Scroll Effect and Link Behaviour

This code implements a parallax scroll effect along with handling link behavior within an iframe. 

Here's a breakdown of its functionality:

# Parallax Scroll Effect

The JavaScript code enables a parallax scroll effect by adjusting the CSS variable --pctbased on the user's scroll position relative to a .parallax element's height. 
This creates a smooth transition effect as the user scrolls down the page.

# Passive Event Listener Support

The code checks for passive event listener support and applies it to the scroll event listener when supported.
This helps to improve scrolling performance by allowing the browser to optimize event handling.

# Handling Links within an Iframe

It checks whether the code is running within an iframe using the inIframe() function.
If so, it displays a designated element (.no-iframe) to indicate that links will open outside the iframe. 
This ensures a better user experience by avoiding potential issues with iframe navigation.

# Masks

The SVG masks (m1 through m7) define specific areas within SVG graphics.
These masks are used for various visual effects or elements within the SVG.

# Note

The provided SVG paths within the masks are not included in the description as they are specific visual
representations and their effects are applied within the SVG elements.


## Conclusion

Overall, this code provides a combination of visual effects (parallax scrolling) and practical functionality (handling links within iframes) to enhance the user experience on a web page.
It demonstrates effective use of JavaScript and SVG graphics to create engaging web interactions.


