# HTML Cheatsheet
## Headings
#\<h1>Heading 1\</h1>
##\<h2>Heading 2\</h2>
###\<h3>Heading 3\</h3>
####\<h4>Heading 4\</h4>
#####\<h5>Heading 5\</h5>
_____
## Paragraphs
Paragraphs are simply made with a `<p>` tag!

```html
<p>I'm learning to make a website at Coderdojo!</p>
```

## Lists
To start a list, you start with the opening list tag. There are two types of lists with a different tag for each - **o**rdered **l**ists (`<ol>`) and **u**nordered **l**ists (`<ul>`).

For each element/item you want in your list, you need to use the **l**ist **i**tem element (`<li>`).

### Ordered List Example:
If you wanted to list something with numbers before each line, you will probably want to use an unordered list:

```html
<p>How to make a million dollars</p>
<ol>
    <li>Go to Coderdojo</li>
    <li>Learn HTML</li>
    <li>Learn CSS</li>
    <li>Learn JS</li>
    <li>Make the next Facebook</li>
</ol>
```
**Becomes:**

How to make a million dollars:

1. Go to Coderdojo
2. Learn HTML
3. Learn CSS
4. Learn JS
5. Make the next Facebook

### Unordered List Example:
Say you wanted to write a shopping list - the order of all the products in the list is not important.

```html
<p>My shopping list:</p>
<ul>
	<li>Milk</li>
	<li>Milo</li>
	<li>Icecream</li>
	<li>Freddos</li>
</ul>
```
**Becomes:**

My shopping list:

* Milk
* Milo
* Icecream
* Freddos