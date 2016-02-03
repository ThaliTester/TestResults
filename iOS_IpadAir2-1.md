#### Test 58135655e794d2c_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/58135655e794d2c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/B3DF3B8D-9CFF-47B4-8E2A-AA3724BCAB84/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/B3DF3B8D-9CFF-47B4-8E2A-AA3724BCAB84/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/58135655e794d2c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/58135655e794d2c/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/99499307-D142-428E-997A-989450D2DB73/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49687"
,(lldb)     command script import "/tmp/B3DF3B8D-9CFF-47B4-8E2A-AA3724BCAB84/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-03 22:13:14.566 ThaliTest[598:881431] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/608C14D9-0CA6-49B8-9822-3FAA888CDDF9/Library/Cookies/Cookies.binarycookies
,2016-02-03 22:13:14.905 ThaliTest[598:881431] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-03 22:13:14.905 ThaliTest[598:881431] Multi-tasking -> Device: YES, App: YES
,2016-02-03 22:13:14.916 ThaliTest[598:881431] Unlimited access to network resources
,2016-02-03 22:13:14.924 ThaliTest[598:881431] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-03 22:13:24.565 ThaliTest[598:881431] Resetting plugins due to page load.
,2016-02-03 22:13:28.282 ThaliTest[598:881431] Finished load of: file:///var/mobile/Containers/Bundle/Application/99499307-D142-428E-997A-989450D2DB73/ThaliTest.app/www/index.html
,2016-02-03 22:13:28.446 ThaliTest[598:881431] JXcore Cordova plugin initializing
,2016-02-03 22:13:28.447 ThaliTest[598:881697] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/99499307-D142-428E-997A-989450D2DB73/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/99499307-D142-428E-997A-989450D2DB73/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/99499307-D142-428E-997A-989450D2DB73/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/99499307-D142-428E-997A-989450D2DB73/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/99499307-D142-428E-997A-989450D2DB73/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/99499307-D142-428E-997A-989450D2DB73/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/99499307-D142-428E-997A-989450D2DB73/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/99499307-D142-428E-997A-989450D2DB73/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

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

ok 16 should be equal

,ok 17 should not throw

# setup

,# successfully read a previous pkcs12 file and return hash value

,# teardown

,ok 18 (unnamed assert)

,ok 19 (unnamed assert)

,ok 20 should not throw

,ok 21 should be equal

,ok 22 should be equal

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

,2016-02-03 22:17:40.579 ThaliTest[598:881697] jxcore: startBroadcasting
,2016-02-03 22:17:40.596 ThaliTest[598:881697] server: starting 1454534260578.598.43wHIQ==
,2016-02-03 22:17:40.597 ThaliTest[598:881697] multipeer session: start timer: 0x17b4fdf0
2016-02-03 22:17:40.598 ThaliTest[598:881697] THEMultipeerSession initialized peer 1454534260578.598
,2016-02-03 22:17:40.599 ThaliTest[598:881697] jxcore: startBroadcasting: success
,ok 54 Should be able to call startBroadcasting without error

,2016-02-03 22:17:40.604 ThaliTest[598:881697] jxcore: stopBroadcasting
2016-02-03 22:17:40.605 ThaliTest[598:881697] THEMultipeerSession stopping peer
2016-02-03 22:17:40.606 ThaliTest[598:881697] multipeer session: stop timer
2016-02-03 22:17:40.607 ThaliTest[598:881697] jxcore: stopBroadcasting: success
ok 55 Should be able to call stopBroadcasting without error

,2016-02-03 22:17:40.611 ThaliTest[598:881697] jxcore: startBroadcasting
,2016-02-03 22:17:40.614 ThaliTest[598:881697] server: starting 1454534260610.598.yrRJ0A==
,2016-02-03 22:17:40.617 ThaliTest[598:881697] multipeer session: start timer: 0x17b4ae50
2016-02-03 22:17:40.617 ThaliTest[598:881697] THEMultipeerSession initialized peer 1454534260610.598
2016-02-03 22:17:40.617 ThaliTest[598:881697] jxcore: startBroadcasting: success
ok 56 Should be able to call startBroadcasting without error

,2016-02-03 22:17:40.620 ThaliTest[598:881697] jxcore: stopBroadcasting
2016-02-03 22:17:40.622 ThaliTest[598:881697] THEMultipeerSession stopping peer
2016-02-03 22:17:40.622 ThaliTest[598:881697] multipeer session: stop timer
2016-02-03 22:17:40.622 Th,aliTest[598:881697] jxcore: stopBroadcasting: success
ok 57 Should be able to call stopBroadcasting without error

,2016-02-03 22:17:40.625 ThaliTest[598:881697] jxcore: startBroadcasting
,2016-02-03 22:17:40.630 ThaliTest[598:881697] server: starting 1454534260624.598.IpS4yQ==
,2016-02-03 22:17:40.635 ThaliTest[598:881697] multipeer session: start timer: 0x17f05860
,2016-02-03 22:17:40.636 ThaliTest[598:881697] THEMultipeerSession initialized peer 1454534260624.598
,2016-02-03 22:17:40.637 ThaliTest[598:881697] jxcore: startBroadcasting: success
ok 58 Should be able to call startBroadcasting without error

2016-02-03 22:17:40.639 ThaliTest[598:881697] jxcore: stopBroadcasting
,2016-02-03 22:17:40.639 ThaliTest[598:881697] THEMultipeerSession stopping peer
2016-02-03 22:17:40.640 ThaliTest[598:881697] multipeer session: stop timer
,2016-02-03 22:17:40.640 ThaliTest[598:881697] jxcore: stopBroadcasting: success
ok 59 Should be able to call stopBroadcasting without error

,2016-02-03 22:17:40.643 ThaliTest[598:881697] jxcore: startBroadcasting
,2016-02-03 22:17:40.648 ThaliTest[598:881697] server: starting 1454534260642.598.VTs6pw==
,2016-02-03 22:17:40.650 ThaliTest[598:881697] multipeer session: start timer: 0x17f05f50
2016-02-03 22:17:40.651 ThaliTest[598:881697] THEMultipeerSession initialized peer 1454534260642.598
2016-02-03 22:17:40.651 ThaliTest[598:881697] jxcore: startBroad,casting: success
ok 60 Should be able to call startBroadcasting without error

,2016-02-03 22:17:40.653 ThaliTest[598:881697] jxcore: stopBroadcasting
2016-02-03 22:17:40.655 ThaliTest[598:881697] THEMultipeerSession stopping peer
2016-02-03 22:17:40.655 ThaliTest[598:881697] multipeer session: stop timer
2016-02-03 22:17:40.656 Th,aliTest[598:881697] jxcore: stopBroadcasting: success
ok 61 Should be able to call stopBroadcasting without error

,2016-02-03 22:17:40.659 ThaliTest[598:881697] jxcore: startBroadcasting
,2016-02-03 22:17:40.663 ThaliTest[598:881697] server: starting 1454534260657.598.cUEWig==
2016-02-03 22:17:40.664 ThaliTest[598:881697] multipeer session: start timer: 0x15e14cf0
2016-02-03 22:17:40.664 ThaliTest[598:881697] THEMultipeerSession initializ,ed peer 1454534260657.598
2016-02-03 22:17:40.665 ThaliTest[598:881697] jxcore: startBroadcasting: success
ok 62 Should be able to call startBroadcasting without error

