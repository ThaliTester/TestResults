#### Test 5838050069f842e_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5838050069f842e/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/0B0F3881-5E8C-4749-A2B5-9AF55A4C487E/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/0B0F3881-5E8C-4749-A2B5-9AF55A4C487E/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5838050069f842e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5838050069f842e/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/3CAB91CE-1F3C-4B92-BC0C-2A65925B2EF3/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50878"
,(lldb)     command script import "/tmp/0B0F3881-5E8C-4749-A2B5-9AF55A4C487E/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-05 20:37:53.187 ThaliTest[1313:2385251] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/15ED189B-0FF2-4126-A5B7-9D88618A6B34/Library/Cookies/Cookies.binarycookies
,2016-02-05 20:37:53.560 ThaliTest[1313:2385251] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-05 20:37:53.562 ThaliTest[1313:2385251] Multi-tasking -> Device: YES, App: YES
,2016-02-05 20:37:53.571 ThaliTest[1313:2385251] Unlimited access to network resources
,2016-02-05 20:37:53.583 ThaliTest[1313:2385251] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-05 20:38:03.274 ThaliTest[1313:2385251] Resetting plugins due to page load.
,2016-02-05 20:38:05.896 ThaliTest[1313:2385251] Finished load of: file:///var/mobile/Containers/Bundle/Application/3CAB91CE-1F3C-4B92-BC0C-2A65925B2EF3/ThaliTest.app/www/index.html
,2016-02-05 20:38:06.074 ThaliTest[1313:2385251] JXcore Cordova plugin initializing
2016-02-05 20:38:06.075 ThaliTest[1313:2385578] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3CAB91CE-1F3C-4B92-BC0C-2A65925B2EF3/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3CAB91CE-1F3C-4B92-BC0C-2A65925B2EF3/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3CAB91CE-1F3C-4B92-BC0C-2A65925B2EF3/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3CAB91CE-1F3C-4B92-BC0C-2A65925B2EF3/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3CAB91CE-1F3C-4B92-BC0C-2A65925B2EF3/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3CAB91CE-1F3C-4B92-BC0C-2A65925B2EF3/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3CAB91CE-1F3C-4B92-BC0C-2A65925B2EF3/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3CAB91CE-1F3C-4B92-BC0C-2A65925B2EF3/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3CAB91CE-1F3C-4B92-BC0C-2A65925B2EF3/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,TAP version 13

,# setup

,# #generatePreambleAndBeacons empty keys to notify

,ok 1 should be equal

ok 2 should be equal

ok 3 should be equal

ok 4 should be equal

# teardown

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

# setup

,# #parseBeacons invalid size for encryptedBeaconKeyId in beaconStreamWithPreAmble

,ok 12 should throw

,# teardown

# setup

,# #parseBeacons addressBookCallback fails decrypt

,ok 13 should be equal

,# teardown

,# setup

# #parseBeacons addressBookCallback returns null for all

,ok 14 (unnamed assert)

,ok 15 should be equal

,# teardown

,# setup

,# #parseBeacons addressBookCallback returns public key

,ok 16 (unnamed assert)

,ok 17 (unnamed assert)

# teardown

,# setup

,# multiplex can send data

,ok 18 String should be length:200

,# teardown

,# setup

,# enqueue and run in order

,ok 19 firstPromise setTimeout

,ok 20 firstPromise result

,ok 21 firstPromise testValue

,ok 22 secondPromise setTimeout

,ok 23 secondPromise result

,ok 24 secondPromise testValue

,ok 25 thirdPromise in promise

,ok 26 thirdPromise result

,ok 27 thirdPromise testValue

,# teardown

,# setup

,# basic

,ok 28 sane

,# teardown

,# setup

,# another

,ok 29 sane

,# teardown

,# setup

,# successfully create a new pkcs12 file and return hash value

,ok 30 should be equal

,ok 31 null

,ok 32 (unnamed assert)

,ok 33 should be equal

,ok 34 should not throw

# teardown

,# setup

,# successfully read a previous pkcs12 file and return hash value

,ok 35 (unnamed assert)

,ok 36 (unnamed assert)

ok 37 should not throw

,ok 38 should be equal

ok 39 should be equal

,# teardown

,# setup

,# failed to extract public key because of corrupt pkcs12 file

,ok 40 should be equal

,# teardown

,# setup

,# failed to get mobile documents path

,ok 41 should be equal

,# teardown

,# setup

,# #init should register the peerAvailabilityChanged event

,ok 42 should be equal

,ok 43 should be equal

,ok 44 should be equal

,# teardown

,# setup

,# #init should register the networkChanged event

,ok 45 should be equal

,# teardown

,# setup

,# #startBroadcasting should throw on null device name

,ok 46 should throw

,# teardown

,# setup

,# #startBroadcasting should throw on empty string device name

,ok 47 should throw

,# teardown

,# setup

,# #startBroadcasting should throw on non-number port

,ok 48 should throw

,# teardown

,# setup

,# #startBroadcasting should throw on NaN port

,ok 49 should throw

,# teardown

,# setup

,# #startBroadcasting should throw on negative port

,ok 50 should throw

,# teardown

,# setup

,# #startBroadcasting should throw on too large port

,ok 51 should throw

,# teardown

,# setup

,# #startBroadcasting should call Mobile("StartBroadcasting") without an error

,ok 52 should be equal

,ok 53 should be equal

,ok 54 should be equal

,# teardown

,# setup

,# #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

,ok 55 should be equal

,ok 56 should be equal

,ok 57 should be equal

,# teardown

,# setup

,# #stopBroadcasting should call Mobile("StopBroadcasting") without an error

,ok 58 should be equal

,ok 59 should be equal

,# teardown

,# setup

,# #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

,ok 60 should be equal

,ok 61 should be equal

,# teardown

,# setup

,# #connect should call Mobile("Connect") with a port and without an error

,ok 62 should be equal

,ok 63 should be equal

,ok 64 should be equal

,# teardown

,# setup

,# #connect should call Mobile("Connect") and handle an error

,ok 65 should be equal

,ok 66 should be equal

,# teardown

,# setup

,# should call Mobile("Disconnect") without an error

,ok 67 should be equal

,ok 68 should be equal

,# teardown

,# setup

,# should call Mobile("Disconnect") and handle an error

,ok 69 should be equal

,ok 70 should be equal

,# teardown

,# setup

,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

,2016-02-05 20:43:02.658 ThaliTest[1313:2385578] jxcore: startBroadcasting
,2016-02-05 20:43:02.672 ThaliTest[1313:2385578] server: starting 1454701382657.1313.JFxtqg==
,2016-02-05 20:43:02.673 ThaliTest[1313:2385578] multipeer session: start timer: 0x170ea6f0
2016-02-05 20:43:02.674 ThaliTest[1313:2385578] THEMultipeerSession initialized peer 1454701382657.1313
2016-02-05 20:43:02.675 ThaliTest[1313:2385578] jxcore: sta,rtBroadcasting: success
ok 71 Should be able to call startBroadcasting without error

