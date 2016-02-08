#### Test 58380500962e22b_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/58380500962e22b/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/0A79B29D-50D2-49E9-AC7B-519DA89B13D9/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/0A79B29D-50D2-49E9-AC7B-519DA89B13D9/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/58380500962e22b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/58380500962e22b/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/ED6CFE00-5ED4-4019-945D-566D75FEEBBC/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52297"
,(lldb)     command script import "/tmp/0A79B29D-50D2-49E9-AC7B-519DA89B13D9/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-09 00:14:52.633 ThaliTest[1530:2861980] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/BABDD1FF-ECCB-4BC6-91EA-BD4A87B2BD1B/Library/Cookies/Cookies.binarycookies
,2016-02-09 00:14:53.054 ThaliTest[1530:2861980] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-09 00:14:53.056 ThaliTest[1530:2861980] Multi-tasking -> Device: YES, App: YES
,2016-02-09 00:14:53.067 ThaliTest[1530:2861980] Unlimited access to network resources
,2016-02-09 00:14:53.082 ThaliTest[1530:2861980] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-09 00:15:02.071 ThaliTest[1530:2861980] Resetting plugins due to page load.
,2016-02-09 00:15:04.939 ThaliTest[1530:2861980] Finished load of: file:///var/mobile/Containers/Bundle/Application/ED6CFE00-5ED4-4019-945D-566D75FEEBBC/ThaliTest.app/www/index.html
,2016-02-09 00:15:05.188 ThaliTest[1530:2861980] JXcore Cordova plugin initializing
,2016-02-09 00:15:05.189 ThaliTest[1530:2862353] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/ED6CFE00-5ED4-4019-945D-566D75FEEBBC/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/ED6CFE00-5ED4-4019-945D-566D75FEEBBC/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/ED6CFE00-5ED4-4019-945D-566D75FEEBBC/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/ED6CFE00-5ED4-4019-945D-566D75FEEBBC/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/ED6CFE00-5ED4-4019-945D-566D75FEEBBC/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/ED6CFE00-5ED4-4019-945D-566D75FEEBBC/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/ED6CFE00-5ED4-4019-945D-566D75FEEBBC/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/ED6CFE00-5ED4-4019-945D-566D75FEEBBC/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/ED6CFE00-5ED4-4019-945D-566D75FEEBBC/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,TAP version 13

,# setup

,# #generatePreambleAndBeacons empty keys to notify

,ok 1 should be equal
,
,# teardown

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

,# setup

,# #parseBeacons invalid expiration in beaconStreamWithPreAmble

,ok 7 should throw

# teardown

,# setup

,# #parseBeacons no beacons returns null

,ok 8 should be equal

,# teardown

,# setup

,# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

,ok 9 should throw

# teardown

,# setup

,# #parseBeacons addressBookCallback fails decrypt

,ok 10 should be equal

# teardown

,# setup

,# #parseBeacons addressBookCallback returns no matches

,ok 11 should be equal

,ok 12 should be equal

,# teardown

,# setup

,# #parseBeacons addressBookCallback returns public key

,ok 13 should be equal

ok 14 (unnamed assert)

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

ok 31 should be equal

,ok 32 should not throw

# teardown

,# setup

,# successfully read a previous pkcs12 file and return hash value

,ok 33 (unnamed assert)

,ok 34 (unnamed assert)

ok 35 should not throw

,ok 36 should be equal

,ok 37 should be equal

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

ok 51 should be equal

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

,ok 64 should be equal

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

,2016-02-09 00:19:24.119 ThaliTest[1530:2862353] jxcore: startBroadcasting
,2016-02-09 00:19:24.134 ThaliTest[1530:2862353] server: starting 1454973564119.1530.9Ug/xg==
,2016-02-09 00:19:24.136 ThaliTest[1530:2862353] multipeer session: start timer: 0x18c3a350
,2016-02-09 00:19:24.137 ThaliTest[1530:2862353] THEMultipeerSession initialized peer 1454973564119.1530
2016-02-09 00:19:24.138 ThaliTest[1530:2862353] jxcore: startBroadcasting: success
,ok 69 Should be able to call startBroadcasting without error

,2016-02-09 00:19:24.141 ThaliTest[1530:2862353] jxcore: stopBroadcasting
2016-02-09 00:19:24.142 ThaliTest[1530:2862353] THEMultipeerSession stopping peer
2016-02-09 00:19:24.142 ThaliTest[1530:2862353] multipeer session: stop timer
2016-02-09 00:19:24.,143 ThaliTest[1530:2862353] jxcore: stopBroadcasting: success
ok 70 Should be able to call stopBroadcasting without error

,2016-02-09 00:19:24.145 ThaliTest[1530:2862353] jxcore: startBroadcasting
,2016-02-09 00:19:24.151 ThaliTest[1530:2862353] server: starting 1454973564144.1530.n99K9A==
,2016-02-09 00:19:24.159 ThaliTest[1530:2862353] multipeer session: start timer: 0x18c36a30
2016-02-09 00:19:24.159 ThaliTest[1530:2862353] THEMultipeerSession initialized peer 1454973564144.1530
2016-02-09 00:19:24.160 ThaliTest[1530:2862353] jxcore: sta,rtBroadcasting: success
ok 71 Should be able to call startBroadcasting without error

2016-02-09 00:19:24.162 ThaliTest[1530:2862353] jxcore: stopBroadcasting
2016-02-09 00:19:24.162 ThaliTest[1530:2862353] THEMultipeerSession stopping peer
2016-02-09, 00:19:24.162 ThaliTest[1530:2862353] multipeer session: stop timer
2016-02-09 00:19:24.163 ThaliTest[1530:2862353] jxcore: stopBroadcasting: success
ok 72 Should be able to call stopBroadcasting without error

2016-02-09 00:19:24.165 ThaliTest[1530:28,62353] jxcore: startBroadcasting
,2016-02-09 00:19:24.175 ThaliTest[1530:2862353] server: starting 1454973564165.1530.d8DbUw==
2016-02-09 00:19:24.175 ThaliTest[1530:2862353] multipeer session: start timer: 0x18c3dea0
2016-02-09 00:19:24.176 ThaliTest[1530:2862353] THEMultipeerSession initialized peer 1454973564165.1530
2016-02-09 00:19:24.176 ThaliTest[1530:2862353] jxcore: startBroadcasting: success
ok 73 Should be able to call startBroadcasting without error

2016-02-09 00:19:24.178 ThaliTest[1530:2862353] jxcore: stopBroadcasting,
2016-02-09 00:19:24.179 ThaliTest[1530:2862353] THEMultipeerSession stopping peer
2016-02-09 00:19:24.179 ThaliTest[1530:2862353] multipeer session: stop timer
2016-02-09 00:19:24.179 ThaliTest[1530:2862353] jxcore: stopBroadcasting: success
ok 74 Shou,ld be able to call stopBroadcasting without error

2016-02-09 00:19:24.181 ThaliTest[1530:2862353] jxcore: startBroadcasting
,2016-02-09 00:19:24.187 ThaliTest[1530:2862353] server: starting 1454973564180.1530.laK8mw==
2016-02-09 00:19:24.188 ThaliTest[1530:2862353] multipeer session: start timer: 0x18e9d650
2016-02-09 00:19:24.188 ThaliTest[1530:2862353] THEMultipeerSession in,itialized peer 1454973564180.1530
2016-02-09 00:19:24.189 ThaliTest[1530:2862353] jxcore: startBroadcasting: success
ok 75 Should be able to call startBroadcasting without error

