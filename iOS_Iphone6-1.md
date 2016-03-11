#### Test 625481247756efd_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/625481247756efd/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/135B48A4-1D91-4A60-8D98-7D804158AB85/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/135B48A4-1D91-4A60-8D98-7D804158AB85/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/625481247756efd/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/625481247756efd/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D8572218-DE21-4715-B93E-068F8C356513/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49425"
,(lldb)     command script import "/tmp/135B48A4-1D91-4A60-8D98-7D804158AB85/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-11 16:05:42.938 ThaliTest[1148:1735023] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D6D18A1C-F3ED-45BB-97F1-0EFB2FB32D02/Library/Cookies/Cookies.binarycookies
,2016-03-11 16:05:43.347 ThaliTest[1148:1735023] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-11 16:05:43.348 ThaliTest[1148:1735023] Multi-tasking -> Device: YES, App: YES
,2016-03-11 16:05:43.371 ThaliTest[1148:1735023] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-11 16:05:45.124 ThaliTest[1148:1735023] Using UIWebView
,2016-03-11 16:05:45.131 ThaliTest[1148:1735023] [CDVTimer][handleopenurl] 0.496984ms
,2016-03-11 16:05:45.139 ThaliTest[1148:1735023] [CDVTimer][intentandnavigationfilter] 7.163048ms
2016-03-11 16:05:45.140 ThaliTest[1148:1735023] [CDVTimer][gesturehandler] 0.362992ms
2016-03-11 16:05:45.140 ThaliTest[1148:1735023] [CDVTimer][TotalPluginStartup] 9.604990ms
,2016-03-11 16:05:51.376 ThaliTest[1148:1735023] Resetting plugins due to page load.
,2016-03-11 16:05:54.342 ThaliTest[1148:1735023] Finished load of: file:///var/mobile/Containers/Bundle/Application/D8572218-DE21-4715-B93E-068F8C356513/ThaliTest.app/www/index.html
,2016-03-11 16:05:54.571 ThaliTest[1148:1735023] JXcore Cordova plugin initializing
2016-03-11 16:05:54.571 ThaliTest[1148:1735215] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,INFO testUtils: Toggling radios to: true

,Unit Test app is loaded

,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D8572218-DE21-4715-B93E-068F8C356513/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D8572218-DE21-4715-B93E-068F8C356513/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D8572218-DE21-4715-B93E-068F8C356513/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D8572218-DE21-4715-B93E-068F8C356513/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D8572218-DE21-4715-B93E-068F8C356513/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D8572218-DE21-4715-B93E-068F8C356513/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-11 16:06:08.706 ThaliTest[1148:1735215] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-11 16:06:08.706 ThaliTest[1148:1735215] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-11 16:06:08.707 ThaliTest[1148:1735215] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

,2016-03-11 16:06:08.708 ThaliTest[1148:1735215] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D8572218-DE21-4715-B93E-068F8C356513/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D8572218-DE21-4715-B93E-068F8C356513/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D8572218-DE21-4715-B93E-068F8C356513/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D8572218-DE21-4715-B93E-068F8C356513/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D8572218-DE21-4715-B93E-068F8C356513/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D8572218-DE21-4715-B93E-068F8C356513/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D8572218-DE21-4715-B93E-068F8C356513/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D8572218-DE21-4715-B93E-068F8C356513/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D8572218-DE21-4715-B93E-068F8C356513/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D8572218-DE21-4715-B93E-068F8C356513/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D8572218-DE21-4715-B93E-068F8C356513/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D8572218-DE21-4715-B93E-068F8C356513/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Reconnected to the test server

,TAP version 13

,# setup

,# 1. closeAll can close even when connections open

,# teardown

,ok 1 not possible to connect to the server anymore

,# setup

,# 2. closeAll with promise

,# teardown

,ok 2 not possible to connect to the server anymore

,# setup

,# 3. multiplex can send data

,# teardown

,ok 3 String should be length:200

,# setup

,# 4. enqueue and run in order

,# teardown

,ok 4 firstPromise setTimeout

,ok 5 firstPromise result

,ok 6 firstPromise testValue

,ok 7 secondPromise setTimeout

,ok 8 secondPromise result

,ok 9 secondPromise testValue

,ok 10 thirdPromise in promise

,ok 11 thirdPromise result

,ok 12 thirdPromise testValue

,# setup

,# 5. enqueueAtTop and run backwards

,# teardown

,ok 13 thirdPromise - first to run

,ok 14 thirdPromise - in resolve

,ok 15 secondPromise - second to run

,ok 16 secondPromise - in catch

,ok 17 firstPromise - third to run

,ok 18 firstPromise - in then

,ok 19 testing promises

,# setup

,# 6. mix enqueue and enqueueAtTop

,# teardown

