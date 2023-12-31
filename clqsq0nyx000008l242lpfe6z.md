---
title: "I can't remember what that does - HTML"
datePublished: Sat Dec 30 2023 23:55:40 GMT+0000 (Coordinated Universal Time)
cuid: clqsq0nyx000008l242lpfe6z
slug: i-cant-remember-what-that-does-html
cover: https://cdn.hashnode.com/res/hashnode/image/stock/unsplash/oZuBNC-6E2s/upload/0a0d252214ff2aa1f48b39e8c36432b7.jpeg
tags: html, explanation, begginers

---

It's sometimes hard to remember what something is used for. Like our brain for instance which we always seem to forget their use. The same can be true when learning a new language. There are new words to remember and sometimes understanding what they do, can help us remember how to use them without having to google it all the time.

## Let's start with the basics.

### HTML elements.

Everything in HTML is made up of elements. every paragraph, image, or button is an element made up of an opening tag, a closing tag, and content in between. All the parts from the opening tag until the closing tag are going to be included in the element.

Some examples of elements:

```xml
<h1>Please like this post</h1>
<p>Oh, my god. Are you seriously not gonna follow my blog?</p>
<br> Nothing here.
```

### Html tags

HTML tags define the format in which the element will be displayed. If I am creating a button I will use HTML button tags. If I am creating a link I will use HTML link tags. For a container use div tags.

Some common tags:

```xml
<img></img>
<h1></h1>,<h2></h2>...
<p></p>
<html></html>
```

### HTML attributes.

Attributes go into the element opening tag affecting its behavior and look, without being visible on the webpage. Most attributes have a specific value which can vary depending on the desired outcome.

```xml
<element attribute="value"></element>
```

For example, if I have an image I want to display on my webpage, I will use the src attribute in the image's opening tag and give it a value containing the address of the image I want.

```xml
<img src="https://whotheheck_reads_the_address1324">
```

If I have a heading I could use the style attribute to give it the color red.

```xml
<h1 style="color:red">Please follow me!</h1>
```

Attributes can also provide info about a specific element:

```xml
<html lang="en"></html>
```

This helps the browser recognize the language of the page.