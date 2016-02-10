#### Test 58752353dc32d9f_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/58752353dc32d9f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/F36D8563-555D-41C7-AE11-6968BA00A0B3/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/F36D8563-555D-41C7-AE11-6968BA00A0B3/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/58752353dc32d9f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/58752353dc32d9f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/CC52ADF7-52C5-441E-AC40-2E481E7C99B1/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54340"
,(lldb)     command script import "/tmp/F36D8563-555D-41C7-AE11-6968BA00A0B3/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-10 15:10:25.671 ThaliTest[1768:3128434] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/33F48AA8-82E3-486E-9F27-1FB552EAE1B9/Library/Cookies/Cookies.binarycookies
,2016-02-10 15:10:26.098 ThaliTest[1768:3128434] Apache Cordova native platform version 4.0.1 is starting.
,2016-02-10 15:10:26.100 ThaliTest[1768:3128434] Multi-tasking -> Device: YES, App: YES
,2016-02-10 15:10:26.127 ThaliTest[1768:3128434] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-10 15:10:28.292 ThaliTest[1768:3128434] Using UIWebView
,2016-02-10 15:10:28.299 ThaliTest[1768:3128434] [CDVTimer][handleopenurl] 0.437021ms
,2016-02-10 15:10:28.307 ThaliTest[1768:3128434] [CDVTimer][intentandnavigationfilter] 7.299960ms
2016-02-10 15:10:28.308 ThaliTest[1768:3128434] [CDVTimer][gesturehandler] 0.328004ms
2016-02-10 15:10:28.308 ThaliTest[1768:3128434] [CDVTimer][TotalPluginStartup] 9.763002ms
,2016-02-10 15:10:35.963 ThaliTest[1768:3128434] Resetting plugins due to page load.
,2016-02-10 15:10:39.477 ThaliTest[1768:3128434] Finished load of: file:///var/mobile/Containers/Bundle/Application/CC52ADF7-52C5-441E-AC40-2E481E7C99B1/ThaliTest.app/www/index.html
,2016-02-10 15:10:39.710 ThaliTest[1768:3128434] JXcore Cordova plugin initializing
2016-02-10 15:10:39.711 ThaliTest[1768:3128788] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CC52ADF7-52C5-441E-AC40-2E481E7C99B1/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CC52ADF7-52C5-441E-AC40-2E481E7C99B1/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CC52ADF7-52C5-441E-AC40-2E481E7C99B1/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CC52ADF7-52C5-441E-AC40-2E481E7C99B1/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CC52ADF7-52C5-441E-AC40-2E481E7C99B1/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CC52ADF7-52C5-441E-AC40-2E481E7C99B1/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CC52ADF7-52C5-441E-AC40-2E481E7C99B1/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CC52ADF7-52C5-441E-AC40-2E481E7C99B1/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CC52ADF7-52C5-441E-AC40-2E481E7C99B1/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CC52ADF7-52C5-441E-AC40-2E481E7C99B1/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,appEnteringBackground wasn't registered

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

# setup

,# successfully read a previous pkcs12 file and return hash value

,# teardown

,ok 18 (unnamed assert)

,ok 19 (unnamed assert)

,ok 20 should not throw

,ok 21 should be equal

ok 22 should be equal

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

,2016-02-10 15:15:44.318 ThaliTest[1768:3128788] jxcore: startBroadcasting
,2016-02-10 15:15:44.333 ThaliTest[1768:3128788] server: starting 1455113744317.1768.gGVsRg==
,2016-02-10 15:15:44.335 ThaliTest[1768:3128788] multipeer session: start timer: 0x18aa0ea0
,2016-02-10 15:15:44.336 ThaliTest[1768:3128788] THEMultipeerSession initialized peer 1455113744317.1768
2016-02-10 15:15:44.336 ThaliTest[1768:3128788] jxcore: startBroadcasting: success
ok 63 Should be able to call startBroadcasting without error

201,6-02-10 15:15:44.339 ThaliTest[1768:3128788] jxcore: stopBroadcasting
2016-02-10 15:15:44.339 ThaliTest[1768:3128788] THEMultipeerSession stopping peer
2016-02-10 15:15:44.340 ThaliTest[1768:3128788] multipeer session: stop timer
2016-02-10 15:15:44.341, ThaliTest[1768:3128788] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error

,2016-02-10 15:15:44.344 ThaliTest[1768:3128788] jxcore: startBroadcasting
,2016-02-10 15:15:44.349 ThaliTest[1768:3128788] server: starting 1455113744343.1768.Vgopig==
2016-02-10 15:15:44.350 ThaliTest[1768:3128788] multipeer session: start timer: 0x18ea40b0
2016-02-10 15:15:44.350 ThaliTest[1768:3128788] THEMultipeerSession in,itialized peer 1455113744343.1768
2016-02-10 15:15:44.351 ThaliTest[1768:3128788] jxcore: startBroadcasting: success
ok 65 Should be able to call startBroadcasting without error

2016-02-10 15:15:44.360 ThaliTest[1768:3128788] jxcore: stopBroadcasting,
2016-02-10 15:15:44.360 ThaliTest[1768:3128788] THEMultipeerSession stopping peer
,2016-02-10 15:15:44.360 ThaliTest[1768:3128788] multipeer session: stop timer
2016-02-10 15:15:44.365 ThaliTest[1768:3128788] jxcore: stopBroadcasting: success
,ok 66 Should be able to call stopBroadcasting without error

