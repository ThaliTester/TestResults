#### Test 61362366b6c9a6f_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/61362366b6c9a6f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/33E36A63-392B-43C3-AA83-DC04CD3A7932/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/33E36A63-392B-43C3-AA83-DC04CD3A7932/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/61362366b6c9a6f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/61362366b6c9a6f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B68C3E0B-E7ED-41C1-936E-7A3C95C38FD4/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50511"
,(lldb)     command script import "/tmp/33E36A63-392B-43C3-AA83-DC04CD3A7932/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-10 09:35:35.376 ThaliTest[804:1720635] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E9C7089A-DF1E-4BB1-AF71-50187AFE5E83/Library/Cookies/Cookies.binarycookies
,2016-03-10 09:35:35.502 ThaliTest[804:1720635] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-10 09:35:35.505 ThaliTest[804:1720635] Multi-tasking -> Device: YES, App: YES
,2016-03-10 09:35:35.525 ThaliTest[804:1720635] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-10 09:35:37.611 ThaliTest[804:1720635] Using UIWebView
,2016-03-10 09:35:37.616 ThaliTest[804:1720635] [CDVTimer][handleopenurl] 0.393033ms
,2016-03-10 09:35:37.621 ThaliTest[804:1720635] [CDVTimer][intentandnavigationfilter] 5.232036ms
2016-03-10 09:35:37.622 ThaliTest[804:1720635] [CDVTimer][gesturehandler] 0.257969ms
2016-03-10 09:35:37.622 ThaliTest[804:1720635] [CDVTimer][TotalPluginStartup] 6.913006ms
,2016-03-10 09:35:45.963 ThaliTest[804:1720635] Resetting plugins due to page load.
,2016-03-10 09:35:50.363 ThaliTest[804:1720635] Finished load of: file:///var/mobile/Containers/Bundle/Application/B68C3E0B-E7ED-41C1-936E-7A3C95C38FD4/ThaliTest.app/www/index.html
,2016-03-10 09:35:50.569 ThaliTest[804:1720635] JXcore Cordova plugin initializing
,2016-03-10 09:35:50.571 ThaliTest[804:1720816] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,INFO testUtils Toggling radios to: true

,Unit Test app is loaded

,My device name is: Apple-Iphone5-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B68C3E0B-E7ED-41C1-936E-7A3C95C38FD4/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B68C3E0B-E7ED-41C1-936E-7A3C95C38FD4/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B68C3E0B-E7ED-41C1-936E-7A3C95C38FD4/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B68C3E0B-E7ED-41C1-936E-7A3C95C38FD4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-10 09:36:12.305 ThaliTest[804:1720816] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-10 09:36:12.307 ThaliTest[804:1720816] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-10 09:36:12.307 ThaliTest[804:1720816] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

,2016-03-10 09:36:12.309 ThaliTest[804:1720816] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B68C3E0B-E7ED-41C1-936E-7A3C95C38FD4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B68C3E0B-E7ED-41C1-936E-7A3C95C38FD4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B68C3E0B-E7ED-41C1-936E-7A3C95C38FD4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B68C3E0B-E7ED-41C1-936E-7A3C95C38FD4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B68C3E0B-E7ED-41C1-936E-7A3C95C38FD4/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B68C3E0B-E7ED-41C1-936E-7A3C95C38FD4/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B68C3E0B-E7ED-41C1-936E-7A3C95C38FD4/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B68C3E0B-E7ED-41C1-936E-7A3C95C38FD4/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B68C3E0B-E7ED-41C1-936E-7A3C95C38FD4/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B68C3E0B-E7ED-41C1-936E-7A3C95C38FD4/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

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

ok 37 error should be null

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

ok 61 first call should succeed

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

,2016-03-10 09:40:29.657 ThaliTest[804:1720816] jxcore: startListeningForAdvertisements
2016-03-10 09:40:29.657 ThaliTest[804:1720816] multipeer manager: start client restart timer: 0x17ec1a50
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}

2016-03-10 09:40:29.659 ThaliTest[804:1720816] jxcore: startListeningForAdvertisements: success
,ok 83 Can call startListeningForAdvertisements without error

2016-03-10 09:40:29.661 ThaliTest[804:1720816] jxcore: stopListeningForAdvertisements
2016-03-10 09:40:29.661 ThaliTest[804:1720816] multipeer manager: stop client timer
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}

