#### Test 48600797ceec528 Logs

Status: 
```

server : IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":25}}
Star Android tests : performance tests, start tests with timer

Test[0]: testSendData.js, timeout : 300000, data : {"timeout":"250000","rounds":"3","dataTimeout":"60000","dataAmount":"100000","conReTryTimeout":"2000","conReTryCount":"1"}
Test[1]: testSendData.js, timeout : 300000, data : {"timeout":"250000","rounds":"3","dataTimeout":"60000","dataAmount":"100000","conReTryTimeout":"2000","conReTryCount":"1"}
Test[2]: testSendData.js, timeout : 300000, data : {"timeout":"250000","rounds":"3","dataTimeout":"60000","dataAmount":"100000","conReTryTimeout":"2000","conReTryCount":"1"}
Star iOs tests : performance tests, start tests with timer
Test[0]: testSendData.js, timeout : 300000, data : {"timeout":"250000","rounds":"3","dataTimeout":"60000","dataAmount":"100000","conReTryTimeout":"2000","conReTryCount":"1"}
Test[1]: testSendData.js, timeout : 300000, data : {"timeout":"250000","rounds":"3","dataTimeout":"60000","dataAmount":"100000","conReTryTimeout":"2000","conReTryCount":"1"}
Test[2]: testSendData.js, timeout : 300000, data : {"timeout":"250000","rounds":"3","dataTimeout":"60000","dataAmount":"100000","conReTryTimeout":"2000","conReTryCount":"1"}

listening on *:3000

-------------- We got wait done, now starting the testing process ------------------


 
Run IS script aborted
 
[0;31mexecution aborted
 [0m


android : Error: Command failed: Error: Command failed: run_.sh aborted
 [0m


TIMEOUT REACHED!
```
###Android Logs
####Node name: thali01
Console output:
```
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
,W/jxcore-log(14852): Initializing JXcore engine
,W/jxcore-log(14852): JXcore engine is ready
,W/jxcore-log(14852): Starting JXcore engine
,W/jxcore-log(14852): Platform android
W/jxcore-log(14852): 
W/jxcore-log(14852): Process ARCH arm
W/jxcore-log(14852): 
,I/jxcore-log(14852): JXcore Cordova bridge is ready!
I/jxcore-log(14852): 
W/jxcore-log(14852): JXcore engine is started


samsung-SM-T232: 
--------- beginning of /dev/log/system
,--------- beginning of /dev/log/main
,W/jxcore-log(  761): Initializing JXcore engine
,W/jxcore-log(  761): JXcore engine is ready
,W/jxcore-log(  761): Starting JXcore engine
,W/jxcore-log(  761): Platform android
W/jxcore-log(  761): 
,W/jxcore-log(  761): Process ARCH arm
W/jxcore-log(  761): 
,I/jxcore-log(  761): JXcore Cordova bridge is ready!
I/jxcore-log(  761): 
,W/jxcore-log(  761): JXcore engine is started


LGE-LG-H815: 
--------- beginning of main
--------- beginning of system
,W/jxcore-log(  506): Initializing JXcore engine
W/jxcore-log(  506): JXcore engine is ready
W/jxcore-log(  506): Starting JXcore engine
W/jxcore-log(  506): Platform android
W/jxcore-log(  506): 
W/jxcore-log(  506): Process ARCH arm
W/jxcore-log(  506): 
,I/jxcore-log(  506): JXcore Cordova bridge is ready!
I/jxcore-log(  506): 
,W/jxcore-log(  506): JXcore engine is started


HUAWEI-ALE-L21: 
int logctl_get(): open '/dev/hwlog_switch' fail -1, 13. Permission denied

Note: log switch off, only log_main and log_events will have logs!
--------- beginning of main
,W/jxcore-log(16173): Initializing JXcore engine
W/jxcore-log(16173): JXcore engine is ready
W/jxcore-log(16173): Starting JXcore engine
W/jxcore-log(16173): Platform android
W/jxcore-log(16173): 
W/jxcore-log(16173): Process ARCH arm
W/jxcore-log(16173): 
,I/jxcore-log(16173): JXcore Cordova bridge is ready!
I/jxcore-log(16173): 
W/jxcore-log(16173): JXcore engine is started


```

