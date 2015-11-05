#### Test 486007975e076d4 Logs

Status: 
```

android : Error: Command failed: Error: Command failed: run_.sh aborted
 [0m


TIMEOUT REACHED!

server : IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":20,"cancel":1}}
Start Android tests : performance tests, start tests with timer

Test[0]: testSendData.js, timeout : undefined, data : {"timeout":"440000","rounds":"1","dataTimeout":"30000","dataAmount":"100000","conReTryTimeout":"4000","conReTryCount":"5"}
Test[1]: testSendData.js, timeout : undefined, data : {"timeout":"440000","rounds":"1","dataTimeout":"30000","dataAmount":"100000","conReTryTimeout":"4000","conReTryCount":"5"}
Test[2]: testSendData.js, timeout : undefined, data : {"timeout":"440000","rounds":"1","dataTimeout":"30000","dataAmount":"100000","conReTryTimeout":"4000","conReTryCount":"5"}
Start iOs tests : performance tests, start tests with timer
Test[0]: testSendData.js, timeout : undefined, data : {"timeout":"440000","rounds":"1","dataTimeout":"30000","dataAmount":"100000","conReTryTimeout":"4000","conReTryCount":"5"}
Test[1]: testSendData.js, timeout : undefined, data : {"timeout":"440000","rounds":"1","dataTimeout":"30000","dataAmount":"100000","conReTryTimeout":"4000","conReTryCount":"5"}
Test[2]: testSendData.js, timeout : undefined, data : {"timeout":"440000","rounds":"1","dataTimeout":"30000","dataAmount":"100000","conReTryTimeout":"4000","conReTryCount":"5"}

listening on *:3000

-------------- We got wait done, now starting the testing process ------------------


 
Run IS script aborted
 
[0;31mexecution aborted
 [0m

```
###Android Logs
####Node name: thali01
Console output:
```
Error! Unexpected exit on device 30049d9501da2100 app:com.test.thalitest code:null 
child process exited with code null on device 30049d9501da2100 
Error! Unexpected exit on device 03157df360a1882a app:com.test.thalitest code:null 
child process exited with code null on device 03157df360a1882a 
Error! Unexpected exit on device W3D7N15428022572 app:com.test.thalitest code:null 
child process exited with code null on device W3D7N15428022572 
Error! Unexpected exit on device LGH8153b36be34 app:com.test.thalitest code:null 
child process exited with code null on device LGH8153b36be34 
Android task is completed 
Error: problem stopping Android apk(com.test.thalitest) to device 30049d9501da2100 error: device unauthorized. Please check the confirmation dialog on your device.
 
```

