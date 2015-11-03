#### Test 49526184ca93672 Logs

Status: 
```

server : Error: Command failed: Unknown information received by IS manager /cancel=1

 
Run IS script aborted
 
[0;31mexecution aborted
 [0m
Unknown information received by IS manager /cancel=1


android : Error: Command failed: Error: Command failed: run_.sh aborted
 [0m


TIMEOUT REACHED!
```
#### Integration Server Logs
```
Error: Command failed: Unknown information received by IS manager /cancel=1

 
Run IS script aborted
 
[0;31mexecution aborted
 [0m
Unknown information received by IS manager /cancel=1

```

###Android Logs
####Node name: thali01
Console output:
```
Error: problem deploying Android apk(/home/pi/test/builder/builds/49526184ca93672/build_android/android_0_49526184ca93672.apk) to device 30049d9501da2100 5561 KB/s (16811451 bytes in 2.951s)
	pkg: /data/local/tmp/android_0_49526184ca93672.apk
Terminated



Test on this node has failed but the reason wasn't the test application itself.
 Cancelling the test result on this node.

```
####Node name: thali02
Console output:
```
Error! Unexpected exit on device 09a9416e0297d102 app:com.example.hello code:null 
child process exited with code null on device 09a9416e0297d102 
Android task is completed 
```

Logcat output:
```
LGE-Nexus 5: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(13676): Initializing JXcore engine
W/jxcore-log(13676): JXcore engine is ready
,W/jxcore-log(13676): Starting JXcore engine
,W/jxcore-log(13676): Platform android
W/jxcore-log(13676): 
W/jxcore-log(13676): Process ARCH arm
W/jxcore-log(13676): 
,I/jxcore-log(13676): JXcore Cordova bridge is ready!
I/jxcore-log(13676): 
,W/jxcore-log(13676): JXcore engine is started
,E/jxcore-log(13676): >> LGE-Nexus 5
E/jxcore-log(13676): 
I/jxcore-log(13676): Total memory 1946181632
I/jxcore-log(13676): 
I/jxcore-log(13676): Free memory 345202688
I/jxcore-log(13676): 
I/jxcore-log(13676): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(13676): 
I/jxcore-log(13676): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(13676): 
,I/jxcore-log(13676): userPath [ 'www' ]
I/jxcore-log(13676): 
,I/jxcore-log(13676): Size 1080 1776
I/jxcore-log(13676): 
,I/jxcore-log(13676): Screen Brightness 82
I/jxcore-log(13676): 
,E/jxcore-log(13676): Dummy Error Log.
E/jxcore-log(13676): 
,I/jxcore-log(13676): getBuffer is called!!!!
I/jxcore-log(13676): 


LGE-LG-D722: 
--------- beginning of system
--------- beginning of main
W/jxcore-log(32255): Initializing JXcore engine
W/jxcore-log(32255): JXcore engine is ready
W/jxcore-log(32255): Starting JXcore engine
W/jxcore-log(32255): Platform android
W/jxcore-log(32255): 
W/jxcore-log(32255): Process ARCH arm
W/jxcore-log(32255): 
I/jxcore-log(32255): JXcore Cordova bridge is ready!
I/jxcore-log(32255): 
W/jxcore-log(32255): JXcore engine is started
E/jxcore-log(32255): >> LGE-LG-D722
E/jxcore-log(32255): 
I/jxcore-log(32255): Total memory 906309632
I/jxcore-log(32255): 
I/jxcore-log(32255): Free memory 15724544
I/jxcore-log(32255): 
I/jxcore-log(32255): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(32255): 
I/jxcore-log(32255): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(32255): 
I/jxcore-log(32255): userPath [ 'www' ]
I/jxcore-log(32255): 
I/jxcore-log(32255): Size 720 1196
I/jxcore-log(32255): 
I/jxcore-log(32255): Screen Brightness 255
I/jxcore-log(32255): 
E/jxcore-log(32255): Dummy Error Log.
E/jxcore-log(32255): 
I/jxcore-log(32255): getBuffer is called!!!!
I/jxcore-log(32255): 
I/jxcore-log(32255): ****TEST TOOK:  5078  ms ****
I/jxcore-log(32255): 
I/jxcore-log(32255): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(32255): 


```

