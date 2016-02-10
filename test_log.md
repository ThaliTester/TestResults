#### Test 58380500a584679 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":21}}
2016-02-10T01:28:44.004Z - info: listening on *:3000

2016-02-10T01:28:45.700Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:0

2016-02-10T01:28:45.722Z - debug: Device presented: LGE-LG-D855 (android) unittest socket:1

2016-02-10T01:28:45.725Z - info: Required number of android devices presented (2)

2016-02-10T01:28:45.728Z - info: Starting unit test run for platform: android

2016-02-10T01:28:45.820Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:2

2016-02-10T01:28:45.821Z - info: Discarding surplus device: LGE-LG-H815

2016-02-10T01:28:46.025Z - debug: Device presented: LGE-LG-D722 (android) unittest socket:4

2016-02-10T01:28:46.026Z - info: Discarding surplus device: LGE-LG-D722

2016-02-10T01:28:46.158Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:5

2016-02-10T01:28:46.159Z - info: Discarding surplus device: motorola-Nexus 6

2016-02-10T01:28:46.193Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:6

2016-02-10T01:28:46.194Z - info: Discarding surplus device: LGE-Nexus 5

2016-02-10T01:28:46.201Z - info: Running on android test: multiplex can send data

2016-02-10T01:28:46.352Z - info: Running on android test: enqueue and run in order

2016-02-10T01:28:46.613Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:3

2016-02-10T01:28:46.643Z - debug: Socket disconnected: transport close 6 (LGE-Nexus 5)

2016-02-10T01:28:46.763Z - info: Running on android test: basic

2016-02-10T01:28:46.777Z - debug: Socket disconnected: transport close 2 (LGE-LG-H815)

2016-02-10T01:28:46.863Z - debug: Socket disconnected: transport close 5 (motorola-Nexus 6)

2016-02-10T01:28:46.890Z - info: Running on android test: another

2016-02-10T01:28:46.962Z - info: Running on android test: successfully create a new pkcs12 file and return hash value

2016-02-10T01:28:47.220Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:7

2016-02-10T01:28:47.221Z - info: Required number of ios devices presented (2)

2016-02-10T01:28:47.222Z - info: Starting unit test run for platform: ios

2016-02-10T01:28:47.262Z - info: Running on android test: successfully read a previous pkcs12 file and return hash value

2016-02-10T01:28:47.271Z - debug: Socket disconnected: transport close 4 (LGE-LG-D722)

2016-02-10T01:28:47.468Z - info: Running on android test: failed to extract public key because of corrupt pkcs12 file

2016-02-10T01:28:47.608Z - info: Running on android test: failed to get mobile documents path

2016-02-10T01:28:47.746Z - info: Running on android test: #init should register the peerAvailabilityChanged event

2016-02-10T01:28:47.847Z - info: Running on android test: #init should register the networkChanged event

2016-02-10T01:28:47.937Z - info: Running on android test: #startBroadcasting should throw on null device name

2016-02-10T01:28:48.050Z - info: Running on android test: #startBroadcasting should throw on empty string device name

2016-02-10T01:28:48.204Z - info: Running on android test: #startBroadcasting should throw on non-number port

2016-02-10T01:28:48.312Z - info: Running on android test: #startBroadcasting should throw on NaN port

2016-02-10T01:28:48.405Z - info: Running on android test: #startBroadcasting should throw on negative port

2016-02-10T01:28:48.493Z - info: Running on android test: #startBroadcasting should throw on too large port

2016-02-10T01:28:48.582Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-10T01:28:48.665Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-10T01:28:48.748Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-10T01:28:48.832Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-10T01:28:48.848Z - info: Running on ios test: multiplex can send data

2016-02-10T01:28:48.948Z - info: Running on android test: #connect should call Mobile("Connect") with a port and without an error

2016-02-10T01:28:49.042Z - info: Running on android test: #connect should call Mobile("Connect") and handle an error

2016-02-10T01:28:49.128Z - info: Running on android test: should call Mobile("Disconnect") without an error

2016-02-10T01:28:49.235Z - info: Running on android test: should call Mobile("Disconnect") and handle an error

2016-02-10T01:28:49.330Z - info: Running on android test: #start should fail if called twice in a row

2016-02-10T01:28:49.438Z - info: Running on android test: #startListeningForAdvertisements should fail if start not called

2016-02-10T01:28:49.546Z - info: Running on android test: should be able to call #stopListeningForAdvertisements many times

2016-02-10T01:28:49.669Z - info: Running on android test: should be able to call #startListeningForAdvertisements many times

2016-02-10T01:28:49.816Z - info: Running on android test: should be able to call #startUpdateAdvertisingAndListening many times

