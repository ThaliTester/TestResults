#### Test 62509094058a2d4_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/62509094058a2d4/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/9FE3D78B-3D3E-43DA-B2D1-6434CC16A100/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/9FE3D78B-3D3E-43DA-B2D1-6434CC16A100/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/62509094058a2d4/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/62509094058a2d4/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/294E1806-40E0-48C7-BA1E-930C2E3F0530/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49590"
,(lldb)     command script import "/tmp/9FE3D78B-3D3E-43DA-B2D1-6434CC16A100/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-15 13:15:44.597 ThaliTest[1488:2351496] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/6212967C-BE38-4575-95D0-6E53EC3BA365/Library/Cookies/Cookies.binarycookies
,2016-03-15 13:15:44.923 ThaliTest[1488:2351496] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-15 13:15:44.924 ThaliTest[1488:2351496] Multi-tasking -> Device: YES, App: YES
,2016-03-15 13:15:44.939 ThaliTest[1488:2351496] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-15 13:15:46.660 ThaliTest[1488:2351496] Using UIWebView
,2016-03-15 13:15:46.670 ThaliTest[1488:2351496] [CDVTimer][handleopenurl] 0.524998ms
,2016-03-15 13:15:46.677 ThaliTest[1488:2351496] [CDVTimer][intentandnavigationfilter] 6.992996ms
,2016-03-15 13:15:46.678 ThaliTest[1488:2351496] [CDVTimer][gesturehandler] 0.334024ms
,2016-03-15 13:15:46.679 ThaliTest[1488:2351496] [CDVTimer][TotalPluginStartup] 9.736001ms
,2016-03-15 13:15:53.913 ThaliTest[1488:2351496] Resetting plugins due to page load.
,2016-03-15 13:15:57.399 ThaliTest[1488:2351496] Finished load of: file:///var/mobile/Containers/Bundle/Application/294E1806-40E0-48C7-BA1E-930C2E3F0530/ThaliTest.app/www/index.html
,2016-03-15 13:15:57.602 ThaliTest[1488:2351496] JXcore Cordova plugin initializing
,2016-03-15 13:15:57.603 ThaliTest[1488:2351749] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,2016-03-15 13:16:00.955 ThaliTest[1488:2351749] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-15 13:16:00.955 ThaliTest[1488:2351749] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-15 13:16:00.956 ThaliTest[1488:2351749] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

,2016-03-15 13:16:00.958 ThaliTest[1488:2351749] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/294E1806-40E0-48C7-BA1E-930C2E3F0530/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/294E1806-40E0-48C7-BA1E-930C2E3F0530/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/294E1806-40E0-48C7-BA1E-930C2E3F0530/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/294E1806-40E0-48C7-BA1E-930C2E3F0530/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/294E1806-40E0-48C7-BA1E-930C2E3F0530/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/294E1806-40E0-48C7-BA1E-930C2E3F0530/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/294E1806-40E0-48C7-BA1E-930C2E3F0530/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/294E1806-40E0-48C7-BA1E-930C2E3F0530/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/294E1806-40E0-48C7-BA1E-930C2E3F0530/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/294E1806-40E0-48C7-BA1E-930C2E3F0530/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/294E1806-40E0-48C7-BA1E-930C2E3F0530/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/294E1806-40E0-48C7-BA1E-930C2E3F0530/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/294E1806-40E0-48C7-BA1E-930C2E3F0530/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/294E1806-40E0-48C7-BA1E-930C2E3F0530/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/294E1806-40E0-48C7-BA1E-930C2E3F0530/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/294E1806-40E0-48C7-BA1E-930C2E3F0530/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/294E1806-40E0-48C7-BA1E-930C2E3F0530/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/294E1806-40E0-48C7-BA1E-930C2E3F0530/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,2016-03-15 13:16:08.112 ThaliTest[1488:2351496] THREAD WARNING: ['JXcore'] took '5483.875244' ms. Plugin should use a background thread.
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

,2016-03-15 13:19:24.913 ThaliTest[1488:2351749] jxcore: startListeningForAdvertisements
,2016-03-15 13:19:24.914 ThaliTest[1488:2351749] multipeer manager: start client restart timer: 0x17ebddf0
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}

2016-03-15 13:19:24.918 ThaliTest[1488:2351749] jxcore: startListeningForAdvertisements: success
ok 127 Can call startListeningForAdvertisements without error

,2016-03-15 13:19:24.921 ThaliTest[1488:2351749] jxcore: stopListeningForAdvertisements
,2016-03-15 13:19:24.922 ThaliTest[1488:2351749] multipeer manager: stop client timer
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}

