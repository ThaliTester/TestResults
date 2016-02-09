#### Test 58380500c26a9ef Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":21}}
2016-02-09T02:09:37.459Z - info: listening on *:3000

2016-02-09T02:09:38.085Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:1

2016-02-09T02:09:38.377Z - debug: Device presented: LGE-LG-D722 (android) unittest socket:2

2016-02-09T02:09:38.380Z - info: Required number of android devices presented (2)

2016-02-09T02:09:38.384Z - info: Starting unit test run for platform: android

2016-02-09T02:09:38.979Z - info: Running on android test: multiplex can send data

2016-02-09T02:09:39.078Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:3

2016-02-09T02:09:39.079Z - info: Discarding surplus device: samsung-SM-G900F

2016-02-09T02:09:39.649Z - info: Running on android test: enqueue and run in order

2016-02-09T02:09:39.659Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:5

2016-02-09T02:09:39.660Z - info: Discarding surplus device: LGE-LG-H815

2016-02-09T02:09:39.786Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:4

2016-02-09T02:09:39.959Z - info: Running on android test: basic

2016-02-09T02:09:40.073Z - info: Running on android test: another

2016-02-09T02:09:40.103Z - debug: Socket disconnected: transport close 3 (samsung-SM-G900F)

2016-02-09T02:09:40.174Z - info: Running on android test: successfully create a new pkcs12 file and return hash value

2016-02-09T02:09:40.413Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:6

2016-02-09T02:09:40.415Z - info: Required number of ios devices presented (2)

2016-02-09T02:09:40.416Z - info: Starting unit test run for platform: ios

2016-02-09T02:09:40.566Z - info: Running on android test: successfully read a previous pkcs12 file and return hash value

2016-02-09T02:09:40.578Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:7

2016-02-09T02:09:40.579Z - info: Discarding surplus device: LGE-Nexus 5

2016-02-09T02:09:40.726Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:0

2016-02-09T02:09:40.727Z - info: Discarding surplus device: Apple-Iphone6-1

2016-02-09T02:09:40.828Z - debug: Socket disconnected: transport close 5 (LGE-LG-H815)

2016-02-09T02:09:40.849Z - info: Running on android test: failed to extract public key because of corrupt pkcs12 file

2016-02-09T02:09:40.933Z - info: Running on android test: failed to get mobile documents path

2016-02-09T02:09:41.001Z - info: Running on android test: #init should register the peerAvailabilityChanged event

2016-02-09T02:09:41.009Z - debug: Socket disconnected: transport close 7 (LGE-Nexus 5)

2016-02-09T02:09:41.052Z - info: Running on android test: #init should register the networkChanged event

2016-02-09T02:09:41.098Z - info: Running on android test: #startBroadcasting should throw on null device name

2016-02-09T02:09:41.151Z - info: Running on android test: #startBroadcasting should throw on empty string device name

2016-02-09T02:09:41.214Z - info: Running on android test: #startBroadcasting should throw on non-number port

2016-02-09T02:09:41.275Z - info: Running on android test: #startBroadcasting should throw on NaN port

2016-02-09T02:09:41.324Z - info: Running on android test: #startBroadcasting should throw on negative port

2016-02-09T02:09:41.369Z - info: Running on android test: #startBroadcasting should throw on too large port

2016-02-09T02:09:41.418Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-09T02:09:41.482Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-09T02:09:41.559Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-09T02:09:41.628Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-09T02:09:41.704Z - info: Running on android test: #connect should call Mobile("Connect") with a port and without an error

2016-02-09T02:09:41.784Z - info: Running on android test: #connect should call Mobile("Connect") and handle an error

2016-02-09T02:09:41.829Z - info: Running on android test: should call Mobile("Disconnect") without an error

2016-02-09T02:09:41.878Z - info: Running on android test: should call Mobile("Disconnect") and handle an error

2016-02-09T02:09:41.941Z - info: Running on android test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-09T02:09:42.135Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:8

