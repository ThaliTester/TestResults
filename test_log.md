#### Test 49526184cc21a54 Logs

Status: 
```

server : IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":24,"cancel":1}}
Integration server has received  [ 'jx',
  '/home/pi/Test/server_49526184cc21a54/Sub/serverApp/index.js',
  '{"devices":{"android":24,"cancel":1}}' ]

JSON { devices: { android: 24, cancel: 1 } }



android : Error: Command failed: Error: Command failed: run_.sh aborted
 [0m


```
###Android Logs
####Node name: thali01
Console output:
```
STOP log received from  03157df360a1882a Test has  SUCCEEDED
Device test finished on 03157df360a1882a 
STOP log received from  W3D7N15428022572 Test has  SUCCEEDED
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
,W/jxcore-log( 2496): Initializing JXcore engine
W/jxcore-log( 2496): JXcore engine is ready
,W/jxcore-log( 2496): Starting JXcore engine
,W/jxcore-log( 2496): Platform android
W/jxcore-log( 2496): 
W/jxcore-log( 2496): Process ARCH arm
W/jxcore-log( 2496): 
,I/jxcore-log( 2496): JXcore Cordova bridge is ready!
I/jxcore-log( 2496): 
W/jxcore-log( 2496): JXcore engine is started
,E/jxcore-log( 2496): >> samsung-SM-G920F
E/jxcore-log( 2496): 
,I/jxcore-log( 2496): Total memory 2829074432
I/jxcore-log( 2496): 
I/jxcore-log( 2496): Free memory 305782784
I/jxcore-log( 2496): 
I/jxcore-log( 2496): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2496): 
I/jxcore-log( 2496): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2496): 
,I/jxcore-log( 2496): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 2496): 
,I/jxcore-log( 2496): Size 1440 2560
I/jxcore-log( 2496): 
,I/jxcore-log( 2496): Screen Brightness 255
I/jxcore-log( 2496): 
E/jxcore-log( 2496): Dummy Error Log.
E/jxcore-log( 2496): 
,I/jxcore-log( 2496): getBuffer is called!!!!
I/jxcore-log( 2496): 
,I/jxcore-log( 2496): Bluetooth toggled
I/jxcore-log( 2496): 
,I/jxcore-log( 2496): WiFi toggled
I/jxcore-log( 2496): 
,I/jxcore-log( 2496): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2496): 
,I/jxcore-log( 2496): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2496): 
,I/jxcore-log( 2496): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2496): 
,I/jxcore-log( 2496): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2496): 
,I/jxcore-log( 2496): Response status code was: 200
I/jxcore-log( 2496): 
,I/jxcore-log( 2496): ****TEST TOOK:  10491  ms ****
I/jxcore-log( 2496): 
I/jxcore-log( 2496): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2496): 


samsung-SM-T232: 
--------- beginning of /dev/log/system
,--------- beginning of /dev/log/main
,W/jxcore-log( 7458): Initializing JXcore engine
W/jxcore-log( 7458): JXcore engine is ready
W/jxcore-log( 7458): Starting JXcore engine
W/jxcore-log( 7458): Platform android
W/jxcore-log( 7458): 
W/jxcore-log( 7458): Process ARCH arm
W/jxcore-log( 7458): 
I/jxcore-log( 7458): JXcore Cordova bridge is ready!
I/jxcore-log( 7458): 
W/jxcore-log( 7458): JXcore engine is started
E/jxcore-log( 7458): >> samsung-SM-T232
E/jxcore-log( 7458): 
I/jxcore-log( 7458): Total memory 1352024064
I/jxcore-log( 7458): 
I/jxcore-log( 7458): Free memory 203407360
I/jxcore-log( 7458): 
I/jxcore-log( 7458): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 7458): 
I/jxcore-log( 7458): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 7458): 
I/jxcore-log( 7458): userPath [ 'www' ]
I/jxcore-log( 7458): 
I/jxcore-log( 7458): Size 800 1280
I/jxcore-log( 7458): 
I/jxcore-log( 7458): Screen Brightness 255
I/jxcore-log( 7458): 
E/jxcore-log( 7458): Dummy Error Log.
E/jxcore-log( 7458): 
,I/jxcore-log( 7458): getBuffer is called!!!!
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Bluetooth toggled
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): WiFi toggled
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 
,TIME-OUT KILL (timeout was 150000ms),I/jxcore-log( 7458): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 7458): 


LGE-LG-H815: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(23568): Initializing JXcore engine
W/jxcore-log(23568): JXcore engine is ready
,W/jxcore-log(23568): Starting JXcore engine
,W/jxcore-log(23568): Platform android
W/jxcore-log(23568): 
W/jxcore-log(23568): Process ARCH arm
W/jxcore-log(23568): 
,I/jxcore-log(23568): JXcore Cordova bridge is ready!
I/jxcore-log(23568): 
,W/jxcore-log(23568): JXcore engine is started
,E/jxcore-log(23568): >> LGE-LG-H815
E/jxcore-log(23568): 
,I/jxcore-log(23568): Total memory 2968948736
I/jxcore-log(23568): 
,I/jxcore-log(23568): Free memory 472076288
I/jxcore-log(23568): 
I/jxcore-log(23568): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(23568): 
I/jxcore-log(23568): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(23568): 
,I/jxcore-log(23568): userPath [ 'www' ]
I/jxcore-log(23568): 
,I/jxcore-log(23568): Size 1440 2392
I/jxcore-log(23568): 
I/jxcore-log(23568): Screen Brightness 255
I/jxcore-log(23568): 
E/jxcore-log(23568): Dummy Error Log.
E/jxcore-log(23568): 
,I/jxcore-log(23568): getBuffer is called!!!!
I/jxcore-log(23568): 
,I/jxcore-log(23568): Bluetooth toggled
I/jxcore-log(23568): 
,I/jxcore-log(23568): WiFi toggled
I/jxcore-log(23568): 
,I/jxcore-log(23568): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(23568): 
,I/jxcore-log(23568): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(23568): 
,I/jxcore-log(23568): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(23568): 
,I/jxcore-log(23568): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(23568): 
,I/jxcore-log(23568): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(23568): 
,I/jxcore-log(23568): Response status code was: 200
I/jxcore-log(23568): 
I/jxcore-log(23568): ****TEST TOOK:  11426  ms ****
I/jxcore-log(23568): 
I/jxcore-log(23568): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(23568): 


HUAWEI-ALE-L21: 
int logctl_get(): open '/dev/hwlog_switch' fail -1, 13. Permission denied

Note: log switch off, only log_main and log_events will have logs!
,--------- beginning of main
W/jxcore-log(31564): Initializing JXcore engine
W/jxcore-log(31564): JXcore engine is ready
W/jxcore-log(31564): Starting JXcore engine
W/jxcore-log(31564): Platform android
W/jxcore-log(31564): 
W/jxcore-log(31564): Process ARCH arm
W/jxcore-log(31564): 
I/jxcore-log(31564): JXcore Cordova bridge is ready!
I/jxcore-log(31564): 
W/jxcore-log(31564): JXcore engine is started
,E/jxcore-log(31564): >> HUAWEI-ALE-L21
E/jxcore-log(31564): 
,I/jxcore-log(31564): Total memory 1949741056
I/jxcore-log(31564): 
,I/jxcore-log(31564): Free memory 24338432
I/jxcore-log(31564): 
I/jxcore-log(31564): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(31564): 
I/jxcore-log(31564): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(31564): 
,I/jxcore-log(31564): userPath [ 'www' ]
I/jxcore-log(31564): 
,I/jxcore-log(31564): Size 720 1184
I/jxcore-log(31564): 
,I/jxcore-log(31564): Screen Brightness 242
I/jxcore-log(31564): 
,E/jxcore-log(31564): Dummy Error Log.
E/jxcore-log(31564): 
,I/jxcore-log(31564): getBuffer is called!!!!
I/jxcore-log(31564): 
,I/jxcore-log(31564): Bluetooth toggled
I/jxcore-log(31564): 
,I/jxcore-log(31564): WiFi toggled
I/jxcore-log(31564): 
,I/jxcore-log(31564): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(31564): 
,I/jxcore-log(31564): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(31564): 
,I/jxcore-log(31564): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(31564): 
,I/jxcore-log(31564): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(31564): 
,I/jxcore-log(31564): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(31564): 
,I/jxcore-log(31564): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(31564): 
,I/jxcore-log(31564): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(31564): 
,I/jxcore-log(31564): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(31564): 
,I/jxcore-log(31564): Response status code was: 200
I/jxcore-log(31564): 
I/jxcore-log(31564): ****TEST TOOK:  14563  ms ****
I/jxcore-log(31564): 
I/jxcore-log(31564): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(31564): 


```

