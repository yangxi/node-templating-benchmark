# Node.js rendering benchmark (React, Nunjucks, ES6, Pug)

A Node.js application written in, used to benchmark rendering engines, especially React.js/ReactDOMServer against more traditional templating engines like Nunjucks, Pug and standard ES6 Template Literals.

More details in the article: [The Performance Cost of Server Side Rendered React on Node.js](https://malloc.fi/performance-cost-of-server-side-rendered-react-node-js)

# compile the code
./node_modules/.bin/tsc

# run the server
node ./dist/server.js