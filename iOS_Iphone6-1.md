#### Test 681021307227906_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/681021307227906/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/708BE7B9-6A37-4413-A534-2520975E32A5/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/708BE7B9-6A37-4413-A534-2520975E32A5/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/681021307227906/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/681021307227906/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/75CEACD4-6BCE-4D94-82C4-BAE3FE18A91F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55111"
,(lldb)     command script import "/tmp/708BE7B9-6A37-4413-A534-2520975E32A5/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-04-28 21:25:18.544 ThaliTest[3782:8979182] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/762612B1-DC77-4F16-A08E-1717206DFC33/Library/Cookies/Cookies.binarycookies
,2016-04-28 21:25:18.988 ThaliTest[3782:8979182] Apache Cordova native platform version 4.1.1 is starting.
2016-04-28 21:25:18.989 ThaliTest[3782:8979182] Multi-tasking -> Device: YES, App: YES
,2016-04-28 21:25:19.010 ThaliTest[3782:8979182] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-04-28 21:25:21.227 ThaliTest[3782:8979182] Using UIWebView
,2016-04-28 21:25:21.234 ThaliTest[3782:8979182] [CDVTimer][handleopenurl] 0.441968ms
,2016-04-28 21:25:21.242 ThaliTest[3782:8979182] [CDVTimer][intentandnavigationfilter] 7.709980ms
2016-04-28 21:25:21.243 ThaliTest[3782:8979182] [CDVTimer][gesturehandler] 0.330031ms
2016-04-28 21:25:21.243 ThaliTest[3782:8979182] [CDVTimer][TotalPluginS,tartup] 10.106027ms
,2016-04-28 21:25:29.080 ThaliTest[3782:8979182] Resetting plugins due to page load.
,2016-04-28 21:25:32.172 ThaliTest[3782:8979182] Finished load of: file:///var/mobile/Containers/Bundle/Application/75CEACD4-6BCE-4D94-82C4-BAE3FE18A91F/ThaliTest.app/www/index.html
,2016-04-28 21:25:32.396 ThaliTest[3782:8979182] JXcore Cordova plugin initializing
,2016-04-28 21:25:32.398 ThaliTest[3782:8979428] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-04-28 21:25:39.777 ThaliTest[3782:8979428] jxcore: didRegisterToNative peerAvailabilityChanged
2016-04-28 21:25:39.777 ThaliTest[3782:8979428] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-04-28 21:25:39.777 ThaliTest[3782:8979428] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-04-28 21:25:39.780 ThaliTest[3782:8979428] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone6-1
,WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/75CEACD4-6BCE-4D94-82C4-BAE3FE18A91F/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/75CEACD4-6BCE-4D94-82C4-BAE3FE18A91F/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/75CEACD4-6BCE-4D94-82C4-BAE3FE18A91F/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/75CEACD4-6BCE-4D94-82C4-BAE3FE18A91F/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/75CEACD4-6BCE-4D94-82C4-BAE3FE18A91F/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/75CEACD4-6BCE-4D94-82C4-BAE3FE18A91F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/75CEACD4-6BCE-4D94-82C4-BAE3FE18A91F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/75CEACD4-6BCE-4D94-82C4-BAE3FE18A91F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/75CEACD4-6BCE-4D94-82C4-BAE3FE18A91F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/75CEACD4-6BCE-4D94-82C4-BAE3FE18A91F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/75CEACD4-6BCE-4D94-82C4-BAE3FE18A91F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/75CEACD4-6BCE-4D94-82C4-BAE3FE18A91F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/75CEACD4-6BCE-4D94-82C4-BAE3FE18A91F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/75CEACD4-6BCE-4D94-82C4-BAE3FE18A91F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/75CEACD4-6BCE-4D94-82C4-BAE3FE18A91F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/75CEACD4-6BCE-4D94-82C4-BAE3FE18A91F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/75CEACD4-6BCE-4D94-82C4-BAE3FE18A91F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/75CEACD4-6BCE-4D94-82C4-BAE3FE18A91F/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/75CEACD4-6BCE-4D94-82C4-BAE3FE18A91F/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/75CEACD4-6BCE-4D94-82C4-BAE3FE18A91F/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/75CEACD4-6BCE-4D94-82C4-BAE3FE18A91F/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/75CEACD4-6BCE-4D94-82C4-BAE3FE18A91F/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-04-28 21:25:45.688 ThaliTest[3782:8979182] THREAD WARNING: ['JXcore'] took '5602.677246' ms. Plugin should use a background thread.
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 60313
,ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 60315
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,ok 2 initial connection state should be CONNECTED
,DEBUG createNativeListener: incoming socket close
,ok 3 final connection state should be DISCONNECTED
,# teardown
,# setup
,# 3. emits routerPortConnectionFailed
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 60318
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: 
,ok 4 tried to connect to right port
,ok 5 failed due to refused connection
,ok 6 routerPortConnectionFailed is emitted
,# teardown
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,# setup
,DEBUG createNativeListener: incoming socket close
,# 4. native server connections all up
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 60322
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,ok 7 Send/recvd #1 should be equal length
,ok 8 Send/recvd #1 should be same
,ok 9 Send/recvd #2 should be equal length
,ok 10 Send/recvd #2 should be same
,ok 11 Should be exactly 2 client sockets
,# teardown
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,# setup
,DEBUG createNativeListener: incoming socket close
,# 5. native server - closing incoming stream cleans outgoing socket
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 60327
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,ok 12 socket shouldn't close until after stream
,ok 13 incoming remains open
,# teardown
,DEBUG createNativeListener: mux close
,# setup
,DEBUG createNativeListener: incoming socket close
,# 6. native server - closing incoming connection cleans outgoing socket
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 60331
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,ok 14 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: incoming socket close
,ok 15 socket shouldn't close until after incoming
,ok 16 incoming is cleaned up
,# teardown
,# setup
,# 7. native server - closing outgoing socket cleans associated mux stream
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 60335
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,ok 17 stream was closed
,ok 18 incoming should survive
,ok 19 mux should have no streams
,# teardown
,DEBUG createNativeListener: mux close
,# setup
,DEBUG createNativeListener: incoming socket close
,# 8. native server - closing the whole server cleans everything up
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 60339
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,ok 20 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,ok 21 Buffers are identical
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,ok 22 native server is nulled out
,ok 23 native server should be closed
,ok 24 incoming has been removed
,ok 25 Incoming should be done
,ok 26 The mux object should be closed
,ok 27 The mux stream should be closed
,DEBUG createNativeListener: incoming socket close
,# teardown
,# setup
,# 9. native server - we can get a ton of connections and data through and still clean up the server completely
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 60343
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
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
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,ok 28 native server is nulled out
,ok 29 native server should be closed
,ok 30 incoming has been removed
,DEBUG createNativeListener: incoming socket close
,DEBUG createNativeListener: incoming socket close
,DEBUG createNativeListener: incoming socket close
,DEBUG createNativeListener: incoming socket close
,DEBUG createNativeListener: incoming socket close
,DEBUG createNativeListener: incoming socket close
,DEBUG createNativeListener: incoming socket close
,DEBUG createNativeListener: incoming socket close
,DEBUG createNativeListener: incoming socket close
,DEBUG createNativeListener: incoming socket close
,# teardown
,# setup
,# 10. native server - simulate mux failure, make sure everything is cleaned up
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 60395
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,ok 31 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,ok 32 Buffers are identical
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
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
,DEBUG createNativeListener: listening 60399
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,ok 38 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,ok 39 Buffers are identical
,DEBUG createNativeListener: incoming socket timeout
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,DEBUG createNativeListener: incoming socket close
,ok 40 server should be fine
,ok 41 server should be open
,ok 42 incoming has been removed
,ok 43 The mux object should be closed
,ok 44 The mux stream should be closed
,# teardown
,# setup
,# 12. closeAll can close even when connections open
,ok 45 not possible to connect to the server anymore
,# teardown
,# setup
,# 13. closeAll with promise
,ok 46 not possible to connect to the server anymore
,# teardown
,# setup
,# 14. closeAll properly throws when closing a non open server with eatNotRunning set to false
,ok 47 Got the right error
,# teardown
,# setup
,# 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true
,# teardown
,# setup
,# 16. enqueue and run in order
,ok 48 firstPromise setTimeout
,ok 49 firstPromise result
,ok 50 firstPromise testValue
,ok 51 secondPromise setTimeout
,ok 52 secondPromise result
,ok 53 secondPromise testValue
,ok 54 thirdPromise in promise
,ok 55 thirdPromise result
,ok 56 thirdPromise testValue
,# teardown
,# setup
,# 17. enqueueAtTop and run backwards
,ok 57 thirdPromise - first to run
,ok 58 thirdPromise - in resolve
,ok 59 secondPromise - second to run
,ok 60 secondPromise - in catch
,ok 61 firstPromise - third to run
,ok 62 firstPromise - in then
,ok 63 testing promises
,# teardown
,# setup
,# 18. mix enqueue and enqueueAtTop
,ok 64 fourth
,ok 65 fourth
,ok 66 second
,ok 67 secondPromise - in then
,ok 68 first
,ok 69 firstPromise - in catch
,ok 70 third
,ok 71 thirdPromise - in then
,ok 72 testingPromises
,# teardown
,# setup
,# 19. queues handled independently
,ok 73 all short operations completed before the long resolves
,# teardown
,# setup
,# 20. basic
,ok 74 sane
,# teardown
,# setup
,# 21. another
,ok 75 sane
,# teardown
,# setup
,# 22. can pass data in setup
,[{"uuid":"12b0fe5c-5358-4bd1-a579-798f1c8d590d","data":"custom data"},{"uuid":"199e0e2c-9092-4104-af67-e71ad2ae16f8","data":"custom data"},{"uuid":"749167e2-4f0b-4861-8dc7-f1c6b8b47666","data":"custom data"},{"uuid":"76d70763-019d-486c-be48-b3480c768092","data":"custom data"}]
,ok 76 test participant has uuid
,ok 77 participant data matches
,ok 78 test participant has uuid
,ok 79 participant data matches
,ok 80 test participant has uuid
,ok 81 participant data matches
,ok 82 test participant has uuid
,ok 83 participant data matches
,ok 84 own UUID is found from the participants list
,# teardown
,# setup
,# 23. #startListeningForAdvertisements should fail if start not called
,ok 85 specific error should be returned
,# teardown
,ok 86 error should be null
,ok 87 error should be null
,# setup
,# 24. #startUpdateAdvertisingAndListening should fail if start not called
,ok 88 specific error should be returned
,# teardown
,ok 89 error should be null
,ok 90 error should be null
,# setup
,# 25. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 60409
,2016-04-28 21:27:54.223 ThaliTest[3782:8979428] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-28 21:27:54.225 ThaliTest[3782:8979428] jxcore: stopListeningForAdvertisements: success
,ok 91 error should be null
,ok 92 error should be null
,2016-04-28 21:27:54.227 ThaliTest[3782:8979428] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-28 21:27:54.228 ThaliTest[3782:8979428] jxcore: stopListeningForAdvertisements: success
,ok 93 error should be null
,ok 94 error should be null
,# teardown
,2016-04-28 21:27:54.311 ThaliTest[3782:8979428] jxcore: stopAdvertisingAndListening
2016-04-28 21:27:54.311 ThaliTest[3782:8979428] THEMultipeerManager stopping peer
2016-04-28 21:27:54.311 ThaliTest[3782:8979428] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-28 21:27:54.312 ThaliTest[3782:8979428] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-28 21:27:54.312 ThaliTest[3782:8979428] jxcore: stopListeningForAdvertisements: success
,ok 95 error should be null
,ok 96 error should be null
,# setup
,# 26. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 60411
,2016-04-28 21:27:54.559 ThaliTest[3782:8979428] jxcore: startListeningForAdvertisements
,2016-04-28 21:27:54.562 ThaliTest[3782:8979428] multipeer manager: start client restart timer: 0x15de6860
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-28 21:27:54.565 ThaliTest[3782:8979428] jxcore: startListeningForAdvertisements: success
,ok 97 error should be null
,ok 98 error should be null
,2016-04-28 21:27:54.595 ThaliTest[3782:8979428] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-28 21:27:54.598 ThaliTest[3782:8979428] jxcore: startListeningForAdvertisements: success
,ok 99 error should be null
,ok 100 error should be null
,# teardown
,2016-04-28 21:27:54.814 ThaliTest[3782:8979428] jxcore: stopAdvertisingAndListening
2016-04-28 21:27:54.815 ThaliTest[3782:8979428] THEMultipeerManager stopping peer
2016-04-28 21:27:54.815 ThaliTest[3782:8979428] jxcore: stopAdvertisingAndListening: success
2016-04-28 21:27:54.815 ThaliTest[3782:8979428] jxcore: stopListeningForAdvertisements
2016-04-28 21:27:54.816 ThaliTest[3782:8979428] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-28 21:27:54.820 ThaliTest[3782:8979428] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 101 error should be null
,ok 102 error should be null
,# setup
,# 27. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 60413
,2016-04-28 21:27:55.360 ThaliTest[3782:8979428] jxcore: startUpdateAdvertisingAndListening
2016-04-28 21:27:55.360 ThaliTest[3782:8979428] server: starting C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:1
2016-04-28 21:27:55.361 ThaliTest[3782:8979428] multipeer m,anager: start client restart timer: 0x15de6860
2016-04-28 21:27:55.362 ThaliTest[3782:8979428] THEMultipeerManager initialized peer C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:1
2016-04-28 21:27:55.362 ThaliTest[3782:8979428] jxcore: startUpdateAdvertisingAndListening: success
,ok 103 error should be null
ok 104 error should be null
,2016-04-28 21:27:55.382 ThaliTest[3782:8979428] jxcore: startUpdateAdvertisingAndListening
2016-04-28 21:27:55.383 ThaliTest[3782:8979428] THEMultipeerManager stopping peer
2016-04-28 21:27:55.383 ThaliTest[3782:8979428] multipeer manager: stop client ti,mer
2016-04-28 21:27:55.384 ThaliTest[3782:8979428] server: starting C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:2
2016-04-28 21:27:55.384 ThaliTest[3782:8979428] multipeer manager: start client restart timer: 0x15de6860
2016-04-28 21:27:55.385 ThaliTest[3782:,8979428] THEMultipeerManager initialized peer C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:2
2016-04-28 21:27:55.385 ThaliTest[3782:8979428] jxcore: startUpdateAdvertisingAndListening: success
,ok 105 error should be null
,ok 106 error should be null
,# teardown
,2016-04-28 21:27:55.585 ThaliTest[3782:8979428] jxcore: stopAdvertisingAndListening
2016-04-28 21:27:55.586 ThaliTest[3782:8979428] THEMultipeerManager stopping peer
,2016-04-28 21:27:55.588 ThaliTest[3782:8979428] multipeer manager: stop client timer
2016-04-28 21:27:55.590 ThaliTest[3782:8979428] jxcore: stopAdvertisingAndListening: success
2016-04-28 21:27:55.591 ThaliTest[3782:8979428] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-28 21:27:55.594 ThaliTest[3782:8979428] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 107 error should be null
,ok 108 error should be null
,# setup
,# 28. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 60418
,2016-04-28 21:27:56.619 ThaliTest[3782:8979428] jxcore: stopAdvertisingAndListening
2016-04-28 21:27:56.619 ThaliTest[3782:8979428] THEMultipeerManager stopping peer
,2016-04-28 21:27:56.620 ThaliTest[3782:8979428] jxcore: stopAdvertisingAndListening: success
,ok 109 error should be null
,ok 110 error should be null
,2016-04-28 21:27:56.626 ThaliTest[3782:8979428] jxcore: stopAdvertisingAndListening
2016-04-28 21:27:56.626 ThaliTest[3782:8979428] THEMultipeerManager stopping peer
2016-04-28 21:27:56.627 ThaliTest[3782:8979428] jxcore: stopAdvertisingAndListening: success
ok 111 error should be null
,ok 112 error should be null
,# teardown
,2016-04-28 21:27:57.437 ThaliTest[3782:8979428] jxcore: stopAdvertisingAndListening
2016-04-28 21:27:57.437 ThaliTest[3782:8979428] THEMultipeerManager stopping peer
2016-04-28 21:27:57.438 ThaliTest[3782:8979428] jxcore: stopAdvertisingAndListening: success
,2016-04-28 21:27:57.440 ThaliTest[3782:8979428] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-28 21:27:57.442 ThaliTest[3782:8979428] jxcore: stopListeningForAdvertisements: success
,ok 113 error should be null
,ok 114 error should be null
,# setup
,# 29. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 60420
,ok 115 first call should succeed
,ok 116 first call should succeed
,ok 117 specific error should be returned
,# teardown
,2016-04-28 21:28:02.578 ThaliTest[3782:8979428] jxcore: stopAdvertisingAndListening
2016-04-28 21:28:02.579 ThaliTest[3782:8979428] THEMultipeerManager stopping peer
2016-04-28 21:28:02.579 ThaliTest[3782:8979428] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-28 21:28:02.580 ThaliTest[3782:8979428] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-28 21:28:02.583 ThaliTest[3782:8979428] jxcore: stopListeningForAdvertisements: success
,ok 118 error should be null
,ok 119 error should be null
,# setup
,# 30. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 60422
,2016-04-28 21:28:02.781 ThaliTest[3782:8979428] jxcore: startListeningForAdvertisements
2016-04-28 21:28:02.782 ThaliTest[3782:8979428] multipeer manager: start client restart timer: 0x15de6860
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-28 21:28:02.784 ThaliTest[3782:8979428] jxcore: startListeningForAdvertisements: success
,2016-04-28 21:28:02.804 ThaliTest[3782:8979428] jxcore: startUpdateAdvertisingAndListening
2016-04-28 21:28:02.805 ThaliTest[3782:8979428] server: starting C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:3
2016-04-28 21:28:02.805 ThaliTest[3782:8979428] THEMultipee,rManager initialized peer C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:3
2016-04-28 21:28:02.806 ThaliTest[3782:8979428] jxcore: startUpdateAdvertisingAndListening: success
,ok 120 called only once
,ok 121 discovery state matches
ok 122 advertising state matches
,# teardown
,2016-04-28 21:28:03.047 ThaliTest[3782:8979428] jxcore: stopAdvertisingAndListening
2016-04-28 21:28:03.048 ThaliTest[3782:8979428] THEMultipeerManager stopping peer
2016-04-28 21:28:03.048 ThaliTest[3782:8979428] jxcore: stopAdvertisingAndListening: success
2016-04-28 21:28:03.049 ThaliTest[3782:8979428] jxcore: stopListeningForAdvertisements
,2016-04-28 21:28:03.052 ThaliTest[3782:8979428] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-28 21:28:03.054 ThaliTest[3782:8979428,] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 123 error should be null
,ok 124 error should be null
,# setup
,# 31. does not send duplicate availability changes
,ok 125 should be called once
,ok 126 should not have been called more than once
,# teardown
,ok 127 error should be null
,ok 128 error should be null
,# setup
,# 32. can get the network status
,ok 129 network status should have certain non-empty properties
,# teardown
,ok 130 error should be null
,ok 131 error should be null
,# setup
,# 33. wifi peer is marked unavailable if announcements stop
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
,ok 132 host address should match
,ok 133 port should match
,ok 134 host address should be null
,ok 135 port should should be null
,# teardown
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 136 error should be null
,ok 137 error should be null
,# setup
,# 34. Can call start/stopListeningForAdvertisements
,2016-04-28 21:28:10.962 ThaliTest[3782:8979428] jxcore: startListeningForAdvertisements
2016-04-28 21:28:10.963 ThaliTest[3782:8979428] multipeer manager: start client restart timer: 0x15de6860
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-28 21:28:10.965 ThaliTest[3782:8979428] jxcore: startListeningForAdvertisements: success
,ok 138 Can call startListeningForAdvertisements without error
,2016-04-28 21:28:10.976 ThaliTest[3782:8979428] jxcore: stopListeningForAdvertisements
,2016-04-28 21:28:10.977 ThaliTest[3782:8979428] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-28 21:28:10.983 ThaliTest[3782:8979428] jxcore: stopListeningForAdvertisements: success
,ok 139 Can call stopListeningForAdvertisements without error
,# teardown
,2016-04-28 21:28:11.286 ThaliTest[3782:8979428] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-28 21:28:11.289 ThaliTest[3782:8979428] jxcore: stopListeningForAdvertisements: success
,ok 140 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-28 21:28:11.292 ThaliTest[3782:8979428] jxcore: stopAdvertisingAndListening
2016-04-28 21:28:11.292 ThaliTest[3782:8979428] THEMultipeerManager stopping peer
2016-04-28 21:28:11.292 ThaliTest[3782:8979428] jxcore: stopAdvertisingAndListening: suc,cess
ok 141 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 35. Calling startListeningForAdvertisements twice is NOT an error
,2016-04-28 21:28:11.846 ThaliTest[3782:8979428] jxcore: startListeningForAdvertisements
2016-04-28 21:28:11.847 ThaliTest[3782:8979428] multipeer manager: start client restart timer: 0x15de6860
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-28 21:28:11.849 ThaliTest[3782:8979428] jxcore: startListeningForAdvertisements: success
,ok 142 Can call startListeningForAdvertisements without error
2016-04-28 21:28:11.853 ThaliTest[3782:8979428] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"disco,veryActive":true}
2016-04-28 21:28:11.855 ThaliTest[3782:8979428] jxcore: startListeningForAdvertisements: success
ok 143 Can call startListeningForAdvertisements twice without error
,# teardown
,2016-04-28 21:28:13.607 ThaliTest[3782:8979428] jxcore: stopListeningForAdvertisements
2016-04-28 21:28:13.608 ThaliTest[3782:8979428] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-28 21:28:13.610 ThaliTest[3782:8979428] jxcore: stopListeningForAdvertisements: success
ok 144 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-28 21:28:13.614 ThaliTest[3782:8979428] jxcore: stopAdvertisingAndListening
2016-04-28 21:28:13.614 ThaliTest[3782:8979428] THEMultipeerManager stopping peer
2016-04-28 21:28:13.615 ThaliTest[3782:8979428] jxcore: stopAdvertisingAndListening: success
ok 145 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 36. Calling stopListeningForAdvertisements without calling start is NOT an error
,2016-04-28 21:28:28.585 ThaliTest[3782:8979428] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-28 21:28:28.587 ThaliTest[3782:8979428] jxcore: stopListeningForAdvertisements: success
,ok 146 Can call stopListeningForAdvertisements without error
,2016-04-28 21:28:28.590 ThaliTest[3782:8979428] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-28 21:28:28.592 ThaliTest[3782:8979428] jxcore: stopListeningForAdvertisements: success
ok 147 Can call stopListeningForAdvertisements without error
,# teardown
,2016-04-28 21:28:28.733 ThaliTest[3782:8979428] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-28 21:28:28.735 ThaliTest[3782:8979428] jxcore: stopListeningForAdvertisements: success
,ok 148 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-28 21:28:28.738 ThaliTest[3782:8979428] jxcore: stopAdvertisingAndListening
2016-04-28 21:28:28.739 ThaliTest[3782:8979428] THEMultipeerManager stopping peer
2016-04-28 21:28:28.739 ThaliTest[3782:8979428] jxcore: stopAdvertisingAndListening: suc,cess
ok 149 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 37. Can call start/stopUpdateAdvertisingAndListening
,2016-04-28 21:28:29.041 ThaliTest[3782:8979428] jxcore: startUpdateAdvertisingAndListening
2016-04-28 21:28:29.041 ThaliTest[3782:8979428] server: starting C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:4
2016-04-28 21:28:29.042 ThaliTest[3782:8979428] multipeer m,anager: start client restart timer: 0x15de6860
2016-04-28 21:28:29.042 ThaliTest[3782:8979428] THEMultipeerManager initialized peer C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:4
,2016-04-28 21:28:29.043 ThaliTest[3782:8979428] jxcore: startUpdateAdvertisingAndListening: success
,ok 150 Can call startUpdateAdvertisingAndListening without error
2016-04-28 21:28:29.046 ThaliTest[3782:8979428] jxcore: stopAdvertisingAndListening
2016-04-28 21:28:29.047 ThaliTest[3782:8979428] THEMultipeerManager stopping peer
2016-04-28 21:28:29.04,7 ThaliTest[3782:8979428] multipeer manager: stop client timer
2016-04-28 21:28:29.047 ThaliTest[3782:8979428] jxcore: stopAdvertisingAndListening: success
ok 151 Can call stopAdvertisingAndListening without error
# teardown
,2016-04-28 21:28:29.335 ThaliTest[3782:8979428] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-28 21:28:29.337 ThaliTest[3782:8979428] jxcore: stopListeningForAdvertisements: success
,ok 152 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-28 21:28:29.340 ThaliTest[3782:8979428] jxcore: stopAdvertisingAndListening
2016-04-28 21:28:29.340 ThaliTest[3782:8979428] THEMultipeerManager stopping peer
2016-04-28 21:28:29.341 ThaliTest[3782:8979428] jxcore: stopAdvertisingAndListening: suc,cess
ok 153 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-04-28 21:28:33.019 ThaliTest[3782:8979428] jxcore: startUpdateAdvertisingAndListening
2016-04-28 21:28:33.020 ThaliTest[3782:8979428] server: starting C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:5
2016-04-28 21:28:33.021 ThaliTest[3782:8979428] multipeer m,anager: start client restart timer: 0x15de6860
2016-04-28 21:28:33.022 ThaliTest[3782:8979428] THEMultipeerManager initialized peer C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:5
2016-04-28 21:28:33.022 ThaliTest[3782:8979428] jxcore: startUpdateAdvertisingAndListening: success
ok 154 Can call startUpdateAdvertisingAndListening without error
,2016-04-28 21:28:33.026 ThaliTest[3782:8979428] jxcore: startUpdateAdvertisingAndListening
2016-04-28 21:28:33.027 ThaliTest[3782:8979428] THEMultipeerManager stopping peer
2016-04-28 21:28:33.027 ThaliTest[3782:8979428] multipeer manager: stop client ti,mer
2016-04-28 21:28:33.028 ThaliTest[3782:8979428] server: starting C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:6
2016-04-28 21:28:33.028 ThaliTest[3782:8979428] multipeer manager: start client restart timer: 0x15de6860
2016-04-28 21:28:33.029 ThaliTest[3782:,8979428] THEMultipeerManager initialized peer C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:6
,2016-04-28 21:28:33.029 ThaliTest[3782:8979428] jxcore: startUpdateAdvertisingAndListening: success
ok 155 Can call startUpdateAdvertisingAndListening twice without error
# teardown
,2016-04-28 21:28:34.337 ThaliTest[3782:8979182] client: found new peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:6
,2016-04-28 21:28:34.974 ThaliTest[3782:8979182] client: found new peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:6
,2016-04-28 21:28:36.129 ThaliTest[3782:8979428] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-28 21:28:36.131 ThaliTest[3782:8979428] jxcore: stopListeningForAdvertisements: success
ok 156 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-28 21:28:36.134 ThaliTest[3782:8979428] jxcore: stopAdvertisingAndListening
2016-04-28 21:28:36.134 ThaliTest[3782:8979428] THEMultipeerManager stopping peer
2016-04-28 21:28:36.134 ThaliTest[3782:8979428] multipeer manager: stop client timer
2016-04-28 21:28:36.135 ThaliTest[3782:8979428] jxcore: stopAdvertisingAndListening: success
ok 157 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,2016-04-28 21:28:36.889 ThaliTest[3782:8979428] jxcore: stopAdvertisingAndListening
2016-04-28 21:28:36.889 ThaliTest[3782:8979428] THEMultipeerManager stopping peer
2016-04-28 21:28:36.889 ThaliTest[3782:8979428] jxcore: stopAdvertisingAndListening: suc,cess
ok 158 Can call startUpdateAdvertisingAndListening without error
,2016-04-28 21:28:36.892 ThaliTest[3782:8979428] jxcore: stopAdvertisingAndListening
2016-04-28 21:28:36.892 ThaliTest[3782:8979428] THEMultipeerManager stopping peer
2016-04-28 21:28:36.893 ThaliTest[3782:8979428] jxcore: stopAdvertisingAndListening: success
,ok 159 Can call stopAdvertisingAndListening without error
,# teardown
,2016-04-28 21:28:38.797 ThaliTest[3782:8979428] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-28 21:28:38.800 ThaliTest[3782:8979428] jxcore: stopListeningForAdvertisements: success
,ok 160 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-28 21:28:38.803 ThaliTest[3782:8979428] jxcore: stopAdvertisingAndListening
2016-04-28 21:28:38.803 ThaliTest[3782:8979428] THEMultipeerManager stopping peer
2016-04-28 21:28:38.803 ThaliTest[3782:8979428] jxcore: stopAdvertisingAndListening: suc,cess
ok 161 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 40. cannot call connect when start listening for advertisements is not active
,2016-04-28 21:28:56.950 ThaliTest[3782:8979428] jxcore: connect foo
2016-04-28 21:28:56.950 ThaliTest[3782:8979428] jxcore: connect: fail: Start browsing first
,not ok 162 got right error
,  ---
,    operator: equal
,    expected: 'startListeningForAdvertisements is not active'
,    actual:   'Start browsing first'
,  ...
,# teardown
,2016-04-28 21:28:57.179 ThaliTest[3782:8979428] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-28 21:28:57.181 ThaliTest[3782:8979428] jxcore: stopListeningForAdvertisements: success
,ok 163 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-28 21:28:57.184 ThaliTest[3782:8979428] jxcore: stopAdvertisingAndListening
2016-04-28 21:28:57.184 ThaliTest[3782:8979428] THEMultipeerManager stopping peer
2016-04-28 21:28:57.184 ThaliTest[3782:8979428] jxcore: stopAdvertisingAndListening: success
ok 164 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 41. peerAvailabilityChange is called
,2016-04-28 21:29:00.338 ThaliTest[3782:8979428] jxcore: startUpdateAdvertisingAndListening
2016-04-28 21:29:00.339 ThaliTest[3782:8979428] server: starting C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:7
2016-04-28 21:29:00.340 ThaliTest[3782:8979428] multipeer m,anager: start client restart timer: 0x15de6860
2016-04-28 21:29:00.340 ThaliTest[3782:8979428] THEMultipeerManager initialized peer C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:7
2016-04-28 21:29:00.341 ThaliTest[3782:8979428] jxcore: startUpdateAdvertisingAndListening: success
ok 165 Can call startUpdateAdvertisingAndListeningwithout error
,2016-04-28 21:29:00.344 ThaliTest[3782:8979428] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
,2016-04-28 21:29:00.347 ThaliTest[3782:8979428] jxcore: startListeningForAdvertisements: success
ok 166 Can call startListeningForAdvertisements without error
,2016-04-28 21:29:00.363 ThaliTest[3782:8979182] client: found new peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:6
ok 167 peers must be an array
,ok 168 peers must not be zero-length
ok 169 peer must have peerIdentifier
,ok 170 peerIdentifier must be a string
,ok 171 peer must have peerAvailable
,ok 172 peer must have pleaseConnect
,# teardown
,2016-04-28 21:29:01.840 ThaliTest[3782:8979182] client: found new peer: 30403743-C17E-454C-8124-9D59A7B25203:7
2016-04-28 21:29:01.841 ThaliTest[3782:8979182] client: found new peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:7
,2016-04-28 21:29:04.109 ThaliTest[3782:8979428] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-28 21:29:04.111 ThaliTest[3782:8979428] jxcore: stopListeningForAdvertisements: success
,ok 173 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-28 21:29:04.114 ThaliTest[3782:8979428] jxcore: stopAdvertisingAndListening
2016-04-28 21:29:04.115 ThaliTest[3782:8979428] THEMultipeerManager stopping peer
2016-04-28 21:29:04.115 ThaliTest[3782:8979428] multipeer manager: stop client timer
20,16-04-28 21:29:04.115 ThaliTest[3782:8979428] jxcore: stopAdvertisingAndListening: success
ok 174 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 42. Can connect to a remote peer
,2016-04-28 21:29:05.257 ThaliTest[3782:8979428] jxcore: startUpdateAdvertisingAndListening
2016-04-28 21:29:05.257 ThaliTest[3782:8979428] server: starting C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:29:05.258 ThaliTest[3782:8979428] multipeer m,anager: start client restart timer: 0x15de6860
2016-04-28 21:29:05.258 ThaliTest[3782:8979428] THEMultipeerManager initialized peer C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:29:05.259 ThaliTest[3782:8979428] jxcore: startUpdateAdvertisingAndLi,stening: success
,ok 175 Can call startUpdateAdvertisingAndListening without error
,2016-04-28 21:29:05.265 ThaliTest[3782:8979428] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-04-28 21:29:05.269 ThaliTest[3782:8979428] jxcore: startListeningForAdvertisements: success
ok 176 Can call startListeningForAdvertisements without error
,2016-04-28 21:29:05.643 ThaliTest[3782:8979182] client: found new peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7
2016-04-28 21:29:05.643 ThaliTest[3782:8979182] client: found new peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:7
INFO testThaliMobileNative: Rece,ived peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"418CC5DB-B63A-41DA-9996-4D5D4125B76C:7","pleaseConnect":0}]
2016-04-28 21:29:05.647 ThaliTest[3782:8979428] jxcore: connect 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7
2016-04-28 2,1:29:05.648 ThaliTest[3782:8979428] client session: connect
,2016-04-28 21:29:05.649 ThaliTest[3782:8979428] client session: stateChange:0->1 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"337492EA-97B4-404F-B8FE-E0E7631E59C8:7","pleaseConnect":0}]
,2016-04-28 21:29:06.215 ThaliTest[3782:8979182] client: found new peer: 30403743-C17E-454C-8124-9D59A7B25203:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"30403743-C17E-454C-8124-9D59A7B25,203:7","pleaseConnect":0}]
,2016-04-28 21:29:06.732 ThaliTest[3782:8979874] client session: not connected 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7
2016-04-28 21:29:06.733 ThaliTest[3782:8979874] client session: onLinkFailure: 418CC5DB-B63A-41DA-9996-4D5D4125B76C
2016-04-28 21:29:06.733 ThaliTest[3782:8979874] client session: disconnect
,2016-04-28 21:29:06.733 ThaliTest[3782:8979874] client session: stateChange:1->0 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7
,2016-04-28 21:29:06.736 ThaliTest[3782:8979874] client session: fireConnectCallback: 418CC5DB-B63A-41DA-9996-4D5D4125B76C
2016-04-28 21:29:06.737 ThaliTest[3782:8979874] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-04-28 21:29:08.254 ThaliTest[3782:8979182] multipeer session: reset timer
2016-04-28 21:29:08.255 ThaliTest[3782:8979182] server: rejecting invitation from 30403743-C17E-454C-8124-9D59A7B25203 due to previous generation (C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8 != C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:7)
,2016-04-28 21:29:09.748 ThaliTest[3782:8979428] jxcore: connect 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7
2016-04-28 21:29:09.749 ThaliTest[3782:8979428] client session: connect
2016-04-28 21:29:09.749 ThaliTest[3782:8979428] client session: stateChange:0->,1 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7
,2016-04-28 21:29:10.149 ThaliTest[3782:8979915] client session: not connected 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7
2016-04-28 21:29:10.149 ThaliTest[3782:8979915] client session: onLinkFailure: 418CC5DB-B63A-41DA-9996-4D5D4125B76C
2016-04-28 21:29:10.1,50 ThaliTest[3782:8979915] client session: disconnect
2016-04-28 21:29:10.150 ThaliTest[3782:8979915] client session: stateChange:1->0 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7
2016-04-28 21:29:10.151 ThaliTest[3782:8979915] client session: fireConnectCallb,ack: 418CC5DB-B63A-41DA-9996-4D5D4125B76C
,2016-04-28 21:29:10.152 ThaliTest[3782:8979915] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-04-28 21:29:13.164 ThaliTest[3782:8979428] jxcore: connect 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7
2016-04-28 21:29:13.164 ThaliTest[3782:8979428] client session: connect
2016-04-28 21:29:13.165 ThaliTest[3782:8979428] client session: stateChange:0->1 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7
,2016-04-28 21:29:13.269 ThaliTest[3782:8979875] client session: not connected 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7
2016-04-28 21:29:13.270 ThaliTest[3782:8979875] client session: onLinkFailure: 418CC5DB-B63A-41DA-9996-4D5D4125B76C
2016-04-28 21:29:13.2,71 ThaliTest[3782:8979875] client session: disconnect
2016-04-28 21:29:13.271 ThaliTest[3782:8979875] client session: stateChange:1->0 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7
,2016-04-28 21:29:13.272 ThaliTest[3782:8979875] client session: fireConnectCallback: 418CC5DB-B63A-41DA-9996-4D5D4125B76C
2016-04-28 21:29:13.273 ThaliTest[3782:8979875] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-04-28 21:29:16.283 ThaliTest[3782:8979428] jxcore: connect 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7
2016-04-28 21:29:16.284 ThaliTest[3782:8979428] client session: connect
2016-04-28 21:29:16.284 ThaliTest[3782:8979428] client session: stateChange:0->1 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7
,2016-04-28 21:29:16.420 ThaliTest[3782:8979875] client session: not connected 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7
2016-04-28 21:29:16.421 ThaliTest[3782:8979875] client session: onLinkFailure: 418CC5DB-B63A-41DA-9996-4D5D4125B76C
2016-04-28 21:29:16.4,21 ThaliTest[3782:8979875] client session: disconnect
2016-04-28 21:29:16.421 ThaliTest[3782:8979875] client session: stateChange:1->0 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7
,2016-04-28 21:29:16.424 ThaliTest[3782:8979875] client session: fireConnectCallback: 418CC5DB-B63A-41DA-9996-4D5D4125B76C
2016-04-28 21:29:16.424 ThaliTest[3782:8979875] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-04-28 21:29:19.431 ThaliTest[3782:8979428] jxcore: connect 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7
2016-04-28 21:29:19.432 ThaliTest[3782:8979428] client session: connect
2016-04-28 21:29:19.433 ThaliTest[3782:8979428] client session: stateChange:0->,1 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7
,2016-04-28 21:29:19.548 ThaliTest[3782:8979875] client session: not connected 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7
2016-04-28 21:29:19.548 ThaliTest[3782:8979875] client session: onLinkFailure: 418CC5DB-B63A-41DA-9996-4D5D4125B76C
,2016-04-28 21:29:19.549 ThaliTest[3782:8979875] client session: disconnect
,2016-04-28 21:29:19.551 ThaliTest[3782:8979875] client session: stateChange:1->0 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7
2016-04-28 21:29:19.552 ThaliTest[3782:8979875] client session: fireConnectCallback: 418CC5DB-B63A-41DA-9996-4D5D4125B76C
2016-04-28 21:29:19.552 ThaliTest[3782:8979875] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-04-28 21:29:19.716 ThaliTest[3782:8979182] multipeer session: reset timer
2016-04-28 21:29:19.717 ThaliTest[3782:8979182] server: disconnecting to refresh session (30403743-C17E-454C-8124-9D59A7B25203)
2016-04-28 21:29:19.718 ThaliTest[3782:8979182], server: rejecting invitation from 30403743-C17E-454C-8124-9D59A7B25203 due to previous generation (C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8 != C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:7)
,2016-04-28 21:29:22.567 ThaliTest[3782:8979428] jxcore: connect 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7
2016-04-28 21:29:22.568 ThaliTest[3782:8979428] client session: connect
2016-04-28 21:29:22.568 ThaliTest[3782:8979428] client session: stateChange:0->1 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7
,2016-04-28 21:29:22.693 ThaliTest[3782:8979915] client session: not connected 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7
2016-04-28 21:29:22.694 ThaliTest[3782:8979915] client session: onLinkFailure: 418CC5DB-B63A-41DA-9996-4D5D4125B76C
2016-04-28 21:29:22.6,94 ThaliTest[3782:8979915] client session: disconnect
2016-04-28 21:29:22.694 ThaliTest[3782:8979915] client session: stateChange:1->0 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7
2016-04-28 21:29:22.695 ThaliTest[3782:8979915] client session: fireConnectCallb,ack: 418CC5DB-B63A-41DA-9996-4D5D4125B76C
2016-04-28 21:29:22.695 ThaliTest[3782:8979915] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 4
,2016-04-28 21:29:25.260 ThaliTest[3782:8979182] multipeer manager: restart client
,2016-04-28 21:29:25.292 ThaliTest[3782:8979182] client: found updated peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:8
2016-04-28 21:29:25.292 ThaliTest[3782:8979182] client: found updated peer: 30403743-C17E-454C-8124-9D59A7B25203:8
2016-04-28 21:29:25.293 ,ThaliTest[3782:8979182] client: found updated peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"337492EA-97B4-404F-B8FE-E0E7631E59C8:8","pleaseConnec,t":0}]
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"30403743-C17E-454C-8124-9D59A7B25203:8","pleaseConnect":0}]
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{",peerAvailable":1,"peerIdentifier":"418CC5DB-B63A-41DA-9996-4D5D4125B76C:8","pleaseConnect":0}]
,2016-04-28 21:29:25.707 ThaliTest[3782:8979428] jxcore: connect 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7
2016-04-28 21:29:25.707 ThaliTest[3782:8979428] client session: connect
2016-04-28 21:29:25.708 ThaliTest[3782:8979428] client session: stateChange:0->,1 418CC5DB-B63A-41DA-9996-4D5D4125B76C:8
,2016-04-28 21:29:25.871 ThaliTest[3782:8979915] client session: not connected 418CC5DB-B63A-41DA-9996-4D5D4125B76C:8
2016-04-28 21:29:25.872 ThaliTest[3782:8979915] client session: onLinkFailure: 418CC5DB-B63A-41DA-9996-4D5D4125B76C
2016-04-28 21:29:25.8,73 ThaliTest[3782:8979915] client session: disconnect
2016-04-28 21:29:25.873 ThaliTest[3782:8979915] client session: stateChange:1->0 418CC5DB-B63A-41DA-9996-4D5D4125B76C:8
,2016-04-28 21:29:25.875 ThaliTest[3782:8979915] client session: fireConnectCallback: 418CC5DB-B63A-41DA-9996-4D5D4125B76C
2016-04-28 21:29:25.876 ThaliTest[3782:8979915] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-04-28 21:29:28.881 ThaliTest[3782:8979428] jxcore: connect 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7
2016-04-28 21:29:28.882 ThaliTest[3782:8979428] client session: connect
2016-04-28 21:29:28.882 ThaliTest[3782:8979428] client session: stateChange:0->1 418CC5DB-B63A-41DA-9996-4D5D4125B76C:8
,2016-04-28 21:29:28.977 ThaliTest[3782:8979915] client session: not connected 418CC5DB-B63A-41DA-9996-4D5D4125B76C:8
2016-04-28 21:29:28.978 ThaliTest[3782:8979915] client session: onLinkFailure: 418CC5DB-B63A-41DA-9996-4D5D4125B76C
2016-04-28 21:29:28.9,78 ThaliTest[3782:8979915] client session: disconnect
2016-04-28 21:29:28.978 ThaliTest[3782:8979915] client session: stateChange:1->0 418CC5DB-B63A-41DA-9996-4D5D4125B76C:8
,2016-04-28 21:29:28.982 ThaliTest[3782:8979915] client session: fireConnectCallback: 418CC5DB-B63A-41DA-9996-4D5D4125B76C
2016-04-28 21:29:28.982 ThaliTest[3782:8979915] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-04-28 21:29:31.994 ThaliTest[3782:8979428] jxcore: connect 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7
2016-04-28 21:29:31.995 ThaliTest[3782:8979428] client session: connect
2016-04-28 21:29:31.996 ThaliTest[3782:8979428] client session: stateChange:0->1 418CC5DB-B63A-41DA-9996-4D5D4125B76C:8
,2016-04-28 21:29:32.162 ThaliTest[3782:8980030] client session: not connected 418CC5DB-B63A-41DA-9996-4D5D4125B76C:8
2016-04-28 21:29:32.163 ThaliTest[3782:8980030] client session: onLinkFailure: 418CC5DB-B63A-41DA-9996-4D5D4125B76C
2016-04-28 21:29:32.163 ThaliTest[3782:8980030] client session: disconnect
,2016-04-28 21:29:32.164 ThaliTest[3782:8980030] client session: stateChange:1->0 418CC5DB-B63A-41DA-9996-4D5D4125B76C:8
,2016-04-28 21:29:32.167 ThaliTest[3782:8980030] client session: fireConnectCallback: 418CC5DB-B63A-41DA-9996-4D5D4125B76C
,2016-04-28 21:29:32.168 ThaliTest[3782:8980030] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-04-28 21:29:32.748 ThaliTest[3782:8979182] multipeer session: reset timer
2016-04-28 21:29:32.749 ThaliTest[3782:8979182] server: disconnecting to refresh session (30403743-C17E-454C-8124-9D59A7B25203)
2016-04-28 21:29:32.750 ThaliTest[3782:8979182], server: rejecting invitation from 30403743-C17E-454C-8124-9D59A7B25203 due to previous generation (C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8 != C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:7)
,2016-04-28 21:29:35.175 ThaliTest[3782:8979428] jxcore: connect 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7
2016-04-28 21:29:35.176 ThaliTest[3782:8979428] client session: connect
2016-04-28 21:29:35.176 ThaliTest[3782:8979428] client session: stateChange:0->1 418CC5DB-B63A-41DA-9996-4D5D4125B76C:8
,2016-04-28 21:29:35.262 ThaliTest[3782:8980030] client session: not connected 418CC5DB-B63A-41DA-9996-4D5D4125B76C:8
2016-04-28 21:29:35.262 ThaliTest[3782:8980030] client session: onLinkFailure: 418CC5DB-B63A-41DA-9996-4D5D4125B76C
2016-04-28 21:29:35.2,63 ThaliTest[3782:8980030] client session: disconnect
2016-04-28 21:29:35.263 ThaliTest[3782:8980030] client session: stateChange:1->0 418CC5DB-B63A-41DA-9996-4D5D4125B76C:8
,2016-04-28 21:29:35.266 ThaliTest[3782:8980030] client session: fireConnectCallback: 418CC5DB-B63A-41DA-9996-4D5D4125B76C
2016-04-28 21:29:35.266 ThaliTest[3782:8980030] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,WARN testThaliMobileNative: Too many connect retries!
,not ok 177 Connect failed!
,  ---
,    operator: fail
,  ...
,# teardown
,2016-04-28 21:29:45.260 ThaliTest[3782:8979182] multipeer manager: restart client
,2016-04-28 21:29:45.292 ThaliTest[3782:8979182] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:8
2016-04-28 21:29:45.293 ThaliTest[3782:8979182] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:8
2016-04-28 21:29:45.29,3 ThaliTest[3782:8979182] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:8
,2016-04-28 21:29:58.506 ThaliTest[3782:8979182] multipeer session: reset timer
2016-04-28 21:29:58.507 ThaliTest[3782:8979182] server: disconnecting to refresh session (30403743-C17E-454C-8124-9D59A7B25203)
2016-04-28 21:29:58.507 ThaliTest[3782:8979182], server: rejecting invitation from 30403743-C17E-454C-8124-9D59A7B25203 due to previous generation (C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8 != C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:7)
,2016-04-28 21:30:05.260 ThaliTest[3782:8979182] multipeer manager: restart client
,2016-04-28 21:30:05.288 ThaliTest[3782:8979182] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:8
2016-04-28 21:30:05.289 ThaliTest[3782:8979182] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:8
2016-04-28 21:30:05.289 ThaliTest[3782:8979182] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:8
,2016-04-28 21:30:12.131 ThaliTest[3782:8979182] multipeer session: reset timer
2016-04-28 21:30:12.132 ThaliTest[3782:8979182] server: disconnecting to refresh session (30403743-C17E-454C-8124-9D59A7B25203)
2016-04-28 21:30:12.133 ThaliTest[3782:8979182] server: rejecting invitation from 30403743-C17E-454C-8124-9D59A7B25203 due to previous generation (C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8 != C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:7)
,2016-04-28 21:30:24.735 ThaliTest[3782:8979182] multipeer session: reset timer
2016-04-28 21:30:24.736 ThaliTest[3782:8979182] server: disconnecting to refresh session (30403743-C17E-454C-8124-9D59A7B25203)
2016-04-28 21:30:24.736 ThaliTest[3782:8979182], server: rejecting invitation from 30403743-C17E-454C-8124-9D59A7B25203 due to previous generation (C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8 != C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:7)
,2016-04-28 21:30:25.260 ThaliTest[3782:8979182] multipeer manager: restart client
,2016-04-28 21:30:25.295 ThaliTest[3782:8979182] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:8
2016-04-28 21:30:25.296 ThaliTest[3782:8979182] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:8
2016-04-28 21:30:25.296 ThaliTest[3782:8979182] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:8
,2016-04-28 21:30:38.591 ThaliTest[3782:8979182] multipeer session: reset timer
2016-04-28 21:30:38.591 ThaliTest[3782:8979182] server: disconnecting to refresh session (30403743-C17E-454C-8124-9D59A7B25203)
2016-04-28 21:30:38.592 ThaliTest[3782:8979182], server: rejecting invitation from 30403743-C17E-454C-8124-9D59A7B25203 due to previous generation (C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8 != C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:7)
,2016-04-28 21:30:45.260 ThaliTest[3782:8979182] multipeer manager: restart client
,2016-04-28 21:30:45.287 ThaliTest[3782:8979182] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:8
2016-04-28 21:30:45.288 ThaliTest[3782:8979182] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:8
2016-04-28 21:30:45.28,8 ThaliTest[3782:8979182] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:8
,2016-04-28 21:30:50.960 ThaliTest[3782:8979182] multipeer session: reset timer
2016-04-28 21:30:50.961 ThaliTest[3782:8979182] server: disconnecting to refresh session (30403743-C17E-454C-8124-9D59A7B25203)
2016-04-28 21:30:50.961 ThaliTest[3782:8979182], server: rejecting invitation from 30403743-C17E-454C-8124-9D59A7B25203 due to previous generation (C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8 != C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:7)
,2016-04-28 21:31:03.498 ThaliTest[3782:8979182] multipeer session: reset timer
2016-04-28 21:31:03.499 ThaliTest[3782:8979182] server: disconnecting to refresh session (30403743-C17E-454C-8124-9D59A7B25203)
2016-04-28 21:31:03.499 ThaliTest[3782:8979182] server: rejecting invitation from 30403743-C17E-454C-8124-9D59A7B25203 due to previous generation (C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8 != C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:7)
,2016-04-28 21:31:05.260 ThaliTest[3782:8979182] multipeer manager: restart client
,2016-04-28 21:31:05.294 ThaliTest[3782:8979182] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:8
2016-04-28 21:31:05.296 ThaliTest[3782:8979182] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:8
2016-04-28 21:31:05.297 ThaliTest[3782:8979182] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:8
,2016-04-28 21:31:17.852 ThaliTest[3782:8979428] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-28 21:31:17.854 ThaliTest[3782:8979428] jxcore: stopListeningForAdvertisements: success
,ok 178 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-28 21:31:17.857 ThaliTest[3782:8979428] jxcore: stopAdvertisingAndListening
2016-04-28 21:31:17.858 ThaliTest[3782:8979428] THEMultipeerManager stopping peer
2016-04-28 21:31:17.858 ThaliTest[3782:8979428] multipeer manager: stop client timer
20,16-04-28 21:31:17.859 ThaliTest[3782:8979428] jxcore: stopAdvertisingAndListening: success
ok 179 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 43. Get error when trying to double connect to a peer
,2016-04-28 21:31:19.752 ThaliTest[3782:8979428] jxcore: startUpdateAdvertisingAndListening
2016-04-28 21:31:19.753 ThaliTest[3782:8979428] server: starting C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:31:19.753 ThaliTest[3782:8979428] multipeer m,anager: start client restart timer: 0x15de6860
2016-04-28 21:31:19.754 ThaliTest[3782:8979428] THEMultipeerManager initialized peer C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:31:19.754 ThaliTest[3782:8979428] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 180 Can call startUpdateAdvertisingAndListening without error
2016-04-28 21:31:19.756 ThaliTest[3782:8979428] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-04-28 21:31:19.758 ThaliTest[3782:8979428] jxcore: startListeningForAdvertisements: success
,ok 181 Can call startListeningForAdvertisements without error
,2016-04-28 21:31:20.089 ThaliTest[3782:8979182] client: found new peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:8
2016-04-28 21:31:20.089 ThaliTest[3782:8979182] client: found new peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:8
2016-04-28 21:31:20.092 ThaliTes,t[3782:8979428] jxcore: connect 337492EA-97B4-404F-B8FE-E0E7631E59C8:8
2016-04-28 21:31:20.092 ThaliTest[3782:8979428] client session: connect
,2016-04-28 21:31:20.093 ThaliTest[3782:8979428] client session: stateChange:0->1 337492EA-97B4-404F-B8FE-E0E7631E59C8:8
,2016-04-28 21:31:20.695 ThaliTest[3782:8979182] multipeer session: reset timer
2016-04-28 21:31:20.695 ThaliTest[3782:8979182] server: rejecting invitation from 337492EA-97B4-404F-B8FE-E0E7631E59C8 due to previous generation (C1CF11DB-5459-4FAE-B6AA-38A4A,647C3FF:9 != C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8)
,2016-04-28 21:31:20.867 ThaliTest[3782:8980282] client session: not connected 337492EA-97B4-404F-B8FE-E0E7631E59C8:8
2016-04-28 21:31:20.868 ThaliTest[3782:8980282] client session: onLinkFailure: 337492EA-97B4-404F-B8FE-E0E7631E59C8
2016-04-28 21:31:20.8,68 ThaliTest[3782:8980282] client session: disconnect
2016-04-28 21:31:20.869 ThaliTest[3782:8980282] client session: stateChange:1->0 337492EA-97B4-404F-B8FE-E0E7631E59C8:8
,2016-04-28 21:31:20.871 ThaliTest[3782:8980282] client session: fireConnectCallback: 337492EA-97B4-404F-B8FE-E0E7631E59C8
,2016-04-28 21:31:20.871 ThaliTest[3782:8980282] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-04-28 21:31:21.711 ThaliTest[3782:8979182] multipeer session: reset timer
2016-04-28 21:31:21.712 ThaliTest[3782:8979182] server: rejecting invitation from 418CC5DB-B63A-41DA-9996-4D5D4125B76C due to previous generation (C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9 != C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8)
,2016-04-28 21:31:23.258 ThaliTest[3782:8979182] client: found new peer: 30403743-C17E-454C-8124-9D59A7B25203:8
,2016-04-28 21:31:23.785 ThaliTest[3782:8979182] multipeer session: reset timer
2016-04-28 21:31:23.785 ThaliTest[3782:8979182] server: rejecting invitation from 30403743-C17E-454C-8124-9D59A7B25203 due to previous generation (C1CF11DB-5459-4FAE-B6AA-38A4A,647C3FF:9 != C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8)
,2016-04-28 21:31:23.877 ThaliTest[3782:8979428] jxcore: connect 337492EA-97B4-404F-B8FE-E0E7631E59C8:8
2016-04-28 21:31:23.878 ThaliTest[3782:8979428] client session: connect
2016-04-28 21:31:23.878 ThaliTest[3782:8979428] client session: stateChange:0->1 337492EA-97B4-404F-B8FE-E0E7631E59C8:8
,2016-04-28 21:31:24.277 ThaliTest[3782:8980291] client session: not connected 337492EA-97B4-404F-B8FE-E0E7631E59C8:8
2016-04-28 21:31:24.278 ThaliTest[3782:8980291] client session: onLinkFailure: 337492EA-97B4-404F-B8FE-E0E7631E59C8
2016-04-28 21:31:24.278 ThaliTest[3782:8980291] client session: disconnect
2016-04-28 21:31:24.278 ThaliTest[3782:8980291] client session: stateChange:1->0 337492EA-97B4-404F-B8FE-E0E7631E59C8:8
,2016-04-28 21:31:24.281 ThaliTest[3782:8980291] client session: fireConnectCallback: 337492EA-97B4-404F-B8FE-E0E7631E59C8
2016-04-28 21:31:24.281 ThaliTest[3782:8980291] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returne,d an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-04-28 21:31:27.287 ThaliTest[3782:8979428] jxcore: connect 337492EA-97B4-404F-B8FE-E0E7631E59C8:8
2016-04-28 21:31:27.288 ThaliTest[3782:8979428] client session: connect
2016-04-28 21:31:27.288 ThaliTest[3782:8979428] client session: stateChange:0->1 337492EA-97B4-404F-B8FE-E0E7631E59C8:8
,2016-04-28 21:31:27.483 ThaliTest[3782:8980282] client session: not connected 337492EA-97B4-404F-B8FE-E0E7631E59C8:8
2016-04-28 21:31:27.484 ThaliTest[3782:8980282] client session: onLinkFailure: 337492EA-97B4-404F-B8FE-E0E7631E59C8
2016-04-28 21:31:27.4,84 ThaliTest[3782:8980282] client session: disconnect
2016-04-28 21:31:27.484 ThaliTest[3782:8980282] client session: stateChange:1->0 337492EA-97B4-404F-B8FE-E0E7631E59C8:8
,2016-04-28 21:31:27.487 ThaliTest[3782:8980282] client session: fireConnectCallback: 337492EA-97B4-404F-B8FE-E0E7631E59C8
2016-04-28 21:31:27.488 ThaliTest[3782:8980282] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-04-28 21:31:30.500 ThaliTest[3782:8979428] jxcore: connect 337492EA-97B4-404F-B8FE-E0E7631E59C8:8
2016-04-28 21:31:30.501 ThaliTest[3782:8979428] client session: connect
2016-04-28 21:31:30.502 ThaliTest[3782:8979428] client session: stateChange:0->1 337492EA-97B4-404F-B8FE-E0E7631E59C8:8
,2016-04-28 21:31:30.592 ThaliTest[3782:8980282] client session: not connected 337492EA-97B4-404F-B8FE-E0E7631E59C8:8
2016-04-28 21:31:30.594 ThaliTest[3782:8980282] client session: onLinkFailure: 337492EA-97B4-404F-B8FE-E0E7631E59C8
2016-04-28 21:31:30.5,94 ThaliTest[3782:8980282] client session: disconnect
2016-04-28 21:31:30.594 ThaliTest[3782:8980282] client session: stateChange:1->0 337492EA-97B4-404F-B8FE-E0E7631E59C8:8
2016-04-28 21:31:30.595 ThaliTest[3782:8980282] client session: fireConnectCallb,ack: 337492EA-97B4-404F-B8FE-E0E7631E59C8
2016-04-28 21:31:30.595 ThaliTest[3782:8980282] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-04-28 21:31:33.195 ThaliTest[3782:8979182] multipeer session: reset timer
2016-04-28 21:31:33.196 ThaliTest[3782:8979182] server: disconnecting to refresh session (337492EA-97B4-404F-B8FE-E0E7631E59C8)
2016-04-28 21:31:33.196 ThaliTest[3782:8979182], server: rejecting invitation from 337492EA-97B4-404F-B8FE-E0E7631E59C8 due to previous generation (C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9 != C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8)
,2016-04-28 21:31:33.307 ThaliTest[3782:8979182] multipeer session: reset timer
2016-04-28 21:31:33.308 ThaliTest[3782:8979182] server: disconnecting to refresh session (418CC5DB-B63A-41DA-9996-4D5D4125B76C)
2016-04-28 21:31:33.308 ThaliTest[3782:8979182], server: rejecting invitation from 418CC5DB-B63A-41DA-9996-4D5D4125B76C due to previous generation (C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9 != C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8)
,2016-04-28 21:31:33.609 ThaliTest[3782:8979428] jxcore: connect 337492EA-97B4-404F-B8FE-E0E7631E59C8:8
2016-04-28 21:31:33.609 ThaliTest[3782:8979428] client session: connect
2016-04-28 21:31:33.610 ThaliTest[3782:8979428] client session: stateChange:0->1 337492EA-97B4-404F-B8FE-E0E7631E59C8:8
,2016-04-28 21:31:33.831 ThaliTest[3782:8980200] client session: not connected 337492EA-97B4-404F-B8FE-E0E7631E59C8:8
2016-04-28 21:31:33.831 ThaliTest[3782:8980200] client session: onLinkFailure: 337492EA-97B4-404F-B8FE-E0E7631E59C8
2016-04-28 21:31:33.832 ThaliTest[3782:8980200] client session: disconnect
,2016-04-28 21:31:33.833 ThaliTest[3782:8980200] client session: stateChange:1->0 337492EA-97B4-404F-B8FE-E0E7631E59C8:8
2016-04-28 21:31:33.834 ThaliTest[3782:8980200] client session: fireConnectCallback: 337492EA-97B4-404F-B8FE-E0E7631E59C8
2016-04-28 2,1:31:33.835 ThaliTest[3782:8980200] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-04-28 21:31:35.995 ThaliTest[3782:8979182] multipeer session: reset timer
2016-04-28 21:31:35.995 ThaliTest[3782:8979182] server: disconnecting to refresh session (30403743-C17E-454C-8124-9D59A7B25203)
2016-04-28 21:31:35.996 ThaliTest[3782:8979182] server: rejecting invitation from 30403743-C17E-454C-8124-9D59A7B25203 due to previous generation (C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9 != C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8)
,2016-04-28 21:31:36.848 ThaliTest[3782:8979428] jxcore: connect 337492EA-97B4-404F-B8FE-E0E7631E59C8:8
2016-04-28 21:31:36.849 ThaliTest[3782:8979428] client session: connect
2016-04-28 21:31:36.849 ThaliTest[3782:8979428] client session: stateChange:0->1 337492EA-97B4-404F-B8FE-E0E7631E59C8:8
,2016-04-28 21:31:37.422 ThaliTest[3782:8980200] client session: not connected 337492EA-97B4-404F-B8FE-E0E7631E59C8:8
2016-04-28 21:31:37.423 ThaliTest[3782:8980200] client session: onLinkFailure: 337492EA-97B4-404F-B8FE-E0E7631E59C8
2016-04-28 21:31:37.4,24 ThaliTest[3782:8980200] client session: disconnect
2016-04-28 21:31:37.424 ThaliTest[3782:8980200] client session: stateChange:1->0 337492EA-97B4-404F-B8FE-E0E7631E59C8:8
2016-04-28 21:31:37.425 ThaliTest[3782:8980200] client session: fireConnectCallb,ack: 337492EA-97B4-404F-B8FE-E0E7631E59C8
2016-04-28 21:31:37.425 ThaliTest[3782:8980200] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 4
,2016-04-28 21:31:39.755 ThaliTest[3782:8979182] multipeer manager: restart client
,2016-04-28 21:31:39.779 ThaliTest[3782:8979182] client: found updated peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:31:39.780 ThaliTest[3782:8979182] client: found updated peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
,2016-04-28 21:31:39.784 ThaliTest[3782:8979182] client: found updated peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:31:40.436 ThaliTest[3782:8979428] jxcore: connect 337492EA-97B4-404F-B8FE-E0E7631E59C8:8
2016-04-28 21:31:40.437 ThaliTest[3782:8979428] client session: connect
2016-04-28 21:31:40.437 ThaliTest[3782:8979428] client session: stateChange:0->1 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
,2016-04-28 21:31:40.642 ThaliTest[3782:8980281] client session: not connected 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:31:40.642 ThaliTest[3782:8980281] client session: onLinkFailure: 337492EA-97B4-404F-B8FE-E0E7631E59C8
2016-04-28 21:31:40.642 ThaliTest[3782:8980281] client session: disconnect
2016-04-28 21:31:40.644 ThaliTest[3782:8980281] client session: stateChange:1->0 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
,2016-04-28 21:31:40.646 ThaliTest[3782:8980281] client session: fireConnectCallback: 337492EA-97B4-404F-B8FE-E0E7631E59C8
2016-04-28 21:31:40.646 ThaliTest[3782:8980281] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-04-28 21:31:43.658 ThaliTest[3782:8979428] jxcore: connect 337492EA-97B4-404F-B8FE-E0E7631E59C8:8
2016-04-28 21:31:43.658 ThaliTest[3782:8979428] client session: connect
2016-04-28 21:31:43.659 ThaliTest[3782:8979428] client session: stateChange:0->,1 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
,2016-04-28 21:31:43.790 ThaliTest[3782:8980291] client session: not connected 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
,2016-04-28 21:31:43.791 ThaliTest[3782:8980291] client session: onLinkFailure: 337492EA-97B4-404F-B8FE-E0E7631E59C8
,2016-04-28 21:31:43.791 ThaliTest[3782:8980291] client session: disconnect
,2016-04-28 21:31:43.793 ThaliTest[3782:8980291] client session: stateChange:1->0 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
,2016-04-28 21:31:43.795 ThaliTest[3782:8980291] client session: fireConnectCallback: 337492EA-97B4-404F-B8FE-E0E7631E59C8
,2016-04-28 21:31:43.795 ThaliTest[3782:8980291] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-04-28 21:31:46.355 ThaliTest[3782:8979182] multipeer session: reset timer
,2016-04-28 21:31:46.357 ThaliTest[3782:8979182] server: disconnecting to refresh session (418CC5DB-B63A-41DA-9996-4D5D4125B76C)
2016-04-28 21:31:46.358 ThaliTest[3782:8979182] server: rejecting invitation from 418CC5DB-B63A-41DA-9996-4D5D4125B76C due to p,revious generation (C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9 != C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8)
,2016-04-28 21:31:46.364 ThaliTest[3782:8979182] multipeer session: reset timer
2016-04-28 21:31:46.364 ThaliTest[3782:8979182] server: disconnecting to refresh session (337492EA-97B4-404F-B8FE-E0E7631E59C8)
2016-04-28 21:31:46.364 ThaliTest[3782:8979182], server: rejecting invitation from 337492EA-97B4-404F-B8FE-E0E7631E59C8 due to previous generation (C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9 != C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8)
,2016-04-28 21:31:46.807 ThaliTest[3782:8979428] jxcore: connect 337492EA-97B4-404F-B8FE-E0E7631E59C8:8
2016-04-28 21:31:46.807 ThaliTest[3782:8979428] client session: connect
2016-04-28 21:31:46.808 ThaliTest[3782:8979428] client session: stateChange:0->,1 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
,2016-04-28 21:31:46.885 ThaliTest[3782:8980281] client session: not connected 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:31:46.886 ThaliTest[3782:8980281] client session: onLinkFailure: 337492EA-97B4-404F-B8FE-E0E7631E59C8
,2016-04-28 21:31:46.886 ThaliTest[3782:8980281] client session: disconnect
2016-04-28 21:31:46.888 ThaliTest[3782:8980281] client session: stateChange:1->0 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:31:46.888 ThaliTest[3782:8980281] client sess,ion: fireConnectCallback: 337492EA-97B4-404F-B8FE-E0E7631E59C8
2016-04-28 21:31:46.889 ThaliTest[3782:8980281] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: ,Scheduling a connect retry - retries left: 1
,2016-04-28 21:31:49.607 ThaliTest[3782:8979182] multipeer session: reset timer
2016-04-28 21:31:49.607 ThaliTest[3782:8979182] server: disconnecting to refresh session (30403743-C17E-454C-8124-9D59A7B25203)
2016-04-28 21:31:49.608 ThaliTest[3782:8979182], server: rejecting invitation from 30403743-C17E-454C-8124-9D59A7B25203 due to previous generation (C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9 != C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8)
,2016-04-28 21:31:49.902 ThaliTest[3782:8979428] jxcore: connect 337492EA-97B4-404F-B8FE-E0E7631E59C8:8
2016-04-28 21:31:49.903 ThaliTest[3782:8979428] client session: connect
2016-04-28 21:31:49.903 ThaliTest[3782:8979428] client session: stateChange:0->1 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
,2016-04-28 21:31:50.041 ThaliTest[3782:8980282] client session: not connected 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
,2016-04-28 21:31:50.041 ThaliTest[3782:8980282] client session: onLinkFailure: 337492EA-97B4-404F-B8FE-E0E7631E59C8
2016-04-28 21:31:50.042 ThaliTest[3782:8980282] client session: disconnect
,2016-04-28 21:31:50.042 ThaliTest[3782:8980282] client session: stateChange:1->0 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
,2016-04-28 21:31:50.044 ThaliTest[3782:8980282] client session: fireConnectCallback: 337492EA-97B4-404F-B8FE-E0E7631E59C8
2016-04-28 21:31:50.044 ThaliTest[3782:8980282] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,WARN testThaliMobileNative: Too many connect retries!
,2016-04-28 21:31:59.755 ThaliTest[3782:8979182] multipeer manager: restart client
,2016-04-28 21:31:59.785 ThaliTest[3782:8979182] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:31:59.786 ThaliTest[3782:8979182] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:31:59.786 ThaliTest[3782:8979182] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:32:02.149 ThaliTest[3782:8979182] multipeer session: reset timer
2016-04-28 21:32:02.150 ThaliTest[3782:8979182] server: disconnecting to refresh session (30403743-C17E-454C-8124-9D59A7B25203)
2016-04-28 21:32:02.150 ThaliTest[3782:8979182], server: rejecting invitation from 30403743-C17E-454C-8124-9D59A7B25203 due to previous generation (C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9 != C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8)
,2016-04-28 21:32:15.626 ThaliTest[3782:8979182] multipeer session: reset timer
2016-04-28 21:32:15.626 ThaliTest[3782:8979182] server: disconnecting to refresh session (30403743-C17E-454C-8124-9D59A7B25203)
2016-04-28 21:32:15.627 ThaliTest[3782:8979182], server: rejecting invitation from 30403743-C17E-454C-8124-9D59A7B25203 due to previous generation (C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9 != C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8)
,2016-04-28 21:32:19.755 ThaliTest[3782:8979182] multipeer manager: restart client
,2016-04-28 21:32:19.790 ThaliTest[3782:8979182] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:32:19.790 ThaliTest[3782:8979182] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
2016-04-28 21:32:19.791 ThaliTest[3782:8979182] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
,2016-04-28 21:32:31.839 ThaliTest[3782:8979182] multipeer session: reset timer
2016-04-28 21:32:31.839 ThaliTest[3782:8979182] server: disconnecting to refresh session (30403743-C17E-454C-8124-9D59A7B25203)
2016-04-28 21:32:31.840 ThaliTest[3782:8979182], server: rejecting invitation from 30403743-C17E-454C-8124-9D59A7B25203 due to previous generation (C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9 != C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8)
,2016-04-28 21:32:39.755 ThaliTest[3782:8979182] multipeer manager: restart client
,2016-04-28 21:32:39.792 ThaliTest[3782:8979182] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:32:39.793 ThaliTest[3782:8979182] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
2016-04-28 21:32:39.793 ThaliTest[3782:8979182] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
,2016-04-28 21:32:59.755 ThaliTest[3782:8979182] multipeer manager: restart client
,2016-04-28 21:32:59.790 ThaliTest[3782:8979182] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:32:59.790 ThaliTest[3782:8979182] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:32:59.792 ThaliTest[3782:8979182] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:33:19.755 ThaliTest[3782:8979182] multipeer manager: restart client
,2016-04-28 21:33:19.790 ThaliTest[3782:8979182] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:33:19.791 ThaliTest[3782:8979182] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
2016-04-28 21:33:19.792 ThaliTest[3782:8979182] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
,2016-04-28 21:33:39.755 ThaliTest[3782:8979182] multipeer manager: restart client
,2016-04-28 21:33:39.792 ThaliTest[3782:8979182] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:33:39.793 ThaliTest[3782:8979182] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:33:39.79,5 ThaliTest[3782:8979182] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:33:59.755 ThaliTest[3782:8979182] multipeer manager: restart client
,2016-04-28 21:33:59.794 ThaliTest[3782:8979182] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:33:59.794 ThaliTest[3782:8979182] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
2016-04-28 21:33:59.794 ThaliTest[3782:8979182] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
,2016-04-28 21:34:19.755 ThaliTest[3782:8979182] multipeer manager: restart client
,2016-04-28 21:34:19.789 ThaliTest[3782:8979182] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:34:19.789 ThaliTest[3782:8979182] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:34:19.791 ThaliTest[3782:8979182] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:34:39.755 ThaliTest[3782:8979182] multipeer manager: restart client
,2016-04-28 21:34:39.788 ThaliTest[3782:8979182] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:34:39.791 ThaliTest[3782:8979182] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
,2016-04-28 21:34:39.795 ThaliTest[3782:8979182] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:34:59.755 ThaliTest[3782:8979182] multipeer manager: restart client
,2016-04-28 21:34:59.788 ThaliTest[3782:8979182] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:34:59.788 ThaliTest[3782:8979182] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:34:59.79,0 ThaliTest[3782:8979182] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:35:19.754 ThaliTest[3782:8979182] multipeer manager: restart client
,2016-04-28 21:35:19.792 ThaliTest[3782:8979182] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
2016-04-28 21:35:19.792 ThaliTest[3782:8979182] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:35:19.793 ThaliTest[3782:8979182] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
,2016-04-28 21:35:39.755 ThaliTest[3782:8979182] multipeer manager: restart client
,2016-04-28 21:35:39.789 ThaliTest[3782:8979182] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:35:39.790 ThaliTest[3782:8979182] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:35:39.792 ThaliTest[3782:8979182] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:35:59.755 ThaliTest[3782:8979182] multipeer manager: restart client
,2016-04-28 21:35:59.788 ThaliTest[3782:8979182] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:35:59.791 ThaliTest[3782:8979182] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
2016-04-28 21:35:59.791 ThaliTest[3782:8979182] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
,2016-04-28 21:36:19.755 ThaliTest[3782:8979182] multipeer manager: restart client
,2016-04-28 21:36:19.788 ThaliTest[3782:8979182] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:36:19.789 ThaliTest[3782:8979182] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:36:19.790 ThaliTest[3782:8979182] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:36:39.755 ThaliTest[3782:8979182] multipeer manager: restart client
,2016-04-28 21:36:39.788 ThaliTest[3782:8979182] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:36:39.789 ThaliTest[3782:8979182] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:36:39.791 ThaliTest[3782:8979182] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:36:59.755 ThaliTest[3782:8979182] multipeer manager: restart client
,2016-04-28 21:36:59.790 ThaliTest[3782:8979182] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:36:59.791 ThaliTest[3782:8979182] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
,2016-04-28 21:36:59.797 ThaliTest[3782:8979182] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:37:19.755 ThaliTest[3782:8979182] multipeer manager: restart client
,2016-04-28 21:37:19.788 ThaliTest[3782:8979182] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:37:19.788 ThaliTest[3782:8979182] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
,2016-04-28 21:37:19.791 ThaliTest[3782:8979182] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:37:39.755 ThaliTest[3782:8979182] multipeer manager: restart client
,2016-04-28 21:37:39.793 ThaliTest[3782:8979182] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:37:39.794 ThaliTest[3782:8979182] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:37:39.794 ThaliTest[3782:8979182] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:37:59.755 ThaliTest[3782:8979182] multipeer manager: restart client
,2016-04-28 21:37:59.793 ThaliTest[3782:8979182] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
2016-04-28 21:37:59.794 ThaliTest[3782:8979182] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:37:59.795 ThaliTest[3782:8979182] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
,2016-04-28 21:38:19.755 ThaliTest[3782:8979182] multipeer manager: restart client
,2016-04-28 21:38:19.792 ThaliTest[3782:8979182] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:38:19.792 ThaliTest[3782:8979182] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:38:19.794 ThaliTest[3782:8979182] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:38:39.755 ThaliTest[3782:8979182] multipeer manager: restart client
,2016-04-28 21:38:39.790 ThaliTest[3782:8979182] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:38:39.790 ThaliTest[3782:8979182] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
2016-04-28 21:38:39.791 ThaliTest[3782:8979182] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
,2016-04-28 21:38:59.755 ThaliTest[3782:8979182] multipeer manager: restart client
,2016-04-28 21:38:59.793 ThaliTest[3782:8979182] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
2016-04-28 21:38:59.794 ThaliTest[3782:8979182] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:38:59.795 ThaliTest[3782:8979182] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
,2016-04-28 21:39:19.755 ThaliTest[3782:8979182] multipeer manager: restart client
,2016-04-28 21:39:19.791 ThaliTest[3782:8979182] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:39:19.792 ThaliTest[3782:8979182] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
,2016-04-28 21:39:19.797 ThaliTest[3782:8979182] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:39:39.755 ThaliTest[3782:8979182] multipeer manager: restart client
,2016-04-28 21:39:39.791 ThaliTest[3782:8979182] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:39:39.791 ThaliTest[3782:8979182] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:39:39.794 ThaliTest[3782:8979182] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:39:59.755 ThaliTest[3782:8979182] multipeer manager: restart client
,2016-04-28 21:39:59.791 ThaliTest[3782:8979182] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:39:59.792 ThaliTest[3782:8979182] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:39:59.792 ThaliTest[3782:8979182] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:40:19.754 ThaliTest[3782:8979182] multipeer manager: restart client
,2016-04-28 21:40:19.789 ThaliTest[3782:8979182] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:40:19.790 ThaliTest[3782:8979182] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
,2016-04-28 21:40:19.797 ThaliTest[3782:8979182] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:40:39.755 ThaliTest[3782:8979182] multipeer manager: restart client
,2016-04-28 21:40:39.792 ThaliTest[3782:8979182] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:40:39.793 ThaliTest[3782:8979182] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:40:39.795 ThaliTest[3782:8979182] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:40:59.755 ThaliTest[3782:8979182] multipeer manager: restart client
,2016-04-28 21:40:59.790 ThaliTest[3782:8979182] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:40:59.791 ThaliTest[3782:8979182] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
2016-04-28 21:40:59.791 ThaliTest[3782:8979182] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
,2016-04-28 21:41:19.755 ThaliTest[3782:8979182] multipeer manager: restart client
,2016-04-28 21:41:19.790 ThaliTest[3782:8979182] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:41:19.791 ThaliTest[3782:8979182] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:41:19.792 ThaliTest[3782:8979182] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:41:39.755 ThaliTest[3782:8979182] multipeer manager: restart client
,2016-04-28 21:41:39.789 ThaliTest[3782:8979182] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:41:39.790 ThaliTest[3782:8979182] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:41:39.793 ThaliTest[3782:8979182] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:41:59.755 ThaliTest[3782:8979182] multipeer manager: restart client
,2016-04-28 21:41:59.790 ThaliTest[3782:8979182] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:41:59.791 ThaliTest[3782:8979182] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
,2016-04-28 21:41:59.795 ThaliTest[3782:8979182] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:42:19.755 ThaliTest[3782:8979182] multipeer manager: restart client
,2016-04-28 21:42:19.790 ThaliTest[3782:8979182] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:42:19.791 ThaliTest[3782:8979182] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:42:19.793 ThaliTest[3782:8979182] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:42:39.755 ThaliTest[3782:8979182] multipeer manager: restart client
,2016-04-28 21:42:39.794 ThaliTest[3782:8979182] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:42:39.794 ThaliTest[3782:8979182] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:42:39.796 ThaliTest[3782:8979182] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
,2016-04-28 21:42:59.755 ThaliTest[3782:8979182] multipeer manager: restart client
,2016-04-28 21:42:59.790 ThaliTest[3782:8979182] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:42:59.791 ThaliTest[3782:8979182] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:42:59.79,5 ThaliTest[3782:8979182] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:43:19.755 ThaliTest[3782:8979182] multipeer manager: restart client
,2016-04-28 21:43:19.790 ThaliTest[3782:8979182] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:43:19.790 ThaliTest[3782:8979182] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:43:19.791 ThaliTest[3782:8979182] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:43:39.755 ThaliTest[3782:8979182] multipeer manager: restart client
,2016-04-28 21:43:39.790 ThaliTest[3782:8979182] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:43:39.790 ThaliTest[3782:8979182] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:43:39.79,4 ThaliTest[3782:8979182] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:43:59.755 ThaliTest[3782:8979182] multipeer manager: restart client
,2016-04-28 21:43:59.791 ThaliTest[3782:8979182] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:43:59.792 ThaliTest[3782:8979182] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
,2016-04-28 21:43:59.793 ThaliTest[3782:8979182] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:44:19.702 ThaliTest[3782:8979182] multipeer manager: restart client
,2016-04-28 21:44:19.738 ThaliTest[3782:8979182] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
2016-04-28 21:44:19.738 ThaliTest[3782:8979182] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:44:19.739 ThaliTest[3782:8979182] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
,2016-04-28 21:44:39.702 ThaliTest[3782:8979182] multipeer manager: restart client
,2016-04-28 21:44:39.736 ThaliTest[3782:8979182] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:44:39.736 ThaliTest[3782:8979182] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
,2016-04-28 21:44:39.743 ThaliTest[3782:8979182] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:44:59.702 ThaliTest[3782:8979182] multipeer manager: restart client
,2016-04-28 21:44:59.737 ThaliTest[3782:8979182] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:44:59.738 ThaliTest[3782:8979182] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
,2016-04-28 21:44:59.744 ThaliTest[3782:8979182] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:45:19.702 ThaliTest[3782:8979182] multipeer manager: restart client
,2016-04-28 21:45:19.738 ThaliTest[3782:8979182] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:45:19.742 ThaliTest[3782:8979182] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:45:19.743 ThaliTest[3782:8979182] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:45:39.702 ThaliTest[3782:8979182] multipeer manager: restart client
,2016-04-28 21:45:39.738 ThaliTest[3782:8979182] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:45:39.739 ThaliTest[3782:8979182] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:45:39.741 ThaliTest[3782:8979182] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:45:59.702 ThaliTest[3782:8979182] multipeer manager: restart client
,2016-04-28 21:45:59.738 ThaliTest[3782:8979182] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:45:59.738 ThaliTest[3782:8979182] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:45:59.73,9 ThaliTest[3782:8979182] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:46:19.702 ThaliTest[3782:8979182] multipeer manager: restart client
,2016-04-28 21:46:19.737 ThaliTest[3782:8979182] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:46:19.737 ThaliTest[3782:8979182] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:46:19.739 ThaliTest[3782:8979182] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:46:39.702 ThaliTest[3782:8979182] multipeer manager: restart client
,2016-04-28 21:46:39.737 ThaliTest[3782:8979182] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
2016-04-28 21:46:39.737 ThaliTest[3782:8979182] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:46:39.73,7 ThaliTest[3782:8979182] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
,2016-04-28 21:46:59.702 ThaliTest[3782:8979182] multipeer manager: restart client
,2016-04-28 21:46:59.741 ThaliTest[3782:8979182] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:46:59.742 ThaliTest[3782:8979182] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:46:59.74,5 ThaliTest[3782:8979182] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9

```