,ok 20 fourth

,ok 21 fourth

,ok 22 second

,ok 23 secondPromise - in then

,ok 24 first

,ok 25 firstPromise - in catch

,ok 26 third

,ok 27 thirdPromise - in then

,ok 28 testingPromises

,# setup

,# 7. queues handled independently

,# teardown

,ok 29 all short operations completed before the long resolves

,# setup

,# 8. basic

,# teardown

,ok 30 sane

,# setup

,# 9. another

,# teardown

,ok 31 sane

,# setup

,# 10. #startListeningForAdvertisements should fail if start not called

,# teardown

,ok 32 specific error should be returned

,# setup

,ok 33 error should be null

,ok 34 error should be null

,# 11. #startUpdateAdvertisingAndListening should fail if start not called

,# teardown

,ok 35 specific error should be returned

,# setup

,ok 36 error should be null

,ok 37 error should be null

,# 12. should be able to call #stopListeningForAdvertisements many times

,# teardown

,2016-03-11 16:09:32.085 ThaliTest[1148:1735215] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}

,2016-03-11 16:09:32.088 ThaliTest[1148:1735215] jxcore: stopListeningForAdvertisements: success
,ok 38 error should be null

,ok 39 error should be null

,2016-03-11 16:09:32.093 ThaliTest[1148:1735215] jxcore: stopListeningForAdvertisements
INFO thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}

,2016-03-11 16:09:32.095 ThaliTest[1148:1735215] jxcore: stopListeningForAdvertisements: success
,ok 40 error should be null

,ok 41 error should be null

,# setup

,2016-03-11 16:09:32.227 ThaliTest[1148:1735215] jxcore: stopAdvertisingAndListening
2016-03-11 16:09:32.228 ThaliTest[1148:1735215] THEMultipeerManager stopping peer
2016-03-11 16:09:32.228 ThaliTest[1148:1735215] jxcore: stopAdvertisingAndListening: success
,2016-03-11 16:09:32.230 ThaliTest[1148:1735215] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}

,2016-03-11 16:09:32.233 ThaliTest[1148:1735215] jxcore: stopListeningForAdvertisements: success
,ok 42 error should be null

,ok 43 error should be null

,# 13. should be able to call #startListeningForAdvertisements many times

,# teardown

,2016-03-11 16:09:32.517 ThaliTest[1148:1735215] jxcore: startListeningForAdvertisements
,2016-03-11 16:09:32.519 ThaliTest[1148:1735215] multipeer manager: start client restart timer: 0x165b7520
INFO thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}

,2016-03-11 16:09:32.521 ThaliTest[1148:1735215] jxcore: startListeningForAdvertisements: success
,ok 44 error should be null

ok 45 error should be null

,2016-03-11 16:09:32.538 ThaliTest[1148:1735215] jxcore: startListeningForAdvertisements
INFO thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}

,2016-03-11 16:09:32.539 ThaliTest[1148:1735215] jxcore: startListeningForAdvertisements: success
,ok 46 error should be null

,ok 47 error should be null

,# setup

,2016-03-11 16:09:32.859 ThaliTest[1148:1735215] jxcore: stopAdvertisingAndListening
2016-03-11 16:09:32.860 ThaliTest[1148:1735215] THEMultipeerManager stopping peer
2016-03-11 16:09:32.860 ThaliTest[1148:1735215] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-11 16:09:32.861 ThaliTest[1148:1735215] jxcore: stopListeningForAdvertisements
2016-03-11 16:09:32.861 ThaliTest[1148:1735215] multipeer manager: stop client timer
,INFO thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}

,2016-03-11 16:09:32.865 ThaliTest[1148:1735215] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).

,ok 48 error should be null

,ok 49 error should be null

,# 14. should be able to call #startUpdateAdvertisingAndListening many times

,# teardown

,2016-03-11 16:09:33.309 ThaliTest[1148:1735215] jxcore: startUpdateAdvertisingAndListening
,2016-03-11 16:09:33.310 ThaliTest[1148:1735215] server: starting 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:1
,2016-03-11 16:09:33.312 ThaliTest[1148:1735215] multipeer manager: start client restart timer: 0x165b7520
2016-03-11 16:09:33.313 ThaliTest[1148:1735215] THEMultipeerManager initialized peer 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:1
2016-03-11 16:09:33.313 ,ThaliTest[1148:1735215] jxcore: startUpdateAdvertisingAndListening: success
,ok 50 error should be null

ok 51 error should be null

