#### Test 4767223456c0496 Logs

Status: 
```

ios : false

server : IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":25}}
Integration server has received  [ 'jx',
  '/home/pi/Test/server_4767223456c0496/Sub/serverApp/index.js',
  '{"devices":{"ios":4,"android":25}}' ]

JSON { devices: { ios: 4, android: 25 } }



android : Error: Command failed: Error: Command failed: run_.sh aborted
 [0m


```
###Android Logs
####Node name: thali01
Console output:
```
STOP log received from  30049d9501da2100 Test has  SUCCEEDED
STOP log received from  W3D7N15428022572 Test has  SUCCEEDED
Device test finished on 30049d9501da2100 
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
Device test finished on W3D7N15428022572 
Device test finished on LGH8153b36be34 
STOP log received from  03157df360a1882a Test has  SUCCEEDED
Device test finished on 03157df360a1882a 
Android task is completed 
```

Logcat output:
```
samsung-SM-G920F: 
--------- beginning of system
,--------- beginning of main
,W/jxcore-log(16944): Initializing JXcore engine
W/jxcore-log(16944): JXcore engine is ready
,W/jxcore-log(16944): Starting JXcore engine
,W/jxcore-log(16944): Platform android
W/jxcore-log(16944): 
W/jxcore-log(16944): Process ARCH arm
W/jxcore-log(16944): 
,I/jxcore-log(16944): JXcore Cordova bridge is ready!
I/jxcore-log(16944): 
W/jxcore-log(16944): JXcore engine is started
,E/jxcore-log(16944): >> samsung-SM-G920F
E/jxcore-log(16944): 
,I/jxcore-log(16944): Total memory 2829074432
I/jxcore-log(16944): 
I/jxcore-log(16944): Free memory 197914624
I/jxcore-log(16944): 
I/jxcore-log(16944): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(16944): 
I/jxcore-log(16944): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(16944): 
,I/jxcore-log(16944): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(16944): 
,I/jxcore-log(16944): Size 1440 2560
I/jxcore-log(16944): 
,I/jxcore-log(16944): Screen Brightness 255
I/jxcore-log(16944): 
E/jxcore-log(16944): Dummy Error Log.
E/jxcore-log(16944): 
,I/jxcore-log(16944): getBuffer is called!!!!
I/jxcore-log(16944): 
,I/jxcore-log(16944): ****TEST TOOK:  5162  ms ****
I/jxcore-log(16944): 
,I/jxcore-log(16944): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(16944): 


samsung-SM-T232: 
--------- beginning of /dev/log/system
,--------- beginning of /dev/log/main
,W/jxcore-log(  515): Initializing JXcore engine
W/jxcore-log(  515): JXcore engine is ready
W/jxcore-log(  515): Starting JXcore engine
,W/jxcore-log(  515): Platform android
W/jxcore-log(  515): 
,W/jxcore-log(  515): Process ARCH arm
W/jxcore-log(  515): 
,I/jxcore-log(  515): JXcore Cordova bridge is ready!
I/jxcore-log(  515): 
,W/jxcore-log(  515): JXcore engine is started
,E/jxcore-log(  515): >> samsung-SM-T232
E/jxcore-log(  515): 
,I/jxcore-log(  515): Total memory 1352024064
I/jxcore-log(  515): 
,I/jxcore-log(  515): Free memory 96792576
I/jxcore-log(  515): 
,I/jxcore-log(  515): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(  515): 
,I/jxcore-log(  515): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(  515): 
,I/jxcore-log(  515): userPath [ 'www' ]
I/jxcore-log(  515): 
,I/jxcore-log(  515): Size 800 1280
I/jxcore-log(  515): 
,I/jxcore-log(  515): Screen Brightness 255
I/jxcore-log(  515): 
,E/jxcore-log(  515): Dummy Error Log.
E/jxcore-log(  515): 
,I/jxcore-log(  515): getBuffer is called!!!!
I/jxcore-log(  515): 
,I/jxcore-log(  515): ****TEST TOOK:  5112  ms ****
I/jxcore-log(  515): 
,I/jxcore-log(  515): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(  515): 


LGE-LG-H815: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(31533): Initializing JXcore engine
W/jxcore-log(31533): JXcore engine is ready
,W/jxcore-log(31533): Starting JXcore engine
,W/jxcore-log(31533): Platform android
W/jxcore-log(31533): 
W/jxcore-log(31533): Process ARCH arm
W/jxcore-log(31533): 
,I/jxcore-log(31533): JXcore Cordova bridge is ready!
I/jxcore-log(31533): 
,W/jxcore-log(31533): JXcore engine is started
,E/jxcore-log(31533): >> LGE-LG-H815
E/jxcore-log(31533): 
,I/jxcore-log(31533): Total memory 2968948736
I/jxcore-log(31533): 
,I/jxcore-log(31533): Free memory 425889792
I/jxcore-log(31533): 
I/jxcore-log(31533): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(31533): 
I/jxcore-log(31533): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(31533): 
,I/jxcore-log(31533): userPath [ 'www' ]
I/jxcore-log(31533): 
,I/jxcore-log(31533): Size 1440 2392
I/jxcore-log(31533): 
,I/jxcore-log(31533): Screen Brightness 255
I/jxcore-log(31533): 
,E/jxcore-log(31533): Dummy Error Log.
E/jxcore-log(31533): 
,I/jxcore-log(31533): getBuffer is called!!!!
I/jxcore-log(31533): 
,I/jxcore-log(31533): ****TEST TOOK:  5099  ms ****
I/jxcore-log(31533): 
I/jxcore-log(31533): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(31533): 


HUAWEI-ALE-L21: 
int logctl_get(): open '/dev/hwlog_switch' fail -1, 13. Permission denied

Note: log switch off, only log_main and log_events will have logs!
--------- beginning of main
,W/jxcore-log(31872): Initializing JXcore engine
W/jxcore-log(31872): JXcore engine is ready
,W/jxcore-log(31872): Starting JXcore engine
,W/jxcore-log(31872): Platform android
W/jxcore-log(31872): 
W/jxcore-log(31872): Process ARCH arm
W/jxcore-log(31872): 
,I/jxcore-log(31872): JXcore Cordova bridge is ready!
I/jxcore-log(31872): 
W/jxcore-log(31872): JXcore engine is started
,E/jxcore-log(31872): >> HUAWEI-ALE-L21
E/jxcore-log(31872): 
,I/jxcore-log(31872): Total memory 1949741056
I/jxcore-log(31872): 
,I/jxcore-log(31872): Free memory 76902400
I/jxcore-log(31872): 
I/jxcore-log(31872): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(31872): 
I/jxcore-log(31872): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(31872): 
,I/jxcore-log(31872): userPath [ 'www' ]
I/jxcore-log(31872): 
,I/jxcore-log(31872): Size 720 1184
I/jxcore-log(31872): 
,I/jxcore-log(31872): Screen Brightness 242
I/jxcore-log(31872): 
,E/jxcore-log(31872): Dummy Error Log.
E/jxcore-log(31872): 
,I/jxcore-log(31872): getBuffer is called!!!!
I/jxcore-log(31872): 
,I/jxcore-log(31872): ****TEST TOOK:  5111  ms ****
I/jxcore-log(31872): 
I/jxcore-log(31872): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(31872): 


```

