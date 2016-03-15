#### Test 62509094058a2d4_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/62509094058a2d4/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/27B15994-AF7F-4D8B-88CB-13F2AAF0BE92/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/27B15994-AF7F-4D8B-88CB-13F2AAF0BE92/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/62509094058a2d4/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/62509094058a2d4/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/6544D220-E942-4846-9856-427E0EA484E3/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49591"
,(lldb)     command script import "/tmp/27B15994-AF7F-4D8B-88CB-13F2AAF0BE92/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-15 13:15:42.525 ThaliTest[1431:2295993] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/921DB591-6DA2-4719-85F7-0C906BCEF5B6/Library/Cookies/Cookies.binarycookies
,2016-03-15 13:15:42.865 ThaliTest[1431:2295993] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-15 13:15:42.866 ThaliTest[1431:2295993] Multi-tasking -> Device: YES, App: YES
,2016-03-15 13:15:42.886 ThaliTest[1431:2295993] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-15 13:15:44.620 ThaliTest[1431:2295993] Using UIWebView
,2016-03-15 13:15:44.627 ThaliTest[1431:2295993] [CDVTimer][handleopenurl] 0.401974ms
,2016-03-15 13:15:44.636 ThaliTest[1431:2295993] [CDVTimer][intentandnavigationfilter] 8.046985ms
2016-03-15 13:15:44.636 ThaliTest[1431:2295993] [CDVTimer][gesturehandler] 0.372946ms
2016-03-15 13:15:44.637 ThaliTest[1431:2295993] [CDVTimer][TotalPluginStartup] 10.959029ms
,2016-03-15 13:15:51.560 ThaliTest[1431:2295993] Resetting plugins due to page load.
,2016-03-15 13:15:54.525 ThaliTest[1431:2295993] Finished load of: file:///var/mobile/Containers/Bundle/Application/6544D220-E942-4846-9856-427E0EA484E3/ThaliTest.app/www/index.html
,2016-03-15 13:15:54.747 ThaliTest[1431:2295993] JXcore Cordova plugin initializing
2016-03-15 13:15:54.748 ThaliTest[1431:2296197] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,2016-03-15 13:15:58.445 ThaliTest[1431:2296197] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-15 13:15:58.446 ThaliTest[1431:2296197] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-15 13:15:58.447 ThaliTest[1431:2296197] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

,2016-03-15 13:15:58.450 ThaliTest[1431:2296197] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6544D220-E942-4846-9856-427E0EA484E3/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6544D220-E942-4846-9856-427E0EA484E3/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6544D220-E942-4846-9856-427E0EA484E3/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6544D220-E942-4846-9856-427E0EA484E3/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6544D220-E942-4846-9856-427E0EA484E3/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6544D220-E942-4846-9856-427E0EA484E3/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6544D220-E942-4846-9856-427E0EA484E3/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6544D220-E942-4846-9856-427E0EA484E3/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6544D220-E942-4846-9856-427E0EA484E3/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6544D220-E942-4846-9856-427E0EA484E3/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6544D220-E942-4846-9856-427E0EA484E3/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6544D220-E942-4846-9856-427E0EA484E3/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6544D220-E942-4846-9856-427E0EA484E3/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6544D220-E942-4846-9856-427E0EA484E3/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6544D220-E942-4846-9856-427E0EA484E3/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6544D220-E942-4846-9856-427E0EA484E3/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6544D220-E942-4846-9856-427E0EA484E3/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6544D220-E942-4846-9856-427E0EA484E3/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,2016-03-15 13:16:06.431 ThaliTest[1431:2295993] THREAD WARNING: ['JXcore'] took '6101.449951' ms. Plugin should use a background thread.
,Reconnected to the test server

,TAP version 13

,# setup

,# 1. calling createNativeListener directly rejects

,# teardown

,ok 1 Should throw

,# setup

,# 2. emits incomingConnectionState

,# teardown

,ok 2 initial connection state should be CONNECTED

,ok 3 final connection state should be DISCONNECTED

,# setup

,# 3. emits routerPortConnectionFailed

,# teardown

,ok 4 routerPortConnectionFailed is emitted

,# setup

,# 4. native server connections all up

,# teardown

,ok 5 Send/recvd #1 should be equal length

,ok 6 Send/recvd #1 should be same

,ok 7 Send/recvd #2 should be equal length

,ok 8 Send/recvd #2 should be same

,ok 9 Should be exactly 2 client sockets

,# setup

,# 5. native server - closing incoming stream cleans outgoing socket

,# teardown

,ok 10 socket shouldn't close until after stream

,ok 11 incoming remains open

,# setup

,# 6. native server - closing incoming connection cleans outgoing socket

,# teardown

,ok 12 we should not have gotten an error

,ok 13 socket shouldn't close until after incoming

,ok 14 incoming is cleaned up

,# setup

,# 7. native server - closing outgoing socket cleans associated mux stream

,# teardown

,ok 15 stream was closed

,ok 16 incoming should survive

,ok 17 mux should have no streams

,# setup

,# 8. native server - closing the whole server cleans everything up

,# teardown

,ok 18 we should not have gotten an error

,ok 19 Buffers are identical

,ok 20 native server is nulled out

