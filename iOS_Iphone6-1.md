#### Test 5797209499148df_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5797209499148df/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/DAB8203B-0A75-4065-8E1D-5E80AFAE56F2/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/DAB8203B-0A75-4065-8E1D-5E80AFAE56F2/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5797209499148df/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5797209499148df/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/68E9418B-31F2-4257-B2D2-2FBE9B9819A0/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64258"
,(lldb)     command script import "/tmp/DAB8203B-0A75-4065-8E1D-5E80AFAE56F2/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-02 13:34:21.097 ThaliTest[984:1871361] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A3C80639-BF28-420E-AF7A-320E8D4A243C/Library/Cookies/Cookies.binarycookies
,2016-02-02 13:34:21.446 ThaliTest[984:1871361] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-02 13:34:21.447 ThaliTest[984:1871361] Multi-tasking -> Device: YES, App: YES
,2016-02-02 13:34:21.457 ThaliTest[984:1871361] Unlimited access to network resources
,2016-02-02 13:34:21.466 ThaliTest[984:1871361] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-02 13:34:30.529 ThaliTest[984:1871361] Resetting plugins due to page load.
,2016-02-02 13:34:33.731 ThaliTest[984:1871361] Finished load of: file:///var/mobile/Containers/Bundle/Application/68E9418B-31F2-4257-B2D2-2FBE9B9819A0/ThaliTest.app/www/index.html
,2016-02-02 13:34:33.912 ThaliTest[984:1871361] JXcore Cordova plugin initializing
2016-02-02 13:34:33.913 ThaliTest[984:1871557] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/68E9418B-31F2-4257-B2D2-2FBE9B9819A0/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/68E9418B-31F2-4257-B2D2-2FBE9B9819A0/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/68E9418B-31F2-4257-B2D2-2FBE9B9819A0/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/68E9418B-31F2-4257-B2D2-2FBE9B9819A0/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/68E9418B-31F2-4257-B2D2-2FBE9B9819A0/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/68E9418B-31F2-4257-B2D2-2FBE9B9819A0/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/68E9418B-31F2-4257-B2D2-2FBE9B9819A0/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/68E9418B-31F2-4257-B2D2-2FBE9B9819A0/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

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

,# setup

,# successfully read a previous pkcs12 file and return hash value

,# teardown

,ok 18 (unnamed assert)

,ok 19 (unnamed assert)

,ok 20 should not throw

,ok 21 should be equal

,ok 22 should be equal

,# setup

,# failed to extract public key because of corrupt pkcs12 file
,
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

,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

,# teardown

,2016-02-02 13:39:29.272 ThaliTest[984:1871557] jxcore: startBroadcasting
,2016-02-02 13:39:29.287 ThaliTest[984:1871557] server: starting 1454416769271.984.KI5LdQ==
,2016-02-02 13:39:29.288 ThaliTest[984:1871557] multipeer session: start timer: 0x14ed0f80
2016-02-02 13:39:29.289 ThaliTest[984:1871557] THEMultipeerSession initialized peer 1454416769271.984
2016-02-02 13:39:29.290 ThaliTest[984:1871557] jxcore: startBroadcasting: success
,ok 54 Should be able to call startBroadcasting without error

2016-02-02 13:39:29.294 ThaliTest[984:1871557] jxcore: stopBroadcasting
2016-02-02 13:39:29.295 ThaliTest[984:1871557] THEMultipeerSession stopping peer
2016-02-02 13:39:29.295 ThaliTest[984,:1871557] multipeer session: stop timer
2016-02-02 13:39:29.295 ThaliTest[984:1871557] jxcore: stopBroadcasting: success
ok 55 Should be able to call stopBroadcasting without error

,2016-02-02 13:39:29.298 ThaliTest[984:1871557] jxcore: startBroadcasting
,2016-02-02 13:39:29.304 ThaliTest[984:1871557] server: starting 1454416769297.984.ESvTJQ==
,2016-02-02 13:39:29.313 ThaliTest[984:1871557] multipeer session: start timer: 0x14e8e840
2016-02-02 13:39:29.313 ThaliTest[984:1871557] THEMultipeerSession initialized peer 1454416769297.984
2016-02-02 13:39:29.314 ThaliTest[984:1871557] jxcore: startBr,oadcasting: success
ok 56 Should be able to call startBroadcasting without error

2016-02-02 13:39:29.315 ThaliTest[984:1871557] jxcore: stopBroadcasting
2016-02-02 13:39:29.316 ThaliTest[984:1871557] THEMultipeerSession stopping peer
2016-02-02 13:39,:29.316 ThaliTest[984:1871557] multipeer session: stop timer
,2016-02-02 13:39:29.317 ThaliTest[984:1871557] jxcore: stopBroadcasting: success
ok 57 Should be able to call stopBroadcasting without error

2016-02-02 13:39:29.322 ThaliTest[984:1871557] jxcore: startBroadcasting
,2016-02-02 13:39:29.328 ThaliTest[984:1871557] server: starting 1454416769322.984.zfkc1Q==
2016-02-02 13:39:29.329 ThaliTest[984:1871557] multipeer session: start timer: 0x16694570
,2016-02-02 13:39:29.330 ThaliTest[984:1871557] THEMultipeerSession initialized peer 1454416769322.984
2016-02-02 13:39:29.335 ThaliTest[984:1871557] jxcore: startBroadcasting: success
ok 58 Should be able to call startBroadcasting without error

2016-0,2-02 13:39:29.337 ThaliTest[984:1871557] jxcore: stopBroadcasting
2016-02-02 13:39:29.337 ThaliTest[984:1871557] THEMultipeerSession stopping peer
2016-02-02 13:39:29.337 ThaliTest[984:1871557] multipeer session: stop timer
2016-02-02 13:39:29.337 Thali,Test[984:1871557] jxcore: stopBroadcasting: success
ok 59 Should be able to call stopBroadcasting without error

2016-02-02 13:39:29.339 ThaliTest[984:1871557] jxcore: startBroadcasting
,2016-02-02 13:39:29.352 ThaliTest[984:1871557] server: starting 1454416769339.984.5M3o4A==
2016-02-02 13:39:29.353 ThaliTest[984:1871557] multipeer session: start timer: 0x16695f10
2016-02-02 13:39:29.354 ThaliTest[984:1871557] THEMultipeerSession initia,lized peer 1454416769339.984
2016-02-02 13:39:29.354 ThaliTest[984:1871557] jxcore: startBroadcasting: success
ok 60 Should be able to call startBroadcasting without error

2016-02-02 13:39:29.356 ThaliTest[984:1871557] jxcore: stopBroadcasting
2016-0,2-02 13:39:29.356 ThaliTest[984:1871557] THEMultipeerSession stopping peer
,2016-02-02 13:39:29.357 ThaliTest[984:1871557] multipeer session: stop timer
2016-02-02 13:39:29.359 ThaliTest[984:1871557] jxcore: stopBroadcasting: success
ok 61 Should be able to call stopBroadcasting without error

,2016-02-02 13:39:29.362 ThaliTest[984:1871557] jxcore: startBroadcasting
,2016-02-02 13:39:29.370 ThaliTest[984:1871557] server: starting 1454416769361.984.HPygpw==
2016-02-02 13:39:29.371 ThaliTest[984:1871557] multipeer session: start timer: 0x166765a0
2016-02-02 13:39:29.371 ThaliTest[984:1871557] THEMultipeerSession initialized peer 1454416769361.984
,2016-02-02 13:39:29.372 ThaliTest[984:1871557] jxcore: startBroadcasting: success
ok 62 Should be able to call startBroadcasting without error

