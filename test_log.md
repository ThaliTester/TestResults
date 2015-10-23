#### Test 480372508bb6354 Logs

Status: 
```

server : IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":25}}
Star Android tests : performance tests, start tests with timer

Test[0]: testReConnect.js, timeout : 700000, data : {"timeout":"600000","rounds":"10","dataTimeout":"5000","conReTryTimeout":"2000","conReTryCount":"3"}
Star iOs tests : performance tests, start tests with timer
Test[0]: testReConnect.js, timeout : 700000, data : {"timeout":"600000","rounds":"10","dataTimeout":"5000","conReTryTimeout":"2000","conReTryCount":"3"}

listening on *:3000

got connection 

got connection 

got connection 

got connection 

got connection 

got connection 

got connection 

got connection 

got connection 

got connection 

got connection 

got connection 

got connection 

got connection 

got connection 

got connection 

got connection 

got connection 

got connection 

got connection 

-------------- We got wait done, now starting the testing process ------------------


 
Run IS script aborted
 
[0;31mexecution aborted
 [0m
Option close timeout is not valid. Please refer to the README.



android : Error: Command failed: Error: Command failed: run_.sh aborted
 [0m


TIMEOUT REACHED!
```
###Android Logs
####Node name: thali01
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 03157df360a1882a app:com.test.thalitest code:null 
child process exited with code null on device 03157df360a1882a 
Error! Unexpected exit on device 30049d9501da2100 app:com.test.thalitest code:null 
child process exited with code null on device 30049d9501da2100 
Error! Unexpected exit on device LGH8153b36be34 app:com.test.thalitest code:null 
child process exited with code null on device LGH8153b36be34 
Error! Unexpected exit on device W3D7N15428022572 app:com.test.thalitest code:null 
child process exited with code null on device W3D7N15428022572 
Android task is completed 
```

Logcat output:
```
samsung-SM-G920F: 
--------- beginning of system
,--------- beginning of main
,W/jxcore-log(16200): Initializing JXcore engine
W/jxcore-log(16200): JXcore engine is ready
,W/jxcore-log(16200): Starting JXcore engine
,W/jxcore-log(16200): Platform android
W/jxcore-log(16200): 
W/jxcore-log(16200): Process ARCH arm
W/jxcore-log(16200): 
,I/jxcore-log(16200): JXcore Cordova bridge is ready!
I/jxcore-log(16200): 
,W/jxcore-log(16200): JXcore engine is started
,I/jxcore-log(16200): Turning radios to true
I/jxcore-log(16200): 
,I/jxcore-log(16200): toggleBluetooth - 
I/jxcore-log(16200): 
,I/jxcore-log(16200): toggleWiFi
I/jxcore-log(16200): 
,I/jxcore-log(16200): my name is : DEV6275
I/jxcore-log(16200): 
I/jxcore-log(16200): Connect to  address : 192.168.1.150 type: override
I/jxcore-log(16200): 
,TIME-OUT KILL (timeout was 1800000ms)

samsung-SM-T232: 
--------- beginning of /dev/log/system
,--------- beginning of /dev/log/main
,W/jxcore-log(29567): Initializing JXcore engine
,W/jxcore-log(29567): JXcore engine is ready
,W/jxcore-log(29567): Starting JXcore engine
,W/jxcore-log(29567): Platform android
W/jxcore-log(29567): 
,W/jxcore-log(29567): Process ARCH arm
W/jxcore-log(29567): 
,I/jxcore-log(29567): JXcore Cordova bridge is ready!
I/jxcore-log(29567): 
,W/jxcore-log(29567): JXcore engine is started
,I/jxcore-log(29567): Turning radios to true
I/jxcore-log(29567): 
,I/jxcore-log(29567): toggleBluetooth - 
I/jxcore-log(29567): 
,I/jxcore-log(29567): toggleWiFi
I/jxcore-log(29567): 
,I/jxcore-log(29567): my name is : DEV9678
I/jxcore-log(29567): 
,I/jxcore-log(29567): Connect to  address : 192.168.1.150 type: override
I/jxcore-log(29567): 
,TIME-OUT KILL (timeout was 1800000ms)

