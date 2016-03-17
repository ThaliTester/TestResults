#### Test 62509094141ff10_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/62509094141ff10/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/8779A0DF-3793-46EF-847D-911B635E8210/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/8779A0DF-3793-46EF-847D-911B635E8210/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/62509094141ff10/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/62509094141ff10/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/9CCD5F66-240A-404D-A2DD-9E7049C388D5/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51434"
,(lldb)     command script import "/tmp/8779A0DF-3793-46EF-847D-911B635E8210/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-17 11:15:53.350 ThaliTest[1258:2789222] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/41789C20-BBAE-4131-A0E7-F6D494F1283E/Library/Cookies/Cookies.binarycookies
,2016-03-17 11:15:53.469 ThaliTest[1258:2789222] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-17 11:15:53.471 ThaliTest[1258:2789222] Multi-tasking -> Device: YES, App: YES
,2016-03-17 11:15:53.492 ThaliTest[1258:2789222] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-17 11:15:55.645 ThaliTest[1258:2789222] Using UIWebView
,2016-03-17 11:15:55.650 ThaliTest[1258:2789222] [CDVTimer][handleopenurl] 0.308037ms
,2016-03-17 11:15:55.655 ThaliTest[1258:2789222] [CDVTimer][intentandnavigationfilter] 5.313993ms
2016-03-17 11:15:55.656 ThaliTest[1258:2789222] [CDVTimer][gesturehandler] 0.271022ms
2016-03-17 11:15:55.656 ThaliTest[1258:2789222] [CDVTimer][TotalPluginS,tartup] 6.971955ms
,2016-03-17 11:16:04.528 ThaliTest[1258:2789222] Resetting plugins due to page load.
,2016-03-17 11:16:08.141 ThaliTest[1258:2789222] Finished load of: file:///var/mobile/Containers/Bundle/Application/9CCD5F66-240A-404D-A2DD-9E7049C388D5/ThaliTest.app/www/index.html
,2016-03-17 11:16:08.345 ThaliTest[1258:2789222] JXcore Cordova plugin initializing
,2016-03-17 11:16:08.347 ThaliTest[1258:2789405] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-17 11:16:18.215 ThaliTest[1258:2789405] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-17 11:16:18.216 ThaliTest[1258:2789405] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-17 11:16:18.216 ThaliTest[1258:2789405] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-17 11:16:18.222 ThaliTest[1258:2789405] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9CCD5F66-240A-404D-A2DD-9E7049C388D5/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9CCD5F66-240A-404D-A2DD-9E7049C388D5/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9CCD5F66-240A-404D-A2DD-9E7049C388D5/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9CCD5F66-240A-404D-A2DD-9E7049C388D5/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9CCD5F66-240A-404D-A2DD-9E7049C388D5/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9CCD5F66-240A-404D-A2DD-9E7049C388D5/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9CCD5F66-240A-404D-A2DD-9E7049C388D5/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9CCD5F66-240A-404D-A2DD-9E7049C388D5/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9CCD5F66-240A-404D-A2DD-9E7049C388D5/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9CCD5F66-240A-404D-A2DD-9E7049C388D5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9CCD5F66-240A-404D-A2DD-9E7049C388D5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9CCD5F66-240A-404D-A2DD-9E7049C388D5/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9CCD5F66-240A-404D-A2DD-9E7049C388D5/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9CCD5F66-240A-404D-A2DD-9E7049C388D5/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9CCD5F66-240A-404D-A2DD-9E7049C388D5/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9CCD5F66-240A-404D-A2DD-9E7049C388D5/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9CCD5F66-240A-404D-A2DD-9E7049C388D5/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9CCD5F66-240A-404D-A2DD-9E7049C388D5/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9CCD5F66-240A-404D-A2DD-9E7049C388D5/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-17 11:16:38.315 ThaliTest[1258:2789222] THREAD WARNING: ['JXcore'] took '14509.090088' ms. Plugin should use a background thread.
,2016-03-17 11:16:38.316 ThaliTest[1258:2789352] void SendDelegateMessage(NSInvocation *): delegate (webView:decidePolicyForNavigationAction:request:frame:decisionListener:) failed to return after waiting 10 seconds. main run loop mode: kCFRunLoopDefaultMod,e
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
,2016-03-17 11:19:51.848 ThaliTest[1258:2789405] jxcore: startListeningForAdvertisements
,2016-03-17 11:19:51.850 ThaliTest[1258:2789405] multipeer manager: start client restart timer: 0x165c9dc0
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-17 11:19:51.853 ThaliTest[1258:2789405] jxcore: startListeningForAdvertisements: success
ok 129 Can call startListeningForAdvertisements without error
2016-03-17 11:19:51.854 ThaliTest[1258:2789405] jxcore: stopListeningForAdvertisements
2016-03,-17 11:19:51.855 ThaliTest[1258:2789405] multipeer manager: stop client timer
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-17 11:19:51.856 ThaliTest[1258:2789405] jxcore:, stopListeningForAdvertisements: success
ok 130 Can call stopListeningForAdvertisements without error
# setup
,2016-03-17 11:19:52.105 ThaliTest[1258:2789405] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-17 11:19:52.106 ThaliTest[1258:2789405] jxcore: stopListeningForAdvertisements: success
,ok 131 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-17 11:19:52.108 ThaliTest[1258:2789405] jxcore: stopAdvertisingAndListening
2016-03-17 11:19:52.108 ThaliTest[1258:2789405] THEMultipeerManager stopping peer
2016-03-17 11:19:52.108 ThaliTest[1258:2789405] jxcore: stopAdvertisingAndListening: suc,cess
ok 132 Should be able to call stopAdvertisingAndListening in teardown
,# 33. Calling startListeningForAdvertisements twice is NOT an error
,# teardown
,2016-03-17 11:19:52.345 ThaliTest[1258:2789405] jxcore: startListeningForAdvertisements
2016-03-17 11:19:52.345 ThaliTest[1258:2789405] multipeer manager: start client restart timer: 0x165c9dc0
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdat,eNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-17 11:19:52.347 ThaliTest[1258:2789405] jxcore: startListeningForAdvertisements: success
,ok 133 Can call startListeningForAdvertisements without error
2016-03-17 11:19:52.349 ThaliTest[1258:2789405] jxcore: startListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-17 11:19:52.350 ThaliTest[1258:2789405] jxcore: startListeningForAdvertisements: success
,ok 134 Can call startListeningForAdvertisements twice without error
,# setup
,2016-03-17 11:19:52.766 ThaliTest[1258:2789405] jxcore: stopListeningForAdvertisements
2016-03-17 11:19:52.766 ThaliTest[1258:2789405] multipeer manager: stop client timer
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-17 11:19:52.767 ThaliTest[1258:2789405] jxcore: stopListeningForAdvertisements: success
,ok 135 Should be able to call stopListeningForAdvertisments in teardown
2016-03-17 11:19:52.769 ThaliTest[1258:2789405] jxcore: stopAdvertisingAndListening
,2016-03-17 11:19:52.769 ThaliTest[1258:2789405] THEMultipeerManager stopping peer
2016-03-17 11:19:52.769 ThaliTest[1258:2789405] jxcore: stopAdvertisingAndListening: success
,ok 136 Should be able to call stopAdvertisingAndListening in teardown
# 34. Can call start/stopUpdateAdvertisingAndListening
,# teardown
,2016-03-17 11:19:53.353 ThaliTest[1258:2789405] jxcore: startUpdateAdvertisingAndListening
2016-03-17 11:19:53.354 ThaliTest[1258:2789405] server: starting FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:1
2016-03-17 11:19:53.354 ThaliTest[1258:2789405] multipeer m,anager: start client restart timer: 0x165c9dc0
2016-03-17 11:19:53.355 ThaliTest[1258:2789405] THEMultipeerManager initialized peer FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:1
2016-03-17 11:19:53.355 ThaliTest[1258:2789405] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 137 Can call startUpdateAdvertisingAndListening without error
2016-03-17 11:19:53.356 ThaliTest[1258:2789405] jxcore: stopAdvertisingAndListening
2016-03-17 11:19:53.356 ThaliTest[1258:2789405] THEMultipeerManager stopping peer
2016,-03-17 11:19:53.357 ThaliTest[1258:2789405] multipeer manager: stop client timer
2016-03-17 11:19:53.357 ThaliTest[1258:2789405] jxcore: stopAdvertisingAndListening: success
,ok 138 Can call stopAdvertisingAndListening without error
,# setup
,2016-03-17 11:19:54.265 ThaliTest[1258:2789405] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-17 11:19:54.266 ThaliTest[1258:2789405] jxcore: stopListeningForAdvertisements: success
,ok 139 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-17 11:19:54.268 ThaliTest[1258:2789405] jxcore: stopAdvertisingAndListening
2016-03-17 11:19:54.268 ThaliTest[1258:2789405] THEMultipeerManager stopping peer
2016-03-17 11:19:54.268 ThaliTest[1258:2789405] jxcore: stopAdvertisingAndListening: suc,cess
ok 140 Should be able to call stopAdvertisingAndListening in teardown
,# 35. Calling startUpdateAdvertisingAndListening twice is NOT an error
,# teardown
,2016-03-17 11:19:54.728 ThaliTest[1258:2789405] jxcore: startUpdateAdvertisingAndListening
2016-03-17 11:19:54.729 ThaliTest[1258:2789405] server: starting FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:2
2016-03-17 11:19:54.729 ThaliTest[1258:2789405] multipeer m,anager: start client restart timer: 0x165c9dc0
2016-03-17 11:19:54.729 ThaliTest[1258:2789405] THEMultipeerManager initialized peer FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:2
2016-03-17 11:19:54.730 ThaliTest[1258:2789405] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 141 Can call startUpdateAdvertisingAndListening without error
2016-03-17 11:19:54.731 ThaliTest[1258:2789405] jxcore: startUpdateAdvertisingAndListening
2016-03-17 11:19:54.731 ThaliTest[1258:2789405] THEMultipeerManager stopping pee,r
2016-03-17 11:19:54.732 ThaliTest[1258:2789405] multipeer manager: stop client timer
2016-03-17 11:19:54.732 ThaliTest[1258:2789405] server: starting FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:3
2016-03-17 11:19:54.732 ThaliTest[1258:2789405] multipeer mana,ger: start client restart timer: 0x165c9dc0
,2016-03-17 11:19:54.737 ThaliTest[1258:2789405] THEMultipeerManager initialized peer FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:3
,2016-03-17 11:19:54.756 ThaliTest[1258:2789405] jxcore: startUpdateAdvertisingAndListening: success
,ok 142 Can call startUpdateAdvertisingAndListening twice without error
,# setup
,2016-03-17 11:19:54.859 ThaliTest[1258:2789405] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-17 11:19:54.860 ThaliTest[1258:2789405] jxcore: stopListeningForAdvertisements: success
,ok 143 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-17 11:19:54.863 ThaliTest[1258:2789405] jxcore: stopAdvertisingAndListening
2016-03-17 11:19:54.863 ThaliTest[1258:2789405] THEMultipeerManager stopping peer
2016-03-17 11:19:54.863 ThaliTest[1258:2789405] multipeer manager: stop client timer
20,16-03-17 11:19:54.863 ThaliTest[1258:2789405] jxcore: stopAdvertisingAndListening: success
ok 144 Should be able to call stopAdvertisingAndListening in teardown
,# 36. peerAvailabilityChange is called
,# teardown
,2016-03-17 11:19:55.294 ThaliTest[1258:2789405] jxcore: startUpdateAdvertisingAndListening
2016-03-17 11:19:55.294 ThaliTest[1258:2789405] server: starting FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:4
2016-03-17 11:19:55.294 ThaliTest[1258:2789405] multipeer m,anager: start client restart timer: 0x165c9dc0
2016-03-17 11:19:55.294 ThaliTest[1258:2789405] THEMultipeerManager initialized peer FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:4
2016-03-17 11:19:55.295 ThaliTest[1258:2789405] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 145 Can call startUpdateAdvertisingAndListeningwithout error
2016-03-17 11:19:55.296 ThaliTest[1258:2789405] jxcore: startListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingAc,tive":true,"discoveryActive":true}
2016-03-17 11:19:55.297 ThaliTest[1258:2789405] jxcore: startListeningForAdvertisements: success
,ok 146 Can call startListeningForAdvertisements without error
,2016-03-17 11:19:56.619 ThaliTest[1258:2789222] client: found new peer: 20B211DA-8CC3-44A8-A409-C300A017DFDB:4
ok 147 peers must be an array
ok 148 peers must not be zero-length
,ok 149 peer must have peerIdentifier
,ok 150 peerIdentifier must be a string
,ok 151 peer must have peerAvailable
,ok 152 peer must have pleaseConnect
,# setup
,2016-03-17 11:19:59.438 ThaliTest[1258:2789405] jxcore: stopListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-17 11:19:59.439 ThaliTest[1258:2789405] jxcore: stopListeningForAdvertisements: success
,ok 153 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-17 11:19:59.440 ThaliTest[1258:2789405] jxcore: stopAdvertisingAndListening
,2016-03-17 11:19:59.440 ThaliTest[1258:2789405] THEMultipeerManager stopping peer
2016-03-17 11:19:59.441 ThaliTest[1258:2789405] multipeer manager: stop client timer
2016-03-17 11:19:59.442 ThaliTest[1258:2789405] jxcore: stopAdvertisingAndListening: su,ccess
ok 154 Should be able to call stopAdvertisingAndListening in teardown
,# 37. Can connect to a remote peer
,# teardown
,2016-03-17 11:19:59.902 ThaliTest[1258:2789405] jxcore: startUpdateAdvertisingAndListening
2016-03-17 11:19:59.902 ThaliTest[1258:2789405] server: starting FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
2016-03-17 11:19:59.903 ThaliTest[1258:2789405] multipeer m,anager: start client restart timer: 0x165c9dc0
2016-03-17 11:19:59.903 ThaliTest[1258:2789405] THEMultipeerManager initialized peer FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
2016-03-17 11:19:59.903 ThaliTest[1258:2789405] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 155 Can call startUpdateAdvertisingAndListening without error
2016-03-17 11:19:59.904 ThaliTest[1258:2789405] jxcore: startListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingA,ctive":true,"discoveryActive":true}
2016-03-17 11:19:59.905 ThaliTest[1258:2789405] jxcore: startListeningForAdvertisements: success
,ok 156 Can call startListeningForAdvertisements without error
,2016-03-17 11:20:01.906 ThaliTest[1258:2789222] client: found new peer: 20B211DA-8CC3-44A8-A409-C300A017DFDB:5
INFO testThaliMobileNative Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"20B211DA-8CC3-44A8-A409-C300A017DF,DB:5","pleaseConnect":0}]
2016-03-17 11:20:01.909 ThaliTest[1258:2789405] jxcore: connect 20B211DA-8CC3-44A8-A409-C300A017DFDB:5
,2016-03-17 11:20:01.910 ThaliTest[1258:2789405] client session: connect
2016-03-17 11:20:01.911 ThaliTest[1258:2789405] client session: stateChange:0->1 20B211DA-8CC3-44A8-A409-C300A017DFDB:5
,2016-03-17 11:20:11.936 ThaliTest[1258:2789222] multipeer session: reset timer
2016-03-17 11:20:11.936 ThaliTest[1258:2789222] server: rejecting invitation from 20B211DA-8CC3-44A8-A409-C300A017DFDB due to previous generation (FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5 != FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:4)
,2016-03-17 11:20:16.455 ThaliTest[1258:2789831] client session: p2p link connected
2016-03-17 11:20:16.458 ThaliTest[1258:2789831] client session: stateChange:1->2 20B211DA-8CC3-44A8-A409-C300A017DFDB:5
2016-03-17 11:20:16.459 ThaliTest[1258:2789831] cli,ent session: fireConnectCallback: 20B211DA-8CC3-44A8-A409-C300A017DFDB
2016-03-17 11:20:16.459 ThaliTest[1258:2789831] jxcore: connect: success
INFO testThaliMobileNative 
ok 157 Must have listeningPort
,ok 158 listeningPort must be a number
,ok 159 Connection must have clientPort
,ok 160 clientPort must be a number
,ok 161 Connection must have serverPort
,ok 162 serverPort must be a number
,ok 163 forward connection must have clientPort == 0
,ok 164 forward connectionmust have serverPort == 0
,# setup
,2016-03-17 11:20:17.314 ThaliTest[1258:2789405] jxcore: stopListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-17 11:20:17.315 ThaliTest[1258:2789405] jxcore: stopListeningForAdvertisements: success
,ok 165 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-17 11:20:17.317 ThaliTest[1258:2789405] jxcore: stopAdvertisingAndListening
,2016-03-17 11:20:17.317 ThaliTest[1258:2789405] THEMultipeerManager stopping peer
,2016-03-17 11:20:17.318 ThaliTest[1258:2789405] client session: disconnect
2016-03-17 11:20:17.318 ThaliTest[1258:2789405] client session: stateChange:2->0 20B211DA-8CC3-44A8-A409-C300A017DFDB:5
,2016-03-17 11:20:17.329 ThaliTest[1258:2789405] multipeer manager: stop client timer
2016-03-17 11:20:17.330 ThaliTest[1258:2789405] jxcore: stopAdvertisingAndListening: success
ok 166 Should be able to call stopAdvertisingAndListening in teardown
# 38., Can shift large amounts of data
,# teardown
,2016-03-17 11:20:18.001 ThaliTest[1258:2789405] jxcore: startUpdateAdvertisingAndListening
2016-03-17 11:20:18.002 ThaliTest[1258:2789405] server: starting FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:6
2016-03-17 11:20:18.002 ThaliTest[1258:2789405] multipeer m,anager: start client restart timer: 0x165c9dc0
2016-03-17 11:20:18.003 ThaliTest[1258:2789405] THEMultipeerManager initialized peer FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:6
2016-03-17 11:20:18.003 ThaliTest[1258:2789405] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 167 Can call startUpdateAdvertisingAndListening without error
2016-03-17 11:20:18.004 ThaliTest[1258:2789405] jxcore: startListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingA,ctive":true,"discoveryActive":true}
2016-03-17 11:20:18.005 ThaliTest[1258:2789405] jxcore: startListeningForAdvertisements: success
ok 168 Can call startListeningForAdvertisements without error
,2016-03-17 11:20:18.843 ThaliTest[1258:2789222] client: found new peer: 20B211DA-8CC3-44A8-A409-C300A017DFDB:5
2016-03-17 11:20:18.844 ThaliTest[1258:2789405] jxcore: connect 20B211DA-8CC3-44A8-A409-C300A017DFDB:5
2016-03-17 11:20:18.848 ThaliTest[1258:2789405] client session: connect
,2016-03-17 11:20:18.848 ThaliTest[1258:2789405] client session: stateChange:0->1 20B211DA-8CC3-44A8-A409-C300A017DFDB:5
,2016-03-17 11:20:20.236 ThaliTest[1258:2789222] multipeer session: reset timer
2016-03-17 11:20:20.236 ThaliTest[1258:2789222] server: rejecting invitation from 20B211DA-8CC3-44A8-A409-C300A017DFDB due to previous generation (FD1CC9F2-9667-4D2B-A114-31A3E,1486EC6:6 != FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5)
,2016-03-17 11:20:20.265 ThaliTest[1258:2789830] client session: not connected 20B211DA-8CC3-44A8-A409-C300A017DFDB:5
2016-03-17 11:20:20.266 ThaliTest[1258:2789830] client session: onLinkFailure: 20B211DA-8CC3-44A8-A409-C300A017DFDB
2016-03-17 11:20:20.2,66 ThaliTest[1258:2789830] client session: disconnect
2016-03-17 11:20:20.266 ThaliTest[1258:2789830] client session: stateChange:1->0 20B211DA-8CC3-44A8-A409-C300A017DFDB:5
2016-03-17 11:20:20.267 ThaliTest[1258:2789830] client session: fireConnectCallb,ack: 20B211DA-8CC3-44A8-A409-C300A017DFDB
2016-03-17 11:20:20.267 ThaliTest[1258:2789830] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative Connect returned an error: Peer disconnected
INFO testThaliMobileNative Scheduling a connect re,try - retries left: 9
,2016-03-17 11:20:23.271 ThaliTest[1258:2789405] jxcore: connect 20B211DA-8CC3-44A8-A409-C300A017DFDB:5
2016-03-17 11:20:23.272 ThaliTest[1258:2789405] client session: connect
2016-03-17 11:20:23.272 ThaliTest[1258:2789405] client session: stateChange:0->1 20B211DA-8CC3-44A8-A409-C300A017DFDB:5
,2016-03-17 11:20:23.427 ThaliTest[1258:2789830] client session: not connected 20B211DA-8CC3-44A8-A409-C300A017DFDB:5
2016-03-17 11:20:23.427 ThaliTest[1258:2789830] client session: onLinkFailure: 20B211DA-8CC3-44A8-A409-C300A017DFDB
2016-03-17 11:20:23.4,28 ThaliTest[1258:2789830] client session: disconnect
2016-03-17 11:20:23.428 ThaliTest[1258:2789830] client session: stateChange:1->0 20B211DA-8CC3-44A8-A409-C300A017DFDB:5
2016-03-17 11:20:23.428 ThaliTest[1258:2789830] client session: fireConnectCallb,ack: 20B211DA-8CC3-44A8-A409-C300A017DFDB
2016-03-17 11:20:23.428 ThaliTest[1258:2789830] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative Connect returned an error: Peer disconnected
INFO testThaliMobileNative Scheduling a connect re,try - retries left: 8
,2016-03-17 11:20:26.431 ThaliTest[1258:2789405] jxcore: connect 20B211DA-8CC3-44A8-A409-C300A017DFDB:5
2016-03-17 11:20:26.431 ThaliTest[1258:2789405] client session: connect
2016-03-17 11:20:26.432 ThaliTest[1258:2789405] client session: stateChange:0->1 20B211DA-8CC3-44A8-A409-C300A017DFDB:5
,2016-03-17 11:20:26.537 ThaliTest[1258:2789933] client session: not connected 20B211DA-8CC3-44A8-A409-C300A017DFDB:5
2016-03-17 11:20:26.537 ThaliTest[1258:2789933] client session: onLinkFailure: 20B211DA-8CC3-44A8-A409-C300A017DFDB
2016-03-17 11:20:26.5,37 ThaliTest[1258:2789933] client session: disconnect
2016-03-17 11:20:26.537 ThaliTest[1258:2789933] client session: stateChange:1->0 20B211DA-8CC3-44A8-A409-C300A017DFDB:5
2016-03-17 11:20:26.538 ThaliTest[1258:2789933] client session: fireConnectCallb,ack: 20B211DA-8CC3-44A8-A409-C300A017DFDB
,2016-03-17 11:20:26.539 ThaliTest[1258:2789933] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative Connect returned an error: Peer disconnected
,INFO testThaliMobileNative Scheduling a connect retry - retries left: 7
,2016-03-17 11:20:29.550 ThaliTest[1258:2789405] jxcore: connect 20B211DA-8CC3-44A8-A409-C300A017DFDB:5
2016-03-17 11:20:29.551 ThaliTest[1258:2789405] client session: connect
2016-03-17 11:20:29.551 ThaliTest[1258:2789405] client session: stateChange:0->,1 20B211DA-8CC3-44A8-A409-C300A017DFDB:5
,2016-03-17 11:20:29.611 ThaliTest[1258:2789831] client session: not connected 20B211DA-8CC3-44A8-A409-C300A017DFDB:5
2016-03-17 11:20:29.612 ThaliTest[1258:2789831] client session: onLinkFailure: 20B211DA-8CC3-44A8-A409-C300A017DFDB
2016-03-17 11:20:29.6,13 ThaliTest[1258:2789831] client session: disconnect
2016-03-17 11:20:29.613 ThaliTest[1258:2789831] client session: stateChange:1->0 20B211DA-8CC3-44A8-A409-C300A017DFDB:5
2016-03-17 11:20:29.613 ThaliTest[1258:2789831] client session: fireConnectCallb,ack: 20B211DA-8CC3-44A8-A409-C300A017DFDB
2016-03-17 11:20:29.613 ThaliTest[1258:2789831] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative Connect returned an error: Peer disconnected
INFO testThaliMobileNative Scheduling a connect retry - retries left: 6
,2016-03-17 11:20:32.220 ThaliTest[1258:2789222] multipeer session: reset timer
2016-03-17 11:20:32.220 ThaliTest[1258:2789222] server: disconnecting to refresh session (20B211DA-8CC3-44A8-A409-C300A017DFDB)
2016-03-17 11:20:32.221 ThaliTest[1258:2789222], server: rejecting invitation from 20B211DA-8CC3-44A8-A409-C300A017DFDB due to previous generation (FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:6 != FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5)
,2016-03-17 11:20:32.619 ThaliTest[1258:2789405] jxcore: connect 20B211DA-8CC3-44A8-A409-C300A017DFDB:5
2016-03-17 11:20:32.620 ThaliTest[1258:2789405] client session: connect
2016-03-17 11:20:32.620 ThaliTest[1258:2789405] client session: stateChange:0->1 20B211DA-8CC3-44A8-A409-C300A017DFDB:5
,2016-03-17 11:20:32.722 ThaliTest[1258:2789932] client session: not connected 20B211DA-8CC3-44A8-A409-C300A017DFDB:5
2016-03-17 11:20:32.724 ThaliTest[1258:2789932] client session: onLinkFailure: 20B211DA-8CC3-44A8-A409-C300A017DFDB
2016-03-17 11:20:32.724 ThaliTest[1258:2789932] client session: disconnect
2016-03-17 11:20:32.724 ThaliTest[1258:2789932] client session: stateChange:1->0 20B211DA-8CC3-44A8-A409-C300A017DFDB:5
,2016-03-17 11:20:32.724 ThaliTest[1258:2789932] client session: fireConnectCallback: 20B211DA-8CC3-44A8-A409-C300A017DFDB
2016-03-17 11:20:32.726 ThaliTest[1258:2789932] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative Connect returned, an error: Peer disconnected
INFO testThaliMobileNative Scheduling a connect retry - retries left: 5
,2016-03-17 11:20:35.735 ThaliTest[1258:2789405] jxcore: connect 20B211DA-8CC3-44A8-A409-C300A017DFDB:5
2016-03-17 11:20:35.736 ThaliTest[1258:2789405] client session: connect
2016-03-17 11:20:35.736 ThaliTest[1258:2789405] client session: stateChange:0->,1 20B211DA-8CC3-44A8-A409-C300A017DFDB:5
,2016-03-17 11:20:35.948 ThaliTest[1258:2789830] client session: not connected 20B211DA-8CC3-44A8-A409-C300A017DFDB:5
2016-03-17 11:20:35.949 ThaliTest[1258:2789830] client session: onLinkFailure: 20B211DA-8CC3-44A8-A409-C300A017DFDB
2016-03-17 11:20:35.9,49 ThaliTest[1258:2789830] client session: disconnect
2016-03-17 11:20:35.949 ThaliTest[1258:2789830] client session: stateChange:1->0 20B211DA-8CC3-44A8-A409-C300A017DFDB:5
2016-03-17 11:20:35.949 ThaliTest[1258:2789830] client session: fireConnectCallb,ack: 20B211DA-8CC3-44A8-A409-C300A017DFDB
2016-03-17 11:20:35.950 ThaliTest[1258:2789830] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative Connect returned an error: Peer disconnected
INFO testThaliMobileNative Scheduling a connect retry - retries left: 4
,2016-03-17 11:20:38.004 ThaliTest[1258:2789222] multipeer manager: restart client
,2016-03-17 11:20:38.018 ThaliTest[1258:2789222] client: found updated peer: 20B211DA-8CC3-44A8-A409-C300A017DFDB:6
,2016-03-17 11:20:38.960 ThaliTest[1258:2789405] jxcore: connect 20B211DA-8CC3-44A8-A409-C300A017DFDB:5
2016-03-17 11:20:38.961 ThaliTest[1258:2789405] client session: connect
2016-03-17 11:20:38.961 ThaliTest[1258:2789405] client session: stateChange:0->1 20B211DA-8CC3-44A8-A409-C300A017DFDB:6
,2016-03-17 11:20:39.088 ThaliTest[1258:2789932] client session: not connected 20B211DA-8CC3-44A8-A409-C300A017DFDB:6
2016-03-17 11:20:39.088 ThaliTest[1258:2789932] client session: onLinkFailure: 20B211DA-8CC3-44A8-A409-C300A017DFDB
2016-03-17 11:20:39.089 ThaliTest[1258:2789932] client session: disconnect
,2016-03-17 11:20:39.089 ThaliTest[1258:2789932] client session: stateChange:1->0 20B211DA-8CC3-44A8-A409-C300A017DFDB:6
,2016-03-17 11:20:39.091 ThaliTest[1258:2789932] client session: fireConnectCallback: 20B211DA-8CC3-44A8-A409-C300A017DFDB
2016-03-17 11:20:39.091 ThaliTest[1258:2789932] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative Connect returned an error: Peer disconnected
INFO testThaliMobileNative Scheduling a connect retry - retries left: 3
,2016-03-17 11:20:42.098 ThaliTest[1258:2789405] jxcore: connect 20B211DA-8CC3-44A8-A409-C300A017DFDB:5
2016-03-17 11:20:42.099 ThaliTest[1258:2789405] client session: connect
2016-03-17 11:20:42.099 ThaliTest[1258:2789405] client session: stateChange:0->,1 20B211DA-8CC3-44A8-A409-C300A017DFDB:6
,2016-03-17 11:20:42.222 ThaliTest[1258:2789831] client session: not connected 20B211DA-8CC3-44A8-A409-C300A017DFDB:6
,2016-03-17 11:20:42.224 ThaliTest[1258:2789831] client session: onLinkFailure: 20B211DA-8CC3-44A8-A409-C300A017DFDB
2016-03-17 11:20:42.224 ThaliTest[1258:2789831] client session: disconnect
2016-03-17 11:20:42.225 ThaliTest[1258:2789831] client session:, stateChange:1->0 20B211DA-8CC3-44A8-A409-C300A017DFDB:6
2016-03-17 11:20:42.225 ThaliTest[1258:2789831] client session: fireConnectCallback: 20B211DA-8CC3-44A8-A409-C300A017DFDB
2016-03-17 11:20:42.225 ThaliTest[1258:2789831] jxcore: connect: fail: Peer, disconnected
INFO testThaliMobileNative Connect returned an error: Peer disconnected
INFO testThaliMobileNative Scheduling a connect retry - retries left: 2
,2016-03-17 11:20:45.235 ThaliTest[1258:2789405] jxcore: connect 20B211DA-8CC3-44A8-A409-C300A017DFDB:5
2016-03-17 11:20:45.236 ThaliTest[1258:2789405] client session: connect
2016-03-17 11:20:45.236 ThaliTest[1258:2789405] client session: stateChange:0->,1 20B211DA-8CC3-44A8-A409-C300A017DFDB:6
,2016-03-17 11:20:45.376 ThaliTest[1258:2789222] multipeer session: reset timer
2016-03-17 11:20:45.377 ThaliTest[1258:2789222] server: disconnecting to refresh session (20B211DA-8CC3-44A8-A409-C300A017DFDB)
2016-03-17 11:20:45.377 ThaliTest[1258:2789222] server: rejecting invitation from 20B211DA-8CC3-44A8-A409-C300A017DFDB due to previous generation (FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:6 != FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5)
,2016-03-17 11:20:45.398 ThaliTest[1258:2789956] client session: not connected 20B211DA-8CC3-44A8-A409-C300A017DFDB:6
,2016-03-17 11:20:45.399 ThaliTest[1258:2789956] client session: onLinkFailure: 20B211DA-8CC3-44A8-A409-C300A017DFDB
,2016-03-17 11:20:45.399 ThaliTest[1258:2789956] client session: disconnect
,2016-03-17 11:20:45.401 ThaliTest[1258:2789956] client session: stateChange:1->0 20B211DA-8CC3-44A8-A409-C300A017DFDB:6
,2016-03-17 11:20:45.402 ThaliTest[1258:2789956] client session: fireConnectCallback: 20B211DA-8CC3-44A8-A409-C300A017DFDB
,2016-03-17 11:20:45.403 ThaliTest[1258:2789956] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative Connect returned an error: Peer disconnected
,INFO testThaliMobileNative Scheduling a connect retry - retries left: 1
,2016-03-17 11:20:48.416 ThaliTest[1258:2789405] jxcore: connect 20B211DA-8CC3-44A8-A409-C300A017DFDB:5
2016-03-17 11:20:48.417 ThaliTest[1258:2789405] client session: connect
2016-03-17 11:20:48.417 ThaliTest[1258:2789405] client session: stateChange:0->,1 20B211DA-8CC3-44A8-A409-C300A017DFDB:6
,2016-03-17 11:20:48.514 ThaliTest[1258:2790050] client session: not connected 20B211DA-8CC3-44A8-A409-C300A017DFDB:6
2016-03-17 11:20:48.515 ThaliTest[1258:2790050] client session: onLinkFailure: 20B211DA-8CC3-44A8-A409-C300A017DFDB
2016-03-17 11:20:48.5,15 ThaliTest[1258:2790050] client session: disconnect
2016-03-17 11:20:48.516 ThaliTest[1258:2790050] client session: stateChange:1->0 20B211DA-8CC3-44A8-A409-C300A017DFDB:6
2016-03-17 11:20:48.516 ThaliTest[1258:2790050] client session: fireConnectCallb,ack: 20B211DA-8CC3-44A8-A409-C300A017DFDB
2016-03-17 11:20:48.516 ThaliTest[1258:2790050] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative Connect returned an error: Peer disconnected
WARN testThaliMobileNative Too many connect retrie,s!
,2016-03-17 11:20:58.004 ThaliTest[1258:2789222] multipeer manager: restart client
,2016-03-17 11:20:58.017 ThaliTest[1258:2789222] client: found existing peer: 20B211DA-8CC3-44A8-A409-C300A017DFDB:6
,2016-03-17 11:21:18.004 ThaliTest[1258:2789222] multipeer manager: restart client
,2016-03-17 11:21:18.018 ThaliTest[1258:2789222] client: found existing peer: 20B211DA-8CC3-44A8-A409-C300A017DFDB:6
,2016-03-17 11:21:38.004 ThaliTest[1258:2789222] multipeer manager: restart client
,2016-03-17 11:21:38.018 ThaliTest[1258:2789222] client: found existing peer: 20B211DA-8CC3-44A8-A409-C300A017DFDB:6
,2016-03-17 11:21:58.004 ThaliTest[1258:2789222] multipeer manager: restart client
,2016-03-17 11:21:58.018 ThaliTest[1258:2789222] client: found existing peer: 20B211DA-8CC3-44A8-A409-C300A017DFDB:6
,2016-03-17 11:22:18.003 ThaliTest[1258:2789222] multipeer manager: restart client
,2016-03-17 11:22:18.017 ThaliTest[1258:2789222] client: found existing peer: 20B211DA-8CC3-44A8-A409-C300A017DFDB:6
,2016-03-17 11:22:38.004 ThaliTest[1258:2789222] multipeer manager: restart client
,2016-03-17 11:22:38.016 ThaliTest[1258:2789222] client: found existing peer: 20B211DA-8CC3-44A8-A409-C300A017DFDB:6
,2016-03-17 11:22:58.004 ThaliTest[1258:2789222] multipeer manager: restart client
,2016-03-17 11:22:58.017 ThaliTest[1258:2789222] client: found existing peer: 20B211DA-8CC3-44A8-A409-C300A017DFDB:6
,2016-03-17 11:23:18.004 ThaliTest[1258:2789222] multipeer manager: restart client
,2016-03-17 11:23:18.018 ThaliTest[1258:2789222] client: found existing peer: 20B211DA-8CC3-44A8-A409-C300A017DFDB:6
,2016-03-17 11:23:38.004 ThaliTest[1258:2789222] multipeer manager: restart client
,2016-03-17 11:23:38.017 ThaliTest[1258:2789222] client: found existing peer: 20B211DA-8CC3-44A8-A409-C300A017DFDB:6
,2016-03-17 11:23:58.004 ThaliTest[1258:2789222] multipeer manager: restart client
,2016-03-17 11:23:58.017 ThaliTest[1258:2789222] client: found existing peer: 20B211DA-8CC3-44A8-A409-C300A017DFDB:6
,2016-03-17 11:24:18.004 ThaliTest[1258:2789222] multipeer manager: restart client
,2016-03-17 11:24:18.016 ThaliTest[1258:2789222] client: found existing peer: 20B211DA-8CC3-44A8-A409-C300A017DFDB:6
,2016-03-17 11:24:38.004 ThaliTest[1258:2789222] multipeer manager: restart client
,2016-03-17 11:24:38.017 ThaliTest[1258:2789222] client: found existing peer: 20B211DA-8CC3-44A8-A409-C300A017DFDB:6
,2016-03-17 11:24:58.004 ThaliTest[1258:2789222] multipeer manager: restart client
,2016-03-17 11:24:58.017 ThaliTest[1258:2789222] client: found existing peer: 20B211DA-8CC3-44A8-A409-C300A017DFDB:6
,2016-03-17 11:25:18.004 ThaliTest[1258:2789222] multipeer manager: restart client
,2016-03-17 11:25:18.018 ThaliTest[1258:2789222] client: found existing peer: 20B211DA-8CC3-44A8-A409-C300A017DFDB:6
,2016-03-17 11:25:38.004 ThaliTest[1258:2789222] multipeer manager: restart client
,2016-03-17 11:25:38.020 ThaliTest[1258:2789222] client: found existing peer: 20B211DA-8CC3-44A8-A409-C300A017DFDB:6
,2016-03-17 11:25:58.003 ThaliTest[1258:2789222] multipeer manager: restart client
,2016-03-17 11:26:18.004 ThaliTest[1258:2789222] multipeer manager: restart client
,2016-03-17 11:26:18.011 ThaliTest[1258:2789222] client: found existing peer: 20B211DA-8CC3-44A8-A409-C300A017DFDB:6
,2016-03-17 11:26:38.004 ThaliTest[1258:2789222] multipeer manager: restart client
,2016-03-17 11:26:38.013 ThaliTest[1258:2789222] client: found existing peer: 20B211DA-8CC3-44A8-A409-C300A017DFDB:6
,2016-03-17 11:26:58.004 ThaliTest[1258:2789222] multipeer manager: restart client
,2016-03-17 11:26:58.013 ThaliTest[1258:2789222] client: found existing peer: 20B211DA-8CC3-44A8-A409-C300A017DFDB:6
,2016-03-17 11:27:18.004 ThaliTest[1258:2789222] multipeer manager: restart client
,2016-03-17 11:27:18.013 ThaliTest[1258:2789222] client: found existing peer: 20B211DA-8CC3-44A8-A409-C300A017DFDB:6
,2016-03-17 11:27:38.003 ThaliTest[1258:2789222] multipeer manager: restart client
,2016-03-17 11:27:38.011 ThaliTest[1258:2789222] client: found existing peer: 20B211DA-8CC3-44A8-A409-C300A017DFDB:6
,2016-03-17 11:27:58.004 ThaliTest[1258:2789222] multipeer manager: restart client
,2016-03-17 11:27:58.013 ThaliTest[1258:2789222] client: found existing peer: 20B211DA-8CC3-44A8-A409-C300A017DFDB:6
,2016-03-17 11:28:18.004 ThaliTest[1258:2789222] multipeer manager: restart client
,2016-03-17 11:28:18.013 ThaliTest[1258:2789222] client: found existing peer: 20B211DA-8CC3-44A8-A409-C300A017DFDB:6
,2016-03-17 11:28:38.004 ThaliTest[1258:2789222] multipeer manager: restart client
,2016-03-17 11:28:58.004 ThaliTest[1258:2789222] multipeer manager: restart client
,2016-03-17 11:28:58.013 ThaliTest[1258:2789222] client: found existing peer: 20B211DA-8CC3-44A8-A409-C300A017DFDB:6
,2016-03-17 11:29:18.004 ThaliTest[1258:2789222] multipeer manager: restart client
,2016-03-17 11:29:18.014 ThaliTest[1258:2789222] client: found existing peer: 20B211DA-8CC3-44A8-A409-C300A017DFDB:6
,2016-03-17 11:29:38.004 ThaliTest[1258:2789222] multipeer manager: restart client
,2016-03-17 11:29:38.017 ThaliTest[1258:2789222] client: found existing peer: 20B211DA-8CC3-44A8-A409-C300A017DFDB:6
,2016-03-17 11:29:58.004 ThaliTest[1258:2789222] multipeer manager: restart client
,2016-03-17 11:29:58.013 ThaliTest[1258:2789222] client: found existing peer: 20B211DA-8CC3-44A8-A409-C300A017DFDB:6
,2016-03-17 11:30:18.004 ThaliTest[1258:2789222] multipeer manager: restart client
,2016-03-17 11:30:18.013 ThaliTest[1258:2789222] client: found existing peer: 20B211DA-8CC3-44A8-A409-C300A017DFDB:6
,2016-03-17 11:30:38.004 ThaliTest[1258:2789222] multipeer manager: restart client
,2016-03-17 11:30:38.013 ThaliTest[1258:2789222] client: found existing peer: 20B211DA-8CC3-44A8-A409-C300A017DFDB:6
,2016-03-17 11:30:58.004 ThaliTest[1258:2789222] multipeer manager: restart client
,2016-03-17 11:30:58.013 ThaliTest[1258:2789222] client: found existing peer: 20B211DA-8CC3-44A8-A409-C300A017DFDB:6
,2016-03-17 11:31:18.004 ThaliTest[1258:2789222] multipeer manager: restart client
,2016-03-17 11:31:18.012 ThaliTest[1258:2789222] client: found existing peer: 20B211DA-8CC3-44A8-A409-C300A017DFDB:6
,2016-03-17 11:31:37.933 ThaliTest[1258:2789222] multipeer manager: restart client
,2016-03-17 11:31:37.943 ThaliTest[1258:2789222] client: found existing peer: 20B211DA-8CC3-44A8-A409-C300A017DFDB:6
,2016-03-17 11:31:57.933 ThaliTest[1258:2789222] multipeer manager: restart client
,2016-03-17 11:31:57.944 ThaliTest[1258:2789222] client: found existing peer: 20B211DA-8CC3-44A8-A409-C300A017DFDB:6
,2016-03-17 11:32:17.933 ThaliTest[1258:2789222] multipeer manager: restart client
,2016-03-17 11:32:17.942 ThaliTest[1258:2789222] client: found existing peer: 20B211DA-8CC3-44A8-A409-C300A017DFDB:6
,2016-03-17 11:32:37.933 ThaliTest[1258:2789222] multipeer manager: restart client
,2016-03-17 11:32:37.943 ThaliTest[1258:2789222] client: found existing peer: 20B211DA-8CC3-44A8-A409-C300A017DFDB:6
,2016-03-17 11:32:57.933 ThaliTest[1258:2789222] multipeer manager: restart client
,2016-03-17 11:32:57.942 ThaliTest[1258:2789222] client: found existing peer: 20B211DA-8CC3-44A8-A409-C300A017DFDB:6
,2016-03-17 11:33:17.933 ThaliTest[1258:2789222] multipeer manager: restart client
,2016-03-17 11:33:17.942 ThaliTest[1258:2789222] client: found existing peer: 20B211DA-8CC3-44A8-A409-C300A017DFDB:6
,2016-03-17 11:33:37.933 ThaliTest[1258:2789222] multipeer manager: restart client
,2016-03-17 11:33:37.942 ThaliTest[1258:2789222] client: found existing peer: 20B211DA-8CC3-44A8-A409-C300A017DFDB:6
,2016-03-17 11:33:57.933 ThaliTest[1258:2789222] multipeer manager: restart client
,2016-03-17 11:33:57.942 ThaliTest[1258:2789222] client: found existing peer: 20B211DA-8CC3-44A8-A409-C300A017DFDB:6
,2016-03-17 11:34:17.933 ThaliTest[1258:2789222] multipeer manager: restart client
,2016-03-17 11:34:17.942 ThaliTest[1258:2789222] client: found existing peer: 20B211DA-8CC3-44A8-A409-C300A017DFDB:6
,2016-03-17 11:34:37.934 ThaliTest[1258:2789222] multipeer manager: restart client
,2016-03-17 11:34:37.942 ThaliTest[1258:2789222] client: found existing peer: 20B211DA-8CC3-44A8-A409-C300A017DFDB:6
,2016-03-17 11:34:57.933 ThaliTest[1258:2789222] multipeer manager: restart client
,2016-03-17 11:35:17.933 ThaliTest[1258:2789222] multipeer manager: restart client
,2016-03-17 11:35:17.942 ThaliTest[1258:2789222] client: found existing peer: 20B211DA-8CC3-44A8-A409-C300A017DFDB:6
,2016-03-17 11:35:37.933 ThaliTest[1258:2789222] multipeer manager: restart client
,2016-03-17 11:35:37.943 ThaliTest[1258:2789222] client: found existing peer: 20B211DA-8CC3-44A8-A409-C300A017DFDB:6
,2016-03-17 11:35:57.933 ThaliTest[1258:2789222] multipeer manager: restart client
,2016-03-17 11:35:57.944 ThaliTest[1258:2789222] client: found existing peer: 20B211DA-8CC3-44A8-A409-C300A017DFDB:6
,2016-03-17 11:36:17.933 ThaliTest[1258:2789222] multipeer manager: restart client
,2016-03-17 11:36:37.933 ThaliTest[1258:2789222] multipeer manager: restart client
,2016-03-17 11:36:37.943 ThaliTest[1258:2789222] client: found existing peer: 20B211DA-8CC3-44A8-A409-C300A017DFDB:6
,2016-03-17 11:36:57.933 ThaliTest[1258:2789222] multipeer manager: restart client
,2016-03-17 11:37:17.933 ThaliTest[1258:2789222] multipeer manager: restart client
,2016-03-17 11:37:17.942 ThaliTest[1258:2789222] client: found existing peer: 20B211DA-8CC3-44A8-A409-C300A017DFDB:6
,2016-03-17 11:37:37.933 ThaliTest[1258:2789222] multipeer manager: restart client
,2016-03-17 11:37:37.942 ThaliTest[1258:2789222] client: found existing peer: 20B211DA-8CC3-44A8-A409-C300A017DFDB:6
,2016-03-17 11:37:57.933 ThaliTest[1258:2789222] multipeer manager: restart client
,2016-03-17 11:37:57.943 ThaliTest[1258:2789222] client: found existing peer: 20B211DA-8CC3-44A8-A409-C300A017DFDB:6
,2016-03-17 11:38:17.933 ThaliTest[1258:2789222] multipeer manager: restart client

```