,2016-03-11 16:09:33.330 ThaliTest[1148:1735215] jxcore: startUpdateAdvertisingAndListening
2016-03-11 16:09:33.334 ThaliTest[1148:1735215] THEMultipeerManager stopping peer
2016-03-11 16:09:33.334 ThaliTest[1148:1735215] multipeer manager: stop client ti,mer
2016-03-11 16:09:33.335 ThaliTest[1148:1735215] server: starting 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:2
2016-03-11 16:09:33.335 ThaliTest[1148:1735215] multipeer manager: start client restart timer: 0x165b7520
2016-03-11 16:09:33.336 ThaliTest[1148:,1735215] THEMultipeerManager initialized peer 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:2
2016-03-11 16:09:33.336 ThaliTest[1148:1735215] jxcore: startUpdateAdvertisingAndListening: success
,ok 52 error should be null

,ok 53 error should be null

,# setup

,2016-03-11 16:09:33.485 ThaliTest[1148:1735215] jxcore: stopAdvertisingAndListening
,2016-03-11 16:09:33.487 ThaliTest[1148:1735215] THEMultipeerManager stopping peer
2016-03-11 16:09:33.487 ThaliTest[1148:1735215] multipeer manager: stop client timer
2016-03-11 16:09:33.488 ThaliTest[1148:1735215] jxcore: stopAdvertisingAndListening: su,ccess
2016-03-11 16:09:33.489 ThaliTest[1148:1735215] jxcore: stopListeningForAdvertisements
INFO thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}

,2016-03-11 16:09:33.490 ThaliTest[1148:1735215] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).

,ok 54 error should be null

,ok 55 error should be null

,# 15. should be able to call #stopAdvertisingAndListening many times
,
,# teardown

,2016-03-11 16:09:34.007 ThaliTest[1148:1735215] jxcore: stopAdvertisingAndListening
2016-03-11 16:09:34.007 ThaliTest[1148:1735215] THEMultipeerManager stopping peer
2016-03-11 16:09:34.008 ThaliTest[1148:1735215] jxcore: stopAdvertisingAndListening: success
,ok 56 error should be null

,ok 57 error should be null

,2016-03-11 16:09:34.013 ThaliTest[1148:1735215] jxcore: stopAdvertisingAndListening
2016-03-11 16:09:34.014 ThaliTest[1148:1735215] THEMultipeerManager stopping peer
2016-03-11 16:09:34.015 ThaliTest[1148:1735215] jxcore: stopAdvertisingAndListening: success
,ok 58 error should be null

,ok 59 error should be null

,# setup

,2016-03-11 16:09:34.428 ThaliTest[1148:1735215] jxcore: stopAdvertisingAndListening
2016-03-11 16:09:34.428 ThaliTest[1148:1735215] THEMultipeerManager stopping peer
2016-03-11 16:09:34.429 ThaliTest[1148:1735215] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-11 16:09:34.429 ThaliTest[1148:1735215] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}

,2016-03-11 16:09:34.432 ThaliTest[1148:1735215] jxcore: stopListeningForAdvertisements: success
,ok 60 error should be null

,ok 61 error should be null

,# 16. #start should fail if called twice in a row

,# teardown

,ok 62 first call should succeed

,ok 63 first call should succeed

,ok 64 specific error should be returned

,# setup

,2016-03-11 16:09:36.380 ThaliTest[1148:1735215] jxcore: stopAdvertisingAndListening
2016-03-11 16:09:36.380 ThaliTest[1148:1735215] THEMultipeerManager stopping peer
2016-03-11 16:09:36.380 ThaliTest[1148:1735215] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-11 16:09:36.381 ThaliTest[1148:1735215] jxcore: stopListeningForAdvertisements
INFO thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}

,2016-03-11 16:09:36.384 ThaliTest[1148:1735215] jxcore: stopListeningForAdvertisements: success
,ok 65 error should be null

,ok 66 error should be null

,# 17. does not emit duplicate discoveryAdvertisingStateUpdate

,# teardown

,2016-03-11 16:09:36.911 ThaliTest[1148:1735215] jxcore: startListeningForAdvertisements
2016-03-11 16:09:36.912 ThaliTest[1148:1735215] multipeer manager: start client restart timer: 0x165b7520
INFO thaliMobileNativeWrapper: discoveryAdvertisingStateUpda,teNonTCP: {"advertisingActive":false,"discoveryActive":true}

2016-03-11 16:09:36.913 ThaliTest[1148:1735215] jxcore: startListeningForAdvertisements: success
,2016-03-11 16:09:36.928 ThaliTest[1148:1735215] jxcore: startUpdateAdvertisingAndListening
2016-03-11 16:09:36.929 ThaliTest[1148:1735215] server: starting 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:3
,2016-03-11 16:09:36.930 ThaliTest[1148:1735215] THEMultipeerManager initialized peer 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:3
2016-03-11 16:09:36.931 ThaliTest[1148:1735215] jxcore: startUpdateAdvertisingAndListening: success
,ok 67 called only once

,ok 68 discovery state matches

