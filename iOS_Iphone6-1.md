#### Test 6262501074dad8f_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/6262501074dad8f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/CF22672E-DC20-4CF5-8662-CD474A4967DE/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/CF22672E-DC20-4CF5-8662-CD474A4967DE/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/6262501074dad8f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/6262501074dad8f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/1FBAB8DA-D936-4120-8CAF-55877A8A483E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51007"
,(lldb)     command script import "/tmp/CF22672E-DC20-4CF5-8662-CD474A4967DE/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-14 23:37:46.125 ThaliTest[1373:2209954] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F62948D5-E229-41F2-AF8B-5D7DF84FC40F/Library/Cookies/Cookies.binarycookies
,2016-03-14 23:37:46.533 ThaliTest[1373:2209954] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-14 23:37:46.535 ThaliTest[1373:2209954] Multi-tasking -> Device: YES, App: YES
,2016-03-14 23:37:46.563 ThaliTest[1373:2209954] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-14 23:37:48.491 ThaliTest[1373:2209954] Using UIWebView
,2016-03-14 23:37:48.500 ThaliTest[1373:2209954] [CDVTimer][handleopenurl] 0.420034ms
,2016-03-14 23:37:48.508 ThaliTest[1373:2209954] [CDVTimer][intentandnavigationfilter] 7.247984ms
2016-03-14 23:37:48.509 ThaliTest[1373:2209954] [CDVTimer][gesturehandler] 0.357985ms
2016-03-14 23:37:48.509 ThaliTest[1373:2209954] [CDVTimer][TotalPluginS,tartup] 9.742975ms
,2016-03-14 23:37:55.118 ThaliTest[1373:2209954] Resetting plugins due to page load.
,2016-03-14 23:37:57.766 ThaliTest[1373:2209954] Finished load of: file:///var/mobile/Containers/Bundle/Application/1FBAB8DA-D936-4120-8CAF-55877A8A483E/ThaliTest.app/www/index.html
,2016-03-14 23:37:57.995 ThaliTest[1373:2209954] JXcore Cordova plugin initializing
,2016-03-14 23:37:57.996 ThaliTest[1373:2210162] JXcore instance initializing
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

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1FBAB8DA-D936-4120-8CAF-55877A8A483E/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1FBAB8DA-D936-4120-8CAF-55877A8A483E/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1FBAB8DA-D936-4120-8CAF-55877A8A483E/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1FBAB8DA-D936-4120-8CAF-55877A8A483E/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1FBAB8DA-D936-4120-8CAF-55877A8A483E/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1FBAB8DA-D936-4120-8CAF-55877A8A483E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-14 23:38:12.068 ThaliTest[1373:2210162] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-14 23:38:12.068 ThaliTest[1373:2210162] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-14 23:38:12.069 ThaliTest[1373:2210162] jxcore: didRegisterToNative networkChanged
,2016-03-14 23:38:12.070 ThaliTest[1373:2210162] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1FBAB8DA-D936-4120-8CAF-55877A8A483E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1FBAB8DA-D936-4120-8CAF-55877A8A483E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1FBAB8DA-D936-4120-8CAF-55877A8A483E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1FBAB8DA-D936-4120-8CAF-55877A8A483E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1FBAB8DA-D936-4120-8CAF-55877A8A483E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1FBAB8DA-D936-4120-8CAF-55877A8A483E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1FBAB8DA-D936-4120-8CAF-55877A8A483E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1FBAB8DA-D936-4120-8CAF-55877A8A483E/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1FBAB8DA-D936-4120-8CAF-55877A8A483E/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1FBAB8DA-D936-4120-8CAF-55877A8A483E/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1FBAB8DA-D936-4120-8CAF-55877A8A483E/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1FBAB8DA-D936-4120-8CAF-55877A8A483E/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

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

,2016-03-14 23:41:08.367 ThaliTest[1373:2210162] jxcore: stopListeningForAdvertisements
,2016-03-14 23:41:08.369 ThaliTest[1373:2210162] jxcore: stopListeningForAdvertisements: success
,ok 38 error should be null

,ok 39 error should be null

,2016-03-14 23:41:08.375 ThaliTest[1373:2210162] jxcore: stopListeningForAdvertisements
,2016-03-14 23:41:08.376 ThaliTest[1373:2210162] jxcore: stopListeningForAdvertisements: success
,ok 40 error should be null

,ok 41 error should be null

,# setup

,2016-03-14 23:41:08.506 ThaliTest[1373:2210162] jxcore: stopAdvertisingAndListening
2016-03-14 23:41:08.506 ThaliTest[1373:2210162] THEMultipeerManager stopping peer
,2016-03-14 23:41:08.507 ThaliTest[1373:2210162] jxcore: stopAdvertisingAndListening: success
,2016-03-14 23:41:08.509 ThaliTest[1373:2210162] jxcore: stopListeningForAdvertisements
,2016-03-14 23:41:08.510 ThaliTest[1373:2210162] jxcore: stopListeningForAdvertisements: success
,ok 42 error should be null

