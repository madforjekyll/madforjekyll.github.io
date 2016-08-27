---
layout: post
title: Markdown Cheatsheet
subtitle: This is Markdown Cheatsheet for MAD4Jekyll
date:       2015-11-25 12:00:00
author:     "MADness"
header-img: "assets/owner/blog/header/post-bg-02.jpg"
thumbnail: /assets/owner/blog/thumbs/thumb02.png
tags: [tag-name-one, tag-name-two]
categories: [cat01, cat02]
---

> This is Markdown Cheatsheet for **MAD4Jekyll**, this Jekyll theme. Please check the raw content of this file for the markdown usage.

## Typography Elements

This is a paragraph. **This text is bolded.** This text is normal! _This text is italic._ We can  also **_combine_** them. A highlighted code looks like `ThisIsMyCode()`. This text is a [hyperlink](#) or [http://www.example.com](http://www.example.com).

___

## Headings H1 to H6

# H1 Heading

## H2 Heading

### H3 Heading

#### H4 Heading

##### H5 Heading

###### H6 Heading

___

## Footnote

If you have some text that you want to refer with a footnote, do as follows. This is an example for the footnote number one [^1]. Add more footnotes, with link. [^2]

___

## Blockquote

> The roots of education are bitter, but the fruit is sweet. --Aristotle

___

## List Items

1. First order list item
2. Second item

* Unordered list can use asterisks
- Or minuses
+ Or pluses

___

## Code Blocks

```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```

```python
s = "Python syntax highlighting"
print s
```

```
No language indicated, so no syntax highlighting.
But let's throw in a <b>tag</b>.
```

___


## Table

### Table 1: With Alignment

| Tables        | for           | Markdown  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | ok? |
| col 2 is      | centered      |   Got it? |
| col 1 is | left-aligned      |    Alright!!! |

### Table 2: With Typography Elements

Another | table | here
--- | --- | ---
*I* | `am` | **row**
1 | two | III

___

## Horizontal Line

The HTML `<hr>` element is for creating a "thematic break" between paragraph-level elements. In markdown, you can create a `<hr>` with any of the following:

* `___`: three consecutive underscores
* `---`: three consecutive dashes
* `***`: three consecutive asterisks

renders to:

___

---

***

<br>

## Media

### YouTube Embedded Iframe

<iframe width="560" height="315" src="https://www.youtube.com/embed/OuoaKai_L00" frameborder="0" allowfullscreen></iframe>

<br>

### Image

![Spectrocat](http://octodex.github.com/images/spectrocat.png)

<br>

## For a more detailed syntax with Markdown, please visit [DaringFireball.net](http://daringfireball.net/projects/markdown/syntax)

###### Image Source: [UNSPLASH](https://unsplash.com/photos/6g0KJWnBhxg)


[^1]: Footnote number one.

[^2]: A footnote you can link to - [click here!](#)
