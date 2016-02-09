#### Test 583805004251330_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/583805004251330/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/BCB3E1DA-026A-4BA4-9D5B-BD4FD67053B9/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/BCB3E1DA-026A-4BA4-9D5B-BD4FD67053B9/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/583805004251330/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/583805004251330/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/018034E5-F061-4FA5-9907-112B2E7DE878/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53574"
,(lldb)     command script import "/tmp/BCB3E1DA-026A-4BA4-9D5B-BD4FD67053B9/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-09 17:05:11.671 ThaliTest[1679:2984168] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/063FF753-781F-4A08-90F0-7049919962D2/Library/Cookies/Cookies.binarycookies
,2016-02-09 17:05:12.095 ThaliTest[1679:2984168] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-09 17:05:12.097 ThaliTest[1679:2984168] Multi-tasking -> Device: YES, App: YES
,2016-02-09 17:05:12.108 ThaliTest[1679:2984168] Unlimited access to network resources
,2016-02-09 17:05:12.120 ThaliTest[1679:2984168] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-09 17:05:22.446 ThaliTest[1679:2984168] Resetting plugins due to page load.
,2016-02-09 17:05:25.802 ThaliTest[1679:2984168] Finished load of: file:///var/mobile/Containers/Bundle/Application/018034E5-F061-4FA5-9907-112B2E7DE878/ThaliTest.app/www/index.html
,2016-02-09 17:05:25.980 ThaliTest[1679:2984168] JXcore Cordova plugin initializing
,2016-02-09 17:05:25.984 ThaliTest[1679:2984512] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/018034E5-F061-4FA5-9907-112B2E7DE878/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/018034E5-F061-4FA5-9907-112B2E7DE878/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/018034E5-F061-4FA5-9907-112B2E7DE878/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/018034E5-F061-4FA5-9907-112B2E7DE878/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/018034E5-F061-4FA5-9907-112B2E7DE878/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/018034E5-F061-4FA5-9907-112B2E7DE878/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/018034E5-F061-4FA5-9907-112B2E7DE878/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/018034E5-F061-4FA5-9907-112B2E7DE878/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/018034E5-F061-4FA5-9907-112B2E7DE878/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/018034E5-F061-4FA5-9907-112B2E7DE878/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

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

,ok 20 should not throw

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

,2016-02-09 17:09:49.530 ThaliTest[1679:2984512] jxcore: startBroadcasting
,2016-02-09 17:09:49.547 ThaliTest[1679:2984512] server: starting 1455034189530.1679.JyaKwA==
,2016-02-09 17:09:49.548 ThaliTest[1679:2984512] multipeer session: start timer: 0x17af60b0
,2016-02-09 17:09:49.549 ThaliTest[1679:2984512] THEMultipeerSession initialized peer 1455034189530.1679
2016-02-09 17:09:49.550 ThaliTest[1679:2984512] jxcore: startBroadcasting: success
ok 63 Should be able to call startBroadcasting without error

,2016-02-09 17:09:49.552 ThaliTest[1679:2984512] jxcore: stopBroadcasting
2016-02-09 17:09:49.554 ThaliTest[1679:2984512] THEMultipeerSession stopping peer
2016-02-09 17:09:49.554 ThaliTest[1679:2984512] multipeer session: stop timer
2016-02-09 17:09:49.,554 ThaliTest[1679:2984512] jxcore: stopBroadcasting: success
ok 64 Should be able to call stopBroadcasting without error

,2016-02-09 17:09:49.557 ThaliTest[1679:2984512] jxcore: startBroadcasting
,2016-02-09 17:09:49.562 ThaliTest[1679:2984512] server: starting 1455034189556.1679.MxtP+A==
2016-02-09 17:09:49.562 ThaliTest[1679:2984512] multipeer session: start timer: 0x17af60b0
2016-02-09 17:09:49.563 ThaliTest[1679:2984512] THEMultipeerSession in,itialized peer 1455034189556.1679
2016-02-09 17:09:49.563 ThaliTest[1679:2984512] jxcore: startBroadcasting: success
ok 65 Should be able to call startBroadcasting without error

2016-02-09 17:09:49.565 ThaliTest[1679:2984512] jxcore: stopBroadcasting,
2016-02-09 17:09:49.565 ThaliTest[1679:2984512] THEMultipeerSession stopping peer
2016-02-09 17:09:49.565 ThaliTest[1679:2984512] multipeer session: stop timer
2016-02-09 17:09:49.566 ThaliTest[1679:2984512] jxcore: stopBroadcasting: success
ok 66 Shou,ld be able to call stopBroadcasting without error

2016-02-09 17:09:49.567 ThaliTest[1679:2984512] jxcore: startBroadcasting
2016-02-09 17:09:49.576 ThaliTest[1679:2984512] server: starting 1455034189567.1679.Z7d9KQ==
2016-02-09 17:09:49.577 ThaliTest[,1679:2984512] multipeer session: start timer: 0x17af90f0
,2016-02-09 17:09:49.590 ThaliTest[1679:2984512] THEMultipeerSession initialized peer 1455034189567.1679
,2016-02-09 17:09:49.596 ThaliTest[1679:2984512] jxcore: startBroadcasting: success
,ok 67 Should be able to call startBroadcasting without error

,2016-02-09 17:09:49.607 ThaliTest[1679:2984512] jxcore: stopBroadcasting
,2016-02-09 17:09:49.607 ThaliTest[1679:2984512] THEMultipeerSession stopping peer
,2016-02-09 17:09:49.609 ThaliTest[1679:2984512] multipeer session: stop timer
,2016-02-09 17:09:49.612 ThaliTest[1679:2984512] jxcore: stopBroadcasting: success
,ok 68 Should be able to call stopBroadcasting without error

,2016-02-09 17:09:49.619 ThaliTest[1679:2984512] jxcore: startBroadcasting
,2016-02-09 17:09:49.622 ThaliTest[1679:2984512] server: starting 1455034189618.1679.6xU0kQ==
,2016-02-09 17:09:49.624 ThaliTest[1679:2984512] multipeer session: start timer: 0x17afacb0
,2016-02-09 17:09:49.632 ThaliTest[1679:2984512] THEMultipeerSession initialized peer 1455034189618.1679
,2016-02-09 17:09:49.634 ThaliTest[1679:2984512] jxcore: startBroadcasting: success
,ok 69 Should be able to call startBroadcasting without error