2016-02-03 22:17:40.667 ThaliTest[598:881697] jxcore: stopBroadcasting
,2016-02-03 22:17:40.667 ThaliTest[598:881697] THEMultipeerSession stopping peer
2016-02-03 22:17:40.667 ThaliTest[598:881697] multipeer session: stop timer
,2016-02-03 22:17:40.668 ThaliTest[598:881697] jxcore: stopBroadcasting: success
,ok 63 Should be able to call stopBroadcasting without error

2016-02-03 22:17:40.671 ThaliTest[598:881697] jxcore: startBroadcasting
,2016-02-03 22:17:40.676 ThaliTest[598:881697] server: starting 1454534260670.598.vMxZ8g==
2016-02-03 22:17:40.678 ThaliTest[598:881697] multipeer session: start timer: 0x17b4c110
2016-02-03 22:17:40.678 ThaliTest[598:881697] THEMultipeerSession initializ,ed peer 1454534260670.598
2016-02-03 22:17:40.678 ThaliTest[598:881697] jxcore: startBroadcasting: success
ok 64 Should be able to call startBroadcasting without error

,2016-02-03 22:17:40.680 ThaliTest[598:881697] jxcore: stopBroadcasting
,2016-02-03 22:17:40.685 ThaliTest[598:881697] THEMultipeerSession stopping peer
,2016-02-03 22:17:40.686 ThaliTest[598:881697] multipeer session: stop timer
,2016-02-03 22:17:40.687 ThaliTest[598:881697] jxcore: stopBroadcasting: success
,ok 65 Should be able to call stopBroadcasting without error
,
,2016-02-03 22:17:40.692 ThaliTest[598:881697] jxcore: startBroadcasting
,2016-02-03 22:17:40.694 ThaliTest[598:881697] server: starting 1454534260691.598.uLrc+g==
,2016-02-03 22:17:40.695 ThaliTest[598:881697] multipeer session: start timer: 0x17b4bd70
,2016-02-03 22:17:40.695 ThaliTest[598:881697] THEMultipeerSession initialized peer 1454534260691.598
,2016-02-03 22:17:40.697 ThaliTest[598:881697] jxcore: startBroadcasting: success
,ok 66 Should be able to call startBroadcasting without error

,2016-02-03 22:17:40.701 ThaliTest[598:881697] jxcore: stopBroadcasting
,2016-02-03 22:17:40.701 ThaliTest[598:881697] THEMultipeerSession stopping peer
,2016-02-03 22:17:40.702 ThaliTest[598:881697] multipeer session: stop timer
,2016-02-03 22:17:40.702 ThaliTest[598:881697] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error

,2016-02-03 22:17:40.706 ThaliTest[598:881697] jxcore: startBroadcasting
,2016-02-03 22:17:40.708 ThaliTest[598:881697] server: starting 1454534260705.598.ELMz6Q==
,2016-02-03 22:17:40.709 ThaliTest[598:881697] multipeer session: start timer: 0x15e17200
,2016-02-03 22:17:40.711 ThaliTest[598:881697] THEMultipeerSession initialized peer 1454534260705.598
,2016-02-03 22:17:40.712 ThaliTest[598:881697] jxcore: startBroadcasting: success
,ok 68 Should be able to call startBroadcasting without error

,2016-02-03 22:17:40.715 ThaliTest[598:881697] jxcore: stopBroadcasting
,2016-02-03 22:17:40.716 ThaliTest[598:881697] THEMultipeerSession stopping peer
,2016-02-03 22:17:40.716 ThaliTest[598:881697] multipeer session: stop timer
,2016-02-03 22:17:40.717 ThaliTest[598:881697] jxcore: stopBroadcasting: success
,ok 69 Should be able to call stopBroadcasting without error

,2016-02-03 22:17:40.721 ThaliTest[598:881697] jxcore: startBroadcasting
,2016-02-03 22:17:40.723 ThaliTest[598:881697] server: starting 1454534260720.598.1klU+g==
,2016-02-03 22:17:40.724 ThaliTest[598:881697] multipeer session: start timer: 0x15e16df0
,2016-02-03 22:17:40.726 ThaliTest[598:881697] THEMultipeerSession initialized peer 1454534260720.598
,2016-02-03 22:17:40.728 ThaliTest[598:881697] jxcore: startBroadcasting: success
,ok 70 Should be able to call startBroadcasting without error

2016-02-03 22:17:40.730 ThaliTest[598:881697] jxcore: stopBroadcasting
2016-02-03 22:17:40.731 ThaliTest[598:881697] THEMultipeerSession stopping peer
2016-02-03 22:17:40.731 ThaliTest[598:8,81697] multipeer session: stop timer
,2016-02-03 22:17:40.732 ThaliTest[598:881697] jxcore: stopBroadcasting: success
,ok 71 Should be able to call stopBroadcasting without error
,
,2016-02-03 22:17:40.736 ThaliTest[598:881697] jxcore: startBroadcasting
,2016-02-03 22:17:40.738 ThaliTest[598:881697] server: starting 1454534260735.598.tsOGtQ==
,2016-02-03 22:17:40.739 ThaliTest[598:881697] multipeer session: start timer: 0x17f0ad50
,2016-02-03 22:17:40.740 ThaliTest[598:881697] THEMultipeerSession initialized peer 1454534260735.598
,2016-02-03 22:17:40.742 ThaliTest[598:881697] jxcore: startBroadcasting: success
,ok 72 Should be able to call startBroadcasting without error

,2016-02-03 22:17:40.745 ThaliTest[598:881697] jxcore: stopBroadcasting
,2016-02-03 22:17:40.746 ThaliTest[598:881697] THEMultipeerSession stopping peer
,2016-02-03 22:17:40.746 ThaliTest[598:881697] multipeer session: stop timer
,2016-02-03 22:17:40.748 ThaliTest[598:881697] jxcore: stopBroadcasting: success
,ok 73 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,# teardown

,2016-02-03 22:17:58.216 ThaliTest[598:881697] jxcore: startBroadcasting
,2016-02-03 22:17:58.220 ThaliTest[598:881697] server: starting 1454534278216.598.8qlRXQ==
,2016-02-03 22:17:58.221 ThaliTest[598:881697] multipeer session: start timer: 0x18fcaa80
,2016-02-03 22:17:58.221 ThaliTest[598:881697] THEMultipeerSession initialized peer 1454534278216.598
2016-02-03 22:17:58.222 ThaliTest[598:881697] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error

,2016-02-03 22:17:58.225 ThaliTest[598:881697] jxcore: startBroadcasting
,2016-02-03 22:17:58.226 ThaliTest[598:881697] jxcore: startBroadcasting: failure
ok 75 Cannot call startBroadcasting twice

