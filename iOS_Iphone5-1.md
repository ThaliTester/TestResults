#### Test 625090941eef958_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/625090941eef958/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/4483BFCD-DD15-4B0A-8B1C-6B4F9DA84A35/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/4483BFCD-DD15-4B0A-8B1C-6B4F9DA84A35/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/625090941eef958/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/625090941eef958/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/637CB072-4624-438F-B997-8555E95937CB/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51162"
,(lldb)     command script import "/tmp/4483BFCD-DD15-4B0A-8B1C-6B4F9DA84A35/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-17 08:32:40.889 ThaliTest[1239:2769183] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4294B8CF-78EE-4753-997F-4BE53EAAB460/Library/Cookies/Cookies.binarycookies
,2016-03-17 08:32:41.000 ThaliTest[1239:2769183] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-17 08:32:41.002 ThaliTest[1239:2769183] Multi-tasking -> Device: YES, App: YES
,2016-03-17 08:32:41.021 ThaliTest[1239:2769183] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-17 08:32:43.005 ThaliTest[1239:2769183] Using UIWebView
,2016-03-17 08:32:43.010 ThaliTest[1239:2769183] [CDVTimer][handleopenurl] 0.326991ms
,2016-03-17 08:32:43.016 ThaliTest[1239:2769183] [CDVTimer][intentandnavigationfilter] 5.258024ms
2016-03-17 08:32:43.016 ThaliTest[1239:2769183] [CDVTimer][gesturehandler] 0.259995ms
2016-03-17 08:32:43.016 ThaliTest[1239:2769183] [CDVTimer][TotalPluginStartup] 6.900966ms
,2016-03-17 08:32:51.477 ThaliTest[1239:2769183] Resetting plugins due to page load.
,2016-03-17 08:32:55.566 ThaliTest[1239:2769183] Finished load of: file:///var/mobile/Containers/Bundle/Application/637CB072-4624-438F-B997-8555E95937CB/ThaliTest.app/www/index.html
,2016-03-17 08:32:55.768 ThaliTest[1239:2769183] JXcore Cordova plugin initializing
,2016-03-17 08:32:55.770 ThaliTest[1239:2769369] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-17 08:33:05.502 ThaliTest[1239:2769369] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-17 08:33:05.503 ThaliTest[1239:2769369] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-17 08:33:05.504 ThaliTest[1239:2769369] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-17 08:33:05.510 ThaliTest[1239:2769369] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/637CB072-4624-438F-B997-8555E95937CB/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/637CB072-4624-438F-B997-8555E95937CB/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/637CB072-4624-438F-B997-8555E95937CB/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/637CB072-4624-438F-B997-8555E95937CB/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/637CB072-4624-438F-B997-8555E95937CB/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/637CB072-4624-438F-B997-8555E95937CB/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/637CB072-4624-438F-B997-8555E95937CB/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/637CB072-4624-438F-B997-8555E95937CB/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/637CB072-4624-438F-B997-8555E95937CB/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/637CB072-4624-438F-B997-8555E95937CB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/637CB072-4624-438F-B997-8555E95937CB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/637CB072-4624-438F-B997-8555E95937CB/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/637CB072-4624-438F-B997-8555E95937CB/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/637CB072-4624-438F-B997-8555E95937CB/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/637CB072-4624-438F-B997-8555E95937CB/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/637CB072-4624-438F-B997-8555E95937CB/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/637CB072-4624-438F-B997-8555E95937CB/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/637CB072-4624-438F-B997-8555E95937CB/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/637CB072-4624-438F-B997-8555E95937CB/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-17 08:33:25.380 ThaliTest[1239:2769183] THREAD WARNING: ['JXcore'] took '14370.150879' ms. Plugin should use a background thread.
,2016-03-17 08:33:25.381 ThaliTest[1239:2769325] void SendDelegateMessage(NSInvocation *): delegate (webView:decidePolicyForNavigationAction:request:frame:decisionListener:) failed to return after waiting 10 seconds. main run loop mode: kCFRunLoopDefaultMode
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
ok 81 error should be null
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
,2016-03-17 08:40:05.724 ThaliTest[1239:2769369] jxcore: startListeningForAdvertisements
,2016-03-17 08:40:05.726 ThaliTest[1239:2769369] multipeer manager: start client restart timer: 0x16e8ed40
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-17 08:40:05.728 ThaliTest[1239:2769369] jxcore: startListeningForAdvertisements: success
,ok 129 Can call startListeningForAdvertisements without error
,2016-03-17 08:40:05.730 ThaliTest[1239:2769369] jxcore: stopListeningForAdvertisements
2016-03-17 08:40:05.731 ThaliTest[1239:2769369] multipeer manager: stop client timer
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-17 08:40:05.732 ThaliTest[1239:2769369] jxcore: stopListeningForAdvertisements: success
ok 130 Can call stopListeningForAdvertisements without error
# setup
,2016-03-17 08:40:06.176 ThaliTest[1239:2769369] jxcore: stopListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-17 08:40:06.177 ThaliTest[1239:2769369] jxcore: stopListeningForAdvertisements: success
,ok 131 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-17 08:40:06.179 ThaliTest[1239:2769369] jxcore: stopAdvertisingAndListening
2016-03-17 08:40:06.179 ThaliTest[1239:2769369] THEMultipeerManager stopping peer
2016-03-17 08:40:06.179 ThaliTest[1239:2769369] jxcore: stopAdvertisingAndListening: suc,cess
ok 132 Should be able to call stopAdvertisingAndListening in teardown
,# 33. Calling startListeningForAdvertisements twice is NOT an error
,# teardown
,2016-03-17 08:40:06.652 ThaliTest[1239:2769369] jxcore: startListeningForAdvertisements
2016-03-17 08:40:06.652 ThaliTest[1239:2769369] multipeer manager: start client restart timer: 0x16e8ed40
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdat,eNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-17 08:40:06.653 ThaliTest[1239:2769369] jxcore: startListeningForAdvertisements: success
ok 133 Can call startListeningForAdvertisements without error
,2016-03-17 08:40:06.655 ThaliTest[1239:2769369] jxcore: startListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-17 08:40:06.656 ThaliTest[1239:2769369] jxcore: startListeningForAdvertisements: success
,ok 134 Can call startListeningForAdvertisements twice without error
# setup
,2016-03-17 08:40:07.046 ThaliTest[1239:2769369] jxcore: stopListeningForAdvertisements
2016-03-17 08:40:07.047 ThaliTest[1239:2769369] multipeer manager: stop client timer
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertising,Active":false,"discoveryActive":false}
2016-03-17 08:40:07.048 ThaliTest[1239:2769369] jxcore: stopListeningForAdvertisements: success
,ok 135 Should be able to call stopListeningForAdvertisments in teardown
2016-03-17 08:40:07.050 ThaliTest[1239:2769369] jxcore: stopAdvertisingAndListening
2016-03-17 08:40:07.050 ThaliTest[1239:2769369] THEMultipeerManager stopping peer
2016-03-17 08:40:07.051 ThaliTest[1239:2769369] jxcore: stopAdvertisingAndListening: success
ok 136 Should be able to call stopAdvertisingAndListening in teardown
,# 34. Can call start/stopUpdateAdvertisingAndListening
,# teardown
,2016-03-17 08:40:07.274 ThaliTest[1239:2769369] jxcore: startUpdateAdvertisingAndListening
2016-03-17 08:40:07.275 ThaliTest[1239:2769369] server: starting B834405C-4BB1-4DDE-BBBE-95797DDD18CB:1
2016-03-17 08:40:07.276 ThaliTest[1239:2769369] multipeer m,anager: start client restart timer: 0x16e8ed40
2016-03-17 08:40:07.276 ThaliTest[1239:2769369] THEMultipeerManager initialized peer B834405C-4BB1-4DDE-BBBE-95797DDD18CB:1
2016-03-17 08:40:07.276 ThaliTest[1239:2769369] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 137 Can call startUpdateAdvertisingAndListening without error
2016-03-17 08:40:07.278 ThaliTest[1239:2769369] jxcore: stopAdvertisingAndListening
2016-03-17 08:40:07.278 ThaliTest[1239:2769369] THEMultipeerManager stopping peer
2016,-03-17 08:40:07.278 ThaliTest[1239:2769369] multipeer manager: stop client timer
2016-03-17 08:40:07.279 ThaliTest[1239:2769369] jxcore: stopAdvertisingAndListening: success
,ok 138 Can call stopAdvertisingAndListening without error
,# setup
,2016-03-17 08:40:07.680 ThaliTest[1239:2769369] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-17 08:40:07.681 ThaliTest[1239:2769369] jxcore: stopListeningForAdvertisements: success
,ok 139 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-17 08:40:07.683 ThaliTest[1239:2769369] jxcore: stopAdvertisingAndListening
2016-03-17 08:40:07.683 ThaliTest[1239:2769369] THEMultipeerManager stopping peer
2016-03-17 08:40:07.683 ThaliTest[1239:2769369] jxcore: stopAdvertisingAndListening: success
ok 140 Should be able to call stopAdvertisingAndListening in teardown
,# 35. Calling startUpdateAdvertisingAndListening twice is NOT an error
,# teardown
,2016-03-17 08:40:08.270 ThaliTest[1239:2769369] jxcore: startUpdateAdvertisingAndListening
2016-03-17 08:40:08.270 ThaliTest[1239:2769369] server: starting B834405C-4BB1-4DDE-BBBE-95797DDD18CB:2
2016-03-17 08:40:08.271 ThaliTest[1239:2769369] multipeer m,anager: start client restart timer: 0x16e8ed40
2016-03-17 08:40:08.271 ThaliTest[1239:2769369] THEMultipeerManager initialized peer B834405C-4BB1-4DDE-BBBE-95797DDD18CB:2
2016-03-17 08:40:08.271 ThaliTest[1239:2769369] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 141 Can call startUpdateAdvertisingAndListening without error
2016-03-17 08:40:08.272 ThaliTest[1239:2769369] jxcore: startUpdateAdvertisingAndListening
2016-03-17 08:40:08.273 ThaliTest[1239:2769369] THEMultipeerManager stopping pee,r
2016-03-17 08:40:08.273 ThaliTest[1239:2769369] multipeer manager: stop client timer
,2016-03-17 08:40:08.273 ThaliTest[1239:2769369] server: starting B834405C-4BB1-4DDE-BBBE-95797DDD18CB:3
2016-03-17 08:40:08.274 ThaliTest[1239:2769369] multipeer manager: start client restart timer: 0x16e8ed40
2016-03-17 08:40:08.274 ThaliTest[1239:27693,69] THEMultipeerManager initialized peer B834405C-4BB1-4DDE-BBBE-95797DDD18CB:3
2016-03-17 08:40:08.274 ThaliTest[1239:2769369] jxcore: startUpdateAdvertisingAndListening: success
,ok 142 Can call startUpdateAdvertisingAndListening twice without error
# setup
,2016-03-17 08:40:08.556 ThaliTest[1239:2769369] jxcore: stopListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-17 08:40:08.557 ThaliTest[1239:2769369] jxcore: stopListeningForAdvertisements: success
ok 143 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-17 08:40:08.559 ThaliTest[1239:2769369] jxcore: stopAdvertisingAndListening
2016-03-17 08:40:08.559 ThaliTest[1239:2769369] THEMultipeerManager stopping peer
2016-03-17 08:40:08.559 ThaliTest[1239:2769369] multipeer manager: stop client timer
20,16-03-17 08:40:08.560 ThaliTest[1239:2769369] jxcore: stopAdvertisingAndListening: success
ok 144 Should be able to call stopAdvertisingAndListening in teardown
,# 36. peerAvailabilityChange is called
,# teardown
,2016-03-17 08:40:09.083 ThaliTest[1239:2769369] jxcore: startUpdateAdvertisingAndListening
2016-03-17 08:40:09.084 ThaliTest[1239:2769369] server: starting B834405C-4BB1-4DDE-BBBE-95797DDD18CB:4
2016-03-17 08:40:09.084 ThaliTest[1239:2769369] multipeer m,anager: start client restart timer: 0x16e8ed40
2016-03-17 08:40:09.084 ThaliTest[1239:2769369] THEMultipeerManager initialized peer B834405C-4BB1-4DDE-BBBE-95797DDD18CB:4
2016-03-17 08:40:09.084 ThaliTest[1239:2769369] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 145 Can call startUpdateAdvertisingAndListeningwithout error
2016-03-17 08:40:09.086 ThaliTest[1239:2769369] jxcore: startListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingAc,tive":true,"discoveryActive":true}
2016-03-17 08:40:09.087 ThaliTest[1239:2769369] jxcore: startListeningForAdvertisements: success
ok 146 Can call startListeningForAdvertisements without error
,2016-03-17 08:40:10.062 ThaliTest[1239:2769183] client: found new peer: B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:4
ok 147 peers must be an array
ok 148 peers must not be zero-length
ok 149 peer must have peerIdentifier
ok 150 peerIdentifier must be a string
,ok 151 peer must have peerAvailable
,ok 152 peer must have pleaseConnect
,# setup
,2016-03-17 08:40:10.950 ThaliTest[1239:2769369] jxcore: stopListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-17 08:40:10.951 ThaliTest[1239:2769369] jxcore: stopListeningForAdvertisements: success
,ok 153 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-17 08:40:10.952 ThaliTest[1239:2769369] jxcore: stopAdvertisingAndListening
2016-03-17 08:40:10.953 ThaliTest[1239:2769369] THEMultipeerManager stopping peer
2016-03-17 08:40:10.953 ThaliTest[1239:2769369] multipeer manager: stop client timer
20,16-03-17 08:40:10.953 ThaliTest[1239:2769369] jxcore: stopAdvertisingAndListening: success
ok 154 Should be able to call stopAdvertisingAndListening in teardown
,# 37. Can connect to a remote peer
,# teardown
,2016-03-17 08:40:11.703 ThaliTest[1239:2769369] jxcore: startUpdateAdvertisingAndListening
2016-03-17 08:40:11.703 ThaliTest[1239:2769369] server: starting B834405C-4BB1-4DDE-BBBE-95797DDD18CB:5
2016-03-17 08:40:11.703 ThaliTest[1239:2769369] multipeer m,anager: start client restart timer: 0x16e8ed40
2016-03-17 08:40:11.703 ThaliTest[1239:2769369] THEMultipeerManager initialized peer B834405C-4BB1-4DDE-BBBE-95797DDD18CB:5
2016-03-17 08:40:11.704 ThaliTest[1239:2769369] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 155 Can call startUpdateAdvertisingAndListening without error
2016-03-17 08:40:11.705 ThaliTest[1239:2769369] jxcore: startListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingA,ctive":true,"discoveryActive":true}
2016-03-17 08:40:11.706 ThaliTest[1239:2769369] jxcore: startListeningForAdvertisements: success
,ok 156 Can call startListeningForAdvertisements without error
,2016-03-17 08:40:12.547 ThaliTest[1239:2769183] client: found new peer: B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:4
,[ { peerAvailable: 1,
    peerIdentifier: 'B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:4',
    pleaseConnect: 0 } ]
