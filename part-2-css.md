# Stylising your webpage with CSS
### Wait a moment
Have you followed the HTML tutorial yet?

____
So now that we've setup the structure of our page with HTML, we can begin styling our webpage - adding colours and generally making it excellent!

To do this, we use **CSS** which stands for *Cascading Style Sheets*, which are a list of **rules** for the styling of the webpage.

CSS rules are really simple and are only made of three components, let's take a look at a sample of a CSS rule:

```css
p {
	color: red;
}
```

In this example above, this is a **CSS rule** which says that all `<p>` **elements** should have the `color` set to `red`. In this example, `<p>` is the **selector**, color is the **property** and red is the **value**. So we could say:

```css
element {
	property: value;
}
```

It's also important to note the curly braces `{}` and the semicolon `;` - it's very important you remember these. You also **don't** need to include the `<` and `>` like you would have used for HTML. 

### Now you try!
So if we wanted to create a **rule** on the **element** `<h1>` which sets the **property** `color` to `blue`, how would we write this rule, try it over in your JSFiddle in the CSS window and if you need help, ask a mentor.
## Selecting via ID

```html
<p>Weapons in my game:</p>
<ul>
	<li id="sword">Sword</li>
	<li>Staff</li>
	<li>Bow and arrow</li>
</ul>
```


select via id

## Selecting via class
If you want to select many, you can also use a class!

```html
<p>Weapons in my game:</p>
<ul>
	<li class="good-weapons">Sword</li>
	<li>Staff</li>
	<li class="good-weapons">Bow and arrow</li>
</ul>
```
To select the class in CSS we use the full-stop before the class-name!

```css
.good-weapons {
	color: red;
}
```

## Nested selectors
_@TODO: Explain nested selecto