2016-02-05 20:43:02.679 ThaliTest[1313:2385578] jxcore: stopBroadcasting
2016-02-05 20:43:02.679 ThaliTest[1313:2385578] THEMultipeerSession stopping peer
2016-02-05, 20:43:02.679 ThaliTest[1313:2385578] multipeer session: stop timer
2016-02-05 20:43:02.680 ThaliTest[1313:2385578] jxcore: stopBroadcasting: success
ok 72 Should be able to call stopBroadcasting without error

2016-02-05 20:43:02.682 ThaliTest[1313:23,85578] jxcore: startBroadcasting
,2016-02-05 20:43:02.687 ThaliTest[1313:2385578] server: starting 1454701382681.1313.soWRKQ==
2016-02-05 20:43:02.687 ThaliTest[1313:2385578] multipeer session: start timer: 0x170ecb90
2016-02-05 20:43:02.688 ThaliTest[1313:2385578] THEMultipeerSession in,itialized peer 1454701382681.1313
,2016-02-05 20:43:02.688 ThaliTest[1313:2385578] jxcore: startBroadcasting: success
ok 73 Should be able to call startBroadcasting without error

2016-02-05 20:43:02.698 ThaliTest[1313:2385578] jxcore: stopBroadcasting
2016-02-05 20:43:02.698 ThaliTest[,1313:2385578] THEMultipeerSession stopping peer
2016-02-05 20:43:02.699 ThaliTest[1313:2385578] multipeer session: stop timer
2016-02-05 20:43:02.699 ThaliTest[1313:2385578] jxcore: stopBroadcasting: success
ok 74 Should be able to call stopBroadcasting, without error

2016-02-05 20:43:02.701 ThaliTest[1313:2385578] jxcore: startBroadcasting
2016-02-05 20:43:02.705 ThaliTest[1313:2385578] server: starting 1454701382701.1313.VS8m9A==
2016-02-05 20:43:02.714 ThaliTest[1313:2385578] multipeer session: st,art timer: 0x170efa00
2016-02-05 20:43:02.715 ThaliTest[1313:2385578] THEMultipeerSession initialized peer 1454701382701.1313
,2016-02-05 20:43:02.715 ThaliTest[1313:2385578] jxcore: startBroadcasting: success
ok 75 Should be able to call startBroadcasting without error

2016-02-05 20:43:02.722 ThaliTest[1313:2385578] jxcore: stopBroadcasting
2016-02-05 20:43:02.722 ThaliTest[,1313:2385578] THEMultipeerSession stopping peer
2016-02-05 20:43:02.722 ThaliTest[1313:2385578] multipeer session: stop timer
2016-02-05 20:43:02.723 ThaliTest[1313:2385578] jxcore: stopBroadcasting: success
,ok 76 Should be able to call stopBroadcasting without error

,2016-02-05 20:43:02.725 ThaliTest[1313:2385578] jxcore: startBroadcasting
,2016-02-05 20:43:02.735 ThaliTest[1313:2385578] server: starting 1454701382724.1313.ZNgxxQ==
2016-02-05 20:43:02.736 ThaliTest[1313:2385578] multipeer session: start timer: 0x14e3a380
2016-02-05 20:43:02.737 ThaliTest[1313:2385578] THEMultipeerSession in,itialized peer 1454701382724.1313
2016-02-05 20:43:02.737 ThaliTest[1313:2385578] jxcore: startBroadcasting: success
ok 77 Should be able to call startBroadcasting without error

2016-02-05 20:43:02.741 ThaliTest[1313:2385578] jxcore: stopBroadcasting
,2016-02-05 20:43:02.742 ThaliTest[1313:2385578] THEMultipeerSession stopping peer
2016-02-05 20:43:02.742 ThaliTest[1313:2385578] multipeer session: stop timer
2016-02-05 20:43:02.743 ThaliTest[1313:2385578] jxcore: stopBroadcasting: success
,ok 78 Should be able to call stopBroadcasting without error

2016-02-05 20:43:02.745 ThaliTest[1313:2385578] jxcore: startBroadcasting
,2016-02-05 20:43:02.754 ThaliTest[1313:2385578] server: starting 1454701382745.1313.qXN5JA==
,2016-02-05 20:43:02.761 ThaliTest[1313:2385578] multipeer session: start timer: 0x14d9c2b0
,2016-02-05 20:43:02.767 ThaliTest[1313:2385578] THEMultipeerSession initialized peer 1454701382745.1313
,2016-02-05 20:43:02.769 ThaliTest[1313:2385578] jxcore: startBroadcasting: success
,ok 79 Should be able to call startBroadcasting without error

,2016-02-05 20:43:02.771 ThaliTest[1313:2385578] jxcore: stopBroadcasting
,2016-02-05 20:43:02.772 ThaliTest[1313:2385578] THEMultipeerSession stopping peer
,2016-02-05 20:43:02.773 ThaliTest[1313:2385578] multipeer session: stop timer
,2016-02-05 20:43:02.774 ThaliTest[1313:2385578] jxcore: stopBroadcasting: success
,ok 80 Should be able to call stopBroadcasting without error

,2016-02-05 20:43:02.779 ThaliTest[1313:2385578] jxcore: startBroadcasting
,2016-02-05 20:43:02.782 ThaliTest[1313:2385578] server: starting 1454701382778.1313.QML70Q==
,2016-02-05 20:43:02.784 ThaliTest[1313:2385578] multipeer session: start timer: 0x14d67550
,2016-02-05 20:43:02.788 ThaliTest[1313:2385578] THEMultipeerSession initialized peer 1454701382778.1313
,2016-02-05 20:43:02.789 ThaliTest[1313:2385578] jxcore: startBroadcasting: success
,ok 81 Should be able to call startBroadcasting without error
,
,2016-02-05 20:43:02.794 ThaliTest[1313:2385578] jxcore: stopBroadcasting
,2016-02-05 20:43:02.795 ThaliTest[1313:2385578] THEMultipeerSession stopping peer
,2016-02-05 20:43:02.796 ThaliTest[1313:2385578] multipeer session: stop timer
,2016-02-05 20:43:02.797 ThaliTest[1313:2385578] jxcore: stopBroadcasting: success
,ok 82 Should be able to call stopBroadcasting without error

,2016-02-05 20:43:02.802 ThaliTest[1313:2385578] jxcore: startBroadcasting
,2016-02-05 20:43:02.804 ThaliTest[1313:2385578] server: starting 1454701382801.1313.hMyI9g==
,2016-02-05 20:43:02.806 ThaliTest[1313:2385578] multipeer session: start timer: 0x14e76af0
,2016-02-05 20:43:02.810 ThaliTest[1313:2385578] THEMultipeerSession initialized peer 1454701382801.1313
,2016-02-05 20:43:02.813 ThaliTest[1313:2385578] jxcore: startBroadcasting: success
,ok 83 Should be able to call startBroadcasting without error

,2016-02-05 20:43:02.816 ThaliTest[1313:2385578] jxcore: stopBroadcasting
,2016-02-05 20:43:02.817 ThaliTest[1313:2385578] THEMultipeerSession stopping peer
2016-02-05 20:43:02.817 ThaliTest[1313:2385578] multipeer session: stop timer
,2016-02-05 20:43:02.819 ThaliTest[1313:2385578] jxcore: stopBroadcasting: success
,ok 84 Should be able to call stopBroadcasting without error