,2016-02-03 22:17:58.233 ThaliTest[598:881697] jxcore: stopBroadcasting
,2016-02-03 22:17:58.234 ThaliTest[598:881697] THEMultipeerSession stopping peer
,2016-02-03 22:17:58.234 ThaliTest[598:881697] multipeer session: stop timer
,2016-02-03 22:17:58.235 ThaliTest[598:881697] jxcore: stopBroadcasting: success
ok 76 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on connection to bad peer

,# teardown

,2016-02-03 22:18:02.614 ThaliTest[598:881697] jxcore: startBroadcasting
,2016-02-03 22:18:02.618 ThaliTest[598:881697] server: starting 1454534282614.598.85NiUQ==
2016-02-03 22:18:02.618 ThaliTest[598:881697] multipeer session: start timer: 0x18bd4ac0
,2016-02-03 22:18:02.619 ThaliTest[598:881697] THEMultipeerSession initialized peer 1454534282614.598
2016-02-03 22:18:02.620 ThaliTest[598:881697] jxcore: startBroadcasting: success
ok 77 Should be able to call startBroadcasting without error

,2016-02-03 22:18:02.622 ThaliTest[598:881697] jxcore: connect foobar
,2016-02-03 22:18:02.623 ThaliTest[598:881697] client: unknown peer foobar
2016-02-03 22:18:02.623 ThaliTest[598:881697] jxcore: connect: fail: Unknown peer
,ok 78 Should not connect to a bad peer

2016-02-03 22:18:02.629 ThaliTest[598:881697] jxcore: stopBroadcasting
,2016-02-03 22:18:02.629 ThaliTest[598:881697] THEMultipeerSession stopping peer
,2016-02-03 22:18:02.630 ThaliTest[598:881697] multipeer session: stop timer
2016-02-03 22:18:02.631 ThaliTest[598:881697] jxcore: stopBroadcasting: success
,ok 79 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on disconnect to bad peer

,# teardown

,2016-02-03 22:18:03.456 ThaliTest[598:881697] jxcore: startBroadcasting
,2016-02-03 22:18:03.459 ThaliTest[598:881697] server: starting 1454534283455.598.3iKnIQ==
,2016-02-03 22:18:03.460 ThaliTest[598:881697] multipeer session: start timer: 0x15f4bdf0
,2016-02-03 22:18:03.461 ThaliTest[598:881697] THEMultipeerSession initialized peer 1454534283455.598
,2016-02-03 22:18:03.461 ThaliTest[598:881697] jxcore: startBroadcasting: success
,ok 80 Should be able to call startBroadcasting without error

2016-02-03 22:18:03.464 ThaliTest[598:881697] jxcore: disconnect
2016-02-03 22:18:03.464 ThaliTest[598:881697] jxcore: disconnect: fail
,ok 81 Disconnect should fail to a non-existant peer 

,2016-02-03 22:18:03.473 ThaliTest[598:881697] jxcore: stopBroadcasting
2016-02-03 22:18:03.473 ThaliTest[598:881697] THEMultipeerSession stopping peer
2016-02-03 22:18:03.474 ThaliTest[598:881697] multipeer session: stop timer
2016-02-03 22:18:03.474 ThaliTest[598:881697] jxcore: stopBroadcasting: success
,ok 82 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter can discover and connect to peers

,# teardown

,2016-02-03 22:18:04.316 ThaliTest[598:881697] jxcore: startBroadcasting
,2016-02-03 22:18:04.320 ThaliTest[598:881697] server: starting 1454534284316.598.uQcXjg==
,2016-02-03 22:18:04.321 ThaliTest[598:881697] multipeer session: start timer: 0x18fdc160
2016-02-03 22:18:04.321 ThaliTest[598:881697] THEMultipeerSession initialized peer 1454534284316.598
2016-02-03 22:18:04.322 ThaliTest[598:881697] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error

,2016-02-03 22:18:05.601 ThaliTest[598:881431] multipeer session: reset timer
2016-02-03 22:18:05.601 ThaliTest[598:881431] multipeer session: stop timer
2016-02-03 22:18:05.602 ThaliTest[598:881431] multipeer session: start timer: 0x18fdc160
,2016-02-03 22:18:05.602 ThaliTest[598:881431] server session: connect
,2016-02-03 22:18:05.603 ThaliTest[598:881431] server session: stateChange:0->1 1454534282188.1180
,2016-02-03 22:18:05.609 ThaliTest[598:881431] server: accepting invitation 1454534282188.1180
,2016-02-03 22:18:05.983 ThaliTest[598:881431] client: found peer: 1454534282188.1180.uRSyDQ==
,2016-02-03 22:18:05.984 ThaliTest[598:881697] jxcore: connect 1454534282188.1180.uRSyDQ==
,2016-02-03 22:18:05.984 ThaliTest[598:881697] client session: connect
2016-02-03 22:18:05.984 ThaliTest[598:881697] client session: stateChange:0->1 1454534282188.1180.uRSyDQ==
,2016-02-03 22:18:08.455 ThaliTest[598:882166] server session: connected
,2016-02-03 22:18:08.455 ThaliTest[598:882166] server session: stateChange:1->2 1454534282188.1180
,2016-02-03 22:18:08.474 ThaliTest[598:881431] server relay: socket disconnected
,2016-02-03 22:18:08.474 ThaliTest[598:881431] server relay: 0x15f51a30 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-03 22:18:08.543 ThaliTest[598:882164] server session: not connected 1454534282188.1180
,2016-02-03 22:18:08.676 ThaliTest[598:882164] client session: connected
2016-02-03 22:18:08.677 ThaliTest[598:882164] client session: stateChange:1->2 1454534282188.1180.uRSyDQ==
,2016-02-03 22:18:08.729 ThaliTest[598:882164] client session: fireConnectCallback: 1454534282188.1180.uRSyDQ==
2016-02-03 22:18:08.730 ThaliTest[598:882164] jxcore: connect: success
,ok 84 Should be able to connect without error

,ok 85 Port should be within range

,2016-02-03 22:18:08.734 ThaliTest[598:881697] jxcore: disconnect
2016-02-03 22:18:08.735 ThaliTest[598:881697] client session: disconnectFromPeer: 1454534282188.1180.uRSyDQ==
2016-02-03 22:18:08.735 ThaliTest[598:881697] client session: disconnect
,2016-02-03 22:18:08.736 ThaliTest[598:881697] client session: stateChange:2->0 1454534282188.1180.uRSyDQ==
,2016-02-03 22:18:08.746 ThaliTest[598:881697] jxcore: disconnect: success
ok 86 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-02-03 22:18:09.038 ThaliTest[598:881697] jxcore: stopBroadcasting
,2016-02-03 22:18:09.039 ThaliTest[598:881697] THEMultipeerSession stopping peer
,2016-02-03 22:18:09.039 ThaliTest[598:881697] multipeer session: stop timer
,2016-02-03 22:18:09.041 ThaliTest[598:881697] server session: disconnect
2016-02-03 22:18:09.041 ThaliTest[598:881697] server session: stateChange:2->0 1454534282188.1180
,2016-02-03 22:18:10.129 ThaliTest[598:881697] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double connect

