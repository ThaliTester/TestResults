#### Test 558877588826def_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/558877588826def/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/118E8478-C05D-4A69-903F-091ACF234CCC/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/118E8478-C05D-4A69-903F-091ACF234CCC/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/558877588826def/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/558877588826def/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54680"
,(lldb)     command script import "/tmp/118E8478-C05D-4A69-903F-091ACF234CCC/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-13 13:35:30.514 ThaliTest[1861:3946631] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4DBCDB95-66C1-4B36-A99C-FA8B34596609/Library/Cookies/Cookies.binarycookies
,2016-01-13 13:35:30.754 ThaliTest[1861:3946631] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-13 13:35:30.755 ThaliTest[1861:3946631] Multi-tasking -> Device: YES, App: YES
,2016-01-13 13:35:30.762 ThaliTest[1861:3946631] Unlimited access to network resources
,2016-01-13 13:35:30.770 ThaliTest[1861:3946631] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-13 13:35:34.978 ThaliTest[1861:3946631] Resetting plugins due to page load.
,2016-01-13 13:35:36.485 ThaliTest[1861:3946631] Finished load of: file:///var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/index.html
,2016-01-13 13:35:36.653 ThaliTest[1861:3946631] JXcore Cordova plugin initializing
,2016-01-13 13:35:36.654 ThaliTest[1861:3946812] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
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
# setup
,# basic
,# teardown
,ok 2 sane
# setup
,# another
,# teardown
,ok 3 sane
# setup
,# successfully create a new pkcs12 file and return hash value
,# teardown
,ok 4 should be equal
,ok 5 null
ok 6 (unnamed assert)
ok 7 should be equal
,ok 8 should not throw
# setup
,# successfully read a previous pkcs12 file and return hash value
,# teardown
,ok 9 (unnamed assert)
,ok 10 (unnamed assert)
ok 11 should not throw
,ok 12 should be equal
,ok 13 should be equal
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
ok 17 should be equal
ok 18 should be equal
# setup
,# #init should register the networkChanged event
,# teardown
,ok 19 should be equal
,# setup
,# #startBroadcasting should throw on null device name
,# teardown
,ok 20 should throw
# setup
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
# setup
,# #startBroadcasting should throw on negative port
,# teardown
,ok 24 should throw
# setup
,# #startBroadcasting should throw on too large port
,# teardown
,ok 25 should throw
# setup
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
ok 33 should be equal
,# setup
,# #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
,# teardown
,ok 34 should be equal
ok 35 should be equal
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
,2016-01-13 13:41:19.574 ThaliTest[1861:3946812] jxcore: startBroadcasting
,2016-01-13 13:41:19.580 ThaliTest[1861:3946812] server: starting 1452688879574.1861.aC6HKQ==
2016-01-13 13:41:19.580 ThaliTest[1861:3946812] multipeer session: start timer: 0x16821140
,2016-01-13 13:41:19.581 ThaliTest[1861:3946812] THEMultipeerSession initialized peer 1452688879574.1861
2016-01-13 13:41:19.581 ThaliTest[1861:3946812] jxcore: startBroadcasting: success
,ok 45 Should be able to call startBroadcasting without error
2016-01-13 13:41:19.583 ThaliTest[1861:3946812] jxcore: stopBroadcasting
2016-01-13 13:41:19.583 ThaliTest[1861:3946812] THEMultipeerSession stopping peer
2016-01-13 13:41:19.583 ThaliTest[1861:3946812] multipeer session: stop timer
2016-01-13 13:41:19.583 ThaliTest[1861:3946812] jxcore: stopBroadcasting: success
ok 46 Should be able to call stopBroadcasting without error
2016-01-13 13:41:19.584 ThaliTest[1861:3946812] jxcore: startBroadcasting
,2016-01-13 13:41:19.588 ThaliTest[1861:3946812] server: starting 1452688879584.1861.EKBkMA==
2016-01-13 13:41:19.591 ThaliTest[1861:3946812] multipeer session: start timer: 0x16b17f70
2016-01-13 13:41:19.591 ThaliTest[1861:3946812] THEMultipeerSession in,itialized peer 1452688879584.1861
2016-01-13 13:41:19.591 ThaliTest[1861:3946812] jxcore: startBroadcasting: success
ok 47 Should be able to call startBroadcasting without error
2016-01-13 13:41:19.592 ThaliTest[1861:3946812] jxcore: stopBroadcasting
,2016-01-13 13:41:19.592 ThaliTest[1861:3946812] THEMultipeerSession stopping peer
2016-01-13 13:41:19.594 ThaliTest[1861:3946812] multipeer session: stop timer
2016-01-13 13:41:19.594 ThaliTest[1861:3946812] jxcore: stopBroadcasting: success
ok 48 Should be able to call stopBroadcasting without error
2016-01-13 13:41:19.595 ThaliTest[1861:3946812] jxcore: startBroadcasting
,2016-01-13 13:41:19.598 ThaliTest[1861:3946812] server: starting 1452688879594.1861.2hl2wA==
2016-01-13 13:41:19.598 ThaliTest[1861:3946812] multipeer session: start timer: 0x155d5dc0
2016-01-13 13:41:19.598 ThaliTest[1861:3946812] THEMultipeerSession in,itialized peer 1452688879594.1861
2016-01-13 13:41:19.598 ThaliTest[1861:3946812] jxcore: startBroadcasting: success
ok 49 Should be able to call startBroadcasting without error
,2016-01-13 13:41:19.599 ThaliTest[1861:3946812] jxcore: stopBroadcasting
,2016-01-13 13:41:19.599 ThaliTest[1861:3946812] THEMultipeerSession stopping peer
2016-01-13 13:41:19.601 ThaliTest[1861:3946812] multipeer session: stop timer
2016-01-13 13:41:19.601 ThaliTest[1861:3946812] jxcore: stopBroadcasting: success
ok 50 Should be able to call stopBroadcasting without error
2016-01-13 13:41:19.602 ThaliTest[1861:3946812] jxcore: startBroadcasting
,2016-01-13 13:41:19.604 ThaliTest[1861:3946812] server: starting 1452688879601.1861.0J30GA==
2016-01-13 13:41:19.604 ThaliTest[1861:3946812] multipeer session: start timer: 0x1698b750
2016-01-13 13:41:19.604 ThaliTest[1861:3946812] THEMultipeerSession initialized peer 1452688879601.1861
,2016-01-13 13:41:19.604 ThaliTest[1861:3946812] jxcore: startBroadcasting: success
ok 51 Should be able to call startBroadcasting without error
2016-01-13 13:41:19.606 ThaliTest[1861:3946812] jxcore: stopBroadcasting
2016-01-13 13:41:19.606 ThaliTest[18,61:3946812] THEMultipeerSession stopping peer
2016-01-13 13:41:19.606 ThaliTest[1861:3946812] multipeer session: stop timer
2016-01-13 13:41:19.606 ThaliTest[1861:3946812] jxcore: stopBroadcasting: success
ok 52 Should be able to call stopBroadcasting without error
2016-01-13 13:41:19.607 ThaliTest[1861:3946812] jxcore: startBroadcasting
,2016-01-13 13:41:19.609 ThaliTest[1861:3946812] server: starting 1452688879607.1861.6AfzhQ==
2016-01-13 13:41:19.611 ThaliTest[1861:3946812] multipeer session: start timer: 0x16892d90
2016-01-13 13:41:19.612 ThaliTest[1861:3946812] THEMultipeerSession initialized peer 1452688879607.1861
2016-01-13 13:41:19.612 ThaliTest[1861:3946812] jxcore: startBroadcasting: success
ok 53 Should be able to call startBroadcasting without error
2016-01-13 13:41:19.612 ThaliTest[1861:3946812] jxcore: stopBroadcasting
2,016-01-13 13:41:19.613 ThaliTest[1861:3946812] THEMultipeerSession stopping peer
2016-01-13 13:41:19.613 ThaliTest[1861:3946812] multipeer session: stop timer
2016-01-13 13:41:19.613 ThaliTest[1861:3946812] jxcore: stopBroadcasting: success
ok 54 Should, be able to call stopBroadcasting without error
2016-01-13 13:41:19.613 ThaliTest[1861:3946812] jxcore: startBroadcasting
,2016-01-13 13:41:19.619 ThaliTest[1861:3946812] server: starting 1452688879613.1861.Ao8CEg==
2016-01-13 13:41:19.619 ThaliTest[1861:3946812] multipeer session: start timer: 0x16b35fa0
2016-01-13 13:41:19.619 ThaliTest[1861:3946812] THEMultipeerSession in,itialized peer 1452688879613.1861
2016-01-13 13:41:19.619 ThaliTest[1861:3946812] jxcore: startBroadcasting: success
ok 55 Should be able to call startBroadcasting without error
2016-01-13 13:41:19.620 ThaliTest[1861:3946812] jxcore: stopBroadcasting
2016-01-13 13:41:19.620 ThaliTest[1861:3946812] THEMultipeerSession stopping peer
2016-01-13 13:41:19.620 ThaliTest[1861:3946812] multipeer session: stop timer
2016-01-13 13:41:19.620 ThaliTest[1861:3946812] jxcore: stopBroadcasting: success
ok 56 Should be able to call stopBroadcasting without error
,2016-01-13 13:41:19.621 ThaliTest[1861:3946812] jxcore: startBroadcasting
,2016-01-13 13:41:19.629 ThaliTest[1861:3946812] server: starting 1452688879621.1861.Dz8pRg==
2016-01-13 13:41:19.629 ThaliTest[1861:3946812] multipeer session: start timer: 0x155ce8b0
2016-01-13 13:41:19.629 ThaliTest[1861:3946812] THEMultipeerSession initialized peer 1452688879621.1861
2016-01-13 13:41:19.629 ThaliTest[1861:3946812] jxcore: startBroadcasting: success
ok 57 Should be able to call startBroadcasting without error
,2016-01-13 13:41:19.630 ThaliTest[1861:3946812] jxcore: stopBroadcasting
2016-01-13 13:41:19.631 ThaliTest[1861:3946812] THEMultipeerSession stopping peer
2016-01-13 13:41:19.631 ThaliTest[1861:3946812] multipeer session: stop timer
2016-01-13 13:41:19.,631 ThaliTest[1861:3946812] jxcore: stopBroadcasting: success
ok 58 Should be able to call stopBroadcasting without error
2016-01-13 13:41:19.632 ThaliTest[1861:3946812] jxcore: startBroadcasting
,2016-01-13 13:41:19.635 ThaliTest[1861:3946812] server: starting 1452688879631.1861.0jcV5w==
,2016-01-13 13:41:19.637 ThaliTest[1861:3946812] multipeer session: start timer: 0x16b992e0
2016-01-13 13:41:19.637 ThaliTest[1861:3946812] THEMultipeerSession initialized peer 1452688879631.1861
2016-01-13 13:41:19.637 ThaliTest[1861:3946812] jxcore: startBroadcasting: success
,ok 59 Should be able to call startBroadcasting without error
2016-01-13 13:41:19.639 ThaliTest[1861:3946812] jxcore: stopBroadcasting
2016-01-13 13:41:19.639 ThaliTest[1861:3946812] THEMultipeerSession stopping peer
2016-01-13 13:41:19.640 ThaliTest[1861:3946812] multipeer session: stop timer
2016-01-13 13:41:19.640 ThaliTest[1861:3946812] jxcore: stopBroadcasting: success
,ok 60 Should be able to call stopBroadcasting without error
2016-01-13 13:41:19.642 ThaliTest[1861:3946812] jxcore: startBroadcasting
,2016-01-13 13:41:19.644 ThaliTest[1861:3946812] server: starting 1452688879642.1861.764KXg==
2016-01-13 13:41:19.645 ThaliTest[1861:3946812] multipeer session: start timer: 0x16810230
2016-01-13 13:41:19.645 ThaliTest[1861:3946812] THEMultipeerSession initialized peer 1452688879642.1861
2016-01-13 13:41:19.645 ThaliTest[1861:3946812] jxcore: startBroadcasting: success
ok 61 Should be able to call startBroadcasting without error
2016-01-13 13:41:19.646 ThaliTest[1861:3946812] jxcore: stopBroadcasting
2,016-01-13 13:41:19.646 ThaliTest[1861:3946812] THEMultipeerSession stopping peer
2016-01-13 13:41:19.646 ThaliTest[1861:3946812] multipeer session: stop timer
2016-01-13 13:41:19.646 ThaliTest[1861:3946812] jxcore: stopBroadcasting: success
ok 62 Should, be able to call stopBroadcasting without error
2016-01-13 13:41:19.647 ThaliTest[1861:3946812] jxcore: startBroadcasting
,2016-01-13 13:41:19.650 ThaliTest[1861:3946812] server: starting 1452688879647.1861.1tHRTw==
2016-01-13 13:41:19.650 ThaliTest[1861:3946812] multipeer session: start timer: 0x1684d8f0
2016-01-13 13:41:19.650 ThaliTest[1861:3946812] THEMultipeerSession in,itialized peer 1452688879647.1861
2016-01-13 13:41:19.651 ThaliTest[1861:3946812] jxcore: startBroadcasting: success
ok 63 Should be able to call startBroadcasting without error
2016-01-13 13:41:19.652 ThaliTest[1861:3946812] jxcore: stopBroadcasting
2016-01-13 13:41:19.652 ThaliTest[1861:3946812] THEMultipeerSession stopping peer
2016-01-13 13:41:19.652 ThaliTest[1861:3946812] multipeer session: stop timer
2016-01-13 13:41:19.652 ThaliTest[1861:3946812] jxcore: stopBroadcasting: success
ok 64 Should be able to call stopBroadcasting without error
# setup
,# ThaliEmitter calls startBroadcasting twice with error
,# teardown
,2016-01-13 13:41:19.911 ThaliTest[1861:3946812] jxcore: startBroadcasting
,2016-01-13 13:41:19.912 ThaliTest[1861:3946812] server: starting 1452688879911.1861.o86Psw==
2016-01-13 13:41:19.912 ThaliTest[1861:3946812] multipeer session: start timer: 0x155d94f0
2016-01-13 13:41:19.912 ThaliTest[1861:3946812] THEMultipeerSession initialized peer 1452688879911.1861
,2016-01-13 13:41:19.914 ThaliTest[1861:3946812] jxcore: startBroadcasting: success
ok 65 Should be able to call startBroadcasting without error
2016-01-13 13:41:19.915 ThaliTest[1861:3946812] jxcore: startBroadcasting
2016-01-13 13:41:19.915 ThaliTest[1861:3946812] jxcore: startBroadcasting: failure
ok 66 Cannot call startBroadcasting twice
2016-01-13 13:41:19.916 ThaliTest[1861:3946812] jxcore: stopBroadcasting
2016-01-13 13:41:19.916 ThaliTest[1861:3946812] THEMultipeerSession stopping peer
,2016-01-13 13:41:19.916 ThaliTest[1861:3946812] multipeer session: stop timer
2016-01-13 13:41:19.917 ThaliTest[1861:3946812] jxcore: stopBroadcasting: success
ok 67 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on connection to bad peer
,# teardown
,2016-01-13 13:41:19.984 ThaliTest[1861:3946812] jxcore: startBroadcasting
,2016-01-13 13:41:19.985 ThaliTest[1861:3946812] server: starting 1452688879983.1861.AXSETA==
2016-01-13 13:41:19.985 ThaliTest[1861:3946812] multipeer session: start timer: 0x16cdfe50
2016-01-13 13:41:19.985 ThaliTest[1861:3946812] THEMultipeerSession in,itialized peer 1452688879983.1861
2016-01-13 13:41:19.985 ThaliTest[1861:3946812] jxcore: startBroadcasting: success
ok 68 Should be able to call startBroadcasting without error
2016-01-13 13:41:19.986 ThaliTest[1861:3946812] jxcore: connect foobar
2016-01-13 13:41:19.986 ThaliTest[1861:3946812] client: unknown peer foobar
2016-01-13 13:41:19.987 ThaliTest[1861:3946812] jxcore: connect: fail: Unknown peer
,ok 69 Should not connect to a bad peer
2016-01-13 13:41:19.988 ThaliTest[1861:3946812] jxcore: stopBroadcasting
2016-01-13 13:41:19.988 ThaliTest[1861:3946812] THEMultipeerSession stopping peer
2016-01-13 13:41:19.988 ThaliTest[1861:3946812] multipeer session: stop timer
2016-01-13 13:41:19.988 ThaliTest[1861:3946812] jxcore: stopBroadcasting: success
ok 70 Should be able to call stopBroadcasting without error
# setup
,# ThaliEmitter throws on disconnect to bad peer
,# teardown
,2016-01-13 13:41:20.364 ThaliTest[1861:3946812] jxcore: startBroadcasting
,2016-01-13 13:41:20.366 ThaliTest[1861:3946812] server: starting 1452688880364.1861.gEBthg==
2016-01-13 13:41:20.366 ThaliTest[1861:3946812] multipeer session: start timer: 0x16f97ba0
2016-01-13 13:41:20.366 ThaliTest[1861:3946812] THEMultipeerSession in,itialized peer 1452688880364.1861
2016-01-13 13:41:20.367 ThaliTest[1861:3946812] jxcore: startBroadcasting: success
ok 71 Should be able to call startBroadcasting without error
2016-01-13 13:41:20.367 ThaliTest[1861:3946812] jxcore: disconnect
2016-01,-13 13:41:20.367 ThaliTest[1861:3946812] jxcore: disconnect: fail
ok 72 Disconnect should fail to a non-existant peer 
,2016-01-13 13:41:20.368 ThaliTest[1861:3946812] jxcore: stopBroadcasting
2016-01-13 13:41:20.371 ThaliTest[1861:3946812] THEMultipeerSession stopping peer
2016-01-13 13:41:20.371 ThaliTest[1861:3946812] multipeer session: stop timer
2016-01-13 13:41:20.371 ThaliTest[1861:3946812] jxcore: stopBroadcasting: success
ok 73 Should be able to call stopBroadcasting without error
# setup
,# ThaliEmitter can discover and connect to peers
,# teardown
,2016-01-13 13:41:20.454 ThaliTest[1861:3946812] jxcore: startBroadcasting
,2016-01-13 13:41:20.456 ThaliTest[1861:3946812] server: starting 1452688880454.1861.e0r2aw==
2016-01-13 13:41:20.456 ThaliTest[1861:3946812] multipeer session: start timer: 0x156e57e0
2016-01-13 13:41:20.456 ThaliTest[1861:3946812] THEMultipeerSession in,itialized peer 1452688880454.1861
2016-01-13 13:41:20.457 ThaliTest[1861:3946812] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error
,2016-01-13 13:41:21.337 ThaliTest[1861:3946631] client: found peer: 1452688880414.1331.qzx3AA==
2016-01-13 13:41:21.338 ThaliTest[1861:3946812] jxcore: connect 1452688880414.1331.qzx3AA==
2016-01-13 13:41:21.338 ThaliTest[1861:3946812] client session: connect
2016-01-13 13:41:21.338 ThaliTest[1861:3946812] client session: stateChange:0->1 1452688880414.1331.qzx3AA==
,2016-01-13 13:41:21.859 ThaliTest[1861:3946631] multipeer session: reset timer
2016-01-13 13:41:21.859 ThaliTest[1861:3946631] multipeer session: stop timer
2016-01-13 13:41:21.860 ThaliTest[1861:3946631] multipeer session: start timer: 0x156e57e0
2016-01-13 13:41:21.860 ThaliTest[1861:3946631] server session: connect
2016-01-13 13:41:21.860 ThaliTest[1861:3946631] server session: stateChange:0->1 1452688880414.1331
,2016-01-13 13:41:21.863 ThaliTest[1861:3946631] server: accepting invitation 1452688880414.1331
,2016-01-13 13:41:24.411 ThaliTest[1861:3947397] server session: connected
2016-01-13 13:41:24.411 ThaliTest[1861:3947397] server session: stateChange:1->2 1452688880414.1331
,2016-01-13 13:41:24.475 ThaliTest[1861:3947396] server session: not connected 1452688880414.1331
,2016-01-13 13:41:24.476 ThaliTest[1861:3946631] server relay: socket disconnected
2016-01-13 13:41:24.476 ThaliTest[1861:3946631] server relay: 0x16b818c0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-13 13:41:24.607 ThaliTest[1861:3947392] client session: connected
2016-01-13 13:41:24.607 ThaliTest[1861:3947392] client session: stateChange:1->2 1452688880414.1331.qzx3AA==
,2016-01-13 13:41:24.617 ThaliTest[1861:3947397] client session: fireConnectCallback: 1452688880414.1331.qzx3AA==
2016-01-13 13:41:24.617 ThaliTest[1861:3947397] jxcore: connect: success
ok 75 Should be able to connect without error
,ok 76 Port should be within range
,2016-01-13 13:41:24.619 ThaliTest[1861:3946812] jxcore: disconnect
2016-01-13 13:41:24.619 ThaliTest[1861:3946812] client session: disconnectFromPeer: 1452688880414.1331.qzx3AA==
2016-01-13 13:41:24.619 ThaliTest[1861:3946812] client session: disconnect,
2016-01-13 13:41:24.619 ThaliTest[1861:3946812] client session: stateChange:2->0 1452688880414.1331.qzx3AA==
,2016-01-13 13:41:24.622 ThaliTest[1861:3946812] jxcore: disconnect: success
ok 77 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
,2016-01-13 13:41:27.952 ThaliTest[1861:3946812] jxcore: stopBroadcasting
2016-01-13 13:41:27.952 ThaliTest[1861:3946812] THEMultipeerSession stopping peer
2016-01-13 13:41:27.952 ThaliTest[1861:3946812] multipeer session: stop timer
2016-01-13 13:41:27.952 ThaliTest[1861:3946812] server session: disconnect
2016-01-13 13:41:27.952 ThaliTest[1861:3946812] server session: stateChange:2->0 1452688880414.1331
2016-01-13 13:41:27.953 ThaliTest[1861:3946812] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter can discover and connect to peers and then fail on double connect
,# teardown
,2016-01-13 13:41:45.649 ThaliTest[1861:3946812] jxcore: startBroadcasting
,2016-01-13 13:41:45.650 ThaliTest[1861:3946812] server: starting 1452688905648.1861.kf6ylw==
2016-01-13 13:41:45.651 ThaliTest[1861:3946812] multipeer session: start timer: 0x1689a0d0
2016-01-13 13:41:45.651 ThaliTest[1861:3946812] THEMultipeerSession initialized peer 1452688905648.1861
2016-01-13 13:41:45.651 ThaliTest[1861:3946812] jxcore: startBroadcasting: success
ok 78 Should be able to call startBroadcasting without error
,2016-01-13 13:41:45.661 ThaliTest[1861:3946631] client: found peer: 1452688899381.1331./bap5Q==
2016-01-13 13:41:45.662 ThaliTest[1861:3946812] jxcore: connect 1452688899381.1331./bap5Q==
2016-01-13 13:41:45.662 ThaliTest[1861:3946812] client session: connect
2016-01-13 13:41:45.662 ThaliTest[1861:3946812] client session: stateChange:0->1 1452688899381.1331./bap5Q==
,2016-01-13 13:41:46.951 ThaliTest[1861:3946631] multipeer session: reset timer
2016-01-13 13:41:46.951 ThaliTest[1861:3946631] multipeer session: stop timer
2016-01-13 13:41:46.951 ThaliTest[1861:3946631] multipeer session: start timer: 0x1689a0d0
2016-01-13 13:41:46.951 ThaliTest[1861:3946631] server session: connect
2016-01-13 13:41:46.951 ThaliTest[1861:3946631] server session: stateChange:0->1 1452688899381.1331
2016-01-13 13:41:46.954 ThaliTest[1861:3946631] server: accepting invitation 1452688899381.1331
,2016-01-13 13:41:48.460 ThaliTest[1861:3947478] client session: connected
2016-01-13 13:41:48.460 ThaliTest[1861:3947478] client session: stateChange:1->2 1452688899381.1331./bap5Q==
,2016-01-13 13:41:49.051 ThaliTest[1861:3947489] client session: fireConnectCallback: 1452688899381.1331./bap5Q==
2016-01-13 13:41:49.051 ThaliTest[1861:3947489] jxcore: connect: success
,ok 79 Should be able to connect without error
,ok 80 Port should be within range
,2016-01-13 13:41:49.053 ThaliTest[1861:3946812] jxcore: connect 1452688899381.1331./bap5Q==
2016-01-13 13:41:49.053 ThaliTest[1861:3946812] client: already connect(ing/ed) to 1452688899381.1331./bap5Q==
2016-01-13 13:41:49.053 ThaliTest[1861:3946812] jxcore: connect: fail: Aleady connecting
ok 81 Should fail on double connect
,2016-01-13 13:41:49.054 ThaliTest[1861:3946812] jxcore: disconnect
2016-01-13 13:41:49.054 ThaliTest[1861:3946812] client session: disconnectFromPeer: 1452688899381.1331./bap5Q==
2016-01-13 13:41:49.054 ThaliTest[1861:3946812] client session: disconnect
2016-01-13 13:41:49.055 ThaliTest[1861:3946812] client session: stateChange:2->0 1452688899381.1331./bap5Q==
,2016-01-13 13:41:49.112 ThaliTest[1861:3946812] jxcore: disconnect: success
,ok 82 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,2016-01-13 13:41:49.572 ThaliTest[1861:3947480] server session: connected
2016-01-13 13:41:49.572 ThaliTest[1861:3947480] server session: stateChange:1->2 1452688899381.1331
,2016-01-13 13:41:49.631 ThaliTest[1861:3946631] server relay: socket disconnected
,2016-01-13 13:41:49.631 ThaliTest[1861:3946631] server relay: 0x16a2c490 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-13 13:41:49.633 ThaliTest[1861:3947478] server session: not connected 1452688899381.1331
,2016-01-13 13:41:51.648 ThaliTest[1861:3946631] client: lost peer: 1452688899381.1331./bap5Q==
2016-01-13 13:41:51.648 ThaliTest[1861:3946631] client session: onPeerLost: 1452688899381.1331./bap5Q==
,2016-01-13 13:42:16.952 ThaliTest[1861:3946631] multipeer session: restart
,2016-01-13 13:42:46.952 ThaliTest[1861:3946631] multipeer session: restart
,calling stopBroadcasting
,2016-01-13 13:43:11.026 ThaliTest[1861:3946812] jxcore: stopBroadcasting
2016-01-13 13:43:11.026 ThaliTest[1861:3946812] THEMultipeerSession stopping peer
2016-01-13 13:43:11.026 ThaliTest[1861:3946812] multipeer session: stop timer
2016-01-13 13:43:11.,026 ThaliTest[1861:3946812] server session: disconnect
2016-01-13 13:43:11.026 ThaliTest[1861:3946812] server session: stateChange:2->0 1452688899381.1331
2016-01-13 13:43:11.027 ThaliTest[1861:3946812] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter can discover and connect to peers and then fail on double disconnect
,# teardown
,2016-01-13 13:43:15.902 ThaliTest[1861:3946812] jxcore: startBroadcasting
,2016-01-13 13:43:15.904 ThaliTest[1861:3946812] server: starting 1452688995902.1861.X0lQsw==
2016-01-13 13:43:15.905 ThaliTest[1861:3946812] multipeer session: start timer: 0x16e21f80
2016-01-13 13:43:15.905 ThaliTest[1861:3946812] THEMultipeerSession in,itialized peer 1452688995902.1861
2016-01-13 13:43:15.905 ThaliTest[1861:3946812] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error
,2016-01-13 13:43:33.474 ThaliTest[1861:3946631] client: found peer: 1452688996089.1331.OFrDkg==
2016-01-13 13:43:33.475 ThaliTest[1861:3946812] jxcore: connect 1452688996089.1331.OFrDkg==
2016-01-13 13:43:33.475 ThaliTest[1861:3946812] client session: connect
2016-01-13 13:43:33.475 ThaliTest[1861:3946812] client session: stateChange:0->1 1452688996089.1331.OFrDkg==
,2016-01-13 13:43:33.934 ThaliTest[1861:3946631] multipeer session: reset timer
2016-01-13 13:43:33.934 ThaliTest[1861:3946631] multipeer session: stop timer
2016-01-13 13:43:33.934 ThaliTest[1861:3946631] multipeer session: start timer: 0x16e21f80
2016-01-13 13:43:33.934 ThaliTest[1861:3946631] server session: connect
2016-01-13 13:43:33.934 ThaliTest[1861:3946631] server session: stateChange:0->1 1452688996089.1331
,2016-01-13 13:43:33.937 ThaliTest[1861:3946631] server: accepting invitation 1452688996089.1331
,2016-01-13 13:43:36.763 ThaliTest[1861:3947716] server session: connected
2016-01-13 13:43:36.763 ThaliTest[1861:3947716] server session: stateChange:1->2 1452688996089.1331
,2016-01-13 13:43:36.789 ThaliTest[1861:3946631] server relay: socket disconnected
2016-01-13 13:43:36.789 ThaliTest[1861:3946631] server relay: 0x16eb3e00 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-13 13:43:36.826 ThaliTest[1861:3947637] server session: not connected 1452688996089.1331
,2016-01-13 13:43:36.829 ThaliTest[1861:3947637] client session: connected
2016-01-13 13:43:36.829 ThaliTest[1861:3947637] client session: stateChange:1->2 1452688996089.1331.OFrDkg==
,2016-01-13 13:43:36.880 ThaliTest[1861:3947716] client session: fireConnectCallback: 1452688996089.1331.OFrDkg==
2016-01-13 13:43:36.880 ThaliTest[1861:3947716] jxcore: connect: success
ok 84 Should be able to connect without error
ok 85 Port should be within range
2016-01-13 13:43:36.882 ThaliTest[1861:3946812] jxcore: disconnect
,2016-01-13 13:43:36.882 ThaliTest[1861:3946812] client session: disconnectFromPeer: 1452688996089.1331.OFrDkg==
2016-01-13 13:43:36.883 ThaliTest[1861:3946812] client session: disconnect
2016-01-13 13:43:36.883 ThaliTest[1861:3946812] client session: stateChange:2->0 1452688996089.1331.OFrDkg==
,2016-01-13 13:43:36.952 ThaliTest[1861:3946812] jxcore: disconnect: success
ok 86 Should be able to disconnect without error
2016-01-13 13:43:36.953 ThaliTest[1861:3946812] jxcore: disconnect
2016-01-13 13:43:36.953 ThaliTest[1861:3946812] jxcore: disconnect: fail
ok 87 Disconnect should fail 
setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
,2016-01-13 13:43:37.029 ThaliTest[1861:3946812] jxcore: stopBroadcasting
2016-01-13 13:43:37.029 ThaliTest[1861:3946812] THEMultipeerSession stopping peer
2016-01-13 13:43:37.030 ThaliTest[1861:3946812] multipeer session: stop timer
2016-01-13 13:43:37.030 ThaliTest[1861:3946812] server session: disconnect
2016-01-13 13:43:37.030 ThaliTest[1861:3946812] server session: stateChange:2->0 1452688996089.1331
2016-01-13 13:43:37.030 ThaliTest[1861:3946812] jxcore: stopBroadcasting: success
,stopBroadcasting returned undefined
# ThaliEmitter can connect and send data
,# teardown
,2016-01-13 13:43:54.828 ThaliTest[1861:3946812] jxcore: startBroadcasting
,2016-01-13 13:43:54.835 ThaliTest[1861:3946812] server: starting 1452689034828.1861.+q8KNQ==
,2016-01-13 13:43:54.836 ThaliTest[1861:3946812] multipeer session: start timer: 0x168098e0
,2016-01-13 13:43:54.841 ThaliTest[1861:3946812] THEMultipeerSession initialized peer 1452689034828.1861
,2016-01-13 13:43:54.842 ThaliTest[1861:3946812] jxcore: startBroadcasting: success
,ok 88 Should be able to call startBroadcasting without error
,echo server started
,2016-01-13 13:43:56.671 ThaliTest[1861:3946631] multipeer session: reset timer
2016-01-13 13:43:56.671 ThaliTest[1861:3946631] multipeer session: stop timer
2016-01-13 13:43:56.671 ThaliTest[1861:3946631] multipeer session: start timer: 0x168098e0
,2016-01-13 13:43:56.671 ThaliTest[1861:3946631] server session: connect
2016-01-13 13:43:56.671 ThaliTest[1861:3946631] server session: stateChange:0->1 1452689035985.1331
,2016-01-13 13:43:56.675 ThaliTest[1861:3946631] server: accepting invitation 1452689035985.1331
,2016-01-13 13:43:57.002 ThaliTest[1861:3946631] client: found peer: 1452689035985.1331.AR1oLw==
2016-01-13 13:43:57.002 ThaliTest[1861:3946812] jxcore: connect 1452689035985.1331.AR1oLw==
2016-01-13 13:43:57.002 ThaliTest[1861:3946812] client session: connect
2016-01-13 13:43:57.002 ThaliTest[1861:3946812] client session: stateChange:0->1 1452689035985.1331.AR1oLw==
,2016-01-13 13:43:59.231 ThaliTest[1861:3947766] server session: connected
2016-01-13 13:43:59.231 ThaliTest[1861:3947766] server session: stateChange:1->2 1452689035985.1331
,2016-01-13 13:43:59.258 ThaliTest[1861:3946631] server relay: connected (to port: 5001)
,2016-01-13 13:43:59.817 ThaliTest[1861:3947779] server session: not connected 1452689035985.1331
,2016-01-13 13:43:59.823 ThaliTest[1861:3947779] client session: connected
2016-01-13 13:43:59.823 ThaliTest[1861:3947779] client session: stateChange:1->2 1452689035985.1331.AR1oLw==
,2016-01-13 13:43:59.881 ThaliTest[1861:3947779] client session: fireConnectCallback: 1452689035985.1331.AR1oLw==
2016-01-13 13:43:59.881 ThaliTest[1861:3947779] jxcore: connect: success
,ok 89 Should be able to connect without error
,ok 90 Port should be within range
,2016-01-13 13:43:59.884 ThaliTest[1861:3946631] client: relay established
2016-01-13 13:43:59.884 ThaliTest[1861:3946631] client: new accepted socket: 0x156e59e0
,data in 1095
,data in 12998
,data in 37088
,data in 49133
,data in 72270
,data in 77674
,data in 83220
,data in 88695
,data in 108334
,data in 131072
,ok 91 the test messages should be equal
,2016-01-13 13:44:00.358 ThaliTest[1861:3946812] jxcore: disconnect
2016-01-13 13:44:00.358 ThaliTest[1861:3946812] client session: disconnectFromPeer: 1452689035985.1331.AR1oLw==
2016-01-13 13:44:00.358 ThaliTest[1861:3946812] client session: disconnect
2016-01-13 13:44:00.358 ThaliTest[1861:3946812] client session: stateChange:2->0 1452689035985.1331.AR1oLw==
,2016-01-13 13:44:00.362 ThaliTest[1861:3946812] jxcore: disconnect: success
ok 92 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
,2016-01-13 13:44:01.080 ThaliTest[1861:3946812] jxcore: stopBroadcasting
2016-01-13 13:44:01.080 ThaliTest[1861:3946812] THEMultipeerSession stopping peer
2016-01-13 13:44:01.080 ThaliTest[1861:3946812] multipeer session: stop timer
2016-01-13 13:44:01.,080 ThaliTest[1861:3946812] server session: disconnect
2016-01-13 13:44:01.080 ThaliTest[1861:3946812] server session: stateChange:2->0 1452689035985.1331
,2016-01-13 13:44:01.084 ThaliTest[1861:3946812] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliEmitter handles socket disconnect correctly
,# teardown
,2016-01-13 13:44:29.578 ThaliTest[1861:3946812] jxcore: startBroadcasting
,2016-01-13 13:44:29.580 ThaliTest[1861:3946812] server: starting 1452689069578.1861.y3V4kQ==
2016-01-13 13:44:29.580 ThaliTest[1861:3946812] multipeer session: start timer: 0x15582400
2016-01-13 13:44:29.580 ThaliTest[1861:3946812] THEMultipeerSession initialized peer 1452689069578.1861
2016-01-13 13:44:29.581 ThaliTest[1861:3946812] jxcore: startBroadcasting: success
ok 93 Should be able to call startBroadcasting without error
2016-01-13 13:44:29.582 ThaliTest[1861:3946812] Error!: listen EADDRINUSE
,Stack:[{"_fileName":"net.js","_functionName":"errnoException","_lineNumber":"835","_columnNumber":"11","_msg":"    at errnoException@net.js:835:11"},{"_fileName":"net.js","_functionName":"Server.prototype._listen2","_lineNumber":"974","_columnNumber":"14",,"_msg":"    at Server.prototype._listen2@net.js:974:14"},{"_fileName":"net.js","_functionName":"listen","_lineNumber":"995","_columnNumber":"5","_msg":"    at listen@net.js:995:5"},{"_fileName":"net.js","_functionName":"Server.prototype.listen","_lineNumbe,r":"1068","_columnNumber":"5","_msg":"    at Server.prototype.listen@net.js:1068:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js","_functionN,ame":"","_lineNumber":"241","_columnNumber":"3","_msg":"    at @/private/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js:241:3"},{"_fileName":"/private/var/mobile/Conta,iners/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/lib/thali-tape.js","_functionName":"declareTest/</<","_lineNumber":"78","_columnNumber":"7","_msg":"    at declareTest/</<@/private/var/mobile/Containers/Bundle/Applicat,ion/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/lib/thali-tape.js:78:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modu,les/component-emitter/index.js","_functionName":"on","_lineNumber":"63","_columnNumber":"5","_msg":"    at on@/private/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node,_modules/component-emitter/index.js:63:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_module,s/component-emitter/index.js:131:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onevent","_lin,eNumber":"263","_columnNumber":"5","_msg":"    at Socket.prototype.onevent@/private/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:263:5"},{"_fileName":"/pr,ivate/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onpacket","_lineNumber":"221","_columnNumber":"7","_msg":"    at Soc,ket.prototype.onpacket@/private/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:221:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/88AE8,B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/private/var/mobile/Con,tainers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB19,2743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/B,undle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0,CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.ondecoded","_lineNumber":"333","_columnNumber":"3","_msg":"    at Manager.prototype.ondecoded@/private/var/mobile/Containers/Bundle/Application/88A,E8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:333:3"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socke,t.io-client/node_modules/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/private/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.ap,p/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules,/socket.io-parser/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB19,2743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app,/www/jxcore/node_modules/socket.io-client/node_modules/socket.io-parser/index.js","_functionName":"Decoder.prototype.add","_lineNumber":"247","_columnNumber":"7","_msg":"    at Decoder.prototype.add@/private/var/mobile/Containers/Bundle/Application/88AE8B2,A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/socket.io-parser/index.js:247:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.ondata","_lineNumber":"323","_columnNumber":"3","_msg":"    at Manager.prototype.ondata@/private/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0C,D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:323:3"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/compone,nt-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/private/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket,.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/node_modules/c,omponent-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcor,e/node_modules/socket.io-client/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.,io-client/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onPacket","_lineNumber":"441","_columnNumber":"9","_msg":"    at Socket.prototype.onPacket@/private/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB,192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/socket.js:441:9"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules,/socket.io-client/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.setTransport/<","_lineNumber":"258","_columnNumber":"5","_msg":"    at Socket.prototype.setTransport/<@/private/var/mobile/Containers/Bundle/Application/88AE8B,2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/socket.js:258:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www,/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containe,rs/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/,88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/transport.js","_functionName":"Transport.prototype.onPacket","_lineNumber":"143","_columnNumber":"3","_msg":"    at Transport.prot,otype.onPacket@/private/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/transport.js:143:3"},{"_fileName":"/private/var/mobile/Containers,/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/transport.js","_functionName":"Transport.prototype.onData","_lineNumber":"135","_columnNumber":"3","_msg":"   , at Transport.prototype.onData@/private/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/transport.js:135:3"},{"_fileName":"/private/var/m,obile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/transports/websocket.js","_functionName":"WS.prototype.addEventListeners/this.ws.onmessage",,"_lineNumber":"127","_columnNumber":"5","_msg":"    at WS.prototype.addEventListeners/this.ws.onmessage@/private/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/transports/websocket.js:127:5"}]
Uncaught Exception: Error: listen EADDRINUSE
,[ { _fileName: 'net.js',
    _functionName: 'errnoException',
    _lineNumber: '835',
    _columnNumber: '11',
    _msg: '    at errnoException@net.js:835:11' },
  { _fileName: 'net.js',
    _functionName: 'Server.prototype._listen2',
    _lineNumbe,r: '974',
    _columnNumber: '14',
    _msg: '    at Server.prototype._listen2@net.js:974:14' },
  { _fileName: 'net.js',
    _functionName: 'listen',
    _lineNumber: '995',
    _columnNumber: '5',
    _msg: '    at listen@net.js:995:5' },
  { _fileName: 'net.js',
    _functionName: 'Server.prototype.listen',
    _lineNumber: '1068',
    _columnNumber: '5',
    _msg: '    at Server.prototype.listen@net.js:1068:5' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF,3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js',
    _functionName: '',
    _lineNumber: '241',
    _columnNumber: '3',
    _msg: '    at @/private/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB1,92743F0CD/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js:241:3' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/lib/thali-tape.js',
    _functionName: 'declareT,est/</<',
    _lineNumber: '78',
    _columnNumber: '7',
    _msg: '    at declareTest/</<@/private/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/lib/thali-tape.js:78:7' },
  { _fileName: '/priva,te/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js',
    _functionName: 'on',
    _lineNumber: '63',
    _columnNumber: '5',
  ,  _msg: '    at on@/private/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:63:5' },
  { _fileName: '/private/var/mobile/Containe,r,s/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js',
    _functionName: 'Emitter.prototype.emit',
    _lineNumber: '131',
    _columnNumber: '7',
    ,_msg: '    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:131:7' },
  { _fileName: '/private/v,ar/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js',
    _functionName: 'Socket.prototype.onevent',
    _lineNumber: '263',
    _columnNumber: '5',
    _msg:, '    at Socket.prototype.onevent@/private/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:263:5' },
  { _fileName: '/private/var/mobile/Containers/Bundle/A,pplication/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js',
    _functionName: 'Socket.prototype.onpacket',
    _lineNumber: '221',
    _columnNumber: '7',
    _msg: '    at Socket.prototype.on,packet@/private/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:221:7' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B,89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js',
    _functionName: 'module.exports/<',
    _lineNumber: '21',
    _columnNumber: '12',
    _msg: '    at module.exports/<@/private/var/mo,bile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4,B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js',
    _functionName: 'Emitter.prototype.emit',
    _lineNumber: '131',
    _columnNumber: '7',
    _msg: '    at Emitter.prototype.emit,@/private/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:131:7' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Applicat,ion/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js',
    _functionName: 'Manager.prototype.ondecoded',
    _lineNumber: '333',
    _columnNumber: '3',
    _msg: '    at Manager.prototype.ondec,oded@/private/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:333:3' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B8,9-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js',
    _functionName: 'module.exports/<',
    _lineNumber: '21',
    _columnNumber: '12',
    _msg: '    at module.exports/<@/private/var/mob,ile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B,89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/socket.io-parser/node_modules/component-emitter/index.js',
    _functionName: 'Emitter.prototype.emit',
    _lineNumber: '134',
    _columnNumber: '7',
    _msg: ',    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:7' },
  {, _fileName: '/private/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/socket.io-parser/index.js',
    _functionName: 'Decoder.prototype.add',
    _lineNumbe,r: '247',
    _columnNumber: '7',
    _msg: '    at Decoder.prototype.add@/private/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/socket.io-parser/index.js,:247:7' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js',
    _functionName: 'Manager.prototype.ondata',
    _lineNumber: '32,3',
    _columnNumber: '3',
    _msg: '    at Manager.prototype.ondata@/private/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:323:3' },
  { _fileName: ,'/private/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js',
    _functionName: 'module.exports/<',
    _lineNumber: '21',
    _colu,mnNumber: '12',
    _msg: '    at module.exports/<@/private/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12' },
  { _fileName:, '/private/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/node_modules/component-emitter/index.js',
    _functionName: 'Emitter.prototype.e,mit',
    _lineNumber: '134',
    _columnNumber: '7',
    _msg: '    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/eng,ine.io-client/node_modules/component-emitter/index.js:134:7' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib,/socket.js',
    _functionName: 'Socket.prototype.onPacket',
    _lineNumber: '441',
    _columnNumber: '9',
    _msg: '    at Socket.prototype.onPacket@/private/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.ap,p/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/socket.js:441:9' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/,node_modules/engine.io-client/lib/socket.js',
    _functionName: 'Socket.prototype.setTransport/<',
    _lineNumber: '258',
    _columnNumber: '5',
    _msg: '    at Socket.prototype.setTransport/<@/private/var/mobile/Containers/Bundle/Application/88AE,8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/socket.js:258:5' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.,app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/node_modules/component-emitter/index.js',
    _functionName: 'Emitter.prototype.emit',
    _lineNumber: '134',
    _columnNumber: '7',
    _msg: '    at Emitter.prototype.emit@/,private/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7' },
  { _fileName: '/private/var/mobil,e/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/transport.js',
    _functionName: 'Transport.prototype.onPacket',
    _lineNumber: '143',
    _,columnNumber: '3',
    _msg: '    at Transport.prototype.onPacket@/private/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/transport.js:,143:3' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/transport.js',
    _functionName: 'Transport.prototy,pe.onData',
    _lineNumber: '135',
    _columnNumber: '3',
    _msg: '    at Transport.prototype.onData@/private/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_m,odules/engine.io-client/lib/transport.js:135:3' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/88AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/transports/,websocket.js',
    _functionName: 'WS.prototype.addEventListeners/this.ws.onmessage',
    _lineNumber: '127',
    _columnNumber: '5',
    _msg: '    at WS.prototype.addEventListeners/this.ws.onmessage@/private/var/mobile/Containers/Bundle/Application/8,8AE8B2A-1AF3-4B89-A1F0-EB192743F0CD/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/transports/websocket.js:127:5' },
  toString: [Function] ]
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****

```
