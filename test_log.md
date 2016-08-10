#### Test 797510157a5d8bb Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":2}}
2016-08-10T05:40:48.751Z - info: Require NaN ios devices

2016-08-10T05:40:48.770Z - info: Require 2 android devices

2016-08-10T05:40:48.829Z - info: listening on *:3000

2016-08-10T05:41:33.625Z - debug: Device presented: LGE-LG-D855 (49f77b9f-cc02-4e67-8f3c-f5862c547107) - android 5.0

2016-08-10T05:41:49.182Z - debug: Device presented: LGE-LG-D722 (2fed5476-02ea-4c02-abb1-00a6b5a17c84) - android 5.0.2

2016-08-10T05:41:49.185Z - info: All 2 android devices are present

2016-08-10T05:41:49.187Z - info: Disqualifying device with unsupported hardware: LGE-LG-D855

2016-08-10T05:41:49.194Z - info: Disqualifying device with unsupported hardware: LGE-LG-D722

2016-08-10T05:41:49.203Z - debug:  TypeError: Cannot read property 'tests' of undefined
    at UnitTestFramework.startTests (/home/pi/Test/server_797510157a5d8bb/test/TestServer/UnitTestFramework.js:74:38)
    at UnitTestFramework.TestFramework.addDevice (/home/pi/Test/server_797510157a5d8bb/test/TestServer/TestFramework.js:157:10)
    at Socket.<anonymous> (/home/pi/Test/server_797510157a5d8bb/test/TestServer/index.js:89:25)
    at Socket.emit (events.js:82:17)
    at Socket.onevent (/home/pi/Test/server_797510157a5d8bb/test/TestServer/node_modules/socket.io/lib/socket.js:330:8)
    at Socket.onpacket (/home/pi/Test/server_797510157a5d8bb/test/TestServer/node_modules/socket.io/lib/socket.js:290:12)
    at Client.ondecoded (/home/pi/Test/server_797510157a5d8bb/test/TestServer/node_modules/socket.io/lib/client.js:193:14)
    at Decoder.Emitter.emit (/home/pi/Test/server_797510157a5d8bb/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:20)
    at Decoder.add (/home/pi/Test/server_797510157a5d8bb/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/index.js:247:12)
    at Client.ondata (/home/pi/Test/server_797510157a5d8bb/test/TestServer/node_modules/socket.io/lib/client.js:175:18)

2016-08-10T05:41:49.250Z - info: Socket to device LGE-LG-D722 disconnected: client error

2016-08-10T05:41:50.180Z - info: Socket to device LGE-LG-D855 disconnected: transport close


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

android : No Error
```


###Android Logs
####Node name: thali05
Console output:
```
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
STOP log received from  LGD855a6933058 Test has  SUCCEEDED
Device test finished on LGD855a6933058 
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/797510157a5d8bb_Check_811_failures_in_CI_do_not_merge__czyzm/thali05_LGE-LG-D722.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/797510157a5d8bb_Check_811_failures_in_CI_do_not_merge__czyzm/thali05_LGE-LG-D855.md)


