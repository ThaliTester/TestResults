#### Test 5838050069f842e_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5838050069f842e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/2B26AFF2-A8B5-4ED6-889A-D1AB191BF000/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/2B26AFF2-A8B5-4ED6-889A-D1AB191BF000/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5838050069f842e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5838050069f842e/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/4D67DB6B-099B-441A-8317-6A360B029446/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50877"
,(lldb)     command script import "/tmp/2B26AFF2-A8B5-4ED6-889A-D1AB191BF000/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-05 20:37:55.871 ThaliTest[735:1154464] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3F703FA1-A05E-4BD5-969B-505BAD68341E/Library/Cookies/Cookies.binarycookies
,2016-02-05 20:37:56.254 ThaliTest[735:1154464] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-05 20:37:56.256 ThaliTest[735:1154464] Multi-tasking -> Device: YES, App: YES
,2016-02-05 20:37:56.265 ThaliTest[735:1154464] Unlimited access to network resources
,2016-02-05 20:37:56.273 ThaliTest[735:1154464] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-05 20:38:05.819 ThaliTest[735:1154464] Resetting plugins due to page load.
,2016-02-05 20:38:09.474 ThaliTest[735:1154464] Finished load of: file:///var/mobile/Containers/Bundle/Application/4D67DB6B-099B-441A-8317-6A360B029446/ThaliTest.app/www/index.html
,2016-02-05 20:38:09.636 ThaliTest[735:1154464] JXcore Cordova plugin initializing
,2016-02-05 20:38:09.636 ThaliTest[735:1154708] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4D67DB6B-099B-441A-8317-6A360B029446/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4D67DB6B-099B-441A-8317-6A360B029446/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4D67DB6B-099B-441A-8317-6A360B029446/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4D67DB6B-099B-441A-8317-6A360B029446/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4D67DB6B-099B-441A-8317-6A360B029446/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4D67DB6B-099B-441A-8317-6A360B029446/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4D67DB6B-099B-441A-8317-6A360B029446/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4D67DB6B-099B-441A-8317-6A360B029446/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4D67DB6B-099B-441A-8317-6A360B029446/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,TAP version 13

,# setup

# #generatePreambleAndBeacons empty keys to notify

,ok 1 should be equal

ok 2 should be equal

,ok 3 should be equal

,ok 4 should be equal

,# teardown

,# setup

,# #generatePreambleAndBeacons multiple keys to notify

,ok 5 should be equal

ok 6 should be equal

,ok 7 should be equal

,ok 8 should be equal

,# teardown

# setup

,# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

,ok 9 should throw

# teardown

,# setup

,# #parseBeacons invalid expiration in beaconStreamWithPreAmble

,ok 10 should throw

,# teardown

,# setup

,# #parseBeacons no beacons returns null

,ok 11 should be equal

,# teardown

# setup

,# #parseBeacons invalid size for encryptedBeaconKeyId in beaconStreamWithPreAmble

,ok 12 should throw

# teardown

,# setup

,# #parseBeacons addressBookCallback fails decrypt

,ok 13 should be equal

# teardown

# setup

,# #parseBeacons addressBookCallback returns null for all

,ok 14 (unnamed assert)

ok 15 should be equal

# teardown

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

,# teardown

,# setup

,# successfully read a previous pkcs12 file and return hash value

,ok 35 (unnamed assert)

,ok 36 (unnamed assert)

,ok 37 should not throw

,ok 38 should be equal

,ok 39 should be equal

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
,
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

,2016-02-05 20:43:04.202 ThaliTest[735:1154708] jxcore: startBroadcasting
,2016-02-05 20:43:04.218 ThaliTest[735:1154708] server: starting 1454701384202.735.ptHKWw==
,2016-02-05 20:43:04.219 ThaliTest[735:1154708] multipeer session: start timer: 0x18bd0590
2016-02-05 20:43:04.220 ThaliTest[735:1154708] THEMultipeerSession initialized peer 1454701384202.735
,2016-02-05 20:43:04.221 ThaliTest[735:1154708] jxcore: startBroadcasting: success
,ok 71 Should be able to call startBroadcasting without error

,2016-02-05 20:43:04.224 ThaliTest[735:1154708] jxcore: stopBroadcasting
2016-02-05 20:43:04.225 ThaliTest[735:1154708] THEMultipeerSession stopping peer
2016-02-05 20:43:04.225 ThaliTest[735:1154708] multipeer session: stop timer
2016-02-05 20:43:04.228 ThaliTest[735:1154708] jxcore: stopBroadcasting: success
ok 72 Should be able to call stopBroadcasting without error

2016-02-05 20:43:04.231 ThaliTest[735:1154708] jxcore: startBroadcasting
,2016-02-05 20:43:04.239 ThaliTest[735:1154708] server: starting 1454701384230.735.IKKkdw==
,2016-02-05 20:43:04.241 ThaliTest[735:1154708] multipeer session: start timer: 0x19ba92a0
,2016-02-05 20:43:04.245 ThaliTest[735:1154708] THEMultipeerSession initialized peer 1454701384230.735
,2016-02-05 20:43:04.247 ThaliTest[735:1154708] jxcore: startBroadcasting: success
,ok 73 Should be able to call startBroadcasting without error

,2016-02-05 20:43:04.250 ThaliTest[735:1154708] jxcore: stopBroadcasting
,2016-02-05 20:43:04.251 ThaliTest[735:1154708] THEMultipeerSession stopping peer
,2016-02-05 20:43:04.252 ThaliTest[735:1154708] multipeer session: stop timer
,2016-02-05 20:43:04.257 ThaliTest[735:1154708] jxcore: stopBroadcasting: success
,ok 74 Should be able to call stopBroadcasting without error

,2016-02-05 20:43:04.260 ThaliTest[735:1154708] jxcore: startBroadcasting
,2016-02-05 20:43:04.263 ThaliTest[735:1154708] server: starting 1454701384260.735.AVPa/A==
,2016-02-05 20:43:04.266 ThaliTest[735:1154708] multipeer session: start timer: 0x18c049e0
,2016-02-05 20:43:04.270 ThaliTest[735:1154708] THEMultipeerSession initialized peer 1454701384260.735
,2016-02-05 20:43:04.273 ThaliTest[735:1154708] jxcore: startBroadcasting: success
,ok 75 Should be able to call startBroadcasting without error

,2016-02-05 20:43:04.275 ThaliTest[735:1154708] jxcore: stopBroadcasting
,2016-02-05 20:43:04.276 ThaliTest[735:1154708] THEMultipeerSession stopping peer
,2016-02-05 20:43:04.277 ThaliTest[735:1154708] multipeer session: stop timer
,2016-02-05 20:43:04.279 ThaliTest[735:1154708] jxcore: stopBroadcasting: success
,ok 76 Should be able to call stopBroadcasting without error

,2016-02-05 20:43:04.284 ThaliTest[735:1154708] jxcore: startBroadcasting
,2016-02-05 20:43:04.288 ThaliTest[735:1154708] server: starting 1454701384283.735.ra24+w==
,2016-02-05 20:43:04.290 ThaliTest[735:1154708] multipeer session: start timer: 0x19ba94f0
,2016-02-05 20:43:04.296 ThaliTest[735:1154708] THEMultipeerSession initialized peer 1454701384283.735
,2016-02-05 20:43:04.297 ThaliTest[735:1154708] jxcore: startBroadcasting: success
,ok 77 Should be able to call startBroadcasting without error