,ok 21 native server should be closed

,ok 22 incoming has been removed

,ok 23 Incoming should be done

,ok 24 The mux object should be closed

,ok 25 The mux stream should be closed

,# setup

,# 9. native server - we can get a ton of connections and data through and still clean up the server completely

,# teardown

,ok 26 native server is nulled out

ok 27 native server should be closed

ok 28 incoming has been removed

,# setup

,# 10. native server - simulate mux failure, make sure everything is cleaned up

,# teardown

,ok 29 we should not have gotten an error

,ok 30 Buffers are identical

,ok 31 server should be fine

,ok 32 server should be open

,ok 33 incoming has been removed

,ok 34 The mux object should be closed

,ok 35 The mux stream should be closed

,# setup

,# 11. native server - timing out the incoming connection cleans everything up

,# teardown

,ok 36 we should not have gotten an error

,ok 37 Buffers are identical

,ok 38 server should be fine

,ok 39 server should be open

,ok 40 incoming has been removed

,ok 41 The mux object should be closed

,ok 42 The mux stream should be closed

,# setup

,# 12. closeAll can close even when connections open

,# teardown

,ok 43 not possible to connect to the server anymore

,# setup

,# 13. closeAll with promise

,# teardown

,ok 44 not possible to connect to the server anymore

,# setup

,# 14. multiplex can send data

,# teardown

,ok 45 String should be length:200

,# setup

,# 15. enqueue and run in order

,# teardown

,ok 46 firstPromise setTimeout

,ok 47 firstPromise result

,ok 48 firstPromise testValue

,ok 49 secondPromise setTimeout

,ok 50 secondPromise result

,ok 51 secondPromise testValue

,ok 52 thirdPromise in promise

,ok 53 thirdPromise result

,ok 54 thirdPromise testValue

,# setup

,# 16. enqueueAtTop and run backwards

,# teardown

,ok 55 thirdPromise - first to run

,ok 56 thirdPromise - in resolve

,ok 57 secondPromise - second to run

,ok 58 secondPromise - in catch

,ok 59 firstPromise - third to run

,ok 60 firstPromise - in then

,ok 61 testing promises

,# setup

,# 17. mix enqueue and enqueueAtTop

,# teardown

,ok 62 fourth

,ok 63 fourth

,ok 64 second

,ok 65 secondPromise - in then

,ok 66 first

,ok 67 firstPromise - in catch

,ok 68 third

,ok 69 thirdPromise - in then

,ok 70 testingPromises

,# setup

,# 18. queues handled independently

,# teardown

,ok 71 all short operations completed before the long resolves

,# setup

,# 19. basic

,# teardown

,ok 72 sane

,# setup

,# 20. another

,# teardown

,ok 73 sane

,# setup

,# 21. #startListeningForAdvertisements should fail if start not called

,# teardown

,ok 74 specific error should be returned

,# setup

,ok 75 error should be null

,ok 76 error should be null

,# 22. #startUpdateAdvertisingAndListening should fail if start not called

,# teardown

,ok 77 specific error should be returned

,# setup

,ok 78 error should be null

,ok 79 error should be null

,# 23. should be able to call #stopListeningForAdvertisements many times

,# teardown

,ok 80 error should be null

,ok 81 error should be null

,ok 82 error should be null

,ok 83 error should be null

,# setup

,ok 84 error should be null

,ok 85 error should be null

,# 24. should be able to call #startListeningForAdvertisements many times

,# teardown

,ok 86 error should be null

,ok 87 error should be null

,ok 88 error should be null

,ok 89 error should be null

,# setup

,INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).

,ok 90 error should be null

,ok 91 error should be null

,# 25. should be able to call #startUpdateAdvertisingAndListening many times

,# teardown

,ok 92 error should be null

,ok 93 error should be null

,ok 94 error should be null

,ok 95 error should be null

,# setup

,INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).

,ok 96 error should be null

,ok 97 error should be null

,# 26. should be able to call #stopAdvertisingAndListening many times

,# teardown

,ok 98 error should be null

,ok 99 error should be null

,ok 100 error should be null

,ok 101 error should be null

,# setup

,ok 102 error should be null

,ok 103 error should be null

,# 27. #start should fail if called twice in a row

,# teardown

,ok 104 first call should succeed

,ok 105 first call should succeed

,ok 106 specific error should be returned

,# setup

,ok 107 error should be null

,ok 108 error should be null

,# 28. does not emit duplicate discoveryAdvertisingStateUpdate

,# teardown

,ok 109 called only once

,ok 110 discovery state matches

,ok 111 advertising state matches

,# setup

,INFO thaliMobile Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}

,INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).

,INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).

,ok 112 error should be null

,ok 113 error should be null

,# 29. does not send duplicate availability changes

,# teardown

,ok 114 should be called once

,ok 115 should not have been called more than once

,# setup

,ok 116 error should be null

,ok 117 error should be null

,# 30. can get the network status

,# teardown

,ok 118 network status should have certain non-empty properties

,# setup

,ok 119 error should be null

,ok 120 error should be null

,# 31. wifi peer is marked unavailable if announcements stop

,# teardown

,ok 121 host address should match

,ok 122 port should match

