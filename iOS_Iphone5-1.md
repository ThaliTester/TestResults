#### Test 62509094c147163_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/62509094c147163/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/571072B0-288B-4614-B439-1402D9BAD4CC/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/571072B0-288B-4614-B439-1402D9BAD4CC/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/62509094c147163/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/62509094c147163/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/111D6425-3122-4517-B748-5EF13219DF4E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50195"
,(lldb)     command script import "/tmp/571072B0-288B-4614-B439-1402D9BAD4CC/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-16 08:32:52.265 ThaliTest[1179:2610942] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/6F3062ED-9CF0-4A32-8E2C-FF990C7085F9/Library/Cookies/Cookies.binarycookies
,2016-03-16 08:32:52.382 ThaliTest[1179:2610942] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-16 08:32:52.383 ThaliTest[1179:2610942] Multi-tasking -> Device: YES, App: YES
,2016-03-16 08:32:52.404 ThaliTest[1179:2610942] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-16 08:32:54.200 ThaliTest[1179:2610942] Using UIWebView
,2016-03-16 08:32:54.207 ThaliTest[1179:2610942] [CDVTimer][handleopenurl] 0.293970ms
,2016-03-16 08:32:54.212 ThaliTest[1179:2610942] [CDVTimer][intentandnavigationfilter] 5.069971ms
2016-03-16 08:32:54.213 ThaliTest[1179:2610942] [CDVTimer][gesturehandler] 0.257015ms
2016-03-16 08:32:54.213 ThaliTest[1179:2610942] [CDVTimer][TotalPluginStartup] 6.658018ms
,2016-03-16 08:33:03.212 ThaliTest[1179:2610942] Resetting plugins due to page load.
,2016-03-16 08:33:06.815 ThaliTest[1179:2610942] Finished load of: file:///var/mobile/Containers/Bundle/Application/111D6425-3122-4517-B748-5EF13219DF4E/ThaliTest.app/www/index.html
,2016-03-16 08:33:07.016 ThaliTest[1179:2610942] JXcore Cordova plugin initializing
,2016-03-16 08:33:07.018 ThaliTest[1179:2611123] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-16 08:33:15.662 ThaliTest[1179:2611123] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-16 08:33:15.662 ThaliTest[1179:2611123] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-16 08:33:15.663 ThaliTest[1179:2,611123] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-16 08:33:15.669 ThaliTest[1179:2611123] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/111D6425-3122-4517-B748-5EF13219DF4E/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/111D6425-3122-4517-B748-5EF13219DF4E/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/111D6425-3122-4517-B748-5EF13219DF4E/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/111D6425-3122-4517-B748-5EF13219DF4E/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/111D6425-3122-4517-B748-5EF13219DF4E/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/111D6425-3122-4517-B748-5EF13219DF4E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/111D6425-3122-4517-B748-5EF13219DF4E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/111D6425-3122-4517-B748-5EF13219DF4E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/111D6425-3122-4517-B748-5EF13219DF4E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/111D6425-3122-4517-B748-5EF13219DF4E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/111D6425-3122-4517-B748-5EF13219DF4E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/111D6425-3122-4517-B748-5EF13219DF4E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/111D6425-3122-4517-B748-5EF13219DF4E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/111D6425-3122-4517-B748-5EF13219DF4E/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/111D6425-3122-4517-B748-5EF13219DF4E/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/111D6425-3122-4517-B748-5EF13219DF4E/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/111D6425-3122-4517-B748-5EF13219DF4E/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/111D6425-3122-4517-B748-5EF13219DF4E/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-16 08:33:34.095 ThaliTest[1179:2610942] THREAD WARNING: ['JXcore'] took '14198.405029' ms. Plugin should use a background thread.
,2016-03-16 08:33:34.096 ThaliTest[1179:2611068] void SendDelegateMessage(NSInvocation *): delegate (webView:decidePolicyForNavigationAction:request:frame:decisionListener:) failed to return after waiting 10 seconds. main run loop mode: kCFRunLoopDefaultMode
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
INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
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
,2016-03-16 08:37:40.498 ThaliTest[1179:2611123] jxcore: startListeningForAdvertisements
,2016-03-16 08:37:40.499 ThaliTest[1179:2611123] multipeer manager: start client restart timer: 0x17daae80
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-16 08:37:40.501 ThaliTest[1179:2611123] jxcore: startListeningForAdvertisements: success
,ok 127 Can call startListeningForAdvertisements without error
2016-03-16 08:37:40.503 ThaliTest[1179:2611123] jxcore: stopListeningForAdvertisements
2016-03-16 08:37:40.503 ThaliTest[1179:2611123] multipeer manager: stop client timer
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-16 08:37:40.505 ThaliTest[1179:2611123] jxcore: stopListeningForAdvertisements: success
ok 128 Can call stopListeningForAdver,tisements without error
# setup
,2016-03-16 08:37:40.897 ThaliTest[1179:2611123] jxcore: stopListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-16 08:37:40.899 ThaliTest[1179:2611123] jxcore: stopListeningForAdvertisements: success
,ok 129 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-16 08:37:40.900 ThaliTest[1179:2611123] jxcore: stopAdvertisingAndListening
2016-03-16 08:37:40.901 ThaliTest[1179:2611123] THEMultipeerManager stopping peer
2016-03-16 08:37:40.901 ThaliTest[1179:2611123] jxcore: stopAdvertisingAndListening: suc,cess
ok 130 Should be able to call stopAdvertisingAndListening in teardown
,# 33. Calling startListeningForAdvertisements twice is NOT an error
,# teardown
,2016-03-16 08:37:42.366 ThaliTest[1179:2611123] jxcore: startListeningForAdvertisements
2016-03-16 08:37:42.367 ThaliTest[1179:2611123] multipeer manager: start client restart timer: 0x17daae80
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-16 08:37:42.368 ThaliTest[1179:2611123] jxcore: startListeningForAdvertisements: success
,ok 131 Can call startListeningForAdvertisements without error
2016-03-16 08:37:42.369 ThaliTest[1179:2611123] jxcore: startListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-16 08:37:42.371 ThaliTest[1179:2611123] jxcore: startListeningForAdvertisements: success
,ok 132 Can call startListeningForAdvertisements twice without error
,# setup
,2016-03-16 08:37:42.513 ThaliTest[1179:2611123] jxcore: stopListeningForAdvertisements
2016-03-16 08:37:42.513 ThaliTest[1179:2611123] multipeer manager: stop client timer
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-16 08:37:42.514 ThaliTest[1179:2611123] jxcore: stopListeningForAdvertisements: success
ok 133 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-16 08:37:42.516 ThaliTest[1179:2611123] jxcore: stopAdvertisingAndListening
2016-03-16 08:37:42.516 ThaliTest[1179:2611123] THEMultipeerManager stopping peer
2016-03-16 08:37:42.516 ThaliTest[1179:2611123] jxcore: stopAdvertisingAndListening: suc,cess
,ok 134 Should be able to call stopAdvertisingAndListening in teardown
,# 34. Can call start/stopUpdateAdvertisingAndListening
,# teardown
,2016-03-16 08:37:43.056 ThaliTest[1179:2611123] jxcore: startUpdateAdvertisingAndListening
2016-03-16 08:37:43.056 ThaliTest[1179:2611123] server: starting 38E041CD-9D6F-4778-BC7D-6B7EF5E979C2:1
2016-03-16 08:37:43.057 ThaliTest[1179:2611123] multipeer m,anager: start client restart timer: 0x17daae80
2016-03-16 08:37:43.057 ThaliTest[1179:2611123] THEMultipeerManager initialized peer 38E041CD-9D6F-4778-BC7D-6B7EF5E979C2:1
2016-03-16 08:37:43.057 ThaliTest[1179:2611123] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 135 Can call startUpdateAdvertisingAndListening without error
,2016-03-16 08:37:43.059 ThaliTest[1179:2611123] jxcore: stopAdvertisingAndListening
2016-03-16 08:37:43.059 ThaliTest[1179:2611123] THEMultipeerManager stopping peer
2016-03-16 08:37:43.060 ThaliTest[1179:2611123] multipeer manager: stop client timer
2016-03-16 08:37:43.060 ThaliTest[1179:2611123] jxcore: stopAdvertisingAndListening: success
,ok 136 Can call stopAdvertisingAndListening without error
,# setup
,2016-03-16 08:37:43.316 ThaliTest[1179:2611123] jxcore: stopListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-16 08:37:43.317 ThaliTest[1179:2611123] jxcore: stopListeningForAdvertisements: success
,ok 137 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-16 08:37:43.319 ThaliTest[1179:2611123] jxcore: stopAdvertisingAndListening
2016-03-16 08:37:43.319 ThaliTest[1179:2611123] THEMultipeerManager stopping peer
2016-03-16 08:37:43.319 ThaliTest[1179:2611123] jxcore: stopAdvertisingAndListening: success
ok 138 Should be able to call stopAdvertisingAndListening in teardown
,# 35. Calling startUpdateAdvertisingAndListening twice is NOT an error
,# teardown
,2016-03-16 08:37:43.838 ThaliTest[1179:2611123] jxcore: startUpdateAdvertisingAndListening
2016-03-16 08:37:43.838 ThaliTest[1179:2611123] server: starting 38E041CD-9D6F-4778-BC7D-6B7EF5E979C2:2
2016-03-16 08:37:43.838 ThaliTest[1179:2611123] multipeer manager: start client restart timer: 0x17daae80
2016-03-16 08:37:43.840 ThaliTest[1179:2611123] THEMultipeerManager initialized peer 38E041CD-9D6F-4778-BC7D-6B7EF5E979C2:2
,2016-03-16 08:37:43.840 ThaliTest[1179:2611123] jxcore: startUpdateAdvertisingAndListening: success
,ok 139 Can call startUpdateAdvertisingAndListening without error
2016-03-16 08:37:43.842 ThaliTest[1179:2611123] jxcore: startUpdateAdvertisingAndListening
2016-03-16 08:37:43.842 ThaliTest[1179:2611123] THEMultipeerManager stopping peer
2016-03-16 08:3,7:43.843 ThaliTest[1179:2611123] multipeer manager: stop client timer
2016-03-16 08:37:43.843 ThaliTest[1179:2611123] server: starting 38E041CD-9D6F-4778-BC7D-6B7EF5E979C2:3
2016-03-16 08:37:43.843 ThaliTest[1179:2611123] multipeer manager: start client ,restart timer: 0x17daae80
2016-03-16 08:37:43.843 ThaliTest[1179:2611123] THEMultipeerManager initialized peer 38E041CD-9D6F-4778-BC7D-6B7EF5E979C2:3
2016-03-16 08:37:43.844 ThaliTest[1179:2611123] jxcore: startUpdateAdvertisingAndListening: success
ok 140 Can call startUpdateAdvertisingAndListening twice without error
,# setup
,2016-03-16 08:37:44.041 ThaliTest[1179:2611123] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-16 08:37:44.042 ThaliTest[1179:2611123] jxcore: stopListeningForAdvertisements: success
,ok 141 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-16 08:37:44.044 ThaliTest[1179:2611123] jxcore: stopAdvertisingAndListening
2016-03-16 08:37:44.044 ThaliTest[1179:2611123] THEMultipeerManager stopping peer
2016-03-16 08:37:44.045 ThaliTest[1179:2611123] multipeer manager: stop client timer
2016-03-16 08:37:44.045 ThaliTest[1179:2611123] jxcore: stopAdvertisingAndListening: success
ok 142 Should be able to call stopAdvertisingAndListening in teardown
,# 36. peerAvailabilityChange is called
,# teardown
,2016-03-16 08:37:44.502 ThaliTest[1179:2611123] jxcore: startUpdateAdvertisingAndListening
2016-03-16 08:37:44.503 ThaliTest[1179:2611123] server: starting 38E041CD-9D6F-4778-BC7D-6B7EF5E979C2:4
2016-03-16 08:37:44.503 ThaliTest[1179:2611123] multipeer m,anager: start client restart timer: 0x17daae80
2016-03-16 08:37:44.503 ThaliTest[1179:2611123] THEMultipeerManager initialized peer 38E041CD-9D6F-4778-BC7D-6B7EF5E979C2:4
2016-03-16 08:37:44.503 ThaliTest[1179:2611123] jxcore: startUpdateAdvertisingAndListening: success
ok 143 Can call startUpdateAdvertisingAndListeningwithout error
,2016-03-16 08:37:44.505 ThaliTest[1179:2611123] jxcore: startListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-16 08:37:44.507 ThaliTest[1179:2611123] jxcore: startListeningForAdvertisements: success
ok 144 Can call startListeningForAdvertisements without error
,2016-03-16 08:37:45.914 ThaliTest[1179:2610942] client: found new peer: 03E45744-28C1-4BBA-82F2-D0743907A071:4
,ok 145 peers must be an array
ok 146 peers must not be zero-length
,ok 147 peer must have peerIdentifier
,ok 148 peerIdentifier must be a string
,ok 149 peer must have peerAvailable
,ok 150 peer must have pleaseConnect
,# setup
,2016-03-16 08:37:47.552 ThaliTest[1179:2611123] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-16 08:37:47.554 ThaliTest[1179:2611123] jxcore: stopListeningForAdvertisements: success
,ok 151 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-16 08:37:47.556 ThaliTest[1179:2611123] jxcore: stopAdvertisingAndListening
2016-03-16 08:37:47.556 ThaliTest[1179:2611123] THEMultipeerManager stopping peer
2016-03-16 08:37:47.556 ThaliTest[1179:2611123] multipeer manager: stop client timer
20,16-03-16 08:37:47.556 ThaliTest[1179:2611123] jxcore: stopAdvertisingAndListening: success
ok 152 Should be able to call stopAdvertisingAndListening in teardown
,# 37. Can connect to a remote peer
,# teardown
,2016-03-16 08:37:48.583 ThaliTest[1179:2611123] jxcore: startUpdateAdvertisingAndListening
2016-03-16 08:37:48.583 ThaliTest[1179:2611123] server: starting 38E041CD-9D6F-4778-BC7D-6B7EF5E979C2:5
2016-03-16 08:37:48.584 ThaliTest[1179:2611123] multipeer m,anager: start client restart timer: 0x17daae80
2016-03-16 08:37:48.584 ThaliTest[1179:2611123] THEMultipeerManager initialized peer 38E041CD-9D6F-4778-BC7D-6B7EF5E979C2:5
2016-03-16 08:37:48.585 ThaliTest[1179:2611123] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 153 Can call startUpdateAdvertisingAndListening without error
,2016-03-16 08:37:48.586 ThaliTest[1179:2611123] jxcore: startListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
,2016-03-16 08:37:48.588 ThaliTest[1179:2611123] jxcore: startListeningForAdvertisements: success
,ok 154 Can call startListeningForAdvertisements without error
,2016-03-16 08:37:49.286 ThaliTest[1179:2610942] client: found new peer: 03E45744-28C1-4BBA-82F2-D0743907A071:4
2016-03-16 08:37:49.288 ThaliTest[1179:2611123] jxcore: connect 03E45744-28C1-4BBA-82F2-D0743907A071:4
2016-03-16 08:37:49.288 ThaliTest[1179:2611123] client session: connect
,2016-03-16 08:37:49.288 ThaliTest[1179:2611123] client session: stateChange:0->1 03E45744-28C1-4BBA-82F2-D0743907A071:4
,2016-03-16 08:37:49.414 ThaliTest[1179:2611744] client session: not connected 03E45744-28C1-4BBA-82F2-D0743907A071:4
2016-03-16 08:37:49.414 ThaliTest[1179:2611744] client session: onLinkFailure: 03E45744-28C1-4BBA-82F2-D0743907A071
2016-03-16 08:37:49.4,14 ThaliTest[1179:2611744] client session: disconnect
2016-03-16 08:37:49.414 ThaliTest[1179:2611744] client session: stateChange:1->0 03E45744-28C1-4BBA-82F2-D0743907A071:4
2016-03-16 08:37:49.415 ThaliTest[1179:2611744] client session: fireConnectCallb,ack: 03E45744-28C1-4BBA-82F2-D0743907A071
2016-03-16 08:37:49.415 ThaliTest[1179:2611744] jxcore: connect: fail: Peer disconnected
not ok 155 Error from connect: Peer disconnected
  ---
    operator: fail
  ...
