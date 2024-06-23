# Markdown Cheat Sheet

This Markdown cheat sheet provides a quick overview of all the Markdown syntax elements.

# Headings

- # Heading H1
- ## Heading H2
- ### Heading H3
- #### Heading H4
- ##### Heading H5
- ###### Heading H6

# Underlines

Underline 1
---

Underline 2
===

# Emphasis formats

### Basic formats

- *italic* format of the first form.
- _italic_ format of the second way.
- **bold or strong** format of the first form.
- __bold or strong__ format of the second way.
- ~~strikethrough~~ format, normal format.
- here we can use *italic formatting*, but also **bold** and ~~strikethrough~~.
- here we can use all ***~~italic, bold and strikethrough~~***.

### More specialized formats

Not in all cases the markdown format will apply, only in some editors.

- This is the HTML format to <mark>highlight</mark> a word.
- This is the markdown format to ==highlight== a word.
- This is the HTML format to subscript H<sub>2</sub>O a word.
- This is the markdown format to subscript H~2~O a word.
- This is the HTML format to superscript X<sup>2</sup> a word.
- This is the markdown format to superscript X^2^ a word.
- This is the way to use emojis :joy:.

# Lists

### Ordered List

1. First item
2. Second item
3. Third item

### Unordered List

- First item
- Second item
- Third item

# Blockquotes

This is a text referring to a quote that we will put below:

> This is a quote.

This is another text that is not related to the previous quote.

> This is another quote.


# Links

- <a href="http://google.com">This is an HTML link</a>
- [This is a link in Markdown](http://google.com)
- [This is a link to the index](index.html)

# Images

![Any Logo](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png)

![GitHub Logo](images/GitHub-logo.png)

# Code

### JSON code

```JSON
[
    {
        "title": "apples",
        "count": [12000, 20000],
        "description": {"text": "...", "sensitive": false}
    },
    {
        "title": "oranges",
        "count": [12000, null],
        "description": {"text": "...", "sensitive": false}
    },
]
```

### Javascript code

```Javascript
function $initHighlight(block, cls) {
  try {
    if (cls.search(/\bno\-highlight\b/) != -1)
      return process(block, true, 0x0F) +
             ` class="${cls}"`;
  } catch (e) {
    /* handle exception */
  }
  for (var i = 0 / 2; i < classes.length; i++) {
    if (checkCondition(classes[i]) === undefined)
      console.log('undefined');
  }

  return (
    <div>
      <web-component>{block}</web-component>
    </div>
  )
}

export  $initHighlight;
```

# Tables

|  Name  |  Surname  | Document |
| ------ | --------- | -------- |
| Maxi   | Burgos    | 3546481  |
| Tomas  | Tompson   | 3243243  |

