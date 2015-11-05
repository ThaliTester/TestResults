#### Test 49526184a3a5cb3 Logs

Status: 
```

server : IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":20,"cancel":1}}
Integration server has received  [ 'jx',
  '/home/pi/Test/server_49526184a3a5cb3/Sub/serverApp/index.js',
  '{"devices":{"android":20,"cancel":1}}' ]

JSON { devices: { android: 20, cancel: 1 } }



android : Error: Command failed: Error: Command failed: run_.sh aborted
 [0m


```
###Android Logs
####Node name: thali01
Console output:
```
STOP log received from  03157df360a1882a Test has  SUCCEEDED
STOP log received from  30049d9501da2100 Test has  SUCCEEDED
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
Device test finished on 30049d9501da2100 
Device test finished on LGH8153b36be34 
STOP log received from  W3D7N15428022572 Test has  SUCCEEDED
Device test finished on W3D7N15428022572 
Device test finished on 03157df360a1882a 
Android task is completed 
Error: problem stopping Android apk(com.example.hello) to device 30049d9501da2100 error: device not found
 
Error: problem stopping Android apk(com.example.hello) to device 03157df360a1882a error: device not found
 
Error: problem stopping Android apk(com.example.hello) to device LGH8153b36be34 error: device not found
 
Error: problem stopping Android apk(com.example.hello) to device W3D7N15428022572 error: device not found
 
```

Logcat output:
```
samsung-SM-T232: 
--------- beginning of /dev/log/system
--------- beginning of /dev/log/main
,W/jxcore-log( 5536): Initializing JXcore engine
W/jxcore-log( 5536): JXcore engine is ready
W/jxcore-log( 5536): Starting JXcore engine
W/jxcore-log( 5536): Platform android
W/jxcore-log( 5536): 
W/jxcore-log( 5536): Process ARCH arm
W/jxcore-log( 5536): 
I/jxcore-log( 5536): JXcore Cordova bridge is ready!
I/jxcore-log( 5536): 
W/jxcore-log( 5536): JXcore engine is started
E/jxcore-log( 5536): >> samsung-SM-T232
E/jxcore-log( 5536): 
I/jxcore-log( 5536): Total memory 1352024064
I/jxcore-log( 5536): 
I/jxcore-log( 5536): Free memory 142618624
I/jxcore-log( 5536): 
I/jxcore-log( 5536): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5536): 
I/jxcore-log( 5536): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5536): 
I/jxcore-log( 5536): userPath [ 'www' ]
I/jxcore-log( 5536): 
I/jxcore-log( 5536): Size 800 1280
I/jxcore-log( 5536): 
I/jxcore-log( 5536): Screen Brightness 255
I/jxcore-log( 5536): 
E/jxcore-log( 5536): Dummy Error Log.
E/jxcore-log( 5536): 
I/jxcore-log( 5536): getBuffer is called!!!!
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): Bluetooth turned on
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): WiFi turned off
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): WiFi turned on
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): No internet connection
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): No internet connection
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): No internet connection
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): No internet connection
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): No internet connection
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): No internet connection
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): WiFi
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): Response status code was: 200
I/jxcore-log( 5536): 
I/jxcore-log( 5536): ****TEST TOOK:  12387  ms ****
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5536): 


samsung-SM-G920F: 
--------- beginning of main
--------- beginning of system
,W/jxcore-log(10737): Initializing JXcore engine
W/jxcore-log(10737): JXcore engine is ready
W/jxcore-log(10737): Starting JXcore engine
,W/jxcore-log(10737): Platform android
W/jxcore-log(10737): 
W/jxcore-log(10737): Process ARCH arm
W/jxcore-log(10737): 
,I/jxcore-log(10737): JXcore Cordova bridge is ready!
I/jxcore-log(10737): 
W/jxcore-log(10737): JXcore engine is started
,E/jxcore-log(10737): >> samsung-SM-G920F
E/jxcore-log(10737): 
,I/jxcore-log(10737): Total memory 2829074432
I/jxcore-log(10737): 
I/jxcore-log(10737): Free memory 49434624
I/jxcore-log(10737): 
I/jxcore-log(10737): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(10737): 
I/jxcore-log(10737): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(10737): 
,I/jxcore-log(10737): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(10737): 
,I/jxcore-log(10737): Size 1440 2560
I/jxcore-log(10737): 
,I/jxcore-log(10737): Screen Brightness 134
I/jxcore-log(10737): 
E/jxcore-log(10737): Dummy Error Log.
E/jxcore-log(10737): 
,I/jxcore-log(10737): getBuffer is called!!!!
I/jxcore-log(10737): 
,I/jxcore-log(10737): Bluetooth turned on
I/jxcore-log(10737): 
,I/jxcore-log(10737): WiFi turned off
I/jxcore-log(10737): 
,I/jxcore-log(10737): WiFi turned on
I/jxcore-log(10737): 
,I/jxcore-log(10737): No internet connection
I/jxcore-log(10737): 
,I/jxcore-log(10737): No internet connection
I/jxcore-log(10737): 
,I/jxcore-log(10737): No internet connection
I/jxcore-log(10737): 
,I/jxcore-log(10737): No internet connection
I/jxcore-log(10737): 
,I/jxcore-log(10737): WiFi
I/jxcore-log(10737): 
,I/jxcore-log(10737): Response status code was: 200
I/jxcore-log(10737): 
,I/jxcore-log(10737): ****TEST TOOK:  10299  ms ****
I/jxcore-log(10737): 
I/jxcore-log(10737): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(10737): 


LGE-LG-H815: 
--------- beginning of main
--------- beginning of system
,W/jxcore-log( 9529): Initializing JXcore engine
W/jxcore-log( 9529): JXcore engine is ready
W/jxcore-log( 9529): Starting JXcore engine
W/jxcore-log( 9529): Platform android
W/jxcore-log( 9529): 
W/jxcore-log( 9529): Process ARCH arm
W/jxcore-log( 9529): 
I/jxcore-log( 9529): JXcore Cordova bridge is ready!
I/jxcore-log( 9529): 
W/jxcore-log( 9529): JXcore engine is started
E/jxcore-log( 9529): >> LGE-LG-H815
E/jxcore-log( 9529): 
I/jxcore-log( 9529): Total memory 2968948736
I/jxcore-log( 9529): 
I/jxcore-log( 9529): Free memory 94265344
I/jxcore-log( 9529): 
I/jxcore-log( 9529): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 9529): 
I/jxcore-log( 9529): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 9529): 
I/jxcore-log( 9529): userPath [ 'www' ]
I/jxcore-log( 9529): 
I/jxcore-log( 9529): Size 1440 2392
I/jxcore-log( 9529): 
I/jxcore-log( 9529): Screen Brightness 255
I/jxcore-log( 9529): 
E/jxcore-log( 9529): Dummy Error Log.
E/jxcore-log( 9529): 
I/jxcore-log( 9529): getBuffer is called!!!!
I/jxcore-log( 9529): 
,I/jxcore-log( 9529): Bluetooth turned on
I/jxcore-log( 9529): 
,I/jxcore-log( 9529): WiFi turned off
I/jxcore-log( 9529): 
,I/jxcore-log( 9529): WiFi turned on
I/jxcore-log( 9529): 
,I/jxcore-log( 9529): No internet connection
I/jxcore-log( 9529): 
,I/jxcore-log( 9529): No internet connection
I/jxcore-log( 9529): 
,I/jxcore-log( 9529): No internet connection
I/jxcore-log( 9529): 
,I/jxcore-log( 9529): No internet connection
I/jxcore-log( 9529): 
,I/jxcore-log( 9529): No internet connection
I/jxcore-log( 9529): 
,I/jxcore-log( 9529): No internet connection
I/jxcore-log( 9529): 
,I/jxcore-log( 9529): WiFi
I/jxcore-log( 9529): 
,I/jxcore-log( 9529): Response status code was: 200
I/jxcore-log( 9529): 
,I/jxcore-log( 9529): ****TEST TOOK:  12763  ms ****
I/jxcore-log( 9529): 
,I/jxcore-log( 9529): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 9529): 


HUAWEI-ALE-L21: 
int logctl_get(): open '/dev/hwlog_switch' fail -1, 13. Permission denied

Note: log switch off, only log_main and log_events will have logs!
--------- beginning of main
,W/jxcore-log( 6233): Initializing JXcore engine
W/jxcore-log( 6233): JXcore engine is ready
,W/jxcore-log( 6233): Starting JXcore engine
,W/jxcore-log( 6233): Platform android
W/jxcore-log( 6233): 
,W/jxcore-log( 6233): Process ARCH arm
W/jxcore-log( 6233): 
,I/jxcore-log( 6233): JXcore Cordova bridge is ready!
I/jxcore-log( 6233): 
W/jxcore-log( 6233): JXcore engine is started
,E/jxcore-log( 6233): >> HUAWEI-ALE-L21
E/jxcore-log( 6233): 
,I/jxcore-log( 6233): Total memory 1949741056
I/jxcore-log( 6233): 
,I/jxcore-log( 6233): Free memory 18477056
I/jxcore-log( 6233): 
I/jxcore-log( 6233): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6233): 
I/jxcore-log( 6233): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6233): 
,I/jxcore-log( 6233): userPath [ 'www' ]
I/jxcore-log( 6233): 
,I/jxcore-log( 6233): Size 720 1184
I/jxcore-log( 6233): 
,I/jxcore-log( 6233): Screen Brightness 242
I/jxcore-log( 6233): 
E/jxcore-log( 6233): Dummy Error Log.
E/jxcore-log( 6233): 
,I/jxcore-log( 6233): getBuffer is called!!!!
I/jxcore-log( 6233): 
,I/jxcore-log( 6233): Bluetooth turned on
I/jxcore-log( 6233): 
,I/jxcore-log( 6233): WiFi turned off
I/jxcore-log( 6233): 
,I/jxcore-log( 6233): WiFi turned on
I/jxcore-log( 6233): 
,I/jxcore-log( 6233): No internet connection
I/jxcore-log( 6233): 
,I/jxcore-log( 6233): No internet connection
I/jxcore-log( 6233): 
,I/jxcore-log( 6233): No internet connection
I/jxcore-log( 6233): 
,I/jxcore-log( 6233): No internet connection
I/jxcore-log( 6233): 
,I/jxcore-log( 6233): No internet connection
I/jxcore-log( 6233): 
,I/jxcore-log( 6233): No internet connection
I/jxcore-log( 6233): 
,I/jxcore-log( 6233): No internet connection
I/jxcore-log( 6233): 
,I/jxcore-log( 6233): WiFi
I/jxcore-log( 6233): 
,I/jxcore-log( 6233): Response status code was: 200
I/jxcore-log( 6233): 
,I/jxcore-log( 6233): ****TEST TOOK:  13465  ms ****
I/jxcore-log( 6233): 
I/jxcore-log( 6233): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6233): 


```

