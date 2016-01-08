#### Test 549702613245198_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/549702613245198/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/16B43F4D-468C-4BB9-8C85-A4FA130ED948/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/16B43F4D-468C-4BB9-8C85-A4FA130ED948/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/549702613245198/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/549702613245198/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/19C7E0BB-0FDA-4132-9BBF-E9C5232F4F68/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51235"
,(lldb)     command script import "/tmp/16B43F4D-468C-4BB9-8C85-A4FA130ED948/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-01-08 21:05:22.823 ThaliTest[1143:3628459] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F69F64FC-4C21-400C-91B3-B22318A04FB0/Library/Cookies/Cookies.binarycookies
,2016-01-08 21:05:22.938 ThaliTest[1143:3628459] Apache Cordova native platform version 3.9.2 is starting.
2016-01-08 21:05:22.939 ThaliTest[1143:3628459] Multi-tasking -> Device: YES, App: YES
,2016-01-08 21:05:22.943 ThaliTest[1143:3628459] Unlimited access to network resources
,2016-01-08 21:05:22.954 ThaliTest[1143:3628459] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-08 21:05:33.345 ThaliTest[1143:3628459] Resetting plugins due to page load.
,2016-01-08 21:05:37.494 ThaliTest[1143:3628459] Finished load of: file:///var/mobile/Containers/Bundle/Application/19C7E0BB-0FDA-4132-9BBF-E9C5232F4F68/ThaliTest.app/www/index.html
,2016-01-08 21:05:37.703 ThaliTest[1143:3628459] JXcore Cordova plugin initializing
2016-01-08 21:05:37.705 ThaliTest[1143:3628642] JXcore instance initializing
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
,2016-01-08 21:11:37.403 ThaliTest[1143:3628642] jxcore: startBroadcasting
,2016-01-08 21:11:37.412 ThaliTest[1143:3628642] server: starting 1452283897402.1143.CKzOpg==
,2016-01-08 21:11:37.413 ThaliTest[1143:3628642] multipeer session: start timer: 0x1bba37f0
,2016-01-08 21:11:37.414 ThaliTest[1143:3628642] THEMultipeerSession initialized peer 1452283897402.1143
,2016-01-08 21:11:37.414 ThaliTest[1143:3628642] jxcore: startBroadcasting: success
ok 45 Should be able to call startBroadcasting without error
2016-01-08 21:11:37.416 ThaliTest[1143:3628642] jxcore: stopBroadcasting
2016-01-08 21:11:37.416 ThaliTest[11,43:3628642] THEMultipeerSession stopping peer
2016-01-08 21:11:37.416 ThaliTest[1143:3628642] multipeer session: stop timer
,2016-01-08 21:11:37.419 ThaliTest[1143:3628642] jxcore: stopBroadcasting: success
ok 46 Should be able to call stopBroadcasting without error
2016-01-08 21:11:37.421 ThaliTest[1143:3628642] jxcore: startBroadcasting
,2016-01-08 21:11:37.426 ThaliTest[1143:3628642] server: starting 1452283897421.1143.ZP5I/Q==
,2016-01-08 21:11:37.433 ThaliTest[1143:3628642] multipeer session: start timer: 0x1b92afc0
,2016-01-08 21:11:37.443 ThaliTest[1143:3628642] THEMultipeerSession initialized peer 1452283897421.1143
,2016-01-08 21:11:37.445 ThaliTest[1143:3628642] jxcore: startBroadcasting: success
,ok 47 Should be able to call startBroadcasting without error
,2016-01-08 21:11:37.448 ThaliTest[1143:3628642] jxcore: stopBroadcasting
,2016-01-08 21:11:37.449 ThaliTest[1143:3628642] THEMultipeerSession stopping peer
,2016-01-08 21:11:37.450 ThaliTest[1143:3628642] multipeer session: stop timer
,2016-01-08 21:11:37.455 ThaliTest[1143:3628642] jxcore: stopBroadcasting: success
,ok 48 Should be able to call stopBroadcasting without error
,2016-01-08 21:11:37.459 ThaliTest[1143:3628642] jxcore: startBroadcasting
,2016-01-08 21:11:37.463 ThaliTest[1143:3628642] server: starting 1452283897458.1143.m7tSUw==
,2016-01-08 21:11:37.470 ThaliTest[1143:3628642] multipeer session: start timer: 0x15d3c1e0
,2016-01-08 21:11:37.476 ThaliTest[1143:3628642] THEMultipeerSession initialized peer 1452283897458.1143
,2016-01-08 21:11:37.478 ThaliTest[1143:3628642] jxcore: startBroadcasting: success
,ok 49 Should be able to call startBroadcasting without error
,2016-01-08 21:11:37.481 ThaliTest[1143:3628642] jxcore: stopBroadcasting
,2016-01-08 21:11:37.482 ThaliTest[1143:3628642] THEMultipeerSession stopping peer
,2016-01-08 21:11:37.483 ThaliTest[1143:3628642] multipeer session: stop timer
,2016-01-08 21:11:37.488 ThaliTest[1143:3628642] jxcore: stopBroadcasting: success
,ok 50 Should be able to call stopBroadcasting without error
,2016-01-08 21:11:37.491 ThaliTest[1143:3628642] jxcore: startBroadcasting
,2016-01-08 21:11:37.495 ThaliTest[1143:3628642] server: starting 1452283897491.1143.UefyHw==
,2016-01-08 21:11:37.498 ThaliTest[1143:3628642] multipeer session: start timer: 0x15e5d640
,2016-01-08 21:11:37.506 ThaliTest[1143:3628642] THEMultipeerSession initialized peer 1452283897491.1143
,2016-01-08 21:11:37.507 ThaliTest[1143:3628642] jxcore: startBroadcasting: success
,ok 51 Should be able to call startBroadcasting without error
,2016-01-08 21:11:37.510 ThaliTest[1143:3628642] jxcore: stopBroadcasting
,2016-01-08 21:11:37.511 ThaliTest[1143:3628642] THEMultipeerSession stopping peer
,2016-01-08 21:11:37.513 ThaliTest[1143:3628642] multipeer session: stop timer
,2016-01-08 21:11:37.518 ThaliTest[1143:3628642] jxcore: stopBroadcasting: success
,ok 52 Should be able to call stopBroadcasting without error
,2016-01-08 21:11:37.520 ThaliTest[1143:3628642] jxcore: startBroadcasting
,2016-01-08 21:11:37.523 ThaliTest[1143:3628642] server: starting 1452283897520.1143.tsjEvA==
,2016-01-08 21:11:37.528 ThaliTest[1143:3628642] multipeer session: start timer: 0x1be6a0d0
,2016-01-08 21:11:37.532 ThaliTest[1143:3628642] THEMultipeerSession initialized peer 1452283897520.1143
,2016-01-08 21:11:37.533 ThaliTest[1143:3628642] jxcore: startBroadcasting: success
,ok 53 Should be able to call startBroadcasting without error
,2016-01-08 21:11:37.536 ThaliTest[1143:3628642] jxcore: stopBroadcasting
,2016-01-08 21:11:37.537 ThaliTest[1143:3628642] THEMultipeerSession stopping peer
,2016-01-08 21:11:37.538 ThaliTest[1143:3628642] multipeer session: stop timer
,2016-01-08 21:11:37.541 ThaliTest[1143:3628642] jxcore: stopBroadcasting: success
,ok 54 Should be able to call stopBroadcasting without error
,2016-01-08 21:11:37.545 ThaliTest[1143:3628642] jxcore: startBroadcasting
,2016-01-08 21:11:37.548 ThaliTest[1143:3628642] server: starting 1452283897545.1143.TX/eiA==
,2016-01-08 21:11:37.550 ThaliTest[1143:3628642] multipeer session: start timer: 0x1bbef8c0
,2016-01-08 21:11:37.554 ThaliTest[1143:3628642] THEMultipeerSession initialized peer 1452283897545.1143
,2016-01-08 21:11:37.558 ThaliTest[1143:3628642] jxcore: startBroadcasting: success
,ok 55 Should be able to call startBroadcasting without error
,2016-01-08 21:11:37.562 ThaliTest[1143:3628642] jxcore: stopBroadcasting
,2016-01-08 21:11:37.562 ThaliTest[1143:3628642] THEMultipeerSession stopping peer
,2016-01-08 21:11:37.563 ThaliTest[1143:3628642] multipeer session: stop timer
,2016-01-08 21:11:37.564 ThaliTest[1143:3628642] jxcore: stopBroadcasting: success
,ok 56 Should be able to call stopBroadcasting without error
,2016-01-08 21:11:37.570 ThaliTest[1143:3628642] jxcore: startBroadcasting
,2016-01-08 21:11:37.572 ThaliTest[1143:3628642] server: starting 1452283897569.1143.FNPRQg==
,2016-01-08 21:11:37.574 ThaliTest[1143:3628642] multipeer session: start timer: 0x1ba96bf0
,2016-01-08 21:11:37.575 ThaliTest[1143:3628642] THEMultipeerSession initialized peer 1452283897569.1143
,2016-01-08 21:11:37.581 ThaliTest[1143:3628642] jxcore: startBroadcasting: success
,ok 57 Should be able to call startBroadcasting without error
,2016-01-08 21:11:37.585 ThaliTest[1143:3628642] jxcore: stopBroadcasting
,2016-01-08 21:11:37.586 ThaliTest[1143:3628642] THEMultipeerSession stopping peer
,2016-01-08 21:11:37.586 ThaliTest[1143:3628642] multipeer session: stop timer
,2016-01-08 21:11:37.588 ThaliTest[1143:3628642] jxcore: stopBroadcasting: success
,ok 58 Should be able to call stopBroadcasting without error
,2016-01-08 21:11:37.593 ThaliTest[1143:3628642] jxcore: startBroadcasting
,2016-01-08 21:11:37.596 ThaliTest[1143:3628642] server: starting 1452283897593.1143.Xy9Bdg==
,2016-01-08 21:11:37.597 ThaliTest[1143:3628642] multipeer session: start timer: 0x15d7af90
,2016-01-08 21:11:37.599 ThaliTest[1143:3628642] THEMultipeerSession initialized peer 1452283897593.1143
,2016-01-08 21:11:37.606 ThaliTest[1143:3628642] jxcore: startBroadcasting: success
,ok 59 Should be able to call startBroadcasting without error
,2016-01-08 21:11:37.609 ThaliTest[1143:3628642] jxcore: stopBroadcasting
,2016-01-08 21:11:37.610 ThaliTest[1143:3628642] THEMultipeerSession stopping peer
,2016-01-08 21:11:37.611 ThaliTest[1143:3628642] multipeer session: stop timer
,2016-01-08 21:11:37.613 ThaliTest[1143:3628642] jxcore: stopBroadcasting: success
,ok 60 Should be able to call stopBroadcasting without error
,2016-01-08 21:11:37.619 ThaliTest[1143:3628642] jxcore: startBroadcasting
,2016-01-08 21:11:37.622 ThaliTest[1143:3628642] server: starting 1452283897618.1143.AufhdQ==
,2016-01-08 21:11:37.623 ThaliTest[1143:3628642] multipeer session: start timer: 0x1ba99530
,2016-01-08 21:11:37.625 ThaliTest[1143:3628642] THEMultipeerSession initialized peer 1452283897618.1143
,2016-01-08 21:11:37.626 ThaliTest[1143:3628642] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error
,2016-01-08 21:11:37.634 ThaliTest[1143:3628642] jxcore: stopBroadcasting
,2016-01-08 21:11:37.636 ThaliTest[1143:3628642] THEMultipeerSession stopping peer
,2016-01-08 21:11:37.637 ThaliTest[1143:3628642] multipeer session: stop timer
,2016-01-08 21:11:37.638 ThaliTest[1143:3628642] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error
,2016-01-08 21:11:37.644 ThaliTest[1143:3628642] jxcore: startBroadcasting
,2016-01-08 21:11:37.646 ThaliTest[1143:3628642] server: starting 1452283897643.1143.HmBw4w==
,2016-01-08 21:11:37.649 ThaliTest[1143:3628642] multipeer session: start timer: 0x1bca5b40
,2016-01-08 21:11:37.656 ThaliTest[1143:3628642] THEMultipeerSession initialized peer 1452283897643.1143
,2016-01-08 21:11:37.659 ThaliTest[1143:3628642] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error
,2016-01-08 21:11:37.662 ThaliTest[1143:3628642] jxcore: stopBroadcasting
,2016-01-08 21:11:37.663 ThaliTest[1143:3628642] THEMultipeerSession stopping peer
,2016-01-08 21:11:37.664 ThaliTest[1143:3628642] multipeer session: stop timer
,2016-01-08 21:11:37.667 ThaliTest[1143:3628642] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter calls startBroadcasting twice with error
,# teardown
,2016-01-08 21:11:37.783 ThaliTest[1143:3628642] jxcore: startBroadcasting
,2016-01-08 21:11:37.786 ThaliTest[1143:3628642] server: starting 1452283897783.1143.Vb61cw==
2016-01-08 21:11:37.786 ThaliTest[1143:3628642] multipeer session: start timer: 0x1bc1f1d0
2016-01-08 21:11:37.786 ThaliTest[1143:3628642] THEMultipeerSession in,itialized peer 1452283897783.1143
2016-01-08 21:11:37.788 ThaliTest[1143:3628642] jxcore: startBroadcasting: success
ok 65 Should be able to call startBroadcasting without error
2016-01-08 21:11:37.789 ThaliTest[1143:3628642] jxcore: startBroadcasting
,2016-01-08 21:11:37.790 ThaliTest[1143:3628642] jxcore: startBroadcasting: failure
,ok 66 Cannot call startBroadcasting twice
2016-01-08 21:11:37.792 ThaliTest[1143:3628642] jxcore: stopBroadcasting
2016-01-08 21:11:37.792 ThaliTest[1143:3628642] THEMultipeerSession stopping peer
2016-01-08 21:11:37.792 ThaliTest[1143:3628642] multipeer session: stop timer
2016-01-08 21:11:37.792 ThaliTest[1143:3628642] jxcore: stopBroadcasting: success
ok 67 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on connection to bad peer
,# teardown
,2016-01-08 21:11:38.388 ThaliTest[1143:3628642] jxcore: startBroadcasting
,2016-01-08 21:11:38.390 ThaliTest[1143:3628642] server: starting 1452283898387.1143.gotuhQ==
2016-01-08 21:11:38.391 ThaliTest[1143:3628642] multipeer session: start timer: 0x15ecc5b0
2016-01-08 21:11:38.391 ThaliTest[1143:3628642] THEMultipeerSession in,itialized peer 1452283898387.1143
2016-01-08 21:11:38.391 ThaliTest[1143:3628642] jxcore: startBroadcasting: success
ok 68 Should be able to call startBroadcasting without error
2016-01-08 21:11:38.392 ThaliTest[1143:3628642] jxcore: connect foobar
201,6-01-08 21:11:38.393 ThaliTest[1143:3628642] client: unknown peer foobar
2016-01-08 21:11:38.393 ThaliTest[1143:3628642] jxcore: connect: fail: Unknown peer
ok 69 Should not connect to a bad peer
,2016-01-08 21:11:38.396 ThaliTest[1143:3628642] jxcore: stopBroadcasting
2016-01-08 21:11:38.397 ThaliTest[1143:3628642] THEMultipeerSession stopping peer
2016-01-08 21:11:38.397 ThaliTest[1143:3628642] multipeer session: stop timer
2016-01-08 21:11:38.,397 ThaliTest[1143:3628642] jxcore: stopBroadcasting: success
ok 70 Should be able to call stopBroadcasting without error
# setup
,# ThaliEmitter throws on disconnect to bad peer
,# teardown
,2016-01-08 21:11:41.546 ThaliTest[1143:3628642] jxcore: startBroadcasting
,2016-01-08 21:11:41.549 ThaliTest[1143:3628642] server: starting 1452283901546.1143.mpcraw==
2016-01-08 21:11:41.549 ThaliTest[1143:3628642] multipeer session: start timer: 0x1bc04ee0
2016-01-08 21:11:41.550 ThaliTest[1143:3628642] THEMultipeerSession initialized peer 1452283901546.1143
2016-01-08 21:11:41.550 ThaliTest[1143:3628642] jxcore: startBroadcasting: success
ok 71 Should be able to call startBroadcasting without error
,2016-01-08 21:11:41.551 ThaliTest[1143:3628642] jxcore: disconnect
2016-01-08 21:11:41.552 ThaliTest[1143:3628642] jxcore: disconnect: fail
,ok 72 Disconnect should fail to a non-existant peer 
2016-01-08 21:11:41.554 ThaliTest[1143:3628642] jxcore: stopBroadcasting
2016-01-08 21:11:41.554 ThaliTest[1143:3628642] THEMultipeerSession stopping peer
2016-01-08 21:11:41.554 ThaliTest[1143:362864,2] multipeer session: stop timer
2016-01-08 21:11:41.554 ThaliTest[1143:3628642] jxcore: stopBroadcasting: success
ok 73 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter can discover and connect to peers
,# teardown
,2016-01-08 21:11:44.549 ThaliTest[1143:3628642] jxcore: startBroadcasting
,2016-01-08 21:11:44.551 ThaliTest[1143:3628642] server: starting 1452283904549.1143.idzy+w==
2016-01-08 21:11:44.551 ThaliTest[1143:3628642] multipeer session: start timer: 0x15e81790
2016-01-08 21:11:44.552 ThaliTest[1143:3628642] THEMultipeerSession initialized peer 1452283904549.1143
2016-01-08 21:11:44.552 ThaliTest[1143:3628642] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error
,2016-01-08 21:11:48.112 ThaliTest[1143:3628459] multipeer session: reset timer
2016-01-08 21:11:48.112 ThaliTest[1143:3628459] multipeer session: stop timer
2016-01-08 21:11:48.112 ThaliTest[1143:3628459] multipeer session: start timer: 0x15e81790
,2016-01-08 21:11:48.113 ThaliTest[1143:3628459] server session: connect
2016-01-08 21:11:48.113 ThaliTest[1143:3628459] server session: stateChange:0->1 1452283906937.1583
,2016-01-08 21:11:48.119 ThaliTest[1143:3628459] server: accepting invitation 1452283906937.1583
,2016-01-08 21:11:48.640 ThaliTest[1143:3628459] client: found peer: 1452283906937.1583.c4YI7w==
,2016-01-08 21:11:48.642 ThaliTest[1143:3628642] jxcore: connect 1452283906937.1583.c4YI7w==
2016-01-08 21:11:48.642 ThaliTest[1143:3628642] client session: connect
2016-01-08 21:11:48.642 ThaliTest[1143:3628642] client session: stateChange:0->1 1452283906937.1583.c4YI7w==
,2016-01-08 21:11:51.180 ThaliTest[1143:3629325] server session: connected
2016-01-08 21:11:51.181 ThaliTest[1143:3629325] server session: stateChange:1->2 1452283906937.1583
,2016-01-08 21:11:51.207 ThaliTest[1143:3628459] server relay: socket disconnected
2016-01-08 21:11:51.207 ThaliTest[1143:3628459] server relay: 0x1bba8250 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-08 21:11:51.247 ThaliTest[1143:3629283] server session: not connected 1452283906937.1583
,2016-01-08 21:11:52.818 ThaliTest[1143:3629283] client session: connected
2016-01-08 21:11:52.818 ThaliTest[1143:3629283] client session: stateChange:1->2 1452283906937.1583.c4YI7w==
,2016-01-08 21:11:52.847 ThaliTest[1143:3629278] client session: fireConnectCallback: 1452283906937.1583.c4YI7w==
2016-01-08 21:11:52.847 ThaliTest[1143:3629278] jxcore: connect: success
ok 75 Should be able to connect without error
,ok 76 Port should be within range
,2016-01-08 21:11:52.850 ThaliTest[1143:3628642] jxcore: disconnect
2016-01-08 21:11:52.850 ThaliTest[1143:3628642] client session: disconnectFromPeer: 1452283906937.1583.c4YI7w==
2016-01-08 21:11:52.850 ThaliTest[1143:3628642] client session: disconnect
2016-01-08 21:11:52.851 ThaliTest[1143:3628642] client session: stateChange:2->0 1452283906937.1583.c4YI7w==
,2016-01-08 21:11:52.859 ThaliTest[1143:3628642] jxcore: disconnect: success
ok 77 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
,2016-01-08 21:11:54.606 ThaliTest[1143:3628642] jxcore: stopBroadcasting
2016-01-08 21:11:54.606 ThaliTest[1143:3628642] THEMultipeerSession stopping peer
2016-01-08 21:11:54.607 ThaliTest[1143:3628642] multipeer session: stop timer
2016-01-08 21:11:54.607 ThaliTest[1143:3628642] server session: disconnect
2016-01-08 21:11:54.607 ThaliTest[1143:3628642] server session: stateChange:2->0 1452283906937.1583
,2016-01-08 21:11:54.608 ThaliTest[1143:3628642] jxcore: stopBroadcasting: success
,stopBroadcasting returned undefined
,# ThaliEmitter can discover and connect to peers and then fail on double connect
,# teardown
,2016-01-08 21:11:55.097 ThaliTest[1143:3628642] jxcore: startBroadcasting
,2016-01-08 21:11:55.099 ThaliTest[1143:3628642] server: starting 1452283915096.1143.NiABgw==
2016-01-08 21:11:55.100 ThaliTest[1143:3628642] multipeer session: start timer: 0x1d8f7870
2016-01-08 21:11:55.100 ThaliTest[1143:3628642] THEMultipeerSession initialized peer 1452283915096.1143
2016-01-08 21:11:55.100 ThaliTest[1143:3628642] jxcore: startBroadcasting: success
ok 78 Should be able to call startBroadcasting without error
,2016-01-08 21:11:56.215 ThaliTest[1143:3628459] client: found peer: 1452283915133.1583.8Fd4dQ==
2016-01-08 21:11:56.216 ThaliTest[1143:3628642] jxcore: connect 1452283915133.1583.8Fd4dQ==
2016-01-08 21:11:56.217 ThaliTest[1143:3628642] client session: co,nnect
2016-01-08 21:11:56.217 ThaliTest[1143:3628642] client session: stateChange:0->1 1452283915133.1583.8Fd4dQ==
,2016-01-08 21:11:56.398 ThaliTest[1143:3628459] multipeer session: reset timer
2016-01-08 21:11:56.398 ThaliTest[1143:3628459] multipeer session: stop timer
2016-01-08 21:11:56.399 ThaliTest[1143:3628459] multipeer session: start timer: 0x1d8f7870
2016-,01-08 21:11:56.399 ThaliTest[1143:3628459] server session: connect
2016-01-08 21:11:56.399 ThaliTest[1143:3628459] server session: stateChange:0->1 1452283915133.1583
,2016-01-08 21:11:56.406 ThaliTest[1143:3628459] server: accepting invitation 1452283915133.1583
,2016-01-08 21:11:59.117 ThaliTest[1143:3629325] client session: connected
2016-01-08 21:11:59.117 ThaliTest[1143:3629325] client session: stateChange:1->2 1452283915133.1583.8Fd4dQ==
,2016-01-08 21:11:59.131 ThaliTest[1143:3629280] client session: fireConnectCallback: 1452283915133.1583.8Fd4dQ==
2016-01-08 21:11:59.132 ThaliTest[1143:3629280] jxcore: connect: success
ok 79 Should be able to connect without error
ok 80 Port should be within range
,2016-01-08 21:11:59.134 ThaliTest[1143:3628642] jxcore: connect 1452283915133.1583.8Fd4dQ==
2016-01-08 21:11:59.134 ThaliTest[1143:3628642] client: already connect(ing/ed) to 1452283915133.1583.8Fd4dQ==
2016-01-08 21:11:59.134 ThaliTest[1143:3628642] jxcore: connect: fail: Aleady connecting
,ok 81 Should fail on double connect
2016-01-08 21:11:59.136 ThaliTest[1143:3628642] jxcore: disconnect
2016-01-08 21:11:59.136 ThaliTest[1143:3628642] client session: disconnectFromPeer: 1452283915133.1583.8Fd4dQ==
2016-01-08 21:11:59.136 ThaliTest[1143:3628642] client session: disconnect
2016-01-08 21:11:59.137 ThaliTest[1143:3628642] client session: stateChange:2->0 1452283915133.1583.8Fd4dQ==
,2016-01-08 21:11:59.209 ThaliTest[1143:3628642] jxcore: disconnect: success
ok 82 Should be able to disconnect without error
,setting stopBroadcasting callback and ending test.
,# setup
,2016-01-08 21:11:59.962 ThaliTest[1143:3629278] server session: connected
,2016-01-08 21:11:59.962 ThaliTest[1143:3629278] server session: stateChange:1->2 1452283915133.1583
,2016-01-08 21:11:59.968 ThaliTest[1143:3628459] server relay: socket disconnected
,2016-01-08 21:11:59.968 ThaliTest[1143:3628459] server relay: 0x1b9719b0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-08 21:12:00.100 ThaliTest[1143:3629325] server session: not connected 1452283915133.1583
,calling stopBroadcasting
,2016-01-08 21:12:00.745 ThaliTest[1143:3628642] jxcore: stopBroadcasting
2016-01-08 21:12:00.746 ThaliTest[1143:3628642] THEMultipeerSession stopping peer
2016-01-08 21:12:00.746 ThaliTest[1143:3628642] multipeer session: stop timer
2016-01-08 21:12:00.,746 ThaliTest[1143:3628642] server session: disconnect
2016-01-08 21:12:00.746 ThaliTest[1143:3628642] server session: stateChange:2->0 1452283915133.1583
,2016-01-08 21:12:00.751 ThaliTest[1143:3628642] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter can discover and connect to peers and then fail on double disconnect
,# teardown
,2016-01-08 21:12:01.683 ThaliTest[1143:3628642] jxcore: startBroadcasting
,2016-01-08 21:12:01.686 ThaliTest[1143:3628642] server: starting 1452283921683.1143.ytsBKQ==
2016-01-08 21:12:01.686 ThaliTest[1143:3628642] multipeer session: start timer: 0x1ba277c0
2016-01-08 21:12:01.687 ThaliTest[1143:3628642] THEMultipeerSession in,itialized peer 1452283921683.1143
2016-01-08 21:12:01.687 ThaliTest[1143:3628642] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error
,2016-01-08 21:12:03.097 ThaliTest[1143:3628459] client: found peer: 1452283921712.1583.tyrCBw==
2016-01-08 21:12:03.098 ThaliTest[1143:3628642] jxcore: connect 1452283921712.1583.tyrCBw==
2016-01-08 21:12:03.098 ThaliTest[1143:3628642] client session: co,nnect
2016-01-08 21:12:03.098 ThaliTest[1143:3628642] client session: stateChange:0->1 1452283921712.1583.tyrCBw==
,2016-01-08 21:12:03.297 ThaliTest[1143:3628459] multipeer session: reset timer
2016-01-08 21:12:03.298 ThaliTest[1143:3628459] multipeer session: stop timer
2016-01-08 21:12:03.298 ThaliTest[1143:3628459] multipeer session: start timer: 0x1ba277c0
2016-01-08 21:12:03.298 ThaliTest[1143:3628459] server session: connect
,2016-01-08 21:12:03.300 ThaliTest[1143:3628459] server session: stateChange:0->1 1452283921712.1583
,2016-01-08 21:12:03.307 ThaliTest[1143:3628459] server: accepting invitation 1452283921712.1583
,2016-01-08 21:12:05.790 ThaliTest[1143:3629278] server session: connected
2016-01-08 21:12:05.790 ThaliTest[1143:3629278] server session: stateChange:1->2 1452283921712.1583
,2016-01-08 21:12:05.820 ThaliTest[1143:3628459] server relay: socket disconnected
2016-01-08 21:12:05.820 ThaliTest[1143:3628459] server relay: 0x1be47db0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-08 21:12:05.927 ThaliTest[1143:3629325] client session: connected
2016-01-08 21:12:05.927 ThaliTest[1143:3629325] client session: stateChange:1->2 1452283921712.1583.tyrCBw==
,2016-01-08 21:12:05.936 ThaliTest[1143:3629325] server session: not connected 1452283921712.1583
,2016-01-08 21:12:05.983 ThaliTest[1143:3629278] client session: fireConnectCallback: 1452283921712.1583.tyrCBw==
2016-01-08 21:12:05.983 ThaliTest[1143:3629278] jxcore: connect: success
ok 84 Should be able to connect without error
ok 85 Port should be ,within range
2016-01-08 21:12:05.985 ThaliTest[1143:3628642] jxcore: disconnect
2016-01-08 21:12:05.985 ThaliTest[1143:3628642] client session: disconnectFromPeer: 1452283921712.1583.tyrCBw==
2016-01-08 21:12:05.986 ThaliTest[1143:3628642] client sessio,n: disconnect
2016-01-08 21:12:05.986 ThaliTest[1143:3628642] client session: stateChange:2->0 1452283921712.1583.tyrCBw==
,2016-01-08 21:12:06.061 ThaliTest[1143:3628642] jxcore: disconnect: success
ok 86 Should be able to disconnect without error
,2016-01-08 21:12:06.064 ThaliTest[1143:3628642] jxcore: disconnect
2016-01-08 21:12:06.064 ThaliTest[1143:3628642] jxcore: disconnect: fail
ok 87 Disconnect should fail 
,setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
,2016-01-08 21:12:06.122 ThaliTest[1143:3628642] jxcore: stopBroadcasting
2016-01-08 21:12:06.123 ThaliTest[1143:3628642] THEMultipeerSession stopping peer
2016-01-08 21:12:06.123 ThaliTest[1143:3628642] multipeer session: stop timer
2016-01-08 21:12:06.123 ThaliTest[1143:3628642] server session: disconnect
2016-01-08 21:12:06.124 ThaliTest[1143:3628642] server session: stateChange:2->0 1452283921712.1583
,2016-01-08 21:12:06.129 ThaliTest[1143:3628642] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliEmitter handles socket disconnect correctly
,# teardown
,2016-01-08 21:12:07.169 ThaliTest[1143:3628642] jxcore: startBroadcasting
,2016-01-08 21:12:07.172 ThaliTest[1143:3628642] server: starting 1452283927168.1143.u1xFpA==
2016-01-08 21:12:07.172 ThaliTest[1143:3628642] multipeer session: start timer: 0x1be5d710
2016-01-08 21:12:07.172 ThaliTest[1143:3628642] THEMultipeerSession in,itialized peer 1452283927168.1143
2016-01-08 21:12:07.173 ThaliTest[1143:3628642] jxcore: startBroadcasting: success
ok 88 Should be able to call startBroadcasting without error
echo server started
,2016-01-08 21:12:08.390 ThaliTest[1143:3628459] client: found peer: 1452283927186.1583.wH5YQA==
[{"peerIdentifier":"1452283927186.1583.wH5YQA==","peerName":"(null)","peerAvailable":true}]
,2016-01-08 21:12:08.393 ThaliTest[1143:3628642] jxcore: connect 1452283927186.1583.wH5YQA==
2016-01-08 21:12:08.393 ThaliTest[1143:3628642] client session: connect
2016-01-08 21:12:08.393 ThaliTest[1143:3628642] client session: stateChange:0->1 1452283927186.1583.wH5YQA==
,2016-01-08 21:12:08.480 ThaliTest[1143:3628459] multipeer session: reset timer
,2016-01-08 21:12:08.480 ThaliTest[1143:3628459] multipeer session: stop timer
,2016-01-08 21:12:08.481 ThaliTest[1143:3628459] multipeer session: start timer: 0x1be5d710
,2016-01-08 21:12:08.481 ThaliTest[1143:3628459] server session: connect
,2016-01-08 21:12:08.482 ThaliTest[1143:3628459] server session: stateChange:0->1 1452283927186.1583
,2016-01-08 21:12:08.488 ThaliTest[1143:3628459] server: accepting invitation 1452283927186.1583
,2016-01-08 21:12:11.104 ThaliTest[1143:3629278] server session: connected
2016-01-08 21:12:11.104 ThaliTest[1143:3629278] server session: stateChange:1->2 1452283927186.1583
,2016-01-08 21:12:11.125 ThaliTest[1143:3628459] server relay: connected (to port: 5001)
,2016-01-08 21:12:11.234 ThaliTest[1143:3629283] client session: connected
2016-01-08 21:12:11.234 ThaliTest[1143:3629283] client session: stateChange:1->2 1452283927186.1583.wH5YQA==
,2016-01-08 21:12:11.253 ThaliTest[1143:3629280] client session: fireConnectCallback: 1452283927186.1583.wH5YQA==
2016-01-08 21:12:11.253 ThaliTest[1143:3629280] jxcore: connect: success
ok 89 Should be able to connect without error
,ok 90 Port should be within range
,ok 91 First connect should succeed
,2016-01-08 21:12:11.288 ThaliTest[1143:3628459] client: relay established
2016-01-08 21:12:11.289 ThaliTest[1143:3628459] client: new accepted socket: 0x1bb412f0
,ok 92 the test messages should be equal
,ok 93 First send should succeed
,2016-01-08 21:12:11.387 ThaliTest[1143:3628459] client: socket closed
2016-01-08 21:12:11.388 ThaliTest[1143:3628459] client relay: socket disconnected
2016-01-08 21:12:11.389 ThaliTest[1143:3628459] client relay: 0x1bb412f0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-08 21:12:11.389 ThaliTest[1143:3628459] client session: socket closed: 1452283927186.1583.wH5YQA==
2016-01-08 ,21:12:11.389 ThaliTest[1143:3628459] client session: onLinkFailure: 1452283927186.1583.wH5YQA==
2016-01-08 21:12:11.390 ThaliTest[1143:3628459] client session: disconnect
2016-01-08 21:12:11.390 ThaliTest[1143:3628459] client session: stateChange:2->0 1452283927186.1583.wH5YQA==
,2016-01-08 21:12:11.398 ThaliTest[1143:3628459] client session: fireConnectionErrorEvent: 1452283927186.1583.wH5YQA==
,2016-01-08 21:12:11.400 ThaliTest[1143:3628642] jxcore: connect 1452283927186.1583.wH5YQA==
2016-01-08 21:12:11.402 ThaliTest[1143:3628642] client session: connect
2016-01-08 21:12:11.402 ThaliTest[1143:3628642] client session: stateChange:0->1 1452283927186.1583.wH5YQA==
,2016-01-08 21:12:11.533 ThaliTest[1143:3629357] server session: not connected 1452283927186.1583
,2016-01-08 21:12:11.683 ThaliTest[1143:3628459] multipeer session: reset timer
,2016-01-08 21:12:11.683 ThaliTest[1143:3628459] multipeer session: stop timer
,2016-01-08 21:12:11.684 ThaliTest[1143:3628459] multipeer session: start timer: 0x1be5d710
,2016-01-08 21:12:11.684 ThaliTest[1143:3628459] server: disconnecting to refresh session (1452283927186.1583)
,2016-01-08 21:12:11.685 ThaliTest[1143:3628459] server session: disconnect
,2016-01-08 21:12:11.686 ThaliTest[1143:3628459] server session: stateChange:2->0 1452283927186.1583
,2016-01-08 21:12:11.689 ThaliTest[1143:3628459] server session: connect
2016-01-08 21:12:11.689 ThaliTest[1143:3628459] server session: stateChange:0->1 1452283927186.1583
,2016-01-08 21:12:11.700 ThaliTest[1143:3628459] server: accepting invitation 1452283927186.1583
,2016-01-08 21:12:14.253 ThaliTest[1143:3629283] server session: connected
2016-01-08 21:12:14.254 ThaliTest[1143:3629283] server session: stateChange:1->2 1452283927186.1583
,2016-01-08 21:12:14.304 ThaliTest[1143:3628459] server relay: connected (to port: 5001)
,2016-01-08 21:12:14.323 ThaliTest[1143:3629278] client session: connected
2016-01-08 21:12:14.323 ThaliTest[1143:3629278] client session: stateChange:1->2 1452283927186.1583.wH5YQA==
,2016-01-08 21:12:14.368 ThaliTest[1143:3629278] client session: fireConnectCallback: 1452283927186.1583.wH5YQA==
2016-01-08 21:12:14.368 ThaliTest[1143:3629278] jxcore: connect: success
ok 94 Should be able to connect without error
ok 95 Port should be within range
ok 96 Second connect should succeed
,2016-01-08 21:12:14.399 ThaliTest[1143:3628459] client: relay established
2016-01-08 21:12:14.399 ThaliTest[1143:3628459] client: new accepted socket: 0x1bcd9d40
,ok 97 the test messages should be equal
2016-01-08 21:12:14.503 ThaliTest[1143:3629280] server session: not connected 1452283927186.1583
ok 98 Second send should succeed
# setup
,2016-01-08 21:12:14.521 ThaliTest[1143:3628459] client: socket closed
2016-01-08 21:12:14.522 ThaliTest[1143:3628459] client relay: socket disconnected
2016-01-08 21:12:14.522 ThaliTest[1143:3628459] client relay: 0x1bcd9d40 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-08 21:12:14.523 ThaliTest[1143:3628459] client session: socket closed: 1452283927186.1583.wH5YQA==
2016-01-08 ,21:12:14.523 ThaliTest[1143:3628459] client session: onLinkFailure: 1452283927186.1583.wH5YQA==
2016-01-08 21:12:14.523 ThaliTest[1143:3628459] client session: disconnect
2016-01-08 21:12:14.523 ThaliTest[1143:3628459] client session: stateChange:2->0 14,52283927186.1583.wH5YQA==
,calling stopBroadcasting
,2016-01-08 21:12:14.535 ThaliTest[1143:3628642] jxcore: stopBroadcasting
,2016-01-08 21:12:14.536 ThaliTest[1143:3628642] THEMultipeerSession stopping peer
,2016-01-08 21:12:14.537 ThaliTest[1143:3628642] multipeer session: stop timer
2016-01-08 21:12:14.539 ThaliTest[1143:3628642] server session: disconnect
2016-01-08 21:12:14.539 ThaliTest[1143:3628642] server session: stateChange:2->0 1452283927186.1583
,2016-01-08 21:12:14.552 ThaliTest[1143:3628642] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliReplicationManager can call start without error
,2016-01-08 21:12:14.624 ThaliTest[1143:3628459] client session: fireConnectionErrorEvent: 1452283927186.1583.wH5YQA==
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/F69F64FC-4C21-400C-91B3-B22318A04FB0/tmp/pouchdb"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,ok 99 starting event should occur in right order
,2016-01-08 21:12:16.658 ThaliTest[1143:3628642] jxcore: startBroadcasting
,2016-01-08 21:12:16.660 ThaliTest[1143:3628642] server: starting JzZu0OmXa1zY1UeKhdgjAQ.LUuG1w==
2016-01-08 21:12:16.661 ThaliTest[1143:3628642] multipeer session: start timer: 0x1bf5f2e0
2016-01-08 21:12:16.661 ThaliTest[1143:3628642] THEMultipeerSessio,n initialized peer JzZu0OmXa1zY1UeKhdgjAQ
2016-01-08 21:12:16.661 ThaliTest[1143:3628642] jxcore: startBroadcasting: success
ok 100 started event should occur in right order
Now in TRM stop
State of this._isStarted: true
ok 101 stopping event should o,ccur in right order
About to call stopBroadcasting
,2016-01-08 21:12:16.665 ThaliTest[1143:3628642] jxcore: stopBroadcasting
2016-01-08 21:12:16.665 ThaliTest[1143:3628642] THEMultipeerSession stopping peer
2016-01-08 21:12:16.666 ThaliTest[1143:3628642] multipeer session: stop timer
2016-01-08 21:12:16.,666 ThaliTest[1143:3628642] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined
,ok 102 stopped event should occur in right order
,mux server bridge listener closed
# setup
,# ThaliReplicationManager receives identity
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/F69F64FC-4C21-400C-91B3-B22318A04FB0/tmp/pouchdb"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,2016-01-08 21:12:17.088 ThaliTest[1143:3628642] jxcore: startBroadcasting
,2016-01-08 21:12:17.090 ThaliTest[1143:3628642] server: starting JzZu0OmXa1zY1UeKhdgjAQ.WI99CQ==
2016-01-08 21:12:17.091 ThaliTest[1143:3628642] multipeer session: start timer: 0x1bf532d0
2016-01-08 21:12:17.091 ThaliTest[1143:3628642] THEMultipeerSessio,n initialized peer JzZu0OmXa1zY1UeKhdgjAQ
2016-01-08 21:12:17.092 ThaliTest[1143:3628642] jxcore: startBroadcasting: success
ok 103 getDeviceIdentity should not return an error
ok 104 deviceName should not be null
Now in TRM stop
State of this._isStarted: true
,About to call stopBroadcasting
2016-01-08 21:12:17.094 ThaliTest[1143:3628642] jxcore: stopBroadcasting
2016-01-08 21:12:17.095 ThaliTest[1143:3628642] THEMultipeerSession stopping peer
2016-01-08 21:12:17.095 ThaliTest[1143:3628642] multipeer session: stop timer
,2016-01-08 21:12:17.096 ThaliTest[1143:3628642] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined
,mux server bridge listener closed
,Tests Complete
,Total: 0	Passed: 0	Failed: 0
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
