#### Test 58380500fccea7e_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/58380500fccea7e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/7A66461E-4846-4F20-ABB9-4EF319139A2B/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/7A66461E-4846-4F20-ABB9-4EF319139A2B/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/58380500fccea7e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/58380500fccea7e/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A3CE4745-193D-4F3B-9341-34FFEC3DB50D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51181"
,(lldb)     command script import "/tmp/7A66461E-4846-4F20-ABB9-4EF319139A2B/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-06 01:12:30.088 ThaliTest[1351:2418446] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F629E397-A9F7-4B66-90FF-3998B5B12F6E/Library/Cookies/Cookies.binarycookies
,2016-02-06 01:12:30.584 ThaliTest[1351:2418446] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-06 01:12:30.585 ThaliTest[1351:2418446] Multi-tasking -> Device: YES, App: YES
,2016-02-06 01:12:30.596 ThaliTest[1351:2418446] Unlimited access to network resources
,2016-02-06 01:12:30.610 ThaliTest[1351:2418446] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-06 01:12:40.286 ThaliTest[1351:2418446] Resetting plugins due to page load.
,2016-02-06 01:12:43.751 ThaliTest[1351:2418446] Finished load of: file:///var/mobile/Containers/Bundle/Application/A3CE4745-193D-4F3B-9341-34FFEC3DB50D/ThaliTest.app/www/index.html
,2016-02-06 01:12:43.927 ThaliTest[1351:2418446] JXcore Cordova plugin initializing
2016-02-06 01:12:43.931 ThaliTest[1351:2418768] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A3CE4745-193D-4F3B-9341-34FFEC3DB50D/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A3CE4745-193D-4F3B-9341-34FFEC3DB50D/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A3CE4745-193D-4F3B-9341-34FFEC3DB50D/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A3CE4745-193D-4F3B-9341-34FFEC3DB50D/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A3CE4745-193D-4F3B-9341-34FFEC3DB50D/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A3CE4745-193D-4F3B-9341-34FFEC3DB50D/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A3CE4745-193D-4F3B-9341-34FFEC3DB50D/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A3CE4745-193D-4F3B-9341-34FFEC3DB50D/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A3CE4745-193D-4F3B-9341-34FFEC3DB50D/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

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

ok 7 should be equal

,ok 8 should be equal

,# teardown

,# setup

,# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

,ok 9 should throw

# teardown

# setup

,# #parseBeacons invalid expiration in beaconStreamWithPreAmble

,ok 10 should throw

# teardown

,# setup

# #parseBeacons no beacons returns null

,ok 11 should be equal

,# teardown

# setup

,# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

,ok 12 should throw

,# teardown

# setup

,# #parseBeacons addressBookCallback fails decrypt

,ok 13 should be equal

,# teardown

,# setup

,# #parseBeacons addressBookCallback returns null for all

,ok 14 (unnamed assert)

,ok 15 should be equal

# teardown

,# setup

# #parseBeacons addressBookCallback returns public key

,ok 16 (unnamed assert)

,ok 17 (unnamed assert)

# teardown

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

,ok 34 should be equal

,ok 35 should not throw

# teardown

,# setup

,# successfully read a previous pkcs12 file and return hash value

,ok 36 (unnamed assert)

,ok 37 (unnamed assert)

ok 38 should not throw

,ok 39 should be equal

,ok 40 should be equal

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

,2016-02-06 01:17:20.692 ThaliTest[1351:2418768] jxcore: startBroadcasting
,2016-02-06 01:17:20.708 ThaliTest[1351:2418768] server: starting 1454717840691.1351.KtvCcg==
,2016-02-06 01:17:20.710 ThaliTest[1351:2418768] multipeer session: start timer: 0x18faa890
2016-02-06 01:17:20.711 ThaliTest[1351:2418768] THEMultipeerSession initialized peer 1454717840691.1351
2016-02-06 01:17:20.711 ThaliTest[1351:2418768] jxcore: startBroadcasting: success
,ok 72 Should be able to call startBroadcasting without error

2016-02-06 01:17:20.715 ThaliTest[1351:2418768] jxcore: stopBroadcasting
2016-02-06 01:17:20.715 ThaliTest[1351:2418768] THEMultipeerSession stopping peer
2016-02-06 01:17:20.716 ThaliTest[1351:2418768] multipeer session: stop timer
2016-02-06 01:17:20.717 ThaliTest[1351:2418768] jxcore: stopBroadcasting: success
,ok 73 Should be able to call stopBroadcasting without error

,2016-02-06 01:17:20.719 ThaliTest[1351:2418768] jxcore: startBroadcasting
,2016-02-06 01:17:20.726 ThaliTest[1351:2418768] server: starting 1454717840718.1351.CB9qEQ==
2016-02-06 01:17:20.727 ThaliTest[1351:2418768] multipeer session: start timer: 0x18fc6a90
2016-02-06 01:17:20.728 ThaliTest[1351:2418768] THEMultipeerSession in,itialized peer 1454717840718.1351
2016-02-06 01:17:20.728 ThaliTest[1351:2418768] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error

2016-02-06 01:17:20.730 ThaliTest[1351:2418768] jxcore: stopBroadcasting,
2016-02-06 01:17:20.730 ThaliTest[1351:2418768] THEMultipeerSession stopping peer
2016-02-06 01:17:20.730 ThaliTest[1351:2418768] multipeer session: stop timer
2016-02-06 01:17:20.731 ThaliTest[1351:2418768] jxcore: stopBroadcasting: success
ok 75 Shou,ld be able to call stopBroadcasting without error

2016-02-06 01:17:20.732 ThaliTest[1351:2418768] jxcore: startBroadcasting
,2016-02-06 01:17:20.747 ThaliTest[1351:2418768] server: starting 1454717840732.1351.VezvWg==
2016-02-06 01:17:20.748 ThaliTest[1351:2418768] multipeer session: start timer: 0x19e97160
2016-02-06 01:17:20.748 ThaliTest[1351:2418768] THEMultipeerSession in,itialized peer 1454717840732.1351
2016-02-06 01:17:20.749 ThaliTest[1351:2418768] jxcore: startBroadcasting: success
,ok 76 Should be able to call startBroadcasting without error

,2016-02-06 01:17:20.753 ThaliTest[1351:2418768] jxcore: stopBroadcasting
2016-02-06 01:17:20.754 ThaliTest[1351:2418768] THEMultipeerSession stopping peer
2016-02-06 01:17:20.755 ThaliTest[1351:2418768] multipeer session: stop timer
2016-02-06 01:17:20.755 ThaliTest[1351:2418768] jxcore: stopBroadcasting: success
ok 77 Should be able to call stopBroadcasting without error

2016-02-06 01:17:20.757 ThaliTest[1351:2418768] jxcore: startBroadcasting
,2016-02-06 01:17:20.770 ThaliTest[1351:2418768] server: starting 1454717840757.1351.SDN/wQ==
2016-02-06 01:17:20.771 ThaliTest[1351:2418768] multipeer session: start timer: 0x19e96060
2016-02-06 01:17:20.772 ThaliTest[1351:2418768] THEMultipeerSession in,itialized peer 1454717840757.1351
2016-02-06 01:17:20.774 ThaliTest[1351:2418768] jxcore: startBroadcasting: success
ok 78 Should be able to call startBroadcasting without error

