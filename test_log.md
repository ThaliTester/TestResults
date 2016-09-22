#### Test 86330306c7a531c Logs

#### Test Server Logs
```
Error: Command failed: IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":3}}
2016-09-22 17:39:50 - ERROR TestServerProcess: 'uncaught exception, error: 'AssertionError: equals arrays expected, received array 1: 'android', array 2: 'android,desktop,ios'', stack: 'AssertionError: equals arrays expected, received array 1: 'android', array 2: 'android,desktop,ios'
    at Object.module.exports.arrayEquals (/home/pi/Test/server_86330306c7a531c/test/TestServer/utils/asserts.js:71:3)
    at UnitTestFramework.TestFramework._setOptions (/home/pi/Test/server_86330306c7a531c/test/TestServer/TestFramework.js:86:11)
    at UnitTestFramework.TestFramework (/home/pi/Test/server_86330306c7a531c/test/TestServer/TestFramework.js:23:8)
    at new UnitTestFramework (/home/pi/Test/server_86330306c7a531c/test/TestServer/UnitTestFramework.js:23:28)
    at Object.<anonymous> (/home/pi/Test/server_86330306c7a531c/test/TestServer/index.js:28:23)
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

android : Error: Command failed: CopyLog Failed (thali05): ssh: connect to host 192.168.1.54 port 22: Operation timed out

Error: Command failed: packet_write_wait: Connection to 192.168.1.54: Broken pipe
packet_write_wait: Connection to 192.168.1.54: Broken pipe


TIMEOUT REACHED!CopyLog Failed (thali05): ssh: connect to host 192.168.1.54 port 22: Operation timed out


```
###Android Logs
####Node name: thali05



