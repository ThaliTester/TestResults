#### Test 47672234ea88e58 Logs

Status: 
```

ios : false

server : IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":25}}
Integration server has received  [ 'jx',
  '/home/pi/Test/server_47672234ea88e58/Sub/serverApp/index.js',
  '{"devices":{"ios":4,"android":25}}' ]

JSON { devices: { ios: 4, android: 25 } }



android : Error: Command failed: Error: Command failed: [0;31mcompilation aborted
 [0m


```
###Android Logs
####Node name: thali01
Console output:
```
STOP log received from  03157df360a1882a Test has  SUCCEEDED
STOP log received from  30049d9501da2100 Test has  SUCCEEDED
Device test finished on 03157df360a1882a 
STOP log received from  W3D7N15428022572 Test has  SUCCEEDED
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
Device test finished on 30049d9501da2100 
Device test finished on W3D7N15428022572 
Device test finished on LGH8153b36be34 
Android task is completed 
```

Logcat output:
```
samsung-SM-G920F: 
--------- beginning of system
,--------- beginning of main
W/jxcore-log(13207): Initializing JXcore engine
W/jxcore-log(13207): JXcore engine is ready
W/jxcore-log(13207): Starting JXcore engine
W/jxcore-log(13207): Platform android
W/jxcore-log(13207): 
W/jxcore-log(13207): Process ARCH arm
W/jxcore-log(13207): 
I/jxcore-log(13207): JXcore Cordova bridge is ready!
I/jxcore-log(13207): 
W/jxcore-log(13207): JXcore engine is started
E/jxcore-log(13207): >> samsung-SM-G920F
E/jxcore-log(13207): 
I/jxcore-log(13207): Total memory 2829074432
I/jxcore-log(13207): 
I/jxcore-log(13207): Free memory 126357504
I/jxcore-log(13207): 
I/jxcore-log(13207): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(13207): 
I/jxcore-log(13207): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(13207): 
I/jxcore-log(13207): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(13207): 
I/jxcore-log(13207): Size 1440 2560
I/jxcore-log(13207): 
I/jxcore-log(13207): Screen Brightness 255
I/jxcore-log(13207): 
E/jxcore-log(13207): Dummy Error Log.
E/jxcore-log(13207): 
,I/jxcore-log(13207): getBuffer is called!!!!
I/jxcore-log(13207): 
,I/jxcore-log(13207): ****TEST TOOK:  5148  ms ****
I/jxcore-log(13207): 
,I/jxcore-log(13207): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(13207): 


samsung-SM-T232: 
--------- beginning of /dev/log/system
--------- beginning of /dev/log/main
,W/jxcore-log(20144): Initializing JXcore engine
W/jxcore-log(20144): JXcore engine is ready
W/jxcore-log(20144): Starting JXcore engine
W/jxcore-log(20144): Platform android
W/jxcore-log(20144): 
W/jxcore-log(20144): Process ARCH arm
W/jxcore-log(20144): 
I/jxcore-log(20144): JXcore Cordova bridge is ready!
I/jxcore-log(20144): 
W/jxcore-log(20144): JXcore engine is started
E/jxcore-log(20144): >> samsung-SM-T232
E/jxcore-log(20144): 
I/jxcore-log(20144): Total memory 1352024064
I/jxcore-log(20144): 
I/jxcore-log(20144): Free memory 142196736
I/jxcore-log(20144): 
I/jxcore-log(20144): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(20144): 
I/jxcore-log(20144): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(20144): 
I/jxcore-log(20144): userPath [ 'www' ]
I/jxcore-log(20144): 
I/jxcore-log(20144): Size 800 1280
I/jxcore-log(20144): 
I/jxcore-log(20144): Screen Brightness 255
I/jxcore-log(20144): 
E/jxcore-log(20144): Dummy Error Log.
E/jxcore-log(20144): 
,I/jxcore-log(20144): getBuffer is called!!!!
I/jxcore-log(20144): 
,I/jxcore-log(20144): ****TEST TOOK:  5137  ms ****
I/jxcore-log(20144): 
,I/jxcore-log(20144): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(20144): 


LGE-LG-H815: 
--------- beginning of main
--------- beginning of system
,W/jxcore-log(15049): Initializing JXcore engine
W/jxcore-log(15049): JXcore engine is ready
,W/jxcore-log(15049): Starting JXcore engine
,W/jxcore-log(15049): Platform android
W/jxcore-log(15049): 
W/jxcore-log(15049): Process ARCH arm
W/jxcore-log(15049): 
,I/jxcore-log(15049): JXcore Cordova bridge is ready!
I/jxcore-log(15049): 
,W/jxcore-log(15049): JXcore engine is started
,E/jxcore-log(15049): >> LGE-LG-H815
E/jxcore-log(15049): 
,I/jxcore-log(15049): Total memory 2968948736
I/jxcore-log(15049): 
,I/jxcore-log(15049): Free memory 340127744
I/jxcore-log(15049): 
I/jxcore-log(15049): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(15049): 
I/jxcore-log(15049): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(15049): 
,I/jxcore-log(15049): userPath [ 'www' ]
I/jxcore-log(15049): 
,I/jxcore-log(15049): Size 1440 2392
I/jxcore-log(15049): 
,I/jxcore-log(15049): Screen Brightness 255
I/jxcore-log(15049): 
,E/jxcore-log(15049): Dummy Error Log.
E/jxcore-log(15049): 
,I/jxcore-log(15049): getBuffer is called!!!!
I/jxcore-log(15049): 
,I/jxcore-log(15049): ****TEST TOOK:  5086  ms ****,
I/jxcore-log(15049): 
I/jxcore-log(15049): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(15049): 


HUAWEI-ALE-L21: 
int logctl_get(): open '/dev/hwlog_switch' fail -1, 13. Permission denied

Note: log switch off, only log_main and log_events will have logs!
--------- beginning of main
,W/jxcore-log( 6981): Initializing JXcore engine
W/jxcore-log( 6981): JXcore engine is ready
W/jxcore-log( 6981): Starting JXcore engine
W/jxcore-log( 6981): Platform android
W/jxcore-log( 6981): 
W/jxcore-log( 6981): Process ARCH arm
W/jxcore-log( 6981): 
I/jxcore-log( 6981): JXcore Cordova bridge is ready!
I/jxcore-log( 6981): 
W/jxcore-log( 6981): JXcore engine is started
,E/jxcore-log( 6981): >> HUAWEI-ALE-L21
E/jxcore-log( 6981): 
,I/jxcore-log( 6981): Total memory 1949741056
I/jxcore-log( 6981): 
,I/jxcore-log( 6981): Free memory 36937728
I/jxcore-log( 6981): 
I/jxcore-log( 6981): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6981): 
I/jxcore-log( 6981): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6981): 
,I/jxcore-log( 6981): userPath [ 'www' ]
I/jxcore-log( 6981): 
,I/jxcore-log( 6981): Size 720 1184
I/jxcore-log( 6981): 
,I/jxcore-log( 6981): Screen Brightness 242
I/jxcore-log( 6981): 
,E/jxcore-log( 6981): Dummy Error Log.
E/jxcore-log( 6981): 
,I/jxcore-log( 6981): getBuffer is called!!!!
I/jxcore-log( 6981): 
,I/jxcore-log( 6981): ****TEST TOOK:  5122  ms ****
I/jxcore-log( 6981): 
I/jxcore-log( 6981): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6981): 


```