####Node name: thali02
Console output:
```
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on LGD7228ee9cf5b 
Device test finished on 09a9416e0297d102 
Android task is completed 
```

Logcat output:
```
LGE-Nexus 5: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(21868): Initializing JXcore engine
W/jxcore-log(21868): JXcore engine is ready
,W/jxcore-log(21868): Starting JXcore engine
,W/jxcore-log(21868): Platform android
W/jxcore-log(21868): 
W/jxcore-log(21868): Process ARCH arm
W/jxcore-log(21868): 
,I/jxcore-log(21868): JXcore Cordova bridge is ready!
I/jxcore-log(21868): 
,W/jxcore-log(21868): JXcore engine is started
,E/jxcore-log(21868): >> LGE-Nexus 5
E/jxcore-log(21868): 
,I/jxcore-log(21868): Total memory 1946181632
I/jxcore-log(21868): 
,I/jxcore-log(21868): Free memory 329883648
I/jxcore-log(21868): 
I/jxcore-log(21868): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(21868): 
I/jxcore-log(21868): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(21868): 
,I/jxcore-log(21868): userPath [ 'www' ]
I/jxcore-log(21868): 
,I/jxcore-log(21868): Size 1080 1776
I/jxcore-log(21868): 
,I/jxcore-log(21868): Screen Brightness 82
I/jxcore-log(21868): 
,E/jxcore-log(21868): Dummy Error Log.
E/jxcore-log(21868): 
,I/jxcore-log(21868): getBuffer is called!!!!
I/jxcore-log(21868): 
,I/jxcore-log(21868): ****TEST TOOK:  5164  ms ****
I/jxcore-log(21868): 
,I/jxcore-log(21868): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(21868): 


LGE-LG-D722: 
--------- beginning of main
--------- beginning of system
,W/jxcore-log(19721): Initializing JXcore engine
W/jxcore-log(19721): JXcore engine is ready
,W/jxcore-log(19721): Starting JXcore engine
,W/jxcore-log(19721): Platform android
W/jxcore-log(19721): 
W/jxcore-log(19721): Process ARCH arm
W/jxcore-log(19721): 
I/jxcore-log(19721): JXcore Cordova bridge is ready!
I/jxcore-log(19721): 
W/jxcore-log(19721): JXcore engine is started
E/jxcore-log(19721): >> LGE-LG-D722
E/jxcore-log(19721): 
I/jxcore-log(19721): Total memory 906309632
I/jxcore-log(19721): 
I/jxcore-log(19721): Free memory 20226048
I/jxcore-log(19721): 
I/jxcore-log(19721): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(19721): 
I/jxcore-log(19721): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(19721): 
I/jxcore-log(19721): userPath [ 'www' ]
I/jxcore-log(19721): 
I/jxcore-log(19721): Size 720 1196
I/jxcore-log(19721): 
I/jxcore-log(19721): Screen Brightness 255
I/jxcore-log(19721): 
E/jxcore-log(19721): Dummy Error Log.
E/jxcore-log(19721): 
,I/jxcore-log(19721): getBuffer is called!!!!
I/jxcore-log(19721): 
,I/jxcore-log(19721): ****TEST TOOK:  5165  ms ****
I/jxcore-log(19721): 
,I/jxcore-log(19721): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(19721): 


```

####Node name: thali03
Console output:
```
STOP log received from  LGD8553bed2d08 Test has  SUCCEEDED
Device test finished on LGD8553bed2d08 
STOP log received from  320414cd475f91e3 Test has  SUCCEEDED
Device test finished on 320414cd475f91e3 
STOP log received from  TA4750HV7I Test has  SUCCEEDED
Device test finished on TA4750HV7I 
Android task is completed 
```