####Node name: thali02
Console output:
```
STOP log received from  FA533YJ03104 Test has  SUCCEEDED
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on LGD7228ee9cf5b 
Device test finished on FA533YJ03104 
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
Android task is completed 
Error: problem stopping Android apk(com.example.hello) to device 09a9416e0297d102 error: device not found
 
```

Logcat output:
```
LGE-Nexus 5: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log( 3353): Initializing JXcore engine
W/jxcore-log( 3353): JXcore engine is ready
W/jxcore-log( 3353): Starting JXcore engine
,W/jxcore-log( 3353): Platform android
W/jxcore-log( 3353): 
W/jxcore-log( 3353): Process ARCH arm
W/jxcore-log( 3353): 
,I/jxcore-log( 3353): JXcore Cordova bridge is ready!
I/jxcore-log( 3353): 
,W/jxcore-log( 3353): JXcore engine is started
,E/jxcore-log( 3353): >> LGE-Nexus 5
E/jxcore-log( 3353): 
I/jxcore-log( 3353): Total memory 1946181632
I/jxcore-log( 3353): 
I/jxcore-log( 3353): Free memory 229941248
I/jxcore-log( 3353): 
I/jxcore-log( 3353): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3353): 
I/jxcore-log( 3353): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3353): 
,I/jxcore-log( 3353): userPath [ 'www' ]
I/jxcore-log( 3353): 
,I/jxcore-log( 3353): Size 1080 1776
I/jxcore-log( 3353): 
,I/jxcore-log( 3353): Screen Brightness 82
I/jxcore-log( 3353): 
E/jxcore-log( 3353): Dummy Error Log.
E/jxcore-log( 3353): 
,I/jxcore-log( 3353): getBuffer is called!!!!
I/jxcore-log( 3353): 
,I/jxcore-log( 3353): Bluetooth turned on
I/jxcore-log( 3353): 
,I/jxcore-log( 3353): WiFi turned off
I/jxcore-log( 3353): 
,I/jxcore-log( 3353): WiFi turned on
I/jxcore-log( 3353): 
,I/jxcore-log( 3353): No internet connection
I/jxcore-log( 3353): 
,I/jxcore-log( 3353): No internet connection
I/jxcore-log( 3353): 
,I/jxcore-log( 3353): No internet connection
I/jxcore-log( 3353): 
,I/jxcore-log( 3353): No internet connection
I/jxcore-log( 3353): 
,I/jxcore-log( 3353): No internet connection
I/jxcore-log( 3353): 
,I/jxcore-log( 3353): WiFi
I/jxcore-log( 3353): 
,I/jxcore-log( 3353): Response status code was: 200
I/jxcore-log( 3353): 
I/jxcore-log( 3353): ****TEST TOOK:  11355  ms ****
I/jxcore-log( 3353): 
I/jxcore-log( 3353): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3353): 


HTC-HTC One M9: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log( 6504): Initializing JXcore engine
W/jxcore-log( 6504): JXcore engine is ready
W/jxcore-log( 6504): Starting JXcore engine
W/jxcore-log( 6504): Platform android
W/jxcore-log( 6504): 
W/jxcore-log( 6504): Process ARCH arm
W/jxcore-log( 6504): 
I/jxcore-log( 6504): JXcore Cordova bridge is ready!
I/jxcore-log( 6504): 
W/jxcore-log( 6504): JXcore engine is started
,E/jxcore-log( 6504): >> HTC-HTC One M9,
E/jxcore-log( 6504): 
,I/jxcore-log( 6504): Total memory 2860257280
I/jxcore-log( 6504): 
I/jxcore-log( 6504): Free memory 150192128
I/jxcore-log( 6504): 
I/jxcore-log( 6504): execPath /data/data/com.example.hello/files/www/jxcore
,I/jxcore-log( 6504): 
I/jxcore-log( 6504): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6504): 
,I/jxcore-log( 6504): userPath [ 'www' ]
I/jxcore-log( 6504): ,
,I/jxcore-log( 6504): Size 1080 1776
I/jxcore-log( 6504): 
,I/jxcore-log( 6504): Screen Brightness 142,
I/jxcore-log( 6504): 
E/jxcore-log( 6504): Dummy Error Log.
E/jxcore-log( 6504): 
,I/jxcore-log( 6504): getBuffer is called!!!!,
I/jxcore-log( 6504): 
,I/jxcore-log( 6504): Bluetooth turned on,
I/jxcore-log( 6504): 
,I/jxcore-log( 6504): WiFi turned off
I/jxcore-log( 6504): 
,I/jxcore-log( 6504): WiFi turned on
I/jxcore-log( 6504): 
,I/jxcore-log( 6504): No internet connection
I/jxcore-log( 6504): 
,I/jxcore-log( 6504): No internet connection
I/jxcore-log( 6504): 
,I/jxcore-log( 6504): No internet connection
I/jxcore-log( 6504): 
,I/jxcore-log( 6504): No internet connection,
I/jxcore-log( 6504): 
,I/jxcore-log( 6504): No internet connection,
I/jxcore-log( 6504): 
,I/jxcore-log( 6504): No internet connection,
I/jxcore-log( 6504): 
,I/jxcore-log( 6504): WiFi
I/jxcore-log( 6504): 
,I/jxcore-log( 6504): Response status code was: 200
I/jxcore-log( 6504): 
I/jxcore-log( 6504): ****TEST TOOK:  12318  ms ****
I/jxcore-log( 6504): 
I/jxcore-log( 6504): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6504): 


LGE-LG-D722: 
--------- beginning of main
--------- beginning of system
,W/jxcore-log( 3201): Initializing JXcore engine
W/jxcore-log( 3201): JXcore engine is ready
,W/jxcore-log( 3201): Starting JXcore engine
,W/jxcore-log( 3201): Platform android
W/jxcore-log( 3201): 
W/jxcore-log( 3201): Process ARCH arm
W/jxcore-log( 3201): 
,I/jxcore-log( 3201): JXcore Cordova bridge is ready!
I/jxcore-log( 3201): 
W/jxcore-log( 3201): JXcore engine is started
,E/jxcore-log( 3201): >> LGE-LG-D722
E/jxcore-log( 3201): 
,I/jxcore-log( 3201): Total memory 906309632
I/jxcore-log( 3201): 
I/jxcore-log( 3201): Free memory 20840448
I/jxcore-log( 3201): 
I/jxcore-log( 3201): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3201): 
I/jxcore-log( 3201): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3201): 
I/jxcore-log( 3201): userPath [ 'www' ]
I/jxcore-log( 3201): 
,I/jxcore-log( 3201): Size 720 1196
I/jxcore-log( 3201): 
,I/jxcore-log( 3201): Screen Brightness 255
I/jxcore-log( 3201): 
E/jxcore-log( 3201): Dummy Error Log.
E/jxcore-log( 3201): 
,I/jxcore-log( 3201): getBuffer is called!!!!
I/jxcore-log( 3201): 
,I/jxcore-log( 3201): Bluetooth turned on
I/jxcore-log( 3201): 
,I/jxcore-log( 3201): WiFi turned off
I/jxcore-log( 3201): 
,I/jxcore-log( 3201): WiFi turned on
I/jxcore-log( 3201): 
,I/jxcore-log( 3201): No internet connection
I/jxcore-log( 3201): 
,I/jxcore-log( 3201): No internet connection
I/jxcore-log( 3201): 
,I/jxcore-log( 3201): No internet connection
I/jxcore-log( 3201): 
,I/jxcore-log( 3201): WiFi
I/jxcore-log( 3201): 
,I/jxcore-log( 3201): Response status code was: 200
I/jxcore-log( 3201): 
I/jxcore-log( 3201): ****TEST TOOK:  9639  ms ****
I/jxcore-log( 3201): 
I/jxcore-log( 3201): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3201): 
,--------- beginning of crash


```

