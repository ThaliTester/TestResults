#### Test 56449660bb41d23_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/56449660bb41d23/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/043251E2-2248-406C-A177-F45C7CD67EDC/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/043251E2-2248-406C-A177-F45C7CD67EDC/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/56449660bb41d23/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/56449660bb41d23/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0C35C09E-42F9-4F01-8C92-C97CB9B6B351/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59610"
,(lldb)     command script import "/tmp/043251E2-2248-406C-A177-F45C7CD67EDC/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-21 16:39:21.195 ThaliTest[2494:5405815] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0B323F97-9411-4D2B-8B78-7E1472DC44D5/Library/Cookies/Cookies.binarycookies
,2016-01-21 16:39:21.433 ThaliTest[2494:5405815] Apache Cordova native platform version 3.9.2 is starting.
2016-01-21 16:39:21.434 ThaliTest[2494:5405815] Multi-tasking -> Device: YES, App: YES
,2016-01-21 16:39:21.440 ThaliTest[2494:5405815] Unlimited access to network resources
,2016-01-21 16:39:21.446 ThaliTest[2494:5405815] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-21 16:39:25.613 ThaliTest[2494:5405815] Resetting plugins due to page load.
,2016-01-21 16:39:27.040 ThaliTest[2494:5405815] Finished load of: file:///var/mobile/Containers/Bundle/Application/0C35C09E-42F9-4F01-8C92-C97CB9B6B351/ThaliTest.app/www/index.html
,2016-01-21 16:39:27.180 ThaliTest[2494:5405815] JXcore Cordova plugin initializing
,2016-01-21 16:39:27.181 ThaliTest[2494:5405970] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C35C09E-42F9-4F01-8C92-C97CB9B6B351/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C35C09E-42F9-4F01-8C92-C97CB9B6B351/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C35C09E-42F9-4F01-8C92-C97CB9B6B351/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C35C09E-42F9-4F01-8C92-C97CB9B6B351/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C35C09E-42F9-4F01-8C92-C97CB9B6B351/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C35C09E-42F9-4F01-8C92-C97CB9B6B351/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C35C09E-42F9-4F01-8C92-C97CB9B6B351/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,TAP version 13

,# setup

,# multiplex can send data

,# teardown

,ok 1 String should be length:200

,# setup

,# basic

,# teardown

,ok 2 sane

,# setup

,# another

,# teardown

,ok 3 sane

,# setup

,# successfully create a new pkcs12 file and return hash value

,# teardown

,ok 4 should be equal

,ok 5 null

,ok 6 (unnamed assert)

,ok 7 should be equal

,ok 8 should not throw

,# setup

,# successfully read a previous pkcs12 file and return hash value

,# teardown

,ok 9 (unnamed assert)

,ok 10 (unnamed assert)

ok 11 should not throw

,ok 12 should be equal

ok 13 should be equal

# setup

,# failed to extract public key because of corrupt pkcs12 file

,# teardown

,ok 14 should be equal

,# setup

,# failed to get mobile documents path

,# teardown

,ok 15 should be equal

,# setup

,# #init should register the peerAvailabilityChanged event

,# teardown

,ok 16 should be equal

,ok 17 should be equal

ok 18 should be equal

,# setup

,# #init should register the networkChanged event

,# teardown

,ok 19 should be equal

,# setup

,# #startBroadcasting should throw on null device name

,# teardown

,ok 20 should throw

,# setup

,# #startBroadcasting should throw on empty string device name

,# teardown

,ok 21 should throw

,# setup

,# #startBroadcasting should throw on non-number port

,# teardown

,ok 22 should throw

,# setup

,# #startBroadcasting should throw on NaN port

,# teardown

,ok 23 should throw

,# setup

,# #startBroadcasting should throw on negative port

,# teardown

,ok 24 should throw

,# setup

,# #startBroadcasting should throw on too large port

,# teardown

,ok 25 should throw

,# setup

,# #startBroadcasting should call Mobile("StartBroadcasting") without an error

,# teardown

,ok 26 should be equal

,ok 27 should be equal

ok 28 should be equal

,# setup

,# #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

,# teardown

,ok 29 should be equal

ok 30 should be equal

ok 31 should be equal

,# setup

,# #stopBroadcasting should call Mobile("StopBroadcasting") without an error

,# teardown

,ok 32 should be equal

ok 33 should be equal

,# setup

,# #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

,# teardown

,ok 34 should be equal

,ok 35 should be equal

,# setup

,# #connect should call Mobile("Connect") with a port and without an error

,# teardown

,ok 36 should be equal

ok 37 should be equal

,ok 38 should be equal

,# setup

,# #connect should call Mobile("Connect") and handle an error

,# teardown

,ok 39 should be equal

ok 40 should be equal

,# setup

,# should call Mobile("Disconnect") without an error

,# teardown

,ok 41 should be equal

ok 42 should be equal

,# setup

,# should call Mobile("Disconnect") and handle an error

,# teardown

,ok 43 should be equal

ok 44 should be equal

,# setup

,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

,# teardown

,2016-01-21 16:44:27.355 ThaliTest[2494:5405970] jxcore: startBroadcasting
,2016-01-21 16:44:27.360 ThaliTest[2494:5405970] server: starting 1453391067355.2494.nsZ99w==
2016-01-21 16:44:27.361 ThaliTest[2494:5405970] multipeer session: start timer: 0x18e9b470
,2016-01-21 16:44:27.361 ThaliTest[2494:5405970] THEMultipeerSession initialized peer 1453391067355.2494
,2016-01-21 16:44:27.361 ThaliTest[2494:5405970] jxcore: startBroadcasting: success
ok 45 Should be able to call startBroadcasting without error

2016-01-21 16:44:27.362 ThaliTest[2494:5405970] jxcore: stopBroadcasting
,2016-01-21 16:44:27.362 ThaliTest[2494:5405970] THEMultipeerSession stopping peer
2016-01-21 16:44:27.362 ThaliTest[2494:5405970] multipeer session: stop timer
2016-01-21 16:44:27.363 ThaliTest[2494:5405970] jxcore: stopBroadcasting: success
ok 46 Should be able to call stopBroadcasting without error

,2016-01-21 16:44:27.364 ThaliTest[2494:5405970] jxcore: startBroadcasting
,2016-01-21 16:44:27.366 ThaliTest[2494:5405970] server: starting 1453391067363.2494.LStWHA==
2016-01-21 16:44:27.367 ThaliTest[2494:5405970] multipeer session: start timer: 0x1975cab0
2016-01-21 16:44:27.367 ThaliTest[2494:5405970] THEMultipeerSession in,itialized peer 1453391067363.2494
2016-01-21 16:44:27.367 ThaliTest[2494:5405970] jxcore: startBroadcasting: success
ok 47 Should be able to call startBroadcasting without error

