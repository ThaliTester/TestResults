#### Test 61362366b225741_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/61362366b225741/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/8A0D0E65-5B68-4C3A-BA0B-133707BFC3CA/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/8A0D0E65-5B68-4C3A-BA0B-133707BFC3CA/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/61362366b225741/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/61362366b225741/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/CFF81F8D-AC59-4A10-A600-586E1147EB9B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50607"
,(lldb)     command script import "/tmp/8A0D0E65-5B68-4C3A-BA0B-133707BFC3CA/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-10 11:12:26.566 ThaliTest[1061:1626535] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/DE0FA8E8-0386-4F7B-96D9-BCD22341624A/Library/Cookies/Cookies.binarycookies
,2016-03-10 11:12:26.947 ThaliTest[1061:1626535] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-10 11:12:26.948 ThaliTest[1061:1626535] Multi-tasking -> Device: YES, App: YES
,2016-03-10 11:12:26.967 ThaliTest[1061:1626535] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-10 11:12:28.786 ThaliTest[1061:1626535] Using UIWebView
,2016-03-10 11:12:28.793 ThaliTest[1061:1626535] [CDVTimer][handleopenurl] 0.719011ms
,2016-03-10 11:12:28.801 ThaliTest[1061:1626535] [CDVTimer][intentandnavigationfilter] 7.247984ms
,2016-03-10 11:12:28.801 ThaliTest[1061:1626535] [CDVTimer][gesturehandler] 0.340998ms
,2016-03-10 11:12:28.802 ThaliTest[1061:1626535] [CDVTimer][TotalPluginStartup] 10.082960ms
,2016-03-10 11:12:35.077 ThaliTest[1061:1626535] Resetting plugins due to page load.
,2016-03-10 11:12:38.309 ThaliTest[1061:1626535] Finished load of: file:///var/mobile/Containers/Bundle/Application/CFF81F8D-AC59-4A10-A600-586E1147EB9B/ThaliTest.app/www/index.html
,2016-03-10 11:12:38.516 ThaliTest[1061:1626535] JXcore Cordova plugin initializing
,2016-03-10 11:12:38.517 ThaliTest[1061:1626751] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,INFO testUtils Toggling radios to: true

,Unit Test app is loaded

,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CFF81F8D-AC59-4A10-A600-586E1147EB9B/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CFF81F8D-AC59-4A10-A600-586E1147EB9B/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CFF81F8D-AC59-4A10-A600-586E1147EB9B/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CFF81F8D-AC59-4A10-A600-586E1147EB9B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-10 11:12:50.160 ThaliTest[1061:1626751] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-10 11:12:50.160 ThaliTest[1061:1626751] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-10 11:12:50.160 ThaliTest[1061:1626751] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

,2016-03-10 11:12:50.161 ThaliTest[1061:1626751] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CFF81F8D-AC59-4A10-A600-586E1147EB9B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CFF81F8D-AC59-4A10-A600-586E1147EB9B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CFF81F8D-AC59-4A10-A600-586E1147EB9B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CFF81F8D-AC59-4A10-A600-586E1147EB9B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CFF81F8D-AC59-4A10-A600-586E1147EB9B/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CFF81F8D-AC59-4A10-A600-586E1147EB9B/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CFF81F8D-AC59-4A10-A600-586E1147EB9B/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CFF81F8D-AC59-4A10-A600-586E1147EB9B/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CFF81F8D-AC59-4A10-A600-586E1147EB9B/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CFF81F8D-AC59-4A10-A600-586E1147EB9B/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

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

,ok 82 error should be null

,# 19. Can call start/stopListeningForAdvertisements

,# teardown

,2016-03-10 11:14:48.761 ThaliTest[1061:1626751] jxcore: startListeningForAdvertisements
,2016-03-10 11:14:48.764 ThaliTest[1061:1626751] multipeer manager: start client restart timer: 0x14f6ae20
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}

