#### Test 5841644866d9c0e_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5841644866d9c0e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/1A6B4562-9C92-498B-BB31-799356AA57EB/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/1A6B4562-9C92-498B-BB31-799356AA57EB/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5841644866d9c0e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5841644866d9c0e/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/4F3A42F6-D532-47C6-9188-14C7E5445697/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52884"
,(lldb)     command script import "/tmp/1A6B4562-9C92-498B-BB31-799356AA57EB/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-09 13:08:15.746 ThaliTest[1069:1746708] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/97494474-2E07-4E3A-8A23-40F21ACBE4B5/Library/Cookies/Cookies.binarycookies
,2016-02-09 13:08:16.113 ThaliTest[1069:1746708] Apache Cordova native platform version 4.0.1 is starting.
,2016-02-09 13:08:16.114 ThaliTest[1069:1746708] Multi-tasking -> Device: YES, App: YES
,2016-02-09 13:08:16.133 ThaliTest[1069:1746708] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-09 13:08:18.221 ThaliTest[1069:1746708] Using UIWebView
,2016-02-09 13:08:18.230 ThaliTest[1069:1746708] [CDVTimer][handleopenurl] 0.406981ms
,2016-02-09 13:08:18.237 ThaliTest[1069:1746708] [CDVTimer][intentandnavigationfilter] 6.579995ms
,2016-02-09 13:08:18.238 ThaliTest[1069:1746708] [CDVTimer][gesturehandler] 0.326991ms
,2016-02-09 13:08:18.238 ThaliTest[1069:1746708] [CDVTimer][TotalPluginStartup] 8.913994ms
,2016-02-09 13:08:25.651 ThaliTest[1069:1746708] Resetting plugins due to page load.
,2016-02-09 13:08:29.380 ThaliTest[1069:1746708] Finished load of: file:///var/mobile/Containers/Bundle/Application/4F3A42F6-D532-47C6-9188-14C7E5445697/ThaliTest.app/www/index.html
,2016-02-09 13:08:29.581 ThaliTest[1069:1746708] JXcore Cordova plugin initializing
,2016-02-09 13:08:29.581 ThaliTest[1069:1746954] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4F3A42F6-D532-47C6-9188-14C7E5445697/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4F3A42F6-D532-47C6-9188-14C7E5445697/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4F3A42F6-D532-47C6-9188-14C7E5445697/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4F3A42F6-D532-47C6-9188-14C7E5445697/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4F3A42F6-D532-47C6-9188-14C7E5445697/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4F3A42F6-D532-47C6-9188-14C7E5445697/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4F3A42F6-D532-47C6-9188-14C7E5445697/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4F3A42F6-D532-47C6-9188-14C7E5445697/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4F3A42F6-D532-47C6-9188-14C7E5445697/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

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

,2016-02-09 13:17:07.427 ThaliTest[1069:1746954] jxcore: startBroadcasting
,2016-02-09 13:17:07.444 ThaliTest[1069:1746954] server: starting 1455020227426.1069.DokuBA==
,2016-02-09 13:17:07.445 ThaliTest[1069:1746954] multipeer session: start timer: 0x1754eb20
2016-02-09 13:17:07.446 ThaliTest[1069:1746954] THEMultipeerSession initialized peer 1455020227426.1069
,2016-02-09 13:17:07.447 ThaliTest[1069:1746954] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error

2016-02-09 13:17:07.452 ThaliTest[1069:1746954] jxcore: stopBroadcasting
2016-02-09 13:17:07.452 ThaliTest[1069:1746954] THEMultipeerSession stopping peer
2016-02-09 13:17:07.452 ThaliTest[1,069:1746954] multipeer session: stop timer
2016-02-09 13:17:07.453 ThaliTest[1069:1746954] jxcore: stopBroadcasting: success
ok 64 Should be able to call stopBroadcasting without error

,2016-02-09 13:17:07.455 ThaliTest[1069:1746954] jxcore: startBroadcasting
,2016-02-09 13:17:07.459 ThaliTest[1069:1746954] server: starting 1455020227455.1069.o+dMvQ==
2016-02-09 13:17:07.460 ThaliTest[1069:1746954] multipeer session: start timer: 0x174e2370
2016-02-09 13:17:07.461 ThaliTest[1069:1746954] THEMultipeerSession initialized peer 1455020227455.1069
,2016-02-09 13:17:07.461 ThaliTest[1069:1746954] jxcore: startBroadcasting: success
,ok 65 Should be able to call startBroadcasting without error

2016-02-09 13:17:07.465 ThaliTest[1069:1746954] jxcore: stopBroadcasting
2016-02-09 13:17:07.465 ThaliTest[1069:1746954] THEMultipeerSession stopping peer
2016-02-09 13:17:07.465 ThaliTest[1069:1746954] multipeer session: stop timer
,2016-02-09 13:17:07.466 ThaliTest[1069:1746954] jxcore: stopBroadcasting: success
,ok 66 Should be able to call stopBroadcasting without error

,2016-02-09 13:17:07.469 ThaliTest[1069:1746954] jxcore: startBroadcasting
,2016-02-09 13:17:07.475 ThaliTest[1069:1746954] server: starting 1455020227468.1069.6oJcLQ==
2016-02-09 13:17:07.476 ThaliTest[1069:1746954] multipeer session: start timer: 0x174e3010
2016-02-09 13:17:07.476 ThaliTest[1069:1746954] THEMultipeerSession in,itialized peer 1455020227468.1069
2016-02-09 13:17:07.477 ThaliTest[1069:1746954] jxcore: startBroadcasting: success
ok 67 Should be able to call startBroadcasting without error

2016-02-09 13:17:07.479 ThaliTest[1069:1746954] jxcore: stopBroadcasting
2016-02-09 13:17:07.479 ThaliTest[1069:1746954] THEMultipeerSession stopping peer
,2016-02-09 13:17:07.479 ThaliTest[1069:1746954] multipeer session: stop timer
2016-02-09 13:17:07.484 ThaliTest[1069:1746954] jxcore: stopBroadcasting: success
,ok 68 Should be able to call stopBroadcasting without error