Logcat output:
```
samsung-SM-T232: 
--------- beginning of /dev/log/system
,--------- beginning of /dev/log/main
,W/jxcore-log( 4922): Initializing JXcore engine
,W/jxcore-log( 4922): JXcore engine is ready
,W/jxcore-log( 4922): Starting JXcore engine
,W/jxcore-log( 4922): Platform android
W/jxcore-log( 4922): 
,W/jxcore-log( 4922): Process ARCH arm
W/jxcore-log( 4922): 
,I/jxcore-log( 4922): JXcore Cordova bridge is ready!
I/jxcore-log( 4922): 
W/jxcore-log( 4922): JXcore engine is started
I/jxcore-log( 4922): Turning radios to true
I/jxcore-log( 4922): 
I/jxcore-log( 4922): toggleBluetooth - 
I/jxcore-log( 4922): 
I/jxcore-log( 4922): toggleWiFi
I/jxcore-log( 4922): 
,I/jxcore-log( 4922): check test folder
I/jxcore-log( 4922): 
,I/jxcore-log( 4922): found test : ./testFindPeers.js
I/jxcore-log( 4922): 
,I/jxcore-log( 4922): found test : ./testReConnect.js
I/jxcore-log( 4922): 
,I/jxcore-log( 4922): found test : ./testSendData.js
I/jxcore-log( 4922): 
,I/jxcore-log( 4922): Test app app.js loaded
I/jxcore-log( 4922): 


samsung-SM-G920F: 
--------- beginning of system,
--------- beginning of main
,W/jxcore-log( 9899): Initializing JXcore engine
W/jxcore-log( 9899): JXcore engine is ready
W/jxcore-log( 9899): Starting JXcore engine
,W/jxcore-log( 9899): Platform android
W/jxcore-log( 9899): 
W/jxcore-log( 9899): Process ARCH arm
W/jxcore-log( 9899): 
,I/jxcore-log( 9899): JXcore Cordova bridge is ready!
I/jxcore-log( 9899): 
W/jxcore-log( 9899): JXcore engine is started
,I/jxcore-log( 9899): Turning radios to true
I/jxcore-log( 9899): 
,I/jxcore-log( 9899): toggleBluetooth - 
I/jxcore-log( 9899): 
,I/jxcore-log( 9899): toggleWiFi
I/jxcore-log( 9899): 
,I/jxcore-log( 9899): check test folder
I/jxcore-log( 9899): 
,I/jxcore-log( 9899): found test : ./testFindPeers.js
I/jxcore-log( 9899): 
,I/jxcore-log( 9899): found test : ./testReConnect.js
I/jxcore-log( 9899): 
,I/jxcore-log( 9899): found test : ./testSendData.js
I/jxcore-log( 9899): 
,I/jxcore-log( 9899): Test app app.js loaded
I/jxcore-log( 9899): 


HUAWEI-ALE-L21: 
int logctl_get(): open '/dev/hwlog_switch' fail -1, 13. Permission denied

Note: log switch off, only log_main and log_events will have logs!
,--------- beginning of main
,W/jxcore-log( 6856): Initializing JXcore engine
W/jxcore-log( 6856): JXcore engine is ready
,W/jxcore-log( 6856): Starting JXcore engine
,W/jxcore-log( 6856): Platform android
W/jxcore-log( 6856): 
W/jxcore-log( 6856): Process ARCH arm
W/jxcore-log( 6856): 
,I/jxcore-log( 6856): JXcore Cordova bridge is ready!
I/jxcore-log( 6856): 
W/jxcore-log( 6856): JXcore engine is started
,I/jxcore-log( 6856): Turning radios to true
I/jxcore-log( 6856): 
,I/jxcore-log( 6856): toggleBluetooth - 
I/jxcore-log( 6856): 
,I/jxcore-log( 6856): toggleWiFi
I/jxcore-log( 6856): 
,I/jxcore-log( 6856): check test folder
I/jxcore-log( 6856): 
,I/jxcore-log( 6856): found test : ./testFindPeers.js
I/jxcore-log( 6856): 
,I/jxcore-log( 6856): found test : ./testReConnect.js
I/jxcore-log( 6856): 
,I/jxcore-log( 6856): found test : ./testSendData.js
I/jxcore-log( 6856): 
,I/jxcore-log( 6856): Test app app.js loaded
I/jxcore-log( 6856): 


LGE-LG-H815: 
--------- beginning of main
--------- beginning of system
,W/jxcore-log( 9543): Initializing JXcore engine
W/jxcore-log( 9543): JXcore engine is ready
,W/jxcore-log( 9543): Starting JXcore engine
,W/jxcore-log( 9543): Platform android
W/jxcore-log( 9543): 
W/jxcore-log( 9543): Process ARCH arm
W/jxcore-log( 9543): 
,I/jxcore-log( 9543): JXcore Cordova bridge is ready!
I/jxcore-log( 9543): 
,W/jxcore-log( 9543): JXcore engine is started
,I/jxcore-log( 9543): Turning radios to true
I/jxcore-log( 9543): 
,I/jxcore-log( 9543): toggleBluetooth - 
I/jxcore-log( 9543): 
,I/jxcore-log( 9543): toggleWiFi
I/jxcore-log( 9543): 
,I/jxcore-log( 9543): check test folder
I/jxcore-log( 9543): 
I/jxcore-log( 9543): found test : ./testFindPeers.js
I/jxcore-log( 9543): 
I/jxcore-log( 9543): found test : ./testReConnect.js
I/jxcore-log( 9543): 
I/jxcore-log( 9543): found test : ./testSendData.js
I/jxcore-log( 9543): 
I/jxcore-log( 9543): Test app app.js loaded
I/jxcore-log( 9543): 


```

