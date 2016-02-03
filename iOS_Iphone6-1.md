#### Test 58135655e794d2c_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/58135655e794d2c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/6AD64843-F2EC-41BE-8BF2-C67DE2D88746/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/6AD64843-F2EC-41BE-8BF2-C67DE2D88746/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/58135655e794d2c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/58135655e794d2c/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/DD39ECB2-742B-4F8D-BDCB-D96EBE75445C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49689"
,(lldb)     command script import "/tmp/6AD64843-F2EC-41BE-8BF2-C67DE2D88746/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-03 22:13:12.712 ThaliTest[1180:2089467] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A24CBE74-0191-41F8-9D8E-8D373E8E73CE/Library/Cookies/Cookies.binarycookies
,2016-02-03 22:13:13.119 ThaliTest[1180:2089467] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-03 22:13:13.121 ThaliTest[1180:2089467] Multi-tasking -> Device: YES, App: YES
,2016-02-03 22:13:13.131 ThaliTest[1180:2089467] Unlimited access to network resources
,2016-02-03 22:13:13.145 ThaliTest[1180:2089467] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-03 22:13:22.836 ThaliTest[1180:2089467] Resetting plugins due to page load.
,2016-02-03 22:13:26.651 ThaliTest[1180:2089467] Finished load of: file:///var/mobile/Containers/Bundle/Application/DD39ECB2-742B-4F8D-BDCB-D96EBE75445C/ThaliTest.app/www/index.html
,2016-02-03 22:13:26.836 ThaliTest[1180:2089467] JXcore Cordova plugin initializing
2016-02-03 22:13:26.837 ThaliTest[1180:2089704] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DD39ECB2-742B-4F8D-BDCB-D96EBE75445C/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DD39ECB2-742B-4F8D-BDCB-D96EBE75445C/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DD39ECB2-742B-4F8D-BDCB-D96EBE75445C/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DD39ECB2-742B-4F8D-BDCB-D96EBE75445C/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DD39ECB2-742B-4F8D-BDCB-D96EBE75445C/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DD39ECB2-742B-4F8D-BDCB-D96EBE75445C/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DD39ECB2-742B-4F8D-BDCB-D96EBE75445C/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DD39ECB2-742B-4F8D-BDCB-D96EBE75445C/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

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

ok 20 should not throw

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

,2016-02-03 22:17:38.447 ThaliTest[1180:2089704] jxcore: startBroadcasting
,2016-02-03 22:17:38.462 ThaliTest[1180:2089704] server: starting 1454534258447.1180.lVDDJg==
,2016-02-03 22:17:38.464 ThaliTest[1180:2089704] multipeer session: start timer: 0x18298be0
2016-02-03 22:17:38.465 ThaliTest[1180:2089704] THEMultipeerSession initialized peer 1454534258447.1180
2016-02-03 22:17:38.465 ThaliTest[1180:2089704] jxcore: startBroadcasting: success
,ok 54 Should be able to call startBroadcasting without error

2016-02-03 22:17:38.469 ThaliTest[1180:2089704] jxcore: stopBroadcasting
2016-02-03 22:17:38.469 ThaliTest[1180:2089704] THEMultipeerSession stopping peer
2016-02-03 22:17:38.470 ThaliTest[1,180:2089704] multipeer session: stop timer
,2016-02-03 22:17:38.472 ThaliTest[1180:2089704] jxcore: stopBroadcasting: success
ok 55 Should be able to call stopBroadcasting without error

2016-02-03 22:17:38.475 ThaliTest[1180:2089704] jxcore: startBroadcasting
,2016-02-03 22:17:38.483 ThaliTest[1180:2089704] server: starting 1454534258474.1180.NepDmg==
,2016-02-03 22:17:38.492 ThaliTest[1180:2089704] multipeer session: start timer: 0x185810d0
2016-02-03 22:17:38.493 ThaliTest[1180:2089704] THEMultipeerSession initialized peer 1454534258474.1180
2016-02-03 22:17:38.493 ThaliTest[1180:2089704] jxcore: sta,rtBroadcasting: success
ok 56 Should be able to call startBroadcasting without error

2016-02-03 22:17:38.495 ThaliTest[1180:2089704] jxcore: stopBroadcasting
2016-02-03 22:17:38.495 ThaliTest[1180:2089704] THEMultipeerSession stopping peer
2016-02-03, 22:17:38.496 ThaliTest[1180:2089704] multipeer session: stop timer
2016-02-03 22:17:38.496 ThaliTest[1180:2089704] jxcore: stopBroadcasting: success
ok 57 Should be able to call stopBroadcasting without error

2016-02-03 22:17:38.499 ThaliTest[1180:20,89704] jxcore: startBroadcasting
,2016-02-03 22:17:38.510 ThaliTest[1180:2089704] server: starting 1454534258498.1180.YWIjrQ==
2016-02-03 22:17:38.511 ThaliTest[1180:2089704] multipeer session: start timer: 0x18581810
2016-02-03 22:17:38.512 ThaliTest[1180:2089704] THEMultipeerSession in,itialized peer 1454534258498.1180
2016-02-03 22:17:38.512 ThaliTest[1180:2089704] jxcore: startBroadcasting: success
ok 58 Should be able to call startBroadcasting without error

2016-02-03 22:17:38.514 ThaliTest[1180:2089704] jxcore: stopBroadcasting,
2016-02-03 22:17:38.515 ThaliTest[1180:2089704] THEMultipeerSession stopping peer
2016-02-03 22:17:38.515 ThaliTest[1180:2089704] multipeer session: stop timer
2016-02-03 22:17:38.515 ThaliTest[1180:2089704] jxcore: stopBroadcasting: success
ok 59 Shou,ld be able to call stopBroadcasting without error

2016-02-03 22:17:38.517 ThaliTest[1180:2089704] jxcore: startBroadcasting
2016-02-03 22:17:38.521 ThaliTest[1180:2089704] server: starting 1454534258517.1180.s+shqQ==
2016-02-03 22:17:38.524 ThaliTest[,1180:2089704] multipeer session: start timer: 0x1828b660
2016-02-03 22:17:38.529 ThaliTest[1180:2089704] THEMultipeerSession initialized peer 1454534258517.1180
,2016-02-03 22:17:38.530 ThaliTest[1180:2089704] jxcore: startBroadcasting: success
ok 60 Should be able to call startBroadcasting without error

2016-02-03 22:17:38.533 ThaliTest[1180:2089704] jxcore: stopBroadcasting
2016-02-03 22:17:38.533 ThaliTest[,1180:2089704] THEMultipeerSession stopping peer
2016-02-03 22:17:38.533 ThaliTest[1180:2089704] multipeer session: stop timer
2016-02-03 22:17:38.534 ThaliTest[1180:2089704] jxcore: stopBroadcasting: success
ok 61 Should be able to call stopBroadcasting, without error

