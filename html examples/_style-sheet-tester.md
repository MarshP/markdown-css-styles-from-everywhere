# Markdown Style Examples (H1)

A page to show how all MD elements look in a style.

## MD Elements (H2)

All major elements are used, but not every flavour/method of creating them is shown. `Have some inline code.` This is not a MD primer. 

### Block-ish level (h3)

I use h3 for most of my working divisions technical docs. 

> This is a block paragraph for inline  
> quoting. It is given the tag "blockquote".
> 
> > They can be nested

#### Code blocks n' divs (h4)

```Python
print('Fenced code block')
print('with syntax identifier')
a = 15
```
On we go...

<div class="infoBox">
**This text**  is in an Active Steward user documents 'infoBox' div.
</div>

### Inline-ish level (h3)

Text attributes are given these html elements: _em_, **strong**, `code`, ~~strike~~

##### Small stuff (h5) 
<span id="jump_here"></span>

In Active Steward user documents <span class="callToAction">we have this &#39;call to action&#39; class</span>.  

###### Smallest stuff (h6)

In all versions you can insert a id ref then [link to it](#jump_here) 

### Lists, images, etc.

-   this is an
-   unordered list
    -   nested item `code sits inline list` 
	    - double nested
	    1. double-nested, mixed type to numbered

This is some more ordinary paragraph text to split lists.

1. ordered list
2. start each item
  3. nested
  - mixed type to bullet

Now for [hyperlink syntax](http://daringfireball.net/projects/markdown/syntax) and images:

![Alternative text](https://staging.activesteward.com/images/AS-logo.png)

Then a HR:

----------

### Tables

Note the colons for alignment in this table (text version)

|Tables|Are|Cool|
|:----|:----:|----:|
|col 1|col 2|col 3|
|left-align|centered|right-align|
|another|row|for contrast|

# Headings hierachy
## H2
### H3
#### H4
##### H5
###### H6

End of file.