,2016-01-21 16:44:27.367 ThaliTest[2494:5405970] jxcore: stopBroadcasting
2016-01-21 16:44:27.369 ThaliTest[2494:5405970] THEMultipeerSession stopping peer
2016-01-21 16:44:27.369 ThaliTest[2494:5405970] multipeer session: stop timer
2016-01-21 16:44:27.369 ThaliTest[2494:5405970] jxcore: stopBroadcasting: success
,ok 48 Should be able to call stopBroadcasting without error

2016-01-21 16:44:27.370 ThaliTest[2494:5405970] jxcore: startBroadcasting
,2016-01-21 16:44:27.371 ThaliTest[2494:5405970] server: starting 1453391067370.2494.hLiykg==
2016-01-21 16:44:27.371 ThaliTest[2494:5405970] multipeer session: start timer: 0x18f813a0
2016-01-21 16:44:27.371 ThaliTest[2494:5405970] THEMultipeerSession in,itialized peer 1453391067370.2494
2016-01-21 16:44:27.371 ThaliTest[2494:5405970] jxcore: startBroadcasting: success
ok 49 Should be able to call startBroadcasting without error

2016-01-21 16:44:27.372 ThaliTest[2494:5405970] jxcore: stopBroadcasting
2016-01-21 16:44:27.373 ThaliTest[2494:5405970] THEMultipeerSession stopping peer
2016-01-21 16:44:27.373 ThaliTest[2494:5405970] multipeer session: stop timer
2016-01-21 16:44:27.373 ThaliTest[2494:5405970] jxcore: stopBroadcasting: success
ok 50 Should be able to call stopBroadcasting without error

2016-01-21 16:44:27.373 ThaliTest[2494:5405970] jxcore: startBroadcasting
,2016-01-21 16:44:27.376 ThaliTest[2494:5405970] server: starting 1453391067373.2494.Se0dbA==
2016-01-21 16:44:27.376 ThaliTest[2494:5405970] multipeer session: start timer: 0x1975bc40
2016-01-21 16:44:27.376 ThaliTest[2494:5405970] THEMultipeerSession in,itialized peer 1453391067373.2494
2016-01-21 16:44:27.376 ThaliTest[2494:5405970] jxcore: startBroadcasting: success
ok 51 Should be able to call startBroadcasting without error

2016-01-21 16:44:27.377 ThaliTest[2494:5405970] jxcore: stopBroadcasting
2016-01-21 16:44:27.377 ThaliTest[2494:5405970] THEMultipeerSession stopping peer
2016-01-21 16:44:27.377 ThaliTest[2494:5405970] multipeer session: stop timer
2016-01-21 16:44:27.377 ThaliTest[2494:5405970] jxcore: stopBroadcasting: success
ok 52 Shou,ld be able to call stopBroadcasting without error

2016-01-21 16:44:27.377 ThaliTest[2494:5405970] jxcore: startBroadcasting
,2016-01-21 16:44:27.379 ThaliTest[2494:5405970] server: starting 1453391067377.2494.f2m0jg==
2016-01-21 16:44:27.379 ThaliTest[2494:5405970] multipeer session: start timer: 0x191562c0
2016-01-21 16:44:27.379 ThaliTest[2494:5405970] THEMultipeerSession in,itialized peer 1453391067377.2494
,2016-01-21 16:44:27.379 ThaliTest[2494:5405970] jxcore: startBroadcasting: success
,ok 53 Should be able to call startBroadcasting without error

,2016-01-21 16:44:27.384 ThaliTest[2494:5405970] jxcore: stopBroadcasting
,2016-01-21 16:44:27.384 ThaliTest[2494:5405970] THEMultipeerSession stopping peer
,2016-01-21 16:44:27.385 ThaliTest[2494:5405970] multipeer session: stop timer
,2016-01-21 16:44:27.385 ThaliTest[2494:5405970] jxcore: stopBroadcasting: success
,ok 54 Should be able to call stopBroadcasting without error

,2016-01-21 16:44:27.387 ThaliTest[2494:5405970] jxcore: startBroadcasting
,2016-01-21 16:44:27.388 ThaliTest[2494:5405970] server: starting 1453391067386.2494.kLAL5Q==
,2016-01-21 16:44:27.388 ThaliTest[2494:5405970] multipeer session: start timer: 0x1975b520
,2016-01-21 16:44:27.389 ThaliTest[2494:5405970] THEMultipeerSession initialized peer 1453391067386.2494
,2016-01-21 16:44:27.390 ThaliTest[2494:5405970] jxcore: startBroadcasting: success
,ok 55 Should be able to call startBroadcasting without error

,2016-01-21 16:44:27.391 ThaliTest[2494:5405970] jxcore: stopBroadcasting
,2016-01-21 16:44:27.391 ThaliTest[2494:5405970] THEMultipeerSession stopping peer
,2016-01-21 16:44:27.391 ThaliTest[2494:5405970] multipeer session: stop timer
,2016-01-21 16:44:27.393 ThaliTest[2494:5405970] jxcore: stopBroadcasting: success
,ok 56 Should be able to call stopBroadcasting without error

,2016-01-21 16:44:27.393 ThaliTest[2494:5405970] jxcore: startBroadcasting
,2016-01-21 16:44:27.394 ThaliTest[2494:5405970] server: starting 1453391067393.2494.ysT2eA==
,2016-01-21 16:44:27.395 ThaliTest[2494:5405970] multipeer session: start timer: 0x1975dec0
,2016-01-21 16:44:27.396 ThaliTest[2494:5405970] THEMultipeerSession initialized peer 1453391067393.2494
,2016-01-21 16:44:27.396 ThaliTest[2494:5405970] jxcore: startBroadcasting: success
,ok 57 Should be able to call startBroadcasting without error

,2016-01-21 16:44:27.397 ThaliTest[2494:5405970] jxcore: stopBroadcasting
,2016-01-21 16:44:27.397 ThaliTest[2494:5405970] THEMultipeerSession stopping peer
,2016-01-21 16:44:27.398 ThaliTest[2494:5405970] multipeer session: stop timer
,2016-01-21 16:44:27.398 ThaliTest[2494:5405970] jxcore: stopBroadcasting: success
,ok 58 Should be able to call stopBroadcasting without error

,2016-01-21 16:44:27.400 ThaliTest[2494:5405970] jxcore: startBroadcasting
,2016-01-21 16:44:27.401 ThaliTest[2494:5405970] server: starting 1453391067399.2494.nYKYbA==
,2016-01-21 16:44:27.401 ThaliTest[2494:5405970] multipeer session: start timer: 0x1975f150
2016-01-21 16:44:27.402 ThaliTest[2494:5405970] THEMultipeerSession initialized peer 1453391067399.2494
2016-01-21 16:44:27.403 ThaliTest[2494:5405970] jxcore: startBroadcasting: success
,ok 59 Should be able to call startBroadcasting without error

,2016-01-21 16:44:27.403 ThaliTest[2494:5405970] jxcore: stopBroadcasting
,2016-01-21 16:44:27.404 ThaliTest[2494:5405970] THEMultipeerSession stopping peer
,2016-01-21 16:44:27.404 ThaliTest[2494:5405970] multipeer session: stop timer
,2016-01-21 16:44:27.404 ThaliTest[2494:5405970] jxcore: stopBroadcasting: success
,ok 60 Should be able to call stopBroadcasting without error

