#### Test 625481246b04bc0_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/625481246b04bc0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/D1160AF7-7E4C-480E-BAD4-E488A911DC09/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/D1160AF7-7E4C-480E-BAD4-E488A911DC09/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/625481246b04bc0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/625481246b04bc0/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/C383F902-460C-47C7-9D03-4A659A3575F9/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49491"
,(lldb)     command script import "/tmp/D1160AF7-7E4C-480E-BAD4-E488A911DC09/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success,
(lldb)     autoexit
,2016-03-15 12:45:01.020 ThaliTest[1478:2346137] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/708966B4-7FDA-411E-A5BF-6C2CA395A8EB/Library/Cookies/Cookies.binarycookies
,2016-03-15 12:45:01.371 ThaliTest[1478:2346137] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-15 12:45:01.372 ThaliTest[1478:2346137] Multi-tasking -> Device: YES, App: YES
,2016-03-15 12:45:01.391 ThaliTest[1478:2346137] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-15 12:45:03.189 ThaliTest[1478:2346137] Using UIWebView
,2016-03-15 12:45:03.196 ThaliTest[1478:2346137] [CDVTimer][handleopenurl] 0.386000ms
,2016-03-15 12:45:03.203 ThaliTest[1478:2346137] [CDVTimer][intentandnavigationfilter] 6.700993ms
,2016-03-15 12:45:03.204 ThaliTest[1478:2346137] [CDVTimer][gesturehandler] 0.308037ms
,2016-03-15 12:45:03.204 ThaliTest[1478:2346137] [CDVTimer][TotalPluginStartup] 8.955002ms
,2016-03-15 12:45:09.607 ThaliTest[1478:2346137] Resetting plugins due to page load.
,2016-03-15 12:45:13.012 ThaliTest[1478:2346137] Finished load of: file:///var/mobile/Containers/Bundle/Application/C383F902-460C-47C7-9D03-4A659A3575F9/ThaliTest.app/www/index.html
,2016-03-15 12:45:13.272 ThaliTest[1478:2346137] JXcore Cordova plugin initializing
,2016-03-15 12:45:13.273 ThaliTest[1478:2346358] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,INFO testUtils: Toggling radios to: true

,Unit Test app is loaded

,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C383F902-460C-47C7-9D03-4A659A3575F9/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C383F902-460C-47C7-9D03-4A659A3575F9/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C383F902-460C-47C7-9D03-4A659A3575F9/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C383F902-460C-47C7-9D03-4A659A3575F9/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C383F902-460C-47C7-9D03-4A659A3575F9/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C383F902-460C-47C7-9D03-4A659A3575F9/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-15 12:45:26.428 ThaliTest[1478:2346358] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-15 12:45:26.428 ThaliTest[1478:2346358] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-15 12:45:26.428 ThaliTest[1478:2346358] jxcore: didRegisterToNative networkChanged
,2016-03-15 12:45:26.429 ThaliTest[1478:2346358] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C383F902-460C-47C7-9D03-4A659A3575F9/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C383F902-460C-47C7-9D03-4A659A3575F9/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C383F902-460C-47C7-9D03-4A659A3575F9/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C383F902-460C-47C7-9D03-4A659A3575F9/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C383F902-460C-47C7-9D03-4A659A3575F9/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C383F902-460C-47C7-9D03-4A659A3575F9/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C383F902-460C-47C7-9D03-4A659A3575F9/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C383F902-460C-47C7-9D03-4A659A3575F9/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C383F902-460C-47C7-9D03-4A659A3575F9/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C383F902-460C-47C7-9D03-4A659A3575F9/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C383F902-460C-47C7-9D03-4A659A3575F9/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C383F902-460C-47C7-9D03-4A659A3575F9/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

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

,ok 27 native server should be closed

,ok 28 incoming has been removed

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

,2016-03-15 12:48:38.965 ThaliTest[1478:2346358] jxcore: stopListeningForAdvertisements
,2016-03-15 12:48:38.967 ThaliTest[1478:2346358] jxcore: stopListeningForAdvertisements: success
,ok 80 error should be null

,ok 81 error should be null

,2016-03-15 12:48:38.973 ThaliTest[1478:2346358] jxcore: stopListeningForAdvertisements
,2016-03-15 12:48:38.974 ThaliTest[1478:2346358] jxcore: stopListeningForAdvertisements: success
,ok 82 error should be null

,ok 83 error should be null

,# setup

,2016-03-15 12:48:39.117 ThaliTest[1478:2346358] jxcore: stopAdvertisingAndListening
,2016-03-15 12:48:39.118 ThaliTest[1478:2346358] THEMultipeerManager stopping peer
,2016-03-15 12:48:39.118 ThaliTest[1478:2346358] jxcore: stopAdvertisingAndListening: success
,2016-03-15 12:48:39.120 ThaliTest[1478:2346358] jxcore: stopListeningForAdvertisements
,2016-03-15 12:48:39.121 ThaliTest[1478:2346358] jxcore: stopListeningForAdvertisements: success
,ok 84 error should be null

,ok 85 error should be null

