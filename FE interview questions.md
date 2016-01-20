in progress...
* TODO
- https://developer.mozilla.org/en-US/docs/Web/HTML
- https://developer.mozilla.org/en/docs/Web/CSS/Specificity
- https://css-tricks.com/search-results/?q=Difference+Between+
- http://css3files.com/2015/10/23/15-common-css-interviews-questions-and-answers/
- http://www.codeproject.com/Articles/702051/important-HTML-Interview-questions-with-answe
- http://webdesign.about.com/od/webdesignhtmlatoz/a/frequently-asked-questions-about-web-design-html-css-and-web-development.htm
- http://webdesign.about.com/od/css/a/aa011606.htm
- http://ipestov.com/22-essential-css-recipes/
- http://www.skilledup.com/articles/html-html5-interview-questions-answers
- https://www.smashingmagazine.com/2013/01/preparing-front-end-job-interview/
- http://learntocodewith.me/web-dev/front-end-developer-skills/
- https://www.quora.com/What-should-a-modern-front-end-developer-know-in-2015
- https://css-tricks.com/front-end-development-is-development/
- https://gist.github.com/jedfoster/4596858
- https://github.com/TIY-Austin-Front-End-Engineering/css-specificity
- https://github.com/h5bp/Front-end-Developer-Interview-Questions/tree/master/Translations/Serbian
- http://rmurphey.com/blog/2012/04/12/a-baseline-for-front-end-developers
- https://github.com/andyshora/front-end-interview-questions
- https://github.com/khan4019/front-end-Interview-Questions
- http://www.impressivewebs.com/css-terms-definitions/
- http://nimbupani.com/css-vocabulary.html
- http://skillcrush.com/2015/03/26/99-tech-terms/
- https://www.smashingmagazine.com/2007/07/css-specificity-things-you-should-know/
- https://www.themuse.com/advice/10-tech-terms-youve-definitely-heard-but-probably-dont-know-the-meaning-of
- http://code.tutsplus.com/tutorials/the-30-css-selectors-you-must-memorize--net-16048
- https://developer.mozilla.org/en-US/docs/Web/CSS/Common_CSS_Questions

CSS

* What is CSS?
    - CSS stands for Cascading Style Sheet.

* How can you integrate/import CSS on a web page?
    - Inline 
        ```html <p style="color:blue">Hello CSS</p>```
    - Internal 
        ```html <style> p{color:blue}  </style>```
    - External
        ```html <link rel="stylesheet" type="text/css" href="style.css"```

1. What are the pros and cons of using absolute positioning?
2. What is the difference between display: inline; and display: inline-block;?
3. What is box model?
4. Where to define styles?
5. List CSS selectors and their priorities
6. The difference between block element, inline-block element and inline element
7. Talk about position property, and its values
8. How to hide an element?
9. What is float element?
10. What is pseudo element? what is pseudo class?
11. How to center align a paragraph?
12. How to center align a div inside another div?
13. How to make a two column Web page? a three column Web page?
14. How to draw a triangle? a circle? a colored square?
15. How to make a tab view?
16. How do you define multiple background images through CSS?
17. What is the purpose of the box-sizing property? What are it's possible values?
18. Provide an example of content-box vs border-box box-sizing
19. What is the difference between RGBa and HSLa? When would you use one vs the other?
20. Šta je css pre processor
21. Šta je pseudo klasa, a sta pseudo element?
22. Kako se horizontalno i vertikalno centrira (block i inline) element?
23. Koji formati slika se koriste na webu (i njihove osobine i namena)?
24. Koje vrednosti postoje, i koji je default, za position / display / overflow?
25. Sta je selector specificity (tj. selector importance) i kako radi?
26. Kako unaprediti brzinu sajta na front-end-u? Kako testirati performanse? (Navesti neki alat za FE performance testing.)
27. Sta je novo doneo CSS3, a sta HTML5? Navesti sto vise novih stvari.
28. Kako funkcionise absolute/relative/fixed/static pozicioniranje? (Kako se ponasa absolute element ako se nadje unutar fixed, relative, ili absolute elementa?)
29. Koje tehnike postoje za clearing floats? (Kako radi .clearfix?)
30. Koji se od nabrojanih CSS preperties-a nasledjuju?
    - position
    - font-size
    - color
    - background-color
