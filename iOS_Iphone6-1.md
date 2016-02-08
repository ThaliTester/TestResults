#### Test 58380500055030c_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/58380500055030c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/C50755C6-9B02-4857-A650-4D64BC1C8137/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/C50755C6-9B02-4857-A650-4D64BC1C8137/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/58380500055030c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/58380500055030c/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/965F8655-47E7-4C80-85A0-A9917CF5613A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52164"
,(lldb)     command script import "/tmp/C50755C6-9B02-4857-A650-4D64BC1C8137/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-08 23:31:31.490 ThaliTest[1509:2854883] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A2D1EDD5-342A-4532-9CA9-B48CAEE259FD/Library/Cookies/Cookies.binarycookies
,2016-02-08 23:31:31.864 ThaliTest[1509:2854883] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-08 23:31:31.865 ThaliTest[1509:2854883] Multi-tasking -> Device: YES, App: YES
,2016-02-08 23:31:31.874 ThaliTest[1509:2854883] Unlimited access to network resources
,2016-02-08 23:31:31.887 ThaliTest[1509:2854883] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-08 23:31:41.837 ThaliTest[1509:2854883] Resetting plugins due to page load.
,2016-02-08 23:31:45.293 ThaliTest[1509:2854883] Finished load of: file:///var/mobile/Containers/Bundle/Application/965F8655-47E7-4C80-85A0-A9917CF5613A/ThaliTest.app/www/index.html
,2016-02-08 23:31:45.474 ThaliTest[1509:2854883] JXcore Cordova plugin initializing
2016-02-08 23:31:45.475 ThaliTest[1509:2855237] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/965F8655-47E7-4C80-85A0-A9917CF5613A/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/965F8655-47E7-4C80-85A0-A9917CF5613A/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/965F8655-47E7-4C80-85A0-A9917CF5613A/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/965F8655-47E7-4C80-85A0-A9917CF5613A/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/965F8655-47E7-4C80-85A0-A9917CF5613A/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/965F8655-47E7-4C80-85A0-A9917CF5613A/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/965F8655-47E7-4C80-85A0-A9917CF5613A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/965F8655-47E7-4C80-85A0-A9917CF5613A/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/965F8655-47E7-4C80-85A0-A9917CF5613A/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,TAP version 13

,# setup

,# #generatePreambleAndBeacons empty keys to notify

,ok 1 should be equal
,
# teardown

# setup

# #generatePreambleAndBeacons multiple keys to notify

,ok 2 should be equal

ok 3 should be equal

,ok 4 should be equal

,ok 5 should be equal

,# teardown

,# setup

,# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

,ok 6 should throw

# teardown

# setup

,# #parseBeacons invalid expiration in beaconStreamWithPreAmble

,ok 7 should throw

# teardown
,
# setup

,# #parseBeacons no beacons returns null

,ok 8 should be equal

# teardown

,# setup

,# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

,ok 9 should throw

# teardown

# setup

,# #parseBeacons addressBookCallback fails decrypt

,ok 10 should be equal

,# teardown

# setup

# #parseBeacons addressBookCallback returns null for all

,ok 11 (unnamed assert)

,ok 12 should be equal

,# teardown

,# setup

,# #parseBeacons addressBookCallback returns public key

,ok 13 (unnamed assert)

,ok 14 (unnamed assert)

,# teardown

,# setup

,# #parseBeacons with beacons both for and not for the user

,ok 15 (unnamed assert)

# teardown

,# setup

,# multiplex can send data

,ok 16 String should be length:200

,# teardown

,# setup

,# enqueue and run in order

,ok 17 firstPromise setTimeout

,ok 18 firstPromise result

,ok 19 firstPromise testValue

,ok 20 secondPromise setTimeout

,ok 21 secondPromise result

,ok 22 secondPromise testValue

,ok 23 thirdPromise in promise

,ok 24 thirdPromise result

,ok 25 thirdPromise testValue

,# teardown

,# setup

,# basic

,ok 26 sane

,# teardown

,# setup

,# another

,ok 27 sane

,# teardown

,# setup

,# successfully create a new pkcs12 file and return hash value

,ok 28 should be equal

,ok 29 null

,ok 30 (unnamed assert)

,ok 31 should be equal

,ok 32 should not throw

,# teardown

,# setup

,# successfully read a previous pkcs12 file and return hash value

,ok 33 (unnamed assert)

,ok 34 (unnamed assert)

ok 35 should not throw

,ok 36 should be equal

ok 37 should be equal

,# teardown

,# setup

,# failed to extract public key because of corrupt pkcs12 file

,ok 38 should be equal

,# teardown

,# setup

,# failed to get mobile documents path

,ok 39 should be equal

,# teardown

,# setup

,# #init should register the peerAvailabilityChanged event

,ok 40 should be equal

,ok 41 should be equal

,ok 42 should be equal

,# teardown

,# setup

,# #init should register the networkChanged event

,ok 43 should be equal

,# teardown

,# setup

,# #startBroadcasting should throw on null device name

,ok 44 should throw

,# teardown

,# setup

,# #startBroadcasting should throw on empty string device name

,ok 45 should throw

,# teardown

,# setup

,# #startBroadcasting should throw on non-number port

,ok 46 should throw

,# teardown

,# setup

,# #startBroadcasting should throw on NaN port

,ok 47 should throw

,# teardown

,# setup

,# #startBroadcasting should throw on negative port

,ok 48 should throw

,# teardown

,# setup

,# #startBroadcasting should throw on too large port

,ok 49 should throw

,# teardown

,# setup

,# #startBroadcasting should call Mobile("StartBroadcasting") without an error

,ok 50 should be equal

,ok 51 should be equal

,ok 52 should be equal

,# teardown

,# setup

,# #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

,ok 53 should be equal

,ok 54 should be equal

,ok 55 should be equal

,# teardown

,# setup

,# #stopBroadcasting should call Mobile("StopBroadcasting") without an error

,ok 56 should be equal

,ok 57 should be equal

,# teardown

,# setup

,# #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

,ok 58 should be equal

,ok 59 should be equal

,# teardown

,# setup

,# #connect should call Mobile("Connect") with a port and without an error

,ok 60 should be equal

,ok 61 should be equal

,ok 62 should be equal

,# teardown

,# setup

,# #connect should call Mobile("Connect") and handle an error

,ok 63 should be equal

ok 64 should be equal

,# teardown

,# setup

,# should call Mobile("Disconnect") without an error

,ok 65 should be equal

,ok 66 should be equal

,# teardown

,# setup

,# should call Mobile("Disconnect") and handle an error

,ok 67 should be equal

,ok 68 should be equal

,# teardown

,# setup

,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

,2016-02-08 23:36:26.520 ThaliTest[1509:2855237] jxcore: startBroadcasting
,2016-02-08 23:36:26.534 ThaliTest[1509:2855237] server: starting 1454970986519.1509.WSVDVw==
,2016-02-08 23:36:26.535 ThaliTest[1509:2855237] multipeer session: start timer: 0x170a1890
,2016-02-08 23:36:26.537 ThaliTest[1509:2855237] THEMultipeerSession initialized peer 1454970986519.1509
2016-02-08 23:36:26.537 ThaliTest[1509:2855237] jxcore: startBroadcasting: success
,ok 69 Should be able to call startBroadcasting without error

,2016-02-08 23:36:26.542 ThaliTest[1509:2855237] jxcore: stopBroadcasting
2016-02-08 23:36:26.542 ThaliTest[1509:2855237] THEMultipeerSession stopping peer
2016-02-08 23:36:26.542 ThaliTest[1509:2855237] multipeer session: stop timer
2016-02-08 23:36:26.543 ThaliTest[1509:2855237] jxcore: stopBroadcasting: success
ok 70 Should be able to call stopBroadcasting without error

