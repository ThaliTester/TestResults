#### Test 584164489c56086_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/584164489c56086/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/9994521D-40B0-4FA4-A343-BCE148F65D51/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/9994521D-40B0-4FA4-A343-BCE148F65D51/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/584164489c56086/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/584164489c56086/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/83FAEBA9-EBB1-4A92-B56F-C747BB4D0ED6/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52744"
,(lldb)     command script import "/tmp/9994521D-40B0-4FA4-A343-BCE148F65D51/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-09 10:18:55.408 ThaliTest[1052:1726307] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4F90DFE8-5D1D-458A-BBA8-421CA9F507B3/Library/Cookies/Cookies.binarycookies
,2016-02-09 10:18:55.756 ThaliTest[1052:1726307] Apache Cordova native platform version 4.0.1 is starting.
,2016-02-09 10:18:55.757 ThaliTest[1052:1726307] Multi-tasking -> Device: YES, App: YES
,2016-02-09 10:18:55.772 ThaliTest[1052:1726307] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-09 10:18:57.611 ThaliTest[1052:1726307] Using UIWebView
,2016-02-09 10:18:57.620 ThaliTest[1052:1726307] [CDVTimer][handleopenurl] 0.389993ms
,2016-02-09 10:18:57.627 ThaliTest[1052:1726307] [CDVTimer][intentandnavigationfilter] 6.671011ms
,2016-02-09 10:18:57.628 ThaliTest[1052:1726307] [CDVTimer][gesturehandler] 0.298023ms
,2016-02-09 10:18:57.628 ThaliTest[1052:1726307] [CDVTimer][TotalPluginStartup] 8.895993ms
,2016-02-09 10:19:05.752 ThaliTest[1052:1726307] Resetting plugins due to page load.
,2016-02-09 10:19:09.720 ThaliTest[1052:1726307] Finished load of: file:///var/mobile/Containers/Bundle/Application/83FAEBA9-EBB1-4A92-B56F-C747BB4D0ED6/ThaliTest.app/www/index.html
,2016-02-09 10:19:09.923 ThaliTest[1052:1726307] JXcore Cordova plugin initializing
,2016-02-09 10:19:09.924 ThaliTest[1052:1726565] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/83FAEBA9-EBB1-4A92-B56F-C747BB4D0ED6/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/83FAEBA9-EBB1-4A92-B56F-C747BB4D0ED6/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/83FAEBA9-EBB1-4A92-B56F-C747BB4D0ED6/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/83FAEBA9-EBB1-4A92-B56F-C747BB4D0ED6/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/83FAEBA9-EBB1-4A92-B56F-C747BB4D0ED6/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/83FAEBA9-EBB1-4A92-B56F-C747BB4D0ED6/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/83FAEBA9-EBB1-4A92-B56F-C747BB4D0ED6/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/83FAEBA9-EBB1-4A92-B56F-C747BB4D0ED6/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/83FAEBA9-EBB1-4A92-B56F-C747BB4D0ED6/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

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

ok 22 should be equal

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

,2016-02-09 10:23:46.433 ThaliTest[1052:1726565] jxcore: startBroadcasting
,2016-02-09 10:23:46.450 ThaliTest[1052:1726565] server: starting 1455009826433.1052.9Miv/g==
,2016-02-09 10:23:46.451 ThaliTest[1052:1726565] multipeer session: start timer: 0x1629b9d0
,2016-02-09 10:23:46.452 ThaliTest[1052:1726565] THEMultipeerSession initialized peer 1455009826433.1052
2016-02-09 10:23:46.453 ThaliTest[1052:1726565] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error

2016-02-09 10:23:46.457 ThaliTest[1052:1726565] jxcore: stopBroadcasting
2016-02-09 10:23:46.457 ThaliTest[1052:1726565] THEMultipeerSession stopping peer
2016-02-09 10:23:46.458 ThaliTest[1,052:1726565] multipeer session: stop timer
2016-02-09 10:23:46.458 ThaliTest[1052:1726565] jxcore: stopBroadcasting: success
ok 64 Should be able to call stopBroadcasting without error

2016-02-09 10:23:46.460 ThaliTest[1052:1726565] jxcore: startBroad,casting
,2016-02-09 10:23:46.466 ThaliTest[1052:1726565] server: starting 1455009826460.1052.M2zW5g==
,2016-02-09 10:23:46.469 ThaliTest[1052:1726565] multipeer session: start timer: 0x174860e0
2016-02-09 10:23:46.469 ThaliTest[1052:1726565] THEMultipeerSession initialized peer 1455009826460.1052
2016-02-09 10:23:46.469 ThaliTest[1052:1726565] jxcore: sta,rtBroadcasting: success
ok 65 Should be able to call startBroadcasting without error

2016-02-09 10:23:46.471 ThaliTest[1052:1726565] jxcore: stopBroadcasting
2016-02-09 10:23:46.472 ThaliTest[1052:1726565] THEMultipeerSession stopping peer
2016-02-09, 10:23:46.472 ThaliTest[1052:1726565] multipeer session: stop timer
2016-02-09 10:23:46.472 ThaliTest[1052:1726565] jxcore: stopBroadcasting: success
ok 66 Should be able to call stopBroadcasting without error

,2016-02-09 10:23:46.474 ThaliTest[1052:1726565] jxcore: startBroadcasting
,2016-02-09 10:23:46.479 ThaliTest[1052:1726565] server: starting 1455009826474.1052.t9IIgQ==
2016-02-09 10:23:46.479 ThaliTest[1052:1726565] multipeer session: start timer: 0x17487170
,2016-02-09 10:23:46.482 ThaliTest[1052:1726565] THEMultipeerSession initialized peer 1455009826474.1052
2016-02-09 10:23:46.482 ThaliTest[1052:1726565] jxcore: startBroadcasting: success
ok 67 Should be able to call startBroadcasting without error