,ok 69 advertising state matches

,# setup

,2016-03-11 16:09:37.089 ThaliTest[1148:1735215] jxcore: stopAdvertisingAndListening
2016-03-11 16:09:37.089 ThaliTest[1148:1735215] THEMultipeerManager stopping peer
2016-03-11 16:09:37.090 ThaliTest[1148:1735215] jxcore: stopAdvertisingAndListening: success
,2016-03-11 16:09:37.090 ThaliTest[1148:1735215] jxcore: stopListeningForAdvertisements
2016-03-11 16:09:37.092 ThaliTest[1148:1735215] multipeer manager: stop client timer
INFO thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisin,gActive":false,"discoveryActive":false}

,2016-03-11 16:09:37.097 ThaliTest[1148:1735215] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}

,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).

,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).

,ok 70 error should be null

,ok 71 error should be null

,# 18. does not send duplicate availability changes

,# teardown

,ok 72 should be called once

,ok 73 should not have been called more than once

,# setup

,ok 74 error should be null

,ok 75 error should be null

,# 19. can get the network status

,# teardown

,ok 76 network status should have certain non-empty properties

,# setup

,ok 77 error should be null

,ok 78 error should be null

,# 20. wifi peer is marked unavailable if announcements stop

,# teardown

,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined

,ok 79 host address should match

,ok 80 port should match

,ok 81 host address should be null

,ok 82 port should should be null

,# setup

,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).

,ok 83 error should be null

,ok 84 error should be null

,# 21. Can call start/stopListeningForAdvertisements

,# teardown

,2016-03-11 16:09:50.226 ThaliTest[1148:1735215] jxcore: startListeningForAdvertisements
2016-03-11 16:09:50.227 ThaliTest[1148:1735215] multipeer manager: start client restart timer: 0x165b7520
,INFO thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}

2016-03-11 16:09:50.229 ThaliTest[1148:1735215] jxcore: startListeningForAdvertisements: success
ok 85 Can call startListeningForAdvertisements without error

,2016-03-11 16:09:50.231 ThaliTest[1148:1735215] jxcore: stopListeningForAdvertisements
2016-03-11 16:09:50.232 ThaliTest[1148:1735215] multipeer manager: stop client timer
,INFO thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}

2016-03-11 16:09:50.235 ThaliTest[1148:1735215] jxcore: stopListeningForAdvertisements: success
ok 86 Can call stopListeningForAdvertisements without error

,# setup

,2016-03-11 16:09:50.517 ThaliTest[1148:1735215] jxcore: stopAdvertisingAndListening
2016-03-11 16:09:50.517 ThaliTest[1148:1735215] THEMultipeerManager stopping peer
2016-03-11 16:09:50.517 ThaliTest[1148:1735215] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-11 16:09:50.518 ThaliTest[1148:1735215] jxcore: stopListeningForAdvertisements
INFO thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}

,2016-03-11 16:09:50.519 ThaliTest[1148:1735215] jxcore: stopListeningForAdvertisements: success
,# 22. Calling startListeningForAdvertisements twice is NOT an error

,# teardown

,2016-03-11 16:09:50.728 ThaliTest[1148:1735215] jxcore: startListeningForAdvertisements
2016-03-11 16:09:50.729 ThaliTest[1148:1735215] multipeer manager: start client restart timer: 0x165b7520
INFO thaliMobileNativeWrapper: discoveryAdvertisingStateUpda,teNonTCP: {"advertisingActive":false,"discoveryActive":true}

2016-03-11 16:09:50.730 ThaliTest[1148:1735215] jxcore: startListeningForAdvertisements: success
,ok 87 Can call startListeningForAdvertisements without error

2016-03-11 16:09:50.734 ThaliTest[1148:1735215] jxcore: startListeningForAdvertisements
INFO thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}

,2016-03-11 16:09:50.736 ThaliTest[1148:1735215] jxcore: startListeningForAdvertisements: success
ok 88 Can call startListeningForAdvertisements twice without error

,# setup

,2016-03-11 16:09:51.117 ThaliTest[1148:1735215] jxcore: stopAdvertisingAndListening
,2016-03-11 16:09:51.118 ThaliTest[1148:1735215] THEMultipeerManager stopping peer
,2016-03-11 16:09:51.118 ThaliTest[1148:1735215] jxcore: stopAdvertisingAndListening: success
,2016-03-11 16:09:51.120 ThaliTest[1148:1735215] jxcore: stopListeningForAdvertisements
2016-03-11 16:09:51.120 ThaliTest[1148:1735215] multipeer manager: stop client timer
INFO thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisin,gActive":false,"discoveryActive":false}

2016-03-11 16:09:51.122 ThaliTest[1148:1735215] jxcore: stopListeningForAdvertisements: success
,# 23. Can call start/stopUpdateAdvertisingAndListening

