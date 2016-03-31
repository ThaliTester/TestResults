#### Test 645312549bcf247_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/645312549bcf247/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/8B459370-65C5-4B47-A309-40BC62ECFB21/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/8B459370-65C5-4B47-A309-40BC62ECFB21/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/645312549bcf247/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/645312549bcf247/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/EB7E0FD7-58F9-4489-84D1-A78523C9798B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49485"
,(lldb)     command script import "/tmp/8B459370-65C5-4B47-A309-40BC62ECFB21/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-31 01:47:08.418 ThaliTest[1897:4857928] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/40F71756-B7C2-4BAE-9CD5-8F6D6B4EA5BF/Library/Cookies/Cookies.binarycookies
,2016-03-31 01:47:08.778 ThaliTest[1897:4857928] Apache Cordova native platform version 4.1.0 is starting.
2016-03-31 01:47:08.780 ThaliTest[1897:4857928] Multi-tasking -> Device: YES, App: YES
,2016-03-31 01:47:08.796 ThaliTest[1897:4857928] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-31 01:47:09.958 ThaliTest[1897:4857928] Using UIWebView
2016-03-31 01:47:09.962 ThaliTest[1897:4857928] [CDVTimer][handleopenurl] 0.248969ms
2016-03-31 01:47:09.966 ThaliTest[1897:4857928] [CDVTimer][intentandnavigationfilter] 4.251957ms
2016-03-31 01:47:09.967 ThaliTest[1897:4857928] [CDVTimer][gesturehandler] 0.191987ms
2016-03-31 01:47:09.967 ThaliTest[1897:4857928] [CDVTimer][TotalPluginStartup] 5.495012ms
,2016-03-31 01:47:14.919 ThaliTest[1897:4857928] Resetting plugins due to page load.
,2016-03-31 01:47:16.985 ThaliTest[1897:4857928] Finished load of: file:///var/mobile/Containers/Bundle/Application/EB7E0FD7-58F9-4489-84D1-A78523C9798B/ThaliTest.app/www/index.html
,2016-03-31 01:47:17.173 ThaliTest[1897:4857928] JXcore Cordova plugin initializing
,2016-03-31 01:47:17.174 ThaliTest[1897:4858059] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
JXcore engine is started
,2016-03-31 01:47:32.037 ThaliTest[1897:4858059] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-31 01:47:32.039 ThaliTest[1897:4858059] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-31 01:47:32.040 ThaliTest[1897:4858059] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-31 01:47:32.043 ThaliTest[1897:4858059] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EB7E0FD7-58F9-4489-84D1-A78523C9798B/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EB7E0FD7-58F9-4489-84D1-A78523C9798B/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EB7E0FD7-58F9-4489-84D1-A78523C9798B/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EB7E0FD7-58F9-4489-84D1-A78523C9798B/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EB7E0FD7-58F9-4489-84D1-A78523C9798B/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EB7E0FD7-58F9-4489-84D1-A78523C9798B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EB7E0FD7-58F9-4489-84D1-A78523C9798B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EB7E0FD7-58F9-4489-84D1-A78523C9798B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EB7E0FD7-58F9-4489-84D1-A78523C9798B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EB7E0FD7-58F9-4489-84D1-A78523C9798B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EB7E0FD7-58F9-4489-84D1-A78523C9798B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EB7E0FD7-58F9-4489-84D1-A78523C9798B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EB7E0FD7-58F9-4489-84D1-A78523C9798B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EB7E0FD7-58F9-4489-84D1-A78523C9798B/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EB7E0FD7-58F9-4489-84D1-A78523C9798B/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EB7E0FD7-58F9-4489-84D1-A78523C9798B/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EB7E0FD7-58F9-4489-84D1-A78523C9798B/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EB7E0FD7-58F9-4489-84D1-A78523C9798B/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EB7E0FD7-58F9-4489-84D1-A78523C9798B/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EB7E0FD7-58F9-4489-84D1-A78523C9798B/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EB7E0FD7-58F9-4489-84D1-A78523C9798B/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-31 01:47:44.215 ThaliTest[1897:4857928] THREAD WARNING: ['JXcore'] took '11495.884277' ms. Plugin should use a background thread.
,2016-03-31 01:47:44.217 ThaliTest[1897:4858038] void SendDelegateMessage(NSInvocation *): delegate (webView:decidePolicyForNavigationAction:request:frame:decisionListener:) failed to return after waiting 10 seconds. main run loop mode: kCFRunLoopDefaultMode
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55570
ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55572
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,ok 2 initial connection state should be CONNECTED
,DEBUG createNativeListener: incoming socket close
,ok 3 final connection state should be DISCONNECTED
,# teardown
,# setup
,# 3. emits routerPortConnectionFailed
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55575
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: 
ok 4 tried to connect to right port
ok 5 failed due to refused connection
ok 6 routerPortConnectionFailed is emitted
,# teardown
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,# setup
DEBUG createNativeListener: incoming socket close
,# 4. native server connections all up
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55579
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,ok 7 Send/recvd #1 should be equal length
ok 8 Send/recvd #1 should be same
ok 9 Send/recvd #2 should be equal length
ok 10 Send/recvd #2 should be same
ok 11 Should be exactly 2 client sockets
,# teardown
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
# setup
DEBUG createNativeListener: incoming socket close
,# 5. native server - closing incoming stream cleans outgoing socket
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55584
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,ok 12 socket shouldn't close until after stream
ok 13 incoming remains open
# teardown
,DEBUG createNativeListener: mux close
# setup
DEBUG createNativeListener: incoming socket close
,# 6. native server - closing incoming connection cleans outgoing socket
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55588
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 14 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: incoming socket close
,ok 15 socket shouldn't close until after incoming
ok 16 incoming is cleaned up
# teardown
,# setup
,# 7. native server - closing outgoing socket cleans associated mux stream
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55592
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,ok 17 stream was closed
ok 18 incoming should survive
ok 19 mux should have no streams
,# teardown
,DEBUG createNativeListener: mux close
# setup
DEBUG createNativeListener: incoming socket close
,# 8. native server - closing the whole server cleans everything up
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 55596
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 20 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,ok 21 Buffers are identical
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
ok 22 native server is nulled out
ok 23 native server should be closed
ok 24 incoming has been removed
ok 25 Incoming should be done
ok 26 The mux object should be closed
ok 27 The mux stream should be closed
DEBUG createNativeListener: incoming socket close
,# teardown
,# setup
,# 9. native server - we can get a ton of connections and data through and still clean up the server completely
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 55600
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new, incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new ,outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DE,BUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DE,BUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DE,BUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
ok 28 ,native server is nulled out
ok 29 native server should be closed
ok 30 incoming has been removed
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
,DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
,# teardown
,# setup
,# 10. native server - simulate mux failure, make sure everything is cleaned up
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55652
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 31 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,ok 32 Buffers are identical
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
,DEBUG createNativeListener: incoming socket close
,ok 33 server should be fine
,ok 34 server should be open
,ok 35 incoming has been removed
,ok 36 The mux object should be closed
,ok 37 The mux stream should be closed
,# teardown
,# setup
,# 11. native server - timing out the incoming connection cleans everything up
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55656
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,ok 38 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,ok 39 Buffers are identical
,DEBUG createNativeListener: incoming socket timeout
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: incoming socket close
ok 40 server should be fine
ok 41 server should be open
ok 42 incomi,ng has been removed
ok 43 The mux object should be closed
ok 44 The mux stream should be closed
,# teardown
,# setup
,# 12. closeAll can close even when connections open
,ok 45 not possible to connect to the server anymore
# teardown
,# setup
,# 13. closeAll with promise
,ok 46 not possible to connect to the server anymore
# teardown
,# setup
,# 14. closeAll properly throws when closing a non open server with eatNotRunning set to false
,ok 47 Got the right error
# teardown
,# setup
,# 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true
,# teardown
,# setup
,# 16. enqueue and run in order
,ok 48 firstPromise setTimeout
ok 49 firstPromise result
ok 50 firstPromise testValue
,ok 51 secondPromise setTimeout
ok 52 secondPromise result
ok 53 secondPromise testValue
ok 54 thirdPromise in promise
ok 55 thirdPromise result
ok 56 thirdPromise testValue
,# teardown
,# setup
,# 17. enqueueAtTop and run backwards
,ok 57 thirdPromise - first to run
ok 58 thirdPromise - in resolve
ok 59 secondPromise - second to run
ok 60 secondPromise - in catch
ok 61 firstPromise - third to run
ok 62 firstPromise - in then
ok 63 testing promises
,# teardown
,# setup
,# 18. mix enqueue and enqueueAtTop
,ok 64 fourth
ok 65 fourth
ok 66 second
ok 67 secondPromise - in then
,ok 68 first
,ok 69 firstPromise - in catch
ok 70 third
ok 71 thirdPromise - in then
ok 72 testingPromises
# teardown
,# setup
,# 19. queues handled independently
,ok 73 all short operations completed before the long resolves
# teardown
,# setup
,# 20. basic
,ok 74 sane
# teardown
,# setup
,# 21. another
,ok 75 sane
,# teardown
,# setup
,# 22. can pass data in setup
,ok 76 test participant has uuid
ok 77 participant data matches
ok 78 test participant has uuid
ok 79 participant data matches
ok 80 test participant has uuid
ok 81 participant data matches
ok 82 own UUID is found from the participants list
# teardown
,# setup
,# 23. #startListeningForAdvertisements should fail if start not called
,ok 83 specific error should be returned
# teardown
,ok 84 error should be null
ok 85 error should be null
# setup
,# 24. #startUpdateAdvertisingAndListening should fail if start not called
,ok 86 specific error should be returned
# teardown
,ok 87 error should be null
,ok 88 error should be null
# setup
,# 25. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55666
2016-03-31 01:50:22.198 ThaliTest[1897:4858059] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 01:50:22.199 ThaliTest[1897:4858059] jxcore: stopListeningForAdvertisements: success
,ok 89 error should be null
ok 90 error should be null
2016-03-31 01:50:22.204 ThaliTest[1897:4858059] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 01:50:22.205 ThaliTest[1897:4858059] jxcore: stopListeningForAdvertisements: success
ok 91 error should be null
ok 92 error should be null
# teardown
,2016-03-31 01:50:22.386 ThaliTest[1897:4858059] jxcore: stopAdvertisingAndListening
2016-03-31 01:50:22.387 ThaliTest[1897:4858059] THEMultipeerManager stopping peer
2016-03-31 01:50:22.387 ThaliTest[1897:4858059] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-31 01:50:22.387 ThaliTest[1897:4858059] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 01:50:22.388 ThaliTest[1897,:4858059] jxcore: stopListeningForAdvertisements: success
ok 93 error should be null
ok 94 error should be null
,# setup
,# 26. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55668
,2016-03-31 01:50:22.709 ThaliTest[1897:4858059] jxcore: startListeningForAdvertisements
,2016-03-31 01:50:22.711 ThaliTest[1897:4858059] multipeer manager: start client restart timer: 0x17db5a20
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 01:50:22.714 ThaliTest[1897:4858059] jxcore: startListeningForAdvertisements: success
,ok 95 error should be null
ok 96 error should be null
2016-03-31 01:50:22.727 ThaliTest[1897:4858059] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 01:50:22.728 ThaliTest[1897:4858059] jxcore: startListeningForAdvertisements: success
ok 97 error should be null
ok 98 error should be null
,# teardown
,2016-03-31 01:50:22.863 ThaliTest[1897:4858059] jxcore: stopAdvertisingAndListening
2016-03-31 01:50:22.863 ThaliTest[1897:4858059] THEMultipeerManager stopping peer
2016-03-31 01:50:22.863 ThaliTest[1897:4858059] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-31 01:50:22.864 ThaliTest[1897:4858059] jxcore: stopListeningForAdvertisements
2016-03-31 01:50:22.864 ThaliTest[1897:4858059] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-31 01:50:22.865 ThaliTest[1897:4858059] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 99 error should be null
ok 100 error should be null
# setup
,# 27. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 55670
,2016-03-31 01:50:23.642 ThaliTest[1897:4858059] jxcore: startUpdateAdvertisingAndListening
2016-03-31 01:50:23.642 ThaliTest[1897:4858059] server: starting 42E93D78-2507-4BE0-9192-FC412A882204:1
2016-03-31 01:50:23.642 ThaliTest[1897:4858059] multipeer m,anager: start client restart timer: 0x17db5a20
2016-03-31 01:50:23.643 ThaliTest[1897:4858059] THEMultipeerManager initialized peer 42E93D78-2507-4BE0-9192-FC412A882204:1
2016-03-31 01:50:23.643 ThaliTest[1897:4858059] jxcore: startUpdateAdvertisingAndLi,stening: success
,ok 101 error should be null
,ok 102 error should be null
,2016-03-31 01:50:23.711 ThaliTest[1897:4858059] jxcore: startUpdateAdvertisingAndListening
,2016-03-31 01:50:23.711 ThaliTest[1897:4858059] THEMultipeerManager stopping peer
,2016-03-31 01:50:23.713 ThaliTest[1897:4858059] multipeer manager: stop client timer
,2016-03-31 01:50:23.715 ThaliTest[1897:4858059] server: starting 42E93D78-2507-4BE0-9192-FC412A882204:2
,2016-03-31 01:50:23.718 ThaliTest[1897:4858059] multipeer manager: start client restart timer: 0x17db5a20
,2016-03-31 01:50:23.724 ThaliTest[1897:4858059] THEMultipeerManager initialized peer 42E93D78-2507-4BE0-9192-FC412A882204:2
,2016-03-31 01:50:23.726 ThaliTest[1897:4858059] jxcore: startUpdateAdvertisingAndListening: success
,ok 103 error should be null
ok 104 error should be null
,# teardown
,2016-03-31 01:50:24.606 ThaliTest[1897:4858059] jxcore: stopAdvertisingAndListening
2016-03-31 01:50:24.607 ThaliTest[1897:4858059] THEMultipeerManager stopping peer
2016-03-31 01:50:24.607 ThaliTest[1897:4858059] multipeer manager: stop client timer
20,16-03-31 01:50:24.607 ThaliTest[1897:4858059] jxcore: stopAdvertisingAndListening: success
2016-03-31 01:50:24.607 ThaliTest[1897:4858059] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-31 01:50:24.608 ThaliTest[1897:4858059] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 105 error should be null
ok 106 error should be null
# setup
,# 28. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 55675
,2016-03-31 01:50:25.253 ThaliTest[1897:4858059] jxcore: stopAdvertisingAndListening
,2016-03-31 01:50:25.254 ThaliTest[1897:4858059] THEMultipeerManager stopping peer
,2016-03-31 01:50:25.255 ThaliTest[1897:4858059] jxcore: stopAdvertisingAndListening: success
,ok 107 error should be null
,ok 108 error should be null
,2016-03-31 01:50:25.259 ThaliTest[1897:4858059] jxcore: stopAdvertisingAndListening
,2016-03-31 01:50:25.261 ThaliTest[1897:4858059] THEMultipeerManager stopping peer
,2016-03-31 01:50:25.262 ThaliTest[1897:4858059] jxcore: stopAdvertisingAndListening: success
,ok 109 error should be null
,ok 110 error should be null
,# teardown
,2016-03-31 01:50:25.662 ThaliTest[1897:4858059] jxcore: stopAdvertisingAndListening
2016-03-31 01:50:25.662 ThaliTest[1897:4858059] THEMultipeerManager stopping peer
2016-03-31 01:50:25.662 ThaliTest[1897:4858059] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-31 01:50:25.663 ThaliTest[1897:4858059] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 01:50:25.664 ThaliTest[1897,:4858059] jxcore: stopListeningForAdvertisements: success
,ok 111 error should be null
,ok 112 error should be null
,# setup
,# 29. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 55677
ok 113 first call should succeed
ok 114 first call should succeed
ok 115 specific error should be returned
# teardown
,2016-03-31 01:50:27.283 ThaliTest[1897:4858059] jxcore: stopAdvertisingAndListening
2016-03-31 01:50:27.283 ThaliTest[1897:4858059] THEMultipeerManager stopping peer
2016-03-31 01:50:27.284 ThaliTest[1897:4858059] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-31 01:50:27.284 ThaliTest[1897:4858059] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 01:50:27.285 ThaliTest[1897:4858059] jxcore: stopListeningForAdvertisements: success
ok 116 error should be null
ok 117 error should be null
,# setup
,# 30. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55679
2016-03-31 01:50:27.753 ThaliTest[1897:4858059] jxcore: startListeningForAdvertisements
2016-03-31 01:50:27.753 ThaliTest[1897:4858059] multipeer manager: start client restart timer: 0x17db5a20
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 01:50:27.757 ThaliTest[1897:4858059] jxcore: startListeningForAdvertisements: success
,2016-03-31 01:50:27.790 ThaliTest[1897:4858059] jxcore: startUpdateAdvertisingAndListening
2016-03-31 01:50:27.790 ThaliTest[1897:4858059] server: starting 42E93D78-2507-4BE0-9192-FC412A882204:3
2016-03-31 01:50:27.790 ThaliTest[1897:4858059] THEMultipee,rManager initialized peer 42E93D78-2507-4BE0-9192-FC412A882204:3
2016-03-31 01:50:27.790 ThaliTest[1897:4858059] jxcore: startUpdateAdvertisingAndListening: success
,ok 118 called only once
ok 119 discovery state matches
ok 120 advertising state matches
# teardown
,2016-03-31 01:50:27.879 ThaliTest[1897:4858059] jxcore: stopAdvertisingAndListening
2016-03-31 01:50:27.880 ThaliTest[1897:4858059] THEMultipeerManager stopping peer
2016-03-31 01:50:27.880 ThaliTest[1897:4858059] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-31 01:50:27.880 ThaliTest[1897:4858059] jxcore: stopListeningForAdvertisements
2016-03-31 01:50:27.881 ThaliTest[1897:4858059] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-31 01:50:27.882 ThaliTest[1897:4858059] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 121 error should be null
,ok 122 error should be null
,# setup
,# 31. does not send duplicate availability changes
,ok 123 should be called once
ok 124 should not have been called more than once
# teardown
,ok 125 error should be null
ok 126 error should be null
# setup
,# 32. can get the network status
,ok 127 network status should have certain non-empty properties
# teardown
,ok 128 error should be null
,ok 129 error should be null
,# setup
,# 33. wifi peer is marked unavailable if announcements stop
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
,ok 130 host address should match
ok 131 port should match
,ok 132 host address should be null
,ok 133 port should should be null
,# teardown
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 134 error should be null
ok 135 error should be null
,# setup
,# 34. Can call start/stopListeningForAdvertisements
,2016-03-31 01:50:57.589 ThaliTest[1897:4858059] jxcore: startListeningForAdvertisements
2016-03-31 01:50:57.589 ThaliTest[1897:4858059] multipeer manager: start client restart timer: 0x17db5a20
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 01:50:57.590 ThaliTest[1897:4858059] jxcore: startListeningForAdvertisements: success
ok 136 Can call startListeningForAdvertisements without error
2016-03-31 01:50:57.591 ThaliTes,t[1897:4858059] jxcore: stopListeningForAdvertisements
2016-03-31 01:50:57.591 ThaliTest[1897:4858059] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive,":false}
2016-03-31 01:50:57.592 ThaliTest[1897:4858059] jxcore: stopListeningForAdvertisements: success
ok 137 Can call stopListeningForAdvertisements without error
# teardown
,2016-03-31 01:50:57.711 ThaliTest[1897:4858059] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 01:50:57.712 ThaliTest[1897:4858059] jxcore: stopListeningForAdvertisements: success
ok 138 Should be able to call stopListeningForAdvertisements in teardown
2016-03-31 01:50:57.713 ThaliTest[1897:4858059] jxcore: stopAdvertisingAndListening
2016-03-31 01:50:57.713 ThaliTest[1897:48580,59] THEMultipeerManager stopping peer
2016-03-31 01:50:57.713 ThaliTest[1897:4858059] jxcore: stopAdvertisingAndListening: success
ok 139 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 35. Calling startListeningForAdvertisements twice is NOT an error
,2016-03-31 01:50:57.999 ThaliTest[1897:4858059] jxcore: startListeningForAdvertisements
2016-03-31 01:50:58.000 ThaliTest[1897:4858059] multipeer manager: start client restart timer: 0x17db5a20
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 01:50:58.001 ThaliTest[1897:4858059] jxcore: startListeningForAdvertisements: success
ok 140 Can call startListeningForAdvertisements without error
2016-03-31 01:50:58.002 ThaliTes,t[1897:4858059] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 01:50:58.003 ThaliTest[1897:4858059] jxcore: startListeningForAdv,ertisements: success
ok 141 Can call startListeningForAdvertisements twice without error
# teardown
,2016-03-31 01:50:58.385 ThaliTest[1897:4858059] jxcore: stopListeningForAdvertisements
2016-03-31 01:50:58.385 ThaliTest[1897:4858059] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 01:50:58.386 ThaliTest[1897:4858059] jxcore: stopListeningForAdvertisements: success
ok 142 Should be able to call stopListeningForAdvertisements in teardown
2016-03-31 01:50:58.387 ThaliTest[1897:4858,059] jxcore: stopAdvertisingAndListening
2016-03-31 01:50:58.387 ThaliTest[1897:4858059] THEMultipeerManager stopping peer
2016-03-31 01:50:58.387 ThaliTest[1897:4858059] jxcore: stopAdvertisingAndListening: success
ok 143 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 36. Calling stopListeningForAdvertisements without calling start is NOT an error
,2016-03-31 01:51:15.038 ThaliTest[1897:4858059] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 01:51:15.039 ThaliTest[1897:48580,59] jxcore: stopListeningForAdvertisements: success
ok 144 Can call stopListeningForAdvertisements without error
2016-03-31 01:51:15.040 ThaliTest[1897:4858059] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingS,tateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 01:51:15.041 ThaliTest[1897:4858059] jxcore: stopListeningForAdvertisements: success
ok 145 Can call stopListeningForAdvertisements without error
# teardown
,2016-03-31 01:51:18.599 ThaliTest[1897:4858059] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 01:51:18.600 ThaliTest[1897:48580,59] jxcore: stopListeningForAdvertisements: success
ok 146 Should be able to call stopListeningForAdvertisements in teardown
2016-03-31 01:51:18.601 ThaliTest[1897:4858059] jxcore: stopAdvertisingAndListening
2016-03-31 01:51:18.601 ThaliTest[1897:48580,59] THEMultipeerManager stopping peer
2016-03-31 01:51:18.601 ThaliTest[1897:4858059] jxcore: stopAdvertisingAndListening: success
ok 147 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 37. Can call start/stopUpdateAdvertisingAndListening
,2016-03-31 01:51:18.823 ThaliTest[1897:4858059] jxcore: startUpdateAdvertisingAndListening
2016-03-31 01:51:18.823 ThaliTest[1897:4858059] server: starting 42E93D78-2507-4BE0-9192-FC412A882204:4
2016-03-31 01:51:18.824 ThaliTest[1897:4858059] multipeer m,anager: start client restart timer: 0x17db5a20
2016-03-31 01:51:18.824 ThaliTest[1897:4858059] THEMultipeerManager initialized peer 42E93D78-2507-4BE0-9192-FC412A882204:4
2016-03-31 01:51:18.824 ThaliTest[1897:4858059] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 148 Can call startUpdateAdvertisingAndListening without error
2016-03-31 01:51:18.825 ThaliTest[1897:4858059] jxcore: stopAdvertisingAndListening
2016-03-31 01:51:18.826 ThaliTest[1897:4858059] THEMultipeerManager stopping peer
,2016-03-31 01:51:18.826 ThaliTest[1897:4858059] multipeer manager: stop client timer
2016-03-31 01:51:18.832 ThaliTest[1897:4858059] jxcore: stopAdvertisingAndListening: success
ok 149 Can call stopAdvertisingAndListening without error
# teardown
,2016-03-31 01:51:18.942 ThaliTest[1897:4858059] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-31 01:51:18.944 ThaliTest[1897:4858059] jxcore: stopListeningForAdvertisements: success
,ok 150 Should be able to call stopListeningForAdvertisements in teardown
,2016-03-31 01:51:18.945 ThaliTest[1897:4858059] jxcore: stopAdvertisingAndListening
2016-03-31 01:51:18.946 ThaliTest[1897:4858059] THEMultipeerManager stopping peer
2016-03-31 01:51:18.946 ThaliTest[1897:4858059] jxcore: stopAdvertisingAndListening: success
ok 151 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-03-31 01:51:19.324 ThaliTest[1897:4858059] jxcore: startUpdateAdvertisingAndListening
2016-03-31 01:51:19.325 ThaliTest[1897:4858059] server: starting 42E93D78-2507-4BE0-9192-FC412A882204:5
2016-03-31 01:51:19.325 ThaliTest[1897:4858059] multipeer m,anager: start client restart timer: 0x17db5a20
2016-03-31 01:51:19.325 ThaliTest[1897:4858059] THEMultipeerManager initialized peer 42E93D78-2507-4BE0-9192-FC412A882204:5
2016-03-31 01:51:19.325 ThaliTest[1897:4858059] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 152 Can call startUpdateAdvertisingAndListening without error
2016-03-31 01:51:19.327 ThaliTest[1897:4858059] jxcore: startUpdateAdvertisingAndListening
2016-03-31 01:51:19.327 ThaliTest[1897:4858059] THEMultipeerManager stopping pee,r
,2016-03-31 01:51:19.327 ThaliTest[1897:4858059] multipeer manager: stop client timer
2016-03-31 01:51:19.333 ThaliTest[1897:4858059] server: starting 42E93D78-2507-4BE0-9192-FC412A882204:6
2016-03-31 01:51:19.333 ThaliTest[1897:4858059] multipeer manager,: start client restart timer: 0x17db5a20
2016-03-31 01:51:19.333 ThaliTest[1897:4858059] THEMultipeerManager initialized peer 42E93D78-2507-4BE0-9192-FC412A882204:6
2016-03-31 01:51:19.333 ThaliTest[1897:4858059] jxcore: startUpdateAdvertisingAndListenin,g: success
ok 153 Can call startUpdateAdvertisingAndListening twice without error
# teardown
,2016-03-31 01:51:19.698 ThaliTest[1897:4858059] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-31 01:51:19.699 ThaliTest[1897:485805,9] jxcore: stopListeningForAdvertisements: success
ok 154 Should be able to call stopListeningForAdvertisements in teardown
2016-03-31 01:51:19.700 ThaliTest[1897:4858059] jxcore: stopAdvertisingAndListening
2016-03-31 01:51:19.700 ThaliTest[1897:485805,9] THEMultipeerManager stopping peer
2016-03-31 01:51:19.701 ThaliTest[1897:4858059] multipeer manager: stop client timer
2016-03-31 01:51:19.701 ThaliTest[1897:4858059] jxcore: stopAdvertisingAndListening: success
ok 155 Should be able to call stopAdve,rtisingAndListening in teardown
# setup
,# 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,2016-03-31 01:51:21.402 ThaliTest[1897:4858059] jxcore: stopAdvertisingAndListening
2016-03-31 01:51:21.403 ThaliTest[1897:4858059] THEMultipeerManager stopping peer
2016-03-31 01:51:21.403 ThaliTest[1897:4858059] jxcore: stopAdvertisingAndListening: suc,cess
ok 156 Can call startUpdateAdvertisingAndListening without error
2016-03-31 01:51:21.404 ThaliTest[1897:4858059] jxcore: stopAdvertisingAndListening
2016-03-31 01:51:21.404 ThaliTest[1897:4858059] THEMultipeerManager stopping peer
2016-03-31 01:51,:21.404 ThaliTest[1897:4858059] jxcore: stopAdvertisingAndListening: success
ok 157 Can call stopAdvertisingAndListening without error
# teardown
,2016-03-31 01:51:38.297 ThaliTest[1897:4858059] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 01:51:38.298 ThaliTest[1897:48580,59] jxcore: stopListeningForAdvertisements: success
ok 158 Should be able to call stopListeningForAdvertisements in teardown
2016-03-31 01:51:38.299 ThaliTest[1897:4858059] jxcore: stopAdvertisingAndListening
2016-03-31 01:51:38.299 ThaliTest[1897:48580,59] THEMultipeerManager stopping peer
2016-03-31 01:51:38.299 ThaliTest[1897:4858059] jxcore: stopAdvertisingAndListening: success
ok 159 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 40. cannot call connect when start listening for advertisements is not active
,2016-03-31 01:51:38.587 ThaliTest[1897:4858059] jxcore: connect foo
2016-03-31 01:51:38.588 ThaliTest[1897:4858059] jxcore: connect: fail: Start browsing first
not ok 160 got right error
  ---
    operator: equal
    expected: 'startListeningForAdvertisements is not active'
    actual:   'Start browsing first'
  ...
