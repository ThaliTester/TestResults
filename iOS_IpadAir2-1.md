#### Test 58380500fccea7e_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/58380500fccea7e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/F0B24F4A-7174-4B46-9E83-47D0714B92EA/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/F0B24F4A-7174-4B46-9E83-47D0714B92EA/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/58380500fccea7e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/58380500fccea7e/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/02C6A42D-CF7F-4381-9DCD-A4B17056615E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51179"
,(lldb)     command script import "/tmp/F0B24F4A-7174-4B46-9E83-47D0714B92EA/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-06 01:12:31.198 ThaliTest[776:1186334] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/1A562368-65A1-42F2-B86B-3FC820769013/Library/Cookies/Cookies.binarycookies
,2016-02-06 01:12:31.549 ThaliTest[776:1186334] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-06 01:12:31.550 ThaliTest[776:1186334] Multi-tasking -> Device: YES, App: YES
,2016-02-06 01:12:31.558 ThaliTest[776:1186334] Unlimited access to network resources
,2016-02-06 01:12:31.566 ThaliTest[776:1186334] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-06 01:12:41.193 ThaliTest[776:1186334] Resetting plugins due to page load.
,2016-02-06 01:12:45.096 ThaliTest[776:1186334] Finished load of: file:///var/mobile/Containers/Bundle/Application/02C6A42D-CF7F-4381-9DCD-A4B17056615E/ThaliTest.app/www/index.html
,2016-02-06 01:12:45.260 ThaliTest[776:1186334] JXcore Cordova plugin initializing
,2016-02-06 01:12:45.260 ThaliTest[776:1186595] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/02C6A42D-CF7F-4381-9DCD-A4B17056615E/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/02C6A42D-CF7F-4381-9DCD-A4B17056615E/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/02C6A42D-CF7F-4381-9DCD-A4B17056615E/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/02C6A42D-CF7F-4381-9DCD-A4B17056615E/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/02C6A42D-CF7F-4381-9DCD-A4B17056615E/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/02C6A42D-CF7F-4381-9DCD-A4B17056615E/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/02C6A42D-CF7F-4381-9DCD-A4B17056615E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/02C6A42D-CF7F-4381-9DCD-A4B17056615E/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/02C6A42D-CF7F-4381-9DCD-A4B17056615E/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,TAP version 13

,# setup

,# #generatePreambleAndBeacons empty keys to notify

,ok 1 should be equal

,ok 2 should be equal

,ok 3 should be equal

,ok 4 should be equal

,# teardown

# setup

# #generatePreambleAndBeacons multiple keys to notify

,ok 5 should be equal

ok 6 should be equal

,ok 7 should be equal

,ok 8 should be equal

,# teardown

,# setup

,# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

,ok 9 should throw

,# teardown

,# setup

,# #parseBeacons invalid expiration in beaconStreamWithPreAmble

,ok 10 should throw

# teardown

,# setup

,# #parseBeacons no beacons returns null

,ok 11 should be equal

,# teardown

,# setup

,# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

,ok 12 should throw

,# teardown

,# setup

,# #parseBeacons addressBookCallback fails decrypt

,ok 13 should be equal

# teardown

,# setup

,# #parseBeacons addressBookCallback returns null for all

,ok 14 (unnamed assert)

,ok 15 should be equal

,# teardown

,# setup

,# #parseBeacons addressBookCallback returns public key

,ok 16 (unnamed assert)

,ok 17 (unnamed assert)

,# teardown

,# setup

,# #parseBeacons with beacons both for and not for the user

,ok 18 (unnamed assert)

# teardown

,# setup

,# multiplex can send data

,ok 19 String should be length:200

,# teardown

,# setup

,# enqueue and run in order

,ok 20 firstPromise setTimeout

,ok 21 firstPromise result

,ok 22 firstPromise testValue

,ok 23 secondPromise setTimeout

,ok 24 secondPromise result

,ok 25 secondPromise testValue

,ok 26 thirdPromise in promise

,ok 27 thirdPromise result

,ok 28 thirdPromise testValue

,# teardown

,# setup

,# basic

,ok 29 sane

,# teardown

,# setup

,# another

,ok 30 sane

,# teardown

,# setup

,# successfully create a new pkcs12 file and return hash value

,ok 31 should be equal

,ok 32 null

,ok 33 (unnamed assert)

ok 34 should be equal

,ok 35 should not throw

# teardown

,# setup

,# successfully read a previous pkcs12 file and return hash value

,ok 36 (unnamed assert)

,ok 37 (unnamed assert)

ok 38 should not throw

,ok 39 should be equal

ok 40 should be equal

,# teardown

,# setup

,# failed to extract public key because of corrupt pkcs12 file

,ok 41 should be equal

,# teardown

,# setup

,# failed to get mobile documents path

,ok 42 should be equal

,# teardown

,# setup

,# #init should register the peerAvailabilityChanged event

,ok 43 should be equal

,ok 44 should be equal

,ok 45 should be equal

,# teardown

,# setup

,# #init should register the networkChanged event

,ok 46 should be equal

,# teardown

,# setup

,# #startBroadcasting should throw on null device name

,ok 47 should throw

,# teardown

,# setup

,# #startBroadcasting should throw on empty string device name

,ok 48 should throw

,# teardown

,# setup

,# #startBroadcasting should throw on non-number port

,ok 49 should throw

,# teardown

,# setup

,# #startBroadcasting should throw on NaN port

,ok 50 should throw

,# teardown

,# setup

,# #startBroadcasting should throw on negative port

,ok 51 should throw

,# teardown

,# setup

,# #startBroadcasting should throw on too large port

,ok 52 should throw

,# teardown

,# setup

,# #startBroadcasting should call Mobile("StartBroadcasting") without an error

,ok 53 should be equal

,ok 54 should be equal

,ok 55 should be equal

,# teardown

,# setup

,# #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

,ok 56 should be equal

,ok 57 should be equal

,ok 58 should be equal

,# teardown

,# setup

,# #stopBroadcasting should call Mobile("StopBroadcasting") without an error

,ok 59 should be equal

,ok 60 should be equal

,# teardown

,# setup

,# #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

,ok 61 should be equal

,ok 62 should be equal

,# teardown

,# setup

,# #connect should call Mobile("Connect") with a port and without an error

,ok 63 should be equal

,ok 64 should be equal

,ok 65 should be equal

,# teardown

,# setup

,# #connect should call Mobile("Connect") and handle an error

,ok 66 should be equal

,ok 67 should be equal

,# teardown

,# setup

,# should call Mobile("Disconnect") without an error

,ok 68 should be equal

,ok 69 should be equal

,# teardown

,# setup

,# should call Mobile("Disconnect") and handle an error

,ok 70 should be equal

,ok 71 should be equal

,# teardown

,# setup

,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

,2016-02-06 01:17:22.548 ThaliTest[776:1186595] jxcore: startBroadcasting
,2016-02-06 01:17:22.565 ThaliTest[776:1186595] server: starting 1454717842548.776.MWOAqw==
,2016-02-06 01:17:22.567 ThaliTest[776:1186595] multipeer session: start timer: 0x1a9332c0
,2016-02-06 01:17:22.567 ThaliTest[776:1186595] THEMultipeerSession initialized peer 1454717842548.776
,2016-02-06 01:17:22.569 ThaliTest[776:1186595] jxcore: startBroadcasting: success
,ok 72 Should be able to call startBroadcasting without error

