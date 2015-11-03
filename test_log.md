#### Test 49526184cc21a54 Logs

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
Error: problem deploying Android apk(/home/pi/test/builder/builds/49526184cc21a54/build_android/android_0_49526184cc21a54.apk) to device 30049d9501da2100 5639 KB/s (16811545 bytes in 2.911s)
	pkg: /data/local/tmp/android_0_49526184cc21a54.apk
Terminated



Test on this node has failed but the reason wasn't the test application itself.
 Cancelling the test result on this node.

```
####Node name: thali02
Console output:
```
Error! Unexpected exit on device 09a9416e0297d102 app:com.example.hello code:null 
child process exited with code null on device 09a9416e0297d102 
Error! Unexpected exit on device LGD7228ee9cf5b app:com.example.hello code:0 
child process exited with code 0 on device LGD7228ee9cf5b 
Android task is completed 
```

Logcat output:
```
LGE-Nexus 5: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(14426): Initializing JXcore engine
W/jxcore-log(14426): JXcore engine is ready
,W/jxcore-log(14426): Starting JXcore engine
,W/jxcore-log(14426): Platform android
W/jxcore-log(14426): 
W/jxcore-log(14426): Process ARCH arm
W/jxcore-log(14426): 
,I/jxcore-log(14426): JXcore Cordova bridge is ready!
I/jxcore-log(14426): 
,W/jxcore-log(14426): JXcore engine is started
,E/jxcore-log(14426): >> LGE-Nexus 5
E/jxcore-log(14426): 
,I/jxcore-log(14426): Total memory 1946181632
I/jxcore-log(14426): 
,I/jxcore-log(14426): Free memory 364441600
I/jxcore-log(14426): 
,I/jxcore-log(14426): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(14426): 
I/jxcore-log(14426): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(14426): 
,I/jxcore-log(14426): userPath [ 'www' ]
I/jxcore-log(14426): 
,I/jxcore-log(14426): Size 1080 1776
I/jxcore-log(14426): 
,I/jxcore-log(14426): Screen Brightness 82
I/jxcore-log(14426): 
,E/jxcore-log(14426): Dummy Error Log.
E/jxcore-log(14426): 
,I/jxcore-log(14426): getBuffer is called!!!!
I/jxcore-log(14426): 


LGE-LG-D722: 
--------- beginning of system
,--------- beginning of main
,W/jxcore-log( 7022): Initializing JXcore engine
W/jxcore-log( 7022): JXcore engine is ready
W/jxcore-log( 7022): Starting JXcore engine
,W/jxcore-log( 7022): Platform android
W/jxcore-log( 7022): 
W/jxcore-log( 7022): Process ARCH arm
W/jxcore-log( 7022): 
,I/jxcore-log( 7022): JXcore Cordova bridge is ready!
I/jxcore-log( 7022): 
W/jxcore-log( 7022): JXcore engine is started
,E/jxcore-log( 7022): >> LGE-LG-D722
E/jxcore-log( 7022): 
,I/jxcore-log( 7022): Total memory 906309632
I/jxcore-log( 7022): 
,I/jxcore-log( 7022): Free memory 33431552
I/jxcore-log( 7022): 
I/jxcore-log( 7022): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 7022): 
,I/jxcore-log( 7022): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 7022): 
,I/jxcore-log( 7022): userPath [ 'www' ]
I/jxcore-log( 7022): 
,I/jxcore-log( 7022): Size 720 1196
I/jxcore-log( 7022): 
,I/jxcore-log( 7022): Screen Brightness 255
I/jxcore-log( 7022): 
E/jxcore-log( 7022): Dummy Error Log.
E/jxcore-log( 7022): 
,I/jxcore-log( 7022): getBuffer is called!!!!
I/jxcore-log( 7022): 