####Node name: thali02
Console output:
```
Error! Unexpected exit on device 09a9416e0297d102 app:com.test.thalitest code:null 
child process exited with code null on device 09a9416e0297d102 
Error! Unexpected exit on device LGD7228ee9cf5b app:com.test.thalitest code:null 
child process exited with code null on device LGD7228ee9cf5b 
Android task is completed 
```

Logcat output:
```
LGE-Nexus 5: 
--------- beginning of system
,--------- beginning of main
,W/jxcore-log(14022): Initializing JXcore engine
W/jxcore-log(14022): JXcore engine is ready
,W/jxcore-log(14022): Starting JXcore engine
,W/jxcore-log(14022): Platform android
W/jxcore-log(14022): 
W/jxcore-log(14022): Process ARCH arm
W/jxcore-log(14022): 
,I/jxcore-log(14022): JXcore Cordova bridge is ready!
I/jxcore-log(14022): 
,W/jxcore-log(14022): JXcore engine is started


LGE-LG-D722: 
--------- beginning of main
--------- beginning of system
,W/jxcore-log( 4979): Initializing JXcore engine
W/jxcore-log( 4979): JXcore engine is ready
,W/jxcore-log( 4979): Starting JXcore engine
,W/jxcore-log( 4979): Platform android
W/jxcore-log( 4979): 
W/jxcore-log( 4979): Process ARCH arm
W/jxcore-log( 4979): 
,I/jxcore-log( 4979): JXcore Cordova bridge is ready!
I/jxcore-log( 4979): 
,W/jxcore-log( 4979): JXcore engine is started


```

####Node name: thali03
Console output:
```
Error! Unexpected exit on device TA4750HV7I app:com.test.thalitest code:null 
child process exited with code null on device TA4750HV7I 
Error! Unexpected exit on device 320414cd475f91e3 app:com.test.thalitest code:null 
child process exited with code null on device 320414cd475f91e3 
Android task is completed 
```

Logcat output:
```
motorola-XT1039: 
--------- beginning of /dev/log/system
,--------- beginning of /dev/log/main
,W/jxcore-log(15237): Initializing JXcore engine
,W/jxcore-log(15237): JXcore engine is ready
,W/jxcore-log(15237): Starting JXcore engine
,W/jxcore-log(15237): Platform android
W/jxcore-log(15237): 
,W/jxcore-log(15237): Process ARCH arm
W/jxcore-log(15237): 
,I/jxcore-log(15237): JXcore Cordova bridge is ready!
I/jxcore-log(15237): 
,W/jxcore-log(15237): JXcore engine is started


LGE-LG-D855: 
--------- beginning of main
--------- beginning of system
W/jxcore-log(19345): Initializing JXcore engine
W/jxcore-log(19345): JXcore engine is ready
W/jxcore-log(19345): Starting JXcore engine
W/jxcore-log(19345): Platform android
W/jxcore-log(19345): 
,W/jxcore-log(19345): Process ARCH arm
W/jxcore-log(19345): 
I/jxcore-log(19345): JXcore Cordova bridge is ready!
I/jxcore-log(19345): 
W/jxcore-log(19345): JXcore engine is started
E/jxcore-log(19345): >> LGE-LG-D855
E/jxcore-log(19345): 
I/jxcore-log(19345): Total memory 2995761152
I/jxcore-log(19345): 
I/jxcore-log(19345): Free memory 467025920
I/jxcore-log(19345): 
I/jxcore-log(19345): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(19345): 
I/jxcore-log(19345): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(19345): 
I/jxcore-log(19345): userPath [ 'www' ]
I/jxcore-log(19345): 
I/jxcore-log(19345): Size 1440 2392
I/jxcore-log(19345): 
I/jxcore-log(19345): Screen Brightness 177
I/jxcore-log(19345): 
E/jxcore-log(19345): Dummy Error Log.
E/jxcore-log(19345): 
I/jxcore-log(19345): getBuffer is called!!!!
I/jxcore-log(19345): 
I/jxcore-log(19345): ****TEST TOOK:  5078  ms ****
I/jxcore-log(19345): 
I/jxcore-log(19345): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(19345): 


samsung-SM-G800F: 
--------- beginning of /dev/log/main
--------- beginning of /dev/log/system
,W/jxcore-log( 9604): Initializing JXcore engine
,W/jxcore-log( 9604): JXcore engine is ready
,W/jxcore-log( 9604): Starting JXcore engine
,W/jxcore-log( 9604): Platform android
W/jxcore-log( 9604): 
,W/jxcore-log( 9604): Process ARCH arm
W/jxcore-log( 9604): 
,I/jxcore-log( 9604): JXcore Cordova bridge is ready!
I/jxcore-log( 9604): 
,W/jxcore-log( 9604): JXcore engine is started


```