Logcat output:
```
motorola-XT1039: 
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
,W/jxcore-log(10489): Initializing JXcore engine
,W/jxcore-log(10489): JXcore engine is ready
,W/jxcore-log(10489): Starting JXcore engine
,W/jxcore-log(10489): Platform android
W/jxcore-log(10489): 
,W/jxcore-log(10489): Process ARCH arm
W/jxcore-log(10489): 
,I/jxcore-log(10489): JXcore Cordova bridge is ready!
I/jxcore-log(10489): 
,W/jxcore-log(10489): JXcore engine is started
,E/jxcore-log(10489): >> motorola-XT1039,
E/jxcore-log(10489): 
I/jxcore-log(10489): Total memory 893136896
I/jxcore-log(10489): 
I/jxcore-log(10489): Free memory 47218688
I/jxcore-log(10489): 
I/jxcore-log(10489): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(10489): 
,I/jxcore-log(10489): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(10489): 
,I/jxcore-log(10489): userPath [ 'www' ]
I/jxcore-log(10489): 
,I/jxcore-log(10489): Size 720 1184
I/jxcore-log(10489): 
,I/jxcore-log(10489): Screen Brightness 210
I/jxcore-log(10489): 
,E/jxcore-log(10489): Dummy Error Log.
E/jxcore-log(10489): 
,I/jxcore-log(10489): getBuffer is called!!!!
I/jxcore-log(10489): 
,I/jxcore-log(10489): ****TEST TOOK:  5148  ms ****
I/jxcore-log(10489): 
I/jxcore-log(10489): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(10489): 


LGE-LG-D855: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(13072): Initializing JXcore engine
W/jxcore-log(13072): JXcore engine is ready
W/jxcore-log(13072): Starting JXcore engine
W/jxcore-log(13072): Platform android
W/jxcore-log(13072): 
W/jxcore-log(13072): Process ARCH arm
W/jxcore-log(13072): 
I/jxcore-log(13072): JXcore Cordova bridge is ready!
I/jxcore-log(13072): 
W/jxcore-log(13072): JXcore engine is started
,E/jxcore-log(13072): >> LGE-LG-D855
E/jxcore-log(13072): 
,I/jxcore-log(13072): Total memory 2995761152
I/jxcore-log(13072): 
,I/jxcore-log(13072): Free memory 458186752
I/jxcore-log(13072): 
,I/jxcore-log(13072): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(13072): 
I/jxcore-log(13072): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(13072): 
I/jxcore-log(13072): userPath [ 'www' ]
I/jxcore-log(13072): 
,I/jxcore-log(13072): Size 1440 2392
I/jxcore-log(13072): 
,I/jxcore-log(13072): Screen Brightness 177
I/jxcore-log(13072): 
,E/jxcore-log(13072): Dummy Error Log.
E/jxcore-log(13072): 
,I/jxcore-log(13072): getBuffer is called!!!!
I/jxcore-log(13072): 
,I/jxcore-log(13072): ****TEST TOOK:  5249  ms ****
I/jxcore-log(13072): 
,I/jxcore-log(13072): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(13072): 


samsung-SM-G800F: 
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
,W/jxcore-log(  903): Initializing JXcore engine
,W/jxcore-log(  903): JXcore engine is ready
,W/jxcore-log(  903): Starting JXcore engine
,W/jxcore-log(  903): Platform android
W/jxcore-log(  903): 
,W/jxcore-log(  903): Process ARCH arm
W/jxcore-log(  903): 
,I/jxcore-log(  903): JXcore Cordova bridge is ready!
I/jxcore-log(  903): 
,W/jxcore-log(  903): JXcore engine is started
,E/jxcore-log(  903): >> samsung-SM-G800F
E/jxcore-log(  903): 
,I/jxcore-log(  903): Total memory 1319530496
I/jxcore-log(  903): 
,I/jxcore-log(  903): Free memory 35123200
I/jxcore-log(  903): 
I/jxcore-log(  903): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(  903): 
,I/jxcore-log(  903): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(  903): 
,I/jxcore-log(  903): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(  903): 
,I/jxcore-log(  903): Size 720 1280
I/jxcore-log(  903): 
,I/jxcore-log(  903): Screen Brightness 255
I/jxcore-log(  903): 
,E/jxcore-log(  903): Dummy Error Log.
E/jxcore-log(  903): 
,I/jxcore-log(  903): getBuffer is called!!!!
I/jxcore-log(  903): 
,I/jxcore-log(  903): ****TEST TOOK:  5228  ms ****
I/jxcore-log(  903): 
,I/jxcore-log(  903): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(  903): 


```

####Node name: thali04
Console output:
```
STOP log received from  0be0c6c6 Test has  SUCCEEDED
STOP log received from  ZX1C223JKW Test has  SUCCEEDED
STOP log received from  f56ad48d Test has  SUCCEEDED
Device test finished on 0be0c6c6 
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
Device test finished on f56ad48d 
Device test finished on ZX1C223JKW 
Device test finished on 41006f95c8139173 
Android task is completed 
```