,2016-02-02 13:39:29.376 ThaliTest[984:1871557] jxcore: stopBroadcasting
,2016-02-02 13:39:29.377 ThaliTest[984:1871557] THEMultipeerSession stopping peer
,2016-02-02 13:39:29.377 ThaliTest[984:1871557] multipeer session: stop timer
,2016-02-02 13:39:29.378 ThaliTest[984:1871557] jxcore: stopBroadcasting: success
ok 63 Should be able to call stopBroadcasting without error

2016-02-02 13:39:29.379 ThaliTest[984:1871557] jxcore: startBroadcasting
2016-02-02 13:39:29.384 ThaliTest[984,:1871557] server: starting 1454416769379.984.Bg9+rw==
2016-02-02 13:39:29.384 ThaliTest[984:1871557] multipeer session: start timer: 0x166974a0
2016-02-02 13:39:29.385 ThaliTest[984:1871557] THEMultipeerSession initialized peer 1454416769379.984
2016-02,-02 13:39:29.385 ThaliTest[984:1871557] jxcore: startBroadcasting: success
ok 64 Should be able to call startBroadcasting without error

2016-02-02 13:39:29.386 ThaliTest[984:1871557] jxcore: stopBroadcasting
2016-02-02 13:39:29.386 ThaliTest[984:18715,57] THEMultipeerSession stopping peer
2016-02-02 13:39:29.386 ThaliTest[984:1871557] multipeer session: stop timer
2016-02-02 13:39:29.387 ThaliTest[984:1871557] jxcore: stopBroadcasting: success
ok 65 Should be able to call stopBroadcasting without err,or

2016-02-02 13:39:29.393 ThaliTest[984:1871557] jxcore: startBroadcasting
,2016-02-02 13:39:29.399 ThaliTest[984:1871557] server: starting 1454416769392.984.crOwgQ==
2016-02-02 13:39:29.400 ThaliTest[984:1871557] multipeer session: start timer: 0x166954c0
2016-02-02 13:39:29.400 ThaliTest[984:1871557] THEMultipeerSession initia,lized peer 1454416769392.984
2016-02-02 13:39:29.401 ThaliTest[984:1871557] jxcore: startBroadcasting: success
ok 66 Should be able to call startBroadcasting without error

2016-02-02 13:39:29.402 ThaliTest[984:1871557] jxcore: stopBroadcasting
,2016-02-02 13:39:29.402 ThaliTest[984:1871557] THEMultipeerSession stopping peer
2016-02-02 13:39:29.405 ThaliTest[984:1871557] multipeer session: stop timer
2016-02-02 13:39:29.406 ThaliTest[984:1871557] jxcore: stopBroadcasting: success
ok 67 Should b,e able to call stopBroadcasting without error

2016-02-02 13:39:29.407 ThaliTest[984:1871557] jxcore: startBroadcasting
,2016-02-02 13:39:29.418 ThaliTest[984:1871557] server: starting 1454416769407.984.k5dEXw==
,2016-02-02 13:39:29.420 ThaliTest[984:1871557] multipeer session: start timer: 0x16697570
,2016-02-02 13:39:29.422 ThaliTest[984:1871557] THEMultipeerSession initialized peer 1454416769407.984
,2016-02-02 13:39:29.425 ThaliTest[984:1871557] jxcore: startBroadcasting: success
,ok 68 Should be able to call startBroadcasting without error

,2016-02-02 13:39:29.429 ThaliTest[984:1871557] jxcore: stopBroadcasting
,2016-02-02 13:39:29.430 ThaliTest[984:1871557] THEMultipeerSession stopping peer
,2016-02-02 13:39:29.431 ThaliTest[984:1871557] multipeer session: stop timer
,2016-02-02 13:39:29.432 ThaliTest[984:1871557] jxcore: stopBroadcasting: success
,ok 69 Should be able to call stopBroadcasting without error
,
,2016-02-02 13:39:29.437 ThaliTest[984:1871557] jxcore: startBroadcasting
,2016-02-02 13:39:29.439 ThaliTest[984:1871557] server: starting 1454416769436.984.MEXmyw==
,2016-02-02 13:39:29.442 ThaliTest[984:1871557] multipeer session: start timer: 0x166957a0
,2016-02-02 13:39:29.444 ThaliTest[984:1871557] THEMultipeerSession initialized peer 1454416769436.984
,2016-02-02 13:39:29.447 ThaliTest[984:1871557] jxcore: startBroadcasting: success
,ok 70 Should be able to call startBroadcasting without error

,2016-02-02 13:39:29.450 ThaliTest[984:1871557] jxcore: stopBroadcasting
,2016-02-02 13:39:29.450 ThaliTest[984:1871557] THEMultipeerSession stopping peer
,2016-02-02 13:39:29.451 ThaliTest[984:1871557] multipeer session: stop timer
,2016-02-02 13:39:29.453 ThaliTest[984:1871557] jxcore: stopBroadcasting: success
,ok 71 Should be able to call stopBroadcasting without error

,2016-02-02 13:39:29.457 ThaliTest[984:1871557] jxcore: startBroadcasting
,2016-02-02 13:39:29.460 ThaliTest[984:1871557] server: starting 1454416769457.984.eU+Bvw==
,2016-02-02 13:39:29.461 ThaliTest[984:1871557] multipeer session: start timer: 0x16694b00
,2016-02-02 13:39:29.465 ThaliTest[984:1871557] THEMultipeerSession initialized peer 1454416769457.984
,2016-02-02 13:39:29.466 ThaliTest[984:1871557] jxcore: startBroadcasting: success
,ok 72 Should be able to call startBroadcasting without error
,
,2016-02-02 13:39:29.470 ThaliTest[984:1871557] jxcore: stopBroadcasting
,2016-02-02 13:39:29.470 ThaliTest[984:1871557] THEMultipeerSession stopping peer
,2016-02-02 13:39:29.471 ThaliTest[984:1871557] multipeer session: stop timer
,2016-02-02 13:39:29.472 ThaliTest[984:1871557] jxcore: stopBroadcasting: success
,ok 73 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,# teardown

,2016-02-02 13:39:29.658 ThaliTest[984:1871557] jxcore: startBroadcasting
,2016-02-02 13:39:29.662 ThaliTest[984:1871557] server: starting 1454416769657.984.agD54Q==
,2016-02-02 13:39:29.665 ThaliTest[984:1871557] multipeer session: start timer: 0x16696f60
,2016-02-02 13:39:29.670 ThaliTest[984:1871557] THEMultipeerSession initialized peer 1454416769657.984
,2016-02-02 13:39:29.673 ThaliTest[984:1871557] jxcore: startBroadcasting: success
,ok 74 Should be able to call startBroadcasting without error

,2016-02-02 13:39:29.678 ThaliTest[984:1871557] jxcore: startBroadcasting
,2016-02-02 13:39:29.680 ThaliTest[984:1871557] jxcore: startBroadcasting: failure
,ok 75 Cannot call startBroadcasting twice

,2016-02-02 13:39:29.686 ThaliTest[984:1871557] jxcore: stopBroadcasting
,2016-02-02 13:39:29.688 ThaliTest[984:1871557] THEMultipeerSession stopping peer
,2016-02-02 13:39:29.689 ThaliTest[984:1871557] multipeer session: stop timer
,2016-02-02 13:39:29.691 ThaliTest[984:1871557] jxcore: stopBroadcasting: success
,ok 76 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on connection to bad peer

,# teardown

