#### Test 58751238ee11130_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/58751238ee11130/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/BDEFD15F-0940-424B-81B2-21CF259210AA/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/BDEFD15F-0940-424B-81B2-21CF259210AA/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/58751238ee11130/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/58751238ee11130/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A2A570B2-4474-43B2-9C8A-C3EEFBA4D792/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53299"
,(lldb)     command script import "/tmp/BDEFD15F-0940-424B-81B2-21CF259210AA/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-09 15:20:19.049 ThaliTest[1656:2969896] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C84A81E1-B001-4703-87FA-1714B2C53202/Library/Cookies/Cookies.binarycookies
,2016-02-09 15:20:19.418 ThaliTest[1656:2969896] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-09 15:20:19.419 ThaliTest[1656:2969896] Multi-tasking -> Device: YES, App: YES
,2016-02-09 15:20:19.429 ThaliTest[1656:2969896] Unlimited access to network resources
,2016-02-09 15:20:19.441 ThaliTest[1656:2969896] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-09 15:20:27.738 ThaliTest[1656:2969896] Resetting plugins due to page load.
,2016-02-09 15:20:30.628 ThaliTest[1656:2969896] Finished load of: file:///var/mobile/Containers/Bundle/Application/A2A570B2-4474-43B2-9C8A-C3EEFBA4D792/ThaliTest.app/www/index.html
,2016-02-09 15:20:30.802 ThaliTest[1656:2969896] JXcore Cordova plugin initializing
2016-02-09 15:20:30.806 ThaliTest[1656:2970205] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2A570B2-4474-43B2-9C8A-C3EEFBA4D792/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2A570B2-4474-43B2-9C8A-C3EEFBA4D792/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2A570B2-4474-43B2-9C8A-C3EEFBA4D792/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2A570B2-4474-43B2-9C8A-C3EEFBA4D792/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2A570B2-4474-43B2-9C8A-C3EEFBA4D792/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2A570B2-4474-43B2-9C8A-C3EEFBA4D792/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2A570B2-4474-43B2-9C8A-C3EEFBA4D792/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2A570B2-4474-43B2-9C8A-C3EEFBA4D792/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2A570B2-4474-43B2-9C8A-C3EEFBA4D792/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

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

,# #start should fail if called twice in a row

,# teardown

,ok 54 specific error should be received

,# setup

,# #startListeningForAdvertisements should fail if start not called

,# teardown

,ok 55 specific error should be returned

,# setup

,# should be able to call #stopListeningForAdvertisements many times

,# teardown

,ok 56 error should be null

,ok 57 error should be null

,# setup

,# should be able to call #startListeningForAdvertisements many times

,# teardown

,ok 58 error should be null

,ok 59 error should be null

,# setup

,# should be able to call #startUpdateAdvertisingAndListening many times

,# teardown

,ok 60 error should be null

,ok 61 error should be null

,# setup

,# #startUpdateAdvertisingAndListening should fail if start not called

,# teardown

,ok 62 specific error should be returned

,# setup

,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

,# teardown

,2016-02-09 15:24:44.501 ThaliTest[1656:2970205] jxcore: startBroadcasting
,2016-02-09 15:24:44.516 ThaliTest[1656:2970205] server: starting 1455027884501.1656.nwJDkw==
,2016-02-09 15:24:44.518 ThaliTest[1656:2970205] multipeer session: start timer: 0x170e0ab0
,2016-02-09 15:24:44.521 ThaliTest[1656:2970205] THEMultipeerSession initialized peer 1455027884501.1656
2016-02-09 15:24:44.522 ThaliTest[1656:2970205] jxcore: startBroadcasting: success
ok 63 Should be able to call startBroadcasting without error

201,6-02-09 15:24:44.525 ThaliTest[1656:2970205] jxcore: stopBroadcasting
2016-02-09 15:24:44.525 ThaliTest[1656:2970205] THEMultipeerSession stopping peer
,2016-02-09 15:24:44.525 ThaliTest[1656:2970205] multipeer session: stop timer
2016-02-09 15:24:44.531 ThaliTest[1656:2970205] jxcore: stopBroadcasting: success
ok 64 Should be able to call stopBroadcasting without error

2016-02-09 15:24:44.533 ThaliTe,st[1656:2970205] jxcore: startBroadcasting
,2016-02-09 15:24:44.543 ThaliTest[1656:2970205] server: starting 1455027884533.1656.psa5Hw==
2016-02-09 15:24:44.544 ThaliTest[1656:2970205] multipeer session: start timer: 0x17227a20
2016-02-09 15:24:44.545 ThaliTest[1656:2970205] THEMultipeerSession in,itialized peer 1455027884533.1656
2016-02-09 15:24:44.545 ThaliTest[1656:2970205] jxcore: startBroadcasting: success
ok 65 Should be able to call startBroadcasting without error

2016-02-09 15:24:44.548 ThaliTest[1656:2970205] jxcore: stopBroadcasting,
2016-02-09 15:24:44.548 ThaliTest[1656:2970205] THEMultipeerSession stopping peer
2016-02-09 15:24:44.549 ThaliTest[1656:2970205] multipeer session: stop timer
2016-02-09 15:24:44.549 ThaliTest[1656:2970205] jxcore: stopBroadcasting: success
ok 66 Shou,ld be able to call stopBroadcasting without error

2016-02-09 15:24:44.551 ThaliTest[1656:2970205] jxcore: startBroadcasting
,2016-02-09 15:24:44.568 ThaliTest[1656:2970205] server: starting 1455027884551.1656.eaJJBw==
,2016-02-09 15:24:44.572 ThaliTest[1656:2970205] multipeer session: start timer: 0x174d1310
,2016-02-09 15:24:44.578 ThaliTest[1656:2970205] THEMultipeerSession initialized peer 1455027884551.1656
,2016-02-09 15:24:44.581 ThaliTest[1656:2970205] jxcore: startBroadcasting: success
,ok 67 Should be able to call startBroadcasting without error

,2016-02-09 15:24:44.586 ThaliTest[1656:2970205] jxcore: stopBroadcasting
,2016-02-09 15:24:44.587 ThaliTest[1656:2970205] THEMultipeerSession stopping peer
,2016-02-09 15:24:44.589 ThaliTest[1656:2970205] multipeer session: stop timer
,2016-02-09 15:24:44.590 ThaliTest[1656:2970205] jxcore: stopBroadcasting: success
,ok 68 Should be able to call stopBroadcasting without error

,2016-02-09 15:24:44.596 ThaliTest[1656:2970205] jxcore: startBroadcasting
,2016-02-09 15:24:44.599 ThaliTest[1656:2970205] server: starting 1455027884596.1656.ciGApg==
,2016-02-09 15:24:44.601 ThaliTest[1656:2970205] multipeer session: start timer: 0x174cf5c0
2016-02-09 15:24:44.604 ThaliTest[1656:2970205] THEMultipeerSession initialized peer 1455027884596.1656
2016-02-09 15:24:44.604 ThaliTest[1656:2970205] jxcore: startBroadcasting: success
,ok 69 Should be able to call startBroadcasting without error
,
,2016-02-09 15:24:44.609 ThaliTest[1656:2970205] jxcore: stopBroadcasting
,2016-02-09 15:24:44.610 ThaliTest[1656:2970205] THEMultipeerSession stopping peer
,2016-02-09 15:24:44.610 ThaliTest[1656:2970205] multipeer session: stop timer
,2016-02-09 15:24:44.614 ThaliTest[1656:2970205] jxcore: stopBroadcasting: success
,ok 70 Should be able to call stopBroadcasting without error