,# 24. should be able to call #startListeningForAdvertisements many times

,# teardown

,2016-03-15 12:48:39.428 ThaliTest[1478:2346358] jxcore: startListeningForAdvertisements
,2016-03-15 12:48:39.430 ThaliTest[1478:2346358] multipeer manager: start client restart timer: 0x14d54270
,2016-03-15 12:48:39.431 ThaliTest[1478:2346358] jxcore: startListeningForAdvertisements: success
,ok 86 error should be null

,ok 87 error should be null

,2016-03-15 12:48:39.459 ThaliTest[1478:2346358] jxcore: startListeningForAdvertisements
,2016-03-15 12:48:39.460 ThaliTest[1478:2346358] jxcore: startListeningForAdvertisements: success
,ok 88 error should be null

,ok 89 error should be null

,# setup

,2016-03-15 12:48:39.807 ThaliTest[1478:2346358] jxcore: stopAdvertisingAndListening
,2016-03-15 12:48:39.808 ThaliTest[1478:2346358] THEMultipeerManager stopping peer
,2016-03-15 12:48:39.808 ThaliTest[1478:2346358] jxcore: stopAdvertisingAndListening: success
,2016-03-15 12:48:39.810 ThaliTest[1478:2346358] jxcore: stopListeningForAdvertisements
2016-03-15 12:48:39.810 ThaliTest[1478:2346358] multipeer manager: stop client timer
,2016-03-15 12:48:39.813 ThaliTest[1478:2346358] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).

,ok 90 error should be null

,ok 91 error should be null

,# 25. should be able to call #startUpdateAdvertisingAndListening many times

,# teardown

,2016-03-15 12:48:41.312 ThaliTest[1478:2346358] jxcore: startUpdateAdvertisingAndListening
,2016-03-15 12:48:41.313 ThaliTest[1478:2346358] server: starting D00D3980-DA15-4582-8F26-46DE57DE4C09:1
,2016-03-15 12:48:41.314 ThaliTest[1478:2346358] multipeer manager: start client restart timer: 0x14d54270
,2016-03-15 12:48:41.316 ThaliTest[1478:2346358] THEMultipeerManager initialized peer D00D3980-DA15-4582-8F26-46DE57DE4C09:1
2016-03-15 12:48:41.316 ThaliTest[1478:2346358] jxcore: startUpdateAdvertisingAndListening: success
,ok 92 error should be null

,ok 93 error should be null

,2016-03-15 12:48:41.348 ThaliTest[1478:2346358] jxcore: startUpdateAdvertisingAndListening
2016-03-15 12:48:41.349 ThaliTest[1478:2346358] THEMultipeerManager stopping peer
,2016-03-15 12:48:41.350 ThaliTest[1478:2346358] multipeer manager: stop client timer
2016-03-15 12:48:41.351 ThaliTest[1478:2346358] server: starting D00D3980-DA15-4582-8F26-46DE57DE4C09:2
2016-03-15 12:48:41.352 ThaliTest[1478:2346358] multipeer manager,: start client restart timer: 0x14d54270
2016-03-15 12:48:41.352 ThaliTest[1478:2346358] THEMultipeerManager initialized peer D00D3980-DA15-4582-8F26-46DE57DE4C09:2
2016-03-15 12:48:41.352 ThaliTest[1478:2346358] jxcore: startUpdateAdvertisingAndListening: success
,ok 94 error should be null

,ok 95 error should be null

,# setup

,2016-03-15 12:48:41.883 ThaliTest[1478:2346358] jxcore: stopAdvertisingAndListening
,2016-03-15 12:48:41.883 ThaliTest[1478:2346358] THEMultipeerManager stopping peer
,2016-03-15 12:48:41.884 ThaliTest[1478:2346358] multipeer manager: stop client timer
,2016-03-15 12:48:41.885 ThaliTest[1478:2346358] jxcore: stopAdvertisingAndListening: success
2016-03-15 12:48:41.886 ThaliTest[1478:2346358] jxcore: stopListeningForAdvertisements
2016-03-15 12:48:41.887 ThaliTest[1478:2346358] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).

,ok 96 error should be null

,ok 97 error should be null

,# 26. should be able to call #stopAdvertisingAndListening many times

,# teardown

,2016-03-15 12:48:42.413 ThaliTest[1478:2346358] jxcore: stopAdvertisingAndListening
,2016-03-15 12:48:42.413 ThaliTest[1478:2346358] THEMultipeerManager stopping peer
,2016-03-15 12:48:42.414 ThaliTest[1478:2346358] jxcore: stopAdvertisingAndListening: success
,ok 98 error should be null

,ok 99 error should be null

,2016-03-15 12:48:42.419 ThaliTest[1478:2346358] jxcore: stopAdvertisingAndListening
,2016-03-15 12:48:42.420 ThaliTest[1478:2346358] THEMultipeerManager stopping peer
,2016-03-15 12:48:42.420 ThaliTest[1478:2346358] jxcore: stopAdvertisingAndListening: success
,ok 100 error should be null

,ok 101 error should be null

,# setup

