#### Test 613623667b1a8f4_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/613623667b1a8f4/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/88A9019B-A54E-4781-8411-7090989E5AF5/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/88A9019B-A54E-4781-8411-7090989E5AF5/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/613623667b1a8f4/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/613623667b1a8f4/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/635AAB08-7221-43A0-A636-DEC7D8E81321/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50994"
,(lldb)     command script import "/tmp/88A9019B-A54E-4781-8411-7090989E5AF5/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-10 16:22:43.000 ThaliTest[1090:1660650] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/240E0F91-5603-4491-95B1-2B5F2FA90160/Library/Cookies/Cookies.binarycookies
,2016-03-10 16:22:43.419 ThaliTest[1090:1660650] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-10 16:22:43.420 ThaliTest[1090:1660650] Multi-tasking -> Device: YES, App: YES
,2016-03-10 16:22:43.438 ThaliTest[1090:1660650] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-10 16:22:45.398 ThaliTest[1090:1660650] Using UIWebView
,2016-03-10 16:22:45.407 ThaliTest[1090:1660650] [CDVTimer][handleopenurl] 0.391960ms
,2016-03-10 16:22:45.414 ThaliTest[1090:1660650] [CDVTimer][intentandnavigationfilter] 6.740987ms
,2016-03-10 16:22:45.415 ThaliTest[1090:1660650] [CDVTimer][gesturehandler] 0.325024ms
2016-03-10 16:22:45.415 ThaliTest[1090:1660650] [CDVTimer][TotalPluginStartup] 9.097993ms
,2016-03-10 16:22:52.671 ThaliTest[1090:1660650] Resetting plugins due to page load.
,2016-03-10 16:22:56.124 ThaliTest[1090:1660650] Finished load of: file:///var/mobile/Containers/Bundle/Application/635AAB08-7221-43A0-A636-DEC7D8E81321/ThaliTest.app/www/index.html
,2016-03-10 16:22:56.324 ThaliTest[1090:1660650] JXcore Cordova plugin initializing
,2016-03-10 16:22:56.325 ThaliTest[1090:1660876] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,INFO testUtils Toggling radios to: true

,Unit Test app is loaded

,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/635AAB08-7221-43A0-A636-DEC7D8E81321/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/635AAB08-7221-43A0-A636-DEC7D8E81321/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/635AAB08-7221-43A0-A636-DEC7D8E81321/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/635AAB08-7221-43A0-A636-DEC7D8E81321/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-10 16:23:07.968 ThaliTest[1090:1660876] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-10 16:23:07.969 ThaliTest[1090:1660876] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-10 16:23:07.969 ThaliTest[1090:1660876] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

,2016-03-10 16:23:07.970 ThaliTest[1090:1660876] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/635AAB08-7221-43A0-A636-DEC7D8E81321/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/635AAB08-7221-43A0-A636-DEC7D8E81321/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/635AAB08-7221-43A0-A636-DEC7D8E81321/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/635AAB08-7221-43A0-A636-DEC7D8E81321/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/635AAB08-7221-43A0-A636-DEC7D8E81321/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/635AAB08-7221-43A0-A636-DEC7D8E81321/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/635AAB08-7221-43A0-A636-DEC7D8E81321/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/635AAB08-7221-43A0-A636-DEC7D8E81321/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/635AAB08-7221-43A0-A636-DEC7D8E81321/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/635AAB08-7221-43A0-A636-DEC7D8E81321/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

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

,2016-03-10 16:26:07.796 ThaliTest[1090:1660876] jxcore: startListeningForAdvertisements
,2016-03-10 16:26:07.797 ThaliTest[1090:1660876] multipeer manager: start client restart timer: 0x17ddc730
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}

,2016-03-10 16:26:07.800 ThaliTest[1090:1660876] jxcore: startListeningForAdvertisements: success
,ok 83 Can call startListeningForAdvertisements without error