,2016-02-09 17:09:49.637 ThaliTest[1679:2984512] jxcore: stopBroadcasting
,2016-02-09 17:09:49.639 ThaliTest[1679:2984512] THEMultipeerSession stopping peer
,2016-02-09 17:09:49.640 ThaliTest[1679:2984512] multipeer session: stop timer
,2016-02-09 17:09:49.642 ThaliTest[1679:2984512] jxcore: stopBroadcasting: success
,ok 70 Should be able to call stopBroadcasting without error

,2016-02-09 17:09:49.649 ThaliTest[1679:2984512] jxcore: startBroadcasting
,2016-02-09 17:09:49.651 ThaliTest[1679:2984512] server: starting 1455034189648.1679.Uo3Erw==
,2016-02-09 17:09:49.654 ThaliTest[1679:2984512] multipeer session: start timer: 0x16b59740
,2016-02-09 17:09:49.659 ThaliTest[1679:2984512] THEMultipeerSession initialized peer 1455034189648.1679
,2016-02-09 17:09:49.660 ThaliTest[1679:2984512] jxcore: startBroadcasting: success
,ok 71 Should be able to call startBroadcasting without error

,2016-02-09 17:09:49.662 ThaliTest[1679:2984512] jxcore: stopBroadcasting
,2016-02-09 17:09:49.662 ThaliTest[1679:2984512] THEMultipeerSession stopping peer
,2016-02-09 17:09:49.663 ThaliTest[1679:2984512] multipeer session: stop timer
,2016-02-09 17:09:49.666 ThaliTest[1679:2984512] jxcore: stopBroadcasting: success
,ok 72 Should be able to call stopBroadcasting without error

,2016-02-09 17:09:49.669 ThaliTest[1679:2984512] jxcore: startBroadcasting
,2016-02-09 17:09:49.671 ThaliTest[1679:2984512] server: starting 1455034189668.1679.4tfrRA==
,2016-02-09 17:09:49.674 ThaliTest[1679:2984512] multipeer session: start timer: 0x16bf36a0
,2016-02-09 17:09:49.678 ThaliTest[1679:2984512] THEMultipeerSession initialized peer 1455034189668.1679
,2016-02-09 17:09:49.681 ThaliTest[1679:2984512] jxcore: startBroadcasting: success
,ok 73 Should be able to call startBroadcasting without error

,2016-02-09 17:09:49.683 ThaliTest[1679:2984512] jxcore: stopBroadcasting
,2016-02-09 17:09:49.684 ThaliTest[1679:2984512] THEMultipeerSession stopping peer
,2016-02-09 17:09:49.684 ThaliTest[1679:2984512] multipeer session: stop timer
,2016-02-09 17:09:49.687 ThaliTest[1679:2984512] jxcore: stopBroadcasting: success
,ok 74 Should be able to call stopBroadcasting without error

,2016-02-09 17:09:49.691 ThaliTest[1679:2984512] jxcore: startBroadcasting
,2016-02-09 17:09:49.694 ThaliTest[1679:2984512] server: starting 1455034189691.1679.Usjeyg==
,2016-02-09 17:09:49.697 ThaliTest[1679:2984512] multipeer session: start timer: 0x16cb9f80
,2016-02-09 17:09:49.702 ThaliTest[1679:2984512] THEMultipeerSession initialized peer 1455034189691.1679
,2016-02-09 17:09:49.703 ThaliTest[1679:2984512] jxcore: startBroadcasting: success
,ok 75 Should be able to call startBroadcasting without error

,2016-02-09 17:09:49.705 ThaliTest[1679:2984512] jxcore: stopBroadcasting
,2016-02-09 17:09:49.706 ThaliTest[1679:2984512] THEMultipeerSession stopping peer
,2016-02-09 17:09:49.707 ThaliTest[1679:2984512] multipeer session: stop timer
,2016-02-09 17:09:49.708 ThaliTest[1679:2984512] jxcore: stopBroadcasting: success
,ok 76 Should be able to call stopBroadcasting without error

,2016-02-09 17:09:49.713 ThaliTest[1679:2984512] jxcore: startBroadcasting
,2016-02-09 17:09:49.716 ThaliTest[1679:2984512] server: starting 1455034189713.1679.jCZkxQ==
,2016-02-09 17:09:49.718 ThaliTest[1679:2984512] multipeer session: start timer: 0x16cba6f0
,2016-02-09 17:09:49.720 ThaliTest[1679:2984512] THEMultipeerSession initialized peer 1455034189713.1679
,2016-02-09 17:09:49.723 ThaliTest[1679:2984512] jxcore: startBroadcasting: success
,ok 77 Should be able to call startBroadcasting without error

,2016-02-09 17:09:49.726 ThaliTest[1679:2984512] jxcore: stopBroadcasting
,2016-02-09 17:09:49.726 ThaliTest[1679:2984512] THEMultipeerSession stopping peer
,2016-02-09 17:09:49.728 ThaliTest[1679:2984512] multipeer session: stop timer
,2016-02-09 17:09:49.731 ThaliTest[1679:2984512] jxcore: stopBroadcasting: success
,ok 78 Should be able to call stopBroadcasting without error

,2016-02-09 17:09:49.735 ThaliTest[1679:2984512] jxcore: startBroadcasting
,2016-02-09 17:09:49.737 ThaliTest[1679:2984512] server: starting 1455034189734.1679.Q+jeKQ==
,2016-02-09 17:09:49.738 ThaliTest[1679:2984512] multipeer session: start timer: 0x17afb8e0
,2016-02-09 17:09:49.740 ThaliTest[1679:2984512] THEMultipeerSession initialized peer 1455034189734.1679
,2016-02-09 17:09:49.742 ThaliTest[1679:2984512] jxcore: startBroadcasting: success
,ok 79 Should be able to call startBroadcasting without error

,2016-02-09 17:09:49.746 ThaliTest[1679:2984512] jxcore: stopBroadcasting
,2016-02-09 17:09:49.747 ThaliTest[1679:2984512] THEMultipeerSession stopping peer
,2016-02-09 17:09:49.747 ThaliTest[1679:2984512] multipeer session: stop timer
,2016-02-09 17:09:49.748 ThaliTest[1679:2984512] jxcore: stopBroadcasting: success
,ok 80 Should be able to call stopBroadcasting without error

