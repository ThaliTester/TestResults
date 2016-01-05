#### Test 54970261aa56788_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/54970261aa56788/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/3AA56539-4B8A-4B41-BFBE-31BB5897A091/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/3AA56539-4B8A-4B41-BFBE-31BB5897A091/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/54970261aa56788/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/54970261aa56788/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/330DAB92-2172-4F6C-BEEA-3F0810ADDBA2/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:65400"
,(lldb)     command script import "/tmp/3AA56539-4B8A-4B41-BFBE-31BB5897A091/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-05 19:37:58.578 ThaliTest[980:3141703] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/FA2C198E-E89C-43B0-A52C-69D70E7BC23B/Library/Cookies/Cookies.binarycookies
,2016-01-05 19:37:58.711 ThaliTest[980:3141703] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-05 19:37:58.713 ThaliTest[980:3141703] Multi-tasking -> Device: YES, App: YES
,2016-01-05 19:37:58.720 ThaliTest[980:3141703] Unlimited access to network resources
,2016-01-05 19:37:58.732 ThaliTest[980:3141703] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-05 19:38:09.613 ThaliTest[980:3141703] Resetting plugins due to page load.
,2016-01-05 19:38:13.328 ThaliTest[980:3141703] Finished load of: file:///var/mobile/Containers/Bundle/Application/330DAB92-2172-4F6C-BEEA-3F0810ADDBA2/ThaliTest.app/www/index.html
,2016-01-05 19:38:13.535 ThaliTest[980:3141703] JXcore Cordova plugin initializing
2016-01-05 19:38:13.536 ThaliTest[980:3141903] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
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
,2016-01-05 19:44:45.529 ThaliTest[980:3141903] jxcore: startBroadcasting
,2016-01-05 19:44:45.539 ThaliTest[980:3141903] server: starting 1452019485528.980.cpsq1g==
,2016-01-05 19:44:45.540 ThaliTest[980:3141903] multipeer session: start timer: 0x1c0e8fb0
2016-01-05 19:44:45.541 ThaliTest[980:3141903] THEMultipeerSession initialized peer 1452019485528.980
2016-01-05 19:44:45.541 ThaliTest[980:3141903] jxcore: startBroadcasting: success
ok 45 Should be able to call startBroadcasting without error
,2016-01-05 19:44:45.543 ThaliTest[980:3141903] jxcore: stopBroadcasting
2016-01-05 19:44:45.543 ThaliTest[980:3141903] THEMultipeerSession stopping peer
2016-01-05 19:44:45.543 ThaliTest[980:3141903] multipeer session: stop timer
,2016-01-05 19:44:45.544 ThaliTest[980:3141903] jxcore: stopBroadcasting: success
ok 46 Should be able to call stopBroadcasting without error
2016-01-05 19:44:45.546 ThaliTest[980:3141903] jxcore: startBroadcasting
2016-01-05 19:44:45.550 ThaliTest[980:3,141903] server: starting 1452019485546.980.iGXBFA==
2016-01-05 19:44:45.550 ThaliTest[980:3141903] multipeer session: start timer: 0x14588250
2016-01-05 19:44:45.550 ThaliTest[980:3141903] THEMultipeerSession initialized peer 1452019485546.980
2016-01-0,5 19:44:45.551 ThaliTest[980:3141903] jxcore: startBroadcasting: success
ok 47 Should be able to call startBroadcasting without error
2016-01-05 19:44:45.552 ThaliTest[980:3141903] jxcore: stopBroadcasting
2016-01-05 19:44:45.553 ThaliTest[980:3141903] THEMultipeerSession stopping peer
,2016-01-05 19:44:45.553 ThaliTest[980:3141903] multipeer session: stop timer
2016-01-05 19:44:45.567 ThaliTest[980:3141903] jxcore: stopBroadcasting: success
ok 48 Should be able to call stopBroadcasting without error
2016-01-05 19:44:45.570 ThaliTest[9,80:3141903] jxcore: startBroadcasting
,2016-01-05 19:44:45.584 ThaliTest[980:3141903] server: starting 1452019485569.980.u2M6IQ==
2016-01-05 19:44:45.586 ThaliTest[980:3141903] multipeer session: start timer: 0x1c164a80
,2016-01-05 19:44:45.587 ThaliTest[980:3141903] THEMultipeerSession initialized peer 1452019485569.980
,2016-01-05 19:44:45.593 ThaliTest[980:3141903] jxcore: startBroadcasting: success
,ok 49 Should be able to call startBroadcasting without error
,2016-01-05 19:44:45.601 ThaliTest[980:3141903] jxcore: stopBroadcasting
,2016-01-05 19:44:45.602 ThaliTest[980:3141903] THEMultipeerSession stopping peer
,2016-01-05 19:44:45.604 ThaliTest[980:3141903] multipeer session: stop timer
,2016-01-05 19:44:45.608 ThaliTest[980:3141903] jxcore: stopBroadcasting: success
,ok 50 Should be able to call stopBroadcasting without error
,2016-01-05 19:44:45.612 ThaliTest[980:3141903] jxcore: startBroadcasting
,2016-01-05 19:44:45.616 ThaliTest[980:3141903] server: starting 1452019485612.980.l14BYA==
,2016-01-05 19:44:45.623 ThaliTest[980:3141903] multipeer session: start timer: 0x1456c1b0
,2016-01-05 19:44:45.624 ThaliTest[980:3141903] THEMultipeerSession initialized peer 1452019485612.980
,2016-01-05 19:44:45.626 ThaliTest[980:3141903] jxcore: startBroadcasting: success
,ok 51 Should be able to call startBroadcasting without error
,2016-01-05 19:44:45.629 ThaliTest[980:3141903] jxcore: stopBroadcasting
,2016-01-05 19:44:45.629 ThaliTest[980:3141903] THEMultipeerSession stopping peer
,2016-01-05 19:44:45.630 ThaliTest[980:3141903] multipeer session: stop timer
,2016-01-05 19:44:45.633 ThaliTest[980:3141903] jxcore: stopBroadcasting: success
,ok 52 Should be able to call stopBroadcasting without error
,2016-01-05 19:44:45.636 ThaliTest[980:3141903] jxcore: startBroadcasting
,2016-01-05 19:44:45.640 ThaliTest[980:3141903] server: starting 1452019485636.980.SDvaRw==
,2016-01-05 19:44:45.643 ThaliTest[980:3141903] multipeer session: start timer: 0x1c0ea3e0
,2016-01-05 19:44:45.646 ThaliTest[980:3141903] THEMultipeerSession initialized peer 1452019485636.980
,2016-01-05 19:44:45.648 ThaliTest[980:3141903] jxcore: startBroadcasting: success
,ok 53 Should be able to call startBroadcasting without error
,2016-01-05 19:44:45.650 ThaliTest[980:3141903] jxcore: stopBroadcasting
,2016-01-05 19:44:45.651 ThaliTest[980:3141903] THEMultipeerSession stopping peer
,2016-01-05 19:44:45.651 ThaliTest[980:3141903] multipeer session: stop timer
,2016-01-05 19:44:45.655 ThaliTest[980:3141903] jxcore: stopBroadcasting: success
,ok 54 Should be able to call stopBroadcasting without error
,2016-01-05 19:44:45.658 ThaliTest[980:3141903] jxcore: startBroadcasting
,2016-01-05 19:44:45.661 ThaliTest[980:3141903] server: starting 1452019485658.980.WGbViw==
,2016-01-05 19:44:45.664 ThaliTest[980:3141903] multipeer session: start timer: 0x1468d1f0
,2016-01-05 19:44:45.668 ThaliTest[980:3141903] THEMultipeerSession initialized peer 1452019485658.980
,2016-01-05 19:44:45.668 ThaliTest[980:3141903] jxcore: startBroadcasting: success
,ok 55 Should be able to call startBroadcasting without error
,2016-01-05 19:44:45.671 ThaliTest[980:3141903] jxcore: stopBroadcasting
,2016-01-05 19:44:45.672 ThaliTest[980:3141903] THEMultipeerSession stopping peer
,2016-01-05 19:44:45.672 ThaliTest[980:3141903] multipeer session: stop timer
,2016-01-05 19:44:45.675 ThaliTest[980:3141903] jxcore: stopBroadcasting: success
,ok 56 Should be able to call stopBroadcasting without error
,2016-01-05 19:44:45.678 ThaliTest[980:3141903] jxcore: startBroadcasting
,2016-01-05 19:44:45.681 ThaliTest[980:3141903] server: starting 1452019485678.980.x+GylQ==
,2016-01-05 19:44:45.683 ThaliTest[980:3141903] multipeer session: start timer: 0x1c0ec520
,2016-01-05 19:44:45.688 ThaliTest[980:3141903] THEMultipeerSession initialized peer 1452019485678.980
,2016-01-05 19:44:45.690 ThaliTest[980:3141903] jxcore: startBroadcasting: success
,ok 57 Should be able to call startBroadcasting without error
,2016-01-05 19:44:45.693 ThaliTest[980:3141903] jxcore: stopBroadcasting
,2016-01-05 19:44:45.695 ThaliTest[980:3141903] THEMultipeerSession stopping peer
,2016-01-05 19:44:45.695 ThaliTest[980:3141903] multipeer session: stop timer
,2016-01-05 19:44:45.698 ThaliTest[980:3141903] jxcore: stopBroadcasting: success
,ok 58 Should be able to call stopBroadcasting without error
,2016-01-05 19:44:45.703 ThaliTest[980:3141903] jxcore: startBroadcasting
,2016-01-05 19:44:45.706 ThaliTest[980:3141903] server: starting 1452019485703.980.2Cbexw==
,2016-01-05 19:44:45.708 ThaliTest[980:3141903] multipeer session: start timer: 0x1c1671f0
,2016-01-05 19:44:45.713 ThaliTest[980:3141903] THEMultipeerSession initialized peer 1452019485703.980
,2016-01-05 19:44:45.714 ThaliTest[980:3141903] jxcore: startBroadcasting: success
,ok 59 Should be able to call startBroadcasting without error
,2016-01-05 19:44:45.717 ThaliTest[980:3141903] jxcore: stopBroadcasting
,2016-01-05 19:44:45.718 ThaliTest[980:3141903] THEMultipeerSession stopping peer
,2016-01-05 19:44:45.719 ThaliTest[980:3141903] multipeer session: stop timer
,2016-01-05 19:44:45.722 ThaliTest[980:3141903] jxcore: stopBroadcasting: success
,ok 60 Should be able to call stopBroadcasting without error
,2016-01-05 19:44:45.726 ThaliTest[980:3141903] jxcore: startBroadcasting
,2016-01-05 19:44:45.729 ThaliTest[980:3141903] server: starting 1452019485725.980.QLONTQ==
,2016-01-05 19:44:45.733 ThaliTest[980:3141903] multipeer session: start timer: 0x1c167440
,2016-01-05 19:44:45.735 ThaliTest[980:3141903] THEMultipeerSession initialized peer 1452019485725.980
,2016-01-05 19:44:45.737 ThaliTest[980:3141903] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error
,2016-01-05 19:44:45.742 ThaliTest[980:3141903] jxcore: stopBroadcasting
,2016-01-05 19:44:45.744 ThaliTest[980:3141903] THEMultipeerSession stopping peer
2016-01-05 19:44:45.744 ThaliTest[980:3141903] multipeer session: stop timer
,2016-01-05 19:44:45.749 ThaliTest[980:3141903] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error
,2016-01-05 19:44:45.752 ThaliTest[980:3141903] jxcore: startBroadcasting
,2016-01-05 19:44:45.755 ThaliTest[980:3141903] server: starting 1452019485752.980.RbJLuw==
,2016-01-05 19:44:45.757 ThaliTest[980:3141903] multipeer session: start timer: 0x1c167ec0
,2016-01-05 19:44:45.760 ThaliTest[980:3141903] THEMultipeerSession initialized peer 1452019485752.980
,2016-01-05 19:44:45.765 ThaliTest[980:3141903] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error
,2016-01-05 19:44:45.768 ThaliTest[980:3141903] jxcore: stopBroadcasting
,2016-01-05 19:44:45.769 ThaliTest[980:3141903] THEMultipeerSession stopping peer
,2016-01-05 19:44:45.770 ThaliTest[980:3141903] multipeer session: stop timer
,2016-01-05 19:44:45.774 ThaliTest[980:3141903] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter calls startBroadcasting twice with error
,# teardown
,2016-01-05 19:44:46.463 ThaliTest[980:3141903] jxcore: startBroadcasting
,2016-01-05 19:44:46.466 ThaliTest[980:3141903] server: starting 1452019486462.980.v5ijuw==
2016-01-05 19:44:46.466 ThaliTest[980:3141903] multipeer session: start timer: 0x1c16a2a0
2016-01-05 19:44:46.466 ThaliTest[980:3141903] THEMultipeerSession initialized peer 1452019486462.980
2016-01-05 19:44:46.466 ThaliTest[980:3141903] jxcore: startBroadcasting: success
ok 65 Should be able to call startBroadcasting without error
2016-01-05 19:44:46.468 ThaliTest[980:3141903] jxcore: startBroadcasting
2016-01,-05 19:44:46.468 ThaliTest[980:3141903] jxcore: startBroadcasting: failure
,ok 66 Cannot call startBroadcasting twice
,2016-01-05 19:44:46.477 ThaliTest[980:3141903] jxcore: stopBroadcasting
,2016-01-05 19:44:46.478 ThaliTest[980:3141903] THEMultipeerSession stopping peer
,2016-01-05 19:44:46.479 ThaliTest[980:3141903] multipeer session: stop timer
,2016-01-05 19:44:46.482 ThaliTest[980:3141903] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on connection to bad peer
,# teardown
,2016-01-05 19:44:49.605 ThaliTest[980:3141903] jxcore: startBroadcasting
,2016-01-05 19:44:49.608 ThaliTest[980:3141903] server: starting 1452019489604.980.GZ/PwA==
2016-01-05 19:44:49.609 ThaliTest[980:3141903] multipeer session: start timer: 0x1c16cbf0
2016-01-05 19:44:49.609 ThaliTest[980:3141903] THEMultipeerSession initia,lized peer 1452019489604.980
2016-01-05 19:44:49.609 ThaliTest[980:3141903] jxcore: startBroadcasting: success
ok 68 Should be able to call startBroadcasting without error
2016-01-05 19:44:49.611 ThaliTest[980:3141903] jxcore: connect foobar
2016-01-05, 19:44:49.611 ThaliTest[980:3141903] client: unknown peer foobar
2016-01-05 19:44:49.611 ThaliTest[980:3141903] jxcore: connect: fail: Unknown peer
,ok 69 Should not connect to a bad peer
,2016-01-05 19:44:49.613 ThaliTest[980:3141903] jxcore: stopBroadcasting
2016-01-05 19:44:49.613 ThaliTest[980:3141903] THEMultipeerSession stopping peer
2016-01-05 19:44:49.614 ThaliTest[980:3141903] multipeer session: stop timer
2016-01-05 19:44:49.614, ThaliTest[980:3141903] jxcore: stopBroadcasting: success
ok 70 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on disconnect to bad peer
,# teardown
,2016-01-05 19:44:50.103 ThaliTest[980:3141903] jxcore: startBroadcasting
,2016-01-05 19:44:50.105 ThaliTest[980:3141903] server: starting 1452019490103.980.J7kxcw==
2016-01-05 19:44:50.106 ThaliTest[980:3141903] multipeer session: start timer: 0x1c16ff20
,2016-01-05 19:44:50.106 ThaliTest[980:3141903] THEMultipeerSession initialized peer 1452019490103.980
2016-01-05 19:44:50.109 ThaliTest[980:3141903] jxcore: startBroadcasting: success
ok 71 Should be able to call startBroadcasting without error
2016-01-,05 19:44:50.110 ThaliTest[980:3141903] jxcore: disconnect
2016-01-05 19:44:50.110 ThaliTest[980:3141903] jxcore: disconnect: fail
ok 72 Disconnect should fail to a non-existant peer 
2016-01-05 19:44:50.112 ThaliTest[980:3141903] jxcore: stopBroadcastin,g
2016-01-05 19:44:50.112 ThaliTest[980:3141903] THEMultipeerSession stopping peer
2016-01-05 19:44:50.112 ThaliTest[980:3141903] multipeer session: stop timer
2016-01-05 19:44:50.112 ThaliTest[980:3141903] jxcore: stopBroadcasting: success
ok 73 Shoul,d be able to call stopBroadcasting without error
# setup
,# ThaliEmitter can discover and connect to peers
,# teardown
,2016-01-05 19:44:50.655 ThaliTest[980:3141903] jxcore: startBroadcasting
,2016-01-05 19:44:50.658 ThaliTest[980:3141903] server: starting 1452019490655.980.3hnmXQ==
2016-01-05 19:44:50.659 ThaliTest[980:3141903] multipeer session: start timer: 0x1c0f6940
2016-01-05 19:44:50.659 ThaliTest[980:3141903] THEMultipeerSession initia,lized peer 1452019490655.980
2016-01-05 19:44:50.659 ThaliTest[980:3141903] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error
,2016-01-05 19:44:51.684 ThaliTest[980:3141703] client: found peer: 1452019494007.1361.eWIdzQ==
2016-01-05 19:44:51.686 ThaliTest[980:3141903] jxcore: connect 1452019494007.1361.eWIdzQ==
,2016-01-05 19:44:51.686 ThaliTest[980:3141903] client session: connect
2016-01-05 19:44:51.687 ThaliTest[980:3141903] client session: stateChange:0->1 1452019494007.1361.eWIdzQ==
,2016-01-05 19:44:52.211 ThaliTest[980:3141703] multipeer session: reset timer
2016-01-05 19:44:52.211 ThaliTest[980:3141703] multipeer session: stop timer
2016-01-05 19:44:52.212 ThaliTest[980:3141703] multipeer session: start timer: 0x1c0f6940
,2016-01-05 19:44:52.212 ThaliTest[980:3141703] server session: connect
2016-01-05 19:44:52.213 ThaliTest[980:3141703] server session: stateChange:0->1 1452019494007.1361
2016-01-05 19:44:52.218 ThaliTest[980:3141703] server: accepting invitation 1452019494007.1361
,2016-01-05 19:44:55.623 ThaliTest[980:3142580] server session: connected
2016-01-05 19:44:55.623 ThaliTest[980:3142580] server session: stateChange:1->2 1452019494007.1361
,2016-01-05 19:44:55.652 ThaliTest[980:3141703] server relay: socket disconnected
2016-01-05 19:44:55.653 ThaliTest[980:3141703] server relay: 0x1c175720 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-05 19:44:55.686 ThaliTest[980:3142580] server session: not connected 1452019494007.1361
,2016-01-05 19:44:55.824 ThaliTest[980:3142580] client session: connected
2016-01-05 19:44:55.824 ThaliTest[980:3142580] client session: stateChange:1->2 1452019494007.1361.eWIdzQ==
,2016-01-05 19:44:55.849 ThaliTest[980:3142578] client session: fireConnectCallback: 1452019494007.1361.eWIdzQ==
2016-01-05 19:44:55.849 ThaliTest[980:3142578] jxcore: connect: success
ok 75 Should be able to connect without error
ok 76 Port should be wi,thin range
2016-01-05 19:44:55.851 ThaliTest[980:3141903] jxcore: disconnect
2016-01-05 19:44:55.851 ThaliTest[980:3141903] client session: disconnectFromPeer: 1452019494007.1361.eWIdzQ==
2016-01-05 19:44:55.851 ThaliTest[980:3141903] client session: di,sconnect
2016-01-05 19:44:55.852 ThaliTest[980:3141903] client session: stateChange:2->0 1452019494007.1361.eWIdzQ==
,2016-01-05 19:44:55.862 ThaliTest[980:3141903] jxcore: disconnect: success
ok 77 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
,2016-01-05 19:44:56.324 ThaliTest[980:3141903] jxcore: stopBroadcasting
2016-01-05 19:44:56.324 ThaliTest[980:3141903] THEMultipeerSession stopping peer
2016-01-05 19:44:56.325 ThaliTest[980:3141903] multipeer session: stop timer
2016-01-05 19:44:56.325 ThaliTest[980:3141903] server session: disconnect
2016-01-05 19:44:56.326 ThaliTest[980:3141903] server session: stateChange:2->0 1452019494007.1361
,2016-01-05 19:44:57.317 ThaliTest[980:3141903] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliEmitter can discover and connect to peers and then fail on double connect
,# teardown
,2016-01-05 19:44:57.730 ThaliTest[980:3141903] jxcore: startBroadcasting
,2016-01-05 19:44:57.733 ThaliTest[980:3141903] server: starting 1452019497729.980.9fJ0Fg==
2016-01-05 19:44:57.733 ThaliTest[980:3141903] multipeer session: start timer: 0x1c0f37e0
2016-01-05 19:44:57.734 ThaliTest[980:3141903] THEMultipeerSession initialized peer 1452019497729.980
2016-01-05 19:44:57.734 ThaliTest[980:3141903] jxcore: startBroadcasting: success
ok 78 Should be able to call startBroadcasting without error
,2016-01-05 19:44:58.583 ThaliTest[980:3141703] client: found peer: 1452019494007.1361.eWIdzQ==
2016-01-05 19:44:58.585 ThaliTest[980:3141903] jxcore: connect 1452019494007.1361.eWIdzQ==
2016-01-05 19:44:58.585 ThaliTest[980:3141903] client session: conne,ct
2016-01-05 19:44:58.585 ThaliTest[980:3141903] client session: stateChange:0->1 1452019494007.1361.eWIdzQ==
,2016-01-05 19:44:58.638 ThaliTest[980:3141703] client: found peer: 1452019501088.1361.2oCJJw==
2016-01-05 19:44:58.639 ThaliTest[980:3141903] jxcore: connect 1452019501088.1361.2oCJJw==
2016-01-05 19:44:58.639 ThaliTest[980:3141903] client session: conne,ct
2016-01-05 19:44:58.639 ThaliTest[980:3141903] client session: stateChange:0->1 1452019501088.1361.2oCJJw==
,2016-01-05 19:44:59.224 ThaliTest[980:3141703] multipeer session: reset timer
2016-01-05 19:44:59.224 ThaliTest[980:3141703] multipeer session: stop timer
2016-01-05 19:44:59.224 ThaliTest[980:3141703] multipeer session: start timer: 0x1c0f37e0
2016-01-,05 19:44:59.224 ThaliTest[980:3141703] server session: connect
,2016-01-05 19:44:59.225 ThaliTest[980:3141703] server session: stateChange:0->1 1452019501088.1361
,2016-01-05 19:44:59.232 ThaliTest[980:3141703] server: accepting invitation 1452019501088.1361
,2016-01-05 19:44:59.583 ThaliTest[980:3141703] client: lost peer: 1452019494007.1361.eWIdzQ==
2016-01-05 19:44:59.583 ThaliTest[980:3141703] client session: onPeerLost: 1452019494007.1361.eWIdzQ==
,2016-01-05 19:44:59.583 ThaliTest[980:3141703] client session: onLinkFailure: 1452019494007.1361.eWIdzQ==
2016-01-05 19:44:59.584 ThaliTest[980:3141703] client session: disconnect
2016-01-05 19:44:59.584 ThaliTest[980:3141703] client session: stateChange,:1->0 1452019494007.1361.eWIdzQ==
2016-01-05 19:44:59.584 ThaliTest[980:3141703] client session: fireConnectCallback: 1452019494007.1361.eWIdzQ==
2016-01-05 19:44:59.585 ThaliTest[980:3141703] jxcore: connect: fail: Peer disconnected
,2016-01-05 19:45:00.595 ThaliTest[980:3141903] jxcore: connect 1452019494007.1361.eWIdzQ==
2016-01-05 19:45:00.595 ThaliTest[980:3141903] client: connect: unreachable 1452019494007.1361.eWIdzQ==
2016-01-05 19:45:00.595 ThaliTest[980:3141903] jxcore: connect: fail: Peer unreachable
,2016-01-05 19:45:02.627 ThaliTest[980:3142579] server session: connected
2016-01-05 19:45:02.627 ThaliTest[980:3142579] server session: stateChange:1->2 1452019501088.1361
,2016-01-05 19:45:02.635 ThaliTest[980:3141703] server relay: socket disconnected
2016-01-05 19:45:02.635 ThaliTest[980:3141703] server relay: 0x1c0f7590 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-05 19:45:02.701 ThaliTest[980:3142580] server session: not connected 1452019501088.1361
,2016-01-05 19:45:02.957 ThaliTest[980:3142578] client session: connected
2016-01-05 19:45:02.957 ThaliTest[980:3142578] client session: stateChange:1->2 1452019501088.1361.2oCJJw==
,2016-01-05 19:45:02.961 ThaliTest[980:3142578] client session: fireConnectCallback: 1452019501088.1361.2oCJJw==
2016-01-05 19:45:02.961 ThaliTest[980:3142578] jxcore: connect: success
ok 79 Should be able to connect without error
ok 80 Port should be wi,thin range
2016-01-05 19:45:02.964 ThaliTest[980:3141903] jxcore: connect 1452019501088.1361.2oCJJw==
2016-01-05 19:45:02.964 ThaliTest[980:3141903] client: already connect(ing/ed) to 1452019501088.1361.2oCJJw==
2016-01-05 19:45:02.964 ThaliTest[980:314,1903] jxcore: connect: fail: Aleady connecting
ok 81 Should fail on double connect
2016-01-05 19:45:02.966 ThaliTest[980:3141903] jxcore: disconnect
2016-01-05 19:45:02.966 ThaliTest[980:3141903] client session: disconnectFromPeer: 1452019501088.1361.2o,CJJw==
2016-01-05 19:45:02.966 ThaliTest[980:3141903] client session: disconnect
2016-01-05 19:45:02.966 ThaliTest[980:3141903] client session: stateChange:2->0 1452019501088.1361.2oCJJw==
,2016-01-05 19:45:02.975 ThaliTest[980:3141903] jxcore: disconnect: success
ok 82 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
,2016-01-05 19:45:03.140 ThaliTest[980:3141903] jxcore: stopBroadcasting
2016-01-05 19:45:03.141 ThaliTest[980:3141903] THEMultipeerSession stopping peer
2016-01-05 19:45:03.141 ThaliTest[980:3141903] multipeer session: stop timer
2016-01-05 19:45:03.142, ThaliTest[980:3141903] server session: disconnect
2016-01-05 19:45:03.142 ThaliTest[980:3141903] server session: stateChange:2->0 1452019501088.1361
2016-01-05 19:45:03.143 ThaliTest[980:3141903] jxcore: stopBroadcasting: success
,stopBroadcasting returned undefined
# ThaliEmitter can discover and connect to peers and then fail on double disconnect
,# teardown
,2016-01-05 19:45:04.292 ThaliTest[980:3141903] jxcore: startBroadcasting
,2016-01-05 19:45:04.295 ThaliTest[980:3141903] server: starting 1452019504292.980.HwEYsA==
2016-01-05 19:45:04.295 ThaliTest[980:3141903] multipeer session: start timer: 0x1c046000
2016-01-05 19:45:04.296 ThaliTest[980:3141903] THEMultipeerSession initialized peer 1452019504292.980
2016-01-05 19:45:04.296 ThaliTest[980:3141903] jxcore: startBroadcasting: success
,ok 83 Should be able to call startBroadcasting without error
,2016-01-05 19:45:04.306 ThaliTest[980:3141703] client: found peer: 1452019501088.1361.2oCJJw==
2016-01-05 19:45:04.307 ThaliTest[980:3141903] jxcore: connect 1452019501088.1361.2oCJJw==
2016-01-05 19:45:04.308 ThaliTest[980:3141903] client session: connect
2016-01-05 19:45:04.308 ThaliTest[980:3141903] client session: stateChange:0->1 1452019501088.1361.2oCJJw==
,2016-01-05 19:45:05.909 ThaliTest[980:3141703] multipeer session: reset timer
2016-01-05 19:45:05.910 ThaliTest[980:3141703] multipeer session: stop timer
2016-01-05 19:45:05.910 ThaliTest[980:3141703] multipeer session: start timer: 0x1c046000
2016-01-05 19:45:05.910 ThaliTest[980:3141703] server session: connect
2016-01-05 19:45:05.910 ThaliTest[980:3141703] server session: stateChange:0->1 1452019507635.1361
,2016-01-05 19:45:05.917 ThaliTest[980:3141703] server: accepting invitation 1452019507635.1361
,2016-01-05 19:45:06.386 ThaliTest[980:3141703] client: lost peer: 1452019501088.1361.2oCJJw==
2016-01-05 19:45:06.386 ThaliTest[980:3141703] client session: onPeerLost: 1452019501088.1361.2oCJJw==
2016-01-05 19:45:06.386 ThaliTest[980:3141703] client ses,sion: onLinkFailure: 1452019501088.1361.2oCJJw==
2016-01-05 19:45:06.386 ThaliTest[980:3141703] client session: disconnect
2016-01-05 19:45:06.386 ThaliTest[980:3141703] client session: stateChange:1->0 1452019501088.1361.2oCJJw==
2016-01-05 19:45:06.38,7 ThaliTest[980:3141703] client session: fireConnectCallback: 1452019501088.1361.2oCJJw==
2016-01-05 19:45:06.387 ThaliTest[980:3141703] jxcore: connect: fail: Peer disconnected
2016-01-05 19:45:06.388 ThaliTest[980:3141703] client: found peer: 145201950,7635.1361./UnwPQ==
,2016-01-05 19:45:06.392 ThaliTest[980:3141903] jxcore: connect 1452019507635.1361./UnwPQ==
2016-01-05 19:45:06.392 ThaliTest[980:3141903] client session: connect
2016-01-05 19:45:06.392 ThaliTest[980:3141903] client session: stateChange:0->1 1452019507635.1361./UnwPQ==
,2016-01-05 19:45:07.400 ThaliTest[980:3141903] jxcore: connect 1452019501088.1361.2oCJJw==
2016-01-05 19:45:07.401 ThaliTest[980:3141903] client: connect: unreachable 1452019501088.1361.2oCJJw==
2016-01-05 19:45:07.401 ThaliTest[980:3141903] jxcore: connect: fail: Peer unreachable
,2016-01-05 19:45:09.326 ThaliTest[980:3142631] server session: connected
2016-01-05 19:45:09.326 ThaliTest[980:3142631] server session: stateChange:1->2 1452019507635.1361
,2016-01-05 19:45:09.342 ThaliTest[980:3141703] server relay: socket disconnected
2016-01-05 19:45:09.342 ThaliTest[980:3141703] server relay: 0x1c17f3c0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-05 19:45:09.379 ThaliTest[980:3142576] server session: not connected 1452019507635.1361
,2016-01-05 19:45:09.773 ThaliTest[980:3142576] client session: connected
2016-01-05 19:45:09.774 ThaliTest[980:3142576] client session: stateChange:1->2 1452019507635.1361./UnwPQ==
,2016-01-05 19:45:09.778 ThaliTest[980:3142576] client session: fireConnectCallback: 1452019507635.1361./UnwPQ==
2016-01-05 19:45:09.778 ThaliTest[980:3142576] jxcore: connect: success
ok 84 Should be able to connect without error
,ok 85 Port should be within range
2016-01-05 19:45:09.781 ThaliTest[980:3141903] jxcore: disconnect
2016-01-05 19:45:09.782 ThaliTest[980:3141903] client session: disconnectFromPeer: 1452019507635.1361./UnwPQ==
2016-01-05 19:45:09.782 ThaliTest[980:3141,903] client session: disconnect
2016-01-05 19:45:09.782 ThaliTest[980:3141903] client session: stateChange:2->0 1452019507635.1361./UnwPQ==
,2016-01-05 19:45:09.792 ThaliTest[980:3141903] jxcore: disconnect: success
,ok 86 Should be able to disconnect without error
2016-01-05 19:45:09.797 ThaliTest[980:3141903] jxcore: disconnect
2016-01-05 19:45:09.798 ThaliTest[980:3141903] jxcore: disconnect: fail
ok 87 Disconnect should fail 
setting stopBroadcasting callback a,nd ending test.
,# setup
,calling stopBroadcasting
,2016-01-05 19:45:09.947 ThaliTest[980:3141903] jxcore: stopBroadcasting
2016-01-05 19:45:09.948 ThaliTest[980:3141903] THEMultipeerSession stopping peer
2016-01-05 19:45:09.948 ThaliTest[980:3141903] multipeer session: stop timer
2016-01-05 19:45:09.949, ThaliTest[980:3141903] server session: disconnect
2016-01-05 19:45:09.949 ThaliTest[980:3141903] server session: stateChange:2->0 1452019507635.1361
2016-01-05 19:45:09.949 ThaliTest[980:3141903] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliEmitter handles socket disconnect correctly
,# teardown
,2016-01-05 19:45:12.061 ThaliTest[980:3141903] jxcore: startBroadcasting
,2016-01-05 19:45:12.063 ThaliTest[980:3141903] server: starting 1452019512061.980.ux/WWw==
2016-01-05 19:45:12.063 ThaliTest[980:3141903] multipeer session: start timer: 0x1c182980
2016-01-05 19:45:12.064 ThaliTest[980:3141903] THEMultipeerSession initialized peer 1452019512061.980
2016-01-05 19:45:12.064 ThaliTest[980:3141903] jxcore: startBroadcasting: success
ok 88 Should be able to call startBroadcasting without error
echo server started
,2016-01-05 19:45:12.076 ThaliTest[980:3141703] client: found peer: 1452019507635.1361./UnwPQ==
[{"peerIdentifier":"1452019507635.1361./UnwPQ==","peerName":"(null)","peerAvailable":true}]
,2016-01-05 19:45:12.078 ThaliTest[980:3141903] jxcore: connect 1452019507635.1361./UnwPQ==
2016-01-05 19:45:12.079 ThaliTest[980:3141903] client session: connect
2016-01-05 19:45:12.079 ThaliTest[980:3141903] client session: stateChange:0->1 1452019507635.1361./UnwPQ==
,2016-01-05 19:45:13.701 ThaliTest[980:3141703] client: found peer: 1452019515723.1361.poqfdw==
[{"peerIdentifier":"1452019515723.1361.poqfdw==","peerName":"(null)","peerAvailable":true}]
,2016-01-05 19:45:13.705 ThaliTest[980:3141903] jxcore: connect 1452019515723.1361.poqfdw==
2016-01-05 19:45:13.706 ThaliTest[980:3141903] client session: connect
2016-01-05 19:45:13.706 ThaliTest[980:3141903] client session: stateChange:0->1 1452019515723.1361.poqfdw==
,2016-01-05 19:45:14.367 ThaliTest[980:3141703] multipeer session: reset timer
2016-01-05 19:45:14.367 ThaliTest[980:3141703] multipeer session: stop timer
2016-01-05 19:45:14.367 ThaliTest[980:3141703] multipeer session: start timer: 0x1c182980
2016-01-,05 19:45:14.368 ThaliTest[980:3141703] server session: connect
2016-01-05 19:45:14.368 ThaliTest[980:3141703] server session: stateChange:0->1 1452019515723.1361
,2016-01-05 19:45:14.375 ThaliTest[980:3141703] server: accepting invitation 1452019515723.1361
,2016-01-05 19:45:15.340 ThaliTest[980:3141703] client: lost peer: 1452019507635.1361./UnwPQ==
2016-01-05 19:45:15.341 ThaliTest[980:3141703] client session: onPeerLost: 1452019507635.1361./UnwPQ==
2016-01-05 19:45:15.341 ThaliTest[980:3141703] client ses,sion: onLinkFailure: 1452019507635.1361./UnwPQ==
2016-01-05 19:45:15.342 ThaliTest[980:3141703] client session: disconnect
2016-01-05 19:45:15.342 ThaliTest[980:3141703] client session: stateChange:1->0 1452019507635.1361./UnwPQ==
2016-01-05 19:45:15.34,2 ThaliTest[980:3141703] client session: fireConnectCallback: 1452019507635.1361./UnwPQ==
2016-01-05 19:45:15.343 ThaliTest[980:3141703] jxcore: connect: fail: Peer disconnected
[{"peerIdentifier":"1452019507635.1361./UnwPQ==","peerName":"(null)","peerAvailable":false}]
,2016-01-05 19:45:16.354 ThaliTest[980:3141903] jxcore: connect 1452019507635.1361./UnwPQ==
2016-01-05 19:45:16.354 ThaliTest[980:3141903] client: connect: unreachable 1452019507635.1361./UnwPQ==
2016-01-05 19:45:16.355 ThaliTest[980:3141903] jxcore: connect: fail: Peer unreachable
,2016-01-05 19:45:17.996 ThaliTest[980:3142582] server session: connected
2016-01-05 19:45:17.997 ThaliTest[980:3142582] server session: stateChange:1->2 1452019515723.1361
,2016-01-05 19:45:18.000 ThaliTest[980:3141703] server relay: connected (to port: 5001)
,2016-01-05 19:45:18.226 ThaliTest[980:3142576] server session: not connected 1452019515723.1361
,2016-01-05 19:45:18.243 ThaliTest[980:3142576] client session: connected
2016-01-05 19:45:18.243 ThaliTest[980:3142576] client session: stateChange:1->2 1452019515723.1361.poqfdw==
,2016-01-05 19:45:18.302 ThaliTest[980:3141703] multipeer session: reset timer
2016-01-05 19:45:18.303 ThaliTest[980:3141703] multipeer session: stop timer
2016-01-05 19:45:18.303 ThaliTest[980:3141703] multipeer session: start timer: 0x1c182980
,2016-01-05 19:45:18.303 ThaliTest[980:3141703] server: disconnecting to refresh session (1452019515723.1361)
,2016-01-05 19:45:18.305 ThaliTest[980:3141703] server session: disconnect
2016-01-05 19:45:18.306 ThaliTest[980:3141703] server session: stateChange:2->0 1452019515723.1361
2016-01-05 19:45:18.304 ThaliTest[980:3142579] client session: fireConnectCallbac,k: 1452019515723.1361.poqfdw==
2016-01-05 19:45:18.306 ThaliTest[980:3142579] jxcore: connect: success
ok 89 Should be able to connect without error
ok 90 Port should be within range
2016-01-05 19:45:18.310 ThaliTest[980:3141703] server session: connect
ok 91 First connect should succeed
2016-01-05 19:45:18.310 ThaliTest[980:3141703] server session: stateChange:0->1 1452019515723.1361
,2016-01-05 19:45:18.331 ThaliTest[980:3141703] server: accepting invitation 1452019515723.1361
,2016-01-05 19:45:18.383 ThaliTest[980:3141703] client: relay established
2016-01-05 19:45:18.383 ThaliTest[980:3141703] client: new accepted socket: 0x1c184330
,ok 92 the test messages should be equal
,ok 93 First send should succeed
,2016-01-05 19:45:18.443 ThaliTest[980:3141703] client: socket closed
2016-01-05 19:45:18.444 ThaliTest[980:3141703] client relay: socket disconnected
2016-01-05 19:45:18.444 ThaliTest[980:3141703] client relay: 0x1c184330 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-05 19:45:18.444 ThaliTest[980:3141703] client session: socket closed: 1452019515723.1361.poqfdw==
2016-01-05 19:4,5:18.444 ThaliTest[980:3141703] client session: onLinkFailure: 1452019515723.1361.poqfdw==
2016-01-05 19:45:18.444 ThaliTest[980:3141703] client session: disconnect
2016-01-05 19:45:18.445 ThaliTest[980:3141703] client session: stateChange:2->0 1452019515723.1361.poqfdw==
,2016-01-05 19:45:18.466 ThaliTest[980:3141703] client session: fireConnectionErrorEvent: 1452019515723.1361.poqfdw==
2016-01-05 19:45:18.469 ThaliTest[980:3141903] jxcore: connect 1452019515723.1361.poqfdw==
2016-01-05 19:45:18.470 ThaliTest[980:3141903], client session: connect
2016-01-05 19:45:18.470 ThaliTest[980:3141903] client session: stateChange:0->1 1452019515723.1361.poqfdw==
,2016-01-05 19:45:22.025 ThaliTest[980:3142580] server session: connected
2016-01-05 19:45:22.025 ThaliTest[980:3142580] server session: stateChange:1->2 1452019515723.1361
2016-01-05 19:45:22.029 ThaliTest[980:3141703] server relay: connected (to port: 5001)
,2016-01-05 19:45:22.100 ThaliTest[980:3142579] client session: connected
,2016-01-05 19:45:22.101 ThaliTest[980:3142579] client session: stateChange:1->2 1452019515723.1361.poqfdw==
,2016-01-05 19:45:22.153 ThaliTest[980:3142661] client session: fireConnectCallback: 1452019515723.1361.poqfdw==
2016-01-05 19:45:22.153 ThaliTest[980:3142661] jxcore: connect: success
ok 94 Should be able to connect without error
,ok 95 Port should be within range
,ok 96 Second connect should succeed
,2016-01-05 19:45:22.175 ThaliTest[980:3142631] server session: not connected 1452019515723.1361
,2016-01-05 19:45:22.182 ThaliTest[980:3141703] client: relay established
2016-01-05 19:45:22.182 ThaliTest[980:3141703] client: new accepted socket: 0x1c033ef0
,ok 97 the test messages should be equal
,ok 98 Second send should succeed
,# setup
,2016-01-05 19:45:22.244 ThaliTest[980:3141703] client: socket closed
2016-01-05 19:45:22.245 ThaliTest[980:3141703] client relay: socket disconnected
2016-01-05 19:45:22.245 ThaliTest[980:3141703] client relay: 0x1c033ef0 disconnected with error Error Do,main=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-05 19:45:22.246 ThaliTest[980:3141703] client session: socket closed: 1452019515723.1361.poqfdw==
2016-01-05 19:4,5:22.246 ThaliTest[980:3141703] client session: onLinkFailure: 1452019515723.1361.poqfdw==
2016-01-05 19:45:22.246 ThaliTest[980:3141703] client session: disconnect
2016-01-05 19:45:22.247 ThaliTest[980:3141703] client session: stateChange:2->0 1452019515723.1361.poqfdw==
,2016-01-05 19:45:22.256 ThaliTest[980:3141703] client session: fireConnectionErrorEvent: 1452019515723.1361.poqfdw==
,calling stopBroadcasting
,2016-01-05 19:45:22.537 ThaliTest[980:3141903] jxcore: stopBroadcasting
2016-01-05 19:45:22.537 ThaliTest[980:3141903] THEMultipeerSession stopping peer
2016-01-05 19:45:22.537 ThaliTest[980:3141903] multipeer session: stop timer
2016-01-05 19:45:22.538 ThaliTest[980:3141903] server session: disconnect
2016-01-05 19:45:22.538 ThaliTest[980:3141903] server session: stateChange:2->0 1452019515723.1361
,2016-01-05 19:45:22.543 ThaliTest[980:3141903] jxcore: stopBroadcasting: success
,stopBroadcasting returned undefined
# ThaliReplicationManager can call start without error
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/FA2C198E-E89C-43B0-A52C-69D70E7BC23B/tmp/pouchdb"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,ok 99 starting event should occur in right order
,2016-01-05 19:45:23.280 ThaliTest[980:3141903] jxcore: startBroadcasting
,2016-01-05 19:45:23.283 ThaliTest[980:3141903] server: starting JpqulKC-3XEZ6ucq7CNg7A.GgMeNg==
2016-01-05 19:45:23.283 ThaliTest[980:3141903] multipeer session: start timer: 0x1c039720
2016-01-05 19:45:23.283 ThaliTest[980:3141903] THEMultipeerSession i,nitialized peer JpqulKC-3XEZ6ucq7CNg7A
2016-01-05 19:45:23.283 ThaliTest[980:3141903] jxcore: startBroadcasting: success
ok 100 started event should occur in right order
Now in TRM stop
State of this._isStarted: true
ok 101 stopping event should occur, in right order
About to call stopBroadcasting
,2016-01-05 19:45:23.287 ThaliTest[980:3141903] jxcore: stopBroadcasting
2016-01-05 19:45:23.289 ThaliTest[980:3141903] THEMultipeerSession stopping peer
2016-01-05 19:45:23.289 ThaliTest[980:3141903] multipeer session: stop timer
2016-01-05 19:45:23.290, ThaliTest[980:3141903] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined
ok 102 stopped event should occur in right order
mux server bridge listener closed
# setup
,# ThaliReplicationManager receives identity
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/FA2C198E-E89C-43B0-A52C-69D70E7BC23B/tmp/pouchdb"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,2016-01-05 19:45:24.072 ThaliTest[980:3141903] jxcore: startBroadcasting
,2016-01-05 19:45:24.074 ThaliTest[980:3141903] server: starting JpqulKC-3XEZ6ucq7CNg7A.v7/ooQ==
2016-01-05 19:45:24.075 ThaliTest[980:3141903] multipeer session: start timer: 0x1c1a0d70
,2016-01-05 19:45:24.075 ThaliTest[980:3141903] THEMultipeerSession initialized peer JpqulKC-3XEZ6ucq7CNg7A
2016-01-05 19:45:24.078 ThaliTest[980:3141903] jxcore: startBroadcasting: success
ok 103 getDeviceIdentity should not return an error
,ok 104 deviceName should not be null
,Now in TRM stop
State of this._isStarted: true
About to call stopBroadcasting
2016-01-05 19:45:24.081 ThaliTest[980:3141903] jxcore: stopBroadcasting
2016-01-05 19:45:24.081 ThaliTest[980:3141903] THEMultipeerSession stopping peer
2016-01-05 19:45:24.,082 ThaliTest[980:3141903] multipeer session: stop timer
2016-01-05 19:45:24.082 ThaliTest[980:3141903] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined
mux server bridge listener closed
Tests Complete
,Total: 0	Passed: 0	Failed: 0
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