,2016-01-21 16:44:27.406 ThaliTest[2494:5405970] jxcore: startBroadcasting
,2016-01-21 16:44:27.407 ThaliTest[2494:5405970] server: starting 1453391067406.2494.bRJrxQ==
,2016-01-21 16:44:27.408 ThaliTest[2494:5405970] multipeer session: start timer: 0x19156590
,2016-01-21 16:44:27.409 ThaliTest[2494:5405970] THEMultipeerSession initialized peer 1453391067406.2494
,2016-01-21 16:44:27.409 ThaliTest[2494:5405970] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error

,2016-01-21 16:44:27.410 ThaliTest[2494:5405970] jxcore: stopBroadcasting
,2016-01-21 16:44:27.410 ThaliTest[2494:5405970] THEMultipeerSession stopping peer
,2016-01-21 16:44:27.410 ThaliTest[2494:5405970] multipeer session: stop timer
,2016-01-21 16:44:27.411 ThaliTest[2494:5405970] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error

2016-01-21 16:44:27.412 ThaliTest[2494:5405970] jxcore: startBroadcasting
,2016-01-21 16:44:27.413 ThaliTest[2494:5405970] server: starting 1453391067412.2494.eMdl4Q==
,2016-01-21 16:44:27.414 ThaliTest[2494:5405970] multipeer session: start timer: 0x1975e950
,2016-01-21 16:44:27.414 ThaliTest[2494:5405970] THEMultipeerSession initialized peer 1453391067412.2494
,2016-01-21 16:44:27.415 ThaliTest[2494:5405970] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error

,2016-01-21 16:44:27.416 ThaliTest[2494:5405970] jxcore: stopBroadcasting
,2016-01-21 16:44:27.416 ThaliTest[2494:5405970] THEMultipeerSession stopping peer
,2016-01-21 16:44:27.416 ThaliTest[2494:5405970] multipeer session: stop timer
,2016-01-21 16:44:27.417 ThaliTest[2494:5405970] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,# teardown

,2016-01-21 16:44:27.728 ThaliTest[2494:5405970] jxcore: startBroadcasting
,2016-01-21 16:44:27.729 ThaliTest[2494:5405970] server: starting 1453391067728.2494.+iL1og==
,2016-01-21 16:44:27.729 ThaliTest[2494:5405970] multipeer session: start timer: 0x19761db0
2016-01-21 16:44:27.730 ThaliTest[2494:5405970] THEMultipeerSession initialized peer 1453391067728.2494
2016-01-21 16:44:27.730 ThaliTest[2494:5405970] jxcore: startBroadcasting: success
,ok 65 Should be able to call startBroadcasting without error

2016-01-21 16:44:27.731 ThaliTest[2494:5405970] jxcore: startBroadcasting
,2016-01-21 16:44:27.731 ThaliTest[2494:5405970] jxcore: startBroadcasting: failure
,ok 66 Cannot call startBroadcasting twice

2016-01-21 16:44:27.732 ThaliTest[2494:5405970] jxcore: stopBroadcasting
2016-01-21 16:44:27.732 ThaliTest[2494:5405970] THEMultipeerSession stopping peer
2016-01-21 16:44:27.732 ThaliTest[2494:5405970] multip,eer session: stop timer
2016-01-21 16:44:27.733 ThaliTest[2494:5405970] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on connection to bad peer

,# teardown

,2016-01-21 16:44:28.162 ThaliTest[2494:5405970] jxcore: startBroadcasting
,2016-01-21 16:44:28.163 ThaliTest[2494:5405970] server: starting 1453391068162.2494.SVS1XA==
2016-01-21 16:44:28.163 ThaliTest[2494:5405970] multipeer session: start timer: 0x1b0a4570
2016-01-21 16:44:28.163 ThaliTest[2494:5405970] THEMultipeerSession in,itialized peer 1453391068162.2494
2016-01-21 16:44:28.163 ThaliTest[2494:5405970] jxcore: startBroadcasting: success
ok 68 Should be able to call startBroadcasting without error

2016-01-21 16:44:28.164 ThaliTest[2494:5405970] jxcore: connect foobar
2016-01-21 16:44:28.164 ThaliTest[2494:5405970] client: unknown peer foobar
2016-01-21 16:44:28.164 ThaliTest[2494:5405970] jxcore: connect: fail: Unknown peer
,ok 69 Should not connect to a bad peer

2016-01-21 16:44:28.166 ThaliTest[2494:5405970] jxcore: stopBroadcasting
2016-01-21 16:44:28.166 ThaliTest[2494:5405970] THEMultipeerSession stopping peer
2016-01-21 16:44:28.166 ThaliTest[2494:5405970] multipeer session: stop timer
2016-01-21 16:44:28.166 ThaliTest[2494:5405970] jxcore: stopBroadcasting: success
ok 70 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on disconnect to bad peer

,# teardown

,2016-01-21 16:44:28.856 ThaliTest[2494:5405970] jxcore: startBroadcasting
,2016-01-21 16:44:28.857 ThaliTest[2494:5405970] server: starting 1453391068856.2494.XiyvTQ==
2016-01-21 16:44:28.858 ThaliTest[2494:5405970] multipeer session: start timer: 0x18b02920
2016-01-21 16:44:28.858 ThaliTest[2494:5405970] THEMultipeerSession in,itialized peer 1453391068856.2494
,2016-01-21 16:44:28.859 ThaliTest[2494:5405970] jxcore: startBroadcasting: success
ok 71 Should be able to call startBroadcasting without error

2016-01-21 16:44:28.860 ThaliTest[2494:5405970] jxcore: disconnect
2016-01-21 16:44:28.860 ThaliTest[2494:5,405970] jxcore: disconnect: fail
ok 72 Disconnect should fail to a non-existant peer 

2016-01-21 16:44:28.861 ThaliTest[2494:5405970] jxcore: stopBroadcasting
2016-01-21 16:44:28.861 ThaliTest[2494:5405970] THEMultipeerSession stopping peer
2016-01-21 16:44:28.861 ThaliTest[2494:5405970] multipeer session: stop timer
2016-01-21 16:44:28.861 ThaliTest[2494:5405970] jxcore: stopBroadcasting: success
ok 73 Should be able to call stopBroadcasting without error

# setup

,# ThaliEmitter can discover and connect to peers

,# teardown

,2016-01-21 16:44:29.808 ThaliTest[2494:5405970] jxcore: startBroadcasting
,2016-01-21 16:44:29.809 ThaliTest[2494:5405970] server: starting 1453391069808.2494.3U3gzw==
2016-01-21 16:44:29.810 ThaliTest[2494:5405970] multipeer session: start timer: 0x18b06db0
2016-01-21 16:44:29.810 ThaliTest[2494:5405970] THEMultipeerSession initialized peer 1453391069808.2494
,2016-01-21 16:44:29.811 ThaliTest[2494:5405970] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error

