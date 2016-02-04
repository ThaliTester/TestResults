#### Test 58259810381ca4f_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/58259810381ca4f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/069E7C7B-D61E-4E77-8546-B09BEC1E42C0/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/069E7C7B-D61E-4E77-8546-B09BEC1E42C0/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/58259810381ca4f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/58259810381ca4f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B3E8043F-A38C-4C16-A4AD-4E42300EB79E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49896"
,(lldb)     command script import "/tmp/069E7C7B-D61E-4E77-8546-B09BEC1E42C0/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-04 10:40:48.902 ThaliTest[626:953703] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A6E308A6-CB41-4BF3-AB74-63397F3D0990/Library/Cookies/Cookies.binarycookies
,2016-02-04 10:40:49.360 ThaliTest[626:953703] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-04 10:40:49.361 ThaliTest[626:953703] Multi-tasking -> Device: YES, App: YES
,2016-02-04 10:40:49.370 ThaliTest[626:953703] Unlimited access to network resources
,2016-02-04 10:40:49.378 ThaliTest[626:953703] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-04 10:40:59.088 ThaliTest[626:953703] Resetting plugins due to page load.
,2016-02-04 10:41:02.956 ThaliTest[626:953703] Finished load of: file:///var/mobile/Containers/Bundle/Application/B3E8043F-A38C-4C16-A4AD-4E42300EB79E/ThaliTest.app/www/index.html
,2016-02-04 10:41:03.085 ThaliTest[626:953703] JXcore Cordova plugin initializing
,2016-02-04 10:41:03.086 ThaliTest[626:953945] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B3E8043F-A38C-4C16-A4AD-4E42300EB79E/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B3E8043F-A38C-4C16-A4AD-4E42300EB79E/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B3E8043F-A38C-4C16-A4AD-4E42300EB79E/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B3E8043F-A38C-4C16-A4AD-4E42300EB79E/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B3E8043F-A38C-4C16-A4AD-4E42300EB79E/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B3E8043F-A38C-4C16-A4AD-4E42300EB79E/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B3E8043F-A38C-4C16-A4AD-4E42300EB79E/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B3E8043F-A38C-4C16-A4AD-4E42300EB79E/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

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

,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

,# teardown

,2016-02-04 10:48:37.305 ThaliTest[626:953945] jxcore: startBroadcasting
,2016-02-04 10:48:37.320 ThaliTest[626:953945] server: starting 1454579317304.626.ca8VIA==
,2016-02-04 10:48:37.322 ThaliTest[626:953945] multipeer session: start timer: 0x14740450
,2016-02-04 10:48:37.323 ThaliTest[626:953945] THEMultipeerSession initialized peer 1454579317304.626
,2016-02-04 10:48:37.325 ThaliTest[626:953945] jxcore: startBroadcasting: success
,ok 54 Should be able to call startBroadcasting without error

2016-02-04 10:48:37.330 ThaliTest[626:953945] jxcore: stopBroadcasting
2016-02-04 10:48:37.331 ThaliTest[626:953945] THEMultipeerSession stopping peer
2016-02-04 10:48:37.331 ThaliTest[626:9,53945] multipeer session: stop timer
,2016-02-04 10:48:37.332 ThaliTest[626:953945] jxcore: stopBroadcasting: success
ok 55 Should be able to call stopBroadcasting without error

2016-02-04 10:48:37.335 ThaliTest[626:953945] jxcore: startBroadcasting
,2016-02-04 10:48:37.338 ThaliTest[626:953945] server: starting 1454579317334.626.35BTlg==
2016-02-04 10:48:37.340 ThaliTest[626:953945] multipeer session: start timer: 0x175c0720
2016-02-04 10:48:37.340 ThaliTest[626:953945] THEMultipeerSession initialized peer 1454579317334.626
,2016-02-04 10:48:37.342 ThaliTest[626:953945] jxcore: startBroadcasting: success
,ok 56 Should be able to call startBroadcasting without error

2016-02-04 10:48:37.345 ThaliTest[626:953945] jxcore: stopBroadcasting
2016-02-04 10:48:37.346 ThaliTest[626:953945] THEMultipeerSession stopping peer
2016-02-04 10:48:37.346 ThaliTest[626:9,53945] multipeer session: stop timer
,2016-02-04 10:48:37.350 ThaliTest[626:953945] jxcore: stopBroadcasting: success
,ok 57 Should be able to call stopBroadcasting without error

2016-02-04 10:48:37.355 ThaliTest[626:953945] jxcore: startBroadcasting
,2016-02-04 10:48:37.359 ThaliTest[626:953945] server: starting 1454579317354.626.x28BEw==
,2016-02-04 10:48:37.360 ThaliTest[626:953945] multipeer session: start timer: 0x175c0da0
,2016-02-04 10:48:37.361 ThaliTest[626:953945] THEMultipeerSession initialized peer 1454579317354.626
2016-02-04 10:48:37.362 ThaliTest[626:953945] jxcore: startBroadcasting: success
,ok 58 Should be able to call startBroadcasting without error

,2016-02-04 10:48:37.364 ThaliTest[626:953945] jxcore: stopBroadcasting
2016-02-04 10:48:37.365 ThaliTest[626:953945] THEMultipeerSession stopping peer
2016-02-04 10:48:37.365 ThaliTest[626:953945] multipeer session: stop timer
,2016-02-04 10:48:37.366 ThaliTest[626:953945] jxcore: stopBroadcasting: success
ok 59 Should be able to call stopBroadcasting without error

2016-02-04 10:48:37.368 ThaliTest[626:953945] jxcore: startBroadcasting
,2016-02-04 10:48:37.376 ThaliTest[626:953945] server: starting 1454579317367.626.zZej0Q==
,2016-02-04 10:48:37.379 ThaliTest[626:953945] multipeer session: start timer: 0x175c1f80
,2016-02-04 10:48:37.379 ThaliTest[626:953945] THEMultipeerSession initialized peer 1454579317367.626
,2016-02-04 10:48:37.383 ThaliTest[626:953945] jxcore: startBroadcasting: success
,ok 60 Should be able to call startBroadcasting without error

