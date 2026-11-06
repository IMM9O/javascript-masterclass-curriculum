<h1 align="center">JavaScript Masterclass Curriculum</h1>

<p align="center">A free, step-by-step path to master JavaScript, from how the language runs to the APIs of the web platform.</p>

<p align="center">
  <a href="https://github.com/imm9o/javascript-masterclass-curriculum/actions/workflows/links.yml"><img src="https://github.com/imm9o/javascript-masterclass-curriculum/actions/workflows/links.yml/badge.svg" alt="Link check"></a>
  <a href="https://github.com/imm9o/javascript-masterclass-curriculum"><img src="https://img.shields.io/github/stars/imm9o/javascript-masterclass-curriculum?style=flat" alt="Stars"></a>
</p>

<p align="center">
  <img src="https://images.unsplash.com/photo-1517446915321-65e972f1b494?auto=format&fit=crop&w=1200&q=80" alt="Laptop with code on the screen">
  <br>
  <sub>Photo by <a href="https://unsplash.com/@paulamayphotography">Paula May</a> on <a href="https://unsplash.com/">Unsplash</a></sub>
</p>

JavaScript has thousands of tutorials but few clear paths through them. This curriculum puts the best free articles, videos, and books in order, from the core language to the tools you use every day.

## How to use this curriculum