,2016-03-10 11:14:48.767 ThaliTest[1061:1626751] jxcore: startListeningForAdvertisements: success
,ok 83 Can call startListeningForAdvertisements without error

,2016-03-10 11:14:48.770 ThaliTest[1061:1626751] jxcore: stopListeningForAdvertisements
,2016-03-10 11:14:48.771 ThaliTest[1061:1626751] multipeer manager: stop client timer
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}

,2016-03-10 11:14:48.773 ThaliTest[1061:1626751] jxcore: stopListeningForAdvertisements: success
,ok 84 Can call stopListeningForAdvertisements without error

,# setup

,2016-03-10 11:14:49.113 ThaliTest[1061:1626751] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}

,2016-03-10 11:14:49.115 ThaliTest[1061:1626751] jxcore: stopListeningForAdvertisements: success
,ok 85 Should be able to call stopListeningForAdvertisments in teardown

,2016-03-10 11:14:49.117 ThaliTest[1061:1626751] jxcore: stopAdvertisingAndListening
,2016-03-10 11:14:49.118 ThaliTest[1061:1626751] THEMultipeerManager stopping peer
,2016-03-10 11:14:49.118 ThaliTest[1061:1626751] jxcore: stopAdvertisingAndListening: success
,ok 86 Should be able to call stopAdvertisingAndListening in teardown

,# 20. Calling startListeningForAdvertisements twice is NOT an error

,# teardown

,2016-03-10 11:14:49.642 ThaliTest[1061:1626751] jxcore: startListeningForAdvertisements
,2016-03-10 11:14:49.643 ThaliTest[1061:1626751] multipeer manager: start client restart timer: 0x14f6ae20
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}

,2016-03-10 11:14:49.645 ThaliTest[1061:1626751] jxcore: startListeningForAdvertisements: success
,ok 87 Can call startListeningForAdvertisements without error

,2016-03-10 11:14:49.649 ThaliTest[1061:1626751] jxcore: startListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}

,2016-03-10 11:14:49.651 ThaliTest[1061:1626751] jxcore: startListeningForAdvertisements: success
,ok 88 Can call startListeningForAdvertisements twice without error

,# setup

,2016-03-10 11:14:49.751 ThaliTest[1061:1626751] jxcore: stopListeningForAdvertisements
,2016-03-10 11:14:49.752 ThaliTest[1061:1626751] multipeer manager: stop client timer
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}

,2016-03-10 11:14:49.755 ThaliTest[1061:1626751] jxcore: stopListeningForAdvertisements: success
,ok 89 Should be able to call stopListeningForAdvertisments in teardown

,2016-03-10 11:14:49.758 ThaliTest[1061:1626751] jxcore: stopAdvertisingAndListening
,2016-03-10 11:14:49.759 ThaliTest[1061:1626751] THEMultipeerManager stopping peer
,2016-03-10 11:14:49.759 ThaliTest[1061:1626751] jxcore: stopAdvertisingAndListening: success
,ok 90 Should be able to call stopAdvertisingAndListening in teardown

,# 21. Can call start/stopUpdateAdvertisingAndListening

,# teardown

,2016-03-10 11:14:52.399 ThaliTest[1061:1626751] jxcore: startUpdateAdvertisingAndListening
,2016-03-10 11:14:52.400 ThaliTest[1061:1626751] server: starting 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:1
,2016-03-10 11:14:52.402 ThaliTest[1061:1626751] multipeer manager: start client restart timer: 0x14f6ae20
2016-03-10 11:14:52.402 ThaliTest[1061:1626751] THEMultipeerManager initialized peer 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:1
2016-03-10 11:14:52.402 ThaliTest[1061:1626751] jxcore: startUpdateAdvertisingAndListening: success
,ok 91 Can call startUpdateAdvertisingAndListening without error