,2016-02-09 15:24:44.617 ThaliTest[1656:2970205] jxcore: startBroadcasting
,2016-02-09 15:24:44.619 ThaliTest[1656:2970205] server: starting 1455027884616.1656.OdxSQA==
,2016-02-09 15:24:44.621 ThaliTest[1656:2970205] multipeer session: start timer: 0x172273f0
,2016-02-09 15:24:44.625 ThaliTest[1656:2970205] THEMultipeerSession initialized peer 1455027884616.1656
,2016-02-09 15:24:44.628 ThaliTest[1656:2970205] jxcore: startBroadcasting: success
,ok 71 Should be able to call startBroadcasting without error

,2016-02-09 15:24:44.630 ThaliTest[1656:2970205] jxcore: stopBroadcasting
2016-02-09 15:24:44.631 ThaliTest[1656:2970205] THEMultipeerSession stopping peer
,2016-02-09 15:24:44.632 ThaliTest[1656:2970205] multipeer session: stop timer
,2016-02-09 15:24:44.636 ThaliTest[1656:2970205] jxcore: stopBroadcasting: success
,ok 72 Should be able to call stopBroadcasting without error

,2016-02-09 15:24:44.639 ThaliTest[1656:2970205] jxcore: startBroadcasting
,2016-02-09 15:24:44.641 ThaliTest[1656:2970205] server: starting 1455027884638.1656.hKmclg==
,2016-02-09 15:24:44.643 ThaliTest[1656:2970205] multipeer session: start timer: 0x172286c0
,2016-02-09 15:24:44.646 ThaliTest[1656:2970205] THEMultipeerSession initialized peer 1455027884638.1656
,2016-02-09 15:24:44.649 ThaliTest[1656:2970205] jxcore: startBroadcasting: success
,ok 73 Should be able to call startBroadcasting without error
,
,2016-02-09 15:24:44.653 ThaliTest[1656:2970205] jxcore: stopBroadcasting
,2016-02-09 15:24:44.654 ThaliTest[1656:2970205] THEMultipeerSession stopping peer
,2016-02-09 15:24:44.654 ThaliTest[1656:2970205] multipeer session: stop timer
,2016-02-09 15:24:44.659 ThaliTest[1656:2970205] jxcore: stopBroadcasting: success
,ok 74 Should be able to call stopBroadcasting without error

,2016-02-09 15:24:44.662 ThaliTest[1656:2970205] jxcore: startBroadcasting
,2016-02-09 15:24:44.665 ThaliTest[1656:2970205] server: starting 1455027884661.1656.u1k9BA==
,2016-02-09 15:24:44.667 ThaliTest[1656:2970205] multipeer session: start timer: 0x174d2330
,2016-02-09 15:24:44.670 ThaliTest[1656:2970205] THEMultipeerSession initialized peer 1455027884661.1656
,2016-02-09 15:24:44.672 ThaliTest[1656:2970205] jxcore: startBroadcasting: success
,ok 75 Should be able to call startBroadcasting without error
,
,2016-02-09 15:24:44.676 ThaliTest[1656:2970205] jxcore: stopBroadcasting
2016-02-09 15:24:44.676 ThaliTest[1656:2970205] THEMultipeerSession stopping peer
2016-02-09 15:24:44.676 ThaliTest[1656:2970205] multipeer session: stop timer
,2016-02-09 15:24:44.679 ThaliTest[1656:2970205] jxcore: stopBroadcasting: success
,ok 76 Should be able to call stopBroadcasting without error
,
,2016-02-09 15:24:44.683 ThaliTest[1656:2970205] jxcore: startBroadcasting
,2016-02-09 15:24:44.686 ThaliTest[1656:2970205] server: starting 1455027884683.1656.0SCI4w==
,2016-02-09 15:24:44.689 ThaliTest[1656:2970205] multipeer session: start timer: 0x17237fb0
,2016-02-09 15:24:44.695 ThaliTest[1656:2970205] THEMultipeerSession initialized peer 1455027884683.1656
,2016-02-09 15:24:44.695 ThaliTest[1656:2970205] jxcore: startBroadcasting: success
,ok 77 Should be able to call startBroadcasting without error

,2016-02-09 15:24:44.697 ThaliTest[1656:2970205] jxcore: stopBroadcasting
,2016-02-09 15:24:44.698 ThaliTest[1656:2970205] THEMultipeerSession stopping peer
,2016-02-09 15:24:44.699 ThaliTest[1656:2970205] multipeer session: stop timer
,2016-02-09 15:24:44.700 ThaliTest[1656:2970205] jxcore: stopBroadcasting: success
,ok 78 Should be able to call stopBroadcasting without error

,2016-02-09 15:24:44.703 ThaliTest[1656:2970205] jxcore: startBroadcasting
,2016-02-09 15:24:44.706 ThaliTest[1656:2970205] server: starting 1455027884703.1656.sHI+QA==
,2016-02-09 15:24:44.708 ThaliTest[1656:2970205] multipeer session: start timer: 0x174d3510
,2016-02-09 15:24:44.711 ThaliTest[1656:2970205] THEMultipeerSession initialized peer 1455027884703.1656
,2016-02-09 15:24:44.712 ThaliTest[1656:2970205] jxcore: startBroadcasting: success
,ok 79 Should be able to call startBroadcasting without error

,2016-02-09 15:24:44.714 ThaliTest[1656:2970205] jxcore: stopBroadcasting
,2016-02-09 15:24:44.715 ThaliTest[1656:2970205] THEMultipeerSession stopping peer
,2016-02-09 15:24:44.715 ThaliTest[1656:2970205] multipeer session: stop timer
,2016-02-09 15:24:44.717 ThaliTest[1656:2970205] jxcore: stopBroadcasting: success
,ok 80 Should be able to call stopBroadcasting without error

,2016-02-09 15:24:44.720 ThaliTest[1656:2970205] jxcore: startBroadcasting
,2016-02-09 15:24:44.722 ThaliTest[1656:2970205] server: starting 1455027884720.1656.uUd8LQ==
,2016-02-09 15:24:44.724 ThaliTest[1656:2970205] multipeer session: start timer: 0x174d4390
,2016-02-09 15:24:44.728 ThaliTest[1656:2970205] THEMultipeerSession initialized peer 1455027884720.1656
,2016-02-09 15:24:44.728 ThaliTest[1656:2970205] jxcore: startBroadcasting: success
,ok 81 Should be able to call startBroadcasting without error

,2016-02-09 15:24:44.730 ThaliTest[1656:2970205] jxcore: stopBroadcasting
2016-02-09 15:24:44.730 ThaliTest[1656:2970205] THEMultipeerSession stopping peer
,2016-02-09 15:24:44.730 ThaliTest[1656:2970205] multipeer session: stop timer
,2016-02-09 15:24:44.732 ThaliTest[1656:2970205] jxcore: stopBroadcasting: success
,ok 82 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,# teardown