201,6-02-09 10:23:46.484 ThaliTest[1052:1726565] jxcore: stopBroadcasting
2016-02-09 10:23:46.484 ThaliTest[1052:1726565] THEMultipeerSession stopping peer
2016-02-09 10:23:46.485 ThaliTest[1052:1726565] multipeer session: stop timer
2016-02-09 10:23:46.486, ThaliTest[1052:1726565] jxcore: stopBroadcasting: success
ok 68 Should be able to call stopBroadcasting without error

2016-02-09 10:23:46.488 ThaliTest[1052:1726565] jxcore: startBroadcasting
,2016-02-09 10:23:46.496 ThaliTest[1052:1726565] server: starting 1455009826487.1052.Hi4/Lg==
2016-02-09 10:23:46.496 ThaliTest[1052:1726565] multipeer session: start timer: 0x1729a540
2016-02-09 10:23:46.498 ThaliTest[1052:1726565] THEMultipeerSession initialized peer 1455009826487.1052
2016-02-09 10:23:46.498 ThaliTest[1052:1726565] jxcore: startBroadcasting: success
ok 69 Should be able to call startBroadcasting without error

,2016-02-09 10:23:46.501 ThaliTest[1052:1726565] jxcore: stopBroadcasting
,2016-02-09 10:23:46.502 ThaliTest[1052:1726565] THEMultipeerSession stopping peer
,2016-02-09 10:23:46.503 ThaliTest[1052:1726565] multipeer session: stop timer
,2016-02-09 10:23:46.503 ThaliTest[1052:1726565] jxcore: stopBroadcasting: success
ok 70 Should be able to call stopBroadcasting without error

2016-02-09 10:23:46.506 ThaliTest[1052:1726565] jxcore: startBroadcasting
,2016-02-09 10:23:46.510 ThaliTest[1052:1726565] server: starting 1455009826505.1052.LEJQkw==
2016-02-09 10:23:46.513 ThaliTest[1052:1726565] multipeer session: start timer: 0x1729c920
2016-02-09 10:23:46.513 ThaliTest[1052:1726565] THEMultipeerSession in,itialized peer 1455009826505.1052
2016-02-09 10:23:46.513 ThaliTest[1052:1726565] jxcore: startBroadcasting: success
ok 71 Should be able to call startBroadcasting without error

,2016-02-09 10:23:46.516 ThaliTest[1052:1726565] jxcore: stopBroadcasting
2016-02-09 10:23:46.518 ThaliTest[1052:1726565] THEMultipeerSession stopping peer
2016-02-09 10:23:46.519 ThaliTest[1052:1726565] multipeer session: stop timer
,2016-02-09 10:23:46.520 ThaliTest[1052:1726565] jxcore: stopBroadcasting: success
,ok 72 Should be able to call stopBroadcasting without error

,2016-02-09 10:23:46.523 ThaliTest[1052:1726565] jxcore: startBroadcasting
,2016-02-09 10:23:46.527 ThaliTest[1052:1726565] server: starting 1455009826522.1052./FwpYg==
2016-02-09 10:23:46.528 ThaliTest[1052:1726565] multipeer session: start timer: 0x1729bd40
2016-02-09 10:23:46.528 ThaliTest[1052:1726565] THEMultipeerSession in,itialized peer 1455009826522.1052
2016-02-09 10:23:46.529 ThaliTest[1052:1726565] jxcore: startBroadcasting: success
ok 73 Should be able to call startBroadcasting without error

2016-02-09 10:23:46.531 ThaliTest[1052:1726565] jxcore: stopBroadcasting,
2016-02-09 10:23:46.531 ThaliTest[1052:1726565] THEMultipeerSession stopping peer
2016-02-09 10:23:46.531 ThaliTest[1052:1726565] multipeer session: stop timer
2016-02-09 10:23:46.532 ThaliTest[1052:1726565] jxcore: stopBroadcasting: success
,ok 74 Should be able to call stopBroadcasting without error

,2016-02-09 10:23:46.534 ThaliTest[1052:1726565] jxcore: startBroadcasting
,2016-02-09 10:23:46.541 ThaliTest[1052:1726565] server: starting 1455009826533.1052.6zG6gA==
,2016-02-09 10:23:46.544 ThaliTest[1052:1726565] multipeer session: start timer: 0x1729dcd0
,2016-02-09 10:23:46.546 ThaliTest[1052:1726565] THEMultipeerSession initialized peer 1455009826533.1052
,2016-02-09 10:23:46.547 ThaliTest[1052:1726565] jxcore: startBroadcasting: success
,ok 75 Should be able to call startBroadcasting without error

,2016-02-09 10:23:46.549 ThaliTest[1052:1726565] jxcore: stopBroadcasting
,2016-02-09 10:23:46.549 ThaliTest[1052:1726565] THEMultipeerSession stopping peer
,2016-02-09 10:23:46.550 ThaliTest[1052:1726565] multipeer session: stop timer
,2016-02-09 10:23:46.551 ThaliTest[1052:1726565] jxcore: stopBroadcasting: success
,ok 76 Should be able to call stopBroadcasting without error

,2016-02-09 10:23:46.554 ThaliTest[1052:1726565] jxcore: startBroadcasting
,2016-02-09 10:23:46.557 ThaliTest[1052:1726565] server: starting 1455009826554.1052.281MIw==
,2016-02-09 10:23:46.559 ThaliTest[1052:1726565] multipeer session: start timer: 0x16775400
,2016-02-09 10:23:46.559 ThaliTest[1052:1726565] THEMultipeerSession initialized peer 1455009826554.1052
,2016-02-09 10:23:46.560 ThaliTest[1052:1726565] jxcore: startBroadcasting: success
,ok 77 Should be able to call startBroadcasting without error

,2016-02-09 10:23:46.564 ThaliTest[1052:1726565] jxcore: stopBroadcasting
2016-02-09 10:23:46.564 ThaliTest[1052:1726565] THEMultipeerSession stopping peer
,2016-02-09 10:23:46.565 ThaliTest[1052:1726565] multipeer session: stop timer
,2016-02-09 10:23:46.566 ThaliTest[1052:1726565] jxcore: stopBroadcasting: success
,ok 78 Should be able to call stopBroadcasting without error

