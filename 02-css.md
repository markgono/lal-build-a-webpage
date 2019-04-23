# CSS

CSS is a language that describes the style of an HTML document – how it looks.

> Note:
>
> CSS stands for *Cascading Style Sheets*.
>
> The cascade part of that means they read from top to bottom, with the last styles defined being the ones that are _usually_ the most important!

CSS allows us to select elements, using a selector, then apply styling rules to any elements that match that selector.

```css
.selector {
	property: value;
}
```

## Selectors
When we covered HTML we learned that elements can have attributes.

Selectors allow us to select an element – based on its type, attributes or even its contents.

Selectors:

```css
body {}
```

Selects the `<body></body>` element

```css
.active {}
```

Selects _any_ element with the class attribute "active"

i.e. `<div class="selected active"></div>` and `<small class="active"></small>`
would both be selected by this rule

```css
#main {}
```

Selects any element an id of main

e.g. `<h1 id="main"></h1>`

> These get confusing – in the real world, we only use one selector type the most – class selectors.

## Rules
CSS rules are made up of a *property* and a *value*.

Rules:
- `text-align: right;` – aligns all the text in this element to the right
- `background-color: black;` – sets the background colour of this element as black
- `margin: 10px;` – puts a 10px margin around the element


## A Complete Rule
If we wanted to center align all the elements in our intro we’d write:

```css
.intro {
	text-align: center;
}
```

> Note:
> Children elements inherit the css rules of their parent

## CSS Challenge
It’s time to write some CSS!

### Challenge 1

The color of our header is off – it’s looking a bit bland.

If I wanted to change the background colour to blue, I could use the rule:

```css
.header {
	background-color: rgb(0, 0, 255);
}
```

Open your `styles/main.css` and add a rule to change the header it to Gousto red!

### Challenge 2

Let's put together what we've learned earlier

Let's create a HTML element in our `index.html`:

> Try using a `blockquote`, `small` or a `ul` containing `li` elements

Now create a styling rule that applies only to that element!

```css
element {
	text-shadow: 2px 4px 10px grey;
}
```

Other CSS properties we could use:

- `text-decoration`
- `text-transform`
- `border`

## Next Steps
If you’re really into CSS, you can check out the rules available:
[CSS Reference - A free visual guide to CSS](https://cssreference.io/)

There’s a lot of cool stuff you can do, just check out the site I’m running the workshop on:
https://codepen.io/

[Okay. Time to get coding! Click here to learn about JavaScript.](03-js.md)