,2016-02-09 00:19:24.191 ThaliTest[1530:2862353] jxcore: stopBroadcasting
2016-02-09 00:19:24.197 ThaliTest[1530:2862353] THEMultipeerSession stopping peer
2016-02-09 00:19:24.199 ThaliTest[1530:2862353] multipeer session: stop timer
,2016-02-09 00:19:24.200 ThaliTest[1530:2862353] jxcore: stopBroadcasting: success
ok 76 Should be able to call stopBroadcasting without error

2016-02-09 00:19:24.207 ThaliTest[1530:2862353] jxcore: startBroadcasting
,2016-02-09 00:19:24.212 ThaliTest[1530:2862353] server: starting 1454973564206.1530./sVtDA==
2016-02-09 00:19:24.213 ThaliTest[1530:2862353] multipeer session: start timer: 0x18c3bbd0
2016-02-09 00:19:24.213 ThaliTest[1530:2862353] THEMultipeerSession in,itialized peer 1454973564206.1530
2016-02-09 00:19:24.213 ThaliTest[1530:2862353] jxcore: startBroadcasting: success
ok 77 Should be able to call startBroadcasting without error

2016-02-09 00:19:24.215 ThaliTest[1530:2862353] jxcore: stopBroadcasting,
2016-02-09 00:19:24.216 ThaliTest[1530:2862353] THEMultipeerSession stopping peer
2016-02-09 00:19:24.216 ThaliTest[1530:2862353] multipeer session: stop timer
2016-02-09 00:19:24.216 ThaliTest[1530:2862353] jxcore: stopBroadcasting: success
ok 78 Shou,ld be able to call stopBroadcasting without error

2016-02-09 00:19:24.217 ThaliTest[1530:2862353] jxcore: startBroadcasting
,2016-02-09 00:19:24.225 ThaliTest[1530:2862353] server: starting 1454973564217.1530.xI3Haw==
2016-02-09 00:19:24.228 ThaliTest[1530:2862353] multipeer session: start timer: 0x18c3c9c0
2016-02-09 00:19:24.228 ThaliTest[1530:2862353] THEMultipeerSession in,itialized peer 1454973564217.1530
2016-02-09 00:19:24.228 ThaliTest[1530:2862353] jxcore: startBroadcasting: success
ok 79 Should be able to call startBroadcasting without error

2016-02-09 00:19:24.230 ThaliTest[1530:2862353] jxcore: stopBroadcasting,
2016-02-09 00:19:24.230 ThaliTest[1530:2862353] THEMultipeerSession stopping peer
2016-02-09 00:19:24.230 ThaliTest[1530:2862353] multipeer session: stop timer
2016-02-09 00:19:24.230 ThaliTest[1530:2862353] jxcore: stopBroadcasting: success
,ok 80 Should be able to call stopBroadcasting without error

,2016-02-09 00:19:24.232 ThaliTest[1530:2862353] jxcore: startBroadcasting
,2016-02-09 00:19:24.236 ThaliTest[1530:2862353] server: starting 1454973564231.1530.XgkJdA==
2016-02-09 00:19:24.237 ThaliTest[1530:2862353] multipeer session: start timer: 0x18c6a000
2016-02-09 00:19:24.238 ThaliTest[1530:2862353] THEMultipeerSession in,itialized peer 1454973564231.1530
2016-02-09 00:19:24.238 ThaliTest[1530:2862353] jxcore: startBroadcasting: success
ok 81 Should be able to call startBroadcasting without error

,2016-02-09 00:19:24.239 ThaliTest[1530:2862353] jxcore: stopBroadcasting
,2016-02-09 00:19:24.243 ThaliTest[1530:2862353] THEMultipeerSession stopping peer
,2016-02-09 00:19:24.245 ThaliTest[1530:2862353] multipeer session: stop timer
,2016-02-09 00:19:24.249 ThaliTest[1530:2862353] jxcore: stopBroadcasting: success
,ok 82 Should be able to call stopBroadcasting without error

,2016-02-09 00:19:24.261 ThaliTest[1530:2862353] jxcore: startBroadcasting
,2016-02-09 00:19:24.265 ThaliTest[1530:2862353] server: starting 1454973564260.1530.Qg46hw==
,2016-02-09 00:19:24.266 ThaliTest[1530:2862353] multipeer session: start timer: 0x18e9aaa0
,2016-02-09 00:19:24.268 ThaliTest[1530:2862353] THEMultipeerSession initialized peer 1454973564260.1530
,2016-02-09 00:19:24.272 ThaliTest[1530:2862353] jxcore: startBroadcasting: success
,ok 83 Should be able to call startBroadcasting without error

,2016-02-09 00:19:24.275 ThaliTest[1530:2862353] jxcore: stopBroadcasting
,2016-02-09 00:19:24.276 ThaliTest[1530:2862353] THEMultipeerSession stopping peer
,2016-02-09 00:19:24.276 ThaliTest[1530:2862353] multipeer session: stop timer
,2016-02-09 00:19:24.278 ThaliTest[1530:2862353] jxcore: stopBroadcasting: success
,ok 84 Should be able to call stopBroadcasting without error

,2016-02-09 00:19:24.283 ThaliTest[1530:2862353] jxcore: startBroadcasting
,2016-02-09 00:19:24.285 ThaliTest[1530:2862353] server: starting 1454973564282.1530.e/R11g==
,2016-02-09 00:19:24.286 ThaliTest[1530:2862353] multipeer session: start timer: 0x18c3c770
,2016-02-09 00:19:24.292 ThaliTest[1530:2862353] THEMultipeerSession initialized peer 1454973564282.1530
,2016-02-09 00:19:24.293 ThaliTest[1530:2862353] jxcore: startBroadcasting: success
,ok 85 Should be able to call startBroadcasting without error

,2016-02-09 00:19:24.296 ThaliTest[1530:2862353] jxcore: stopBroadcasting
,2016-02-09 00:19:24.297 ThaliTest[1530:2862353] THEMultipeerSession stopping peer
,2016-02-09 00:19:24.298 ThaliTest[1530:2862353] multipeer session: stop timer
,2016-02-09 00:19:24.299 ThaliTest[1530:2862353] jxcore: stopBroadcasting: success
,ok 86 Should be able to call stopBroadcasting without error

,2016-02-09 00:19:24.305 ThaliTest[1530:2862353] jxcore: startBroadcasting
,2016-02-09 00:19:24.308 ThaliTest[1530:2862353] server: starting 1454973564304.1530.TvXsdg==
,2016-02-09 00:19:24.309 ThaliTest[1530:2862353] multipeer session: start timer: 0x18e9ee50
,2016-02-09 00:19:24.310 ThaliTest[1530:2862353] THEMultipeerSession initialized peer 1454973564304.1530
,2016-02-09 00:19:24.315 ThaliTest[1530:2862353] jxcore: startBroadcasting: success
,ok 87 Should be able to call startBroadcasting without error

,2016-02-09 00:19:24.318 ThaliTest[1530:2862353] jxcore: stopBroadcasting
,2016-02-09 00:19:24.318 ThaliTest[1530:2862353] THEMultipeerSession stopping peer
,2016-02-09 00:19:24.319 ThaliTest[1530:2862353] multipeer session: stop timer
,2016-02-09 00:19:24.320 ThaliTest[1530:2862353] jxcore: stopBroadcasting: success
,ok 88 Should be able to call stopBroadcasting without error

,# teardown