,2016-02-09 10:23:46.569 ThaliTest[1052:1726565] jxcore: startBroadcasting
,2016-02-09 10:23:46.572 ThaliTest[1052:1726565] server: starting 1455009826569.1052.sfRBAA==
,2016-02-09 10:23:46.573 ThaliTest[1052:1726565] multipeer session: start timer: 0x1729bf70
,2016-02-09 10:23:46.574 ThaliTest[1052:1726565] THEMultipeerSession initialized peer 1455009826569.1052
,2016-02-09 10:23:46.576 ThaliTest[1052:1726565] jxcore: startBroadcasting: success
,ok 79 Should be able to call startBroadcasting without error

,2016-02-09 10:23:46.578 ThaliTest[1052:1726565] jxcore: stopBroadcasting
,2016-02-09 10:23:46.579 ThaliTest[1052:1726565] THEMultipeerSession stopping peer
2016-02-09 10:23:46.580 ThaliTest[1052:1726565] multipeer session: stop timer
,2016-02-09 10:23:46.582 ThaliTest[1052:1726565] jxcore: stopBroadcasting: success
,ok 80 Should be able to call stopBroadcasting without error

,2016-02-09 10:23:46.584 ThaliTest[1052:1726565] jxcore: startBroadcasting
,2016-02-09 10:23:46.587 ThaliTest[1052:1726565] server: starting 1455009826584.1052.tWHC6w==
,2016-02-09 10:23:46.588 ThaliTest[1052:1726565] multipeer session: start timer: 0x17488760
,2016-02-09 10:23:46.591 ThaliTest[1052:1726565] THEMultipeerSession initialized peer 1455009826584.1052
,2016-02-09 10:23:46.593 ThaliTest[1052:1726565] jxcore: startBroadcasting: success
,ok 81 Should be able to call startBroadcasting without error

,2016-02-09 10:23:46.594 ThaliTest[1052:1726565] jxcore: stopBroadcasting
,2016-02-09 10:23:46.595 ThaliTest[1052:1726565] THEMultipeerSession stopping peer
,2016-02-09 10:23:46.595 ThaliTest[1052:1726565] multipeer session: stop timer
,2016-02-09 10:23:46.597 ThaliTest[1052:1726565] jxcore: stopBroadcasting: success
,ok 82 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,# teardown

,2016-02-09 10:23:46.847 ThaliTest[1052:1726565] jxcore: startBroadcasting
,2016-02-09 10:23:46.850 ThaliTest[1052:1726565] server: starting 1455009826846.1052.VwATog==
,2016-02-09 10:23:46.853 ThaliTest[1052:1726565] multipeer session: start timer: 0x17488da0
,2016-02-09 10:23:46.857 ThaliTest[1052:1726565] THEMultipeerSession initialized peer 1455009826846.1052
,2016-02-09 10:23:46.858 ThaliTest[1052:1726565] jxcore: startBroadcasting: success
,ok 83 Should be able to call startBroadcasting without error

,2016-02-09 10:23:46.861 ThaliTest[1052:1726565] jxcore: startBroadcasting
2016-02-09 10:23:46.862 ThaliTest[1052:1726565] jxcore: startBroadcasting: failure
,ok 84 Cannot call startBroadcasting twice

,2016-02-09 10:23:46.867 ThaliTest[1052:1726565] jxcore: stopBroadcasting
,2016-02-09 10:23:46.868 ThaliTest[1052:1726565] THEMultipeerSession stopping peer
,2016-02-09 10:23:46.870 ThaliTest[1052:1726565] multipeer session: stop timer
,2016-02-09 10:23:46.873 ThaliTest[1052:1726565] jxcore: stopBroadcasting: success
,ok 85 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on connection to bad peer

,# teardown

,2016-02-09 10:23:47.381 ThaliTest[1052:1726565] jxcore: startBroadcasting
,2016-02-09 10:23:47.384 ThaliTest[1052:1726565] server: starting 1455009827380.1052.57+G4A==
,2016-02-09 10:23:47.385 ThaliTest[1052:1726565] multipeer session: start timer: 0x172a1e20
2016-02-09 10:23:47.385 ThaliTest[1052:1726565] THEMultipeerSession initialized peer 1455009827380.1052
2016-02-09 10:23:47.386 ThaliTest[1052:1726565] jxcore: sta,rtBroadcasting: success
ok 86 Should be able to call startBroadcasting without error

,2016-02-09 10:23:47.389 ThaliTest[1052:1726565] jxcore: connect foobar
2016-02-09 10:23:47.389 ThaliTest[1052:1726565] client: unknown peer foobar
2016-02-09 10:23:47.389 ThaliTest[1052:1726565] jxcore: connect: fail: Unknown peer
,ok 87 Should not connect to a bad peer

2016-02-09 10:23:47.393 ThaliTest[1052:1726565] jxcore: stopBroadcasting
2016-02-09 10:23:47.393 ThaliTest[1052:1726565] THEMultipeerSession stopping peer
2016-02-09 10:23:47.393 ThaliTest[1052:1726565] multipeer session: stop timer
2016-02-09 10:23:47.394 ThaliTest[1052:1726565] jxcore: stopBroadcasting: success
,ok 88 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on disconnect to bad peer

,# teardown

,2016-02-09 10:23:47.858 ThaliTest[1052:1726565] jxcore: startBroadcasting
,2016-02-09 10:23:47.861 ThaliTest[1052:1726565] server: starting 1455009827858.1052.Fp93aQ==
,2016-02-09 10:23:47.862 ThaliTest[1052:1726565] multipeer session: start timer: 0x172a4380
,2016-02-09 10:23:47.863 ThaliTest[1052:1726565] THEMultipeerSession initialized peer 1455009827858.1052
2016-02-09 10:23:47.863 ThaliTest[1052:1726565] jxcore: startBroadcasting: success
,ok 89 Should be able to call startBroadcasting without error