2016-02-03 22:17:38.536 ThaliTest[1180:2089704] jxcore: startBroadcasting
,2016-02-03 22:17:38.543 ThaliTest[1180:2089704] server: starting 1454534258535.1180.Utp40A==
2016-02-03 22:17:38.547 ThaliTest[1180:2089704] multipeer session: start timer: 0x1858b3e0
2016-02-03 22:17:38.550 ThaliTest[1180:2089704] THEMultipeerSession in,itialized peer 1454534258535.1180
2016-02-03 22:17:38.551 ThaliTest[1180:2089704] jxcore: startBroadcasting: success
ok 62 Should be able to call startBroadcasting without error

,2016-02-03 22:17:38.555 ThaliTest[1180:2089704] jxcore: stopBroadcasting
2016-02-03 22:17:38.555 ThaliTest[1180:2089704] THEMultipeerSession stopping peer
2016-02-03 22:17:38.556 ThaliTest[1180:2089704] multipeer session: stop timer
2016-02-03 22:17:38.,556 ThaliTest[1180:2089704] jxcore: stopBroadcasting: success
ok 63 Should be able to call stopBroadcasting without error

2016-02-03 22:17:38.557 ThaliTest[1180:2089704] jxcore: startBroadcasting
,2016-02-03 22:17:38.562 ThaliTest[1180:2089704] server: starting 1454534258557.1180.hrJFeQ==
2016-02-03 22:17:38.563 ThaliTest[1180:2089704] multipeer session: start timer: 0x18401510
2016-02-03 22:17:38.563 ThaliTest[1180:2089704] THEMultipeerSession in,itialized peer 1454534258557.1180
2016-02-03 22:17:38.563 ThaliTest[1180:2089704] jxcore: startBroadcasting: success
ok 64 Should be able to call startBroadcasting without error

2016-02-03 22:17:38.564 ThaliTest[1180:2089704] jxcore: stopBroadcasting,
2016-02-03 22:17:38.565 ThaliTest[1180:2089704] THEMultipeerSession stopping peer
2016-02-03 22:17:38.565 ThaliTest[1180:2089704] multipeer session: stop timer
2016-02-03 22:17:38.565 ThaliTest[1180:2089704] jxcore: stopBroadcasting: success
ok 65 Shou,ld be able to call stopBroadcasting without error

2016-02-03 22:17:38.566 ThaliTest[1180:2089704] jxcore: startBroadcasting
,2016-02-03 22:17:38.572 ThaliTest[1180:2089704] server: starting 1454534258566.1180.TV0pog==
2016-02-03 22:17:38.572 ThaliTest[1180:2089704] multipeer session: start timer: 0x1858a340
2016-02-03 22:17:38.574 ThaliTest[1180:2089704] THEMultipeerSession in,itialized peer 1454534258566.1180
2016-02-03 22:17:38.574 ThaliTest[1180:2089704] jxcore: startBroadcasting: success
ok 66 Should be able to call startBroadcasting without error

2016-02-03 22:17:38.576 ThaliTest[1180:2089704] jxcore: stopBroadcasting,
2016-02-03 22:17:38.576 ThaliTest[1180:2089704] THEMultipeerSession stopping peer
2016-02-03 22:17:38.576 ThaliTest[1180:2089704] multipeer session: stop timer
2016-02-03 22:17:38.576 ThaliTest[1180:2089704] jxcore: stopBroadcasting: success
ok 67 Shou,ld be able to call stopBroadcasting without error

2016-02-03 22:17:38.577 ThaliTest[1180:2089704] jxcore: startBroadcasting
,2016-02-03 22:17:38.585 ThaliTest[1180:2089704] server: starting 1454534258577.1180.nFw7vA==
,2016-02-03 22:17:38.592 ThaliTest[1180:2089704] multipeer session: start timer: 0x1858e6b0
,2016-02-03 22:17:38.594 ThaliTest[1180:2089704] THEMultipeerSession initialized peer 1454534258577.1180
,2016-02-03 22:17:38.596 ThaliTest[1180:2089704] jxcore: startBroadcasting: success
,ok 68 Should be able to call startBroadcasting without error
,
,2016-02-03 22:17:38.601 ThaliTest[1180:2089704] jxcore: stopBroadcasting
,2016-02-03 22:17:38.602 ThaliTest[1180:2089704] THEMultipeerSession stopping peer
,2016-02-03 22:17:38.603 ThaliTest[1180:2089704] multipeer session: stop timer
,2016-02-03 22:17:38.605 ThaliTest[1180:2089704] jxcore: stopBroadcasting: success
,ok 69 Should be able to call stopBroadcasting without error
,
,2016-02-03 22:17:38.609 ThaliTest[1180:2089704] jxcore: startBroadcasting
,2016-02-03 22:17:38.611 ThaliTest[1180:2089704] server: starting 1454534258608.1180.YhtuGg==
,2016-02-03 22:17:38.612 ThaliTest[1180:2089704] multipeer session: start timer: 0x18588cd0
,2016-02-03 22:17:38.613 ThaliTest[1180:2089704] THEMultipeerSession initialized peer 1454534258608.1180
,2016-02-03 22:17:38.619 ThaliTest[1180:2089704] jxcore: startBroadcasting: success
,ok 70 Should be able to call startBroadcasting without error
,
,2016-02-03 22:17:38.621 ThaliTest[1180:2089704] jxcore: stopBroadcasting
,2016-02-03 22:17:38.622 ThaliTest[1180:2089704] THEMultipeerSession stopping peer
,2016-02-03 22:17:38.623 ThaliTest[1180:2089704] multipeer session: stop timer
,2016-02-03 22:17:38.624 ThaliTest[1180:2089704] jxcore: stopBroadcasting: success
,ok 71 Should be able to call stopBroadcasting without error

,2016-02-03 22:17:38.629 ThaliTest[1180:2089704] jxcore: startBroadcasting
,2016-02-03 22:17:38.632 ThaliTest[1180:2089704] server: starting 1454534258628.1180.dWdcpw==
,2016-02-03 22:17:38.634 ThaliTest[1180:2089704] multipeer session: start timer: 0x1858aef0
,2016-02-03 22:17:38.635 ThaliTest[1180:2089704] THEMultipeerSession initialized peer 1454534258628.1180
,2016-02-03 22:17:38.637 ThaliTest[1180:2089704] jxcore: startBroadcasting: success
,ok 72 Should be able to call startBroadcasting without error

,2016-02-03 22:17:38.642 ThaliTest[1180:2089704] jxcore: stopBroadcasting
,2016-02-03 22:17:38.643 ThaliTest[1180:2089704] THEMultipeerSession stopping peer
,2016-02-03 22:17:38.643 ThaliTest[1180:2089704] multipeer session: stop timer
,2016-02-03 22:17:38.645 ThaliTest[1180:2089704] jxcore: stopBroadcasting: success
,ok 73 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,# teardown

,2016-02-03 22:18:00.146 ThaliTest[1180:2089704] jxcore: startBroadcasting
,2016-02-03 22:18:00.148 ThaliTest[1180:2089704] server: starting 1454534280146.1180.j7PKNg==
,2016-02-03 22:18:00.149 ThaliTest[1180:2089704] multipeer session: start timer: 0x196b5660
2016-02-03 22:18:00.152 ThaliTest[1180:2089704] THEMultipeerSession initialized peer 1454534280146.1180
,2016-02-03 22:18:00.153 ThaliTest[1180:2089704] jxcore: startBroadcasting: success
,ok 74 Should be able to call startBroadcasting without error

