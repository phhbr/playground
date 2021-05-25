# Web Components Workshop

## About

This workshop will teach you the basics of web components.

material:
- slides: https://app.deckdeckgo.com/editor/iAB3p7dY2ribWi5hFmHz?signin=success
- source code basics
- source code stenciljs

### Agenda

1. specification of web components
2. simple web component via vanilla JS & web component API
    1. step-by-step implementation of a toggle button
    2. disadvantages
3. StencilJS
    1. motivation
    2. implementation of a toggle button
    3. resolving disadvantages
    4. alternatives to stenciljs


### Preparation

- install [nodejs lts](https://nodejs.org/en/download/) or [nvm](https://github.com/nvm-sh/nvm)
- verify successful installation `node -v`

## Web Components

### What are web components?

Web components are a set of web platform APIs that allow you to create new custom, reusable, encapsulated HTML tags to use in web pages and web apps. Custom components and widgets build on the Web Component standards, will work across modern browsers, and can be used with any JavaScript library or framework that works with HTML.

Web components are based on existing web standards. Features to support web components are currently being added to the HTML and DOM specs, letting web developers easily extend HTML with new elements with encapsulated styling and custom behavior.

src: [1]

### Specifications

web components are based on four main specification

- Custom Elements
- Shadow DOM
- HTML Template
- ES Modules

#### Custom Elements

- support to build fully-featured DOM elements
- concept is already known because of web libraries / frameworks
- has to have a dash in the element selector, i.e. `<wc-button>`
- elements have to be registered
- autonomous custom element vs customized built-in element
- behaviour via attributes, properties & events
- lifecycle methods
- DEMO

src: [2]

#### Shadow DOM

- nothing new: compare to <video> which only exposes control 
- is a node tree whose root is a shadow root
    - what is DOM, shadow tree, shadow root, shadow host
- allows encapsulation
- has different modes: open / closed
- contains zero or more elements that are slots
- elements & text nodes can be slotted
- DEMO

src: [3]

## StencilJS

#### Alternatives

[55 different ways to make a Web Component](https://webcomponents.dev/blog/all-the-ways-to-make-a-web-component/)



## References

[1]: https://www.webcomponents.org/introduction
1: https://www.webcomponents.org/introduction

[2]: https://html.spec.whatwg.org/multipage/custom-elements.html#custom-elements
2: https://html.spec.whatwg.org/multipage/custom-elements.html#custom-elements

[3]: https://dom.spec.whatwg.org/#shadow-trees
3: https://dom.spec.whatwg.org/#shadow-trees

[4]: https://developer.mozilla.org/en-US/docs/Web/Web_Components/Using_shadow_DOM
4: https://developer.mozilla.org/en-US/docs/Web/Web_Components/Using_shadow_DOM

