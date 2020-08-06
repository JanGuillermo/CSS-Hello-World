# CSS - 'Hello World!'

## Project's Goal

You can print `Hello World!` in Python. Even in Java. Heck, any language could work!

> But you can't print "Hello World!" in a stylesheet language!

My friend, let me prove you wrong. Therefore, that brings us to this section - the project's goal. I shall attempt to print `Hello World!` using CSS (a stylesheet language).

## How the heck did you do this?!

I placed this code block in a HTML5 page.

```
<div class="helloworld"></div>
```

Then I applied a style rule to the class `helloworld`.

```
.helloworld:after {
  display: block;
  content: "Hello World!";
}
```

That's it! Simple, right? So basically, this style rule creates a pseudo-element of the selected element and tells it to display as a block and have the text "Hello World!" on it.

Programming is where you can make magic happen!

[Demo](https://janguillermo.github.io/CSS-Hello-World/)
