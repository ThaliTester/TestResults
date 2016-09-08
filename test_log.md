#### Test 845006541145c7f Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":10}}
2016-09-08T19:15:48.924Z - info: listening on *:3000

2016-09-08T19:15:48.905Z - error: AssertionError: equals arrays expected, received array 1: 'android', array 2: 'android,ios'
    at Object.module.exports.arrayEquals (/home/pi/Test/server_845006541145c7f/test/TestServer/utils/asserts.js:71:3)
    at UnitTestFramework.TestFramework (/home/pi/Test/server_845006541145c7f/test/TestServer/TestFramework.js:42:11)
    at new UnitTestFramework (/home/pi/Test/server_845006541145c7f/test/TestServer/UnitTestFramework.js:22:28)
    at Object.<anonymous> (/home/pi/Test/server_845006541145c7f/test/TestServer/index.js:73:25)
    at Module._compile (module.js:619:26)
    at Object.Module._extensions..js (module.js:649:10)
    at Module.load (module.js:440:36)
    at Function.Module._load (module.js:405:12)
    at Function.Module.runMain (module.js:849:12)
    at startup (node.js:485:18)
    at node.js:1604:3


```


Logs for system : 
```

android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###Android Logs
####Node name: thali01
Console output:
```

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1G429CRK app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1G429CRK 
Error! Unexpected exit on device 0be0c6c6 app:com.test.thalitest code:null 
child process exited with code null on device 0be0c6c6 
Android task is completed. [FAILED]
```
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/845006541145c7f_New_test_server_andrew-aladev/thali01_motorola-Nexus 6.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/845006541145c7f_New_test_server_andrew-aladev/thali01_samsung-SM-G900F.md)

####Node name: thali02
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGD7228ee9cf5b app:com.test.thalitest code:0 
child process exited with code 0 on device LGD7228ee9cf5b 
Error! Unexpected exit on device LGD855a6933058 app:com.test.thalitest code:null 
child process exited with code null on device LGD855a6933058 
Android task is completed. [FAILED]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/845006541145c7f_New_test_server_andrew-aladev/thali02_LGE-LG-D722.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/845006541145c7f_New_test_server_andrew-aladev/thali02_LGE-LG-D855.md)

####Node name: thali03
Console output:
```
STOP log received from  7970f88c Test has  SUCCEEDED
STOP log received from  f56ad48d Test has  SUCCEEDED
Device test finished on 7970f88c 
Device test finished on f56ad48d 
Android task is completed. [SUCCESS]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/845006541145c7f_New_test_server_andrew-aladev/thali03_samsung-SM-A500FU.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/845006541145c7f_New_test_server_andrew-aladev/thali03_samsung-SM-A300FU.md)

####Node name: thali04
Console output:
```
STOP log received from  HT54GYJ03048 Test has  SUCCEEDED
Device test finished on HT54GYJ03048 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:null 
child process exited with code null on device 4325e43f 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/845006541145c7f_New_test_server_andrew-aladev/thali04_samsung-SM-A300FU.md)

[HTC-HTC One M9](https://github.com/ThaliTester/TestResults/blob/845006541145c7f_New_test_server_andrew-aladev/thali04_HTC-HTC One M9.md)

####Node name: thali05
Console output:
```

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device e8c09bab app:com.test.thalitest code:0 
child process exited with code 0 on device e8c09bab 
Error! Unexpected exit on device ce061606e320561102 app:com.test.thalitest code:0 
child process exited with code 0 on device ce061606e320561102 
Android task is completed. [FAILED]
```
[samsung-SM-T719](https://github.com/ThaliTester/TestResults/blob/845006541145c7f_New_test_server_andrew-aladev/thali05_samsung-SM-T719.md)

[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/845006541145c7f_New_test_server_andrew-aladev/thali05_samsung-SM-G935F.md)