,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,2016-02-09 00:19:24.958 ThaliTest[1530:2862353] jxcore: startBroadcasting
,2016-02-09 00:19:24.962 ThaliTest[1530:2862353] server: starting 1454973564958.1530.zVyLOg==
2016-02-09 00:19:24.962 ThaliTest[1530:2862353] multipeer session: start timer: 0x18c63e40
2016-02-09 00:19:24.963 ThaliTest[1530:2862353] THEMultipeerSession in,itialized peer 1454973564958.1530
2016-02-09 00:19:24.963 ThaliTest[1530:2862353] jxcore: startBroadcasting: success
,ok 89 Should be able to call startBroadcasting without error

,2016-02-09 00:19:24.966 ThaliTest[1530:2862353] jxcore: startBroadcasting
,2016-02-09 00:19:24.967 ThaliTest[1530:2862353] jxcore: startBroadcasting: failure
,ok 90 Cannot call startBroadcasting twice

2016-02-09 00:19:24.971 ThaliTest[1530:2862353] jxcore: stopBroadcasting
2016-02-09 00:19:24.972 ThaliTest[1530:2862353] THEMultipeerSession stopping peer
2016-02-09 00:19:24.972 ThaliTest[1530:2862353] multip,eer session: stop timer
2016-02-09 00:19:24.972 ThaliTest[1530:2862353] jxcore: stopBroadcasting: success
ok 91 Should be able to call stopBroadcasting without error

,# teardown

,# setup

,# ThaliEmitter throws on connection to bad peer

,2016-02-09 00:19:25.594 ThaliTest[1530:2862353] jxcore: startBroadcasting
,2016-02-09 00:19:25.598 ThaliTest[1530:2862353] server: starting 1454973565594.1530.AM/qQQ==
2016-02-09 00:19:25.598 ThaliTest[1530:2862353] multipeer session: start timer: 0x18ea4170
2016-02-09 00:19:25.599 ThaliTest[1530:2862353] THEMultipeerSession in,itialized peer 1454973565594.1530
2016-02-09 00:19:25.599 ThaliTest[1530:2862353] jxcore: startBroadcasting: success
ok 92 Should be able to call startBroadcasting without error

2016-02-09 00:19:25.601 ThaliTest[1530:2862353] jxcore: connect foobar
2,016-02-09 00:19:25.602 ThaliTest[1530:2862353] client: unknown peer foobar
2016-02-09 00:19:25.602 ThaliTest[1530:2862353] jxcore: connect: fail: Unknown peer
ok 93 Should not connect to a bad peer

,2016-02-09 00:19:25.606 ThaliTest[1530:2862353] jxcore: stopBroadcasting
2016-02-09 00:19:25.606 ThaliTest[1530:2862353] THEMultipeerSession stopping peer
2016-02-09 00:19:25.607 ThaliTest[1530:2862353] multipeer session: stop timer
,2016-02-09 00:19:25.608 ThaliTest[1530:2862353] jxcore: stopBroadcasting: success
,ok 94 Should be able to call stopBroadcasting without error

,# teardown

,# setup

,# ThaliEmitter throws on disconnect to bad peer

,2016-02-09 00:19:26.542 ThaliTest[1530:2862353] jxcore: startBroadcasting
,2016-02-09 00:19:26.546 ThaliTest[1530:2862353] server: starting 1454973566542.1530.F3L20Q==
2016-02-09 00:19:26.547 ThaliTest[1530:2862353] multipeer session: start timer: 0x18c67800
2016-02-09 00:19:26.547 ThaliTest[1530:2862353] THEMultipeerSession initialized peer 1454973566542.1530
2016-02-09 00:19:26.548 ThaliTest[1530:2862353] jxcore: startBroadcasting: success
ok 95 Should be able to call startBroadcasting without error
,
,2016-02-09 00:19:26.551 ThaliTest[1530:2862353] jxcore: disconnect
2016-02-09 00:19:26.552 ThaliTest[1530:2862353] jxcore: disconnect: fail
ok 96 Disconnect should fail to a non-existant peer 

2016-02-09 00:19:26.556 ThaliTest[1530:2862353] jxcore: st,opBroadcasting
2016-02-09 00:19:26.556 ThaliTest[1530:2862353] THEMultipeerSession stopping peer
2016-02-09 00:19:26.556 ThaliTest[1530:2862353] multipeer session: stop timer
2016-02-09 00:19:26.557 ThaliTest[1530:2862353] jxcore: stopBroadcasting: succ,ess
ok 97 Should be able to call stopBroadcasting without error

,# teardown

,# setup

,# ThaliEmitter can discover and connect to peers

,2016-02-09 00:19:26.948 ThaliTest[1530:2862353] jxcore: startBroadcasting
,2016-02-09 00:19:26.951 ThaliTest[1530:2862353] server: starting 1454973566947.1530.QPwF6Q==
2016-02-09 00:19:26.952 ThaliTest[1530:2862353] multipeer session: start timer: 0x18c62f80
2016-02-09 00:19:26.953 ThaliTest[1530:2862353] THEMultipeerSession in,itialized peer 1454973566947.1530
2016-02-09 00:19:26.953 ThaliTest[1530:2862353] jxcore: startBroadcasting: success
ok 98 Should be able to call startBroadcasting without error

,2016-02-09 00:19:27.917 ThaliTest[1530:2861980] client: found peer: 1454973567388.974.cLlcMg==
,2016-02-09 00:19:27.920 ThaliTest[1530:2862353] jxcore: connect 1454973567388.974.cLlcMg==
2016-02-09 00:19:27.921 ThaliTest[1530:2862353] client session: connect
2016-02-09 00:19:27.921 ThaliTest[1530:2862353] client session: stateChange:0->1 1454973567388.974.cLlcMg==
,2016-02-09 00:19:28.467 ThaliTest[1530:2861980] multipeer session: reset timer
2016-02-09 00:19:28.467 ThaliTest[1530:2861980] multipeer session: stop timer
2016-02-09 00:19:28.468 ThaliTest[1530:2861980] multipeer session: start timer: 0x18c62f80
2016-,02-09 00:19:28.468 ThaliTest[1530:2861980] server session: connect
2016-02-09 00:19:28.468 ThaliTest[1530:2861980] server session: stateChange:0->1 1454973567388.974
,2016-02-09 00:19:28.477 ThaliTest[1530:2861980] server: accepting invitation 1454973567388.974
,2016-02-09 00:19:30.954 ThaliTest[1530:2862817] server session: connected
2016-02-09 00:19:30.955 ThaliTest[1530:2862817] server session: stateChange:1->2 1454973567388.974
,2016-02-09 00:19:31.046 ThaliTest[1530:2862826] server session: not connected 1454973567388.974
,2016-02-09 00:19:31.048 ThaliTest[1530:2861980] server relay: socket disconnected
,2016-02-09 00:19:31.048 ThaliTest[1530:2861980] server relay: 0x165a34f0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-09 00:19:31.081 ThaliTest[1530:2862817] client session: connected
,2016-02-09 00:19:31.081 ThaliTest[1530:2862817] client session: stateChange:1->2 1454973567388.974.cLlcMg==
,2016-02-09 00:19:31.141 ThaliTest[1530:2862826] client session: fireConnectCallback: 1454973567388.974.cLlcMg==
,2016-02-09 00:19:31.141 ThaliTest[1530:2862826] jxcore: connect: success
,ok 99 Should be able to connect without error

,ok 100 Port should be within range

,2016-02-09 00:19:31.146 ThaliTest[1530:2862353] jxcore: disconnect
,2016-02-09 00:19:31.147 ThaliTest[1530:2862353] client session: disconnectFromPeer: 1454973567388.974.cLlcMg==
,2016-02-09 00:19:31.148 ThaliTest[1530:2862353] client session: disconnect
,2016-02-09 00:19:31.149 ThaliTest[1530:2862353] client session: stateChange:2->0 1454973567388.974.cLlcMg==
,2016-02-09 00:19:31.159 ThaliTest[1530:2862353] jxcore: disconnect: success
,ok 101 Should be able to disconnect without error

