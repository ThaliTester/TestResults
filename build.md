#### Test (Fail) 50650278 Build Logs


```


```

```
Already up-to-date.

From https://github.com/thaliproject/Thali_CordovaPlugin
   3a40166..1cef9bd  issue_302  -> origin/issue_302

```

```
Your branch is up-to-date with 'origin/master'.
Branch story_001 set up to track remote branch story_001 from origin.
Merge made by the 'recursive' strategy.
 .jshintrc | 3 ---
 1 file changed, 3 deletions(-)

Already on 'master'
Switched to a new branch 'story_001'
Note: checking out '1cef9bd'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by performing another checkout.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -b with the checkout command again. Example:

  git checkout -b <new-branch-name>

HEAD is now at 1cef9bd... Force CI

```

```
-e [0;31mcompilation aborted
 [0m
build aborted
 [0m

npm ERR! install Couldn't read dependencies
npm ERR! Error: Invalid name: "Thali Test Server"
npm ERR!     at ensureValidName (/Users/thali/.jx/npm/node_modules/read-package-json/node_modules/normalize-package-data/lib/fixer.js:300:15)
npm ERR!     at Object.module.exports.fixNameField (/Users/thali/.jx/npm/node_modules/read-package-json/node_modules/normalize-package-data/lib/fixer.js:204:5)
npm ERR!     at /Users/thali/.jx/npm/node_modules/read-package-json/node_modules/normalize-package-data/lib/normalize.js:30:38
npm ERR!     at Array.forEach (native)
npm ERR!     at normalize (/Users/thali/.jx/npm/node_modules/read-package-json/node_modules/normalize-package-data/lib/normalize.js:29:15)
npm ERR!     at final (/Users/thali/.jx/npm/node_modules/read-package-json/read-json.js:342:33)
npm ERR!     at then (/Users/thali/.jx/npm/node_modules/read-package-json/read-json.js:126:33)
npm ERR!     at /Users/thali/.jx/npm/node_modules/read-package-json/read-json.js:266:40
npm ERR!     at fs.js:259:8
npm ERR!     at /Users/thali/.jx/npm/node_modules/graceful-fs/graceful-fs.js:105:5
npm ERR! If you need help, you may report this *entire* log,
npm ERR! including the npm and node versions, at:
npm ERR!     <http://github.com/npm/npm/issues>

npm ERR! System Darwin 14.5.0
npm ERR! command "/usr/local/bin/jx" "/Users/thali/.jx/npm" "--loglevel" "http" "--color" "true" "install"
npm ERR! cwd /Users/thali/Github/testBuild/test/TestServer
npm ERR! node -v v0.10.40
npm ERR! npm -v 1.4.14
npm ERR! 
npm ERR! Additional logging details can be found in:
npm ERR!     /Users/thali/Github/testBuild/test/TestServer/npm-debug.log
npm ERR! not ok code 0

```

Error: Command failed: npm ERR! install Couldn't read dependencies
npm ERR! Error: Invalid name: "Thali Test Server"
npm ERR!     at ensureValidName (/Users/thali/.jx/npm/node_modules/read-package-json/node_modules/normalize-package-data/lib/fixer.js:300:15)
npm ERR!     at Object.module.exports.fixNameField (/Users/thali/.jx/npm/node_modules/read-package-json/node_modules/normalize-package-data/lib/fixer.js:204:5)
npm ERR!     at /Users/thali/.jx/npm/node_modules/read-package-json/node_modules/normalize-package-data/lib/normalize.js:30:38
npm ERR!     at Array.forEach (native)
npm ERR!     at normalize (/Users/thali/.jx/npm/node_modules/read-package-json/node_modules/normalize-package-data/lib/normalize.js:29:15)
npm ERR!     at final (/Users/thali/.jx/npm/node_modules/read-package-json/read-json.js:342:33)
npm ERR!     at then (/Users/thali/.jx/npm/node_modules/read-package-json/read-json.js:126:33)
npm ERR!     at /Users/thali/.jx/npm/node_modules/read-package-json/read-json.js:266:40
npm ERR!     at fs.js:259:8
npm ERR!     at /Users/thali/.jx/npm/node_modules/graceful-fs/graceful-fs.js:105:5
npm ERR! If you need help, you may report this *entire* log,
npm ERR! including the npm and node versions, at:
npm ERR!     <http://github.com/npm/npm/issues>

npm ERR! System Darwin 14.5.0
npm ERR! command "/usr/local/bin/jx" "/Users/thali/.jx/npm" "--loglevel" "http" "--color" "true" "install"
npm ERR! cwd /Users/thali/Github/testBuild/test/TestServer
npm ERR! node -v v0.10.40
npm ERR! npm -v 1.4.14
npm ERR! 
npm ERR! Additional logging details can be found in:
npm ERR!     /Users/thali/Github/testBuild/test/TestServer/npm-debug.log
npm ERR! not ok code 0