2016-02-09 10:23:47.866 ThaliTest[1052:1726565] jxcore: disconnect
2016-02-09 10:23:47.867 ThaliTest[1052:1726565] jxcore: disconnect: fail
,ok 90 Disconnect should fail to a non-existant peer 

2016-02-09 10:23:47.870 ThaliTest[1052:1726565] jxcore: stopBroadcasting
2016-02-09 10:23:47.870 ThaliTest[1052:1726565] THEMultipeerSession stopping peer
2016-02-09 10:23:47.871 ThaliTest[1052:1726,565] multipeer session: stop timer
2016-02-09 10:23:47.871 ThaliTest[1052:1726565] jxcore: stopBroadcasting: success
,ok 91 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter can discover and connect to peers

,# teardown

,2016-02-09 10:23:48.331 ThaliTest[1052:1726565] jxcore: startBroadcasting
,2016-02-09 10:23:48.335 ThaliTest[1052:1726565] server: starting 1455009828331.1052.2k96ig==
,2016-02-09 10:23:48.335 ThaliTest[1052:1726565] multipeer session: start timer: 0x1748d650
2016-02-09 10:23:48.336 ThaliTest[1052:1726565] THEMultipeerSession initialized peer 1455009828331.1052
2016-02-09 10:23:48.336 ThaliTest[1052:1726565] jxcore: startBroadcasting: success
,ok 92 Should be able to call startBroadcasting without error

,2016-02-09 10:23:49.571 ThaliTest[1052:1726307] client: found peer: 1455009827083.1582.o+ApXQ==
,2016-02-09 10:23:49.573 ThaliTest[1052:1726565] jxcore: connect 1455009827083.1582.o+ApXQ==
2016-02-09 10:23:49.574 ThaliTest[1052:1726565] client session: connect
,2016-02-09 10:23:49.574 ThaliTest[1052:1726565] client session: stateChange:0->1 1455009827083.1582.o+ApXQ==
,2016-02-09 10:23:49.772 ThaliTest[1052:1726307] multipeer session: reset timer
2016-02-09 10:23:49.772 ThaliTest[1052:1726307] multipeer session: stop timer
2016-02-09 10:23:49.773 ThaliTest[1052:1726307] multipeer session: start timer: 0x1748d650
,2016-02-09 10:23:49.773 ThaliTest[1052:1726307] server session: connect
2016-02-09 10:23:49.774 ThaliTest[1052:1726307] server session: stateChange:0->1 1455009827083.1582
,2016-02-09 10:23:49.781 ThaliTest[1052:1726307] server: accepting invitation 1455009827083.1582
,2016-02-09 10:23:52.210 ThaliTest[1052:1727074] server session: connected
2016-02-09 10:23:52.210 ThaliTest[1052:1727074] server session: stateChange:1->2 1455009827083.1582
,2016-02-09 10:23:52.215 ThaliTest[1052:1726307] server relay: socket disconnected
,2016-02-09 10:23:52.215 ThaliTest[1052:1726307] server relay: 0x162446f0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-09 10:23:52.269 ThaliTest[1052:1727080] server session: not connected 1455009827083.1582
,2016-02-09 10:23:52.333 ThaliTest[1052:1727076] client session: connected
,2016-02-09 10:23:52.333 ThaliTest[1052:1727076] client session: stateChange:1->2 1455009827083.1582.o+ApXQ==
,2016-02-09 10:23:52.339 ThaliTest[1052:1727072] client session: fireConnectCallback: 1455009827083.1582.o+ApXQ==
2016-02-09 10:23:52.339 ThaliTest[1052:1727072] jxcore: connect: success
,ok 93 Should be able to connect without error

,ok 94 Port should be within range

,2016-02-09 10:23:52.344 ThaliTest[1052:1726565] jxcore: disconnect
,2016-02-09 10:23:52.344 ThaliTest[1052:1726565] client session: disconnectFromPeer: 1455009827083.1582.o+ApXQ==
,2016-02-09 10:23:52.345 ThaliTest[1052:1726565] client session: disconnect
,2016-02-09 10:23:52.346 ThaliTest[1052:1726565] client session: stateChange:2->0 1455009827083.1582.o+ApXQ==
,2016-02-09 10:23:52.356 ThaliTest[1052:1726565] jxcore: disconnect: success
,ok 95 Should be able to disconnect without error

,setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-02-09 10:23:52.593 ThaliTest[1052:1726565] jxcore: stopBroadcasting
,2016-02-09 10:23:52.594 ThaliTest[1052:1726565] THEMultipeerSession stopping peer
,2016-02-09 10:23:52.595 ThaliTest[1052:1726565] multipeer session: stop timer
,2016-02-09 10:23:52.595 ThaliTest[1052:1726565] server session: disconnect
2016-02-09 10:23:52.596 ThaliTest[1052:1726565] server session: stateChange:2->0 1455009827083.1582
,2016-02-09 10:23:52.599 ThaliTest[1052:1726565] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double connect

,# teardown

,2016-02-09 10:23:52.669 ThaliTest[1052:1726565] jxcore: startBroadcasting
,2016-02-09 10:23:52.672 ThaliTest[1052:1726565] server: starting 1455009832668.1052.O/6BBA==
,2016-02-09 10:23:52.673 ThaliTest[1052:1726565] multipeer session: start timer: 0x172ab420
2016-02-09 10:23:52.673 ThaliTest[1052:1726565] THEMultipeerSession initialized peer 1455009832668.1052
2016-02-09 10:23:52.674 ThaliTest[1052:1726565] jxcore: startBroadcasting: success
ok 96 Should be able to call startBroadcasting without error