,2016-02-09 17:09:49.752 ThaliTest[1679:2984512] jxcore: startBroadcasting
,2016-02-09 17:09:49.754 ThaliTest[1679:2984512] server: starting 1455034189752.1679.zmvkjA==
,2016-02-09 17:09:49.755 ThaliTest[1679:2984512] multipeer session: start timer: 0x16cba5d0
,2016-02-09 17:09:49.756 ThaliTest[1679:2984512] THEMultipeerSession initialized peer 1455034189752.1679
,2016-02-09 17:09:49.758 ThaliTest[1679:2984512] jxcore: startBroadcasting: success
,ok 81 Should be able to call startBroadcasting without error

,2016-02-09 17:09:49.762 ThaliTest[1679:2984512] jxcore: stopBroadcasting
,2016-02-09 17:09:49.762 ThaliTest[1679:2984512] THEMultipeerSession stopping peer
,2016-02-09 17:09:49.763 ThaliTest[1679:2984512] multipeer session: stop timer
,2016-02-09 17:09:49.764 ThaliTest[1679:2984512] jxcore: stopBroadcasting: success
,ok 82 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,# teardown

,2016-02-09 17:09:50.335 ThaliTest[1679:2984512] jxcore: startBroadcasting
,2016-02-09 17:09:50.339 ThaliTest[1679:2984512] server: starting 1455034190335.1679.pQ38fQ==
2016-02-09 17:09:50.339 ThaliTest[1679:2984512] multipeer session: start timer: 0x16c05ce0
2016-02-09 17:09:50.340 ThaliTest[1679:2984512] THEMultipeerSession in,itialized peer 1455034190335.1679
2016-02-09 17:09:50.340 ThaliTest[1679:2984512] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error

2016-02-09 17:09:50.342 ThaliTest[1679:2984512] jxcore: startBroadcasting
2016-02-09 17:09:50.343 ThaliTest[1679:2984512] jxcore: startBroadcasting: failure
,ok 84 Cannot call startBroadcasting twice

,2016-02-09 17:09:50.357 ThaliTest[1679:2984512] jxcore: stopBroadcasting
,2016-02-09 17:09:50.358 ThaliTest[1679:2984512] THEMultipeerSession stopping peer
,2016-02-09 17:09:50.359 ThaliTest[1679:2984512] multipeer session: stop timer
,2016-02-09 17:09:50.364 ThaliTest[1679:2984512] jxcore: stopBroadcasting: success
,ok 85 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on connection to bad peer

,# teardown

,2016-02-09 17:09:50.490 ThaliTest[1679:2984512] jxcore: startBroadcasting
,2016-02-09 17:09:50.493 ThaliTest[1679:2984512] server: starting 1455034190489.1679.OqMnhw==
2016-02-09 17:09:50.494 ThaliTest[1679:2984512] multipeer session: start timer: 0x17e070c0
2016-02-09 17:09:50.494 ThaliTest[1679:2984512] THEMultipeerSession in,itialized peer 1455034190489.1679
2016-02-09 17:09:50.495 ThaliTest[1679:2984512] jxcore: startBroadcasting: success
ok 86 Should be able to call startBroadcasting without error

,2016-02-09 17:09:50.497 ThaliTest[1679:2984512] jxcore: connect foobar
2016-02-09 17:09:50.498 ThaliTest[1679:2984512] client: unknown peer foobar
,2016-02-09 17:09:50.499 ThaliTest[1679:2984512] jxcore: connect: fail: Unknown peer
,ok 87 Should not connect to a bad peer

2016-02-09 17:09:50.503 ThaliTest[1679:2984512] jxcore: stopBroadcasting
2016-02-09 17:09:50.503 ThaliTest[1679:2984512] THEMultipeerSession stopping peer
,2016-02-09 17:09:50.503 ThaliTest[1679:2984512] multipeer session: stop timer
2016-02-09 17:09:50.505 ThaliTest[1679:2984512] jxcore: stopBroadcasting: success
ok 88 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on disconnect to bad peer

,# teardown

,2016-02-09 17:09:51.436 ThaliTest[1679:2984512] jxcore: startBroadcasting
,2016-02-09 17:09:51.439 ThaliTest[1679:2984512] server: starting 1455034191435.1679.cT1OMQ==
2016-02-09 17:09:51.440 ThaliTest[1679:2984512] multipeer session: start timer: 0x17e0aa80
2016-02-09 17:09:51.440 ThaliTest[1679:2984512] THEMultipeerSession in,itialized peer 1455034191435.1679
2016-02-09 17:09:51.441 ThaliTest[1679:2984512] jxcore: startBroadcasting: success
ok 89 Should be able to call startBroadcasting without error

2016-02-09 17:09:51.443 ThaliTest[1679:2984512] jxcore: disconnect
2016-,02-09 17:09:51.443 ThaliTest[1679:2984512] jxcore: disconnect: fail
ok 90 Disconnect should fail to a non-existant peer 

,2016-02-09 17:09:51.446 ThaliTest[1679:2984512] jxcore: stopBroadcasting
2016-02-09 17:09:51.447 ThaliTest[1679:2984512] THEMultipeerSession stopping peer
2016-02-09 17:09:51.447 ThaliTest[1679:2984512] multipeer session: stop timer
,2016-02-09 17:09:51.448 ThaliTest[1679:2984512] jxcore: stopBroadcasting: success
,ok 91 Should be able to call stopBroadcasting without error

# setup

,# ThaliEmitter can discover and connect to peers

,# teardown

,2016-02-09 17:09:52.601 ThaliTest[1679:2984512] jxcore: startBroadcasting
,2016-02-09 17:09:52.605 ThaliTest[1679:2984512] server: starting 1455034192601.1679.6iRk8g==
,2016-02-09 17:09:52.606 ThaliTest[1679:2984512] multipeer session: start timer: 0x17e0e3e0
,2016-02-09 17:09:52.607 ThaliTest[1679:2984512] THEMultipeerSession initialized peer 1455034192601.1679
,2016-02-09 17:09:52.608 ThaliTest[1679:2984512] jxcore: startBroadcasting: success
ok 92 Should be able to call startBroadcasting without error