LGE-LG-H815: 
--------- beginning of system
--------- beginning of main
,W/jxcore-log(12971): Initializing JXcore engine
W/jxcore-log(12971): JXcore engine is ready
W/jxcore-log(12971): Starting JXcore engine
W/jxcore-log(12971): Platform android
W/jxcore-log(12971): 
W/jxcore-log(12971): Process ARCH arm
W/jxcore-log(12971): 
,I/jxcore-log(12971): JXcore Cordova bridge is ready!
I/jxcore-log(12971): 
,W/jxcore-log(12971): JXcore engine is started
,I/jxcore-log(12971): Turning radios to true
I/jxcore-log(12971): 
,I/jxcore-log(12971): toggleBluetooth - 
I/jxcore-log(12971): 
,I/jxcore-log(12971): toggleWiFi
I/jxcore-log(12971): 
,I/jxcore-log(12971): my name is : DEV9757
I/jxcore-log(12971): 
I/jxcore-log(12971): Connect to  address : 192.168.1.150 type: override
I/jxcore-log(12971): 
,TIME-OUT KILL (timeout was 1800000ms)

HUAWEI-ALE-L21: 
int logctl_get(): open '/dev/hwlog_switch' fail -1, 13. Permission denied

Note: log switch off, only log_main and log_events will have logs!
--------- beginning of main
,W/jxcore-log(17292): Initializing JXcore engine
W/jxcore-log(17292): JXcore engine is ready
W/jxcore-log(17292): Starting JXcore engine
,W/jxcore-log(17292): Platform android
W/jxcore-log(17292): 
W/jxcore-log(17292): Process ARCH arm
W/jxcore-log(17292): 
,I/jxcore-log(17292): JXcore Cordova bridge is ready!
I/jxcore-log(17292): 
W/jxcore-log(17292): JXcore engine is started
,I/jxcore-log(17292): Turning radios to true
I/jxcore-log(17292): 
,I/jxcore-log(17292): toggleBluetooth - 
I/jxcore-log(17292): 
,I/jxcore-log(17292): toggleWiFi
I/jxcore-log(17292): 
,I/jxcore-log(17292): my name is : DEV8241
I/jxcore-log(17292): 
I/jxcore-log(17292): Connect to  address : 192.168.1.150 type: override
I/jxcore-log(17292): 
,TIME-OUT KILL (timeout was 1800000ms)

```

####Node name: thali02
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 09a9416e0297d102 app:com.test.thalitest code:null 
child process exited with code null on device 09a9416e0297d102 
Error! Unexpected exit on device LGD7228ee9cf5b app:com.test.thalitest code:null 
child process exited with code null on device LGD7228ee9cf5b 
Android task is completed 
```

Logcat output:
```
LGE-Nexus 5: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(13321): Initializing JXcore engine
W/jxcore-log(13321): JXcore engine is ready
W/jxcore-log(13321): Starting JXcore engine
,W/jxcore-log(13321): Platform android
W/jxcore-log(13321): 
W/jxcore-log(13321): Process ARCH arm
W/jxcore-log(13321): 
,I/jxcore-log(13321): JXcore Cordova bridge is ready!
I/jxcore-log(13321): 
,W/jxcore-log(13321): JXcore engine is started
,I/jxcore-log(13321): Turning radios to true
,I/jxcore-log(13321): 
,I/jxcore-log(13321): toggleBluetooth - 
I/jxcore-log(13321): 
,I/jxcore-log(13321): toggleWiFi
I/jxcore-log(13321): 
,I/jxcore-log(13321): my name is : DEV6529
I/jxcore-log(13321): 
I/jxcore-log(13321): Connect to  address : 192.168.1.150 type: override
I/jxcore-log(13321): 
,TIME-OUT KILL (timeout was 1800000ms)

LGE-LG-D722: 
--------- beginning of main
--------- beginning of system
,W/jxcore-log(26920): Initializing JXcore engine
W/jxcore-log(26920): JXcore engine is ready
W/jxcore-log(26920): Starting JXcore engine
,W/jxcore-log(26920): Platform android
W/jxcore-log(26920): 
W/jxcore-log(26920): Process ARCH arm
W/jxcore-log(26920): 
,I/jxcore-log(26920): JXcore Cordova bridge is ready!
I/jxcore-log(26920): 
,W/jxcore-log(26920): JXcore engine is started
,I/jxcore-log(26920): Turning radios to true
I/jxcore-log(26920): 
,I/jxcore-log(26920): toggleBluetooth - 
I/jxcore-log(26920): 
,I/jxcore-log(26920): toggleWiFi
I/jxcore-log(26920): 
,TIME-OUT KILL (timeout was 1800000ms)

```

