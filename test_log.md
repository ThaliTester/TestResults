#### Test 986941184ef5798 Logs

#### Test Server Logs
```
Error: Command failed: IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":2}}
2016-12-21 11:12:33 - INFO HttpServer: 'listening on *:3000'

2016-12-21 11:13:50 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '19cbdb64-649f-409d-88fe-41ca5d4bfbd9', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-12-21 11:13:50 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2016-12-21 11:14:13 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: 'e1ccf991-9101-4066-b9a3-83738058e5c4', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-12-21 11:14:13 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2016-12-21 11:14:13 - INFO TestFramework: 'all required 2 devices are present for platformName: 'android''

2016-12-21 11:14:13 - ERROR HttpServer: 'unexpected server error: 'undefined''

2016-12-21 11:14:13 - ERROR TestServerProcess: 'uncaught exception, error: 'Error', stack: 'Error
    at Server._error (/home/pi/Test/server_986941184ef5798/test/TestServer/HttpServer.js:77:9)
    at Socket.emit (events.js:82:17)
    at Socket.emit (/home/pi/Test/server_986941184ef5798/test/TestServer/node_modules/socket.io/lib/socket.js:128:10)
    at Socket.onerror (/home/pi/Test/server_986941184ef5798/test/TestServer/node_modules/socket.io/lib/socket.js:401:10)
    at Client.onerror (/home/pi/Test/server_986941184ef5798/test/TestServer/node_modules/socket.io/lib/client.js:210:24)
    at Client.ondata (/home/pi/Test/server_986941184ef5798/test/TestServer/node_modules/socket.io/lib/client.js:177:10)
    at Socket.emit (events.js:82:17)
    at Socket.onPacket (/home/pi/Test/server_986941184ef5798/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/socket.js:101:14)
    at WebSocket.emit (events.js:82:17)
    at WebSocket.Transport.onPacket (/home/pi/Test/server_986941184ef5798/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transport.js:104:8)
    at WebSocket.Transport.onData (/home/pi/Test/server_986941184ef5798/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transport.js:115:8)
    at WebSocket.onData (/home/pi/Test/server_986941184ef5798/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transports/websocket.js:76:30)
    at WebSocket.emit (events.js:85:17)
    at Receiver.ontext (/home/pi/Test/server_986941184ef5798/test/TestServer/node_modules/socket.io/node_modules/engine.io/node_modules/ws/lib/WebSocket.js:841:10)
    at /home/pi/Test/server_986941184ef5798/test/TestServer/node_modules/socket.io/node_modules/engine.io/node_modules/ws/lib/Receiver.js:536:18
    at /home/pi/Test/server_986941184ef5798/test/TestServer/node_modules/socket.io/node_modules/engine.io/node_modules/ws/lib/Receiver.js:368:7''

2016-12-21 11:14:13 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

2016-12-21 11:14:13 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

[0;31merror: command 'sudo jx ______.js android' failed with code 1, file 'bash' on line 30[0m
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/986941184ef5798_CI_sanity_check_czyzm/thali02_samsung-SM-G930F.md)

####Node name: thali03
Console output:
```
Stopping app on  ce061606c181d71003
Uninstalling app on  ce061606c181d71003

All devices are ready!

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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/986941184ef5798_CI_sanity_check_czyzm/thali03_samsung-SM-G930F.md)