####Node name: thali02
Console output:
```
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
Device test finished on LGD7228ee9cf5b 
Android task is completed 
```

Logcat output:
```
LGE-Nexus 5: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(23769): Initializing JXcore engine
W/jxcore-log(23769): JXcore engine is ready
W/jxcore-log(23769): Starting JXcore engine
,W/jxcore-log(23769): Platform android
W/jxcore-log(23769): 
W/jxcore-log(23769): Process ARCH arm
W/jxcore-log(23769): 
,I/jxcore-log(23769): JXcore Cordova bridge is ready!
I/jxcore-log(23769): 
,W/jxcore-log(23769): JXcore engine is started
,E/jxcore-log(23769): >> LGE-Nexus 5
E/jxcore-log(23769): 
I/jxcore-log(23769): Total memory 1946181632
I/jxcore-log(23769): 
I/jxcore-log(23769): Free memory 290902016
I/jxcore-log(23769): 
I/jxcore-log(23769): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(23769): 
I/jxcore-log(23769): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(23769): 
I/jxcore-log(23769): userPath [ 'www' ]
I/jxcore-log(23769): 
,I/jxcore-log(23769): Size 1080 1776
I/jxcore-log(23769): 
,I/jxcore-log(23769): Screen Brightness 82
I/jxcore-log(23769): 
E/jxcore-log(23769): Dummy Error Log.
E/jxcore-log(23769): 
,I/jxcore-log(23769): getBuffer is called!!!!
I/jxcore-log(23769): 
,I/jxcore-log(23769): Bluetooth toggled
I/jxcore-log(23769): 
,I/jxcore-log(23769): WiFi toggled
I/jxcore-log(23769): 
,I/jxcore-log(23769): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(23769): 
,I/jxcore-log(23769): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(23769): 
,I/jxcore-log(23769): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(23769): 
,I/jxcore-log(23769): Response status code was: 200
I/jxcore-log(23769): 
,I/jxcore-log(23769): ****TEST TOOK:  9462  ms ****,
I/jxcore-log(23769): 
,I/jxcore-log(23769): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(23769): 


LGE-LG-D722: 
--------- beginning of system
--------- beginning of main
,W/jxcore-log(12153): Initializing JXcore engine
W/jxcore-log(12153): JXcore engine is ready
,W/jxcore-log(12153): Starting JXcore engine
,W/jxcore-log(12153): Platform android
W/jxcore-log(12153): 
W/jxcore-log(12153): Process ARCH arm
W/jxcore-log(12153): 
,I/jxcore-log(12153): JXcore Cordova bridge is ready!
I/jxcore-log(12153): 
W/jxcore-log(12153): JXcore engine is started
,E/jxcore-log(12153): >> LGE-LG-D722
E/jxcore-log(12153): 
,I/jxcore-log(12153): Total memory 906309632
I/jxcore-log(12153): 
I/jxcore-log(12153): Free memory 15716352
I/jxcore-log(12153): 
I/jxcore-log(12153): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(12153): 
I/jxcore-log(12153): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(12153): 
I/jxcore-log(12153): userPath [ 'www' ]
I/jxcore-log(12153): 
,I/jxcore-log(12153): Size 720 1196
I/jxcore-log(12153): 
I/jxcore-log(12153): Screen Brightness 255
I/jxcore-log(12153): 
E/jxcore-log(12153): Dummy Error Log.
E/jxcore-log(12153): 
,I/jxcore-log(12153): getBuffer is called!!!!
I/jxcore-log(12153): 
,I/jxcore-log(12153): Bluetooth toggled
I/jxcore-log(12153): 
,I/jxcore-log(12153): WiFi toggled
I/jxcore-log(12153): 
,I/jxcore-log(12153): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(12153): 
,I/jxcore-log(12153): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(12153): 
,I/jxcore-log(12153): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(12153): 
,I/jxcore-log(12153): Response status code was: 200
I/jxcore-log(12153): 
,I/jxcore-log(12153): ****TEST TOOK:  9462  ms ****
I/jxcore-log(12153): 
I/jxcore-log(12153): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(12153): 


```

