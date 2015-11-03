#### Test 49526184d88d809 Logs

Status: 
```

server : IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":23,"cancel":1}}
Integration server has received  [ 'jx',
  '/home/pi/Test/server_49526184d88d809/Sub/serverApp/index.js',
  '{"devices":{"android":23,"cancel":1}}' ]

JSON { devices: { android: 23, cancel: 1 } }



android : Error: Command failed: Error: Command failed: run_.sh aborted
 [0m


```
###Android Logs
####Node name: thali01
Console output:
```
STOP log received from  03157df360a1882a Test has  SUCCEEDED
STOP log received from  W3D7N15428022572 Test has  SUCCEEDED
Device test finished on 03157df360a1882a 
Device test finished on W3D7N15428022572 
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
Device test finished on LGH8153b36be34 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 30049d9501da2100 app:com.example.hello code:null 
child process exited with code null on device 30049d9501da2100 
Android task is completed 
```

Logcat output:
```
samsung-SM-G920F: 
--------- beginning of system
,--------- beginning of main
,W/jxcore-log(32081): Initializing JXcore engine
W/jxcore-log(32081): JXcore engine is ready
,W/jxcore-log(32081): Starting JXcore engine
,W/jxcore-log(32081): Platform android
W/jxcore-log(32081): 
W/jxcore-log(32081): Process ARCH arm
W/jxcore-log(32081): 
,I/jxcore-log(32081): JXcore Cordova bridge is ready!
I/jxcore-log(32081): 
W/jxcore-log(32081): JXcore engine is started
,E/jxcore-log(32081): >> samsung-SM-G920F
E/jxcore-log(32081): 
,I/jxcore-log(32081): Total memory 2829074432
I/jxcore-log(32081): 
I/jxcore-log(32081): Free memory 281620480
I/jxcore-log(32081): 
I/jxcore-log(32081): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(32081): 
I/jxcore-log(32081): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(32081): 
,I/jxcore-log(32081): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(32081): 
,I/jxcore-log(32081): Size 1440 2560
I/jxcore-log(32081): 
,I/jxcore-log(32081): Screen Brightness 255
I/jxcore-log(32081): 
E/jxcore-log(32081): Dummy Error Log.
E/jxcore-log(32081): 
,I/jxcore-log(32081): getBuffer is called!!!!
I/jxcore-log(32081): 
,I/jxcore-log(32081): Bluetooth toggled
I/jxcore-log(32081): 
,I/jxcore-log(32081): WiFi toggled
I/jxcore-log(32081): 
,I/jxcore-log(32081): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32081): 
,I/jxcore-log(32081): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32081): 
,I/jxcore-log(32081): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32081): 
,I/jxcore-log(32081): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32081): 
,I/jxcore-log(32081): Response status code was: 200
I/jxcore-log(32081): 
,I/jxcore-log(32081): ****TEST TOOK:  10400  ms ****
I/jxcore-log(32081): 
I/jxcore-log(32081): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(32081): 


samsung-SM-T232: 
--------- beginning of /dev/log/system
,--------- beginning of /dev/log/main
,W/jxcore-log( 2816): Initializing JXcore engine
W/jxcore-log( 2816): JXcore engine is ready
W/jxcore-log( 2816): Starting JXcore engine
,W/jxcore-log( 2816): Platform android
W/jxcore-log( 2816): 
W/jxcore-log( 2816): Process ARCH arm
W/jxcore-log( 2816): 
I/jxcore-log( 2816): JXcore Cordova bridge is ready!
I/jxcore-log( 2816): 
W/jxcore-log( 2816): JXcore engine is started
E/jxcore-log( 2816): >> samsung-SM-T232
E/jxcore-log( 2816): 
I/jxcore-log( 2816): Total memory 1352024064
I/jxcore-log( 2816): 
I/jxcore-log( 2816): Free memory 100175872
I/jxcore-log( 2816): 
I/jxcore-log( 2816): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2816): 
I/jxcore-log( 2816): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2816): 
I/jxcore-log( 2816): userPath [ 'www' ]
I/jxcore-log( 2816): 
I/jxcore-log( 2816): Size 800 1280
I/jxcore-log( 2816): 
I/jxcore-log( 2816): Screen Brightness 255
I/jxcore-log( 2816): 
E/jxcore-log( 2816): Dummy Error Log.
E/jxcore-log( 2816): 
,I/jxcore-log( 2816): getBuffer is called!!!!
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Bluetooth toggled
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): WiFi toggled
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
,TIME-OUT KILL (timeout was 1200000ms),I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 
I/jxcore-log( 2816): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2816): 


LGE-LG-H815: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log( 6808): Initializing JXcore engine
W/jxcore-log( 6808): JXcore engine is ready
,W/jxcore-log( 6808): Starting JXcore engine
,W/jxcore-log( 6808): Platform android
W/jxcore-log( 6808): 
W/jxcore-log( 6808): Process ARCH arm
W/jxcore-log( 6808): 
,I/jxcore-log( 6808): JXcore Cordova bridge is ready!
I/jxcore-log( 6808): 
,W/jxcore-log( 6808): JXcore engine is started
,E/jxcore-log( 6808): >> LGE-LG-H815
E/jxcore-log( 6808): 
,I/jxcore-log( 6808): Total memory 2968948736
I/jxcore-log( 6808): 
,I/jxcore-log( 6808): Free memory 759066624
I/jxcore-log( 6808): 
I/jxcore-log( 6808): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6808): 
I/jxcore-log( 6808): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6808): 
,I/jxcore-log( 6808): userPath [ 'www' ]
I/jxcore-log( 6808): 
,I/jxcore-log( 6808): Size 1440 2392
I/jxcore-log( 6808): 
I/jxcore-log( 6808): Screen Brightness 255
I/jxcore-log( 6808): 
E/jxcore-log( 6808): Dummy Error Log.
E/jxcore-log( 6808): 
,I/jxcore-log( 6808): getBuffer is called!!!!
I/jxcore-log( 6808): 
,I/jxcore-log( 6808): Bluetooth toggled
I/jxcore-log( 6808): 
,I/jxcore-log( 6808): WiFi toggled
I/jxcore-log( 6808): 
,I/jxcore-log( 6808): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 6808): 
,I/jxcore-log( 6808): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 6808): 
,I/jxcore-log( 6808): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 6808): 
,I/jxcore-log( 6808): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 6808): 
,I/jxcore-log( 6808): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 6808): 
,I/jxcore-log( 6808): Response status code was: 200
I/jxcore-log( 6808): 
I/jxcore-log( 6808): ****TEST TOOK:  11627  ms ****
I/jxcore-log( 6808): 
I/jxcore-log( 6808): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6808): 


HUAWEI-ALE-L21: 
int logctl_get(): open '/dev/hwlog_switch' fail -1, 13. Permission denied

Note: log switch off, only log_main and log_events will have logs!
,--------- beginning of main
,W/jxcore-log( 9373): Initializing JXcore engine
W/jxcore-log( 9373): JXcore engine is ready
W/jxcore-log( 9373): Starting JXcore engine
,W/jxcore-log( 9373): Platform android
W/jxcore-log( 9373): 
W/jxcore-log( 9373): Process ARCH arm
W/jxcore-log( 9373): 
,I/jxcore-log( 9373): JXcore Cordova bridge is ready!
I/jxcore-log( 9373): 
W/jxcore-log( 9373): JXcore engine is started
,E/jxcore-log( 9373): >> HUAWEI-ALE-L21
E/jxcore-log( 9373): 
,I/jxcore-log( 9373): Total memory 1949741056
I/jxcore-log( 9373): 
,I/jxcore-log( 9373): Free memory 323555328
I/jxcore-log( 9373): 
I/jxcore-log( 9373): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 9373): 
I/jxcore-log( 9373): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 9373): 
,I/jxcore-log( 9373): userPath [ 'www' ]
I/jxcore-log( 9373): 
,I/jxcore-log( 9373): Size 720 1184
I/jxcore-log( 9373): 
,I/jxcore-log( 9373): Screen Brightness 242
I/jxcore-log( 9373): 
,E/jxcore-log( 9373): Dummy Error Log.
E/jxcore-log( 9373): 
,I/jxcore-log( 9373): getBuffer is called!!!!
I/jxcore-log( 9373): 
,I/jxcore-log( 9373): Bluetooth toggled
I/jxcore-log( 9373): 
,I/jxcore-log( 9373): WiFi toggled
I/jxcore-log( 9373): 
,I/jxcore-log( 9373): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 9373): 
,I/jxcore-log( 9373): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 9373): 
,I/jxcore-log( 9373): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 9373): 
,I/jxcore-log( 9373): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 9373): 
,I/jxcore-log( 9373): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 9373): 
,I/jxcore-log( 9373): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 9373): 
,I/jxcore-log( 9373): Response status code was: 200
I/jxcore-log( 9373): 
I/jxcore-log( 9373): ****TEST TOOK:  12531  ms ****
I/jxcore-log( 9373): 
I/jxcore-log( 9373): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 9373): 


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
,W/jxcore-log(19032): Initializing JXcore engine
W/jxcore-log(19032): JXcore engine is ready
,W/jxcore-log(19032): Starting JXcore engine
,W/jxcore-log(19032): Platform android
W/jxcore-log(19032): 
W/jxcore-log(19032): Process ARCH arm
W/jxcore-log(19032): 
,I/jxcore-log(19032): JXcore Cordova bridge is ready!
I/jxcore-log(19032): 
,W/jxcore-log(19032): JXcore engine is started
,E/jxcore-log(19032): >> LGE-Nexus 5
E/jxcore-log(19032): 
,I/jxcore-log(19032): Total memory 1946181632
I/jxcore-log(19032): 
I/jxcore-log(19032): Free memory 321781760
I/jxcore-log(19032): 
I/jxcore-log(19032): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(19032): 
I/jxcore-log(19032): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(19032): 
,I/jxcore-log(19032): userPath [ 'www' ]
I/jxcore-log(19032): 
,I/jxcore-log(19032): Size 1080 1776
I/jxcore-log(19032): 
,I/jxcore-log(19032): Screen Brightness 82
I/jxcore-log(19032): 
,E/jxcore-log(19032): Dummy Error Log.
E/jxcore-log(19032): 
,I/jxcore-log(19032): getBuffer is called!!!!
I/jxcore-log(19032): 
,I/jxcore-log(19032): Bluetooth toggled
I/jxcore-log(19032): 
,I/jxcore-log(19032): WiFi toggled
I/jxcore-log(19032): 
,I/jxcore-log(19032): Response status code was: 200
I/jxcore-log(19032): 
,I/jxcore-log(19032): ****TEST TOOK:  6548  ms ****
I/jxcore-log(19032): 
,I/jxcore-log(19032): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(19032): 


LGE-LG-D722: 
--------- beginning of system
--------- beginning of main
,W/jxcore-log(22236): Initializing JXcore engine
W/jxcore-log(22236): JXcore engine is ready
,W/jxcore-log(22236): Starting JXcore engine
,W/jxcore-log(22236): Platform android
W/jxcore-log(22236): 
W/jxcore-log(22236): Process ARCH arm
W/jxcore-log(22236): 
,I/jxcore-log(22236): JXcore Cordova bridge is ready!
I/jxcore-log(22236): 
W/jxcore-log(22236): JXcore engine is started
,E/jxcore-log(22236): >> LGE-LG-D722
E/jxcore-log(22236): 
I/jxcore-log(22236): Total memory 906309632
I/jxcore-log(22236): 
,I/jxcore-log(22236): Free memory 26001408
I/jxcore-log(22236): 
I/jxcore-log(22236): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(22236): 
I/jxcore-log(22236): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(22236): 
I/jxcore-log(22236): userPath [ 'www' ]
I/jxcore-log(22236): 
I/jxcore-log(22236): Size 720 1196
I/jxcore-log(22236): 
I/jxcore-log(22236): Screen Brightness 255
I/jxcore-log(22236): 
E/jxcore-log(22236): Dummy Error Log.
E/jxcore-log(22236): 
,I/jxcore-log(22236): getBuffer is called!!!!
I/jxcore-log(22236): 
,I/jxcore-log(22236): Bluetooth toggled
I/jxcore-log(22236): 
,I/jxcore-log(22236): WiFi toggled
I/jxcore-log(22236): 
,I/jxcore-log(22236): Response status code was: 200
I/jxcore-log(22236): 
I/jxcore-log(22236): ****TEST TOOK:  6552  ms ****
I/jxcore-log(22236): 
I/jxcore-log(22236): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(22236): 


```

