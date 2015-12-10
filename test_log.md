#### Test 50650278c0f6ec2 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":23}}
listening on *:3000

New unit test device: UNITTEST-0.8503205047941637

New unit test device: UNITTEST-0.25500750524562843

New unit test device: UNITTEST-0.6873306228965858

New unit test device: UNITTEST-0.2551353694002715

New unit test device: UNITTEST-0.5497473930563159

New unit test device: UNITTEST-0.7067380824136923

New unit test device: UNITTEST-0.8269193203573507

Running test: multiplex can send data

New unit test device: UNITTEST-0.036483601146450884

New unit test device: UNITTEST-0.5092888008335632

Running test: basic

New unit test device: UNITTEST-0.957004580845605

New unit test device: UNITTEST-0.9687026253339219

New unit test device: UNITTEST-0.8916554247197098

New unit test device: UNITTEST-0.6857301282811052

Running test: another

New unit test device: UNITTEST-0.3036184867542294

New unit test device: UNITTEST-0.2588565724165828

Running test: successfully create a new pkcs12 file and return hash value

New unit test device: UNITTEST-0.32639199081890236

Running test: successfully read a previous pkcs12 file and return hash value

New unit test device: UNITTEST-0.4683121228316057

New unit test device: UNITTEST-0.2655568460958625

Running test: failed to extract public key because of corrupt pkcs12 file

Running test: multiplex can send data

Running test: failed to get mobile documents path

New unit test device: UNITTEST-0.011355117110755542

New unit test device: UNITTEST-0.9823723638096562

New unit test device: UNITTEST-0.5691154254238102

New unit test device: UNITTEST-0.4059055334583235

New unit test device: UNITTEST-0.29185448472597864

New unit test device: UNITTEST-0.9551177386445412

New unit test device: UNITTEST-0.21431734425704363

Running test: #init should register the peerAvailabilityChanged event

Running test: #init should register the networkChanged event

Running test: #startBroadcasting should throw on null device name

Running test: basic

Running test: #startBroadcasting should throw on empty string device name

Running test: another

Running test: successfully create a new pkcs12 file and return hash value

Running test: #startBroadcasting should throw on non-number port

Running test: successfully read a previous pkcs12 file and return hash value

Running test: #startBroadcasting should throw on NaN port

Running test: failed to extract public key because of corrupt pkcs12 file

Running test: #startBroadcasting should throw on negative port

Running test: failed to get mobile documents path

Running test: #init should register the peerAvailabilityChanged event

Running test: #startBroadcasting should throw on too large port

Running test: #init should register the networkChanged event

Running test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

Running test: #startBroadcasting should throw on null device name

Running test: #startBroadcasting should throw on empty string device name

Running test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

Running test: #startBroadcasting should throw on non-number port

Running test: #startBroadcasting should throw on NaN port

Running test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

Running test: #startBroadcasting should throw on negative port

Running test: #startBroadcasting should throw on too large port

Running test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

Running test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

Running test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

Running test: #connect should call Mobile("Connect") with a port and without an error

Running test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

Running test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

Running test: #connect should call Mobile("Connect") and handle an error

Running test: #connect should call Mobile("Connect") with a port and without an error

Running test: #connect should call Mobile("Connect") and handle an error

Running test: should call Mobile("Disconnect") without an error

Running test: should call Mobile("Disconnect") without an error

Running test: should call Mobile("Disconnect") and handle an error

Running test: should call Mobile("Disconnect") and handle an error

Running test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

Running test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

Running test: ThaliEmitter calls startBroadcasting twice with error

Running test: ThaliEmitter calls startBroadcasting twice with error

Running test: ThaliEmitter throws on connection to bad peer

Running test: ThaliEmitter throws on disconnect to bad peer

Running test: ThaliEmitter throws on connection to bad peer

Running test: ThaliEmitter can discover and connect to peers

Running test: ThaliEmitter throws on disconnect to bad peer

