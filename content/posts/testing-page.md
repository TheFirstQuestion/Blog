---
title: "Testing Page"
date: 2020-03-30T15:24:31-04:00
draft: false
tags: ["To Delete"]
summary: "The *Hello, World* of this blog."
---


# heading1
## heading2
### heading3
#### heading4
##### heading5
###### heading6

___
## Text

That was a horizontal line. This is a paragraph.

This is a paragraph with **bold**, *italic*, and ~~struck-through~~ text.

___
## Lists

1. First ordered list item
2. Another item
  * Unordered sub-list.
1. Actual numbers don't matter, just that it's a number
  1. Ordered sub-list
4. And another item.

   You can have properly indented paragraphs within list items. Notice the blank line above, and the leading spaces (at least one, but we'll use three here to also align the raw Markdown).

   To have a line break without a paragraph, you will need to use two trailing spaces.  
   Note that this line is separate, but within the same paragraph.  
   (This is contrary to the typical GFM line break behaviour, where trailing spaces are not required.)

* Unordered list can use asterisks
- Or minuses
+ Or pluses

___
## Links
[I'm an inline-style link](https://www.google.com)

[I'm an inline-style link with title](https://www.google.com "Google's Homepage")

[I'm a reference-style link][Arbitrary case-insensitive reference text]

[You can use numbers for reference-style link definitions][1]

Or leave it empty and use the [link text itself].

URLs and URLs in angle brackets will automatically get turned into links.
http://www.example.com or <http://www.example.com> and sometimes
example.com (but not on Github, for example).

Some text to show that the reference links can follow later.

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: http://slashdot.org
[link text itself]: http://www.reddit.com

___
## Code
Inline `code` has `back-ticks around` it.

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
## Tables
| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

There must be at least 3 dashes separating each header cell.
The outer pipes (|) are optional, and you don't need to make the
raw Markdown line up prettily. You can also use inline Markdown.

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3

___
## Blockquotes
{{< quote >}}
Blockquotes are very handy in email to emulate reply text.  
This line is part of the same quote.
{{< /quote >}}

Quote break.

{{< quote >}}
This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can *put* **Markdown** into a blockquote.
{{< /quote >}}

___
## Borders
{{< border >}}
Regular
{{< /border >}}

{{< border "dashed" >}}
Dashed
{{< /border >}}

{{< border "dotted" >}}
Dotted
{{< /border >}}

{{< border "dashed thick" >}}
Dashed Thick
{{< /border >}}

{{< border "dotted thick" >}}
Dotted Thick
{{< /border >}}

___
## Color
{{< color "primary" >}}
Text primary
{{< /color >}}

{{< color "secondary" >}}
Text secondary
{{< /color >}}

{{< color "success" >}}
Text success
{{< /color >}}

{{< color "warning" >}}
Text warning
{{< /color >}}

{{< color "danger" >}}
Text danger
{{< /color >}}

{{< color "muted" >}}
Text muted
{{< /color >}}

___
## Backgrounds
{{< background "primary" >}}
Background primary
{{< /background >}}

{{< background "secondary" >}}
Background secondary
{{< /background >}}

{{< background "success" >}}
Background success
{{< /background >}}

{{< background "warning" >}}
Background warning
{{< /background >}}

{{< background "danger" >}}
Background danger
{{< /background >}}
___
## Alerts
{{< alert "primary" >}}
Alert-primary
{{< /alert >}}

{{< alert "secondary" >}}
Alert-secondary
{{< /alert >}}

{{< alert "success" >}}
Alert-success
{{< /alert >}}

{{< alert "warning" >}}
Alert-warning
{{< /alert >}}

{{< alert "danger" >}}
Alert-danger
{{< /alert >}}
___
# Badges
<h3>Example badge {{< badge >}}123{{< /badge >}}</h3>

<h3>Example badge {{< badge "secondary" >}}123{{< /badge >}}</h3>

<h3>Example badge {{< badge "success" >}}123{{< /badge >}}</h3>

<h3>Example badge {{< badge "warning" >}}123{{< /badge >}}</h3>

<h3>Example badge {{< badge "danger" >}}123{{< /badge >}}</h3>
