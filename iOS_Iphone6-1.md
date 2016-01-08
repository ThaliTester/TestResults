#### Test 549702618c0ebdb_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/549702618c0ebdb/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/ED0B5142-2407-483B-817D-726B449EC931/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/ED0B5142-2407-483B-817D-726B449EC931/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/549702618c0ebdb/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/549702618c0ebdb/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/7D0B94B0-3C5D-4756-8603-9878586CA992/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50410"
,(lldb)     command script import "/tmp/ED0B5142-2407-483B-817D-726B449EC931/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-01-08 16:30:45.490 ThaliTest[1520:3248089] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/FB87CA5A-ABA9-4EF6-8133-4A57AF072D49/Library/Cookies/Cookies.binarycookies
,2016-01-08 16:30:45.904 ThaliTest[1520:3248089] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-08 16:30:45.905 ThaliTest[1520:3248089] Multi-tasking -> Device: YES, App: YES
,2016-01-08 16:30:45.916 ThaliTest[1520:3248089] Unlimited access to network resources
,2016-01-08 16:30:45.929 ThaliTest[1520:3248089] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-08 16:30:54.363 ThaliTest[1520:3248089] Resetting plugins due to page load.
,2016-01-08 16:30:57.556 ThaliTest[1520:3248089] Finished load of: file:///var/mobile/Containers/Bundle/Application/7D0B94B0-3C5D-4756-8603-9878586CA992/ThaliTest.app/www/index.html
,2016-01-08 16:30:57.737 ThaliTest[1520:3248089] JXcore Cordova plugin initializing
2016-01-08 16:30:57.738 ThaliTest[1520:3248299] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
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
,ok 11 should not throw
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
,2016-01-08 16:35:20.427 ThaliTest[1520:3248299] jxcore: startBroadcasting
,2016-01-08 16:35:20.442 ThaliTest[1520:3248299] server: starting 1452267320426.1520.DT9b1Q==
,2016-01-08 16:35:20.443 ThaliTest[1520:3248299] multipeer session: start timer: 0x1936f1e0
2016-01-08 16:35:20.444 ThaliTest[1520:3248299] THEMultipeerSession initialized peer 1452267320426.1520
,2016-01-08 16:35:20.446 ThaliTest[1520:3248299] jxcore: startBroadcasting: success
,ok 45 Should be able to call startBroadcasting without error
2016-01-08 16:35:20.451 ThaliTest[1520:3248299] jxcore: stopBroadcasting
2016-01-08 16:35:20.451 ThaliTest[1520:3248299] THEMultipeerSession stopping peer
2016-01-08 16:35:20.451 ThaliTest[152,0:3248299] multipeer session: stop timer
,2016-01-08 16:35:20.452 ThaliTest[1520:3248299] jxcore: stopBroadcasting: success
ok 46 Should be able to call stopBroadcasting without error
2016-01-08 16:35:20.455 ThaliTest[1520:3248299] jxcore: startBroadcasting
,2016-01-08 16:35:20.466 ThaliTest[1520:3248299] server: starting 1452267320454.1520.kQjIKA==
2016-01-08 16:35:20.467 ThaliTest[1520:3248299] multipeer session: start timer: 0x19315190
2016-01-08 16:35:20.468 ThaliTest[1520:3248299] THEMultipeerSession in,itialized peer 1452267320454.1520
2016-01-08 16:35:20.468 ThaliTest[1520:3248299] jxcore: startBroadcasting: success
ok 47 Should be able to call startBroadcasting without error
,2016-01-08 16:35:20.471 ThaliTest[1520:3248299] jxcore: stopBroadcasting
2016-01-08 16:35:20.474 ThaliTest[1520:3248299] THEMultipeerSession stopping peer
2016-01-08 16:35:20.475 ThaliTest[1520:3248299] multipeer session: stop timer
2016-01-08 16:35:20.,475 ThaliTest[1520:3248299] jxcore: stopBroadcasting: success
,ok 48 Should be able to call stopBroadcasting without error
,2016-01-08 16:35:20.479 ThaliTest[1520:3248299] jxcore: startBroadcasting
,2016-01-08 16:35:20.484 ThaliTest[1520:3248299] server: starting 1452267320478.1520.yvlU4Q==
2016-01-08 16:35:20.485 ThaliTest[1520:3248299] multipeer session: start timer: 0x196573a0
2016-01-08 16:35:20.485 ThaliTest[1520:3248299] THEMultipeerSession in,itialized peer 1452267320478.1520
2016-01-08 16:35:20.486 ThaliTest[1520:3248299] jxcore: startBroadcasting: success
ok 49 Should be able to call startBroadcasting without error
2016-01-08 16:35:20.488 ThaliTest[1520:3248299] jxcore: stopBroadcasting
2,016-01-08 16:35:20.488 ThaliTest[1520:3248299] THEMultipeerSession stopping peer
2016-01-08 16:35:20.488 ThaliTest[1520:3248299] multipeer session: stop timer
2016-01-08 16:35:20.489 ThaliTest[1520:3248299] jxcore: stopBroadcasting: success
ok 50 Should, be able to call stopBroadcasting without error
2016-01-08 16:35:20.491 ThaliTest[1520:3248299] jxcore: startBroadcasting
2016-01-08 16:35:20.494 ThaliTest[1520:3248299] server: starting 1452267320490.1520.PpBT9g==
2016-01-08 16:35:20.495 ThaliTest[1520,:3248299] multipeer session: start timer: 0x19508660
2016-01-08 16:35:20.500 ThaliTest[1520:3248299] THEMultipeerSession initialized peer 1452267320490.1520
2016-01-08 16:35:20.501 ThaliTest[1520:3248299] jxcore: startBroadcasting: success
ok 51 Should ,be able to call startBroadcasting without error
,2016-01-08 16:35:20.503 ThaliTest[1520:3248299] jxcore: stopBroadcasting
2016-01-08 16:35:20.508 ThaliTest[1520:3248299] THEMultipeerSession stopping peer
2016-01-08 16:35:20.509 ThaliTest[1520:3248299] multipeer session: stop timer
2016-01-08 16:35:20.,509 ThaliTest[1520:3248299] jxcore: stopBroadcasting: success
ok 52 Should be able to call stopBroadcasting without error
2016-01-08 16:35:20.511 ThaliTest[1520:3248299] jxcore: startBroadcasting
,2016-01-08 16:35:20.520 ThaliTest[1520:3248299] server: starting 1452267320511.1520./2KD1Q==
,2016-01-08 16:35:20.528 ThaliTest[1520:3248299] multipeer session: start timer: 0x19659e70
,2016-01-08 16:35:20.534 ThaliTest[1520:3248299] THEMultipeerSession initialized peer 1452267320511.1520
,2016-01-08 16:35:20.541 ThaliTest[1520:3248299] jxcore: startBroadcasting: success
,ok 53 Should be able to call startBroadcasting without error
,2016-01-08 16:35:20.547 ThaliTest[1520:3248299] jxcore: stopBroadcasting
,2016-01-08 16:35:20.549 ThaliTest[1520:3248299] THEMultipeerSession stopping peer
,2016-01-08 16:35:20.550 ThaliTest[1520:3248299] multipeer session: stop timer
,2016-01-08 16:35:20.551 ThaliTest[1520:3248299] jxcore: stopBroadcasting: success
,ok 54 Should be able to call stopBroadcasting without error
,2016-01-08 16:35:20.557 ThaliTest[1520:3248299] jxcore: startBroadcasting
,2016-01-08 16:35:20.560 ThaliTest[1520:3248299] server: starting 1452267320557.1520.100ceQ==
,2016-01-08 16:35:20.562 ThaliTest[1520:3248299] multipeer session: start timer: 0x19656170
,2016-01-08 16:35:20.564 ThaliTest[1520:3248299] THEMultipeerSession initialized peer 1452267320557.1520
,2016-01-08 16:35:20.569 ThaliTest[1520:3248299] jxcore: startBroadcasting: success
,ok 55 Should be able to call startBroadcasting without error
,2016-01-08 16:35:20.571 ThaliTest[1520:3248299] jxcore: stopBroadcasting
,2016-01-08 16:35:20.572 ThaliTest[1520:3248299] THEMultipeerSession stopping peer
,2016-01-08 16:35:20.572 ThaliTest[1520:3248299] multipeer session: stop timer
,2016-01-08 16:35:20.574 ThaliTest[1520:3248299] jxcore: stopBroadcasting: success
,ok 56 Should be able to call stopBroadcasting without error
,2016-01-08 16:35:20.579 ThaliTest[1520:3248299] jxcore: startBroadcasting
,2016-01-08 16:35:20.582 ThaliTest[1520:3248299] server: starting 1452267320578.1520.Hqyxfw==
,2016-01-08 16:35:20.584 ThaliTest[1520:3248299] multipeer session: start timer: 0x1974e890
2016-01-08 16:35:20.586 ThaliTest[1520:3248299] THEMultipeerSession initialized peer 1452267320578.1520
,2016-01-08 16:35:20.587 ThaliTest[1520:3248299] jxcore: startBroadcasting: success
,ok 57 Should be able to call startBroadcasting without error
,2016-01-08 16:35:20.592 ThaliTest[1520:3248299] jxcore: stopBroadcasting
,2016-01-08 16:35:20.593 ThaliTest[1520:3248299] THEMultipeerSession stopping peer
,2016-01-08 16:35:20.594 ThaliTest[1520:3248299] multipeer session: stop timer
,2016-01-08 16:35:20.596 ThaliTest[1520:3248299] jxcore: stopBroadcasting: success
,ok 58 Should be able to call stopBroadcasting without error
,2016-01-08 16:35:20.601 ThaliTest[1520:3248299] jxcore: startBroadcasting
,2016-01-08 16:35:20.603 ThaliTest[1520:3248299] server: starting 1452267320600.1520.yH7JLw==
,2016-01-08 16:35:20.605 ThaliTest[1520:3248299] multipeer session: start timer: 0x196511b0
,2016-01-08 16:35:20.607 ThaliTest[1520:3248299] THEMultipeerSession initialized peer 1452267320600.1520
,2016-01-08 16:35:20.610 ThaliTest[1520:3248299] jxcore: startBroadcasting: success
,ok 59 Should be able to call startBroadcasting without error
,2016-01-08 16:35:20.614 ThaliTest[1520:3248299] jxcore: stopBroadcasting
,2016-01-08 16:35:20.615 ThaliTest[1520:3248299] THEMultipeerSession stopping peer
,2016-01-08 16:35:20.616 ThaliTest[1520:3248299] multipeer session: stop timer
,2016-01-08 16:35:20.618 ThaliTest[1520:3248299] jxcore: stopBroadcasting: success
,ok 60 Should be able to call stopBroadcasting without error
,2016-01-08 16:35:20.622 ThaliTest[1520:3248299] jxcore: startBroadcasting
,2016-01-08 16:35:20.625 ThaliTest[1520:3248299] server: starting 1452267320622.1520.usaLEg==
,2016-01-08 16:35:20.626 ThaliTest[1520:3248299] multipeer session: start timer: 0x193ef9b0
,2016-01-08 16:35:20.628 ThaliTest[1520:3248299] THEMultipeerSession initialized peer 1452267320622.1520
,2016-01-08 16:35:20.631 ThaliTest[1520:3248299] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error
,2016-01-08 16:35:20.633 ThaliTest[1520:3248299] jxcore: stopBroadcasting
,2016-01-08 16:35:20.634 ThaliTest[1520:3248299] THEMultipeerSession stopping peer
,2016-01-08 16:35:20.634 ThaliTest[1520:3248299] multipeer session: stop timer
,2016-01-08 16:35:20.635 ThaliTest[1520:3248299] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error
,2016-01-08 16:35:20.639 ThaliTest[1520:3248299] jxcore: startBroadcasting
,2016-01-08 16:35:20.641 ThaliTest[1520:3248299] server: starting 1452267320639.1520.4mbefw==
,2016-01-08 16:35:20.642 ThaliTest[1520:3248299] multipeer session: start timer: 0x19193ae0
,2016-01-08 16:35:20.644 ThaliTest[1520:3248299] THEMultipeerSession initialized peer 1452267320639.1520
,2016-01-08 16:35:20.645 ThaliTest[1520:3248299] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error
,2016-01-08 16:35:20.649 ThaliTest[1520:3248299] jxcore: stopBroadcasting
,2016-01-08 16:35:20.649 ThaliTest[1520:3248299] THEMultipeerSession stopping peer
,2016-01-08 16:35:20.650 ThaliTest[1520:3248299] multipeer session: stop timer
,2016-01-08 16:35:20.651 ThaliTest[1520:3248299] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter calls startBroadcasting twice with error
,# teardown
,2016-01-08 16:35:20.785 ThaliTest[1520:3248299] jxcore: startBroadcasting
,2016-01-08 16:35:20.789 ThaliTest[1520:3248299] server: starting 1452267320785.1520./YhQ8w==
,2016-01-08 16:35:20.795 ThaliTest[1520:3248299] multipeer session: start timer: 0x194c9700
,2016-01-08 16:35:20.798 ThaliTest[1520:3248299] THEMultipeerSession initialized peer 1452267320785.1520
,2016-01-08 16:35:20.800 ThaliTest[1520:3248299] jxcore: startBroadcasting: success
,ok 65 Should be able to call startBroadcasting without error
,2016-01-08 16:35:20.806 ThaliTest[1520:3248299] jxcore: startBroadcasting
,2016-01-08 16:35:20.807 ThaliTest[1520:3248299] jxcore: startBroadcasting: failure
,ok 66 Cannot call startBroadcasting twice
,2016-01-08 16:35:20.811 ThaliTest[1520:3248299] jxcore: stopBroadcasting
,2016-01-08 16:35:20.813 ThaliTest[1520:3248299] THEMultipeerSession stopping peer
,2016-01-08 16:35:20.815 ThaliTest[1520:3248299] multipeer session: stop timer
,2016-01-08 16:35:20.819 ThaliTest[1520:3248299] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on connection to bad peer
,# teardown
,2016-01-08 16:35:20.907 ThaliTest[1520:3248299] jxcore: startBroadcasting
,2016-01-08 16:35:20.911 ThaliTest[1520:3248299] server: starting 1452267320907.1520.Iiwb3g==
,2016-01-08 16:35:20.920 ThaliTest[1520:3248299] multipeer session: start timer: 0x1964fe60
,2016-01-08 16:35:20.922 ThaliTest[1520:3248299] THEMultipeerSession initialized peer 1452267320907.1520
,2016-01-08 16:35:20.925 ThaliTest[1520:3248299] jxcore: startBroadcasting: success
,ok 68 Should be able to call startBroadcasting without error
,2016-01-08 16:35:20.929 ThaliTest[1520:3248299] jxcore: connect foobar
,2016-01-08 16:35:20.930 ThaliTest[1520:3248299] client: unknown peer foobar
,2016-01-08 16:35:20.932 ThaliTest[1520:3248299] jxcore: connect: fail: Unknown peer
,ok 69 Should not connect to a bad peer
,2016-01-08 16:35:20.936 ThaliTest[1520:3248299] jxcore: stopBroadcasting
,2016-01-08 16:35:20.937 ThaliTest[1520:3248299] THEMultipeerSession stopping peer
,2016-01-08 16:35:20.938 ThaliTest[1520:3248299] multipeer session: stop timer
,2016-01-08 16:35:20.943 ThaliTest[1520:3248299] jxcore: stopBroadcasting: success
,ok 70 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on disconnect to bad peer
,# teardown
,2016-01-08 16:35:21.272 ThaliTest[1520:3248299] jxcore: startBroadcasting
,2016-01-08 16:35:21.275 ThaliTest[1520:3248299] server: starting 1452267321271.1520.NERRkw==
2016-01-08 16:35:21.276 ThaliTest[1520:3248299] multipeer session: start timer: 0x17e146b0
,2016-01-08 16:35:21.278 ThaliTest[1520:3248299] THEMultipeerSession initialized peer 1452267321271.1520
,2016-01-08 16:35:21.287 ThaliTest[1520:3248299] jxcore: startBroadcasting: success
,ok 71 Should be able to call startBroadcasting without error
,2016-01-08 16:35:21.292 ThaliTest[1520:3248299] jxcore: disconnect
,2016-01-08 16:35:21.293 ThaliTest[1520:3248299] jxcore: disconnect: fail
,ok 72 Disconnect should fail to a non-existant peer 
,2016-01-08 16:35:21.298 ThaliTest[1520:3248299] jxcore: stopBroadcasting
,2016-01-08 16:35:21.299 ThaliTest[1520:3248299] THEMultipeerSession stopping peer
,2016-01-08 16:35:21.300 ThaliTest[1520:3248299] multipeer session: stop timer
,2016-01-08 16:35:21.305 ThaliTest[1520:3248299] jxcore: stopBroadcasting: success
,ok 73 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter can discover and connect to peers
,# teardown
,2016-01-08 16:35:21.371 ThaliTest[1520:3248299] jxcore: startBroadcasting
,2016-01-08 16:35:21.376 ThaliTest[1520:3248299] server: starting 1452267321371.1520.T3uJKQ==
,2016-01-08 16:35:21.378 ThaliTest[1520:3248299] multipeer session: start timer: 0x17ec7e90
,2016-01-08 16:35:21.387 ThaliTest[1520:3248299] THEMultipeerSession initialized peer 1452267321371.1520
,2016-01-08 16:35:21.388 ThaliTest[1520:3248299] jxcore: startBroadcasting: success
,ok 74 Should be able to call startBroadcasting without error
,2016-01-08 16:35:22.207 ThaliTest[1520:3248089] client: found peer: 1452267321384.1098.R8al9Q==
2016-01-08 16:35:22.210 ThaliTest[1520:3248299] jxcore: connect 1452267321384.1098.R8al9Q==
2016-01-08 16:35:22.210 ThaliTest[1520:3248299] client session: co,nnect
2016-01-08 16:35:22.210 ThaliTest[1520:3248299] client session: stateChange:0->1 1452267321384.1098.R8al9Q==
,2016-01-08 16:35:22.729 ThaliTest[1520:3248089] multipeer session: reset timer
2016-01-08 16:35:22.729 ThaliTest[1520:3248089] multipeer session: stop timer
2016-01-08 16:35:22.730 ThaliTest[1520:3248089] multipeer session: start timer: 0x17ec7e90
2016-,01-08 16:35:22.730 ThaliTest[1520:3248089] server session: connect
2016-01-08 16:35:22.730 ThaliTest[1520:3248089] server session: stateChange:0->1 1452267321384.1098
,2016-01-08 16:35:22.740 ThaliTest[1520:3248089] server: accepting invitation 1452267321384.1098
,2016-01-08 16:35:25.360 ThaliTest[1520:3248734] client session: connected
2016-01-08 16:35:25.364 ThaliTest[1520:3248734] client session: stateChange:1->2 1452267321384.1098.R8al9Q==
,2016-01-08 16:35:25.374 ThaliTest[1520:3248734] client session: fireConnectCallback: 1452267321384.1098.R8al9Q==
,2016-01-08 16:35:25.375 ThaliTest[1520:3248734] jxcore: connect: success
,ok 75 Should be able to connect without error
,ok 76 Port should be within range
,2016-01-08 16:35:25.380 ThaliTest[1520:3248299] jxcore: disconnect
,2016-01-08 16:35:25.381 ThaliTest[1520:3248299] client session: disconnectFromPeer: 1452267321384.1098.R8al9Q==
,2016-01-08 16:35:25.381 ThaliTest[1520:3248299] client session: disconnect
,2016-01-08 16:35:25.382 ThaliTest[1520:3248299] client session: stateChange:2->0 1452267321384.1098.R8al9Q==
,2016-01-08 16:35:25.429 ThaliTest[1520:3248728] server session: connected
,2016-01-08 16:35:25.430 ThaliTest[1520:3248728] server session: stateChange:1->2 1452267321384.1098
,2016-01-08 16:35:25.437 ThaliTest[1520:3248089] server relay: socket disconnected
2016-01-08 16:35:25.438 ThaliTest[1520:3248089] server relay: 0x196450f0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLoc,alizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-08 16:35:25.456 ThaliTest[1520:3248299] jxcore: disconnect: success
,ok 77 Should be able to disconnect without error
,setting stopBroadcasting callback and ending test.
,# setup
,2016-01-08 16:35:26.791 ThaliTest[1520:3248743] server session: not connected 1452267321384.1098
,calling stopBroadcasting
,2016-01-08 16:35:27.658 ThaliTest[1520:3248299] jxcore: stopBroadcasting
2016-01-08 16:35:27.659 ThaliTest[1520:3248299] THEMultipeerSession stopping peer
2016-01-08 16:35:27.659 ThaliTest[1520:3248299] multipeer session: stop timer
2016-01-08 16:35:27.,659 ThaliTest[1520:3248299] server session: disconnect
2016-01-08 16:35:27.660 ThaliTest[1520:3248299] server session: stateChange:2->0 1452267321384.1098
,2016-01-08 16:35:27.663 ThaliTest[1520:3248299] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliEmitter can discover and connect to peers and then fail on double connect
,# teardown
,2016-01-08 16:35:27.752 ThaliTest[1520:3248299] jxcore: startBroadcasting
,2016-01-08 16:35:27.757 ThaliTest[1520:3248299] server: starting 1452267327752.1520.DA77og==
,2016-01-08 16:35:27.760 ThaliTest[1520:3248299] multipeer session: start timer: 0x19573150
,2016-01-08 16:35:27.769 ThaliTest[1520:3248299] THEMultipeerSession initialized peer 1452267327752.1520
,2016-01-08 16:35:27.771 ThaliTest[1520:3248299] jxcore: startBroadcasting: success
,ok 78 Should be able to call startBroadcasting without error
,2016-01-08 16:35:28.392 ThaliTest[1520:3248089] client: found peer: 1452267321371.1520.T3uJKQ==
,2016-01-08 16:35:28.394 ThaliTest[1520:3248299] jxcore: connect 1452267321371.1520.T3uJKQ==
,2016-01-08 16:35:28.394 ThaliTest[1520:3248299] client session: connect
2016-01-08 16:35:28.395 ThaliTest[1520:3248299] client session: stateChange:0->1 1452267321371.1520.T3uJKQ==
,2016-01-08 16:35:28.928 ThaliTest[1520:3248089] client: lost peer: 1452267321371.1520.T3uJKQ==
2016-01-08 16:35:28.928 ThaliTest[1520:3248089] client session: onPeerLost: 1452267321371.1520.T3uJKQ==
2016-01-08 16:35:28.928 ThaliTest[1520:3248089] client ,session: onLinkFailure: 1452267321371.1520.T3uJKQ==
2016-01-08 16:35:28.929 ThaliTest[1520:3248089] client session: disconnect
2016-01-08 16:35:28.929 ThaliTest[1520:3248089] client session: stateChange:1->0 1452267321371.1520.T3uJKQ==
2016-01-08 16:35:,28.929 ThaliTest[1520:3248089] client session: fireConnectCallback: 1452267321371.1520.T3uJKQ==
2016-01-08 16:35:28.930 ThaliTest[1520:3248089] jxcore: connect: fail: Peer disconnected
,2016-01-08 16:35:29.352 ThaliTest[1520:3248089] client: found peer: 1452267328127.1098.dyzcWg==
2016-01-08 16:35:29.353 ThaliTest[1520:3248299] jxcore: connect 1452267328127.1098.dyzcWg==
,2016-01-08 16:35:29.353 ThaliTest[1520:3248299] client session: connect
2016-01-08 16:35:29.355 ThaliTest[1520:3248299] client session: stateChange:0->1 1452267328127.1098.dyzcWg==
,2016-01-08 16:35:29.537 ThaliTest[1520:3248089] multipeer session: reset timer
2016-01-08 16:35:29.537 ThaliTest[1520:3248089] multipeer session: stop timer
2016-01-08 16:35:29.537 ThaliTest[1520:3248089] multipeer session: start timer: 0x19573150
2016-,01-08 16:35:29.538 ThaliTest[1520:3248089] server session: connect
2016-01-08 16:35:29.538 ThaliTest[1520:3248089] server session: stateChange:0->1 1452267328127.1098
,2016-01-08 16:35:29.547 ThaliTest[1520:3248089] server: accepting invitation 1452267328127.1098
,2016-01-08 16:35:29.937 ThaliTest[1520:3248299] jxcore: connect 1452267321371.1520.T3uJKQ==
2016-01-08 16:35:29.938 ThaliTest[1520:3248299] client: connect: unreachable 1452267321371.1520.T3uJKQ==
2016-01-08 16:35:29.938 ThaliTest[1520:3248299] jxcore: connect: fail: Peer unreachable
,2016-01-08 16:35:32.130 ThaliTest[1520:3248728] client session: connected
,2016-01-08 16:35:32.130 ThaliTest[1520:3248728] client session: stateChange:1->2 1452267328127.1098.dyzcWg==
,2016-01-08 16:35:32.135 ThaliTest[1520:3248728] client session: fireConnectCallback: 1452267328127.1098.dyzcWg==
2016-01-08 16:35:32.136 ThaliTest[1520:3248728] jxcore: connect: success
,ok 79 Should be able to connect without error
,ok 80 Port should be within range
,2016-01-08 16:35:32.140 ThaliTest[1520:3248299] jxcore: connect 1452267328127.1098.dyzcWg==
,2016-01-08 16:35:32.141 ThaliTest[1520:3248299] client: already connect(ing/ed) to 1452267328127.1098.dyzcWg==
,2016-01-08 16:35:32.141 ThaliTest[1520:3248299] jxcore: connect: fail: Aleady connecting
,ok 81 Should fail on double connect
,2016-01-08 16:35:32.145 ThaliTest[1520:3248299] jxcore: disconnect
,2016-01-08 16:35:32.147 ThaliTest[1520:3248299] client session: disconnectFromPeer: 1452267328127.1098.dyzcWg==
,2016-01-08 16:35:32.147 ThaliTest[1520:3248299] client session: disconnect
,2016-01-08 16:35:32.148 ThaliTest[1520:3248299] client session: stateChange:2->0 1452267328127.1098.dyzcWg==
,2016-01-08 16:35:32.236 ThaliTest[1520:3248728] server session: connected
,2016-01-08 16:35:32.238 ThaliTest[1520:3248728] server session: stateChange:1->2 1452267328127.1098
,2016-01-08 16:35:32.245 ThaliTest[1520:3248089] server relay: socket disconnected
,2016-01-08 16:35:32.246 ThaliTest[1520:3248299] jxcore: disconnect: success
,2016-01-08 16:35:32.246 ThaliTest[1520:3248089] server relay: 0x17e02db0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection ,refused} 
ok 82 Should be able to disconnect without error
,setting stopBroadcasting callback and ending test.
,# setup
,2016-01-08 16:35:32.558 ThaliTest[1520:3248728] server session: not connected 1452267328127.1098
,calling stopBroadcasting
,2016-01-08 16:35:33.402 ThaliTest[1520:3248299] jxcore: stopBroadcasting
2016-01-08 16:35:33.403 ThaliTest[1520:3248299] THEMultipeerSession stopping peer
2016-01-08 16:35:33.403 ThaliTest[1520:3248299] multipeer session: stop timer
2016-01-08 16:35:33.,404 ThaliTest[1520:3248299] server session: disconnect
2016-01-08 16:35:33.404 ThaliTest[1520:3248299] server session: stateChange:2->0 1452267328127.1098
2016-01-08 16:35:33.405 ThaliTest[1520:3248299] jxcore: stopBroadcasting: success
stopBroadcasting, returned undefined
,# ThaliEmitter can discover and connect to peers and then fail on double disconnect
,# teardown
,2016-01-08 16:35:34.464 ThaliTest[1520:3248299] jxcore: startBroadcasting
,2016-01-08 16:35:34.467 ThaliTest[1520:3248299] server: starting 1452267334463.1520.FQc8/A==
2016-01-08 16:35:34.469 ThaliTest[1520:3248299] multipeer session: start timer: 0x19774dd0
2016-01-08 16:35:34.470 ThaliTest[1520:3248299] THEMultipeerSession in,itialized peer 1452267334463.1520
2016-01-08 16:35:34.470 ThaliTest[1520:3248299] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error
,2016-01-08 16:35:35.740 ThaliTest[1520:3248089] client: found peer: 1452267334583.1098.EBDrlg==
2016-01-08 16:35:35.742 ThaliTest[1520:3248299] jxcore: connect 1452267334583.1098.EBDrlg==
2016-01-08 16:35:35.743 ThaliTest[1520:3248299] client session: co,nnect
2016-01-08 16:35:35.743 ThaliTest[1520:3248299] client session: stateChange:0->1 1452267334583.1098.EBDrlg==
,2016-01-08 16:35:36.169 ThaliTest[1520:3248089] multipeer session: reset timer
2016-01-08 16:35:36.170 ThaliTest[1520:3248089] multipeer session: stop timer
2016-01-08 16:35:36.170 ThaliTest[1520:3248089] multipeer session: start timer: 0x19774dd0
2016-,01-08 16:35:36.170 ThaliTest[1520:3248089] server session: connect
2016-01-08 16:35:36.171 ThaliTest[1520:3248089] server session: stateChange:0->1 1452267334583.1098
,2016-01-08 16:35:36.182 ThaliTest[1520:3248089] server: accepting invitation 1452267334583.1098
,2016-01-08 16:35:38.855 ThaliTest[1520:3248733] server session: connected
2016-01-08 16:35:38.855 ThaliTest[1520:3248733] server session: stateChange:1->2 1452267334583.1098
,2016-01-08 16:35:38.881 ThaliTest[1520:3248089] server relay: socket disconnected
2016-01-08 16:35:38.881 ThaliTest[1520:3248089] server relay: 0x17e042d0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLoc,alizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-08 16:35:38.916 ThaliTest[1520:3248734] server session: not connected 1452267334583.1098
,2016-01-08 16:35:39.307 ThaliTest[1520:3248734] client session: connected
2016-01-08 16:35:39.307 ThaliTest[1520:3248734] client session: stateChange:1->2 1452267334583.1098.EBDrlg==
,2016-01-08 16:35:39.339 ThaliTest[1520:3248733] client session: fireConnectCallback: 1452267334583.1098.EBDrlg==
2016-01-08 16:35:39.339 ThaliTest[1520:3248733] jxcore: connect: success
,ok 84 Should be able to connect without error
,ok 85 Port should be within range
,2016-01-08 16:35:39.344 ThaliTest[1520:3248299] jxcore: disconnect
2016-01-08 16:35:39.345 ThaliTest[1520:3248299] client session: disconnectFromPeer: 1452267334583.1098.EBDrlg==
2016-01-08 16:35:39.345 ThaliTest[1520:3248299] client session: disconnect,
2016-01-08 16:35:39.345 ThaliTest[1520:3248299] client session: stateChange:2->0 1452267334583.1098.EBDrlg==
,2016-01-08 16:35:39.357 ThaliTest[1520:3248299] jxcore: disconnect: success
ok 86 Should be able to disconnect without error
2016-01-08 16:35:39.361 ThaliTest[1520:3248299] jxcore: disconnect
2016-01-08 16:35:39.362 ThaliTest[1520:3248299] jxcore: disco,nnect: fail
ok 87 Disconnect should fail 
setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
,2016-01-08 16:35:39.701 ThaliTest[1520:3248299] jxcore: stopBroadcasting
2016-01-08 16:35:39.701 ThaliTest[1520:3248299] THEMultipeerSession stopping peer
2016-01-08 16:35:39.701 ThaliTest[1520:3248299] multipeer session: stop timer
2016-01-08 16:35:39.,702 ThaliTest[1520:3248299] server session: disconnect
2016-01-08 16:35:39.702 ThaliTest[1520:3248299] server session: stateChange:2->0 1452267334583.1098
2016-01-08 16:35:39.703 ThaliTest[1520:3248299] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter handles socket disconnect correctly
,# teardown
,2016-01-08 16:35:40.224 ThaliTest[1520:3248299] jxcore: startBroadcasting
,2016-01-08 16:35:40.228 ThaliTest[1520:3248299] server: starting 1452267340224.1520.QS302Q==
2016-01-08 16:35:40.228 ThaliTest[1520:3248299] multipeer session: start timer: 0x1963f670
2016-01-08 16:35:40.229 ThaliTest[1520:3248299] THEMultipeerSession in,itialized peer 1452267340224.1520
2016-01-08 16:35:40.229 ThaliTest[1520:3248299] jxcore: startBroadcasting: success
ok 88 Should be able to call startBroadcasting without error
echo server started
,2016-01-08 16:35:41.452 ThaliTest[1520:3248089] client: found peer: 1452267340250.1098.gxXw7Q==
[{"peerIdentifier":"1452267340250.1098.gxXw7Q==","peerName":"(null)","peerAvailable":true}]
2016-01-08 16:35:41.455 ThaliTest[1520:3248299] jxcore: connect 14,52267340250.1098.gxXw7Q==
,2016-01-08 16:35:41.456 ThaliTest[1520:3248299] client session: connect
2016-01-08 16:35:41.456 ThaliTest[1520:3248299] client session: stateChange:0->1 1452267340250.1098.gxXw7Q==
,2016-01-08 16:35:41.547 ThaliTest[1520:3248089] multipeer session: reset timer
2016-01-08 16:35:41.547 ThaliTest[1520:3248089] multipeer session: stop timer
,2016-01-08 16:35:41.547 ThaliTest[1520:3248089] multipeer session: start timer: 0x1963f670
2016-01-08 16:35:41.548 ThaliTest[1520:3248089] server session: connect
2016-01-08 16:35:41.548 ThaliTest[1520:3248089] server session: stateChange:0->1 1452267340,250.1098
,2016-01-08 16:35:41.557 ThaliTest[1520:3248089] server: accepting invitation 1452267340250.1098
,2016-01-08 16:35:44.255 ThaliTest[1520:3248743] server session: connected
2016-01-08 16:35:44.255 ThaliTest[1520:3248743] server session: stateChange:1->2 1452267340250.1098
,2016-01-08 16:35:44.262 ThaliTest[1520:3248089] server relay: connected (to port: 5001)
,2016-01-08 16:35:44.431 ThaliTest[1520:3248744] server session: not connected 1452267340250.1098
,2016-01-08 16:35:44.483 ThaliTest[1520:3248733] client session: connected
,2016-01-08 16:35:44.484 ThaliTest[1520:3248733] client session: stateChange:1->2 1452267340250.1098.gxXw7Q==
,2016-01-08 16:35:44.493 ThaliTest[1520:3248733] client session: fireConnectCallback: 1452267340250.1098.gxXw7Q==
,2016-01-08 16:35:44.494 ThaliTest[1520:3248733] jxcore: connect: success
,ok 89 Should be able to connect without error
,ok 90 Port should be within range
,ok 91 First connect should succeed
,2016-01-08 16:35:44.557 ThaliTest[1520:3248089] client: relay established
,2016-01-08 16:35:44.558 ThaliTest[1520:3248089] client: new accepted socket: 0x193231b0
,ok 92 the test messages should be equal
,ok 93 First send should succeed
,2016-01-08 16:35:44.630 ThaliTest[1520:3248089] client: socket closed
2016-01-08 16:35:44.631 ThaliTest[1520:3248089] client relay: socket disconnected
2016-01-08 16:35:44.631 ThaliTest[1520:3248089] client relay: 0x193231b0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-08 16:35:44.631 ThaliTest[1520:3248089] client session: socket closed: 1452267340250.1098.gxXw7Q==
2016-01-08 ,16:35:44.632 ThaliTest[1520:3248089] client session: onLinkFailure: 1452267340250.1098.gxXw7Q==
2016-01-08 16:35:44.632 ThaliTest[1520:3248089] client session: disconnect
2016-01-08 16:35:44.632 ThaliTest[1520:3248089] client session: stateChange:2->0 14,52267340250.1098.gxXw7Q==
,2016-01-08 16:35:44.646 ThaliTest[1520:3248089] client session: fireConnectionErrorEvent: 1452267340250.1098.gxXw7Q==
,2016-01-08 16:35:44.650 ThaliTest[1520:3248299] jxcore: connect 1452267340250.1098.gxXw7Q==
,2016-01-08 16:35:44.662 ThaliTest[1520:3248299] client session: connect
,2016-01-08 16:35:44.663 ThaliTest[1520:3248299] client session: stateChange:0->1 1452267340250.1098.gxXw7Q==
,2016-01-08 16:35:44.685 ThaliTest[1520:3248089] multipeer session: reset timer
2016-01-08 16:35:44.685 ThaliTest[1520:3248089] multipeer session: stop timer
2016-01-08 16:35:44.686 ThaliTest[1520:3248089] multipeer session: start timer: 0x1963f670
2016-,01-08 16:35:44.686 ThaliTest[1520:3248089] server: disconnecting to refresh session (1452267340250.1098)
2016-01-08 16:35:44.686 ThaliTest[1520:3248089] server session: disconnect
2016-01-08 16:35:44.686 ThaliTest[1520:3248089] server session: stateChang,e:2->0 1452267340250.1098
,2016-01-08 16:35:44.693 ThaliTest[1520:3248089] server session: connect
2016-01-08 16:35:44.694 ThaliTest[1520:3248089] server session: stateChange:0->1 1452267340250.1098
,2016-01-08 16:35:44.716 ThaliTest[1520:3248089] server: accepting invitation 1452267340250.1098
,2016-01-08 16:35:47.427 ThaliTest[1520:3248744] server session: connected
2016-01-08 16:35:47.428 ThaliTest[1520:3248744] server session: stateChange:1->2 1452267340250.1098
,2016-01-08 16:35:47.442 ThaliTest[1520:3248089] server relay: connected (to port: 5001)
,2016-01-08 16:35:47.505 ThaliTest[1520:3248733] client session: connected
,2016-01-08 16:35:47.505 ThaliTest[1520:3248733] client session: stateChange:1->2 1452267340250.1098.gxXw7Q==
,2016-01-08 16:35:47.511 ThaliTest[1520:3248733] client session: fireConnectCallback: 1452267340250.1098.gxXw7Q==
,2016-01-08 16:35:47.511 ThaliTest[1520:3248733] jxcore: connect: success
,ok 94 Should be able to connect without error
,ok 95 Port should be within range
,ok 96 Second connect should succeed
,2016-01-08 16:35:47.548 ThaliTest[1520:3248089] client: relay established
2016-01-08 16:35:47.549 ThaliTest[1520:3248089] client: new accepted socket: 0x1940f540
,2016-01-08 16:35:47.626 ThaliTest[1520:3248744] server session: not connected 1452267340250.1098
,ok 97 the test messages should be equal
,ok 98 Second send should succeed
,# setup
,2016-01-08 16:35:47.659 ThaliTest[1520:3248089] client: socket closed
,2016-01-08 16:35:47.660 ThaliTest[1520:3248089] client relay: socket disconnected
,2016-01-08 16:35:47.660 ThaliTest[1520:3248089] client relay: 0x1940f540 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-08 16:35:,47.660 ThaliTest[1520:3248089] client session: socket closed: 1452267340250.1098.gxXw7Q==
,2016-01-08 16:35:47.661 ThaliTest[1520:3248089] client session: onLinkFailure: 1452267340250.1098.gxXw7Q==
2016-01-08 16:35:47.661 ThaliTest[1520:3248089] client session: disconnect
2016-01-08 16:35:47.661 ThaliTest[1520:3248089] client session: stateCha,nge:2->0 1452267340250.1098.gxXw7Q==
,calling stopBroadcasting
,2016-01-08 16:35:47.680 ThaliTest[1520:3248299] jxcore: stopBroadcasting
,2016-01-08 16:35:47.682 ThaliTest[1520:3248299] THEMultipeerSession stopping peer
,2016-01-08 16:35:47.683 ThaliTest[1520:3248299] multipeer session: stop timer
,2016-01-08 16:35:47.687 ThaliTest[1520:3248299] server session: disconnect
,2016-01-08 16:35:47.697 ThaliTest[1520:3248299] server session: stateChange:2->0 1452267340250.1098
,2016-01-08 16:35:47.770 ThaliTest[1520:3248089] client session: fireConnectionErrorEvent: 1452267340250.1098.gxXw7Q==
,2016-01-08 16:35:47.816 ThaliTest[1520:3248299] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliReplicationManager can call start without error
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/FB87CA5A-ABA9-4EF6-8133-4A57AF072D49/tmp/pouchdb"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,",failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,ok 99 starting event should occur in right order
,2016-01-08 16:35:49.271 ThaliTest[1520:3248299] jxcore: startBroadcasting
,2016-01-08 16:35:49.273 ThaliTest[1520:3248299] server: starting arHOyJhd_x30DwouAFXvBg.PuST5A==
2016-01-08 16:35:49.273 ThaliTest[1520:3248299] multipeer session: start timer: 0x17e29070
2016-01-08 16:35:49.273 ThaliTest[1520:3248299] THEMultipeerSessio,n initialized peer arHOyJhd_x30DwouAFXvBg
2016-01-08 16:35:49.273 ThaliTest[1520:3248299] jxcore: startBroadcasting: success
ok 100 started event should occur in right order
Now in TRM stop
State of this._isStarted: true
ok 101 stopping event should occur in right order
,About to call stopBroadcasting
2016-01-08 16:35:49.275 ThaliTest[1520:3248299] jxcore: stopBroadcasting
2016-01-08 16:35:49.276 ThaliTest[1520:3248299] THEMultipeerSession stopping peer
2016-01-08 16:35:49.276 ThaliTest[1520:3248299] multipeer session: ,stop timer
2016-01-08 16:35:49.276 ThaliTest[1520:3248299] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined
ok 102 stopped event should occur in right order
,mux server bridge listener closed
# setup
,# ThaliReplicationManager receives identity
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/FB87CA5A-ABA9-4EF6-8133-4A57AF072D49/tmp/pouchdb"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,",failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,2016-01-08 16:35:50.320 ThaliTest[1520:3248299] jxcore: startBroadcasting
,2016-01-08 16:35:50.324 ThaliTest[1520:3248299] server: starting arHOyJhd_x30DwouAFXvBg.hzWjeQ==
2016-01-08 16:35:50.325 ThaliTest[1520:3248299] multipeer session: start timer: 0x19177b60
2016-01-08 16:35:50.325 ThaliTest[1520:3248299] THEMultipeerSessio,n initialized peer arHOyJhd_x30DwouAFXvBg
2016-01-08 16:35:50.326 ThaliTest[1520:3248299] jxcore: startBroadcasting: success
ok 103 getDeviceIdentity should not return an error
,ok 104 deviceName should not be null
,Now in TRM stop
,State of this._isStarted: true
,About to call stopBroadcasting
,2016-01-08 16:35:50.342 ThaliTest[1520:3248299] jxcore: stopBroadcasting
,2016-01-08 16:35:50.343 ThaliTest[1520:3248299] THEMultipeerSession stopping peer
,2016-01-08 16:35:50.345 ThaliTest[1520:3248299] multipeer session: stop timer
,2016-01-08 16:35:50.351 ThaliTest[1520:3248299] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined
,mux server bridge listener closed
,Tests Complete
,Total: 0	Passed: 0	Failed: 0
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
