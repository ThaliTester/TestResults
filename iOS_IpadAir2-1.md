#### Test 5797209499148df_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5797209499148df/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/014F5BEF-AC0B-4B08-A46E-6965A007115A/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/014F5BEF-AC0B-4B08-A46E-6965A007115A/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5797209499148df/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5797209499148df/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/5E8E8183-9A98-4DCC-9047-82D835C70CEB/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64256"
,(lldb)     command script import "/tmp/014F5BEF-AC0B-4B08-A46E-6965A007115A/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-02 13:34:19.871 ThaliTest[438:678697] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E2BA60ED-0DA1-4920-8EE8-91BAD48973C9/Library/Cookies/Cookies.binarycookies
,2016-02-02 13:34:20.296 ThaliTest[438:678697] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-02 13:34:20.297 ThaliTest[438:678697] Multi-tasking -> Device: YES, App: YES
,2016-02-02 13:34:20.306 ThaliTest[438:678697] Unlimited access to network resources
,2016-02-02 13:34:20.315 ThaliTest[438:678697] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-02 13:34:29.538 ThaliTest[438:678697] Resetting plugins due to page load.
,2016-02-02 13:34:33.070 ThaliTest[438:678697] Finished load of: file:///var/mobile/Containers/Bundle/Application/5E8E8183-9A98-4DCC-9047-82D835C70CEB/ThaliTest.app/www/index.html
,2016-02-02 13:34:33.224 ThaliTest[438:678697] JXcore Cordova plugin initializing
,2016-02-02 13:34:33.225 ThaliTest[438:678946] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E8E8183-9A98-4DCC-9047-82D835C70CEB/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E8E8183-9A98-4DCC-9047-82D835C70CEB/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E8E8183-9A98-4DCC-9047-82D835C70CEB/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E8E8183-9A98-4DCC-9047-82D835C70CEB/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E8E8183-9A98-4DCC-9047-82D835C70CEB/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E8E8183-9A98-4DCC-9047-82D835C70CEB/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E8E8183-9A98-4DCC-9047-82D835C70CEB/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E8E8183-9A98-4DCC-9047-82D835C70CEB/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

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

,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

,# teardown

,2016-02-02 13:39:29.352 ThaliTest[438:678946] jxcore: startBroadcasting
,2016-02-02 13:39:29.369 ThaliTest[438:678946] server: starting 1454416769352.438.RLmqEQ==
,2016-02-02 13:39:29.371 ThaliTest[438:678946] multipeer session: start timer: 0x19b57c80
,2016-02-02 13:39:29.372 ThaliTest[438:678946] THEMultipeerSession initialized peer 1454416769352.438
,2016-02-02 13:39:29.374 ThaliTest[438:678946] jxcore: startBroadcasting: success
,ok 54 Should be able to call startBroadcasting without error

,2016-02-02 13:39:29.378 ThaliTest[438:678946] jxcore: stopBroadcasting
2016-02-02 13:39:29.378 ThaliTest[438:678946] THEMultipeerSession stopping peer
2016-02-02 13:39:29.378 ThaliTest[438:678946] multipeer session: stop timer
2016-02-02 13:39:29.379 ThaliTest[438:678946] jxcore: stopBroadcasting: success
,ok 55 Should be able to call stopBroadcasting without error

,2016-02-02 13:39:29.385 ThaliTest[438:678946] jxcore: startBroadcasting
,2016-02-02 13:39:29.391 ThaliTest[438:678946] server: starting 1454416769384.438.ymqOeQ==
,2016-02-02 13:39:29.392 ThaliTest[438:678946] multipeer session: start timer: 0x19b30e40
2016-02-02 13:39:29.394 ThaliTest[438:678946] THEMultipeerSession initialized peer 1454416769384.438
2016-02-02 13:39:29.394 ThaliTest[438:678946] jxcore: startBroad,casting: success
ok 56 Should be able to call startBroadcasting without error

2016-02-02 13:39:29.396 ThaliTest[438:678946] jxcore: stopBroadcasting
,2016-02-02 13:39:29.397 ThaliTest[438:678946] THEMultipeerSession stopping peer
2016-02-02 13:39:29.397 ThaliTest[438:678946] multipeer session: stop timer
,2016-02-02 13:39:29.398 ThaliTest[438:678946] jxcore: stopBroadcasting: success
,ok 57 Should be able to call stopBroadcasting without error

2016-02-02 13:39:29.401 ThaliTest[438:678946] jxcore: startBroadcasting
,2016-02-02 13:39:29.404 ThaliTest[438:678946] server: starting 1454416769400.438.rrec0A==
2016-02-02 13:39:29.407 ThaliTest[438:678946] multipeer session: start timer: 0x19b33150
2016-02-02 13:39:29.407 ThaliTest[438:678946] THEMultipeerSession initializ,ed peer 1454416769400.438
2016-02-02 13:39:29.407 ThaliTest[438:678946] jxcore: startBroadcasting: success
ok 58 Should be able to call startBroadcasting without error

2016-02-02 13:39:29.409 ThaliTest[438:678946] jxcore: stopBroadcasting
2016-02-02 ,13:39:29.409 ThaliTest[438:678946] THEMultipeerSession stopping peer
2016-02-02 13:39:29.410 ThaliTest[438:678946] multipeer session: stop timer
2016-02-02 13:39:29.410 ThaliTest[438:678946] jxcore: stopBroadcasting: success
ok 59 Should be able to call, stopBroadcasting without error

2016-02-02 13:39:29.411 ThaliTest[438:678946] jxcore: startBroadcasting
,2016-02-02 13:39:29.422 ThaliTest[438:678946] server: starting 1454416769411.438.xIUzXQ==
,2016-02-02 13:39:29.424 ThaliTest[438:678946] multipeer session: start timer: 0x17513cb0
,2016-02-02 13:39:29.429 ThaliTest[438:678946] THEMultipeerSession initialized peer 1454416769411.438
,2016-02-02 13:39:29.430 ThaliTest[438:678946] jxcore: startBroadcasting: success
,ok 60 Should be able to call startBroadcasting without error

,2016-02-02 13:39:29.434 ThaliTest[438:678946] jxcore: stopBroadcasting
,2016-02-02 13:39:29.435 ThaliTest[438:678946] THEMultipeerSession stopping peer
,2016-02-02 13:39:29.436 ThaliTest[438:678946] multipeer session: stop timer
,2016-02-02 13:39:29.440 ThaliTest[438:678946] jxcore: stopBroadcasting: success
,ok 61 Should be able to call stopBroadcasting without error

,2016-02-02 13:39:29.443 ThaliTest[438:678946] jxcore: startBroadcasting
,2016-02-02 13:39:29.447 ThaliTest[438:678946] server: starting 1454416769442.438.osfx1Q==
,2016-02-02 13:39:29.450 ThaliTest[438:678946] multipeer session: start timer: 0x15692690
,2016-02-02 13:39:29.453 ThaliTest[438:678946] THEMultipeerSession initialized peer 1454416769442.438
,2016-02-02 13:39:29.456 ThaliTest[438:678946] jxcore: startBroadcasting: success
,ok 62 Should be able to call startBroadcasting without error

,2016-02-02 13:39:29.459 ThaliTest[438:678946] jxcore: stopBroadcasting
,2016-02-02 13:39:29.460 ThaliTest[438:678946] THEMultipeerSession stopping peer
,2016-02-02 13:39:29.461 ThaliTest[438:678946] multipeer session: stop timer
,2016-02-02 13:39:29.462 ThaliTest[438:678946] jxcore: stopBroadcasting: success
,ok 63 Should be able to call stopBroadcasting without error