2016-02-06 01:17:20.777 ThaliTest[1351:2418768] jxcore: stopBroadcasting,
2016-02-06 01:17:20.777 ThaliTest[1351:2418768] THEMultipeerSession stopping peer
2016-02-06 01:17:20.777 ThaliTest[1351:2418768] multipeer session: stop timer
2016-02-06 01:17:20.778 ThaliTest[1351:2418768] jxcore: stopBroadcasting: success
,ok 79 Should be able to call stopBroadcasting without error
,
,2016-02-06 01:17:20.790 ThaliTest[1351:2418768] jxcore: startBroadcasting
,2016-02-06 01:17:20.803 ThaliTest[1351:2418768] server: starting 1454717840789.1351.A04V0Q==
,2016-02-06 01:17:20.807 ThaliTest[1351:2418768] multipeer session: start timer: 0x19e957b0
,2016-02-06 01:17:20.810 ThaliTest[1351:2418768] THEMultipeerSession initialized peer 1454717840789.1351
,2016-02-06 01:17:20.812 ThaliTest[1351:2418768] jxcore: startBroadcasting: success
,ok 80 Should be able to call startBroadcasting without error

,2016-02-06 01:17:20.815 ThaliTest[1351:2418768] jxcore: stopBroadcasting
,2016-02-06 01:17:20.815 ThaliTest[1351:2418768] THEMultipeerSession stopping peer
,2016-02-06 01:17:20.817 ThaliTest[1351:2418768] multipeer session: stop timer
,2016-02-06 01:17:20.818 ThaliTest[1351:2418768] jxcore: stopBroadcasting: success
,ok 81 Should be able to call stopBroadcasting without error

,2016-02-06 01:17:20.823 ThaliTest[1351:2418768] jxcore: startBroadcasting
,2016-02-06 01:17:20.826 ThaliTest[1351:2418768] server: starting 1454717840822.1351.X/kS5g==
,2016-02-06 01:17:20.828 ThaliTest[1351:2418768] multipeer session: start timer: 0x19e97bf0
,2016-02-06 01:17:20.834 ThaliTest[1351:2418768] THEMultipeerSession initialized peer 1454717840822.1351
,2016-02-06 01:17:20.835 ThaliTest[1351:2418768] jxcore: startBroadcasting: success
,ok 82 Should be able to call startBroadcasting without error

,2016-02-06 01:17:20.837 ThaliTest[1351:2418768] jxcore: stopBroadcasting
,2016-02-06 01:17:20.837 ThaliTest[1351:2418768] THEMultipeerSession stopping peer
,2016-02-06 01:17:20.838 ThaliTest[1351:2418768] multipeer session: stop timer
,2016-02-06 01:17:20.839 ThaliTest[1351:2418768] jxcore: stopBroadcasting: success
,ok 83 Should be able to call stopBroadcasting without error

,2016-02-06 01:17:20.844 ThaliTest[1351:2418768] jxcore: startBroadcasting
,2016-02-06 01:17:20.847 ThaliTest[1351:2418768] server: starting 1454717840844.1351.iUgaEQ==
,2016-02-06 01:17:20.849 ThaliTest[1351:2418768] multipeer session: start timer: 0x18fc7250
,2016-02-06 01:17:20.852 ThaliTest[1351:2418768] THEMultipeerSession initialized peer 1454717840844.1351
,2016-02-06 01:17:20.853 ThaliTest[1351:2418768] jxcore: startBroadcasting: success
,ok 84 Should be able to call startBroadcasting without error

,2016-02-06 01:17:20.857 ThaliTest[1351:2418768] jxcore: stopBroadcasting
,2016-02-06 01:17:20.858 ThaliTest[1351:2418768] THEMultipeerSession stopping peer
,2016-02-06 01:17:20.858 ThaliTest[1351:2418768] multipeer session: stop timer
,2016-02-06 01:17:20.861 ThaliTest[1351:2418768] jxcore: stopBroadcasting: success
,ok 85 Should be able to call stopBroadcasting without error

,2016-02-06 01:17:20.865 ThaliTest[1351:2418768] jxcore: startBroadcasting
,2016-02-06 01:17:20.867 ThaliTest[1351:2418768] server: starting 1454717840864.1351.7snKLA==
,2016-02-06 01:17:20.868 ThaliTest[1351:2418768] multipeer session: start timer: 0x19e98970
,2016-02-06 01:17:20.870 ThaliTest[1351:2418768] THEMultipeerSession initialized peer 1454717840864.1351
,2016-02-06 01:17:20.872 ThaliTest[1351:2418768] jxcore: startBroadcasting: success
,ok 86 Should be able to call startBroadcasting without error

,2016-02-06 01:17:20.877 ThaliTest[1351:2418768] jxcore: stopBroadcasting
,2016-02-06 01:17:20.877 ThaliTest[1351:2418768] THEMultipeerSession stopping peer
,2016-02-06 01:17:20.878 ThaliTest[1351:2418768] multipeer session: stop timer
,2016-02-06 01:17:20.879 ThaliTest[1351:2418768] jxcore: stopBroadcasting: success
,ok 87 Should be able to call stopBroadcasting without error

,2016-02-06 01:17:20.885 ThaliTest[1351:2418768] jxcore: startBroadcasting
,2016-02-06 01:17:20.887 ThaliTest[1351:2418768] server: starting 1454717840884.1351.P9rCcA==
,2016-02-06 01:17:20.888 ThaliTest[1351:2418768] multipeer session: start timer: 0x18fe5830
,2016-02-06 01:17:20.890 ThaliTest[1351:2418768] THEMultipeerSession initialized peer 1454717840884.1351
,2016-02-06 01:17:20.892 ThaliTest[1351:2418768] jxcore: startBroadcasting: success
,ok 88 Should be able to call startBroadcasting without error
,
,2016-02-06 01:17:20.897 ThaliTest[1351:2418768] jxcore: stopBroadcasting
,2016-02-06 01:17:20.899 ThaliTest[1351:2418768] THEMultipeerSession stopping peer
,2016-02-06 01:17:20.899 ThaliTest[1351:2418768] multipeer session: stop timer
,2016-02-06 01:17:20.900 ThaliTest[1351:2418768] jxcore: stopBroadcasting: success
,ok 89 Should be able to call stopBroadcasting without error

,2016-02-06 01:17:20.904 ThaliTest[1351:2418768] jxcore: startBroadcasting
,2016-02-06 01:17:20.906 ThaliTest[1351:2418768] server: starting 1454717840904.1351.fvWX4w==
,2016-02-06 01:17:20.908 ThaliTest[1351:2418768] multipeer session: start timer: 0x18f5ff90
,2016-02-06 01:17:20.913 ThaliTest[1351:2418768] THEMultipeerSession initialized peer 1454717840904.1351
,2016-02-06 01:17:20.914 ThaliTest[1351:2418768] jxcore: startBroadcasting: success
,ok 90 Should be able to call startBroadcasting without error

,2016-02-06 01:17:20.915 ThaliTest[1351:2418768] jxcore: stopBroadcasting
,2016-02-06 01:17:20.916 ThaliTest[1351:2418768] THEMultipeerSession stopping peer
,2016-02-06 01:17:20.916 ThaliTest[1351:2418768] multipeer session: stop timer
,2016-02-06 01:17:20.917 ThaliTest[1351:2418768] jxcore: stopBroadcasting: success
,ok 91 Should be able to call stopBroadcasting without error

,# teardown

,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,2016-02-06 01:17:21.188 ThaliTest[1351:2418768] jxcore: startBroadcasting
,2016-02-06 01:17:21.192 ThaliTest[1351:2418768] server: starting 1454717841188.1351.JO1drQ==
2016-02-06 01:17:21.192 ThaliTest[1351:2418768] multipeer session: start timer: 0x19e98e10
2016-02-06 01:17:21.193 ThaliTest[1351:2418768] THEMultipeerSession in,itialized peer 1454717841188.1351
2016-02-06 01:17:21.193 ThaliTest[1351:2418768] jxcore: startBroadcasting: success
ok 92 Should be able to call startBroadcasting without error

