# Material Web Components

Material Web Components helps developers execute [Material Design](https://www.material.io) using [web components](https://developer.mozilla.org/en-US/docs/Web/Web_Components).

Built on top of the [Material Components Web](https://github.com/material-components/material-components-web) project and [LitElement](https://github.com/polymerlabs/lit-element), the Material Web Components enable a reliable development workflow to build beautiful and functional web projects.

Web Components can be seamlessly incorporated into a wide range of usage contexts. Whether you're already heavily invested in another framework or not, it should be easy to incorporate Material Web Components into your site in a lightweight, idiomatic fashion.

**[Demos](demos/)**

## Quick start

> Note: This guide assumes you have npm installed locally.

To get started using one of the Material Web Components in your web application, simply:

1. npm install it

    ```
    npm install @material/mwc-button
    ```

1. Load the webcomponents polyfills (see the [webcomponents polyfill Readme](https://github.com/webcomponents/webcomponentsjs/blob/v2/README.md) for more info).

1. import the element

    ```
    <script type="module">
      import {Button} from '@material/mwc-button';
    </script>
    ```

1. Use the element on the page

    ```
    <mwc-button label="Hi" icon="explore" raised></mwc-button>
    ```

Below are instructions for setting up project development.

1. `git clone` this repo
1. install dependencies by running `npm run bootstrap`
1. to run a development server: `npm run dev` (view the demos by accessing `<dev server url>`/demos/index.html)
1. to run tests: `npm run test`

### Rebuild CSS for components

Components define their css using [SASS](http://sass-lang.com/). The SASS output is built into a javascript module which exports the component's styling as a (lit-html)[https://github.com/Polymer/lit-html] template.

To compile the component SASS run

  ```
  npm run update-styling
  ```

## Useful Links

- [All Components](packages/)
- [Demos](demos/)
- [Contributing](CONTRIBUTING.md)
- [Material.io](https://www.material.io) (external site)
- [Material Design Guidelines](https://material.io/guidelines) (external site)

## Browser Support

We officially support the last two versions of every major browser. Specifically, we test on the following browsers:

- Chrome
- Safari
- Firefox
- IE 11/Edge
- Opera
- Mobile Safari
- Chrome on Android
