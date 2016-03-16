#### Test 63012666c2ddc84_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/63012666c2ddc84/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/812B6574-535D-407F-8501-9B5F2D068F44/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/812B6574-535D-407F-8501-9B5F2D068F44/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/63012666c2ddc84/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/63012666c2ddc84/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/DEAE8E3E-4282-4A48-91F9-96BC729208AC/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50067"
,(lldb)     command script import "/tmp/812B6574-535D-407F-8501-9B5F2D068F44/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-16 06:27:40.660 ThaliTest[1166:2596243] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4FC58FDA-017F-4D6B-9602-85651FD8A4C9/Library/Cookies/Cookies.binarycookies
,2016-03-16 06:27:40.788 ThaliTest[1166:2596243] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-16 06:27:40.790 ThaliTest[1166:2596243] Multi-tasking -> Device: YES, App: YES
,2016-03-16 06:27:40.817 ThaliTest[1166:2596243] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-16 06:27:42.878 ThaliTest[1166:2596243] Using UIWebView
,2016-03-16 06:27:42.882 ThaliTest[1166:2596243] [CDVTimer][handleopenurl] 0.283003ms
,2016-03-16 06:27:42.888 ThaliTest[1166:2596243] [CDVTimer][intentandnavigationfilter] 5.187035ms
2016-03-16 06:27:42.889 ThaliTest[1166:2596243] [CDVTimer][gesturehandler] 0.388026ms
2016-03-16 06:27:42.889 ThaliTest[1166:2596243] [CDVTimer][TotalPluginStartup] 7.021010ms
,2016-03-16 06:27:51.066 ThaliTest[1166:2596243] Resetting plugins due to page load.
,2016-03-16 06:27:54.683 ThaliTest[1166:2596243] Finished load of: file:///var/mobile/Containers/Bundle/Application/DEAE8E3E-4282-4A48-91F9-96BC729208AC/ThaliTest.app/www/index.html
,2016-03-16 06:27:54.889 ThaliTest[1166:2596243] JXcore Cordova plugin initializing
2016-03-16 06:27:54.890 ThaliTest[1166:2596423] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,2016-03-16 06:28:03.504 ThaliTest[1166:2596423] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-16 06:28:03.505 ThaliTest[1166:2596423] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-16 06:28:03.505 ThaliTest[1166:2596423] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

,2016-03-16 06:28:03.511 ThaliTest[1166:2596423] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

,My device name is: Apple-Iphone5-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DEAE8E3E-4282-4A48-91F9-96BC729208AC/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DEAE8E3E-4282-4A48-91F9-96BC729208AC/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DEAE8E3E-4282-4A48-91F9-96BC729208AC/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DEAE8E3E-4282-4A48-91F9-96BC729208AC/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DEAE8E3E-4282-4A48-91F9-96BC729208AC/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DEAE8E3E-4282-4A48-91F9-96BC729208AC/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DEAE8E3E-4282-4A48-91F9-96BC729208AC/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DEAE8E3E-4282-4A48-91F9-96BC729208AC/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DEAE8E3E-4282-4A48-91F9-96BC729208AC/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DEAE8E3E-4282-4A48-91F9-96BC729208AC/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DEAE8E3E-4282-4A48-91F9-96BC729208AC/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DEAE8E3E-4282-4A48-91F9-96BC729208AC/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DEAE8E3E-4282-4A48-91F9-96BC729208AC/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DEAE8E3E-4282-4A48-91F9-96BC729208AC/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DEAE8E3E-4282-4A48-91F9-96BC729208AC/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DEAE8E3E-4282-4A48-91F9-96BC729208AC/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DEAE8E3E-4282-4A48-91F9-96BC729208AC/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DEAE8E3E-4282-4A48-91F9-96BC729208AC/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,2016-03-16 06:28:21.855 ThaliTest[1166:2596243] THREAD WARNING: ['JXcore'] took '14118.687988' ms. Plugin should use a background thread.
,2016-03-16 06:28:21.856 ThaliTest[1166:2596377] void SendDelegateMessage(NSInvocation *): delegate (webView:decidePolicyForNavigationAction:request:frame:decisionListener:) failed to return after waiting 10 seconds. main run loop mode: kCFRunLoopDefaultMode
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

ok 16 incoming should survive
,
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

ok 61 testing promises

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

ok 93 error should be null

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

ok 105 first call should succeed

,ok 106 specific error should be returned

,# setup

,ok 107 error should be null

,ok 108 error should be null

,# 28. does not emit duplicate discoveryAdvertisingStateUpdate

,# teardown

,ok 109 called only once

ok 110 discovery state matches

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

ok 117 error should be null

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

,2016-03-16 06:32:28.380 ThaliTest[1166:2596423] jxcore: startListeningForAdvertisements
2016-03-16 06:32:28.381 ThaliTest[1166:2596423] multipeer manager: start client restart timer: 0x145ba300
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdat,eNonTCP: {"advertisingActive":false,"discoveryActive":true}

2016-03-16 06:32:28.382 ThaliTest[1166:2596423] jxcore: startListeningForAdvertisements: success
ok 127 Can call startListeningForAdvertisements without error

,2016-03-16 06:32:28.383 ThaliTest[1166:2596423] jxcore: stopListeningForAdvertisements
2016-03-16 06:32:28.384 ThaliTest[1166:2596423] multipeer manager: stop client timer
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}

2016-03-16 06:32:28.385 ThaliTest[1166:2596423] jxcore: stopListeningForAdvertisements: success
,ok 128 Can call stopListeningForAdvertisements without error

# setup

,2016-03-16 06:32:28.652 ThaliTest[1166:2596423] jxcore: stopListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}

2016-03-16 06:32:28.653 ThaliTest[1166:2596423] jxcore: stopListeningForAdvertisements: success
,ok 129 Should be able to call stopListeningForAdvertisments in teardown

,2016-03-16 06:32:28.654 ThaliTest[1166:2596423] jxcore: stopAdvertisingAndListening
2016-03-16 06:32:28.655 ThaliTest[1166:2596423] THEMultipeerManager stopping peer
2016-03-16 06:32:28.655 ThaliTest[1166:2596423] jxcore: stopAdvertisingAndListening: success
ok 130 Should be able to call stopAdvertisingAndListening in teardown

,# 33. Calling startListeningForAdvertisements twice is NOT an error

,# teardown

,2016-03-16 06:32:28.879 ThaliTest[1166:2596423] jxcore: startListeningForAdvertisements
2016-03-16 06:32:28.879 ThaliTest[1166:2596423] multipeer manager: start client restart timer: 0x145ba300
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}

,2016-03-16 06:32:28.881 ThaliTest[1166:2596423] jxcore: startListeningForAdvertisements: success
,ok 131 Can call startListeningForAdvertisements without error

,2016-03-16 06:32:28.883 ThaliTest[1166:2596423] jxcore: startListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}

2016-03-16 06:32:28.885 ThaliTest[1166:2596423] jxcore: startListeningForAdvertisements: success
,ok 132 Can call startListeningForAdvertisements twice without error

# setup

,2016-03-16 06:32:29.297 ThaliTest[1166:2596423] jxcore: stopListeningForAdvertisements
2016-03-16 06:32:29.298 ThaliTest[1166:2596423] multipeer manager: stop client timer
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}

,2016-03-16 06:32:29.299 ThaliTest[1166:2596423] jxcore: stopListeningForAdvertisements: success
,ok 133 Should be able to call stopListeningForAdvertisments in teardown

2016-03-16 06:32:29.300 ThaliTest[1166:2596423] jxcore: stopAdvertisingAndListening
2016-03-16 06:32:29.300 ThaliTest[1166:2596423] THEMultipeerManager stopping peer
,2016-03-16 06:32:29.300 ThaliTest[1166:2596423] jxcore: stopAdvertisingAndListening: success
ok 134 Should be able to call stopAdvertisingAndListening in teardown

,# 34. Can call start/stopUpdateAdvertisingAndListening

,# teardown