,2016-02-02 13:39:30.105 ThaliTest[984:1871557] jxcore: startBroadcasting
,2016-02-02 13:39:30.108 ThaliTest[984:1871557] server: starting 1454416770104.984.sVBLdg==
2016-02-02 13:39:30.109 ThaliTest[984:1871557] multipeer session: start timer: 0x1610b6b0
2016-02-02 13:39:30.109 ThaliTest[984:1871557] THEMultipeerSession initia,lized peer 1454416770104.984
2016-02-02 13:39:30.110 ThaliTest[984:1871557] jxcore: startBroadcasting: success
ok 77 Should be able to call startBroadcasting without error

2016-02-02 13:39:30.112 ThaliTest[984:1871557] jxcore: connect foobar
2016-02-,02 13:39:30.113 ThaliTest[984:1871557] client: unknown peer foobar
2016-02-02 13:39:30.113 ThaliTest[984:1871557] jxcore: connect: fail: Unknown peer
,ok 78 Should not connect to a bad peer

,2016-02-02 13:39:30.119 ThaliTest[984:1871557] jxcore: stopBroadcasting
2016-02-02 13:39:30.120 ThaliTest[984:1871557] THEMultipeerSession stopping peer
2016-02-02 13:39:30.121 ThaliTest[984:1871557] multipeer session: stop timer
2016-02-02 13:39:30.121 ThaliTest[984:1871557] jxcore: stopBroadcasting: success
,ok 79 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on disconnect to bad peer

,# teardown

,2016-02-02 13:39:30.261 ThaliTest[984:1871557] jxcore: startBroadcasting
,2016-02-02 13:39:30.265 ThaliTest[984:1871557] server: starting 1454416770261.984./HTSDw==
2016-02-02 13:39:30.266 ThaliTest[984:1871557] multipeer session: start timer: 0x173f85a0
2016-02-02 13:39:30.266 ThaliTest[984:1871557] THEMultipeerSession initia,lized peer 1454416770261.984
2016-02-02 13:39:30.267 ThaliTest[984:1871557] jxcore: startBroadcasting: success
ok 80 Should be able to call startBroadcasting without error

,2016-02-02 13:39:30.269 ThaliTest[984:1871557] jxcore: disconnect
2016-02-02 13:39:30.272 ThaliTest[984:1871557] jxcore: disconnect: fail
,ok 81 Disconnect should fail to a non-existant peer 

2016-02-02 13:39:30.277 ThaliTest[984:1871557] jxcore: stopBroadcasting
2016-02-02 13:39:30.277 ThaliTest[984:1871557] THEMultipeerSession stopping peer
2016-02-02 13:39:30.277 ThaliTest[984:1871557,] multipeer session: stop timer
2016-02-02 13:39:30.278 ThaliTest[984:1871557] jxcore: stopBroadcasting: success
ok 82 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter can discover and connect to peers

,# teardown

,2016-02-02 13:39:30.746 ThaliTest[984:1871557] jxcore: startBroadcasting
,2016-02-02 13:39:30.750 ThaliTest[984:1871557] server: starting 1454416770746.984.XGC5BA==
2016-02-02 13:39:30.750 ThaliTest[984:1871557] multipeer session: start timer: 0x161cc0f0
2016-02-02 13:39:30.751 ThaliTest[984:1871557] THEMultipeerSession initia,lized peer 1454416770746.984
2016-02-02 13:39:30.751 ThaliTest[984:1871557] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error

,2016-02-02 13:39:31.965 ThaliTest[984:1871361] client: found peer: 1454416770863.438.fiXOiw==
,2016-02-02 13:39:31.970 ThaliTest[984:1871557] jxcore: connect 1454416770863.438.fiXOiw==
2016-02-02 13:39:31.970 ThaliTest[984:1871557] client session: connect
2016-02-02 13:39:31.971 ThaliTest[984:1871557] client session: stateChange:0->1 1454416770863,.438.fiXOiw==
,2016-02-02 13:39:31.981 ThaliTest[984:1871361] multipeer session: reset timer
2016-02-02 13:39:31.981 ThaliTest[984:1871361] multipeer session: stop timer
2016-02-02 13:39:31.981 ThaliTest[984:1871361] multipeer session: start timer: 0x161cc0f0
2016-02-,02 13:39:31.982 ThaliTest[984:1871361] server session: connect
2016-02-02 13:39:31.982 ThaliTest[984:1871361] server session: stateChange:0->1 1454416770863.438
,2016-02-02 13:39:31.994 ThaliTest[984:1871361] server: accepting invitation 1454416770863.438
,2016-02-02 13:39:34.896 ThaliTest[984:1872105] server session: connected
,2016-02-02 13:39:34.896 ThaliTest[984:1872105] server session: stateChange:1->2 1454416770863.438
,2016-02-02 13:39:34.909 ThaliTest[984:1871361] server relay: socket disconnected
,2016-02-02 13:39:34.910 ThaliTest[984:1871361] server relay: 0x173c61a0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection r,efused} 
,2016-02-02 13:39:35.115 ThaliTest[984:1872107] client session: connected
2016-02-02 13:39:35.115 ThaliTest[984:1872107] client session: stateChange:1->2 1454416770863.438.fiXOiw==
,2016-02-02 13:39:35.747 ThaliTest[984:1872111] client session: fireConnectCallback: 1454416770863.438.fiXOiw==
2016-02-02 13:39:35.748 ThaliTest[984:1872111] jxcore: connect: success
,ok 84 Should be able to connect without error

,ok 85 Port should be within range

,2016-02-02 13:39:35.753 ThaliTest[984:1871557] jxcore: disconnect
2016-02-02 13:39:35.753 ThaliTest[984:1871557] client session: disconnectFromPeer: 1454416770863.438.fiXOiw==
2016-02-02 13:39:35.753 ThaliTest[984:1871557] client session: disconnect
201,6-02-02 13:39:35.754 ThaliTest[984:1871557] client session: stateChange:2->0 1454416770863.438.fiXOiw==
,2016-02-02 13:39:35.835 ThaliTest[984:1871557] jxcore: disconnect: success
ok 86 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-02-02 13:39:35.970 ThaliTest[984:1871557] jxcore: stopBroadcasting
2016-02-02 13:39:35.971 ThaliTest[984:1871557] THEMultipeerSession stopping peer
2016-02-02 13:39:35.971 ThaliTest[984:1871557] multipeer session: stop timer
2016-02-02 13:39:35.972, ThaliTest[984:1871557] server session: disconnect
2016-02-02 13:39:35.972 ThaliTest[984:1871557] server session: stateChange:2->0 1454416770863.438
,2016-02-02 13:39:36.005 ThaliTest[984:1871557] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double connect

,# teardown

,2016-02-02 13:39:36.496 ThaliTest[984:1871557] jxcore: startBroadcasting
,2016-02-02 13:39:36.499 ThaliTest[984:1871557] server: starting 1454416776495.984.6FCF9Q==
2016-02-02 13:39:36.500 ThaliTest[984:1871557] multipeer session: start timer: 0x161d0e60
2016-02-02 13:39:36.501 ThaliTest[984:1871557] THEMultipeerSession initia,lized peer 1454416776495.984
2016-02-02 13:39:36.501 ThaliTest[984:1871557] jxcore: startBroadcasting: success
ok 87 Should be able to call startBroadcasting without error