Running test: ThaliEmitter can discover and connect to peers

New unit test device: UNITTEST-0.7787789629122183

New unit test device: UNITTEST-0.09663590296873203

Running test: ThaliEmitter can discover and connect to peers and then fail on double connect

Running test: ThaliEmitter can discover and connect to peers and then fail on double disconnect

Running test: ThaliEmitter handles socket disconnect correctly

Running test: ThaliEmitter can discover and connect to peers and then fail on double connect

Running test: ThaliReplicationManager can call start without error

Running test: ThaliReplicationManager receives identity

Test run complete



-== UNIT TEST RESULTS ==-

PLATFORM: ios

RESULT: PASS
33 of 33 tests completed

33/33 passed (0 failures)
---


multiplex can send data - pass
basic - pass
another - pass
successfully create a new pkcs12 file and return hash value - pass

successfully read a previous pkcs12 file and return hash value - pass
failed to extract public key because of corrupt pkcs12 file - pass
failed to get mobile documents path - pass
#init should register the peerAvailabilityChanged event - pass
#init should register the networkChanged event - pass
#startBroadcasting should throw on null device name - pass
#startBroadcasting should throw on empty string device name - pass
#startBroadcasting should throw on non-number port - pass

#startBroadcasting should throw on NaN port - pass
#startBroadcasting should throw on negative port - pass
#startBroadcasting should throw on too large port - pass
#startBroadcasting should call Mobile("StartBroadcasting") without an error - pass
#startBroadcasting should call Mobile("StartBroadcasting") and handle an error - pass
#stopBroadcasting should call Mobile("StopBroadcasting") without an error - pass
#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error - pass

#connect should call Mobile("Connect") with a port and without an error - pass
#connect should call Mobile("Connect") and handle an error - pass
should call Mobile("Disconnect") without an error - pass
should call Mobile("Disconnect") and handle an error - pass
ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error - pass
ThaliEmitter calls startBroadcasting twice with error - pass
ThaliEmitter throws on connection to bad peer - pass
ThaliEmitter throws on disconnect to bad peer - pass
ThaliEmitter can discover and connect to peers - pass

ThaliEmitter can discover and connect to peers and then fail on double connect - pass
ThaliEmitter can discover and connect to peers and then fail on double disconnect - pass
ThaliEmitter handles socket disconnect correctly - pass
ThaliReplicationManager can call start without error - pass
ThaliReplicationManager receives identity - pass


-== END ==-


```


Logs for system : 
```

ios : Error: Command failed: true
Getting the list of iOS devices 
Deploying iOS test app 
uninstalling the application 
installing the application 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
ios: child process exited with code null on device 2a65f58f9902a701b5c9a55b2befb18672927474 
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/50650278c0f6ec2_Enable_UnitTest_tobybrad/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/50650278c0f6ec2_Enable_UnitTest_tobybrad/iOS_Iphone5s-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/50650278c0f6ec2_Enable_UnitTest_tobybrad/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/50650278c0f6ec2_Enable_UnitTest_tobybrad/iOS_Iphone5-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/50650278c0f6ec2_Enable_UnitTest_tobybrad/iOS_server.md)


###Android Logs
####Node name: thali01
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGH8153b36be34 app:com.test.thalitest code:0 
child process exited with code 0 on device LGH8153b36be34 
Error! Unexpected exit on device W3D7N15428022572 app:com.test.thalitest code:0 
child process exited with code 0 on device W3D7N15428022572 
Error! Unexpected exit on device f56ad48d app:com.test.thalitest code:null 
child process exited with code null on device f56ad48d 
Android task is completed. [FAILED]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/50650278c0f6ec2_Enable_UnitTest_tobybrad/thali01_LGE-LG-H815.md)