2016-02-08 23:36:26.547 ThaliTest[1509:2855237] jxcore: startBroadcasting
,2016-02-08 23:36:26.557 ThaliTest[1509:2855237] server: starting 1454970986546.1509.P9xjiQ==
2016-02-08 23:36:26.558 ThaliTest[1509:2855237] multipeer session: start timer: 0x14ddf130
2016-02-08 23:36:26.559 ThaliTest[1509:2855237] THEMultipeerSession initialized peer 1454970986546.1509
,2016-02-08 23:36:26.559 ThaliTest[1509:2855237] jxcore: startBroadcasting: success
ok 71 Should be able to call startBroadcasting without error

2016-02-08 23:36:26.568 ThaliTest[1509:2855237] jxcore: stopBroadcasting
2016-02-08 23:36:26.569 ThaliTest[,1509:2855237] THEMultipeerSession stopping peer
2016-02-08 23:36:26.569 ThaliTest[1509:2855237] multipeer session: stop timer
2016-02-08 23:36:26.570 ThaliTest[1509:2855237] jxcore: stopBroadcasting: success
ok 72 Should be able to call stopBroadcasting without error

2016-02-08 23:36:26.571 ThaliTest[1509:2855237] jxcore: startBroadcasting
,2016-02-08 23:36:26.581 ThaliTest[1509:2855237] server: starting 1454970986571.1509.6jGxAA==
2016-02-08 23:36:26.581 ThaliTest[1509:2855237] multipeer session: start timer: 0x14ddfce0
2016-02-08 23:36:26.582 ThaliTest[1509:2855237] THEMultipeerSession in,itialized peer 1454970986571.1509
2016-02-08 23:36:26.582 ThaliTest[1509:2855237] jxcore: startBroadcasting: success
ok 73 Should be able to call startBroadcasting without error

,2016-02-08 23:36:26.585 ThaliTest[1509:2855237] jxcore: stopBroadcasting
2016-02-08 23:36:26.585 ThaliTest[1509:2855237] THEMultipeerSession stopping peer
,2016-02-08 23:36:26.586 ThaliTest[1509:2855237] multipeer session: stop timer
,2016-02-08 23:36:26.587 ThaliTest[1509:2855237] jxcore: stopBroadcasting: success
ok 74 Should be able to call stopBroadcasting without error

2016-02-08 23:36:26.590 ThaliTest[1509:2855237] jxcore: startBroadcasting
,2016-02-08 23:36:26.601 ThaliTest[1509:2855237] server: starting 1454970986589.1509.m7dhBg==
2016-02-08 23:36:26.602 ThaliTest[1509:2855237] multipeer session: start timer: 0x14ef26e0
2016-02-08 23:36:26.603 ThaliTest[1509:2855237] THEMultipeerSession in,itialized peer 1454970986589.1509
2016-02-08 23:36:26.603 ThaliTest[1509:2855237] jxcore: startBroadcasting: success
ok 75 Should be able to call startBroadcasting without error

2016-02-08 23:36:26.605 ThaliTest[1509:2855237] jxcore: stopBroadcasting,
2016-02-08 23:36:26.606 ThaliTest[1509:2855237] THEMultipeerSession stopping peer
2016-02-08 23:36:26.606 ThaliTest[1509:2855237] multipeer session: stop timer
2016-02-08 23:36:26.606 ThaliTest[1509:2855237] jxcore: stopBroadcasting: success
ok 76 Shou,ld be able to call stopBroadcasting without error

,2016-02-08 23:36:26.608 ThaliTest[1509:2855237] jxcore: startBroadcasting
,2016-02-08 23:36:26.613 ThaliTest[1509:2855237] server: starting 1454970986608.1509.ClG6zw==
2016-02-08 23:36:26.614 ThaliTest[1509:2855237] multipeer session: start timer: 0x174c3bf0
2016-02-08 23:36:26.614 ThaliTest[1509:2855237] THEMultipeerSession initialized peer 1454970986608.1509
2016-02-08 23:36:26.618 ThaliTest[1509:2855237] jxcore: startBroadcasting: success
ok 77 Should be able to call startBroadcasting without error

2016-02-08 23:36:26.619 ThaliTest[1509:2855237] jxcore: stopBroadcasting,
2016-02-08 23:36:26.620 ThaliTest[1509:2855237] THEMultipeerSession stopping peer
2016-02-08 23:36:26.620 ThaliTest[1509:2855237] multipeer session: stop timer
2016-02-08 23:36:26.620 ThaliTest[1509:2855237] jxcore: stopBroadcasting: success
ok 78 Shou,ld be able to call stopBroadcasting without error

2016-02-08 23:36:26.622 ThaliTest[1509:2855237] jxcore: startBroadcasting
,2016-02-08 23:36:26.632 ThaliTest[1509:2855237] server: starting 1454970986621.1509.feqsfA==
,2016-02-08 23:36:26.634 ThaliTest[1509:2855237] multipeer session: start timer: 0x165d5280
2016-02-08 23:36:26.636 ThaliTest[1509:2855237] THEMultipeerSession initialized peer 1454970986621.1509
2016-02-08 23:36:26.637 ThaliTest[1509:2855237] jxcore: sta,rtBroadcasting: success
ok 79 Should be able to call startBroadcasting without error

2016-02-08 23:36:26.638 ThaliTest[1509:2855237] jxcore: stopBroadcasting
2016-02-08 23:36:26.638 ThaliTest[1509:2855237] THEMultipeerSession stopping peer
2016-02-08, 23:36:26.638 ThaliTest[1509:2855237] multipeer session: stop timer
2016-02-08 23:36:26.639 ThaliTest[1509:2855237] jxcore: stopBroadcasting: success
ok 80 Should be able to call stopBroadcasting without error

2016-02-08 23:36:26.640 ThaliTest[1509:28,55237] jxcore: startBroadcasting
,2016-02-08 23:36:26.646 ThaliTest[1509:2855237] server: starting 1454970986640.1509.ucT1RA==
2016-02-08 23:36:26.646 ThaliTest[1509:2855237] multipeer session: start timer: 0x165d5370
2016-02-08 23:36:26.647 ThaliTest[1509:2855237] THEMultipeerSession initialized peer 1454970986640.1509
,2016-02-08 23:36:26.647 ThaliTest[1509:2855237] jxcore: startBroadcasting: success
ok 81 Should be able to call startBroadcasting without error

2016-02-08 23:36:26.652 ThaliTest[1509:2855237] jxcore: stopBroadcasting
2016-02-08 23:36:26.653 ThaliTest[,1509:2855237] THEMultipeerSession stopping peer
2016-02-08 23:36:26.653 ThaliTest[1509:2855237] multipeer session: stop timer
2016-02-08 23:36:26.653 ThaliTest[1509:2855237] jxcore: stopBroadcasting: success
ok 82 Should be able to call stopBroadcasting, without error

2016-02-08 23:36:26.654 ThaliTest[1509:2855237] jxcore: startBroadcasting
,2016-02-08 23:36:26.665 ThaliTest[1509:2855237] server: starting 1454970986654.1509.tt0kLA==
,2016-02-08 23:36:26.667 ThaliTest[1509:2855237] multipeer session: start timer: 0x165d6980
,2016-02-08 23:36:26.669 ThaliTest[1509:2855237] THEMultipeerSession initialized peer 1454970986654.1509
,2016-02-08 23:36:26.672 ThaliTest[1509:2855237] jxcore: startBroadcasting: success
,ok 83 Should be able to call startBroadcasting without error
,
,2016-02-08 23:36:26.677 ThaliTest[1509:2855237] jxcore: stopBroadcasting
,2016-02-08 23:36:26.678 ThaliTest[1509:2855237] THEMultipeerSession stopping peer
,2016-02-08 23:36:26.679 ThaliTest[1509:2855237] multipeer session: stop timer
,2016-02-08 23:36:26.681 ThaliTest[1509:2855237] jxcore: stopBroadcasting: success
,ok 84 Should be able to call stopBroadcasting without error
,
,2016-02-08 23:36:26.686 ThaliTest[1509:2855237] jxcore: startBroadcasting
,2016-02-08 23:36:26.689 ThaliTest[1509:2855237] server: starting 1454970986686.1509.AbQmxw==
,2016-02-08 23:36:26.691 ThaliTest[1509:2855237] multipeer session: start timer: 0x14ef1d50
,2016-02-08 23:36:26.694 ThaliTest[1509:2855237] THEMultipeerSession initialized peer 1454970986686.1509
,2016-02-08 23:36:26.697 ThaliTest[1509:2855237] jxcore: startBroadcasting: success
,ok 85 Should be able to call startBroadcasting without error