,2016-02-02 13:39:29.466 ThaliTest[438:678946] jxcore: startBroadcasting
,2016-02-02 13:39:29.468 ThaliTest[438:678946] server: starting 1454416769465.438.CzxbIg==
,2016-02-02 13:39:29.469 ThaliTest[438:678946] multipeer session: start timer: 0x156926d0
,2016-02-02 13:39:29.473 ThaliTest[438:678946] THEMultipeerSession initialized peer 1454416769465.438
,2016-02-02 13:39:29.474 ThaliTest[438:678946] jxcore: startBroadcasting: success
,ok 64 Should be able to call startBroadcasting without error

,2016-02-02 13:39:29.476 ThaliTest[438:678946] jxcore: stopBroadcasting
,2016-02-02 13:39:29.476 ThaliTest[438:678946] THEMultipeerSession stopping peer
,2016-02-02 13:39:29.477 ThaliTest[438:678946] multipeer session: stop timer
,2016-02-02 13:39:29.479 ThaliTest[438:678946] jxcore: stopBroadcasting: success
,ok 65 Should be able to call stopBroadcasting without error
,
,2016-02-02 13:39:29.483 ThaliTest[438:678946] jxcore: startBroadcasting
,2016-02-02 13:39:29.485 ThaliTest[438:678946] server: starting 1454416769482.438.YSQvfw==
,2016-02-02 13:39:29.486 ThaliTest[438:678946] multipeer session: start timer: 0x19b33510
,2016-02-02 13:39:29.490 ThaliTest[438:678946] THEMultipeerSession initialized peer 1454416769482.438
,2016-02-02 13:39:29.491 ThaliTest[438:678946] jxcore: startBroadcasting: success
,ok 66 Should be able to call startBroadcasting without error

,2016-02-02 13:39:29.493 ThaliTest[438:678946] jxcore: stopBroadcasting
,2016-02-02 13:39:29.493 ThaliTest[438:678946] THEMultipeerSession stopping peer
,2016-02-02 13:39:29.495 ThaliTest[438:678946] multipeer session: stop timer
,2016-02-02 13:39:29.497 ThaliTest[438:678946] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error

,2016-02-02 13:39:29.500 ThaliTest[438:678946] jxcore: startBroadcasting
,2016-02-02 13:39:29.502 ThaliTest[438:678946] server: starting 1454416769499.438.nql1aA==
,2016-02-02 13:39:29.504 ThaliTest[438:678946] multipeer session: start timer: 0x1812f2f0
,2016-02-02 13:39:29.508 ThaliTest[438:678946] THEMultipeerSession initialized peer 1454416769499.438
,2016-02-02 13:39:29.508 ThaliTest[438:678946] jxcore: startBroadcasting: success
,ok 68 Should be able to call startBroadcasting without error

,2016-02-02 13:39:29.510 ThaliTest[438:678946] jxcore: stopBroadcasting
,2016-02-02 13:39:29.511 ThaliTest[438:678946] THEMultipeerSession stopping peer
,2016-02-02 13:39:29.512 ThaliTest[438:678946] multipeer session: stop timer
,2016-02-02 13:39:29.513 ThaliTest[438:678946] jxcore: stopBroadcasting: success
,ok 69 Should be able to call stopBroadcasting without error

,2016-02-02 13:39:29.516 ThaliTest[438:678946] jxcore: startBroadcasting
,2016-02-02 13:39:29.519 ThaliTest[438:678946] server: starting 1454416769516.438.n+KVmw==
,2016-02-02 13:39:29.520 ThaliTest[438:678946] multipeer session: start timer: 0x1812efb0
,2016-02-02 13:39:29.523 ThaliTest[438:678946] THEMultipeerSession initialized peer 1454416769516.438
,2016-02-02 13:39:29.524 ThaliTest[438:678946] jxcore: startBroadcasting: success
,ok 70 Should be able to call startBroadcasting without error

,2016-02-02 13:39:29.526 ThaliTest[438:678946] jxcore: stopBroadcasting
,2016-02-02 13:39:29.527 ThaliTest[438:678946] THEMultipeerSession stopping peer
,2016-02-02 13:39:29.527 ThaliTest[438:678946] multipeer session: stop timer
,2016-02-02 13:39:29.530 ThaliTest[438:678946] jxcore: stopBroadcasting: success
,ok 71 Should be able to call stopBroadcasting without error

,2016-02-02 13:39:29.532 ThaliTest[438:678946] jxcore: startBroadcasting
,2016-02-02 13:39:29.535 ThaliTest[438:678946] server: starting 1454416769532.438.L2qLFA==
,2016-02-02 13:39:29.537 ThaliTest[438:678946] multipeer session: start timer: 0x1812f150
,2016-02-02 13:39:29.539 ThaliTest[438:678946] THEMultipeerSession initialized peer 1454416769532.438
,2016-02-02 13:39:29.540 ThaliTest[438:678946] jxcore: startBroadcasting: success
,ok 72 Should be able to call startBroadcasting without error

,2016-02-02 13:39:29.542 ThaliTest[438:678946] jxcore: stopBroadcasting
,2016-02-02 13:39:29.542 ThaliTest[438:678946] THEMultipeerSession stopping peer
,2016-02-02 13:39:29.542 ThaliTest[438:678946] multipeer session: stop timer
,2016-02-02 13:39:29.544 ThaliTest[438:678946] jxcore: stopBroadcasting: success
,ok 73 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,# teardown

,2016-02-02 13:39:29.731 ThaliTest[438:678946] jxcore: startBroadcasting
,2016-02-02 13:39:29.735 ThaliTest[438:678946] server: starting 1454416769731.438.8j/ryA==
,2016-02-02 13:39:29.737 ThaliTest[438:678946] multipeer session: start timer: 0x1812ef40
,2016-02-02 13:39:29.740 ThaliTest[438:678946] THEMultipeerSession initialized peer 1454416769731.438
,2016-02-02 13:39:29.742 ThaliTest[438:678946] jxcore: startBroadcasting: success
,ok 74 Should be able to call startBroadcasting without error

,2016-02-02 13:39:29.746 ThaliTest[438:678946] jxcore: startBroadcasting
,2016-02-02 13:39:29.747 ThaliTest[438:678946] jxcore: startBroadcasting: failure
,ok 75 Cannot call startBroadcasting twice

,2016-02-02 13:39:29.754 ThaliTest[438:678946] jxcore: stopBroadcasting
,2016-02-02 13:39:29.754 ThaliTest[438:678946] THEMultipeerSession stopping peer
,2016-02-02 13:39:29.756 ThaliTest[438:678946] multipeer session: stop timer
,2016-02-02 13:39:29.760 ThaliTest[438:678946] jxcore: stopBroadcasting: success
,ok 76 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on connection to bad peer

,# teardown

,2016-02-02 13:39:30.196 ThaliTest[438:678946] jxcore: startBroadcasting
,2016-02-02 13:39:30.199 ThaliTest[438:678946] server: starting 1454416770195.438.kNRtdQ==
,2016-02-02 13:39:30.201 ThaliTest[438:678946] multipeer session: start timer: 0x175d6f00
2016-02-02 13:39:30.201 ThaliTest[438:678946] THEMultipeerSession initialized peer 1454416770195.438
2016-02-02 13:39:30.202 ThaliTest[438:678946] jxcore: startBroadcasting: success
,ok 77 Should be able to call startBroadcasting without error

