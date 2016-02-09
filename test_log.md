#### Test 58380500306a2c5 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":21}}
2016-02-09T22:53:14.569Z - info: listening on *:3000

2016-02-09T22:53:14.914Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:0

2016-02-09T22:53:14.974Z - debug: Device presented: LGE-LG-D855 (android) unittest socket:2

2016-02-09T22:53:14.976Z - info: Required number of android devices presented (2)

2016-02-09T22:53:14.980Z - info: Starting unit test run for platform: android

2016-02-09T22:53:15.097Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:1

2016-02-09T22:53:15.362Z - info: Running on android test: multiplex can send data

2016-02-09T22:53:15.394Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:3

2016-02-09T22:53:15.395Z - info: Required number of ios devices presented (2)

2016-02-09T22:53:15.397Z - info: Starting unit test run for platform: ios

2016-02-09T22:53:15.448Z - debug: Device presented: HTC-HTC One M8s (android) unittest socket:4

2016-02-09T22:53:15.449Z - info: Discarding surplus device: HTC-HTC One M8s

2016-02-09T22:53:15.589Z - info: Running on android test: enqueue and run in order

2016-02-09T22:53:15.647Z - info: Running on ios test: multiplex can send data

2016-02-09T22:53:15.971Z - info: Running on android test: basic

2016-02-09T22:53:15.999Z - info: Running on ios test: enqueue and run in order

2016-02-09T22:53:16.096Z - info: Running on android test: another

2016-02-09T22:53:16.192Z - info: Running on android test: successfully create a new pkcs12 file and return hash value

2016-02-09T22:53:16.418Z - info: Running on android test: successfully read a previous pkcs12 file and return hash value

2016-02-09T22:53:16.599Z - info: Running on android test: failed to extract public key because of corrupt pkcs12 file

2016-02-09T22:53:16.698Z - info: Running on android test: failed to get mobile documents path

2016-02-09T22:53:16.814Z - info: Running on android test: #init should register the peerAvailabilityChanged event

2016-02-09T22:53:16.852Z - debug: Socket disconnected: transport close 4 (HTC-HTC One M8s)

2016-02-09T22:53:16.922Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:5

2016-02-09T22:53:16.926Z - info: Discarding surplus device: samsung-SM-G900F

2016-02-09T22:53:16.975Z - info: Running on android test: #init should register the networkChanged event

2016-02-09T22:53:17.123Z - info: Running on android test: #startBroadcasting should throw on null device name

2016-02-09T22:53:17.228Z - info: Running on android test: #startBroadcasting should throw on empty string device name

2016-02-09T22:53:17.356Z - info: Running on android test: #startBroadcasting should throw on non-number port

2016-02-09T22:53:17.464Z - info: Running on android test: #startBroadcasting should throw on NaN port

2016-02-09T22:53:17.497Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:6

2016-02-09T22:53:17.498Z - info: Discarding surplus device: LGE-Nexus 5

2016-02-09T22:53:17.565Z - info: Running on android test: #startBroadcasting should throw on negative port

2016-02-09T22:53:17.654Z - info: Running on android test: #startBroadcasting should throw on too large port

2016-02-09T22:53:17.728Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-09T22:53:17.824Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-09T22:53:17.920Z - debug: Socket disconnected: transport close 6 (LGE-Nexus 5)

2016-02-09T22:53:17.931Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-09T22:53:18.020Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-09T22:53:18.095Z - info: Running on android test: #connect should call Mobile("Connect") with a port and without an error

2016-02-09T22:53:18.135Z - debug: Device presented: LGE-LG-D722 (android) unittest socket:7

2016-02-09T22:53:18.136Z - info: Discarding surplus device: LGE-LG-D722

2016-02-09T22:53:18.142Z - debug: Socket disconnected: transport close 5 (samsung-SM-G900F)

2016-02-09T22:53:18.216Z - info: Running on android test: #connect should call Mobile("Connect") and handle an error

2016-02-09T22:53:18.313Z - info: Running on android test: should call Mobile("Disconnect") without an error

2016-02-09T22:53:18.395Z - info: Running on android test: should call Mobile("Disconnect") and handle an error

2016-02-09T22:53:18.473Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:8

2016-02-09T22:53:18.474Z - info: Discarding surplus device: samsung-SM-N910C

2016-02-09T22:53:18.505Z - info: Running on android test: #start should fail if called twice in a row

2016-02-09T22:53:18.598Z - info: Running on android test: #startListeningForAdvertisements should fail if start not called

2016-02-09T22:53:18.676Z - info: Running on android test: should be able to call #stopListeningForAdvertisements many times

2016-02-09T22:53:18.777Z - info: Running on android test: should be able to call #startListeningForAdvertisements many times

2016-02-09T22:53:18.882Z - info: Running on android test: should be able to call #startUpdateAdvertisingAndListening many times