,ok 43 error should be null

,# 13. should be able to call #startListeningForAdvertisements many times

,# teardown

,2016-03-14 23:41:08.813 ThaliTest[1373:2210162] jxcore: startListeningForAdvertisements
,2016-03-14 23:41:08.814 ThaliTest[1373:2210162] multipeer manager: start client restart timer: 0x15e78810
,2016-03-14 23:41:08.817 ThaliTest[1373:2210162] jxcore: startListeningForAdvertisements: success
,ok 44 error should be null

,ok 45 error should be null

,2016-03-14 23:41:08.850 ThaliTest[1373:2210162] jxcore: startListeningForAdvertisements
,2016-03-14 23:41:08.852 ThaliTest[1373:2210162] jxcore: startListeningForAdvertisements: success
,ok 46 error should be null

,ok 47 error should be null

,# setup

,2016-03-14 23:41:09.122 ThaliTest[1373:2210162] jxcore: stopAdvertisingAndListening
2016-03-14 23:41:09.122 ThaliTest[1373:2210162] THEMultipeerManager stopping peer
2016-03-14 23:41:09.123 ThaliTest[1373:2210162] jxcore: stopAdvertisingAndListening: success
2016-03-14 23:41:09.123 ThaliTest[1373:2210162] jxcore: stopListeningForAdvertisements
,2016-03-14 23:41:09.124 ThaliTest[1373:2210162] multipeer manager: stop client timer
,2016-03-14 23:41:09.129 ThaliTest[1373:2210162] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).

,ok 48 error should be null

,ok 49 error should be null

,# 14. should be able to call #startUpdateAdvertisingAndListening many times

,# teardown

,2016-03-14 23:41:09.607 ThaliTest[1373:2210162] jxcore: startUpdateAdvertisingAndListening
2016-03-14 23:41:09.608 ThaliTest[1373:2210162] server: starting A23A2191-9ACE-4296-8393-82BF95886094:1
2016-03-14 23:41:09.609 ThaliTest[1373:2210162] multipeer m,anager: start client restart timer: 0x15e78810
2016-03-14 23:41:09.609 ThaliTest[1373:2210162] THEMultipeerManager initialized peer A23A2191-9ACE-4296-8393-82BF95886094:1
2016-03-14 23:41:09.609 ThaliTest[1373:2210162] jxcore: startUpdateAdvertisingAndLi,stening: success
,ok 50 error should be null

ok 51 error should be null

,2016-03-14 23:41:09.628 ThaliTest[1373:2210162] jxcore: startUpdateAdvertisingAndListening
2016-03-14 23:41:09.629 ThaliTest[1373:2210162] THEMultipeerManager stopping peer
,2016-03-14 23:41:09.630 ThaliTest[1373:2210162] multipeer manager: stop client timer
2016-03-14 23:41:09.631 ThaliTest[1373:2210162] server: starting A23A2191-9ACE-4296-8393-82BF95886094:2
2016-03-14 23:41:09.634 ThaliTest[1373:2210162] multipeer manager,: start client restart timer: 0x15e78810
2016-03-14 23:41:09.635 ThaliTest[1373:2210162] THEMultipeerManager initialized peer A23A2191-9ACE-4296-8393-82BF95886094:2
2016-03-14 23:41:09.635 ThaliTest[1373:2210162] jxcore: startUpdateAdvertisingAndListening: success
,ok 52 error should be null

,ok 53 error should be null

,# setup

,2016-03-14 23:41:09.757 ThaliTest[1373:2210162] jxcore: stopAdvertisingAndListening
2016-03-14 23:41:09.757 ThaliTest[1373:2210162] THEMultipeerManager stopping peer
2016-03-14 23:41:09.758 ThaliTest[1373:2210162] multipeer manager: stop client timer
,2016-03-14 23:41:09.760 ThaliTest[1373:2210162] jxcore: stopAdvertisingAndListening: success
2016-03-14 23:41:09.761 ThaliTest[1373:2210162] jxcore: stopListeningForAdvertisements
,2016-03-14 23:41:09.764 ThaliTest[1373:2210162] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).

,ok 54 error should be null

,ok 55 error should be null

,# 15. should be able to call #stopAdvertisingAndListening many times

,# teardown

,2016-03-14 23:41:10.266 ThaliTest[1373:2210162] jxcore: stopAdvertisingAndListening
2016-03-14 23:41:10.266 ThaliTest[1373:2210162] THEMultipeerManager stopping peer
2016-03-14 23:41:10.267 ThaliTest[1373:2210162] jxcore: stopAdvertisingAndListening: success
ok 56 error should be null

,ok 57 error should be null

,2016-03-14 23:41:10.273 ThaliTest[1373:2210162] jxcore: stopAdvertisingAndListening
2016-03-14 23:41:10.273 ThaliTest[1373:2210162] THEMultipeerManager stopping peer
2016-03-14 23:41:10.273 ThaliTest[1373:2210162] jxcore: stopAdvertisingAndListening: suc,cess
ok 58 error should be null

