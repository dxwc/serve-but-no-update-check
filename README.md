+ [Original Github](https://github.com/zeit/serve/commit/73206336971c38e9f4867dc8cd88f95bd996f37d)
+ [Original NPM](https://www.npmjs.com/package/serve/v/10.1.2)
+ Removed default update check
+ Removed default clipboard overwrite with URL
+ Removed now.js and package.json config support
+ Removed single.html

# Setup

+ Git clone, cd in
+ `npm install`
+ To change style, edit `./node_modules/serve-handler/src/directory.js`
+ To install globally, `npm link` or `sudo npm link`

# Example Use

+ `node bin/serve ~`
+ `node bin/serve --listen 9001`
+ If there is a `index.html` where it is being served, it will serve that instead (???)
    + Can't be removed from this package, it's on a dependency