2016-02-09 13:17:07.486 ThaliTest[1069:1746954] jxcore: startBroadcasting
,2016-02-09 13:17:07.492 ThaliTest[1069:1746954] server: starting 1455020227485.1069./a5jPQ==
2016-02-09 13:17:07.494 ThaliTest[1069:1746954] multipeer session: start timer: 0x1829a540
2016-02-09 13:17:07.494 ThaliTest[1069:1746954] THEMultipeerSession in,itialized peer 1455020227485.1069
2016-02-09 13:17:07.496 ThaliTest[1069:1746954] jxcore: startBroadcasting: success
ok 69 Should be able to call startBroadcasting without error

,2016-02-09 13:17:07.499 ThaliTest[1069:1746954] jxcore: stopBroadcasting
2016-02-09 13:17:07.500 ThaliTest[1069:1746954] THEMultipeerSession stopping peer
2016-02-09 13:17:07.500 ThaliTest[1069:1746954] multipeer session: stop timer
2016-02-09 13:17:07.500 ThaliTest[1069:1746954] jxcore: stopBroadcasting: success
,ok 70 Should be able to call stopBroadcasting without error

,2016-02-09 13:17:07.502 ThaliTest[1069:1746954] jxcore: startBroadcasting
,2016-02-09 13:17:07.508 ThaliTest[1069:1746954] server: starting 1455020227502.1069.Gg8GZA==
2016-02-09 13:17:07.509 ThaliTest[1069:1746954] multipeer session: start timer: 0x1829b8e0
2016-02-09 13:17:07.509 ThaliTest[1069:1746954] THEMultipeerSession initialized peer 1455020227502.1069
2016-02-09 13:17:07.509 ThaliTest[1069:1746954] jxcore: startBroadcasting: success
,ok 71 Should be able to call startBroadcasting without error

2016-02-09 13:17:07.512 ThaliTest[1069:1746954] jxcore: stopBroadcasting
2016-02-09 13:17:07.512 ThaliTest[1069:1746954] THEMultipeerSession stopping peer
2016-02-09 13:17:07.512 ThaliTest[1069:1746954] multipeer session: stop timer
2016-02-09 13:17:07.513 ThaliTest[1069:1746954] jxcore: stopBroadcasting: success
,ok 72 Should be able to call stopBroadcasting without error

,2016-02-09 13:17:07.515 ThaliTest[1069:1746954] jxcore: startBroadcasting
,2016-02-09 13:17:07.518 ThaliTest[1069:1746954] server: starting 1455020227514.1069.Hh+jDw==
,2016-02-09 13:17:07.518 ThaliTest[1069:1746954] multipeer session: start timer: 0x1829c2b0
2016-02-09 13:17:07.519 ThaliTest[1069:1746954] THEMultipeerSession initialized peer 1455020227514.1069
2016-02-09 13:17:07.519 ThaliTest[1069:1746954] jxcore: startBroadcasting: success
ok 73 Should be able to call startBroadcasting without error

,2016-02-09 13:17:07.520 ThaliTest[1069:1746954] jxcore: stopBroadcasting
2016-02-09 13:17:07.522 ThaliTest[1069:1746954] THEMultipeerSession stopping peer
2016-02-09 13:17:07.522 ThaliTest[1069:1746954] multipeer session: stop timer
2016-02-09 13:17:07.523 ThaliTest[1069:1746954] jxcore: stopBroadcasting: success
ok 74 Should be able to call stopBroadcasting without error

,2016-02-09 13:17:07.524 ThaliTest[1069:1746954] jxcore: startBroadcasting
,2016-02-09 13:17:07.529 ThaliTest[1069:1746954] server: starting 1455020227524.1069.XbdDnA==
2016-02-09 13:17:07.530 ThaliTest[1069:1746954] multipeer session: start timer: 0x172c31c0
2016-02-09 13:17:07.530 ThaliTest[1069:1746954] THEMultipeerSession initialized peer 1455020227524.1069
2016-02-09 13:17:07.530 ThaliTest[1069:1746954] jxcore: startBroadcasting: success
ok 75 Should be able to call startBroadcasting without error

,2016-02-09 13:17:07.532 ThaliTest[1069:1746954] jxcore: stopBroadcasting
2016-02-09 13:17:07.532 ThaliTest[1069:1746954] THEMultipeerSession stopping peer
2016-02-09 13:17:07.533 ThaliTest[1069:1746954] multipeer session: stop timer
,2016-02-09 13:17:07.533 ThaliTest[1069:1746954] jxcore: stopBroadcasting: success
,ok 76 Should be able to call stopBroadcasting without error

2016-02-09 13:17:07.535 ThaliTest[1069:1746954] jxcore: startBroadcasting
,2016-02-09 13:17:07.540 ThaliTest[1069:1746954] server: starting 1455020227535.1069.G1sulQ==
,2016-02-09 13:17:07.541 ThaliTest[1069:1746954] multipeer session: start timer: 0x174e3870
,2016-02-09 13:17:07.542 ThaliTest[1069:1746954] THEMultipeerSession initialized peer 1455020227535.1069
,2016-02-09 13:17:07.544 ThaliTest[1069:1746954] jxcore: startBroadcasting: success
,ok 77 Should be able to call startBroadcasting without error
,
,2016-02-09 13:17:07.547 ThaliTest[1069:1746954] jxcore: stopBroadcasting
,2016-02-09 13:17:07.548 ThaliTest[1069:1746954] THEMultipeerSession stopping peer
2016-02-09 13:17:07.548 ThaliTest[1069:1746954] multipeer session: stop timer
,2016-02-09 13:17:07.549 ThaliTest[1069:1746954] jxcore: stopBroadcasting: success
,ok 78 Should be able to call stopBroadcasting without error

,2016-02-09 13:17:07.553 ThaliTest[1069:1746954] jxcore: startBroadcasting
,2016-02-09 13:17:07.556 ThaliTest[1069:1746954] server: starting 1455020227552.1069.VOGcng==
,2016-02-09 13:17:07.557 ThaliTest[1069:1746954] multipeer session: start timer: 0x1829d2c0
,2016-02-09 13:17:07.559 ThaliTest[1069:1746954] THEMultipeerSession initialized peer 1455020227552.1069
,2016-02-09 13:17:07.560 ThaliTest[1069:1746954] jxcore: startBroadcasting: success
,ok 79 Should be able to call startBroadcasting without error