,ok 59 error should be null

,# setup

,2016-03-14 23:41:10.630 ThaliTest[1373:2210162] jxcore: stopAdvertisingAndListening
2016-03-14 23:41:10.630 ThaliTest[1373:2210162] THEMultipeerManager stopping peer
2016-03-14 23:41:10.631 ThaliTest[1373:2210162] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-14 23:41:10.631 ThaliTest[1373:2210162] jxcore: stopListeningForAdvertisements
,2016-03-14 23:41:10.633 ThaliTest[1373:2210162] jxcore: stopListeningForAdvertisements: success
,ok 60 error should be null

,ok 61 error should be null

,# 16. #start should fail if called twice in a row

,# teardown

,ok 62 first call should succeed

,ok 63 first call should succeed

,ok 64 specific error should be returned

,# setup

,2016-03-14 23:41:12.411 ThaliTest[1373:2210162] jxcore: stopAdvertisingAndListening
2016-03-14 23:41:12.411 ThaliTest[1373:2210162] THEMultipeerManager stopping peer
2016-03-14 23:41:12.411 ThaliTest[1373:2210162] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-14 23:41:12.412 ThaliTest[1373:2210162] jxcore: stopListeningForAdvertisements
2016-03-14 23:41:12.413 ThaliTest[1373:2210162] jxcore: stopListeningForAdvertisements: success
,ok 65 error should be null

,ok 66 error should be null

,# 17. does not emit duplicate discoveryAdvertisingStateUpdate

,# teardown

,2016-03-14 23:41:12.871 ThaliTest[1373:2210162] jxcore: startListeningForAdvertisements
2016-03-14 23:41:12.872 ThaliTest[1373:2210162] multipeer manager: start client restart timer: 0x15e78810
2016-03-14 23:41:12.873 ThaliTest[1373:2210162] jxcore: startListeningForAdvertisements: success
,2016-03-14 23:41:12.899 ThaliTest[1373:2210162] jxcore: startUpdateAdvertisingAndListening
2016-03-14 23:41:12.900 ThaliTest[1373:2210162] server: starting A23A2191-9ACE-4296-8393-82BF95886094:3
2016-03-14 23:41:12.900 ThaliTest[1373:2210162] THEMultipee,rManager initialized peer A23A2191-9ACE-4296-8393-82BF95886094:3
2016-03-14 23:41:12.901 ThaliTest[1373:2210162] jxcore: startUpdateAdvertisingAndListening: success
,ok 67 called only once

,ok 68 discovery state matches

,ok 69 advertising state matches

,# setup

,2016-03-14 23:41:13.122 ThaliTest[1373:2210162] jxcore: stopAdvertisingAndListening
2016-03-14 23:41:13.122 ThaliTest[1373:2210162] THEMultipeerManager stopping peer
2016-03-14 23:41:13.123 ThaliTest[1373:2210162] jxcore: stopAdvertisingAndListening: success
,2016-03-14 23:41:13.123 ThaliTest[1373:2210162] jxcore: stopListeningForAdvertisements
2016-03-14 23:41:13.125 ThaliTest[1373:2210162] multipeer manager: stop client timer
2016-03-14 23:41:13.127 ThaliTest[1373:2210162] jxcore: stopListeningForAdvertisements: success
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

,2016-03-14 23:41:17.121 ThaliTest[1373:2210162] jxcore: startListeningForAdvertisements
2016-03-14 23:41:17.122 ThaliTest[1373:2210162] multipeer manager: start client restart timer: 0x15e78810
2016-03-14 23:41:17.123 ThaliTest[1373:2210162] jxcore: star,tListeningForAdvertisements: success
,ok 85 Can call startListeningForAdvertisements without error

,2016-03-14 23:41:17.126 ThaliTest[1373:2210162] jxcore: stopListeningForAdvertisements
2016-03-14 23:41:17.132 ThaliTest[1373:2210162] multipeer manager: stop client timer
,2016-03-14 23:41:17.134 ThaliTest[1373:2210162] jxcore: stopListeningForAdvertisements: success
ok 86 Can call stopListeningForAdvertisements without error

,# setup

,2016-03-14 23:41:17.366 ThaliTest[1373:2210162] jxcore: stopAdvertisingAndListening
2016-03-14 23:41:17.367 ThaliTest[1373:2210162] THEMultipeerManager stopping peer
2016-03-14 23:41:17.367 ThaliTest[1373:2210162] jxcore: stopAdvertisingAndListening: success
2016-03-14 23:41:17.368 ThaliTest[1373:2210162] jxcore: stopListeningForAdvertisements
2016-03-14 23:41:17.369 ThaliTest[1373:2210162] jxcore: stopListeningForAdvertisements: success
,# 22. Calling startListeningForAdvertisements twice is NOT an error

,# teardown