,2016-02-05 20:43:02.824 ThaliTest[1313:2385578] jxcore: startBroadcasting
,2016-02-05 20:43:02.827 ThaliTest[1313:2385578] server: starting 1454701382823.1313.zlQliA==
,2016-02-05 20:43:02.830 ThaliTest[1313:2385578] multipeer session: start timer: 0x14d33e50
,2016-02-05 20:43:02.834 ThaliTest[1313:2385578] THEMultipeerSession initialized peer 1454701382823.1313
,2016-02-05 20:43:02.835 ThaliTest[1313:2385578] jxcore: startBroadcasting: success
,ok 85 Should be able to call startBroadcasting without error

,2016-02-05 20:43:02.838 ThaliTest[1313:2385578] jxcore: stopBroadcasting
,2016-02-05 20:43:02.839 ThaliTest[1313:2385578] THEMultipeerSession stopping peer
,2016-02-05 20:43:02.840 ThaliTest[1313:2385578] multipeer session: stop timer
,2016-02-05 20:43:02.841 ThaliTest[1313:2385578] jxcore: stopBroadcasting: success
,ok 86 Should be able to call stopBroadcasting without error

,2016-02-05 20:43:02.847 ThaliTest[1313:2385578] jxcore: startBroadcasting
,2016-02-05 20:43:02.850 ThaliTest[1313:2385578] server: starting 1454701382847.1313.QtGrww==
,2016-02-05 20:43:02.852 ThaliTest[1313:2385578] multipeer session: start timer: 0x170eada0
,2016-02-05 20:43:02.856 ThaliTest[1313:2385578] THEMultipeerSession initialized peer 1454701382847.1313
,2016-02-05 20:43:02.857 ThaliTest[1313:2385578] jxcore: startBroadcasting: success
,ok 87 Should be able to call startBroadcasting without error
,
,2016-02-05 20:43:02.861 ThaliTest[1313:2385578] jxcore: stopBroadcasting
,2016-02-05 20:43:02.861 ThaliTest[1313:2385578] THEMultipeerSession stopping peer
,2016-02-05 20:43:02.862 ThaliTest[1313:2385578] multipeer session: stop timer
,2016-02-05 20:43:02.862 ThaliTest[1313:2385578] jxcore: stopBroadcasting: success
,ok 88 Should be able to call stopBroadcasting without error

,2016-02-05 20:43:02.866 ThaliTest[1313:2385578] jxcore: startBroadcasting
,2016-02-05 20:43:02.868 ThaliTest[1313:2385578] server: starting 1454701382866.1313.6TzTiA==
,2016-02-05 20:43:02.869 ThaliTest[1313:2385578] multipeer session: start timer: 0x14e69200
,2016-02-05 20:43:02.874 ThaliTest[1313:2385578] THEMultipeerSession initialized peer 1454701382866.1313
,2016-02-05 20:43:02.875 ThaliTest[1313:2385578] jxcore: startBroadcasting: success
,ok 89 Should be able to call startBroadcasting without error

,2016-02-05 20:43:02.877 ThaliTest[1313:2385578] jxcore: stopBroadcasting
,2016-02-05 20:43:02.878 ThaliTest[1313:2385578] THEMultipeerSession stopping peer
,2016-02-05 20:43:02.878 ThaliTest[1313:2385578] multipeer session: stop timer
,2016-02-05 20:43:02.879 ThaliTest[1313:2385578] jxcore: stopBroadcasting: success
,ok 90 Should be able to call stopBroadcasting without error
,
,# teardown

,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,2016-02-05 20:43:03.445 ThaliTest[1313:2385578] jxcore: startBroadcasting
,2016-02-05 20:43:03.448 ThaliTest[1313:2385578] server: starting 1454701383444.1313.Twyf3w==
2016-02-05 20:43:03.449 ThaliTest[1313:2385578] multipeer session: start timer: 0x165ac8b0
2016-02-05 20:43:03.449 ThaliTest[1313:2385578] THEMultipeerSession in,itialized peer 1454701383444.1313
2016-02-05 20:43:03.450 ThaliTest[1313:2385578] jxcore: startBroadcasting: success
ok 91 Should be able to call startBroadcasting without error

2016-02-05 20:43:03.452 ThaliTest[1313:2385578] jxcore: startBroadcasting
2016-02-05 20:43:03.453 ThaliTest[1313:2385578] jxcore: startBroadcasting: failure
,ok 92 Cannot call startBroadcasting twice

,2016-02-05 20:43:03.457 ThaliTest[1313:2385578] jxcore: stopBroadcasting
2016-02-05 20:43:03.458 ThaliTest[1313:2385578] THEMultipeerSession stopping peer
2016-02-05 20:43:03.458 ThaliTest[1313:2385578] multipeer session: stop timer
2016-02-05 20:43:03.459 ThaliTest[1313:2385578] jxcore: stopBroadcasting: success
ok 93 Should be able to call stopBroadcasting without error

# teardown

,# setup

,# ThaliEmitter throws on connection to bad peer

,2016-02-05 20:43:03.584 ThaliTest[1313:2385578] jxcore: startBroadcasting
,2016-02-05 20:43:03.587 ThaliTest[1313:2385578] server: starting 1454701383583.1313.5LxcgA==
2016-02-05 20:43:03.588 ThaliTest[1313:2385578] multipeer session: start timer: 0x165e6860
2016-02-05 20:43:03.589 ThaliTest[1313:2385578] THEMultipeerSession in,itialized peer 1454701383583.1313
2016-02-05 20:43:03.589 ThaliTest[1313:2385578] jxcore: startBroadcasting: success
ok 94 Should be able to call startBroadcasting without error

2016-02-05 20:43:03.591 ThaliTest[1313:2385578] jxcore: connect foobar
2,016-02-05 20:43:03.592 ThaliTest[1313:2385578] client: unknown peer foobar
2016-02-05 20:43:03.592 ThaliTest[1313:2385578] jxcore: connect: fail: Unknown peer
,ok 95 Should not connect to a bad peer

,2016-02-05 20:43:03.596 ThaliTest[1313:2385578] jxcore: stopBroadcasting
2016-02-05 20:43:03.597 ThaliTest[1313:2385578] THEMultipeerSession stopping peer
2016-02-05 20:43:03.597 ThaliTest[1313:2385578] multipeer session: stop timer
,2016-02-05 20:43:03.599 ThaliTest[1313:2385578] jxcore: stopBroadcasting: success
ok 96 Should be able to call stopBroadcasting without error

,# teardown

,# setup

,# ThaliEmitter throws on disconnect to bad peer

,2016-02-05 20:43:04.667 ThaliTest[1313:2385578] jxcore: startBroadcasting
,2016-02-05 20:43:04.671 ThaliTest[1313:2385578] server: starting 1454701384667.1313.3I1niw==
2016-02-05 20:43:04.672 ThaliTest[1313:2385578] multipeer session: start timer: 0x1667a9e0
2016-02-05 20:43:04.672 ThaliTest[1313:2385578] THEMultipeerSession in,itialized peer 1454701384667.1313
2016-02-05 20:43:04.672 ThaliTest[1313:2385578] jxcore: startBroadcasting: success
ok 97 Should be able to call startBroadcasting without error