,2016-03-10 16:26:07.807 ThaliTest[1090:1660876] jxcore: stopListeningForAdvertisements
,2016-03-10 16:26:07.809 ThaliTest[1090:1660876] multipeer manager: stop client timer
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}

,2016-03-10 16:26:07.812 ThaliTest[1090:1660876] jxcore: stopListeningForAdvertisements: success
,ok 84 Can call stopListeningForAdvertisements without error

,# setup

,2016-03-10 16:26:08.141 ThaliTest[1090:1660876] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}

,2016-03-10 16:26:08.142 ThaliTest[1090:1660876] jxcore: stopListeningForAdvertisements: success
,ok 85 Should be able to call stopListeningForAdvertisments in teardown

,2016-03-10 16:26:08.145 ThaliTest[1090:1660876] jxcore: stopAdvertisingAndListening
,2016-03-10 16:26:08.145 ThaliTest[1090:1660876] THEMultipeerManager stopping peer
,2016-03-10 16:26:08.146 ThaliTest[1090:1660876] jxcore: stopAdvertisingAndListening: success
,ok 86 Should be able to call stopAdvertisingAndListening in teardown

,# 20. Calling startListeningForAdvertisements twice is NOT an error

,# teardown

,2016-03-10 16:26:08.694 ThaliTest[1090:1660876] jxcore: startListeningForAdvertisements
,2016-03-10 16:26:08.696 ThaliTest[1090:1660876] multipeer manager: start client restart timer: 0x17ddc730
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}

,2016-03-10 16:26:08.698 ThaliTest[1090:1660876] jxcore: startListeningForAdvertisements: success
ok 87 Can call startListeningForAdvertisements without error

2016-03-10 16:26:08.700 ThaliTest[1090:1660876] jxcore: startListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}

,2016-03-10 16:26:08.703 ThaliTest[1090:1660876] jxcore: startListeningForAdvertisements: success
,ok 88 Can call startListeningForAdvertisements twice without error

,# setup

,2016-03-10 16:26:09.106 ThaliTest[1090:1660876] jxcore: stopListeningForAdvertisements
,2016-03-10 16:26:09.107 ThaliTest[1090:1660876] multipeer manager: stop client timer
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}

2016-03-10 16:26:09.109 ThaliTest[1090:1660876] jxcore: stopListeningForAdvertisements: success
,ok 89 Should be able to call stopListeningForAdvertisments in teardown

,2016-03-10 16:26:09.113 ThaliTest[1090:1660876] jxcore: stopAdvertisingAndListening
,2016-03-10 16:26:09.113 ThaliTest[1090:1660876] THEMultipeerManager stopping peer
,2016-03-10 16:26:09.114 ThaliTest[1090:1660876] jxcore: stopAdvertisingAndListening: success
,ok 90 Should be able to call stopAdvertisingAndListening in teardown

,# 21. Can call start/stopUpdateAdvertisingAndListening

,# teardown

,2016-03-10 16:26:09.618 ThaliTest[1090:1660876] jxcore: startUpdateAdvertisingAndListening
,2016-03-10 16:26:09.619 ThaliTest[1090:1660876] server: starting 2DDCB564-8D3A-4BFA-B857-963B8512EB44:1
,2016-03-10 16:26:09.620 ThaliTest[1090:1660876] multipeer manager: start client restart timer: 0x17ddc730
,2016-03-10 16:26:09.621 ThaliTest[1090:1660876] THEMultipeerManager initialized peer 2DDCB564-8D3A-4BFA-B857-963B8512EB44:1
2016-03-10 16:26:09.622 ThaliTest[1090:1660876] jxcore: startUpdateAdvertisingAndListening: success
ok 91 Can call startUpdateAdvertisingAndListening without error