,2016-02-03 22:18:00.154 ThaliTest[1180:2089704] jxcore: startBroadcasting
,2016-02-03 22:18:00.155 ThaliTest[1180:2089704] jxcore: startBroadcasting: failure
,ok 75 Cannot call startBroadcasting twice

2016-02-03 22:18:00.156 ThaliTest[1180:2089704] jxcore: stopBroadcasting
,2016-02-03 22:18:00.157 ThaliTest[1180:2089704] THEMultipeerSession stopping peer
,2016-02-03 22:18:00.157 ThaliTest[1180:2089704] multipeer session: stop timer
,2016-02-03 22:18:00.159 ThaliTest[1180:2089704] jxcore: stopBroadcasting: success
,ok 76 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on connection to bad peer

,# teardown

,2016-02-03 22:18:00.495 ThaliTest[1180:2089704] jxcore: startBroadcasting
,2016-02-03 22:18:00.500 ThaliTest[1180:2089704] server: starting 1454534280495.1180.d3g5uA==
,2016-02-03 22:18:00.502 ThaliTest[1180:2089704] multipeer session: start timer: 0x1959bd10
,2016-02-03 22:18:00.510 ThaliTest[1180:2089704] THEMultipeerSession initialized peer 1454534280495.1180
,2016-02-03 22:18:00.512 ThaliTest[1180:2089704] jxcore: startBroadcasting: success
,ok 77 Should be able to call startBroadcasting without error

,2016-02-03 22:18:00.516 ThaliTest[1180:2089704] jxcore: connect foobar
,2016-02-03 22:18:00.518 ThaliTest[1180:2089704] client: unknown peer foobar
,2016-02-03 22:18:00.519 ThaliTest[1180:2089704] jxcore: connect: fail: Unknown peer
,ok 78 Should not connect to a bad peer

,2016-02-03 22:18:00.526 ThaliTest[1180:2089704] jxcore: stopBroadcasting
,2016-02-03 22:18:00.527 ThaliTest[1180:2089704] THEMultipeerSession stopping peer
,2016-02-03 22:18:00.528 ThaliTest[1180:2089704] multipeer session: stop timer
,2016-02-03 22:18:00.530 ThaliTest[1180:2089704] jxcore: stopBroadcasting: success
,ok 79 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on disconnect to bad peer

,# teardown

,2016-02-03 22:18:01.441 ThaliTest[1180:2089704] jxcore: startBroadcasting
,2016-02-03 22:18:01.445 ThaliTest[1180:2089704] server: starting 1454534281441.1180.8wlWlg==
2016-02-03 22:18:01.446 ThaliTest[1180:2089704] multipeer session: start timer: 0x16d055b0
2016-02-03 22:18:01.447 ThaliTest[1180:2089704] THEMultipeerSession in,itialized peer 1454534281441.1180
2016-02-03 22:18:01.447 ThaliTest[1180:2089704] jxcore: startBroadcasting: success
ok 80 Should be able to call startBroadcasting without error

2016-02-03 22:18:01.449 ThaliTest[1180:2089704] jxcore: disconnect
2016-,02-03 22:18:01.449 ThaliTest[1180:2089704] jxcore: disconnect: fail
,ok 81 Disconnect should fail to a non-existant peer 

2016-02-03 22:18:01.456 ThaliTest[1180:2089704] jxcore: stopBroadcasting
2016-02-03 22:18:01.457 ThaliTest[1180:2089704] THEMultipeerSession stopping peer
2016-02-03 22:18:01.457 ThaliTest[1180:2089,704] multipeer session: stop timer
2016-02-03 22:18:01.457 ThaliTest[1180:2089704] jxcore: stopBroadcasting: success
ok 82 Should be able to call stopBroadcasting without error

,# setup
,
,# ThaliEmitter can discover and connect to peers

,# teardown

,2016-02-03 22:18:02.189 ThaliTest[1180:2089704] jxcore: startBroadcasting
,2016-02-03 22:18:02.193 ThaliTest[1180:2089704] server: starting 1454534282188.1180.uRSyDQ==
2016-02-03 22:18:02.193 ThaliTest[1180:2089704] multipeer session: start timer: 0x1977db40
2016-02-03 22:18:02.194 ThaliTest[1180:2089704] THEMultipeerSession in,itialized peer 1454534282188.1180
2016-02-03 22:18:02.194 ThaliTest[1180:2089704] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error

,2016-02-03 22:18:03.279 ThaliTest[1180:2089467] client: found peer: 1454534284316.598.uQcXjg==
,2016-02-03 22:18:03.282 ThaliTest[1180:2089704] jxcore: connect 1454534284316.598.uQcXjg==
2016-02-03 22:18:03.283 ThaliTest[1180:2089704] client session: connect
2016-02-03 22:18:03.283 ThaliTest[1180:2089704] client session: stateChange:0->1 1454534284316.598.uQcXjg==
,2016-02-03 22:18:03.994 ThaliTest[1180:2089467] multipeer session: reset timer
2016-02-03 22:18:03.994 ThaliTest[1180:2089467] multipeer session: stop timer
2016-02-03 22:18:03.994 ThaliTest[1180:2089467] multipeer session: start timer: 0x1977db40
2016-,02-03 22:18:03.994 ThaliTest[1180:2089467] server session: connect
2016-02-03 22:18:03.995 ThaliTest[1180:2089467] server session: stateChange:0->1 1454534284316.598
,2016-02-03 22:18:04.001 ThaliTest[1180:2089467] server: accepting invitation 1454534284316.598
,2016-02-03 22:18:06.334 ThaliTest[1180:2090241] client session: connected
2016-02-03 22:18:06.335 ThaliTest[1180:2090241] client session: stateChange:1->2 1454534284316.598.uQcXjg==
,2016-02-03 22:18:06.341 ThaliTest[1180:2090241] client session: fireConnectCallback: 1454534284316.598.uQcXjg==
2016-02-03 22:18:06.343 ThaliTest[1180:2090241] jxcore: connect: success
ok 84 Should be able to connect without error

ok 85 Port should be within range

,2016-02-03 22:18:06.349 ThaliTest[1180:2089704] jxcore: disconnect
2016-02-03 22:18:06.350 ThaliTest[1180:2089704] client session: disconnectFromPeer: 1454534284316.598.uQcXjg==
2016-02-03 22:18:06.350 ThaliTest[1180:2089704] client session: disconnect
,2016-02-03 22:18:06.350 ThaliTest[1180:2089704] client session: stateChange:2->0 1454534284316.598.uQcXjg==
,2016-02-03 22:18:06.432 ThaliTest[1180:2089704] jxcore: disconnect: success
ok 86 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,2016-02-03 22:18:06.557 ThaliTest[1180:2090278] server session: connected
,2016-02-03 22:18:06.558 ThaliTest[1180:2090278] server session: stateChange:1->2 1454534284316.598
,2016-02-03 22:18:06.562 ThaliTest[1180:2089467] server relay: socket disconnected
,2016-02-03 22:18:06.562 ThaliTest[1180:2089467] server relay: 0x18163f10 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-03 22:18:06.632 ThaliTest[1180:2090241] server session: not connected 1454534284316.598
,calling stopBroadcasting