,2016-02-09 15:24:45.312 ThaliTest[1656:2970205] jxcore: startBroadcasting
,2016-02-09 15:24:45.316 ThaliTest[1656:2970205] server: starting 1455027885312.1656.SeROAg==
2016-02-09 15:24:45.316 ThaliTest[1656:2970205] multipeer session: start timer: 0x174d6090
2016-02-09 15:24:45.317 ThaliTest[1656:2970205] THEMultipeerSession in,itialized peer 1455027885312.1656
2016-02-09 15:24:45.318 ThaliTest[1656:2970205] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error

2016-02-09 15:24:45.320 ThaliTest[1656:2970205] jxcore: startBroadcasting,
2016-02-09 15:24:45.320 ThaliTest[1656:2970205] jxcore: startBroadcasting: failure
,ok 84 Cannot call startBroadcasting twice

2016-02-09 15:24:45.324 ThaliTest[1656:2970205] jxcore: stopBroadcasting
2016-02-09 15:24:45.325 ThaliTest[1656:2970205] THEMultipeerSession stopping peer
,2016-02-09 15:24:45.325 ThaliTest[1656:2970205] multipeer session: stop timer
,2016-02-09 15:24:45.334 ThaliTest[1656:2970205] jxcore: stopBroadcasting: success
,ok 85 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on connection to bad peer

,# teardown

,2016-02-09 15:24:45.514 ThaliTest[1656:2970205] jxcore: startBroadcasting
,2016-02-09 15:24:45.518 ThaliTest[1656:2970205] server: starting 1455027885514.1656.x9aGfw==
2016-02-09 15:24:45.519 ThaliTest[1656:2970205] multipeer session: start timer: 0x174d7af0
2016-02-09 15:24:45.519 ThaliTest[1656:2970205] THEMultipeerSession in,itialized peer 1455027885514.1656
2016-02-09 15:24:45.520 ThaliTest[1656:2970205] jxcore: startBroadcasting: success
ok 86 Should be able to call startBroadcasting without error

2016-02-09 15:24:45.522 ThaliTest[1656:2970205] jxcore: connect foobar
2,016-02-09 15:24:45.522 ThaliTest[1656:2970205] client: unknown peer foobar
2016-02-09 15:24:45.522 ThaliTest[1656:2970205] jxcore: connect: fail: Unknown peer
ok 87 Should not connect to a bad peer

,2016-02-09 15:24:45.526 ThaliTest[1656:2970205] jxcore: stopBroadcasting
2016-02-09 15:24:45.528 ThaliTest[1656:2970205] THEMultipeerSession stopping peer
2016-02-09 15:24:45.529 ThaliTest[1656:2970205] multipeer session: stop timer
2016-02-09 15:24:45.,529 ThaliTest[1656:2970205] jxcore: stopBroadcasting: success
ok 88 Should be able to call stopBroadcasting without error

# setup

,# ThaliEmitter throws on disconnect to bad peer

,# teardown

,2016-02-09 15:24:45.925 ThaliTest[1656:2970205] jxcore: startBroadcasting
,2016-02-09 15:24:45.929 ThaliTest[1656:2970205] server: starting 1455027885925.1656./5itGw==
2016-02-09 15:24:45.930 ThaliTest[1656:2970205] multipeer session: start timer: 0x1724f2e0
2016-02-09 15:24:45.930 ThaliTest[1656:2970205] THEMultipeerSession in,itialized peer 1455027885925.1656
2016-02-09 15:24:45.931 ThaliTest[1656:2970205] jxcore: startBroadcasting: success
ok 89 Should be able to call startBroadcasting without error

2016-02-09 15:24:45.933 ThaliTest[1656:2970205] jxcore: disconnect
2016-,02-09 15:24:45.933 ThaliTest[1656:2970205] jxcore: disconnect: fail
,ok 90 Disconnect should fail to a non-existant peer 

2016-02-09 15:24:45.938 ThaliTest[1656:2970205] jxcore: stopBroadcasting
2016-02-09 15:24:45.938 ThaliTest[1656:2970205] THEMultipeerSession stopping peer
2016-02-09 15:24:45.938 ThaliTest[1656:2970,205] multipeer session: stop timer
2016-02-09 15:24:45.939 ThaliTest[1656:2970205] jxcore: stopBroadcasting: success
,ok 91 Should be able to call stopBroadcasting without error

# setup

,# ThaliEmitter can discover and connect to peers

,# teardown

,2016-02-09 15:24:46.398 ThaliTest[1656:2970205] jxcore: startBroadcasting
,2016-02-09 15:24:46.402 ThaliTest[1656:2970205] server: starting 1455027886397.1656.QY39eg==
2016-02-09 15:24:46.402 ThaliTest[1656:2970205] multipeer session: start timer: 0x17293560
2016-02-09 15:24:46.403 ThaliTest[1656:2970205] THEMultipeerSession in,itialized peer 1455027886397.1656
2016-02-09 15:24:46.403 ThaliTest[1656:2970205] jxcore: startBroadcasting: success
,ok 92 Should be able to call startBroadcasting without error

,2016-02-09 15:24:47.218 ThaliTest[1656:2969896] client: found peer: 1455027887979.1112.D0vGWQ==
,2016-02-09 15:24:47.221 ThaliTest[1656:2970205] jxcore: connect 1455027887979.1112.D0vGWQ==
2016-02-09 15:24:47.222 ThaliTest[1656:2970205] client session: connect
2016-02-09 15:24:47.222 ThaliTest[1656:2970205] client session: stateChange:0->1 1455027887979.1112.D0vGWQ==
,2016-02-09 15:24:47.852 ThaliTest[1656:2969896] multipeer session: reset timer
2016-02-09 15:24:47.852 ThaliTest[1656:2969896] multipeer session: stop timer
2016-02-09 15:24:47.853 ThaliTest[1656:2969896] multipeer session: start timer: 0x17293560
2016-,02-09 15:24:47.853 ThaliTest[1656:2969896] server session: connect
2016-02-09 15:24:47.853 ThaliTest[1656:2969896] server session: stateChange:0->1 1455027887979.1112
,2016-02-09 15:24:47.863 ThaliTest[1656:2969896] server: accepting invitation 1455027887979.1112
,2016-02-09 15:24:50.333 ThaliTest[1656:2970673] client session: connected
,2016-02-09 15:24:50.333 ThaliTest[1656:2970673] client session: stateChange:1->2 1455027887979.1112.D0vGWQ==
,2016-02-09 15:24:50.351 ThaliTest[1656:2970678] client session: fireConnectCallback: 1455027887979.1112.D0vGWQ==
2016-02-09 15:24:50.352 ThaliTest[1656:2970678] jxcore: connect: success
,ok 93 Should be able to connect without error

,ok 94 Port should be within range

