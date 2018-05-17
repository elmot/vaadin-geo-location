# <vaadin-geo-location> element

## Running the tutorial code

You'll need to install some command-line tools to manage dependencies and to run the demo.

1.  Download and install Node version 8.x or later from [https://nodejs.org/](https://nodejs.org/). Node includes the node package manager command, `npm`.

2.  Install `bower` and the Polymer CLI:

        npm install -g bower polymer-cli
3. Look at the [example](https://github.com/elmot/vaadin-geo-location/blob/master/demo/demo-element.html)
 
##API

```html
<vaadin-geo-location on-location="handleLocation" on-error="handleOops"
    high-accuracy timeout="50" max-age="15" watch></vaadin-geo-location>

```
### See also

https://github.com/elmot/vaadin-geo-location-flow