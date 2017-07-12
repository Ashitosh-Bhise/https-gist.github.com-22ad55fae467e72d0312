### CSS
---
* What is CSS?
    - CSS stands for Cascading Style Sheet.
    - Styles define how to display HTML elements
    - Styles were added to HTML 4.0 to solve a problem
    - External Style Sheets can save a lot of work
    - External Style Sheets are stored in CSS files


* Where to define styles? How can you integrate/import CSS on a web page?
    - Inline, used to style only a small piece of code
        ```
            <p style="color:blue">
                Hello CSS
            </p>
        ```
    - Internal/Embedded, style sheets are put between the <head>...</head>
        ```
            <style> 
                p{color:blue}
            </style>
        ```
    - External
        ```
            <link rel="stylesheet" type="text/css" href="style.css"
        ```

* What is Property?
    - The style that you are applying to a selector, e.g. border.         

        
* What is Selector? 
    The way you declare which elements the styles should apply to. There are different kinds of selectors:

        - Class: The most commonly used selector. E.g. “.cloudy” to select an element with classname cloudy. 
            There can be more than 1 element with the same classname.
        
        - ID: Use this sparingly. You cannot reuse an ID within the same page and used only to identify an element uniquely. E.g. <div id=lovelyweather></div>
        
        - Attribute Selector: If you use any attribute other than class or id to identify an element in a stylesheet, you would be using Attribute Selectors. You can also do basic pattern matching within an attribute selector (so if you would like to do basic pattern matching for selectors using class or ID attributes, you would want to use attribute selectors).
        
        - Pseudo-Classes: Classes that are applied to elements based on information that is not present in the markup, e.g. :first-child or :last-child. Do note that the selectors are parsed from right to left (see the demo). You cannot use section article:first-child to select the first occurrence of article, if the first child of section is h1 and not article. Likewise with the :nth-child, and :last-child pseudo-classes.
        
        - Pseudo-Elements Pseudo-elements differ from Pseudo-Classes in that they actually create an element in the document tree. This is almost the first instance of CSS modifying the HTML document tree. You should ideally use pseudo-elements with “::” instead of “:” (but most browsers accept “:” notation for CSS 2.1 pseudo-elements). Pseudo-elements are: ::first-line, ::first-letter, ::before, ::after (See the demo for how pseudo-elements work).
        

* What are Combinators?
    - The selection of an element based on its occurrence in relation to another element (chosen by the choice of combinator: whitespace, >, +, or ~). You can have:


    * Descendant Combinator
        - This is the most common usage, e.g. #lovelyweather h1.
    
    
    * Child Combinator
        - Select an element if it is a direct child of another element (and not a grandchild of that element).
    
    
    * Adjacent Sibling Combinator
        - The element that is immediately adjacent to another element.


    * General Sibling Combinator
        - The element that is adjacent, but not immediately to another element.
        

* Why background and color are the separate properties if they should always be set together?
    - Color is an inherited property while background is not. So this can make confusion further.


* What is the difference between class selectors and id selectors?
    - An overall block is given to class selector while id selectors take only a single element differing from other element
  
    
* When working on a large codebase CSS it can quickly become unwieldly and difficult to maintain. How do you approach this problem? How do you architect your CSS (and have you heard/used BEM, OOCS or SMACSS)?    
    
    
* How do you organize CSS files?

    
* What are the advantages of External Style Sheets?
    - You can create classes for reusing it in many documents.
    - By using it, you can control the styles of multiple documents from one file.
    - In complex situations, you can use selectors and grouping methods to apply styles.


* What is RWD (Responsive web design) ?
    - Responsive Web Design. This technique is used to display the designed page perfectly on every screen size and device. For example: Mobile, Tablet, desktop, laptop etc. You don't need to create a different page for each device. 
    

* Explain CSS sprites, and how you would implement them on a page or site. How do you go about creating them? What are possible alternatives to sprites?    
    
    
* What are the benefits of CSS sprites?
    - If a web page has large no. of images that takes a longer time to load because each image separately sends out an http request. The concept of CSS sprites is used to reduce the loading time for a web page because it combines the various small images into one image. It reduces the number of http requests and hence the loading time. 
    
    