1. Keep one main reference open while you learn: [javascript.info](https://javascript.info/) or the [MDN JavaScript Guide](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide).
2. Follow the stages in order. Each section has a short summary and a list of resources.
3. After each stage, build a small project that uses what you learned.

| Icon | Meaning |
|---|---|
| 📜 | Article or documentation |
| 📹 | Video |
| 📀 | Course or video series |
| 📕 | Book |
| ⭐ | Recommended |
| 💲 | Paid |

## Table of contents

| Stage | Sections |
|---|---|
| 1. The core language | [Core concepts](#core-concepts) · [How JavaScript runs](#how-javascript-runs) |
| 2. Functions and paradigms | [Objects and functions](#objects-and-functions) · [Object-oriented programming](#object-oriented-programming) · [Functional programming](#functional-programming) |
| 3. Asynchronous JavaScript | [Callbacks, promises, and async/await](#callbacks-promises-and-asyncawait) |
| 4. Web APIs | [DOM and events](#dom-and-events) · [Network requests](#network-requests) · [Storage](#storage) · [Files](#files) · [Drag and drop](#drag-and-drop) · [Animation](#animation) · [Audio and video](#audio-and-video) · [Time and date](#time-and-date) · [Payments](#payments) · [Web components](#web-components) · [WebRTC](#webrtc) · [Progressive web apps](#progressive-web-apps) |
| 5. Tooling | [Modules and build tools](#modules-and-build-tools) · [Code quality](#code-quality) · [Testing](#testing) |
| 6. Architecture | [Design patterns](#design-patterns) · [Data structures and algorithms](#data-structures-and-algorithms) · [Frameworks and libraries](#frameworks-and-libraries) |
| 7. Beyond the browser | [TypeScript](#typescript) · [Node.js](#nodejs) |
| Extra | [Interview preparation](#interview-preparation) · [Where to go next](#where-to-go-next) |

---

# Stage 1. The core language

## Core concepts

Learn the syntax, the types, and the rules of the language.

- ⭐ 📜 [The Modern JavaScript Tutorial](https://javascript.info/) - javascript.info.
- ⭐ 📜 [JavaScript Guide](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide) - MDN.
- 📜 [ES6 Overview in 350 Bullet Points](https://ponyfoo.com/articles/es6) - Pony Foo.
- 📜 [7 Tips to Handle undefined in JavaScript](https://dmitripavlutin.com/7-tips-to-handle-undefined-in-javascript/) - Dmitri Pavlutin.
- 📜 [Learning Advanced JavaScript](https://johnresig.com/apps/learn/) - John Resig.

<p align="right"><a href="#table-of-contents">Back to top ⬆</a></p>

## How JavaScript runs

Learn what the engine does with your code: the call stack, the event loop, and memory.

- ⭐ 📹 [What the heck is the event loop anyway?](https://www.youtube.com/watch?v=8aGhZQkoFbQ) - Philip Roberts, JSConf EU.
- 📹 [In The Loop](https://www.youtube.com/watch?v=cCOL7MC4Pl0) - Jake Archibald, JSConf.Asia.
- 📜 [JavaScript Visualized: the JavaScript Engine](https://dev.to/lydiahallie/javascript-visualized-the-javascript-engine-4cdf) - Lydia Hallie.
- 📜 [JavaScript's Memory Management Explained](https://felixgerschau.com/javascript-memory-management/) - Felix Gerschau.
- 📜 [How browsers work](https://web.dev/articles/howbrowserswork) - web.dev.

<p align="right"><a href="#table-of-contents">Back to top ⬆</a></p>

---

# Stage 2. Functions and paradigms

## Objects and functions

Arrays, objects, and functions are the building blocks of every paradigm. Learn them well before you go deeper.

- 📹 [An Encounter with JavaScript Objects](https://www.youtube.com/watch?v=napDjGFjHR0) - Fireship.
- 📜 [Function Declarations vs. Function Expressions](https://javascriptweblog.wordpress.com/2010/07/06/function-declarations-vs-function-expressions/) - JavaScript, JavaScript.
- 📜 [Objects: the basics](https://javascript.info/object-basics) - javascript.info.

<p align="right"><a href="#table-of-contents">Back to top ⬆</a></p>

## Object-oriented programming

Object-oriented programming builds software from objects. Each object holds data (fields) and the code that works on that data (methods).

- ⭐ 📜 [Classes](https://javascript.info/classes) - javascript.info.
- 📜 [Prototypal inheritance](https://javascript.info/prototype-inheritance) - javascript.info.
- 📜 [What’s the Difference Between Class and Prototypal Inheritance?](https://medium.com/javascript-scene/master-the-javascript-interview-what-s-the-difference-between-class-prototypal-inheritance-e4cd0a7562e9) - Eric Elliott.
- 📹 [Object-oriented Programming in 7 minutes](https://www.youtube.com/watch?v=pTB0EiLXUC8) - Mosh.
- 📹 [Object-oriented Programming in JavaScript: Made Super Simple](https://www.youtube.com/watch?v=PFmuCDHHpwk) - Mosh.
- 📹 [JavaScript OOP Crash Course (ES5 and ES6)](https://www.youtube.com/watch?v=vDJpGenyHaA) - Traversy Media.
- 📹 [Object Oriented vs Functional Programming with TypeScript](https://www.youtube.com/watch?v=fsVL_xrYO0w) - Fireship.
- 📀 [Modular JavaScript](https://www.youtube.com/playlist?list=PLoYCgNOIyGABs-wDaaxChu82q_xQgUb4f) - LearnCode.academy.

<p align="right"><a href="#table-of-contents">Back to top ⬆</a></p>

## Functional programming

Functional programming builds software from pure functions. It avoids shared state, changing data, and side effects. Data flows through the functions.

- ⭐ 📜 [What is Functional Programming?](https://medium.com/javascript-scene/master-the-javascript-interview-what-is-functional-programming-7f218c68b3a0) - Eric Elliott.
- 📜 [What is a Pure Function?](https://medium.com/javascript-scene/master-the-javascript-interview-what-is-a-pure-function-d1c076bec976) - Eric Elliott.
- 📜 [What is a Closure?](https://medium.com/javascript-scene/master-the-javascript-interview-what-is-a-closure-b2f0d2152b36) - Eric Elliott.
- 📜 [What is Function Composition?](https://medium.com/javascript-scene/master-the-javascript-interview-what-is-function-composition-20dfb109a1a0) - Eric Elliott.
- 📜 [The Two Pillars of JavaScript](https://medium.com/javascript-scene/the-two-pillars-of-javascript-ee6f3281e7f3) - Eric Elliott.
- 📕 [Composing Software: The Book](https://medium.com/javascript-scene/composing-software-the-book-f31c77fc3ddc) - Eric Elliott.
- 📜 [JavaScript Callbacks Explained Using Minions](https://www.freecodecamp.org/news/javascript-callbacks-explained-using-minions-da272f4d9bcd/) - freeCodeCamp.
- 📜 [Understanding Immutability in JavaScript](https://css-tricks.com/understanding-immutability-in-javascript/) - CSS-Tricks.
- 📜 [Four Ways to Immutability in JavaScript](https://dev.to/glebec/four-ways-to-immutability-in-javascript-3b3l) - dev.to.
- 📜 [How to Deep Copy Objects and Arrays in JavaScript](https://medium.com/javascript-in-plain-english/how-to-deep-copy-objects-and-arrays-in-javascript-7c911359b089) - JavaScript in Plain English.
- 📜 [structuredClone()](https://developer.mozilla.org/en-US/docs/Web/API/Window/structuredClone) - MDN. The built-in way to deep copy.
- 📹 [JavaScript Higher Order Functions and Arrays](https://www.youtube.com/watch?v=rRgD1yVwIvE) - Traversy Media.
- 📹 [Learning Functional Programming with JavaScript](https://www.youtube.com/watch?v=e-5obm1G_FY) - Anjana Vakil, JSUnconf.

<p align="right"><a href="#table-of-contents">Back to top ⬆</a></p>

---

# Stage 3. Asynchronous JavaScript

## Callbacks, promises, and async/await

JavaScript runs on one thread. Asynchronous code lets it wait for a network request or a timer without freezing the page.

- ⭐ 📜 [Promises, async/await](https://javascript.info/async) - javascript.info.
- 📜 [Asynchronous JavaScript](https://developer.mozilla.org/en-US/docs/Learn_web_development/Extensions/Async_JS) - MDN.
- 📜 [What is a Promise?](https://medium.com/javascript-scene/master-the-javascript-interview-what-is-a-promise-27fc71e77261) - Eric Elliott.
- 📹 [Async JS Crash Course: Callbacks, Promises, Async Await](https://www.youtube.com/watch?v=PoRJizFvM7s) - Traversy Media.
- 📹 [The Async Await Episode I Promised](https://www.youtube.com/watch?v=vn3tm0quoqE) - Fireship.

<p align="right"><a href="#table-of-contents">Back to top ⬆</a></p>

---

# Stage 4. Web APIs

Before you start, look at [What Web Can Do Today](https://progressier.com/what-web-can-do-today). It shows which device features a web page can use.

## DOM and events

- ⭐ 📜 [Document](https://javascript.info/document) - javascript.info.
- 📜 [Introduction to events](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Scripting/Events) - MDN.
- 📀 [JavaScript DOM Crash Course](https://www.youtube.com/playlist?list=PLillGF-RfqbYE6Ik_EuXA2iZFcE082B3s) - Traversy Media.
- 📹 [Learn DOM Manipulation In 18 Minutes](https://www.youtube.com/watch?v=y17RuWkWdn8) - Web Dev Simplified.
- 📹 [Learn JavaScript DOM Traversal In 15 Minutes](https://www.youtube.com/watch?v=v7rSSy8CaYE) - Web Dev Simplified.
- 📹 [Learn JavaScript Event Listeners In 18 Minutes](https://www.youtube.com/watch?v=XF1_MlZ5l6M) - Web Dev Simplified.

<p align="right"><a href="#table-of-contents">Back to top ⬆</a></p>

## Network requests

A page talks to a server over HTTP, WebSocket, or WebRTC. The browser gives you `fetch()`, `XMLHttpRequest`, and `WebSocket` to do it.

- ⭐ 📜 [Using the Fetch API](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch) - MDN.
- 📜 [The WebSocket API](https://developer.mozilla.org/en-US/docs/Web/API/WebSockets_API) - MDN.
- 📹 [Fetch API Introduction](https://www.youtube.com/watch?v=Oive66jrwBs) - Traversy Media.
- 📹 [AJAX Crash Course (Vanilla JavaScript)](https://www.youtube.com/watch?v=82hnvUYY6QA) - Traversy Media.
- 📹 [Axios Crash Course](https://www.youtube.com/watch?v=6LyagkoRWYA) - Traversy Media.
- 📹 [Sending JavaScript HTTP Requests with XMLHttpRequest](https://www.youtube.com/watch?v=4K33w-0-p2c) - Academind.
- 📹 [Sending JavaScript HTTP Requests with the fetch() API](https://www.youtube.com/watch?v=23hrM4saaMk) - Academind.
- 📹 [Sending JavaScript HTTP Requests with Axios](https://www.youtube.com/watch?v=qM4G1Ai2ZpE) - Academind.

<p align="right"><a href="#table-of-contents">Back to top ⬆</a></p>

## Storage

- ⭐ 📜 [Web Storage API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Storage_API) - MDN. `localStorage` and `sessionStorage`.
- 📜 [IndexedDB API](https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API) - MDN. A database in the browser for larger data.
- 📜 [Storage for the web](https://web.dev/articles/storage-for-the-web) - web.dev. Which storage to use and how much you get.

<p align="right"><a href="#table-of-contents">Back to top ⬆</a></p>

## Files

- 📜 [File API](https://developer.mozilla.org/en-US/docs/Web/API/File_API) - MDN.
- 📜 [Using files from web applications](https://developer.mozilla.org/en-US/docs/Web/API/File_API/Using_files_from_web_applications) - MDN.
- 📜 [File System API](https://developer.mozilla.org/en-US/docs/Web/API/File_System_API) - MDN.

<p align="right"><a href="#table-of-contents">Back to top ⬆</a></p>

## Drag and drop

- 📜 [HTML Drag and Drop API](https://developer.mozilla.org/en-US/docs/Web/API/HTML_Drag_and_Drop_API) - MDN.

<p align="right"><a href="#table-of-contents">Back to top ⬆</a></p>

## Animation

- 📜 [Using the Web Animations API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Animations_API/Using_the_Web_Animations_API) - MDN.
- 📜 [requestAnimationFrame()](https://developer.mozilla.org/en-US/docs/Web/API/Window/requestAnimationFrame) - MDN.

<p align="right"><a href="#table-of-contents">Back to top ⬆</a></p>

## Audio and video

- 📜 [Web Audio API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API) - MDN.
- 📜 [Media Capture and Streams API](https://developer.mozilla.org/en-US/docs/Web/API/Media_Capture_and_Streams_API) - MDN. Use the camera and the microphone.

<p align="right"><a href="#table-of-contents">Back to top ⬆</a></p>

## Time and date

- 📜 [Intl.DateTimeFormat](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl/DateTimeFormat) - MDN.
- 📜 [Temporal](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Temporal) - MDN. The new date and time API.
- 📜 [Natively Format JavaScript Dates and Times](https://elijahmanor.com/blog/format-js-dates-and-times) - Elijah Manor.

<p align="right"><a href="#table-of-contents">Back to top ⬆</a></p>

## Payments

- 📜 [Payment Request API](https://developer.mozilla.org/en-US/docs/Web/API/Payment_Request_API) - MDN.

<p align="right"><a href="#table-of-contents">Back to top ⬆</a></p>

## Web components

- ⭐ 📜 [Web Components](https://developer.mozilla.org/en-US/docs/Web/API/Web_components) - MDN.
- 📹 [Web Components Crash Course](https://www.youtube.com/watch?v=PCWaFLy3VUo) - Traversy Media.
- 📹 [Building a REAL Web Component from Scratch](https://www.youtube.com/watch?v=mNtLjzzxGQM) - DesignCourse.
- 💲 [Web Components and Stencil.js: Build Custom HTML Elements](https://www.udemy.com/course/web-components-stenciljs-build-custom-html-elements/) - Udemy.

<p align="right"><a href="#table-of-contents">Back to top ⬆</a></p>

## WebRTC

- 📜 [WebRTC API](https://developer.mozilla.org/en-US/docs/Web/API/WebRTC_API) - MDN.
- 📹 [How To Create A Video Chat App With WebRTC](https://www.youtube.com/watch?v=DvlyzDZDEq4) - Web Dev Simplified.

<p align="right"><a href="#table-of-contents">Back to top ⬆</a></p>

## Progressive web apps

- ⭐ 📀 [Learn PWA](https://web.dev/learn/pwa/) - web.dev.
- 📜 [The Offline Cookbook](https://jakearchibald.com/2014/offline-cookbook/) - Jake Archibald.
- 📜 [Using Service Workers](https://developer.mozilla.org/en-US/docs/Web/API/Service_Worker_API/Using_Service_Workers) - MDN.
- 📹 [Progressive Web Apps in 100 Seconds](https://www.youtube.com/watch?v=sFsRylCQblw) - Fireship.
- 📹 [7 Web Features You Didn’t Know Existed](https://www.youtube.com/watch?v=ppwagkhrZJs) - Fireship.
- 📹 [PWA to Google Play Store with Trusted Web Activities](https://www.youtube.com/watch?v=7JDFjeMvxos) - Fireship.
- 📀 [PWA Tutorial for Beginners](https://www.youtube.com/playlist?list=PL4cUxeGkcC9gTxqJBcDmoi5Q2pzDusSL7) - The Net Ninja.
- 📀 [Progressive Web App Training](https://www.youtube.com/playlist?list=PLNYkxOF6rcIB2xHBZ7opgc2Mv009X87Hh) - Chrome for Developers.
- 💲 [Progressive Web Apps (PWA): The Complete Guide](https://www.udemy.com/course/progressive-web-app-pwa-the-complete-guide/) - Udemy.

<p align="right"><a href="#table-of-contents">Back to top ⬆</a></p>

---

# Stage 5. Tooling

## Modules and build tools

#### What you will learn

- **Module formats, oldest to newest:** IIFE, AMD, CommonJS, UMD, and ES modules.
- **Bundlers:** combine many files into a few files for the browser.
- **Transpilers:** turn new syntax or TypeScript into code that older browsers run.

#### Resources

- ⭐ 📜 [JavaScript modules](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules) - MDN.
- 📜 [Modules, introduction](https://javascript.info/modules-intro) - javascript.info.
- Bundlers: [Vite](https://vite.dev/) ⭐ · [webpack](https://webpack.js.org/) · [esbuild](https://esbuild.github.io/) · [Rollup](https://rollupjs.org/) · [Parcel](https://parceljs.org/)
- Transpilers: [Babel](https://babeljs.io/) · [SWC](https://swc.rs/) · [TypeScript](https://www.typescriptlang.org/)

<p align="right"><a href="#table-of-contents">Back to top ⬆</a></p>

## Code quality

- ⭐ 📜 [Clean Code JavaScript](https://github.com/ryanmcdermott/clean-code-javascript) - Ryan McDermott.
- 📜 [Top 10 JavaScript errors from 1000+ projects](https://codeburst.io/top-10-javascript-errors-from-1000-projects-and-how-to-avoid-them-2956ce008437) - codeburst.
- 📜 [ESLint](https://eslint.org/) - Find problems in your code.
- 📜 [Prettier](https://prettier.io/) - Format your code the same way every time.

<p align="right"><a href="#table-of-contents">Back to top ⬆</a></p>

## Testing

- ⭐ 📜 [Vitest](https://vitest.dev/) - A fast test runner for Vite projects.
- 📜 [Jest](https://jestjs.io/) - A widely used test runner.
- 📜 [Testing Library](https://testing-library.com/) - Test the UI the way a user uses it.
- 📜 [Playwright](https://playwright.dev/) - End-to-end tests in real browsers.

<p align="right"><a href="#table-of-contents">Back to top ⬆</a></p>

---

# Stage 6. Architecture

## Design patterns

- ⭐ 📕 [Patterns.dev](https://www.patterns.dev/) - Lydia Hallie and Addy Osmani. Design, rendering, and performance patterns for modern web apps.
- 📕 [Learning JavaScript Design Patterns](https://patterns.addy.ie/) - Addy Osmani.
- 📜 [JavaScript Design Patterns for Humans](https://github.com/sohamkamani/javascript-design-patterns-for-humans) - Soham Kamani.
- 📜 [Understanding MVC and MVP (For JavaScript and Backbone Developers)](https://addyosmani.com/blog/understanding-mvc-and-mvp-for-javascript-and-backbone-developers/) - Addy Osmani.
- 📜 [What is the difference between MVC and MVVM?](https://stackoverflow.com/questions/667781/what-is-the-difference-between-mvc-and-mvvm) - Stack Overflow.
- 📜 [What are MVP and MVC and what is the difference?](https://stackoverflow.com/questions/2056/what-are-mvp-and-mvc-and-what-is-the-difference) - Stack Overflow.
- 📜 [What is the MVVM design pattern?](https://www.quora.com/What-is-the-MVVM-design-pattern) - Quora.
- 📜 [3 Key Software Principles You Must Understand](https://code.tutsplus.com/tutorials/3-key-software-principles-you-must-understand--net-25161) - Envato Tuts+.
- 📜 [SOLID Principles: The Definitive Guide](https://medium.com/android-news/solid-principles-the-definitive-guide-75e30a284dea) - AndroidPub on Medium.

<p align="right"><a href="#table-of-contents">Back to top ⬆</a></p>

## Data structures and algorithms

- ⭐ 📜 [JavaScript Algorithms and Data Structures](https://github.com/trekhleb/javascript-algorithms) - Oleksii Trekhleb.
- 📜 [JS: Sorting Algorithm](https://khan4019.github.io/front-end-Interview-Questions/sort.html) - MD Khan.

<p align="right"><a href="#table-of-contents">Back to top ⬆</a></p>

## Frameworks and libraries

- 📜 [Change And Its Detection In JavaScript Frameworks](https://teropa.info/blog/2015/03/02/change-and-its-detection-in-javascript-frameworks.html) - Tero Parviainen.
- 📜 [The Ultimate Guide to JavaScript Frameworks](https://javascriptreport.com/the-ultimate-guide-to-javascript-frameworks/) - The JavaScript Report.

<p align="right"><a href="#table-of-contents">Back to top ⬆</a></p>

---

# Stage 7. Beyond the browser

## TypeScript

TypeScript adds types to JavaScript. It finds many bugs before you run the code.

- ⭐ 📜 [The TypeScript Handbook](https://www.typescriptlang.org/docs/handbook/intro.html) - TypeScript.
- 📜 [TypeScript Evolution](https://mariusschulz.com/blog/series/typescript-evolution) - Marius Schulz.
- 📀 [Introduction to TypeScript](https://scrimba.com/g/gintrototypescript) - Scrimba.

<p align="right"><a href="#table-of-contents">Back to top ⬆</a></p>

## Node.js

Node.js runs JavaScript on the server, so you can use one language for the whole stack.

- ⭐ 📜 [Introduction to Node.js](https://nodejs.org/en/learn/getting-started/introduction-to-nodejs) - Node.js.
- 📜 [The Node.js event loop](https://nodejs.org/en/learn/asynchronous-work/event-loop-timers-and-nexttick) - Node.js.

<p align="right"><a href="#table-of-contents">Back to top ⬆</a></p>

---

## Interview preparation

- ⭐ 📜 [JavaScript Questions](https://github.com/lydiahallie/javascript-questions) - Lydia Hallie.
- 📜 [10 Interview Questions Every JavaScript Developer Should Know](https://medium.com/javascript-scene/10-interview-questions-every-javascript-developer-should-know-6fa6bdf5ad95) - Eric Elliott.

<p align="right"><a href="#table-of-contents">Back to top ⬆</a></p>

## Where to go next

#### References 📜

- ⭐ [MDN JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- [javascript.info](https://javascript.info/)
- [Modern JavaScript for Ancient Web Developers](https://postlight.com/insights/modern-javascript-for-ancient-web-developers) - Postlight.

#### Books and courses 📕 📀

- ⭐ 📕 [Eloquent JavaScript](https://eloquentjavascript.net/) - Marijn Haverbeke.
- 📕 [You Don't Know JS Yet](https://github.com/getify/You-Dont-Know-JS) - Kyle Simpson.
- 📀 [JavaScript 30](https://javascript30.com/) - Wes Bos. 30 small projects in 30 days.
- 💲 [Modern JavaScript From The Beginning](https://www.udemy.com/course/modern-javascript-from-the-beginning/) - Udemy. Beginner.
- 💲 [JavaScript: The Complete Guide](https://www.udemy.com/course/javascript-the-complete-guide-2020-beginner-advanced/) - Udemy. Beginner to advanced.
- 💲 [The Complete JavaScript Course: From Zero to Expert!](https://www.udemy.com/course/the-complete-javascript-course/) - Udemy. Intermediate to advanced.

#### Blogs, podcasts, and newsletters 📝 🎙 📫

- [web.dev](https://web.dev/) 📝
- [freeCodeCamp News](https://www.freecodecamp.org/news/) 📝
- [JavaScript Scene](https://medium.com/javascript-scene) 📝
- [JavaScript Weekly](https://javascriptweekly.com/) 📫

<p align="right"><a href="#table-of-contents">Back to top ⬆</a></p>
