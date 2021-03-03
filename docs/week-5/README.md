# Week 5: CSS

### Lecture

We continue on with CSS tackling the painful part of CSS, manual positioning.

#### Table Styles and Selectors

[Link to Tables and Selectors Intro](https://nyu.zoom.us/rec/play/vgSYZJIWOGv8uzotxXuPw_shpAUAZUBJ7utj3RLsOkptLPAHGB8QuHSc3llPtsIK389aD1NajnXntqcA.eXmz9MK5Zvm3OR84)

I showed some simple table styling and pseudo selectors like `p:first-child` and `li:nth-child` which essentially offer greater granularity in selecting individual elements within their siblings. This is handy in lists or a matrix of images for example.

Check out this nth-child tester [HERE](css-tricks.com/examples/nth-child-tester) and check out a larger list of helpful structural pseudo-classes [HERE](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-classes#tree-structural_pseudo-classes).

Also, please look at [Combinators](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Selectors/Combinators). Combinators will also be very useful in pulling out specific elements that you want to style. For example, a '_' space means 'descendant' (more general than a 'child'), remember? There are plenty more: `>` direct child is probably the most important.

#### Layout

[Layout Project files](https://onetimeuser.github.io/intro-web-comp-principles/week-5/positioning.zip)

Open the above file and drag the html file to your browser. You should see a Positioning page with a lot of text and descriptions. Go ahead and open your developer console so you can read along and inspect the elements/css and change alter on the fly to see what the page looks like when you change certain properties and values.

Take your time understanding this.

We started off talking about the `display` property. I've showed you some of this already and talked about the values `inline` and `block`. Other values to note: `inline-block` and `none`. `display: none;` should be differentiated from `visibility:hidden`.

Floating elements is also another method to position. You can `float` to the `left` or `right` of objects, and use the `clear` property to stop the floating.

Finally, we talk about `position` property which is used quite a lot, and each value has it's own special case, `relative` `absolute` `fixed` `sticky`.


- READ Learning Web Design\
    Chapter 15: Floating and Positioning


### Synchronous Zoom

[Link to Sync Zoom](https://nyu.zoom.us/rec/play/rt8I1uFJ7HztJss-Ge4hs-5UwtEr2Xh6JtJD4DNDTQ6AFBcfGeNBTJ1__FoLmVl17qiU7nZeda-cEQmO.b71ZxO4TAhvUePN6)

[Sync Project files](https://onetimeuser.github.io/intro-web-comp-principles/week-5/sync-positioning.zip)

[Live link to Positioning Page](https://cims.nyu.edu/~aston/positioning/positioning-index.html)
