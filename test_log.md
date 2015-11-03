#### Test 49526184791338a Logs

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
Error: problem deploying Android apk(/home/pi/test/builder/builds/49526184791338a/build_android/android_0_49526184791338a.apk) to device 30049d9501da2100 5508 KB/s (16811545 bytes in 2.980s)
	pkg: /data/local/tmp/android_0_49526184791338a.apk
Terminated



Test on this node has failed but the reason wasn't the test application itself.
 Cancelling the test result on this node.

```
####Node name: thali02
Console output:
```
Error! Unexpected exit on device 09a9416e0297d102 app:com.example.hello code:null 
child process exited with code null on device 09a9416e0297d102 
Device test finished on LGD7228ee9cf5b 
Android task is completed 
```

Logcat output:
```
LGE-Nexus 5: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(16008): Initializing JXcore engine
W/jxcore-log(16008): JXcore engine is ready
,W/jxcore-log(16008): Starting JXcore engine
,W/jxcore-log(16008): Platform android
W/jxcore-log(16008): 
W/jxcore-log(16008): Process ARCH arm
W/jxcore-log(16008): 
,I/jxcore-log(16008): JXcore Cordova bridge is ready!
I/jxcore-log(16008): 
W/jxcore-log(16008): JXcore engine is started
,E/jxcore-log(16008): >> LGE-Nexus 5
E/jxcore-log(16008): 
I/jxcore-log(16008): Total memory 1946181632
I/jxcore-log(16008): 
I/jxcore-log(16008): Free memory 300085248
I/jxcore-log(16008): 
I/jxcore-log(16008): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(16008): 
I/jxcore-log(16008): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(16008): 
,I/jxcore-log(16008): userPath [ 'www' ]
I/jxcore-log(16008): 
,I/jxcore-log(16008): Size 1080 1776
I/jxcore-log(16008): 
,I/jxcore-log(16008): Screen Brightness 82
I/jxcore-log(16008): 
,E/jxcore-log(16008): Dummy Error Log.
E/jxcore-log(16008): 
,I/jxcore-log(16008): getBuffer is called!!!!
I/jxcore-log(16008): 
,I/jxcore-log(16008): Bluetooth toggled
I/jxcore-log(16008): 
,I/jxcore-log(16008): WiFi toggled
I/jxcore-log(16008): 


LGE-LG-D722: 
--------- beginning of system
,--------- beginning of main
,W/jxcore-log( 9964): Initializing JXcore engine
W/jxcore-log( 9964): JXcore engine is ready
,W/jxcore-log( 9964): Starting JXcore engine
,W/jxcore-log( 9964): Platform android
W/jxcore-log( 9964): 
W/jxcore-log( 9964): Process ARCH arm
W/jxcore-log( 9964): 
,I/jxcore-log( 9964): JXcore Cordova bridge is ready!
I/jxcore-log( 9964): 
,W/jxcore-log( 9964): JXcore engine is started
,E/jxcore-log( 9964): >> LGE-LG-D722
E/jxcore-log( 9964): 
I/jxcore-log( 9964): Total memory 906309632
I/jxcore-log( 9964): 
I/jxcore-log( 9964): Free memory 20697088
I/jxcore-log( 9964): 
I/jxcore-log( 9964): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 9964): 
,I/jxcore-log( 9964): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 9964): 
I/jxcore-log( 9964): userPath [ 'www' ]
I/jxcore-log( 9964): 
I/jxcore-log( 9964): Size 720 1196
I/jxcore-log( 9964): 
I/jxcore-log( 9964): Screen Brightness 255
I/jxcore-log( 9964): 
E/jxcore-log( 9964): Dummy Error Log.
E/jxcore-log( 9964): 
I/jxcore-log( 9964): getBuffer is called!!!!
I/jxcore-log( 9964): 
,I/jxcore-log( 9964): Bluetooth toggled
I/jxcore-log( 9964): 
,I/jxcore-log( 9964): WiFi toggled
I/jxcore-log( 9964): 
,I/jxcore-log( 9964): Response status code was: 200
I/jxcore-log( 9964): 
,I/jxcore-log( 9964): ****TEST TOOK:  6382  ms ****
I/jxcore-log( 9964): 
I/jxcore-log( 9964): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 9964): 


