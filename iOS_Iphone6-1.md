#### Test 549702610b97681_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/549702610b97681/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/A747E9EF-EAFE-4AEA-AB69-5A207682B7A6/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/A747E9EF-EAFE-4AEA-AB69-5A207682B7A6/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/549702610b97681/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/549702610b97681/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/4775B99D-5282-4A7B-AEBD-D168CE7E4A40/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51516"
,(lldb)     command script import "/tmp/A747E9EF-EAFE-4AEA-AB69-5A207682B7A6/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-09 00:03:57.157 ThaliTest[1603:3305203] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C0470A19-A292-4FAD-BE7C-4891FF17C72C/Library/Cookies/Cookies.binarycookies
,2016-01-09 00:03:57.580 ThaliTest[1603:3305203] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-09 00:03:57.581 ThaliTest[1603:3305203] Multi-tasking -> Device: YES, App: YES
,2016-01-09 00:03:57.592 ThaliTest[1603:3305203] Unlimited access to network resources
,2016-01-09 00:03:57.606 ThaliTest[1603:3305203] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-09 00:04:06.803 ThaliTest[1603:3305203] Resetting plugins due to page load.
,2016-01-09 00:04:10.121 ThaliTest[1603:3305203] Finished load of: file:///var/mobile/Containers/Bundle/Application/4775B99D-5282-4A7B-AEBD-D168CE7E4A40/ThaliTest.app/www/index.html
,2016-01-09 00:04:10.314 ThaliTest[1603:3305203] JXcore Cordova plugin initializing
2016-01-09 00:04:10.315 ThaliTest[1603:3305414] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,My device name is: Apple-Iphone6-1
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
# setup
,# successfully read a previous pkcs12 file and return hash value
,# teardown
,ok 9 (unnamed assert)
,ok 10 (unnamed assert)
ok 11 should not throw
,ok 12 should be equal
,ok 13 should be equal
,# setup
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
,ok 18 should be equal
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
,ok 28 should be equal
,# setup
,# #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
,# teardown
,ok 29 should be equal
,ok 30 should be equal
,ok 31 should be equal
,# setup
,# #stopBroadcasting should call Mobile("StopBroadcasting") without an error
,# teardown
,ok 32 should be equal
,ok 33 should be equal
,# setup
,# #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
,# teardown
,ok 34 should be equal
,ok 35 should be equal
,# setup
,# #connect should call Mobile("Connect") with a port and without an error
,# teardown
,ok 36 should be equal
,ok 37 should be equal
,ok 38 should be equal
,# setup
,# #connect should call Mobile("Connect") and handle an error
,# teardown
,ok 39 should be equal
,ok 40 should be equal
,# setup
,# should call Mobile("Disconnect") without an error
,# teardown
,ok 41 should be equal
,ok 42 should be equal
,# setup
,# should call Mobile("Disconnect") and handle an error
,# teardown
,ok 43 should be equal
,ok 44 should be equal
,# setup
,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
,# teardown
,2016-01-09 00:08:32.357 ThaliTest[1603:3305414] jxcore: startBroadcasting
,2016-01-09 00:08:32.372 ThaliTest[1603:3305414] server: starting 1452294512356.1603.TWYhgw==
,2016-01-09 00:08:32.377 ThaliTest[1603:3305414] multipeer session: start timer: 0x187da5c0
,2016-01-09 00:08:32.388 ThaliTest[1603:3305414] THEMultipeerSession initialized peer 1452294512356.1603
,2016-01-09 00:08:32.389 ThaliTest[1603:3305414] jxcore: startBroadcasting: success
,ok 45 Should be able to call startBroadcasting without error
,2016-01-09 00:08:32.393 ThaliTest[1603:3305414] jxcore: stopBroadcasting
,2016-01-09 00:08:32.394 ThaliTest[1603:3305414] THEMultipeerSession stopping peer
,2016-01-09 00:08:32.395 ThaliTest[1603:3305414] multipeer session: stop timer
,2016-01-09 00:08:32.402 ThaliTest[1603:3305414] jxcore: stopBroadcasting: success
,ok 46 Should be able to call stopBroadcasting without error
,2016-01-09 00:08:32.406 ThaliTest[1603:3305414] jxcore: startBroadcasting
,2016-01-09 00:08:32.412 ThaliTest[1603:3305414] server: starting 1452294512405.1603.4Zo5tQ==
,2016-01-09 00:08:32.415 ThaliTest[1603:3305414] multipeer session: start timer: 0x187dd390
,2016-01-09 00:08:32.425 ThaliTest[1603:3305414] THEMultipeerSession initialized peer 1452294512405.1603
,2016-01-09 00:08:32.427 ThaliTest[1603:3305414] jxcore: startBroadcasting: success
,ok 47 Should be able to call startBroadcasting without error
,2016-01-09 00:08:32.431 ThaliTest[1603:3305414] jxcore: stopBroadcasting
,2016-01-09 00:08:32.432 ThaliTest[1603:3305414] THEMultipeerSession stopping peer
,2016-01-09 00:08:32.433 ThaliTest[1603:3305414] multipeer session: stop timer
,2016-01-09 00:08:32.440 ThaliTest[1603:3305414] jxcore: stopBroadcasting: success
,ok 48 Should be able to call stopBroadcasting without error
,2016-01-09 00:08:32.444 ThaliTest[1603:3305414] jxcore: startBroadcasting
,2016-01-09 00:08:32.448 ThaliTest[1603:3305414] server: starting 1452294512443.1603.+lxEpA==
,2016-01-09 00:08:32.450 ThaliTest[1603:3305414] multipeer session: start timer: 0x1832fc40
,2016-01-09 00:08:32.458 ThaliTest[1603:3305414] THEMultipeerSession initialized peer 1452294512443.1603
,2016-01-09 00:08:32.459 ThaliTest[1603:3305414] jxcore: startBroadcasting: success
,ok 49 Should be able to call startBroadcasting without error
,2016-01-09 00:08:32.462 ThaliTest[1603:3305414] jxcore: stopBroadcasting
,2016-01-09 00:08:32.463 ThaliTest[1603:3305414] THEMultipeerSession stopping peer
,2016-01-09 00:08:32.464 ThaliTest[1603:3305414] multipeer session: stop timer
,2016-01-09 00:08:32.466 ThaliTest[1603:3305414] jxcore: stopBroadcasting: success
,ok 50 Should be able to call stopBroadcasting without error
,2016-01-09 00:08:32.470 ThaliTest[1603:3305414] jxcore: startBroadcasting
,2016-01-09 00:08:32.473 ThaliTest[1603:3305414] server: starting 1452294512470.1603.dFeozg==
,2016-01-09 00:08:32.476 ThaliTest[1603:3305414] multipeer session: start timer: 0x187de0e0
,2016-01-09 00:08:32.482 ThaliTest[1603:3305414] THEMultipeerSession initialized peer 1452294512470.1603
,2016-01-09 00:08:32.483 ThaliTest[1603:3305414] jxcore: startBroadcasting: success
,ok 51 Should be able to call startBroadcasting without error
,2016-01-09 00:08:32.485 ThaliTest[1603:3305414] jxcore: stopBroadcasting
,2016-01-09 00:08:32.486 ThaliTest[1603:3305414] THEMultipeerSession stopping peer
,2016-01-09 00:08:32.487 ThaliTest[1603:3305414] multipeer session: stop timer
,2016-01-09 00:08:32.489 ThaliTest[1603:3305414] jxcore: stopBroadcasting: success
,ok 52 Should be able to call stopBroadcasting without error
,2016-01-09 00:08:32.494 ThaliTest[1603:3305414] jxcore: startBroadcasting
,2016-01-09 00:08:32.496 ThaliTest[1603:3305414] server: starting 1452294512493.1603.UzlglQ==
,2016-01-09 00:08:32.498 ThaliTest[1603:3305414] multipeer session: start timer: 0x187de7b0
,2016-01-09 00:08:32.502 ThaliTest[1603:3305414] THEMultipeerSession initialized peer 1452294512493.1603
,2016-01-09 00:08:32.504 ThaliTest[1603:3305414] jxcore: startBroadcasting: success
,ok 53 Should be able to call startBroadcasting without error
,2016-01-09 00:08:32.507 ThaliTest[1603:3305414] jxcore: stopBroadcasting
,2016-01-09 00:08:32.508 ThaliTest[1603:3305414] THEMultipeerSession stopping peer
,2016-01-09 00:08:32.509 ThaliTest[1603:3305414] multipeer session: stop timer
,2016-01-09 00:08:32.514 ThaliTest[1603:3305414] jxcore: stopBroadcasting: success
,ok 54 Should be able to call stopBroadcasting without error
,2016-01-09 00:08:32.516 ThaliTest[1603:3305414] jxcore: startBroadcasting
,2016-01-09 00:08:32.519 ThaliTest[1603:3305414] server: starting 1452294512516.1603.rGzKQQ==
,2016-01-09 00:08:32.521 ThaliTest[1603:3305414] multipeer session: start timer: 0x187de430
,2016-01-09 00:08:32.524 ThaliTest[1603:3305414] THEMultipeerSession initialized peer 1452294512516.1603
,2016-01-09 00:08:32.526 ThaliTest[1603:3305414] jxcore: startBroadcasting: success
,ok 55 Should be able to call startBroadcasting without error
,2016-01-09 00:08:32.530 ThaliTest[1603:3305414] jxcore: stopBroadcasting
,2016-01-09 00:08:32.530 ThaliTest[1603:3305414] THEMultipeerSession stopping peer
,2016-01-09 00:08:32.531 ThaliTest[1603:3305414] multipeer session: stop timer
,2016-01-09 00:08:32.533 ThaliTest[1603:3305414] jxcore: stopBroadcasting: success
,ok 56 Should be able to call stopBroadcasting without error
,2016-01-09 00:08:32.538 ThaliTest[1603:3305414] jxcore: startBroadcasting
,2016-01-09 00:08:32.541 ThaliTest[1603:3305414] server: starting 1452294512537.1603.JGJGYw==
,2016-01-09 00:08:32.543 ThaliTest[1603:3305414] multipeer session: start timer: 0x187e0100
,2016-01-09 00:08:32.548 ThaliTest[1603:3305414] THEMultipeerSession initialized peer 1452294512537.1603
,2016-01-09 00:08:32.550 ThaliTest[1603:3305414] jxcore: startBroadcasting: success
,ok 57 Should be able to call startBroadcasting without error
,2016-01-09 00:08:32.554 ThaliTest[1603:3305414] jxcore: stopBroadcasting
,2016-01-09 00:08:32.555 ThaliTest[1603:3305414] THEMultipeerSession stopping peer
,2016-01-09 00:08:32.555 ThaliTest[1603:3305414] multipeer session: stop timer
,2016-01-09 00:08:32.557 ThaliTest[1603:3305414] jxcore: stopBroadcasting: success
,ok 58 Should be able to call stopBroadcasting without error
,2016-01-09 00:08:32.562 ThaliTest[1603:3305414] jxcore: startBroadcasting
,2016-01-09 00:08:32.564 ThaliTest[1603:3305414] server: starting 1452294512561.1603.WGRCEw==
,2016-01-09 00:08:32.565 ThaliTest[1603:3305414] multipeer session: start timer: 0x16d4a8c0
,2016-01-09 00:08:32.568 ThaliTest[1603:3305414] THEMultipeerSession initialized peer 1452294512561.1603
,2016-01-09 00:08:32.569 ThaliTest[1603:3305414] jxcore: startBroadcasting: success
,ok 59 Should be able to call startBroadcasting without error
,2016-01-09 00:08:32.572 ThaliTest[1603:3305414] jxcore: stopBroadcasting
,2016-01-09 00:08:32.572 ThaliTest[1603:3305414] THEMultipeerSession stopping peer
,2016-01-09 00:08:32.573 ThaliTest[1603:3305414] multipeer session: stop timer
,2016-01-09 00:08:32.575 ThaliTest[1603:3305414] jxcore: stopBroadcasting: success
,ok 60 Should be able to call stopBroadcasting without error
,2016-01-09 00:08:32.578 ThaliTest[1603:3305414] jxcore: startBroadcasting
,2016-01-09 00:08:32.580 ThaliTest[1603:3305414] server: starting 1452294512578.1603.petc4w==
,2016-01-09 00:08:32.583 ThaliTest[1603:3305414] multipeer session: start timer: 0x187e17e0
,2016-01-09 00:08:32.586 ThaliTest[1603:3305414] THEMultipeerSession initialized peer 1452294512578.1603
,2016-01-09 00:08:32.588 ThaliTest[1603:3305414] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error
,2016-01-09 00:08:32.590 ThaliTest[1603:3305414] jxcore: stopBroadcasting
,2016-01-09 00:08:32.591 ThaliTest[1603:3305414] THEMultipeerSession stopping peer
,2016-01-09 00:08:32.591 ThaliTest[1603:3305414] multipeer session: stop timer
,2016-01-09 00:08:32.593 ThaliTest[1603:3305414] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error
,2016-01-09 00:08:32.596 ThaliTest[1603:3305414] jxcore: startBroadcasting
,2016-01-09 00:08:32.599 ThaliTest[1603:3305414] server: starting 1452294512596.1603.UQnK4Q==
,2016-01-09 00:08:32.600 ThaliTest[1603:3305414] multipeer session: start timer: 0x187e26c0
,2016-01-09 00:08:32.602 ThaliTest[1603:3305414] THEMultipeerSession initialized peer 1452294512596.1603
,2016-01-09 00:08:32.604 ThaliTest[1603:3305414] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error
,2016-01-09 00:08:32.606 ThaliTest[1603:3305414] jxcore: stopBroadcasting
,2016-01-09 00:08:32.607 ThaliTest[1603:3305414] THEMultipeerSession stopping peer
,2016-01-09 00:08:32.607 ThaliTest[1603:3305414] multipeer session: stop timer
,2016-01-09 00:08:32.609 ThaliTest[1603:3305414] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter calls startBroadcasting twice with error
,# teardown
,2016-01-09 00:08:32.766 ThaliTest[1603:3305414] jxcore: startBroadcasting
,2016-01-09 00:08:32.770 ThaliTest[1603:3305414] server: starting 1452294512766.1603.c2Wpog==
,2016-01-09 00:08:32.773 ThaliTest[1603:3305414] multipeer session: start timer: 0x187e2170
,2016-01-09 00:08:32.779 ThaliTest[1603:3305414] THEMultipeerSession initialized peer 1452294512766.1603
,2016-01-09 00:08:32.784 ThaliTest[1603:3305414] jxcore: startBroadcasting: success
,ok 65 Should be able to call startBroadcasting without error
,2016-01-09 00:08:32.789 ThaliTest[1603:3305414] jxcore: startBroadcasting
,2016-01-09 00:08:32.790 ThaliTest[1603:3305414] jxcore: startBroadcasting: failure
,ok 66 Cannot call startBroadcasting twice
,2016-01-09 00:08:32.795 ThaliTest[1603:3305414] jxcore: stopBroadcasting
,2016-01-09 00:08:32.796 ThaliTest[1603:3305414] THEMultipeerSession stopping peer
,2016-01-09 00:08:32.797 ThaliTest[1603:3305414] multipeer session: stop timer
,2016-01-09 00:08:32.802 ThaliTest[1603:3305414] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on connection to bad peer
,# teardown
,2016-01-09 00:08:33.245 ThaliTest[1603:3305414] jxcore: startBroadcasting
,2016-01-09 00:08:33.249 ThaliTest[1603:3305414] server: starting 1452294513245.1603.A3tVng==
2016-01-09 00:08:33.250 ThaliTest[1603:3305414] multipeer session: start timer: 0x187c28c0
2016-01-09 00:08:33.250 ThaliTest[1603:3305414] THEMultipeerSession in,itialized peer 1452294513245.1603
2016-01-09 00:08:33.250 ThaliTest[1603:3305414] jxcore: startBroadcasting: success
ok 68 Should be able to call startBroadcasting without error
2016-01-09 00:08:33.253 ThaliTest[1603:3305414] jxcore: connect foobar
201,6-01-09 00:08:33.253 ThaliTest[1603:3305414] client: unknown peer foobar
2016-01-09 00:08:33.253 ThaliTest[1603:3305414] jxcore: connect: fail: Unknown peer
,ok 69 Should not connect to a bad peer
,2016-01-09 00:08:33.257 ThaliTest[1603:3305414] jxcore: stopBroadcasting
,2016-01-09 00:08:33.258 ThaliTest[1603:3305414] THEMultipeerSession stopping peer
,2016-01-09 00:08:33.258 ThaliTest[1603:3305414] multipeer session: stop timer
,2016-01-09 00:08:33.272 ThaliTest[1603:3305414] jxcore: stopBroadcasting: success
,ok 70 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on disconnect to bad peer
,# teardown
,2016-01-09 00:08:33.337 ThaliTest[1603:3305414] jxcore: startBroadcasting
,2016-01-09 00:08:33.341 ThaliTest[1603:3305414] server: starting 1452294513337.1603.FE4aMg==
,2016-01-09 00:08:33.344 ThaliTest[1603:3305414] multipeer session: start timer: 0x187c5a30
,2016-01-09 00:08:33.352 ThaliTest[1603:3305414] THEMultipeerSession initialized peer 1452294513337.1603
,2016-01-09 00:08:33.354 ThaliTest[1603:3305414] jxcore: startBroadcasting: success
,ok 71 Should be able to call startBroadcasting without error
,2016-01-09 00:08:33.358 ThaliTest[1603:3305414] jxcore: disconnect
,2016-01-09 00:08:33.360 ThaliTest[1603:3305414] jxcore: disconnect: fail
,ok 72 Disconnect should fail to a non-existant peer 
,2016-01-09 00:08:33.364 ThaliTest[1603:3305414] jxcore: stopBroadcasting
,2016-01-09 00:08:33.366 ThaliTest[1603:3305414] THEMultipeerSession stopping peer
,2016-01-09 00:08:33.368 ThaliTest[1603:3305414] multipeer session: stop timer
,2016-01-09 00:08:33.371 ThaliTest[1603:3305414] jxcore: stopBroadcasting: success
,ok 73 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter can discover and connect to peers
,# teardown
,2016-01-09 00:08:34.966 ThaliTest[1603:3305414] jxcore: startBroadcasting
,2016-01-09 00:08:34.969 ThaliTest[1603:3305414] server: starting 1452294514965.1603.XskMJQ==
2016-01-09 00:08:34.970 ThaliTest[1603:3305414] multipeer session: start timer: 0x187c7de0
2016-01-09 00:08:34.971 ThaliTest[1603:3305414] THEMultipeerSession in,itialized peer 1452294514965.1603
2016-01-09 00:08:34.972 ThaliTest[1603:3305414] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error
,2016-01-09 00:08:36.162 ThaliTest[1603:3305203] client: found peer: 1452294514891.1155.yOzLtg==
,2016-01-09 00:08:36.165 ThaliTest[1603:3305414] jxcore: connect 1452294514891.1155.yOzLtg==
2016-01-09 00:08:36.165 ThaliTest[1603:3305414] client session: connect
2016-01-09 00:08:36.165 ThaliTest[1603:3305414] client session: stateChange:0->1 1452294514891.1155.yOzLtg==
,2016-01-09 00:08:36.239 ThaliTest[1603:3305203] multipeer session: reset timer
2016-01-09 00:08:36.239 ThaliTest[1603:3305203] multipeer session: stop timer
2016-01-09 00:08:36.240 ThaliTest[1603:3305203] multipeer session: start timer: 0x187c7de0
,2016-01-09 00:08:36.240 ThaliTest[1603:3305203] server session: connect
2016-01-09 00:08:36.242 ThaliTest[1603:3305203] server session: stateChange:0->1 1452294514891.1155
,2016-01-09 00:08:36.252 ThaliTest[1603:3305203] server: accepting invitation 1452294514891.1155
,2016-01-09 00:08:38.861 ThaliTest[1603:3305832] server session: connected
2016-01-09 00:08:38.861 ThaliTest[1603:3305832] server session: stateChange:1->2 1452294514891.1155
,2016-01-09 00:08:38.867 ThaliTest[1603:3305203] server relay: socket disconnected
2016-01-09 00:08:38.868 ThaliTest[1603:3305203] server relay: 0x187cbec0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-09 00:08:38.927 ThaliTest[1603:3305866] client session: connected
,2016-01-09 00:08:38.927 ThaliTest[1603:3305866] client session: stateChange:1->2 1452294514891.1155.yOzLtg==
,2016-01-09 00:08:39.701 ThaliTest[1603:3305866] client session: fireConnectCallback: 1452294514891.1155.yOzLtg==
2016-01-09 00:08:39.701 ThaliTest[1603:3305866] jxcore: connect: success
,ok 75 Should be able to connect without error
,ok 76 Port should be within range
,2016-01-09 00:08:39.707 ThaliTest[1603:3305414] jxcore: disconnect
2016-01-09 00:08:39.708 ThaliTest[1603:3305414] client session: disconnectFromPeer: 1452294514891.1155.yOzLtg==
2016-01-09 00:08:39.708 ThaliTest[1603:3305414] client session: disconnect,
2016-01-09 00:08:39.708 ThaliTest[1603:3305414] client session: stateChange:2->0 1452294514891.1155.yOzLtg==
,2016-01-09 00:08:39.721 ThaliTest[1603:3305414] jxcore: disconnect: success
ok 77 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
,2016-01-09 00:08:41.452 ThaliTest[1603:3305414] jxcore: stopBroadcasting
2016-01-09 00:08:41.453 ThaliTest[1603:3305414] THEMultipeerSession stopping peer
2016-01-09 00:08:41.453 ThaliTest[1603:3305414] multipeer session: stop timer
2016-01-09 00:08:41.454 ThaliTest[1603:3305414] server session: disconnect
2016-01-09 00:08:41.454 ThaliTest[1603:3305414] server session: stateChange:2->0 1452294514891.1155
,2016-01-09 00:08:41.485 ThaliTest[1603:3305414] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter can discover and connect to peers and then fail on double connect
,# teardown
,2016-01-09 00:09:03.640 ThaliTest[1603:3305414] jxcore: startBroadcasting
,2016-01-09 00:09:03.643 ThaliTest[1603:3305414] server: starting 1452294543639.1603.1SENGA==
2016-01-09 00:09:03.644 ThaliTest[1603:3305414] multipeer session: start timer: 0x182dd400
2016-01-09 00:09:03.645 ThaliTest[1603:3305414] THEMultipeerSession in,itialized peer 1452294543639.1603
2016-01-09 00:09:03.645 ThaliTest[1603:3305414] jxcore: startBroadcasting: success
ok 78 Should be able to call startBroadcasting without error
,2016-01-09 00:09:04.872 ThaliTest[1603:3305203] client: found peer: 1452294543523.1155.3lGMTw==
2016-01-09 00:09:04.874 ThaliTest[1603:3305414] jxcore: connect 1452294543523.1155.3lGMTw==
2016-01-09 00:09:04.875 ThaliTest[1603:3305414] client session: connect
2016-01-09 00:09:04.875 ThaliTest[1603:3305414] client session: stateChange:0->1 1452294543523.1155.3lGMTw==
,2016-01-09 00:09:05.561 ThaliTest[1603:3305203] multipeer session: reset timer
2016-01-09 00:09:05.561 ThaliTest[1603:3305203] multipeer session: stop timer
2016-01-09 00:09:05.561 ThaliTest[1603:3305203] multipeer session: start timer: 0x182dd400
2016-,01-09 00:09:05.562 ThaliTest[1603:3305203] server session: connect
2016-01-09 00:09:05.562 ThaliTest[1603:3305203] server session: stateChange:0->1 1452294543523.1155
,2016-01-09 00:09:05.571 ThaliTest[1603:3305203] server: accepting invitation 1452294543523.1155
,2016-01-09 00:09:08.149 ThaliTest[1603:3305920] client session: connected
2016-01-09 00:09:08.149 ThaliTest[1603:3305920] client session: stateChange:1->2 1452294543523.1155.3lGMTw==
2016-01-09 00:09:08.157 ThaliTest[1603:3305920] client session: fireCon,nectCallback: 1452294543523.1155.3lGMTw==
,2016-01-09 00:09:08.157 ThaliTest[1603:3305920] jxcore: connect: success
,ok 79 Should be able to connect without error
ok 80 Port should be within range
,2016-01-09 00:09:08.162 ThaliTest[1603:3305414] jxcore: connect 1452294543523.1155.3lGMTw==
,2016-01-09 00:09:08.163 ThaliTest[1603:3305414] client: already connect(ing/ed) to 1452294543523.1155.3lGMTw==
2016-01-09 00:09:08.163 ThaliTest[1603:3305414] jxcore: connect: fail: Aleady connecting
ok 81 Should fail on double connect
,2016-01-09 00:09:08.166 ThaliTest[1603:3305414] jxcore: disconnect
2016-01-09 00:09:08.167 ThaliTest[1603:3305414] client session: disconnectFromPeer: 1452294543523.1155.3lGMTw==
2016-01-09 00:09:08.167 ThaliTest[1603:3305414] client session: disconnect
2016-01-09 00:09:08.167 ThaliTest[1603:3305414] client session: stateChange:2->0 1452294543523.1155.3lGMTw==
,2016-01-09 00:09:08.244 ThaliTest[1603:3305414] jxcore: disconnect: success
,ok 82 Should be able to disconnect without error
,setting stopBroadcasting callback and ending test.
,# setup
,2016-01-09 00:09:08.348 ThaliTest[1603:3305950] server session: connected
2016-01-09 00:09:08.349 ThaliTest[1603:3305950] server session: stateChange:1->2 1452294543523.1155
2016-01-09 00:09:08.354 ThaliTest[1603:3305203] server relay: socket disconnecte,d
2016-01-09 00:09:08.354 ThaliTest[1603:3305203] server relay: 0x187cb220 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-09 00:09:08.394 ThaliTest[1603:3305920] server session: not connected 1452294543523.1155
,calling stopBroadcasting
,2016-01-09 00:09:08.456 ThaliTest[1603:3305414] jxcore: stopBroadcasting
2016-01-09 00:09:08.456 ThaliTest[1603:3305414] THEMultipeerSession stopping peer
2016-01-09 00:09:08.457 ThaliTest[1603:3305414] multipeer session: stop timer
2016-01-09 00:09:08.,457 ThaliTest[1603:3305414] server session: disconnect
2016-01-09 00:09:08.457 ThaliTest[1603:3305414] server session: stateChange:2->0 1452294543523.1155
2016-01-09 00:09:08.459 ThaliTest[1603:3305414] jxcore: stopBroadcasting: success
stopBroadcasting, returned undefined
,# ThaliEmitter can discover and connect to peers and then fail on double disconnect
,# teardown
,2016-01-09 00:09:08.999 ThaliTest[1603:3305414] jxcore: startBroadcasting
,2016-01-09 00:09:09.003 ThaliTest[1603:3305414] server: starting 1452294548999.1603./7PX5g==
2016-01-09 00:09:09.004 ThaliTest[1603:3305414] multipeer session: start timer: 0x16eb4550
2016-01-09 00:09:09.004 ThaliTest[1603:3305414] THEMultipeerSession in,itialized peer 1452294548999.1603
2016-01-09 00:09:09.004 ThaliTest[1603:3305414] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error
,2016-01-09 00:09:10.135 ThaliTest[1603:3305203] client: found peer: 1452294548987.1155.Cr861g==
2016-01-09 00:09:10.136 ThaliTest[1603:3305414] jxcore: connect 1452294548987.1155.Cr861g==
2016-01-09 00:09:10.137 ThaliTest[1603:3305414] client session: connect
,2016-01-09 00:09:10.137 ThaliTest[1603:3305414] client session: stateChange:0->1 1452294548987.1155.Cr861g==
,2016-01-09 00:09:10.239 ThaliTest[1603:3305203] multipeer session: reset timer
2016-01-09 00:09:10.240 ThaliTest[1603:3305203] multipeer session: stop timer
2016-01-09 00:09:10.240 ThaliTest[1603:3305203] multipeer session: start timer: 0x16eb4550
,2016-01-09 00:09:10.240 ThaliTest[1603:3305203] server session: connect
,2016-01-09 00:09:10.241 ThaliTest[1603:3305203] server session: stateChange:0->1 1452294548987.1155
,2016-01-09 00:09:10.253 ThaliTest[1603:3305203] server: accepting invitation 1452294548987.1155
,2016-01-09 00:09:13.202 ThaliTest[1603:3305949] client session: connected
2016-01-09 00:09:13.203 ThaliTest[1603:3305949] client session: stateChange:1->2 1452294548987.1155.Cr861g==
2016-01-09 00:09:13.207 ThaliTest[1603:3305950] server session: connect,ed
2016-01-09 00:09:13.207 ThaliTest[1603:3305950] server session: stateChange:1->2 1452294548987.1155
,2016-01-09 00:09:13.252 ThaliTest[1603:3305203] server relay: socket disconnected
2016-01-09 00:09:13.253 ThaliTest[1603:3305203] server relay: 0x187d1850 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLoc,alizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-09 00:09:13.270 ThaliTest[1603:3305949] client session: fireConnectCallback: 1452294548987.1155.Cr861g==
2016-01-09 00:09:13.271 ThaliTest[1603:3305949] jxcore: connect: success
,ok 84 Should be able to connect without error
,ok 85 Port should be within range
,2016-01-09 00:09:13.276 ThaliTest[1603:3305414] jxcore: disconnect
2016-01-09 00:09:13.276 ThaliTest[1603:3305414] client session: disconnectFromPeer: 1452294548987.1155.Cr861g==
2016-01-09 00:09:13.277 ThaliTest[1603:3305414] client session: disconnect,
2016-01-09 00:09:13.277 ThaliTest[1603:3305414] client session: stateChange:2->0 1452294548987.1155.Cr861g==
,2016-01-09 00:09:13.291 ThaliTest[1603:3305414] jxcore: disconnect: success
ok 86 Should be able to disconnect without error
2016-01-09 00:09:13.293 ThaliTest[1603:3305414] jxcore: disconnect
2016-01-09 00:09:13.293 ThaliTest[1603:3305414] jxcore: disco,nnect: fail
ok 87 Disconnect should fail 
setting stopBroadcasting callback and ending test.
,# setup
,2016-01-09 00:09:13.319 ThaliTest[1603:3305942] server session: not connected 1452294548987.1155
,calling stopBroadcasting
,2016-01-09 00:09:14.244 ThaliTest[1603:3305414] jxcore: stopBroadcasting
2016-01-09 00:09:14.245 ThaliTest[1603:3305414] THEMultipeerSession stopping peer
2016-01-09 00:09:14.245 ThaliTest[1603:3305414] multipeer session: stop timer
2016-01-09 00:09:14.,246 ThaliTest[1603:3305414] server session: disconnect
2016-01-09 00:09:14.246 ThaliTest[1603:3305414] server session: stateChange:2->0 1452294548987.1155
2016-01-09 00:09:14.248 ThaliTest[1603:3305414] jxcore: stopBroadcasting: success
stopBroadcasting, returned undefined
,# ThaliEmitter handles socket disconnect correctly
,# teardown
,2016-01-09 00:09:15.306 ThaliTest[1603:3305414] jxcore: startBroadcasting
,2016-01-09 00:09:15.310 ThaliTest[1603:3305414] server: starting 1452294555306.1603.7eKM8g==
2016-01-09 00:09:15.311 ThaliTest[1603:3305414] multipeer session: start timer: 0x185124c0
2016-01-09 00:09:15.312 ThaliTest[1603:3305414] THEMultipeerSession initialized peer 1452294555306.1603
2016-01-09 00:09:15.312 ThaliTest[1603:3305414] jxcore: startBroadcasting: success
ok 88 Should be able to call startBroadcasting without error
echo server started
,2016-01-09 00:09:16.395 ThaliTest[1603:3305203] client: found peer: 1452294555291.1155.+whsTw==
[{"peerIdentifier":"1452294555291.1155.+whsTw==","peerName":"(null)","peerAvailable":true}]
2016-01-09 00:09:16.398 ThaliTest[1603:3305414] jxcore: connect 1452294555291.1155.+whsTw==
,2016-01-09 00:09:16.398 ThaliTest[1603:3305414] client session: connect
2016-01-09 00:09:16.399 ThaliTest[1603:3305414] client session: stateChange:0->1 1452294555291.1155.+whsTw==
,2016-01-09 00:09:16.599 ThaliTest[1603:3305203] multipeer session: reset timer
2016-01-09 00:09:16.600 ThaliTest[1603:3305203] multipeer session: stop timer
2016-01-09 00:09:16.600 ThaliTest[1603:3305203] multipeer session: start timer: 0x185124c0
2016-01-09 00:09:16.600 ThaliTest[1603:3305203] server session: connect
2016-01-09 00:09:16.600 ThaliTest[1603:3305203] server session: stateChange:0->1 1452294555291.1155
,2016-01-09 00:09:16.610 ThaliTest[1603:3305203] server: accepting invitation 1452294555291.1155
,2016-01-09 00:09:19.226 ThaliTest[1603:3305942] server session: connected
2016-01-09 00:09:19.226 ThaliTest[1603:3305942] server session: stateChange:1->2 1452294555291.1155
,2016-01-09 00:09:19.235 ThaliTest[1603:3305942] client session: connected
2016-01-09 00:09:19.235 ThaliTest[1603:3305942] client session: stateChange:1->2 1452294555291.1155.+whsTw==
,2016-01-09 00:09:19.253 ThaliTest[1603:3305203] server relay: connected (to port: 5001)
,2016-01-09 00:09:19.294 ThaliTest[1603:3305942] client session: fireConnectCallback: 1452294555291.1155.+whsTw==
2016-01-09 00:09:19.294 ThaliTest[1603:3305942] jxcore: connect: success
,ok 89 Should be able to connect without error
,ok 90 Port should be within range
,ok 91 First connect should succeed
,2016-01-09 00:09:19.359 ThaliTest[1603:3305203] client: relay established
2016-01-09 00:09:19.359 ThaliTest[1603:3305203] client: new accepted socket: 0x187aa050
,ok 92 the test messages should be equal
,ok 93 First send should succeed
,2016-01-09 00:09:19.454 ThaliTest[1603:3305203] client: socket closed
2016-01-09 00:09:19.455 ThaliTest[1603:3305203] client relay: socket disconnected
2016-01-09 00:09:19.455 ThaliTest[1603:3305203] client relay: 0x187aa050 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-09 00:09:19.455 ThaliTest[1603:3305203] client session: socket closed: 1452294555291.1155.+whsTw==
2016-01-09 ,00:09:19.455 ThaliTest[1603:3305203] client session: onLinkFailure: 1452294555291.1155.+whsTw==
2016-01-09 00:09:19.456 ThaliTest[1603:3305203] client session: disconnect
2016-01-09 00:09:19.456 ThaliTest[1603:3305203] client session: stateChange:2->0 14,52294555291.1155.+whsTw==
,2016-01-09 00:09:19.469 ThaliTest[1603:3305203] client session: fireConnectionErrorEvent: 1452294555291.1155.+whsTw==
,2016-01-09 00:09:19.475 ThaliTest[1603:3305414] jxcore: connect 1452294555291.1155.+whsTw==
2016-01-09 00:09:19.476 ThaliTest[1603:3305414] client session: connect
2016-01-09 00:09:19.477 ThaliTest[1603:3305414] client session: stateChange:0->1 1452294555291.1155.+whsTw==
,2016-01-09 00:09:19.512 ThaliTest[1603:3305950] server session: not connected 1452294555291.1155
,2016-01-09 00:09:19.609 ThaliTest[1603:3305203] multipeer session: reset timer
2016-01-09 00:09:19.609 ThaliTest[1603:3305203] multipeer session: stop timer
2016-01-09 00:09:19.610 ThaliTest[1603:3305203] multipeer session: start timer: 0x185124c0
2016-,01-09 00:09:19.610 ThaliTest[1603:3305203] server: disconnecting to refresh session (1452294555291.1155)
2016-01-09 00:09:19.610 ThaliTest[1603:3305203] server session: disconnect
2016-01-09 00:09:19.610 ThaliTest[1603:3305203] server session: stateChang,e:2->0 1452294555291.1155
,2016-01-09 00:09:19.615 ThaliTest[1603:3305203] server session: connect
,2016-01-09 00:09:19.616 ThaliTest[1603:3305203] server session: stateChange:0->1 1452294555291.1155
,2016-01-09 00:09:19.629 ThaliTest[1603:3305203] server: accepting invitation 1452294555291.1155
,2016-01-09 00:09:22.241 ThaliTest[1603:3305919] client session: connected
2016-01-09 00:09:22.242 ThaliTest[1603:3305919] client session: stateChange:1->2 1452294555291.1155.+whsTw==
,2016-01-09 00:09:22.262 ThaliTest[1603:3305942] server session: connected
,2016-01-09 00:09:22.262 ThaliTest[1603:3305942] server session: stateChange:1->2 1452294555291.1155
,2016-01-09 00:09:22.266 ThaliTest[1603:3305916] client session: fireConnectCallback: 1452294555291.1155.+whsTw==
,2016-01-09 00:09:22.269 ThaliTest[1603:3305916] jxcore: connect: success
,ok 94 Should be able to connect without error
,ok 95 Port should be within range
ok 96 Second connect should succeed
,2016-01-09 00:09:22.291 ThaliTest[1603:3305203] server relay: connected (to port: 5001)
,2016-01-09 00:09:22.316 ThaliTest[1603:3305203] client: relay established
2016-01-09 00:09:22.316 ThaliTest[1603:3305203] client: new accepted socket: 0x18598280
,ok 97 the test messages should be equal
,ok 98 Second send should succeed
,# setup
,2016-01-09 00:09:22.385 ThaliTest[1603:3305203] client: socket closed
,2016-01-09 00:09:22.385 ThaliTest[1603:3305203] client relay: socket disconnected
,2016-01-09 00:09:22.386 ThaliTest[1603:3305203] client relay: 0x18598280 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-09 00:09:,22.386 ThaliTest[1603:3305203] client session: socket closed: 1452294555291.1155.+whsTw==
,2016-01-09 00:09:22.386 ThaliTest[1603:3305203] client session: onLinkFailure: 1452294555291.1155.+whsTw==
2016-01-09 00:09:22.387 ThaliTest[1603:3305203] client session: disconnect
2016-01-09 00:09:22.387 ThaliTest[1603:3305203] client session: stateCha,nge:2->0 1452294555291.1155.+whsTw==
,2016-01-09 00:09:22.413 ThaliTest[1603:3305203] client session: fireConnectionErrorEvent: 1452294555291.1155.+whsTw==
,2016-01-09 00:09:22.427 ThaliTest[1603:3305950] server session: not connected 1452294555291.1155
,calling stopBroadcasting
,2016-01-09 00:09:23.139 ThaliTest[1603:3305414] jxcore: stopBroadcasting
2016-01-09 00:09:23.139 ThaliTest[1603:3305414] THEMultipeerSession stopping peer
2016-01-09 00:09:23.140 ThaliTest[1603:3305414] multipeer session: stop timer
2016-01-09 00:09:23.,140 ThaliTest[1603:3305414] server session: disconnect
2016-01-09 00:09:23.140 ThaliTest[1603:3305414] server session: stateChange:2->0 1452294555291.1155
2016-01-09 00:09:23.146 ThaliTest[1603:3305414] jxcore: stopBroadcasting: success
,stopBroadcasting returned undefined
,# ThaliReplicationManager can call start without error
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/C0470A19-A292-4FAD-BE7C-4891FF17C72C/tmp/pouchdb"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,ok 99 starting event should occur in right order
,2016-01-09 00:09:24.662 ThaliTest[1603:3305414] jxcore: startBroadcasting
,2016-01-09 00:09:24.664 ThaliTest[1603:3305414] server: starting pz-Bfh1knE1aW2mJeqnuxg.L6wb8w==
2016-01-09 00:09:24.664 ThaliTest[1603:3305414] multipeer session: start timer: 0x187a6b20
2016-01-09 00:09:24.664 ThaliTest[1603:3305414] THEMultipeerSessio,n initialized peer pz-Bfh1knE1aW2mJeqnuxg
2016-01-09 00:09:24.665 ThaliTest[1603:3305414] jxcore: startBroadcasting: success
ok 100 started event should occur in right order
Now in TRM stop
State of this._isStarted: true
ok 101 stopping event should occur in right order
About to call stopBroadcasting
,2016-01-09 00:09:24.666 ThaliTest[1603:3305414] jxcore: stopBroadcasting
,2016-01-09 00:09:24.667 ThaliTest[1603:3305414] THEMultipeerSession stopping peer
2016-01-09 00:09:24.667 ThaliTest[1603:3305414] multipeer session: stop timer
2016-01-09 00:09:24.667 ThaliTest[1603:3305414] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined
ok 102 stopped event should occur in right order
,mux server bridge listener closed
# setup
,# ThaliReplicationManager receives identity
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/C0470A19-A292-4FAD-BE7C-4891FF17C72C/tmp/pouchdb"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,2016-01-09 00:09:26.241 ThaliTest[1603:3305414] jxcore: startBroadcasting
,2016-01-09 00:09:26.245 ThaliTest[1603:3305414] server: starting pz-Bfh1knE1aW2mJeqnuxg.TDRt3g==
2016-01-09 00:09:26.246 ThaliTest[1603:3305414] multipeer session: start timer: 0x1831f220
2016-01-09 00:09:26.246 ThaliTest[1603:3305414] THEMultipeerSessio,n initialized peer pz-Bfh1knE1aW2mJeqnuxg
2016-01-09 00:09:26.247 ThaliTest[1603:3305414] jxcore: startBroadcasting: success
,ok 103 getDeviceIdentity should not return an error
,ok 104 deviceName should not be null
Now in TRM stop
,State of this._isStarted: true
,About to call stopBroadcasting
,2016-01-09 00:09:26.253 ThaliTest[1603:3305414] jxcore: stopBroadcasting
2016-01-09 00:09:26.255 ThaliTest[1603:3305414] THEMultipeerSession stopping peer
2016-01-09 00:09:26.255 ThaliTest[1603:3305414] multipeer session: stop timer
2016-01-09 00:09:26.,255 ThaliTest[1603:3305414] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined
mux server bridge listener closed
,Tests Complete
,Total: 0	Passed: 0	Failed: 0
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
