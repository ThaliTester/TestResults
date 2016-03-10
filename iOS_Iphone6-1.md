#### Test 613623667b1a8f4_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/613623667b1a8f4/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/27303833-A874-46B0-8C04-9C9E05F869B2/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/27303833-A874-46B0-8C04-9C9E05F869B2/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/613623667b1a8f4/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/613623667b1a8f4/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/6A6D8EBE-85B1-4189-87DC-EDC73AA66A29/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50995"
,(lldb)     command script import "/tmp/27303833-A874-46B0-8C04-9C9E05F869B2/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-10 16:22:42.486 ThaliTest[1053:1622463] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/968CF07C-A686-45D2-9108-3A3070F8F340/Library/Cookies/Cookies.binarycookies
,2016-03-10 16:22:42.861 ThaliTest[1053:1622463] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-10 16:22:42.863 ThaliTest[1053:1622463] Multi-tasking -> Device: YES, App: YES
,2016-03-10 16:22:42.889 ThaliTest[1053:1622463] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-10 16:22:44.781 ThaliTest[1053:1622463] Using UIWebView
,2016-03-10 16:22:44.788 ThaliTest[1053:1622463] [CDVTimer][handleopenurl] 0.432014ms
,2016-03-10 16:22:44.796 ThaliTest[1053:1622463] [CDVTimer][intentandnavigationfilter] 7.331014ms
2016-03-10 16:22:44.797 ThaliTest[1053:1622463] [CDVTimer][gesturehandler] 0.384986ms
2016-03-10 16:22:44.798 ThaliTest[1053:1622463] [CDVTimer][TotalPluginS,tartup] 9.893000ms
,2016-03-10 16:22:51.668 ThaliTest[1053:1622463] Resetting plugins due to page load.
,2016-03-10 16:22:54.829 ThaliTest[1053:1622463] Finished load of: file:///var/mobile/Containers/Bundle/Application/6A6D8EBE-85B1-4189-87DC-EDC73AA66A29/ThaliTest.app/www/index.html
,2016-03-10 16:22:55.056 ThaliTest[1053:1622463] JXcore Cordova plugin initializing
,2016-03-10 16:22:55.058 ThaliTest[1053:1622704] JXcore instance initializing
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

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6A6D8EBE-85B1-4189-87DC-EDC73AA66A29/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6A6D8EBE-85B1-4189-87DC-EDC73AA66A29/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6A6D8EBE-85B1-4189-87DC-EDC73AA66A29/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6A6D8EBE-85B1-4189-87DC-EDC73AA66A29/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-10 16:23:07.418 ThaliTest[1053:1622704] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-10 16:23:07.419 ThaliTest[1053:1622704] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-10 16:23:07.419 ThaliTest[1053:1,622704] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

,2016-03-10 16:23:07.420 ThaliTest[1053:1622704] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6A6D8EBE-85B1-4189-87DC-EDC73AA66A29/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6A6D8EBE-85B1-4189-87DC-EDC73AA66A29/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6A6D8EBE-85B1-4189-87DC-EDC73AA66A29/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6A6D8EBE-85B1-4189-87DC-EDC73AA66A29/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6A6D8EBE-85B1-4189-87DC-EDC73AA66A29/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6A6D8EBE-85B1-4189-87DC-EDC73AA66A29/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6A6D8EBE-85B1-4189-87DC-EDC73AA66A29/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6A6D8EBE-85B1-4189-87DC-EDC73AA66A29/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6A6D8EBE-85B1-4189-87DC-EDC73AA66A29/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6A6D8EBE-85B1-4189-87DC-EDC73AA66A29/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

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
,
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

,ok 82 error should be null

,# 19. Can call start/stopListeningForAdvertisements

,# teardown

,2016-03-10 16:26:07.584 ThaliTest[1053:1622704] jxcore: startListeningForAdvertisements
2016-03-10 16:26:07.586 ThaliTest[1053:1622704] multipeer manager: start client restart timer: 0x16552880
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}