2016-02-09T02:09:42.136Z - info: Discarding surplus device: samsung-SM-N910C

2016-02-09T02:09:42.266Z - debug: Device presented: LGE-LG-D855 (android) unittest socket:9

2016-02-09T02:09:42.267Z - info: Discarding surplus device: LGE-LG-D855

2016-02-09T02:09:42.590Z - debug: Socket disconnected: transport close 8 (samsung-SM-N910C)

2016-02-09T02:09:42.859Z - debug: Socket disconnected: transport close 9 (LGE-LG-D855)

2016-02-09T02:09:43.197Z - info: Running on android test: ThaliEmitter calls startBroadcasting twice with error

2016-02-09T02:09:43.382Z - info: Running on android test: ThaliEmitter throws on connection to bad peer

2016-02-09T02:09:43.505Z - debug: Socket disconnected: transport close 0 (Apple-Iphone6-1)

2016-02-09T02:09:48.982Z - info: Running on ios test: multiplex can send data

2016-02-09T02:09:49.184Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:10

2016-02-09T02:09:49.185Z - info: Discarding surplus device: samsung-SM-G900F

2016-02-09T02:09:49.857Z - debug: Socket disconnected: transport close 10 (samsung-SM-G900F)

2016-02-09T02:10:15.917Z - info: Running on ios test: enqueue and run in order

2016-02-09T02:10:23.929Z - info: Running on ios test: basic

2016-02-09T02:10:38.950Z - info: Running on ios test: another

2016-02-09T02:10:52.643Z - info: Running on ios test: successfully create a new pkcs12 file and return hash value

2016-02-09T02:11:02.128Z - info: Running on ios test: successfully read a previous pkcs12 file and return hash value

2016-02-09T02:11:08.404Z - debug: Socket disconnected: ping timeout 1 (motorola-Nexus 6)

2016-02-09T02:11:11.268Z - info: Running on ios test: failed to extract public key because of corrupt pkcs12 file

2016-02-09T02:11:30.317Z - info: Running on ios test: failed to get mobile documents path

2016-02-09T02:11:55.192Z - info: Running on ios test: #init should register the peerAvailabilityChanged event

2016-02-09T02:12:09.188Z - info: Running on ios test: #init should register the networkChanged event

2016-02-09T02:13:14.286Z - info: Running on ios test: #startBroadcasting should throw on null device name

2016-02-09T02:13:43.134Z - info: Running on ios test: #startBroadcasting should throw on empty string device name

2016-02-09T02:13:47.410Z - info: Running on ios test: #startBroadcasting should throw on non-number port

2016-02-09T02:13:57.478Z - info: Running on ios test: #startBroadcasting should throw on NaN port

2016-02-09T02:14:06.271Z - info: Running on ios test: #startBroadcasting should throw on negative port

2016-02-09T02:14:15.848Z - info: Running on ios test: #startBroadcasting should throw on too large port

2016-02-09T02:14:17.991Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-09T02:14:30.019Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-09T02:14:34.827Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-09T02:14:42.489Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-09T02:14:51.294Z - info: Running on ios test: #connect should call Mobile("Connect") with a port and without an error

2016-02-09T02:14:56.236Z - info: Running on ios test: #connect should call Mobile("Connect") and handle an error

2016-02-09T02:15:09.588Z - info: Running on ios test: should call Mobile("Disconnect") without an error

2016-02-09T02:15:22.116Z - info: Running on ios test: should call Mobile("Disconnect") and handle an error

2016-02-09T02:15:26.419Z - info: Running on ios test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-09T02:15:37.145Z - info: Running on ios test: ThaliEmitter calls startBroadcasting twice with error

2016-02-09T02:15:37.590Z - info: Running on ios test: ThaliEmitter throws on connection to bad peer

2016-02-09T02:15:46.877Z - info: Running on ios test: ThaliEmitter throws on disconnect to bad peer