####Node name: thali03
Console output:
```
STOP log received from  320414cd475f91e3 Test has  SUCCEEDED
Device test finished on 320414cd475f91e3 
STOP log received from  TA4750HV7I Test has  SUCCEEDED
Device test finished on TA4750HV7I 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGD8553bed2d08 app:com.example.hello code:null 
child process exited with code null on device LGD8553bed2d08 
Android task is completed 
```

Logcat output:
```
motorola-XT1039: 
--------- beginning of /dev/log/system
,--------- beginning of /dev/log/main
,W/jxcore-log(26302): Initializing JXcore engine
,W/jxcore-log(26302): JXcore engine is ready
,W/jxcore-log(26302): Starting JXcore engine
,W/jxcore-log(26302): Platform android
W/jxcore-log(26302): 
,W/jxcore-log(26302): Process ARCH arm
W/jxcore-log(26302): 
,I/jxcore-log(26302): JXcore Cordova bridge is ready!
I/jxcore-log(26302): 
,W/jxcore-log(26302): JXcore engine is started
,E/jxcore-log(26302): >> motorola-XT1039
E/jxcore-log(26302): 
,I/jxcore-log(26302): Total memory 893136896
I/jxcore-log(26302): 
I/jxcore-log(26302): Free memory 85606400
I/jxcore-log(26302): 
I/jxcore-log(26302): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(26302): 
,I/jxcore-log(26302): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(26302): 
,I/jxcore-log(26302): userPath [ 'www' ]
I/jxcore-log(26302): 
,I/jxcore-log(26302): Size 720 1184
I/jxcore-log(26302): 
,I/jxcore-log(26302): Screen Brightness 210
I/jxcore-log(26302): 
,E/jxcore-log(26302): Dummy Error Log.
E/jxcore-log(26302): 
,I/jxcore-log(26302): getBuffer is called!!!!
I/jxcore-log(26302): 
,I/jxcore-log(26302): Bluetooth toggled
I/jxcore-log(26302): 
,I/jxcore-log(26302): WiFi toggled
I/jxcore-log(26302): 
,I/jxcore-log(26302): Response status code was: 200
I/jxcore-log(26302): 
I/jxcore-log(26302): ****TEST TOOK:  9456  ms ****
I/jxcore-log(26302): 
,I/jxcore-log(26302): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(26302): 


LGE-LG-D855: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(14680): Initializing JXcore engine
W/jxcore-log(14680): JXcore engine is ready
W/jxcore-log(14680): Starting JXcore engine
W/jxcore-log(14680): Platform android
W/jxcore-log(14680): 
W/jxcore-log(14680): Process ARCH arm
W/jxcore-log(14680): 
,I/jxcore-log(14680): JXcore Cordova bridge is ready!
I/jxcore-log(14680): 
,W/jxcore-log(14680): JXcore engine is started
,E/jxcore-log(14680): >> LGE-LG-D855
E/jxcore-log(14680): 
,I/jxcore-log(14680): Total memory 2995761152
I/jxcore-log(14680): 
,I/jxcore-log(14680): Free memory 490213376
I/jxcore-log(14680): 
I/jxcore-log(14680): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(14680): 
I/jxcore-log(14680): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(14680): 
I/jxcore-log(14680): userPath [ 'www' ]
I/jxcore-log(14680): 
I/jxcore-log(14680): Size 1440 2392
I/jxcore-log(14680): 
I/jxcore-log(14680): Screen Brightness 177
I/jxcore-log(14680): 
E/jxcore-log(14680): Dummy Error Log.
E/jxcore-log(14680): 
,I/jxcore-log(14680): getBuffer is called!!!!
I/jxcore-log(14680): 
,I/jxcore-log(14680): Bluetooth toggled
I/jxcore-log(14680): 
,I/jxcore-log(14680): WiFi toggled
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 
,TIME-OUT KILL (timeout was 150000ms),I/jxcore-log(14680): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(14680): 


samsung-SM-G800F: 
--------- beginning of /dev/log/main
--------- beginning of /dev/log/system
,W/jxcore-log( 1478): Initializing JXcore engine
,W/jxcore-log( 1478): JXcore engine is ready
,W/jxcore-log( 1478): Starting JXcore engine
,W/jxcore-log( 1478): Platform android
W/jxcore-log( 1478): 
,W/jxcore-log( 1478): Process ARCH arm
W/jxcore-log( 1478): 
,I/jxcore-log( 1478): JXcore Cordova bridge is ready!
I/jxcore-log( 1478): 
,W/jxcore-log( 1478): JXcore engine is started
,E/jxcore-log( 1478): >> samsung-SM-G800F
E/jxcore-log( 1478): 
,I/jxcore-log( 1478): Total memory 1319530496
I/jxcore-log( 1478): 
,I/jxcore-log( 1478): Free memory 36425728
I/jxcore-log( 1478): 
I/jxcore-log( 1478): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 1478): 
,I/jxcore-log( 1478): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 1478): 
,I/jxcore-log( 1478): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 1478): 
,I/jxcore-log( 1478): Size 720 1280
I/jxcore-log( 1478): 
,I/jxcore-log( 1478): Screen Brightness 255
I/jxcore-log( 1478): 
,E/jxcore-log( 1478): Dummy Error Log.
E/jxcore-log( 1478): 
,I/jxcore-log( 1478): getBuffer is called!!!!
I/jxcore-log( 1478): 
,I/jxcore-log( 1478): Bluetooth toggled
I/jxcore-log( 1478): 
,I/jxcore-log( 1478): WiFi toggled
I/jxcore-log( 1478): 
,I/jxcore-log( 1478): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 1478): 
,I/jxcore-log( 1478): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 1478): 
,I/jxcore-log( 1478): Response status code was: 200
I/jxcore-log( 1478): 
I/jxcore-log( 1478): ****TEST TOOK:  8537  ms ****
I/jxcore-log( 1478): 
,I/jxcore-log( 1478): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 1478): 


```

