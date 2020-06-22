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


---------------------------------------------------------------------------


Basic CSS: Use a CSS Class to Style an ElementPassed
Classes are reusable styles that can be added to HTML elements.

Here's an example CSS class declaration:

<style>
  .blue-text {
    color: blue;
  }
</style>

You can see that we've created a CSS class called blue-text within the <style> tag. You can apply a class to an HTML element like this: <h2 class="blue-text">CatPhotoApp</h2> Note that in your CSS style element, class names start with a period. In your HTML elements' class attribute, the class name does not include the period.

Inside your style element, change the h2 selector to .red-text and update the color's value from blue to red.

Give your h2 element the class attribute with a value of 'red-text'.

<style>
  .red-text {
    color: red;
  }
</style>

<h2 class="red-text">CatPhotoApp</h2>


------------------------------------------------------------------------------

Basic CSS: Style Multiple Elements with a CSS ClassPassed
Classes allow you to use the same CSS styles on multiple HTML elements. You can see this by applying your red-text class to the first p element.

<style>
  .red-text {
    color: red;
  }
</style>

<h2 class="red-text">CatPhotoApp</h2>
<main>
  <p class="red-text">Click here to view more <a href="#">cat photos</a>.</p>

  ------------------------------------------------------------------------------

  Basic CSS: Change the Font Size of an Element
Font size is controlled by the font-size CSS property, like this:

h1 {
  font-size: 30px;
}
Inside the same <style> tag that contains your red-text class, create an entry for p elements and set the font-size to 16 pixels (16px).

<style>
  .red-text {
    color: red;
  }

  p {
    font-size: 16px;
  }

</style>

<h2 class="red-text">CatPhotoApp</h2>
<main>
  <p class="red-text">Click here to view more <a href="#">cat photos</a>.</p>

  <a href="#"><img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back."></a>

  <div>
    <p>Things cats love:</p>
    <ul>
      <li>cat nip</li>
      <li>laser pointers</li>
      <li>lasagna</li>
    </ul>
    <p>Top 3 things cats hate:</p>
    <ol>
      <li>flea treatment</li>
      <li>thunder</li>
      <li>other cats</li>
    </ol>
  </div>

  ---------------------------------------------------------------------------


  Basic CSS: Set the Font Family of an Element
You can set which font an element should use, by using the font-family property.

For example, if you wanted to set your h2 element's font to sans-serif, you would use the following CSS:

h2 {
  font-family: sans-serif;
}
Make all of your p elements use the monospace font.

<style>
  .red-text {
    color: red;
  }

  p {
    font-size: 16px;
    font-family: "monospace";
  }

  /* body {
    font-family: "Paytone One"
  } */
</style>