####Node name: thali02
####Node name: thali03
Console output:
```
Error! Unexpected exit on device 320414cd475f91e3 app:com.test.thalitest code:null 
child process exited with code null on device 320414cd475f91e3 
Error! Unexpected exit on device TA4750HV7I app:com.test.thalitest code:null 
child process exited with code null on device TA4750HV7I 
Error! Unexpected exit on device LGD8553bed2d08 app:com.test.thalitest code:null 
child process exited with code null on device LGD8553bed2d08 
Android task is completed 
```

Logcat output:
```
samsung-SM-G800F: 
--------- beginning of /dev/log/system,
--------- beginning of /dev/log/main
,W/jxcore-log( 6913): Initializing JXcore engine
,W/jxcore-log( 6913): JXcore engine is ready
,W/jxcore-log( 6913): Starting JXcore engine
,W/jxcore-log( 6913): Platform android
W/jxcore-log( 6913): 
,W/jxcore-log( 6913): Process ARCH arm
W/jxcore-log( 6913): 
,I/jxcore-log( 6913): JXcore Cordova bridge is ready!
I/jxcore-log( 6913): 
,W/jxcore-log( 6913): JXcore engine is started
,I/jxcore-log( 6913): Turning radios to true
I/jxcore-log( 6913): 
,I/jxcore-log( 6913): toggleBluetooth - 
I/jxcore-log( 6913): 
,I/jxcore-log( 6913): toggleWiFi
I/jxcore-log( 6913): 
,I/jxcore-log( 6913): check test folder
I/jxcore-log( 6913): 
,I/jxcore-log( 6913): found test : ./testFindPeers.js
I/jxcore-log( 6913): 
,I/jxcore-log( 6913): found test : ./testReConnect.js
I/jxcore-log( 6913): 
,I/jxcore-log( 6913): found test : ./testSendData.js
I/jxcore-log( 6913): 
,I/jxcore-log( 6913): Test app app.js loaded
I/jxcore-log( 6913): 


motorola-XT1039: 
--------- beginning of /dev/log/system
,--------- beginning of /dev/log/main
,W/jxcore-log( 3517): Initializing JXcore engine,
,W/jxcore-log( 3517): JXcore engine is ready
,W/jxcore-log( 3517): Starting JXcore engine
,W/jxcore-log( 3517): Platform android
W/jxcore-log( 3517): 
,W/jxcore-log( 3517): Process ARCH arm
W/jxcore-log( 3517): 
,I/jxcore-log( 3517): JXcore Cordova bridge is ready!
I/jxcore-log( 3517): 
,W/jxcore-log( 3517): JXcore engine is started
,I/jxcore-log( 3517): Turning radios to true
I/jxcore-log( 3517): 
,I/jxcore-log( 3517): toggleBluetooth - 
I/jxcore-log( 3517): 
,I/jxcore-log( 3517): toggleWiFi
I/jxcore-log( 3517): 
,I/jxcore-log( 3517): check test folder
I/jxcore-log( 3517): 
,I/jxcore-log( 3517): found test : ./testFindPeers.js
I/jxcore-log( 3517): 
,I/jxcore-log( 3517): found test : ./testReConnect.js
I/jxcore-log( 3517): 
,I/jxcore-log( 3517): found test : ./testSendData.js
I/jxcore-log( 3517): 
,I/jxcore-log( 3517): Test app app.js loaded
I/jxcore-log( 3517): 


LGE-LG-D855: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log( 6168): Initializing JXcore engine
W/jxcore-log( 6168): JXcore engine is ready
W/jxcore-log( 6168): Starting JXcore engine
W/jxcore-log( 6168): Platform android
W/jxcore-log( 6168): 
W/jxcore-log( 6168): Process ARCH arm
W/jxcore-log( 6168): 
I/jxcore-log( 6168): JXcore Cordova bridge is ready!
I/jxcore-log( 6168): 
W/jxcore-log( 6168): JXcore engine is started
I/jxcore-log( 6168): Turning radios to true
I/jxcore-log( 6168): 
I/jxcore-log( 6168): toggleBluetooth - 
I/jxcore-log( 6168): 
I/jxcore-log( 6168): toggleWiFi
I/jxcore-log( 6168): 
,I/jxcore-log( 6168): check test folder
I/jxcore-log( 6168): 
I/jxcore-log( 6168): found test : ./testFindPeers.js
I/jxcore-log( 6168): 
,I/jxcore-log( 6168): found test : ./testReConnect.js
I/jxcore-log( 6168): 
I/jxcore-log( 6168): found test : ./testSendData.js
I/jxcore-log( 6168): 
,I/jxcore-log( 6168): Test app app.js loaded
I/jxcore-log( 6168): 


```