,2016-01-21 16:44:31.095 ThaliTest[2494:5405815] client: found peer: 1453391067059.2403.nY8DCQ==
,2016-01-21 16:44:31.096 ThaliTest[2494:5405970] jxcore: connect 1453391067059.2403.nY8DCQ==
2016-01-21 16:44:31.096 ThaliTest[2494:5405970] client session: connect
2016-01-21 16:44:31.096 ThaliTest[2494:5405970] client session: stateChange:0->1 1453391067059.2403.nY8DCQ==
,2016-01-21 16:44:31.613 ThaliTest[2494:5405815] multipeer session: reset timer
2016-01-21 16:44:31.613 ThaliTest[2494:5405815] multipeer session: stop timer
2016-01-21 16:44:31.613 ThaliTest[2494:5405815] multipeer session: start timer: 0x18b06db0
2016-01-21 16:44:31.613 ThaliTest[2494:5405815] server session: connect
2016-01-21 16:44:31.613 ThaliTest[2494:5405815] server session: stateChange:0->1 1453391067059.2403
2016-01-21 16:44:31.615 ThaliTest[2494:5405815] server: accepting invitation 1453391067059.2403
,2016-01-21 16:44:34.159 ThaliTest[2494:5406559] client session: connected
2016-01-21 16:44:34.159 ThaliTest[2494:5406559] client session: stateChange:1->2 1453391067059.2403.nY8DCQ==
,2016-01-21 16:44:34.310 ThaliTest[2494:5406559] server session: connected
2016-01-21 16:44:34.310 ThaliTest[2494:5406559] server session: stateChange:1->2 1453391067059.2403
,2016-01-21 16:44:34.678 ThaliTest[2494:5406558] client session: fireConnectCallback: 1453391067059.2403.nY8DCQ==
2016-01-21 16:44:34.678 ThaliTest[2494:5406558] jxcore: connect: success
,ok 75 Should be able to connect without error

ok 76 Port should be within range

,2016-01-21 16:44:34.679 ThaliTest[2494:5405970] jxcore: disconnect
2016-01-21 16:44:34.679 ThaliTest[2494:5405970] client session: disconnectFromPeer: 1453391067059.2403.nY8DCQ==
2016-01-21 16:44:34.679 ThaliTest[2494:5405970] client session: disconnect
2016-01-21 16:44:34.679 ThaliTest[2494:5405970] client session: stateChange:2->0 1453391067059.2403.nY8DCQ==
,2016-01-21 16:44:34.743 ThaliTest[2494:5405970] jxcore: disconnect: success
,ok 77 Should be able to disconnect without error

,setting stopBroadcasting callback and ending test.

,# setup

,2016-01-21 16:44:35.196 ThaliTest[2494:5405815] server relay: socket disconnected
2016-01-21 16:44:35.196 ThaliTest[2494:5405815] server relay: 0x19765730 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLoc,alizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-21 16:44:35.592 ThaliTest[2494:5406559] server session: not connected 1453391067059.2403
,calling stopBroadcasting

,2016-01-21 16:44:36.118 ThaliTest[2494:5405970] jxcore: stopBroadcasting
2016-01-21 16:44:36.118 ThaliTest[2494:5405970] THEMultipeerSession stopping peer
2016-01-21 16:44:36.119 ThaliTest[2494:5405970] multipeer session: stop timer
2016-01-21 16:44:36.119 ThaliTest[2494:5405970] server session: disconnect
2016-01-21 16:44:36.119 ThaliTest[2494:5405970] server session: stateChange:2->0 1453391067059.2403
2016-01-21 16:44:36.121 ThaliTest[2494:5405970] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double connect

,# teardown

,2016-01-21 16:44:36.695 ThaliTest[2494:5405970] jxcore: startBroadcasting
,2016-01-21 16:44:36.697 ThaliTest[2494:5405970] server: starting 1453391076695.2494.eT/2Zw==
2016-01-21 16:44:36.697 ThaliTest[2494:5405970] multipeer session: start timer: 0x18b07820
2016-01-21 16:44:36.697 ThaliTest[2494:5405970] THEMultipeerSession in,itialized peer 1453391076695.2494
2016-01-21 16:44:36.697 ThaliTest[2494:5405970] jxcore: startBroadcasting: success
ok 78 Should be able to call startBroadcasting without error

,2016-01-21 16:44:37.812 ThaliTest[2494:5405815] client: found peer: 1453391073919.2403.16iqqw==
,2016-01-21 16:44:37.813 ThaliTest[2494:5405970] jxcore: connect 1453391073919.2403.16iqqw==
2016-01-21 16:44:37.813 ThaliTest[2494:5405970] client session: connect
2016-01-21 16:44:37.813 ThaliTest[2494:5405970] client session: stateChange:0->1 145339107,3919.2403.16iqqw==
,2016-01-21 16:44:37.949 ThaliTest[2494:5405815] multipeer session: reset timer
2016-01-21 16:44:37.949 ThaliTest[2494:5405815] multipeer session: stop timer
2016-01-21 16:44:37.949 ThaliTest[2494:5405815] multipeer session: start timer: 0x18b07820
2016-,01-21 16:44:37.949 ThaliTest[2494:5405815] server session: connect
2016-01-21 16:44:37.949 ThaliTest[2494:5405815] server session: stateChange:0->1 1453391073919.2403
2016-01-21 16:44:37.951 ThaliTest[2494:5405815] server: accepting invitation 1453391073919.2403
,2016-01-21 16:44:40.479 ThaliTest[2494:5406558] client session: connected
2016-01-21 16:44:40.479 ThaliTest[2494:5406558] client session: stateChange:1->2 1453391073919.2403.16iqqw==
,2016-01-21 16:44:40.497 ThaliTest[2494:5406597] client session: fireConnectCallback: 1453391073919.2403.16iqqw==
2016-01-21 16:44:40.497 ThaliTest[2494:5406597] jxcore: connect: success
,ok 79 Should be able to connect without error

,ok 80 Port should be within range

,2016-01-21 16:44:40.498 ThaliTest[2494:5405970] jxcore: connect 1453391073919.2403.16iqqw==
2016-01-21 16:44:40.499 ThaliTest[2494:5405970] client: already connect(ing/ed) to 1453391073919.2403.16iqqw==
2016-01-21 16:44:40.499 ThaliTest[2494:5405970] jxc,ore: connect: fail: Aleady connecting
,ok 81 Should fail on double connect

,2016-01-21 16:44:40.500 ThaliTest[2494:5405970] jxcore: disconnect
,2016-01-21 16:44:40.500 ThaliTest[2494:5405970] client session: disconnectFromPeer: 1453391073919.2403.16iqqw==
2016-01-21 16:44:40.500 ThaliTest[2494:5405970] client session: disconnect
2016-01-21 16:44:40.500 ThaliTest[2494:5405970] client session: sta,teChange:2->0 1453391073919.2403.16iqqw==
,2016-01-21 16:44:40.550 ThaliTest[2494:5406544] server session: connected
2016-01-21 16:44:40.550 ThaliTest[2494:5406544] server session: stateChange:1->2 1453391073919.2403
,2016-01-21 16:44:40.558 ThaliTest[2494:5405970] jxcore: disconnect: success
,ok 82 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,2016-01-21 16:44:40.561 ThaliTest[2494:5405815] server relay: socket disconnected
,2016-01-21 16:44:40.561 ThaliTest[2494:5405815] server relay: 0x19737280 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,# setup

