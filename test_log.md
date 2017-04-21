#### Test 1167800976d9437e Logs

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
URL:  [ 'ios', '1' ]
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
> jx index.js {"devices":{"ios":1,"android":3}}
2017-04-21 15:41:06 - INFO HttpServer: 'listening on *:3000'

2017-04-21 15:41:13 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: 'cf35930b-1619-4eaf-8dce-dae4185ed853', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-04-21 15:41:13 - DEBUG TestFramework: 'device added, name: 'Apple-ipad-air-2-1''

2017-04-21 15:41:13 - INFO TestFramework: 'all required 1 devices are present for platformName: 'ios''

2017-04-21 15:41:13 - ERROR HttpServer: 'unexpected server error: 'undefined''

2017-04-21 15:41:13 - ERROR TestServerProcess: 'uncaught exception, error: 'Error', stack: 'Error
    at Server._error (/home/pi/Test/server_1167800976d9437e/test/TestServer/HttpServer.js:78:9)
    at Socket.emit (events.js:82:17)
    at Socket.emit (/home/pi/Test/server_1167800976d9437e/test/TestServer/node_modules/socket.io/lib/socket.js:128:10)
    at Socket.onerror (/home/pi/Test/server_1167800976d9437e/test/TestServer/node_modules/socket.io/lib/socket.js:401:10)
    at Client.onerror (/home/pi/Test/server_1167800976d9437e/test/TestServer/node_modules/socket.io/lib/client.js:210:24)
    at Client.ondata (/home/pi/Test/server_1167800976d9437e/test/TestServer/node_modules/socket.io/lib/client.js:177:10)
    at Socket.emit (events.js:82:17)
    at Socket.onPacket (/home/pi/Test/server_1167800976d9437e/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/socket.js:101:14)
    at WebSocket.emit (events.js:82:17)
    at WebSocket.Transport.onPacket (/home/pi/Test/server_1167800976d9437e/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transport.js:104:8)
    at WebSocket.Transport.onData (/home/pi/Test/server_1167800976d9437e/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transport.js:115:8)
    at WebSocket.onData (/home/pi/Test/server_1167800976d9437e/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transports/websocket.js:76:30)
    at WebSocket.emit (events.js:85:17)
    at Receiver.ontext (/home/pi/Test/server_1167800976d9437e/test/TestServer/node_modules/socket.io/node_modules/engine.io/node_modules/ws/lib/WebSocket.js:841:10)
    at /home/pi/Test/server_1167800976d9437e/test/TestServer/node_modules/socket.io/node_modules/engine.io/node_modules/ws/lib/Receiver.js:536:18
    at /home/pi/Test/server_1167800976d9437e/test/TestServer/node_modules/socket.io/node_modules/engine.io/node_modules/ws/lib/Receiver.js:368:7''

2017-04-21 15:41:13 - INFO HttpServer: 'Socket to device name: 'Apple-ipad-air-2-1' disconnected, reason: 'undefined''