,2016-02-02 13:39:37.740 ThaliTest[984:1871361] multipeer session: reset timer
2016-02-02 13:39:37.740 ThaliTest[984:1871361] multipeer session: stop timer
2016-02-02 13:39:37.740 ThaliTest[984:1871361] multipeer session: start timer: 0x161d0e60
2016-02-,02 13:39:37.741 ThaliTest[984:1871361] server session: connect
2016-02-02 13:39:37.741 ThaliTest[984:1871361] server session: stateChange:0->1 1454416776581.438
,2016-02-02 13:39:37.752 ThaliTest[984:1871361] server: accepting invitation 1454416776581.438
,2016-02-02 13:39:38.011 ThaliTest[984:1871361] client: found peer: 1454416776581.438.ftA4DQ==
2016-02-02 13:39:38.013 ThaliTest[984:1871557] jxcore: connect 1454416776581.438.ftA4DQ==
2016-02-02 13:39:38.013 ThaliTest[984:1871557] client session: connect
2016-02-02 13:39:38.013 ThaliTest[984:1871557] client session: stateChange:0->1 1454416776581.438.ftA4DQ==
,2016-02-02 13:39:40.758 ThaliTest[984:1872113] server session: connected
,2016-02-02 13:39:40.758 ThaliTest[984:1872113] server session: stateChange:1->2 1454416776581.438
,2016-02-02 13:39:40.780 ThaliTest[984:1871361] server relay: socket disconnected
,2016-02-02 13:39:40.780 ThaliTest[984:1871361] server relay: 0x17258710 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-02 13:39:40.894 ThaliTest[984:1872105] server session: not connected 1454416776581.438
,2016-02-02 13:39:41.062 ThaliTest[984:1872113] client session: connected
2016-02-02 13:39:41.062 ThaliTest[984:1872113] client session: stateChange:1->2 1454416776581.438.ftA4DQ==
,2016-02-02 13:39:41.073 ThaliTest[984:1872105] client session: fireConnectCallback: 1454416776581.438.ftA4DQ==
2016-02-02 13:39:41.074 ThaliTest[984:1872105] jxcore: connect: success
,ok 88 Should be able to connect without error

,ok 89 Port should be within range

,2016-02-02 13:39:41.076 ThaliTest[984:1871557] jxcore: connect 1454416776581.438.ftA4DQ==
2016-02-02 13:39:41.077 ThaliTest[984:1871557] client: already connect(ing/ed) to 1454416776581.438.ftA4DQ==
2016-02-02 13:39:41.077 ThaliTest[984:1871557] jxcore: connect: fail: Aleady connecting
,ok 90 Should fail on double connect

,2016-02-02 13:39:41.079 ThaliTest[984:1871557] jxcore: disconnect
2016-02-02 13:39:41.079 ThaliTest[984:1871557] client session: disconnectFromPeer: 1454416776581.438.ftA4DQ==
2016-02-02 13:39:41.079 ThaliTest[984:1871557] client session: disconnect
201,6-02-02 13:39:41.079 ThaliTest[984:1871557] client session: stateChange:2->0 1454416776581.438.ftA4DQ==
,2016-02-02 13:39:41.147 ThaliTest[984:1871557] jxcore: disconnect: success
ok 91 Should be able to disconnect without error

,setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-02-02 13:39:41.205 ThaliTest[984:1871557] jxcore: stopBroadcasting
2016-02-02 13:39:41.205 ThaliTest[984:1871557] THEMultipeerSession stopping peer
2016-02-02 13:39:41.205 ThaliTest[984:1871557] multipeer session: stop timer
2016-02-02 13:39:41.206, ThaliTest[984:1871557] server session: disconnect
2016-02-02 13:39:41.206 ThaliTest[984:1871557] server session: stateChange:2->0 1454416776581.438
,2016-02-02 13:39:41.207 ThaliTest[984:1871557] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,# teardown

,2016-02-02 13:39:41.285 ThaliTest[984:1871557] jxcore: startBroadcasting
,2016-02-02 13:39:41.288 ThaliTest[984:1871557] server: starting 1454416781285.984.9EmuGw==
2016-02-02 13:39:41.288 ThaliTest[984:1871557] multipeer session: start timer: 0x173a4f10
2016-02-02 13:39:41.289 ThaliTest[984:1871557] THEMultipeerSession initia,lized peer 1454416781285.984
2016-02-02 13:39:41.289 ThaliTest[984:1871557] jxcore: startBroadcasting: success
ok 92 Should be able to call startBroadcasting without error

,2016-02-02 13:39:42.184 ThaliTest[984:1871361] client: found peer: 1454416776495.984.6FCF9Q==
2016-02-02 13:39:42.184 ThaliTest[984:1871361] client: found peer: 1454416776581.438.ftA4DQ==
,2016-02-02 13:39:42.186 ThaliTest[984:1871557] jxcore: connect 1454416776495.984.6FCF9Q==
2016-02-02 13:39:42.187 ThaliTest[984:1871557] client session: connect
2016-02-02 13:39:42.188 ThaliTest[984:1871557] client session: stateChange:0->1 1454416776495.984.6FCF9Q==
,2016-02-02 13:39:42.202 ThaliTest[984:1871557] jxcore: connect 1454416776581.438.ftA4DQ==
2016-02-02 13:39:42.202 ThaliTest[984:1871557] client session: connect
2016-02-02 13:39:42.202 ThaliTest[984:1871557] client session: stateChange:0->1 1454416776581.438.ftA4DQ==
,2016-02-02 13:39:42.506 ThaliTest[984:1871361] client: lost peer: 1454416776495.984.6FCF9Q==
2016-02-02 13:39:42.506 ThaliTest[984:1871361] client session: onPeerLost: 1454416776495.984.6FCF9Q==
2016-02-02 13:39:42.506 ThaliTest[984:1871361] client sessi,on: onLinkFailure: 1454416776495.984.6FCF9Q==
2016-02-02 13:39:42.506 ThaliTest[984:1871361] client session: disconnect
2016-02-02 13:39:42.507 ThaliTest[984:1871361] client session: stateChange:1->0 1454416776495.984.6FCF9Q==
2016-02-02 13:39:42.507 Th,aliTest[984:1871361] client session: fireConnectCallback: 1454416776495.984.6FCF9Q==
2016-02-02 13:39:42.507 ThaliTest[984:1871361] jxcore: connect: fail: Peer disconnected
2016-02-02 13:39:42.508 ThaliTest[984:1871361] client: lost peer: 1454416776581.4,38.ftA4DQ==
2016-02-02 13:39:42.508 ThaliTest[984:1871361] client session: onPeerLost: 1454416776581.438.ftA4DQ==
2016-02-02 13:39:42.508 ThaliTest[984:1871361] client session: onLinkFailure: 1454416776581.438.ftA4DQ==
2016-02-02 13:39:42.509 ThaliTest[,984:1871361] client session: disconnect
2016-02-02 13:39:42.511 ThaliTest[984:1871361] client session: stateChange:1->0 1454416776581.438.ftA4DQ==
2016-02-02 13:39:42.512 ThaliTest[984:1871361] client session: fireConnectCallback: 1454416776581.438.ftA4D,Q==
2016-02-02 13:39:42.512 ThaliTest[984:1871361] jxcore: connect: fail: Peer disconnected
2016-02-02 13:39:42.513 ThaliTest[984:1871361] client: found peer: 1454416781380.438.KHAk0w==
,2016-02-02 13:39:42.515 ThaliTest[984:1871557] jxcore: connect 1454416781380.438.KHAk0w==
2016-02-02 13:39:42.516 ThaliTest[984:1871557] client session: connect
2016-02-02 13:39:42.516 ThaliTest[984:1871557] client session: stateChange:0->1 1454416781380.438.KHAk0w==
,2016-02-02 13:39:42.836 ThaliTest[984:1871361] multipeer session: reset timer
,2016-02-02 13:39:42.837 ThaliTest[984:1871361] multipeer session: stop timer
,2016-02-02 13:39:42.838 ThaliTest[984:1871361] multipeer session: start timer: 0x173a4f10
,2016-02-02 13:39:42.839 ThaliTest[984:1871361] server session: connect
2016-02-02 13:39:42.840 ThaliTest[984:1871361] server session: stateChange:0->1 1454416781380.438
,2016-02-02 13:39:42.848 ThaliTest[984:1871361] server: accepting invitation 1454416781380.438
,2016-02-02 13:39:43.515 ThaliTest[984:1871557] jxcore: connect 1454416776495.984.6FCF9Q==
2016-02-02 13:39:43.515 ThaliTest[984:1871557] client: connect: unreachable 1454416776495.984.6FCF9Q==
2016-02-02 13:39:43.515 ThaliTest[984:1871557] jxcore: connect: fail: Peer unreachable
2016-02-02 13:39:43.517 ThaliTest[984:1871557] jxcore: connect 1454416776581.438.ftA4DQ==
2016-02-02 13:39:43.517 ThaliTest[984:1871557] client: connect: unreachable 1454416776581.438.ftA4DQ==
2016-02-02 13:39:43.517 ThaliTest[984:1871557] jxcore: connect: fail: Peer unreachable
,2016-02-02 13:39:45.737 ThaliTest[984:1872105] server session: connected
2016-02-02 13:39:45.737 ThaliTest[984:1872105] server session: stateChange:1->2 1454416781380.438
,2016-02-02 13:39:45.745 ThaliTest[984:1871361] server relay: socket disconnected
,2016-02-02 13:39:45.745 ThaliTest[984:1871361] server relay: 0x1728f170 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection r,efused} 
,2016-02-02 13:39:45.787 ThaliTest[984:1872109] server session: not connected 1454416781380.438
,2016-02-02 13:39:45.870 ThaliTest[984:1872113] client session: connected
2016-02-02 13:39:45.872 ThaliTest[984:1872113] client session: stateChange:1->2 1454416781380.438.KHAk0w==
,2016-02-02 13:39:45.876 ThaliTest[984:1872113] client session: fireConnectCallback: 1454416781380.438.KHAk0w==
2016-02-02 13:39:45.876 ThaliTest[984:1872113] jxcore: connect: success
ok 93 Should be able to connect without error

