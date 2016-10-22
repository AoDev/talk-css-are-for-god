# CSS are for god
Presentation of the talk at [ngBigParty III](http://www.meetup.com/ngParty/events/231965205/) in Prague on 12th of October 2016, by Kevin Purnelle.

## How to view the slides

Just clone the repo and open `index.html in your browser.

The presentation is made with `reveal.js`.

* Press `space` to go to next slide.
* Press `escape` to view all the slides.

## Why this talk?

More than technology it's about methodology to achieve product quality on the frontend. There are some examples with the React library but it's not about React.

I hope that this talk can provide a few tips to make your UI development faster, more enjoyable and maybe raise quality.


### Context

There is a thin line between prototype, MVP and actual product. In fact there is none. These terms only reflect a phase of a product development but in no way guarantee the quality needed or expected in each of these steps. Today you have a prototype, tomorrow you have it in production. Nothing changed in your code while some marketing department runs crazy shouting all over Internet to get people to try your product.

Some hacky UI goes quickly to production due to fast iteration because when it comes to web and startups, the goal is to release something as fast as possible, usually it means quality comes later. And regarding the UI, the mindset is: "Looking good is good enough".

It is even more true in the era of fullstack "hackers", ops, sorry I meant "developers".

People with various skills who have superficial knowledge of accessibility, design, visual coherence or UX are in charge of building UI with javascript, html and CSS.

__So comes the first important observation__: the quality must be provided by a different mean.

The UI building blocks that the developer will use, must __encapsulate quality__ as much as possible.

CSS for instance are probably the last thing that are cared about. There are far less efforts put into architecturing the CSS code, creating reusable styles solutions and actually learning how they work compared to javascript. This usually leads to senseless solutions and unmaintainable mess unless you have a CSS watchdog around in your company.