,2016-02-09 15:24:50.357 ThaliTest[1656:2970205] jxcore: disconnect
2016-02-09 15:24:50.357 ThaliTest[1656:2970205] client session: disconnectFromPeer: 1455027887979.1112.D0vGWQ==
,2016-02-09 15:24:50.362 ThaliTest[1656:2970205] client session: disconnect
,2016-02-09 15:24:50.365 ThaliTest[1656:2970205] client session: stateChange:2->0 1455027887979.1112.D0vGWQ==
,2016-02-09 15:24:50.386 ThaliTest[1656:2970205] jxcore: disconnect: success
ok 95 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,2016-02-09 15:24:50.425 ThaliTest[1656:2970709] server session: connected
2016-02-09 15:24:50.425 ThaliTest[1656:2970709] server session: stateChange:1->2 1455027887979.1112
,2016-02-09 15:24:50.453 ThaliTest[1656:2969896] server relay: socket disconnected
,2016-02-09 15:24:50.453 ThaliTest[1656:2969896] server relay: 0x172bc810 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-09 15:24:50.473 ThaliTest[1656:2970677] server session: not connected 1455027887979.1112
,calling stopBroadcasting

,2016-02-09 15:24:51.510 ThaliTest[1656:2970205] jxcore: stopBroadcasting
2016-02-09 15:24:51.511 ThaliTest[1656:2970205] THEMultipeerSession stopping peer
2016-02-09 15:24:51.511 ThaliTest[1656:2970205] multipeer session: stop timer
2016-02-09 15:24:51.,512 ThaliTest[1656:2970205] server session: disconnect
2016-02-09 15:24:51.512 ThaliTest[1656:2970205] server session: stateChange:2->0 1455027887979.1112
2016-02-09 15:24:51.513 ThaliTest[1656:2970205] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double connect

,# teardown

,2016-02-09 15:24:51.811 ThaliTest[1656:2970205] jxcore: startBroadcasting
,2016-02-09 15:24:51.815 ThaliTest[1656:2970205] server: starting 1455027891810.1656./UnS+w==
2016-02-09 15:24:51.815 ThaliTest[1656:2970205] multipeer session: start timer: 0x172ab730
2016-02-09 15:24:51.816 ThaliTest[1656:2970205] THEMultipeerSession in,itialized peer 1455027891810.1656
2016-02-09 15:24:51.816 ThaliTest[1656:2970205] jxcore: startBroadcasting: success
ok 96 Should be able to call startBroadcasting without error

,2016-02-09 15:24:52.884 ThaliTest[1656:2969896] client: found peer: 1455027893387.1112.SYMpiA==
2016-02-09 15:24:52.886 ThaliTest[1656:2970205] jxcore: connect 1455027893387.1112.SYMpiA==
2016-02-09 15:24:52.886 ThaliTest[1656:2970205] client session: co,nnect
2016-02-09 15:24:52.886 ThaliTest[1656:2970205] client session: stateChange:0->1 1455027893387.1112.SYMpiA==
,2016-02-09 15:24:52.946 ThaliTest[1656:2969896] multipeer session: reset timer
2016-02-09 15:24:52.947 ThaliTest[1656:2969896] multipeer session: stop timer
2016-02-09 15:24:52.947 ThaliTest[1656:2969896] multipeer session: start timer: 0x172ab730
,2016-02-09 15:24:52.947 ThaliTest[1656:2969896] server session: connect
2016-02-09 15:24:52.950 ThaliTest[1656:2969896] server session: stateChange:0->1 1455027893387.1112
,2016-02-09 15:24:52.958 ThaliTest[1656:2969896] server: accepting invitation 1455027893387.1112
,2016-02-09 15:24:55.363 ThaliTest[1656:2970673] server session: connected
2016-02-09 15:24:55.363 ThaliTest[1656:2970673] server session: stateChange:1->2 1455027893387.1112
,2016-02-09 15:24:55.396 ThaliTest[1656:2969896] server relay: socket disconnected
2016-02-09 15:24:55.396 ThaliTest[1656:2969896] server relay: 0x172bcce0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-09 15:24:55.444 ThaliTest[1656:2970709] server session: not connected 1455027893387.1112
,2016-02-09 15:24:55.517 ThaliTest[1656:2970709] client session: connected
2016-02-09 15:24:55.517 ThaliTest[1656:2970709] client session: stateChange:1->2 1455027893387.1112.SYMpiA==
,2016-02-09 15:24:55.558 ThaliTest[1656:2970715] client session: fireConnectCallback: 1455027893387.1112.SYMpiA==
2016-02-09 15:24:55.558 ThaliTest[1656:2970715] jxcore: connect: success
,ok 97 Should be able to connect without error

,ok 98 Port should be within range

,2016-02-09 15:24:55.563 ThaliTest[1656:2970205] jxcore: connect 1455027893387.1112.SYMpiA==
2016-02-09 15:24:55.563 ThaliTest[1656:2970205] client: already connect(ing/ed) to 1455027893387.1112.SYMpiA==
2016-02-09 15:24:55.564 ThaliTest[1656:2970205] jxc,ore: connect: fail: Aleady connecting
,ok 99 Should fail on double connect

,2016-02-09 15:24:55.568 ThaliTest[1656:2970205] jxcore: disconnect
2016-02-09 15:24:55.569 ThaliTest[1656:2970205] client session: disconnectFromPeer: 1455027893387.1112.SYMpiA==
2016-02-09 15:24:55.569 ThaliTest[1656:2970205] client session: disconnect,
2016-02-09 15:24:55.570 ThaliTest[1656:2970205] client session: stateChange:2->0 1455027893387.1112.SYMpiA==
,2016-02-09 15:24:55.584 ThaliTest[1656:2970205] jxcore: disconnect: success
ok 100 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-02-09 15:24:58.480 ThaliTest[1656:2970205] jxcore: stopBroadcasting
2016-02-09 15:24:58.480 ThaliTest[1656:2970205] THEMultipeerSession stopping peer
2016-02-09 15:24:58.480 ThaliTest[1656:2970205] multipeer session: stop timer
2016-02-09 15:24:58.,481 ThaliTest[1656:2970205] server session: disconnect
2016-02-09 15:24:58.481 ThaliTest[1656:2970205] server session: stateChange:2->0 1455027893387.1112
,2016-02-09 15:24:58.482 ThaliTest[1656:2970205] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,# teardown

,2016-02-09 15:25:13.363 ThaliTest[1656:2970205] jxcore: startBroadcasting
,2016-02-09 15:25:13.367 ThaliTest[1656:2970205] server: starting 1455027913363.1656.wtaGUA==
2016-02-09 15:25:13.368 ThaliTest[1656:2970205] multipeer session: start timer: 0x161b3030
2016-02-09 15:25:13.368 ThaliTest[1656:2970205] THEMultipeerSession in,itialized peer 1455027913363.1656
2016-02-09 15:25:13.369 ThaliTest[1656:2970205] jxcore: startBroadcasting: success
,ok 101 Should be able to call startBroadcasting without error