,2016-01-21 16:44:40.577 ThaliTest[2494:5406559] server session: not connected 1453391073919.2403
,calling stopBroadcasting

,2016-01-21 16:44:40.847 ThaliTest[2494:5405970] jxcore: stopBroadcasting
,2016-01-21 16:44:40.847 ThaliTest[2494:5405970] THEMultipeerSession stopping peer
2016-01-21 16:44:40.847 ThaliTest[2494:5405970] multipeer session: stop timer
,2016-01-21 16:44:40.848 ThaliTest[2494:5405970] server session: disconnect
2016-01-21 16:44:40.848 ThaliTest[2494:5405970] server session: stateChange:2->0 1453391073919.2403
,2016-01-21 16:44:40.848 ThaliTest[2494:5405970] jxcore: stopBroadcasting: success
,stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,# teardown

,2016-01-21 16:44:41.351 ThaliTest[2494:5405970] jxcore: startBroadcasting
,2016-01-21 16:44:41.352 ThaliTest[2494:5405970] server: starting 1453391081351.2494.qPjuwg==
2016-01-21 16:44:41.352 ThaliTest[2494:5405970] multipeer session: start timer: 0x18b2b9f0
2016-01-21 16:44:41.352 ThaliTest[2494:5405970] THEMultipeerSession in,itialized peer 1453391081351.2494
2016-01-21 16:44:41.352 ThaliTest[2494:5405970] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error

,2016-01-21 16:44:42.014 ThaliTest[2494:5405815] client: found peer: 1453391078168.2403.Fxajfg==
2016-01-21 16:44:42.014 ThaliTest[2494:5405970] jxcore: connect 1453391078168.2403.Fxajfg==
2016-01-21 16:44:42.014 ThaliTest[2494:5405970] client session: connect
,2016-01-21 16:44:42.015 ThaliTest[2494:5405970] client session: stateChange:0->1 1453391078168.2403.Fxajfg==
,2016-01-21 16:44:42.476 ThaliTest[2494:5405815] multipeer session: reset timer
2016-01-21 16:44:42.476 ThaliTest[2494:5405815] multipeer session: stop timer
2016-01-21 16:44:42.476 ThaliTest[2494:5405815] multipeer session: start timer: 0x18b2b9f0
2016-01-21 16:44:42.476 ThaliTest[2494:5405815] server session: connect
2016-01-21 16:44:42.476 ThaliTest[2494:5405815] server session: stateChange:0->1 1453391078168.2403
2016-01-21 16:44:42.478 ThaliTest[2494:5405815] server: accepting invitation 1453391078168.2403
,2016-01-21 16:44:44.485 ThaliTest[2494:5406548] client session: connected
2016-01-21 16:44:44.485 ThaliTest[2494:5406548] client session: stateChange:1->2 1453391078168.2403.Fxajfg==
,2016-01-21 16:44:44.487 ThaliTest[2494:5406558] client session: fireConnectCallback: 1453391078168.2403.Fxajfg==
2016-01-21 16:44:44.487 ThaliTest[2494:5406558] jxcore: connect: success
ok 84 Should be able to connect without error

ok 85 Port should be within range

,2016-01-21 16:44:44.489 ThaliTest[2494:5405970] jxcore: disconnect
2016-01-21 16:44:44.489 ThaliTest[2494:5405970] client session: disconnectFromPeer: 1453391078168.2403.Fxajfg==
2016-01-21 16:44:44.489 ThaliTest[2494:5405970] client session: disconnect
2016-01-21 16:44:44.489 ThaliTest[2494:5405970] client session: stateChange:2->0 1453391078168.2403.Fxajfg==
,2016-01-21 16:44:44.548 ThaliTest[2494:5405970] jxcore: disconnect: success
,ok 86 Should be able to disconnect without error

,2016-01-21 16:44:44.549 ThaliTest[2494:5405970] jxcore: disconnect
2016-01-21 16:44:44.549 ThaliTest[2494:5405970] jxcore: disconnect: fail
,ok 87 Disconnect should fail 

setting stopBroadcasting callback and ending test.

,# setup

,2016-01-21 16:44:45.030 ThaliTest[2494:5406559] server session: connected
2016-01-21 16:44:45.030 ThaliTest[2494:5406559] server session: stateChange:1->2 1453391078168.2403
,2016-01-21 16:44:45.032 ThaliTest[2494:5405815] server relay: socket disconnected
2016-01-21 16:44:45.032 ThaliTest[2494:5405815] server relay: 0x19740030 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-21 16:44:45.058 ThaliTest[2494:5406559] server session: not connected 1453391078168.2403
,calling stopBroadcasting

,2016-01-21 16:44:45.090 ThaliTest[2494:5405970] jxcore: stopBroadcasting
2016-01-21 16:44:45.090 ThaliTest[2494:5405970] THEMultipeerSession stopping peer
2016-01-21 16:44:45.090 ThaliTest[2494:5405970] multipeer session: stop timer
2016-01-21 16:44:45.,090 ThaliTest[2494:5405970] server session: disconnect
2016-01-21 16:44:45.090 ThaliTest[2494:5405970] server session: stateChange:2->0 1453391078168.2403
,2016-01-21 16:44:45.092 ThaliTest[2494:5405970] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can connect and send data

,# teardown

,echo server started on port: 56099

,2016-01-21 16:44:46.061 ThaliTest[2494:5405970] jxcore: startBroadcasting
,2016-01-21 16:44:46.062 ThaliTest[2494:5405970] server: starting 1453391086060.2494.ByQIxQ==
,2016-01-21 16:44:46.064 ThaliTest[2494:5405970] multipeer session: start timer: 0x16ee2b90
,2016-01-21 16:44:46.065 ThaliTest[2494:5405970] THEMultipeerSession initialized peer 1453391086060.2494
,2016-01-21 16:44:46.065 ThaliTest[2494:5405970] jxcore: startBroadcasting: success
,ok 88 Should be able to call startBroadcasting without error