2016-02-09T22:53:19.073Z - info: Running on android test: #startUpdateAdvertisingAndListening should fail if start not called

2016-02-09T22:53:19.164Z - info: Running on android test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-09T22:53:19.169Z - debug: Socket disconnected: transport close 8 (samsung-SM-N910C)

2016-02-09T22:53:19.302Z - debug: Socket disconnected: transport close 7 (LGE-LG-D722)

2016-02-09T22:53:19.384Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:9

2016-02-09T22:53:19.385Z - info: Discarding surplus device: motorola-Nexus 6

2016-02-09T22:53:19.734Z - info: Running on ios test: basic

2016-02-09T22:53:20.046Z - debug: Socket disconnected: transport close 9 (motorola-Nexus 6)

2016-02-09T22:53:24.056Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:10

2016-02-09T22:53:24.057Z - info: Discarding surplus device: Apple-Iphone5-1

2016-02-09T22:53:24.665Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:11

2016-02-09T22:53:24.666Z - info: Discarding surplus device: samsung-SM-G900F

2016-02-09T22:53:25.336Z - debug: Socket disconnected: transport close 11 (samsung-SM-G900F)

2016-02-09T22:53:28.143Z - info: Running on ios test: another

2016-02-09T22:53:29.937Z - debug: Socket disconnected: transport close 10 (Apple-Iphone5-1)

2016-02-09T22:53:33.041Z - info: Running on ios test: successfully create a new pkcs12 file and return hash value

2016-02-09T22:53:36.569Z - info: Running on ios test: successfully read a previous pkcs12 file and return hash value

2016-02-09T22:53:37.070Z - info: Running on ios test: failed to extract public key because of corrupt pkcs12 file

2016-02-09T22:53:37.408Z - info: Running on ios test: failed to get mobile documents path

2016-02-09T22:53:37.754Z - info: Running on ios test: #init should register the peerAvailabilityChanged event

2016-02-09T22:53:38.084Z - info: Running on ios test: #init should register the networkChanged event

2016-02-09T22:53:38.426Z - info: Running on ios test: #startBroadcasting should throw on null device name

2016-02-09T22:53:38.778Z - info: Running on ios test: #startBroadcasting should throw on empty string device name

2016-02-09T22:53:46.748Z - info: Running on ios test: #startBroadcasting should throw on non-number port

2016-02-09T22:53:50.062Z - info: Running on ios test: #startBroadcasting should throw on NaN port

2016-02-09T22:53:50.200Z - info: Running on ios test: #startBroadcasting should throw on negative port

2016-02-09T22:53:50.313Z - info: Running on ios test: #startBroadcasting should throw on too large port

2016-02-09T22:53:50.428Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-09T22:53:50.553Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-09T22:53:50.681Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-09T22:53:50.809Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-09T22:53:50.953Z - info: Running on ios test: #connect should call Mobile("Connect") with a port and without an error

2016-02-09T22:53:51.088Z - info: Running on ios test: #connect should call Mobile("Connect") and handle an error

2016-02-09T22:53:51.244Z - info: Running on ios test: should call Mobile("Disconnect") without an error

2016-02-09T22:53:51.477Z - info: Running on ios test: should call Mobile("Disconnect") and handle an error

2016-02-09T22:53:51.608Z - info: Running on ios test: #start should fail if called twice in a row

2016-02-09T22:53:51.764Z - info: Running on ios test: #startListeningForAdvertisements should fail if start not called

2016-02-09T22:53:51.893Z - info: Running on ios test: should be able to call #stopListeningForAdvertisements many times

2016-02-09T22:53:52.023Z - info: Running on ios test: should be able to call #startListeningForAdvertisements many times

2016-02-09T22:53:52.257Z - info: Running on ios test: should be able to call #startUpdateAdvertisingAndListening many times

2016-02-09T22:53:52.501Z - info: Running on ios test: #startUpdateAdvertisingAndListening should fail if start not called

2016-02-09T22:53:52.629Z - info: Running on ios test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-09T22:53:53.083Z - info: Running on ios test: ThaliEmitter calls startBroadcasting twice with error

2016-02-09T22:53:54.156Z - info: Running on ios test: ThaliEmitter throws on connection to bad peer

2016-02-09T22:53:55.123Z - info: Running on ios test: ThaliEmitter throws on disconnect to bad peer

2016-02-09T22:54:02.203Z - info: Running on ios test: ThaliEmitter can discover and connect to peers

2016-02-09T22:54:09.372Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double connect

2016-02-09T22:54:14.078Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-02-09T22:54:19.266Z - info: Running on ios test: ThaliEmitter can connect and send data

2016-02-09T22:54:24.567Z - info: Running on ios test: ThaliEmitter handles socket disconnect correctly

2016-02-09T22:54:32.367Z - info: Running on ios test: #generatePreambleAndBeacons null ECDH for local device