,ok 123 host address should be null

,ok 124 port should should be null

,# setup

,INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).

,ok 125 error should be null

,ok 126 error should be null

,# 32. Can call start/stopListeningForAdvertisements

,# teardown

,2016-03-15 13:19:24.304 ThaliTest[1431:2296197] jxcore: startListeningForAdvertisements
2016-03-15 13:19:24.306 ThaliTest[1431:2296197] multipeer manager: start client restart timer: 0x1454f190
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}

,2016-03-15 13:19:24.308 ThaliTest[1431:2296197] jxcore: startListeningForAdvertisements: success
,ok 127 Can call startListeningForAdvertisements without error

2016-03-15 13:19:24.311 ThaliTest[1431:2296197] jxcore: stopListeningForAdvertisements
2016-03-15 13:19:24.312 ThaliTest[1431:2296197] multipeer manager: stop client timer
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}

,2016-03-15 13:19:24.314 ThaliTest[1431:2296197] jxcore: stopListeningForAdvertisements: success
ok 128 Can call stopListeningForAdvertisements without error

,# setup

,2016-03-15 13:19:24.393 ThaliTest[1431:2296197] jxcore: stopListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}

,2016-03-15 13:19:24.395 ThaliTest[1431:2296197] jxcore: stopListeningForAdvertisements: success
,ok 129 Should be able to call stopListeningForAdvertisments in teardown

,2016-03-15 13:19:24.398 ThaliTest[1431:2296197] jxcore: stopAdvertisingAndListening
2016-03-15 13:19:24.398 ThaliTest[1431:2296197] THEMultipeerManager stopping peer
2016-03-15 13:19:24.398 ThaliTest[1431:2296197] jxcore: stopAdvertisingAndListening: suc,cess
ok 130 Should be able to call stopAdvertisingAndListening in teardown

,# 33. Calling startListeningForAdvertisements twice is NOT an error

,# teardown

,2016-03-15 13:19:25.086 ThaliTest[1431:2296197] jxcore: startListeningForAdvertisements
2016-03-15 13:19:25.087 ThaliTest[1431:2296197] multipeer manager: start client restart timer: 0x1454f190
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}

2016-03-15 13:19:25.090 ThaliTest[1431:2296197] jxcore: startListeningForAdvertisements: success
ok 131 Can call startListeningForAd,vertisements without error

2016-03-15 13:19:25.092 ThaliTest[1431:2296197] jxcore: startListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}

,2016-03-15 13:19:25.094 ThaliTest[1431:2296197] jxcore: startListeningForAdvertisements: success
,ok 132 Can call startListeningForAdvertisements twice without error

# setup
,
,2016-03-15 13:19:25.199 ThaliTest[1431:2296197] jxcore: stopListeningForAdvertisements
2016-03-15 13:19:25.199 ThaliTest[1431:2296197] multipeer manager: stop client timer
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}

,2016-03-15 13:19:25.201 ThaliTest[1431:2296197] jxcore: stopListeningForAdvertisements: success
ok 133 Should be able to call stopListeningForAdvertisments in teardown

,2016-03-15 13:19:25.204 ThaliTest[1431:2296197] jxcore: stopAdvertisingAndListening
2016-03-15 13:19:25.204 ThaliTest[1431:2296197] THEMultipeerManager stopping peer
2016-03-15 13:19:25.205 ThaliTest[1431:2296197] jxcore: stopAdvertisingAndListening: suc,cess
ok 134 Should be able to call stopAdvertisingAndListening in teardown

,# 34. Can call start/stopUpdateAdvertisingAndListening

,# teardown

,2016-03-15 13:19:25.707 ThaliTest[1431:2296197] jxcore: startUpdateAdvertisingAndListening
2016-03-15 13:19:25.707 ThaliTest[1431:2296197] server: starting B7D25A96-D37D-4E73-B512-E3AADCC34F73:1
2016-03-15 13:19:25.708 ThaliTest[1431:2296197] multipeer m,anager: start client restart timer: 0x1454f190
2016-03-15 13:19:25.709 ThaliTest[1431:2296197] THEMultipeerManager initialized peer B7D25A96-D37D-4E73-B512-E3AADCC34F73:1
2016-03-15 13:19:25.709 ThaliTest[1431:2296197] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 135 Can call startUpdateAdvertisingAndListening without error

2016-03-15 13:19:25.711 ThaliTest[1431:2296197] jxcore: stopAdvertisingAndListening
2016-03-15 13:19:25.712 ThaliTest[1431:2296197] THEMultipeerManager stopping peer
20,16-03-15 13:19:25.712 ThaliTest[1431:2296197] multipeer manager: stop client timer
2016-03-15 13:19:25.713 ThaliTest[1431:2296197] jxcore: stopAdvertisingAndListening: success
ok 136 Can call stopAdvertisingAndListening without error

# setup

,2016-03-15 13:19:26.726 ThaliTest[1431:2296197] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}

,2016-03-15 13:19:26.728 ThaliTest[1431:2296197] jxcore: stopListeningForAdvertisements: success
,ok 137 Should be able to call stopListeningForAdvertisments in teardown