,# teardown

,2016-03-11 16:09:51.626 ThaliTest[1148:1735215] jxcore: startUpdateAdvertisingAndListening
2016-03-11 16:09:51.627 ThaliTest[1148:1735215] server: starting 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:4
2016-03-11 16:09:51.628 ThaliTest[1148:1735215] multipeer m,anager: start client restart timer: 0x165b7520
2016-03-11 16:09:51.628 ThaliTest[1148:1735215] THEMultipeerManager initialized peer 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:4
2016-03-11 16:09:51.628 ThaliTest[1148:1735215] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 89 Can call startUpdateAdvertisingAndListening without error

2016-03-11 16:09:51.631 ThaliTest[1148:1735215] jxcore: stopAdvertisingAndListening
2016-03-11 16:09:51.631 ThaliTest[1148:1735215] THEMultipeerManager stopping peer
201,6-03-11 16:09:51.631 ThaliTest[1148:1735215] multipeer manager: stop client timer
2016-03-11 16:09:51.632 ThaliTest[1148:1735215] jxcore: stopAdvertisingAndListening: success
ok 90 Can call stopAdvertisingAndListening without error

,# setup
,
,2016-03-11 16:09:51.775 ThaliTest[1148:1735215] jxcore: stopAdvertisingAndListening
2016-03-11 16:09:51.776 ThaliTest[1148:1735215] THEMultipeerManager stopping peer
2016-03-11 16:09:51.776 ThaliTest[1148:1735215] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-11 16:09:51.777 ThaliTest[1148:1735215] jxcore: stopListeningForAdvertisements
INFO thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}

2016-03-11 16:09:51.778 ThaliTest[114,8:1735215] jxcore: stopListeningForAdvertisements: success
,# 24. Calling startUpdateAdvertisingAndListening twice is NOT an error

,# teardown

,2016-03-11 16:09:52.578 ThaliTest[1148:1735215] jxcore: startUpdateAdvertisingAndListening
2016-03-11 16:09:52.579 ThaliTest[1148:1735215] server: starting 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:5
2016-03-11 16:09:52.580 ThaliTest[1148:1735215] multipeer m,anager: start client restart timer: 0x165b7520
2016-03-11 16:09:52.580 ThaliTest[1148:1735215] THEMultipeerManager initialized peer 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:5
2016-03-11 16:09:52.580 ThaliTest[1148:1735215] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 91 Can call startUpdateAdvertisingAndListening without error

,2016-03-11 16:09:52.583 ThaliTest[1148:1735215] jxcore: startUpdateAdvertisingAndListening
2016-03-11 16:09:52.585 ThaliTest[1148:1735215] THEMultipeerManager stopping peer
2016-03-11 16:09:52.585 ThaliTest[1148:1735215] multipeer manager: stop client ti,mer
2016-03-11 16:09:52.585 ThaliTest[1148:1735215] server: starting 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:6
2016-03-11 16:09:52.586 ThaliTest[1148:1735215] multipeer manager: start client restart timer: 0x165b7520
2016-03-11 16:09:52.586 ThaliTest[1148:,1735215] THEMultipeerManager initialized peer 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:6
2016-03-11 16:09:52.586 ThaliTest[1148:1735215] jxcore: startUpdateAdvertisingAndListening: success
ok 92 Can call startUpdateAdvertisingAndListening twice without error,

# setup

,2016-03-11 16:09:53.039 ThaliTest[1148:1735215] jxcore: stopAdvertisingAndListening
2016-03-11 16:09:53.039 ThaliTest[1148:1735215] THEMultipeerManager stopping peer
2016-03-11 16:09:53.040 ThaliTest[1148:1735215] multipeer manager: stop client timer
20,16-03-11 16:09:53.040 ThaliTest[1148:1735215] jxcore: stopAdvertisingAndListening: success
2016-03-11 16:09:53.041 ThaliTest[1148:1735215] jxcore: stopListeningForAdvertisements
INFO thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adve,rtisingActive":false,"discoveryActive":false}

,2016-03-11 16:09:53.042 ThaliTest[1148:1735215] jxcore: stopListeningForAdvertisements: success
# 25. peerAvailabilityChange is called

,# teardown

,2016-03-11 16:09:53.551 ThaliTest[1148:1735215] jxcore: startUpdateAdvertisingAndListening
2016-03-11 16:09:53.552 ThaliTest[1148:1735215] server: starting 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:7
2016-03-11 16:09:53.552 ThaliTest[1148:1735215] multipeer m,anager: start client restart timer: 0x165b7520
2016-03-11 16:09:53.553 ThaliTest[1148:1735215] THEMultipeerManager initialized peer 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:7
2016-03-11 16:09:53.553 ThaliTest[1148:1735215] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 93 Can call startUpdateAdvertisingAndListeningwithout error