,2016-02-05 20:43:04.300 ThaliTest[735:1154708] jxcore: stopBroadcasting
2016-02-05 20:43:04.301 ThaliTest[735:1154708] THEMultipeerSession stopping peer
2016-02-05 20:43:04.302 ThaliTest[735:1154708] multipeer session: stop timer
2016-02-05 20:43:04.303 ThaliTest[735:1154708] jxcore: stopBroadcasting: success
ok 78 Should be able to call stopBroadcasting without error

2016-02-05 20:43:04.307 ThaliTest[735:1154708] jxcore: startBroadcasting
,2016-02-05 20:43:04.310 ThaliTest[735:1154708] server: starting 1454701384307.735.U5+QmA==
,2016-02-05 20:43:04.312 ThaliTest[735:1154708] multipeer session: start timer: 0x19baa0e0
,2016-02-05 20:43:04.314 ThaliTest[735:1154708] THEMultipeerSession initialized peer 1454701384307.735
,2016-02-05 20:43:04.315 ThaliTest[735:1154708] jxcore: startBroadcasting: success
,ok 79 Should be able to call startBroadcasting without error

,2016-02-05 20:43:04.318 ThaliTest[735:1154708] jxcore: stopBroadcasting
,2016-02-05 20:43:04.318 ThaliTest[735:1154708] THEMultipeerSession stopping peer
,2016-02-05 20:43:04.319 ThaliTest[735:1154708] multipeer session: stop timer
,2016-02-05 20:43:04.322 ThaliTest[735:1154708] jxcore: stopBroadcasting: success
,ok 80 Should be able to call stopBroadcasting without error

,2016-02-05 20:43:04.324 ThaliTest[735:1154708] jxcore: startBroadcasting
,2016-02-05 20:43:04.327 ThaliTest[735:1154708] server: starting 1454701384323.735.aYneZA==
,2016-02-05 20:43:04.328 ThaliTest[735:1154708] multipeer session: start timer: 0x19baa0e0
,2016-02-05 20:43:04.332 ThaliTest[735:1154708] THEMultipeerSession initialized peer 1454701384323.735
,2016-02-05 20:43:04.333 ThaliTest[735:1154708] jxcore: startBroadcasting: success
,ok 81 Should be able to call startBroadcasting without error

,2016-02-05 20:43:04.335 ThaliTest[735:1154708] jxcore: stopBroadcasting
,2016-02-05 20:43:04.336 ThaliTest[735:1154708] THEMultipeerSession stopping peer
,2016-02-05 20:43:04.336 ThaliTest[735:1154708] multipeer session: stop timer
,2016-02-05 20:43:04.337 ThaliTest[735:1154708] jxcore: stopBroadcasting: success
,ok 82 Should be able to call stopBroadcasting without error

,2016-02-05 20:43:04.341 ThaliTest[735:1154708] jxcore: startBroadcasting
,2016-02-05 20:43:04.343 ThaliTest[735:1154708] server: starting 1454701384340.735.Olqxyw==
,2016-02-05 20:43:04.345 ThaliTest[735:1154708] multipeer session: start timer: 0x18f6c2c0
,2016-02-05 20:43:04.348 ThaliTest[735:1154708] THEMultipeerSession initialized peer 1454701384340.735
,2016-02-05 20:43:04.349 ThaliTest[735:1154708] jxcore: startBroadcasting: success
,ok 83 Should be able to call startBroadcasting without error

,2016-02-05 20:43:04.351 ThaliTest[735:1154708] jxcore: stopBroadcasting
,2016-02-05 20:43:04.352 ThaliTest[735:1154708] THEMultipeerSession stopping peer
,2016-02-05 20:43:04.352 ThaliTest[735:1154708] multipeer session: stop timer
,2016-02-05 20:43:04.354 ThaliTest[735:1154708] jxcore: stopBroadcasting: success
,ok 84 Should be able to call stopBroadcasting without error

,2016-02-05 20:43:04.357 ThaliTest[735:1154708] jxcore: startBroadcasting
,2016-02-05 20:43:04.360 ThaliTest[735:1154708] server: starting 1454701384357.735.KK5yNQ==
,2016-02-05 20:43:04.361 ThaliTest[735:1154708] multipeer session: start timer: 0x18d3d800
,2016-02-05 20:43:04.365 ThaliTest[735:1154708] THEMultipeerSession initialized peer 1454701384357.735
,2016-02-05 20:43:04.365 ThaliTest[735:1154708] jxcore: startBroadcasting: success
,ok 85 Should be able to call startBroadcasting without error

,2016-02-05 20:43:04.367 ThaliTest[735:1154708] jxcore: stopBroadcasting
,2016-02-05 20:43:04.368 ThaliTest[735:1154708] THEMultipeerSession stopping peer
,2016-02-05 20:43:04.369 ThaliTest[735:1154708] multipeer session: stop timer
,2016-02-05 20:43:04.372 ThaliTest[735:1154708] jxcore: stopBroadcasting: success
,ok 86 Should be able to call stopBroadcasting without error

,2016-02-05 20:43:04.374 ThaliTest[735:1154708] jxcore: startBroadcasting
,2016-02-05 20:43:04.377 ThaliTest[735:1154708] server: starting 1454701384374.735.om9VLA==
,2016-02-05 20:43:04.378 ThaliTest[735:1154708] multipeer session: start timer: 0x19baaa20
,2016-02-05 20:43:04.382 ThaliTest[735:1154708] THEMultipeerSession initialized peer 1454701384374.735
,2016-02-05 20:43:04.382 ThaliTest[735:1154708] jxcore: startBroadcasting: success
,ok 87 Should be able to call startBroadcasting without error

,2016-02-05 20:43:04.384 ThaliTest[735:1154708] jxcore: stopBroadcasting
,2016-02-05 20:43:04.384 ThaliTest[735:1154708] THEMultipeerSession stopping peer
,2016-02-05 20:43:04.385 ThaliTest[735:1154708] multipeer session: stop timer
,2016-02-05 20:43:04.386 ThaliTest[735:1154708] jxcore: stopBroadcasting: success
,ok 88 Should be able to call stopBroadcasting without error

,2016-02-05 20:43:04.388 ThaliTest[735:1154708] jxcore: startBroadcasting
,2016-02-05 20:43:04.390 ThaliTest[735:1154708] server: starting 1454701384388.735.BtJZ3A==
,2016-02-05 20:43:04.391 ThaliTest[735:1154708] multipeer session: start timer: 0x1990e990
,2016-02-05 20:43:04.394 ThaliTest[735:1154708] THEMultipeerSession initialized peer 1454701384388.735
,2016-02-05 20:43:04.394 ThaliTest[735:1154708] jxcore: startBroadcasting: success
,ok 89 Should be able to call startBroadcasting without error