2016-02-05 20:43:04.675 ThaliTest[1313:2385578] jxcore: disconnect
2016-,02-05 20:43:04.675 ThaliTest[1313:2385578] jxcore: disconnect: fail
ok 98 Disconnect should fail to a non-existant peer 

,2016-02-05 20:43:04.686 ThaliTest[1313:2385578] jxcore: stopBroadcasting
,2016-02-05 20:43:04.688 ThaliTest[1313:2385578] THEMultipeerSession stopping peer
,2016-02-05 20:43:04.689 ThaliTest[1313:2385578] multipeer session: stop timer
,2016-02-05 20:43:04.691 ThaliTest[1313:2385578] jxcore: stopBroadcasting: success
,ok 99 Should be able to call stopBroadcasting without error

,# teardown

,# setup

,# ThaliEmitter can discover and connect to peers

,2016-02-05 20:43:05.187 ThaliTest[1313:2385578] jxcore: startBroadcasting
,2016-02-05 20:43:05.191 ThaliTest[1313:2385578] server: starting 1454701385187.1313.kiZFBA==
2016-02-05 20:43:05.192 ThaliTest[1313:2385578] multipeer session: start timer: 0x166c8920
2016-02-05 20:43:05.192 ThaliTest[1313:2385578] THEMultipeerSession initialized peer 1454701385187.1313
2016-02-05 20:43:05.193 ThaliTest[1313:2385578] jxcore: startBroadcasting: success
,ok 100 Should be able to call startBroadcasting without error

,2016-02-05 20:43:06.385 ThaliTest[1313:2385251] client: found peer: 1454701386755.735.Arvtkw==
,2016-02-05 20:43:06.389 ThaliTest[1313:2385578] jxcore: connect 1454701386755.735.Arvtkw==
2016-02-05 20:43:06.389 ThaliTest[1313:2385578] client session: connect
2016-02-05 20:43:06.390 ThaliTest[1313:2385578] client session: stateChange:0->1 1454701386755.735.Arvtkw==
,2016-02-05 20:43:06.578 ThaliTest[1313:2385251] multipeer session: reset timer
2016-02-05 20:43:06.578 ThaliTest[1313:2385251] multipeer session: stop timer
2016-02-05 20:43:06.579 ThaliTest[1313:2385251] multipeer session: start timer: 0x166c8920
2016-02-05 20:43:06.579 ThaliTest[1313:2385251] server session: connect
,2016-02-05 20:43:06.581 ThaliTest[1313:2385251] server session: stateChange:0->1 1454701386755.735
,2016-02-05 20:43:06.592 ThaliTest[1313:2385251] server: accepting invitation 1454701386755.735
,2016-02-05 20:43:09.279 ThaliTest[1313:2386085] server session: connected
,2016-02-05 20:43:09.279 ThaliTest[1313:2386085] server session: stateChange:1->2 1454701386755.735
,2016-02-05 20:43:09.287 ThaliTest[1313:2385251] server relay: socket disconnected
,2016-02-05 20:43:09.288 ThaliTest[1313:2385251] server relay: 0x170001d0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-05 20:43:09.342 ThaliTest[1313:2386098] server session: not connected 1454701386755.735
,2016-02-05 20:43:09.498 ThaliTest[1313:2386098] client session: connected
2016-02-05 20:43:09.499 ThaliTest[1313:2386098] client session: stateChange:1->2 1454701386755.735.Arvtkw==
,2016-02-05 20:43:09.503 ThaliTest[1313:2386098] client session: fireConnectCallback: 1454701386755.735.Arvtkw==
2016-02-05 20:43:09.504 ThaliTest[1313:2386098] jxcore: connect: success
,ok 101 Should be able to connect without error

,ok 102 Port should be within range

,2016-02-05 20:43:09.509 ThaliTest[1313:2385578] jxcore: disconnect
2016-02-05 20:43:09.510 ThaliTest[1313:2385578] client session: disconnectFromPeer: 1454701386755.735.Arvtkw==
2016-02-05 20:43:09.510 ThaliTest[1313:2385578] client session: disconnect
2016-02-05 20:43:09.511 ThaliTest[1313:2385578] client session: stateChange:2->0 1454701386755.735.Arvtkw==
,2016-02-05 20:43:09.592 ThaliTest[1313:2385578] jxcore: disconnect: success
,ok 103 Should be able to disconnect without error

,setting stopBroadcasting callback and ending test.

,# teardown

,calling stopBroadcasting

,2016-02-05 20:43:10.444 ThaliTest[1313:2385578] jxcore: stopBroadcasting
2016-02-05 20:43:10.444 ThaliTest[1313:2385578] THEMultipeerSession stopping peer
2016-02-05 20:43:10.444 ThaliTest[1313:2385578] multipeer session: stop timer
2016-02-05 20:43:10.,445 ThaliTest[1313:2385578] server session: disconnect
2016-02-05 20:43:10.445 ThaliTest[1313:2385578] server session: stateChange:2->0 1454701386755.735
2016-02-05 20:43:10.446 ThaliTest[1313:2385578] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# setup

,# ThaliEmitter can discover and connect to peers and then fail on double connect

,2016-02-05 20:43:10.916 ThaliTest[1313:2385578] jxcore: startBroadcasting
,2016-02-05 20:43:10.920 ThaliTest[1313:2385578] server: starting 1454701390915.1313.m44ORw==
2016-02-05 20:43:10.920 ThaliTest[1313:2385578] multipeer session: start timer: 0x1761cf50
2016-02-05 20:43:10.921 ThaliTest[1313:2385578] THEMultipeerSession in,itialized peer 1454701390915.1313
2016-02-05 20:43:10.921 ThaliTest[1313:2385578] jxcore: startBroadcasting: success
ok 104 Should be able to call startBroadcasting without error