,setting stopBroadcasting callback and ending test.

,# teardown

,calling stopBroadcasting

,2016-02-09 00:19:31.349 ThaliTest[1530:2862353] jxcore: stopBroadcasting
2016-02-09 00:19:31.349 ThaliTest[1530:2862353] THEMultipeerSession stopping peer
2016-02-09 00:19:31.350 ThaliTest[1530:2862353] multipeer session: stop timer
,2016-02-09 00:19:31.350 ThaliTest[1530:2862353] server session: disconnect
,2016-02-09 00:19:31.351 ThaliTest[1530:2862353] server session: stateChange:2->0 1454973567388.974
,2016-02-09 00:19:31.352 ThaliTest[1530:2862353] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# setup

,# ThaliEmitter can discover and connect to peers and then fail on double connect

,2016-02-09 00:19:32.409 ThaliTest[1530:2862353] jxcore: startBroadcasting
,2016-02-09 00:19:32.413 ThaliTest[1530:2862353] server: starting 1454973572409.1530.8OL1AA==
2016-02-09 00:19:32.414 ThaliTest[1530:2862353] multipeer session: start timer: 0x165b5d00
2016-02-09 00:19:32.414 ThaliTest[1530:2862353] THEMultipeerSession in,itialized peer 1454973572409.1530
2016-02-09 00:19:32.415 ThaliTest[1530:2862353] jxcore: startBroadcasting: success
ok 102 Should be able to call startBroadcasting without error

,2016-02-09 00:19:33.655 ThaliTest[1530:2861980] multipeer session: reset timer
2016-02-09 00:19:33.655 ThaliTest[1530:2861980] multipeer session: stop timer
2016-02-09 00:19:33.655 ThaliTest[1530:2861980] multipeer session: start timer: 0x165b5d00
2016-,02-09 00:19:33.656 ThaliTest[1530:2861980] server session: connect
2016-02-09 00:19:33.656 ThaliTest[1530:2861980] server session: stateChange:0->1 1454973573917.974
,2016-02-09 00:19:33.665 ThaliTest[1530:2861980] server: accepting invitation 1454973573917.974
,2016-02-09 00:19:34.410 ThaliTest[1530:2861980] client: found peer: 1454973573917.974.PJWINg==
2016-02-09 00:19:34.412 ThaliTest[1530:2862353] jxcore: connect 1454973573917.974.PJWINg==
,2016-02-09 00:19:34.413 ThaliTest[1530:2862353] client session: connect
2016-02-09 00:19:34.413 ThaliTest[1530:2862353] client session: stateChange:0->1 1454973573917.974.PJWINg==
,2016-02-09 00:19:36.194 ThaliTest[1530:2862821] server session: connected
2016-02-09 00:19:36.195 ThaliTest[1530:2862821] server session: stateChange:1->2 1454973573917.974
,2016-02-09 00:19:36.205 ThaliTest[1530:2861980] server relay: socket disconnected
2016-02-09 00:19:36.206 ThaliTest[1530:2861980] server relay: 0x18c8e7e0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-09 00:19:36.261 ThaliTest[1530:2862817] server session: not connected 1454973573917.974
,2016-02-09 00:19:37.378 ThaliTest[1530:2862819] client session: connected
2016-02-09 00:19:37.379 ThaliTest[1530:2862819] client session: stateChange:1->2 1454973573917.974.PJWINg==
2016-02-09 00:19:37.382 ThaliTest[1530:2862819] client session: fireConnectCallback: 1454973573917.974.PJWINg==
,2016-02-09 00:19:37.382 ThaliTest[1530:2862819] jxcore: connect: success
,ok 103 Should be able to connect without error

ok 104 Port should be within range

2016-02-09 00:19:37.387 ThaliTest[1530:2862353] jxcore: connect 1454973573917.974.PJWINg==
2016-02-09 00:19:37.388 ThaliTest[1530:2862353] client: already connect(ing/,ed) to 1454973573917.974.PJWINg==
2016-02-09 00:19:37.388 ThaliTest[1530:2862353] jxcore: connect: fail: Aleady connecting
,ok 105 Should fail on double connect
,
,2016-02-09 00:19:37.393 ThaliTest[1530:2862353] jxcore: disconnect
2016-02-09 00:19:37.393 ThaliTest[1530:2862353] client session: disconnectFromPeer: 1454973573917.974.PJWINg==
2016-02-09 00:19:37.393 ThaliTest[1530:2862353] client session: disconnect
2016-02-09 00:19:37.394 ThaliTest[1530:2862353] client session: stateChange:2->0 1454973573917.974.PJWINg==
,2016-02-09 00:19:37.470 ThaliTest[1530:2862353] jxcore: disconnect: success
ok 106 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# teardown

,calling stopBroadcasting

,2016-02-09 00:19:37.645 ThaliTest[1530:2862353] jxcore: stopBroadcasting
2016-02-09 00:19:37.645 ThaliTest[1530:2862353] THEMultipeerSession stopping peer
2016-02-09 00:19:37.646 ThaliTest[1530:2862353] multipeer session: stop timer
2016-02-09 00:19:37.,646 ThaliTest[1530:2862353] server session: disconnect
2016-02-09 00:19:37.646 ThaliTest[1530:2862353] server session: stateChange:2->0 1454973573917.974
2016-02-09 00:19:37.649 ThaliTest[1530:2862353] jxcore: stopBroadcasting: success
stopBroadcasting ,returned undefined

,# setup

,# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,2016-02-09 00:19:38.169 ThaliTest[1530:2862353] jxcore: startBroadcasting
,2016-02-09 00:19:38.172 ThaliTest[1530:2862353] server: starting 1454973578169.1530.fLQN+w==
2016-02-09 00:19:38.173 ThaliTest[1530:2862353] multipeer session: start timer: 0x18c60490
2016-02-09 00:19:38.174 ThaliTest[1530:2862353] THEMultipeerSession in,itialized peer 1454973578169.1530
2016-02-09 00:19:38.174 ThaliTest[1530:2862353] jxcore: startBroadcasting: success
ok 107 Should be able to call startBroadcasting without error

,2016-02-09 00:19:38.875 ThaliTest[1530:2861980] client: found peer: 1454973573917.974.PJWINg==
2016-02-09 00:19:38.876 ThaliTest[1530:2862353] jxcore: connect 1454973573917.974.PJWINg==
2016-02-09 00:19:38.877 ThaliTest[1530:2862353] client session: conn,ect
2016-02-09 00:19:38.877 ThaliTest[1530:2862353] client session: stateChange:0->1 1454973573917.974.PJWINg==
,2016-02-09 00:19:39.364 ThaliTest[1530:2861980] multipeer session: reset timer
2016-02-09 00:19:39.364 ThaliTest[1530:2861980] multipeer session: stop timer
2016-02-09 00:19:39.365 ThaliTest[1530:2861980] multipeer session: start timer: 0x18c60490
2016-02-09 00:19:39.365 ThaliTest[1530:2861980] server session: connect
2016-02-09 00:19:39.365 ThaliTest[1530:2861980] server session: stateChange:0->1 1454973578852.974
,2016-02-09 00:19:39.375 ThaliTest[1530:2861980] server: accepting invitation 1454973578852.974
,2016-02-09 00:19:39.393 ThaliTest[1530:2861980] client: found peer: 1454973578852.974.wGAwbw==
2016-02-09 00:19:39.397 ThaliTest[1530:2862353] jxcore: connect 1454973578852.974.wGAwbw==
2016-02-09 00:19:39.399 ThaliTest[1530:2862353] client session: connect
2016-02-09 00:19:39.399 ThaliTest[1530:2862353] client session: stateChange:0->1 1454973578852.974.wGAwbw==
,2016-02-09 00:19:41.811 ThaliTest[1530:2862826] server session: connected
2016-02-09 00:19:41.812 ThaliTest[1530:2862826] server session: stateChange:1->2 1454973578852.974
,2016-02-09 00:19:41.829 ThaliTest[1530:2861980] server relay: socket disconnected
2016-02-09 00:19:41.830 ThaliTest[1530:2861980] server relay: 0x18eb4610 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLoc,alizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-09 00:19:41.871 ThaliTest[1530:2862825] server session: not connected 1454973578852.974
,2016-02-09 00:19:41.962 ThaliTest[1530:2862825] client session: connected
2016-02-09 00:19:41.962 ThaliTest[1530:2862825] client session: stateChange:1->2 1454973578852.974.wGAwbw==
,2016-02-09 00:19:41.980 ThaliTest[1530:2862821] client session: fireConnectCallback: 1454973578852.974.wGAwbw==
2016-02-09 00:19:41.980 ThaliTest[1530:2862821] jxcore: connect: success
ok 108 Should be able to connect without error

