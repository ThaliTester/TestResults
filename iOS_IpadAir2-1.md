#### Test 58135655e9e7eb8_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/58135655e9e7eb8/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/72EB63F2-13CA-4486-8F84-6200E987EC14/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/72EB63F2-13CA-4486-8F84-6200E987EC14/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/58135655e9e7eb8/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/58135655e9e7eb8/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/205E8CB4-AE83-416F-BFE4-2B1DA3CBABCF/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53029"
,(lldb)     command script import "/tmp/72EB63F2-13CA-4486-8F84-6200E987EC14/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-09 13:36:48.229 ThaliTest[1081:1751437] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/39DC2D29-8FC2-471D-9E48-3A2BAAC1D134/Library/Cookies/Cookies.binarycookies
,2016-02-09 13:36:48.574 ThaliTest[1081:1751437] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-09 13:36:48.575 ThaliTest[1081:1751437] Multi-tasking -> Device: YES, App: YES
,2016-02-09 13:36:48.584 ThaliTest[1081:1751437] Unlimited access to network resources
,2016-02-09 13:36:48.591 ThaliTest[1081:1751437] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-09 13:36:57.133 ThaliTest[1081:1751437] Resetting plugins due to page load.
,2016-02-09 13:37:00.660 ThaliTest[1081:1751437] Finished load of: file:///var/mobile/Containers/Bundle/Application/205E8CB4-AE83-416F-BFE4-2B1DA3CBABCF/ThaliTest.app/www/index.html
,2016-02-09 13:37:00.802 ThaliTest[1081:1751437] JXcore Cordova plugin initializing
,2016-02-09 13:37:00.803 ThaliTest[1081:1751651] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/205E8CB4-AE83-416F-BFE4-2B1DA3CBABCF/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/205E8CB4-AE83-416F-BFE4-2B1DA3CBABCF/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/205E8CB4-AE83-416F-BFE4-2B1DA3CBABCF/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/205E8CB4-AE83-416F-BFE4-2B1DA3CBABCF/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/205E8CB4-AE83-416F-BFE4-2B1DA3CBABCF/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/205E8CB4-AE83-416F-BFE4-2B1DA3CBABCF/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/205E8CB4-AE83-416F-BFE4-2B1DA3CBABCF/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/205E8CB4-AE83-416F-BFE4-2B1DA3CBABCF/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/205E8CB4-AE83-416F-BFE4-2B1DA3CBABCF/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,TAP version 13

,# setup

,# multiplex can send data

,# teardown

,ok 1 String should be length:200

,# setup

,# enqueue and run in order

,# teardown

,ok 2 firstPromise setTimeout

,ok 3 firstPromise result

,ok 4 firstPromise testValue

,ok 5 secondPromise setTimeout

,ok 6 secondPromise result

,ok 7 secondPromise testValue

,ok 8 thirdPromise in promise

,ok 9 thirdPromise result

,ok 10 thirdPromise testValue

,# setup

,# basic

,# teardown

,ok 11 sane

,# setup

,# another

,# teardown

,ok 12 sane

,# setup

,# successfully create a new pkcs12 file and return hash value

,# teardown

,ok 13 should be equal

,ok 14 null

,ok 15 (unnamed assert)

,ok 16 should be equal

,ok 17 should not throw

# setup

,# successfully read a previous pkcs12 file and return hash value

,# teardown

,ok 18 (unnamed assert)

,ok 19 (unnamed assert)

ok 20 should not throw

,ok 21 should be equal

,ok 22 should be equal

,# setup

,# failed to extract public key because of corrupt pkcs12 file

,# teardown

,ok 23 should be equal

,# setup

,# failed to get mobile documents path

,# teardown

,ok 24 should be equal

,# setup

,# #init should register the peerAvailabilityChanged event

,# teardown

,ok 25 should be equal

,ok 26 should be equal

,ok 27 should be equal

,# setup

,# #init should register the networkChanged event

,# teardown

,ok 28 should be equal

,# setup

,# #startBroadcasting should throw on null device name

,# teardown

,ok 29 should throw

,# setup

,# #startBroadcasting should throw on empty string device name

,# teardown

,ok 30 should throw

,# setup

,# #startBroadcasting should throw on non-number port

,# teardown

,ok 31 should throw

,# setup

,# #startBroadcasting should throw on NaN port

,# teardown

,ok 32 should throw

,# setup

,# #startBroadcasting should throw on negative port

,# teardown

,ok 33 should throw

,# setup

,# #startBroadcasting should throw on too large port

,# teardown

,ok 34 should throw

,# setup

,# #startBroadcasting should call Mobile("StartBroadcasting") without an error

,# teardown

,ok 35 should be equal

,ok 36 should be equal

,ok 37 should be equal

,# setup

,# #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

,# teardown

,ok 38 should be equal

,ok 39 should be equal

,ok 40 should be equal

,# setup

,# #stopBroadcasting should call Mobile("StopBroadcasting") without an error

,# teardown

,ok 41 should be equal

,ok 42 should be equal

,# setup

,# #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

,# teardown

,ok 43 should be equal

,ok 44 should be equal

,# setup

,# #connect should call Mobile("Connect") with a port and without an error

,# teardown

,ok 45 should be equal

,ok 46 should be equal

,ok 47 should be equal

,# setup

,# #connect should call Mobile("Connect") and handle an error

,# teardown

,ok 48 should be equal

,ok 49 should be equal

,# setup

,# should call Mobile("Disconnect") without an error

,# teardown

,ok 50 should be equal

,ok 51 should be equal

,# setup

,# should call Mobile("Disconnect") and handle an error

,# teardown

,ok 52 should be equal

,ok 53 should be equal

,# setup

,# #start should fail if called twice in a row

,# teardown

,ok 54 specific error should be received

,# setup

,# #startListeningForAdvertisements should fail if start not called

,# teardown

,ok 55 specific error should be returned

,# setup

,# should be able to call #stopListeningForAdvertisements many times

,# teardown

,ok 56 error should be null

,ok 57 error should be null

,# setup

,# should be able to call #startListeningForAdvertisements many times

,# teardown

,ok 58 error should be null

,ok 59 error should be null

,# setup

,# should be able to call #startUpdateAdvertisingAndListening many times

,# teardown

,ok 60 error should be null

,ok 61 error should be null

,# setup

,# #startUpdateAdvertisingAndListening should fail if start not called

,# teardown

,ok 62 specific error should be returned

,# setup

,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

,# teardown

,2016-02-09 13:41:45.285 ThaliTest[1081:1751651] jxcore: startBroadcasting
,2016-02-09 13:41:45.301 ThaliTest[1081:1751651] server: starting 1455021705284.1081.cCgLQw==
,2016-02-09 13:41:45.303 ThaliTest[1081:1751651] multipeer session: start timer: 0x17261d80
2016-02-09 13:41:45.304 ThaliTest[1081:1751651] THEMultipeerSession initialized peer 1455021705284.1081
2016-02-09 13:41:45.304 ThaliTest[1081:1751651] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error

2016-02-09 13:41:45.308 ThaliTest[1081:1751651] jxcore: stopBroadcasting
,2016-02-09 13:41:45.309 ThaliTest[1081:1751651] THEMultipeerSession stopping peer
2016-02-09 13:41:45.309 ThaliTest[1081:1751651] multipeer session: stop timer
2016-02-09 13:41:45.310 ThaliTest[1081:1751651] jxcore: stopBroadcasting: success
ok 64 Should be able to call stopBroadcasting without error

