CHECKS (11/05/26):
- Browser size checks done at narrow through wide. All elements currently react as expected. Same goes for 200% zoom, image sizes, alt text, and layout shifts. Loading is also as expected.

NOTE: All reactive images are currently in the gallery page only and will be added to the home/index further in the process.



CHECKS (10/22/26):
- Narrow, medium, and wide browser sizes all respond as expected. Keyboard focuses work, still piecing together on how to open the small screen menu via keyboard. The dark mode condition was also tested by switching modes. The feature query is there to show that it works, will likely alter this to something else that makes more sense down the road.

GENERAL NOTES:
LACK OF SUBGRID (CURRENT):
    My current page is not yet in need of a subgrid. I may decide to utilize one within the gallery page.

REFACTORING EVIDENCE
Kept a cleaner/non-repetitive layout in mind while beginning the CSS. If I started to code something with a lot of repetition, I would stop, rethink it, and alter things. Added classes for specific alignment and ROOT variables for spacing and color, to name a few examples.

!!Specific Example!!
    Instead of setting multiple elements set to a specific color (for example, the black test in the print media section), all text elements were listed together with commas instead of each having their own separate sections.

Naming conventions were thought out beforehand and were created with specificity in mind, if needed. Many rules are general for now and more specific ones could be added as progress is made.

ARCHITECTURE NOTES
All layers are ordered appropriately from the reset to the overrides. The more specific a layer item is, the stronger it is in a layer-system. For example, "li a" would override "a." The more general and base-qualified that the values are, the more of them there are. As things get more specific and are meant to override the base, they lessen to only arguably more essential things. As for my tokens, I wanted to make sure I kept not only colors consistent but also spacing and font values. Creating such tokens makes consistency an easier task and hence paves way for a more enjoyable user experience. When it comes to naming, the more specific a value/rule is, the more specific the naming gets. This is especially apparent for classes and utilities as the specific use should be easy to understand just by reading the name. Finally, browser checks were completed by making a simple HTML and trying out the CSS that I have begun (within Edge, FireFox, Chrome, and DuckDuckGo). Screen widths were additionally tested by changing the size of the browser window (400px, 912px, 1400px). Print testing was done by checking the preview prior to physically printing the page.

Focus checks also completed, all navigation (including hamburger menu) are reachable. The only possible(?) issue is that, since the menu is created using a checkbox, it can only be accessed/entered and closed using the space bar.

Do note that my current HTML structure does not match my wire frames yet as I am still figuring out the CSS architecture.

AI DISCLOSURE
The only AI used in this assignment was help fixing a bug in the hamburger menu. The menu was having trouble positioning properly, suggested fix was to revise the padding. Verified by testing it in the Edge browser and double checking the focus.

