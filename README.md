# Product Landing Page

## Description

This website is a product landing page for a Chrome extension created by the Turtles 11 team in the _Chingu Voyage 2_ cohort.

This product landing page is a project required for freeCodeCamp's _[Responsive Web Design](https://learn.freecodecamp.org/)_ certificate. It fulfills the user stories listed [here](https://learn.freecodecamp.org/responsive-web-design/responsive-web-design-projects/build-a-product-landing-page/).

## Demo

https://eunicode.github.io/product-landing-page/

## Features

- Fixed navigation bar
- Client-side form validation with HTML5
- Aligned, centered width-constrained content with `max-width` and auto-margins, or with Grid, if supported
- Single-column, mobile-first layout
- Progressive enhancement with `@supports` rule, Flexbox, and Grid
- Responsive design with media queries

## Tech Stack

- HTML5
- CSS3

## Setup

Install dependencies

```
npm install
```

Run the default `gulp` command to start the live server

```
gulp
```

## Lessons Learned

- How to display full-bleed sections with centered, width-constrained content that aligns with other sections' content by applying the same grid to each section to create a "global", aggregate grid
- How to create a pure HTML form that submits data to a server by using `form`'s `action` attribute and an element with a `type="submit"` attribute (`input`, `button`)
- When a form is submitted, the data submitted will be a key-value pair derived from the value of the `name` attribute and the `value` attribute. E.g. `subscribe=newsletter`
- For `input` elements of the type text, the `value` attribute is a DOMString that contains the current value of the text entered into the text field. You can retrieve this using the `HTMLInputElement.value` property in JavaScript.
- How to require form fields with the `required` attribute
- The `label` element's `for` attribute and the `input` element's `id` attribute are used to link them together (their values must match).
