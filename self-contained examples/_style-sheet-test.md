# Markdown Style Examples

A page to show how all MD elements look in a given style. (H1 makes a good information map title.)

## Elements

All major elements are used, but not every flavour/method of creating
them is shown. This is not a MD primer. The structure is somewhat forced, in order to test ToC tools. (In information mapping terms, H2 makes good information block titles.)

### Label level

I use h3 for most of my working divisions in technical docs. (This and below are the label-level in information mapping.)

#### Block-quotes

> This is a block paragraph for inline
> quoting. It is given the tag "blockquote".
> > They can be nested

#### Code blocks, spans n' divs

```Python
print('Fenced code block')
print('with syntax identifier')
a = 15
```

We can also put `code inline using backticks` and make content around it.

<div class="infoBox">
**This text** is in a div with class 'infoBox' so we can see how custom class styles work.
</div>

In A-S documents <span class="callToAction">we have this 'callToAction' class</span>.

#### Text attributes

Text attributes are given these html elements: *em*, **strong**, `code`, ~~del~~

#### Jump around
<a id="jump-here" />
Many Markdown processors support custom IDs for headings — some Markdown processors automatically add them. Adding custom IDs allows you to link directly to headings and modify them with CSS.



##### Jump-testing

You can [link to the IDs](#jump-here) throughout.

### Lists, links, images, etc.

- this is an
- unordered list
  - nested item `code can sits inline in lists`
    - double nested
    1. double-nested, mixed type to numbered, may not work in all parsers

This is some more ordinary paragraph text to split lists.

1. ordered list
2. start each item with a number
  3. nested
  - nested, mixed type to bullet, may not work in all parsers

Now for [hyperlink
syntax](http://daringfireball.net/projects/markdown/syntax) and images:

![Alt-text here](https://cdn.shopify.com/s/files/1/0051/4802/products/thumb_2354dfe5-30ea-457f-ac57-194dc2c3c057_200x200_crop_center.jpg)

In certain Markdown implementations you can append =WIDTHxHEIGHT after the URL of the graphic file to resize the image. Do not forget the space before the =.

Then a HR:

------------------------------------------------------------------------

### Tables

Note the colons for alignment in this table (text version)

|Tables|Are|Cool|
|:----|:----:|----:|
|col 1|col 2|col 3|
|left-align|centered|right-align|
|another|row for|contrast|

# Headings

## H2

### H3

#### H4

##### H5

###### H6

End of file.
