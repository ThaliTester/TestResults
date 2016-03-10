#### Test 61362366b6c9a6f_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/61362366b6c9a6f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/11B24C26-AEAA-43B6-9157-DA81522C7E3C/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/11B24C26-AEAA-43B6-9157-DA81522C7E3C/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/61362366b6c9a6f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/61362366b6c9a6f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/446F4F58-5AA4-403F-A64F-9691807AFF20/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50535"
,(lldb)     command script import "/tmp/11B24C26-AEAA-43B6-9157-DA81522C7E3C/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-10 09:36:37.589 ThaliTest[1016:1575452] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/694D62FD-A31F-45AE-9604-D001848F6D25/Library/Cookies/Cookies.binarycookies
,2016-03-10 09:36:37.937 ThaliTest[1016:1575452] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-10 09:36:37.939 ThaliTest[1016:1575452] Multi-tasking -> Device: YES, App: YES
,2016-03-10 09:36:37.962 ThaliTest[1016:1575452] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-10 09:36:39.844 ThaliTest[1016:1575452] Using UIWebView
,2016-03-10 09:36:39.854 ThaliTest[1016:1575452] [CDVTimer][handleopenurl] 0.529945ms
,2016-03-10 09:36:39.862 ThaliTest[1016:1575452] [CDVTimer][intentandnavigationfilter] 7.216990ms
2016-03-10 09:36:39.863 ThaliTest[1016:1575452] [CDVTimer][gesturehandler] 0.368953ms
2016-03-10 09:36:39.863 ThaliTest[1016:1575452] [CDVTimer][TotalPluginS,tartup] 9.774983ms
,2016-03-10 09:36:46.826 ThaliTest[1016:1575452] Resetting plugins due to page load.
,2016-03-10 09:36:50.267 ThaliTest[1016:1575452] Finished load of: file:///var/mobile/Containers/Bundle/Application/446F4F58-5AA4-403F-A64F-9691807AFF20/ThaliTest.app/www/index.html
,2016-03-10 09:36:50.486 ThaliTest[1016:1575452] JXcore Cordova plugin initializing
,2016-03-10 09:36:50.487 ThaliTest[1016:1575663] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,INFO testUtils Toggling radios to: true

,Unit Test app is loaded

,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/446F4F58-5AA4-403F-A64F-9691807AFF20/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/446F4F58-5AA4-403F-A64F-9691807AFF20/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/446F4F58-5AA4-403F-A64F-9691807AFF20/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/446F4F58-5AA4-403F-A64F-9691807AFF20/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-10 09:37:02.850 ThaliTest[1016:1575663] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-10 09:37:02.850 ThaliTest[1016:1575663] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-10 09:37:02.850 ThaliTest[1016:1575663] jxcore: didRegisterToNative networkChanged
INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

,2016-03-10 09:37:02.852 ThaliTest[1016:1575663] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/446F4F58-5AA4-403F-A64F-9691807AFF20/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/446F4F58-5AA4-403F-A64F-9691807AFF20/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/446F4F58-5AA4-403F-A64F-9691807AFF20/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/446F4F58-5AA4-403F-A64F-9691807AFF20/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/446F4F58-5AA4-403F-A64F-9691807AFF20/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/446F4F58-5AA4-403F-A64F-9691807AFF20/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/446F4F58-5AA4-403F-A64F-9691807AFF20/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/446F4F58-5AA4-403F-A64F-9691807AFF20/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/446F4F58-5AA4-403F-A64F-9691807AFF20/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/446F4F58-5AA4-403F-A64F-9691807AFF20/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Reconnected to the test server

,TAP version 13

,# setup

,# 1. multiplex can send data

,# teardown

,ok 1 String should be length:200

,# setup

,# 2. enqueue and run in order

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

,# 3. enqueueAtTop and run backwards

,# teardown

,ok 11 thirdPromise - first to run

,ok 12 thirdPromise - in resolve

,ok 13 secondPromise - second to run

,ok 14 secondPromise - in catch

,ok 15 firstPromise - third to run

,ok 16 firstPromise - in then

,ok 17 testing promises

,# setup

,# 4. mix enqueue and enqueueAtTop

,# teardown

,ok 18 fourth

,ok 19 fourth

,ok 20 second

,ok 21 secondPromise - in then

,ok 22 first

,ok 23 firstPromise - in catch

,ok 24 third