####Node name: thali03
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device TA4750HV7I app:com.test.thalitest code:null 
child process exited with code null on device TA4750HV7I 
Error! Unexpected exit on device LGD8553bed2d08 app:com.test.thalitest code:null 
child process exited with code null on device LGD8553bed2d08 
Error! Unexpected exit on device 320414cd475f91e3 app:com.test.thalitest code:null 
child process exited with code null on device 320414cd475f91e3 
Android task is completed 
```

Logcat output:
```
motorola-XT1039: 
--------- beginning of /dev/log/system
,--------- beginning of /dev/log/main
,W/jxcore-log( 1490): Initializing JXcore engine
,W/jxcore-log( 1490): JXcore engine is ready
,W/jxcore-log( 1490): Starting JXcore engine
,W/jxcore-log( 1490): Platform android
W/jxcore-log( 1490): 
,W/jxcore-log( 1490): Process ARCH arm
W/jxcore-log( 1490): 
,I/jxcore-log( 1490): JXcore Cordova bridge is ready!
I/jxcore-log( 1490): 
,W/jxcore-log( 1490): JXcore engine is started
,I/jxcore-log( 1490): Turning radios to true
I/jxcore-log( 1490): 
,I/jxcore-log( 1490): toggleBluetooth - 
I/jxcore-log( 1490): 
,I/jxcore-log( 1490): toggleWiFi
I/jxcore-log( 1490): 
,I/jxcore-log( 1490): my name is : DEV9550
I/jxcore-log( 1490): 
,I/jxcore-log( 1490): Connect to  address : 192.168.1.150 type: override
I/jxcore-log( 1490): 
,TIME-OUT KILL (timeout was 1800000ms)

LGE-LG-D855: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(29425): Initializing JXcore engine
,W/jxcore-log(29425): JXcore engine is ready
,W/jxcore-log(29425): Starting JXcore engine
,W/jxcore-log(29425): Platform android
W/jxcore-log(29425): 
,W/jxcore-log(29425): Process ARCH arm
W/jxcore-log(29425): 
,I/jxcore-log(29425): JXcore Cordova bridge is ready!
I/jxcore-log(29425): 
,W/jxcore-log(29425): JXcore engine is started
,I/jxcore-log(29425): Turning radios to true
I/jxcore-log(29425): 
,I/jxcore-log(29425): toggleBluetooth - 
I/jxcore-log(29425): 
,I/jxcore-log(29425): toggleWiFi
I/jxcore-log(29425): 
,I/jxcore-log(29425): my name is : DEV5573
I/jxcore-log(29425): 
I/jxcore-log(29425): Connect to  address : 192.168.1.150 type: override
I/jxcore-log(29425): 
,TIME-OUT KILL (timeout was 1800000ms)

samsung-SM-G800F: 
--------- beginning of /dev/log/main
--------- beginning of /dev/log/system
,W/jxcore-log(24392): Initializing JXcore engine
,W/jxcore-log(24392): JXcore engine is ready
,W/jxcore-log(24392): Starting JXcore engine
,W/jxcore-log(24392): Platform android
W/jxcore-log(24392): 
,W/jxcore-log(24392): Process ARCH arm
W/jxcore-log(24392): 
,I/jxcore-log(24392): JXcore Cordova bridge is ready!
I/jxcore-log(24392): 
,W/jxcore-log(24392): JXcore engine is started
,I/jxcore-log(24392): Turning radios to true
I/jxcore-log(24392): 
,I/jxcore-log(24392): toggleBluetooth - 
I/jxcore-log(24392): 
,I/jxcore-log(24392): toggleWiFi
I/jxcore-log(24392): 
,I/jxcore-log(24392): my name is : DEV1645
I/jxcore-log(24392): 
,I/jxcore-log(24392): Connect to  address : 192.168.1.150 type: override
I/jxcore-log(24392): 
,TIME-OUT KILL (timeout was 1800000ms)