2016-02-10 15:15:44.368 ThaliTest[1768:3128788] jxcore: startBroadcasting
,2016-02-10 15:15:44.383 ThaliTest[1768:3128788] server: starting 1455113744368.1768.mi/Inw==
,2016-02-10 15:15:44.393 ThaliTest[1768:3128788] multipeer session: start timer: 0x18ab0f90
,2016-02-10 15:15:44.398 ThaliTest[1768:3128788] THEMultipeerSession initialized peer 1455113744368.1768
,2016-02-10 15:15:44.399 ThaliTest[1768:3128788] jxcore: startBroadcasting: success
,ok 67 Should be able to call startBroadcasting without error

,2016-02-10 15:15:44.403 ThaliTest[1768:3128788] jxcore: stopBroadcasting
,2016-02-10 15:15:44.403 ThaliTest[1768:3128788] THEMultipeerSession stopping peer
,2016-02-10 15:15:44.405 ThaliTest[1768:3128788] multipeer session: stop timer
,2016-02-10 15:15:44.409 ThaliTest[1768:3128788] jxcore: stopBroadcasting: success
,ok 68 Should be able to call stopBroadcasting without error

,2016-02-10 15:15:44.414 ThaliTest[1768:3128788] jxcore: startBroadcasting
,2016-02-10 15:15:44.418 ThaliTest[1768:3128788] server: starting 1455113744414.1768.mglusw==
,2016-02-10 15:15:44.421 ThaliTest[1768:3128788] multipeer session: start timer: 0x18ea47f0
,2016-02-10 15:15:44.422 ThaliTest[1768:3128788] THEMultipeerSession initialized peer 1455113744414.1768
,2016-02-10 15:15:44.426 ThaliTest[1768:3128788] jxcore: startBroadcasting: success
,ok 69 Should be able to call startBroadcasting without error

,2016-02-10 15:15:44.429 ThaliTest[1768:3128788] jxcore: stopBroadcasting
,2016-02-10 15:15:44.430 ThaliTest[1768:3128788] THEMultipeerSession stopping peer
,2016-02-10 15:15:44.431 ThaliTest[1768:3128788] multipeer session: stop timer
,2016-02-10 15:15:44.432 ThaliTest[1768:3128788] jxcore: stopBroadcasting: success
,ok 70 Should be able to call stopBroadcasting without error

,2016-02-10 15:15:44.437 ThaliTest[1768:3128788] jxcore: startBroadcasting
,2016-02-10 15:15:44.439 ThaliTest[1768:3128788] server: starting 1455113744436.1768.1WwzIg==
,2016-02-10 15:15:44.441 ThaliTest[1768:3128788] multipeer session: start timer: 0x18ea5270
,2016-02-10 15:15:44.444 ThaliTest[1768:3128788] THEMultipeerSession initialized peer 1455113744436.1768
,2016-02-10 15:15:44.447 ThaliTest[1768:3128788] jxcore: startBroadcasting: success
,ok 71 Should be able to call startBroadcasting without error

,2016-02-10 15:15:44.449 ThaliTest[1768:3128788] jxcore: stopBroadcasting
,2016-02-10 15:15:44.450 ThaliTest[1768:3128788] THEMultipeerSession stopping peer
,2016-02-10 15:15:44.451 ThaliTest[1768:3128788] multipeer session: stop timer
,2016-02-10 15:15:44.452 ThaliTest[1768:3128788] jxcore: stopBroadcasting: success
,ok 72 Should be able to call stopBroadcasting without error

,2016-02-10 15:15:44.457 ThaliTest[1768:3128788] jxcore: startBroadcasting
,2016-02-10 15:15:44.460 ThaliTest[1768:3128788] server: starting 1455113744457.1768.RoTZNg==
,2016-02-10 15:15:44.462 ThaliTest[1768:3128788] multipeer session: start timer: 0x18acdeb0
,2016-02-10 15:15:44.464 ThaliTest[1768:3128788] THEMultipeerSession initialized peer 1455113744457.1768
,2016-02-10 15:15:44.469 ThaliTest[1768:3128788] jxcore: startBroadcasting: success
,ok 73 Should be able to call startBroadcasting without error

,2016-02-10 15:15:44.471 ThaliTest[1768:3128788] jxcore: stopBroadcasting
,2016-02-10 15:15:44.472 ThaliTest[1768:3128788] THEMultipeerSession stopping peer
,2016-02-10 15:15:44.473 ThaliTest[1768:3128788] multipeer session: stop timer
,2016-02-10 15:15:44.475 ThaliTest[1768:3128788] jxcore: stopBroadcasting: success
,ok 74 Should be able to call stopBroadcasting without error

,2016-02-10 15:15:44.480 ThaliTest[1768:3128788] jxcore: startBroadcasting
,2016-02-10 15:15:44.482 ThaliTest[1768:3128788] server: starting 1455113744479.1768.r7bFgw==
,2016-02-10 15:15:44.485 ThaliTest[1768:3128788] multipeer session: start timer: 0x18ad05d0
,2016-02-10 15:15:44.488 ThaliTest[1768:3128788] THEMultipeerSession initialized peer 1455113744479.1768
,2016-02-10 15:15:44.491 ThaliTest[1768:3128788] jxcore: startBroadcasting: success
,ok 75 Should be able to call startBroadcasting without error