,2016-02-08 23:36:26.700 ThaliTest[1509:2855237] jxcore: stopBroadcasting
,2016-02-08 23:36:26.701 ThaliTest[1509:2855237] THEMultipeerSession stopping peer
,2016-02-08 23:36:26.701 ThaliTest[1509:2855237] multipeer session: stop timer
,2016-02-08 23:36:26.704 ThaliTest[1509:2855237] jxcore: stopBroadcasting: success
,ok 86 Should be able to call stopBroadcasting without error
,
,2016-02-08 23:36:26.708 ThaliTest[1509:2855237] jxcore: startBroadcasting
,2016-02-08 23:36:26.710 ThaliTest[1509:2855237] server: starting 1454970986707.1509.Lp+kVA==
,2016-02-08 23:36:26.711 ThaliTest[1509:2855237] multipeer session: start timer: 0x165d6260
,2016-02-08 23:36:26.713 ThaliTest[1509:2855237] THEMultipeerSession initialized peer 1454970986707.1509
,2016-02-08 23:36:26.716 ThaliTest[1509:2855237] jxcore: startBroadcasting: success
,ok 87 Should be able to call startBroadcasting without error

,2016-02-08 23:36:26.721 ThaliTest[1509:2855237] jxcore: stopBroadcasting
,2016-02-08 23:36:26.722 ThaliTest[1509:2855237] THEMultipeerSession stopping peer
,2016-02-08 23:36:26.723 ThaliTest[1509:2855237] multipeer session: stop timer
,2016-02-08 23:36:26.723 ThaliTest[1509:2855237] jxcore: stopBroadcasting: success
,ok 88 Should be able to call stopBroadcasting without error

,# teardown

,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,2016-02-08 23:36:27.318 ThaliTest[1509:2855237] jxcore: startBroadcasting
,2016-02-08 23:36:27.322 ThaliTest[1509:2855237] server: starting 1454970987318.1509.ImKELQ==
2016-02-08 23:36:27.323 ThaliTest[1509:2855237] multipeer session: start timer: 0x163895a0
2016-02-08 23:36:27.323 ThaliTest[1509:2855237] THEMultipeerSession in,itialized peer 1454970987318.1509
2016-02-08 23:36:27.323 ThaliTest[1509:2855237] jxcore: startBroadcasting: success
ok 89 Should be able to call startBroadcasting without error

2016-02-08 23:36:27.326 ThaliTest[1509:2855237] jxcore: startBroadcasting
2016-02-08 23:36:27.326 ThaliTest[1509:2855237] jxcore: startBroadcasting: failure
,ok 90 Cannot call startBroadcasting twice

2016-02-08 23:36:27.329 ThaliTest[1509:2855237] jxcore: stopBroadcasting
,2016-02-08 23:36:27.331 ThaliTest[1509:2855237] THEMultipeerSession stopping peer
,2016-02-08 23:36:27.331 ThaliTest[1509:2855237] multipeer session: stop timer
,2016-02-08 23:36:27.332 ThaliTest[1509:2855237] jxcore: stopBroadcasting: success
ok 91 Should be able to call stopBroadcasting without error

,# teardown

,# setup

,# ThaliEmitter throws on connection to bad peer

,2016-02-08 23:36:27.432 ThaliTest[1509:2855237] jxcore: startBroadcasting
,2016-02-08 23:36:27.437 ThaliTest[1509:2855237] server: starting 1454970987432.1509.dgjrHA==
2016-02-08 23:36:27.437 ThaliTest[1509:2855237] multipeer session: start timer: 0x16389d60
2016-02-08 23:36:27.438 ThaliTest[1509:2855237] THEMultipeerSession in,itialized peer 1454970987432.1509
2016-02-08 23:36:27.438 ThaliTest[1509:2855237] jxcore: startBroadcasting: success
ok 92 Should be able to call startBroadcasting without error

2016-02-08 23:36:27.440 ThaliTest[1509:2855237] jxcore: connect foobar
2,016-02-08 23:36:27.441 ThaliTest[1509:2855237] client: unknown peer foobar
2016-02-08 23:36:27.442 ThaliTest[1509:2855237] jxcore: connect: fail: Unknown peer
,ok 93 Should not connect to a bad peer

2016-02-08 23:36:27.446 ThaliTest[1509:2855237] jxcore: stopBroadcasting
2016-02-08 23:36:27.446 ThaliTest[1509:2855237] THEMultipeerSession stopping peer
2016-02-08 23:36:27.446 ThaliTest[1509:2855237] multipeer, session: stop timer
2016-02-08 23:36:27.447 ThaliTest[1509:2855237] jxcore: stopBroadcasting: success
ok 94 Should be able to call stopBroadcasting without error

,# teardown

,# setup

,# ThaliEmitter throws on disconnect to bad peer

,2016-02-08 23:36:27.534 ThaliTest[1509:2855237] jxcore: startBroadcasting
,2016-02-08 23:36:27.537 ThaliTest[1509:2855237] server: starting 1454970987533.1509.gWgG9Q==
2016-02-08 23:36:27.538 ThaliTest[1509:2855237] multipeer session: start timer: 0x1623ffc0
2016-02-08 23:36:27.538 ThaliTest[1509:2855237] THEMultipeerSession in,itialized peer 1454970987533.1509
2016-02-08 23:36:27.539 ThaliTest[1509:2855237] jxcore: startBroadcasting: success
ok 95 Should be able to call startBroadcasting without error

2016-02-08 23:36:27.541 ThaliTest[1509:2855237] jxcore: disconnect
2016-02-08 23:36:27.541 ThaliTest[1509:2855237] jxcore: disconnect: fail
,ok 96 Disconnect should fail to a non-existant peer 

,2016-02-08 23:36:27.545 ThaliTest[1509:2855237] jxcore: stopBroadcasting
2016-02-08 23:36:27.546 ThaliTest[1509:2855237] THEMultipeerSession stopping peer
2016-02-08 23:36:27.546 ThaliTest[1509:2855237] multipeer session: stop timer
2016-02-08 23:36:27.547 ThaliTest[1509:2855237] jxcore: stopBroadcasting: success
,ok 97 Should be able to call stopBroadcasting without error

,# teardown

,# setup

,# ThaliEmitter can discover and connect to peers

,2016-02-08 23:36:27.898 ThaliTest[1509:2855237] jxcore: startBroadcasting
,2016-02-08 23:36:27.902 ThaliTest[1509:2855237] server: starting 1454970987898.1509.hEBz8w==
,2016-02-08 23:36:27.905 ThaliTest[1509:2855237] multipeer session: start timer: 0x16553250
,2016-02-08 23:36:27.914 ThaliTest[1509:2855237] THEMultipeerSession initialized peer 1454970987898.1509
,2016-02-08 23:36:27.916 ThaliTest[1509:2855237] jxcore: startBroadcasting: success
,ok 98 Should be able to call startBroadcasting without error