,# teardown

,2016-02-03 22:18:11.646 ThaliTest[598:881697] jxcore: startBroadcasting
,2016-02-03 22:18:11.650 ThaliTest[598:881697] server: starting 1454534291646.598.eA16Og==
,2016-02-03 22:18:11.650 ThaliTest[598:881697] multipeer session: start timer: 0x18d88ce0
2016-02-03 22:18:11.651 ThaliTest[598:881697] THEMultipeerSession initialized peer 1454534291646.598
2016-02-03 22:18:11.652 ThaliTest[598:881697] jxcore: startBroadcasting: success
,ok 87 Should be able to call startBroadcasting without error

,2016-02-03 22:18:11.664 ThaliTest[598:881431] client: found peer: 1454534282188.1180.uRSyDQ==
,2016-02-03 22:18:11.667 ThaliTest[598:881697] jxcore: connect 1454534282188.1180.uRSyDQ==
2016-02-03 22:18:11.667 ThaliTest[598:881697] client session: connect
2016-02-03 22:18:11.668 ThaliTest[598:881697] client session: stateChange:0->1 1454534282188.1180.uRSyDQ==
,2016-02-03 22:18:12.865 ThaliTest[598:881431] multipeer session: reset timer
,2016-02-03 22:18:12.865 ThaliTest[598:881431] multipeer session: stop timer
2016-02-03 22:18:12.866 ThaliTest[598:881431] multipeer session: start timer: 0x18d88ce0
,2016-02-03 22:18:12.866 ThaliTest[598:881431] server session: connect
2016-02-03 22:18:12.867 ThaliTest[598:881431] server session: stateChange:0->1 1454534289458.1180
,2016-02-03 22:18:12.873 ThaliTest[598:881431] server: accepting invitation 1454534289458.1180
,2016-02-03 22:18:12.963 ThaliTest[598:881431] client: found peer: 1454534289458.1180.cy09Hg==
2016-02-03 22:18:12.964 ThaliTest[598:881697] jxcore: connect 1454534289458.1180.cy09Hg==
2016-02-03 22:18:12.965 ThaliTest[598:881697] client session: connect
,2016-02-03 22:18:12.965 ThaliTest[598:881697] client session: stateChange:0->1 1454534289458.1180.cy09Hg==
,2016-02-03 22:18:15.626 ThaliTest[598:882230] server session: connected
2016-02-03 22:18:15.626 ThaliTest[598:882230] server session: stateChange:1->2 1454534289458.1180
,2016-02-03 22:18:15.652 ThaliTest[598:881431] server relay: socket disconnected
,2016-02-03 22:18:15.652 ThaliTest[598:881431] server relay: 0x17b7a920 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-03 22:18:15.697 ThaliTest[598:882230] server session: not connected 1454534289458.1180
,2016-02-03 22:18:15.921 ThaliTest[598:882230] client session: connected
,2016-02-03 22:18:15.922 ThaliTest[598:882230] client session: stateChange:1->2 1454534289458.1180.cy09Hg==
,2016-02-03 22:18:15.941 ThaliTest[598:882165] client session: fireConnectCallback: 1454534289458.1180.cy09Hg==
2016-02-03 22:18:15.941 ThaliTest[598:882165] jxcore: connect: success
,ok 88 Should be able to connect without error

,ok 89 Port should be within range

,2016-02-03 22:18:15.946 ThaliTest[598:881697] jxcore: connect 1454534289458.1180.cy09Hg==
,2016-02-03 22:18:15.947 ThaliTest[598:881697] client: already connect(ing/ed) to 1454534289458.1180.cy09Hg==
2016-02-03 22:18:15.947 ThaliTest[598:881697] jxcore: connect: fail: Aleady connecting
,ok 90 Should fail on double connect

,2016-02-03 22:18:15.951 ThaliTest[598:881697] jxcore: disconnect
,2016-02-03 22:18:15.952 ThaliTest[598:881697] client session: disconnectFromPeer: 1454534289458.1180.cy09Hg==
,2016-02-03 22:18:15.952 ThaliTest[598:881697] client session: disconnect
,2016-02-03 22:18:15.953 ThaliTest[598:881697] client session: stateChange:2->0 1454534289458.1180.cy09Hg==
,2016-02-03 22:18:15.962 ThaliTest[598:881697] jxcore: disconnect: success
ok 91 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-02-03 22:18:16.346 ThaliTest[598:881697] jxcore: stopBroadcasting
,2016-02-03 22:18:16.346 ThaliTest[598:881697] THEMultipeerSession stopping peer
,2016-02-03 22:18:16.347 ThaliTest[598:881697] multipeer session: stop timer
,2016-02-03 22:18:16.348 ThaliTest[598:881697] client session: disconnect
2016-02-03 22:18:16.348 ThaliTest[598:881697] client session: stateChange:1->0 1454534282188.1180.uRSyDQ==
,2016-02-03 22:18:16.350 ThaliTest[598:881697] server session: disconnect
2016-02-03 22:18:16.350 ThaliTest[598:881697] server session: stateChange:2->0 1454534289458.1180
,2016-02-03 22:18:17.367 ThaliTest[598:881697] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,# teardown

,2016-02-03 22:18:17.684 ThaliTest[598:881697] jxcore: startBroadcasting
,2016-02-03 22:18:17.688 ThaliTest[598:881697] server: starting 1454534297684.598.n04Wpg==
,2016-02-03 22:18:17.689 ThaliTest[598:881697] multipeer session: start timer: 0x17b7e600
2016-02-03 22:18:17.689 ThaliTest[598:881697] THEMultipeerSession initialized peer 1454534297684.598
2016-02-03 22:18:17.689 ThaliTest[598:881697] jxcore: startBroad,casting: success
ok 92 Should be able to call startBroadcasting without error

,2016-02-03 22:18:17.930 ThaliTest[598:881431] client: found peer: 1454534289458.1180.cy09Hg==
,2016-02-03 22:18:17.933 ThaliTest[598:881697] jxcore: connect 1454534289458.1180.cy09Hg==
2016-02-03 22:18:17.933 ThaliTest[598:881697] client session: connect
,2016-02-03 22:18:17.934 ThaliTest[598:881697] client session: stateChange:0->1 1454534289458.1180.cy09Hg==
,2016-02-03 22:18:18.631 ThaliTest[598:881431] client: found peer: 1454534295531.1180.5UGSbA==
,2016-02-03 22:18:18.633 ThaliTest[598:881697] jxcore: connect 1454534295531.1180.5UGSbA==
2016-02-03 22:18:18.633 ThaliTest[598:881697] client session: connect
2016-02-03 22:18:18.634 ThaliTest[598:881697] client session: stateChange:0->1 1454534295531.1180.5UGSbA==
,2016-02-03 22:18:19.062 ThaliTest[598:881431] multipeer session: reset timer
2016-02-03 22:18:19.062 ThaliTest[598:881431] multipeer session: stop timer
,2016-02-03 22:18:19.063 ThaliTest[598:881431] multipeer session: start timer: 0x17b7e600
2016-02-03 22:18:19.063 ThaliTest[598:881431] server session: connect
2016-02-03 22:18:19.063 ThaliTest[598:881431] server session: stateChange:0->1 1454534295531.1180
,2016-02-03 22:18:19.071 ThaliTest[598:881431] server: accepting invitation 1454534295531.1180
,2016-02-03 22:18:21.735 ThaliTest[598:882257] client session: connected
2016-02-03 22:18:21.736 ThaliTest[598:882257] client session: stateChange:1->2 1454534295531.1180.5UGSbA==
,2016-02-03 22:18:21.768 ThaliTest[598:882230] client session: fireConnectCallback: 1454534295531.1180.5UGSbA==
2016-02-03 22:18:21.768 ThaliTest[598:882230] jxcore: connect: success
,ok 93 Should be able to connect without error