,2016-02-09 13:17:07.563 ThaliTest[1069:1746954] jxcore: stopBroadcasting
2016-02-09 13:17:07.563 ThaliTest[1069:1746954] THEMultipeerSession stopping peer
2016-02-09 13:17:07.563 ThaliTest[1069:1746954] multipeer session: stop timer
2016-02-09 13:17:07.563 ThaliTest[1069:1746954] jxcore: stopBroadcasting: success
,ok 80 Should be able to call stopBroadcasting without error
,
,2016-02-09 13:17:07.568 ThaliTest[1069:1746954] jxcore: startBroadcasting
,2016-02-09 13:17:07.570 ThaliTest[1069:1746954] server: starting 1455020227567.1069.J79N+w==
,2016-02-09 13:17:07.571 ThaliTest[1069:1746954] multipeer session: start timer: 0x18540dd0
,2016-02-09 13:17:07.573 ThaliTest[1069:1746954] THEMultipeerSession initialized peer 1455020227567.1069
,2016-02-09 13:17:07.574 ThaliTest[1069:1746954] jxcore: startBroadcasting: success
,ok 81 Should be able to call startBroadcasting without error

,2016-02-09 13:17:07.578 ThaliTest[1069:1746954] jxcore: stopBroadcasting
,2016-02-09 13:17:07.578 ThaliTest[1069:1746954] THEMultipeerSession stopping peer
,2016-02-09 13:17:07.579 ThaliTest[1069:1746954] multipeer session: stop timer
,2016-02-09 13:17:07.581 ThaliTest[1069:1746954] jxcore: stopBroadcasting: success
,ok 82 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,# teardown

,2016-02-09 13:17:13.734 ThaliTest[1069:1746954] jxcore: startBroadcasting
,2016-02-09 13:17:13.738 ThaliTest[1069:1746954] server: starting 1455020233734.1069.Dv49qg==
,2016-02-09 13:17:13.739 ThaliTest[1069:1746954] multipeer session: start timer: 0x1829d1a0
2016-02-09 13:17:13.740 ThaliTest[1069:1746954] THEMultipeerSession initialized peer 1455020233734.1069
2016-02-09 13:17:13.740 ThaliTest[1069:1746954] jxcore: startBroadcasting: success
,ok 83 Should be able to call startBroadcasting without error

2016-02-09 13:17:13.743 ThaliTest[1069:1746954] jxcore: startBroadcasting
2016-02-09 13:17:13.743 ThaliTest[1069:1746954] jxcore: startBroadcasting: failure
,ok 84 Cannot call startBroadcasting twice

2016-02-09 13:17:13.748 ThaliTest[1069:1746954] jxcore: stopBroadcasting
,2016-02-09 13:17:13.748 ThaliTest[1069:1746954] THEMultipeerSession stopping peer
,2016-02-09 13:17:13.749 ThaliTest[1069:1746954] multipeer session: stop timer
,2016-02-09 13:17:13.753 ThaliTest[1069:1746954] jxcore: stopBroadcasting: success
,ok 85 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on connection to bad peer

,# teardown

,2016-02-09 13:17:40.780 ThaliTest[1069:1746954] jxcore: startBroadcasting
,2016-02-09 13:17:40.783 ThaliTest[1069:1746954] server: starting 1455020260779.1069.YaSYDw==
,2016-02-09 13:17:40.784 ThaliTest[1069:1746954] multipeer session: start timer: 0x174c0eb0
,2016-02-09 13:17:40.785 ThaliTest[1069:1746954] THEMultipeerSession initialized peer 1455020260779.1069
,2016-02-09 13:17:40.785 ThaliTest[1069:1746954] jxcore: startBroadcasting: success
,ok 86 Should be able to call startBroadcasting without error

2016-02-09 13:17:40.788 ThaliTest[1069:1746954] jxcore: connect foobar
2016-02-09 13:17:40.788 ThaliTest[1069:1746954] client: unknown peer foobar
2016-02-09 13:17:40.788 ThaliTest[1069:1746954] jxcore: connect: fail: Unknown peer
,ok 87 Should not connect to a bad peer

2016-02-09 13:17:40.792 ThaliTest[1069:1746954] jxcore: stopBroadcasting
,2016-02-09 13:17:40.793 ThaliTest[1069:1746954] THEMultipeerSession stopping peer
,2016-02-09 13:17:40.794 ThaliTest[1069:1746954] multipeer session: stop timer
,2016-02-09 13:17:40.795 ThaliTest[1069:1746954] jxcore: stopBroadcasting: success
ok 88 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on disconnect to bad peer

,# teardown

,2016-02-09 13:17:48.272 ThaliTest[1069:1746954] jxcore: startBroadcasting
,2016-02-09 13:17:48.275 ThaliTest[1069:1746954] server: starting 1455020268272.1069.ccYCLw==
,2016-02-09 13:17:48.276 ThaliTest[1069:1746954] multipeer session: start timer: 0x175414d0
,2016-02-09 13:17:48.277 ThaliTest[1069:1746954] THEMultipeerSession initialized peer 1455020268272.1069
2016-02-09 13:17:48.278 ThaliTest[1069:1746954] jxcore: startBroadcasting: success
,ok 89 Should be able to call startBroadcasting without error

,2016-02-09 13:17:48.281 ThaliTest[1069:1746954] jxcore: disconnect
,2016-02-09 13:17:48.281 ThaliTest[1069:1746954] jxcore: disconnect: fail
,ok 90 Disconnect should fail to a non-existant peer 

,2016-02-09 13:17:48.286 ThaliTest[1069:1746954] jxcore: stopBroadcasting
2016-02-09 13:17:48.286 ThaliTest[1069:1746954] THEMultipeerSession stopping peer
2016-02-09 13:17:48.287 ThaliTest[1069:1746954] multipeer session: stop timer
2016-02-09 13:17:48.,287 ThaliTest[1069:1746954] jxcore: stopBroadcasting: success
,ok 91 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter can discover and connect to peers

,# teardown

,2016-02-09 13:17:57.385 ThaliTest[1069:1746954] jxcore: startBroadcasting
,2016-02-09 13:17:57.389 ThaliTest[1069:1746954] server: starting 1455020277385.1069.XMv4Kw==
,2016-02-09 13:17:57.390 ThaliTest[1069:1746954] multipeer session: start timer: 0x1753fa20
,2016-02-09 13:17:57.390 ThaliTest[1069:1746954] THEMultipeerSession initialized peer 1455020277385.1069
2016-02-09 13:17:57.391 ThaliTest[1069:1746954] jxcore: startBroadcasting: success
,ok 92 Should be able to call startBroadcasting without error