,2016-02-09 10:23:53.386 ThaliTest[1052:1726307] client: found peer: 1455009827083.1582.o+ApXQ==
2016-02-09 10:23:53.386 ThaliTest[1052:1726307] client: found peer: 1455009828331.1052.2k96ig==
,2016-02-09 10:23:53.388 ThaliTest[1052:1726565] jxcore: connect 1455009827083.1582.o+ApXQ==
,2016-02-09 10:23:53.388 ThaliTest[1052:1726565] client session: connect
,2016-02-09 10:23:53.389 ThaliTest[1052:1726565] client session: stateChange:0->1 1455009827083.1582.o+ApXQ==
,2016-02-09 10:23:53.396 ThaliTest[1052:1726565] jxcore: connect 1455009828331.1052.2k96ig==
2016-02-09 10:23:53.397 ThaliTest[1052:1726565] client session: connect
2016-02-09 10:23:53.397 ThaliTest[1052:1726565] client session: stateChange:0->1 1455009828331.1052.2k96ig==
,2016-02-09 10:23:53.748 ThaliTest[1052:1726307] client: lost peer: 1455009827083.1582.o+ApXQ==
,2016-02-09 10:23:53.749 ThaliTest[1052:1726307] client session: onPeerLost: 1455009827083.1582.o+ApXQ==
2016-02-09 10:23:53.749 ThaliTest[1052:1726307] client session: onLinkFailure: 1455009827083.1582.o+ApXQ==
,2016-02-09 10:23:53.749 ThaliTest[1052:1726307] client session: disconnect
2016-02-09 10:23:53.750 ThaliTest[1052:1726307] client session: stateChange:1->0 1455009827083.1582.o+ApXQ==
,2016-02-09 10:23:53.750 ThaliTest[1052:1726307] client session: fireConnectCallback: 1455009827083.1582.o+ApXQ==
,2016-02-09 10:23:53.751 ThaliTest[1052:1726307] jxcore: connect: fail: Peer disconnected
,2016-02-09 10:23:53.752 ThaliTest[1052:1726307] client: lost peer: 1455009828331.1052.2k96ig==
2016-02-09 10:23:53.752 ThaliTest[1052:1726307] client session: onPeerLost: 1455009828331.1052.2k96ig==
2016-02-09 10:23:53.753 ThaliTest[1052:1726307] client session: onLinkFailure: 1455009828331.1052.2k96ig==
2016-02-09 10:23:53.753 ThaliTest[1052:1726307] client session: disconnect
2016-02-09 10:23:53.753 ThaliTest[1052:1726307] client session: stateChange:1->0 1455009828331.1052.2k96ig==
2016-02-09 10:23:,53.754 ThaliTest[1052:1726307] client session: fireConnectCallback: 1455009828331.1052.2k96ig==
2016-02-09 10:23:53.754 ThaliTest[1052:1726307] jxcore: connect: fail: Peer disconnected
,2016-02-09 10:23:53.804 ThaliTest[1052:1726307] client: found peer: 1455009831386.1582.irKX/A==
,2016-02-09 10:23:53.805 ThaliTest[1052:1726565] jxcore: connect 1455009831386.1582.irKX/A==
2016-02-09 10:23:53.806 ThaliTest[1052:1726565] client session: connect
2016-02-09 10:23:53.806 ThaliTest[1052:1726565] client session: stateChange:0->1 1455009831386.1582.irKX/A==
,2016-02-09 10:23:53.868 ThaliTest[1052:1726307] multipeer session: reset timer
2016-02-09 10:23:53.868 ThaliTest[1052:1726307] multipeer session: stop timer
2016-02-09 10:23:53.868 ThaliTest[1052:1726307] multipeer session: start timer: 0x172ab420
,2016-02-09 10:23:53.869 ThaliTest[1052:1726307] server session: connect
2016-02-09 10:23:53.869 ThaliTest[1052:1726307] server session: stateChange:0->1 1455009831386.1582
,2016-02-09 10:23:53.876 ThaliTest[1052:1726307] server: accepting invitation 1455009831386.1582
,2016-02-09 10:23:54.753 ThaliTest[1052:1726565] jxcore: connect 1455009827083.1582.o+ApXQ==
2016-02-09 10:23:54.754 ThaliTest[1052:1726565] client: connect: unreachable 1455009827083.1582.o+ApXQ==
,2016-02-09 10:23:54.755 ThaliTest[1052:1726565] jxcore: connect: fail: Peer unreachable
,2016-02-09 10:23:54.768 ThaliTest[1052:1726565] jxcore: connect 1455009828331.1052.2k96ig==
,2016-02-09 10:23:54.769 ThaliTest[1052:1726565] client: connect: unreachable 1455009828331.1052.2k96ig==
,2016-02-09 10:23:54.770 ThaliTest[1052:1726565] jxcore: connect: fail: Peer unreachable
,2016-02-09 10:23:56.321 ThaliTest[1052:1727077] server session: connected
2016-02-09 10:23:56.321 ThaliTest[1052:1727077] server session: stateChange:1->2 1455009831386.1582
,2016-02-09 10:23:56.326 ThaliTest[1052:1726307] server relay: socket disconnected
,2016-02-09 10:23:56.326 ThaliTest[1052:1726307] server relay: 0x172b0a50 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-09 10:23:56.369 ThaliTest[1052:1727077] server session: not connected 1455009831386.1582
,2016-02-09 10:23:56.521 ThaliTest[1052:1727077] client session: connected
2016-02-09 10:23:56.522 ThaliTest[1052:1727077] client session: stateChange:1->2 1455009831386.1582.irKX/A==
,2016-02-09 10:23:56.529 ThaliTest[1052:1727077] client session: fireConnectCallback: 1455009831386.1582.irKX/A==
2016-02-09 10:23:56.530 ThaliTest[1052:1727077] jxcore: connect: success
,ok 97 Should be able to connect without error

,ok 98 Port should be within range

,2016-02-09 10:23:56.533 ThaliTest[1052:1726565] jxcore: connect 1455009831386.1582.irKX/A==
,2016-02-09 10:23:56.534 ThaliTest[1052:1726565] client: already connect(ing/ed) to 1455009831386.1582.irKX/A==
,2016-02-09 10:23:56.534 ThaliTest[1052:1726565] jxcore: connect: fail: Aleady connecting
,ok 99 Should fail on double connect

