#### Test 121460753250d573 Logs

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
2017-05-19 10:11:14 - INFO HttpServer: 'listening on *:3000'

2017-05-19 10:11:15 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: 'e3e5a079-9699-48ab-b563-895fb2a62ad4', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-05-19 10:11:15 - DEBUG TestFramework: 'device added, name: 'Apple-ipad-air-2-1''

2017-05-19 10:11:15 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: '9b46f162-e5e5-4881-94e9-df46b276cc57', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-05-19 10:11:15 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-1''

2017-05-19 10:11:15 - INFO TestFramework: 'all required 2 devices are present for platformName: 'ios''

2017-05-19 10:11:15 - ERROR HttpServer: 'unexpected server error: 'undefined''

2017-05-19 10:11:15 - ERROR TestServerProcess: 'uncaught exception, error: 'Error', stack: 'Error
    at Server._error (/home/pi/Test/server_121460753250d573/test/TestServer/HttpServer.js:78:9)
    at Socket.emit (events.js:82:17)
    at Socket.emit (/home/pi/Test/server_121460753250d573/test/TestServer/node_modules/socket.io/lib/socket.js:128:10)
    at Socket.onerror (/home/pi/Test/server_121460753250d573/test/TestServer/node_modules/socket.io/lib/socket.js:401:10)
    at Client.onerror (/home/pi/Test/server_121460753250d573/test/TestServer/node_modules/socket.io/lib/client.js:210:24)
    at Client.ondata (/home/pi/Test/server_121460753250d573/test/TestServer/node_modules/socket.io/lib/client.js:177:10)
    at Socket.emit (events.js:82:17)
    at Socket.onPacket (/home/pi/Test/server_121460753250d573/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/socket.js:101:14)
    at WebSocket.emit (events.js:82:17)
    at WebSocket.Transport.onPacket (/home/pi/Test/server_121460753250d573/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transport.js:104:8)
    at WebSocket.Transport.onData (/home/pi/Test/server_121460753250d573/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transport.js:115:8)
    at WebSocket.onData (/home/pi/Test/server_121460753250d573/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transports/websocket.js:76:30)
    at WebSocket.emit (events.js:85:17)
    at Receiver.ontext (/home/pi/Test/server_121460753250d573/test/TestServer/node_modules/socket.io/node_modules/engine.io/node_modules/ws/lib/WebSocket.js:841:10)
    at /home/pi/Test/server_121460753250d573/test/TestServer/node_modules/socket.io/node_modules/engine.io/node_modules/ws/lib/Receiver.js:536:18
    at /home/pi/Test/server_121460753250d573/test/TestServer/node_modules/socket.io/node_modules/engine.io/node_modules/ws/lib/Receiver.js:368:7''

2017-05-19 10:11:15 - INFO HttpServer: 'Socket to device name: 'Apple-ipad-air-2-1' disconnected, reason: 'undefined''

2017-05-19 10:11:15 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-1' disconnected, reason: 'undefined''

