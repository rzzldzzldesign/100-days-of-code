# 100 Days Of Code - Log

## Day 025: May 13

**💅PROGRESS:** QUARTER DONE :) Whew, got deep into the weeds of making a Mobi site work across desktop and mobile devices once it has been embedded into a users site. Some rules from the site interfere with the embedded code.

**🤔LEARNINGS:** Learning how to target specific data elements has been interesting.

Once a site is embedded the width of the outer element can be targetedusing `.code-block { width:x;}` to make sure all the content fits.

Remember about using query strings on the url for different modes:

`?live_preview` = Live Preview

`?headoffice_theme=preview` = Head Office Preview

`?ui=mobile-embed` = Mobile Embedded Version

`?ui=web-embed` = Web Embedded Version

**🌐LINK:** [STREETWISE COFFEE EMBEDDED](https://www.streetwisecoffee.co.nz/order-online)

## Day 024: May 12

**💅PROGRESS:** I'm just gonna count my work days because I'm learning heaps anyways!

**🤔LEARNINGS:** From David: Aim to avoid margins if you can as they are collapsable and therefore hard to debug. Only use in _one direction_ if you do use them. Use padding instead on the parent element. If the parent is there for layout it should control it!

Also Learned HEAPS about exporting and optimising SVGs. The more points the bigger the file of course. Use imageoptim after exporting from illustrator to further condense the code. Awesome tool for creating inline SVGs [here](https://yoksel.github.io/url-encoder/) Stroke can be changed with `stroke-width="x"` in the SVG code without the pixel `px`

**🌐LINK:** [First Project: Streetwise Coffee!](https://streetwisecoffee.mobi2go.com/)

## Day 023: May 11

**💅PROGRESS:** Started day one at Mobi2Go. Got a Saas job writing LESS oh so techno! Gonna have to on pause possibly to avaoid burn out as I'm not used to coding for 8 hours a day for a job and certanily not doing another hour after that! Fro the best thought, pace yourself and stay healthy :)

**🤔LEARNINGS:** Rest is as important as grind and hustle.

**🌐LINK:** Nah bowl.

## Day 022: May 10

**💅PROGRESS:** Added a bunch of rendered imgs to the 257 site.

**🤔LEARNINGS:** Played with fixed background images and some flexed psedo elements and negative margins to make a pretty slick and modern looking vibe :)

**🌐LINK:** [twofiveseven](https://twofiveseven.netlify.app/partners.html)

## Day 021: May 09

**💅PROGRESS:** Added content to 257 site.

**🤔LEARNINGS:** Playing with grid some more to lay out text and it looks slick af :)

**🌐LINK:** [twofiveseven](https://twofiveseven.netlify.app/partners.html)

## Day 020: May 08

**💅PROGRESS:** Only went and got a new job didn't I! Yay for Mobi2Go! Also added the partners page to 257 site.

**🤔LEARNINGS:** Used grid with auto-fit and minmax again to make a responsive grid layout. Comin in handy all the damn tmie now.

**🌐LINK:** [twofiveseven](https://twofiveseven.netlify.app/partners.html)

## Day 019: May 07

**💅PROGRESS:** Messed around with the Javascript on twofiveseven and got the calculator to load on click and unmount on close! Bloody miracle. ALSO SECRET THING HAPPENED, COULD BE A BIG DEAL :)

**🤔LEARNINGS:** Learned a little about async functions but defo kind of fluked it so need to dive deeper to get what happening!

**🌐LINK:** [twofiveseven](https://twofiveseven.netlify.app/)

## Day 018: May 06

**💅PROGRESS:** Built a #100DAYSOFCODE Visualizer site in CSS Grid to practise and make a more visual version of this log. Thought it might be a bit more interesting to look at :) Also reworked the Hens Hiatus Site and made a post about it.

**🤔LEARNINGS:** Got some more practise in with grids auto-fit function.

**🌐LINK:** [100-DAYS-VISUALIZER](https://100-days-visualizer.netlify.app/) — [HEN'S HIATUS HOT WAX](https://hens-hiatus-hot-wax.netlify.app/)

## Day 017: May 05

**💅PROGRESS:** Added a pop up modal window to the twofiveseven site. Spent a very frustrating morning trying to build the site in Gatsby only to get to the point of loading the calculator and not knowing how. Need to take it back to basics and learn it from the ground up.

**🤔LEARNINGS:** Coded a modal window from scratch in vanilla JS, so that was a first :)

**🌐LINK:** [twofiveseven](https://twofiveseven.netlify.app/)

## Day 016: May 04

**💅PROGRESS:** Totes finished [Kevin Powell](https://www.kevinpowell.co/)'s course on Conquering Reponsive Design!

**🤔LEARNINGS:** The web is inherently responsive, its only when we start adding fixed widths to things that it breaks. Mobile first is the way to go. Start at minimun size then add complexity as the viewport gets wider.

Built a full repsonsive site for my lil' brothers business, mobile first!

**🌐LINK:** [HEN'S HIATUS HOT WAX](https://hens-hiatus-hot-wax.netlify.app/)

## Day 015: May 03

**💅PROGRESS:** Finished [Wes Boss' CSS GRID COURSE](https://cssgrid.io/)! Woooop, learned so much about the fundamentals of grid and can see myself using it all the damn time now! So many use cases.

**🤔LEARNINGS:** Got the fundamentals down, now need to solidify the learnin's by building some sites with it.

**🌐LINK:** [CSS GRID DONE!](https://github.com/rzzldzzldesign/css-grid)

## Day 014: May 02

**💅PROGRESS:** Finished Challenge 22 of [Wes Boss' CSS GRID COURSE](https://cssgrid.io/) recreating Code Pens layout using grid. Also finished day 19 of Kevins responsive course building a responsive navigation menu. Taking a short day today to recover and get away from the screen for a while!

**🤔LEARNINGS:** CSS Grid is super flexible and can be used to achieve complicated layouts with ease!

**🌐LINK:** [Recreating CodePen](https://github.com/rzzldzzldesign/css-grid/commit/b35b4d65ede7ec7596b788a49a460f06baabeb8d)

## Day 013: May 01

**💅PROGRESS:** Built a 1.0 version of a site for Ashs project **twofiveseven.** Tried out using CSS Grid for the first time in the wild and it was great!

**🤔LEARNINGS:** Managed to import the [calculator tool](https://app.convertcalculator.co/to/rBWJQs6tWzqCsmnyC) from the site and style it on my own page. Overwriting the calculators own styling using very specific css classes is working pretty good for now.

Also continues with the CSS Grid course and learned the diffferent use cases for flexbox vs grid.

**🌐LINK:** [TWOFIVESEVEN](https://twofiveseven.netlify.app/)

## Day 012: April 30

**💅PROGRESS:** Rewrote the LESS code for the Viva Mexico Mobi2Go site so its a bit cleaner and uses less `!important` tags hahaaa. Layed out the Item Titles and Prices nicely using flexbox and increased some of the hierarchy on mobile.

Day 17 from Kevins course. Real short one about using the `<meta viewport=x>` tag in the head to make sure it resizes properly on mobile.

Challenge 20 from [Wes Boss' CSS GRID COURSE](https://cssgrid.io/). Making an image gallery using css grid.

**🤔LEARNINGS:** CSS GRID: grid elemenst can be overlayed over each other without using `postion: absolute` by simply setting their `grid-column/row` settngs to the same position. Super nice :)

**🌐LINK:** [VIVA! MEXICO BETTER](https://vivamexicoleftbank.mobi2go.com/) / [CSS GRID COMMIT](https://github.com/rzzldzzldesign/css-grid/commit/2ce9cfc232291dbfb5226c30c57159e665e856a5)

## Day 011: April 29

**💅PROGRESS:** Continued with Kevins course with some media query things. Then onto more #GRIDDYUP with [Wes Boss' CSS GRID COURSE](https://cssgrid.io/), did a lot today and took extensive notes on CSS Grid Fundamentals.

**🤔LEARNINGS:** CSS GRID IS AWESOME! Best thing out mate. Made a simple fully responsive grid layout using `grid-template-columns: repeat(auto-fit, minmax(300px, 1fr))` It's so cool!

[Best breakpoints](https://www.freecodecamp.org/news/the-100-correct-way-to-do-css-breakpoints-88d6a5ba1862/) for most common devices are `600px 900px 1200px` and `1800px` and up for larger screens.

**🌐LINK:** [NO MEDIA QUERY RESPONSIVE GRID](https://conquering-responsive-design.netlify.app/grid1.html)

## Day 010: April 28

**💅PROGRESS:** Started week 3 of Kevins course. I'm pretty familiar with media queries already so gonna expand my learning to [Wes Boss' CSS GRID COURSE!](https://cssgrid.io/) Been wanting to learn grid properly for a while so excited to dive into this one!

**🤔LEARNINGS:** [Firefox Developer Edition](https://www.mozilla.org/en-US/firefox/developer/) is rad! The dev tools are beautiful and their grid inspector is awesome.

Difference between EXPLICIT and IMPLICIT GRID.

EXPLICIT grid is the one defined by you the developer directly. Shown in the dev tools by a _dashed line._

IMPLICIT is any additional elements that do not fit the defined grid and flow on outside. Shown as a _dotted line._

`grid-template-row/column: Xsize;` Explicitly defines a track size.

`grid-auto-row/column: Xsize` Defines the default size for an Implicitly sized element.

By default the Columns are defined Implicitly and extra elements flow onto additional Implicit Rows.

`grid-auto-flow: row(default) / column` Defines how Implicit elements are added to the grid, similar to `flex-direction` with flexbox.

**🌐LINK:** [GIT COMMIT FOR THE COURSE LEARNIN'S](https://github.com/rzzldzzldesign/css-grid/commit/d15cca9eb4396e3823ab993b0521c5fc6be5dc99)

## Day 009: April 27

**💅PROGRESS:** Finished off custom LESS styles for the Viva Mexico Mobi2Go ordering system! Then applied for the job :)

**🤔LEARNINGS:** How to target specific classes between desktop and mobile by nesting selectors in LESS.

**🌐LINK:** [VIVA! MEXICO ONLINE](https://vivamexicoleftbank.mobi2go.com/)

## Day 008: April 26

**💅PROGRESS:** Found a really awesome job to apply for with [Mobi2Go](https://www.mobi2go.com/) so went hard on testing out the platform, setting up a store for my client Viva Mexico and expermented with custom styling using LESS.

**🤔LEARNINGS:** LESS is very similar to SASS! Mobi2Go is awesome and I want the job! Going to tweak where I got to today, tomorrow, then apply for the job! Wooop!

**🌐LINK:** [VIVA! MEXICO ONLINE](https://vivamexicoleftbank.mobi2go.com/)

## Day 007: April 25

**💅PROGRESS:** Day 12 of [Kevin Powell](https://www.kevinpowell.co/)'s course. Made another fairly simple responsive layout from scratch using flexbox.

**🤔LEARNINGS:** Centering things is easy as pie with flexbox. Reiterated what I've been learning on the course and got some good practice in.

**🌐LINK:** [Conquering Responsive Design](https://conquering-responsive-design.netlify.app/flexbox4.html) 5.0

## Day 006: April 24

**💅PROGRESS:** Day 11 and flexbox challenge 3 of [Kevin Powell](https://www.kevinpowell.co/)'s course. Added a simple navigation and used flexbox to push two sub navigations to either side of the container.

**🤔LEARNINGS:** Pretty simple addition today so nothing too new. Added some semantic HTML to the 002 page with `<main>` and `<aside>` tags to replace `<divs>` Would be good to learn all that a little better.

**🌐LINK:** [Conquering Responsive Design](https://conquering-responsive-design.netlify.app/flexbox3.html) 0.5

## Day 005: April 23—2020

**💅PROGRESS:** Break day from Kevins Course, followed along with tutorials: [FLEXBOX CONTAINERS](https://www.youtube.com/watch?v=hwbqquXww-U&list=PL4-IK0AVhVjMSb9c06AjRlTpvxL3otpUd&index=2&t=0s) AND [FLEX ITEMS](https://www.youtube.com/watch?v=4Oi5xpjoCRk&list=PL4-IK0AVhVjMSb9c06AjRlTpvxL3otpUd&index=2) AND ALSO [MIN() MAX() CLAMP()](https://www.youtube.com/watch?v=U9VF-4euyRo)

**🤔LEARNINGS:**

### FLEXBOX

#### Flex-Container

`align-items: baseline` Aligns first row of text along its baseline. Ie when you have different font-sizes on two flex items.
`align-content: (same as justify-content)` Spaces things along the cross axis if there are multiple lines of content, ie wrapping items with flex: wrap.
Default: `align-items: stretch`

#### Flex-Items

`flex-grow: X` Fill the available space of the parent container. Overwrites `flex-basis` size also. Larger the number the faster it grows in relation to other items. If set to `0` it will hold the `flex-basis` size if there is enough available space.

`flex-shrink: X` Defines the ratio of shrinking in relation to other items.

`flex-basis: X` Ideal size, ie 250px will hold this width if there is enough available space, but shrink/grow if they are defined.

Shorthand: `flex: (flex-grow) (flex-shrink) (flex-basis)` on one line.
Default: `flex: 1 1 XXpx` grow: 1 / shrink: 1 / size

`align-self: value` Overwrite the Flex Container and go where you please!

`order: X` Explicitly set an order. 0 is the default and won't move the item. Can be defined on all items to set the order.

#### Min() Max() + Clamp()

`min(x, y)` Use to set variable sizes on elements within a range of values.
IE `width: min(500px, 70%)` Whichever is the _smallest_ of the 2 values will set the width. Similar to writing `width: 70%; max-width: 500px;` but all in one line.

`max(x, y)` Similar but computes whichever value is _larger_ between the two. Can be used with three values also but gets confusing.

`clamp(x, y, z)` Takes three values: x: minimum value, y: ideal value, z: maximum value. Could be an issue when used for widths due to mobile screen sizes but experiment with for font-sizes!

**🌐LINK:** No link today as its all just taking lessons.

## Day 004: April 22—2020

**💅PROGRESS:** Built Day 009 of [Kevin Powell](https://www.kevinpowell.co/)'s course. Fun fun! Diving deeper into flexbox and how it handles images.

**🤔LEARNINGS:** Flexbox stretches images to the full max-size of the parent container. This can be fixed by wrapping them in a div or using `align-self: flex-start;` on the image to over-ride the stretching. Flex widths, as long as all childrens widths are less than 100% they can be spaced out using `justify-content: space-between` If they are all 100% (like by default) they will compete for all the available space.

**🌐LINK:** [Conquering Responsive Design](https://conquering-responsive-design.netlify.app/day009.html) 0.4

## Day 003: April 21—2020

**💅PROGRESS:** JAM-STACK = **J**AVASCRIPT **A**PIS + **M**ARKDOWN!

Signed up for [JAMStack Conf 2020!](https://jamstackconf.com/) Its my first ever developer conference and its all gonna be online, oh the irony.

Continued with Week 2 of Kevin Powells Conquering Responsive Course, bringin in flexbox, taking it back to the basics and learning it all thoroughly. Removed the slide out menu for now to simplify. Added 3 column and 2 column flex text sections, both responsive for mobile. Introducing BEM to the project.

**🤔LEARNINGS:** BEM + SCSS = AMAZING!

Learnin' about CSS COMBINATORS: IE to select an adjacent sibling with the same class:
`.flexbox__text + .flexbox__text {}`

**🌐LINK:** [Conquering Responsive Design](https://conquering-responsive-design.netlify.app/) 0.3

## Day 002: April 20—2020

**💅PROGRESS:** Got [Kevin Powell](https://www.kevinpowell.co/)'s solution to the responsive challange from day 0. Rewrote some of my Conquering Responsive site to work a bit better. Then went on and added a CSS only animated slide out menu on a [tutorial from fireship.io](https://www.youtube.com/watch?v=biOMz4puGt8&t=206s)

**🤔LEARNINGS:** Slide out menu can be made from pure CSS! No JS needed. Fixing menu to bottom of the screen on mobile is good for usablity. [Font-awesome](https://fontawesome.com/icons?d=gallery) has a whole bunch of SVG icons now.

**🌐LINK:** [Conquering Responsive Design](https://web.archive.org/web/20200420223551/https://conquering-responsive-design.netlify.app/) 0.2

## Day 001: April 19—2020

**💅PROGRESS:** Day 1 feeling super tired today so no huge progress. Did an hour and a half of Javascript practise including Module 8: Data Types: Objects + Objects References Vs Values from Wes Bos's Beginner Javascript course. Also continued with FreeCodeCamps Basic Javascript course.

**🤔LEARNINGS:** Changing values of properties within an object mutates the original object which can cause bugs. When modifying objects make sure to create a copy of the original using the `...` spread operator.

**🌐LINK:** No link today as its all just taking lessons.

## Day 0: April 18—2020

**💅PROGRESS:** DAY 0 BABY! Worked on a lesson (Day 5) from [Kevin Powell](https://www.kevinpowell.co/)'s course about Conquering Responsive Design.

**🤔LEARNINGS:** The web is inherently responsive! Learned about implementing variable fonts for the first time:

> This dynamic typography uses continuous ranges of styles, offering all the weights between 100 and 900 on a page, and responsively varying the weight based on some conditions.
> To request a range of a variable font axis, join the 2 values with `..` >[LINK](https://developers.google.com/fonts/docs/css2#axis_ranges)

Experimented with a fun animated hover state on the button. Also set up this git repo and learning how to write markdown!

**🌐LINK:** [Conquering Responsive Design](https://github.com/rzzldzzldesign/conquering-responsive-design/commit/d52e3b2597a4e50571a3b96a4585da91509e32c1) 0.1