ok 94 Port should be within range

,2016-02-02 13:39:45.881 ThaliTest[984:1871557] jxcore: disconnect
,2016-02-02 13:39:45.881 ThaliTest[984:1871557] client session: disconnectFromPeer: 1454416781380.438.KHAk0w==
2016-02-02 13:39:45.882 ThaliTest[984:1871557] client session: disconnect
2016-02-02 13:39:45.883 ThaliTest[984:1871557] client session: stateChange:2->0 1454416781380.438.KHAk0w==
,2016-02-02 13:39:45.965 ThaliTest[984:1871557] jxcore: disconnect: success
ok 95 Should be able to disconnect without error

,2016-02-02 13:39:45.968 ThaliTest[984:1871557] jxcore: disconnect
2016-02-02 13:39:45.969 ThaliTest[984:1871557] jxcore: disconnect: fail
,ok 96 Disconnect should fail 

,setting stopBroadcasting callback and ending test.

,calling stopBroadcasting

,2016-02-02 13:39:45.993 ThaliTest[984:1871557] jxcore: stopBroadcasting
2016-02-02 13:39:45.994 ThaliTest[984:1871557] THEMultipeerSession stopping peer
2016-02-02 13:39:45.994 ThaliTest[984:1871557] multipeer session: stop timer
2016-02-02 13:39:45.995, ThaliTest[984:1871557] server session: disconnect
2016-02-02 13:39:45.995 ThaliTest[984:1871557] server session: stateChange:2->0 1454416781380.438
2016-02-02 13:39:45.996 ThaliTest[984:1871557] jxcore: stopBroadcasting: success
stopBroadcasting return,ed undefined

# setup

,# ThaliEmitter can connect and send data

,# teardown

,echo server started on port: 54628

,2016-02-02 13:39:47.029 ThaliTest[984:1871557] jxcore: startBroadcasting
,2016-02-02 13:39:47.030 ThaliTest[984:1871557] server: starting 1454416787029.984.KTJFuA==
2016-02-02 13:39:47.031 ThaliTest[984:1871557] multipeer session: start timer: 0x17289cb0
2016-02-02 13:39:47.031 ThaliTest[984:1871557] THEMultipeerSession initialized peer 1454416787029.984
2016-02-02 13:39:47.031 ThaliTest[984:1871557] jxcore: startBroadcasting: success
ok 97 Should be able to call startBroadcasting without error

,2016-02-02 13:39:47.641 ThaliTest[984:1871361] client: found peer: 1454416781380.438.KHAk0w==
2016-02-02 13:39:47.642 ThaliTest[984:1871557] jxcore: connect 1454416781380.438.KHAk0w==
,2016-02-02 13:39:47.643 ThaliTest[984:1871557] client session: connect
2016-02-02 13:39:47.646 ThaliTest[984:1871557] client session: stateChange:0->1 1454416781380.438.KHAk0w==
,2016-02-02 13:39:47.797 ThaliTest[984:1871361] client: found peer: 1454416787054.438.1D88vQ==
2016-02-02 13:39:47.799 ThaliTest[984:1871557] jxcore: connect 1454416787054.438.1D88vQ==
2016-02-02 13:39:47.800 ThaliTest[984:1871557] client session: connect,
2016-02-02 13:39:47.800 ThaliTest[984:1871557] client session: stateChange:0->1 1454416787054.438.1D88vQ==
,2016-02-02 13:39:48.351 ThaliTest[984:1871361] multipeer session: reset timer
2016-02-02 13:39:48.351 ThaliTest[984:1871361] multipeer session: stop timer
2016-02-02 13:39:48.351 ThaliTest[984:1871361] multipeer session: start timer: 0x17289cb0
2016-02-,02 13:39:48.352 ThaliTest[984:1871361] server session: connect
2016-02-02 13:39:48.352 ThaliTest[984:1871361] server session: stateChange:0->1 1454416787054.438
,2016-02-02 13:39:48.362 ThaliTest[984:1871361] server: accepting invitation 1454416787054.438
,2016-02-02 13:39:53.800 ThaliTest[984:1872109] client session: connected
2016-02-02 13:39:53.800 ThaliTest[984:1872109] client session: stateChange:1->2 1454416787054.438.1D88vQ==
,2016-02-02 13:39:54.029 ThaliTest[984:1872110] client session: fireConnectCallback: 1454416787054.438.1D88vQ==
2016-02-02 13:39:54.032 ThaliTest[984:1872110] jxcore: connect: success
ok 98 Should be able to connect without error

ok 99 Port should be w,ithin range