2016-02-06 01:17:21.195 ThaliTest[1351:2418768] jxcore: startBroadcasting,
2016-02-06 01:17:21.195 ThaliTest[1351:2418768] jxcore: startBroadcasting: failure
ok 93 Cannot call startBroadcasting twice

2016-02-06 01:17:21.198 ThaliTest[1351:2418768] jxcore: stopBroadcasting
2016-02-06 01:17:21.199 ThaliTest[1351:2418768] THE,MultipeerSession stopping peer
2016-02-06 01:17:21.199 ThaliTest[1351:2418768] multipeer session: stop timer
2016-02-06 01:17:21.199 ThaliTest[1351:2418768] jxcore: stopBroadcasting: success
ok 94 Should be able to call stopBroadcasting without error
,
,# teardown

,# setup

,# ThaliEmitter throws on connection to bad peer

,2016-02-06 01:17:25.054 ThaliTest[1351:2418768] jxcore: startBroadcasting
,2016-02-06 01:17:25.058 ThaliTest[1351:2418768] server: starting 1454717845054.1351.ixtRjg==
2016-02-06 01:17:25.059 ThaliTest[1351:2418768] multipeer session: start timer: 0x19978180
2016-02-06 01:17:25.059 ThaliTest[1351:2418768] THEMultipeerSession in,itialized peer 1454717845054.1351
2016-02-06 01:17:25.060 ThaliTest[1351:2418768] jxcore: startBroadcasting: success
ok 95 Should be able to call startBroadcasting without error

2016-02-06 01:17:25.062 ThaliTest[1351:2418768] jxcore: connect foobar
2,016-02-06 01:17:25.062 ThaliTest[1351:2418768] client: unknown peer foobar
2016-02-06 01:17:25.063 ThaliTest[1351:2418768] jxcore: connect: fail: Unknown peer
,ok 96 Should not connect to a bad peer

,2016-02-06 01:17:25.067 ThaliTest[1351:2418768] jxcore: stopBroadcasting
2016-02-06 01:17:25.068 ThaliTest[1351:2418768] THEMultipeerSession stopping peer
2016-02-06 01:17:25.068 ThaliTest[1351:2418768] multipeer session: stop timer
,2016-02-06 01:17:25.068 ThaliTest[1351:2418768] jxcore: stopBroadcasting: success
,ok 97 Should be able to call stopBroadcasting without error

# teardown

,# setup

,# ThaliEmitter throws on disconnect to bad peer

,2016-02-06 01:17:30.295 ThaliTest[1351:2418768] jxcore: startBroadcasting
,2016-02-06 01:17:30.299 ThaliTest[1351:2418768] server: starting 1454717850295.1351.zDxhYQ==
2016-02-06 01:17:30.300 ThaliTest[1351:2418768] multipeer session: start timer: 0x19e9edd0
2016-02-06 01:17:30.300 ThaliTest[1351:2418768] THEMultipeerSession in,itialized peer 1454717850295.1351
2016-02-06 01:17:30.301 ThaliTest[1351:2418768] jxcore: startBroadcasting: success
,ok 98 Should be able to call startBroadcasting without error

,2016-02-06 01:17:30.304 ThaliTest[1351:2418768] jxcore: disconnect
2016-02-06 01:17:30.304 ThaliTest[1351:2418768] jxcore: disconnect: fail
,ok 99 Disconnect should fail to a non-existant peer 

2016-02-06 01:17:30.309 ThaliTest[1351:2418768] jxcore: stopBroadcasting
,2016-02-06 01:17:30.309 ThaliTest[1351:2418768] THEMultipeerSession stopping peer
,2016-02-06 01:17:30.310 ThaliTest[1351:2418768] multipeer session: stop timer
2016-02-06 01:17:30.310 ThaliTest[1351:2418768] jxcore: stopBroadcasting: success
ok 100 Should be able to call stopBroadcasting without error

,# teardown

,# setup

,# ThaliEmitter can discover and connect to peers

,2016-02-06 01:17:31.081 ThaliTest[1351:2418768] jxcore: startBroadcasting
,2016-02-06 01:17:31.084 ThaliTest[1351:2418768] server: starting 1454717851080.1351.fN3s3Q==
2016-02-06 01:17:31.085 ThaliTest[1351:2418768] multipeer session: start timer: 0x19ea1bb0
2016-02-06 01:17:31.085 ThaliTest[1351:2418768] THEMultipeerSession initialized peer 1454717851080.1351
2016-02-06 01:17:31.086 ThaliTest[1351:2418768] jxcore: startBroadcasting: success
ok 101 Should be able to call startBroadcasting without error

,2016-02-06 01:17:32.283 ThaliTest[1351:2418446] client: found peer: 1454717852856.776.e9+C8Q==
2016-02-06 01:17:32.286 ThaliTest[1351:2418768] jxcore: connect 1454717852856.776.e9+C8Q==
,2016-02-06 01:17:32.287 ThaliTest[1351:2418768] client session: connect
,2016-02-06 01:17:32.287 ThaliTest[1351:2418768] client session: stateChange:0->1 1454717852856.776.e9+C8Q==
,2016-02-06 01:17:32.555 ThaliTest[1351:2418446] multipeer session: reset timer
,2016-02-06 01:17:32.556 ThaliTest[1351:2418446] multipeer session: stop timer
2016-02-06 01:17:32.556 ThaliTest[1351:2418446] multipeer session: start timer: 0x19ea1bb0
2016-02-06 01:17:32.557 ThaliTest[1351:2418446] server session: connect
2016-02-06 0,1:17:32.557 ThaliTest[1351:2418446] server session: stateChange:0->1 1454717852856.776
,2016-02-06 01:17:32.568 ThaliTest[1351:2418446] server: accepting invitation 1454717852856.776
,2016-02-06 01:17:35.114 ThaliTest[1351:2419225] client session: connected
2016-02-06 01:17:35.114 ThaliTest[1351:2419222] server session: connected
2016-02-06 01:17:35.114 ThaliTest[1351:2419225] client session: stateChange:1->2 1454717852856.776.e9+C8Q=,=
,2016-02-06 01:17:35.116 ThaliTest[1351:2419222] server session: stateChange:1->2 1454717852856.776
,2016-02-06 01:17:35.118 ThaliTest[1351:2419225] client session: fireConnectCallback: 1454717852856.776.e9+C8Q==
,2016-02-06 01:17:35.121 ThaliTest[1351:2419225] jxcore: connect: success
,ok 102 Should be able to connect without error

,ok 103 Port should be within range

,2016-02-06 01:17:35.126 ThaliTest[1351:2418768] jxcore: disconnect
,2016-02-06 01:17:35.128 ThaliTest[1351:2418446] server relay: socket disconnected
,2016-02-06 01:17:35.129 ThaliTest[1351:2418768] client session: disconnectFromPeer: 1454717852856.776.e9+C8Q==
,2016-02-06 01:17:35.130 ThaliTest[1351:2418446] server relay: 0x1754c7e0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-06 01:17:35.131 ThaliTest[1351:2418768] client session: disconnect
,2016-02-06 01:17:35.133 ThaliTest[1351:2418768] client session: stateChange:2->0 1454717852856.776.e9+C8Q==
,2016-02-06 01:17:35.180 ThaliTest[1351:2419222] server session: not connected 1454717852856.776
,2016-02-06 01:17:35.217 ThaliTest[1351:2418768] jxcore: disconnect: success
,ok 104 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# teardown

,calling stopBroadcasting

