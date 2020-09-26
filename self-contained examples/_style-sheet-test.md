---
uid: uid_of_the_file_for_cross_refs
title: Markdown Style Examples
author: MarshP
---

<!-- Start Document Outline -->

* [Markdown Style Examples](#markdown-style-examples)
	* [Elements in This Doc](#elements-in-this-doc)
		* [H3 == label level](#h3--label-level)
			* [Block-quotes](#block-quotes)
			* [Code blocks](#code-blocks)
	* [Spans n' Divs n' Icons](#spans-n-divs-n-icons)
	* [Text Attributes](#text-attributes)
		* [Jump around](#jump-around)
	* [Lists](#lists)
	* [Links](#links)
		* [Images and media](#images-and-media)
	* [Tables](#tables)
	* [Other Extensions](#other-extensions)
		* [Figure and caption](#figure-and-caption)

<!-- End Document Outline -->

# Markdown Style Examples

A somewhat-realistic page to show how all MD elements look with a given stylesheet. (A common project convention is to use H1 only as title, not in intra-document headings. H1 makes a good information map title.) 
## Elements in This Doc

All major elements are used, but not every flavour/method of creating
them is shown. This is not a MD primer. The structure is somewhat forced, in order to test ToC tools. (H2 makes a good information block title.)

### H3 == label level

Use h3 for most working divisions in technical docs. (This is label-level in information mapping.)

#### Block-quotes

> This is a block paragraph for inline
> quoting. It is given the tag "blockquote".
> > They can be nested

#### Code blocks

```Python
print('Fenced code block')
print('with syntax identifier')
a = 15
```

We can also put `code inline using backticks` and make content around it.

## Spans n' Divs n' Icons

<div class="infoBox">
**This text** is in a div with class 'infoBox' so we can see how custom class styles work. Examples in this section will be plain if the the css lacks this class
</div>

In A-S documents <span class="callToAction">we have this 'callToAction' class</span>.

:::callToAction
Some flavours allow creating or using a div class on the fly
:::

<span style="color: green; border: 1px dashed;">This span has inline styling.</span>

Some parsers will put font-awesome icons here: <i class="fa fa-eye fa-fw"></i><i class="fa fa-pencil fa-fw"></i>

Most allow emoji :red_car:

> [!Warning]
> Some flavours support Note, Tip, Warning, Important and Caution blockquotes with in-built styling and icons. 

## Text Attributes

Text attributes are given these html elements: *em*, **strong**, `code`, ~~del~~

Extended flavours provide these html elements: ==mark==, ++ins++, ~sub~, ^sup^. (Plain if not supported in the flavour/stylesheet used.)

### Jump around
<a id="jump-here"></a>
Many Markdown processors support custom I.Ds for headings — some Markdown processors automatically add them. Some add them but change to slug-style-wording (GitHub flavour). If not, adding custom I.Ds allows you to link directly to headings and modify them with CSS.

You can link to [slug-style auto-generated I.Ds](#jump-around) or [link to your personal I.Ds](#jump-here) throughout.

Here is a footnote reference,[^1] and another.[^longnote]

## Lists

* Unordered lists can use an asterisk, like these nested items:
  * Barry Bonds
  * Mark McGwire
  * Astros 2019
 
---

- Unordered lists can use a dash
  - `code can sits inline in lists`
    - double nested items are possible
 
---

1. Make an ordered list
2. Start each item with a number (parsers will correct numbering)
  * nest an item, mix type to bullet (may not work in all parsers)
3. Some parsers allow a. i., etc.
  i. lower roman nested
  ii. works in some parsers
  iii. remember your roman
  iv. numerals!
4. Test lower latin items
  a. lower latin test
  b. works with some parsers
 
---

- [ ] To do items
- [x] From GH flavoured markdown

---

Click this Definition List definition
:   This is a definition item
:   Some flavours will fold it

## Links

There are three common styles for links. First, obviousy, just a URL which some flavours link automatically:

https://www.marsh.org.uk

[Link text with link address elsewhere][link-at-doc-end]

[Link text with link inline](https://www.marsh.org.uk)

### Images and media

Now for media and images, some flavours embed media:

![youtube.com](https://www.youtube.com/watch?v=mswPy5bt3TQ)

*[MD]: Markdown

Here a abbr. is defined and when used below will have hover text: MD

![Alt-text-here](https://upload.wikimedia.org/wikipedia/commons/thumb/5/51/Octicons-markdown.svg/128px-Octicons-markdown.svg.png)

In certain Markdown implementations you can append =WIDTHxHEIGHT after the URL of the graphic file to resize the image. Do not forget the space before the =.

## Tables

Note the colons for alignment in this table (text version)

|Tables|Are|Cool|
|:----|:----:|----:|
|col 1|col 2|col 3|
|left-align|centered|right-align|
|another|row for|contrast|

## Other Extensions

#### Figure and caption

These are in some flavours. Also below are the final heading samples.

^^^
![Alt-text-here](https://upload.wikimedia.org/wikipedia/commons/thumb/5/51/Octicons-markdown.svg/128px-Octicons-markdown.svg.png)
^^^ Caption - Markdown icon

##### Maths

$$
\begin{equation}
  \int_0^\infty \frac{x^3}{e^x-1}\,dx = \frac{\pi^4}{15}
  \label{eq:sample}
\end{equation}
$$

###### Footnotes

[^1]: Here is the footnote.
[^longnote]: Here's another footnote..

[link-at-doc-end]: https://www.marsh.org.uk

End of file - note the footnotes may appear below this in html even if above them in raw MD.