,ok 25 thirdPromise - in then

,ok 26 testingPromises

,# setup

,# 5. queues handled independently

,# teardown

,ok 27 all short operations completed before the long resolves

,# setup

,# 6. basic

,# teardown

,ok 28 sane

,# setup

,# 7. another

,# teardown

,ok 29 sane

,# setup

,# 8. #startListeningForAdvertisements should fail if start not called

,# teardown

,ok 30 specific error should be returned

,# setup

,ok 31 error should be null

,ok 32 error should be null

,# 9. #startUpdateAdvertisingAndListening should fail if start not called

,# teardown

,ok 33 specific error should be returned

,# setup

,ok 34 error should be null

,ok 35 error should be null

,# 10. should be able to call #stopListeningForAdvertisements many times

,# teardown

,ok 36 error should be null

,ok 37 error should be null

,ok 38 error should be null

,ok 39 error should be null

,# setup

,ok 40 error should be null

,ok 41 error should be null

,# 11. should be able to call #startListeningForAdvertisements many times

,# teardown

,ok 42 error should be null

,ok 43 error should be null

,ok 44 error should be null

,ok 45 error should be null

,# setup

,INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).

,ok 46 error should be null

,ok 47 error should be null

,# 12. should be able to call #startUpdateAdvertisingAndListening many times

,# teardown

,ok 48 error should be null

,ok 49 error should be null

,ok 50 error should be null

,ok 51 error should be null

,# setup

,INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).

,ok 52 error should be null

,ok 53 error should be null

,# 13. should be able to call #stopAdvertisingAndListening many times

,# teardown

,ok 54 error should be null

,ok 55 error should be null

,ok 56 error should be null

,ok 57 error should be null

,# setup

,ok 58 error should be null

,ok 59 error should be null

,# 14. #start should fail if called twice in a row

,# teardown

,ok 60 first call should succeed

,ok 61 first call should succeed

,ok 62 specific error should be returned

,# setup

,ok 63 error should be null

,ok 64 error should be null

,# 15. does not emit duplicate discoveryAdvertisingStateUpdate

,# teardown

,ok 65 called only once

,ok 66 discovery state matches

,ok 67 advertising state matches

,# setup

,INFO thaliMobile Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}

,INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).

,INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).

,ok 68 error should be null

,ok 69 error should be null

,# 16. does not send duplicate availability changes

,# teardown

,ok 70 should be called once

,ok 71 should not have been called more than once

,# setup

,ok 72 error should be null

,ok 73 error should be null

,# 17. can get the network status

,# teardown

,ok 74 network status should have certain non-empty properties

,# setup

,ok 75 error should be null

,ok 76 error should be null

,# 18. wifi peer is marked unavailable if announcements stop

,# teardown

,ok 77 host address should match

,ok 78 port should match

,ok 79 host address should be null

,ok 80 port should should be null

,# setup

,INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).

,ok 81 error should be null

ok 82 error should be null

,# 19. Can call start/stopListeningForAdvertisements

,# teardown

,2016-03-10 09:40:29.658 ThaliTest[1016:1575663] jxcore: startListeningForAdvertisements
,2016-03-10 09:40:29.663 ThaliTest[1016:1575663] multipeer manager: start client restart timer: 0x14de0c50
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,
,2016-03-10 09:40:29.667 ThaliTest[1016:1575663] jxcore: startListeningForAdvertisements: success
,ok 83 Can call startListeningForAdvertisements without error

,2016-03-10 09:40:29.672 ThaliTest[1016:1575663] jxcore: stopListeningForAdvertisements
,2016-03-10 09:40:29.675 ThaliTest[1016:1575663] multipeer manager: stop client timer
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,
,2016-03-10 09:40:29.679 ThaliTest[1016:1575663] jxcore: stopListeningForAdvertisements: success
,ok 84 Can call stopListeningForAdvertisements without error
,
,# setup

,2016-03-10 09:40:29.792 ThaliTest[1016:1575663] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}

,2016-03-10 09:40:29.795 ThaliTest[1016:1575663] jxcore: stopListeningForAdvertisements: success
,ok 85 Should be able to call stopListeningForAdvertisments in teardown

,2016-03-10 09:40:29.799 ThaliTest[1016:1575663] jxcore: stopAdvertisingAndListening
,2016-03-10 09:40:29.800 ThaliTest[1016:1575663] THEMultipeerManager stopping peer
,2016-03-10 09:40:29.801 ThaliTest[1016:1575663] jxcore: stopAdvertisingAndListening: success
,ok 86 Should be able to call stopAdvertisingAndListening in teardown