,2016-03-15 12:48:42.765 ThaliTest[1478:2346358] jxcore: stopAdvertisingAndListening
,2016-03-15 12:48:42.766 ThaliTest[1478:2346358] THEMultipeerManager stopping peer
,2016-03-15 12:48:42.766 ThaliTest[1478:2346358] jxcore: stopAdvertisingAndListening: success
,2016-03-15 12:48:42.767 ThaliTest[1478:2346358] jxcore: stopListeningForAdvertisements
,2016-03-15 12:48:42.769 ThaliTest[1478:2346358] jxcore: stopListeningForAdvertisements: success
,ok 102 error should be null

,ok 103 error should be null

,# 27. #start should fail if called twice in a row

,# teardown

,ok 104 first call should succeed

,ok 105 first call should succeed

,ok 106 specific error should be returned

,# setup

,2016-03-15 12:48:50.728 ThaliTest[1478:2346358] jxcore: stopAdvertisingAndListening
,2016-03-15 12:48:50.729 ThaliTest[1478:2346358] THEMultipeerManager stopping peer
,2016-03-15 12:48:50.729 ThaliTest[1478:2346358] jxcore: stopAdvertisingAndListening: success
,2016-03-15 12:48:50.730 ThaliTest[1478:2346358] jxcore: stopListeningForAdvertisements
,2016-03-15 12:48:50.731 ThaliTest[1478:2346358] jxcore: stopListeningForAdvertisements: success
,ok 107 error should be null

,ok 108 error should be null

,# 28. does not emit duplicate discoveryAdvertisingStateUpdate

,# teardown

,2016-03-15 12:48:50.951 ThaliTest[1478:2346358] jxcore: startListeningForAdvertisements
,2016-03-15 12:48:50.952 ThaliTest[1478:2346358] multipeer manager: start client restart timer: 0x14d54270
,2016-03-15 12:48:50.954 ThaliTest[1478:2346358] jxcore: startListeningForAdvertisements: success
,2016-03-15 12:48:50.965 ThaliTest[1478:2346358] jxcore: startUpdateAdvertisingAndListening
,2016-03-15 12:48:50.966 ThaliTest[1478:2346358] server: starting D00D3980-DA15-4582-8F26-46DE57DE4C09:3
,2016-03-15 12:48:50.967 ThaliTest[1478:2346358] THEMultipeerManager initialized peer D00D3980-DA15-4582-8F26-46DE57DE4C09:3
2016-03-15 12:48:50.968 ThaliTest[1478:2346358] jxcore: startUpdateAdvertisingAndListening: success
,ok 109 called only once

,ok 110 discovery state matches

,ok 111 advertising state matches

,# setup

,2016-03-15 12:48:51.200 ThaliTest[1478:2346358] jxcore: stopAdvertisingAndListening
2016-03-15 12:48:51.200 ThaliTest[1478:2346358] THEMultipeerManager stopping peer
,2016-03-15 12:48:51.201 ThaliTest[1478:2346358] jxcore: stopAdvertisingAndListening: success
2016-03-15 12:48:51.202 ThaliTest[1478:2346358] jxcore: stopListeningForAdvertisements
2016-03-15 12:48:51.203 ThaliTest[1478:2346358] multipeer manager: stop client timer
,2016-03-15 12:48:51.205 ThaliTest[1478:2346358] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}

,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).

,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).

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

,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined

,ok 121 host address should match

,ok 122 port should match

,ok 123 host address should be null

,ok 124 port should should be null

,# setup

,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).

,ok 125 error should be null

,ok 126 error should be null

,# 32. Can call start/stopListeningForAdvertisements

,# teardown

,2016-03-15 12:49:01.483 ThaliTest[1478:2346358] jxcore: startListeningForAdvertisements
,2016-03-15 12:49:01.484 ThaliTest[1478:2346358] multipeer manager: start client restart timer: 0x14d54270
,2016-03-15 12:49:01.485 ThaliTest[1478:2346358] jxcore: startListeningForAdvertisements: success
,ok 127 Can call startListeningForAdvertisements without error

,2016-03-15 12:49:01.490 ThaliTest[1478:2346358] jxcore: stopListeningForAdvertisements
2016-03-15 12:49:01.491 ThaliTest[1478:2346358] multipeer manager: stop client timer
,2016-03-15 12:49:01.493 ThaliTest[1478:2346358] jxcore: stopListeningForAdvertisements: success
,ok 128 Can call stopListeningForAdvertisements without error

,# setup

,2016-03-15 12:49:01.787 ThaliTest[1478:2346358] jxcore: stopAdvertisingAndListening
,2016-03-15 12:49:01.788 ThaliTest[1478:2346358] THEMultipeerManager stopping peer
,2016-03-15 12:49:01.788 ThaliTest[1478:2346358] jxcore: stopAdvertisingAndListening: success
,2016-03-15 12:49:01.790 ThaliTest[1478:2346358] jxcore: stopListeningForAdvertisements
,2016-03-15 12:49:01.791 ThaliTest[1478:2346358] jxcore: stopListeningForAdvertisements: success
,# 33. Calling startListeningForAdvertisements twice is NOT an error