,2016-02-10 15:15:44.493 ThaliTest[1768:3128788] jxcore: stopBroadcasting
,2016-02-10 15:15:44.494 ThaliTest[1768:3128788] THEMultipeerSession stopping peer
,2016-02-10 15:15:44.495 ThaliTest[1768:3128788] multipeer session: stop timer
,2016-02-10 15:15:44.500 ThaliTest[1768:3128788] jxcore: stopBroadcasting: success
,ok 76 Should be able to call stopBroadcasting without error

,2016-02-10 15:15:44.503 ThaliTest[1768:3128788] jxcore: startBroadcasting
,2016-02-10 15:15:44.505 ThaliTest[1768:3128788] server: starting 1455113744502.1768.LBE8MA==
,2016-02-10 15:15:44.507 ThaliTest[1768:3128788] multipeer session: start timer: 0x18ad0f00
,2016-02-10 15:15:44.509 ThaliTest[1768:3128788] THEMultipeerSession initialized peer 1455113744502.1768
,2016-02-10 15:15:44.511 ThaliTest[1768:3128788] jxcore: startBroadcasting: success
,ok 77 Should be able to call startBroadcasting without error

,2016-02-10 15:15:44.515 ThaliTest[1768:3128788] jxcore: stopBroadcasting
,2016-02-10 15:15:44.515 ThaliTest[1768:3128788] THEMultipeerSession stopping peer
,2016-02-10 15:15:44.516 ThaliTest[1768:3128788] multipeer session: stop timer
,2016-02-10 15:15:44.517 ThaliTest[1768:3128788] jxcore: stopBroadcasting: success
,ok 78 Should be able to call stopBroadcasting without error

,2016-02-10 15:15:44.521 ThaliTest[1768:3128788] jxcore: startBroadcasting
,2016-02-10 15:15:44.523 ThaliTest[1768:3128788] server: starting 1455113744521.1768.tRR2hg==
,2016-02-10 15:15:44.525 ThaliTest[1768:3128788] multipeer session: start timer: 0x18ea6dd0
,2016-02-10 15:15:44.526 ThaliTest[1768:3128788] THEMultipeerSession initialized peer 1455113744521.1768
,2016-02-10 15:15:44.529 ThaliTest[1768:3128788] jxcore: startBroadcasting: success
,ok 79 Should be able to call startBroadcasting without error

,2016-02-10 15:15:44.531 ThaliTest[1768:3128788] jxcore: stopBroadcasting
,2016-02-10 15:15:44.532 ThaliTest[1768:3128788] THEMultipeerSession stopping peer
,2016-02-10 15:15:44.532 ThaliTest[1768:3128788] multipeer session: stop timer
,2016-02-10 15:15:44.534 ThaliTest[1768:3128788] jxcore: stopBroadcasting: success
,ok 80 Should be able to call stopBroadcasting without error

,2016-02-10 15:15:44.537 ThaliTest[1768:3128788] jxcore: startBroadcasting
,2016-02-10 15:15:44.540 ThaliTest[1768:3128788] server: starting 1455113744537.1768.1k4kUA==
,2016-02-10 15:15:44.541 ThaliTest[1768:3128788] multipeer session: start timer: 0x18ea5de0
,2016-02-10 15:15:44.543 ThaliTest[1768:3128788] THEMultipeerSession initialized peer 1455113744537.1768
,2016-02-10 15:15:44.543 ThaliTest[1768:3128788] jxcore: startBroadcasting: success
,ok 81 Should be able to call startBroadcasting without error

,2016-02-10 15:15:44.547 ThaliTest[1768:3128788] jxcore: stopBroadcasting
,2016-02-10 15:15:44.547 ThaliTest[1768:3128788] THEMultipeerSession stopping peer
,2016-02-10 15:15:44.548 ThaliTest[1768:3128788] multipeer session: stop timer
,2016-02-10 15:15:44.550 ThaliTest[1768:3128788] jxcore: stopBroadcasting: success
,ok 82 Should be able to call stopBroadcasting without error
,
,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,# teardown

,2016-02-10 15:15:44.810 ThaliTest[1768:3128788] jxcore: startBroadcasting
,2016-02-10 15:15:44.814 ThaliTest[1768:3128788] server: starting 1455113744809.1768.pf7E9g==
,2016-02-10 15:15:44.817 ThaliTest[1768:3128788] multipeer session: start timer: 0x18eabb80
,2016-02-10 15:15:44.822 ThaliTest[1768:3128788] THEMultipeerSession initialized peer 1455113744809.1768
,2016-02-10 15:15:44.826 ThaliTest[1768:3128788] jxcore: startBroadcasting: success
,ok 83 Should be able to call startBroadcasting without error

,2016-02-10 15:15:44.830 ThaliTest[1768:3128788] jxcore: startBroadcasting
,2016-02-10 15:15:44.832 ThaliTest[1768:3128788] jxcore: startBroadcasting: failure
,ok 84 Cannot call startBroadcasting twice

,2016-02-10 15:15:44.837 ThaliTest[1768:3128788] jxcore: stopBroadcasting
,2016-02-10 15:15:44.840 ThaliTest[1768:3128788] THEMultipeerSession stopping peer
,2016-02-10 15:15:44.841 ThaliTest[1768:3128788] multipeer session: stop timer
,2016-02-10 15:15:44.844 ThaliTest[1768:3128788] jxcore: stopBroadcasting: success
,ok 85 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on connection to bad peer