,# 20. Calling startListeningForAdvertisements twice is NOT an error

,# teardown

,2016-03-10 09:40:30.194 ThaliTest[1016:1575663] jxcore: startListeningForAdvertisements
2016-03-10 09:40:30.195 ThaliTest[1016:1575663] multipeer manager: start client restart timer: 0x14de0c50
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}

,2016-03-10 09:40:30.197 ThaliTest[1016:1575663] jxcore: startListeningForAdvertisements: success
,ok 87 Can call startListeningForAdvertisements without error

,2016-03-10 09:40:30.200 ThaliTest[1016:1575663] jxcore: startListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}

2016-03-10 09:40:30.203 ThaliTest[1016:1575663] jxcore: startListeningForAdvertisements: success
ok 88 Can call startListeningForAdvertisements twice without error

,# setup

,2016-03-10 09:40:30.643 ThaliTest[1016:1575663] jxcore: stopListeningForAdvertisements
2016-03-10 09:40:30.644 ThaliTest[1016:1575663] multipeer manager: stop client timer
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertising,Active":false,"discoveryActive":false}

2016-03-10 09:40:30.646 ThaliTest[1016:1575663] jxcore: stopListeningForAdvertisements: success
ok 89 Should be able to call stopListeningForAdvertisments in teardown

,2016-03-10 09:40:30.649 ThaliTest[1016:1575663] jxcore: stopAdvertisingAndListening
2016-03-10 09:40:30.651 ThaliTest[1016:1575663] THEMultipeerManager stopping peer
2016-03-10 09:40:30.651 ThaliTest[1016:1575663] jxcore: stopAdvertisingAndListening: success
ok 90 Should be able to call stopAdvertisingAndListening in teardown

,# 21. Can call start/stopUpdateAdvertisingAndListening

,# teardown

,2016-03-10 09:40:33.240 ThaliTest[1016:1575663] jxcore: startUpdateAdvertisingAndListening
2016-03-10 09:40:33.241 ThaliTest[1016:1575663] server: starting EB1717B1-EA19-4A83-A99B-88282DEBD7B6:1
,2016-03-10 09:40:33.243 ThaliTest[1016:1575663] multipeer manager: start client restart timer: 0x14de0c50
,2016-03-10 09:40:33.244 ThaliTest[1016:1575663] THEMultipeerManager initialized peer EB1717B1-EA19-4A83-A99B-88282DEBD7B6:1
2016-03-10 09:40:33.244 ThaliTest[1016:1575663] jxcore: startUpdateAdvertisingAndListening: success
,ok 91 Can call startUpdateAdvertisingAndListening without error

2016-03-10 09:40:33.248 ThaliTest[1016:1575663] jxcore: stopAdvertisingAndListening
2016-03-10 09:40:33.248 ThaliTest[1016:1575663] THEMultipeerManager stopping peer
,2016-03-10 09:40:33.249 ThaliTest[1016:1575663] multipeer manager: stop client timer
2016-03-10 09:40:33.250 ThaliTest[1016:1575663] jxcore: stopAdvertisingAndListening: success
,ok 92 Can call stopAdvertisingAndListening without error

# setup

,2016-03-10 09:40:33.556 ThaliTest[1016:1575663] jxcore: stopListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}

,2016-03-10 09:40:33.557 ThaliTest[1016:1575663] jxcore: stopListeningForAdvertisements: success
,ok 93 Should be able to call stopListeningForAdvertisments in teardown

,2016-03-10 09:40:33.560 ThaliTest[1016:1575663] jxcore: stopAdvertisingAndListening
,2016-03-10 09:40:33.560 ThaliTest[1016:1575663] THEMultipeerManager stopping peer
,2016-03-10 09:40:33.561 ThaliTest[1016:1575663] jxcore: stopAdvertisingAndListening: success
,ok 94 Should be able to call stopAdvertisingAndListening in teardown

,# 22. Calling startUpdateAdvertisingAndListening twice is NOT an error

,# teardown