,2016-03-10 16:26:09.625 ThaliTest[1090:1660876] jxcore: stopAdvertisingAndListening
2016-03-10 16:26:09.626 ThaliTest[1090:1660876] THEMultipeerManager stopping peer
2016-03-10 16:26:09.626 ThaliTest[1090:1660876] multipeer manager: stop client timer
20,16-03-10 16:26:09.627 ThaliTest[1090:1660876] jxcore: stopAdvertisingAndListening: success
ok 92 Can call stopAdvertisingAndListening without error

,# setup

,2016-03-10 16:26:09.778 ThaliTest[1090:1660876] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}

,2016-03-10 16:26:09.781 ThaliTest[1090:1660876] jxcore: stopListeningForAdvertisements: success
,ok 93 Should be able to call stopListeningForAdvertisments in teardown

,2016-03-10 16:26:09.783 ThaliTest[1090:1660876] jxcore: stopAdvertisingAndListening
,2016-03-10 16:26:09.783 ThaliTest[1090:1660876] THEMultipeerManager stopping peer
2016-03-10 16:26:09.784 ThaliTest[1090:1660876] jxcore: stopAdvertisingAndListening: success
,ok 94 Should be able to call stopAdvertisingAndListening in teardown

,# 22. Calling startUpdateAdvertisingAndListening twice is NOT an error

,# teardown

,2016-03-10 16:26:10.262 ThaliTest[1090:1660876] jxcore: startUpdateAdvertisingAndListening
,2016-03-10 16:26:10.263 ThaliTest[1090:1660876] server: starting 2DDCB564-8D3A-4BFA-B857-963B8512EB44:2
,2016-03-10 16:26:10.264 ThaliTest[1090:1660876] multipeer manager: start client restart timer: 0x17ddc730
2016-03-10 16:26:10.264 ThaliTest[1090:1660876] THEMultipeerManager initialized peer 2DDCB564-8D3A-4BFA-B857-963B8512EB44:2
2016-03-10 16:26:10.264 ThaliTest[1090:1660876] jxcore: startUpdateAdvertisingAndListening: success
ok 95 Can call startUpdateAdvertisingAndListening without error

,2016-03-10 16:26:10.268 ThaliTest[1090:1660876] jxcore: startUpdateAdvertisingAndListening
2016-03-10 16:26:10.268 ThaliTest[1090:1660876] THEMultipeerManager stopping peer
2016-03-10 16:26:10.268 ThaliTest[1090:1660876] multipeer manager: stop client ti,mer
2016-03-10 16:26:10.269 ThaliTest[1090:1660876] server: starting 2DDCB564-8D3A-4BFA-B857-963B8512EB44:3
2016-03-10 16:26:10.269 ThaliTest[1090:1660876] multipeer manager: start client restart timer: 0x17ddc730
2016-03-10 16:26:10.270 ThaliTest[1090:,1660876] THEMultipeerManager initialized peer 2DDCB564-8D3A-4BFA-B857-963B8512EB44:3
2016-03-10 16:26:10.270 ThaliTest[1090:1660876] jxcore: startUpdateAdvertisingAndListening: success
ok 96 Can call startUpdateAdvertisingAndListening twice without error

,# setup

,2016-03-10 16:26:10.383 ThaliTest[1090:1660876] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}

,2016-03-10 16:26:10.385 ThaliTest[1090:1660876] jxcore: stopListeningForAdvertisements: success
,ok 97 Should be able to call stopListeningForAdvertisments in teardown

,2016-03-10 16:26:10.387 ThaliTest[1090:1660876] jxcore: stopAdvertisingAndListening
,2016-03-10 16:26:10.388 ThaliTest[1090:1660876] THEMultipeerManager stopping peer
,2016-03-10 16:26:10.389 ThaliTest[1090:1660876] multipeer manager: stop client timer
2016-03-10 16:26:10.389 ThaliTest[1090:1660876] jxcore: stopAdvertisingAndListening: success
,ok 98 Should be able to call stopAdvertisingAndListening in teardown

,# 23. peerAvailabilityChange is called

,# teardown