,2016-02-08 23:36:29.195 ThaliTest[1509:2854883] client: found peer: 1454970988484.963.uK8uJQ==
,2016-02-08 23:36:29.199 ThaliTest[1509:2855237] jxcore: connect 1454970988484.963.uK8uJQ==
2016-02-08 23:36:29.199 ThaliTest[1509:2855237] client session: connect
2016-02-08 23:36:29.199 ThaliTest[1509:2855237] client session: stateChange:0->1 1454970988484.963.uK8uJQ==
,2016-02-08 23:36:29.585 ThaliTest[1509:2854883] multipeer session: reset timer
2016-02-08 23:36:29.585 ThaliTest[1509:2854883] multipeer session: stop timer
2016-02-08 23:36:29.585 ThaliTest[1509:2854883] multipeer session: start timer: 0x16553250
2016-,02-08 23:36:29.586 ThaliTest[1509:2854883] server session: connect
2016-02-08 23:36:29.586 ThaliTest[1509:2854883] server session: stateChange:0->1 1454970988484.963
,2016-02-08 23:36:29.596 ThaliTest[1509:2854883] server: accepting invitation 1454970988484.963
,2016-02-08 23:36:32.062 ThaliTest[1509:2855737] server session: connected
2016-02-08 23:36:32.062 ThaliTest[1509:2855737] server session: stateChange:1->2 1454970988484.963
,2016-02-08 23:36:32.081 ThaliTest[1509:2854883] server relay: socket disconnected
2016-02-08 23:36:32.082 ThaliTest[1509:2854883] server relay: 0x1702a460 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-08 23:36:32.146 ThaliTest[1509:2855744] server session: not connected 1454970988484.963
,2016-02-08 23:36:32.372 ThaliTest[1509:2855744] client session: connected
2016-02-08 23:36:32.372 ThaliTest[1509:2855744] client session: stateChange:1->2 1454970988484.963.uK8uJQ==
,2016-02-08 23:36:32.405 ThaliTest[1509:2855737] client session: fireConnectCallback: 1454970988484.963.uK8uJQ==
2016-02-08 23:36:32.406 ThaliTest[1509:2855737] jxcore: connect: success
,ok 99 Should be able to connect without error

,ok 100 Port should be within range

,2016-02-08 23:36:32.411 ThaliTest[1509:2855237] jxcore: disconnect
2016-02-08 23:36:32.411 ThaliTest[1509:2855237] client session: disconnectFromPeer: 1454970988484.963.uK8uJQ==
2016-02-08 23:36:32.412 ThaliTest[1509:2855237] client session: disconnect
2016-02-08 23:36:32.412 ThaliTest[1509:2855237] client session: stateChange:2->0 1454970988484.963.uK8uJQ==
,2016-02-08 23:36:32.427 ThaliTest[1509:2855237] jxcore: disconnect: success
ok 101 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# teardown

,calling stopBroadcasting

,2016-02-08 23:36:32.676 ThaliTest[1509:2855237] jxcore: stopBroadcasting
2016-02-08 23:36:32.677 ThaliTest[1509:2855237] THEMultipeerSession stopping peer
2016-02-08 23:36:32.677 ThaliTest[1509:2855237] multipeer session: stop timer
2016-02-08 23:36:32.,677 ThaliTest[1509:2855237] server session: disconnect
2016-02-08 23:36:32.678 ThaliTest[1509:2855237] server session: stateChange:2->0 1454970988484.963
2016-02-08 23:36:32.679 ThaliTest[1509:2855237] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# setup

,# ThaliEmitter can discover and connect to peers and then fail on double connect

,2016-02-08 23:36:32.752 ThaliTest[1509:2855237] jxcore: startBroadcasting
,2016-02-08 23:36:32.755 ThaliTest[1509:2855237] server: starting 1454970992751.1509.ZxVHkA==
,2016-02-08 23:36:32.758 ThaliTest[1509:2855237] multipeer session: start timer: 0x14d9df80
2016-02-08 23:36:32.762 ThaliTest[1509:2855237] THEMultipeerSession initialized peer 1454970992751.1509
,2016-02-08 23:36:32.763 ThaliTest[1509:2855237] jxcore: startBroadcasting: success
ok 102 Should be able to call startBroadcasting without error

,2016-02-08 23:36:33.541 ThaliTest[1509:2854883] client: found peer: 1454970988484.963.uK8uJQ==
2016-02-08 23:36:33.543 ThaliTest[1509:2855237] jxcore: connect 1454970988484.963.uK8uJQ==
2016-02-08 23:36:33.543 ThaliTest[1509:2854883] client: found peer: ,1454970987898.1509.hEBz8w==
2016-02-08 23:36:33.543 ThaliTest[1509:2855237] client session: connect
2016-02-08 23:36:33.543 ThaliTest[1509:2855237] client session: stateChange:0->1 1454970988484.963.uK8uJQ==
,2016-02-08 23:36:33.558 ThaliTest[1509:2855237] jxcore: connect 1454970987898.1509.hEBz8w==
2016-02-08 23:36:33.558 ThaliTest[1509:2855237] client session: connect
2016-02-08 23:36:33.558 ThaliTest[1509:2855237] client session: stateChange:0->1 145497098,7898.1509.hEBz8w==
,2016-02-08 23:36:34.666 ThaliTest[1509:2854883] client: lost peer: 1454970987898.1509.hEBz8w==
2016-02-08 23:36:34.666 ThaliTest[1509:2854883] client session: onPeerLost: 1454970987898.1509.hEBz8w==
2016-02-08 23:36:34.666 ThaliTest[1509:2854883] client ,session: onLinkFailure: 1454970987898.1509.hEBz8w==
2016-02-08 23:36:34.666 ThaliTest[1509:2854883] client session: disconnect
2016-02-08 23:36:34.667 ThaliTest[1509:2854883] client session: stateChange:1->0 1454970987898.1509.hEBz8w==
2016-02-08 23:36:,34.667 ThaliTest[1509:2854883] client session: fireConnectCallback: 1454970987898.1509.hEBz8w==
2016-02-08 23:36:34.668 ThaliTest[1509:2854883] jxcore: connect: fail: Peer disconnected
2016-02-08 23:36:34.669 ThaliTest[1509:2854883] client: found peer: 1,454970993328.963.0wLGOA==
2016-02-08 23:36:34.671 ThaliTest[1509:2855237] jxcore: connect 1454970993328.963.0wLGOA==
2016-02-08 23:36:34.671 ThaliTest[1509:2855237] client session: connect
2016-02-08 23:36:34.672 ThaliTest[1509:2855237] client session: ,stateChange:0->1 1454970993328.963.0wLGOA==
,2016-02-08 23:36:34.958 ThaliTest[1509:2854883] multipeer session: reset timer
2016-02-08 23:36:34.958 ThaliTest[1509:2854883] multipeer session: stop timer
2016-02-08 23:36:34.959 ThaliTest[1509:2854883] multipeer session: start timer: 0x14d9df80
2016-02-08 23:36:34.959 ThaliTest[1509:2854883] server session: connect
2016-02-08 23:36:34.960 ThaliTest[1509:2854883] server session: stateChange:0->1 1454970993328.963
,2016-02-08 23:36:34.969 ThaliTest[1509:2854883] server: accepting invitation 1454970993328.963
,2016-02-08 23:36:35.681 ThaliTest[1509:2855237] jxcore: connect 1454970987898.1509.hEBz8w==
2016-02-08 23:36:35.681 ThaliTest[1509:2855237] client: connect: unreachable 1454970987898.1509.hEBz8w==
2016-02-08 23:36:35.682 ThaliTest[1509:2855237] jxcore: connect: fail: Peer unreachable
,2016-02-08 23:36:37.402 ThaliTest[1509:2855744] client session: connected
,2016-02-08 23:36:37.404 ThaliTest[1509:2855744] client session: stateChange:1->2 1454970993328.963.0wLGOA==
,2016-02-08 23:36:37.412 ThaliTest[1509:2855744] client session: fireConnectCallback: 1454970993328.963.0wLGOA==
,2016-02-08 23:36:37.414 ThaliTest[1509:2855744] jxcore: connect: success
,ok 103 Should be able to connect without error

,ok 104 Port should be within range