,2016-02-09 10:23:56.537 ThaliTest[1052:1726565] jxcore: disconnect
,2016-02-09 10:23:56.537 ThaliTest[1052:1726565] client session: disconnectFromPeer: 1455009831386.1582.irKX/A==
2016-02-09 10:23:56.538 ThaliTest[1052:1726565] client session: disconnect
,2016-02-09 10:23:56.538 ThaliTest[1052:1726565] client session: stateChange:2->0 1455009831386.1582.irKX/A==
,2016-02-09 10:23:56.601 ThaliTest[1052:1726565] jxcore: disconnect: success
ok 100 Should be able to disconnect without error

,setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-02-09 10:23:56.798 ThaliTest[1052:1726565] jxcore: stopBroadcasting
,2016-02-09 10:23:56.798 ThaliTest[1052:1726565] THEMultipeerSession stopping peer
,2016-02-09 10:23:56.799 ThaliTest[1052:1726565] multipeer session: stop timer
,2016-02-09 10:23:56.800 ThaliTest[1052:1726565] server session: disconnect
2016-02-09 10:23:56.805 ThaliTest[1052:1726565] server session: stateChange:2->0 1455009831386.1582
2016-02-09 10:23:56.806 ThaliTest[1052:1726565] jxcore: stopBroadcasting: succe,ss
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,# teardown

,2016-02-09 10:23:56.850 ThaliTest[1052:1726565] jxcore: startBroadcasting
,2016-02-09 10:23:56.853 ThaliTest[1052:1726565] server: starting 1455009836849.1052.KWL4Rg==
,2016-02-09 10:23:56.854 ThaliTest[1052:1726565] multipeer session: start timer: 0x173461b0
2016-02-09 10:23:56.854 ThaliTest[1052:1726565] THEMultipeerSession initialized peer 1455009836849.1052
2016-02-09 10:23:56.855 ThaliTest[1052:1726565] jxcore: startBroadcasting: success
,ok 101 Should be able to call startBroadcasting without error

,2016-02-09 10:23:56.865 ThaliTest[1052:1726307] client: found peer: 1455009832668.1052.O/6BBA==
2016-02-09 10:23:56.865 ThaliTest[1052:1726307] client: found peer: 1455009831386.1582.irKX/A==
,2016-02-09 10:23:56.866 ThaliTest[1052:1726565] jxcore: connect 1455009832668.1052.O/6BBA==
2016-02-09 10:23:56.866 ThaliTest[1052:1726565] client session: connect
2016-02-09 10:23:56.866 ThaliTest[1052:1726565] client session: stateChange:0->1 145500983,2668.1052.O/6BBA==
,2016-02-09 10:23:56.873 ThaliTest[1052:1726565] jxcore: connect 1455009831386.1582.irKX/A==
2016-02-09 10:23:56.873 ThaliTest[1052:1726565] client session: connect
,2016-02-09 10:23:56.873 ThaliTest[1052:1726565] client session: stateChange:0->1 1455009831386.1582.irKX/A==
,2016-02-09 10:23:58.075 ThaliTest[1052:1726307] client: lost peer: 1455009832668.1052.O/6BBA==
2016-02-09 10:23:58.075 ThaliTest[1052:1726307] client session: onPeerLost: 1455009832668.1052.O/6BBA==
2016-02-09 10:23:58.075 ThaliTest[1052:1726307] client ,session: onLinkFailure: 1455009832668.1052.O/6BBA==
2016-02-09 10:23:58.075 ThaliTest[1052:1726307] client session: disconnect
2016-02-09 10:23:58.076 ThaliTest[1052:1726307] client session: stateChange:1->0 1455009832668.1052.O/6BBA==
2016-02-09 10:23:,58.076 ThaliTest[1052:1726307] client session: fireConnectCallback: 1455009832668.1052.O/6BBA==
,2016-02-09 10:23:58.077 ThaliTest[1052:1726307] jxcore: connect: fail: Peer disconnected
,2016-02-09 10:23:58.733 ThaliTest[1052:1726307] multipeer session: reset timer
2016-02-09 10:23:58.734 ThaliTest[1052:1726307] multipeer session: stop timer
2016-02-09 10:23:58.734 ThaliTest[1052:1726307] multipeer session: start timer: 0x173461b0
,2016-02-09 10:23:58.734 ThaliTest[1052:1726307] server session: connect
,2016-02-09 10:23:58.735 ThaliTest[1052:1726307] server session: stateChange:0->1 1455009835583.1582
,2016-02-09 10:23:58.742 ThaliTest[1052:1726307] server: accepting invitation 1455009835583.1582
,2016-02-09 10:23:58.757 ThaliTest[1052:1726307] client: found peer: 1455009835583.1582.JwZBEg==
2016-02-09 10:23:58.759 ThaliTest[1052:1726565] jxcore: connect 1455009835583.1582.JwZBEg==
2016-02-09 10:23:58.759 ThaliTest[1052:1726565] client session: connect
2016-02-09 10:23:58.760 ThaliTest[1052:1726565] client session: stateChange:0->1 1455009835583.1582.JwZBEg==
,2016-02-09 10:23:59.083 ThaliTest[1052:1726565] jxcore: connect 1455009832668.1052.O/6BBA==
,2016-02-09 10:23:59.084 ThaliTest[1052:1726565] client: connect: unreachable 1455009832668.1052.O/6BBA==
,2016-02-09 10:23:59.084 ThaliTest[1052:1726565] jxcore: connect: fail: Peer unreachable
,2016-02-09 10:24:04.223 ThaliTest[1052:1727076] server session: connected
2016-02-09 10:24:04.224 ThaliTest[1052:1727076] server session: stateChange:1->2 1455009835583.1582
,2016-02-09 10:24:04.231 ThaliTest[1052:1727076] client session: connected
,2016-02-09 10:24:04.232 ThaliTest[1052:1727076] client session: stateChange:1->2 1455009835583.1582.JwZBEg==
,2016-02-09 10:24:04.536 ThaliTest[1052:1726307] server relay: socket disconnected
2016-02-09 10:24:04.536 ThaliTest[1052:1726307] server relay: 0x1749c780 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-09 10:24:04.859 ThaliTest[1052:1727080] client session: fireConnectCallback: 1455009835583.1582.JwZBEg==
2016-02-09 10:24:04.859 ThaliTest[1052:1727080] jxcore: connect: success
,ok 102 Should be able to connect without error