,2016-03-16 06:32:29.882 ThaliTest[1166:2596423] jxcore: startUpdateAdvertisingAndListening
2016-03-16 06:32:29.882 ThaliTest[1166:2596423] server: starting 7579825C-F152-45B2-BE5B-E01EEC4FE5D6:1
2016-03-16 06:32:29.883 ThaliTest[1166:2596423] multipeer m,anager: start client restart timer: 0x145ba300
2016-03-16 06:32:29.883 ThaliTest[1166:2596423] THEMultipeerManager initialized peer 7579825C-F152-45B2-BE5B-E01EEC4FE5D6:1
2016-03-16 06:32:29.883 ThaliTest[1166:2596423] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 135 Can call startUpdateAdvertisingAndListening without error

,2016-03-16 06:32:29.885 ThaliTest[1166:2596423] jxcore: stopAdvertisingAndListening
2016-03-16 06:32:29.885 ThaliTest[1166:2596423] THEMultipeerManager stopping peer
2016-03-16 06:32:29.885 ThaliTest[1166:2596423] multipeer manager: stop client timer
20,16-03-16 06:32:29.885 ThaliTest[1166:2596423] jxcore: stopAdvertisingAndListening: success
ok 136 Can call stopAdvertisingAndListening without error

,# setup

,2016-03-16 06:32:30.284 ThaliTest[1166:2596423] jxcore: stopListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}

,2016-03-16 06:32:30.285 ThaliTest[1166:2596423] jxcore: stopListeningForAdvertisements: success
,ok 137 Should be able to call stopListeningForAdvertisments in teardown

,2016-03-16 06:32:30.287 ThaliTest[1166:2596423] jxcore: stopAdvertisingAndListening
2016-03-16 06:32:30.287 ThaliTest[1166:2596423] THEMultipeerManager stopping peer
,2016-03-16 06:32:30.287 ThaliTest[1166:2596423] jxcore: stopAdvertisingAndListening: success
,ok 138 Should be able to call stopAdvertisingAndListening in teardown

,# 35. Calling startUpdateAdvertisingAndListening twice is NOT an error

,# teardown

,2016-03-16 06:32:30.749 ThaliTest[1166:2596423] jxcore: startUpdateAdvertisingAndListening
2016-03-16 06:32:30.749 ThaliTest[1166:2596423] server: starting 7579825C-F152-45B2-BE5B-E01EEC4FE5D6:2
2016-03-16 06:32:30.749 ThaliTest[1166:2596423] multipeer m,anager: start client restart timer: 0x145ba300
2016-03-16 06:32:30.750 ThaliTest[1166:2596423] THEMultipeerManager initialized peer 7579825C-F152-45B2-BE5B-E01EEC4FE5D6:2
2016-03-16 06:32:30.750 ThaliTest[1166:2596423] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 139 Can call startUpdateAdvertisingAndListening without error

,2016-03-16 06:32:30.751 ThaliTest[1166:2596423] jxcore: startUpdateAdvertisingAndListening
2016-03-16 06:32:30.751 ThaliTest[1166:2596423] THEMultipeerManager stopping peer
2016-03-16 06:32:30.752 ThaliTest[1166:2596423] multipeer manager: stop client ti,mer
2016-03-16 06:32:30.752 ThaliTest[1166:2596423] server: starting 7579825C-F152-45B2-BE5B-E01EEC4FE5D6:3
,2016-03-16 06:32:30.753 ThaliTest[1166:2596423] multipeer manager: start client restart timer: 0x145ba300
2016-03-16 06:32:30.753 ThaliTest[1166:2596423] THEMultipeerManager initialized peer 7579825C-F152-45B2-BE5B-E01EEC4FE5D6:3
,2016-03-16 06:32:30.753 ThaliTest[1166:2596423] jxcore: startUpdateAdvertisingAndListening: success
,ok 140 Can call startUpdateAdvertisingAndListening twice without error

# setup

,2016-03-16 06:32:30.830 ThaliTest[1166:2596423] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}

2016-03-16 06:32:30.831 ThaliTest[1166:2596423] jxcore: stopListeningForAdvertisements: success
,ok 141 Should be able to call stopListeningForAdvertisments in teardown

,2016-03-16 06:32:30.833 ThaliTest[1166:2596423] jxcore: stopAdvertisingAndListening
,2016-03-16 06:32:30.834 ThaliTest[1166:2596423] THEMultipeerManager stopping peer
,2016-03-16 06:32:30.835 ThaliTest[1166:2596423] multipeer manager: stop client timer
,2016-03-16 06:32:30.836 ThaliTest[1166:2596423] jxcore: stopAdvertisingAndListening: success
,ok 142 Should be able to call stopAdvertisingAndListening in teardown

,# 36. peerAvailabilityChange is called

,# teardown

,2016-03-16 06:32:31.199 ThaliTest[1166:2596423] jxcore: startUpdateAdvertisingAndListening
2016-03-16 06:32:31.199 ThaliTest[1166:2596423] server: starting 7579825C-F152-45B2-BE5B-E01EEC4FE5D6:4
2016-03-16 06:32:31.199 ThaliTest[1166:2596423] multipeer m,anager: start client restart timer: 0x145ba300
2016-03-16 06:32:31.199 ThaliTest[1166:2596423] THEMultipeerManager initialized peer 7579825C-F152-45B2-BE5B-E01EEC4FE5D6:4
2016-03-16 06:32:31.200 ThaliTest[1166:2596423] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 143 Can call startUpdateAdvertisingAndListeningwithout error

2016-03-16 06:32:31.201 ThaliTest[1166:2596423] jxcore: startListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}

,2016-03-16 06:32:31.202 ThaliTest[1166:2596423] jxcore: startListeningForAdvertisements: success
ok 144 Can call startListeningForAdvertisements without error

,2016-03-16 06:32:32.206 ThaliTest[1166:2596243] client: found new peer: 03F2872D-2889-439A-8812-7222B677B744:4
,ok 145 peers must be an array

,ok 146 peers must not be zero-length

,ok 147 peer must have peerIdentifier

,ok 148 peerIdentifier must be a string

,ok 149 peer must have peerAvailable

,ok 150 peer must have pleaseConnect

,# setup

,2016-03-16 06:32:32.373 ThaliTest[1166:2596423] jxcore: stopListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}

2016-03-16 06:32:32.374 ThaliTest[1166:2596423] jxcore: stopListeningForAdvertisements: success
,ok 151 Should be able to call stopListeningForAdvertisments in teardown

,2016-03-16 06:32:32.376 ThaliTest[1166:2596423] jxcore: stopAdvertisingAndListening
2016-03-16 06:32:32.377 ThaliTest[1166:2596423] THEMultipeerManager stopping peer
2016-03-16 06:32:32.377 ThaliTest[1166:2596423] multipeer manager: stop client timer
2016-03-16 06:32:32.377 ThaliTest[1166:2596423] jxcore: stopAdvertisingAndListening: success
ok 152 Should be able to call stopAdvertisingAndListening in teardown

,# 37. Can connect to a remote peer

,# teardown

,2016-03-16 06:32:32.549 ThaliTest[1166:2596423] jxcore: startUpdateAdvertisingAndListening
2016-03-16 06:32:32.549 ThaliTest[1166:2596423] server: starting 7579825C-F152-45B2-BE5B-E01EEC4FE5D6:5
,2016-03-16 06:32:32.550 ThaliTest[1166:2596423] multipeer manager: start client restart timer: 0x145ba300
2016-03-16 06:32:32.550 ThaliTest[1166:2596423] THEMultipeerManager initialized peer 7579825C-F152-45B2-BE5B-E01EEC4FE5D6:5
2016-03-16 06:32:32.551 ,ThaliTest[1166:2596423] jxcore: startUpdateAdvertisingAndListening: success
,ok 153 Can call startUpdateAdvertisingAndListening without error

2016-03-16 06:32:32.552 ThaliTest[1166:2596423] jxcore: startListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}

2016-03-16 06:32:32.553 ThaliTest[1166:2596423] jxcore: startListeningForAdvertisements: success
,ok 154 Can call startListeningForAdvertisements without error

,2016-03-16 06:32:33.503 ThaliTest[1166:2596243] client: found new peer: 03F2872D-2889-439A-8812-7222B677B744:4
,[ { peerAvailable: 1,
    peerIdentifier: '03F2872D-2889-439A-8812-7222B677B744:4',
    pleaseConnect: 0 } ]