,2016-02-09 13:18:08.421 ThaliTest[1069:1746708] client: found peer: 1455020283271.2819.w22JdQ==
,2016-02-09 13:18:08.424 ThaliTest[1069:1746954] jxcore: connect 1455020283271.2819.w22JdQ==
,2016-02-09 13:18:08.425 ThaliTest[1069:1746954] client session: connect
,2016-02-09 13:18:08.425 ThaliTest[1069:1746954] client session: stateChange:0->1 1455020283271.2819.w22JdQ==
,2016-02-09 13:18:09.134 ThaliTest[1069:1746708] multipeer session: reset timer
2016-02-09 13:18:09.134 ThaliTest[1069:1746708] multipeer session: stop timer
2016-02-09 13:18:09.134 ThaliTest[1069:1746708] multipeer session: start timer: 0x1753fa20
2016-02-09 13:18:09.135 ThaliTest[1069:1746708] server session: connect
2016-02-09 13:18:09.135 ThaliTest[1069:1746708] server session: stateChange:0->1 1455020283271.2819
,2016-02-09 13:18:09.142 ThaliTest[1069:1746708] server: accepting invitation 1455020283271.2819
,2016-02-09 13:18:11.912 ThaliTest[1069:1748041] client session: connected
2016-02-09 13:18:11.913 ThaliTest[1069:1748041] client session: stateChange:1->2 1455020283271.2819.w22JdQ==
,2016-02-09 13:18:11.918 ThaliTest[1069:1748041] client session: fireConnectCallback: 1455020283271.2819.w22JdQ==
2016-02-09 13:18:11.919 ThaliTest[1069:1748041] jxcore: connect: success
,ok 93 Should be able to connect without error

,ok 94 Port should be within range

,2016-02-09 13:18:11.923 ThaliTest[1069:1746954] jxcore: disconnect
,2016-02-09 13:18:11.923 ThaliTest[1069:1746954] client session: disconnectFromPeer: 1455020283271.2819.w22JdQ==
,2016-02-09 13:18:11.924 ThaliTest[1069:1746954] client session: disconnect
2016-02-09 13:18:11.925 ThaliTest[1069:1746954] client session: stateChange:2->0 1455020283271.2819.w22JdQ==
,2016-02-09 13:18:11.935 ThaliTest[1069:1746954] jxcore: disconnect: success
ok 95 Should be able to disconnect without error

,setting stopBroadcasting callback and ending test.

,# setup

,2016-02-09 13:18:12.108 ThaliTest[1069:1748062] server session: connected
,2016-02-09 13:18:12.109 ThaliTest[1069:1748062] server session: stateChange:1->2 1455020283271.2819
,2016-02-09 13:18:12.113 ThaliTest[1069:1746708] server relay: socket disconnected
2016-02-09 13:18:12.114 ThaliTest[1069:1746708] server relay: 0x182a4d30 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-09 13:18:12.156 ThaliTest[1069:1748062] server session: not connected 1455020283271.2819
,calling stopBroadcasting

,2016-02-09 13:18:12.442 ThaliTest[1069:1746954] jxcore: stopBroadcasting
,2016-02-09 13:18:12.443 ThaliTest[1069:1746954] THEMultipeerSession stopping peer
,2016-02-09 13:18:12.444 ThaliTest[1069:1746954] multipeer session: stop timer
,2016-02-09 13:18:12.445 ThaliTest[1069:1746954] server session: disconnect
2016-02-09 13:18:12.448 ThaliTest[1069:1746954] server session: stateChange:2->0 1455020283271.2819
,2016-02-09 13:18:12.450 ThaliTest[1069:1746954] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double connect

,# teardown

,2016-02-09 13:18:13.047 ThaliTest[1069:1746954] jxcore: startBroadcasting
,2016-02-09 13:18:13.050 ThaliTest[1069:1746954] server: starting 1455020293046.1069.9oddgg==
,2016-02-09 13:18:13.052 ThaliTest[1069:1746954] multipeer session: start timer: 0x1749a640
2016-02-09 13:18:13.053 ThaliTest[1069:1746954] THEMultipeerSession initialized peer 1455020293046.1069
2016-02-09 13:18:13.054 ThaliTest[1069:1746954] jxcore: startBroadcasting: success
,ok 96 Should be able to call startBroadcasting without error

,2016-02-09 13:18:13.569 ThaliTest[1069:1746708] client: found peer: 1455020283271.2819.w22JdQ==
,2016-02-09 13:18:13.571 ThaliTest[1069:1746954] jxcore: connect 1455020283271.2819.w22JdQ==
2016-02-09 13:18:13.572 ThaliTest[1069:1746954] client session: connect
2016-02-09 13:18:13.572 ThaliTest[1069:1746954] client session: stateChange:0->1 1455020283271.2819.w22JdQ==
,2016-02-09 13:18:14.168 ThaliTest[1069:1746708] client: lost peer: 1455020283271.2819.w22JdQ==
2016-02-09 13:18:14.168 ThaliTest[1069:1746708] client session: onPeerLost: 1455020283271.2819.w22JdQ==
,2016-02-09 13:18:14.168 ThaliTest[1069:1746708] client session: onLinkFailure: 1455020283271.2819.w22JdQ==
2016-02-09 13:18:14.170 ThaliTest[1069:1746708] client session: disconnect
2016-02-09 13:18:14.170 ThaliTest[1069:1746708] client session: stateChange:1->0 1455020283271.2819.w22JdQ==
2016-02-09 13:18:14.171 ThaliTest[1069:1746708] client session: fireConnectCallback: 1455020283271.2819.w22JdQ==
2016-02-09 13:18:14.171 ThaliTest[1069:1746708] jxcore: connect: fail: Peer disconnected
2016-02-09 13:,18:14.171 ThaliTest[1069:1746708] client: found peer: 1455020291171.2819.HjYL0w==
,2016-02-09 13:18:14.176 ThaliTest[1069:1746954] jxcore: connect 1455020291171.2819.HjYL0w==
,2016-02-09 13:18:14.177 ThaliTest[1069:1746954] client session: connect
,2016-02-09 13:18:14.177 ThaliTest[1069:1746954] client session: stateChange:0->1 1455020291171.2819.HjYL0w==
,2016-02-09 13:18:14.342 ThaliTest[1069:1746708] multipeer session: reset timer
2016-02-09 13:18:14.342 ThaliTest[1069:1746708] multipeer session: stop timer
2016-02-09 13:18:14.342 ThaliTest[1069:1746708] multipeer session: start timer: 0x1749a640
,2016-02-09 13:18:14.343 ThaliTest[1069:1746708] server session: connect
2016-02-09 13:18:14.343 ThaliTest[1069:1746708] server session: stateChange:0->1 1455020291171.2819
,2016-02-09 13:18:14.350 ThaliTest[1069:1746708] server: accepting invitation 1455020291171.2819
,2016-02-09 13:18:15.182 ThaliTest[1069:1746954] jxcore: connect 1455020283271.2819.w22JdQ==
2016-02-09 13:18:15.183 ThaliTest[1069:1746954] client: connect: unreachable 1455020283271.2819.w22JdQ==
,2016-02-09 13:18:15.183 ThaliTest[1069:1746954] jxcore: connect: fail: Peer unreachable
,2016-02-09 13:18:17.096 ThaliTest[1069:1748062] client session: connected
2016-02-09 13:18:17.097 ThaliTest[1069:1748062] client session: stateChange:1->2 1455020291171.2819.HjYL0w==
,2016-02-09 13:18:17.125 ThaliTest[1069:1748033] client session: fireConnectCallback: 1455020291171.2819.HjYL0w==
2016-02-09 13:18:17.125 ThaliTest[1069:1748033] jxcore: connect: success
ok 97 Should be able to connect without error