####Node name: thali03
Console output:
```
STOP log received from  LGD8553bed2d08 Test has  SUCCEEDED
STOP log received from  320414cd475f91e3 Test has  SUCCEEDED
Device test finished on LGD8553bed2d08 
Device test finished on 320414cd475f91e3 
STOP log received from  TA4750HV7I Test has  SUCCEEDED
Device test finished on TA4750HV7I 
Android task is completed 
```

Logcat output:
```
motorola-XT1039: 
--------- beginning of /dev/log/system
,--------- beginning of /dev/log/main
,W/jxcore-log(18806): Initializing JXcore engine
,W/jxcore-log(18806): JXcore engine is ready
,W/jxcore-log(18806): Starting JXcore engine
,W/jxcore-log(18806): Platform android
W/jxcore-log(18806): 
,W/jxcore-log(18806): Process ARCH arm
W/jxcore-log(18806): 
,I/jxcore-log(18806): JXcore Cordova bridge is ready!
I/jxcore-log(18806): 
,W/jxcore-log(18806): JXcore engine is started
,E/jxcore-log(18806): >> motorola-XT1039
E/jxcore-log(18806): 
,I/jxcore-log(18806): Total memory 893136896
I/jxcore-log(18806): 
I/jxcore-log(18806): Free memory 31125504
I/jxcore-log(18806): 
I/jxcore-log(18806): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(18806): 
,I/jxcore-log(18806): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(18806): 
I/jxcore-log(18806): userPath [ 'www' ]
I/jxcore-log(18806): 
I/jxcore-log(18806): Size 720 1184
I/jxcore-log(18806): 
I/jxcore-log(18806): Screen Brightness 210
I/jxcore-log(18806): 
E/jxcore-log(18806): Dummy Error Log.
E/jxcore-log(18806): 
,I/jxcore-log(18806): getBuffer is called!!!!
I/jxcore-log(18806): 
,I/jxcore-log(18806): Bluetooth toggled
I/jxcore-log(18806): 
,I/jxcore-log(18806): WiFi toggled
I/jxcore-log(18806): 
,I/jxcore-log(18806): Response status code was: 200
I/jxcore-log(18806): 
,I/jxcore-log(18806): ****TEST TOOK:  10489  ms ****
I/jxcore-log(18806): 
,I/jxcore-log(18806): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(18806): 


LGE-LG-D855: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(30860): Initializing JXcore engine
,W/jxcore-log(30860): JXcore engine is ready
,W/jxcore-log(30860): Starting JXcore engine
,W/jxcore-log(30860): Platform android
W/jxcore-log(30860): 
,W/jxcore-log(30860): Process ARCH arm
W/jxcore-log(30860): 
,I/jxcore-log(30860): JXcore Cordova bridge is ready!
I/jxcore-log(30860): 
,W/jxcore-log(30860): JXcore engine is started
,E/jxcore-log(30860): >> LGE-LG-D855
E/jxcore-log(30860): 
I/jxcore-log(30860): Total memory 2995761152
I/jxcore-log(30860): 
I/jxcore-log(30860): Free memory 562049024
I/jxcore-log(30860): 
I/jxcore-log(30860): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(30860): 
I/jxcore-log(30860): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(30860): 
,I/jxcore-log(30860): userPath [ 'www' ]
I/jxcore-log(30860): 
,I/jxcore-log(30860): Size 1440 2392
I/jxcore-log(30860): 
,I/jxcore-log(30860): Screen Brightness 177
I/jxcore-log(30860): 
,E/jxcore-log(30860): Dummy Error Log.
E/jxcore-log(30860): 
,I/jxcore-log(30860): getBuffer is called!!!!
I/jxcore-log(30860): 
,I/jxcore-log(30860): Bluetooth toggled
I/jxcore-log(30860): 
,I/jxcore-log(30860): WiFi toggled
I/jxcore-log(30860): 
,I/jxcore-log(30860): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(30860): 
,I/jxcore-log(30860): Response status code was: 200
I/jxcore-log(30860): 
,I/jxcore-log(30860): ****TEST TOOK:  7461  ms ****
I/jxcore-log(30860): 
I/jxcore-log(30860): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(30860): 


samsung-SM-G800F: 
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
,W/jxcore-log(28415): Initializing JXcore engine
,W/jxcore-log(28415): JXcore engine is ready
,W/jxcore-log(28415): Starting JXcore engine
,W/jxcore-log(28415): Platform android
W/jxcore-log(28415): 
,W/jxcore-log(28415): Process ARCH arm
W/jxcore-log(28415): 
,I/jxcore-log(28415): JXcore Cordova bridge is ready!
I/jxcore-log(28415): 
,W/jxcore-log(28415): JXcore engine is started
,E/jxcore-log(28415): >> samsung-SM-G800F
E/jxcore-log(28415): 
,I/jxcore-log(28415): Total memory 1319530496
I/jxcore-log(28415): 
,I/jxcore-log(28415): Free memory 65744896
I/jxcore-log(28415): 
I/jxcore-log(28415): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(28415): 
,I/jxcore-log(28415): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(28415): 
,I/jxcore-log(28415): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(28415): 
I/jxcore-log(28415): Size 720 1280
I/jxcore-log(28415): 
I/jxcore-log(28415): Screen Brightness 255
I/jxcore-log(28415): 
E/jxcore-log(28415): Dummy Error Log.
E/jxcore-log(28415): 
,I/jxcore-log(28415): getBuffer is called!!!!
I/jxcore-log(28415): 
,I/jxcore-log(28415): Bluetooth toggled
I/jxcore-log(28415): 
,I/jxcore-log(28415): WiFi toggled
I/jxcore-log(28415): 
,I/jxcore-log(28415): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(28415): 
,I/jxcore-log(28415): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(28415): 
,I/jxcore-log(28415): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(28415): 
,I/jxcore-log(28415): Response status code was: 200
I/jxcore-log(28415): 
I/jxcore-log(28415): ****TEST TOOK:  9744  ms ****
I/jxcore-log(28415): 
,I/jxcore-log(28415): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(28415): 


```