,2016-03-16 06:32:33.509 ThaliTest[1166:2596423] jxcore: connect 03F2872D-2889-439A-8812-7222B677B744:4
2016-03-16 06:32:33.509 ThaliTest[1166:2596423] client session: connect
2016-03-16 06:32:33.509 ThaliTest[1166:2596423] client session: stateChange:0->1 03F2872D-2889-439A-8812-7222B677B744:4
,2016-03-16 06:32:34.869 ThaliTest[1166:2596243] multipeer session: reset timer
2016-03-16 06:32:34.869 ThaliTest[1166:2596243] server: rejecting invitation from 03F2872D-2889-439A-8812-7222B677B744 due to previous generation (7579825C-F152-45B2-BE5B-E01EE,C4FE5D6:5 != 7579825C-F152-45B2-BE5B-E01EEC4FE5D6:4)
,2016-03-16 06:32:34.871 ThaliTest[1166:2597178] client session: not connected 03F2872D-2889-439A-8812-7222B677B744:4
2016-03-16 06:32:34.871 ThaliTest[1166:2597178] client session: onLinkFailure: 03F2872D-2889-439A-8812-7222B677B744
,2016-03-16 06:32:34.871 ThaliTest[1166:2597178] client session: disconnect
2016-03-16 06:32:34.874 ThaliTest[1166:2597178] client session: stateChange:1->0 03F2872D-2889-439A-8812-7222B677B744:4
,2016-03-16 06:32:34.876 ThaliTest[1166:2597178] client session: fireConnectCallback: 03F2872D-2889-439A-8812-7222B677B744
2016-03-16 06:32:34.876 ThaliTest[1166:2597178] jxcore: connect: fail: Peer disconnected
,2016-03-16 06:32:37.889 ThaliTest[1166:2596423] jxcore: connect 03F2872D-2889-439A-8812-7222B677B744:4
2016-03-16 06:32:37.890 ThaliTest[1166:2596423] client session: connect
2016-03-16 06:32:37.890 ThaliTest[1166:2596423] client session: stateChange:0->1 03F2872D-2889-439A-8812-7222B677B744:4
,2016-03-16 06:32:37.997 ThaliTest[1166:2597190] client session: not connected 03F2872D-2889-439A-8812-7222B677B744:4
,2016-03-16 06:32:37.999 ThaliTest[1166:2597190] client session: onLinkFailure: 03F2872D-2889-439A-8812-7222B677B744
2016-03-16 06:32:37.999 ThaliTest[1166:2597190] client session: disconnect
2016-03-16 06:32:38.000 ThaliTest[1166:2597190] client session:, stateChange:1->0 03F2872D-2889-439A-8812-7222B677B744:4
2016-03-16 06:32:38.000 ThaliTest[1166:2597190] client session: fireConnectCallback: 03F2872D-2889-439A-8812-7222B677B744
2016-03-16 06:32:38.000 ThaliTest[1166:2597190] jxcore: connect: fail: Peer disconnected
,2016-03-16 06:32:41.003 ThaliTest[1166:2596423] jxcore: connect 03F2872D-2889-439A-8812-7222B677B744:4
2016-03-16 06:32:41.004 ThaliTest[1166:2596423] client session: connect
2016-03-16 06:32:41.004 ThaliTest[1166:2596423] client session: stateChange:0->,1 03F2872D-2889-439A-8812-7222B677B744:4
,2016-03-16 06:32:41.091 ThaliTest[1166:2597190] client session: not connected 03F2872D-2889-439A-8812-7222B677B744:4
2016-03-16 06:32:41.092 ThaliTest[1166:2597190] client session: onLinkFailure: 03F2872D-2889-439A-8812-7222B677B744
2016-03-16 06:32:41.0,92 ThaliTest[1166:2597190] client session: disconnect
2016-03-16 06:32:41.092 ThaliTest[1166:2597190] client session: stateChange:1->0 03F2872D-2889-439A-8812-7222B677B744:4
2016-03-16 06:32:41.093 ThaliTest[1166:2597190] client session: fireConnectCallb,ack: 03F2872D-2889-439A-8812-7222B677B744
2016-03-16 06:32:41.093 ThaliTest[1166:2597190] jxcore: connect: fail: Peer disconnected
,2016-03-16 06:32:44.104 ThaliTest[1166:2596423] jxcore: connect 03F2872D-2889-439A-8812-7222B677B744:4
2016-03-16 06:32:44.105 ThaliTest[1166:2596423] client session: connect
2016-03-16 06:32:44.105 ThaliTest[1166:2596423] client session: stateChange:0->1 03F2872D-2889-439A-8812-7222B677B744:4
,2016-03-16 06:32:44.690 ThaliTest[1166:2597178] client session: not connected 03F2872D-2889-439A-8812-7222B677B744:4
2016-03-16 06:32:44.690 ThaliTest[1166:2597178] client session: onLinkFailure: 03F2872D-2889-439A-8812-7222B677B744
2016-03-16 06:32:44.6,90 ThaliTest[1166:2597178] client session: disconnect
2016-03-16 06:32:44.690 ThaliTest[1166:2597178] client session: stateChange:1->0 03F2872D-2889-439A-8812-7222B677B744:4
2016-03-16 06:32:44.692 ThaliTest[1166:2597178] client session: fireConnectCallback: 03F2872D-2889-439A-8812-7222B677B744
2016-03-16 06:32:44.692 ThaliTest[1166:2597178] jxcore: connect: fail: Peer disconnected
,2016-03-16 06:32:47.697 ThaliTest[1166:2596423] jxcore: connect 03F2872D-2889-439A-8812-7222B677B744:4
2016-03-16 06:32:47.698 ThaliTest[1166:2596423] client session: connect
2016-03-16 06:32:47.698 ThaliTest[1166:2596423] client session: stateChange:0->1 03F2872D-2889-439A-8812-7222B677B744:4
,2016-03-16 06:32:47.837 ThaliTest[1166:2597190] client session: not connected 03F2872D-2889-439A-8812-7222B677B744:4
2016-03-16 06:32:47.837 ThaliTest[1166:2597190] client session: onLinkFailure: 03F2872D-2889-439A-8812-7222B677B744
2016-03-16 06:32:47.8,37 ThaliTest[1166:2597190] client session: disconnect
2016-03-16 06:32:47.837 ThaliTest[1166:2597190] client session: stateChange:1->0 03F2872D-2889-439A-8812-7222B677B744:4
2016-03-16 06:32:47.839 ThaliTest[1166:2597190] client session: fireConnectCallb,ack: 03F2872D-2889-439A-8812-7222B677B744
2016-03-16 06:32:47.839 ThaliTest[1166:2597190] jxcore: connect: fail: Peer disconnected
,2016-03-16 06:32:50.848 ThaliTest[1166:2596423] jxcore: connect 03F2872D-2889-439A-8812-7222B677B744:4
2016-03-16 06:32:50.848 ThaliTest[1166:2596423] client session: connect
2016-03-16 06:32:50.849 ThaliTest[1166:2596423] client session: stateChange:0->1 03F2872D-2889-439A-8812-7222B677B744:4
,2016-03-16 06:32:52.025 ThaliTest[1166:2597192] client session: not connected 03F2872D-2889-439A-8812-7222B677B744:4
2016-03-16 06:32:52.026 ThaliTest[1166:2597192] client session: onLinkFailure: 03F2872D-2889-439A-8812-7222B677B744
,2016-03-16 06:32:52.026 ThaliTest[1166:2597192] client session: disconnect
2016-03-16 06:32:52.027 ThaliTest[1166:2597192] client session: stateChange:1->0 03F2872D-2889-439A-8812-7222B677B744:4
2016-03-16 06:32:52.028 ThaliTest[1166:2597192] client sess,ion: fireConnectCallback: 03F2872D-2889-439A-8812-7222B677B744
2016-03-16 06:32:52.028 ThaliTest[1166:2597192] jxcore: connect: fail: Peer disconnected
,2016-03-16 06:32:52.551 ThaliTest[1166:2596243] multipeer manager: restart client
,2016-03-16 06:32:52.564 ThaliTest[1166:2596243] client: found updated peer: 03F2872D-2889-439A-8812-7222B677B744:5
[ { peerAvailable: 1,
    peerIdentifier: '03F2872D-2889-439A-8812-7222B677B744:5',
    pleaseConnect: 0 } ]

