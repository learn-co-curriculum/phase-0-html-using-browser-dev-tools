## Dev Tools Super Power

The Developer tools that browsers provide you are super powerful and are a really good way to edit HTML and CSS and see immediately how those changes are rendered in the browser. We're going to be using the Chrome browser.

For this lab, please open the Twitter account of your favorite celebrity in Chrome. If you don't know their Twitter handle, a quick Google search should find it for you.

Once the page is open, right click on the body of their very first tweet. You should get a list of options. We want to click on the one that says `Inspect Element`. This is going to bring up a window at the bottom of the page that contains all of the HTML that makes up that Twitter page. 

If you hover over elements, you should see different colored boxes appear over different parts of the page. We're going to hover over the HTML until we find the section that contains the text of the first tweet. It should look like this: 
```
<p class="ProfileTweet-text js-tweet-text u-dir" dir="ltr">...</p>
``` 

There should be a drop down arrow next to the first `<p`... when you click that, more text should show up, including the actual body of the tweet. We want to right click that text and select `Edit as HTML`.

A new window will pop up where we can actually go in and type. Here you can delete the body of the tweet, and enter your own message. Once you're done, just click outside of the text window, and take a look back at the tweet in the browser. It should have changed your message.

If you refresh the page, your text will disappear. We're just editing HTML in our own copy, not on Twitter's. You can scroll around on Twitter and play with all sorts of different HTML elements and see what happens.

See if you can find an image. It will be wrapped in HTML tags that start with `<img src=`.... You can right click on the image tag in the HTML and again select `Edit as HTML`. Between the quotes after `src=` you can replace the image with another one from a website.../

```
<img src="./my_image.jpg" alt="Some Image">
```
Can become...
```
<img src="http://images2.fanpop.com/image/photos/9400000/Aaaaaawwwwwwwwww-Sweet-puppies-9415255-1600-1200.jpg" alt="Puppies">
```

Feel free to play with other HTML elements and watch things change on the page.

###Bonus:
If you want to attempt to change any of the styles of the page, take a look at the right-hand column. CSS, which stands for Cascading StyleSheets, manages all the styles of your page (think background color, font size, placement of different items on the page, etc).


Feel free to play around, check and uncheck boxes, change colors, change pixels. It's okay if you "mess things up". Just refresh the browser and it will all go back to how it was!




<a href='https://learn.co/lessons/dev-tools-super-power' data-visibility='hidden'>View this lesson on Learn.co</a>

<p data-visibility='hidden'>View <a href='https://learn.co/lessons/dev-tools-super-power'>Dev Tools Super Power</a> on Learn.co and start learning to code for free.</p>
