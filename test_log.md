#### Test 821470465fdde63 Logs

#### Test Server Logs
```
Error: Command failed: 

/home/pi/Test/server_821470465fdde63/test/TestServer/UnitTestFramework.js:41
+UnitTestFramework.prototype.abortRun =
^

ReferenceError: Invalid left-hand side in assignment
    at Object.<anonymous> (/home/pi/Test/server_821470465fdde63/test/TestServer/UnitTestFramework.js:41:1)
    at Module._compile (module.js:619:26)
    at Object.Module._extensions..js (module.js:649:10)
    at Module.load (module.js:440:36)
    at Function.Module._load (module.js:405:12)
    at Module.require (module.js:475:17)
    at require (module.js:493:17)
    at Object.<anonymous> (/home/pi/Test/server_821470465fdde63/test/TestServer/index.js:19:25)
    at Module._compile (module.js:619:26)
    at Object.Module._extensions..js (module.js:649:10)

IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":8}}

 
Run IS script aborted
 
One or more Android tests are failed.
 [0m


/home/pi/Test/server_821470465fdde63/test/TestServer/UnitTestFramework.js:41
+UnitTestFramework.prototype.abortRun =
^

ReferenceError: Invalid left-hand side in assignment
    at Object.<anonymous> (/home/pi/Test/server_821470465fdde63/test/TestServer/UnitTestFramework.js:41:1)
    at Module._compile (module.js:619:26)
    at Object.Module._extensions..js (module.js:649:10)
    at Module.load (module.js:440:36)
    at Function.Module._load (module.js:405:12)
    at Module.require (module.js:475:17)
    at require (module.js:493:17)
    at Object.<anonymous> (/home/pi/Test/server_821470465fdde63/test/TestServer/index.js:19:25)
    at Module._compile (module.js:619:26)
    at Object.Module._extensions..js (module.js:649:10)


```


Logs for system : 
```

android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


TIMEOUT REACHED!
```
###Android Logs
####Node name: thali01
Console output:
```

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
STOP log received from  0be0c6c6 Test has  SUCCEEDED
Device test finished on 0be0c6c6 
STOP log received from  ZX1G429CRK Test has  SUCCEEDED
Device test finished on ZX1G429CRK 
Android task is completed. [SUCCESS]
```
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/821470465fdde63_Handling_variable_number_of_devices_in_CI_and_failing_native_tests_czyzm/thali01_motorola-Nexus 6.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/821470465fdde63_Handling_variable_number_of_devices_in_CI_and_failing_native_tests_czyzm/thali01_samsung-SM-G900F.md)

####Node name: thali02
Console output:
```
Error! Unexpected exit on device LGD7228ee9cf5b app:com.test.thalitest code:null 
child process exited with code null on device LGD7228ee9cf5b 
Error! Unexpected exit on device LGD855a6933058 app:com.test.thalitest code:null 
child process exited with code null on device LGD855a6933058 
Android task is completed. [FAILED]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/821470465fdde63_Handling_variable_number_of_devices_in_CI_and_failing_native_tests_czyzm/thali02_LGE-LG-D722.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/821470465fdde63_Handling_variable_number_of_devices_in_CI_and_failing_native_tests_czyzm/thali02_LGE-LG-D855.md)

####Node name: thali03
Console output:
```
STOP log received from  f56ad48d Test has  SUCCEEDED
STOP log received from  7970f88c Test has  SUCCEEDED
Device test finished on 7970f88c 
Device test finished on f56ad48d 
Android task is completed. [SUCCESS]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/821470465fdde63_Handling_variable_number_of_devices_in_CI_and_failing_native_tests_czyzm/thali03_samsung-SM-A500FU.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/821470465fdde63_Handling_variable_number_of_devices_in_CI_and_failing_native_tests_czyzm/thali03_samsung-SM-A300FU.md)

####Node name: thali04
Console output:
```
STOP log received from  4325e43f Test has  SUCCEEDED
STOP log received from  HT54GYJ03048 Test has  SUCCEEDED
Device test finished on 4325e43f 
Device test finished on HT54GYJ03048 
Android task is completed. [SUCCESS]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/821470465fdde63_Handling_variable_number_of_devices_in_CI_and_failing_native_tests_czyzm/thali04_samsung-SM-A300FU.md)

[HTC-HTC One M9](https://github.com/ThaliTester/TestResults/blob/821470465fdde63_Handling_variable_number_of_devices_in_CI_and_failing_native_tests_czyzm/thali04_HTC-HTC One M9.md)