,ok 109 Port should be within range

,2016-02-09 00:19:41.985 ThaliTest[1530:2862353] jxcore: disconnect
2016-02-09 00:19:41.986 ThaliTest[1530:2862353] client session: disconnectFromPeer: 1454973578852.974.wGAwbw==
2016-02-09 00:19:41.986 ThaliTest[1530:2862353] client session: disconnect
,2016-02-09 00:19:41.986 ThaliTest[1530:2862353] client session: stateChange:2->0 1454973578852.974.wGAwbw==
,2016-02-09 00:19:41.996 ThaliTest[1530:2862353] jxcore: disconnect: success
ok 110 Should be able to disconnect without error

,2016-02-09 00:19:41.998 ThaliTest[1530:2862353] jxcore: disconnect
2016-02-09 00:19:42.002 ThaliTest[1530:2862353] jxcore: disconnect: fail
ok 111 Disconnect should fail 

setting stopBroadcasting callback and ending test.

,# teardown

,calling stopBroadcasting

,2016-02-09 00:19:42.361 ThaliTest[1530:2862353] jxcore: stopBroadcasting
2016-02-09 00:19:42.362 ThaliTest[1530:2862353] THEMultipeerSession stopping peer
2016-02-09 00:19:42.362 ThaliTest[1530:2862353] multipeer session: stop timer
2016-02-09 00:19:42.,363 ThaliTest[1530:2862353] client session: disconnect
2016-02-09 00:19:42.363 ThaliTest[1530:2862353] client session: stateChange:1->0 1454973573917.974.PJWINg==
2016-02-09 00:19:42.364 ThaliTest[1530:2862353] server session: disconnect
2016-02-09 00:1,9:42.364 ThaliTest[1530:2862353] server session: stateChange:2->0 1454973578852.974
2016-02-09 00:19:42.365 ThaliTest[1530:2862353] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# setup

,# ThaliEmitter can connect and send data

,echo server started on port: 58834

,2016-02-09 00:19:43.124 ThaliTest[1530:2862353] jxcore: startBroadcasting
,2016-02-09 00:19:43.126 ThaliTest[1530:2862353] server: starting 1454973583124.1530.X7t7sA==
2016-02-09 00:19:43.126 ThaliTest[1530:2862353] multipeer session: start timer: 0x165bc3e0
2016-02-09 00:19:43.126 ThaliTest[1530:2862353] THEMultipeerSession in,itialized peer 1454973583124.1530
,2016-02-09 00:19:43.127 ThaliTest[1530:2862353] jxcore: startBroadcasting: success
ok 112 Should be able to call startBroadcasting without error

,2016-02-09 00:19:43.602 ThaliTest[1530:2861980] client: found peer: 1454973573917.974.PJWINg==
,2016-02-09 00:19:43.603 ThaliTest[1530:2862353] jxcore: connect 1454973573917.974.PJWINg==
,2016-02-09 00:19:43.604 ThaliTest[1530:2862353] client session: connect
,2016-02-09 00:19:43.605 ThaliTest[1530:2862353] client session: stateChange:0->1 1454973573917.974.PJWINg==
,2016-02-09 00:19:44.050 ThaliTest[1530:2861980] client: found peer: 1454973583695.974.SFONmA==
2016-02-09 00:19:44.052 ThaliTest[1530:2862353] jxcore: connect 1454973583695.974.SFONmA==
2016-02-09 00:19:44.052 ThaliTest[1530:2862353] client session: conn,ect
2016-02-09 00:19:44.053 ThaliTest[1530:2862353] client session: stateChange:0->1 1454973583695.974.SFONmA==
,2016-02-09 00:19:44.372 ThaliTest[1530:2861980] multipeer session: reset timer
2016-02-09 00:19:44.373 ThaliTest[1530:2861980] multipeer session: stop timer
2016-02-09 00:19:44.373 ThaliTest[1530:2861980] multipeer session: start timer: 0x165bc3e0
2016-,02-09 00:19:44.374 ThaliTest[1530:2861980] server session: connect
2016-02-09 00:19:44.374 ThaliTest[1530:2861980] server session: stateChange:0->1 1454973583695.974
2016-02-09 00:19:44.389 ThaliTest[1530:2861980] server: accepting invitation 1454973583695.974
,2016-02-09 00:19:46.676 ThaliTest[1530:2862825] client session: connected
2016-02-09 00:19:46.678 ThaliTest[1530:2862825] client session: stateChange:1->2 1454973583695.974.SFONmA==
,2016-02-09 00:19:46.733 ThaliTest[1530:2862821] client session: fireConnectCallback: 1454973583695.974.SFONmA==
2016-02-09 00:19:46.733 ThaliTest[1530:2862821] jxcore: connect: success
,ok 113 Should be able to connect without error

ok 114 Port should be within range

,2016-02-09 00:19:46.741 ThaliTest[1530:2861980] client: relay established
2016-02-09 00:19:46.741 ThaliTest[1530:2861980] client: new accepted socket: 0x18917d70
,data in 1095

,data in 3285

,data in 17449

2016-02-09 00:19:46.878 ThaliTest[1530:2862825] server session: connected
2016-02-09 00:19:46.878 ThaliTest[1530:2862825] server session: stateChange:1->2 1454973583695.974
,data in 40515

,data in 71175

,data in 112206

,data in 131072

,ok 115 the test messages should be equal

,2016-02-09 00:19:46.985 ThaliTest[1530:2862353] jxcore: disconnect
2016-02-09 00:19:46.986 ThaliTest[1530:2862353] client session: disconnectFromPeer: 1454973583695.974.SFONmA==
2016-02-09 00:19:46.986 ThaliTest[1530:2862353] client session: disconnect
2016-02-09 00:19:46.986 ThaliTest[1530:2862353] client session: stateChange:2->0 1454973583695.974.SFONmA==
,2016-02-09 00:19:46.991 ThaliTest[1530:2862353] jxcore: disconnect: success
ok 116 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# teardown

,2016-02-09 00:19:47.652 ThaliTest[1530:2861980] server relay: connected (to port: 58834)
,2016-02-09 00:19:48.039 ThaliTest[1530:2862825] server session: not connected 1454973583695.974
,calling stopBroadcasting