,ok 103 Port should be within range

,2016-02-09 10:24:04.864 ThaliTest[1052:1726565] jxcore: disconnect
,2016-02-09 10:24:04.864 ThaliTest[1052:1726565] client session: disconnectFromPeer: 1455009835583.1582.JwZBEg==
,2016-02-09 10:24:04.865 ThaliTest[1052:1726565] client session: disconnect
,2016-02-09 10:24:04.865 ThaliTest[1052:1726565] client session: stateChange:2->0 1455009835583.1582.JwZBEg==
,2016-02-09 10:24:04.877 ThaliTest[1052:1726565] jxcore: disconnect: success
ok 104 Should be able to disconnect without error

2016-02-09 10:24:04.879 ThaliTest[1052:1726565] jxcore: disconnect
2016-02-09 10:24:04.879 ThaliTest[1052:1726565] jxcore: disconnect: fail
,ok 105 Disconnect should fail 

setting stopBroadcasting callback and ending test.

,# setup

,2016-02-09 10:24:04.928 ThaliTest[1052:1727077] server session: not connected 1455009835583.1582
,calling stopBroadcasting

,2016-02-09 10:24:05.064 ThaliTest[1052:1726565] jxcore: stopBroadcasting
,2016-02-09 10:24:05.064 ThaliTest[1052:1726565] THEMultipeerSession stopping peer
,2016-02-09 10:24:05.065 ThaliTest[1052:1726565] multipeer session: stop timer
,2016-02-09 10:24:05.065 ThaliTest[1052:1726565] client session: disconnect
,2016-02-09 10:24:05.066 ThaliTest[1052:1726565] client session: stateChange:1->0 1455009831386.1582.irKX/A==
2016-02-09 10:24:05.067 ThaliTest[1052:1726565] server session: disconnect
2016-02-09 10:24:05.067 ThaliTest[1052:1726565] server session: stateC,hange:2->0 1455009835583.1582
,2016-02-09 10:24:05.072 ThaliTest[1052:1726565] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can connect and send data

,# teardown

,echo server started on port: 55567

,2016-02-09 10:24:06.703 ThaliTest[1052:1726565] jxcore: startBroadcasting
,2016-02-09 10:24:06.704 ThaliTest[1052:1726565] server: starting 1455009846703.1052.4yoxhg==
,2016-02-09 10:24:06.705 ThaliTest[1052:1726565] multipeer session: start timer: 0x172b2630
2016-02-09 10:24:06.705 ThaliTest[1052:1726565] THEMultipeerSession initialized peer 1455009846703.1052
2016-02-09 10:24:06.705 ThaliTest[1052:1726565] jxcore: startBroadcasting: success
,ok 106 Should be able to call startBroadcasting without error

,2016-02-09 10:24:08.081 ThaliTest[1052:1726307] client: found peer: 1455009845488.1582.fZwK3w==
,2016-02-09 10:24:08.083 ThaliTest[1052:1726565] jxcore: connect 1455009845488.1582.fZwK3w==
2016-02-09 10:24:08.083 ThaliTest[1052:1726565] client session: connect
2016-02-09 10:24:08.083 ThaliTest[1052:1726565] client session: stateChange:0->1 145500984,5488.1582.fZwK3w==
,2016-02-09 10:24:08.511 ThaliTest[1052:1726307] multipeer session: reset timer
,2016-02-09 10:24:08.511 ThaliTest[1052:1726307] multipeer session: stop timer
2016-02-09 10:24:08.511 ThaliTest[1052:1726307] multipeer session: start timer: 0x172b2630
,2016-02-09 10:24:08.512 ThaliTest[1052:1726307] server session: connect
2016-02-09 10:24:08.512 ThaliTest[1052:1726307] server session: stateChange:0->1 1455009845488.1582
,2016-02-09 10:24:08.519 ThaliTest[1052:1726307] server: accepting invitation 1455009845488.1582
,2016-02-09 10:24:13.328 ThaliTest[1052:1727077] client session: connected
2016-02-09 10:24:13.328 ThaliTest[1052:1727077] client session: stateChange:1->2 1455009845488.1582.fZwK3w==
,2016-02-09 10:24:13.458 ThaliTest[1052:1727080] client session: fireConnectCallback: 1455009845488.1582.fZwK3w==
2016-02-09 10:24:13.459 ThaliTest[1052:1727080] jxcore: connect: success
ok 107 Should be able to connect without error

ok 108 Port should be within range

,2016-02-09 10:24:13.467 ThaliTest[1052:1726307] client: relay established
2016-02-09 10:24:13.468 ThaliTest[1052:1726307] client: new accepted socket: 0x173530e0
,2016-02-09 10:24:13.471 ThaliTest[1052:1727076] server session: connected
,2016-02-09 10:24:13.472 ThaliTest[1052:1727076] server session: stateChange:1->2 1455009845488.1582
,2016-02-09 10:24:13.486 ThaliTest[1052:1726307] server relay: connected (to port: 55567)
,data in 1095

,data in 2190

,data in 3285

,data in 4380

,data in 5475