,2016-02-05 20:43:11.683 ThaliTest[1313:2385251] client: found peer: 1454701386755.735.Arvtkw==
2016-02-05 20:43:11.684 ThaliTest[1313:2385578] jxcore: connect 1454701386755.735.Arvtkw==
2016-02-05 20:43:11.685 ThaliTest[1313:2385578] client session: connect
2016-02-05 20:43:11.685 ThaliTest[1313:2385578] client session: stateChange:0->1 1454701386755.735.Arvtkw==
,2016-02-05 20:43:12.131 ThaliTest[1313:2385251] client: found peer: 1454701392470.735.UkKx9A==
2016-02-05 20:43:12.133 ThaliTest[1313:2385578] jxcore: connect 1454701392470.735.UkKx9A==
,2016-02-05 20:43:12.133 ThaliTest[1313:2385578] client session: connect
2016-02-05 20:43:12.134 ThaliTest[1313:2385578] client session: stateChange:0->1 1454701392470.735.UkKx9A==
,2016-02-05 20:43:12.151 ThaliTest[1313:2385251] multipeer session: reset timer
2016-02-05 20:43:12.152 ThaliTest[1313:2385251] multipeer session: stop timer
2016-02-05 20:43:12.152 ThaliTest[1313:2385251] multipeer session: start timer: 0x1761cf50
2016-,02-05 20:43:12.153 ThaliTest[1313:2385251] server session: connect
2016-02-05 20:43:12.153 ThaliTest[1313:2385251] server session: stateChange:0->1 1454701392470.735
2016-02-05 20:43:12.161 ThaliTest[1313:2385251] server: accepting invitation 1454701392470.735
,2016-02-05 20:43:14.915 ThaliTest[1313:2386083] server session: connected
2016-02-05 20:43:14.915 ThaliTest[1313:2386083] server session: stateChange:1->2 1454701392470.735
,2016-02-05 20:43:14.923 ThaliTest[1313:2385251] server relay: socket disconnected
2016-02-05 20:43:14.923 ThaliTest[1313:2385251] server relay: 0x172a8ef0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLoc,alizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-05 20:43:14.971 ThaliTest[1313:2386101] server session: not connected 1454701392470.735
,2016-02-05 20:43:15.087 ThaliTest[1313:2386101] client session: connected
2016-02-05 20:43:15.087 ThaliTest[1313:2386101] client session: stateChange:1->2 1454701392470.735.UkKx9A==
,2016-02-05 20:43:15.095 ThaliTest[1313:2386101] client session: fireConnectCallback: 1454701392470.735.UkKx9A==
2016-02-05 20:43:15.096 ThaliTest[1313:2386101] jxcore: connect: success
ok 105 Should be able to connect without error

,ok 106 Port should be within range

,2016-02-05 20:43:15.101 ThaliTest[1313:2385578] jxcore: connect 1454701392470.735.UkKx9A==
2016-02-05 20:43:15.102 ThaliTest[1313:2385578] client: already connect(ing/ed) to 1454701392470.735.UkKx9A==
2016-02-05 20:43:15.102 ThaliTest[1313:2385578] jxcor,e: connect: fail: Aleady connecting
ok 107 Should fail on double connect

2016-02-05 20:43:15.105 ThaliTest[1313:2385578] jxcore: disconnect
2016-02-05 20:43:15.105 ThaliTest[1313:2385578] client session: disconnectFromPeer: 1454701392470.735.UkKx9A==,
2016-02-05 20:43:15.105 ThaliTest[1313:2385578] client session: disconnect
2016-02-05 20:43:15.106 ThaliTest[1313:2385578] client session: stateChange:2->0 1454701392470.735.UkKx9A==
,2016-02-05 20:43:15.185 ThaliTest[1313:2385578] jxcore: disconnect: success
,ok 108 Should be able to disconnect without error

,setting stopBroadcasting callback and ending test.

,# teardown

,calling stopBroadcasting

,2016-02-05 20:43:15.639 ThaliTest[1313:2385578] jxcore: stopBroadcasting
2016-02-05 20:43:15.640 ThaliTest[1313:2385578] THEMultipeerSession stopping peer
2016-02-05 20:43:15.640 ThaliTest[1313:2385578] multipeer session: stop timer
2016-02-05 20:43:15.,641 ThaliTest[1313:2385578] client session: disconnect
2016-02-05 20:43:15.641 ThaliTest[1313:2385578] client session: stateChange:1->0 1454701386755.735.Arvtkw==
2016-02-05 20:43:15.642 ThaliTest[1313:2385578] server session: disconnect
2016-02-05 20:4,3:15.643 ThaliTest[1313:2385578] server session: stateChange:2->0 1454701392470.735
2016-02-05 20:43:15.644 ThaliTest[1313:2385578] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# setup

,# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,2016-02-05 20:43:15.971 ThaliTest[1313:2385578] jxcore: startBroadcasting
,2016-02-05 20:43:15.975 ThaliTest[1313:2385578] server: starting 1454701395970.1313.zo8WgA==
2016-02-05 20:43:15.976 ThaliTest[1313:2385578] multipeer session: start timer: 0x176194b0
2016-02-05 20:43:15.976 ThaliTest[1313:2385578] THEMultipeerSession in,itialized peer 1454701395970.1313
2016-02-05 20:43:15.977 ThaliTest[1313:2385578] jxcore: startBroadcasting: success
ok 109 Should be able to call startBroadcasting without error

,2016-02-05 20:43:16.890 ThaliTest[1313:2385251] client: found peer: 1454701392470.735.UkKx9A==
2016-02-05 20:43:16.891 ThaliTest[1313:2385578] jxcore: connect 1454701392470.735.UkKx9A==
2016-02-05 20:43:16.892 ThaliTest[1313:2385578] client session: connect
2016-02-05 20:43:16.892 ThaliTest[1313:2385578] client session: stateChange:0->1 1454701392470.735.UkKx9A==
,2016-02-05 20:43:16.944 ThaliTest[1313:2385251] client: found peer: 1454701397548.735.zXyGdw==
,2016-02-05 20:43:16.945 ThaliTest[1313:2385578] jxcore: connect 1454701397548.735.zXyGdw==
2016-02-05 20:43:16.946 ThaliTest[1313:2385578] client session: connect
2016-02-05 20:43:16.947 ThaliTest[1313:2385578] client session: stateChange:0->1 1454701397,548.735.zXyGdw==
,2016-02-05 20:43:17.362 ThaliTest[1313:2385251] multipeer session: reset timer
,2016-02-05 20:43:17.362 ThaliTest[1313:2385251] multipeer session: stop timer
2016-02-05 20:43:17.364 ThaliTest[1313:2385251] multipeer session: start timer: 0x176194b0
2016-02-05 20:43:17.365 ThaliTest[1313:2385251] server session: connect
2016-02-05 2,0:43:17.365 ThaliTest[1313:2385251] server session: stateChange:0->1 1454701397548.735
,2016-02-05 20:43:17.376 ThaliTest[1313:2385251] server: accepting invitation 1454701397548.735
,2016-02-05 20:43:20.089 ThaliTest[1313:2386099] server session: connected
2016-02-05 20:43:20.089 ThaliTest[1313:2386099] server session: stateChange:1->2 1454701397548.735
2016-02-05 20:43:20.098 ThaliTest[1313:2385251] server relay: socket disconnected,
2016-02-05 20:43:20.098 ThaliTest[1313:2385251] server relay: 0x176277e0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-05 20:43:20.176 ThaliTest[1313:2386098] client session: connected
,2016-02-05 20:43:20.177 ThaliTest[1313:2386098] client session: stateChange:1->2 1454701397548.735.zXyGdw==
,2016-02-05 20:43:20.183 ThaliTest[1313:2386098] client session: fireConnectCallback: 1454701397548.735.zXyGdw==
2016-02-05 20:43:20.183 ThaliTest[1313:2386098] jxcore: connect: success
,ok 110 Should be able to connect without error

,ok 111 Port should be within range

,2016-02-05 20:43:20.187 ThaliTest[1313:2385578] jxcore: disconnect
,2016-02-05 20:43:20.188 ThaliTest[1313:2385578] client session: disconnectFromPeer: 1454701397548.735.zXyGdw==
,2016-02-05 20:43:20.189 ThaliTest[1313:2385578] client session: disconnect
,2016-02-05 20:43:20.190 ThaliTest[1313:2385578] client session: stateChange:2->0 1454701397548.735.zXyGdw==
,2016-02-05 20:43:20.203 ThaliTest[1313:2386098] server session: not connected 1454701397548.735
,2016-02-05 20:43:20.277 ThaliTest[1313:2385578] jxcore: disconnect: success
ok 112 Should be able to disconnect without error