,2016-02-09 00:19:48.123 ThaliTest[1530:2862353] jxcore: stopBroadcasting
2016-02-09 00:19:48.124 ThaliTest[1530:2862353] THEMultipeerSession stopping peer
2016-02-09 00:19:48.124 ThaliTest[1530:2862353] multipeer session: stop timer
2016-02-09 00:19:48.,124 ThaliTest[1530:2862353] client session: disconnect
2016-02-09 00:19:48.125 ThaliTest[1530:2862353] client session: stateChange:1->0 1454973573917.974.PJWINg==
2016-02-09 00:19:48.126 ThaliTest[1530:2862353] server session: disconnect
2016-02-09 00:1,9:48.126 ThaliTest[1530:2862353] server session: stateChange:2->0 1454973583695.974
,2016-02-09 00:19:48.133 ThaliTest[1530:2862353] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# setup

,# ThaliEmitter handles socket disconnect correctly

,echo server started on port: 58841

,2016-02-09 00:19:48.680 ThaliTest[1530:2862353] jxcore: startBroadcasting
,2016-02-09 00:19:48.684 ThaliTest[1530:2862353] server: starting 1454973588680.1530.6h94OA==
2016-02-09 00:19:48.685 ThaliTest[1530:2862353] multipeer session: start timer: 0x166a02d0
2016-02-09 00:19:48.685 ThaliTest[1530:2862353] THEMultipeerSession in,itialized peer 1454973588680.1530
2016-02-09 00:19:48.685 ThaliTest[1530:2862353] jxcore: startBroadcasting: success
ok 117 Should be able to call startBroadcasting without error

,2016-02-09 00:19:49.533 ThaliTest[1530:2861980] client: found peer: 1454973583695.974.SFONmA==
[{"peerIdentifier":"1454973583695.974.SFONmA==","peerName":"(null)","peerAvailable":true}]

,2016-02-09 00:19:49.536 ThaliTest[1530:2862353] jxcore: connect 1454973583695.974.SFONmA==
,2016-02-09 00:19:49.537 ThaliTest[1530:2862353] client session: connect
2016-02-09 00:19:49.537 ThaliTest[1530:2862353] client session: stateChange:0->1 1454973583695.974.SFONmA==
,2016-02-09 00:19:49.822 ThaliTest[1530:2861980] client: found peer: 1454973589337.974./QEt9Q==
[{"peerIdentifier":"1454973589337.974./QEt9Q==","peerName":"(null)","peerAvailable":true}]

2016-02-09 00:19:49.824 ThaliTest[1530:2862353] jxcore: connect 14,54973589337.974./QEt9Q==
2016-02-09 00:19:49.825 ThaliTest[1530:2862353] client session: connect
2016-02-09 00:19:49.825 ThaliTest[1530:2862353] client session: stateChange:0->1 1454973589337.974./QEt9Q==
,2016-02-09 00:19:50.478 ThaliTest[1530:2861980] multipeer session: reset timer
2016-02-09 00:19:50.478 ThaliTest[1530:2861980] multipeer session: stop timer
2016-02-09 00:19:50.478 ThaliTest[1530:2861980] multipeer session: start timer: 0x166a02d0
2016-,02-09 00:19:50.479 ThaliTest[1530:2861980] server session: connect
2016-02-09 00:19:50.479 ThaliTest[1530:2861980] server session: stateChange:0->1 1454973589337.974
2016-02-09 00:19:50.487 ThaliTest[1530:2861980] server: accepting invitation 1454973589337.974
,2016-02-09 00:19:52.844 ThaliTest[1530:2862826] client session: connected
2016-02-09 00:19:52.845 ThaliTest[1530:2862826] client session: stateChange:1->2 1454973589337.974./QEt9Q==
,2016-02-09 00:19:52.895 ThaliTest[1530:2862919] client session: fireConnectCallback: 1454973589337.974./QEt9Q==
2016-02-09 00:19:52.895 ThaliTest[1530:2862919] jxcore: connect: success
ok 118 Should be able to connect without error

,ok 119 Port should be within range

,ok 120 First connect should succeed

,2016-02-09 00:19:52.957 ThaliTest[1530:2861980] client: relay established
2016-02-09 00:19:52.958 ThaliTest[1530:2861980] client: new accepted socket: 0x18e6d1c0
,ok 121 the test messages should be equal

,ok 122 First send should succeed

,2016-02-09 00:19:53.043 ThaliTest[1530:2861980] client: socket closed
2016-02-09 00:19:53.044 ThaliTest[1530:2861980] client relay: socket disconnected
2016-02-09 00:19:53.044 ThaliTest[1530:2861980] client relay: 0x18e6d1c0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-02-09 00:19:53.044 ThaliTest[1530:2861980] client session: socket closed: 1454973589337.974./QEt9Q==
2016-02-09 0,0:19:53.044 ThaliTest[1530:2861980] client session: onLinkFailure: 1454973589337.974./QEt9Q==
2016-02-09 00:19:53.045 ThaliTest[1530:2861980] client session: disconnect
2016-02-09 00:19:53.045 ThaliTest[1530:2861980] client session: stateChange:2->0 1454,973589337.974./QEt9Q==
,2016-02-09 00:19:53.085 ThaliTest[1530:2861980] client session: fireConnectionErrorEvent: 1454973589337.974./QEt9Q==
,2016-02-09 00:19:53.091 ThaliTest[1530:2862353] jxcore: connect 1454973589337.974./QEt9Q==
,2016-02-09 00:19:53.093 ThaliTest[1530:2862353] client session: connect
,2016-02-09 00:19:53.097 ThaliTest[1530:2862353] client session: stateChange:0->1 1454973589337.974./QEt9Q==
,2016-02-09 00:19:53.226 ThaliTest[1530:2862826] server session: connected
2016-02-09 00:19:53.226 ThaliTest[1530:2862826] server session: stateChange:1->2 1454973589337.974
,2016-02-09 00:19:53.238 ThaliTest[1530:2861980] server relay: connected (to port: 58841)
,2016-02-09 00:19:53.437 ThaliTest[1530:2862826] server session: not connected 1454973589337.974
,2016-02-09 00:19:53.492 ThaliTest[1530:2861980] multipeer session: reset timer
2016-02-09 00:19:53.493 ThaliTest[1530:2861980] multipeer session: stop timer
2016-02-09 00:19:53.493 ThaliTest[1530:2861980] multipeer session: start timer: 0x166a02d0
2016-,02-09 00:19:53.493 ThaliTest[1530:2861980] server: disconnecting to refresh session (1454973589337.974)
2016-02-09 00:19:53.494 ThaliTest[1530:2861980] server session: disconnect
2016-02-09 00:19:53.494 ThaliTest[1530:2861980] server session: stateChange,:2->0 1454973589337.974
,2016-02-09 00:19:53.507 ThaliTest[1530:2861980] server session: connect
2016-02-09 00:19:53.508 ThaliTest[1530:2861980] server session: stateChange:0->1 1454973589337.974
2016-02-09 00:19:53.523 ThaliTest[1530:2861980] server: accepting invitation 1454973589337.974
,2016-02-09 00:19:58.770 ThaliTest[1530:2861980] client: lost peer: 1454973583695.974.SFONmA==
2016-02-09 00:19:58.770 ThaliTest[1530:2861980] client session: onPeerLost: 1454973583695.974.SFONmA==
2016-02-09 00:19:58.771 ThaliTest[1530:2861980] client se,ssion: onLinkFailure: 1454973583695.974.SFONmA==
2016-02-09 00:19:58.771 ThaliTest[1530:2861980] client session: disconnect
2016-02-09 00:19:58.771 ThaliTest[1530:2861980] client session: stateChange:1->0 1454973583695.974.SFONmA==
,2016-02-09 00:19:58.773 ThaliTest[1530:2861980] client session: fireConnectCallback: 1454973583695.974.SFONmA==
2016-02-09 00:19:58.773 ThaliTest[1530:2861980] jxcore: connect: fail: Peer disconnected
[{"peerIdentifier":"1454973583695.974.SFONmA==","peerName":"(null)","peerAvailable":false}]