,2016-02-06 01:17:35.314 ThaliTest[1351:2418768] jxcore: stopBroadcasting
2016-02-06 01:17:35.315 ThaliTest[1351:2418768] THEMultipeerSession stopping peer
2016-02-06 01:17:35.315 ThaliTest[1351:2418768] multipeer session: stop timer
2016-02-06 01:17:35.,316 ThaliTest[1351:2418768] server session: disconnect
2016-02-06 01:17:35.316 ThaliTest[1351:2418768] server session: stateChange:2->0 1454717852856.776
,2016-02-06 01:17:35.319 ThaliTest[1351:2418768] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# setup

,# ThaliEmitter can discover and connect to peers and then fail on double connect

,2016-02-06 01:17:35.879 ThaliTest[1351:2418768] jxcore: startBroadcasting
,2016-02-06 01:17:35.883 ThaliTest[1351:2418768] server: starting 1454717855879.1351.ICFwxw==
2016-02-06 01:17:35.884 ThaliTest[1351:2418768] multipeer session: start timer: 0x19ea1aa0
2016-02-06 01:17:35.885 ThaliTest[1351:2418768] THEMultipeerSession in,itialized peer 1454717855879.1351
2016-02-06 01:17:35.885 ThaliTest[1351:2418768] jxcore: startBroadcasting: success
ok 105 Should be able to call startBroadcasting without error

,2016-02-06 01:17:37.067 ThaliTest[1351:2418446] client: found peer: 1454717857743.776.U236Eg==
2016-02-06 01:17:37.068 ThaliTest[1351:2418768] jxcore: connect 1454717857743.776.U236Eg==
2016-02-06 01:17:37.069 ThaliTest[1351:2418768] client session: conn,ect
2016-02-06 01:17:37.069 ThaliTest[1351:2418768] client session: stateChange:0->1 1454717857743.776.U236Eg==
,2016-02-06 01:17:37.398 ThaliTest[1351:2418446] multipeer session: reset timer
2016-02-06 01:17:37.398 ThaliTest[1351:2418446] multipeer session: stop timer
2016-02-06 01:17:37.398 ThaliTest[1351:2418446] multipeer session: start timer: 0x19ea1aa0
2016-,02-06 01:17:37.399 ThaliTest[1351:2418446] server session: connect
2016-02-06 01:17:37.399 ThaliTest[1351:2418446] server session: stateChange:0->1 1454717857743.776
,2016-02-06 01:17:37.408 ThaliTest[1351:2418446] server: accepting invitation 1454717857743.776
,2016-02-06 01:17:39.898 ThaliTest[1351:2419271] server session: connected
2016-02-06 01:17:39.901 ThaliTest[1351:2419271] server session: stateChange:1->2 1454717857743.776
,2016-02-06 01:17:39.971 ThaliTest[1351:2418446] server relay: socket disconnected
,2016-02-06 01:17:39.972 ThaliTest[1351:2419279] client session: connected
,2016-02-06 01:17:39.972 ThaliTest[1351:2418446] server relay: 0x19ea6810 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-06 01:17:39.974 ThaliTest[1351:2419279] client session: stateChange:1->2 1454717857743.776.U236Eg==
,2016-02-06 01:17:39.991 ThaliTest[1351:2419279] server session: not connected 1454717857743.776
,2016-02-06 01:17:40.031 ThaliTest[1351:2419279] client session: fireConnectCallback: 1454717857743.776.U236Eg==
,2016-02-06 01:17:40.033 ThaliTest[1351:2419279] jxcore: connect: success
,ok 106 Should be able to connect without error

,ok 107 Port should be within range

,2016-02-06 01:17:40.037 ThaliTest[1351:2418768] jxcore: connect 1454717857743.776.U236Eg==
,2016-02-06 01:17:40.038 ThaliTest[1351:2418768] client: already connect(ing/ed) to 1454717857743.776.U236Eg==
,2016-02-06 01:17:40.038 ThaliTest[1351:2418768] jxcore: connect: fail: Aleady connecting
,ok 108 Should fail on double connect

,2016-02-06 01:17:40.042 ThaliTest[1351:2418768] jxcore: disconnect
,2016-02-06 01:17:40.042 ThaliTest[1351:2418768] client session: disconnectFromPeer: 1454717857743.776.U236Eg==
,2016-02-06 01:17:40.043 ThaliTest[1351:2418768] client session: disconnect
,2016-02-06 01:17:40.044 ThaliTest[1351:2418768] client session: stateChange:2->0 1454717857743.776.U236Eg==
,2016-02-06 01:17:40.058 ThaliTest[1351:2418768] jxcore: disconnect: success
,ok 109 Should be able to disconnect without error

,setting stopBroadcasting callback and ending test.

,# teardown

,calling stopBroadcasting

,2016-02-06 01:17:40.107 ThaliTest[1351:2418768] jxcore: stopBroadcasting
2016-02-06 01:17:40.108 ThaliTest[1351:2418768] THEMultipeerSession stopping peer
2016-02-06 01:17:40.108 ThaliTest[1351:2418768] multipeer session: stop timer
2016-02-06 01:17:40.,109 ThaliTest[1351:2418768] server session: disconnect
2016-02-06 01:17:40.109 ThaliTest[1351:2418768] server session: stateChange:2->0 1454717857743.776
,2016-02-06 01:17:40.113 ThaliTest[1351:2418768] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# setup

,# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,2016-02-06 01:17:40.645 ThaliTest[1351:2418768] jxcore: startBroadcasting
,2016-02-06 01:17:40.649 ThaliTest[1351:2418768] server: starting 1454717860645.1351.d4urHQ==
2016-02-06 01:17:40.650 ThaliTest[1351:2418768] multipeer session: start timer: 0x199f6fe0
2016-02-06 01:17:40.650 ThaliTest[1351:2418768] THEMultipeerSession initialized peer 1454717860645.1351
2016-02-06 01:17:40.651 ThaliTest[1351:2418768] jxcore: startBroadcasting: success
ok 110 Should be able to call startBroadcasting without error

,2016-02-06 01:17:41.721 ThaliTest[1351:2418446] client: found peer: 1454717862499.776.4FjJVg==
2016-02-06 01:17:41.722 ThaliTest[1351:2418768] jxcore: connect 1454717862499.776.4FjJVg==
2016-02-06 01:17:41.723 ThaliTest[1351:2418768] client session: conn,ect
2016-02-06 01:17:41.723 ThaliTest[1351:2418768] client session: stateChange:0->1 1454717862499.776.4FjJVg==
,2016-02-06 01:17:41.862 ThaliTest[1351:2418446] multipeer session: reset timer
2016-02-06 01:17:41.863 ThaliTest[1351:2418446] multipeer session: stop timer
2016-02-06 01:17:41.863 ThaliTest[1351:2418446] multipeer session: start timer: 0x199f6fe0
2016-02-06 01:17:41.863 ThaliTest[1351:2418446] server session: connect
2016-02-06 01:17:41.864 ThaliTest[1351:2418446] server session: stateChange:0->1 1454717862499.776
,2016-02-06 01:17:41.873 ThaliTest[1351:2418446] server: accepting invitation 1454717862499.776
,2016-02-06 01:17:44.420 ThaliTest[1351:2419279] client session: connected
2016-02-06 01:17:44.420 ThaliTest[1351:2419279] client session: stateChange:1->2 1454717862499.776.4FjJVg==
2016-02-06 01:17:44.423 ThaliTest[1351:2419301] server session: connecte,d
2016-02-06 01:17:44.423 ThaliTest[1351:2419301] server session: stateChange:1->2 1454717862499.776
,2016-02-06 01:17:44.433 ThaliTest[1351:2419279] client session: fireConnectCallback: 1454717862499.776.4FjJVg==
,2016-02-06 01:17:44.436 ThaliTest[1351:2418446] server relay: socket disconnected
,2016-02-06 01:17:44.437 ThaliTest[1351:2419279] jxcore: connect: success
,2016-02-06 01:17:44.439 ThaliTest[1351:2418446] server relay: 0x19ea9ec0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,ok 111 Should be able to connect without error