####Node name: thali04
Console output:
```
STOP log received from  ZX1C223JKW Test has  SUCCEEDED
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
Device test finished on ZX1C223JKW 
Device test finished on 41006f95c8139173 
Android task is completed 
```

Logcat output:
```
samsung-SM-N910C: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(12567): Initializing JXcore engine
,W/jxcore-log(12567): JXcore engine is ready
,W/jxcore-log(12567): Starting JXcore engine
,W/jxcore-log(12567): Platform android
W/jxcore-log(12567): 
,W/jxcore-log(12567): Process ARCH arm
W/jxcore-log(12567): 
,I/jxcore-log(12567): JXcore Cordova bridge is ready!
I/jxcore-log(12567): 
,W/jxcore-log(12567): JXcore engine is started
,E/jxcore-log(12567): >> samsung-SM-N910C
E/jxcore-log(12567): 
,I/jxcore-log(12567): Total memory 2971066368
I/jxcore-log(12567): 
I/jxcore-log(12567): Free memory 259059712
I/jxcore-log(12567): 
I/jxcore-log(12567): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(12567): 
I/jxcore-log(12567): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(12567): 
,I/jxcore-log(12567): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(12567): 
,I/jxcore-log(12567): Size 1440 2560
I/jxcore-log(12567): 
,I/jxcore-log(12567): Screen Brightness 134
I/jxcore-log(12567): 
,E/jxcore-log(12567): Dummy Error Log.
E/jxcore-log(12567): 
,I/jxcore-log(12567): getBuffer is called!!!!
I/jxcore-log(12567): 
,I/jxcore-log(12567): Bluetooth toggled
I/jxcore-log(12567): 
,I/jxcore-log(12567): WiFi toggled
I/jxcore-log(12567): 
,I/jxcore-log(12567): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(12567): 
,I/jxcore-log(12567): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(12567): 
,I/jxcore-log(12567): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(12567): 
,I/jxcore-log(12567): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(12567): 
,I/jxcore-log(12567): Response status code was: 200
I/jxcore-log(12567): 
I/jxcore-log(12567): ****TEST TOOK:  10511  ms ****
I/jxcore-log(12567): 
I/jxcore-log(12567): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(12567): 


motorola-XT1072: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(25658): Initializing JXcore engine
W/jxcore-log(25658): JXcore engine is ready
W/jxcore-log(25658): Starting JXcore engine
W/jxcore-log(25658): Platform android
W/jxcore-log(25658): 
W/jxcore-log(25658): Process ARCH arm
W/jxcore-log(25658): 
,I/jxcore-log(25658): JXcore Cordova bridge is ready!
I/jxcore-log(25658): 
,W/jxcore-log(25658): JXcore engine is started
,E/jxcore-log(25658): >> motorola-XT1072
E/jxcore-log(25658): 
,I/jxcore-log(25658): Total memory 916258816
I/jxcore-log(25658): 
,I/jxcore-log(25658): Free memory 56963072
I/jxcore-log(25658): 
I/jxcore-log(25658): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(25658): 
I/jxcore-log(25658): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(25658): 
,I/jxcore-log(25658): userPath [ 'www' ]
I/jxcore-log(25658): 
,I/jxcore-log(25658): Size 720 1184
I/jxcore-log(25658): 
,I/jxcore-log(25658): Screen Brightness 82
I/jxcore-log(25658): 
E/jxcore-log(25658): Dummy Error Log.
E/jxcore-log(25658): 
,I/jxcore-log(25658): getBuffer is called!!!!
I/jxcore-log(25658): 
,I/jxcore-log(25658): Bluetooth toggled
I/jxcore-log(25658): 
,I/jxcore-log(25658): WiFi toggled
I/jxcore-log(25658): 
,I/jxcore-log(25658): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(25658): 
,I/jxcore-log(25658): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(25658): 
,I/jxcore-log(25658): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(25658): 
,I/jxcore-log(25658): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(25658): 
,I/jxcore-log(25658): Response status code was: 200
I/jxcore-log(25658): 
,I/jxcore-log(25658): ****TEST TOOK:  10506  ms ****
I/jxcore-log(25658): 
I/jxcore-log(25658): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(25658): 


```