Logcat output:
```
motorola-XT1072: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(27375): Initializing JXcore engine
,W/jxcore-log(27375): JXcore engine is ready
,W/jxcore-log(27375): Starting JXcore engine
,W/jxcore-log(27375): Platform android
W/jxcore-log(27375): 
W/jxcore-log(27375): Process ARCH arm
W/jxcore-log(27375): 
I/jxcore-log(27375): JXcore Cordova bridge is ready!
I/jxcore-log(27375): 
W/jxcore-log(27375): JXcore engine is started
E/jxcore-log(27375): >> motorola-XT1072
E/jxcore-log(27375): 
I/jxcore-log(27375): Total memory 916258816
I/jxcore-log(27375): 
I/jxcore-log(27375): Free memory 55431168
I/jxcore-log(27375): 
I/jxcore-log(27375): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(27375): 
I/jxcore-log(27375): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(27375): 
I/jxcore-log(27375): userPath [ 'www' ]
I/jxcore-log(27375): 
I/jxcore-log(27375): Size 720 1184
I/jxcore-log(27375): 
I/jxcore-log(27375): Screen Brightness 82
I/jxcore-log(27375): 
E/jxcore-log(27375): Dummy Error Log.
E/jxcore-log(27375): 
,I/jxcore-log(27375): getBuffer is called!!!!
I/jxcore-log(27375): 
,I/jxcore-log(27375): ****TEST TOOK:  5278  ms ****
I/jxcore-log(27375): 
I/jxcore-log(27375): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(27375): 


samsung-SM-N910C: 
--------- beginning of system
,--------- beginning of main
,W/jxcore-log(18324): Initializing JXcore engine
W/jxcore-log(18324): JXcore engine is ready
,W/jxcore-log(18324): Starting JXcore engine
,W/jxcore-log(18324): Platform android
W/jxcore-log(18324): 
W/jxcore-log(18324): Process ARCH arm
W/jxcore-log(18324): 
,I/jxcore-log(18324): JXcore Cordova bridge is ready!
I/jxcore-log(18324): 
W/jxcore-log(18324): JXcore engine is started
,E/jxcore-log(18324): >> samsung-SM-N910C
E/jxcore-log(18324): 
,I/jxcore-log(18324): Total memory 2971066368
I/jxcore-log(18324): 
I/jxcore-log(18324): Free memory 269586432
I/jxcore-log(18324): 
I/jxcore-log(18324): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(18324): 
I/jxcore-log(18324): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(18324): 
,I/jxcore-log(18324): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(18324): 
,I/jxcore-log(18324): Size 1440 2560
I/jxcore-log(18324): 
,I/jxcore-log(18324): Screen Brightness 134
I/jxcore-log(18324): 
E/jxcore-log(18324): Dummy Error Log.
E/jxcore-log(18324): 
,I/jxcore-log(18324): getBuffer is called!!!!
I/jxcore-log(18324): 
,I/jxcore-log(18324): ****TEST TOOK:  5170  ms ****
I/jxcore-log(18324): 
,I/jxcore-log(18324): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(18324): 


samsung-SM-A500FU: 
--------- beginning of system
,--------- beginning of main
,W/jxcore-log(13827): Initializing JXcore engine
W/jxcore-log(13827): JXcore engine is ready
W/jxcore-log(13827): Starting JXcore engine
W/jxcore-log(13827): Platform android
W/jxcore-log(13827): 
W/jxcore-log(13827): Process ARCH arm
W/jxcore-log(13827): 
I/jxcore-log(13827): JXcore Cordova bridge is ready!
I/jxcore-log(13827): 
W/jxcore-log(13827): JXcore engine is started
E/jxcore-log(13827): >> samsung-SM-A500FU
E/jxcore-log(13827): 
I/jxcore-log(13827): Total memory 1983787008
I/jxcore-log(13827): 
I/jxcore-log(13827): Free memory 355524608
I/jxcore-log(13827): 
I/jxcore-log(13827): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(13827): 
I/jxcore-log(13827): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(13827): 
I/jxcore-log(13827): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(13827): 
I/jxcore-log(13827): Size 720 1280
I/jxcore-log(13827): 
I/jxcore-log(13827): Screen Brightness 255
I/jxcore-log(13827): 
E/jxcore-log(13827): Dummy Error Log.
E/jxcore-log(13827): 
,I/jxcore-log(13827): getBuffer is called!!!!
I/jxcore-log(13827): 
,I/jxcore-log(13827): ****TEST TOOK:  5079  ms ****
I/jxcore-log(13827): 
,I/jxcore-log(13827): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(13827): 


samsung-SM-G900F: 
--------- beginning of main
--------- beginning of system
,W/jxcore-log(13106): Initializing JXcore engine
W/jxcore-log(13106): JXcore engine is ready
W/jxcore-log(13106): Starting JXcore engine
W/jxcore-log(13106): Platform android
W/jxcore-log(13106): 
W/jxcore-log(13106): Process ARCH arm
W/jxcore-log(13106): 
I/jxcore-log(13106): JXcore Cordova bridge is ready!
I/jxcore-log(13106): 
W/jxcore-log(13106): JXcore engine is started
E/jxcore-log(13106): >> samsung-SM-G900F
E/jxcore-log(13106): 
I/jxcore-log(13106): Total memory 1787449344
I/jxcore-log(13106): 
I/jxcore-log(13106): Free memory 43761664
I/jxcore-log(13106): 
I/jxcore-log(13106): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(13106): 
I/jxcore-log(13106): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(13106): 
I/jxcore-log(13106): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(13106): 
I/jxcore-log(13106): Size 1080 1920
I/jxcore-log(13106): 
I/jxcore-log(13106): Screen Brightness 255
I/jxcore-log(13106): 
E/jxcore-log(13106): Dummy Error Log.
E/jxcore-log(13106): 
,I/jxcore-log(13106): getBuffer is called!!!!
I/jxcore-log(13106): 
,I/jxcore-log(13106): ****TEST TOOK:  5243  ms ****
I/jxcore-log(13106): 
I/jxcore-log(13106): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(13106): 


```

####Node name: thali05
Console output:
```
STOP log received from  ZX1G429CRK Test has  SUCCEEDED
STOP log received from  1d6a772d Test has  SUCCEEDED
Device test finished on ZX1G429CRK 
Device test finished on 1d6a772d 
STOP log received from  SH47FWM00508 Test has  SUCCEEDED
Device test finished on SH47FWM00508 
Android task is completed 
```