2016-02-06 01:17:22.573 ThaliTest[776:1186595] jxcore: stopBroadcasting
2016-02-06 01:17:22.574 ThaliTest[776:1186595] THEMultipeerSession stopping peer
2016-02-06 01:17:22.574 ThaliTest[776:1186595] multipeer session: stop timer
,2016-02-06 01:17:22.575 ThaliTest[776:1186595] jxcore: stopBroadcasting: success
,ok 73 Should be able to call stopBroadcasting without error

,2016-02-06 01:17:22.584 ThaliTest[776:1186595] jxcore: startBroadcasting
,2016-02-06 01:17:22.588 ThaliTest[776:1186595] server: starting 1454717842583.776.HXTA7g==
,2016-02-06 01:17:22.590 ThaliTest[776:1186595] multipeer session: start timer: 0x1a95ae50
,2016-02-06 01:17:22.595 ThaliTest[776:1186595] THEMultipeerSession initialized peer 1454717842583.776
,2016-02-06 01:17:22.597 ThaliTest[776:1186595] jxcore: startBroadcasting: success
,ok 74 Should be able to call startBroadcasting without error

,2016-02-06 01:17:22.600 ThaliTest[776:1186595] jxcore: stopBroadcasting
,2016-02-06 01:17:22.602 ThaliTest[776:1186595] THEMultipeerSession stopping peer
,2016-02-06 01:17:22.603 ThaliTest[776:1186595] multipeer session: stop timer
,2016-02-06 01:17:22.608 ThaliTest[776:1186595] jxcore: stopBroadcasting: success
,ok 75 Should be able to call stopBroadcasting without error

,2016-02-06 01:17:22.612 ThaliTest[776:1186595] jxcore: startBroadcasting
,2016-02-06 01:17:22.617 ThaliTest[776:1186595] server: starting 1454717842611.776.LWxw1w==
,2016-02-06 01:17:22.619 ThaliTest[776:1186595] multipeer session: start timer: 0x1a95b1c0
,2016-02-06 01:17:22.623 ThaliTest[776:1186595] THEMultipeerSession initialized peer 1454717842611.776
,2016-02-06 01:17:22.625 ThaliTest[776:1186595] jxcore: startBroadcasting: success
,ok 76 Should be able to call startBroadcasting without error

,2016-02-06 01:17:22.629 ThaliTest[776:1186595] jxcore: stopBroadcasting
,2016-02-06 01:17:22.629 ThaliTest[776:1186595] THEMultipeerSession stopping peer
,2016-02-06 01:17:22.630 ThaliTest[776:1186595] multipeer session: stop timer
,2016-02-06 01:17:22.636 ThaliTest[776:1186595] jxcore: stopBroadcasting: success
,ok 77 Should be able to call stopBroadcasting without error

,2016-02-06 01:17:22.638 ThaliTest[776:1186595] jxcore: startBroadcasting
,2016-02-06 01:17:22.642 ThaliTest[776:1186595] server: starting 1454717842638.776.EnEXuw==
,2016-02-06 01:17:22.643 ThaliTest[776:1186595] multipeer session: start timer: 0x1abd73d0
,2016-02-06 01:17:22.647 ThaliTest[776:1186595] THEMultipeerSession initialized peer 1454717842638.776
,2016-02-06 01:17:22.652 ThaliTest[776:1186595] jxcore: startBroadcasting: success
,ok 78 Should be able to call startBroadcasting without error

,2016-02-06 01:17:22.655 ThaliTest[776:1186595] jxcore: stopBroadcasting
,2016-02-06 01:17:22.656 ThaliTest[776:1186595] THEMultipeerSession stopping peer
,2016-02-06 01:17:22.657 ThaliTest[776:1186595] multipeer session: stop timer
,2016-02-06 01:17:22.659 ThaliTest[776:1186595] jxcore: stopBroadcasting: success
,ok 79 Should be able to call stopBroadcasting without error

,2016-02-06 01:17:22.661 ThaliTest[776:1186595] jxcore: startBroadcasting
,2016-02-06 01:17:22.664 ThaliTest[776:1186595] server: starting 1454717842661.776.G3RLpQ==
,2016-02-06 01:17:22.665 ThaliTest[776:1186595] multipeer session: start timer: 0x1a95beb0
,2016-02-06 01:17:22.668 ThaliTest[776:1186595] THEMultipeerSession initialized peer 1454717842661.776
,2016-02-06 01:17:22.669 ThaliTest[776:1186595] jxcore: startBroadcasting: success
,ok 80 Should be able to call startBroadcasting without error

,2016-02-06 01:17:22.671 ThaliTest[776:1186595] jxcore: stopBroadcasting
,2016-02-06 01:17:22.671 ThaliTest[776:1186595] THEMultipeerSession stopping peer
,2016-02-06 01:17:22.672 ThaliTest[776:1186595] multipeer session: stop timer
,2016-02-06 01:17:22.673 ThaliTest[776:1186595] jxcore: stopBroadcasting: success
,ok 81 Should be able to call stopBroadcasting without error

,2016-02-06 01:17:22.676 ThaliTest[776:1186595] jxcore: startBroadcasting
,2016-02-06 01:17:22.679 ThaliTest[776:1186595] server: starting 1454717842676.776.E3ZcRA==
,2016-02-06 01:17:22.680 ThaliTest[776:1186595] multipeer session: start timer: 0x1af50c50
,2016-02-06 01:17:22.683 ThaliTest[776:1186595] THEMultipeerSession initialized peer 1454717842676.776
,2016-02-06 01:17:22.685 ThaliTest[776:1186595] jxcore: startBroadcasting: success
,ok 82 Should be able to call startBroadcasting without error

,2016-02-06 01:17:22.687 ThaliTest[776:1186595] jxcore: stopBroadcasting
,2016-02-06 01:17:22.687 ThaliTest[776:1186595] THEMultipeerSession stopping peer
,2016-02-06 01:17:22.688 ThaliTest[776:1186595] multipeer session: stop timer
,2016-02-06 01:17:22.691 ThaliTest[776:1186595] jxcore: stopBroadcasting: success
,ok 83 Should be able to call stopBroadcasting without error

,2016-02-06 01:17:22.693 ThaliTest[776:1186595] jxcore: startBroadcasting
,2016-02-06 01:17:22.695 ThaliTest[776:1186595] server: starting 1454717842692.776.vhHcSw==
,2016-02-06 01:17:22.697 ThaliTest[776:1186595] multipeer session: start timer: 0x1a95b9f0
,2016-02-06 01:17:22.701 ThaliTest[776:1186595] THEMultipeerSession initialized peer 1454717842692.776
,2016-02-06 01:17:22.702 ThaliTest[776:1186595] jxcore: startBroadcasting: success
,ok 84 Should be able to call startBroadcasting without error

,2016-02-06 01:17:22.704 ThaliTest[776:1186595] jxcore: stopBroadcasting
,2016-02-06 01:17:22.704 ThaliTest[776:1186595] THEMultipeerSession stopping peer
,2016-02-06 01:17:22.706 ThaliTest[776:1186595] multipeer session: stop timer
,2016-02-06 01:17:22.709 ThaliTest[776:1186595] jxcore: stopBroadcasting: success
,ok 85 Should be able to call stopBroadcasting without error

,2016-02-06 01:17:22.711 ThaliTest[776:1186595] jxcore: startBroadcasting
,2016-02-06 01:17:22.714 ThaliTest[776:1186595] server: starting 1454717842710.776.BbtLcA==
,2016-02-06 01:17:22.715 ThaliTest[776:1186595] multipeer session: start timer: 0x1af51bd0
,2016-02-06 01:17:22.719 ThaliTest[776:1186595] THEMultipeerSession initialized peer 1454717842710.776
,2016-02-06 01:17:22.720 ThaliTest[776:1186595] jxcore: startBroadcasting: success
,ok 86 Should be able to call startBroadcasting without error