```

####Node name: thali04
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:null 
child process exited with code null on device ZX1C223JKW 
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Error! Unexpected exit on device f56ad48d app:com.test.thalitest code:null 
child process exited with code null on device f56ad48d 
Error! Unexpected exit on device 0be0c6c6 app:com.test.thalitest code:null 
child process exited with code null on device 0be0c6c6 
Android task is completed 
```

Logcat output:
```
motorola-XT1072: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(13295): Initializing JXcore engine
W/jxcore-log(13295): JXcore engine is ready
,W/jxcore-log(13295): Starting JXcore engine
,W/jxcore-log(13295): Platform android
W/jxcore-log(13295): 
,W/jxcore-log(13295): Process ARCH arm
W/jxcore-log(13295): 
,I/jxcore-log(13295): JXcore Cordova bridge is ready!
I/jxcore-log(13295): 
,W/jxcore-log(13295): JXcore engine is started
,I/jxcore-log(13295): Turning radios to true
I/jxcore-log(13295): 
,I/jxcore-log(13295): toggleBluetooth - 
I/jxcore-log(13295): 
,I/jxcore-log(13295): toggleWiFi
I/jxcore-log(13295): 
,I/jxcore-log(13295): my name is : DEV8536
I/jxcore-log(13295): 
,I/jxcore-log(13295): Connect to  address : 192.168.1.150 type: override
I/jxcore-log(13295): 
,TIME-OUT KILL (timeout was 1800000ms)

samsung-SM-N910C: 
--------- beginning of system,
--------- beginning of main
,W/jxcore-log(21977): Initializing JXcore engine
,W/jxcore-log(21977): JXcore engine is ready
,W/jxcore-log(21977): Starting JXcore engine
,W/jxcore-log(21977): Platform android
W/jxcore-log(21977): 
W/jxcore-log(21977): Process ARCH arm
W/jxcore-log(21977): 
,I/jxcore-log(21977): JXcore Cordova bridge is ready!
I/jxcore-log(21977): 
W/jxcore-log(21977): JXcore engine is started
,I/jxcore-log(21977): Turning radios to true
I/jxcore-log(21977): 
,I/jxcore-log(21977): toggleBluetooth - 
I/jxcore-log(21977): 
,I/jxcore-log(21977): toggleWiFi
I/jxcore-log(21977): 
,I/jxcore-log(21977): my name is : DEV2084
I/jxcore-log(21977): 
I/jxcore-log(21977): Connect to  address : 192.168.1.150 type: override
I/jxcore-log(21977): 
,TIME-OUT KILL (timeout was 1800000ms)

samsung-SM-A500FU: 
--------- beginning of system
--------- beginning of main
,W/jxcore-log(19152): Initializing JXcore engine
W/jxcore-log(19152): JXcore engine is ready
,W/jxcore-log(19152): Starting JXcore engine
,W/jxcore-log(19152): Platform android,
W/jxcore-log(19152): 
W/jxcore-log(19152): Process ARCH arm
W/jxcore-log(19152): 
,I/jxcore-log(19152): JXcore Cordova bridge is ready!,
I/jxcore-log(19152): 
W/jxcore-log(19152): JXcore engine is started
,I/jxcore-log(19152): Turning radios to true
I/jxcore-log(19152): 
,I/jxcore-log(19152): toggleBluetooth - 
I/jxcore-log(19152): 
,I/jxcore-log(19152): toggleWiFi,
I/jxcore-log(19152): 
,I/jxcore-log(19152): my name is : DEV5621
I/jxcore-log(19152): 
I/jxcore-log(19152): Connect to  address : 192.168.1.150 type: override
I/jxcore-log(19152): 
,TIME-OUT KILL (timeout was 1800000ms)

samsung-SM-G900F: 
--------- beginning of main
--------- beginning of system
,W/jxcore-log(29060): Initializing JXcore engine
W/jxcore-log(29060): JXcore engine is ready
,W/jxcore-log(29060): Starting JXcore engine
,W/jxcore-log(29060): Platform android
W/jxcore-log(29060): 
W/jxcore-log(29060): Process ARCH arm
W/jxcore-log(29060): 
,I/jxcore-log(29060): JXcore Cordova bridge is ready!
I/jxcore-log(29060): 
W/jxcore-log(29060): JXcore engine is started
,I/jxcore-log(29060): Turning radios to true
I/jxcore-log(29060): 
,I/jxcore-log(29060): toggleBluetooth - 
I/jxcore-log(29060): 
,I/jxcore-log(29060): toggleWiFi
I/jxcore-log(29060): 
,I/jxcore-log(29060): my name is : DEV9804
I/jxcore-log(29060): 
,I/jxcore-log(29060): Connect to  address : 192.168.1.150 type: override
I/jxcore-log(29060): 
,TIME-OUT KILL (timeout was 1800000ms)

```