,2016-03-10 16:26:10.804 ThaliTest[1090:1660876] jxcore: startUpdateAdvertisingAndListening
,2016-03-10 16:26:10.804 ThaliTest[1090:1660876] server: starting 2DDCB564-8D3A-4BFA-B857-963B8512EB44:4
,2016-03-10 16:26:10.805 ThaliTest[1090:1660876] multipeer manager: start client restart timer: 0x17ddc730
2016-03-10 16:26:10.806 ThaliTest[1090:1660876] THEMultipeerManager initialized peer 2DDCB564-8D3A-4BFA-B857-963B8512EB44:4
2016-03-10 16:26:10.806 ThaliTest[1090:1660876] jxcore: startUpdateAdvertisingAndListening: success
ok 99 Can call startUpdateAdvertisingAndListeningwithout error

,2016-03-10 16:26:10.808 ThaliTest[1090:1660876] jxcore: startListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}

2016-03-10 16:26:10.811 ThaliTest[1090:1660876] jxcore: startListeningForAdvertisements: success
ok 100 Can call startListeningForAdvertisements without error

,2016-03-10 16:26:11.849 ThaliTest[1090:1660650] client: found new peer: C9491499-6B46-498D-8C3C-073CDE82501E:4
,ok 101 peers must be an array

,ok 102 peers must not be zero-length

,ok 103 peer must have peerIdentifier

,ok 104 peerIdentifier must be a string

,ok 105 peer must have peerAvailable

,ok 106 peer must have pleaseConnect

,# setup

,2016-03-10 16:26:12.746 ThaliTest[1090:1660876] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}

,2016-03-10 16:26:12.747 ThaliTest[1090:1660876] jxcore: stopListeningForAdvertisements: success
,ok 107 Should be able to call stopListeningForAdvertisments in teardown

,2016-03-10 16:26:12.750 ThaliTest[1090:1660876] jxcore: stopAdvertisingAndListening
,2016-03-10 16:26:12.750 ThaliTest[1090:1660876] THEMultipeerManager stopping peer
,2016-03-10 16:26:12.751 ThaliTest[1090:1660876] multipeer manager: stop client timer
,2016-03-10 16:26:12.756 ThaliTest[1090:1660876] jxcore: stopAdvertisingAndListening: success
,ok 108 Should be able to call stopAdvertisingAndListening in teardown

,# 24. Can connect to a remote peer

,# teardown

,2016-03-10 16:26:13.240 ThaliTest[1090:1660876] jxcore: startUpdateAdvertisingAndListening
,2016-03-10 16:26:13.240 ThaliTest[1090:1660876] server: starting 2DDCB564-8D3A-4BFA-B857-963B8512EB44:5
,2016-03-10 16:26:13.242 ThaliTest[1090:1660876] multipeer manager: start client restart timer: 0x17ddc730
2016-03-10 16:26:13.242 ThaliTest[1090:1660876] THEMultipeerManager initialized peer 2DDCB564-8D3A-4BFA-B857-963B8512EB44:5
2016-03-10 16:26:13.243 ThaliTest[1090:1660876] jxcore: startUpdateAdvertisingAndListening: success
ok 109 Can call startUpdateAdvertisingAndListening without error

,2016-03-10 16:26:13.246 ThaliTest[1090:1660876] jxcore: startListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}

2016-03-10 16:26:13.247 ThaliTest[1090:1660876] jxcore: startListeningForAdvertisements: success
ok 110 Can call startListeningForAdvertisements without error