[0;31merror: command 'sudo jx ______.js all' failed with code 1, file 'bash' on line 30[0m
One or more Android tests are failed.
 [0m
index.js failed [ 1 ]

```


Logs for system : 
```

android : Error: Command failed: job.nodes [ { name: 'thali03', ip: '192.168.1.52' },
  { name: 'thali04', ip: '192.168.1.53' },
  { name: 'thali05', ip: '192.168.1.54' } ]
copyCmd cd /Users/thali/Github/CI/tasker;scp ../builder/builds/121460753250d573/build_android/android_0_121460753250d573.apk pi@192.168.1.52:~/test/builder/builds/121460753250d573/build_android/android_0_121460753250d573.apk
copyCmd cd /Users/thali/Github/CI/tasker;scp ../builder/builds/121460753250d573/build_android/android_0_121460753250d573.apk pi@192.168.1.53:~/test/builder/builds/121460753250d573/build_android/android_0_121460753250d573.apk
copyCmd cd /Users/thali/Github/CI/tasker;scp ../builder/builds/121460753250d573/build_android/android_0_121460753250d573.apk pi@192.168.1.54:~/test/builder/builds/121460753250d573/build_android/android_0_121460753250d573.apk
mkdirCmd mkdir -p /Users/thali/Github/CI/tasker/results/121460753250d573/thali03/
copyCmd scp pi@192.168.1.52:~/*.json /Users/thali/Github/CI/tasker/results/121460753250d573/thali03/
mkdirCmd mkdir -p /Users/thali/Github/CI/tasker/results/121460753250d573/thali04/
copyCmd scp pi@192.168.1.53:~/*.json /Users/thali/Github/CI/tasker/results/121460753250d573/thali04/
mkdirCmd mkdir -p /Users/thali/Github/CI/tasker/results/121460753250d573/thali05/
copyCmd scp pi@192.168.1.54:~/*.json /Users/thali/Github/CI/tasker/results/121460753250d573/thali05/
Error: Command failed: Android testing process has failed
 [0m


TIMEOUT REACHED!job.nodes [ { name: 'thali03', ip: '192.168.1.52' },
  { name: 'thali04', ip: '192.168.1.53' },
  { name: 'thali05', ip: '192.168.1.54' } ]
copyCmd cd /Users/thali/Github/CI/tasker;scp ../builder/builds/121460753250d573/build_android/android_0_121460753250d573.apk pi@192.168.1.52:~/test/builder/builds/121460753250d573/build_android/android_0_121460753250d573.apk
copyCmd cd /Users/thali/Github/CI/tasker;scp ../builder/builds/121460753250d573/build_android/android_0_121460753250d573.apk pi@192.168.1.53:~/test/builder/builds/121460753250d573/build_android/android_0_121460753250d573.apk
copyCmd cd /Users/thali/Github/CI/tasker;scp ../builder/builds/121460753250d573/build_android/android_0_121460753250d573.apk pi@192.168.1.54:~/test/builder/builds/121460753250d573/build_android/android_0_121460753250d573.apk
mkdirCmd mkdir -p /Users/thali/Github/CI/tasker/results/121460753250d573/thali03/
copyCmd scp pi@192.168.1.52:~/*.json /Users/thali/Github/CI/tasker/results/121460753250d573/thali03/
mkdirCmd mkdir -p /Users/thali/Github/CI/tasker/results/121460753250d573/thali04/
copyCmd scp pi@192.168.1.53:~/*.json /Users/thali/Github/CI/tasker/results/121460753250d573/thali04/
mkdirCmd mkdir -p /Users/thali/Github/CI/tasker/results/121460753250d573/thali05/
copyCmd scp pi@192.168.1.54:~/*.json /Users/thali/Github/CI/tasker/results/121460753250d573/thali05/


ios : Error: Command failed: 19/5/2017@12:07:46 Getting the list of iOS devices 
19/5/2017@12:07:47 ios: device name: iphone-5s-1 , device identifier:  00b2e2c1b30013159b62125fe7f097bdcc055c10
19/5/2017@12:07:47 ios: device name: ipad-air-2-1 , device identifier:  605a17dff1a0ba7f312ea7b076f5923e29d8b1fe
19/5/2017@12:07:47 Deploying iOS test app 
19/5/2017@12:07:47 uninstalling the application 
19/5/2017@12:07:48 installing the application 

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
deploy command: adb -s ce061606e320561102 install -r /home/pi/test/builder/builds/121460753250d573/build_android/android_0_121460753250d573.apk&& adb -s ce061606e320561102 shell pm grant com.rockwellautomation.thalitest android.permission.ACCESS_COARSE_LOCATION
Deploying to ce061606e320561102
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
deploy command: adb -s ce061606e320561102 install -r /home/pi/test/builder/builds/121460753250d573/build_android/android_0_121460753250d573.apk&& adb -s ce061606e320561102 shell pm grant com.rockwellautomation.thalitest android.permission.ACCESS_COARSE_LOCATION
App was succesfully deployed to ce061606e320561102

Starting application ThaliTest on ce061606e320561102

App was succesfully started on ce061606e320561102

Error! Unexpected exit on device ce061606e320561102 app:com.rockwellautomation.thalitest code:null 
Child process exited with code null on device ce061606e320561102
Android task is completed. [FAILED]
```
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/121460753250d573_Update_mobile_test_json_jareksl/thali03_samsung-SM-G935F.md)

####Node name: thali04
Console output:
```
Stopping app on  ce0616068b9f212302
Uninstalling app on  ce0616068b9f212302

All devices are ready!

Deploying to ce0616068b9f212302
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
deploy command: adb -s ce0616068b9f212302 install -r /home/pi/test/builder/builds/121460753250d573/build_android/android_0_121460753250d573.apk&& adb -s ce0616068b9f212302 shell pm grant com.rockwellautomation.thalitest android.permission.ACCESS_COARSE_LOCATION
Deploying to ce0616068b9f212302
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
deploy command: adb -s ce0616068b9f212302 install -r /home/pi/test/builder/builds/121460753250d573/build_android/android_0_121460753250d573.apk&& adb -s ce0616068b9f212302 shell pm grant com.rockwellautomation.thalitest android.permission.ACCESS_COARSE_LOCATION
App was succesfully deployed to ce0616068b9f212302

Starting application ThaliTest on ce0616068b9f212302

App was succesfully started on ce0616068b9f212302

Error! Unexpected exit on device ce0616068b9f212302 app:com.rockwellautomation.thalitest code:null 
Child process exited with code null on device ce0616068b9f212302
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/121460753250d573_Update_mobile_test_json_jareksl/thali04_samsung-SM-G930F.md)

####Node name: thali05
Console output:
```
Stopping app on  ce061606c181d71003
Uninstalling app on  ce061606c181d71003

All devices are ready!

Deploying to ce061606c181d71003
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
deploy command: adb -s ce061606c181d71003 install -r /home/pi/test/builder/builds/121460753250d573/build_android/android_0_121460753250d573.apk&& adb -s ce061606c181d71003 shell pm grant com.rockwellautomation.thalitest android.permission.ACCESS_COARSE_LOCATION
Deploying to ce061606c181d71003
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
deploy command: adb -s ce061606c181d71003 install -r /home/pi/test/builder/builds/121460753250d573/build_android/android_0_121460753250d573.apk&& adb -s ce061606c181d71003 shell pm grant com.rockwellautomation.thalitest android.permission.ACCESS_COARSE_LOCATION
App was succesfully deployed to ce061606c181d71003

```

###iOS Logs
[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/121460753250d573_Update_mobile_test_json_jareksl/iOS_iphone-5s-1.md)

[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/121460753250d573_Update_mobile_test_json_jareksl/iOS_ipad-air-2-1.md)