,2016-02-09 00:19:59.778 ThaliTest[1530:2862353] jxcore: connect 1454973583695.974.SFONmA==
2016-02-09 00:19:59.778 ThaliTest[1530:2862353] client: connect: unreachable 1454973583695.974.SFONmA==
2016-02-09 00:19:59.778 ThaliTest[1530:2862353] jxcore: connect: fail: Peer unreachable
,2016-02-09 00:19:59.938 ThaliTest[1530:2862825] client session: connected
2016-02-09 00:19:59.939 ThaliTest[1530:2862825] client session: stateChange:1->2 1454973589337.974./QEt9Q==
,2016-02-09 00:20:00.062 ThaliTest[1530:2862817] client session: fireConnectCallback: 1454973589337.974./QEt9Q==
2016-02-09 00:20:00.066 ThaliTest[1530:2862817] jxcore: connect: success
,ok 123 Should be able to connect without error

ok 124 Port should be within range

ok 125 Second connect should succeed

,2016-02-09 00:20:00.093 ThaliTest[1530:2861980] client: relay established
2016-02-09 00:20:00.094 ThaliTest[1530:2861980] client: new accepted socket: 0x16612e50
,2016-02-09 00:20:00.194 ThaliTest[1530:2862817] server session: connected
2016-02-09 00:20:00.195 ThaliTest[1530:2862817] server session: stateChange:1->2 1454973589337.974
,2016-02-09 00:20:00.342 ThaliTest[1530:2861980] server relay: connected (to port: 58841)
,ok 126 the test messages should be equal

,ok 127 Second send should succeed

,# teardown

,2016-02-09 00:20:03.252 ThaliTest[1530:2861980] client: socket closed
,2016-02-09 00:20:03.252 ThaliTest[1530:2861980] client relay: socket disconnected
2016-02-09 00:20:03.253 ThaliTest[1530:2861980] client relay: 0x16612e50 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer", UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-02-09 00:20:03.253 ThaliTest[1530:2861980] client session: socket closed: 1454973589337.974./QEt9Q==
2016-02-09 00:20:03.254 ThaliTest[1530:2861980] client session: onLinkFailure: 1454,973589337.974./QEt9Q==
2016-02-09 00:20:03.254 ThaliTest[1530:2861980] client session: disconnect
2016-02-09 00:20:03.254 ThaliTest[1530:2861980] client session: stateChange:2->0 1454973589337.974./QEt9Q==
,2016-02-09 00:20:03.273 ThaliTest[1530:2861980] client session: fireConnectionErrorEvent: 1454973589337.974./QEt9Q==
,calling stopBroadcasting

,2016-02-09 00:20:05.227 ThaliTest[1530:2862353] jxcore: stopBroadcasting
2016-02-09 00:20:05.228 ThaliTest[1530:2862353] THEMultipeerSession stopping peer
2016-02-09 00:20:05.228 ThaliTest[1530:2862353] multipeer session: stop timer
2016-02-09 00:20:05.,229 ThaliTest[1530:2862353] server session: disconnect
2016-02-09 00:20:05.229 ThaliTest[1530:2862353] server session: stateChange:2->0 1454973589337.974
,2016-02-09 00:20:05.246 ThaliTest[1530:2862353] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# setup

,# ThaliReplicationManager can call start without error

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/BABDD1FF-ECCB-4BC6-91EA-BD4A87B2BD1B/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,ok 128 starting event should occur in right order

,2016-02-09 00:20:05.466 ThaliTest[1530:2862353] jxcore: startBroadcasting
,2016-02-09 00:20:05.468 ThaliTest[1530:2862353] server: starting IrWKtz0S2cYg9kvcczVTAA.4gGMkQ==
2016-02-09 00:20:05.468 ThaliTest[1530:2862353] multipeer session: start timer: 0x17eb5f10
2016-02-09 00:20:05.468 ThaliTest[1530:2862353] THEMultipeerSessio,n initialized peer IrWKtz0S2cYg9kvcczVTAA
2016-02-09 00:20:05.468 ThaliTest[1530:2862353] jxcore: startBroadcasting: success
ok 129 started event should occur in right order

Now in TRM stop

State of this._isStarted: true

ok 130 stopping event should occur in right order

About to call stopBroadcasting

,2016-02-09 00:20:05.470 ThaliTest[1530:2862353] jxcore: stopBroadcasting
2016-02-09 00:20:05.470 ThaliTest[1530:2862353] THEMultipeerSession stopping peer
2016-02-09 00:20:05.470 ThaliTest[1530:2862353] multipeer session: stop timer
2016-02-09 00:20:05.,470 ThaliTest[1530:2862353] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

ok 131 stopped event should occur in right order

,mux server bridge listener closed

# teardown

,# setup

,# ThaliReplicationManager receives identity

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/BABDD1FF-ECCB-4BC6-91EA-BD4A87B2BD1B/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-02-09 00:20:05.858 ThaliTest[1530:2862353] jxcore: startBroadcasting
,2016-02-09 00:20:05.862 ThaliTest[1530:2862353] server: starting IrWKtz0S2cYg9kvcczVTAA.cbML7w==
2016-02-09 00:20:05.863 ThaliTest[1530:2862353] multipeer session: start timer: 0x18e653a0
2016-02-09 00:20:05.863 ThaliTest[1530:2862353] THEMultipeerSessio,n initialized peer IrWKtz0S2cYg9kvcczVTAA
2016-02-09 00:20:05.863 ThaliTest[1530:2862353] jxcore: startBroadcasting: success
ok 132 getDeviceIdentity should not return an error

ok 133 deviceName should not be null

Now in TRM stop

State of this._,isStarted: true

About to call stopBroadcasting

2016-02-09 00:20:05.866 ThaliTest[1530:2862353] jxcore: stopBroadcasting
2016-02-09 00:20:05.867 ThaliTest[1530:2862353] THEMultipeerSession stopping peer
2016-02-09 00:20:05.867 ThaliTest[1530:2862353,] multipeer session: stop timer
2016-02-09 00:20:05.867 ThaliTest[1530:2862353] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,mux server bridge listener closed

# teardown

,# setup

,# ThaliReplicationManager replicates database

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/BABDD1FF-ECCB-4BC6-91EA-BD4A87B2BD1B/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-02-09 00:20:10.237 ThaliTest[1530:2862353] jxcore: startBroadcasting
,2016-02-09 00:20:10.239 ThaliTest[1530:2862353] server: starting IrWKtz0S2cYg9kvcczVTAA.WZ2KPg==
,2016-02-09 00:20:10.240 ThaliTest[1530:2862353] multipeer session: start timer: 0x188c6530
2016-02-09 00:20:10.242 ThaliTest[1530:2862353] THEMultipeerSession initialized peer IrWKtz0S2cYg9kvcczVTAA
2016-02-09 00:20:10.242 ThaliTest[1530:2862353] jxcore: startBroadcasting: success
,ok 134 getDeviceIdentity should not return an error

,ok 135 deviceName should not be null