####Node name: thali02
Console output:
```
Error: problem deploying Android apk(/home/pi/test/builder/builds/47672234ea88e58/build_android/android_0_47672234ea88e58.apk) to device 8a09fc3c protocol failure
- waiting for device -
rm: /data/local/tmp/android_0_47672234ea88e58.apk: No such file or directory



Test on this node has failed but the reason wasn't the test application itself.
 Cancelling the test result on this node.

```
####Node name: thali03
Console output:
```
STOP log received from  LGD8553bed2d08 Test has  SUCCEEDED
STOP log received from  320414cd475f91e3 Test has  SUCCEEDED
STOP log received from  TA4750HV7I Test has  SUCCEEDED
Device test finished on LGD8553bed2d08 
Device test finished on TA4750HV7I 
Device test finished on 320414cd475f91e3 
Android task is completed 
```

Logcat output:
```
motorola-XT1039: 
--------- beginning of /dev/log/system
,--------- beginning of /dev/log/main
,W/jxcore-log(32524): Initializing JXcore engine
,W/jxcore-log(32524): JXcore engine is ready
,W/jxcore-log(32524): Starting JXcore engine
,W/jxcore-log(32524): Platform android
W/jxcore-log(32524): 
,W/jxcore-log(32524): Process ARCH arm
W/jxcore-log(32524): 
,I/jxcore-log(32524): JXcore Cordova bridge is ready!
I/jxcore-log(32524): 
,W/jxcore-log(32524): JXcore engine is started
,E/jxcore-log(32524): >> motorola-XT1039
E/jxcore-log(32524): 
,I/jxcore-log(32524): Total memory 893136896
I/jxcore-log(32524): 
I/jxcore-log(32524): Free memory 42459136
I/jxcore-log(32524): 
I/jxcore-log(32524): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(32524): 
,I/jxcore-log(32524): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(32524): 
,I/jxcore-log(32524): userPath [ 'www' ]
I/jxcore-log(32524): 
,I/jxcore-log(32524): Size 720 1184
I/jxcore-log(32524): 
,I/jxcore-log(32524): Screen Brightness 210
I/jxcore-log(32524): 
,E/jxcore-log(32524): Dummy Error Log.
E/jxcore-log(32524): 
,I/jxcore-log(32524): getBuffer is called!!!!
I/jxcore-log(32524): 
,I/jxcore-log(32524): ****TEST TOOK:  5198  ms ****
I/jxcore-log(32524): 
I/jxcore-log(32524): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(32524): 


LGE-LG-D855: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(32697): Initializing JXcore engine
W/jxcore-log(32697): JXcore engine is ready
W/jxcore-log(32697): Starting JXcore engine
,W/jxcore-log(32697): Platform android
W/jxcore-log(32697): 
W/jxcore-log(32697): Process ARCH arm
W/jxcore-log(32697): 
I/jxcore-log(32697): JXcore Cordova bridge is ready!
I/jxcore-log(32697): 
W/jxcore-log(32697): JXcore engine is started
E/jxcore-log(32697): >> LGE-LG-D855
E/jxcore-log(32697): 
I/jxcore-log(32697): Total memory 2995761152
I/jxcore-log(32697): 
I/jxcore-log(32697): Free memory 224612352
I/jxcore-log(32697): 
I/jxcore-log(32697): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(32697): 
I/jxcore-log(32697): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(32697): 
I/jxcore-log(32697): userPath [ 'www' ]
I/jxcore-log(32697): 
I/jxcore-log(32697): Size 1440 2392
I/jxcore-log(32697): 
I/jxcore-log(32697): Screen Brightness 177
I/jxcore-log(32697): 
E/jxcore-log(32697): Dummy Error Log.
E/jxcore-log(32697): 
I/jxcore-log(32697): getBuffer is called!!!!
I/jxcore-log(32697): 
,I/jxcore-log(32697): ****TEST TOOK:  5226  ms ****
I/jxcore-log(32697): 
I/jxcore-log(32697): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(32697): 


samsung-SM-G800F: 
--------- beginning of /dev/log/main
--------- beginning of /dev/log/system
,W/jxcore-log(31842): Initializing JXcore engine
,W/jxcore-log(31842): JXcore engine is ready
,W/jxcore-log(31842): Starting JXcore engine
,W/jxcore-log(31842): Platform android
W/jxcore-log(31842): 
,W/jxcore-log(31842): Process ARCH arm
W/jxcore-log(31842): 
,I/jxcore-log(31842): JXcore Cordova bridge is ready!
I/jxcore-log(31842): 
,W/jxcore-log(31842): JXcore engine is started
,E/jxcore-log(31842): >> samsung-SM-G800F
E/jxcore-log(31842): 
,I/jxcore-log(31842): Total memory 1319530496
I/jxcore-log(31842): 
I/jxcore-log(31842): Free memory 37097472
I/jxcore-log(31842): 
I/jxcore-log(31842): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(31842): 
,I/jxcore-log(31842): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(31842): 
,I/jxcore-log(31842): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(31842): 
,I/jxcore-log(31842): Size 720 1280
I/jxcore-log(31842): 
,I/jxcore-log(31842): Screen Brightness 255
I/jxcore-log(31842): 
,E/jxcore-log(31842): Dummy Error Log.
E/jxcore-log(31842): 
,I/jxcore-log(31842): getBuffer is called!!!!
I/jxcore-log(31842): 
,I/jxcore-log(31842): ****TEST TOOK:  5170  ms ****
I/jxcore-log(31842): 
,I/jxcore-log(31842): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(31842): 


```