2016-03-10 16:26:07.588 ThaliTest[1053:1622704] jxcore: startListeningForAdvertisements: success
,ok 83 Can call startListeningForAdvertisements without error

2016-03-10 16:26:07.592 ThaliTest[1053:1622704] jxcore: stopListeningForAdvertisements
2016-03-10 16:26:07.595 ThaliTest[1053:1622704] multipeer manager: stop client timer
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}

,2016-03-10 16:26:07.599 ThaliTest[1053:1622704] jxcore: stopListeningForAdvertisements: success
ok 84 Can call stopListeningForAdvertisements without error

,# setup

,2016-03-10 16:26:07.933 ThaliTest[1053:1622704] jxcore: stopListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}

,2016-03-10 16:26:07.935 ThaliTest[1053:1622704] jxcore: stopListeningForAdvertisements: success
ok 85 Should be able to call stopListeningForAdvertisments in teardown

,2016-03-10 16:26:07.938 ThaliTest[1053:1622704] jxcore: stopAdvertisingAndListening
2016-03-10 16:26:07.938 ThaliTest[1053:1622704] THEMultipeerManager stopping peer
2016-03-10 16:26:07.939 ThaliTest[1053:1622704] jxcore: stopAdvertisingAndListening: suc,cess
ok 86 Should be able to call stopAdvertisingAndListening in teardown

,# 20. Calling startListeningForAdvertisements twice is NOT an error

,# teardown

,2016-03-10 16:26:08.479 ThaliTest[1053:1622704] jxcore: startListeningForAdvertisements
2016-03-10 16:26:08.480 ThaliTest[1053:1622704] multipeer manager: start client restart timer: 0x16552880
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}

,2016-03-10 16:26:08.482 ThaliTest[1053:1622704] jxcore: startListeningForAdvertisements: success
,ok 87 Can call startListeningForAdvertisements without error

2016-03-10 16:26:08.486 ThaliTest[1053:1622704] jxcore: startListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discov,eryActive":true}

,2016-03-10 16:26:08.487 ThaliTest[1053:1622704] jxcore: startListeningForAdvertisements: success
ok 88 Can call startListeningForAdvertisements twice without error

,# setup

,2016-03-10 16:26:08.591 ThaliTest[1053:1622704] jxcore: stopListeningForAdvertisements
2016-03-10 16:26:08.592 ThaliTest[1053:1622704] multipeer manager: stop client timer
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}

,2016-03-10 16:26:08.594 ThaliTest[1053:1622704] jxcore: stopListeningForAdvertisements: success
ok 89 Should be able to call stopListeningForAdvertisments in teardown

,2016-03-10 16:26:08.599 ThaliTest[1053:1622704] jxcore: stopAdvertisingAndListening
2016-03-10 16:26:08.599 ThaliTest[1053:1622704] THEMultipeerManager stopping peer
2016-03-10 16:26:08.599 ThaliTest[1053:1622704] jxcore: stopAdvertisingAndListening: success
ok 90 Should be able to call stopAdvertisingAndListening in teardown

,# 21. Can call start/stopUpdateAdvertisingAndListening

,# teardown

,2016-03-10 16:26:09.402 ThaliTest[1053:1622704] jxcore: startUpdateAdvertisingAndListening
2016-03-10 16:26:09.403 ThaliTest[1053:1622704] server: starting C9491499-6B46-498D-8C3C-073CDE82501E:1
2016-03-10 16:26:09.403 ThaliTest[1053:1622704] multipeer m,anager: start client restart timer: 0x16552880
2016-03-10 16:26:09.404 ThaliTest[1053:1622704] THEMultipeerManager initialized peer C9491499-6B46-498D-8C3C-073CDE82501E:1
2016-03-10 16:26:09.404 ThaliTest[1053:1622704] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 91 Can call startUpdateAdvertisingAndListening without error