2016-02-02 13:39:30.205 ThaliTest[438:678946] jxcore: connect foobar
2016-02-02 13:39:30.206 ThaliTest[438:678946] client: unknown peer foobar
2016-02-02 13:39:30.206 ThaliTest[438:678946] jxcore: connect: fail: Unknown peer
,ok 78 Should not connect to a bad peer

,2016-02-02 13:39:30.211 ThaliTest[438:678946] jxcore: stopBroadcasting
,2016-02-02 13:39:30.212 ThaliTest[438:678946] THEMultipeerSession stopping peer
,2016-02-02 13:39:30.213 ThaliTest[438:678946] multipeer session: stop timer
,2016-02-02 13:39:30.214 ThaliTest[438:678946] jxcore: stopBroadcasting: success
ok 79 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on disconnect to bad peer

,# teardown

,2016-02-02 13:39:30.342 ThaliTest[438:678946] jxcore: startBroadcasting
,2016-02-02 13:39:30.345 ThaliTest[438:678946] server: starting 1454416770341.438.27Qluw==
,2016-02-02 13:39:30.346 ThaliTest[438:678946] multipeer session: start timer: 0x19b29030
,2016-02-02 13:39:30.347 ThaliTest[438:678946] THEMultipeerSession initialized peer 1454416770341.438
2016-02-02 13:39:30.348 ThaliTest[438:678946] jxcore: startBroadcasting: success
,ok 80 Should be able to call startBroadcasting without error

2016-02-02 13:39:30.351 ThaliTest[438:678946] jxcore: disconnect
,2016-02-02 13:39:30.351 ThaliTest[438:678946] jxcore: disconnect: fail
,ok 81 Disconnect should fail to a non-existant peer 

2016-02-02 13:39:30.356 ThaliTest[438:678946] jxcore: stopBroadcasting
2016-02-02 13:39:30.356 ThaliTest[438:678946] THEMultipeerSession stopping peer
2016-02-02 13:39:30.356 ThaliTest[438:678946] m,ultipeer session: stop timer
2016-02-02 13:39:30.357 ThaliTest[438:678946] jxcore: stopBroadcasting: success
,ok 82 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter can discover and connect to peers

,# teardown

,2016-02-02 13:39:30.863 ThaliTest[438:678946] jxcore: startBroadcasting
,2016-02-02 13:39:30.866 ThaliTest[438:678946] server: starting 1454416770863.438.fiXOiw==
,2016-02-02 13:39:30.867 ThaliTest[438:678946] multipeer session: start timer: 0x15687b80
,2016-02-02 13:39:30.868 ThaliTest[438:678946] THEMultipeerSession initialized peer 1454416770863.438
2016-02-02 13:39:30.868 ThaliTest[438:678946] jxcore: startBroadcasting: success
,ok 83 Should be able to call startBroadcasting without error

,2016-02-02 13:39:31.524 ThaliTest[438:678697] client: found peer: 1454416770746.984.XGC5BA==
,2016-02-02 13:39:31.527 ThaliTest[438:678946] jxcore: connect 1454416770746.984.XGC5BA==
,2016-02-02 13:39:31.528 ThaliTest[438:678946] client session: connect
,2016-02-02 13:39:31.528 ThaliTest[438:678946] client session: stateChange:0->1 1454416770746.984.XGC5BA==
,2016-02-02 13:39:32.150 ThaliTest[438:678697] multipeer session: reset timer
2016-02-02 13:39:32.150 ThaliTest[438:678697] multipeer session: stop timer
2016-02-02 13:39:32.150 ThaliTest[438:678697] multipeer session: start timer: 0x15687b80
,2016-02-02 13:39:32.151 ThaliTest[438:678697] server session: connect
2016-02-02 13:39:32.151 ThaliTest[438:678697] server session: stateChange:0->1 1454416770746.984
,2016-02-02 13:39:32.159 ThaliTest[438:678697] server: accepting invitation 1454416770746.984
,2016-02-02 13:39:34.970 ThaliTest[438:679411] client session: connected
2016-02-02 13:39:34.971 ThaliTest[438:679411] client session: stateChange:1->2 1454416770746.984.XGC5BA==
,2016-02-02 13:39:35.000 ThaliTest[438:679407] client session: fireConnectCallback: 1454416770746.984.XGC5BA==
2016-02-02 13:39:35.002 ThaliTest[438:679407] jxcore: connect: success
,ok 84 Should be able to connect without error

,ok 85 Port should be within range

,2016-02-02 13:39:35.006 ThaliTest[438:678946] jxcore: disconnect
2016-02-02 13:39:35.007 ThaliTest[438:678946] client session: disconnectFromPeer: 1454416770746.984.XGC5BA==
,2016-02-02 13:39:35.007 ThaliTest[438:678946] client session: disconnect
2016-02-02 13:39:35.007 ThaliTest[438:678946] client session: stateChange:2->0 1454416770746.984.XGC5BA==
,2016-02-02 13:39:35.016 ThaliTest[438:678946] jxcore: disconnect: success
ok 86 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,2016-02-02 13:39:35.036 ThaliTest[438:679405] server session: connected
,2016-02-02 13:39:35.037 ThaliTest[438:679405] server session: stateChange:1->2 1454416770746.984
,2016-02-02 13:39:35.204 ThaliTest[438:678697] server relay: socket disconnected
,2016-02-02 13:39:35.204 ThaliTest[438:678697] server relay: 0x19a03b20 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-02 13:39:35.881 ThaliTest[438:679411] server session: not connected 1454416770746.984
,calling stopBroadcasting

,2016-02-02 13:39:36.059 ThaliTest[438:678946] jxcore: stopBroadcasting
,2016-02-02 13:39:36.060 ThaliTest[438:678946] THEMultipeerSession stopping peer
,2016-02-02 13:39:36.060 ThaliTest[438:678946] multipeer session: stop timer
,2016-02-02 13:39:36.061 ThaliTest[438:678946] server session: disconnect
,2016-02-02 13:39:36.062 ThaliTest[438:678946] server session: stateChange:2->0 1454416770746.984
,2016-02-02 13:39:36.064 ThaliTest[438:678946] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double connect

,# teardown

,2016-02-02 13:39:36.582 ThaliTest[438:678946] jxcore: startBroadcasting
,2016-02-02 13:39:36.585 ThaliTest[438:678946] server: starting 1454416776581.438.ftA4DQ==
,2016-02-02 13:39:36.586 ThaliTest[438:678946] multipeer session: start timer: 0x157ba900
2016-02-02 13:39:36.586 ThaliTest[438:678946] THEMultipeerSession initialized peer 1454416776581.438
2016-02-02 13:39:36.587 ThaliTest[438:678946] jxcore: startBroad,casting: success
ok 87 Should be able to call startBroadcasting without error