####Node name: thali04
Console output:
```
STOP log received from  0be0c6c6 Test has  SUCCEEDED
STOP log received from  f56ad48d Test has  SUCCEEDED
Device test finished on 0be0c6c6 
Device test finished on f56ad48d 
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
STOP log received from  ZX1C223JKW Test has  SUCCEEDED
Device test finished on ZX1C223JKW 
Android task is completed 
```

Logcat output:
```
motorola-XT1072: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(10041): Initializing JXcore engine
W/jxcore-log(10041): JXcore engine is ready
W/jxcore-log(10041): Starting JXcore engine
,W/jxcore-log(10041): Platform android
W/jxcore-log(10041): 
,W/jxcore-log(10041): Process ARCH arm
W/jxcore-log(10041): 
,I/jxcore-log(10041): JXcore Cordova bridge is ready!
I/jxcore-log(10041): 
,W/jxcore-log(10041): JXcore engine is started
,E/jxcore-log(10041): >> motorola-XT1072
E/jxcore-log(10041): 
,I/jxcore-log(10041): Total memory 916258816
I/jxcore-log(10041): 
I/jxcore-log(10041): Free memory 53964800
I/jxcore-log(10041): 
I/jxcore-log(10041): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(10041): 
I/jxcore-log(10041): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(10041): 
,I/jxcore-log(10041): userPath [ 'www' ]
I/jxcore-log(10041): 
,I/jxcore-log(10041): Size 720 1184
I/jxcore-log(10041): 
,I/jxcore-log(10041): Screen Brightness 82
I/jxcore-log(10041): 
,E/jxcore-log(10041): Dummy Error Log.
E/jxcore-log(10041): 
,I/jxcore-log(10041): getBuffer is called!!!!
I/jxcore-log(10041): 
,I/jxcore-log(10041): ****TEST TOOK:  5283  ms ****
I/jxcore-log(10041): 
,I/jxcore-log(10041): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(10041): 


samsung-SM-N910C: 
--------- beginning of system
,--------- beginning of main
,W/jxcore-log(18900): Initializing JXcore engine
W/jxcore-log(18900): JXcore engine is ready
,W/jxcore-log(18900): Starting JXcore engine
,W/jxcore-log(18900): Platform android
W/jxcore-log(18900): 
W/jxcore-log(18900): Process ARCH arm
W/jxcore-log(18900): 
,I/jxcore-log(18900): JXcore Cordova bridge is ready!
I/jxcore-log(18900): 
W/jxcore-log(18900): JXcore engine is started
,E/jxcore-log(18900): >> samsung-SM-N910C
E/jxcore-log(18900): 
,I/jxcore-log(18900): Total memory 2971066368
I/jxcore-log(18900): 
,I/jxcore-log(18900): Free memory 297238528
I/jxcore-log(18900): 
I/jxcore-log(18900): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(18900): 
I/jxcore-log(18900): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(18900): 
,I/jxcore-log(18900): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(18900): 
,I/jxcore-log(18900): Size 1440 2560
I/jxcore-log(18900): 
,I/jxcore-log(18900): Screen Brightness 134
I/jxcore-log(18900): 
,E/jxcore-log(18900): Dummy Error Log.
E/jxcore-log(18900): 
,I/jxcore-log(18900): getBuffer is called!!!!
I/jxcore-log(18900): 
,I/jxcore-log(18900): ****TEST TOOK:  5203  ms ****
I/jxcore-log(18900): 
,I/jxcore-log(18900): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(18900): 


samsung-SM-A500FU: 
--------- beginning of system
,--------- beginning of main
,W/jxcore-log(13431): Initializing JXcore engine
W/jxcore-log(13431): JXcore engine is ready
,W/jxcore-log(13431): Starting JXcore engine
,W/jxcore-log(13431): Platform android,
W/jxcore-log(13431): 
W/jxcore-log(13431): Process ARCH arm
W/jxcore-log(13431): 
,I/jxcore-log(13431): JXcore Cordova bridge is ready!
I/jxcore-log(13431): 
,W/jxcore-log(13431): JXcore engine is started
,E/jxcore-log(13431): >> samsung-SM-A500FU
E/jxcore-log(13431): 
,I/jxcore-log(13431): Total memory 1983787008
I/jxcore-log(13431): 
,I/jxcore-log(13431): Free memory 358555648
I/jxcore-log(13431): 
,I/jxcore-log(13431): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(13431): 
I/jxcore-log(13431): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(13431): 
,I/jxcore-log(13431): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(13431): 
,I/jxcore-log(13431): Size 720 1280
I/jxcore-log(13431): 
,I/jxcore-log(13431): Screen Brightness 255
I/jxcore-log(13431): 
,E/jxcore-log(13431): Dummy Error Log.
E/jxcore-log(13431): 
,I/jxcore-log(13431): getBuffer is called!!!!
I/jxcore-log(13431): 
,I/jxcore-log(13431): ****TEST TOOK:  5072  ms ****,
I/jxcore-log(13431): 
I/jxcore-log(13431): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(13431): 


samsung-SM-G900F: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(12417): Initializing JXcore engine
,W/jxcore-log(12417): JXcore engine is ready
,W/jxcore-log(12417): Starting JXcore engine
,W/jxcore-log(12417): Platform android
W/jxcore-log(12417): 
W/jxcore-log(12417): Process ARCH arm
W/jxcore-log(12417): 
I/jxcore-log(12417): JXcore Cordova bridge is ready!
I/jxcore-log(12417): 
W/jxcore-log(12417): JXcore engine is started
E/jxcore-log(12417): >> samsung-SM-G900F
E/jxcore-log(12417): 
I/jxcore-log(12417): Total memory 1787449344
I/jxcore-log(12417): 
I/jxcore-log(12417): Free memory 51060736
I/jxcore-log(12417): 
I/jxcore-log(12417): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(12417): 
I/jxcore-log(12417): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(12417): 
I/jxcore-log(12417): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(12417): 
I/jxcore-log(12417): Size 1080 1920
I/jxcore-log(12417): 
I/jxcore-log(12417): Screen Brightness 255
I/jxcore-log(12417): 
E/jxcore-log(12417): Dummy Error Log.
E/jxcore-log(12417): 
,I/jxcore-log(12417): getBuffer is called!!!!
I/jxcore-log(12417): 
,I/jxcore-log(12417): ****TEST TOOK:  5238  ms ****
I/jxcore-log(12417): 
,I/jxcore-log(12417): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(12417): 


```

