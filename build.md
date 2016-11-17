#### Test (Fail) 93765317 Build Logs


```


```

```
Already up-to-date.

From https://github.com/thaliproject/Thali_CordovaPlugin
   29ac2d0..2ca5349  evabishchevich_1517 -> origin/evabishchevich_1517
   57daca3..75fe588  iOS_update-env -> origin/iOS_update-env

```

```
Your branch is up-to-date with 'origin/master'.
Branch iOS set up to track remote branch iOS from origin.
Merge made by the 'recursive' strategy.
 test/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js | 2 +-
 1 file changed, 1 insertion(+), 1 deletion(-)

Already on 'master'
Switched to a new branch 'iOS'
Note: checking out '75fe588'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by performing another checkout.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -b with the checkout command again. Example:

  git checkout -b <new-branch-name>

HEAD is now at 75fe588... enable updateEnvironmentSettings.js for CI

```

```
start build.sh
Cordova version:
6.3.1
start setUpDesktop.sh
[0;31merror: command 'node updateEnvironmentSettings.js' failed with code 1, file 'setUpDesktop.sh' on line 23[0m
[0;31merror: command 'thali/install/setUpDesktop.sh' failed with code 1, file 'build.sh' on line 44[0m
./build.sh CI FAILED - build.sh failure[0m

module.js:471
    throw err;
    ^

Error: Cannot find module '/Users/thali/Github/Thali_CordovaPlugin/updateEnvironmentSettings.js'
    at Function.Module._resolveFilename (module.js:469:15)
    at Function.Module._load (module.js:417:25)
    at Module.runMain (module.js:604:10)
    at run (bootstrap_node.js:394:7)
    at startup (bootstrap_node.js:149:9)
    at bootstrap_node.js:509:3

```

Error: Command failed: module.js:471
    throw err;
    ^

Error: Cannot find module '/Users/thali/Github/Thali_CordovaPlugin/updateEnvironmentSettings.js'
    at Function.Module._resolveFilename (module.js:469:15)
    at Function.Module._load (module.js:417:25)
    at Module.runMain (module.js:604:10)
    at run (bootstrap_node.js:394:7)
    at startup (bootstrap_node.js:149:9)
    at bootstrap_node.js:509:3