,2016-02-09 15:25:14.448 ThaliTest[1656:2969896] client: found peer: 1455027914797.1112.3mgFjw==
2016-02-09 15:25:14.450 ThaliTest[1656:2970205] jxcore: connect 1455027914797.1112.3mgFjw==
,2016-02-09 15:25:14.450 ThaliTest[1656:2970205] client session: connect
2016-02-09 15:25:14.451 ThaliTest[1656:2970205] client session: stateChange:0->1 1455027914797.1112.3mgFjw==
,2016-02-09 15:25:14.906 ThaliTest[1656:2969896] multipeer session: reset timer
2016-02-09 15:25:14.907 ThaliTest[1656:2969896] multipeer session: stop timer
,2016-02-09 15:25:14.907 ThaliTest[1656:2969896] multipeer session: start timer: 0x161b3030
2016-02-09 15:25:14.909 ThaliTest[1656:2969896] server session: connect
2016-02-09 15:25:14.909 ThaliTest[1656:2969896] server session: stateChange:0->1 1455027914797.1112
2016-02-09 15:25:14.921 ThaliTest[1656:2969896] server: accepting invitation 1455027914797.1112
,2016-02-09 15:25:17.655 ThaliTest[1656:2970786] client session: connected
2016-02-09 15:25:17.656 ThaliTest[1656:2970786] client session: stateChange:1->2 1455027914797.1112.3mgFjw==
,2016-02-09 15:25:17.668 ThaliTest[1656:2970767] client session: fireConnectCallback: 1455027914797.1112.3mgFjw==
2016-02-09 15:25:17.668 ThaliTest[1656:2970767] jxcore: connect: success
ok 102 Should be able to connect without error

ok 103 Port should, be within range

2016-02-09 15:25:17.671 ThaliTest[1656:2970205] jxcore: disconnect
2016-02-09 15:25:17.672 ThaliTest[1656:2970205] client session: disconnectFromPeer: 1455027914797.1112.3mgFjw==
2016-02-09 15:25:17.672 ThaliTest[1656:2970205] client ,session: disconnect
2016-02-09 15:25:17.672 ThaliTest[1656:2970205] client session: stateChange:2->0 1455027914797.1112.3mgFjw==
,2016-02-09 15:25:17.758 ThaliTest[1656:2970205] jxcore: disconnect: success
,ok 104 Should be able to disconnect without error

,2016-02-09 15:25:17.761 ThaliTest[1656:2970205] jxcore: disconnect
,2016-02-09 15:25:17.761 ThaliTest[1656:2970205] jxcore: disconnect: fail
,ok 105 Disconnect should fail 

,setting stopBroadcasting callback and ending test.
,
,# setup

,2016-02-09 15:25:17.785 ThaliTest[1656:2970768] server session: connected
,2016-02-09 15:25:17.785 ThaliTest[1656:2970768] server session: stateChange:1->2 1455027914797.1112
,2016-02-09 15:25:17.799 ThaliTest[1656:2969896] server relay: socket disconnected
,2016-02-09 15:25:17.800 ThaliTest[1656:2969896] server relay: 0x161b3fe0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection ,refused} 
,2016-02-09 15:25:18.052 ThaliTest[1656:2970767] server session: not connected 1455027914797.1112
,calling stopBroadcasting

,2016-02-09 15:25:18.527 ThaliTest[1656:2970205] jxcore: stopBroadcasting
2016-02-09 15:25:18.528 ThaliTest[1656:2970205] THEMultipeerSession stopping peer
2016-02-09 15:25:18.528 ThaliTest[1656:2970205] multipeer session: stop timer
2016-02-09 15:25:18.,528 ThaliTest[1656:2970205] server session: disconnect
2016-02-09 15:25:18.529 ThaliTest[1656:2970205] server session: stateChange:2->0 1455027914797.1112
,2016-02-09 15:25:18.531 ThaliTest[1656:2970205] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter can connect and send data

,# teardown

,echo server started on port: 60126

,2016-02-09 15:25:21.554 ThaliTest[1656:2970205] jxcore: startBroadcasting
,2016-02-09 15:25:21.555 ThaliTest[1656:2970205] server: starting 1455027921553.1656.tNBT+A==
2016-02-09 15:25:21.555 ThaliTest[1656:2970205] multipeer session: start timer: 0x1724efc0
2016-02-09 15:25:21.556 ThaliTest[1656:2970205] THEMultipeerSession in,itialized peer 1455027921553.1656
2016-02-09 15:25:21.556 ThaliTest[1656:2970205] jxcore: startBroadcasting: success
ok 106 Should be able to call startBroadcasting without error

,2016-02-09 15:25:21.766 ThaliTest[1656:2969896] client: found peer: 1455027914797.1112.3mgFjw==
,2016-02-09 15:25:21.767 ThaliTest[1656:2970205] jxcore: connect 1455027914797.1112.3mgFjw==
2016-02-09 15:25:21.767 ThaliTest[1656:2970205] client session: connect
2016-02-09 15:25:21.767 ThaliTest[1656:2970205] client session: stateChange:0->1 1455027914797.1112.3mgFjw==
,2016-02-09 15:25:22.934 ThaliTest[1656:2969896] client: found peer: 1455027923092.1112.F6XCDg==
,2016-02-09 15:25:22.936 ThaliTest[1656:2970205] jxcore: connect 1455027923092.1112.F6XCDg==
2016-02-09 15:25:22.937 ThaliTest[1656:2970205] client session: connect
2016-02-09 15:25:22.937 ThaliTest[1656:2970205] client session: stateChange:0->1 1455027923092.1112.F6XCDg==
,2016-02-09 15:25:23.322 ThaliTest[1656:2969896] multipeer session: reset timer
2016-02-09 15:25:23.323 ThaliTest[1656:2969896] multipeer session: stop timer
2016-02-09 15:25:23.323 ThaliTest[1656:2969896] multipeer session: start timer: 0x1724efc0
2016-,02-09 15:25:23.323 ThaliTest[1656:2969896] server session: connect
2016-02-09 15:25:23.324 ThaliTest[1656:2969896] server session: stateChange:0->1 1455027923092.1112
,2016-02-09 15:25:23.334 ThaliTest[1656:2969896] server: accepting invitation 1455027923092.1112
,2016-02-09 15:25:25.743 ThaliTest[1656:2970782] client session: connected
2016-02-09 15:25:25.744 ThaliTest[1656:2970782] client session: stateChange:1->2 1455027923092.1112.F6XCDg==
,2016-02-09 15:25:25.794 ThaliTest[1656:2970782] client session: fireConnectCallback: 1455027923092.1112.F6XCDg==
,2016-02-09 15:25:25.796 ThaliTest[1656:2970782] jxcore: connect: success
,ok 107 Should be able to connect without error

,ok 108 Port should be within range

,2016-02-09 15:25:25.807 ThaliTest[1656:2969896] client: relay established
,2016-02-09 15:25:25.808 ThaliTest[1656:2969896] client: new accepted socket: 0x167f5200
,2016-02-09 15:25:25.835 ThaliTest[1656:2970768] server session: connected
,2016-02-09 15:25:25.838 ThaliTest[1656:2970768] server session: stateChange:1->2 1455027923092.1112
,2016-02-09 15:25:25.936 ThaliTest[1656:2969896] server relay: connected (to port: 60126)
,data in 15330

,data in 41610

,data in 43800

,data in 54750
,
,data in 71175
,
,data in 88695
,
,data in 101835

,data in 111690

,data in 131072

,ok 109 the test messages should be equal

,2016-02-09 15:25:26.190 ThaliTest[1656:2970205] jxcore: disconnect
,2016-02-09 15:25:26.190 ThaliTest[1656:2970205] client session: disconnectFromPeer: 1455027923092.1112.F6XCDg==
,2016-02-09 15:25:26.190 ThaliTest[1656:2970205] client session: disconnect
,2016-02-09 15:25:26.191 ThaliTest[1656:2970205] client session: stateChange:2->0 1455027923092.1112.F6XCDg==
,2016-02-09 15:25:26.232 ThaliTest[1656:2970782] server session: not connected 1455027923092.1112
,2016-02-09 15:25:26.262 ThaliTest[1656:2970205] jxcore: disconnect: success
,ok 110 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.
,
,# setup