####Node name: thali05
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 1d6a772d app:com.test.thalitest code:0 
child process exited with code 0 on device 1d6a772d 
Error! Unexpected exit on device SH47FWM00508 app:com.test.thalitest code:0 
child process exited with code 0 on device SH47FWM00508 
Error! Unexpected exit on device ZX1G429CRK app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1G429CRK 
Android task is completed 
Error: problem stopping Android apk(com.test.thalitest) to device 1d6a772d error: device not found
 
Error: problem stopping Android apk(com.test.thalitest) to device SH47FWM00508 error: device not found
 
Error: problem stopping Android apk(com.test.thalitest) to device ZX1G429CRK error: device not found
 
```

Logcat output:
```
samsung-SM-N9005: 
--------- beginning of system
,--------- beginning of main
,W/jxcore-log( 6289): Initializing JXcore engine
W/jxcore-log( 6289): JXcore engine is ready
W/jxcore-log( 6289): Starting JXcore engine
W/jxcore-log( 6289): Platform android
W/jxcore-log( 6289): 
W/jxcore-log( 6289): Process ARCH arm
W/jxcore-log( 6289): 
,I/jxcore-log( 6289): JXcore Cordova bridge is ready!
I/jxcore-log( 6289): 
,W/jxcore-log( 6289): JXcore engine is started
,I/jxcore-log( 6289): Turning radios to true
I/jxcore-log( 6289): 
,I/jxcore-log( 6289): toggleBluetooth - 
I/jxcore-log( 6289): 
,I/jxcore-log( 6289): toggleWiFi
I/jxcore-log( 6289): 
,I/jxcore-log( 6289): check test folder
I/jxcore-log( 6289): 
,I/jxcore-log( 6289): found test : ./testFindPeers.js
I/jxcore-log( 6289): 
,I/jxcore-log( 6289): found test : ./testReConnect.js
I/jxcore-log( 6289): 
,I/jxcore-log( 6289): found test : ./testSendData.js
I/jxcore-log( 6289): 
,I/jxcore-log( 6289): Test app app.js loaded
I/jxcore-log( 6289): 
,TIME-OUT KILL (timeout was 1800000ms)