```

####Node name: thali03
Console output:
```
Error: problem deploying Android apk(/home/pi/test/builder/builds/49526184791338a/build_android/android_0_49526184791338a.apk) to device 320414cd475f91e3 3273 KB/s (16811545 bytes in 5.014s)
	pkg: /data/local/tmp/android_0_49526184791338a.apk
Terminated



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
--------- beginning of system,
--------- beginning of main
,W/jxcore-log(22784): Initializing JXcore engine
,W/jxcore-log(22784): JXcore engine is ready
,W/jxcore-log(22784): Starting JXcore engine
,W/jxcore-log(22784): Platform android
W/jxcore-log(22784): 
,W/jxcore-log(22784): Process ARCH arm
W/jxcore-log(22784): 
,I/jxcore-log(22784): JXcore Cordova bridge is ready!,
I/jxcore-log(22784): 
W/jxcore-log(22784): JXcore engine is started
,E/jxcore-log(22784): >> HTC-HTC One_M8,
E/jxcore-log(22784): 
I/jxcore-log(22784): Total memory 1912020992
I/jxcore-log(22784): 
I/jxcore-log(22784): Free memory 426561536
I/jxcore-log(22784): 
I/jxcore-log(22784): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(22784): 
I/jxcore-log(22784): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(22784): 
,I/jxcore-log(22784): userPath [ 'www' ],
I/jxcore-log(22784): 
,I/jxcore-log(22784): Size 1080 1776
I/jxcore-log(22784): 
,I/jxcore-log(22784): Screen Brightness 142
I/jxcore-log(22784): ,
E/jxcore-log(22784): Dummy Error Log.
E/jxcore-log(22784): 
,I/jxcore-log(22784): getBuffer is called!!!!
I/jxcore-log(22784): 


samsung-SM-N9005: 
--------- beginning of system
,--------- beginning of main
,W/jxcore-log(30349): Initializing JXcore engine,
,W/jxcore-log(30349): JXcore engine is ready,
,W/jxcore-log(30349): Starting JXcore engine
,W/jxcore-log(30349): Platform android
W/jxcore-log(30349): 
W/jxcore-log(30349): Process ARCH arm
W/jxcore-log(30349): 
,I/jxcore-log(30349): JXcore Cordova bridge is ready!
I/jxcore-log(30349): 
W/jxcore-log(30349): JXcore engine is started
,E/jxcore-log(30349): >> samsung-SM-N9005
E/jxcore-log(30349): 
,I/jxcore-log(30349): Total memory 2971471872
I/jxcore-log(30349): 
,I/jxcore-log(30349): Free memory 569409536
I/jxcore-log(30349): 
I/jxcore-log(30349): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(30349): 
,I/jxcore-log(30349): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(30349): 
,I/jxcore-log(30349): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(30349): 
,I/jxcore-log(30349): Size 1080 1920
I/jxcore-log(30349): 
,I/jxcore-log(30349): Screen Brightness 255
I/jxcore-log(30349): 
,E/jxcore-log(30349): Dummy Error Log.
E/jxcore-log(30349): 
,I/jxcore-log(30349): getBuffer is called!!!!
I/jxcore-log(30349): 
,I/jxcore-log(30349): Bluetooth toggled
I/jxcore-log(30349): 
,I/jxcore-log(30349): WiFi toggled
I/jxcore-log(30349): 


motorola-Nexus 6: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(17118): Initializing JXcore engine
,W/jxcore-log(17118): JXcore engine is ready
,W/jxcore-log(17118): Starting JXcore engine
,W/jxcore-log(17118): Platform android
W/jxcore-log(17118): 
,W/jxcore-log(17118): Process ARCH arm
W/jxcore-log(17118): 
,I/jxcore-log(17118): JXcore Cordova bridge is ready!
I/jxcore-log(17118): 
W/jxcore-log(17118): JXcore engine is started
,E/jxcore-log(17118): >> motorola-Nexus 6
E/jxcore-log(17118): 
I/jxcore-log(17118): Total memory 3114405888
I/jxcore-log(17118): 
I/jxcore-log(17118): Free memory 539893760
I/jxcore-log(17118): 
I/jxcore-log(17118): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(17118): 
I/jxcore-log(17118): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(17118): 
I/jxcore-log(17118): userPath [ 'www' ]
I/jxcore-log(17118): 
,I/jxcore-log(17118): Size 1440 2392
I/jxcore-log(17118): 
,I/jxcore-log(17118): Screen Brightness 82
I/jxcore-log(17118): 
,E/jxcore-log(17118): Dummy Error Log.
E/jxcore-log(17118): 
,I/jxcore-log(17118): getBuffer is called!!!!
I/jxcore-log(17118): 
,I/jxcore-log(17118): Bluetooth toggled
I/jxcore-log(17118): 
,I/jxcore-log(17118): WiFi toggled
I/jxcore-log(17118): 