,calling stopBroadcasting

,2016-02-09 15:25:26.322 ThaliTest[1656:2970205] jxcore: stopBroadcasting
2016-02-09 15:25:26.323 ThaliTest[1656:2970205] THEMultipeerSession stopping peer
2016-02-09 15:25:26.323 ThaliTest[1656:2970205] multipeer session: stop timer
2016-02-09 15:25:26.,323 ThaliTest[1656:2970205] client session: disconnect
2016-02-09 15:25:26.324 ThaliTest[1656:2970205] client session: stateChange:1->0 1455027914797.1112.3mgFjw==
2016-02-09 15:25:26.324 ThaliTest[1656:2970205] server session: disconnect
2016-02-09 15:25:26.324 ThaliTest[1656:2970205] server session: stateChange:2->0 1455027923092.1112
,2016-02-09 15:25:26.340 ThaliTest[1656:2970205] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter handles socket disconnect correctly

,# teardown

,echo server started on port: 60133

,2016-02-09 15:25:26.837 ThaliTest[1656:2970205] jxcore: startBroadcasting
,2016-02-09 15:25:26.841 ThaliTest[1656:2970205] server: starting 1455027926836.1656.x1ojrQ==
2016-02-09 15:25:26.841 ThaliTest[1656:2970205] multipeer session: start timer: 0x162653a0
2016-02-09 15:25:26.842 ThaliTest[1656:2970205] THEMultipeerSession in,itialized peer 1455027926836.1656
2016-02-09 15:25:26.842 ThaliTest[1656:2970205] jxcore: startBroadcasting: success
ok 111 Should be able to call startBroadcasting without error

,2016-02-09 15:25:27.569 ThaliTest[1656:2969896] client: found peer: 1455027923092.1112.F6XCDg==
[{"peerIdentifier":"1455027923092.1112.F6XCDg==","peerName":"(null)","peerAvailable":true}]

2016-02-09 15:25:27.571 ThaliTest[1656:2970205] jxcore: connect ,1455027923092.1112.F6XCDg==
2016-02-09 15:25:27.572 ThaliTest[1656:2970205] client session: connect
2016-02-09 15:25:27.572 ThaliTest[1656:2970205] client session: stateChange:0->1 1455027923092.1112.F6XCDg==
,2016-02-09 15:25:27.816 ThaliTest[1656:2969896] multipeer session: reset timer
2016-02-09 15:25:27.816 ThaliTest[1656:2969896] multipeer session: stop timer
2016-02-09 15:25:27.817 ThaliTest[1656:2969896] multipeer session: start timer: 0x162653a0
2016-02-09 15:25:27.817 ThaliTest[1656:2969896] server session: connect
,2016-02-09 15:25:27.817 ThaliTest[1656:2969896] server session: stateChange:0->1 1455027928427.1112
,2016-02-09 15:25:27.826 ThaliTest[1656:2969896] server: accepting invitation 1455027928427.1112
,2016-02-09 15:25:28.029 ThaliTest[1656:2969896] client: found peer: 1455027928427.1112.k6j4Ag==
[{"peerIdentifier":"1455027928427.1112.k6j4Ag==","peerName":"(null)","peerAvailable":true}]

,2016-02-09 15:25:28.031 ThaliTest[1656:2970205] jxcore: connect 1455027928427.1112.k6j4Ag==
2016-02-09 15:25:28.031 ThaliTest[1656:2970205] client session: connect
2016-02-09 15:25:28.031 ThaliTest[1656:2970205] client session: stateChange:0->1 1455027928427.1112.k6j4Ag==
,2016-02-09 15:25:30.355 ThaliTest[1656:2970795] server session: connected
,2016-02-09 15:25:30.356 ThaliTest[1656:2970795] server session: stateChange:1->2 1455027928427.1112
,2016-02-09 15:25:30.369 ThaliTest[1656:2969896] server relay: connected (to port: 60133)
,2016-02-09 15:25:30.554 ThaliTest[1656:2970769] server session: not connected 1455027928427.1112
,2016-02-09 15:25:30.598 ThaliTest[1656:2969896] multipeer session: reset timer
2016-02-09 15:25:30.598 ThaliTest[1656:2969896] multipeer session: stop timer
2016-02-09 15:25:30.598 ThaliTest[1656:2969896] multipeer session: start timer: 0x162653a0
2016-,02-09 15:25:30.599 ThaliTest[1656:2969896] server: disconnecting to refresh session (1455027928427.1112)
2016-02-09 15:25:30.599 ThaliTest[1656:2969896] server session: disconnect
2016-02-09 15:25:30.599 ThaliTest[1656:2969896] server session: stateChang,e:2->0 1455027928427.1112
,2016-02-09 15:25:30.605 ThaliTest[1656:2969896] server session: connect
2016-02-09 15:25:30.605 ThaliTest[1656:2969896] server session: stateChange:0->1 1455027928427.1112
,2016-02-09 15:25:30.624 ThaliTest[1656:2969896] server: accepting invitation 1455027928427.1112
,2016-02-09 15:25:30.785 ThaliTest[1656:2970795] client session: connected
2016-02-09 15:25:30.789 ThaliTest[1656:2970795] client session: stateChange:1->2 1455027928427.1112.k6j4Ag==
,2016-02-09 15:25:30.829 ThaliTest[1656:2970782] client session: fireConnectCallback: 1455027928427.1112.k6j4Ag==
2016-02-09 15:25:30.830 ThaliTest[1656:2970782] jxcore: connect: success
ok 112 Should be able to connect without error

ok 113 Port should be within range

ok 114 First connect should succeed

,2016-02-09 15:25:30.859 ThaliTest[1656:2969896] client: relay established
2016-02-09 15:25:30.860 ThaliTest[1656:2969896] client: new accepted socket: 0x16113840
,ok 115 the test messages should be equal

,ok 116 First send should succeed

,2016-02-09 15:25:30.913 ThaliTest[1656:2969896] client: socket closed
2016-02-09 15:25:30.914 ThaliTest[1656:2969896] client relay: socket disconnected
2016-02-09 15:25:30.914 ThaliTest[1656:2969896] client relay: 0x16113840 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-02-09 15:25:30.914 ThaliTest[1656:2969896] client session: socket closed: 1455027928427.1112.k6j4Ag==
2016-02-09 ,15:25:30.914 ThaliTest[1656:2969896] client session: onLinkFailure: 1455027928427.1112.k6j4Ag==
2016-02-09 15:25:30.914 ThaliTest[1656:2969896] client session: disconnect
2016-02-09 15:25:30.915 ThaliTest[1656:2969896] client session: stateChange:2->0 14,55027928427.1112.k6j4Ag==
,2016-02-09 15:25:30.925 ThaliTest[1656:2969896] client session: fireConnectionErrorEvent: 1455027928427.1112.k6j4Ag==
2016-02-09 15:25:30.928 ThaliTest[1656:2970205] jxcore: connect 1455027928427.1112.k6j4Ag==
2016-02-09 15:25:30.928 ThaliTest[1656:29702,05] client session: connect
2016-02-09 15:25:30.928 ThaliTest[1656:2970205] client session: stateChange:0->1 1455027928427.1112.k6j4Ag==
,2016-02-09 15:25:39.000 ThaliTest[1656:2970782] client session: connected
2016-02-09 15:25:39.001 ThaliTest[1656:2970782] client session: stateChange:1->2 1455027928427.1112.k6j4Ag==
,2016-02-09 15:25:39.009 ThaliTest[1656:2970782] server session: connected
2016-02-09 15:25:39.010 ThaliTest[1656:2970782] server session: stateChange:1->2 1455027928427.1112
,2016-02-09 15:25:40.963 ThaliTest[1656:2970782] client session: fireConnectCallback: 1455027928427.1112.k6j4Ag==
2016-02-09 15:25:40.963 ThaliTest[1656:2970782] jxcore: connect: success
ok 117 Should be able to connect without error