ok 94 Port should be within range

2016-02-03 22:18:21.774 ThaliTest[598:881697] jxcore: disconnect
2016-02-03 22:18:21.774 ThaliTest[598:881697] client session: disconnectFromPeer: 1454534295531.1180.5UGSbA==
,2016-02-03 22:18:21.775 ThaliTest[598:881697] client session: disconnect
2016-02-03 22:18:21.776 ThaliTest[598:881697] client session: stateChange:2->0 1454534295531.1180.5UGSbA==
,2016-02-03 22:18:21.792 ThaliTest[598:881697] jxcore: disconnect: success
,ok 95 Should be able to disconnect without error

,2016-02-03 22:18:21.794 ThaliTest[598:881697] jxcore: disconnect
,2016-02-03 22:18:21.794 ThaliTest[598:881697] jxcore: disconnect: fail
,ok 96 Disconnect should fail 

setting stopBroadcasting callback and ending test.

,# setup

,2016-02-03 22:18:21.826 ThaliTest[598:882165] server session: connected
,2016-02-03 22:18:21.826 ThaliTest[598:882165] server session: stateChange:1->2 1454534295531.1180
,2016-02-03 22:18:21.830 ThaliTest[598:881431] server relay: socket disconnected
,2016-02-03 22:18:21.831 ThaliTest[598:881431] server relay: 0x15e60c60 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-03 22:18:21.856 ThaliTest[598:882237] server session: not connected 1454534295531.1180
,calling stopBroadcasting

,2016-02-03 22:18:22.119 ThaliTest[598:881697] jxcore: stopBroadcasting
,2016-02-03 22:18:22.119 ThaliTest[598:881697] THEMultipeerSession stopping peer
2016-02-03 22:18:22.119 ThaliTest[598:881697] multipeer session: stop timer
,2016-02-03 22:18:22.120 ThaliTest[598:881697] client session: disconnect
2016-02-03 22:18:22.120 ThaliTest[598:881697] client session: stateChange:1->0 1454534289458.1180.cy09Hg==
2016-02-03 22:18:22.121 ThaliTest[598:881697] server session: disconnect
,2016-02-03 22:18:22.121 ThaliTest[598:881697] server session: stateChange:2->0 1454534295531.1180
2016-02-03 22:18:22.122 ThaliTest[598:881697] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can connect and send data

,# teardown

,echo server started on port: 52707

,2016-02-03 22:18:23.130 ThaliTest[598:881697] jxcore: startBroadcasting
,2016-02-03 22:18:23.131 ThaliTest[598:881697] server: starting 1454534303130.598.IIkLGw==
,2016-02-03 22:18:23.131 ThaliTest[598:881697] multipeer session: start timer: 0x17d8a6f0
2016-02-03 22:18:23.132 ThaliTest[598:881697] THEMultipeerSession initialized peer 1454534303130.598
2016-02-03 22:18:23.132 ThaliTest[598:881697] jxcore: startBroadcasting: success
,ok 97 Should be able to call startBroadcasting without error

,2016-02-03 22:18:23.877 ThaliTest[598:881431] client: found peer: 1454534295531.1180.5UGSbA==
,2016-02-03 22:18:23.879 ThaliTest[598:881697] jxcore: connect 1454534295531.1180.5UGSbA==
2016-02-03 22:18:23.879 ThaliTest[598:881697] client session: connect
2016-02-03 22:18:23.880 ThaliTest[598:881697] client session: stateChange:0->1 1454534295531.1180.5UGSbA==
,2016-02-03 22:18:24.298 ThaliTest[598:881431] client: found peer: 1454534301085.1180.7aLCCw==
,2016-02-03 22:18:24.299 ThaliTest[598:881697] jxcore: connect 1454534301085.1180.7aLCCw==
2016-02-03 22:18:24.300 ThaliTest[598:881697] client session: connect
2016-02-03 22:18:24.300 ThaliTest[598:881697] client session: stateChange:0->1 1454534301085.1180.7aLCCw==
,2016-02-03 22:18:24.345 ThaliTest[598:881431] multipeer session: reset timer
2016-02-03 22:18:24.346 ThaliTest[598:881431] multipeer session: stop timer
2016-02-03 22:18:24.346 ThaliTest[598:881431] multipeer session: start timer: 0x17d8a6f0
2016-02-03 ,22:18:24.346 ThaliTest[598:881431] server session: connect
2016-02-03 22:18:24.347 ThaliTest[598:881431] server session: stateChange:0->1 1454534301085.1180
,2016-02-03 22:18:24.354 ThaliTest[598:881431] server: accepting invitation 1454534301085.1180
,2016-02-03 22:18:25.897 ThaliTest[598:881431] client: lost peer: 1454534295531.1180.5UGSbA==
2016-02-03 22:18:25.897 ThaliTest[598:881431] client session: onPeerLost: 1454534295531.1180.5UGSbA==
,2016-02-03 22:18:25.897 ThaliTest[598:881431] client session: onLinkFailure: 1454534295531.1180.5UGSbA==
,2016-02-03 22:18:25.897 ThaliTest[598:881431] client session: disconnect
2016-02-03 22:18:25.897 ThaliTest[598:881431] client session: stateChange:1->0 1454534295531.1180.5UGSbA==
,2016-02-03 22:18:25.898 ThaliTest[598:881431] client session: fireConnectCallback: 1454534295531.1180.5UGSbA==
2016-02-03 22:18:25.898 ThaliTest[598:881431] jxcore: connect: fail: Peer disconnected
,2016-02-03 22:18:26.908 ThaliTest[598:881697] jxcore: connect 1454534295531.1180.5UGSbA==
,2016-02-03 22:18:26.908 ThaliTest[598:881697] client: connect: unreachable 1454534295531.1180.5UGSbA==
,2016-02-03 22:18:26.909 ThaliTest[598:881697] jxcore: connect: fail: Peer unreachable
,2016-02-03 22:18:27.206 ThaliTest[598:882230] client session: connected
2016-02-03 22:18:27.207 ThaliTest[598:882230] client session: stateChange:1->2 1454534301085.1180.7aLCCw==
,2016-02-03 22:18:27.217 ThaliTest[598:882230] client session: fireConnectCallback: 1454534301085.1180.7aLCCw==
2016-02-03 22:18:27.217 ThaliTest[598:882230] jxcore: connect: success
,ok 98 Should be able to connect without error