,2016-03-14 23:41:17.896 ThaliTest[1373:2210162] jxcore: startListeningForAdvertisements
2016-03-14 23:41:17.897 ThaliTest[1373:2210162] multipeer manager: start client restart timer: 0x15e78810
,2016-03-14 23:41:17.898 ThaliTest[1373:2210162] jxcore: startListeningForAdvertisements: success
,ok 87 Can call startListeningForAdvertisements without error

,2016-03-14 23:41:17.902 ThaliTest[1373:2210162] jxcore: startListeningForAdvertisements
2016-03-14 23:41:17.903 ThaliTest[1373:2210162] jxcore: startListeningForAdvertisements: success
ok 88 Can call startListeningForAdvertisements twice without error

,# setup

,2016-03-14 23:41:17.994 ThaliTest[1373:2210162] jxcore: stopAdvertisingAndListening
2016-03-14 23:41:17.995 ThaliTest[1373:2210162] THEMultipeerManager stopping peer
2016-03-14 23:41:17.995 ThaliTest[1373:2210162] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-14 23:41:17.996 ThaliTest[1373:2210162] jxcore: stopListeningForAdvertisements
2016-03-14 23:41:17.996 ThaliTest[1373:2210162] multipeer manager: stop client timer
2016-03-14 23:41:17.997 ThaliTest[1373:2210162] jxcore: stopListeningForAdve,rtisements: success
,# 23. Can call start/stopUpdateAdvertisingAndListening

,# teardown

,2016-03-14 23:41:18.508 ThaliTest[1373:2210162] jxcore: startUpdateAdvertisingAndListening
2016-03-14 23:41:18.509 ThaliTest[1373:2210162] server: starting A23A2191-9ACE-4296-8393-82BF95886094:4
2016-03-14 23:41:18.509 ThaliTest[1373:2210162] multipeer manager: start client restart timer: 0x15e78810
,2016-03-14 23:41:18.512 ThaliTest[1373:2210162] THEMultipeerManager initialized peer A23A2191-9ACE-4296-8393-82BF95886094:4
2016-03-14 23:41:18.512 ThaliTest[1373:2210162] jxcore: startUpdateAdvertisingAndListening: success
ok 89 Can call startUpdateAdvertisingAndListening without error

,2016-03-14 23:41:18.515 ThaliTest[1373:2210162] jxcore: stopAdvertisingAndListening
2016-03-14 23:41:18.515 ThaliTest[1373:2210162] THEMultipeerManager stopping peer
2016-03-14 23:41:18.516 ThaliTest[1373:2210162] multipeer manager: stop client timer
2016-03-14 23:41:18.516 ThaliTest[1373:2210162] jxcore: stopAdvertisingAndListening: success
ok 90 Can call stopAdvertisingAndListening without error

# setup

,2016-03-14 23:41:19.004 ThaliTest[1373:2210162] jxcore: stopAdvertisingAndListening
2016-03-14 23:41:19.005 ThaliTest[1373:2210162] THEMultipeerManager stopping peer
2016-03-14 23:41:19.005 ThaliTest[1373:2210162] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-14 23:41:19.006 ThaliTest[1373:2210162] jxcore: stopListeningForAdvertisements
2016-03-14 23:41:19.007 ThaliTest[1373:2210162] jxcore: stopListeningForAdvertisements: success
,# 24. Calling startUpdateAdvertisingAndListening twice is NOT an error

,# teardown

,2016-03-14 23:41:19.190 ThaliTest[1373:2210162] jxcore: startUpdateAdvertisingAndListening
2016-03-14 23:41:19.191 ThaliTest[1373:2210162] server: starting A23A2191-9ACE-4296-8393-82BF95886094:5
2016-03-14 23:41:19.192 ThaliTest[1373:2210162] multipeer m,anager: start client restart timer: 0x15e78810
2016-03-14 23:41:19.192 ThaliTest[1373:2210162] THEMultipeerManager initialized peer A23A2191-9ACE-4296-8393-82BF95886094:5
2016-03-14 23:41:19.193 ThaliTest[1373:2210162] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 91 Can call startUpdateAdvertisingAndListening without error

,2016-03-14 23:41:19.195 ThaliTest[1373:2210162] jxcore: startUpdateAdvertisingAndListening
,2016-03-14 23:41:19.196 ThaliTest[1373:2210162] THEMultipeerManager stopping peer
,2016-03-14 23:41:19.197 ThaliTest[1373:2210162] multipeer manager: stop client timer
2016-03-14 23:41:19.198 ThaliTest[1373:2210162] server: starting A23A2191-9ACE-4296-8393-82BF95886094:6
2016-03-14 23:41:19.198 ThaliTest[1373:2210162] multipeer manager,: start client restart timer: 0x15e78810
2016-03-14 23:41:19.199 ThaliTest[1373:2210162] THEMultipeerManager initialized peer A23A2191-9ACE-4296-8393-82BF95886094:6
2016-03-14 23:41:19.199 ThaliTest[1373:2210162] jxcore: startUpdateAdvertisingAndListenin,g: success
ok 92 Can call startUpdateAdvertisingAndListening twice without error