,2016-03-10 16:26:09.408 ThaliTest[1053:1622704] jxcore: stopAdvertisingAndListening
2016-03-10 16:26:09.409 ThaliTest[1053:1622704] THEMultipeerManager stopping peer
2016-03-10 16:26:09.410 ThaliTest[1053:1622704] multipeer manager: stop client timer
20,16-03-10 16:26:09.410 ThaliTest[1053:1622704] jxcore: stopAdvertisingAndListening: success
ok 92 Can call stopAdvertisingAndListening without error

# setup

,2016-03-10 16:26:09.563 ThaliTest[1053:1622704] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}

,2016-03-10 16:26:09.566 ThaliTest[1053:1622704] jxcore: stopListeningForAdvertisements: success
ok 93 Should be able to call stopListeningForAdvertisments in teardown

,2016-03-10 16:26:09.568 ThaliTest[1053:1622704] jxcore: stopAdvertisingAndListening
2016-03-10 16:26:09.568 ThaliTest[1053:1622704] THEMultipeerManager stopping peer
2016-03-10 16:26:09.568 ThaliTest[1053:1622704] jxcore: stopAdvertisingAndListening: suc,cess
ok 94 Should be able to call stopAdvertisingAndListening in teardown

,# 22. Calling startUpdateAdvertisingAndListening twice is NOT an error

,# teardown

,2016-03-10 16:26:10.061 ThaliTest[1053:1622704] jxcore: startUpdateAdvertisingAndListening
2016-03-10 16:26:10.062 ThaliTest[1053:1622704] server: starting C9491499-6B46-498D-8C3C-073CDE82501E:2
2016-03-10 16:26:10.063 ThaliTest[1053:1622704] multipeer m,anager: start client restart timer: 0x16552880
2016-03-10 16:26:10.064 ThaliTest[1053:1622704] THEMultipeerManager initialized peer C9491499-6B46-498D-8C3C-073CDE82501E:2
2016-03-10 16:26:10.064 ThaliTest[1053:1622704] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 95 Can call startUpdateAdvertisingAndListening without error

,2016-03-10 16:26:10.067 ThaliTest[1053:1622704] jxcore: startUpdateAdvertisingAndListening
2016-03-10 16:26:10.068 ThaliTest[1053:1622704] THEMultipeerManager stopping peer
2016-03-10 16:26:10.069 ThaliTest[1053:1622704] multipeer manager: stop client ti,mer
2016-03-10 16:26:10.070 ThaliTest[1053:1622704] server: starting C9491499-6B46-498D-8C3C-073CDE82501E:3
2016-03-10 16:26:10.070 ThaliTest[1053:1622704] multipeer manager: start client restart timer: 0x16552880
2016-03-10 16:26:10.071 ThaliTest[1053:,1622704] THEMultipeerManager initialized peer C9491499-6B46-498D-8C3C-073CDE82501E:3
2016-03-10 16:26:10.071 ThaliTest[1053:1622704] jxcore: startUpdateAdvertisingAndListening: success
ok 96 Can call startUpdateAdvertisingAndListening twice without error

# setup

,2016-03-10 16:26:10.175 ThaliTest[1053:1622704] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,
,2016-03-10 16:26:10.177 ThaliTest[1053:1622704] jxcore: stopListeningForAdvertisements: success
ok 97 Should be able to call stopListeningForAdvertisments in teardown

,2016-03-10 16:26:10.180 ThaliTest[1053:1622704] jxcore: stopAdvertisingAndListening
2016-03-10 16:26:10.180 ThaliTest[1053:1622704] THEMultipeerManager stopping peer
2016-03-10 16:26:10.180 ThaliTest[1053:1622704] multipeer manager: stop client timer
20,16-03-10 16:26:10.181 ThaliTest[1053:1622704] jxcore: stopAdvertisingAndListening: success
,ok 98 Should be able to call stopAdvertisingAndListening in teardown