ok 98 Port should b,e within range

2016-02-09 13:18:17.129 ThaliTest[1069:1746954] jxcore: connect 1455020291171.2819.HjYL0w==
2016-02-09 13:18:17.129 ThaliTest[1069:1746954] client: already connect(ing/ed) to 1455020291171.2819.HjYL0w==
2016-02-09 13:18:17.130 ThaliTest,[1069:1746954] jxcore: connect: fail: Aleady connecting
ok 99 Should fail on double connect

,2016-02-09 13:18:17.132 ThaliTest[1069:1746954] jxcore: disconnect
2016-02-09 13:18:17.133 ThaliTest[1069:1746954] client session: disconnectFromPeer: 1455020291171.2819.HjYL0w==
,2016-02-09 13:18:17.133 ThaliTest[1069:1746954] client session: disconnect
,2016-02-09 13:18:17.134 ThaliTest[1069:1746954] client session: stateChange:2->0 1455020291171.2819.HjYL0w==
,2016-02-09 13:18:17.138 ThaliTest[1069:1748033] server session: connected
,2016-02-09 13:18:17.139 ThaliTest[1069:1748033] server session: stateChange:1->2 1455020291171.2819
,2016-02-09 13:18:17.149 ThaliTest[1069:1746708] server relay: socket disconnected
2016-02-09 13:18:17.150 ThaliTest[1069:1746708] server relay: 0x1771cfd0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-09 13:18:17.217 ThaliTest[1069:1746954] jxcore: disconnect: success
,ok 100 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,calling stopBroadcasting

,2016-02-09 13:18:17.240 ThaliTest[1069:1746954] jxcore: stopBroadcasting
,2016-02-09 13:18:17.241 ThaliTest[1069:1746954] THEMultipeerSession stopping peer
,2016-02-09 13:18:17.242 ThaliTest[1069:1746954] multipeer session: stop timer
2016-02-09 13:18:17.243 ThaliTest[1069:1746954] server session: disconnect
2016-02-09 13:18:17.243 ThaliTest[1069:1746954] server session: stateChange:2->0 1455020291171.2819
,2016-02-09 13:18:17.264 ThaliTest[1069:1746954] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# setup

,# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,# teardown

,2016-02-09 13:18:17.767 ThaliTest[1069:1746954] jxcore: startBroadcasting
,2016-02-09 13:18:17.770 ThaliTest[1069:1746954] server: starting 1455020297766.1069.PYsssg==
,2016-02-09 13:18:17.771 ThaliTest[1069:1746954] multipeer session: start timer: 0x182a7260
,2016-02-09 13:18:17.771 ThaliTest[1069:1746954] THEMultipeerSession initialized peer 1455020297766.1069
2016-02-09 13:18:17.772 ThaliTest[1069:1746954] jxcore: startBroadcasting: success
,ok 101 Should be able to call startBroadcasting without error

,2016-02-09 13:18:18.357 ThaliTest[1069:1746708] client: found peer: 1455020291171.2819.HjYL0w==
,2016-02-09 13:18:18.359 ThaliTest[1069:1746954] jxcore: connect 1455020291171.2819.HjYL0w==
2016-02-09 13:18:18.360 ThaliTest[1069:1746954] client session: connect
2016-02-09 13:18:18.360 ThaliTest[1069:1746954] client session: stateChange:0->1 1455020291171.2819.HjYL0w==
,2016-02-09 13:18:18.976 ThaliTest[1069:1746708] multipeer session: reset timer
,2016-02-09 13:18:18.976 ThaliTest[1069:1746708] multipeer session: stop timer
,2016-02-09 13:18:18.976 ThaliTest[1069:1746708] multipeer session: start timer: 0x182a7260
2016-02-09 13:18:18.977 ThaliTest[1069:1746708] server session: connect
,2016-02-09 13:18:18.977 ThaliTest[1069:1746708] server session: stateChange:0->1 1455020296324.2819
,2016-02-09 13:18:18.984 ThaliTest[1069:1746708] server: accepting invitation 1455020296324.2819
,2016-02-09 13:18:19.004 ThaliTest[1069:1746708] client: found peer: 1455020296324.2819.TAsZlw==
2016-02-09 13:18:19.006 ThaliTest[1069:1746954] jxcore: connect 1455020296324.2819.TAsZlw==
2016-02-09 13:18:19.006 ThaliTest[1069:1746954] client session: connect
2016-02-09 13:18:19.006 ThaliTest[1069:1746954] client session: stateChange:0->1 1455020296324.2819.TAsZlw==
,2016-02-09 13:18:22.005 ThaliTest[1069:1748041] server session: connected
2016-02-09 13:18:22.005 ThaliTest[1069:1748041] server session: stateChange:1->2 1455020296324.2819
,2016-02-09 13:18:22.016 ThaliTest[1069:1746708] server relay: socket disconnected
,2016-02-09 13:18:22.016 ThaliTest[1069:1746708] server relay: 0x17791d30 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection ,refused} 
,2016-02-09 13:18:22.082 ThaliTest[1069:1748062] server session: not connected 1455020296324.2819
,2016-02-09 13:18:22.398 ThaliTest[1069:1748061] client session: connected
2016-02-09 13:18:22.399 ThaliTest[1069:1748061] client session: stateChange:1->2 1455020296324.2819.TAsZlw==
,2016-02-09 13:18:22.505 ThaliTest[1069:1748061] client session: fireConnectCallback: 1455020296324.2819.TAsZlw==
2016-02-09 13:18:22.506 ThaliTest[1069:1748061] jxcore: connect: success
,ok 102 Should be able to connect without error