####Node name: thali04
Console output:
```
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:null 
child process exited with code null on device ZX1C223JKW 
Error! Unexpected exit on device f56ad48d app:com.test.thalitest code:null 
child process exited with code null on device f56ad48d 
Android task is completed 
```

Logcat output:
```
samsung-SM-N910C: 
--------- beginning of system
,--------- beginning of main
,W/jxcore-log( 9094): Initializing JXcore engine
W/jxcore-log( 9094): JXcore engine is ready
,W/jxcore-log( 9094): Starting JXcore engine
,W/jxcore-log( 9094): Platform android
W/jxcore-log( 9094): 
W/jxcore-log( 9094): Process ARCH arm
W/jxcore-log( 9094): 
,I/jxcore-log( 9094): JXcore Cordova bridge is ready!
I/jxcore-log( 9094): 
W/jxcore-log( 9094): JXcore engine is started


samsung-SM-G900F: 
--------- beginning of main
,--------- beginning of system


motorola-XT1072: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(22891): Initializing JXcore engine
,W/jxcore-log(22891): JXcore engine is ready
,W/jxcore-log(22891): Starting JXcore engine
,W/jxcore-log(22891): Platform android
W/jxcore-log(22891): 
,W/jxcore-log(22891): Process ARCH arm
W/jxcore-log(22891): 
,I/jxcore-log(22891): JXcore Cordova bridge is ready!
I/jxcore-log(22891): 
,W/jxcore-log(22891): JXcore engine is started


samsung-SM-A500FU: 
--------- beginning of main,
--------- beginning of system
,W/jxcore-log(28990): Initializing JXcore engine
,W/jxcore-log(28990): JXcore engine is ready
,W/jxcore-log(28990): Starting JXcore engine
,W/jxcore-log(28990): Platform android,
W/jxcore-log(28990): 
W/jxcore-log(28990): Process ARCH arm
W/jxcore-log(28990): 
,I/jxcore-log(28990): JXcore Cordova bridge is ready!
I/jxcore-log(28990): 
W/jxcore-log(28990): JXcore engine is started


```

####Node name: thali05
Console output:
```
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
,W/jxcore-log(21728): Initializing JXcore engine
,W/jxcore-log(21728): JXcore engine is ready
,W/jxcore-log(21728): Starting JXcore engine
,W/jxcore-log(21728): Platform android
W/jxcore-log(21728): 
,W/jxcore-log(21728): Process ARCH arm
W/jxcore-log(21728): 
,I/jxcore-log(21728): JXcore Cordova bridge is ready!
I/jxcore-log(21728): 
W/jxcore-log(21728): JXcore engine is started


samsung-SM-N9005: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(28467): Initializing JXcore engine
W/jxcore-log(28467): JXcore engine is ready
,W/jxcore-log(28467): Starting JXcore engine
,W/jxcore-log(28467): Platform android
W/jxcore-log(28467): 
W/jxcore-log(28467): Process ARCH arm
W/jxcore-log(28467): 
,I/jxcore-log(28467): JXcore Cordova bridge is ready!
I/jxcore-log(28467): 
,W/jxcore-log(28467): JXcore engine is started


motorola-Nexus 6: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(15489): Initializing JXcore engine
W/jxcore-log(15489): JXcore engine is ready
,W/jxcore-log(15489): Starting JXcore engine
,W/jxcore-log(15489): Platform android
W/jxcore-log(15489): 
,W/jxcore-log(15489): Process ARCH arm
W/jxcore-log(15489): 
,I/jxcore-log(15489): JXcore Cordova bridge is ready!
I/jxcore-log(15489): 
,W/jxcore-log(15489): JXcore engine is started


```

