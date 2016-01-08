#### Test 549702610b97681_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/549702610b97681/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/2B663D05-93FD-4D43-B221-CBCD2563A385/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/2B663D05-93FD-4D43-B221-CBCD2563A385/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/549702610b97681/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/549702610b97681/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/5D63C2B0-62D1-45B0-A827-26839B390F5E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51480"
,(lldb)     command script import "/tmp/2B663D05-93FD-4D43-B221-CBCD2563A385/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-09 00:02:30.054 ThaliTest[1155:3649974] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E7615EA4-DEA8-431F-B5CB-7B5A0AFB6DF3/Library/Cookies/Cookies.binarycookies
,2016-01-09 00:02:30.181 ThaliTest[1155:3649974] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-09 00:02:30.183 ThaliTest[1155:3649974] Multi-tasking -> Device: YES, App: YES
,2016-01-09 00:02:30.190 ThaliTest[1155:3649974] Unlimited access to network resources
,2016-01-09 00:02:30.204 ThaliTest[1155:3649974] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-09 00:02:40.544 ThaliTest[1155:3649974] Resetting plugins due to page load.
,2016-01-09 00:02:44.562 ThaliTest[1155:3649974] Finished load of: file:///var/mobile/Containers/Bundle/Application/5D63C2B0-62D1-45B0-A827-26839B390F5E/ThaliTest.app/www/index.html
,2016-01-09 00:02:44.775 ThaliTest[1155:3649974] JXcore Cordova plugin initializing
,2016-01-09 00:02:44.777 ThaliTest[1155:3650153] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,My device name is: Apple-Iphone5-1
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
,2016-01-09 00:08:32.361 ThaliTest[1155:3650153] jxcore: startBroadcasting
,2016-01-09 00:08:32.374 ThaliTest[1155:3650153] server: starting 1452294512360.1155.HkOFIQ==
,2016-01-09 00:08:32.374 ThaliTest[1155:3650153] multipeer session: start timer: 0x1aee7f50
,2016-01-09 00:08:32.375 ThaliTest[1155:3650153] THEMultipeerSession initialized peer 1452294512360.1155
,2016-01-09 00:08:32.376 ThaliTest[1155:3650153] jxcore: startBroadcasting: success
,ok 45 Should be able to call startBroadcasting without error
2016-01-09 00:08:32.381 ThaliTest[1155:3650153] jxcore: stopBroadcasting
2016-01-09 00:08:32.382 ThaliTest[1155:3650153] THEMultipeerSession stopping peer
2016-01-09 00:08:32.382 ThaliTest[115,5:3650153] multipeer session: stop timer
2016-01-09 00:08:32.382 ThaliTest[1155:3650153] jxcore: stopBroadcasting: success
ok 46 Should be able to call stopBroadcasting without error
2016-01-09 00:08:32.385 ThaliTest[1155:3650153] jxcore: startBroadcasting
,2016-01-09 00:08:32.392 ThaliTest[1155:3650153] server: starting 1452294512384.1155.ii4DAQ==
2016-01-09 00:08:32.393 ThaliTest[1155:3650153] multipeer session: start timer: 0x1ad1d330
2016-01-09 00:08:32.393 ThaliTest[1155:3650153] THEMultipeerSession in,itialized peer 1452294512384.1155
2016-01-09 00:08:32.393 ThaliTest[1155:3650153] jxcore: startBroadcasting: success
ok 47 Should be able to call startBroadcasting without error
2016-01-09 00:08:32.395 ThaliTest[1155:3650153] jxcore: stopBroadcasting
2,016-01-09 00:08:32.395 ThaliTest[1155:3650153] THEMultipeerSession stopping peer
2016-01-09 00:08:32.396 ThaliTest[1155:3650153] multipeer session: stop timer
2016-01-09 00:08:32.396 ThaliTest[1155:3650153] jxcore: stopBroadcasting: success
ok 48 Should, be able to call stopBroadcasting without error
2016-01-09 00:08:32.398 ThaliTest[1155:3650153] jxcore: startBroadcasting
2016-01-09 00:08:32.404 ThaliTest[1155:3650153] server: starting 1452294512398.1155.9FrkIw==
2016-01-09 00:08:32.405 ThaliTest[1155,:3650153] multipeer session: start timer: 0x1a9efef0
2016-01-09 00:08:32.411 ThaliTest[1155:3650153] THEMultipeerSession initialized peer 1452294512398.1155
2016-01-09 00:08:32.412 ThaliTest[1155:3650153] jxcore: startBroadcasting: success
ok 49 Should ,be able to call startBroadcasting without error
2016-01-09 00:08:32.414 ThaliTest[1155:3650153] jxcore: stopBroadcasting
2016-01-09 00:08:32.414 ThaliTest[1155:3650153] THEMultipeerSession stopping peer
2016-01-09 00:08:32.415 ThaliTest[1155:3650153] multipeer session: stop timer
,2016-01-09 00:08:32.415 ThaliTest[1155:3650153] jxcore: stopBroadcasting: success
,ok 50 Should be able to call stopBroadcasting without error
2016-01-09 00:08:32.421 ThaliTest[1155:3650153] jxcore: startBroadcasting
,2016-01-09 00:08:32.427 ThaliTest[1155:3650153] server: starting 1452294512421.1155.yskmIA==
2016-01-09 00:08:32.428 ThaliTest[1155:3650153] multipeer session: start timer: 0x14ee8bd0
2016-01-09 00:08:32.428 ThaliTest[1155:3650153] THEMultipeerSession initialized peer 1452294512421.1155
2016-01-09 00:08:32.428 ThaliTest[1155:3650153] jxcore: startBroadcasting: success
,ok 51 Should be able to call startBroadcasting without error
2016-01-09 00:08:32.435 ThaliTest[1155:3650153] jxcore: stopBroadcasting
2016-01-09 00:08:32.435 ThaliTest[1155:3650153] THEMultipeerSession stopping peer
2016-01-09 00:08:32.435 ThaliTest[115,5:3650153] multipeer session: stop timer
2016-01-09 00:08:32.436 ThaliTest[1155:3650153] jxcore: stopBroadcasting: success
ok 52 Should be able to call stopBroadcasting without error
2016-01-09 00:08:32.438 ThaliTest[1155:3650153] jxcore: startBroadcast,ing
,2016-01-09 00:08:32.447 ThaliTest[1155:3650153] server: starting 1452294512437.1155.MO8HXA==
,2016-01-09 00:08:32.451 ThaliTest[1155:3650153] multipeer session: start timer: 0x14dc0a70
,2016-01-09 00:08:32.462 ThaliTest[1155:3650153] THEMultipeerSession initialized peer 1452294512437.1155
,2016-01-09 00:08:32.468 ThaliTest[1155:3650153] jxcore: startBroadcasting: success
,ok 53 Should be able to call startBroadcasting without error
,2016-01-09 00:08:32.474 ThaliTest[1155:3650153] jxcore: stopBroadcasting
,2016-01-09 00:08:32.474 ThaliTest[1155:3650153] THEMultipeerSession stopping peer
,2016-01-09 00:08:32.475 ThaliTest[1155:3650153] multipeer session: stop timer
,2016-01-09 00:08:32.477 ThaliTest[1155:3650153] jxcore: stopBroadcasting: success
,ok 54 Should be able to call stopBroadcasting without error
,2016-01-09 00:08:32.484 ThaliTest[1155:3650153] jxcore: startBroadcasting
,2016-01-09 00:08:32.486 ThaliTest[1155:3650153] server: starting 1452294512483.1155.0pTPqA==
,2016-01-09 00:08:32.489 ThaliTest[1155:3650153] multipeer session: start timer: 0x14ddbf70
,2016-01-09 00:08:32.492 ThaliTest[1155:3650153] THEMultipeerSession initialized peer 1452294512483.1155
,2016-01-09 00:08:32.496 ThaliTest[1155:3650153] jxcore: startBroadcasting: success
,ok 55 Should be able to call startBroadcasting without error
,2016-01-09 00:08:32.498 ThaliTest[1155:3650153] jxcore: stopBroadcasting
,2016-01-09 00:08:32.499 ThaliTest[1155:3650153] THEMultipeerSession stopping peer
,2016-01-09 00:08:32.500 ThaliTest[1155:3650153] multipeer session: stop timer
,2016-01-09 00:08:32.503 ThaliTest[1155:3650153] jxcore: stopBroadcasting: success
,ok 56 Should be able to call stopBroadcasting without error
,2016-01-09 00:08:32.507 ThaliTest[1155:3650153] jxcore: startBroadcasting
,2016-01-09 00:08:32.509 ThaliTest[1155:3650153] server: starting 1452294512506.1155.7wZ5YQ==
,2016-01-09 00:08:32.512 ThaliTest[1155:3650153] multipeer session: start timer: 0x1c83e680
,2016-01-09 00:08:32.517 ThaliTest[1155:3650153] THEMultipeerSession initialized peer 1452294512506.1155
,2016-01-09 00:08:32.519 ThaliTest[1155:3650153] jxcore: startBroadcasting: success
,ok 57 Should be able to call startBroadcasting without error
,2016-01-09 00:08:32.521 ThaliTest[1155:3650153] jxcore: stopBroadcasting
,2016-01-09 00:08:32.522 ThaliTest[1155:3650153] THEMultipeerSession stopping peer
,2016-01-09 00:08:32.523 ThaliTest[1155:3650153] multipeer session: stop timer
,2016-01-09 00:08:32.525 ThaliTest[1155:3650153] jxcore: stopBroadcasting: success
,ok 58 Should be able to call stopBroadcasting without error
,2016-01-09 00:08:32.530 ThaliTest[1155:3650153] jxcore: startBroadcasting
,2016-01-09 00:08:32.533 ThaliTest[1155:3650153] server: starting 1452294512530.1155.Xh6AVg==
,2016-01-09 00:08:32.536 ThaliTest[1155:3650153] multipeer session: start timer: 0x1aa71fb0
,2016-01-09 00:08:32.543 ThaliTest[1155:3650153] THEMultipeerSession initialized peer 1452294512530.1155
,2016-01-09 00:08:32.544 ThaliTest[1155:3650153] jxcore: startBroadcasting: success
,ok 59 Should be able to call startBroadcasting without error
,2016-01-09 00:08:32.546 ThaliTest[1155:3650153] jxcore: stopBroadcasting
,2016-01-09 00:08:32.547 ThaliTest[1155:3650153] THEMultipeerSession stopping peer
,2016-01-09 00:08:32.547 ThaliTest[1155:3650153] multipeer session: stop timer
,2016-01-09 00:08:32.549 ThaliTest[1155:3650153] jxcore: stopBroadcasting: success
,ok 60 Should be able to call stopBroadcasting without error
,2016-01-09 00:08:32.555 ThaliTest[1155:3650153] jxcore: startBroadcasting
,2016-01-09 00:08:32.557 ThaliTest[1155:3650153] server: starting 1452294512554.1155.WbWobQ==
,2016-01-09 00:08:32.559 ThaliTest[1155:3650153] multipeer session: start timer: 0x1c841040
,2016-01-09 00:08:32.562 ThaliTest[1155:3650153] THEMultipeerSession initialized peer 1452294512554.1155
,2016-01-09 00:08:32.567 ThaliTest[1155:3650153] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error
,2016-01-09 00:08:32.570 ThaliTest[1155:3650153] jxcore: stopBroadcasting
,2016-01-09 00:08:32.571 ThaliTest[1155:3650153] THEMultipeerSession stopping peer
,2016-01-09 00:08:32.571 ThaliTest[1155:3650153] multipeer session: stop timer
,2016-01-09 00:08:32.575 ThaliTest[1155:3650153] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error
,2016-01-09 00:08:32.579 ThaliTest[1155:3650153] jxcore: startBroadcasting
,2016-01-09 00:08:32.581 ThaliTest[1155:3650153] server: starting 1452294512578.1155./jHCBA==
,2016-01-09 00:08:32.584 ThaliTest[1155:3650153] multipeer session: start timer: 0x14da4b10
,2016-01-09 00:08:32.587 ThaliTest[1155:3650153] THEMultipeerSession initialized peer 1452294512578.1155
,2016-01-09 00:08:32.591 ThaliTest[1155:3650153] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error
,2016-01-09 00:08:32.593 ThaliTest[1155:3650153] jxcore: stopBroadcasting
,2016-01-09 00:08:32.594 ThaliTest[1155:3650153] THEMultipeerSession stopping peer
,2016-01-09 00:08:32.595 ThaliTest[1155:3650153] multipeer session: stop timer
,2016-01-09 00:08:32.599 ThaliTest[1155:3650153] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter calls startBroadcasting twice with error
,# teardown
,2016-01-09 00:08:32.753 ThaliTest[1155:3650153] jxcore: startBroadcasting
,2016-01-09 00:08:32.755 ThaliTest[1155:3650153] server: starting 1452294512752.1155.6kX08Q==
2016-01-09 00:08:32.756 ThaliTest[1155:3650153] multipeer session: start timer: 0x1c8bfaf0
,2016-01-09 00:08:32.756 ThaliTest[1155:3650153] THEMultipeerSession initialized peer 1452294512752.1155
2016-01-09 00:08:32.758 ThaliTest[1155:3650153] jxcore: startBroadcasting: success
ok 65 Should be able to call startBroadcasting without error
2016-,01-09 00:08:32.760 ThaliTest[1155:3650153] jxcore: startBroadcasting
2016-01-09 00:08:32.760 ThaliTest[1155:3650153] jxcore: startBroadcasting: failure
ok 66 Cannot call startBroadcasting twice
2016-01-09 00:08:32.761 ThaliTest[1155:3650153] jxcore: stopBroadcasting
2016-01-09 00:08:32.762 ThaliTest[1155:3650153] THEMultipeerSession stopping peer
2016-01-09 00:08:32.762 ThaliTest[1155:3650153] multipeer session: stop timer
2016-01-09 00:08:32.762 ThaliTest[1155:3650153] jxcore: stopBroadcasting: succe,ss
ok 67 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on connection to bad peer
,# teardown
,2016-01-09 00:08:33.205 ThaliTest[1155:3650153] jxcore: startBroadcasting
,2016-01-09 00:08:33.207 ThaliTest[1155:3650153] server: starting 1452294513204.1155.EolaWg==
2016-01-09 00:08:33.208 ThaliTest[1155:3650153] multipeer session: start timer: 0x1ade9510
2016-01-09 00:08:33.208 ThaliTest[1155:3650153] THEMultipeerSession in,itialized peer 1452294513204.1155
2016-01-09 00:08:33.208 ThaliTest[1155:3650153] jxcore: startBroadcasting: success
ok 68 Should be able to call startBroadcasting without error
2016-01-09 00:08:33.210 ThaliTest[1155:3650153] jxcore: connect foobar
2016-01-09 00:08:33.210 ThaliTest[1155:3650153] client: unknown peer foobar
2016-01-09 00:08:33.210 ThaliTest[1155:3650153] jxcore: connect: fail: Unknown peer
ok 69 Should not connect to a bad peer
,2016-01-09 00:08:33.212 ThaliTest[1155:3650153] jxcore: stopBroadcasting
2016-01-09 00:08:33.212 ThaliTest[1155:3650153] THEMultipeerSession stopping peer
2016-01-09 00:08:33.212 ThaliTest[1155:3650153] multipeer session: stop timer
2016-01-09 00:08:33.,212 ThaliTest[1155:3650153] jxcore: stopBroadcasting: success
,ok 70 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on disconnect to bad peer
,# teardown
,2016-01-09 00:08:33.345 ThaliTest[1155:3650153] jxcore: startBroadcasting
,2016-01-09 00:08:33.347 ThaliTest[1155:3650153] server: starting 1452294513344.1155.+L5khQ==
2016-01-09 00:08:33.347 ThaliTest[1155:3650153] multipeer session: start timer: 0x1ad90f90
2016-01-09 00:08:33.348 ThaliTest[1155:3650153] THEMultipeerSession in,itialized peer 1452294513344.1155
2016-01-09 00:08:33.348 ThaliTest[1155:3650153] jxcore: startBroadcasting: success
ok 71 Should be able to call startBroadcasting without error
2016-01-09 00:08:33.349 ThaliTest[1155:3650153] jxcore: disconnect
2016-01,-09 00:08:33.349 ThaliTest[1155:3650153] jxcore: disconnect: fail
,ok 72 Disconnect should fail to a non-existant peer 
2016-01-09 00:08:33.351 ThaliTest[1155:3650153] jxcore: stopBroadcasting
2016-01-09 00:08:33.352 ThaliTest[1155:3650153] THEMultipeerSession stopping peer
2016-01-09 00:08:33.352 ThaliTest[1155:365015,3] multipeer session: stop timer
2016-01-09 00:08:33.352 ThaliTest[1155:3650153] jxcore: stopBroadcasting: success
ok 73 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter can discover and connect to peers
,# teardown
,2016-01-09 00:08:34.891 ThaliTest[1155:3650153] jxcore: startBroadcasting
,2016-01-09 00:08:34.894 ThaliTest[1155:3650153] server: starting 1452294514891.1155.yOzLtg==
2016-01-09 00:08:34.894 ThaliTest[1155:3650153] multipeer session: start timer: 0x1add5400
2016-01-09 00:08:34.894 ThaliTest[1155:3650153] THEMultipeerSession in,itialized peer 1452294514891.1155
2016-01-09 00:08:34.894 ThaliTest[1155:3650153] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error
,2016-01-09 00:08:36.100 ThaliTest[1155:3649974] client: found peer: 1452294514965.1603.XskMJQ==
2016-01-09 00:08:36.102 ThaliTest[1155:3650153] jxcore: connect 1452294514965.1603.XskMJQ==
2016-01-09 00:08:36.102 ThaliTest[1155:3650153] client session: connect
2016-01-09 00:08:36.102 ThaliTest[1155:3650153] client session: stateChange:0->1 1452294514965.1603.XskMJQ==
,2016-01-09 00:08:36.239 ThaliTest[1155:3649974] multipeer session: reset timer
2016-01-09 00:08:36.239 ThaliTest[1155:3649974] multipeer session: stop timer
2016-01-09 00:08:36.239 ThaliTest[1155:3649974] multipeer session: start timer: 0x1add5400
2016-,01-09 00:08:36.240 ThaliTest[1155:3649974] server session: connect
2016-01-09 00:08:36.240 ThaliTest[1155:3649974] server session: stateChange:0->1 1452294514965.1603
,2016-01-09 00:08:36.247 ThaliTest[1155:3649974] server: accepting invitation 1452294514965.1603
,2016-01-09 00:08:38.853 ThaliTest[1155:3650820] client session: connected
2016-01-09 00:08:38.853 ThaliTest[1155:3650820] client session: stateChange:1->2 1452294514965.1603.XskMJQ==
,2016-01-09 00:08:38.886 ThaliTest[1155:3650811] client session: fireConnectCallback: 1452294514965.1603.XskMJQ==
2016-01-09 00:08:38.886 ThaliTest[1155:3650811] jxcore: connect: success
,ok 75 Should be able to connect without error
,ok 76 Port should be within range
,2016-01-09 00:08:38.890 ThaliTest[1155:3650153] jxcore: disconnect
,2016-01-09 00:08:38.890 ThaliTest[1155:3650153] client session: disconnectFromPeer: 1452294514965.1603.XskMJQ==
,2016-01-09 00:08:38.890 ThaliTest[1155:3650153] client session: disconnect
,2016-01-09 00:08:38.890 ThaliTest[1155:3650153] client session: stateChange:2->0 1452294514965.1603.XskMJQ==
,2016-01-09 00:08:38.904 ThaliTest[1155:3650153] jxcore: disconnect: success
,ok 77 Should be able to disconnect without error
,setting stopBroadcasting callback and ending test.
,# setup
,2016-01-09 00:08:38.926 ThaliTest[1155:3650820] server session: connected
,2016-01-09 00:08:38.926 ThaliTest[1155:3650820] server session: stateChange:1->2 1452294514965.1603
,2016-01-09 00:08:38.955 ThaliTest[1155:3649974] server relay: socket disconnected
,2016-01-09 00:08:38.955 ThaliTest[1155:3649974] server relay: 0x1aa6e430 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-09 00:08:39.772 ThaliTest[1155:3650811] server session: not connected 1452294514965.1603
,2016-01-09 00:08:42.900 ThaliTest[1155:3649974] client: lost peer: 1452294514965.1603.XskMJQ==
2016-01-09 00:08:42.900 ThaliTest[1155:3649974] client session: onPeerLost: 1452294514965.1603.XskMJQ==
,calling stopBroadcasting
,2016-01-09 00:08:49.588 ThaliTest[1155:3650153] jxcore: stopBroadcasting
2016-01-09 00:08:49.589 ThaliTest[1155:3650153] THEMultipeerSession stopping peer
2016-01-09 00:08:49.589 ThaliTest[1155:3650153] multipeer session: stop timer
,2016-01-09 00:08:49.590 ThaliTest[1155:3650153] server session: disconnect
2016-01-09 00:08:49.590 ThaliTest[1155:3650153] server session: stateChange:2->0 1452294514965.1603
,2016-01-09 00:08:49.593 ThaliTest[1155:3650153] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliEmitter can discover and connect to peers and then fail on double connect
,# teardown
,2016-01-09 00:09:03.524 ThaliTest[1155:3650153] jxcore: startBroadcasting
,2016-01-09 00:09:03.526 ThaliTest[1155:3650153] server: starting 1452294543523.1155.3lGMTw==
2016-01-09 00:09:03.527 ThaliTest[1155:3650153] multipeer session: start timer: 0x1afa4950
2016-01-09 00:09:03.527 ThaliTest[1155:3650153] THEMultipeerSession initialized peer 1452294543523.1155
2016-01-09 00:09:03.527 ThaliTest[1155:3650153] jxcore: startBroadcasting: success
ok 78 Should be able to call startBroadcasting without error
,2016-01-09 00:09:04.905 ThaliTest[1155:3649974] client: found peer: 1452294543639.1603.1SENGA==
2016-01-09 00:09:04.906 ThaliTest[1155:3650153] jxcore: connect 1452294543639.1603.1SENGA==
2016-01-09 00:09:04.906 ThaliTest[1155:3650153] client session: connect
2016-01-09 00:09:04.906 ThaliTest[1155:3650153] client session: stateChange:0->1 1452294543639.1603.1SENGA==
,2016-01-09 00:09:05.557 ThaliTest[1155:3649974] multipeer session: reset timer
2016-01-09 00:09:05.557 ThaliTest[1155:3649974] multipeer session: stop timer
2016-01-09 00:09:05.557 ThaliTest[1155:3649974] multipeer session: start timer: 0x1afa4950
2016-,01-09 00:09:05.557 ThaliTest[1155:3649974] server session: connect
2016-01-09 00:09:05.558 ThaliTest[1155:3649974] server session: stateChange:0->1 1452294543639.1603
,2016-01-09 00:09:05.564 ThaliTest[1155:3649974] server: accepting invitation 1452294543639.1603
,2016-01-09 00:09:08.145 ThaliTest[1155:3650922] server session: connected
2016-01-09 00:09:08.145 ThaliTest[1155:3650922] server session: stateChange:1->2 1452294543639.1603
,2016-01-09 00:09:08.208 ThaliTest[1155:3650953] server session: not connected 1452294543639.1603
,2016-01-09 00:09:08.341 ThaliTest[1155:3650953] client session: connected
2016-01-09 00:09:08.341 ThaliTest[1155:3650953] client session: stateChange:1->2 1452294543639.1603.1SENGA==
,2016-01-09 00:09:08.358 ThaliTest[1155:3650923] client session: fireConnectCallback: 1452294543639.1603.1SENGA==
2016-01-09 00:09:08.358 ThaliTest[1155:3650923] jxcore: connect: success
ok 79 Should be able to connect without error
ok 80 Port should be ,within range
2016-01-09 00:09:08.360 ThaliTest[1155:3650153] jxcore: connect 1452294543639.1603.1SENGA==
2016-01-09 00:09:08.360 ThaliTest[1155:3650153] client: already connect(ing/ed) to 1452294543639.1603.1SENGA==
2016-01-09 00:09:08.361 ThaliTest[115,5:3650153] jxcore: connect: fail: Aleady connecting
,ok 81 Should fail on double connect
,2016-01-09 00:09:08.363 ThaliTest[1155:3650153] jxcore: disconnect
,2016-01-09 00:09:08.364 ThaliTest[1155:3650153] client session: disconnectFromPeer: 1452294543639.1603.1SENGA==
2016-01-09 00:09:08.364 ThaliTest[1155:3650153] client session: disconnect
2016-01-09 00:09:08.364 ThaliTest[1155:3650153] client session: sta,teChange:2->0 1452294543639.1603.1SENGA==
,2016-01-09 00:09:08.373 ThaliTest[1155:3650153] jxcore: disconnect: success
,ok 82 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
2016-01-09 00:09:08.489 ThaliTest[1155:3650153] jxcore: stopBroadcasting
2016-01-09 00:09:08.490 ThaliTest[1155:3650153] THEMultipeerSession stopping peer
2016-01-09 00:09:08.490 ThaliTest[1155:3650153] multipeer session: stop timer
2016-01-09 00:09:08.490 ThaliTest[1155:3650153] server session: disconnect
2016-01-09 00:09:08.490 ThaliTest[1155:3650153] server session: stateChange:2->0 1452294543639.1603
,2016-01-09 00:09:08.607 ThaliTest[1155:3650153] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter can discover and connect to peers and then fail on double disconnect
,# teardown
,2016-01-09 00:09:08.988 ThaliTest[1155:3650153] jxcore: startBroadcasting
,2016-01-09 00:09:08.990 ThaliTest[1155:3650153] server: starting 1452294548987.1155.Cr861g==
2016-01-09 00:09:08.991 ThaliTest[1155:3650153] multipeer session: start timer: 0x1ac925f0
2016-01-09 00:09:08.991 ThaliTest[1155:3650153] THEMultipeerSession in,itialized peer 1452294548987.1155
2016-01-09 00:09:08.991 ThaliTest[1155:3650153] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error
,2016-01-09 00:09:10.106 ThaliTest[1155:3649974] client: found peer: 1452294548999.1603./7PX5g==
2016-01-09 00:09:10.107 ThaliTest[1155:3650153] jxcore: connect 1452294548999.1603./7PX5g==
2016-01-09 00:09:10.107 ThaliTest[1155:3650153] client session: connect
2016-01-09 00:09:10.107 ThaliTest[1155:3650153] client session: stateChange:0->1 1452294548999.1603./7PX5g==
,2016-01-09 00:09:10.386 ThaliTest[1155:3649974] multipeer session: reset timer
2016-01-09 00:09:10.386 ThaliTest[1155:3649974] multipeer session: stop timer
2016-01-09 00:09:10.387 ThaliTest[1155:3649974] multipeer session: start timer: 0x1ac925f0
2016-01-09 00:09:10.387 ThaliTest[1155:3649974] server session: connect
2016-01-09 00:09:10.387 ThaliTest[1155:3649974] server session: stateChange:0->1 1452294548999.1603
,2016-01-09 00:09:10.393 ThaliTest[1155:3649974] server: accepting invitation 1452294548999.1603
,2016-01-09 00:09:13.201 ThaliTest[1155:3650923] server session: connected
2016-01-09 00:09:13.201 ThaliTest[1155:3650923] server session: stateChange:1->2 1452294548999.1603
,2016-01-09 00:09:13.219 ThaliTest[1155:3650954] client session: connected
2016-01-09 00:09:13.219 ThaliTest[1155:3650954] client session: stateChange:1->2 1452294548999.1603./7PX5g==
,2016-01-09 00:09:13.253 ThaliTest[1155:3650964] client session: fireConnectCallback: 1452294548999.1603./7PX5g==
2016-01-09 00:09:13.254 ThaliTest[1155:3650964] jxcore: connect: success
ok 84 Should be able to connect without error
ok 85 Port should be within range
2016-01-09 00:09:13.256 ThaliTest[1155:3650153] jxcore: disconnect
,2016-01-09 00:09:13.257 ThaliTest[1155:3650153] client session: disconnectFromPeer: 1452294548999.1603./7PX5g==
,2016-01-09 00:09:13.257 ThaliTest[1155:3650153] client session: disconnect
2016-01-09 00:09:13.257 ThaliTest[1155:3650153] client session: stateChange:2->0 1452294548999.1603./7PX5g==
2016-01-09 00:09:13.258 ThaliTest[1155:3649974] server relay: socket d,isconnected
2016-01-09 00:09:13.258 ThaliTest[1155:3649974] server relay: 0x1ae51c60 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescriptio,n=Connection refused} 
,2016-01-09 00:09:13.270 ThaliTest[1155:3650153] jxcore: disconnect: success
,ok 86 Should be able to disconnect without error
2016-01-09 00:09:13.273 ThaliTest[1155:3650153] jxcore: disconnect
2016-01-09 00:09:13.273 ThaliTest[1155:3650153] jxcore: disconnect: fail
ok 87 Disconnect should fail 
setting stopBroadcasting callback and ending test.
,# setup
,2016-01-09 00:09:13.320 ThaliTest[1155:3650954] server session: not connected 1452294548999.1603
,calling stopBroadcasting
,2016-01-09 00:09:14.234 ThaliTest[1155:3650153] jxcore: stopBroadcasting
2016-01-09 00:09:14.234 ThaliTest[1155:3650153] THEMultipeerSession stopping peer
2016-01-09 00:09:14.234 ThaliTest[1155:3650153] multipeer session: stop timer
,2016-01-09 00:09:14.236 ThaliTest[1155:3650153] server session: disconnect
2016-01-09 00:09:14.236 ThaliTest[1155:3650153] server session: stateChange:2->0 1452294548999.1603
,2016-01-09 00:09:14.880 ThaliTest[1155:3650153] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter handles socket disconnect correctly
,# teardown
,2016-01-09 00:09:15.291 ThaliTest[1155:3650153] jxcore: startBroadcasting
,2016-01-09 00:09:15.294 ThaliTest[1155:3650153] server: starting 1452294555291.1155.+whsTw==
2016-01-09 00:09:15.294 ThaliTest[1155:3650153] multipeer session: start timer: 0x1add1810
2016-01-09 00:09:15.294 ThaliTest[1155:3650153] THEMultipeerSession in,itialized peer 1452294555291.1155
2016-01-09 00:09:15.295 ThaliTest[1155:3650153] jxcore: startBroadcasting: success
ok 88 Should be able to call startBroadcasting without error
,echo server started
,2016-01-09 00:09:16.405 ThaliTest[1155:3649974] client: found peer: 1452294555306.1603.7eKM8g==
[{"peerIdentifier":"1452294555306.1603.7eKM8g==","peerName":"(null)","peerAvailable":true}]
2016-01-09 00:09:16.407 ThaliTest[1155:3650153] jxcore: connect 14,52294555306.1603.7eKM8g==
2016-01-09 00:09:16.407 ThaliTest[1155:3650153] client session: connect
2016-01-09 00:09:16.407 ThaliTest[1155:3650153] client session: stateChange:0->1 1452294555306.1603.7eKM8g==
,2016-01-09 00:09:16.596 ThaliTest[1155:3649974] multipeer session: reset timer
2016-01-09 00:09:16.597 ThaliTest[1155:3649974] multipeer session: stop timer
2016-01-09 00:09:16.597 ThaliTest[1155:3649974] multipeer session: start timer: 0x1add1810
,2016-01-09 00:09:16.597 ThaliTest[1155:3649974] server session: connect
2016-01-09 00:09:16.598 ThaliTest[1155:3649974] server session: stateChange:0->1 1452294555306.1603
,2016-01-09 00:09:16.605 ThaliTest[1155:3649974] server: accepting invitation 1452294555306.1603
,2016-01-09 00:09:19.229 ThaliTest[1155:3650954] client session: connected
2016-01-09 00:09:19.229 ThaliTest[1155:3650954] client session: stateChange:1->2 1452294555306.1603.7eKM8g==
,2016-01-09 00:09:19.285 ThaliTest[1155:3650924] server session: connected
2016-01-09 00:09:19.286 ThaliTest[1155:3650924] server session: stateChange:1->2 1452294555306.1603
2016-01-09 00:09:19.289 ThaliTest[1155:3650954] client session: fireConnectCallback: 1452294555306.1603.7eKM8g==
2016-01-09 00:09:19.290 ThaliTest[1155:3650954] jxcore: connect: success
ok 89 Should be able to connect without error
,ok 90 Port should be within range
,ok 91 First connect should succeed
2016-01-09 00:09:19.297 ThaliTest[1155:3649974] server relay: connected (to port: 5001)
,2016-01-09 00:09:19.338 ThaliTest[1155:3649974] client: relay established
2016-01-09 00:09:19.339 ThaliTest[1155:3649974] client: new accepted socket: 0x1ab5a7a0
,ok 92 the test messages should be equal
,ok 93 First send should succeed
,2016-01-09 00:09:19.437 ThaliTest[1155:3649974] client: socket closed
2016-01-09 00:09:19.438 ThaliTest[1155:3649974] client relay: socket disconnected
2016-01-09 00:09:19.438 ThaliTest[1155:3649974] client relay: 0x1ab5a7a0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-09 00:09:19.438 ThaliTest[1155:3649974] client session: socket closed: 1452294555306.1603.7eKM8g==
2016-01-09 ,00:09:19.439 ThaliTest[1155:3649974] client session: onLinkFailure: 1452294555306.1603.7eKM8g==
2016-01-09 00:09:19.439 ThaliTest[1155:3649974] client session: disconnect
2016-01-09 00:09:19.439 ThaliTest[1155:3649974] client session: stateChange:2->0 14,52294555306.1603.7eKM8g==
,2016-01-09 00:09:19.448 ThaliTest[1155:3649974] client session: fireConnectionErrorEvent: 1452294555306.1603.7eKM8g==
,2016-01-09 00:09:19.454 ThaliTest[1155:3650153] jxcore: connect 1452294555306.1603.7eKM8g==
,2016-01-09 00:09:19.455 ThaliTest[1155:3650153] client session: connect
,2016-01-09 00:09:19.462 ThaliTest[1155:3650153] client session: stateChange:0->1 1452294555306.1603.7eKM8g==
,2016-01-09 00:09:19.517 ThaliTest[1155:3650923] server session: not connected 1452294555306.1603
,2016-01-09 00:09:19.609 ThaliTest[1155:3649974] multipeer session: reset timer
2016-01-09 00:09:19.610 ThaliTest[1155:3649974] multipeer session: stop timer
2016-01-09 00:09:19.610 ThaliTest[1155:3649974] multipeer session: start timer: 0x1add1810
2016-,01-09 00:09:19.610 ThaliTest[1155:3649974] server: disconnecting to refresh session (1452294555306.1603)
2016-01-09 00:09:19.610 ThaliTest[1155:3649974] server session: disconnect
,2016-01-09 00:09:19.611 ThaliTest[1155:3649974] server session: stateChange:2->0 1452294555306.1603
,2016-01-09 00:09:19.614 ThaliTest[1155:3649974] server session: connect
2016-01-09 00:09:19.615 ThaliTest[1155:3649974] server session: stateChange:0->1 1452294555306.1603
,2016-01-09 00:09:19.623 ThaliTest[1155:3649974] server: accepting invitation 1452294555306.1603
,2016-01-09 00:09:22.246 ThaliTest[1155:3650924] server session: connected
2016-01-09 00:09:22.246 ThaliTest[1155:3650924] server session: stateChange:1->2 1452294555306.1603
,2016-01-09 00:09:22.253 ThaliTest[1155:3649974] server relay: connected (to port: 5001)
,2016-01-09 00:09:22.269 ThaliTest[1155:3650924] client session: connected
2016-01-09 00:09:22.269 ThaliTest[1155:3650924] client session: stateChange:1->2 1452294555306.1603.7eKM8g==
2016-01-09 00:09:22.274 ThaliTest[1155:3650964] client session: fireCon,nectCallback: 1452294555306.1603.7eKM8g==
2016-01-09 00:09:22.275 ThaliTest[1155:3650964] jxcore: connect: success
ok 94 Should be able to connect without error
ok 95 Port should be within range
ok 96 Second connect should succeed
,2016-01-09 00:09:22.303 ThaliTest[1155:3649974] client: relay established
2016-01-09 00:09:22.303 ThaliTest[1155:3649974] client: new accepted socket: 0x1a910e90
,ok 97 the test messages should be equal
,ok 98 Second send should succeed
,# setup
,2016-01-09 00:09:22.378 ThaliTest[1155:3649974] client: socket closed
2016-01-09 00:09:22.379 ThaliTest[1155:3649974] client relay: socket disconnected
2016-01-09 00:09:22.380 ThaliTest[1155:3649974] client relay: 0x1a910e90 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-09 00:09:22.380 ThaliTest[1155:3649974] client session: socket closed: 1452294555306.1603.7eKM8g==
2016-01-09 ,00:09:22.380 ThaliTest[1155:3649974] client session: onLinkFailure: 1452294555306.1603.7eKM8g==
2016-01-09 00:09:22.381 ThaliTest[1155:3649974] client session: disconnect
2016-01-09 00:09:22.381 ThaliTest[1155:3649974] client session: stateChange:2->0 1452294555306.1603.7eKM8g==
,2016-01-09 00:09:22.389 ThaliTest[1155:3649974] client session: fireConnectionErrorEvent: 1452294555306.1603.7eKM8g==
,2016-01-09 00:09:22.444 ThaliTest[1155:3650924] server session: not connected 1452294555306.1603
,calling stopBroadcasting
,2016-01-09 00:09:22.654 ThaliTest[1155:3650153] jxcore: stopBroadcasting
2016-01-09 00:09:22.655 ThaliTest[1155:3650153] THEMultipeerSession stopping peer
2016-01-09 00:09:22.655 ThaliTest[1155:3650153] multipeer session: stop timer
2016-01-09 00:09:22.,655 ThaliTest[1155:3650153] server session: disconnect
2016-01-09 00:09:22.656 ThaliTest[1155:3650153] server session: stateChange:2->0 1452294555306.1603
2016-01-09 00:09:22.659 ThaliTest[1155:3650153] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliReplicationManager can call start without error
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/E7615EA4-DEA8-431F-B5CB-7B5A0AFB6DF3/tmp/pouchdb"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,",failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,ok 99 starting event should occur in right order
,2016-01-09 00:09:25.110 ThaliTest[1155:3650153] jxcore: startBroadcasting
,2016-01-09 00:09:25.112 ThaliTest[1155:3650153] server: starting AofNqcsByqNzwLLFMwKN0Q.xSAVrw==
2016-01-09 00:09:25.112 ThaliTest[1155:3650153] multipeer session: start timer: 0x1afeee30
2016-01-09 00:09:25.113 ThaliTest[1155:3650153] THEMultipeerSessio,n initialized peer AofNqcsByqNzwLLFMwKN0Q
2016-01-09 00:09:25.113 ThaliTest[1155:3650153] jxcore: startBroadcasting: success
ok 100 started event should occur in right order
Now in TRM stop
State of this._isStarted: true
ok 101 stopping event should o,ccur in right order
About to call stopBroadcasting
2016-01-09 00:09:25.116 ThaliTest[1155:3650153] jxcore: stopBroadcasting
2016-01-09 00:09:25.116 ThaliTest[1155:3650153] THEMultipeerSession stopping peer
2016-01-09 00:09:25.116 ThaliTest[1155:3650153,] multipeer session: stop timer
2016-01-09 00:09:25.117 ThaliTest[1155:3650153] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined
ok 102 stopped event should occur in right order
,mux server bridge listener closed
# setup
,# ThaliReplicationManager receives identity
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/E7615EA4-DEA8-431F-B5CB-7B5A0AFB6DF3/tmp/pouchdb"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,2016-01-09 00:09:26.842 ThaliTest[1155:3650153] jxcore: startBroadcasting
,2016-01-09 00:09:26.845 ThaliTest[1155:3650153] server: starting AofNqcsByqNzwLLFMwKN0Q.nga14w==
2016-01-09 00:09:26.845 ThaliTest[1155:3650153] multipeer session: start timer: 0x1abc2dd0
,2016-01-09 00:09:26.845 ThaliTest[1155:3650153] THEMultipeerSession initialized peer AofNqcsByqNzwLLFMwKN0Q
2016-01-09 00:09:26.848 ThaliTest[1155:3650153] jxcore: startBroadcasting: success
ok 103 getDeviceIdentity should not return an error
ok 104 dev,iceName should not be null
Now in TRM stop
State of this._isStarted: true
About to call stopBroadcasting
2016-01-09 00:09:26.851 ThaliTest[1155:3650153] jxcore: stopBroadcasting
2016-01-09 00:09:26.851 ThaliTest[1155:3650153] THEMultipeerSession stopp,ing peer
2016-01-09 00:09:26.851 ThaliTest[1155:3650153] multipeer session: stop timer
2016-01-09 00:09:26.852 ThaliTest[1155:3650153] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined
,mux server bridge listener closed
Tests Complete
,Total: 0	Passed: 0	Failed: 0
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