,2016-02-09 00:20:11.451 ThaliTest[1530:2861980] client: found peer: YLI8N2rcDUla7VO39yhBFw.1GXILg==
,2016-02-09 00:20:14.909 ThaliTest[1530:2861980] multipeer session: reset timer
2016-02-09 00:20:14.909 ThaliTest[1530:2861980] multipeer session: stop timer
2016-02-09 00:20:14.909 ThaliTest[1530:2861980] multipeer session: start timer: 0x188c6530
2016-02-09 00:20:14.909 ThaliTest[1530:2861980] server session: connect
2016-02-09 00:20:14.909 ThaliTest[1530:2861980] server session: stateChange:0->1 YLI8N2rcDUla7VO39yhBFw
2016-02-09 00:20:14.912 ThaliTest[1530:2861980] server: accepting invitation YLI8N2rcDUla7VO39yhBFw
,2016-02-09 00:20:14.927 ThaliTest[1530:2862353] jxcore: connect YLI8N2rcDUla7VO39yhBFw.1GXILg==
,2016-02-09 00:20:14.929 ThaliTest[1530:2862353] client session: connect
,2016-02-09 00:20:14.930 ThaliTest[1530:2862353] client session: stateChange:0->1 YLI8N2rcDUla7VO39yhBFw.1GXILg==
,ok 136 Should be able to put doc without error

,ok 137 1st change of local doc should contain local id

,2016-02-09 00:20:17.560 ThaliTest[1530:2863062] server session: connected
,2016-02-09 00:20:17.561 ThaliTest[1530:2863062] server session: stateChange:1->2 YLI8N2rcDUla7VO39yhBFw
,2016-02-09 00:20:17.726 ThaliTest[1530:2861980] server relay: connected (to port: 58859)
,server bridge: new client socket

,2016-02-09 00:20:18.560 ThaliTest[1530:2863062] client session: connected
2016-02-09 00:20:18.561 ThaliTest[1530:2863062] client session: stateChange:1->2 YLI8N2rcDUla7VO39yhBFw.1GXILg==
,2016-02-09 00:20:19.519 ThaliTest[1530:2862919] client session: fireConnectCallback: YLI8N2rcDUla7VO39yhBFw.1GXILg==
2016-02-09 00:20:19.519 ThaliTest[1530:2862919] jxcore: connect: success
,2016-02-09 00:20:19.526 ThaliTest[1530:2861980] client: relay established
2016-02-09 00:20:19.527 ThaliTest[1530:2861980] client: new accepted socket: 0x18e2eac0
,client bridge: new client socket

,client bridge: new client socket

,ok 138 1st change of remote doc should contain remote id

,ok 139 Can update remote doc without error

,null

,{ ok: true,
  id: 'c6e0234a-cac4-4fbc-88c3-8c31a28e85ae',
  rev: '2-c6ad2e7f5295007d6d35134168a56014' }

,client bridge: socket closed

,client bridge: new client socket

,ok 140 Remote changes occur in strict order

,client bridge: socket closed

,client bridge: new client socket
,
,client bridge: socket closed

,client bridge: new client socket
,
,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket
,
,client bridge: socket closed

,client bridge: new client socket

,2016-02-09 00:20:44.910 ThaliTest[1530:2861980] multipeer session: restart
,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,2016-02-09 00:20:55.802 ThaliTest[1530:2862353] Error!: cyclic object value
Stack:[{"_fileName":"/private/var/mobile/Containers/Bundle/Application/ED6CFE00-5ED4-4019-945D-566D75FEEBBC/ThaliTest.app/www/jxcore/lib/thali-tape.js","_functionName":"","_lineNu,mber":"36","_columnNumber":"48","_msg":"    at @/private/var/mobile/Containers/Bundle/Application/ED6CFE00-5ED4-4019-945D-566D75FEEBBC/ThaliTest.app/www/jxcore/lib/thali-tape.js:36:48"},{"_fileName":"events.js","_functionName":"emit","_lineNumber":"98","_c,olumnNumber":"1","_msg":"    at emit@events.js:98:1"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/ED6CFE00-5ED4-4019-945D-566D75FEEBBC/ThaliTest.app/www/jxcore/node_modules/lie/lib/index.js","_functionName":"handlers.reject/<","_lineNum,ber":"128","_columnNumber":"11","_msg":"    at handlers.reject/<@/private/var/mobile/Containers/Bundle/Application/ED6CFE00-5ED4-4019-945D-566D75FEEBBC/ThaliTest.app/www/jxcore/node_modules/lie/lib/index.js:128:11"},{"_fileName":"/private/var/mobile/Contai,ners/Bundle/Application/ED6CFE00-5ED4-4019-945D-566D75FEEBBC/ThaliTest.app/www/jxcore/node_modules/lie/node_modules/immediate/lib/index.js","_functionName":"nextTick","_lineNumber":"61","_columnNumber":"7","_msg":"    at nextTick@/private/var/mobile/Contai,ners/Bundle/Application/ED6CFE00-5ED4-4019-945D-566D75FEEBBC/ThaliTest.app/www/jxcore/node_modules/lie/node_modules/immediate/lib/index.js:61:7"},{"_fileName":"node.js","_functionName":"$0a","_lineNumber":"917","_columnNumber":"1","_msg":"    at $0a@node.j,s:917:1"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/ED6CFE00-5ED4-4019-945D-566D75FEEBBC/ThaliTest.app/www/jxcore/lib/thali-tape.js","_functionName":"unknown","_lineNumber":36,"_columnNumber":47,"_msg":""}]
,Uncaught Exception: TypeError: cyclic object value

,[ { _fileName: '/private/var/mobile/Containers/Bundle/Application/ED6CFE00-5ED4-4019-945D-566D75FEEBBC/ThaliTest.app/www/jxcore/lib/thali-tape.js',
    _functionName: '',
    _lineNumber: '36',
    _columnNumber: '48',
    _msg: '    at @/private/var/m,obile/Containers/Bundle/Application/ED6CFE00-5ED4-4019-945D-566D75FEEBBC/ThaliTest.app/www/jxcore/lib/thali-tape.js:36:48' },
  { _fileName: 'events.js',
    _functionName: 'emit',
    _lineNumber: '98',
    _columnNumber: '1',
    _msg: '    at emit@,events.js:98:1' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/ED6CFE00-5ED4-4019-945D-566D75FEEBBC/ThaliTest.app/www/jxcore/node_modules/lie/lib/index.js',
    _functionName: 'handlers.reject/<',
    _lineNumber: '128',
    _colu,mnNumber: '11',
    _msg: '    at handlers.reject/<@/private/var/mobile/Containers/Bundle/Application/ED6CFE00-5ED4-4019-945D-566D75FEEBBC/ThaliTest.app/www/jxcore/node_modules/lie/lib/index.js:128:11' },
  { _fileName: '/private/var/mobile/Containers/Bu,ndle/Application/ED6CFE00-5ED4-4019-945D-566D75FEEBBC/ThaliTest.app/www/jxcore/node_modules/lie/node_modules/immediate/lib/index.js',
    _functionName: 'nextTick',
    _lineNumber: '61',
    _columnNumber: '7',
    _msg: '    at nextTick@/private/var/,mobile/Containers/Bundle/Application/ED6CFE00-5ED4-4019-945D-566D75FEEBBC/ThaliTest.app/www/jxcore/node_modules/lie/node_modules/immediate/lib/index.js:61:7' },
  { _fileName: 'node.js',
    _functionName: '$0a',
    _lineNumber: '917',
    _columnNumb,er: '1',
    _msg: '    at $0a@node.js:917:1' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/ED6CFE00-5ED4-4019-945D-566D75FEEBBC/ThaliTest.app/www/jxcore/li,b/thali-tape.js',
    _functionName: 'unknown',
    _lineNumber: 36,
    _columnNumber: 47,
    _msg: '' },
  toString: [Function] ]

****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****

TypeError: cyclic object value (/private
```