,2016-03-15 13:19:24.925 ThaliTest[1488:2351749] jxcore: stopListeningForAdvertisements: success
,ok 128 Can call stopListeningForAdvertisements without error

,# setup

,2016-03-15 13:19:25.003 ThaliTest[1488:2351749] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}

,2016-03-15 13:19:25.005 ThaliTest[1488:2351749] jxcore: stopListeningForAdvertisements: success
,ok 129 Should be able to call stopListeningForAdvertisments in teardown

,2016-03-15 13:19:25.008 ThaliTest[1488:2351749] jxcore: stopAdvertisingAndListening
,2016-03-15 13:19:25.009 ThaliTest[1488:2351749] THEMultipeerManager stopping peer
,2016-03-15 13:19:25.010 ThaliTest[1488:2351749] jxcore: stopAdvertisingAndListening: success
,ok 130 Should be able to call stopAdvertisingAndListening in teardown

,# 33. Calling startListeningForAdvertisements twice is NOT an error

,# teardown

,2016-03-15 13:19:25.690 ThaliTest[1488:2351749] jxcore: startListeningForAdvertisements
,2016-03-15 13:19:25.691 ThaliTest[1488:2351749] multipeer manager: start client restart timer: 0x17ebddf0
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}

,2016-03-15 13:19:25.693 ThaliTest[1488:2351749] jxcore: startListeningForAdvertisements: success
,ok 131 Can call startListeningForAdvertisements without error

,2016-03-15 13:19:25.697 ThaliTest[1488:2351749] jxcore: startListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}

,2016-03-15 13:19:25.699 ThaliTest[1488:2351749] jxcore: startListeningForAdvertisements: success
,ok 132 Can call startListeningForAdvertisements twice without error

,# setup

,2016-03-15 13:19:25.803 ThaliTest[1488:2351749] jxcore: stopListeningForAdvertisements
,2016-03-15 13:19:25.803 ThaliTest[1488:2351749] multipeer manager: stop client timer
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}

,2016-03-15 13:19:25.805 ThaliTest[1488:2351749] jxcore: stopListeningForAdvertisements: success
,ok 133 Should be able to call stopListeningForAdvertisments in teardown

,2016-03-15 13:19:25.810 ThaliTest[1488:2351749] jxcore: stopAdvertisingAndListening
,2016-03-15 13:19:25.811 ThaliTest[1488:2351749] THEMultipeerManager stopping peer
,2016-03-15 13:19:25.811 ThaliTest[1488:2351749] jxcore: stopAdvertisingAndListening: success
,ok 134 Should be able to call stopAdvertisingAndListening in teardown

,# 34. Can call start/stopUpdateAdvertisingAndListening

,# teardown

,2016-03-15 13:19:26.794 ThaliTest[1488:2351749] jxcore: startUpdateAdvertisingAndListening
,2016-03-15 13:19:26.795 ThaliTest[1488:2351749] server: starting 92BE0BB8-A3CB-455A-82BE-F170E648CB17:1
,2016-03-15 13:19:26.796 ThaliTest[1488:2351749] multipeer manager: start client restart timer: 0x17ebddf0
2016-03-15 13:19:26.797 ThaliTest[1488:2351749] THEMultipeerManager initialized peer 92BE0BB8-A3CB-455A-82BE-F170E648CB17:1
,2016-03-15 13:19:26.798 ThaliTest[1488:2351749] jxcore: startUpdateAdvertisingAndListening: success
,ok 135 Can call startUpdateAdvertisingAndListening without error

2016-03-15 13:19:26.801 ThaliTest[1488:2351749] jxcore: stopAdvertisingAndListening
2016-03-15 13:19:26.801 ThaliTest[1488:2351749] THEMultipeerManager stopping peer
2016-03-15 13:19:26.802 ThaliTest[1488:2351749] multipeer manager: stop client timer
,2016-03-15 13:19:26.802 ThaliTest[1488:2351749] jxcore: stopAdvertisingAndListening: success
,ok 136 Can call stopAdvertisingAndListening without error

,# setup

,2016-03-15 13:19:26.881 ThaliTest[1488:2351749] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}

,2016-03-15 13:19:26.884 ThaliTest[1488:2351749] jxcore: stopListeningForAdvertisements: success
,ok 137 Should be able to call stopListeningForAdvertisments in teardown