,2016-02-03 22:18:06.905 ThaliTest[1180:2089704] jxcore: stopBroadcasting
2016-02-03 22:18:06.906 ThaliTest[1180:2089704] THEMultipeerSession stopping peer
2016-02-03 22:18:06.906 ThaliTest[1180:2089704] multipeer session: stop timer
2016-02-03 22:18:06.,907 ThaliTest[1180:2089704] server session: disconnect
2016-02-03 22:18:06.907 ThaliTest[1180:2089704] server session: stateChange:2->0 1454534284316.598
2016-02-03 22:18:06.908 ThaliTest[1180:2089704] jxcore: stopBroadcasting: success
stopBroadcasting ,returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double connect

,# teardown

,2016-02-03 22:18:09.459 ThaliTest[1180:2089704] jxcore: startBroadcasting
,2016-02-03 22:18:09.462 ThaliTest[1180:2089704] server: starting 1454534289458.1180.cy09Hg==
2016-02-03 22:18:09.464 ThaliTest[1180:2089704] multipeer session: start timer: 0x190c2b50
2016-02-03 22:18:09.464 ThaliTest[1180:2089704] THEMultipeerSession in,itialized peer 1454534289458.1180
2016-02-03 22:18:09.465 ThaliTest[1180:2089704] jxcore: startBroadcasting: success
ok 87 Should be able to call startBroadcasting without error

,2016-02-03 22:18:10.645 ThaliTest[1180:2089467] client: found peer: 1454534291646.598.eA16Og==
,2016-02-03 22:18:10.647 ThaliTest[1180:2089704] jxcore: connect 1454534291646.598.eA16Og==
2016-02-03 22:18:10.648 ThaliTest[1180:2089704] client session: connect
,2016-02-03 22:18:10.649 ThaliTest[1180:2089704] client session: stateChange:0->1 1454534291646.598.eA16Og==
,2016-02-03 22:18:11.132 ThaliTest[1180:2089467] multipeer session: reset timer
2016-02-03 22:18:11.132 ThaliTest[1180:2089467] multipeer session: stop timer
2016-02-03 22:18:11.133 ThaliTest[1180:2089467] multipeer session: start timer: 0x190c2b50
2016-,02-03 22:18:11.133 ThaliTest[1180:2089467] server session: connect
2016-02-03 22:18:11.134 ThaliTest[1180:2089467] server session: stateChange:0->1 1454534291646.598
2016-02-03 22:18:11.146 ThaliTest[1180:2089467] server: accepting invitation 1454534291646.598
,2016-02-03 22:18:13.503 ThaliTest[1180:2090241] client session: connected
2016-02-03 22:18:13.503 ThaliTest[1180:2090241] client session: stateChange:1->2 1454534291646.598.eA16Og==
,2016-02-03 22:18:13.519 ThaliTest[1180:2090242] client session: fireConnectCallback: 1454534291646.598.eA16Og==
2016-02-03 22:18:13.519 ThaliTest[1180:2090242] jxcore: connect: success
,ok 88 Should be able to connect without error

ok 89 Port should be within range

,2016-02-03 22:18:13.526 ThaliTest[1180:2089704] jxcore: connect 1454534291646.598.eA16Og==
2016-02-03 22:18:13.526 ThaliTest[1180:2089704] client: already connect(ing/ed) to 1454534291646.598.eA16Og==
2016-02-03 22:18:13.527 ThaliTest[1180:2089704] jxcore: connect: fail: Aleady connecting
,ok 90 Should fail on double connect

,2016-02-03 22:18:13.530 ThaliTest[1180:2089704] jxcore: disconnect
2016-02-03 22:18:13.531 ThaliTest[1180:2089704] client session: disconnectFromPeer: 1454534291646.598.eA16Og==
2016-02-03 22:18:13.531 ThaliTest[1180:2089704] client session: disconnect
,2016-02-03 22:18:13.531 ThaliTest[1180:2089704] client session: stateChange:2->0 1454534291646.598.eA16Og==
,2016-02-03 22:18:13.546 ThaliTest[1180:2089704] jxcore: disconnect: success
ok 91 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,2016-02-03 22:18:13.802 ThaliTest[1180:2090242] server session: connected
2016-02-03 22:18:13.802 ThaliTest[1180:2090242] server session: stateChange:1->2 1454534291646.598
,2016-02-03 22:18:13.809 ThaliTest[1180:2089467] server relay: socket disconnected
2016-02-03 22:18:13.810 ThaliTest[1180:2089467] server relay: 0x197963e0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-03 22:18:13.857 ThaliTest[1180:2090278] server session: not connected 1454534291646.598
,calling stopBroadcasting

,2016-02-03 22:18:14.230 ThaliTest[1180:2089704] jxcore: stopBroadcasting
2016-02-03 22:18:14.231 ThaliTest[1180:2089704] THEMultipeerSession stopping peer
2016-02-03 22:18:14.231 ThaliTest[1180:2089704] multipeer session: stop timer
2016-02-03 22:18:14.,231 ThaliTest[1180:2089704] server session: disconnect
2016-02-03 22:18:14.232 ThaliTest[1180:2089704] server session: stateChange:2->0 1454534291646.598
2016-02-03 22:18:14.233 ThaliTest[1180:2089704] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,
# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,# teardown

,2016-02-03 22:18:15.532 ThaliTest[1180:2089704] jxcore: startBroadcasting
,2016-02-03 22:18:15.536 ThaliTest[1180:2089704] server: starting 1454534295531.1180.5UGSbA==
2016-02-03 22:18:15.536 ThaliTest[1180:2089704] multipeer session: start timer: 0x18557a90
2016-02-03 22:18:15.537 ThaliTest[1180:2089704] THEMultipeerSession in,itialized peer 1454534295531.1180
2016-02-03 22:18:15.537 ThaliTest[1180:2089704] jxcore: startBroadcasting: success
ok 92 Should be able to call startBroadcasting without error