,ok 112 Port should be within range

,2016-02-06 01:17:44.444 ThaliTest[1351:2418768] jxcore: disconnect
,2016-02-06 01:17:44.445 ThaliTest[1351:2418768] client session: disconnectFromPeer: 1454717862499.776.4FjJVg==
,2016-02-06 01:17:44.446 ThaliTest[1351:2418768] client session: disconnect
,2016-02-06 01:17:44.449 ThaliTest[1351:2418768] client session: stateChange:2->0 1454717862499.776.4FjJVg==
,2016-02-06 01:17:44.470 ThaliTest[1351:2418768] jxcore: disconnect: success
,ok 113 Should be able to disconnect without error

,2016-02-06 01:17:44.472 ThaliTest[1351:2418768] jxcore: disconnect
,2016-02-06 01:17:44.473 ThaliTest[1351:2418768] jxcore: disconnect: fail
,ok 114 Disconnect should fail 

,setting stopBroadcasting callback and ending test.

,# teardown

,2016-02-06 01:17:44.498 ThaliTest[1351:2419227] server session: not connected 1454717862499.776
,calling stopBroadcasting

,2016-02-06 01:17:44.747 ThaliTest[1351:2418768] jxcore: stopBroadcasting
,2016-02-06 01:17:44.748 ThaliTest[1351:2418768] THEMultipeerSession stopping peer
,2016-02-06 01:17:44.748 ThaliTest[1351:2418768] multipeer session: stop timer
,2016-02-06 01:17:44.750 ThaliTest[1351:2418768] server session: disconnect
2016-02-06 01:17:44.750 ThaliTest[1351:2418768] server session: stateChange:2->0 1454717862499.776
,2016-02-06 01:17:44.751 ThaliTest[1351:2418768] jxcore: stopBroadcasting: success
,stopBroadcasting returned undefined

,# setup

,# ThaliEmitter can connect and send data

,echo server started on port: 57719

,2016-02-06 01:17:46.014 ThaliTest[1351:2418768] jxcore: startBroadcasting
,2016-02-06 01:17:46.016 ThaliTest[1351:2418768] server: starting 1454717866014.1351.DXC6hQ==
2016-02-06 01:17:46.016 ThaliTest[1351:2418768] multipeer session: start timer: 0x198bceb0
2016-02-06 01:17:46.016 ThaliTest[1351:2418768] THEMultipeerSession initialized peer 1454717866014.1351
,2016-02-06 01:17:46.018 ThaliTest[1351:2418768] jxcore: startBroadcasting: success
ok 115 Should be able to call startBroadcasting without error

,2016-02-06 01:17:46.974 ThaliTest[1351:2418446] client: found peer: 1454717867797.776.TNwaBw==
2016-02-06 01:17:46.975 ThaliTest[1351:2418768] jxcore: connect 1454717867797.776.TNwaBw==
2016-02-06 01:17:46.976 ThaliTest[1351:2418768] client session: connect
2016-02-06 01:17:46.976 ThaliTest[1351:2418768] client session: stateChange:0->1 1454717867797.776.TNwaBw==
,2016-02-06 01:17:47.081 ThaliTest[1351:2418446] multipeer session: reset timer
2016-02-06 01:17:47.081 ThaliTest[1351:2418446] multipeer session: stop timer
2016-02-06 01:17:47.082 ThaliTest[1351:2418446] multipeer session: start timer: 0x198bceb0
2016-,02-06 01:17:47.082 ThaliTest[1351:2418446] server session: connect
2016-02-06 01:17:47.082 ThaliTest[1351:2418446] server session: stateChange:0->1 1454717867797.776
2016-02-06 01:17:47.090 ThaliTest[1351:2418446] server: accepting invitation 1454717867797.776
,2016-02-06 01:17:49.423 ThaliTest[1351:2419301] client session: connected
2016-02-06 01:17:49.423 ThaliTest[1351:2419301] client session: stateChange:1->2 1454717867797.776.TNwaBw==
,2016-02-06 01:17:49.427 ThaliTest[1351:2419301] client session: fireConnectCallback: 1454717867797.776.TNwaBw==
2016-02-06 01:17:49.428 ThaliTest[1351:2419301] jxcore: connect: success
,ok 116 Should be able to connect without error

,ok 117 Port should be within range

,2016-02-06 01:17:49.435 ThaliTest[1351:2418446] client: relay established
2016-02-06 01:17:49.435 ThaliTest[1351:2418446] client: new accepted socket: 0x18a07150
,data in 27648
,
,2016-02-06 01:17:49.602 ThaliTest[1351:2419279] server session: connected
,2016-02-06 01:17:49.603 ThaliTest[1351:2419279] server session: stateChange:1->2 1454717867797.776
,data in 49275

,2016-02-06 01:17:49.615 ThaliTest[1351:2418446] server relay: connected (to port: 57719)
,data in 51465

,data in 68985

,data in 74460

,data in 75555

,data in 77745
,
,data in 81030

,data in 88695

,data in 104978

,data in 127689

,data in 131072

,ok 118 the test messages should be equal

,2016-02-06 01:17:49.831 ThaliTest[1351:2418768] jxcore: disconnect
,2016-02-06 01:17:49.832 ThaliTest[1351:2418768] client session: disconnectFromPeer: 1454717867797.776.TNwaBw==
,2016-02-06 01:17:49.832 ThaliTest[1351:2418768] client session: disconnect
,2016-02-06 01:17:49.832 ThaliTest[1351:2418768] client session: stateChange:2->0 1454717867797.776.TNwaBw==
,2016-02-06 01:17:49.906 ThaliTest[1351:2418768] jxcore: disconnect: success
,ok 119 Should be able to disconnect without error

,setting stopBroadcasting callback and ending test.

,# teardown

,calling stopBroadcasting

,2016-02-06 01:17:49.975 ThaliTest[1351:2418768] jxcore: stopBroadcasting
2016-02-06 01:17:49.976 ThaliTest[1351:2418768] THEMultipeerSession stopping peer
2016-02-06 01:17:49.976 ThaliTest[1351:2418768] multipeer session: stop timer
2016-02-06 01:17:49.,976 ThaliTest[1351:2418768] server session: disconnect
2016-02-06 01:17:49.976 ThaliTest[1351:2418768] server session: stateChange:2->0 1454717867797.776
,2016-02-06 01:17:49.995 ThaliTest[1351:2418768] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# setup

,# ThaliEmitter handles socket disconnect correctly

,echo server started on port: 57725

,2016-02-06 01:17:50.061 ThaliTest[1351:2418768] jxcore: startBroadcasting
,2016-02-06 01:17:50.064 ThaliTest[1351:2418768] server: starting 1454717870061.1351.6cUd6g==
2016-02-06 01:17:50.064 ThaliTest[1351:2418768] multipeer session: start timer: 0x175e94b0
2016-02-06 01:17:50.065 ThaliTest[1351:2418768] THEMultipeerSession in,itialized peer 1454717870061.1351
2016-02-06 01:17:50.065 ThaliTest[1351:2418768] jxcore: startBroadcasting: success
ok 120 Should be able to call startBroadcasting without error

,2016-02-06 01:17:51.015 ThaliTest[1351:2418446] client: found peer: 1454717867797.776.TNwaBw==
,[{"peerIdentifier":"1454717867797.776.TNwaBw==","peerName":"(null)","peerAvailable":true}]