,2016-03-10 09:40:33.813 ThaliTest[1016:1575663] jxcore: startUpdateAdvertisingAndListening
2016-03-10 09:40:33.814 ThaliTest[1016:1575663] server: starting EB1717B1-EA19-4A83-A99B-88282DEBD7B6:2
2016-03-10 09:40:33.815 ThaliTest[1016:1575663] multipeer m,anager: start client restart timer: 0x14de0c50
2016-03-10 09:40:33.815 ThaliTest[1016:1575663] THEMultipeerManager initialized peer EB1717B1-EA19-4A83-A99B-88282DEBD7B6:2
2016-03-10 09:40:33.815 ThaliTest[1016:1575663] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 95 Can call startUpdateAdvertisingAndListening without error

,2016-03-10 09:40:33.818 ThaliTest[1016:1575663] jxcore: startUpdateAdvertisingAndListening
2016-03-10 09:40:33.819 ThaliTest[1016:1575663] THEMultipeerManager stopping peer
2016-03-10 09:40:33.819 ThaliTest[1016:1575663] multipeer manager: stop client ti,mer
2016-03-10 09:40:33.820 ThaliTest[1016:1575663] server: starting EB1717B1-EA19-4A83-A99B-88282DEBD7B6:3
2016-03-10 09:40:33.821 ThaliTest[1016:1575663] multipeer manager: start client restart timer: 0x14de0c50
2016-03-10 09:40:33.821 ThaliTest[1016:,1575663] THEMultipeerManager initialized peer EB1717B1-EA19-4A83-A99B-88282DEBD7B6:3
2016-03-10 09:40:33.821 ThaliTest[1016:1575663] jxcore: startUpdateAdvertisingAndListening: success
ok 96 Can call startUpdateAdvertisingAndListening twice without error,

# setup

,2016-03-10 09:40:34.087 ThaliTest[1016:1575663] jxcore: stopListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}

,2016-03-10 09:40:34.089 ThaliTest[1016:1575663] jxcore: stopListeningForAdvertisements: success
,ok 97 Should be able to call stopListeningForAdvertisments in teardown

,2016-03-10 09:40:34.092 ThaliTest[1016:1575663] jxcore: stopAdvertisingAndListening
2016-03-10 09:40:34.093 ThaliTest[1016:1575663] THEMultipeerManager stopping peer
2016-03-10 09:40:34.093 ThaliTest[1016:1575663] multipeer manager: stop client timer
20,16-03-10 09:40:34.094 ThaliTest[1016:1575663] jxcore: stopAdvertisingAndListening: success
ok 98 Should be able to call stopAdvertisingAndListening in teardown

,# 23. peerAvailabilityChange is called

,# teardown

,2016-03-10 09:40:35.135 ThaliTest[1016:1575663] jxcore: startUpdateAdvertisingAndListening
2016-03-10 09:40:35.135 ThaliTest[1016:1575663] server: starting EB1717B1-EA19-4A83-A99B-88282DEBD7B6:4
2016-03-10 09:40:35.136 ThaliTest[1016:1575663] multipeer m,anager: start client restart timer: 0x14de0c50
2016-03-10 09:40:35.136 ThaliTest[1016:1575663] THEMultipeerManager initialized peer EB1717B1-EA19-4A83-A99B-88282DEBD7B6:4
2016-03-10 09:40:35.136 ThaliTest[1016:1575663] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 99 Can call startUpdateAdvertisingAndListeningwithout error

2016-03-10 09:40:35.138 ThaliTest[1016:1575663] jxcore: startListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingA,ctive":true,"discoveryActive":true}

2016-03-10 09:40:35.140 ThaliTest[1016:1575663] jxcore: startListeningForAdvertisements: success
ok 100 Can call startListeningForAdvertisements without error

,2016-03-10 09:40:38.392 ThaliTest[1016:1575452] client: found new peer: DDDB0EC9-C034-47C5-8433-6E846CC55A9A:4
,ok 101 peers must be an array

,ok 102 peers must not be zero-length

,ok 103 peer must have peerIdentifier

,ok 104 peerIdentifier must be a string

,ok 105 peer must have peerAvailable

,ok 106 peer must have pleaseConnect

,# setup

,2016-03-10 09:40:38.503 ThaliTest[1016:1575663] jxcore: stopListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}

,2016-03-10 09:40:38.505 ThaliTest[1016:1575663] jxcore: stopListeningForAdvertisements: success
ok 107 Should be able to call stopListeningForAdvertisments in teardown