####Node name: thali03
Console output:
```
Error: problem deploying Android apk(/home/pi/test/builder/builds/49526184ca93672/build_android/android_0_49526184ca93672.apk) to device 320414cd475f91e3 Terminated



Test on this node has failed but the reason wasn't the test application itself.
 Cancelling the test result on this node.

```
####Node name: thali04
####Node name: thali05
Console output:
```
Error! Unexpected exit on device SH47FWM00508 app:com.example.hello code:null 
child process exited with code null on device SH47FWM00508 
Error! Unexpected exit on device 1d6a772d app:com.example.hello code:null 
child process exited with code null on device 1d6a772d 
Error! Unexpected exit on device ZX1G429CRK app:com.example.hello code:null 
child process exited with code null on device ZX1G429CRK 
Android task is completed 
```

Logcat output:
```
HTC-HTC One_M8: 


samsung-SM-N9005: 
--------- beginning of system,
--------- beginning of main
,W/jxcore-log(27945): Initializing JXcore engine
,W/jxcore-log(27945): JXcore engine is ready
,W/jxcore-log(27945): Starting JXcore engine
,W/jxcore-log(27945): Platform android
W/jxcore-log(27945): 
,W/jxcore-log(27945): Process ARCH arm
W/jxcore-log(27945): 
,I/jxcore-log(27945): JXcore Cordova bridge is ready!
I/jxcore-log(27945): 
,W/jxcore-log(27945): JXcore engine is started
,E/jxcore-log(27945): >> samsung-SM-N9005
E/jxcore-log(27945): 
,I/jxcore-log(27945): Total memory 2971471872
I/jxcore-log(27945): 
I/jxcore-log(27945): Free memory 579805184
I/jxcore-log(27945): 
I/jxcore-log(27945): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(27945): 
I/jxcore-log(27945): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(27945): 
,I/jxcore-log(27945): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(27945): 
,I/jxcore-log(27945): Size 1080 1920
I/jxcore-log(27945): 
,I/jxcore-log(27945): Screen Brightness 255
I/jxcore-log(27945): 
E/jxcore-log(27945): Dummy Error Log.
E/jxcore-log(27945): 
,I/jxcore-log(27945): getBuffer is called!!!!
I/jxcore-log(27945): 


motorola-Nexus 6: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(13717): Initializing JXcore engine
W/jxcore-log(13717): JXcore engine is ready
W/jxcore-log(13717): Starting JXcore engine
,W/jxcore-log(13717): Platform android
W/jxcore-log(13717): 
,W/jxcore-log(13717): Process ARCH arm
W/jxcore-log(13717): 
,I/jxcore-log(13717): JXcore Cordova bridge is ready!
I/jxcore-log(13717): 
,W/jxcore-log(13717): JXcore engine is started
,E/jxcore-log(13717): >> motorola-Nexus 6
E/jxcore-log(13717): 
,I/jxcore-log(13717): Total memory 3114405888
I/jxcore-log(13717): 
,I/jxcore-log(13717): Free memory 610893824
I/jxcore-log(13717): 
I/jxcore-log(13717): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(13717): 
I/jxcore-log(13717): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(13717): 
,I/jxcore-log(13717): userPath [ 'www' ]
I/jxcore-log(13717): 
,I/jxcore-log(13717): Size 1440 2392
I/jxcore-log(13717): 
,I/jxcore-log(13717): Screen Brightness 82
I/jxcore-log(13717): 
,E/jxcore-log(13717): Dummy Error Log.
E/jxcore-log(13717): 
,I/jxcore-log(13717): getBuffer is called!!!!
I/jxcore-log(13717): 


```

####Node name: thali06
Console output:
```
Error! Unexpected exit on device FA55PYS00566 app:com.example.hello code:null 
child process exited with code null on device FA55PYS00566 
Error! Unexpected exit on device 7970f88c app:com.example.hello code:0 
child process exited with code 0 on device 7970f88c 
Error! Unexpected exit on device 022678fb504e29b0 app:com.example.hello code:0 
child process exited with code 0 on device 022678fb504e29b0 
Android task is completed 
```