```

####Node name: thali03
Console output:
```
Error: problem deploying Android apk(/home/pi/test/builder/builds/49526184cc21a54/build_android/android_0_49526184cc21a54.apk) to device 320414cd475f91e3 Terminated



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
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(29777): Initializing JXcore engine
,W/jxcore-log(29777): JXcore engine is ready
W/jxcore-log(29777): Starting JXcore engine
,W/jxcore-log(29777): Platform android
W/jxcore-log(29777): 
W/jxcore-log(29777): Process ARCH arm
W/jxcore-log(29777): 
,I/jxcore-log(29777): JXcore Cordova bridge is ready!
I/jxcore-log(29777): 
W/jxcore-log(29777): JXcore engine is started
,E/jxcore-log(29777): >> samsung-SM-N9005
E/jxcore-log(29777): 
,I/jxcore-log(29777): Total memory 2971471872
I/jxcore-log(29777): 
I/jxcore-log(29777): Free memory 593166336
I/jxcore-log(29777): 
I/jxcore-log(29777): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(29777): 
I/jxcore-log(29777): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(29777): 
,I/jxcore-log(29777): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(29777): 
,I/jxcore-log(29777): Size 1080 1920
I/jxcore-log(29777): 
,I/jxcore-log(29777): Screen Brightness 255
I/jxcore-log(29777): 
,E/jxcore-log(29777): Dummy Error Log.
E/jxcore-log(29777): 
,I/jxcore-log(29777): getBuffer is called!!!!
I/jxcore-log(29777): 


motorola-Nexus 6: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(16464): Initializing JXcore engine
W/jxcore-log(16464): JXcore engine is ready
,W/jxcore-log(16464): Starting JXcore engine
,W/jxcore-log(16464): Platform android
W/jxcore-log(16464): 
W/jxcore-log(16464): Process ARCH arm
W/jxcore-log(16464): 
,I/jxcore-log(16464): JXcore Cordova bridge is ready!
I/jxcore-log(16464): 
W/jxcore-log(16464): JXcore engine is started
,E/jxcore-log(16464): >> motorola-Nexus 6
E/jxcore-log(16464): 
I/jxcore-log(16464): Total memory 3114405888
I/jxcore-log(16464): 
I/jxcore-log(16464): Free memory 554418176
I/jxcore-log(16464): 
I/jxcore-log(16464): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(16464): 
I/jxcore-log(16464): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(16464): 
I/jxcore-log(16464): userPath [ 'www' ]
I/jxcore-log(16464): 
I/jxcore-log(16464): Size 1440 2392
I/jxcore-log(16464): 
I/jxcore-log(16464): Screen Brightness 82
I/jxcore-log(16464): 
E/jxcore-log(16464): Dummy Error Log.
E/jxcore-log(16464): 
I/jxcore-log(16464): getBuffer is called!!!!
I/jxcore-log(16464): 


```

####Node name: thali06
Console output:
```
Error! Unexpected exit on device FA55PYS00566 app:com.example.hello code:null 
child process exited with code null on device FA55PYS00566 
Error! Unexpected exit on device 7970f88c app:com.example.hello code:null 
child process exited with code null on device 7970f88c 
Error! Unexpected exit on device 022678fb504e29b0 app:com.example.hello code:null 
child process exited with code null on device 022678fb504e29b0 
Android task is completed 
```

Logcat output:
```
HTC-HTC One M8s: 


samsung-SM-A300FU: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(17855): Initializing JXcore engine
W/jxcore-log(17855): JXcore engine is ready
W/jxcore-log(17855): Starting JXcore engine
W/jxcore-log(17855): Platform android
W/jxcore-log(17855): 
W/jxcore-log(17855): Process ARCH arm
W/jxcore-log(17855): 
I/jxcore-log(17855): JXcore Cordova bridge is ready!
I/jxcore-log(17855): 
W/jxcore-log(17855): JXcore engine is started
E/jxcore-log(17855): >> samsung-SM-A300FU
E/jxcore-log(17855): 
I/jxcore-log(17855): Total memory 1451114496
I/jxcore-log(17855): 
I/jxcore-log(17855): Free memory 148537344
I/jxcore-log(17855): 
I/jxcore-log(17855): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(17855): 
I/jxcore-log(17855): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(17855): 
I/jxcore-log(17855): userPath [ 'www' ]
I/jxcore-log(17855): 
I/jxcore-log(17855): Size 540 960
I/jxcore-log(17855): 
I/jxcore-log(17855): Screen Brightness 160
I/jxcore-log(17855): 
E/jxcore-log(17855): Dummy Error Log.
E/jxcore-log(17855): 
,I/jxcore-log(17855): getBuffer is called!!!!
I/jxcore-log(17855): 


