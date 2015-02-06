# Kerning the Web

Various methods of kerning web typography as part of the @ixdbelfast AAD117 - Exploring Identity module.

##Kerning with CSS

###1. Kerning with ```<span>``` - Serif
In this example we'll work through kerning type using ```<span>```'s and the ```letter-spacing``` CSS element.

+ [Template](kerning-with-css/1-kerning-with-css-sans-serif-template.html)
+ Final Exercise with Kerning (Link your work here)

###2. Kerning with ```<span>``` - Sans Serif
Let's try it again, this time using a different typeface and case.

+ [Template](kerning-with-css/2-kerning-with-css-serif-template.html)
+ Final Exercise with Kerning (Link your work here)

__Notes__ Kerning with ```<span>``` and ```letter-spacing``` can make your code messy, especially on long words where a lot of kerning is required. It is however supported by all browsers and gives you absolute and precise control over the kerning.

###3. Kerning with ```font-kerning``` - Serif
In this example we'll work through kerning type using the ```font-kerning``` CSS3 property.

+ [Template](kerning-with-css/3-kerning-with-font-kerning-template.html)
+ Final Exercise with Kerning (Link your work here)

__Note:__ Kerning with the CSS3 property ```font-kerning``` controls the usage of the kerning information, that is, if this information is stored in the font. Try Georgia for example, you'll notice there is no change. Be wary of the browser support for this property as at the time of writing, is fairly limited.


###4. Kerning with JavaScript - Sans Serif
In this example we'll work through kerning type using [JQuery](http://jquery.com/) and [Kerning.js](http://kerningjs.com/).

+ [Template](kerning-with-javascript/4-kerning-with-kerningjs-sans-serif-template.html)
+ Final Exercise with Kerning (Link your work here)

###5. Kerning with JavaScript - Web Fonts
In this example we'll work through kerning type using [JQuery](http://jquery.com/) and [Kerning.js](http://kerningjs.com/) using a typeface of your choice, from [Google Fonts](https://www.google.com/fonts)

+ [Template](kerning-with-javascript/5-kerning-with-kerningjs-webfont-template.html)
+ Final Exercise with Kerning (Link your work here)

__Note:__ Kerning with Javascript offers a great way to take control of your web typography. There are many great features baked in that makes life easier, like transforming letters and positioning. The downside is the payload of these scripts increase the page load and the rendered HTML wraps the letters in ```<span>```'s and inline CSS.