2016-03-10 09:40:29.663 ThaliTest[804:1720816] jxcore: stopListeningForAdvertisements: success
ok 84 Can call stopListeningForAdvertisements without error

,# setup

,2016-03-10 09:40:29.777 ThaliTest[804:1720816] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}

,2016-03-10 09:40:29.778 ThaliTest[804:1720816] jxcore: stopListeningForAdvertisements: success
,ok 85 Should be able to call stopListeningForAdvertisments in teardown

,2016-03-10 09:40:29.780 ThaliTest[804:1720816] jxcore: stopAdvertisingAndListening
2016-03-10 09:40:29.780 ThaliTest[804:1720816] THEMultipeerManager stopping peer
2016-03-10 09:40:29.781 ThaliTest[804:1720816] jxcore: stopAdvertisingAndListening: success
ok 86 Should be able to call stopAdvertisingAndListening in teardown

,# 20. Calling startListeningForAdvertisements twice is NOT an error

,# teardown

,2016-03-10 09:40:30.459 ThaliTest[804:1720816] jxcore: startListeningForAdvertisements
2016-03-10 09:40:30.460 ThaliTest[804:1720816] multipeer manager: start client restart timer: 0x17ec1a50
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}

2016-03-10 09:40:30.461 ThaliTest[804:1720816] jxcore: startListeningForAdvertisements: success
ok 87 Can call startListeningForAdvertisements without error

2016-03-10 09:40:30.462 ThaliTest[804:1720816] jxcore: startListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}

2016-03-10 09:40:30.463 ThaliTest[804:1720816] jxcore: startListeningForAdvertisements: success
,ok 88 Can call startListeningForAdvertisements twice without error

,# setup

,2016-03-10 09:40:30.629 ThaliTest[804:1720816] jxcore: stopListeningForAdvertisements
2016-03-10 09:40:30.629 ThaliTest[804:1720816] multipeer manager: stop client timer
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}

2016-03-10 09:40:30.630 ThaliTest[804:1720816] jxcore: stopListeningForAdvertisements: success
,ok 89 Should be able to call stopListeningForAdvertisments in teardown

2016-03-10 09:40:30.632 ThaliTest[804:1720816] jxcore: stopAdvertisingAndListening
2016-03-10 09:40:30.632 ThaliTest[804:1720816] THEMultipeerManager stopping peer
2016-03-10 09:40,:30.632 ThaliTest[804:1720816] jxcore: stopAdvertisingAndListening: success
ok 90 Should be able to call stopAdvertisingAndListening in teardown

,# 21. Can call start/stopUpdateAdvertisingAndListening

,# teardown

,2016-03-10 09:40:33.279 ThaliTest[804:1720816] jxcore: startUpdateAdvertisingAndListening
2016-03-10 09:40:33.280 ThaliTest[804:1720816] server: starting DDDB0EC9-C034-47C5-8433-6E846CC55A9A:1
,2016-03-10 09:40:33.281 ThaliTest[804:1720816] multipeer manager: start client restart timer: 0x17ec1a50
2016-03-10 09:40:33.282 ThaliTest[804:1720816] THEMultipeerManager initialized peer DDDB0EC9-C034-47C5-8433-6E846CC55A9A:1
2016-03-10 09:40:33.282 Th,aliTest[804:1720816] jxcore: startUpdateAdvertisingAndListening: success
ok 91 Can call startUpdateAdvertisingAndListening without error

2016-03-10 09:40:33.284 ThaliTest[804:1720816] jxcore: stopAdvertisingAndListening
2016-03-10 09:40:33.284 ThaliTe,st[804:1720816] THEMultipeerManager stopping peer
2016-03-10 09:40:33.284 ThaliTest[804:1720816] multipeer manager: stop client timer
2016-03-10 09:40:33.285 ThaliTest[804:1720816] jxcore: stopAdvertisingAndListening: success
ok 92 Can call stopAdvertisingAndListening without error

,# setup

,2016-03-10 09:40:33.545 ThaliTest[804:1720816] jxcore: stopListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}

2016-03-10 09:40:33.546 ThaliTest[804:1720816] jxcore: stopListeningForAdvertisements: success
,ok 93 Should be able to call stopListeningForAdvertisments in teardown

