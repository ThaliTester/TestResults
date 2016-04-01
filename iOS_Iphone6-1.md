#### Test 6480993629f6128_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/6480993629f6128/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/1FDEE080-D8A5-4838-87CD-AD1975629BEE/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/1FDEE080-D8A5-4838-87CD-AD1975629BEE/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/6480993629f6128/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/6480993629f6128/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/95BEB29B-D9D6-426D-AA4E-2BE3A7CCB735/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50397"
,(lldb)     command script import "/tmp/1FDEE080-D8A5-4838-87CD-AD1975629BEE/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-04-01 23:47:07.324 ThaliTest[2652:4910376] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4CEADDE3-7F63-4884-A9C5-150F0E9123C3/Library/Cookies/Cookies.binarycookies
,2016-04-01 23:47:07.551 ThaliTest[2652:4910376] Apache Cordova native platform version 4.1.0 is starting.
2016-04-01 23:47:07.552 ThaliTest[2652:4910376] Multi-tasking -> Device: YES, App: YES
,2016-04-01 23:47:07.568 ThaliTest[2652:4910376] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-04-01 23:47:08.353 ThaliTest[2652:4910376] Using UIWebView
,2016-04-01 23:47:08.356 ThaliTest[2652:4910376] [CDVTimer][handleopenurl] 0.147045ms
2016-04-01 23:47:08.359 ThaliTest[2652:4910376] [CDVTimer][intentandnavigationfilter] 2.443969ms
2016-04-01 23:47:08.359 ThaliTest[2652:4910376] [CDVTimer][gesturehandler] 0.102997ms
2016-04-01 23:47:08.359 ThaliTest[2652:4910376] [CDVTimer][TotalPluginStartup] 3.626049ms
,2016-04-01 23:47:11.479 ThaliTest[2652:4910376] Resetting plugins due to page load.
,2016-04-01 23:47:12.707 ThaliTest[2652:4910376] Finished load of: file:///var/mobile/Containers/Bundle/Application/95BEB29B-D9D6-426D-AA4E-2BE3A7CCB735/ThaliTest.app/www/index.html
,2016-04-01 23:47:12.864 ThaliTest[2652:4910376] JXcore Cordova plugin initializing
,2016-04-01 23:47:12.947 ThaliTest[2652:4910532] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-04-01 23:47:19.853 ThaliTest[2652:4910532] jxcore: didRegisterToNative peerAvailabilityChanged
2016-04-01 23:47:19.853 ThaliTest[2652:4910532] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-04-01 23:47:19.853 ThaliTest[2652:4910532] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-04-01 23:47:19.855 ThaliTest[2652:4910532] jxcore: didRegisterToNativ,e incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone6-1
WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/95BEB29B-D9D6-426D-AA4E-2BE3A7CCB735/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/95BEB29B-D9D6-426D-AA4E-2BE3A7CCB735/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/95BEB29B-D9D6-426D-AA4E-2BE3A7CCB735/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/95BEB29B-D9D6-426D-AA4E-2BE3A7CCB735/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/95BEB29B-D9D6-426D-AA4E-2BE3A7CCB735/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/95BEB29B-D9D6-426D-AA4E-2BE3A7CCB735/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/95BEB29B-D9D6-426D-AA4E-2BE3A7CCB735/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/95BEB29B-D9D6-426D-AA4E-2BE3A7CCB735/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/95BEB29B-D9D6-426D-AA4E-2BE3A7CCB735/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/95BEB29B-D9D6-426D-AA4E-2BE3A7CCB735/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/95BEB29B-D9D6-426D-AA4E-2BE3A7CCB735/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/95BEB29B-D9D6-426D-AA4E-2BE3A7CCB735/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/95BEB29B-D9D6-426D-AA4E-2BE3A7CCB735/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/95BEB29B-D9D6-426D-AA4E-2BE3A7CCB735/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/95BEB29B-D9D6-426D-AA4E-2BE3A7CCB735/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/95BEB29B-D9D6-426D-AA4E-2BE3A7CCB735/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/95BEB29B-D9D6-426D-AA4E-2BE3A7CCB735/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/95BEB29B-D9D6-426D-AA4E-2BE3A7CCB735/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/95BEB29B-D9D6-426D-AA4E-2BE3A7CCB735/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/95BEB29B-D9D6-426D-AA4E-2BE3A7CCB735/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/95BEB29B-D9D6-426D-AA4E-2BE3A7CCB735/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/95BEB29B-D9D6-426D-AA4E-2BE3A7CCB735/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 56933
ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 56935
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 2 initial connection state should be CONNECTED
,DEBUG createNativeListener: incoming socket close
ok 3 final connection state should be DISCONNECTED
,# teardown
,# setup
,# 3. emits routerPortConnectionFailed
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 56938
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: 
ok 4 tried to connect to right port
ok 5 failed due to refused connection
ok 6 routerPortConnectionFailed is emitted
# teardown
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
# setup
DEBUG createNativeListener: incoming socket close
,# 4. native server connections all up
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 56942
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
,ok 11 Should be exactly 2 client sockets
,# teardown
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
# setup
DEBUG createNativeListener: incoming socket close
,# 5. native server - closing incoming stream cleans outgoing socket
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 56947
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
DEBUG createNativeListener: listening 56951
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
DEBUG createNativeListener: listening 56955
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: listening 56959
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 20 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,ok 21 Buffers are identical
DEBUG createNativeListener: stream close:
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
DEBUG createNativeListener: listening 56963
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
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createN,ativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new ,mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new ,outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNat,iveListener: new outgoing socket
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
DEBUG createNativeListene,r: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG cr,eateNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
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
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
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
DEBUG createNativeListener: mux close
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
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBU,G createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,ok 28 native server is nulled out
ok 29 native server should be closed
ok 30 incoming has been removed
,DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
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
,DEBUG createNativeListener: listening 57015
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
DEBUG createNativeListener: listening 57019
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
ok 40 server should be fine
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
# teardown
,# setup
,# 17. enqueueAtTop and run backwards
,ok 57 thirdPromise - first to run
ok 58 thirdPromise - in resolve
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
ok 69 firstPromise - in catch
ok 70 third
ok 71 thirdPromise - in then
ok 72 testingPromises
# teardown
,# setup
,# 19. queues handled independently
,ok 73 all short operations completed before the long resolves
,# teardown
,# setup
,# 20. basic
,ok 74 sane
# teardown
,# setup
,# 21. another
,ok 75 sane
# teardown
,# setup
,# 22. can pass data in setup
,[{"uuid":"8f481545-2d3c-4c34-90c0-6602bf93a785","data":"custom data"},{"uuid":"7299c1cd-4325-4a34-90c1-c1db833eeee1","data":"custom data"},{"uuid":"c7e38397-c90d-4e48-845d-977d1574ba6e","data":"custom data"},{"uuid":"3559cc27-6402-432b-bcfd-c285802596a6",",data":"custom data"}]
ok 76 test participant has uuid
ok 77 participant data matches
ok 78 test participant has uuid
ok 79 participant data matches
ok 80 test participant has uuid
ok 81 participant data matches
ok 82 test participant has uuid
ok 83 participant data matches
ok 84 own UUID is found from the participants list
# teardown
,# setup
,# 23. #startListeningForAdvertisements should fail if start not called
,ok 85 specific error should be returned
# teardown
,ok 86 error should be null
ok 87 error should be null
# setup
,# 24. #startUpdateAdvertisingAndListening should fail if start not called
,ok 88 specific error should be returned
# teardown
,ok 89 error should be null
ok 90 error should be null
# setup
,# 25. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 57029
2016-04-01 23:50:18.160 ThaliTest[2652:4910532] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 23:50:18.160 ThaliTest[2652:4910532] jxcore: stopListeningForAdvertisements: success
ok 91 error should be null
ok 92 error should be null
2016-04-01 23:50:18.162 ThaliTest[2652:4910532] jx,core: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 23:50:18.162 ThaliTest[2652:4910532] jxcore: stopListeningForAdvertisements: success
ok 93 error should be null
ok 94 error should be null
# teardown
,2016-04-01 23:50:18.327 ThaliTest[2652:4910532] jxcore: stopAdvertisingAndListening
2016-04-01 23:50:18.327 ThaliTest[2652:4910532] THEMultipeerManager stopping peer
2016-04-01 23:50:18.327 ThaliTest[2652:4910532] jxcore: stopAdvertisingAndListening: success
2016-04-01 23:50:18.328 ThaliTest[2652:4910532] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 23:50:18.328 ThaliTest[2652:4910532] jxcore: stopListeningForAdvertisements: success
ok 95 error should be null
ok 96 error should be null
# setup
,# 26. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 57031
2016-04-01 23:50:18.572 ThaliTest[2652:4910532] jxcore: startListeningForAdvertisements
,2016-04-01 23:50:18.574 ThaliTest[2652:4910532] multipeer manager: start client restart timer: 0x1455d050
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-01 23:50:18.574 ThaliTest[2652:4910532] jxcore: startListeningForAdvertisements: success
,ok 97 error should be null
ok 98 error should be null
2016-04-01 23:50:18.581 ThaliTest[2652:4910532] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-01 23:50:18.582 ThaliTest[2652:4910532] jxcore: startListeningForAdvertisements: success
ok 99 error should be null
ok 100 error should be null
# teardown
,2016-04-01 23:50:19.355 ThaliTest[2652:4910532] jxcore: stopAdvertisingAndListening
2016-04-01 23:50:19.355 ThaliTest[2652:4910532] THEMultipeerManager stopping peer
2016-04-01 23:50:19.355 ThaliTest[2652:4910532] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-01 23:50:19.355 ThaliTest[2652:4910532] jxcore: stopListeningForAdvertisements
2016-04-01 23:50:19.355 ThaliTest[2652:4910532] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 23:50:19.356 ThaliTest[2652:4910532] jxcore: stopListeningForAdvertisements: success
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 101 error should be ,null
ok 102 error should be null
# setup
,# 27. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 57033
2016-04-01 23:50:36.168 ThaliTest[2652:4910532] jxcore: startUpdateAdvertisingAndListening
2016-04-01 23:50:36.169 ThaliTest[2652:4910532] server: starting BC3134AD-A0D1-47B0-885A-5F5313680802:1
,2016-04-01 23:50:36.169 ThaliTest[2652:4910532] multipeer manager: start client restart timer: 0x1455d050
2016-04-01 23:50:36.170 ThaliTest[2652:4910532] THEMultipeerManager initialized peer BC3134AD-A0D1-47B0-885A-5F5313680802:1
2016-04-01 23:50:36.171 ,ThaliTest[2652:4910532] jxcore: startUpdateAdvertisingAndListening: success
,ok 103 error should be null
ok 104 error should be null
2016-04-01 23:50:36.177 ThaliTest[2652:4910532] jxcore: startUpdateAdvertisingAndListening
2016-04-01 23:50:36.177 ThaliTest[2652:4910532] THEMultipeerManager stopping peer
2016-04-01 23:50:36.177, ThaliTest[2652:4910532] multipeer manager: stop client timer
2016-04-01 23:50:36.178 ThaliTest[2652:4910532] server: starting BC3134AD-A0D1-47B0-885A-5F5313680802:2
2016-04-01 23:50:36.178 ThaliTest[2652:4910532] multipeer manager: start client restart timer: 0x1455d050
2016-04-01 23:50:36.179 ThaliTest[2652:4910532] THEMultipeerManager initialized peer BC3134AD-A0D1-47B0-885A-5F5313680802:2
2016-04-01 23:50:36.179 ThaliTest[2652:4910532] jxcore: startUpdateAdvertisingAndListening: success
,ok 105 error should be null
,ok 106 error should be null
,# teardown
,2016-04-01 23:50:38.862 ThaliTest[2652:4910376] client: found new peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:2
,2016-04-01 23:50:39.151 ThaliTest[2652:4910532] jxcore: stopAdvertisingAndListening
2016-04-01 23:50:39.151 ThaliTest[2652:4910532] THEMultipeerManager stopping peer
2016-04-01 23:50:39.151 ThaliTest[2652:4910532] multipeer manager: stop client timer
2016-04-01 23:50:39.151 ThaliTest[2652:4910532] jxcore: stopAdvertisingAndListening: success
2016-04-01 23:50:39.151 ThaliTest[2652:4910532] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-04-01 23:50:39.152 ThaliTest[2652:4910532] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 107 error should be null
ok 108 error should be null
# setup
,# 28. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 57038
2016-04-01 23:50:55.970 ThaliTest[2652:4910532] jxcore: stopAdvertisingAndListening
2016-04-01 23:50:55.970 ThaliTest[2652:4910532] THEMultipeerManager stopping peer
2016-04-01 23:50:55.970 ThaliTest[2652:4910532] jxcore: stopAdvertisingAndListening: success
ok 109 error should be null
ok 110 error should be null
2016-04-01 23:50:55.971 ThaliTest[2652:4910532] jxcore: stopAdvertisingAndListening
2016-04-01 23:50:55.971 ThaliTest[2652:4910532] THEMultipeerManager stopping peer
2016-04-01 23:50:55.971 ThaliTest[2652:4910532] jxcore: stopAdvertisingAndListening: success
ok 111 error should be null
ok 112 error should be null
# teardown
,2016-04-01 23:50:56.468 ThaliTest[2652:4910532] jxcore: stopAdvertisingAndListening
2016-04-01 23:50:56.468 ThaliTest[2652:4910532] THEMultipeerManager stopping peer
2016-04-01 23:50:56.468 ThaliTest[2652:4910532] jxcore: stopAdvertisingAndListening: success
2016-04-01 23:50:56.468 ThaliTest[2652:4910532] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 23:50:56.469 ThaliTest[2652,:4910532] jxcore: stopListeningForAdvertisements: success
ok 113 error should be null
ok 114 error should be null
# setup
,# 29. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 57040
ok 115 first call should succeed
ok 116 first call should succeed
ok 117 specific error should be returned
# teardown
,2016-04-01 23:50:57.042 ThaliTest[2652:4910532] jxcore: stopAdvertisingAndListening
2016-04-01 23:50:57.042 ThaliTest[2652:4910532] THEMultipeerManager stopping peer
2016-04-01 23:50:57.042 ThaliTest[2652:4910532] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-01 23:50:57.042 ThaliTest[2652:4910532] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 23:50:57.043 ThaliTest[2652:4910532] jxcore: stopListeningForAdvertisements: success
ok 118 error should be null
ok 119 error should be null
# setup
,# 30. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 57042
2016-04-01 23:50:57.947 ThaliTest[2652:4910532] jxcore: startListeningForAdvertisements
2016-04-01 23:50:57.947 ThaliTest[2652:4910532] multipeer manager: sta,rt client restart timer: 0x1455d050
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-01 23:50:57.948 ThaliTest[2652:4910532] jxcore: startListeningForAdvertisements: success
,2016-04-01 23:50:57.955 ThaliTest[2652:4910532] jxcore: startUpdateAdvertisingAndListening
2016-04-01 23:50:57.955 ThaliTest[2652:4910532] server: starting BC3134AD-A0D1-47B0-885A-5F5313680802:3
2016-04-01 23:50:57.956 ThaliTest[2652:4910532] THEMultipee,rManager initialized peer BC3134AD-A0D1-47B0-885A-5F5313680802:3
2016-04-01 23:50:57.956 ThaliTest[2652:4910532] jxcore: startUpdateAdvertisingAndListening: success
ok 120 called only once
ok 121 discovery state matches
ok 122 advertising state matches
# teardown
,2016-04-01 23:50:58.110 ThaliTest[2652:4910532] jxcore: stopAdvertisingAndListening
2016-04-01 23:50:58.111 ThaliTest[2652:4910532] THEMultipeerManager stopping peer
2016-04-01 23:50:58.111 ThaliTest[2652:4910532] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-01 23:50:58.111 ThaliTest[2652:4910532] jxcore: stopListeningForAdvertisements
2016-04-01 23:50:58.111 ThaliTest[2652:4910532] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 23:50:58.112 ThaliTest[2652:4910532] jxcore: stopListeningForAdvertisements: success
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
# teardown
,ok 130 error should be null
,ok 131 error should be null
# setup
,# 33. wifi peer is marked unavailable if announcements stop
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
,ok 132 host address should match
ok 133 port should match
,ok 134 host address should be null
ok 135 port should should be null
# teardown
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 136 error should be null
ok 137 error should be null
# setup
,# 34. Can call start/stopListeningForAdvertisements
,2016-04-01 23:51:27.768 ThaliTest[2652:4910532] jxcore: startListeningForAdvertisements
2016-04-01 23:51:27.769 ThaliTest[2652:4910532] multipeer manager: start client restart timer: 0x1455d050
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-01 23:51:27.770 ThaliTest[2652:4910532] jxcore: startListeningForAdvertisements: success
ok 138 Can call startListeningForAdvertisements without error
2016-04-01 23:51:27.770 ThaliTest[2652:4910532] jxcore: stopListeningForAdvertisements
2016-04-01 23:51:27.770 ThaliTest[2652:4910532] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 23:51:27.771 ThaliTest[2652:4910532] jxcore: stopListeningForAdvertisements: success
ok 139 Can call stopListeningForAdvertisements without error
# teardown
,2016-04-01 23:51:28.014 ThaliTest[2652:4910532] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 23:51:28.015 ThaliTest[2652:4910532] jxcore: stopListeningForAdvertisements: success
ok 140 Should be able to call stopListeningForAdvertisements in teardown
2016-04-01 23:51:28.016 ThaliTest[2652:4910532] jxcore: stopAdvertisingAndListening
2016-04-01 23:51:28.016 ThaliTest[2652:49105,32] THEMultipeerManager stopping peer
2016-04-01 23:51:28.016 ThaliTest[2652:4910532] jxcore: stopAdvertisingAndListening: success
ok 141 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 35. Calling startListeningForAdvertisements twice is NOT an error
,2016-04-01 23:51:28.541 ThaliTest[2652:4910532] jxcore: startListeningForAdvertisements
2016-04-01 23:51:28.542 ThaliTest[2652:4910532] multipeer manager: start client restart timer: 0x1455d050
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-01 23:51:28.542 ThaliTest[2652:4910532] jxcore: startListeningForAdvertisements: success
ok 142 Can call startListeningForAdvertisements without error
2016-04-01 23:51:28.543 ThaliTes,t[2652:4910532] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-01 23:51:28.543 ThaliTest[2652:4910532] jxcore: startListeningForAdvertisements: success
ok 143 Can call startListeningForAdvertisements twice without error
# teardown
,2016-04-01 23:51:28.695 ThaliTest[2652:4910532] jxcore: stopListeningForAdvertisements
2016-04-01 23:51:28.695 ThaliTest[2652:4910532] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 23:51:28.696 ThaliTest[2652:4910532] jxcore: stopListeningForAdvertisements: success
ok 144 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-01 23:51:28.696 ThaliTest[2652:4910532] jxcore: stopAdvertisingAndListening
2016-04-01 23:51:28.697 ThaliTest[2652:4910532] THEMultipeerManager stopping peer
,2016-04-01 23:51:28.697 ThaliTest[2652:4910532] jxcore: stopAdvertisingAndListening: success
,ok 145 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 36. Calling stopListeningForAdvertisements without calling start is NOT an error
,2016-04-01 23:51:31.643 ThaliTest[2652:4910532] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 23:51:31.643 ThaliTest[2652:49105,32] jxcore: stopListeningForAdvertisements: success
ok 146 Can call stopListeningForAdvertisements without error
2016-04-01 23:51:31.644 ThaliTest[2652:4910532] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 23:51:31.645 ThaliTest[2652:4910532] jxcore: stopListeningForAdvertisements: success
ok 147 Can call stopListeningForAdvertisements without error
# teardown
,2016-04-01 23:51:50.077 ThaliTest[2652:4910532] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 23:51:50.078 ThaliTest[2652:49105,32] jxcore: stopListeningForAdvertisements: success
ok 148 Should be able to call stopListeningForAdvertisements in teardown
2016-04-01 23:51:50.078 ThaliTest[2652:4910532] jxcore: stopAdvertisingAndListening
2016-04-01 23:51:50.078 ThaliTest[2652:49105,32] THEMultipeerManager stopping peer
2016-04-01 23:51:50.078 ThaliTest[2652:4910532] jxcore: stopAdvertisingAndListening: success
ok 149 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 37. Can call start/stopUpdateAdvertisingAndListening
,2016-04-01 23:51:52.362 ThaliTest[2652:4910532] jxcore: startUpdateAdvertisingAndListening
2016-04-01 23:51:52.362 ThaliTest[2652:4910532] server: starting BC3134AD-A0D1-47B0-885A-5F5313680802:4
2016-04-01 23:51:52.363 ThaliTest[2652:4910532] multipeer manager: start client restart timer: 0x1455d050
2016-04-01 23:51:52.363 ThaliTest[2652:4910532] THEMultipeerManager initialized peer BC3134AD-A0D1-47B0-885A-5F5313680802:4
,2016-04-01 23:51:52.365 ThaliTest[2652:4910532] jxcore: startUpdateAdvertisingAndListening: success
ok 150 Can call startUpdateAdvertisingAndListening without error
2016-04-01 23:51:52.366 ThaliTest[2652:4910532] jxcore: stopAdvertisingAndListening
2016,-04-01 23:51:52.366 ThaliTest[2652:4910532] THEMultipeerManager stopping peer
2016-04-01 23:51:52.366 ThaliTest[2652:4910532] multipeer manager: stop client timer
2016-04-01 23:51:52.366 ThaliTest[2652:4910532] jxcore: stopAdvertisingAndListening: success
ok 151 Can call stopAdvertisingAndListening without error
# teardown
,2016-04-01 23:51:52.652 ThaliTest[2652:4910532] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 23:51:52.653 ThaliTest[2652:49105,32] jxcore: stopListeningForAdvertisements: success
ok 152 Should be able to call stopListeningForAdvertisements in teardown
2016-04-01 23:51:52.654 ThaliTest[2652:4910532] jxcore: stopAdvertisingAndListening
2016-04-01 23:51:52.654 ThaliTest[2652:4910532] THEMultipeerManager stopping peer
2016-04-01 23:51:52.654 ThaliTest[2652:4910532] jxcore: stopAdvertisingAndListening: success
ok 153 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-04-01 23:51:53.248 ThaliTest[2652:4910532] jxcore: startUpdateAdvertisingAndListening
2016-04-01 23:51:53.248 ThaliTest[2652:4910532] server: starting BC3134AD-A0D1-47B0-885A-5F5313680802:5
2016-04-01 23:51:53.249 ThaliTest[2652:4910532] multipeer manager: start client restart timer: 0x1455d050
2016-04-01 23:51:53.249 ThaliTest[2652:4910532] THEMultipeerManager initialized peer BC3134AD-A0D1-47B0-885A-5F5313680802:5
,2016-04-01 23:51:53.251 ThaliTest[2652:4910532] jxcore: startUpdateAdvertisingAndListening: success
ok 154 Can call startUpdateAdvertisingAndListening without error
2016-04-01 23:51:53.252 ThaliTest[2652:4910532] jxcore: startUpdateAdvertisingAndListening
2016-04-01 23:51:53.252 ThaliTest[2652:4910532] THEMultipeerManager stopping peer
2016-04-01 23:51:53.252 ThaliTest[2652:4910532] multipeer manager: stop client timer
2016-04-01 23:51:53.252 ThaliTest[2652:4910532] server: starting BC3134AD-A0D1-47B0-885A-5F5313680802:6
2016-04-01 23:51:53.252 ThaliTest[2652:4910532] multipeer manager: start client restart timer: 0x1455d050
2016-04-01 23:51:53.252 ThaliTest[2652:4910532] THEMultipeerManager initialized peer BC3134AD-A0D1-47B0-885A-5F5313680802:6
,2016-04-01 23:51:53.252 ThaliTest[2652:4910532] jxcore: startUpdateAdvertisingAndListening: success
ok 155 Can call startUpdateAdvertisingAndListening twice without error
# teardown
,2016-04-01 23:51:53.648 ThaliTest[2652:4910532] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-04-01 23:51:53.649 ThaliTest[2652:4910532] jxcore: stopListeningForAdvertisements: success
ok 156 Should be able to call stopListeningForAdvertisements in teardown
2016-04-01 23:51:53.650 ThaliTest[2652:4910532] jxcore: stopAdvertisingAndListening
2016-04-01 23:51:53.650 ThaliTest[2652:491053,2] THEMultipeerManager stopping peer
2016-04-01 23:51:53.650 ThaliTest[2652:4910532] multipeer manager: stop client timer
2016-04-01 23:51:53.650 ThaliTest[2652:4910532] jxcore: stopAdvertisingAndListening: success
ok 157 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,2016-04-01 23:51:54.270 ThaliTest[2652:4910532] jxcore: stopAdvertisingAndListening
2016-04-01 23:51:54.271 ThaliTest[2652:4910532] THEMultipeerManager stopping peer
2016-04-01 23:51:54.271 ThaliTest[2652:4910532] jxcore: stopAdvertisingAndListening: suc,cess
ok 158 Can call startUpdateAdvertisingAndListening without error
2016-04-01 23:51:54.271 ThaliTest[2652:4910532] jxcore: stopAdvertisingAndListening
2016-04-01 23:51:54.271 ThaliTest[2652:4910532] THEMultipeerManager stopping peer
2016-04-01 23:51:54.271 ThaliTest[2652:4910532] jxcore: stopAdvertisingAndListening: success
ok 159 Can call stopAdvertisingAndListening without error
# teardown
,2016-04-01 23:51:56.427 ThaliTest[2652:4910532] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 23:51:56.428 ThaliTest[2652:4910532] jxcore: stopListeningForAdvertisements: success
ok 160 Should be able to call stopListeningForAdvertisements in teardown
2016-04-01 23:51:56.429 ThaliTest[2652:4910532] jxcore: stopAdvertisingAndListening
2016-04-01 23:51:56.429 ThaliTest[2652:49105,32] THEMultipeerManager stopping peer
2016-04-01 23:51:56.429 ThaliTest[2652:4910532] jxcore: stopAdvertisingAndListening: success
ok 161 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 40. cannot call connect when start listening for advertisements is not active
,2016-04-01 23:51:56.862 ThaliTest[2652:4910532] jxcore: connect foo
2016-04-01 23:51:56.862 ThaliTest[2652:4910532] jxcore: connect: fail: Start browsing first
,not ok 162 got right error
  ---
    operator: equal
    expected: 'startListeningForAdvertisements is not active'
    actual:   'Start browsing first'
  ...
