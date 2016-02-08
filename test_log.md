#### Test 58380500962e22b Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":21}}
2016-02-08T23:19:06.823Z - info: listening on *:3000

2016-02-08T23:19:07.592Z - debug: Device presented: LGE-LG-D855 (android) unittest socket:0

2016-02-08T23:19:08.851Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:1

2016-02-08T23:19:08.854Z - info: Required number of android devices presented (2)

2016-02-08T23:19:08.857Z - info: Starting unit test run for platform: android

2016-02-08T23:19:08.894Z - debug: Device presented: LGE-LG-D722 (android) unittest socket:2

2016-02-08T23:19:08.895Z - info: Discarding surplus device: LGE-LG-D722

2016-02-08T23:19:09.152Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:3

2016-02-08T23:19:09.153Z - info: Discarding surplus device: samsung-SM-N910C

2016-02-08T23:19:09.520Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:4

2016-02-08T23:19:09.521Z - info: Discarding surplus device: motorola-Nexus 6

2016-02-08T23:19:09.816Z - debug: Socket disconnected: transport close 3 (samsung-SM-N910C)

2016-02-08T23:19:10.054Z - debug: Socket disconnected: transport close 2 (LGE-LG-D722)

2016-02-08T23:19:10.211Z - debug: Socket disconnected: transport close 4 (motorola-Nexus 6)

2016-02-08T23:19:10.482Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:5

2016-02-08T23:19:10.754Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:6

2016-02-08T23:19:10.755Z - info: Discarding surplus device: LGE-Nexus 5

2016-02-08T23:19:11.044Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:7

2016-02-08T23:19:11.045Z - info: Discarding surplus device: LGE-LG-H815

2016-02-08T23:19:11.151Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:8

2016-02-08T23:19:11.152Z - info: Required number of ios devices presented (2)

2016-02-08T23:19:11.154Z - info: Starting unit test run for platform: ios

2016-02-08T23:19:11.269Z - debug: Socket disconnected: transport close 6 (LGE-Nexus 5)

2016-02-08T23:19:11.986Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:9

2016-02-08T23:19:11.987Z - info: Discarding surplus device: samsung-SM-G900F

2016-02-08T23:19:12.041Z - debug: Socket disconnected: transport close 7 (LGE-LG-H815)

2016-02-08T23:19:12.656Z - debug: Socket disconnected: transport close 9 (samsung-SM-G900F)

2016-02-08T23:19:12.748Z - info: Running on android test: multiplex can send data

2016-02-08T23:19:13.051Z - info: Running on android test: enqueue and run in order

2016-02-08T23:19:13.463Z - info: Running on android test: basic

2016-02-08T23:19:13.570Z - info: Running on ios test: multiplex can send data

2016-02-08T23:19:13.604Z - info: Running on android test: another

2016-02-08T23:19:13.825Z - info: Running on android test: successfully create a new pkcs12 file and return hash value

2016-02-08T23:19:14.116Z - info: Running on android test: successfully read a previous pkcs12 file and return hash value

2016-02-08T23:19:14.275Z - info: Running on android test: failed to extract public key because of corrupt pkcs12 file

2016-02-08T23:19:14.338Z - info: Running on android test: failed to get mobile documents path

2016-02-08T23:19:14.383Z - info: Running on android test: #init should register the peerAvailabilityChanged event

2016-02-08T23:19:14.434Z - info: Running on android test: #init should register the networkChanged event

2016-02-08T23:19:14.496Z - info: Running on android test: #startBroadcasting should throw on null device name

2016-02-08T23:19:14.546Z - info: Running on android test: #startBroadcasting should throw on empty string device name

2016-02-08T23:19:14.819Z - info: Running on android test: #startBroadcasting should throw on non-number port

2016-02-08T23:19:14.992Z - info: Running on android test: #startBroadcasting should throw on NaN port

2016-02-08T23:19:15.065Z - info: Running on android test: #startBroadcasting should throw on negative port

2016-02-08T23:19:15.125Z - info: Running on android test: #startBroadcasting should throw on too large port

2016-02-08T23:19:15.197Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-08T23:19:15.274Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-08T23:19:15.343Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-08T23:19:15.411Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-08T23:19:15.491Z - info: Running on android test: #connect should call Mobile("Connect") with a port and without an error

2016-02-08T23:19:15.555Z - info: Running on android test: #connect should call Mobile("Connect") and handle an error

2016-02-08T23:19:15.894Z - info: Running on android test: should call Mobile("Disconnect") without an error