,2016-02-06 01:17:51.019 ThaliTest[1351:2418768] jxcore: connect 1454717867797.776.TNwaBw==
2016-02-06 01:17:51.020 ThaliTest[1351:2418768] client session: connect
2016-02-06 01:17:51.020 ThaliTest[1351:2418768] client session: stateChange:0->1 1454717867797.776.TNwaBw==
,2016-02-06 01:17:51.112 ThaliTest[1351:2418446] client: lost peer: 1454717867797.776.TNwaBw==
2016-02-06 01:17:51.112 ThaliTest[1351:2418446] client session: onPeerLost: 1454717867797.776.TNwaBw==
2016-02-06 01:17:51.112 ThaliTest[1351:2418446] client session: onLinkFailure: 1454717867797.776.TNwaBw==
,2016-02-06 01:17:51.113 ThaliTest[1351:2418446] client session: disconnect
2016-02-06 01:17:51.114 ThaliTest[1351:2418446] client session: stateChange:1->0 1454717867797.776.TNwaBw==
2016-02-06 01:17:51.115 ThaliTest[1351:2418446] client session: fireConnectCallback: 1454717867797.776.TNwaBw==
2016-02-06 01:17:51.115 ThaliTest[1351:2418446] jxcore: connect: fail: Peer disconnected
[{"peerIdentifier":"1454717867797.776.TNwaBw==","peerName":"(null)","peerAvailable":false}]

,2016-02-06 01:17:51.152 ThaliTest[1351:2418446] client: found peer: 1454717871923.776.9anJUQ==
[{"peerIdentifier":"1454717871923.776.9anJUQ==","peerName":"(null)","peerAvailable":true}]

2016-02-06 01:17:51.153 ThaliTest[1351:2418768] jxcore: connect 14,54717871923.776.9anJUQ==
2016-02-06 01:17:51.154 ThaliTest[1351:2418768] client session: connect
2016-02-06 01:17:51.154 ThaliTest[1351:2418768] client session: stateChange:0->1 1454717871923.776.9anJUQ==
,2016-02-06 01:17:51.268 ThaliTest[1351:2418446] multipeer session: reset timer
2016-02-06 01:17:51.268 ThaliTest[1351:2418446] multipeer session: stop timer
2016-02-06 01:17:51.269 ThaliTest[1351:2418446] multipeer session: start timer: 0x175e94b0
2016-,02-06 01:17:51.269 ThaliTest[1351:2418446] server session: connect
2016-02-06 01:17:51.269 ThaliTest[1351:2418446] server session: stateChange:0->1 1454717871923.776
,2016-02-06 01:17:51.279 ThaliTest[1351:2418446] server: accepting invitation 1454717871923.776
,2016-02-06 01:17:52.128 ThaliTest[1351:2418768] jxcore: connect 1454717867797.776.TNwaBw==
2016-02-06 01:17:52.129 ThaliTest[1351:2418768] client: connect: unreachable 1454717867797.776.TNwaBw==
2016-02-06 01:17:52.129 ThaliTest[1351:2418768] jxcore: connect: fail: Peer unreachable
,2016-02-06 01:17:53.647 ThaliTest[1351:2419225] client session: connected
2016-02-06 01:17:53.647 ThaliTest[1351:2419225] client session: stateChange:1->2 1454717871923.776.9anJUQ==
,2016-02-06 01:17:53.689 ThaliTest[1351:2419225] client session: fireConnectCallback: 1454717871923.776.9anJUQ==
2016-02-06 01:17:53.690 ThaliTest[1351:2419225] jxcore: connect: success
ok 121 Should be able to connect without error

,ok 122 Port should be within range

,ok 123 First connect should succeed

,2016-02-06 01:17:53.702 ThaliTest[1351:2419225] server session: connected
2016-02-06 01:17:53.703 ThaliTest[1351:2419225] server session: stateChange:1->2 1454717871923.776
,2016-02-06 01:17:53.715 ThaliTest[1351:2418446] server relay: connected (to port: 57725)
,2016-02-06 01:17:53.777 ThaliTest[1351:2418446] client: relay established
2016-02-06 01:17:53.778 ThaliTest[1351:2418446] client: new accepted socket: 0x189187b0
,2016-02-06 01:17:53.925 ThaliTest[1351:2419225] server session: not connected 1454717871923.776
,2016-02-06 01:17:53.969 ThaliTest[1351:2418446] multipeer session: reset timer
2016-02-06 01:17:53.969 ThaliTest[1351:2418446] multipeer session: stop timer
2016-02-06 01:17:53.970 ThaliTest[1351:2418446] multipeer session: start timer: 0x175e94b0
2016-,02-06 01:17:53.970 ThaliTest[1351:2418446] server: disconnecting to refresh session (1454717871923.776)
2016-02-06 01:17:53.970 ThaliTest[1351:2418446] server session: disconnect
2016-02-06 01:17:53.971 ThaliTest[1351:2418446] server session: stateChange:2->0 1454717871923.776
,2016-02-06 01:17:53.976 ThaliTest[1351:2418446] server session: connect
2016-02-06 01:17:53.977 ThaliTest[1351:2418446] server session: stateChange:0->1 1454717871923.776
,2016-02-06 01:17:53.991 ThaliTest[1351:2418446] server: accepting invitation 1454717871923.776
,ok 124 the test messages should be equal

,ok 125 First send should succeed

,2016-02-06 01:17:54.105 ThaliTest[1351:2418446] client: socket closed
,2016-02-06 01:17:54.106 ThaliTest[1351:2418446] client relay: socket disconnected
,2016-02-06 01:17:54.106 ThaliTest[1351:2418446] client relay: 0x189187b0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2016-02-06 01:17:54.107 ThaliTest[1351:2418446] client session: socket closed: 1454717871923.776.9anJUQ==
,2016-02-06 01:17:54.107 ThaliTest[1351:2418446] client session: onLinkFailure: 1454717871923.776.9anJUQ==
2016-02-06 01:17:54.107 ThaliTest[1351:2418446] client session: disconnect
,2016-02-06 01:17:54.107 ThaliTest[1351:2418446] client session: stateChange:2->0 1454717871923.776.9anJUQ==
,2016-02-06 01:17:54.121 ThaliTest[1351:2418446] client session: fireConnectionErrorEvent: 1454717871923.776.9anJUQ==
,2016-02-06 01:17:54.123 ThaliTest[1351:2418768] jxcore: connect 1454717871923.776.9anJUQ==
,2016-02-06 01:17:54.126 ThaliTest[1351:2418768] client session: connect
,2016-02-06 01:17:54.127 ThaliTest[1351:2418768] client session: stateChange:0->1 1454717871923.776.9anJUQ==
,2016-02-06 01:17:56.473 ThaliTest[1351:2419225] server session: connected
2016-02-06 01:17:56.473 ThaliTest[1351:2419225] server session: stateChange:1->2 1454717871923.776
,2016-02-06 01:17:56.500 ThaliTest[1351:2418446] server relay: connected (to port: 57725)
,2016-02-06 01:17:56.661 ThaliTest[1351:2419227] client session: connected
,2016-02-06 01:17:56.661 ThaliTest[1351:2419227] client session: stateChange:1->2 1454717871923.776.9anJUQ==
,2016-02-06 01:17:56.680 ThaliTest[1351:2419227] client session: fireConnectCallback: 1454717871923.776.9anJUQ==
,2016-02-06 01:17:56.680 ThaliTest[1351:2419227] jxcore: connect: success
,ok 126 Should be able to connect without error

ok 127 Port should be within range

,ok 128 Second connect should succeed