,2016-02-04 10:48:37.387 ThaliTest[626:953945] jxcore: stopBroadcasting
,2016-02-04 10:48:37.387 ThaliTest[626:953945] THEMultipeerSession stopping peer
,2016-02-04 10:48:37.388 ThaliTest[626:953945] multipeer session: stop timer
,2016-02-04 10:48:37.389 ThaliTest[626:953945] jxcore: stopBroadcasting: success
,ok 61 Should be able to call stopBroadcasting without error
,
,2016-02-04 10:48:37.393 ThaliTest[626:953945] jxcore: startBroadcasting
,2016-02-04 10:48:37.395 ThaliTest[626:953945] server: starting 1454579317393.626.LmPCXw==
,2016-02-04 10:48:37.396 ThaliTest[626:953945] multipeer session: start timer: 0x14731b60
,2016-02-04 10:48:37.397 ThaliTest[626:953945] THEMultipeerSession initialized peer 1454579317393.626
,2016-02-04 10:48:37.400 ThaliTest[626:953945] jxcore: startBroadcasting: success
,ok 62 Should be able to call startBroadcasting without error

,2016-02-04 10:48:37.402 ThaliTest[626:953945] jxcore: stopBroadcasting
,2016-02-04 10:48:37.403 ThaliTest[626:953945] THEMultipeerSession stopping peer
,2016-02-04 10:48:37.403 ThaliTest[626:953945] multipeer session: stop timer
,2016-02-04 10:48:37.404 ThaliTest[626:953945] jxcore: stopBroadcasting: success
,ok 63 Should be able to call stopBroadcasting without error

,2016-02-04 10:48:37.408 ThaliTest[626:953945] jxcore: startBroadcasting
,2016-02-04 10:48:37.411 ThaliTest[626:953945] server: starting 1454579317408.626.T8cUcg==
,2016-02-04 10:48:37.412 ThaliTest[626:953945] multipeer session: start timer: 0x14702d30
,2016-02-04 10:48:37.416 ThaliTest[626:953945] THEMultipeerSession initialized peer 1454579317408.626
,2016-02-04 10:48:37.417 ThaliTest[626:953945] jxcore: startBroadcasting: success
,ok 64 Should be able to call startBroadcasting without error

,2016-02-04 10:48:37.419 ThaliTest[626:953945] jxcore: stopBroadcasting
,2016-02-04 10:48:37.420 ThaliTest[626:953945] THEMultipeerSession stopping peer
,2016-02-04 10:48:37.420 ThaliTest[626:953945] multipeer session: stop timer
,2016-02-04 10:48:37.421 ThaliTest[626:953945] jxcore: stopBroadcasting: success
,ok 65 Should be able to call stopBroadcasting without error
,
,2016-02-04 10:48:37.424 ThaliTest[626:953945] jxcore: startBroadcasting
,2016-02-04 10:48:37.427 ThaliTest[626:953945] server: starting 1454579317424.626.8vNcVA==
,2016-02-04 10:48:37.428 ThaliTest[626:953945] multipeer session: start timer: 0x147035f0
,2016-02-04 10:48:37.429 ThaliTest[626:953945] THEMultipeerSession initialized peer 1454579317424.626
,2016-02-04 10:48:37.431 ThaliTest[626:953945] jxcore: startBroadcasting: success
,ok 66 Should be able to call startBroadcasting without error

,2016-02-04 10:48:37.434 ThaliTest[626:953945] jxcore: stopBroadcasting
,2016-02-04 10:48:37.435 ThaliTest[626:953945] THEMultipeerSession stopping peer
,2016-02-04 10:48:37.435 ThaliTest[626:953945] multipeer session: stop timer
,2016-02-04 10:48:37.438 ThaliTest[626:953945] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error

,2016-02-04 10:48:37.440 ThaliTest[626:953945] jxcore: startBroadcasting
,2016-02-04 10:48:37.442 ThaliTest[626:953945] server: starting 1454579317439.626.S03KCA==
,2016-02-04 10:48:37.443 ThaliTest[626:953945] multipeer session: start timer: 0x147035d0
,2016-02-04 10:48:37.445 ThaliTest[626:953945] THEMultipeerSession initialized peer 1454579317439.626
,2016-02-04 10:48:37.446 ThaliTest[626:953945] jxcore: startBroadcasting: success
,ok 68 Should be able to call startBroadcasting without error

,2016-02-04 10:48:37.449 ThaliTest[626:953945] jxcore: stopBroadcasting
,2016-02-04 10:48:37.451 ThaliTest[626:953945] THEMultipeerSession stopping peer
,2016-02-04 10:48:37.451 ThaliTest[626:953945] multipeer session: stop timer
,2016-02-04 10:48:37.452 ThaliTest[626:953945] jxcore: stopBroadcasting: success
,ok 69 Should be able to call stopBroadcasting without error

,2016-02-04 10:48:37.456 ThaliTest[626:953945] jxcore: startBroadcasting
,2016-02-04 10:48:37.459 ThaliTest[626:953945] server: starting 1454579317455.626.3JG4Ow==
,2016-02-04 10:48:37.461 ThaliTest[626:953945] multipeer session: start timer: 0x175c1680
,2016-02-04 10:48:37.463 ThaliTest[626:953945] THEMultipeerSession initialized peer 1454579317455.626
,2016-02-04 10:48:37.465 ThaliTest[626:953945] jxcore: startBroadcasting: success
,ok 70 Should be able to call startBroadcasting without error

,2016-02-04 10:48:37.467 ThaliTest[626:953945] jxcore: stopBroadcasting
,2016-02-04 10:48:37.467 ThaliTest[626:953945] THEMultipeerSession stopping peer
,2016-02-04 10:48:37.468 ThaliTest[626:953945] multipeer session: stop timer
,2016-02-04 10:48:37.469 ThaliTest[626:953945] jxcore: stopBroadcasting: success
,ok 71 Should be able to call stopBroadcasting without error