,2016-02-09 13:41:45.313 ThaliTest[1081:1751651] jxcore: startBroadcasting
,2016-02-09 13:41:45.319 ThaliTest[1081:1751651] server: starting 1455021705312.1081.2vndXQ==
,2016-02-09 13:41:45.321 ThaliTest[1081:1751651] multipeer session: start timer: 0x16624ab0
2016-02-09 13:41:45.321 ThaliTest[1081:1751651] THEMultipeerSession initialized peer 1455021705312.1081
,2016-02-09 13:41:45.324 ThaliTest[1081:1751651] jxcore: startBroadcasting: success
ok 65 Should be able to call startBroadcasting without error

2016-02-09 13:41:45.326 ThaliTest[1081:1751651] jxcore: stopBroadcasting
,2016-02-09 13:41:45.327 ThaliTest[1081:1751651] THEMultipeerSession stopping peer
2016-02-09 13:41:45.327 ThaliTest[1081:1751651] multipeer session: stop timer
,2016-02-09 13:41:45.328 ThaliTest[1081:1751651] jxcore: stopBroadcasting: success
ok 66 Should be able to call stopBroadcasting without error

2016-02-09 13:41:45.330 ThaliTest[1081:1751651] jxcore: startBroadcasting
,2016-02-09 13:41:45.334 ThaliTest[1081:1751651] server: starting 1455021705330.1081.HgZWrQ==
2016-02-09 13:41:45.335 ThaliTest[1081:1751651] multipeer session: start timer: 0x166a7b40
2016-02-09 13:41:45.336 ThaliTest[1081:1751651] THEMultipeerSession initialized peer 1455021705330.1081
,2016-02-09 13:41:45.336 ThaliTest[1081:1751651] jxcore: startBroadcasting: success
ok 67 Should be able to call startBroadcasting without error

,2016-02-09 13:41:45.341 ThaliTest[1081:1751651] jxcore: stopBroadcasting
2016-02-09 13:41:45.342 ThaliTest[1081:1751651] THEMultipeerSession stopping peer
2016-02-09 13:41:45.342 ThaliTest[1081:1751651] multipeer session: stop timer
2016-02-09 13:41:45.,343 ThaliTest[1081:1751651] jxcore: stopBroadcasting: success
ok 68 Should be able to call stopBroadcasting without error

2016-02-09 13:41:45.344 ThaliTest[1081:1751651] jxcore: startBroadcasting
,2016-02-09 13:41:45.349 ThaliTest[1081:1751651] server: starting 1455021705344.1081.++gsqg==
,2016-02-09 13:41:45.351 ThaliTest[1081:1751651] multipeer session: start timer: 0x17252180
2016-02-09 13:41:45.351 ThaliTest[1081:1751651] THEMultipeerSession initialized peer 1455021705344.1081
2016-02-09 13:41:45.352 ThaliTest[1081:1751651] jxcore: startBroadcasting: success
,ok 69 Should be able to call startBroadcasting without error

2016-02-09 13:41:45.356 ThaliTest[1081:1751651] jxcore: stopBroadcasting
2016-02-09 13:41:45.356 ThaliTest[1081:1751651] THEMultipeerSession stopping peer
2016-02-09 13:41:45.356 ThaliTest[1,081:1751651] multipeer session: stop timer
2016-02-09 13:41:45.357 ThaliTest[1081:1751651] jxcore: stopBroadcasting: success
ok 70 Should be able to call stopBroadcasting without error

2016-02-09 13:41:45.359 ThaliTest[1081:1751651] jxcore: startBroadcasting
,2016-02-09 13:41:45.364 ThaliTest[1081:1751651] server: starting 1455021705359.1081.8FlJVA==
2016-02-09 13:41:45.365 ThaliTest[1081:1751651] multipeer session: start timer: 0x170428e0
,2016-02-09 13:41:45.365 ThaliTest[1081:1751651] THEMultipeerSession initialized peer 1455021705359.1081
2016-02-09 13:41:45.366 ThaliTest[1081:1751651] jxcore: startBroadcasting: success
,ok 71 Should be able to call startBroadcasting without error

,2016-02-09 13:41:45.368 ThaliTest[1081:1751651] jxcore: stopBroadcasting
2016-02-09 13:41:45.368 ThaliTest[1081:1751651] THEMultipeerSession stopping peer
2016-02-09 13:41:45.369 ThaliTest[1081:1751651] multipeer session: stop timer
,2016-02-09 13:41:45.369 ThaliTest[1081:1751651] jxcore: stopBroadcasting: success
ok 72 Should be able to call stopBroadcasting without error

,2016-02-09 13:41:45.372 ThaliTest[1081:1751651] jxcore: startBroadcasting
,2016-02-09 13:41:45.375 ThaliTest[1081:1751651] server: starting 1455021705372.1081.pxVnYg==
,2016-02-09 13:41:45.376 ThaliTest[1081:1751651] multipeer session: start timer: 0x14754390
2016-02-09 13:41:45.376 ThaliTest[1081:1751651] THEMultipeerSession initialized peer 1455021705372.1081
2016-02-09 13:41:45.376 ThaliTest[1081:1751651] jxcore: startBroadcasting: success
,ok 73 Should be able to call startBroadcasting without error

2016-02-09 13:41:45.378 ThaliTest[1081:1751651] jxcore: stopBroadcasting
2016-02-09 13:41:45.379 ThaliTest[1081:1751651] THEMultipeerSession stopping peer
2016-02-09 13:41:45.379 ThaliTest[1081:1751651] multipeer session: stop timer
,2016-02-09 13:41:45.379 ThaliTest[1081:1751651] jxcore: stopBroadcasting: success
,ok 74 Should be able to call stopBroadcasting without error

,2016-02-09 13:41:45.382 ThaliTest[1081:1751651] jxcore: startBroadcasting
,2016-02-09 13:41:45.385 ThaliTest[1081:1751651] server: starting 1455021705381.1081.PXxsrA==
2016-02-09 13:41:45.385 ThaliTest[1081:1751651] multipeer session: start timer: 0x16736f90
2016-02-09 13:41:45.385 ThaliTest[1081:1751651] THEMultipeerSession in,itialized peer 1455021705381.1081
2016-02-09 13:41:45.386 ThaliTest[1081:1751651] jxcore: startBroadcasting: success
ok 75 Should be able to call startBroadcasting without error

2016-02-09 13:41:45.387 ThaliTest[1081:1751651] jxcore: stopBroadcasting,
2016-02-09 13:41:45.387 ThaliTest[1081:1751651] THEMultipeerSession stopping peer
2016-02-09 13:41:45.387 ThaliTest[1081:1751651] multipeer session: stop timer
2016-02-09 13:41:45.388 ThaliTest[1081:1751651] jxcore: stopBroadcasting: success
ok 76 Should be able to call stopBroadcasting without error

,2016-02-09 13:41:45.389 ThaliTest[1081:1751651] jxcore: startBroadcasting
,2016-02-09 13:41:45.392 ThaliTest[1081:1751651] server: starting 1455021705389.1081.oZJUiQ==
2016-02-09 13:41:45.393 ThaliTest[1081:1751651] multipeer session: start timer: 0x16737300
,2016-02-09 13:41:45.393 ThaliTest[1081:1751651] THEMultipeerSession initialized peer 1455021705389.1081
2016-02-09 13:41:45.395 ThaliTest[1081:1751651] jxcore: startBroadcasting: success
ok 77 Should be able to call startBroadcasting without error