,2016-03-17 08:40:12.554 ThaliTest[1239:2769369] jxcore: connect B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:4
2016-03-17 08:40:12.554 ThaliTest[1239:2769369] client session: connect
2016-03-17 08:40:12.554 ThaliTest[1239:2769369] client session: stateChange:0->1 B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:4
,2016-03-17 08:40:12.811 ThaliTest[1239:2770212] client session: not connected B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:4
2016-03-17 08:40:12.812 ThaliTest[1239:2770212] client session: onLinkFailure: B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D
2016-03-17 08:40:12.8,12 ThaliTest[1239:2770212] client session: disconnect
2016-03-17 08:40:12.812 ThaliTest[1239:2770212] client session: stateChange:1->0 B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:4
,2016-03-17 08:40:12.814 ThaliTest[1239:2770212] client session: fireConnectCallback: B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D
,2016-03-17 08:40:12.814 ThaliTest[1239:2770212] jxcore: connect: fail: Peer disconnected
,2016-03-17 08:40:15.823 ThaliTest[1239:2769369] jxcore: connect B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:4
2016-03-17 08:40:15.824 ThaliTest[1239:2769369] client session: connect
2016-03-17 08:40:15.825 ThaliTest[1239:2769369] client session: stateChange:0->1 B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:4
,2016-03-17 08:40:15.850 ThaliTest[1239:2769183] multipeer session: reset timer
2016-03-17 08:40:15.851 ThaliTest[1239:2769183] server: rejecting invitation from B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D due to previous generation (B834405C-4BB1-4DDE-BBBE-95797DDD18CB:5 != B834405C-4BB1-4DDE-BBBE-95797DDD18CB:4)
,2016-03-17 08:40:15.915 ThaliTest[1239:2770219] client session: not connected B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:4
2016-03-17 08:40:15.915 ThaliTest[1239:2770219] client session: onLinkFailure: B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D
2016-03-17 08:40:15.9,16 ThaliTest[1239:2770219] client session: disconnect
2016-03-17 08:40:15.916 ThaliTest[1239:2770219] client session: stateChange:1->0 B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:4
,2016-03-17 08:40:15.918 ThaliTest[1239:2770219] client session: fireConnectCallback: B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D
2016-03-17 08:40:15.918 ThaliTest[1239:2770219] jxcore: connect: fail: Peer disconnected
,2016-03-17 08:40:18.927 ThaliTest[1239:2769369] jxcore: connect B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:4
2016-03-17 08:40:18.928 ThaliTest[1239:2769369] client session: connect
2016-03-17 08:40:18.928 ThaliTest[1239:2769369] client session: stateChange:0->,1 B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:4
,2016-03-17 08:40:19.388 ThaliTest[1239:2770184] client session: not connected B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:4
2016-03-17 08:40:19.388 ThaliTest[1239:2770184] client session: onLinkFailure: B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D
2016-03-17 08:40:19.388 ThaliTest[1239:2770184] client session: disconnect
2016-03-17 08:40:19.389 ThaliTest[1239:2770184] client session: stateChange:1->0 B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:4
,2016-03-17 08:40:19.390 ThaliTest[1239:2770184] client session: fireConnectCallback: B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D
2016-03-17 08:40:19.390 ThaliTest[1239:2770184] jxcore: connect: fail: Peer disconnected
,2016-03-17 08:40:22.401 ThaliTest[1239:2769369] jxcore: connect B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:4
2016-03-17 08:40:22.402 ThaliTest[1239:2769369] client session: connect
2016-03-17 08:40:22.403 ThaliTest[1239:2769369] client session: stateChange:0->1 B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:4
,2016-03-17 08:40:22.597 ThaliTest[1239:2770272] client session: not connected B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:4
,2016-03-17 08:40:22.598 ThaliTest[1239:2770272] client session: onLinkFailure: B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D
2016-03-17 08:40:22.599 ThaliTest[1239:2770272] client session: disconnect
2016-03-17 08:40:22.599 ThaliTest[1239:2770272] client session:, stateChange:1->0 B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:4
2016-03-17 08:40:22.600 ThaliTest[1239:2770272] client session: fireConnectCallback: B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D
2016-03-17 08:40:22.600 ThaliTest[1239:2770272] jxcore: connect: fail: Peer disconnected
,2016-03-17 08:40:25.608 ThaliTest[1239:2769369] jxcore: connect B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:4
2016-03-17 08:40:25.609 ThaliTest[1239:2769369] client session: connect
2016-03-17 08:40:25.609 ThaliTest[1239:2769369] client session: stateChange:0->1 B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:4
,2016-03-17 08:40:25.712 ThaliTest[1239:2770183] client session: not connected B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:4
2016-03-17 08:40:25.712 ThaliTest[1239:2770183] client session: onLinkFailure: B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D
2016-03-17 08:40:25.712 ThaliTest[1239:2770183] client session: disconnect
2016-03-17 08:40:25.712 ThaliTest[1239:2770183] client session: stateChange:1->0 B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:4
,2016-03-17 08:40:25.715 ThaliTest[1239:2770183] client session: fireConnectCallback: B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D
,2016-03-17 08:40:25.715 ThaliTest[1239:2770183] jxcore: connect: fail: Peer disconnected
,2016-03-17 08:40:25.778 ThaliTest[1239:2769183] multipeer session: reset timer
2016-03-17 08:40:25.779 ThaliTest[1239:2769183] server: disconnecting to refresh session (B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D)
2016-03-17 08:40:25.779 ThaliTest[1239:2769183] server: rejecting invitation from B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D due to previous generation (B834405C-4BB1-4DDE-BBBE-95797DDD18CB:5 != B834405C-4BB1-4DDE-BBBE-95797DDD18CB:4)
,2016-03-17 08:40:28.718 ThaliTest[1239:2769369] jxcore: connect B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:4
2016-03-17 08:40:28.719 ThaliTest[1239:2769369] client session: connect
2016-03-17 08:40:28.719 ThaliTest[1239:2769369] client session: stateChange:0->1 B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:4
,2016-03-17 08:40:28.871 ThaliTest[1239:2770183] client session: not connected B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:4
2016-03-17 08:40:28.871 ThaliTest[1239:2770183] client session: onLinkFailure: B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D
2016-03-17 08:40:28.8,71 ThaliTest[1239:2770183] client session: disconnect
,2016-03-17 08:40:28.871 ThaliTest[1239:2770183] client session: stateChange:1->0 B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:4
2016-03-17 08:40:28.873 ThaliTest[1239:2770183] client session: fireConnectCallback: B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D
2016-03-17 08:40:28.873 ThaliTest[1239:2770183] jxcore: connect: fail: Peer disconnected
,2016-03-17 08:40:31.705 ThaliTest[1239:2769183] multipeer manager: restart client
,2016-03-17 08:40:31.717 ThaliTest[1239:2769183] client: found updated peer: B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
[ { peerAvailable: 1,
    peerIdentifier: 'B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5',
    pleaseConnect: 0 } ]