####Node name: thali04
Console output:
```
STOP log received from  ZX1C223JKW Test has  SUCCEEDED
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
Device test finished on ZX1C223JKW 
Device test finished on 41006f95c8139173 
STOP log received from  0be0c6c6 Test has  SUCCEEDED
Device test finished on 0be0c6c6 
Android task is completed 
```

Logcat output:
```
samsung-SM-N910C: 
--------- beginning of system
,--------- beginning of main
,W/jxcore-log(13227): Initializing JXcore engine
,W/jxcore-log(13227): JXcore engine is ready
,W/jxcore-log(13227): Starting JXcore engine
,W/jxcore-log(13227): Platform android
W/jxcore-log(13227): 
,W/jxcore-log(13227): Process ARCH arm
W/jxcore-log(13227): 
,I/jxcore-log(13227): JXcore Cordova bridge is ready!
I/jxcore-log(13227): 
,W/jxcore-log(13227): JXcore engine is started
,E/jxcore-log(13227): >> samsung-SM-N910C
E/jxcore-log(13227): 
,I/jxcore-log(13227): Total memory 2971066368
I/jxcore-log(13227): 
I/jxcore-log(13227): Free memory 201326592
I/jxcore-log(13227): 
I/jxcore-log(13227): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(13227): 
I/jxcore-log(13227): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(13227): 
,I/jxcore-log(13227): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(13227): 
,I/jxcore-log(13227): Size 1440 2560
I/jxcore-log(13227): 
,I/jxcore-log(13227): Screen Brightness 134
I/jxcore-log(13227): 
,E/jxcore-log(13227): Dummy Error Log.
E/jxcore-log(13227): 
,I/jxcore-log(13227): getBuffer is called!!!!
I/jxcore-log(13227): 
,I/jxcore-log(13227): Bluetooth toggled
I/jxcore-log(13227): 
,I/jxcore-log(13227): WiFi toggled
I/jxcore-log(13227): 
,I/jxcore-log(13227): Response status code was: 200
I/jxcore-log(13227): 
,I/jxcore-log(13227): ****TEST TOOK:  6414  ms ****
I/jxcore-log(13227): 
,I/jxcore-log(13227): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(13227): 


samsung-SM-G900F: 
--------- beginning of system
,--------- beginning of main
,W/jxcore-log( 4772): Initializing JXcore engine
,W/jxcore-log( 4772): JXcore engine is ready
,W/jxcore-log( 4772): Starting JXcore engine
,W/jxcore-log( 4772): Platform android
W/jxcore-log( 4772): 
,W/jxcore-log( 4772): Process ARCH arm
W/jxcore-log( 4772): 
,I/jxcore-log( 4772): JXcore Cordova bridge is ready!
I/jxcore-log( 4772): 
,W/jxcore-log( 4772): JXcore engine is started
,E/jxcore-log( 4772): >> samsung-SM-G900F
E/jxcore-log( 4772): 
,I/jxcore-log( 4772): Total memory 1787449344
I/jxcore-log( 4772): 
I/jxcore-log( 4772): Free memory 54956032
I/jxcore-log( 4772): 
I/jxcore-log( 4772): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4772): 
I/jxcore-log( 4772): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4772): 
,I/jxcore-log( 4772): userPath [ 'rList-com.example.hello.MainActivity', 'www' ],
,I/jxcore-log( 4772): 
,I/jxcore-log( 4772): Size 1080 1920
,I/jxcore-log( 4772): 
,I/jxcore-log( 4772): Screen Brightness 255
,I/jxcore-log( 4772): 
,E/jxcore-log( 4772): Dummy Error Log.
,E/jxcore-log( 4772): 
,I/jxcore-log( 4772): getBuffer is called!!!!
I/jxcore-log( 4772): 
,I/jxcore-log( 4772): Bluetooth toggled
I/jxcore-log( 4772): 
,I/jxcore-log( 4772): WiFi toggled
I/jxcore-log( 4772): 
,I/jxcore-log( 4772): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 4772): 
,I/jxcore-log( 4772): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 4772): 
,I/jxcore-log( 4772): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 4772): 
,I/jxcore-log( 4772): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 4772): 
,I/jxcore-log( 4772): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 4772): 
,I/jxcore-log( 4772): Response status code was: 200
I/jxcore-log( 4772): 
I/jxcore-log( 4772): ****TEST TOOK:  11466  ms ****
I/jxcore-log( 4772): 
I/jxcore-log( 4772): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4772): 


motorola-XT1072: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log( 2785): Initializing JXcore engine
W/jxcore-log( 2785): JXcore engine is ready
W/jxcore-log( 2785): Starting JXcore engine
,W/jxcore-log( 2785): Platform android
W/jxcore-log( 2785): 
,W/jxcore-log( 2785): Process ARCH arm
W/jxcore-log( 2785): 
,I/jxcore-log( 2785): JXcore Cordova bridge is ready!
I/jxcore-log( 2785): 
,W/jxcore-log( 2785): JXcore engine is started
,E/jxcore-log( 2785): >> motorola-XT1072
E/jxcore-log( 2785): 
,I/jxcore-log( 2785): Total memory 916258816
I/jxcore-log( 2785): 
,I/jxcore-log( 2785): Free memory 56434688
I/jxcore-log( 2785): 
,I/jxcore-log( 2785): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2785): 
,I/jxcore-log( 2785): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2785): 
,I/jxcore-log( 2785): userPath [ 'www' ]
I/jxcore-log( 2785): 
,I/jxcore-log( 2785): Size 720 1184
I/jxcore-log( 2785): 
,I/jxcore-log( 2785): Screen Brightness 82
I/jxcore-log( 2785): 
,E/jxcore-log( 2785): Dummy Error Log.
E/jxcore-log( 2785): 
,I/jxcore-log( 2785): getBuffer is called!!!!
I/jxcore-log( 2785): 
,I/jxcore-log( 2785): Bluetooth toggled
I/jxcore-log( 2785): 
,I/jxcore-log( 2785): WiFi toggled
I/jxcore-log( 2785): 
,I/jxcore-log( 2785): Response status code was: 200
I/jxcore-log( 2785): 
,I/jxcore-log( 2785): ****TEST TOOK:  6361  ms ****
I/jxcore-log( 2785): 
I/jxcore-log( 2785): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2785): 


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
,W/jxcore-log( 3653): Initializing JXcore engine,
W/jxcore-log( 3653): JXcore engine is ready
,W/jxcore-log( 3653): Starting JXcore engine
,W/jxcore-log( 3653): Platform android
W/jxcore-log( 3653): 
,W/jxcore-log( 3653): Process ARCH arm
W/jxcore-log( 3653): 
,I/jxcore-log( 3653): JXcore Cordova bridge is ready!,
I/jxcore-log( 3653): 
W/jxcore-log( 3653): JXcore engine is started
,E/jxcore-log( 3653): >> HTC-HTC One_M8
E/jxcore-log( 3653): 
,I/jxcore-log( 3653): Total memory 1912020992,
I/jxcore-log( 3653): 
I/jxcore-log( 3653): Free memory 431435776
I/jxcore-log( 3653): 
I/jxcore-log( 3653): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3653): 
I/jxcore-log( 3653): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3653): 
,I/jxcore-log( 3653): userPath [ 'www' ],
I/jxcore-log( 3653): 
,I/jxcore-log( 3653): Size 1080 1776
I/jxcore-log( 3653): 
,I/jxcore-log( 3653): Screen Brightness 142
I/jxcore-log( 3653): 
E/jxcore-log( 3653): Dummy Error Log.
E/jxcore-log( 3653): 
,I/jxcore-log( 3653): getBuffer is called!!!!,
I/jxcore-log( 3653): 
,I/jxcore-log( 3653): Bluetooth toggled,
,I/jxcore-log( 3653): 
,I/jxcore-log( 3653): WiFi toggled,
I/jxcore-log( 3653): 
,I/jxcore-log( 3653): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 3653): 
,I/jxcore-log( 3653): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 3653): 
,I/jxcore-log( 3653): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 3653): 
,I/jxcore-log( 3653): Response status code was: 200,
I/jxcore-log( 3653): ,
I/jxcore-log( 3653): ****TEST TOOK:  9566  ms ****,
I/jxcore-log( 3653): 
,I/jxcore-log( 3653): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3653): 


samsung-SM-N9005: 
--------- beginning of system
,--------- beginning of main
,W/jxcore-log(13012): Initializing JXcore engine,
W/jxcore-log(13012): JXcore engine is ready
,W/jxcore-log(13012): Starting JXcore engine
,W/jxcore-log(13012): Platform android
W/jxcore-log(13012): 
W/jxcore-log(13012): Process ARCH arm
W/jxcore-log(13012): 
,I/jxcore-log(13012): JXcore Cordova bridge is ready!
I/jxcore-log(13012): 
W/jxcore-log(13012): JXcore engine is started
,E/jxcore-log(13012): >> samsung-SM-N9005
E/jxcore-log(13012): 
,I/jxcore-log(13012): Total memory 2971471872
I/jxcore-log(13012): 
,I/jxcore-log(13012): Free memory 348397568
I/jxcore-log(13012): 
I/jxcore-log(13012): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(13012): 
I/jxcore-log(13012): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(13012): 
,I/jxcore-log(13012): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(13012): 
,I/jxcore-log(13012): Size 1080 1920
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
,I/jxcore-log(13012): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(13012): 
,I/jxcore-log(13012): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(13012): 
,I/jxcore-log(13012): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(13012): 
,I/jxcore-log(13012): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(13012): 
,I/jxcore-log(13012): Response status code was: 200
I/jxcore-log(13012): 
,I/jxcore-log(13012): ****TEST TOOK:  10439  ms ****
I/jxcore-log(13012): 
I/jxcore-log(13012): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(13012): 


motorola-Nexus 6: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log( 3354): Initializing JXcore engine
W/jxcore-log( 3354): JXcore engine is ready
W/jxcore-log( 3354): Starting JXcore engine
W/jxcore-log( 3354): Platform android
W/jxcore-log( 3354): 
W/jxcore-log( 3354): Process ARCH arm
W/jxcore-log( 3354): 
I/jxcore-log( 3354): JXcore Cordova bridge is ready!
I/jxcore-log( 3354): 
W/jxcore-log( 3354): JXcore engine is started
E/jxcore-log( 3354): >> motorola-Nexus 6
E/jxcore-log( 3354): 
I/jxcore-log( 3354): Total memory 3114405888
I/jxcore-log( 3354): 
I/jxcore-log( 3354): Free memory 532557824
I/jxcore-log( 3354): 
I/jxcore-log( 3354): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3354): 
I/jxcore-log( 3354): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3354): 
I/jxcore-log( 3354): userPath [ 'www' ]
I/jxcore-log( 3354): 
I/jxcore-log( 3354): Size 1440 2392
I/jxcore-log( 3354): 
I/jxcore-log( 3354): Screen Brightness 82
I/jxcore-log( 3354): 
E/jxcore-log( 3354): Dummy Error Log.
E/jxcore-log( 3354): 
,I/jxcore-log( 3354): getBuffer is called!!!!
I/jxcore-log( 3354): 
,I/jxcore-log( 3354): Bluetooth toggled
I/jxcore-log( 3354): 
,I/jxcore-log( 3354): WiFi toggled
I/jxcore-log( 3354): 
,I/jxcore-log( 3354): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 3354): 
,I/jxcore-log( 3354): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 3354): 
,I/jxcore-log( 3354): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 3354): 
,I/jxcore-log( 3354): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 3354): 
,I/jxcore-log( 3354): Response status code was: 200
I/jxcore-log( 3354): 
,I/jxcore-log( 3354): ****TEST TOOK:  10452  ms ****
I/jxcore-log( 3354): 
,I/jxcore-log( 3354): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3354): 


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
,W/jxcore-log(32609): Initializing JXcore engine
W/jxcore-log(32609): JXcore engine is ready
,W/jxcore-log(32609): Starting JXcore engine
,W/jxcore-log(32609): Platform android,
W/jxcore-log(32609): 
W/jxcore-log(32609): Process ARCH arm
W/jxcore-log(32609): 
,I/jxcore-log(32609): JXcore Cordova bridge is ready!,
I/jxcore-log(32609): 
W/jxcore-log(32609): JXcore engine is started
,E/jxcore-log(32609): >> HTC-HTC One M8s
E/jxcore-log(32609): 
,I/jxcore-log(32609): Total memory 1931808768
I/jxcore-log(32609): 
,I/jxcore-log(32609): Free memory 316686336
I/jxcore-log(32609): 
I/jxcore-log(32609): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(32609): 
I/jxcore-log(32609): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(32609): 
,I/jxcore-log(32609): userPath [ 'www' ],
I/jxcore-log(32609): 
,I/jxcore-log(32609): Size 1080 1776,
I/jxcore-log(32609): 
I/jxcore-log(32609): Screen Brightness 142
I/jxcore-log(32609): 
,E/jxcore-log(32609): Dummy Error Log.,
E/jxcore-log(32609): 
,I/jxcore-log(32609): getBuffer is called!!!!,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Bluetooth toggled,
I/jxcore-log(32609): 
,I/jxcore-log(32609): WiFi toggled,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 
,I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32609): 
,TIME-OUT KILL (timeout was 150000ms),I/jxcore-log(32609): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32609): 


samsung-SM-A300FU: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(27834): Initializing JXcore engine
,W/jxcore-log(27834): JXcore engine is ready
,W/jxcore-log(27834): Starting JXcore engine
,W/jxcore-log(27834): Platform android
W/jxcore-log(27834): 
W/jxcore-log(27834): Process ARCH arm
W/jxcore-log(27834): 
,I/jxcore-log(27834): JXcore Cordova bridge is ready!
I/jxcore-log(27834): 
,W/jxcore-log(27834): JXcore engine is started
,E/jxcore-log(27834): >> samsung-SM-A300FU
E/jxcore-log(27834): 
,I/jxcore-log(27834): Total memory 1451114496
I/jxcore-log(27834): 
,I/jxcore-log(27834): Free memory 26329088
I/jxcore-log(27834): 
I/jxcore-log(27834): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(27834): 
I/jxcore-log(27834): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(27834): 
,I/jxcore-log(27834): userPath [ 'www' ]
I/jxcore-log(27834): 
,I/jxcore-log(27834): Size 540 960
I/jxcore-log(27834): 
,I/jxcore-log(27834): Screen Brightness 160
I/jxcore-log(27834): 
,E/jxcore-log(27834): Dummy Error Log.
E/jxcore-log(27834): 
,I/jxcore-log(27834): getBuffer is called!!!!
I/jxcore-log(27834): 
,I/jxcore-log(27834): Bluetooth toggled
I/jxcore-log(27834): 
,I/jxcore-log(27834): WiFi toggled,
I/jxcore-log(27834): 
,I/jxcore-log(27834): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27834): 
,I/jxcore-log(27834): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27834): 
,I/jxcore-log(27834): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(27834): 
,I/jxcore-log(27834): Response status code was: 200
I/jxcore-log(27834): 
I/jxcore-log(27834): ****TEST TOOK:  9348  ms ****
I/jxcore-log(27834): ,
I/jxcore-log(27834): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(27834): 


LGE-LG-D802: 
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
,W/jxcore-log(21201): Initializing JXcore engine
W/jxcore-log(21201): JXcore engine is ready
W/jxcore-log(21201): Starting JXcore engine
W/jxcore-log(21201): Platform android
W/jxcore-log(21201): 
W/jxcore-log(21201): Process ARCH arm
W/jxcore-log(21201): 
,I/jxcore-log(21201): JXcore Cordova bridge is ready!
I/jxcore-log(21201): 
,W/jxcore-log(21201): JXcore engine is started
,E/jxcore-log(21201): >> LGE-LG-D802
E/jxcore-log(21201): 
,I/jxcore-log(21201): Total memory 1943035904
I/jxcore-log(21201): 
I/jxcore-log(21201): Free memory 155197440
I/jxcore-log(21201): 
I/jxcore-log(21201): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(21201): 
,I/jxcore-log(21201): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(21201): 
,I/jxcore-log(21201): userPath [ 'www' ]
I/jxcore-log(21201): 
,I/jxcore-log(21201): Size 1080 1776
I/jxcore-log(21201): 
,I/jxcore-log(21201): Screen Brightness 255
I/jxcore-log(21201): 
,E/jxcore-log(21201): Dummy Error Log.
E/jxcore-log(21201): 
,I/jxcore-log(21201): getBuffer is called!!!!
I/jxcore-log(21201): 
,I/jxcore-log(21201): Bluetooth toggled
I/jxcore-log(21201): 
,I/jxcore-log(21201): WiFi toggled
I/jxcore-log(21201): 
,I/jxcore-log(21201): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(21201): 
,I/jxcore-log(21201): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(21201): 
,I/jxcore-log(21201): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(21201): 
,I/jxcore-log(21201): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(21201): 
,I/jxcore-log(21201): Response status code was: 200
I/jxcore-log(21201): 
,I/jxcore-log(21201): ****TEST TOOK:  10532  ms ****
I/jxcore-log(21201): 
,I/jxcore-log(21201): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(21201): 


```