####Node name: thali05
Console output:
```
STOP log received from  SH47FWM00508 Test has  SUCCEEDED
STOP log received from  ZX1G429CRK Test has  SUCCEEDED
Device test finished on SH47FWM00508 
STOP log received from  1d6a772d Test has  SUCCEEDED
Device test finished on ZX1G429CRK 
Device test finished on 1d6a772d 
Android task is completed 
```

Logcat output:
```
HTC-HTC One_M8: 
--------- beginning of main
--------- beginning of system
,W/jxcore-log(22051): Initializing JXcore engine
W/jxcore-log(22051): JXcore engine is ready
W/jxcore-log(22051): Starting JXcore engine
W/jxcore-log(22051): Platform android
W/jxcore-log(22051): 
W/jxcore-log(22051): Process ARCH arm
W/jxcore-log(22051): 
I/jxcore-log(22051): JXcore Cordova bridge is ready!
I/jxcore-log(22051): 
W/jxcore-log(22051): JXcore engine is started
E/jxcore-log(22051): >> HTC-HTC One_M8
E/jxcore-log(22051): 
I/jxcore-log(22051): Total memory 1912020992
I/jxcore-log(22051): 
I/jxcore-log(22051): Free memory 353497088
I/jxcore-log(22051): 
I/jxcore-log(22051): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(22051): 
I/jxcore-log(22051): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(22051): 
I/jxcore-log(22051): userPath [ 'www' ]
I/jxcore-log(22051): 
I/jxcore-log(22051): Size 1080 1776
I/jxcore-log(22051): 
I/jxcore-log(22051): Screen Brightness 142
I/jxcore-log(22051): 
E/jxcore-log(22051): Dummy Error Log.
E/jxcore-log(22051): 
I/jxcore-log(22051): getBuffer is called!!!!
I/jxcore-log(22051): 
,I/jxcore-log(22051): ****TEST TOOK:  5192  ms ****
I/jxcore-log(22051): 
I/jxcore-log(22051): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(22051): 


samsung-SM-N9005: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(16311): Initializing JXcore engine,
W/jxcore-log(16311): JXcore engine is ready
,W/jxcore-log(16311): Starting JXcore engine
,W/jxcore-log(16311): Platform android
W/jxcore-log(16311): 
,W/jxcore-log(16311): Process ARCH arm
W/jxcore-log(16311): 
,I/jxcore-log(16311): JXcore Cordova bridge is ready!
I/jxcore-log(16311): 
,W/jxcore-log(16311): JXcore engine is started
,E/jxcore-log(16311): >> samsung-SM-N9005
E/jxcore-log(16311): 
,I/jxcore-log(16311): Total memory 2971471872
I/jxcore-log(16311): 
,I/jxcore-log(16311): Free memory 313282560
I/jxcore-log(16311): 
I/jxcore-log(16311): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(16311): 
I/jxcore-log(16311): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(16311): 
,I/jxcore-log(16311): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(16311): 
,I/jxcore-log(16311): Size 1080 1920
I/jxcore-log(16311): 
,I/jxcore-log(16311): Screen Brightness 255
I/jxcore-log(16311): 
,E/jxcore-log(16311): Dummy Error Log.
E/jxcore-log(16311): 
,I/jxcore-log(16311): getBuffer is called!!!!
I/jxcore-log(16311): 
,I/jxcore-log(16311): ****TEST TOOK:  5160  ms ****
I/jxcore-log(16311): 
,I/jxcore-log(16311): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(16311): 


motorola-Nexus 6: 
--------- beginning of main
--------- beginning of system
,W/jxcore-log(  651): Initializing JXcore engine
W/jxcore-log(  651): JXcore engine is ready
W/jxcore-log(  651): Starting JXcore engine
W/jxcore-log(  651): Platform android
W/jxcore-log(  651): 
W/jxcore-log(  651): Process ARCH arm
W/jxcore-log(  651): 
I/jxcore-log(  651): JXcore Cordova bridge is ready!
I/jxcore-log(  651): 
W/jxcore-log(  651): JXcore engine is started
E/jxcore-log(  651): >> motorola-Nexus 6
E/jxcore-log(  651): 
I/jxcore-log(  651): Total memory 3114405888
I/jxcore-log(  651): 
I/jxcore-log(  651): Free memory 523530240
I/jxcore-log(  651): 
I/jxcore-log(  651): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(  651): 
I/jxcore-log(  651): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(  651): 
I/jxcore-log(  651): userPath [ 'www' ]
I/jxcore-log(  651): 
I/jxcore-log(  651): Size 1440 2392
I/jxcore-log(  651): 
I/jxcore-log(  651): Screen Brightness 82
I/jxcore-log(  651): 
E/jxcore-log(  651): Dummy Error Log.
E/jxcore-log(  651): 
,I/jxcore-log(  651): getBuffer is called!!!!
I/jxcore-log(  651): 
,I/jxcore-log(  651): ****TEST TOOK:  5165  ms ****
I/jxcore-log(  651): 
I/jxcore-log(  651): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(  651): 


```

