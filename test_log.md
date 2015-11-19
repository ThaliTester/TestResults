#### Test 51193821e3da755 Logs

Status: 
```

ios : false

android : Error: Command failed: COPY_LOGS timeout reached
Error: Command failed: Android testing process has failed
 [0m


TIMEOUT REACHED!COPY_LOGS timeout reached


server : IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":16}}
Start Android tests : performance tests, start tests with timer

Test[0]: testSendData.js, timeout : 1500000, data : {"timeout":"500000","rounds":"1","dataTimeout":"10000","dataAmount":"1000000","conReTryTimeout":"5000","conReTryCount":"5"}
Start iOs tests : performance tests, start tests with timer
Test[0]: testSendData.js, timeout : 1500000, data : {"timeout":"500000","rounds":"1","dataTimeout":"10000","dataAmount":"1000000","conReTryTimeout":"5000","conReTryCount":"5"}

listening on *:3000

Android  LGE-LG-D855_PT1433 added : 0.591 sec., device count 1

Android  samsung-SM-N910C_PT6448 added : 0.628 sec., device count 2

Android  LGE-Nexus 5_PT8166 added : 0.799 sec., device count 3

Android  motorola-XT1072_PT4525 added : 1.488 sec., device count 4

Android  LGE-LG-D802_PT1545 added : 1.566 sec., device count 5

Android  samsung-SM-G900F_PT9704 added : 2.885 sec., device count 6

Android  HTC-HTC One_M8_PT5538 added : 3.133 sec., device count 7

Android  LGE-Nexus 5_PT3417 added : 3.616 sec., device count 8

Android  HTC-HTC Desire 820_PT3126 added : 3.779 sec., device count 9

iOs  Apple-Iphone6-1_PT4558 added : 3.956 sec., device count 1

Android  HTC-HTC One M8s_PT3094 added : 4.16 sec., device count 10

Android  LGE-LG-D722_PT9121 added : 4.577 sec., device count 11

Android  motorola-Nexus 6_PT3617 added : 4.977 sec., device count 12

Android  samsung-SM-A300FU_PT575 added : 5.042 sec., device count 13

Android  samsung-SM-N9005_PT2757 added : 5.111 sec., device count 14

iOs  Apple-IpadAir2-1_PT6621 added : 5.171 sec., device count 2

iOs  Apple-Iphone5s-1_PT9462 added : 5.318 sec., device count 3

Android  samsung-SM-G800F_PT8840 added : 6.694 sec., device count 15

Android  motorola-XT1039_PT7881 added : 34.926 sec., device count 16

-------------- We got wait done, now starting the testing process ------------------

-----Android start testing now with 16 devices, time now: 300.072 sec.

start test[0] with 16 devices.

-----iOs start testing now with 3 devices, time now: 300.104 sec.

start test[0] with 3 devices.

Android LGE-Nexus 5_PT3417 got re-connected event  ####################################################

Android samsung-SM-N910C_PT6448 got disconnected

Android LGE-Nexus 5_PT3417 got disconnected

iOs with Apple-Iphone5s-1_PT9462 request took : 230767 ms. results peers[0], reConnects[0], sendData[2], time now: 530.874 sec.

iOs with Apple-IpadAir2-1_PT6621 request took : 234528 ms. results peers[0], reConnects[0], sendData[2], time now: 534.634 sec.

iOs with Apple-Iphone6-1_PT4558 request took : 250546 ms. results peers[0], reConnects[0], sendData[2], time now: 550.652 sec.

------------------------------------------------------
iOs test[ 0] done now. , time now: 550.653 sec.

iOs All tests are done, preparing test report. , time now: 550.659 sec.

--------------- test report ---------------------

--------------- Apple-Iphone6-1_PT4558 --------------------- : 1

sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.

Results list does not contain any items
sendList failed peers count : 2 [100 %]
- Peer ID : Apple-Iphone5s-1_PT9462.AiaXgQ==, Tried : 5
- Peer ID : Apple-IpadAir2-1_PT6621.ucYn4g==, Tried : 5
sendList never tried peers count : 0 [0 %]

--------------- Apple-IpadAir2-1_PT6621 --------------------- : 2

sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Results list does not contain any items

sendList failed peers count : 2 [100 %]
- Peer ID : Apple-Iphone6-1_PT4558.76EyUA==, Tried : 5
- Peer ID : Apple-Iphone5s-1_PT9462.AiaXgQ==, Tried : 5

sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5s-1_PT9462 --------------------- : 3

sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Results list does not contain any items
sendList failed peers count : 2 [100 %]

- Peer ID : Apple-Iphone6-1_PT4558.76EyUA==, Tried : 5
- Peer ID : Apple-IpadAir2-1_PT6621.ucYn4g==, Tried : 5
sendList never tried peers count : 0 [0 %]

--------------- Combined ---------------------
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.

--------------- end of test report ---------------------

Android LGE-Nexus 5_PT3417 got re-connected event  ####################################################

Android LGE-Nexus 5_PT3417 got disconnected

Android motorola-Nexus 6_PT3617 got re-connected event  ####################################################

Android LGE-Nexus 5_PT3417 got re-connected event  ####################################################

Android LGE-Nexus 5_PT3417 got disconnected

Android motorola-Nexus 6_PT3617 got disconnected

Android LGE-Nexus 5_PT3417 got re-connected event  ####################################################

Android LGE-Nexus 5_PT3417 got disconnected

Android with motorola-Nexus 6_PT3617 request took : 500479 ms. results peers[0], reConnects[0], sendData[15], time now: 800.571 sec.

Android with LGE-Nexus 5_PT8166 request took : 500493 ms. results peers[0], reConnects[0], sendData[15], time now: 800.579 sec.

Android with samsung-SM-N9005_PT2757 request took : 500572 ms. results peers[0], reConnects[0], sendData[15], time now: 800.666 sec.

Android with samsung-SM-G800F_PT8840 request took : 500578 ms. results peers[0], reConnects[0], sendData[15], time now: 800.671 sec.

Android with samsung-SM-A300FU_PT575 request took : 500605 ms. results peers[0], reConnects[0], sendData[15], time now: 800.698 sec.

Android with motorola-XT1039_PT7881 request took : 500607 ms. results peers[0], reConnects[0], sendData[15], time now: 800.701 sec.

Android with motorola-XT1072_PT4525 request took : 500620 ms. results peers[0], reConnects[0], sendData[15], time now: 800.706 sec.

Android with HTC-HTC One M8s_PT3094 request took : 500763 ms. results peers[0], reConnects[0], sendData[15], time now: 800.854 sec.

Android with HTC-HTC One_M8_PT5538 request took : 500843 ms. results peers[0], reConnects[0], sendData[15], time now: 800.931 sec.

Android with LGE-LG-D855_PT1433 request took : 501258 ms. results peers[0], reConnects[0], sendData[15], time now: 801.339 sec.

Android with HTC-HTC Desire 820_PT3126 request took : 501444 ms. results peers[0], reConnects[0], sendData[15], time now: 801.533 sec.

Android with LGE-LG-D722_PT9121 request took : 501919 ms. results peers[0], reConnects[0], sendData[15], time now: 802.011 sec.

Android with samsung-SM-G900F_PT9704 request took : 502070 ms. results peers[0], reConnects[0], sendData[15], time now: 802.157 sec.

Android with LGE-LG-D802_PT1545 request took : 502577 ms. results peers[0], reConnects[0], sendData[15], time now: 802.664 sec.

Android LGE-Nexus 5_PT3417 got re-connected event  ####################################################

Android with LGE-Nexus 5_PT3417 request took : 540639 ms. results peers[0], reConnects[0], sendData[15], time now: 840.727 sec.

Android LGE-Nexus 5_PT3417 got disconnected

Android HTC-HTC One_M8_PT5538 got re-connected event  ####################################################

Android HTC-HTC One_M8_PT5538 got disconnected


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```
###Android Logs
####Node name: thali01
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/51193821e3da755_Performance_test_in_CI__vjrantal/thali01_samsung-SM-A500FU.md)