,ok 103 Port should be within range

,2016-02-09 13:18:22.510 ThaliTest[1069:1746954] jxcore: disconnect
,2016-02-09 13:18:22.510 ThaliTest[1069:1746954] client session: disconnectFromPeer: 1455020296324.2819.TAsZlw==
,2016-02-09 13:18:22.511 ThaliTest[1069:1746954] client session: disconnect
,2016-02-09 13:18:22.512 ThaliTest[1069:1746954] client session: stateChange:2->0 1455020296324.2819.TAsZlw==
,2016-02-09 13:18:22.522 ThaliTest[1069:1746954] jxcore: disconnect: success
ok 104 Should be able to disconnect without error

2016-02-09 13:18:22.525 ThaliTest[1069:1746954] jxcore: disconnect
2016-02-09 13:18:22.525 ThaliTest[1069:1746954] jxcore: di,sconnect: fail
ok 105 Disconnect should fail 

,setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-02-09 13:18:22.919 ThaliTest[1069:1746954] jxcore: stopBroadcasting
,2016-02-09 13:18:22.919 ThaliTest[1069:1746954] THEMultipeerSession stopping peer
,2016-02-09 13:18:22.920 ThaliTest[1069:1746954] multipeer session: stop timer
,2016-02-09 13:18:22.921 ThaliTest[1069:1746954] client session: disconnect
2016-02-09 13:18:22.922 ThaliTest[1069:1746954] client session: stateChange:1->0 1455020291171.2819.HjYL0w==
,2016-02-09 13:18:22.923 ThaliTest[1069:1746954] server session: disconnect
2016-02-09 13:18:22.924 ThaliTest[1069:1746954] server session: stateChange:2->0 1455020296324.2819
,2016-02-09 13:18:23.781 ThaliTest[1069:1746954] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can connect and send data

,# teardown

,echo server started on port: 55714

,2016-02-09 13:18:24.597 ThaliTest[1069:1746954] jxcore: startBroadcasting
,2016-02-09 13:18:24.598 ThaliTest[1069:1746954] server: starting 1455020304597.1069.F5tE5A==
,2016-02-09 13:18:24.598 ThaliTest[1069:1746954] multipeer session: start timer: 0x17679c80
2016-02-09 13:18:24.599 ThaliTest[1069:1746954] THEMultipeerSession initialized peer 1455020304597.1069
,2016-02-09 13:18:24.599 ThaliTest[1069:1746954] jxcore: startBroadcasting: success
ok 106 Should be able to call startBroadcasting without error

,2016-02-09 13:18:26.190 ThaliTest[1069:1746708] multipeer session: reset timer
2016-02-09 13:18:26.190 ThaliTest[1069:1746708] multipeer session: stop timer
,2016-02-09 13:18:26.190 ThaliTest[1069:1746708] multipeer session: start timer: 0x17679c80
,2016-02-09 13:18:26.192 ThaliTest[1069:1746708] server session: connect
2016-02-09 13:18:26.192 ThaliTest[1069:1746708] server session: stateChange:0->1 1455020303921.2819
,2016-02-09 13:18:26.199 ThaliTest[1069:1746708] server: accepting invitation 1455020303921.2819
,2016-02-09 13:18:26.887 ThaliTest[1069:1746708] client: found peer: 1455020303921.2819.aUWkkg==
,2016-02-09 13:18:26.889 ThaliTest[1069:1746954] jxcore: connect 1455020303921.2819.aUWkkg==
2016-02-09 13:18:26.890 ThaliTest[1069:1746954] client session: connect
2016-02-09 13:18:26.890 ThaliTest[1069:1746954] client session: stateChange:0->1 1455020303921.2819.aUWkkg==
,2016-02-09 13:18:29.405 ThaliTest[1069:1748103] server session: connected
2016-02-09 13:18:29.405 ThaliTest[1069:1748103] server session: stateChange:1->2 1455020303921.2819
,2016-02-09 13:18:29.472 ThaliTest[1069:1746708] server relay: connected (to port: 55714)
,2016-02-09 13:18:30.587 ThaliTest[1069:1748033] server session: not connected 1455020303921.2819
,2016-02-09 13:18:31.324 ThaliTest[1069:1748033] client session: connected
2016-02-09 13:18:31.324 ThaliTest[1069:1748033] client session: stateChange:1->2 1455020303921.2819.aUWkkg==
,2016-02-09 13:18:31.545 ThaliTest[1069:1748041] client session: fireConnectCallback: 1455020303921.2819.aUWkkg==
2016-02-09 13:18:31.546 ThaliTest[1069:1748041] jxcore: connect: success
,ok 107 Should be able to connect without error

,ok 108 Port should be within range

,2016-02-09 13:18:31.552 ThaliTest[1069:1746708] client: relay established
2016-02-09 13:18:31.553 ThaliTest[1069:1746708] client: new accepted socket: 0x174e0870
,data in 1095

,data in 2190

,data in 3285

,data in 4380

,data in 28470

,data in 32850

,data in 33945

,data in 43161

,data in 104025

,data in 108334

,data in 124759

,data in 131072

,ok 109 the test messages should be equal

,2016-02-09 13:18:32.941 ThaliTest[1069:1746954] jxcore: disconnect
,2016-02-09 13:18:32.942 ThaliTest[1069:1746954] client session: disconnectFromPeer: 1455020303921.2819.aUWkkg==
,2016-02-09 13:18:32.942 ThaliTest[1069:1746954] client session: disconnect
,2016-02-09 13:18:32.943 ThaliTest[1069:1746954] client session: stateChange:2->0 1455020303921.2819.aUWkkg==
,2016-02-09 13:18:32.954 ThaliTest[1069:1746954] jxcore: disconnect: success
,ok 110 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-02-09 13:18:32.980 ThaliTest[1069:1746954] jxcore: stopBroadcasting
,2016-02-09 13:18:32.981 ThaliTest[1069:1746954] THEMultipeerSession stopping peer
,2016-02-09 13:18:32.981 ThaliTest[1069:1746954] multipeer session: stop timer
2016-02-09 13:18:32.982 ThaliTest[1069:1746954] server session: disconnect
,2016-02-09 13:18:32.983 ThaliTest[1069:1746954] server session: stateChange:2->0 1455020303921.2819
,2016-02-09 13:18:32.993 ThaliTest[1069:1746954] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter handles socket disconnect correctly