ok 118 Port should, be within range

,ok 119 Second connect should succeed

,2016-02-09 15:25:40.998 ThaliTest[1656:2969896] client: relay established
,2016-02-09 15:25:40.999 ThaliTest[1656:2969896] client: new accepted socket: 0x167f5200
,2016-02-09 15:25:41.533 ThaliTest[1656:2969896] server relay: connected (to port: 60133)
,ok 120 the test messages should be equal

,ok 121 Second send should succeed

,# setup

,2016-02-09 15:25:42.761 ThaliTest[1656:2969896] client: socket closed
2016-02-09 15:25:42.761 ThaliTest[1656:2969896] client relay: socket disconnected
2016-02-09 15:25:42.761 ThaliTest[1656:2969896] client relay: 0x167f5200 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-02-09 15:25:42.762 ThaliTest[1656:2969896] client session: socket closed: 1455027928427.1112.k6j4Ag==
2016-02-09 ,15:25:42.762 ThaliTest[1656:2969896] client session: onLinkFailure: 1455027928427.1112.k6j4Ag==
2016-02-09 15:25:42.762 ThaliTest[1656:2969896] client session: disconnect
2016-02-09 15:25:42.762 ThaliTest[1656:2969896] client session: stateChange:2->0 14,55027928427.1112.k6j4Ag==
,2016-02-09 15:25:42.768 ThaliTest[1656:2969896] client session: fireConnectionErrorEvent: 1455027928427.1112.k6j4Ag==
,calling stopBroadcasting

,2016-02-09 15:25:46.049 ThaliTest[1656:2970205] jxcore: stopBroadcasting
2016-02-09 15:25:46.049 ThaliTest[1656:2970205] THEMultipeerSession stopping peer
2016-02-09 15:25:46.049 ThaliTest[1656:2970205] multipeer session: stop timer
2016-02-09 15:25:46.,050 ThaliTest[1656:2970205] client session: disconnect
2016-02-09 15:25:46.050 ThaliTest[1656:2970205] client session: stateChange:1->0 1455027923092.1112.F6XCDg==
2016-02-09 15:25:46.051 ThaliTest[1656:2970205] server session: disconnect
2016-02-09 15:,25:46.051 ThaliTest[1656:2970205] server session: stateChange:2->0 1455027928427.1112
,2016-02-09 15:25:46.067 ThaliTest[1656:2970205] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliReplicationManager can call start without error

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/C84A81E1-B001-4703-87FA-1714B2C53202/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,ok 122 starting event should occur in right order

,2016-02-09 15:25:46.443 ThaliTest[1656:2970205] jxcore: startBroadcasting
,2016-02-09 15:25:46.445 ThaliTest[1656:2970205] server: starting CqTws3O_Kmbx6iHoCFOQOw.G2hH7Q==
2016-02-09 15:25:46.445 ThaliTest[1656:2970205] multipeer session: start timer: 0x14ea1520
2016-02-09 15:25:46.445 ThaliTest[1656:2970205] THEMultipeerSession initialized peer CqTws3O_Kmbx6iHoCFOQOw
2016-02-09 15:25:46.445 ThaliTest[1656:2970205] jxcore: startBroadcasting: success
ok 123 started event should occur in right order

Now in TRM stop

State of this._isStarted: true

ok 124 stopping event sh,ould occur in right order

About to call stopBroadcasting

2016-02-09 15:25:46.447 ThaliTest[1656:2970205] jxcore: stopBroadcasting
2016-02-09 15:25:46.447 ThaliTest[1656:2970205] THEMultipeerSession stopping peer
2016-02-09 15:25:46.447 ThaliTest[1656:2970205] multipeer session: stop timer
2016-02-09 15:25:46.447 ThaliTest[1656:2970205] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined

ok 125 stopped event should occur in right order

,mux server bridge listener closed

# setup

,# ThaliReplicationManager receives identity

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/C84A81E1-B001-4703-87FA-1714B2C53202/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-02-09 15:25:47.320 ThaliTest[1656:2970205] jxcore: startBroadcasting
,2016-02-09 15:25:47.324 ThaliTest[1656:2970205] server: starting CqTws3O_Kmbx6iHoCFOQOw.Vbhikg==
2016-02-09 15:25:47.324 ThaliTest[1656:2970205] multipeer session: start timer: 0x1724f040
2016-02-09 15:25:47.325 ThaliTest[1656:2970205] THEMultipeerSessio,n initialized peer CqTws3O_Kmbx6iHoCFOQOw
2016-02-09 15:25:47.325 ThaliTest[1656:2970205] jxcore: startBroadcasting: success
ok 126 getDeviceIdentity should not return an error

ok 127 deviceName should not be null

Now in TRM stop

State of this._isStarted: true

,About to call stopBroadcasting

2016-02-09 15:25:47.329 ThaliTest[1656:2970205] jxcore: stopBroadcasting
2016-02-09 15:25:47.330 ThaliTest[1656:2970205] THEMultipeerSession stopping peer
,2016-02-09 15:25:47.330 ThaliTest[1656:2970205] multipeer session: stop timer
,2016-02-09 15:25:47.331 ThaliTest[1656:2970205] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,mux server bridge listener closed

# setup

,# ThaliReplicationManager replicates database

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/C84A81E1-B001-4703-87FA-1714B2C53202/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-02-09 15:25:50.406 ThaliTest[1656:2970205] jxcore: startBroadcasting
,2016-02-09 15:25:50.407 ThaliTest[1656:2970205] server: starting CqTws3O_Kmbx6iHoCFOQOw.9t0p+g==
2016-02-09 15:25:50.407 ThaliTest[1656:2970205] multipeer session: start timer: 0x17153a60
2016-02-09 15:25:50.407 ThaliTest[1656:2970205] THEMultipeerSession initialized peer CqTws3O_Kmbx6iHoCFOQOw
2016-02-09 15:25:50.408 ThaliTest[1656:2970205] jxcore: startBroadcasting: success
ok 128 getDeviceIdentity should not return an error

ok 129 deviceName should not be null