####Node name: thali05
Console output:
```
STOP log received from  ZX1G429CRK Test has  SUCCEEDED
Device test finished on ZX1G429CRK 
STOP log received from  1d6a772d Test has  SUCCEEDED
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
,W/jxcore-log(26555): Initializing JXcore engine
,W/jxcore-log(26555): JXcore engine is ready
,W/jxcore-log(26555): Starting JXcore engine
,W/jxcore-log(26555): Platform android
W/jxcore-log(26555): 
,W/jxcore-log(26555): Process ARCH arm
W/jxcore-log(26555): 
,I/jxcore-log(26555): JXcore Cordova bridge is ready!,
I/jxcore-log(26555): 
W/jxcore-log(26555): JXcore engine is started
,E/jxcore-log(26555): >> HTC-HTC One_M8
E/jxcore-log(26555): 
,I/jxcore-log(26555): Total memory 1912020992
,I/jxcore-log(26555): 
I/jxcore-log(26555): Free memory 447340544
I/jxcore-log(26555): 
I/jxcore-log(26555): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(26555): 
I/jxcore-log(26555): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(26555): 
,I/jxcore-log(26555): userPath [ 'www' ]
I/jxcore-log(26555): 
,I/jxcore-log(26555): Size 1080 1776
I/jxcore-log(26555): 
,I/jxcore-log(26555): Screen Brightness 142
I/jxcore-log(26555): 
,E/jxcore-log(26555): Dummy Error Log.
E/jxcore-log(26555): 
,I/jxcore-log(26555): getBuffer is called!!!!
I/jxcore-log(26555): 
,I/jxcore-log(26555): Bluetooth toggled,
I/jxcore-log(26555): 
,I/jxcore-log(26555): WiFi toggled
I/jxcore-log(26555): 
,I/jxcore-log(26555): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(26555): 
,I/jxcore-log(26555): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(26555): 
,I/jxcore-log(26555): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(26555): 
,I/jxcore-log(26555): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(26555): 
,I/jxcore-log(26555): Response status code was: 200,
I/jxcore-log(26555): 
I/jxcore-log(26555): ****TEST TOOK:  10534  ms ****
I/jxcore-log(26555): ,
I/jxcore-log(26555): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(26555): 


samsung-SM-N9005: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log( 5830): Initializing JXcore engine
W/jxcore-log( 5830): JXcore engine is ready
,W/jxcore-log( 5830): Starting JXcore engine
,W/jxcore-log( 5830): Platform android
W/jxcore-log( 5830): 
,W/jxcore-log( 5830): Process ARCH arm
W/jxcore-log( 5830): 
,I/jxcore-log( 5830): JXcore Cordova bridge is ready!
I/jxcore-log( 5830): 
,W/jxcore-log( 5830): JXcore engine is started
,E/jxcore-log( 5830): >> samsung-SM-N9005
E/jxcore-log( 5830): 
,I/jxcore-log( 5830): Total memory 2971471872
I/jxcore-log( 5830): 
,I/jxcore-log( 5830): Free memory 344649728
I/jxcore-log( 5830): 
I/jxcore-log( 5830): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5830): 
I/jxcore-log( 5830): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5830): 
,I/jxcore-log( 5830): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 5830): 
,I/jxcore-log( 5830): Size 1080 1920
I/jxcore-log( 5830): 
,I/jxcore-log( 5830): Screen Brightness 255
I/jxcore-log( 5830): 
,E/jxcore-log( 5830): Dummy Error Log.
E/jxcore-log( 5830): 
,I/jxcore-log( 5830): getBuffer is called!!!!
I/jxcore-log( 5830): 
,I/jxcore-log( 5830): Bluetooth toggled
I/jxcore-log( 5830): 
,I/jxcore-log( 5830): WiFi toggled
I/jxcore-log( 5830): 
,I/jxcore-log( 5830): Response status code was: 200
I/jxcore-log( 5830): 
I/jxcore-log( 5830): ****TEST TOOK:  6412  ms ****
I/jxcore-log( 5830): 
I/jxcore-log( 5830): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5830): 


motorola-Nexus 6: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(22893): Initializing JXcore engine
W/jxcore-log(22893): JXcore engine is ready
W/jxcore-log(22893): Starting JXcore engine
W/jxcore-log(22893): Platform android
W/jxcore-log(22893): 
W/jxcore-log(22893): Process ARCH arm
W/jxcore-log(22893): 
I/jxcore-log(22893): JXcore Cordova bridge is ready!
I/jxcore-log(22893): 
W/jxcore-log(22893): JXcore engine is started
E/jxcore-log(22893): >> motorola-Nexus 6
E/jxcore-log(22893): 
I/jxcore-log(22893): Total memory 3114405888
I/jxcore-log(22893): 
I/jxcore-log(22893): Free memory 652197888
I/jxcore-log(22893): 
I/jxcore-log(22893): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(22893): 
I/jxcore-log(22893): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(22893): 
I/jxcore-log(22893): userPath [ 'www' ]
I/jxcore-log(22893): 
I/jxcore-log(22893): Size 1440 2392
I/jxcore-log(22893): 
I/jxcore-log(22893): Screen Brightness 82
I/jxcore-log(22893): 
E/jxcore-log(22893): Dummy Error Log.
E/jxcore-log(22893): 
,I/jxcore-log(22893): getBuffer is called!!!!
,I/jxcore-log(22893): 
,I/jxcore-log(22893): Bluetooth toggled
I/jxcore-log(22893): 
,I/jxcore-log(22893): WiFi toggled
I/jxcore-log(22893): 
,I/jxcore-log(22893): Response status code was: 200
I/jxcore-log(22893): 
I/jxcore-log(22893): ****TEST TOOK:  6302  ms ****
I/jxcore-log(22893): 
I/jxcore-log(22893): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(22893): 


```