Logcat output:
```
HTC-HTC One M8s: 


samsung-SM-A300FU: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(14681): Initializing JXcore engine
,W/jxcore-log(14681): JXcore engine is ready
,W/jxcore-log(14681): Starting JXcore engine
,W/jxcore-log(14681): Platform android
W/jxcore-log(14681): 
W/jxcore-log(14681): Process ARCH arm
W/jxcore-log(14681): 
,I/jxcore-log(14681): JXcore Cordova bridge is ready!
I/jxcore-log(14681): 
,W/jxcore-log(14681): JXcore engine is started
,E/jxcore-log(14681): >> samsung-SM-A300FU
E/jxcore-log(14681): 
,I/jxcore-log(14681): Total memory 1451114496
I/jxcore-log(14681): 
,I/jxcore-log(14681): Free memory 187944960
I/jxcore-log(14681): 
I/jxcore-log(14681): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(14681): 
I/jxcore-log(14681): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(14681): 
,I/jxcore-log(14681): userPath [ 'www' ]
I/jxcore-log(14681): 
,I/jxcore-log(14681): Size 540 960
I/jxcore-log(14681): 
,I/jxcore-log(14681): Screen Brightness 160
I/jxcore-log(14681): 
,E/jxcore-log(14681): Dummy Error Log.
E/jxcore-log(14681): 
,I/jxcore-log(14681): getBuffer is called!!!!
I/jxcore-log(14681): 


LGE-LG-D802: 
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
,W/jxcore-log(18224): Initializing JXcore engine
W/jxcore-log(18224): JXcore engine is ready
W/jxcore-log(18224): Starting JXcore engine
W/jxcore-log(18224): Platform android
W/jxcore-log(18224): 
W/jxcore-log(18224): Process ARCH arm
W/jxcore-log(18224): 
I/jxcore-log(18224): JXcore Cordova bridge is ready!
I/jxcore-log(18224): 
W/jxcore-log(18224): JXcore engine is started
E/jxcore-log(18224): >> LGE-LG-D802
E/jxcore-log(18224): 
I/jxcore-log(18224): Total memory 1943035904
I/jxcore-log(18224): 
I/jxcore-log(18224): Free memory 173473792
I/jxcore-log(18224): 
I/jxcore-log(18224): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(18224): 
I/jxcore-log(18224): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(18224): 
I/jxcore-log(18224): userPath [ 'www' ]
I/jxcore-log(18224): 
I/jxcore-log(18224): Size 1080 1776
I/jxcore-log(18224): 
I/jxcore-log(18224): Screen Brightness 255
I/jxcore-log(18224): 
E/jxcore-log(18224): Dummy Error Log.
E/jxcore-log(18224): 
,I/jxcore-log(18224): getBuffer is called!!!!
I/jxcore-log(18224): 


```

####Node name: thali07
Console output:
```
Error! Unexpected exit on device 4db5c8cc app:com.example.hello code:null 
child process exited with code null on device 4db5c8cc 
Error! Unexpected exit on device c5afcdcb app:com.example.hello code:null 
child process exited with code null on device c5afcdcb 
Android task is completed 
```

Logcat output:
```
samsung-SM-A500FU: 
--------- beginning of system
,--------- beginning of main
,W/jxcore-log(16414): Initializing JXcore engine
W/jxcore-log(16414): JXcore engine is ready
W/jxcore-log(16414): Starting JXcore engine
W/jxcore-log(16414): Platform android
W/jxcore-log(16414): 
W/jxcore-log(16414): Process ARCH arm
W/jxcore-log(16414): 
I/jxcore-log(16414): JXcore Cordova bridge is ready!
I/jxcore-log(16414): 
W/jxcore-log(16414): JXcore engine is started
,E/jxcore-log(16414): >> samsung-SM-A500FU
E/jxcore-log(16414): 
,I/jxcore-log(16414): Total memory 1983787008
I/jxcore-log(16414): 
,I/jxcore-log(16414): Free memory 363450368
I/jxcore-log(16414): 
I/jxcore-log(16414): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(16414): 
I/jxcore-log(16414): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(16414): 
,I/jxcore-log(16414): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(16414): 
,I/jxcore-log(16414): Size 720 1280
I/jxcore-log(16414): 
,I/jxcore-log(16414): Screen Brightness 255
I/jxcore-log(16414): 
,E/jxcore-log(16414): Dummy Error Log.
E/jxcore-log(16414): 
,I/jxcore-log(16414): getBuffer is called!!!!
I/jxcore-log(16414): 
,I/jxcore-log(16414): Bluetooth toggled
I/jxcore-log(16414): 
,I/jxcore-log(16414): WiFi toggled
I/jxcore-log(16414): 


samsung-SM-G900F: 
--------- beginning of main
--------- beginning of system
,W/jxcore-log(23396): Initializing JXcore engine
W/jxcore-log(23396): JXcore engine is ready
,W/jxcore-log(23396): Starting JXcore engine
,W/jxcore-log(23396): Platform android
W/jxcore-log(23396): 
W/jxcore-log(23396): Process ARCH arm
W/jxcore-log(23396): 
,I/jxcore-log(23396): JXcore Cordova bridge is ready!
I/jxcore-log(23396): 
,W/jxcore-log(23396): JXcore engine is started
,E/jxcore-log(23396): >> samsung-SM-G900F
E/jxcore-log(23396): 
,I/jxcore-log(23396): Total memory 1787449344
I/jxcore-log(23396): 
,I/jxcore-log(23396): Free memory 41644032
I/jxcore-log(23396): 
I/jxcore-log(23396): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(23396): 
I/jxcore-log(23396): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(23396): 
,I/jxcore-log(23396): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(23396): 
,I/jxcore-log(23396): Size 1080 1920
I/jxcore-log(23396): 
,I/jxcore-log(23396): Screen Brightness 134
I/jxcore-log(23396): 
,E/jxcore-log(23396): Dummy Error Log.
E/jxcore-log(23396): 
,I/jxcore-log(23396): getBuffer is called!!!!
I/jxcore-log(23396): 
,I/jxcore-log(23396): Bluetooth toggled
I/jxcore-log(23396): 
,I/jxcore-log(23396): WiFi toggled
I/jxcore-log(23396): 


```