2016-02-09 13:41:45.396 ThaliTest[1081:1751651] jxcore: stopBroadcasting
2016-02-09 13:41:45.396 ThaliTest[1081:1751651] THEMultipeerSession stopping peer
,2016-02-09 13:41:45.397 ThaliTest[1081:1751651] multipeer session: stop timer
,2016-02-09 13:41:45.397 ThaliTest[1081:1751651] jxcore: stopBroadcasting: success
,ok 78 Should be able to call stopBroadcasting without error

2016-02-09 13:41:45.399 ThaliTest[1081:1751651] jxcore: startBroadcasting
,2016-02-09 13:41:45.401 ThaliTest[1081:1751651] server: starting 1455021705398.1081.KlQ40w==
,2016-02-09 13:41:45.406 ThaliTest[1081:1751651] multipeer session: start timer: 0x16737760
,2016-02-09 13:41:45.407 ThaliTest[1081:1751651] THEMultipeerSession initialized peer 1455021705398.1081
,2016-02-09 13:41:45.408 ThaliTest[1081:1751651] jxcore: startBroadcasting: success
,ok 79 Should be able to call startBroadcasting without error

,2016-02-09 13:41:45.412 ThaliTest[1081:1751651] jxcore: stopBroadcasting
,2016-02-09 13:41:45.413 ThaliTest[1081:1751651] THEMultipeerSession stopping peer
,2016-02-09 13:41:45.413 ThaliTest[1081:1751651] multipeer session: stop timer
,2016-02-09 13:41:45.414 ThaliTest[1081:1751651] jxcore: stopBroadcasting: success
,ok 80 Should be able to call stopBroadcasting without error

,2016-02-09 13:41:45.417 ThaliTest[1081:1751651] jxcore: startBroadcasting
,2016-02-09 13:41:45.420 ThaliTest[1081:1751651] server: starting 1455021705417.1081.JA9bWA==
,2016-02-09 13:41:45.421 ThaliTest[1081:1751651] multipeer session: start timer: 0x16737760
,2016-02-09 13:41:45.423 ThaliTest[1081:1751651] THEMultipeerSession initialized peer 1455021705417.1081
,2016-02-09 13:41:45.425 ThaliTest[1081:1751651] jxcore: startBroadcasting: success
,ok 81 Should be able to call startBroadcasting without error

,2016-02-09 13:41:45.428 ThaliTest[1081:1751651] jxcore: stopBroadcasting
,2016-02-09 13:41:45.428 ThaliTest[1081:1751651] THEMultipeerSession stopping peer
,2016-02-09 13:41:45.429 ThaliTest[1081:1751651] multipeer session: stop timer
,2016-02-09 13:41:45.430 ThaliTest[1081:1751651] jxcore: stopBroadcasting: success
,ok 82 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,# teardown

,2016-02-09 13:41:45.685 ThaliTest[1081:1751651] jxcore: startBroadcasting
,2016-02-09 13:41:45.688 ThaliTest[1081:1751651] server: starting 1455021705684.1081.nRl26Q==
,2016-02-09 13:41:45.690 ThaliTest[1081:1751651] multipeer session: start timer: 0x172522c0
,2016-02-09 13:41:45.696 ThaliTest[1081:1751651] THEMultipeerSession initialized peer 1455021705684.1081
,2016-02-09 13:41:45.697 ThaliTest[1081:1751651] jxcore: startBroadcasting: success
,ok 83 Should be able to call startBroadcasting without error

,2016-02-09 13:41:45.700 ThaliTest[1081:1751651] jxcore: startBroadcasting
,2016-02-09 13:41:45.701 ThaliTest[1081:1751651] jxcore: startBroadcasting: failure
,ok 84 Cannot call startBroadcasting twice

,2016-02-09 13:41:45.706 ThaliTest[1081:1751651] jxcore: stopBroadcasting
,2016-02-09 13:41:45.707 ThaliTest[1081:1751651] THEMultipeerSession stopping peer
,2016-02-09 13:41:45.708 ThaliTest[1081:1751651] multipeer session: stop timer
,2016-02-09 13:41:45.712 ThaliTest[1081:1751651] jxcore: stopBroadcasting: success
,ok 85 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on connection to bad peer

,# teardown

,2016-02-09 13:41:46.165 ThaliTest[1081:1751651] jxcore: startBroadcasting
,2016-02-09 13:41:46.168 ThaliTest[1081:1751651] server: starting 1455021706164.1081.5ekp5Q==
,2016-02-09 13:41:46.169 ThaliTest[1081:1751651] multipeer session: start timer: 0x1729d840
,2016-02-09 13:41:46.170 ThaliTest[1081:1751651] THEMultipeerSession initialized peer 1455021706164.1081
2016-02-09 13:41:46.170 ThaliTest[1081:1751651] jxcore: startBroadcasting: success
,ok 86 Should be able to call startBroadcasting without error

,2016-02-09 13:41:46.178 ThaliTest[1081:1751651] jxcore: connect foobar
,2016-02-09 13:41:46.179 ThaliTest[1081:1751651] client: unknown peer foobar
,2016-02-09 13:41:46.180 ThaliTest[1081:1751651] jxcore: connect: fail: Unknown peer
,ok 87 Should not connect to a bad peer

,2016-02-09 13:41:46.186 ThaliTest[1081:1751651] jxcore: stopBroadcasting
,2016-02-09 13:41:46.187 ThaliTest[1081:1751651] THEMultipeerSession stopping peer
,2016-02-09 13:41:46.188 ThaliTest[1081:1751651] multipeer session: stop timer
,2016-02-09 13:41:46.191 ThaliTest[1081:1751651] jxcore: stopBroadcasting: success
,ok 88 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on disconnect to bad peer

,# teardown

,2016-02-09 13:41:46.678 ThaliTest[1081:1751651] jxcore: startBroadcasting
,2016-02-09 13:41:46.681 ThaliTest[1081:1751651] server: starting 1455021706678.1081.mzwRZw==
,2016-02-09 13:41:46.682 ThaliTest[1081:1751651] multipeer session: start timer: 0x1679b0d0
2016-02-09 13:41:46.683 ThaliTest[1081:1751651] THEMultipeerSession initialized peer 1455021706678.1081
2016-02-09 13:41:46.683 ThaliTest[1081:1751651] jxcore: startBroadcasting: success
,ok 89 Should be able to call startBroadcasting without error

,2016-02-09 13:41:46.692 ThaliTest[1081:1751651] jxcore: disconnect
,2016-02-09 13:41:46.693 ThaliTest[1081:1751651] jxcore: disconnect: fail
,ok 90 Disconnect should fail to a non-existant peer 

,2016-02-09 13:41:46.698 ThaliTest[1081:1751651] jxcore: stopBroadcasting
,2016-02-09 13:41:46.699 ThaliTest[1081:1751651] THEMultipeerSession stopping peer
,2016-02-09 13:41:46.700 ThaliTest[1081:1751651] multipeer session: stop timer
,2016-02-09 13:41:46.705 ThaliTest[1081:1751651] jxcore: stopBroadcasting: success
,ok 91 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter can discover and connect to peers