,2016-02-04 10:48:37.472 ThaliTest[626:953945] jxcore: startBroadcasting
,2016-02-04 10:48:37.474 ThaliTest[626:953945] server: starting 1454579317471.626.t2RkmQ==
,2016-02-04 10:48:37.475 ThaliTest[626:953945] multipeer session: start timer: 0x175c38d0
2016-02-04 10:48:37.475 ThaliTest[626:953945] THEMultipeerSession initialized peer 1454579317471.626
,2016-02-04 10:48:37.476 ThaliTest[626:953945] jxcore: startBroadcasting: success
,ok 72 Should be able to call startBroadcasting without error

,2016-02-04 10:48:37.478 ThaliTest[626:953945] jxcore: stopBroadcasting
,2016-02-04 10:48:37.478 ThaliTest[626:953945] THEMultipeerSession stopping peer
,2016-02-04 10:48:37.479 ThaliTest[626:953945] multipeer session: stop timer
,2016-02-04 10:48:37.480 ThaliTest[626:953945] jxcore: stopBroadcasting: success
,ok 73 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,# teardown

,2016-02-04 10:48:50.003 ThaliTest[626:953945] jxcore: startBroadcasting
,2016-02-04 10:48:50.006 ThaliTest[626:953945] server: starting 1454579330002.626.5sB16w==
,2016-02-04 10:48:50.007 ThaliTest[626:953945] multipeer session: start timer: 0x172e5e40
,2016-02-04 10:48:50.008 ThaliTest[626:953945] THEMultipeerSession initialized peer 1454579330002.626
2016-02-04 10:48:50.009 ThaliTest[626:953945] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error

,2016-02-04 10:48:50.012 ThaliTest[626:953945] jxcore: startBroadcasting
2016-02-04 10:48:50.012 ThaliTest[626:953945] jxcore: startBroadcasting: failure
ok 75 Cannot call startBroadcasting twice

2016-02-04 10:48:50.017 ThaliTest[626:953945] jxcore: st,opBroadcasting
2016-02-04 10:48:50.017 ThaliTest[626:953945] THEMultipeerSession stopping peer
2016-02-04 10:48:50.018 ThaliTest[626:953945] multipeer session: stop timer
2016-02-04 10:48:50.018 ThaliTest[626:953945] jxcore: stopBroadcasting: success
o,k 76 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on connection to bad peer

,# teardown

,2016-02-04 10:49:11.920 ThaliTest[626:953945] jxcore: startBroadcasting
,2016-02-04 10:49:11.923 ThaliTest[626:953945] server: starting 1454579351919.626.kHjJmw==
,2016-02-04 10:49:11.924 ThaliTest[626:953945] multipeer session: start timer: 0x175c8b80
,2016-02-04 10:49:11.925 ThaliTest[626:953945] THEMultipeerSession initialized peer 1454579351919.626
2016-02-04 10:49:11.926 ThaliTest[626:953945] jxcore: startBroadcasting: success
,ok 77 Should be able to call startBroadcasting without error

,2016-02-04 10:49:11.929 ThaliTest[626:953945] jxcore: connect foobar
2016-02-04 10:49:11.930 ThaliTest[626:953945] client: unknown peer foobar
2016-02-04 10:49:11.930 ThaliTest[626:953945] jxcore: connect: fail: Unknown peer
,ok 78 Should not connect to a bad peer

2016-02-04 10:49:11.936 ThaliTest[626:953945] jxcore: stopBroadcasting
2016-02-04 10:49:11.937 ThaliTest[626:953945] THEMultipeerSession stopping peer
2016-02-04 10:49:11.937 ThaliTest[626:953945] multipeer session: stop timer
2016-02-04 10:49:11.937 ThaliTest[626:953945] jxcore: stopBroadcasting: success
,ok 79 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on disconnect to bad peer

,# teardown

,2016-02-04 10:49:23.882 ThaliTest[626:953945] jxcore: startBroadcasting
,2016-02-04 10:49:23.886 ThaliTest[626:953945] server: starting 1454579363882.626.IytcvA==
,2016-02-04 10:49:23.887 ThaliTest[626:953945] multipeer session: start timer: 0x175cb7d0
,2016-02-04 10:49:23.888 ThaliTest[626:953945] THEMultipeerSession initialized peer 1454579363882.626
,2016-02-04 10:49:23.888 ThaliTest[626:953945] jxcore: startBroadcasting: success
,ok 80 Should be able to call startBroadcasting without error

,2016-02-04 10:49:23.892 ThaliTest[626:953945] jxcore: disconnect
2016-02-04 10:49:23.893 ThaliTest[626:953945] jxcore: disconnect: fail
,ok 81 Disconnect should fail to a non-existant peer 

2016-02-04 10:49:23.900 ThaliTest[626:953945] jxcore: stopBroadcasting
2016-02-04 10:49:23.900 ThaliTest[626:953945] THEMultipeerSession stopping peer
,2016-02-04 10:49:23.901 ThaliTest[626:953945] multipeer session: stop timer
,2016-02-04 10:49:23.903 ThaliTest[626:953945] jxcore: stopBroadcasting: success
,ok 82 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter can discover and connect to peers

,# teardown

,2016-02-04 10:49:24.296 ThaliTest[626:953945] jxcore: startBroadcasting
,2016-02-04 10:49:24.300 ThaliTest[626:953945] server: starting 1454579364296.626.kKhhAw==
,2016-02-04 10:49:24.301 ThaliTest[626:953945] multipeer session: start timer: 0x175cc020
,2016-02-04 10:49:24.301 ThaliTest[626:953945] THEMultipeerSession initialized peer 1454579364296.626
2016-02-04 10:49:24.302 ThaliTest[626:953945] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error

