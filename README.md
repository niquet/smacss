# Learn About SMACSS And FUN :zap:

It is fairly correct to say, when working on big projects or with groups of developers, code can get messy, hard to read, and even hard to extend after a while.
These issues play a role in frontend development too. This repository aims to show you a neat way of organizing your css code, hoping that it will make your next project easier to maintain and extend.

Whether it is a side project, a new CSS frontend framework or even a CSS design system you're working on, SMACSS and FUN are some great ways of getting structure and meaning into your code.

## So, What Exactly is SMACSS?

SMACSS stands for **Scalable** and **Modular Architecture** for **CSS**. It is an architecture to help style code and make CSS more readable or as Slobodan Gajic put it in his [Toptal read](https://www.toptal.com/css/smacss-scalable-modular-architecture-css): *"It’s a particular set of CSS architecture guidelines from Jonathan Snook[...]. Now, the architectural approach of SMACSS is a bit different from a CSS framework like Bootstrap or Foundation. Instead, it’s a set of rules, more like a template or guide."* 

<img width="1000" src="https://github.com/niquet/smacss/blob/main/smacss_overview.png">

In SMACSS, styles are divided into 5 parts with each part being represented as either a section in a very long CSS file or as a CSS file of their own. You can think of a style as a category, or guide of what goes into said section / CSS file.

### 1. Base 

Base rules / styles define what an element should look like anywhere on the page.These are the styles of the main website elements - defaults if you want - like body, input, button, ul, ol, etc. In 

### Layout

### Modules

### State

### Theme

**Key Takeaways, so far :bulb:**
```
:bulb:
```

## And, What is FUN?

**Key Takeaways, so far :bulb:**
```
:bulb:
```

## Mehod of Organizing CSS

*SMACSS* stands for Scalable and Modular Architecture for CSS. The main goal of the approach is to reduce the amount of code and simplify code support.

*Jonathan Snook* divides styles into 5 parts:

1. **Base rules.** These are styles of the main website elements – body, input, button, ul, ol, etc. In this section, we use mainly HTML tags and attribute selectors, in exceptional cases – classes (for example, if you have JavaScript-style selections);
2. **Layout rules.** Here are the styles of global elements, the size of the cap, footer, sidebar, etc. Jonathan suggests using id here in selectors since these elements will not occur more than 1 time on the page. However, the author of the article considers this a bad practice (whenever an id appears in the styles, somewhere in the world the kitten is sad).
3. **Modules rules.** Blocks that can be used multiple times on a single page. For module classes, it is not recommended to use id and tag selectors (for reuse and context independence, respectively).
4. **State rules.** In this section, the various statuses of the modules and the basis of the site are prescribed. This is the only section in which the use of the keyword “! Important” is acceptable.
5. **Theme rules.** Design styles that you might need to replace.
It is also recommended to enter the namespace for classes belonging to a certain group, and also to use a separate namespace for the classes used in JavaScript.

This approach makes it easier to write and maintain code, and has attracted a large number of developers.