* What is the CSS Box model and what are its elements?
    - The CSS box model is used to define the design and layout of elements of CSS.
    - The elements are:
        - Margin
        - Border
        - Padding
        - Content
   
        
* What is the float property and what float do.
    - The CSS float property is used to move the image to the right or left along with the texts to be wrapped around it. It doesn't change the property of the elements used before it
  
    
* What is tweening?

    - It is the process of generating intermediate frames between two images.

    - It gives the impression that the first image has smoothly evolved into the second one.

    - It is an important method used in all types of animations.

    - In CSS3, Transforms (matrix, translate, rotate, scale etc.) module can be used to achieve tweening.


* What do you understand by W3C
    - W3C stands for World Wide Web Consortium.


* Explain the difference between "visibility: hidden;" and "display: none;"? What are the pros and cons of using “display:none”?

    - visibility: hidden simply hides the element but it will occupy space and affect the layout of the document.

    - display: none also hides the element but will not occupy space. It will not affect the layout of the document.
    


* Describe z-index and how stacking context is formed.
    - An element with greater stack order is always in front of an element with a lower stack order. z-index only works on positioned elements. 
    The default stack order of non-positioned elements is their order in the document.
    

* What is the purpose of the z-index and how is it used?

    - The z-index helps specify the stack order of positioned elements that may overlap one another. 
    The z-index default value is zero, and can take on either a positive or negative number.

    - An element with a higher z-index is always stacked above than a lower index.

    - Z-Index can take the following values:

        - Auto: Sets the stack order equal to its parents.
        - Number: Orders the stack order.
        - Initial: Sets this property to its default value (0).
        - Inherit: Inherits this property from its parent element.
    

* How does z-index relate to positioning
    - The z-index property specifies the stack order of elements.
    An element with a higher z-index/stack order is always rendered in front of an element with a lower z-index/stack order on the screen. 
    Z-index will only work on elements that have a specified position (position:absolute, position:relative, or position:fixed).


* What existing CSS frameworks have you used locally, or in production? How would you change/improve them?


* What are CSS frameworks? What CSS frameworks have you used
    - It is a pre-planned libraries, which allows easier and more standards-compliant webpage styling, using CSS language.
        
        
* Who maintains the CSS specifications?
    - W3C (World Wide Web Consortium) maintains the CSS specifications.        
    
    
* How works absolute/relative/fixed/static position? 
    - https://css-tricks.com/absolute-relative-fixed-positioining-how-do-they-differ/


* How is behave absolute element if it is inside fixed element/relative/absolute element
    

* What's the difference between a relative, fixed, absolute and statically positioned element?
    
    - Static - default for every single page element. The only reason you would ever set an element to position: static is to forcefully-remove some positioning that got applied to an element outside of your control.
    
    - Relative - means "relative to itself". Setting position: relative; on an element and no other positioning attributes, it will no effect on it's positioning. It allows the use of z-index on the element and it limits the scope of absolutely positioned child elements. Any child element will be absolutely positioned within that block.
    
    - Absolute - positions the element exactly where you want it rrelative to the next parent element with relative (or absolute) positioning. If there is no such parent, it will default all the way back up to the <html> element.
    
    - Fixed - positioned relative to the viewport, or the browser window itself. regardless of scroll position.



* What are the pros and cons of using absolute positioning?


* The difference between block / inline / inline-block element
    
    - Elements with display: inline-block are like display: inline elements, but they can have a width and a height. 
    That means that you can use an inline-block element as a block while flowing it within text or other elements.
    
    - Block elements:
        respect all of those
        force a line break after the block element
        
    - Inline elements:
        respect left & right margins and padding, but not top & bottom
        cannot have a width and height set
        allow other elements to sit to their left and right.
        
    - Inline-block elements:
        allow other elements to sit to their left and right
        respect top & bottom margins and padding
        respect height and width



* List CSS selectors and their priorities
    - https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Selectors


* Talk about position property, and its values


* What are counters in CSS3 ?


* How to hide an element?


* Are CSS rule names case sensitive?


* Does margin-top or margin-bottom has effect on inline element?


* Does padding-top or padding-bottom has effect on inline element?


* Which one would you prefer among px, em % or pt and why?


* Does padding-left or padding-right or margin-left or margin-right has effect on inline element?