,2016-02-03 22:18:16.590 ThaliTest[1180:2089467] client: found peer: 1454534297684.598.n04Wpg==
2016-02-03 22:18:16.591 ThaliTest[1180:2089704] jxcore: connect 1454534297684.598.n04Wpg==
2016-02-03 22:18:16.592 ThaliTest[1180:2089704] client session: conn,ect
2016-02-03 22:18:16.592 ThaliTest[1180:2089704] client session: stateChange:0->1 1454534297684.598.n04Wpg==
,2016-02-03 22:18:17.041 ThaliTest[1180:2089467] multipeer session: reset timer
2016-02-03 22:18:17.042 ThaliTest[1180:2089467] multipeer session: stop timer
2016-02-03 22:18:17.042 ThaliTest[1180:2089467] multipeer session: start timer: 0x18557a90
2016-02-03 22:18:17.042 ThaliTest[1180:2089467] server session: connect
2016-02-03 22:18:17.043 ThaliTest[1180:2089467] server session: stateChange:0->1 1454534297684.598
,2016-02-03 22:18:17.051 ThaliTest[1180:2089467] server: accepting invitation 1454534297684.598
,2016-02-03 22:18:19.600 ThaliTest[1180:2090241] server session: connected
2016-02-03 22:18:19.600 ThaliTest[1180:2090241] server session: stateChange:1->2 1454534297684.598
,2016-02-03 22:18:19.646 ThaliTest[1180:2089467] server relay: socket disconnected
2016-02-03 22:18:19.647 ThaliTest[1180:2089467] server relay: 0x190cff00 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLoc,alizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-03 22:18:19.682 ThaliTest[1180:2090303] server session: not connected 1454534297684.598
,2016-02-03 22:18:19.693 ThaliTest[1180:2090277] client session: connected
2016-02-03 22:18:19.693 ThaliTest[1180:2090277] client session: stateChange:1->2 1454534297684.598.n04Wpg==
,2016-02-03 22:18:19.703 ThaliTest[1180:2090303] client session: fireConnectCallback: 1454534297684.598.n04Wpg==
2016-02-03 22:18:19.703 ThaliTest[1180:2090303] jxcore: connect: success
ok 93 Should be able to connect without error

ok 94 Port should be within range

,2016-02-03 22:18:19.705 ThaliTest[1180:2089704] jxcore: disconnect
2016-02-03 22:18:19.706 ThaliTest[1180:2089704] client session: disconnectFromPeer: 1454534297684.598.n04Wpg==
2016-02-03 22:18:19.706 ThaliTest[1180:2089704] client session: disconnect
2016-02-03 22:18:19.706 ThaliTest[1180:2089704] client session: stateChange:2->0 1454534297684.598.n04Wpg==
,2016-02-03 22:18:19.713 ThaliTest[1180:2089704] jxcore: disconnect: success
ok 95 Should be able to disconnect without error

2016-02-03 22:18:19.714 ThaliTest[1180:2089704] jxcore: disconnect
2016-02-03 22:18:19.714 ThaliTest[1180:2089704] jxcore: disconnect: fail
ok 96 Disconnect should fail 

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting
,
,2016-02-03 22:18:19.933 ThaliTest[1180:2089704] jxcore: stopBroadcasting
2016-02-03 22:18:19.933 ThaliTest[1180:2089704] THEMultipeerSession stopping peer
2016-02-03 22:18:19.933 ThaliTest[1180:2089704] multipeer session: stop timer
2016-02-03 22:18:19.,934 ThaliTest[1180:2089704] server session: disconnect
2016-02-03 22:18:19.934 ThaliTest[1180:2089704] server session: stateChange:2->0 1454534297684.598
2016-02-03 22:18:19.935 ThaliTest[1180:2089704] jxcore: stopBroadcasting: success
stopBroadcasting ,returned undefined

# ThaliEmitter can connect and send data

,# teardown

,echo server started on port: 56239

,2016-02-03 22:18:21.085 ThaliTest[1180:2089704] jxcore: startBroadcasting
,2016-02-03 22:18:21.087 ThaliTest[1180:2089704] server: starting 1454534301085.1180.7aLCCw==
,2016-02-03 22:18:21.088 ThaliTest[1180:2089704] multipeer session: start timer: 0x184c34b0
,2016-02-03 22:18:21.091 ThaliTest[1180:2089704] THEMultipeerSession initialized peer 1454534301085.1180
,2016-02-03 22:18:21.091 ThaliTest[1180:2089704] jxcore: startBroadcasting: success
,ok 97 Should be able to call startBroadcasting without error

,2016-02-03 22:18:21.978 ThaliTest[1180:2089467] client: found peer: 1454534303130.598.IIkLGw==
2016-02-03 22:18:21.980 ThaliTest[1180:2089704] jxcore: connect 1454534303130.598.IIkLGw==
2016-02-03 22:18:21.980 ThaliTest[1180:2089704] client session: conn,ect
2016-02-03 22:18:21.981 ThaliTest[1180:2089704] client session: stateChange:0->1 1454534303130.598.IIkLGw==
,2016-02-03 22:18:22.257 ThaliTest[1180:2089467] multipeer session: reset timer
2016-02-03 22:18:22.257 ThaliTest[1180:2089467] multipeer session: stop timer
2016-02-03 22:18:22.258 ThaliTest[1180:2089467] multipeer session: start timer: 0x184c34b0
2016-,02-03 22:18:22.258 ThaliTest[1180:2089467] server session: connect
2016-02-03 22:18:22.258 ThaliTest[1180:2089467] server session: stateChange:0->1 1454534303130.598
,2016-02-03 22:18:22.270 ThaliTest[1180:2089467] server: accepting invitation 1454534303130.598
,2016-02-03 22:18:25.073 ThaliTest[1180:2090241] server session: connected
2016-02-03 22:18:25.075 ThaliTest[1180:2090241] server session: stateChange:1->2 1454534303130.598
,2016-02-03 22:18:25.089 ThaliTest[1180:2089467] server relay: connected (to port: 56239)
,2016-02-03 22:18:25.257 ThaliTest[1180:2090278] client session: connected
,2016-02-03 22:18:25.258 ThaliTest[1180:2090278] client session: stateChange:1->2 1454534303130.598.IIkLGw==
,2016-02-03 22:18:25.270 ThaliTest[1180:2090238] client session: fireConnectCallback: 1454534303130.598.IIkLGw==
,2016-02-03 22:18:25.273 ThaliTest[1180:2090238] jxcore: connect: success
,ok 98 Should be able to connect without error

,ok 99 Port should be within range

,2016-02-03 22:18:25.285 ThaliTest[1180:2089467] client: relay established
2016-02-03 22:18:25.285 ThaliTest[1180:2089467] client: new accepted socket: 0x19668c70
,data in 15330

,data in 24019
,
,data in 43972
,
,data in 65629
,
,data in 77745

,data in 87600

,2016-02-03 22:18:25.546 ThaliTest[1180:2090277] server session: not connected 1454534303130.598
,data in 99574

,data in 107239

,data in 130234

,data in 131072

,ok 100 the test messages should be equal

,2016-02-03 22:18:25.625 ThaliTest[1180:2089704] jxcore: disconnect
,2016-02-03 22:18:25.625 ThaliTest[1180:2089704] client session: disconnectFromPeer: 1454534303130.598.IIkLGw==
,2016-02-03 22:18:25.626 ThaliTest[1180:2089704] client session: disconnect
,2016-02-03 22:18:25.626 ThaliTest[1180:2089704] client session: stateChange:2->0 1454534303130.598.IIkLGw==
,2016-02-03 22:18:25.632 ThaliTest[1180:2089704] jxcore: disconnect: success
,ok 101 Should be able to disconnect without error

,setting stopBroadcasting callback and ending test.

,# setup
,
,calling stopBroadcasting