,2016-02-02 13:39:37.285 ThaliTest[438:678697] client: found peer: 1454416770746.984.XGC5BA==
,2016-02-02 13:39:37.287 ThaliTest[438:678946] jxcore: connect 1454416770746.984.XGC5BA==
,2016-02-02 13:39:37.288 ThaliTest[438:678946] client session: connect
,2016-02-02 13:39:37.288 ThaliTest[438:678946] client session: stateChange:0->1 1454416770746.984.XGC5BA==
,2016-02-02 13:39:37.358 ThaliTest[438:678697] client: found peer: 1454416776495.984.6FCF9Q==
,2016-02-02 13:39:37.359 ThaliTest[438:678946] jxcore: connect 1454416776495.984.6FCF9Q==
2016-02-02 13:39:37.360 ThaliTest[438:678946] client session: connect
2016-02-02 13:39:37.360 ThaliTest[438:678946] client session: stateChange:0->1 1454416776495.984.6FCF9Q==
,2016-02-02 13:39:38.290 ThaliTest[438:678697] multipeer session: reset timer
2016-02-02 13:39:38.290 ThaliTest[438:678697] multipeer session: stop timer
2016-02-02 13:39:38.290 ThaliTest[438:678697] multipeer session: start timer: 0x157ba900
2016-02-02 ,13:39:38.290 ThaliTest[438:678697] server session: connect
2016-02-02 13:39:38.290 ThaliTest[438:678697] server session: stateChange:0->1 1454416776495.984
,2016-02-02 13:39:38.295 ThaliTest[438:678697] server: accepting invitation 1454416776495.984
,2016-02-02 13:39:40.842 ThaliTest[438:679407] client session: connected
,2016-02-02 13:39:40.843 ThaliTest[438:679407] client session: stateChange:1->2 1454416776495.984.6FCF9Q==
,2016-02-02 13:39:40.848 ThaliTest[438:679464] client session: fireConnectCallback: 1454416776495.984.6FCF9Q==
2016-02-02 13:39:40.849 ThaliTest[438:679464] jxcore: connect: success
,ok 88 Should be able to connect without error

,ok 89 Port should be within range

,2016-02-02 13:39:40.852 ThaliTest[438:678946] jxcore: connect 1454416776495.984.6FCF9Q==
,2016-02-02 13:39:40.853 ThaliTest[438:678946] client: already connect(ing/ed) to 1454416776495.984.6FCF9Q==
,2016-02-02 13:39:40.853 ThaliTest[438:678946] jxcore: connect: fail: Aleady connecting
,ok 90 Should fail on double connect

,2016-02-02 13:39:40.857 ThaliTest[438:678946] jxcore: disconnect
,2016-02-02 13:39:40.857 ThaliTest[438:678946] client session: disconnectFromPeer: 1454416776495.984.6FCF9Q==
,2016-02-02 13:39:40.857 ThaliTest[438:678946] client session: disconnect
2016-02-02 13:39:40.858 ThaliTest[438:678946] client session: stateChange:2->0 1454416776495.984.6FCF9Q==
,2016-02-02 13:39:40.931 ThaliTest[438:678946] jxcore: disconnect: success
,ok 91 Should be able to disconnect without error

,setting stopBroadcasting callback and ending test.

,# setup

,2016-02-02 13:39:41.146 ThaliTest[438:679411] server session: connected
2016-02-02 13:39:41.146 ThaliTest[438:679411] server session: stateChange:1->2 1454416776495.984
,2016-02-02 13:39:41.150 ThaliTest[438:678697] server relay: socket disconnected
,2016-02-02 13:39:41.150 ThaliTest[438:678697] server relay: 0x19a0fc80 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-02 13:39:41.179 ThaliTest[438:679448] server session: not connected 1454416776495.984
,calling stopBroadcasting

,2016-02-02 13:39:41.295 ThaliTest[438:678946] jxcore: stopBroadcasting
,2016-02-02 13:39:41.296 ThaliTest[438:678946] THEMultipeerSession stopping peer
,2016-02-02 13:39:41.296 ThaliTest[438:678946] multipeer session: stop timer
,2016-02-02 13:39:41.297 ThaliTest[438:678946] client session: disconnect
2016-02-02 13:39:41.297 ThaliTest[438:678946] client session: stateChange:1->0 1454416770746.984.XGC5BA==
2016-02-02 13:39:41.298 ThaliTest[438:678946] server session: disconnect
2,016-02-02 13:39:41.299 ThaliTest[438:678946] server session: stateChange:2->0 1454416776495.984
,2016-02-02 13:39:41.308 ThaliTest[438:678946] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,# teardown
,
,2016-02-02 13:39:41.380 ThaliTest[438:678946] jxcore: startBroadcasting
,2016-02-02 13:39:41.383 ThaliTest[438:678946] server: starting 1454416781380.438.KHAk0w==
,2016-02-02 13:39:41.383 ThaliTest[438:678946] multipeer session: start timer: 0x17582760
,2016-02-02 13:39:41.385 ThaliTest[438:678946] THEMultipeerSession initialized peer 1454416781380.438
,2016-02-02 13:39:41.388 ThaliTest[438:678946] jxcore: startBroadcasting: success
,ok 92 Should be able to call startBroadcasting without error

,2016-02-02 13:39:41.392 ThaliTest[438:678697] client: found peer: 1454416776495.984.6FCF9Q==
,2016-02-02 13:39:41.394 ThaliTest[438:678697] client: found peer: 1454416776581.438.ftA4DQ==
,2016-02-02 13:39:41.395 ThaliTest[438:678946] jxcore: connect 1454416776495.984.6FCF9Q==
,2016-02-02 13:39:41.396 ThaliTest[438:678946] client session: connect
,2016-02-02 13:39:41.396 ThaliTest[438:678946] client session: stateChange:0->1 1454416776495.984.6FCF9Q==
,2016-02-02 13:39:41.660 ThaliTest[438:678946] jxcore: connect 1454416776581.438.ftA4DQ==
2016-02-02 13:39:41.660 ThaliTest[438:678946] client session: connect
,2016-02-02 13:39:41.661 ThaliTest[438:678946] client session: stateChange:0->1 1454416776581.438.ftA4DQ==
,2016-02-02 13:39:42.476 ThaliTest[438:678697] client: lost peer: 1454416776581.438.ftA4DQ==
2016-02-02 13:39:42.476 ThaliTest[438:678697] client session: onPeerLost: 1454416776581.438.ftA4DQ==
2016-02-02 13:39:42.477 ThaliTest[438:678697] client session:, onLinkFailure: 1454416776581.438.ftA4DQ==
2016-02-02 13:39:42.477 ThaliTest[438:678697] client session: disconnect
2016-02-02 13:39:42.477 ThaliTest[438:678697] client session: stateChange:1->0 1454416776581.438.ftA4DQ==
2016-02-02 13:39:42.478 ThaliTe,st[438:678697] client session: fireConnectCallback: 1454416776581.438.ftA4DQ==
2016-02-02 13:39:42.478 ThaliTest[438:678697] jxcore: connect: fail: Peer disconnected
,2016-02-02 13:39:42.613 ThaliTest[438:678697] client: found peer: 1454416781285.984.9EmuGw==
,2016-02-02 13:39:42.615 ThaliTest[438:678946] jxcore: connect 1454416781285.984.9EmuGw==
2016-02-02 13:39:42.615 ThaliTest[438:678946] client session: connect
2016-02-02 13:39:42.616 ThaliTest[438:678946] client session: stateChange:0->1 1454416781285.984.9EmuGw==
,2016-02-02 13:39:42.936 ThaliTest[438:678697] multipeer session: reset timer
2016-02-02 13:39:42.936 ThaliTest[438:678697] multipeer session: stop timer
,2016-02-02 13:39:42.936 ThaliTest[438:678697] multipeer session: start timer: 0x17582760
,2016-02-02 13:39:42.937 ThaliTest[438:678697] server session: connect
,2016-02-02 13:39:42.937 ThaliTest[438:678697] server session: stateChange:0->1 1454416781285.984
,2016-02-02 13:39:42.945 ThaliTest[438:678697] server: accepting invitation 1454416781285.984
,2016-02-02 13:39:43.483 ThaliTest[438:678946] jxcore: connect 1454416776581.438.ftA4DQ==
2016-02-02 13:39:43.483 ThaliTest[438:678946] client: connect: unreachable 1454416776581.438.ftA4DQ==
2016-02-02 13:39:43.483 ThaliTest[438:678946] jxcore: connect: fail: Peer unreachable
,2016-02-02 13:39:45.672 ThaliTest[438:678697] client: lost peer: 1454416776495.984.6FCF9Q==
2016-02-02 13:39:45.672 ThaliTest[438:678697] client session: onPeerLost: 1454416776495.984.6FCF9Q==
2016-02-02 13:39:45.673 ThaliTest[438:678697] client session:, onLinkFailure: 1454416776495.984.6FCF9Q==
2016-02-02 13:39:45.673 ThaliTest[438:678697] client session: disconnect
2016-02-02 13:39:45.673 ThaliTest[438:678697] client session: stateChange:1->0 1454416776495.984.6FCF9Q==
,2016-02-02 13:39:45.675 ThaliTest[438:678697] client session: fireConnectCallback: 1454416776495.984.6FCF9Q==
2016-02-02 13:39:45.675 ThaliTest[438:678697] jxcore: connect: fail: Peer disconnected
,2016-02-02 13:39:45.811 ThaliTest[438:679464] client session: connected
,2016-02-02 13:39:45.811 ThaliTest[438:679464] client session: stateChange:1->2 1454416781285.984.9EmuGw==
,2016-02-02 13:39:45.829 ThaliTest[438:679448] client session: fireConnectCallback: 1454416781285.984.9EmuGw==
2016-02-02 13:39:45.830 ThaliTest[438:679448] jxcore: connect: success
,ok 93 Should be able to connect without error