,2016-03-15 13:19:26.887 ThaliTest[1488:2351749] jxcore: stopAdvertisingAndListening
,2016-03-15 13:19:26.887 ThaliTest[1488:2351749] THEMultipeerManager stopping peer
,2016-03-15 13:19:26.888 ThaliTest[1488:2351749] jxcore: stopAdvertisingAndListening: success
,ok 138 Should be able to call stopAdvertisingAndListening in teardown

,# 35. Calling startUpdateAdvertisingAndListening twice is NOT an error

,# teardown

,2016-03-15 13:19:27.782 ThaliTest[1488:2351749] jxcore: startUpdateAdvertisingAndListening
,2016-03-15 13:19:27.783 ThaliTest[1488:2351749] server: starting 92BE0BB8-A3CB-455A-82BE-F170E648CB17:2
,2016-03-15 13:19:27.785 ThaliTest[1488:2351749] multipeer manager: start client restart timer: 0x17ebddf0
2016-03-15 13:19:27.785 ThaliTest[1488:2351749] THEMultipeerManager initialized peer 92BE0BB8-A3CB-455A-82BE-F170E648CB17:2
2016-03-15 13:19:27.785 ThaliTest[1488:2351749] jxcore: startUpdateAdvertisingAndListening: success
,ok 139 Can call startUpdateAdvertisingAndListening without error

,2016-03-15 13:19:27.788 ThaliTest[1488:2351749] jxcore: startUpdateAdvertisingAndListening
2016-03-15 13:19:27.789 ThaliTest[1488:2351749] THEMultipeerManager stopping peer
2016-03-15 13:19:27.789 ThaliTest[1488:2351749] multipeer manager: stop client ti,mer
2016-03-15 13:19:27.789 ThaliTest[1488:2351749] server: starting 92BE0BB8-A3CB-455A-82BE-F170E648CB17:3
2016-03-15 13:19:27.790 ThaliTest[1488:2351749] multipeer manager: start client restart timer: 0x17ebddf0
2016-03-15 13:19:27.790 ThaliTest[1488:,2351749] THEMultipeerManager initialized peer 92BE0BB8-A3CB-455A-82BE-F170E648CB17:3
2016-03-15 13:19:27.791 ThaliTest[1488:2351749] jxcore: startUpdateAdvertisingAndListening: success
ok 140 Can call startUpdateAdvertisingAndListening twice without error

,# setup

,2016-03-15 13:19:27.976 ThaliTest[1488:2351749] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}

,2016-03-15 13:19:27.978 ThaliTest[1488:2351749] jxcore: stopListeningForAdvertisements: success
,ok 141 Should be able to call stopListeningForAdvertisments in teardown

,2016-03-15 13:19:27.981 ThaliTest[1488:2351749] jxcore: stopAdvertisingAndListening
,2016-03-15 13:19:27.981 ThaliTest[1488:2351749] THEMultipeerManager stopping peer
,2016-03-15 13:19:27.982 ThaliTest[1488:2351749] multipeer manager: stop client timer
2016-03-15 13:19:27.983 ThaliTest[1488:2351749] jxcore: stopAdvertisingAndListening: success
,ok 142 Should be able to call stopAdvertisingAndListening in teardown

,# 36. peerAvailabilityChange is called

,# teardown

,2016-03-15 13:19:28.336 ThaliTest[1488:2351749] jxcore: startUpdateAdvertisingAndListening
2016-03-15 13:19:28.337 ThaliTest[1488:2351749] server: starting 92BE0BB8-A3CB-455A-82BE-F170E648CB17:4
,2016-03-15 13:19:28.338 ThaliTest[1488:2351749] multipeer manager: start client restart timer: 0x17ebddf0
2016-03-15 13:19:28.339 ThaliTest[1488:2351749] THEMultipeerManager initialized peer 92BE0BB8-A3CB-455A-82BE-F170E648CB17:4
2016-03-15 13:19:28.340 ThaliTest[1488:2351749] jxcore: startUpdateAdvertisingAndListening: success
,ok 143 Can call startUpdateAdvertisingAndListeningwithout error

,2016-03-15 13:19:28.344 ThaliTest[1488:2351749] jxcore: startListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}

,2016-03-15 13:19:28.349 ThaliTest[1488:2351749] jxcore: startListeningForAdvertisements: success
,ok 144 Can call startListeningForAdvertisements without error

,2016-03-15 13:19:29.151 ThaliTest[1488:2351496] client: found new peer: A23A2191-9ACE-4296-8393-82BF95886094:8
,ok 145 peers must be an array

,ok 146 peers must not be zero-length

,ok 147 peer must have peerIdentifier

2016-03-15 13:19:29.157 ThaliTest[1488:2351496] client: found new peer: B7D25A96-D37D-4E73-B512-E3AADCC34F73:4
ok 148 peerIdentifier must be a string