####Node name: thali07
Console output:
```
STOP log received from  c5afcdcb Test has  SUCCEEDED
Device test finished on c5afcdcb 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 4db5c8cc app:com.example.hello code:null 
child process exited with code null on device 4db5c8cc 
Android task is completed 
```

Logcat output:
```
samsung-SM-A500FU: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(32520): Initializing JXcore engine
W/jxcore-log(32520): JXcore engine is ready
,W/jxcore-log(32520): Starting JXcore engine
,W/jxcore-log(32520): Platform android
W/jxcore-log(32520): 
W/jxcore-log(32520): Process ARCH arm
W/jxcore-log(32520): 
,I/jxcore-log(32520): JXcore Cordova bridge is ready!
I/jxcore-log(32520): 
,W/jxcore-log(32520): JXcore engine is started
,E/jxcore-log(32520): >> samsung-SM-A500FU
E/jxcore-log(32520): 
,I/jxcore-log(32520): Total memory 1983787008
I/jxcore-log(32520): 
,I/jxcore-log(32520): Free memory 349220864
I/jxcore-log(32520): 
I/jxcore-log(32520): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(32520): 
I/jxcore-log(32520): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(32520): 
,I/jxcore-log(32520): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(32520): 
,I/jxcore-log(32520): Size 720 1280
I/jxcore-log(32520): 
,I/jxcore-log(32520): Screen Brightness 255
I/jxcore-log(32520): 
,E/jxcore-log(32520): Dummy Error Log.
E/jxcore-log(32520): 
,I/jxcore-log(32520): getBuffer is called!!!!,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Bluetooth toggled,
I/jxcore-log(32520): 
,I/jxcore-log(32520): WiFi toggled
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log(32520): 
,I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 
,TIME-OUT KILL (timeout was 150000ms),I/jxcore-log(32520): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(32520): 


samsung-SM-G900F: 
--------- beginning of main
--------- beginning of system
,W/jxcore-log(19115): Initializing JXcore engine
W/jxcore-log(19115): JXcore engine is ready
W/jxcore-log(19115): Starting JXcore engine
,W/jxcore-log(19115): Platform android
W/jxcore-log(19115): 
,W/jxcore-log(19115): Process ARCH arm
W/jxcore-log(19115): 
,I/jxcore-log(19115): JXcore Cordova bridge is ready!
I/jxcore-log(19115): 
,W/jxcore-log(19115): JXcore engine is started
,E/jxcore-log(19115): >> samsung-SM-G900F
E/jxcore-log(19115): 
,I/jxcore-log(19115): Total memory 1787449344
I/jxcore-log(19115): 
,I/jxcore-log(19115): Free memory 47804416
I/jxcore-log(19115): 
I/jxcore-log(19115): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(19115): 
I/jxcore-log(19115): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(19115): 
,I/jxcore-log(19115): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(19115): 
,I/jxcore-log(19115): Size 1080 1920
I/jxcore-log(19115): 
,I/jxcore-log(19115): Screen Brightness 134
I/jxcore-log(19115): 
,E/jxcore-log(19115): Dummy Error Log.
E/jxcore-log(19115): 
,I/jxcore-log(19115): getBuffer is called!!!!
I/jxcore-log(19115): 
,I/jxcore-log(19115): Bluetooth toggled
I/jxcore-log(19115): 
,I/jxcore-log(19115): WiFi toggled
I/jxcore-log(19115): 
,I/jxcore-log(19115): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(19115): 
,I/jxcore-log(19115): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(19115): 
,I/jxcore-log(19115): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(19115): 
,I/jxcore-log(19115): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(19115): 
,I/jxcore-log(19115): Response status code was: 200
I/jxcore-log(19115): 
,I/jxcore-log(19115): ****TEST TOOK:  10562  ms ****
I/jxcore-log(19115): 
I/jxcore-log(19115): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(19115): 


```