2016-03-16 06:32:52.566 Th,aliTest[1166:2596423] jxcore: connect 03F2872D-2889-439A-8812-7222B677B744:5
2016-03-16 06:32:52.567 ThaliTest[1166:2596423] client session: connect
2016-03-16 06:32:52.567 ThaliTest[1166:2596423] client session: stateChange:0->1 03F2872D-2889-439A-8812-,7222B677B744:5
,2016-03-16 06:32:55.030 ThaliTest[1166:2596423] jxcore: connect 03F2872D-2889-439A-8812-7222B677B744:4
2016-03-16 06:32:55.031 ThaliTest[1166:2596423] client: already connect(ing/ed) to 03F2872D-2889-439A-8812-7222B677B744:4
2016-03-16 06:32:55.031 ThaliTest[1166:2596423] jxcore: connect: fail: Aleady connecting
,2016-03-16 06:32:55.572 ThaliTest[1166:2597172] client session: connected
2016-03-16 06:32:55.572 ThaliTest[1166:2597172] client session: stateChange:1->2 03F2872D-2889-439A-8812-7222B677B744:5
,2016-03-16 06:32:55.577 ThaliTest[1166:2597172] client session: fireConnectCallback: 03F2872D-2889-439A-8812-7222B677B744
,2016-03-16 06:32:55.578 ThaliTest[1166:2597172] jxcore: connect: success
,{ clientPort: 0, serverPort: 0, listeningPort: 61809 }

ok 155 Must have listeningPort

ok 156 listeningPort must be a number

,ok 157 Connection must have clientPort

,ok 158 clientPort must be a number

,ok 159 Connection must have serverPort

,ok 160 serverPort must be a number

,ok 161 (unnamed assert)

,ok 162 (unnamed assert)

,# setup

,2016-03-16 06:32:57.590 ThaliTest[1166:2596423] jxcore: stopListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}

,2016-03-16 06:32:57.591 ThaliTest[1166:2596423] jxcore: stopListeningForAdvertisements: success
,ok 163 Should be able to call stopListeningForAdvertisments in teardown

2016-03-16 06:32:57.593 ThaliTest[1166:2596423] jxcore: stopAdvertisingAndListening
2016-03-16 06:32:57.593 ThaliTest[1166:2596423] THEMultipeerManager stopping peer
2016-03-16 06,:32:57.593 ThaliTest[1166:2596423] client session: disconnect
2016-03-16 06:32:57.593 ThaliTest[1166:2596423] client session: stateChange:2->0 03F2872D-2889-439A-8812-7222B677B744:5
,2016-03-16 06:32:57.608 ThaliTest[1166:2596423] multipeer manager: stop client timer
2016-03-16 06:32:57.610 ThaliTest[1166:2596423] jxcore: stopAdvertisingAndListening: success
,ok 164 Should be able to call stopAdvertisingAndListening in teardown

,# 38. Can shift large amounts of data

,2016-03-16 06:32:58.043 ThaliTest[1166:2596423] jxcore: connect 03F2872D-2889-439A-8812-7222B677B744:4
2016-03-16 06:32:58.043 ThaliTest[1166:2596423] jxcore: connect: fail: Start browsing first
,# teardown

,2016-03-16 06:32:58.786 ThaliTest[1166:2596423] jxcore: startUpdateAdvertisingAndListening
,2016-03-16 06:32:58.787 ThaliTest[1166:2596423] server: starting 7579825C-F152-45B2-BE5B-E01EEC4FE5D6:6
,2016-03-16 06:32:58.789 ThaliTest[1166:2596423] multipeer manager: start client restart timer: 0x145ba300
,2016-03-16 06:32:58.797 ThaliTest[1166:2596423] THEMultipeerManager initialized peer 7579825C-F152-45B2-BE5B-E01EEC4FE5D6:6
,2016-03-16 06:32:58.798 ThaliTest[1166:2596423] jxcore: startUpdateAdvertisingAndListening: success
,ok 165 Can call startUpdateAdvertisingAndListening without error

,2016-03-16 06:32:58.801 ThaliTest[1166:2596423] jxcore: startListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}

,2016-03-16 06:32:58.804 ThaliTest[1166:2596423] jxcore: startListeningForAdvertisements: success
,ok 166 Can call startListeningForAdvertisements without error