```

####Node name: thali06
Console output:
```
STOP log received from  022678fb504e29b0 Test has  SUCCEEDED
Error! Unexpected exit on device FA55PYS00566 app:com.example.hello code:null 
child process exited with code null on device FA55PYS00566 
Error! Unexpected exit on device 7970f88c app:com.example.hello code:null 
child process exited with code null on device 7970f88c 
Device test finished on 022678fb504e29b0 
Android task is completed 
```

Logcat output:
```
HTC-HTC One M8s: 


samsung-SM-A300FU: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(20588): Initializing JXcore engine
W/jxcore-log(20588): JXcore engine is ready
,W/jxcore-log(20588): Starting JXcore engine
,W/jxcore-log(20588): Platform android
W/jxcore-log(20588): 
W/jxcore-log(20588): Process ARCH arm
W/jxcore-log(20588): 
,I/jxcore-log(20588): JXcore Cordova bridge is ready!
I/jxcore-log(20588): 
,W/jxcore-log(20588): JXcore engine is started
,E/jxcore-log(20588): >> samsung-SM-A300FU
E/jxcore-log(20588): 
,I/jxcore-log(20588): Total memory 1451114496
I/jxcore-log(20588): 
,I/jxcore-log(20588): Free memory 45277184
I/jxcore-log(20588): 
I/jxcore-log(20588): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(20588): 
I/jxcore-log(20588): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(20588): 
,I/jxcore-log(20588): userPath [ 'www' ]
I/jxcore-log(20588): 
,I/jxcore-log(20588): Size 540 960
I/jxcore-log(20588): 
,I/jxcore-log(20588): Screen Brightness 160
I/jxcore-log(20588): 
,E/jxcore-log(20588): Dummy Error Log.
E/jxcore-log(20588): 
,I/jxcore-log(20588): getBuffer is called!!!!
I/jxcore-log(20588): 
,I/jxcore-log(20588): Bluetooth toggled
I/jxcore-log(20588): 
,I/jxcore-log(20588): WiFi toggled
I/jxcore-log(20588): 


LGE-LG-D802: 
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
,W/jxcore-log(28611): Initializing JXcore engine
W/jxcore-log(28611): JXcore engine is ready
W/jxcore-log(28611): Starting JXcore engine
W/jxcore-log(28611): Platform android
W/jxcore-log(28611): 
W/jxcore-log(28611): Process ARCH arm
W/jxcore-log(28611): 
I/jxcore-log(28611): JXcore Cordova bridge is ready!
I/jxcore-log(28611): 
W/jxcore-log(28611): JXcore engine is started
,E/jxcore-log(28611): >> LGE-LG-D802
E/jxcore-log(28611): 
,I/jxcore-log(28611): Total memory 1943035904
I/jxcore-log(28611): 
I/jxcore-log(28611): Free memory 166805504
I/jxcore-log(28611): 
I/jxcore-log(28611): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(28611): 
,I/jxcore-log(28611): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(28611): 
,I/jxcore-log(28611): userPath [ 'www' ]
I/jxcore-log(28611): 
,I/jxcore-log(28611): Size 1080 1776
I/jxcore-log(28611): 
,I/jxcore-log(28611): Screen Brightness 255
I/jxcore-log(28611): 
,E/jxcore-log(28611): Dummy Error Log.
E/jxcore-log(28611): 
,I/jxcore-log(28611): getBuffer is called!!!!
I/jxcore-log(28611): 
,I/jxcore-log(28611): Bluetooth toggled
I/jxcore-log(28611): 
,I/jxcore-log(28611): WiFi toggled
I/jxcore-log(28611): 
,I/jxcore-log(28611): Response status code was: 200
I/jxcore-log(28611): 
,I/jxcore-log(28611): ****TEST TOOK:  6491  ms ****
I/jxcore-log(28611): 
,I/jxcore-log(28611): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(28611): 