####Node name: thali05
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device SH47FWM00508 app:com.test.thalitest code:null 
child process exited with code null on device SH47FWM00508 
Error! Unexpected exit on device 1d6a772d app:com.test.thalitest code:null 
child process exited with code null on device 1d6a772d 
Error! Unexpected exit on device ZX1G429CRK app:com.test.thalitest code:null 
child process exited with code null on device ZX1G429CRK 
Android task is completed 
```

Logcat output:
```
HTC-HTC One_M8: 
--------- beginning of system,
--------- beginning of main
,W/jxcore-log( 8470): Initializing JXcore engine,
W/jxcore-log( 8470): JXcore engine is ready
,W/jxcore-log( 8470): Starting JXcore engine
,W/jxcore-log( 8470): Platform android
W/jxcore-log( 8470): 
,W/jxcore-log( 8470): Process ARCH arm
W/jxcore-log( 8470): 
,I/jxcore-log( 8470): JXcore Cordova bridge is ready!,
I/jxcore-log( 8470): 
W/jxcore-log( 8470): JXcore engine is started
,I/jxcore-log( 8470): Turning radios to true
I/jxcore-log( 8470): 
,I/jxcore-log( 8470): toggleBluetooth - 
I/jxcore-log( 8470): 
,I/jxcore-log( 8470): toggleWiFi,
I/jxcore-log( 8470): 
,I/jxcore-log( 8470): my name is : DEV941,
I/jxcore-log( 8470): 
I/jxcore-log( 8470): Connect to  address : 192.168.1.150 type: override
I/jxcore-log( 8470): 
,TIME-OUT KILL (timeout was 1800000ms)

samsung-SM-N9005: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(13490): Initializing JXcore engine
,W/jxcore-log(13490): JXcore engine is ready
,W/jxcore-log(13490): Starting JXcore engine
,W/jxcore-log(13490): Platform android
W/jxcore-log(13490): 
,W/jxcore-log(13490): Process ARCH arm
W/jxcore-log(13490): 
,I/jxcore-log(13490): JXcore Cordova bridge is ready!
I/jxcore-log(13490): 
W/jxcore-log(13490): JXcore engine is started
,I/jxcore-log(13490): Turning radios to true
I/jxcore-log(13490): 
,I/jxcore-log(13490): toggleBluetooth - 
I/jxcore-log(13490): 
,I/jxcore-log(13490): toggleWiFi
I/jxcore-log(13490): 
,I/jxcore-log(13490): my name is : DEV7096
I/jxcore-log(13490): 
I/jxcore-log(13490): Connect to  address : 192.168.1.150 type: override
I/jxcore-log(13490): 
,TIME-OUT KILL (timeout was 1800000ms)