,2016-03-10 11:14:52.406 ThaliTest[1061:1626751] jxcore: stopAdvertisingAndListening
2016-03-10 11:14:52.406 ThaliTest[1061:1626751] THEMultipeerManager stopping peer
2016-03-10 11:14:52.407 ThaliTest[1061:1626751] multipeer manager: stop client timer
2016-03-10 11:14:52.407 ThaliTest[1061:1626751] jxcore: stopAdvertisingAndListening: success
ok 92 Can call stopAdvertisingAndListening without error

,# setup

,2016-03-10 11:14:52.698 ThaliTest[1061:1626751] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}

,2016-03-10 11:14:52.700 ThaliTest[1061:1626751] jxcore: stopListeningForAdvertisements: success
,ok 93 Should be able to call stopListeningForAdvertisments in teardown

,2016-03-10 11:14:52.702 ThaliTest[1061:1626751] jxcore: stopAdvertisingAndListening
,2016-03-10 11:14:52.703 ThaliTest[1061:1626751] THEMultipeerManager stopping peer
,2016-03-10 11:14:52.703 ThaliTest[1061:1626751] jxcore: stopAdvertisingAndListening: success
,ok 94 Should be able to call stopAdvertisingAndListening in teardown

,# 22. Calling startUpdateAdvertisingAndListening twice is NOT an error

,# teardown

,2016-03-10 11:14:55.307 ThaliTest[1061:1626751] jxcore: startUpdateAdvertisingAndListening
,2016-03-10 11:14:55.308 ThaliTest[1061:1626751] server: starting 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:2
,2016-03-10 11:14:55.310 ThaliTest[1061:1626751] multipeer manager: start client restart timer: 0x14f6ae20
2016-03-10 11:14:55.310 ThaliTest[1061:1626751] THEMultipeerManager initialized peer 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:2
2016-03-10 11:14:55.310 ThaliTest[1061:1626751] jxcore: startUpdateAdvertisingAndListening: success
,ok 95 Can call startUpdateAdvertisingAndListening without error

,2016-03-10 11:14:55.313 ThaliTest[1061:1626751] jxcore: startUpdateAdvertisingAndListening
2016-03-10 11:14:55.314 ThaliTest[1061:1626751] THEMultipeerManager stopping peer
2016-03-10 11:14:55.314 ThaliTest[1061:1626751] multipeer manager: stop client timer
,2016-03-10 11:14:55.315 ThaliTest[1061:1626751] server: starting 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:3
,2016-03-10 11:14:55.316 ThaliTest[1061:1626751] multipeer manager: start client restart timer: 0x14f6ae20
2016-03-10 11:14:55.317 ThaliTest[1061:1626751] THEMultipeerManager initialized peer 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:3
2016-03-10 11:14:55.318 ,ThaliTest[1061:1626751] jxcore: startUpdateAdvertisingAndListening: success
ok 96 Can call startUpdateAdvertisingAndListening twice without error

,# setup

,2016-03-10 11:14:55.472 ThaliTest[1061:1626751] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}

,2016-03-10 11:14:55.474 ThaliTest[1061:1626751] jxcore: stopListeningForAdvertisements: success
,ok 97 Should be able to call stopListeningForAdvertisments in teardown

,2016-03-10 11:14:55.476 ThaliTest[1061:1626751] jxcore: stopAdvertisingAndListening
,2016-03-10 11:14:55.477 ThaliTest[1061:1626751] THEMultipeerManager stopping peer
,2016-03-10 11:14:55.478 ThaliTest[1061:1626751] multipeer manager: stop client timer
,2016-03-10 11:14:55.480 ThaliTest[1061:1626751] jxcore: stopAdvertisingAndListening: success
,ok 98 Should be able to call stopAdvertisingAndListening in teardown

,# 23. peerAvailabilityChange is called

,# teardown

,2016-03-10 11:14:55.967 ThaliTest[1061:1626751] jxcore: startUpdateAdvertisingAndListening
,2016-03-10 11:14:55.968 ThaliTest[1061:1626751] server: starting 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:4
,2016-03-10 11:14:55.969 ThaliTest[1061:1626751] multipeer manager: start client restart timer: 0x14f6ae20
2016-03-10 11:14:55.970 ThaliTest[1061:1626751] THEMultipeerManager initialized peer 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:4
2016-03-10 11:14:55.970 ThaliTest[1061:1626751] jxcore: startUpdateAdvertisingAndListening: success
ok 99 Can call startUpdateAdvertisingAndListeningwithout error