,# teardown
,2016-03-31 01:51:38.699 ThaliTest[1897:4858059] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 01:51:38.700 ThaliTest[1897:4858059] jxcore: stopListeningForAdvertisements: success
,ok 161 Should be able to call stopListeningForAdvertisements in teardown
2016-03-31 01:51:38.701 ThaliTest[1897:4858059] jxcore: stopAdvertisingAndListening
,2016-03-31 01:51:38.702 ThaliTest[1897:4858059] THEMultipeerManager stopping peer
,2016-03-31 01:51:38.702 ThaliTest[1897:4858059] jxcore: stopAdvertisingAndListening: success
,ok 162 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 41. peerAvailabilityChange is called
,2016-03-31 01:51:38.996 ThaliTest[1897:4858059] jxcore: startUpdateAdvertisingAndListening
2016-03-31 01:51:38.996 ThaliTest[1897:4858059] server: starting 42E93D78-2507-4BE0-9192-FC412A882204:7
2016-03-31 01:51:38.996 ThaliTest[1897:4858059] multipeer m,anager: start client restart timer: 0x17db5a20
2016-03-31 01:51:38.997 ThaliTest[1897:4858059] THEMultipeerManager initialized peer 42E93D78-2507-4BE0-9192-FC412A882204:7
2016-03-31 01:51:38.997 ThaliTest[1897:4858059] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 163 Can call startUpdateAdvertisingAndListeningwithout error
2016-03-31 01:51:38.998 ThaliTest[1897:4858059] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertising,Active":true,"discoveryActive":true}
2016-03-31 01:51:38.999 ThaliTest[1897:4858059] jxcore: startListeningForAdvertisements: success
ok 164 Can call startListeningForAdvertisements without error
,2016-03-31 01:51:43.291 ThaliTest[1897:4857928] client: found new peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:7
ok 165 peers must be an array
ok 166 peers must not be zero-length
ok 167 peer must have peerIdentifier
ok 168 peerIdentifier must be a string
ok 169 peer must have peerAvailable
ok 170 peer must have pleaseConnect
,# teardown
,2016-03-31 01:51:43.461 ThaliTest[1897:4858059] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-31 01:51:43.462 ThaliTest[1897:485805,9] jxcore: stopListeningForAdvertisements: success
ok 171 Should be able to call stopListeningForAdvertisements in teardown
2016-03-31 01:51:43.463 ThaliTest[1897:4858059] jxcore: stopAdvertisingAndListening
2016-03-31 01:51:43.463 ThaliTest[1897:485805,9] THEMultipeerManager stopping peer
2016-03-31 01:51:43.463 ThaliTest[1897:4858059] multipeer manager: stop client timer
2016-03-31 01:51:43.463 ThaliTest[1897:4858059] jxcore: stopAdvertisingAndListening: success
ok 172 Should be able to call stopAdve,rtisingAndListening in teardown
# setup
,# 42. Can connect to a remote peer
,2016-03-31 01:51:43.930 ThaliTest[1897:4858059] jxcore: startUpdateAdvertisingAndListening
2016-03-31 01:51:43.930 ThaliTest[1897:4858059] server: starting 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:51:43.931 ThaliTest[1897:4858059] multipeer m,anager: start client restart timer: 0x17db5a20
2016-03-31 01:51:43.931 ThaliTest[1897:4858059] THEMultipeerManager initialized peer 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:51:43.932 ThaliTest[1897:4858059] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 173 Can call startUpdateAdvertisingAndListening without error
2016-03-31 01:51:43.933 ThaliTest[1897:4858059] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisin,gActive":true,"discoveryActive":true}
2016-03-31 01:51:43.934 ThaliTest[1897:4858059] jxcore: startListeningForAdvertisements: success
ok 174 Can call startListeningForAdvertisements without error
,2016-03-31 01:51:44.613 ThaliTest[1897:4857928] client: found new peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"25ECEE51-730A-4F4F-BA49-ACDAF32AF,B41:7","pleaseConnect":0}]
2016-03-31 01:51:44.615 ThaliTest[1897:4858059] jxcore: connect 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:7
2016-03-31 01:51:44.615 ThaliTest[1897:4858059] client session: connect
2016-03-31 01:51:44.616 ThaliTest[1897:4858059] client session: stateChange:0->1 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:7
,2016-03-31 01:51:45.276 ThaliTest[1897:4857928] client: found new peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"9BF3B351-B42F-4B62-994E-93C3F024E3C4:8","pleaseConnect":0}]
,2016-03-31 01:51:45.378 ThaliTest[1897:4859441] client session: not connected 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:7
2016-03-31 01:51:45.380 ThaliTest[1897:4859441] client session: onLinkFailure: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41
2016-03-31 01:51:45.3,80 ThaliTest[1897:4859441] client session: disconnect
2016-03-31 01:51:45.380 ThaliTest[1897:4859441] client session: stateChange:1->0 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:7
2016-03-31 01:51:45.381 ThaliTest[1897:4859441] client session: fireConnectCallb,ack: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41
2016-03-31 01:51:45.381 ThaliTest[1897:4859441] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 9
,2016-03-31 01:51:46.245 ThaliTest[1897:4857928] multipeer session: reset timer
2016-03-31 01:51:46.245 ThaliTest[1897:4857928] server: rejecting invitation from 9BF3B351-B42F-4B62-994E-93C3F024E3C4 due to previous generation (42E93D78-2507-4BE0-9192-FC412A882204:8 != 42E93D78-2507-4BE0-9192-FC412A882204:7)
,2016-03-31 01:51:46.251 ThaliTest[1897:4857928] multipeer session: reset timer
2016-03-31 01:51:46.251 ThaliTest[1897:4857928] server: rejecting invitation from 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41 due to previous generation (42E93D78-2507-4BE0-9192-FC412,A882204:8 != 42E93D78-2507-4BE0-9192-FC412A882204:7)
,2016-03-31 01:51:48.393 ThaliTest[1897:4858059] jxcore: connect 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:7
2016-03-31 01:51:48.393 ThaliTest[1897:4858059] client session: connect
2016-03-31 01:51:48.393 ThaliTest[1897:4858059] client session: stateChange:0->,1 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:7
,2016-03-31 01:51:48.536 ThaliTest[1897:4859455] client session: not connected 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:7
2016-03-31 01:51:48.537 ThaliTest[1897:4859455] client session: onLinkFailure: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41
2016-03-31 01:51:48.5,38 ThaliTest[1897:4859455] client session: disconnect
2016-03-31 01:51:48.538 ThaliTest[1897:4859455] client session: stateChange:1->0 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:7
2016-03-31 01:51:48.538 ThaliTest[1897:4859455] client session: fireConnectCallb,ack: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41
2016-03-31 01:51:48.538 ThaliTest[1897:4859455] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-31 01:51:49.638 ThaliTest[1897:4857928] multipeer session: reset timer
2016-03-31 01:51:49.639 ThaliTest[1897:4857928] server: disconnecting to refresh session (9BF3B351-B42F-4B62-994E-93C3F024E3C4)
2016-03-31 01:51:49.639 ThaliTest[1897:4857928] server: rejecting invitation from 9BF3B351-B42F-4B62-994E-93C3F024E3C4 due to previous generation (42E93D78-2507-4BE0-9192-FC412A882204:8 != 42E93D78-2507-4BE0-9192-FC412A882204:7)
,2016-03-31 01:51:51.545 ThaliTest[1897:4858059] jxcore: connect 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:7
2016-03-31 01:51:51.545 ThaliTest[1897:4858059] client session: connect
2016-03-31 01:51:51.545 ThaliTest[1897:4858059] client session: stateChange:0->1 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:7
,2016-03-31 01:51:51.681 ThaliTest[1897:4859458] client session: not connected 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:7
2016-03-31 01:51:51.681 ThaliTest[1897:4859458] client session: onLinkFailure: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41
2016-03-31 01:51:51.6,82 ThaliTest[1897:4859458] client session: disconnect
2016-03-31 01:51:51.682 ThaliTest[1897:4859458] client session: stateChange:1->0 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:7
,2016-03-31 01:51:51.684 ThaliTest[1897:4859458] client session: fireConnectCallback: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41
2016-03-31 01:51:51.684 ThaliTest[1897:4859458] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-31 01:51:53.125 ThaliTest[1897:4857928] multipeer session: reset timer
2016-03-31 01:51:53.125 ThaliTest[1897:4857928] server: disconnecting to refresh session (9BF3B351-B42F-4B62-994E-93C3F024E3C4)
2016-03-31 01:51:53.125 ThaliTest[1897:4857928], server: rejecting invitation from 9BF3B351-B42F-4B62-994E-93C3F024E3C4 due to previous generation (42E93D78-2507-4BE0-9192-FC412A882204:8 != 42E93D78-2507-4BE0-9192-FC412A882204:7)
,2016-03-31 01:51:54.697 ThaliTest[1897:4858059] jxcore: connect 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:7
2016-03-31 01:51:54.697 ThaliTest[1897:4858059] client session: connect
2016-03-31 01:51:54.698 ThaliTest[1897:4858059] client session: stateChange:0->,1 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:7
,2016-03-31 01:51:54.816 ThaliTest[1897:4859458] client session: not connected 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:7
,2016-03-31 01:51:54.820 ThaliTest[1897:4859458] client session: onLinkFailure: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41
,2016-03-31 01:51:54.820 ThaliTest[1897:4859458] client session: disconnect
,2016-03-31 01:51:54.820 ThaliTest[1897:4859458] client session: stateChange:1->0 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:7
,2016-03-31 01:51:54.821 ThaliTest[1897:4859458] client session: fireConnectCallback: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41
,2016-03-31 01:51:54.822 ThaliTest[1897:4859458] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-31 01:51:56.828 ThaliTest[1897:4857928] multipeer session: reset timer
2016-03-31 01:51:56.828 ThaliTest[1897:4857928] server: disconnecting to refresh session (9BF3B351-B42F-4B62-994E-93C3F024E3C4)
2016-03-31 01:51:56.829 ThaliTest[1897:4857928], server: rejecting invitation from 9BF3B351-B42F-4B62-994E-93C3F024E3C4 due to previous generation (42E93D78-2507-4BE0-9192-FC412A882204:8 != 42E93D78-2507-4BE0-9192-FC412A882204:7)
,2016-03-31 01:51:57.830 ThaliTest[1897:4858059] jxcore: connect 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:7
2016-03-31 01:51:57.830 ThaliTest[1897:4858059] client session: connect
2016-03-31 01:51:57.831 ThaliTest[1897:4858059] client session: stateChange:0->,1 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:7
,2016-03-31 01:51:57.942 ThaliTest[1897:4859443] client session: not connected 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:7
2016-03-31 01:51:57.942 ThaliTest[1897:4859443] client session: onLinkFailure: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41
2016-03-31 01:51:57.942 ThaliTest[1897:4859443] client session: disconnect
2016-03-31 01:51:57.942 ThaliTest[1897:4859443] client session: stateChange:1->0 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:7
2016-03-31 01:51:57.943 ThaliTest[1897:4859443] client session: fireConnectCallb,ack: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41
2016-03-31 01:51:57.943 ThaliTest[1897:4859443] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-31 01:51:57.960 ThaliTest[1897:4857928] multipeer session: reset timer
2016-03-31 01:51:57.960 ThaliTest[1897:4857928] server: disconnecting to refresh session (25ECEE51-730A-4F4F-BA49-ACDAF32AFB41)
2016-03-31 01:51:57.960 ThaliTest[1897:4857928], server: rejecting invitation from 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41 due to previous generation (42E93D78-2507-4BE0-9192-FC412A882204:8 != 42E93D78-2507-4BE0-9192-FC412A882204:7)
,2016-03-31 01:51:59.988 ThaliTest[1897:4857928] multipeer session: reset timer
2016-03-31 01:51:59.989 ThaliTest[1897:4857928] server: disconnecting to refresh session (9BF3B351-B42F-4B62-994E-93C3F024E3C4)
2016-03-31 01:51:59.989 ThaliTest[1897:4857928] server: rejecting invitation from 9BF3B351-B42F-4B62-994E-93C3F024E3C4 due to previous generation (42E93D78-2507-4BE0-9192-FC412A882204:8 != 42E93D78-2507-4BE0-9192-FC412A882204:7)
,2016-03-31 01:52:00.953 ThaliTest[1897:4858059] jxcore: connect 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:7
2016-03-31 01:52:00.953 ThaliTest[1897:4858059] client session: connect
2016-03-31 01:52:00.953 ThaliTest[1897:4858059] client session: stateChange:0->,1 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:7
,2016-03-31 01:52:01.532 ThaliTest[1897:4859458] client session: not connected 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:7
2016-03-31 01:52:01.532 ThaliTest[1897:4859458] client session: onLinkFailure: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41
,2016-03-31 01:52:01.532 ThaliTest[1897:4859458] client session: disconnect
,2016-03-31 01:52:01.533 ThaliTest[1897:4859458] client session: stateChange:1->0 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:7
,2016-03-31 01:52:01.535 ThaliTest[1897:4859458] client session: fireConnectCallback: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41
2016-03-31 01:52:01.535 ThaliTest[1897:4859458] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returne,d an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-31 01:52:03.100 ThaliTest[1897:4857928] multipeer session: reset timer
2016-03-31 01:52:03.101 ThaliTest[1897:4857928] server: disconnecting to refresh session (9BF3B351-B42F-4B62-994E-93C3F024E3C4)
2016-03-31 01:52:03.101 ThaliTest[1897:4857928], server: rejecting invitation from 9BF3B351-B42F-4B62-994E-93C3F024E3C4 due to previous generation (42E93D78-2507-4BE0-9192-FC412A882204:8 != 42E93D78-2507-4BE0-9192-FC412A882204:7)
,2016-03-31 01:52:03.932 ThaliTest[1897:4857928] multipeer manager: restart client
,2016-03-31 01:52:03.954 ThaliTest[1897:4857928] client: found updated peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8
,2016-03-31 01:52:03.960 ThaliTest[1897:4857928] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"25ECEE51-730A-4F4F-BA49-ACDA,F32AFB41:8","pleaseConnect":0}]
,2016-03-31 01:52:04.548 ThaliTest[1897:4858059] jxcore: connect 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:7
2016-03-31 01:52:04.548 ThaliTest[1897:4858059] client session: connect
2016-03-31 01:52:04.548 ThaliTest[1897:4858059] client session: stateChange:0->,1 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8
,2016-03-31 01:52:04.678 ThaliTest[1897:4859440] client session: not connected 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8
2016-03-31 01:52:04.678 ThaliTest[1897:4859440] client session: onLinkFailure: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41
2016-03-31 01:52:04.6,79 ThaliTest[1897:4859440] client session: disconnect
2016-03-31 01:52:04.679 ThaliTest[1897:4859440] client session: stateChange:1->0 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8
2016-03-31 01:52:04.682 ThaliTest[1897:4859440] client session: fireConnectCallb,ack: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41
2016-03-31 01:52:04.682 ThaliTest[1897:4859440] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 3
,2016-03-31 01:52:06.226 ThaliTest[1897:4857928] multipeer session: reset timer
2016-03-31 01:52:06.227 ThaliTest[1897:4857928] server: disconnecting to refresh session (9BF3B351-B42F-4B62-994E-93C3F024E3C4)
2016-03-31 01:52:06.227 ThaliTest[1897:4857928] server: rejecting invitation from 9BF3B351-B42F-4B62-994E-93C3F024E3C4 due to previous generation (42E93D78-2507-4BE0-9192-FC412A882204:8 != 42E93D78-2507-4BE0-9192-FC412A882204:7)
,2016-03-31 01:52:07.686 ThaliTest[1897:4858059] jxcore: connect 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:7
2016-03-31 01:52:07.686 ThaliTest[1897:4858059] client session: connect
2016-03-31 01:52:07.686 ThaliTest[1897:4858059] client session: stateChange:0->1 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8
,2016-03-31 01:52:07.863 ThaliTest[1897:4859443] client session: not connected 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8
2016-03-31 01:52:07.864 ThaliTest[1897:4859443] client session: onLinkFailure: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41
2016-03-31 01:52:07.8,65 ThaliTest[1897:4859443] client session: disconnect
2016-03-31 01:52:07.865 ThaliTest[1897:4859443] client session: stateChange:1->0 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8
2016-03-31 01:52:07.866 ThaliTest[1897:4859443] client session: fireConnectCallb,ack: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41
2016-03-31 01:52:07.866 ThaliTest[1897:4859443] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-31 01:52:09.426 ThaliTest[1897:4857928] multipeer session: reset timer
2016-03-31 01:52:09.426 ThaliTest[1897:4857928] server: disconnecting to refresh session (9BF3B351-B42F-4B62-994E-93C3F024E3C4)
2016-03-31 01:52:09.427 ThaliTest[1897:4857928] server: rejecting invitation from 9BF3B351-B42F-4B62-994E-93C3F024E3C4 due to previous generation (42E93D78-2507-4BE0-9192-FC412A882204:8 != 42E93D78-2507-4BE0-9192-FC412A882204:7)
,2016-03-31 01:52:10.871 ThaliTest[1897:4858059] jxcore: connect 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:7
2016-03-31 01:52:10.871 ThaliTest[1897:4858059] client session: connect
2016-03-31 01:52:10.871 ThaliTest[1897:4858059] client session: stateChange:0->1 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8
,2016-03-31 01:52:11.010 ThaliTest[1897:4857928] multipeer session: reset timer
2016-03-31 01:52:11.011 ThaliTest[1897:4857928] server: disconnecting to refresh session (25ECEE51-730A-4F4F-BA49-ACDAF32AFB41)
2016-03-31 01:52:11.011 ThaliTest[1897:4857928] server: rejecting invitation from 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41 due to previous generation (42E93D78-2507-4BE0-9192-FC412A882204:8 != 42E93D78-2507-4BE0-9192-FC412A882204:7)
,2016-03-31 01:52:11.028 ThaliTest[1897:4859455] client session: not connected 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8
2016-03-31 01:52:11.029 ThaliTest[1897:4859455] client session: onLinkFailure: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41
2016-03-31 01:52:11.029 ThaliTest[1897:4859455] client session: disconnect
,2016-03-31 01:52:11.030 ThaliTest[1897:4859455] client session: stateChange:1->0 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8
2016-03-31 01:52:11.031 ThaliTest[1897:4859455] client session: fireConnectCallback: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41
2016-03-31 01:52:11.031 ThaliTest[1897:4859455] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-31 01:52:12.522 ThaliTest[1897:4857928] multipeer session: reset timer
2016-03-31 01:52:12.523 ThaliTest[1897:4857928] server: disconnecting to refresh session (9BF3B351-B42F-4B62-994E-93C3F024E3C4)
2016-03-31 01:52:12.523 ThaliTest[1897:4857928], server: rejecting invitation from 9BF3B351-B42F-4B62-994E-93C3F024E3C4 due to previous generation (42E93D78-2507-4BE0-9192-FC412A882204:8 != 42E93D78-2507-4BE0-9192-FC412A882204:7)
,2016-03-31 01:52:14.034 ThaliTest[1897:4858059] jxcore: connect 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:7
2016-03-31 01:52:14.034 ThaliTest[1897:4858059] client session: connect
2016-03-31 01:52:14.035 ThaliTest[1897:4858059] client session: stateChange:0->1 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8
,2016-03-31 01:52:14.279 ThaliTest[1897:4859455] client session: not connected 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8
2016-03-31 01:52:14.280 ThaliTest[1897:4859455] client session: onLinkFailure: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41
2016-03-31 01:52:14.280 ThaliTest[1897:4859455] client session: disconnect
2016-03-31 01:52:14.280 ThaliTest[1897:4859455] client session: stateChange:1->0 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8
2016-03-31 01:52:14.281 ThaliTest[1897:4859455] client session: fireConnectCallb,ack: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41
2016-03-31 01:52:14.281 ThaliTest[1897:4859455] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
WARN testThaliMobileNative: Too many connect retries!
not ok 175 Connect failed!
  ---
    operator: fail
  ...
