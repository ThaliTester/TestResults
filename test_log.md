#### Test 9945185497797f9 Logs

#### Test Server Logs
```
Error: Command failed: index.js failed [ 1 ]
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":5,"android":3}}
2016-12-27 15:21:08 - INFO HttpServer: 'listening on *:3000'

2016-12-27 15:21:20 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: 'a76d0aa3-e683-43e7-8587-4b89e6e1c701', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-12-27 15:21:20 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'samsung-SM-G935F''

2016-12-27 15:21:20 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'client namespace disconnect''

2016-12-27 15:21:24 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '0ac1a246-61ec-4fbd-8e27-861ced325ce1', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-12-27 15:21:24 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'samsung-SM-G930F''

2016-12-27 15:21:24 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'client namespace disconnect''

2016-12-27 15:22:40 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '41c75cbc-8a83-442d-9c14-e24e85d9a206', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-12-27 15:22:40 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2016-12-27 15:26:08 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_9945185497797f9/test/TestServer/index.js:45:9)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-12-27 15:26:08 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

[0;31merror: command 'sudo jx ______.js all' failed with code 1, file 'bash' on line 30[0m
One or more Android tests are failed.
 [0m
index.js failed [ 1 ]

```


Logs for system : 
```

ios : false

android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


TIMEOUT REACHED!
```
###Android Logs
####Node name: thali02
Console output:
```
Stopping app on  ce0616068b9f212302
Uninstalling app on  ce0616068b9f212302

All devices are ready!

Deploying to ce0616068b9f212302
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ce0616068b9f212302

Starting application ThaliTest on ce0616068b9f212302

App was succesfully started on ce0616068b9f212302

STOP log received from ce0616068b9f212302
Test has FAILED

Device test finished on ce0616068b9f212302 
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/9945185497797f9_Changed_wifiPeerAvailabilityChanged_in_wifiBasedNativeMock_squid48/thali02_samsung-SM-G930F.md)

####Node name: thali03
Console output:
```
Stopping app on  ce061606c181d71003
Uninstalling app on  ce061606c181d71003

All devices are ready!

Deploying to ce061606c181d71003
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
Deploying to ce061606c181d71003
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ce061606c181d71003

Starting application ThaliTest on ce061606c181d71003

App was succesfully started on ce061606c181d71003

STOP log received from ce061606c181d71003
Test has FAILED

Device test finished on ce061606c181d71003 
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/9945185497797f9_Changed_wifiPeerAvailabilityChanged_in_wifiBasedNativeMock_squid48/thali03_samsung-SM-G930F.md)

####Node name: thali04
Console output:
```
Stopping app on  ce061606e320561102
Uninstalling app on  ce061606e320561102

All devices are ready!

Deploying to ce061606e320561102
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
Deploying to ce061606e320561102
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ce061606e320561102

Starting application ThaliTest on ce061606e320561102

App was succesfully started on ce061606e320561102

STOP log received from ce061606e320561102
Test has FAILED

Device test finished on ce061606e320561102 
Android task is completed. [FAILED]
```
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/9945185497797f9_Changed_wifiPeerAvailabilityChanged_in_wifiBasedNativeMock_squid48/thali04_samsung-SM-G935F.md)




###iOS Logs
[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/9945185497797f9_Changed_wifiPeerAvailabilityChanged_in_wifiBasedNativeMock_squid48/iOS_ipad-air-2-1.md)

[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/9945185497797f9_Changed_wifiPeerAvailabilityChanged_in_wifiBasedNativeMock_squid48/iOS_iphone-5s-mfts.md)

[iphone-6-2](https://github.com/ThaliTester/TestResults/blob/9945185497797f9_Changed_wifiPeerAvailabilityChanged_in_wifiBasedNativeMock_squid48/iOS_iphone-6-2.md)

[ipad-mini-mfts](https://github.com/ThaliTester/TestResults/blob/9945185497797f9_Changed_wifiPeerAvailabilityChanged_in_wifiBasedNativeMock_squid48/iOS_ipad-mini-mfts.md)

[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/9945185497797f9_Changed_wifiPeerAvailabilityChanged_in_wifiBasedNativeMock_squid48/iOS_iphone-5s-1.md)


