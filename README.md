## Dev Tools Super Power

The Developer tools that browsers provide you are super powerful and are a really good way to edit HTML and CSS and see immediately how those changes are rendered in the browser. We're going to be using the Chrome browser.

For this lab, please open the twitter account of your favorite celebrity in Chrome. If you don't know their twitter handle, a quick google search should narrow it down for you.

Once the page is open, right click on the body of their very first tweet. You should get a list of options. We want to click on the one that says `Inspect Element`. This is going to bring up a window at the bottom of the page that contains all of the HTML that make of that twitter page. 

If you hover over elements, you should see different colored boxes appear over different parts of the page. We're going to hover over the HTML until we find the section that contains the text of the first tweet. It should look like this 
```
<p class="ProfileTweet-text js-tweet-text u-dir" dir="ltr">...</p>
``` 

There should be a drop down arrow next to the first `<p`... If you click that, more text should show up, inlcuding the actual body of the tweet. We want to right click that text and select `Edit as HTML`.

A new window will pop up where we can actually go in and type. Here you can delete the body of the tweet, and enter your own message. Once you're done, just click off to the side of that back, and take a look back at the tweet in the browser. It should have changed your message.

If you refresh the page, your text will disappear. We're just editing HTML in our own copy, not on twitter's. You can scroll around on twitter and play with all sorts of different HTML elements and see what happens.

See if you can find an image. It will be wrapped in HTML tags that start with `<img src=`....