,2016-02-03 22:18:25.691 ThaliTest[1180:2089704] jxcore: stopBroadcasting
2016-02-03 22:18:25.691 ThaliTest[1180:2089704] THEMultipeerSession stopping peer
2016-02-03 22:18:25.691 ThaliTest[1180:2089704] multipeer session: stop timer
2016-02-03 22:18:25.692 ThaliTest[1180:2089704] server session: disconnect
2016-02-03 22:18:25.692 ThaliTest[1180:2089704] server session: stateChange:2->0 1454534303130.598
,2016-02-03 22:18:25.697 ThaliTest[1180:2089704] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter handles socket disconnect correctly

,# teardown

,echo server started on port: 56245

,2016-02-03 22:18:26.237 ThaliTest[1180:2089704] jxcore: startBroadcasting
,2016-02-03 22:18:26.241 ThaliTest[1180:2089704] server: starting 1454534306236.1180.0UHTVQ==
2016-02-03 22:18:26.242 ThaliTest[1180:2089704] multipeer session: start timer: 0x16dfbf90
2016-02-03 22:18:26.242 ThaliTest[1180:2089704] THEMultipeerSession in,itialized peer 1454534306236.1180
2016-02-03 22:18:26.242 ThaliTest[1180:2089704] jxcore: startBroadcasting: success
ok 102 Should be able to call startBroadcasting without error

,2016-02-03 22:18:26.919 ThaliTest[1180:2089467] client: found peer: 1454534303130.598.IIkLGw==
[{"peerIdentifier":"1454534303130.598.IIkLGw==","peerName":"(null)","peerAvailable":true}]

,2016-02-03 22:18:26.922 ThaliTest[1180:2089704] jxcore: connect 1454534303130.598.IIkLGw==
,2016-02-03 22:18:26.922 ThaliTest[1180:2089704] client session: connect
,2016-02-03 22:18:26.923 ThaliTest[1180:2089704] client session: stateChange:0->1 1454534303130.598.IIkLGw==
,2016-02-03 22:18:27.443 ThaliTest[1180:2089467] multipeer session: reset timer
2016-02-03 22:18:27.443 ThaliTest[1180:2089467] multipeer session: stop timer
2016-02-03 22:18:27.443 ThaliTest[1180:2089467] multipeer session: start timer: 0x16dfbf90
2016-,02-03 22:18:27.444 ThaliTest[1180:2089467] server session: connect
2016-02-03 22:18:27.444 ThaliTest[1180:2089467] server session: stateChange:0->1 1454534308363.598
,2016-02-03 22:18:27.454 ThaliTest[1180:2089467] server: accepting invitation 1454534308363.598
,2016-02-03 22:18:27.571 ThaliTest[1180:2089467] client: lost peer: 1454534303130.598.IIkLGw==
2016-02-03 22:18:27.572 ThaliTest[1180:2089467] client session: onPeerLost: 1454534303130.598.IIkLGw==
2016-02-03 22:18:27.572 ThaliTest[1180:2089467] client session: onLinkFailure: 1454534303130.598.IIkLGw==
2016-02-03 22:18:27.572 ThaliTest[1180:2089467] client session: disconnect
2016-02-03 22:18:27.573 ThaliTest[1180:2089467] client session: stateChange:1->0 1454534303130.598.IIkLGw==
2016-02-03 22:18:27.5,73 ThaliTest[1180:2089467] client session: fireConnectCallback: 1454534303130.598.IIkLGw==
2016-02-03 22:18:27.573 ThaliTest[1180:2089467] jxcore: connect: fail: Peer disconnected
[{"peerIdentifier":"1454534303130.598.IIkLGw==","peerName":"(null)","peerAvailable":false}]

,2016-02-03 22:18:27.753 ThaliTest[1180:2089467] client: found peer: 1454534308363.598.4OoMyA==
[{"peerIdentifier":"1454534308363.598.4OoMyA==","peerName":"(null)","peerAvailable":true}]

,2016-02-03 22:18:27.756 ThaliTest[1180:2089704] jxcore: connect 1454534308363.598.4OoMyA==
2016-02-03 22:18:27.756 ThaliTest[1180:2089704] client session: connect
2016-02-03 22:18:27.756 ThaliTest[1180:2089704] client session: stateChange:0->1 1454534308363.598.4OoMyA==
,2016-02-03 22:18:28.575 ThaliTest[1180:2089704] jxcore: connect 1454534303130.598.IIkLGw==
2016-02-03 22:18:28.576 ThaliTest[1180:2089704] client: connect: unreachable 1454534303130.598.IIkLGw==
,2016-02-03 22:18:28.576 ThaliTest[1180:2089704] jxcore: connect: fail: Peer unreachable
,2016-02-03 22:18:31.048 ThaliTest[1180:2090241] client session: connected
2016-02-03 22:18:31.048 ThaliTest[1180:2090241] client session: stateChange:1->2 1454534308363.598.4OoMyA==
,2016-02-03 22:18:31.064 ThaliTest[1180:2090241] client session: fireConnectCallback: 1454534308363.598.4OoMyA==
,2016-02-03 22:18:31.064 ThaliTest[1180:2090241] jxcore: connect: success
,ok 103 Should be able to connect without error

,ok 104 Port should be within range

,ok 105 First connect should succeed

,2016-02-03 22:18:31.101 ThaliTest[1180:2089467] client: relay established
,2016-02-03 22:18:31.102 ThaliTest[1180:2089467] client: new accepted socket: 0x19669700
,ok 106 the test messages should be equal

,ok 107 First send should succeed

,2016-02-03 22:18:31.156 ThaliTest[1180:2089467] client: socket closed
,2016-02-03 22:18:31.156 ThaliTest[1180:2089467] client relay: socket disconnected
,2016-02-03 22:18:31.157 ThaliTest[1180:2089467] client relay: 0x19669700 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2016-02-03 22:18:31.158 ThaliTest[1180:2089467] client session: socket closed: 1454534308363.598.4OoMyA==
,2016-02-03 22:18:31.158 ThaliTest[1180:2089467] client session: onLinkFailure: 1454534308363.598.4OoMyA==
,2016-02-03 22:18:31.159 ThaliTest[1180:2089467] client session: disconnect
,2016-02-03 22:18:31.160 ThaliTest[1180:2089467] client session: stateChange:2->0 1454534308363.598.4OoMyA==
,2016-02-03 22:18:31.237 ThaliTest[1180:2089467] client session: fireConnectionErrorEvent: 1454534308363.598.4OoMyA==
,2016-02-03 22:18:31.239 ThaliTest[1180:2089704] jxcore: connect 1454534308363.598.4OoMyA==
,2016-02-03 22:18:31.240 ThaliTest[1180:2089704] client session: connect
,2016-02-03 22:18:31.241 ThaliTest[1180:2089704] client session: stateChange:0->1 1454534308363.598.4OoMyA==
,2016-02-03 22:18:34.204 ThaliTest[1180:2090303] client session: connected
2016-02-03 22:18:34.204 ThaliTest[1180:2090303] client session: stateChange:1->2 1454534308363.598.4OoMyA==
,2016-02-03 22:18:34.218 ThaliTest[1180:2090303] client session: fireConnectCallback: 1454534308363.598.4OoMyA==
2016-02-03 22:18:34.218 ThaliTest[1180:2090303] jxcore: connect: success
ok 108 Should be able to connect without error

,ok 109 Port should be within range

ok 110 Second connect should succeed