####Node name: thali03
Console output:
```
STOP log received from  TA4750HV7I Test has  SUCCEEDED
STOP log received from  320414cd475f91e3 Test has  SUCCEEDED
Device test finished on TA4750HV7I 
Device test finished on 320414cd475f91e3 
STOP log received from  LGD8553bed2d08 Test has  SUCCEEDED
Device test finished on LGD8553bed2d08 
Android task is completed 
Error: problem stopping Android apk(com.example.hello) to device LGD8553bed2d08 error: device not found
 
```

Logcat output:
```
motorola-XT1039: 
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
,W/jxcore-log( 4003): Initializing JXcore engine,
,W/jxcore-log( 4003): JXcore engine is ready
,W/jxcore-log( 4003): Starting JXcore engine
,W/jxcore-log( 4003): Platform android
W/jxcore-log( 4003): 
,W/jxcore-log( 4003): Process ARCH arm
W/jxcore-log( 4003): 
,I/jxcore-log( 4003): JXcore Cordova bridge is ready!
I/jxcore-log( 4003): 
,W/jxcore-log( 4003): JXcore engine is started
,E/jxcore-log( 4003): >> motorola-XT1039
E/jxcore-log( 4003): 
,I/jxcore-log( 4003): Total memory 893136896
I/jxcore-log( 4003): 
I/jxcore-log( 4003): Free memory 40284160
I/jxcore-log( 4003): 
I/jxcore-log( 4003): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4003): 
,I/jxcore-log( 4003): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4003): 
,I/jxcore-log( 4003): userPath [ 'www' ]
I/jxcore-log( 4003): 
,I/jxcore-log( 4003): Size 720 1184
I/jxcore-log( 4003): 
,I/jxcore-log( 4003): Screen Brightness 210
I/jxcore-log( 4003): 
,E/jxcore-log( 4003): Dummy Error Log.
E/jxcore-log( 4003): 
,I/jxcore-log( 4003): getBuffer is called!!!!
I/jxcore-log( 4003): 
,I/jxcore-log( 4003): Bluetooth turned on
I/jxcore-log( 4003): 
,I/jxcore-log( 4003): WiFi turned off
I/jxcore-log( 4003): 
,I/jxcore-log( 4003): WiFi turned on
I/jxcore-log( 4003): 
,I/jxcore-log( 4003): No internet connection
I/jxcore-log( 4003): 
,I/jxcore-log( 4003): No internet connection
I/jxcore-log( 4003): 
,I/jxcore-log( 4003): No internet connection
I/jxcore-log( 4003): 
,I/jxcore-log( 4003): No internet connection
I/jxcore-log( 4003): 
,I/jxcore-log( 4003): WiFi
I/jxcore-log( 4003): 
,I/jxcore-log( 4003): Response status code was: 200
I/jxcore-log( 4003): 
I/jxcore-log( 4003): ****TEST TOOK:  10338  ms ****
I/jxcore-log( 4003): 
,I/jxcore-log( 4003): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4003): 


LGE-LG-D855: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log( 7292): Initializing JXcore engine
W/jxcore-log( 7292): JXcore engine is ready
W/jxcore-log( 7292): Starting JXcore engine
W/jxcore-log( 7292): Platform android
W/jxcore-log( 7292): 
W/jxcore-log( 7292): Process ARCH arm
W/jxcore-log( 7292): 
I/jxcore-log( 7292): JXcore Cordova bridge is ready!
I/jxcore-log( 7292): 
W/jxcore-log( 7292): JXcore engine is started
,E/jxcore-log( 7292): >> LGE-LG-D855
E/jxcore-log( 7292): 
,I/jxcore-log( 7292): Total memory 2995761152
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): Free memory 525877248
I/jxcore-log( 7292): 
I/jxcore-log( 7292): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 7292): 
I/jxcore-log( 7292): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 7292): 
I/jxcore-log( 7292): userPath [ 'www' ]
I/jxcore-log( 7292): 
I/jxcore-log( 7292): Size 1440 2392
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): Screen Brightness 177
I/jxcore-log( 7292): 
,E/jxcore-log( 7292): Dummy Error Log.
E/jxcore-log( 7292): 
,I/jxcore-log( 7292): getBuffer is called!!!!
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): Bluetooth turned on
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): WiFi turned off
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): WiFi turned on
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection,
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection,
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): Timeout in log.js file reached!
I/jxcore-log( 7292): 
I/jxcore-log( 7292): ****TEST TOOK:  125130  ms ****
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILURE]****
I/jxcore-log( 7292): 
I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 
,I/jxcore-log( 7292): No internet connection
I/jxcore-log( 7292): 


samsung-SM-G800F: 
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
,W/jxcore-log( 7053): Initializing JXcore engine
W/jxcore-log( 7053): JXcore engine is ready
W/jxcore-log( 7053): Starting JXcore engine
W/jxcore-log( 7053): Platform android
W/jxcore-log( 7053): 
W/jxcore-log( 7053): Process ARCH arm
W/jxcore-log( 7053): 
I/jxcore-log( 7053): JXcore Cordova bridge is ready!
I/jxcore-log( 7053): 
W/jxcore-log( 7053): JXcore engine is started
,E/jxcore-log( 7053): >> samsung-SM-G800F
E/jxcore-log( 7053): 
,I/jxcore-log( 7053): Total memory 1319530496
I/jxcore-log( 7053): 
I/jxcore-log( 7053): Free memory 31903744
I/jxcore-log( 7053): 
,I/jxcore-log( 7053): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 7053): 
,I/jxcore-log( 7053): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 7053): 
,I/jxcore-log( 7053): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 7053): 
,I/jxcore-log( 7053): Size 720 1280
I/jxcore-log( 7053): 
,I/jxcore-log( 7053): Screen Brightness 134
I/jxcore-log( 7053): 
,E/jxcore-log( 7053): Dummy Error Log.
E/jxcore-log( 7053): 
,I/jxcore-log( 7053): getBuffer is called!!!!
I/jxcore-log( 7053): 
,I/jxcore-log( 7053): Bluetooth turned on
I/jxcore-log( 7053): 
,I/jxcore-log( 7053): WiFi turned off
I/jxcore-log( 7053): 
,I/jxcore-log( 7053): WiFi turned on,
I/jxcore-log( 7053): 
,I/jxcore-log( 7053): No internet connection,
I/jxcore-log( 7053): 
,I/jxcore-log( 7053): No internet connection
I/jxcore-log( 7053): 
,I/jxcore-log( 7053): No internet connection
I/jxcore-log( 7053): 
,I/jxcore-log( 7053): No internet connection
I/jxcore-log( 7053): 
,I/jxcore-log( 7053): No internet connection,
I/jxcore-log( 7053): 
,I/jxcore-log( 7053): WiFi
I/jxcore-log( 7053): 
,I/jxcore-log( 7053): Response status code was: 200,
I/jxcore-log( 7053): 
I/jxcore-log( 7053): ****TEST TOOK:  11425  ms ****
I/jxcore-log( 7053): 
,I/jxcore-log( 7053): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****,
I/jxcore-log( 7053): 


```

