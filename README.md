## Media Query Tutorial

```@media``` Media query is the backbone of reponsive web pages. Media queries 
allow us to change, modify, customize and temporarily view the web page differently. 
To alter the page, we must have an expression, or condition and a CSS style or rule
to be permitted after the expression. A media type may also be applied before the 
condition to let your browser know if the query is for ```screen```, ```print```, or ```all```.

The most common example of a media condition would be viewport/screen size.
Applying the minimum/maximum ```width``` or ```height``` as a condition
will affect the page when you resize it. Setting the ```max-width``` to 600px
will apply the rule to your page when your width is at 600 pixels or lower.

Setting a rule to your media query is essential, and your code will not work without it.
The rule that you are applying must be a CSS property, and will customize your page
accordingly. If you set your ```max-width``` at 600px, and set your body ```background-colour```
to yellow, then when you resize the page less than or equal to 600px, the ```background-colour```
of the page will turn to yellow.

You may also set multiple rules to a single media condition, such as ```font-size```, ```color```,
etc. By doing so, you will be able to change multiple aspects of your page through your condition.
More conditions include using ```hover```, changing the ```orientation```, and many more. 

```CSS
@media (max-width: 480px) {
    body { background-color: yellow; }
    p { 
        font-size: 50px;
        font-weight: 600;
        color: #41434b;
    }
}
```
You must link your main index.html file to your index.css for the properties to be applied to your page
when resizing.

### References
[Guide to CSS Media Queries](https://css-tricks.com/a-complete-guide-to-css-media-queries/)\
[CSS Media Queries](https://www.w3schools.com/css/css3_mediaqueries.asp)\
[Responsive Web Design](https://www.w3schools.com/css/css_rwd_mediaqueries.asp)