,2016-02-08 23:36:37.420 ThaliTest[1509:2855237] jxcore: connect 1454970993328.963.0wLGOA==
,2016-02-08 23:36:37.421 ThaliTest[1509:2855237] client: already connect(ing/ed) to 1454970993328.963.0wLGOA==
,2016-02-08 23:36:37.426 ThaliTest[1509:2855237] jxcore: connect: fail: Aleady connecting
,ok 105 Should fail on double connect

,2016-02-08 23:36:37.431 ThaliTest[1509:2855237] jxcore: disconnect
,2016-02-08 23:36:37.433 ThaliTest[1509:2855237] client session: disconnectFromPeer: 1454970993328.963.0wLGOA==
,2016-02-08 23:36:37.435 ThaliTest[1509:2855237] client session: disconnect
,2016-02-08 23:36:37.437 ThaliTest[1509:2855237] client session: stateChange:2->0 1454970993328.963.0wLGOA==
,2016-02-08 23:36:37.465 ThaliTest[1509:2855237] jxcore: disconnect: success
,ok 106 Should be able to disconnect without error

,setting stopBroadcasting callback and ending test.

,# teardown

,2016-02-08 23:36:37.552 ThaliTest[1509:2855737] server session: connected
,2016-02-08 23:36:37.553 ThaliTest[1509:2855737] server session: stateChange:1->2 1454970993328.963
,2016-02-08 23:36:37.559 ThaliTest[1509:2854883] server relay: socket disconnected
,2016-02-08 23:36:37.559 ThaliTest[1509:2854883] server relay: 0x17475f50 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection ,refused} 
,2016-02-08 23:36:37.639 ThaliTest[1509:2855743] server session: not connected 1454970993328.963
,calling stopBroadcasting

,2016-02-08 23:36:37.936 ThaliTest[1509:2855237] jxcore: stopBroadcasting
2016-02-08 23:36:37.937 ThaliTest[1509:2855237] THEMultipeerSession stopping peer
2016-02-08 23:36:37.937 ThaliTest[1509:2855237] multipeer session: stop timer
2016-02-08 23:36:37.,937 ThaliTest[1509:2855237] client session: disconnect
2016-02-08 23:36:37.937 ThaliTest[1509:2855237] client session: stateChange:1->0 1454970988484.963.uK8uJQ==
2016-02-08 23:36:37.938 ThaliTest[1509:2855237] server session: disconnect
2016-02-08 23:3,6:37.938 ThaliTest[1509:2855237] server session: stateChange:2->0 1454970993328.963
2016-02-08 23:36:37.939 ThaliTest[1509:2855237] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# setup

,# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,2016-02-08 23:36:38.347 ThaliTest[1509:2855237] jxcore: startBroadcasting
,2016-02-08 23:36:38.351 ThaliTest[1509:2855237] server: starting 1454970998347.1509.1R+vrA==
2016-02-08 23:36:38.352 ThaliTest[1509:2855237] multipeer session: start timer: 0x14e05690
2016-02-08 23:36:38.353 ThaliTest[1509:2855237] THEMultipeerSession in,itialized peer 1454970998347.1509
2016-02-08 23:36:38.353 ThaliTest[1509:2855237] jxcore: startBroadcasting: success
ok 107 Should be able to call startBroadcasting without error

,2016-02-08 23:36:39.182 ThaliTest[1509:2854883] client: found peer: 1454970993328.963.0wLGOA==
2016-02-08 23:36:39.184 ThaliTest[1509:2855237] jxcore: connect 1454970993328.963.0wLGOA==
2016-02-08 23:36:39.184 ThaliTest[1509:2855237] client session: conn,ect
2016-02-08 23:36:39.185 ThaliTest[1509:2855237] client session: stateChange:0->1 1454970993328.963.0wLGOA==
,2016-02-08 23:36:39.392 ThaliTest[1509:2854883] client: found peer: 1454970998920.963.poLk/Q==
,2016-02-08 23:36:39.394 ThaliTest[1509:2855237] jxcore: connect 1454970998920.963.poLk/Q==
2016-02-08 23:36:39.394 ThaliTest[1509:2855237] client session: connect
,2016-02-08 23:36:39.395 ThaliTest[1509:2855237] client session: stateChange:0->1 1454970998920.963.poLk/Q==
,2016-02-08 23:36:40.205 ThaliTest[1509:2854883] multipeer session: reset timer
2016-02-08 23:36:40.205 ThaliTest[1509:2854883] multipeer session: stop timer
2016-02-08 23:36:40.206 ThaliTest[1509:2854883] multipeer session: start timer: 0x14e05690
2016-,02-08 23:36:40.206 ThaliTest[1509:2854883] server session: connect
2016-02-08 23:36:40.206 ThaliTest[1509:2854883] server session: stateChange:0->1 1454970998920.963
,2016-02-08 23:36:40.217 ThaliTest[1509:2854883] server: accepting invitation 1454970998920.963
,2016-02-08 23:36:42.549 ThaliTest[1509:2855735] server session: connected
2016-02-08 23:36:42.549 ThaliTest[1509:2855735] server session: stateChange:1->2 1454970998920.963
,2016-02-08 23:36:42.567 ThaliTest[1509:2854883] server relay: socket disconnected
2016-02-08 23:36:42.568 ThaliTest[1509:2854883] server relay: 0x16390ac0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-08 23:36:42.724 ThaliTest[1509:2855745] server session: not connected 1454970998920.963
,2016-02-08 23:36:46.067 ThaliTest[1509:2855745] client session: connected
2016-02-08 23:36:46.067 ThaliTest[1509:2855745] client session: stateChange:1->2 1454970998920.963.poLk/Q==
2016-02-08 23:36:46.070 ThaliTest[1509:2855745] client session: fireConn,ectCallback: 1454970998920.963.poLk/Q==
2016-02-08 23:36:46.070 ThaliTest[1509:2855745] jxcore: connect: success
ok 108 Should be able to connect without error

,ok 109 Port should be within range

,2016-02-08 23:36:46.075 ThaliTest[1509:2855237] jxcore: disconnect
2016-02-08 23:36:46.075 ThaliTest[1509:2855237] client session: disconnectFromPeer: 1454970998920.963.poLk/Q==
,2016-02-08 23:36:46.075 ThaliTest[1509:2855237] client session: disconnect
2016-02-08 23:36:46.077 ThaliTest[1509:2855237] client session: stateChange:2->0 1454970998920.963.poLk/Q==
,2016-02-08 23:36:46.155 ThaliTest[1509:2855237] jxcore: disconnect: success
ok 110 Should be able to disconnect without error

,2016-02-08 23:36:46.157 ThaliTest[1509:2855237] jxcore: disconnect
,2016-02-08 23:36:46.158 ThaliTest[1509:2855237] jxcore: disconnect: fail
,ok 111 Disconnect should fail 

setting stopBroadcasting callback and ending test.

,# teardown

,calling stopBroadcasting

,2016-02-08 23:36:46.305 ThaliTest[1509:2855237] jxcore: stopBroadcasting
2016-02-08 23:36:46.306 ThaliTest[1509:2855237] THEMultipeerSession stopping peer
2016-02-08 23:36:46.306 ThaliTest[1509:2855237] multipeer session: stop timer
2016-02-08 23:36:46.,307 ThaliTest[1509:2855237] client session: disconnect
2016-02-08 23:36:46.307 ThaliTest[1509:2855237] client session: stateChange:1->0 1454970993328.963.0wLGOA==
2016-02-08 23:36:46.308 ThaliTest[1509:2855237] server session: disconnect
2016-02-08 23:3,6:46.308 ThaliTest[1509:2855237] server session: stateChange:2->0 1454970998920.963
2016-02-08 23:36:46.309 ThaliTest[1509:2855237] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# setup

,# ThaliEmitter can connect and send data

,echo server started on port: 58554