,2016-03-10 09:40:33.548 ThaliTest[804:1720816] jxcore: stopAdvertisingAndListening
2016-03-10 09:40:33.548 ThaliTest[804:1720816] THEMultipeerManager stopping peer
,2016-03-10 09:40:33.548 ThaliTest[804:1720816] jxcore: stopAdvertisingAndListening: success
ok 94 Should be able to call stopAdvertisingAndListening in teardown

,# 22. Calling startUpdateAdvertisingAndListening twice is NOT an error

,# teardown

,2016-03-10 09:40:33.811 ThaliTest[804:1720816] jxcore: startUpdateAdvertisingAndListening
2016-03-10 09:40:33.811 ThaliTest[804:1720816] server: starting DDDB0EC9-C034-47C5-8433-6E846CC55A9A:2
2016-03-10 09:40:33.812 ThaliTest[804:1720816] multipeer mana,ger: start client restart timer: 0x17ec1a50
2016-03-10 09:40:33.812 ThaliTest[804:1720816] THEMultipeerManager initialized peer DDDB0EC9-C034-47C5-8433-6E846CC55A9A:2
2016-03-10 09:40:33.812 ThaliTest[804:1720816] jxcore: startUpdateAdvertisingAndListeni,ng: success
ok 95 Can call startUpdateAdvertisingAndListening without error

,2016-03-10 09:40:33.814 ThaliTest[804:1720816] jxcore: startUpdateAdvertisingAndListening
2016-03-10 09:40:33.814 ThaliTest[804:1720816] THEMultipeerManager stopping peer
2016-03-10 09:40:33.814 ThaliTest[804:1720816] multipeer manager: stop client timer,
2016-03-10 09:40:33.814 ThaliTest[804:1720816] server: starting DDDB0EC9-C034-47C5-8433-6E846CC55A9A:3
,2016-03-10 09:40:33.815 ThaliTest[804:1720816] multipeer manager: start client restart timer: 0x17ec1a50
2016-03-10 09:40:33.816 ThaliTest[804:1720816] THEMultipeerManager initialized peer DDDB0EC9-C034-47C5-8433-6E846CC55A9A:3
,2016-03-10 09:40:33.816 ThaliTest[804:1720816] jxcore: startUpdateAdvertisingAndListening: success
,ok 96 Can call startUpdateAdvertisingAndListening twice without error

# setup

,2016-03-10 09:40:34.066 ThaliTest[804:1720816] jxcore: stopListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}

,2016-03-10 09:40:34.067 ThaliTest[804:1720816] jxcore: stopListeningForAdvertisements: success
,ok 97 Should be able to call stopListeningForAdvertisments in teardown

2016-03-10 09:40:34.068 ThaliTest[804:1720816] jxcore: stopAdvertisingAndListening
2016-03-10 09:40:34.069 ThaliTest[804:1720816] THEMultipeerManager stopping peer
2016-03-10 09:40,:34.069 ThaliTest[804:1720816] multipeer manager: stop client timer
2016-03-10 09:40:34.069 ThaliTest[804:1720816] jxcore: stopAdvertisingAndListening: success
ok 98 Should be able to call stopAdvertisingAndListening in teardown

,# 23. peerAvailabilityChange is called

,# teardown

,2016-03-10 09:40:35.106 ThaliTest[804:1720816] jxcore: startUpdateAdvertisingAndListening
2016-03-10 09:40:35.106 ThaliTest[804:1720816] server: starting DDDB0EC9-C034-47C5-8433-6E846CC55A9A:4
2016-03-10 09:40:35.107 ThaliTest[804:1720816] multipeer mana,ger: start client restart timer: 0x17ec1a50
2016-03-10 09:40:35.107 ThaliTest[804:1720816] THEMultipeerManager initialized peer DDDB0EC9-C034-47C5-8433-6E846CC55A9A:4
2016-03-10 09:40:35.107 ThaliTest[804:1720816] jxcore: startUpdateAdvertisingAndListening: success
ok 99 Can call startUpdateAdvertisingAndListeningwithout error

,2016-03-10 09:40:35.109 ThaliTest[804:1720816] jxcore: startListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}

,2016-03-10 09:40:35.110 ThaliTest[804:1720816] jxcore: startListeningForAdvertisements: success
,ok 100 Can call startListeningForAdvertisements without error

,2016-03-10 09:40:38.372 ThaliTest[804:1720635] client: found new peer: EB1717B1-EA19-4A83-A99B-88282DEBD7B6:4
ok 101 peers must be an array