[HUAWEI-ALE-L21](https://github.com/ThaliTester/TestResults/blob/51193821e3da755_Performance_test_in_CI__vjrantal/thali01_HUAWEI-ALE-L21.md)

[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/51193821e3da755_Performance_test_in_CI__vjrantal/thali01_LGE-LG-H815.md)

####Node name: thali02
Console output:
```
Error! Unexpected exit on device LGD7228ee9cf5b app:com.test.thalitest code:null 
child process exited with code null on device LGD7228ee9cf5b 
Error! Unexpected exit on device 09a9416e0297d102 app:com.test.thalitest code:null 
child process exited with code null on device 09a9416e0297d102 
Android task is completed 
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/51193821e3da755_Performance_test_in_CI__vjrantal/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/51193821e3da755_Performance_test_in_CI__vjrantal/thali02_LGE-Nexus 5.md)

####Node name: thali03



###iOS Logs
[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/51193821e3da755_Performance_test_in_CI__vjrantal/iOS_Iphone5s-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/51193821e3da755_Performance_test_in_CI__vjrantal/iOS_Iphone6-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/51193821e3da755_Performance_test_in_CI__vjrantal/iOS_IpadAir2-1.md)


#### Integration Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":16}}
Start Android tests : performance tests, start tests with timer

Test[0]: testSendData.js, timeout : 1500000, data : {"timeout":"500000","rounds":"1","dataTimeout":"10000","dataAmount":"1000000","conReTryTimeout":"5000","conReTryCount":"5"}
Start iOs tests : performance tests, start tests with timer
Test[0]: testSendData.js, timeout : 1500000, data : {"timeout":"500000","rounds":"1","dataTimeout":"10000","dataAmount":"1000000","conReTryTimeout":"5000","conReTryCount":"5"}

listening on *:3000

Android  LGE-LG-D855_PT1433 added : 0.591 sec., device count 1

Android  samsung-SM-N910C_PT6448 added : 0.628 sec., device count 2

Android  LGE-Nexus 5_PT8166 added : 0.799 sec., device count 3

Android  motorola-XT1072_PT4525 added : 1.488 sec., device count 4

Android  LGE-LG-D802_PT1545 added : 1.566 sec., device count 5

Android  samsung-SM-G900F_PT9704 added : 2.885 sec., device count 6

Android  HTC-HTC One_M8_PT5538 added : 3.133 sec., device count 7

Android  LGE-Nexus 5_PT3417 added : 3.616 sec., device count 8

Android  HTC-HTC Desire 820_PT3126 added : 3.779 sec., device count 9

iOs  Apple-Iphone6-1_PT4558 added : 3.956 sec., device count 1

Android  HTC-HTC One M8s_PT3094 added : 4.16 sec., device count 10

Android  LGE-LG-D722_PT9121 added : 4.577 sec., device count 11

Android  motorola-Nexus 6_PT3617 added : 4.977 sec., device count 12

Android  samsung-SM-A300FU_PT575 added : 5.042 sec., device count 13

Android  samsung-SM-N9005_PT2757 added : 5.111 sec., device count 14

iOs  Apple-IpadAir2-1_PT6621 added : 5.171 sec., device count 2

iOs  Apple-Iphone5s-1_PT9462 added : 5.318 sec., device count 3

Android  samsung-SM-G800F_PT8840 added : 6.694 sec., device count 15

Android  motorola-XT1039_PT7881 added : 34.926 sec., device count 16

-------------- We got wait done, now starting the testing process ------------------

-----Android start testing now with 16 devices, time now: 300.072 sec.

start test[0] with 16 devices.

-----iOs start testing now with 3 devices, time now: 300.104 sec.

start test[0] with 3 devices.

Android LGE-Nexus 5_PT3417 got re-connected event  ####################################################

Android samsung-SM-N910C_PT6448 got disconnected

Android LGE-Nexus 5_PT3417 got disconnected

iOs with Apple-Iphone5s-1_PT9462 request took : 230767 ms. results peers[0], reConnects[0], sendData[2], time now: 530.874 sec.

iOs with Apple-IpadAir2-1_PT6621 request took : 234528 ms. results peers[0], reConnects[0], sendData[2], time now: 534.634 sec.

iOs with Apple-Iphone6-1_PT4558 request took : 250546 ms. results peers[0], reConnects[0], sendData[2], time now: 550.652 sec.

------------------------------------------------------
iOs test[ 0] done now. , time now: 550.653 sec.

iOs All tests are done, preparing test report. , time now: 550.659 sec.

--------------- test report ---------------------

--------------- Apple-Iphone6-1_PT4558 --------------------- : 1

sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.

Results list does not contain any items
sendList failed peers count : 2 [100 %]
- Peer ID : Apple-Iphone5s-1_PT9462.AiaXgQ==, Tried : 5
- Peer ID : Apple-IpadAir2-1_PT6621.ucYn4g==, Tried : 5
sendList never tried peers count : 0 [0 %]

--------------- Apple-IpadAir2-1_PT6621 --------------------- : 2

sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Results list does not contain any items

sendList failed peers count : 2 [100 %]
- Peer ID : Apple-Iphone6-1_PT4558.76EyUA==, Tried : 5
- Peer ID : Apple-Iphone5s-1_PT9462.AiaXgQ==, Tried : 5

sendList never tried peers count : 0 [0 %]
--------------- Apple-Iphone5s-1_PT9462 --------------------- : 3

sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Results list does not contain any items
sendList failed peers count : 2 [100 %]

- Peer ID : Apple-Iphone6-1_PT4558.76EyUA==, Tried : 5
- Peer ID : Apple-IpadAir2-1_PT6621.ucYn4g==, Tried : 5
sendList never tried peers count : 0 [0 %]

--------------- Combined ---------------------
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.

--------------- end of test report ---------------------

Android LGE-Nexus 5_PT3417 got re-connected event  ####################################################

Android LGE-Nexus 5_PT3417 got disconnected

Android motorola-Nexus 6_PT3617 got re-connected event  ####################################################

Android LGE-Nexus 5_PT3417 got re-connected event  ####################################################

Android LGE-Nexus 5_PT3417 got disconnected

Android motorola-Nexus 6_PT3617 got disconnected

Android LGE-Nexus 5_PT3417 got re-connected event  ####################################################

Android LGE-Nexus 5_PT3417 got disconnected

Android with motorola-Nexus 6_PT3617 request took : 500479 ms. results peers[0], reConnects[0], sendData[15], time now: 800.571 sec.

Android with LGE-Nexus 5_PT8166 request took : 500493 ms. results peers[0], reConnects[0], sendData[15], time now: 800.579 sec.

Android with samsung-SM-N9005_PT2757 request took : 500572 ms. results peers[0], reConnects[0], sendData[15], time now: 800.666 sec.

Android with samsung-SM-G800F_PT8840 request took : 500578 ms. results peers[0], reConnects[0], sendData[15], time now: 800.671 sec.

Android with samsung-SM-A300FU_PT575 request took : 500605 ms. results peers[0], reConnects[0], sendData[15], time now: 800.698 sec.

Android with motorola-XT1039_PT7881 request took : 500607 ms. results peers[0], reConnects[0], sendData[15], time now: 800.701 sec.

Android with motorola-XT1072_PT4525 request took : 500620 ms. results peers[0], reConnects[0], sendData[15], time now: 800.706 sec.

Android with HTC-HTC One M8s_PT3094 request took : 500763 ms. results peers[0], reConnects[0], sendData[15], time now: 800.854 sec.

Android with HTC-HTC One_M8_PT5538 request took : 500843 ms. results peers[0], reConnects[0], sendData[15], time now: 800.931 sec.

Android with LGE-LG-D855_PT1433 request took : 501258 ms. results peers[0], reConnects[0], sendData[15], time now: 801.339 sec.

Android with HTC-HTC Desire 820_PT3126 request took : 501444 ms. results peers[0], reConnects[0], sendData[15], time now: 801.533 sec.

Android with LGE-LG-D722_PT9121 request took : 501919 ms. results peers[0], reConnects[0], sendData[15], time now: 802.011 sec.

Android with samsung-SM-G900F_PT9704 request took : 502070 ms. results peers[0], reConnects[0], sendData[15], time now: 802.157 sec.

Android with LGE-LG-D802_PT1545 request took : 502577 ms. results peers[0], reConnects[0], sendData[15], time now: 802.664 sec.

Android LGE-Nexus 5_PT3417 got re-connected event  ####################################################

Android with LGE-Nexus 5_PT3417 request took : 540639 ms. results peers[0], reConnects[0], sendData[15], time now: 840.727 sec.

Android LGE-Nexus 5_PT3417 got disconnected

Android HTC-HTC One_M8_PT5538 got re-connected event  ####################################################

Android HTC-HTC One_M8_PT5538 got disconnected


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```