,2016-02-09 15:25:51.303 ThaliTest[1656:2969896] client: found peer: nNJbi8ca0mhCyrEBAuD8rA.eoriNA==
,2016-02-09 15:25:54.852 ThaliTest[1656:2969896] client: found peer: 1455027928427.1112.k6j4Ag==
,2016-02-09 15:25:54.880 ThaliTest[1656:2970205] jxcore: connect nNJbi8ca0mhCyrEBAuD8rA.eoriNA==
2016-02-09 15:25:54.881 ThaliTest[1656:2970205] client session: connect
,2016-02-09 15:25:54.881 ThaliTest[1656:2970205] client session: stateChange:0->1 nNJbi8ca0mhCyrEBAuD8rA.eoriNA==
,2016-02-09 15:25:54.885 ThaliTest[1656:2969896] client: lost peer: 1455027928427.1112.k6j4Ag==
2016-02-09 15:25:54.885 ThaliTest[1656:2969896] client session: onPeerLost: 1455027928427.1112.k6j4Ag==
,2016-02-09 15:25:54.888 ThaliTest[1656:2970205] jxcore: connect 1455027928427.1112.k6j4Ag==
2016-02-09 15:25:54.888 ThaliTest[1656:2970205] client: connect: unreachable 1455027928427.1112.k6j4Ag==
2016-02-09 15:25:54.888 ThaliTest[1656:2970205] jxcore: c,onnect: fail: Peer unreachable
Connect error with error: Error: Peer unreachable

,2016-02-09 15:25:54.947 ThaliTest[1656:2970205] jxcore: disconnect
2016-02-09 15:25:54.948 ThaliTest[1656:2970205] jxcore: disconnect: fail
Disconnect error with error: Error: Not connected to specified peer

peerIdentifier not available 1455027928427.1112.k6j4Ag==

,ok 130 Should be able to put doc without error

,ok 131 1st change of local doc should contain local id

,2016-02-09 15:25:55.135 ThaliTest[1656:2969896] multipeer session: reset timer
2016-02-09 15:25:55.135 ThaliTest[1656:2969896] multipeer session: stop timer
2016-02-09 15:25:55.135 ThaliTest[1656:2969896] multipeer session: start timer: 0x17153a60
2016-02-09 15:25:55.136 ThaliTest[1656:2969896] server session: connect
2016-02-09 15:25:55.136 ThaliTest[1656:2969896] server session: stateChange:0->1 nNJbi8ca0mhCyrEBAuD8rA
2016-02-09 15:25:55.139 ThaliTest[1656:2969896] server: accepting invitation nNJbi8ca0mhCyrEBAuD8rA
,2016-02-09 15:25:57.130 ThaliTest[1656:2970769] client session: connected
2016-02-09 15:25:57.130 ThaliTest[1656:2970769] client session: stateChange:1->2 nNJbi8ca0mhCyrEBAuD8rA.eoriNA==
,2016-02-09 15:25:57.860 ThaliTest[1656:2970821] server session: connected
2016-02-09 15:25:57.860 ThaliTest[1656:2970821] server session: stateChange:1->2 nNJbi8ca0mhCyrEBAuD8rA
,2016-02-09 15:25:57.883 ThaliTest[1656:2969896] server relay: connected (to port: 60149)
,server bridge: new client socket

,2016-02-09 15:25:58.072 ThaliTest[1656:2970821] client session: fireConnectCallback: nNJbi8ca0mhCyrEBAuD8rA.eoriNA==
2016-02-09 15:25:58.072 ThaliTest[1656:2970821] jxcore: connect: success
,2016-02-09 15:25:58.100 ThaliTest[1656:2969896] client: relay established
2016-02-09 15:25:58.101 ThaliTest[1656:2969896] client: new accepted socket: 0x174e6690
,client bridge: new client socket
,
,client bridge: new client socket

,client bridge: socket closed

,client bridge: socket closed
,
,client bridge: new client socket
,
,client bridge: new client socket
,
,client bridge: socket closed

,client bridge: socket closed
,
,client bridge: new client socket
,
,client bridge: new client socket

,client bridge: socket closed

client bridge: socket closed
,
,client bridge: new client socket

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed
,
,client bridge: new client socket
,
,client bridge: socket closed

client bridge: socket closed

,client bridge: socket closed

,client bridge: new client socket
,
,ok 132 1st change of remote doc should contain remote id

,ok 133 Can update remote doc without error

,null

,{ ok: true,
,  id: '93eaf857-2799-4a01-94d2-60b187c8e1aa',
,  rev: '2-6bf9bd35b9d30415720897fd1b75c45e' }
,
,client bridge: new client socket
,
,ok 134 Remote changes occur in strict order

,client bridge: socket closed

,client bridge: new client socket
,
,client bridge: socket closed

,client bridge: new client socket
,
,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed
,
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

,ok 135 Local changes occur in strict order

,ok 136 2nd change of local doc should contain remote id

,# setup

,client bridge: socket closed

,client bridge: new client socket
,
,client bridge: new client socket
,
,client bridge: socket closed

,client bridge: new client socket
,
,client bridge: socket closed

,Now in TRM stop

,State of this._isStarted: true
,
,About to call stopBroadcasting

,2016-02-09 15:26:08.306 ThaliTest[1656:2970205] jxcore: stopBroadcasting
,2016-02-09 15:26:08.307 ThaliTest[1656:2970205] THEMultipeerSession stopping peer
,2016-02-09 15:26:08.309 ThaliTest[1656:2970205] multipeer session: stop timer
,2016-02-09 15:26:08.311 ThaliTest[1656:2970205] client session: disconnect
,2016-02-09 15:26:08.314 ThaliTest[1656:2970205] client session: stateChange:2->0 nNJbi8ca0mhCyrEBAuD8rA.eoriNA==
,2016-02-09 15:26:08.339 ThaliTest[1656:2970954] server session: not connected nNJbi8ca0mhCyrEBAuD8rA
,2016-02-09 15:26:08.424 ThaliTest[1656:2970205] server session: disconnect
,2016-02-09 15:26:08.426 ThaliTest[1656:2970205] server session: stateChange:2->0 nNJbi8ca0mhCyrEBAuD8rA
,2016-02-09 15:26:08.435 ThaliTest[1656:2970205] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined
,
,mux server bridge listener closed

,2016-02-09 15:26:08.481 ThaliTest[1656:2970205] Error!: connect ECONNREFUSED
Stack:[{"_fileName":"net.js","_functionName":"$c","_lineNumber":"837","_columnNumber":"7","_msg":"    at $c@net.js:837:7"},{"_fileName":"net.js","_functionName":"$09","_lineNumbe,r":"829","_columnNumber":"13","_msg":"    at $09@net.js:829:13"},{"_fileName":"net.js","_functionName":"unknown","_lineNumber":"837","_columnNumber":"7","_msg":""}]
,Uncaught Exception: Error: connect ECONNREFUSED

,[ { _fileName: 'net.js',
    _functionName: '$c',
    _lineNumber: '837',
    _columnNumber: '7',
    _msg: '    at $c@net.js:837:7' },
  { _fileName: 'net.js',
    _functionName: '$09',
    _lineNumber: '829',
,    _columnNumber: '13',
    _msg: '    at $09@net.js:829:13' },
  { _fileName: 'net.js',
    _functionName: 'unknown',
,    _lineNumber: '837',
,    _columnNumber: '7',
    _msg: '' },
,  toString: [Function] ]
,
,****TEST TOOK:  ms ****

,****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****


```
