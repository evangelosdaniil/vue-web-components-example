# Vue.js to Web Components

An example on how to wrap and register a Vue component as a Web Component. This is a typical 👋🏼🌍 Vue.js example with the only difference that we are utilizing the [vue-custom-component](https://github.com/karol-f/vue-custom-element) to wrap and register our Vue component as a Web Component.

We then can use the build generated files in any HTML page to inject our Vue components 🥳🎉

## Prerequisites

To run this project locally, we need to:

1. grab a ☕️
2. [install npm](https://www.npmjs.com/get-npm)

## Installation

1. Clone the repo
   ```sh
   git clone https://github.com/evangelosdaniil/vue-web-components-example.git
   ```

2. Install the npm packages
   ```sh
   npm install
   ```
## Building the project

To build the project, you should run the following command:

```sh
npm run build
```

Once the process is finished, it will generate the following files under dist: 

1. app.css
2. app.js

Which then you can import in any HTML file you want to inject your Vue web component.

## Importing your Vue Web Component in any HTML

Check the public/index.html file to see a working example. In short, you can do something like this:

```
<vue-wc-test></vue-wc>

<script type="module" src="/dist/js/app.js"></script>
```