,2016-02-06 01:17:22.722 ThaliTest[776:1186595] jxcore: stopBroadcasting
,2016-02-06 01:17:22.722 ThaliTest[776:1186595] THEMultipeerSession stopping peer
,2016-02-06 01:17:22.723 ThaliTest[776:1186595] multipeer session: stop timer
,2016-02-06 01:17:22.726 ThaliTest[776:1186595] jxcore: stopBroadcasting: success
,ok 87 Should be able to call stopBroadcasting without error

,2016-02-06 01:17:22.728 ThaliTest[776:1186595] jxcore: startBroadcasting
,2016-02-06 01:17:22.731 ThaliTest[776:1186595] server: starting 1454717842728.776.Y7yg6g==
,2016-02-06 01:17:22.733 ThaliTest[776:1186595] multipeer session: start timer: 0x1abd7720
,2016-02-06 01:17:22.734 ThaliTest[776:1186595] THEMultipeerSession initialized peer 1454717842728.776
,2016-02-06 01:17:22.736 ThaliTest[776:1186595] jxcore: startBroadcasting: success
,ok 88 Should be able to call startBroadcasting without error

,2016-02-06 01:17:22.738 ThaliTest[776:1186595] jxcore: stopBroadcasting
,2016-02-06 01:17:22.739 ThaliTest[776:1186595] THEMultipeerSession stopping peer
,2016-02-06 01:17:22.739 ThaliTest[776:1186595] multipeer session: stop timer
,2016-02-06 01:17:22.740 ThaliTest[776:1186595] jxcore: stopBroadcasting: success
,ok 89 Should be able to call stopBroadcasting without error

,2016-02-06 01:17:22.742 ThaliTest[776:1186595] jxcore: startBroadcasting
,2016-02-06 01:17:22.744 ThaliTest[776:1186595] server: starting 1454717842742.776.MZv83Q==
,2016-02-06 01:17:22.745 ThaliTest[776:1186595] multipeer session: start timer: 0x1a957d70
,2016-02-06 01:17:22.747 ThaliTest[776:1186595] THEMultipeerSession initialized peer 1454717842742.776
2016-02-06 01:17:22.749 ThaliTest[776:1186595] jxcore: startBroadcasting: success
,ok 90 Should be able to call startBroadcasting without error

,2016-02-06 01:17:22.751 ThaliTest[776:1186595] jxcore: stopBroadcasting
,2016-02-06 01:17:22.751 ThaliTest[776:1186595] THEMultipeerSession stopping peer
,2016-02-06 01:17:22.752 ThaliTest[776:1186595] multipeer session: stop timer
,2016-02-06 01:17:22.753 ThaliTest[776:1186595] jxcore: stopBroadcasting: success
,ok 91 Should be able to call stopBroadcasting without error

,# teardown

,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,2016-02-06 01:17:23.335 ThaliTest[776:1186595] jxcore: startBroadcasting
,2016-02-06 01:17:23.339 ThaliTest[776:1186595] server: starting 1454717843335.776.ucGyoA==
2016-02-06 01:17:23.340 ThaliTest[776:1186595] multipeer session: start timer: 0x1af55430
,2016-02-06 01:17:23.340 ThaliTest[776:1186595] THEMultipeerSession initialized peer 1454717843335.776
,2016-02-06 01:17:23.343 ThaliTest[776:1186595] jxcore: startBroadcasting: success
,ok 92 Should be able to call startBroadcasting without error

,2016-02-06 01:17:23.350 ThaliTest[776:1186595] jxcore: startBroadcasting
,2016-02-06 01:17:23.351 ThaliTest[776:1186595] jxcore: startBroadcasting: failure
,ok 93 Cannot call startBroadcasting twice

,2016-02-06 01:17:23.356 ThaliTest[776:1186595] jxcore: stopBroadcasting
,2016-02-06 01:17:23.357 ThaliTest[776:1186595] THEMultipeerSession stopping peer
,2016-02-06 01:17:23.358 ThaliTest[776:1186595] multipeer session: stop timer
,2016-02-06 01:17:23.362 ThaliTest[776:1186595] jxcore: stopBroadcasting: success
,ok 94 Should be able to call stopBroadcasting without error

,# teardown

,# setup

,# ThaliEmitter throws on connection to bad peer

,2016-02-06 01:17:28.969 ThaliTest[776:1186595] jxcore: startBroadcasting
,2016-02-06 01:17:28.972 ThaliTest[776:1186595] server: starting 1454717848968.776.lagElw==
,2016-02-06 01:17:28.974 ThaliTest[776:1186595] multipeer session: start timer: 0x1a95a730
,2016-02-06 01:17:28.975 ThaliTest[776:1186595] THEMultipeerSession initialized peer 1454717848968.776
2016-02-06 01:17:28.975 ThaliTest[776:1186595] jxcore: startBroadcasting: success
,ok 95 Should be able to call startBroadcasting without error

2016-02-06 01:17:28.978 ThaliTest[776:1186595] jxcore: connect foobar
2016-02-06 01:17:28.978 ThaliTest[776:1186595] client: unknown peer foobar
,2016-02-06 01:17:28.978 ThaliTest[776:1186595] jxcore: connect: fail: Unknown peer
,ok 96 Should not connect to a bad peer

2016-02-06 01:17:28.983 ThaliTest[776:1186595] jxcore: stopBroadcasting
,2016-02-06 01:17:28.983 ThaliTest[776:1186595] THEMultipeerSession stopping peer
,2016-02-06 01:17:28.984 ThaliTest[776:1186595] multipeer session: stop timer
,2016-02-06 01:17:28.985 ThaliTest[776:1186595] jxcore: stopBroadcasting: success
,ok 97 Should be able to call stopBroadcasting without error

,# teardown

,# setup

,# ThaliEmitter throws on disconnect to bad peer

,2016-02-06 01:17:32.066 ThaliTest[776:1186595] jxcore: startBroadcasting
,2016-02-06 01:17:32.069 ThaliTest[776:1186595] server: starting 1454717852065.776.afitAg==
,2016-02-06 01:17:32.070 ThaliTest[776:1186595] multipeer session: start timer: 0x1ab13470
,2016-02-06 01:17:32.071 ThaliTest[776:1186595] THEMultipeerSession initialized peer 1454717852065.776
2016-02-06 01:17:32.071 ThaliTest[776:1186595] jxcore: startBroadcasting: success
,ok 98 Should be able to call startBroadcasting without error

2016-02-06 01:17:32.074 ThaliTest[776:1186595] jxcore: disconnect
,2016-02-06 01:17:32.074 ThaliTest[776:1186595] jxcore: disconnect: fail
,ok 99 Disconnect should fail to a non-existant peer 

2016-02-06 01:17:32.079 ThaliTest[776:1186595] jxcore: stopBroadcasting
2016-02-06 01:17:32.079 ThaliTest[776:1186595] THEMultipeerSession stopping peer
2016-02-06 01:17:32.079 ThaliTest[776:1186595,] multipeer session: stop timer
2016-02-06 01:17:32.080 ThaliTest[776:1186595] jxcore: stopBroadcasting: success
,ok 100 Should be able to call stopBroadcasting without error

,# teardown

,# setup

,# ThaliEmitter can discover and connect to peers