,2016-02-09 17:09:53.925 ThaliTest[1679:2984168] multipeer session: reset timer
2016-02-09 17:09:53.925 ThaliTest[1679:2984168] multipeer session: stop timer
2016-02-09 17:09:53.925 ThaliTest[1679:2984168] multipeer session: start timer: 0x17e0e3e0
2016-,02-09 17:09:53.926 ThaliTest[1679:2984168] server session: connect
2016-02-09 17:09:53.926 ThaliTest[1679:2984168] server session: stateChange:0->1 1455034194626.1146
2016-02-09 17:09:53.934 ThaliTest[1679:2984168] server: accepting invitation 1455034194,626.1146
,2016-02-09 17:09:54.267 ThaliTest[1679:2984168] client: found peer: 1455034194626.1146.c45i5A==
2016-02-09 17:09:54.270 ThaliTest[1679:2984512] jxcore: connect 1455034194626.1146.c45i5A==
,2016-02-09 17:09:54.270 ThaliTest[1679:2984512] client session: connect
,2016-02-09 17:09:54.274 ThaliTest[1679:2984512] client session: stateChange:0->1 1455034194626.1146.c45i5A==
,2016-02-09 17:09:56.445 ThaliTest[1679:2984966] server session: connected
2016-02-09 17:09:56.446 ThaliTest[1679:2984966] server session: stateChange:1->2 1455034194626.1146
,2016-02-09 17:09:56.469 ThaliTest[1679:2984168] server relay: socket disconnected
2016-02-09 17:09:56.469 ThaliTest[1679:2984168] server relay: 0x15651f30 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-09 17:09:56.496 ThaliTest[1679:2984959] server session: not connected 1455034194626.1146
,2016-02-09 17:09:56.840 ThaliTest[1679:2984959] client session: connected
2016-02-09 17:09:56.840 ThaliTest[1679:2984959] client session: stateChange:1->2 1455034194626.1146.c45i5A==
,2016-02-09 17:09:56.864 ThaliTest[1679:2984964] client session: fireConnectCallback: 1455034194626.1146.c45i5A==
,2016-02-09 17:09:56.864 ThaliTest[1679:2984964] jxcore: connect: success
ok 93 Should be able to connect without error

,ok 94 Port should be within range

,2016-02-09 17:09:56.871 ThaliTest[1679:2984512] jxcore: disconnect
2016-02-09 17:09:56.871 ThaliTest[1679:2984512] client session: disconnectFromPeer: 1455034194626.1146.c45i5A==
2016-02-09 17:09:56.872 ThaliTest[1679:2984512] client session: disconnect,
2016-02-09 17:09:56.872 ThaliTest[1679:2984512] client session: stateChange:2->0 1455034194626.1146.c45i5A==
,2016-02-09 17:09:56.883 ThaliTest[1679:2984512] jxcore: disconnect: success
ok 95 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-02-09 17:09:57.280 ThaliTest[1679:2984512] jxcore: stopBroadcasting
2016-02-09 17:09:57.280 ThaliTest[1679:2984512] THEMultipeerSession stopping peer
2016-02-09 17:09:57.281 ThaliTest[1679:2984512] multipeer session: stop timer
2016-02-09 17:09:57.,281 ThaliTest[1679:2984512] server session: disconnect
2016-02-09 17:09:57.282 ThaliTest[1679:2984512] server session: stateChange:2->0 1455034194626.1146
2016-02-09 17:09:57.283 ThaliTest[1679:2984512] jxcore: stopBroadcasting: success
stopBroadcasting, returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double connect

,# teardown

,2016-02-09 17:09:57.797 ThaliTest[1679:2984512] jxcore: startBroadcasting
,2016-02-09 17:09:57.801 ThaliTest[1679:2984512] server: starting 1455034197797.1679.+BHUCA==
2016-02-09 17:09:57.801 ThaliTest[1679:2984512] multipeer session: start timer: 0x17e135f0
2016-02-09 17:09:57.802 ThaliTest[1679:2984512] THEMultipeerSession in,itialized peer 1455034197797.1679
2016-02-09 17:09:57.802 ThaliTest[1679:2984512] jxcore: startBroadcasting: success
ok 96 Should be able to call startBroadcasting without error

,2016-02-09 17:09:58.526 ThaliTest[1679:2984168] client: found peer: 1455034194626.1146.c45i5A==
,2016-02-09 17:09:58.530 ThaliTest[1679:2984512] jxcore: connect 1455034194626.1146.c45i5A==
2016-02-09 17:09:58.530 ThaliTest[1679:2984512] client session: connect
2016-02-09 17:09:58.531 ThaliTest[1679:2984512] client session: stateChange:0->1 1455034194626.1146.c45i5A==
,2016-02-09 17:09:58.964 ThaliTest[1679:2984168] client: found peer: 1455034199495.1146.2BDUpA==
2016-02-09 17:09:58.965 ThaliTest[1679:2984512] jxcore: connect 1455034199495.1146.2BDUpA==
2016-02-09 17:09:58.966 ThaliTest[1679:2984512] client session: connect
,2016-02-09 17:09:58.966 ThaliTest[1679:2984512] client session: stateChange:0->1 1455034199495.1146.2BDUpA==
,2016-02-09 17:09:59.053 ThaliTest[1679:2984168] multipeer session: reset timer
2016-02-09 17:09:59.053 ThaliTest[1679:2984168] multipeer session: stop timer
2016-02-09 17:09:59.054 ThaliTest[1679:2984168] multipeer session: start timer: 0x17e135f0
2016-,02-09 17:09:59.054 ThaliTest[1679:2984168] server session: connect
2016-02-09 17:09:59.054 ThaliTest[1679:2984168] server session: stateChange:0->1 1455034199495.1146
,2016-02-09 17:09:59.064 ThaliTest[1679:2984168] server: accepting invitation 1455034199495.1146
,2016-02-09 17:10:01.491 ThaliTest[1679:2984966] client session: connected
2016-02-09 17:10:01.491 ThaliTest[1679:2984966] client session: stateChange:1->2 1455034199495.1146.2BDUpA==
,2016-02-09 17:10:01.494 ThaliTest[1679:2984966] client session: fireConnectCallback: 1455034199495.1146.2BDUpA==
2016-02-09 17:10:01.494 ThaliTest[1679:2984966] jxcore: connect: success
ok 97 Should be able to connect without error

ok 98 Port should be within range

2016-02-09 17:10:01.497 ThaliTest[1679:2984512] jxcore: connect 1455034199495.1146.2BDUpA==
2016-02-09 17:10:01.497 ThaliTest[1679:2984512] client: already connect(ing/ed) to 1455034199495.1146.2BDUpA==
2016-02-09 17:10:01.497 ThaliTest[1679:2984512] jxcore: connect: fail: Aleady connecting
ok 99 Should fail on double connect