,ok 94 Port should be within range

,2016-02-02 13:39:45.833 ThaliTest[438:678946] jxcore: disconnect
,2016-02-02 13:39:45.834 ThaliTest[438:678946] client session: disconnectFromPeer: 1454416781285.984.9EmuGw==
,2016-02-02 13:39:45.834 ThaliTest[438:678946] client session: disconnect
,2016-02-02 13:39:45.835 ThaliTest[438:678946] client session: stateChange:2->0 1454416781285.984.9EmuGw==
,2016-02-02 13:39:45.845 ThaliTest[438:678946] jxcore: disconnect: success
,ok 95 Should be able to disconnect without error

,2016-02-02 13:39:45.847 ThaliTest[438:678946] jxcore: disconnect
,2016-02-02 13:39:45.848 ThaliTest[438:678946] jxcore: disconnect: fail
,ok 96 Disconnect should fail 

,setting stopBroadcasting callback and ending test.

,# setup

,2016-02-02 13:39:45.943 ThaliTest[438:679411] server session: connected
2016-02-02 13:39:45.943 ThaliTest[438:679411] server session: stateChange:1->2 1454416781285.984
,2016-02-02 13:39:45.980 ThaliTest[438:678697] server relay: socket disconnected
,2016-02-02 13:39:45.980 ThaliTest[438:678697] server relay: 0x19aefbd0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-02 13:39:46.005 ThaliTest[438:679409] server session: not connected 1454416781285.984
,calling stopBroadcasting

,2016-02-02 13:39:46.072 ThaliTest[438:678946] jxcore: stopBroadcasting
,2016-02-02 13:39:46.072 ThaliTest[438:678946] THEMultipeerSession stopping peer
,2016-02-02 13:39:46.073 ThaliTest[438:678946] multipeer session: stop timer
,2016-02-02 13:39:46.074 ThaliTest[438:678946] server session: disconnect
,2016-02-02 13:39:46.074 ThaliTest[438:678946] server session: stateChange:2->0 1454416781285.984
,2016-02-02 13:39:46.077 ThaliTest[438:678946] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can connect and send data

,# teardown

,echo server started on port: 51282

,2016-02-02 13:39:47.054 ThaliTest[438:678946] jxcore: startBroadcasting
,2016-02-02 13:39:47.055 ThaliTest[438:678946] server: starting 1454416787054.438.1D88vQ==
,2016-02-02 13:39:47.055 ThaliTest[438:678946] multipeer session: start timer: 0x19ae45f0
,2016-02-02 13:39:47.056 ThaliTest[438:678946] THEMultipeerSession initialized peer 1454416787054.438
,2016-02-02 13:39:47.056 ThaliTest[438:678946] jxcore: startBroadcasting: success
,ok 97 Should be able to call startBroadcasting without error

,2016-02-02 13:39:47.722 ThaliTest[438:678697] client: found peer: 1454416781285.984.9EmuGw==
,2016-02-02 13:39:47.724 ThaliTest[438:678946] jxcore: connect 1454416781285.984.9EmuGw==
2016-02-02 13:39:47.724 ThaliTest[438:678946] client session: connect
2016-02-02 13:39:47.725 ThaliTest[438:678946] client session: stateChange:0->1 1454416781285.984.9EmuGw==
,2016-02-02 13:39:48.273 ThaliTest[438:678697] multipeer session: reset timer
2016-02-02 13:39:48.273 ThaliTest[438:678697] multipeer session: stop timer
2016-02-02 13:39:48.274 ThaliTest[438:678697] multipeer session: start timer: 0x19ae45f0
2016-02-02 ,13:39:48.274 ThaliTest[438:678697] server session: connect
2016-02-02 13:39:48.274 ThaliTest[438:678697] server session: stateChange:0->1 1454416787029.984
,2016-02-02 13:39:48.283 ThaliTest[438:678697] server: accepting invitation 1454416787029.984
,2016-02-02 13:39:48.309 ThaliTest[438:678697] client: found peer: 1454416787029.984.KTJFuA==
,2016-02-02 13:39:48.312 ThaliTest[438:678946] jxcore: connect 1454416787029.984.KTJFuA==
2016-02-02 13:39:48.313 ThaliTest[438:678946] client session: connect
2016-02-02 13:39:48.314 ThaliTest[438:678946] client session: stateChange:0->1 1454416787029.984.KTJFuA==
,2016-02-02 13:39:53.625 ThaliTest[438:679464] server session: connected
2016-02-02 13:39:53.625 ThaliTest[438:679464] server session: stateChange:1->2 1454416787029.984
,2016-02-02 13:39:53.943 ThaliTest[438:679464] client session: connected
,2016-02-02 13:39:53.944 ThaliTest[438:679464] client session: stateChange:1->2 1454416787029.984.KTJFuA==
,2016-02-02 13:39:56.142 ThaliTest[438:678697] server relay: connected (to port: 51282)
,2016-02-02 13:39:56.715 ThaliTest[438:679448] client session: fireConnectCallback: 1454416787029.984.KTJFuA==
2016-02-02 13:39:56.715 ThaliTest[438:679448] jxcore: connect: success
,ok 98 Should be able to connect without error

,ok 99 Port should be within range

,2016-02-02 13:39:56.721 ThaliTest[438:678697] client: relay established
2016-02-02 13:39:56.722 ThaliTest[438:678697] client: new accepted socket: 0x19ae7960
,2016-02-02 13:40:01.695 ThaliTest[438:678697] client: lost peer: 1454416781285.984.9EmuGw==
2016-02-02 13:40:01.695 ThaliTest[438:678697] client session: onPeerLost: 1454416781285.984.9EmuGw==
2016-02-02 13:40:01.695 ThaliTest[438:678697] client session:, onLinkFailure: 1454416781285.984.9EmuGw==
2016-02-02 13:40:01.696 ThaliTest[438:678697] client session: disconnect
2016-02-02 13:40:01.696 ThaliTest[438:678697] client session: stateChange:1->0 1454416781285.984.9EmuGw==
2016-02-02 13:40:01.697 ThaliTe,st[438:678697] client session: fireConnectCallback: 1454416781285.984.9EmuGw==
,2016-02-02 13:40:01.697 ThaliTest[438:678697] jxcore: connect: fail: Peer disconnected
,data in 1095