,2016-02-04 10:49:25.614 ThaliTest[626:953703] client: found peer: 1454579361869.2519.Nr3MYw==
,2016-02-04 10:49:25.617 ThaliTest[626:953945] jxcore: connect 1454579361869.2519.Nr3MYw==
2016-02-04 10:49:25.617 ThaliTest[626:953945] client session: connect
2016-02-04 10:49:25.618 ThaliTest[626:953945] client session: stateChange:0->1 1454579361869.2519.Nr3MYw==
,2016-02-04 10:49:27.914 ThaliTest[626:953703] multipeer session: reset timer
2016-02-04 10:49:27.914 ThaliTest[626:953703] multipeer session: stop timer
2016-02-04 10:49:27.914 ThaliTest[626:953703] multipeer session: start timer: 0x175cc020
,2016-02-04 10:49:27.915 ThaliTest[626:953703] server session: connect
,2016-02-04 10:49:27.915 ThaliTest[626:953703] server session: stateChange:0->1 1454579361869.2519
,2016-02-04 10:49:27.922 ThaliTest[626:953703] server: accepting invitation 1454579361869.2519
,2016-02-04 10:49:30.346 ThaliTest[626:955514] client session: connected
,2016-02-04 10:49:30.346 ThaliTest[626:955514] client session: stateChange:1->2 1454579361869.2519.Nr3MYw==
,2016-02-04 10:49:30.356 ThaliTest[626:955513] client session: fireConnectCallback: 1454579361869.2519.Nr3MYw==
2016-02-04 10:49:30.356 ThaliTest[626:955513] jxcore: connect: success
,ok 84 Should be able to connect without error

,ok 85 Port should be within range

,2016-02-04 10:49:30.361 ThaliTest[626:953945] jxcore: disconnect
2016-02-04 10:49:30.362 ThaliTest[626:953945] client session: disconnectFromPeer: 1454579361869.2519.Nr3MYw==
2016-02-04 10:49:30.362 ThaliTest[626:953945] client session: disconnect
2016-02-04 10:49:30.363 ThaliTest[626:953945] client session: stateChange:2->0 1454579361869.2519.Nr3MYw==
,2016-02-04 10:49:30.372 ThaliTest[626:953945] jxcore: disconnect: success
ok 86 Should be able to disconnect without error

,setting stopBroadcasting callback and ending test.

,# setup
,
,2016-02-04 10:49:31.211 ThaliTest[626:955556] server session: connected
2016-02-04 10:49:31.211 ThaliTest[626:955556] server session: stateChange:1->2 1454579361869.2519
,2016-02-04 10:49:31.216 ThaliTest[626:953703] server relay: socket disconnected
,2016-02-04 10:49:31.217 ThaliTest[626:953703] server relay: 0x1631e3a0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-04 10:49:31.340 ThaliTest[626:955556] server session: not connected 1454579361869.2519
,calling stopBroadcasting

,2016-02-04 10:49:31.666 ThaliTest[626:953945] jxcore: stopBroadcasting
,2016-02-04 10:49:31.667 ThaliTest[626:953945] THEMultipeerSession stopping peer
,2016-02-04 10:49:31.667 ThaliTest[626:953945] multipeer session: stop timer
,2016-02-04 10:49:31.668 ThaliTest[626:953945] server session: disconnect
2016-02-04 10:49:31.669 ThaliTest[626:953945] server session: stateChange:2->0 1454579361869.2519
,2016-02-04 10:49:31.671 ThaliTest[626:953945] jxcore: stopBroadcasting: success
,stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double connect

,# teardown

,2016-02-04 10:49:33.191 ThaliTest[626:953945] jxcore: startBroadcasting
,2016-02-04 10:49:33.194 ThaliTest[626:953945] server: starting 1454579373191.626.+mjFYQ==
,2016-02-04 10:49:33.195 ThaliTest[626:953945] multipeer session: start timer: 0x175ce8e0
2016-02-04 10:49:33.196 ThaliTest[626:953945] THEMultipeerSession initialized peer 1454579373191.626
,2016-02-04 10:49:33.196 ThaliTest[626:953945] jxcore: startBroadcasting: success
,ok 87 Should be able to call startBroadcasting without error

,2016-02-04 10:49:36.579 ThaliTest[626:953703] multipeer session: reset timer
2016-02-04 10:49:36.580 ThaliTest[626:953703] multipeer session: stop timer
2016-02-04 10:49:36.580 ThaliTest[626:953703] multipeer session: start timer: 0x175ce8e0
,2016-02-04 10:49:36.580 ThaliTest[626:953703] server session: connect
2016-02-04 10:49:36.581 ThaliTest[626:953703] server session: stateChange:0->1 1454579373709.2519
,2016-02-04 10:49:36.588 ThaliTest[626:953703] server: accepting invitation 1454579373709.2519
,2016-02-04 10:49:37.188 ThaliTest[626:953703] client: found peer: 1454579373709.2519.veA/ug==
,2016-02-04 10:49:37.189 ThaliTest[626:953945] jxcore: connect 1454579373709.2519.veA/ug==
2016-02-04 10:49:37.189 ThaliTest[626:953945] client session: connect
,2016-02-04 10:49:37.190 ThaliTest[626:953945] client session: stateChange:0->1 1454579373709.2519.veA/ug==
,2016-02-04 10:49:39.708 ThaliTest[626:955556] server session: connected
2016-02-04 10:49:39.709 ThaliTest[626:955556] server session: stateChange:1->2 1454579373709.2519
,2016-02-04 10:49:39.725 ThaliTest[626:953703] server relay: socket disconnected
,2016-02-04 10:49:39.726 ThaliTest[626:953703] server relay: 0x147ad480 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-04 10:49:39.758 ThaliTest[626:955552] server session: not connected 1454579373709.2519
,2016-02-04 10:49:40.845 ThaliTest[626:955512] client session: connected
,2016-02-04 10:49:40.845 ThaliTest[626:955512] client session: stateChange:1->2 1454579373709.2519.veA/ug==
,2016-02-04 10:49:40.906 ThaliTest[626:955513] client session: fireConnectCallback: 1454579373709.2519.veA/ug==
2016-02-04 10:49:40.907 ThaliTest[626:955513] jxcore: connect: success
,ok 88 Should be able to connect without error