2016-03-11 16:09:53.555 ThaliTest[1148:1735215] jxcore: startListeningForAdvertisements
,INFO thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}

2016-03-11 16:09:53.561 ThaliTest[1148:1735215] jxcore: startListeningForAdvertisements: success
ok 94 Can call startListeningForAdvertisements without error

,2016-03-11 16:09:54.780 ThaliTest[1148:1735023] client: found new peer: 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:7
,ok 95 peer must have peerIdentifier

,ok 96 peerIdentifier must be a string

,# setup

,2016-03-11 16:09:55.405 ThaliTest[1148:1735215] jxcore: stopAdvertisingAndListening
2016-03-11 16:09:55.406 ThaliTest[1148:1735215] THEMultipeerManager stopping peer
2016-03-11 16:09:55.406 ThaliTest[1148:1735215] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-11 16:09:55.407 ThaliTest[1148:1735215] jxcore: stopListeningForAdvertisements
2016-03-11 16:09:55.408 ThaliTest[1148:1735215] multipeer manager: stop client timer
INFO thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adve,rtisingActive":false,"discoveryActive":false}

2016-03-11 16:09:55.409 ThaliTest[1148:1735215] jxcore: stopListeningForAdvertisements: success
,# 26. Can connect to a remote peer

,# teardown

,2016-03-11 16:10:11.353 ThaliTest[1148:1735215] jxcore: startUpdateAdvertisingAndListening
2016-03-11 16:10:11.354 ThaliTest[1148:1735215] server: starting 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:8
2016-03-11 16:10:11.354 ThaliTest[1148:1735215] multipeer m,anager: start client restart timer: 0x165b7520
2016-03-11 16:10:11.355 ThaliTest[1148:1735215] THEMultipeerManager initialized peer 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:8
2016-03-11 16:10:11.355 ThaliTest[1148:1735215] jxcore: startUpdateAdvertisingAndLi,stening: success
,ok 97 Can call startUpdateAdvertisingAndListening without error

,2016-03-11 16:10:11.358 ThaliTest[1148:1735215] jxcore: startListeningForAdvertisements
,INFO thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}

2016-03-11 16:10:11.361 ThaliTest[1148:1735215] jxcore: startListeningForAdvertisements: success
,ok 98 Can call startListeningForAdvertisements without error