,2016-03-10 16:26:13.983 ThaliTest[1090:1660650] client: found new peer: C9491499-6B46-498D-8C3C-073CDE82501E:4
,2016-03-10 16:26:13.985 ThaliTest[1090:1660876] jxcore: connect C9491499-6B46-498D-8C3C-073CDE82501E:4
,2016-03-10 16:26:13.986 ThaliTest[1090:1660876] client: server will connect
2016-03-10 16:26:13.987 ThaliTest[1090:1660876] client session: reverseConnect
,2016-03-10 16:26:13.987 ThaliTest[1090:1660876] client session: stateChange:0->1 C9491499-6B46-498D-8C3C-073CDE82501E:4
,2016-03-10 16:26:14.464 ThaliTest[1090:1661226] client session: not connected C9491499-6B46-498D-8C3C-073CDE82501E:4
,2016-03-10 16:26:14.465 ThaliTest[1090:1661226] client session: onLinkFailure: C9491499-6B46-498D-8C3C-073CDE82501E
2016-03-10 16:26:14.466 ThaliTest[1090:1661226] client session: disconnect
,2016-03-10 16:26:14.466 ThaliTest[1090:1661226] client session: stateChange:1->0 C9491499-6B46-498D-8C3C-073CDE82501E:4
,2016-03-10 16:26:14.467 ThaliTest[1090:1661226] client session: no connect callback (server initiated)
,2016-03-10 16:26:15.363 ThaliTest[1090:1660650] multipeer session: reset timer
,2016-03-10 16:26:15.363 ThaliTest[1090:1660650] server: rejecting invitation from C9491499-6B46-498D-8C3C-073CDE82501E due to previous generation (2DDCB564-8D3A-4BFA-B857-963B8512EB44:5 != 2DDCB564-8D3A-4BFA-B857-963B8512EB44:4)
,2016-03-10 16:26:33.243 ThaliTest[1090:1660650] multipeer manager: restart client
,2016-03-10 16:26:33.257 ThaliTest[1090:1660650] client: found updated peer: C9491499-6B46-498D-8C3C-073CDE82501E:5
,2016-03-10 16:26:53.243 ThaliTest[1090:1660650] multipeer manager: restart client
,2016-03-10 16:26:53.257 ThaliTest[1090:1660650] client: found existing peer: C9491499-6B46-498D-8C3C-073CDE82501E:5
,2016-03-10 16:27:13.243 ThaliTest[1090:1660650] multipeer manager: restart client
,2016-03-10 16:27:13.255 ThaliTest[1090:1660650] client: found existing peer: C9491499-6B46-498D-8C3C-073CDE82501E:5
,2016-03-10 16:27:33.243 ThaliTest[1090:1660650] multipeer manager: restart client
,2016-03-10 16:27:33.257 ThaliTest[1090:1660650] client: found existing peer: C9491499-6B46-498D-8C3C-073CDE82501E:5
,2016-03-10 16:27:53.243 ThaliTest[1090:1660650] multipeer manager: restart client
,2016-03-10 16:27:53.258 ThaliTest[1090:1660650] client: found existing peer: C9491499-6B46-498D-8C3C-073CDE82501E:5
,2016-03-10 16:28:13.243 ThaliTest[1090:1660650] multipeer manager: restart client
,2016-03-10 16:28:13.258 ThaliTest[1090:1660650] client: found existing peer: C9491499-6B46-498D-8C3C-073CDE82501E:5
,2016-03-10 16:28:33.243 ThaliTest[1090:1660650] multipeer manager: restart client
,2016-03-10 16:28:33.257 ThaliTest[1090:1660650] client: found existing peer: C9491499-6B46-498D-8C3C-073CDE82501E:5
,2016-03-10 16:28:53.243 ThaliTest[1090:1660650] multipeer manager: restart client
,2016-03-10 16:28:53.256 ThaliTest[1090:1660650] client: found existing peer: C9491499-6B46-498D-8C3C-073CDE82501E:5
,2016-03-10 16:29:13.243 ThaliTest[1090:1660650] multipeer manager: restart client
,2016-03-10 16:29:13.257 ThaliTest[1090:1660650] client: found existing peer: C9491499-6B46-498D-8C3C-073CDE82501E:5
,2016-03-10 16:29:33.242 ThaliTest[1090:1660650] multipeer manager: restart client
,2016-03-10 16:29:33.257 ThaliTest[1090:1660650] client: found existing peer: C9491499-6B46-498D-8C3C-073CDE82501E:5
,2016-03-10 16:29:53.243 ThaliTest[1090:1660650] multipeer manager: restart client
,2016-03-10 16:29:53.257 ThaliTest[1090:1660650] client: found existing peer: C9491499-6B46-498D-8C3C-073CDE82501E:5
,2016-03-10 16:30:13.243 ThaliTest[1090:1660650] multipeer manager: restart client
,2016-03-10 16:30:13.256 ThaliTest[1090:1660650] client: found existing peer: C9491499-6B46-498D-8C3C-073CDE82501E:5
,2016-03-10 16:30:33.243 ThaliTest[1090:1660650] multipeer manager: restart client
,2016-03-10 16:30:33.257 ThaliTest[1090:1660650] client: found existing peer: C9491499-6B46-498D-8C3C-073CDE82501E:5
,2016-03-10 16:30:53.243 ThaliTest[1090:1660650] multipeer manager: restart client
,2016-03-10 16:30:53.257 ThaliTest[1090:1660650] client: found existing peer: C9491499-6B46-498D-8C3C-073CDE82501E:5
,2016-03-10 16:31:13.243 ThaliTest[1090:1660650] multipeer manager: restart client
,2016-03-10 16:31:13.258 ThaliTest[1090:1660650] client: found existing peer: C9491499-6B46-498D-8C3C-073CDE82501E:5
,2016-03-10 16:31:33.243 ThaliTest[1090:1660650] multipeer manager: restart client
,2016-03-10 16:31:33.258 ThaliTest[1090:1660650] client: found existing peer: C9491499-6B46-498D-8C3C-073CDE82501E:5
,2016-03-10 16:31:53.243 ThaliTest[1090:1660650] multipeer manager: restart client
,2016-03-10 16:31:53.257 ThaliTest[1090:1660650] client: found existing peer: C9491499-6B46-498D-8C3C-073CDE82501E:5
,2016-03-10 16:32:13.243 ThaliTest[1090:1660650] multipeer manager: restart client
,2016-03-10 16:32:13.258 ThaliTest[1090:1660650] client: found existing peer: C9491499-6B46-498D-8C3C-073CDE82501E:5
,2016-03-10 16:32:33.243 ThaliTest[1090:1660650] multipeer manager: restart client
,2016-03-10 16:32:33.258 ThaliTest[1090:1660650] client: found existing peer: C9491499-6B46-498D-8C3C-073CDE82501E:5
,2016-03-10 16:32:53.243 ThaliTest[1090:1660650] multipeer manager: restart client
,2016-03-10 16:32:53.258 ThaliTest[1090:1660650] client: found existing peer: C9491499-6B46-498D-8C3C-073CDE82501E:5
,2016-03-10 16:33:13.243 ThaliTest[1090:1660650] multipeer manager: restart client
,2016-03-10 16:33:13.257 ThaliTest[1090:1660650] client: found existing peer: C9491499-6B46-498D-8C3C-073CDE82501E:5
,2016-03-10 16:33:33.243 ThaliTest[1090:1660650] multipeer manager: restart client
,2016-03-10 16:33:33.258 ThaliTest[1090:1660650] client: found existing peer: C9491499-6B46-498D-8C3C-073CDE82501E:5
,2016-03-10 16:33:53.243 ThaliTest[1090:1660650] multipeer manager: restart client
,2016-03-10 16:33:53.258 ThaliTest[1090:1660650] client: found existing peer: C9491499-6B46-498D-8C3C-073CDE82501E:5
,2016-03-10 16:34:13.243 ThaliTest[1090:1660650] multipeer manager: restart client
,2016-03-10 16:34:13.257 ThaliTest[1090:1660650] client: found existing peer: C9491499-6B46-498D-8C3C-073CDE82501E:5
,2016-03-10 16:34:33.243 ThaliTest[1090:1660650] multipeer manager: restart client
,2016-03-10 16:34:33.257 ThaliTest[1090:1660650] client: found existing peer: C9491499-6B46-498D-8C3C-073CDE82501E:5
,2016-03-10 16:34:53.243 ThaliTest[1090:1660650] multipeer manager: restart client
,2016-03-10 16:34:53.257 ThaliTest[1090:1660650] client: found existing peer: C9491499-6B46-498D-8C3C-073CDE82501E:5
,2016-03-10 16:35:13.243 ThaliTest[1090:1660650] multipeer manager: restart client
,2016-03-10 16:35:13.257 ThaliTest[1090:1660650] client: found existing peer: C9491499-6B46-498D-8C3C-073CDE82501E:5
,2016-03-10 16:35:33.243 ThaliTest[1090:1660650] multipeer manager: restart client
,2016-03-10 16:35:33.257 ThaliTest[1090:1660650] client: found existing peer: C9491499-6B46-498D-8C3C-073CDE82501E:5
,2016-03-10 16:35:53.243 ThaliTest[1090:1660650] multipeer manager: restart client
,2016-03-10 16:35:53.258 ThaliTest[1090:1660650] client: found existing peer: C9491499-6B46-498D-8C3C-073CDE82501E:5
,2016-03-10 16:36:13.243 ThaliTest[1090:1660650] multipeer manager: restart client
,2016-03-10 16:36:13.258 ThaliTest[1090:1660650] client: found existing peer: C9491499-6B46-498D-8C3C-073CDE82501E:5
,2016-03-10 16:36:33.243 ThaliTest[1090:1660650] multipeer manager: restart client
,2016-03-10 16:36:33.258 ThaliTest[1090:1660650] client: found existing peer: C9491499-6B46-498D-8C3C-073CDE82501E:5
,2016-03-10 16:36:53.243 ThaliTest[1090:1660650] multipeer manager: restart client
,2016-03-10 16:36:53.256 ThaliTest[1090:1660650] client: found existing peer: C9491499-6B46-498D-8C3C-073CDE82501E:5
,2016-03-10 16:37:13.243 ThaliTest[1090:1660650] multipeer manager: restart client
,2016-03-10 16:37:13.256 ThaliTest[1090:1660650] client: found existing peer: C9491499-6B46-498D-8C3C-073CDE82501E:5
,2016-03-10 16:37:33.243 ThaliTest[1090:1660650] multipeer manager: restart client
,2016-03-10 16:37:33.259 ThaliTest[1090:1660650] client: found existing peer: C9491499-6B46-498D-8C3C-073CDE82501E:5
,2016-03-10 16:37:53.243 ThaliTest[1090:1660650] multipeer manager: restart client
,2016-03-10 16:37:53.257 ThaliTest[1090:1660650] client: found existing peer: C9491499-6B46-498D-8C3C-073CDE82501E:5
,2016-03-10 16:38:13.243 ThaliTest[1090:1660650] multipeer manager: restart client
,2016-03-10 16:38:13.258 ThaliTest[1090:1660650] client: found existing peer: C9491499-6B46-498D-8C3C-073CDE82501E:5
,2016-03-10 16:38:33.243 ThaliTest[1090:1660650] multipeer manager: restart client
,2016-03-10 16:38:33.258 ThaliTest[1090:1660650] client: found existing peer: C9491499-6B46-498D-8C3C-073CDE82501E:5
,2016-03-10 16:38:53.243 ThaliTest[1090:1660650] multipeer manager: restart client
,2016-03-10 16:38:53.258 ThaliTest[1090:1660650] client: found existing peer: C9491499-6B46-498D-8C3C-073CDE82501E:5
,2016-03-10 16:39:13.243 ThaliTest[1090:1660650] multipeer manager: restart client
,2016-03-10 16:39:13.257 ThaliTest[1090:1660650] client: found existing peer: C9491499-6B46-498D-8C3C-073CDE82501E:5
,2016-03-10 16:39:33.229 ThaliTest[1090:1660650] multipeer manager: restart client
,2016-03-10 16:39:33.243 ThaliTest[1090:1660650] client: found existing peer: C9491499-6B46-498D-8C3C-073CDE82501E:5
,2016-03-10 16:39:53.229 ThaliTest[1090:1660650] multipeer manager: restart client
,2016-03-10 16:39:53.242 ThaliTest[1090:1660650] client: found existing peer: C9491499-6B46-498D-8C3C-073CDE82501E:5
,2016-03-10 16:40:13.229 ThaliTest[1090:1660650] multipeer manager: restart client
,2016-03-10 16:40:13.243 ThaliTest[1090:1660650] client: found existing peer: C9491499-6B46-498D-8C3C-073CDE82501E:5
,2016-03-10 16:40:33.229 ThaliTest[1090:1660650] multipeer manager: restart client
,2016-03-10 16:40:33.242 ThaliTest[1090:1660650] client: found existing peer: C9491499-6B46-498D-8C3C-073CDE82501E:5
,2016-03-10 16:40:53.229 ThaliTest[1090:1660650] multipeer manager: restart client
,2016-03-10 16:40:53.242 ThaliTest[1090:1660650] client: found existing peer: C9491499-6B46-498D-8C3C-073CDE82501E:5
,2016-03-10 16:41:13.229 ThaliTest[1090:1660650] multipeer manager: restart client
,2016-03-10 16:41:13.243 ThaliTest[1090:1660650] client: found existing peer: C9491499-6B46-498D-8C3C-073CDE82501E:5
,2016-03-10 16:41:33.229 ThaliTest[1090:1660650] multipeer manager: restart client
,2016-03-10 16:41:33.244 ThaliTest[1090:1660650] client: found existing peer: C9491499-6B46-498D-8C3C-073CDE82501E:5
,2016-03-10 16:41:53.229 ThaliTest[1090:1660650] multipeer manager: restart client
,2016-03-10 16:41:53.242 ThaliTest[1090:1660650] client: found existing peer: C9491499-6B46-498D-8C3C-073CDE82501E:5
,2016-03-10 16:42:13.229 ThaliTest[1090:1660650] multipeer manager: restart client
,2016-03-10 16:42:13.244 ThaliTest[1090:1660650] client: found existing peer: C9491499-6B46-498D-8C3C-073CDE82501E:5
,2016-03-10 16:42:33.229 ThaliTest[1090:1660650] multipeer manager: restart client
,2016-03-10 16:42:33.244 ThaliTest[1090:1660650] client: found existing peer: C9491499-6B46-498D-8C3C-073CDE82501E:5
,2016-03-10 16:42:53.229 ThaliTest[1090:1660650] multipeer manager: restart client
,2016-03-10 16:42:53.243 ThaliTest[1090:1660650] client: found existing peer: C9491499-6B46-498D-8C3C-073CDE82501E:5
,2016-03-10 16:43:13.229 ThaliTest[1090:1660650] multipeer manager: restart client
,2016-03-10 16:43:13.242 ThaliTest[1090:1660650] client: found existing peer: C9491499-6B46-498D-8C3C-073CDE82501E:5
,2016-03-10 16:43:33.228 ThaliTest[1090:1660650] multipeer manager: restart client
,2016-03-10 16:43:33.242 ThaliTest[1090:1660650] client: found existing peer: C9491499-6B46-498D-8C3C-073CDE82501E:5
,2016-03-10 16:43:53.229 ThaliTest[1090:1660650] multipeer manager: restart client
,2016-03-10 16:43:53.243 ThaliTest[1090:1660650] client: found existing peer: C9491499-6B46-498D-8C3C-073CDE82501E:5

```