,ok 89 Port should be within range

,2016-02-04 10:49:40.912 ThaliTest[626:953945] jxcore: connect 1454579373709.2519.veA/ug==
,2016-02-04 10:49:40.913 ThaliTest[626:953945] client: already connect(ing/ed) to 1454579373709.2519.veA/ug==
,2016-02-04 10:49:40.914 ThaliTest[626:953945] jxcore: connect: fail: Aleady connecting
,ok 90 Should fail on double connect

,2016-02-04 10:49:40.917 ThaliTest[626:953945] jxcore: disconnect
,2016-02-04 10:49:40.918 ThaliTest[626:953945] client session: disconnectFromPeer: 1454579373709.2519.veA/ug==
,2016-02-04 10:49:40.918 ThaliTest[626:953945] client session: disconnect
,2016-02-04 10:49:40.919 ThaliTest[626:953945] client session: stateChange:2->0 1454579373709.2519.veA/ug==
,2016-02-04 10:49:40.927 ThaliTest[626:953945] jxcore: disconnect: success
ok 91 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-02-04 10:49:41.042 ThaliTest[626:953945] jxcore: stopBroadcasting
,2016-02-04 10:49:41.043 ThaliTest[626:953945] THEMultipeerSession stopping peer
,2016-02-04 10:49:41.044 ThaliTest[626:953945] multipeer session: stop timer
,2016-02-04 10:49:41.046 ThaliTest[626:953945] server session: disconnect
,2016-02-04 10:49:41.055 ThaliTest[626:953945] server session: stateChange:2->0 1454579373709.2519
,2016-02-04 10:49:41.057 ThaliTest[626:953945] jxcore: stopBroadcasting: success
,stopBroadcasting returned undefined
,
,# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,# teardown

,2016-02-04 10:49:44.548 ThaliTest[626:953945] jxcore: startBroadcasting
,2016-02-04 10:49:44.552 ThaliTest[626:953945] server: starting 1454579384548.626.aIV07A==
,2016-02-04 10:49:44.552 ThaliTest[626:953945] multipeer session: start timer: 0x175d45d0
2016-02-04 10:49:44.553 ThaliTest[626:953945] THEMultipeerSession initialized peer 1454579384548.626
2016-02-04 10:49:44.554 ThaliTest[626:953945] jxcore: startBroadcasting: success
ok 92 Should be able to call startBroadcasting without error

,2016-02-04 10:49:45.881 ThaliTest[626:953703] client: found peer: 1454579382114.2519.RfvuPg==
,2016-02-04 10:49:45.883 ThaliTest[626:953945] jxcore: connect 1454579382114.2519.RfvuPg==
,2016-02-04 10:49:45.883 ThaliTest[626:953945] client session: connect
,2016-02-04 10:49:45.884 ThaliTest[626:953945] client session: stateChange:0->1 1454579382114.2519.RfvuPg==
,2016-02-04 10:49:46.406 ThaliTest[626:953703] multipeer session: reset timer
2016-02-04 10:49:46.407 ThaliTest[626:953703] multipeer session: stop timer
2016-02-04 10:49:46.407 ThaliTest[626:953703] multipeer session: start timer: 0x175d45d0
2016-02-04 10:49:46.407 ThaliTest[626:953703] server session: connect
2016-02-04 10:49:46.408 ThaliTest[626:953703] server session: stateChange:0->1 1454579382114.2519
,2016-02-04 10:49:46.414 ThaliTest[626:953703] server: accepting invitation 1454579382114.2519
,2016-02-04 10:49:49.230 ThaliTest[626:955513] client session: connected
2016-02-04 10:49:49.231 ThaliTest[626:955513] client session: stateChange:1->2 1454579382114.2519.RfvuPg==
,2016-02-04 10:49:49.292 ThaliTest[626:955556] client session: fireConnectCallback: 1454579382114.2519.RfvuPg==
2016-02-04 10:49:49.292 ThaliTest[626:955556] jxcore: connect: success
,ok 93 Should be able to connect without error

,ok 94 Port should be within range

,2016-02-04 10:49:49.297 ThaliTest[626:953945] jxcore: disconnect
,2016-02-04 10:49:49.297 ThaliTest[626:953945] client session: disconnectFromPeer: 1454579382114.2519.RfvuPg==
,2016-02-04 10:49:49.298 ThaliTest[626:953945] client session: disconnect
2016-02-04 10:49:49.298 ThaliTest[626:953945] client session: stateChange:2->0 1454579382114.2519.RfvuPg==
,2016-02-04 10:49:49.307 ThaliTest[626:953945] jxcore: disconnect: success
,ok 95 Should be able to disconnect without error

2016-02-04 10:49:49.309 ThaliTest[626:953945] jxcore: disconnect
2016-02-04 10:49:49.310 ThaliTest[626:953945] jxcore: disconnect: fail
,ok 96 Disconnect should fail 

setting stopBroadcasting callback and ending test.

,# setup

,2016-02-04 10:49:49.617 ThaliTest[626:955552] server session: connected
2016-02-04 10:49:49.618 ThaliTest[626:955552] server session: stateChange:1->2 1454579382114.2519
,2016-02-04 10:49:49.684 ThaliTest[626:953703] server relay: socket disconnected
,2016-02-04 10:49:49.686 ThaliTest[626:953703] server relay: 0x175da6a0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-04 10:49:49.695 ThaliTest[626:955555] server session: not connected 1454579382114.2519
,calling stopBroadcasting

,2016-02-04 10:49:49.958 ThaliTest[626:953945] jxcore: stopBroadcasting
2016-02-04 10:49:49.958 ThaliTest[626:953945] THEMultipeerSession stopping peer
2016-02-04 10:49:49.959 ThaliTest[626:953945] multipeer session: stop timer
2016-02-04 10:49:49.959 ThaliTest[626:953945] server session: disconnect
2016-02-04 10:49:49.959 ThaliTest[626:953945] server session: stateChange:2->0 1454579382114.2519
,2016-02-04 10:49:49.961 ThaliTest[626:953945] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can connect and send data