,2016-02-06 01:17:32.856 ThaliTest[776:1186595] jxcore: startBroadcasting
,2016-02-06 01:17:32.859 ThaliTest[776:1186595] server: starting 1454717852856.776.e9+C8Q==
,2016-02-06 01:17:32.860 ThaliTest[776:1186595] multipeer session: start timer: 0x1ab0e900
,2016-02-06 01:17:32.861 ThaliTest[776:1186595] THEMultipeerSession initialized peer 1454717852856.776
,2016-02-06 01:17:32.863 ThaliTest[776:1186595] jxcore: startBroadcasting: success
,ok 101 Should be able to call startBroadcasting without error

,2016-02-06 01:17:34.145 ThaliTest[776:1186334] client: found peer: 1454717851080.1351.fN3s3Q==
,2016-02-06 01:17:34.148 ThaliTest[776:1186595] jxcore: connect 1454717851080.1351.fN3s3Q==
,2016-02-06 01:17:34.148 ThaliTest[776:1186595] client session: connect
,2016-02-06 01:17:34.149 ThaliTest[776:1186595] client session: stateChange:0->1 1454717851080.1351.fN3s3Q==
,2016-02-06 01:17:34.418 ThaliTest[776:1186334] multipeer session: reset timer
,2016-02-06 01:17:34.419 ThaliTest[776:1186334] multipeer session: stop timer
,2016-02-06 01:17:34.419 ThaliTest[776:1186334] multipeer session: start timer: 0x1ab0e900
2016-02-06 01:17:34.420 ThaliTest[776:1186334] server session: connect
,2016-02-06 01:17:34.420 ThaliTest[776:1186334] server session: stateChange:0->1 1454717851080.1351
,2016-02-06 01:17:34.427 ThaliTest[776:1186334] server: accepting invitation 1454717851080.1351
,2016-02-06 01:17:36.952 ThaliTest[776:1187105] server session: connected
2016-02-06 01:17:36.952 ThaliTest[776:1187105] server session: stateChange:1->2 1454717851080.1351
2016-02-06 01:17:36.952 ThaliTest[776:1187124] client session: connected
2016-02-,06 01:17:36.953 ThaliTest[776:1187124] client session: stateChange:1->2 1454717851080.1351.fN3s3Q==
,2016-02-06 01:17:36.998 ThaliTest[776:1186334] server relay: socket disconnected
2016-02-06 01:17:36.998 ThaliTest[776:1187105] client session: fireConnectCallback: 1454717851080.1351.fN3s3Q==
2016-02-06 01:17:36.998 ThaliTest[776:1186334] server relay: 0x17d3dff0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-06 01:17:36.999 ThaliTest[776:1187105] jxcore: connect: success
,ok 102 Should be able to connect without error

,ok 103 Port should be within range

,2016-02-06 01:17:37.004 ThaliTest[776:1186595] jxcore: disconnect
,2016-02-06 01:17:37.005 ThaliTest[776:1186595] client session: disconnectFromPeer: 1454717851080.1351.fN3s3Q==
,2016-02-06 01:17:37.005 ThaliTest[776:1186595] client session: disconnect
,2016-02-06 01:17:37.006 ThaliTest[776:1186595] client session: stateChange:2->0 1454717851080.1351.fN3s3Q==
,2016-02-06 01:17:37.015 ThaliTest[776:1186595] jxcore: disconnect: success
,ok 104 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,2016-02-06 01:17:37.034 ThaliTest[776:1187124] server session: not connected 1454717851080.1351
,# teardown

,calling stopBroadcasting

,2016-02-06 01:17:37.178 ThaliTest[776:1186595] jxcore: stopBroadcasting
,2016-02-06 01:17:37.179 ThaliTest[776:1186595] THEMultipeerSession stopping peer
,2016-02-06 01:17:37.179 ThaliTest[776:1186595] multipeer session: stop timer
,2016-02-06 01:17:37.180 ThaliTest[776:1186595] server session: disconnect
2016-02-06 01:17:37.181 ThaliTest[776:1186595] server session: stateChange:2->0 1454717851080.1351
,2016-02-06 01:17:37.437 ThaliTest[776:1186595] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# setup

,# ThaliEmitter can discover and connect to peers and then fail on double connect

,2016-02-06 01:17:37.743 ThaliTest[776:1186595] jxcore: startBroadcasting
,2016-02-06 01:17:37.747 ThaliTest[776:1186595] server: starting 1454717857743.776.U236Eg==
,2016-02-06 01:17:37.747 ThaliTest[776:1186595] multipeer session: start timer: 0x1a9ba840
,2016-02-06 01:17:37.748 ThaliTest[776:1186595] THEMultipeerSession initialized peer 1454717857743.776
2016-02-06 01:17:37.749 ThaliTest[776:1186595] jxcore: startBroadcasting: success
,ok 105 Should be able to call startBroadcasting without error

,2016-02-06 01:17:38.925 ThaliTest[776:1186334] client: found peer: 1454717855879.1351.ICFwxw==
,2016-02-06 01:17:38.927 ThaliTest[776:1186595] jxcore: connect 1454717855879.1351.ICFwxw==
2016-02-06 01:17:38.927 ThaliTest[776:1186595] client session: connect
2016-02-06 01:17:38.928 ThaliTest[776:1186595] client session: stateChange:0->1 1454717855879.1351.ICFwxw==
,2016-02-06 01:17:39.257 ThaliTest[776:1186334] multipeer session: reset timer
2016-02-06 01:17:39.258 ThaliTest[776:1186334] multipeer session: stop timer
2016-02-06 01:17:39.258 ThaliTest[776:1186334] multipeer session: start timer: 0x1a9ba840
2016-02-06 01:17:39.258 ThaliTest[776:1186334] server session: connect
2016-02-06 01:17:39.259 ThaliTest[776:1186334] server session: stateChange:0->1 1454717855879.1351
,2016-02-06 01:17:39.265 ThaliTest[776:1186334] server: accepting invitation 1454717855879.1351
,2016-02-06 01:17:41.797 ThaliTest[776:1187105] client session: connected
2016-02-06 01:17:41.797 ThaliTest[776:1187105] client session: stateChange:1->2 1454717855879.1351.ICFwxw==
,2016-02-06 01:17:41.807 ThaliTest[776:1187104] client session: fireConnectCallback: 1454717855879.1351.ICFwxw==
2016-02-06 01:17:41.808 ThaliTest[776:1187104] jxcore: connect: success
,ok 106 Should be able to connect without error

,ok 107 Port should be within range

,2016-02-06 01:17:41.813 ThaliTest[776:1186595] jxcore: connect 1454717855879.1351.ICFwxw==
2016-02-06 01:17:41.813 ThaliTest[776:1186595] client: already connect(ing/ed) to 1454717855879.1351.ICFwxw==
2016-02-06 01:17:41.814 ThaliTest[776:1186595] jxcore: connect: fail: Aleady connecting
,ok 108 Should fail on double connect

,2016-02-06 01:17:41.820 ThaliTest[776:1186595] jxcore: disconnect
,2016-02-06 01:17:41.820 ThaliTest[776:1186595] client session: disconnectFromPeer: 1454717855879.1351.ICFwxw==
,2016-02-06 01:17:41.821 ThaliTest[776:1186595] client session: disconnect
2016-02-06 01:17:41.822 ThaliTest[776:1186595] client session: stateChange:2->0 1454717855879.1351.ICFwxw==
,2016-02-06 01:17:41.879 ThaliTest[776:1187125] server session: connected
2016-02-06 01:17:41.880 ThaliTest[776:1187125] server session: stateChange:1->2 1454717855879.1351
,2016-02-06 01:17:41.883 ThaliTest[776:1186334] server relay: socket disconnected
2016-02-06 01:17:41.884 ThaliTest[776:1186334] server relay: 0x17e00410 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocal,izedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-06 01:17:41.893 ThaliTest[776:1186595] jxcore: disconnect: success
,ok 109 Should be able to disconnect without error