####Node name: thali06
Console output:
```
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:0 
child process exited with code 0 on device FA55PYS00566 
Error! Unexpected exit on device 7970f88c app:com.test.thalitest code:0 
child process exited with code 0 on device 7970f88c 
Error! Unexpected exit on device 022678fb504e29b0 app:com.test.thalitest code:0 
child process exited with code 0 on device 022678fb504e29b0 
Android task is completed 
```

Logcat output:
```
HTC-HTC One M8s: 
--------- beginning of system
,--------- beginning of main
,W/jxcore-log(25470): Initializing JXcore engine,
W/jxcore-log(25470): JXcore engine is ready
,W/jxcore-log(25470): Starting JXcore engine
,W/jxcore-log(25470): Platform android,
W/jxcore-log(25470): 
W/jxcore-log(25470): Process ARCH arm
W/jxcore-log(25470): 
,I/jxcore-log(25470): JXcore Cordova bridge is ready!,
,I/jxcore-log(25470): 
W/jxcore-log(25470): JXcore engine is started


samsung-SM-A300FU: 
--------- beginning of main
--------- beginning of system
,W/jxcore-log(15834): Initializing JXcore engine
W/jxcore-log(15834): JXcore engine is ready
,W/jxcore-log(15834): Starting JXcore engine
,W/jxcore-log(15834): Platform android
W/jxcore-log(15834): 
W/jxcore-log(15834): Process ARCH arm
W/jxcore-log(15834): 
,I/jxcore-log(15834): JXcore Cordova bridge is ready!
I/jxcore-log(15834): 
W/jxcore-log(15834): JXcore engine is started


LGE-LG-D802: 
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
,W/jxcore-log(21474): Initializing JXcore engine
,W/jxcore-log(21474): JXcore engine is ready
,W/jxcore-log(21474): Starting JXcore engine
,W/jxcore-log(21474): Platform android
W/jxcore-log(21474): 
,W/jxcore-log(21474): Process ARCH arm
W/jxcore-log(21474): 
,I/jxcore-log(21474): JXcore Cordova bridge is ready!
I/jxcore-log(21474): 
,W/jxcore-log(21474): JXcore engine is started


```

####Node name: thali07
Console output:
```
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:null 
child process exited with code null on device 4db5c8cc 
Error! Unexpected exit on device c5afcdcb app:com.test.thalitest code:null 
child process exited with code null on device c5afcdcb 
Android task is completed 
```

Logcat output:
```
samsung-SM-A500FU: 
--------- beginning of system
,--------- beginning of main
,W/jxcore-log(19484): Initializing JXcore engine
,W/jxcore-log(19484): JXcore engine is ready
,W/jxcore-log(19484): Starting JXcore engine
,W/jxcore-log(19484): Platform android
W/jxcore-log(19484): 
W/jxcore-log(19484): Process ARCH arm
W/jxcore-log(19484): 
,I/jxcore-log(19484): JXcore Cordova bridge is ready!
I/jxcore-log(19484): 
,W/jxcore-log(19484): JXcore engine is started


samsung-SM-G900F: 
--------- beginning of main
--------- beginning of system
,W/jxcore-log(26309): Initializing JXcore engine
W/jxcore-log(26309): JXcore engine is ready
,W/jxcore-log(26309): Starting JXcore engine
,W/jxcore-log(26309): Platform android
W/jxcore-log(26309): 
W/jxcore-log(26309): Process ARCH arm
W/jxcore-log(26309): 
,I/jxcore-log(26309): JXcore Cordova bridge is ready!
I/jxcore-log(26309): 
,W/jxcore-log(26309): JXcore engine is started


```

####Node name: thali08
Console output:
```
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:null 
child process exited with code null on device 4325e43f 
Error! Unexpected exit on device HT574YC04723 app:com.test.thalitest code:null 
child process exited with code null on device HT574YC04723 
Android task is completed 
```