,ok 149 peer must have peerAvailable

ok 150 peer must have pleaseConnect

,# setup

,2016-03-15 13:19:29.958 ThaliTest[1488:2351749] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}

,2016-03-15 13:19:29.960 ThaliTest[1488:2351749] jxcore: stopListeningForAdvertisements: success
,ok 151 Should be able to call stopListeningForAdvertisments in teardown

,2016-03-15 13:19:29.963 ThaliTest[1488:2351749] jxcore: stopAdvertisingAndListening
,2016-03-15 13:19:29.963 ThaliTest[1488:2351749] THEMultipeerManager stopping peer
,2016-03-15 13:19:29.964 ThaliTest[1488:2351749] multipeer manager: stop client timer
2016-03-15 13:19:29.965 ThaliTest[1488:2351749] jxcore: stopAdvertisingAndListening: success
,ok 152 Should be able to call stopAdvertisingAndListening in teardown

,# 37. Can connect to a remote peer

,# teardown

,2016-03-15 13:19:56.250 ThaliTest[1488:2351749] jxcore: startUpdateAdvertisingAndListening
,2016-03-15 13:19:56.251 ThaliTest[1488:2351749] server: starting 92BE0BB8-A3CB-455A-82BE-F170E648CB17:5
,2016-03-15 13:19:56.253 ThaliTest[1488:2351749] multipeer manager: start client restart timer: 0x17ebddf0
2016-03-15 13:19:56.253 ThaliTest[1488:2351749] THEMultipeerManager initialized peer 92BE0BB8-A3CB-455A-82BE-F170E648CB17:5
2016-03-15 13:19:56.253 ThaliTest[1488:2351749] jxcore: startUpdateAdvertisingAndListening: success
,ok 153 Can call startUpdateAdvertisingAndListening without error

2016-03-15 13:19:56.255 ThaliTest[1488:2351749] jxcore: startListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}

2016-03-15 13:19:56.258 ThaliTest[1488:2351749] jxcore: startListeningForAdvertisements: success
ok 154 Can call startListeningForAdvertisements without error

,2016-03-15 13:19:58.314 ThaliTest[1488:2351496] client: found new peer: B7D25A96-D37D-4E73-B512-E3AADCC34F73:5
,2016-03-15 13:19:58.316 ThaliTest[1488:2351749] jxcore: connect B7D25A96-D37D-4E73-B512-E3AADCC34F73:5
2016-03-15 13:19:58.317 ThaliTest[1488:2351749] client: server will connect
,2016-03-15 13:19:58.318 ThaliTest[1488:2351749] client session: reverseConnect
2016-03-15 13:19:58.318 ThaliTest[1488:2351749] client session: stateChange:0->1 B7D25A96-D37D-4E73-B512-E3AADCC34F73:5
,2016-03-15 13:19:59.097 ThaliTest[1488:2351496] multipeer session: reset timer
,2016-03-15 13:19:59.098 ThaliTest[1488:2352166] client session: not connected B7D25A96-D37D-4E73-B512-E3AADCC34F73:5
2016-03-15 13:19:59.099 ThaliTest[1488:2352166] client session: onLinkFailure: B7D25A96-D37D-4E73-B512-E3AADCC34F73
,2016-03-15 13:19:59.099 ThaliTest[1488:2352166] client session: disconnect
,2016-03-15 13:19:59.098 ThaliTest[1488:2351496] server session: connect
2016-03-15 13:19:59.100 ThaliTest[1488:2352166] client session: stateChange:1->0 B7D25A96-D37D-4E73-B512-E3AADCC34F73:5
,2016-03-15 13:19:59.100 ThaliTest[1488:2351496] server session: stateChange:0->1 B7D25A96-D37D-4E73-B512-E3AADCC34F73:5
,2016-03-15 13:19:59.102 ThaliTest[1488:2352166] client session: no connect callback (server initiated)
,2016-03-15 13:19:59.108 ThaliTest[1488:2351496] server: accepting invitation B7D25A96-D37D-4E73-B512-E3AADCC34F73
,2016-03-15 13:20:00.473 ThaliTest[1488:2352166] server session: connected
2016-03-15 13:20:00.474 ThaliTest[1488:2352166] server session: stateChange:1->2 B7D25A96-D37D-4E73-B512-E3AADCC34F73:5
,2016-03-15 13:20:00.514 ThaliTest[1488:2351496] server relay: connected (to port: 61910)
,2016-03-15 13:20:00.516 ThaliTest[1488:2351496] jxcore: connect: success
,{ clientPort: 61913, serverPort: 61910, listeningPort: 0 }