,# teardown

,2016-02-09 13:41:47.778 ThaliTest[1081:1751651] jxcore: startBroadcasting
,2016-02-09 13:41:47.782 ThaliTest[1081:1751651] server: starting 1455021707778.1081.poBOdw==
,2016-02-09 13:41:47.782 ThaliTest[1081:1751651] multipeer session: start timer: 0x1678aa20
2016-02-09 13:41:47.783 ThaliTest[1081:1751651] THEMultipeerSession initialized peer 1455021707778.1081
2016-02-09 13:41:47.784 ThaliTest[1081:1751651] jxcore: startBroadcasting: success
,ok 92 Should be able to call startBroadcasting without error

,2016-02-09 13:41:49.181 ThaliTest[1081:1751437] client: found peer: 1455021706284.1620.33VlJQ==
,2016-02-09 13:41:49.183 ThaliTest[1081:1751437] multipeer session: reset timer
2016-02-09 13:41:49.183 ThaliTest[1081:1751437] multipeer session: stop timer
2016-02-09 13:41:49.184 ThaliTest[1081:1751437] multipeer session: start timer: 0x1678aa20
2016-,02-09 13:41:49.184 ThaliTest[1081:1751437] server session: connect
2016-02-09 13:41:49.185 ThaliTest[1081:1751437] server session: stateChange:0->1 1455021706284.1620
2016-02-09 13:41:49.184 ThaliTest[1081:1751651] jxcore: connect 1455021706284.1620.33Vl,JQ==
2016-02-09 13:41:49.187 ThaliTest[1081:1751651] client session: connect
2016-02-09 13:41:49.187 ThaliTest[1081:1751651] client session: stateChange:0->1 1455021706284.1620.33VlJQ==
,2016-02-09 13:41:49.197 ThaliTest[1081:1751437] server: accepting invitation 1455021706284.1620
,2016-02-09 13:41:51.829 ThaliTest[1081:1752290] server session: connected
2016-02-09 13:41:51.829 ThaliTest[1081:1752290] server session: stateChange:1->2 1455021706284.1620
,2016-02-09 13:41:51.845 ThaliTest[1081:1751437] server relay: socket disconnected
,2016-02-09 13:41:51.846 ThaliTest[1081:1751437] server relay: 0x174b0d00 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-09 13:41:51.899 ThaliTest[1081:1752288] server session: not connected 1455021706284.1620
,2016-02-09 13:41:52.037 ThaliTest[1081:1752290] client session: connected
2016-02-09 13:41:52.037 ThaliTest[1081:1752290] client session: stateChange:1->2 1455021706284.1620.33VlJQ==
,2016-02-09 13:41:52.062 ThaliTest[1081:1752292] client session: fireConnectCallback: 1455021706284.1620.33VlJQ==
2016-02-09 13:41:52.062 ThaliTest[1081:1752292] jxcore: connect: success
,ok 93 Should be able to connect without error

,ok 94 Port should be within range

,2016-02-09 13:41:52.067 ThaliTest[1081:1751651] jxcore: disconnect
,2016-02-09 13:41:52.068 ThaliTest[1081:1751651] client session: disconnectFromPeer: 1455021706284.1620.33VlJQ==
,2016-02-09 13:41:52.068 ThaliTest[1081:1751651] client session: disconnect
,2016-02-09 13:41:52.069 ThaliTest[1081:1751651] client session: stateChange:2->0 1455021706284.1620.33VlJQ==
,2016-02-09 13:41:52.079 ThaliTest[1081:1751651] jxcore: disconnect: success
ok 95 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-02-09 13:41:52.524 ThaliTest[1081:1751651] jxcore: stopBroadcasting
,2016-02-09 13:41:52.525 ThaliTest[1081:1751651] THEMultipeerSession stopping peer
,2016-02-09 13:41:52.526 ThaliTest[1081:1751651] multipeer session: stop timer
,2016-02-09 13:41:52.527 ThaliTest[1081:1751651] server session: disconnect
2016-02-09 13:41:52.527 ThaliTest[1081:1751651] server session: stateChange:2->0 1455021706284.1620
,2016-02-09 13:41:52.529 ThaliTest[1081:1751651] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double connect

,# teardown

,2016-02-09 13:41:53.594 ThaliTest[1081:1751651] jxcore: startBroadcasting
,2016-02-09 13:41:53.598 ThaliTest[1081:1751651] server: starting 1455021713594.1081.S7JWnA==
,2016-02-09 13:41:53.599 ThaliTest[1081:1751651] multipeer session: start timer: 0x1643c990
,2016-02-09 13:41:53.600 ThaliTest[1081:1751651] THEMultipeerSession initialized peer 1455021713594.1081
2016-02-09 13:41:53.602 ThaliTest[1081:1751651] jxcore: startBroadcasting: success
,ok 96 Should be able to call startBroadcasting without error

,2016-02-09 13:41:54.407 ThaliTest[1081:1751437] client: found peer: 1455021711554.1620.cVRjvg==
,2016-02-09 13:41:54.410 ThaliTest[1081:1751651] jxcore: connect 1455021711554.1620.cVRjvg==
2016-02-09 13:41:54.411 ThaliTest[1081:1751651] client session: connect
2016-02-09 13:41:54.411 ThaliTest[1081:1751651] client session: stateChange:0->1 1455021711554.1620.cVRjvg==
,2016-02-09 13:41:54.916 ThaliTest[1081:1751437] multipeer session: reset timer
2016-02-09 13:41:54.916 ThaliTest[1081:1751437] multipeer session: stop timer
,2016-02-09 13:41:54.917 ThaliTest[1081:1751437] multipeer session: start timer: 0x1643c990
2016-02-09 13:41:54.917 ThaliTest[1081:1751437] server session: connect
,2016-02-09 13:41:54.917 ThaliTest[1081:1751437] server session: stateChange:0->1 1455021711554.1620
,2016-02-09 13:41:54.924 ThaliTest[1081:1751437] server: accepting invitation 1455021711554.1620
,2016-02-09 13:41:57.456 ThaliTest[1081:1752290] client session: connected
,2016-02-09 13:41:57.457 ThaliTest[1081:1752290] client session: stateChange:1->2 1455021711554.1620.cVRjvg==
,2016-02-09 13:41:57.460 ThaliTest[1081:1752290] client session: fireConnectCallback: 1455021711554.1620.cVRjvg==
2016-02-09 13:41:57.461 ThaliTest[1081:1752290] jxcore: connect: success
,ok 97 Should be able to connect without error

,ok 98 Port should be within range

,2016-02-09 13:41:57.465 ThaliTest[1081:1751651] jxcore: connect 1455021711554.1620.cVRjvg==
,2016-02-09 13:41:57.465 ThaliTest[1081:1751651] client: already connect(ing/ed) to 1455021711554.1620.cVRjvg==
,2016-02-09 13:41:57.466 ThaliTest[1081:1751651] jxcore: connect: fail: Aleady connecting
,ok 99 Should fail on double connect

