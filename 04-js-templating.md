# Template Strings

Template Strings in JavaScript work like string literals mixed with variables. So for example, the string “Hello, Mark” could be replaced with a template string:

```
const name = ‘Mark’
console.log(‘Hello, ${name}’)
```

> Try it out!
> Paste the above in your console, but assign your name to *name* instead!

The way our application turns our products into HTML Elements is using Template Strings. Take a look at ‘base/templates.js’, our products are showing, but our categories are not.

Challenge:
Let’s create a template string for the categories. It needs to look like:
‘<li class=“category”>Free From</li>`