* If you have a <p> element with font-size: 10rem, will the text be responsive when the user resizes / drags the browser window?


* Describe pseudo-elements and discuss what they are used for.
    - https://developer.mozilla.org/en-US/docs/Web/CSS/pseudo-elements

    - A CSS pseudo-element is used to style specified parts of an element.

    For example, it can be used to:
    
        Style the first letter, or line, of an element
        Insert content before, or after, the content of an element
    
```css
p::first-line {
    color: #ff0000;
    font-variant: small-caps;
}
```


* What is pseudo element? what is pseudo class?


* How to center align a paragraph?


* How to center align a div inside another div?


* How to make a two column Web page? a three column Web page?


* How to draw a triangle? a circle? a colored square?


* How to make a tab view?


* How do you define multiple background images through CSS?


* Explain the CSS “box model” and the layout components that it consists of. Provide some usage examples.
    - The CSS box model is a rectangular layout paradigm for HTML elements that consists of the following:

    Content - The content of the box, where text and images appear
    
    
    Padding - A transparent area surrounding the content (i.e., the amount of space between the border and the content)
    
    Border - A border surrounding the padding (if any) and content
    
    Margin - A transparent area surrounding the border (i.e., the amount of space between the border and any neighboring elements)

    ```css
    /*       top   right  bottom left  */
    padding: 25px  50px   75px   100px;
    
    /* same padding on all 4 sides: */
    padding: 25px;
    
    /* top/bottom padding 25px; right/left padding 50px */
    padding: 25px 50px;
    
    /* top padding 25px; right/left padding 50px; bottom padding 75px */
    padding: 25px 50px 75px;
    ```
    
* Explain what elements will match each of the following CSS selectors:
    div, p - Selects all <div> elements and all <p> elements
    div p - Selects all <p> elements that are anywhere inside a <div> element
    div > p - Selects all <p> elements where the immediate parent is a <div> element
    div + p - Selects all <p> elements that are placed immediately after a <div> element
    div ~ p - Selects all <p> elements that are anywhere preceded by a <div> element


* Explain the meaning of each of these CSS units for expressing length:

    cm - centimeters
    em - elements (i.e., relative to the font-size of the element; e.g., 2 em means 2 times the current font size)
    in - inches
    mm - millimeters
    pc - picas (1 pc = 12 pt = 1/6th of an inch)
    pt - points (1 pt = 1/72nd of an inch)
    px - pixels (1 px = 1/96th of an inch)


* Which values (units) could be used for width?


* In CSS3, how would you select:

    Every <a> element whose href attribute value begins with “https”.
        a[href^="https"]
        
    Every <a> element whose href attribute value ends with “.pdf”.
        a[href$=".pdf"]
        
    Every <a> element whose href attribute value contains the substring “css”.
        a[href*="css"]



* What is the purpose of the box-sizing property? What are it's possible values?


* Provide an example of content-box vs border-box box-sizing


* What is * { box-sizing: border-box; }? What are advantages?


* What is the difference between RGBa and HSLa? When would you use one vs the other?


* What libraries and tools you are using?


* What preprocessors you are using?


* What are the reasons to use preprocessor


* What is CSS preprocessor


* What are the advantages/disadvantages of using CSS preprocessors?


* What preprocessor do you use? (Sass, LESS, Stylus) Why do people use them? How does something like Compass relate to Sass?
    - They are CSS preprocessors. They are a special syntax/language that compile down into CSS.
     They make managing CSS easier, with things like variables and mixins to handle vendor prefixes (among other things). 
     They make doing best practices easier, like concatenating and compressing CSS.


* Describe what you like and dislike about the CSS preprocessors you have used.


* What's the difference between "resetting" and "normalizing" CSS? Which would you choose, and why?
    - resetting will remove all the default styling applied by the browser to give you a blank canvas 
    where as normalize is a base stylesheet meaning its the starting point for custom styles and it styles the default elements to be consistent across the browsers.


* Describe Floats and how they work.


* Describe BFC(Block Formatting Context) and how it works.
    https://www.sitepoint.com/understanding-block-formatting-contexts-in-css/


* What are the various clearing techniques and which is appropriate for what context? How works .clearfix?


* What are your favourite image replacement techniques and which do you use when?


