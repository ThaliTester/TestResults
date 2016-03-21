#### Test 635253937ae73fc_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/635253937ae73fc/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/1A1F197E-E733-434B-9CE0-2559C7A8A156/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/1A1F197E-E733-434B-9CE0-2559C7A8A156/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/635253937ae73fc/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/635253937ae73fc/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B617925D-D62D-4D7C-A75D-BEFB46C32905/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53633"
,(lldb)     command script import "/tmp/1A1F197E-E733-434B-9CE0-2559C7A8A156/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-21 08:35:33.058 ThaliTest[1926:3222287] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/817DDAEE-B80E-433D-973E-FEF8A8943BA5/Library/Cookies/Cookies.binarycookies
,2016-03-21 08:35:33.376 ThaliTest[1926:3222287] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-21 08:35:33.377 ThaliTest[1926:3222287] Multi-tasking -> Device: YES, App: YES
,2016-03-21 08:35:33.393 ThaliTest[1926:3222287] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-21 08:35:35.258 ThaliTest[1926:3222287] Using UIWebView
,2016-03-21 08:35:35.265 ThaliTest[1926:3222287] [CDVTimer][handleopenurl] 0.397980ms
,2016-03-21 08:35:35.272 ThaliTest[1926:3222287] [CDVTimer][intentandnavigationfilter] 6.668985ms
,2016-03-21 08:35:35.273 ThaliTest[1926:3222287] [CDVTimer][gesturehandler] 0.304997ms
,2016-03-21 08:35:35.273 ThaliTest[1926:3222287] [CDVTimer][TotalPluginStartup] 8.997977ms
,2016-03-21 08:35:42.187 ThaliTest[1926:3222287] Resetting plugins due to page load.
,2016-03-21 08:35:45.857 ThaliTest[1926:3222287] Finished load of: file:///var/mobile/Containers/Bundle/Application/B617925D-D62D-4D7C-A75D-BEFB46C32905/ThaliTest.app/www/index.html
,2016-03-21 08:35:46.063 ThaliTest[1926:3222287] JXcore Cordova plugin initializing
,2016-03-21 08:35:46.064 ThaliTest[1926:3222507] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-21 08:35:49.934 ThaliTest[1926:3222507] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-21 08:35:49.934 ThaliTest[1926:3222507] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-21 08:35:49.934 ThaliTest[1926:3222507] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-21 08:35:49.936 ThaliTest[1926:3222507] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-IpadAir2-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B617925D-D62D-4D7C-A75D-BEFB46C32905/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B617925D-D62D-4D7C-A75D-BEFB46C32905/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B617925D-D62D-4D7C-A75D-BEFB46C32905/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B617925D-D62D-4D7C-A75D-BEFB46C32905/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B617925D-D62D-4D7C-A75D-BEFB46C32905/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B617925D-D62D-4D7C-A75D-BEFB46C32905/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B617925D-D62D-4D7C-A75D-BEFB46C32905/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B617925D-D62D-4D7C-A75D-BEFB46C32905/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B617925D-D62D-4D7C-A75D-BEFB46C32905/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B617925D-D62D-4D7C-A75D-BEFB46C32905/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B617925D-D62D-4D7C-A75D-BEFB46C32905/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B617925D-D62D-4D7C-A75D-BEFB46C32905/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B617925D-D62D-4D7C-A75D-BEFB46C32905/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B617925D-D62D-4D7C-A75D-BEFB46C32905/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B617925D-D62D-4D7C-A75D-BEFB46C32905/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B617925D-D62D-4D7C-A75D-BEFB46C32905/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B617925D-D62D-4D7C-A75D-BEFB46C32905/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B617925D-D62D-4D7C-A75D-BEFB46C32905/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B617925D-D62D-4D7C-A75D-BEFB46C32905/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B617925D-D62D-4D7C-A75D-BEFB46C32905/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-21 08:35:57.706 ThaliTest[1926:3222287] THREAD WARNING: ['JXcore'] took '5559.608887' ms. Plugin should use a background thread.
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
,ok 4 tried to connect to right port
,ok 5 failed due to refused connection
,ok 6 routerPortConnectionFailed is emitted
,# setup
,# 4. native server connections all up
,# teardown
,ok 7 Send/recvd #1 should be equal length
,ok 8 Send/recvd #1 should be same
,ok 9 Send/recvd #2 should be equal length
,ok 10 Send/recvd #2 should be same
,ok 11 Should be exactly 2 client sockets
,# setup
,# 5. native server - closing incoming stream cleans outgoing socket
,# teardown
,ok 12 socket shouldn't close until after stream
,ok 13 incoming remains open
,# setup
,# 6. native server - closing incoming connection cleans outgoing socket
,# teardown
,ok 14 we should not have gotten an error
,ok 15 socket shouldn't close until after incoming
,ok 16 incoming is cleaned up
,# setup
,# 7. native server - closing outgoing socket cleans associated mux stream
,# teardown
,ok 17 stream was closed
,ok 18 incoming should survive
,ok 19 mux should have no streams
,# setup
,# 8. native server - closing the whole server cleans everything up
,# teardown
,ok 20 we should not have gotten an error
,ok 21 Buffers are identical
,ok 22 native server is nulled out
,ok 23 native server should be closed
,ok 24 incoming has been removed
,ok 25 Incoming should be done
,ok 26 The mux object should be closed
,ok 27 The mux stream should be closed
,# setup
,# 9. native server - we can get a ton of connections and data through and still clean up the server completely
,# teardown
,ok 28 native server is nulled out
,ok 29 native server should be closed
,ok 30 incoming has been removed
,# setup
,# 10. native server - simulate mux failure, make sure everything is cleaned up
,# teardown
,ok 31 we should not have gotten an error
,ok 32 Buffers are identical
,ok 33 server should be fine
,ok 34 server should be open
,ok 35 incoming has been removed
,ok 36 The mux object should be closed
,ok 37 The mux stream should be closed
,# setup
,# 11. native server - timing out the incoming connection cleans everything up
,# teardown
,ok 38 we should not have gotten an error
,ok 39 Buffers are identical
,ok 40 server should be fine
,ok 41 server should be open
,ok 42 incoming has been removed
,ok 43 The mux object should be closed
,ok 44 The mux stream should be closed
,# setup
,# 12. closeAll can close even when connections open
,# teardown
,ok 45 not possible to connect to the server anymore
,# setup
,# 13. closeAll with promise
,# teardown
,ok 46 not possible to connect to the server anymore
,# setup
,# 14. multiplex can send data
,# teardown
,ok 47 String should be length:200
,# setup
,# 15. enqueue and run in order
,# teardown
,ok 48 firstPromise setTimeout
,ok 49 firstPromise result
,ok 50 firstPromise testValue
,ok 51 secondPromise setTimeout
,ok 52 secondPromise result
,ok 53 secondPromise testValue
,ok 54 thirdPromise in promise
,ok 55 thirdPromise result
,ok 56 thirdPromise testValue
,# setup
,# 16. enqueueAtTop and run backwards
,# teardown
,ok 57 thirdPromise - first to run
,ok 58 thirdPromise - in resolve
,ok 59 secondPromise - second to run
,ok 60 secondPromise - in catch
,ok 61 firstPromise - third to run
,ok 62 firstPromise - in then
,ok 63 testing promises
,# setup
,# 17. mix enqueue and enqueueAtTop
,# teardown
,ok 64 fourth
,ok 65 fourth
,ok 66 second
,ok 67 secondPromise - in then
,ok 68 first
,ok 69 firstPromise - in catch
,ok 70 third
,ok 71 thirdPromise - in then
,ok 72 testingPromises
,# setup
,# 18. queues handled independently
,# teardown
,ok 73 all short operations completed before the long resolves
,# setup
,# 19. basic
,# teardown
,ok 74 sane
,# setup
,# 20. another
,# teardown
,ok 75 sane
,# setup
,# 21. #startListeningForAdvertisements should fail if start not called
,# teardown
,ok 76 specific error should be returned
,# setup
,ok 77 error should be null
,ok 78 error should be null
,# 22. #startUpdateAdvertisingAndListening should fail if start not called
,# teardown
,ok 79 specific error should be returned
,# setup
,ok 80 error should be null
,ok 81 error should be null
,# 23. should be able to call #stopListeningForAdvertisements many times
,# teardown
,ok 82 error should be null
,ok 83 error should be null
,ok 84 error should be null
,ok 85 error should be null
,# setup
,ok 86 error should be null
,ok 87 error should be null
,# 24. should be able to call #startListeningForAdvertisements many times
,# teardown
,ok 88 error should be null
,ok 89 error should be null
,ok 90 error should be null
,ok 91 error should be null
,# setup
,INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 92 error should be null
,ok 93 error should be null
,# 25. should be able to call #startUpdateAdvertisingAndListening many times
,# teardown
,ok 94 error should be null
,ok 95 error should be null
,ok 96 error should be null
,ok 97 error should be null
,# setup
,INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 98 error should be null
,ok 99 error should be null
,# 26. should be able to call #stopAdvertisingAndListening many times
,# teardown
,ok 100 error should be null
,ok 101 error should be null
,ok 102 error should be null
,ok 103 error should be null
,# setup
,ok 104 error should be null
,ok 105 error should be null
,# 27. #start should fail if called twice in a row
,# teardown
,ok 106 first call should succeed
,ok 107 first call should succeed
,ok 108 specific error should be returned
,# setup
,ok 109 error should be null
,ok 110 error should be null
,# 28. does not emit duplicate discoveryAdvertisingStateUpdate
,# teardown
,ok 111 called only once
,ok 112 discovery state matches
,ok 113 advertising state matches
,# setup
,INFO thaliMobile Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
,INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 114 error should be null
,ok 115 error should be null
,# 29. does not send duplicate availability changes
,# teardown
,ok 116 should be called once
,ok 117 should not have been called more than once
,# setup
,ok 118 error should be null
,ok 119 error should be null
,# 30. can get the network status
,# teardown
,ok 120 network status should have certain non-empty properties
,# setup
,ok 121 error should be null
,ok 122 error should be null
,# 31. wifi peer is marked unavailable if announcements stop
,# teardown
,ok 123 host address should match
,ok 124 port should match
,ok 125 host address should be null
,ok 126 port should should be null
,# setup
,INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 127 error should be null
,ok 128 error should be null
,# 32. Can call start/stopListeningForAdvertisements
,# teardown
,2016-03-21 08:39:19.433 ThaliTest[1926:3222507] jxcore: startListeningForAdvertisements
,2016-03-21 08:39:19.434 ThaliTest[1926:3222507] multipeer manager: start client restart timer: 0x156d1f50
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-21 08:39:19.438 ThaliTest[1926:3222507] jxcore: startListeningForAdvertisements: success
,ok 129 Can call startListeningForAdvertisements without error
,2016-03-21 08:39:19.445 ThaliTest[1926:3222507] jxcore: stopListeningForAdvertisements
,2016-03-21 08:39:19.446 ThaliTest[1926:3222507] multipeer manager: stop client timer
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 08:39:19.449 ThaliTest[1926:3222507] jxcore: stopListeningForAdvertisements: success
,ok 130 Can call stopListeningForAdvertisements without error
,# setup
,2016-03-21 08:39:19.867 ThaliTest[1926:3222507] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 08:39:19.869 ThaliTest[1926:3222507] jxcore: stopListeningForAdvertisements: success
,ok 131 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-21 08:39:19.872 ThaliTest[1926:3222507] jxcore: stopAdvertisingAndListening
,2016-03-21 08:39:19.873 ThaliTest[1926:3222507] THEMultipeerManager stopping peer
,2016-03-21 08:39:19.873 ThaliTest[1926:3222507] jxcore: stopAdvertisingAndListening: success
,ok 132 Should be able to call stopAdvertisingAndListening in teardown
,# 33. Calling startListeningForAdvertisements twice is NOT an error
,# teardown
,2016-03-21 08:39:20.422 ThaliTest[1926:3222507] jxcore: startListeningForAdvertisements
,2016-03-21 08:39:20.423 ThaliTest[1926:3222507] multipeer manager: start client restart timer: 0x156d1f50
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-21 08:39:20.426 ThaliTest[1926:3222507] jxcore: startListeningForAdvertisements: success
,ok 133 Can call startListeningForAdvertisements without error
,2016-03-21 08:39:20.429 ThaliTest[1926:3222507] jxcore: startListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-21 08:39:20.431 ThaliTest[1926:3222507] jxcore: startListeningForAdvertisements: success
,ok 134 Can call startListeningForAdvertisements twice without error
,# setup
,2016-03-21 08:39:21.428 ThaliTest[1926:3222507] jxcore: stopListeningForAdvertisements
2016-03-21 08:39:21.429 ThaliTest[1926:3222507] multipeer manager: stop client timer
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 08:39:21.432 ThaliTest[1926:3222507] jxcore: stopListeningForAdvertisements: success
,ok 135 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-21 08:39:21.435 ThaliTest[1926:3222507] jxcore: stopAdvertisingAndListening
2016-03-21 08:39:21.435 ThaliTest[1926:3222507] THEMultipeerManager stopping peer
2016-03-21 08:39:21.436 ThaliTest[1926:3222507] jxcore: stopAdvertisingAndListening: success
,ok 136 Should be able to call stopAdvertisingAndListening in teardown
,# 34. Can call start/stopUpdateAdvertisingAndListening
,# teardown
,2016-03-21 08:39:22.288 ThaliTest[1926:3222507] jxcore: startUpdateAdvertisingAndListening
,2016-03-21 08:39:22.289 ThaliTest[1926:3222507] server: starting 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:1
,2016-03-21 08:39:22.290 ThaliTest[1926:3222507] multipeer manager: start client restart timer: 0x156d1f50
2016-03-21 08:39:22.291 ThaliTest[1926:3222507] THEMultipeerManager initialized peer 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:1
,2016-03-21 08:39:22.291 ThaliTest[1926:3222507] jxcore: startUpdateAdvertisingAndListening: success
,ok 137 Can call startUpdateAdvertisingAndListening without error
2016-03-21 08:39:22.295 ThaliTest[1926:3222507] jxcore: stopAdvertisingAndListening
2016-03-21 08:39:22.295 ThaliTest[1926:3222507] THEMultipeerManager stopping peer
2016-03-21 08:39:22.29,5 ThaliTest[1926:3222507] multipeer manager: stop client timer
2016-03-21 08:39:22.296 ThaliTest[1926:3222507] jxcore: stopAdvertisingAndListening: success
,ok 138 Can call stopAdvertisingAndListening without error
,# setup
,2016-03-21 08:39:22.774 ThaliTest[1926:3222507] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 08:39:22.776 ThaliTest[1926:3222507] jxcore: stopListeningForAdvertisements: success
,ok 139 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-21 08:39:22.778 ThaliTest[1926:3222507] jxcore: stopAdvertisingAndListening
,2016-03-21 08:39:22.779 ThaliTest[1926:3222507] THEMultipeerManager stopping peer
,2016-03-21 08:39:22.779 ThaliTest[1926:3222507] jxcore: stopAdvertisingAndListening: success
,ok 140 Should be able to call stopAdvertisingAndListening in teardown
,# 35. Calling startUpdateAdvertisingAndListening twice is NOT an error
,# teardown
,2016-03-21 08:39:23.820 ThaliTest[1926:3222507] jxcore: startUpdateAdvertisingAndListening
,2016-03-21 08:39:23.820 ThaliTest[1926:3222507] server: starting 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:2
,2016-03-21 08:39:23.822 ThaliTest[1926:3222507] multipeer manager: start client restart timer: 0x156d1f50
2016-03-21 08:39:23.822 ThaliTest[1926:3222507] THEMultipeerManager initialized peer 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:2
2016-03-21 08:39:23.822 ThaliTest[1926:3222507] jxcore: startUpdateAdvertisingAndListening: success
,ok 141 Can call startUpdateAdvertisingAndListening without error
,2016-03-21 08:39:23.830 ThaliTest[1926:3222507] jxcore: startUpdateAdvertisingAndListening
,2016-03-21 08:39:23.832 ThaliTest[1926:3222507] THEMultipeerManager stopping peer
2016-03-21 08:39:23.833 ThaliTest[1926:3222507] multipeer manager: stop client timer
,2016-03-21 08:39:23.833 ThaliTest[1926:3222507] server: starting 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:3
,2016-03-21 08:39:23.835 ThaliTest[1926:3222507] multipeer manager: start client restart timer: 0x156d1f50
2016-03-21 08:39:23.835 ThaliTest[1926:3222507] THEMultipeerManager initialized peer 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:3
2016-03-21 08:39:23.836 ThaliTest[1926:3222507] jxcore: startUpdateAdvertisingAndListening: success
,ok 142 Can call startUpdateAdvertisingAndListening twice without error
,# setup
,2016-03-21 08:39:23.982 ThaliTest[1926:3222507] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-21 08:39:23.984 ThaliTest[1926:3222507] jxcore: stopListeningForAdvertisements: success
,ok 143 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-21 08:39:23.986 ThaliTest[1926:3222507] jxcore: stopAdvertisingAndListening
,2016-03-21 08:39:23.987 ThaliTest[1926:3222507] THEMultipeerManager stopping peer
,2016-03-21 08:39:23.988 ThaliTest[1926:3222507] multipeer manager: stop client timer
2016-03-21 08:39:23.989 ThaliTest[1926:3222507] jxcore: stopAdvertisingAndListening: success
,ok 144 Should be able to call stopAdvertisingAndListening in teardown
,# 36. peerAvailabilityChange is called
,# teardown
,2016-03-21 08:39:24.480 ThaliTest[1926:3222507] jxcore: startUpdateAdvertisingAndListening
,2016-03-21 08:39:24.481 ThaliTest[1926:3222507] server: starting 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:4
,2016-03-21 08:39:24.482 ThaliTest[1926:3222507] multipeer manager: start client restart timer: 0x156d1f50
2016-03-21 08:39:24.482 ThaliTest[1926:3222507] THEMultipeerManager initialized peer 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:4
2016-03-21 08:39:24.483 ,ThaliTest[1926:3222507] jxcore: startUpdateAdvertisingAndListening: success
ok 145 Can call startUpdateAdvertisingAndListeningwithout error
,2016-03-21 08:39:24.486 ThaliTest[1926:3222507] jxcore: startListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-21 08:39:24.488 ThaliTest[1926:3222507], jxcore: startListeningForAdvertisements: success
,ok 146 Can call startListeningForAdvertisements without error
,2016-03-21 08:39:25.704 ThaliTest[1926:3222287] client: found new peer: 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:4
,ok 147 peers must be an array
,ok 148 peers must not be zero-length
,ok 149 peer must have peerIdentifier
,ok 150 peerIdentifier must be a string
,ok 151 peer must have peerAvailable
,ok 152 peer must have pleaseConnect
,# setup
,2016-03-21 08:39:26.545 ThaliTest[1926:3222507] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-21 08:39:26.547 ThaliTest[1926:3222507] jxcore: stopListeningForAdvertisements: success
,ok 153 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-21 08:39:26.549 ThaliTest[1926:3222507] jxcore: stopAdvertisingAndListening
,2016-03-21 08:39:26.550 ThaliTest[1926:3222507] THEMultipeerManager stopping peer
,2016-03-21 08:39:26.551 ThaliTest[1926:3222507] multipeer manager: stop client timer
2016-03-21 08:39:26.552 ThaliTest[1926:3222507] jxcore: stopAdvertisingAndListening: success
ok 154 Should be able to call stopAdvertisingAndListening in teardown
,# 37. Can connect to a remote peer
,# teardown
,2016-03-21 08:39:27.096 ThaliTest[1926:3222507] jxcore: startUpdateAdvertisingAndListening
,2016-03-21 08:39:27.097 ThaliTest[1926:3222507] server: starting 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
,2016-03-21 08:39:27.098 ThaliTest[1926:3222507] multipeer manager: start client restart timer: 0x156d1f50
2016-03-21 08:39:27.099 ThaliTest[1926:3222507] THEMultipeerManager initialized peer 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
2016-03-21 08:39:27.099 ThaliTest[1926:3222507] jxcore: startUpdateAdvertisingAndListening: success
,ok 155 Can call startUpdateAdvertisingAndListening without error
,2016-03-21 08:39:27.101 ThaliTest[1926:3222507] jxcore: startListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-21 08:39:27.105 ThaliTest[1926:3222507] jxcore: startListeningForAdvertisements: success
,ok 156 Can call startListeningForAdvertisements without error
,2016-03-21 08:39:27.678 ThaliTest[1926:3222287] client: found new peer: 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:4
,INFO testThaliMobileNative Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"7AE3ED20-28A5-49DE-832C-CB513D1E3D29:4","pleaseConnect":0}]
,2016-03-21 08:39:27.682 ThaliTest[1926:3222507] jxcore: connect 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:4
,2016-03-21 08:39:27.683 ThaliTest[1926:3222507] client: server will connect
,2016-03-21 08:39:27.683 ThaliTest[1926:3222507] client session: reverseConnect
,2016-03-21 08:39:27.684 ThaliTest[1926:3222507] client session: stateChange:0->1 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:4
,2016-03-21 08:39:28.027 ThaliTest[1926:3222949] client session: not connected 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:4
2016-03-21 08:39:28.027 ThaliTest[1926:3222949] client session: onLinkFailure: 7AE3ED20-28A5-49DE-832C-CB513D1E3D29
2016-03-21 08:39:28.027 ThaliTest[1926:3222949] client session: disconnect
,2016-03-21 08:39:28.028 ThaliTest[1926:3222949] client session: stateChange:1->0 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:4
,2016-03-21 08:39:28.030 ThaliTest[1926:3222949] client session: no connect callback (server initiated)
,2016-03-21 08:39:28.451 ThaliTest[1926:3222287] multipeer session: reset timer
,2016-03-21 08:39:28.452 ThaliTest[1926:3222287] server: rejecting invitation from 7AE3ED20-28A5-49DE-832C-CB513D1E3D29 due to previous generation (1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5 != 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:4)
,2016-03-21 08:39:31.584 ThaliTest[1926:3222287] multipeer session: reset timer
2016-03-21 08:39:31.585 ThaliTest[1926:3222287] server: disconnecting to refresh session (7AE3ED20-28A5-49DE-832C-CB513D1E3D29)
,2016-03-21 08:39:31.585 ThaliTest[1926:3222287] server: rejecting invitation from 7AE3ED20-28A5-49DE-832C-CB513D1E3D29 due to previous generation (1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5 != 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:4)
,2016-03-21 08:39:34.683 ThaliTest[1926:3222287] multipeer session: reset timer
2016-03-21 08:39:34.684 ThaliTest[1926:3222287] server: disconnecting to refresh session (7AE3ED20-28A5-49DE-832C-CB513D1E3D29)
,2016-03-21 08:39:34.684 ThaliTest[1926:3222287] server: rejecting invitation from 7AE3ED20-28A5-49DE-832C-CB513D1E3D29 due to previous generation (1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5 != 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:4)
,2016-03-21 08:39:37.685 ThaliTest[1926:3222287] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative Scheduling a connect retry - retries left: 9
,2016-03-21 08:39:38.713 ThaliTest[1926:3222287] multipeer session: reset timer
2016-03-21 08:39:38.714 ThaliTest[1926:3222287] server: disconnecting to refresh session (7AE3ED20-28A5-49DE-832C-CB513D1E3D29)
,2016-03-21 08:39:38.714 ThaliTest[1926:3222287] server: rejecting invitation from 7AE3ED20-28A5-49DE-832C-CB513D1E3D29 due to previous generation (1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5 != 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:4)
,2016-03-21 08:39:40.700 ThaliTest[1926:3222507] jxcore: connect 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:4
,2016-03-21 08:39:40.701 ThaliTest[1926:3222507] client: server will connect
,2016-03-21 08:39:40.702 ThaliTest[1926:3222507] client session: reverseConnect
,2016-03-21 08:39:40.702 ThaliTest[1926:3222507] client session: stateChange:0->1 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:4
,2016-03-21 08:39:40.989 ThaliTest[1926:3222949] client session: not connected 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:4
2016-03-21 08:39:40.990 ThaliTest[1926:3222949] client session: onLinkFailure: 7AE3ED20-28A5-49DE-832C-CB513D1E3D29
,2016-03-21 08:39:40.990 ThaliTest[1926:3222949] client session: disconnect
2016-03-21 08:39:40.992 ThaliTest[1926:3222949] client session: stateChange:1->0 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:4
2016-03-21 08:39:40.992 ThaliTest[1926:3222949] client session: no connect callback (server initiated)
,2016-03-21 08:39:42.426 ThaliTest[1926:3222287] multipeer session: reset timer
,2016-03-21 08:39:42.427 ThaliTest[1926:3222287] server: disconnecting to refresh session (7AE3ED20-28A5-49DE-832C-CB513D1E3D29)
,2016-03-21 08:39:42.427 ThaliTest[1926:3222287] server: rejecting invitation from 7AE3ED20-28A5-49DE-832C-CB513D1E3D29 due to previous generation (1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5 != 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:4)
,2016-03-21 08:39:47.073 ThaliTest[1926:3222287] multipeer session: reset timer
2016-03-21 08:39:47.074 ThaliTest[1926:3222287] server: disconnecting to refresh session (7AE3ED20-28A5-49DE-832C-CB513D1E3D29)
,2016-03-21 08:39:47.074 ThaliTest[1926:3222287] server: rejecting invitation from 7AE3ED20-28A5-49DE-832C-CB513D1E3D29 due to previous generation (1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5 != 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:4)
,2016-03-21 08:39:47.100 ThaliTest[1926:3222287] multipeer manager: restart client
,2016-03-21 08:39:47.112 ThaliTest[1926:3222287] client: found updated peer: 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5
,INFO testThaliMobileNative Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5","pleaseConnect":0}]
,2016-03-21 08:39:50.702 ThaliTest[1926:3222287] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative Scheduling a connect retry - retries left: 8
,2016-03-21 08:39:53.714 ThaliTest[1926:3222507] jxcore: connect 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:4
,2016-03-21 08:39:53.715 ThaliTest[1926:3222507] client: server will connect
,2016-03-21 08:39:53.715 ThaliTest[1926:3222507] client session: reverseConnect
,2016-03-21 08:39:53.716 ThaliTest[1926:3222507] client session: stateChange:0->1 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5
,2016-03-21 08:39:54.141 ThaliTest[1926:3223091] client session: not connected 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5
2016-03-21 08:39:54.141 ThaliTest[1926:3223091] client session: onLinkFailure: 7AE3ED20-28A5-49DE-832C-CB513D1E3D29
2016-03-21 08:39:54.142 ThaliTest[1926:3223091] client session: disconnect
,2016-03-21 08:39:54.142 ThaliTest[1926:3223091] client session: stateChange:1->0 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5
,2016-03-21 08:39:54.143 ThaliTest[1926:3223091] client session: no connect callback (server initiated)
,2016-03-21 08:40:03.717 ThaliTest[1926:3222287] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative Scheduling a connect retry - retries left: 7
,2016-03-21 08:40:06.730 ThaliTest[1926:3222507] jxcore: connect 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:4
2016-03-21 08:40:06.731 ThaliTest[1926:3222507] client: server will connect
,2016-03-21 08:40:06.731 ThaliTest[1926:3222507] client session: reverseConnect
2016-03-21 08:40:06.732 ThaliTest[1926:3222507] client session: stateChange:0->1 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5
,2016-03-21 08:40:07.100 ThaliTest[1926:3222287] multipeer manager: restart client
,2016-03-21 08:40:07.117 ThaliTest[1926:3222287] client: found existing peer: 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5
,2016-03-21 08:40:16.733 ThaliTest[1926:3222287] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative Scheduling a connect retry - retries left: 6
,2016-03-21 08:40:19.739 ThaliTest[1926:3222507] jxcore: connect 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:4
,2016-03-21 08:40:19.740 ThaliTest[1926:3222507] client: already connect(ing/ed) to 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:4
,2016-03-21 08:40:19.740 ThaliTest[1926:3222507] jxcore: connect: fail: Already connect(ing/ed)
,INFO testThaliMobileNative Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative Scheduling a connect retry - retries left: 5
,2016-03-21 08:40:22.035 ThaliTest[1926:3222287] multipeer session: reset timer
2016-03-21 08:40:22.036 ThaliTest[1926:3222287] server: disconnecting to refresh session (7AE3ED20-28A5-49DE-832C-CB513D1E3D29)
,2016-03-21 08:40:22.036 ThaliTest[1926:3222287] server: rejecting invitation from 7AE3ED20-28A5-49DE-832C-CB513D1E3D29 due to previous generation (1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5 != 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:4)
,2016-03-21 08:40:22.753 ThaliTest[1926:3222507] jxcore: connect 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:4
,2016-03-21 08:40:22.754 ThaliTest[1926:3222507] client: already connect(ing/ed) to 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:4
2016-03-21 08:40:22.754 ThaliTest[1926:3222507] jxcore: connect: fail: Already connect(ing/ed)
,INFO testThaliMobileNative Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative Scheduling a connect retry - retries left: 4
,2016-03-21 08:40:25.536 ThaliTest[1926:3222287] multipeer session: reset timer
2016-03-21 08:40:25.537 ThaliTest[1926:3222287] server: disconnecting to refresh session (7AE3ED20-28A5-49DE-832C-CB513D1E3D29)
2016-03-21 08:40:25.537 ThaliTest[1926:3222287], server: rejecting invitation from 7AE3ED20-28A5-49DE-832C-CB513D1E3D29 due to previous generation (1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5 != 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:4)
,2016-03-21 08:40:25.773 ThaliTest[1926:3222507] jxcore: connect 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:4
,2016-03-21 08:40:25.774 ThaliTest[1926:3222507] client: already connect(ing/ed) to 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:4
,2016-03-21 08:40:25.774 ThaliTest[1926:3222507] jxcore: connect: fail: Already connect(ing/ed)
,INFO testThaliMobileNative Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative Scheduling a connect retry - retries left: 3
,2016-03-21 08:40:27.100 ThaliTest[1926:3222287] multipeer manager: restart client
,2016-03-21 08:40:27.116 ThaliTest[1926:3222287] client: found existing peer: 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5
,2016-03-21 08:40:28.708 ThaliTest[1926:3222287] multipeer session: reset timer
2016-03-21 08:40:28.709 ThaliTest[1926:3222287] server: disconnecting to refresh session (7AE3ED20-28A5-49DE-832C-CB513D1E3D29)
,2016-03-21 08:40:28.709 ThaliTest[1926:3222287] server: rejecting invitation from 7AE3ED20-28A5-49DE-832C-CB513D1E3D29 due to previous generation (1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5 != 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:4)
,2016-03-21 08:40:28.792 ThaliTest[1926:3222507] jxcore: connect 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:4
,2016-03-21 08:40:28.793 ThaliTest[1926:3222507] client: already connect(ing/ed) to 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:4
,2016-03-21 08:40:28.793 ThaliTest[1926:3222507] jxcore: connect: fail: Already connect(ing/ed)
,INFO testThaliMobileNative Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative Scheduling a connect retry - retries left: 2
,2016-03-21 08:40:31.812 ThaliTest[1926:3222507] jxcore: connect 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:4
2016-03-21 08:40:31.813 ThaliTest[1926:3222507] client: already connect(ing/ed) to 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:4
2016-03-21 08:40:31.814 Thali,Test[1926:3222507] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative Scheduling a connect retry - retries left: 1
,2016-03-21 08:40:31.887 ThaliTest[1926:3222287] multipeer session: reset timer
2016-03-21 08:40:31.888 ThaliTest[1926:3222287] server: disconnecting to refresh session (7AE3ED20-28A5-49DE-832C-CB513D1E3D29)
2016-03-21 08:40:31.888 ThaliTest[1926:3222287], server: rejecting invitation from 7AE3ED20-28A5-49DE-832C-CB513D1E3D29 due to previous generation (1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5 != 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:4)
,2016-03-21 08:40:34.843 ThaliTest[1926:3222507] jxcore: connect 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:4
,2016-03-21 08:40:34.844 ThaliTest[1926:3222507] client: already connect(ing/ed) to 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:4
2016-03-21 08:40:34.845 ThaliTest[1926:3222507] jxcore: connect: fail: Already connect(ing/ed)
,INFO testThaliMobileNative Connect returned an error: Already connect(ing/ed)
,WARN testThaliMobileNative Too many connect retries!
,2016-03-21 08:40:39.709 ThaliTest[1926:3223248] client session: not connected 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5
2016-03-21 08:40:39.710 ThaliTest[1926:3223248] client session: onLinkFailure: 7AE3ED20-28A5-49DE-832C-CB513D1E3D29
2016-03-21 08:40:39.7,10 ThaliTest[1926:3223248] client session: disconnect
2016-03-21 08:40:39.710 ThaliTest[1926:3223248] client session: stateChange:1->0 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5
2016-03-21 08:40:39.711 ThaliTest[1926:3223248] client session: no connect callback (server initiated)
,2016-03-21 08:40:47.100 ThaliTest[1926:3222287] multipeer manager: restart client
,2016-03-21 08:40:47.114 ThaliTest[1926:3222287] client: found existing peer: 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5
,2016-03-21 08:41:07.100 ThaliTest[1926:3222287] multipeer manager: restart client
,2016-03-21 08:41:07.114 ThaliTest[1926:3222287] client: found existing peer: 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5
,2016-03-21 08:41:27.099 ThaliTest[1926:3222287] multipeer manager: restart client
,2016-03-21 08:41:27.114 ThaliTest[1926:3222287] client: found existing peer: 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5
,2016-03-21 08:41:47.100 ThaliTest[1926:3222287] multipeer manager: restart client
,2016-03-21 08:41:47.115 ThaliTest[1926:3222287] client: found existing peer: 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5
,2016-03-21 08:42:07.100 ThaliTest[1926:3222287] multipeer manager: restart client
,2016-03-21 08:42:07.113 ThaliTest[1926:3222287] client: found existing peer: 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5
,2016-03-21 08:42:27.100 ThaliTest[1926:3222287] multipeer manager: restart client
,2016-03-21 08:42:27.113 ThaliTest[1926:3222287] client: found existing peer: 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5
,2016-03-21 08:42:47.100 ThaliTest[1926:3222287] multipeer manager: restart client
,2016-03-21 08:42:47.113 ThaliTest[1926:3222287] client: found existing peer: 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5
,2016-03-21 08:43:07.100 ThaliTest[1926:3222287] multipeer manager: restart client
,2016-03-21 08:43:07.114 ThaliTest[1926:3222287] client: found existing peer: 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5
,2016-03-21 08:43:27.100 ThaliTest[1926:3222287] multipeer manager: restart client
,2016-03-21 08:43:27.114 ThaliTest[1926:3222287] client: found existing peer: 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5
,2016-03-21 08:43:47.100 ThaliTest[1926:3222287] multipeer manager: restart client
,2016-03-21 08:43:47.114 ThaliTest[1926:3222287] client: found existing peer: 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5
,2016-03-21 08:44:07.100 ThaliTest[1926:3222287] multipeer manager: restart client
,2016-03-21 08:44:07.115 ThaliTest[1926:3222287] client: found existing peer: 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5
,2016-03-21 08:44:27.100 ThaliTest[1926:3222287] multipeer manager: restart client
,2016-03-21 08:44:27.115 ThaliTest[1926:3222287] client: found existing peer: 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5
,2016-03-21 08:44:47.099 ThaliTest[1926:3222287] multipeer manager: restart client
,2016-03-21 08:44:47.111 ThaliTest[1926:3222287] client: found existing peer: 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5
,2016-03-21 08:45:07.100 ThaliTest[1926:3222287] multipeer manager: restart client
,2016-03-21 08:45:07.113 ThaliTest[1926:3222287] client: found existing peer: 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5
,2016-03-21 08:45:27.100 ThaliTest[1926:3222287] multipeer manager: restart client
,2016-03-21 08:45:27.116 ThaliTest[1926:3222287] client: found existing peer: 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5
,2016-03-21 08:45:47.100 ThaliTest[1926:3222287] multipeer manager: restart client
,2016-03-21 08:45:47.113 ThaliTest[1926:3222287] client: found existing peer: 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5
,2016-03-21 08:46:07.100 ThaliTest[1926:3222287] multipeer manager: restart client
,2016-03-21 08:46:07.113 ThaliTest[1926:3222287] client: found existing peer: 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5
,2016-03-21 08:46:27.100 ThaliTest[1926:3222287] multipeer manager: restart client
,2016-03-21 08:46:27.114 ThaliTest[1926:3222287] client: found existing peer: 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5
,2016-03-21 08:46:47.100 ThaliTest[1926:3222287] multipeer manager: restart client
,2016-03-21 08:46:47.112 ThaliTest[1926:3222287] client: found existing peer: 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5
,2016-03-21 08:47:07.100 ThaliTest[1926:3222287] multipeer manager: restart client
,2016-03-21 08:47:07.113 ThaliTest[1926:3222287] client: found existing peer: 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5
,2016-03-21 08:47:27.100 ThaliTest[1926:3222287] multipeer manager: restart client
,2016-03-21 08:47:27.114 ThaliTest[1926:3222287] client: found existing peer: 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5
,2016-03-21 08:47:47.100 ThaliTest[1926:3222287] multipeer manager: restart client
,2016-03-21 08:47:47.114 ThaliTest[1926:3222287] client: found existing peer: 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5
,2016-03-21 08:48:07.100 ThaliTest[1926:3222287] multipeer manager: restart client
,2016-03-21 08:48:07.113 ThaliTest[1926:3222287] client: found existing peer: 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5
,2016-03-21 08:48:27.100 ThaliTest[1926:3222287] multipeer manager: restart client
,2016-03-21 08:48:27.114 ThaliTest[1926:3222287] client: found existing peer: 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5
,2016-03-21 08:48:47.099 ThaliTest[1926:3222287] multipeer manager: restart client
,2016-03-21 08:48:47.112 ThaliTest[1926:3222287] client: found existing peer: 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5
,2016-03-21 08:49:07.099 ThaliTest[1926:3222287] multipeer manager: restart client
,2016-03-21 08:49:07.113 ThaliTest[1926:3222287] client: found existing peer: 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5
,2016-03-21 08:49:27.100 ThaliTest[1926:3222287] multipeer manager: restart client
,2016-03-21 08:49:27.113 ThaliTest[1926:3222287] client: found existing peer: 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5
,2016-03-21 08:49:47.100 ThaliTest[1926:3222287] multipeer manager: restart client
,2016-03-21 08:49:47.114 ThaliTest[1926:3222287] client: found existing peer: 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5
,2016-03-21 08:50:07.100 ThaliTest[1926:3222287] multipeer manager: restart client
,2016-03-21 08:50:07.113 ThaliTest[1926:3222287] client: found existing peer: 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5
,2016-03-21 08:50:27.100 ThaliTest[1926:3222287] multipeer manager: restart client
,2016-03-21 08:50:27.114 ThaliTest[1926:3222287] client: found existing peer: 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5
,2016-03-21 08:50:47.100 ThaliTest[1926:3222287] multipeer manager: restart client
,2016-03-21 08:50:47.112 ThaliTest[1926:3222287] client: found existing peer: 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5
,2016-03-21 08:51:07.100 ThaliTest[1926:3222287] multipeer manager: restart client
,2016-03-21 08:51:07.115 ThaliTest[1926:3222287] client: found existing peer: 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5
,2016-03-21 08:51:27.100 ThaliTest[1926:3222287] multipeer manager: restart client
,2016-03-21 08:51:27.112 ThaliTest[1926:3222287] client: found existing peer: 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5
,2016-03-21 08:51:47.100 ThaliTest[1926:3222287] multipeer manager: restart client
,2016-03-21 08:51:47.112 ThaliTest[1926:3222287] client: found existing peer: 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5
,2016-03-21 08:52:07.100 ThaliTest[1926:3222287] multipeer manager: restart client
,2016-03-21 08:52:07.115 ThaliTest[1926:3222287] client: found existing peer: 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5
,2016-03-21 08:52:27.100 ThaliTest[1926:3222287] multipeer manager: restart client
,2016-03-21 08:52:27.113 ThaliTest[1926:3222287] client: found existing peer: 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5
,2016-03-21 08:52:47.100 ThaliTest[1926:3222287] multipeer manager: restart client
,2016-03-21 08:52:47.114 ThaliTest[1926:3222287] client: found existing peer: 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5
,2016-03-21 08:53:07.100 ThaliTest[1926:3222287] multipeer manager: restart client
,2016-03-21 08:53:07.113 ThaliTest[1926:3222287] client: found existing peer: 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5
,2016-03-21 08:53:27.100 ThaliTest[1926:3222287] multipeer manager: restart client
,2016-03-21 08:53:27.113 ThaliTest[1926:3222287] client: found existing peer: 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5
,2016-03-21 08:53:47.100 ThaliTest[1926:3222287] multipeer manager: restart client
,2016-03-21 08:53:47.113 ThaliTest[1926:3222287] client: found existing peer: 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5
,2016-03-21 08:54:07.100 ThaliTest[1926:3222287] multipeer manager: restart client
,2016-03-21 08:54:07.113 ThaliTest[1926:3222287] client: found existing peer: 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5
,2016-03-21 08:54:27.100 ThaliTest[1926:3222287] multipeer manager: restart client
,2016-03-21 08:54:27.113 ThaliTest[1926:3222287] client: found existing peer: 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5
,2016-03-21 08:54:47.100 ThaliTest[1926:3222287] multipeer manager: restart client
,2016-03-21 08:54:47.113 ThaliTest[1926:3222287] client: found existing peer: 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5
,2016-03-21 08:55:07.100 ThaliTest[1926:3222287] multipeer manager: restart client
,2016-03-21 08:55:07.114 ThaliTest[1926:3222287] client: found existing peer: 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5
,2016-03-21 08:55:27.100 ThaliTest[1926:3222287] multipeer manager: restart client
,2016-03-21 08:55:27.112 ThaliTest[1926:3222287] client: found existing peer: 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5
,2016-03-21 08:55:47.100 ThaliTest[1926:3222287] multipeer manager: restart client
,2016-03-21 08:55:47.113 ThaliTest[1926:3222287] client: found existing peer: 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5
,2016-03-21 08:56:07.100 ThaliTest[1926:3222287] multipeer manager: restart client
,2016-03-21 08:56:07.114 ThaliTest[1926:3222287] client: found existing peer: 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5
,2016-03-21 08:56:27.100 ThaliTest[1926:3222287] multipeer manager: restart client
,2016-03-21 08:56:27.112 ThaliTest[1926:3222287] client: found existing peer: 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5
,2016-03-21 08:56:47.100 ThaliTest[1926:3222287] multipeer manager: restart client
,2016-03-21 08:56:47.114 ThaliTest[1926:3222287] client: found existing peer: 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5
,2016-03-21 08:57:07.100 ThaliTest[1926:3222287] multipeer manager: restart client
,2016-03-21 08:57:07.113 ThaliTest[1926:3222287] client: found existing peer: 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5

```