2016-02-09T02:15:57.189Z - info: Running on ios test: ThaliEmitter can discover and connect to peers

2016-02-09T02:16:05.602Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double connect

2016-02-09T02:16:15.636Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-02-09T02:16:25.085Z - info: Running on ios test: ThaliEmitter can connect and send data

2016-02-09T02:16:55.497Z - info: Running on ios test: ThaliEmitter handles socket disconnect correctly

2016-02-09T02:17:32.909Z - info: Running on ios test: #generatePreambleAndBeacons null ECDH for local device

2016-02-09T02:19:42.533Z - info: Running on ios test: #generatePreambleAndBeacons expiration out of range

2016-02-09T02:19:47.286Z - info: Running on ios test: #generatePreambleAndBeacons empty keys to notify

2016-02-09T02:19:55.598Z - info: Running on ios test: #generatePreambleAndBeacons multiple keys to notify

2016-02-09T02:20:05.229Z - info: Running on ios test: #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-02-09T02:20:12.221Z - info: Running on ios test: #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-02-09T02:20:18.659Z - info: Running on ios test: #parseBeacons expiration out of range

2016-02-09T02:20:26.317Z - info: Running on ios test: #parseBeacons no beacons returns null

2016-02-09T02:20:27.675Z - info: Running on ios test: #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-02-09T02:20:28.160Z - info: Running on ios test: #parseBeacons addressBookCallback fails decrypt

2016-02-09T02:20:28.812Z - info: Running on ios test: #parseBeacons addressBookCallback returns no matches

2016-02-09T02:20:32.932Z - info: Running on ios test: #parseBeacons addressBookCallback returns public key

2016-02-09T02:20:52.362Z - info: Running on ios test: #parseBeacons with beacons both for and not for the user

2016-02-09T02:20:55.466Z - info: Running on ios test: ThaliReplicationManager can call start without error

2016-02-09T02:21:06.859Z - info: Running on ios test: ThaliReplicationManager receives identity

2016-02-09T02:21:16.393Z - info: Running on ios test: ThaliReplicationManager replicates database

2016-02-09T02:21:49.498Z - debug: Socket disconnected: transport close 6 (Apple-IpadAir2-1)

2016-02-09T02:22:07.159Z - debug: Socket disconnected: transport close 4 (Apple-Iphone5-1)

2016-02-09T02:26:26.852Z - debug: Socket disconnected: transport close 2 (LGE-LG-D722)


 
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
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/58380500c26a9ef_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/58380500c26a9ef_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/58380500c26a9ef_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/iOS_Iphone5-1.md)


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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/58380500c26a9ef_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/58380500c26a9ef_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGD7228ee9cf5b app:com.test.thalitest code:0 
child process exited with code 0 on device LGD7228ee9cf5b 
Android task is completed. [FAILED]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/58380500c26a9ef_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/58380500c26a9ef_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/58380500c26a9ef_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/58380500c26a9ef_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/58380500c26a9ef_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali03_samsung-SM-G800F.md)

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
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/58380500c26a9ef_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/58380500c26a9ef_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/58380500c26a9ef_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali04_samsung-SM-G900F.md)

####Node name: thali05
Console output:
```
Error! Unexpected exit on device 954a12ed app:com.test.thalitest code:0 
child process exited with code 0 on device 954a12ed 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1G429CRK app:com.test.thalitest code:null 
child process exited with code null on device ZX1G429CRK 
Android task is completed. [FAILED]
```
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/58380500c26a9ef_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/58380500c26a9ef_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali05_samsung-SM-G800H.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/58380500c26a9ef_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/58380500c26a9ef_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/58380500c26a9ef_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali06_LGE-LG-D802.md)

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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/58380500c26a9ef_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/58380500c26a9ef_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/58380500c26a9ef_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/58380500c26a9ef_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/58380500c26a9ef_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/58380500c26a9ef_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali09_LGE-Nexus 5.md)