,setting stopBroadcasting callback and ending test.

,# teardown

,2016-02-06 01:17:41.945 ThaliTest[776:1187125] server session: not connected 1454717855879.1351
,calling stopBroadcasting

,2016-02-06 01:17:41.963 ThaliTest[776:1186595] jxcore: stopBroadcasting
,2016-02-06 01:17:41.964 ThaliTest[776:1186595] THEMultipeerSession stopping peer
,2016-02-06 01:17:41.964 ThaliTest[776:1186595] multipeer session: stop timer
2016-02-06 01:17:41.965 ThaliTest[776:1186595] server session: disconnect
,2016-02-06 01:17:41.968 ThaliTest[776:1186595] server session: stateChange:2->0 1454717855879.1351
2016-02-06 01:17:41.969 ThaliTest[776:1186595] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# setup

,# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,2016-02-06 01:17:42.499 ThaliTest[776:1186595] jxcore: startBroadcasting
,2016-02-06 01:17:42.503 ThaliTest[776:1186595] server: starting 1454717862499.776.4FjJVg==
,2016-02-06 01:17:42.504 ThaliTest[776:1186595] multipeer session: start timer: 0x17e01b20
,2016-02-06 01:17:42.504 ThaliTest[776:1186595] THEMultipeerSession initialized peer 1454717862499.776
2016-02-06 01:17:42.505 ThaliTest[776:1186595] jxcore: startBroadcasting: success
,ok 110 Should be able to call startBroadcasting without error

,2016-02-06 01:17:43.181 ThaliTest[776:1186334] client: found peer: 1454717855879.1351.ICFwxw==
,2016-02-06 01:17:43.182 ThaliTest[776:1186595] jxcore: connect 1454717855879.1351.ICFwxw==
2016-02-06 01:17:43.183 ThaliTest[776:1186595] client session: connect
2016-02-06 01:17:43.183 ThaliTest[776:1186595] client session: stateChange:0->1 1454717855879.1351.ICFwxw==
,2016-02-06 01:17:43.579 ThaliTest[776:1186334] client: found peer: 1454717860645.1351.d4urHQ==
,2016-02-06 01:17:43.582 ThaliTest[776:1186595] jxcore: connect 1454717860645.1351.d4urHQ==
2016-02-06 01:17:43.582 ThaliTest[776:1186595] client session: connect
2016-02-06 01:17:43.583 ThaliTest[776:1186595] client session: stateChange:0->1 1454717860645.1351.d4urHQ==
,2016-02-06 01:17:43.723 ThaliTest[776:1186334] multipeer session: reset timer
2016-02-06 01:17:43.723 ThaliTest[776:1186334] multipeer session: stop timer
2016-02-06 01:17:43.724 ThaliTest[776:1186334] multipeer session: start timer: 0x17e01b20
2016-02-,06 01:17:43.724 ThaliTest[776:1186334] server session: connect
2016-02-06 01:17:43.724 ThaliTest[776:1186334] server session: stateChange:0->1 1454717860645.1351
,2016-02-06 01:17:43.731 ThaliTest[776:1186334] server: accepting invitation 1454717860645.1351
,2016-02-06 01:17:46.264 ThaliTest[776:1187125] server session: connected
2016-02-06 01:17:46.264 ThaliTest[776:1187125] server session: stateChange:1->2 1454717860645.1351
,2016-02-06 01:17:46.270 ThaliTest[776:1187104] client session: connected
,2016-02-06 01:17:46.270 ThaliTest[776:1187104] client session: stateChange:1->2 1454717860645.1351.d4urHQ==
,2016-02-06 01:17:46.293 ThaliTest[776:1187104] client session: fireConnectCallback: 1454717860645.1351.d4urHQ==
2016-02-06 01:17:46.294 ThaliTest[776:1187104] jxcore: connect: success
2016-02-06 01:17:46.294 ThaliTest[776:1186334] server relay: socket di,sconnected
2016-02-06 01:17:46.295 ThaliTest[776:1186334] server relay: 0x1af6a2c0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,ok 111 Should be able to connect without error

,ok 112 Port should be within range

,2016-02-06 01:17:46.298 ThaliTest[776:1186595] jxcore: disconnect
,2016-02-06 01:17:46.299 ThaliTest[776:1186595] client session: disconnectFromPeer: 1454717860645.1351.d4urHQ==
,2016-02-06 01:17:46.299 ThaliTest[776:1186595] client session: disconnect
,2016-02-06 01:17:46.299 ThaliTest[776:1186595] client session: stateChange:2->0 1454717860645.1351.d4urHQ==
,2016-02-06 01:17:46.309 ThaliTest[776:1186595] jxcore: disconnect: success
,ok 113 Should be able to disconnect without error

2016-02-06 01:17:46.312 ThaliTest[776:1186595] jxcore: disconnect
2016-02-06 01:17:46.312 ThaliTest[776:1186595] jxcore: disconnect: fail
,ok 114 Disconnect should fail 
,
,setting stopBroadcasting callback and ending test.

,# teardown

,2016-02-06 01:17:46.379 ThaliTest[776:1187106] server session: not connected 1454717860645.1351
,calling stopBroadcasting

,2016-02-06 01:17:46.668 ThaliTest[776:1186595] jxcore: stopBroadcasting
,2016-02-06 01:17:46.668 ThaliTest[776:1186595] THEMultipeerSession stopping peer
,2016-02-06 01:17:46.669 ThaliTest[776:1186595] multipeer session: stop timer
2016-02-06 01:17:46.670 ThaliTest[776:1186595] client session: disconnect
2016-02-06 01:17:46.670 ThaliTest[776:1186595] client session: stateChange:1->0 1454717855879.1351.ICFw,xw==
2016-02-06 01:17:46.671 ThaliTest[776:1186595] server session: disconnect
2016-02-06 01:17:46.671 ThaliTest[776:1186595] server session: stateChange:2->0 1454717860645.1351
,2016-02-06 01:17:46.680 ThaliTest[776:1186595] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# setup

,# ThaliEmitter can connect and send data

,echo server started on port: 54129

,2016-02-06 01:17:47.797 ThaliTest[776:1186595] jxcore: startBroadcasting
,2016-02-06 01:17:47.798 ThaliTest[776:1186595] server: starting 1454717867797.776.TNwaBw==
,2016-02-06 01:17:47.798 ThaliTest[776:1186595] multipeer session: start timer: 0x1af54dc0
2016-02-06 01:17:47.799 ThaliTest[776:1186595] THEMultipeerSession initialized peer 1454717867797.776
2016-02-06 01:17:47.799 ThaliTest[776:1186595] jxcore: startBroadcasting: success
,ok 115 Should be able to call startBroadcasting without error