,2016-02-09 13:41:57.470 ThaliTest[1081:1751651] jxcore: disconnect
,2016-02-09 13:41:57.471 ThaliTest[1081:1751651] client session: disconnectFromPeer: 1455021711554.1620.cVRjvg==
,2016-02-09 13:41:57.472 ThaliTest[1081:1751651] client session: disconnect
,2016-02-09 13:41:57.472 ThaliTest[1081:1751651] client session: stateChange:2->0 1455021711554.1620.cVRjvg==
,2016-02-09 13:41:57.550 ThaliTest[1081:1751651] jxcore: disconnect: success
,ok 100 Should be able to disconnect without error

,setting stopBroadcasting callback and ending test.

,2016-02-09 13:41:57.566 ThaliTest[1081:1752290] server session: connected
,2016-02-09 13:41:57.567 ThaliTest[1081:1752290] server session: stateChange:1->2 1455021711554.1620
,# setup

,2016-02-09 13:41:57.584 ThaliTest[1081:1751437] server relay: socket disconnected
,2016-02-09 13:41:57.584 ThaliTest[1081:1751437] server relay: 0x166811d0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection ,refused} 
,2016-02-09 13:41:57.630 ThaliTest[1081:1752288] server session: not connected 1455021711554.1620
,calling stopBroadcasting

,2016-02-09 13:41:57.761 ThaliTest[1081:1751651] jxcore: stopBroadcasting
,2016-02-09 13:41:57.761 ThaliTest[1081:1751651] THEMultipeerSession stopping peer
2016-02-09 13:41:57.762 ThaliTest[1081:1751651] multipeer session: stop timer
,2016-02-09 13:41:57.762 ThaliTest[1081:1751651] server session: disconnect
2016-02-09 13:41:57.763 ThaliTest[1081:1751651] server session: stateChange:2->0 1455021711554.1620
2016-02-09 13:41:57.765 ThaliTest[1081:1751651] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,# teardown

,2016-02-09 13:41:58.320 ThaliTest[1081:1751651] jxcore: startBroadcasting
,2016-02-09 13:41:58.323 ThaliTest[1081:1751651] server: starting 1455021718319.1081.miCMOQ==
,2016-02-09 13:41:58.324 ThaliTest[1081:1751651] multipeer session: start timer: 0x174b5320
,2016-02-09 13:41:58.324 ThaliTest[1081:1751651] THEMultipeerSession initialized peer 1455021718319.1081
,2016-02-09 13:41:58.325 ThaliTest[1081:1751651] jxcore: startBroadcasting: success
,ok 101 Should be able to call startBroadcasting without error

,2016-02-09 13:41:59.530 ThaliTest[1081:1751437] multipeer session: reset timer
2016-02-09 13:41:59.530 ThaliTest[1081:1751437] multipeer session: stop timer
2016-02-09 13:41:59.530 ThaliTest[1081:1751437] multipeer session: start timer: 0x174b5320
2016-02-09 13:41:59.531 ThaliTest[1081:1751437] server session: connect
2016-02-09 13:41:59.531 ThaliTest[1081:1751437] server session: stateChange:0->1 1455021716800.1620
,2016-02-09 13:41:59.538 ThaliTest[1081:1751437] server: accepting invitation 1455021716800.1620
,2016-02-09 13:41:59.592 ThaliTest[1081:1751437] client: found peer: 1455021716800.1620.2qdl/g==
2016-02-09 13:41:59.593 ThaliTest[1081:1751651] jxcore: connect 1455021716800.1620.2qdl/g==
,2016-02-09 13:41:59.594 ThaliTest[1081:1751651] client session: connect
,2016-02-09 13:41:59.595 ThaliTest[1081:1751651] client session: stateChange:0->1 1455021716800.1620.2qdl/g==
,2016-02-09 13:42:02.211 ThaliTest[1081:1752335] server session: connected
2016-02-09 13:42:02.211 ThaliTest[1081:1752335] server session: stateChange:1->2 1455021716800.1620
,2016-02-09 13:42:02.217 ThaliTest[1081:1751437] server relay: socket disconnected
,2016-02-09 13:42:02.217 ThaliTest[1081:1751437] server relay: 0x17498750 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-09 13:42:02.272 ThaliTest[1081:1752335] server session: not connected 1455021716800.1620
,2016-02-09 13:42:02.296 ThaliTest[1081:1752293] client session: connected
2016-02-09 13:42:02.297 ThaliTest[1081:1752293] client session: stateChange:1->2 1455021716800.1620.2qdl/g==
,2016-02-09 13:42:02.325 ThaliTest[1081:1752290] client session: fireConnectCallback: 1455021716800.1620.2qdl/g==
2016-02-09 13:42:02.325 ThaliTest[1081:1752290] jxcore: connect: success
,ok 102 Should be able to connect without error

,ok 103 Port should be within range

,2016-02-09 13:42:02.330 ThaliTest[1081:1751651] jxcore: disconnect
,2016-02-09 13:42:02.330 ThaliTest[1081:1751651] client session: disconnectFromPeer: 1455021716800.1620.2qdl/g==
2016-02-09 13:42:02.331 ThaliTest[1081:1751651] client session: disconnect
,2016-02-09 13:42:02.331 ThaliTest[1081:1751651] client session: stateChange:2->0 1455021716800.1620.2qdl/g==
,2016-02-09 13:42:02.341 ThaliTest[1081:1751651] jxcore: disconnect: success
ok 104 Should be able to disconnect without error

,2016-02-09 13:42:02.344 ThaliTest[1081:1751651] jxcore: disconnect
2016-02-09 13:42:02.345 ThaliTest[1081:1751651] jxcore: disconnect: fail
ok 105 Disconnect should fail 

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-02-09 13:42:02.500 ThaliTest[1081:1751651] jxcore: stopBroadcasting
,2016-02-09 13:42:02.501 ThaliTest[1081:1751651] THEMultipeerSession stopping peer
,2016-02-09 13:42:02.501 ThaliTest[1081:1751651] multipeer session: stop timer
,2016-02-09 13:42:02.502 ThaliTest[1081:1751651] server session: disconnect
,2016-02-09 13:42:02.502 ThaliTest[1081:1751651] server session: stateChange:2->0 1455021716800.1620
,2016-02-09 13:42:02.505 ThaliTest[1081:1751651] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter can connect and send data

,# teardown

,echo server started on port: 55861

,2016-02-09 13:42:03.663 ThaliTest[1081:1751651] jxcore: startBroadcasting
,2016-02-09 13:42:03.664 ThaliTest[1081:1751651] server: starting 1455021723663.1081.ObekEA==
,2016-02-09 13:42:03.665 ThaliTest[1081:1751651] multipeer session: start timer: 0x166999f0
2016-02-09 13:42:03.665 ThaliTest[1081:1751651] THEMultipeerSession initialized peer 1455021723663.1081
,2016-02-09 13:42:03.665 ThaliTest[1081:1751651] jxcore: startBroadcasting: success
ok 106 Should be able to call startBroadcasting without error

