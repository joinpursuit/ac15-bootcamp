# Intro to HTML & CSS

#### Review of CodeAcademy's HTML & CSS course

HTML
- Glossary: http://www.codecademy.com/glossary/html
- "Hypertext Markup Language"
- The language of web pages
- Adds structure and meaning to content
- In principle, a person should be able to understand the structure and meaning of your web page without being able to see it.

```html
    <title>Access Code 2.1</title>
```

CSS
- Glossary: http://www.codecademy.com/glossary/css
- "Cascading Style Sheets"
- Adds style to the page
- Multiple selectors can target the same HTML; precedence rules decide which selector is applied.

```css
title {
    color: red;
}
```

> **Exercise:** ???

#### Padding and margins



#### Block, inline, inline-block

The `display` property has three possible values: `inline`, `block`, and `inline-block`:

**Inline**
- `width` and `height` cannot be set
- Allows other elements to sit to their left and right
- Respect left/right padding/margin but not top/bottom

**Block**
- Forces a line break after the block element
- `width`, `height`, `margin`, and `padding` can all be set

**Inline-block**
- Allows other elements to sit to their left and right
- `width`, `height`, `margin`, and `padding` can all be set

> **Exercise:** Take the quote below and stylize every instance of the word "information". Create a line break as in the quote. Here is an example:
>
> ![information](images/information.png)
>
> *"On the one hand information wants to be expensive, because it's so valuable. The right information in the right place just changes your life.*
>
> *"On the other hand, information wants to be free, because the cost of getting it out is getting lower and lower all the time. So you have these two fighting against each other."*

#### Positioning

**Position**
- `static`: position element in order, in document flow (cannot set `top`, `bottom`, `left,` or `right`)
  ![static](images/static.png)

- `relative`: position the element relative to its default position
  ![relative](images/relative.png)

- `absolute`: position element relative to top-left of page
  ![absolute](images/absolute.png)

- `fixed`: position element in a fixed location on page
  ![fixed](images/fixed1.png)
  ![fixed](images/fixed2.png)

> **Exercise:** Create a fixed navigation bar. See this example:
>
> ![nav1](images/nav1.png)
>
> ![nav2](images/nav2.png)

#### Float and clear

**Float**
- `left`: float element left
- `right`: float element right

**Clear**
- `left`: clears a left float
- `right`: clears a right flow
- `both`: clears both

> **Exercise:** Create a page with four sections: two horizontal sections with two equal-width sections in between. See the example below. Don't use a `table` tag. Use `float` and `clear`.
>
> ![float-clear](images/float-clear.png)

#### Custom fonts

# In-class assignment
Work in teams of four to build a weather/alarm clock.

# Homework assignment
[Here](https://github.com/C4Q/ac15-bootcamp/blob/master/assignment.md)