,2016-02-05 20:43:04.396 ThaliTest[735:1154708] jxcore: stopBroadcasting
,2016-02-05 20:43:04.396 ThaliTest[735:1154708] THEMultipeerSession stopping peer
,2016-02-05 20:43:04.397 ThaliTest[735:1154708] multipeer session: stop timer
,2016-02-05 20:43:04.399 ThaliTest[735:1154708] jxcore: stopBroadcasting: success
,ok 90 Should be able to call stopBroadcasting without error

,# teardown

,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,2016-02-05 20:43:04.667 ThaliTest[735:1154708] jxcore: startBroadcasting
,2016-02-05 20:43:04.671 ThaliTest[735:1154708] server: starting 1454701384667.735.jN0ubA==
,2016-02-05 20:43:04.671 ThaliTest[735:1154708] multipeer session: start timer: 0x19cb94f0
,2016-02-05 20:43:04.672 ThaliTest[735:1154708] THEMultipeerSession initialized peer 1454701384667.735
,2016-02-05 20:43:04.673 ThaliTest[735:1154708] jxcore: startBroadcasting: success
,ok 91 Should be able to call startBroadcasting without error

,2016-02-05 20:43:04.675 ThaliTest[735:1154708] jxcore: startBroadcasting
2016-02-05 20:43:04.676 ThaliTest[735:1154708] jxcore: startBroadcasting: failure
,ok 92 Cannot call startBroadcasting twice

2016-02-05 20:43:04.681 ThaliTest[735:1154708] jxcore: stopBroadcasting
2016-02-05 20:43:04.681 ThaliTest[735:1154708] THEMultipeerSession stopping peer
2016-02-05 20:43:04.681 ThaliTest[735:1154708] multipeer, session: stop timer
,2016-02-05 20:43:04.683 ThaliTest[735:1154708] jxcore: stopBroadcasting: success
ok 93 Should be able to call stopBroadcasting without error

,# teardown

,# setup

,# ThaliEmitter throws on connection to bad peer

,2016-02-05 20:43:05.134 ThaliTest[735:1154708] jxcore: startBroadcasting
,2016-02-05 20:43:05.138 ThaliTest[735:1154708] server: starting 1454701385134.735.IftIjw==
,2016-02-05 20:43:05.138 ThaliTest[735:1154708] multipeer session: start timer: 0x19cbbe40
,2016-02-05 20:43:05.139 ThaliTest[735:1154708] THEMultipeerSession initialized peer 1454701385134.735
,2016-02-05 20:43:05.140 ThaliTest[735:1154708] jxcore: startBroadcasting: success
,ok 94 Should be able to call startBroadcasting without error

2016-02-05 20:43:05.143 ThaliTest[735:1154708] jxcore: connect foobar
2016-02-05 20:43:05.144 ThaliTest[735:1154708] client: unknown peer foobar
2016-02-05 20:43:05.144 ThaliTest[735:1154708,] jxcore: connect: fail: Unknown peer
,ok 95 Should not connect to a bad peer

2016-02-05 20:43:05.148 ThaliTest[735:1154708] jxcore: stopBroadcasting
2016-02-05 20:43:05.148 ThaliTest[735:1154708] THEMultipeerSession stopping peer
2016-02-05 20:43:05.149 ThaliTest[735:1154708] multipeer session: stop timer
,2016-02-05 20:43:05.149 ThaliTest[735:1154708] jxcore: stopBroadcasting: success
,ok 96 Should be able to call stopBroadcasting without error

,# teardown

,# setup

,# ThaliEmitter throws on disconnect to bad peer

,2016-02-05 20:43:06.171 ThaliTest[735:1154708] jxcore: startBroadcasting
,2016-02-05 20:43:06.175 ThaliTest[735:1154708] server: starting 1454701386171.735.L1iDqw==
,2016-02-05 20:43:06.176 ThaliTest[735:1154708] multipeer session: start timer: 0x19cbee20
,2016-02-05 20:43:06.177 ThaliTest[735:1154708] THEMultipeerSession initialized peer 1454701386171.735
2016-02-05 20:43:06.178 ThaliTest[735:1154708] jxcore: startBroadcasting: success
,ok 97 Should be able to call startBroadcasting without error

,2016-02-05 20:43:06.181 ThaliTest[735:1154708] jxcore: disconnect
2016-02-05 20:43:06.181 ThaliTest[735:1154708] jxcore: disconnect: fail
ok 98 Disconnect should fail to a non-existant peer 

2016-02-05 20:43:06.185 ThaliTest[735:1154708] jxcore: stopB,roadcasting
2016-02-05 20:43:06.185 ThaliTest[735:1154708] THEMultipeerSession stopping peer
2016-02-05 20:43:06.185 ThaliTest[735:1154708] multipeer session: stop timer
2016-02-05 20:43:06.186 ThaliTest[735:1154708] jxcore: stopBroadcasting: success
,ok 99 Should be able to call stopBroadcasting without error

,# teardown

,# setup

,# ThaliEmitter can discover and connect to peers

,2016-02-05 20:43:06.756 ThaliTest[735:1154708] jxcore: startBroadcasting
,2016-02-05 20:43:06.759 ThaliTest[735:1154708] server: starting 1454701386755.735.Arvtkw==
,2016-02-05 20:43:06.760 ThaliTest[735:1154708] multipeer session: start timer: 0x19bad4a0
,2016-02-05 20:43:06.761 ThaliTest[735:1154708] THEMultipeerSession initialized peer 1454701386755.735
,2016-02-05 20:43:06.763 ThaliTest[735:1154708] jxcore: startBroadcasting: success
ok 100 Should be able to call startBroadcasting without error

,2016-02-05 20:43:07.936 ThaliTest[735:1154464] client: found peer: 1454701385187.1313.kiZFBA==
,2016-02-05 20:43:07.938 ThaliTest[735:1154708] jxcore: connect 1454701385187.1313.kiZFBA==
2016-02-05 20:43:07.939 ThaliTest[735:1154708] client session: connect
2016-02-05 20:43:07.939 ThaliTest[735:1154708] client session: stateChange:0->1 1454701385187.1313.kiZFBA==
,2016-02-05 20:43:08.131 ThaliTest[735:1154464] multipeer session: reset timer
2016-02-05 20:43:08.132 ThaliTest[735:1154464] multipeer session: stop timer
2016-02-05 20:43:08.132 ThaliTest[735:1154464] multipeer session: start timer: 0x19bad4a0
,2016-02-05 20:43:08.132 ThaliTest[735:1154464] server session: connect
2016-02-05 20:43:08.133 ThaliTest[735:1154464] server session: stateChange:0->1 1454701385187.1313
,2016-02-05 20:43:08.139 ThaliTest[735:1154464] server: accepting invitation 1454701385187.1313
,2016-02-05 20:43:10.822 ThaliTest[735:1155268] client session: connected
2016-02-05 20:43:10.822 ThaliTest[735:1155268] client session: stateChange:1->2 1454701385187.1313.kiZFBA==
,2016-02-05 20:43:10.851 ThaliTest[735:1155282] client session: fireConnectCallback: 1454701385187.1313.kiZFBA==
2016-02-05 20:43:10.852 ThaliTest[735:1155282] jxcore: connect: success
,ok 101 Should be able to connect without error

,ok 102 Port should be within range