,2016-03-10 11:14:55.972 ThaliTest[1061:1626751] jxcore: startListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}

,2016-03-10 11:14:55.975 ThaliTest[1061:1626751] jxcore: startListeningForAdvertisements: success
ok 100 Can call startListeningForAdvertisements without error

,2016-03-10 11:14:57.126 ThaliTest[1061:1626535] client: found new peer: 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:4
,ok 101 peers must be an array

,ok 102 peers must not be zero-length

,ok 103 peer must have peerIdentifier

,ok 104 peerIdentifier must be a string

,ok 105 peer must have peerAvailable

,ok 106 peer must have pleaseConnect

,# setup

,2016-03-10 11:14:59.041 ThaliTest[1061:1626751] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}

,2016-03-10 11:14:59.043 ThaliTest[1061:1626751] jxcore: stopListeningForAdvertisements: success
,ok 107 Should be able to call stopListeningForAdvertisments in teardown

,2016-03-10 11:14:59.046 ThaliTest[1061:1626751] jxcore: stopAdvertisingAndListening
,2016-03-10 11:14:59.046 ThaliTest[1061:1626751] THEMultipeerManager stopping peer
,2016-03-10 11:14:59.047 ThaliTest[1061:1626751] multipeer manager: stop client timer
,2016-03-10 11:14:59.048 ThaliTest[1061:1626751] jxcore: stopAdvertisingAndListening: success
,ok 108 Should be able to call stopAdvertisingAndListening in teardown

,# 24. Can connect to a remote peer

,# teardown

,2016-03-10 11:14:59.701 ThaliTest[1061:1626751] jxcore: startUpdateAdvertisingAndListening
,2016-03-10 11:14:59.702 ThaliTest[1061:1626751] server: starting 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:5
,2016-03-10 11:14:59.703 ThaliTest[1061:1626751] multipeer manager: start client restart timer: 0x14f6ae20
2016-03-10 11:14:59.703 ThaliTest[1061:1626751] THEMultipeerManager initialized peer 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:5
,2016-03-10 11:14:59.704 ThaliTest[1061:1626751] jxcore: startUpdateAdvertisingAndListening: success
,ok 109 Can call startUpdateAdvertisingAndListening without error

,2016-03-10 11:14:59.708 ThaliTest[1061:1626751] jxcore: startListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}

2016-03-10 11:14:59.710 ThaliTest[1061:1626751] jxcore: startListeningForAdvertisements: success
,ok 110 Can call startListeningForAdvertisements without error

,2016-03-10 11:15:00.165 ThaliTest[1061:1626535] client: found new peer: 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:4
,2016-03-10 11:15:00.168 ThaliTest[1061:1626751] jxcore: connect 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:4
,2016-03-10 11:15:00.168 ThaliTest[1061:1626751] client session: connect
,2016-03-10 11:15:00.169 ThaliTest[1061:1626751] client session: stateChange:0->1 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:4
,2016-03-10 11:15:00.815 ThaliTest[1061:1627043] client session: not connected 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:4
2016-03-10 11:15:00.816 ThaliTest[1061:1627043] client session: onLinkFailure: 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315
,2016-03-10 11:15:00.816 ThaliTest[1061:1627043] client session: disconnect
2016-03-10 11:15:00.817 ThaliTest[1061:1627043] client session: stateChange:1->0 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:4
,2016-03-10 11:15:00.818 ThaliTest[1061:1627043] client session: fireConnectCallback: 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315
2016-03-10 11:15:00.818 ThaliTest[1061:1627043] jxcore: connect: fail: Peer disconnected
,not ok 111 Error from connect: Peer disconnected

  ---

,    operator: fail

,  ...

,# setup