[0;31merror: command 'sudo jx ______.js all' failed with code 1, file 'bash' on line 30[0m
One or more Android tests are failed.
 [0m
index.js failed [ 1 ]

```


Logs for system : 
```

android : Error: Command failed: job.nodes [ { name: 'thali03', ip: '192.168.1.52' },
  { name: 'thali05', ip: '192.168.1.54' },
  { name: 'thali04', ip: '192.168.1.53' } ]
copyCmd cd /Users/thali/Github/CI/tasker;scp ../builder/builds/1167800976d9437e/build_android/android_0_1167800976d9437e.apk pi@192.168.1.52:~/test/builder/builds/1167800976d9437e/build_android/android_0_1167800976d9437e.apk
copyCmd cd /Users/thali/Github/CI/tasker;scp ../builder/builds/1167800976d9437e/build_android/android_0_1167800976d9437e.apk pi@192.168.1.54:~/test/builder/builds/1167800976d9437e/build_android/android_0_1167800976d9437e.apk
copyCmd cd /Users/thali/Github/CI/tasker;scp ../builder/builds/1167800976d9437e/build_android/android_0_1167800976d9437e.apk pi@192.168.1.53:~/test/builder/builds/1167800976d9437e/build_android/android_0_1167800976d9437e.apk
copyCmd scp pi@192.168.1.52:~/*.json /Users/thali/Github/CI/tasker/results/1167800976d9437e/thali03/
copyCmd scp pi@192.168.1.54:~/*.json /Users/thali/Github/CI/tasker/results/1167800976d9437e/thali05/
copyCmd scp pi@192.168.1.53:~/*.json /Users/thali/Github/CI/tasker/results/1167800976d9437e/thali04/
Error: Command failed: Android testing process has failed
 [0m


TIMEOUT REACHED!job.nodes [ { name: 'thali03', ip: '192.168.1.52' },
  { name: 'thali05', ip: '192.168.1.54' },
  { name: 'thali04', ip: '192.168.1.53' } ]
copyCmd cd /Users/thali/Github/CI/tasker;scp ../builder/builds/1167800976d9437e/build_android/android_0_1167800976d9437e.apk pi@192.168.1.52:~/test/builder/builds/1167800976d9437e/build_android/android_0_1167800976d9437e.apk
copyCmd cd /Users/thali/Github/CI/tasker;scp ../builder/builds/1167800976d9437e/build_android/android_0_1167800976d9437e.apk pi@192.168.1.54:~/test/builder/builds/1167800976d9437e/build_android/android_0_1167800976d9437e.apk
copyCmd cd /Users/thali/Github/CI/tasker;scp ../builder/builds/1167800976d9437e/build_android/android_0_1167800976d9437e.apk pi@192.168.1.53:~/test/builder/builds/1167800976d9437e/build_android/android_0_1167800976d9437e.apk
copyCmd scp pi@192.168.1.52:~/*.json /Users/thali/Github/CI/tasker/results/1167800976d9437e/thali03/
copyCmd scp pi@192.168.1.54:~/*.json /Users/thali/Github/CI/tasker/results/1167800976d9437e/thali05/
copyCmd scp pi@192.168.1.53:~/*.json /Users/thali/Github/CI/tasker/results/1167800976d9437e/thali04/


ios : Error: Command failed: 21/4/2017@17:37:43 Getting the list of iOS devices 
21/4/2017@17:37:44 ios: device name: ipad-air-2-1 , device identifier:  605a17dff1a0ba7f312ea7b076f5923e29d8b1fe
21/4/2017@17:37:44 Deploying iOS test app 
21/4/2017@17:37:44 uninstalling the application 
21/4/2017@17:37:44 installing the application 

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
deploy command: adb -s ce061606e320561102 install -r /home/pi/test/builder/builds/1167800976d9437e/build_android/android_0_1167800976d9437e.apk&& adb -s ce061606e320561102 shell pm grant com.rockwellautomation.thalitest android.permission.ACCESS_COARSE_LOCATION
Deploying to ce061606e320561102
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
deploy command: adb -s ce061606e320561102 install -r /home/pi/test/builder/builds/1167800976d9437e/build_android/android_0_1167800976d9437e.apk&& adb -s ce061606e320561102 shell pm grant com.rockwellautomation.thalitest android.permission.ACCESS_COARSE_LOCATION
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
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/1167800976d9437e_Can_shift_data_via_parallel_connections_fails_on_desktop__1857_opetkevich/thali03_samsung-SM-G935F.md)

####Node name: thali04
Console output:
```
Stopping app on  ce0616068b9f212302
Uninstalling app on  ce0616068b9f212302

All devices are ready!

Deploying to ce0616068b9f212302
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
deploy command: adb -s ce0616068b9f212302 install -r /home/pi/test/builder/builds/1167800976d9437e/build_android/android_0_1167800976d9437e.apk&& adb -s ce0616068b9f212302 shell pm grant com.rockwellautomation.thalitest android.permission.ACCESS_COARSE_LOCATION
Deploying to ce0616068b9f212302
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
deploy command: adb -s ce0616068b9f212302 install -r /home/pi/test/builder/builds/1167800976d9437e/build_android/android_0_1167800976d9437e.apk&& adb -s ce0616068b9f212302 shell pm grant com.rockwellautomation.thalitest android.permission.ACCESS_COARSE_LOCATION
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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/1167800976d9437e_Can_shift_data_via_parallel_connections_fails_on_desktop__1857_opetkevich/thali04_samsung-SM-G930F.md)

####Node name: thali05
Console output:
```
Stopping app on  ce061606c181d71003
Uninstalling app on  ce061606c181d71003

All devices are ready!

Deploying to ce061606c181d71003
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
deploy command: adb -s ce061606c181d71003 install -r /home/pi/test/builder/builds/1167800976d9437e/build_android/android_0_1167800976d9437e.apk&& adb -s ce061606c181d71003 shell pm grant com.rockwellautomation.thalitest android.permission.ACCESS_COARSE_LOCATION
Deploying to ce061606c181d71003
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
deploy command: adb -s ce061606c181d71003 install -r /home/pi/test/builder/builds/1167800976d9437e/build_android/android_0_1167800976d9437e.apk&& adb -s ce061606c181d71003 shell pm grant com.rockwellautomation.thalitest android.permission.ACCESS_COARSE_LOCATION
App was succesfully deployed to ce061606c181d71003

```

###iOS Logs
[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/1167800976d9437e_Can_shift_data_via_parallel_connections_fails_on_desktop__1857_opetkevich/iOS_ipad-air-2-1.md)