,2016-02-08 23:36:48.469 ThaliTest[1509:2855237] jxcore: startBroadcasting
,2016-02-08 23:36:48.471 ThaliTest[1509:2855237] server: starting 1454971008469.1509.LeNrqg==
,2016-02-08 23:36:48.473 ThaliTest[1509:2855237] multipeer session: start timer: 0x16552fa0
,2016-02-08 23:36:48.476 ThaliTest[1509:2855237] THEMultipeerSession initialized peer 1454971008469.1509
,2016-02-08 23:36:48.477 ThaliTest[1509:2855237] jxcore: startBroadcasting: success
,ok 112 Should be able to call startBroadcasting without error

,2016-02-08 23:36:49.575 ThaliTest[1509:2854883] client: found peer: 1454971008989.963.vzmIcg==
2016-02-08 23:36:49.577 ThaliTest[1509:2855237] jxcore: connect 1454971008989.963.vzmIcg==
2016-02-08 23:36:49.577 ThaliTest[1509:2855237] client session: conn,ect
2016-02-08 23:36:49.578 ThaliTest[1509:2855237] client session: stateChange:0->1 1454971008989.963.vzmIcg==
,2016-02-08 23:36:51.370 ThaliTest[1509:2854883] multipeer session: reset timer
2016-02-08 23:36:51.370 ThaliTest[1509:2854883] multipeer session: stop timer
2016-02-08 23:36:51.371 ThaliTest[1509:2854883] multipeer session: start timer: 0x16552fa0
2016-,02-08 23:36:51.371 ThaliTest[1509:2854883] server session: connect
2016-02-08 23:36:51.371 ThaliTest[1509:2854883] server session: stateChange:0->1 1454971008989.963
2016-02-08 23:36:51.380 ThaliTest[1509:2854883] server: accepting invitation 14549710089,89.963
,2016-02-08 23:36:52.339 ThaliTest[1509:2855743] client session: connected
2016-02-08 23:36:52.339 ThaliTest[1509:2855743] client session: stateChange:1->2 1454971008989.963.vzmIcg==
,2016-02-08 23:36:52.352 ThaliTest[1509:2855735] client session: fireConnectCallback: 1454971008989.963.vzmIcg==
2016-02-08 23:36:52.352 ThaliTest[1509:2855735] jxcore: connect: success
,ok 113 Should be able to connect without error

,ok 114 Port should be within range

,2016-02-08 23:36:52.360 ThaliTest[1509:2854883] client: relay established
2016-02-08 23:36:52.361 ThaliTest[1509:2854883] client: new accepted socket: 0x16326b40
,data in 12288

,data in 27375

,data in 39136

,data in 58035

,data in 66795

data in 78840

,data in 83220

,data in 84315

,data in 96360

,data in 102930

,data in 118260

,data in 131072

,ok 115 the test messages should be equal

,2016-02-08 23:36:52.642 ThaliTest[1509:2855237] jxcore: disconnect
,2016-02-08 23:36:52.642 ThaliTest[1509:2855237] client session: disconnectFromPeer: 1454971008989.963.vzmIcg==
,2016-02-08 23:36:52.643 ThaliTest[1509:2855237] client session: disconnect
,2016-02-08 23:36:52.643 ThaliTest[1509:2855237] client session: stateChange:2->0 1454971008989.963.vzmIcg==
,2016-02-08 23:36:52.650 ThaliTest[1509:2855237] jxcore: disconnect: success
,ok 116 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.
,
,# teardown

,2016-02-08 23:36:54.244 ThaliTest[1509:2855737] server session: connected
2016-02-08 23:36:54.244 ThaliTest[1509:2855737] server session: stateChange:1->2 1454971008989.963
,2016-02-08 23:36:54.291 ThaliTest[1509:2854883] server relay: connected (to port: 58554)
,2016-02-08 23:36:55.996 ThaliTest[1509:2855737] server session: not connected 1454971008989.963
,calling stopBroadcasting

,2016-02-08 23:36:56.317 ThaliTest[1509:2855237] jxcore: stopBroadcasting
2016-02-08 23:36:56.317 ThaliTest[1509:2855237] THEMultipeerSession stopping peer
2016-02-08 23:36:56.318 ThaliTest[1509:2855237] multipeer session: stop timer
2016-02-08 23:36:56.,318 ThaliTest[1509:2855237] server session: disconnect
2016-02-08 23:36:56.318 ThaliTest[1509:2855237] server session: stateChange:2->0 1454971008989.963
,2016-02-08 23:36:56.327 ThaliTest[1509:2855237] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# setup

,# ThaliEmitter handles socket disconnect correctly

,echo server started on port: 58560

,2016-02-08 23:36:56.808 ThaliTest[1509:2855237] jxcore: startBroadcasting
,2016-02-08 23:36:56.812 ThaliTest[1509:2855237] server: starting 1454971016808.1509.5Fr2Vw==
2016-02-08 23:36:56.813 ThaliTest[1509:2855237] multipeer session: start timer: 0x14e7ccf0
2016-02-08 23:36:56.813 ThaliTest[1509:2855237] THEMultipeerSession in,itialized peer 1454971016808.1509
2016-02-08 23:36:56.813 ThaliTest[1509:2855237] jxcore: startBroadcasting: success
ok 117 Should be able to call startBroadcasting without error

,2016-02-08 23:36:57.561 ThaliTest[1509:2854883] client: found peer: 1454971008989.963.vzmIcg==
,[{"peerIdentifier":"1454971008989.963.vzmIcg==","peerName":"(null)","peerAvailable":true}]

2016-02-08 23:36:57.566 ThaliTest[1509:2855237] jxcore: connect 1454971008989.963.vzmIcg==
2016-02-08 23:36:57.566 ThaliTest[1509:2855237] client session: connect
2016-02-08 23:36:57.567 ThaliTest[1509:2855237] client session: stateChange:0->1 1454971008989.963.vzmIcg==
,2016-02-08 23:36:57.602 ThaliTest[1509:2854883] client: found peer: 1454971017387.963.XB3jRg==
[{"peerIdentifier":"1454971017387.963.XB3jRg==","peerName":"(null)","peerAvailable":true}]

2016-02-08 23:36:57.603 ThaliTest[1509:2855237] jxcore: connect 14,54971017387.963.XB3jRg==
2016-02-08 23:36:57.604 ThaliTest[1509:2855237] client session: connect
2016-02-08 23:36:57.604 ThaliTest[1509:2855237] client session: stateChange:0->1 1454971017387.963.XB3jRg==
,2016-02-08 23:36:58.098 ThaliTest[1509:2854883] multipeer session: reset timer
2016-02-08 23:36:58.099 ThaliTest[1509:2854883] multipeer session: stop timer
2016-02-08 23:36:58.099 ThaliTest[1509:2854883] multipeer session: start timer: 0x14e7ccf0
2016-,02-08 23:36:58.099 ThaliTest[1509:2854883] server session: connect
2016-02-08 23:36:58.100 ThaliTest[1509:2854883] server session: stateChange:0->1 1454971017387.963
,2016-02-08 23:36:58.109 ThaliTest[1509:2854883] server: accepting invitation 1454971017387.963
,2016-02-08 23:37:00.713 ThaliTest[1509:2855735] client session: connected
2016-02-08 23:37:00.715 ThaliTest[1509:2855735] client session: stateChange:1->2 1454971017387.963.XB3jRg==
,2016-02-08 23:37:00.744 ThaliTest[1509:2855743] client session: fireConnectCallback: 1454971017387.963.XB3jRg==
2016-02-08 23:37:00.745 ThaliTest[1509:2855743] jxcore: connect: success
ok 118 Should be able to connect without error

,ok 119 Port should be within range

,ok 120 First connect should succeed

,2016-02-08 23:37:00.816 ThaliTest[1509:2854883] client: relay established
2016-02-08 23:37:00.817 ThaliTest[1509:2854883] client: new accepted socket: 0x16326b40
,2016-02-08 23:37:00.841 ThaliTest[1509:2855743] server session: connected
2016-02-08 23:37:00.841 ThaliTest[1509:2855743] server session: stateChange:1->2 1454971017387.963
,2016-02-08 23:37:00.874 ThaliTest[1509:2854883] server relay: connected (to port: 58560)
ok 121 the test messages should be equal