####Node name: thali05
Console output:
```
STOP log received from  SH47FWM00508 Test has  SUCCEEDED
STOP log received from  1d6a772d Test has  SUCCEEDED
Device test finished on SH47FWM00508 
Device test finished on 1d6a772d 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1G429CRK app:com.example.hello code:0 
child process exited with code 0 on device ZX1G429CRK 
Android task is completed 
Error: problem stopping Android apk(com.example.hello) to device ZX1G429CRK error: device not found
 
```

Logcat output:
```
HTC-HTC One_M8: 
--------- beginning of main
--------- beginning of system
,W/jxcore-log( 6585): Initializing JXcore engine
W/jxcore-log( 6585): JXcore engine is ready
W/jxcore-log( 6585): Starting JXcore engine
,W/jxcore-log( 6585): Platform android
W/jxcore-log( 6585): 
W/jxcore-log( 6585): Process ARCH arm
W/jxcore-log( 6585): 
I/jxcore-log( 6585): JXcore Cordova bridge is ready!
I/jxcore-log( 6585): 
W/jxcore-log( 6585): JXcore engine is started
E/jxcore-log( 6585): >> HTC-HTC One_M8
E/jxcore-log( 6585): 
I/jxcore-log( 6585): Total memory 1912020992
I/jxcore-log( 6585): 
I/jxcore-log( 6585): Free memory 127946752
I/jxcore-log( 6585): 
I/jxcore-log( 6585): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6585): 
I/jxcore-log( 6585): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6585): 
I/jxcore-log( 6585): userPath [ 'www' ]
I/jxcore-log( 6585): 
I/jxcore-log( 6585): Size 1080 1776
I/jxcore-log( 6585): 
I/jxcore-log( 6585): Screen Brightness 142
I/jxcore-log( 6585): 
E/jxcore-log( 6585): Dummy Error Log.
E/jxcore-log( 6585): 
,I/jxcore-log( 6585): getBuffer is called!!!!
I/jxcore-log( 6585): 
,I/jxcore-log( 6585): Bluetooth turned on,
,I/jxcore-log( 6585): 
,I/jxcore-log( 6585): WiFi turned off
I/jxcore-log( 6585): 
,I/jxcore-log( 6585): WiFi turned on
I/jxcore-log( 6585): 
,I/jxcore-log( 6585): No internet connection,
I/jxcore-log( 6585): 
,I/jxcore-log( 6585): No internet connection,
I/jxcore-log( 6585): 
,I/jxcore-log( 6585): No internet connection
I/jxcore-log( 6585): 
,I/jxcore-log( 6585): No internet connection
I/jxcore-log( 6585): 
,I/jxcore-log( 6585): WiFi,
I/jxcore-log( 6585): 
,I/jxcore-log( 6585): Response status code was: 200
I/jxcore-log( 6585): 
,I/jxcore-log( 6585): ****TEST TOOK:  10261  ms ****
I/jxcore-log( 6585): 
I/jxcore-log( 6585): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6585): 


samsung-SM-N9005: 
--------- beginning of main
--------- beginning of system
,W/jxcore-log( 6530): Initializing JXcore engine
W/jxcore-log( 6530): JXcore engine is ready
,W/jxcore-log( 6530): Starting JXcore engine
,W/jxcore-log( 6530): Platform android
W/jxcore-log( 6530): 
W/jxcore-log( 6530): Process ARCH arm
W/jxcore-log( 6530): 
,I/jxcore-log( 6530): JXcore Cordova bridge is ready!
I/jxcore-log( 6530): 
,W/jxcore-log( 6530): JXcore engine is started
,E/jxcore-log( 6530): >> samsung-SM-N9005
E/jxcore-log( 6530): 
,I/jxcore-log( 6530): Total memory 2971471872
I/jxcore-log( 6530): 
,I/jxcore-log( 6530): Free memory 343109632
I/jxcore-log( 6530): 
I/jxcore-log( 6530): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6530): 
I/jxcore-log( 6530): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6530): 
,I/jxcore-log( 6530): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 6530): 
,I/jxcore-log( 6530): Size 1080 1920
I/jxcore-log( 6530): 
,I/jxcore-log( 6530): Screen Brightness 162
I/jxcore-log( 6530): 
,E/jxcore-log( 6530): Dummy Error Log.
E/jxcore-log( 6530): 
,I/jxcore-log( 6530): getBuffer is called!!!!
I/jxcore-log( 6530): 
,I/jxcore-log( 6530): Bluetooth turned on
I/jxcore-log( 6530): 
,I/jxcore-log( 6530): WiFi turned off
I/jxcore-log( 6530): 
,I/jxcore-log( 6530): WiFi turned on
I/jxcore-log( 6530): 
,I/jxcore-log( 6530): No internet connection
I/jxcore-log( 6530): 
,I/jxcore-log( 6530): No internet connection
I/jxcore-log( 6530): 
,I/jxcore-log( 6530): No internet connection
I/jxcore-log( 6530): 
,I/jxcore-log( 6530): No internet connection
I/jxcore-log( 6530): 
,I/jxcore-log( 6530): WiFi
I/jxcore-log( 6530): 
,I/jxcore-log( 6530): Response status code was: 200
I/jxcore-log( 6530): 
I/jxcore-log( 6530): ****TEST TOOK:  10179  ms ****
I/jxcore-log( 6530): 
I/jxcore-log( 6530): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6530): 


motorola-Nexus 6: 
--------- beginning of main
,--------- beginning of system
,TIME-OUT KILL (timeout was 150000ms)

```

