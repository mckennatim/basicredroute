# basic redux routing
A stripped down example of `react`, `redux`, `react-router` and `redux-simple router` drawn from the `example/basic` of `redux-simple-router`

<blockquote>
This is a basic example that demonstrates rendering components based
on URLs with react-router as well as connecting them to Redux state.
It uses both <Link> elements and the `updatePath` action creator to
update the paths.    
</blockquote>

To run, follow these steps:

1. Install dependencies with `npm install` 
2. Build with `webpack --watch`
3. Open `index.html`

versions in working example

├─┬ history@1.17.0
│ ├── deep-equal@1.0.1
│ ├─┬ invariant@2.2.0
│ │ └─┬ loose-envify@1.1.0
│ │   └── js-tokens@1.0.2
│ ├─┬ query-string@3.0.0
│ │ └── strict-uri-encode@1.1.0
│ └─┬ warning@2.1.0
│   └─┬ loose-envify@1.1.0
│     └── js-tokens@1.0.2
├─┬ react@0.14.6
│ ├─┬ envify@3.4.0
│ │ ├─┬ jstransform@10.1.0
│ │ │ ├── base62@0.1.1
│ │ │ ├── esprima-fb@13001.1001.0-dev-harmony-fb
│ │ │ └─┬ source-map@0.1.31
│ │ │   └── amdefine@1.0.0
│ │ └── through@2.3.8
│ └─┬ fbjs@0.6.1
│   ├── core-js@1.2.6
│   ├─┬ loose-envify@1.1.0
│   │ └── js-tokens@1.0.2
│   ├─┬ promise@7.1.1
│   │ └── asap@2.0.3
│   ├── ua-parser-js@0.7.10
│   └── whatwg-fetch@0.9.0
├── react-dom@0.14.6
├─┬ react-redux@4.0.6
│ ├── hoist-non-react-statics@1.0.3
│ └─┬ invariant@2.2.0
│   └─┬ loose-envify@1.1.0
│     └── js-tokens@1.0.2
├─┬ react-router@1.0.3
│ ├─┬ invariant@2.2.0
│ │ └─┬ loose-envify@1.1.0
│ │   └── js-tokens@1.0.2
│ └─┬ warning@2.1.0
│   └─┬ loose-envify@1.1.0
│     └── js-tokens@1.0.2
├── redux@3.0.5
├─┬ redux-simple-router@1.0.2
│ ├── deep-equal@1.0.1
│ └── history@1.13.1 extraneous