,2016-02-05 20:43:20.279 ThaliTest[1313:2385578] jxcore: disconnect
2016-02-05 20:43:20.280 ThaliTest[1313:2385578] jxcore: disconnect: fail
,ok 113 Disconnect should fail 

,setting stopBroadcasting callback and ending test.

,# teardown

,calling stopBroadcasting

,2016-02-05 20:43:20.354 ThaliTest[1313:2385578] jxcore: stopBroadcasting
2016-02-05 20:43:20.354 ThaliTest[1313:2385578] THEMultipeerSession stopping peer
2016-02-05 20:43:20.355 ThaliTest[1313:2385578] multipeer session: stop timer
2016-02-05 20:43:20.,355 ThaliTest[1313:2385578] client session: disconnect
2016-02-05 20:43:20.355 ThaliTest[1313:2385578] client session: stateChange:1->0 1454701392470.735.UkKx9A==
2016-02-05 20:43:20.356 ThaliTest[1313:2385578] server session: disconnect
2016-02-05 20:4,3:20.356 ThaliTest[1313:2385578] server session: stateChange:2->0 1454701397548.735
2016-02-05 20:43:20.360 ThaliTest[1313:2385578] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# setup

,# ThaliEmitter can connect and send data

,echo server started on port: 57340

,2016-02-05 20:43:22.100 ThaliTest[1313:2385578] jxcore: startBroadcasting
,2016-02-05 20:43:22.102 ThaliTest[1313:2385578] server: starting 1454701402099.1313.hPRMKw==
,2016-02-05 20:43:22.103 ThaliTest[1313:2385578] multipeer session: start timer: 0x14e0af10
,2016-02-05 20:43:22.104 ThaliTest[1313:2385578] THEMultipeerSession initialized peer 1454701402099.1313
,2016-02-05 20:43:22.105 ThaliTest[1313:2385578] jxcore: startBroadcasting: success
,ok 114 Should be able to call startBroadcasting without error

,2016-02-05 20:43:22.111 ThaliTest[1313:2385251] client: found peer: 1454701397548.735.zXyGdw==
,2016-02-05 20:43:22.111 ThaliTest[1313:2385578] jxcore: connect 1454701397548.735.zXyGdw==
,2016-02-05 20:43:22.112 ThaliTest[1313:2385578] client session: connect
,2016-02-05 20:43:22.112 ThaliTest[1313:2385578] client session: stateChange:0->1 1454701397548.735.zXyGdw==
,2016-02-05 20:43:22.581 ThaliTest[1313:2385251] client: found peer: 1454701403087.735.FB5Qcw==
2016-02-05 20:43:22.583 ThaliTest[1313:2385578] jxcore: connect 1454701403087.735.FB5Qcw==
2016-02-05 20:43:22.583 ThaliTest[1313:2385578] client session: conn,ect
,2016-02-05 20:43:22.583 ThaliTest[1313:2385578] client session: stateChange:0->1 1454701403087.735.FB5Qcw==
,2016-02-05 20:43:23.316 ThaliTest[1313:2385251] multipeer session: reset timer
2016-02-05 20:43:23.317 ThaliTest[1313:2385251] multipeer session: stop timer
2016-02-05 20:43:23.318 ThaliTest[1313:2385251] multipeer session: start timer: 0x14e0af10
2016-02-05 20:43:23.318 ThaliTest[1313:2385251] server session: connect
,2016-02-05 20:43:23.318 ThaliTest[1313:2385251] server session: stateChange:0->1 1454701403087.735
,2016-02-05 20:43:23.324 ThaliTest[1313:2385251] server: accepting invitation 1454701403087.735
,2016-02-05 20:43:25.444 ThaliTest[1313:2386083] client session: connected
2016-02-05 20:43:25.445 ThaliTest[1313:2386083] client session: stateChange:1->2 1454701403087.735.FB5Qcw==
,2016-02-05 20:43:25.455 ThaliTest[1313:2386083] client session: fireConnectCallback: 1454701403087.735.FB5Qcw==
2016-02-05 20:43:25.455 ThaliTest[1313:2386083] jxcore: connect: success
ok 115 Should be able to connect without error

ok 116 Port should ,be within range

2016-02-05 20:43:25.461 ThaliTest[1313:2385251] client: relay established
2016-02-05 20:43:25.461 ThaliTest[1313:2385251] client: new accepted socket: 0x163dcf10
,data in 18615

,data in 29565

,data in 47085

,data in 62415

,data in 76650

,data in 95123

,data in 106215

,data in 107310

,data in 110595

,data in 131072

,ok 117 the test messages should be equal

,2016-02-05 20:43:25.785 ThaliTest[1313:2385578] jxcore: disconnect
,2016-02-05 20:43:25.785 ThaliTest[1313:2385578] client session: disconnectFromPeer: 1454701403087.735.FB5Qcw==
,2016-02-05 20:43:25.785 ThaliTest[1313:2385578] client session: disconnect
,2016-02-05 20:43:25.785 ThaliTest[1313:2385578] client session: stateChange:2->0 1454701403087.735.FB5Qcw==
,2016-02-05 20:43:25.854 ThaliTest[1313:2385578] jxcore: disconnect: success
,ok 118 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# teardown

,2016-02-05 20:43:25.916 ThaliTest[1313:2386101] server session: connected
2016-02-05 20:43:25.916 ThaliTest[1313:2386101] server session: stateChange:1->2 1454701403087.735
,2016-02-05 20:43:25.919 ThaliTest[1313:2385251] server relay: connected (to port: 57340)
,2016-02-05 20:43:26.147 ThaliTest[1313:2386973] server session: not connected 1454701403087.735
,calling stopBroadcasting

,2016-02-05 20:43:26.207 ThaliTest[1313:2385578] jxcore: stopBroadcasting
2016-02-05 20:43:26.207 ThaliTest[1313:2385578] THEMultipeerSession stopping peer
2016-02-05 20:43:26.207 ThaliTest[1313:2385578] multipeer session: stop timer
2016-02-05 20:43:26.,208 ThaliTest[1313:2385578] client session: disconnect
2016-02-05 20:43:26.208 ThaliTest[1313:2385578] client session: stateChange:1->0 1454701397548.735.zXyGdw==
2016-02-05 20:43:26.208 ThaliTest[1313:2385578] server session: disconnect
2016-02-05 20:4,3:26.208 ThaliTest[1313:2385578] server session: stateChange:2->0 1454701403087.735
,2016-02-05 20:43:26.213 ThaliTest[1313:2385578] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# setup

,# ThaliEmitter handles socket disconnect correctly

,echo server started on port: 57347

