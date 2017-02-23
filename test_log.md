#### Test 107380351ee7f847 Logs

#### Test Server Logs
```
Error: Command failed: index.js failed [ 1 ]
Enter ____.js
Targets defined
http required
Creating internal server
Got request
URL:  [ 'nodes', '3' ]
Got request
URL:  [ 'ios', '2' ]
Enter checkIt
Got request
URL:  [ 'droid', '1' ]
Got request
URL:  [ 'droid', '1' ]
Got request
URL:  [ 'droid', '1' ]
Enter checkIt
checkIt do the job
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":2,"android":3}}
2017-02-23 10:45:25 - INFO HttpServer: 'listening on *:3000'

2017-02-23 10:45:32 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: '0a5ece5e-d0a7-42f6-8fdb-84ae8f3f0601', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-23 10:45:32 - DEBUG TestFramework: 'device added, name: 'Apple-ipad-air-2-1''

2017-02-23 10:45:34 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: '0a5ece5e-d0a7-42f6-8fdb-84ae8f3f0601', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-23 10:45:34 - INFO TestFramework: 'updating existing device, name: 'Apple-ipad-air-2-1', uuid: '0a5ece5e-d0a7-42f6-8fdb-84ae8f3f0601', platformName: 'ios''

2017-02-23 10:45:53 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-mini-mfts', uuid: '3a5580d0-4bc8-4cfc-86d5-725b3293543d', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2017-02-23 10:45:53 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'Apple-ipad-mini-mfts''

2017-02-23 10:45:53 - INFO HttpServer: 'Socket to device name: 'Apple-ipad-mini-mfts' disconnected, reason: 'client namespace disconnect''

2017-02-23 10:46:05 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-6-2', uuid: 'ca98f373-99e6-488c-95b8-68cf1429a3df', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-23 10:46:05 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-6-2''
2017-02-23 10:46:05 - INFO TestFramework: 'all required 2 devices are present for platformName: 'ios''

2017-02-23 10:46:05 - ERROR HttpServer: 'unexpected server error: 'undefined''

2017-02-23 10:46:05 - ERROR TestServerProcess: 'uncaught exception, error: 'Error', stack: 'Error
    at Server._error (/home/pi/Test/server_107380351ee7f847/test/TestServer/HttpServer.js:78:9)
    at Socket.emit (events.js:82:17)
    at Socket.emit (/home/pi/Test/server_107380351ee7f847/test/TestServer/node_modules/socket.io/lib/socket.js:128:10)
    at Socket.onerror (/home/pi/Test/server_107380351ee7f847/test/TestServer/node_modules/socket.io/lib/socket.js:401:10)
    at Client.onerror (/home/pi/Test/server_107380351ee7f847/test/TestServer/node_modules/socket.io/lib/client.js:210:24)
    at Client.ondata (/home/pi/Test/server_107380351ee7f847/test/TestServer/node_modules/socket.io/lib/client.js:177:10)
    at Socket.emit (events.js:82:17)
    at Socket.onPacket (/home/pi/Test/server_107380351ee7f847/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/socket.js:101:14)
    at WebSocket.emit (events.js:82:17)
    at WebSocket.Transport.onPacket (/home/pi/Test/server_107380351ee7f847/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transport.js:104:8)
    at WebSocket.Transport.onData (/home/pi/Test/server_107380351ee7f847/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transport.js:115:8)
    at WebSocket.onData (/home/pi/Test/server_107380351ee7f847/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transports/websocket.js:76:30)
    at WebSocket.emit (events.js:85:17)
    at Receiver.ontext (/home/pi/Test/server_107380351ee7f847/test/TestServer/node_modules/socket.io/node_modules/engine.io/node_modules/ws/lib/WebSocket.js:841:10)
    at /home/pi/Test/server_107380351ee7f847/test/TestServer/node_modules/socket.io/node_modules/engine.io/node_modules/ws/lib/Receiver.js:536:18
    at /home/pi/Test/server_107380351ee7f847/test/TestServer/node_modules/socket.io/node_modules/engine.io/node_modules/ws/lib/Receiver.js:368:7''

2017-02-23 10:46:05 - INFO HttpServer: 'Socket to device name: 'Apple-ipad-air-2-1' disconnected, reason: 'undefined''

2017-02-23 10:46:05 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-6-2' disconnected, reason: 'undefined''

[0;31merror: command 'sudo jx ______.js all' failed with code 1, file 'bash' on line 30[0m
One or more Android tests are failed.
 [0m
index.js failed [ 1 ]

```


Logs for system : 
```

android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


TIMEOUT REACHED!

ios : Error: Command failed: true
23/2/2017@11:42:08 Getting the list of iOS devices 
23/2/2017@11:42:09 ios: device name: ipad-air-2-1 , device identifier:  605a17dff1a0ba7f312ea7b076f5923e29d8b1fe
23/2/2017@11:42:09 ios: device name: ipad-mini-mfts , device identifier:  83aab4e7f1dde3becec287ac4c44362439d2595b
23/2/2017@11:42:09 Deploying iOS test app 
23/2/2017@11:42:09 uninstalling the application 
23/2/2017@11:42:11 installing the application 
true

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
Deploying to ce0616068b9f212302
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ce0616068b9f212302

Starting application ThaliTest on ce0616068b9f212302

App was succesfully started on ce0616068b9f212302

Error! Unexpected exit on device ce0616068b9f212302 app:com.test.thalitest code:null 
Child process exited with code null on device ce0616068b9f212302
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/107380351ee7f847_CI_sanity_check_-_master_jareksl/thali02_samsung-SM-G930F.md)

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

Error! Unexpected exit on device ce061606c181d71003 app:com.test.thalitest code:null 
Child process exited with code null on device ce061606c181d71003
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/107380351ee7f847_CI_sanity_check_-_master_jareksl/thali03_samsung-SM-G930F.md)

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

```

###iOS Logs
[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/107380351ee7f847_CI_sanity_check_-_master_jareksl/iOS_ipad-air-2-1.md)

[ipad-mini-mfts](https://github.com/ThaliTester/TestResults/blob/107380351ee7f847_CI_sanity_check_-_master_jareksl/iOS_ipad-mini-mfts.md)