,2016-02-02 13:40:02.704 ThaliTest[438:678946] jxcore: connect 1454416781285.984.9EmuGw==
,2016-02-02 13:40:02.705 ThaliTest[438:678946] client: connect: unreachable 1454416781285.984.9EmuGw==
,2016-02-02 13:40:02.706 ThaliTest[438:678946] jxcore: connect: fail: Peer unreachable
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

,2016-02-02 13:40:18.275 ThaliTest[438:678697] multipeer session: restart
,2016-02-02 13:40:18.299 ThaliTest[438:678697] client: found peer: 1454416787029.984.KTJFuA==
,data in 14235

,data in 15330

,data in 25185

,data in 29565

,data in 58035

,data in 61320

,data in 63510

,data in 78870

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

,data in 116070

,data in 117165

,data in 118260

,data in 119355

,data in 120450

,data in 121545

,data in 122640

,data in 124830

,data in 125925

,data in 127020

,data in 131072

,ok 100 the test messages should be equal

,2016-02-02 13:40:41.642 ThaliTest[438:678946] jxcore: disconnect
,2016-02-02 13:40:41.643 ThaliTest[438:678946] client session: disconnectFromPeer: 1454416787029.984.KTJFuA==
2016-02-02 13:40:41.643 ThaliTest[438:678946] client session: disconnect
2016-02-02 13:40:41.644 ThaliTest[438:678946] client session: stateChang,e:2->0 1454416787029.984.KTJFuA==
,2016-02-02 13:40:41.651 ThaliTest[438:678946] jxcore: disconnect: success
ok 101 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,2016-02-02 13:40:43.151 ThaliTest[438:679603] server session: not connected 1454416787029.984
,2016-02-02 13:40:44.480 ThaliTest[438:678697] client: lost peer: 1454416787029.984.KTJFuA==
2016-02-02 13:40:44.480 ThaliTest[438:678697] client session: onPeerLost: 1454416787029.984.KTJFuA==
,calling stopBroadcasting

,2016-02-02 13:40:45.791 ThaliTest[438:678946] jxcore: stopBroadcasting
,2016-02-02 13:40:45.791 ThaliTest[438:678946] THEMultipeerSession stopping peer
,2016-02-02 13:40:45.792 ThaliTest[438:678946] multipeer session: stop timer
,2016-02-02 13:40:45.793 ThaliTest[438:678946] server session: disconnect
2016-02-02 13:40:45.793 ThaliTest[438:678946] server session: stateChange:2->0 1454416787029.984
,2016-02-02 13:40:45.800 ThaliTest[438:678946] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter handles socket disconnect correctly

,# teardown

,echo server started on port: 51292

,2016-02-02 13:40:45.965 ThaliTest[438:678946] jxcore: startBroadcasting
,2016-02-02 13:40:45.969 ThaliTest[438:678946] server: starting 1454416845964.438.JBsgHQ==
,2016-02-02 13:40:45.969 ThaliTest[438:678946] multipeer session: start timer: 0x19ae4f50
,2016-02-02 13:40:45.970 ThaliTest[438:678946] THEMultipeerSession initialized peer 1454416845964.438
2016-02-02 13:40:45.971 ThaliTest[438:678946] jxcore: startBroadcasting: success
ok 102 Should be able to call startBroadcasting without error

,2016-02-02 13:40:46.912 ThaliTest[438:678697] client: found peer: 1454416787029.984.KTJFuA==
,[{"peerIdentifier":"1454416787029.984.KTJFuA==","peerName":"(null)","peerAvailable":true}]

,2016-02-02 13:40:46.915 ThaliTest[438:678946] jxcore: connect 1454416787029.984.KTJFuA==
,2016-02-02 13:40:46.916 ThaliTest[438:678946] client session: connect
2016-02-02 13:40:46.916 ThaliTest[438:678946] client session: stateChange:0->1 1454416787029.984.KTJFuA==
,2016-02-02 13:40:47.181 ThaliTest[438:678697] client: found peer: 1454416845876.984./mImjQ==
[{"peerIdentifier":"1454416845876.984./mImjQ==","peerName":"(null)","peerAvailable":true}]

,2016-02-02 13:40:47.183 ThaliTest[438:678946] jxcore: connect 1454416845876.984./mImjQ==
2016-02-02 13:40:47.184 ThaliTest[438:678946] client session: connect
,2016-02-02 13:40:47.185 ThaliTest[438:678946] client session: stateChange:0->1 1454416845876.984./mImjQ==
,2016-02-02 13:40:47.450 ThaliTest[438:678697] multipeer session: reset timer
2016-02-02 13:40:47.450 ThaliTest[438:678697] multipeer session: stop timer
2016-02-02 13:40:47.451 ThaliTest[438:678697] multipeer session: start timer: 0x19ae4f50
,2016-02-02 13:40:47.451 ThaliTest[438:678697] server session: connect
,2016-02-02 13:40:47.452 ThaliTest[438:678697] server session: stateChange:0->1 1454416845876.984
,2016-02-02 13:40:47.459 ThaliTest[438:678697] server: accepting invitation 1454416845876.984
,2016-02-02 13:40:52.741 ThaliTest[438:679650] client session: connected
2016-02-02 13:40:52.741 ThaliTest[438:679650] client session: stateChange:1->2 1454416845876.984./mImjQ==
,2016-02-02 13:40:52.849 ThaliTest[438:679663] server session: connected
2016-02-02 13:40:52.849 ThaliTest[438:679663] server session: stateChange:1->2 1454416845876.984
,2016-02-02 13:40:53.199 ThaliTest[438:679650] client session: fireConnectCallback: 1454416845876.984./mImjQ==
2016-02-02 13:40:53.200 ThaliTest[438:679650] jxcore: connect: success
,ok 103 Should be able to connect without error

,ok 104 Port should be within range

,ok 105 First connect should succeed

,2016-02-02 13:40:53.234 ThaliTest[438:678697] client: relay established
2016-02-02 13:40:53.234 ThaliTest[438:678697] client: new accepted socket: 0x19a12ad0
,2016-02-02 13:40:53.274 ThaliTest[438:678697] server relay: connected (to port: 51292)
,2016-02-02 13:40:53.671 ThaliTest[438:678697] client: lost peer: 1454416787029.984.KTJFuA==
2016-02-02 13:40:53.672 ThaliTest[438:678697] client session: onPeerLost: 1454416787029.984.KTJFuA==
2016-02-02 13:40:53.672 ThaliTest[438:678697] client session:, onLinkFailure: 1454416787029.984.KTJFuA==
2016-02-02 13:40:53.672 ThaliTest[438:678697] client session: disconnect
2016-02-02 13:40:53.672 ThaliTest[438:678697] client session: stateChange:1->0 1454416787029.984.KTJFuA==
,2016-02-02 13:40:53.673 ThaliTest[438:678697] client session: fireConnectCallback: 1454416787029.984.KTJFuA==
2016-02-02 13:40:53.673 ThaliTest[438:678697] jxcore: connect: fail: Peer disconnected
,[{"peerIdentifier":"1454416787029.984.KTJFuA==","peerName":"(null)","peerAvailable":false}]

,ok 106 the test messages should be equal

,ok 107 First send should succeed