[HUAWEI-ALE-L21](https://github.com/ThaliTester/TestResults/blob/50650278c0f6ec2_Enable_UnitTest_tobybrad/thali01_HUAWEI-ALE-L21.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/50650278c0f6ec2_Enable_UnitTest_tobybrad/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGD7228ee9cf5b app:com.test.thalitest code:0 
child process exited with code 0 on device LGD7228ee9cf5b 
Error! Unexpected exit on device 09a9416e0297d102 app:com.test.thalitest code:0 
child process exited with code 0 on device 09a9416e0297d102 
Android task is completed. [FAILED]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/50650278c0f6ec2_Enable_UnitTest_tobybrad/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/50650278c0f6ec2_Enable_UnitTest_tobybrad/thali02_LGE-Nexus 5.md)

####Node name: thali03
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 320414cd475f91e3 app:com.test.thalitest code:null 
child process exited with code null on device 320414cd475f91e3 
Error! Unexpected exit on device TA4750HV7I app:com.test.thalitest code:0 
child process exited with code 0 on device TA4750HV7I 
Error! Unexpected exit on device LGD8553bed2d08 app:com.test.thalitest code:0 
child process exited with code 0 on device LGD8553bed2d08 
Android task is completed. [FAILED]
```
[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/50650278c0f6ec2_Enable_UnitTest_tobybrad/thali03_samsung-SM-G800F.md)

[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/50650278c0f6ec2_Enable_UnitTest_tobybrad/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/50650278c0f6ec2_Enable_UnitTest_tobybrad/thali03_LGE-LG-D855.md)

####Node name: thali04
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1C223JKW 
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Error! Unexpected exit on device 0be0c6c6 app:com.test.thalitest code:null 
child process exited with code null on device 0be0c6c6 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/50650278c0f6ec2_Enable_UnitTest_tobybrad/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/50650278c0f6ec2_Enable_UnitTest_tobybrad/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/50650278c0f6ec2_Enable_UnitTest_tobybrad/thali04_samsung-SM-G900F.md)

####Node name: thali05
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 1d6a772d app:com.test.thalitest code:null 
child process exited with code null on device 1d6a772d 
Error! Unexpected exit on device ZX1G429CRK app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1G429CRK 
Error! Unexpected exit on device 954a12ed app:com.test.thalitest code:0 
child process exited with code 0 on device 954a12ed 
Android task is completed. [FAILED]
```
[samsung-SM-N9005](https://github.com/ThaliTester/TestResults/blob/50650278c0f6ec2_Enable_UnitTest_tobybrad/thali05_samsung-SM-N9005.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/50650278c0f6ec2_Enable_UnitTest_tobybrad/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/50650278c0f6ec2_Enable_UnitTest_tobybrad/thali05_samsung-SM-G800H.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/50650278c0f6ec2_Enable_UnitTest_tobybrad/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/50650278c0f6ec2_Enable_UnitTest_tobybrad/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/50650278c0f6ec2_Enable_UnitTest_tobybrad/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device c5afcdcb app:com.test.thalitest code:null 
child process exited with code null on device c5afcdcb 
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:0 
child process exited with code 0 on device 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/50650278c0f6ec2_Enable_UnitTest_tobybrad/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/50650278c0f6ec2_Enable_UnitTest_tobybrad/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/50650278c0f6ec2_Enable_UnitTest_tobybrad/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/50650278c0f6ec2_Enable_UnitTest_tobybrad/thali08_samsung-SM-A300FU.md)

####Node name: thali09
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device CC51WYC03425 app:com.test.thalitest code:null 
child process exited with code null on device CC51WYC03425 
Error! Unexpected exit on device 0c6a0f3c0bdb4e77 app:com.test.thalitest code:0 
child process exited with code 0 on device 0c6a0f3c0bdb4e77 
Android task is completed. [FAILED]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/50650278c0f6ec2_Enable_UnitTest_tobybrad/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/50650278c0f6ec2_Enable_UnitTest_tobybrad/thali09_LGE-Nexus 5.md)