Logcat output:
```
samsung-SM-A300FU: 
--------- beginning of system
,--------- beginning of main
,W/jxcore-log(23371): Initializing JXcore engine
W/jxcore-log(23371): JXcore engine is ready
,W/jxcore-log(23371): Starting JXcore engine
,W/jxcore-log(23371): Platform android
W/jxcore-log(23371): 
W/jxcore-log(23371): Process ARCH arm
W/jxcore-log(23371): 
,I/jxcore-log(23371): JXcore Cordova bridge is ready!,
I/jxcore-log(23371): 
W/jxcore-log(23371): JXcore engine is started


HTC-HTC Desire 820: 
--------- beginning of /dev/log/main
--------- beginning of /dev/log/system
,W/jxcore-log( 8146): Initializing JXcore engine
W/jxcore-log( 8146): JXcore engine is ready
W/jxcore-log( 8146): Starting JXcore engine
W/jxcore-log( 8146): Platform android
W/jxcore-log( 8146): 
W/jxcore-log( 8146): Process ARCH arm
W/jxcore-log( 8146): 
,I/jxcore-log( 8146): JXcore Cordova bridge is ready!
I/jxcore-log( 8146): 
W/jxcore-log( 8146): JXcore engine is started


```

####Node name: thali09
Console output:
```
Error! Unexpected exit on device 0c6a0f3c0bdb4e77 app:com.test.thalitest code:null 
child process exited with code null on device 0c6a0f3c0bdb4e77 
Error! Unexpected exit on device CC51WYC03425 app:com.test.thalitest code:null 
child process exited with code null on device CC51WYC03425 
Android task is completed 
```

Logcat output:
```
LGE-Nexus 5: 
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
,W/jxcore-log(13534): Initializing JXcore engine
,W/jxcore-log(13534): JXcore engine is ready
,W/jxcore-log(13534): Starting JXcore engine
,W/jxcore-log(13534): Platform android
W/jxcore-log(13534): 
,W/jxcore-log(13534): Process ARCH arm
W/jxcore-log(13534): 
,I/jxcore-log(13534): JXcore Cordova bridge is ready!
I/jxcore-log(13534): 
,W/jxcore-log(13534): JXcore engine is started


HTC-HTC Desire 820: 
--------- beginning of /dev/log/main
--------- beginning of /dev/log/system
,W/jxcore-log( 1159): Initializing JXcore engine
,W/jxcore-log( 1159): JXcore engine is ready
,W/jxcore-log( 1159): Starting JXcore engine
,W/jxcore-log( 1159): Platform android
W/jxcore-log( 1159): 
,W/jxcore-log( 1159): Process ARCH arm
W/jxcore-log( 1159): 
,I/jxcore-log( 1159): JXcore Cordova bridge is ready!
I/jxcore-log( 1159): 
,W/jxcore-log( 1159): JXcore engine is started


```




#### Integration Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":25}}
Star Android tests : performance tests, start tests with timer

Test[0]: testSendData.js, timeout : 300000, data : {"timeout":"250000","rounds":"3","dataTimeout":"60000","dataAmount":"100000","conReTryTimeout":"2000","conReTryCount":"1"}
Test[1]: testSendData.js, timeout : 300000, data : {"timeout":"250000","rounds":"3","dataTimeout":"60000","dataAmount":"100000","conReTryTimeout":"2000","conReTryCount":"1"}
Test[2]: testSendData.js, timeout : 300000, data : {"timeout":"250000","rounds":"3","dataTimeout":"60000","dataAmount":"100000","conReTryTimeout":"2000","conReTryCount":"1"}
Star iOs tests : performance tests, start tests with timer
Test[0]: testSendData.js, timeout : 300000, data : {"timeout":"250000","rounds":"3","dataTimeout":"60000","dataAmount":"100000","conReTryTimeout":"2000","conReTryCount":"1"}
Test[1]: testSendData.js, timeout : 300000, data : {"timeout":"250000","rounds":"3","dataTimeout":"60000","dataAmount":"100000","conReTryTimeout":"2000","conReTryCount":"1"}
Test[2]: testSendData.js, timeout : 300000, data : {"timeout":"250000","rounds":"3","dataTimeout":"60000","dataAmount":"100000","conReTryTimeout":"2000","conReTryCount":"1"}

listening on *:3000

-------------- We got wait done, now starting the testing process ------------------


 
Run IS script aborted
 
[0;31mexecution aborted
 [0m

```