# teardown
,2016-04-01 23:51:57.003 ThaliTest[2652:4910532] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 23:51:57.003 ThaliTest[2652:49105,32] jxcore: stopListeningForAdvertisements: success
ok 163 Should be able to call stopListeningForAdvertisements in teardown
2016-04-01 23:51:57.004 ThaliTest[2652:4910532] jxcore: stopAdvertisingAndListening
2016-04-01 23:51:57.004 ThaliTest[2652:4910532] THEMultipeerManager stopping peer
2016-04-01 23:51:57.004 ThaliTest[2652:4910532] jxcore: stopAdvertisingAndListening: success
ok 164 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 41. peerAvailabilityChange is called
,2016-04-01 23:51:58.059 ThaliTest[2652:4910532] jxcore: startUpdateAdvertisingAndListening
2016-04-01 23:51:58.059 ThaliTest[2652:4910532] server: starting BC3134AD-A0D1-47B0-885A-5F5313680802:7
2016-04-01 23:51:58.059 ThaliTest[2652:4910532] multipeer m,anager: start client restart timer: 0x1455d050
2016-04-01 23:51:58.060 ThaliTest[2652:4910532] THEMultipeerManager initialized peer BC3134AD-A0D1-47B0-885A-5F5313680802:7
2016-04-01 23:51:58.060 ThaliTest[2652:4910532] jxcore: startUpdateAdvertisingAndListening: success
ok 165 Can call startUpdateAdvertisingAndListeningwithout error
2016-04-01 23:51:58.060 ThaliTest[2652:4910532] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-04-01 23:51:58.061 ThaliTest[2652:4910532] jxcore: startListeningForAdvertisements: success
ok 166 Can call startListeningForAdvertisements without error
,2016-04-01 23:52:00.059 ThaliTest[2652:4910376] client: found new peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:7
2016-04-01 23:52:00.060 ThaliTest[2652:4910376] client: found new peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:7
2016-04-01 23:52:00.060 ThaliTest[2652:4910376] client: found new peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:7
ok 167 peers must be an array
ok 168 peers must not be zero-length
ok 169 peer must have peerIdentifier
ok 170 peerIdentifier must be a string
ok 171 peer must have peerAvailable
ok 172 peer must have pleaseConnect
,# teardown
,2016-04-01 23:52:05.131 ThaliTest[2652:4910532] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-04-01 23:52:05.132 ThaliTest[2652:491053,2] jxcore: stopListeningForAdvertisements: success
ok 173 Should be able to call stopListeningForAdvertisements in teardown
2016-04-01 23:52:05.133 ThaliTest[2652:4910532] jxcore: stopAdvertisingAndListening
2016-04-01 23:52:05.133 ThaliTest[2652:4910532] THEMultipeerManager stopping peer
2016-04-01 23:52:05.133 ThaliTest[2652:4910532] multipeer manager: stop client timer
2016-04-01 23:52:05.133 ThaliTest[2652:4910532] jxcore: stopAdvertisingAndListening: success
ok 174 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 42. Can connect to a remote peer
,2016-04-01 23:52:25.710 ThaliTest[2652:4910532] jxcore: startUpdateAdvertisingAndListening
2016-04-01 23:52:25.710 ThaliTest[2652:4910532] server: starting BC3134AD-A0D1-47B0-885A-5F5313680802:8
2016-04-01 23:52:25.710 ThaliTest[2652:4910532] multipeer manager: start client restart timer: 0x1455d050
2016-04-01 23:52:25.710 ThaliTest[2652:4910532] THEMultipeerManager initialized peer BC3134AD-A0D1-47B0-885A-5F5313680802:8
,2016-04-01 23:52:25.713 ThaliTest[2652:4910532] jxcore: startUpdateAdvertisingAndListening: success
ok 175 Can call startUpdateAdvertisingAndListening without error
2016-04-01 23:52:25.713 ThaliTest[2652:4910532] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-04-01 23:52:25.714 ThaliTest[2652:4910532] jxcore: startListeningForAdvertisements: success
ok 176 Can call startListeningForAdvertisements without error
,2016-04-01 23:52:26.646 ThaliTest[2652:4910376] client: found new peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:8
2016-04-01 23:52:26.646 ThaliTest[2652:4910376] client: found new peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"EEA4391C-4C5F-40D5-B71D-C147ED7B0517:8","pleaseConnect":0}]
2016-04-01 23:52:26.647 ThaliTest[2652:4910532] jxcore: connect EEA4391C-4C5F-40D5-B71D-C147ED7B0517:8
2016-04-01 23:52:26.648 ThaliTest[2652:4910532] client: server will connect
2016-04-01 23:52:26.648 ThaliTest[2652:4910532] client session: reverseConnect
,2016-04-01 23:52:26.648 ThaliTest[2652:4910532] client session: stateChange:0->1 EEA4391C-4C5F-40D5-B71D-C147ED7B0517:8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"53FC597F-8F79-47DA-ABAE-0C427F412EFF:7","pleaseConnect":0}]
,2016-04-01 23:52:27.205 ThaliTest[2652:4910376] client: found new peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8","pleaseConnect":0}]
,2016-04-01 23:52:28.123 ThaliTest[2652:4911244] client session: not connected EEA4391C-4C5F-40D5-B71D-C147ED7B0517:8
2016-04-01 23:52:28.123 ThaliTest[2652:4911244] client session: onLinkFailure: EEA4391C-4C5F-40D5-B71D-C147ED7B0517
2016-04-01 23:52:28.1,23 ThaliTest[2652:4911244] client session: disconnect
2016-04-01 23:52:28.123 ThaliTest[2652:4911244] client session: stateChange:1->0 EEA4391C-4C5F-40D5-B71D-C147ED7B0517:8
2016-04-01 23:52:28.123 ThaliTest[2652:4911244] client session: no connect callback (server initiated)
,2016-04-01 23:52:36.649 ThaliTest[2652:4910376] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect ret,ry - retries left: 9
,2016-04-01 23:52:39.652 ThaliTest[2652:4910532] jxcore: connect EEA4391C-4C5F-40D5-B71D-C147ED7B0517:8
2016-04-01 23:52:39.653 ThaliTest[2652:4910532] client: server will connect
2016-04-01 23:52:39.653 ThaliTest[2652:4910532] client session: reverseConnect
2016-04-01 23:52:39.653 ThaliTest[2652:4910532] client session: stateChange:0->1 EEA4391C-4C5F-40D5-B71D-C147ED7B0517:8
,2016-04-01 23:52:39.786 ThaliTest[2652:4911287] client session: not connected EEA4391C-4C5F-40D5-B71D-C147ED7B0517:8
2016-04-01 23:52:39.786 ThaliTest[2652:4911287] client session: onLinkFailure: EEA4391C-4C5F-40D5-B71D-C147ED7B0517
2016-04-01 23:52:39.786 ThaliTest[2652:4911287] client session: disconnect
2016-04-01 23:52:39.786 ThaliTest[2652:4911287] client session: stateChange:1->0 EEA4391C-4C5F-40D5-B71D-C147ED7B0517:8
2016-04-01 23:52:39.787 ThaliTest[2652:4911287] client session: no connect callback (server initiated)
,2016-04-01 23:52:45.711 ThaliTest[2652:4910376] multipeer manager: restart client
,2016-04-01 23:52:45.725 ThaliTest[2652:4910376] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:8
2016-04-01 23:52:45.725 ThaliTest[2652:4910376] client: found updated peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:8
2016-04-01 23:52:45.725 ThaliTest[2652:4910376] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"53FC597F-8F79-47DA-ABAE-0C427F412EFF:8","pleaseConn,ect":0}]
,2016-04-01 23:52:49.654 ThaliTest[2652:4910376] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-04-01 23:52:52.665 ThaliTest[2652:4910532] jxcore: connect EEA4391C-4C5F-40D5-B71D-C147ED7B0517:8
2016-04-01 23:52:52.666 ThaliTest[2652:4910532] client: server will connect
2016-04-01 23:52:52.666 ThaliTest[2652:4910532] client session: reverseConnect
2016-04-01 23:52:52.666 ThaliTest[2652:4910532] client session: stateChange:0->1 EEA4391C-4C5F-40D5-B71D-C147ED7B0517:8
,2016-04-01 23:52:52.765 ThaliTest[2652:4911322] client session: not connected EEA4391C-4C5F-40D5-B71D-C147ED7B0517:8
2016-04-01 23:52:52.765 ThaliTest[2652:4911322] client session: onLinkFailure: EEA4391C-4C5F-40D5-B71D-C147ED7B0517
2016-04-01 23:52:52.7,65 ThaliTest[2652:4911322] client session: disconnect
2016-04-01 23:52:52.765 ThaliTest[2652:4911322] client session: stateChange:1->0 EEA4391C-4C5F-40D5-B71D-C147ED7B0517:8
2016-04-01 23:52:52.765 ThaliTest[2652:4911322] client session: no connect callback (server initiated)
,2016-04-01 23:53:02.667 ThaliTest[2652:4910376] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-04-01 23:53:05.674 ThaliTest[2652:4910532] jxcore: connect EEA4391C-4C5F-40D5-B71D-C147ED7B0517:8
2016-04-01 23:53:05.674 ThaliTest[2652:4910532] client: server will connect
2016-04-01 23:53:05.674 ThaliTest[2652:4910532] client session: reverseConn,ect
2016-04-01 23:53:05.675 ThaliTest[2652:4910532] client session: stateChange:0->1 EEA4391C-4C5F-40D5-B71D-C147ED7B0517:8
,2016-04-01 23:53:05.711 ThaliTest[2652:4910376] multipeer manager: restart client
,2016-04-01 23:53:05.727 ThaliTest[2652:4910376] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:8
2016-04-01 23:53:05.728 ThaliTest[2652:4910376] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
2016-04-01 23:53:05.728 ThaliTest[2652:4910376] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:8
,2016-04-01 23:53:15.675 ThaliTest[2652:4910376] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-04-01 23:53:18.681 ThaliTest[2652:4910532] jxcore: connect EEA4391C-4C5F-40D5-B71D-C147ED7B0517:8
2016-04-01 23:53:18.681 ThaliTest[2652:4910532] client: already connect(ing/ed) to EEA4391C-4C5F-40D5-B71D-C147ED7B0517:8
2016-04-01 23:53:18.681 ThaliTest[2652:4910532] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-04-01 23:53:21.694 ThaliTest[2652:4910532] jxcore: connect EEA4391C-4C5F-40D5-B71D-C147ED7B0517:8
2016-04-01 23:53:21.694 ThaliTest[2652:4910532] client: already connect(ing/ed) to EEA4391C-4C5F-40D5-B71D-C147ED7B0517:8
2016-04-01 23:53:21.694 Thali,Test[2652:4910532] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-04-01 23:53:24.702 ThaliTest[2652:4910532] jxcore: connect EEA4391C-4C5F-40D5-B71D-C147ED7B0517:8
2016-04-01 23:53:24.702 ThaliTest[2652:4910532] client: already connect(ing/ed) to EEA4391C-4C5F-40D5-B71D-C147ED7B0517:8
2016-04-01 23:53:24.702 ThaliTest[2652:4910532] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-04-01 23:53:25.711 ThaliTest[2652:4910376] multipeer manager: restart client
,2016-04-01 23:53:25.727 ThaliTest[2652:4910376] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:8
2016-04-01 23:53:25.727 ThaliTest[2652:4910376] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
2016-04-01 23:53:25.72,7 ThaliTest[2652:4910376] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:8
,2016-04-01 23:53:27.711 ThaliTest[2652:4910532] jxcore: connect EEA4391C-4C5F-40D5-B71D-C147ED7B0517:8
2016-04-01 23:53:27.711 ThaliTest[2652:4910532] client: already connect(ing/ed) to EEA4391C-4C5F-40D5-B71D-C147ED7B0517:8
2016-04-01 23:53:27.711 Thali,Test[2652:4910532] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-04-01 23:53:30.725 ThaliTest[2652:4910532] jxcore: connect EEA4391C-4C5F-40D5-B71D-C147ED7B0517:8
2016-04-01 23:53:30.725 ThaliTest[2652:4910532] client: already connect(ing/ed) to EEA4391C-4C5F-40D5-B71D-C147ED7B0517:8
2016-04-01 23:53:30.725 ThaliTest[2652:4910532] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-04-01 23:53:33.738 ThaliTest[2652:4910532] jxcore: connect EEA4391C-4C5F-40D5-B71D-C147ED7B0517:8
2016-04-01 23:53:33.738 ThaliTest[2652:4910532] client: already connect(ing/ed) to EEA4391C-4C5F-40D5-B71D-C147ED7B0517:8
2016-04-01 23:53:33.738 Thali,Test[2652:4910532] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
WARN testThaliMobileNative: Too many connect retries!
,not ok 177 Connect failed!
  ---