####Node name: thali08
Console output:
```
STOP log received from  HT574YC04723 Test has  SUCCEEDED
Device test finished on HT574YC04723 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 4325e43f app:com.example.hello code:null 
child process exited with code null on device 4325e43f 
Android task is completed 
```

Logcat output:
```
samsung-SM-A300FU: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log( 2646): Initializing JXcore engine
,W/jxcore-log( 2646): JXcore engine is ready
,W/jxcore-log( 2646): Starting JXcore engine
,W/jxcore-log( 2646): Platform android
W/jxcore-log( 2646): 
W/jxcore-log( 2646): Process ARCH arm
W/jxcore-log( 2646): 
,I/jxcore-log( 2646): JXcore Cordova bridge is ready!,
I/jxcore-log( 2646): 
W/jxcore-log( 2646): JXcore engine is started
,E/jxcore-log( 2646): >> samsung-SM-A300FU,
E/jxcore-log( 2646): 
,I/jxcore-log( 2646): Total memory 1451114496,
I/jxcore-log( 2646): 
I/jxcore-log( 2646): Free memory 176267264
I/jxcore-log( 2646): 
I/jxcore-log( 2646): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): userPath [ 'www' ],
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Size 540 960,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Screen Brightness 255
I/jxcore-log( 2646): 
,E/jxcore-log( 2646): Dummy Error Log.
E/jxcore-log( 2646): 
,I/jxcore-log( 2646): getBuffer is called!!!!
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Bluetooth toggled
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): WiFi toggled
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2646): ,
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2646): ,
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND,
I/jxcore-log( 2646): 
,TIME-OUT KILL (timeout was 150000ms),I/jxcore-log( 2646): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log( 2646): 


HTC-HTC Desire 820: 
--------- beginning of /dev/log/system
,--------- beginning of /dev/log/main
,W/jxcore-log(16189): Initializing JXcore engine
,W/jxcore-log(16189): JXcore engine is ready
,W/jxcore-log(16189): Starting JXcore engine
,W/jxcore-log(16189): Platform android
W/jxcore-log(16189): 
,W/jxcore-log(16189): Process ARCH arm
W/jxcore-log(16189): 
,I/jxcore-log(16189): JXcore Cordova bridge is ready!
I/jxcore-log(16189): 
,W/jxcore-log(16189): JXcore engine is started
,E/jxcore-log(16189): >> HTC-HTC Desire 820
E/jxcore-log(16189): 
,I/jxcore-log(16189): Total memory 1964650496
I/jxcore-log(16189): 
I/jxcore-log(16189): Free memory 163393536
I/jxcore-log(16189): 
,I/jxcore-log(16189): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(16189): 
,I/jxcore-log(16189): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(16189): 
,I/jxcore-log(16189): userPath [ 'www' ]
I/jxcore-log(16189): 
,I/jxcore-log(16189): Size 720 1184
I/jxcore-log(16189): 
,I/jxcore-log(16189): Screen Brightness 10
I/jxcore-log(16189): 
,E/jxcore-log(16189): Dummy Error Log.
E/jxcore-log(16189): 
,I/jxcore-log(16189): getBuffer is called!!!!
I/jxcore-log(16189): 
,I/jxcore-log(16189): Bluetooth toggled
I/jxcore-log(16189): 
,I/jxcore-log(16189): WiFi toggled
I/jxcore-log(16189): 
,I/jxcore-log(16189): Response status code was: 200
I/jxcore-log(16189): 
I/jxcore-log(16189): ****TEST TOOK:  6336  ms ****
I/jxcore-log(16189): 
,I/jxcore-log(16189): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(16189): 


```