# setup

,2016-03-14 23:41:19.515 ThaliTest[1373:2210162] jxcore: stopAdvertisingAndListening
2016-03-14 23:41:19.516 ThaliTest[1373:2210162] THEMultipeerManager stopping peer
2016-03-14 23:41:19.516 ThaliTest[1373:2210162] multipeer manager: stop client timer
20,16-03-14 23:41:19.517 ThaliTest[1373:2210162] jxcore: stopAdvertisingAndListening: success
2016-03-14 23:41:19.517 ThaliTest[1373:2210162] jxcore: stopListeningForAdvertisements
2016-03-14 23:41:19.518 ThaliTest[1373:2210162] jxcore: stopListeningForAdve,rtisements: success
,# 25. peerAvailabilityChange is called

,# teardown

,2016-03-14 23:41:19.919 ThaliTest[1373:2210162] jxcore: startUpdateAdvertisingAndListening
2016-03-14 23:41:19.920 ThaliTest[1373:2210162] server: starting A23A2191-9ACE-4296-8393-82BF95886094:7
2016-03-14 23:41:19.920 ThaliTest[1373:2210162] multipeer m,anager: start client restart timer: 0x15e78810
2016-03-14 23:41:19.921 ThaliTest[1373:2210162] THEMultipeerManager initialized peer A23A2191-9ACE-4296-8393-82BF95886094:7
2016-03-14 23:41:19.921 ThaliTest[1373:2210162] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 93 Can call startUpdateAdvertisingAndListeningwithout error

2016-03-14 23:41:19.923 ThaliTest[1373:2210162] jxcore: startListeningForAdvertisements
2016-03-14 23:41:19.925 ThaliTest[1373:2210162] jxcore: startListeningForAdvertisements: success
,ok 94 Can call startListeningForAdvertisements without error

,2016-03-14 23:41:20.919 ThaliTest[1373:2209954] client: found new peer: 435ACF87-6352-482F-B5FA-1EDD8A011FA8:7
,ok 95 peer must have peerIdentifier

,ok 96 peerIdentifier must be a string

,# setup

,2016-03-14 23:41:21.607 ThaliTest[1373:2210162] jxcore: stopAdvertisingAndListening
2016-03-14 23:41:21.608 ThaliTest[1373:2210162] THEMultipeerManager stopping peer
2016-03-14 23:41:21.608 ThaliTest[1373:2210162] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-14 23:41:21.609 ThaliTest[1373:2210162] jxcore: stopListeningForAdvertisements
2016-03-14 23:41:21.610 ThaliTest[1373:2210162] multipeer manager: stop client timer
2016-03-14 23:41:21.611 ThaliTest[1373:2210162] jxcore: stopListeningForAdve,rtisements: success
,# 26. Can connect to a remote peer

,# teardown

,2016-03-14 23:41:21.800 ThaliTest[1373:2210162] jxcore: startUpdateAdvertisingAndListening
2016-03-14 23:41:21.801 ThaliTest[1373:2210162] server: starting A23A2191-9ACE-4296-8393-82BF95886094:8
2016-03-14 23:41:21.802 ThaliTest[1373:2210162] multipeer m,anager: start client restart timer: 0x15e78810
2016-03-14 23:41:21.802 ThaliTest[1373:2210162] THEMultipeerManager initialized peer A23A2191-9ACE-4296-8393-82BF95886094:8
2016-03-14 23:41:21.803 ThaliTest[1373:2210162] jxcore: startUpdateAdvertisingAndListening: success
,ok 97 Can call startUpdateAdvertisingAndListening without error

,2016-03-14 23:41:21.806 ThaliTest[1373:2210162] jxcore: startListeningForAdvertisements
,2016-03-14 23:41:21.808 ThaliTest[1373:2210162] jxcore: startListeningForAdvertisements: success
ok 98 Can call startListeningForAdvertisements without error

,2016-03-14 23:41:22.743 ThaliTest[1373:2209954] client: found new peer: 435ACF87-6352-482F-B5FA-1EDD8A011FA8:7
,2016-03-14 23:41:22.761 ThaliTest[1373:2210162] jxcore: connect 435ACF87-6352-482F-B5FA-1EDD8A011FA8:7
2016-03-14 23:41:22.762 ThaliTest[1373:2210162] client session: connect
2016-03-14 23:41:22.763 ThaliTest[1373:2210162] client session: stateChange:0->1 435ACF87-6352-482F-B5FA-1EDD8A011FA8:7
,2016-03-14 23:41:23.419 ThaliTest[1373:2209954] multipeer session: reset timer
2016-03-14 23:41:23.419 ThaliTest[1373:2209954] server: rejecting invitation from 435ACF87-6352-482F-B5FA-1EDD8A011FA8 due to previous generation (A23A2191-9ACE-4296-8393-82BF9,5886094:8 != A23A2191-9ACE-4296-8393-82BF95886094:7)
,2016-03-14 23:41:23.453 ThaliTest[1373:2210503] client session: not connected 435ACF87-6352-482F-B5FA-1EDD8A011FA8:7
2016-03-14 23:41:23.455 ThaliTest[1373:2210503] client session: onLinkFailure: 435ACF87-6352-482F-B5FA-1EDD8A011FA8
2016-03-14 23:41:23.456 ThaliTest[1373:2210503] client session: disconnect
2016-03-14 23:41:23.456 ThaliTest[1373:2210503] client session: stateChange:1->0 435ACF87-6352-482F-B5FA-1EDD8A011FA8:7
,2016-03-14 23:41:23.458 ThaliTest[1373:2210503] client session: fireConnectCallback: 435ACF87-6352-482F-B5FA-1EDD8A011FA8
2016-03-14 23:41:23.459 ThaliTest[1373:2210503] jxcore: connect: fail: Peer disconnected
,not ok 99 Error from connect: Peer disconnected