```

####Node name: thali07
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
--------- beginning of system
,--------- beginning of main
,W/jxcore-log(26698): Initializing JXcore engine
,W/jxcore-log(26698): JXcore engine is ready
,W/jxcore-log(26698): Starting JXcore engine
,W/jxcore-log(26698): Platform android
W/jxcore-log(26698): 
,W/jxcore-log(26698): Process ARCH arm
W/jxcore-log(26698): 
,I/jxcore-log(26698): JXcore Cordova bridge is ready!
I/jxcore-log(26698): 
,W/jxcore-log(26698): JXcore engine is started
,E/jxcore-log(26698): >> samsung-SM-A300FU
E/jxcore-log(26698): 
,I/jxcore-log(26698): Total memory 1451114496
I/jxcore-log(26698): 
,I/jxcore-log(26698): Free memory 32477184
I/jxcore-log(26698): 
I/jxcore-log(26698): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(26698): 
I/jxcore-log(26698): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(26698): 
,I/jxcore-log(26698): userPath [ 'www' ]
I/jxcore-log(26698): 
,I/jxcore-log(26698): Size 540 960
I/jxcore-log(26698): 
,I/jxcore-log(26698): Screen Brightness 255
I/jxcore-log(26698): 
,E/jxcore-log(26698): Dummy Error Log.
E/jxcore-log(26698): 
,I/jxcore-log(26698): getBuffer is called!!!!
I/jxcore-log(26698): 
,I/jxcore-log(26698): Bluetooth toggled
I/jxcore-log(26698): 
,I/jxcore-log(26698): WiFi toggled
I/jxcore-log(26698): 
,I/jxcore-log(26698): Response status code was: 200
I/jxcore-log(26698): 
,I/jxcore-log(26698): ****TEST TOOK:  6303  ms ****
I/jxcore-log(26698): 
I/jxcore-log(26698): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(26698): 


HTC-HTC Desire 820: 
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
,W/jxcore-log( 8991): Initializing JXcore engine
W/jxcore-log( 8991): JXcore engine is ready
W/jxcore-log( 8991): Starting JXcore engine
W/jxcore-log( 8991): Platform android
W/jxcore-log( 8991): 
W/jxcore-log( 8991): Process ARCH arm
W/jxcore-log( 8991): 
I/jxcore-log( 8991): JXcore Cordova bridge is ready!
I/jxcore-log( 8991): 
W/jxcore-log( 8991): JXcore engine is started
E/jxcore-log( 8991): >> HTC-HTC Desire 820
E/jxcore-log( 8991): 
I/jxcore-log( 8991): Total memory 1964650496
I/jxcore-log( 8991): 
I/jxcore-log( 8991): Free memory 204271616
I/jxcore-log( 8991): 
I/jxcore-log( 8991): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 8991): 
I/jxcore-log( 8991): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 8991): 
I/jxcore-log( 8991): userPath [ 'www' ]
I/jxcore-log( 8991): 
I/jxcore-log( 8991): Size 720 1184
I/jxcore-log( 8991): 
I/jxcore-log( 8991): Screen Brightness 10
I/jxcore-log( 8991): 
E/jxcore-log( 8991): Dummy Error Log.
E/jxcore-log( 8991): 
,I/jxcore-log( 8991): getBuffer is called!!!!
I/jxcore-log( 8991): 
,I/jxcore-log( 8991): Bluetooth toggled
I/jxcore-log( 8991): 
,I/jxcore-log( 8991): WiFi toggled
I/jxcore-log( 8991): 
,I/jxcore-log( 8991): Response status code was: 200
I/jxcore-log( 8991): 
I/jxcore-log( 8991): ****TEST TOOK:  6341  ms ****
I/jxcore-log( 8991): 
,I/jxcore-log( 8991): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 8991): 


```