,2016-02-05 20:43:26.735 ThaliTest[1313:2385578] jxcore: startBroadcasting
,2016-02-05 20:43:26.739 ThaliTest[1313:2385578] server: starting 1454701406734.1313.htI4ng==
2016-02-05 20:43:26.740 ThaliTest[1313:2385578] multipeer session: start timer: 0x17192ae0
2016-02-05 20:43:26.740 ThaliTest[1313:2385578] THEMultipeerSession initialized peer 1454701406734.1313
2016-02-05 20:43:26.741 ThaliTest[1313:2385578] jxcore: startBroadcasting: success
,ok 119 Should be able to call startBroadcasting without error

,2016-02-05 20:43:27.238 ThaliTest[1313:2385251] client: found peer: 1454701403087.735.FB5Qcw==
[{"peerIdentifier":"1454701403087.735.FB5Qcw==","peerName":"(null)","peerAvailable":true}]

2016-02-05 20:43:27.240 ThaliTest[1313:2385578] jxcore: connect 1454701403087.735.FB5Qcw==
2016-02-05 20:43:27.240 ThaliTest[1313:2385578] client session: connect
2016-02-05 20:43:27.241 ThaliTest[1313:2385578] client session: stateChange:0->1 1454701403087.735.FB5Qcw==
,2016-02-05 20:43:28.479 ThaliTest[1313:2385251] client: found peer: 1454701408594.735.Dt6WEQ==
[{"peerIdentifier":"1454701408594.735.Dt6WEQ==","peerName":"(null)","peerAvailable":true}]

,2016-02-05 20:43:28.481 ThaliTest[1313:2385578] jxcore: connect 1454701408594.735.Dt6WEQ==
,2016-02-05 20:43:28.482 ThaliTest[1313:2385578] client session: connect
2016-02-05 20:43:28.483 ThaliTest[1313:2385578] client session: stateChange:0->1 1454701408594.735.Dt6WEQ==
,2016-02-05 20:43:29.418 ThaliTest[1313:2385251] multipeer session: reset timer
2016-02-05 20:43:29.418 ThaliTest[1313:2385251] multipeer session: stop timer
2016-02-05 20:43:29.419 ThaliTest[1313:2385251] multipeer session: start timer: 0x17192ae0
2016-,02-05 20:43:29.419 ThaliTest[1313:2385251] server session: connect
2016-02-05 20:43:29.419 ThaliTest[1313:2385251] server session: stateChange:0->1 1454701408594.735
,2016-02-05 20:43:29.431 ThaliTest[1313:2385251] server: accepting invitation 1454701408594.735
,2016-02-05 20:43:33.487 ThaliTest[1313:2386083] server session: connected
,2016-02-05 20:43:33.487 ThaliTest[1313:2386083] server session: stateChange:1->2 1454701408594.735
,2016-02-05 20:43:34.209 ThaliTest[1313:2385251] server relay: connected (to port: 57347)
,2016-02-05 20:43:36.269 ThaliTest[1313:2386973] client session: connected
2016-02-05 20:43:36.269 ThaliTest[1313:2386973] client session: stateChange:1->2 1454701408594.735.Dt6WEQ==
,2016-02-05 20:43:36.298 ThaliTest[1313:2386083] client session: fireConnectCallback: 1454701408594.735.Dt6WEQ==
2016-02-05 20:43:36.298 ThaliTest[1313:2386083] jxcore: connect: success
,ok 120 Should be able to connect without error

,ok 121 Port should be within range

,ok 122 First connect should succeed

,2016-02-05 20:43:36.351 ThaliTest[1313:2385251] client: relay established
2016-02-05 20:43:36.351 ThaliTest[1313:2385251] client: new accepted socket: 0x14eb38f0
,ok 123 the test messages should be equal

,ok 124 First send should succeed

,2016-02-05 20:43:36.422 ThaliTest[1313:2385251] client: socket closed
,2016-02-05 20:43:36.422 ThaliTest[1313:2385251] client relay: socket disconnected
,2016-02-05 20:43:36.423 ThaliTest[1313:2385251] client relay: 0x14eb38f0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-02-05 20:43:,36.423 ThaliTest[1313:2385251] client session: socket closed: 1454701408594.735.Dt6WEQ==
,2016-02-05 20:43:36.424 ThaliTest[1313:2385251] client session: onLinkFailure: 1454701408594.735.Dt6WEQ==
2016-02-05 20:43:36.424 ThaliTest[1313:2385251] client session: disconnect
2016-02-05 20:43:36.424 ThaliTest[1313:2385251] client session: stateChan,ge:2->0 1454701408594.735.Dt6WEQ==
,2016-02-05 20:43:36.438 ThaliTest[1313:2385251] client session: fireConnectionErrorEvent: 1454701408594.735.Dt6WEQ==
,2016-02-05 20:43:36.452 ThaliTest[1313:2385578] jxcore: connect 1454701408594.735.Dt6WEQ==
,2016-02-05 20:43:36.454 ThaliTest[1313:2385578] client session: connect
,2016-02-05 20:43:36.456 ThaliTest[1313:2385578] client session: stateChange:0->1 1454701408594.735.Dt6WEQ==
,2016-02-05 20:43:36.992 ThaliTest[1313:2385251] multipeer session: reset timer
2016-02-05 20:43:36.993 ThaliTest[1313:2385251] multipeer session: stop timer
2016-02-05 20:43:36.993 ThaliTest[1313:2385251] multipeer session: start timer: 0x17192ae0
2016-02-05 20:43:36.994 ThaliTest[1313:2385251] server: disconnecting to refresh session (1454701408594.735)
2016-02-05 20:43:36.994 ThaliTest[1313:2385251] server session: disconnect
2016-02-05 20:43:36.995 ThaliTest[1313:2385251] server session: stateChange,:2->0 1454701408594.735
,2016-02-05 20:43:37.027 ThaliTest[1313:2385251] server session: connect
2016-02-05 20:43:37.029 ThaliTest[1313:2385251] server session: stateChange:0->1 1454701408594.735
,2016-02-05 20:43:37.084 ThaliTest[1313:2385251] server: accepting invitation 1454701408594.735
,2016-02-05 20:43:38.128 ThaliTest[1313:2386973] server session: not connected 1454701408594.735
,2016-02-05 20:43:43.260 ThaliTest[1313:2385251] client: lost peer: 1454701403087.735.FB5Qcw==
2016-02-05 20:43:43.261 ThaliTest[1313:2385251] client session: onPeerLost: 1454701403087.735.FB5Qcw==
2016-02-05 20:43:43.261 ThaliTest[1313:2385251] client se,ssion: onLinkFailure: 1454701403087.735.FB5Qcw==
2016-02-05 20:43:43.261 ThaliTest[1313:2385251] client session: disconnect
2016-02-05 20:43:43.262 ThaliTest[1313:2385251] client session: stateChange:1->0 1454701403087.735.FB5Qcw==
2016-02-05 20:43:43.2,62 ThaliTest[1313:2385251] client session: fireConnectCallback: 1454701403087.735.FB5Qcw==
2016-02-05 20:43:43.263 ThaliTest[1313:2385251] jxcore: connect: fail: Peer disconnected
[{"peerIdentifier":"1454701403087.735.FB5Qcw==","peerName":"(null)","peerAvailable":false}]