,# teardown

,2016-02-10 15:15:47.369 ThaliTest[1768:3128788] jxcore: startBroadcasting
,2016-02-10 15:15:47.372 ThaliTest[1768:3128788] server: starting 1455113747368.1768.p7qD9w==
2016-02-10 15:15:47.373 ThaliTest[1768:3128788] multipeer session: start timer: 0x18eaf420
2016-02-10 15:15:47.374 ThaliTest[1768:3128788] THEMultipeerSession in,itialized peer 1455113747368.1768
2016-02-10 15:15:47.374 ThaliTest[1768:3128788] jxcore: startBroadcasting: success
ok 86 Should be able to call startBroadcasting without error

2016-02-10 15:15:47.376 ThaliTest[1768:3128788] jxcore: connect foobar
2,016-02-10 15:15:47.376 ThaliTest[1768:3128788] client: unknown peer foobar
2016-02-10 15:15:47.377 ThaliTest[1768:3128788] jxcore: connect: fail: Unknown peer
ok 87 Should not connect to a bad peer

2016-02-10 15:15:47.380 ThaliTest[1768:3128788] jxcor,e: stopBroadcasting
2016-02-10 15:15:47.380 ThaliTest[1768:3128788] THEMultipeerSession stopping peer
2016-02-10 15:15:47.380 ThaliTest[1768:3128788] multipeer session: stop timer
2016-02-10 15:15:47.381 ThaliTest[1768:3128788] jxcore: stopBroadcasting:, success
,ok 88 Should be able to call stopBroadcasting without error

# setup

,# ThaliEmitter throws on disconnect to bad peer

,# teardown

,2016-02-10 15:15:47.895 ThaliTest[1768:3128788] jxcore: startBroadcasting
,2016-02-10 15:15:47.898 ThaliTest[1768:3128788] server: starting 1455113747894.1768.FWvPNA==
2016-02-10 15:15:47.899 ThaliTest[1768:3128788] multipeer session: start timer: 0x18eb19a0
2016-02-10 15:15:47.900 ThaliTest[1768:3128788] THEMultipeerSession in,itialized peer 1455113747894.1768
2016-02-10 15:15:47.900 ThaliTest[1768:3128788] jxcore: startBroadcasting: success
ok 89 Should be able to call startBroadcasting without error

,2016-02-10 15:15:47.903 ThaliTest[1768:3128788] jxcore: disconnect
2016-02-10 15:15:47.903 ThaliTest[1768:3128788] jxcore: disconnect: fail
,ok 90 Disconnect should fail to a non-existant peer 

,2016-02-10 15:15:47.908 ThaliTest[1768:3128788] jxcore: stopBroadcasting
2016-02-10 15:15:47.909 ThaliTest[1768:3128788] THEMultipeerSession stopping peer
2016-02-10 15:15:47.909 ThaliTest[1768:3128788] multipeer session: stop timer
2016-02-10 15:15:47.910 ThaliTest[1768:3128788] jxcore: stopBroadcasting: success
ok 91 Should be able to call stopBroadcasting without error

# setup

,# ThaliEmitter can discover and connect to peers

,# teardown

,2016-02-10 15:15:48.407 ThaliTest[1768:3128788] jxcore: startBroadcasting
,2016-02-10 15:15:48.411 ThaliTest[1768:3128788] server: starting 1455113748407.1768.ybCI6g==
2016-02-10 15:15:48.411 ThaliTest[1768:3128788] multipeer session: start timer: 0x18ad9170
2016-02-10 15:15:48.412 ThaliTest[1768:3128788] THEMultipeerSession in,itialized peer 1455113748407.1768
2016-02-10 15:15:48.412 ThaliTest[1768:3128788] jxcore: startBroadcasting: success
ok 92 Should be able to call startBroadcasting without error

,2016-02-10 15:15:49.659 ThaliTest[1768:3128434] client: found peer: 1455113751420.1459.34QzYA==
,2016-02-10 15:15:49.662 ThaliTest[1768:3128788] jxcore: connect 1455113751420.1459.34QzYA==
2016-02-10 15:15:49.663 ThaliTest[1768:3128788] client session: connect
2016-02-10 15:15:49.663 ThaliTest[1768:3128788] client session: stateChange:0->1 1455113751420.1459.34QzYA==
,2016-02-10 15:15:50.279 ThaliTest[1768:3128434] multipeer session: reset timer
2016-02-10 15:15:50.279 ThaliTest[1768:3128434] multipeer session: stop timer
2016-02-10 15:15:50.279 ThaliTest[1768:3128434] multipeer session: start timer: 0x18ad9170
2016-,02-10 15:15:50.280 ThaliTest[1768:3128434] server session: connect
2016-02-10 15:15:50.280 ThaliTest[1768:3128434] server session: stateChange:0->1 1455113751420.1459
,2016-02-10 15:15:50.290 ThaliTest[1768:3128434] server: accepting invitation 1455113751420.1459
,2016-02-10 15:15:52.719 ThaliTest[1768:3129336] client session: connected
2016-02-10 15:15:52.720 ThaliTest[1768:3129336] client session: stateChange:1->2 1455113751420.1459.34QzYA==
,2016-02-10 15:15:52.772 ThaliTest[1768:3129338] client session: fireConnectCallback: 1455113751420.1459.34QzYA==
2016-02-10 15:15:52.772 ThaliTest[1768:3129338] jxcore: connect: success
,ok 93 Should be able to connect without error

