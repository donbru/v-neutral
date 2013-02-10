# *v-neutral*

## Original Machine Configuration Steps

1. Install [node.js](http://www.nodejs.org/)
1. From a (Windows) command prompt, run "express --sessions --css less v-neutral" to create the folder *v-neutral*, node module dependency package *package.json*, and node application *app.js*. For details, see [http://expressjs.com/guide.html](http://expressjs.com/guide.html). Express defaults to [jade](http://jade-lang.com/) node view template engine; see [ejs-vs.-jade comparison](http://vschart.com/compare/embedded-javascript/vs/jade-template-engin) -- unicode support a plus.
1. "cd v-neutral"
1. Edit *package.json* and add modules *mongoDB* and *mongoose*.
1. Run "npm install" invokes node to run *package.json*, which creates the sub-folder *node_modules*.
1. Run "node app.js"; see output in browser, use http://localhost:3000/.

## Arbitrary Exploratory Objectives
1. Explore use of a single page application ala the example in [https://github.com/btford/angular-express-seed](https://github.com/btford/angular-express-seed).
1. Seed [MongoDB](http://www.mongodb.org/) collection with simple view data initially accessed directly via REST.
1. Consider [Typesafe.com](http://typesafe.com/) for implementing business logic in Scala.