2016-03-17 08:40:31.720 Thal,iTest[1239:2769369] jxcore: connect B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
2016-03-17 08:40:31.721 ThaliTest[1239:2769369] client session: connect
2016-03-17 08:40:31.721 ThaliTest[1239:2769369] client session: stateChange:0->1 B3E5E16C-F6AC-48A7-AEDD-2B,3D06013F6D:5
,2016-03-17 08:40:31.880 ThaliTest[1239:2769369] jxcore: connect B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:4
2016-03-17 08:40:31.881 ThaliTest[1239:2769369] client: already connect(ing/ed) to B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:4
2016-03-17 08:40:31.881 ThaliTest[1239:2769369] jxcore: connect: fail: Aleady connecting
,2016-03-17 08:40:31.975 ThaliTest[1239:2769183] multipeer session: reset timer
2016-03-17 08:40:31.976 ThaliTest[1239:2769183] server: disconnecting to refresh session (B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D)
2016-03-17 08:40:31.976 ThaliTest[1239:2769183] server: rejecting invitation for lexical ordering B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D
,[ { peerAvailable: 1,
    peerIdentifier: 'B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5',
    pleaseConnect: 1 } ]
,2016-03-17 08:40:31.979 ThaliTest[1239:2769369] jxcore: connect B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
2016-03-17 08:40:31.981 ThaliTest[1239:2769369] client: already connect(ing/ed) to B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
2016-03-17 08:40:31.982 ThaliTest[1239:2769369] jxcore: connect: fail: Aleady connecting
,2016-03-17 08:40:33.496 ThaliTest[1239:2770183] client session: p2p link connected
,2016-03-17 08:40:33.630 ThaliTest[1239:2770184] client session: stateChange:1->2 B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
2016-03-17 08:40:33.630 ThaliTest[1239:2770184] client session: fireConnectCallback: B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D
2016-03-17 0,8:40:33.630 ThaliTest[1239:2770184] jxcore: connect: success
{ clientPort: 0, serverPort: 0, listeningPort: 63576 }
ok 157 Must have listeningPort
,ok 158 listeningPort must be a number
,ok 159 Connection must have clientPort
,ok 160 clientPort must be a number
,ok 161 Connection must have serverPort
,ok 162 serverPort must be a number
,ok 163 forward connection must have clientPort == 0
,ok 164 forward connectionmust have serverPort == 0
,# setup
,2016-03-17 08:40:34.163 ThaliTest[1239:2770219] client session: not connected B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
2016-03-17 08:40:34.164 ThaliTest[1239:2770219] client session: onLinkFailure: B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D
2016-03-17 08:40:34.1,64 ThaliTest[1239:2770219] client session: disconnect
2016-03-17 08:40:34.164 ThaliTest[1239:2770219] client session: stateChange:2->0 B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
,2016-03-17 08:40:34.453 ThaliTest[1239:2769369] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-17 08:40:34.455 ThaliTest[1239:2769369] jxcore: stopListeningForAdvertisements: success
,ok 165 Should be able to call stopListeningForAdvertisments in teardown
2016-03-17 08:40:34.456 ThaliTest[1239:2769369] jxcore: stopAdvertisingAndListening
2016-03-17 08:40:34.456 ThaliTest[1239:2769369] THEMultipeerManager stopping peer
2016-03-17 08:4,0:34.457 ThaliTest[1239:2769369] multipeer manager: stop client timer
2016-03-17 08:40:34.457 ThaliTest[1239:2769369] jxcore: stopAdvertisingAndListening: success
ok 166 Should be able to call stopAdvertisingAndListening in teardown
,# 38. Can shift large amounts of data
,# teardown
,2016-03-17 08:40:34.885 ThaliTest[1239:2769369] jxcore: connect B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:4
2016-03-17 08:40:34.886 ThaliTest[1239:2769369] jxcore: connect: fail: Start browsing first
,2016-03-17 08:40:35.033 ThaliTest[1239:2769369] jxcore: startUpdateAdvertisingAndListening
2016-03-17 08:40:35.033 ThaliTest[1239:2769369] server: starting B834405C-4BB1-4DDE-BBBE-95797DDD18CB:6
,2016-03-17 08:40:35.034 ThaliTest[1239:2769369] multipeer manager: start client restart timer: 0x16e8ed40
2016-03-17 08:40:35.035 ThaliTest[1239:2769369] THEMultipeerManager initialized peer B834405C-4BB1-4DDE-BBBE-95797DDD18CB:6
2016-03-17 08:40:35.036 ThaliTest[1239:2769369] jxcore: startUpdateAdvertisingAndListening: success
,ok 167 Can call startUpdateAdvertisingAndListening without error
2016-03-17 08:40:35.039 ThaliTest[1239:2769369] jxcore: startListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"disco,veryActive":true}
,2016-03-17 08:40:35.040 ThaliTest[1239:2769369] jxcore: startListeningForAdvertisements: success
,ok 168 Can call startListeningForAdvertisements without error
,2016-03-17 08:40:35.055 ThaliTest[1239:2769369] jxcore: connect B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
2016-03-17 08:40:35.056 ThaliTest[1239:2769369] client: unknown peer B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
2016-03-17 08:40:35.057 ThaliTest[1239:2769,369] jxcore: connect: fail: Unknown peer
,2016-03-17 08:40:35.686 ThaliTest[1239:2769183] client: found new peer: B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
,2016-03-17 08:40:35.688 ThaliTest[1239:2769369] jxcore: connect B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
2016-03-17 08:40:35.688 ThaliTest[1239:2769369] client session: connect
2016-03-17 08:40:35.689 ThaliTest[1239:2769369] client session: stateChange:0->1 B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
,2016-03-17 08:40:36.310 ThaliTest[1239:2769183] multipeer session: reset timer
2016-03-17 08:40:36.310 ThaliTest[1239:2769183] server: rejecting invitation from B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D due to previous generation (B834405C-4BB1-4DDE-BBBE-95797,DDD18CB:6 != B834405C-4BB1-4DDE-BBBE-95797DDD18CB:5)
,2016-03-17 08:40:37.360 ThaliTest[1239:2770219] client session: not connected B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
2016-03-17 08:40:37.360 ThaliTest[1239:2770219] client session: onLinkFailure: B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D
2016-03-17 08:40:37.360 ThaliTest[1239:2770219] client session: disconnect
2016-03-17 08:40:37.361 ThaliTest[1239:2770219] client session: stateChange:1->0 B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
,2016-03-17 08:40:37.362 ThaliTest[1239:2770219] client session: fireConnectCallback: B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D
2016-03-17 08:40:37.362 ThaliTest[1239:2770219] jxcore: connect: fail: Peer disconnected
,2016-03-17 08:40:37.900 ThaliTest[1239:2769369] jxcore: connect B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:4
2016-03-17 08:40:37.901 ThaliTest[1239:2769369] client session: connect
2016-03-17 08:40:37.901 ThaliTest[1239:2769369] client session: stateChange:0->,1 B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
,2016-03-17 08:40:38.040 ThaliTest[1239:2770219] client session: not connected B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
2016-03-17 08:40:38.041 ThaliTest[1239:2770219] client session: onLinkFailure: B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D
2016-03-17 08:40:38.0,42 ThaliTest[1239:2770219] client session: disconnect
2016-03-17 08:40:38.042 ThaliTest[1239:2770219] client session: stateChange:1->0 B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
,2016-03-17 08:40:38.043 ThaliTest[1239:2770219] client session: fireConnectCallback: B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D
2016-03-17 08:40:38.043 ThaliTest[1239:2770219] jxcore: connect: fail: Peer disconnected
,2016-03-17 08:40:38.070 ThaliTest[1239:2769369] jxcore: connect B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
2016-03-17 08:40:38.071 ThaliTest[1239:2769369] client session: connect
2016-03-17 08:40:38.071 ThaliTest[1239:2769369] client session: stateChange:0->,1 B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
,2016-03-17 08:40:38.200 ThaliTest[1239:2770183] client session: not connected B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
2016-03-17 08:40:38.200 ThaliTest[1239:2770183] client session: onLinkFailure: B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D
2016-03-17 08:40:38.200 ThaliTest[1239:2770183] client session: disconnect
,2016-03-17 08:40:38.200 ThaliTest[1239:2770183] client session: stateChange:1->0 B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
,2016-03-17 08:40:38.202 ThaliTest[1239:2770183] client session: fireConnectCallback: B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D
2016-03-17 08:40:38.203 ThaliTest[1239:2770183] jxcore: connect: fail: Peer disconnected
,2016-03-17 08:40:40.369 ThaliTest[1239:2769369] jxcore: connect B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
2016-03-17 08:40:40.370 ThaliTest[1239:2769369] client session: connect
2016-03-17 08:40:40.371 ThaliTest[1239:2769369] client session: stateChange:0->1 B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
,2016-03-17 08:40:40.449 ThaliTest[1239:2770184] client session: not connected B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
2016-03-17 08:40:40.451 ThaliTest[1239:2770184] client session: onLinkFailure: B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D
2016-03-17 08:40:40.4,51 ThaliTest[1239:2770184] client session: disconnect
2016-03-17 08:40:40.451 ThaliTest[1239:2770184] client session: stateChange:1->0 B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
2016-03-17 08:40:40.452 ThaliTest[1239:2770184] client session: fireConnectCallb,ack: B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D
,2016-03-17 08:40:40.452 ThaliTest[1239:2770184] jxcore: connect: fail: Peer disconnected
,2016-03-17 08:40:41.050 ThaliTest[1239:2769369] jxcore: connect B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:4
2016-03-17 08:40:41.051 ThaliTest[1239:2769369] client session: connect
2016-03-17 08:40:41.052 ThaliTest[1239:2769369] client session: stateChange:0->,1 B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
,2016-03-17 08:40:41.122 ThaliTest[1239:2770184] client session: not connected B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
2016-03-17 08:40:41.122 ThaliTest[1239:2770184] client session: onLinkFailure: B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D
2016-03-17 08:40:41.123 ThaliTest[1239:2770184] client session: disconnect
,2016-03-17 08:40:41.123 ThaliTest[1239:2770184] client session: stateChange:1->0 B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
,2016-03-17 08:40:41.125 ThaliTest[1239:2770184] client session: fireConnectCallback: B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D
2016-03-17 08:40:41.125 ThaliTest[1239:2770184] jxcore: connect: fail: Peer disconnected
,2016-03-17 08:40:41.214 ThaliTest[1239:2769369] jxcore: connect B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
2016-03-17 08:40:41.215 ThaliTest[1239:2769369] client session: connect
2016-03-17 08:40:41.215 ThaliTest[1239:2769369] client session: stateChange:0->1 B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
,2016-03-17 08:40:41.380 ThaliTest[1239:2770219] client session: not connected B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
2016-03-17 08:40:41.381 ThaliTest[1239:2770219] client session: onLinkFailure: B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D
2016-03-17 08:40:41.3,81 ThaliTest[1239:2770219] client session: disconnect
2016-03-17 08:40:41.381 ThaliTest[1239:2770219] client session: stateChange:1->0 B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
2016-03-17 08:40:41.381 ThaliTest[1239:2770219] client session: fireConnectCallb,ack: B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D
2016-03-17 08:40:41.381 ThaliTest[1239:2770219] jxcore: connect: fail: Peer disconnected
,2016-03-17 08:40:43.463 ThaliTest[1239:2769369] jxcore: connect B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
2016-03-17 08:40:43.464 ThaliTest[1239:2769369] client session: connect
2016-03-17 08:40:43.465 ThaliTest[1239:2769369] client session: stateChange:0->,1 B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
,2016-03-17 08:40:43.611 ThaliTest[1239:2770184] client session: not connected B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
2016-03-17 08:40:43.611 ThaliTest[1239:2770184] client session: onLinkFailure: B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D
2016-03-17 08:40:43.6,11 ThaliTest[1239:2770184] client session: disconnect
2016-03-17 08:40:43.611 ThaliTest[1239:2770184] client session: stateChange:1->0 B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
2016-03-17 08:40:43.612 ThaliTest[1239:2770184] client session: fireConnectCallback: B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D
,2016-03-17 08:40:43.612 ThaliTest[1239:2770184] jxcore: connect: fail: Peer disconnected
,2016-03-17 08:40:44.386 ThaliTest[1239:2769369] jxcore: connect B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
2016-03-17 08:40:44.386 ThaliTest[1239:2769369] client session: connect
2016-03-17 08:40:44.387 ThaliTest[1239:2769369] client session: stateChange:0->1 B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
,2016-03-17 08:40:44.585 ThaliTest[1239:2770183] client session: not connected B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
2016-03-17 08:40:44.587 ThaliTest[1239:2770183] client session: onLinkFailure: B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D
2016-03-17 08:40:44.5,87 ThaliTest[1239:2770183] client session: disconnect
2016-03-17 08:40:44.587 ThaliTest[1239:2770183] client session: stateChange:1->0 B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
2016-03-17 08:40:44.587 ThaliTest[1239:2770183] client session: fireConnectCallback: B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D
2016-03-17 08:40:44.588 ThaliTest[1239:2770183] jxcore: connect: fail: Peer disconnected
,2016-03-17 08:40:46.620 ThaliTest[1239:2769369] jxcore: connect B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
2016-03-17 08:40:46.621 ThaliTest[1239:2769369] client session: connect
2016-03-17 08:40:46.621 ThaliTest[1239:2769369] client session: stateChange:0->1 B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
,2016-03-17 08:40:46.744 ThaliTest[1239:2770184] client session: not connected B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
2016-03-17 08:40:46.744 ThaliTest[1239:2770184] client session: onLinkFailure: B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D
2016-03-17 08:40:46.7,46 ThaliTest[1239:2770184] client session: disconnect
2016-03-17 08:40:46.746 ThaliTest[1239:2770184] client session: stateChange:1->0 B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
2016-03-17 08:40:46.746 ThaliTest[1239:2770184] client session: fireConnectCallb,ack: B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D
,2016-03-17 08:40:46.748 ThaliTest[1239:2770184] jxcore: connect: fail: Peer disconnected
,2016-03-17 08:40:47.597 ThaliTest[1239:2769369] jxcore: connect B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
2016-03-17 08:40:47.598 ThaliTest[1239:2769369] client session: connect
2016-03-17 08:40:47.598 ThaliTest[1239:2769369] client session: stateChange:0->1 B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
,2016-03-17 08:40:47.795 ThaliTest[1239:2770184] client session: not connected B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
2016-03-17 08:40:47.795 ThaliTest[1239:2770184] client session: onLinkFailure: B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D
2016-03-17 08:40:47.7,95 ThaliTest[1239:2770184] client session: disconnect
2016-03-17 08:40:47.796 ThaliTest[1239:2770184] client session: stateChange:1->0 B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
2016-03-17 08:40:47.796 ThaliTest[1239:2770184] client session: fireConnectCallb,ack: B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D
2016-03-17 08:40:47.796 ThaliTest[1239:2770184] jxcore: connect: fail: Peer disconnected
,2016-03-17 08:40:49.628 ThaliTest[1239:2769183] multipeer session: reset timer
2016-03-17 08:40:49.628 ThaliTest[1239:2769183] server: disconnecting to refresh session (B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D)
2016-03-17 08:40:49.628 ThaliTest[1239:2769183], server: rejecting invitation from B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D due to previous generation (B834405C-4BB1-4DDE-BBBE-95797DDD18CB:6 != B834405C-4BB1-4DDE-BBBE-95797DDD18CB:5)
,2016-03-17 08:40:49.758 ThaliTest[1239:2769369] jxcore: connect B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
2016-03-17 08:40:49.758 ThaliTest[1239:2769369] client session: connect
2016-03-17 08:40:49.759 ThaliTest[1239:2769369] client session: stateChange:0->,1 B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
,2016-03-17 08:40:49.919 ThaliTest[1239:2770347] client session: not connected B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
,2016-03-17 08:40:49.919 ThaliTest[1239:2770347] client session: onLinkFailure: B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D
2016-03-17 08:40:49.920 ThaliTest[1239:2770347] client session: disconnect
2016-03-17 08:40:49.920 ThaliTest[1239:2770347] client session:, stateChange:1->0 B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
2016-03-17 08:40:49.921 ThaliTest[1239:2770347] client session: fireConnectCallback: B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D
2016-03-17 08:40:49.921 ThaliTest[1239:2770347] jxcore: connect: fail: Peer disconnected
,2016-03-17 08:40:50.803 ThaliTest[1239:2769369] jxcore: connect B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
2016-03-17 08:40:50.804 ThaliTest[1239:2769369] client session: connect
2016-03-17 08:40:50.804 ThaliTest[1239:2769369] client session: stateChange:0->1 B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
,2016-03-17 08:40:51.469 ThaliTest[1239:2770184] client session: not connected B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
2016-03-17 08:40:51.470 ThaliTest[1239:2770184] client session: onLinkFailure: B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D
,2016-03-17 08:40:51.470 ThaliTest[1239:2770184] client session: disconnect
,2016-03-17 08:40:51.471 ThaliTest[1239:2770184] client session: stateChange:1->0 B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
,2016-03-17 08:40:51.472 ThaliTest[1239:2770184] client session: fireConnectCallback: B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D
2016-03-17 08:40:51.472 ThaliTest[1239:2770184] jxcore: connect: fail: Peer disconnected
,2016-03-17 08:40:52.922 ThaliTest[1239:2769369] jxcore: connect B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
2016-03-17 08:40:52.923 ThaliTest[1239:2769369] client session: connect
2016-03-17 08:40:52.923 ThaliTest[1239:2769369] client session: stateChange:0->,1 B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
,2016-03-17 08:40:53.110 ThaliTest[1239:2770183] client session: not connected B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
2016-03-17 08:40:53.110 ThaliTest[1239:2770183] client session: onLinkFailure: B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D
2016-03-17 08:40:53.110 ThaliTest[1239:2770183] client session: disconnect
2016-03-17 08:40:53.111 ThaliTest[1239:2770183] client session: stateChange:1->0 B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
,2016-03-17 08:40:53.112 ThaliTest[1239:2770183] client session: fireConnectCallback: B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D
2016-03-17 08:40:53.113 ThaliTest[1239:2770183] jxcore: connect: fail: Peer disconnected
,2016-03-17 08:40:54.482 ThaliTest[1239:2769369] jxcore: connect B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
2016-03-17 08:40:54.483 ThaliTest[1239:2769369] client session: connect
2016-03-17 08:40:54.483 ThaliTest[1239:2769369] client session: stateChange:0->1 B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
,2016-03-17 08:40:54.552 ThaliTest[1239:2770347] client session: not connected B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
2016-03-17 08:40:54.553 ThaliTest[1239:2770347] client session: onLinkFailure: B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D
2016-03-17 08:40:54.5,53 ThaliTest[1239:2770347] client session: disconnect
2016-03-17 08:40:54.553 ThaliTest[1239:2770347] client session: stateChange:1->0 B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
2016-03-17 08:40:54.554 ThaliTest[1239:2770347] client session: fireConnectCallb,ack: B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D
2016-03-17 08:40:54.554 ThaliTest[1239:2770347] jxcore: connect: fail: Peer disconnected
,2016-03-17 08:40:55.036 ThaliTest[1239:2769183] multipeer manager: restart client
,2016-03-17 08:40:55.051 ThaliTest[1239:2769183] client: found updated peer: B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:6
2016-03-17 08:40:55.052 ThaliTest[1239:2769369] jxcore: connect B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:6
2016-03-17 08:40:55.053 ThaliTest[12,39:2769369] client session: connect
2016-03-17 08:40:55.054 ThaliTest[1239:2769369] client session: stateChange:0->1 B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:6
,2016-03-17 08:40:56.120 ThaliTest[1239:2769369] jxcore: connect B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
2016-03-17 08:40:56.121 ThaliTest[1239:2769369] client: already connect(ing/ed) to B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
2016-03-17 08:40:56.121 ThaliTest[1239:2769369] jxcore: connect: fail: Aleady connecting
,2016-03-17 08:40:57.565 ThaliTest[1239:2769369] jxcore: connect B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
2016-03-17 08:40:57.566 ThaliTest[1239:2769369] client: already connect(ing/ed) to B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
2016-03-17 08:40:57.566 Thali,Test[1239:2769369] jxcore: connect: fail: Aleady connecting
,2016-03-17 08:40:57.736 ThaliTest[1239:2770272] client session: p2p link connected
2016-03-17 08:40:57.740 ThaliTest[1239:2770272] client session: stateChange:1->2 B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:6
2016-03-17 08:40:57.740 ThaliTest[1239:2770272] cli,ent session: fireConnectCallback: B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D
2016-03-17 08:40:57.741 ThaliTest[1239:2770272] jxcore: connect: success
{ clientPort: 0, serverPort: 0, listeningPort: 63597 }
Forward connection
,2016-03-17 08:40:57.745 ThaliTest[1239:2769183] client: relay established
2016-03-17 08:40:57.746 ThaliTest[1239:2769183] client: new accepted socket: 0x1cdba8a0
,forwardSend
,forwardData
,forwardData
,ok 169 received should match sent forward
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
,forwardData
,forwardData
,forwardData
,forwardData
,forwardData
,forwardData
,forwardData
,forwardData
,2016-03-17 08:40:59.127 ThaliTest[1239:2769369] jxcore: connect B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
2016-03-17 08:40:59.128 ThaliTest[1239:2769369] client: already connect(ing/ed) to B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
2016-03-17 08:40:59.129 Thali,Test[1239:2769369] jxcore: connect: fail: Aleady connecting
,2016-03-17 08:40:59.133 ThaliTest[1239:2769369] jxcore: stopListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-17 08:40:59.134 ThaliTest[1239:2769369] jxcore: stopListeningForAdvertisements: success
,ok 170 Should be able to call stopListeningForAdvertisments in teardown
2016-03-17 08:40:59.136 ThaliTest[1239:2769369] jxcore: stopAdvertisingAndListening
2016-03-17 08:40:59.136 ThaliTest[1239:2769369] THEMultipeerManager stopping peer
2016-03-17 08:4,0:59.136 ThaliTest[1239:2769369] client session: disconnect
2016-03-17 08:40:59.136 ThaliTest[1239:2769369] client session: stateChange:2->0 B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:6
,2016-03-17 08:40:59.171 ThaliTest[1239:2769369] multipeer manager: stop client timer
2016-03-17 08:40:59.171 ThaliTest[1239:2769369] jxcore: stopAdvertisingAndListening: success
ok 171 Should be able to call stopAdvertisingAndListening in teardown
# 39. can get the network status before starting
,# teardown
,2016-03-17 08:41:00.583 ThaliTest[1239:2769369] jxcore: connect B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
2016-03-17 08:41:00.583 ThaliTest[1239:2769369] jxcore: connect: fail: Start browsing first
,ok 172 network status should have certain non-empty properties
,# setup
,# 40. #generatePreambleAndBeacons bad args
,# teardown
,ok 173 publicKeysToNotify cannot be null
,ok 174 ecdh for local device cannot be null
,ok 175 milliseconds cannot be less than 0
,ok 176 milliseconds cannot be 0
,ok 177 milliseconds cannot be greater than one_day
,# setup
,2016-03-17 08:41:02.134 ThaliTest[1239:2769369] jxcore: connect B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
2016-03-17 08:41:02.134 ThaliTest[1239:2769369] jxcore: connect: fail: Start browsing first
,# 41. #generatePreambleAndBeacons empty keys to notify
,# teardown
,2016-03-17 08:41:05.142 ThaliTest[1239:2769369] jxcore: connect B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
2016-03-17 08:41:05.143 ThaliTest[1239:2769369] jxcore: connect: fail: Start browsing first
,ok 178 should be equal
,# setup
,# 42. #generatePreambleAndBeacons multiple keys to notify
,# teardown
,ok 179 should be equal
,ok 180 should be equal
,ok 181 (unnamed assert)
,ok 182 should be equal
,# setup
,# 43. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
,# teardown
,ok 183 should throw
,# setup
,# 44. #parseBeacons invalid expiration in beaconStreamWithPreAmble
,# teardown
,ok 184 Preamble expiration must be a 64 bit integer
,# setup
,# 45. #parseBeacons expiration out of range lower
,# teardown
,ok 185 Expiration out of range
,# setup
,# 46. #parseBeacons expiration out of range lower
,# teardown
,ok 186 Expiration out of range
,# setup
,# 47. #parseBeacons no beacons returns null
,# teardown
,ok 187 should be equal
,# setup
,# 48. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
,# teardown
,ok 188 Malformed encrypted beacon key ID
,# setup
,# 49. #parseBeacons addressBookCallback fails decrypt
,# teardown
,ok 189 should be equal
,# setup
,# 50. #parseBeacons addressBookCallback returns no matches
,# teardown
,ok 190 should be equal
,ok 191 should be equal
,# setup
,# 51. #parseBeacons addressBookCallback returns spurious match
,# teardown
,ok 192 should be equal
,ok 193 should be equal
,# setup
,# 52. #parseBeacons addressBookCallback returns public key
,# teardown
,ok 194 should be equal
,ok 195 (unnamed assert)
,# setup
,# 53. #parseBeacons with beacons both for and not for the user
,# teardown
,ok 196 should be equal
,ok 197 (unnamed assert)
,# setup
,# 54. Start and stop ThaliNotificationServer
,# teardown
,ok 198 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
,ok 199 ThaliMobile.StopAdvertisingAndListening should be called once
,# setup
,# 55. Pass an empty array to ThaliNotificationServer.start
,# teardown
,ok 200 StartUpdateAdvertisingAndListening should not be called
,ok 201 ThaliMobile.StopAdvertisingAndListening should be called once
,ok 202 no error
,ok 203 should be 204
,# setup
,# 56. Pass a string to ThaliNotificationServer.start
,# teardown
,ok 204 StartUpdateAdvertisingAndListening should not be called
,# setup
,# 57. Pass an empty parameter to ThaliNotificationServer.start
,# teardown
,ok 205 StartUpdateAdvertisingAndListening should not be called
,# setup
,# 58. Make an HTTP request to /NotificationBeacons
,# teardown
,ok 206 no error
,ok 207 should be 200
,ok 208 should be equal
,ok 209 should be equal
,ok 210 (unnamed assert)
,ok 211 no error
,ok 212 should be 204
,# setup
,# 59. Make an HTTP request to /NotificationBeacons (no keys)
,# teardown
,ok 213 error should be null
,ok 214 should be 204
,# setup
,# 60. Make an HTTP request to /NotificationBeacons before calling start
,# teardown
,ok 215 should be 404
,# setup
,# 61. #testThaliPeerAction - test getters
,# teardown
,ok 216 getPeerIdentifier
,ok 217 getConnectionType
,ok 218 getActionType
,ok 219 getActionState
,# setup
,# 62. #testThaliPeerAction - start and kill
,# teardown
,ok 220 initial state
,ok 221 after start
,ok 222 after kill
,# setup
,# 63. #testThaliPeerAction - double start
,# teardown
,ok 223 should be equal
,# setup
,# 64. #testThaliPeerAction - start after kill
,# teardown
,ok 224 clean kill
,ok 225 should be equal
,# setup
,# 65. #testThaliPeerAction - make sure ids are unique
,# teardown
,ok 226 should not be equal
,# setup
,# 66. Test PeerConnectionInformation basics
,# teardown
,ok 227 getHostAddress works
,ok 228 getPortNumber works
,ok 229 getSuggestedTCPTimeout works
,# setup
,# 67. Test PeerDictionary basic functionality
,# teardown
,ok 230 Entry counter must be 1
,ok 231 Size must be 1
,ok 232 Entry counter must be 2
,ok 233 Size must be 2
,ok 234 Entry2 should not be found
,ok 235 Size must be 1
,ok 236 Size must be 0
,ok 237 entry not found must be thrown
,# setup
,# 68. Test PeerDictionary with multiple entries.
,# teardown
,ok 238 Size must be100
,ok 239 Entries between 20 and MAXSIZE + 20 should exist
,ok 240 WAITING state entry should not be removed
,# setup
,# 69. RESOLVED entries are removed before WAITING state entry.
,# teardown
,ok 241 Entries between 6 and MAXSIZE + 4 should exist
,ok 242 Size should be MAXSIZE
,ok 243 Size should be MAXSIZE+6
,# setup
,# 70. WAITING entries are removed before CONTROLLED_BY_POOL state entry.
,# teardown
,ok 244 WAITING state entry should not be removed
,ok 245 Waiting entries between 6 and MAXSIZE + 4 should exist
,ok 246 Size should be MAXSIZE
,ok 247 entryCounter should be MAXSIZE+6
,# setup
,# 71. When CONTROLLED_BY_POOL entry is removed and kill is called.
,# teardown
,ok 248 Kill should be called once
,ok 249 Size should be 100
,# setup
,# 72. #ThaliPeerPoolInterface - bad enqueues
,# teardown
,ok 250 null arg
,ok 251 wrong arg type
,ok 252 wrong state
,# setup
,# 73. #ThaliPeerPoolInterface - do not allow same object type
,# teardown
,ok 253 good enqueue
,ok 254 should be equal
,# setup
,# 74. #ThaliPeerPoolInterface - make sure we catch kill and dequeue
,# teardown
,ok 255 good enqueue
,ok 256 2nd good enqueue
,ok 257 we are in the pool
,ok 258 We are out of the pool
,ok 259 Action was killed
,ok 260 The original kill was called too
,ok 261 second item is still in queue
,# setup
,# 75. compareBufferArrays
,# teardown
,ok 262 should throw
,ok 263 should throw
,ok 264 (unnamed assert)
,ok 265 (unnamed assert)
,ok 266 (unnamed assert)
,ok 267 (unnamed assert)
,ok 268 (unnamed assert)
,# setup
,# 76. Call start twice and get error
,# teardown
,ok 269 should throw
,# setup
,# 77. Start and make sure it runs
,# teardown
,# setup
,# 78. Make sure getTimeWhenRun is right after start
,# teardown
,ok 270 (unnamed assert)
,# setup
,# 79. Make sure getTimeWhenRun is -1 after function is called
,# teardown
,ok 271 should be equal
,# setup
,# 80. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running
,# teardown
,ok 272 should be equal
,ok 273 should be equal
,ok 274 should throw
,# setup
,# 81. Test TransientState
,# teardown
,ok 275 should throw
,ok 276 should throw
,ok 277 should be equal
,ok 278 should be equal
,ok 279 should be equal
,ok 280 should be equal
,ok 281 (unnamed assert)
,ok 282 (unnamed assert)
,# setup
,# 82. No peers and empty database
,# teardown
,ok 283 verify failed
,ok 284 constructor called once
,ok 285 constructor called with right args
,ok 286 match start arg
,ok 287 start called once
,ok 288 stop called once
,ok 289 stop after start
,# setup
,# 83. One peer and empty DB
,# teardown
,ok 290 verify failed
,ok 291 constructor called once
,ok 292 constructor called with right args
,ok 293 match start arg
,ok 294 start called once
,ok 295 stop called once
,ok 296 stop after start
,# setup
,# 84. One peer with _Local set behind current seq
,# teardown
,ok 297 verify failed
,ok 298 constructor called once
,ok 299 constructor called with right args
,ok 300 match start arg
,ok 301 start called once
,ok 302 stop called once
,ok 303 stop after start
,# setup
,# 85. One peer with _Local set equal to current seq
,# teardown
,ok 304 verify failed
,ok 305 constructor called once
,ok 306 constructor called with right args
,ok 307 match start arg
,ok 308 start called once
,ok 309 stop called once
,ok 310 stop after start
,# setup
,# 86. One peer with _Local set ahead of current seq (and no this should not happen)
,# teardown
,ok 311 verify failed
,ok 312 constructor called once
,ok 313 constructor called with right args
,ok 314 match start arg
,ok 315 start called once
,ok 316 stop called once
,ok 317 stop after start
,# setup
,# 87. Three peers, one not in DB, one behind and one ahead
,# teardown
,ok 318 verify failed
,ok 319 constructor called once
,ok 320 constructor called with right args
,ok 321 match start arg
,ok 322 start called once
,ok 323 stop called once
,ok 324 stop after start
,# setup
,# 88. More than maximum peers, make sure we only send maximum allowed
,# teardown
,ok 325 verify failed
,ok 326 constructor called once
,ok 327 constructor called with right args
,ok 328 match start arg
,ok 329 start called once
,ok 330 stop called once
,ok 331 stop after start
,# setup
,# 89. two peers with empty DB, update the doc
,# teardown
,ok 332 verify failed
,ok 333 constructor called once
,ok 334 constructor called with right args
,ok 335 last start before stop
,ok 336 empty first start
,ok 337 full second start
,ok 338 only 2 timers
,# setup
,# 90. add doc and make sure tokens refresh when they expire
,# teardown
,ok 339 verify failed
,ok 340 constructor called once
,ok 341 constructor called with right args
,ok 342 start before stop
,ok 343 We got at least 3 calls to start
,ok 344 at least 3
,ok 345 default 1
,ok 346 1 run
,ok 347 default 2
,ok 348 2 run
,ok 349 default 3
,# setup
,# 91. start and stop and start and stop
,# teardown
,ok 350 start out null
,ok 351 back to null
,ok 352 still null
,ok 353 verify failed
,ok 354 constructor called once
,ok 355 constructor called with right args
,ok 356 first start before first stop
,ok 357 first stop before second start
,ok 358 second start before second stop
,# setup
,# 92. two identical starts in a row
,# teardown
,ok 359 verify failed
,ok 360 constructor called once
,ok 361 constructor called with right args
,ok 362 (unnamed assert)
,# setup
,# 93. two different starts in a row
,# teardown
,ok 363 verify failed
,ok 364 constructor called once
,ok 365 constructor called with right args
,ok 366 (unnamed assert)
,ok 367 (unnamed assert)
,# setup
,# 94. two stops and a start and two stops
,# teardown
,ok 368 verify failed
,ok 369 constructor called once
,ok 370 constructor called with right args
,ok 371 start before stop
,# setup
,# 95. we properly enqueue requests so no then needed
,# teardown
,ok 372 verify failed
,ok 373 constructor called once
,ok 374 constructor called with right args
,ok 375 start before stop
,# setup
,# 96. test calculateSeqPointKeyId
,# teardown
,ok 376 should be equal
,ok 377 should be equal
,# setup
,# 97. can create servers manager
,# teardown
,ok 378 serversManager must not be null
,ok 379 serversManager must be an object
,# setup
,# 98. calling stop without start causes error
,# teardown
,ok 380 We need to call start first
,# setup
,# 99. can start/stop servers manager
,# teardown
,ok 381 port must be in range
,# setup
,# 100. starting twice resolves with listening port
,# teardown
,ok 382 second start should return same port
,# setup
,# 101. terminateIncomingConnection will terminate a connection
,# teardown
,ok 383 we should be connected
,ok 384 now we are disconnected
,# setup
,# 102. terminate an Outgoing connection will terminate the server
,# teardown
,# setup
,# 103. terminate an Outgoing connection with wrong arguments is not harmful
,# teardown
,# setup
,# 104. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted
,ok 385 should be in started state
,# teardown
,ok 386 peer identifier should match
,ok 387 host address should match
,ok 388 port should match
,ok 389 host address should be null
,ok 390 port should should be null
,# setup
,ok 391 should not be in started state
,# 105. #startUpdateAdvertisingAndListening should use different USN after every invocation
,ok 392 should be in started state
,# teardown
,ok 393 USN should have changed from the first one
,ok 394 when receiving the second byebye, the first USN should be already set
,# setup
,ok 395 should not be in started state
,# 106. messages with invalid location or USN should be ignored
,ok 396 should be in started state
,# teardown
,WARN thaliWifiInfrastructure Failed to parse a valid port number from location: http://foo.bar:90000
,ok 397 should not have emitted with invalid port
,WARN thaliWifiInfrastructure Received an invalid USN value: 
,ok 398 should not have emitted with invalid USN
,# setup
,ok 399 should not be in started state
,# 107. verify that Thali-specific messages are filtered correctly
,ok 400 should be in started state
,# teardown
,ok 401 irrelevant messages should be ignored
,ok 402 relevant messages should not be ignored
,ok 403 messages from this device should be ignored
,# setup
,ok 404 should not be in started state
,# 108. #startListeningForAdvertisements should fail if start not called
,ok 405 should be in started state
,# teardown
,ok 406 specific error should be returned
,# setup
,ok 407 should not be in started state
,# 109. #startUpdateAdvertisingAndListening should fail if start not called
,ok 408 should be in started state
,# teardown
,ok 409 specific error should be returned
,# setup
,ok 410 should not be in started state
,# 110. #start should fail if called twice in a row
,ok 411 should be in started state
,# teardown
,ok 412 specific error should be received
,# setup
,ok 413 should not be in started state
,# 111. should not be started after stop is called
,ok 414 should be in started state
,# teardown
,ok 415 should not be started
,ok 416 should not be listening
,ok 417 should not target listening
,ok 418 should not be advertising
,ok 419 should not target advertising
,# setup
,ok 420 should not be in started state
,# 112. #startUpdateAdvertisingAndListening should fail invalid router has been passed
,ok 421 should be in started state
,# teardown
,ERROR thaliWifiInfrastructure Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
,ok 422 specific error should be received
,# setup
,ok 423 should not be in started state
,# 113. #startUpdateAdvertisingAndListening should fail if router server starting fails
,ok 424 should be in started state
,# teardown
,ERROR thaliWifiInfrastructure Router server emitted an error: Error: listen EADDRINUSE
,ok 425 specific error expected
,# setup
,ok 426 should not be in started state
,# 114. #startUpdateAdvertisingAndListening should start hosting given router object
,ok 427 should be in started state
,# teardown
,ok 428 server should respond with code 200
,# setup
,ok 429 should not be in started state
,# 115. #stop can be called multiple times in a row
,ok 430 should be in started state
,# teardown
,ok 431 should be in stopped state
,ok 432 should still be in stopped state
,# setup
,ok 433 should not be in started state
,# 116. #startListeningForAdvertisements can be called multiple times in a row
,ok 434 should be in started state
,# teardown
,ok 435 should be in listening state
,ok 436 should still be in listening state
,# setup
,ok 437 should not be in started state
,# 117. #stopListeningForAdvertisements can be called multiple times in a row
,ok 438 should be in started state
,# teardown
,ok 439 should not be in listening state
,ok 440 should still not be in listening state
,# setup
,ok 441 should not be in started state
,# 118. #stopAdvertisingAndListening can be called multiple times in a row
,ok 442 should be in started state
,# teardown
,ok 443 should not be in advertising state
,ok 444 should still not be in advertising state
,# setup
,ok 445 should not be in started state
,# 119. functions are run from a queue in the right order
,ok 446 should be in started state
,# teardown
,ok 447 call order must match
,# setup
,ok 448 should not be in started state
,# 120. #ThaliPeerPoolDefault - single action
,# teardown
,ok 449 is an agent
,ok 450 enqueue is fine
,ok 451 Everything should be off the queue
,# setup
,# 121. #ThaliPeerPoolDefault - multiple actions
,# teardown
,ok 452 is an agent
,ok 453 first enqueue is fine
,ok 454 is an agent
,ok 455 second enqueue is fine
,ok 456 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
,ok 457 Queue is empty
,Tests Complete
,Total: 0	Passed: 0	Failed: 0
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