motorola-Nexus 6: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(29412): Initializing JXcore engine,
W/jxcore-log(29412): JXcore engine is ready
,W/jxcore-log(29412): Starting JXcore engine,
,W/jxcore-log(29412): Platform android
W/jxcore-log(29412): 
,W/jxcore-log(29412): Process ARCH arm
W/jxcore-log(29412): 
,I/jxcore-log(29412): JXcore Cordova bridge is ready!
I/jxcore-log(29412): 
W/jxcore-log(29412): JXcore engine is started
,I/jxcore-log(29412): Turning radios to true
I/jxcore-log(29412): 
,I/jxcore-log(29412): toggleBluetooth - 
I/jxcore-log(29412): 
,I/jxcore-log(29412): toggleWiFi
I/jxcore-log(29412): 
,I/jxcore-log(29412): my name is : DEV3873
I/jxcore-log(29412): 
,I/jxcore-log(29412): Connect to  address : 192.168.1.150 type: override
I/jxcore-log(29412): 
,TIME-OUT KILL (timeout was 1800000ms)

```

####Node name: thali06
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:null 
child process exited with code null on device FA55PYS00566 
Error! Unexpected exit on device 7970f88c app:com.test.thalitest code:null 
child process exited with code null on device 7970f88c 
Error! Unexpected exit on device 022678fb504e29b0 app:com.test.thalitest code:null 
child process exited with code null on device 022678fb504e29b0 
Android task is completed 
```

Logcat output:
```
HTC-HTC One M8s: 
--------- beginning of system,
--------- beginning of main
,W/jxcore-log(31652): Initializing JXcore engine
,W/jxcore-log(31652): JXcore engine is ready
,W/jxcore-log(31652): Starting JXcore engine
,W/jxcore-log(31652): Platform android
W/jxcore-log(31652): 
W/jxcore-log(31652): Process ARCH arm
W/jxcore-log(31652): 
,I/jxcore-log(31652): JXcore Cordova bridge is ready!,
I/jxcore-log(31652): 
W/jxcore-log(31652): JXcore engine is started
,I/jxcore-log(31652): Turning radios to true
I/jxcore-log(31652): 
,I/jxcore-log(31652): toggleBluetooth - 
I/jxcore-log(31652): 
,I/jxcore-log(31652): toggleWiFi,
I/jxcore-log(31652): 
,I/jxcore-log(31652): my name is : DEV3235
I/jxcore-log(31652): 
I/jxcore-log(31652): Connect to  address : 192.168.1.150 type: override
I/jxcore-log(31652): 
,TIME-OUT KILL (timeout was 1800000ms)

samsung-SM-A300FU: 
--------- beginning of system
--------- beginning of main
,W/jxcore-log(23292): Initializing JXcore engine
W/jxcore-log(23292): JXcore engine is ready
,W/jxcore-log(23292): Starting JXcore engine
,W/jxcore-log(23292): Platform android
W/jxcore-log(23292): 
W/jxcore-log(23292): Process ARCH arm
W/jxcore-log(23292): 
,I/jxcore-log(23292): JXcore Cordova bridge is ready!
I/jxcore-log(23292): 
W/jxcore-log(23292): JXcore engine is started
,I/jxcore-log(23292): Turning radios to true,
I/jxcore-log(23292): 
,I/jxcore-log(23292): toggleBluetooth - 
I/jxcore-log(23292): 
,I/jxcore-log(23292): toggleWiFi
I/jxcore-log(23292): 
,I/jxcore-log(23292): my name is : DEV9273
I/jxcore-log(23292): 
I/jxcore-log(23292): Connect to  address : 192.168.1.150 type: override
I/jxcore-log(23292): 
,TIME-OUT KILL (timeout was 1800000ms)

LGE-LG-D802: 
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
,W/jxcore-log(27078): Initializing JXcore engine,
,W/jxcore-log(27078): JXcore engine is ready
,W/jxcore-log(27078): Starting JXcore engine
,W/jxcore-log(27078): Platform android
W/jxcore-log(27078): 
,W/jxcore-log(27078): Process ARCH arm
W/jxcore-log(27078): 
,I/jxcore-log(27078): JXcore Cordova bridge is ready!
I/jxcore-log(27078): 
,W/jxcore-log(27078): JXcore engine is started
,I/jxcore-log(27078): Turning radios to true
I/jxcore-log(27078): 
,I/jxcore-log(27078): toggleBluetooth - 
I/jxcore-log(27078): 
,I/jxcore-log(27078): toggleWiFi
I/jxcore-log(27078): 
,I/jxcore-log(27078): my name is : DEV8692
I/jxcore-log(27078): 
,I/jxcore-log(27078): Connect to  address : 192.168.1.150 type: override
I/jxcore-log(27078): 
,TIME-OUT KILL (timeout was 1800000ms)

```