HTC-HTC One_M8: 
--------- beginning of system,
--------- beginning of main
,W/jxcore-log( 5743): Initializing JXcore engine
W/jxcore-log( 5743): JXcore engine is ready
,W/jxcore-log( 5743): Starting JXcore engine,
,W/jxcore-log( 5743): Platform android,
W/jxcore-log( 5743): 
W/jxcore-log( 5743): Process ARCH arm
W/jxcore-log( 5743): 
,I/jxcore-log( 5743): JXcore Cordova bridge is ready!,
I/jxcore-log( 5743): 
W/jxcore-log( 5743): JXcore engine is started
,I/jxcore-log( 5743): Turning radios to true,
I/jxcore-log( 5743): 
,I/jxcore-log( 5743): toggleBluetooth - ,
I/jxcore-log( 5743): 
,I/jxcore-log( 5743): toggleWiFi,
I/jxcore-log( 5743): 
,I/jxcore-log( 5743): check test folder
I/jxcore-log( 5743): 
,I/jxcore-log( 5743): found test : ./testFindPeers.js,
I/jxcore-log( 5743): 
,I/jxcore-log( 5743): found test : ./testReConnect.js,
I/jxcore-log( 5743): 
,I/jxcore-log( 5743): found test : ./testSendData.js,
I/jxcore-log( 5743): 
,I/jxcore-log( 5743): Test app app.js loaded,
,I/jxcore-log( 5743): 
,TIME-OUT KILL (timeout was 1800000ms)

motorola-Nexus 6: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log( 3401): Initializing JXcore engine,
,W/jxcore-log( 3401): JXcore engine is ready,
,W/jxcore-log( 3401): Starting JXcore engine
,W/jxcore-log( 3401): Platform android
W/jxcore-log( 3401): 
W/jxcore-log( 3401): Process ARCH arm
W/jxcore-log( 3401): 
,I/jxcore-log( 3401): JXcore Cordova bridge is ready!
I/jxcore-log( 3401): 
W/jxcore-log( 3401): JXcore engine is started
,I/jxcore-log( 3401): Turning radios to true
I/jxcore-log( 3401): 
,I/jxcore-log( 3401): toggleBluetooth - 
I/jxcore-log( 3401): 
,I/jxcore-log( 3401): toggleWiFi
I/jxcore-log( 3401): 
,I/jxcore-log( 3401): check test folder
I/jxcore-log( 3401): 
I/jxcore-log( 3401): found test : ./testFindPeers.js
I/jxcore-log( 3401): 
,I/jxcore-log( 3401): found test : ./testReConnect.js
I/jxcore-log( 3401): 
,I/jxcore-log( 3401): found test : ./testSendData.js
I/jxcore-log( 3401): 
,I/jxcore-log( 3401): Test app app.js loaded
I/jxcore-log( 3401): 
,TIME-OUT KILL (timeout was 1800000ms)

```

####Node name: thali06
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 7970f88c app:com.test.thalitest code:0 
child process exited with code 0 on device 7970f88c 
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:0 
child process exited with code 0 on device FA55PYS00566 
Error! Unexpected exit on device 022678fb504e29b0 app:com.test.thalitest code:0 
child process exited with code 0 on device 022678fb504e29b0 
Android task is completed 
Error: problem stopping Android apk(com.test.thalitest) to device 7970f88c error: device not found
 
Error: problem stopping Android apk(com.test.thalitest) to device FA55PYS00566 error: device not found
 
Error: problem stopping Android apk(com.test.thalitest) to device 022678fb504e29b0 error: device not found
 
```