2016-02-09T22:54:33.265Z - info: Running on ios test: #generatePreambleAndBeacons expiration out of range lower

2016-02-09T22:54:34.824Z - info: Running on ios test: #generatePreambleAndBeacons expiration out of range upper

2016-02-09T22:54:35.066Z - info: Running on ios test: #generatePreambleAndBeacons empty keys to notify

2016-02-09T22:54:35.849Z - info: Running on ios test: #generatePreambleAndBeacons multiple keys to notify

2016-02-09T22:54:37.072Z - info: Running on ios test: #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-02-09T22:54:38.486Z - info: Running on ios test: #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-02-09T22:54:39.278Z - info: Running on ios test: #parseBeacons expiration out of range lower

2016-02-09T22:54:39.790Z - info: Running on ios test: #parseBeacons no beacons returns null

2016-02-09T22:54:40.261Z - info: Running on ios test: #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-02-09T22:54:40.770Z - info: Running on ios test: #parseBeacons addressBookCallback fails decrypt

2016-02-09T22:54:41.626Z - info: Running on ios test: #parseBeacons addressBookCallback returns no matches

2016-02-09T22:54:42.831Z - info: Running on ios test: #parseBeacons addressBookCallback returns public key

2016-02-09T22:54:43.847Z - info: Running on ios test: #parseBeacons with beacons both for and not for the user

2016-02-09T22:54:44.223Z - debug: Socket disconnected: ping timeout 0 (LGE-LG-H815)

2016-02-09T22:54:44.313Z - info: Running on ios test: ThaliReplicationManager can call start without error

2016-02-09T22:54:44.651Z - info: Running on ios test: ThaliReplicationManager receives identity

2016-02-09T22:54:44.895Z - info: Running on ios test: ThaliReplicationManager replicates database

2016-02-09T22:55:09.179Z - debug: Socket disconnected: transport close 1 (Apple-Iphone6-1)

2016-02-09T22:55:12.036Z - debug: Socket disconnected: transport close 3 (Apple-IpadAir2-1)

2016-02-09T23:03:50.436Z - debug: Socket disconnected: ping timeout 2 (LGE-LG-D855)


 
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
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/58380500306a2c5_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/58380500306a2c5_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/58380500306a2c5_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/iOS_Iphone5-1.md)


###Android Logs
####Node name: thali01
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGH8153b36be34 app:com.test.thalitest code:0 
child process exited with code 0 on device LGH8153b36be34 
Error! Unexpected exit on device f56ad48d app:com.test.thalitest code:0 
child process exited with code 0 on device f56ad48d 
Android task is completed. [FAILED]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/58380500306a2c5_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/58380500306a2c5_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/58380500306a2c5_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/58380500306a2c5_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali02_LGE-Nexus 5.md)

####Node name: thali03
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device TA4750HV7I app:com.test.thalitest code:0 
child process exited with code 0 on device TA4750HV7I 
Error! Unexpected exit on device LGD8553bed2d08 app:com.test.thalitest code:0 
child process exited with code 0 on device LGD8553bed2d08 
Error! Unexpected exit on device 320414cd475f91e3 app:com.test.thalitest code:0 
child process exited with code 0 on device 320414cd475f91e3 
Android task is completed. [FAILED]
```
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/58380500306a2c5_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/58380500306a2c5_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/58380500306a2c5_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali03_samsung-SM-G800F.md)

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
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/58380500306a2c5_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/58380500306a2c5_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/58380500306a2c5_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali04_samsung-SM-G900F.md)

####Node name: thali05
Console output:
```
Error! Unexpected exit on device 954a12ed app:com.test.thalitest code:0 
child process exited with code 0 on device 954a12ed 
STOP log received from  ZX1G429CRK Test has  SUCCEEDED
Device test finished on ZX1G429CRK 
Android task is completed. [FAILED]
```
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/58380500306a2c5_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/58380500306a2c5_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali05_samsung-SM-G800H.md)

####Node name: thali06
Console output:
```
STOP log received from  FA55PYS00566 Test has  SUCCEEDED
Device test finished on FA55PYS00566 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 7970f88c app:com.test.thalitest code:0 
child process exited with code 0 on device 7970f88c 
Error! Unexpected exit on device 022678fb504e29b0 app:com.test.thalitest code:0 
child process exited with code 0 on device 022678fb504e29b0 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/58380500306a2c5_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/58380500306a2c5_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/58380500306a2c5_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali06_LGE-LG-D802.md)

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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/58380500306a2c5_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/58380500306a2c5_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device HT574YC04723 app:com.test.thalitest code:0 
child process exited with code 0 on device HT574YC04723 
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:null 
child process exited with code null on device 4325e43f 
Android task is completed. [FAILED]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/58380500306a2c5_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/58380500306a2c5_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/58380500306a2c5_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/58380500306a2c5_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali09_LGE-Nexus 5.md)




