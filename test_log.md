#### Test 102706742aeb8de5 Logs

#### Test Server Logs
```
Error: Command failed: index.js failed [ 1 ]
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":2}}
2017-01-30 07:47:28 - INFO HttpServer: 'listening on *:3000'

2017-01-30 07:47:36 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '6e8f6859-e18b-49f0-b0b9-b4aeb413f735', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-01-30 07:47:36 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-01-30 07:47:39 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'transport close''

2017-01-30 07:48:34 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '4ad1d744-913b-468b-bca0-b73a2ef3fa7a', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-01-30 07:48:34 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-01-30 07:48:34 - INFO TestFramework: 'all required 2 devices are present for platformName: 'android''

2017-01-30 07:48:34 - ERROR HttpServer: 'unexpected server error: 'undefined''

2017-01-30 07:48:34 - ERROR TestServerProcess: 'uncaught exception, error: 'Error', stack: 'Error
    at Server._error (/home/pi/Test/server_102706742aeb8de5/test/TestServer/HttpServer.js:78:9)
    at Socket.emit (events.js:82:17)
    at Socket.emit (/home/pi/Test/server_102706742aeb8de5/test/TestServer/node_modules/socket.io/lib/socket.js:128:10)
    at Socket.onerror (/home/pi/Test/server_102706742aeb8de5/test/TestServer/node_modules/socket.io/lib/socket.js:401:10)
    at Client.onerror (/home/pi/Test/server_102706742aeb8de5/test/TestServer/node_modules/socket.io/lib/client.js:210:24)
    at Client.ondata (/home/pi/Test/server_102706742aeb8de5/test/TestServer/node_modules/socket.io/lib/client.js:177:10)
    at Socket.emit (events.js:82:17)
    at Socket.onPacket (/home/pi/Test/server_102706742aeb8de5/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/socket.js:101:14)
    at WebSocket.emit (events.js:82:17)
    at WebSocket.Transport.onPacket (/home/pi/Test/server_102706742aeb8de5/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transport.js:104:8)
    at WebSocket.Transport.onData (/home/pi/Test/server_102706742aeb8de5/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transport.js:115:8)
    at WebSocket.onData (/home/pi/Test/server_102706742aeb8de5/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transports/websocket.js:76:30)
    at WebSocket.emit (events.js:85:17)
    at Receiver.ontext (/home/pi/Test/server_102706742aeb8de5/test/TestServer/node_modules/socket.io/node_modules/engine.io/node_modules/ws/lib/WebSocket.js:841:10)
    at /home/pi/Test/server_102706742aeb8de5/test/TestServer/node_modules/socket.io/node_modules/engine.io/node_modules/ws/lib/Receiver.js:536:18
    at /home/pi/Test/server_102706742aeb8de5/test/TestServer/node_modules/socket.io/node_modules/engine.io/node_modules/ws/lib/Receiver.js:368:7''

2017-01-30 07:48:34 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

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
Deploying to ce0616068b9f212302
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ce0616068b9f212302

Starting application ThaliTest on ce0616068b9f212302

App was succesfully started on ce0616068b9f212302

Error! Unexpected exit on device ce0616068b9f212302 app:com.test.thalitest code:null 
Child process exited with code null on device ce0616068b9f212302
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/102706742aeb8de5_iOS_CI_sanity_check_czyzm/thali02_samsung-SM-G930F.md)

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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/102706742aeb8de5_iOS_CI_sanity_check_czyzm/thali03_samsung-SM-G930F.md)




###iOS Logs
[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/102706742aeb8de5_iOS_CI_sanity_check_czyzm/iOS_ipad-air-2-1.md)

[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/102706742aeb8de5_iOS_CI_sanity_check_czyzm/iOS_iphone-5s-mfts.md)

[ipad-mini-mfts](https://github.com/ThaliTester/TestResults/blob/102706742aeb8de5_iOS_CI_sanity_check_czyzm/iOS_ipad-mini-mfts.md)

[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/102706742aeb8de5_iOS_CI_sanity_check_czyzm/iOS_iphone-5s-1.md)