2016-02-10T01:28:50.019Z - info: Running on android test: #startUpdateAdvertisingAndListening should fail if start not called

2016-02-10T01:28:50.105Z - info: Running on android test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-10T01:28:50.429Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:8

2016-02-10T01:28:50.430Z - info: Discarding surplus device: samsung-SM-N910C

2016-02-10T01:28:51.045Z - debug: Socket disconnected: transport close 8 (samsung-SM-N910C)

2016-02-10T01:28:53.092Z - info: Running on android test: ThaliEmitter calls startBroadcasting twice with error

2016-02-10T01:28:53.378Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:9

2016-02-10T01:28:53.379Z - info: Discarding surplus device: samsung-SM-G900F

2016-02-10T01:28:54.072Z - debug: Socket disconnected: transport close 9 (samsung-SM-G900F)

2016-02-10T01:28:54.331Z - info: Running on ios test: enqueue and run in order

2016-02-10T01:28:59.657Z - info: Running on android test: ThaliEmitter throws on connection to bad peer

2016-02-10T01:29:00.116Z - info: Running on ios test: basic

2016-02-10T01:29:04.146Z - info: Running on android test: ThaliEmitter throws on disconnect to bad peer

2016-02-10T01:29:04.791Z - info: Running on android test: #generatePreambleAndBeacons null ECDH for local device

2016-02-10T01:29:04.978Z - info: Running on android test: #generatePreambleAndBeacons expiration out of range lower

2016-02-10T01:29:05.028Z - info: Running on ios test: another

2016-02-10T01:29:05.365Z - info: Running on android test: #generatePreambleAndBeacons expiration out of range upper

2016-02-10T01:29:05.468Z - info: Running on android test: #generatePreambleAndBeacons empty keys to notify

2016-02-10T01:29:05.605Z - info: Running on android test: #generatePreambleAndBeacons multiple keys to notify

2016-02-10T01:29:10.633Z - info: Running on android test: #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-02-10T01:29:10.877Z - info: Running on android test: #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-02-10T01:29:11.028Z - info: Running on android test: #parseBeacons expiration out of range lower

2016-02-10T01:29:11.207Z - info: Running on android test: #parseBeacons no beacons returns null

2016-02-10T01:29:16.425Z - info: Running on android test: #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-02-10T01:29:23.605Z - info: Running on android test: #parseBeacons addressBookCallback fails decrypt

2016-02-10T01:29:24.070Z - info: Running on android test: #parseBeacons addressBookCallback returns no matches

2016-02-10T01:29:24.397Z - info: Running on android test: #parseBeacons addressBookCallback returns public key

2016-02-10T01:29:24.959Z - info: Running on android test: #parseBeacons with beacons both for and not for the user

2016-02-10T01:29:25.278Z - info: Running on android test: After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-02-10T01:29:33.746Z - info: Running on android test: #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-02-10T01:29:33.969Z - info: Running on android test: messages with invalid location or USN should be ignored

2016-02-10T01:29:34.253Z - info: Running on android test: verify that Thali-specific messages are filtered correctly

2016-02-10T01:29:34.400Z - info: Running on android test: #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-02-10T01:29:34.513Z - info: Running on android test: #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-02-10T01:29:34.611Z - info: Running on android test: #startUpdateAdvertisingAndListening should start hosting given router object

2016-02-10T01:29:34.779Z - info: Running on android test: #stop can be called multiple times in a row

2016-02-10T01:29:34.870Z - info: Running on android test: #startListeningForAdvertisements can be called multiple times in a row

2016-02-10T01:29:34.971Z - info: Running on android test: #stopListeningForAdvertisements can be called multiple times in a row

2016-02-10T01:29:35.367Z - info: Running on android test: #stopAdvertisingAndListening can be called multiple times in a row

2016-02-10T01:29:35.483Z - info: Running on android test: functions are run from a queue in the right order

2016-02-10T01:29:35.653Z - info: Test run on android complete

2016-02-10T01:29:35.655Z - info: 

-== UNIT TEST RESULTS ==-

2016-02-10T01:29:35.657Z - info: PLATFORM: android

2016-02-10T01:29:35.658Z - info: RESULT: PASS

2016-02-10T01:29:35.659Z - info: 60 of 60 tests completed

2016-02-10T01:29:35.660Z - info: 60/60 passed (0 failures)

2016-02-10T01:29:35.661Z - info: --- Test Details ---



2016-02-10T01:29:35.663Z - info: multiplex can send data - pass

2016-02-10T01:29:35.664Z - info: enqueue and run in order - pass

2016-02-10T01:29:35.665Z - info: basic - pass

2016-02-10T01:29:35.666Z - info: another - pass