,2016-02-03 22:18:34.258 ThaliTest[1180:2089467] client: relay established
2016-02-03 22:18:34.258 ThaliTest[1180:2089467] client: new accepted socket: 0x192449a0
,ok 111 the test messages should be equal

,ok 112 Second send should succeed

,# setup

,2016-02-03 22:18:34.343 ThaliTest[1180:2089467] client: socket closed
,2016-02-03 22:18:34.344 ThaliTest[1180:2089467] client relay: socket disconnected
2016-02-03 22:18:34.344 ThaliTest[1180:2089467] client relay: 0x192449a0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer", UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2016-02-03 22:18:34.345 ThaliTest[1180:2089467] client session: socket closed: 1454534308363.598.4OoMyA==
2016-02-03 22:18:34.345 ThaliTest[1180:2089467] client session: onLinkFailure: 1454534308363.598.4OoMyA==
2016-02-03 22:18:34.345 ThaliTest[1180:208,9467] client session: disconnect
2016-02-03 22:18:34.346 ThaliTest[1180:2089467] client session: stateChange:2->0 1454534308363.598.4OoMyA==
,2016-02-03 22:18:34.364 ThaliTest[1180:2089467] client session: fireConnectionErrorEvent: 1454534308363.598.4OoMyA==
,2016-02-03 22:18:35.750 ThaliTest[1180:2090238] server session: connected
2016-02-03 22:18:35.750 ThaliTest[1180:2090238] server session: stateChange:1->2 1454534308363.598
,2016-02-03 22:18:37.685 ThaliTest[1180:2089467] server relay: connected (to port: 56245)
,2016-02-03 22:18:38.804 ThaliTest[1180:2090238] server session: not connected 1454534308363.598
,2016-02-03 22:18:38.965 ThaliTest[1180:2089467] multipeer session: reset timer
2016-02-03 22:18:38.965 ThaliTest[1180:2089467] multipeer session: stop timer
2016-02-03 22:18:38.965 ThaliTest[1180:2089467] multipeer session: start timer: 0x16dfbf90
2016-,02-03 22:18:38.966 ThaliTest[1180:2089467] server: disconnecting to refresh session (1454534308363.598)
2016-02-03 22:18:38.966 ThaliTest[1180:2089467] server session: disconnect
2016-02-03 22:18:38.966 ThaliTest[1180:2089467] server session: stateChange,:2->0 1454534308363.598
,2016-02-03 22:18:39.026 ThaliTest[1180:2089467] server session: connect
2016-02-03 22:18:39.026 ThaliTest[1180:2089467] server session: stateChange:0->1 1454534308363.598
2016-02-03 22:18:39.035 ThaliTest[1180:2089467] server: accepting invitation 1454534308363.598
,2016-02-03 22:18:40.910 ThaliTest[1180:2090241] server session: connected
2016-02-03 22:18:40.910 ThaliTest[1180:2090241] server session: stateChange:1->2 1454534308363.598
,2016-02-03 22:18:41.529 ThaliTest[1180:2089467] server relay: connected (to port: 56245)
,2016-02-03 22:18:42.134 ThaliTest[1180:2090277] server session: not connected 1454534308363.598
,calling stopBroadcasting

,2016-02-03 22:18:42.460 ThaliTest[1180:2089704] jxcore: stopBroadcasting
2016-02-03 22:18:42.461 ThaliTest[1180:2089704] THEMultipeerSession stopping peer
2016-02-03 22:18:42.461 ThaliTest[1180:2089704] multipeer session: stop timer
2016-02-03 22:18:42.,462 ThaliTest[1180:2089704] server session: disconnect
2016-02-03 22:18:42.462 ThaliTest[1180:2089704] server session: stateChange:2->0 1454534308363.598
,2016-02-03 22:18:42.469 ThaliTest[1180:2089704] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliReplicationManager can call start without error

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/A24CBE74-0191-41F8-9D8E-8D373E8E73CE/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,ok 113 starting event should occur in right order

,2016-02-03 22:18:43.033 ThaliTest[1180:2089704] jxcore: startBroadcasting
,2016-02-03 22:18:43.036 ThaliTest[1180:2089704] server: starting 2F-swrW2aUDGTp7z2s7leA.Uq5KeQ==
,2016-02-03 22:18:43.038 ThaliTest[1180:2089704] multipeer session: start timer: 0x19252040
,2016-02-03 22:18:43.041 ThaliTest[1180:2089704] THEMultipeerSession initialized peer 2F-swrW2aUDGTp7z2s7leA
,2016-02-03 22:18:43.041 ThaliTest[1180:2089704] jxcore: startBroadcasting: success
,ok 114 started event should occur in right order

Now in TRM stop

,State of this._isStarted: true

,ok 115 stopping event should occur in right order

About to call stopBroadcasting

,2016-02-03 22:18:43.043 ThaliTest[1180:2089704] jxcore: stopBroadcasting
,2016-02-03 22:18:43.044 ThaliTest[1180:2089704] THEMultipeerSession stopping peer
,2016-02-03 22:18:43.044 ThaliTest[1180:2089704] multipeer session: stop timer
,2016-02-03 22:18:43.046 ThaliTest[1180:2089704] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined

,ok 116 stopped event should occur in right order

,mux server bridge listener closed

# setup

,# ThaliReplicationManager receives identity

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/A24CBE74-0191-41F8-9D8E-8D373E8E73CE/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-02-03 22:18:43.499 ThaliTest[1180:2089704] jxcore: startBroadcasting
,2016-02-03 22:18:43.502 ThaliTest[1180:2089704] server: starting 2F-swrW2aUDGTp7z2s7leA.+3furQ==
2016-02-03 22:18:43.503 ThaliTest[1180:2089704] multipeer session: start timer: 0x195efdb0
2016-02-03 22:18:43.503 ThaliTest[1180:2089704] THEMultipeerSessio,n initialized peer 2F-swrW2aUDGTp7z2s7leA
2016-02-03 22:18:43.504 ThaliTest[1180:2089704] jxcore: startBroadcasting: success
ok 117 getDeviceIdentity should not return an error

,ok 118 deviceName should not be null

Now in TRM stop

State of this._isStarted: true

,About to call stopBroadcasting

,2016-02-03 22:18:43.509 ThaliTest[1180:2089704] jxcore: stopBroadcasting
2016-02-03 22:18:43.509 ThaliTest[1180:2089704] THEMultipeerSession stopping peer
2016-02-03 22:18:43.509 ThaliTest[1180:2089704] multipeer session: stop timer
2016-02-03 22:18:43.,510 ThaliTest[1180:2089704] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,mux server bridge listener closed

,# setup

,# ThaliReplicationManager replicates database

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/A24CBE74-0191-41F8-9D8E-8D373E8E73CE/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-02-03 22:18:46.267 ThaliTest[1180:2089704] jxcore: startBroadcasting
,2016-02-03 22:18:46.269 ThaliTest[1180:2089704] server: starting 2F-swrW2aUDGTp7z2s7leA.YrziBg==
2016-02-03 22:18:46.269 ThaliTest[1180:2089704] multipeer session: start timer: 0x1a9f0c50
2016-02-03 22:18:46.269 ThaliTest[1180:2089704] THEMultipeerSession initialized peer 2F-swrW2aUDGTp7z2s7leA
2016-02-03 22:18:46.270 ThaliTest[1180:2089704] jxcore: startBroadcasting: success
ok 119 getDeviceIdentity should not return an error