,ok 94 Port should be within range

,2016-02-10 15:15:52.778 ThaliTest[1768:3128788] jxcore: disconnect
2016-02-10 15:15:52.778 ThaliTest[1768:3128788] client session: disconnectFromPeer: 1455113751420.1459.34QzYA==
2016-02-10 15:15:52.778 ThaliTest[1768:3128788] client session: disconnect,
2016-02-10 15:15:52.779 ThaliTest[1768:3128788] client session: stateChange:2->0 1455113751420.1459.34QzYA==
,2016-02-10 15:15:52.791 ThaliTest[1768:3128788] jxcore: disconnect: success
ok 95 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,2016-02-10 15:15:53.039 ThaliTest[1768:3129338] server session: connected
2016-02-10 15:15:53.039 ThaliTest[1768:3129338] server session: stateChange:1->2 1455113751420.1459
,2016-02-10 15:15:53.077 ThaliTest[1768:3128434] server relay: socket disconnected
2016-02-10 15:15:53.078 ThaliTest[1768:3128434] server relay: 0x18eb74d0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-10 15:15:53.099 ThaliTest[1768:3129334] server session: not connected 1455113751420.1459
,calling stopBroadcasting

,2016-02-10 15:15:54.150 ThaliTest[1768:3128788] jxcore: stopBroadcasting
2016-02-10 15:15:54.151 ThaliTest[1768:3128788] THEMultipeerSession stopping peer
2016-02-10 15:15:54.151 ThaliTest[1768:3128788] multipeer session: stop timer
2016-02-10 15:15:54.,152 ThaliTest[1768:3128788] server session: disconnect
2016-02-10 15:15:54.152 ThaliTest[1768:3128788] server session: stateChange:2->0 1455113751420.1459
2016-02-10 15:15:54.153 ThaliTest[1768:3128788] jxcore: stopBroadcasting: success
stopBroadcasting, returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double connect

,# teardown

,2016-02-10 15:15:54.487 ThaliTest[1768:3128788] jxcore: startBroadcasting
,2016-02-10 15:15:54.491 ThaliTest[1768:3128788] server: starting 1455113754486.1768.FWj1Sg==
2016-02-10 15:15:54.492 ThaliTest[1768:3128788] multipeer session: start timer: 0x18eba810
2016-02-10 15:15:54.492 ThaliTest[1768:3128788] THEMultipeerSession in,itialized peer 1455113754486.1768
2016-02-10 15:15:54.492 ThaliTest[1768:3128788] jxcore: startBroadcasting: success
ok 96 Should be able to call startBroadcasting without error

,2016-02-10 15:15:56.510 ThaliTest[1768:3128434] multipeer session: reset timer
2016-02-10 15:15:56.510 ThaliTest[1768:3128434] multipeer session: stop timer
2016-02-10 15:15:56.511 ThaliTest[1768:3128434] multipeer session: start timer: 0x18eba810
2016-02-10 15:15:56.511 ThaliTest[1768:3128434] server session: connect
2016-02-10 15:15:56.513 ThaliTest[1768:3128434] server session: stateChange:0->1 1455113757828.1459
,2016-02-10 15:15:56.523 ThaliTest[1768:3128434] server: accepting invitation 1455113757828.1459
2016-02-10 15:15:56.525 ThaliTest[1768:3128434] client: found peer: 1455113757828.1459.fF+coQ==
,2016-02-10 15:15:56.527 ThaliTest[1768:3128788] jxcore: connect 1455113757828.1459.fF+coQ==
2016-02-10 15:15:56.540 ThaliTest[1768:3128788] client session: connect
2016-02-10 15:15:56.540 ThaliTest[1768:3128788] client session: stateChange:0->1 1455113757828.1459.fF+coQ==
,2016-02-10 15:15:59.259 ThaliTest[1768:3129334] server session: connected
2016-02-10 15:15:59.260 ThaliTest[1768:3129334] server session: stateChange:1->2 1455113757828.1459
,2016-02-10 15:15:59.287 ThaliTest[1768:3128434] server relay: socket disconnected
2016-02-10 15:15:59.288 ThaliTest[1768:3128434] server relay: 0x18eb7bc0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-10 15:15:59.308 ThaliTest[1768:3129338] server session: not connected 1455113757828.1459
,2016-02-10 15:15:59.518 ThaliTest[1768:3129338] client session: connected
2016-02-10 15:15:59.518 ThaliTest[1768:3129338] client session: stateChange:1->2 1455113757828.1459.fF+coQ==
,2016-02-10 15:15:59.534 ThaliTest[1768:3129340] client session: fireConnectCallback: 1455113757828.1459.fF+coQ==
2016-02-10 15:15:59.534 ThaliTest[1768:3129340] jxcore: connect: success
ok 97 Should be able to connect without error

ok 98 Port should b,e within range

,2016-02-10 15:15:59.538 ThaliTest[1768:3128788] jxcore: connect 1455113757828.1459.fF+coQ==
,2016-02-10 15:15:59.538 ThaliTest[1768:3128788] client: already connect(ing/ed) to 1455113757828.1459.fF+coQ==
2016-02-10 15:15:59.539 ThaliTest[1768:3128788] jxcore: connect: fail: Aleady connecting
,ok 99 Should fail on double connect

