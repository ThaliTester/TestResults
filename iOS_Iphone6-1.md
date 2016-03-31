#### Test 646138038b5bc7c_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/646138038b5bc7c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/3D8CD87E-212F-4345-AA3D-9CE35D9A8925/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/3D8CD87E-212F-4345-AA3D-9CE35D9A8925/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/646138038b5bc7c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/646138038b5bc7c/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/92878505-E6C8-4F3E-8BCB-97184C43E65E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49912"
,(lldb)     command script import "/tmp/3D8CD87E-212F-4345-AA3D-9CE35D9A8925/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-31 17:38:46.306 ThaliTest[2543:4714632] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/58403E98-3EE8-4BA7-9E79-1A12DA386C88/Library/Cookies/Cookies.binarycookies
,2016-03-31 17:38:46.533 ThaliTest[2543:4714632] Apache Cordova native platform version 4.1.0 is starting.
,2016-03-31 17:38:46.534 ThaliTest[2543:4714632] Multi-tasking -> Device: YES, App: YES
,2016-03-31 17:38:46.551 ThaliTest[2543:4714632] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-31 17:38:47.334 ThaliTest[2543:4714632] Using UIWebView
2016-03-31 17:38:47.336 ThaliTest[2543:4714632] [CDVTimer][handleopenurl] 0.123024ms
,2016-03-31 17:38:47.338 ThaliTest[2543:4714632] [CDVTimer][intentandnavigationfilter] 2.528012ms
,2016-03-31 17:38:47.339 ThaliTest[2543:4714632] [CDVTimer][gesturehandler] 0.797987ms
2016-03-31 17:38:47.340 ThaliTest[2543:4714632] [CDVTimer][TotalPluginStartup] 4.060984ms
,2016-03-31 17:38:50.477 ThaliTest[2543:4714632] Resetting plugins due to page load.
,2016-03-31 17:38:51.702 ThaliTest[2543:4714632] Finished load of: file:///var/mobile/Containers/Bundle/Application/92878505-E6C8-4F3E-8BCB-97184C43E65E/ThaliTest.app/www/index.html
,2016-03-31 17:38:51.864 ThaliTest[2543:4714632] JXcore Cordova plugin initializing
,2016-03-31 17:38:51.866 ThaliTest[2543:4714797] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-31 17:38:58.839 ThaliTest[2543:4714797] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-31 17:38:58.841 ThaliTest[2543:4714797] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-31 17:38:58.841 ThaliTest[2543:4714797] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-31 17:38:58.843 ThaliTest[2543:4714797] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone6-1
,WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/92878505-E6C8-4F3E-8BCB-97184C43E65E/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/92878505-E6C8-4F3E-8BCB-97184C43E65E/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/92878505-E6C8-4F3E-8BCB-97184C43E65E/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/92878505-E6C8-4F3E-8BCB-97184C43E65E/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/92878505-E6C8-4F3E-8BCB-97184C43E65E/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/92878505-E6C8-4F3E-8BCB-97184C43E65E/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/92878505-E6C8-4F3E-8BCB-97184C43E65E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/92878505-E6C8-4F3E-8BCB-97184C43E65E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/92878505-E6C8-4F3E-8BCB-97184C43E65E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/92878505-E6C8-4F3E-8BCB-97184C43E65E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/92878505-E6C8-4F3E-8BCB-97184C43E65E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/92878505-E6C8-4F3E-8BCB-97184C43E65E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/92878505-E6C8-4F3E-8BCB-97184C43E65E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/92878505-E6C8-4F3E-8BCB-97184C43E65E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/92878505-E6C8-4F3E-8BCB-97184C43E65E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/92878505-E6C8-4F3E-8BCB-97184C43E65E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/92878505-E6C8-4F3E-8BCB-97184C43E65E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/92878505-E6C8-4F3E-8BCB-97184C43E65E/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/92878505-E6C8-4F3E-8BCB-97184C43E65E/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/92878505-E6C8-4F3E-8BCB-97184C43E65E/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/92878505-E6C8-4F3E-8BCB-97184C43E65E/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/92878505-E6C8-4F3E-8BCB-97184C43E65E/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55681
ok 1 Should throw
# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55683
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
ok 2 initial connection state should be CONNECTED
,DEBUG createNativeListener: incoming socket close
ok 3 final connection state should be DISCONNECTED
,# teardown
,# setup
,# 3. emits routerPortConnectionFailed
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55686
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
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
,DEBUG createNativeListener: listening 55690
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
DEBUG createNativeListener: listening 55695
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,ok 12 socket shouldn't close until after stream
ok 13 incoming remains open
# teardown
,DEBUG createNativeListener: mux close
# setup
DEBUG createNativeListener: incoming socket close
,# 6. native server - closing incoming connection cleans outgoing socket
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55699
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
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
DEBUG createNativeListener: listening 55703
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
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
,DEBUG createNativeListener: listening 55707
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
DEBUG createNativeListener: listening 55711
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeL,istener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
D,EBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creati,ng incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
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
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListene,r: new stream: 
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
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListene,r: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListene,r: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListene,r: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListene,r: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG cr,eateNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
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
DEBUG createNativeListener: mux close
DEBUG cr,eateNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
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
DEBUG createNativeListener: listening 55763
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,ok 31 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,ok 32 Buffers are identical
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
,DEBUG createNativeListener: incoming socket close
,ok 33 server should be fine
ok 34 server should be open
ok 35 incoming has been removed
ok 36 The mux object should be closed
ok 37 The mux stream should be closed
,# teardown
,# setup
,# 11. native server - timing out the incoming connection cleans everything up
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55767
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 38 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,ok 39 Buffers are identical
,DEBUG createNativeListener: incoming socket timeout
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: incoming socket close
ok 40 server should be fine
ok 41 server should be open
ok 42 incoming has been removed
ok 43 The mux object should be closed
ok 44 The mux stream should be closed
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
# teardown
,# setup
,# 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true
,# teardown
,# setup
,# 16. multiplex can send data
,ok 48 String should be length:200
,# teardown
,# setup
,# 17. enqueue and run in order
,ok 49 firstPromise setTimeout
ok 50 firstPromise result
ok 51 firstPromise testValue
,ok 52 secondPromise setTimeout
ok 53 secondPromise result
ok 54 secondPromise testValue
ok 55 thirdPromise in promise
ok 56 thirdPromise result
ok 57 thirdPromise testValue
# teardown
,# setup
,# 18. enqueueAtTop and run backwards
,ok 58 thirdPromise - first to run
ok 59 thirdPromise - in resolve
ok 60 secondPromise - second to run
ok 61 secondPromise - in catch
ok 62 firstPromise - third to run
ok 63 firstPromise - in then
ok 64 testing promises
# teardown
,# setup
,# 19. mix enqueue and enqueueAtTop
,ok 65 fourth
ok 66 fourth
ok 67 second
ok 68 secondPromise - in then
,ok 69 first
ok 70 firstPromise - in catch
ok 71 third
ok 72 thirdPromise - in then
ok 73 testingPromises
# teardown
,# setup
,# 20. queues handled independently
,ok 74 all short operations completed before the long resolves
,# teardown
,# setup
,# 21. basic
,ok 75 sane
,# teardown
,# setup
,# 22. another
,ok 76 sane
,# teardown
,# setup
,# 23. can pass data in setup
,[{"uuid":"93b06dd5-4156-4a62-b430-5e379b5bf668","data":"custom data"},{"uuid":"d360614e-eafc-47a4-b232-9db4049e83cd","data":"custom data"},{"uuid":"2d44cdcc-6331-4fd1-8321-40772b7965dd","data":"custom data"},{"uuid":"5a159754-f32d-49c6-9977-dc42c1fa4a99","data":"custom data"}]
ok 77 test participant has uuid
ok 78 participant data matches
ok 79 test participant has uuid
ok 80 participant data matches
ok 81 test participant has uuid
ok 82 participant data matches
ok 83 test participant has uuid
ok 84 participant data matches
ok 85 own UUID is found from the participants list
,# teardown
,# setup
,# 24. #startListeningForAdvertisements should fail if start not called
,ok 86 specific error should be returned
# teardown
,ok 87 error should be null
ok 88 error should be null
# setup
,# 25. #startUpdateAdvertisingAndListening should fail if start not called
,ok 89 specific error should be returned
# teardown
,ok 90 error should be null
ok 91 error should be null
# setup
,# 26. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55779
2016-03-31 17:41:32.760 ThaliTest[2543:4714797] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 17:41:32.761 ThaliTest[2543:4714797] jxcore: stopListeningForAdvertisements: success
ok 92 error should be null
ok 93 error should be null
2016-03-31 17:41:32.762 ThaliTest[2543:4714797] jx,core: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 17:41:32.763 ThaliTest[2543:4714797] jxcore: stopListeningForAdvertisements: success
ok 94 error should be null
ok 95 error should be null
# teardown
,2016-03-31 17:41:32.932 ThaliTest[2543:4714797] jxcore: stopAdvertisingAndListening
2016-03-31 17:41:32.932 ThaliTest[2543:4714797] THEMultipeerManager stopping peer
2016-03-31 17:41:32.932 ThaliTest[2543:4714797] jxcore: stopAdvertisingAndListening: success
2016-03-31 17:41:32.932 ThaliTest[2543:4714797] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 17:41:32.933 ThaliTest[2543,:4714797] jxcore: stopListeningForAdvertisements: success
ok 96 error should be null
ok 97 error should be null
# setup
,# 27. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55781
2016-03-31 17:41:33.268 ThaliTest[2543:4714797] jxcore: startListeningForAdvertisements
,2016-03-31 17:41:33.270 ThaliTest[2543:4714797] multipeer manager: start client restart timer: 0x166daad0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 17:41:33.270 ThaliTest[2543:4714797] jxcore: startListeningForAdvertisements: success
,ok 98 error should be null
ok 99 error should be null
2016-03-31 17:41:33.276 ThaliTest[2543:4714797] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 17:41:33.277 ThaliTest[2543:4714797] jxcore: startListeningForAdvertisements: success
ok 100 error should be null
ok 101 error should be null
# teardown
,2016-03-31 17:41:33.616 ThaliTest[2543:4714797] jxcore: stopAdvertisingAndListening
2016-03-31 17:41:33.616 ThaliTest[2543:4714797] THEMultipeerManager stopping peer
2016-03-31 17:41:33.616 ThaliTest[2543:4714797] jxcore: stopAdvertisingAndListening: success
2016-03-31 17:41:33.616 ThaliTest[2543:4714797] jxcore: stopListeningForAdvertisements
2016-03-31 17:41:33.616 ThaliTest[2543:4714797] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-31 17:41:33.617 ThaliTest[2543:4714797] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 102 error should be null
,ok 103 error should be null
,# setup
,# 28. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55783
,2016-03-31 17:41:34.156 ThaliTest[2543:4714797] jxcore: startUpdateAdvertisingAndListening
2016-03-31 17:41:34.157 ThaliTest[2543:4714797] server: starting B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:1
2016-03-31 17:41:34.157 ThaliTest[2543:4714797] multipeer manager: start client restart timer: 0x166daad0
2016-03-31 17:41:34.157 ThaliTest[2543:4714797] THEMultipeerManager initialized peer B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:1
2016-03-31 17:41:34.157 ThaliTest[2543:4714797] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 104 error should be null
ok 105 error should be null
2016-03-31 17:41:34.163 ThaliTest[2543:4714797] jxcore: startUpdateAdvertisingAndListening
2016-03-31 17:41:34.163 ThaliTest[2543:4714797] THEMultipeerManager stopping peer
2016-,03-31 17:41:34.163 ThaliTest[2543:4714797] multipeer manager: stop client timer
2016-03-31 17:41:34.164 ThaliTest[2543:4714797] server: starting B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:2
2016-03-31 17:41:34.164 ThaliTest[2543:4714797] multipeer manager: sta,rt client restart timer: 0x166daad0
2016-03-31 17:41:34.167 ThaliTest[2543:4714797] THEMultipeerManager initialized peer B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:2
2016-03-31 17:41:34.167 ThaliTest[2543:4714797] jxcore: startUpdateAdvertisingAndListening: success
,ok 106 error should be null
ok 107 error should be null
# teardown
,2016-03-31 17:41:35.354 ThaliTest[2543:4714632] client: found new peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:2
,2016-03-31 17:41:35.358 ThaliTest[2543:4714632] client: found new peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:2
,2016-03-31 17:41:36.721 ThaliTest[2543:4714797] jxcore: stopAdvertisingAndListening
2016-03-31 17:41:36.721 ThaliTest[2543:4714797] THEMultipeerManager stopping peer
2016-03-31 17:41:36.722 ThaliTest[2543:4714797] multipeer manager: stop client timer
2016-03-31 17:41:36.722 ThaliTest[2543:4714797] jxcore: stopAdvertisingAndListening: success
2016-03-31 17:41:36.722 ThaliTest[2543:4714797] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-31 17:41:36.723 ThaliTest[2543:4714797] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 108 error should be null
,ok 109 error should be null
,# setup
,# 29. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55788
2016-03-31 17:41:40.534 ThaliTest[2543:4714797] jxcore: stopAdvertisingAndListening
2016-03-31 17:41:40.534 ThaliTest[2543:4714797] THEMultipeerManager stopping peer
2016-03-31 17:41:40.534 ThaliTest[2543:4714797] jxcore: stopAdvertisingAndListening: success
,ok 110 error should be null
ok 111 error should be null
2016-03-31 17:41:40.536 ThaliTest[2543:4714797] jxcore: stopAdvertisingAndListening
2016-03-31 17:41:40.536 ThaliTest[2543:4714797] THEMultipeerManager stopping peer
2016-03-31 17:41:40.536 ThaliTest[2543:4714797] jxcore: stopAdvertisingAndListening: success
ok 112 error should be null
ok 113 error should be null
,# teardown
,2016-03-31 17:41:40.793 ThaliTest[2543:4714797] jxcore: stopAdvertisingAndListening
2016-03-31 17:41:40.793 ThaliTest[2543:4714797] THEMultipeerManager stopping peer
2016-03-31 17:41:40.793 ThaliTest[2543:4714797] jxcore: stopAdvertisingAndListening: success
2016-03-31 17:41:40.794 ThaliTest[2543:4714797] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 17:41:40.794 ThaliTest[2543:4714797] jxcore: stopListeningForAdvertisements: success
ok 114 error should be null
ok 115 error should be null
# setup
,# 30. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55790
ok 116 first call should succeed
ok 117 first call should succeed
ok 118 specific error should be returned
# teardown
,2016-03-31 17:41:42.964 ThaliTest[2543:4714797] jxcore: stopAdvertisingAndListening
2016-03-31 17:41:42.964 ThaliTest[2543:4714797] THEMultipeerManager stopping peer
2016-03-31 17:41:42.964 ThaliTest[2543:4714797] jxcore: stopAdvertisingAndListening: success
2016-03-31 17:41:42.964 ThaliTest[2543:4714797] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 17:41:42.964 ThaliTest[2543:4714797] jxcore: stopListeningForAdvertisements: success
ok 119 error should be null
ok 120 error should be null
# setup
,# 31. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55792
2016-03-31 17:41:56.263 ThaliTest[2543:4714797] jxcore: startListeningForAdvertisements
2016-03-31 17:41:56.263 ThaliTest[2543:4714797] multipeer manager: start client restart timer: 0x166daad0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 17:41:56.264 ThaliTest[2543:4714797] jxcore: startListeningForAdvertisements: success
,2016-03-31 17:41:56.269 ThaliTest[2543:4714797] jxcore: startUpdateAdvertisingAndListening
2016-03-31 17:41:56.269 ThaliTest[2543:4714797] server: starting B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:3
2016-03-31 17:41:56.269 ThaliTest[2543:4714797] THEMultipee,rManager initialized peer B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:3
2016-03-31 17:41:56.269 ThaliTest[2543:4714797] jxcore: startUpdateAdvertisingAndListening: success
ok 121 called only once
ok 122 discovery state matches
ok 123 advertising state matches
# teardown
,2016-03-31 17:41:56.473 ThaliTest[2543:4714797] jxcore: stopAdvertisingAndListening
2016-03-31 17:41:56.473 ThaliTest[2543:4714797] THEMultipeerManager stopping peer
2016-03-31 17:41:56.473 ThaliTest[2543:4714797] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-31 17:41:56.473 ThaliTest[2543:4714797] jxcore: stopListeningForAdvertisements
2016-03-31 17:41:56.473 ThaliTest[2543:4714797] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 17:41:56.474 ThaliTest[2543:4714797] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 124 error should be null
ok 125 error should be null
# setup
,# 32. does not send duplicate availability changes
,ok 126 should be called once
ok 127 should not have been called more than once
# teardown
,ok 128 error should be null
ok 129 error should be null
# setup
,# 33. can get the network status
,ok 130 network status should have certain non-empty properties
# teardown
,ok 131 error should be null
ok 132 error should be null
# setup
,# 34. wifi peer is marked unavailable if announcements stop
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
,ok 133 host address should match
ok 134 port should match
,ok 135 host address should be null
,ok 136 port should should be null
# teardown
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 137 error should be null
ok 138 error should be null
# setup
,# 35. Can call start/stopListeningForAdvertisements
,2016-03-31 17:42:39.398 ThaliTest[2543:4714797] jxcore: startListeningForAdvertisements
2016-03-31 17:42:39.398 ThaliTest[2543:4714797] multipeer manager: start client restart timer: 0x166daad0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 17:42:39.399 ThaliTest[2543:4714797] jxcore: startListeningForAdvertisements: success
ok 139 Can call startListeningForAdvertisements without error
2016-03-31 17:42:39.400 ThaliTest[2543:4714797] jxcore: stopListeningForAdvertisements
2016-03-31 17:42:39.400 ThaliTest[2543:4714797] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive,":false}
2016-03-31 17:42:39.400 ThaliTest[2543:4714797] jxcore: stopListeningForAdvertisements: success
ok 140 Can call stopListeningForAdvertisements without error
# teardown
,2016-03-31 17:42:39.758 ThaliTest[2543:4714797] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 17:42:39.758 ThaliTest[2543:4714797] jxcore: stopListeningForAdvertisements: success
ok 141 Should be able to call stopListeningForAdvertisments in teardown
2016-03-31 17:42:39.759 ThaliTest[2543:4714797] jxcore: stopAdvertisingAndListening
2016-03-31 17:42:39.759 ThaliTest[2543:471479,7] THEMultipeerManager stopping peer
2016-03-31 17:42:39.759 ThaliTest[2543:4714797] jxcore: stopAdvertisingAndListening: success
ok 142 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 36. Calling startListeningForAdvertisements twice is NOT an error
,2016-03-31 17:42:43.023 ThaliTest[2543:4714797] jxcore: startListeningForAdvertisements
2016-03-31 17:42:43.024 ThaliTest[2543:4714797] multipeer manager: start client restart timer: 0x166daad0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 17:42:43.024 ThaliTest[2543:4714797] jxcore: startListeningForAdvertisements: success
ok 143 Can call startListeningForAdvertisements without error
2016-03-31 17:42:43.025 ThaliTest[2543:4714797] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 17:42:43.025 ThaliTest[2543:4714797] jxcore: startListeningForAdvertisements: success
ok 144 Can call startListeningForAdvertisements twice without error
# teardown
,2016-03-31 17:42:47.502 ThaliTest[2543:4714797] jxcore: stopListeningForAdvertisements
2016-03-31 17:42:47.503 ThaliTest[2543:4714797] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 17:42:47.503 ThaliTest[2543:4714797] jxcore: stopListeningForAdvertisements: success
ok 145 Should be able to call stopListeningForAdvertisments in teardown
2016-03-31 17:42:47.504 ThaliTest[2543:47147,97] jxcore: stopAdvertisingAndListening
2016-03-31 17:42:47.504 ThaliTest[2543:4714797] THEMultipeerManager stopping peer
2016-03-31 17:42:47.504 ThaliTest[2543:4714797] jxcore: stopAdvertisingAndListening: success
ok 146 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 37. Can call start/stopUpdateAdvertisingAndListening
,2016-03-31 17:42:50.169 ThaliTest[2543:4714797] jxcore: startUpdateAdvertisingAndListening
2016-03-31 17:42:50.169 ThaliTest[2543:4714797] server: starting B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:4
2016-03-31 17:42:50.169 ThaliTest[2543:4714797] multipeer m,anager: start client restart timer: 0x166daad0
2016-03-31 17:42:50.170 ThaliTest[2543:4714797] THEMultipeerManager initialized peer B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:4
2016-03-31 17:42:50.170 ThaliTest[2543:4714797] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 147 Can call startUpdateAdvertisingAndListening without error
2016-03-31 17:42:50.170 ThaliTest[2543:4714797] jxcore: stopAdvertisingAndListening
2016-03-31 17:42:50.170 ThaliTest[2543:4714797] THEMultipeerManager stopping peer
,2016-03-31 17:42:50.170 ThaliTest[2543:4714797] multipeer manager: stop client timer
2016-03-31 17:42:50.174 ThaliTest[2543:4714797] jxcore: stopAdvertisingAndListening: success
ok 148 Can call stopAdvertisingAndListening without error
# teardown
,2016-03-31 17:42:53.230 ThaliTest[2543:4714797] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 17:42:53.231 ThaliTest[2543:47147,97] jxcore: stopListeningForAdvertisements: success
ok 149 Should be able to call stopListeningForAdvertisments in teardown
2016-03-31 17:42:53.231 ThaliTest[2543:4714797] jxcore: stopAdvertisingAndListening
2016-03-31 17:42:53.232 ThaliTest[2543:4714797] THEMultipeerManager stopping peer
2016-03-31 17:42:53.232 ThaliTest[2543:4714797] jxcore: stopAdvertisingAndListening: success
ok 150 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-03-31 17:42:57.858 ThaliTest[2543:4714797] jxcore: startUpdateAdvertisingAndListening
2016-03-31 17:42:57.858 ThaliTest[2543:4714797] server: starting B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:5
2016-03-31 17:42:57.858 ThaliTest[2543:4714797] multipeer manager: start client restart timer: 0x166daad0
2016-03-31 17:42:57.859 ThaliTest[2543:4714797] THEMultipeerManager initialized peer B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:5
2016-03-31 17:42:57.859 ThaliTest[2543:4714797] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 151 Can call startUpdateAdvertisingAndListening without error
2016-03-31 17:42:57.859 ThaliTest[2543:4714797] jxcore: startUpdateAdvertisingAndListening
2016-03-31 17:42:57.859 ThaliTest[2543:4714797] THEMultipeerManager stopping pee,r
,2016-03-31 17:42:57.859 ThaliTest[2543:4714797] multipeer manager: stop client timer
2016-03-31 17:42:57.863 ThaliTest[2543:4714797] server: starting B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:6
2016-03-31 17:42:57.863 ThaliTest[2543:4714797] multipeer manager,: start client restart timer: 0x166daad0
2016-03-31 17:42:57.863 ThaliTest[2543:4714797] THEMultipeerManager initialized peer B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:6
2016-03-31 17:42:57.863 ThaliTest[2543:4714797] jxcore: startUpdateAdvertisingAndListenin,g: success
ok 152 Can call startUpdateAdvertisingAndListening twice without error
# teardown
,2016-03-31 17:42:58.958 ThaliTest[2543:4714632] client: found new peer: 4F791D6C-3E6B-4315-830D-E0F106215081:6
2016-03-31 17:42:58.958 ThaliTest[2543:4714632] client: found new peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:2
,2016-03-31 17:43:01.225 ThaliTest[2543:4714797] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-31 17:43:01.225 ThaliTest[2543:471479,7] jxcore: stopListeningForAdvertisements: success
ok 153 Should be able to call stopListeningForAdvertisments in teardown
2016-03-31 17:43:01.226 ThaliTest[2543:4714797] jxcore: stopAdvertisingAndListening
2016-03-31 17:43:01.226 ThaliTest[2543:4714797,] THEMultipeerManager stopping peer
2016-03-31 17:43:01.226 ThaliTest[2543:4714797] multipeer manager: stop client timer
2016-03-31 17:43:01.226 ThaliTest[2543:4714797] jxcore: stopAdvertisingAndListening: success
ok 154 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 39. peerAvailabilityChange is called
,2016-03-31 17:43:16.885 ThaliTest[2543:4714797] jxcore: startUpdateAdvertisingAndListening
2016-03-31 17:43:16.885 ThaliTest[2543:4714797] server: starting B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:7
2016-03-31 17:43:16.885 ThaliTest[2543:4714797] multipeer m,anager: start client restart timer: 0x166daad0
2016-03-31 17:43:16.886 ThaliTest[2543:4714797] THEMultipeerManager initialized peer B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:7
2016-03-31 17:43:16.886 ThaliTest[2543:4714797] jxcore: startUpdateAdvertisingAndListening: success
ok 155 Can call startUpdateAdvertisingAndListeningwithout error
2016-03-31 17:43:16.886 ThaliTest[2543:4714797] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertising,Active":true,"discoveryActive":true}
2016-03-31 17:43:16.887 ThaliTest[2543:4714797] jxcore: startListeningForAdvertisements: success
ok 156 Can call startListeningForAdvertisements without error
,2016-03-31 17:43:17.813 ThaliTest[2543:4714632] client: found new peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:6
ok 157 peers must be an array
ok 158 peers must not be zero-length
ok 159 peer must have peerIdentifier
ok 160 peerIdentifier must be a string
ok 161 peer must have peerAvailable
ok 162 peer must have pleaseConnect
,# teardown
,2016-03-31 17:43:19.082 ThaliTest[2543:4714632] client: found new peer: 4F791D6C-3E6B-4315-830D-E0F106215081:7
,2016-03-31 17:43:20.452 ThaliTest[2543:4714632] client: found new peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
,2016-03-31 17:43:21.115 ThaliTest[2543:4714797] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-31 17:43:21.115 ThaliTest[2543:4714797] jxcore: stopListeningForAdvertisements: success
ok 163 Should be able to call stopListeningForAdvertisments in teardown
2016-03-31 17:43:21.116 ThaliTest[2543:4714797] jxcore: stopAdvertisingAndListening
2016-03-31 17:43:21.116 ThaliTest[2543:4714797,] THEMultipeerManager stopping peer
2016-03-31 17:43:21.116 ThaliTest[2543:4714797] multipeer manager: stop client timer
2016-03-31 17:43:21.116 ThaliTest[2543:4714797] jxcore: stopAdvertisingAndListening: success
ok 164 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 40. Can connect to a remote peer
,2016-03-31 17:43:21.766 ThaliTest[2543:4714797] jxcore: startUpdateAdvertisingAndListening
2016-03-31 17:43:21.767 ThaliTest[2543:4714797] server: starting B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:8
2016-03-31 17:43:21.767 ThaliTest[2543:4714797] multipeer manager: start client restart timer: 0x166daad0
2016-03-31 17:43:21.767 ThaliTest[2543:4714797] THEMultipeerManager initialized peer B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:8
2016-03-31 17:43:21.767 ThaliTest[2543:4714797] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 165 Can call startUpdateAdvertisingAndListening without error
2016-03-31 17:43:21.768 ThaliTest[2543:4714797] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisin,gActive":true,"discoveryActive":true}
2016-03-31 17:43:21.769 ThaliTest[2543:4714797] jxcore: startListeningForAdvertisements: success
ok 166 Can call startListeningForAdvertisements without error
,2016-03-31 17:43:22.510 ThaliTest[2543:4714632] client: found new peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7","pleaseConnect":0}]
2016-03-31 17:43:22.511 ThaliTest[2543:4714797] jxcore: connect 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
2016-03-31 17:43:22.511 ThaliTest[2543:4714797] client session: connect
2016-03-31 17:43:22.511 ThaliTest[2543:4714797] client session: stateChange:0->1 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
,2016-03-31 17:43:22.743 ThaliTest[2543:4714632] client: found new peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:7","pleaseConnect":0}]
,2016-03-31 17:43:22.810 ThaliTest[2543:4715347] client session: not connected 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
2016-03-31 17:43:22.810 ThaliTest[2543:4715347] client session: onLinkFailure: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:43:22.810 ThaliTest[2543:4715347] client session: disconnect
,2016-03-31 17:43:22.811 ThaliTest[2543:4715347] client session: stateChange:1->0 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
,2016-03-31 17:43:22.811 ThaliTest[2543:4715347] client session: fireConnectCallback: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:43:22.811 ThaliTest[2543:4715347] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-31 17:43:24.820 ThaliTest[2543:4714632] client: found new peer: 4F791D6C-3E6B-4315-830D-E0F106215081:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"4F791D6C-3E6B-4315-830D-E0F106215081:7","pleaseConnect":0}]
,2016-03-31 17:43:25.823 ThaliTest[2543:4714797] jxcore: connect 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
2016-03-31 17:43:25.823 ThaliTest[2543:4714797] client session: connect
2016-03-31 17:43:25.823 ThaliTest[2543:4714797] client session: stateChange:0->,1 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
,2016-03-31 17:43:26.224 ThaliTest[2543:4715347] client session: not connected 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
2016-03-31 17:43:26.224 ThaliTest[2543:4715347] client session: onLinkFailure: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:43:26.2,24 ThaliTest[2543:4715347] client session: disconnect
2016-03-31 17:43:26.224 ThaliTest[2543:4715347] client session: stateChange:1->0 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
2016-03-31 17:43:26.224 ThaliTest[2543:4715347] client session: fireConnectCallb,ack: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:43:26.224 ThaliTest[2543:4715347] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-31 17:43:29.225 ThaliTest[2543:4714797] jxcore: connect 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
2016-03-31 17:43:29.226 ThaliTest[2543:4714797] client session: connect
2016-03-31 17:43:29.226 ThaliTest[2543:4714797] client session: stateChange:0->1 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
,2016-03-31 17:43:29.342 ThaliTest[2543:4715347] client session: not connected 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
2016-03-31 17:43:29.343 ThaliTest[2543:4715347] client session: onLinkFailure: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:43:29.3,43 ThaliTest[2543:4715347] client session: disconnect
2016-03-31 17:43:29.343 ThaliTest[2543:4715347] client session: stateChange:1->0 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
2016-03-31 17:43:29.343 ThaliTest[2543:4715347] client session: fireConnectCallb,ack: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:43:29.343 ThaliTest[2543:4715347] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-31 17:43:32.348 ThaliTest[2543:4714797] jxcore: connect 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
2016-03-31 17:43:32.349 ThaliTest[2543:4714797] client session: connect
2016-03-31 17:43:32.349 ThaliTest[2543:4714797] client session: stateChange:0->,1 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
,2016-03-31 17:43:32.465 ThaliTest[2543:4715374] client session: not connected 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
2016-03-31 17:43:32.465 ThaliTest[2543:4715374] client session: onLinkFailure: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:43:32.465 ThaliTest[2543:4715374] client session: disconnect
2016-03-31 17:43:32.465 ThaliTest[2543:4715374] client session: stateChange:1->0 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
2016-03-31 17:43:32.465 ThaliTest[2543:4715374] client session: fireConnectCallb,ack: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:43:32.465 ThaliTest[2543:4715374] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 6
,2016-03-31 17:43:35.478 ThaliTest[2543:4714797] jxcore: connect 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
2016-03-31 17:43:35.478 ThaliTest[2543:4714797] client session: connect
2016-03-31 17:43:35.478 ThaliTest[2543:4714797] client session: stateChange:0->1 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
,2016-03-31 17:43:35.598 ThaliTest[2543:4715374] client session: not connected 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
2016-03-31 17:43:35.599 ThaliTest[2543:4715374] client session: onLinkFailure: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:43:35.599 ThaliTest[2543:4715374] client session: disconnect
2016-03-31 17:43:35.599 ThaliTest[2543:4715374] client session: stateChange:1->0 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
2016-03-31 17:43:35.599 ThaliTest[2543:4715374] client session: fireConnectCallb,ack: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:43:35.599 ThaliTest[2543:4715374] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-31 17:43:38.607 ThaliTest[2543:4714797] jxcore: connect 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
2016-03-31 17:43:38.608 ThaliTest[2543:4714797] client session: connect
2016-03-31 17:43:38.608 ThaliTest[2543:4714797] client session: stateChange:0->1 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
,2016-03-31 17:43:38.839 ThaliTest[2543:4715374] client session: not connected 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
2016-03-31 17:43:38.840 ThaliTest[2543:4715374] client session: onLinkFailure: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:43:38.8,40 ThaliTest[2543:4715374] client session: disconnect
2016-03-31 17:43:38.840 ThaliTest[2543:4715374] client session: stateChange:1->0 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
2016-03-31 17:43:38.840 ThaliTest[2543:4715374] client session: fireConnectCallback: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:43:38.840 ThaliTest[2543:4715374] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-31 17:43:41.768 ThaliTest[2543:4714632] multipeer manager: restart client
,2016-03-31 17:43:41.782 ThaliTest[2543:4714632] client: found updated peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:43:41.782 ThaliTest[2543:4714632] client: found updated peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
INFO testThaliMobileNati,ve: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8","pleaseConnect":0}]
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier,":"501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8","pleaseConnect":0}]
,2016-03-31 17:43:41.787 ThaliTest[2543:4714632] client: found updated peer: 4F791D6C-3E6B-4315-830D-E0F106215081:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"4F791D6C-3E6B-4315-830D-E0F106215081:8","pleaseConnect":0}]
,2016-03-31 17:43:41.849 ThaliTest[2543:4714797] jxcore: connect 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
2016-03-31 17:43:41.850 ThaliTest[2543:4714797] client session: connect
2016-03-31 17:43:41.850 ThaliTest[2543:4714797] client session: stateChange:0->1 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
,2016-03-31 17:43:41.943 ThaliTest[2543:4715374] client session: not connected 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:43:41.944 ThaliTest[2543:4715374] client session: onLinkFailure: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:43:41.945 ThaliTest[2543:4715374] client session: disconnect
2016-03-31 17:43:41.945 ThaliTest[2543:4715374] client session: stateChange:1->0 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:43:41.945 ThaliTest[2543:4715374] client session: fireConnectCallb,ack: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:43:41.945 ThaliTest[2543:4715374] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-31 17:43:44.948 ThaliTest[2543:4714797] jxcore: connect 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
2016-03-31 17:43:44.948 ThaliTest[2543:4714797] client session: connect
2016-03-31 17:43:44.948 ThaliTest[2543:4714797] client session: stateChange:0->,1 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
,2016-03-31 17:43:45.078 ThaliTest[2543:4715374] client session: not connected 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:43:45.078 ThaliTest[2543:4715374] client session: onLinkFailure: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:43:45.0,78 ThaliTest[2543:4715374] client session: disconnect
2016-03-31 17:43:45.078 ThaliTest[2543:4715374] client session: stateChange:1->0 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:43:45.078 ThaliTest[2543:4715374] client session: fireConnectCallb,ack: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:43:45.078 ThaliTest[2543:4715374] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 2
,2016-03-31 17:43:48.086 ThaliTest[2543:4714797] jxcore: connect 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
2016-03-31 17:43:48.086 ThaliTest[2543:4714797] client session: connect
2016-03-31 17:43:48.086 ThaliTest[2543:4714797] client session: stateChange:0->1 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
,2016-03-31 17:43:48.191 ThaliTest[2543:4715473] client session: not connected 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:43:48.191 ThaliTest[2543:4715473] client session: onLinkFailure: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:43:48.1,91 ThaliTest[2543:4715473] client session: disconnect
2016-03-31 17:43:48.192 ThaliTest[2543:4715473] client session: stateChange:1->0 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:43:48.192 ThaliTest[2543:4715473] client session: fireConnectCallback: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:43:48.192 ThaliTest[2543:4715473] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-31 17:43:51.200 ThaliTest[2543:4714797] jxcore: connect 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
2016-03-31 17:43:51.200 ThaliTest[2543:4714797] client session: connect
2016-03-31 17:43:51.200 ThaliTest[2543:4714797] client session: stateChange:0->1 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
,2016-03-31 17:43:51.358 ThaliTest[2543:4715473] client session: not connected 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:43:51.358 ThaliTest[2543:4715473] client session: onLinkFailure: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:43:51.3,58 ThaliTest[2543:4715473] client session: disconnect
2016-03-31 17:43:51.358 ThaliTest[2543:4715473] client session: stateChange:1->0 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:43:51.358 ThaliTest[2543:4715473] client session: fireConnectCallb,ack: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:43:51.359 ThaliTest[2543:4715473] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
WARN testThaliMobileNative: Too many connect retries!
,not ok 167 Connect failed!
  ---