2016-02-02 13:39:54.040 ThaliTest[984:1871361] client: relay established
2016-02-02 13:39:54.041 ThaliTest[984:1871361] client: new accepted socket: 0x1724f340
2016-02-02 13:39:54.034 ThaliTest[984:1872109] server session: connected
,2016-02-02 13:39:54.045 ThaliTest[984:1872109] server session: stateChange:1->2 1454416787054.438
,2016-02-02 13:39:54.052 ThaliTest[984:1871361] server relay: connected (to port: 54628)
,2016-02-02 13:40:00.022 ThaliTest[984:1871361] client: lost peer: 1454416781380.438.KHAk0w==
2016-02-02 13:40:00.022 ThaliTest[984:1871361] client session: onPeerLost: 1454416781380.438.KHAk0w==
,2016-02-02 13:40:00.024 ThaliTest[984:1871361] client session: onLinkFailure: 1454416781380.438.KHAk0w==
2016-02-02 13:40:00.024 ThaliTest[984:1871361] client session: disconnect
,2016-02-02 13:40:00.025 ThaliTest[984:1871361] client session: stateChange:1->0 1454416781380.438.KHAk0w==
,2016-02-02 13:40:00.026 ThaliTest[984:1871361] client session: fireConnectCallback: 1454416781380.438.KHAk0w==
2016-02-02 13:40:00.026 ThaliTest[984:1871361] jxcore: connect: fail: Peer disconnected
,2016-02-02 13:40:01.039 ThaliTest[984:1871557] jxcore: connect 1454416781380.438.KHAk0w==
2016-02-02 13:40:01.040 ThaliTest[984:1871557] client: connect: unreachable 1454416781380.438.KHAk0w==
2016-02-02 13:40:01.040 ThaliTest[984:1871557] jxcore: connect: fail: Peer unreachable
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

,data in 16425

,data in 17520

,data in 18615

,data in 19710

,data in 20805

,data in 21900

,data in 22995

,data in 24019

,data in 24090

,data in 25185

,data in 26280

,data in 27375

,data in 28470

,data in 29565

,data in 30660

,data in 31755

,data in 32850

,data in 33945

,data in 35040

,data in 36135

,2016-02-02 13:40:18.353 ThaliTest[984:1871361] multipeer session: restart
,2016-02-02 13:40:18.390 ThaliTest[984:1871361] client: found peer: 1454416787054.438.1D88vQ==
,data in 37230

,data in 53655

,data in 67890

,data in 72270

,data in 73365

,data in 74460

,data in 83220

,data in 84315

,data in 85410

,data in 86505

,data in 87600

,data in 88695

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

,2016-02-02 13:40:42.096 ThaliTest[984:1872105] server session: not connected 1454416787054.438
,data in 112785

,data in 113880

,data in 114975

,data in 116070

,data in 117165

,data in 117905

,data in 119000

,data in 120095

,data in 121190

,data in 122285

,data in 123380

,data in 124475

,data in 125570

,data in 127020

,data in 128115

,data in 129210

,data in 130305

,data in 131072

,ok 100 the test messages should be equal

,2016-02-02 13:40:43.040 ThaliTest[984:1871557] jxcore: disconnect
2016-02-02 13:40:43.040 ThaliTest[984:1871557] client session: disconnectFromPeer: 1454416787054.438.1D88vQ==
2016-02-02 13:40:43.041 ThaliTest[984:1871557] client session: disconnect
201,6-02-02 13:40:43.041 ThaliTest[984:1871557] client session: stateChange:2->0 1454416787054.438.1D88vQ==
,2016-02-02 13:40:43.050 ThaliTest[984:1871557] jxcore: disconnect: success
,ok 101 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.
,
,# setup

,calling stopBroadcasting

,2016-02-02 13:40:43.113 ThaliTest[984:1871557] jxcore: stopBroadcasting
,2016-02-02 13:40:43.114 ThaliTest[984:1871557] THEMultipeerSession stopping peer
,2016-02-02 13:40:43.116 ThaliTest[984:1871557] multipeer session: stop timer
,2016-02-02 13:40:43.120 ThaliTest[984:1871557] server session: disconnect
,2016-02-02 13:40:43.136 ThaliTest[984:1871557] server session: stateChange:2->0 1454416787054.438
,2016-02-02 13:40:43.206 ThaliTest[984:1871557] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter handles socket disconnect correctly

,# teardown

,echo server started on port: 54638

,2016-02-02 13:40:45.877 ThaliTest[984:1871557] jxcore: startBroadcasting
,2016-02-02 13:40:45.881 ThaliTest[984:1871557] server: starting 1454416845876.984./mImjQ==
2016-02-02 13:40:45.882 ThaliTest[984:1871557] multipeer session: start timer: 0x14dde5a0
2016-02-02 13:40:45.882 ThaliTest[984:1871557] THEMultipeerSession initia,lized peer 1454416845876.984
2016-02-02 13:40:45.882 ThaliTest[984:1871557] jxcore: startBroadcasting: success
ok 102 Should be able to call startBroadcasting without error

,2016-02-02 13:40:46.785 ThaliTest[984:1871361] client: found peer: 1454416787054.438.1D88vQ==
[{"peerIdentifier":"1454416787054.438.1D88vQ==","peerName":"(null)","peerAvailable":true}]

2016-02-02 13:40:46.787 ThaliTest[984:1871557] jxcore: connect 1454,416787054.438.1D88vQ==
2016-02-02 13:40:46.787 ThaliTest[984:1871557] client session: connect
2016-02-02 13:40:46.788 ThaliTest[984:1871557] client session: stateChange:0->1 1454416787054.438.1D88vQ==
,2016-02-02 13:40:47.257 ThaliTest[984:1871361] client: found peer: 1454416845964.438.JBsgHQ==
2016-02-02 13:40:47.257 ThaliTest[984:1871361] multipeer session: reset timer
2016-02-02 13:40:47.258 ThaliTest[984:1871361] multipeer session: stop timer
2016,-02-02 13:40:47.258 ThaliTest[984:1871361] multipeer session: start timer: 0x14dde5a0
2016-02-02 13:40:47.258 ThaliTest[984:1871361] server session: connect
2016-02-02 13:40:47.259 ThaliTest[984:1871361] server session: stateChange:0->1 1454416845964.438,
[{"peerIdentifier":"1454416845964.438.JBsgHQ==","peerName":"(null)","peerAvailable":true}]

2016-02-02 13:40:47.261 ThaliTest[984:1871557] jxcore: connect 1454416845964.438.JBsgHQ==
2016-02-02 13:40:47.261 ThaliTest[984:1871557] client session: connect
,2016-02-02 13:40:47.261 ThaliTest[984:1871557] client session: stateChange:0->1 1454416845964.438.JBsgHQ==
,2016-02-02 13:40:47.280 ThaliTest[984:1871361] server: accepting invitation 1454416845964.438
,2016-02-02 13:40:52.872 ThaliTest[984:1872113] server session: connected
2016-02-02 13:40:52.872 ThaliTest[984:1872113] server session: stateChange:1->2 1454416845964.438
,2016-02-02 13:40:52.878 ThaliTest[984:1871361] server relay: connected (to port: 54638)
,2016-02-02 13:40:52.894 ThaliTest[984:1872352] client session: connected
2016-02-02 13:40:52.895 ThaliTest[984:1872352] client session: stateChange:1->2 1454416845964.438.JBsgHQ==
,2016-02-02 13:40:52.921 ThaliTest[984:1872374] client session: fireConnectCallback: 1454416845964.438.JBsgHQ==
2016-02-02 13:40:52.921 ThaliTest[984:1872374] jxcore: connect: success
,ok 103 Should be able to connect without error

,ok 104 Port should be within range

ok 105 First connect should succeed

