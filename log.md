# 100 Days Of Code - Log

## Day 004: April 22—2020

**💅PROGRESS:** Built Day 009 of [Kevin Powell](https://www.kevinpowell.co/)'s course. Fun fun! Diving deeper into flexbox and how it handles images.

**🤔LEARNINGS:** Flexbox stretches images to the full max-size of the parent container. This can be fixed by wrapping them in a div or using `align-self: flex-start;` on the image to over-ride the stretching. Flex widths, as long as all childrens widths are less than 100% they can be spaced out using `justify-content: space-between` If they are all 100% (like by default) they will compete for all the available space.

**🌐LINK:** [Conquering Responsive Design](https://conquering-responsive-design.netlify.app/day009.html) 4.0

## Day 003: April 21—2020

**💅PROGRESS:** JAM-STACK = **J**AVASCRIPT **A**PIS + **M**ARKDOWN!

Signed up for [JAMStack Conf 2020!](https://jamstackconf.com/) Its my first ever developer conference and its all gonna be online, oh the irony.

Continued with Week 2 of Kevin Powells Conquering Responsive Course, bringin in flexbox, taking it back to the basics and learning it all thoroughly. Removed the slide out menu for now to simplify. Added 3 column and 2 column flex text sections, both responsive for mobile. Introducing BEM to the project.

**🤔LEARNINGS:** BEM + SCSS = AMAZING!

Learnin' about CSS COMBINATORS: IE to select an adjacent sibling with the same class:
`.flexbox__text + .flexbox__text {}`

**🌐LINK:** [Conquering Responsive Design](https://conquering-responsive-design.netlify.app/) 3.0

## Day 002: April 20—2020

**💅PROGRESS:** Got [Kevin Powell](https://www.kevinpowell.co/)'s solution to the responsive challange from day 0. Rewrote some of my Conquering Responsive site to work a bit better. Then went on and added a CSS only animated slide out menu on a [tutorial from fireship.io](https://www.youtube.com/watch?v=biOMz4puGt8&t=206s)

**🤔LEARNINGS:** Slide out menu can be made from pure CSS! No JS needed. Fixing menu to bottom of the screen on mobile is good for usablity. [Font-awesome](https://fontawesome.com/icons?d=gallery) has a whole bunch of SVG icons now.

**🌐LINK:** [Conquering Responsive Design](https://web.archive.org/web/20200420223551/https://conquering-responsive-design.netlify.app/) 2.0

## Day 001: April 19—2020

**💅PROGRESS:** Day 1 feeling super tired today so no huge progress. Did an hour and a half of Javascript practise including Module 8: Data Types: Objects + Objects References Vs Values from Wes Bos's Beginner Javascript course. Also continued with FreeCodeCamps Basic Javascript course.

**🤔LEARNINGS:** Changing values of properties within an object mutates the original object which can cause bugs. When modifying objects make sure to create a copy of the original using the `...` spread operator.

**🌐LINK:** No link today as its all just taking lessons.

## Day 0: April 18—2020

**💅PROGRESS:** DAY 0 BABY! Worked on a lesson (Day 5) from [Kevin Powell](https://www.kevinpowell.co/)'s course about Conquering Responsive Design.

**🤔LEARNINGS:** The web is inherently responsive! Learned about implementing variable fonts for the first time:

>This dynamic typography uses continuous ranges of styles, offering all the weights between 100 and 900 on a page, and responsively varying the weight based on some conditions.
>To request a range of a variable font axis, join the 2 values with `..`
>[LINK](https://developers.google.com/fonts/docs/css2#axis_ranges)

Experimented with a fun animated hover state on the button. Also set up this git repo and learning how to write markdown!

**🌐LINK:** [Conquering Responsive Design](https://github.com/rzzldzzldesign/conquering-responsive-design/commit/d52e3b2597a4e50571a3b96a4585da91509e32c1) 1.0
