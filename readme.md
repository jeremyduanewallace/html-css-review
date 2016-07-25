# HTML/CSS Review

This is a review of your working knowledge of HTML and CSS. Note that this review is designed to help you recall and familiarize yourself with technical concepts.

## Getting Started

* Fork and clone this repository
* Answer the following questions by...
  * Opening this file in Sublime
  * Answering the questions via Markdown. Feel free to refer to this [Markdown Cheat Sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
* Commit your changes
* Make a pull request for submission

---

## HTML

1.) Create a valid, empty HTML page with the necessary tags.

```html
<!-- Code goes here -->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Document</title>
</head>
<body>
  
</body>
</html>
```

2.) What are the differences between these tags?

```html
<!-- Tag 1 -->
<img src="images/me.jpg" alt="My profile image">

<!-- Tag 2 -->
<div></div>
```

```
Explain here.
```
img tag is a inline element and div is a block element 

---

## CSS

1.) Compare and contrast the following ways to add CSS to HTML elements.

```html
<!-- Inline CSS -->
<div style="background-color: red;"></div>

<!-- Internal style sheet -->
<style type="text/css">
  div {
    background-color: red;
  }
</style>

<!-- External style sheet (not shown) -->
<link rel="stylesheet" type="text/css" href="css/style.css">
```

```
Explain here
```
inline css is directly applied to a element inline on the html document.

internal css is applied to the html document in the head between script tags.

external css is apllied in a .css file and can be applied to more than one html file.


2.) Below are some different CSS selectors. Use CSS comments to describe what each selector will do.

```css
/* this will select all div elements on the html page */
div {
  border-radius: 50%;
}

/* this will select all p tags nested inside parent element with a .header class*/
.header p {
  font-size: 18px;
}

/* will select all .footer classes and apply the css*/
.footer {
  position: absolute;
  bottom: 0;
}

/*will select all .splash-image classes and apply the css*/
.splash-image {
  background-image: url("../images/ocean.jpg");
  background-size: cover;
  width: 100%;
}

/*this will select all .ninja classes in the hoover state*/
.ninja:hover {
  display: none;
  color: black;
}
```


---

## Licensing
1. All content is licensed under a CC-BY-NC-SA 4.0 license.
2. All software code is licensed under GNU GPLv3. For commercial use or alternative licensing, please contact legal@ga.co.
