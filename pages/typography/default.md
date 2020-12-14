---
title: Typography
---

! Details on the full capabilities of Spectre.css can be found in the [Official Spectre Documentation](https://picturepan2.github.io/spectre/elements.html)

The [Quark theme](https://github.com/getgrav/grav-theme-quark) is the new default theme for Grav built with [Spectre.css](https://picturepan2.github.io/spectre/) the lightweight, responsive and modern CSS framework. Spectre provides basic styles for typography, elements, and a responsive layout system that utilizes best practices and consistent language design.

metadata

### Headings

# H1 Heading `40px`

## H2 Heading `32px`

### H3 Heading `28px`

#### H4 Heading `24px`

##### H5 Heading `20px`

###### H6 Heading `16px`

```html
# H1 Heading
# H1 Heading `40px`</small>`

<span class="h1">H1 Heading</span>
```

### Paragraphs

Lorem ipsum dolor sit amet, consectetur [adipiscing elit. Praesent risus leo, dictum in vehicula sit amet](#), feugiat tempus tellus. Duis quis sodales risus. Etiam euismod ornare consequat.

Climb leg rub face on everything give attitude nap all day for under the bed. Chase mice attack feet but rub face on everything hopped up on goofballs.

### Markdown Semantic Text Elements

**Bold** `**Bold**`

*Italic* `_Italic_`

~~Deleted~~ `~~Deleted~~`

`Inline Code` `` `Inline Code` ``

### HTML Semantic Text Elements

I18N `<abbr>`

Citation `<cite>`

Ctrl + S `<kbd>`

TextSuperscripted `<sup>`

TextSubscripted `<sub>`

Underlined `<u>`

Highlighted `<mark>`

20:14 `<time>`

x = y + 2 `<var>`

### Blockquote

> The advance of technology is based on making it fit in so that you don't really even notice it,
> so it's part of everyday life.
> 
> - Bill Gates

```
> The advance of technology is based on making it fit in so that you don't really even notice it,
> so it's part of everyday life.
>
> <cite>- Bill Gates</cite>
```

### Unordered List

*   list item 1
*   list item 2
    *   list item 2.1
    *   list item 2.2
    *   list item 2.3
*   list item 3

```
* list item 1
* list item 2
    * list item 2.1
    * list item 2.2
    * list item 2.3
* list item 3
```

### Ordered List

1.  list item 1
2.  list item 2
    1.  list item 2.1
    2.  list item 2.2
    3.  list item 2.3
3.  list item 3

```
1. list item 1
1. list item 2
    1. list item 2.1
    1. list item 2.2
    1. list item 2.3
1. list item 3
```

### Table

| Name | Genre | Release date |
| --- | :-: | --: |
| The Shawshank Redemption | Crime, Drama | 14 October 1994 |
| The Godfather | Crime, Drama | 24 March 1972 |
| Schindler's List | Biography, Drama, History | 4 February 1994 |
| Se7en | Crime, Drama, Mystery | 22 September 1995 |

```
| Name                        | Genre                         | Release date         |
| :-------------------------- | :---------------------------: | -------------------: |
| The Shawshank Redemption    | Crime, Drama                  | 14 October 1994      |
| The Godfather               | Crime, Drama                  | 24 March 1972        |
| Schindler's List            | Biography, Drama, History     | 4 February 1994      |
| Se7en                       | Crime, Drama, Mystery         | 22 September 1995    |
```

### Notices

The notices styles are actually provided by the `markdown-notices` plugin but are useful enough to include here:

! This is a warning notification

!! This is a error notification

!!! This is a default notification

!!!! This is a success notification

```
! This is a warning notification

!! This is a error notification

!!! This is a default notification

!!!! This is a success notification
```