,2016-02-06 01:17:56.717 ThaliTest[1351:2418446] client: relay established
2016-02-06 01:17:56.717 ThaliTest[1351:2418446] client: new accepted socket: 0x18d638e0
,2016-02-06 01:17:56.733 ThaliTest[1351:2419279] server session: not connected 1454717871923.776
,ok 129 the test messages should be equal

,ok 130 Second send should succeed

,# teardown

,2016-02-06 01:17:56.823 ThaliTest[1351:2418446] client: socket closed
2016-02-06 01:17:56.823 ThaliTest[1351:2418446] client relay: socket disconnected
2016-02-06 01:17:56.824 ThaliTest[1351:2418446] client relay: 0x18d638e0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-02-06 01:17:56.824 ThaliTest[1351:2418446] client session: socket closed: 1454717871923.776.9anJUQ==
2016-02-06 0,1:17:56.824 ThaliTest[1351:2418446] client session: onLinkFailure: 1454717871923.776.9anJUQ==
2016-02-06 01:17:56.824 ThaliTest[1351:2418446] client session: disconnect
2016-02-06 01:17:56.825 ThaliTest[1351:2418446] client session: stateChange:2->0 1454717871923.776.9anJUQ==
,2016-02-06 01:17:56.838 ThaliTest[1351:2418446] client session: fireConnectionErrorEvent: 1454717871923.776.9anJUQ==
calling stopBroadcasting

2016-02-06 01:17:56.841 ThaliTest[1351:2418768] jxcore: stopBroadcasting
2016-02-06 01:17:56.842 ThaliTest[13,51:2418768] THEMultipeerSession stopping peer
2016-02-06 01:17:56.842 ThaliTest[1351:2418768] multipeer session: stop timer
2016-02-06 01:17:56.843 ThaliTest[1351:2418768] server session: disconnect
2016-02-06 01:17:56.843 ThaliTest[1351:2418768] server, session: stateChange:2->0 1454717871923.776
,2016-02-06 01:17:56.857 ThaliTest[1351:2418768] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# setup

,# ThaliReplicationManager can call start without error

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/F629E397-A9F7-4B66-90FF-3998B5B12F6E/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,ok 131 starting event should occur in right order

,2016-02-06 01:17:57.516 ThaliTest[1351:2418768] jxcore: startBroadcasting
,2016-02-06 01:17:57.517 ThaliTest[1351:2418768] server: starting zQYBSF-NNOFn1bJGYdeNfQ.0xC9wQ==
2016-02-06 01:17:57.518 ThaliTest[1351:2418768] multipeer session: start timer: 0x18aaf280
2016-02-06 01:17:57.518 ThaliTest[1351:2418768] THEMultipeerSession initialized peer zQYBSF-NNOFn1bJGYdeNfQ
,2016-02-06 01:17:57.519 ThaliTest[1351:2418768] jxcore: startBroadcasting: success
ok 132 started event should occur in right order

Now in TRM stop

State of this._isStarted: true

ok 133 stopping event should occur in right order

About to call ,stopBroadcasting

2016-02-06 01:17:57.521 ThaliTest[1351:2418768] jxcore: stopBroadcasting
,2016-02-06 01:17:57.521 ThaliTest[1351:2418768] THEMultipeerSession stopping peer
,2016-02-06 01:17:57.523 ThaliTest[1351:2418768] multipeer session: stop timer
,2016-02-06 01:17:57.523 ThaliTest[1351:2418768] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,ok 134 stopped event should occur in right order

mux server bridge listener closed

# teardown

,# setup

,# ThaliReplicationManager receives identity

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/F629E397-A9F7-4B66-90FF-3998B5B12F6E/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-02-06 01:17:57.794 ThaliTest[1351:2418768] jxcore: startBroadcasting
,2016-02-06 01:17:57.797 ThaliTest[1351:2418768] server: starting zQYBSF-NNOFn1bJGYdeNfQ.T4TQyg==
2016-02-06 01:17:57.797 ThaliTest[1351:2418768] multipeer session: start timer: 0x18e7ab70
2016-02-06 01:17:57.798 ThaliTest[1351:2418768] THEMultipeerSessio,n initialized peer zQYBSF-NNOFn1bJGYdeNfQ
2016-02-06 01:17:57.798 ThaliTest[1351:2418768] jxcore: startBroadcasting: success
ok 135 getDeviceIdentity should not return an error

ok 136 deviceName should not be null

Now in TRM stop

State of this._,isStarted: true

About to call stopBroadcasting

2016-02-06 01:17:57.800 ThaliTest[1351:2418768] jxcore: stopBroadcasting
2016-02-06 01:17:57.800 ThaliTest[1351:2418768] THEMultipeerSession stopping peer
2016-02-06 01:17:57.800 ThaliTest[1351:2418768,] multipeer session: stop timer
2016-02-06 01:17:57.801 ThaliTest[1351:2418768] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,mux server bridge listener closed

,# teardown

,# setup

,# ThaliReplicationManager replicates database

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/F629E397-A9F7-4B66-90FF-3998B5B12F6E/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-02-06 01:17:59.667 ThaliTest[1351:2418768] jxcore: startBroadcasting
,2016-02-06 01:17:59.668 ThaliTest[1351:2418768] server: starting zQYBSF-NNOFn1bJGYdeNfQ.EpYRuw==
2016-02-06 01:17:59.668 ThaliTest[1351:2418768] multipeer session: start timer: 0x19e787b0
2016-02-06 01:17:59.669 ThaliTest[1351:2418768] THEMultipeerSession initialized peer zQYBSF-NNOFn1bJGYdeNfQ
2016-02-06 01:17:59.669 ThaliTest[1351:2418768] jxcore: startBroadcasting: success
ok 137 getDeviceIdentity should not return an error

ok 138 deviceName should not be null

,2016-02-06 01:18:00.743 ThaliTest[1351:2418446] client: found peer: Zf-mP40mygTtOnEoUu9muA.OiPVlg==
,2016-02-06 01:18:04.373 ThaliTest[1351:2418446] multipeer session: reset timer
2016-02-06 01:18:04.373 ThaliTest[1351:2418446] multipeer session: stop timer
2016-02-06 01:18:04.374 ThaliTest[1351:2418446] multipeer session: start timer: 0x19e787b0
2016-,02-06 01:18:04.374 ThaliTest[1351:2418446] server session: connect
2016-02-06 01:18:04.374 ThaliTest[1351:2418446] server session: stateChange:0->1 Zf-mP40mygTtOnEoUu9muA
2016-02-06 01:18:04.378 ThaliTest[1351:2418768] jxcore: connect Zf-mP40mygTtOnEoUu9muA.OiPVlg==
2016-02-06 01:18:04.378 ThaliTest[1351:2418768] client session: connect
2016-02-06 01:18:04.378 ThaliTest[1351:2418768] client session: stateChange:0->1 Zf-mP40mygTtOnEoUu9muA.OiPVlg==
,2016-02-06 01:18:04.380 ThaliTest[1351:2418446] server: accepting invitation Zf-mP40mygTtOnEoUu9muA
,ok 139 Should be able to put doc without error

,ok 140 1st change of local doc should contain local id

,2016-02-06 01:18:09.979 ThaliTest[1351:2419227] server session: connected
,2016-02-06 01:18:09.979 ThaliTest[1351:2419227] server session: stateChange:1->2 Zf-mP40mygTtOnEoUu9muA
,2016-02-06 01:18:10.227 ThaliTest[1351:2419222] client session: connected
2016-02-06 01:18:10.228 ThaliTest[1351:2419222] client session: stateChange:1->2 Zf-mP40mygTtOnEoUu9muA.OiPVlg==
,2016-02-06 01:18:10.313 ThaliTest[1351:2418446] server relay: connected (to port: 57741)
server bridge: new client socket