2016-02-08T23:19:16.118Z - info: Running on android test: should call Mobile("Disconnect") and handle an error

2016-02-08T23:19:16.206Z - info: Running on android test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-08T23:19:18.416Z - info: Running on ios test: enqueue and run in order

2016-02-08T23:19:20.055Z - info: Running on android test: ThaliEmitter calls startBroadcasting twice with error

2016-02-08T23:19:20.118Z - info: Running on ios test: basic

2016-02-08T23:19:20.443Z - info: Running on ios test: another

2016-02-08T23:19:20.659Z - info: Running on ios test: successfully create a new pkcs12 file and return hash value

2016-02-08T23:19:21.148Z - info: Running on ios test: successfully read a previous pkcs12 file and return hash value

2016-02-08T23:19:21.320Z - info: Running on ios test: failed to extract public key because of corrupt pkcs12 file

2016-02-08T23:19:21.673Z - info: Running on ios test: failed to get mobile documents path

2016-02-08T23:19:21.852Z - info: Running on ios test: #init should register the peerAvailabilityChanged event

2016-02-08T23:19:22.172Z - info: Running on ios test: #init should register the networkChanged event

2016-02-08T23:19:22.375Z - info: Running on ios test: #startBroadcasting should throw on null device name

2016-02-08T23:19:22.675Z - info: Running on ios test: #startBroadcasting should throw on empty string device name

2016-02-08T23:19:22.846Z - info: Running on ios test: #startBroadcasting should throw on non-number port

2016-02-08T23:19:23.034Z - info: Running on ios test: #startBroadcasting should throw on NaN port

2016-02-08T23:19:23.214Z - info: Running on ios test: #startBroadcasting should throw on negative port

2016-02-08T23:19:23.288Z - info: Running on ios test: #startBroadcasting should throw on too large port

2016-02-08T23:19:23.373Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-08T23:19:23.447Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-08T23:19:23.520Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-08T23:19:23.629Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-08T23:19:23.711Z - info: Running on ios test: #connect should call Mobile("Connect") with a port and without an error

2016-02-08T23:19:23.797Z - info: Running on ios test: #connect should call Mobile("Connect") and handle an error

2016-02-08T23:19:23.900Z - info: Running on ios test: should call Mobile("Disconnect") without an error

2016-02-08T23:19:23.975Z - info: Running on ios test: should call Mobile("Disconnect") and handle an error

2016-02-08T23:19:24.052Z - info: Running on ios test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-08T23:19:24.479Z - info: Running on ios test: ThaliEmitter calls startBroadcasting twice with error

2016-02-08T23:19:25.484Z - info: Running on ios test: ThaliEmitter throws on connection to bad peer

2016-02-08T23:19:26.092Z - info: Running on ios test: ThaliEmitter throws on disconnect to bad peer

2016-02-08T23:19:26.607Z - info: Running on ios test: ThaliEmitter can discover and connect to peers

2016-02-08T23:19:27.216Z - info: Running on android test: ThaliEmitter throws on connection to bad peer

2016-02-08T23:19:31.841Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double connect

2016-02-08T23:19:32.121Z - info: Running on android test: ThaliEmitter throws on disconnect to bad peer

2016-02-08T23:19:32.807Z - info: Running on android test: After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-02-08T23:19:33.230Z - info: Running on android test: #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-02-08T23:19:33.471Z - info: Running on android test: messages with invalid location or USN should be ignored

2016-02-08T23:19:33.576Z - info: Running on android test: verify that Thali-specific messages are filtered correctly

2016-02-08T23:19:33.680Z - info: Running on android test: #start should fail if called twice in a row

2016-02-08T23:19:33.765Z - info: Running on android test: #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-02-08T23:19:33.895Z - info: Running on android test: #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-02-08T23:19:34.053Z - info: Running on android test: #startUpdateAdvertisingAndListening should start hosting given router object

2016-02-08T23:19:34.319Z - info: Running on android test: #stop can be called multiple times in a row

2016-02-08T23:19:34.421Z - info: Running on android test: #startListeningForAdvertisements can be called multiple times in a row

2016-02-08T23:19:34.491Z - info: Running on android test: #stopListeningForAdvertisements can be called multiple times in a row

2016-02-08T23:19:34.577Z - info: Running on android test: #stopAdvertisingAndListening can be called multiple times in a row

2016-02-08T23:19:34.642Z - info: Running on android test: functions are run from a queue in the right order

