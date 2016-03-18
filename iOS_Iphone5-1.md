#### Test 63377149f0d5e10_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/63377149f0d5e10/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/BB09DC4F-05BC-4844-8C21-B941B3F4EE14/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/BB09DC4F-05BC-4844-8C21-B941B3F4EE14/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/63377149f0d5e10/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/63377149f0d5e10/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/847EED9C-C06C-4119-8558-A1C464363471/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52614"
,(lldb)     command script import "/tmp/BB09DC4F-05BC-4844-8C21-B941B3F4EE14/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-18 15:46:39.212 ThaliTest[1312:2971502] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/517F177F-4A0D-4E36-BB95-3B49E4433D52/Library/Cookies/Cookies.binarycookies
,2016-03-18 15:46:39.325 ThaliTest[1312:2971502] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-18 15:46:39.327 ThaliTest[1312:2971502] Multi-tasking -> Device: YES, App: YES
,2016-03-18 15:46:39.348 ThaliTest[1312:2971502] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-18 15:46:41.395 ThaliTest[1312:2971502] Using UIWebView
,2016-03-18 15:46:41.400 ThaliTest[1312:2971502] [CDVTimer][handleopenurl] 0.315011ms
,2016-03-18 15:46:41.406 ThaliTest[1312:2971502] [CDVTimer][intentandnavigationfilter] 5.357981ms
2016-03-18 15:46:41.406 ThaliTest[1312:2971502] [CDVTimer][gesturehandler] 0.258982ms
2016-03-18 15:46:41.407 ThaliTest[1312:2971502] [CDVTimer][TotalPluginStartup] 7.071972ms
,2016-03-18 15:46:49.779 ThaliTest[1312:2971502] Resetting plugins due to page load.
,2016-03-18 15:46:53.497 ThaliTest[1312:2971502] Finished load of: file:///var/mobile/Containers/Bundle/Application/847EED9C-C06C-4119-8558-A1C464363471/ThaliTest.app/www/index.html
,2016-03-18 15:46:53.702 ThaliTest[1312:2971502] JXcore Cordova plugin initializing
,2016-03-18 15:46:53.704 ThaliTest[1312:2972290] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-18 15:47:03.782 ThaliTest[1312:2972290] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-18 15:47:03.783 ThaliTest[1312:2972290] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-18 15:47:03.783 ThaliTest[1312:2,972290] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-18 15:47:03.788 ThaliTest[1312:2972290] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/847EED9C-C06C-4119-8558-A1C464363471/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/847EED9C-C06C-4119-8558-A1C464363471/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/847EED9C-C06C-4119-8558-A1C464363471/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/847EED9C-C06C-4119-8558-A1C464363471/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/847EED9C-C06C-4119-8558-A1C464363471/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/847EED9C-C06C-4119-8558-A1C464363471/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/847EED9C-C06C-4119-8558-A1C464363471/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/847EED9C-C06C-4119-8558-A1C464363471/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/847EED9C-C06C-4119-8558-A1C464363471/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/847EED9C-C06C-4119-8558-A1C464363471/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/847EED9C-C06C-4119-8558-A1C464363471/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/847EED9C-C06C-4119-8558-A1C464363471/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/847EED9C-C06C-4119-8558-A1C464363471/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/847EED9C-C06C-4119-8558-A1C464363471/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/847EED9C-C06C-4119-8558-A1C464363471/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/847EED9C-C06C-4119-8558-A1C464363471/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/847EED9C-C06C-4119-8558-A1C464363471/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/847EED9C-C06C-4119-8558-A1C464363471/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/847EED9C-C06C-4119-8558-A1C464363471/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/847EED9C-C06C-4119-8558-A1C464363471/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-18 15:47:23.809 ThaliTest[1312:2971502] THREAD WARNING: ['JXcore'] took '14455.485840' ms. Plugin should use a background thread.
,2016-03-18 15:47:23.811 ThaliTest[1312:2971635] void SendDelegateMessage(NSInvocation *): delegate (webView:decidePolicyForNavigationAction:request:frame:decisionListener:) failed to return after waiting 10 seconds. main run loop mode: kCFRunLoopDefaultMode
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
ok 91 error should be null
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
ok 122 error should be null
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
,2016-03-18 15:50:56.227 ThaliTest[1312:2972290] jxcore: startListeningForAdvertisements
,2016-03-18 15:50:56.229 ThaliTest[1312:2972290] multipeer manager: start client restart timer: 0x14dc2cc0
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-18 15:50:56.231 ThaliTest[1312:2972290] jxcore: startListeningForAdvertisements: success
ok 129 Can call startListeningForAdvertisements without error
,2016-03-18 15:50:56.233 ThaliTest[1312:2972290] jxcore: stopListeningForAdvertisements
2016-03-18 15:50:56.234 ThaliTest[1312:2972290] multipeer manager: stop client timer
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-18 15:50:56.235 ThaliTest[1312:2972290] jxcore: stopListeningForAdvertisements: success
,ok 130 Can call stopListeningForAdvertisements without error
# setup
,2016-03-18 15:50:56.381 ThaliTest[1312:2972290] jxcore: stopListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-18 15:50:56.382 ThaliTest[1312:2972290] jxcore: stopListeningForAdvertisements: success
,ok 131 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-18 15:50:56.384 ThaliTest[1312:2972290] jxcore: stopAdvertisingAndListening
2016-03-18 15:50:56.384 ThaliTest[1312:2972290] THEMultipeerManager stopping peer
2016-03-18 15:50:56.384 ThaliTest[1312:2972290] jxcore: stopAdvertisingAndListening: success
ok 132 Should be able to call stopAdvertisingAndListening in teardown
,# 33. Calling startListeningForAdvertisements twice is NOT an error
,# teardown
,2016-03-18 15:50:57.037 ThaliTest[1312:2972290] jxcore: startListeningForAdvertisements
2016-03-18 15:50:57.037 ThaliTest[1312:2972290] multipeer manager: start client restart timer: 0x14dc2cc0
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-18 15:50:57.038 ThaliTest[1312:2972290] jxcore: startListeningForAdvertisements: success
,ok 133 Can call startListeningForAdvertisements without error
2016-03-18 15:50:57.040 ThaliTest[1312:2972290] jxcore: startListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-18 15:50:57.041 ThaliTest[1312:2972290] jxcore: startListeningForAdvertisements: success
,ok 134 Can call startListeningForAdvertisements twice without error
,# setup
,2016-03-18 15:50:57.164 ThaliTest[1312:2972290] jxcore: stopListeningForAdvertisements
2016-03-18 15:50:57.164 ThaliTest[1312:2972290] multipeer manager: stop client timer
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertising,Active":false,"discoveryActive":false}
,2016-03-18 15:50:57.165 ThaliTest[1312:2972290] jxcore: stopListeningForAdvertisements: success
ok 135 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-18 15:50:57.167 ThaliTest[1312:2972290] jxcore: stopAdvertisingAndListening
2016-03-18 15:50:57.167 ThaliTest[1312:2972290] THEMultipeerManager stopping peer
,2016-03-18 15:50:57.167 ThaliTest[1312:2972290] jxcore: stopAdvertisingAndListening: success
,ok 136 Should be able to call stopAdvertisingAndListening in teardown
,# 34. Can call start/stopUpdateAdvertisingAndListening
,# teardown
,2016-03-18 15:51:00.189 ThaliTest[1312:2972290] jxcore: startUpdateAdvertisingAndListening
2016-03-18 15:51:00.189 ThaliTest[1312:2972290] server: starting 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:1
2016-03-18 15:51:00.190 ThaliTest[1312:2972290] multipeer m,anager: start client restart timer: 0x14dc2cc0
2016-03-18 15:51:00.190 ThaliTest[1312:2972290] THEMultipeerManager initialized peer 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:1
2016-03-18 15:51:00.190 ThaliTest[1312:2972290] jxcore: startUpdateAdvertisingAndListening: success
,ok 137 Can call startUpdateAdvertisingAndListening without error
,2016-03-18 15:51:00.192 ThaliTest[1312:2972290] jxcore: stopAdvertisingAndListening
,2016-03-18 15:51:00.193 ThaliTest[1312:2972290] THEMultipeerManager stopping peer
,2016-03-18 15:51:00.193 ThaliTest[1312:2972290] multipeer manager: stop client timer
2016-03-18 15:51:00.194 ThaliTest[1312:2972290] jxcore: stopAdvertisingAndListening: success
ok 138 Can call stopAdvertisingAndListening without error
,# setup
,2016-03-18 15:51:00.308 ThaliTest[1312:2972290] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-18 15:51:00.310 ThaliTest[1312:2972290] jxcore: stopListeningForAdvertisements: success
,ok 139 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-18 15:51:00.311 ThaliTest[1312:2972290] jxcore: stopAdvertisingAndListening
2016-03-18 15:51:00.311 ThaliTest[1312:2972290] THEMultipeerManager stopping peer
2016-03-18 15:51:00.311 ThaliTest[1312:2972290] jxcore: stopAdvertisingAndListening: success
ok 140 Should be able to call stopAdvertisingAndListening in teardown
,# 35. Calling startUpdateAdvertisingAndListening twice is NOT an error
,# teardown
,2016-03-18 15:51:00.731 ThaliTest[1312:2972290] jxcore: startUpdateAdvertisingAndListening
2016-03-18 15:51:00.731 ThaliTest[1312:2972290] server: starting 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:2
2016-03-18 15:51:00.732 ThaliTest[1312:2972290] multipeer m,anager: start client restart timer: 0x14dc2cc0
2016-03-18 15:51:00.732 ThaliTest[1312:2972290] THEMultipeerManager initialized peer 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:2
2016-03-18 15:51:00.732 ThaliTest[1312:2972290] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 141 Can call startUpdateAdvertisingAndListening without error
2016-03-18 15:51:00.733 ThaliTest[1312:2972290] jxcore: startUpdateAdvertisingAndListening
2016-03-18 15:51:00.734 ThaliTest[1312:2972290] THEMultipeerManager stopping pee,r
2016-03-18 15:51:00.734 ThaliTest[1312:2972290] multipeer manager: stop client timer
,2016-03-18 15:51:00.734 ThaliTest[1312:2972290] server: starting 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:3
2016-03-18 15:51:00.735 ThaliTest[1312:2972290] multipeer manager: start client restart timer: 0x14dc2cc0
2016-03-18 15:51:00.735 ThaliTest[1312:29722,90] THEMultipeerManager initialized peer 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:3
2016-03-18 15:51:00.735 ThaliTest[1312:2972290] jxcore: startUpdateAdvertisingAndListening: success
,ok 142 Can call startUpdateAdvertisingAndListening twice without error
,# setup
,2016-03-18 15:51:00.910 ThaliTest[1312:2972290] jxcore: stopListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-18 15:51:00.912 ThaliTest[1312:2972290] jxcore: stopListeningForAdvertisements: success
,ok 143 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-18 15:51:00.914 ThaliTest[1312:2972290] jxcore: stopAdvertisingAndListening
2016-03-18 15:51:00.914 ThaliTest[1312:2972290] THEMultipeerManager stopping peer
2016-03-18 15:51:00.915 ThaliTest[1312:2972290] multipeer manager: stop client timer
20,16-03-18 15:51:00.915 ThaliTest[1312:2972290] jxcore: stopAdvertisingAndListening: success
ok 144 Should be able to call stopAdvertisingAndListening in teardown
,# 36. peerAvailabilityChange is called
,# teardown
,2016-03-18 15:51:01.300 ThaliTest[1312:2972290] jxcore: startUpdateAdvertisingAndListening
2016-03-18 15:51:01.300 ThaliTest[1312:2972290] server: starting 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
2016-03-18 15:51:01.300 ThaliTest[1312:2972290] multipeer m,anager: start client restart timer: 0x14dc2cc0
2016-03-18 15:51:01.301 ThaliTest[1312:2972290] THEMultipeerManager initialized peer 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
2016-03-18 15:51:01.301 ThaliTest[1312:2972290] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 145 Can call startUpdateAdvertisingAndListeningwithout error
,2016-03-18 15:51:01.302 ThaliTest[1312:2972290] jxcore: startListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
,2016-03-18 15:51:01.304 ThaliTest[1312:2972290] jxcore: startListeningForAdvertisements: success
,ok 146 Can call startListeningForAdvertisements without error
,2016-03-18 15:51:03.235 ThaliTest[1312:2971502] client: found new peer: FB7229AA-4713-4BED-BA62-4F08FAA3D947:4
,ok 147 peers must be an array
ok 148 peers must not be zero-length
ok 149 peer must have peerIdentifier
,ok 150 peerIdentifier must be a string
,ok 151 peer must have peerAvailable
,ok 152 peer must have pleaseConnect
,# setup
,2016-03-18 15:51:03.339 ThaliTest[1312:2972290] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-18 15:51:03.340 ThaliTest[1312:2972290] jxcore: stopListeningForAdvertisements: success
,ok 153 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-18 15:51:03.342 ThaliTest[1312:2972290] jxcore: stopAdvertisingAndListening
2016-03-18 15:51:03.342 ThaliTest[1312:2972290] THEMultipeerManager stopping peer
2016-03-18 15:51:03.342 ThaliTest[1312:2972290] multipeer manager: stop client timer
2016-03-18 15:51:03.343 ThaliTest[1312:2972290] jxcore: stopAdvertisingAndListening: success
ok 154 Should be able to call stopAdvertisingAndListening in teardown
,# 37. Can connect to a remote peer
,# teardown
,2016-03-18 15:51:18.669 ThaliTest[1312:2972290] jxcore: startUpdateAdvertisingAndListening
2016-03-18 15:51:18.669 ThaliTest[1312:2972290] server: starting 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:5
2016-03-18 15:51:18.670 ThaliTest[1312:2972290] multipeer m,anager: start client restart timer: 0x14dc2cc0
2016-03-18 15:51:18.670 ThaliTest[1312:2972290] THEMultipeerManager initialized peer 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:5
2016-03-18 15:51:18.670 ThaliTest[1312:2972290] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 155 Can call startUpdateAdvertisingAndListening without error
2016-03-18 15:51:18.671 ThaliTest[1312:2972290] jxcore: startListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingA,ctive":true,"discoveryActive":true}
2016-03-18 15:51:18.672 ThaliTest[1312:2972290] jxcore: startListeningForAdvertisements: success
,ok 156 Can call startListeningForAdvertisements without error
,2016-03-18 15:51:20.698 ThaliTest[1312:2971502] client: found new peer: FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
INFO testThaliMobileNative Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"FB7229AA-4713-4BED-BA62-4F08FAA3D9,47:5","pleaseConnect":0}]
,2016-03-18 15:51:20.701 ThaliTest[1312:2972290] jxcore: connect FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
2016-03-18 15:51:20.701 ThaliTest[1312:2972290] client: server will connect
2016-03-18 15:51:20.702 ThaliTest[1312:2972290] client session: reverseConnect
2016-03-18 15:51:20.702 ThaliTest[1312:2972290] client session: stateChange:0->1 FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 15:51:21.131 ThaliTest[1312:2971502] multipeer session: reset timer
2016-03-18 15:51:21.132 ThaliTest[1312:2971502] server: rejecting invitation from FB7229AA-4713-4BED-BA62-4F08FAA3D947 due to previous generation (5AF2D5AA-97F0-4EB5-AB41-40475,ADCED46:5 != 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4)
,2016-03-18 15:51:21.156 ThaliTest[1312:2972815] client session: not connected FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
2016-03-18 15:51:21.156 ThaliTest[1312:2972815] client session: onLinkFailure: FB7229AA-4713-4BED-BA62-4F08FAA3D947
2016-03-18 15:51:21.1,56 ThaliTest[1312:2972815] client session: disconnect
2016-03-18 15:51:21.157 ThaliTest[1312:2972815] client session: stateChange:1->0 FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 15:51:21.158 ThaliTest[1312:2972815] client session: no connect callback (server initiated)
,2016-03-18 15:51:24.669 ThaliTest[1312:2971502] multipeer session: reset timer
2016-03-18 15:51:24.669 ThaliTest[1312:2971502] server: disconnecting to refresh session (FB7229AA-4713-4BED-BA62-4F08FAA3D947)
2016-03-18 15:51:24.669 ThaliTest[1312:2971502], server: rejecting invitation from FB7229AA-4713-4BED-BA62-4F08FAA3D947 due to previous generation (5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:5 != 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4)
,2016-03-18 15:51:28.368 ThaliTest[1312:2971502] multipeer session: reset timer
2016-03-18 15:51:28.368 ThaliTest[1312:2971502] server: disconnecting to refresh session (FB7229AA-4713-4BED-BA62-4F08FAA3D947)
2016-03-18 15:51:28.368 ThaliTest[1312:2971502] server: rejecting invitation from FB7229AA-4713-4BED-BA62-4F08FAA3D947 due to previous generation (5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:5 != 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4)
,2016-03-18 15:51:30.703 ThaliTest[1312:2971502] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative Scheduling a connect retry - retries left: 9
,2016-03-18 15:51:31.925 ThaliTest[1312:2971502] multipeer session: reset timer
2016-03-18 15:51:31.925 ThaliTest[1312:2971502] server: disconnecting to refresh session (FB7229AA-4713-4BED-BA62-4F08FAA3D947)
2016-03-18 15:51:31.926 ThaliTest[1312:2971502], server: rejecting invitation from FB7229AA-4713-4BED-BA62-4F08FAA3D947 due to previous generation (5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:5 != 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4)
,2016-03-18 15:51:33.713 ThaliTest[1312:2972290] jxcore: connect FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
2016-03-18 15:51:33.713 ThaliTest[1312:2972290] client: server will connect
2016-03-18 15:51:33.714 ThaliTest[1312:2972290] client session: reverseConn,ect
2016-03-18 15:51:33.714 ThaliTest[1312:2972290] client session: stateChange:0->1 FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 15:51:34.152 ThaliTest[1312:2972794] client session: not connected FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
2016-03-18 15:51:34.152 ThaliTest[1312:2972794] client session: onLinkFailure: FB7229AA-4713-4BED-BA62-4F08FAA3D947
2016-03-18 15:51:34.1,52 ThaliTest[1312:2972794] client session: disconnect
2016-03-18 15:51:34.152 ThaliTest[1312:2972794] client session: stateChange:1->0 FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 15:51:34.153 ThaliTest[1312:2972794] client session: no connect callback (server initiated)
,2016-03-18 15:51:35.569 ThaliTest[1312:2971502] multipeer session: reset timer
2016-03-18 15:51:35.570 ThaliTest[1312:2971502] server: disconnecting to refresh session (FB7229AA-4713-4BED-BA62-4F08FAA3D947)
2016-03-18 15:51:35.570 ThaliTest[1312:2971502], server: rejecting invitation from FB7229AA-4713-4BED-BA62-4F08FAA3D947 due to previous generation (5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:5 != 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4)
,2016-03-18 15:51:38.671 ThaliTest[1312:2971502] multipeer manager: restart client
,2016-03-18 15:51:38.684 ThaliTest[1312:2971502] client: found existing peer: FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 15:51:42.033 ThaliTest[1312:2971502] multipeer session: reset timer
2016-03-18 15:51:42.034 ThaliTest[1312:2971502] server: disconnecting to refresh session (FB7229AA-4713-4BED-BA62-4F08FAA3D947)
2016-03-18 15:51:42.034 ThaliTest[1312:2971502], server: rejecting invitation from FB7229AA-4713-4BED-BA62-4F08FAA3D947 due to previous generation (5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:5 != 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4)
,2016-03-18 15:51:43.715 ThaliTest[1312:2971502] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative Scheduling a connect retry - retries left: 8
,2016-03-18 15:51:46.098 ThaliTest[1312:2971502] multipeer session: reset timer
2016-03-18 15:51:46.098 ThaliTest[1312:2971502] server: disconnecting to refresh session (FB7229AA-4713-4BED-BA62-4F08FAA3D947)
2016-03-18 15:51:46.098 ThaliTest[1312:2971502] server: rejecting invitation from FB7229AA-4713-4BED-BA62-4F08FAA3D947 due to previous generation (5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:5 != 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4)
,2016-03-18 15:51:46.724 ThaliTest[1312:2972290] jxcore: connect FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
2016-03-18 15:51:46.725 ThaliTest[1312:2972290] client: server will connect
2016-03-18 15:51:46.726 ThaliTest[1312:2972290] client session: reverseConnect
2016-03-18 15:51:46.726 ThaliTest[1312:2972290] client session: stateChange:0->1 FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 15:51:46.807 ThaliTest[1312:2972794] client session: not connected FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 15:51:46.808 ThaliTest[1312:2972794] client session: onLinkFailure: FB7229AA-4713-4BED-BA62-4F08FAA3D947
,2016-03-18 15:51:46.808 ThaliTest[1312:2972794] client session: disconnect
,2016-03-18 15:51:46.809 ThaliTest[1312:2972794] client session: stateChange:1->0 FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 15:51:46.811 ThaliTest[1312:2972794] client session: no connect callback (server initiated)
,2016-03-18 15:51:49.760 ThaliTest[1312:2971502] multipeer session: reset timer
2016-03-18 15:51:49.760 ThaliTest[1312:2971502] server: disconnecting to refresh session (FB7229AA-4713-4BED-BA62-4F08FAA3D947)
2016-03-18 15:51:49.760 ThaliTest[1312:2971502], server: rejecting invitation from FB7229AA-4713-4BED-BA62-4F08FAA3D947 due to previous generation (5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:5 != 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4)
,2016-03-18 15:51:53.428 ThaliTest[1312:2971502] multipeer session: reset timer
2016-03-18 15:51:53.428 ThaliTest[1312:2971502] server: disconnecting to refresh session (FB7229AA-4713-4BED-BA62-4F08FAA3D947)
2016-03-18 15:51:53.428 ThaliTest[1312:2971502] server: rejecting invitation from FB7229AA-4713-4BED-BA62-4F08FAA3D947 due to previous generation (5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:5 != 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4)
,2016-03-18 15:51:56.726 ThaliTest[1312:2971502] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative Scheduling a connect retry - retries left: 7
,2016-03-18 15:51:58.671 ThaliTest[1312:2971502] multipeer manager: restart client
,2016-03-18 15:51:58.684 ThaliTest[1312:2971502] client: found existing peer: FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 15:51:59.737 ThaliTest[1312:2972290] jxcore: connect FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
2016-03-18 15:51:59.738 ThaliTest[1312:2972290] client: server will connect
2016-03-18 15:51:59.739 ThaliTest[1312:2972290] client session: reverseConnect
2016-03-18 15:51:59.739 ThaliTest[1312:2972290] client session: stateChange:0->1 FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 15:51:59.928 ThaliTest[1312:2972815] client session: not connected FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
2016-03-18 15:51:59.928 ThaliTest[1312:2972815] client session: onLinkFailure: FB7229AA-4713-4BED-BA62-4F08FAA3D947
2016-03-18 15:51:59.9,28 ThaliTest[1312:2972815] client session: disconnect
2016-03-18 15:51:59.928 ThaliTest[1312:2972815] client session: stateChange:1->0 FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
2016-03-18 15:51:59.929 ThaliTest[1312:2972815] client session: no connect callback (server initiated)
,2016-03-18 15:52:09.740 ThaliTest[1312:2971502] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative Scheduling a connect retry - retries left: 6
,2016-03-18 15:52:12.744 ThaliTest[1312:2972290] jxcore: connect FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
2016-03-18 15:52:12.745 ThaliTest[1312:2972290] client: server will connect
2016-03-18 15:52:12.745 ThaliTest[1312:2972290] client session: reverseConn,ect
2016-03-18 15:52:12.746 ThaliTest[1312:2972290] client session: stateChange:0->1 FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 15:52:13.278 ThaliTest[1312:2972972] client session: not connected FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
2016-03-18 15:52:13.279 ThaliTest[1312:2972972] client session: onLinkFailure: FB7229AA-4713-4BED-BA62-4F08FAA3D947
2016-03-18 15:52:13.2,79 ThaliTest[1312:2972972] client session: disconnect
2016-03-18 15:52:13.279 ThaliTest[1312:2972972] client session: stateChange:1->0 FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
2016-03-18 15:52:13.279 ThaliTest[1312:2972972] client session: no connect callback (server initiated)
,2016-03-18 15:52:18.671 ThaliTest[1312:2971502] multipeer manager: restart client
,2016-03-18 15:52:18.684 ThaliTest[1312:2971502] client: found existing peer: FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 15:52:22.746 ThaliTest[1312:2971502] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative Scheduling a connect retry - retries left: 5
,2016-03-18 15:52:25.761 ThaliTest[1312:2972290] jxcore: connect FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
2016-03-18 15:52:25.761 ThaliTest[1312:2972290] client: server will connect
2016-03-18 15:52:25.762 ThaliTest[1312:2972290] client session: reverseConn,ect
2016-03-18 15:52:25.762 ThaliTest[1312:2972290] client session: stateChange:0->1 FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 15:52:26.396 ThaliTest[1312:2973018] client session: not connected FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
2016-03-18 15:52:26.397 ThaliTest[1312:2973018] client session: onLinkFailure: FB7229AA-4713-4BED-BA62-4F08FAA3D947
2016-03-18 15:52:26.3,97 ThaliTest[1312:2973018] client session: disconnect
2016-03-18 15:52:26.397 ThaliTest[1312:2973018] client session: stateChange:1->0 FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
2016-03-18 15:52:26.398 ThaliTest[1312:2973018] client session: no connect callb,ack (server initiated)
,2016-03-18 15:52:35.763 ThaliTest[1312:2971502] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative Scheduling a connect retry - retries left: 4
,2016-03-18 15:52:38.671 ThaliTest[1312:2971502] multipeer manager: restart client
,2016-03-18 15:52:38.684 ThaliTest[1312:2971502] client: found existing peer: FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 15:52:38.769 ThaliTest[1312:2972290] jxcore: connect FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
2016-03-18 15:52:38.770 ThaliTest[1312:2972290] client: server will connect
2016-03-18 15:52:38.771 ThaliTest[1312:2972290] client session: reverseConnect
2016-03-18 15:52:38.771 ThaliTest[1312:2972290] client session: stateChange:0->1 FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 15:52:39.631 ThaliTest[1312:2973051] client session: not connected FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
2016-03-18 15:52:39.631 ThaliTest[1312:2973051] client session: onLinkFailure: FB7229AA-4713-4BED-BA62-4F08FAA3D947
2016-03-18 15:52:39.632 ThaliTest[1312:2973051] client session: disconnect
2016-03-18 15:52:39.632 ThaliTest[1312:2973051] client session: stateChange:1->0 FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 15:52:39.634 ThaliTest[1312:2973051] client session: no connect callback (server initiated)
,2016-03-18 15:52:48.772 ThaliTest[1312:2971502] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative Scheduling a connect retry - retries left: 3
,2016-03-18 15:52:51.779 ThaliTest[1312:2972290] jxcore: connect FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
2016-03-18 15:52:51.780 ThaliTest[1312:2972290] client: server will connect
2016-03-18 15:52:51.780 ThaliTest[1312:2972290] client session: reverseConn,ect
2016-03-18 15:52:51.781 ThaliTest[1312:2972290] client session: stateChange:0->1 FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 15:52:52.208 ThaliTest[1312:2973081] client session: not connected FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
2016-03-18 15:52:52.209 ThaliTest[1312:2973081] client session: onLinkFailure: FB7229AA-4713-4BED-BA62-4F08FAA3D947
2016-03-18 15:52:52.2,09 ThaliTest[1312:2973081] client session: disconnect
2016-03-18 15:52:52.209 ThaliTest[1312:2973081] client session: stateChange:1->0 FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 15:52:52.211 ThaliTest[1312:2973081] client session: no connect callback (server initiated)
,2016-03-18 15:52:58.671 ThaliTest[1312:2971502] multipeer manager: restart client
,2016-03-18 15:52:58.684 ThaliTest[1312:2971502] client: found existing peer: FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 15:53:01.782 ThaliTest[1312:2971502] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative Scheduling a connect retry - retries left: 2
,2016-03-18 15:53:04.790 ThaliTest[1312:2972290] jxcore: connect FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
2016-03-18 15:53:04.791 ThaliTest[1312:2972290] client: server will connect
2016-03-18 15:53:04.791 ThaliTest[1312:2972290] client session: reverseConnect
2016-03-18 15:53:04.792 ThaliTest[1312:2972290] client session: stateChange:0->1 FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 15:53:05.380 ThaliTest[1312:2973051] client session: not connected FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
2016-03-18 15:53:05.381 ThaliTest[1312:2973051] client session: onLinkFailure: FB7229AA-4713-4BED-BA62-4F08FAA3D947
2016-03-18 15:53:05.3,81 ThaliTest[1312:2973051] client session: disconnect
2016-03-18 15:53:05.381 ThaliTest[1312:2973051] client session: stateChange:1->0 FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
2016-03-18 15:53:05.381 ThaliTest[1312:2973051] client session: no connect callb,ack (server initiated)
,2016-03-18 15:53:14.793 ThaliTest[1312:2971502] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative Scheduling a connect retry - retries left: 1
,2016-03-18 15:53:17.803 ThaliTest[1312:2972290] jxcore: connect FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
2016-03-18 15:53:17.803 ThaliTest[1312:2972290] client: server will connect
2016-03-18 15:53:17.804 ThaliTest[1312:2972290] client session: reverseConnect
2016-03-18 15:53:17.804 ThaliTest[1312:2972290] client session: stateChange:0->1 FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 15:53:18.606 ThaliTest[1312:2973128] client session: not connected FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
2016-03-18 15:53:18.606 ThaliTest[1312:2973128] client session: onLinkFailure: FB7229AA-4713-4BED-BA62-4F08FAA3D947
2016-03-18 15:53:18.6,06 ThaliTest[1312:2973128] client session: disconnect
2016-03-18 15:53:18.606 ThaliTest[1312:2973128] client session: stateChange:1->0 FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 15:53:18.608 ThaliTest[1312:2973128] client session: no connect callback (server initiated)
,2016-03-18 15:53:18.671 ThaliTest[1312:2971502] multipeer manager: restart client
,2016-03-18 15:53:18.685 ThaliTest[1312:2971502] client: found existing peer: FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 15:53:27.805 ThaliTest[1312:2971502] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative Connect returned an error: Timed out awaiting reverse connection
,WARN testThaliMobileNative Too many connect retries!
,2016-03-18 15:53:38.671 ThaliTest[1312:2971502] multipeer manager: restart client
,2016-03-18 15:53:58.671 ThaliTest[1312:2971502] multipeer manager: restart client
,2016-03-18 15:53:58.681 ThaliTest[1312:2971502] client: found existing peer: FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 15:54:18.670 ThaliTest[1312:2971502] multipeer manager: restart client
,2016-03-18 15:54:18.680 ThaliTest[1312:2971502] client: found existing peer: FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 15:54:38.671 ThaliTest[1312:2971502] multipeer manager: restart client
,2016-03-18 15:54:58.671 ThaliTest[1312:2971502] multipeer manager: restart client
,2016-03-18 15:54:58.681 ThaliTest[1312:2971502] client: found existing peer: FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 15:55:18.671 ThaliTest[1312:2971502] multipeer manager: restart client
,2016-03-18 15:55:18.681 ThaliTest[1312:2971502] client: found existing peer: FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 15:55:38.671 ThaliTest[1312:2971502] multipeer manager: restart client
,2016-03-18 15:55:38.680 ThaliTest[1312:2971502] client: found existing peer: FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 15:55:58.671 ThaliTest[1312:2971502] multipeer manager: restart client
,2016-03-18 15:55:58.681 ThaliTest[1312:2971502] client: found existing peer: FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 15:56:18.671 ThaliTest[1312:2971502] multipeer manager: restart client
,2016-03-18 15:56:18.681 ThaliTest[1312:2971502] client: found existing peer: FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 15:56:38.671 ThaliTest[1312:2971502] multipeer manager: restart client
,2016-03-18 15:56:38.680 ThaliTest[1312:2971502] client: found existing peer: FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 15:56:58.671 ThaliTest[1312:2971502] multipeer manager: restart client
,2016-03-18 15:56:58.681 ThaliTest[1312:2971502] client: found existing peer: FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 15:57:18.671 ThaliTest[1312:2971502] multipeer manager: restart client
,2016-03-18 15:57:18.680 ThaliTest[1312:2971502] client: found existing peer: FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 15:57:38.671 ThaliTest[1312:2971502] multipeer manager: restart client
,2016-03-18 15:57:38.680 ThaliTest[1312:2971502] client: found existing peer: FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 15:57:58.670 ThaliTest[1312:2971502] multipeer manager: restart client
,2016-03-18 15:57:58.680 ThaliTest[1312:2971502] client: found existing peer: FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 15:58:18.671 ThaliTest[1312:2971502] multipeer manager: restart client
,2016-03-18 15:58:18.682 ThaliTest[1312:2971502] client: found existing peer: FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 15:58:38.671 ThaliTest[1312:2971502] multipeer manager: restart client
,2016-03-18 15:58:38.681 ThaliTest[1312:2971502] client: found existing peer: FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 15:58:58.671 ThaliTest[1312:2971502] multipeer manager: restart client
,2016-03-18 15:58:58.681 ThaliTest[1312:2971502] client: found existing peer: FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 15:59:18.671 ThaliTest[1312:2971502] multipeer manager: restart client
,2016-03-18 15:59:18.681 ThaliTest[1312:2971502] client: found existing peer: FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 15:59:38.671 ThaliTest[1312:2971502] multipeer manager: restart client
,2016-03-18 15:59:38.681 ThaliTest[1312:2971502] client: found existing peer: FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 15:59:58.671 ThaliTest[1312:2971502] multipeer manager: restart client
,2016-03-18 15:59:58.680 ThaliTest[1312:2971502] client: found existing peer: FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 16:00:18.670 ThaliTest[1312:2971502] multipeer manager: restart client
,2016-03-18 16:00:18.680 ThaliTest[1312:2971502] client: found existing peer: FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 16:00:38.671 ThaliTest[1312:2971502] multipeer manager: restart client
,2016-03-18 16:00:38.681 ThaliTest[1312:2971502] client: found existing peer: FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 16:00:58.671 ThaliTest[1312:2971502] multipeer manager: restart client
,2016-03-18 16:00:58.680 ThaliTest[1312:2971502] client: found existing peer: FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 16:01:18.671 ThaliTest[1312:2971502] multipeer manager: restart client
,2016-03-18 16:01:18.680 ThaliTest[1312:2971502] client: found existing peer: FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 16:01:38.671 ThaliTest[1312:2971502] multipeer manager: restart client
,2016-03-18 16:01:38.681 ThaliTest[1312:2971502] client: found existing peer: FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 16:01:58.671 ThaliTest[1312:2971502] multipeer manager: restart client
,2016-03-18 16:01:58.680 ThaliTest[1312:2971502] client: found existing peer: FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 16:02:18.671 ThaliTest[1312:2971502] multipeer manager: restart client
,2016-03-18 16:02:18.681 ThaliTest[1312:2971502] client: found existing peer: FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 16:02:38.671 ThaliTest[1312:2971502] multipeer manager: restart client
,2016-03-18 16:02:38.681 ThaliTest[1312:2971502] client: found existing peer: FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 16:02:58.671 ThaliTest[1312:2971502] multipeer manager: restart client
,2016-03-18 16:02:58.680 ThaliTest[1312:2971502] client: found existing peer: FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 16:03:18.671 ThaliTest[1312:2971502] multipeer manager: restart client
,2016-03-18 16:03:18.680 ThaliTest[1312:2971502] client: found existing peer: FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 16:03:38.671 ThaliTest[1312:2971502] multipeer manager: restart client
,2016-03-18 16:03:38.681 ThaliTest[1312:2971502] client: found existing peer: FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 16:03:58.671 ThaliTest[1312:2971502] multipeer manager: restart client
,2016-03-18 16:03:58.681 ThaliTest[1312:2971502] client: found existing peer: FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 16:04:18.671 ThaliTest[1312:2971502] multipeer manager: restart client
,2016-03-18 16:04:18.681 ThaliTest[1312:2971502] client: found existing peer: FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 16:04:38.671 ThaliTest[1312:2971502] multipeer manager: restart client
,2016-03-18 16:04:38.681 ThaliTest[1312:2971502] client: found existing peer: FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 16:04:58.671 ThaliTest[1312:2971502] multipeer manager: restart client
,2016-03-18 16:04:58.680 ThaliTest[1312:2971502] client: found existing peer: FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 16:05:18.671 ThaliTest[1312:2971502] multipeer manager: restart client
,2016-03-18 16:05:18.681 ThaliTest[1312:2971502] client: found existing peer: FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 16:05:38.671 ThaliTest[1312:2971502] multipeer manager: restart client
,2016-03-18 16:05:38.681 ThaliTest[1312:2971502] client: found existing peer: FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 16:05:58.671 ThaliTest[1312:2971502] multipeer manager: restart client
,2016-03-18 16:05:58.681 ThaliTest[1312:2971502] client: found existing peer: FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 16:06:18.671 ThaliTest[1312:2971502] multipeer manager: restart client
,2016-03-18 16:06:18.680 ThaliTest[1312:2971502] client: found existing peer: FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 16:06:38.671 ThaliTest[1312:2971502] multipeer manager: restart client
,2016-03-18 16:06:38.681 ThaliTest[1312:2971502] client: found existing peer: FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 16:06:58.671 ThaliTest[1312:2971502] multipeer manager: restart client
,2016-03-18 16:06:58.680 ThaliTest[1312:2971502] client: found existing peer: FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 16:07:18.671 ThaliTest[1312:2971502] multipeer manager: restart client
,2016-03-18 16:07:18.680 ThaliTest[1312:2971502] client: found existing peer: FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 16:07:38.671 ThaliTest[1312:2971502] multipeer manager: restart client
,2016-03-18 16:07:38.682 ThaliTest[1312:2971502] client: found existing peer: FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 16:07:58.671 ThaliTest[1312:2971502] multipeer manager: restart client
,2016-03-18 16:07:58.682 ThaliTest[1312:2971502] client: found existing peer: FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 16:08:18.671 ThaliTest[1312:2971502] multipeer manager: restart client
,2016-03-18 16:08:18.680 ThaliTest[1312:2971502] client: found existing peer: FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 16:08:38.671 ThaliTest[1312:2971502] multipeer manager: restart client
,2016-03-18 16:08:38.681 ThaliTest[1312:2971502] client: found existing peer: FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 16:08:58.671 ThaliTest[1312:2971502] multipeer manager: restart client
,2016-03-18 16:08:58.680 ThaliTest[1312:2971502] client: found existing peer: FB7229AA-4713-4BED-BA62-4F08FAA3D947:5

```