,ok 122 First send should succeed

,2016-02-08 23:37:00.898 ThaliTest[1509:2854883] client: socket closed
2016-02-08 23:37:00.899 ThaliTest[1509:2854883] client relay: socket disconnected
2016-02-08 23:37:00.899 ThaliTest[1509:2854883] client relay: 0x16326b40 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-02-08 23:37:00.899 ThaliTest[1509:2854883] client session: socket closed: 1454971017387.963.XB3jRg==
2016-02-08 2,3:37:00.900 ThaliTest[1509:2854883] client session: onLinkFailure: 1454971017387.963.XB3jRg==
2016-02-08 23:37:00.900 ThaliTest[1509:2854883] client session: disconnect
2016-02-08 23:37:00.900 ThaliTest[1509:2854883] client session: stateChange:2->0 1454,971017387.963.XB3jRg==
,2016-02-08 23:37:00.917 ThaliTest[1509:2854883] client session: fireConnectionErrorEvent: 1454971017387.963.XB3jRg==
2016-02-08 23:37:00.920 ThaliTest[1509:2855237] jxcore: connect 1454971017387.963.XB3jRg==
2016-02-08 23:37:00.921 ThaliTest[1509:2855237,] client session: connect
2016-02-08 23:37:00.921 ThaliTest[1509:2855237] client session: stateChange:0->1 1454971017387.963.XB3jRg==
,2016-02-08 23:37:01.070 ThaliTest[1509:2855745] server session: not connected 1454971017387.963
,2016-02-08 23:37:01.167 ThaliTest[1509:2854883] multipeer session: reset timer
,2016-02-08 23:37:01.168 ThaliTest[1509:2854883] multipeer session: stop timer
,2016-02-08 23:37:01.169 ThaliTest[1509:2854883] multipeer session: start timer: 0x14e7ccf0
,2016-02-08 23:37:01.169 ThaliTest[1509:2854883] server: disconnecting to refresh session (1454971017387.963)
,2016-02-08 23:37:01.170 ThaliTest[1509:2854883] server session: disconnect
,2016-02-08 23:37:01.171 ThaliTest[1509:2854883] server session: stateChange:2->0 1454971017387.963
,2016-02-08 23:37:01.176 ThaliTest[1509:2854883] server session: connect
,2016-02-08 23:37:01.177 ThaliTest[1509:2854883] server session: stateChange:0->1 1454971017387.963
,2016-02-08 23:37:01.208 ThaliTest[1509:2854883] server: accepting invitation 1454971017387.963
,2016-02-08 23:37:03.786 ThaliTest[1509:2855745] client session: connected
,2016-02-08 23:37:03.786 ThaliTest[1509:2855745] client session: stateChange:1->2 1454971017387.963.XB3jRg==
,2016-02-08 23:37:03.800 ThaliTest[1509:2855743] client session: fireConnectCallback: 1454971017387.963.XB3jRg==
2016-02-08 23:37:03.800 ThaliTest[1509:2855743] jxcore: connect: success
ok 123 Should be able to connect without error

ok 124 Port should ,be within range

ok 125 Second connect should succeed

,2016-02-08 23:37:03.838 ThaliTest[1509:2854883] client: relay established
2016-02-08 23:37:03.839 ThaliTest[1509:2854883] client: new accepted socket: 0x163fbb60
,ok 126 the test messages should be equal

,ok 127 Second send should succeed

,# teardown

,2016-02-08 23:37:03.926 ThaliTest[1509:2854883] client: socket closed
2016-02-08 23:37:03.926 ThaliTest[1509:2854883] client relay: socket disconnected
2016-02-08 23:37:03.927 ThaliTest[1509:2854883] client relay: 0x163fbb60 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-02-08 23:37:03.927 ThaliTest[1509:2854883] client session: socket closed: 1454971017387.963.XB3jRg==
2016-02-08 2,3:37:03.927 ThaliTest[1509:2854883] client session: onLinkFailure: 1454971017387.963.XB3jRg==
2016-02-08 23:37:03.927 ThaliTest[1509:2854883] client session: disconnect
2016-02-08 23:37:03.927 ThaliTest[1509:2854883] client session: stateChange:2->0 1454971017387.963.XB3jRg==
,2016-02-08 23:37:03.944 ThaliTest[1509:2854883] client session: fireConnectionErrorEvent: 1454971017387.963.XB3jRg==
,2016-02-08 23:37:04.039 ThaliTest[1509:2855743] server session: connected
2016-02-08 23:37:04.039 ThaliTest[1509:2855743] server session: stateChange:1->2 1454971017387.963
,2016-02-08 23:37:04.055 ThaliTest[1509:2854883] server relay: connected (to port: 58560)
,calling stopBroadcasting

2016-02-08 23:37:04.218 ThaliTest[1509:2855237] jxcore: stopBroadcasting
2016-02-08 23:37:04.218 ThaliTest[1509:2855237] THEMultipeerSession stopping peer
2016-02-08 23:37:04.218 ThaliTest[1509:2855237] multipeer session: stop timer
2016-02-08 23:37:04.219 ThaliTest[1509:2855237] client session: disconnect
2016-02-08 23:37:04.219 ThaliTest[1509:2855237] client session: stateChange:1->0 1454971008989.963.vzmIcg==
,2016-02-08 23:37:04.223 ThaliTest[1509:2855237] server session: disconnect
2016-02-08 23:37:04.226 ThaliTest[1509:2855237] server session: stateChange:2->0 1454971017387.963
,2016-02-08 23:37:04.257 ThaliTest[1509:2855237] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# setup

,# ThaliReplicationManager can call start without error

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/A2D1EDD5-342A-4532-9CA9-B48CAEE259FD/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,ok 128 starting event should occur in right order

,2016-02-08 23:37:04.825 ThaliTest[1509:2855237] jxcore: startBroadcasting
,2016-02-08 23:37:04.827 ThaliTest[1509:2855237] server: starting 8cjLUaU3CP8-JFk3KuK_lQ.XOyFQQ==
2016-02-08 23:37:04.827 ThaliTest[1509:2855237] multipeer session: start timer: 0x170757c0
2016-02-08 23:37:04.827 ThaliTest[1509:2855237] THEMultipeerSession initialized peer 8cjLUaU3CP8-JFk3KuK_lQ
2016-02-08 23:37:04.827 ThaliTest[1509:2855237] jxcore: startBroadcasting: success
ok 129 started event should occur in right order

Now in TRM stop

State of this._isStarted: true

ok 130 stopping event sh,ould occur in right order

About to call stopBroadcasting

,2016-02-08 23:37:04.828 ThaliTest[1509:2855237] jxcore: stopBroadcasting
2016-02-08 23:37:04.829 ThaliTest[1509:2855237] THEMultipeerSession stopping peer
2016-02-08 23:37:04.829 ThaliTest[1509:2855237] multipeer session: stop timer
2016-02-08 23:37:04.829 ThaliTest[1509:2855237] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,ok 131 stopped event should occur in right order

,mux server bridge listener closed

# teardown

,# setup

,# ThaliReplicationManager receives identity

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/A2D1EDD5-342A-4532-9CA9-B48CAEE259FD/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-02-08 23:37:05.179 ThaliTest[1509:2855237] jxcore: startBroadcasting
,2016-02-08 23:37:05.183 ThaliTest[1509:2855237] server: starting 8cjLUaU3CP8-JFk3KuK_lQ.FEQyvQ==
,2016-02-08 23:37:05.186 ThaliTest[1509:2855237] multipeer session: start timer: 0x16326270
,2016-02-08 23:37:05.195 ThaliTest[1509:2855237] THEMultipeerSession initialized peer 8cjLUaU3CP8-JFk3KuK_lQ
,2016-02-08 23:37:05.197 ThaliTest[1509:2855237] jxcore: startBroadcasting: success
,ok 132 getDeviceIdentity should not return an error

