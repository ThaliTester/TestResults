#### Test 63186632d456b18_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/63186632d456b18/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/60FACA24-AE9E-4C95-93E5-54B897B3B953/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/60FACA24-AE9E-4C95-93E5-54B897B3B953/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/63186632d456b18/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/63186632d456b18/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/19B78B0A-B6B1-42CF-95B7-C89B262ABCD1/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51282"
,(lldb)     command script import "/tmp/60FACA24-AE9E-4C95-93E5-54B897B3B953/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-17 09:48:19.475 ThaliTest[1250:2778841] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/5D89D405-895E-43FC-9033-A1B160B8CF87/Library/Cookies/Cookies.binarycookies
,2016-03-17 09:48:19.583 ThaliTest[1250:2778841] Apache Cordova native platform version 4.0.1 is starting.
2016-03-17 09:48:19.585 ThaliTest[1250:2778841] Multi-tasking -> Device: YES, App: YES
,2016-03-17 09:48:19.602 ThaliTest[1250:2778841] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-17 09:48:21.746 ThaliTest[1250:2778841] Using UIWebView
,2016-03-17 09:48:21.751 ThaliTest[1250:2778841] [CDVTimer][handleopenurl] 0.415027ms
,2016-03-17 09:48:21.756 ThaliTest[1250:2778841] [CDVTimer][intentandnavigationfilter] 5.125046ms
2016-03-17 09:48:21.757 ThaliTest[1250:2778841] [CDVTimer][gesturehandler] 0.257015ms
2016-03-17 09:48:21.757 ThaliTest[1250:2778841] [CDVTimer][TotalPluginStartup] 6.951034ms
,2016-03-17 09:48:30.122 ThaliTest[1250:2778841] Resetting plugins due to page load.
,2016-03-17 09:48:34.317 ThaliTest[1250:2778841] Finished load of: file:///var/mobile/Containers/Bundle/Application/19B78B0A-B6B1-42CF-95B7-C89B262ABCD1/ThaliTest.app/www/index.html
,2016-03-17 09:48:34.524 ThaliTest[1250:2778841] JXcore Cordova plugin initializing
,2016-03-17 09:48:34.525 ThaliTest[1250:2779035] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-17 09:48:44.332 ThaliTest[1250:2779035] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-17 09:48:44.333 ThaliTest[1250:2779035] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-17 09:48:44.334 ThaliTest[1250:2779035] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-17 09:48:44.339 ThaliTest[1250:2779035] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/19B78B0A-B6B1-42CF-95B7-C89B262ABCD1/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/19B78B0A-B6B1-42CF-95B7-C89B262ABCD1/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/19B78B0A-B6B1-42CF-95B7-C89B262ABCD1/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/19B78B0A-B6B1-42CF-95B7-C89B262ABCD1/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/19B78B0A-B6B1-42CF-95B7-C89B262ABCD1/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/19B78B0A-B6B1-42CF-95B7-C89B262ABCD1/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/19B78B0A-B6B1-42CF-95B7-C89B262ABCD1/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/19B78B0A-B6B1-42CF-95B7-C89B262ABCD1/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/19B78B0A-B6B1-42CF-95B7-C89B262ABCD1/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/19B78B0A-B6B1-42CF-95B7-C89B262ABCD1/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/19B78B0A-B6B1-42CF-95B7-C89B262ABCD1/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/19B78B0A-B6B1-42CF-95B7-C89B262ABCD1/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/19B78B0A-B6B1-42CF-95B7-C89B262ABCD1/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/19B78B0A-B6B1-42CF-95B7-C89B262ABCD1/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/19B78B0A-B6B1-42CF-95B7-C89B262ABCD1/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/19B78B0A-B6B1-42CF-95B7-C89B262ABCD1/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/19B78B0A-B6B1-42CF-95B7-C89B262ABCD1/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/19B78B0A-B6B1-42CF-95B7-C89B262ABCD1/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/19B78B0A-B6B1-42CF-95B7-C89B262ABCD1/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-17 09:49:04.440 ThaliTest[1250:2778841] THREAD WARNING: ['JXcore'] took '14531.001953' ms. Plugin should use a background thread.
,2016-03-17 09:49:04.442 ThaliTest[1250:2778975] void SendDelegateMessage(NSInvocation *): delegate (webView:decidePolicyForNavigationAction:request:frame:decisionListener:) failed to return after waiting 10 seconds. main run loop mode: kCFRunLoopDefaultMod,e
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
ok 65 fourth
ok 66 second
,ok 67 secondPromise - in then
,ok 68 first
,ok 69 firstPromise - in catch
,ok 70 third
,ok 71 thirdPromise - in then
ok 72 testingPromises
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
ok 95 error should be null
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
ok 105 error should be null
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
INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
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
,2016-03-17 09:52:52.253 ThaliTest[1250:2779035] jxcore: startListeningForAdvertisements
,2016-03-17 09:52:52.255 ThaliTest[1250:2779035] multipeer manager: start client restart timer: 0x166d1f00
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-17 09:52:52.258 ThaliTest[1250:2779035] jxcore: startListeningForAdvertisements: success
ok 129 Can call startListeningForAdvertisements without error
2016-03-17 09:52:52.265 ThaliTest[1250:2779035] jxcore: stopListeningForAdvertisements
2016-03,-17 09:52:52.265 ThaliTest[1250:2779035] multipeer manager: stop client timer
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-17 09:52:52.267 ThaliTest[1250:2779035] jxcore: stopListeningForAdvertisements: success
,ok 130 Can call stopListeningForAdvertisements without error
,# setup
,2016-03-17 09:52:52.362 ThaliTest[1250:2779035] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-17 09:52:52.364 ThaliTest[1250:2779035] jxcore: stopListeningForAdvertisements: success
,ok 131 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-17 09:52:52.366 ThaliTest[1250:2779035] jxcore: stopAdvertisingAndListening
2016-03-17 09:52:52.366 ThaliTest[1250:2779035] THEMultipeerManager stopping peer
2016-03-17 09:52:52.366 ThaliTest[1250:2779035] jxcore: stopAdvertisingAndListening: suc,cess
ok 132 Should be able to call stopAdvertisingAndListening in teardown
,# 33. Calling startListeningForAdvertisements twice is NOT an error
,# teardown
,2016-03-17 09:52:53.112 ThaliTest[1250:2779035] jxcore: startListeningForAdvertisements
2016-03-17 09:52:53.112 ThaliTest[1250:2779035] multipeer manager: start client restart timer: 0x166d1f00
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-17 09:52:53.114 ThaliTest[1250:2779035] jxcore: startListeningForAdvertisements: success
,ok 133 Can call startListeningForAdvertisements without error
,2016-03-17 09:52:53.115 ThaliTest[1250:2779035] jxcore: startListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-17 09:52:53.117 ThaliTest[1250:2779035] jxcore: startListeningForAdvertisements: success
,ok 134 Can call startListeningForAdvertisements twice without error
,# setup
,2016-03-17 09:52:53.222 ThaliTest[1250:2779035] jxcore: stopListeningForAdvertisements
2016-03-17 09:52:53.222 ThaliTest[1250:2779035] multipeer manager: stop client timer
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-17 09:52:53.224 ThaliTest[1250:2779035] jxcore: stopListeningForAdvertisements: success
,ok 135 Should be able to call stopListeningForAdvertisments in teardown
2016-03-17 09:52:53.225 ThaliTest[1250:2779035] jxcore: stopAdvertisingAndListening
,2016-03-17 09:52:53.225 ThaliTest[1250:2779035] THEMultipeerManager stopping peer
,2016-03-17 09:52:53.226 ThaliTest[1250:2779035] jxcore: stopAdvertisingAndListening: success
,ok 136 Should be able to call stopAdvertisingAndListening in teardown
,# 34. Can call start/stopUpdateAdvertisingAndListening
,# teardown
,2016-03-17 09:52:54.108 ThaliTest[1250:2779035] jxcore: startUpdateAdvertisingAndListening
2016-03-17 09:52:54.108 ThaliTest[1250:2779035] server: starting 2766A7C7-4577-4560-847A-F62CCBA6A141:1
2016-03-17 09:52:54.109 ThaliTest[1250:2779035] multipeer m,anager: start client restart timer: 0x166d1f00
2016-03-17 09:52:54.109 ThaliTest[1250:2779035] THEMultipeerManager initialized peer 2766A7C7-4577-4560-847A-F62CCBA6A141:1
2016-03-17 09:52:54.109 ThaliTest[1250:2779035] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 137 Can call startUpdateAdvertisingAndListening without error
2016-03-17 09:52:54.111 ThaliTest[1250:2779035] jxcore: stopAdvertisingAndListening
2016-03-17 09:52:54.111 ThaliTest[1250:2779035] THEMultipeerManager stopping peer
,2016-03-17 09:52:54.111 ThaliTest[1250:2779035] multipeer manager: stop client timer
2016-03-17 09:52:54.111 ThaliTest[1250:2779035] jxcore: stopAdvertisingAndListening: success
ok 138 Can call stopAdvertisingAndListening without error
,# setup
,2016-03-17 09:52:54.234 ThaliTest[1250:2779035] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-17 09:52:54.235 ThaliTest[1250:2779035] jxcore: stopListeningForAdvertisements: success
,ok 139 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-17 09:52:54.237 ThaliTest[1250:2779035] jxcore: stopAdvertisingAndListening
2016-03-17 09:52:54.237 ThaliTest[1250:2779035] THEMultipeerManager stopping peer
2016-03-17 09:52:54.238 ThaliTest[1250:2779035] jxcore: stopAdvertisingAndListening: success
ok 140 Should be able to call stopAdvertisingAndListening in teardown
,# 35. Calling startUpdateAdvertisingAndListening twice is NOT an error
,# teardown
,2016-03-17 09:52:54.796 ThaliTest[1250:2779035] jxcore: startUpdateAdvertisingAndListening
2016-03-17 09:52:54.797 ThaliTest[1250:2779035] server: starting 2766A7C7-4577-4560-847A-F62CCBA6A141:2
2016-03-17 09:52:54.797 ThaliTest[1250:2779035] multipeer m,anager: start client restart timer: 0x166d1f00
2016-03-17 09:52:54.797 ThaliTest[1250:2779035] THEMultipeerManager initialized peer 2766A7C7-4577-4560-847A-F62CCBA6A141:2
2016-03-17 09:52:54.798 ThaliTest[1250:2779035] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 141 Can call startUpdateAdvertisingAndListening without error
2016-03-17 09:52:54.799 ThaliTest[1250:2779035] jxcore: startUpdateAdvertisingAndListening
2016-03-17 09:52:54.799 ThaliTest[1250:2779035] THEMultipeerManager stopping pee,r
2016-03-17 09:52:54.800 ThaliTest[1250:2779035] multipeer manager: stop client timer
2016-03-17 09:52:54.800 ThaliTest[1250:2779035] server: starting 2766A7C7-4577-4560-847A-F62CCBA6A141:3
2016-03-17 09:52:54.800 ThaliTest[1250:2779035] multipeer man,a,ger: start client restart timer: 0x166d1f00
2016-03-17 09:52:54.804 ThaliTest[1250:2779035] THEMultipeerManager initialized peer 2766A7C7-4577-4560-847A-F62CCBA6A141:3
2016-03-17 09:52:54.805 ThaliTest[1250:2779035] jxcore: startUpdateAdvertisingAndListening: success
ok 142 Can call startUpdateAdvertisingAndListening twice without error
,# setup
,2016-03-17 09:52:55.079 ThaliTest[1250:2779035] jxcore: stopListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-17 09:52:55.081 ThaliTest[1250:2779035] jxcore: stopListeningForAdvertisements: success
,ok 143 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-17 09:52:55.082 ThaliTest[1250:2779035] jxcore: stopAdvertisingAndListening
2016-03-17 09:52:55.083 ThaliTest[1250:2779035] THEMultipeerManager stopping peer
2016-03-17 09:52:55.083 ThaliTest[1250:2779035] multipeer manager: stop client timer
2016-03-17 09:52:55.083 ThaliTest[1250:2779035] jxcore: stopAdvertisingAndListening: success
ok 144 Should be able to call stopAdvertisingAndListening in teardown
,# 36. peerAvailabilityChange is called
,# teardown
,2016-03-17 09:52:58.397 ThaliTest[1250:2779035] jxcore: startUpdateAdvertisingAndListening
2016-03-17 09:52:58.398 ThaliTest[1250:2779035] server: starting 2766A7C7-4577-4560-847A-F62CCBA6A141:4
2016-03-17 09:52:58.398 ThaliTest[1250:2779035] multipeer m,anager: start client restart timer: 0x166d1f00
2016-03-17 09:52:58.398 ThaliTest[1250:2779035] THEMultipeerManager initialized peer 2766A7C7-4577-4560-847A-F62CCBA6A141:4
2016-03-17 09:52:58.398 ThaliTest[1250:2779035] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 145 Can call startUpdateAdvertisingAndListeningwithout error
2016-03-17 09:52:58.400 ThaliTest[1250:2779035] jxcore: startListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingAc,tive":true,"discoveryActive":true}
2016-03-17 09:52:58.401 ThaliTest[1250:2779035] jxcore: startListeningForAdvertisements: success
ok 146 Can call startListeningForAdvertisements without error
,2016-03-17 09:52:59.196 ThaliTest[1250:2778841] client: found new peer: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:4
ok 147 peers must be an array
ok 148 peers must not be zero-length
,ok 149 peer must have peerIdentifier
,ok 150 peerIdentifier must be a string
ok 151 peer must have peerAvailable
,ok 152 peer must have pleaseConnect
,# setup
,2016-03-17 09:52:59.418 ThaliTest[1250:2779035] jxcore: stopListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-17 09:52:59.420 ThaliTest[1250:2779035] jxcore: stopListeningForAdvertisements: success
,ok 153 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-17 09:52:59.421 ThaliTest[1250:2779035] jxcore: stopAdvertisingAndListening
2016-03-17 09:52:59.422 ThaliTest[1250:2779035] THEMultipeerManager stopping peer
2016-03-17 09:52:59.422 ThaliTest[1250:2779035] multipeer manager: stop client timer
2016-03-17 09:52:59.422 ThaliTest[1250:2779035] jxcore: stopAdvertisingAndListening: success
ok 154 Should be able to call stopAdvertisingAndListening in teardown
,# 37. Can connect to a remote peer
,# teardown
,2016-03-17 09:52:59.948 ThaliTest[1250:2779035] jxcore: startUpdateAdvertisingAndListening
2016-03-17 09:52:59.949 ThaliTest[1250:2779035] server: starting 2766A7C7-4577-4560-847A-F62CCBA6A141:5
2016-03-17 09:52:59.949 ThaliTest[1250:2779035] multipeer m,anager: start client restart timer: 0x166d1f00
2016-03-17 09:52:59.949 ThaliTest[1250:2779035] THEMultipeerManager initialized peer 2766A7C7-4577-4560-847A-F62CCBA6A141:5
2016-03-17 09:52:59.950 ThaliTest[1250:2779035] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 155 Can call startUpdateAdvertisingAndListening without error
,2016-03-17 09:52:59.951 ThaliTest[1250:2779035] jxcore: startListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
,2016-03-17 09:52:59.953 ThaliTest[1250:2779035] jxcore: startListeningForAdvertisements: success
ok 156 Can call startListeningForAdvertisements without error
,2016-03-17 09:53:01.878 ThaliTest[1250:2778841] client: found new peer: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:4
INFO testThaliMobileNative Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"18009BE9-5DE3-42DE-8B21-9C164A8A04D8:4","pleaseConnect":0}]
,2016-03-17 09:53:01.881 ThaliTest[1250:2779035] jxcore: connect 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:4
2016-03-17 09:53:01.882 ThaliTest[1250:2779035] client session: connect
2016-03-17 09:53:01.882 ThaliTest[1250:2779035] client session: stateChange:0->1 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:4
,2016-03-17 09:53:02.439 ThaliTest[1250:2779574] client session: not connected 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:4
2016-03-17 09:53:02.439 ThaliTest[1250:2779574] client session: onLinkFailure: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8
2016-03-17 09:53:02.4,39 ThaliTest[1250:2779574] client session: disconnect
2016-03-17 09:53:02.439 ThaliTest[1250:2779574] client session: stateChange:1->0 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:4
2016-03-17 09:53:02.440 ThaliTest[1250:2779574] client session: fireConnectCallb,ack: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8
2016-03-17 09:53:02.440 ThaliTest[1250:2779574] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative Connect returned an error: Peer disconnected
INFO testThaliMobileNative Scheduling a connect retry - retries left: 9
,2016-03-17 09:53:05.451 ThaliTest[1250:2779035] jxcore: connect 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:4
2016-03-17 09:53:05.452 ThaliTest[1250:2779035] client session: connect
2016-03-17 09:53:05.452 ThaliTest[1250:2779035] client session: stateChange:0->1 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:4
,2016-03-17 09:53:05.560 ThaliTest[1250:2779574] client session: not connected 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:4
2016-03-17 09:53:05.561 ThaliTest[1250:2779574] client session: onLinkFailure: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8
,2016-03-17 09:53:05.561 ThaliTest[1250:2779574] client session: disconnect
2016-03-17 09:53:05.562 ThaliTest[1250:2779574] client session: stateChange:1->0 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:4
2016-03-17 09:53:05.563 ThaliTest[1250:2779574] client sess,ion: fireConnectCallback: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8
2016-03-17 09:53:05.563 ThaliTest[1250:2779574] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative Connect returned an error: Peer disconnected
INFO testThaliMobileNative Sc,heduling a connect retry - retries left: 8
,2016-03-17 09:53:08.571 ThaliTest[1250:2779035] jxcore: connect 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:4
2016-03-17 09:53:08.572 ThaliTest[1250:2779035] client session: connect
2016-03-17 09:53:08.572 ThaliTest[1250:2779035] client session: stateChange:0->1 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:4
,2016-03-17 09:53:08.859 ThaliTest[1250:2779576] client session: not connected 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:4
2016-03-17 09:53:08.860 ThaliTest[1250:2779576] client session: onLinkFailure: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8
2016-03-17 09:53:08.860 ThaliTest[1250:2779576] client session: disconnect
2016-03-17 09:53:08.860 ThaliTest[1250:2779576] client session: stateChange:1->0 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:4
,2016-03-17 09:53:08.862 ThaliTest[1250:2779576] client session: fireConnectCallback: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8
2016-03-17 09:53:08.862 ThaliTest[1250:2779576] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative Connect returned an error: Peer disconnected
INFO testThaliMobileNative Scheduling a connect retry - retries left: 7
,2016-03-17 09:53:11.866 ThaliTest[1250:2779035] jxcore: connect 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:4
2016-03-17 09:53:11.866 ThaliTest[1250:2779035] client session: connect
2016-03-17 09:53:11.867 ThaliTest[1250:2779035] client session: stateChange:0->1 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:4
,2016-03-17 09:53:12.937 ThaliTest[1250:2779563] client session: not connected 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:4
2016-03-17 09:53:12.937 ThaliTest[1250:2779563] client session: onLinkFailure: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8
2016-03-17 09:53:12.9,37 ThaliTest[1250:2779563] client session: disconnect
2016-03-17 09:53:12.938 ThaliTest[1250:2779563] client session: stateChange:1->0 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:4
,2016-03-17 09:53:12.938 ThaliTest[1250:2779563] client session: fireConnectCallback: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8
2016-03-17 09:53:12.939 ThaliTest[1250:2779563] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative Connect returned an error: Peer disconnected
INFO testThaliMobileNative Scheduling a connect retry - retries left: 6
,2016-03-17 09:53:15.948 ThaliTest[1250:2779035] jxcore: connect 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:4
2016-03-17 09:53:15.949 ThaliTest[1250:2779035] client session: connect
2016-03-17 09:53:15.949 ThaliTest[1250:2779035] client session: stateChange:0->1 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:4
,2016-03-17 09:53:16.043 ThaliTest[1250:2779574] client session: not connected 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:4
2016-03-17 09:53:16.043 ThaliTest[1250:2779574] client session: onLinkFailure: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8
2016-03-17 09:53:16.0,43 ThaliTest[1250:2779574] client session: disconnect
2016-03-17 09:53:16.043 ThaliTest[1250:2779574] client session: stateChange:1->0 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:4
,2016-03-17 09:53:16.045 ThaliTest[1250:2779574] client session: fireConnectCallback: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8
2016-03-17 09:53:16.045 ThaliTest[1250:2779574] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative Connect returned an error: Peer disconnected
INFO testThaliMobileNative Scheduling a connect retry - retries left: 5
,2016-03-17 09:53:19.051 ThaliTest[1250:2779035] jxcore: connect 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:4
2016-03-17 09:53:19.051 ThaliTest[1250:2779035] client session: connect
2016-03-17 09:53:19.052 ThaliTest[1250:2779035] client session: stateChange:0->1 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:4
,2016-03-17 09:53:19.196 ThaliTest[1250:2779576] client session: not connected 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:4
2016-03-17 09:53:19.196 ThaliTest[1250:2779576] client session: onLinkFailure: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8
2016-03-17 09:53:19.1,96 ThaliTest[1250:2779576] client session: disconnect
2016-03-17 09:53:19.196 ThaliTest[1250:2779576] client session: stateChange:1->0 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:4
,2016-03-17 09:53:19.198 ThaliTest[1250:2779576] client session: fireConnectCallback: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8
2016-03-17 09:53:19.198 ThaliTest[1250:2779576] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative Connect returned an error: Peer disconnected
INFO testThaliMobileNative Scheduling a connect retry - retries left: 4
,2016-03-17 09:53:19.950 ThaliTest[1250:2778841] multipeer manager: restart client
,2016-03-17 09:53:19.964 ThaliTest[1250:2778841] client: found updated peer: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
INFO testThaliMobileNative Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5","pleaseConnect":0}]
,2016-03-17 09:53:22.207 ThaliTest[1250:2779035] jxcore: connect 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:4
2016-03-17 09:53:22.208 ThaliTest[1250:2779035] client session: connect
2016-03-17 09:53:22.208 ThaliTest[1250:2779035] client session: stateChange:0->,1 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
,2016-03-17 09:53:22.585 ThaliTest[1250:2779534] client session: not connected 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
2016-03-17 09:53:22.585 ThaliTest[1250:2779534] client session: onLinkFailure: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8
2016-03-17 09:53:22.5,86 ThaliTest[1250:2779534] client session: disconnect
2016-03-17 09:53:22.586 ThaliTest[1250:2779534] client session: stateChange:1->0 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
2016-03-17 09:53:22.586 ThaliTest[1250:2779534] client session: fireConnectCallb,ack: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8
2016-03-17 09:53:22.586 ThaliTest[1250:2779534] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative Connect returned an error: Peer disconnected
INFO testThaliMobileNative Scheduling a connect retry - retries left: 3
,2016-03-17 09:53:25.591 ThaliTest[1250:2779035] jxcore: connect 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:4
2016-03-17 09:53:25.592 ThaliTest[1250:2779035] client session: connect
2016-03-17 09:53:25.592 ThaliTest[1250:2779035] client session: stateChange:0->1 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
,2016-03-17 09:53:25.975 ThaliTest[1250:2779576] client session: not connected 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
2016-03-17 09:53:25.976 ThaliTest[1250:2779576] client session: onLinkFailure: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8
2016-03-17 09:53:25.9,76 ThaliTest[1250:2779576] client session: disconnect
2016-03-17 09:53:25.976 ThaliTest[1250:2779576] client session: stateChange:1->0 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
2016-03-17 09:53:25.977 ThaliTest[1250:2779576] client session: fireConnectCallb,ack: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8
2016-03-17 09:53:25.977 ThaliTest[1250:2779576] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative Connect returned an error: Peer disconnected
INFO testThaliMobileNative Scheduling a connect re,try - retries left: 2
,2016-03-17 09:53:28.982 ThaliTest[1250:2779035] jxcore: connect 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:4
2016-03-17 09:53:28.983 ThaliTest[1250:2779035] client session: connect
2016-03-17 09:53:28.983 ThaliTest[1250:2779035] client session: stateChange:0->1 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
,2016-03-17 09:53:29.468 ThaliTest[1250:2779576] client session: not connected 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
2016-03-17 09:53:29.469 ThaliTest[1250:2779576] client session: onLinkFailure: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8
2016-03-17 09:53:29.469 ThaliTest[1250:2779576] client session: disconnect
2016-03-17 09:53:29.469 ThaliTest[1250:2779576] client session: stateChange:1->0 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
,2016-03-17 09:53:29.470 ThaliTest[1250:2779576] client session: fireConnectCallback: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8
,2016-03-17 09:53:29.471 ThaliTest[1250:2779576] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative Connect returned an error: Peer disconnected
INFO testThaliMobileNative Scheduling a connect retry - retries left: 1
,2016-03-17 09:53:32.482 ThaliTest[1250:2779035] jxcore: connect 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:4
2016-03-17 09:53:32.482 ThaliTest[1250:2779035] client session: connect
2016-03-17 09:53:32.483 ThaliTest[1250:2779035] client session: stateChange:0->,1 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
,2016-03-17 09:53:32.663 ThaliTest[1250:2779563] client session: not connected 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
2016-03-17 09:53:32.664 ThaliTest[1250:2779563] client session: onLinkFailure: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8
2016-03-17 09:53:32.6,64 ThaliTest[1250:2779563] client session: disconnect
2016-03-17 09:53:32.664 ThaliTest[1250:2779563] client session: stateChange:1->0 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
2016-03-17 09:53:32.665 ThaliTest[1250:2779563] client session: fireConnectCallback: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8
,2016-03-17 09:53:32.665 ThaliTest[1250:2779563] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative Connect returned an error: Peer disconnected
WARN testThaliMobileNative Too many connect retries!
,2016-03-17 09:53:39.950 ThaliTest[1250:2778841] multipeer manager: restart client
,2016-03-17 09:53:39.963 ThaliTest[1250:2778841] client: found existing peer: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
,2016-03-17 09:53:59.950 ThaliTest[1250:2778841] multipeer manager: restart client
,2016-03-17 09:53:59.965 ThaliTest[1250:2778841] client: found existing peer: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
,2016-03-17 09:54:19.950 ThaliTest[1250:2778841] multipeer manager: restart client
,2016-03-17 09:54:19.965 ThaliTest[1250:2778841] client: found existing peer: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
,2016-03-17 09:54:39.950 ThaliTest[1250:2778841] multipeer manager: restart client
,2016-03-17 09:54:39.963 ThaliTest[1250:2778841] client: found existing peer: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
,2016-03-17 09:54:59.951 ThaliTest[1250:2778841] multipeer manager: restart client
,2016-03-17 09:54:59.965 ThaliTest[1250:2778841] client: found existing peer: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
,2016-03-17 09:55:19.950 ThaliTest[1250:2778841] multipeer manager: restart client
,2016-03-17 09:55:19.964 ThaliTest[1250:2778841] client: found existing peer: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
,2016-03-17 09:55:39.950 ThaliTest[1250:2778841] multipeer manager: restart client
,2016-03-17 09:55:39.964 ThaliTest[1250:2778841] client: found existing peer: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
,2016-03-17 09:55:59.950 ThaliTest[1250:2778841] multipeer manager: restart client
,2016-03-17 09:55:59.965 ThaliTest[1250:2778841] client: found existing peer: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
,2016-03-17 09:56:19.950 ThaliTest[1250:2778841] multipeer manager: restart client
,2016-03-17 09:56:19.965 ThaliTest[1250:2778841] client: found existing peer: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
,2016-03-17 09:56:39.950 ThaliTest[1250:2778841] multipeer manager: restart client
,2016-03-17 09:56:39.964 ThaliTest[1250:2778841] client: found existing peer: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
,2016-03-17 09:56:59.950 ThaliTest[1250:2778841] multipeer manager: restart client
,2016-03-17 09:56:59.964 ThaliTest[1250:2778841] client: found existing peer: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
,2016-03-17 09:57:19.950 ThaliTest[1250:2778841] multipeer manager: restart client
,2016-03-17 09:57:19.963 ThaliTest[1250:2778841] client: found existing peer: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
,2016-03-17 09:57:39.951 ThaliTest[1250:2778841] multipeer manager: restart client
,2016-03-17 09:57:39.965 ThaliTest[1250:2778841] client: found existing peer: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
,2016-03-17 09:57:59.950 ThaliTest[1250:2778841] multipeer manager: restart client
,2016-03-17 09:57:59.966 ThaliTest[1250:2778841] client: found existing peer: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
,2016-03-17 09:58:19.950 ThaliTest[1250:2778841] multipeer manager: restart client
,2016-03-17 09:58:19.964 ThaliTest[1250:2778841] client: found existing peer: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
,2016-03-17 09:58:39.950 ThaliTest[1250:2778841] multipeer manager: restart client
,2016-03-17 09:58:39.964 ThaliTest[1250:2778841] client: found existing peer: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
,2016-03-17 09:58:59.950 ThaliTest[1250:2778841] multipeer manager: restart client
,2016-03-17 09:58:59.964 ThaliTest[1250:2778841] client: found existing peer: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
,2016-03-17 09:59:19.950 ThaliTest[1250:2778841] multipeer manager: restart client
,2016-03-17 09:59:19.965 ThaliTest[1250:2778841] client: found existing peer: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
,2016-03-17 09:59:39.950 ThaliTest[1250:2778841] multipeer manager: restart client
,2016-03-17 09:59:39.964 ThaliTest[1250:2778841] client: found existing peer: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
,2016-03-17 09:59:59.950 ThaliTest[1250:2778841] multipeer manager: restart client
,2016-03-17 09:59:59.965 ThaliTest[1250:2778841] client: found existing peer: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
,2016-03-17 10:00:19.950 ThaliTest[1250:2778841] multipeer manager: restart client
,2016-03-17 10:00:19.965 ThaliTest[1250:2778841] client: found existing peer: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
,2016-03-17 10:00:39.950 ThaliTest[1250:2778841] multipeer manager: restart client
,2016-03-17 10:00:39.966 ThaliTest[1250:2778841] client: found existing peer: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
,2016-03-17 10:00:59.951 ThaliTest[1250:2778841] multipeer manager: restart client
,2016-03-17 10:00:59.965 ThaliTest[1250:2778841] client: found existing peer: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
,2016-03-17 10:01:19.950 ThaliTest[1250:2778841] multipeer manager: restart client
,2016-03-17 10:01:19.965 ThaliTest[1250:2778841] client: found existing peer: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
,2016-03-17 10:01:39.950 ThaliTest[1250:2778841] multipeer manager: restart client
,2016-03-17 10:01:39.964 ThaliTest[1250:2778841] client: found existing peer: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
,2016-03-17 10:01:59.950 ThaliTest[1250:2778841] multipeer manager: restart client
,2016-03-17 10:01:59.964 ThaliTest[1250:2778841] client: found existing peer: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
,2016-03-17 10:02:19.950 ThaliTest[1250:2778841] multipeer manager: restart client
,2016-03-17 10:02:19.964 ThaliTest[1250:2778841] client: found existing peer: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
,2016-03-17 10:02:39.950 ThaliTest[1250:2778841] multipeer manager: restart client
,2016-03-17 10:02:39.965 ThaliTest[1250:2778841] client: found existing peer: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
,2016-03-17 10:02:59.950 ThaliTest[1250:2778841] multipeer manager: restart client
,2016-03-17 10:02:59.964 ThaliTest[1250:2778841] client: found existing peer: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
,2016-03-17 10:03:19.950 ThaliTest[1250:2778841] multipeer manager: restart client
,2016-03-17 10:03:19.965 ThaliTest[1250:2778841] client: found existing peer: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
,2016-03-17 10:03:39.950 ThaliTest[1250:2778841] multipeer manager: restart client
,2016-03-17 10:03:39.966 ThaliTest[1250:2778841] client: found existing peer: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
,2016-03-17 10:03:59.950 ThaliTest[1250:2778841] multipeer manager: restart client
,2016-03-17 10:03:59.965 ThaliTest[1250:2778841] client: found existing peer: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
,2016-03-17 10:04:19.950 ThaliTest[1250:2778841] multipeer manager: restart client
,2016-03-17 10:04:19.968 ThaliTest[1250:2778841] client: found existing peer: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
,2016-03-17 10:04:39.950 ThaliTest[1250:2778841] multipeer manager: restart client
,2016-03-17 10:04:39.963 ThaliTest[1250:2778841] client: found existing peer: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
,2016-03-17 10:04:59.950 ThaliTest[1250:2778841] multipeer manager: restart client
,2016-03-17 10:04:59.964 ThaliTest[1250:2778841] client: found existing peer: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
,2016-03-17 10:05:19.950 ThaliTest[1250:2778841] multipeer manager: restart client
,2016-03-17 10:05:19.967 ThaliTest[1250:2778841] client: found existing peer: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
,2016-03-17 10:05:39.950 ThaliTest[1250:2778841] multipeer manager: restart client
,2016-03-17 10:05:39.964 ThaliTest[1250:2778841] client: found existing peer: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
,2016-03-17 10:05:59.950 ThaliTest[1250:2778841] multipeer manager: restart client
,2016-03-17 10:05:59.963 ThaliTest[1250:2778841] client: found existing peer: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
,2016-03-17 10:06:19.950 ThaliTest[1250:2778841] multipeer manager: restart client
,2016-03-17 10:06:19.965 ThaliTest[1250:2778841] client: found existing peer: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
,2016-03-17 10:06:39.951 ThaliTest[1250:2778841] multipeer manager: restart client
,2016-03-17 10:06:39.965 ThaliTest[1250:2778841] client: found existing peer: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
,2016-03-17 10:06:59.950 ThaliTest[1250:2778841] multipeer manager: restart client
,2016-03-17 10:06:59.965 ThaliTest[1250:2778841] client: found existing peer: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
,2016-03-17 10:07:19.950 ThaliTest[1250:2778841] multipeer manager: restart client
,2016-03-17 10:07:19.965 ThaliTest[1250:2778841] client: found existing peer: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
,2016-03-17 10:07:39.950 ThaliTest[1250:2778841] multipeer manager: restart client
,2016-03-17 10:07:39.965 ThaliTest[1250:2778841] client: found existing peer: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
,2016-03-17 10:07:59.950 ThaliTest[1250:2778841] multipeer manager: restart client
,2016-03-17 10:07:59.964 ThaliTest[1250:2778841] client: found existing peer: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
,2016-03-17 10:08:19.950 ThaliTest[1250:2778841] multipeer manager: restart client
,2016-03-17 10:08:19.965 ThaliTest[1250:2778841] client: found existing peer: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
,2016-03-17 10:08:39.951 ThaliTest[1250:2778841] multipeer manager: restart client
,2016-03-17 10:08:39.965 ThaliTest[1250:2778841] client: found existing peer: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
,2016-03-17 10:08:59.950 ThaliTest[1250:2778841] multipeer manager: restart client
,2016-03-17 10:08:59.965 ThaliTest[1250:2778841] client: found existing peer: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
,2016-03-17 10:09:19.950 ThaliTest[1250:2778841] multipeer manager: restart client
,2016-03-17 10:09:19.964 ThaliTest[1250:2778841] client: found existing peer: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
,2016-03-17 10:09:39.950 ThaliTest[1250:2778841] multipeer manager: restart client
,2016-03-17 10:09:39.964 ThaliTest[1250:2778841] client: found existing peer: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
,2016-03-17 10:09:59.950 ThaliTest[1250:2778841] multipeer manager: restart client
,2016-03-17 10:09:59.965 ThaliTest[1250:2778841] client: found existing peer: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
,2016-03-17 10:10:19.950 ThaliTest[1250:2778841] multipeer manager: restart client
,2016-03-17 10:10:19.962 ThaliTest[1250:2778841] client: found existing peer: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
,2016-03-17 10:10:39.950 ThaliTest[1250:2778841] multipeer manager: restart client
,2016-03-17 10:10:39.965 ThaliTest[1250:2778841] client: found existing peer: 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5

```