,2016-02-09 17:10:01.502 ThaliTest[1679:2984512] jxcore: disconnect
2016-02-09 17:10:01.503 ThaliTest[1679:2984512] client session: disconnectFromPeer: 1455034199495.1146.2BDUpA==
2016-02-09 17:10:01.503 ThaliTest[1679:2984512] client session: disconnect,
2016-02-09 17:10:01.503 ThaliTest[1679:2984512] client session: stateChange:2->0 1455034199495.1146.2BDUpA==
,2016-02-09 17:10:01.514 ThaliTest[1679:2984963] server session: connected
,2016-02-09 17:10:01.514 ThaliTest[1679:2984963] server session: stateChange:1->2 1455034199495.1146
,2016-02-09 17:10:01.519 ThaliTest[1679:2984168] server relay: socket disconnected
,2016-02-09 17:10:01.520 ThaliTest[1679:2984168] server relay: 0x16d37870 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-09 17:10:01.590 ThaliTest[1679:2984512] jxcore: disconnect: success
ok 100 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,2016-02-09 17:10:01.613 ThaliTest[1679:2984963] server session: not connected 1455034199495.1146
,calling stopBroadcasting

,2016-02-09 17:10:01.996 ThaliTest[1679:2984512] jxcore: stopBroadcasting
2016-02-09 17:10:01.996 ThaliTest[1679:2984512] THEMultipeerSession stopping peer
2016-02-09 17:10:01.997 ThaliTest[1679:2984512] multipeer session: stop timer
2016-02-09 17:10:01.,997 ThaliTest[1679:2984512] client session: disconnect
2016-02-09 17:10:01.997 ThaliTest[1679:2984512] client session: stateChange:1->0 1455034194626.1146.c45i5A==
2016-02-09 17:10:01.998 ThaliTest[1679:2984512] server session: disconnect
2016-02-09 17:,10:01.999 ThaliTest[1679:2984512] server session: stateChange:2->0 1455034199495.1146
2016-02-09 17:10:01.999 ThaliTest[1679:2984512] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,# teardown

,2016-02-09 17:10:02.518 ThaliTest[1679:2984512] jxcore: startBroadcasting
,2016-02-09 17:10:02.522 ThaliTest[1679:2984512] server: starting 1455034202518.1679.ZGlmpQ==
2016-02-09 17:10:02.523 ThaliTest[1679:2984512] multipeer session: start timer: 0x17e18270
2016-02-09 17:10:02.524 ThaliTest[1679:2984512] THEMultipeerSession initialized peer 1455034202518.1679
2016-02-09 17:10:02.524 ThaliTest[1679:2984512] jxcore: startBroadcasting: success
ok 101 Should be able to call startBroadcasting without error

,2016-02-09 17:10:03.267 ThaliTest[1679:2984168] client: found peer: 1455034199495.1146.2BDUpA==
2016-02-09 17:10:03.268 ThaliTest[1679:2984512] jxcore: connect 1455034199495.1146.2BDUpA==
2016-02-09 17:10:03.268 ThaliTest[1679:2984512] client session: co,nnect
2016-02-09 17:10:03.269 ThaliTest[1679:2984512] client session: stateChange:0->1 1455034199495.1146.2BDUpA==
,2016-02-09 17:10:04.868 ThaliTest[1679:2984168] client: found peer: 1455034204212.1146.ULzrQg==
2016-02-09 17:10:04.870 ThaliTest[1679:2984512] jxcore: connect 1455034204212.1146.ULzrQg==
2016-02-09 17:10:04.870 ThaliTest[1679:2984512] client session: co,nnect
2016-02-09 17:10:04.870 ThaliTest[1679:2984512] client session: stateChange:0->1 1455034204212.1146.ULzrQg==
,2016-02-09 17:10:04.888 ThaliTest[1679:2984168] multipeer session: reset timer
,2016-02-09 17:10:04.889 ThaliTest[1679:2984168] multipeer session: stop timer
,2016-02-09 17:10:04.890 ThaliTest[1679:2984168] multipeer session: start timer: 0x17e18270
,2016-02-09 17:10:04.890 ThaliTest[1679:2984168] server session: connect
2016-02-09 17:10:04.891 ThaliTest[1679:2984168] server session: stateChange:0->1 1455034204212.1146
,2016-02-09 17:10:04.903 ThaliTest[1679:2984168] server: accepting invitation 1455034204212.1146
,2016-02-09 17:10:07.499 ThaliTest[1679:2984961] server session: connected
2016-02-09 17:10:07.499 ThaliTest[1679:2984961] server session: stateChange:1->2 1455034204212.1146
,2016-02-09 17:10:07.510 ThaliTest[1679:2984168] server relay: socket disconnected
2016-02-09 17:10:07.510 ThaliTest[1679:2984168] server relay: 0x16e29d80 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-09 17:10:07.560 ThaliTest[1679:2984961] server session: not connected 1455034204212.1146
,2016-02-09 17:10:10.036 ThaliTest[1679:2984961] client session: connected
2016-02-09 17:10:10.036 ThaliTest[1679:2984961] client session: stateChange:1->2 1455034204212.1146.ULzrQg==
,2016-02-09 17:10:10.153 ThaliTest[1679:2984959] client session: fireConnectCallback: 1455034204212.1146.ULzrQg==
2016-02-09 17:10:10.153 ThaliTest[1679:2984959] jxcore: connect: success
ok 102 Should be able to connect without error

ok 103 Port should, be within range

2016-02-09 17:10:10.157 ThaliTest[1679:2984512] jxcore: disconnect
2016-02-09 17:10:10.158 ThaliTest[1679:2984512] client session: disconnectFromPeer: 1455034204212.1146.ULzrQg==
2016-02-09 17:10:10.158 ThaliTest[1679:2984512] client ,session: disconnect
2016-02-09 17:10:10.158 ThaliTest[1679:2984512] client session: stateChange:2->0 1455034204212.1146.ULzrQg==
,2016-02-09 17:10:10.243 ThaliTest[1679:2984512] jxcore: disconnect: success
ok 104 Should be able to disconnect without error

,2016-02-09 17:10:10.245 ThaliTest[1679:2984512] jxcore: disconnect
2016-02-09 17:10:10.246 ThaliTest[1679:2984512] jxcore: disconnect: fail
,ok 105 Disconnect should fail 

,setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-02-09 17:10:10.286 ThaliTest[1679:2984512] jxcore: stopBroadcasting
2016-02-09 17:10:10.287 ThaliTest[1679:2984512] THEMultipeerSession stopping peer
2016-02-09 17:10:10.287 ThaliTest[1679:2984512] multipeer session: stop timer
2016-02-09 17:10:10.,287 ThaliTest[1679:2984512] client session: disconnect
2016-02-09 17:10:10.288 ThaliTest[1679:2984512] client session: stateChange:1->0 1455034199495.1146.2BDUpA==
2016-02-09 17:10:10.288 ThaliTest[1679:2984512] server session: disconnect
2016-02-09 17:,10:10.289 ThaliTest[1679:2984512] server session: stateChange:2->0 1455034204212.1146
2016-02-09 17:10:10.290 ThaliTest[1679:2984512] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter can connect and send data

,# teardown

,echo server started on port: 60566

,2016-02-09 17:10:12.406 ThaliTest[1679:2984512] jxcore: startBroadcasting
,2016-02-09 17:10:12.408 ThaliTest[1679:2984512] server: starting 1455034212406.1679.OOTR4g==
2016-02-09 17:10:12.408 ThaliTest[1679:2984512] multipeer session: start timer: 0x17a65b70
2016-02-09 17:10:12.408 ThaliTest[1679:2984512] THEMultipeerSession in,itialized peer 1455034212406.1679
2016-02-09 17:10:12.408 ThaliTest[1679:2984512] jxcore: startBroadcasting: success
ok 106 Should be able to call startBroadcasting without error

,2016-02-09 17:10:13.662 ThaliTest[1679:2984168] client: found peer: 1455034214042.1146.fCKSEg==
2016-02-09 17:10:13.664 ThaliTest[1679:2984512] jxcore: connect 1455034214042.1146.fCKSEg==
2016-02-09 17:10:13.664 ThaliTest[1679:2984512] client session: co,nnect
2016-02-09 17:10:13.665 ThaliTest[1679:2984512] client session: stateChange:0->1 1455034214042.1146.fCKSEg==
,2016-02-09 17:10:14.118 ThaliTest[1679:2984168] multipeer session: reset timer
2016-02-09 17:10:14.119 ThaliTest[1679:2984168] multipeer session: stop timer
2016-02-09 17:10:14.120 ThaliTest[1679:2984168] multipeer session: start timer: 0x17a65b70
2016-02-09 17:10:14.120 ThaliTest[1679:2984168] server session: connect
,2016-02-09 17:10:14.122 ThaliTest[1679:2984168] server session: stateChange:0->1 1455034214042.1146
,2016-02-09 17:10:14.133 ThaliTest[1679:2984168] server: accepting invitation 1455034214042.1146
,2016-02-09 17:10:16.269 ThaliTest[1679:2984964] server session: connected
2016-02-09 17:10:16.269 ThaliTest[1679:2984964] server session: stateChange:1->2 1455034214042.1146
,2016-02-09 17:10:16.554 ThaliTest[1679:2985089] client session: connected
2016-02-09 17:10:16.554 ThaliTest[1679:2985089] client session: stateChange:1->2 1455034214042.1146.fCKSEg==
,2016-02-09 17:10:16.850 ThaliTest[1679:2984168] server relay: connected (to port: 60566)
,2016-02-09 17:10:17.359 ThaliTest[1679:2985089] client session: fireConnectCallback: 1455034214042.1146.fCKSEg==
2016-02-09 17:10:17.360 ThaliTest[1679:2985089] jxcore: connect: success
ok 107 Should be able to connect without error

,ok 108 Port should be within range

,2016-02-09 17:10:17.367 ThaliTest[1679:2984168] client: relay established
2016-02-09 17:10:17.367 ThaliTest[1679:2984168] client: new accepted socket: 0x17a07530
,data in 1095

,data in 2190

,data in 3285

,data in 4380

,data in 5475

,data in 6570

,data in 7665

,data in 8760

,data in 9855

,data in 10950

,data in 12045

,data in 13140

,data in 14235

,data in 15330

,data in 18615

,data in 19710

,data in 20805

,2016-02-09 17:10:44.121 ThaliTest[1679:2984168] multipeer session: restart
,2016-02-09 17:10:44.157 ThaliTest[1679:2984168] client: found peer: 1455034214042.1146.fCKSEg==
,data in 26280

,data in 29565

,data in 45949

,data in 48180

,2016-02-09 17:11:14.121 ThaliTest[1679:2984168] multipeer session: restart
,data in 49275

,data in 77745

,data in 78840

,data in 79935

,data in 81030

,data in 82125

,data in 83220

,data in 84315

,data in 85410

,data in 86505

,data in 87600

,data in 89790

,data in 90885

,data in 91980

,data in 93075

,data in 94170

,data in 95265

,data in 96360

,data in 97455

,data in 98550

,data in 99645

,data in 100740

,data in 101835

,data in 102930

,data in 104025

,data in 105120

,data in 106215

,data in 107310

,data in 108405

,data in 109500

,data in 110595

,data in 111690

,data in 112785

,data in 113880

,data in 114975

,data in 116070

,data in 117165

,data in 118260

,data in 119355

,data in 120450

,data in 121545

,data in 122640

,data in 123380

,2016-02-09 17:11:44.121 ThaliTest[1679:2984168] multipeer session: restart
data in 124475

,2016-02-09 17:11:44.153 ThaliTest[1679:2984168] client: found peer: 1455034214042.1146.fCKSEg==
,data in 125570

,data in 126665

,data in 127760

,data in 128855

,data in 129950

,data in 131045

,data in 131072

,ok 109 the test messages should be equal

,2016-02-09 17:11:45.648 ThaliTest[1679:2984512] jxcore: disconnect
2016-02-09 17:11:45.649 ThaliTest[1679:2984512] client session: disconnectFromPeer: 1455034214042.1146.fCKSEg==
2016-02-09 17:11:45.649 ThaliTest[1679:2984512] client session: disconnect,
2016-02-09 17:11:45.649 ThaliTest[1679:2984512] client session: stateChange:2->0 1455034214042.1146.fCKSEg==
2016-02-09 17:11:45.655 ThaliTest[1679:2984512] jxcore: disconnect: success
ok 110 Should be able to disconnect without error

setting stopBro,adcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-02-09 17:11:45.702 ThaliTest[1679:2984512] jxcore: stopBroadcasting
2016-02-09 17:11:45.703 ThaliTest[1679:2984512] THEMultipeerSession stopping peer
2016-02-09 17:11:45.703 ThaliTest[1679:2984512] multipeer session: stop timer
2016-02-09 17:11:45.704 ThaliTest[1679:2984512] server session: disconnect
2016-02-09 17:11:45.704 ThaliTest[1679:2984512] server session: stateChange:2->0 1455034214042.1146
,2016-02-09 17:11:45.733 ThaliTest[1679:2984512] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter handles socket disconnect correctly