,2016-02-05 20:43:44.270 ThaliTest[1313:2385578] jxcore: connect 1454701403087.735.FB5Qcw==
2016-02-05 20:43:44.271 ThaliTest[1313:2385578] client: connect: unreachable 1454701403087.735.FB5Qcw==
2016-02-05 20:43:44.271 ThaliTest[1313:2385578] jxcore: connect: fail: Peer unreachable
,2016-02-05 20:43:47.400 ThaliTest[1313:2387009] client session: not connected 1454701408594.735.Dt6WEQ==
,2016-02-05 20:43:47.401 ThaliTest[1313:2387009] client session: onLinkFailure: 1454701408594.735.Dt6WEQ==
,2016-02-05 20:43:47.402 ThaliTest[1313:2387009] client session: disconnect
,2016-02-05 20:43:47.403 ThaliTest[1313:2387009] client session: stateChange:1->0 1454701408594.735.Dt6WEQ==
,2016-02-05 20:43:47.405 ThaliTest[1313:2387009] client session: fireConnectCallback: 1454701408594.735.Dt6WEQ==
,2016-02-05 20:43:47.406 ThaliTest[1313:2387009] jxcore: connect: fail: Peer disconnected
,2016-02-05 20:43:48.410 ThaliTest[1313:2385578] jxcore: connect 1454701408594.735.Dt6WEQ==
2016-02-05 20:43:48.410 ThaliTest[1313:2385578] client session: connect
2016-02-05 20:43:48.410 ThaliTest[1313:2385578] client session: stateChange:0->1 1454701408594.735.Dt6WEQ==
,2016-02-05 20:43:50.177 ThaliTest[1313:2386973] client session: connected
2016-02-05 20:43:50.178 ThaliTest[1313:2386973] client session: stateChange:1->2 1454701408594.735.Dt6WEQ==
,2016-02-05 20:43:50.524 ThaliTest[1313:2386083] client session: fireConnectCallback: 1454701408594.735.Dt6WEQ==
2016-02-05 20:43:50.524 ThaliTest[1313:2386083] jxcore: connect: success
,ok 125 Should be able to connect without error

,ok 126 Port should be within range

,ok 127 Second connect should succeed

,2016-02-05 20:43:50.561 ThaliTest[1313:2385251] client: relay established
2016-02-05 20:43:50.561 ThaliTest[1313:2385251] client: new accepted socket: 0x14ee7e50
,ok 128 the test messages should be equal

,ok 129 Second send should succeed

,# teardown

,2016-02-05 20:43:52.104 ThaliTest[1313:2385251] client: socket closed
2016-02-05 20:43:52.104 ThaliTest[1313:2385251] client relay: socket disconnected
2016-02-05 20:43:52.104 ThaliTest[1313:2385251] client relay: 0x14ee7e50 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-02-05 20:43:52.105 ThaliTest[1313:2385251] client session: socket closed: 1454701408594.735.Dt6WEQ==
2016-02-05 2,0:43:52.105 ThaliTest[1313:2385251] client session: onLinkFailure: 1454701408594.735.Dt6WEQ==
2016-02-05 20:43:52.105 ThaliTest[1313:2385251] client session: disconnect
2016-02-05 20:43:52.105 ThaliTest[1313:2385251] client session: stateChange:2->0 1454,701408594.735.Dt6WEQ==
,2016-02-05 20:43:52.186 ThaliTest[1313:2385251] client session: fireConnectionErrorEvent: 1454701408594.735.Dt6WEQ==
,2016-02-05 20:43:58.011 ThaliTest[1313:2385251] multipeer session: reset timer
2016-02-05 20:43:58.011 ThaliTest[1313:2385251] multipeer session: stop timer
2016-02-05 20:43:58.012 ThaliTest[1313:2385251] multipeer session: start timer: 0x17192ae0
2016-,02-05 20:43:58.012 ThaliTest[1313:2385251] server: disconnecting to refresh session (1454701408594.735)
2016-02-05 20:43:58.013 ThaliTest[1313:2385251] server session: disconnect
2016-02-05 20:43:58.013 ThaliTest[1313:2385251] server session: stateChange,:1->0 1454701408594.735
,2016-02-05 20:43:58.069 ThaliTest[1313:2385251] server session: connect
2016-02-05 20:43:58.069 ThaliTest[1313:2385251] server session: stateChange:0->1 1454701408594.735
2016-02-05 20:43:58.078 ThaliTest[1313:2385251] server: accepting invitation 1454701408594.735
,2016-02-05 20:44:28.014 ThaliTest[1313:2385251] multipeer session: restart
,2016-02-05 20:44:28.053 ThaliTest[1313:2385251] client: found peer: 1454701408594.735.Dt6WEQ==
,2016-02-05 20:44:58.014 ThaliTest[1313:2385251] multipeer session: restart
,2016-02-05 20:44:58.052 ThaliTest[1313:2385251] client: found peer: 1454701408594.735.Dt6WEQ==
,2016-02-05 20:45:28.014 ThaliTest[1313:2385251] multipeer session: restart
,2016-02-05 20:45:58.014 ThaliTest[1313:2385251] multipeer session: restart
,2016-02-05 20:45:58.046 ThaliTest[1313:2385251] client: found peer: 1454701408594.735.Dt6WEQ==
,2016-02-05 20:46:28.014 ThaliTest[1313:2385251] multipeer session: restart
,2016-02-05 20:46:42.789 ThaliTest[1313:2387455] server session: not connected 1454701408594.735
,2016-02-05 20:46:58.014 ThaliTest[1313:2385251] multipeer session: restart
,2016-02-05 20:47:28.014 ThaliTest[1313:2385251] multipeer session: restart
,2016-02-05 20:47:58.014 ThaliTest[1313:2385251] multipeer session: restart
,2016-02-05 20:48:28.014 ThaliTest[1313:2385251] multipeer session: restart
,2016-02-05 20:48:58.013 ThaliTest[1313:2385251] multipeer session: restart
,2016-02-05 20:49:28.014 ThaliTest[1313:2385251] multipeer session: restart
,2016-02-05 20:49:58.014 ThaliTest[1313:2385251] multipeer session: restart
,2016-02-05 20:50:28.014 ThaliTest[1313:2385251] multipeer session: restart
,2016-02-05 20:50:58.014 ThaliTest[1313:2385251] multipeer session: restart
,2016-02-05 20:51:28.014 ThaliTest[1313:2385251] multipeer session: restart
,2016-02-05 20:51:58.013 ThaliTest[1313:2385251] multipeer session: restart
,2016-02-05 20:52:28.014 ThaliTest[1313:2385251] multipeer session: restart
,2016-02-05 20:52:58.014 ThaliTest[1313:2385251] multipeer session: restart
,2016-02-05 20:53:28.014 ThaliTest[1313:2385251] multipeer session: restart
,2016-02-05 20:53:58.013 ThaliTest[1313:2385251] multipeer session: restart
,2016-02-05 20:54:28.014 ThaliTest[1313:2385251] multipeer session: restart
,2016-02-05 20:54:58.014 ThaliTest[1313:2385251] multipeer session: restart
,2016-02-05 20:55:28.014 ThaliTest[1313:2385251] multipeer session: restart

```