,2016-02-09 10:24:25.060 ThaliTest[1052:1727259] client session: not connected 1455009845488.1582.fZwK3w==
2016-02-09 10:24:25.060 ThaliTest[1052:1727259] client session: onLinkFailure: 1455009845488.1582.fZwK3w==
2016-02-09 10:24:25.061 ThaliTest[1052:1727259] client session: disconnect
,2016-02-09 10:24:25.061 ThaliTest[1052:1727259] client session: stateChange:2->0 1455009845488.1582.fZwK3w==
,2016-02-09 10:24:25.065 ThaliTest[1052:1727259] client session: fireConnectionErrorEvent: 1455009845488.1582.fZwK3w==
,2016-02-09 10:24:38.513 ThaliTest[1052:1726307] multipeer session: restart
,2016-02-09 10:24:38.534 ThaliTest[1052:1726307] client: found peer: 1455009845488.1582.fZwK3w==
,2016-02-09 10:25:01.409 ThaliTest[1052:1727314] server session: not connected 1455009845488.1582
,2016-02-09 10:25:08.513 ThaliTest[1052:1726307] multipeer session: restart
,2016-02-09 10:25:08.537 ThaliTest[1052:1726307] client: found peer: 1455009845488.1582.fZwK3w==
,2016-02-09 10:25:38.513 ThaliTest[1052:1726307] multipeer session: restart
,2016-02-09 10:25:38.538 ThaliTest[1052:1726307] client: found peer: 1455009845488.1582.fZwK3w==
,2016-02-09 10:26:08.513 ThaliTest[1052:1726307] multipeer session: restart
,2016-02-09 10:26:08.539 ThaliTest[1052:1726307] client: found peer: 1455009845488.1582.fZwK3w==
,2016-02-09 10:26:38.513 ThaliTest[1052:1726307] multipeer session: restart
,2016-02-09 10:27:08.513 ThaliTest[1052:1726307] multipeer session: restart
,2016-02-09 10:27:08.534 ThaliTest[1052:1726307] client: found peer: 1455009845488.1582.fZwK3w==
,2016-02-09 10:27:38.499 ThaliTest[1052:1726307] multipeer session: restart
,2016-02-09 10:27:38.521 ThaliTest[1052:1726307] client: found peer: 1455009845488.1582.fZwK3w==
,2016-02-09 10:28:08.499 ThaliTest[1052:1726307] multipeer session: restart
,2016-02-09 10:28:08.520 ThaliTest[1052:1726307] client: found peer: 1455009845488.1582.fZwK3w==
,2016-02-09 10:28:38.498 ThaliTest[1052:1726307] multipeer session: restart
,2016-02-09 10:28:38.520 ThaliTest[1052:1726307] client: found peer: 1455009845488.1582.fZwK3w==
,2016-02-09 10:29:08.499 ThaliTest[1052:1726307] multipeer session: restart
,2016-02-09 10:29:08.521 ThaliTest[1052:1726307] client: found peer: 1455009845488.1582.fZwK3w==
,2016-02-09 10:29:38.499 ThaliTest[1052:1726307] multipeer session: restart
,2016-02-09 10:29:38.520 ThaliTest[1052:1726307] client: found peer: 1455009845488.1582.fZwK3w==
,2016-02-09 10:30:08.499 ThaliTest[1052:1726307] multipeer session: restart
,2016-02-09 10:30:08.518 ThaliTest[1052:1726307] client: found peer: 1455009845488.1582.fZwK3w==
,2016-02-09 10:30:38.498 ThaliTest[1052:1726307] multipeer session: restart
,2016-02-09 10:30:38.518 ThaliTest[1052:1726307] client: found peer: 1455009845488.1582.fZwK3w==
,2016-02-09 10:31:08.499 ThaliTest[1052:1726307] multipeer session: restart
,2016-02-09 10:31:08.519 ThaliTest[1052:1726307] client: found peer: 1455009845488.1582.fZwK3w==
,2016-02-09 10:31:38.499 ThaliTest[1052:1726307] multipeer session: restart
,2016-02-09 10:31:38.521 ThaliTest[1052:1726307] client: found peer: 1455009845488.1582.fZwK3w==
,2016-02-09 10:32:08.499 ThaliTest[1052:1726307] multipeer session: restart
,2016-02-09 10:32:08.518 ThaliTest[1052:1726307] client: found peer: 1455009845488.1582.fZwK3w==
,2016-02-09 10:32:38.499 ThaliTest[1052:1726307] multipeer session: restart
,2016-02-09 10:32:38.520 ThaliTest[1052:1726307] client: found peer: 1455009845488.1582.fZwK3w==
,2016-02-09 10:33:08.499 ThaliTest[1052:1726307] multipeer session: restart
,2016-02-09 10:33:08.519 ThaliTest[1052:1726307] client: found peer: 1455009845488.1582.fZwK3w==
,2016-02-09 10:33:38.499 ThaliTest[1052:1726307] multipeer session: restart
,2016-02-09 10:33:38.520 ThaliTest[1052:1726307] client: found peer: 1455009845488.1582.fZwK3w==
,2016-02-09 10:34:08.499 ThaliTest[1052:1726307] multipeer session: restart
,2016-02-09 10:34:08.520 ThaliTest[1052:1726307] client: found peer: 1455009845488.1582.fZwK3w==
,2016-02-09 10:34:38.499 ThaliTest[1052:1726307] multipeer session: restart
,2016-02-09 10:35:08.499 ThaliTest[1052:1726307] multipeer session: restart
,2016-02-09 10:35:08.517 ThaliTest[1052:1726307] client: found peer: 1455009845488.1582.fZwK3w==
,2016-02-09 10:35:38.499 ThaliTest[1052:1726307] multipeer session: restart
,2016-02-09 10:36:08.499 ThaliTest[1052:1726307] multipeer session: restart
,2016-02-09 10:36:08.518 ThaliTest[1052:1726307] client: found peer: 1455009845488.1582.fZwK3w==
,2016-02-09 10:36:38.499 ThaliTest[1052:1726307] multipeer session: restart
,2016-02-09 10:36:39.207 ThaliTest[1052:1726307] client: found peer: 1455009845488.1582.fZwK3w==

```