,2016-02-05 20:43:10.856 ThaliTest[735:1154708] jxcore: disconnect
,2016-02-05 20:43:10.857 ThaliTest[735:1154708] client session: disconnectFromPeer: 1454701385187.1313.kiZFBA==
,2016-02-05 20:43:10.857 ThaliTest[735:1154708] client session: disconnect
,2016-02-05 20:43:10.858 ThaliTest[735:1154708] client session: stateChange:2->0 1454701385187.1313.kiZFBA==
,2016-02-05 20:43:10.870 ThaliTest[735:1154708] jxcore: disconnect: success
ok 103 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# teardown

,2016-02-05 20:43:11.026 ThaliTest[735:1155320] server session: connected
,2016-02-05 20:43:11.027 ThaliTest[735:1155320] server session: stateChange:1->2 1454701385187.1313
,2016-02-05 20:43:11.068 ThaliTest[735:1154464] server relay: socket disconnected
,2016-02-05 20:43:11.068 ThaliTest[735:1154464] server relay: 0x198b39c0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-05 20:43:11.092 ThaliTest[735:1155266] server session: not connected 1454701385187.1313
,calling stopBroadcasting

,2016-02-05 20:43:11.937 ThaliTest[735:1154708] jxcore: stopBroadcasting
,2016-02-05 20:43:11.938 ThaliTest[735:1154708] THEMultipeerSession stopping peer
,2016-02-05 20:43:11.939 ThaliTest[735:1154708] multipeer session: stop timer
,2016-02-05 20:43:11.939 ThaliTest[735:1154708] server session: disconnect
2016-02-05 20:43:11.940 ThaliTest[735:1154708] server session: stateChange:2->0 1454701385187.1313
,2016-02-05 20:43:11.943 ThaliTest[735:1154708] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# setup

,# ThaliEmitter can discover and connect to peers and then fail on double connect

,2016-02-05 20:43:12.470 ThaliTest[735:1154708] jxcore: startBroadcasting
,2016-02-05 20:43:12.474 ThaliTest[735:1154708] server: starting 1454701392470.735.UkKx9A==
,2016-02-05 20:43:12.475 ThaliTest[735:1154708] multipeer session: start timer: 0x1980f810
2016-02-05 20:43:12.476 ThaliTest[735:1154708] THEMultipeerSession initialized peer 1454701392470.735
2016-02-05 20:43:12.476 ThaliTest[735:1154708] jxcore: startBroadcasting: success
,ok 104 Should be able to call startBroadcasting without error

,2016-02-05 20:43:13.159 ThaliTest[735:1154464] client: found peer: 1454701385187.1313.kiZFBA==
,2016-02-05 20:43:13.161 ThaliTest[735:1154708] jxcore: connect 1454701385187.1313.kiZFBA==
2016-02-05 20:43:13.162 ThaliTest[735:1154708] client session: connect
2016-02-05 20:43:13.162 ThaliTest[735:1154708] client session: stateChange:0->1 1454701385187.1313.kiZFBA==
,2016-02-05 20:43:13.635 ThaliTest[735:1154464] client: found peer: 1454701390915.1313.m44ORw==
,2016-02-05 20:43:13.636 ThaliTest[735:1154708] jxcore: connect 1454701390915.1313.m44ORw==
2016-02-05 20:43:13.637 ThaliTest[735:1154708] client session: connect
2016-02-05 20:43:13.637 ThaliTest[735:1154708] client session: stateChange:0->1 1454701390915.1313.m44ORw==
,2016-02-05 20:43:13.837 ThaliTest[735:1154464] multipeer session: reset timer
2016-02-05 20:43:13.837 ThaliTest[735:1154464] multipeer session: stop timer
,2016-02-05 20:43:13.837 ThaliTest[735:1154464] multipeer session: start timer: 0x1980f810
2016-02-05 20:43:13.838 ThaliTest[735:1154464] server session: connect
,2016-02-05 20:43:13.838 ThaliTest[735:1154464] server session: stateChange:0->1 1454701390915.1313
,2016-02-05 20:43:13.846 ThaliTest[735:1154464] server: accepting invitation 1454701390915.1313
,2016-02-05 20:43:16.455 ThaliTest[735:1155282] client session: connected
,2016-02-05 20:43:16.455 ThaliTest[735:1155282] client session: stateChange:1->2 1454701390915.1313.m44ORw==
,2016-02-05 20:43:16.473 ThaliTest[735:1155267] client session: fireConnectCallback: 1454701390915.1313.m44ORw==
2016-02-05 20:43:16.473 ThaliTest[735:1155267] jxcore: connect: success
,ok 105 Should be able to connect without error

,ok 106 Port should be within range

,2016-02-05 20:43:16.478 ThaliTest[735:1154708] jxcore: connect 1454701390915.1313.m44ORw==
,2016-02-05 20:43:16.479 ThaliTest[735:1154708] client: already connect(ing/ed) to 1454701390915.1313.m44ORw==
,2016-02-05 20:43:16.479 ThaliTest[735:1154708] jxcore: connect: fail: Aleady connecting
,ok 107 Should fail on double connect

,2016-02-05 20:43:16.483 ThaliTest[735:1154708] jxcore: disconnect
,2016-02-05 20:43:16.484 ThaliTest[735:1154708] client session: disconnectFromPeer: 1454701390915.1313.m44ORw==
2016-02-05 20:43:16.484 ThaliTest[735:1154708] client session: disconnect
2016-02-05 20:43:16.485 ThaliTest[735:1154708] client session: stateC,hange:2->0 1454701390915.1313.m44ORw==
,2016-02-05 20:43:16.496 ThaliTest[735:1154708] jxcore: disconnect: success
ok 108 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# teardown

,2016-02-05 20:43:16.625 ThaliTest[735:1155282] server session: connected
2016-02-05 20:43:16.626 ThaliTest[735:1155282] server session: stateChange:1->2 1454701390915.1313
,2016-02-05 20:43:16.647 ThaliTest[735:1154464] server relay: socket disconnected
,2016-02-05 20:43:16.647 ThaliTest[735:1154464] server relay: 0x19aa6d30 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection r,efused} 
,2016-02-05 20:43:16.682 ThaliTest[735:1155282] server session: not connected 1454701390915.1313
,calling stopBroadcasting

2016-02-05 20:43:17.178 ThaliTest[735:1154708] jxcore: stopBroadcasting
2016-02-05 20:43:17.179 ThaliTest[735:1154708] THEMultipeerSession stopping peer
2016-02-05 20:43:17.179 ThaliTest[735:1154708] multipeer session: stop ti,mer
2016-02-05 20:43:17.179 ThaliTest[735:1154708] client session: disconnect
2016-02-05 20:43:17.180 ThaliTest[735:1154708] client session: stateChange:1->0 1454701385187.1313.kiZFBA==
2016-02-05 20:43:17.180 ThaliTest[735:1154708] server session: disconnect
2016-02-05 20:43:17.181 ThaliTest[735:1154708] server session: stateChange:2->0 1454701390915.1313
,2016-02-05 20:43:17.184 ThaliTest[735:1154708] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# setup

,# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,2016-02-05 20:43:17.548 ThaliTest[735:1154708] jxcore: startBroadcasting
,2016-02-05 20:43:17.552 ThaliTest[735:1154708] server: starting 1454701397548.735.zXyGdw==
,2016-02-05 20:43:17.553 ThaliTest[735:1154708] multipeer session: start timer: 0x18cef310
,2016-02-05 20:43:17.555 ThaliTest[735:1154708] THEMultipeerSession initialized peer 1454701397548.735
,2016-02-05 20:43:17.556 ThaliTest[735:1154708] jxcore: startBroadcasting: success
,ok 109 Should be able to call startBroadcasting without error

,2016-02-05 20:43:18.418 ThaliTest[735:1154464] client: found peer: 1454701390915.1313.m44ORw==
,2016-02-05 20:43:18.420 ThaliTest[735:1154708] jxcore: connect 1454701390915.1313.m44ORw==
,2016-02-05 20:43:18.421 ThaliTest[735:1154708] client session: connect
,2016-02-05 20:43:18.421 ThaliTest[735:1154708] client session: stateChange:0->1 1454701390915.1313.m44ORw==
,2016-02-05 20:43:18.429 ThaliTest[735:1154464] client: found peer: 1454701395970.1313.zo8WgA==
,2016-02-05 20:43:18.432 ThaliTest[735:1154708] jxcore: connect 1454701395970.1313.zo8WgA==
2016-02-05 20:43:18.432 ThaliTest[735:1154708] client session: connect
2016-02-05 20:43:18.433 ThaliTest[735:1154708] client session: stateChange:0->1 145470139597,0.1313.zo8WgA==
,2016-02-05 20:43:18.905 ThaliTest[735:1154464] multipeer session: reset timer
2016-02-05 20:43:18.905 ThaliTest[735:1154464] multipeer session: stop timer
,2016-02-05 20:43:18.905 ThaliTest[735:1154464] multipeer session: start timer: 0x18cef310
,2016-02-05 20:43:18.907 ThaliTest[735:1154464] server session: connect
2016-02-05 20:43:18.907 ThaliTest[735:1154464] server session: stateChange:0->1 1454701395970.1313
,2016-02-05 20:43:18.914 ThaliTest[735:1154464] server: accepting invitation 1454701395970.1313
,2016-02-05 20:43:21.631 ThaliTest[735:1155411] client session: connected
,2016-02-05 20:43:21.631 ThaliTest[735:1155411] client session: stateChange:1->2 1454701395970.1313.zo8WgA==
,2016-02-05 20:43:21.671 ThaliTest[735:1155266] client session: fireConnectCallback: 1454701395970.1313.zo8WgA==
2016-02-05 20:43:21.671 ThaliTest[735:1155266] jxcore: connect: success
,ok 110 Should be able to connect without error

,ok 111 Port should be within range

,2016-02-05 20:43:21.676 ThaliTest[735:1154708] jxcore: disconnect
,2016-02-05 20:43:21.677 ThaliTest[735:1154708] client session: disconnectFromPeer: 1454701395970.1313.zo8WgA==
,2016-02-05 20:43:21.678 ThaliTest[735:1154708] client session: disconnect
,2016-02-05 20:43:21.678 ThaliTest[735:1154708] client session: stateChange:2->0 1454701395970.1313.zo8WgA==
,2016-02-05 20:43:21.687 ThaliTest[735:1154708] jxcore: disconnect: success
,ok 112 Should be able to disconnect without error

2016-02-05 20:43:21.690 ThaliTest[735:1154708] jxcore: disconnect
,2016-02-05 20:43:21.691 ThaliTest[735:1154708] jxcore: disconnect: fail
,ok 113 Disconnect should fail 

setting stopBroadcasting callback and ending test.

,2016-02-05 20:43:21.710 ThaliTest[735:1155268] server session: connected
,2016-02-05 20:43:21.710 ThaliTest[735:1155268] server session: stateChange:1->2 1454701395970.1313
,# teardown

,2016-02-05 20:43:21.761 ThaliTest[735:1154464] server relay: socket disconnected
,2016-02-05 20:43:21.761 ThaliTest[735:1154464] server relay: 0x19bb2ef0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-05 20:43:21.790 ThaliTest[735:1155355] server session: not connected 1454701395970.1313
,calling stopBroadcasting

,2016-02-05 20:43:21.969 ThaliTest[735:1154708] jxcore: stopBroadcasting
,2016-02-05 20:43:21.969 ThaliTest[735:1154708] THEMultipeerSession stopping peer
,2016-02-05 20:43:21.970 ThaliTest[735:1154708] multipeer session: stop timer
,2016-02-05 20:43:21.971 ThaliTest[735:1154708] client session: disconnect
,2016-02-05 20:43:21.971 ThaliTest[735:1154708] client session: stateChange:1->0 1454701390915.1313.m44ORw==
,2016-02-05 20:43:21.973 ThaliTest[735:1154708] server session: disconnect
2016-02-05 20:43:21.973 ThaliTest[735:1154708] server session: stateChange:2->0 1454701395970.1313
,2016-02-05 20:43:21.974 ThaliTest[735:1154708] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# setup

,# ThaliEmitter can connect and send data

,echo server started on port: 53812

,2016-02-05 20:43:23.087 ThaliTest[735:1154708] jxcore: startBroadcasting
,2016-02-05 20:43:23.088 ThaliTest[735:1154708] server: starting 1454701403087.735.FB5Qcw==
,2016-02-05 20:43:23.088 ThaliTest[735:1154708] multipeer session: start timer: 0x18b9e960
2016-02-05 20:43:23.089 ThaliTest[735:1154708] THEMultipeerSession initialized peer 1454701403087.735
2016-02-05 20:43:23.089 ThaliTest[735:1154708] jxcore: startBroadcasting: success
,ok 114 Should be able to call startBroadcasting without error

,2016-02-05 20:43:23.189 ThaliTest[735:1154464] client: found peer: 1454701395970.1313.zo8WgA==
,2016-02-05 20:43:23.189 ThaliTest[735:1154708] jxcore: connect 1454701395970.1313.zo8WgA==
2016-02-05 20:43:23.190 ThaliTest[735:1154708] client session: connect
2016-02-05 20:43:23.190 ThaliTest[735:1154708] client session: stateChange:0->1 1454701395970.1313.zo8WgA==
,2016-02-05 20:43:24.201 ThaliTest[735:1154464] multipeer session: reset timer
2016-02-05 20:43:24.202 ThaliTest[735:1154464] multipeer session: stop timer
2016-02-05 20:43:24.202 ThaliTest[735:1154464] multipeer session: start timer: 0x18b9e960
2016-02-05 20:43:24.202 ThaliTest[735:1154464] server session: connect
,2016-02-05 20:43:24.203 ThaliTest[735:1154464] server session: stateChange:0->1 1454701402099.1313
,2016-02-05 20:43:24.209 ThaliTest[735:1154464] server: accepting invitation 1454701402099.1313
,2016-02-05 20:43:24.650 ThaliTest[735:1154464] client: found peer: 1454701402099.1313.hPRMKw==
,2016-02-05 20:43:24.651 ThaliTest[735:1154708] jxcore: connect 1454701402099.1313.hPRMKw==
2016-02-05 20:43:24.651 ThaliTest[735:1154708] client session: connect
2016-02-05 20:43:24.651 ThaliTest[735:1154708] client session: stateChange:0->1 1454701402099.1313.hPRMKw==
,2016-02-05 20:43:26.983 ThaliTest[735:1155411] server session: connected
,2016-02-05 20:43:26.984 ThaliTest[735:1155411] server session: stateChange:1->2 1454701402099.1313
,2016-02-05 20:43:27.003 ThaliTest[735:1154464] server relay: connected (to port: 53812)
,2016-02-05 20:43:27.353 ThaliTest[735:1155282] server session: not connected 1454701402099.1313
,2016-02-05 20:43:27.459 ThaliTest[735:1155282] client session: connected
2016-02-05 20:43:27.459 ThaliTest[735:1155282] client session: stateChange:1->2 1454701402099.1313.hPRMKw==
,2016-02-05 20:43:27.470 ThaliTest[735:1155411] client session: fireConnectCallback: 1454701402099.1313.hPRMKw==
2016-02-05 20:43:27.470 ThaliTest[735:1155411] jxcore: connect: success
,ok 115 Should be able to connect without error