Logcat output:
```
HTC-HTC One_M8: 
--------- beginning of system,
--------- beginning of main
,W/jxcore-log(21029): Initializing JXcore engine
W/jxcore-log(21029): JXcore engine is ready
,W/jxcore-log(21029): Starting JXcore engine,
,W/jxcore-log(21029): Platform android,
W/jxcore-log(21029): 
W/jxcore-log(21029): Process ARCH arm
W/jxcore-log(21029): 
,I/jxcore-log(21029): JXcore Cordova bridge is ready!,
I/jxcore-log(21029): 
W/jxcore-log(21029): JXcore engine is started
,E/jxcore-log(21029): >> HTC-HTC One_M8,
E/jxcore-log(21029): 
,I/jxcore-log(21029): Total memory 1912020992,
I/jxcore-log(21029): 
I/jxcore-log(21029): Free memory 379236352
I/jxcore-log(21029): 
I/jxcore-log(21029): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(21029): 
I/jxcore-log(21029): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(21029): 
,I/jxcore-log(21029): userPath [ 'www' ],
I/jxcore-log(21029): 
,I/jxcore-log(21029): Size 1080 1776
I/jxcore-log(21029): 
,I/jxcore-log(21029): Screen Brightness 142,
I/jxcore-log(21029): 
E/jxcore-log(21029): Dummy Error Log.
E/jxcore-log(21029): 
,I/jxcore-log(21029): getBuffer is called!!!!,
I/jxcore-log(21029): 
,I/jxcore-log(21029): ****TEST TOOK:  5204  ms ****
I/jxcore-log(21029): 
I/jxcore-log(21029): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(21029): 


samsung-SM-N9005: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(30253): Initializing JXcore engine
W/jxcore-log(30253): JXcore engine is ready
,W/jxcore-log(30253): Starting JXcore engine
,W/jxcore-log(30253): Platform android
W/jxcore-log(30253): 
W/jxcore-log(30253): Process ARCH arm
W/jxcore-log(30253): 
,I/jxcore-log(30253): JXcore Cordova bridge is ready!
I/jxcore-log(30253): 
,W/jxcore-log(30253): JXcore engine is started
,E/jxcore-log(30253): >> samsung-SM-N9005
E/jxcore-log(30253): 
,I/jxcore-log(30253): Total memory 2971471872
I/jxcore-log(30253): 
,I/jxcore-log(30253): Free memory 325976064
I/jxcore-log(30253): 
I/jxcore-log(30253): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(30253): 
I/jxcore-log(30253): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(30253): 
,I/jxcore-log(30253): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(30253): 
,I/jxcore-log(30253): Size 1080 1920
I/jxcore-log(30253): 
,I/jxcore-log(30253): Screen Brightness 255
I/jxcore-log(30253): 
,E/jxcore-log(30253): Dummy Error Log.
E/jxcore-log(30253): 
,I/jxcore-log(30253): getBuffer is called!!!!
I/jxcore-log(30253): 
,I/jxcore-log(30253): ****TEST TOOK:  5175  ms ****
I/jxcore-log(30253): 
,I/jxcore-log(30253): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(30253): 


motorola-Nexus 6: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(10844): Initializing JXcore engine
W/jxcore-log(10844): JXcore engine is ready
W/jxcore-log(10844): Starting JXcore engine
W/jxcore-log(10844): Platform android
W/jxcore-log(10844): 
W/jxcore-log(10844): Process ARCH arm
W/jxcore-log(10844): 
I/jxcore-log(10844): JXcore Cordova bridge is ready!
I/jxcore-log(10844): 
W/jxcore-log(10844): JXcore engine is started
E/jxcore-log(10844): >> motorola-Nexus 6
E/jxcore-log(10844): 
I/jxcore-log(10844): Total memory 3114405888
I/jxcore-log(10844): 
I/jxcore-log(10844): Free memory 557301760
I/jxcore-log(10844): 
I/jxcore-log(10844): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(10844): 
I/jxcore-log(10844): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(10844): 
I/jxcore-log(10844): userPath [ 'www' ]
I/jxcore-log(10844): 
I/jxcore-log(10844): Size 1440 2392
I/jxcore-log(10844): 
I/jxcore-log(10844): Screen Brightness 82
I/jxcore-log(10844): 
E/jxcore-log(10844): Dummy Error Log.
E/jxcore-log(10844): 
,I/jxcore-log(10844): getBuffer is called!!!!
I/jxcore-log(10844): 
,I/jxcore-log(10844): ****TEST TOOK:  5100  ms ****
I/jxcore-log(10844): 
I/jxcore-log(10844): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(10844): 


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
--------- beginning of main
,--------- beginning of system
,W/jxcore-log( 3575): Initializing JXcore engine,
W/jxcore-log( 3575): JXcore engine is ready
,W/jxcore-log( 3575): Starting JXcore engine
,W/jxcore-log( 3575): Platform android
W/jxcore-log( 3575): 
,W/jxcore-log( 3575): Process ARCH arm
W/jxcore-log( 3575): 
,I/jxcore-log( 3575): JXcore Cordova bridge is ready!,
I/jxcore-log( 3575): 
W/jxcore-log( 3575): JXcore engine is started
,E/jxcore-log( 3575): >> HTC-HTC One M8s,
E/jxcore-log( 3575): 
,I/jxcore-log( 3575): Total memory 1931808768,
I/jxcore-log( 3575): 
I/jxcore-log( 3575): Free memory 293347328
I/jxcore-log( 3575): 
I/jxcore-log( 3575): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3575): 
,I/jxcore-log( 3575): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3575): 
,I/jxcore-log( 3575): userPath [ 'www' ],
I/jxcore-log( 3575): 
,I/jxcore-log( 3575): Size 1080 1776
I/jxcore-log( 3575): 
,I/jxcore-log( 3575): Screen Brightness 142,
I/jxcore-log( 3575): 
E/jxcore-log( 3575): Dummy Error Log.
E/jxcore-log( 3575): 
,I/jxcore-log( 3575): getBuffer is called!!!!,
I/jxcore-log( 3575): 
,I/jxcore-log( 3575): ****TEST TOOK:  5090  ms ****,
I/jxcore-log( 3575): 
I/jxcore-log( 3575): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3575): 


samsung-SM-A300FU: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(17777): Initializing JXcore engine
,W/jxcore-log(17777): JXcore engine is ready
,W/jxcore-log(17777): Starting JXcore engine
,W/jxcore-log(17777): Platform android
W/jxcore-log(17777): 
W/jxcore-log(17777): Process ARCH arm
W/jxcore-log(17777): 
,I/jxcore-log(17777): JXcore Cordova bridge is ready!
I/jxcore-log(17777): 
,W/jxcore-log(17777): JXcore engine is started
,E/jxcore-log(17777): >> samsung-SM-A300FU
E/jxcore-log(17777): 
,I/jxcore-log(17777): Total memory 1451114496
I/jxcore-log(17777): 
,I/jxcore-log(17777): Free memory 157220864
I/jxcore-log(17777): 
,I/jxcore-log(17777): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(17777): 
I/jxcore-log(17777): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(17777): 
,I/jxcore-log(17777): userPath [ 'www' ]
I/jxcore-log(17777): 
,I/jxcore-log(17777): Size 540 960
I/jxcore-log(17777): 
,I/jxcore-log(17777): Screen Brightness 160
I/jxcore-log(17777): 
,E/jxcore-log(17777): Dummy Error Log.
E/jxcore-log(17777): 
,I/jxcore-log(17777): getBuffer is called!!!!
I/jxcore-log(17777): 
,I/jxcore-log(17777): ****TEST TOOK:  5080  ms ****
I/jxcore-log(17777): 
,I/jxcore-log(17777): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(17777): 


LGE-LG-D802: 
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
,W/jxcore-log( 9836): Initializing JXcore engine
,W/jxcore-log( 9836): JXcore engine is ready
,W/jxcore-log( 9836): Starting JXcore engine
,W/jxcore-log( 9836): Platform android
W/jxcore-log( 9836): 
,W/jxcore-log( 9836): Process ARCH arm
W/jxcore-log( 9836): 
,I/jxcore-log( 9836): JXcore Cordova bridge is ready!
I/jxcore-log( 9836): 
W/jxcore-log( 9836): JXcore engine is started
E/jxcore-log( 9836): >> LGE-LG-D802
E/jxcore-log( 9836): 
I/jxcore-log( 9836): Total memory 1943035904
I/jxcore-log( 9836): 
I/jxcore-log( 9836): Free memory 249233408
I/jxcore-log( 9836): 
I/jxcore-log( 9836): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 9836): 
I/jxcore-log( 9836): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 9836): 
I/jxcore-log( 9836): userPath [ 'www' ]
I/jxcore-log( 9836): 
I/jxcore-log( 9836): Size 1080 1776
I/jxcore-log( 9836): 
I/jxcore-log( 9836): Screen Brightness 255
I/jxcore-log( 9836): 
E/jxcore-log( 9836): Dummy Error Log.
E/jxcore-log( 9836): 
I/jxcore-log( 9836): getBuffer is called!!!!
I/jxcore-log( 9836): 
,I/jxcore-log( 9836): ****TEST TOOK:  5223  ms ****
I/jxcore-log( 9836): 
,I/jxcore-log( 9836): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 9836): 


```