,2016-01-21 16:44:47.280 ThaliTest[2494:5405815] client: found peer: 1453391083448.2403.7XEqsg==
2016-01-21 16:44:47.281 ThaliTest[2494:5405970] jxcore: connect 1453391083448.2403.7XEqsg==
2016-01-21 16:44:47.281 ThaliTest[2494:5405970] client session: connect
2016-01-21 16:44:47.281 ThaliTest[2494:5405970] client session: stateChange:0->1 1453391083448.2403.7XEqsg==
,2016-01-21 16:44:47.282 ThaliTest[2494:5405815] multipeer session: reset timer
2016-01-21 16:44:47.283 ThaliTest[2494:5405815] multipeer session: stop timer
2016-01-21 16:44:47.283 ThaliTest[2494:5405815] multipeer session: start timer: 0x16ee2b90
2016-01-21 16:44:47.283 ThaliTest[2494:5405815] server session: connect
,2016-01-21 16:44:47.284 ThaliTest[2494:5405815] server session: stateChange:0->1 1453391083448.2403
,2016-01-21 16:44:47.287 ThaliTest[2494:5405815] server: accepting invitation 1453391083448.2403
,2016-01-21 16:44:49.811 ThaliTest[2494:5406544] server session: connected
2016-01-21 16:44:49.811 ThaliTest[2494:5406544] server session: stateChange:1->2 1453391083448.2403
,2016-01-21 16:44:49.837 ThaliTest[2494:5406559] client session: connected
,2016-01-21 16:44:49.837 ThaliTest[2494:5406559] client session: stateChange:1->2 1453391083448.2403.7XEqsg==
,2016-01-21 16:44:49.840 ThaliTest[2494:5405815] server relay: connected (to port: 56099)
,2016-01-21 16:44:49.882 ThaliTest[2494:5406558] client session: fireConnectCallback: 1453391083448.2403.7XEqsg==
2016-01-21 16:44:49.882 ThaliTest[2494:5406558] jxcore: connect: success
ok 89 Should be able to connect without error

ok 90 Port should be within range

,2016-01-21 16:44:49.885 ThaliTest[2494:5405815] client: relay established
2016-01-21 16:44:49.886 ThaliTest[2494:5405815] client: new accepted socket: 0x19129dd0
,data in 4380

,data in 9855

,data in 10950

,data in 21900

,data in 49275

,data in 54750

,data in 56940

,data in 59130

,data in 68985

,data in 70080

,data in 79935

,data in 93075

,data in 122640

,data in 125925

,data in 127020

,2016-01-21 16:44:50.600 ThaliTest[2494:5406548] server session: not connected 1453391083448.2403
,data in 131072

,ok 91 the test messages should be equal

,2016-01-21 16:44:50.601 ThaliTest[2494:5405970] jxcore: disconnect
,2016-01-21 16:44:50.602 ThaliTest[2494:5405970] client session: disconnectFromPeer: 1453391083448.2403.7XEqsg==
,2016-01-21 16:44:50.602 ThaliTest[2494:5405970] client session: disconnect
,2016-01-21 16:44:50.602 ThaliTest[2494:5405970] client session: stateChange:2->0 1453391083448.2403.7XEqsg==
,2016-01-21 16:44:50.605 ThaliTest[2494:5405970] jxcore: disconnect: success
,ok 92 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-01-21 16:44:50.858 ThaliTest[2494:5405970] jxcore: stopBroadcasting
,2016-01-21 16:44:50.858 ThaliTest[2494:5405970] THEMultipeerSession stopping peer
,2016-01-21 16:44:50.859 ThaliTest[2494:5405970] multipeer session: stop timer
2016-01-21 16:44:50.859 ThaliTest[2494:5405970] server session: disconnect
,2016-01-21 16:44:50.859 ThaliTest[2494:5405970] server session: stateChange:2->0 1453391083448.2403
,2016-01-21 16:44:50.862 ThaliTest[2494:5405970] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter handles socket disconnect correctly

,# teardown

,echo server started on port: 56105

,2016-01-21 16:44:54.828 ThaliTest[2494:5405970] jxcore: startBroadcasting
,2016-01-21 16:44:54.829 ThaliTest[2494:5405970] server: starting 1453391094828.2494.wCjumA==
2016-01-21 16:44:54.830 ThaliTest[2494:5405970] multipeer session: start timer: 0x16ee57c0
2016-01-21 16:44:54.830 ThaliTest[2494:5405970] THEMultipeerSession in,itialized peer 1453391094828.2494
2016-01-21 16:44:54.830 ThaliTest[2494:5405970] jxcore: startBroadcasting: success
ok 93 Should be able to call startBroadcasting without error

,2016-01-21 16:44:55.709 ThaliTest[2494:5405815] client: found peer: 1453391091783.2403.hlBK9w==
[{"peerIdentifier":"1453391091783.2403.hlBK9w==","peerName":"(null)","peerAvailable":true}]

2016-01-21 16:44:55.710 ThaliTest[2494:5405970] jxcore: connect ,1453391091783.2403.hlBK9w==
2016-01-21 16:44:55.710 ThaliTest[2494:5405970] client session: connect
2016-01-21 16:44:55.710 ThaliTest[2494:5405970] client session: stateChange:0->1 1453391091783.2403.hlBK9w==
,2016-01-21 16:44:55.836 ThaliTest[2494:5405815] multipeer session: reset timer
2016-01-21 16:44:55.836 ThaliTest[2494:5405815] multipeer session: stop timer
2016-01-21 16:44:55.836 ThaliTest[2494:5405815] multipeer session: start timer: 0x16ee57c0
2016-01-21 16:44:55.837 ThaliTest[2494:5405815] server session: connect
2016-01-21 16:44:55.837 ThaliTest[2494:5405815] server session: stateChange:0->1 1453391091783.2403
,2016-01-21 16:44:55.839 ThaliTest[2494:5405815] server: accepting invitation 1453391091783.2403
,2016-01-21 16:44:58.424 ThaliTest[2494:5406559] client session: connected
2016-01-21 16:44:58.424 ThaliTest[2494:5406559] client session: stateChange:1->2 1453391091783.2403.hlBK9w==
,2016-01-21 16:44:58.425 ThaliTest[2494:5406597] client session: fireConnectCallback: 1453391091783.2403.hlBK9w==
2016-01-21 16:44:58.426 ThaliTest[2494:5406597] jxcore: connect: success
,ok 94 Should be able to connect without error

,ok 95 Port should be within range

,ok 96 First connect should succeed

,2016-01-21 16:44:58.436 ThaliTest[2494:5405815] client: relay established
2016-01-21 16:44:58.436 ThaliTest[2494:5405815] client: new accepted socket: 0x18eee0c0
,ok 97 the test messages should be equal

ok 98 First send should succeed