,# teardown

,echo server started on port: 55722

,2016-02-09 13:18:34.027 ThaliTest[1069:1746954] jxcore: startBroadcasting
,2016-02-09 13:18:34.029 ThaliTest[1069:1746954] server: starting 1455020314026.1069.hXy/gA==
2016-02-09 13:18:34.030 ThaliTest[1069:1746954] multipeer session: start timer: 0x174ab0f0
,2016-02-09 13:18:34.030 ThaliTest[1069:1746954] THEMultipeerSession initialized peer 1455020314026.1069
2016-02-09 13:18:34.030 ThaliTest[1069:1746954] jxcore: startBroadcasting: success
ok 111 Should be able to call startBroadcasting without error

,2016-02-09 13:18:34.099 ThaliTest[1069:1746708] client: found peer: 1455020303921.2819.aUWkkg==
,[{"peerIdentifier":"1455020303921.2819.aUWkkg==","peerName":"(null)","peerAvailable":true}]

,2016-02-09 13:18:34.103 ThaliTest[1069:1746954] jxcore: connect 1455020303921.2819.aUWkkg==
,2016-02-09 13:18:34.104 ThaliTest[1069:1746954] client session: connect
,2016-02-09 13:18:34.105 ThaliTest[1069:1746954] client session: stateChange:0->1 1455020303921.2819.aUWkkg==
,2016-02-09 13:18:35.241 ThaliTest[1069:1746708] multipeer session: reset timer
2016-02-09 13:18:35.242 ThaliTest[1069:1746708] multipeer session: stop timer
,2016-02-09 13:18:35.242 ThaliTest[1069:1746708] multipeer session: start timer: 0x174ab0f0
2016-02-09 13:18:35.243 ThaliTest[1069:1746708] server session: connect
2016-02-09 13:18:35.244 ThaliTest[1069:1746708] server session: stateChange:0->1 1455020312522.2819
,2016-02-09 13:18:35.251 ThaliTest[1069:1746708] server: accepting invitation 1455020312522.2819
,2016-02-09 13:18:35.303 ThaliTest[1069:1746708] client: found peer: 1455020312522.2819.yh5DEw==
[{"peerIdentifier":"1455020312522.2819.yh5DEw==","peerName":"(null)","peerAvailable":true}]

2016-02-09 13:18:35.304 ThaliTest[1069:1746954] jxcore: connect 1455020312522.2819.yh5DEw==
,2016-02-09 13:18:35.305 ThaliTest[1069:1746954] client session: connect
,2016-02-09 13:18:35.306 ThaliTest[1069:1746954] client session: stateChange:0->1 1455020312522.2819.yh5DEw==
,2016-02-09 13:18:37.195 ThaliTest[1069:1746708] client: lost peer: 1455020303921.2819.aUWkkg==
2016-02-09 13:18:37.196 ThaliTest[1069:1746708] client session: onPeerLost: 1455020303921.2819.aUWkkg==
2016-02-09 13:18:37.196 ThaliTest[1069:1746708] client ,session: onLinkFailure: 1455020303921.2819.aUWkkg==
2016-02-09 13:18:37.196 ThaliTest[1069:1746708] client session: disconnect
2016-02-09 13:18:37.196 ThaliTest[1069:1746708] client session: stateChange:1->0 1455020303921.2819.aUWkkg==
,2016-02-09 13:18:37.197 ThaliTest[1069:1746708] client session: fireConnectCallback: 1455020303921.2819.aUWkkg==
2016-02-09 13:18:37.197 ThaliTest[1069:1746708] jxcore: connect: fail: Peer disconnected
,[{"peerIdentifier":"1455020303921.2819.aUWkkg==","peerName":"(null)","peerAvailable":false}]

,2016-02-09 13:18:38.203 ThaliTest[1069:1746954] jxcore: connect 1455020303921.2819.aUWkkg==
,2016-02-09 13:18:38.204 ThaliTest[1069:1746954] client: connect: unreachable 1455020303921.2819.aUWkkg==
,2016-02-09 13:18:38.204 ThaliTest[1069:1746954] jxcore: connect: fail: Peer unreachable
,2016-02-09 13:18:38.856 ThaliTest[1069:1748041] server session: connected
2016-02-09 13:18:38.856 ThaliTest[1069:1748041] server session: stateChange:1->2 1455020312522.2819
,2016-02-09 13:18:38.857 ThaliTest[1069:1748194] client session: connected
2016-02-09 13:18:38.859 ThaliTest[1069:1748194] client session: stateChange:1->2 1455020312522.2819.yh5DEw==
,2016-02-09 13:18:38.863 ThaliTest[1069:1746708] server relay: connected (to port: 55722)
,2016-02-09 13:18:38.866 ThaliTest[1069:1748194] client session: fireConnectCallback: 1455020312522.2819.yh5DEw==
2016-02-09 13:18:38.867 ThaliTest[1069:1748194] jxcore: connect: success
,ok 112 Should be able to connect without error

ok 113 Port should be within range

ok 114 First connect should succeed

,2016-02-09 13:18:38.930 ThaliTest[1069:1746708] client: relay established
2016-02-09 13:18:38.930 ThaliTest[1069:1746708] client: new accepted socket: 0x1564c770
,ok 115 the test messages should be equal

,ok 116 First send should succeed