####Node name: thali06
Console output:
```
STOP log received from  7970f88c Test has  SUCCEEDED
STOP log received from  022678fb504e29b0 Test has  SUCCEEDED
Device test finished on 7970f88c 
Device test finished on 022678fb504e29b0 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device FA55PYS00566 app:com.example.hello code:null 
child process exited with code null on device FA55PYS00566 
Android task is completed 
```

Logcat output:
```
HTC-HTC One M8s: 
--------- beginning of system
,--------- beginning of main
,W/jxcore-log(27917): Initializing JXcore engine,
W/jxcore-log(27917): JXcore engine is ready
,W/jxcore-log(27917): Starting JXcore engine,
,W/jxcore-log(27917): Platform android,
W/jxcore-log(27917): 
W/jxcore-log(27917): Process ARCH arm
W/jxcore-log(27917): 
,I/jxcore-log(27917): JXcore Cordova bridge is ready!,
I/jxcore-log(27917): 
,W/jxcore-log(27917): JXcore engine is started
,E/jxcore-log(27917): >> HTC-HTC One M8s,
E/jxcore-log(27917): 
,I/jxcore-log(27917): Total memory 1931808768
I/jxcore-log(27917): 
,I/jxcore-log(27917): Free memory 258756608
I/jxcore-log(27917): 
I/jxcore-log(27917): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(27917): 
I/jxcore-log(27917): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(27917): 
I/jxcore-log(27917): userPath [ 'www' ]
I/jxcore-log(27917): 
I/jxcore-log(27917): Size 1080 1776
I/jxcore-log(27917): 
I/jxcore-log(27917): Screen Brightness 142
I/jxcore-log(27917): 
E/jxcore-log(27917): Dummy Error Log.
E/jxcore-log(27917): 
,I/jxcore-log(27917): getBuffer is called!!!!,
,I/jxcore-log(27917): 
,I/jxcore-log(27917): Bluetooth toggled
I/jxcore-log(27917): 
,I/jxcore-log(27917): WiFi toggled,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
,I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): ,
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): ,
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
,I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
,I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): ,
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
,I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
,I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
,I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
,I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
,I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
,I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
,I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
,I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
,I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
,I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
,I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): ,
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
,I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
,I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
,I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
,I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
,I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
,I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
,I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
,I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
,I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
,I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
,I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
,I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
,I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
,I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
,I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
,I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
,I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
,I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
,I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
,I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
,I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
,I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
,I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
,I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
,I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
,I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
,I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
,I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
,I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
,I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
,I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
,I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
,I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
,I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
,I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
,I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
,I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
,I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
,I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
,I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
,I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
,I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
,I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
,I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
,I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
,I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
,I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): ,
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(27917): 
,TIME-OUT KILL (timeout was 1200000ms),I/jxcore-log(27917): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27917): 


samsung-SM-A300FU: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log( 1945): Initializing JXcore engine
W/jxcore-log( 1945): JXcore engine is ready
W/jxcore-log( 1945): Starting JXcore engine
W/jxcore-log( 1945): Platform android
W/jxcore-log( 1945): 
W/jxcore-log( 1945): Process ARCH arm
W/jxcore-log( 1945): 
,I/jxcore-log( 1945): JXcore Cordova bridge is ready!
I/jxcore-log( 1945): 
,W/jxcore-log( 1945): JXcore engine is started
,E/jxcore-log( 1945): >> samsung-SM-A300FU
E/jxcore-log( 1945): 
,I/jxcore-log( 1945): Total memory 1451114496
I/jxcore-log( 1945): 
,I/jxcore-log( 1945): Free memory 28176384
I/jxcore-log( 1945): 
I/jxcore-log( 1945): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 1945): 
I/jxcore-log( 1945): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 1945): 
,I/jxcore-log( 1945): userPath [ 'www' ]
I/jxcore-log( 1945): 
,I/jxcore-log( 1945): Size 540 960
I/jxcore-log( 1945): 
,I/jxcore-log( 1945): Screen Brightness 160,
I/jxcore-log( 1945): 
E/jxcore-log( 1945): Dummy Error Log.
E/jxcore-log( 1945): 
,I/jxcore-log( 1945): getBuffer is called!!!!
I/jxcore-log( 1945): 
,I/jxcore-log( 1945): Bluetooth toggled
I/jxcore-log( 1945): 
,I/jxcore-log( 1945): WiFi toggled
I/jxcore-log( 1945): 
,I/jxcore-log( 1945): Response status code was: 200
I/jxcore-log( 1945): 
,I/jxcore-log( 1945): ****TEST TOOK:  6480  ms ****
I/jxcore-log( 1945): 
,I/jxcore-log( 1945): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 1945): 


LGE-LG-D802: 
--------- beginning of /dev/log/main
--------- beginning of /dev/log/system
,W/jxcore-log(26834): Initializing JXcore engine
,W/jxcore-log(26834): JXcore engine is ready
,W/jxcore-log(26834): Starting JXcore engine
,W/jxcore-log(26834): Platform android
W/jxcore-log(26834): 
,W/jxcore-log(26834): Process ARCH arm
W/jxcore-log(26834): 
,I/jxcore-log(26834): JXcore Cordova bridge is ready!
I/jxcore-log(26834): 
,W/jxcore-log(26834): JXcore engine is started
,E/jxcore-log(26834): >> LGE-LG-D802
E/jxcore-log(26834): 
,I/jxcore-log(26834): Total memory 1943035904
I/jxcore-log(26834): 
I/jxcore-log(26834): Free memory 212819968
I/jxcore-log(26834): 
I/jxcore-log(26834): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(26834): 
,I/jxcore-log(26834): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(26834): 
,I/jxcore-log(26834): userPath [ 'www' ]
I/jxcore-log(26834): 
,I/jxcore-log(26834): Size 1080 1776
I/jxcore-log(26834): 
,I/jxcore-log(26834): Screen Brightness 255
I/jxcore-log(26834): 
,E/jxcore-log(26834): Dummy Error Log.
E/jxcore-log(26834): 
,I/jxcore-log(26834): getBuffer is called!!!!
I/jxcore-log(26834): 
,I/jxcore-log(26834): Bluetooth toggled
I/jxcore-log(26834): 
,I/jxcore-log(26834): WiFi toggled
I/jxcore-log(26834): 
,I/jxcore-log(26834): Response status code was: 200
I/jxcore-log(26834): 
,I/jxcore-log(26834): ****TEST TOOK:  6479  ms ****
I/jxcore-log(26834): 
,I/jxcore-log(26834): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(26834): 


```