ok 102 peers must not be zero-length

ok 103 peer must have peerIdentifier

,ok 104 peerIdentifier must be a string

ok 105 peer must have peerAvailable

ok 106 peer must have pleaseConnect

,# setup

,2016-03-10 09:40:38.498 ThaliTest[804:1720816] jxcore: stopListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}

,2016-03-10 09:40:38.500 ThaliTest[804:1720816] jxcore: stopListeningForAdvertisements: success
,ok 107 Should be able to call stopListeningForAdvertisments in teardown

2016-03-10 09:40:38.501 ThaliTest[804:1720816] jxcore: stopAdvertisingAndListening
2016-03-10 09:40:38.501 ThaliTest[804:1720816] THEMultipeerManager stopping peer
2016-03-10 09:4,0:38.501 ThaliTest[804:1720816] multipeer manager: stop client timer
2016-03-10 09:40:38.502 ThaliTest[804:1720816] jxcore: stopAdvertisingAndListening: success
ok 108 Should be able to call stopAdvertisingAndListening in teardown

,# 24. Can connect to a remote peer

,# teardown

,2016-03-10 09:40:38.900 ThaliTest[804:1720816] jxcore: startUpdateAdvertisingAndListening
2016-03-10 09:40:38.900 ThaliTest[804:1720816] server: starting DDDB0EC9-C034-47C5-8433-6E846CC55A9A:5
2016-03-10 09:40:38.901 ThaliTest[804:1720816] multipeer mana,ger: start client restart timer: 0x17ec1a50
2016-03-10 09:40:38.901 ThaliTest[804:1720816] THEMultipeerManager initialized peer DDDB0EC9-C034-47C5-8433-6E846CC55A9A:5
2016-03-10 09:40:38.901 ThaliTest[804:1720816] jxcore: startUpdateAdvertisingAndListening: success
ok 109 Can call startUpdateAdvertisingAndListening without error

,2016-03-10 09:40:38.902 ThaliTest[804:1720816] jxcore: startListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}

,2016-03-10 09:40:38.904 ThaliTest[804:1720816] jxcore: startListeningForAdvertisements: success
,ok 110 Can call startListeningForAdvertisements without error