,2016-02-10 15:15:59.543 ThaliTest[1768:3128788] jxcore: disconnect
2016-02-10 15:15:59.543 ThaliTest[1768:3128788] client session: disconnectFromPeer: 1455113757828.1459.fF+coQ==
2016-02-10 15:15:59.544 ThaliTest[1768:3128788] client session: disconnect,
2016-02-10 15:15:59.544 ThaliTest[1768:3128788] client session: stateChange:2->0 1455113757828.1459.fF+coQ==
,2016-02-10 15:15:59.553 ThaliTest[1768:3128788] jxcore: disconnect: success
ok 100 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-02-10 15:15:59.938 ThaliTest[1768:3128788] jxcore: stopBroadcasting
2016-02-10 15:15:59.938 ThaliTest[1768:3128788] THEMultipeerSession stopping peer
2016-02-10 15:15:59.939 ThaliTest[1768:3128788] multipeer session: stop timer
2016-02-10 15:15:59.,939 ThaliTest[1768:3128788] server session: disconnect
2016-02-10 15:15:59.940 ThaliTest[1768:3128788] server session: stateChange:2->0 1455113757828.1459
2016-02-10 15:15:59.941 ThaliTest[1768:3128788] jxcore: stopBroadcasting: success
stopBroadcasting, returned undefined

# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,# teardown

,2016-02-10 15:16:00.477 ThaliTest[1768:3128788] jxcore: startBroadcasting
,2016-02-10 15:16:00.481 ThaliTest[1768:3128788] server: starting 1455113760477.1768.tuq5kg==
2016-02-10 15:16:00.482 ThaliTest[1768:3128788] multipeer session: start timer: 0x18ec2700
2016-02-10 15:16:00.483 ThaliTest[1768:3128788] THEMultipeerSession in,itialized peer 1455113760477.1768
2016-02-10 15:16:00.483 ThaliTest[1768:3128788] jxcore: startBroadcasting: success
ok 101 Should be able to call startBroadcasting without error

,2016-02-10 15:16:01.075 ThaliTest[1768:3128434] client: found peer: 1455113757828.1459.fF+coQ==
2016-02-10 15:16:01.076 ThaliTest[1768:3128788] jxcore: connect 1455113757828.1459.fF+coQ==
2016-02-10 15:16:01.077 ThaliTest[1768:3128788] client session: co,nnect
2016-02-10 15:16:01.077 ThaliTest[1768:3128788] client session: stateChange:0->1 1455113757828.1459.fF+coQ==
,2016-02-10 15:16:01.699 ThaliTest[1768:3128434] client: found peer: 1455113763602.1459.TGadlQ==
2016-02-10 15:16:01.700 ThaliTest[1768:3128788] jxcore: connect 1455113763602.1459.TGadlQ==
2016-02-10 15:16:01.701 ThaliTest[1768:3128788] client session: connect
2016-02-10 15:16:01.701 ThaliTest[1768:3128788] client session: stateChange:0->1 1455113763602.1459.TGadlQ==
,2016-02-10 15:16:01.824 ThaliTest[1768:3128434] multipeer session: reset timer
2016-02-10 15:16:01.824 ThaliTest[1768:3128434] multipeer session: stop timer
2016-02-10 15:16:01.824 ThaliTest[1768:3128434] multipeer session: start timer: 0x18ec2700
,2016-02-10 15:16:01.825 ThaliTest[1768:3128434] server session: connect
2016-02-10 15:16:01.827 ThaliTest[1768:3128434] server session: stateChange:0->1 1455113763602.1459
,2016-02-10 15:16:01.837 ThaliTest[1768:3128434] server: accepting invitation 1455113763602.1459
,2016-02-10 15:16:04.392 ThaliTest[1768:3129339] client session: connected
,2016-02-10 15:16:04.392 ThaliTest[1768:3129339] client session: stateChange:1->2 1455113763602.1459.TGadlQ==
,2016-02-10 15:16:04.396 ThaliTest[1768:3129339] client session: fireConnectCallback: 1455113763602.1459.TGadlQ==
,2016-02-10 15:16:04.397 ThaliTest[1768:3129339] jxcore: connect: success
,ok 102 Should be able to connect without error

,ok 103 Port should be within range

,2016-02-10 15:16:04.400 ThaliTest[1768:3128788] jxcore: disconnect
,2016-02-10 15:16:04.402 ThaliTest[1768:3128788] client session: disconnectFromPeer: 1455113763602.1459.TGadlQ==
,2016-02-10 15:16:04.403 ThaliTest[1768:3128788] client session: disconnect
,2016-02-10 15:16:04.404 ThaliTest[1768:3128788] client session: stateChange:2->0 1455113763602.1459.TGadlQ==
,2016-02-10 15:16:04.414 ThaliTest[1768:3128788] jxcore: disconnect: success
,ok 104 Should be able to disconnect without error

,2016-02-10 15:16:04.416 ThaliTest[1768:3128788] jxcore: disconnect
,2016-02-10 15:16:04.416 ThaliTest[1768:3128788] jxcore: disconnect: fail
,ok 105 Disconnect should fail 

,setting stopBroadcasting callback and ending test.

