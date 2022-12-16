ohmyfood
_

ohmyfood is the 4th class project from the OpenClassrooms "Intégrateur Web" course.

It is a mobile-first oriented site where users can select restaurants close to them then pick a menu and have it prepared before they arrive at the restaurant to shorten the waiting and ordering time.

The site can stretched to be more usable on a desktop computer.

The goal was to implement animations on elements and a loader-example for the landing page.

finished 2022/12/13

coded with:
    - html
    - css + scss pre-processor

_

_Validator HTML_

landing-page
    index.html: 3 warning linked to heading h2-h6 not present in section/article

pages restaurants
    - restaurant_a-la-francaise.html: 3 warning linked to heading h2-h6 not present in section/article
    - restaurant_la-note.html: 3 warning linked to heading h2-h6 not present in section/article
    - restaurant_la-palette.html: 3 warning linked to heading h2-h6 not present in section/article
    - restaurant_le-delice.html: 3 warning linked to heading h2-h6 not present in section/article

_

_Validateur CSS_

2 errors linked to the property "clip-path" which is not recognised as valid by the W3C though it does not have any negative impact on the code itself. It is (as of today) the only way to crop content with complex-shapes via the SVG path capabilities.