,# teardown

,2016-03-15 12:49:02.260 ThaliTest[1478:2346358] jxcore: startListeningForAdvertisements
,2016-03-15 12:49:02.261 ThaliTest[1478:2346358] multipeer manager: start client restart timer: 0x14d54270
,2016-03-15 12:49:02.262 ThaliTest[1478:2346358] jxcore: startListeningForAdvertisements: success
,ok 129 Can call startListeningForAdvertisements without error

,2016-03-15 12:49:02.266 ThaliTest[1478:2346358] jxcore: startListeningForAdvertisements
,2016-03-15 12:49:02.268 ThaliTest[1478:2346358] jxcore: startListeningForAdvertisements: success
,ok 130 Can call startListeningForAdvertisements twice without error

,# setup

,2016-03-15 12:49:02.398 ThaliTest[1478:2346358] jxcore: stopAdvertisingAndListening
,2016-03-15 12:49:02.398 ThaliTest[1478:2346358] THEMultipeerManager stopping peer
,2016-03-15 12:49:02.399 ThaliTest[1478:2346358] jxcore: stopAdvertisingAndListening: success
,2016-03-15 12:49:02.400 ThaliTest[1478:2346358] jxcore: stopListeningForAdvertisements
2016-03-15 12:49:02.400 ThaliTest[1478:2346358] multipeer manager: stop client timer
,2016-03-15 12:49:02.402 ThaliTest[1478:2346358] jxcore: stopListeningForAdvertisements: success
,# 34. Can call start/stopUpdateAdvertisingAndListening

,# teardown

,2016-03-15 12:49:02.897 ThaliTest[1478:2346358] jxcore: startUpdateAdvertisingAndListening
,2016-03-15 12:49:02.898 ThaliTest[1478:2346358] server: starting D00D3980-DA15-4582-8F26-46DE57DE4C09:4
,2016-03-15 12:49:02.899 ThaliTest[1478:2346358] multipeer manager: start client restart timer: 0x14d54270
2016-03-15 12:49:02.899 ThaliTest[1478:2346358] THEMultipeerManager initialized peer D00D3980-DA15-4582-8F26-46DE57DE4C09:4
2016-03-15 12:49:02.900 ,ThaliTest[1478:2346358] jxcore: startUpdateAdvertisingAndListening: success
ok 131 Can call startUpdateAdvertisingAndListening without error

,2016-03-15 12:49:02.903 ThaliTest[1478:2346358] jxcore: stopAdvertisingAndListening
2016-03-15 12:49:02.903 ThaliTest[1478:2346358] THEMultipeerManager stopping peer
2016-03-15 12:49:02.903 ThaliTest[1478:2346358] multipeer manager: stop client timer
2016-03-15 12:49:02.904 ThaliTest[1478:2346358] jxcore: stopAdvertisingAndListening: success
,ok 132 Can call stopAdvertisingAndListening without error

,# setup

,2016-03-15 12:49:03.803 ThaliTest[1478:2346358] jxcore: stopAdvertisingAndListening
,2016-03-15 12:49:03.804 ThaliTest[1478:2346358] THEMultipeerManager stopping peer
,2016-03-15 12:49:03.804 ThaliTest[1478:2346358] jxcore: stopAdvertisingAndListening: success
,2016-03-15 12:49:03.806 ThaliTest[1478:2346358] jxcore: stopListeningForAdvertisements
,2016-03-15 12:49:03.807 ThaliTest[1478:2346358] jxcore: stopListeningForAdvertisements: success
,# 35. Calling startUpdateAdvertisingAndListening twice is NOT an error

,# teardown

,2016-03-15 12:49:04.010 ThaliTest[1478:2346358] jxcore: startUpdateAdvertisingAndListening
2016-03-15 12:49:04.011 ThaliTest[1478:2346358] server: starting D00D3980-DA15-4582-8F26-46DE57DE4C09:5
,2016-03-15 12:49:04.012 ThaliTest[1478:2346358] multipeer manager: start client restart timer: 0x14d54270
2016-03-15 12:49:04.012 ThaliTest[1478:2346358] THEMultipeerManager initialized peer D00D3980-DA15-4582-8F26-46DE57DE4C09:5
2016-03-15 12:49:04.013 ,ThaliTest[1478:2346358] jxcore: startUpdateAdvertisingAndListening: success
ok 133 Can call startUpdateAdvertisingAndListening without error

,2016-03-15 12:49:04.016 ThaliTest[1478:2346358] jxcore: startUpdateAdvertisingAndListening
2016-03-15 12:49:04.016 ThaliTest[1478:2346358] THEMultipeerManager stopping peer
2016-03-15 12:49:04.016 ThaliTest[1478:2346358] multipeer manager: stop client ti,mer
2016-03-15 12:49:04.017 ThaliTest[1478:2346358] server: starting D00D3980-DA15-4582-8F26-46DE57DE4C09:6
2016-03-15 12:49:04.018 ThaliTest[1478:2346358] multipeer manager: start client restart timer: 0x14d54270
2016-03-15 12:49:04.018 ThaliTest[1478:,2346358] THEMultipeerManager initialized peer D00D3980-DA15-4582-8F26-46DE57DE4C09:6
2016-03-15 12:49:04.018 ThaliTest[1478:2346358] jxcore: startUpdateAdvertisingAndListening: success
ok 134 Can call startUpdateAdvertisingAndListening twice without error