,2016-03-15 13:19:26.732 ThaliTest[1431:2296197] jxcore: stopAdvertisingAndListening
2016-03-15 13:19:26.732 ThaliTest[1431:2296197] THEMultipeerManager stopping peer
2016-03-15 13:19:26.732 ThaliTest[1431:2296197] jxcore: stopAdvertisingAndListening: success
ok 138 Should be able to call stopAdvertisingAndListening in teardown

,# 35. Calling startUpdateAdvertisingAndListening twice is NOT an error

,# teardown

,2016-03-15 13:19:27.113 ThaliTest[1431:2296197] jxcore: startUpdateAdvertisingAndListening
2016-03-15 13:19:27.114 ThaliTest[1431:2296197] server: starting B7D25A96-D37D-4E73-B512-E3AADCC34F73:2
2016-03-15 13:19:27.114 ThaliTest[1431:2296197] multipeer m,anager: start client restart timer: 0x1454f190
2016-03-15 13:19:27.115 ThaliTest[1431:2296197] THEMultipeerManager initialized peer B7D25A96-D37D-4E73-B512-E3AADCC34F73:2
2016-03-15 13:19:27.115 ThaliTest[1431:2296197] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 139 Can call startUpdateAdvertisingAndListening without error

2016-03-15 13:19:27.117 ThaliTest[1431:2296197] jxcore: startUpdateAdvertisingAndListening
2016-03-15 13:19:27.118 ThaliTest[1431:2296197] THEMultipeerManager stopping p,eer
2016-03-15 13:19:27.118 ThaliTest[1431:2296197] multipeer manager: stop client timer
2016-03-15 13:19:27.119 ThaliTest[1431:2296197] server: starting B7D25A96-D37D-4E73-B512-E3AADCC34F73:3
2016-03-15 13:19:27.119 ThaliTest[1431:2296197] multipeer ma,nager: start client restart timer: 0x1454f190
,2016-03-15 13:19:27.126 ThaliTest[1431:2296197] THEMultipeerManager initialized peer B7D25A96-D37D-4E73-B512-E3AADCC34F73:3
2016-03-15 13:19:27.126 ThaliTest[1431:2296197] jxcore: startUpdateAdvertisingAndListening: success
ok 140 Can call startUpdateAdvertisingAndListening twice without error

# setup

,2016-03-15 13:19:27.367 ThaliTest[1431:2296197] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}

2016-03-15 13:19:27.371 ThaliTest[1431:2296197] jxcore: stopListeningForAdvertisements: success
,ok 141 Should be able to call stopListeningForAdvertisments in teardown

,2016-03-15 13:19:27.374 ThaliTest[1431:2296197] jxcore: stopAdvertisingAndListening
2016-03-15 13:19:27.375 ThaliTest[1431:2296197] THEMultipeerManager stopping peer
2016-03-15 13:19:27.375 ThaliTest[1431:2296197] multipeer manager: stop client timer
2016-03-15 13:19:27.375 ThaliTest[1431:2296197] jxcore: stopAdvertisingAndListening: success
ok 142 Should be able to call stopAdvertisingAndListening in teardown

,# 36. peerAvailabilityChange is called

,# teardown

,2016-03-15 13:19:27.737 ThaliTest[1431:2296197] jxcore: startUpdateAdvertisingAndListening
2016-03-15 13:19:27.738 ThaliTest[1431:2296197] server: starting B7D25A96-D37D-4E73-B512-E3AADCC34F73:4
2016-03-15 13:19:27.739 ThaliTest[1431:2296197] multipeer manager: start client restart timer: 0x1454f190
2016-03-15 13:19:27.739 ThaliTest[1431:2296197] THEMultipeerManager initialized peer B7D25A96-D37D-4E73-B512-E3AADCC34F73:4
2016-03-15 13:19:27.740 ThaliTest[1431:2296197] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 143 Can call startUpdateAdvertisingAndListeningwithout error

2016-03-15 13:19:27.741 ThaliTest[1431:2296197] jxcore: startListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}

2016-03-15 13:19:27.746 ThaliTest[1431:2296197] jxcore: startListeningForAdvertisements: success
ok 144 Can call startListeningForAdvertisements without error

,2016-03-15 13:19:29.099 ThaliTest[1431:2295993] client: found new peer: 92BE0BB8-A3CB-455A-82BE-F170E648CB17:4
ok 145 peers must be an array

,ok 146 peers must not be zero-length

,ok 147 peer must have peerIdentifier

ok 148 peerIdentifier must be a string

ok 149 peer must have peerAvailable

ok 150 peer must have pleaseConnect

,# setup

,2016-03-15 13:19:29.369 ThaliTest[1431:2296197] jxcore: stopListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}

,2016-03-15 13:19:29.371 ThaliTest[1431:2296197] jxcore: stopListeningForAdvertisements: success
,ok 151 Should be able to call stopListeningForAdvertisments in teardown

,2016-03-15 13:19:29.373 ThaliTest[1431:2296197] jxcore: stopAdvertisingAndListening
2016-03-15 13:19:29.374 ThaliTest[1431:2296197] THEMultipeerManager stopping peer
2016-03-15 13:19:29.374 ThaliTest[1431:2296197] multipeer manager: stop client timer
,2016-03-15 13:19:29.376 ThaliTest[1431:2296197] jxcore: stopAdvertisingAndListening: success
ok 152 Should be able to call stopAdvertisingAndListening in teardown