,# teardown

,echo server started on port: 60577

,2016-02-09 17:11:45.863 ThaliTest[1679:2984512] jxcore: startBroadcasting
,2016-02-09 17:11:45.868 ThaliTest[1679:2984512] server: starting 1455034305863.1679.uEOCMQ==
2016-02-09 17:11:45.869 ThaliTest[1679:2984512] multipeer session: start timer: 0x16ee6c00
2016-02-09 17:11:45.869 ThaliTest[1679:2984512] THEMultipeerSession in,itialized peer 1455034305863.1679
2016-02-09 17:11:45.869 ThaliTest[1679:2984512] jxcore: startBroadcasting: success
ok 111 Should be able to call startBroadcasting without error

,2016-02-09 17:11:46.839 ThaliTest[1679:2984168] client: found peer: 1455034214042.1146.fCKSEg==
[{"peerIdentifier":"1455034214042.1146.fCKSEg==","peerName":"(null)","peerAvailable":true}]

,2016-02-09 17:11:46.843 ThaliTest[1679:2984512] jxcore: connect 1455034214042.1146.fCKSEg==
2016-02-09 17:11:46.844 ThaliTest[1679:2984512] client session: connect
2016-02-09 17:11:46.844 ThaliTest[1679:2984512] client session: stateChange:0->1 1455034214042.1146.fCKSEg==
,2016-02-09 17:11:47.020 ThaliTest[1679:2984168] client: found peer: 1455034307562.1146.BAatuA==
,[{"peerIdentifier":"1455034307562.1146.BAatuA==","peerName":"(null)","peerAvailable":true}]

2016-02-09 17:11:47.024 ThaliTest[1679:2984512] jxcore: connect 1455034307562.1146.BAatuA==
2016-02-09 17:11:47.025 ThaliTest[1679:2984512] client session: conn,ect
2016-02-09 17:11:47.025 ThaliTest[1679:2984512] client session: stateChange:0->1 1455034307562.1146.BAatuA==
,2016-02-09 17:11:47.078 ThaliTest[1679:2984168] multipeer session: reset timer
2016-02-09 17:11:47.079 ThaliTest[1679:2984168] multipeer session: stop timer
2016-02-09 17:11:47.079 ThaliTest[1679:2984168] multipeer session: start timer: 0x16ee6c00
2016-,02-09 17:11:47.079 ThaliTest[1679:2984168] server session: connect
2016-02-09 17:11:47.080 ThaliTest[1679:2984168] server session: stateChange:0->1 1455034307562.1146
,2016-02-09 17:11:47.091 ThaliTest[1679:2984168] server: accepting invitation 1455034307562.1146
,2016-02-09 17:11:49.840 ThaliTest[1679:2985276] server session: connected
2016-02-09 17:11:49.841 ThaliTest[1679:2985276] server session: stateChange:1->2 1455034307562.1146
,2016-02-09 17:11:49.862 ThaliTest[1679:2984168] server relay: connected (to port: 60577)
,2016-02-09 17:11:50.047 ThaliTest[1679:2985276] server session: not connected 1455034307562.1146
,2016-02-09 17:11:50.093 ThaliTest[1679:2984168] multipeer session: reset timer
2016-02-09 17:11:50.093 ThaliTest[1679:2984168] multipeer session: stop timer
2016-02-09 17:11:50.093 ThaliTest[1679:2984168] multipeer session: start timer: 0x16ee6c00
2016-,02-09 17:11:50.094 ThaliTest[1679:2984168] server: disconnecting to refresh session (1455034307562.1146)
2016-02-09 17:11:50.094 ThaliTest[1679:2984168] server session: disconnect
2016-02-09 17:11:50.095 ThaliTest[1679:2984168] server session: stateChang,e:2->0 1455034307562.1146
,2016-02-09 17:11:50.160 ThaliTest[1679:2985090] client session: connected
2016-02-09 17:11:50.161 ThaliTest[1679:2985090] client session: stateChange:1->2 1455034307562.1146.BAatuA==
,2016-02-09 17:11:50.219 ThaliTest[1679:2984168] server session: connect
2016-02-09 17:11:50.219 ThaliTest[1679:2984168] server session: stateChange:0->1 1455034307562.1146
,2016-02-09 17:11:50.227 ThaliTest[1679:2984168] server: accepting invitation 1455034307562.1146
,2016-02-09 17:11:50.423 ThaliTest[1679:2985090] client session: fireConnectCallback: 1455034307562.1146.BAatuA==
2016-02-09 17:11:50.424 ThaliTest[1679:2985090] jxcore: connect: success
ok 112 Should be able to connect without error

ok 113 Port should be within range

ok 114 First connect should succeed

,2016-02-09 17:11:50.458 ThaliTest[1679:2984168] client: relay established
,2016-02-09 17:11:50.459 ThaliTest[1679:2984168] client: new accepted socket: 0x17e1f3c0
,ok 115 the test messages should be equal

,ok 116 First send should succeed

,2016-02-09 17:11:50.509 ThaliTest[1679:2984168] client: socket closed
2016-02-09 17:11:50.509 ThaliTest[1679:2984168] client relay: socket disconnected
2016-02-09 17:11:50.509 ThaliTest[1679:2984168] client relay: 0x17e1f3c0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-02-09 17:11:50.510 ThaliTest[1679:2984168] client session: socket closed: 1455034307562.1146.BAatuA==
2016-02-09 ,17:11:50.510 ThaliTest[1679:2984168] client session: onLinkFailure: 1455034307562.1146.BAatuA==
2016-02-09 17:11:50.510 ThaliTest[1679:2984168] client session: disconnect
2016-02-09 17:11:50.510 ThaliTest[1679:2984168] client session: stateChange:2->0 14,55034307562.1146.BAatuA==
,2016-02-09 17:11:50.521 ThaliTest[1679:2984168] client session: fireConnectionErrorEvent: 1455034307562.1146.BAatuA==
,2016-02-09 17:11:50.524 ThaliTest[1679:2984512] jxcore: connect 1455034307562.1146.BAatuA==
,2016-02-09 17:11:50.524 ThaliTest[1679:2984512] client session: connect
,2016-02-09 17:11:50.526 ThaliTest[1679:2984512] client session: stateChange:0->1 1455034307562.1146.BAatuA==
,2016-02-09 17:11:52.922 ThaliTest[1679:2985090] server session: connected
2016-02-09 17:11:52.923 ThaliTest[1679:2985090] server session: stateChange:1->2 1455034307562.1146
,2016-02-09 17:11:52.928 ThaliTest[1679:2984168] server relay: connected (to port: 60577)
,2016-02-09 17:11:53.115 ThaliTest[1679:2985090] server session: not connected 1455034307562.1146
,2016-02-09 17:11:53.304 ThaliTest[1679:2985090] client session: connected
2016-02-09 17:11:53.305 ThaliTest[1679:2985090] client session: stateChange:1->2 1455034307562.1146.BAatuA==
2016-02-09 17:11:53.308 ThaliTest[1679:2985090] client session: fireCon,nectCallback: 1455034307562.1146.BAatuA==
2016-02-09 17:11:53.308 ThaliTest[1679:2985090] jxcore: connect: success
ok 117 Should be able to connect without error
,
ok 118 Port should be within range