,ok 99 Port should be within range

,2016-02-03 22:18:27.223 ThaliTest[598:881431] client: relay established
2016-02-03 22:18:27.224 ThaliTest[598:881431] client: new accepted socket: 0x18da9a50
,data in 6570

,data in 10950

,data in 13140

,2016-02-03 22:18:27.379 ThaliTest[598:882230] server session: connected
2016-02-03 22:18:27.380 ThaliTest[598:882230] server session: stateChange:1->2 1454534301085.1180
data in 18615

,data in 31755

,2016-02-03 22:18:27.397 ThaliTest[598:881431] server relay: connected (to port: 52707)
,data in 36135

,data in 42705

,data in 43800

,data in 54750

,data in 61320

,data in 67819

,data in 70080

,data in 76650

,data in 94170

,data in 110625

,data in 131072

,ok 100 the test messages should be equal

,2016-02-03 22:18:27.637 ThaliTest[598:881697] jxcore: disconnect
,2016-02-03 22:18:27.638 ThaliTest[598:881697] client session: disconnectFromPeer: 1454534301085.1180.7aLCCw==
,2016-02-03 22:18:27.638 ThaliTest[598:881697] client session: disconnect
,2016-02-03 22:18:27.638 ThaliTest[598:881697] client session: stateChange:2->0 1454534301085.1180.7aLCCw==
,2016-02-03 22:18:27.646 ThaliTest[598:881697] jxcore: disconnect: success
,ok 101 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,2016-02-03 22:18:27.779 ThaliTest[598:882257] server session: not connected 1454534301085.1180
,calling stopBroadcasting

,2016-02-03 22:18:27.825 ThaliTest[598:881697] jxcore: stopBroadcasting
,2016-02-03 22:18:27.825 ThaliTest[598:881697] THEMultipeerSession stopping peer
,2016-02-03 22:18:27.826 ThaliTest[598:881697] multipeer session: stop timer
,2016-02-03 22:18:27.827 ThaliTest[598:881697] server session: disconnect
2016-02-03 22:18:27.828 ThaliTest[598:881697] server session: stateChange:2->0 1454534301085.1180
,2016-02-03 22:18:27.837 ThaliTest[598:881697] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter handles socket disconnect correctly

,# teardown

,echo server started on port: 52714

,2016-02-03 22:18:28.364 ThaliTest[598:881697] jxcore: startBroadcasting
,2016-02-03 22:18:28.368 ThaliTest[598:881697] server: starting 1454534308363.598.4OoMyA==
,2016-02-03 22:18:28.369 ThaliTest[598:881697] multipeer session: start timer: 0x15d26ad0
2016-02-03 22:18:28.369 ThaliTest[598:881697] THEMultipeerSession initialized peer 1454534308363.598
2016-02-03 22:18:28.369 ThaliTest[598:881697] jxcore: startBroadcasting: success
,ok 102 Should be able to call startBroadcasting without error

,2016-02-03 22:18:29.509 ThaliTest[598:881431] client: found peer: 1454534306236.1180.0UHTVQ==
,[{"peerIdentifier":"1454534306236.1180.0UHTVQ==","peerName":"(null)","peerAvailable":true}]

,2016-02-03 22:18:29.512 ThaliTest[598:881697] jxcore: connect 1454534306236.1180.0UHTVQ==
,2016-02-03 22:18:29.513 ThaliTest[598:881697] client session: connect
,2016-02-03 22:18:29.513 ThaliTest[598:881697] client session: stateChange:0->1 1454534306236.1180.0UHTVQ==
,2016-02-03 22:18:29.974 ThaliTest[598:881431] multipeer session: reset timer
2016-02-03 22:18:29.974 ThaliTest[598:881431] multipeer session: stop timer
2016-02-03 22:18:29.974 ThaliTest[598:881431] multipeer session: start timer: 0x15d26ad0
2016-02-03 22:18:29.974 ThaliTest[598:881431] server session: connect
2016-02-03 22:18:29.974 ThaliTest[598:881431] server session: stateChange:0->1 1454534306236.1180
,2016-02-03 22:18:29.979 ThaliTest[598:881431] server: accepting invitation 1454534306236.1180
,2016-02-03 22:18:33.182 ThaliTest[598:882237] server session: connected
2016-02-03 22:18:33.182 ThaliTest[598:882237] server session: stateChange:1->2 1454534306236.1180
,2016-02-03 22:18:33.189 ThaliTest[598:881431] server relay: connected (to port: 52714)
,2016-02-03 22:18:33.322 ThaliTest[598:882165] server session: not connected 1454534306236.1180
,2016-02-03 22:18:33.444 ThaliTest[598:881431] multipeer session: reset timer
,2016-02-03 22:18:33.445 ThaliTest[598:881431] multipeer session: stop timer
2016-02-03 22:18:33.445 ThaliTest[598:881431] multipeer session: start timer: 0x15d26ad0
,2016-02-03 22:18:33.446 ThaliTest[598:881431] server: disconnecting to refresh session (1454534306236.1180)
2016-02-03 22:18:33.446 ThaliTest[598:881431] server session: disconnect
,2016-02-03 22:18:33.446 ThaliTest[598:881431] server session: stateChange:2->0 1454534306236.1180
,2016-02-03 22:18:33.450 ThaliTest[598:881431] server session: connect
2016-02-03 22:18:33.450 ThaliTest[598:881431] server session: stateChange:0->1 1454534306236.1180
,2016-02-03 22:18:33.464 ThaliTest[598:881431] server: accepting invitation 1454534306236.1180
,2016-02-03 22:18:36.339 ThaliTest[598:882166] server session: connected
2016-02-03 22:18:36.339 ThaliTest[598:882166] server session: stateChange:1->2 1454534306236.1180
,2016-02-03 22:18:36.344 ThaliTest[598:881431] server relay: connected (to port: 52714)
,2016-02-03 22:18:36.519 ThaliTest[598:882165] server session: not connected 1454534306236.1180
,2016-02-03 22:18:39.704 ThaliTest[598:882230] client session: connected
2016-02-03 22:18:39.704 ThaliTest[598:882230] client session: stateChange:1->2 1454534306236.1180.0UHTVQ==
,2016-02-03 22:18:39.708 ThaliTest[598:882230] client session: fireConnectCallback: 1454534306236.1180.0UHTVQ==
2016-02-03 22:18:39.708 ThaliTest[598:882230] jxcore: connect: success
,ok 103 Should be able to connect without error

,ok 104 Port should be within range

,ok 105 First connect should succeed

,2016-02-03 22:18:39.744 ThaliTest[598:881431] client: relay established
2016-02-03 22:18:39.745 ThaliTest[598:881431] client: new accepted socket: 0x17b61f00
,ok 106 the test messages should be equal

,ok 107 First send should succeed