# 37. Can connect to a remote peer

,# teardown

,2016-03-15 13:19:55.622 ThaliTest[1431:2296197] jxcore: startUpdateAdvertisingAndListening
2016-03-15 13:19:55.622 ThaliTest[1431:2296197] server: starting B7D25A96-D37D-4E73-B512-E3AADCC34F73:5
2016-03-15 13:19:55.623 ThaliTest[1431:2296197] multipeer m,anager: start client restart timer: 0x1454f190
2016-03-15 13:19:55.624 ThaliTest[1431:2296197] THEMultipeerManager initialized peer B7D25A96-D37D-4E73-B512-E3AADCC34F73:5
2016-03-15 13:19:55.624 ThaliTest[1431:2296197] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 153 Can call startUpdateAdvertisingAndListening without error

2016-03-15 13:19:55.626 ThaliTest[1431:2296197] jxcore: startListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}

,2016-03-15 13:19:55.629 ThaliTest[1431:2296197] jxcore: startListeningForAdvertisements: success
,ok 154 Can call startListeningForAdvertisements without error

,2016-03-15 13:19:57.787 ThaliTest[1431:2295993] client: found new peer: 92BE0BB8-A3CB-455A-82BE-F170E648CB17:5
2016-03-15 13:19:57.790 ThaliTest[1431:2296197] jxcore: connect 92BE0BB8-A3CB-455A-82BE-F170E648CB17:5
2016-03-15 13:19:57.790 ThaliTest[1431:2296197] client session: connect
2016-03-15 13:19:57.791 ThaliTest[1431:2296197] client session: stateChange:0->1 92BE0BB8-A3CB-455A-82BE-F170E648CB17:5
,2016-03-15 13:19:58.440 ThaliTest[1431:2295993] multipeer session: reset timer
2016-03-15 13:19:58.441 ThaliTest[1431:2295993] server: rejecting invitation for lexical ordering 92BE0BB8-A3CB-455A-82BE-F170E648CB17
,2016-03-15 13:19:59.877 ThaliTest[1431:2296633] client session: connected
,2016-03-15 13:19:59.879 ThaliTest[1431:2296633] client session: stateChange:1->2 92BE0BB8-A3CB-455A-82BE-F170E648CB17:5
,2016-03-15 13:19:59.902 ThaliTest[1431:2296633] client session: fireConnectCallback: 92BE0BB8-A3CB-455A-82BE-F170E648CB17
,2016-03-15 13:19:59.904 ThaliTest[1431:2296633] jxcore: connect: success
,{ clientPort: 0, serverPort: 0, listeningPort: 61079 }

,ok 155 Must have listeningPort

,ok 156 listeningPort must be a number

,ok 157 Connection must have clientPort

,ok 158 clientPort must be a number

,ok 159 Connection must have serverPort

,ok 160 serverPort must be a number

,ok 161 (unnamed assert)

,ok 162 (unnamed assert)

,# setup

,2016-03-15 13:20:00.441 ThaliTest[1431:2296197] jxcore: stopListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}

,2016-03-15 13:20:00.443 ThaliTest[1431:2296197] jxcore: stopListeningForAdvertisements: success
,ok 163 Should be able to call stopListeningForAdvertisments in teardown

,2016-03-15 13:20:00.446 ThaliTest[1431:2296197] jxcore: stopAdvertisingAndListening
,2016-03-15 13:20:00.446 ThaliTest[1431:2296197] THEMultipeerManager stopping peer
,2016-03-15 13:20:00.448 ThaliTest[1431:2296197] client session: disconnect
2016-03-15 13:20:00.448 ThaliTest[1431:2296197] client session: stateChange:2->0 92BE0BB8-A3CB-455A-82BE-F170E648CB17:5
,2016-03-15 13:20:00.488 ThaliTest[1431:2296197] multipeer manager: stop client timer
,2016-03-15 13:20:00.494 ThaliTest[1431:2296197] jxcore: stopAdvertisingAndListening: success
,ok 164 Should be able to call stopAdvertisingAndListening in teardown

,# 38. Can shift large amounts of data

,# teardown

,2016-03-15 13:20:01.542 ThaliTest[1431:2296197] jxcore: startUpdateAdvertisingAndListening
2016-03-15 13:20:01.542 ThaliTest[1431:2296197] server: starting B7D25A96-D37D-4E73-B512-E3AADCC34F73:6
2016-03-15 13:20:01.543 ThaliTest[1431:2296197] multipeer manager: start client restart timer: 0x1454f190
2016-03-15 13:20:01.543 ThaliTest[1431:2296197] THEMultipeerManager initialized peer B7D25A96-D37D-4E73-B512-E3AADCC34F73:6
2016-03-15 13:20:01.543 ThaliTest[1431:2296197] jxcore: startUpdateAdvertisingAndListening: success
ok 165 Can call startUpdateAdvertisingAndListening without error

,2016-03-15 13:20:01.544 ThaliTest[1431:2296197] jxcore: startListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}

