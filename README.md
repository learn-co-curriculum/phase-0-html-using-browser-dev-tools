# Dev Tools Super Power

## Learning Goals

1. Examine the developer tools
2. Use the developer tools to locate and inspect elements
3. Use the developer tools to edit HTML

##  Introduction

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

For this lesson, please open the Twitter account of your favorite celebrity in
Chrome. If you don't know their Twitter handle, a quick Google search should
find it for you. _(Drawing a blank? Try using the [Flatiron School twitter
account](https://twitter.com/flatironschool).)_

Once the page is open, right click on the body of their very first tweet. You
should get a list of options. We want to click on the one that says `Inspect`.
This is going to bring up a window at the bottom of the page that contains all
of the HTML that makes up that Twitter page.

## Use the Developer Tools to Locate and Inspect Elements

If you hover over elements, you should see different colored boxes appear over
different parts of the page. We're going to hover over the HTML until we find
the section that contains the text of the first tweet. It should look like this:
```
<p class="TweetTextSize TweetTextSize--normal js-tweet-text tweet-text"
lang="en" data-aria-label-part="0">...</p>
```

## Use the Developer Tools to Edit HTML

There should be a drop down arrow next to the first `<p`... If you don't already
see more elements nested under that `<p>`, click on the arrow. When you click
it, more text should show up, including the actual body of the tweet. Right
click that text and select `Edit as HTML`.

A new window will pop up where we can actually go in and type. Try deleting the
body of the tweet, and entering your own message. Once you're done, just click
outside of the text window, and take a look back at the tweet in the browser. It
should have changed to your message.

If you refresh the page, your text will disappear. We're just editing HTML in
our own web browser, not on Twitter's web server. Feel free to scroll around on
Twitter and play with all sorts of different HTML elements and see what happens.

### Editing Images

See if you can find an image. It will be wrapped in HTML tags that start with
`<img src=`.... You can right click on the image tag in the HTML and again
select `Edit as HTML`. Between the quotes after `src=` you can replace the image
with another one from a website. For example,

```
<img src="./my_image.jpg" alt="Some Image">
```

might become

```
<img src="http://images2.fanpop.com/image/photos/9400000/Aaaaaawwwwwwwwww-Sweet-puppies-9415255-1600-1200.jpg" alt="Puppies">
```

Feel free to play with other HTML elements and watch things change on the page.

### Bonus

If you want to attempt to change any of the styles of the page, take a look at
the right-hand column. CSS, which stands for Cascading Style Sheets, manages all
the styles of your page (think background color, font size, placement of
different items on the page, etc).

Feel free to play around, check and uncheck boxes, change colors, change pixels.
It's okay if you "mess things up". Just refresh the browser and it will all go
back to how it was!

<p data-visibility='hidden'>View <a href='https://learn.co/lessons/dev-tools-super-power'>Dev Tools Super Power</a> on Learn.co and start learning to code for free.</p>