,    operator: fail
  ...
,# teardown
,2016-04-01 23:53:34.018 ThaliTest[2652:4910532] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-01 23:53:34.019 ThaliTest[2652:4910532] jxcore: stopListeningForAdvertisements: success
ok 178 Should be able to call stopListeningForAdvertisements in teardown
,dvertisingAndListening: success
ok 179 Should be able to call stopAdvertisingAndListening in teardown
2016-04-01 23:53:34.020 ThaliTest[2652:4910532] jxcore: stopAdvertisingAndListening
2016-04-01 23:53:34.020 ThaliTest[2652:4910532] THEMultipeerManager stopping peer
2016-04-01 23:53:34.020 ThaliTest[2652:4910532] client session: disconnect
2016-04-01 23:53:34.020 ThaliTest[2652:4910532] client session: stateChange:1->0 EEA4391C-4C5F-40D5-B71D-C147ED7B0517:8
2016-04-01 23:53:34.020 ThaliTest[2652:4910532] multipeer manager: stop client timer
2016-04-01 23:53:34.021 ThaliTest[2652:4910532] jxcore: stopA,# setup
,# 43. Get error when trying to double connect to a peer
,2016-04-01 23:53:34.998 ThaliTest[2652:4910532] jxcore: startUpdateAdvertisingAndListening
2016-04-01 23:53:34.998 ThaliTest[2652:4910532] server: starting BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-01 23:53:34.998 ThaliTest[2652:4910532] multipeer m,anager: start client restart timer: 0x1455d050
2016-04-01 23:53:34.999 ThaliTest[2652:4910532] THEMultipeerManager initialized peer BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-01 23:53:34.999 ThaliTest[2652:4910532] jxcore: startUpdateAdvertisingAndListening: success
ok 180 Can call startUpdateAdvertisingAndListening without error
2016-04-01 23:53:34.999 ThaliTest[2652:4910532] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-04-01 23:53:35.000 ThaliTest[2652:4910532] jxcore: startListeningForAdvertisements: success
ok 181 Can call startListeningForAdvertisements without error
,2016-04-01 23:53:35.927 ThaliTest[2652:4910376] client: found new peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
2016-04-01 23:53:35.927 ThaliTest[2652:4910376] client: found new peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:8
2016-04-01 23:53:35.928 ThaliTes,t[2652:4910376] client: found new peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:8
2016-04-01 23:53:35.928 ThaliTest[2652:4910532] jxcore: connect 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
2016-04-01 23:53:35.929 ThaliTest[2652:4910532] client session: connect
2016-04-01 23:53:35.929 ThaliTest[2652:4910532] client session: stateChange:0->1 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
,2016-04-01 23:53:36.854 ThaliTest[2652:4911395] client session: not connected 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
2016-04-01 23:53:36.854 ThaliTest[2652:4911395] client session: onLinkFailure: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D
2016-04-01 23:53:36.8,54 ThaliTest[2652:4911395] client session: disconnect
2016-04-01 23:53:36.854 ThaliTest[2652:4911395] client session: stateChange:1->0 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
2016-04-01 23:53:36.855 ThaliTest[2652:4911395] client session: fireConnectCallback: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D
2016-04-01 23:53:36.855 ThaliTest[2652:4911395] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-04-01 23:53:37.444 ThaliTest[2652:4910376] multipeer session: reset timer
2016-04-01 23:53:37.445 ThaliTest[2652:4910376] server: rejecting invitation from 53FC597F-8F79-47DA-ABAE-0C427F412EFF due to previous generation (BC3134AD-A0D1-47B0-885A-5F5313680802:9 != BC3134AD-A0D1-47B0-885A-5F5313680802:8)
,2016-04-01 23:53:39.861 ThaliTest[2652:4910532] jxcore: connect 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
2016-04-01 23:53:39.862 ThaliTest[2652:4910532] client session: connect
2016-04-01 23:53:39.862 ThaliTest[2652:4910532] client session: stateChange:0->1 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
,2016-04-01 23:53:42.277 ThaliTest[2652:4911396] client session: not connected 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
2016-04-01 23:53:42.278 ThaliTest[2652:4911396] client session: onLinkFailure: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D
2016-04-01 23:53:42.2,78 ThaliTest[2652:4911396] client session: disconnect
2016-04-01 23:53:42.278 ThaliTest[2652:4911396] client session: stateChange:1->0 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
2016-04-01 23:53:42.278 ThaliTest[2652:4911396] client session: fireConnectCallback: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D
2016-04-01 23:53:42.278 ThaliTest[2652:4911396] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-04-01 23:53:45.288 ThaliTest[2652:4910532] jxcore: connect 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
2016-04-01 23:53:45.288 ThaliTest[2652:4910532] client session: connect
2016-04-01 23:53:45.288 ThaliTest[2652:4910532] client session: stateChange:0->1 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
,2016-04-01 23:53:45.651 ThaliTest[2652:4911410] client session: not connected 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
2016-04-01 23:53:45.651 ThaliTest[2652:4911410] client session: onLinkFailure: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D
2016-04-01 23:53:45.651 ThaliTest[2652:4911410] client session: disconnect
2016-04-01 23:53:45.651 ThaliTest[2652:4911410] client session: stateChange:1->0 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
2016-04-01 23:53:45.651 ThaliTest[2652:4911410] client session: fireConnectCallb,ack: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D
2016-04-01 23:53:45.651 ThaliTest[2652:4911410] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-04-01 23:53:48.655 ThaliTest[2652:4910532] jxcore: connect 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
2016-04-01 23:53:48.656 ThaliTest[2652:4910532] client session: connect
2016-04-01 23:53:48.656 ThaliTest[2652:4910532] client session: stateChange:0->,1 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
,2016-04-01 23:53:48.763 ThaliTest[2652:4911410] client session: not connected 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
2016-04-01 23:53:48.764 ThaliTest[2652:4911410] client session: onLinkFailure: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D
,2016-04-01 23:53:48.764 ThaliTest[2652:4911410] client session: disconnect
2016-04-01 23:53:48.765 ThaliTest[2652:4911410] client session: stateChange:1->0 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
2016-04-01 23:53:48.765 ThaliTest[2652:4911410] client session: fireConnectCallback: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D
2016-04-01 23:53:48.765 ThaliTest[2652:4911410] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-04-01 23:53:48.839 ThaliTest[2652:4910376] multipeer session: reset timer
2016-04-01 23:53:48.839 ThaliTest[2652:4910376] server: disconnecting to refresh session (53FC597F-8F79-47DA-ABAE-0C427F412EFF)
2016-04-01 23:53:48.840 ThaliTest[2652:4910376] server: rejecting invitation from 53FC597F-8F79-47DA-ABAE-0C427F412EFF due to previous generation (BC3134AD-A0D1-47B0-885A-5F5313680802:9 != BC3134AD-A0D1-47B0-885A-5F5313680802:8)
,2016-04-01 23:53:51.772 ThaliTest[2652:4910532] jxcore: connect 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
2016-04-01 23:53:51.772 ThaliTest[2652:4910532] client session: connect
2016-04-01 23:53:51.772 ThaliTest[2652:4910532] client session: stateChange:0->1 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
,2016-04-01 23:53:51.908 ThaliTest[2652:4911396] client session: not connected 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
2016-04-01 23:53:51.908 ThaliTest[2652:4911396] client session: onLinkFailure: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D
2016-04-01 23:53:51.908 ThaliTest[2652:4911396] client session: disconnect
2016-04-01 23:53:51.908 ThaliTest[2652:4911396] client session: stateChange:1->0 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
2016-04-01 23:53:51.909 ThaliTest[2652:4911396] client session: fireConnectCallback: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D
2016-04-01 23:53:51.909 ThaliTest[2652:4911396] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-04-01 23:53:54.914 ThaliTest[2652:4910532] jxcore: connect 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
2016-04-01 23:53:54.914 ThaliTest[2652:4910532] client session: connect
2016-04-01 23:53:54.915 ThaliTest[2652:4910532] client session: stateChange:0->1 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
,2016-04-01 23:53:54.962 ThaliTest[2652:4911395] client session: not connected 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
2016-04-01 23:53:54.962 ThaliTest[2652:4911395] client session: onLinkFailure: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D
,2016-04-01 23:53:54.962 ThaliTest[2652:4911395] client session: disconnect
,2016-04-01 23:53:54.963 ThaliTest[2652:4911395] client session: stateChange:1->0 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
2016-04-01 23:53:54.963 ThaliTest[2652:4911395] client session: fireConnectCallback: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D
2016-04-01 23:53:54.963 ThaliTest[2652:4911395] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-04-01 23:53:55.000 ThaliTest[2652:4910376] multipeer manager: restart client
,2016-04-01 23:53:55.009 ThaliTest[2652:4910376] client: found updated peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-01 23:53:55.010 ThaliTest[2652:4910376] client: found updated peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-01 23:53:55.012 ThaliTest[2652:4910376] client: found updated peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-01 23:53:57.970 ThaliTest[2652:4910532] jxcore: connect 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
2016-04-01 23:53:57.970 ThaliTest[2652:4910532] client session: connect
2016-04-01 23:53:57.970 ThaliTest[2652:4910532] client session: stateChange:0->1 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-01 23:53:58.123 ThaliTest[2652:4911471] client session: not connected 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-01 23:53:58.124 ThaliTest[2652:4911471] client session: onLinkFailure: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D
2016-04-01 23:53:58.124 ThaliTest[2652:4911471] client session: disconnect
2016-04-01 23:53:58.124 ThaliTest[2652:4911471] client session: stateChange:1->0 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-01 23:53:58.124 ThaliTest[2652:4911471] client session: fireConnectCallb,ack: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D
2016-04-01 23:53:58.124 ThaliTest[2652:4911471] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-04-01 23:54:01.128 ThaliTest[2652:4910532] jxcore: connect 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
2016-04-01 23:54:01.128 ThaliTest[2652:4910532] client session: connect
2016-04-01 23:54:01.128 ThaliTest[2652:4910532] client session: stateChange:0->1 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-01 23:54:01.746 ThaliTest[2652:4911471] client session: not connected 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-01 23:54:01.746 ThaliTest[2652:4911471] client session: onLinkFailure: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D
2016-04-01 23:54:01.7,47 ThaliTest[2652:4911471] client session: disconnect
2016-04-01 23:54:01.747 ThaliTest[2652:4911471] client session: stateChange:1->0 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-01 23:54:01.747 ThaliTest[2652:4911471] client session: fireConnectCallback: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D
2016-04-01 23:54:01.747 ThaliTest[2652:4911471] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-04-01 23:54:01.818 ThaliTest[2652:4910376] multipeer session: reset timer
2016-04-01 23:54:01.818 ThaliTest[2652:4910376] server: disconnecting to refresh session (53FC597F-8F79-47DA-ABAE-0C427F412EFF)
2016-04-01 23:54:01.818 ThaliTest[2652:4910376] server: rejecting invitation from 53FC597F-8F79-47DA-ABAE-0C427F412EFF due to previous generation (BC3134AD-A0D1-47B0-885A-5F5313680802:9 != BC3134AD-A0D1-47B0-885A-5F5313680802:8)
,2016-04-01 23:54:04.759 ThaliTest[2652:4910532] jxcore: connect 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
2016-04-01 23:54:04.759 ThaliTest[2652:4910532] client session: connect
2016-04-01 23:54:04.759 ThaliTest[2652:4910532] client session: stateChange:0->1 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-01 23:54:04.957 ThaliTest[2652:4911376] client session: not connected 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-01 23:54:04.958 ThaliTest[2652:4911376] client session: onLinkFailure: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D
2016-04-01 23:54:04.958 ThaliTest[2652:4911376] client session: disconnect
,2016-04-01 23:54:04.958 ThaliTest[2652:4911376] client session: stateChange:1->0 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-01 23:54:04.959 ThaliTest[2652:4911376] client session: fireConnectCallback: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D
2016-04-01 23:54:04.959 ThaliTest[2652:4911376] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-04-01 23:54:07.960 ThaliTest[2652:4910532] jxcore: connect 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
2016-04-01 23:54:07.961 ThaliTest[2652:4910532] client session: connect
2016-04-01 23:54:07.961 ThaliTest[2652:4910532] client session: stateChange:0->1 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-01 23:54:08.063 ThaliTest[2652:4911395] client session: not connected 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-01 23:54:08.063 ThaliTest[2652:4911395] client session: onLinkFailure: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D
2016-04-01 23:54:08.063 ThaliTest[2652:4911395] client session: disconnect
2016-04-01 23:54:08.064 ThaliTest[2652:4911395] client session: stateChange:1->0 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-01 23:54:08.064 ThaliTest[2652:4911395] client session: fireConnectCallb,ack: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D
2016-04-01 23:54:08.064 ThaliTest[2652:4911395] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
WARN testThaliMobileNative: Too many connect retries!
,2016-04-01 23:54:15.000 ThaliTest[2652:4910376] multipeer manager: restart client
,2016-04-01 23:54:15.008 ThaliTest[2652:4910376] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-01 23:54:15.010 ThaliTest[2652:4910376] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-01 23:54:15.010 ThaliTest[2652:4910376] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
,2016-04-01 23:54:35.000 ThaliTest[2652:4910376] multipeer manager: restart client
,2016-04-01 23:54:35.008 ThaliTest[2652:4910376] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-01 23:54:35.008 ThaliTest[2652:4910376] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-01 23:54:35.008 ThaliTest[2652:4910376] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
,2016-04-01 23:54:55.000 ThaliTest[2652:4910376] multipeer manager: restart client
,2016-04-01 23:54:55.008 ThaliTest[2652:4910376] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-01 23:54:55.009 ThaliTest[2652:4910376] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-01 23:54:55.009 ThaliTest[2652:4910376] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
,2016-04-01 23:55:15.000 ThaliTest[2652:4910376] multipeer manager: restart client
,2016-04-01 23:55:15.010 ThaliTest[2652:4910376] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-01 23:55:15.011 ThaliTest[2652:4910376] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-01 23:55:15.012 ThaliTest[2652:4910376] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-01 23:55:34.999 ThaliTest[2652:4910376] multipeer manager: restart client
,2016-04-01 23:55:35.009 ThaliTest[2652:4910376] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-01 23:55:35.010 ThaliTest[2652:4910376] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-01 23:55:35.011 ThaliTest[2652:4910376] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-01 23:55:55.000 ThaliTest[2652:4910376] multipeer manager: restart client
,2016-04-01 23:55:55.013 ThaliTest[2652:4910376] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-01 23:55:55.013 ThaliTest[2652:4910376] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-01 23:55:55.013 ThaliTest[2652:4910376] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-01 23:56:15.000 ThaliTest[2652:4910376] multipeer manager: restart client
,2016-04-01 23:56:15.011 ThaliTest[2652:4910376] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-01 23:56:15.011 ThaliTest[2652:4910376] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-01 23:56:15.011 ThaliTest[2652:4910376] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-01 23:56:35.000 ThaliTest[2652:4910376] multipeer manager: restart client
,2016-04-01 23:56:35.011 ThaliTest[2652:4910376] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-01 23:56:35.011 ThaliTest[2652:4910376] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-01 23:56:35.012 ThaliTest[2652:4910376] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-01 23:56:55.000 ThaliTest[2652:4910376] multipeer manager: restart client
,2016-04-01 23:56:55.015 ThaliTest[2652:4910376] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-01 23:56:55.015 ThaliTest[2652:4910376] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
,2016-04-01 23:56:55.020 ThaliTest[2652:4910376] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-01 23:57:15.000 ThaliTest[2652:4910376] multipeer manager: restart client
,2016-04-01 23:57:15.010 ThaliTest[2652:4910376] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-01 23:57:15.011 ThaliTest[2652:4910376] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-01 23:57:15.012 ThaliTest[2652:4910376] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-01 23:57:35.000 ThaliTest[2652:4910376] multipeer manager: restart client
,2016-04-01 23:57:35.011 ThaliTest[2652:4910376] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-01 23:57:35.012 ThaliTest[2652:4910376] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-01 23:57:35.012 ThaliTest[2652:4910376] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-01 23:57:55.000 ThaliTest[2652:4910376] multipeer manager: restart client
,2016-04-01 23:57:55.011 ThaliTest[2652:4910376] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
,2016-04-01 23:57:55.012 ThaliTest[2652:4910376] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-01 23:57:55.012 ThaliTest[2652:4910376] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-01 23:58:15.000 ThaliTest[2652:4910376] multipeer manager: restart client
,2016-04-01 23:58:15.011 ThaliTest[2652:4910376] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-01 23:58:15.011 ThaliTest[2652:4910376] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-01 23:58:15.011 ThaliTest[2652:4910376] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-01 23:58:35.000 ThaliTest[2652:4910376] multipeer manager: restart client
,2016-04-01 23:58:35.015 ThaliTest[2652:4910376] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-01 23:58:35.015 ThaliTest[2652:4910376] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-01 23:58:35.019 ThaliTest[2652:4910376] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-01 23:58:55.000 ThaliTest[2652:4910376] multipeer manager: restart client
,2016-04-01 23:58:55.010 ThaliTest[2652:4910376] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-01 23:58:55.011 ThaliTest[2652:4910376] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-01 23:58:55.011 ThaliTest[2652:4910376] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-01 23:59:15.000 ThaliTest[2652:4910376] multipeer manager: restart client
,2016-04-01 23:59:15.014 ThaliTest[2652:4910376] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-01 23:59:15.015 ThaliTest[2652:4910376] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-01 23:59:15.015 ThaliTest[2652:4910376] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-01 23:59:35.000 ThaliTest[2652:4910376] multipeer manager: restart client
,2016-04-01 23:59:35.014 ThaliTest[2652:4910376] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-01 23:59:35.014 ThaliTest[2652:4910376] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-01 23:59:35.018 ThaliTest[2652:4910376] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-01 23:59:55.000 ThaliTest[2652:4910376] multipeer manager: restart client
,2016-04-01 23:59:55.011 ThaliTest[2652:4910376] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-01 23:59:55.011 ThaliTest[2652:4910376] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-01 23:59:55.011 ThaliTest[2652:4910376] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-02 00:00:15.000 ThaliTest[2652:4910376] multipeer manager: restart client
,2016-04-02 00:00:15.011 ThaliTest[2652:4910376] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-02 00:00:15.011 ThaliTest[2652:4910376] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-02 00:00:15.013 ThaliTest[2652:4910376] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-02 00:00:35.000 ThaliTest[2652:4910376] multipeer manager: restart client
,2016-04-02 00:00:35.014 ThaliTest[2652:4910376] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-02 00:00:35.019 ThaliTest[2652:4910376] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-02 00:00:35.019 ThaliTest[2652:4910376] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-02 00:00:55.000 ThaliTest[2652:4910376] multipeer manager: restart client
,2016-04-02 00:00:55.011 ThaliTest[2652:4910376] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-02 00:00:55.011 ThaliTest[2652:4910376] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-02 00:00:55.011 ThaliTest[2652:4910376] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-02 00:01:15.000 ThaliTest[2652:4910376] multipeer manager: restart client
,2016-04-02 00:01:15.011 ThaliTest[2652:4910376] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-02 00:01:15.011 ThaliTest[2652:4910376] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-02 00:01:15.011 ThaliTest[2652:4910376] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-02 00:01:35.000 ThaliTest[2652:4910376] multipeer manager: restart client
,2016-04-02 00:01:35.011 ThaliTest[2652:4910376] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-02 00:01:35.012 ThaliTest[2652:4910376] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-02 00:01:35.012 ThaliTest[2652:4910376] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-02 00:01:55.000 ThaliTest[2652:4910376] multipeer manager: restart client
,2016-04-02 00:01:55.012 ThaliTest[2652:4910376] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-02 00:01:55.013 ThaliTest[2652:4910376] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-02 00:01:55.013 ThaliTest[2652:4910376] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-02 00:02:15.000 ThaliTest[2652:4910376] multipeer manager: restart client
,2016-04-02 00:02:15.014 ThaliTest[2652:4910376] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-02 00:02:15.016 ThaliTest[2652:4910376] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-02 00:02:15.016 ThaliTest[2652:4910376] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-02 00:02:35.000 ThaliTest[2652:4910376] multipeer manager: restart client
,2016-04-02 00:02:35.015 ThaliTest[2652:4910376] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-02 00:02:35.018 ThaliTest[2652:4910376] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-02 00:02:35.018 ThaliTest[2652:4910376] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-02 00:02:54.999 ThaliTest[2652:4910376] multipeer manager: restart client
,2016-04-02 00:02:55.010 ThaliTest[2652:4910376] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-02 00:02:55.012 ThaliTest[2652:4910376] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-02 00:02:55.012 ThaliTest[2652:4910376] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
,2016-04-02 00:03:15.000 ThaliTest[2652:4910376] multipeer manager: restart client
,2016-04-02 00:03:15.010 ThaliTest[2652:4910376] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-02 00:03:15.011 ThaliTest[2652:4910376] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-02 00:03:15.013 ThaliTest[2652:4910376] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-02 00:03:35.000 ThaliTest[2652:4910376] multipeer manager: restart client
,2016-04-02 00:03:35.012 ThaliTest[2652:4910376] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-02 00:03:35.012 ThaliTest[2652:4910376] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
,2016-04-02 00:03:35.014 ThaliTest[2652:4910376] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-02 00:03:55.000 ThaliTest[2652:4910376] multipeer manager: restart client
,2016-04-02 00:03:55.009 ThaliTest[2652:4910376] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-02 00:03:55.010 ThaliTest[2652:4910376] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-02 00:03:55.010 ThaliTest[2652:4910376] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-02 00:04:15.000 ThaliTest[2652:4910376] multipeer manager: restart client
,2016-04-02 00:04:15.012 ThaliTest[2652:4910376] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-02 00:04:15.012 ThaliTest[2652:4910376] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-02 00:04:15.012 ThaliTest[2652:4910376] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-02 00:04:35.000 ThaliTest[2652:4910376] multipeer manager: restart client
,2016-04-02 00:04:35.016 ThaliTest[2652:4910376] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-02 00:04:35.016 ThaliTest[2652:4910376] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-02 00:04:35.017 ThaliTest[2652:4910376] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-02 00:04:55.000 ThaliTest[2652:4910376] multipeer manager: restart client
,2016-04-02 00:04:55.011 ThaliTest[2652:4910376] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-02 00:04:55.011 ThaliTest[2652:4910376] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-02 00:04:55.011 ThaliTest[2652:4910376] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
,2016-04-02 00:05:15.000 ThaliTest[2652:4910376] multipeer manager: restart client
,2016-04-02 00:05:15.011 ThaliTest[2652:4910376] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-02 00:05:15.011 ThaliTest[2652:4910376] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-02 00:05:15.011 ThaliTest[2652:4910376] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-02 00:05:35.000 ThaliTest[2652:4910376] multipeer manager: restart client
,2016-04-02 00:05:35.012 ThaliTest[2652:4910376] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-02 00:05:35.012 ThaliTest[2652:4910376] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-02 00:05:35.012 ThaliTest[2652:4910376] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-02 00:05:55.000 ThaliTest[2652:4910376] multipeer manager: restart client
,2016-04-02 00:05:55.011 ThaliTest[2652:4910376] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-02 00:05:55.012 ThaliTest[2652:4910376] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-02 00:05:55.012 ThaliTest[2652:4910376] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-02 00:06:14.999 ThaliTest[2652:4910376] multipeer manager: restart client
,2016-04-02 00:06:15.011 ThaliTest[2652:4910376] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-02 00:06:15.011 ThaliTest[2652:4910376] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
,2016-04-02 00:06:15.011 ThaliTest[2652:4910376] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-02 00:06:35.000 ThaliTest[2652:4910376] multipeer manager: restart client
,2016-04-02 00:06:35.011 ThaliTest[2652:4910376] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-02 00:06:35.012 ThaliTest[2652:4910376] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-02 00:06:35.012 ThaliTest[2652:4910376] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-02 00:06:55.000 ThaliTest[2652:4910376] multipeer manager: restart client
,2016-04-02 00:06:55.010 ThaliTest[2652:4910376] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-02 00:06:55.010 ThaliTest[2652:4910376] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-02 00:06:55.010 ThaliTest[2652:4910376] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-02 00:07:15.000 ThaliTest[2652:4910376] multipeer manager: restart client
,2016-04-02 00:07:15.010 ThaliTest[2652:4910376] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-02 00:07:15.010 ThaliTest[2652:4910376] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-02 00:07:15.011 ThaliTest[2652:4910376] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-02 00:07:35.000 ThaliTest[2652:4910376] multipeer manager: restart client
,2016-04-02 00:07:35.017 ThaliTest[2652:4910376] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-02 00:07:35.017 ThaliTest[2652:4910376] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-02 00:07:35.017 ThaliTest[2652:4910376] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-02 00:07:55.000 ThaliTest[2652:4910376] multipeer manager: restart client
,2016-04-02 00:07:55.011 ThaliTest[2652:4910376] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-02 00:07:55.011 ThaliTest[2652:4910376] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-02 00:07:55.011 ThaliTest[2652:4910376] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-02 00:08:15.000 ThaliTest[2652:4910376] multipeer manager: restart client
,2016-04-02 00:08:15.011 ThaliTest[2652:4910376] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-02 00:08:15.011 ThaliTest[2652:4910376] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-02 00:08:15.012 ThaliTest[2652:4910376] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-02 00:08:35.000 ThaliTest[2652:4910376] multipeer manager: restart client
,2016-04-02 00:08:35.011 ThaliTest[2652:4910376] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-02 00:08:35.011 ThaliTest[2652:4910376] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-02 00:08:35.01,1 ThaliTest[2652:4910376] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-02 00:08:55.000 ThaliTest[2652:4910376] multipeer manager: restart client
,2016-04-02 00:08:55.011 ThaliTest[2652:4910376] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-02 00:08:55.011 ThaliTest[2652:4910376] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-02 00:08:55.011 ThaliTest[2652:4910376] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9

```
