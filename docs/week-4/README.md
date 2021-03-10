# Week 4: CSS

### Lecture

Welcome to CSS! Now we can finally begin to make our HTML look like something! So let's get styling!\
Here's a [good reference (ok, cheat sheet)](https://adam-marsden.co.uk/css-cheat-sheet) for CSS that will link to Mozilla's Web Documentation on CSS specifics. Keep it handy!

#### CSS
[Download Intro-CSS Lecture](https://onetimeuser.github.io/intro-web-comp-principles/week-4/4.pdf)\
[Link to CSS Intro](https://nyu.zoom.us/rec/play/0H1DtEkk5ZXPiEhkhvGmpxRZ_LB55Nvq7n6F58pv3d_Ue3FuVQBMxLl5A_pp_832QtoAQ8c0k3Qvz9sx.JYLTmFMYRpD2SNQb)\
[Link to CSS Coding Video](https://nyu.zoom.us/rec/play/LCtZSyu0UYdyAH9xDXQ77oYnyqAvVgDf88F8ViV3mjzG_PqnypfOnQgSEDJDJVBOgFEmImDTJ7yJ_A0T.plBCRzqusZOrwFRE)

- We talked a bit about CSS and it's history. Check the slides for more on that.
- We also outlined the 3 ways we include styles in our html: inline, internal and external (preferred). 
- There are three components of a style rule: selector, declaration block, and property/value pairs.\
Simple Example:
```
h1{
  color:red;
}
```
- Cascading is namesake feature of CSS. Styles cascade or trickle down to elements in a number of ways based on importance and specificity.\
**IMPORTANCE**: by using the `!important` block\
**SPECIFICITY**: means the more specific the selector the higher priority: inline style > id > class > element\
**LAST ONE IN**: if all things being equal and there is a duplicate style, the one further down the style sheet is the one that is used.
- Some styles are inherited (e.g. font styles) and most are not (margins, padding, etc.)
- **Understand the CSS box model**:
![Box Model](boxmodel.png "Box Model")
- Margins and Paddings and Borders are written interestingly (ex. `margin:10px 0 10px 9px`). Make note of this is the videos and in the project folder.
- Absolute (`px`) and Relative (`em, %, vw, vh`)units of measurement are the means to add dimensions to your elements.
- `id` and `class` attributes allow us to lend identification markers to elements so we can select them easily in the CSS. What's the difference?
- There are 6 ways to define color: RGB (`rgb(255,0,0)`), RGBA (`rgba(255,0,0,.5)`), HEXADECIMAL (`#00FFFF`), COLOR NAMES (`red`), HSL (`hsl(270,15%,15%)`), HSLA (`hsl(270,15%,15%,.5)`). It's beneficial to know what each means.
- Here are some extras!\
A basic gradient linearly positioned (top to bottom)
```
.simple-linear {
  background: linear-gradient(blue, pink);
}
```
Gradient that moves from left to right
```
.horizontal-gradient {
  background: linear-gradient(to right, blue, pink);
}
```
Diagonal gradient
```
.diagonal-gradient {
  background: linear-gradient(to bottom right, blue, pink);
}
```
You can also use angles
```
.angled-gradient {
  background: linear-gradient(70deg, rgb(0,0,255), rgb(255,0,127));
}
```
More than two colors:
```
.auto-spaced-linear {
  background: linear-gradient(red, yellow, blue, orange);
}
```
Radial
```
.simple-radial {
  background: radial-gradient(red, blue);
}
```
- Background images are different from normal images we use with the `<img />`tag. Background images react differently to the amount of space you have made for them. This will make more sense when coded up and played with. At it's simplese it looks something like:\
```
body{
  background: url("assets/image.png")
}
```
A more complete example looks something like this (with added `/* comments */`):
```
body {
  background:
     url("sweettexture.jpg")  /* image ex background-image*/
     top center / 200px 200px /* position / size */
     no-repeat                /* repeat ex. does it repeat on x or y or both*/
     fixed                    /* attachment */
     padding-box              /* origin */
     content-box              /* clip */
     red;                     /* color */
}
```
Check your book or online for a complete listing of all the available values. Background images can be tricky but they are used quite often in modern web development.\
If you are looking for a full screen image background that is well positioned at all times:
```
html {
  background: url("images/bg.jpg") no-repeat center center fixed;
  background-size: cover;
}
```
**Want more recipes? Go [HERE](https://cims.nyu.edu/~aston/backgrounds/)**
- Link (anchor) element styles and states (`a:visited`, `a:hover`). There are others as well but those are the most used and addressed.
- Fonts can be added in a few different ways:\
Changing the font in CSS (this relies on users to have the font already)
```
h1{
   font-family: Helvetic,Arial, sans-serif;
 }
```
Using a service like Google Fonts (instructions are well said while you are browing Google fonts but looks something like below)\
This goes in the `<head>`
```
<link href="https://fonts.googleapis.com/css?family=Roboto" rel="stylesheet">
```
And this goes in the css
```
h1{
   font-family: 'Roboto', sans-serif;
 }
```
You can also use [@font-face](https://developer.mozilla.org/en-US/docs/Web/CSS/@font-face) to load in custom fonts, but you will need to process fonts to make sure you have the necessary formats.


[Right Click and 'Save File As' to download zip file](https://onetimeuser.github.io/intro-web-comp-principles/week-4/Week4.zip)

- READ Learning Web Design\
    Chapter 13: Colors and Backgrounds\
    Chapter 14: Thinking Inside the Box\
    Chapter 15: Floating and Positioning

### Synchronous Zoom
[Link to CSS Coding Video](https://nyu.zoom.us/rec/play/l-CViSzdELi1kkDvwmAUWfB-47m57ia5pHP_xYucVUhsk5KneU121CbHwPr2yX7mk-kieh3eh2QpyiTJ.Mkk-vq11hv-8apoR)\
[Project Files: Right Click and 'Save File As' to download zip file](https://onetimeuser.github.io/intro-web-comp-principles/week-4/Week-4-synchro-files.zip)


### Assignment
- [ASSIGNMENT 3 - Due March 8](/assignments/assignment-3/)