,2016-02-09 13:42:04.759 ThaliTest[1081:1751437] client: found peer: 1455021722225.1620.NsK3Lw==
,2016-02-09 13:42:04.760 ThaliTest[1081:1751651] jxcore: connect 1455021722225.1620.NsK3Lw==
2016-02-09 13:42:04.761 ThaliTest[1081:1751651] client session: connect
2016-02-09 13:42:04.761 ThaliTest[1081:1751651] client session: stateChange:0->1 1455021722225.1620.NsK3Lw==
,2016-02-09 13:42:05.268 ThaliTest[1081:1751437] multipeer session: reset timer
2016-02-09 13:42:05.268 ThaliTest[1081:1751437] multipeer session: stop timer
2016-02-09 13:42:05.268 ThaliTest[1081:1751437] multipeer session: start timer: 0x166999f0
2016-02-09 13:42:05.269 ThaliTest[1081:1751437] server session: connect
2016-02-09 13:42:05.269 ThaliTest[1081:1751437] server session: stateChange:0->1 1455021722225.1620
,2016-02-09 13:42:05.277 ThaliTest[1081:1751437] server: accepting invitation 1455021722225.1620
,2016-02-09 13:42:07.793 ThaliTest[1081:1752335] client session: connected
2016-02-09 13:42:07.794 ThaliTest[1081:1752335] client session: stateChange:1->2 1455021722225.1620.NsK3Lw==
,2016-02-09 13:42:07.799 ThaliTest[1081:1752294] client session: fireConnectCallback: 1455021722225.1620.NsK3Lw==
2016-02-09 13:42:07.799 ThaliTest[1081:1752294] jxcore: connect: success
,ok 107 Should be able to connect without error

,ok 108 Port should be within range

,2016-02-09 13:42:07.805 ThaliTest[1081:1751437] client: relay established
2016-02-09 13:42:07.806 ThaliTest[1081:1751437] client: new accepted socket: 0x17104950
,data in 4096

,data in 26280

,data in 30660

,data in 31755

,data in 43800

,data in 59130

,data in 60225

,data in 80847

,data in 130305

,data in 131072

,ok 109 the test messages should be equal

,2016-02-09 13:42:08.277 ThaliTest[1081:1751651] jxcore: disconnect
,2016-02-09 13:42:08.278 ThaliTest[1081:1751651] client session: disconnectFromPeer: 1455021722225.1620.NsK3Lw==
,2016-02-09 13:42:08.278 ThaliTest[1081:1751651] client session: disconnect
,2016-02-09 13:42:08.279 ThaliTest[1081:1751651] client session: stateChange:2->0 1455021722225.1620.NsK3Lw==
,2016-02-09 13:42:08.289 ThaliTest[1081:1751651] jxcore: disconnect: success
,ok 110 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,2016-02-09 13:42:09.158 ThaliTest[1081:1752294] server session: connected
,2016-02-09 13:42:09.158 ThaliTest[1081:1752294] server session: stateChange:1->2 1455021722225.1620
,2016-02-09 13:42:09.167 ThaliTest[1081:1751437] server relay: connected (to port: 55861)
,2016-02-09 13:42:09.742 ThaliTest[1081:1752288] server session: not connected 1455021722225.1620
,calling stopBroadcasting

,2016-02-09 13:42:09.814 ThaliTest[1081:1751651] jxcore: stopBroadcasting
,2016-02-09 13:42:09.815 ThaliTest[1081:1751651] THEMultipeerSession stopping peer
2016-02-09 13:42:09.815 ThaliTest[1081:1751651] multipeer session: stop timer
,2016-02-09 13:42:09.816 ThaliTest[1081:1751651] server session: disconnect
2016-02-09 13:42:09.817 ThaliTest[1081:1751651] server session: stateChange:2->0 1455021722225.1620
,2016-02-09 13:42:10.129 ThaliTest[1081:1751651] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter handles socket disconnect correctly

,# teardown

,echo server started on port: 55867

,2016-02-09 13:42:10.416 ThaliTest[1081:1751651] jxcore: startBroadcasting
,2016-02-09 13:42:10.419 ThaliTest[1081:1751651] server: starting 1455021730415.1081.TLIvfQ==
,2016-02-09 13:42:10.420 ThaliTest[1081:1751651] multipeer session: start timer: 0x147614d0
,2016-02-09 13:42:10.420 ThaliTest[1081:1751651] THEMultipeerSession initialized peer 1455021730415.1081
2016-02-09 13:42:10.421 ThaliTest[1081:1751651] jxcore: startBroadcasting: success
ok 111 Should be able to call startBroadcasting without error

,2016-02-09 13:42:11.510 ThaliTest[1081:1751437] client: found peer: 1455021728929.1620.Zh8/dA==
,[{"peerIdentifier":"1455021728929.1620.Zh8/dA==","peerName":"(null)","peerAvailable":true}]

,2016-02-09 13:42:11.513 ThaliTest[1081:1751651] jxcore: connect 1455021728929.1620.Zh8/dA==
,2016-02-09 13:42:11.514 ThaliTest[1081:1751651] client session: connect
,2016-02-09 13:42:11.515 ThaliTest[1081:1751651] client session: stateChange:0->1 1455021728929.1620.Zh8/dA==
,2016-02-09 13:42:11.705 ThaliTest[1081:1751437] multipeer session: reset timer
2016-02-09 13:42:11.706 ThaliTest[1081:1751437] multipeer session: stop timer
,2016-02-09 13:42:11.706 ThaliTest[1081:1751437] multipeer session: start timer: 0x147614d0
,2016-02-09 13:42:11.706 ThaliTest[1081:1751437] server session: connect
2016-02-09 13:42:11.707 ThaliTest[1081:1751437] server session: stateChange:0->1 1455021728929.1620
,2016-02-09 13:42:11.713 ThaliTest[1081:1751437] server: accepting invitation 1455021728929.1620
,2016-02-09 13:42:14.210 ThaliTest[1081:1752288] client session: connected
,2016-02-09 13:42:14.210 ThaliTest[1081:1752288] client session: stateChange:1->2 1455021728929.1620.Zh8/dA==
,2016-02-09 13:42:14.263 ThaliTest[1081:1752288] client session: fireConnectCallback: 1455021728929.1620.Zh8/dA==
2016-02-09 13:42:14.264 ThaliTest[1081:1752288] jxcore: connect: success
ok 112 Should be able to connect without error

ok 113 Port should be within range

,ok 114 First connect should succeed

,2016-02-09 13:42:14.274 ThaliTest[1081:1752288] server session: connected
2016-02-09 13:42:14.275 ThaliTest[1081:1752288] server session: stateChange:1->2 1455021728929.1620
,2016-02-09 13:42:14.298 ThaliTest[1081:1751437] server relay: connected (to port: 55867)
,2016-02-09 13:42:14.327 ThaliTest[1081:1751437] client: relay established
2016-02-09 13:42:14.328 ThaliTest[1081:1751437] client: new accepted socket: 0x174b0d00
,ok 115 the test messages should be equal

,ok 116 First send should succeed

