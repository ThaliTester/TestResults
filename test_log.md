#### Test 495261841e19499 Logs

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
Error: problem deploying Android apk(/home/pi/test/builder/builds/495261841e19499/build_android/android_0_495261841e19499.apk) to device 03157df360a1882a protocol failure
Terminated



Test on this node has failed but the reason wasn't the test application itself.
 Cancelling the test result on this node.

```
####Node name: thali02
Console output:
```
Error: problem deploying Android apk(/home/pi/test/builder/builds/495261841e19499/build_android/android_0_495261841e19499.apk) to device LGD7228ee9cf5b Terminated



Test on this node has failed but the reason wasn't the test application itself.
 Cancelling the test result on this node.

```
####Node name: thali03
Console output:
```
Error: problem deploying Android apk(/home/pi/test/builder/builds/495261841e19499/build_android/android_0_495261841e19499.apk) to device TA4750HV7I 2550 KB/s (16811545 bytes in 6.437s)
	pkg: /data/local/tmp/android_0_495261841e19499.apk
Terminated



Test on this node has failed but the reason wasn't the test application itself.
 Cancelling the test result on this node.

```
####Node name: thali04
####Node name: thali05
####Node name: thali06
Console output:
```
Error: problem deploying Android apk(/home/pi/test/builder/builds/495261841e19499/build_android/android_0_495261841e19499.apk) to device 022678fb504e29b0 Terminated



Test on this node has failed but the reason wasn't the test application itself.
 Cancelling the test result on this node.

```
####Node name: thali07
Console output:
```
Error: problem stopping Android apk(com.example.hello) to device 4db5c8cc Terminated
 
```
####Node name: thali08
####Node name: thali09
Console output:
```
Error! Unexpected exit on device 0c6a0f3c0bdb4e77 app:com.example.hello code:null 
child process exited with code null on device 0c6a0f3c0bdb4e77 
Error! Unexpected exit on device CC51WYC03425 app:com.example.hello code:null 
child process exited with code null on device CC51WYC03425 
Android task is completed 
```

Logcat output:
```
LGE-Nexus 5: 


HTC-HTC Desire 820: 
--------- beginning of /dev/log/main
--------- beginning of /dev/log/system
,W/jxcore-log( 4725): Initializing JXcore engine
,W/jxcore-log( 4725): JXcore engine is ready
,W/jxcore-log( 4725): Starting JXcore engine
,W/jxcore-log( 4725): Platform android
W/jxcore-log( 4725): 
,W/jxcore-log( 4725): Process ARCH arm
W/jxcore-log( 4725): 
,I/jxcore-log( 4725): JXcore Cordova bridge is ready!
I/jxcore-log( 4725): 
,W/jxcore-log( 4725): JXcore engine is started
,E/jxcore-log( 4725): >> HTC-HTC Desire 820
E/jxcore-log( 4725): 
,I/jxcore-log( 4725): Total memory 1964650496
I/jxcore-log( 4725): 
I/jxcore-log( 4725): Free memory 253804544
I/jxcore-log( 4725): 
I/jxcore-log( 4725): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4725): 
,I/jxcore-log( 4725): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4725): 
,I/jxcore-log( 4725): userPath [ 'www' ]
I/jxcore-log( 4725): 
,I/jxcore-log( 4725): Size 720 1184
I/jxcore-log( 4725): 
,I/jxcore-log( 4725): Screen Brightness 142
I/jxcore-log( 4725): 
,E/jxcore-log( 4725): Dummy Error Log.
E/jxcore-log( 4725): 
,I/jxcore-log( 4725): getBuffer is called!!!!
I/jxcore-log( 4725): 
,I/jxcore-log( 4725): Bluetooth toggled
I/jxcore-log( 4725): 
,I/jxcore-log( 4725): WiFi toggled
I/jxcore-log( 4725): 


```




