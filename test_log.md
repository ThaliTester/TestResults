#### Test 797510159e44f0b Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":4}}
2016-08-12T20:00:29.554Z - info: Require 0 ios devices

2016-08-12T20:00:29.573Z - info: Require 4 android devices

2016-08-12T20:00:29.634Z - info: listening on *:3000

2016-08-12T20:00:34.193Z - debug: Device presented: motorola-Nexus 6 (5561117b-1c15-4880-a884-219941d4f467) - android 6.0.1

2016-08-12T20:00:34.378Z - debug: Device presented: samsung-SM-G900F (97f84159-68d1-4b43-971d-ed9782d766cc) - android 6.0.1

2016-08-12T20:00:35.163Z - debug: Device presented: motorola-Nexus 6 (5561117b-1c15-4880-a884-219941d4f467) - android 6.0.1

2016-08-12T20:00:35.165Z - info: Updating existing device: motorola-Nexus 6 (5561117b-1c15-4880-a884-219941d4f467)

2016-08-12T20:00:35.385Z - debug: Device presented: samsung-SM-G900F (97f84159-68d1-4b43-971d-ed9782d766cc) - android 6.0.1

2016-08-12T20:00:35.388Z - info: Updating existing device: samsung-SM-G900F (97f84159-68d1-4b43-971d-ed9782d766cc)

2016-08-12T20:00:59.667Z - debug: Device presented: LGE-LG-D855 (6bcccf89-ca2a-4d10-a00a-a5c93706ea5a) - android 5.0

2016-08-12T20:01:03.687Z - debug: Device presented: LGE-LG-D722 (6e0214f1-a0d9-4e49-baa5-d49132255a83) - android 5.0.2

2016-08-12T20:01:03.690Z - info: All 4 android devices are present

2016-08-12T20:01:03.692Z - info: Disqualifying device on which native unit tests failed: motorola-Nexus 6

2016-08-12T20:01:03.700Z - info: Disqualifying device on which native unit tests failed: samsung-SM-G900F

2016-08-12T20:01:03.703Z - info: Disqualifying device with unsupported hardware: LGE-LG-D855

2016-08-12T20:01:03.705Z - info: Disqualifying device with unsupported hardware: LGE-LG-D722

2016-08-12T20:01:03.713Z - debug:  TypeError: Cannot read property 'tests' of undefined
    at UnitTestFramework.startTests (/home/pi/Test/server_797510159e44f0b/test/TestServer/UnitTestFramework.js:99:38)
    at UnitTestFramework.TestFramework.addDevice (/home/pi/Test/server_797510159e44f0b/test/TestServer/TestFramework.js:162:10)
    at Socket.<anonymous> (/home/pi/Test/server_797510159e44f0b/test/TestServer/index.js:89:25)
    at Socket.emit (events.js:82:17)
    at Socket.onevent (/home/pi/Test/server_797510159e44f0b/test/TestServer/node_modules/socket.io/lib/socket.js:330:8)
    at Socket.onpacket (/home/pi/Test/server_797510159e44f0b/test/TestServer/node_modules/socket.io/lib/socket.js:290:12)
    at Client.ondecoded (/home/pi/Test/server_797510159e44f0b/test/TestServer/node_modules/socket.io/lib/client.js:193:14)
    at Decoder.Emitter.emit (/home/pi/Test/server_797510159e44f0b/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:20)
    at Decoder.add (/home/pi/Test/server_797510159e44f0b/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/index.js:247:12)
    at Client.ondata (/home/pi/Test/server_797510159e44f0b/test/TestServer/node_modules/socket.io/lib/client.js:175:18)

2016-08-12T20:01:03.757Z - info: Socket to device LGE-LG-D722 disconnected: client error

2016-08-12T20:01:04.767Z - info: Socket to device LGE-LG-D855 disconnected: transport close

2016-08-12T20:01:04.907Z - info: Socket to device motorola-Nexus 6 disconnected: transport close

2016-08-12T20:01:05.899Z - info: Socket to device samsung-SM-G900F disconnected: transport close


 
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

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
STOP log received from  ZX1G429CRK Test has  FAILED
STOP log received from  0be0c6c6 Test has  FAILED
Device test finished on ZX1G429CRK 
Device test finished on 0be0c6c6 
Android task is completed. [FAILED]
```
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/797510159e44f0b_Check_811_failures_in_CI_do_not_merge__czyzm/thali01_motorola-Nexus 6.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/797510159e44f0b_Check_811_failures_in_CI_do_not_merge__czyzm/thali01_samsung-SM-G900F.md)

####Node name: thali02
Console output:
```
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
STOP log received from  LGD855a6933058 Test has  SUCCEEDED
Device test finished on LGD855a6933058 
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/797510159e44f0b_Check_811_failures_in_CI_do_not_merge__czyzm/thali02_LGE-LG-D722.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/797510159e44f0b_Check_811_failures_in_CI_do_not_merge__czyzm/thali02_LGE-LG-D855.md)