,2016-02-02 13:40:52.963 ThaliTest[984:1871361] client: relay established
2016-02-02 13:40:52.963 ThaliTest[984:1871361] client: new accepted socket: 0x1667fcb0
,2016-02-02 13:40:53.747 ThaliTest[984:1871361] multipeer session: reset timer
,2016-02-02 13:40:53.747 ThaliTest[984:1871361] multipeer session: stop timer
2016-02-02 13:40:53.748 ThaliTest[984:1871361] multipeer session: start timer: 0x14dde5a0
2016-02-02 13:40:53.748 ThaliTest[984:1871361] server: disconnecting to refresh session, (1454416845964.438)
2016-02-02 13:40:53.749 ThaliTest[984:1871361] server session: disconnect
,2016-02-02 13:40:53.749 ThaliTest[984:1871361] server session: stateChange:2->0 1454416845964.438
,2016-02-02 13:40:53.839 ThaliTest[984:1871361] server session: connect
,2016-02-02 13:40:53.840 ThaliTest[984:1871361] server session: stateChange:0->1 1454416845964.438
,2016-02-02 13:40:53.850 ThaliTest[984:1871361] server: accepting invitation 1454416845964.438
,ok 106 the test messages should be equal

,ok 107 First send should succeed

,2016-02-02 13:40:54.208 ThaliTest[984:1871361] client: socket closed
2016-02-02 13:40:54.209 ThaliTest[984:1871361] client relay: socket disconnected
2016-02-02 13:40:54.209 ThaliTest[984:1871361] client relay: 0x1667fcb0 disconnected with error Error Do,main=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-02-02 13:40:54.209 ThaliTest[984:1871361] client session: socket closed: 1454416845964.438.JBsgHQ==
2016-02-02 13:40,:54.209 ThaliTest[984:1871361] client session: onLinkFailure: 1454416845964.438.JBsgHQ==
2016-02-02 13:40:54.209 ThaliTest[984:1871361] client session: disconnect
2016-02-02 13:40:54.209 ThaliTest[984:1871361] client session: stateChange:2->0 14544168459,64.438.JBsgHQ==
,2016-02-02 13:40:54.215 ThaliTest[984:1871361] client session: fireConnectionErrorEvent: 1454416845964.438.JBsgHQ==
2016-02-02 13:40:54.217 ThaliTest[984:1871557] jxcore: connect 1454416845964.438.JBsgHQ==
,2016-02-02 13:40:54.217 ThaliTest[984:1871557] client session: connect
,2016-02-02 13:40:54.218 ThaliTest[984:1871557] client session: stateChange:0->1 1454416845964.438.JBsgHQ==
,2016-02-02 13:40:57.387 ThaliTest[984:1872352] client session: connected
2016-02-02 13:40:57.387 ThaliTest[984:1872352] client session: stateChange:1->2 1454416845964.438.JBsgHQ==
,2016-02-02 13:40:57.392 ThaliTest[984:1872352] client session: fireConnectCallback: 1454416845964.438.JBsgHQ==
2016-02-02 13:40:57.392 ThaliTest[984:1872352] jxcore: connect: success
ok 108 Should be able to connect without error

ok 109 Port should be within range

ok 110 Second connect should succeed

,2016-02-02 13:40:57.432 ThaliTest[984:1871361] client: relay established
2016-02-02 13:40:57.433 ThaliTest[984:1871361] client: new accepted socket: 0x171c45d0
,ok 111 the test messages should be equal

,ok 112 Second send should succeed
,
,# setup

,2016-02-02 13:40:57.500 ThaliTest[984:1871361] client: socket closed
,2016-02-02 13:40:57.500 ThaliTest[984:1871361] client relay: socket disconnected
2016-02-02 13:40:57.501 ThaliTest[984:1871361] client relay: 0x171c45d0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" U,serInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2016-02-02 13:40:57.501 ThaliTest[984:1871361] client session: socket closed: 1454416845964.438.JBsgHQ==
2016-02-02 13:40:57.501 ThaliTest[984:1871361] client session: onLinkFailure: 1454416845964.438.JBsgHQ==
2016-02-02 13:40:57.502 ThaliTest[984:1871361] client session: disconnect
,2016-02-02 13:40:57.502 ThaliTest[984:1871361] client session: stateChange:2->0 1454416845964.438.JBsgHQ==
,2016-02-02 13:40:57.518 ThaliTest[984:1871361] client session: fireConnectionErrorEvent: 1454416845964.438.JBsgHQ==
,2016-02-02 13:41:00.020 ThaliTest[984:1872113] server session: connected
2016-02-02 13:41:00.021 ThaliTest[984:1872113] server session: stateChange:1->2 1454416845964.438
,2016-02-02 13:41:00.128 ThaliTest[984:1871361] server relay: connected (to port: 54638)
,calling stopBroadcasting

,2016-02-02 13:41:02.819 ThaliTest[984:1871557] jxcore: stopBroadcasting
2016-02-02 13:41:02.819 ThaliTest[984:1871557] THEMultipeerSession stopping peer
2016-02-02 13:41:02.820 ThaliTest[984:1871557] multipeer session: stop timer
2016-02-02 13:41:02.820, ThaliTest[984:1871557] client session: disconnect
2016-02-02 13:41:02.820 ThaliTest[984:1871557] client session: stateChange:1->0 1454416787054.438.1D88vQ==
2016-02-02 13:41:02.821 ThaliTest[984:1871557] server session: disconnect
2016-02-02 13:41:02.8,21 ThaliTest[984:1871557] server session: stateChange:2->0 1454416845964.438
,2016-02-02 13:41:02.855 ThaliTest[984:1871557] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliReplicationManager can call start without error

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/A3C80639-BF28-420E-AF7A-320E8D4A243C/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,ok 113 starting event should occur in right order

,2016-02-02 13:41:04.020 ThaliTest[984:1871557] jxcore: startBroadcasting
,2016-02-02 13:41:04.022 ThaliTest[984:1871557] server: starting _vfrhYzGzfT5MBj9M0TDvQ.ULHExg==
2016-02-02 13:41:04.022 ThaliTest[984:1871557] multipeer session: start timer: 0x16643030
2016-02-02 13:41:04.022 ThaliTest[984:1871557] THEMultipeerSession i,nitialized peer _vfrhYzGzfT5MBj9M0TDvQ
2016-02-02 13:41:04.022 ThaliTest[984:1871557] jxcore: startBroadcasting: success
ok 114 started event should occur in right order

Now in TRM stop

State of this._isStarted: true

ok 115 stopping event should, occur in right order

About to call stopBroadcasting

2016-02-02 13:41:04.024 ThaliTest[984:1871557] jxcore: stopBroadcasting
2016-02-02 13:41:04.024 ThaliTest[984:1871557] THEMultipeerSession stopping peer
2016-02-02 13:41:04.024 ThaliTest[984:1871,557] multipeer session: stop timer
2016-02-02 13:41:04.024 ThaliTest[984:1871557] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

ok 116 stopped event should occur in right order

,mux server bridge listener closed

# setup

,# ThaliReplicationManager receives identity

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/A3C80639-BF28-420E-AF7A-320E8D4A243C/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-02-02 13:41:04.195 ThaliTest[984:1871557] jxcore: startBroadcasting
,2016-02-02 13:41:04.196 ThaliTest[984:1871557] server: starting _vfrhYzGzfT5MBj9M0TDvQ.gfLQiw==
2016-02-02 13:41:04.197 ThaliTest[984:1871557] multipeer session: start timer: 0x14ee8440
2016-02-02 13:41:04.197 ThaliTest[984:1871557] THEMultipeerSession initialized peer _vfrhYzGzfT5MBj9M0TDvQ
,2016-02-02 13:41:04.198 ThaliTest[984:1871557] jxcore: startBroadcasting: success
,ok 117 getDeviceIdentity should not return an error

,ok 118 deviceName should not be null