,2016-03-10 09:40:38.507 ThaliTest[1016:1575663] jxcore: stopAdvertisingAndListening
2016-03-10 09:40:38.508 ThaliTest[1016:1575663] THEMultipeerManager stopping peer
,2016-03-10 09:40:38.508 ThaliTest[1016:1575663] multipeer manager: stop client timer
2016-03-10 09:40:38.510 ThaliTest[1016:1575663] jxcore: stopAdvertisingAndListening: success
ok 108 Should be able to call stopAdvertisingAndListening in teardown

,# 24. Can connect to a remote peer

,# teardown

,2016-03-10 09:40:38.906 ThaliTest[1016:1575663] jxcore: startUpdateAdvertisingAndListening
2016-03-10 09:40:38.907 ThaliTest[1016:1575663] server: starting EB1717B1-EA19-4A83-A99B-88282DEBD7B6:5
2016-03-10 09:40:38.907 ThaliTest[1016:1575663] multipeer m,anager: start client restart timer: 0x14de0c50
2016-03-10 09:40:38.908 ThaliTest[1016:1575663] THEMultipeerManager initialized peer EB1717B1-EA19-4A83-A99B-88282DEBD7B6:5
2016-03-10 09:40:38.908 ThaliTest[1016:1575663] jxcore: startUpdateAdvertisingAndListening: success
,ok 109 Can call startUpdateAdvertisingAndListening without error

,2016-03-10 09:40:38.911 ThaliTest[1016:1575663] jxcore: startListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}

,2016-03-10 09:40:38.914 ThaliTest[1016:1575663] jxcore: startListeningForAdvertisements: success
,ok 110 Can call startListeningForAdvertisements without error

,2016-03-10 09:40:39.630 ThaliTest[1016:1575452] client: found new peer: DDDB0EC9-C034-47C5-8433-6E846CC55A9A:4
,2016-03-10 09:40:39.633 ThaliTest[1016:1575663] jxcore: connect DDDB0EC9-C034-47C5-8433-6E846CC55A9A:4
,2016-03-10 09:40:39.634 ThaliTest[1016:1575663] client session: connect
2016-03-10 09:40:39.634 ThaliTest[1016:1575663] client session: stateChange:0->1 DDDB0EC9-C034-47C5-8433-6E846CC55A9A:4
,2016-03-10 09:40:47.611 ThaliTest[1016:1575452] multipeer session: reset timer
,2016-03-10 09:40:47.612 ThaliTest[1016:1575452] server: rejecting invitation from DDDB0EC9-C034-47C5-8433-6E846CC55A9A due to previous generation (EB1717B1-EA19-4A83-A99B-88282DEBD7B6:5 != EB1717B1-EA19-4A83-A99B-88282DEBD7B6:4)
,2016-03-10 09:40:47.619 ThaliTest[1016:1576723] client session: not connected DDDB0EC9-C034-47C5-8433-6E846CC55A9A:4
,2016-03-10 09:40:47.620 ThaliTest[1016:1576723] client session: onLinkFailure: DDDB0EC9-C034-47C5-8433-6E846CC55A9A
2016-03-10 09:40:47.622 ThaliTest[1016:1576723] client session: disconnect
,2016-03-10 09:40:47.622 ThaliTest[1016:1576723] client session: stateChange:1->0 DDDB0EC9-C034-47C5-8433-6E846CC55A9A:4
2016-03-10 09:40:47.625 ThaliTest[1016:1576723] client session: fireConnectCallback: DDDB0EC9-C034-47C5-8433-6E846CC55A9A
2016-03-10 09:40:47.625 ThaliTest[1016:1576723] jxcore: connect: fail: Peer disconnected
,not ok 111 Error from connect: Peer disconnected

,  ---

,    operator: fail

,  ...

,# setup