,2016-03-16 06:32:59.517 ThaliTest[1166:2596243] client: found new peer: 03F2872D-2889-439A-8812-7222B677B744:5
2016-03-16 06:32:59.519 ThaliTest[1166:2596423] jxcore: connect 03F2872D-2889-439A-8812-7222B677B744:5
2016-03-16 06:32:59.519 ThaliTest[1166:2596423] client session: connect
2016-03-16 06:32:59.519 ThaliTest[1166:2596423] client session: stateChange:0->1 03F2872D-2889-439A-8812-7222B677B744:5
,2016-03-16 06:33:00.409 ThaliTest[1166:2596243] multipeer session: reset timer
2016-03-16 06:33:00.410 ThaliTest[1166:2596243] server: rejecting invitation from 03F2872D-2889-439A-8812-7222B677B744 due to previous generation (7579825C-F152-45B2-BE5B-E01EEC4FE5D6:6 != 7579825C-F152-45B2-BE5B-E01EEC4FE5D6:5)
,2016-03-16 06:33:01.058 ThaliTest[1166:2596423] jxcore: connect 03F2872D-2889-439A-8812-7222B677B744:4
2016-03-16 06:33:01.059 ThaliTest[1166:2596423] client: already connect(ing/ed) to 03F2872D-2889-439A-8812-7222B677B744:4
2016-03-16 06:33:01.059 ThaliTest[1166:2596423] jxcore: connect: fail: Aleady connecting
,2016-03-16 06:33:01.159 ThaliTest[1166:2597179] client session: not connected 03F2872D-2889-439A-8812-7222B677B744:5
2016-03-16 06:33:01.160 ThaliTest[1166:2597179] client session: onLinkFailure: 03F2872D-2889-439A-8812-7222B677B744
2016-03-16 06:33:01.160 ThaliTest[1166:2597179] client session: disconnect
2016-03-16 06:33:01.160 ThaliTest[1166:2597179] client session: stateChange:1->0 03F2872D-2889-439A-8812-7222B677B744:5
,2016-03-16 06:33:01.162 ThaliTest[1166:2597179] client session: fireConnectCallback: 03F2872D-2889-439A-8812-7222B677B744
2016-03-16 06:33:01.162 ThaliTest[1166:2597179] jxcore: connect: fail: Peer disconnected
,2016-03-16 06:33:04.070 ThaliTest[1166:2596423] jxcore: connect 03F2872D-2889-439A-8812-7222B677B744:4
2016-03-16 06:33:04.070 ThaliTest[1166:2596423] client session: connect
2016-03-16 06:33:04.071 ThaliTest[1166:2596423] client session: stateChange:0->1 03F2872D-2889-439A-8812-7222B677B744:5
,2016-03-16 06:33:04.155 ThaliTest[1166:2597192] client session: not connected 03F2872D-2889-439A-8812-7222B677B744:5
2016-03-16 06:33:04.156 ThaliTest[1166:2597192] client session: onLinkFailure: 03F2872D-2889-439A-8812-7222B677B744
2016-03-16 06:33:04.1,56 ThaliTest[1166:2597192] client session: disconnect
2016-03-16 06:33:04.156 ThaliTest[1166:2597192] client session: stateChange:1->0 03F2872D-2889-439A-8812-7222B677B744:5
2016-03-16 06:33:04.157 ThaliTest[1166:2597192] client session: fireConnectCallb,ack: 03F2872D-2889-439A-8812-7222B677B744
2016-03-16 06:33:04.157 ThaliTest[1166:2597192] jxcore: connect: fail: Peer disconnected
,2016-03-16 06:33:04.171 ThaliTest[1166:2596423] jxcore: connect 03F2872D-2889-439A-8812-7222B677B744:5
2016-03-16 06:33:04.172 ThaliTest[1166:2596423] client session: connect
2016-03-16 06:33:04.172 ThaliTest[1166:2596423] client session: stateChange:0->1 03F2872D-2889-439A-8812-7222B677B744:5
,2016-03-16 06:33:04.287 ThaliTest[1166:2597192] client session: not connected 03F2872D-2889-439A-8812-7222B677B744:5
2016-03-16 06:33:04.287 ThaliTest[1166:2597192] client session: onLinkFailure: 03F2872D-2889-439A-8812-7222B677B744
2016-03-16 06:33:04.2,87 ThaliTest[1166:2597192] client session: disconnect
2016-03-16 06:33:04.287 ThaliTest[1166:2597192] client session: stateChange:1->0 03F2872D-2889-439A-8812-7222B677B744:5
,2016-03-16 06:33:04.289 ThaliTest[1166:2597192] client session: fireConnectCallback: 03F2872D-2889-439A-8812-7222B677B744
2016-03-16 06:33:04.289 ThaliTest[1166:2597192] jxcore: connect: fail: Peer disconnected
,2016-03-16 06:33:07.300 ThaliTest[1166:2596423] jxcore: connect 03F2872D-2889-439A-8812-7222B677B744:5
2016-03-16 06:33:07.302 ThaliTest[1166:2596423] client session: connect
2016-03-16 06:33:07.302 ThaliTest[1166:2596423] client session: stateChange:0->,1 03F2872D-2889-439A-8812-7222B677B744:5
,2016-03-16 06:33:07.563 ThaliTest[1166:2597179] client session: not connected 03F2872D-2889-439A-8812-7222B677B744:5
2016-03-16 06:33:07.564 ThaliTest[1166:2597179] client session: onLinkFailure: 03F2872D-2889-439A-8812-7222B677B744
2016-03-16 06:33:07.5,65 ThaliTest[1166:2597179] client session: disconnect
2016-03-16 06:33:07.565 ThaliTest[1166:2597179] client session: stateChange:1->0 03F2872D-2889-439A-8812-7222B677B744:5
2016-03-16 06:33:07.565 ThaliTest[1166:2597179] client session: fireConnectCallb,ack: 03F2872D-2889-439A-8812-7222B677B744
2016-03-16 06:33:07.565 ThaliTest[1166:2597179] jxcore: connect: fail: Peer disconnected
,2016-03-16 06:33:10.572 ThaliTest[1166:2596423] jxcore: connect 03F2872D-2889-439A-8812-7222B677B744:5
2016-03-16 06:33:10.573 ThaliTest[1166:2596423] client session: connect
2016-03-16 06:33:10.574 ThaliTest[1166:2596423] client session: stateChange:0->1 03F2872D-2889-439A-8812-7222B677B744:5
,2016-03-16 06:33:10.931 ThaliTest[1166:2597192] client session: not connected 03F2872D-2889-439A-8812-7222B677B744:5
2016-03-16 06:33:10.931 ThaliTest[1166:2597192] client session: onLinkFailure: 03F2872D-2889-439A-8812-7222B677B744
2016-03-16 06:33:10.931 ThaliTest[1166:2597192] client session: disconnect
2016-03-16 06:33:10.931 ThaliTest[1166:2597192] client session: stateChange:1->0 03F2872D-2889-439A-8812-7222B677B744:5
2016-03-16 06:33:10.932 ThaliTest[1166:2597192] client session: fireConnectCallb,ack: 03F2872D-2889-439A-8812-7222B677B744
2016-03-16 06:33:10.932 ThaliTest[1166:2597192] jxcore: connect: fail: Peer disconnected
,2016-03-16 06:33:12.469 ThaliTest[1166:2596243] multipeer session: reset timer
2016-03-16 06:33:12.469 ThaliTest[1166:2596243] server: disconnecting to refresh session (03F2872D-2889-439A-8812-7222B677B744)
2016-03-16 06:33:12.470 ThaliTest[1166:2596243], server: rejecting invitation from 03F2872D-2889-439A-8812-7222B677B744 due to previous generation (7579825C-F152-45B2-BE5B-E01EEC4FE5D6:6 != 7579825C-F152-45B2-BE5B-E01EEC4FE5D6:5)
,2016-03-16 06:33:13.941 ThaliTest[1166:2596423] jxcore: connect 03F2872D-2889-439A-8812-7222B677B744:5
2016-03-16 06:33:13.942 ThaliTest[1166:2596423] client session: connect
2016-03-16 06:33:13.943 ThaliTest[1166:2596423] client session: stateChange:0->1 03F2872D-2889-439A-8812-7222B677B744:5
,2016-03-16 06:33:14.050 ThaliTest[1166:2597179] client session: not connected 03F2872D-2889-439A-8812-7222B677B744:5
2016-03-16 06:33:14.050 ThaliTest[1166:2597179] client session: onLinkFailure: 03F2872D-2889-439A-8812-7222B677B744
2016-03-16 06:33:14.0,50 ThaliTest[1166:2597179] client session: disconnect
2016-03-16 06:33:14.050 ThaliTest[1166:2597179] client session: stateChange:1->0 03F2872D-2889-439A-8812-7222B677B744:5
,2016-03-16 06:33:14.052 ThaliTest[1166:2597179] client session: fireConnectCallback: 03F2872D-2889-439A-8812-7222B677B744
2016-03-16 06:33:14.052 ThaliTest[1166:2597179] jxcore: connect: fail: Peer disconnected
,2016-03-16 06:33:17.059 ThaliTest[1166:2596423] jxcore: connect 03F2872D-2889-439A-8812-7222B677B744:5
2016-03-16 06:33:17.060 ThaliTest[1166:2596423] client session: connect
2016-03-16 06:33:17.060 ThaliTest[1166:2596423] client session: stateChange:0->,1 03F2872D-2889-439A-8812-7222B677B744:5
,2016-03-16 06:33:17.218 ThaliTest[1166:2597400] client session: not connected 03F2872D-2889-439A-8812-7222B677B744:5
2016-03-16 06:33:17.218 ThaliTest[1166:2597400] client session: onLinkFailure: 03F2872D-2889-439A-8812-7222B677B744
2016-03-16 06:33:17.2,18 ThaliTest[1166:2597400] client session: disconnect
2016-03-16 06:33:17.218 ThaliTest[1166:2597400] client session: stateChange:1->0 03F2872D-2889-439A-8812-7222B677B744:5
,2016-03-16 06:33:17.220 ThaliTest[1166:2597400] client session: fireConnectCallback: 03F2872D-2889-439A-8812-7222B677B744
2016-03-16 06:33:17.220 ThaliTest[1166:2597400] jxcore: connect: fail: Peer disconnected
,2016-03-16 06:33:18.798 ThaliTest[1166:2596243] multipeer manager: restart client
,2016-03-16 06:33:20.228 ThaliTest[1166:2596423] jxcore: connect 03F2872D-2889-439A-8812-7222B677B744:5
2016-03-16 06:33:20.228 ThaliTest[1166:2596423] client session: connect
2016-03-16 06:33:20.229 ThaliTest[1166:2596423] client session: stateChange:0->1 03F2872D-2889-439A-8812-7222B677B744:5
,2016-03-16 06:33:20.237 ThaliTest[1166:2596243] client: lost peer: 03F2872D-2889-439A-8812-7222B677B744
2016-03-16 06:33:20.237 ThaliTest[1166:2596243] client session: onPeerLost: 03F2872D-2889-439A-8812-7222B677B744
,2016-03-16 06:33:20.237 ThaliTest[1166:2596243] client session: onLinkFailure: 03F2872D-2889-439A-8812-7222B677B744
2016-03-16 06:33:20.237 ThaliTest[1166:2596243] client session: disconnect
,2016-03-16 06:33:20.238 ThaliTest[1166:2596243] client session: stateChange:1->0 03F2872D-2889-439A-8812-7222B677B744:5
,2016-03-16 06:33:20.239 ThaliTest[1166:2596243] client session: fireConnectCallback: 03F2872D-2889-439A-8812-7222B677B744
2016-03-16 06:33:20.239 ThaliTest[1166:2596243] jxcore: connect: fail: Peer disconnected
,2016-03-16 06:33:23.246 ThaliTest[1166:2596423] jxcore: connect 03F2872D-2889-439A-8812-7222B677B744:5
2016-03-16 06:33:23.246 ThaliTest[1166:2596423] client: connect: unreachable 03F2872D-2889-439A-8812-7222B677B744
2016-03-16 06:33:23.247 ThaliTest[1166:2596423] jxcore: connect: fail: Peer unreachable
,2016-03-16 06:33:26.251 ThaliTest[1166:2596423] jxcore: connect 03F2872D-2889-439A-8812-7222B677B744:5
2016-03-16 06:33:26.252 ThaliTest[1166:2596423] client: connect: unreachable 03F2872D-2889-439A-8812-7222B677B744
2016-03-16 06:33:26.252 ThaliTest[1166:2596423] jxcore: connect: fail: Peer unreachable
,2016-03-16 06:33:29.261 ThaliTest[1166:2596423] jxcore: connect 03F2872D-2889-439A-8812-7222B677B744:5
2016-03-16 06:33:29.261 ThaliTest[1166:2596423] client: connect: unreachable 03F2872D-2889-439A-8812-7222B677B744
2016-03-16 06:33:29.262 ThaliTest[116,6:2596423] jxcore: connect: fail: Peer unreachable
,2016-03-16 06:33:38.798 ThaliTest[1166:2596243] multipeer manager: restart client
,2016-03-16 06:33:39.340 ThaliTest[1166:2596243] multipeer session: reset timer
2016-03-16 06:33:39.340 ThaliTest[1166:2596243] server: disconnecting to refresh session (03F2872D-2889-439A-8812-7222B677B744)
2016-03-16 06:33:39.340 ThaliTest[1166:2596243], server: rejecting invitation from 03F2872D-2889-439A-8812-7222B677B744 due to previous generation (7579825C-F152-45B2-BE5B-E01EEC4FE5D6:6 != 7579825C-F152-45B2-BE5B-E01EEC4FE5D6:5)
,2016-03-16 06:33:41.491 ThaliTest[1166:2596243] multipeer session: reset timer
2016-03-16 06:33:41.492 ThaliTest[1166:2596243] server: disconnecting to refresh session (03F2872D-2889-439A-8812-7222B677B744)
2016-03-16 06:33:41.492 ThaliTest[1166:2596243], server: rejecting invitation from 03F2872D-2889-439A-8812-7222B677B744 due to previous generation (7579825C-F152-45B2-BE5B-E01EEC4FE5D6:6 != 7579825C-F152-45B2-BE5B-E01EEC4FE5D6:5)
,2016-03-16 06:33:51.898 ThaliTest[1166:2596243] multipeer session: reset timer
2016-03-16 06:33:51.898 ThaliTest[1166:2596243] server: disconnecting to refresh session (03F2872D-2889-439A-8812-7222B677B744)
2016-03-16 06:33:51.898 ThaliTest[1166:2596243] server: rejecting invitation from 03F2872D-2889-439A-8812-7222B677B744 due to previous generation (7579825C-F152-45B2-BE5B-E01EEC4FE5D6:6 != 7579825C-F152-45B2-BE5B-E01EEC4FE5D6:5)
,2016-03-16 06:33:58.798 ThaliTest[1166:2596243] multipeer manager: restart client
,2016-03-16 06:33:58.806 ThaliTest[1166:2596243] client: found updated peer: 03F2872D-2889-439A-8812-7222B677B744:6
2016-03-16 06:33:58.808 ThaliTest[1166:2596423] jxcore: connect 03F2872D-2889-439A-8812-7222B677B744:6
2016-03-16 06:33:58.808 ThaliTest[11,66:2596423] client session: connect
2016-03-16 06:33:58.808 ThaliTest[1166:2596423] client session: stateChange:0->1 03F2872D-2889-439A-8812-7222B677B744:6
,2016-03-16 06:33:59.146 ThaliTest[1166:2596243] multipeer session: reset timer
2016-03-16 06:33:59.147 ThaliTest[1166:2596243] server: disconnecting to refresh session (03F2872D-2889-439A-8812-7222B677B744)
2016-03-16 06:33:59.147 ThaliTest[1166:2596243], server: rejecting invitation for lexical ordering 03F2872D-2889-439A-8812-7222B677B744
2016-03-16 06:33:59.148 ThaliTest[1166:2596423] jxcore: connect 03F2872D-2889-439A-8812-7222B677B744:6
2016-03-16 06:33:59.148 ThaliTest[1166:2596423] client: already, connect(ing/ed) to 03F2872D-2889-439A-8812-7222B677B744:6
2016-03-16 06:33:59.149 ThaliTest[1166:2596423] jxcore: connect: fail: Aleady connecting
,2016-03-16 06:34:00.801 ThaliTest[1166:2597527] client session: connected
2016-03-16 06:34:00.801 ThaliTest[1166:2597527] client session: stateChange:1->2 03F2872D-2889-439A-8812-7222B677B744:6
,2016-03-16 06:34:00.938 ThaliTest[1166:2597532] client session: fireConnectCallback: 03F2872D-2889-439A-8812-7222B677B744
2016-03-16 06:34:00.938 ThaliTest[1166:2597532] jxcore: connect: success
{ clientPort: 0, serverPort: 0, listeningPort: 61825 }