2016-02-08T23:19:34.739Z - info: Test run on android complete

2016-02-08T23:19:34.742Z - info: 

-== UNIT TEST RESULTS ==-

2016-02-08T23:19:34.743Z - info: PLATFORM: android

2016-02-08T23:19:34.744Z - info: RESULT: PASS

2016-02-08T23:19:34.745Z - info: 41 of 41 tests completed

2016-02-08T23:19:34.746Z - info: 41/41 passed (0 failures)

2016-02-08T23:19:34.747Z - info: --- Test Details ---



2016-02-08T23:19:34.747Z - info: multiplex can send data - pass

2016-02-08T23:19:34.748Z - info: enqueue and run in order - pass

2016-02-08T23:19:34.749Z - info: basic - pass

2016-02-08T23:19:34.750Z - info: another - pass

2016-02-08T23:19:34.751Z - info: successfully create a new pkcs12 file and return hash value - pass
2016-02-08T23:19:34.752Z - info: successfully read a previous pkcs12 file and return hash value - pass
2016-02-08T23:19:34.752Z - info: failed to extract public key because of corrupt pkcs12 file - pass
2016-02-08T23:19:34.753Z - info: failed to get mobile documents path - pass

2016-02-08T23:19:34.754Z - info: #init should register the peerAvailabilityChanged event - pass
2016-02-08T23:19:34.754Z - info: #init should register the networkChanged event - pass
2016-02-08T23:19:34.755Z - info: #startBroadcasting should throw on null device name - pass

2016-02-08T23:19:34.756Z - info: #startBroadcasting should throw on empty string device name - pass

2016-02-08T23:19:34.762Z - info: #startBroadcasting should throw on non-number port - pass

2016-02-08T23:19:34.763Z - info: #startBroadcasting should throw on NaN port - pass

2016-02-08T23:19:34.764Z - info: #startBroadcasting should throw on negative port - pass
2016-02-08T23:19:34.765Z - info: #startBroadcasting should throw on too large port - pass
2016-02-08T23:19:34.766Z - info: #startBroadcasting should call Mobile("StartBroadcasting") without an error - pass

2016-02-08T23:19:34.766Z - info: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error - pass
2016-02-08T23:19:34.767Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") without an error - pass

2016-02-08T23:19:34.768Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error - pass
2016-02-08T23:19:34.769Z - info: #connect should call Mobile("Connect") with a port and without an error - pass
2016-02-08T23:19:34.769Z - info: #connect should call Mobile("Connect") and handle an error - pass
2016-02-08T23:19:34.770Z - info: should call Mobile("Disconnect") without an error - pass
2016-02-08T23:19:34.771Z - info: should call Mobile("Disconnect") and handle an error - pass

2016-02-08T23:19:34.772Z - info: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error - pass
2016-02-08T23:19:34.772Z - info: ThaliEmitter calls startBroadcasting twice with error - pass
2016-02-08T23:19:34.775Z - info: ThaliEmitter throws on connection to bad peer - pass
2016-02-08T23:19:34.779Z - info: ThaliEmitter throws on disconnect to bad peer - pass
2016-02-08T23:19:34.779Z - info: After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted - pass
2016-02-08T23:19:34.780Z - info: #startUpdateAdvertisingAndListening should use different USN after every invocation - pass
2016-02-08T23:19:34.781Z - info: messages with invalid location or USN should be ignored - pass
2016-02-08T23:19:34.782Z - info: verify that Thali-specific messages are filtered correctly - pass
2016-02-08T23:19:34.782Z - info: #start should fail if called twice in a row - pass
2016-02-08T23:19:34.783Z - info: #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass
2016-02-08T23:19:34.784Z - info: #startUpdateAdvertisingAndListening should fail if router server starting fails - pass
2016-02-08T23:19:34.784Z - info: #startUpdateAdvertisingAndListening should start hosting given router object - pass
2016-02-08T23:19:34.785Z - info: #stop can be called multiple times in a row - pass
2016-02-08T23:19:34.785Z - info: #startListeningForAdvertisements can be called multiple times in a row - pass

2016-02-08T23:19:34.786Z - info: #stopListeningForAdvertisements can be called multiple times in a row - pass
2016-02-08T23:19:34.787Z - info: #stopAdvertisingAndListening can be called multiple times in a row - pass

2016-02-08T23:19:34.788Z - info: functions are run from a queue in the right order - pass

2016-02-08T23:19:34.788Z - info: 