,ok 155 Must have listeningPort

,ok 156 listeningPort must be a number

,ok 157 Connection must have clientPort

,ok 158 clientPort must be a number

,ok 159 Connection must have serverPort

,ok 160 serverPort must be a number

,ok 161 (unnamed assert)

,ok 162 (unnamed assert)

,# setup

,2016-03-15 13:20:01.033 ThaliTest[1488:2351749] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}

,2016-03-15 13:20:01.035 ThaliTest[1488:2351749] jxcore: stopListeningForAdvertisements: success
,ok 163 Should be able to call stopListeningForAdvertisments in teardown

,2016-03-15 13:20:01.038 ThaliTest[1488:2351749] jxcore: stopAdvertisingAndListening
,2016-03-15 13:20:01.038 ThaliTest[1488:2351749] THEMultipeerManager stopping peer
,2016-03-15 13:20:01.039 ThaliTest[1488:2351749] server session: disconnect
,2016-03-15 13:20:01.040 ThaliTest[1488:2351749] server session: stateChange:2->0 B7D25A96-D37D-4E73-B512-E3AADCC34F73:5
,2016-03-15 13:20:01.058 ThaliTest[1488:2351749] multipeer manager: stop client timer
2016-03-15 13:20:01.058 ThaliTest[1488:2351749] jxcore: stopAdvertisingAndListening: success
,ok 164 Should be able to call stopAdvertisingAndListening in teardown

,# 38. Can shift large amounts of data

,# teardown

,2016-03-15 13:20:02.149 ThaliTest[1488:2351749] jxcore: startUpdateAdvertisingAndListening
,2016-03-15 13:20:02.150 ThaliTest[1488:2351749] server: starting 92BE0BB8-A3CB-455A-82BE-F170E648CB17:6
,2016-03-15 13:20:02.151 ThaliTest[1488:2351749] multipeer manager: start client restart timer: 0x17ebddf0
2016-03-15 13:20:02.152 ThaliTest[1488:2351749] THEMultipeerManager initialized peer 92BE0BB8-A3CB-455A-82BE-F170E648CB17:6
,2016-03-15 13:20:02.153 ThaliTest[1488:2351749] jxcore: startUpdateAdvertisingAndListening: success
ok 165 Can call startUpdateAdvertisingAndListening without error

2016-03-15 13:20:02.154 ThaliTest[1488:2351749] jxcore: startListeningForAdvertisements,
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}

2016-03-15 13:20:02.154 ThaliTest[1488:2351749] jxcore: startListeningForAdvertisements: success
,ok 166 Can call startListeningForAdvertisements without error