####Node name: thali07
Console output:
```
STOP log received from  c5afcdcb Test has  SUCCEEDED
Device test finished on c5afcdcb 
STOP log received from  4db5c8cc Test has  SUCCEEDED
Device test finished on 4db5c8cc 
Android task is completed 
```

Logcat output:
```
samsung-SM-A500FU: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log( 5852): Initializing JXcore engine
W/jxcore-log( 5852): JXcore engine is ready
,W/jxcore-log( 5852): Starting JXcore engine
,W/jxcore-log( 5852): Platform android
W/jxcore-log( 5852): 
W/jxcore-log( 5852): Process ARCH arm
W/jxcore-log( 5852): 
,I/jxcore-log( 5852): JXcore Cordova bridge is ready!
I/jxcore-log( 5852): 
,W/jxcore-log( 5852): JXcore engine is started
,E/jxcore-log( 5852): >> samsung-SM-A500FU
E/jxcore-log( 5852): 
,I/jxcore-log( 5852): Total memory 1983787008
I/jxcore-log( 5852): 
,I/jxcore-log( 5852): Free memory 357285888
I/jxcore-log( 5852): 
I/jxcore-log( 5852): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5852): 
I/jxcore-log( 5852): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5852): 
,I/jxcore-log( 5852): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 5852): 
,I/jxcore-log( 5852): Size 720 1280
I/jxcore-log( 5852): 
,I/jxcore-log( 5852): Screen Brightness 255
I/jxcore-log( 5852): 
,E/jxcore-log( 5852): Dummy Error Log.
E/jxcore-log( 5852): 
,I/jxcore-log( 5852): getBuffer is called!!!!
I/jxcore-log( 5852): 
,I/jxcore-log( 5852): Bluetooth toggled
I/jxcore-log( 5852): 
,I/jxcore-log( 5852): WiFi toggled
I/jxcore-log( 5852): 
,I/jxcore-log( 5852): Response status code was: 200
I/jxcore-log( 5852): 
,I/jxcore-log( 5852): ****TEST TOOK:  6304  ms ****
I/jxcore-log( 5852): 
I/jxcore-log( 5852): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5852): 


samsung-SM-G900F: 
--------- beginning of main
--------- beginning of system
,W/jxcore-log( 7375): Initializing JXcore engine
W/jxcore-log( 7375): JXcore engine is ready
,W/jxcore-log( 7375): Starting JXcore engine
,W/jxcore-log( 7375): Platform android
W/jxcore-log( 7375): 
W/jxcore-log( 7375): Process ARCH arm
W/jxcore-log( 7375): 
,I/jxcore-log( 7375): JXcore Cordova bridge is ready!
I/jxcore-log( 7375): 
,W/jxcore-log( 7375): JXcore engine is started
,E/jxcore-log( 7375): >> samsung-SM-G900F
E/jxcore-log( 7375): 
,I/jxcore-log( 7375): Total memory 1787449344
I/jxcore-log( 7375): 
,I/jxcore-log( 7375): Free memory 113315840
I/jxcore-log( 7375): 
I/jxcore-log( 7375): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 7375): 
I/jxcore-log( 7375): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 7375): 
,I/jxcore-log( 7375): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 7375): 
,I/jxcore-log( 7375): Size 1080 1920
I/jxcore-log( 7375): 
,I/jxcore-log( 7375): Screen Brightness 134
I/jxcore-log( 7375): 
,E/jxcore-log( 7375): Dummy Error Log.
E/jxcore-log( 7375): 
,I/jxcore-log( 7375): getBuffer is called!!!!
I/jxcore-log( 7375): 
,I/jxcore-log( 7375): Bluetooth toggled,
I/jxcore-log( 7375): ,
,I/jxcore-log( 7375): WiFi toggled
I/jxcore-log( 7375): 
,I/jxcore-log( 7375): Response status code was: 200
I/jxcore-log( 7375): 
,I/jxcore-log( 7375): ****TEST TOOK:  6476  ms ****
I/jxcore-log( 7375): 
,I/jxcore-log( 7375): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7375): 


```