####Node name: thali06
Console output:
```
STOP log received from  022678fb504e29b0 Test has  SUCCEEDED
Device test finished on 022678fb504e29b0 
STOP log received from  7970f88c Test has  SUCCEEDED
STOP log received from  FA55PYS00566 Test has  SUCCEEDED
Device test finished on 7970f88c 
Device test finished on FA55PYS00566 
Android task is completed 
Error: problem stopping Android apk(com.example.hello) to device FA55PYS00566 error: device not found
 
Error: problem stopping Android apk(com.example.hello) to device 7970f88c error: device not found
 
Error: problem stopping Android apk(com.example.hello) to device 022678fb504e29b0 error: device not found
 
```

Logcat output:
```
HTC-HTC One M8s: 
--------- beginning of main
--------- beginning of system
,W/jxcore-log( 6657): Initializing JXcore engine,
W/jxcore-log( 6657): JXcore engine is ready
,W/jxcore-log( 6657): Starting JXcore engine,
,W/jxcore-log( 6657): Platform android
W/jxcore-log( 6657): ,
W/jxcore-log( 6657): Process ARCH arm
W/jxcore-log( 6657): 
,I/jxcore-log( 6657): JXcore Cordova bridge is ready!,
I/jxcore-log( 6657): 
W/jxcore-log( 6657): JXcore engine is started
,E/jxcore-log( 6657): >> HTC-HTC One M8s,
E/jxcore-log( 6657): 
,I/jxcore-log( 6657): Total memory 1931808768
I/jxcore-log( 6657): 
I/jxcore-log( 6657): Free memory 86982656
I/jxcore-log( 6657): 
I/jxcore-log( 6657): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6657): 
I/jxcore-log( 6657): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6657): 
,I/jxcore-log( 6657): userPath [ 'www' ],
I/jxcore-log( 6657): 
,I/jxcore-log( 6657): Size 1080 1776
I/jxcore-log( 6657): 
,I/jxcore-log( 6657): Screen Brightness 142
I/jxcore-log( 6657): 
,E/jxcore-log( 6657): Dummy Error Log.
E/jxcore-log( 6657): 
,I/jxcore-log( 6657): getBuffer is called!!!!,
I/jxcore-log( 6657): 
,I/jxcore-log( 6657): Bluetooth turned on,
I/jxcore-log( 6657): 
,I/jxcore-log( 6657): WiFi turned off
I/jxcore-log( 6657): 
,I/jxcore-log( 6657): WiFi turned on
I/jxcore-log( 6657): 
,I/jxcore-log( 6657): No internet connection,
I/jxcore-log( 6657): 
,I/jxcore-log( 6657): No internet connection,
I/jxcore-log( 6657): 
,I/jxcore-log( 6657): No internet connection,
I/jxcore-log( 6657): 
,I/jxcore-log( 6657): No internet connection
I/jxcore-log( 6657): 
,I/jxcore-log( 6657): No internet connection,
I/jxcore-log( 6657): 
,I/jxcore-log( 6657): WiFi
I/jxcore-log( 6657): 
,I/jxcore-log( 6657): Response status code was: 200,
I/jxcore-log( 6657): 
I/jxcore-log( 6657): ****TEST TOOK:  11429  ms ****
I/jxcore-log( 6657): 
I/jxcore-log( 6657): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6657): 


samsung-SM-A300FU: 
--------- beginning of system
--------- beginning of main
,W/jxcore-log( 4318): Initializing JXcore engine
W/jxcore-log( 4318): JXcore engine is ready
W/jxcore-log( 4318): Starting JXcore engine
W/jxcore-log( 4318): Platform android
W/jxcore-log( 4318): 
W/jxcore-log( 4318): Process ARCH arm
W/jxcore-log( 4318): 
I/jxcore-log( 4318): JXcore Cordova bridge is ready!
I/jxcore-log( 4318): 
W/jxcore-log( 4318): JXcore engine is started
E/jxcore-log( 4318): >> samsung-SM-A300FU
E/jxcore-log( 4318): 
I/jxcore-log( 4318): Total memory 1451114496
I/jxcore-log( 4318): 
I/jxcore-log( 4318): Free memory 21725184
I/jxcore-log( 4318): 
I/jxcore-log( 4318): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4318): 
I/jxcore-log( 4318): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4318): 
I/jxcore-log( 4318): userPath [ 'www' ]
I/jxcore-log( 4318): 
I/jxcore-log( 4318): Size 540 960
I/jxcore-log( 4318): 
I/jxcore-log( 4318): Screen Brightness 160
I/jxcore-log( 4318): 
E/jxcore-log( 4318): Dummy Error Log.
E/jxcore-log( 4318): 
,I/jxcore-log( 4318): getBuffer is called!!!!
I/jxcore-log( 4318): 
,I/jxcore-log( 4318): Bluetooth turned on
I/jxcore-log( 4318): 
,I/jxcore-log( 4318): WiFi turned off
I/jxcore-log( 4318): 
,I/jxcore-log( 4318): WiFi turned on
I/jxcore-log( 4318): 
,I/jxcore-log( 4318): No internet connection
I/jxcore-log( 4318): 
,I/jxcore-log( 4318): No internet connection
I/jxcore-log( 4318): 
,I/jxcore-log( 4318): No internet connection
I/jxcore-log( 4318): 
,I/jxcore-log( 4318): No internet connection
I/jxcore-log( 4318): 
,I/jxcore-log( 4318): No internet connection
I/jxcore-log( 4318): 
,I/jxcore-log( 4318): No internet connection
I/jxcore-log( 4318): 
,I/jxcore-log( 4318): WiFi
I/jxcore-log( 4318): 
,I/jxcore-log( 4318): Response status code was: 200
I/jxcore-log( 4318): 
I/jxcore-log( 4318): ****TEST TOOK:  12371  ms ****
I/jxcore-log( 4318): 
I/jxcore-log( 4318): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4318): 


LGE-LG-D802: 
--------- beginning of /dev/log/main
--------- beginning of /dev/log/system
,W/jxcore-log( 4877): Initializing JXcore engine
W/jxcore-log( 4877): JXcore engine is ready
W/jxcore-log( 4877): Starting JXcore engine
W/jxcore-log( 4877): Platform android
W/jxcore-log( 4877): 
W/jxcore-log( 4877): Process ARCH arm
W/jxcore-log( 4877): 
I/jxcore-log( 4877): JXcore Cordova bridge is ready!
I/jxcore-log( 4877): 
W/jxcore-log( 4877): JXcore engine is started
E/jxcore-log( 4877): >> LGE-LG-D802
E/jxcore-log( 4877): 
I/jxcore-log( 4877): Total memory 1943035904
I/jxcore-log( 4877): 
I/jxcore-log( 4877): Free memory 380932096
I/jxcore-log( 4877): 
I/jxcore-log( 4877): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4877): 
I/jxcore-log( 4877): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4877): 
I/jxcore-log( 4877): userPath [ 'www' ]
I/jxcore-log( 4877): 
I/jxcore-log( 4877): Size 1080 1776
I/jxcore-log( 4877): 
I/jxcore-log( 4877): Screen Brightness 255
I/jxcore-log( 4877): 
E/jxcore-log( 4877): Dummy Error Log.
E/jxcore-log( 4877): 
,I/jxcore-log( 4877): getBuffer is called!!!!
I/jxcore-log( 4877): 
,I/jxcore-log( 4877): Bluetooth turned on
I/jxcore-log( 4877): 
,I/jxcore-log( 4877): WiFi turned off
I/jxcore-log( 4877): 
,I/jxcore-log( 4877): WiFi turned on
I/jxcore-log( 4877): 
,I/jxcore-log( 4877): No internet connection
I/jxcore-log( 4877): 
,I/jxcore-log( 4877): No internet connection
I/jxcore-log( 4877): 
,I/jxcore-log( 4877): No internet connection
I/jxcore-log( 4877): 
,I/jxcore-log( 4877): No internet connection
I/jxcore-log( 4877): 
,I/jxcore-log( 4877): WiFi
I/jxcore-log( 4877): 
,I/jxcore-log( 4877): Response status code was: 200
I/jxcore-log( 4877): 
I/jxcore-log( 4877): ****TEST TOOK:  10232  ms ****
I/jxcore-log( 4877): 
,I/jxcore-log( 4877): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4877): 


```

