# Images

Controlling the size and alignment of your images using CSS keeps rules that affect the presentation of your page in the CSS and out of the HTML markup. You can also achieve several interesting effects using background images.

## Controlling sizes of images in CSS

You can control the size of an image using the `width` and `height` properties in CSS, just like you can for any other box.
Specifying image sizes helps pages to load more smoothly because the HTML and CSS code will often load before the images, and telling the browser how much space to leave for an image allows it to render the rest of the page without waiting for the image to download.
You might think that your site is likely to have images of all different sizes, but a lot of sites use the same sized image across many of their pages.
For example, an e-commerce site tends to show product photos at the same size. Or, if your site is designed on a grid, then you might have a selection of image sizes that are commonly used on all pages.


## Aligning images Using CSS

Rather than using the `<img>` element's align attribute, web page authors are increasingly using the float property to align
images. There are two ways that this is commonly achieved:
1. The float property is added to the class that was created to represent the size of the image (such as the small class in our example).
2. New classes are created with names such as align-left or align-right to align the images to the left or right of the page.
These class names are used in addition to classes that indicate the size of the image.

## Background Images

The `background-image` property allows you to place an image behind any HTML element. This could be the entire page or just part of the page. By default, a background image will repeat to fill the entire box.

The path to the image follows the letters `url`, and it is put inside parentheses and quotes.

## Repeating Images

The `background-repeat` property can have four values:

### repeat
The background image is repeated both horizontally and vertically (the default way it is shown if the background repeat property isn't used).

### repeat-x
The image is repeated horizontally only (as shown in the first example on the left).

### repeat-y
The image is repeated vertically only.

### no-repeat
The image is only shown once.


The `background-attachment` property specifies whether a background image should stay in one position or move as the user
scrolls up and down the page. It can have one of two values:

### fixed
The background image stays in the same position on the page.

### scroll
The background image moves up and down as the user scrolls up and down the page.

## Image Rollovers & Sprites

Using CSS, it is possible to create a link or button that changes to a second style when a user moves their mouse over it (known as a rollover) and a third style when they click on it.

This is achieved by setting a background image for the link or button that has three different styles of the same button (but
only allows enough space to show one of them at a time). You can see the image we are using in this example on the right. It actually features two buttons on the one image.

When the user moves their mouse over the element, or clicks on it, the position of the background image is moved to show the relevant image.


# Practical Information

## Search Engine Optimization (SEO)
SEO is a huge topic and several books have been written on the subject.

### The Basics
Search engine optimization (or SEO) is the practice of trying to help your site appear nearer the top of search engine results when people look for the topics that your website covers.
At the heart of SEO is the idea of working out which terms people are likely to enter into a search engine to find your site and then using these terms in the right places on your site to increase the chances that search engines will show a link to your site in their results.

In order to determine who comes first in the search results, search engines do not only look at what appears on your site. They also consider how many sites link to you (and how relevant those links are). For this reason, SEO is often split into two areas: on-page techniques and off-page techniques.


### On-Page Techniques
On-page techniques are the methods you can use on your
web pages to improve their rating in search engines.

The main component of this is looking at keywords that people are likely to enter into a search engine if they wanted to find your site, and then including these in the text and HTML code for your site in order to help the search engines know that your site covers these topics.

Search engines rely very heavily on the text that is in your pages so it is important that the terms people are going to search for are in text. There are seven essential places where you want your keywords to appear.

Ensuring that any images have appropriate text in the value of their alt attribute also helps search engines understand the content of images. 

### Off-Page Techniques
Getting other sites to link to you is just as important as on-page techniques. Search engines help determine how to rank your site by looking at the number of other sites that link to yours.

They are particularly interested in sites whose content is related to yours. For example, if you were running a website that sold fish bait, then a link from a hairdresser is not likely to be considered as relevant as one from an angling community.

Search engines also look at the words between the opening `<a>` tag and closing `</a>` tag in the link. If the text in the link contains keywords (rather than just click here or your website address) it may be considered more relevant.

The words that appear in links to your site should also appear in the text of the page that the site links to.

## Learning about your Visitors

As soon as people start coming to your site, you can start analyzing how they found it, what they were looking at and at what point they are leaving. One of the best tools for doing this is a free service offered by Google called Google Analytics.

### Signing Up
The Google Analytics service relies on you signing up for an account at:
www.google.com/analytics
The site will give you a piece of tracking code which you need to put on every page of your site.

### How it Works
Every time someone loads a page of your site, the tracking code sends data to the Google servers where it is stored. Google then provides a web-based interface that allows you to see how visitors use your site.

### The Tracking Code
A tracking code is provided by Google Analytics for each website you are tracking. It should appear just before the closing `</head>` tag. The code does not alter the appearance of your web pages.









<br/><br/> 
<br/><br/>  



|201| [Go back Home](https://suhaib-ersan.github.io/reading-notes/) |
|-|-|
| read## | Name and Link |
| read01 | [Introductory HTML and JavaScript](https://suhaib-ersan.github.io/reading-notes/201/read01) |
| read02 | [HTML Text, CSS Introduction, and Basic JavaScript Instructions](https://suhaib-ersan.github.io/reading-notes/201/read02) |
| read03 | [HTML Lists, CSS Boxes, JS Control Flow](https://suhaib-ersan.github.io/reading-notes/201/read03) |
| read04 | [HTML Links, CSS Layout, JS Functions](https://suhaib-ersan.github.io/reading-notes/201/read04) |
| read05 | [HTML Images; CSS Color & Text](https://suhaib-ersan.github.io/reading-notes/201/read05) |
| read06 | [JS Object Literals; The DOM](https://suhaib-ersan.github.io/reading-notes/201/read06) |
| read07 | [HTML Tables; JS Constructor Functions](https://suhaib-ersan.github.io/reading-notes/201/read07)) |
| read08 | [More CSS Layout](https://suhaib-ersan.github.io/reading-notes/201/read08) |
| read09 | [Forms and JS Events](https://suhaib-ersan.github.io/reading-notes/201/read09) |
| read10 | [Debugging](https://suhaib-ersan.github.io/reading-notes/201/read10) |
| **read11** | **Audio, Video, Images** |
| read12 | [Docs for the HTML `<canvas>` Element & Chart.js](https://suhaib-ersan.github.io/reading-notes/201/read12) |
| read13 | [Local Storage](https://suhaib-ersan.github.io/reading-notes/201/read13) |
| read14 | [](https://suhaib-ersan.github.io/reading-notes/201/read14) |
| read15 | [](https://suhaib-ersan.github.io/reading-notes/201/read15) |