2016-02-10T01:29:35.666Z - info: successfully create a new pkcs12 file and return hash value - pass

2016-02-10T01:29:35.667Z - info: successfully read a previous pkcs12 file and return hash value - pass
2016-02-10T01:29:35.668Z - info: failed to extract public key because of corrupt pkcs12 file - pass

2016-02-10T01:29:35.669Z - info: failed to get mobile documents path - pass

2016-02-10T01:29:35.670Z - info: #init should register the peerAvailabilityChanged event - pass

2016-02-10T01:29:35.671Z - info: #init should register the networkChanged event - pass
2016-02-10T01:29:35.672Z - info: #startBroadcasting should throw on null device name - pass

2016-02-10T01:29:35.673Z - info: #startBroadcasting should throw on empty string device name - pass

2016-02-10T01:29:35.674Z - info: #startBroadcasting should throw on non-number port - pass
2016-02-10T01:29:35.674Z - info: #startBroadcasting should throw on NaN port - pass
2016-02-10T01:29:35.675Z - info: #startBroadcasting should throw on negative port - pass
2016-02-10T01:29:35.676Z - info: #startBroadcasting should throw on too large port - pass
2016-02-10T01:29:35.677Z - info: #startBroadcasting should call Mobile("StartBroadcasting") without an error - pass

2016-02-10T01:29:35.678Z - info: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error - pass
2016-02-10T01:29:35.682Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") without an error - pass

2016-02-10T01:29:35.683Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error - pass
2016-02-10T01:29:35.684Z - info: #connect should call Mobile("Connect") with a port and without an error - pass

2016-02-10T01:29:35.685Z - info: #connect should call Mobile("Connect") and handle an error - pass

2016-02-10T01:29:35.686Z - info: should call Mobile("Disconnect") without an error - pass

2016-02-10T01:29:35.687Z - info: should call Mobile("Disconnect") and handle an error - pass
2016-02-10T01:29:35.688Z - info: #start should fail if called twice in a row - pass
2016-02-10T01:29:35.689Z - info: #startListeningForAdvertisements should fail if start not called - pass
2016-02-10T01:29:35.689Z - info: should be able to call #stopListeningForAdvertisements many times - pass

2016-02-10T01:29:35.690Z - info: should be able to call #startListeningForAdvertisements many times - pass
2016-02-10T01:29:35.691Z - info: should be able to call #startUpdateAdvertisingAndListening many times - pass

2016-02-10T01:29:35.692Z - info: #startUpdateAdvertisingAndListening should fail if start not called - pass
2016-02-10T01:29:35.693Z - info: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error - pass

2016-02-10T01:29:35.694Z - info: ThaliEmitter calls startBroadcasting twice with error - pass
2016-02-10T01:29:35.696Z - info: ThaliEmitter throws on connection to bad peer - pass
2016-02-10T01:29:35.700Z - info: ThaliEmitter throws on disconnect to bad peer - pass
2016-02-10T01:29:35.701Z - info: #generatePreambleAndBeacons null ECDH for local device - pass
2016-02-10T01:29:35.702Z - info: #generatePreambleAndBeacons expiration out of range lower - pass
2016-02-10T01:29:35.702Z - info: #generatePreambleAndBeacons expiration out of range upper - pass
2016-02-10T01:29:35.703Z - info: #generatePreambleAndBeacons empty keys to notify - pass
2016-02-10T01:29:35.704Z - info: #generatePreambleAndBeacons multiple keys to notify - pass
2016-02-10T01:29:35.704Z - info: #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble - pass
2016-02-10T01:29:35.705Z - info: #parseBeacons invalid expiration in beaconStreamWithPreAmble - pass
2016-02-10T01:29:35.706Z - info: #parseBeacons expiration out of range lower - pass
2016-02-10T01:29:35.706Z - info: #parseBeacons no beacons returns null - pass
2016-02-10T01:29:35.707Z - info: #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble - pass
2016-02-10T01:29:35.708Z - info: #parseBeacons addressBookCallback fails decrypt - pass
2016-02-10T01:29:35.708Z - info: #parseBeacons addressBookCallback returns no matches - pass

2016-02-10T01:29:35.709Z - info: #parseBeacons addressBookCallback returns public key - pass
2016-02-10T01:29:35.710Z - info: #parseBeacons with beacons both for and not for the user - pass

2016-02-10T01:29:35.711Z - info: After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted - pass

2016-02-10T01:29:35.712Z - info: #startUpdateAdvertisingAndListening should use different USN after every invocation - pass