ok 119 Second connect should succeed

,2016-02-09 17:11:53.345 ThaliTest[1679:2984168] client: relay established
2016-02-09 17:11:53.346 ThaliTest[1679:2984168] client: new accepted socket: 0x17c181b0
,ok 120 the test messages should be equal

,ok 121 Second send should succeed

,# setup

,2016-02-09 17:11:53.429 ThaliTest[1679:2984168] client: socket closed
,2016-02-09 17:11:53.430 ThaliTest[1679:2984168] client relay: socket disconnected
,2016-02-09 17:11:53.431 ThaliTest[1679:2984168] client relay: 0x17c181b0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-02-09 17:11:,53.431 ThaliTest[1679:2984168] client session: socket closed: 1455034307562.1146.BAatuA==
2016-02-09 17:11:53.431 ThaliTest[1679:2984168] client session: onLinkFailure: 1455034307562.1146.BAatuA==
,2016-02-09 17:11:53.432 ThaliTest[1679:2984168] client session: disconnect
2016-02-09 17:11:53.432 ThaliTest[1679:2984168] client session: stateChange:2->0 1455034307562.1146.BAatuA==
,2016-02-09 17:11:53.456 ThaliTest[1679:2984168] client session: fireConnectionErrorEvent: 1455034307562.1146.BAatuA==
,calling stopBroadcasting

,2016-02-09 17:11:53.645 ThaliTest[1679:2984512] jxcore: stopBroadcasting
,2016-02-09 17:11:53.647 ThaliTest[1679:2984512] THEMultipeerSession stopping peer
,2016-02-09 17:11:53.649 ThaliTest[1679:2984512] multipeer session: stop timer
,2016-02-09 17:11:53.651 ThaliTest[1679:2984512] client session: disconnect
,2016-02-09 17:11:53.653 ThaliTest[1679:2984512] client session: stateChange:1->0 1455034214042.1146.fCKSEg==
,2016-02-09 17:11:53.671 ThaliTest[1679:2984512] server session: disconnect
,2016-02-09 17:11:53.672 ThaliTest[1679:2984512] server session: stateChange:2->0 1455034307562.1146
,2016-02-09 17:11:53.678 ThaliTest[1679:2984512] jxcore: stopBroadcasting: success
,stopBroadcasting returned undefined
,
,# #generatePreambleAndBeacons null ECDH for local device

,# teardown

,ok 122 ecdhForLocalDevice cannot be null

,# setup

,# #generatePreambleAndBeacons expiration out of range lower

,# teardown

,ok 123 secondsUntilExpiration out of range.

,# setup

,# #generatePreambleAndBeacons expiration out of range upper

,# teardown

,ok 124 secondsUntilExpiration out of range.

,# setup

,# #generatePreambleAndBeacons empty keys to notify

,# teardown

,ok 125 should be equal

,# setup

,# #generatePreambleAndBeacons multiple keys to notify

,# teardown

,ok 126 should be equal

ok 127 should be equal

,ok 128 should be equal

,ok 129 should be equal

,# setup

,# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

,# teardown

,ok 130 should throw

,# setup

,# #parseBeacons invalid expiration in beaconStreamWithPreAmble

,# teardown

,ok 131 Preamble expiration must be a 64 bit integer

,# setup

,# #parseBeacons expiration out of range lower

,# teardown

,ok 132 Expiration out of range

,# setup

,# #parseBeacons no beacons returns null

,# teardown

,ok 133 should be equal

,# setup

,# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

,# teardown

,ok 134 Malformed encrypted beacon key ID

,# setup

,# #parseBeacons addressBookCallback fails decrypt

,# teardown

,ok 135 should be equal

,# setup

,# #parseBeacons addressBookCallback returns no matches

,# teardown

,ok 136 should be equal

ok 137 should be equal

,# setup

,# #parseBeacons addressBookCallback returns public key

,# teardown

,ok 138 should be equal

,ok 139 (unnamed assert)
,
,# setup

,# #parseBeacons with beacons both for and not for the user

,# teardown

,ok 140 (unnamed assert)

,# setup

,# ThaliReplicationManager can call start without error

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/063FF753-781F-4A08-90F0-7049919962D2/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,ok 141 starting event should occur in right order

,2016-02-09 17:11:58.879 ThaliTest[1679:2984512] jxcore: startBroadcasting
,2016-02-09 17:11:58.881 ThaliTest[1679:2984512] server: starting RnFKHRp4q9GiF7vkBKNucA.SmPYhg==
2016-02-09 17:11:58.881 ThaliTest[1679:2984512] multipeer session: start timer: 0x16deaef0
2016-02-09 17:11:58.881 ThaliTest[1679:2984512] THEMultipeerSessio,n initialized peer RnFKHRp4q9GiF7vkBKNucA
2016-02-09 17:11:58.882 ThaliTest[1679:2984512] jxcore: startBroadcasting: success
ok 142 started event should occur in right order

Now in TRM stop

State of this._isStarted: true

,ok 143 stopping event should occur in right order

About to call stopBroadcasting

,2016-02-09 17:11:58.884 ThaliTest[1679:2984512] jxcore: stopBroadcasting
,2016-02-09 17:11:58.884 ThaliTest[1679:2984512] THEMultipeerSession stopping peer
2016-02-09 17:11:58.884 ThaliTest[1679:2984512] multipeer session: stop timer
2016-02-09 17:11:58.884 ThaliTest[1679:2984512] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,ok 144 stopped event should occur in right order

,mux server bridge listener closed

,# setup

,# ThaliReplicationManager receives identity

,appEnteredForeground wasn't registered

,appEnteringBackground wasn't registered


```