,2016-02-06 01:17:47.802 ThaliTest[776:1186334] client: found peer: 1454717855879.1351.ICFwxw==
,2016-02-06 01:17:47.803 ThaliTest[776:1186595] jxcore: connect 1454717855879.1351.ICFwxw==
,2016-02-06 01:17:47.803 ThaliTest[776:1186595] client session: connect
,2016-02-06 01:17:47.803 ThaliTest[776:1186595] client session: stateChange:0->1 1454717855879.1351.ICFwxw==
,2016-02-06 01:17:48.824 ThaliTest[776:1186334] client: found peer: 1454717866014.1351.DXC6hQ==
,2016-02-06 01:17:48.826 ThaliTest[776:1186595] jxcore: connect 1454717866014.1351.DXC6hQ==
2016-02-06 01:17:48.826 ThaliTest[776:1186595] client session: connect
,2016-02-06 01:17:48.826 ThaliTest[776:1186595] client session: stateChange:0->1 1454717866014.1351.DXC6hQ==
,2016-02-06 01:17:48.919 ThaliTest[776:1186334] multipeer session: reset timer
2016-02-06 01:17:48.920 ThaliTest[776:1186334] multipeer session: stop timer
2016-02-06 01:17:48.920 ThaliTest[776:1186334] multipeer session: start timer: 0x1af54dc0
2016-02-06 01:17:48.920 ThaliTest[776:1186334] server session: connect
,2016-02-06 01:17:48.920 ThaliTest[776:1186334] server session: stateChange:0->1 1454717866014.1351
,2016-02-06 01:17:48.925 ThaliTest[776:1186334] server: accepting invitation 1454717866014.1351
,2016-02-06 01:17:51.265 ThaliTest[776:1187124] server session: connected
,2016-02-06 01:17:51.266 ThaliTest[776:1187124] server session: stateChange:1->2 1454717866014.1351
,2016-02-06 01:17:51.316 ThaliTest[776:1186334] server relay: connected (to port: 54129)
,2016-02-06 01:17:51.449 ThaliTest[776:1187124] client session: connected
2016-02-06 01:17:51.449 ThaliTest[776:1187124] client session: stateChange:1->2 1454717866014.1351.DXC6hQ==
,2016-02-06 01:17:51.468 ThaliTest[776:1187124] client session: fireConnectCallback: 1454717866014.1351.DXC6hQ==
2016-02-06 01:17:51.468 ThaliTest[776:1187124] jxcore: connect: success
,ok 116 Should be able to connect without error

ok 117 Port should be within range

,2016-02-06 01:17:51.476 ThaliTest[776:1186334] client: relay established
2016-02-06 01:17:51.477 ThaliTest[776:1186334] client: new accepted socket: 0x19ec2810
,data in 12288

,data in 28470

,data in 49275

,data in 71175

,data in 91980

,data in 109500

,2016-02-06 01:17:51.729 ThaliTest[776:1187125] server session: not connected 1454717866014.1351
,data in 110595

,data in 116657

,data in 130750

,data in 131072

,ok 118 the test messages should be equal

,2016-02-06 01:17:51.799 ThaliTest[776:1186595] jxcore: disconnect
,2016-02-06 01:17:51.799 ThaliTest[776:1186595] client session: disconnectFromPeer: 1454717866014.1351.DXC6hQ==
,2016-02-06 01:17:51.800 ThaliTest[776:1186595] client session: disconnect
,2016-02-06 01:17:51.800 ThaliTest[776:1186595] client session: stateChange:2->0 1454717866014.1351.DXC6hQ==
,2016-02-06 01:17:51.810 ThaliTest[776:1186595] jxcore: disconnect: success
,ok 119 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# teardown

,calling stopBroadcasting

,2016-02-06 01:17:51.846 ThaliTest[776:1186595] jxcore: stopBroadcasting
,2016-02-06 01:17:51.847 ThaliTest[776:1186595] THEMultipeerSession stopping peer
,2016-02-06 01:17:51.847 ThaliTest[776:1186595] multipeer session: stop timer
,2016-02-06 01:17:51.848 ThaliTest[776:1186595] client session: disconnect
2016-02-06 01:17:51.848 ThaliTest[776:1186595] client session: stateChange:1->0 1454717855879.1351.ICFwxw==
,2016-02-06 01:17:51.850 ThaliTest[776:1186595] server session: disconnect
2016-02-06 01:17:51.853 ThaliTest[776:1186595] server session: stateChange:2->0 1454717866014.1351
,2016-02-06 01:17:51.864 ThaliTest[776:1186595] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# setup

,# ThaliEmitter handles socket disconnect correctly

,echo server started on port: 54136

,2016-02-06 01:17:51.924 ThaliTest[776:1186595] jxcore: startBroadcasting
,2016-02-06 01:17:51.926 ThaliTest[776:1186595] server: starting 1454717871923.776.9anJUQ==
,2016-02-06 01:17:51.926 ThaliTest[776:1186595] multipeer session: start timer: 0x1af5cfb0
2016-02-06 01:17:51.927 ThaliTest[776:1186595] THEMultipeerSession initialized peer 1454717871923.776
2016-02-06 01:17:51.927 ThaliTest[776:1186595] jxcore: startBroadcasting: success
,ok 120 Should be able to call startBroadcasting without error

,2016-02-06 01:17:51.936 ThaliTest[776:1186334] client: found peer: 1454717867797.776.TNwaBw==
,2016-02-06 01:17:51.937 ThaliTest[776:1186334] client: found peer: 1454717866014.1351.DXC6hQ==
[{"peerIdentifier":"1454717867797.776.TNwaBw==","peerName":"(null)","peerAvailable":true}]

,2016-02-06 01:17:51.938 ThaliTest[776:1186595] jxcore: connect 1454717867797.776.TNwaBw==
2016-02-06 01:17:51.938 ThaliTest[776:1186595] client session: connect
2016-02-06 01:17:51.939 ThaliTest[776:1186595] client session: stateChange:0->1 1454717867797.776.TNwaBw==
,[{"peerIdentifier":"1454717866014.1351.DXC6hQ==","peerName":"(null)","peerAvailable":true}]

2016-02-06 01:17:52.022 ThaliTest[776:1186595] jxcore: connect 1454717866014.1351.DXC6hQ==
2016-02-06 01:17:52.023 ThaliTest[776:1186595] client session: connect
2016-02-06 01:17:52.023 ThaliTest[776:1186595] client session: stateChange:0->1 1454717866014.1351.DXC6hQ==
,2016-02-06 01:17:52.985 ThaliTest[776:1186334] client: lost peer: 1454717867797.776.TNwaBw==
,2016-02-06 01:17:52.985 ThaliTest[776:1186334] client session: onPeerLost: 1454717867797.776.TNwaBw==
2016-02-06 01:17:52.986 ThaliTest[776:1186334] client session: onLinkFailure: 1454717867797.776.TNwaBw==
2016-02-06 01:17:52.986 ThaliTest[776:1186334] client session: disconnect
,2016-02-06 01:17:52.986 ThaliTest[776:1186334] client session: stateChange:1->0 1454717867797.776.TNwaBw==
2016-02-06 01:17:52.987 ThaliTest[776:1186334] client session: fireConnectCallback: 1454717867797.776.TNwaBw==
,2016-02-06 01:17:52.987 ThaliTest[776:1186334] jxcore: connect: fail: Peer disconnected
,[{"peerIdentifier":"1454717867797.776.TNwaBw==","peerName":"(null)","peerAvailable":false}]

,2016-02-06 01:17:53.011 ThaliTest[776:1186334] client: found peer: 1454717870061.1351.6cUd6g==
,[{"peerIdentifier":"1454717870061.1351.6cUd6g==","peerName":"(null)","peerAvailable":true}]