Forward connection

,2016-03-16 06:34:00.942 ThaliTest[1166:2596243] client: relay established
2016-03-16 06:34:00.942 ThaliTest[1166:2596243] client: new accepted socket: 0x1ae62d80
,forwardSend

,forwardData

,forwardData

,2016-03-16 06:34:02.158 ThaliTest[1166:2596423] jxcore: connect 03F2872D-2889-439A-8812-7222B677B744:6
2016-03-16 06:34:02.159 ThaliTest[1166:2596423] client: already connect(ing/ed) to 03F2872D-2889-439A-8812-7222B677B744:6
2016-03-16 06:34:02.159 ThaliTest[1166:2596423] jxcore: connect: fail: Aleady connecting
,forwardData

,forwardData

,forwardData

,ok 167 received should match sent forward

,# setup

,forwardData

,forwardData

,forwardData

,forwardData

,forwardData

,forwardData

,forwardData

,forwardData

,forwardData

,forwardData

,forwardData

,2016-03-16 06:34:03.190 ThaliTest[1166:2596423] jxcore: stopListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}

,2016-03-16 06:34:03.191 ThaliTest[1166:2596423] jxcore: stopListeningForAdvertisements: success
,ok 168 Should be able to call stopListeningForAdvertisments in teardown

,2016-03-16 06:34:03.193 ThaliTest[1166:2596423] jxcore: stopAdvertisingAndListening
2016-03-16 06:34:03.194 ThaliTest[1166:2596423] THEMultipeerManager stopping peer
2016-03-16 06:34:03.194 ThaliTest[1166:2596423] client session: disconnect
2016-03-16 0,6:34:03.194 ThaliTest[1166:2596423] client session: stateChange:2->0 03F2872D-2889-439A-8812-7222B677B744:6
,2016-03-16 06:34:03.211 ThaliTest[1166:2596423] multipeer manager: stop client timer
2016-03-16 06:34:03.218 ThaliTest[1166:2596423] jxcore: stopAdvertisingAndListening: success
ok 169 Should be able to call stopAdvertisingAndListening in teardown

# 3,9. can get the network status before starting

,# teardown

,ok 170 network status should have certain non-empty properties

,# setup

,2016-03-16 06:34:05.171 ThaliTest[1166:2596423] jxcore: connect 03F2872D-2889-439A-8812-7222B677B744:6
2016-03-16 06:34:05.171 ThaliTest[1166:2596423] jxcore: connect: fail: Start browsing first
,# 40. #generatePreambleAndBeacons bad args

,# teardown

,ok 171 publicKeysToNotify cannot be null

,ok 172 ecdh for local device cannot be null

,ok 173 milliseconds cannot be less than 0

,ok 174 milliseconds cannot be 0

,ok 175 milliseconds cannot be greater than one_day

,# setup

,# 41. #generatePreambleAndBeacons empty keys to notify

,# teardown

,ok 176 should be equal

,# setup

,# 42. #generatePreambleAndBeacons multiple keys to notify

,# teardown

,ok 177 should be equal

,ok 178 should be equal

,ok 179 (unnamed assert)

,ok 180 should be equal

,# setup

,# 43. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

,2016-03-16 06:34:08.180 ThaliTest[1166:2596423] jxcore: connect 03F2872D-2889-439A-8812-7222B677B744:6
2016-03-16 06:34:08.181 ThaliTest[1166:2596423] jxcore: connect: fail: Start browsing first
,# teardown

,ok 181 should throw

,# setup

,# 44. #parseBeacons invalid expiration in beaconStreamWithPreAmble