* How would you approach fixing browser-specific styling issues?


* How do you serve your pages for feature-constrained browsers? What techniques/processes do you use?


* What are the different ways to visually hide content (and make it available only for screen readers)?


* Have you ever used a grid system, and if so, what do you prefer? Explain how a grid system works


* Have you used or implemented media queries or mobile specific layouts/CSS?


* Are you familiar with styling SVG?


* How do you optimize your webpages for print?


* How would you implement a web design comp that uses non-standard fonts?


* Explain how a browser determines what elements match a CSS selector.


* What are the some pseudo classed u have used?


* How do you optimize css selectors?


* How can you load css resources conditionally?


* Describe pseudo-elements and discuss what they are used for.


* What are the properties related to box model


* Explain your understanding of the box model and how you would tell the browser in CSS to render your layout in different box models.
    - The content of the space taken by an element. Each element has an inner and outer height/width calculated based on the content, padding, border and margin.

    content-box - default. Excludes padding, border and margin from the inner dimensions.
    border-box - includes the padding and border, but not the margin in the inner dimension.


* What does * { box-sizing: border-box; } do? What are its advantages?
    - Make every element in the document include the padding and border in the element's inner dimensions; 
    making it easier to reason about the layout of elements on the page.


* List as many values for the display property that you can remember.


* The 'C' in CSS stands for Cascading. How is priority determined in assigning styles (a few examples)? How can you use this system to your advantage?


* Can you explain the differences between em, rem, px?


* What's #target.


* What existing CSS frameworks have you used locally, or in production? How would you change/improve them?



* What are most common tested browsers and devices?


* Have you played around with the new CSS Flexbox or Grid specs?

    - Flexbox or Flexible boxes, is a new layout mode in CSS3 Use of flexbox ensures that elements behave predictably when the page layout must accommodate different screen sizes and different display devices.

    - For many applications, the flexible box model provides an improvement over the block model in that it does not use floats, nor do the flex container's margins collapse with the margins of its contents.

    - Grid specs CSS Grid Layout is a specification for creating two-dimensional grids Grid is a companion to the Flexible Box Module (flexbox). Flexbox is designed for one-dimensional layout, so things can be arranged in an unbroken line. Grid is designed for two-dimensional layout, meaning the items don't need to sit next to each other. In the future we're likely to use both: Grid Layout for main page areas, and flexbox for the smaller UI elements it excels with.


* How is responsive design different from adaptive design? What is responsive design? What is the difference between fixed and fluid layouts? What are some of the pros and cons with these designs?


* Have you ever worked with retina graphics? If so, when and what techniques did you use? What kind of techniques do you use to handle images for retina screens?


* Is there any reason you'd want to use translate() instead of absolute positioning, or vice-versa? And why?


* Do you subscribe to any particular CSS structure? (SMACSS, OOCSS)


* What is browser Compatibility?


* Tell what each of these tags do, if there are alternatives, which are preferable, why?

    <em>
    <b>
    <abbr>
    <nav>
    <i>
    <j>
    <link>
    <strong>
    <article>
    

* What is At-Rule

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


* What is Combinator selector

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

* What is RuleSet?
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

* Provide CSS so that three lines are displayed - red, then green, then blue (2):

    <div class="rgb">
        <span>Red</span>
        <span>Green<b>Blue</b></span>
    </div>


* Provided following HTML and CSS, what will be displayed (1)?

    <div class="red">Hi, I'm Blue</div>

    div.red    {color:green}
    div        {font-weight:bold}
    .red       {color:yellow;font-weight:normal}


* What is Declaration
    - The set of property names and values like: background: red;



* What is Declaration Block

    - A declaration block is the section of CSS where the property/value pairs appear. In the example below, everything found between the curly braces (not including the comments) is a declaration block:
```html
body {
  font-family: Arial, sans-serif; /* starts with this line */
  color: #555;
  font-size: 14px;
  line-height: 20px; /* ends here, before the closing curly brace */
}
```

* What is Universal Selector

    - The universal selector matches any element within the context in which it’s placed in a selector. 
    In the example below, the * character is the universal selector:
```html
/* the asterisk character is the universal selector */
.navigation ul * {
  width: 100px;
  float: left;
}
```

    - So, any element that appears as a child descendant of the unordered list element inside an element that has a class of “navigation” will receive the declared styles.

    - Universal selectors are generally discouraged for performance reasons.


