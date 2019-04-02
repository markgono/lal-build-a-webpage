# CSS

CSS is a language that describes the style of an HTML document – how it looks.

> Note:
> CSS stands for *Cascading Style Sheets*.  The cascade part of that means they read from top to bottom, with the last styles defined being the ones that are /usually/ the most important!

CSS allows us to select elements, using a selector, then apply styling rules to any elements that match that selector.

```
.selector {
	property: value;
}
```

## Selectors
When we covered HTML we learned that elements can have attributes.

Selectors allow us to select an element – based on its type, attributes or even its contents.

Selectors:
- *body* – selects the body element
- *.active* – selects any element with the class attribute “green”
- *#main* – selects any element an id of main

> These get confusing – in the real world, we only use one selector type the most – class selectors.

## Rules
CSS rules are made up of a *property* and a *value*.

Rules:
- *text-align: right;* – aligns all the text in this element to the right
- *background-color: black;* – sets the background colour of this element as black
- *margin: 10px;* – puts a 10px margin around the element


## A Complete Rule
If we wanted to center align all the elements on the page we’d write:

```
body {
	text-align: center;
}
```

> Note:
> Children elements inherit the css rules of their parent

## CSS Challenge
It’s time to write some CSS!

- The color of our header is off – it’s looking a bit bland. If I wanted to change the background colour to blue, I could use the rule:
```
.header {
	background-color: rgb(0, 0, 255);
}
```

Open your `styles/main.css` and add a rule to change the header it to Gousto red!

- Change the color or positioning of one other element on the page!

## Next Steps
If you’re really into CSS, you can check out the rules available:
[CSS Reference - A free visual guide to CSS](https://cssreference.io/)

There’s a lot of cool stuff you can do, just check out the site I’m running the workshop on:
https://codepen.io/

[Okay. Time to get coding! Click here to learn about JavaScript.](03-js.md)
