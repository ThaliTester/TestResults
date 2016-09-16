#### Test 85606604eee3408 Logs

#### Test Server Logs
```
Error: Command failed: IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":3}}
2016-09-16 18:30:06 - ERROR TestServerProcess: 'uncaught exception, error: 'AssertionError: equals arrays expected, received array 1: 'android', array 2: 'android,ios'', stack: 'AssertionError: equals arrays expected, received array 1: 'android', array 2: 'android,ios'
    at Object.module.exports.arrayEquals (/home/pi/Test/server_85606604eee3408/test/TestServer/utils/asserts.js:71:3)
    at UnitTestFramework.TestFramework._setOptions (/home/pi/Test/server_85606604eee3408/test/TestServer/TestFramework.js:77:11)
    at UnitTestFramework.TestFramework (/home/pi/Test/server_85606604eee3408/test/TestServer/TestFramework.js:22:8)
    at new UnitTestFramework (/home/pi/Test/server_85606604eee3408/test/TestServer/UnitTestFramework.js:24:28)
    at Object.<anonymous> (/home/pi/Test/server_85606604eee3408/test/TestServer/index.js:28:23)
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

android : Error: Command failed: CopyLog Failed (thali04): ssh: connect to host 192.168.1.53 port 22: Operation timed out

Error: Command failed: packet_write_wait: Connection to 192.168.1.53: Broken pipe

Trying to deploy app to android: ENU7N16516000107

Deploying to android ENU7N16516000107

App was succesfully deployed to ENU7N16516000107

Trying to deploy app to android: ce061606e320561102

Deploying to android ce061606e320561102

App was succesfully deployed to ce061606e320561102

Trying to deploy app to android: ce0616068b9f212302

Deploying to android ce0616068b9f212302

App was succesfully deployed to ce0616068b9f212302

Trying to start application ThaliTest on ENU7N16516000107

Trying to start application ThaliTest on ce061606e320561102

Trying to start application ThaliTest on ce0616068b9f212302
child process exited with code null
child process exited with code null
child process exited with code null
Android task is completed.
packet_write_wait: Connection to 192.168.1.53: Broken pipe


TIMEOUT REACHED!CopyLog Failed (thali04): ssh: connect to host 192.168.1.53 port 22: Operation timed out


```
###Android Logs
####Node name: thali04