,# setup

,2016-03-15 12:49:04.264 ThaliTest[1478:2346358] jxcore: stopAdvertisingAndListening
,2016-03-15 12:49:04.265 ThaliTest[1478:2346358] THEMultipeerManager stopping peer
,2016-03-15 12:49:04.265 ThaliTest[1478:2346358] multipeer manager: stop client timer
,2016-03-15 12:49:04.266 ThaliTest[1478:2346358] jxcore: stopAdvertisingAndListening: success
,2016-03-15 12:49:04.267 ThaliTest[1478:2346358] jxcore: stopListeningForAdvertisements
2016-03-15 12:49:04.269 ThaliTest[1478:2346358] jxcore: stopListeningForAdvertisements: success
,# 36. peerAvailabilityChange is called

,# teardown

,2016-03-15 12:49:04.488 ThaliTest[1478:2346358] jxcore: startUpdateAdvertisingAndListening
,2016-03-15 12:49:04.489 ThaliTest[1478:2346358] server: starting D00D3980-DA15-4582-8F26-46DE57DE4C09:7
,2016-03-15 12:49:04.490 ThaliTest[1478:2346358] multipeer manager: start client restart timer: 0x14d54270
,2016-03-15 12:49:04.491 ThaliTest[1478:2346358] THEMultipeerManager initialized peer D00D3980-DA15-4582-8F26-46DE57DE4C09:7
,2016-03-15 12:49:04.491 ThaliTest[1478:2346358] jxcore: startUpdateAdvertisingAndListening: success
ok 135 Can call startUpdateAdvertisingAndListeningwithout error

,2016-03-15 12:49:04.493 ThaliTest[1478:2346358] jxcore: startListeningForAdvertisements
,2016-03-15 12:49:04.496 ThaliTest[1478:2346358] jxcore: startListeningForAdvertisements: success
ok 136 Can call startListeningForAdvertisements without error

,2016-03-15 12:49:05.234 ThaliTest[1478:2346137] client: found new peer: 269C88B3-FCD7-4B25-9CB6-15E21901468C:7
,ok 137 peer must have peerIdentifier

,ok 138 peerIdentifier must be a string

,# setup

,2016-03-15 12:49:06.371 ThaliTest[1478:2346358] jxcore: stopAdvertisingAndListening
,2016-03-15 12:49:06.371 ThaliTest[1478:2346358] THEMultipeerManager stopping peer
,2016-03-15 12:49:06.372 ThaliTest[1478:2346358] jxcore: stopAdvertisingAndListening: success
,2016-03-15 12:49:06.374 ThaliTest[1478:2346358] jxcore: stopListeningForAdvertisements
2016-03-15 12:49:06.374 ThaliTest[1478:2346358] multipeer manager: stop client timer
2016-03-15 12:49:06.375 ThaliTest[1478:2346358] jxcore: stopListeningForAdvertisements: success
,# 37. Can connect to a remote peer

,# teardown

,2016-03-15 12:49:07.066 ThaliTest[1478:2346358] jxcore: startUpdateAdvertisingAndListening
,2016-03-15 12:49:07.067 ThaliTest[1478:2346358] server: starting D00D3980-DA15-4582-8F26-46DE57DE4C09:8
,2016-03-15 12:49:07.068 ThaliTest[1478:2346358] multipeer manager: start client restart timer: 0x14d54270
,2016-03-15 12:49:07.069 ThaliTest[1478:2346358] THEMultipeerManager initialized peer D00D3980-DA15-4582-8F26-46DE57DE4C09:8
2016-03-15 12:49:07.070 ThaliTest[1478:2346358] jxcore: startUpdateAdvertisingAndListening: success
ok 139 Can call startUpdateAdvertisingAndListening without error

,2016-03-15 12:49:07.072 ThaliTest[1478:2346358] jxcore: startListeningForAdvertisements
2016-03-15 12:49:07.073 ThaliTest[1478:2346358] jxcore: startListeningForAdvertisements: success
,ok 140 Can call startListeningForAdvertisements without error