* How can the gap under the image be removed?
    - As images being inline elements are treated same as texts, so there is a gap left, which can be   removed by:
```css
img { display: block ; }
```


* How comments can be added in CSS?
    - The comments in CSS can be added with /* and */.
    

* Define Attribute Selector ?
    - It is defined by a set of elements, value and its parts.


* Define property?
    - A style, that helps in influencing CSS. E.g. FONT. They have corresponding values or properties within them, 
    like FONT has different style like bold, italic etc.    


* What is graceful degradation?
    - In case the component fails, it will continue to work properly in the presence of a graceful degradation.
     The latest browser application is used when a webpage is designed. As it is not available to everyone,
      there is a basic functionality, which enables its use to a wider audience. 
    In case the image is unavailable for viewing, text is shown with the alt tag.


* What is progressive enhancement?
    - It’s an alternative to graceful degradation, which concentrates on the matter of the web. 
    The functionality is same, but it provides an extra edge to users having the latest bandwidth. 
    It has been into prominent use recently with mobile internet connections expanding their base.


* What is progressive rendering?

    http://stackoverflow.com/questions/33651166/what-is-progressive-rendering
    

* What is feature detection (vs browser detection)?


* What is mobile-first?


* What is accessibility/usability? What experience do you have with web accessibility? 


* What is SEO


* What is UI/UX
    - UI—or User Interface—is how a product or website is laid out and how you interact with it: Where the buttons are, how big the fonts are, and how menus are organized are all elements of UI.
    But UX—or User Experience—is how you feel about using a product or a website. So, your love for the way the new Apple Watch looks or your excitement that there’s finally a tablet-sized iPhone to watch those Corgi videos you’re obsessed with are reflections of UX.
    So the new look of the Facebook news feed involves a change to UI, and the way you navigate that new page is the UX. 


* What is semantic code


* What is typography  


* What are web standards


* What is valid HTML i CSS? (Who determines standards and criteria)


* Which of listed CSS properties are inherited?
    - position
    - font-size
    - color
    - background-color


* Enlist image types used in web, their properties and usage


* What is the purpose of em measurement unit?


* What is the purpose of pt measurement unit?


* Which property is used to change the face of a font?
    - The font-family property is used to change the face of a font.


* Which property is used to make a font italic or oblique?
    - The font-style property is used to make a font italic or oblique.


* Which property is used to create a small-caps effect?
    - The font-variant property is used to create a small-caps effect.


* Which property is used to increase or decrease how bold or light a font appears?
    - The font-weight property is used to increase or decrease how bold or light a font appears.


* Which property is used to add or subtract space between the letters that make up a word?

    - The letter-spacing property is used to add or subtract space between the letters that make up a word.


* Which property is used to add or subtract space between the words of a sentence?
    - The word-spacing property is used to add or subtract space between the words of a sentence.


* Which property is used to indent the text of a paragraph?
    - The text-indent property is used to indent the text of a paragraph.


* Which property is used to align the text of a document?
    - The text-align property is used to align the text of a document.


* Which property is used to underline, overline, and strikethrough text?
    - The text-decoration property is used to underline, overline, and strikethrough text.


* Which property is used to capitalize text or convert text to uppercase or lowercase letters?
    - The text-transform property is used to capitalize text or convert text to uppercase or lowercase letters.


* Which property allows you to control the shape or appearance of the marker of a list?
    - The list-style-type allows you to control the shape or appearance of the marker.


* How do I restore the default value of a property?
    - Initially CSS didn't provide a "default" keyword and the only way to restore the default value of a property is to explicitly re-declare that property
    This has changed with CSS 2; the keyword 'initial' is now a valid value for a CSS property. 
    It resets it to its default value, which is defined in the CSS specification of the given property.


* How do I assign multiple classes to an element?
    - HTML elements can be assigned multiple classes by listing the classes in the class attribute, with a blank space to separate them.
```html
<style type="text/css">
.news { background: black; color: white; }
.today { font-weight: bold; }
</style>

<div class="news today">
... content of today's news ...
</div>
```

* What are preferred rules for specificity?