,ok 133 deviceName should not be null

,Now in TRM stop

,State of this._isStarted: true

,About to call stopBroadcasting

,2016-02-08 23:37:05.204 ThaliTest[1509:2855237] jxcore: stopBroadcasting
,2016-02-08 23:37:05.206 ThaliTest[1509:2855237] THEMultipeerSession stopping peer
,2016-02-08 23:37:05.207 ThaliTest[1509:2855237] multipeer session: stop timer
,2016-02-08 23:37:05.209 ThaliTest[1509:2855237] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined

,mux server bridge listener closed

,# teardown

,# setup

,# ThaliReplicationManager replicates database

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/A2D1EDD5-342A-4532-9CA9-B48CAEE259FD/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-02-08 23:37:07.368 ThaliTest[1509:2855237] jxcore: startBroadcasting
,2016-02-08 23:37:07.369 ThaliTest[1509:2855237] server: starting 8cjLUaU3CP8-JFk3KuK_lQ.OaQSEw==
2016-02-08 23:37:07.370 ThaliTest[1509:2855237] multipeer session: start timer: 0x16467a70
2016-02-08 23:37:07.370 ThaliTest[1509:2855237] THEMultipeerSession initialized peer 8cjLUaU3CP8-JFk3KuK_lQ
2016-02-08 23:37:07.370 ThaliTest[1509:2855237] jxcore: startBroadcasting: success
ok 134 getDeviceIdentity should not return an error

ok 135 deviceName should not be null

,2016-02-08 23:37:08.055 ThaliTest[1509:2854883] client: found peer: 1454971017387.963.XB3jRg==
,2016-02-08 23:37:11.948 ThaliTest[1509:2854883] client: found peer: MO4x_LoLvtLb1O_NXKa3eQ.yeJseg==
,2016-02-08 23:37:11.977 ThaliTest[1509:2855237] jxcore: connect 1454971017387.963.XB3jRg==
,2016-02-08 23:37:11.978 ThaliTest[1509:2855237] client session: connect
,2016-02-08 23:37:11.979 ThaliTest[1509:2855237] client session: stateChange:0->1 1454971017387.963.XB3jRg==
,2016-02-08 23:37:11.990 ThaliTest[1509:2855237] jxcore: connect MO4x_LoLvtLb1O_NXKa3eQ.yeJseg==
2016-02-08 23:37:11.991 ThaliTest[1509:2855237] client session: connect
,2016-02-08 23:37:11.993 ThaliTest[1509:2854883] multipeer session: reset timer
2016-02-08 23:37:11.993 ThaliTest[1509:2855237] client session: stateChange:0->1 MO4x_LoLvtLb1O_NXKa3eQ.yeJseg==
,2016-02-08 23:37:11.994 ThaliTest[1509:2854883] multipeer session: stop timer
2016-02-08 23:37:11.995 ThaliTest[1509:2854883] multipeer session: start timer: 0x16467a70
2016-02-08 23:37:11.995 ThaliTest[1509:2854883] server session: connect
,2016-02-08 23:37:11.995 ThaliTest[1509:2854883] server session: stateChange:0->1 MO4x_LoLvtLb1O_NXKa3eQ
,2016-02-08 23:37:12.000 ThaliTest[1509:2854883] server: accepting invitation MO4x_LoLvtLb1O_NXKa3eQ
,ok 136 Should be able to put doc without error
,
,ok 137 1st change of local doc should contain local id

,2016-02-08 23:37:14.668 ThaliTest[1509:2855744] server session: connected
,2016-02-08 23:37:14.669 ThaliTest[1509:2855744] server session: stateChange:1->2 MO4x_LoLvtLb1O_NXKa3eQ
,2016-02-08 23:37:14.678 ThaliTest[1509:2854883] server relay: connected (to port: 58578)
,server bridge: new client socket

,2016-02-08 23:37:14.703 ThaliTest[1509:2855744] client session: connected
,2016-02-08 23:37:14.705 ThaliTest[1509:2855744] client session: stateChange:1->2 MO4x_LoLvtLb1O_NXKa3eQ.yeJseg==
,2016-02-08 23:37:14.710 ThaliTest[1509:2855744] client session: fireConnectCallback: MO4x_LoLvtLb1O_NXKa3eQ.yeJseg==
2016-02-08 23:37:14.711 ThaliTest[1509:2855744] jxcore: connect: success
,2016-02-08 23:37:14.716 ThaliTest[1509:2854883] client: relay established
,2016-02-08 23:37:14.718 ThaliTest[1509:2854883] client: new accepted socket: 0x14edb340
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

,client bridge: socket closed

client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket
,
,client bridge: new client socket
,
,2016-02-08 23:37:16.334 ThaliTest[1509:2854883] client: lost peer: 1454971017387.963.XB3jRg==
2016-02-08 23:37:16.334 ThaliTest[1509:2854883] client session: onPeerLost: 1454971017387.963.XB3jRg==
2016-02-08 23:37:16.335 ThaliTest[1509:2854883] client se,ssion: onLinkFailure: 1454971017387.963.XB3jRg==
2016-02-08 23:37:16.335 ThaliTest[1509:2854883] client session: disconnect
2016-02-08 23:37:16.335 ThaliTest[1509:2854883] client session: stateChange:1->0 1454971017387.963.XB3jRg==
2016-02-08 23:37:16.3,35 ThaliTest[1509:2854883] client session: fireConnectCallback: 1454971017387.963.XB3jRg==
2016-02-08 23:37:16.336 ThaliTest[1509:2854883] jxcore: connect: fail: Peer disconnected
,Connect error with error: Error: Peer disconnected

,2016-02-08 23:37:16.478 ThaliTest[1509:2855237] jxcore: disconnect
,2016-02-08 23:37:16.479 ThaliTest[1509:2855237] jxcore: disconnect: fail
,Disconnect error with error: Error: Not connected to specified peer

peerIdentifier not available 1454971017387.963.XB3jRg==

,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: socket closed

client bridge: socket closed

,ok 138 1st change of remote doc should contain remote id

,client bridge: new client socket

,ok 139 Can update remote doc without error
,
,null

,{ ok: true,
  id: 'b4626801-6381-4e40-9e7d-0157120160b4',
  rev: '2-c4a78078e44518311b8c096be9388983' }

,client bridge: new client socket

,ok 140 Remote changes occur in strict order

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket
,
,client bridge: socket closed

,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket
,
,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket
,
,client bridge: socket closed

client bridge: socket closed

,ok 141 Local changes occur in strict order

ok 142 2nd change of local doc should contain remote id

,# teardown

,client bridge: new client socket
,
,client bridge: new client socket

,Now in TRM stop

State of this._isStarted: true

,About to call stopBroadcasting

,2016-02-08 23:37:25.651 ThaliTest[1509:2855237] jxcore: stopBroadcasting
,2016-02-08 23:37:25.652 ThaliTest[1509:2855237] THEMultipeerSession stopping peer
,2016-02-08 23:37:25.653 ThaliTest[1509:2855237] multipeer session: stop timer
,2016-02-08 23:37:25.653 ThaliTest[1509:2855237] client session: disconnect
2016-02-08 23:37:25.655 ThaliTest[1509:2855237] client session: stateChange:2->0 MO4x_LoLvtLb1O_NXKa3eQ.yeJseg==
,2016-02-08 23:37:25.724 ThaliTest[1509:2855237] server session: disconnect
2016-02-08 23:37:25.724 ThaliTest[1509:2855237] server session: stateChange:2->0 MO4x_LoLvtLb1O_NXKa3eQ
,2016-02-08 23:37:25.793 ThaliTest[1509:2855237] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,# setup

,client bridge: socket closed

,mux server bridge listener closed

,server bridge: socket closed

,# After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

,client bridge: socket closed

,client bridge: socket closed

,appEnteredForeground wasn't registered

,appEnteringBackground wasn't registered

,appEnteredForeground wasn't registered


```