,# setup
,2016-03-16 08:37:49.526 ThaliTest[1179:2610942] multipeer session: reset timer
2016-03-16 08:37:49.526 ThaliTest[1179:2610942] server: rejecting invitation from 03E45744-28C1-4BBA-82F2-D0743907A071 due to previous generation (38E041CD-9D6F-4778-BC7D-6B7EF,5E979C2:5 != 38E041CD-9D6F-4778-BC7D-6B7EF5E979C2:4)
,2016-03-16 08:38:08.585 ThaliTest[1179:2610942] multipeer manager: restart client
,2016-03-16 08:38:08.599 ThaliTest[1179:2610942] client: found updated peer: 03E45744-28C1-4BBA-82F2-D0743907A071:5
,2016-03-16 08:38:28.585 ThaliTest[1179:2610942] multipeer manager: restart client
,2016-03-16 08:38:28.600 ThaliTest[1179:2610942] client: found existing peer: 03E45744-28C1-4BBA-82F2-D0743907A071:5
,2016-03-16 08:38:48.585 ThaliTest[1179:2610942] multipeer manager: restart client
,2016-03-16 08:38:48.598 ThaliTest[1179:2610942] client: found existing peer: 03E45744-28C1-4BBA-82F2-D0743907A071:5
,2016-03-16 08:39:08.585 ThaliTest[1179:2610942] multipeer manager: restart client
,2016-03-16 08:39:28.585 ThaliTest[1179:2610942] multipeer manager: restart client
,2016-03-16 08:39:28.595 ThaliTest[1179:2610942] client: found existing peer: 03E45744-28C1-4BBA-82F2-D0743907A071:5
,2016-03-16 08:39:48.585 ThaliTest[1179:2610942] multipeer manager: restart client
,2016-03-16 08:39:48.594 ThaliTest[1179:2610942] client: found existing peer: 03E45744-28C1-4BBA-82F2-D0743907A071:5
,2016-03-16 08:40:08.585 ThaliTest[1179:2610942] multipeer manager: restart client
,2016-03-16 08:40:08.594 ThaliTest[1179:2610942] client: found existing peer: 03E45744-28C1-4BBA-82F2-D0743907A071:5
,2016-03-16 08:40:28.585 ThaliTest[1179:2610942] multipeer manager: restart client
,2016-03-16 08:40:28.594 ThaliTest[1179:2610942] client: found existing peer: 03E45744-28C1-4BBA-82F2-D0743907A071:5
,2016-03-16 08:40:48.585 ThaliTest[1179:2610942] multipeer manager: restart client
,2016-03-16 08:40:48.595 ThaliTest[1179:2610942] client: found existing peer: 03E45744-28C1-4BBA-82F2-D0743907A071:5
,2016-03-16 08:41:08.585 ThaliTest[1179:2610942] multipeer manager: restart client
,2016-03-16 08:41:08.595 ThaliTest[1179:2610942] client: found existing peer: 03E45744-28C1-4BBA-82F2-D0743907A071:5
,2016-03-16 08:41:28.585 ThaliTest[1179:2610942] multipeer manager: restart client
,2016-03-16 08:41:28.594 ThaliTest[1179:2610942] client: found existing peer: 03E45744-28C1-4BBA-82F2-D0743907A071:5
,2016-03-16 08:41:48.585 ThaliTest[1179:2610942] multipeer manager: restart client
,2016-03-16 08:41:48.595 ThaliTest[1179:2610942] client: found existing peer: 03E45744-28C1-4BBA-82F2-D0743907A071:5
,2016-03-16 08:42:08.585 ThaliTest[1179:2610942] multipeer manager: restart client
,2016-03-16 08:42:08.594 ThaliTest[1179:2610942] client: found existing peer: 03E45744-28C1-4BBA-82F2-D0743907A071:5
,2016-03-16 08:42:28.585 ThaliTest[1179:2610942] multipeer manager: restart client
,2016-03-16 08:42:48.585 ThaliTest[1179:2610942] multipeer manager: restart client
,2016-03-16 08:42:48.594 ThaliTest[1179:2610942] client: found existing peer: 03E45744-28C1-4BBA-82F2-D0743907A071:5
,2016-03-16 08:43:08.585 ThaliTest[1179:2610942] multipeer manager: restart client
,2016-03-16 08:43:08.594 ThaliTest[1179:2610942] client: found existing peer: 03E45744-28C1-4BBA-82F2-D0743907A071:5
,2016-03-16 08:43:28.585 ThaliTest[1179:2610942] multipeer manager: restart client
,2016-03-16 08:43:28.595 ThaliTest[1179:2610942] client: found existing peer: 03E45744-28C1-4BBA-82F2-D0743907A071:5
,2016-03-16 08:43:48.585 ThaliTest[1179:2610942] multipeer manager: restart client
,2016-03-16 08:44:08.585 ThaliTest[1179:2610942] multipeer manager: restart client
,2016-03-16 08:44:08.595 ThaliTest[1179:2610942] client: found existing peer: 03E45744-28C1-4BBA-82F2-D0743907A071:5
,2016-03-16 08:44:28.585 ThaliTest[1179:2610942] multipeer manager: restart client
,2016-03-16 08:44:28.594 ThaliTest[1179:2610942] client: found existing peer: 03E45744-28C1-4BBA-82F2-D0743907A071:5
,2016-03-16 08:44:48.585 ThaliTest[1179:2610942] multipeer manager: restart client
,2016-03-16 08:44:48.595 ThaliTest[1179:2610942] client: found existing peer: 03E45744-28C1-4BBA-82F2-D0743907A071:5
,2016-03-16 08:45:08.585 ThaliTest[1179:2610942] multipeer manager: restart client
,2016-03-16 08:45:08.596 ThaliTest[1179:2610942] client: found existing peer: 03E45744-28C1-4BBA-82F2-D0743907A071:5
,2016-03-16 08:45:28.585 ThaliTest[1179:2610942] multipeer manager: restart client
,2016-03-16 08:45:28.594 ThaliTest[1179:2610942] client: found existing peer: 03E45744-28C1-4BBA-82F2-D0743907A071:5
,2016-03-16 08:45:48.585 ThaliTest[1179:2610942] multipeer manager: restart client
,2016-03-16 08:45:48.596 ThaliTest[1179:2610942] client: found existing peer: 03E45744-28C1-4BBA-82F2-D0743907A071:5
,2016-03-16 08:46:08.585 ThaliTest[1179:2610942] multipeer manager: restart client
,2016-03-16 08:46:08.595 ThaliTest[1179:2610942] client: found existing peer: 03E45744-28C1-4BBA-82F2-D0743907A071:5
,2016-03-16 08:46:28.585 ThaliTest[1179:2610942] multipeer manager: restart client
,2016-03-16 08:46:28.595 ThaliTest[1179:2610942] client: found existing peer: 03E45744-28C1-4BBA-82F2-D0743907A071:5
,2016-03-16 08:46:48.585 ThaliTest[1179:2610942] multipeer manager: restart client
,2016-03-16 08:46:48.594 ThaliTest[1179:2610942] client: found existing peer: 03E45744-28C1-4BBA-82F2-D0743907A071:5
,2016-03-16 08:47:08.585 ThaliTest[1179:2610942] multipeer manager: restart client
,2016-03-16 08:47:08.593 ThaliTest[1179:2610942] client: found existing peer: 03E45744-28C1-4BBA-82F2-D0743907A071:5
,2016-03-16 08:47:28.585 ThaliTest[1179:2610942] multipeer manager: restart client
,2016-03-16 08:47:28.595 ThaliTest[1179:2610942] client: found existing peer: 03E45744-28C1-4BBA-82F2-D0743907A071:5
,2016-03-16 08:47:48.585 ThaliTest[1179:2610942] multipeer manager: restart client
,2016-03-16 08:47:48.597 ThaliTest[1179:2610942] client: found existing peer: 03E45744-28C1-4BBA-82F2-D0743907A071:5
,2016-03-16 08:48:08.585 ThaliTest[1179:2610942] multipeer manager: restart client
,2016-03-16 08:48:08.596 ThaliTest[1179:2610942] client: found existing peer: 03E45744-28C1-4BBA-82F2-D0743907A071:5
,2016-03-16 08:48:28.585 ThaliTest[1179:2610942] multipeer manager: restart client
,2016-03-16 08:48:28.595 ThaliTest[1179:2610942] client: found existing peer: 03E45744-28C1-4BBA-82F2-D0743907A071:5
,2016-03-16 08:48:48.585 ThaliTest[1179:2610942] multipeer manager: restart client
,2016-03-16 08:48:48.595 ThaliTest[1179:2610942] client: found existing peer: 03E45744-28C1-4BBA-82F2-D0743907A071:5
,2016-03-16 08:49:08.585 ThaliTest[1179:2610942] multipeer manager: restart client
,2016-03-16 08:49:08.596 ThaliTest[1179:2610942] client: found existing peer: 03E45744-28C1-4BBA-82F2-D0743907A071:5
,2016-03-16 08:49:28.585 ThaliTest[1179:2610942] multipeer manager: restart client
,2016-03-16 08:49:28.595 ThaliTest[1179:2610942] client: found existing peer: 03E45744-28C1-4BBA-82F2-D0743907A071:5
,2016-03-16 08:49:48.585 ThaliTest[1179:2610942] multipeer manager: restart client
,2016-03-16 08:49:48.595 ThaliTest[1179:2610942] client: found existing peer: 03E45744-28C1-4BBA-82F2-D0743907A071:5
,2016-03-16 08:50:08.585 ThaliTest[1179:2610942] multipeer manager: restart client
,2016-03-16 08:50:08.595 ThaliTest[1179:2610942] client: found existing peer: 03E45744-28C1-4BBA-82F2-D0743907A071:5
,2016-03-16 08:50:28.585 ThaliTest[1179:2610942] multipeer manager: restart client
,2016-03-16 08:50:28.594 ThaliTest[1179:2610942] client: found existing peer: 03E45744-28C1-4BBA-82F2-D0743907A071:5
,2016-03-16 08:50:48.585 ThaliTest[1179:2610942] multipeer manager: restart client
,2016-03-16 08:50:48.594 ThaliTest[1179:2610942] client: found existing peer: 03E45744-28C1-4BBA-82F2-D0743907A071:5
,2016-03-16 08:51:08.585 ThaliTest[1179:2610942] multipeer manager: restart client
,2016-03-16 08:51:08.594 ThaliTest[1179:2610942] client: found existing peer: 03E45744-28C1-4BBA-82F2-D0743907A071:5
,2016-03-16 08:51:28.585 ThaliTest[1179:2610942] multipeer manager: restart client
,2016-03-16 08:51:28.593 ThaliTest[1179:2610942] client: found existing peer: 03E45744-28C1-4BBA-82F2-D0743907A071:5
,2016-03-16 08:51:48.585 ThaliTest[1179:2610942] multipeer manager: restart client
,2016-03-16 08:51:48.596 ThaliTest[1179:2610942] client: found existing peer: 03E45744-28C1-4BBA-82F2-D0743907A071:5
,2016-03-16 08:52:08.585 ThaliTest[1179:2610942] multipeer manager: restart client
,2016-03-16 08:52:08.595 ThaliTest[1179:2610942] client: found existing peer: 03E45744-28C1-4BBA-82F2-D0743907A071:5
,2016-03-16 08:52:28.585 ThaliTest[1179:2610942] multipeer manager: restart client
,2016-03-16 08:52:28.595 ThaliTest[1179:2610942] client: found existing peer: 03E45744-28C1-4BBA-82F2-D0743907A071:5
,2016-03-16 08:52:48.585 ThaliTest[1179:2610942] multipeer manager: restart client
,2016-03-16 08:52:48.595 ThaliTest[1179:2610942] client: found existing peer: 03E45744-28C1-4BBA-82F2-D0743907A071:5
,2016-03-16 08:53:08.585 ThaliTest[1179:2610942] multipeer manager: restart client
,2016-03-16 08:53:08.595 ThaliTest[1179:2610942] client: found existing peer: 03E45744-28C1-4BBA-82F2-D0743907A071:5
,2016-03-16 08:53:28.584 ThaliTest[1179:2610942] multipeer manager: restart client
,2016-03-16 08:53:28.594 ThaliTest[1179:2610942] client: found existing peer: 03E45744-28C1-4BBA-82F2-D0743907A071:5
,2016-03-16 08:53:48.585 ThaliTest[1179:2610942] multipeer manager: restart client
,2016-03-16 08:53:48.595 ThaliTest[1179:2610942] client: found existing peer: 03E45744-28C1-4BBA-82F2-D0743907A071:5
,2016-03-16 08:54:08.585 ThaliTest[1179:2610942] multipeer manager: restart client
,2016-03-16 08:54:08.595 ThaliTest[1179:2610942] client: found existing peer: 03E45744-28C1-4BBA-82F2-D0743907A071:5
,2016-03-16 08:54:28.585 ThaliTest[1179:2610942] multipeer manager: restart client
,2016-03-16 08:54:28.595 ThaliTest[1179:2610942] client: found existing peer: 03E45744-28C1-4BBA-82F2-D0743907A071:5
,2016-03-16 08:54:48.585 ThaliTest[1179:2610942] multipeer manager: restart client
,2016-03-16 08:54:48.595 ThaliTest[1179:2610942] client: found existing peer: 03E45744-28C1-4BBA-82F2-D0743907A071:5
,2016-03-16 08:55:08.585 ThaliTest[1179:2610942] multipeer manager: restart client
,2016-03-16 08:55:08.594 ThaliTest[1179:2610942] client: found existing peer: 03E45744-28C1-4BBA-82F2-D0743907A071:5

```