####Node name: thali09
Console output:
```
STOP log received from  CC51WYC03425 Test has  SUCCEEDED
STOP log received from  CC51WYC03425 Test has  SUCCEEDED
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
,W/jxcore-log(21151): Initializing JXcore engine
,W/jxcore-log(21151): JXcore engine is ready
,W/jxcore-log(21151): Starting JXcore engine
,W/jxcore-log(21151): Platform android
W/jxcore-log(21151): 
,W/jxcore-log(21151): Process ARCH arm
W/jxcore-log(21151): 
,I/jxcore-log(21151): JXcore Cordova bridge is ready!
I/jxcore-log(21151): 
,W/jxcore-log(21151): JXcore engine is started
,E/jxcore-log(21151): >> LGE-Nexus 5
E/jxcore-log(21151): 
I/jxcore-log(21151): Total memory 1945137152
I/jxcore-log(21151): 
I/jxcore-log(21151): Free memory 435212288
I/jxcore-log(21151): 
I/jxcore-log(21151): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(21151): 
,I/jxcore-log(21151): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(21151): 
,I/jxcore-log(21151): userPath [ 'www' ]
I/jxcore-log(21151): 
,I/jxcore-log(21151): Size 1080 1776
I/jxcore-log(21151): 
I/jxcore-log(21151): Screen Brightness 82
I/jxcore-log(21151): 
,E/jxcore-log(21151): Dummy Error Log.
E/jxcore-log(21151): 
,I/jxcore-log(21151): getBuffer is called!!!!
I/jxcore-log(21151): 
,I/jxcore-log(21151): Bluetooth toggled
I/jxcore-log(21151): 
,I/jxcore-log(21151): WiFi toggled
I/jxcore-log(21151): 
,I/jxcore-log(21151): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(21151): 
,I/jxcore-log(21151): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(21151): 
,I/jxcore-log(21151): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(21151): 
,I/jxcore-log(21151): Request error was: Error: getaddrinfo ENOTFOUND
I/jxcore-log(21151): 
,I/jxcore-log(21151): Response status code was: 200
I/jxcore-log(21151): 
I/jxcore-log(21151): ****TEST TOOK:  10431  ms ****
I/jxcore-log(21151): 
,I/jxcore-log(21151): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(21151): 


HTC-HTC Desire 820: 
--------- beginning of /dev/log/main,
--------- beginning of /dev/log/system
,W/jxcore-log( 9455): Initializing JXcore engine
,W/jxcore-log( 9455): JXcore engine is ready
,W/jxcore-log( 9455): Starting JXcore engine
,W/jxcore-log( 9455): Platform android
W/jxcore-log( 9455): 
,W/jxcore-log( 9455): Process ARCH arm
W/jxcore-log( 9455): 
,I/jxcore-log( 9455): JXcore Cordova bridge is ready!
I/jxcore-log( 9455): 
,W/jxcore-log( 9455): JXcore engine is started
,E/jxcore-log( 9455): >> HTC-HTC Desire 820
E/jxcore-log( 9455): 
,I/jxcore-log( 9455): Total memory 1964650496
I/jxcore-log( 9455): 
I/jxcore-log( 9455): Free memory 218775552
I/jxcore-log( 9455): 
,I/jxcore-log( 9455): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 9455): 
,I/jxcore-log( 9455): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 9455): 
,I/jxcore-log( 9455): userPath [ 'www' ]
I/jxcore-log( 9455): 
,I/jxcore-log( 9455): Size 720 1184
I/jxcore-log( 9455): 
,I/jxcore-log( 9455): Screen Brightness 142
I/jxcore-log( 9455): 
,E/jxcore-log( 9455): Dummy Error Log.
E/jxcore-log( 9455): 
,I/jxcore-log( 9455): getBuffer is called!!!!
I/jxcore-log( 9455): 
,I/jxcore-log( 9455): Bluetooth toggled
I/jxcore-log( 9455): 
,I/jxcore-log( 9455): WiFi toggled
I/jxcore-log( 9455): 
,I/jxcore-log( 9455): Response status code was: 200
I/jxcore-log( 9455): 
,I/jxcore-log( 9455): ****TEST TOOK:  10375  ms ****
I/jxcore-log( 9455): 
,I/jxcore-log( 9455): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 9455): 
,I/jxcore-log( 9455): Response status code was: 200
I/jxcore-log( 9455): 
I/jxcore-log( 9455): ****TEST TOOK:  10399  ms ****
I/jxcore-log( 9455): 
I/jxcore-log( 9455): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 9455): 
I/jxcore-log( 9455): Response status code was: 200
I/jxcore-log( 9455): 
I/jxcore-log( 9455): ****TEST TOOK:  10407  ms ****
I/jxcore-log( 9455): 
I/jxcore-log( 9455): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 9455): 
I/jxcore-log( 9455): Response status code was: 200
I/jxcore-log( 9455): 
I/jxcore-log( 9455): ****TEST TOOK:  10411  ms ****
I/jxcore-log( 9455): 
I/jxcore-log( 9455): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 9455): 
,I/jxcore-log( 9455): Response status code was: 200
I/jxcore-log( 9455): 
,I/jxcore-log( 9455): ****TEST TOOK:  10477  ms ****
I/jxcore-log( 9455): 
,I/jxcore-log( 9455): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 9455): 


```




#### Integration Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":24,"cancel":1}}
Integration server has received  [ 'jx',
  '/home/pi/Test/server_49526184cc21a54/Sub/serverApp/index.js',
  '{"devices":{"android":24,"cancel":1}}' ]

JSON { devices: { android: 24, cancel: 1 } }


```