,  ---
,
,    operator: fail

,  ...
,
,# setup

,2016-03-14 23:41:41.804 ThaliTest[1373:2209954] multipeer manager: restart client
,2016-03-14 23:41:41.823 ThaliTest[1373:2209954] client: found updated peer: 435ACF87-6352-482F-B5FA-1EDD8A011FA8:8
,2016-03-14 23:42:01.803 ThaliTest[1373:2209954] multipeer manager: restart client
,2016-03-14 23:42:01.820 ThaliTest[1373:2209954] client: found existing peer: 435ACF87-6352-482F-B5FA-1EDD8A011FA8:8
,2016-03-14 23:42:21.804 ThaliTest[1373:2209954] multipeer manager: restart client
,2016-03-14 23:42:21.821 ThaliTest[1373:2209954] client: found existing peer: 435ACF87-6352-482F-B5FA-1EDD8A011FA8:8
,2016-03-14 23:42:41.804 ThaliTest[1373:2209954] multipeer manager: restart client
,2016-03-14 23:42:41.820 ThaliTest[1373:2209954] client: found existing peer: 435ACF87-6352-482F-B5FA-1EDD8A011FA8:8
,2016-03-14 23:43:01.804 ThaliTest[1373:2209954] multipeer manager: restart client
,2016-03-14 23:43:01.819 ThaliTest[1373:2209954] client: found existing peer: 435ACF87-6352-482F-B5FA-1EDD8A011FA8:8
,2016-03-14 23:43:21.804 ThaliTest[1373:2209954] multipeer manager: restart client
,2016-03-14 23:43:21.821 ThaliTest[1373:2209954] client: found existing peer: 435ACF87-6352-482F-B5FA-1EDD8A011FA8:8
,2016-03-14 23:43:41.804 ThaliTest[1373:2209954] multipeer manager: restart client
,2016-03-14 23:43:41.822 ThaliTest[1373:2209954] client: found existing peer: 435ACF87-6352-482F-B5FA-1EDD8A011FA8:8
,2016-03-14 23:44:01.803 ThaliTest[1373:2209954] multipeer manager: restart client
,2016-03-14 23:44:01.822 ThaliTest[1373:2209954] client: found existing peer: 435ACF87-6352-482F-B5FA-1EDD8A011FA8:8
,2016-03-14 23:44:21.804 ThaliTest[1373:2209954] multipeer manager: restart client
,2016-03-14 23:44:21.822 ThaliTest[1373:2209954] client: found existing peer: 435ACF87-6352-482F-B5FA-1EDD8A011FA8:8
,2016-03-14 23:44:41.804 ThaliTest[1373:2209954] multipeer manager: restart client
,2016-03-14 23:44:41.821 ThaliTest[1373:2209954] client: found existing peer: 435ACF87-6352-482F-B5FA-1EDD8A011FA8:8
,2016-03-14 23:45:01.803 ThaliTest[1373:2209954] multipeer manager: restart client
,2016-03-14 23:45:01.820 ThaliTest[1373:2209954] client: found existing peer: 435ACF87-6352-482F-B5FA-1EDD8A011FA8:8
,2016-03-14 23:45:21.804 ThaliTest[1373:2209954] multipeer manager: restart client
,2016-03-14 23:45:21.820 ThaliTest[1373:2209954] client: found existing peer: 435ACF87-6352-482F-B5FA-1EDD8A011FA8:8
,2016-03-14 23:45:41.804 ThaliTest[1373:2209954] multipeer manager: restart client
,2016-03-14 23:45:41.819 ThaliTest[1373:2209954] client: found existing peer: 435ACF87-6352-482F-B5FA-1EDD8A011FA8:8
,2016-03-14 23:46:01.804 ThaliTest[1373:2209954] multipeer manager: restart client
,2016-03-14 23:46:01.821 ThaliTest[1373:2209954] client: found existing peer: 435ACF87-6352-482F-B5FA-1EDD8A011FA8:8
,2016-03-14 23:46:21.804 ThaliTest[1373:2209954] multipeer manager: restart client
,2016-03-14 23:46:21.821 ThaliTest[1373:2209954] client: found existing peer: 435ACF87-6352-482F-B5FA-1EDD8A011FA8:8
,2016-03-14 23:46:41.804 ThaliTest[1373:2209954] multipeer manager: restart client
,2016-03-14 23:46:41.821 ThaliTest[1373:2209954] client: found existing peer: 435ACF87-6352-482F-B5FA-1EDD8A011FA8:8
,2016-03-14 23:47:01.804 ThaliTest[1373:2209954] multipeer manager: restart client
,2016-03-14 23:47:01.820 ThaliTest[1373:2209954] client: found existing peer: 435ACF87-6352-482F-B5FA-1EDD8A011FA8:8
,2016-03-14 23:47:21.804 ThaliTest[1373:2209954] multipeer manager: restart client
,2016-03-14 23:47:21.821 ThaliTest[1373:2209954] client: found existing peer: 435ACF87-6352-482F-B5FA-1EDD8A011FA8:8
,2016-03-14 23:47:41.804 ThaliTest[1373:2209954] multipeer manager: restart client
,2016-03-14 23:47:41.823 ThaliTest[1373:2209954] client: found existing peer: 435ACF87-6352-482F-B5FA-1EDD8A011FA8:8
,2016-03-14 23:48:01.803 ThaliTest[1373:2209954] multipeer manager: restart client
,2016-03-14 23:48:01.822 ThaliTest[1373:2209954] client: found existing peer: 435ACF87-6352-482F-B5FA-1EDD8A011FA8:8
,2016-03-14 23:48:21.804 ThaliTest[1373:2209954] multipeer manager: restart client
,2016-03-14 23:48:21.822 ThaliTest[1373:2209954] client: found existing peer: 435ACF87-6352-482F-B5FA-1EDD8A011FA8:8
,2016-03-14 23:48:41.804 ThaliTest[1373:2209954] multipeer manager: restart client
,2016-03-14 23:48:41.821 ThaliTest[1373:2209954] client: found existing peer: 435ACF87-6352-482F-B5FA-1EDD8A011FA8:8
,2016-03-14 23:49:01.804 ThaliTest[1373:2209954] multipeer manager: restart client
,2016-03-14 23:49:01.824 ThaliTest[1373:2209954] client: found existing peer: 435ACF87-6352-482F-B5FA-1EDD8A011FA8:8
,2016-03-14 23:49:21.804 ThaliTest[1373:2209954] multipeer manager: restart client
,2016-03-14 23:49:21.819 ThaliTest[1373:2209954] client: found existing peer: 435ACF87-6352-482F-B5FA-1EDD8A011FA8:8
,2016-03-14 23:49:41.804 ThaliTest[1373:2209954] multipeer manager: restart client
,2016-03-14 23:49:41.820 ThaliTest[1373:2209954] client: found existing peer: 435ACF87-6352-482F-B5FA-1EDD8A011FA8:8
,2016-03-14 23:50:01.803 ThaliTest[1373:2209954] multipeer manager: restart client
,2016-03-14 23:50:01.820 ThaliTest[1373:2209954] client: found existing peer: 435ACF87-6352-482F-B5FA-1EDD8A011FA8:8
,2016-03-14 23:50:21.804 ThaliTest[1373:2209954] multipeer manager: restart client
,2016-03-14 23:50:21.821 ThaliTest[1373:2209954] client: found existing peer: 435ACF87-6352-482F-B5FA-1EDD8A011FA8:8
,2016-03-14 23:50:41.804 ThaliTest[1373:2209954] multipeer manager: restart client
,2016-03-14 23:51:00.017 ThaliTest[1373:2209954] client: found existing peer: 435ACF87-6352-482F-B5FA-1EDD8A011FA8:8
,2016-03-14 23:51:01.803 ThaliTest[1373:2209954] multipeer manager: restart client
,2016-03-14 23:51:21.803 ThaliTest[1373:2209954] multipeer manager: restart client
,2016-03-14 23:51:21.819 ThaliTest[1373:2209954] client: found existing peer: 435ACF87-6352-482F-B5FA-1EDD8A011FA8:8
,2016-03-14 23:51:41.804 ThaliTest[1373:2209954] multipeer manager: restart client
,2016-03-14 23:51:41.822 ThaliTest[1373:2209954] client: found existing peer: 435ACF87-6352-482F-B5FA-1EDD8A011FA8:8
,2016-03-14 23:52:01.804 ThaliTest[1373:2209954] multipeer manager: restart client
,2016-03-14 23:52:21.803 ThaliTest[1373:2209954] multipeer manager: restart client
,2016-03-14 23:52:21.820 ThaliTest[1373:2209954] client: found existing peer: 435ACF87-6352-482F-B5FA-1EDD8A011FA8:8
,2016-03-14 23:52:41.804 ThaliTest[1373:2209954] multipeer manager: restart client
,2016-03-14 23:52:41.822 ThaliTest[1373:2209954] client: found existing peer: 435ACF87-6352-482F-B5FA-1EDD8A011FA8:8
,2016-03-14 23:53:01.804 ThaliTest[1373:2209954] multipeer manager: restart client
,2016-03-14 23:53:21.804 ThaliTest[1373:2209954] multipeer manager: restart client
,2016-03-14 23:53:21.823 ThaliTest[1373:2209954] client: found existing peer: 435ACF87-6352-482F-B5FA-1EDD8A011FA8:8
,2016-03-14 23:53:41.804 ThaliTest[1373:2209954] multipeer manager: restart client
,2016-03-14 23:53:41.820 ThaliTest[1373:2209954] client: found existing peer: 435ACF87-6352-482F-B5FA-1EDD8A011FA8:8
,2016-03-14 23:54:01.804 ThaliTest[1373:2209954] multipeer manager: restart client
,2016-03-14 23:54:01.821 ThaliTest[1373:2209954] client: found existing peer: 435ACF87-6352-482F-B5FA-1EDD8A011FA8:8
,2016-03-14 23:54:21.804 ThaliTest[1373:2209954] multipeer manager: restart client
,2016-03-14 23:54:21.821 ThaliTest[1373:2209954] client: found existing peer: 435ACF87-6352-482F-B5FA-1EDD8A011FA8:8
,2016-03-14 23:54:41.803 ThaliTest[1373:2209954] multipeer manager: restart client
,2016-03-14 23:54:41.821 ThaliTest[1373:2209954] client: found existing peer: 435ACF87-6352-482F-B5FA-1EDD8A011FA8:8
,2016-03-14 23:55:01.803 ThaliTest[1373:2209954] multipeer manager: restart client
,2016-03-14 23:55:01.821 ThaliTest[1373:2209954] client: found existing peer: 435ACF87-6352-482F-B5FA-1EDD8A011FA8:8
,2016-03-14 23:55:21.804 ThaliTest[1373:2209954] multipeer manager: restart client
,2016-03-14 23:55:21.821 ThaliTest[1373:2209954] client: found existing peer: 435ACF87-6352-482F-B5FA-1EDD8A011FA8:8
,2016-03-14 23:55:41.804 ThaliTest[1373:2209954] multipeer manager: restart client
,2016-03-14 23:55:41.821 ThaliTest[1373:2209954] client: found existing peer: 435ACF87-6352-482F-B5FA-1EDD8A011FA8:8
,2016-03-14 23:56:01.804 ThaliTest[1373:2209954] multipeer manager: restart client
,2016-03-14 23:56:01.821 ThaliTest[1373:2209954] client: found existing peer: 435ACF87-6352-482F-B5FA-1EDD8A011FA8:8
,2016-03-14 23:56:21.804 ThaliTest[1373:2209954] multipeer manager: restart client
,2016-03-14 23:56:21.820 ThaliTest[1373:2209954] client: found existing peer: 435ACF87-6352-482F-B5FA-1EDD8A011FA8:8
,2016-03-14 23:56:41.804 ThaliTest[1373:2209954] multipeer manager: restart client
,2016-03-14 23:56:41.822 ThaliTest[1373:2209954] client: found existing peer: 435ACF87-6352-482F-B5FA-1EDD8A011FA8:8
,2016-03-14 23:57:01.803 ThaliTest[1373:2209954] multipeer manager: restart client
,2016-03-14 23:57:01.821 ThaliTest[1373:2209954] client: found existing peer: 435ACF87-6352-482F-B5FA-1EDD8A011FA8:8
,2016-03-14 23:57:21.803 ThaliTest[1373:2209954] multipeer manager: restart client
,2016-03-14 23:57:21.820 ThaliTest[1373:2209954] client: found existing peer: 435ACF87-6352-482F-B5FA-1EDD8A011FA8:8
,2016-03-14 23:57:41.804 ThaliTest[1373:2209954] multipeer manager: restart client
,2016-03-14 23:57:41.823 ThaliTest[1373:2209954] client: found existing peer: 435ACF87-6352-482F-B5FA-1EDD8A011FA8:8
,2016-03-14 23:58:01.803 ThaliTest[1373:2209954] multipeer manager: restart client
,2016-03-14 23:58:01.819 ThaliTest[1373:2209954] client: found existing peer: 435ACF87-6352-482F-B5FA-1EDD8A011FA8:8
,2016-03-14 23:58:21.804 ThaliTest[1373:2209954] multipeer manager: restart client
,2016-03-14 23:58:21.821 ThaliTest[1373:2209954] client: found existing peer: 435ACF87-6352-482F-B5FA-1EDD8A011FA8:8
,2016-03-14 23:58:41.803 ThaliTest[1373:2209954] multipeer manager: restart client
,2016-03-14 23:58:41.821 ThaliTest[1373:2209954] client: found existing peer: 435ACF87-6352-482F-B5FA-1EDD8A011FA8:8

```