* What is selector specificity (selector importance) and how it works? How do u calculate specificity?
    - https://developer.mozilla.org/en/docs/Web/CSS/Specificity
    
    - https://www.smashingmagazine.com/2007/07/css-specificity-things-you-should-know/
    
    - https://github.com/TIY-Austin-Front-End-Engineering/css-specificity


* What do you know about transition?


* What are the different css filter you can use?
    https://developer.mozilla.org/en/docs/Web/CSS/filter


* Enlist the various fonts properties?
    - font-style
    - font-variant
    - font-weight
    - font-size/line-height
    - font-family
    - caption
    - icon


* Enlist the position / display / overflow properties and what are defaults


* Enlist the various CSS background properties.
 

* Image paths in CSS vs HTML 
 

* What is transition & transform? 
 

* What is used flexbox / transforms / transitions / animations?


* What exposure do you have to CSS3 animations and transitions


* Can you export contents from PSD / Sketch?


* What kind of challenges do you run into formatting a site for Mobile devices?


* Describe Floats and Flexbox and how each works. Why Flexbox is a better solution for web layouts?
    
    - Floats - specifies that an element should be taken from the normal flow and placed along the left or right side of its container, 
    where text and inline elements will wrap around it.
    
    - Flexbox - consists of flex containers and flex items. Flex containers wrap a set of flex items and define how they are laid out. 
    Flex items has properites that define how they interact with sibling flex elements and can also be flex containers themselves.


* What font units are available in CSS?


* What is the difference between padding and margins?


* What does !important mean in CSS?
    - It overrides the cascade and gives the style rule the highest precedence.


* What is cross-browser compatibility? 


* How do you test cross-browser compatibility of your site?


* How can you make a site responsive?


* The Difference Between Responsive and Adaptive Design
    https://css-tricks.com/the-difference-between-responsive-and-adaptive-design/


* What do you know about text shadows, box shadows?


* What is the difference between CSS variables and preprocessor variables?
    https://css-tricks.com/difference-between-types-of-css-variables/


* The Difference Between :nth-child and :nth-of-type
    https://css-tricks.com/the-difference-between-nth-child-and-nth-of-type/
    

* What selects ul[class] > li:nth-child(2n+1)    
    

* What is the difference between “word-break: break-all” versus “word-wrap: break-word” in CSS
    

* How is word-wrap different from white-space ?
    https://css-tricks.com/almanac/properties/w/whitespace/


* What is <pre> ?


* How is <b> different from <strong> ?
    

* What does minification do?


* What are some ways to make websites faster? Name as many different techniques as you can.
    

* How do you test the performance of your code and/or web pages?


* What are some rules for writing efficient CSS    
    

* Sass
    * What are you favorite features in SASS?
    
    * Explain nested selectors in Sass
        
    * How do you refer to a parent selector in the SASS?
        
    * Explain what Sass Maps are and how they are use?
    
    * Explain the @import function and how it is used
    
    * Explain the @include, @mixin, @function functions and how they are used. What is %placeholder
        
        - @mixin: A mixin lets you make groups of CSS declarations that you want to reuse throughout your site

            @mixin border-radius($radius) {
              -webkit-border-radius: $radius;
                 -moz-border-radius: $radius;
                  -ms-border-radius: $radius;
                      border-radius: $radius;
            }
            
            .box { @include border-radius(10px); }
            

        - @extend directive provides a simple way to allow a selector to inherit/extend the styles of another one.

            .message {
              border: 1px solid #ccc;
              padding: 10px;
              color: #333;
            }
            
            .success {
              @extend .message;
              border-color: green;
            }
            
            .error {
              @extend .message;
              border-color: red;
            }
        
        

        - %placeholder are classes that aren’t output when your SCSS is compiled

            %awesome {
                width: 100%;
                height: 100%;
            }
            body {
                @extend %awesome;
            }
            p {
                @extend %awesome;
            }
            
            Output
            
            body, p {
                width: 100%;
                height: 100%;
            }


* What are some considerations in selecting font sizes? // This question is focused on accessibility


* As an organisation we aim to meet WCAG AA standards for accessibility. What experience do you have with developing accessible websites?


* How do you approach developing an accessible website?


* What are some of the common accessibility pitfalls when developing a website? How would you go about fixing them?