,2016-03-10 11:15:01.259 ThaliTest[1061:1626535] multipeer session: reset timer
,2016-03-10 11:15:01.260 ThaliTest[1061:1626535] server: rejecting invitation from 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315 due to previous generation (9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:5 != 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:4)
,2016-03-10 11:15:19.705 ThaliTest[1061:1626535] multipeer manager: restart client
,2016-03-10 11:15:19.719 ThaliTest[1061:1626535] client: found updated peer: 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:5
,2016-03-10 11:15:39.705 ThaliTest[1061:1626535] multipeer manager: restart client
,2016-03-10 11:15:39.718 ThaliTest[1061:1626535] client: found existing peer: 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:5
,2016-03-10 11:15:59.705 ThaliTest[1061:1626535] multipeer manager: restart client
,2016-03-10 11:15:59.718 ThaliTest[1061:1626535] client: found existing peer: 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:5
,2016-03-10 11:16:19.705 ThaliTest[1061:1626535] multipeer manager: restart client
,2016-03-10 11:16:19.720 ThaliTest[1061:1626535] client: found existing peer: 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:5
,2016-03-10 11:16:39.705 ThaliTest[1061:1626535] multipeer manager: restart client
,2016-03-10 11:16:39.719 ThaliTest[1061:1626535] client: found existing peer: 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:5
,2016-03-10 11:16:59.705 ThaliTest[1061:1626535] multipeer manager: restart client
,2016-03-10 11:16:59.718 ThaliTest[1061:1626535] client: found existing peer: 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:5
,2016-03-10 11:17:19.705 ThaliTest[1061:1626535] multipeer manager: restart client
,2016-03-10 11:17:19.718 ThaliTest[1061:1626535] client: found existing peer: 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:5
,2016-03-10 11:17:39.705 ThaliTest[1061:1626535] multipeer manager: restart client
,2016-03-10 11:17:39.718 ThaliTest[1061:1626535] client: found existing peer: 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:5
,2016-03-10 11:17:59.705 ThaliTest[1061:1626535] multipeer manager: restart client
,2016-03-10 11:17:59.718 ThaliTest[1061:1626535] client: found existing peer: 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:5
,2016-03-10 11:18:19.705 ThaliTest[1061:1626535] multipeer manager: restart client
,2016-03-10 11:18:19.720 ThaliTest[1061:1626535] client: found existing peer: 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:5
,2016-03-10 11:18:39.705 ThaliTest[1061:1626535] multipeer manager: restart client
,2016-03-10 11:18:39.719 ThaliTest[1061:1626535] client: found existing peer: 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:5
,2016-03-10 11:18:59.705 ThaliTest[1061:1626535] multipeer manager: restart client
,2016-03-10 11:18:59.719 ThaliTest[1061:1626535] client: found existing peer: 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:5
,2016-03-10 11:19:19.705 ThaliTest[1061:1626535] multipeer manager: restart client
,2016-03-10 11:19:19.720 ThaliTest[1061:1626535] client: found existing peer: 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:5
,2016-03-10 11:19:39.705 ThaliTest[1061:1626535] multipeer manager: restart client
,2016-03-10 11:19:39.719 ThaliTest[1061:1626535] client: found existing peer: 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:5
,2016-03-10 11:19:59.705 ThaliTest[1061:1626535] multipeer manager: restart client
,2016-03-10 11:19:59.721 ThaliTest[1061:1626535] client: found existing peer: 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:5
,2016-03-10 11:20:19.705 ThaliTest[1061:1626535] multipeer manager: restart client
,2016-03-10 11:20:19.722 ThaliTest[1061:1626535] client: found existing peer: 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:5
,2016-03-10 11:20:39.705 ThaliTest[1061:1626535] multipeer manager: restart client
,2016-03-10 11:20:39.718 ThaliTest[1061:1626535] client: found existing peer: 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:5
,2016-03-10 11:20:59.705 ThaliTest[1061:1626535] multipeer manager: restart client
,2016-03-10 11:20:59.718 ThaliTest[1061:1626535] client: found existing peer: 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:5
,2016-03-10 11:21:19.705 ThaliTest[1061:1626535] multipeer manager: restart client
,2016-03-10 11:21:19.720 ThaliTest[1061:1626535] client: found existing peer: 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:5
,2016-03-10 11:21:39.705 ThaliTest[1061:1626535] multipeer manager: restart client
,2016-03-10 11:21:39.720 ThaliTest[1061:1626535] client: found existing peer: 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:5
,2016-03-10 11:21:59.704 ThaliTest[1061:1626535] multipeer manager: restart client
,2016-03-10 11:21:59.718 ThaliTest[1061:1626535] client: found existing peer: 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:5
,2016-03-10 11:22:19.705 ThaliTest[1061:1626535] multipeer manager: restart client
,2016-03-10 11:22:19.719 ThaliTest[1061:1626535] client: found existing peer: 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:5
,2016-03-10 11:22:39.705 ThaliTest[1061:1626535] multipeer manager: restart client
,2016-03-10 11:22:39.719 ThaliTest[1061:1626535] client: found existing peer: 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:5
,2016-03-10 11:22:59.705 ThaliTest[1061:1626535] multipeer manager: restart client
,2016-03-10 11:22:59.718 ThaliTest[1061:1626535] client: found existing peer: 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:5
,2016-03-10 11:23:19.705 ThaliTest[1061:1626535] multipeer manager: restart client
,2016-03-10 11:23:19.719 ThaliTest[1061:1626535] client: found existing peer: 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:5
,2016-03-10 11:23:39.705 ThaliTest[1061:1626535] multipeer manager: restart client
,2016-03-10 11:23:39.718 ThaliTest[1061:1626535] client: found existing peer: 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:5
,2016-03-10 11:23:59.705 ThaliTest[1061:1626535] multipeer manager: restart client
,2016-03-10 11:23:59.718 ThaliTest[1061:1626535] client: found existing peer: 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:5
,2016-03-10 11:24:19.705 ThaliTest[1061:1626535] multipeer manager: restart client
,2016-03-10 11:24:19.717 ThaliTest[1061:1626535] client: found existing peer: 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:5
,2016-03-10 11:24:39.705 ThaliTest[1061:1626535] multipeer manager: restart client
,2016-03-10 11:24:39.718 ThaliTest[1061:1626535] client: found existing peer: 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:5
,2016-03-10 11:24:59.705 ThaliTest[1061:1626535] multipeer manager: restart client
,2016-03-10 11:24:59.718 ThaliTest[1061:1626535] client: found existing peer: 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:5
,2016-03-10 11:25:19.705 ThaliTest[1061:1626535] multipeer manager: restart client
,2016-03-10 11:25:19.719 ThaliTest[1061:1626535] client: found existing peer: 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:5
,2016-03-10 11:25:39.705 ThaliTest[1061:1626535] multipeer manager: restart client
,2016-03-10 11:25:39.719 ThaliTest[1061:1626535] client: found existing peer: 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:5
,2016-03-10 11:25:59.705 ThaliTest[1061:1626535] multipeer manager: restart client
,2016-03-10 11:25:59.721 ThaliTest[1061:1626535] client: found existing peer: 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:5
,2016-03-10 11:26:19.705 ThaliTest[1061:1626535] multipeer manager: restart client
,2016-03-10 11:26:19.718 ThaliTest[1061:1626535] client: found existing peer: 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:5
,2016-03-10 11:26:39.704 ThaliTest[1061:1626535] multipeer manager: restart client
,2016-03-10 11:26:39.718 ThaliTest[1061:1626535] client: found existing peer: 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:5
,2016-03-10 11:26:59.705 ThaliTest[1061:1626535] multipeer manager: restart client
,2016-03-10 11:26:59.718 ThaliTest[1061:1626535] client: found existing peer: 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:5
,2016-03-10 11:27:19.705 ThaliTest[1061:1626535] multipeer manager: restart client
,2016-03-10 11:27:19.718 ThaliTest[1061:1626535] client: found existing peer: 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:5
,2016-03-10 11:27:39.705 ThaliTest[1061:1626535] multipeer manager: restart client
,2016-03-10 11:27:39.719 ThaliTest[1061:1626535] client: found existing peer: 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:5
,2016-03-10 11:27:59.705 ThaliTest[1061:1626535] multipeer manager: restart client
,2016-03-10 11:27:59.718 ThaliTest[1061:1626535] client: found existing peer: 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:5
,2016-03-10 11:28:19.705 ThaliTest[1061:1626535] multipeer manager: restart client
,2016-03-10 11:28:19.719 ThaliTest[1061:1626535] client: found existing peer: 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:5
,2016-03-10 11:28:39.705 ThaliTest[1061:1626535] multipeer manager: restart client
,2016-03-10 11:28:39.718 ThaliTest[1061:1626535] client: found existing peer: 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:5
,2016-03-10 11:28:59.705 ThaliTest[1061:1626535] multipeer manager: restart client
,2016-03-10 11:28:59.720 ThaliTest[1061:1626535] client: found existing peer: 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:5
,2016-03-10 11:29:19.705 ThaliTest[1061:1626535] multipeer manager: restart client
,2016-03-10 11:29:19.718 ThaliTest[1061:1626535] client: found existing peer: 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:5
,2016-03-10 11:29:39.705 ThaliTest[1061:1626535] multipeer manager: restart client
,2016-03-10 11:29:39.719 ThaliTest[1061:1626535] client: found existing peer: 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:5
,2016-03-10 11:29:59.705 ThaliTest[1061:1626535] multipeer manager: restart client
,2016-03-10 11:29:59.717 ThaliTest[1061:1626535] client: found existing peer: 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:5
,2016-03-10 11:30:19.705 ThaliTest[1061:1626535] multipeer manager: restart client
,2016-03-10 11:30:19.718 ThaliTest[1061:1626535] client: found existing peer: 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:5
,2016-03-10 11:30:39.705 ThaliTest[1061:1626535] multipeer manager: restart client
,2016-03-10 11:30:39.719 ThaliTest[1061:1626535] client: found existing peer: 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:5
,2016-03-10 11:30:59.705 ThaliTest[1061:1626535] multipeer manager: restart client
,2016-03-10 11:30:59.720 ThaliTest[1061:1626535] client: found existing peer: 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:5
,2016-03-10 11:31:19.705 ThaliTest[1061:1626535] multipeer manager: restart client
,2016-03-10 11:31:19.717 ThaliTest[1061:1626535] client: found existing peer: 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:5
,2016-03-10 11:31:39.705 ThaliTest[1061:1626535] multipeer manager: restart client
,2016-03-10 11:31:39.718 ThaliTest[1061:1626535] client: found existing peer: 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:5
,2016-03-10 11:31:59.705 ThaliTest[1061:1626535] multipeer manager: restart client
,2016-03-10 11:31:59.720 ThaliTest[1061:1626535] client: found existing peer: 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:5
,2016-03-10 11:32:19.705 ThaliTest[1061:1626535] multipeer manager: restart client
,2016-03-10 11:32:19.718 ThaliTest[1061:1626535] client: found existing peer: 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:5
,2016-03-10 11:32:39.704 ThaliTest[1061:1626535] multipeer manager: restart client
,2016-03-10 11:32:39.718 ThaliTest[1061:1626535] client: found existing peer: 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:5
,2016-03-10 11:32:59.705 ThaliTest[1061:1626535] multipeer manager: restart client
,2016-03-10 11:32:59.719 ThaliTest[1061:1626535] client: found existing peer: 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:5
,2016-03-10 11:33:19.705 ThaliTest[1061:1626535] multipeer manager: restart client
,2016-03-10 11:33:19.717 ThaliTest[1061:1626535] client: found existing peer: 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:5

```