,2016-03-11 16:10:13.814 ThaliTest[1148:1735023] client: found new peer: 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:7
,2016-03-11 16:10:13.832 ThaliTest[1148:1735215] jxcore: connect 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:7
2016-03-11 16:10:13.832 ThaliTest[1148:1735215] client: server will connect
2016-03-11 16:10:13.833 ThaliTest[1148:1735215] client session: reverseConn,ect
2016-03-11 16:10:13.833 ThaliTest[1148:1735215] client session: stateChange:0->1 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:7
,2016-03-11 16:10:14.778 ThaliTest[1148:1735023] multipeer session: reset timer
2016-03-11 16:10:14.779 ThaliTest[1148:1735023] server: rejecting invitation from 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704 due to previous generation (14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:8 != 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:7)
,2016-03-11 16:10:14.789 ThaliTest[1148:1735707] client session: not connected 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:7
2016-03-11 16:10:14.789 ThaliTest[1148:1735707] client session: onLinkFailure: 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704
2016-03-11 16:10:14.7,90 ThaliTest[1148:1735707] client session: disconnect
2016-03-11 16:10:14.790 ThaliTest[1148:1735707] client session: stateChange:1->0 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:7
2016-03-11 16:10:14.791 ThaliTest[1148:1735707] client session: no connect callb,ack (server initiated)
,2016-03-11 16:10:31.356 ThaliTest[1148:1735023] multipeer manager: restart client
,2016-03-11 16:10:31.375 ThaliTest[1148:1735023] client: found updated peer: 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:8
,2016-03-11 16:10:51.356 ThaliTest[1148:1735023] multipeer manager: restart client
,2016-03-11 16:10:51.373 ThaliTest[1148:1735023] client: found existing peer: 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:8
,2016-03-11 16:11:11.356 ThaliTest[1148:1735023] multipeer manager: restart client
,2016-03-11 16:11:11.376 ThaliTest[1148:1735023] client: found existing peer: 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:8
,2016-03-11 16:11:31.356 ThaliTest[1148:1735023] multipeer manager: restart client
,2016-03-11 16:11:31.374 ThaliTest[1148:1735023] client: found existing peer: 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:8
,2016-03-11 16:11:51.356 ThaliTest[1148:1735023] multipeer manager: restart client
,2016-03-11 16:11:51.373 ThaliTest[1148:1735023] client: found existing peer: 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:8
,2016-03-11 16:12:11.356 ThaliTest[1148:1735023] multipeer manager: restart client
,2016-03-11 16:12:11.375 ThaliTest[1148:1735023] client: found existing peer: 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:8
,2016-03-11 16:12:31.356 ThaliTest[1148:1735023] multipeer manager: restart client
,2016-03-11 16:12:31.374 ThaliTest[1148:1735023] client: found existing peer: 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:8
,2016-03-11 16:12:51.356 ThaliTest[1148:1735023] multipeer manager: restart client
,2016-03-11 16:12:51.373 ThaliTest[1148:1735023] client: found existing peer: 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:8
,2016-03-11 16:13:11.356 ThaliTest[1148:1735023] multipeer manager: restart client
,2016-03-11 16:13:11.373 ThaliTest[1148:1735023] client: found existing peer: 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:8
,2016-03-11 16:13:31.356 ThaliTest[1148:1735023] multipeer manager: restart client
,2016-03-11 16:13:31.376 ThaliTest[1148:1735023] client: found existing peer: 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:8
,2016-03-11 16:13:51.356 ThaliTest[1148:1735023] multipeer manager: restart client
,2016-03-11 16:13:51.373 ThaliTest[1148:1735023] client: found existing peer: 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:8
,2016-03-11 16:14:11.356 ThaliTest[1148:1735023] multipeer manager: restart client
,2016-03-11 16:14:11.373 ThaliTest[1148:1735023] client: found existing peer: 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:8
,2016-03-11 16:14:31.356 ThaliTest[1148:1735023] multipeer manager: restart client
,2016-03-11 16:14:31.374 ThaliTest[1148:1735023] client: found existing peer: 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:8
,2016-03-11 16:14:51.356 ThaliTest[1148:1735023] multipeer manager: restart client
,2016-03-11 16:14:51.373 ThaliTest[1148:1735023] client: found existing peer: 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:8
,2016-03-11 16:15:11.356 ThaliTest[1148:1735023] multipeer manager: restart client
,2016-03-11 16:15:11.376 ThaliTest[1148:1735023] client: found existing peer: 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:8
,2016-03-11 16:15:31.356 ThaliTest[1148:1735023] multipeer manager: restart client
,2016-03-11 16:15:31.375 ThaliTest[1148:1735023] client: found existing peer: 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:8
,2016-03-11 16:15:51.356 ThaliTest[1148:1735023] multipeer manager: restart client
,2016-03-11 16:15:51.373 ThaliTest[1148:1735023] client: found existing peer: 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:8
,2016-03-11 16:16:11.356 ThaliTest[1148:1735023] multipeer manager: restart client
,2016-03-11 16:16:11.375 ThaliTest[1148:1735023] client: found existing peer: 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:8
,2016-03-11 16:16:31.356 ThaliTest[1148:1735023] multipeer manager: restart client
,2016-03-11 16:16:31.374 ThaliTest[1148:1735023] client: found existing peer: 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:8
,2016-03-11 16:16:51.356 ThaliTest[1148:1735023] multipeer manager: restart client
,2016-03-11 16:16:51.371 ThaliTest[1148:1735023] client: found existing peer: 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:8
,2016-03-11 16:17:11.356 ThaliTest[1148:1735023] multipeer manager: restart client
,2016-03-11 16:17:11.375 ThaliTest[1148:1735023] client: found existing peer: 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:8
,2016-03-11 16:17:31.356 ThaliTest[1148:1735023] multipeer manager: restart client
,2016-03-11 16:17:31.374 ThaliTest[1148:1735023] client: found existing peer: 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:8
,2016-03-11 16:17:51.356 ThaliTest[1148:1735023] multipeer manager: restart client
,2016-03-11 16:17:51.374 ThaliTest[1148:1735023] client: found existing peer: 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:8
,2016-03-11 16:18:11.356 ThaliTest[1148:1735023] multipeer manager: restart client
,2016-03-11 16:18:11.373 ThaliTest[1148:1735023] client: found existing peer: 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:8
,2016-03-11 16:18:31.356 ThaliTest[1148:1735023] multipeer manager: restart client
,2016-03-11 16:18:31.373 ThaliTest[1148:1735023] client: found existing peer: 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:8
,2016-03-11 16:18:51.356 ThaliTest[1148:1735023] multipeer manager: restart client
,2016-03-11 16:18:51.374 ThaliTest[1148:1735023] client: found existing peer: 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:8
,2016-03-11 16:19:11.356 ThaliTest[1148:1735023] multipeer manager: restart client
,2016-03-11 16:19:11.373 ThaliTest[1148:1735023] client: found existing peer: 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:8
,2016-03-11 16:19:31.356 ThaliTest[1148:1735023] multipeer manager: restart client
,2016-03-11 16:19:31.373 ThaliTest[1148:1735023] client: found existing peer: 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:8
,2016-03-11 16:19:51.356 ThaliTest[1148:1735023] multipeer manager: restart client
,2016-03-11 16:19:51.372 ThaliTest[1148:1735023] client: found existing peer: 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:8
,2016-03-11 16:20:11.356 ThaliTest[1148:1735023] multipeer manager: restart client
,2016-03-11 16:20:11.374 ThaliTest[1148:1735023] client: found existing peer: 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:8
,2016-03-11 16:20:31.356 ThaliTest[1148:1735023] multipeer manager: restart client
,2016-03-11 16:20:31.374 ThaliTest[1148:1735023] client: found existing peer: 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:8
,2016-03-11 16:20:51.356 ThaliTest[1148:1735023] multipeer manager: restart client
,2016-03-11 16:20:51.375 ThaliTest[1148:1735023] client: found existing peer: 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:8
,2016-03-11 16:21:11.356 ThaliTest[1148:1735023] multipeer manager: restart client
,2016-03-11 16:21:11.375 ThaliTest[1148:1735023] client: found existing peer: 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:8
,2016-03-11 16:21:31.356 ThaliTest[1148:1735023] multipeer manager: restart client
,2016-03-11 16:21:31.374 ThaliTest[1148:1735023] client: found existing peer: 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:8
,2016-03-11 16:21:51.356 ThaliTest[1148:1735023] multipeer manager: restart client
,2016-03-11 16:21:51.377 ThaliTest[1148:1735023] client: found existing peer: 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:8
,2016-03-11 16:22:11.356 ThaliTest[1148:1735023] multipeer manager: restart client
,2016-03-11 16:22:11.378 ThaliTest[1148:1735023] client: found existing peer: 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:8
,2016-03-11 16:22:31.356 ThaliTest[1148:1735023] multipeer manager: restart client
,2016-03-11 16:22:31.373 ThaliTest[1148:1735023] client: found existing peer: 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:8
,2016-03-11 16:22:51.356 ThaliTest[1148:1735023] multipeer manager: restart client
,2016-03-11 16:22:51.372 ThaliTest[1148:1735023] client: found existing peer: 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:8
,2016-03-11 16:23:11.356 ThaliTest[1148:1735023] multipeer manager: restart client
,2016-03-11 16:23:11.373 ThaliTest[1148:1735023] client: found existing peer: 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:8
,2016-03-11 16:23:31.356 ThaliTest[1148:1735023] multipeer manager: restart client
,2016-03-11 16:23:31.375 ThaliTest[1148:1735023] client: found existing peer: 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:8
,2016-03-11 16:23:51.356 ThaliTest[1148:1735023] multipeer manager: restart client
,2016-03-11 16:23:51.374 ThaliTest[1148:1735023] client: found existing peer: 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:8
,2016-03-11 16:24:11.356 ThaliTest[1148:1735023] multipeer manager: restart client
,2016-03-11 16:24:11.372 ThaliTest[1148:1735023] client: found existing peer: 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:8
,2016-03-11 16:24:31.356 ThaliTest[1148:1735023] multipeer manager: restart client
,2016-03-11 16:24:31.375 ThaliTest[1148:1735023] client: found existing peer: 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:8
,2016-03-11 16:24:51.356 ThaliTest[1148:1735023] multipeer manager: restart client
,2016-03-11 16:24:51.375 ThaliTest[1148:1735023] client: found existing peer: 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:8
,2016-03-11 16:25:11.356 ThaliTest[1148:1735023] multipeer manager: restart client
,2016-03-11 16:25:11.374 ThaliTest[1148:1735023] client: found existing peer: 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:8
,2016-03-11 16:25:31.356 ThaliTest[1148:1735023] multipeer manager: restart client
,2016-03-11 16:25:31.375 ThaliTest[1148:1735023] client: found existing peer: 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:8
,2016-03-11 16:25:51.356 ThaliTest[1148:1735023] multipeer manager: restart client
,2016-03-11 16:25:51.373 ThaliTest[1148:1735023] client: found existing peer: 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:8
,2016-03-11 16:26:11.356 ThaliTest[1148:1735023] multipeer manager: restart client
,2016-03-11 16:26:11.375 ThaliTest[1148:1735023] client: found existing peer: 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:8
,2016-03-11 16:26:31.356 ThaliTest[1148:1735023] multipeer manager: restart client
,2016-03-11 16:26:31.374 ThaliTest[1148:1735023] client: found existing peer: 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:8
,2016-03-11 16:26:51.356 ThaliTest[1148:1735023] multipeer manager: restart client
,2016-03-11 16:26:51.374 ThaliTest[1148:1735023] client: found existing peer: 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:8

```