,# teardown
,2016-03-31 01:52:15.715 ThaliTest[1897:4857928] multipeer session: reset timer
2016-03-31 01:52:15.716 ThaliTest[1897:4857928] server: disconnecting to refresh session (9BF3B351-B42F-4B62-994E-93C3F024E3C4)
2016-03-31 01:52:15.716 ThaliTest[1897:4857928], server: rejecting invitation from 9BF3B351-B42F-4B62-994E-93C3F024E3C4 due to previous generation (42E93D78-2507-4BE0-9192-FC412A882204:8 != 42E93D78-2507-4BE0-9192-FC412A882204:7)
,2016-03-31 01:52:23.932 ThaliTest[1897:4857928] multipeer manager: restart client
,2016-03-31 01:52:23.953 ThaliTest[1897:4857928] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8
,2016-03-31 01:52:23.958 ThaliTest[1897:4857928] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:8
,2016-03-31 01:52:43.932 ThaliTest[1897:4857928] multipeer manager: restart client
,2016-03-31 01:52:43.959 ThaliTest[1897:4857928] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:8
2016-03-31 01:52:43.959 ThaliTest[1897:4857928] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8
,2016-03-31 01:52:53.343 ThaliTest[1897:4857928] client: lost peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41
2016-03-31 01:52:53.343 ThaliTest[1897:4857928] client session: onPeerLost: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41
,2016-03-31 01:52:53.836 ThaliTest[1897:4858059] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-31 01:52:53.837 ThaliTest[1897:4858059] jxcore: stopListeningForAdvertisements: success
ok 176 Should be able to call stopListeningForAdvertisements in teardown
2016-03-31 01:52:53.838 ThaliTest[1897:4858059] jxcore: stopAdvertisingAndListening
2016-03-31 01:52:53.838 ThaliTest[1897:485805,9] THEMultipeerManager stopping peer
2016-03-31 01:52:53.839 ThaliTest[1897:4858059] multipeer manager: stop client timer
2016-03-31 01:52:53.839 ThaliTest[1897:4858059] jxcore: stopAdvertisingAndListening: success
ok 177 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 43. Get error when trying to double connect to a peer
,2016-03-31 01:52:55.245 ThaliTest[1897:4858059] jxcore: startUpdateAdvertisingAndListening
2016-03-31 01:52:55.246 ThaliTest[1897:4858059] server: starting 42E93D78-2507-4BE0-9192-FC412A882204:9
2016-03-31 01:52:55.246 ThaliTest[1897:4858059] multipeer m,anager: start client restart timer: 0x17db5a20
2016-03-31 01:52:55.246 ThaliTest[1897:4858059] THEMultipeerManager initialized peer 42E93D78-2507-4BE0-9192-FC412A882204:9
2016-03-31 01:52:55.246 ThaliTest[1897:4858059] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 178 Can call startUpdateAdvertisingAndListening without error
2016-03-31 01:52:55.248 ThaliTest[1897:4858059] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisin,gActive":true,"discoveryActive":true}
2016-03-31 01:52:55.249 ThaliTest[1897:4858059] jxcore: startListeningForAdvertisements: success
,ok 179 Can call startListeningForAdvertisements without error
,2016-03-31 01:52:55.492 ThaliTest[1897:4857928] client: found new peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:8
,2016-03-31 01:52:55.496 ThaliTest[1897:4858059] jxcore: connect 9BF3B351-B42F-4B62-994E-93C3F024E3C4:8
2016-03-31 01:52:55.496 ThaliTest[1897:4858059] client: server will connect
2016-03-31 01:52:55.496 ThaliTest[1897:4858059] client session: reverseConn,ect
2016-03-31 01:52:55.497 ThaliTest[1897:4858059] client session: stateChange:0->1 9BF3B351-B42F-4B62-994E-93C3F024E3C4:8
,2016-03-31 01:52:55.519 ThaliTest[1897:4857928] client: found new peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8
,2016-03-31 01:52:55.839 ThaliTest[1897:4859695] client session: not connected 9BF3B351-B42F-4B62-994E-93C3F024E3C4:8
2016-03-31 01:52:55.840 ThaliTest[1897:4859695] client session: onLinkFailure: 9BF3B351-B42F-4B62-994E-93C3F024E3C4
2016-03-31 01:52:55.8,41 ThaliTest[1897:4859695] client session: disconnect
2016-03-31 01:52:55.841 ThaliTest[1897:4859695] client session: stateChange:1->0 9BF3B351-B42F-4B62-994E-93C3F024E3C4:8
2016-03-31 01:52:55.841 ThaliTest[1897:4859695] client session: no connect callb,ack (server initiated)
,2016-03-31 01:52:56.749 ThaliTest[1897:4857928] multipeer session: reset timer
2016-03-31 01:52:56.749 ThaliTest[1897:4857928] server: rejecting invitation from 9BF3B351-B42F-4B62-994E-93C3F024E3C4 due to previous generation (42E93D78-2507-4BE0-9192-FC412A882204:9 != 42E93D78-2507-4BE0-9192-FC412A882204:8)
,2016-03-31 01:52:56.805 ThaliTest[1897:4857928] multipeer session: reset timer
2016-03-31 01:52:56.805 ThaliTest[1897:4857928] server: rejecting invitation from 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41 due to previous generation (42E93D78-2507-4BE0-9192-FC412A882204:9 != 42E93D78-2507-4BE0-9192-FC412A882204:8)
,2016-03-31 01:53:00.223 ThaliTest[1897:4857928] multipeer session: reset timer
2016-03-31 01:53:00.223 ThaliTest[1897:4857928] server: disconnecting to refresh session (9BF3B351-B42F-4B62-994E-93C3F024E3C4)
2016-03-31 01:53:00.223 ThaliTest[1897:4857928] server: rejecting invitation from 9BF3B351-B42F-4B62-994E-93C3F024E3C4 due to previous generation (42E93D78-2507-4BE0-9192-FC412A882204:9 != 42E93D78-2507-4BE0-9192-FC412A882204:8)
,2016-03-31 01:53:03.522 ThaliTest[1897:4857928] multipeer session: reset timer
2016-03-31 01:53:03.522 ThaliTest[1897:4857928] server: disconnecting to refresh session (9BF3B351-B42F-4B62-994E-93C3F024E3C4)
2016-03-31 01:53:03.522 ThaliTest[1897:4857928], server: rejecting invitation from 9BF3B351-B42F-4B62-994E-93C3F024E3C4 due to previous generation (42E93D78-2507-4BE0-9192-FC412A882204:9 != 42E93D78-2507-4BE0-9192-FC412A882204:8)
,2016-03-31 01:53:05.497 ThaliTest[1897:4857928] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-31 01:53:07.154 ThaliTest[1897:4857928] multipeer session: reset timer
2016-03-31 01:53:07.154 ThaliTest[1897:4857928] server: disconnecting to refresh session (9BF3B351-B42F-4B62-994E-93C3F024E3C4)
2016-03-31 01:53:07.155 ThaliTest[1897:4857928], server: rejecting invitation from 9BF3B351-B42F-4B62-994E-93C3F024E3C4 due to previous generation (42E93D78-2507-4BE0-9192-FC412A882204:9 != 42E93D78-2507-4BE0-9192-FC412A882204:8)
,2016-03-31 01:53:08.510 ThaliTest[1897:4858059] jxcore: connect 9BF3B351-B42F-4B62-994E-93C3F024E3C4:8
2016-03-31 01:53:08.511 ThaliTest[1897:4858059] client: server will connect
2016-03-31 01:53:08.511 ThaliTest[1897:4858059] client session: reverseConnect
2016-03-31 01:53:08.511 ThaliTest[1897:4858059] client session: stateChange:0->1 9BF3B351-B42F-4B62-994E-93C3F024E3C4:8
,2016-03-31 01:53:08.598 ThaliTest[1897:4859694] client session: not connected 9BF3B351-B42F-4B62-994E-93C3F024E3C4:8
2016-03-31 01:53:08.598 ThaliTest[1897:4859694] client session: onLinkFailure: 9BF3B351-B42F-4B62-994E-93C3F024E3C4
2016-03-31 01:53:08.5,98 ThaliTest[1897:4859694] client session: disconnect
,2016-03-31 01:53:08.599 ThaliTest[1897:4859694] client session: stateChange:1->0 9BF3B351-B42F-4B62-994E-93C3F024E3C4:8
2016-03-31 01:53:08.602 ThaliTest[1897:4859694] client session: no connect callback (server initiated)
,2016-03-31 01:53:08.730 ThaliTest[1897:4857928] multipeer session: reset timer
,2016-03-31 01:53:08.730 ThaliTest[1897:4857928] server: disconnecting to refresh session (25ECEE51-730A-4F4F-BA49-ACDAF32AFB41)
,2016-03-31 01:53:08.730 ThaliTest[1897:4857928] server: rejecting invitation from 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41 due to previous generation (42E93D78-2507-4BE0-9192-FC412A882204:9 != 42E93D78-2507-4BE0-9192-FC412A882204:8)
,2016-03-31 01:53:11.397 ThaliTest[1897:4857928] multipeer session: reset timer
2016-03-31 01:53:11.397 ThaliTest[1897:4857928] server: disconnecting to refresh session (9BF3B351-B42F-4B62-994E-93C3F024E3C4)
2016-03-31 01:53:11.397 ThaliTest[1897:4857928] server: rejecting invitation from 9BF3B351-B42F-4B62-994E-93C3F024E3C4 due to previous generation (42E93D78-2507-4BE0-9192-FC412A882204:9 != 42E93D78-2507-4BE0-9192-FC412A882204:8)
,2016-03-31 01:53:15.246 ThaliTest[1897:4857928] multipeer manager: restart client
,2016-03-31 01:53:15.273 ThaliTest[1897:4857928] client: found updated peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
2016-03-31 01:53:15.274 ThaliTest[1897:4857928] client: found updated peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
,2016-03-31 01:53:16.410 ThaliTest[1897:4857928] multipeer session: reset timer
2016-03-31 01:53:16.410 ThaliTest[1897:4857928] server: disconnecting to refresh session (9BF3B351-B42F-4B62-994E-93C3F024E3C4)
2016-03-31 01:53:16.410 ThaliTest[1897:4857928] server: rejecting invitation from 9BF3B351-B42F-4B62-994E-93C3F024E3C4 due to previous generation (42E93D78-2507-4BE0-9192-FC412A882204:9 != 42E93D78-2507-4BE0-9192-FC412A882204:8)
,2016-03-31 01:53:18.511 ThaliTest[1897:4857928] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect ret,ry - retries left: 8
,2016-03-31 01:53:20.194 ThaliTest[1897:4857928] multipeer session: reset timer
2016-03-31 01:53:20.195 ThaliTest[1897:4857928] server: disconnecting to refresh session (9BF3B351-B42F-4B62-994E-93C3F024E3C4)
2016-03-31 01:53:20.195 ThaliTest[1897:4857928], server: rejecting invitation from 9BF3B351-B42F-4B62-994E-93C3F024E3C4 due to previous generation (42E93D78-2507-4BE0-9192-FC412A882204:9 != 42E93D78-2507-4BE0-9192-FC412A882204:8)
,2016-03-31 01:53:21.515 ThaliTest[1897:4858059] jxcore: connect 9BF3B351-B42F-4B62-994E-93C3F024E3C4:8
2016-03-31 01:53:21.515 ThaliTest[1897:4858059] client: server will connect
2016-03-31 01:53:21.516 ThaliTest[1897:4858059] client session: reverseConnect
2016-03-31 01:53:21.516 ThaliTest[1897:4858059] client session: stateChange:0->1 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
,2016-03-31 01:53:21.731 ThaliTest[1897:4859695] client session: not connected 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
2016-03-31 01:53:21.731 ThaliTest[1897:4859695] client session: onLinkFailure: 9BF3B351-B42F-4B62-994E-93C3F024E3C4
2016-03-31 01:53:21.732 ThaliTest[1897:4859695] client session: disconnect
,2016-03-31 01:53:21.732 ThaliTest[1897:4859695] client session: stateChange:1->0 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
2016-03-31 01:53:21.733 ThaliTest[1897:4859695] client session: no connect callback (server initiated)
,2016-03-31 01:53:21.834 ThaliTest[1897:4857928] multipeer session: reset timer
2016-03-31 01:53:21.834 ThaliTest[1897:4857928] server: disconnecting to refresh session (25ECEE51-730A-4F4F-BA49-ACDAF32AFB41)
2016-03-31 01:53:21.834 ThaliTest[1897:4857928], server: rejecting invitation from 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41 due to previous generation (42E93D78-2507-4BE0-9192-FC412A882204:9 != 42E93D78-2507-4BE0-9192-FC412A882204:8)
,2016-03-31 01:53:24.437 ThaliTest[1897:4857928] multipeer session: reset timer
2016-03-31 01:53:24.437 ThaliTest[1897:4857928] server: disconnecting to refresh session (9BF3B351-B42F-4B62-994E-93C3F024E3C4)
2016-03-31 01:53:24.437 ThaliTest[1897:4857928], server: rejecting invitation from 9BF3B351-B42F-4B62-994E-93C3F024E3C4 due to previous generation (42E93D78-2507-4BE0-9192-FC412A882204:9 != 42E93D78-2507-4BE0-9192-FC412A882204:8)
,2016-03-31 01:53:28.056 ThaliTest[1897:4857928] multipeer session: reset timer
2016-03-31 01:53:28.056 ThaliTest[1897:4857928] server: disconnecting to refresh session (9BF3B351-B42F-4B62-994E-93C3F024E3C4)
2016-03-31 01:53:28.056 ThaliTest[1897:4857928] server: rejecting invitation from 9BF3B351-B42F-4B62-994E-93C3F024E3C4 due to previous generation (42E93D78-2507-4BE0-9192-FC412A882204:9 != 42E93D78-2507-4BE0-9192-FC412A882204:8)
,2016-03-31 01:53:31.516 ThaliTest[1897:4857928] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect ret,ry - retries left: 7
,2016-03-31 01:53:32.375 ThaliTest[1897:4857928] multipeer session: reset timer
2016-03-31 01:53:32.375 ThaliTest[1897:4857928] server: disconnecting to refresh session (9BF3B351-B42F-4B62-994E-93C3F024E3C4)
2016-03-31 01:53:32.375 ThaliTest[1897:4857928] server: rejecting invitation from 9BF3B351-B42F-4B62-994E-93C3F024E3C4 due to previous generation (42E93D78-2507-4BE0-9192-FC412A882204:9 != 42E93D78-2507-4BE0-9192-FC412A882204:8)
,2016-03-31 01:53:34.519 ThaliTest[1897:4858059] jxcore: connect 9BF3B351-B42F-4B62-994E-93C3F024E3C4:8
2016-03-31 01:53:34.519 ThaliTest[1897:4858059] client: server will connect
2016-03-31 01:53:34.519 ThaliTest[1897:4858059] client session: reverseConn,ect
2016-03-31 01:53:34.519 ThaliTest[1897:4858059] client session: stateChange:0->1 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
,2016-03-31 01:53:35.247 ThaliTest[1897:4857928] multipeer manager: restart client
,2016-03-31 01:53:35.268 ThaliTest[1897:4857928] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
2016-03-31 01:53:35.270 ThaliTest[1897:4857928] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
,2016-03-31 01:53:44.520 ThaliTest[1897:4857928] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect ret,ry - retries left: 6
,2016-03-31 01:53:47.527 ThaliTest[1897:4858059] jxcore: connect 9BF3B351-B42F-4B62-994E-93C3F024E3C4:8
2016-03-31 01:53:47.527 ThaliTest[1897:4858059] client: already connect(ing/ed) to 9BF3B351-B42F-4B62-994E-93C3F024E3C4:8
2016-03-31 01:53:47.527 Thali,Test[1897:4858059] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-31 01:53:50.540 ThaliTest[1897:4858059] jxcore: connect 9BF3B351-B42F-4B62-994E-93C3F024E3C4:8
2016-03-31 01:53:50.540 ThaliTest[1897:4858059] client: already connect(ing/ed) to 9BF3B351-B42F-4B62-994E-93C3F024E3C4:8
2016-03-31 01:53:50.540 Thali,Test[1897:4858059] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-31 01:53:53.547 ThaliTest[1897:4858059] jxcore: connect 9BF3B351-B42F-4B62-994E-93C3F024E3C4:8
2016-03-31 01:53:53.547 ThaliTest[1897:4858059] client: already connect(ing/ed) to 9BF3B351-B42F-4B62-994E-93C3F024E3C4:8
2016-03-31 01:53:53.547 Thali,Test[1897:4858059] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-31 01:53:55.247 ThaliTest[1897:4857928] multipeer manager: restart client
,2016-03-31 01:53:55.268 ThaliTest[1897:4857928] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
2016-03-31 01:53:55.268 ThaliTest[1897:4857928] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
,2016-03-31 01:53:56.553 ThaliTest[1897:4858059] jxcore: connect 9BF3B351-B42F-4B62-994E-93C3F024E3C4:8
2016-03-31 01:53:56.553 ThaliTest[1897:4858059] client: already connect(ing/ed) to 9BF3B351-B42F-4B62-994E-93C3F024E3C4:8
2016-03-31 01:53:56.554 Thali,Test[1897:4858059] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-31 01:53:59.566 ThaliTest[1897:4858059] jxcore: connect 9BF3B351-B42F-4B62-994E-93C3F024E3C4:8
2016-03-31 01:53:59.566 ThaliTest[1897:4858059] client: already connect(ing/ed) to 9BF3B351-B42F-4B62-994E-93C3F024E3C4:8
2016-03-31 01:53:59.567 Thali,Test[1897:4858059] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-31 01:54:02.570 ThaliTest[1897:4858059] jxcore: connect 9BF3B351-B42F-4B62-994E-93C3F024E3C4:8
2016-03-31 01:54:02.570 ThaliTest[1897:4858059] client: already connect(ing/ed) to 9BF3B351-B42F-4B62-994E-93C3F024E3C4:8
2016-03-31 01:54:02.570 ThaliTest[1897:4858059] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
WARN testThaliMobileNative: Too many connect retries!
,2016-03-31 01:54:07.492 ThaliTest[1897:4859712] client session: not connected 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
2016-03-31 01:54:07.492 ThaliTest[1897:4859712] client session: onLinkFailure: 9BF3B351-B42F-4B62-994E-93C3F024E3C4
2016-03-31 01:54:07.492 ThaliTest[1897:4859712] client session: disconnect
2016-03-31 01:54:07.492 ThaliTest[1897:4859712] client session: stateChange:1->0 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
,2016-03-31 01:54:07.496 ThaliTest[1897:4859712] client session: no connect callback (server initiated)
,2016-03-31 01:54:15.247 ThaliTest[1897:4857928] multipeer manager: restart client
,2016-03-31 01:54:15.264 ThaliTest[1897:4857928] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
2016-03-31 01:54:15.264 ThaliTest[1897:4857928] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
,2016-03-31 01:54:35.247 ThaliTest[1897:4857928] multipeer manager: restart client
,2016-03-31 01:54:35.266 ThaliTest[1897:4857928] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
2016-03-31 01:54:35.266 ThaliTest[1897:4857928] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
,2016-03-31 01:54:55.247 ThaliTest[1897:4857928] multipeer manager: restart client
,2016-03-31 01:54:55.272 ThaliTest[1897:4857928] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
2016-03-31 01:54:55.272 ThaliTest[1897:4857928] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
,2016-03-31 01:55:15.247 ThaliTest[1897:4857928] multipeer manager: restart client
,2016-03-31 01:55:15.266 ThaliTest[1897:4857928] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
2016-03-31 01:55:15.266 ThaliTest[1897:4857928] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
,2016-03-31 01:55:35.247 ThaliTest[1897:4857928] multipeer manager: restart client
,2016-03-31 01:55:35.266 ThaliTest[1897:4857928] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
2016-03-31 01:55:35.267 ThaliTest[1897:4857928] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
,2016-03-31 01:55:55.247 ThaliTest[1897:4857928] multipeer manager: restart client
,2016-03-31 01:55:55.272 ThaliTest[1897:4857928] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
2016-03-31 01:55:55.272 ThaliTest[1897:4857928] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
,2016-03-31 01:56:15.247 ThaliTest[1897:4857928] multipeer manager: restart client
,2016-03-31 01:56:15.267 ThaliTest[1897:4857928] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
,2016-03-31 01:56:15.277 ThaliTest[1897:4857928] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
,2016-03-31 01:56:35.247 ThaliTest[1897:4857928] multipeer manager: restart client
,2016-03-31 01:56:35.276 ThaliTest[1897:4857928] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
2016-03-31 01:56:35.276 ThaliTest[1897:4857928] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
,2016-03-31 01:56:55.247 ThaliTest[1897:4857928] multipeer manager: restart client
,2016-03-31 01:57:15.247 ThaliTest[1897:4857928] multipeer manager: restart client
,2016-03-31 01:57:15.261 ThaliTest[1897:4857928] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
2016-03-31 01:57:15.262 ThaliTest[1897:4857928] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
,2016-03-31 01:57:35.247 ThaliTest[1897:4857928] multipeer manager: restart client
,2016-03-31 01:57:35.262 ThaliTest[1897:4857928] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
2016-03-31 01:57:35.262 ThaliTest[1897:4857928] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
,2016-03-31 01:57:55.247 ThaliTest[1897:4857928] multipeer manager: restart client
,2016-03-31 01:57:55.260 ThaliTest[1897:4857928] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
2016-03-31 01:57:55.260 ThaliTest[1897:4857928] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
,2016-03-31 01:58:15.247 ThaliTest[1897:4857928] multipeer manager: restart client
,2016-03-31 01:58:15.264 ThaliTest[1897:4857928] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
2016-03-31 01:58:15.264 ThaliTest[1897:4857928] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
,2016-03-31 01:58:35.247 ThaliTest[1897:4857928] multipeer manager: restart client
,2016-03-31 01:58:35.264 ThaliTest[1897:4857928] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
2016-03-31 01:58:35.265 ThaliTest[1897:4857928] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
,2016-03-31 01:58:55.247 ThaliTest[1897:4857928] multipeer manager: restart client
,2016-03-31 01:58:55.264 ThaliTest[1897:4857928] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
2016-03-31 01:58:55.266 ThaliTest[1897:4857928] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
,2016-03-31 01:59:15.246 ThaliTest[1897:4857928] multipeer manager: restart client
,2016-03-31 01:59:15.260 ThaliTest[1897:4857928] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
2016-03-31 01:59:15.261 ThaliTest[1897:4857928] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
,2016-03-31 01:59:35.246 ThaliTest[1897:4857928] multipeer manager: restart client
,2016-03-31 01:59:35.263 ThaliTest[1897:4857928] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
2016-03-31 01:59:35.263 ThaliTest[1897:4857928] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
,2016-03-31 01:59:55.247 ThaliTest[1897:4857928] multipeer manager: restart client
,2016-03-31 01:59:55.265 ThaliTest[1897:4857928] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
2016-03-31 01:59:55.266 ThaliTest[1897:4857928] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
,2016-03-31 02:00:15.247 ThaliTest[1897:4857928] multipeer manager: restart client
,2016-03-31 02:00:15.264 ThaliTest[1897:4857928] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
2016-03-31 02:00:15.265 ThaliTest[1897:4857928] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
,2016-03-31 02:00:35.247 ThaliTest[1897:4857928] multipeer manager: restart client
,2016-03-31 02:00:35.263 ThaliTest[1897:4857928] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
2016-03-31 02:00:35.264 ThaliTest[1897:4857928] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
,2016-03-31 02:00:55.247 ThaliTest[1897:4857928] multipeer manager: restart client
,2016-03-31 02:00:55.264 ThaliTest[1897:4857928] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
2016-03-31 02:00:55.264 ThaliTest[1897:4857928] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
,2016-03-31 02:01:15.247 ThaliTest[1897:4857928] multipeer manager: restart client
,2016-03-31 02:01:15.260 ThaliTest[1897:4857928] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
2016-03-31 02:01:15.260 ThaliTest[1897:4857928] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
,2016-03-31 02:01:35.247 ThaliTest[1897:4857928] multipeer manager: restart client
,2016-03-31 02:01:35.261 ThaliTest[1897:4857928] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
2016-03-31 02:01:35.261 ThaliTest[1897:4857928] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
,2016-03-31 02:01:55.247 ThaliTest[1897:4857928] multipeer manager: restart client
,2016-03-31 02:01:55.262 ThaliTest[1897:4857928] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
2016-03-31 02:01:55.262 ThaliTest[1897:4857928] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
,2016-03-31 02:02:15.247 ThaliTest[1897:4857928] multipeer manager: restart client
,2016-03-31 02:02:15.266 ThaliTest[1897:4857928] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
2016-03-31 02:02:15.266 ThaliTest[1897:4857928] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
,2016-03-31 02:02:35.247 ThaliTest[1897:4857928] multipeer manager: restart client
,2016-03-31 02:02:35.264 ThaliTest[1897:4857928] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
2016-03-31 02:02:35.265 ThaliTest[1897:4857928] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
,2016-03-31 02:02:55.247 ThaliTest[1897:4857928] multipeer manager: restart client
,2016-03-31 02:02:55.263 ThaliTest[1897:4857928] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
2016-03-31 02:02:55.263 ThaliTest[1897:4857928] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
,2016-03-31 02:03:15.247 ThaliTest[1897:4857928] multipeer manager: restart client
,2016-03-31 02:03:15.260 ThaliTest[1897:4857928] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
2016-03-31 02:03:15.260 ThaliTest[1897:4857928] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
,2016-03-31 02:03:35.247 ThaliTest[1897:4857928] multipeer manager: restart client
,2016-03-31 02:03:35.261 ThaliTest[1897:4857928] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
2016-03-31 02:03:35.262 ThaliTest[1897:4857928] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
,2016-03-31 02:03:55.247 ThaliTest[1897:4857928] multipeer manager: restart client
,2016-03-31 02:03:55.262 ThaliTest[1897:4857928] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
,2016-03-31 02:03:55.266 ThaliTest[1897:4857928] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
,2016-03-31 02:04:15.247 ThaliTest[1897:4857928] multipeer manager: restart client
,2016-03-31 02:04:15.261 ThaliTest[1897:4857928] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
2016-03-31 02:04:15.261 ThaliTest[1897:4857928] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
,2016-03-31 02:04:35.247 ThaliTest[1897:4857928] multipeer manager: restart client
,2016-03-31 02:04:35.262 ThaliTest[1897:4857928] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
2016-03-31 02:04:35.262 ThaliTest[1897:4857928] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
,2016-03-31 02:04:55.247 ThaliTest[1897:4857928] multipeer manager: restart client
,2016-03-31 02:04:55.259 ThaliTest[1897:4857928] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
2016-03-31 02:04:55.260 ThaliTest[1897:4857928] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
,2016-03-31 02:05:15.247 ThaliTest[1897:4857928] multipeer manager: restart client
,2016-03-31 02:05:15.262 ThaliTest[1897:4857928] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
2016-03-31 02:05:15.263 ThaliTest[1897:4857928] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
,2016-03-31 02:05:35.247 ThaliTest[1897:4857928] multipeer manager: restart client
,2016-03-31 02:05:35.264 ThaliTest[1897:4857928] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
2016-03-31 02:05:35.264 ThaliTest[1897:4857928] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
,2016-03-31 02:05:55.247 ThaliTest[1897:4857928] multipeer manager: restart client
,2016-03-31 02:05:55.263 ThaliTest[1897:4857928] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
2016-03-31 02:05:55.263 ThaliTest[1897:4857928] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
,2016-03-31 02:06:15.247 ThaliTest[1897:4857928] multipeer manager: restart client
,2016-03-31 02:06:15.261 ThaliTest[1897:4857928] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
2016-03-31 02:06:15.263 ThaliTest[1897:4857928] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
,2016-03-31 02:06:35.247 ThaliTest[1897:4857928] multipeer manager: restart client
,2016-03-31 02:06:35.263 ThaliTest[1897:4857928] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
2016-03-31 02:06:35.263 ThaliTest[1897:4857928] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
,2016-03-31 02:06:55.247 ThaliTest[1897:4857928] multipeer manager: restart client
,2016-03-31 02:06:55.260 ThaliTest[1897:4857928] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
2016-03-31 02:06:55.260 ThaliTest[1897:4857928] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
,2016-03-31 02:07:15.247 ThaliTest[1897:4857928] multipeer manager: restart client
,2016-03-31 02:07:15.263 ThaliTest[1897:4857928] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
2016-03-31 02:07:15.264 ThaliTest[1897:4857928] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
,2016-03-31 02:07:35.247 ThaliTest[1897:4857928] multipeer manager: restart client
,2016-03-31 02:07:35.264 ThaliTest[1897:4857928] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
2016-03-31 02:07:35.264 ThaliTest[1897:4857928] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
,2016-03-31 02:07:55.247 ThaliTest[1897:4857928] multipeer manager: restart client
,2016-03-31 02:07:55.263 ThaliTest[1897:4857928] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
2016-03-31 02:07:55.263 ThaliTest[1897:4857928] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
,2016-03-31 02:08:15.247 ThaliTest[1897:4857928] multipeer manager: restart client
,2016-03-31 02:08:15.263 ThaliTest[1897:4857928] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
2016-03-31 02:08:15.263 ThaliTest[1897:4857928] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
,2016-03-31 02:08:35.247 ThaliTest[1897:4857928] multipeer manager: restart client
,2016-03-31 02:08:35.264 ThaliTest[1897:4857928] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
2016-03-31 02:08:35.264 ThaliTest[1897:4857928] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
,2016-03-31 02:08:55.247 ThaliTest[1897:4857928] multipeer manager: restart client
,2016-03-31 02:08:55.265 ThaliTest[1897:4857928] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
2016-03-31 02:08:55.265 ThaliTest[1897:4857928] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
,2016-03-31 02:09:15.246 ThaliTest[1897:4857928] multipeer manager: restart client
,2016-03-31 02:09:15.258 ThaliTest[1897:4857928] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
2016-03-31 02:09:15.260 ThaliTest[1897:4857928] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
,2016-03-31 02:09:35.247 ThaliTest[1897:4857928] multipeer manager: restart client
,2016-03-31 02:09:35.261 ThaliTest[1897:4857928] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
2016-03-31 02:09:35.262 ThaliTest[1897:4857928] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9

```
