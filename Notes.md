REFACTORING EVIDENCE
Kept a cleaner/non-repetitive layout in mind while beginning the CSS. If I started to code something with a lot of repetition, I would stop, rethink it, and alter things. Added classes for specific alignment and ROOT variables for spacing and color, to name a few examples.

Naming conventions were thought out beforehand and were created with specificity in mind, if needed. Many rules are general for now and more specific ones could be added as progress is made.

ARCHITECTURE NOTES
All layers are ordered appropriately from the reset to the overrides. The more specific a layer item is, the stronger it is in a layer-system. For example, "li a" would override "a." The more general and base-qualified that the values are, the more of them there are. As things get more specific and are meant to override the base, they lessen to only arguably more essential things. As for my tokens, I wanted to make sure I kept not only colors consistent but also spacing and font values. Creating such tokens makes consistency an easier task and hence paves way for a more enjoyable user experience. When it comes to naming, the more specific a value/rule is, the more specific the naming gets. This is especially apparent for classes and utilities as the specific use should be easy to understand just by reading the name. Finally, browser checks were completed by making a simple HTML and trying out the CSS that I have begun. Screen widths were additionally tested by changing the size of the browser window.

Do note that my current HTML structure does not match my wire frames yet as I am still figuring out the CSS architecture.

AI DISCLOSURE
The only AI used in this assignment was help fixing a bug in the hamburger menu.