,2016-03-15 12:49:08.384 ThaliTest[1478:2346137] multipeer session: reset timer
2016-03-15 12:49:08.385 ThaliTest[1478:2346137] server: rejecting invitation from 269C88B3-FCD7-4B25-9CB6-15E21901468C due to previous generation (D00D3980-DA15-4582-8F26-46DE5,7DE4C09:8 != D00D3980-DA15-4582-8F26-46DE57DE4C09:7)
,2016-03-15 12:49:09.319 ThaliTest[1478:2346137] client: found new peer: 269C88B3-FCD7-4B25-9CB6-15E21901468C:8
,2016-03-15 12:49:09.338 ThaliTest[1478:2346358] jxcore: connect 269C88B3-FCD7-4B25-9CB6-15E21901468C:8
,2016-03-15 12:49:09.339 ThaliTest[1478:2346358] client session: connect
2016-03-15 12:49:09.340 ThaliTest[1478:2346358] client session: stateChange:0->1 269C88B3-FCD7-4B25-9CB6-15E21901468C:8
,2016-03-15 12:49:12.103 ThaliTest[1478:2346788] client session: connected
2016-03-15 12:49:12.103 ThaliTest[1478:2346788] client session: stateChange:1->2 269C88B3-FCD7-4B25-9CB6-15E21901468C:8
,2016-03-15 12:49:12.110 ThaliTest[1478:2346778] client session: fireConnectCallback: 269C88B3-FCD7-4B25-9CB6-15E21901468C
2016-03-15 12:49:12.111 ThaliTest[1478:2346778] jxcore: connect: success
,{ clientPort: 0, serverPort: 0, listeningPort: 61728 }

,ok 141 Must have listeningPort

,ok 142 listeningPort must be a number

,ok 143 Connection must have clientPort

,ok 144 clientPort must be a number

,ok 145 Connection must have serverPort

,ok 146 serverPort must be a number

,ok 147 (unnamed assert)

,ok 148 (unnamed assert)

,# setup

,2016-03-15 12:49:12.430 ThaliTest[1478:2346358] jxcore: stopAdvertisingAndListening
2016-03-15 12:49:12.431 ThaliTest[1478:2346358] THEMultipeerManager stopping peer
,2016-03-15 12:49:12.431 ThaliTest[1478:2346358] jxcore: stopAdvertisingAndListening: success
2016-03-15 12:49:12.432 ThaliTest[1478:2346358] jxcore: stopListeningForAdvertisements
,2016-03-15 12:49:12.434 ThaliTest[1478:2346358] client session: disconnect
,2016-03-15 12:49:12.435 ThaliTest[1478:2346358] client session: stateChange:2->0 269C88B3-FCD7-4B25-9CB6-15E21901468C:8
,2016-03-15 12:49:12.455 ThaliTest[1478:2346358] multipeer manager: stop client timer
2016-03-15 12:49:12.456 ThaliTest[1478:2346358] jxcore: stopListeningForAdvertisements: success
,# 38. Can shift large amounts of data

,# teardown

,2016-03-15 12:49:13.952 ThaliTest[1478:2346358] jxcore: startUpdateAdvertisingAndListening
,2016-03-15 12:49:13.953 ThaliTest[1478:2346358] server: starting D00D3980-DA15-4582-8F26-46DE57DE4C09:9
,2016-03-15 12:49:13.954 ThaliTest[1478:2346358] multipeer manager: start client restart timer: 0x14d54270
2016-03-15 12:49:13.954 ThaliTest[1478:2346358] THEMultipeerManager initialized peer D00D3980-DA15-4582-8F26-46DE57DE4C09:9
,2016-03-15 12:49:13.954 ThaliTest[1478:2346358] jxcore: startUpdateAdvertisingAndListening: success
,ok 149 Can call startUpdateAdvertisingAndListening without error

,2016-03-15 12:49:13.958 ThaliTest[1478:2346358] jxcore: startListeningForAdvertisements
2016-03-15 12:49:13.958 ThaliTest[1478:2346358] jxcore: startListeningForAdvertisements: success
,ok 150 Can call startListeningForAdvertisements without error