####Node name: thali07
Console output:
```
Error! Unexpected exit on device c5afcdcb app:com.example.hello code:0 
child process exited with code 0 on device c5afcdcb 
STOP log received from  f56ad48d Test has  SUCCEEDED
Device test finished on f56ad48d 
Android task is completed 
Error: problem stopping Android apk(com.example.hello) to device f56ad48d error: device not found
 
```

Logcat output:
```
samsung-SM-A500FU: 
--------- beginning of system
--------- beginning of main
,W/jxcore-log( 5678): Initializing JXcore engine
W/jxcore-log( 5678): JXcore engine is ready
,W/jxcore-log( 5678): Starting JXcore engine
,W/jxcore-log( 5678): Platform android,
W/jxcore-log( 5678): 
W/jxcore-log( 5678): Process ARCH arm
W/jxcore-log( 5678): 
,I/jxcore-log( 5678): JXcore Cordova bridge is ready!
I/jxcore-log( 5678): 
,W/jxcore-log( 5678): JXcore engine is started
,E/jxcore-log( 5678): >> samsung-SM-A500FU
E/jxcore-log( 5678): 
,I/jxcore-log( 5678): Total memory 1983787008
I/jxcore-log( 5678): 
,I/jxcore-log( 5678): Free memory 31887360
I/jxcore-log( 5678): 
I/jxcore-log( 5678): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5678): 
I/jxcore-log( 5678): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5678): 
,I/jxcore-log( 5678): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 5678): 
,I/jxcore-log( 5678): Size 720 1280
I/jxcore-log( 5678): 
,I/jxcore-log( 5678): Screen Brightness 255
I/jxcore-log( 5678): 
,E/jxcore-log( 5678): Dummy Error Log.
E/jxcore-log( 5678): 
,I/jxcore-log( 5678): getBuffer is called!!!!
I/jxcore-log( 5678): 
,I/jxcore-log( 5678): Bluetooth turned on
I/jxcore-log( 5678): 
,I/jxcore-log( 5678): WiFi turned off
I/jxcore-log( 5678): 
,I/jxcore-log( 5678): WiFi turned on
I/jxcore-log( 5678): 
,I/jxcore-log( 5678): No internet connection
I/jxcore-log( 5678): 
,I/jxcore-log( 5678): No internet connection
I/jxcore-log( 5678): 
,I/jxcore-log( 5678): No internet connection
I/jxcore-log( 5678): 
,I/jxcore-log( 5678): No internet connection
I/jxcore-log( 5678): 
,I/jxcore-log( 5678): No internet connection,
I/jxcore-log( 5678): 
,I/jxcore-log( 5678): WiFi
I/jxcore-log( 5678): 
,I/jxcore-log( 5678): Response status code was: 200
I/jxcore-log( 5678): 
I/jxcore-log( 5678): ****TEST TOOK:  11272  ms ****
I/jxcore-log( 5678): 
I/jxcore-log( 5678): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5678): 


samsung-SM-G900F: 
--------- beginning of main
--------- beginning of system
,W/jxcore-log( 5083): Initializing JXcore engine
W/jxcore-log( 5083): JXcore engine is ready
W/jxcore-log( 5083): Starting JXcore engine
,W/jxcore-log( 5083): Platform android
W/jxcore-log( 5083): 
W/jxcore-log( 5083): Process ARCH arm
W/jxcore-log( 5083): 
,I/jxcore-log( 5083): JXcore Cordova bridge is ready!
I/jxcore-log( 5083): 
,W/jxcore-log( 5083): JXcore engine is started
,E/jxcore-log( 5083): >> samsung-SM-G900F
E/jxcore-log( 5083): 
,I/jxcore-log( 5083): Total memory 1787449344
I/jxcore-log( 5083): 
,I/jxcore-log( 5083): Free memory 47206400
I/jxcore-log( 5083): 
I/jxcore-log( 5083): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5083): 
I/jxcore-log( 5083): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5083): 
,I/jxcore-log( 5083): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 5083): 
,I/jxcore-log( 5083): Size 1080 1920
I/jxcore-log( 5083): 
,I/jxcore-log( 5083): Screen Brightness 134
I/jxcore-log( 5083): 
,E/jxcore-log( 5083): Dummy Error Log.
E/jxcore-log( 5083): 
,I/jxcore-log( 5083): getBuffer is called!!!!
I/jxcore-log( 5083): 
,I/jxcore-log( 5083): Bluetooth turned on
I/jxcore-log( 5083): 
,I/jxcore-log( 5083): WiFi turned off
I/jxcore-log( 5083): 
,I/jxcore-log( 5083): WiFi turned on
I/jxcore-log( 5083): 
,I/jxcore-log( 5083): No internet connection
I/jxcore-log( 5083): 
,I/jxcore-log( 5083): No internet connection
I/jxcore-log( 5083): 
,I/jxcore-log( 5083): No internet connection
I/jxcore-log( 5083): 


```

