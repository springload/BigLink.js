bigLink.js
====================

A handy jQuery plugin that turns container elements into links.

Apply .bigLink() to your container element. The default behaviour will use the href of the first link found inside the container. This can be overridden by using the "target" option.

It also supports command/control click (to open links in a new tab).

##Options:
* **target**: String or jQuery Element that exists inside the container. Use this element's href attribute as the link to go to when the container is clicked. Default 'a'
* **avoid**: String or jQuery Element that exists inside the container. Clicking on this will not result in bigLink.js being implemented. Default 'a'

##Example:
```
$(".my-selector").bigLink({
    avoid: "a.my-other-link"
});
```