,2016-02-09 13:18:38.997 ThaliTest[1069:1746708] client: socket closed
,2016-02-09 13:18:38.998 ThaliTest[1069:1746708] client relay: socket disconnected
,2016-02-09 13:18:38.998 ThaliTest[1069:1746708] client relay: 0x1564c770 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-02-09 13:18:,38.998 ThaliTest[1069:1746708] client session: socket closed: 1455020312522.2819.yh5DEw==
2016-02-09 13:18:38.998 ThaliTest[1069:1746708] client session: onLinkFailure: 1455020312522.2819.yh5DEw==
,2016-02-09 13:18:38.999 ThaliTest[1069:1746708] client session: disconnect
2016-02-09 13:18:38.999 ThaliTest[1069:1746708] client session: stateChange:2->0 1455020312522.2819.yh5DEw==
,2016-02-09 13:18:39.012 ThaliTest[1069:1746708] client session: fireConnectionErrorEvent: 1455020312522.2819.yh5DEw==
,2016-02-09 13:18:39.017 ThaliTest[1069:1746954] jxcore: connect 1455020312522.2819.yh5DEw==
,2016-02-09 13:18:39.019 ThaliTest[1069:1746954] client session: connect
,2016-02-09 13:18:39.020 ThaliTest[1069:1746954] client session: stateChange:0->1 1455020312522.2819.yh5DEw==
,2016-02-09 13:18:39.036 ThaliTest[1069:1748103] server session: not connected 1455020312522.2819
,2016-02-09 13:18:39.105 ThaliTest[1069:1746708] multipeer session: reset timer
,2016-02-09 13:18:39.105 ThaliTest[1069:1746708] multipeer session: stop timer
,2016-02-09 13:18:39.105 ThaliTest[1069:1746708] multipeer session: start timer: 0x174ab0f0
2016-02-09 13:18:39.106 ThaliTest[1069:1746708] server: disconnecting to refresh session (1455020312522.2819)
,2016-02-09 13:18:39.106 ThaliTest[1069:1746708] server session: disconnect
,2016-02-09 13:18:39.107 ThaliTest[1069:1746708] server session: stateChange:2->0 1455020312522.2819
,2016-02-09 13:18:39.111 ThaliTest[1069:1746708] server session: connect
,2016-02-09 13:18:39.112 ThaliTest[1069:1746708] server session: stateChange:0->1 1455020312522.2819
,2016-02-09 13:18:39.122 ThaliTest[1069:1746708] server: accepting invitation 1455020312522.2819
,2016-02-09 13:18:43.672 ThaliTest[1069:1748041] server session: connected
2016-02-09 13:18:43.672 ThaliTest[1069:1748041] server session: stateChange:1->2 1455020312522.2819
,2016-02-09 13:18:43.677 ThaliTest[1069:1746708] server relay: connected (to port: 55722)
,2016-02-09 13:18:43.700 ThaliTest[1069:1748041] client session: connected
,2016-02-09 13:18:43.700 ThaliTest[1069:1748041] client session: stateChange:1->2 1455020312522.2819.yh5DEw==
,2016-02-09 13:18:43.704 ThaliTest[1069:1748041] client session: fireConnectCallback: 1455020312522.2819.yh5DEw==
,2016-02-09 13:18:43.705 ThaliTest[1069:1748041] jxcore: connect: success
,ok 117 Should be able to connect without error

,ok 118 Port should be within range

,ok 119 Second connect should succeed

,2016-02-09 13:18:43.739 ThaliTest[1069:1746708] client: relay established
2016-02-09 13:18:43.739 ThaliTest[1069:1746708] client: new accepted socket: 0x1821c270
,2016-02-09 13:18:44.508 ThaliTest[1069:1748103] server session: not connected 1455020312522.2819
,ok 120 the test messages should be equal

,ok 121 Second send should succeed

,# setup

,calling stopBroadcasting

,2016-02-09 13:18:44.958 ThaliTest[1069:1746954] jxcore: stopBroadcasting
,2016-02-09 13:18:44.959 ThaliTest[1069:1746954] THEMultipeerSession stopping peer
,2016-02-09 13:18:44.959 ThaliTest[1069:1746954] multipeer session: stop timer
,2016-02-09 13:18:44.960 ThaliTest[1069:1746954] client session: disconnect
2016-02-09 13:18:44.961 ThaliTest[1069:1746954] client session: stateChange:2->0 1455020312522.2819.yh5DEw==
,2016-02-09 13:18:44.976 ThaliTest[1069:1746954] server session: disconnect
2016-02-09 13:18:44.976 ThaliTest[1069:1746954] server session: stateChange:2->0 1455020312522.2819
,2016-02-09 13:18:44.988 ThaliTest[1069:1746954] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliReplicationManager can call start without error

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/97494474-2E07-4E3A-8A23-40F21ACBE4B5/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,ok 122 starting event should occur in right order

,2016-02-09 13:18:54.491 ThaliTest[1069:1746954] jxcore: startBroadcasting
,2016-02-09 13:18:54.492 ThaliTest[1069:1746954] server: starting uiDGykO_8IpTQYZhQeQGFQ.h+xNLw==
,2016-02-09 13:18:54.493 ThaliTest[1069:1746954] multipeer session: start timer: 0x182995d0
2016-02-09 13:18:54.493 ThaliTest[1069:1746954] THEMultipeerSession initialized peer uiDGykO_8IpTQYZhQeQGFQ
2016-02-09 13:18:54.493 ThaliTest[1069:1746954] jxcore: startBroadcasting: success
,ok 123 started event should occur in right order

,Now in TRM stop

,State of this._isStarted: true

,ok 124 stopping event should occur in right order

About to call stopBroadcasting

2016-02-09 13:18:54.495 ThaliTest[1069:1746954] jxcore: stopBroadcasting
2016-02-09 13:18:54.495 ThaliTest[1069:1746954] THEMultipeerSession stopping peer
2016-02-09 13:18:54.495 ThaliTest[1069:1746954] multipeer session: stop timer
2016-02-09 13:18:54.496 ThaliTest[1069:1746954] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,ok 125 stopped event should occur in right order

,mux server bridge listener closed

# setup

,* thread #1: tid = 0x1aa714, 0x36abffbc libsystem_kernel.dylib`mach_msg_trap + 20, queue = 'com.apple.main-thread'
  * frame #0: 0x36abffbc libsystem_kernel.dylib`mach_msg_trap + 20
    frame #1: 0x36abfdbc libsystem_kernel.dylib`mach_msg + 40
    frame #2: 0x2477c48c CoreFoundation`<redacted> + 136
    frame #3: 0x2477a812 CoreFoundation`<redacted> + 1050
    frame #4: 0x246cd0d8 CoreFoundation`CFRunLoopRunSpecific + 516
    frame #5: 0x246ccecc CoreFoundation`CFRunLoopRunInMode + 108
    frame #6: 0x2d874af8 GraphicsServices`GSEventRunModal + 160
    frame #7: 0x289562dc UIKit`UIApplicationMain + 144
    frame #8: 0x00091062 ThaliTest`main + 50

```