####Node name: thali08
Console output:
```
Error! Unexpected exit on device 4325e43f app:com.example.hello code:null 
child process exited with code null on device 4325e43f 
Error! Unexpected exit on device HT574YC04723 app:com.example.hello code:null 
child process exited with code null on device HT574YC04723 
Android task is completed 
```

Logcat output:
```
samsung-SM-A300FU: 
--------- beginning of system
--------- beginning of main
,W/jxcore-log(13012): Initializing JXcore engine
W/jxcore-log(13012): JXcore engine is ready
,W/jxcore-log(13012): Starting JXcore engine
,W/jxcore-log(13012): Platform android,
W/jxcore-log(13012): 
W/jxcore-log(13012): Process ARCH arm
W/jxcore-log(13012): 
,I/jxcore-log(13012): JXcore Cordova bridge is ready!,
I/jxcore-log(13012): 
W/jxcore-log(13012): JXcore engine is started
,E/jxcore-log(13012): >> samsung-SM-A300FU
E/jxcore-log(13012): 
,I/jxcore-log(13012): Total memory 1451114496
I/jxcore-log(13012): 
,I/jxcore-log(13012): Free memory 200765440
I/jxcore-log(13012): 
I/jxcore-log(13012): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(13012): 
I/jxcore-log(13012): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(13012): 
,I/jxcore-log(13012): userPath [ 'www' ]
I/jxcore-log(13012): 
,I/jxcore-log(13012): Size 540 960
I/jxcore-log(13012): 
,I/jxcore-log(13012): Screen Brightness 255
I/jxcore-log(13012): 
,E/jxcore-log(13012): Dummy Error Log.
E/jxcore-log(13012): 
,I/jxcore-log(13012): getBuffer is called!!!!
I/jxcore-log(13012): 
,I/jxcore-log(13012): Bluetooth toggled
I/jxcore-log(13012): 
,I/jxcore-log(13012): WiFi toggled
I/jxcore-log(13012): 


HTC-HTC Desire 820: 
--------- beginning of /dev/log/system
,--------- beginning of /dev/log/main
,W/jxcore-log( 7246): Initializing JXcore engine
W/jxcore-log( 7246): JXcore engine is ready
W/jxcore-log( 7246): Starting JXcore engine
W/jxcore-log( 7246): Platform android
W/jxcore-log( 7246): 
W/jxcore-log( 7246): Process ARCH arm
W/jxcore-log( 7246): 
I/jxcore-log( 7246): JXcore Cordova bridge is ready!
I/jxcore-log( 7246): 
W/jxcore-log( 7246): JXcore engine is started
E/jxcore-log( 7246): >> HTC-HTC Desire 820
E/jxcore-log( 7246): 
I/jxcore-log( 7246): Total memory 1964650496
I/jxcore-log( 7246): 
I/jxcore-log( 7246): Free memory 231247872
I/jxcore-log( 7246): 
I/jxcore-log( 7246): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 7246): 
I/jxcore-log( 7246): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 7246): 
I/jxcore-log( 7246): userPath [ 'www' ]
I/jxcore-log( 7246): 
I/jxcore-log( 7246): Size 720 1184
I/jxcore-log( 7246): 
I/jxcore-log( 7246): Screen Brightness 10
I/jxcore-log( 7246): 
E/jxcore-log( 7246): Dummy Error Log.
E/jxcore-log( 7246): 
,I/jxcore-log( 7246): getBuffer is called!!!!
I/jxcore-log( 7246): 
,I/jxcore-log( 7246): Bluetooth toggled
I/jxcore-log( 7246): 
,I/jxcore-log( 7246): WiFi toggled
I/jxcore-log( 7246): 


```