####Node name: thali07
Console output:
```
STOP log received from  4db5c8cc Test has  SUCCEEDED
STOP log received from  c5afcdcb Test has  SUCCEEDED
Device test finished on 4db5c8cc 
Device test finished on c5afcdcb 
Android task is completed 
```

Logcat output:
```
samsung-SM-A500FU: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log( 2921): Initializing JXcore engine
W/jxcore-log( 2921): JXcore engine is ready
W/jxcore-log( 2921): Starting JXcore engine
,W/jxcore-log( 2921): Platform android
W/jxcore-log( 2921): 
W/jxcore-log( 2921): Process ARCH arm
W/jxcore-log( 2921): 
,I/jxcore-log( 2921): JXcore Cordova bridge is ready!
I/jxcore-log( 2921): 
,W/jxcore-log( 2921): JXcore engine is started
,E/jxcore-log( 2921): >> samsung-SM-A500FU
E/jxcore-log( 2921): 
,I/jxcore-log( 2921): Total memory 1983787008
I/jxcore-log( 2921): 
,I/jxcore-log( 2921): Free memory 373309440
I/jxcore-log( 2921): 
I/jxcore-log( 2921): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2921): 
I/jxcore-log( 2921): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2921): 
,I/jxcore-log( 2921): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 2921): 
,I/jxcore-log( 2921): Size 720 1280
I/jxcore-log( 2921): 
,I/jxcore-log( 2921): Screen Brightness 255
I/jxcore-log( 2921): 
,E/jxcore-log( 2921): Dummy Error Log.
E/jxcore-log( 2921): 
,I/jxcore-log( 2921): getBuffer is called!!!!
I/jxcore-log( 2921): 
,I/jxcore-log( 2921): ****TEST TOOK:  5075  ms ****
I/jxcore-log( 2921): 
,I/jxcore-log( 2921): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2921): 


samsung-SM-G900F: 
--------- beginning of main
--------- beginning of system
,W/jxcore-log( 4209): Initializing JXcore engine
,W/jxcore-log( 4209): JXcore engine is ready
,W/jxcore-log( 4209): Starting JXcore engine
,W/jxcore-log( 4209): Platform android
W/jxcore-log( 4209): 
W/jxcore-log( 4209): Process ARCH arm
W/jxcore-log( 4209): 
,I/jxcore-log( 4209): JXcore Cordova bridge is ready!
I/jxcore-log( 4209): 
,W/jxcore-log( 4209): JXcore engine is started
,E/jxcore-log( 4209): >> samsung-SM-G900F
E/jxcore-log( 4209): 
,I/jxcore-log( 4209): Total memory 1787449344
I/jxcore-log( 4209): 
,I/jxcore-log( 4209): Free memory 80814080
I/jxcore-log( 4209): 
I/jxcore-log( 4209): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4209): 
I/jxcore-log( 4209): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4209): 
,I/jxcore-log( 4209): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 4209): 
,I/jxcore-log( 4209): Size 1080 1920
I/jxcore-log( 4209): 
,I/jxcore-log( 4209): Screen Brightness 134
I/jxcore-log( 4209): 
E/jxcore-log( 4209): Dummy Error Log.
E/jxcore-log( 4209): 
,I/jxcore-log( 4209): getBuffer is called!!!!,
I/jxcore-log( 4209): 
,I/jxcore-log( 4209): ****TEST TOOK:  5185  ms ****
I/jxcore-log( 4209): 
,I/jxcore-log( 4209): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4209): 


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
,W/jxcore-log( 8614): Initializing JXcore engine
W/jxcore-log( 8614): JXcore engine is ready
,W/jxcore-log( 8614): Starting JXcore engine
,W/jxcore-log( 8614): Platform android
W/jxcore-log( 8614): 
,W/jxcore-log( 8614): Process ARCH arm
W/jxcore-log( 8614): 
,I/jxcore-log( 8614): JXcore Cordova bridge is ready!
I/jxcore-log( 8614): 
,W/jxcore-log( 8614): JXcore engine is started
,E/jxcore-log( 8614): >> samsung-SM-A300FU
E/jxcore-log( 8614): 
,I/jxcore-log( 8614): Total memory 1451114496
I/jxcore-log( 8614): 
,I/jxcore-log( 8614): Free memory 210305024
I/jxcore-log( 8614): 
,I/jxcore-log( 8614): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 8614): 
I/jxcore-log( 8614): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 8614): 
,I/jxcore-log( 8614): userPath [ 'www' ]
I/jxcore-log( 8614): 
,I/jxcore-log( 8614): Size 540 960
I/jxcore-log( 8614): 
,I/jxcore-log( 8614): Screen Brightness 255
I/jxcore-log( 8614): 
,E/jxcore-log( 8614): Dummy Error Log.
E/jxcore-log( 8614): 
,I/jxcore-log( 8614): getBuffer is called!!!!
I/jxcore-log( 8614): 
,I/jxcore-log( 8614): ****TEST TOOK:  5065  ms ****
I/jxcore-log( 8614): 
I/jxcore-log( 8614): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 8614): 


HTC-HTC Desire 820: 
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
,W/jxcore-log(17507): Initializing JXcore engine
W/jxcore-log(17507): JXcore engine is ready
W/jxcore-log(17507): Starting JXcore engine
W/jxcore-log(17507): Platform android
W/jxcore-log(17507): 
W/jxcore-log(17507): Process ARCH arm
W/jxcore-log(17507): 
I/jxcore-log(17507): JXcore Cordova bridge is ready!
I/jxcore-log(17507): 
W/jxcore-log(17507): JXcore engine is started
E/jxcore-log(17507): >> HTC-HTC Desire 820
E/jxcore-log(17507): 
I/jxcore-log(17507): Total memory 1964650496
I/jxcore-log(17507): 
I/jxcore-log(17507): Free memory 223133696
I/jxcore-log(17507): 
I/jxcore-log(17507): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(17507): 
I/jxcore-log(17507): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(17507): 
I/jxcore-log(17507): userPath [ 'www' ]
I/jxcore-log(17507): 
I/jxcore-log(17507): Size 720 1184
I/jxcore-log(17507): 
I/jxcore-log(17507): Screen Brightness 10
I/jxcore-log(17507): 
E/jxcore-log(17507): Dummy Error Log.
E/jxcore-log(17507): 
,I/jxcore-log(17507): getBuffer is called!!!!
I/jxcore-log(17507): 
,I/jxcore-log(17507): ****TEST TOOK:  5185  ms ****
I/jxcore-log(17507): 
,I/jxcore-log(17507): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(17507): 


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
,TIME-OUT KILL (timeout was 150000ms)

HTC-HTC Desire 820: 
--------- beginning of /dev/log/main
--------- beginning of /dev/log/system
,W/jxcore-log(15514): Initializing JXcore engine
,W/jxcore-log(15514): JXcore engine is ready
,W/jxcore-log(15514): Starting JXcore engine
,W/jxcore-log(15514): Platform android
W/jxcore-log(15514): 
,W/jxcore-log(15514): Process ARCH arm
W/jxcore-log(15514): 
,I/jxcore-log(15514): JXcore Cordova bridge is ready!
I/jxcore-log(15514): 
,W/jxcore-log(15514): JXcore engine is started
,E/jxcore-log(15514): >> HTC-HTC Desire 820
E/jxcore-log(15514): 
,I/jxcore-log(15514): Total memory 1964650496
I/jxcore-log(15514): 
I/jxcore-log(15514): Free memory 252710912
I/jxcore-log(15514): 
I/jxcore-log(15514): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(15514): 
,I/jxcore-log(15514): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(15514): 
,I/jxcore-log(15514): userPath [ 'www' ]
I/jxcore-log(15514): 
,I/jxcore-log(15514): Size 720 1184
I/jxcore-log(15514): 
,I/jxcore-log(15514): Screen Brightness 142
I/jxcore-log(15514): 
,E/jxcore-log(15514): Dummy Error Log.
E/jxcore-log(15514): 
,I/jxcore-log(15514): getBuffer is called!!!!
I/jxcore-log(15514): 
,I/jxcore-log(15514): ****TEST TOOK:  5167  ms ****
I/jxcore-log(15514): 
,I/jxcore-log(15514): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(15514): 


```