####Node name: thali07
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:null 
child process exited with code null on device 4db5c8cc 
Error! Unexpected exit on device c5afcdcb app:com.test.thalitest code:null 
child process exited with code null on device c5afcdcb 
Android task is completed 
```

Logcat output:
```
samsung-SM-A500FU: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log( 7269): Initializing JXcore engine
,W/jxcore-log( 7269): JXcore engine is ready
,W/jxcore-log( 7269): Starting JXcore engine
,W/jxcore-log( 7269): Platform android
W/jxcore-log( 7269): 
W/jxcore-log( 7269): Process ARCH arm
W/jxcore-log( 7269): 
,I/jxcore-log( 7269): JXcore Cordova bridge is ready!
I/jxcore-log( 7269): 
,W/jxcore-log( 7269): JXcore engine is started
,I/jxcore-log( 7269): Turning radios to true
I/jxcore-log( 7269): 
,I/jxcore-log( 7269): toggleBluetooth - 
I/jxcore-log( 7269): 
,I/jxcore-log( 7269): toggleWiFi
I/jxcore-log( 7269): 
,I/jxcore-log( 7269): my name is : DEV9586
I/jxcore-log( 7269): 
I/jxcore-log( 7269): Connect to  address : 192.168.1.150 type: override
I/jxcore-log( 7269): 
,TIME-OUT KILL (timeout was 1800000ms)

samsung-SM-G900F: 
--------- beginning of main
--------- beginning of system
,W/jxcore-log(17546): Initializing JXcore engine
W/jxcore-log(17546): JXcore engine is ready
W/jxcore-log(17546): Starting JXcore engine
W/jxcore-log(17546): Platform android
W/jxcore-log(17546): 
W/jxcore-log(17546): Process ARCH arm
W/jxcore-log(17546): 
,I/jxcore-log(17546): JXcore Cordova bridge is ready!
I/jxcore-log(17546): 
,W/jxcore-log(17546): JXcore engine is started
,I/jxcore-log(17546): Turning radios to true
I/jxcore-log(17546): 
,I/jxcore-log(17546): toggleBluetooth - 
I/jxcore-log(17546): 
,I/jxcore-log(17546): toggleWiFi
I/jxcore-log(17546): 
,I/jxcore-log(17546): my name is : DEV2651
I/jxcore-log(17546): 
I/jxcore-log(17546): Connect to  address : 192.168.1.150 type: override
I/jxcore-log(17546): 
,TIME-OUT KILL (timeout was 1800000ms)

```

####Node name: thali08
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:null 
child process exited with code null on device 4325e43f 
Error! Unexpected exit on device HT574YC04723 app:com.test.thalitest code:null 
child process exited with code null on device HT574YC04723 
Android task is completed 
```