####Node name: thali06
Console output:
```
STOP log received from  022678fb504e29b0 Test has  SUCCEEDED
STOP log received from  7970f88c Test has  SUCCEEDED
Device test finished on 022678fb504e29b0 
Device test finished on 7970f88c 
STOP log received from  FA55PYS00566 Test has  SUCCEEDED
Device test finished on FA55PYS00566 
Android task is completed 
```

Logcat output:
```
HTC-HTC One M8s: 
--------- beginning of system,
--------- beginning of main
,W/jxcore-log(14525): Initializing JXcore engine,
W/jxcore-log(14525): JXcore engine is ready
,W/jxcore-log(14525): Starting JXcore engine,
,W/jxcore-log(14525): Platform android
W/jxcore-log(14525): 
,W/jxcore-log(14525): Process ARCH arm
W/jxcore-log(14525): 
,I/jxcore-log(14525): JXcore Cordova bridge is ready!
I/jxcore-log(14525): 
,W/jxcore-log(14525): JXcore engine is started
,E/jxcore-log(14525): >> HTC-HTC One M8s,
E/jxcore-log(14525): 
,I/jxcore-log(14525): Total memory 1931808768
I/jxcore-log(14525): 
I/jxcore-log(14525): Free memory 296321024
I/jxcore-log(14525): 
I/jxcore-log(14525): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(14525): 
I/jxcore-log(14525): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(14525): 
,I/jxcore-log(14525): userPath [ 'www' ]
I/jxcore-log(14525): 
,I/jxcore-log(14525): Size 1080 1776
I/jxcore-log(14525): 
,I/jxcore-log(14525): Screen Brightness 142
I/jxcore-log(14525): 
,E/jxcore-log(14525): Dummy Error Log.
E/jxcore-log(14525): 
,I/jxcore-log(14525): getBuffer is called!!!!,
I/jxcore-log(14525): 
,I/jxcore-log(14525): ****TEST TOOK:  5123  ms ****
I/jxcore-log(14525): 
,I/jxcore-log(14525): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(14525): 


samsung-SM-A300FU: 
--------- beginning of system,
--------- beginning of main
,W/jxcore-log( 6766): Initializing JXcore engine
W/jxcore-log( 6766): JXcore engine is ready
,W/jxcore-log( 6766): Starting JXcore engine
,W/jxcore-log( 6766): Platform android
W/jxcore-log( 6766): 
W/jxcore-log( 6766): Process ARCH arm
W/jxcore-log( 6766): 
,I/jxcore-log( 6766): JXcore Cordova bridge is ready!
I/jxcore-log( 6766): 
,W/jxcore-log( 6766): JXcore engine is started
,E/jxcore-log( 6766): >> samsung-SM-A300FU
E/jxcore-log( 6766): 
,I/jxcore-log( 6766): Total memory 1451114496
I/jxcore-log( 6766): 
,I/jxcore-log( 6766): Free memory 171921408
I/jxcore-log( 6766): 
,I/jxcore-log( 6766): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6766): 
I/jxcore-log( 6766): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6766): 
,I/jxcore-log( 6766): userPath [ 'www' ]
I/jxcore-log( 6766): 
,I/jxcore-log( 6766): Size 540 960
I/jxcore-log( 6766): 
,I/jxcore-log( 6766): Screen Brightness 160
I/jxcore-log( 6766): 
,E/jxcore-log( 6766): Dummy Error Log.
E/jxcore-log( 6766): 
,I/jxcore-log( 6766): getBuffer is called!!!!
I/jxcore-log( 6766): 
,I/jxcore-log( 6766): ****TEST TOOK:  5082  ms ****
I/jxcore-log( 6766): 
,I/jxcore-log( 6766): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6766): 


LGE-LG-D802: 
--------- beginning of /dev/log/system
--------- beginning of /dev/log/main
,W/jxcore-log(30080): Initializing JXcore engine
W/jxcore-log(30080): JXcore engine is ready
W/jxcore-log(30080): Starting JXcore engine
W/jxcore-log(30080): Platform android
W/jxcore-log(30080): 
W/jxcore-log(30080): Process ARCH arm
W/jxcore-log(30080): 
I/jxcore-log(30080): JXcore Cordova bridge is ready!
I/jxcore-log(30080): 
W/jxcore-log(30080): JXcore engine is started
E/jxcore-log(30080): >> LGE-LG-D802
E/jxcore-log(30080): 
I/jxcore-log(30080): Total memory 1943035904
I/jxcore-log(30080): 
I/jxcore-log(30080): Free memory 176664576
I/jxcore-log(30080): 
I/jxcore-log(30080): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(30080): 
,I/jxcore-log(30080): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(30080): 
,I/jxcore-log(30080): userPath [ 'www' ]
I/jxcore-log(30080): 
,I/jxcore-log(30080): Size 1080 1776
I/jxcore-log(30080): 
,I/jxcore-log(30080): Screen Brightness 255
I/jxcore-log(30080): 
,E/jxcore-log(30080): Dummy Error Log.
E/jxcore-log(30080): 
,I/jxcore-log(30080): getBuffer is called!!!!
I/jxcore-log(30080): 
,I/jxcore-log(30080): ****TEST TOOK:  5222  ms ****
I/jxcore-log(30080): 
,I/jxcore-log(30080): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(30080): 


```

####Node name: thali07
Console output:
```
STOP log received from  c5afcdcb Test has  SUCCEEDED
STOP log received from  4db5c8cc Test has  SUCCEEDED
Device test finished on c5afcdcb 
Device test finished on 4db5c8cc 
Android task is completed 
```