Now in TRM stop

,State of this._isStarted: true
,
About to call stopBroadcasting

,2016-02-02 13:41:04.200 ThaliTest[984:1871557] jxcore: stopBroadcasting
2016-02-02 13:41:04.201 ThaliTest[984:1871557] THEMultipeerSession stopping peer
2016-02-02 13:41:04.201 ThaliTest[984:1871557] multipeer session: stop timer
2016-02-02 13:41:04.201, ThaliTest[984:1871557] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

mux server bridge listener closed

# setup

,# ThaliReplicationManager replicates database

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/A3C80639-BF28-420E-AF7A-320E8D4A243C/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-02-02 13:41:06.824 ThaliTest[984:1871557] jxcore: startBroadcasting
,2016-02-02 13:41:06.826 ThaliTest[984:1871557] server: starting _vfrhYzGzfT5MBj9M0TDvQ.rYAIlg==
2016-02-02 13:41:06.826 ThaliTest[984:1871557] multipeer session: start timer: 0x1763a930
2016-02-02 13:41:06.826 ThaliTest[984:1871557] THEMultipeerSession initialized peer _vfrhYzGzfT5MBj9M0TDvQ
2016-02-02 13:41:06.826 ThaliTest[984:1871557] jxcore: startBroadcasting: success
ok 119 getDeviceIdentity should not return an error

ok 120 deviceName should not be null

,2016-02-02 13:41:07.826 ThaliTest[984:1871361] client: found peer: aCOtCSY3a8XpRhyjDFipHA.hbQPAA==
,2016-02-02 13:41:11.489 ThaliTest[984:1871361] multipeer session: reset timer
2016-02-02 13:41:11.488 ThaliTest[984:1871557] jxcore: connect aCOtCSY3a8XpRhyjDFipHA.hbQPAA==
2016-02-02 13:41:11.489 ThaliTest[984:1871361] multipeer session: stop timer
2016-02-02 13:41:11.489 ThaliTest[984:1871361] multipeer session: start timer: 0x1763a930
2016-02-02 13:41:11.489 ThaliTest[984:1871361] server session: connect
2016-02-02 13:41:11.489 ThaliTest[984:1871361] server session: stateChange:0->1 aCOtCSY3a8XpRhyjDFipHA
,2016-02-02 13:41:11.490 ThaliTest[984:1871557] client session: connect
,2016-02-02 13:41:11.494 ThaliTest[984:1871361] server: accepting invitation aCOtCSY3a8XpRhyjDFipHA
2016-02-02 13:41:11.493 ThaliTest[984:1871557] client session: stateChange:0->1 aCOtCSY3a8XpRhyjDFipHA.hbQPAA==
,ok 121 Should be able to put doc without error

,ok 122 1st change of local doc should contain local id

,2016-02-02 13:41:12.790 ThaliTest[984:1872374] server session: connected
2016-02-02 13:41:12.790 ThaliTest[984:1872374] server session: stateChange:1->2 aCOtCSY3a8XpRhyjDFipHA
,2016-02-02 13:41:13.060 ThaliTest[984:1871361] server relay: connected (to port: 54656)
,server bridge: new client socket

,2016-02-02 13:41:13.455 ThaliTest[984:1872113] client session: connected
2016-02-02 13:41:13.456 ThaliTest[984:1872113] client session: stateChange:1->2 aCOtCSY3a8XpRhyjDFipHA.hbQPAA==
,2016-02-02 13:41:13.571 ThaliTest[984:1872113] client session: fireConnectCallback: aCOtCSY3a8XpRhyjDFipHA.hbQPAA==
2016-02-02 13:41:13.571 ThaliTest[984:1872113] jxcore: connect: success
,2016-02-02 13:41:13.602 ThaliTest[984:1871361] client: relay established
2016-02-02 13:41:13.602 ThaliTest[984:1871361] client: new accepted socket: 0x173a0280
,client bridge: new client socket
,
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

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: socket closed
,
,client bridge: new client socket

,client bridge: new client socket

,client bridge: new client socket
,
,client bridge: socket closed

,ok 123 1st change of remote doc should contain remote id

,client bridge: socket closed

,ok 124 Can update remote doc without error

,null

,{ ok: true,
  id: '7aaf6381-e974-445e-8b60-eaa0a44cac7e',
,  rev: '2-f1496cbc12a26bbd5bcfb87553ada2ce' }

client bridge: new client socket

,ok 125 Remote changes occur in strict order

,client bridge: new client socket
,
,client bridge: socket closed

client bridge: socket closed

client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed
,
,client bridge: new client socket
,
,client bridge: socket closed

,client bridge: new client socket
,
,client bridge: socket closed

,client bridge: socket closed
,
,client bridge: new client socket

,client bridge: new client socket
,
,client bridge: socket closed

,client bridge: new client socket
,
,client bridge: socket closed
,
,client bridge: socket closed
,
,client bridge: new client socket

,ok 126 Local changes occur in strict order

,ok 127 2nd change of local doc should contain remote id

,# setup

,client bridge: new client socket

,client bridge: socket closed

,Now in TRM stop

State of this._isStarted: true
,
,About to call stopBroadcasting
,
,2016-02-02 13:41:24.499 ThaliTest[984:1871557] jxcore: stopBroadcasting
,2016-02-02 13:41:24.500 ThaliTest[984:1871557] THEMultipeerSession stopping peer
,2016-02-02 13:41:24.502 ThaliTest[984:1871557] multipeer session: stop timer
,2016-02-02 13:41:24.504 ThaliTest[984:1871557] client session: disconnect
,2016-02-02 13:41:24.507 ThaliTest[984:1871557] client session: stateChange:2->0 aCOtCSY3a8XpRhyjDFipHA.hbQPAA==
,2016-02-02 13:41:24.518 ThaliTest[984:1872445] server session: not connected aCOtCSY3a8XpRhyjDFipHA
,2016-02-02 13:41:24.539 ThaliTest[984:1871557] server session: disconnect
,2016-02-02 13:41:24.545 ThaliTest[984:1871557] server session: stateChange:2->0 aCOtCSY3a8XpRhyjDFipHA
,2016-02-02 13:41:24.611 ThaliTest[984:1871557] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined

,client bridge: new client socket

,# After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

,Error in mux client bridge Error: read ECONNRESET

,client bridge: socket closed

,mux server bridge listener closed

,2016-02-02 13:41:24.686 ThaliTest[984:1871557] Error!: connect ECONNREFUSED
Stack:[{"_fileName":"net.js","_functionName":"$c","_lineNumber":"837","_columnNumber":"7","_msg":"    at $c@net.js:837:7"},{"_fileName":"net.js","_functionName":"$09","_lineNumber,":"829","_columnNumber":"13","_msg":"    at $09@net.js:829:13"},{"_fileName":"net.js","_functionName":"unknown","_lineNumber":"837","_columnNumber":"7","_msg":""}]
,Uncaught Exception: Error: connect ECONNREFUSED

,[ { _fileName: 'net.js',
    _functionName: '$c',
    _lineNumber: '837',
    _columnNumber: '7',
    _msg: '    at $c@net.js:837:7' },
  { _fileName: 'net.js',
    _functionName: '$09',
    _lineNumber: '829',
,    _columnNumber: '13',
    _msg: '    at $09@net.js:829:13' },
  { _fileName: 'net.js',
    _functionName: 'unknown',
    _lineNumber: '837',
    _columnNumber: '7',
,    _msg: '' },
  toString: [Function] ]
,
,****TEST TOOK:  ms ****

,****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****


```