,2016-02-10 15:16:04.427 ThaliTest[1768:3129336] server session: connected
,2016-02-10 15:16:04.428 ThaliTest[1768:3129336] server session: stateChange:1->2 1455113763602.1459
,2016-02-10 15:16:04.431 ThaliTest[1768:3128434] server relay: socket disconnected
,2016-02-10 15:16:04.431 ThaliTest[1768:3128434] server relay: 0x17bd9cf0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,# setup

,2016-02-10 15:16:04.496 ThaliTest[1768:3129340] server session: not connected 1455113763602.1459
,calling stopBroadcasting

,2016-02-10 15:16:05.243 ThaliTest[1768:3128788] jxcore: stopBroadcasting
2016-02-10 15:16:05.244 ThaliTest[1768:3128788] THEMultipeerSession stopping peer
2016-02-10 15:16:05.244 ThaliTest[1768:3128788] multipeer session: stop timer
2016-02-10 15:16:05.,245 ThaliTest[1768:3128788] client session: disconnect
2016-02-10 15:16:05.245 ThaliTest[1768:3128788] client session: stateChange:1->0 1455113757828.1459.fF+coQ==
2016-02-10 15:16:05.246 ThaliTest[1768:3128788] server session: disconnect
2016-02-10 15:,16:05.246 ThaliTest[1768:3128788] server session: stateChange:2->0 1455113763602.1459
,2016-02-10 15:16:05.249 ThaliTest[1768:3128788] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter can connect and send data

,# teardown

,echo server started on port: 61536

,2016-02-10 15:16:08.332 ThaliTest[1768:3128788] jxcore: startBroadcasting
,2016-02-10 15:16:08.334 ThaliTest[1768:3128788] server: starting 1455113768332.1768.7T5mUA==
,2016-02-10 15:16:08.336 ThaliTest[1768:3128788] multipeer session: start timer: 0x166593b0
,2016-02-10 15:16:08.338 ThaliTest[1768:3128788] THEMultipeerSession initialized peer 1455113768332.1768
,2016-02-10 15:16:08.339 ThaliTest[1768:3128788] jxcore: startBroadcasting: success
,ok 106 Should be able to call startBroadcasting without error

,2016-02-10 15:16:09.137 ThaliTest[1768:3128434] client: found peer: 1455113771326.1459.gBubyg==
,2016-02-10 15:16:09.139 ThaliTest[1768:3128788] jxcore: connect 1455113771326.1459.gBubyg==
2016-02-10 15:16:09.140 ThaliTest[1768:3128788] client session: connect
2016-02-10 15:16:09.140 ThaliTest[1768:3128788] client session: stateChange:0->1 1455113771326.1459.gBubyg==
,2016-02-10 15:16:10.042 ThaliTest[1768:3128434] multipeer session: reset timer
2016-02-10 15:16:10.043 ThaliTest[1768:3128434] multipeer session: stop timer
2016-02-10 15:16:10.043 ThaliTest[1768:3128434] multipeer session: start timer: 0x166593b0
2016-,02-10 15:16:10.043 ThaliTest[1768:3128434] server session: connect
2016-02-10 15:16:10.044 ThaliTest[1768:3128434] server session: stateChange:0->1 1455113771326.1459
,2016-02-10 15:16:10.053 ThaliTest[1768:3128434] server: accepting invitation 1455113771326.1459
,2016-02-10 15:16:14.671 ThaliTest[1768:3129336] server session: connected
2016-02-10 15:16:14.672 ThaliTest[1768:3129336] server session: stateChange:1->2 1455113771326.1459
,2016-02-10 15:16:15.059 ThaliTest[1768:3129334] client session: connected
2016-02-10 15:16:15.059 ThaliTest[1768:3129334] client session: stateChange:1->2 1455113771326.1459.gBubyg==
,2016-02-10 15:16:15.125 ThaliTest[1768:3128434] server relay: connected (to port: 61536)
,2016-02-10 15:16:15.333 ThaliTest[1768:3129336] client session: fireConnectCallback: 1455113771326.1459.gBubyg==
2016-02-10 15:16:15.334 ThaliTest[1768:3129336] jxcore: connect: success
ok 107 Should be able to connect without error

ok 108 Port should be within range

,2016-02-10 15:16:15.341 ThaliTest[1768:3128434] client: relay established
2016-02-10 15:16:15.342 ThaliTest[1768:3128434] client: new accepted socket: 0x17c9e240
,data in 1095

,data in 2190

,data in 3285

,data in 4380

,data in 5475

,data in 6570

,data in 7665

,data in 8760

,data in 9855

,2016-02-10 15:16:40.045 ThaliTest[1768:3128434] multipeer session: restart
,2016-02-10 15:16:40.937 ThaliTest[1768:3129507] server session: not connected 1455113771326.1459
,data in 14235

,data in 31755

,data in 56940

,data in 63510

,data in 64605

,data in 65700

,data in 70080

,data in 79935

,data in 81030

,data in 83220

,data in 84315

,data in 85410

,data in 86505

,data in 87600

,data in 88695

,data in 89790

,data in 90885

,data in 91980

,data in 93075

,data in 94170

,data in 95265

,data in 96360

,data in 97455

,data in 98550

,data in 99645

,data in 100740

,data in 101835

,data in 102930

,data in 104025

,data in 105120

,data in 106215

,data in 107310

,data in 108405

,data in 109500
,
,data in 110595

,data in 111690

,data in 112785

,data in 113880

,data in 114975

