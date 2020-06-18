### CSS has been adopted by all major browsers and allows you to control:

color
fonts
positioning
spacing
sizing
decorations
transitions

### There are three main ways to apply CSS styling. 
### You can apply inline styles directly to HTML elements with the style attribute. 
### Alternatively, you can place CSS rules within style tags in an HTML document. 
### Finally, you can write CSS rules in an external style sheet, 
### then reference that file in the HTML document.

### The idea behind CSS is that you can use a selector to target an HTML element 
### in the DOM (Document Object Model) and then apply a variety of attributes to 
### that element to change the way it is displayed on the page.


----------------------------------

Basic CSS: Change the Color of Text
Now let's change the color of some of our text.

We can do this by changing the style of your h2 element.

The property that is responsible for the color of an element's text is the color style property.

Here's how you would set your h2 element's text color to blue:

<h2 style="color: blue;">CatPhotoApp</h2>

Note that it is a good practice to end inline style declarations with a ; .

Change your h2 element's style so that its text color is red.

-------------------------------------

Basic CSS: Use CSS Selectors to Style Elements
With CSS, there are hundreds of CSS properties that you can use to change the way an element looks on your page.

When you entered <h2 style="color: red;">CatPhotoApp</h2>, you were styling that individual h2 element with inline CSS, which stands for Cascading Style Sheets.

That's one way to specify the style of an element, but there's a better way to apply CSS.

At the top of your code, create a style block like this:

<style>
</style>
Inside that style block, you can create a CSS selector for all h2 elements. For example, if you wanted all h2 elements to be red, you would add a style rule that looks like this:

<style>
  h2 {
    color: red;
  }
</style>
Note that it's important to have both opening and closing curly braces ({ and }) around each element's style rule(s). You also need to make sure that your element's style definition is between the opening and closing style tags. Finally, be sure to add a semicolon to the end of each of your element's style rules.

Delete your h2 element's style attribute, and instead create a CSS style block. Add the necessary CSS to turn all h2 elements blue.