,# teardown

,echo server started on port: 52933

,2016-02-04 10:49:53.537 ThaliTest[626:953945] jxcore: startBroadcasting
,2016-02-04 10:49:53.538 ThaliTest[626:953945] server: starting 1454579393536.626.4X3Rxg==
2016-02-04 10:49:53.538 ThaliTest[626:953945] multipeer session: start timer: 0x175d6310
,2016-02-04 10:49:53.538 ThaliTest[626:953945] THEMultipeerSession initialized peer 1454579393536.626
2016-02-04 10:49:53.539 ThaliTest[626:953945] jxcore: startBroadcasting: success
,ok 97 Should be able to call startBroadcasting without error

,2016-02-04 10:50:23.540 ThaliTest[626:953703] multipeer session: restart
,2016-02-04 10:50:36.251 ThaliTest[626:953703] client: found peer: 1454579431741.2519.AkU5fw==
,2016-02-04 10:50:36.253 ThaliTest[626:953945] jxcore: connect 1454579431741.2519.AkU5fw==
2016-02-04 10:50:36.254 ThaliTest[626:953945] client session: connect
,2016-02-04 10:50:36.254 ThaliTest[626:953945] client session: stateChange:0->1 1454579431741.2519.AkU5fw==
,2016-02-04 10:50:37.000 ThaliTest[626:953703] multipeer session: reset timer
2016-02-04 10:50:37.000 ThaliTest[626:953703] multipeer session: stop timer
2016-02-04 10:50:37.000 ThaliTest[626:953703] multipeer session: start timer: 0x175d6310
2016-02-04 10:50:37.001 ThaliTest[626:953703] server session: connect
2016-02-04 10:50:37.001 ThaliTest[626:953703] server session: stateChange:0->1 1454579431741.2519
,2016-02-04 10:50:37.007 ThaliTest[626:953703] server: accepting invitation 1454579431741.2519
,2016-02-04 10:50:39.873 ThaliTest[626:955716] client session: connected
2016-02-04 10:50:39.873 ThaliTest[626:955716] client session: stateChange:1->2 1454579431741.2519.AkU5fw==
,2016-02-04 10:50:39.876 ThaliTest[626:955716] client session: fireConnectCallback: 1454579431741.2519.AkU5fw==
2016-02-04 10:50:39.876 ThaliTest[626:955716] jxcore: connect: success
,ok 98 Should be able to connect without error

,ok 99 Port should be within range

,2016-02-04 10:50:39.879 ThaliTest[626:953703] client: relay established
2016-02-04 10:50:39.880 ThaliTest[626:953703] client: new accepted socket: 0x1673df50
,2016-02-04 10:50:39.945 ThaliTest[626:955716] server session: connected
2016-02-04 10:50:39.945 ThaliTest[626:955716] server session: stateChange:1->2 1454579431741.2519
,2016-02-04 10:50:40.000 ThaliTest[626:953703] server relay: connected (to port: 52933)
,data in 7665

,data in 8760

,data in 28470

,data in 45990

,data in 47085

,data in 50370

,data in 54608

,data in 65700

,data in 68985

,data in 70080

,data in 72270

,data in 83220

,data in 88695

,data in 98550

,data in 100740

,data in 111690

,data in 128115

,data in 131072

,ok 100 the test messages should be equal

,2016-02-04 10:50:41.191 ThaliTest[626:953945] jxcore: disconnect
,2016-02-04 10:50:41.192 ThaliTest[626:953945] client session: disconnectFromPeer: 1454579431741.2519.AkU5fw==
2016-02-04 10:50:41.192 ThaliTest[626:953945] client session: disconnect
,2016-02-04 10:50:41.192 ThaliTest[626:953945] client session: stateChange:2->0 1454579431741.2519.AkU5fw==
,2016-02-04 10:50:41.252 ThaliTest[626:953945] jxcore: disconnect: success
,ok 101 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,2016-02-04 10:50:42.233 ThaliTest[626:955714] server session: not connected 1454579431741.2519
,calling stopBroadcasting

,2016-02-04 10:50:56.393 ThaliTest[626:953945] jxcore: stopBroadcasting
,2016-02-04 10:50:56.394 ThaliTest[626:953945] THEMultipeerSession stopping peer
,2016-02-04 10:50:56.394 ThaliTest[626:953945] multipeer session: stop timer
,2016-02-04 10:50:56.395 ThaliTest[626:953945] server session: disconnect
2016-02-04 10:50:56.396 ThaliTest[626:953945] server session: stateChange:2->0 1454579431741.2519
,2016-02-04 10:50:56.404 ThaliTest[626:953945] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter handles socket disconnect correctly

,# teardown

,echo server started on port: 52940

,2016-02-04 10:50:58.964 ThaliTest[626:953945] jxcore: startBroadcasting
,2016-02-04 10:50:58.968 ThaliTest[626:953945] server: starting 1454579458964.626.q01zJg==
,2016-02-04 10:50:58.968 ThaliTest[626:953945] multipeer session: start timer: 0x147317e0
,2016-02-04 10:50:58.969 ThaliTest[626:953945] THEMultipeerSession initialized peer 1454579458964.626
2016-02-04 10:50:58.970 ThaliTest[626:953945] jxcore: startBroadcasting: success
,ok 102 Should be able to call startBroadcasting without error

,2016-02-04 10:50:59.900 ThaliTest[626:953703] client: found peer: 1454579431741.2519.AkU5fw==
,[{"peerIdentifier":"1454579431741.2519.AkU5fw==","peerName":"(null)","peerAvailable":true}]

