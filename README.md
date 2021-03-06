![CF](https://camo.githubusercontent.com/70edab54bba80edb7493cad3135e9606781cbb6b/687474703a2f2f692e696d6775722e636f6d2f377635415363382e706e67) Lab 03: jQuery Events
===

## Code Wars Challenge

Complete [today's Kata](https://www.codewars.com/kata/insert-dashes) and follow the submission instructions from Lab 01.

## Lab 03 Submission Instructions
Follow the submission instructions from Lab 01.

## Resources  
[jQuery cheatsheet](https://oscarotero.com/jquery/)

[Template Literals MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Template_literals)

## Configuration
_Your repository must include:_

```
03-jquery-with-events
├── .eslintrc.json
├── .gitignore
├── LICENSE
├── README.md
├── index.html
├── scripts
│   ├── article.js
│   ├── articleView.js
│   └── blogArticles.js
├── styles
│   ├── base.css
│   ├── fonts
│   │   ├── icomoon.eot
│   │   ├── icomoon.svg
│   │   ├── icomoon.ttf
│   │   └── icomoon.woff
│   ├── icons.css
│   ├── layout.css
│   └── modules.css
└── vendor
    └── styles
        └── normalize.css
```

## User Stories and Feature Tasks

- Continue styling the app using SMACSS practices. Take a few minutes for code review of your partner's CSS and decide how to incorporate it into your paired lab. You can choose one partner's CSS structure, or you can combine them as you see fit. Seek to optimize and organize your CSS as much as possible!

*As a user, I want to be able to filter my articles so that I can selectively view articles by author or by category.*

- Complete the new requirements for setting `data-<attributes>` in your `toHtml()` method.
- Complete the methods for handling filter events when selecting an option from a drop down menu via Authors and Categories so that only the selected articles are displayed on the screen.

*As a user, I want to be able to preview each article so that I can easily view the results and select the one I want to read further.*

- Add an event to reveal a complete article if the user would like to see more of it beyond the teaser.

*As a user, I want tab-based navigation so that I can easily visit other sections of my site.*

- Complete the method `articleView.handleMainNav()` for implementing tab-based event navigation on the page.

*As a developer, I want my code to be thoughtfully organized, easy to read, and executing efficiently.*

- Review and understand the new JS file, `articleView.js`
- Add any new script tags to your HTML.
- Refactor concatenation using template literals.
- Render the app upon page load.

### Stretch Goal

*As a user, I want to be able to collapse an expanded article to the teaser view so that I can more easily scan over a series of articles.*

- Build in functionality such that a user can click on "Show Less" to collapse a full article into a teaser.

## Documentation
_Your README.md must include:_

```md
# Project Name

**Author**: Wyatt Pefley
**Version**: 1.0.0 (increment the patch/fix version number up if you make more commits past your first submission)

## Overview
This is an application that filters blog posts based on user input using Jquery and JavaScript/

## Getting Started
1. Fork repo on GitHub.
2. Copy repo to local machine.
3. read through code to understand what each piece is doing.
4. Read commented instructions and follow them.
5. ACP
6. Use Jquery cheat sheet and Jquery Docs as resources

## Architecture
This application uses HTML, CSS, and JavaScript with the Jquery library imported.
We use HTML and CSS for the front end work, and use Javascript and Jquery for back and work and DOM traversal, selection, and manipulation.

## Change Log
<!-- Use this are to document the iterative changes made to your application as each feature is successfully implemented. Use time stamps. Here's an examples:

9:00 - began reading through codebase
9:10 - Began commenting where the instructions said
9:20 - Began creating template literals
10:00 - Adding event handlers
## Credits and Collaborations
Wyatt Pefley
-->
```