,# 23. peerAvailabilityChange is called

,# teardown

,2016-03-10 16:26:10.585 ThaliTest[1053:1622704] jxcore: startUpdateAdvertisingAndListening
2016-03-10 16:26:10.586 ThaliTest[1053:1622704] server: starting C9491499-6B46-498D-8C3C-073CDE82501E:4
2016-03-10 16:26:10.587 ThaliTest[1053:1622704] multipeer m,anager: start client restart timer: 0x16552880
2016-03-10 16:26:10.587 ThaliTest[1053:1622704] THEMultipeerManager initialized peer C9491499-6B46-498D-8C3C-073CDE82501E:4
2016-03-10 16:26:10.588 ThaliTest[1053:1622704] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 99 Can call startUpdateAdvertisingAndListeningwithout error

,2016-03-10 16:26:10.589 ThaliTest[1053:1622704] jxcore: startListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}

2016-03-10 16:26:10.593 ThaliTest[1053:1622704] jxcore: startListeningForAdvertisements: success
ok 100 Can call startListeningForAdvertisements without error

,2016-03-10 16:26:11.762 ThaliTest[1053:1622463] client: found new peer: 2DDCB564-8D3A-4BFA-B857-963B8512EB44:4
,ok 101 peers must be an array

ok 102 peers must not be zero-length

ok 103 peer must have peerIdentifier

,ok 104 peerIdentifier must be a string

,ok 105 peer must have peerAvailable

,ok 106 peer must have pleaseConnect

,# setup

,2016-03-10 16:26:12.537 ThaliTest[1053:1622704] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}

,2016-03-10 16:26:12.539 ThaliTest[1053:1622704] jxcore: stopListeningForAdvertisements: success
,ok 107 Should be able to call stopListeningForAdvertisments in teardown

,2016-03-10 16:26:12.542 ThaliTest[1053:1622704] jxcore: stopAdvertisingAndListening
2016-03-10 16:26:12.543 ThaliTest[1053:1622704] THEMultipeerManager stopping peer
,2016-03-10 16:26:12.544 ThaliTest[1053:1622704] multipeer manager: stop client timer
2016-03-10 16:26:12.544 ThaliTest[1053:1622704] jxcore: stopAdvertisingAndListening: success
ok 108 Should be able to call stopAdvertisingAndListening in teardown

# 2,4. Can connect to a remote peer

,# teardown

,2016-03-10 16:26:13.012 ThaliTest[1053:1622704] jxcore: startUpdateAdvertisingAndListening
2016-03-10 16:26:13.013 ThaliTest[1053:1622704] server: starting C9491499-6B46-498D-8C3C-073CDE82501E:5
2016-03-10 16:26:13.014 ThaliTest[1053:1622704] multipeer m,anager: start client restart timer: 0x16552880
2016-03-10 16:26:13.014 ThaliTest[1053:1622704] THEMultipeerManager initialized peer C9491499-6B46-498D-8C3C-073CDE82501E:5
2016-03-10 16:26:13.014 ThaliTest[1053:1622704] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 109 Can call startUpdateAdvertisingAndListening without error

2016-03-10 16:26:13.016 ThaliTest[1053:1622704] jxcore: startListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisin,gActive":true,"discoveryActive":true}

2016-03-10 16:26:13.018 ThaliTest[1053:1622704] jxcore: startListeningForAdvertisements: success
ok 110 Can call startListeningForAdvertisements without error