,2016-02-04 10:50:59.904 ThaliTest[626:953945] jxcore: connect 1454579431741.2519.AkU5fw==
,2016-02-04 10:50:59.905 ThaliTest[626:953945] client session: connect
,2016-02-04 10:50:59.906 ThaliTest[626:953945] client session: stateChange:0->1 1454579431741.2519.AkU5fw==
,2016-02-04 10:51:09.604 ThaliTest[626:953703] multipeer session: reset timer
2016-02-04 10:51:09.605 ThaliTest[626:953703] multipeer session: stop timer
2016-02-04 10:51:09.605 ThaliTest[626:953703] multipeer session: start timer: 0x147317e0
2016-02-04 ,10:51:09.605 ThaliTest[626:953703] server session: connect
2016-02-04 10:51:09.606 ThaliTest[626:953703] server session: stateChange:0->1 1454579466514.2519
,2016-02-04 10:51:09.613 ThaliTest[626:953703] server: accepting invitation 1454579466514.2519
,2016-02-04 10:51:09.901 ThaliTest[626:953703] client: found peer: 1454579466514.2519.fpP7ow==
[{"peerIdentifier":"1454579466514.2519.fpP7ow==","peerName":"(null)","peerAvailable":true}]

,2016-02-04 10:51:09.902 ThaliTest[626:953945] jxcore: connect 1454579466514.2519.fpP7ow==
2016-02-04 10:51:09.902 ThaliTest[626:953945] client session: connect
2016-02-04 10:51:09.903 ThaliTest[626:953945] client session: stateChange:0->1 1454579466514.2519.fpP7ow==
,2016-02-04 10:51:13.056 ThaliTest[626:955843] server session: connected
2016-02-04 10:51:13.056 ThaliTest[626:955843] server session: stateChange:1->2 1454579466514.2519
,2016-02-04 10:51:13.837 ThaliTest[626:953703] server relay: connected (to port: 52940)
,2016-02-04 10:51:13.865 ThaliTest[626:955806] client session: connected
2016-02-04 10:51:13.865 ThaliTest[626:955806] client session: stateChange:1->2 1454579466514.2519.fpP7ow==
,2016-02-04 10:51:13.939 ThaliTest[626:953703] client: lost peer: 1454579431741.2519.AkU5fw==
2016-02-04 10:51:13.940 ThaliTest[626:953703] client session: onPeerLost: 1454579431741.2519.AkU5fw==
,2016-02-04 10:51:13.940 ThaliTest[626:953703] client session: onLinkFailure: 1454579431741.2519.AkU5fw==
2016-02-04 10:51:13.940 ThaliTest[626:953703] client session: disconnect
,2016-02-04 10:51:13.941 ThaliTest[626:953703] client session: stateChange:1->0 1454579431741.2519.AkU5fw==
2016-02-04 10:51:13.941 ThaliTest[626:953703] client session: fireConnectCallback: 1454579431741.2519.AkU5fw==
,2016-02-04 10:51:13.942 ThaliTest[626:953703] jxcore: connect: fail: Peer disconnected
,[{"peerIdentifier":"1454579431741.2519.AkU5fw==","peerName":"(null)","peerAvailable":false}]

,2016-02-04 10:51:14.335 ThaliTest[626:955843] client session: fireConnectCallback: 1454579466514.2519.fpP7ow==
2016-02-04 10:51:14.335 ThaliTest[626:955843] jxcore: connect: success
,ok 103 Should be able to connect without error

,ok 104 Port should be within range

,ok 105 First connect should succeed

,2016-02-04 10:51:14.396 ThaliTest[626:953703] client: relay established
,2016-02-04 10:51:14.397 ThaliTest[626:953703] client: new accepted socket: 0x16293a40
,2016-02-04 10:51:14.544 ThaliTest[626:955843] server session: not connected 1454579466514.2519
,ok 106 the test messages should be equal

ok 107 First send should succeed

,2016-02-04 10:51:14.602 ThaliTest[626:953703] client: socket closed
2016-02-04 10:51:14.602 ThaliTest[626:953703] client relay: socket disconnected
,2016-02-04 10:51:14.602 ThaliTest[626:953703] client relay: 0x16293a40 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-02-04 10:51:14,.603 ThaliTest[626:953703] client session: socket closed: 1454579466514.2519.fpP7ow==
2016-02-04 10:51:14.603 ThaliTest[626:953703] client session: onLinkFailure: 1454579466514.2519.fpP7ow==
2016-02-04 10:51:14.603 ThaliTest[626:953703] client session: d,isconnect
2016-02-04 10:51:14.604 ThaliTest[626:953703] client session: stateChange:2->0 1454579466514.2519.fpP7ow==
,2016-02-04 10:51:14.616 ThaliTest[626:953703] client session: fireConnectionErrorEvent: 1454579466514.2519.fpP7ow==
,2016-02-04 10:51:14.620 ThaliTest[626:953945] jxcore: connect 1454579466514.2519.fpP7ow==
2016-02-04 10:51:14.622 ThaliTest[626:953945] client session: connect
2016-02-04 10:51:14.622 ThaliTest[626:953945] client session: stateChange:0->1 1454579466514.2519.fpP7ow==
,2016-02-04 10:51:14.663 ThaliTest[626:953703] multipeer session: reset timer
2016-02-04 10:51:14.663 ThaliTest[626:953703] multipeer session: stop timer
2016-02-04 10:51:14.664 ThaliTest[626:953703] multipeer session: start timer: 0x147317e0
,2016-02-04 10:51:14.664 ThaliTest[626:953703] server: disconnecting to refresh session (1454579466514.2519)
2016-02-04 10:51:14.664 ThaliTest[626:953703] server session: disconnect
,2016-02-04 10:51:14.665 ThaliTest[626:953703] server session: stateChange:2->0 1454579466514.2519
,2016-02-04 10:51:14.668 ThaliTest[626:953703] server session: connect
2016-02-04 10:51:14.668 ThaliTest[626:953703] server session: stateChange:0->1 1454579466514.2519
,2016-02-04 10:51:14.678 ThaliTest[626:953703] server: accepting invitation 1454579466514.2519
,2016-02-04 10:51:14.953 ThaliTest[626:953945] jxcore: connect 1454579431741.2519.AkU5fw==
2016-02-04 10:51:14.953 ThaliTest[626:953945] client: connect: unreachable 1454579431741.2519.AkU5fw==
2016-02-04 10:51:14.953 ThaliTest[626:953945] jxcore: connect: fail: Peer unreachable
,2016-02-04 10:51:17.012 ThaliTest[626:955843] server session: connected
2016-02-04 10:51:17.012 ThaliTest[626:955843] server session: stateChange:1->2 1454579466514.2519
,2016-02-04 10:51:17.073 ThaliTest[626:953703] server relay: connected (to port: 52940)
,2016-02-04 10:51:17.567 ThaliTest[626:955843] client session: connected
2016-02-04 10:51:17.568 ThaliTest[626:955843] client session: stateChange:1->2 1454579466514.2519.fpP7ow==
,2016-02-04 10:51:17.785 ThaliTest[626:955806] server session: not connected 1454579466514.2519
,2016-02-04 10:51:18.111 ThaliTest[626:955806] client session: fireConnectCallback: 1454579466514.2519.fpP7ow==
2016-02-04 10:51:18.111 ThaliTest[626:955806] jxcore: connect: success
,ok 108 Should be able to connect without error

