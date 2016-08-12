#### Test 7975101549b9187 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":3}}
2016-08-12T11:47:49.875Z - info: Require 0 ios devices

2016-08-12T11:47:49.893Z - info: Require 3 android devices

2016-08-12T11:47:49.955Z - info: listening on *:3000

2016-08-12T11:47:55.075Z - debug: Device presented: motorola-Nexus 6 (2c3edbe5-ec66-47fc-8031-8c573430b95f) - android 6.0.1

2016-08-12T11:47:56.014Z - debug: Device presented: motorola-Nexus 6 (2c3edbe5-ec66-47fc-8031-8c573430b95f) - android 6.0.1

2016-08-12T11:47:56.017Z - info: Updating existing device: motorola-Nexus 6 (2c3edbe5-ec66-47fc-8031-8c573430b95f)

2016-08-12T11:48:23.862Z - debug: Device presented: LGE-LG-D722 (067fc63a-9677-4d73-8f74-7fb75aab8a8f) - android 5.0.2

2016-08-12T11:48:31.431Z - debug: Device presented: LGE-LG-D855 (0783888c-b661-4b3c-80b0-56f079887262) - android 5.0

2016-08-12T11:48:31.432Z - info: All 3 android devices are present

2016-08-12T11:48:31.435Z - info: Disqualifying device with unsupported hardware: LGE-LG-D722

2016-08-12T11:48:31.441Z - info: Disqualifying device with unsupported hardware: LGE-LG-D855

2016-08-12T11:48:31.452Z - warn: Aborting unit test run for android. At least 2 devices needed, having 1 device(s)

2016-08-12T11:48:31.456Z - debug:  TypeError: Cannot call method 'abortRun' of undefined
    at UnitTestFramework.startTests (/home/pi/Test/server_7975101549b9187/test/TestServer/UnitTestFramework.js:111:10)
    at UnitTestFramework.TestFramework.addDevice (/home/pi/Test/server_7975101549b9187/test/TestServer/TestFramework.js:157:10)
    at Socket.<anonymous> (/home/pi/Test/server_7975101549b9187/test/TestServer/index.js:89:25)
    at Socket.emit (events.js:82:17)
    at Socket.onevent (/home/pi/Test/server_7975101549b9187/test/TestServer/node_modules/socket.io/lib/socket.js:330:8)
    at Socket.onpacket (/home/pi/Test/server_7975101549b9187/test/TestServer/node_modules/socket.io/lib/socket.js:290:12)
    at Client.ondecoded (/home/pi/Test/server_7975101549b9187/test/TestServer/node_modules/socket.io/lib/client.js:193:14)
    at Decoder.Emitter.emit (/home/pi/Test/server_7975101549b9187/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:20)
    at Decoder.add (/home/pi/Test/server_7975101549b9187/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/index.js:247:12)
    at Client.ondata (/home/pi/Test/server_7975101549b9187/test/TestServer/node_modules/socket.io/lib/client.js:175:18)

2016-08-12T11:48:31.502Z - info: Socket to device LGE-LG-D855 disconnected: client error

2016-08-12T11:48:32.676Z - info: Socket to device LGE-LG-D722 disconnected: transport close

2016-08-12T12:07:05.748Z - info: Socket to device motorola-Nexus 6 disconnected: transport close


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

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
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1G429CRK app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1G429CRK 
Android task is completed. [FAILED]
```
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/7975101549b9187_Check_811_failures_in_CI_do_not_merge__czyzm/thali01_motorola-Nexus 6.md)

####Node name: thali02
Console output:
```
STOP log received from  LGD855a6933058 Test has  SUCCEEDED
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on LGD855a6933058 
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/7975101549b9187_Check_811_failures_in_CI_do_not_merge__czyzm/thali02_LGE-LG-D722.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/7975101549b9187_Check_811_failures_in_CI_do_not_merge__czyzm/thali02_LGE-LG-D855.md)