,2016-03-10 16:26:13.907 ThaliTest[1053:1622463] client: found new peer: 2DDCB564-8D3A-4BFA-B857-963B8512EB44:4
2016-03-10 16:26:13.909 ThaliTest[1053:1622704] jxcore: connect 2DDCB564-8D3A-4BFA-B857-963B8512EB44:4
2016-03-10 16:26:13.909 ThaliTest[1053:1,622704] client session: connect
2016-03-10 16:26:13.910 ThaliTest[1053:1622704] client session: stateChange:0->1 2DDCB564-8D3A-4BFA-B857-963B8512EB44:4
,2016-03-10 16:26:14.184 ThaliTest[1053:1622463] multipeer session: reset timer
2016-03-10 16:26:14.185 ThaliTest[1053:1622463] server: rejecting invitation from 2DDCB564-8D3A-4BFA-B857-963B8512EB44 due to previous generation (C9491499-6B46-498D-8C3C-073CDE82501E:5 != C9491499-6B46-498D-8C3C-073CDE82501E:4)
,2016-03-10 16:26:15.164 ThaliTest[1053:1623027] client session: not connected 2DDCB564-8D3A-4BFA-B857-963B8512EB44:4
2016-03-10 16:26:15.164 ThaliTest[1053:1623027] client session: onLinkFailure: 2DDCB564-8D3A-4BFA-B857-963B8512EB44
2016-03-10 16:26:15.1,65 ThaliTest[1053:1623027] client session: disconnect
,2016-03-10 16:26:15.165 ThaliTest[1053:1623027] client session: stateChange:1->0 2DDCB564-8D3A-4BFA-B857-963B8512EB44:4
,2016-03-10 16:26:15.168 ThaliTest[1053:1623027] client session: fireConnectCallback: 2DDCB564-8D3A-4BFA-B857-963B8512EB44
2016-03-10 16:26:15.168 ThaliTest[1053:1623027] jxcore: connect: fail: Peer disconnected
,not ok 111 Error from connect: Peer disconnected

  ---

,    operator: fail

,  ...

,# setup