,ok 116 Port should be within range

,2016-02-05 20:43:27.473 ThaliTest[735:1154464] client: relay established
2016-02-05 20:43:27.473 ThaliTest[735:1154464] client: new accepted socket: 0x18cf32c0
,data in 12045

,data in 20805

,data in 21900

,data in 45990

,data in 81030

,data in 87600

,data in 97455

,data in 119213

,data in 131072

,ok 117 the test messages should be equal

,2016-02-05 20:43:27.671 ThaliTest[735:1154708] jxcore: disconnect
2016-02-05 20:43:27.671 ThaliTest[735:1154708] client session: disconnectFromPeer: 1454701402099.1313.hPRMKw==
,2016-02-05 20:43:27.671 ThaliTest[735:1154708] client session: disconnect
,2016-02-05 20:43:27.671 ThaliTest[735:1154708] client session: stateChange:2->0 1454701402099.1313.hPRMKw==
,2016-02-05 20:43:27.734 ThaliTest[735:1154708] jxcore: disconnect: success
,ok 118 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# teardown

,calling stopBroadcasting

,2016-02-05 20:43:28.187 ThaliTest[735:1154708] jxcore: stopBroadcasting
,2016-02-05 20:43:28.187 ThaliTest[735:1154708] THEMultipeerSession stopping peer
,2016-02-05 20:43:28.188 ThaliTest[735:1154708] multipeer session: stop timer
2016-02-05 20:43:28.189 ThaliTest[735:1154708] client session: disconnect
2016-02-05 20:43:28.189 ThaliTest[735:1154708] client session: stateChange:1->0 1454701395970.1313.zo8WgA==
2016-02-05 20:43:28.190 ThaliTest[735:1154708] server session: disconnect
,2016-02-05 20:43:28.190 ThaliTest[735:1154708] server session: stateChange:2->0 1454701402099.1313
,2016-02-05 20:43:28.202 ThaliTest[735:1154708] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# setup

,# ThaliEmitter handles socket disconnect correctly

,echo server started on port: 53819

,2016-02-05 20:43:28.595 ThaliTest[735:1154708] jxcore: startBroadcasting
,2016-02-05 20:43:28.598 ThaliTest[735:1154708] server: starting 1454701408594.735.Dt6WEQ==
,2016-02-05 20:43:28.599 ThaliTest[735:1154708] multipeer session: start timer: 0x16f7b9d0
,2016-02-05 20:43:28.600 ThaliTest[735:1154708] THEMultipeerSession initialized peer 1454701408594.735
,2016-02-05 20:43:28.600 ThaliTest[735:1154708] jxcore: startBroadcasting: success
ok 119 Should be able to call startBroadcasting without error

,2016-02-05 20:43:29.319 ThaliTest[735:1154464] client: found peer: 1454701402099.1313.hPRMKw==
,[{"peerIdentifier":"1454701402099.1313.hPRMKw==","peerName":"(null)","peerAvailable":true}]

,2016-02-05 20:43:29.323 ThaliTest[735:1154708] jxcore: connect 1454701402099.1313.hPRMKw==
,2016-02-05 20:43:29.323 ThaliTest[735:1154708] client session: connect
,2016-02-05 20:43:29.324 ThaliTest[735:1154708] client session: stateChange:0->1 1454701402099.1313.hPRMKw==
,2016-02-05 20:43:30.406 ThaliTest[735:1154464] client: found peer: 1454701406734.1313.htI4ng==
,[{"peerIdentifier":"1454701406734.1313.htI4ng==","peerName":"(null)","peerAvailable":true}]

,2016-02-05 20:43:30.408 ThaliTest[735:1154708] jxcore: connect 1454701406734.1313.htI4ng==
,2016-02-05 20:43:30.409 ThaliTest[735:1154708] client session: connect
,2016-02-05 20:43:30.410 ThaliTest[735:1154708] client session: stateChange:0->1 1454701406734.1313.htI4ng==
,2016-02-05 20:43:32.481 ThaliTest[735:1154464] multipeer session: reset timer
2016-02-05 20:43:32.482 ThaliTest[735:1154464] multipeer session: stop timer
2016-02-05 20:43:32.482 ThaliTest[735:1154464] multipeer session: start timer: 0x16f7b9d0
,2016-02-05 20:43:32.482 ThaliTest[735:1154464] server session: connect
2016-02-05 20:43:32.483 ThaliTest[735:1154464] server session: stateChange:0->1 1454701406734.1313
,2016-02-05 20:43:32.491 ThaliTest[735:1154464] server: accepting invitation 1454701406734.1313
,2016-02-05 20:43:32.774 ThaliTest[735:1154464] client: lost peer: 1454701402099.1313.hPRMKw==
2016-02-05 20:43:32.774 ThaliTest[735:1154464] client session: onPeerLost: 1454701402099.1313.hPRMKw==
2016-02-05 20:43:32.774 ThaliTest[735:1154464] client ses,sion: onLinkFailure: 1454701402099.1313.hPRMKw==
2016-02-05 20:43:32.774 ThaliTest[735:1154464] client session: disconnect
2016-02-05 20:43:32.774 ThaliTest[735:1154464] client session: stateChange:1->0 1454701402099.1313.hPRMKw==
2016-02-05 20:43:32.775 ThaliTest[735:1154464] client session: fireConnectCallback: 1454701402099.1313.hPRMKw==
2016-02-05 20:43:32.775 ThaliTest[735:1154464] jxcore: connect: fail: Peer disconnected
[{"peerIdentifier":"1454701402099.1313.hPRMKw==","peerName":"(null)","peerAvailable":false}]

,2016-02-05 20:43:33.788 ThaliTest[735:1154708] jxcore: connect 1454701402099.1313.hPRMKw==
,2016-02-05 20:43:33.789 ThaliTest[735:1154708] client: connect: unreachable 1454701402099.1313.hPRMKw==
,2016-02-05 20:43:33.789 ThaliTest[735:1154708] jxcore: connect: fail: Peer unreachable
,2016-02-05 20:43:35.054 ThaliTest[735:1155411] client session: connected
,2016-02-05 20:43:35.057 ThaliTest[735:1155411] client session: stateChange:1->2 1454701406734.1313.htI4ng==
,2016-02-05 20:43:35.073 ThaliTest[735:1155267] client session: fireConnectCallback: 1454701406734.1313.htI4ng==
2016-02-05 20:43:35.074 ThaliTest[735:1155267] jxcore: connect: success
,ok 120 Should be able to connect without error