####Node name: thali08
Console output:
```
STOP log received from  4325e43f Test has  SUCCEEDED
STOP log received from  HT574YC04723 Test has  SUCCEEDED
Device test finished on 4325e43f 
Device test finished on HT574YC04723 
Android task is completed 
```

Logcat output:
```
samsung-SM-A300FU: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log( 8540): Initializing JXcore engine
W/jxcore-log( 8540): JXcore engine is ready
W/jxcore-log( 8540): Starting JXcore engine
W/jxcore-log( 8540): Platform android
W/jxcore-log( 8540): 
W/jxcore-log( 8540): Process ARCH arm
W/jxcore-log( 8540): 
I/jxcore-log( 8540): JXcore Cordova bridge is ready!
I/jxcore-log( 8540): 
W/jxcore-log( 8540): JXcore engine is started
E/jxcore-log( 8540): >> samsung-SM-A300FU
E/jxcore-log( 8540): 
I/jxcore-log( 8540): Total memory 1451114496
I/jxcore-log( 8540): 
I/jxcore-log( 8540): Free memory 183734272
I/jxcore-log( 8540): 
I/jxcore-log( 8540): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 8540): 
I/jxcore-log( 8540): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 8540): 
I/jxcore-log( 8540): userPath [ 'www' ]
I/jxcore-log( 8540): 
I/jxcore-log( 8540): Size 540 960
I/jxcore-log( 8540): 
I/jxcore-log( 8540): Screen Brightness 255
I/jxcore-log( 8540): 
E/jxcore-log( 8540): Dummy Error Log.
E/jxcore-log( 8540): 
,I/jxcore-log( 8540): getBuffer is called!!!!
I/jxcore-log( 8540): 
,I/jxcore-log( 8540): Bluetooth toggled
I/jxcore-log( 8540): 
,I/jxcore-log( 8540): WiFi toggled
I/jxcore-log( 8540): 
,I/jxcore-log( 8540): Response status code was: 200
I/jxcore-log( 8540): 
,I/jxcore-log( 8540): ****TEST TOOK:  6308  ms ****
I/jxcore-log( 8540): 
I/jxcore-log( 8540): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 8540): ,


HTC-HTC Desire 820: 
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
,W/jxcore-log(11068): Initializing JXcore engine
,W/jxcore-log(11068): JXcore engine is ready
,W/jxcore-log(11068): Starting JXcore engine
,W/jxcore-log(11068): Platform android
W/jxcore-log(11068): 
,W/jxcore-log(11068): Process ARCH arm
W/jxcore-log(11068): 
,I/jxcore-log(11068): JXcore Cordova bridge is ready!
I/jxcore-log(11068): 
,W/jxcore-log(11068): JXcore engine is started
,E/jxcore-log(11068): >> HTC-HTC Desire 820
E/jxcore-log(11068): 
,I/jxcore-log(11068): Total memory 1964650496
I/jxcore-log(11068): 
I/jxcore-log(11068): Free memory 76288000
I/jxcore-log(11068): 
I/jxcore-log(11068): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(11068): 
,I/jxcore-log(11068): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(11068): 
,I/jxcore-log(11068): userPath [ 'www' ]
I/jxcore-log(11068): 
,I/jxcore-log(11068): Size 720 1184
I/jxcore-log(11068): 
,I/jxcore-log(11068): Screen Brightness 10
I/jxcore-log(11068): 
,E/jxcore-log(11068): Dummy Error Log.
E/jxcore-log(11068): 
,I/jxcore-log(11068): getBuffer is called!!!!
I/jxcore-log(11068): 
,I/jxcore-log(11068): Bluetooth toggled
I/jxcore-log(11068): 
,I/jxcore-log(11068): WiFi toggled
I/jxcore-log(11068): 
,I/jxcore-log(11068): Response status code was: 200
I/jxcore-log(11068): 
,I/jxcore-log(11068): ****TEST TOOK:  6302  ms ****
I/jxcore-log(11068): 
,I/jxcore-log(11068): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(11068): 


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
,W/jxcore-log(17399): Initializing JXcore engine,
,W/jxcore-log(17399): JXcore engine is ready
,W/jxcore-log(17399): Starting JXcore engine
,W/jxcore-log(17399): Platform android
W/jxcore-log(17399): 
,W/jxcore-log(17399): Process ARCH arm
W/jxcore-log(17399): 
,I/jxcore-log(17399): JXcore Cordova bridge is ready!
I/jxcore-log(17399): 
,W/jxcore-log(17399): JXcore engine is started
,E/jxcore-log(17399): >> LGE-Nexus 5
E/jxcore-log(17399): 
,I/jxcore-log(17399): Total memory 1945137152
I/jxcore-log(17399): 
I/jxcore-log(17399): Free memory 469463040
I/jxcore-log(17399): 
I/jxcore-log(17399): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(17399): 
,I/jxcore-log(17399): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(17399): 
,I/jxcore-log(17399): userPath [ 'www' ]
I/jxcore-log(17399): 
,I/jxcore-log(17399): Size 1080 1776
I/jxcore-log(17399): 
,I/jxcore-log(17399): Screen Brightness 82
I/jxcore-log(17399): 
,E/jxcore-log(17399): Dummy Error Log.
E/jxcore-log(17399): 
,I/jxcore-log(17399): getBuffer is called!!!!
I/jxcore-log(17399): 
,I/jxcore-log(17399): Bluetooth toggled
I/jxcore-log(17399): 
,I/jxcore-log(17399): WiFi toggled
I/jxcore-log(17399): 
,I/jxcore-log(17399): Response status code was: 200
I/jxcore-log(17399): 
,I/jxcore-log(17399): ****TEST TOOK:  6349  ms ****
I/jxcore-log(17399): 
,I/jxcore-log(17399): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(17399): 


HTC-HTC Desire 820: 
--------- beginning of /dev/log/main,
--------- beginning of /dev/log/system
,W/jxcore-log( 5107): Initializing JXcore engine
,W/jxcore-log( 5107): JXcore engine is ready
,W/jxcore-log( 5107): Starting JXcore engine
,W/jxcore-log( 5107): Platform android
W/jxcore-log( 5107): 
,W/jxcore-log( 5107): Process ARCH arm
W/jxcore-log( 5107): 
,I/jxcore-log( 5107): JXcore Cordova bridge is ready!
I/jxcore-log( 5107): 
,W/jxcore-log( 5107): JXcore engine is started
,E/jxcore-log( 5107): >> HTC-HTC Desire 820
E/jxcore-log( 5107): 
,I/jxcore-log( 5107): Total memory 1964650496
I/jxcore-log( 5107): 
I/jxcore-log( 5107): Free memory 253120512
I/jxcore-log( 5107): 
,I/jxcore-log( 5107): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5107): 
,I/jxcore-log( 5107): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5107): 
,I/jxcore-log( 5107): userPath [ 'www' ]
I/jxcore-log( 5107): 
,I/jxcore-log( 5107): Size 720 1184
I/jxcore-log( 5107): 
,I/jxcore-log( 5107): Screen Brightness 142
I/jxcore-log( 5107): 
,E/jxcore-log( 5107): Dummy Error Log.
E/jxcore-log( 5107): 
,I/jxcore-log( 5107): getBuffer is called!!!!
I/jxcore-log( 5107): 
,I/jxcore-log( 5107): Bluetooth toggled
I/jxcore-log( 5107): 
,I/jxcore-log( 5107): WiFi toggled
I/jxcore-log( 5107): 
,I/jxcore-log( 5107): Response status code was: 200
I/jxcore-log( 5107): 
,I/jxcore-log( 5107): ****TEST TOOK:  6302  ms ****
I/jxcore-log( 5107): 
,I/jxcore-log( 5107): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5107): 


```




#### Integration Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":23,"cancel":1}}
Integration server has received  [ 'jx',
  '/home/pi/Test/server_49526184d88d809/Sub/serverApp/index.js',
  '{"devices":{"android":23,"cancel":1}}' ]

JSON { devices: { android: 23, cancel: 1 } }


```