,2016-02-03 22:18:40.884 ThaliTest[598:881431] client: socket closed
,2016-02-03 22:18:40.884 ThaliTest[598:881431] client relay: socket disconnected
,2016-02-03 22:18:40.885 ThaliTest[598:881431] client relay: 0x17b61f00 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-02-03 22:18:40,.885 ThaliTest[598:881431] client session: socket closed: 1454534306236.1180.0UHTVQ==
2016-02-03 22:18:40.885 ThaliTest[598:881431] client session: onLinkFailure: 1454534306236.1180.0UHTVQ==
,2016-02-03 22:18:40.885 ThaliTest[598:881431] client session: disconnect
2016-02-03 22:18:40.886 ThaliTest[598:881431] client session: stateChange:2->0 1454534306236.1180.0UHTVQ==
,2016-02-03 22:18:40.891 ThaliTest[598:881431] client session: fireConnectionErrorEvent: 1454534306236.1180.0UHTVQ==
,2016-02-03 22:18:40.897 ThaliTest[598:881697] jxcore: connect 1454534306236.1180.0UHTVQ==
2016-02-03 22:18:40.897 ThaliTest[598:881697] client session: connect
2016-02-03 22:18:40.897 ThaliTest[598:881697] client session: stateChange:0->1 1454534306236.1180.0UHTVQ==
,2016-02-03 22:18:43.362 ThaliTest[598:882257] client session: connected
,2016-02-03 22:18:43.362 ThaliTest[598:882257] client session: stateChange:1->2 1454534306236.1180.0UHTVQ==
,2016-02-03 22:18:43.427 ThaliTest[598:882166] client session: fireConnectCallback: 1454534306236.1180.0UHTVQ==
2016-02-03 22:18:43.427 ThaliTest[598:882166] jxcore: connect: success
,ok 108 Should be able to connect without error

,ok 109 Port should be within range

,ok 110 Second connect should succeed

,2016-02-03 22:18:43.461 ThaliTest[598:881431] client: relay established
2016-02-03 22:18:43.462 ThaliTest[598:881431] client: new accepted socket: 0x18daa8c0
,ok 111 the test messages should be equal

,ok 112 Second send should succeed

,# setup

,2016-02-03 22:18:44.234 ThaliTest[598:881431] client: socket closed
2016-02-03 22:18:44.235 ThaliTest[598:881431] client relay: socket disconnected
,2016-02-03 22:18:44.235 ThaliTest[598:881431] client relay: 0x18daa8c0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2016-02-03 22:18:44.235 ThaliTest[598:881431] client session: socket closed: 1454534306236.1180.0UHTVQ==
,2016-02-03 22:18:44.236 ThaliTest[598:881431] client session: onLinkFailure: 1454534306236.1180.0UHTVQ==
2016-02-03 22:18:44.236 ThaliTest[598:881431] client session: disconnect
,2016-02-03 22:18:44.237 ThaliTest[598:881431] client session: stateChange:2->0 1454534306236.1180.0UHTVQ==
,2016-02-03 22:18:44.246 ThaliTest[598:881431] client session: fireConnectionErrorEvent: 1454534306236.1180.0UHTVQ==
,calling stopBroadcasting

,2016-02-03 22:18:44.592 ThaliTest[598:881697] jxcore: stopBroadcasting
,2016-02-03 22:18:44.592 ThaliTest[598:881697] THEMultipeerSession stopping peer
,2016-02-03 22:18:44.593 ThaliTest[598:881697] multipeer session: stop timer
,2016-02-03 22:18:44.594 ThaliTest[598:881697] server session: disconnect
2016-02-03 22:18:44.594 ThaliTest[598:881697] server session: stateChange:2->0 1454534306236.1180
,2016-02-03 22:18:44.603 ThaliTest[598:881697] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliReplicationManager can call start without error

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/608C14D9-0CA6-49B8-9822-3FAA888CDDF9/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,ok 113 starting event should occur in right order

,2016-02-03 22:18:45.270 ThaliTest[598:881697] jxcore: startBroadcasting
,2016-02-03 22:18:45.271 ThaliTest[598:881697] server: starting RfVTpOnuy1VqRfzzLJX7oA.x9hpYw==
,2016-02-03 22:18:45.271 ThaliTest[598:881697] multipeer session: start timer: 0x18ccd9e0
2016-02-03 22:18:45.271 ThaliTest[598:881697] THEMultipeerSession initialized peer RfVTpOnuy1VqRfzzLJX7oA
2016-02-03 22:18:45.271 ThaliTest[598:881697] jxcore: startBroadcasting: success
,ok 114 started event should occur in right order

,Now in TRM stop

,State of this._isStarted: true

,ok 115 stopping event should occur in right order

About to call stopBroadcasting

,2016-02-03 22:18:45.273 ThaliTest[598:881697] jxcore: stopBroadcasting
2016-02-03 22:18:45.274 ThaliTest[598:881697] THEMultipeerSession stopping peer
2016-02-03 22:18:45.274 ThaliTest[598:881697] multipeer session: stop timer
2016-02-03 22:18:45.274 ThaliTest[598:881697] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,ok 116 stopped event should occur in right order

,mux server bridge listener closed

# setup

,# ThaliReplicationManager receives identity

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/608C14D9-0CA6-49B8-9822-3FAA888CDDF9/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-02-03 22:18:45.609 ThaliTest[598:881697] jxcore: startBroadcasting
,2016-02-03 22:18:45.611 ThaliTest[598:881697] server: starting RfVTpOnuy1VqRfzzLJX7oA.LE+Y7w==
,2016-02-03 22:18:45.612 ThaliTest[598:881697] multipeer session: start timer: 0x18ccc660
2016-02-03 22:18:45.612 ThaliTest[598:881697] THEMultipeerSession initialized peer RfVTpOnuy1VqRfzzLJX7oA
2016-02-03 22:18:45.612 ThaliTest[598:881697] jxcore: start,Broadcasting: success
ok 117 getDeviceIdentity should not return an error

ok 118 deviceName should not be null

,Now in TRM stop

,State of this._isStarted: true

,About to call stopBroadcasting

,2016-02-03 22:18:45.616 ThaliTest[598:881697] jxcore: stopBroadcasting
2016-02-03 22:18:45.616 ThaliTest[598:881697] THEMultipeerSession stopping peer
2016-02-03 22:18:45.616 ThaliTest[598:881697] multipeer session: stop timer
2016-02-03 22:18:45.617 ThaliTest[598:881697] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,mux server bridge listener closed

,# setup

,# ThaliReplicationManager replicates database

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/608C14D9-0CA6-49B8-9822-3FAA888CDDF9/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-02-03 22:18:48.276 ThaliTest[598:881697] jxcore: startBroadcasting
,2016-02-03 22:18:48.277 ThaliTest[598:881697] server: starting RfVTpOnuy1VqRfzzLJX7oA.vAy9QQ==
,2016-02-03 22:18:48.277 ThaliTest[598:881697] multipeer session: start timer: 0x18c0a240
,2016-02-03 22:18:48.278 ThaliTest[598:881697] THEMultipeerSession initialized peer RfVTpOnuy1VqRfzzLJX7oA
,2016-02-03 22:18:48.278 ThaliTest[598:881697] jxcore: startBroadcasting: success
,ok 119 getDeviceIdentity should not return an error

