# HTML

A *markup language* is a system for annotating a document in a way that is syntactically distinguishable from the text or contents of the document.

HTML is a markup language – it actually stands for HyperText Markup Language – we use it to describe the building blocks of a webpage to the browser.

## The Markup

In terms of how it looks, we use markup to describe the elements that make up a page.

The HTML:

```html
<h1>Lunch & Learn</h1>
```

Describes a **Header** element (the *h* in *h1*) which contains the text **Lunch & Learn**.

Most HTML Elements require opening and closing tags, this allows us to put things inside of them!

```html
<ul>
  <li>Salt</li>
  <li>Pepper</li>
  <li>Olive Oil</li>
</ul>
```

Describes a **List** element (an unordered list) which contains **3 List Items**: Salt, Pepper and Olive Oil.

---

On our page, we’re using:
Some required elements:
- *html* – Every page starts and ends with this!
- *head* – For hidden information about the page
- *body* – The substance, everything you see ends up here

Some lesser elements:
- *p* - a paragraph
- *ul* - an unordered list
- *div* - a division. /We use these to separate and group elements together/

## HTML Attributes

HTML elements can also have attributes that further define the element.

```html
<img src="http://placekitten.com/200/300" />
```
Describes an **Image** element whose contents are *sourced* from placekitten.com

### Try it!

Try copying and pasting the above image into your page, between the body tags!

Also, try changing the numbers or adding multiple `img` tags - What happens?

---

We could also assign an ID:
```html
<h3 id=“#welcome”>Welcome to Gousto</h3>
```
or some classes:
```html
<p class="description">Precise ingredients, delicious recipes and a dollop of adventure.</p>
```

## HTML Challenge
Let’s try modifying some HTML!

### Challenge 1

First, let’s modify our title!

Let’s tell the browser to make the middle line more impactful by increasing the importance of the header.

> No CSS required!

### Challenge 2
Name your app!

Change the contents of the title to whatever you want!

## Next Steps
Great, that’s a short intro into HTML essentials.

If you want to learn more about HTML, here’s a great reference:

[HTML Tutorial](https://www.w3schools.com/html/default.asp)

[Click here and we’ll learn about CSS.](02-css.md)