Logcat output:
```
samsung-SM-A500FU: 
--------- beginning of system
--------- beginning of main
,W/jxcore-log(15944): Initializing JXcore engine
W/jxcore-log(15944): JXcore engine is ready
,W/jxcore-log(15944): Starting JXcore engine
,W/jxcore-log(15944): Platform android
W/jxcore-log(15944): 
W/jxcore-log(15944): Process ARCH arm
W/jxcore-log(15944): 
,I/jxcore-log(15944): JXcore Cordova bridge is ready!
I/jxcore-log(15944): 
,W/jxcore-log(15944): JXcore engine is started
,E/jxcore-log(15944): >> samsung-SM-A500FU
E/jxcore-log(15944): 
,I/jxcore-log(15944): Total memory 1983787008
I/jxcore-log(15944): 
,I/jxcore-log(15944): Free memory 358592512
I/jxcore-log(15944): 
I/jxcore-log(15944): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(15944): 
I/jxcore-log(15944): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(15944): 
,I/jxcore-log(15944): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(15944): 
,I/jxcore-log(15944): Size 720 1280
I/jxcore-log(15944): 
,I/jxcore-log(15944): Screen Brightness 255
I/jxcore-log(15944): 
,E/jxcore-log(15944): Dummy Error Log.
E/jxcore-log(15944): 
,I/jxcore-log(15944): getBuffer is called!!!!
I/jxcore-log(15944): 
,I/jxcore-log(15944): ****TEST TOOK:  5086  ms ****
I/jxcore-log(15944): 
,I/jxcore-log(15944): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(15944): 


samsung-SM-G900F: 
--------- beginning of main
--------- beginning of system
,W/jxcore-log(19662): Initializing JXcore engine
W/jxcore-log(19662): JXcore engine is ready
W/jxcore-log(19662): Starting JXcore engine
,W/jxcore-log(19662): Platform android
W/jxcore-log(19662): 
W/jxcore-log(19662): Process ARCH arm
W/jxcore-log(19662): 
,I/jxcore-log(19662): JXcore Cordova bridge is ready!
I/jxcore-log(19662): 
,W/jxcore-log(19662): JXcore engine is started
,E/jxcore-log(19662): >> samsung-SM-G900F
E/jxcore-log(19662): 
,I/jxcore-log(19662): Total memory 1787449344
I/jxcore-log(19662): 
,I/jxcore-log(19662): Free memory 46354432
I/jxcore-log(19662): 
I/jxcore-log(19662): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(19662): 
,I/jxcore-log(19662): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(19662): 
,I/jxcore-log(19662): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(19662): 
,I/jxcore-log(19662): Size 1080 1920
I/jxcore-log(19662): 
,I/jxcore-log(19662): Screen Brightness 134
I/jxcore-log(19662): 
,E/jxcore-log(19662): Dummy Error Log.
E/jxcore-log(19662): 
,I/jxcore-log(19662): getBuffer is called!!!!
I/jxcore-log(19662): 
,I/jxcore-log(19662): ****TEST TOOK:  5200  ms ****
I/jxcore-log(19662): 
,I/jxcore-log(19662): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(19662): 


```

####Node name: thali08
Console output:
```
STOP log received from  HT574YC04723 Test has  SUCCEEDED
STOP log received from  4325e43f Test has  SUCCEEDED
Device test finished on HT574YC04723 
Device test finished on 4325e43f 
Android task is completed 
```

Logcat output:
```
samsung-SM-A300FU: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log( 9468): Initializing JXcore engine
W/jxcore-log( 9468): JXcore engine is ready
,W/jxcore-log( 9468): Starting JXcore engine
,W/jxcore-log( 9468): Platform android,
W/jxcore-log( 9468): 
W/jxcore-log( 9468): Process ARCH arm
W/jxcore-log( 9468): 
,I/jxcore-log( 9468): JXcore Cordova bridge is ready!,
I/jxcore-log( 9468): 
W/jxcore-log( 9468): JXcore engine is started
,E/jxcore-log( 9468): >> samsung-SM-A300FU
E/jxcore-log( 9468): 
,I/jxcore-log( 9468): Total memory 1451114496
I/jxcore-log( 9468): 
,I/jxcore-log( 9468): Free memory 236228608
I/jxcore-log( 9468): 
,I/jxcore-log( 9468): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 9468): 
I/jxcore-log( 9468): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 9468): 
,I/jxcore-log( 9468): userPath [ 'www' ]
I/jxcore-log( 9468): 
,I/jxcore-log( 9468): Size 540 960
I/jxcore-log( 9468): 
,I/jxcore-log( 9468): Screen Brightness 255
I/jxcore-log( 9468): 
,E/jxcore-log( 9468): Dummy Error Log.
E/jxcore-log( 9468): 
,I/jxcore-log( 9468): getBuffer is called!!!!
I/jxcore-log( 9468): 
,I/jxcore-log( 9468): ****TEST TOOK:  5111  ms ****
I/jxcore-log( 9468): 
,I/jxcore-log( 9468): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 9468): 


HTC-HTC Desire 820: 
--------- beginning of /dev/log/main
--------- beginning of /dev/log/system
,W/jxcore-log(23116): Initializing JXcore engine
,W/jxcore-log(23116): JXcore engine is ready
,W/jxcore-log(23116): Starting JXcore engine
,W/jxcore-log(23116): Platform android
W/jxcore-log(23116): 
,W/jxcore-log(23116): Process ARCH arm
W/jxcore-log(23116): 
I/jxcore-log(23116): JXcore Cordova bridge is ready!
I/jxcore-log(23116): 
W/jxcore-log(23116): JXcore engine is started
E/jxcore-log(23116): >> HTC-HTC Desire 820
E/jxcore-log(23116): 
I/jxcore-log(23116): Total memory 1964650496
I/jxcore-log(23116): 
I/jxcore-log(23116): Free memory 180862976
I/jxcore-log(23116): 
I/jxcore-log(23116): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(23116): 
I/jxcore-log(23116): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(23116): 
I/jxcore-log(23116): userPath [ 'www' ]
I/jxcore-log(23116): 
I/jxcore-log(23116): Size 720 1184
I/jxcore-log(23116): 
I/jxcore-log(23116): Screen Brightness 10
I/jxcore-log(23116): 
E/jxcore-log(23116): Dummy Error Log.
E/jxcore-log(23116): 
I/jxcore-log(23116): getBuffer is called!!!!
I/jxcore-log(23116): 
,I/jxcore-log(23116): ****TEST TOOK:  5163  ms ****
I/jxcore-log(23116): 
,I/jxcore-log(23116): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(23116): 


```