,# teardown

,ok 182 Preamble expiration must be a 64 bit integer

,# setup

,# 45. #parseBeacons expiration out of range lower

,2016-03-16 06:34:11.187 ThaliTest[1166:2596423] jxcore: connect 03F2872D-2889-439A-8812-7222B677B744:6
2016-03-16 06:34:11.188 ThaliTest[1166:2596423] jxcore: connect: fail: Start browsing first
,# teardown

,ok 183 Expiration out of range

,# setup

,# 46. #parseBeacons expiration out of range lower

,# teardown

,2016-03-16 06:34:14.200 ThaliTest[1166:2596423] jxcore: connect 03F2872D-2889-439A-8812-7222B677B744:6
2016-03-16 06:34:14.200 ThaliTest[1166:2596423] jxcore: connect: fail: Start browsing first
,2016-03-16 06:34:17.205 ThaliTest[1166:2596423] jxcore: connect 03F2872D-2889-439A-8812-7222B677B744:6
2016-03-16 06:34:17.205 ThaliTest[1166:2596423] jxcore: connect: fail: Start browsing first
,ok 184 Expiration out of range

,# setup

,# 47. #parseBeacons no beacons returns null

,2016-03-16 06:34:20.217 ThaliTest[1166:2596423] jxcore: connect 03F2872D-2889-439A-8812-7222B677B744:6
2016-03-16 06:34:20.217 ThaliTest[1166:2596423] jxcore: connect: fail: Start browsing first
,# teardown

,ok 185 should be equal

,# setup

,2016-03-16 06:34:23.222 ThaliTest[1166:2596423] jxcore: connect 03F2872D-2889-439A-8812-7222B677B744:6
2016-03-16 06:34:23.223 ThaliTest[1166:2596423] jxcore: connect: fail: Start browsing first
,# 48. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

,# teardown

,2016-03-16 06:34:26.233 ThaliTest[1166:2596423] jxcore: connect 03F2872D-2889-439A-8812-7222B677B744:6
2016-03-16 06:34:26.234 ThaliTest[1166:2596423] jxcore: connect: fail: Start browsing first
,ok 186 Malformed encrypted beacon key ID

,# setup

,# 49. #parseBeacons addressBookCallback fails decrypt

,# teardown

,ok 187 should be equal
,
,# setup

,# 50. #parseBeacons addressBookCallback returns no matches

,# teardown

,
ok 188 should be equal

ok 189 should be equal
,# setup

,# 51. #parseBeacons addressBookCallback returns spurious match

,# teardown

,ok 190 should be equal

,ok 191 should be equal

,# setup

,# 52. #parseBeacons addressBookCallback returns public key

,# teardown

,ok 192 should be equal

,ok 193 (unnamed assert)

,# setup

,# 53. #parseBeacons with beacons both for and not for the user

,# teardown

,ok 194 should be equal

,ok 195 (unnamed assert)

,# setup

,# 54. Start and stop ThaliNotificationServer

,# teardown

,ok 196 ThaliMobile.StartUpdateAdvertisingAndListening should be called once

,ok 197 ThaliMobile.StopAdvertisingAndListening should be called once

,# setup

,# 55. Pass an empty array to ThaliNotificationServer.start

,# teardown

,ok 198 StartUpdateAdvertisingAndListening should not be called

,ok 199 ThaliMobile.StopAdvertisingAndListening should be called once

,ok 200 no error

,ok 201 should be 204

,# setup

,# 56. Pass a string to ThaliNotificationServer.start

,# teardown

,ok 202 StartUpdateAdvertisingAndListening should not be called

,# setup

,# 57. Pass an empty parameter to ThaliNotificationServer.start

,# teardown

,ok 203 StartUpdateAdvertisingAndListening should not be called

,# setup

,# 58. Make an HTTP request to /NotificationBeacons

,# teardown

,ok 204 no error

ok 205 should be 200

,ok 206 should be equal

,ok 207 should be equal

,ok 208 (unnamed assert)

,ok 209 no error

,ok 210 should be 204

,# setup

,# 59. Make an HTTP request to /NotificationBeacons (no keys)

,# teardown

,ok 211 error should be null

,ok 212 should be 204

,# setup

,# 60. Make an HTTP request to /NotificationBeacons before calling start

,# teardown

,ok 213 should be 404

,# setup

,# 61. #testThaliPeerAction - test getters

,# teardown

,ok 214 getPeerIdentifier

,ok 215 getConnectionType

,ok 216 getActionType

,ok 217 getActionState

,# setup

,# 62. #testThaliPeerAction - start and kill

,# teardown

,ok 218 initial state

,ok 219 after start

,ok 220 after kill

,# setup

,# 63. #testThaliPeerAction - double start

,# teardown

,ok 221 should be equal

,# setup

,# 64. #testThaliPeerAction - start after kill

,# teardown

,ok 222 clean kill

,ok 223 should be equal

,# setup

,# 65. #testThaliPeerAction - make sure ids are unique

,# teardown

,ok 224 should not be equal

,# setup

,# 66. Test PeerConnectionInformation basics

,# teardown

,ok 225 getHostAddress works

,ok 226 getPortNumber works

,ok 227 getSuggestedTCPTimeout works

,# setup

,# 67. Test PeerDictionary basic functionality

,# teardown

,ok 228 Entry counter must be 1

,ok 229 Size must be 1

,ok 230 Entry counter must be 2

,ok 231 Size must be 2

,ok 232 Entry2 should not be found

,ok 233 Size must be 1

,ok 234 Size must be 0

,ok 235 entry not found must be thrown

,# setup

,# 68. Test PeerDictionary with multiple entries.

,# teardown

,ok 236 Size must be100

,ok 237 Entries between 20 and MAXSIZE + 20 should exist

,ok 238 WAITING state entry should not be removed

,# setup

,# 69. RESOLVED entries are removed before WAITING state entry.

,# teardown

,ok 239 Entries between 6 and MAXSIZE + 4 should exist

,ok 240 Size should be MAXSIZE

,ok 241 Size should be MAXSIZE+6

,# setup

,# 70. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

,# teardown

,ok 242 WAITING state entry should not be removed

,ok 243 Waiting entries between 6 and MAXSIZE + 4 should exist

,ok 244 Size should be MAXSIZE

,ok 245 entryCounter should be MAXSIZE+6

,# setup

,# 71. When CONTROLLED_BY_POOL entry is removed and kill is called.

,# teardown

,ok 246 Kill should be called once

,ok 247 Size should be 100

,# setup

,# 72. #ThaliPeerPoolInterface - bad enqueues

,# teardown

,ok 248 null arg

,ok 249 wrong arg type

,ok 250 wrong state

,# setup

,# 73. #ThaliPeerPoolInterface - do not allow same object type

,# teardown

,ok 251 good enqueue

,ok 252 should be equal

,# setup

,# 74. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

,# teardown

,ok 253 good enqueue

,ok 254 2nd good enqueue

,ok 255 we are in the pool

,ok 256 We are out of the pool

,ok 257 Action was killed

,ok 258 The original kill was called too

,ok 259 second item is still in queue

,# setup

,# 75. compareBufferArrays

,# teardown

,ok 260 should throw

,ok 261 should throw

,ok 262 (unnamed assert)

,ok 263 (unnamed assert)

,ok 264 (unnamed assert)

,ok 265 (unnamed assert)

,ok 266 (unnamed assert)

,# setup

,# 76. Call start twice and get error

,# teardown

,ok 267 should throw

,# setup

,# 77. Start and make sure it runs

,# teardown

,# setup

,# 78. Make sure getTimeWhenRun is right after start

,# teardown

,ok 268 (unnamed assert)

,# setup

,# 79. Make sure getTimeWhenRun is -1 after function is called

,# teardown

,ok 269 should be equal

,# setup

,# 80. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

,# teardown

,ok 270 should be equal

,ok 271 should be equal

,ok 272 should throw

,# setup

,# 81. Test TransientState

,# teardown

,ok 273 should throw

,ok 274 should throw

,ok 275 should be equal
,
,ok 276 should be equal

,ok 277 should be equal

,ok 278 should be equal

,ok 279 (unnamed assert)

,ok 280 (unnamed assert)

,# setup

,# 82. No peers and empty database

,# teardown

,ok 281 verify failed