,    operator: fail
,  ...
,# teardown
,2016-03-31 17:44:01.768 ThaliTest[2543:4714632] multipeer manager: restart client
,2016-03-31 17:44:01.789 ThaliTest[2543:4714632] client: found existing peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:44:01.789 ThaliTest[2543:4714632] client: found existing peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
2016-03-31 17:44:01.789 ThaliTest[2543:4714632] client: found existing peer: 4F791D6C-3E6B-4315-830D-E0F106215081:8
,2016-03-31 17:44:21.768 ThaliTest[2543:4714632] multipeer manager: restart client
,2016-03-31 17:44:21.783 ThaliTest[2543:4714632] client: found existing peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:44:21.784 ThaliTest[2543:4714632] client: found existing peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
,2016-03-31 17:44:21.786 ThaliTest[2543:4714632] client: found existing peer: 4F791D6C-3E6B-4315-830D-E0F106215081:8
,2016-03-31 17:44:41.757 ThaliTest[2543:4714632] multipeer manager: restart client
,2016-03-31 17:44:41.769 ThaliTest[2543:4714632] client: found existing peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:44:41.769 ThaliTest[2543:4714632] client: found existing peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
2016-03-31 17:44:41.770 ThaliTest[2543:4714632] client: found existing peer: 4F791D6C-3E6B-4315-830D-E0F106215081:8
,2016-03-31 17:45:01.724 ThaliTest[2543:4714632] multipeer manager: restart client
,2016-03-31 17:45:01.737 ThaliTest[2543:4714632] client: found existing peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:45:01.737 ThaliTest[2543:4714632] client: found existing peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
2016-03-31 17:45:01.738 ThaliTest[2543:4714632] client: found existing peer: 4F791D6C-3E6B-4315-830D-E0F106215081:8
,2016-03-31 17:45:21.724 ThaliTest[2543:4714632] multipeer manager: restart client
,2016-03-31 17:45:21.739 ThaliTest[2543:4714632] client: found existing peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:45:21.740 ThaliTest[2543:4714632] client: found existing peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
2016-03-31 17:45:21.740 ThaliTest[2543:4714632] client: found existing peer: 4F791D6C-3E6B-4315-830D-E0F106215081:8
,2016-03-31 17:45:31.031 ThaliTest[2543:4714797] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-31 17:45:31.032 ThaliTest[2543:4714797] jxcore: stopListeningForAdvertisements: success
ok 168 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-31 17:45:31.033 ThaliTest[2543:4714797] jxcore: stopAdvertisingAndListening
2016-03-31 17:45:31.033 ThaliTest[2543:4714797] THEMultipeerManager stopping peer
2016-03-31 17:45:31.033 ThaliTest[2543:4714797] multipeer manager: stop client timer
2016-03-31 17:45:31.034 ThaliTest[2543:4714797] jxcore: stopAdvertisingAndListening: success
ok 169 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 41. Can shift large amounts of data
,2016-03-31 17:45:34.410 ThaliTest[2543:4714797] jxcore: startUpdateAdvertisingAndListening
2016-03-31 17:45:34.411 ThaliTest[2543:4714797] server: starting B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:9
2016-03-31 17:45:34.411 ThaliTest[2543:4714797] multipeer manager: start client restart timer: 0x166daad0
2016-03-31 17:45:34.411 ThaliTest[2543:4714797] THEMultipeerManager initialized peer B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:9
2016-03-31 17:45:34.411 ThaliTest[2543:4714797] jxcore: startUpdateAdvertisingAndListening: success
ok 170 Can call startUpdateAdvertisingAndListening without error
,2016-03-31 17:45:34.412 ThaliTest[2543:4714797] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-31 17:45:34.413 ThaliTest[2543:4714797] jxcore: startListeningForAdvertisements: success
,ok 171 Can call startListeningForAdvertisements without error
,2016-03-31 17:45:35.186 ThaliTest[2543:4714632] client: found new peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:45:35.186 ThaliTest[2543:4714797] jxcore: connect 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:45:35.186 ThaliTest[2543:4714797] client session: connect
2016-03-31 17:45:35.187 ThaliTest[2543:4714797] client session: stateChange:0->1 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
,2016-03-31 17:45:35.704 ThaliTest[2543:4714632] client: found new peer: 4F791D6C-3E6B-4315-830D-E0F106215081:8
,2016-03-31 17:45:35.830 ThaliTest[2543:4715809] client session: not connected 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:45:35.831 ThaliTest[2543:4715809] client session: onLinkFailure: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:45:35.8,31 ThaliTest[2543:4715809] client session: disconnect
2016-03-31 17:45:35.831 ThaliTest[2543:4715809] client session: stateChange:1->0 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:45:35.832 ThaliTest[2543:4715809] client session: fireConnectCallback: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:45:35.832 ThaliTest[2543:4715809] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-31 17:45:36.623 ThaliTest[2543:4714632] multipeer session: reset timer
2016-03-31 17:45:36.623 ThaliTest[2543:4714632] server: rejecting invitation from 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB due to previous generation (B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:9 != B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:8)
,2016-03-31 17:45:37.696 ThaliTest[2543:4714632] client: found new peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
,2016-03-31 17:45:38.844 ThaliTest[2543:4714797] jxcore: connect 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:45:38.845 ThaliTest[2543:4714797] client session: connect
2016-03-31 17:45:38.845 ThaliTest[2543:4714797] client session: stateChange:0->1 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
,2016-03-31 17:45:38.904 ThaliTest[2543:4715628] client session: not connected 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:45:38.905 ThaliTest[2543:4715628] client session: onLinkFailure: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:45:38.905 ThaliTest[2543:4715628] client session: disconnect
2016-03-31 17:45:38.905 ThaliTest[2543:4715628] client session: stateChange:1->0 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:45:38.906 ThaliTest[2543:4715628] client session: fireConnectCallb,ack: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:45:38.906 ThaliTest[2543:4715628] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-31 17:45:41.911 ThaliTest[2543:4714797] jxcore: connect 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:45:41.911 ThaliTest[2543:4714797] client session: connect
2016-03-31 17:45:41.911 ThaliTest[2543:4714797] client session: stateChange:0->1 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
,2016-03-31 17:45:41.944 ThaliTest[2543:4715628] client session: not connected 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:45:41.945 ThaliTest[2543:4715628] client session: onLinkFailure: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:45:41.9,45 ThaliTest[2543:4715628] client session: disconnect
2016-03-31 17:45:41.945 ThaliTest[2543:4715628] client session: stateChange:1->0 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:45:41.946 ThaliTest[2543:4715628] client session: fireConnectCallback: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:45:41.946 ThaliTest[2543:4715628] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 7
,2016-03-31 17:45:44.953 ThaliTest[2543:4714797] jxcore: connect 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:45:44.953 ThaliTest[2543:4714797] client session: connect
2016-03-31 17:45:44.953 ThaliTest[2543:4714797] client session: stateChange:0->1 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
,2016-03-31 17:45:45.023 ThaliTest[2543:4715810] client session: not connected 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:45:45.023 ThaliTest[2543:4715810] client session: onLinkFailure: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:45:45.024 ThaliTest[2543:4715810] client session: disconnect
2016-03-31 17:45:45.024 ThaliTest[2543:4715810] client session: stateChange:1->0 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
,2016-03-31 17:45:45.026 ThaliTest[2543:4715810] client session: fireConnectCallback: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:45:45.027 ThaliTest[2543:4715810] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returne,d an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-31 17:45:48.036 ThaliTest[2543:4714797] jxcore: connect 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:45:48.036 ThaliTest[2543:4714797] client session: connect
2016-03-31 17:45:48.036 ThaliTest[2543:4714797] client session: stateChange:0->1 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
,2016-03-31 17:45:48.169 ThaliTest[2543:4714632] multipeer session: reset timer
2016-03-31 17:45:48.169 ThaliTest[2543:4714632] server: disconnecting to refresh session (2646853F-7FBE-4B67-A117-C1DAA2A4C3FB)
2016-03-31 17:45:48.169 ThaliTest[2543:4714632] server: rejecting invitation from 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB due to previous generation (B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:9 != B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:8)
,2016-03-31 17:45:48.188 ThaliTest[2543:4715628] client session: not connected 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:45:48.188 ThaliTest[2543:4715628] client session: onLinkFailure: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:45:48.188 ThaliTest[2543:4715628] client session: disconnect
2016-03-31 17:45:48.188 ThaliTest[2543:4715628] client session: stateChange:1->0 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:45:48.189 ThaliTest[2543:4715628] client session: fireConnectCallb,ack: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:45:48.189 ThaliTest[2543:4715628] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-31 17:45:51.195 ThaliTest[2543:4714797] jxcore: connect 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:45:51.196 ThaliTest[2543:4714797] client session: connect
2016-03-31 17:45:51.196 ThaliTest[2543:4714797] client session: stateChange:0->1 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
,2016-03-31 17:45:51.310 ThaliTest[2543:4715831] client session: not connected 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:45:51.311 ThaliTest[2543:4715831] client session: onLinkFailure: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:45:51.311 ThaliTest[2543:4715831] client session: disconnect
2016-03-31 17:45:51.311 ThaliTest[2543:4715831] client session: stateChange:1->0 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:45:51.312 ThaliTest[2543:4715831] client session: fireConnectCallb,ack: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:45:51.312 ThaliTest[2543:4715831] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-31 17:45:54.316 ThaliTest[2543:4714797] jxcore: connect 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:45:54.316 ThaliTest[2543:4714797] client session: connect
2016-03-31 17:45:54.316 ThaliTest[2543:4714797] client session: stateChange:0->1 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
,2016-03-31 17:45:54.412 ThaliTest[2543:4714632] multipeer manager: restart client
,2016-03-31 17:45:54.424 ThaliTest[2543:4714632] client: found updated peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
2016-03-31 17:45:54.425 ThaliTest[2543:4714632] client: found updated peer: 4F791D6C-3E6B-4315-830D-E0F106215081:9
2016-03-31 17:45:54.425 ThaliTest[2543:4714632] client: found existing peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
,2016-03-31 17:46:00.858 ThaliTest[2543:4714632] multipeer session: reset timer
2016-03-31 17:46:00.858 ThaliTest[2543:4714632] server: disconnecting to refresh session (2646853F-7FBE-4B67-A117-C1DAA2A4C3FB)
2016-03-31 17:46:00.858 ThaliTest[2543:4714632] server: rejecting invitation from 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB due to previous generation (B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:9 != B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:8)
,2016-03-31 17:46:14.412 ThaliTest[2543:4714632] multipeer manager: restart client
,2016-03-31 17:46:14.423 ThaliTest[2543:4714632] client: found existing peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
2016-03-31 17:46:14.423 ThaliTest[2543:4714632] client: found existing peer: 4F791D6C-3E6B-4315-830D-E0F106215081:9
2016-03-31 17:46:14.424 ThaliTest[2543:4714632] client: found existing peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
,2016-03-31 17:46:27.286 ThaliTest[2543:4715949] client session: not connected 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
2016-03-31 17:46:27.286 ThaliTest[2543:4715949] client session: onLinkFailure: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:46:27.286 ThaliTest[2543:4715949] client session: disconnect
2016-03-31 17:46:27.286 ThaliTest[2543:4715949] client session: stateChange:1->0 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
2016-03-31 17:46:27.287 ThaliTest[2543:4715949] client session: fireConnectCallb,ack: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:46:27.287 ThaliTest[2543:4715949] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-31 17:46:29.469 ThaliTest[2543:4714632] client: lost peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA
2016-03-31 17:46:29.469 ThaliTest[2543:4714632] client session: onPeerLost: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA
,2016-03-31 17:46:30.291 ThaliTest[2543:4714797] jxcore: connect 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:46:30.291 ThaliTest[2543:4714797] client session: connect
2016-03-31 17:46:30.291 ThaliTest[2543:4714797] client session: stateChange:0->1 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
,2016-03-31 17:46:30.748 ThaliTest[2543:4715949] client session: not connected 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
,2016-03-31 17:46:30.749 ThaliTest[2543:4715949] client session: onLinkFailure: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:46:30.750 ThaliTest[2543:4715949] client session: disconnect
,2016-03-31 17:46:30.750 ThaliTest[2543:4715949] client session: stateChange:1->0 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
2016-03-31 17:46:30.750 ThaliTest[2543:4715949] client session: fireConnectCallback: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:46:30.750 ThaliTest[2543:4715949] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-31 17:46:33.752 ThaliTest[2543:4714797] jxcore: connect 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:46:33.753 ThaliTest[2543:4714797] client session: connect
2016-03-31 17:46:33.753 ThaliTest[2543:4714797] client session: stateChange:0->,1 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
,2016-03-31 17:46:33.821 ThaliTest[2543:4715858] client session: not connected 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
2016-03-31 17:46:33.822 ThaliTest[2543:4715858] client session: onLinkFailure: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:46:33.8,23 ThaliTest[2543:4715858] client session: disconnect
2016-03-31 17:46:33.823 ThaliTest[2543:4715858] client session: stateChange:1->0 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
2016-03-31 17:46:33.823 ThaliTest[2543:4715858] client session: fireConnectCallback: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:46:33.823 ThaliTest[2543:4715858] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-31 17:46:34.411 ThaliTest[2543:4714632] multipeer manager: restart client
,2016-03-31 17:46:34.421 ThaliTest[2543:4714632] client: found existing peer: 4F791D6C-3E6B-4315-830D-E0F106215081:9
2016-03-31 17:46:34.422 ThaliTest[2543:4714632] client: found existing peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
,2016-03-31 17:46:34.423 ThaliTest[2543:4714632] client: found existing peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
,2016-03-31 17:46:36.830 ThaliTest[2543:4714797] jxcore: connect 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:46:36.830 ThaliTest[2543:4714797] client session: connect
2016-03-31 17:46:36.830 ThaliTest[2543:4714797] client session: stateChange:0->1 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
,2016-03-31 17:46:36.931 ThaliTest[2543:4715951] client session: not connected 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
2016-03-31 17:46:36.932 ThaliTest[2543:4715951] client session: onLinkFailure: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:46:36.932 ThaliTest[2543:4715951] client session: disconnect
2016-03-31 17:46:36.932 ThaliTest[2543:4715951] client session: stateChange:1->0 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
,2016-03-31 17:46:36.932 ThaliTest[2543:4715951] client session: fireConnectCallback: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:46:36.933 ThaliTest[2543:4715951] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
WARN testThaliMobileNative: Too many connect retries!
,not ok 172 Connect failed!
  ---