Logcat output:
```
samsung-SM-A300FU: 
--------- beginning of system,
--------- beginning of main
,W/jxcore-log(13974): Initializing JXcore engine
W/jxcore-log(13974): JXcore engine is ready
,W/jxcore-log(13974): Starting JXcore engine
,W/jxcore-log(13974): Platform android
W/jxcore-log(13974): 
W/jxcore-log(13974): Process ARCH arm
W/jxcore-log(13974): 
,I/jxcore-log(13974): JXcore Cordova bridge is ready!,
I/jxcore-log(13974): 
W/jxcore-log(13974): JXcore engine is started
,I/jxcore-log(13974): Turning radios to true
I/jxcore-log(13974): 
,I/jxcore-log(13974): toggleBluetooth - 
I/jxcore-log(13974): 
,I/jxcore-log(13974): toggleWiFi
I/jxcore-log(13974): 
,I/jxcore-log(13974): my name is : DEV954,
I/jxcore-log(13974): 
I/jxcore-log(13974): Connect to  address : 192.168.1.150 type: override
I/jxcore-log(13974): 
,TIME-OUT KILL (timeout was 1800000ms)

HTC-HTC Desire 820: 
--------- beginning of /dev/log/system
--------- beginning of /dev/log/main
,W/jxcore-log(11486): Initializing JXcore engine
,W/jxcore-log(11486): JXcore engine is ready
,W/jxcore-log(11486): Starting JXcore engine
,W/jxcore-log(11486): Platform android
W/jxcore-log(11486): 
,W/jxcore-log(11486): Process ARCH arm
W/jxcore-log(11486): 
,I/jxcore-log(11486): JXcore Cordova bridge is ready!
I/jxcore-log(11486): 
,W/jxcore-log(11486): JXcore engine is started
,I/jxcore-log(11486): Turning radios to true
I/jxcore-log(11486): 
,I/jxcore-log(11486): toggleBluetooth - 
I/jxcore-log(11486): 
,I/jxcore-log(11486): toggleWiFi
I/jxcore-log(11486): 
,I/jxcore-log(11486): my name is : DEV4621
I/jxcore-log(11486): 
,I/jxcore-log(11486): Connect to  address : 192.168.1.150 type: override
I/jxcore-log(11486): 
,TIME-OUT KILL (timeout was 1800000ms)

```

####Node name: thali09
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 0c6a0f3c0bdb4e77 app:com.test.thalitest code:null 
child process exited with code null on device 0c6a0f3c0bdb4e77 
Error! Unexpected exit on device CC51WYC03425 app:com.test.thalitest code:null 
child process exited with code null on device CC51WYC03425 
Android task is completed 
```

Logcat output:
```
LGE-Nexus 5: 
--------- beginning of /dev/log/system
,--------- beginning of /dev/log/main
,TIME-OUT KILL (timeout was 1800000ms)

HTC-HTC Desire 820: 
--------- beginning of /dev/log/main
--------- beginning of /dev/log/system
,W/jxcore-log( 9241): Initializing JXcore engine
,W/jxcore-log( 9241): JXcore engine is ready
,W/jxcore-log( 9241): Starting JXcore engine
,W/jxcore-log( 9241): Platform android
W/jxcore-log( 9241): 
,W/jxcore-log( 9241): Process ARCH arm
W/jxcore-log( 9241): 
,I/jxcore-log( 9241): JXcore Cordova bridge is ready!
I/jxcore-log( 9241): 
,W/jxcore-log( 9241): JXcore engine is started
,I/jxcore-log( 9241): Turning radios to true
I/jxcore-log( 9241): 
,I/jxcore-log( 9241): toggleBluetooth - 
I/jxcore-log( 9241): 
,I/jxcore-log( 9241): toggleWiFi
I/jxcore-log( 9241): 
,I/jxcore-log( 9241): my name is : DEV567
I/jxcore-log( 9241): 
,I/jxcore-log( 9241): Connect to  address : 192.168.1.150 type: override
I/jxcore-log( 9241): 
,TIME-OUT KILL (timeout was 1800000ms)

```




#### Integration Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":25}}
Star Android tests : performance tests, start tests with timer

Test[0]: testReConnect.js, timeout : 700000, data : {"timeout":"600000","rounds":"10","dataTimeout":"5000","conReTryTimeout":"2000","conReTryCount":"3"}
Star iOs tests : performance tests, start tests with timer
Test[0]: testReConnect.js, timeout : 700000, data : {"timeout":"600000","rounds":"10","dataTimeout":"5000","conReTryTimeout":"2000","conReTryCount":"3"}

listening on *:3000

got connection 

got connection 

got connection 

got connection 

got connection 

got connection 

got connection 

got connection 

got connection 

got connection 

got connection 

got connection 

got connection 

got connection 

got connection 

got connection 

got connection 

got connection 

got connection 

got connection 

-------------- We got wait done, now starting the testing process ------------------


 
Run IS script aborted
 
[0;31mexecution aborted
 [0m
Option close timeout is not valid. Please refer to the README.


```