ok 282 constructor called once

,ok 283 constructor called with right args

,ok 284 match start arg

,ok 285 start called once

,ok 286 stop called once

,ok 287 stop after start

,# setup

,# 83. One peer and empty DB

,# teardown

,ok 288 verify failed

,ok 289 constructor called once

,ok 290 constructor called with right args

,ok 291 match start arg

,ok 292 start called once

,ok 293 stop called once

,ok 294 stop after start

,# setup

,# 84. One peer with _Local set behind current seq

,# teardown

,ok 295 verify failed

ok 296 constructor called once

,ok 297 constructor called with right args

,ok 298 match start arg

,ok 299 start called once

,ok 300 stop called once

,ok 301 stop after start

,# setup

,# 85. One peer with _Local set equal to current seq

,# teardown

,ok 302 verify failed

,ok 303 constructor called once

,ok 304 constructor called with right args

,ok 305 match start arg

,ok 306 start called once

,ok 307 stop called once

,ok 308 stop after start

,# setup

,# 86. One peer with _Local set ahead of current seq (and no this should not happen)

,# teardown

,ok 309 verify failed

,ok 310 constructor called once

,ok 311 constructor called with right args

,ok 312 match start arg

,ok 313 start called once

,ok 314 stop called once

,ok 315 stop after start

,# setup

,# 87. Three peers, one not in DB, one behind and one ahead

,# teardown

,ok 316 verify failed

,ok 317 constructor called once

,ok 318 constructor called with right args

,ok 319 match start arg

,ok 320 start called once

,ok 321 stop called once

,ok 322 stop after start

,# setup

,# 88. More than maximum peers, make sure we only send maximum allowed

,# teardown

,ok 323 verify failed

,ok 324 constructor called once

,ok 325 constructor called with right args

,ok 326 match start arg

,ok 327 start called once

,ok 328 stop called once

,ok 329 stop after start

,# setup

,# 89. two peers with empty DB, update the doc

,# teardown

,ok 330 verify failed

,ok 331 constructor called once

,ok 332 constructor called with right args

,ok 333 last start before stop

,ok 334 empty first start

,ok 335 full second start

,ok 336 only 2 timers

,# setup

,# 90. add doc and make sure tokens refresh when they expire

,# teardown

,ok 337 verify failed

,ok 338 constructor called once

,ok 339 constructor called with right args

,ok 340 start before stop

,ok 341 We got at least 3 calls to start

,ok 342 at least 3

,ok 343 default 1

ok 344 1 run

,ok 345 default 2

,ok 346 2 run

,ok 347 default 3

,# setup

,# 91. start and stop and start and stop

,# teardown

,ok 348 start out null

,ok 349 back to null

,ok 350 still null

,ok 351 verify failed

,ok 352 constructor called once

,ok 353 constructor called with right args

,ok 354 first start before first stop

,ok 355 first stop before second start

,ok 356 second start before second stop

,# setup

,# 92. two identical starts in a row

,# teardown

,ok 357 verify failed

,ok 358 constructor called once

,ok 359 constructor called with right args

,ok 360 (unnamed assert)

,# setup

,# 93. two different starts in a row

,# teardown

,ok 361 verify failed

ok 362 constructor called once

,ok 363 constructor called with right args

,ok 364 (unnamed assert)

,ok 365 (unnamed assert)

,# setup

,# 94. two stops and a start and two stops

,# teardown

,ok 366 verify failed

,ok 367 constructor called once

,ok 368 constructor called with right args

,ok 369 start before stop

,# setup

,# 95. we properly enqueue requests so no then needed

,# teardown

,ok 370 verify failed

,ok 371 constructor called once

,ok 372 constructor called with right args

,ok 373 start before stop

,# setup

,# 96. test calculateSeqPointKeyId

,# teardown

,ok 374 should be equal

,ok 375 should be equal

,# setup

,# 97. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

,ok 376 should be in started state

,# teardown

,ok 377 peer identifier should match

,ok 378 host address should match

,ok 379 port should match

,ok 380 host address should be null

,ok 381 port should should be null

,# setup

,ok 382 should not be in started state

,# 98. #startUpdateAdvertisingAndListening should use different USN after every invocation

,ok 383 should be in started state

,# teardown

,ok 384 USN should have changed from the first one

,ok 385 when receiving the second byebye, the first USN should be already set

,# setup

,ok 386 should not be in started state

,# 99. messages with invalid location or USN should be ignored

,ok 387 should be in started state

,# teardown

,WARN thaliWifiInfrastructure Failed to parse a valid port number from location: http://foo.bar:90000

,ok 388 should not have emitted with invalid port

,WARN thaliWifiInfrastructure Received an invalid USN value: 

,ok 389 should not have emitted with invalid USN

,# setup

,ok 390 should not be in started state

,# 100. verify that Thali-specific messages are filtered correctly

,ok 391 should be in started state

,# teardown

,ok 392 irrelevant messages should be ignored

,ok 393 relevant messages should not be ignored

,ok 394 messages from this device should be ignored

,# setup

,ok 395 should not be in started state

,# 101. #startListeningForAdvertisements should fail if start not called

,ok 396 should be in started state

,# teardown

,ok 397 specific error should be returned

,# setup

,ok 398 should not be in started state

,# 102. #startUpdateAdvertisingAndListening should fail if start not called

,ok 399 should be in started state

,# teardown

,ok 400 specific error should be returned

,# setup

,ok 401 should not be in started state

,# 103. #start should fail if called twice in a row

,ok 402 should be in started state

,# teardown

,ok 403 specific error should be received

,# setup

,ok 404 should not be in started state

,# 104. should not be started after stop is called

,ok 405 should be in started state

,# teardown

,ok 406 should not be started

,ok 407 should not be listening

,ok 408 should not target listening

,ok 409 should not be advertising

,ok 410 should not target advertising

,# setup

,ok 411 should not be in started state

,# 105. #startUpdateAdvertisingAndListening should fail invalid router has been passed

,ok 412 should be in started state

,# teardown

,ERROR thaliWifiInfrastructure Unable to use the given router: TypeError: Router.use() requires middleware function but got a string

,ok 413 specific error should be received

,# setup

,ok 414 should not be in started state

,# 106. #startUpdateAdvertisingAndListening should fail if router server starting fails

,ok 415 should be in started state

,# teardown

,ERROR thaliWifiInfrastructure Router server emitted an error: Error: listen EADDRINUSE

,ok 416 specific error expected

,# setup

,ok 417 should not be in started state

,# 107. #startUpdateAdvertisingAndListening should start hosting given router object

,ok 418 should be in started state

,# teardown

,ok 419 server should respond with code 200

,# setup

,ok 420 should not be in started state

,# 108. #stop can be called multiple times in a row

,ok 421 should be in started state

,# teardown

,ok 422 should be in stopped state

,ok 423 should still be in stopped state

,# setup

,ok 424 should not be in started state

,# 109. #startListeningForAdvertisements can be called multiple times in a row

,ok 425 should be in started state

,# teardown

,ok 426 should be in listening state

,ok 427 should still be in listening state

,# setup

,ok 428 should not be in started state

,# 110. #stopListeningForAdvertisements can be called multiple times in a row

,ok 429 should be in started state

,# teardown

,ok 430 should not be in listening state

,ok 431 should still not be in listening state
,
,# setup

,ok 432 should not be in started state

,# 111. #stopAdvertisingAndListening can be called multiple times in a row

,ok 433 should be in started state

,# teardown

,ok 434 should not be in advertising state

,ok 435 should still not be in advertising state

,# setup
,
,ok 436 should not be in started state

,# 112. functions are run from a queue in the right order

,ok 437 should be in started state

,# teardown

,ok 438 call order must match

,# setup

,ok 439 should not be in started state

,# 113. #ThaliPeerPoolDefault - single action

,# teardown

,ok 440 is an agent

,ok 441 enqueue is fine

,ok 442 Everything should be off the queue

,# setup

,# 114. #ThaliPeerPoolDefault - multiple actions

,# teardown

,ok 443 is an agent

,ok 444 first enqueue is fine

,ok 445 is an agent

,ok 446 second enqueue is fine

,ok 447 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.

,ok 448 Queue is empty

,Tests Complete

,Total: 0	Passed: 0	Failed: 0

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