,2016-03-10 09:40:58.909 ThaliTest[1016:1575452] multipeer manager: restart client
,2016-03-10 09:40:58.926 ThaliTest[1016:1575452] client: found updated peer: DDDB0EC9-C034-47C5-8433-6E846CC55A9A:5
,2016-03-10 09:41:18.909 ThaliTest[1016:1575452] multipeer manager: restart client
,2016-03-10 09:41:18.926 ThaliTest[1016:1575452] client: found existing peer: DDDB0EC9-C034-47C5-8433-6E846CC55A9A:5
,2016-03-10 09:41:38.909 ThaliTest[1016:1575452] multipeer manager: restart client
,2016-03-10 09:41:38.925 ThaliTest[1016:1575452] client: found existing peer: DDDB0EC9-C034-47C5-8433-6E846CC55A9A:5
,2016-03-10 09:41:58.909 ThaliTest[1016:1575452] multipeer manager: restart client
,2016-03-10 09:41:58.925 ThaliTest[1016:1575452] client: found existing peer: DDDB0EC9-C034-47C5-8433-6E846CC55A9A:5
,2016-03-10 09:42:18.909 ThaliTest[1016:1575452] multipeer manager: restart client
,2016-03-10 09:42:18.928 ThaliTest[1016:1575452] client: found existing peer: DDDB0EC9-C034-47C5-8433-6E846CC55A9A:5
,2016-03-10 09:42:38.909 ThaliTest[1016:1575452] multipeer manager: restart client
,2016-03-10 09:42:38.928 ThaliTest[1016:1575452] client: found existing peer: DDDB0EC9-C034-47C5-8433-6E846CC55A9A:5
,2016-03-10 09:42:58.909 ThaliTest[1016:1575452] multipeer manager: restart client
,2016-03-10 09:42:58.927 ThaliTest[1016:1575452] client: found existing peer: DDDB0EC9-C034-47C5-8433-6E846CC55A9A:5
,2016-03-10 09:43:18.898 ThaliTest[1016:1575452] multipeer manager: restart client
,2016-03-10 09:43:18.916 ThaliTest[1016:1575452] client: found existing peer: DDDB0EC9-C034-47C5-8433-6E846CC55A9A:5
,2016-03-10 09:43:38.899 ThaliTest[1016:1575452] multipeer manager: restart client
,2016-03-10 09:43:38.917 ThaliTest[1016:1575452] client: found existing peer: DDDB0EC9-C034-47C5-8433-6E846CC55A9A:5
,2016-03-10 09:43:58.899 ThaliTest[1016:1575452] multipeer manager: restart client
,2016-03-10 09:43:58.915 ThaliTest[1016:1575452] client: found existing peer: DDDB0EC9-C034-47C5-8433-6E846CC55A9A:5
,2016-03-10 09:44:18.899 ThaliTest[1016:1575452] multipeer manager: restart client
,2016-03-10 09:44:18.917 ThaliTest[1016:1575452] client: found existing peer: DDDB0EC9-C034-47C5-8433-6E846CC55A9A:5
,2016-03-10 09:44:38.899 ThaliTest[1016:1575452] multipeer manager: restart client
,2016-03-10 09:44:38.919 ThaliTest[1016:1575452] client: found existing peer: DDDB0EC9-C034-47C5-8433-6E846CC55A9A:5
,2016-03-10 09:44:58.899 ThaliTest[1016:1575452] multipeer manager: restart client
,2016-03-10 09:44:58.917 ThaliTest[1016:1575452] client: found existing peer: DDDB0EC9-C034-47C5-8433-6E846CC55A9A:5
,2016-03-10 09:45:18.898 ThaliTest[1016:1575452] multipeer manager: restart client
,2016-03-10 09:45:18.917 ThaliTest[1016:1575452] client: found existing peer: DDDB0EC9-C034-47C5-8433-6E846CC55A9A:5
,2016-03-10 09:45:38.899 ThaliTest[1016:1575452] multipeer manager: restart client
,2016-03-10 09:45:38.916 ThaliTest[1016:1575452] client: found existing peer: DDDB0EC9-C034-47C5-8433-6E846CC55A9A:5
,2016-03-10 09:45:58.899 ThaliTest[1016:1575452] multipeer manager: restart client
,2016-03-10 09:45:58.918 ThaliTest[1016:1575452] client: found existing peer: DDDB0EC9-C034-47C5-8433-6E846CC55A9A:5
,2016-03-10 09:46:18.899 ThaliTest[1016:1575452] multipeer manager: restart client
,2016-03-10 09:46:18.916 ThaliTest[1016:1575452] client: found existing peer: DDDB0EC9-C034-47C5-8433-6E846CC55A9A:5
,2016-03-10 09:46:38.899 ThaliTest[1016:1575452] multipeer manager: restart client
,2016-03-10 09:46:38.916 ThaliTest[1016:1575452] client: found existing peer: DDDB0EC9-C034-47C5-8433-6E846CC55A9A:5
,2016-03-10 09:46:58.899 ThaliTest[1016:1575452] multipeer manager: restart client
,2016-03-10 09:46:58.917 ThaliTest[1016:1575452] client: found existing peer: DDDB0EC9-C034-47C5-8433-6E846CC55A9A:5
,2016-03-10 09:47:18.899 ThaliTest[1016:1575452] multipeer manager: restart client
,2016-03-10 09:47:38.899 ThaliTest[1016:1575452] multipeer manager: restart client
,2016-03-10 09:47:38.909 ThaliTest[1016:1575452] client: found existing peer: DDDB0EC9-C034-47C5-8433-6E846CC55A9A:5
,2016-03-10 09:47:58.898 ThaliTest[1016:1575452] multipeer manager: restart client
,2016-03-10 09:47:58.910 ThaliTest[1016:1575452] client: found existing peer: DDDB0EC9-C034-47C5-8433-6E846CC55A9A:5
,2016-03-10 09:48:18.899 ThaliTest[1016:1575452] multipeer manager: restart client
,2016-03-10 09:48:18.911 ThaliTest[1016:1575452] client: found existing peer: DDDB0EC9-C034-47C5-8433-6E846CC55A9A:5
,2016-03-10 09:48:38.899 ThaliTest[1016:1575452] multipeer manager: restart client
,2016-03-10 09:48:58.899 ThaliTest[1016:1575452] multipeer manager: restart client
,2016-03-10 09:48:58.909 ThaliTest[1016:1575452] client: found existing peer: DDDB0EC9-C034-47C5-8433-6E846CC55A9A:5
,2016-03-10 09:49:18.898 ThaliTest[1016:1575452] multipeer manager: restart client
,2016-03-10 09:49:18.909 ThaliTest[1016:1575452] client: found existing peer: DDDB0EC9-C034-47C5-8433-6E846CC55A9A:5
,2016-03-10 09:49:38.899 ThaliTest[1016:1575452] multipeer manager: restart client
,2016-03-10 09:49:38.911 ThaliTest[1016:1575452] client: found existing peer: DDDB0EC9-C034-47C5-8433-6E846CC55A9A:5
,2016-03-10 09:49:58.899 ThaliTest[1016:1575452] multipeer manager: restart client
,2016-03-10 09:49:58.911 ThaliTest[1016:1575452] client: found existing peer: DDDB0EC9-C034-47C5-8433-6E846CC55A9A:5
,2016-03-10 09:50:18.899 ThaliTest[1016:1575452] multipeer manager: restart client
,2016-03-10 09:50:18.912 ThaliTest[1016:1575452] client: found existing peer: DDDB0EC9-C034-47C5-8433-6E846CC55A9A:5
,2016-03-10 09:50:38.899 ThaliTest[1016:1575452] multipeer manager: restart client
,2016-03-10 09:50:38.913 ThaliTest[1016:1575452] client: found existing peer: DDDB0EC9-C034-47C5-8433-6E846CC55A9A:5
,2016-03-10 09:50:58.899 ThaliTest[1016:1575452] multipeer manager: restart client
,2016-03-10 09:50:58.912 ThaliTest[1016:1575452] client: found existing peer: DDDB0EC9-C034-47C5-8433-6E846CC55A9A:5
,2016-03-10 09:51:18.898 ThaliTest[1016:1575452] multipeer manager: restart client
,2016-03-10 09:51:18.910 ThaliTest[1016:1575452] client: found existing peer: DDDB0EC9-C034-47C5-8433-6E846CC55A9A:5
,2016-03-10 09:51:38.899 ThaliTest[1016:1575452] multipeer manager: restart client
,2016-03-10 09:51:38.911 ThaliTest[1016:1575452] client: found existing peer: DDDB0EC9-C034-47C5-8433-6E846CC55A9A:5
,2016-03-10 09:51:58.899 ThaliTest[1016:1575452] multipeer manager: restart client
,2016-03-10 09:51:58.912 ThaliTest[1016:1575452] client: found existing peer: DDDB0EC9-C034-47C5-8433-6E846CC55A9A:5
,2016-03-10 09:52:18.899 ThaliTest[1016:1575452] multipeer manager: restart client
,2016-03-10 09:52:18.911 ThaliTest[1016:1575452] client: found existing peer: DDDB0EC9-C034-47C5-8433-6E846CC55A9A:5
,2016-03-10 09:52:38.899 ThaliTest[1016:1575452] multipeer manager: restart client
,2016-03-10 09:52:38.913 ThaliTest[1016:1575452] client: found existing peer: DDDB0EC9-C034-47C5-8433-6E846CC55A9A:5
,2016-03-10 09:52:58.899 ThaliTest[1016:1575452] multipeer manager: restart client
,2016-03-10 09:52:58.910 ThaliTest[1016:1575452] client: found existing peer: DDDB0EC9-C034-47C5-8433-6E846CC55A9A:5
,2016-03-10 09:53:18.899 ThaliTest[1016:1575452] multipeer manager: restart client
,2016-03-10 09:53:18.910 ThaliTest[1016:1575452] client: found existing peer: DDDB0EC9-C034-47C5-8433-6E846CC55A9A:5
,2016-03-10 09:53:38.898 ThaliTest[1016:1575452] multipeer manager: restart client
,2016-03-10 09:53:38.911 ThaliTest[1016:1575452] client: found existing peer: DDDB0EC9-C034-47C5-8433-6E846CC55A9A:5
,2016-03-10 09:53:58.899 ThaliTest[1016:1575452] multipeer manager: restart client
,2016-03-10 09:53:58.911 ThaliTest[1016:1575452] client: found existing peer: DDDB0EC9-C034-47C5-8433-6E846CC55A9A:5
,2016-03-10 09:54:18.899 ThaliTest[1016:1575452] multipeer manager: restart client
,2016-03-10 09:54:18.913 ThaliTest[1016:1575452] client: found existing peer: DDDB0EC9-C034-47C5-8433-6E846CC55A9A:5
,2016-03-10 09:54:38.899 ThaliTest[1016:1575452] multipeer manager: restart client
,2016-03-10 09:54:38.910 ThaliTest[1016:1575452] client: found existing peer: DDDB0EC9-C034-47C5-8433-6E846CC55A9A:5
,2016-03-10 09:54:58.899 ThaliTest[1016:1575452] multipeer manager: restart client
,2016-03-10 09:54:58.911 ThaliTest[1016:1575452] client: found existing peer: DDDB0EC9-C034-47C5-8433-6E846CC55A9A:5
,2016-03-10 09:55:18.899 ThaliTest[1016:1575452] multipeer manager: restart client
,2016-03-10 09:55:18.910 ThaliTest[1016:1575452] client: found existing peer: DDDB0EC9-C034-47C5-8433-6E846CC55A9A:5
,2016-03-10 09:55:38.899 ThaliTest[1016:1575452] multipeer manager: restart client
,2016-03-10 09:55:38.911 ThaliTest[1016:1575452] client: found existing peer: DDDB0EC9-C034-47C5-8433-6E846CC55A9A:5
,2016-03-10 09:55:58.899 ThaliTest[1016:1575452] multipeer manager: restart client
,2016-03-10 09:55:58.911 ThaliTest[1016:1575452] client: found existing peer: DDDB0EC9-C034-47C5-8433-6E846CC55A9A:5
,2016-03-10 09:56:18.899 ThaliTest[1016:1575452] multipeer manager: restart client
,2016-03-10 09:56:18.911 ThaliTest[1016:1575452] client: found existing peer: DDDB0EC9-C034-47C5-8433-6E846CC55A9A:5
,2016-03-10 09:56:38.899 ThaliTest[1016:1575452] multipeer manager: restart client
,2016-03-10 09:56:38.910 ThaliTest[1016:1575452] client: found existing peer: DDDB0EC9-C034-47C5-8433-6E846CC55A9A:5
,2016-03-10 09:56:58.898 ThaliTest[1016:1575452] multipeer manager: restart client
,2016-03-10 09:56:58.910 ThaliTest[1016:1575452] client: found existing peer: DDDB0EC9-C034-47C5-8433-6E846CC55A9A:5
,2016-03-10 09:57:18.899 ThaliTest[1016:1575452] multipeer manager: restart client
,2016-03-10 09:57:18.910 ThaliTest[1016:1575452] client: found existing peer: DDDB0EC9-C034-47C5-8433-6E846CC55A9A:5
,2016-03-10 09:57:38.899 ThaliTest[1016:1575452] multipeer manager: restart client
,2016-03-10 09:57:38.908 ThaliTest[1016:1575452] client: found existing peer: DDDB0EC9-C034-47C5-8433-6E846CC55A9A:5

```