ok 120 deviceName should not be null

,2016-02-03 22:18:46.278 ThaliTest[1180:2089467] client: found peer: 1454534308363.598.4OoMyA==
,2016-02-03 22:18:50.887 ThaliTest[1180:2089467] client: found peer: RfVTpOnuy1VqRfzzLJX7oA.vAy9QQ==
,2016-02-03 22:18:50.935 ThaliTest[1180:2089704] jxcore: connect 1454534308363.598.4OoMyA==
,2016-02-03 22:18:50.936 ThaliTest[1180:2089704] client session: connect
2016-02-03 22:18:50.937 ThaliTest[1180:2089704] client session: stateChange:0->1 1454534308363.598.4OoMyA==
,2016-02-03 22:18:50.941 ThaliTest[1180:2089704] jxcore: connect RfVTpOnuy1VqRfzzLJX7oA.vAy9QQ==
2016-02-03 22:18:50.942 ThaliTest[1180:2089704] client session: connect
2016-02-03 22:18:50.942 ThaliTest[1180:2089704] client session: stateChange:0->1 RfVTpOnuy1VqRfzzLJX7oA.vAy9QQ==
,2016-02-03 22:18:50.974 ThaliTest[1180:2089467] multipeer session: reset timer
,2016-02-03 22:18:50.974 ThaliTest[1180:2089467] multipeer session: stop timer
2016-02-03 22:18:50.975 ThaliTest[1180:2089467] multipeer session: start timer: 0x1a9f0c50
,2016-02-03 22:18:50.975 ThaliTest[1180:2089467] server session: connect
2016-02-03 22:18:50.975 ThaliTest[1180:2089467] server session: stateChange:0->1 RfVTpOnuy1VqRfzzLJX7oA
,2016-02-03 22:18:50.981 ThaliTest[1180:2089467] server: accepting invitation RfVTpOnuy1VqRfzzLJX7oA
,ok 121 Should be able to put doc without error

,ok 122 1st change of local doc should contain local id

,2016-02-03 22:18:53.791 ThaliTest[1180:2089467] client: lost peer: 1454534308363.598.4OoMyA==
2016-02-03 22:18:53.791 ThaliTest[1180:2089467] client session: onPeerLost: 1454534308363.598.4OoMyA==
2016-02-03 22:18:53.792 ThaliTest[1180:2089467] client se,ssion: onLinkFailure: 1454534308363.598.4OoMyA==
2016-02-03 22:18:53.792 ThaliTest[1180:2089467] client session: disconnect
2016-02-03 22:18:53.792 ThaliTest[1180:2089467] client session: stateChange:1->0 1454534308363.598.4OoMyA==
2016-02-03 22:18:53.7,93 ThaliTest[1180:2089467] client session: fireConnectCallback: 1454534308363.598.4OoMyA==
2016-02-03 22:18:53.793 ThaliTest[1180:2089467] jxcore: connect: fail: Peer disconnected
Connect error with error: Error: Peer disconnected

,2016-02-03 22:18:53.809 ThaliTest[1180:2089704] jxcore: disconnect
2016-02-03 22:18:53.809 ThaliTest[1180:2089704] jxcore: disconnect: fail
,Disconnect error with error: Error: Not connected to specified peer

,peerIdentifier not available 1454534308363.598.4OoMyA==

,2016-02-03 22:18:54.390 ThaliTest[1180:2090277] server session: connected
2016-02-03 22:18:54.390 ThaliTest[1180:2090277] server session: stateChange:1->2 RfVTpOnuy1VqRfzzLJX7oA
,2016-02-03 22:18:54.404 ThaliTest[1180:2089467] server relay: connected (to port: 56263)
server bridge: new client socket

,2016-02-03 22:18:54.781 ThaliTest[1180:2090303] client session: connected
2016-02-03 22:18:54.781 ThaliTest[1180:2090303] client session: stateChange:1->2 RfVTpOnuy1VqRfzzLJX7oA.vAy9QQ==
,2016-02-03 22:18:55.094 ThaliTest[1180:2090277] client session: fireConnectCallback: RfVTpOnuy1VqRfzzLJX7oA.vAy9QQ==
2016-02-03 22:18:55.094 ThaliTest[1180:2090277] jxcore: connect: success
,2016-02-03 22:18:55.119 ThaliTest[1180:2089467] client: relay established
2016-02-03 22:18:55.119 ThaliTest[1180:2089467] client: new accepted socket: 0x193a4870
,client bridge: new client socket

,client bridge: new client socket

,client bridge: new client socket
,
,client bridge: socket closed
,
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

,client bridge: new client socket

,client bridge: socket closed

,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: new client socket

,ok 123 1st change of remote doc should contain remote id

,ok 124 Can update remote doc without error

,null

,{ ok: true,
  id: '52d2d8d9-98f8-4514-85ed-b196a5ac5616',
  rev: '2-862d7b6d11e6a95e70f544389f659e91' }

,client bridge: socket closed

client bridge: socket closed

client bridge: socket closed

,client bridge: socket closed

,client bridge: new client socket
,
,client bridge: new client socket
,
,ok 125 Remote changes occur in strict order

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket
,
,client bridge: socket closed

,client bridge: new client socket
,
,client bridge: socket closed

,client bridge: socket closed

,ok 126 Local changes occur in strict order

ok 127 2nd change of local doc should contain remote id

,# setup

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: socket closed

,client bridge: new client socket
,
,client bridge: new client socket
,
,client bridge: socket closed

,client bridge: socket closed

client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket
,
,Now in TRM stop

,State of this._isStarted: true

About to call stopBroadcasting

,2016-02-03 22:19:06.603 ThaliTest[1180:2089704] jxcore: stopBroadcasting
,2016-02-03 22:19:06.604 ThaliTest[1180:2089704] THEMultipeerSession stopping peer
,2016-02-03 22:19:06.604 ThaliTest[1180:2089704] multipeer session: stop timer
,2016-02-03 22:19:06.605 ThaliTest[1180:2089704] client session: disconnect
2016-02-03 22:19:06.606 ThaliTest[1180:2089704] client session: stateChange:2->0 RfVTpOnuy1VqRfzzLJX7oA.vAy9QQ==
,2016-02-03 22:19:06.616 ThaliTest[1180:2089704] server session: disconnect
,2016-02-03 22:19:06.617 ThaliTest[1180:2089704] server session: stateChange:2->0 RfVTpOnuy1VqRfzzLJX7oA
,2016-02-03 22:19:06.683 ThaliTest[1180:2089704] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined

,# After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

,Error in mux client bridge Error: write EPIPE

,mux server bridge listener closed

,syncRetry called when not started

client bridge: socket closed

server bridge: socket closed

,client bridge: new client socket
,
,# teardown

,client bridge: socket closed

,client bridge: socket closed


```