Logcat output:
```
samsung-SM-A300FU: 
--------- beginning of main
--------- beginning of system
,W/jxcore-log( 5418): Initializing JXcore engine
W/jxcore-log( 5418): JXcore engine is ready
,W/jxcore-log( 5418): Starting JXcore engine
,W/jxcore-log( 5418): Platform android
W/jxcore-log( 5418): 
W/jxcore-log( 5418): Process ARCH arm
W/jxcore-log( 5418): 
,I/jxcore-log( 5418): JXcore Cordova bridge is ready!
I/jxcore-log( 5418): 
,W/jxcore-log( 5418): JXcore engine is started
,I/jxcore-log( 5418): Turning radios to true
I/jxcore-log( 5418): 
,I/jxcore-log( 5418): toggleBluetooth - 
I/jxcore-log( 5418): 
,I/jxcore-log( 5418): toggleWiFi
I/jxcore-log( 5418): 
,I/jxcore-log( 5418): check test folder
I/jxcore-log( 5418): 
,I/jxcore-log( 5418): found test : ./testFindPeers.js
I/jxcore-log( 5418): 
,I/jxcore-log( 5418): found test : ./testReConnect.js
I/jxcore-log( 5418): 
,I/jxcore-log( 5418): found test : ./testSendData.js,
I/jxcore-log( 5418): 
,I/jxcore-log( 5418): Test app app.js loaded,
I/jxcore-log( 5418): 
,TIME-OUT KILL (timeout was 1800000ms)

HTC-HTC One M8s: 
--------- beginning of main,
--------- beginning of system
,W/jxcore-log( 6032): Initializing JXcore engine
,W/jxcore-log( 6032): JXcore engine is ready
,W/jxcore-log( 6032): Starting JXcore engine
,W/jxcore-log( 6032): Platform android
W/jxcore-log( 6032): 
W/jxcore-log( 6032): Process ARCH arm
W/jxcore-log( 6032): 
,I/jxcore-log( 6032): JXcore Cordova bridge is ready!,
I/jxcore-log( 6032): 
W/jxcore-log( 6032): JXcore engine is started
,I/jxcore-log( 6032): Turning radios to true,
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): toggleBluetooth - ,
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): toggleWiFi
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): check test folder,
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): found test : ./testFindPeers.js,
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): found test : ./testReConnect.js,
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): found test : ./testSendData.js,
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): Test app app.js loaded,
I/jxcore-log( 6032): 
,TIME-OUT KILL (timeout was 1800000ms)

LGE-LG-D802: 
--------- beginning of /dev/log/system
--------- beginning of /dev/log/main
,W/jxcore-log( 4154): Initializing JXcore engine,
,W/jxcore-log( 4154): JXcore engine is ready
,W/jxcore-log( 4154): Starting JXcore engine
,W/jxcore-log( 4154): Platform android
W/jxcore-log( 4154): 
,W/jxcore-log( 4154): Process ARCH arm
W/jxcore-log( 4154): 
,I/jxcore-log( 4154): JXcore Cordova bridge is ready!
I/jxcore-log( 4154): 
,W/jxcore-log( 4154): JXcore engine is started
,I/jxcore-log( 4154): Turning radios to true
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): toggleBluetooth - 
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): toggleWiFi
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): check test folder
I/jxcore-log( 4154): 
I/jxcore-log( 4154): found test : ./testFindPeers.js
I/jxcore-log( 4154): 
I/jxcore-log( 4154): found test : ./testReConnect.js
I/jxcore-log( 4154): 
I/jxcore-log( 4154): found test : ./testSendData.js
I/jxcore-log( 4154): 
I/jxcore-log( 4154): Test app app.js loaded
I/jxcore-log( 4154): 
,TIME-OUT KILL (timeout was 1800000ms)

```

####Node name: thali07
Console output:
```
Error: problem deploying Android apk(/home/pi/test/builder/builds/486007975e076d4/build_android/android_0_486007975e076d4.apk) to device f56ad48d protocol failure
- waiting for device -
rm: /data/local/tmp/android_0_486007975e076d4.apk: No such file or directory



Test on this node has failed but the reason wasn't the test application itself.
 Cancelling the test result on this node.

```
####Node name: thali08
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device HT574YC04723 app:com.test.thalitest code:0 
child process exited with code 0 on device HT574YC04723 
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:0 
child process exited with code 0 on device 4325e43f 
Android task is completed 
Error: problem stopping Android apk(com.test.thalitest) to device HT574YC04723 error: device not found
 
Error: problem stopping Android apk(com.test.thalitest) to device 4325e43f error: device not found
 