####Node name: thali09
Console output:
```
STOP log received from  CC51WYC03425 Test has  SUCCEEDED
Device test finished on CC51WYC03425 
STOP log received from  0c6a0f3c0bdb4e77 Test has  SUCCEEDED
Device test finished on 0c6a0f3c0bdb4e77 
Android task is completed 
```

Logcat output:
```
LGE-Nexus 5: 
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
,W/jxcore-log(14665): Initializing JXcore engine
,W/jxcore-log(14665): JXcore engine is ready
,W/jxcore-log(14665): Starting JXcore engine
,W/jxcore-log(14665): Platform android
W/jxcore-log(14665): 
,W/jxcore-log(14665): Process ARCH arm
W/jxcore-log(14665): 
,I/jxcore-log(14665): JXcore Cordova bridge is ready!
I/jxcore-log(14665): 
,W/jxcore-log(14665): JXcore engine is started
,E/jxcore-log(14665): >> LGE-Nexus 5
E/jxcore-log(14665): 
,I/jxcore-log(14665): Total memory 1945137152
I/jxcore-log(14665): 
I/jxcore-log(14665): Free memory 480227328
I/jxcore-log(14665): 
,I/jxcore-log(14665): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(14665): 
,I/jxcore-log(14665): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(14665): 
,I/jxcore-log(14665): userPath [ 'www' ]
I/jxcore-log(14665): 
,I/jxcore-log(14665): Size 1080 1776
I/jxcore-log(14665): 
,I/jxcore-log(14665): Screen Brightness 82
I/jxcore-log(14665): 
,E/jxcore-log(14665): Dummy Error Log.
E/jxcore-log(14665): 
,I/jxcore-log(14665): getBuffer is called!!!!
I/jxcore-log(14665): 
,I/jxcore-log(14665): Bluetooth toggled
I/jxcore-log(14665): 
,I/jxcore-log(14665): WiFi toggled
I/jxcore-log(14665): 
,I/jxcore-log(14665): Response status code was: 200
I/jxcore-log(14665): 
I/jxcore-log(14665): ****TEST TOOK:  6334  ms ****
I/jxcore-log(14665): 
,I/jxcore-log(14665): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(14665): 


HTC-HTC Desire 820: 
--------- beginning of /dev/log/system
,--------- beginning of /dev/log/main
,W/jxcore-log( 2221): Initializing JXcore engine
,W/jxcore-log( 2221): JXcore engine is ready
,W/jxcore-log( 2221): Starting JXcore engine
,W/jxcore-log( 2221): Platform android
W/jxcore-log( 2221): 
,W/jxcore-log( 2221): Process ARCH arm
W/jxcore-log( 2221): 
,I/jxcore-log( 2221): JXcore Cordova bridge is ready!
I/jxcore-log( 2221): 
,W/jxcore-log( 2221): JXcore engine is started
,E/jxcore-log( 2221): >> HTC-HTC Desire 820
E/jxcore-log( 2221): 
,I/jxcore-log( 2221): Total memory 1964650496
I/jxcore-log( 2221): 
I/jxcore-log( 2221): Free memory 323133440
I/jxcore-log( 2221): 
,I/jxcore-log( 2221): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2221): 
,I/jxcore-log( 2221): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2221): 
,I/jxcore-log( 2221): userPath [ 'www' ]
I/jxcore-log( 2221): 
,I/jxcore-log( 2221): Size 720 1184
I/jxcore-log( 2221): 
,I/jxcore-log( 2221): Screen Brightness 142
I/jxcore-log( 2221): 
,E/jxcore-log( 2221): Dummy Error Log.
E/jxcore-log( 2221): 
,I/jxcore-log( 2221): getBuffer is called!!!!
I/jxcore-log( 2221): 
,I/jxcore-log( 2221): Bluetooth toggled
I/jxcore-log( 2221): 
,I/jxcore-log( 2221): WiFi toggled
I/jxcore-log( 2221): 
,I/jxcore-log( 2221): Response status code was: 200
I/jxcore-log( 2221): 
,I/jxcore-log( 2221): ****TEST TOOK:  6350  ms ****
I/jxcore-log( 2221): 
,I/jxcore-log( 2221): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2221): 


```