,2016-03-10 09:40:39.618 ThaliTest[804:1720635] client: found new peer: EB1717B1-EA19-4A83-A99B-88282DEBD7B6:4
,2016-03-10 09:40:39.620 ThaliTest[804:1720816] jxcore: connect EB1717B1-EA19-4A83-A99B-88282DEBD7B6:4
2016-03-10 09:40:39.621 ThaliTest[804:1720816] client: server will connect
2016-03-10 09:40:39.621 ThaliTest[804:1720816] client session: reverseConnect,
2016-03-10 09:40:39.621 ThaliTest[804:1720816] client session: stateChange:0->1 EB1717B1-EA19-4A83-A99B-88282DEBD7B6:4
,2016-03-10 09:40:46.785 ThaliTest[804:1720635] multipeer session: reset timer
2016-03-10 09:40:46.785 ThaliTest[804:1720635] server: rejecting invitation from EB1717B1-EA19-4A83-A99B-88282DEBD7B6 due to previous generation (DDDB0EC9-C034-47C5-8433-6E846CC55A9A:5 != DDDB0EC9-C034-47C5-8433-6E846CC55A9A:4)
,2016-03-10 09:40:47.970 ThaliTest[804:1721572] client session: not connected EB1717B1-EA19-4A83-A99B-88282DEBD7B6:4
2016-03-10 09:40:47.970 ThaliTest[804:1721572] client session: onLinkFailure: EB1717B1-EA19-4A83-A99B-88282DEBD7B6
,2016-03-10 09:40:47.970 ThaliTest[804:1721572] client session: disconnect
2016-03-10 09:40:47.971 ThaliTest[804:1721572] client session: stateChange:1->0 EB1717B1-EA19-4A83-A99B-88282DEBD7B6:4
2016-03-10 09:40:47.972 ThaliTest[804:1721572] client session: no connect callback (server initiated)
,2016-03-10 09:40:58.902 ThaliTest[804:1720635] multipeer manager: restart client
,2016-03-10 09:40:58.918 ThaliTest[804:1720635] client: found updated peer: EB1717B1-EA19-4A83-A99B-88282DEBD7B6:5
,2016-03-10 09:41:18.902 ThaliTest[804:1720635] multipeer manager: restart client
,2016-03-10 09:41:18.914 ThaliTest[804:1720635] client: found existing peer: EB1717B1-EA19-4A83-A99B-88282DEBD7B6:5
,2016-03-10 09:41:38.902 ThaliTest[804:1720635] multipeer manager: restart client
,2016-03-10 09:41:58.902 ThaliTest[804:1720635] multipeer manager: restart client
,2016-03-10 09:41:58.910 ThaliTest[804:1720635] client: found existing peer: EB1717B1-EA19-4A83-A99B-88282DEBD7B6:5
,2016-03-10 09:42:18.902 ThaliTest[804:1720635] multipeer manager: restart client
,2016-03-10 09:42:18.912 ThaliTest[804:1720635] client: found existing peer: EB1717B1-EA19-4A83-A99B-88282DEBD7B6:5
,2016-03-10 09:42:38.902 ThaliTest[804:1720635] multipeer manager: restart client
,2016-03-10 09:42:38.913 ThaliTest[804:1720635] client: found existing peer: EB1717B1-EA19-4A83-A99B-88282DEBD7B6:5
,2016-03-10 09:42:58.902 ThaliTest[804:1720635] multipeer manager: restart client
,2016-03-10 09:42:58.911 ThaliTest[804:1720635] client: found existing peer: EB1717B1-EA19-4A83-A99B-88282DEBD7B6:5
,2016-03-10 09:43:18.902 ThaliTest[804:1720635] multipeer manager: restart client
,2016-03-10 09:43:18.913 ThaliTest[804:1720635] client: found existing peer: EB1717B1-EA19-4A83-A99B-88282DEBD7B6:5
,2016-03-10 09:43:38.902 ThaliTest[804:1720635] multipeer manager: restart client
,2016-03-10 09:43:38.912 ThaliTest[804:1720635] client: found existing peer: EB1717B1-EA19-4A83-A99B-88282DEBD7B6:5
,2016-03-10 09:43:58.902 ThaliTest[804:1720635] multipeer manager: restart client
,2016-03-10 09:43:58.911 ThaliTest[804:1720635] client: found existing peer: EB1717B1-EA19-4A83-A99B-88282DEBD7B6:5
,2016-03-10 09:44:18.902 ThaliTest[804:1720635] multipeer manager: restart client
,2016-03-10 09:44:18.912 ThaliTest[804:1720635] client: found existing peer: EB1717B1-EA19-4A83-A99B-88282DEBD7B6:5
,2016-03-10 09:44:38.902 ThaliTest[804:1720635] multipeer manager: restart client
,2016-03-10 09:44:38.911 ThaliTest[804:1720635] client: found existing peer: EB1717B1-EA19-4A83-A99B-88282DEBD7B6:5
,2016-03-10 09:44:58.902 ThaliTest[804:1720635] multipeer manager: restart client
,2016-03-10 09:44:58.911 ThaliTest[804:1720635] client: found existing peer: EB1717B1-EA19-4A83-A99B-88282DEBD7B6:5
,2016-03-10 09:45:18.902 ThaliTest[804:1720635] multipeer manager: restart client
,2016-03-10 09:45:18.912 ThaliTest[804:1720635] client: found existing peer: EB1717B1-EA19-4A83-A99B-88282DEBD7B6:5
,2016-03-10 09:45:38.902 ThaliTest[804:1720635] multipeer manager: restart client
,2016-03-10 09:45:38.911 ThaliTest[804:1720635] client: found existing peer: EB1717B1-EA19-4A83-A99B-88282DEBD7B6:5
,2016-03-10 09:45:58.902 ThaliTest[804:1720635] multipeer manager: restart client
,2016-03-10 09:45:58.912 ThaliTest[804:1720635] client: found existing peer: EB1717B1-EA19-4A83-A99B-88282DEBD7B6:5
,2016-03-10 09:46:18.902 ThaliTest[804:1720635] multipeer manager: restart client
,2016-03-10 09:46:18.912 ThaliTest[804:1720635] client: found existing peer: EB1717B1-EA19-4A83-A99B-88282DEBD7B6:5
,2016-03-10 09:46:38.902 ThaliTest[804:1720635] multipeer manager: restart client
,2016-03-10 09:46:38.911 ThaliTest[804:1720635] client: found existing peer: EB1717B1-EA19-4A83-A99B-88282DEBD7B6:5
,2016-03-10 09:46:58.902 ThaliTest[804:1720635] multipeer manager: restart client
,2016-03-10 09:46:58.912 ThaliTest[804:1720635] client: found existing peer: EB1717B1-EA19-4A83-A99B-88282DEBD7B6:5
,2016-03-10 09:47:18.902 ThaliTest[804:1720635] multipeer manager: restart client
,2016-03-10 09:47:18.913 ThaliTest[804:1720635] client: found existing peer: EB1717B1-EA19-4A83-A99B-88282DEBD7B6:5
,2016-03-10 09:47:38.902 ThaliTest[804:1720635] multipeer manager: restart client
,2016-03-10 09:47:58.902 ThaliTest[804:1720635] multipeer manager: restart client
,2016-03-10 09:47:58.912 ThaliTest[804:1720635] client: found existing peer: EB1717B1-EA19-4A83-A99B-88282DEBD7B6:5
,2016-03-10 09:48:18.902 ThaliTest[804:1720635] multipeer manager: restart client
,2016-03-10 09:48:18.912 ThaliTest[804:1720635] client: found existing peer: EB1717B1-EA19-4A83-A99B-88282DEBD7B6:5
,2016-03-10 09:48:38.902 ThaliTest[804:1720635] multipeer manager: restart client
,2016-03-10 09:48:38.912 ThaliTest[804:1720635] client: found existing peer: EB1717B1-EA19-4A83-A99B-88282DEBD7B6:5
,2016-03-10 09:48:58.902 ThaliTest[804:1720635] multipeer manager: restart client
,2016-03-10 09:48:58.912 ThaliTest[804:1720635] client: found existing peer: EB1717B1-EA19-4A83-A99B-88282DEBD7B6:5
,2016-03-10 09:49:18.902 ThaliTest[804:1720635] multipeer manager: restart client
,2016-03-10 09:49:18.912 ThaliTest[804:1720635] client: found existing peer: EB1717B1-EA19-4A83-A99B-88282DEBD7B6:5
,2016-03-10 09:49:38.902 ThaliTest[804:1720635] multipeer manager: restart client
,2016-03-10 09:49:38.911 ThaliTest[804:1720635] client: found existing peer: EB1717B1-EA19-4A83-A99B-88282DEBD7B6:5
,2016-03-10 09:49:58.902 ThaliTest[804:1720635] multipeer manager: restart client
,2016-03-10 09:49:58.912 ThaliTest[804:1720635] client: found existing peer: EB1717B1-EA19-4A83-A99B-88282DEBD7B6:5
,2016-03-10 09:50:18.902 ThaliTest[804:1720635] multipeer manager: restart client
,2016-03-10 09:50:18.911 ThaliTest[804:1720635] client: found existing peer: EB1717B1-EA19-4A83-A99B-88282DEBD7B6:5
,2016-03-10 09:50:38.902 ThaliTest[804:1720635] multipeer manager: restart client
,2016-03-10 09:50:38.911 ThaliTest[804:1720635] client: found existing peer: EB1717B1-EA19-4A83-A99B-88282DEBD7B6:5
,2016-03-10 09:50:58.902 ThaliTest[804:1720635] multipeer manager: restart client
,2016-03-10 09:50:58.912 ThaliTest[804:1720635] client: found existing peer: EB1717B1-EA19-4A83-A99B-88282DEBD7B6:5
,2016-03-10 09:51:18.902 ThaliTest[804:1720635] multipeer manager: restart client
,2016-03-10 09:51:18.912 ThaliTest[804:1720635] client: found existing peer: EB1717B1-EA19-4A83-A99B-88282DEBD7B6:5
,2016-03-10 09:51:38.902 ThaliTest[804:1720635] multipeer manager: restart client
,2016-03-10 09:51:38.912 ThaliTest[804:1720635] client: found existing peer: EB1717B1-EA19-4A83-A99B-88282DEBD7B6:5
,2016-03-10 09:51:58.902 ThaliTest[804:1720635] multipeer manager: restart client
,2016-03-10 09:51:58.912 ThaliTest[804:1720635] client: found existing peer: EB1717B1-EA19-4A83-A99B-88282DEBD7B6:5
,2016-03-10 09:52:18.902 ThaliTest[804:1720635] multipeer manager: restart client
,2016-03-10 09:52:18.911 ThaliTest[804:1720635] client: found existing peer: EB1717B1-EA19-4A83-A99B-88282DEBD7B6:5
,2016-03-10 09:52:38.902 ThaliTest[804:1720635] multipeer manager: restart client
,2016-03-10 09:52:38.911 ThaliTest[804:1720635] client: found existing peer: EB1717B1-EA19-4A83-A99B-88282DEBD7B6:5
,2016-03-10 09:52:58.902 ThaliTest[804:1720635] multipeer manager: restart client
,2016-03-10 09:52:58.912 ThaliTest[804:1720635] client: found existing peer: EB1717B1-EA19-4A83-A99B-88282DEBD7B6:5
,2016-03-10 09:53:18.902 ThaliTest[804:1720635] multipeer manager: restart client
,2016-03-10 09:53:18.913 ThaliTest[804:1720635] client: found existing peer: EB1717B1-EA19-4A83-A99B-88282DEBD7B6:5
,2016-03-10 09:53:38.902 ThaliTest[804:1720635] multipeer manager: restart client
,2016-03-10 09:53:38.913 ThaliTest[804:1720635] client: found existing peer: EB1717B1-EA19-4A83-A99B-88282DEBD7B6:5
,2016-03-10 09:53:58.902 ThaliTest[804:1720635] multipeer manager: restart client
,2016-03-10 09:53:58.910 ThaliTest[804:1720635] client: found existing peer: EB1717B1-EA19-4A83-A99B-88282DEBD7B6:5
,2016-03-10 09:54:18.902 ThaliTest[804:1720635] multipeer manager: restart client
,2016-03-10 09:54:18.912 ThaliTest[804:1720635] client: found existing peer: EB1717B1-EA19-4A83-A99B-88282DEBD7B6:5
,2016-03-10 09:54:38.901 ThaliTest[804:1720635] multipeer manager: restart client
,2016-03-10 09:54:38.911 ThaliTest[804:1720635] client: found existing peer: EB1717B1-EA19-4A83-A99B-88282DEBD7B6:5
,2016-03-10 09:54:58.902 ThaliTest[804:1720635] multipeer manager: restart client
,2016-03-10 09:54:58.911 ThaliTest[804:1720635] client: found existing peer: EB1717B1-EA19-4A83-A99B-88282DEBD7B6:5
,2016-03-10 09:55:18.902 ThaliTest[804:1720635] multipeer manager: restart client
,2016-03-10 09:55:18.911 ThaliTest[804:1720635] client: found existing peer: EB1717B1-EA19-4A83-A99B-88282DEBD7B6:5
,2016-03-10 09:55:38.902 ThaliTest[804:1720635] multipeer manager: restart client
,2016-03-10 09:55:38.911 ThaliTest[804:1720635] client: found existing peer: EB1717B1-EA19-4A83-A99B-88282DEBD7B6:5
,2016-03-10 09:55:58.902 ThaliTest[804:1720635] multipeer manager: restart client
,2016-03-10 09:55:58.912 ThaliTest[804:1720635] client: found existing peer: EB1717B1-EA19-4A83-A99B-88282DEBD7B6:5
,2016-03-10 09:56:18.902 ThaliTest[804:1720635] multipeer manager: restart client
,2016-03-10 09:56:18.911 ThaliTest[804:1720635] client: found existing peer: EB1717B1-EA19-4A83-A99B-88282DEBD7B6:5
,2016-03-10 09:56:38.902 ThaliTest[804:1720635] multipeer manager: restart client
,2016-03-10 09:56:58.902 ThaliTest[804:1720635] multipeer manager: restart client
,2016-03-10 09:56:58.910 ThaliTest[804:1720635] client: found existing peer: EB1717B1-EA19-4A83-A99B-88282DEBD7B6:5
,2016-03-10 09:57:18.902 ThaliTest[804:1720635] multipeer manager: restart client
,2016-03-10 09:57:18.912 ThaliTest[804:1720635] client: found existing peer: EB1717B1-EA19-4A83-A99B-88282DEBD7B6:5
,2016-03-10 09:57:38.902 ThaliTest[804:1720635] multipeer manager: restart client
,2016-03-10 09:57:38.911 ThaliTest[804:1720635] client: found existing peer: EB1717B1-EA19-4A83-A99B-88282DEBD7B6:5

```