2016-02-06 01:17:53.013 ThaliTest[776:1186595] jxcore: connect 1454717870061.1351.6cUd6g==
2016-02-06 01:17:53.013 ThaliTest[776:1186595] client session: connect
2016-02-06 01:17:53.014 ThaliTest[776:1186595] client session: stateChange:0->1 1454717870061.1351.6cUd6g==
,2016-02-06 01:17:53.116 ThaliTest[776:1186334] multipeer session: reset timer
,2016-02-06 01:17:53.116 ThaliTest[776:1186334] multipeer session: stop timer
,2016-02-06 01:17:53.117 ThaliTest[776:1186334] multipeer session: start timer: 0x1af5cfb0
,2016-02-06 01:17:53.117 ThaliTest[776:1186334] server session: connect
,2016-02-06 01:17:53.118 ThaliTest[776:1186334] server session: stateChange:0->1 1454717870061.1351
,2016-02-06 01:17:53.124 ThaliTest[776:1186334] server: accepting invitation 1454717870061.1351
,2016-02-06 01:17:54.000 ThaliTest[776:1186595] jxcore: connect 1454717867797.776.TNwaBw==
2016-02-06 01:17:54.000 ThaliTest[776:1186595] client: connect: unreachable 1454717867797.776.TNwaBw==
,2016-02-06 01:17:54.001 ThaliTest[776:1186595] jxcore: connect: fail: Peer unreachable
,2016-02-06 01:17:55.513 ThaliTest[776:1187104] server session: connected
2016-02-06 01:17:55.513 ThaliTest[776:1187104] server session: stateChange:1->2 1454717870061.1351
,2016-02-06 01:17:55.520 ThaliTest[776:1186334] server relay: connected (to port: 54136)
,2016-02-06 01:17:55.553 ThaliTest[776:1187124] client session: connected
,2016-02-06 01:17:55.553 ThaliTest[776:1187124] client session: stateChange:1->2 1454717870061.1351.6cUd6g==
,2016-02-06 01:17:55.573 ThaliTest[776:1187169] client session: fireConnectCallback: 1454717870061.1351.6cUd6g==
2016-02-06 01:17:55.573 ThaliTest[776:1187169] jxcore: connect: success
,ok 121 Should be able to connect without error

,ok 122 Port should be within range

,ok 123 First connect should succeed

,2016-02-06 01:17:55.663 ThaliTest[776:1186334] client: relay established
,2016-02-06 01:17:55.664 ThaliTest[776:1186334] client: new accepted socket: 0x1abb6990
,ok 124 the test messages should be equal

,ok 125 First send should succeed
,
,2016-02-06 01:17:55.748 ThaliTest[776:1186334] client: socket closed
,2016-02-06 01:17:55.748 ThaliTest[776:1186334] client relay: socket disconnected
,2016-02-06 01:17:55.749 ThaliTest[776:1186334] client relay: 0x1abb6990 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2016-02-06 01:17:55.749 ThaliTest[776:1186334] client session: socket closed: 1454717870061.1351.6cUd6g==
2016-02-06 01:17:55.749 ThaliTest[776:1186334] client session: onLinkFailure: 1454717870061.1351.6cUd6g==
,2016-02-06 01:17:55.750 ThaliTest[776:1186334] client session: disconnect
2016-02-06 01:17:55.750 ThaliTest[776:1186334] client session: stateChange:2->0 1454717870061.1351.6cUd6g==
,2016-02-06 01:17:55.761 ThaliTest[776:1186334] client session: fireConnectionErrorEvent: 1454717870061.1351.6cUd6g==
,2016-02-06 01:17:55.767 ThaliTest[776:1186595] jxcore: connect 1454717870061.1351.6cUd6g==
,2016-02-06 01:17:55.768 ThaliTest[776:1186595] client session: connect
,2016-02-06 01:17:55.769 ThaliTest[776:1186595] client session: stateChange:0->1 1454717870061.1351.6cUd6g==
,2016-02-06 01:17:56.001 ThaliTest[776:1187125] server session: not connected 1454717870061.1351
,2016-02-06 01:17:56.178 ThaliTest[776:1186334] multipeer session: reset timer
,2016-02-06 01:17:56.178 ThaliTest[776:1186334] multipeer session: stop timer
,2016-02-06 01:17:56.179 ThaliTest[776:1186334] multipeer session: start timer: 0x1af5cfb0
,2016-02-06 01:17:56.180 ThaliTest[776:1186334] server: disconnecting to refresh session (1454717870061.1351)
2016-02-06 01:17:56.181 ThaliTest[776:1186334] server session: disconnect
,2016-02-06 01:17:56.181 ThaliTest[776:1186334] server session: stateChange:2->0 1454717870061.1351
,2016-02-06 01:17:56.184 ThaliTest[776:1186334] server session: connect
,2016-02-06 01:17:56.184 ThaliTest[776:1186334] server session: stateChange:0->1 1454717870061.1351
,2016-02-06 01:17:56.191 ThaliTest[776:1186334] server: accepting invitation 1454717870061.1351
,2016-02-06 01:17:58.334 ThaliTest[776:1187105] client session: connected
,2016-02-06 01:17:58.334 ThaliTest[776:1187105] client session: stateChange:1->2 1454717870061.1351.6cUd6g==
,2016-02-06 01:17:58.384 ThaliTest[776:1187105] client session: fireConnectCallback: 1454717870061.1351.6cUd6g==
2016-02-06 01:17:58.384 ThaliTest[776:1187105] jxcore: connect: success
,ok 126 Should be able to connect without error

,ok 127 Port should be within range

,ok 128 Second connect should succeed

,2016-02-06 01:17:58.419 ThaliTest[776:1186334] client: relay established
,2016-02-06 01:17:58.419 ThaliTest[776:1186334] client: new accepted socket: 0x19ba21a0
,ok 129 the test messages should be equal

,ok 130 Second send should succeed

,# teardown
,2016-02-06 01:17:58.524 ThaliTest[776:1187106] server session: connected
,2016-02-06 01:17:58.524 ThaliTest[776:1187106] server session: stateChange:1->2 1454717870061.1351
,
,2016-02-06 01:17:58.529 ThaliTest[776:1186334] server relay: connected (to port: 54136)
,2016-02-06 01:17:58.542 ThaliTest[776:1186334] client: socket closed
,2016-02-06 01:17:58.542 ThaliTest[776:1186334] client relay: socket disconnected
,2016-02-06 01:17:58.543 ThaliTest[776:1186334] client relay: 0x19ba21a0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-02-06 01:17:5,8.543 ThaliTest[776:1186334] client session: socket closed: 1454717870061.1351.6cUd6g==
,2016-02-06 01:17:58.543 ThaliTest[776:1186334] client session: onLinkFailure: 1454717870061.1351.6cUd6g==
2016-02-06 01:17:58.544 ThaliTest[776:1186334] client session: disconnect
2016-02-06 01:17:58.544 ThaliTest[776:1186334] client session: stateChange,:2->0 1454717870061.1351.6cUd6g==
,2016-02-06 01:17:58.555 ThaliTest[776:1186334] client session: fireConnectionErrorEvent: 1454717870061.1351.6cUd6g==
,calling stopBroadcasting

,2016-02-06 01:17:58.712 ThaliTest[776:1186595] jxcore: stopBroadcasting
,2016-02-06 01:17:58.712 ThaliTest[776:1186595] THEMultipeerSession stopping peer
,2016-02-06 01:17:58.713 ThaliTest[776:1186595] multipeer session: stop timer
,2016-02-06 01:17:58.715 ThaliTest[776:1186595] client session: disconnect
,2016-02-06 01:17:58.718 ThaliTest[776:1186595] client session: stateChange:1->0 1454717866014.1351.DXC6hQ==
,2016-02-06 01:17:58.722 ThaliTest[776:1186595] server session: disconnect
,2016-02-06 01:17:58.729 ThaliTest[776:1186595] server session: stateChange:2->0 1454717870061.1351
,2016-02-06 01:17:58.746 ThaliTest[776:1186595] jxcore: stopBroadcasting: success
,stopBroadcasting returned undefined

,# setup

,# ThaliReplicationManager can call start without error

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/1A562368-65A1-42F2-B86B-3FC820769013/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,ok 131 starting event should occur in right order

