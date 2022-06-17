# refactoring-horiseon
This project __refactors the code for an existing website__, Horiseon, to make it more accessible to clients. The refactored code responds to the user story by meeting the acceptance criteria. Here is the user story, acceptance criteria, and the mock-up of the website for background.
## User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```
## Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```
## Website
This is the mock-up of the website that needed its code to be refactored.

![Horiseon website](./assets/images/01-html-css-git-homework-demo.png)

## Solution In Detail
Essentially, refactored code fixes the source code by:
* renaming website's title as `Horiseon` to be more specific and relevant to user
* replacing `<div>` with proper semantic HTML elements such as `<main>`, `<header>`, `<nav>`, `<figure>`, `<section>`, `<article>`, `<aside>`, and `<footer>`
* adding alternate text to all images
* creating `class` and `id` tags to remove redundant codes in `style.css`
* reorganizing `style.css` in top-down format
* inserting quality comments to describe certain sections of the code

## Screenshot of Solution
This screenshot is an example of the before-and-after refactored code within the `index.html`.
![Screenshot of fixes](./assets/images/screenshot.png)

> **Note**: All of the fixes does not alter the website's appearance in any way.

## How to Run Project
1. Go to  this [respository](https://github.com/christylex3/refactoring-horiseon) on GitHub.
2. Clone it to your computer.
3. Find the `index.html` within the `refactoring-horiseon` folder and open it with Visual Studio Code.
4. Then launch the `index.html` file to see the website, which should look like [this](https://christylex3.github.io/refactoring-horiseon/).

## Credits
https://www.w3schools.com/html/html5_semantic_elements.asp