,ok 121 Port should be within range

,ok 122 First connect should succeed

,2016-02-05 20:43:35.135 ThaliTest[735:1154464] client: relay established
2016-02-05 20:43:35.136 ThaliTest[735:1154464] client: new accepted socket: 0x16ee5ac0
,2016-02-05 20:43:37.822 ThaliTest[735:1155267] server session: connected
2016-02-05 20:43:37.823 ThaliTest[735:1155267] server session: stateChange:1->2 1454701406734.1313
,2016-02-05 20:43:37.875 ThaliTest[735:1154464] server relay: connected (to port: 53819)
,2016-02-05 20:43:38.005 ThaliTest[735:1155411] server session: not connected 1454701406734.1313
,2016-02-05 20:43:38.144 ThaliTest[735:1154464] multipeer session: reset timer
2016-02-05 20:43:38.144 ThaliTest[735:1154464] multipeer session: stop timer
,2016-02-05 20:43:38.144 ThaliTest[735:1154464] multipeer session: start timer: 0x16f7b9d0
2016-02-05 20:43:38.145 ThaliTest[735:1154464] server: disconnecting to refresh session (1454701406734.1313)
,2016-02-05 20:43:38.145 ThaliTest[735:1154464] server session: disconnect
2016-02-05 20:43:38.145 ThaliTest[735:1154464] server session: stateChange:2->0 1454701406734.1313
,2016-02-05 20:43:38.149 ThaliTest[735:1154464] server session: connect
2016-02-05 20:43:38.149 ThaliTest[735:1154464] server session: stateChange:0->1 1454701406734.1313
,2016-02-05 20:43:38.160 ThaliTest[735:1154464] server: accepting invitation 1454701406734.1313
,ok 123 the test messages should be equal

,ok 124 First send should succeed

,2016-02-05 20:43:38.194 ThaliTest[735:1154464] client: socket closed
2016-02-05 20:43:38.194 ThaliTest[735:1154464] client relay: socket disconnected
2016-02-05 20:43:38.195 ThaliTest[735:1154464] client relay: 0x16ee5ac0 disconnected with error Error Do,main=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-02-05 20:43:38.195 ThaliTest[735:1154464] client session: socket closed: 1454701406734.1313.htI4ng==
2016-02-05 20:4,3:38.195 ThaliTest[735:1154464] client session: onLinkFailure: 1454701406734.1313.htI4ng==
2016-02-05 20:43:38.196 ThaliTest[735:1154464] client session: disconnect
2016-02-05 20:43:38.196 ThaliTest[735:1154464] client session: stateChange:2->0 145470140,6734.1313.htI4ng==
,2016-02-05 20:43:38.213 ThaliTest[735:1154464] client session: fireConnectionErrorEvent: 1454701406734.1313.htI4ng==
2016-02-05 20:43:38.218 ThaliTest[735:1154708] jxcore: connect 1454701406734.1313.htI4ng==
2016-02-05 20:43:38.220 ThaliTest[735:1154708], client session: connect
2016-02-05 20:43:38.220 ThaliTest[735:1154708] client session: stateChange:0->1 1454701406734.1313.htI4ng==
,2016-02-05 20:43:38.787 ThaliTest[735:1155462] server session: not connected 1454701406734.1313
,2016-02-05 20:43:50.646 ThaliTest[735:1154464] multipeer session: reset timer
2016-02-05 20:43:50.647 ThaliTest[735:1154464] multipeer session: stop timer
2016-02-05 20:43:50.647 ThaliTest[735:1154464] multipeer session: start timer: 0x16f7b9d0
,2016-02-05 20:43:50.647 ThaliTest[735:1154464] server: disconnecting to refresh session (1454701406734.1313)
2016-02-05 20:43:50.648 ThaliTest[735:1154464] server session: disconnect
,2016-02-05 20:43:50.648 ThaliTest[735:1154464] server session: stateChange:1->0 1454701406734.1313
,2016-02-05 20:43:50.703 ThaliTest[735:1154464] server session: connect
2016-02-05 20:43:50.703 ThaliTest[735:1154464] server session: stateChange:0->1 1454701406734.1313
,2016-02-05 20:43:50.710 ThaliTest[735:1154464] server: accepting invitation 1454701406734.1313
,2016-02-05 20:43:51.837 ThaliTest[735:1155463] server session: connected
2016-02-05 20:43:51.838 ThaliTest[735:1155463] server session: stateChange:1->2 1454701406734.1313
,2016-02-05 20:43:51.881 ThaliTest[735:1154464] server relay: connected (to port: 53819)
,2016-02-05 20:43:53.725 ThaliTest[735:1155267] server session: not connected 1454701406734.1313
,2016-02-05 20:43:58.202 ThaliTest[735:1155267] client session: not connected 1454701406734.1313.htI4ng==
2016-02-05 20:43:58.203 ThaliTest[735:1155267] client session: onLinkFailure: 1454701406734.1313.htI4ng==
,2016-02-05 20:43:58.203 ThaliTest[735:1155267] client session: disconnect
2016-02-05 20:43:58.204 ThaliTest[735:1155267] client session: stateChange:1->0 1454701406734.1313.htI4ng==
,2016-02-05 20:43:58.205 ThaliTest[735:1155267] client session: fireConnectCallback: 1454701406734.1313.htI4ng==
2016-02-05 20:43:58.205 ThaliTest[735:1155267] jxcore: connect: fail: Peer disconnected
,2016-02-05 20:43:59.216 ThaliTest[735:1154708] jxcore: connect 1454701406734.1313.htI4ng==
,2016-02-05 20:43:59.217 ThaliTest[735:1154708] client session: connect
,2016-02-05 20:43:59.217 ThaliTest[735:1154708] client session: stateChange:0->1 1454701406734.1313.htI4ng==
,2016-02-05 20:44:01.294 ThaliTest[735:1155514] client session: connected
2016-02-05 20:44:01.294 ThaliTest[735:1155514] client session: stateChange:1->2 1454701406734.1313.htI4ng==
,2016-02-05 20:44:20.649 ThaliTest[735:1154464] multipeer session: restart
,2016-02-05 20:44:20.680 ThaliTest[735:1154464] client: found peer: 1454701406734.1313.htI4ng==
,2016-02-05 20:44:50.649 ThaliTest[735:1154464] multipeer session: restart
,2016-02-05 20:44:50.671 ThaliTest[735:1154464] client: found peer: 1454701406734.1313.htI4ng==
,2016-02-05 20:45:20.649 ThaliTest[735:1154464] multipeer session: restart
,2016-02-05 20:45:20.672 ThaliTest[735:1154464] client: found peer: 1454701406734.1313.htI4ng==
,2016-02-05 20:45:50.649 ThaliTest[735:1154464] multipeer session: restart
,2016-02-05 20:45:50.674 ThaliTest[735:1154464] client: found peer: 1454701406734.1313.htI4ng==
,2016-02-05 20:46:20.648 ThaliTest[735:1154464] multipeer session: restart
,2016-02-05 20:46:20.674 ThaliTest[735:1154464] client: found peer: 1454701406734.1313.htI4ng==
,2016-02-05 20:46:33.378 ThaliTest[735:1156594] client session: not connected 1454701406734.1313.htI4ng==
2016-02-05 20:46:33.378 ThaliTest[735:1156594] client session: onLinkFailure: 1454701406734.1313.htI4ng==
,2016-02-05 20:46:33.378 ThaliTest[735:1156594] client session: disconnect
2016-02-05 20:46:33.379 ThaliTest[735:1156594] client session: stateChange:2->0 1454701406734.1313.htI4ng==
,2016-02-05 20:46:33.380 ThaliTest[735:1156594] client session: fireConnectionErrorEvent: 1454701406734.1313.htI4ng==
2016-02-05 20:46:33.382 ThaliTest[735:1154708] jxcore: connect 1454701406734.1313.htI4ng==
Assertion failed: (_connectCallback == nil), f,unction -[THEMultipeerClientSession connectWithConnectCallback:], file /Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Plugins/org.thaliproject.p2p/THEMultipeerClientSession.m, line 63.
,Process 735 stopped
* thread #16: tid = 0x119e94, 0x36ad3c84 libsystem_kernel.dylib`__pthread_kill + 8, stop reason = signal SIGABRT
    frame #0: 0x36ad3c84 libsystem_kernel.dylib`__pthread_kill + 8