,2016-02-06 01:17:59.370 ThaliTest[776:1186595] jxcore: startBroadcasting
,2016-02-06 01:17:59.371 ThaliTest[776:1186595] server: starting Zf-mP40mygTtOnEoUu9muA.Agmnjw==
2016-02-06 01:17:59.371 ThaliTest[776:1186595] multipeer session: start timer: 0x1ac15970
,2016-02-06 01:17:59.372 ThaliTest[776:1186595] THEMultipeerSession initialized peer Zf-mP40mygTtOnEoUu9muA
2016-02-06 01:17:59.372 ThaliTest[776:1186595] jxcore: startBroadcasting: success
ok 132 started event should occur in right order

Now in TRM stop

State of this._isStarted: true

,ok 133 stopping event should occur in right order

,About to call stopBroadcasting

,2016-02-06 01:17:59.373 ThaliTest[776:1186595] jxcore: stopBroadcasting
2016-02-06 01:17:59.374 ThaliTest[776:1186595] THEMultipeerSession stopping peer
2016-02-06 01:17:59.374 ThaliTest[776:1186595] multipeer session: stop timer
2016-02-06 01:17:59.374 ThaliTest[776:1186595] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

ok 134 stopped event should occur in right order

,mux server bridge listener closed

# teardown

,# setup

,# ThaliReplicationManager receives identity

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/1A562368-65A1-42F2-B86B-3FC820769013/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-02-06 01:17:59.652 ThaliTest[776:1186595] jxcore: startBroadcasting
,2016-02-06 01:17:59.654 ThaliTest[776:1186595] server: starting Zf-mP40mygTtOnEoUu9muA.Cp1vhg==
2016-02-06 01:17:59.655 ThaliTest[776:1186595] multipeer session: start timer: 0x19e61cd0
,2016-02-06 01:17:59.655 ThaliTest[776:1186595] THEMultipeerSession initialized peer Zf-mP40mygTtOnEoUu9muA
,2016-02-06 01:17:59.656 ThaliTest[776:1186595] jxcore: startBroadcasting: success
,ok 135 getDeviceIdentity should not return an error

,ok 136 deviceName should not be null

Now in TRM stop

,State of this._isStarted: true

About to call stopBroadcasting

,2016-02-06 01:17:59.659 ThaliTest[776:1186595] jxcore: stopBroadcasting
2016-02-06 01:17:59.659 ThaliTest[776:1186595] THEMultipeerSession stopping peer
2016-02-06 01:17:59.659 ThaliTest[776:1186595] multipeer session: stop timer
2016-02-06 01:17:59.659, ThaliTest[776:1186595] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,mux server bridge listener closed

# teardown

,# setup

,# ThaliReplicationManager replicates database

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/1A562368-65A1-42F2-B86B-3FC820769013/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-02-06 01:18:01.513 ThaliTest[776:1186595] jxcore: startBroadcasting
,2016-02-06 01:18:01.514 ThaliTest[776:1186595] server: starting Zf-mP40mygTtOnEoUu9muA.OiPVlg==
,2016-02-06 01:18:01.514 ThaliTest[776:1186595] multipeer session: start timer: 0x1a995240
2016-02-06 01:18:01.515 ThaliTest[776:1186595] THEMultipeerSession initialized peer Zf-mP40mygTtOnEoUu9muA
2016-02-06 01:18:01.515 ThaliTest[776:1186595] jxcore: startBroadcasting: success
ok 137 getDeviceIdentity should not return an error

,ok 138 deviceName should not be null

,2016-02-06 01:18:01.520 ThaliTest[776:1186334] client: found peer: 1454717870061.1351.6cUd6g==
,2016-02-06 01:18:05.582 ThaliTest[776:1186334] client: found peer: zQYBSF-NNOFn1bJGYdeNfQ.EpYRuw==
,2016-02-06 01:18:05.605 ThaliTest[776:1186595] jxcore: connect 1454717870061.1351.6cUd6g==
2016-02-06 01:18:05.605 ThaliTest[776:1186595] client session: connect
2016-02-06 01:18:05.605 ThaliTest[776:1186595] client session: stateChange:0->1 1454717870061.1351.6cUd6g==
,2016-02-06 01:18:05.608 ThaliTest[776:1186595] jxcore: connect zQYBSF-NNOFn1bJGYdeNfQ.EpYRuw==
2016-02-06 01:18:05.608 ThaliTest[776:1186595] client session: connect
2016-02-06 01:18:05.608 ThaliTest[776:1186595] client session: stateChange:0->1 zQYBSF-NNOFn1bJGYdeNfQ.EpYRuw==
,ok 139 Should be able to put doc without error

,ok 140 1st change of local doc should contain local id

,2016-02-06 01:18:06.449 ThaliTest[776:1186334] multipeer session: reset timer
,2016-02-06 01:18:06.450 ThaliTest[776:1186334] multipeer session: stop timer
,2016-02-06 01:18:06.450 ThaliTest[776:1186334] multipeer session: start timer: 0x1a995240
,2016-02-06 01:18:06.450 ThaliTest[776:1186334] server session: connect
2016-02-06 01:18:06.451 ThaliTest[776:1186334] server session: stateChange:0->1 zQYBSF-NNOFn1bJGYdeNfQ
,2016-02-06 01:18:06.459 ThaliTest[776:1186334] server: accepting invitation zQYBSF-NNOFn1bJGYdeNfQ
,2016-02-06 01:18:11.908 ThaliTest[776:1187244] client session: connected
2016-02-06 01:18:11.909 ThaliTest[776:1187244] client session: stateChange:1->2 zQYBSF-NNOFn1bJGYdeNfQ.EpYRuw==
,2016-02-06 01:18:11.970 ThaliTest[776:1187125] client session: fireConnectCallback: zQYBSF-NNOFn1bJGYdeNfQ.EpYRuw==
2016-02-06 01:18:11.971 ThaliTest[776:1187125] jxcore: connect: success
,2016-02-06 01:18:11.983 ThaliTest[776:1186334] client: relay established
2016-02-06 01:18:11.984 ThaliTest[776:1186334] client: new accepted socket: 0x19de6960
,client bridge: new client socket

,client bridge: new client socket

,2016-02-06 01:18:12.156 ThaliTest[776:1187125] server session: connected
2016-02-06 01:18:12.157 ThaliTest[776:1187125] server session: stateChange:1->2 zQYBSF-NNOFn1bJGYdeNfQ
,2016-02-06 01:18:12.162 ThaliTest[776:1186334] server relay: connected (to port: 54155)
server bridge: new client socket

,client bridge: socket closed

,client bridge: socket closed

,client bridge: new client socket

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

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,Uncaught Promise Rejection: {"status":400}

,Trace: { [Error: ETIMEDOUT] status: 400 }
    at $3.prototype.trace@console.js:139:8
    at @/private/var/mobile/Containers/Bundle/Application/02C6A42D-CF7F-4381-9DCD-A4B17056615E/ThaliTest.app/www/jxcore/lib/thali-tape.js:37:3
    at emit@events.js:98:,1
    at handlers.reject/<@/private/var/mobile/Containers/Bundle/Application/02C6A42D-CF7F-4381-9DCD-A4B17056615E/ThaliTest.app/www/jxcore/node_modules/lie/lib/index.js:128:11
    at nextTick@/private/var/mobile/Containers/Bundle/Application/02C6A42D-CF7,F-4381-9DCD-A4B17056615E/ThaliTest.app/www/jxcore/node_modules/lie/node_modules/immediate/lib/index.js:61:7
    at $0a@node.js:917:1

****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****


```