ok 120 deviceName should not be null

,2016-02-03 22:18:49.262 ThaliTest[598:881431] client: found peer: 1454534306236.1180.0UHTVQ==
,2016-02-03 22:18:52.331 ThaliTest[598:881431] client: found peer: 2F-swrW2aUDGTp7z2s7leA.YrziBg==
,2016-02-03 22:18:52.370 ThaliTest[598:881697] jxcore: connect 1454534306236.1180.0UHTVQ==
2016-02-03 22:18:52.370 ThaliTest[598:881697] client session: connect
2016-02-03 22:18:52.371 ThaliTest[598:881697] client session: stateChange:0->1 1454534306236.1180.0UHTVQ==
,2016-02-03 22:18:52.374 ThaliTest[598:881697] jxcore: connect 2F-swrW2aUDGTp7z2s7leA.YrziBg==
2016-02-03 22:18:52.374 ThaliTest[598:881697] client session: connect
,2016-02-03 22:18:52.374 ThaliTest[598:881697] client session: stateChange:0->1 2F-swrW2aUDGTp7z2s7leA.YrziBg==
,ok 121 Should be able to put doc without error

,ok 122 1st change of local doc should contain local id

,2016-02-03 22:18:53.166 ThaliTest[598:881431] multipeer session: reset timer
,2016-02-03 22:18:53.167 ThaliTest[598:881431] multipeer session: stop timer
,2016-02-03 22:18:53.167 ThaliTest[598:881431] multipeer session: start timer: 0x18c0a240
,2016-02-03 22:18:53.167 ThaliTest[598:881431] server session: connect
,2016-02-03 22:18:53.168 ThaliTest[598:881431] server session: stateChange:0->1 2F-swrW2aUDGTp7z2s7leA
,2016-02-03 22:18:53.176 ThaliTest[598:881431] server: accepting invitation 2F-swrW2aUDGTp7z2s7leA
,2016-02-03 22:18:56.512 ThaliTest[598:882165] client session: connected
2016-02-03 22:18:56.513 ThaliTest[598:882165] client session: stateChange:1->2 2F-swrW2aUDGTp7z2s7leA.YrziBg==
,2016-02-03 22:18:56.536 ThaliTest[598:882453] client session: fireConnectCallback: 2F-swrW2aUDGTp7z2s7leA.YrziBg==
2016-02-03 22:18:56.537 ThaliTest[598:882453] jxcore: connect: success
,2016-02-03 22:18:56.550 ThaliTest[598:881431] client: relay established
2016-02-03 22:18:56.550 ThaliTest[598:881431] client: new accepted socket: 0x18849150
,client bridge: new client socket

,client bridge: new client socket

,2016-02-03 22:18:56.768 ThaliTest[598:881431] client: lost peer: 1454534306236.1180.0UHTVQ==
2016-02-03 22:18:56.768 ThaliTest[598:881431] client session: onPeerLost: 1454534306236.1180.0UHTVQ==
2016-02-03 22:18:56.768 ThaliTest[598:881431] client sessio,n: onLinkFailure: 1454534306236.1180.0UHTVQ==
2016-02-03 22:18:56.769 ThaliTest[598:881431] client session: disconnect
2016-02-03 22:18:56.769 ThaliTest[598:881431] client session: stateChange:1->0 1454534306236.1180.0UHTVQ==
,2016-02-03 22:18:56.770 ThaliTest[598:881431] client session: fireConnectCallback: 1454534306236.1180.0UHTVQ==
,2016-02-03 22:18:56.771 ThaliTest[598:881431] jxcore: connect: fail: Peer disconnected
,Connect error with error: Error: Peer disconnected

,2016-02-03 22:18:56.778 ThaliTest[598:882257] server session: connected
,2016-02-03 22:18:56.778 ThaliTest[598:882257] server session: stateChange:1->2 2F-swrW2aUDGTp7z2s7leA
,2016-02-03 22:18:56.789 ThaliTest[598:881697] jxcore: disconnect
,2016-02-03 22:18:56.789 ThaliTest[598:881697] jxcore: disconnect: fail
,Disconnect error with error: Error: Not connected to specified peer

,peerIdentifier not available 1454534306236.1180.0UHTVQ==

,2016-02-03 22:18:56.929 ThaliTest[598:881431] server relay: connected (to port: 52731)
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

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: socket closed

client bridge: socket closed

,ok 123 1st change of remote doc should contain remote id

,client bridge: new client socket

,ok 124 Can update remote doc without error

,null

,{ ok: true,
,  id: '49d47a7f-fb1b-434d-b3c9-ae5648db9856',
  rev: '2-854594a29f4bb4d742e0cfd80a439989' }

,client bridge: new client socket

,ok 125 Remote changes occur in strict order
,
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

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,ok 126 Local changes occur in strict order

,ok 127 2nd change of local doc should contain remote id

,# setup

,Now in TRM stop

State of this._isStarted: true

,About to call stopBroadcasting
,
,2016-02-03 22:19:08.746 ThaliTest[598:881697] jxcore: stopBroadcasting
,2016-02-03 22:19:08.747 ThaliTest[598:881697] THEMultipeerSession stopping peer
,2016-02-03 22:19:08.748 ThaliTest[598:881697] multipeer session: stop timer
,2016-02-03 22:19:08.756 ThaliTest[598:881697] client session: disconnect
,2016-02-03 22:19:08.761 ThaliTest[598:881697] client session: stateChange:2->0 2F-swrW2aUDGTp7z2s7leA.YrziBg==
,2016-02-03 22:19:08.770 ThaliTest[598:882165] server session: not connected 2F-swrW2aUDGTp7z2s7leA
,2016-02-03 22:19:08.836 ThaliTest[598:881697] server session: disconnect
,2016-02-03 22:19:08.842 ThaliTest[598:881697] server session: stateChange:2->0 2F-swrW2aUDGTp7z2s7leA
,2016-02-03 22:19:08.908 ThaliTest[598:881697] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,2016-02-03 22:19:08.918 ThaliTest[598:881697] Error!: connect ECONNRESET
Stack:[{"_fileName":"net.js","_functionName":"$c","_lineNumber":"837","_columnNumber":"7","_msg":"    at $c@net.js:837:7"},{"_fileName":"net.js","_functionName":"$09","_lineNumber":",829","_columnNumber":"13","_msg":"    at $09@net.js:829:13"},{"_fileName":"net.js","_functionName":"unknown","_lineNumber":"837","_columnNumber":"7","_msg":""}]
,Uncaught Exception: Error: connect ECONNRESET

,[ { _fileName: 'net.js',
    _functionName: '$c',
    _lineNumber: '837',
    _columnNumber: '7',
    _msg: '    at $c@net.js:837:7' },
  { _fileName: 'net.js',
    _functionName: '$09',
    _lineNumber: '829',
    _columnNumber: '13',
    _msg: ',    at $09@net.js:829:13' },
  { _fileName: 'net.js',
    _functionName: 'unknown',
    _lineNumber: '837',
    _columnNumber: '7',
    _msg: '' },
  toString: [Function] ]

****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****


```