```

Logcat output:
```
HTC-HTC Desire 820: 
--------- beginning of /dev/log/system
,--------- beginning of /dev/log/main
,W/jxcore-log( 4516): Initializing JXcore engine,
,W/jxcore-log( 4516): JXcore engine is ready
,W/jxcore-log( 4516): Starting JXcore engine
,W/jxcore-log( 4516): Platform android
W/jxcore-log( 4516): 
,W/jxcore-log( 4516): Process ARCH arm
W/jxcore-log( 4516): 
,I/jxcore-log( 4516): JXcore Cordova bridge is ready!
I/jxcore-log( 4516): 
,W/jxcore-log( 4516): JXcore engine is started
,I/jxcore-log( 4516): Turning radios to true
I/jxcore-log( 4516): 
,I/jxcore-log( 4516): toggleBluetooth - 
I/jxcore-log( 4516): 
,I/jxcore-log( 4516): toggleWiFi
I/jxcore-log( 4516): 
,I/jxcore-log( 4516): check test folder
I/jxcore-log( 4516): 
,I/jxcore-log( 4516): found test : ./testFindPeers.js
I/jxcore-log( 4516): 
,I/jxcore-log( 4516): found test : ./testReConnect.js
I/jxcore-log( 4516): 
,I/jxcore-log( 4516): found test : ./testSendData.js
I/jxcore-log( 4516): 
,I/jxcore-log( 4516): Test app app.js loaded
I/jxcore-log( 4516): 
,TIME-OUT KILL (timeout was 1800000ms)

samsung-SM-A300FU: 
--------- beginning of system
--------- beginning of main
,W/jxcore-log( 5625): Initializing JXcore engine
W/jxcore-log( 5625): JXcore engine is ready
,W/jxcore-log( 5625): Starting JXcore engine
,W/jxcore-log( 5625): Platform android
W/jxcore-log( 5625): 
W/jxcore-log( 5625): Process ARCH arm
W/jxcore-log( 5625): 
,I/jxcore-log( 5625): JXcore Cordova bridge is ready!,
I/jxcore-log( 5625): 
W/jxcore-log( 5625): JXcore engine is started
,I/jxcore-log( 5625): Turning radios to true
I/jxcore-log( 5625): 
,I/jxcore-log( 5625): toggleBluetooth - 
I/jxcore-log( 5625): 
,I/jxcore-log( 5625): toggleWiFi
I/jxcore-log( 5625): 
,I/jxcore-log( 5625): check test folder
I/jxcore-log( 5625): 
,I/jxcore-log( 5625): found test : ./testFindPeers.js
I/jxcore-log( 5625): 
,I/jxcore-log( 5625): found test : ./testReConnect.js
I/jxcore-log( 5625): 
,I/jxcore-log( 5625): found test : ./testSendData.js
I/jxcore-log( 5625): 
,I/jxcore-log( 5625): Test app app.js loaded
I/jxcore-log( 5625): 
,TIME-OUT KILL (timeout was 1800000ms)

```

####Node name: thali09
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device CC51WYC03425 app:com.test.thalitest code:0 
child process exited with code 0 on device CC51WYC03425 
Error! Unexpected exit on device 0c6a0f3c0bdb4e77 app:com.test.thalitest code:0 
child process exited with code 0 on device 0c6a0f3c0bdb4e77 
Android task is completed 
Error: problem stopping Android apk(com.test.thalitest) to device CC51WYC03425 error: device not found
 
Error: problem stopping Android apk(com.test.thalitest) to device 0c6a0f3c0bdb4e77 error: device not found
 
```