,ok 109 Port should be within range

,ok 110 Second connect should succeed

,2016-02-04 10:51:18.147 ThaliTest[626:953703] client: relay established
2016-02-04 10:51:18.148 ThaliTest[626:953703] client: new accepted socket: 0x145008c0
,ok 111 the test messages should be equal

,ok 112 Second send should succeed

,# setup

,2016-02-04 10:51:18.476 ThaliTest[626:953703] client: socket closed
,2016-02-04 10:51:18.477 ThaliTest[626:953703] client relay: socket disconnected
,2016-02-04 10:51:18.477 ThaliTest[626:953703] client relay: 0x145008c0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-02-04 10:51:18.477 ThaliTest[626:953703] client session: socket closed: 1454579466514.2519.fpP7ow==
,2016-02-04 10:51:18.478 ThaliTest[626:953703] client session: onLinkFailure: 1454579466514.2519.fpP7ow==
2016-02-04 10:51:18.478 ThaliTest[626:953703] client session: disconnect
2016-02-04 10:51:18.478 ThaliTest[626:953703] client session: stateChange:2->0 1454579466514.2519.fpP7ow==
,2016-02-04 10:51:18.550 ThaliTest[626:953703] client session: fireConnectionErrorEvent: 1454579466514.2519.fpP7ow==
,calling stopBroadcasting

,2016-02-04 10:51:18.601 ThaliTest[626:953945] jxcore: stopBroadcasting
,2016-02-04 10:51:18.602 ThaliTest[626:953945] THEMultipeerSession stopping peer
,2016-02-04 10:51:18.602 ThaliTest[626:953945] multipeer session: stop timer
,2016-02-04 10:51:18.604 ThaliTest[626:953945] server session: disconnect
2016-02-04 10:51:18.604 ThaliTest[626:953945] server session: stateChange:2->0 1454579466514.2519
,2016-02-04 10:51:18.610 ThaliTest[626:953945] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliReplicationManager can call start without error

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/A6E308A6-CB41-4BF3-AB74-63397F3D0990/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,ok 113 starting event should occur in right order

,2016-02-04 10:51:19.820 ThaliTest[626:953945] jxcore: startBroadcasting
,2016-02-04 10:51:19.822 ThaliTest[626:953945] server: starting sHzSv3s8Iw4JCCeRW84Z8A.rvXO3Q==
,2016-02-04 10:51:19.822 ThaliTest[626:953945] multipeer session: start timer: 0x16657720
2016-02-04 10:51:19.822 ThaliTest[626:953945] THEMultipeerSession initialized peer sHzSv3s8Iw4JCCeRW84Z8A
2016-02-04 10:51:19.822 ThaliTest[626:953945] jxcore: startBroadcasting: success
,ok 114 started event should occur in right order

Now in TRM stop

State of this._isStarted: true

ok 115 stopping event should occur in right order

About to call stopBroadcasting

,2016-02-04 10:51:19.824 ThaliTest[626:953945] jxcore: stopBroadcasting
2016-02-04 10:51:19.824 ThaliTest[626:953945] THEMultipeerSession stopping peer
2016-02-04 10:51:19.824 ThaliTest[626:953945] multipeer session: stop timer
,2016-02-04 10:51:19.824 ThaliTest[626:953945] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined
,
,ok 116 stopped event should occur in right order

,mux server bridge listener closed

# setup

,# ThaliReplicationManager receives identity

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/A6E308A6-CB41-4BF3-AB74-63397F3D0990/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-02-04 10:51:23.819 ThaliTest[626:953945] jxcore: startBroadcasting
,2016-02-04 10:51:23.822 ThaliTest[626:953945] server: starting sHzSv3s8Iw4JCCeRW84Z8A.x7/7ng==
,2016-02-04 10:51:23.823 ThaliTest[626:953945] multipeer session: start timer: 0x145eeba0
2016-02-04 10:51:23.824 ThaliTest[626:953945] THEMultipeerSession initialized peer sHzSv3s8Iw4JCCeRW84Z8A
2016-02-04 10:51:23.824 ThaliTest[626:953945] jxcore: start,Broadcasting: success
ok 117 getDeviceIdentity should not return an error

,ok 118 deviceName should not be null

,Now in TRM stop

,State of this._isStarted: true

,About to call stopBroadcasting

,2016-02-04 10:51:23.830 ThaliTest[626:953945] jxcore: stopBroadcasting
2016-02-04 10:51:23.830 ThaliTest[626:953945] THEMultipeerSession stopping peer
2016-02-04 10:51:23.830 ThaliTest[626:953945] multipeer session: stop timer
2016-02-04 10:51:23.831 ThaliTest[626:953945] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,mux server bridge listener closed

# setup

,# ThaliReplicationManager replicates database


```