,2016-02-02 13:40:53.745 ThaliTest[438:678697] client: socket closed
,2016-02-02 13:40:53.746 ThaliTest[438:678697] client relay: socket disconnected
,2016-02-02 13:40:53.746 ThaliTest[438:678697] client relay: 0x19a12ad0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2016-02-02 13:40:53.746 ThaliTest[438:678697] client session: socket closed: 1454416845876.984./mImjQ==
2016-02-02 13:40:53.747 ThaliTest[438:678697] client session: onLinkFailure: 1454416845876.984./mImjQ==
2016-02-02 13:40:53.747 ThaliTest[438:678697] ,client session: disconnect
2016-02-02 13:40:53.747 ThaliTest[438:678697] client session: stateChange:2->0 1454416845876.984./mImjQ==
,2016-02-02 13:40:53.759 ThaliTest[438:678697] client session: fireConnectionErrorEvent: 1454416845876.984./mImjQ==
,2016-02-02 13:40:53.763 ThaliTest[438:678946] jxcore: connect 1454416845876.984./mImjQ==
2016-02-02 13:40:53.763 ThaliTest[438:678946] client session: connect
2016-02-02 13:40:53.763 ThaliTest[438:678946] client session: stateChange:0->1 1454416845876.984./mImjQ==
,2016-02-02 13:40:54.351 ThaliTest[438:678697] multipeer session: reset timer
2016-02-02 13:40:54.352 ThaliTest[438:678697] multipeer session: stop timer
2016-02-02 13:40:54.352 ThaliTest[438:678697] multipeer session: start timer: 0x19ae4f50
2016-02-02 ,13:40:54.352 ThaliTest[438:678697] server: disconnecting to refresh session (1454416845876.984)
2016-02-02 13:40:54.352 ThaliTest[438:678697] server session: disconnect
2016-02-02 13:40:54.353 ThaliTest[438:678697] server session: stateChange:2->0 1454416845876.984
,2016-02-02 13:40:54.363 ThaliTest[438:678697] server session: connect
2016-02-02 13:40:54.363 ThaliTest[438:678697] server session: stateChange:0->1 1454416845876.984
,2016-02-02 13:40:54.372 ThaliTest[438:678697] server: accepting invitation 1454416845876.984
,2016-02-02 13:40:54.687 ThaliTest[438:678946] jxcore: connect 1454416787029.984.KTJFuA==
2016-02-02 13:40:54.687 ThaliTest[438:678946] client: connect: unreachable 1454416787029.984.KTJFuA==
2016-02-02 13:40:54.687 ThaliTest[438:678946] jxcore: connect: fail: Peer unreachable
,2016-02-02 13:40:57.460 ThaliTest[438:679663] server session: connected
,2016-02-02 13:40:57.460 ThaliTest[438:679663] server session: stateChange:1->2 1454416845876.984
,2016-02-02 13:40:57.477 ThaliTest[438:678697] server relay: connected (to port: 51292)
,2016-02-02 13:40:57.616 ThaliTest[438:679650] server session: not connected 1454416845876.984
,2016-02-02 13:40:59.101 ThaliTest[438:679662] client session: connected
,2016-02-02 13:40:59.101 ThaliTest[438:679662] client session: stateChange:1->2 1454416845876.984./mImjQ==
,2016-02-02 13:41:00.202 ThaliTest[438:679663] client session: fireConnectCallback: 1454416845876.984./mImjQ==
2016-02-02 13:41:00.203 ThaliTest[438:679663] jxcore: connect: success
,ok 108 Should be able to connect without error

,ok 109 Port should be within range

,ok 110 Second connect should succeed

,2016-02-02 13:41:00.231 ThaliTest[438:678697] client: relay established
2016-02-02 13:41:00.232 ThaliTest[438:678697] client: new accepted socket: 0x186922e0
,ok 111 the test messages should be equal

,ok 112 Second send should succeed

,# setup

,2016-02-02 13:41:02.843 ThaliTest[438:678697] client: socket closed
,2016-02-02 13:41:02.843 ThaliTest[438:678697] client relay: socket disconnected
,2016-02-02 13:41:02.844 ThaliTest[438:678697] client relay: 0x186922e0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-02-02 13:41:02,.844 ThaliTest[438:678697] client session: socket closed: 1454416845876.984./mImjQ==
,2016-02-02 13:41:02.844 ThaliTest[438:678697] client session: onLinkFailure: 1454416845876.984./mImjQ==
2016-02-02 13:41:02.844 ThaliTest[438:678697] client session: disconnect
2016-02-02 13:41:02.845 ThaliTest[438:678697] client session: stateChange:2->,0 1454416845876.984./mImjQ==
,2016-02-02 13:41:02.855 ThaliTest[438:678697] client session: fireConnectionErrorEvent: 1454416845876.984./mImjQ==
,calling stopBroadcasting

,2016-02-02 13:41:02.897 ThaliTest[438:678946] jxcore: stopBroadcasting
,2016-02-02 13:41:02.897 ThaliTest[438:678946] THEMultipeerSession stopping peer
,2016-02-02 13:41:02.898 ThaliTest[438:678946] multipeer session: stop timer
,2016-02-02 13:41:02.899 ThaliTest[438:678946] server session: disconnect
2016-02-02 13:41:02.900 ThaliTest[438:678946] server session: stateChange:2->0 1454416845876.984
,2016-02-02 13:41:03.659 ThaliTest[438:678946] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliReplicationManager can call start without error

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/E2BA60ED-0DA1-4920-8EE8-91BAD48973C9/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,ok 113 starting event should occur in right order

,2016-02-02 13:41:04.088 ThaliTest[438:678946] jxcore: startBroadcasting
,2016-02-02 13:41:04.090 ThaliTest[438:678946] server: starting aCOtCSY3a8XpRhyjDFipHA.RIaljQ==
,2016-02-02 13:41:04.090 ThaliTest[438:678946] multipeer session: start timer: 0x156086a0
2016-02-02 13:41:04.090 ThaliTest[438:678946] THEMultipeerSession initialized peer aCOtCSY3a8XpRhyjDFipHA
2016-02-02 13:41:04.090 ThaliTest[438:678946] jxcore: startBroadcasting: success
ok 114 started event should occur in right order

,Now in TRM stop

State of this._isStarted: true
,
,ok 115 stopping event should occur in right order

About to call stopBroadcasting

,2016-02-02 13:41:04.092 ThaliTest[438:678946] jxcore: stopBroadcasting
2016-02-02 13:41:04.092 ThaliTest[438:678946] THEMultipeerSession stopping peer
2016-02-02 13:41:04.092 ThaliTest[438:678946] multipeer session: stop timer
,2016-02-02 13:41:04.094 ThaliTest[438:678946] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined

,ok 116 stopped event should occur in right order

,mux server bridge listener closed

,# setup

,# ThaliReplicationManager receives identity

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/E2BA60ED-0DA1-4920-8EE8-91BAD48973C9/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-02-02 13:41:04.285 ThaliTest[438:678946] jxcore: startBroadcasting
,2016-02-02 13:41:04.287 ThaliTest[438:678946] server: starting aCOtCSY3a8XpRhyjDFipHA.Je9phA==
,2016-02-02 13:41:04.288 ThaliTest[438:678946] multipeer session: start timer: 0x181b0190
,2016-02-02 13:41:04.289 ThaliTest[438:678946] THEMultipeerSession initialized peer aCOtCSY3a8XpRhyjDFipHA
,2016-02-02 13:41:04.292 ThaliTest[438:678946] jxcore: startBroadcasting: success
,ok 117 getDeviceIdentity should not return an error

,ok 118 deviceName should not be null

,Now in TRM stop