,2016-02-06 01:18:10.363 ThaliTest[1351:2419227] client session: fireConnectCallback: Zf-mP40mygTtOnEoUu9muA.OiPVlg==
2016-02-06 01:18:10.363 ThaliTest[1351:2419227] jxcore: connect: success
,2016-02-06 01:18:10.369 ThaliTest[1351:2418446] client: relay established
2016-02-06 01:18:10.369 ThaliTest[1351:2418446] client: new accepted socket: 0x19abada0
,client bridge: new client socket

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

,client bridge: new client socket

,2016-02-06 01:18:31.871 ThaliTest[1351:2419225] client session: not connected Zf-mP40mygTtOnEoUu9muA.OiPVlg==
2016-02-06 01:18:31.872 ThaliTest[1351:2419225] client session: onLinkFailure: Zf-mP40mygTtOnEoUu9muA.OiPVlg==
2016-02-06 01:18:31.872 ThaliTest,[1351:2419225] client session: disconnect
2016-02-06 01:18:31.872 ThaliTest[1351:2419225] client session: stateChange:2->0 Zf-mP40mygTtOnEoUu9muA.OiPVlg==
2016-02-06 01:18:31.874 ThaliTest[1351:2419225] client session: fireConnectionErrorEvent: Zf-mP40mygTtOnEoUu9muA.OiPVlg==
,client bridge: socket closed
,
,2016-02-06 01:18:35.586 ThaliTest[1351:2418768] Error!: stream.push() after EOF
Stack:[{"_fileName":"/private/var/mobile/Containers/Bundle/Application/A3CE4745-193D-4F3B-9341-34FFEC3DB50D/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex/,node_modules/readable-stream/lib/_stream_readable.js","_functionName":"readableAddChunk","_lineNumber":"187","_columnNumber":"15","_msg":"    at readableAddChunk@/private/var/mobile/Containers/Bundle/Application/A3CE4745-193D-4F3B-9341-34FFEC3DB50D/ThaliTe,st.app/www/jxcore/node_modules/thali/node_modules/multiplex/node_modules/readable-stream/lib/_stream_readable.js:187:15"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/A3CE4745-193D-4F3B-9341-34FFEC3DB50D/ThaliTest.app/www/jxcore/node_mod,ules/thali/node_modules/multiplex/node_modules/readable-stream/lib/_stream_readable.js","_functionName":"Readable.prototype.push","_lineNumber":"165","_columnNumber":"10","_msg":"    at Readable.prototype.push@/private/var/mobile/Containers/Bundle/Applicat,ion/A3CE4745-193D-4F3B-9341-34FFEC3DB50D/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex/node_modules/readable-stream/lib/_stream_readable.js:165:10"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/A3CE4745-193D-4F3B-934,1-34FFEC3DB50D/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex/index.js","_functionName":"Multiplex.prototype._send","_lineNumber":"197","_columnNumber":"13","_msg":"    at Multiplex.prototype._send@/private/var/mobile/Containers/Bundle/,Application/A3CE4745-193D-4F3B-9341-34FFEC3DB50D/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex/index.js:197:13"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/A3CE4745-193D-4F3B-9341-34FFEC3DB50D/ThaliTest.app/www/jxc,ore/node_modules/thali/node_modules/multiplex/index.js","_functionName":"Channel.prototype._open","_lineNumber":"109","_columnNumber":"3","_msg":"    at Channel.prototype._open@/private/var/mobile/Containers/Bundle/Application/A3CE4745-193D-4F3B-9341-34FFE,C3DB50D/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex/index.js:109:3"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/A3CE4745-193D-4F3B-9341-34FFEC3DB50D/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/multip,lex/index.js","_functionName":"Channel.prototype.open","_lineNumber":"117","_columnNumber":"38","_msg":"    at Channel.prototype.open@/private/var/mobile/Containers/Bundle/Application/A3CE4745-193D-4F3B-9341-34FFEC3DB50D/ThaliTest.app/www/jxcore/node_modul,es/thali/node_modules/multiplex/index.js:117:38"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/A3CE4745-193D-4F3B-9341-34FFEC3DB50D/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex/index.js","_functionName":"Multiplex.p,rototype._addChannel","_lineNumber":"215","_columnNumber":"3","_msg":"    at Multiplex.prototype._addChannel@/private/var/mobile/Containers/Bundle/Application/A3CE4745-193D-4F3B-9341-34FFEC3DB50D/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/m,u,ltiplex/index.js:215:3"}]
Uncaught Exception: Error: stream.push() after EOF

,[ { _fileName: '/private/var/mobile/Containers/Bundle/Application/A3CE4745-193D-4F3B-9341-34FFEC3DB50D/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex/node_modules/readable-stream/lib/_stream_readable.js',
    _functionName: 'readableAd,dChunk',
    _lineNumber: '187',
    _columnNumber: '15',
    _msg: '    at readableAddChunk@/private/var/mobile/Containers/Bundle/Application/A3CE4745-193D-4F3B-9341-34FFEC3DB50D/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex/node_m,odules/readable-stream/lib/_stream_readable.js:187:15' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/A3CE4745-193D-4F3B-9341-34FFEC3DB50D/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex/node_modules/readable-strea,m/lib/_stream_readable.js',
    _functionName: 'Readable.prototype.push',
    _lineNumber: '165',
    _columnNumber: '10',
    _msg: '    at Readable.prototype.push@/private/var/mobile/Containers/Bundle/Application/A3CE4745-193D-4F3B-9341-34FFEC3DB50D/,ThaliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex/node_modules/readable-stream/lib/_stream_readable.js:165:10' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/A3CE4745-193D-4F3B-9341-34FFEC3DB50D/ThaliTest.app/www/jxc,ore/node_modules/thali/node_modules/multiplex/index.js',
    _functionName: 'Multiplex.prototype._send',
    _lineNumber: '197',
    _columnNumber: '13',
    _msg: '    at Multiplex.prototype._send@/private/var/mobile/Containers/Bundle/Application/A3CE,4745-193D-4F3B-9341-34FFEC3DB50D/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex/index.js:197:13' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/A3CE4745-193D-4F3B-9341-34FFEC3DB50D/ThaliTest.app/www/jxcore/node_mo,dules/thali/node_modules/multiplex/index.js',
    _functionName: 'Channel.prototype._open',
    _lineNumber: '109',
    _columnNumber: '3',
    _msg: '    at Channel.prototype._open@/private/var/mobile/Containers/Bundle/Application/A3CE4745-193D-4F3B-9,341-34FFEC3DB50D/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex/index.js:109:3' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/A3CE4745-193D-4F3B-9341-34FFEC3DB50D/ThaliTest.app/www/jxcore/node_modules/thali/node_,modules/multiplex/index.js',
    _functionName: 'Channel.prototype.open',
    _lineNumber: '117',
    _columnNumber: '38',
    _msg: '    at Channel.prototype.open@/private/var/mobile/Containers/Bundle/Application/A3CE4745-193D-4F3B-9341-34FFEC3DB50D/T,haliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex/index.js:117:38' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/A3CE4745-193D-4F3B-9341-34FFEC3DB50D/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex,/index.js',
    _functionName: 'Multiplex.prototype._addChannel',
    _lineNumber: '215',
    _columnNumber: '3',
    _msg: '    at Multiplex.prototype._addChannel@/private/var/mobile/Containers/Bundle/Application/A3CE4745-193D-4F3B-9341-34FFEC3DB50D/T,haliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex/index.js:215:3' },
  toString: [Function] ]

****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****

Error: stream.push() after EOF (/private/var/mobile/Containers/Bund
```