####Node name: thali08
Console output:
```
Error: problem deploying Android apk(/home/pi/test/builder/builds/49526184a3a5cb3/build_android/android_0_49526184a3a5cb3.apk) to device 4325e43f protocol failure
- waiting for device -
rm: /data/local/tmp/android_0_49526184a3a5cb3.apk: No such file or directory



Test on this node has failed but the reason wasn't the test application itself.
 Cancelling the test result on this node.

```
####Node name: thali09
Console output:
```
STOP log received from  CC51WYC03425 Test has  SUCCEEDED
Device test finished on CC51WYC03425 
STOP log received from  0c6a0f3c0bdb4e77 Test has  SUCCEEDED
Device test finished on 0c6a0f3c0bdb4e77 
Android task is completed 
Error: problem stopping Android apk(com.example.hello) to device 0c6a0f3c0bdb4e77 error: device not found
 
```

Logcat output:
```
LGE-Nexus 5: 
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
,W/jxcore-log( 2723): Initializing JXcore engine
,W/jxcore-log( 2723): JXcore engine is ready
,W/jxcore-log( 2723): Starting JXcore engine
,W/jxcore-log( 2723): Platform android
W/jxcore-log( 2723): 
,W/jxcore-log( 2723): Process ARCH arm
W/jxcore-log( 2723): 
,I/jxcore-log( 2723): JXcore Cordova bridge is ready!
I/jxcore-log( 2723): 
,W/jxcore-log( 2723): JXcore engine is started
,E/jxcore-log( 2723): >> LGE-Nexus 5
E/jxcore-log( 2723): 
,I/jxcore-log( 2723): Total memory 1945137152
I/jxcore-log( 2723): 
,I/jxcore-log( 2723): Free memory 853524480
I/jxcore-log( 2723): 
,I/jxcore-log( 2723): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2723): 
,I/jxcore-log( 2723): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2723): 
,I/jxcore-log( 2723): userPath [ 'www' ]
I/jxcore-log( 2723): 
,I/jxcore-log( 2723): Size 1080 1776
I/jxcore-log( 2723): 
,I/jxcore-log( 2723): Screen Brightness 82
I/jxcore-log( 2723): 
,E/jxcore-log( 2723): Dummy Error Log.
E/jxcore-log( 2723): 
,I/jxcore-log( 2723): getBuffer is called!!!!
I/jxcore-log( 2723): 
,I/jxcore-log( 2723): Bluetooth turned on
I/jxcore-log( 2723): 
,I/jxcore-log( 2723): WiFi turned off
I/jxcore-log( 2723): 
,I/jxcore-log( 2723): WiFi turned on
I/jxcore-log( 2723): 
,I/jxcore-log( 2723): No internet connection
I/jxcore-log( 2723): 
,I/jxcore-log( 2723): No internet connection
I/jxcore-log( 2723): 
,I/jxcore-log( 2723): No internet connection
I/jxcore-log( 2723): 
,I/jxcore-log( 2723): No internet connection
I/jxcore-log( 2723): 
,I/jxcore-log( 2723): No internet connection
I/jxcore-log( 2723): 
,I/jxcore-log( 2723): No internet connection
I/jxcore-log( 2723): 
,I/jxcore-log( 2723): No internet connection
I/jxcore-log( 2723): 
,I/jxcore-log( 2723): No internet connection
I/jxcore-log( 2723): 
,I/jxcore-log( 2723): No internet connection
I/jxcore-log( 2723): 
,I/jxcore-log( 2723): No internet connection
I/jxcore-log( 2723): 
,I/jxcore-log( 2723): No internet connection
I/jxcore-log( 2723): 
,I/jxcore-log( 2723): No internet connection
I/jxcore-log( 2723): 
,I/jxcore-log( 2723): No internet connection
I/jxcore-log( 2723): 
,I/jxcore-log( 2723): No internet connection
I/jxcore-log( 2723): 
,I/jxcore-log( 2723): No internet connection
I/jxcore-log( 2723): 
,I/jxcore-log( 2723): No internet connection
I/jxcore-log( 2723): 
,I/jxcore-log( 2723): No internet connection
I/jxcore-log( 2723): 
,I/jxcore-log( 2723): No internet connection
I/jxcore-log( 2723): 
,I/jxcore-log( 2723): No internet connection
I/jxcore-log( 2723): 
,I/jxcore-log( 2723): No internet connection
I/jxcore-log( 2723): 
,I/jxcore-log( 2723): No internet connection
I/jxcore-log( 2723): 
,I/jxcore-log( 2723): No internet connection
I/jxcore-log( 2723): 
,I/jxcore-log( 2723): No internet connection
I/jxcore-log( 2723): 
,I/jxcore-log( 2723): No internet connection
I/jxcore-log( 2723): 
,I/jxcore-log( 2723): No internet connection
I/jxcore-log( 2723): 
,I/jxcore-log( 2723): No internet connection
I/jxcore-log( 2723): 
,I/jxcore-log( 2723): No internet connection
I/jxcore-log( 2723): 
,I/jxcore-log( 2723): No internet connection
I/jxcore-log( 2723): 
,I/jxcore-log( 2723): No internet connection
I/jxcore-log( 2723): 
,I/jxcore-log( 2723): No internet connection
I/jxcore-log( 2723): 
,I/jxcore-log( 2723): No internet connection
I/jxcore-log( 2723): 
,I/jxcore-log( 2723): No internet connection
I/jxcore-log( 2723): 
,I/jxcore-log( 2723): No internet connection
I/jxcore-log( 2723): 
,I/jxcore-log( 2723): No internet connection
I/jxcore-log( 2723): 
,I/jxcore-log( 2723): No internet connection
I/jxcore-log( 2723): 
,I/jxcore-log( 2723): No internet connection
I/jxcore-log( 2723): 
,I/jxcore-log( 2723): WiFi
I/jxcore-log( 2723): 
,I/jxcore-log( 2723): Response status code was: 200
I/jxcore-log( 2723): 
,I/jxcore-log( 2723): ****TEST TOOK:  42227  ms ****
I/jxcore-log( 2723): 
,I/jxcore-log( 2723): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2723): 


HTC-HTC Desire 820: 
--------- beginning of /dev/log/system
--------- beginning of /dev/log/main
,W/jxcore-log( 2679): Initializing JXcore engine
W/jxcore-log( 2679): JXcore engine is ready
W/jxcore-log( 2679): Starting JXcore engine
W/jxcore-log( 2679): Platform android
W/jxcore-log( 2679): 
W/jxcore-log( 2679): Process ARCH arm
W/jxcore-log( 2679): 
I/jxcore-log( 2679): JXcore Cordova bridge is ready!
I/jxcore-log( 2679): 
W/jxcore-log( 2679): JXcore engine is started
E/jxcore-log( 2679): >> HTC-HTC Desire 820
E/jxcore-log( 2679): 
I/jxcore-log( 2679): Total memory 1964650496
I/jxcore-log( 2679): 
I/jxcore-log( 2679): Free memory 750739456
I/jxcore-log( 2679): 
I/jxcore-log( 2679): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2679): 
I/jxcore-log( 2679): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2679): 
I/jxcore-log( 2679): userPath [ 'www' ]
I/jxcore-log( 2679): 
I/jxcore-log( 2679): Size 720 1184
I/jxcore-log( 2679): 
I/jxcore-log( 2679): Screen Brightness 142
I/jxcore-log( 2679): 
E/jxcore-log( 2679): Dummy Error Log.
E/jxcore-log( 2679): 
,I/jxcore-log( 2679): getBuffer is called!!!!
I/jxcore-log( 2679): 
,I/jxcore-log( 2679): Bluetooth turned on
I/jxcore-log( 2679): 
,I/jxcore-log( 2679): WiFi turned off
I/jxcore-log( 2679): 
,I/jxcore-log( 2679): WiFi turned on
I/jxcore-log( 2679): 
,I/jxcore-log( 2679): No internet connection
I/jxcore-log( 2679): 
,I/jxcore-log( 2679): No internet connection
I/jxcore-log( 2679): 
,I/jxcore-log( 2679): No internet connection
I/jxcore-log( 2679): 
,I/jxcore-log( 2679): No internet connection
I/jxcore-log( 2679): 
,I/jxcore-log( 2679): No internet connection
I/jxcore-log( 2679): 
,I/jxcore-log( 2679): WiFi
I/jxcore-log( 2679): 
,I/jxcore-log( 2679): Response status code was: 200
I/jxcore-log( 2679): 
,I/jxcore-log( 2679): ****TEST TOOK:  11336  ms ****
I/jxcore-log( 2679): 
,I/jxcore-log( 2679): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2679): 


```




#### Integration Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":20,"cancel":1}}
Integration server has received  [ 'jx',
  '/home/pi/Test/server_49526184a3a5cb3/Sub/serverApp/index.js',
  '{"devices":{"android":20,"cancel":1}}' ]

JSON { devices: { android: 20, cancel: 1 } }


```

