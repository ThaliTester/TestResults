#### Test 86373152291968c Logs

#### Test Server Logs
```
Error: Command failed: IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":3}}
2016-09-23 08:27:54 - ERROR TestServerProcess: 'uncaught exception, error: 'AssertionError: equals arrays expected, received array 1: 'android', array 2: 'android,desktop,ios'', stack: 'AssertionError: equals arrays expected, received array 1: 'android', array 2: 'android,desktop,ios'
    at Object.module.exports.arrayEquals (/home/pi/Test/server_86373152291968c/test/TestServer/utils/asserts.js:71:3)
    at UnitTestFramework.TestFramework._setOptions (/home/pi/Test/server_86373152291968c/test/TestServer/TestFramework.js:86:11)
    at UnitTestFramework.TestFramework (/home/pi/Test/server_86373152291968c/test/TestServer/TestFramework.js:23:8)
    at new UnitTestFramework (/home/pi/Test/server_86373152291968c/test/TestServer/UnitTestFramework.js:23:28)
    at Object.<anonymous> (/home/pi/Test/server_86373152291968c/test/TestServer/index.js:28:23)
    at Module._compile (module.js:619:26)
    at Object.Module._extensions..js (module.js:649:10)
    at Module.load (module.js:440:36)
    at Function.Module._load (module.js:405:12)
    at Function.Module.runMain (module.js:849:12)
    at startup (node.js:485:18)
    at node.js:1604:3''


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


TIMEOUT REACHED!
```
###Android Logs
####Node name: thali05
Console output:
```
Stopping app on  ce0616068b9f212302
Uninstalling app on  ce0616068b9f212302
Stopping app on  ce061606e320561102
Uninstalling app on  ce061606e320561102
Stopping app on  ENU7N16516000107
Uninstalling app on  ENU7N16516000107

All devices are ready!

Deploying to ce0616068b9f212302
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ce0616068b9f212302

Deploying to ce061606e320561102
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ce061606e320561102

Deploying to ENU7N16516000107
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ENU7N16516000107

Starting application ThaliTest on ce0616068b9f212302

Starting application ThaliTest on ce061606e320561102

Starting application ThaliTest on ENU7N16516000107

App was succesfully started on ce0616068b9f212302

App was succesfully started on ce061606e320561102

App was succesfully started on ENU7N16516000107

Error! Unexpected exit on device ce0616068b9f212302 app:com.test.thalitest code:null 
Child process exited with code null on device ce0616068b9f212302
Error! Unexpected exit on device ce061606e320561102 app:com.test.thalitest code:null 
Child process exited with code null on device ce061606e320561102
Error! Unexpected exit on device ENU7N16516000107 app:com.test.thalitest code:null 
Child process exited with code null on device ENU7N16516000107
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/86373152291968c__899_2_Added__discoveryDos__event_artemjackson/thali05_samsung-SM-G930F.md)

[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/86373152291968c__899_2_Added__discoveryDos__event_artemjackson/thali05_samsung-SM-G935F.md)

[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/86373152291968c__899_2_Added__discoveryDos__event_artemjackson/thali05_Huawei-Nexus 6P.md)




