# Intro to HTML & CSS

#### Review of CodeAcademy's HTML & CSS course

Resources
- HTML glossary: http://www.codecademy.com/glossary/html
- CSS glossary: http://www.codecademy.com/glossary/css

HTML
- "Hypertext Markup Language"
- The language of web pages
- Adds structure and meaning to content
- In principle, a blind person should be able to understand the structure and meaning of your web page if you explain the markup.

```html
    <title>Access Code 2.1</title>
```

CSS
- "Cascading Style Sheets"
- Multiple selectors can target the same HTML; precedence rules decide which selector is applied.

```css
title {
    color: red;
}
```

> Exercise: 

#### Block, inline, inline-block

The display property has three possible values: `inline`, `block`, and `inline-block`:

Inline
- Width/height cannot be set
- Allow other elements to sit to their left and right
- Respect left/right padding/margin but not top/bottom

Block
- Forces a line break after the block element
- Width/height, margin/padding can all be set

Inline-block
- Allow other elements to sit to their left and right
- Top/bottom padding/margins can be set
- Width/height can be set

> **Exercise:** Take the following quote and use inline elements to stylize every instance of the word "information":

> "On the one hand information wants to be expensive, because it's so valuable. The right information in the right place just changes your life. On the other hand, information wants to be free, because the cost of getting it out is getting lower and lower all the time. So you have these two fighting against each other."

#### Padding and margins

#### Positioning

`position` values
- `static`: position element in order, in document flow
- `absolute`: position element relative to top-left of page
- `fixed`: position element in a fixed location on page
- `relative`: position the element relative to its default position

> **Exercise:** Create a fixed navigation bar.

#### Float and clear

`float` values
- `left`: float element left
- `right`: float element right

`clear` values
- `left`: clears a left float
- `right`: clears a right flow
- `both`: clears both

# In-class assignment
Work in teams of four to build a weather/alarm clock.

# Homework assignment
[Here](https://github.com/C4Q/ac15-bootcamp/blob/master/assignment.md)