libsystem_kernel.dylib`__pthread_kill:
->  0x36ad3c84 <+8>:  blo    0x36ad3c9c                ; <+32>
    0x36ad3c88 <+12>: ldr    r12, [pc, #0x4]           ; <+24>
    0x36ad3c8c <+16>: ldr    r12, [pc, r12]
    0x36ad3c90 <+20>: b      0x36ad3c98                ; <+28>
,* thread #16: tid = 0x119e94, 0x36ad3c84 libsystem_kernel.dylib`__pthread_kill + 8, stop reason = signal SIGABRT
  * frame #0: 0x36ad3c84 libsystem_kernel.dylib`__pthread_kill + 8
    frame #1: 0x36b73b46 libsystem_pthread.dylib`pthread_kill + 62
    frame #2: 0x36a6bf40 libsystem_c.dylib`abort + 108
    frame #3: 0x36a4b6ce libsystem_c.dylib`__assert_rtn + 302
    frame #4: 0x00036e8e ThaliTest`-[THEMultipeerClientSession connectWithConnectCallback:] + 254
    frame #5: 0x00033392 ThaliTest`__74-[THEMultipeerClient connectToPeerWithPeerIdentifier:withConnectCallback:]_block_invoke + 250
    frame #6: 0x0005a192 ThaliTest`__52-[THESessionDictionary updateForPeerID:updateBlock:]_block_invoke + 42
    frame #7: 0x00059940 ThaliTest`-[THEProtectedMutableDictionary updateForKey:updateBlock:] + 176
    frame #8: 0x0005a132 ThaliTest`-[THESessionDictionary updateForPeerID:updateBlock:] + 230
    frame #9: 0x0005a41a ThaliTest`-[THESessionDictionary updateForPeerIdentifier:updateBlock:] + 166
    frame #10: 0x00033156 ThaliTest`-[THEMultipeerClient connectToPeerWithPeerIdentifier:withConnectCallback:] + 346
    frame #11: 0x00032a46 ThaliTest`-[THEMultipeerSession connectToPeerServerWithPeerIdentifier:withConnectCallback:] + 106
    frame #12: 0x0002d4ea ThaliTest`-[THEAppContext connectToPeer:connectCallback:] + 222
    frame #13: 0x0002b49a ThaliTest`__32-[JXcoreExtension defineMethods]_block_invoke53 + 718
    frame #14: 0x00026b38 ThaliTest`callJXcoreNative + 644
    frame #15: 0x000ad4f0 ThaliTest`extensionCallback(JSContext*, unsigned int, JS::Value*) + 284
    frame #16: 0x001ed2ae ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 230
    frame #17: 0x001871c8 ThaliTest`js_fun_apply(JSContext*, unsigned int, JS::Value*) + 612
    frame #18: 0x001ed2ae ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 230
    frame #19: 0x001ea82e ThaliTest`___lldb_unnamed_function930$$ThaliTest + 17614
    frame #20: 0x001e6346 ThaliTest`js::RunScript(JSContext*, js::RunState&) + 154
    frame #21: 0x001ed34c ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 388
    frame #22: 0x001871c8 ThaliTest`js_fun_apply(JSContext*, unsigned int, JS::Value*) + 612
    frame #23: 0x001ed2ae ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 230
    frame #24: 0x001ea82e ThaliTest`___lldb_unnamed_function930$$ThaliTest + 17614
    frame #25: 0x001e6346 ThaliTest`js::RunScript(JSContext*, js::RunState&) + 154
    frame #26: 0x001ed34c ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 388
    frame #27: 0x00186e94 ThaliTest`js_fun_call(JSContext*, unsigned int, JS::Value*) + 160
    frame #28: 0x001ed2ae ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 230
    frame #29: 0x001ea82e ThaliTest`___lldb_unnamed_function930$$ThaliTest + 17614
    frame #30: 0x001e6346 ThaliTest`js::RunScript(JSContext*, js::RunState&) + 154
    frame #31: 0x001ed34c ThaliTest`js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct) + 388
    frame #32: 0x001ed55c ThaliTest`js::Invoke(JSContext*, JS::Value const&, JS::Value const&, unsigned int, JS::Value const*, JS::MutableHandle<JS::Value>) + 272
    frame #33: 0x0016f1e0 ThaliTest`JS_CallFunctionValue(JSContext*, JS::Handle<JSObject*>, JS::Handle<JS::Value>, JS::HandleValueArray const&, JS::MutableHandle<JS::Value>) + 64
    frame #34: 0x000c9484 ThaliTest`MozJS::Value::Call(MozJS::Value const&, int, MozJS::Value*) const + 220
    frame #35: 0x000ad1b6 ThaliTest`jxcore::JXFunctionWrapper::Call(int, MozJS::Value*, bool*) + 130
    frame #36: 0x000ac936 ThaliTest`JX_CallFunction + 434
    frame #37: 0x000287b8 ThaliTest`+[JXcore callDirectMethod:withParams:isJSON:] + 2096
    frame #38: 0x00027814 ThaliTest`+[JXcore callEventCallbackNoThread:withParams:isJSON:] + 452
    frame #39: 0x00028cc2 ThaliTest`__46+[JXcore callEventCallback:withParams:isJSON:]_block_invoke + 634
    frame #40: 0x000270c4 ThaliTest`+[JXcore threadMain] + 716
    frame #41: 0x2559036c Foundation`<redacted> + 1144
    frame #42: 0x36b72c7e libsystem_pthread.dylib`<redacted> + 138
    frame #43: 0x36b72bf2 libsystem_pthread.dylib`_pthread_start + 110
    frame #44: 0x36b70a08 libsystem_pthread.dylib`thread_start + 8

```