####Node name: thali09
Console output:
```
STOP log received from  CC51WYC03425 Test has  SUCCEEDED
Device test finished on CC51WYC03425 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 0c6a0f3c0bdb4e77 app:com.example.hello code:null 
child process exited with code null on device 0c6a0f3c0bdb4e77 
Android task is completed 
```

Logcat output:
```
LGE-Nexus 5: 
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
,W/jxcore-log(14012): Initializing JXcore engine
W/jxcore-log(14012): JXcore engine is ready
W/jxcore-log(14012): Starting JXcore engine
W/jxcore-log(14012): Platform android
W/jxcore-log(14012): 
W/jxcore-log(14012): Process ARCH arm
W/jxcore-log(14012): 
I/jxcore-log(14012): JXcore Cordova bridge is ready!
I/jxcore-log(14012): 
W/jxcore-log(14012): JXcore engine is started
E/jxcore-log(14012): >> LGE-Nexus 5
E/jxcore-log(14012): 
I/jxcore-log(14012): Total memory 1945137152
I/jxcore-log(14012): 
I/jxcore-log(14012): Free memory 40833024
I/jxcore-log(14012): 
I/jxcore-log(14012): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(14012): 
I/jxcore-log(14012): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(14012): 
I/jxcore-log(14012): userPath [ 'www' ]
I/jxcore-log(14012): 
I/jxcore-log(14012): Size 1080 1776
I/jxcore-log(14012): 
I/jxcore-log(14012): Screen Brightness 82
I/jxcore-log(14012): 
E/jxcore-log(14012): Dummy Error Log.
E/jxcore-log(14012): 
,TIME-OUT KILL (timeout was 150000ms)

HTC-HTC Desire 820: 
--------- beginning of /dev/log/system
--------- beginning of /dev/log/main
,W/jxcore-log(17884): Initializing JXcore engine
,W/jxcore-log(17884): JXcore engine is ready
,W/jxcore-log(17884): Starting JXcore engine
,W/jxcore-log(17884): Platform android
W/jxcore-log(17884): 
,W/jxcore-log(17884): Process ARCH arm
W/jxcore-log(17884): 
,I/jxcore-log(17884): JXcore Cordova bridge is ready!
I/jxcore-log(17884): 
,W/jxcore-log(17884): JXcore engine is started
,E/jxcore-log(17884): >> HTC-HTC Desire 820
E/jxcore-log(17884): 
,I/jxcore-log(17884): Total memory 1964650496
I/jxcore-log(17884): 
I/jxcore-log(17884): Free memory 166690816
I/jxcore-log(17884): 
,I/jxcore-log(17884): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(17884): 
,I/jxcore-log(17884): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(17884): 
,I/jxcore-log(17884): userPath [ 'www' ]
I/jxcore-log(17884): 
,I/jxcore-log(17884): Size 720 1184
I/jxcore-log(17884): 
,I/jxcore-log(17884): Screen Brightness 142
I/jxcore-log(17884): 
,E/jxcore-log(17884): Dummy Error Log.
E/jxcore-log(17884): 
,I/jxcore-log(17884): getBuffer is called!!!!
I/jxcore-log(17884): 
,I/jxcore-log(17884): ****TEST TOOK:  5172  ms ****
I/jxcore-log(17884): 
,I/jxcore-log(17884): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(17884): 


```




###iOS Logs

