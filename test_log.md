#### Test 122449695e186250 Logs

#### Test Server Logs
```
Error: Command failed: index.js failed [ 1 ]
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":2,"android":0}}
2017-05-25 14:58:50 - INFO HttpServer: 'listening on *:3000'

2017-05-25 14:59:05 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: '41835076-31f1-40e0-bbaa-2e0045ac7405', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-05-25 14:59:05 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-1''

2017-05-25 14:59:06 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: 'b395a2a7-d954-4665-bdf7-fb834bf8974c', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-05-25 14:59:06 - DEBUG TestFramework: 'device added, name: 'Apple-ipad-air-2-1''

2017-05-25 14:59:06 - INFO TestFramework: 'all required 2 devices are present for platformName: 'ios''

2017-05-25 14:59:06 - ERROR HttpServer: 'unexpected server error: 'undefined''

2017-05-25 14:59:06 - ERROR TestServerProcess: 'uncaught exception, error: 'Error', stack: 'Error
    at Server._error (/home/pi/Test/server_122449695e186250/test/TestServer/HttpServer.js:78:9)
    at Socket.emit (events.js:82:17)
    at Socket.emit (/home/pi/Test/server_122449695e186250/test/TestServer/node_modules/socket.io/lib/socket.js:128:10)
    at Socket.onerror (/home/pi/Test/server_122449695e186250/test/TestServer/node_modules/socket.io/lib/socket.js:401:10)
    at Client.onerror (/home/pi/Test/server_122449695e186250/test/TestServer/node_modules/socket.io/lib/client.js:210:24)
    at Client.ondata (/home/pi/Test/server_122449695e186250/test/TestServer/node_modules/socket.io/lib/client.js:177:10)
    at Socket.emit (events.js:82:17)
    at Socket.onPacket (/home/pi/Test/server_122449695e186250/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/socket.js:101:14)
    at WebSocket.emit (events.js:82:17)
    at WebSocket.Transport.onPacket (/home/pi/Test/server_122449695e186250/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transport.js:104:8)
    at WebSocket.Transport.onData (/home/pi/Test/server_122449695e186250/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transport.js:115:8)
    at WebSocket.onData (/home/pi/Test/server_122449695e186250/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transports/websocket.js:76:30)
    at WebSocket.emit (events.js:85:17)
    at Receiver.ontext (/home/pi/Test/server_122449695e186250/test/TestServer/node_modules/socket.io/node_modules/engine.io/node_modules/ws/lib/WebSocket.js:841:10)
    at /home/pi/Test/server_122449695e186250/test/TestServer/node_modules/socket.io/node_modules/engine.io/node_modules/ws/lib/Receiver.js:536:18
    at /home/pi/Test/server_122449695e186250/test/TestServer/node_modules/socket.io/node_modules/engine.io/node_modules/ws/lib/Receiver.js:368:7''

2017-05-25 14:59:06 - INFO HttpServer: 'Socket to device name: 'Apple-ipad-air-2-1' disconnected, reason: 'undefined''

2017-05-25 14:59:06 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-1' disconnected, reason: 'undefined''

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
25/5/2017@16:55:37 Getting the list of iOS devices 
25/5/2017@16:55:38 ios: device name: iphone-5s-mfts , device identifier:  bffa901fefdea07f59339a6737776943349f5077
25/5/2017@16:55:38 ios: device name: iphone-5s-1 , device identifier:  00b2e2c1b30013159b62125fe7f097bdcc055c10
25/5/2017@16:55:38 ios: device name: ipad-air-2-1 , device identifier:  605a17dff1a0ba7f312ea7b076f5923e29d8b1fe
25/5/2017@16:55:38 Deploying iOS test app 
25/5/2017@16:55:38 uninstalling the application 
25/5/2017@16:55:38 installing the application 
true

```
###Android Logs
####Node name: thali03
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

Error: problem running Android apk(com.test.thalitest) on device samsung-SM-G935F 
Starting: Intent { cmp=com.test.thalitest/.MainActivity VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
Error type 3
Error: Activity class {com.test.thalitest/com.test.thalitest.MainActivity} does not exist.
 
Error! true 
Error! Unexpected exit on device ce061606e320561102 app:com.test.thalitest code:null 
Child process exited with code null on device ce061606e320561102
Android task is completed. [FAILED]
```
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/122449695e186250_Provide_remote_db_name_for_ThaliReplicationPeerAction_during_runtime__1873_mlesnic/thali03_samsung-SM-G935F.md)

####Node name: thali04
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

Error: problem running Android apk(com.test.thalitest) on device samsung-SM-G930F 
Starting: Intent { cmp=com.test.thalitest/.MainActivity VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
Error type 3
Error: Activity class {com.test.thalitest/com.test.thalitest.MainActivity} does not exist.
 
Error! true 
Error! Unexpected exit on device ce0616068b9f212302 app:com.test.thalitest code:null 
Child process exited with code null on device ce0616068b9f212302
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/122449695e186250_Provide_remote_db_name_for_ThaliReplicationPeerAction_during_runtime__1873_mlesnic/thali04_samsung-SM-G930F.md)

####Node name: thali05
Console output:
```
Stopping app on  ce061606c181d71003
Uninstalling app on  ce061606c181d71003

All devices are ready!

Deploying to ce061606c181d71003
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ce061606c181d71003

```

###iOS Logs
[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/122449695e186250_Provide_remote_db_name_for_ThaliReplicationPeerAction_during_runtime__1873_mlesnic/iOS_iphone-5s-mfts.md)

[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/122449695e186250_Provide_remote_db_name_for_ThaliReplicationPeerAction_during_runtime__1873_mlesnic/iOS_iphone-5s-1.md)

[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/122449695e186250_Provide_remote_db_name_for_ThaliReplicationPeerAction_during_runtime__1873_mlesnic/iOS_ipad-air-2-1.md)