LGE-LG-D802: 
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
,W/jxcore-log(25338): Initializing JXcore engine
,W/jxcore-log(25338): JXcore engine is ready
,W/jxcore-log(25338): Starting JXcore engine
,W/jxcore-log(25338): Platform android
W/jxcore-log(25338): 
,W/jxcore-log(25338): Process ARCH arm
W/jxcore-log(25338): 
,I/jxcore-log(25338): JXcore Cordova bridge is ready!
I/jxcore-log(25338): 
,W/jxcore-log(25338): JXcore engine is started
,E/jxcore-log(25338): >> LGE-LG-D802
E/jxcore-log(25338): 
,I/jxcore-log(25338): Total memory 1943035904
I/jxcore-log(25338): 
I/jxcore-log(25338): Free memory 161685504
I/jxcore-log(25338): 
I/jxcore-log(25338): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(25338): 
,I/jxcore-log(25338): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(25338): 
,I/jxcore-log(25338): userPath [ 'www' ]
I/jxcore-log(25338): 
,I/jxcore-log(25338): Size 1080 1776
I/jxcore-log(25338): 
,I/jxcore-log(25338): Screen Brightness 255
I/jxcore-log(25338): 
,E/jxcore-log(25338): Dummy Error Log.
E/jxcore-log(25338): 
,I/jxcore-log(25338): getBuffer is called!!!!
I/jxcore-log(25338): 


```

####Node name: thali07
####Node name: thali08
####Node name: thali09
Console output:
```
Error! Unexpected exit on device 0c6a0f3c0bdb4e77 app:com.example.hello code:null 
child process exited with code null on device 0c6a0f3c0bdb4e77 
Android task is completed 
```

Logcat output:
```
LGE-Nexus 5: 


HTC-HTC Desire 820: 
--------- beginning of /dev/log/system
--------- beginning of /dev/log/main
,W/jxcore-log( 1932): Initializing JXcore engine
,W/jxcore-log( 1932): JXcore engine is ready
,W/jxcore-log( 1932): Starting JXcore engine
,W/jxcore-log( 1932): Platform android
W/jxcore-log( 1932): 
,W/jxcore-log( 1932): Process ARCH arm
W/jxcore-log( 1932): 
,I/jxcore-log( 1932): JXcore Cordova bridge is ready!
I/jxcore-log( 1932): 
,W/jxcore-log( 1932): JXcore engine is started
,E/jxcore-log( 1932): >> HTC-HTC Desire 820
E/jxcore-log( 1932): 
,I/jxcore-log( 1932): Total memory 1964650496
I/jxcore-log( 1932): 
I/jxcore-log( 1932): Free memory 324648960
I/jxcore-log( 1932): 
I/jxcore-log( 1932): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 1932): 
,I/jxcore-log( 1932): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 1932): 
,I/jxcore-log( 1932): userPath [ 'www' ]
I/jxcore-log( 1932): 
,I/jxcore-log( 1932): Size 720 1184
I/jxcore-log( 1932): 
,I/jxcore-log( 1932): Screen Brightness 142
I/jxcore-log( 1932): 
,E/jxcore-log( 1932): Dummy Error Log.
E/jxcore-log( 1932): 
,I/jxcore-log( 1932): getBuffer is called!!!!
I/jxcore-log( 1932): 
,I/jxcore-log( 1932): Bluetooth toggled
I/jxcore-log( 1932): 
,I/jxcore-log( 1932): WiFi toggled
I/jxcore-log( 1932): 
,I/jxcore-log( 1932): Response status code was: 200
I/jxcore-log( 1932): 
,I/jxcore-log( 1932): ****TEST TOOK:  11380  ms ****
I/jxcore-log( 1932): 
,I/jxcore-log( 1932): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 1932): 
,I/jxcore-log( 1932): Response status code was: 200
I/jxcore-log( 1932): 
I/jxcore-log( 1932): ****TEST TOOK:  11394  ms ****
I/jxcore-log( 1932): 
I/jxcore-log( 1932): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 1932): 
I/jxcore-log( 1932): Response status code was: 200
I/jxcore-log( 1932): 
I/jxcore-log( 1932): ****TEST TOOK:  11403  ms ****
I/jxcore-log( 1932): 
I/jxcore-log( 1932): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 1932): 
I/jxcore-log( 1932): Response status code was: 200
I/jxcore-log( 1932): 
I/jxcore-log( 1932): ****TEST TOOK:  11406  ms ****
I/jxcore-log( 1932): 
I/jxcore-log( 1932): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 1932): 


```