,    operator: fail
  ...
,# teardown
,2016-03-31 17:46:54.412 ThaliTest[2543:4714632] multipeer manager: restart client
,2016-03-31 17:46:54.424 ThaliTest[2543:4714632] client: found existing peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
2016-03-31 17:46:54.424 ThaliTest[2543:4714632] client: found existing peer: 4F791D6C-3E6B-4315-830D-E0F106215081:9
2016-03-31 17:46:54.424 ThaliTest[2543:4714632] client: found existing peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
,2016-03-31 17:47:14.412 ThaliTest[2543:4714632] multipeer manager: restart client
,2016-03-31 17:47:14.426 ThaliTest[2543:4714632] client: found existing peer: 4F791D6C-3E6B-4315-830D-E0F106215081:9
2016-03-31 17:47:14.426 ThaliTest[2543:4714632] client: found existing peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
,2016-03-31 17:47:14.432 ThaliTest[2543:4714632] client: found existing peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
,2016-03-31 17:47:34.412 ThaliTest[2543:4714632] multipeer manager: restart client
,2016-03-31 17:47:34.424 ThaliTest[2543:4714632] client: found existing peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
2016-03-31 17:47:34.424 ThaliTest[2543:4714632] client: found existing peer: 4F791D6C-3E6B-4315-830D-E0F106215081:9
,2016-03-31 17:47:34.428 ThaliTest[2543:4714632] client: found existing peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
,2016-03-31 17:47:54.412 ThaliTest[2543:4714632] multipeer manager: restart client
,2016-03-31 17:47:54.422 ThaliTest[2543:4714632] client: found existing peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
,2016-03-31 17:47:54.425 ThaliTest[2543:4714632] client: found existing peer: 4F791D6C-3E6B-4315-830D-E0F106215081:9
2016-03-31 17:47:54.426 ThaliTest[2543:4714632] client: found existing peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
,2016-03-31 17:48:14.412 ThaliTest[2543:4714632] multipeer manager: restart client
,2016-03-31 17:48:14.424 ThaliTest[2543:4714632] client: found existing peer: 4F791D6C-3E6B-4315-830D-E0F106215081:9
2016-03-31 17:48:14.424 ThaliTest[2543:4714632] client: found existing peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
2016-03-31 17:48:14.424 ThaliTest[2543:4714632] client: found existing peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
,2016-03-31 17:48:34.412 ThaliTest[2543:4714632] multipeer manager: restart client
,2016-03-31 17:48:34.423 ThaliTest[2543:4714632] client: found existing peer: 4F791D6C-3E6B-4315-830D-E0F106215081:9
2016-03-31 17:48:34.423 ThaliTest[2543:4714632] client: found existing peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
,2016-03-31 17:48:34.425 ThaliTest[2543:4714632] client: found existing peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
,2016-03-31 17:48:54.412 ThaliTest[2543:4714632] multipeer manager: restart client
,2016-03-31 17:48:54.423 ThaliTest[2543:4714632] client: found existing peer: 4F791D6C-3E6B-4315-830D-E0F106215081:9
2016-03-31 17:48:54.423 ThaliTest[2543:4714632] client: found existing peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
,2016-03-31 17:48:54.425 ThaliTest[2543:4714632] client: found updated peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:9
,2016-03-31 17:49:14.412 ThaliTest[2543:4714632] multipeer manager: restart client
,2016-03-31 17:49:34.411 ThaliTest[2543:4714632] multipeer manager: restart client
,2016-03-31 17:49:34.420 ThaliTest[2543:4714632] client: found updated peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
2016-03-31 17:49:34.420 ThaliTest[2543:4714632] client: found existing peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
2016-03-31 17:49:34.420 ThaliTest[2543:4714632] client: found existing peer: 4F791D6C-3E6B-4315-830D-E0F106215081:9
,2016-03-31 17:49:54.412 ThaliTest[2543:4714632] multipeer manager: restart client
,2016-03-31 17:49:54.422 ThaliTest[2543:4714632] client: found existing peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
2016-03-31 17:49:54.422 ThaliTest[2543:4714632] client: found existing peer: 4F791D6C-3E6B-4315-830D-E0F106215081:9
2016-03-31 17:49:54.422 ThaliTest[2543:4714632] client: found existing peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
,2016-03-31 17:50:00.478 ThaliTest[2543:4714797] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-31 17:50:00.479 ThaliTest[2543:4714797] jxcore: stopListeningForAdvertisements: success
,ok 173 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-31 17:50:00.480 ThaliTest[2543:4714797] jxcore: stopAdvertisingAndListening
2016-03-31 17:50:00.480 ThaliTest[2543:4714797] THEMultipeerManager stopping peer
2016-03-31 17:50:00.480 ThaliTest[2543:4714797] multipeer manager: stop client timer
2016-03-31 17:50:00.480 ThaliTest[2543:4714797] jxcore: stopAdvertisingAndListening: success
ok 174 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2016-03-31 17:50:11.798 ThaliTest[2543:4714797] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-31 17:50:11.798 ThaliTest[2543:4714797] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-31 17:50:11.798 ThaliTest[2543:4,714797] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-31 17:50:11.799 ThaliTest[2543:4714797] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 42. #startListeningForAdvertisements should fail if start not called
,ok 175 specific error should be returned
,# teardown
,ok 176 must be stopped
,# setup
,2016-03-31 17:50:23.655 ThaliTest[2543:4714797] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-31 17:50:23.656 ThaliTest[2543:4714797] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-31 17:50:23.656 ThaliTest[2543:4714797] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-31 17:50:23.657 ThaliTest[2543:4714797] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 43. #startUpdateAdvertisingAndListening should fail if start not called
,ok 177 specific error should be returned
,# teardown
,ok 178 must be stopped
,# setup
,2016-03-31 17:50:25.181 ThaliTest[2543:4714797] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-31 17:50:25.181 ThaliTest[2543:4714797] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-31 17:50:25.181 ThaliTest[2543:4,714797] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-31 17:50:25.182 ThaliTest[2543:4714797] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 44. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 55830
,2016-03-31 17:50:25.688 ThaliTest[2543:4714797] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 17:50:25.689 ThaliTest[2543:4714797] jxcore: stopListeningForAdvertisements: success
,ok 179 no errors
,2016-03-31 17:50:25.691 ThaliTest[2543:4714797] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-31 17:50:25.691 ThaliTest[2543:4714797] jxcore: stopListeningForAdvertisements: success
,ok 180 still no errors
,# teardown
,2016-03-31 17:50:30.487 ThaliTest[2543:4714797] jxcore: stopAdvertisingAndListening
2016-03-31 17:50:30.488 ThaliTest[2543:4714797] THEMultipeerManager stopping peer
2016-03-31 17:50:30.488 ThaliTest[2543:4714797] jxcore: stopAdvertisingAndListening: success
2016-03-31 17:50:30.488 ThaliTest[2543:4714797] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 17:50:30.489 ThaliTest[2543:4714797] jxcore: stopListeningForAdvertisements: success
,ok 181 must be stopped
,# setup
,2016-03-31 17:50:56.569 ThaliTest[2543:4714797] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-31 17:50:56.569 ThaliTest[2543:4714797] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-31 17:50:56.569 ThaliTest[2543:4714797] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-31 17:50:56.571 ThaliTest[2543:4714797] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 45. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 55832
,2016-03-31 17:50:56.714 ThaliTest[2543:4714797] jxcore: startListeningForAdvertisements
2016-03-31 17:50:56.715 ThaliTest[2543:4714797] multipeer manager: start client restart timer: 0x166daad0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 17:50:56.716 ThaliTest[2543:4714797] jxcore: startListeningForAdvertisements: success
ok 182 no errors
,2016-03-31 17:50:56.717 ThaliTest[2543:4714797] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-31 17:50:56.718 ThaliTest[2543:4714797] jxcore: startListeningForAdvertisements: success
,ok 183 still no errors
# teardown
,2016-03-31 17:50:56.722 ThaliTest[2543:4714632] client: found new peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
2016-03-31 17:50:56.723 ThaliTest[2543:4714632] client: found new peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
,DEBUG createPeerListener: createPeerListener
,DEBUG createPeerListener: pleaseConnect= 0
,DEBUG createPeerListener: createPeerListener
,DEBUG createPeerListener: pleaseConnect= 0
,2016-03-31 17:50:57.103 ThaliTest[2543:4714632] client: lost peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA
,2016-03-31 17:50:57.104 ThaliTest[2543:4714632] client session: onPeerLost: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA
,2016-03-31 17:51:03.257 ThaliTest[2543:4714797] jxcore: stopAdvertisingAndListening
2016-03-31 17:51:03.257 ThaliTest[2543:4714797] THEMultipeerManager stopping peer
2016-03-31 17:51:03.257 ThaliTest[2543:4714797] jxcore: stopAdvertisingAndListening: success
2016-03-31 17:51:03.257 ThaliTest[2543:4714797] jxcore: stopListeningForAdvertisements
2016-03-31 17:51:03.258 ThaliTest[2543:4714797] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-31 17:51:03.258 ThaliTest[2543:4714797] jxcore: stopListeningForAdvertisements: success
ok 184 must be stopped
# setup
,2016-03-31 17:51:16.102 ThaliTest[2543:4714797] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-31 17:51:16.102 ThaliTest[2543:4714797] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-31 17:51:16.102 ThaliTest[2543:4714797] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-31 17:51:16.103 ThaliTest[2543:4714797] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
# 46. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 55836
,2016-03-31 17:51:29.249 ThaliTest[2543:4714797] jxcore: startUpdateAdvertisingAndListening
2016-03-31 17:51:29.250 ThaliTest[2543:4714797] server: starting B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:10
2016-03-31 17:51:29.250 ThaliTest[2543:4714797] multipeer manager: start client restart timer: 0x166daad0
2016-03-31 17:51:29.250 ThaliTest[2543:4714797] THEMultipeerManager initialized peer B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:10
,2016-03-31 17:51:29.252 ThaliTest[2543:4714797] jxcore: startUpdateAdvertisingAndListening: success
ok 185 no errors
2016-03-31 17:51:29.253 ThaliTest[2543:4714797] jxcore: startUpdateAdvertisingAndListening
2016-03-31 17:51:29.253 ThaliTest[2543:471479,7] THEMultipeerManager stopping peer
2016-03-31 17:51:29.253 ThaliTest[2543:4714797] multipeer manager: stop client timer
2016-03-31 17:51:29.253 ThaliTest[2543:4714797] server: starting B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:11
,2016-03-31 17:51:29.254 ThaliTest[2543:4714797] multipeer manager: start client restart timer: 0x166daad0
2016-03-31 17:51:29.254 ThaliTest[2543:4714797] THEMultipeerManager initialized peer B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:11
,2016-03-31 17:51:29.254 ThaliTest[2543:4714797] jxcore: startUpdateAdvertisingAndListening: success
ok 186 still no errors
# teardown
,* thread #1: tid = 0x47f088, 0x21dd4f96 CoreFoundation`CFArrayAppendValue + 30, queue = 'com.apple.main-thread', stop reason = EXC_BAD_ACCESS (code=1, address=0x0)
  * frame #0: 0x21dd4f96 CoreFoundation`CFArrayAppendValue + 30
    frame #1: 0x2170fd62 CFNetwork`<redacted> + 526
    frame #2: 0x340dcbcc libsystem_dnssd.dylib`<redacted> + 128
    frame #3: 0x340db490 libsystem_dnssd.dylib`DNSServiceProcessResult + 528
    frame #4: 0x2170f798 CFNetwork`<redacted> + 20
    frame #5: 0x21e8b4f6 CoreFoundation`<redacted> + 818
    frame #6: 0x21e877c6 CoreFoundation`<redacted> + 14
    frame #7: 0x21e87348 CoreFoundation`<redacted> + 344
    frame #8: 0x21e8571e CoreFoundation`<redacted> + 806
    frame #9: 0x21dd80d8 CoreFoundation`CFRunLoopRunSpecific + 516
    frame #10: 0x21dd7ecc CoreFoundation`CFRunLoopRunInMode + 108
    frame #11: 0x2b10daf8 GraphicsServices`GSEventRunModal + 160
    frame #12: 0x260612dc UIKit`UIApplicationMain + 144
    frame #13: 0x000e1282 ThaliTest`main + 50

```