,2016-01-21 16:44:58.480 ThaliTest[2494:5405815] client: socket closed
2016-01-21 16:44:58.480 ThaliTest[2494:5405815] client relay: socket disconnected
2016-01-21 16:44:58.480 ThaliTest[2494:5405815] client relay: 0x18eee0c0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-21 16:44:58.480 ThaliTest[2494:5405815] client session: socket closed: 1453391091783.2403.hlBK9w==
2016-01-21 ,16:44:58.480 ThaliTest[2494:5405815] client session: onLinkFailure: 1453391091783.2403.hlBK9w==
2016-01-21 16:44:58.480 ThaliTest[2494:5405815] client session: disconnect
2016-01-21 16:44:58.480 ThaliTest[2494:5405815] client session: stateChange:2->0 1453391091783.2403.hlBK9w==
,2016-01-21 16:44:58.484 ThaliTest[2494:5405815] client session: fireConnectionErrorEvent: 1453391091783.2403.hlBK9w==
2016-01-21 16:44:58.485 ThaliTest[2494:5405970] jxcore: connect 1453391091783.2403.hlBK9w==
2016-01-21 16:44:58.485 ThaliTest[2494:5405970] client session: connect
2016-01-21 16:44:58.485 ThaliTest[2494:5405970] client session: stateChange:0->1 1453391091783.2403.hlBK9w==
,2016-01-21 16:44:58.492 ThaliTest[2494:5406597] server session: connected
2016-01-21 16:44:58.492 ThaliTest[2494:5406597] server session: stateChange:1->2 1453391091783.2403
,2016-01-21 16:44:58.496 ThaliTest[2494:5405815] server relay: connected (to port: 56105)
,2016-01-21 16:44:58.680 ThaliTest[2494:5406558] server session: not connected 1453391091783.2403
,2016-01-21 16:44:58.988 ThaliTest[2494:5405815] multipeer session: reset timer
,2016-01-21 16:44:58.988 ThaliTest[2494:5405815] multipeer session: stop timer
2016-01-21 16:44:58.988 ThaliTest[2494:5405815] multipeer session: start timer: 0x16ee57c0
,2016-01-21 16:44:58.988 ThaliTest[2494:5405815] server: disconnecting to refresh session (1453391091783.2403)
,2016-01-21 16:44:58.988 ThaliTest[2494:5405815] server session: disconnect
2016-01-21 16:44:58.989 ThaliTest[2494:5405815] server session: stateChange:2->0 1453391091783.2403
,2016-01-21 16:44:59.044 ThaliTest[2494:5405815] server session: connect
2016-01-21 16:44:59.044 ThaliTest[2494:5405815] server session: stateChange:0->1 1453391091783.2403
,2016-01-21 16:44:59.046 ThaliTest[2494:5405815] server: accepting invitation 1453391091783.2403
,2016-01-21 16:45:01.021 ThaliTest[2494:5406548] client session: connected
2016-01-21 16:45:01.021 ThaliTest[2494:5406548] client session: stateChange:1->2 1453391091783.2403.hlBK9w==
,2016-01-21 16:45:01.070 ThaliTest[2494:5406597] client session: fireConnectCallback: 1453391091783.2403.hlBK9w==
2016-01-21 16:45:01.071 ThaliTest[2494:5406597] jxcore: connect: success
,ok 99 Should be able to connect without error

ok 100 Port should be within range

,ok 101 Second connect should succeed

,2016-01-21 16:45:01.080 ThaliTest[2494:5405815] client: relay established
,2016-01-21 16:45:01.080 ThaliTest[2494:5405815] client: new accepted socket: 0x19738130
,ok 102 the test messages should be equal

ok 103 Second send should succeed

,# setup

,2016-01-21 16:45:01.164 ThaliTest[2494:5405815] client: socket closed
2016-01-21 16:45:01.164 ThaliTest[2494:5405815] client relay: socket disconnected
,2016-01-21 16:45:01.164 ThaliTest[2494:5405815] client relay: 0x19738130 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2016-01-21 16:45:01.164 ThaliTest[2494:5405815] client session: socket closed: 1453391091783.2403.hlBK9w==
,2016-01-21 16:45:01.164 ThaliTest[2494:5405815] client session: onLinkFailure: 1453391091783.2403.hlBK9w==
2016-01-21 16:45:01.164 ThaliTest[2494:5405815] client session: disconnect
2016-01-21 16:45:01.164 ThaliTest[2494:5405815] client session: stateChange:2->0 1453391091783.2403.hlBK9w==
,2016-01-21 16:45:01.168 ThaliTest[2494:5405815] client session: fireConnectionErrorEvent: 1453391091783.2403.hlBK9w==
,2016-01-21 16:45:01.479 ThaliTest[2494:5406597] server session: connected
2016-01-21 16:45:01.479 ThaliTest[2494:5406597] server session: stateChange:1->2 1453391091783.2403
,2016-01-21 16:45:01.530 ThaliTest[2494:5405815] server relay: connected (to port: 56105)
,2016-01-21 16:45:01.662 ThaliTest[2494:5406558] server session: not connected 1453391091783.2403
,calling stopBroadcasting

2016-01-21 16:45:01.813 ThaliTest[2494:5405970] jxcore: stopBroadcasting
,2016-01-21 16:45:01.813 ThaliTest[2494:5405970] THEMultipeerSession stopping peer
,2016-01-21 16:45:01.813 ThaliTest[2494:5405970] multipeer session: stop timer
,2016-01-21 16:45:01.814 ThaliTest[2494:5405970] server session: disconnect
2016-01-21 16:45:01.814 ThaliTest[2494:5405970] server session: stateChange:2->0 1453391091783.2403
,2016-01-21 16:45:01.816 ThaliTest[2494:5405970] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliReplicationManager can call start without error

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/0B323F97-9411-4D2B-8B78-7E1472DC44D5/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,ok 104 starting event should occur in right order

,2016-01-21 16:45:03.281 ThaliTest[2494:5405970] jxcore: startBroadcasting
,2016-01-21 16:45:03.282 ThaliTest[2494:5405970] server: starting mxHO5WH3PpjIB3-1m_VHKw.sv1pRw==
2016-01-21 16:45:03.282 ThaliTest[2494:5405970] multipeer session: start timer: 0x19748c20
2016-01-21 16:45:03.282 ThaliTest[2494:5405970] THEMultipeerSession initialized peer mxHO5WH3PpjIB3-1m_VHKw
,2016-01-21 16:45:03.283 ThaliTest[2494:5405970] jxcore: startBroadcasting: success
ok 105 started event should occur in right order

Now in TRM stop

State of this._isStarted: true

ok 106 stopping event should occur in right order

About to call ,stopBroadcasting

2016-01-21 16:45:03.285 ThaliTest[2494:5405970] jxcore: stopBroadcasting
2016-01-21 16:45:03.285 ThaliTest[2494:5405970] THEMultipeerSession stopping peer
2016-01-21 16:45:03.285 ThaliTest[2494:5405970] multipeer session: stop timer
2016-01-21 16:45:03.285 ThaliTest[2494:5405970] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,ok 107 stopped event should occur in right order

,mux server bridge listener closed

,# setup

,# ThaliReplicationManager receives identity

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/0B323F97-9411-4D2B-8B78-7E1472DC44D5/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-01-21 16:45:03.447 ThaliTest[2494:5405970] jxcore: startBroadcasting
,2016-01-21 16:45:03.448 ThaliTest[2494:5405970] server: starting mxHO5WH3PpjIB3-1m_VHKw.VAHAWA==
2016-01-21 16:45:03.448 ThaliTest[2494:5405970] multipeer session: start timer: 0x19751280
2016-01-21 16:45:03.448 ThaliTest[2494:5405970] THEMultipeerSession initialized peer mxHO5WH3PpjIB3-1m_VHKw
,2016-01-21 16:45:03.449 ThaliTest[2494:5405970] jxcore: startBroadcasting: success
ok 108 getDeviceIdentity should not return an error