,2016-02-09 13:42:14.409 ThaliTest[1081:1751437] client: socket closed
,2016-02-09 13:42:14.409 ThaliTest[1081:1751437] client relay: socket disconnected
,2016-02-09 13:42:14.409 ThaliTest[1081:1751437] client relay: 0x174b0d00 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2016-02-09 13:42:14.410 ThaliTest[1081:1751437] client session: socket closed: 1455021728929.1620.Zh8/dA==
2016-02-09 13:42:14.410 ThaliTest[1081:1751437] client session: onLinkFailure: 1455021728929.1620.Zh8/dA==
2016-02-09 13:42:14.410 ThaliTest[1081:1,751437] client session: disconnect
2016-02-09 13:42:14.411 ThaliTest[1081:1751437] client session: stateChange:2->0 1455021728929.1620.Zh8/dA==
,2016-02-09 13:42:14.421 ThaliTest[1081:1751437] client session: fireConnectionErrorEvent: 1455021728929.1620.Zh8/dA==
,2016-02-09 13:42:14.425 ThaliTest[1081:1751651] jxcore: connect 1455021728929.1620.Zh8/dA==
,2016-02-09 13:42:14.426 ThaliTest[1081:1751651] client session: connect
,2016-02-09 13:42:14.429 ThaliTest[1081:1751651] client session: stateChange:0->1 1455021728929.1620.Zh8/dA==
,2016-02-09 13:42:14.468 ThaliTest[1081:1752335] server session: not connected 1455021728929.1620
,2016-02-09 13:42:14.653 ThaliTest[1081:1751437] multipeer session: reset timer
2016-02-09 13:42:14.654 ThaliTest[1081:1751437] multipeer session: stop timer
2016-02-09 13:42:14.654 ThaliTest[1081:1751437] multipeer session: start timer: 0x147614d0
2016-,02-09 13:42:14.654 ThaliTest[1081:1751437] server: disconnecting to refresh session (1455021728929.1620)
2016-02-09 13:42:14.654 ThaliTest[1081:1751437] server session: disconnect
,2016-02-09 13:42:14.655 ThaliTest[1081:1751437] server session: stateChange:2->0 1455021728929.1620
,2016-02-09 13:42:14.659 ThaliTest[1081:1751437] server session: connect
2016-02-09 13:42:14.660 ThaliTest[1081:1751437] server session: stateChange:0->1 1455021728929.1620
,2016-02-09 13:42:14.667 ThaliTest[1081:1751437] server: accepting invitation 1455021728929.1620
,2016-02-09 13:42:17.100 ThaliTest[1081:1752335] client session: connected
2016-02-09 13:42:17.100 ThaliTest[1081:1752335] client session: stateChange:1->2 1455021728929.1620.Zh8/dA==
,2016-02-09 13:42:17.129 ThaliTest[1081:1752335] client session: fireConnectCallback: 1455021728929.1620.Zh8/dA==
,2016-02-09 13:42:17.129 ThaliTest[1081:1752335] jxcore: connect: success
,ok 117 Should be able to connect without error

,ok 118 Port should be within range

,ok 119 Second connect should succeed

,2016-02-09 13:42:17.166 ThaliTest[1081:1751437] client: relay established
2016-02-09 13:42:17.166 ThaliTest[1081:1751437] client: new accepted socket: 0x167da240
,ok 120 the test messages should be equal

,ok 121 Second send should succeed

,# setup

,2016-02-09 13:42:17.232 ThaliTest[1081:1752290] server session: connected
2016-02-09 13:42:17.232 ThaliTest[1081:1752290] server session: stateChange:1->2 1455021728929.1620
,2016-02-09 13:42:17.234 ThaliTest[1081:1751437] client: socket closed
,2016-02-09 13:42:17.235 ThaliTest[1081:1751437] client relay: socket disconnected
,2016-02-09 13:42:17.235 ThaliTest[1081:1751437] client relay: 0x167da240 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2016-02-09 13:42:17.235 ThaliTest[1081:1751437] client session: socket closed: 1455021728929.1620.Zh8/dA==
2016-02-09 13:42:17.235 ThaliTest[1081:1751437] client session: onLinkFailure: 1455021728929.1620.Zh8/dA==
,2016-02-09 13:42:17.236 ThaliTest[1081:1751437] client session: disconnect
2016-02-09 13:42:17.236 ThaliTest[1081:1751437] client session: stateChange:2->0 1455021728929.1620.Zh8/dA==
,2016-02-09 13:42:17.248 ThaliTest[1081:1751437] client session: fireConnectionErrorEvent: 1455021728929.1620.Zh8/dA==
,2016-02-09 13:42:17.263 ThaliTest[1081:1751437] server relay: connected (to port: 55867)
,2016-02-09 13:42:17.422 ThaliTest[1081:1752368] server session: not connected 1455021728929.1620
,calling stopBroadcasting

,2016-02-09 13:42:17.686 ThaliTest[1081:1751651] jxcore: stopBroadcasting
,2016-02-09 13:42:17.687 ThaliTest[1081:1751651] THEMultipeerSession stopping peer
,2016-02-09 13:42:17.687 ThaliTest[1081:1751651] multipeer session: stop timer
,2016-02-09 13:42:17.688 ThaliTest[1081:1751651] server session: disconnect
2016-02-09 13:42:17.689 ThaliTest[1081:1751651] server session: stateChange:2->0 1455021728929.1620
,2016-02-09 13:42:17.696 ThaliTest[1081:1751651] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliReplicationManager can call start without error

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/39DC2D29-8FC2-471D-9E48-3A2BAAC1D134/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,ok 122 starting event should occur in right order

,2016-02-09 13:42:18.206 ThaliTest[1081:1751651] jxcore: startBroadcasting
,2016-02-09 13:42:18.207 ThaliTest[1081:1751651] server: starting 2HEd01SRKhm8KBSuSAzcIg.HBCyGA==
,2016-02-09 13:42:18.208 ThaliTest[1081:1751651] multipeer session: start timer: 0x167c85a0
2016-02-09 13:42:18.208 ThaliTest[1081:1751651] THEMultipeerSession initialized peer 2HEd01SRKhm8KBSuSAzcIg
2016-02-09 13:42:18.208 ThaliTest[1081:1751651] jxcore: startBroadcasting: success
,ok 123 started event should occur in right order

,Now in TRM stop

State of this._isStarted: true

,ok 124 stopping event should occur in right order

About to call stopBroadcasting

2016-02-09 13:42:18.210 ThaliTest[1081:1751651] jxcore: stopBroadcasting
2016-02-09 13:42:18.210 ThaliTest[1081:1751651] THEMultipeerSession stopping peer
,2016-02-09 13:42:18.210 ThaliTest[1081:1751651] multipeer session: stop timer
2016-02-09 13:42:18.211 ThaliTest[1081:1751651] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,ok 125 stopped event should occur in right order

,mux server bridge listener closed

,# setup

,# ThaliReplicationManager receives identity

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/39DC2D29-8FC2-471D-9E48-3A2BAAC1D134/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-02-09 13:42:18.656 ThaliTest[1081:1751651] jxcore: startBroadcasting
,2016-02-09 13:42:18.659 ThaliTest[1081:1751651] server: starting 2HEd01SRKhm8KBSuSAzcIg.T3lz8g==
,2016-02-09 13:42:18.660 ThaliTest[1081:1751651] multipeer session: start timer: 0x167da200
,2016-02-09 13:42:18.660 ThaliTest[1081:1751651] THEMultipeerSession initialized peer 2HEd01SRKhm8KBSuSAzcIg
2016-02-09 13:42:18.661 ThaliTest[1081:1751651] jxcore: startBroadcasting: success
ok 126 getDeviceIdentity should not return an error

,ok 127 deviceName should not be null

,Now in TRM stop

,State of this._isStarted: true

,About to call stopBroadcasting

,2016-02-09 13:42:18.666 ThaliTest[1081:1751651] jxcore: stopBroadcasting
2016-02-09 13:42:18.667 ThaliTest[1081:1751651] THEMultipeerSession stopping peer
2016-02-09 13:42:18.667 ThaliTest[1081:1751651] multipeer session: stop timer
,2016-02-09 13:42:18.672 ThaliTest[1081:1751651] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,mux server bridge listener closed

