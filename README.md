# 30 days of react

This is a project to document learning for a crash course in React

It is based on the book "30 Days of React" from FullStack.io

## Lesson 1

Lesson one covered the basic introduction to React and its reliance on the concept of the virtual DOM.

## Lesson 2

Lesson two introduced the concept of extending Javascript to represent HTML, and how this can be written in ECMAScript 6 and then transpiled to ECMAScript 5.

## Lesson 3

In Lesson three I created my first React Component, a simple H1 tag with Hello World. I took the latest libraries from the React website and used the example in the book. At first I omitted the babel library to see if it is needed in my environment. I ran the code using the live preview of Brackets.io which served the page in chrome. On first try it did not work. Including the script tag for babel resolved this issue.

## Lesson 4
Lesson four introduced the concept of breaking down a page into sub components. Then it shows how these components can be represented in their own class, and the components can be nested within other components. This is done by using the class name as its own single HTML tag, e.g. <MyComponent />

### Lesson 4.5
Ok so minor slip up here, because the example in the book didn't show the binding of the app class to the app div, I assumed it should be left out and carried on to lesson 5. I then got curious and tried to run my code. It. Did. Not. Work. I discovered the hard way that className must be camel-cased, and also that the render function must have a return statement and that basically all the html sits within this return statement. The link for an avatar image does not work, also the book does not include any CSS so I think I will add my own before progressing onto chapter 5.