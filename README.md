![logo](https://github.frapsoft.com/top/nodejs-logo.png)

# Node.js for Developers [![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=102)](https://github.com/ellerbrock/open-source-badge/) [![Gitter Chat](https://badges.gitter.im/frapsoft/frapsoft.svg)](https://gitter.im/frapsoft/frapsoft/)

Full Stack Javascript Development with [Node.js](https://nodejs.org/en/)

# Recommended Reading

- [Unix Philosophy and Node.js](http://blog.izs.me/post/48281998870/unix-philosophy-and-nodejs)
- [Writing small & reusable Modules](http://substack.net/how_I_write_modules)
- [Semantic Versioning & Node.js](https://nodesource.com/blog/semver-a-primer/)
- [The Art of Node](https://github.com/maxogden/art-of-node#modules)
- [Node School](http://nodeschool.io/)

# Modules

- [Publishing NPM Packages for Developers](https://github.com/ellerbrock/tutorial-publishing-npm-packages)
- [Node.js Modules Documentation](https://nodejs.org/api/modules.html)
- [Node.js Module Pattern - simple examples](https://darrenderidder.github.io/talks/ModulePatterns/)
- [Understanding module.exports and exports in Node.js](https://www.sitepoint.com/understanding-module-exports-exports-node-js/)
- [An overview of Node: Modules and npm](http://book.mixu.net/node/ch8.html)

## Simple Module Example

index.js:

```
const pkg = require("./package.json");

module.exports = () => pkg;
```

run.js:

```
const pkg = require("./index");

console.log('Name: ' + pkg().name + ' Version: ' + pkg().version);
```

# Asynchronous Javascript

## Promises

- [MDN Promises](https://developer.mozilla.org/en/docs/Web/JavaScript/Reference/Global_Objects/Promise)
- [Promises in Node.js with Q – An Alternative to Callbacks](https://strongloop.com/strongblog/promises-in-node-js-with-q-an-alternative-to-callbacks/)
- [JavaScript Promise API](https://davidwalsh.name/promises)
- [Awesome Promises](https://github.com/wbinnssmith/awesome-promises)
- [Bluebird.js](http://bluebirdjs.com/docs/getting-started.html)

## Callbacks

- [Callbacks MDN](https://developer.mozilla.org/en-US/docs/Mozilla/js-ctypes/Using_js-ctypes/Declaring_and_Using_Callbacks)
- [You Don't Know JS: Async & Performance](https://github.com/getify/You-Dont-Know-JS/blob/master/async%20&%20performance/README.md#you-dont-know-js-async--performance)

# Applications

## Flat File CMS

- [Hexo](https://hexo.io/)
- [Raneto](http://raneto.com/)
- [MetalSmith](http://www.metalsmith.io/)
- [WinterSmith](http://wintersmith.io/)

## Blog Systems

- [Ghost](https://ghost.org/)

# Security

- [Node.js Security Checklist](https://blog.risingstack.com/node-js-security-checklist/)
- [Node.js Security Tips](https://blog.risingstack.com/node-js-security-tips/)
- [nsp](https://nodesecurity.io/opensource) - command line interface to the Node Security Platform
- [http authentication](https://github.com/request/request#http-authentication)

# Travis CI

- [Building a Node.js project](https://docs.travis-ci.com/user/languages/javascript-with-nodejs)
- [validate your .travis.yaml](http://yaml.travis-ci.org/)

# Semantic Version Examples

- ~1.2.3 installs all the patches (>=1.2.3 <1.3.0)
- ^1.5.1 installs patch and minor versions (>=1.5.1 <2.0.0)

# Install Node LTS with homebrew on OS X

```
brew tap homebrew/versions
brew install homebrew/versions/node4-lts
brew link --overwrite node4-lts
```

- [Downgrade Node.js to a Specific Version Using Homebrew](http://www.wiredatom.com/blog/2015/03/30/downgrade-node-js-to-a-specific-version-using-homebrew/)
- [Switch Node.js versions with the Node Version Manager (nvm)](http://michael-kuehnel.de/node.js/2015/09/08/using-vm-to-switch-node-versions.html)

### Contact / Social Media

*Get the latest News about Web Development, Open Source, Tooling, Server & Security*

[![Twitter](https://github.frapsoft.com/social/twitter.png)](https://twitter.com/frapsoft/)
[![Facebook](https://github.frapsoft.com/social/facebook.png)](https://www.facebook.com/frapsoft/)
[![Google+](https://github.frapsoft.com/social/google-plus.png)](https://plus.google.com/116540931335841862774)
[![Gitter](https://github.frapsoft.com/social/gitter.png)](https://gitter.im/frapsoft/frapsoft/)
[![Github](https://github.frapsoft.com/social/github.png)](https://github.com/ellerbrock/)

### Development by 

Developer / Author: [Maik Ellerbrock](https://github.com/ellerbrock/)  
Company: [Frapsoft](https://github.com/frapsoft/)


### License 

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />

This work by <a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/ellerbrock/" property="cc:attributionName" rel="cc:attributionURL">Maik Ellerbrock</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.