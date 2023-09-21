# Labarum
A Hugo/Micro.blog theme based on html and schema tags.

![Basic Header of Labarum](media/labarum-basic-header.png)

I created this to learn more about Micro.blog and hugo and I'm pretty proud of it. It handles all of the basic Goldmark syntax and has both a light and dark mode. 

## Labarum has a light and dark mode.
![Theme in light mode](media/labarum-part6-light-mode.png "Using Local copy")
![Theme in dark mode](media/labarum-part6-dark-mode.png "Same theme but in dark mode")

## Basic syntax

![Labarum theme with sample text moving from light to dark mode](media/labarum-basic-syntax.gif)

## block quotes

![Block quotes going from light to dark mode](media/labarum-block-quote.gif)

## lists

![Lists going from light to dark mode](media/labarum-lists.gif)

## tasks lists

![Task list going from light to dark mode](media/labarum-tasklist.gif)

## Release notes

### v1.1.4

* Create parameters `showDebugInfo` & `showAuthorInfo`
    * Defaults to `false`
    * The information is rendered into the page but is hidden using `display:none` in inline style.
    * Can be toggled on or off in plugin settings.

* Adjustments in different aspect of the theme to prepare to moving to [CUBE CSS](https://cube.fyi)

* Modifications to tables
	* Using `min-width` and `margin: auto` for centering the table to the container and making use of the space that is available.
	
* Modifications to code blocks
	* An update in rendering added more styling.

* Removed increased padding on links as part of a:hover

* Added styling for `<s>`
	* This was previously overlooked as it was thought to be the same as `<del>`.

* Update the README.md