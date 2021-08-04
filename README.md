# Using Your Browser's Developer Tools

## Learning Goals

- Examine the developer tools
- Use the developer tools to locate and inspect elements
- Use the developer tools to edit HTML

## Introduction

By now, you're pretty familiar with HTML structural elements, and how they
relate to each other on the page. You might even feel pretty comfortable writing
your own valid HTML. But much of the time as developers, we'll be jumping in on
projects that are already in progress. We'll need a way to view existing HTML
and CSS, and potentially a way to play around with elements on live pages to see
how we might potentially adjust things. Luckily for us, most browsers have those
kinds of tools already built in, called `developer tools`, or `dev tools` for
short. In this lesson, we'll look at the `dev tools` on [Google
Chrome](https://www.google.com/chrome/).

## Examine the Developer Tools

The Developer tools that browsers provide you are a great way to experiment with
HTML and CSS, and immediately see how those changes are rendered in the browser.

For this lesson, please open the
[Wikipedia page for Alan Turing](https://en.wikipedia.org/wiki/Alan_Turing) in
Chrome.

Once the page is open, right click on the title of the page — the header
containing his name. You should get a list of options. We want to click on the
one that says `Inspect`. This is going to bring up a window at the bottom of the
page that contains all of the HTML that makes up the Wikipedia page.

## Use the Developer Tools to Locate and Inspect Elements

If you hover over elements, you should see different colored boxes appear over
different parts of the page. We're going to hover over the HTML until we find
the section that contains the title of the page ("Alan Turing"). It should look
something like this:

```html
<h1 id="firstHeading" class="firstHeading">...</h1>
```

## Use the Developer Tools to Edit HTML

There should be a drop down arrow next to the first `<h1 ...>` If you don't
already see the text nested under that `<h1>`, click on the arrow to expose it.
Right click that text and select `Edit as HTML`.

A new window will pop up in Dev Tools where we can actually go in and type. Try
deleting "Alan Turing" and replacing it with "Puppies Puppies Puppies." Once
you're done, just click outside of the text window, and take a look back at the
header in the browser. It should now say "Puppies Puppies Puppies."

If you refresh the page, your text will disappear. We're just editing HTML in
our own web browser, not on Wikipedia's web server. Feel free to scroll around
on the page and play with all sorts of different HTML elements and see what
happens.

### Editing Images

Now, right click on Alan Turing's picture and choose "Inspect". Right click on
the image tag in the HTML and again select `Edit as HTML`. Let's replace the
entire `<img>` tag with another image from a website. For example, you might
change it to this:

```html
<img
  src="http://images2.fanpop.com/image/photos/9400000/Aaaaaawwwwwwwwww-Sweet-puppies-9415255-1600-1200.jpg"
  alt="Puppies"
/>
```

Your puppy image should now be displaying on the page, but it's pretty big.
Let's add an attribute to our `<img>` tag to set the image's size. It should
look like this:

```html
<img
  src="http://images2.fanpop.com/image/photos/9400000/Aaaaaawwwwwwwwww-Sweet-puppies-9415255-1600-1200.jpg"
  width="200"
  alt="Puppies"
/>
```

This attribute sets the width of the image to 200px and adjusts the height
accordingly. Much better!

Feel free to play with other HTML elements and watch things change on the page.

### Bonus

If you want to attempt to change any of the styles of the page, take a look at
the right-hand column. CSS, which stands for Cascading Style Sheets, manages all
the styles of your page (think background color, font size, placement of
different items on the page, etc).

Feel free to play around, check and uncheck boxes, change colors, change pixels.
It's okay if you "mess things up". Just refresh the browser and it will all go
back to how it was!