,2016-03-15 12:49:14.022 ThaliTest[1478:2346137] client: found new peer: 269C88B3-FCD7-4B25-9CB6-15E21901468C:8
,2016-03-15 12:49:14.040 ThaliTest[1478:2346358] jxcore: connect 269C88B3-FCD7-4B25-9CB6-15E21901468C:8
,2016-03-15 12:49:14.041 ThaliTest[1478:2346358] client session: connect
2016-03-15 12:49:14.041 ThaliTest[1478:2346358] client session: stateChange:0->1 269C88B3-FCD7-4B25-9CB6-15E21901468C:8
,2016-03-15 12:49:15.054 ThaliTest[1478:2346137] multipeer session: reset timer
2016-03-15 12:49:15.054 ThaliTest[1478:2346137] server: rejecting invitation from 269C88B3-FCD7-4B25-9CB6-15E21901468C due to previous generation (D00D3980-DA15-4582-8F26-46DE5,7DE4C09:9 != D00D3980-DA15-4582-8F26-46DE57DE4C09:8)
,2016-03-15 12:49:16.297 ThaliTest[1478:2346788] client session: not connected 269C88B3-FCD7-4B25-9CB6-15E21901468C:8
,2016-03-15 12:49:16.297 ThaliTest[1478:2346788] client session: onLinkFailure: 269C88B3-FCD7-4B25-9CB6-15E21901468C
2016-03-15 12:49:16.298 ThaliTest[1478:2346788] client session: disconnect
,2016-03-15 12:49:16.298 ThaliTest[1478:2346788] client session: stateChange:1->0 269C88B3-FCD7-4B25-9CB6-15E21901468C:8
,2016-03-15 12:49:16.299 ThaliTest[1478:2346788] client session: fireConnectCallback: 269C88B3-FCD7-4B25-9CB6-15E21901468C
,2016-03-15 12:49:16.300 ThaliTest[1478:2346788] jxcore: connect: fail: Peer disconnected
,2016-03-15 12:49:33.956 ThaliTest[1478:2346137] multipeer manager: restart client
,2016-03-15 12:49:33.972 ThaliTest[1478:2346137] client: found updated peer: 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-15 12:49:53.956 ThaliTest[1478:2346137] multipeer manager: restart client
,2016-03-15 12:49:53.970 ThaliTest[1478:2346137] client: found existing peer: 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-15 12:50:13.956 ThaliTest[1478:2346137] multipeer manager: restart client
,2016-03-15 12:50:13.969 ThaliTest[1478:2346137] client: found existing peer: 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-15 12:50:33.956 ThaliTest[1478:2346137] multipeer manager: restart client
,2016-03-15 12:50:33.971 ThaliTest[1478:2346137] client: found existing peer: 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-15 12:50:53.956 ThaliTest[1478:2346137] multipeer manager: restart client
,2016-03-15 12:50:53.970 ThaliTest[1478:2346137] client: found existing peer: 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-15 12:51:13.956 ThaliTest[1478:2346137] multipeer manager: restart client
,2016-03-15 12:51:13.972 ThaliTest[1478:2346137] client: found existing peer: 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-15 12:51:33.956 ThaliTest[1478:2346137] multipeer manager: restart client
,2016-03-15 12:51:33.970 ThaliTest[1478:2346137] client: found existing peer: 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-15 12:51:53.955 ThaliTest[1478:2346137] multipeer manager: restart client
,2016-03-15 12:51:53.969 ThaliTest[1478:2346137] client: found existing peer: 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-15 12:52:13.956 ThaliTest[1478:2346137] multipeer manager: restart client
,2016-03-15 12:52:13.969 ThaliTest[1478:2346137] client: found existing peer: 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-15 12:52:33.955 ThaliTest[1478:2346137] multipeer manager: restart client
,2016-03-15 12:52:33.971 ThaliTest[1478:2346137] client: found existing peer: 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-15 12:52:53.956 ThaliTest[1478:2346137] multipeer manager: restart client
,2016-03-15 12:52:53.970 ThaliTest[1478:2346137] client: found existing peer: 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-15 12:53:13.956 ThaliTest[1478:2346137] multipeer manager: restart client
,2016-03-15 12:53:13.967 ThaliTest[1478:2346137] client: found existing peer: 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-15 12:53:33.956 ThaliTest[1478:2346137] multipeer manager: restart client
,2016-03-15 12:53:33.968 ThaliTest[1478:2346137] client: found existing peer: 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-15 12:53:53.956 ThaliTest[1478:2346137] multipeer manager: restart client
,2016-03-15 12:53:53.971 ThaliTest[1478:2346137] client: found existing peer: 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-15 12:54:13.956 ThaliTest[1478:2346137] multipeer manager: restart client
,2016-03-15 12:54:13.969 ThaliTest[1478:2346137] client: found existing peer: 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-15 12:54:33.956 ThaliTest[1478:2346137] multipeer manager: restart client
,2016-03-15 12:54:33.971 ThaliTest[1478:2346137] client: found existing peer: 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-15 12:54:53.956 ThaliTest[1478:2346137] multipeer manager: restart client
,2016-03-15 12:54:53.970 ThaliTest[1478:2346137] client: found existing peer: 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-15 12:55:13.956 ThaliTest[1478:2346137] multipeer manager: restart client
,2016-03-15 12:55:13.970 ThaliTest[1478:2346137] client: found existing peer: 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-15 12:55:33.956 ThaliTest[1478:2346137] multipeer manager: restart client
,2016-03-15 12:55:33.970 ThaliTest[1478:2346137] client: found existing peer: 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-15 12:55:53.956 ThaliTest[1478:2346137] multipeer manager: restart client
,2016-03-15 12:55:53.969 ThaliTest[1478:2346137] client: found existing peer: 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-15 12:56:13.956 ThaliTest[1478:2346137] multipeer manager: restart client
,2016-03-15 12:56:13.970 ThaliTest[1478:2346137] client: found existing peer: 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-15 12:56:33.956 ThaliTest[1478:2346137] multipeer manager: restart client
,2016-03-15 12:56:33.970 ThaliTest[1478:2346137] client: found existing peer: 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-15 12:56:53.956 ThaliTest[1478:2346137] multipeer manager: restart client
,2016-03-15 12:56:53.969 ThaliTest[1478:2346137] client: found existing peer: 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-15 12:57:13.956 ThaliTest[1478:2346137] multipeer manager: restart client
,2016-03-15 12:57:13.970 ThaliTest[1478:2346137] client: found existing peer: 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-15 12:57:33.956 ThaliTest[1478:2346137] multipeer manager: restart client
,2016-03-15 12:57:33.969 ThaliTest[1478:2346137] client: found existing peer: 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-15 12:57:53.956 ThaliTest[1478:2346137] multipeer manager: restart client
,2016-03-15 12:57:53.971 ThaliTest[1478:2346137] client: found existing peer: 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-15 12:58:13.956 ThaliTest[1478:2346137] multipeer manager: restart client
,2016-03-15 12:58:13.970 ThaliTest[1478:2346137] client: found existing peer: 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-15 12:58:33.956 ThaliTest[1478:2346137] multipeer manager: restart client
,2016-03-15 12:58:33.970 ThaliTest[1478:2346137] client: found existing peer: 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-15 12:58:53.956 ThaliTest[1478:2346137] multipeer manager: restart client
,2016-03-15 12:58:53.970 ThaliTest[1478:2346137] client: found existing peer: 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-15 12:59:13.956 ThaliTest[1478:2346137] multipeer manager: restart client
,2016-03-15 12:59:13.969 ThaliTest[1478:2346137] client: found existing peer: 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-15 12:59:33.955 ThaliTest[1478:2346137] multipeer manager: restart client
,2016-03-15 12:59:33.967 ThaliTest[1478:2346137] client: found existing peer: 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-15 12:59:53.956 ThaliTest[1478:2346137] multipeer manager: restart client
,2016-03-15 12:59:53.968 ThaliTest[1478:2346137] client: found existing peer: 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-15 13:00:13.955 ThaliTest[1478:2346137] multipeer manager: restart client
,2016-03-15 13:00:13.969 ThaliTest[1478:2346137] client: found existing peer: 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-15 13:00:33.956 ThaliTest[1478:2346137] multipeer manager: restart client
,2016-03-15 13:00:33.969 ThaliTest[1478:2346137] client: found existing peer: 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-15 13:00:53.956 ThaliTest[1478:2346137] multipeer manager: restart client
,2016-03-15 13:00:53.971 ThaliTest[1478:2346137] client: found existing peer: 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-15 13:01:13.955 ThaliTest[1478:2346137] multipeer manager: restart client
,2016-03-15 13:01:13.969 ThaliTest[1478:2346137] client: found existing peer: 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-15 13:01:33.955 ThaliTest[1478:2346137] multipeer manager: restart client
,2016-03-15 13:01:33.969 ThaliTest[1478:2346137] client: found existing peer: 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-15 13:01:53.956 ThaliTest[1478:2346137] multipeer manager: restart client
,2016-03-15 13:01:53.970 ThaliTest[1478:2346137] client: found existing peer: 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-15 13:02:13.956 ThaliTest[1478:2346137] multipeer manager: restart client
,2016-03-15 13:02:13.970 ThaliTest[1478:2346137] client: found existing peer: 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-15 13:02:33.956 ThaliTest[1478:2346137] multipeer manager: restart client
,2016-03-15 13:02:33.969 ThaliTest[1478:2346137] client: found existing peer: 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-15 13:02:53.956 ThaliTest[1478:2346137] multipeer manager: restart client
,2016-03-15 13:02:53.969 ThaliTest[1478:2346137] client: found existing peer: 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-15 13:03:13.955 ThaliTest[1478:2346137] multipeer manager: restart client
,2016-03-15 13:03:13.970 ThaliTest[1478:2346137] client: found existing peer: 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-15 13:03:33.956 ThaliTest[1478:2346137] multipeer manager: restart client
,2016-03-15 13:03:33.969 ThaliTest[1478:2346137] client: found existing peer: 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-15 13:03:53.956 ThaliTest[1478:2346137] multipeer manager: restart client
,2016-03-15 13:03:53.969 ThaliTest[1478:2346137] client: found existing peer: 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-15 13:04:13.956 ThaliTest[1478:2346137] multipeer manager: restart client
,2016-03-15 13:04:13.969 ThaliTest[1478:2346137] client: found existing peer: 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-15 13:04:33.956 ThaliTest[1478:2346137] multipeer manager: restart client
,2016-03-15 13:04:33.969 ThaliTest[1478:2346137] client: found existing peer: 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-15 13:04:53.956 ThaliTest[1478:2346137] multipeer manager: restart client
,2016-03-15 13:04:53.970 ThaliTest[1478:2346137] client: found existing peer: 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-15 13:05:13.956 ThaliTest[1478:2346137] multipeer manager: restart client
,2016-03-15 13:05:13.970 ThaliTest[1478:2346137] client: found existing peer: 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-15 13:05:33.956 ThaliTest[1478:2346137] multipeer manager: restart client
,2016-03-15 13:05:33.969 ThaliTest[1478:2346137] client: found existing peer: 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-15 13:05:53.956 ThaliTest[1478:2346137] multipeer manager: restart client
,2016-03-15 13:05:53.970 ThaliTest[1478:2346137] client: found existing peer: 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-15 13:06:13.956 ThaliTest[1478:2346137] multipeer manager: restart client
,2016-03-15 13:06:13.970 ThaliTest[1478:2346137] client: found existing peer: 269C88B3-FCD7-4B25-9CB6-15E21901468C:9

```
