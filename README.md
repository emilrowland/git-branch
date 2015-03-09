# git-branch [![NPM version](https://badge.fury.io/js/git-branch.svg)](http://badge.fury.io/js/git-branch)

> Get the current branch for a local git repository.

## Install with [npm](npmjs.org)

```bash
npm i git-branch --save
```

## Usage

```js
var branch = require('git-branch');

// async
branch(function (err, res) {
  //=> 'master'
});

// sync
branch.sync();
//=> 'master'
```

## Related projects
* [parse-git-config](https://github.com/jonschlinkert/parse-git-config): Parse `.git/config` into a JavaScript object. sync or async.
* [git-username](https://github.com/jonschlinkert/git-username): Get the username from a git remote origin URL.
* [git-user-name](https://github.com/jonschlinkert/git-user-name): Get a user's name from git config at the project or global scope, depending on what git uses in the current context.
* [git-repo-name](https://github.com/jonschlinkert/git-repo-name): Get the repository name from the git remote origin URL.  

## Running tests
Install dev dependencies.

```bash
npm i -d && npm test
```


## Contributing
Pull requests and stars are always welcome. For bugs and feature requests, [please create an issue](https://github.com/jonschlinkert/git-branch/issues)


## Author

**Jon Schlinkert**
 
+ [github/jonschlinkert](https://github.com/jonschlinkert)
+ [twitter/jonschlinkert](http://twitter.com/jonschlinkert) 

## License
Copyright (c) 2014-2015 Jon Schlinkert  
Released under the MIT license

***

_This file was generated by [verb-cli](https://github.com/assemble/verb-cli) on March 09, 2015._