,data in 116070

,data in 117165

,data in 118260

,data in 119355

,data in 120450

,data in 121545

,data in 122640

,data in 123735

,data in 124830

,data in 125925

,data in 127020

,data in 128115

,data in 129210

,data in 130305

,data in 131072

,ok 109 the test messages should be equal

,2016-02-10 15:17:02.682 ThaliTest[1768:3128788] jxcore: disconnect
2016-02-10 15:17:02.683 ThaliTest[1768:3128788] client session: disconnectFromPeer: 1455113771326.1459.gBubyg==
2016-02-10 15:17:02.683 ThaliTest[1768:3128788] client session: disconnect,
2016-02-10 15:17:02.683 ThaliTest[1768:3128788] client session: stateChange:2->0 1455113771326.1459.gBubyg==
,2016-02-10 15:17:02.692 ThaliTest[1768:3128788] jxcore: disconnect: success
ok 110 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,2016-02-10 15:17:10.045 ThaliTest[1768:3128434] multipeer session: restart
,2016-02-10 15:17:10.075 ThaliTest[1768:3128434] client: found peer: 1455113771326.1459.gBubyg==
,2016-02-10 15:17:40.045 ThaliTest[1768:3128434] multipeer session: restart
,2016-02-10 15:18:10.045 ThaliTest[1768:3128434] multipeer session: restart
,2016-02-10 15:18:10.073 ThaliTest[1768:3128434] client: found peer: 1455113771326.1459.gBubyg==
,2016-02-10 15:18:40.045 ThaliTest[1768:3128434] multipeer session: restart
,2016-02-10 15:18:40.075 ThaliTest[1768:3128434] client: found peer: 1455113771326.1459.gBubyg==
,2016-02-10 15:19:10.045 ThaliTest[1768:3128434] multipeer session: restart
,2016-02-10 15:19:10.076 ThaliTest[1768:3128434] client: found peer: 1455113771326.1459.gBubyg==
,2016-02-10 15:19:40.045 ThaliTest[1768:3128434] multipeer session: restart
,2016-02-10 15:20:10.045 ThaliTest[1768:3128434] multipeer session: restart
,2016-02-10 15:20:10.074 ThaliTest[1768:3128434] client: found peer: 1455113771326.1459.gBubyg==
,2016-02-10 15:20:40.045 ThaliTest[1768:3128434] multipeer session: restart
,2016-02-10 15:20:40.076 ThaliTest[1768:3128434] client: found peer: 1455113771326.1459.gBubyg==
,2016-02-10 15:21:10.044 ThaliTest[1768:3128434] multipeer session: restart
,2016-02-10 15:21:40.045 ThaliTest[1768:3128434] multipeer session: restart
,2016-02-10 15:21:40.072 ThaliTest[1768:3128434] client: found peer: 1455113771326.1459.gBubyg==
,2016-02-10 15:22:10.045 ThaliTest[1768:3128434] multipeer session: restart
,2016-02-10 15:22:10.075 ThaliTest[1768:3128434] client: found peer: 1455113771326.1459.gBubyg==
,appEnteredForeground wasn't registered

,2016-02-10 15:22:40.045 ThaliTest[1768:3128434] multipeer session: restart
,2016-02-10 15:22:40.076 ThaliTest[1768:3128434] client: found peer: 1455113771326.1459.gBubyg==
,appEnteringBackground wasn't registered

,2016-02-10 15:23:10.045 ThaliTest[1768:3128434] multipeer session: restart
,2016-02-10 15:23:10.078 ThaliTest[1768:3128434] client: found peer: 1455113771326.1459.gBubyg==
,2016-02-10 15:23:40.045 ThaliTest[1768:3128434] multipeer session: restart
,2016-02-10 15:23:40.073 ThaliTest[1768:3128434] client: found peer: 1455113771326.1459.gBubyg==
,2016-02-10 15:24:10.045 ThaliTest[1768:3128434] multipeer session: restart
,2016-02-10 15:24:40.044 ThaliTest[1768:3128434] multipeer session: restart
,2016-02-10 15:24:40.075 ThaliTest[1768:3128434] client: found peer: 1455113771326.1459.gBubyg==
,2016-02-10 15:25:10.045 ThaliTest[1768:3128434] multipeer session: restart
,2016-02-10 15:25:40.045 ThaliTest[1768:3128434] multipeer session: restart
,2016-02-10 15:25:40.076 ThaliTest[1768:3128434] client: found peer: 1455113771326.1459.gBubyg==
,2016-02-10 15:26:10.045 ThaliTest[1768:3128434] multipeer session: restart
,2016-02-10 15:26:10.075 ThaliTest[1768:3128434] client: found peer: 1455113771326.1459.gBubyg==
,2016-02-10 15:26:40.045 ThaliTest[1768:3128434] multipeer session: restart
,2016-02-10 15:27:10.045 ThaliTest[1768:3128434] multipeer session: restart
,2016-02-10 15:27:10.074 ThaliTest[1768:3128434] client: found peer: 1455113771326.1459.gBubyg==
,2016-02-10 15:27:40.045 ThaliTest[1768:3128434] multipeer session: restart
,2016-02-10 15:28:10.045 ThaliTest[1768:3128434] multipeer session: restart
,2016-02-10 15:28:10.072 ThaliTest[1768:3128434] client: found peer: 1455113771326.1459.gBubyg==

```
