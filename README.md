# 21-design-components

Mission objectives
You work in a Web Design agency as Frontend Integrator. The UI Designer provides you with 22 images, each representing a high-fidelity mockup of the website's interface component. Your job is to reproduce in html and CSS each of these components. Each UI component has been validated by your customer. It's therefore really important that the end-result looks as close as possible to the mockups.

Instructions
Create as many html/css templates as there are UI Components and try to reproduce the interface as close as possible. The HTML has to be valid, semantic and abide to the Progressive Enhancement approach. With your css skills, reach the closest "pixel-perfect" version you can. Ideally, we should not see any difference between the image mockup and your result, without using any image. Images are only accepted for illustrations, when there is no CSS alternative.
Start with number 1 and work your way until the last.
Each UI component should be responsive (you are free to decide how exactly the screen should reflow) over 2 breakpoints: 480 and 768 pixel-width.
Use the html5boilerplate as a starting basis.
Given the amount of code you will reuse, use SASS, and organize your SCSS partials so as to stay orderly. Need ideas ? Read on how others are doing it. You probably should also read about Block, Element, Modifier (BEM) Methodology (en) or the SMACSS approaches, often referred to in the industry. Use variables, nesting and @import.
This file structure would be a good basis:
- UI-component-name/
    L index.html
    L assets
        L css
        L sass
        L img