2016-03-15 13:20:01.545 ThaliTest[1431:2296197] jxcore: startListeningForAdvertisements: success
ok 166 Can call startListeningForAdvertisements without error

,2016-03-15 13:20:03.552 ThaliTest[1431:2295993] client: found new peer: 92BE0BB8-A3CB-455A-82BE-F170E648CB17:5
2016-03-15 13:20:03.554 ThaliTest[1431:2296197] jxcore: connect 92BE0BB8-A3CB-455A-82BE-F170E648CB17:5
,2016-03-15 13:20:03.554 ThaliTest[1431:2296197] client session: connect
,2016-03-15 13:20:03.555 ThaliTest[1431:2296197] client session: stateChange:0->1 92BE0BB8-A3CB-455A-82BE-F170E648CB17:5
,2016-03-15 13:20:04.139 ThaliTest[1431:2295993] multipeer session: reset timer
2016-03-15 13:20:04.139 ThaliTest[1431:2295993] server: rejecting invitation for lexical ordering 92BE0BB8-A3CB-455A-82BE-F170E648CB17
,2016-03-15 13:20:04.263 ThaliTest[1431:2296634] client session: not connected 92BE0BB8-A3CB-455A-82BE-F170E648CB17:5
2016-03-15 13:20:04.263 ThaliTest[1431:2296634] client session: onLinkFailure: 92BE0BB8-A3CB-455A-82BE-F170E648CB17
2016-03-15 13:20:04.2,63 ThaliTest[1431:2296634] client session: disconnect
2016-03-15 13:20:04.264 ThaliTest[1431:2296634] client session: stateChange:1->0 92BE0BB8-A3CB-455A-82BE-F170E648CB17:5
2016-03-15 13:20:04.264 ThaliTest[1431:2296634] client session: fireConnectCallb,ack: 92BE0BB8-A3CB-455A-82BE-F170E648CB17
2016-03-15 13:20:04.265 ThaliTest[1431:2296634] jxcore: connect: fail: Peer disconnected
not ok 167 Error from connect: Peer disconnected

  ---

    operator: fail

,  ...

,# setup

