# web-component-playground

tinkering with web components

web components are pretty great! they come with a lot of new syntax but bring a ton of awesome features! in my first example, `pricing-cards.html` i leaned into using templates and slots. this is an extremely powerful feature, i love that you can use named slots or empty, un-named slots to pass large amount of information. cards are a perfect use-case for this since you can leverage the wrapper and blankcard then drop in whatever content you need.

i see why some may view shadow dom style encapsulation as an anti-pattern, but personally i think it's great. it reminds me of using BEM naming for your CSS (particulalry with react components). when you're building with components, it's nice to not have leaky styles.

i'd like to spend more time playing around with component life cycle events. my card example is mostly static and next i'd like to try building something with an aspect of 'state'. i'd like to do more with `constructor()`, `static observedAttributes()`, `attributeChangedCallback()`, `connectedCallback()`, `disconnectedCallback()` & `adoptedCallback()`.