,# setup

,# ThaliReplicationManager replicates database

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/39DC2D29-8FC2-471D-9E48-3A2BAAC1D134/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-02-09 13:42:20.627 ThaliTest[1081:1751651] jxcore: startBroadcasting
,2016-02-09 13:42:20.628 ThaliTest[1081:1751651] server: starting 2HEd01SRKhm8KBSuSAzcIg.fWNtwg==
,2016-02-09 13:42:20.628 ThaliTest[1081:1751651] multipeer session: start timer: 0x16707bd0
2016-02-09 13:42:20.628 ThaliTest[1081:1751651] THEMultipeerSession initialized peer 2HEd01SRKhm8KBSuSAzcIg
2016-02-09 13:42:20.629 ThaliTest[1081:1751651] jxcore: startBroadcasting: success
ok 128 getDeviceIdentity should not return an error

,ok 129 deviceName should not be null

,2016-02-09 13:42:20.633 ThaliTest[1081:1751437] client: found peer: 1455021728929.1620.Zh8/dA==
,2016-02-09 13:42:24.723 ThaliTest[1081:1751437] client: found peer: bKW0MF74g-13gggg2lZtCg.dhRfRQ==
,2016-02-09 13:42:24.746 ThaliTest[1081:1751651] jxcore: connect 1455021728929.1620.Zh8/dA==
2016-02-09 13:42:24.746 ThaliTest[1081:1751651] client session: connect
,2016-02-09 13:42:24.746 ThaliTest[1081:1751651] client session: stateChange:0->1 1455021728929.1620.Zh8/dA==
,2016-02-09 13:42:24.749 ThaliTest[1081:1751651] jxcore: connect bKW0MF74g-13gggg2lZtCg.dhRfRQ==
2016-02-09 13:42:24.749 ThaliTest[1081:1751651] client session: connect
2016-02-09 13:42:24.749 ThaliTest[1081:1751651] client session: stateChange:0->1 bKW0MF74g-13gggg2lZtCg.dhRfRQ==
,ok 130 Should be able to put doc without error

,ok 131 1st change of local doc should contain local id

,2016-02-09 13:42:25.587 ThaliTest[1081:1751437] multipeer session: reset timer
,2016-02-09 13:42:25.588 ThaliTest[1081:1751437] multipeer session: stop timer
,2016-02-09 13:42:25.588 ThaliTest[1081:1751437] multipeer session: start timer: 0x16707bd0
,2016-02-09 13:42:25.589 ThaliTest[1081:1751437] server session: connect
,2016-02-09 13:42:25.589 ThaliTest[1081:1751437] server session: stateChange:0->1 bKW0MF74g-13gggg2lZtCg
,2016-02-09 13:42:25.596 ThaliTest[1081:1751437] server: accepting invitation bKW0MF74g-13gggg2lZtCg
,2016-02-09 13:42:26.114 ThaliTest[1081:1751437] client: lost peer: 1455021728929.1620.Zh8/dA==
2016-02-09 13:42:26.114 ThaliTest[1081:1751437] client session: onPeerLost: 1455021728929.1620.Zh8/dA==
2016-02-09 13:42:26.115 ThaliTest[1081:1751437] client ,session: onLinkFailure: 1455021728929.1620.Zh8/dA==
2016-02-09 13:42:26.115 ThaliTest[1081:1751437] client session: disconnect
2016-02-09 13:42:26.115 ThaliTest[1081:1751437] client session: stateChange:1->0 1455021728929.1620.Zh8/dA==
,2016-02-09 13:42:26.116 ThaliTest[1081:1751437] client session: fireConnectCallback: 1455021728929.1620.Zh8/dA==
2016-02-09 13:42:26.116 ThaliTest[1081:1751437] jxcore: connect: fail: Peer disconnected
,Connect error with error: Error: Peer disconnected

,2016-02-09 13:42:26.134 ThaliTest[1081:1751651] jxcore: disconnect
,2016-02-09 13:42:26.134 ThaliTest[1081:1751651] jxcore: disconnect: fail
,Disconnect error with error: Error: Not connected to specified peer

,peerIdentifier not available 1455021728929.1620.Zh8/dA==

,2016-02-09 13:42:28.028 ThaliTest[1081:1752335] client session: connected
,2016-02-09 13:42:28.028 ThaliTest[1081:1752335] client session: stateChange:1->2 bKW0MF74g-13gggg2lZtCg.dhRfRQ==
,2016-02-09 13:42:28.033 ThaliTest[1081:1752294] client session: fireConnectCallback: bKW0MF74g-13gggg2lZtCg.dhRfRQ==
2016-02-09 13:42:28.033 ThaliTest[1081:1752294] jxcore: connect: success
,2016-02-09 13:42:28.045 ThaliTest[1081:1751437] client: relay established
2016-02-09 13:42:28.046 ThaliTest[1081:1751437] client: new accepted socket: 0x1457ae40
,client bridge: new client socket

,client bridge: new client socket

,2016-02-09 13:42:28.415 ThaliTest[1081:1752294] server session: connected
,2016-02-09 13:42:28.415 ThaliTest[1081:1752294] server session: stateChange:1->2 bKW0MF74g-13gggg2lZtCg
,2016-02-09 13:42:28.419 ThaliTest[1081:1751437] server relay: connected (to port: 55882)
,server bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed
,
,client bridge: socket closed

,client bridge: socket closed

,ok 132 1st change of remote doc should contain remote id

,client bridge: new client socket

,ok 133 Can update remote doc without error

,null

,{ ok: true,
  id: 'cdd7db0a-96c6-4cc8-86a7-c5c49454e0ec',
  rev: '2-d9d944a60c12189c2769a34656dc3cd2' }

,client bridge: new client socket

,ok 134 Remote changes occur in strict order

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: socket closed

,client bridge: socket closed

,client bridge: new client socket

,ok 135 Local changes occur in strict order

,ok 136 2nd change of local doc should contain remote id
,
,# setup

,client bridge: new client socket

,client bridge: new client socket

,Now in TRM stop

State of this._isStarted: true

,About to call stopBroadcasting

,2016-02-09 13:42:47.093 ThaliTest[1081:1751651] jxcore: stopBroadcasting
,2016-02-09 13:42:47.093 ThaliTest[1081:1751651] THEMultipeerSession stopping peer
,2016-02-09 13:42:47.094 ThaliTest[1081:1751651] multipeer session: stop timer
,2016-02-09 13:42:47.095 ThaliTest[1081:1751651] client session: disconnect
2016-02-09 13:42:47.095 ThaliTest[1081:1751651] client session: stateChange:2->0 bKW0MF74g-13gggg2lZtCg.dhRfRQ==
,2016-02-09 13:42:47.102 ThaliTest[1081:1751651] server session: disconnect
2016-02-09 13:42:47.102 ThaliTest[1081:1751651] server session: stateChange:2->0 bKW0MF74g-13gggg2lZtCg
,2016-02-09 13:42:47.126 ThaliTest[1081:1751651] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined
,
,# After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

,mux server bridge listener closed

,client bridge: socket closed

,server bridge: socket closed

,client bridge: socket closed

,client bridge: socket closed


```