,2016-03-10 16:26:33.015 ThaliTest[1053:1622463] multipeer manager: restart client
,2016-03-10 16:26:33.033 ThaliTest[1053:1622463] client: found updated peer: 2DDCB564-8D3A-4BFA-B857-963B8512EB44:5
,2016-03-10 16:26:53.015 ThaliTest[1053:1622463] multipeer manager: restart client
,2016-03-10 16:26:53.033 ThaliTest[1053:1622463] client: found existing peer: 2DDCB564-8D3A-4BFA-B857-963B8512EB44:5
,2016-03-10 16:27:13.015 ThaliTest[1053:1622463] multipeer manager: restart client
,2016-03-10 16:27:13.033 ThaliTest[1053:1622463] client: found existing peer: 2DDCB564-8D3A-4BFA-B857-963B8512EB44:5
,2016-03-10 16:27:33.015 ThaliTest[1053:1622463] multipeer manager: restart client
,2016-03-10 16:27:53.015 ThaliTest[1053:1622463] multipeer manager: restart client
,2016-03-10 16:27:53.027 ThaliTest[1053:1622463] client: found existing peer: 2DDCB564-8D3A-4BFA-B857-963B8512EB44:5
,2016-03-10 16:28:13.015 ThaliTest[1053:1622463] multipeer manager: restart client
,2016-03-10 16:28:13.028 ThaliTest[1053:1622463] client: found existing peer: 2DDCB564-8D3A-4BFA-B857-963B8512EB44:5
,2016-03-10 16:28:33.015 ThaliTest[1053:1622463] multipeer manager: restart client
,2016-03-10 16:28:33.026 ThaliTest[1053:1622463] client: found existing peer: 2DDCB564-8D3A-4BFA-B857-963B8512EB44:5
,2016-03-10 16:28:53.015 ThaliTest[1053:1622463] multipeer manager: restart client
,2016-03-10 16:28:53.028 ThaliTest[1053:1622463] client: found existing peer: 2DDCB564-8D3A-4BFA-B857-963B8512EB44:5
,2016-03-10 16:29:13.015 ThaliTest[1053:1622463] multipeer manager: restart client
,2016-03-10 16:29:33.015 ThaliTest[1053:1622463] multipeer manager: restart client
,2016-03-10 16:29:33.027 ThaliTest[1053:1622463] client: found existing peer: 2DDCB564-8D3A-4BFA-B857-963B8512EB44:5
,2016-03-10 16:29:53.014 ThaliTest[1053:1622463] multipeer manager: restart client
,2016-03-10 16:29:53.028 ThaliTest[1053:1622463] client: found existing peer: 2DDCB564-8D3A-4BFA-B857-963B8512EB44:5
,2016-03-10 16:30:13.015 ThaliTest[1053:1622463] multipeer manager: restart client
,2016-03-10 16:30:13.027 ThaliTest[1053:1622463] client: found existing peer: 2DDCB564-8D3A-4BFA-B857-963B8512EB44:5
,2016-03-10 16:30:33.015 ThaliTest[1053:1622463] multipeer manager: restart client
,2016-03-10 16:30:33.028 ThaliTest[1053:1622463] client: found existing peer: 2DDCB564-8D3A-4BFA-B857-963B8512EB44:5
,2016-03-10 16:30:53.015 ThaliTest[1053:1622463] multipeer manager: restart client
,2016-03-10 16:30:53.029 ThaliTest[1053:1622463] client: found existing peer: 2DDCB564-8D3A-4BFA-B857-963B8512EB44:5
,2016-03-10 16:31:12.963 ThaliTest[1053:1622463] multipeer manager: restart client
,2016-03-10 16:31:12.977 ThaliTest[1053:1622463] client: found existing peer: 2DDCB564-8D3A-4BFA-B857-963B8512EB44:5
,2016-03-10 16:31:32.963 ThaliTest[1053:1622463] multipeer manager: restart client
,2016-03-10 16:31:32.975 ThaliTest[1053:1622463] client: found existing peer: 2DDCB564-8D3A-4BFA-B857-963B8512EB44:5
,2016-03-10 16:31:52.963 ThaliTest[1053:1622463] multipeer manager: restart client
,2016-03-10 16:31:52.975 ThaliTest[1053:1622463] client: found existing peer: 2DDCB564-8D3A-4BFA-B857-963B8512EB44:5
,2016-03-10 16:32:12.963 ThaliTest[1053:1622463] multipeer manager: restart client
,2016-03-10 16:32:12.975 ThaliTest[1053:1622463] client: found existing peer: 2DDCB564-8D3A-4BFA-B857-963B8512EB44:5
,2016-03-10 16:32:32.963 ThaliTest[1053:1622463] multipeer manager: restart client
,2016-03-10 16:32:32.976 ThaliTest[1053:1622463] client: found existing peer: 2DDCB564-8D3A-4BFA-B857-963B8512EB44:5
,2016-03-10 16:32:52.963 ThaliTest[1053:1622463] multipeer manager: restart client
,2016-03-10 16:32:52.976 ThaliTest[1053:1622463] client: found existing peer: 2DDCB564-8D3A-4BFA-B857-963B8512EB44:5
,2016-03-10 16:33:12.963 ThaliTest[1053:1622463] multipeer manager: restart client
,2016-03-10 16:33:12.974 ThaliTest[1053:1622463] client: found existing peer: 2DDCB564-8D3A-4BFA-B857-963B8512EB44:5
,2016-03-10 16:33:32.963 ThaliTest[1053:1622463] multipeer manager: restart client
,2016-03-10 16:33:32.976 ThaliTest[1053:1622463] client: found existing peer: 2DDCB564-8D3A-4BFA-B857-963B8512EB44:5
,2016-03-10 16:33:52.963 ThaliTest[1053:1622463] multipeer manager: restart client
,2016-03-10 16:33:52.974 ThaliTest[1053:1622463] client: found existing peer: 2DDCB564-8D3A-4BFA-B857-963B8512EB44:5
,2016-03-10 16:34:12.963 ThaliTest[1053:1622463] multipeer manager: restart client
,2016-03-10 16:34:12.975 ThaliTest[1053:1622463] client: found existing peer: 2DDCB564-8D3A-4BFA-B857-963B8512EB44:5
,2016-03-10 16:34:32.963 ThaliTest[1053:1622463] multipeer manager: restart client
,2016-03-10 16:34:32.974 ThaliTest[1053:1622463] client: found existing peer: 2DDCB564-8D3A-4BFA-B857-963B8512EB44:5
,2016-03-10 16:34:52.963 ThaliTest[1053:1622463] multipeer manager: restart client
,2016-03-10 16:34:52.975 ThaliTest[1053:1622463] client: found existing peer: 2DDCB564-8D3A-4BFA-B857-963B8512EB44:5
,2016-03-10 16:35:12.963 ThaliTest[1053:1622463] multipeer manager: restart client
,2016-03-10 16:35:12.975 ThaliTest[1053:1622463] client: found existing peer: 2DDCB564-8D3A-4BFA-B857-963B8512EB44:5
,2016-03-10 16:35:32.963 ThaliTest[1053:1622463] multipeer manager: restart client
,2016-03-10 16:35:32.977 ThaliTest[1053:1622463] client: found existing peer: 2DDCB564-8D3A-4BFA-B857-963B8512EB44:5
,2016-03-10 16:35:52.963 ThaliTest[1053:1622463] multipeer manager: restart client
,2016-03-10 16:35:52.975 ThaliTest[1053:1622463] client: found existing peer: 2DDCB564-8D3A-4BFA-B857-963B8512EB44:5
,2016-03-10 16:36:12.963 ThaliTest[1053:1622463] multipeer manager: restart client
,2016-03-10 16:36:12.977 ThaliTest[1053:1622463] client: found existing peer: 2DDCB564-8D3A-4BFA-B857-963B8512EB44:5
,2016-03-10 16:36:32.963 ThaliTest[1053:1622463] multipeer manager: restart client
,2016-03-10 16:36:32.975 ThaliTest[1053:1622463] client: found existing peer: 2DDCB564-8D3A-4BFA-B857-963B8512EB44:5
,2016-03-10 16:36:52.963 ThaliTest[1053:1622463] multipeer manager: restart client
,2016-03-10 16:37:12.963 ThaliTest[1053:1622463] multipeer manager: restart client
,2016-03-10 16:37:12.974 ThaliTest[1053:1622463] client: found existing peer: 2DDCB564-8D3A-4BFA-B857-963B8512EB44:5
,2016-03-10 16:37:32.963 ThaliTest[1053:1622463] multipeer manager: restart client
,2016-03-10 16:37:52.963 ThaliTest[1053:1622463] multipeer manager: restart client
,2016-03-10 16:37:52.976 ThaliTest[1053:1622463] client: found existing peer: 2DDCB564-8D3A-4BFA-B857-963B8512EB44:5
,2016-03-10 16:38:12.963 ThaliTest[1053:1622463] multipeer manager: restart client
,2016-03-10 16:38:12.976 ThaliTest[1053:1622463] client: found existing peer: 2DDCB564-8D3A-4BFA-B857-963B8512EB44:5
,2016-03-10 16:38:32.963 ThaliTest[1053:1622463] multipeer manager: restart client
,2016-03-10 16:38:32.975 ThaliTest[1053:1622463] client: found existing peer: 2DDCB564-8D3A-4BFA-B857-963B8512EB44:5
,2016-03-10 16:38:52.963 ThaliTest[1053:1622463] multipeer manager: restart client
,2016-03-10 16:38:52.976 ThaliTest[1053:1622463] client: found existing peer: 2DDCB564-8D3A-4BFA-B857-963B8512EB44:5
,2016-03-10 16:39:12.963 ThaliTest[1053:1622463] multipeer manager: restart client
,2016-03-10 16:39:12.976 ThaliTest[1053:1622463] client: found existing peer: 2DDCB564-8D3A-4BFA-B857-963B8512EB44:5
,2016-03-10 16:39:32.963 ThaliTest[1053:1622463] multipeer manager: restart client
,2016-03-10 16:39:32.976 ThaliTest[1053:1622463] client: found existing peer: 2DDCB564-8D3A-4BFA-B857-963B8512EB44:5
,2016-03-10 16:39:52.963 ThaliTest[1053:1622463] multipeer manager: restart client
,2016-03-10 16:39:52.975 ThaliTest[1053:1622463] client: found existing peer: 2DDCB564-8D3A-4BFA-B857-963B8512EB44:5
,2016-03-10 16:40:12.963 ThaliTest[1053:1622463] multipeer manager: restart client
,2016-03-10 16:40:12.976 ThaliTest[1053:1622463] client: found existing peer: 2DDCB564-8D3A-4BFA-B857-963B8512EB44:5
,2016-03-10 16:40:32.963 ThaliTest[1053:1622463] multipeer manager: restart client
,2016-03-10 16:40:32.977 ThaliTest[1053:1622463] client: found existing peer: 2DDCB564-8D3A-4BFA-B857-963B8512EB44:5
,2016-03-10 16:40:52.963 ThaliTest[1053:1622463] multipeer manager: restart client
,2016-03-10 16:41:12.963 ThaliTest[1053:1622463] multipeer manager: restart client
,2016-03-10 16:41:12.975 ThaliTest[1053:1622463] client: found existing peer: 2DDCB564-8D3A-4BFA-B857-963B8512EB44:5
,2016-03-10 16:41:32.963 ThaliTest[1053:1622463] multipeer manager: restart client
,2016-03-10 16:41:32.975 ThaliTest[1053:1622463] client: found existing peer: 2DDCB564-8D3A-4BFA-B857-963B8512EB44:5
,2016-03-10 16:41:52.963 ThaliTest[1053:1622463] multipeer manager: restart client
,2016-03-10 16:41:52.975 ThaliTest[1053:1622463] client: found existing peer: 2DDCB564-8D3A-4BFA-B857-963B8512EB44:5
,2016-03-10 16:42:12.963 ThaliTest[1053:1622463] multipeer manager: restart client
,2016-03-10 16:42:12.976 ThaliTest[1053:1622463] client: found existing peer: 2DDCB564-8D3A-4BFA-B857-963B8512EB44:5
,2016-03-10 16:42:32.963 ThaliTest[1053:1622463] multipeer manager: restart client
,2016-03-10 16:42:32.974 ThaliTest[1053:1622463] client: found existing peer: 2DDCB564-8D3A-4BFA-B857-963B8512EB44:5
,2016-03-10 16:42:52.963 ThaliTest[1053:1622463] multipeer manager: restart client
,2016-03-10 16:42:52.976 ThaliTest[1053:1622463] client: found existing peer: 2DDCB564-8D3A-4BFA-B857-963B8512EB44:5
,2016-03-10 16:43:12.963 ThaliTest[1053:1622463] multipeer manager: restart client
,2016-03-10 16:43:12.975 ThaliTest[1053:1622463] client: found existing peer: 2DDCB564-8D3A-4BFA-B857-963B8512EB44:5
,2016-03-10 16:43:32.962 ThaliTest[1053:1622463] multipeer manager: restart client
,2016-03-10 16:43:32.975 ThaliTest[1053:1622463] client: found existing peer: 2DDCB564-8D3A-4BFA-B857-963B8512EB44:5
,2016-03-10 16:43:52.963 ThaliTest[1053:1622463] multipeer manager: restart client
,2016-03-10 16:43:52.976 ThaliTest[1053:1622463] client: found existing peer: 2DDCB564-8D3A-4BFA-B857-963B8512EB44:5

```
