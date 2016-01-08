#### Test 549702618c0ebdb_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/549702618c0ebdb/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/DF90BCAD-75B4-4E27-933A-F56DD8D03CB3/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/DF90BCAD-75B4-4E27-933A-F56DD8D03CB3/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/549702618c0ebdb/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/549702618c0ebdb/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/CC5297A3-73DC-48F7-AAEE-FD0DA4012035/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50375"
,(lldb)     command script import "/tmp/DF90BCAD-75B4-4E27-933A-F56DD8D03CB3/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-01-08 16:29:17.976 ThaliTest[1098:3590490] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2F977FB0-97E1-4ED4-A453-19A8F748F130/Library/Cookies/Cookies.binarycookies
,2016-01-08 16:29:18.445 ThaliTest[1098:3590490] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-08 16:29:18.447 ThaliTest[1098:3590490] Multi-tasking -> Device: YES, App: YES
,2016-01-08 16:29:18.453 ThaliTest[1098:3590490] Unlimited access to network resources
,2016-01-08 16:29:18.463 ThaliTest[1098:3590490] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-08 16:29:28.027 ThaliTest[1098:3590490] Resetting plugins due to page load.
,2016-01-08 16:29:31.406 ThaliTest[1098:3590490] Finished load of: file:///var/mobile/Containers/Bundle/Application/CC5297A3-73DC-48F7-AAEE-FD0DA4012035/ThaliTest.app/www/index.html
,2016-01-08 16:29:31.619 ThaliTest[1098:3590490] JXcore Cordova plugin initializing
,2016-01-08 16:29:31.621 ThaliTest[1098:3590656] JXcore instance initializing
Initializing JXcore engine
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
,2016-01-08 16:35:20.448 ThaliTest[1098:3590656] jxcore: startBroadcasting
,2016-01-08 16:35:20.459 ThaliTest[1098:3590656] server: starting 1452267320448.1098.I7eQiw==
,2016-01-08 16:35:20.459 ThaliTest[1098:3590656] multipeer session: start timer: 0x18f67c10
2016-01-08 16:35:20.460 ThaliTest[1098:3590656] THEMultipeerSession initialized peer 1452267320448.1098
2016-01-08 16:35:20.460 ThaliTest[1098:3590656] jxcore: sta,rtBroadcasting: success
,ok 45 Should be able to call startBroadcasting without error
2016-01-08 16:35:20.477 ThaliTest[1098:3590656] jxcore: stopBroadcasting
2016-01-08 16:35:20.477 ThaliTest[1098:3590656] THEMultipeerSession stopping peer
2016-01-08 16:35:20.477 ThaliTest[109,8:3590656] multipeer session: stop timer
2016-01-08 16:35:20.478 ThaliTest[1098:3590656] jxcore: stopBroadcasting: success
ok 46 Should be able to call stopBroadcasting without error
,2016-01-08 16:35:20.480 ThaliTest[1098:3590656] jxcore: startBroadcasting
,2016-01-08 16:35:20.486 ThaliTest[1098:3590656] server: starting 1452267320480.1098.2vujOA==
2016-01-08 16:35:20.486 ThaliTest[1098:3590656] multipeer session: start timer: 0x18f84510
2016-01-08 16:35:20.487 ThaliTest[1098:3590656] THEMultipeerSession in,itialized peer 1452267320480.1098
2016-01-08 16:35:20.487 ThaliTest[1098:3590656] jxcore: startBroadcasting: success
,ok 47 Should be able to call startBroadcasting without error
,2016-01-08 16:35:20.495 ThaliTest[1098:3590656] jxcore: stopBroadcasting
,2016-01-08 16:35:20.495 ThaliTest[1098:3590656] THEMultipeerSession stopping peer
,2016-01-08 16:35:20.496 ThaliTest[1098:3590656] multipeer session: stop timer
2016-01-08 16:35:20.497 ThaliTest[1098:3590656] jxcore: stopBroadcasting: success
ok 48 Should be able to call stopBroadcasting without error
2016-01-08 16:35:20.499 ThaliTest,[1098:3590656] jxcore: startBroadcasting
2016-01-08 16:35:20.503 ThaliTest[1098:3590656] server: starting 1452267320499.1098.GhLNkA==
,2016-01-08 16:35:20.508 ThaliTest[1098:3590656] multipeer session: start timer: 0x189a1060
2016-01-08 16:35:20.508 ThaliTest[1098:3590656] THEMultipeerSession initialized peer 1452267320499.1098
2016-01-08 16:35:20.509 ThaliTest[1098:3590656] jxcore: startBroadcasting: success
,ok 49 Should be able to call startBroadcasting without error
,2016-01-08 16:35:20.513 ThaliTest[1098:3590656] jxcore: stopBroadcasting
2016-01-08 16:35:20.514 ThaliTest[1098:3590656] THEMultipeerSession stopping peer
2016-01-08 16:35:20.514 ThaliTest[1098:3590656] multipeer session: stop timer
2016-01-08 16:35:20.,515 ThaliTest[1098:3590656] jxcore: stopBroadcasting: success
ok 50 Should be able to call stopBroadcasting without error
,2016-01-08 16:35:20.517 ThaliTest[1098:3590656] jxcore: startBroadcasting
,2016-01-08 16:35:20.525 ThaliTest[1098:3590656] server: starting 1452267320517.1098.bpErPQ==
2016-01-08 16:35:20.526 ThaliTest[1098:3590656] multipeer session: start timer: 0x14523520
2016-01-08 16:35:20.526 ThaliTest[1098:3590656] THEMultipeerSession in,itialized peer 1452267320517.1098
2016-01-08 16:35:20.527 ThaliTest[1098:3590656] jxcore: startBroadcasting: success
ok 51 Should be able to call startBroadcasting without error
2016-01-08 16:35:20.529 ThaliTest[1098:3590656] jxcore: stopBroadcasting
2,016-01-08 16:35:20.530 ThaliTest[1098:3590656] THEMultipeerSession stopping peer
2016-01-08 16:35:20.530 ThaliTest[1098:3590656] multipeer session: stop timer
2016-01-08 16:35:20.530 ThaliTest[1098:3590656] jxcore: stopBroadcasting: success
ok 52 Should, be able to call stopBroadcasting without error
2016-01-08 16:35:20.532 ThaliTest[1098:3590656] jxcore: startBroadcasting
,2016-01-08 16:35:20.539 ThaliTest[1098:3590656] server: starting 1452267320532.1098.LmAKfg==
2016-01-08 16:35:20.540 ThaliTest[1098:3590656] multipeer session: start timer: 0x1c02d7f0
2016-01-08 16:35:20.541 ThaliTest[1098:3590656] THEMultipeerSession in,itialized peer 1452267320532.1098
2016-01-08 16:35:20.541 ThaliTest[1098:3590656] jxcore: startBroadcasting: success
ok 53 Should be able to call startBroadcasting without error
2016-01-08 16:35:20.542 ThaliTest[1098:3590656] jxcore: stopBroadcasting
2,016-01-08 16:35:20.542 ThaliTest[1098:3590656] THEMultipeerSession stopping peer
2016-01-08 16:35:20.543 ThaliTest[1098:3590656] multipeer session: stop timer
2016-01-08 16:35:20.543 ThaliTest[1098:3590656] jxcore: stopBroadcasting: success
ok 54 Should, be able to call stopBroadcasting without error
2016-01-08 16:35:20.544 ThaliTest[1098:3590656] jxcore: startBroadcasting
,2016-01-08 16:35:20.555 ThaliTest[1098:3590656] server: starting 1452267320544.1098.94Aiew==
2016-01-08 16:35:20.561 ThaliTest[1098:3590656] multipeer session: start timer: 0x18936580
2016-01-08 16:35:20.563 ThaliTest[1098:3590656] THEMultipeerSession in,itialized peer 1452267320544.1098
2016-01-08 16:35:20.564 ThaliTest[1098:3590656] jxcore: startBroadcasting: success
ok 55 Should be able to call startBroadcasting without error
2016-01-08 16:35:20.566 ThaliTest[1098:3590656] jxcore: stopBroadcasting
2,016-01-08 16:35:20.566 ThaliTest[1098:3590656] THEMultipeerSession stopping peer
2016-01-08 16:35:20.567 ThaliTest[1098:3590656] multipeer session: stop timer
2016-01-08 16:35:20.567 ThaliTest[1098:3590656] jxcore: stopBroadcasting: success
ok 56 Should, be able to call stopBroadcasting without error
2016-01-08 16:35:20.568 ThaliTest[1098:3590656] jxcore: startBroadcasting
,2016-01-08 16:35:20.575 ThaliTest[1098:3590656] server: starting 1452267320568.1098.p7OksA==
2016-01-08 16:35:20.575 ThaliTest[1098:3590656] multipeer session: start timer: 0x18a8c4e0
2016-01-08 16:35:20.575 ThaliTest[1098:3590656] THEMultipeerSession in,itialized peer 1452267320568.1098
2016-01-08 16:35:20.576 ThaliTest[1098:3590656] jxcore: startBroadcasting: success
ok 57 Should be able to call startBroadcasting without error
,2016-01-08 16:35:20.585 ThaliTest[1098:3590656] jxcore: stopBroadcasting
,2016-01-08 16:35:20.588 ThaliTest[1098:3590656] THEMultipeerSession stopping peer
,2016-01-08 16:35:20.591 ThaliTest[1098:3590656] multipeer session: stop timer
,2016-01-08 16:35:20.596 ThaliTest[1098:3590656] jxcore: stopBroadcasting: success
,ok 58 Should be able to call stopBroadcasting without error
,2016-01-08 16:35:20.600 ThaliTest[1098:3590656] jxcore: startBroadcasting
,2016-01-08 16:35:20.603 ThaliTest[1098:3590656] server: starting 1452267320600.1098.ZQBz5w==
,2016-01-08 16:35:20.606 ThaliTest[1098:3590656] multipeer session: start timer: 0x18c22f80
,2016-01-08 16:35:20.609 ThaliTest[1098:3590656] THEMultipeerSession initialized peer 1452267320600.1098
,2016-01-08 16:35:20.613 ThaliTest[1098:3590656] jxcore: startBroadcasting: success
,ok 59 Should be able to call startBroadcasting without error
,2016-01-08 16:35:20.616 ThaliTest[1098:3590656] jxcore: stopBroadcasting
,2016-01-08 16:35:20.616 ThaliTest[1098:3590656] THEMultipeerSession stopping peer
,2016-01-08 16:35:20.617 ThaliTest[1098:3590656] multipeer session: stop timer
,2016-01-08 16:35:20.618 ThaliTest[1098:3590656] jxcore: stopBroadcasting: success
,ok 60 Should be able to call stopBroadcasting without error
,2016-01-08 16:35:20.624 ThaliTest[1098:3590656] jxcore: startBroadcasting
,2016-01-08 16:35:20.627 ThaliTest[1098:3590656] server: starting 1452267320624.1098.mr1oSQ==
,2016-01-08 16:35:20.629 ThaliTest[1098:3590656] multipeer session: start timer: 0x18af56d0
,2016-01-08 16:35:20.632 ThaliTest[1098:3590656] THEMultipeerSession initialized peer 1452267320624.1098
,2016-01-08 16:35:20.636 ThaliTest[1098:3590656] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error
,2016-01-08 16:35:20.639 ThaliTest[1098:3590656] jxcore: stopBroadcasting
,2016-01-08 16:35:20.640 ThaliTest[1098:3590656] THEMultipeerSession stopping peer
,2016-01-08 16:35:20.641 ThaliTest[1098:3590656] multipeer session: stop timer
,2016-01-08 16:35:20.642 ThaliTest[1098:3590656] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error
,2016-01-08 16:35:20.648 ThaliTest[1098:3590656] jxcore: startBroadcasting
,2016-01-08 16:35:20.651 ThaliTest[1098:3590656] server: starting 1452267320648.1098.8tlF0Q==
,2016-01-08 16:35:20.653 ThaliTest[1098:3590656] multipeer session: start timer: 0x18d0b5f0
,2016-01-08 16:35:20.657 ThaliTest[1098:3590656] THEMultipeerSession initialized peer 1452267320648.1098
,2016-01-08 16:35:20.659 ThaliTest[1098:3590656] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error
,2016-01-08 16:35:20.664 ThaliTest[1098:3590656] jxcore: stopBroadcasting
,2016-01-08 16:35:20.665 ThaliTest[1098:3590656] THEMultipeerSession stopping peer
,2016-01-08 16:35:20.666 ThaliTest[1098:3590656] multipeer session: stop timer
,2016-01-08 16:35:20.667 ThaliTest[1098:3590656] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter calls startBroadcasting twice with error
,# teardown
,2016-01-08 16:35:20.809 ThaliTest[1098:3590656] jxcore: startBroadcasting
,2016-01-08 16:35:20.812 ThaliTest[1098:3590656] server: starting 1452267320809.1098.tUKw6g==
2016-01-08 16:35:20.812 ThaliTest[1098:3590656] multipeer session: start timer: 0x18b42480
2016-01-08 16:35:20.813 ThaliTest[1098:3590656] THEMultipeerSession in,itialized peer 1452267320809.1098
2016-01-08 16:35:20.813 ThaliTest[1098:3590656] jxcore: startBroadcasting: success
ok 65 Should be able to call startBroadcasting without error
2016-01-08 16:35:20.815 ThaliTest[1098:3590656] jxcore: startBroadcasting
,2016-01-08 16:35:20.815 ThaliTest[1098:3590656] jxcore: startBroadcasting: failure
ok 66 Cannot call startBroadcasting twice
2016-01-08 16:35:20.816 ThaliTest[1098:3590656] jxcore: stopBroadcasting
2016-01-08 16:35:20.816 ThaliTest[1098:3590656] THEMult,ipeerSession stopping peer
2016-01-08 16:35:20.817 ThaliTest[1098:3590656] multipeer session: stop timer
2016-01-08 16:35:20.817 ThaliTest[1098:3590656] jxcore: stopBroadcasting: success
ok 67 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on connection to bad peer
,# teardown
,2016-01-08 16:35:20.929 ThaliTest[1098:3590656] jxcore: startBroadcasting
,2016-01-08 16:35:20.931 ThaliTest[1098:3590656] server: starting 1452267320928.1098.dlnmeQ==
,2016-01-08 16:35:20.934 ThaliTest[1098:3590656] multipeer session: start timer: 0x18da3cf0
,2016-01-08 16:35:20.938 ThaliTest[1098:3590656] THEMultipeerSession initialized peer 1452267320928.1098
,2016-01-08 16:35:20.939 ThaliTest[1098:3590656] jxcore: startBroadcasting: success
,ok 68 Should be able to call startBroadcasting without error
,2016-01-08 16:35:20.942 ThaliTest[1098:3590656] jxcore: connect foobar
,2016-01-08 16:35:20.943 ThaliTest[1098:3590656] client: unknown peer foobar
,2016-01-08 16:35:20.944 ThaliTest[1098:3590656] jxcore: connect: fail: Unknown peer
,ok 69 Should not connect to a bad peer
,2016-01-08 16:35:20.948 ThaliTest[1098:3590656] jxcore: stopBroadcasting
,2016-01-08 16:35:20.949 ThaliTest[1098:3590656] THEMultipeerSession stopping peer
,2016-01-08 16:35:20.951 ThaliTest[1098:3590656] multipeer session: stop timer
,2016-01-08 16:35:20.956 ThaliTest[1098:3590656] jxcore: stopBroadcasting: success
,ok 70 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on disconnect to bad peer
,# teardown
,2016-01-08 16:35:21.295 ThaliTest[1098:3590656] jxcore: startBroadcasting
,2016-01-08 16:35:21.297 ThaliTest[1098:3590656] server: starting 1452267321294.1098.9HsU1g==
2016-01-08 16:35:21.298 ThaliTest[1098:3590656] multipeer session: start timer: 0x18b22530
2016-01-08 16:35:21.298 ThaliTest[1098:3590656] THEMultipeerSession in,itialized peer 1452267321294.1098
2016-01-08 16:35:21.298 ThaliTest[1098:3590656] jxcore: startBroadcasting: success
ok 71 Should be able to call startBroadcasting without error
2016-01-08 16:35:21.300 ThaliTest[1098:3590656] jxcore: disconnect
2016-01,-08 16:35:21.300 ThaliTest[1098:3590656] jxcore: disconnect: fail
ok 72 Disconnect should fail to a non-existant peer 
2016-01-08 16:35:21.301 ThaliTest[1098:3590656] jxcore: stopBroadcasting
2016-01-08 16:35:21.301 ThaliTest[1098:3590656] THEMultipeerS,ession stopping peer
2016-01-08 16:35:21.302 ThaliTest[1098:3590656] multipeer session: stop timer
2016-01-08 16:35:21.302 ThaliTest[1098:3590656] jxcore: stopBroadcasting: success
ok 73 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter can discover and connect to peers
,# teardown
,2016-01-08 16:35:21.384 ThaliTest[1098:3590656] jxcore: startBroadcasting
,2016-01-08 16:35:21.387 ThaliTest[1098:3590656] server: starting 1452267321384.1098.R8al9Q==
2016-01-08 16:35:21.387 ThaliTest[1098:3590656] multipeer session: start timer: 0x1891ede0
2016-01-08 16:35:21.387 ThaliTest[1098:3590656] THEMultipeerSession in,itialized peer 1452267321384.1098
2016-01-08 16:35:21.388 ThaliTest[1098:3590656] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error
,2016-01-08 16:35:22.178 ThaliTest[1098:3590490] client: found peer: 1452267321371.1520.T3uJKQ==
2016-01-08 16:35:22.179 ThaliTest[1098:3590656] jxcore: connect 1452267321371.1520.T3uJKQ==
2016-01-08 16:35:22.180 ThaliTest[1098:3590656] client session: co,nnect
2016-01-08 16:35:22.180 ThaliTest[1098:3590656] client session: stateChange:0->1 1452267321371.1520.T3uJKQ==
,2016-01-08 16:35:22.673 ThaliTest[1098:3590490] multipeer session: reset timer
2016-01-08 16:35:22.673 ThaliTest[1098:3590490] multipeer session: stop timer
2016-01-08 16:35:22.674 ThaliTest[1098:3590490] multipeer session: start timer: 0x1891ede0
2016-,01-08 16:35:22.674 ThaliTest[1098:3590490] server session: connect
2016-01-08 16:35:22.674 ThaliTest[1098:3590490] server session: stateChange:0->1 1452267321371.1520
,2016-01-08 16:35:22.680 ThaliTest[1098:3590490] server: accepting invitation 1452267321371.1520
,2016-01-08 16:35:25.243 ThaliTest[1098:3591249] server session: connected
2016-01-08 16:35:25.243 ThaliTest[1098:3591249] server session: stateChange:1->2 1452267321371.1520
,2016-01-08 16:35:25.398 ThaliTest[1098:3590490] server relay: socket disconnected
2016-01-08 16:35:25.398 ThaliTest[1098:3590490] server relay: 0x18ca9d90 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLoc,alizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-08 16:35:25.434 ThaliTest[1098:3591249] server session: not connected 1452267321371.1520
,2016-01-08 16:35:25.444 ThaliTest[1098:3591255] client session: connected
2016-01-08 16:35:25.445 ThaliTest[1098:3591255] client session: stateChange:1->2 1452267321371.1520.T3uJKQ==
,2016-01-08 16:35:26.742 ThaliTest[1098:3591251] client session: fireConnectCallback: 1452267321371.1520.T3uJKQ==
2016-01-08 16:35:26.742 ThaliTest[1098:3591251] jxcore: connect: success
ok 75 Should be able to connect without error
,ok 76 Port should be within range
,2016-01-08 16:35:26.746 ThaliTest[1098:3590656] jxcore: disconnect
2016-01-08 16:35:26.747 ThaliTest[1098:3590656] client session: disconnectFromPeer: 1452267321371.1520.T3uJKQ==
2016-01-08 16:35:26.747 ThaliTest[1098:3590656] client session: disconnect,
2016-01-08 16:35:26.747 ThaliTest[1098:3590656] client session: stateChange:2->0 1452267321371.1520.T3uJKQ==
,2016-01-08 16:35:26.757 ThaliTest[1098:3590656] jxcore: disconnect: success
ok 77 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
,2016-01-08 16:35:27.193 ThaliTest[1098:3590656] jxcore: stopBroadcasting
2016-01-08 16:35:27.193 ThaliTest[1098:3590656] THEMultipeerSession stopping peer
2016-01-08 16:35:27.193 ThaliTest[1098:3590656] multipeer session: stop timer
2016-01-08 16:35:27.,194 ThaliTest[1098:3590656] server session: disconnect
2016-01-08 16:35:27.194 ThaliTest[1098:3590656] server session: stateChange:2->0 1452267321371.1520
2016-01-08 16:35:27.195 ThaliTest[1098:3590656] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter can discover and connect to peers and then fail on double connect
,# teardown
,2016-01-08 16:35:28.128 ThaliTest[1098:3590656] jxcore: startBroadcasting
,2016-01-08 16:35:28.130 ThaliTest[1098:3590656] server: starting 1452267328127.1098.dyzcWg==
2016-01-08 16:35:28.131 ThaliTest[1098:3590656] multipeer session: start timer: 0x18aef340
2016-01-08 16:35:28.131 ThaliTest[1098:3590656] THEMultipeerSession in,itialized peer 1452267328127.1098
2016-01-08 16:35:28.131 ThaliTest[1098:3590656] jxcore: startBroadcasting: success
ok 78 Should be able to call startBroadcasting without error
,2016-01-08 16:35:29.457 ThaliTest[1098:3590490] client: found peer: 1452267327752.1520.DA77og==
2016-01-08 16:35:29.458 ThaliTest[1098:3590656] jxcore: connect 1452267327752.1520.DA77og==
2016-01-08 16:35:29.458 ThaliTest[1098:3590656] client session: co,nnect
2016-01-08 16:35:29.459 ThaliTest[1098:3590656] client session: stateChange:0->1 1452267327752.1520.DA77og==
,2016-01-08 16:35:29.516 ThaliTest[1098:3590490] multipeer session: reset timer
2016-01-08 16:35:29.517 ThaliTest[1098:3590490] multipeer session: stop timer
2016-01-08 16:35:29.517 ThaliTest[1098:3590490] multipeer session: start timer: 0x18aef340
2016-,01-08 16:35:29.518 ThaliTest[1098:3590490] server session: connect
2016-01-08 16:35:29.518 ThaliTest[1098:3590490] server session: stateChange:0->1 1452267327752.1520
,2016-01-08 16:35:29.528 ThaliTest[1098:3590490] server: accepting invitation 1452267327752.1520
,2016-01-08 16:35:32.125 ThaliTest[1098:3591255] server session: connected
2016-01-08 16:35:32.126 ThaliTest[1098:3591255] server session: stateChange:1->2 1452267327752.1520
,2016-01-08 16:35:32.192 ThaliTest[1098:3590490] server relay: socket disconnected
2016-01-08 16:35:32.192 ThaliTest[1098:3590490] server relay: 0x18eccb40 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLoc,alizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-08 16:35:32.234 ThaliTest[1098:3591264] server session: not connected 1452267327752.1520
,2016-01-08 16:35:32.250 ThaliTest[1098:3591264] client session: connected
,2016-01-08 16:35:32.250 ThaliTest[1098:3591264] client session: stateChange:1->2 1452267327752.1520.DA77og==
,2016-01-08 16:35:32.515 ThaliTest[1098:3591255] client session: fireConnectCallback: 1452267327752.1520.DA77og==
2016-01-08 16:35:32.515 ThaliTest[1098:3591255] jxcore: connect: success
ok 79 Should be able to connect without error
ok 80 Port should be ,within range
2016-01-08 16:35:32.517 ThaliTest[1098:3590656] jxcore: connect 1452267327752.1520.DA77og==
2016-01-08 16:35:32.517 ThaliTest[1098:3590656] client: already connect(ing/ed) to 1452267327752.1520.DA77og==
2016-01-08 16:35:32.517 ThaliTest[109,8:3590656] jxcore: connect: fail: Aleady connecting
ok 81 Should fail on double connect
2016-01-08 16:35:32.519 ThaliTest[1098:3590656] jxcore: disconnect
2016-01-08 16:35:32.519 ThaliTest[1098:3590656] client session: disconnectFromPeer: 1452267327752.,1520.DA77og==
2016-01-08 16:35:32.519 ThaliTest[1098:3590656] client session: disconnect
2016-01-08 16:35:32.519 ThaliTest[1098:3590656] client session: stateChange:2->0 1452267327752.1520.DA77og==
,2016-01-08 16:35:32.531 ThaliTest[1098:3590656] jxcore: disconnect: success
ok 82 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
,2016-01-08 16:35:33.663 ThaliTest[1098:3590656] jxcore: stopBroadcasting
2016-01-08 16:35:33.664 ThaliTest[1098:3590656] THEMultipeerSession stopping peer
2016-01-08 16:35:33.664 ThaliTest[1098:3590656] multipeer session: stop timer
2016-01-08 16:35:33.,664 ThaliTest[1098:3590656] server session: disconnect
2016-01-08 16:35:33.665 ThaliTest[1098:3590656] server session: stateChange:2->0 1452267327752.1520
,2016-01-08 16:35:33.668 ThaliTest[1098:3590656] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter can discover and connect to peers and then fail on double disconnect
,# teardown
,2016-01-08 16:35:34.583 ThaliTest[1098:3590656] jxcore: startBroadcasting
,2016-01-08 16:35:34.585 ThaliTest[1098:3590656] server: starting 1452267334583.1098.EBDrlg==
2016-01-08 16:35:34.585 ThaliTest[1098:3590656] multipeer session: start timer: 0x18eed7b0
2016-01-08 16:35:34.586 ThaliTest[1098:3590656] THEMultipeerSession in,itialized peer 1452267334583.1098
2016-01-08 16:35:34.586 ThaliTest[1098:3590656] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error
,2016-01-08 16:35:35.715 ThaliTest[1098:3590490] client: found peer: 1452267334463.1520.FQc8/A==
2016-01-08 16:35:35.716 ThaliTest[1098:3590656] jxcore: connect 1452267334463.1520.FQc8/A==
,2016-01-08 16:35:35.716 ThaliTest[1098:3590656] client session: connect
2016-01-08 16:35:35.717 ThaliTest[1098:3590656] client session: stateChange:0->1 1452267334463.1520.FQc8/A==
,2016-01-08 16:35:36.243 ThaliTest[1098:3590490] multipeer session: reset timer
2016-01-08 16:35:36.243 ThaliTest[1098:3590490] multipeer session: stop timer
2016-01-08 16:35:36.244 ThaliTest[1098:3590490] multipeer session: start timer: 0x18eed7b0
2016-,01-08 16:35:36.244 ThaliTest[1098:3590490] server session: connect
2016-01-08 16:35:36.244 ThaliTest[1098:3590490] server session: stateChange:0->1 1452267334463.1520
,2016-01-08 16:35:36.250 ThaliTest[1098:3590490] server: accepting invitation 1452267334463.1520
,2016-01-08 16:35:38.877 ThaliTest[1098:3591251] client session: connected
2016-01-08 16:35:38.877 ThaliTest[1098:3591251] client session: stateChange:1->2 1452267334463.1520.FQc8/A==
,2016-01-08 16:35:38.894 ThaliTest[1098:3591255] client session: fireConnectCallback: 1452267334463.1520.FQc8/A==
2016-01-08 16:35:38.894 ThaliTest[1098:3591255] jxcore: connect: success
ok 84 Should be able to connect without error
ok 85 Port should be within range
,2016-01-08 16:35:38.897 ThaliTest[1098:3590656] jxcore: disconnect
2016-01-08 16:35:38.897 ThaliTest[1098:3590656] client session: disconnectFromPeer: 1452267334463.1520.FQc8/A==
,2016-01-08 16:35:38.897 ThaliTest[1098:3590656] client session: disconnect
2016-01-08 16:35:38.897 ThaliTest[1098:3590656] client session: stateChange:2->0 1452267334463.1520.FQc8/A==
,2016-01-08 16:35:38.970 ThaliTest[1098:3590656] jxcore: disconnect: success
ok 86 Should be able to disconnect without error
,2016-01-08 16:35:38.973 ThaliTest[1098:3590656] jxcore: disconnect
,2016-01-08 16:35:38.973 ThaliTest[1098:3590656] jxcore: disconnect: fail
,ok 87 Disconnect should fail 
setting stopBroadcasting callback and ending test.
,# setup
,2016-01-08 16:35:39.334 ThaliTest[1098:3591251] server session: connected
2016-01-08 16:35:39.334 ThaliTest[1098:3591251] server session: stateChange:1->2 1452267334463.1520
,2016-01-08 16:35:39.337 ThaliTest[1098:3590490] server relay: socket disconnected
2016-01-08 16:35:39.337 ThaliTest[1098:3590490] server relay: 0x18bcf5b0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLoc,alizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-08 16:35:39.454 ThaliTest[1098:3591255] server session: not connected 1452267334463.1520
,calling stopBroadcasting
,2016-01-08 16:35:39.729 ThaliTest[1098:3590656] jxcore: stopBroadcasting
2016-01-08 16:35:39.729 ThaliTest[1098:3590656] THEMultipeerSession stopping peer
2016-01-08 16:35:39.729 ThaliTest[1098:3590656] multipeer session: stop timer
2016-01-08 16:35:39.,730 ThaliTest[1098:3590656] server session: disconnect
2016-01-08 16:35:39.730 ThaliTest[1098:3590656] server session: stateChange:2->0 1452267334463.1520
,2016-01-08 16:35:39.732 ThaliTest[1098:3590656] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter handles socket disconnect correctly
,# teardown
,2016-01-08 16:35:40.251 ThaliTest[1098:3590656] jxcore: startBroadcasting
,2016-01-08 16:35:40.253 ThaliTest[1098:3590656] server: starting 1452267340250.1098.gxXw7Q==
2016-01-08 16:35:40.253 ThaliTest[1098:3590656] multipeer session: start timer: 0x18d46610
2016-01-08 16:35:40.253 ThaliTest[1098:3590656] THEMultipeerSession in,itialized peer 1452267340250.1098
2016-01-08 16:35:40.254 ThaliTest[1098:3590656] jxcore: startBroadcasting: success
ok 88 Should be able to call startBroadcasting without error
,echo server started
,2016-01-08 16:35:41.103 ThaliTest[1098:3590490] client: found peer: 1452267340224.1520.QS302Q==
[{"peerIdentifier":"1452267340224.1520.QS302Q==","peerName":"(null)","peerAvailable":true}]
2016-01-08 16:35:41.105 ThaliTest[1098:3590656] jxcore: connect 1452267340224.1520.QS302Q==
2016-01-08 16:35:41.107 ThaliTest[1098:3590656] client session: connect
,2016-01-08 16:35:41.107 ThaliTest[1098:3590656] client session: stateChange:0->1 1452267340224.1520.QS302Q==
,2016-01-08 16:35:41.678 ThaliTest[1098:3590490] multipeer session: reset timer
2016-01-08 16:35:41.678 ThaliTest[1098:3590490] multipeer session: stop timer
2016-01-08 16:35:41.678 ThaliTest[1098:3590490] multipeer session: start timer: 0x18d46610
2016-,01-08 16:35:41.678 ThaliTest[1098:3590490] server session: connect
2016-01-08 16:35:41.678 ThaliTest[1098:3590490] server session: stateChange:0->1 1452267340224.1520
2016-01-08 16:35:41.683 ThaliTest[1098:3590490] server: accepting invitation 1452267340224.1520
,2016-01-08 16:35:44.249 ThaliTest[1098:3591249] client session: connected
2016-01-08 16:35:44.249 ThaliTest[1098:3591249] client session: stateChange:1->2 1452267340224.1520.QS302Q==
,2016-01-08 16:35:44.289 ThaliTest[1098:3591255] client session: fireConnectCallback: 1452267340224.1520.QS302Q==
2016-01-08 16:35:44.289 ThaliTest[1098:3591255] jxcore: connect: success
ok 89 Should be able to connect without error
,ok 90 Port should be within range
,ok 91 First connect should succeed
,2016-01-08 16:35:44.328 ThaliTest[1098:3590490] client: relay established
2016-01-08 16:35:44.328 ThaliTest[1098:3590490] client: new accepted socket: 0x18c858e0
,ok 92 the test messages should be equal
,ok 93 First send should succeed
,2016-01-08 16:35:44.401 ThaliTest[1098:3590490] client: socket closed
2016-01-08 16:35:44.402 ThaliTest[1098:3590490] client relay: socket disconnected
2016-01-08 16:35:44.402 ThaliTest[1098:3590490] client relay: 0x18c858e0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-08 16:35:44.403 ThaliTest[1098:3590490] client session: socket closed: 1452267340224.1520.QS302Q==
2016-01-08 ,16:35:44.403 ThaliTest[1098:3590490] client session: onLinkFailure: 1452267340224.1520.QS302Q==
2016-01-08 16:35:44.403 ThaliTest[1098:3590490] client session: disconnect
2016-01-08 16:35:44.404 ThaliTest[1098:3590490] client session: stateChange:2->0 14,52267340224.1520.QS302Q==
,2016-01-08 16:35:44.413 ThaliTest[1098:3590490] client session: fireConnectionErrorEvent: 1452267340224.1520.QS302Q==
2016-01-08 16:35:44.416 ThaliTest[1098:3590656] jxcore: connect 1452267340224.1520.QS302Q==
2016-01-08 16:35:44.416 ThaliTest[1098:35906,56] client session: connect
2016-01-08 16:35:44.416 ThaliTest[1098:3590656] client session: stateChange:0->1 1452267340224.1520.QS302Q==
,2016-01-08 16:35:44.480 ThaliTest[1098:3591251] server session: connected
2016-01-08 16:35:44.480 ThaliTest[1098:3591251] server session: stateChange:1->2 1452267340224.1520
,2016-01-08 16:35:44.533 ThaliTest[1098:3590490] server relay: connected (to port: 5001)
,2016-01-08 16:35:44.705 ThaliTest[1098:3591249] server session: not connected 1452267340224.1520
,2016-01-08 16:35:44.833 ThaliTest[1098:3590490] multipeer session: reset timer
2016-01-08 16:35:44.833 ThaliTest[1098:3590490] multipeer session: stop timer
2016-01-08 16:35:44.833 ThaliTest[1098:3590490] multipeer session: start timer: 0x18d46610
2016-,01-08 16:35:44.833 ThaliTest[1098:3590490] server: disconnecting to refresh session (1452267340224.1520)
2016-01-08 16:35:44.833 ThaliTest[1098:3590490] server session: disconnect
2016-01-08 16:35:44.834 ThaliTest[1098:3590490] server session: stateChang,e:2->0 1452267340224.1520
,2016-01-08 16:35:44.837 ThaliTest[1098:3590490] server session: connect
2016-01-08 16:35:44.837 ThaliTest[1098:3590490] server session: stateChange:0->1 1452267340224.1520
,2016-01-08 16:35:44.848 ThaliTest[1098:3590490] server: accepting invitation 1452267340224.1520
,2016-01-08 16:35:47.392 ThaliTest[1098:3591264] client session: connected
2016-01-08 16:35:47.393 ThaliTest[1098:3591264] client session: stateChange:1->2 1452267340224.1520.QS302Q==
,2016-01-08 16:35:47.455 ThaliTest[1098:3591251] client session: fireConnectCallback: 1452267340224.1520.QS302Q==
2016-01-08 16:35:47.455 ThaliTest[1098:3591251] jxcore: connect: success
ok 94 Should be able to connect without error
ok 95 Port should be within range
,ok 96 Second connect should succeed
,2016-01-08 16:35:47.485 ThaliTest[1098:3590490] client: relay established
2016-01-08 16:35:47.485 ThaliTest[1098:3590490] client: new accepted socket: 0x18cd2c20
,2016-01-08 16:35:47.514 ThaliTest[1098:3591249] server session: connected
2016-01-08 16:35:47.514 ThaliTest[1098:3591249] server session: stateChange:1->2 1452267340224.1520
,2016-01-08 16:35:47.579 ThaliTest[1098:3590490] server relay: connected (to port: 5001)
,ok 97 the test messages should be equal
,ok 98 Second send should succeed
,# setup
,2016-01-08 16:35:47.607 ThaliTest[1098:3590490] client: socket closed
2016-01-08 16:35:47.608 ThaliTest[1098:3590490] client relay: socket disconnected
2016-01-08 16:35:47.608 ThaliTest[1098:3590490] client relay: 0x18cd2c20 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-08 16:35:47.609 ThaliTest[1098:3590490] client session: socket closed: 1452267340224.1520.QS302Q==
2016-01-08 ,16:35:47.609 ThaliTest[1098:3590490] client session: onLinkFailure: 1452267340224.1520.QS302Q==
2016-01-08 16:35:47.609 ThaliTest[1098:3590490] client session: disconnect
2016-01-08 16:35:47.609 ThaliTest[1098:3590490] client session: stateChange:2->0 14,52267340224.1520.QS302Q==
,2016-01-08 16:35:47.619 ThaliTest[1098:3590490] client session: fireConnectionErrorEvent: 1452267340224.1520.QS302Q==
,2016-01-08 16:35:47.776 ThaliTest[1098:3591251] server session: not connected 1452267340224.1520
,calling stopBroadcasting
,2016-01-08 16:35:48.475 ThaliTest[1098:3590656] jxcore: stopBroadcasting
2016-01-08 16:35:48.476 ThaliTest[1098:3590656] THEMultipeerSession stopping peer
2016-01-08 16:35:48.476 ThaliTest[1098:3590656] multipeer session: stop timer
2016-01-08 16:35:48.,477 ThaliTest[1098:3590656] server session: disconnect
2016-01-08 16:35:48.477 ThaliTest[1098:3590656] server session: stateChange:2->0 1452267340224.1520
,2016-01-08 16:35:48.483 ThaliTest[1098:3590656] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliReplicationManager can call start without error
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/2F977FB0-97E1-4ED4-A453-19A8F748F130/tmp/pouchdb"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,",failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,ok 99 starting event should occur in right order
,2016-01-08 16:35:49.270 ThaliTest[1098:3590656] jxcore: startBroadcasting
,2016-01-08 16:35:49.273 ThaliTest[1098:3590656] server: starting inWzZitBjeeV_nkurKzNlw.Ou1NZA==
2016-01-08 16:35:49.274 ThaliTest[1098:3590656] multipeer session: start timer: 0x18d28ae0
2016-01-08 16:35:49.274 ThaliTest[1098:3590656] THEMultipeerSessio,n initialized peer inWzZitBjeeV_nkurKzNlw
2016-01-08 16:35:49.274 ThaliTest[1098:3590656] jxcore: startBroadcasting: success
ok 100 started event should occur in right order
Now in TRM stop
State of this._isStarted: true
,ok 101 stopping event should occur in right order
About to call stopBroadcasting
,2016-01-08 16:35:49.279 ThaliTest[1098:3590656] jxcore: stopBroadcasting
2016-01-08 16:35:49.279 ThaliTest[1098:3590656] THEMultipeerSession stopping peer
2016-01-08 16:35:49.279 ThaliTest[1098:3590656] multipeer session: stop timer
2016-01-08 16:35:49.,279 ThaliTest[1098:3590656] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined
ok 102 stopped event should occur in right order
,mux server bridge listener closed
,# setup
,# ThaliReplicationManager receives identity
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/2F977FB0-97E1-4ED4-A453-19A8F748F130/tmp/pouchdb"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,",failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,2016-01-08 16:35:50.291 ThaliTest[1098:3590656] jxcore: startBroadcasting
,2016-01-08 16:35:50.293 ThaliTest[1098:3590656] server: starting inWzZitBjeeV_nkurKzNlw.l4KijA==
2016-01-08 16:35:50.294 ThaliTest[1098:3590656] multipeer session: start timer: 0x14509c60
2016-01-08 16:35:50.294 ThaliTest[1098:3590656] THEMultipeerSessio,n initialized peer inWzZitBjeeV_nkurKzNlw
2016-01-08 16:35:50.294 ThaliTest[1098:3590656] jxcore: startBroadcasting: success
ok 103 getDeviceIdentity should not return an error
ok 104 deviceName should not be null
Now in TRM stop
State of this._isStar,ted: true
About to call stopBroadcasting
2016-01-08 16:35:50.298 ThaliTest[1098:3590656] jxcore: stopBroadcasting
2016-01-08 16:35:50.298 ThaliTest[1098:3590656] THEMultipeerSession stopping peer
2016-01-08 16:35:50.298 ThaliTest[1098:3590656] multipee,r session: stop timer
2016-01-08 16:35:50.298 ThaliTest[1098:3590656] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined
,mux server bridge listener closed
Tests Complete
,Total: 0	Passed: 0	Failed: 0
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