ok 109 deviceName should not be null

Now in TRM stop

State of this._isStarted: true

About to call stopBroadcasting

,2016-01-21 16:45:03.450 ThaliTest[2494:5405970] jxcore: stopBroadcasting
2016-01-21 16:45:03.451 ThaliTest[2494:5405970] THEMultipeerSession stopping peer
2016-01-21 16:45:03.451 ThaliTest[2494:5405970] multipeer session: stop timer
2016-01-21 16:45:03.,451 ThaliTest[2494:5405970] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,mux server bridge listener closed

,# setup

,# ThaliReplicationManager replicates database

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/0B323F97-9411-4D2B-8B78-7E1472DC44D5/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-01-21 16:45:06.866 ThaliTest[2494:5405970] jxcore: startBroadcasting
,2016-01-21 16:45:06.868 ThaliTest[2494:5405970] server: starting mxHO5WH3PpjIB3-1m_VHKw.faqMqg==
2016-01-21 16:45:06.868 ThaliTest[2494:5405970] multipeer session: start timer: 0x16d13ee0
2016-01-21 16:45:06.868 ThaliTest[2494:5405970] THEMultipeerSessio,n initialized peer mxHO5WH3PpjIB3-1m_VHKw
,2016-01-21 16:45:06.870 ThaliTest[2494:5405970] jxcore: startBroadcasting: success
ok 110 getDeviceIdentity should not return an error

ok 111 deviceName should not be null

,2016-01-21 16:45:09.919 ThaliTest[2494:5405815] client: found peer: TQJolC_lnHeSmLHZWAv11A.VOttFA==
,2016-01-21 16:45:11.127 ThaliTest[2494:5405970] jxcore: connect TQJolC_lnHeSmLHZWAv11A.VOttFA==
2016-01-21 16:45:11.127 ThaliTest[2494:5405970] client session: connect
2016-01-21 16:45:11.127 ThaliTest[2494:5405970] client session: stateChange:0->1 TQJol,C_lnHeSmLHZWAv11A.VOttFA==
,ok 112 Should be able to put doc without error

,ok 113 1st change of local doc should contain local id

,2016-01-21 16:45:13.654 ThaliTest[2494:5405815] multipeer session: reset timer
2016-01-21 16:45:13.654 ThaliTest[2494:5405815] multipeer session: stop timer
2016-01-21 16:45:13.654 ThaliTest[2494:5405815] multipeer session: start timer: 0x16d13ee0
2016-,01-21 16:45:13.654 ThaliTest[2494:5405815] server session: connect
2016-01-21 16:45:13.654 ThaliTest[2494:5405815] server session: stateChange:0->1 TQJolC_lnHeSmLHZWAv11A
2016-01-21 16:45:13.657 ThaliTest[2494:5405815] server: accepting invitation TQJolC_lnHeSmLHZWAv11A
,2016-01-21 16:45:16.158 ThaliTest[2494:5406559] client session: connected
2016-01-21 16:45:16.158 ThaliTest[2494:5406559] client session: stateChange:1->2 TQJolC_lnHeSmLHZWAv11A.VOttFA==
,2016-01-21 16:45:16.211 ThaliTest[2494:5406544] client session: fireConnectCallback: TQJolC_lnHeSmLHZWAv11A.VOttFA==
2016-01-21 16:45:16.211 ThaliTest[2494:5406544] jxcore: connect: success
,2016-01-21 16:45:16.215 ThaliTest[2494:5405815] client: relay established
2016-01-21 16:45:16.215 ThaliTest[2494:5405815] client: new accepted socket: 0x18ce34b0
,client bridge: new client socket

,client bridge: new client socket

,2016-01-21 16:45:16.355 ThaliTest[2494:5406559] server session: connected
2016-01-21 16:45:16.356 ThaliTest[2494:5406559] server session: stateChange:1->2 TQJolC_lnHeSmLHZWAv11A
,2016-01-21 16:45:16.392 ThaliTest[2494:5405815] server relay: connected (to port: 56120)
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

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

client bridge: socket closed

,client bridge: socket closed

,client bridge: new client socket

,ok 114 1st change of remote doc should contain remote id

,ok 115 Can update remote doc without error

null

,{ ok: true,
  id: '61db956a-b119-49db-9bac-5da0d7ebda7d',
  rev: '2-bd83cd08e3adea273078ca9f85f2f4ff' }

,client bridge: new client socket

,ok 116 Remote changes occur in strict order

,client bridge: socket closed

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

,ok 117 Local changes occur in strict order

ok 118 2nd change of local doc should contain remote id

,# setup

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

client bridge: socket closed

,client bridge: new client socket

Now in TRM stop

State of this._isStarted: true

About to call stopBroadcasting

2016-01-21 16:45:32.853 ThaliTest[2494:5405970] jxcore: stopBroadcasting
2016-01-21 16:45:32.853 ThaliTest[2494:5405970] THEMultipeerSession stopping peer
2016-01-21 16:45:32.853 ThaliTest[2494:5405970] multipeer session: stop timer
2016-01-21 16:45:32.853 ThaliTest[2494:5405970] client session: disconnect
2016-01-21 16:45:32.853 ThaliTest[2494:5405970] client session: stateChange:2->0 TQJolC_lnHeSmLHZWAv11A.VOttFA==
,2016-01-21 16:45:32.879 ThaliTest[2494:5405970] server session: disconnect
2016-01-21 16:45:32.880 ThaliTest[2494:5405970] server session: stateChange:2->0 TQJolC_lnHeSmLHZWAv11A
,2016-01-21 16:45:32.892 ThaliTest[2494:5405970] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined

,client bridge: new client socket

,Error in mux client bridge Error: read ECONNRESET

,mux server bridge listener closed

,# #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available

server bridge: socket closed

,client bridge: socket closed

,syncRetry called when not started

,# teardown

,ok 119 host address should match

ok 120 port should match

,# setup

,# #startUpdateAdvertisingAndListening should use different USN after every invocation

,# teardown

,ok 121 USN should have changed from the first one

,# setup

,# verify that Thali-specific messages are filtered correctly

,# teardown

,ok 122 irrelevant messages should be ignored

ok 123 relevant messages should not be ignored

,ok 124 messages from this device should be ignored

,# setup

,# #start should fail if called twice in a row

,# teardown

,ok 125 specific error should be received

,# setup

,# #startUpdateAdvertisingAndListening should fail invalid router has been passed

,# teardown

,ERROR thaliWifiInfrastructure Unable to use the given router: TypeError: Router.use() requires middleware function but got a string

,ok 126 specific error should be received

,# setup

,# #startUpdateAdvertisingAndListening should start hosting given router object

,# teardown

,ok 127 server should respond with code 200

,# setup

,# #stop can be called multiple times in a row

,# teardown

,ok 128 should be in stopped state

ok 129 should still be in stopped state

,Tests Complete

,client bridge: socket closed

,Total: 0	Passed: 0	Failed: 0

****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