,2016-03-15 13:20:21.544 ThaliTest[1431:2295993] multipeer manager: restart client
,2016-03-15 13:20:30.804 ThaliTest[1431:2295993] client: found updated peer: 92BE0BB8-A3CB-455A-82BE-F170E648CB17:6
,2016-03-15 13:20:41.544 ThaliTest[1431:2295993] multipeer manager: restart client
,2016-03-15 13:20:41.563 ThaliTest[1431:2295993] client: found existing peer: 92BE0BB8-A3CB-455A-82BE-F170E648CB17:6
,2016-03-15 13:21:01.544 ThaliTest[1431:2295993] multipeer manager: restart client
,2016-03-15 13:21:01.560 ThaliTest[1431:2295993] client: found existing peer: 92BE0BB8-A3CB-455A-82BE-F170E648CB17:6
,2016-03-15 13:21:21.544 ThaliTest[1431:2295993] multipeer manager: restart client
,2016-03-15 13:21:21.560 ThaliTest[1431:2295993] client: found existing peer: 92BE0BB8-A3CB-455A-82BE-F170E648CB17:6
,2016-03-15 13:21:41.544 ThaliTest[1431:2295993] multipeer manager: restart client
,2016-03-15 13:21:41.562 ThaliTest[1431:2295993] client: found existing peer: 92BE0BB8-A3CB-455A-82BE-F170E648CB17:6
,2016-03-15 13:22:01.544 ThaliTest[1431:2295993] multipeer manager: restart client
,2016-03-15 13:22:01.562 ThaliTest[1431:2295993] client: found existing peer: 92BE0BB8-A3CB-455A-82BE-F170E648CB17:6
,2016-03-15 13:22:21.544 ThaliTest[1431:2295993] multipeer manager: restart client
,2016-03-15 13:22:21.562 ThaliTest[1431:2295993] client: found existing peer: 92BE0BB8-A3CB-455A-82BE-F170E648CB17:6
,2016-03-15 13:22:41.544 ThaliTest[1431:2295993] multipeer manager: restart client
,2016-03-15 13:22:41.562 ThaliTest[1431:2295993] client: found existing peer: 92BE0BB8-A3CB-455A-82BE-F170E648CB17:6
,2016-03-15 13:23:01.544 ThaliTest[1431:2295993] multipeer manager: restart client
,2016-03-15 13:23:01.563 ThaliTest[1431:2295993] client: found existing peer: 92BE0BB8-A3CB-455A-82BE-F170E648CB17:6
,2016-03-15 13:23:21.544 ThaliTest[1431:2295993] multipeer manager: restart client
,2016-03-15 13:23:21.561 ThaliTest[1431:2295993] client: found existing peer: 92BE0BB8-A3CB-455A-82BE-F170E648CB17:6
,2016-03-15 13:23:41.544 ThaliTest[1431:2295993] multipeer manager: restart client
,2016-03-15 13:23:41.564 ThaliTest[1431:2295993] client: found existing peer: 92BE0BB8-A3CB-455A-82BE-F170E648CB17:6
,2016-03-15 13:24:01.544 ThaliTest[1431:2295993] multipeer manager: restart client
,2016-03-15 13:24:01.563 ThaliTest[1431:2295993] client: found existing peer: 92BE0BB8-A3CB-455A-82BE-F170E648CB17:6
,2016-03-15 13:24:21.545 ThaliTest[1431:2295993] multipeer manager: restart client
,2016-03-15 13:24:21.562 ThaliTest[1431:2295993] client: found existing peer: 92BE0BB8-A3CB-455A-82BE-F170E648CB17:6
,2016-03-15 13:24:41.544 ThaliTest[1431:2295993] multipeer manager: restart client
,2016-03-15 13:24:41.563 ThaliTest[1431:2295993] client: found existing peer: 92BE0BB8-A3CB-455A-82BE-F170E648CB17:6
,2016-03-15 13:25:01.544 ThaliTest[1431:2295993] multipeer manager: restart client
,2016-03-15 13:25:01.563 ThaliTest[1431:2295993] client: found existing peer: 92BE0BB8-A3CB-455A-82BE-F170E648CB17:6
,2016-03-15 13:25:21.544 ThaliTest[1431:2295993] multipeer manager: restart client
,2016-03-15 13:25:21.560 ThaliTest[1431:2295993] client: found existing peer: 92BE0BB8-A3CB-455A-82BE-F170E648CB17:6
,2016-03-15 13:25:41.544 ThaliTest[1431:2295993] multipeer manager: restart client
,2016-03-15 13:25:41.561 ThaliTest[1431:2295993] client: found existing peer: 92BE0BB8-A3CB-455A-82BE-F170E648CB17:6
,2016-03-15 13:26:01.544 ThaliTest[1431:2295993] multipeer manager: restart client
,2016-03-15 13:26:01.560 ThaliTest[1431:2295993] client: found existing peer: 92BE0BB8-A3CB-455A-82BE-F170E648CB17:6
,2016-03-15 13:26:21.544 ThaliTest[1431:2295993] multipeer manager: restart client
,2016-03-15 13:26:21.560 ThaliTest[1431:2295993] client: found existing peer: 92BE0BB8-A3CB-455A-82BE-F170E648CB17:6
,2016-03-15 13:26:41.544 ThaliTest[1431:2295993] multipeer manager: restart client
,2016-03-15 13:26:41.563 ThaliTest[1431:2295993] client: found existing peer: 92BE0BB8-A3CB-455A-82BE-F170E648CB17:6
,2016-03-15 13:27:01.544 ThaliTest[1431:2295993] multipeer manager: restart client
,2016-03-15 13:27:21.544 ThaliTest[1431:2295993] multipeer manager: restart client
,2016-03-15 13:27:21.555 ThaliTest[1431:2295993] client: found existing peer: 92BE0BB8-A3CB-455A-82BE-F170E648CB17:6
,2016-03-15 13:27:41.544 ThaliTest[1431:2295993] multipeer manager: restart client
,2016-03-15 13:27:41.556 ThaliTest[1431:2295993] client: found existing peer: 92BE0BB8-A3CB-455A-82BE-F170E648CB17:6
,2016-03-15 13:28:01.544 ThaliTest[1431:2295993] multipeer manager: restart client
,2016-03-15 13:28:01.556 ThaliTest[1431:2295993] client: found existing peer: 92BE0BB8-A3CB-455A-82BE-F170E648CB17:6
,2016-03-15 13:28:21.544 ThaliTest[1431:2295993] multipeer manager: restart client
,2016-03-15 13:28:21.558 ThaliTest[1431:2295993] client: found existing peer: 92BE0BB8-A3CB-455A-82BE-F170E648CB17:6
,2016-03-15 13:28:41.544 ThaliTest[1431:2295993] multipeer manager: restart client
,2016-03-15 13:28:41.557 ThaliTest[1431:2295993] client: found existing peer: 92BE0BB8-A3CB-455A-82BE-F170E648CB17:6
,2016-03-15 13:29:01.544 ThaliTest[1431:2295993] multipeer manager: restart client
,2016-03-15 13:29:01.555 ThaliTest[1431:2295993] client: found existing peer: 92BE0BB8-A3CB-455A-82BE-F170E648CB17:6
,2016-03-15 13:29:21.544 ThaliTest[1431:2295993] multipeer manager: restart client
,2016-03-15 13:29:21.556 ThaliTest[1431:2295993] client: found existing peer: 92BE0BB8-A3CB-455A-82BE-F170E648CB17:6
,2016-03-15 13:29:41.544 ThaliTest[1431:2295993] multipeer manager: restart client
,2016-03-15 13:29:41.555 ThaliTest[1431:2295993] client: found existing peer: 92BE0BB8-A3CB-455A-82BE-F170E648CB17:6
,2016-03-15 13:30:01.544 ThaliTest[1431:2295993] multipeer manager: restart client
,2016-03-15 13:30:01.557 ThaliTest[1431:2295993] client: found existing peer: 92BE0BB8-A3CB-455A-82BE-F170E648CB17:6
,2016-03-15 13:30:21.544 ThaliTest[1431:2295993] multipeer manager: restart client
,2016-03-15 13:30:21.558 ThaliTest[1431:2295993] client: found existing peer: 92BE0BB8-A3CB-455A-82BE-F170E648CB17:6
,2016-03-15 13:30:41.544 ThaliTest[1431:2295993] multipeer manager: restart client
,2016-03-15 13:30:41.559 ThaliTest[1431:2295993] client: found existing peer: 92BE0BB8-A3CB-455A-82BE-F170E648CB17:6
,2016-03-15 13:31:01.544 ThaliTest[1431:2295993] multipeer manager: restart client
,2016-03-15 13:31:01.556 ThaliTest[1431:2295993] client: found existing peer: 92BE0BB8-A3CB-455A-82BE-F170E648CB17:6
,2016-03-15 13:31:21.544 ThaliTest[1431:2295993] multipeer manager: restart client
,2016-03-15 13:31:41.544 ThaliTest[1431:2295993] multipeer manager: restart client
,2016-03-15 13:31:41.555 ThaliTest[1431:2295993] client: found existing peer: 92BE0BB8-A3CB-455A-82BE-F170E648CB17:6
,2016-03-15 13:32:01.544 ThaliTest[1431:2295993] multipeer manager: restart client
,2016-03-15 13:32:01.557 ThaliTest[1431:2295993] client: found existing peer: 92BE0BB8-A3CB-455A-82BE-F170E648CB17:6
,2016-03-15 13:32:21.544 ThaliTest[1431:2295993] multipeer manager: restart client
,2016-03-15 13:32:21.556 ThaliTest[1431:2295993] client: found existing peer: 92BE0BB8-A3CB-455A-82BE-F170E648CB17:6
,2016-03-15 13:32:41.544 ThaliTest[1431:2295993] multipeer manager: restart client
,2016-03-15 13:32:41.557 ThaliTest[1431:2295993] client: found existing peer: 92BE0BB8-A3CB-455A-82BE-F170E648CB17:6
,2016-03-15 13:33:01.544 ThaliTest[1431:2295993] multipeer manager: restart client
,2016-03-15 13:33:01.556 ThaliTest[1431:2295993] client: found existing peer: 92BE0BB8-A3CB-455A-82BE-F170E648CB17:6
,2016-03-15 13:33:21.544 ThaliTest[1431:2295993] multipeer manager: restart client
,2016-03-15 13:33:21.557 ThaliTest[1431:2295993] client: found existing peer: 92BE0BB8-A3CB-455A-82BE-F170E648CB17:6
,2016-03-15 13:33:41.544 ThaliTest[1431:2295993] multipeer manager: restart client
,2016-03-15 13:33:41.557 ThaliTest[1431:2295993] client: found existing peer: 92BE0BB8-A3CB-455A-82BE-F170E648CB17:6
,2016-03-15 13:34:01.544 ThaliTest[1431:2295993] multipeer manager: restart client
,2016-03-15 13:34:01.556 ThaliTest[1431:2295993] client: found existing peer: 92BE0BB8-A3CB-455A-82BE-F170E648CB17:6
,2016-03-15 13:34:21.544 ThaliTest[1431:2295993] multipeer manager: restart client
,2016-03-15 13:34:21.557 ThaliTest[1431:2295993] client: found existing peer: 92BE0BB8-A3CB-455A-82BE-F170E648CB17:6
,2016-03-15 13:34:41.544 ThaliTest[1431:2295993] multipeer manager: restart client
,2016-03-15 13:34:41.557 ThaliTest[1431:2295993] client: found existing peer: 92BE0BB8-A3CB-455A-82BE-F170E648CB17:6
,2016-03-15 13:35:01.544 ThaliTest[1431:2295993] multipeer manager: restart client
,2016-03-15 13:35:01.556 ThaliTest[1431:2295993] client: found existing peer: 92BE0BB8-A3CB-455A-82BE-F170E648CB17:6
,2016-03-15 13:35:21.544 ThaliTest[1431:2295993] multipeer manager: restart client
,2016-03-15 13:35:21.556 ThaliTest[1431:2295993] client: found existing peer: 92BE0BB8-A3CB-455A-82BE-F170E648CB17:6
,2016-03-15 13:35:41.544 ThaliTest[1431:2295993] multipeer manager: restart client
,2016-03-15 13:35:41.557 ThaliTest[1431:2295993] client: found existing peer: 92BE0BB8-A3CB-455A-82BE-F170E648CB17:6
,2016-03-15 13:36:01.544 ThaliTest[1431:2295993] multipeer manager: restart client
,2016-03-15 13:36:01.556 ThaliTest[1431:2295993] client: found existing peer: 92BE0BB8-A3CB-455A-82BE-F170E648CB17:6
,2016-03-15 13:36:21.544 ThaliTest[1431:2295993] multipeer manager: restart client
,2016-03-15 13:36:21.556 ThaliTest[1431:2295993] client: found existing peer: 92BE0BB8-A3CB-455A-82BE-F170E648CB17:6
,2016-03-15 13:36:41.544 ThaliTest[1431:2295993] multipeer manager: restart client
,2016-03-15 13:36:41.557 ThaliTest[1431:2295993] client: found existing peer: 92BE0BB8-A3CB-455A-82BE-F170E648CB17:6

```