####Node name: thali09
Console output:
```
Error! Unexpected exit on device 0c6a0f3c0bdb4e77 app:com.example.hello code:0 
child process exited with code 0 on device 0c6a0f3c0bdb4e77 
Error! Unexpected exit on device CC51WYC03425 app:com.example.hello code:0 
child process exited with code 0 on device CC51WYC03425 
Android task is completed 
```

Logcat output:
```
LGE-Nexus 5: 
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
,W/jxcore-log(12518): Initializing JXcore engine
W/jxcore-log(12518): JXcore engine is ready
W/jxcore-log(12518): Starting JXcore engine
W/jxcore-log(12518): Platform android
W/jxcore-log(12518): 
W/jxcore-log(12518): Process ARCH arm
W/jxcore-log(12518): 
I/jxcore-log(12518): JXcore Cordova bridge is ready!
I/jxcore-log(12518): 
W/jxcore-log(12518): JXcore engine is started
E/jxcore-log(12518): >> LGE-Nexus 5
E/jxcore-log(12518): 
I/jxcore-log(12518): Total memory 1945137152
I/jxcore-log(12518): 
I/jxcore-log(12518): Free memory 514969600
I/jxcore-log(12518): 
I/jxcore-log(12518): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(12518): 
I/jxcore-log(12518): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(12518): 
I/jxcore-log(12518): userPath [ 'www' ]
I/jxcore-log(12518): 
I/jxcore-log(12518): Size 1080 1776
I/jxcore-log(12518): 
I/jxcore-log(12518): Screen Brightness 82
I/jxcore-log(12518): 
E/jxcore-log(12518): Dummy Error Log.
E/jxcore-log(12518): 
,I/jxcore-log(12518): getBuffer is called!!!!
I/jxcore-log(12518): 
,I/jxcore-log(12518): Bluetooth toggled
I/jxcore-log(12518): 
,I/jxcore-log(12518): WiFi toggled
I/jxcore-log(12518): 


HTC-HTC Desire 820: 
--------- beginning of /dev/log/main
--------- beginning of /dev/log/system
,W/jxcore-log(32368): Initializing JXcore engine
,W/jxcore-log(32368): JXcore engine is ready
,W/jxcore-log(32368): Starting JXcore engine
,W/jxcore-log(32368): Platform android
W/jxcore-log(32368): 
,W/jxcore-log(32368): Process ARCH arm
W/jxcore-log(32368): 
,I/jxcore-log(32368): JXcore Cordova bridge is ready!
I/jxcore-log(32368): 
,W/jxcore-log(32368): JXcore engine is started
,E/jxcore-log(32368): >> HTC-HTC Desire 820
E/jxcore-log(32368): 
,I/jxcore-log(32368): Total memory 1964650496
I/jxcore-log(32368): 
I/jxcore-log(32368): Free memory 347033600
I/jxcore-log(32368): 
I/jxcore-log(32368): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(32368): 
,I/jxcore-log(32368): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(32368): 
,I/jxcore-log(32368): userPath [ 'www' ]
I/jxcore-log(32368): 
,I/jxcore-log(32368): Size 720 1184
I/jxcore-log(32368): 
,I/jxcore-log(32368): Screen Brightness 142
I/jxcore-log(32368): 
,E/jxcore-log(32368): Dummy Error Log.
E/jxcore-log(32368): 
,I/jxcore-log(32368): getBuffer is called!!!!
I/jxcore-log(32368): 
,I/jxcore-log(32368): Bluetooth toggled
I/jxcore-log(32368): 
,I/jxcore-log(32368): WiFi toggled
I/jxcore-log(32368): 


```