,2016-03-15 13:20:04.249 ThaliTest[1488:2351496] client: found new peer: B7D25A96-D37D-4E73-B512-E3AADCC34F73:6
,2016-03-15 13:20:04.251 ThaliTest[1488:2351749] jxcore: connect B7D25A96-D37D-4E73-B512-E3AADCC34F73:6
2016-03-15 13:20:04.252 ThaliTest[1488:2351749] client: server will connect
,2016-03-15 13:20:04.252 ThaliTest[1488:2351749] client session: reverseConnect
,2016-03-15 13:20:04.253 ThaliTest[1488:2351749] client session: stateChange:0->1 B7D25A96-D37D-4E73-B512-E3AADCC34F73:6
,2016-03-15 13:20:04.781 ThaliTest[1488:2352193] client session: not connected B7D25A96-D37D-4E73-B512-E3AADCC34F73:6
2016-03-15 13:20:04.781 ThaliTest[1488:2352193] client session: onLinkFailure: B7D25A96-D37D-4E73-B512-E3AADCC34F73
2016-03-15 13:20:04.7,81 ThaliTest[1488:2352193] client session: disconnect
2016-03-15 13:20:04.781 ThaliTest[1488:2352193] client session: stateChange:1->0 B7D25A96-D37D-4E73-B512-E3AADCC34F73:6
,2016-03-15 13:20:04.783 ThaliTest[1488:2352193] client session: no connect callback (server initiated)
,2016-03-15 13:20:04.802 ThaliTest[1488:2351496] multipeer session: reset timer
,2016-03-15 13:20:04.803 ThaliTest[1488:2351496] server: rejecting invitation from B7D25A96-D37D-4E73-B512-E3AADCC34F73 due to previous generation (92BE0BB8-A3CB-455A-82BE-F170E648CB17:6 != 92BE0BB8-A3CB-455A-82BE-F170E648CB17:5)
,2016-03-15 13:20:22.153 ThaliTest[1488:2351496] multipeer manager: restart client
,2016-03-15 13:20:22.167 ThaliTest[1488:2351496] client: found existing peer: B7D25A96-D37D-4E73-B512-E3AADCC34F73:6
,2016-03-15 13:20:42.153 ThaliTest[1488:2351496] multipeer manager: restart client
,2016-03-15 13:20:42.166 ThaliTest[1488:2351496] client: found existing peer: B7D25A96-D37D-4E73-B512-E3AADCC34F73:6
,2016-03-15 13:21:02.153 ThaliTest[1488:2351496] multipeer manager: restart client
,2016-03-15 13:21:02.167 ThaliTest[1488:2351496] client: found existing peer: B7D25A96-D37D-4E73-B512-E3AADCC34F73:6
,2016-03-15 13:21:22.153 ThaliTest[1488:2351496] multipeer manager: restart client
,2016-03-15 13:21:22.167 ThaliTest[1488:2351496] client: found existing peer: B7D25A96-D37D-4E73-B512-E3AADCC34F73:6
,2016-03-15 13:21:42.153 ThaliTest[1488:2351496] multipeer manager: restart client
,2016-03-15 13:21:42.166 ThaliTest[1488:2351496] client: found existing peer: B7D25A96-D37D-4E73-B512-E3AADCC34F73:6
,2016-03-15 13:22:02.153 ThaliTest[1488:2351496] multipeer manager: restart client
,2016-03-15 13:22:02.167 ThaliTest[1488:2351496] client: found existing peer: B7D25A96-D37D-4E73-B512-E3AADCC34F73:6
,2016-03-15 13:22:22.153 ThaliTest[1488:2351496] multipeer manager: restart client
,2016-03-15 13:22:22.167 ThaliTest[1488:2351496] client: found existing peer: B7D25A96-D37D-4E73-B512-E3AADCC34F73:6
,2016-03-15 13:22:42.153 ThaliTest[1488:2351496] multipeer manager: restart client
,2016-03-15 13:22:42.167 ThaliTest[1488:2351496] client: found existing peer: B7D25A96-D37D-4E73-B512-E3AADCC34F73:6
,2016-03-15 13:23:02.153 ThaliTest[1488:2351496] multipeer manager: restart client
,2016-03-15 13:23:02.168 ThaliTest[1488:2351496] client: found existing peer: B7D25A96-D37D-4E73-B512-E3AADCC34F73:6
,2016-03-15 13:23:22.153 ThaliTest[1488:2351496] multipeer manager: restart client
,2016-03-15 13:23:22.166 ThaliTest[1488:2351496] client: found existing peer: B7D25A96-D37D-4E73-B512-E3AADCC34F73:6
,2016-03-15 13:23:42.153 ThaliTest[1488:2351496] multipeer manager: restart client
,2016-03-15 13:23:42.166 ThaliTest[1488:2351496] client: found existing peer: B7D25A96-D37D-4E73-B512-E3AADCC34F73:6
,2016-03-15 13:24:02.153 ThaliTest[1488:2351496] multipeer manager: restart client
,2016-03-15 13:24:02.166 ThaliTest[1488:2351496] client: found existing peer: B7D25A96-D37D-4E73-B512-E3AADCC34F73:6
,2016-03-15 13:24:22.153 ThaliTest[1488:2351496] multipeer manager: restart client
,2016-03-15 13:24:22.169 ThaliTest[1488:2351496] client: found existing peer: B7D25A96-D37D-4E73-B512-E3AADCC34F73:6
,2016-03-15 13:24:42.153 ThaliTest[1488:2351496] multipeer manager: restart client
,2016-03-15 13:24:42.169 ThaliTest[1488:2351496] client: found existing peer: B7D25A96-D37D-4E73-B512-E3AADCC34F73:6
,2016-03-15 13:25:02.153 ThaliTest[1488:2351496] multipeer manager: restart client
,2016-03-15 13:25:02.166 ThaliTest[1488:2351496] client: found existing peer: B7D25A96-D37D-4E73-B512-E3AADCC34F73:6
,2016-03-15 13:25:22.153 ThaliTest[1488:2351496] multipeer manager: restart client
,2016-03-15 13:25:22.167 ThaliTest[1488:2351496] client: found existing peer: B7D25A96-D37D-4E73-B512-E3AADCC34F73:6
,2016-03-15 13:25:42.153 ThaliTest[1488:2351496] multipeer manager: restart client
,2016-03-15 13:25:42.168 ThaliTest[1488:2351496] client: found existing peer: B7D25A96-D37D-4E73-B512-E3AADCC34F73:6
,2016-03-15 13:26:02.153 ThaliTest[1488:2351496] multipeer manager: restart client
,2016-03-15 13:26:02.167 ThaliTest[1488:2351496] client: found existing peer: B7D25A96-D37D-4E73-B512-E3AADCC34F73:6
,2016-03-15 13:26:22.153 ThaliTest[1488:2351496] multipeer manager: restart client
,2016-03-15 13:26:22.167 ThaliTest[1488:2351496] client: found existing peer: B7D25A96-D37D-4E73-B512-E3AADCC34F73:6
,2016-03-15 13:26:42.153 ThaliTest[1488:2351496] multipeer manager: restart client
,2016-03-15 13:26:42.167 ThaliTest[1488:2351496] client: found existing peer: B7D25A96-D37D-4E73-B512-E3AADCC34F73:6
,2016-03-15 13:27:02.153 ThaliTest[1488:2351496] multipeer manager: restart client
,2016-03-15 13:27:02.168 ThaliTest[1488:2351496] client: found existing peer: B7D25A96-D37D-4E73-B512-E3AADCC34F73:6
,2016-03-15 13:27:22.153 ThaliTest[1488:2351496] multipeer manager: restart client
,2016-03-15 13:27:22.168 ThaliTest[1488:2351496] client: found existing peer: B7D25A96-D37D-4E73-B512-E3AADCC34F73:6
,2016-03-15 13:27:42.153 ThaliTest[1488:2351496] multipeer manager: restart client
,2016-03-15 13:27:42.167 ThaliTest[1488:2351496] client: found existing peer: B7D25A96-D37D-4E73-B512-E3AADCC34F73:6
,2016-03-15 13:28:02.153 ThaliTest[1488:2351496] multipeer manager: restart client
,2016-03-15 13:28:02.167 ThaliTest[1488:2351496] client: found existing peer: B7D25A96-D37D-4E73-B512-E3AADCC34F73:6
,2016-03-15 13:28:22.153 ThaliTest[1488:2351496] multipeer manager: restart client
,2016-03-15 13:28:22.167 ThaliTest[1488:2351496] client: found existing peer: B7D25A96-D37D-4E73-B512-E3AADCC34F73:6
,2016-03-15 13:28:42.153 ThaliTest[1488:2351496] multipeer manager: restart client
,2016-03-15 13:28:42.167 ThaliTest[1488:2351496] client: found existing peer: B7D25A96-D37D-4E73-B512-E3AADCC34F73:6
,2016-03-15 13:29:02.153 ThaliTest[1488:2351496] multipeer manager: restart client
,2016-03-15 13:29:02.166 ThaliTest[1488:2351496] client: found existing peer: B7D25A96-D37D-4E73-B512-E3AADCC34F73:6
,2016-03-15 13:29:22.153 ThaliTest[1488:2351496] multipeer manager: restart client
,2016-03-15 13:29:22.165 ThaliTest[1488:2351496] client: found existing peer: B7D25A96-D37D-4E73-B512-E3AADCC34F73:6
,2016-03-15 13:29:42.152 ThaliTest[1488:2351496] multipeer manager: restart client
,2016-03-15 13:29:42.166 ThaliTest[1488:2351496] client: found existing peer: B7D25A96-D37D-4E73-B512-E3AADCC34F73:6
,2016-03-15 13:30:02.153 ThaliTest[1488:2351496] multipeer manager: restart client
,2016-03-15 13:30:02.167 ThaliTest[1488:2351496] client: found existing peer: B7D25A96-D37D-4E73-B512-E3AADCC34F73:6
,2016-03-15 13:30:22.153 ThaliTest[1488:2351496] multipeer manager: restart client
,2016-03-15 13:30:22.166 ThaliTest[1488:2351496] client: found existing peer: B7D25A96-D37D-4E73-B512-E3AADCC34F73:6
,2016-03-15 13:30:42.153 ThaliTest[1488:2351496] multipeer manager: restart client
,2016-03-15 13:30:42.166 ThaliTest[1488:2351496] client: found existing peer: B7D25A96-D37D-4E73-B512-E3AADCC34F73:6
,2016-03-15 13:31:02.153 ThaliTest[1488:2351496] multipeer manager: restart client
,2016-03-15 13:31:02.168 ThaliTest[1488:2351496] client: found existing peer: B7D25A96-D37D-4E73-B512-E3AADCC34F73:6
,2016-03-15 13:31:22.153 ThaliTest[1488:2351496] multipeer manager: restart client
,2016-03-15 13:31:22.167 ThaliTest[1488:2351496] client: found existing peer: B7D25A96-D37D-4E73-B512-E3AADCC34F73:6
,2016-03-15 13:31:42.139 ThaliTest[1488:2351496] multipeer manager: restart client
,2016-03-15 13:31:42.155 ThaliTest[1488:2351496] client: found existing peer: B7D25A96-D37D-4E73-B512-E3AADCC34F73:6
,2016-03-15 13:32:02.139 ThaliTest[1488:2351496] multipeer manager: restart client
,2016-03-15 13:32:02.151 ThaliTest[1488:2351496] client: found existing peer: B7D25A96-D37D-4E73-B512-E3AADCC34F73:6
,2016-03-15 13:32:22.139 ThaliTest[1488:2351496] multipeer manager: restart client
,2016-03-15 13:32:22.153 ThaliTest[1488:2351496] client: found existing peer: B7D25A96-D37D-4E73-B512-E3AADCC34F73:6
,2016-03-15 13:32:42.139 ThaliTest[1488:2351496] multipeer manager: restart client
,2016-03-15 13:32:42.152 ThaliTest[1488:2351496] client: found existing peer: B7D25A96-D37D-4E73-B512-E3AADCC34F73:6
,2016-03-15 13:33:02.139 ThaliTest[1488:2351496] multipeer manager: restart client
,2016-03-15 13:33:02.153 ThaliTest[1488:2351496] client: found existing peer: B7D25A96-D37D-4E73-B512-E3AADCC34F73:6
,2016-03-15 13:33:22.139 ThaliTest[1488:2351496] multipeer manager: restart client
,2016-03-15 13:33:22.154 ThaliTest[1488:2351496] client: found existing peer: B7D25A96-D37D-4E73-B512-E3AADCC34F73:6
,2016-03-15 13:33:42.139 ThaliTest[1488:2351496] multipeer manager: restart client
,2016-03-15 13:33:42.154 ThaliTest[1488:2351496] client: found existing peer: B7D25A96-D37D-4E73-B512-E3AADCC34F73:6
,2016-03-15 13:34:02.139 ThaliTest[1488:2351496] multipeer manager: restart client
,2016-03-15 13:34:02.154 ThaliTest[1488:2351496] client: found existing peer: B7D25A96-D37D-4E73-B512-E3AADCC34F73:6
,2016-03-15 13:34:22.139 ThaliTest[1488:2351496] multipeer manager: restart client
,2016-03-15 13:34:22.153 ThaliTest[1488:2351496] client: found existing peer: B7D25A96-D37D-4E73-B512-E3AADCC34F73:6
,2016-03-15 13:34:42.139 ThaliTest[1488:2351496] multipeer manager: restart client
,2016-03-15 13:34:42.153 ThaliTest[1488:2351496] client: found existing peer: B7D25A96-D37D-4E73-B512-E3AADCC34F73:6
,2016-03-15 13:35:02.139 ThaliTest[1488:2351496] multipeer manager: restart client
,2016-03-15 13:35:02.153 ThaliTest[1488:2351496] client: found existing peer: B7D25A96-D37D-4E73-B512-E3AADCC34F73:6
,2016-03-15 13:35:22.139 ThaliTest[1488:2351496] multipeer manager: restart client
,2016-03-15 13:35:22.153 ThaliTest[1488:2351496] client: found existing peer: B7D25A96-D37D-4E73-B512-E3AADCC34F73:6
,2016-03-15 13:35:42.138 ThaliTest[1488:2351496] multipeer manager: restart client
,2016-03-15 13:35:42.154 ThaliTest[1488:2351496] client: found existing peer: B7D25A96-D37D-4E73-B512-E3AADCC34F73:6
,2016-03-15 13:36:02.138 ThaliTest[1488:2351496] multipeer manager: restart client
,2016-03-15 13:36:02.153 ThaliTest[1488:2351496] client: found existing peer: B7D25A96-D37D-4E73-B512-E3AADCC34F73:6
,2016-03-15 13:36:22.139 ThaliTest[1488:2351496] multipeer manager: restart client
,2016-03-15 13:36:22.152 ThaliTest[1488:2351496] client: found existing peer: B7D25A96-D37D-4E73-B512-E3AADCC34F73:6
,2016-03-15 13:36:42.139 ThaliTest[1488:2351496] multipeer manager: restart client
,2016-03-15 13:36:42.152 ThaliTest[1488:2351496] client: found existing peer: B7D25A96-D37D-4E73-B512-E3AADCC34F73:6

```