,State of this._isStarted: true

,About to call stopBroadcasting
,
,2016-02-02 13:41:04.295 ThaliTest[438:678946] jxcore: stopBroadcasting
,2016-02-02 13:41:04.295 ThaliTest[438:678946] THEMultipeerSession stopping peer
,2016-02-02 13:41:04.295 ThaliTest[438:678946] multipeer session: stop timer
,2016-02-02 13:41:04.296 ThaliTest[438:678946] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined

,mux server bridge listener closed

# setup

,# ThaliReplicationManager replicates database

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/E2BA60ED-0DA1-4920-8EE8-91BAD48973C9/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-02-02 13:41:06.747 ThaliTest[438:678946] jxcore: startBroadcasting
,2016-02-02 13:41:06.748 ThaliTest[438:678946] server: starting aCOtCSY3a8XpRhyjDFipHA.hbQPAA==
,2016-02-02 13:41:06.749 ThaliTest[438:678946] multipeer session: start timer: 0x1813f570
,2016-02-02 13:41:06.749 ThaliTest[438:678946] THEMultipeerSession initialized peer aCOtCSY3a8XpRhyjDFipHA
,2016-02-02 13:41:06.751 ThaliTest[438:678946] jxcore: startBroadcasting: success
,2016-02-02 13:41:06.752 ThaliTest[438:678697] client: found peer: 1454416845876.984./mImjQ==
,ok 119 getDeviceIdentity should not return an error

,ok 120 deviceName should not be null

,2016-02-02 13:41:10.776 ThaliTest[438:678697] client: found peer: _vfrhYzGzfT5MBj9M0TDvQ.rYAIlg==
,2016-02-02 13:41:10.803 ThaliTest[438:678946] jxcore: connect 1454416845876.984./mImjQ==
2016-02-02 13:41:10.803 ThaliTest[438:678946] client session: connect
2016-02-02 13:41:10.803 ThaliTest[438:678946] client session: stateChange:0->1 1454416845876.984./mImjQ==
,2016-02-02 13:41:10.806 ThaliTest[438:678946] jxcore: connect _vfrhYzGzfT5MBj9M0TDvQ.rYAIlg==
2016-02-02 13:41:10.806 ThaliTest[438:678946] client session: connect
2016-02-02 13:41:10.806 ThaliTest[438:678946] client session: stateChange:0->1 _vfrhYzGzfT5MBj9M0TDvQ.rYAIlg==
,ok 121 Should be able to put doc without error

,ok 122 1st change of local doc should contain local id

,2016-02-02 13:41:11.707 ThaliTest[438:678697] multipeer session: reset timer
2016-02-02 13:41:11.707 ThaliTest[438:678697] multipeer session: stop timer
,2016-02-02 13:41:11.708 ThaliTest[438:678697] multipeer session: start timer: 0x1813f570
,2016-02-02 13:41:11.709 ThaliTest[438:678697] server session: connect
,2016-02-02 13:41:11.709 ThaliTest[438:678697] server session: stateChange:0->1 _vfrhYzGzfT5MBj9M0TDvQ
,2016-02-02 13:41:11.717 ThaliTest[438:678697] server: accepting invitation _vfrhYzGzfT5MBj9M0TDvQ
,2016-02-02 13:41:12.939 ThaliTest[438:679650] client session: connected
2016-02-02 13:41:12.939 ThaliTest[438:679650] client session: stateChange:1->2 _vfrhYzGzfT5MBj9M0TDvQ.rYAIlg==
,2016-02-02 13:41:12.988 ThaliTest[438:679663] client session: fireConnectCallback: _vfrhYzGzfT5MBj9M0TDvQ.rYAIlg==
,2016-02-02 13:41:12.988 ThaliTest[438:679663] jxcore: connect: success
,2016-02-02 13:41:13.000 ThaliTest[438:678697] client: relay established
2016-02-02 13:41:13.001 ThaliTest[438:678697] client: new accepted socket: 0x174878c0
,client bridge: new client socket

,client bridge: new client socket

,2016-02-02 13:41:13.590 ThaliTest[438:679741] server session: connected
2016-02-02 13:41:13.590 ThaliTest[438:679741] server session: stateChange:1->2 _vfrhYzGzfT5MBj9M0TDvQ
,2016-02-02 13:41:13.596 ThaliTest[438:678697] server relay: connected (to port: 51310)
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

,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,2016-02-02 13:41:19.608 ThaliTest[438:678697] client: lost peer: 1454416845876.984./mImjQ==
2016-02-02 13:41:19.609 ThaliTest[438:678697] client session: onPeerLost: 1454416845876.984./mImjQ==
2016-02-02 13:41:19.609 ThaliTest[438:678697] client session:, onLinkFailure: 1454416845876.984./mImjQ==
2016-02-02 13:41:19.609 ThaliTest[438:678697] client session: disconnect
2016-02-02 13:41:19.609 ThaliTest[438:678697] client session: stateChange:1->0 1454416845876.984./mImjQ==
2016-02-02 13:41:19.610 ThaliTest[438:678697] client session: fireConnectCallback: 1454416845876.984./mImjQ==
2016-02-02 13:41:19.610 ThaliTest[438:678697] jxcore: connect: fail: Peer disconnected
,Connect error with error: Error: Peer disconnected

,2016-02-02 13:41:19.644 ThaliTest[438:678946] jxcore: disconnect
,2016-02-02 13:41:19.645 ThaliTest[438:678946] jxcore: disconnect: fail
,Disconnect error with error: Error: Not connected to specified peer

peerIdentifier not available 1454416845876.984./mImjQ==
,
,client bridge: socket closed

client bridge: socket closed

client bridge: socket closed

,client bridge: new client socket

,ok 123 1st change of remote doc should contain remote id

,ok 124 Can update remote doc without error

,null

,{ ok: true,
  id: '45ae50e1-9730-44c8-806c-f25902134f0f',
  rev: '2-cff0123f9ae756884e903c303091096d' }

,client bridge: new client socket

,ok 125 Remote changes occur in strict order

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

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

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,ok 126 Local changes occur in strict order

,ok 127 2nd change of local doc should contain remote id

,# setup

,client bridge: socket closed

,client bridge: socket closed
,
,client bridge: new client socket

,client bridge: new client socket

,client bridge: new client socket

,Now in TRM stop

State of this._isStarted: true
,
About to call stopBroadcasting

,2016-02-02 13:41:24.580 ThaliTest[438:678946] jxcore: stopBroadcasting
,2016-02-02 13:41:24.581 ThaliTest[438:678946] THEMultipeerSession stopping peer
,2016-02-02 13:41:24.581 ThaliTest[438:678946] multipeer session: stop timer
,2016-02-02 13:41:24.582 ThaliTest[438:678946] client session: disconnect
2016-02-02 13:41:24.582 ThaliTest[438:678946] client session: stateChange:2->0 _vfrhYzGzfT5MBj9M0TDvQ.rYAIlg==
,2016-02-02 13:41:24.587 ThaliTest[438:678946] server session: disconnect
2016-02-02 13:41:24.588 ThaliTest[438:678946] server session: stateChange:2->0 _vfrhYzGzfT5MBj9M0TDvQ
,2016-02-02 13:41:24.604 ThaliTest[438:678946] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined
,
,# After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

,incoming client socket error Error: read ECONNRESET

mux server bridge listener closed

,client bridge: socket closed

server bridge: socket closed
,
,# teardown

,client bridge: socket closed

,client bridge: socket closed

,appEnteredForeground wasn't registered

,appEnteringBackground wasn't registered


```