###iOS Logs

```
Iphone5s-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/4767223456c0496/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/7E4509B5-7895-4B4F-A06C-53D9D73ACEC2/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/7E4509B5-7895-4B4F-A06C-53D9D73ACEC2/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/4767223456c0496/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/4767223456c0496/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/778363E3-E1EC-4AB2-908F-12AFFA4FFECB/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55316"
,(lldb)     command script import "/tmp/7E4509B5-7895-4B4F-A06C-53D9D73ACEC2/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-10-23 23:24:51.225 HelloWorld[372:176175] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A4178A53-4F92-4755-A8A3-B11362E021FD/Library/Cookies/Cookies.binarycookies
,2015-10-23 23:24:51.601 HelloWorld[372:176175] Apache Cordova native platform version 3.9.1 is starting.
,2015-10-23 23:24:51.602 HelloWorld[372:176175] Multi-tasking -> Device: YES, App: YES
,2015-10-23 23:24:51.606 HelloWorld[372:176175] Unlimited access to network resources
,2015-10-23 23:24:51.612 HelloWorld[372:176175] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-10-23 23:24:55.422 HelloWorld[372:176175] Resetting plugins due to page load.
,2015-10-23 23:24:55.794 HelloWorld[372:176175] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/778363E3-E1EC-4AB2-908F-12AFFA4FFECB/HelloWorld.app/www/index.html
,2015-10-23 23:24:55.854 HelloWorld[372:176175] JXcore Cordova plugin initializing
2015-10-23 23:24:55.854 HelloWorld[372:176301] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone5s-1
Total memory 1047695360
Free memory 169795584
execPath /private/var/mobile/Containers/Bundle/Application/778363E3-E1EC-4AB2-908F-12AFFA4FFECB/HelloWorld.app/HelloWorld
process.cwd /private/var/mobile/Containers/Bundle/Application/77,8363E3-E1EC-4AB2-908F-12AFFA4FFECB/HelloWorld.app/www/jxcore/
,userPath []
2015-10-23 23:24:56.087 HelloWorld[372:176301] Native method ScreenInfo not found.
2015-10-23 23:24:56.088 HelloWorld[372:176301] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5113  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****



Iphone5-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/4767223456c0496/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 90%] Mounting developer disk image
,[ 95%] Developer disk image already mounted
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/4C7519CD-D125-4ED9-85E0-223FFAD0CF56/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/4C7519CD-D125-4ED9-85E0-223FFAD0CF56/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/4767223456c0496/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/4767223456c0496/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Applications/49A5FED0-D708-4009-B559-EE51BAD945BB/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55320"
,(lldb)     command script import "/tmp/4C7519CD-D125-4ED9-85E0-223FFAD0CF56/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-10-23 23:25:36.953 HelloWorld[737:60b] Apache Cordova native platform version 3.9.1 is starting.
2015-10-23 23:25:36.957 HelloWorld[737:60b] Multi-tasking -> Device: YES, App: YES
,2015-10-23 23:25:36.963 HelloWorld[737:60b] Unlimited access to network resources
,2015-10-23 23:25:36.973 HelloWorld[737:60b] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.app,le.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-10-23 23:25:47.830 HelloWorld[737:60b] Resetting plugins due to page load.
,2015-10-23 23:25:48.677 HelloWorld[737:60b] Finished load of: file:///var/mobile/Applications/49A5FED0-D708-4009-B559-EE51BAD945BB/HelloWorld.app/www/index.html
,2015-10-23 23:25:48.746 HelloWorld[737:60b] JXcore Cordova plugin initializing
,2015-10-23 23:25:48.749 HelloWorld[737:6707] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone5-1
Total memory 1065000960
Free memory 525070336
execPath /private/var/mobile/Applications/49A5FED0-D708-4009-B559-EE51BAD945BB/HelloWorld.app/HelloWorld
process.cwd /var/mobile/Applications/49A5FED0-D708-4009-B559-EE51BAD945BB/HelloWorld.app/www/jxcore/
userPath []
,2015-10-23 23:25:49.219 HelloWorld[737:6707] Native method ScreenInfo not found.
,2015-10-23 23:25:49.221 HelloWorld[737:6707] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5251  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****



Iphone6-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/4767223456c0496/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/CABE88FA-AC4E-4ECB-BF1F-6B11020DA8B3/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/CABE88FA-AC4E-4ECB-BF1F-6B11020DA8B3/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/4767223456c0496/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/4767223456c0496/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/EA13E779-0858-4139-9F99-046CE79A7982/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55315"
,(lldb)     command script import "/tmp/CABE88FA-AC4E-4ECB-BF1F-6B11020DA8B3/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-10-23 23:24:51.670 HelloWorld[1338:1134451] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2D997A56-F199-4BC3-8624-A857B35D2E33/Library/Cookies/Cookies.binarycookies
,2015-10-23 23:24:52.048 HelloWorld[1338:1134451] Apache Cordova native platform version 3.9.1 is starting.
2015-10-23 23:24:52.049 HelloWorld[1338:1134451] Multi-tasking -> Device: YES, App: YES
,2015-10-23 23:24:52.051 HelloWorld[1338:1134451] Unlimited access to network resources
,2015-10-23 23:24:52.056 HelloWorld[1338:1134451] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-10-23 23:24:55.547 HelloWorld[1338:1134451] Resetting plugins due to page load.
,2015-10-23 23:24:55.865 HelloWorld[1338:1134451] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/EA13E779-0858-4139-9F99-046CE79A7982/HelloWorld.app/www/index.html
,2015-10-23 23:24:55.965 HelloWorld[1338:1134451] JXcore Cordova plugin initializing
2015-10-23 23:24:55.970 HelloWorld[1338:1134559] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone6-1
Total memory 1035988992
Free memory 124792832
execPath /private/var/mobile/Containers/Bundle/Application/EA13E779-0858-4139-9F99-046CE79A7982/HelloWorld.app/HelloWorld
process.cwd /private/var/mobile/Containers/Bundle/Application/EA13E779-0858-4139-9F99-046CE79A7982/HelloWorld.app/www/jxcore/
userPath []
2015-10-23 23:24:56.221 HelloWorld[1338:1134559] Native method ScreenInfo not found.
2015-10-23 23:24:56.221 HelloWorld[1338:1134559] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5111  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****



IpadAir2-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/4767223456c0496/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/7F6F778E-3C9B-4CBE-8C09-B0967595165F/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/7F6F778E-3C9B-4CBE-8C09-B0967595165F/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/4767223456c0496/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/4767223456c0496/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/7DA6999E-8A26-4DE4-95DC-0E57DAE8EFAB/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55314"
,(lldb)     command script import "/tmp/7F6F778E-3C9B-4CBE-8C09-B0967595165F/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-10-23 23:24:56.003 HelloWorld[945:1436837] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/FAC038B1-E0DD-4C09-84FC-5038B3FDD007/Library/Cookies/Cookies.binarycookies
,2015-10-23 23:24:56.386 HelloWorld[945:1436837] Apache Cordova native platform version 3.9.1 is starting.
,2015-10-23 23:24:56.387 HelloWorld[945:1436837] Multi-tasking -> Device: YES, App: YES
,2015-10-23 23:24:56.395 HelloWorld[945:1436837] Unlimited access to network resources
,2015-10-23 23:24:56.402 HelloWorld[945:1436837] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-10-23 23:25:05.264 HelloWorld[945:1436837] Resetting plugins due to page load.
,2015-10-23 23:25:08.765 HelloWorld[945:1436837] Finished load of: file:///var/mobile/Containers/Bundle/Application/7DA6999E-8A26-4DE4-95DC-0E57DAE8EFAB/HelloWorld.app/www/index.html
,2015-10-23 23:25:08.860 HelloWorld[945:1436837] JXcore Cordova plugin initializing
,2015-10-23 23:25:08.861 HelloWorld[945:1437047] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-IpadAir2-1
,Total memory 2084569088
,Free memory 346750976
,execPath /private/var/mobile/Containers/Bundle/Application/7DA6999E-8A26-4DE4-95DC-0E57DAE8EFAB/HelloWorld.app/HelloWorld
,process.cwd /var/mobile/Containers/Bundle/Application/7DA6999E-8A26-4DE4-95DC-0E57DAE8EFAB/HelloWorld.app/www/jxcore/
,userPath []
,2015-10-23 23:25:09.065 HelloWorld[945:1437047] Native method ScreenInfo not found.
2015-10-23 23:25:09.066 HelloWorld[945:1437047] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5115  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****



```

#### Integration Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":25}}
Integration server has received  [ 'jx',
  '/home/pi/Test/server_4767223456c0496/Sub/serverApp/index.js',
  '{"devices":{"ios":4,"android":25}}' ]

JSON { devices: { ios: 4, android: 25 } }


```