Logcat output:
```
HTC-HTC Desire 820: 
--------- beginning of /dev/log/system
,--------- beginning of /dev/log/main
,W/jxcore-log( 3847): Initializing JXcore engine
,W/jxcore-log( 3847): JXcore engine is ready
,W/jxcore-log( 3847): Starting JXcore engine
,W/jxcore-log( 3847): Platform android
W/jxcore-log( 3847): 
,W/jxcore-log( 3847): Process ARCH arm
W/jxcore-log( 3847): 
,I/jxcore-log( 3847): JXcore Cordova bridge is ready!
I/jxcore-log( 3847): 
,W/jxcore-log( 3847): JXcore engine is started
,I/jxcore-log( 3847): Turning radios to true
I/jxcore-log( 3847): 
,I/jxcore-log( 3847): toggleBluetooth - 
I/jxcore-log( 3847): 
,I/jxcore-log( 3847): toggleWiFi
I/jxcore-log( 3847): 
,I/jxcore-log( 3847): check test folder
I/jxcore-log( 3847): 
,I/jxcore-log( 3847): found test : ./testFindPeers.js
I/jxcore-log( 3847): 
,I/jxcore-log( 3847): found test : ./testReConnect.js
I/jxcore-log( 3847): 
,I/jxcore-log( 3847): found test : ./testSendData.js
I/jxcore-log( 3847): 
,I/jxcore-log( 3847): Test app app.js loaded
I/jxcore-log( 3847): 
,TIME-OUT KILL (timeout was 1800000ms)

LGE-Nexus 5: 
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
,W/jxcore-log( 2499): Initializing JXcore engine
,W/jxcore-log( 2499): JXcore engine is ready
,W/jxcore-log( 2499): Starting JXcore engine
,W/jxcore-log( 2499): Platform android
W/jxcore-log( 2499): 
,W/jxcore-log( 2499): Process ARCH arm
W/jxcore-log( 2499): 
,I/jxcore-log( 2499): JXcore Cordova bridge is ready!
I/jxcore-log( 2499): 
,W/jxcore-log( 2499): JXcore engine is started
,I/jxcore-log( 2499): Turning radios to true
I/jxcore-log( 2499): 
,I/jxcore-log( 2499): toggleBluetooth - 
I/jxcore-log( 2499): 
,I/jxcore-log( 2499): toggleWiFi
I/jxcore-log( 2499): 
,I/jxcore-log( 2499): check test folder
I/jxcore-log( 2499): 
,I/jxcore-log( 2499): found test : ./testFindPeers.js
I/jxcore-log( 2499): 
,I/jxcore-log( 2499): found test : ./testReConnect.js
I/jxcore-log( 2499): 
,I/jxcore-log( 2499): found test : ./testSendData.js
I/jxcore-log( 2499): 
,I/jxcore-log( 2499): Test app app.js loaded
I/jxcore-log( 2499): 
,TIME-OUT KILL (timeout was 1800000ms)

```




#### Integration Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":20,"cancel":1}}
Start Android tests : performance tests, start tests with timer

Test[0]: testSendData.js, timeout : undefined, data : {"timeout":"440000","rounds":"1","dataTimeout":"30000","dataAmount":"100000","conReTryTimeout":"4000","conReTryCount":"5"}
Test[1]: testSendData.js, timeout : undefined, data : {"timeout":"440000","rounds":"1","dataTimeout":"30000","dataAmount":"100000","conReTryTimeout":"4000","conReTryCount":"5"}
Test[2]: testSendData.js, timeout : undefined, data : {"timeout":"440000","rounds":"1","dataTimeout":"30000","dataAmount":"100000","conReTryTimeout":"4000","conReTryCount":"5"}
Start iOs tests : performance tests, start tests with timer
Test[0]: testSendData.js, timeout : undefined, data : {"timeout":"440000","rounds":"1","dataTimeout":"30000","dataAmount":"100000","conReTryTimeout":"4000","conReTryCount":"5"}
Test[1]: testSendData.js, timeout : undefined, data : {"timeout":"440000","rounds":"1","dataTimeout":"30000","dataAmount":"100000","conReTryTimeout":"4000","conReTryCount":"5"}
Test[2]: testSendData.js, timeout : undefined, data : {"timeout":"440000","rounds":"1","dataTimeout":"30000","dataAmount":"100000","conReTryTimeout":"4000","conReTryCount":"5"}

listening on *:3000

-------------- We got wait done, now starting the testing process ------------------


 
Run IS script aborted
 
[0;31mexecution aborted
 [0m

```

