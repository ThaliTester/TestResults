#### Test 54970261fc259e9_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/54970261fc259e9/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/A54C2A21-A7B2-489B-8FC6-CB3D4EBE7097/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/A54C2A21-A7B2-489B-8FC6-CB3D4EBE7097/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/54970261fc259e9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/54970261fc259e9/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/199115A7-AD5A-4435-8446-116EE097DA77/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:65178"
,(lldb)     command script import "/tmp/A54C2A21-A7B2-489B-8FC6-CB3D4EBE7097/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-05 17:24:36.142 ThaliTest[1323:2824053] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F959200D-364B-45EA-B69F-579C62812388/Library/Cookies/Cookies.binarycookies
,2016-01-05 17:24:36.570 ThaliTest[1323:2824053] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-05 17:24:36.572 ThaliTest[1323:2824053] Multi-tasking -> Device: YES, App: YES
,2016-01-05 17:24:36.581 ThaliTest[1323:2824053] Unlimited access to network resources
,2016-01-05 17:24:36.595 ThaliTest[1323:2824053] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-05 17:24:45.853 ThaliTest[1323:2824053] Resetting plugins due to page load.
,2016-01-05 17:24:49.135 ThaliTest[1323:2824053] Finished load of: file:///var/mobile/Containers/Bundle/Application/199115A7-AD5A-4435-8446-116EE097DA77/ThaliTest.app/www/index.html
,2016-01-05 17:24:49.319 ThaliTest[1323:2824053] JXcore Cordova plugin initializing
,2016-01-05 17:24:49.320 ThaliTest[1323:2824283] JXcore instance initializing
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
,2016-01-05 17:30:11.507 ThaliTest[1323:2824283] jxcore: startBroadcasting
,2016-01-05 17:30:11.521 ThaliTest[1323:2824283] server: starting 1452011411506.1323.M2R2bA==
,2016-01-05 17:30:11.523 ThaliTest[1323:2824283] multipeer session: start timer: 0x1a04b850
,2016-01-05 17:30:11.524 ThaliTest[1323:2824283] THEMultipeerSession initialized peer 1452011411506.1323
2016-01-05 17:30:11.524 ThaliTest[1323:2824283] jxcore: startBroadcasting: success
,ok 45 Should be able to call startBroadcasting without error
,2016-01-05 17:30:11.529 ThaliTest[1323:2824283] jxcore: stopBroadcasting
,2016-01-05 17:30:11.529 ThaliTest[1323:2824283] THEMultipeerSession stopping peer
2016-01-05 17:30:11.531 ThaliTest[1323:2824283] multipeer session: stop timer
2016-01-05 17:30:11.532 ThaliTest[1323:2824283] jxcore: stopBroadcasting: success
ok 46 Should be able to call stopBroadcasting without error
2016-01-05 17:30:11.537 ThaliTest[1323:2824283] jxcore: startBroadcasting
,2016-01-05 17:30:11.547 ThaliTest[1323:2824283] server: starting 1452011411537.1323.N4Aexg==
2016-01-05 17:30:11.548 ThaliTest[1323:2824283] multipeer session: start timer: 0x1a049160
2016-01-05 17:30:11.555 ThaliTest[1323:2824283] THEMultipeerSession in,itialized peer 1452011411537.1323
2016-01-05 17:30:11.556 ThaliTest[1323:2824283] jxcore: startBroadcasting: success
ok 47 Should be able to call startBroadcasting without error
2016-01-05 17:30:11.559 ThaliTest[1323:2824283] jxcore: stopBroadcasting
2,016-01-05 17:30:11.559 ThaliTest[1323:2824283] THEMultipeerSession stopping peer
2016-01-05 17:30:11.559 ThaliTest[1323:2824283] multipeer session: stop timer
2016-01-05 17:30:11.560 ThaliTest[1323:2824283] jxcore: stopBroadcasting: success
,ok 48 Should be able to call stopBroadcasting without error
2016-01-05 17:30:11.563 ThaliTest[1323:2824283] jxcore: startBroadcasting
,2016-01-05 17:30:11.567 ThaliTest[1323:2824283] server: starting 1452011411562.1323.EShMXg==
2016-01-05 17:30:11.568 ThaliTest[1323:2824283] multipeer session: start timer: 0x1a15fe00
2016-01-05 17:30:11.569 ThaliTest[1323:2824283] THEMultipeerSession in,itialized peer 1452011411562.1323
2016-01-05 17:30:11.569 ThaliTest[1323:2824283] jxcore: startBroadcasting: success
ok 49 Should be able to call startBroadcasting without error
2016-01-05 17:30:11.571 ThaliTest[1323:2824283] jxcore: stopBroadcasting
2,016-01-05 17:30:11.572 ThaliTest[1323:2824283] THEMultipeerSession stopping peer
2016-01-05 17:30:11.572 ThaliTest[1323:2824283] multipeer session: stop timer
2016-01-05 17:30:11.573 ThaliTest[1323:2824283] jxcore: stopBroadcasting: success
ok 50 Should, be able to call stopBroadcasting without error
,2016-01-05 17:30:11.575 ThaliTest[1323:2824283] jxcore: startBroadcasting
,2016-01-05 17:30:11.596 ThaliTest[1323:2824283] server: starting 1452011411574.1323.SBeveg==
,2016-01-05 17:30:11.598 ThaliTest[1323:2824283] multipeer session: start timer: 0x1a162fe0
,2016-01-05 17:30:11.601 ThaliTest[1323:2824283] THEMultipeerSession initialized peer 1452011411574.1323
,2016-01-05 17:30:11.605 ThaliTest[1323:2824283] jxcore: startBroadcasting: success
,ok 51 Should be able to call startBroadcasting without error
,2016-01-05 17:30:11.610 ThaliTest[1323:2824283] jxcore: stopBroadcasting
,2016-01-05 17:30:11.611 ThaliTest[1323:2824283] THEMultipeerSession stopping peer
,2016-01-05 17:30:11.612 ThaliTest[1323:2824283] multipeer session: stop timer
,2016-01-05 17:30:11.613 ThaliTest[1323:2824283] jxcore: stopBroadcasting: success
,ok 52 Should be able to call stopBroadcasting without error
,2016-01-05 17:30:11.618 ThaliTest[1323:2824283] jxcore: startBroadcasting
,2016-01-05 17:30:11.621 ThaliTest[1323:2824283] server: starting 1452011411617.1323.ew7uqA==
,2016-01-05 17:30:11.624 ThaliTest[1323:2824283] multipeer session: start timer: 0x1a047920
,2016-01-05 17:30:11.627 ThaliTest[1323:2824283] THEMultipeerSession initialized peer 1452011411617.1323
,2016-01-05 17:30:11.628 ThaliTest[1323:2824283] jxcore: startBroadcasting: success
,ok 53 Should be able to call startBroadcasting without error
,2016-01-05 17:30:11.631 ThaliTest[1323:2824283] jxcore: stopBroadcasting
,2016-01-05 17:30:11.632 ThaliTest[1323:2824283] THEMultipeerSession stopping peer
,2016-01-05 17:30:11.633 ThaliTest[1323:2824283] multipeer session: stop timer
,2016-01-05 17:30:11.635 ThaliTest[1323:2824283] jxcore: stopBroadcasting: success
,ok 54 Should be able to call stopBroadcasting without error
,2016-01-05 17:30:11.639 ThaliTest[1323:2824283] jxcore: startBroadcasting
,2016-01-05 17:30:11.642 ThaliTest[1323:2824283] server: starting 1452011411638.1323.biglTQ==
,2016-01-05 17:30:11.644 ThaliTest[1323:2824283] multipeer session: start timer: 0x1a049d00
,2016-01-05 17:30:11.648 ThaliTest[1323:2824283] THEMultipeerSession initialized peer 1452011411638.1323
,2016-01-05 17:30:11.649 ThaliTest[1323:2824283] jxcore: startBroadcasting: success
,ok 55 Should be able to call startBroadcasting without error
,2016-01-05 17:30:11.653 ThaliTest[1323:2824283] jxcore: stopBroadcasting
,2016-01-05 17:30:11.653 ThaliTest[1323:2824283] THEMultipeerSession stopping peer
,2016-01-05 17:30:11.654 ThaliTest[1323:2824283] multipeer session: stop timer
,2016-01-05 17:30:11.655 ThaliTest[1323:2824283] jxcore: stopBroadcasting: success
,ok 56 Should be able to call stopBroadcasting without error
,2016-01-05 17:30:11.661 ThaliTest[1323:2824283] jxcore: startBroadcasting
,2016-01-05 17:30:11.664 ThaliTest[1323:2824283] server: starting 1452011411661.1323.QnRHZg==
,2016-01-05 17:30:11.665 ThaliTest[1323:2824283] multipeer session: start timer: 0x1a045e20
,2016-01-05 17:30:11.669 ThaliTest[1323:2824283] THEMultipeerSession initialized peer 1452011411661.1323
,2016-01-05 17:30:11.671 ThaliTest[1323:2824283] jxcore: startBroadcasting: success
,ok 57 Should be able to call startBroadcasting without error
,2016-01-05 17:30:11.674 ThaliTest[1323:2824283] jxcore: stopBroadcasting
,2016-01-05 17:30:11.675 ThaliTest[1323:2824283] THEMultipeerSession stopping peer
,2016-01-05 17:30:11.675 ThaliTest[1323:2824283] multipeer session: stop timer
,2016-01-05 17:30:11.676 ThaliTest[1323:2824283] jxcore: stopBroadcasting: success
,ok 58 Should be able to call stopBroadcasting without error
,2016-01-05 17:30:11.682 ThaliTest[1323:2824283] jxcore: startBroadcasting
,2016-01-05 17:30:11.685 ThaliTest[1323:2824283] server: starting 1452011411682.1323.IxoPWA==
,2016-01-05 17:30:11.687 ThaliTest[1323:2824283] multipeer session: start timer: 0x1a044990
,2016-01-05 17:30:11.689 ThaliTest[1323:2824283] THEMultipeerSession initialized peer 1452011411682.1323
,2016-01-05 17:30:11.691 ThaliTest[1323:2824283] jxcore: startBroadcasting: success
,ok 59 Should be able to call startBroadcasting without error
,2016-01-05 17:30:11.695 ThaliTest[1323:2824283] jxcore: stopBroadcasting
,2016-01-05 17:30:11.696 ThaliTest[1323:2824283] THEMultipeerSession stopping peer
,2016-01-05 17:30:11.697 ThaliTest[1323:2824283] multipeer session: stop timer
,2016-01-05 17:30:11.698 ThaliTest[1323:2824283] jxcore: stopBroadcasting: success
,ok 60 Should be able to call stopBroadcasting without error
,2016-01-05 17:30:11.704 ThaliTest[1323:2824283] jxcore: startBroadcasting
,2016-01-05 17:30:11.706 ThaliTest[1323:2824283] server: starting 1452011411703.1323.I2edow==
,2016-01-05 17:30:11.708 ThaliTest[1323:2824283] multipeer session: start timer: 0x1a165440
,2016-01-05 17:30:11.710 ThaliTest[1323:2824283] THEMultipeerSession initialized peer 1452011411703.1323
,2016-01-05 17:30:11.711 ThaliTest[1323:2824283] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error
,2016-01-05 17:30:11.715 ThaliTest[1323:2824283] jxcore: stopBroadcasting
,2016-01-05 17:30:11.715 ThaliTest[1323:2824283] THEMultipeerSession stopping peer
,2016-01-05 17:30:11.716 ThaliTest[1323:2824283] multipeer session: stop timer
,2016-01-05 17:30:11.717 ThaliTest[1323:2824283] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error
,2016-01-05 17:30:11.721 ThaliTest[1323:2824283] jxcore: startBroadcasting
,2016-01-05 17:30:11.723 ThaliTest[1323:2824283] server: starting 1452011411720.1323.MyYHgg==
,2016-01-05 17:30:11.724 ThaliTest[1323:2824283] multipeer session: start timer: 0x1a043a90
,2016-01-05 17:30:11.725 ThaliTest[1323:2824283] THEMultipeerSession initialized peer 1452011411720.1323
,2016-01-05 17:30:11.727 ThaliTest[1323:2824283] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error
,2016-01-05 17:30:11.731 ThaliTest[1323:2824283] jxcore: stopBroadcasting
,2016-01-05 17:30:11.731 ThaliTest[1323:2824283] THEMultipeerSession stopping peer
,2016-01-05 17:30:11.732 ThaliTest[1323:2824283] multipeer session: stop timer
,2016-01-05 17:30:11.733 ThaliTest[1323:2824283] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter calls startBroadcasting twice with error
,# teardown
,2016-01-05 17:30:12.344 ThaliTest[1323:2824283] jxcore: startBroadcasting
,2016-01-05 17:30:12.347 ThaliTest[1323:2824283] server: starting 1452011412343.1323.ysP9kA==
2016-01-05 17:30:12.348 ThaliTest[1323:2824283] multipeer session: start timer: 0x1a047750
2016-01-05 17:30:12.348 ThaliTest[1323:2824283] THEMultipeerSession in,itialized peer 1452011412343.1323
2016-01-05 17:30:12.349 ThaliTest[1323:2824283] jxcore: startBroadcasting: success
ok 65 Should be able to call startBroadcasting without error
,2016-01-05 17:30:12.351 ThaliTest[1323:2824283] jxcore: startBroadcasting
,2016-01-05 17:30:12.353 ThaliTest[1323:2824283] jxcore: startBroadcasting: failure
,ok 66 Cannot call startBroadcasting twice
2016-01-05 17:30:12.356 ThaliTest[1323:2824283] jxcore: stopBroadcasting
2016-01-05 17:30:12.357 ThaliTest[1323:2824283] THEMultipeerSession stopping peer
2016-01-05 17:30:12.357 ThaliTest[1323:2824283] multipeer session: stop timer
2016-01-05 17:30:12.357 ThaliTest[1323:2824283] jxcore: stopBroadcasting: success
ok 67 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on connection to bad peer
,# teardown
,2016-01-05 17:30:13.555 ThaliTest[1323:2824283] jxcore: startBroadcasting
,2016-01-05 17:30:13.558 ThaliTest[1323:2824283] server: starting 1452011413554.1323.VU72QQ==
2016-01-05 17:30:13.559 ThaliTest[1323:2824283] multipeer session: start timer: 0x1a040f40
2016-01-05 17:30:13.560 ThaliTest[1323:2824283] THEMultipeerSession in,itialized peer 1452011413554.1323
2016-01-05 17:30:13.560 ThaliTest[1323:2824283] jxcore: startBroadcasting: success
ok 68 Should be able to call startBroadcasting without error
2016-01-05 17:30:13.562 ThaliTest[1323:2824283] jxcore: connect foobar
201,6-01-05 17:30:13.563 ThaliTest[1323:2824283] client: unknown peer foobar
2016-01-05 17:30:13.563 ThaliTest[1323:2824283] jxcore: connect: fail: Unknown peer
ok 69 Should not connect to a bad peer
,2016-01-05 17:30:13.565 ThaliTest[1323:2824283] jxcore: stopBroadcasting
2016-01-05 17:30:13.565 ThaliTest[1323:2824283] THEMultipeerSession stopping peer
2016-01-05 17:30:13.566 ThaliTest[1323:2824283] multipeer session: stop timer
,2016-01-05 17:30:13.567 ThaliTest[1323:2824283] jxcore: stopBroadcasting: success
,ok 70 Should be able to call stopBroadcasting without error
# setup

```