```
Iphone5-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/47672234ea88e58/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 90%] Mounting developer disk image
,[ 95%] Developer disk image already mounted
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/2CCA90E6-23B0-47A6-93F6-76305C785C73/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/2CCA90E6-23B0-47A6-93F6-76305C785C73/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/47672234ea88e58/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/47672234ea88e58/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Applications/081D2611-5FD0-4B62-906D-12BD8FB78682/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49162"
,(lldb)     command script import "/tmp/2CCA90E6-23B0-47A6-93F6-76305C785C73/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-10-21 13:48:09.917 HelloWorld[519:60b] Apache Cordova native platform version 3.9.1 is starting.
2015-10-21 13:48:09.920 HelloWorld[519:60b] Multi-tasking -> Device: YES, App: YES
,2015-10-21 13:48:09.926 HelloWorld[519:60b] Unlimited access to network resources
2015-10-21 13:48:09.933 HelloWorld[519:60b] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For mo,re information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-10-21 13:48:20.892 HelloWorld[519:60b] Resetting plugins due to page load.
,2015-10-21 13:48:21.733 HelloWorld[519:60b] Finished load of: file:///var/mobile/Applications/081D2611-5FD0-4B62-906D-12BD8FB78682/HelloWorld.app/www/index.html
,2015-10-21 13:48:21.855 HelloWorld[519:60b] JXcore Cordova plugin initializing
,2015-10-21 13:48:21.857 HelloWorld[519:650b] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone5-1
Total memory 1065000960
Free memory 630263808
execPath /private/var/mobile/Applications/081D2611-5FD0-4B62-906D-12BD8FB78682/HelloWorld.app/HelloWorld
process.cwd /var/mobile/Applications/081D2611-5FD0-4B62-906D-12BD8FB78682/HelloWorld.app/www/jxcore/
userPath []
,2015-10-21 13:48:22.322 HelloWorld[519:650b] Native method ScreenInfo not found.
,2015-10-21 13:48:22.324 HelloWorld[519:650b] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5239  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****



Iphone6-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/47672234ea88e58/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/91B7837D-A9A4-40AC-9AE4-F2ADD94E1FA2/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/91B7837D-A9A4-40AC-9AE4-F2ADD94E1FA2/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/47672234ea88e58/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/47672234ea88e58/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/41158317-4EEC-47A1-AA34-3708866332E0/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49156"
,(lldb)     command script import "/tmp/91B7837D-A9A4-40AC-9AE4-F2ADD94E1FA2/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-10-21 13:47:26.431 HelloWorld[1011:838431] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/5A1C6887-4193-458E-8891-0FD0CE1DFD9D/Library/Cookies/Cookies.binarycookies
,2015-10-21 13:47:26.813 HelloWorld[1011:838431] Apache Cordova native platform version 3.9.1 is starting.
,2015-10-21 13:47:26.814 HelloWorld[1011:838431] Multi-tasking -> Device: YES, App: YES
,2015-10-21 13:47:26.817 HelloWorld[1011:838431] Unlimited access to network resources
,2015-10-21 13:47:26.822 HelloWorld[1011:838431] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-10-21 13:47:30.466 HelloWorld[1011:838431] Resetting plugins due to page load.
,2015-10-21 13:47:30.819 HelloWorld[1011:838431] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/41158317-4EEC-47A1-AA34-3708866332E0/HelloWorld.app/www/index.html
,2015-10-21 13:47:30.860 HelloWorld[1011:838431] JXcore Cordova plugin initializing
2015-10-21 13:47:30.860 HelloWorld[1011:838567] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone6-1
Total memory 1035988992
Free memory 132775936
execPath /private/var/mobile/Containers/Bundle/Application/41158317-4EEC-47A1-AA34-3708866332E0/HelloWorld.app/HelloWorld
process.cwd /private/var/mobile/Containers/Bundle/Application/411,58317-4EEC-47A1-AA34-3708866332E0/HelloWorld.app/www/jxcore/
userPath []
2015-10-21 13:47:31.059 HelloWorld[1011:838567] Native method ScreenInfo not found.
2015-10-21 13:47:31.059 HelloWorld[1011:838567] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5105  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****



Iphone5s-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/47672234ea88e58/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/8CF6040F-FBD9-4DFC-B185-657A3E5808AB/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/8CF6040F-FBD9-4DFC-B185-657A3E5808AB/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/47672234ea88e58/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/47672234ea88e58/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/27A940E0-34F5-4A2B-8B24-763EB8447FF3/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49157"
,(lldb)     command script import "/tmp/8CF6040F-FBD9-4DFC-B185-657A3E5808AB/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-10-21 13:47:25.929 HelloWorld[936:831906] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/CF681C64-36E2-4B12-B0EE-E47FD0756F87/Library/Cookies/Cookies.binarycookies
,2015-10-21 13:47:26.334 HelloWorld[936:831906] Apache Cordova native platform version 3.9.1 is starting.
2015-10-21 13:47:26.335 HelloWorld[936:831906] Multi-tasking -> Device: YES, App: YES
,2015-10-21 13:47:26.338 HelloWorld[936:831906] Unlimited access to network resources
,2015-10-21 13:47:26.344 HelloWorld[936:831906] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-10-21 13:47:30.310 HelloWorld[936:831906] Resetting plugins due to page load.
,2015-10-21 13:47:30.660 HelloWorld[936:831906] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/27A940E0-34F5-4A2B-8B24-763EB8447FF3/HelloWorld.app/www/index.html
,2015-10-21 13:47:30.711 HelloWorld[936:831906] JXcore Cordova plugin initializing
,2015-10-21 13:47:30.712 HelloWorld[936:832040] JXcore instance initializing
Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone5s-1
Total memory 1047695360
Free memory 223363072
execPath /private/var/mobile/Containers/Bundle/Application/27A940E0-34F5-4A2B-8B24-763EB8447FF3/HelloWorld.app/HelloWorld
process.cwd /private/var/mobile/Containers/Bundle/Application/27,A940E0-34F5-4A2B-8B24-763EB8447FF3/HelloWorld.app/www/jxcore/
userPath []
2015-10-21 13:47:30.940 HelloWorld[936:832040] Native method ScreenInfo not found.
2015-10-21 13:47:30.941 HelloWorld[936:832040] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5113  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****



IpadAir2-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/47672234ea88e58/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/44D30850-A5BC-4C51-B39D-3F1A92E03406/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/44D30850-A5BC-4C51-B39D-3F1A92E03406/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/47672234ea88e58/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/47672234ea88e58/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/860007C4-B57C-4E0F-B747-F612E419F812/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49155"
,(lldb)     command script import "/tmp/44D30850-A5BC-4C51-B39D-3F1A92E03406/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-10-21 13:47:30.536 HelloWorld[717:1054339] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3953DBAA-1C31-4D2D-86B2-39E7C9BB864F/Library/Cookies/Cookies.binarycookies
,2015-10-21 13:47:31.030 HelloWorld[717:1054339] Apache Cordova native platform version 3.9.1 is starting.
,2015-10-21 13:47:31.031 HelloWorld[717:1054339] Multi-tasking -> Device: YES, App: YES
,2015-10-21 13:47:31.035 HelloWorld[717:1054339] Unlimited access to network resources
,2015-10-21 13:47:31.045 HelloWorld[717:1054339] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-10-21 13:47:40.509 HelloWorld[717:1054339] Resetting plugins due to page load.
,2015-10-21 13:47:43.991 HelloWorld[717:1054339] Finished load of: file:///var/mobile/Containers/Bundle/Application/860007C4-B57C-4E0F-B747-F612E419F812/HelloWorld.app/www/index.html
,2015-10-21 13:47:44.077 HelloWorld[717:1054339] JXcore Cordova plugin initializing
,2015-10-21 13:47:44.077 HelloWorld[717:1054603] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-IpadAir2-1
,Total memory 2084569088
,Free memory 477020160
execPath /private/var/mobile/Containers/Bundle/Application/860007C4-B57C-4E0F-B747-F612E419F812/HelloWorld.app/HelloWorld
,process.cwd /var/mobile/Containers/Bundle/Application/860007C4-B57C-4E0F-B747-F612E419F812/HelloWorld.app/www/jxcore/
,userPath []
,2015-10-21 13:47:44.276 HelloWorld[717:1054603] Native method ScreenInfo not found.
2015-10-21 13:47:44.276 HelloWorld[717:1054603] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5116  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****



```

#### Integration Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":25}}
Integration server has received  [ 'jx',
  '/home/pi/Test/server_47672234ea88e58/Sub/serverApp/index.js',
  '{"devices":{"ios":4,"android":25}}' ]

JSON { devices: { ios: 4, android: 25 } }


```