-== END ==-

2016-02-08T23:19:37.648Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-02-08T23:19:42.370Z - info: Running on ios test: ThaliEmitter can connect and send data

2016-02-08T23:19:48.602Z - info: Running on ios test: ThaliEmitter handles socket disconnect correctly

2016-02-08T23:20:05.242Z - info: Running on ios test: ThaliReplicationManager can call start without error

2016-02-08T23:20:05.548Z - info: Running on ios test: ThaliReplicationManager receives identity

2016-02-08T23:20:07.455Z - info: Running on ios test: ThaliReplicationManager replicates database

2016-02-08T23:20:56.558Z - debug: Socket disconnected: transport close 8 (Apple-IpadAir2-1)

2016-02-08T23:20:58.646Z - debug: Socket disconnected: transport close 5 (Apple-Iphone6-1)

2016-02-08T23:20:59.745Z - debug: Socket disconnected: ping timeout 0 (LGE-LG-D855)

2016-02-08T23:20:59.753Z - debug: Socket disconnected: ping timeout 1 (samsung-SM-G900F)


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

ios : Error: Command failed: true
Getting the list of iOS devices 
Deploying iOS test app 
uninstalling the application 
installing the application 
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/58380500962e22b_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/58380500962e22b_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/58380500962e22b_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/iOS_Iphone5-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/58380500962e22b_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/iOS_server.md)


###Android Logs
####Node name: thali01
Console output:
```
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
Device test finished on LGH8153b36be34 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device f56ad48d app:com.test.thalitest code:null 
child process exited with code null on device f56ad48d 
Android task is completed. [FAILED]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/58380500962e22b_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/58380500962e22b_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on LGD7228ee9cf5b 
Device test finished on 09a9416e0297d102 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/58380500962e22b_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/58380500962e22b_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali02_LGE-Nexus 5.md)

####Node name: thali03
Console output:
```
STOP log received from  LGD8553bed2d08 Test has  SUCCEEDED
Device test finished on LGD8553bed2d08 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device TA4750HV7I app:com.test.thalitest code:0 
child process exited with code 0 on device TA4750HV7I 
Error! Unexpected exit on device 320414cd475f91e3 app:com.test.thalitest code:0 
child process exited with code 0 on device 320414cd475f91e3 
Android task is completed. [FAILED]
```
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/58380500962e22b_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/58380500962e22b_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/58380500962e22b_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
STOP log received from  0be0c6c6 Test has  SUCCEEDED
Device test finished on 0be0c6c6 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1C223JKW 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/58380500962e22b_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/58380500962e22b_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/58380500962e22b_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali04_samsung-SM-G900F.md)

####Node name: thali05
Console output:
```
Error! Unexpected exit on device 954a12ed app:com.test.thalitest code:0 
child process exited with code 0 on device 954a12ed 
STOP log received from  ZX1G429CRK Test has  SUCCEEDED
Device test finished on ZX1G429CRK 
Android task is completed. [FAILED]
```
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/58380500962e22b_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/58380500962e22b_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali05_samsung-SM-G800H.md)

####Node name: thali06
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 7970f88c app:com.test.thalitest code:0 
child process exited with code 0 on device 7970f88c 
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:0 
child process exited with code 0 on device FA55PYS00566 
Error! Unexpected exit on device 022678fb504e29b0 app:com.test.thalitest code:0 
child process exited with code 0 on device 022678fb504e29b0 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/58380500962e22b_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/58380500962e22b_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/58380500962e22b_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
STOP log received from  c5afcdcb Test has  SUCCEEDED
Device test finished on c5afcdcb 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:0 
child process exited with code 0 on device 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/58380500962e22b_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/58380500962e22b_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device HT574YC04723 app:com.test.thalitest code:0 
child process exited with code 0 on device HT574YC04723 
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:0 
child process exited with code 0 on device 4325e43f 
Android task is completed. [FAILED]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/58380500962e22b_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/58380500962e22b_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali08_samsung-SM-A300FU.md)

####Node name: thali09
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device CC51WYC03425 app:com.test.thalitest code:0 
child process exited with code 0 on device CC51WYC03425 
Error! Unexpected exit on device 0c6a0f3c0bdb4e77 app:com.test.thalitest code:0 
child process exited with code 0 on device 0c6a0f3c0bdb4e77 
Android task is completed. [FAILED]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/58380500962e22b_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/58380500962e22b_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali09_LGE-Nexus 5.md)