31. Koje vrednosti mogu da se upotrebe za width? (Navesti sto vise CSS units.)
32. Navesti sto vise CSS background properties.
33. Cemu sluzi flexbox / transforms / transitions / animations?
34. Cemu sluzi * { box-sizing: border-box; }? Koje su prednosti?
35. Koje CSS pre-procesore, biblioteke, i alate koristis?
36. Da li koristis Git, GitHub?
37. Koje sajtove, blogove, reference citas i koristis?
38. Koja je razlika izmedju inline i inline-block?
39. Sta je accessibility / usability / SEO / UI / UX / typography / semantic code / web standards?
40. Za koje browsere i uredjaje se obicno radi testiranje? Koji su najzastupljeniji?
41. Sta znaci validan HTML i CSS? (Ko odredjuje kriterijume i standarde?)
42. Sta znaci mobile-first?
43. Sta selektuje ul[class] > li:nth-child(2n+1)
44. Sta je progressive enhancement, graceful degradation
45. Šta je sve neophodno uraditi da bi site bio responsive, a zatim i da bi podržavao što više starijih browsera (npr. IE8+)
46. Šta je feature detection (vs browser detection)?
47. What is the difference between classes and ID's in CSS?
48. What's the difference between "resetting" and "normalizing" CSS? Which would you choose, and why?
49. Describe Floats and how they work.
50. Describe z-index and how stacking context is formed.
51. Describe BFC(Block Formatting Context) and how it works.
52. What are the various clearing techniques and which is appropriate for what context?
53. Explain CSS sprites, and how you would implement them on a page or site.
54. What are your favourite image replacement techniques and which do you use when?
55. How would you approach fixing browser-specific styling issues?
56. How do you serve your pages for feature-constrained browsers?
57. What techniques/processes do you use?
58. What are the different ways to visually hide content (and make it available only for screen readers)?
59. Have you ever used a grid system, and if so, what do you prefer?
60. Have you used or implemented media queries or mobile specific layouts/CSS?
61. Are you familiar with styling SVG?
62. How do you optimize your webpages for print?
63. What are some of the "gotchas" for writing efficient CSS
64. What are the advantages/disadvantages of using CSS preprocessors?
65. Describe what you like and dislike about the CSS preprocessors you have used.
66. How would you implement a web design comp that uses non-standard fonts?
67. Explain how a browser determines what elements match a CSS selector.
68. Describe pseudo-elements and discuss what they are used for.
69. Explain your understanding of the box model and how you would tell the browser in CSS to render your layout in different box models.
70. What does * { box-sizing: border-box; } do? What are its advantages?
71. List as many values for the display property that you can remember.
72. What's the difference between inline and inline-block?
73. What's the difference between a relative, fixed, absolute and statically positioned element?
74. The 'C' in CSS stands for Cascading. How is priority determined in assigning styles (a few examples)? How can you use this system to your advantage?
75. What existing CSS frameworks have you used locally, or in production? How would you change/improve them?
76. Have you played around with the new CSS Flexbox or Grid specs?
77. How is responsive design different from adaptive design?
78. Have you ever worked with retina graphics? If so, when and what techniques did you use?
79. Is there any reason you'd want to use translate() instead of absolute positioning, or vice-versa? And why?
80. What, if any preprocessor do you use? (Sass, LESS, Stylus)
81. Do you subscribe to any particular CSS structure? (SMACSS, OOCSS)
82. Sass mixins?
83. What is browser Compatibility?
84. What is At-Rule

    - An at-rule is an instruction given in a CSS document using the @ character. An at-rule could have a declaration block or a simple string of text. The example below has two different at-rules:
```html
@import url(secondary.css);

@media print {
  #container {
    width: 500px;
  }
}
```
    - The at-rule is not just the “@media” or “@import” part at the beginning; the entire instruction comprises the complete at-rule.

84. What is Combinator selector

    - A combinator is the character in a selector that connects two selectors together. There are four types of combinators. These four combinators help create descendant selectors (with a space character), child selectors (with the “>” character), adjacent sibling selectors (with the “+” character), and general sibling selectors (with the “~” character). To dispel any confusion, here are those four combinators in use:
```html
/* In all 4 examples */
/* whatever appears between "div" and "p" is a combinator */
/* in the first example, the combinator is a space character */
div p {
  color: #222;
}

div>p {
  color: #333;
}

div+p {
  color: #444;
}

div~p {
  color: #555;
}
```
85. What is Rule Set?
    - A rule set is a single section of CSS including the selector, the curly braces, and the different lines with properties and values. The code in the example below comprises one rule set:

```html
/* the rule set starts with the line below */
body {
  font-family: Arial, sans-serif;
  color: #555;
  font-size: 14px;
}
/* ends with the closing curly brace above */
```
86. What is Declaration Block

    - A declaration block is the section of CSS where the property/value pairs appear. In the example below, everything found between the curly braces (not including the comments) is a declaration block:
```html
body {
  font-family: Arial, sans-serif; /* starts with this line */
  color: #555;
  font-size: 14px;
  line-height: 20px; /* ends here, before the closing curly brace */
}
```
87. What is Universal Selector

    - The universal selector matches any element within the context in which it’s placed in a selector. In the example below, the * character is the universal selector:
```html
/* the asterisk character is the universal selector */
.navigation ul * {
  width: 100px;
  float: left;
}
```

    - So, any element that appears as a child descendant of the unordered list element inside an element that has a class of “navigation” will receive the declared styles.

    - Universal selectors are generally discouraged for performance reasons.



HTML

1. What does a doctype do?
2. What's the difference between standards mode and quirks mode?
3. What's the difference between HTML and XHTML?
4. Are there any problems with serving pages as application/xhtml+xml?
5. How do you serve a page with content in multiple languages?
6. What kind of things must you be wary of when design or developing for multilingual sites?
7. What are data- attributes good for?
8. Consider HTML5 as an open web platform. What are the building blocks of HTML5?
9. Describe the difference between a cookie, sessionStorage and localStorage.
10. Describe the difference between <script>, <script async> and <script defer>.
11. Why is it generally a good idea to position CSS <link>s between <head></head> and JS <script>s just before </body>? Do you know any exceptions?
12. What is progressive rendering?
13. Have you used different HTML templating languages before?