2016-02-10T01:29:35.713Z - info: messages with invalid location or USN should be ignored - pass
2016-02-10T01:29:35.714Z - info: verify that Thali-specific messages are filtered correctly - pass
2016-02-10T01:29:35.714Z - info: #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass
2016-02-10T01:29:35.715Z - info: #startUpdateAdvertisingAndListening should fail if router server starting fails - pass
2016-02-10T01:29:35.716Z - info: #startUpdateAdvertisingAndListening should start hosting given router object - pass
2016-02-10T01:29:35.717Z - info: #stop can be called multiple times in a row - pass

2016-02-10T01:29:35.718Z - info: #startListeningForAdvertisements can be called multiple times in a row - pass

2016-02-10T01:29:35.718Z - info: #stopListeningForAdvertisements can be called multiple times in a row - pass

2016-02-10T01:29:35.719Z - info: #stopAdvertisingAndListening can be called multiple times in a row - pass

2016-02-10T01:29:35.720Z - info: functions are run from a queue in the right order - pass

2016-02-10T01:29:35.722Z - info: 

-== END ==-

2016-02-10T01:30:02.197Z - info: Running on ios test: successfully create a new pkcs12 file and return hash value

2016-02-10T01:30:46.957Z - info: Running on ios test: successfully read a previous pkcs12 file and return hash value

2016-02-10T01:30:58.213Z - info: Running on ios test: failed to extract public key because of corrupt pkcs12 file

2016-02-10T01:31:00.656Z - debug: Socket disconnected: ping timeout 0 (samsung-SM-G900F)

2016-02-10T01:31:00.664Z - debug: Socket disconnected: ping timeout 1 (LGE-LG-D855)

2016-02-10T01:31:06.402Z - info: Running on ios test: failed to get mobile documents path

2016-02-10T01:31:25.841Z - info: Running on ios test: #init should register the peerAvailabilityChanged event

2016-02-10T01:31:42.622Z - info: Running on ios test: #init should register the networkChanged event

2016-02-10T01:31:46.920Z - info: Running on ios test: #startBroadcasting should throw on null device name

2016-02-10T01:33:11.936Z - debug: Socket disconnected: ping timeout 3 (Apple-Iphone5-1)

2016-02-10T01:41:36.732Z - debug: Socket disconnected: transport close 7 (Apple-IpadAir2-1)


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m
2016-02-10T01:29:14.057Z - error: test server: Device undefined

2016-02-10T01:29:51.118Z - error: test server: Device undefined

2016-02-10T01:30:17.911Z - error: test server: Device undefined

2016-02-10T01:30:30.203Z - error: test server: Device undefined

2016-02-10T01:31:25.496Z - error: test server: Device undefined

2016-02-10T01:31:34.883Z - error: test server: Device undefined

2016-02-10T01:31:55.954Z - error: test server: Device undefined


```


Logs for system : 
```

ios : Error: Command failed: true
Getting the list of iOS devices 
Deploying iOS test app 
uninstalling the application 
installing the application 
ios: child process exited with code null on device 2a65f58f9902a701b5c9a55b2befb18672927474 
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/58380500a584679_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/58380500a584679_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/58380500a584679_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/iOS_Iphone5-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/58380500a584679_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/iOS_server.md)


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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/58380500a584679_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/58380500a584679_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/58380500a584679_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/58380500a584679_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/58380500a584679_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/58380500a584679_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/58380500a584679_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali03_samsung-SM-G800F.md)

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
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/58380500a584679_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/58380500a584679_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/58380500a584679_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali04_samsung-SM-G900F.md)

####Node name: thali05
Console output:
```
Error! Unexpected exit on device 954a12ed app:com.test.thalitest code:0 
child process exited with code 0 on device 954a12ed 
STOP log received from  ZX1G429CRK Test has  SUCCEEDED
Device test finished on ZX1G429CRK 
Android task is completed. [FAILED]
```
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/58380500a584679_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/58380500a584679_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali05_samsung-SM-G800H.md)

####Node name: thali06
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 7970f88c app:com.test.thalitest code:0 
child process exited with code 0 on device 7970f88c 
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:null 
child process exited with code null on device FA55PYS00566 
Error! Unexpected exit on device 022678fb504e29b0 app:com.test.thalitest code:0 
child process exited with code 0 on device 022678fb504e29b0 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/58380500a584679_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/58380500a584679_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/58380500a584679_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali06_LGE-LG-D802.md)

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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/58380500a584679_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/58380500a584679_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device HT574YC04723 app:com.test.thalitest code:null 
child process exited with code null on device HT574YC04723 
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:null 
child process exited with code null on device 4325e43f 
Android task is completed. [FAILED]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/58380500a584679_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/58380500a584679_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/58380500a584679_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/58380500a584679_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali09_LGE-Nexus 5.md)




