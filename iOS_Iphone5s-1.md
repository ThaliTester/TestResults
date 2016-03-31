#### Test 64746945aaa3c62_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/64746945aaa3c62/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/400D27BC-FE03-4264-B717-D20B1FF625A5/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/400D27BC-FE03-4264-B717-D20B1FF625A5/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/64746945aaa3c62/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/64746945aaa3c62/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/4036897F-38D6-4AF0-A9A7-C193AE3D40E7/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49633"
,(lldb)     command script import "/tmp/400D27BC-FE03-4264-B717-D20B1FF625A5/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-03-31 10:10:15.097 ThaliTest[2559:4700406] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/8DEB4A14-B481-4889-BBD0-43C652B12F54/Library/Cookies/Cookies.binarycookies
,2016-03-31 10:10:15.350 ThaliTest[2559:4700406] Apache Cordova native platform version 4.1.0 is starting.
,2016-03-31 10:10:15.351 ThaliTest[2559:4700406] Multi-tasking -> Device: YES, App: YES
,2016-03-31 10:10:15.370 ThaliTest[2559:4700406] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-31 10:10:16.172 ThaliTest[2559:4700406] Using UIWebView
,2016-03-31 10:10:16.175 ThaliTest[2559:4700406] [CDVTimer][handleopenurl] 0.177026ms
,2016-03-31 10:10:16.178 ThaliTest[2559:4700406] [CDVTimer][intentandnavigationfilter] 2.977967ms
2016-03-31 10:10:16.179 ThaliTest[2559:4700406] [CDVTimer][gesturehandler] 0.148952ms
2016-03-31 10:10:16.179 ThaliTest[2559:4700406] [CDVTimer][TotalPluginS,tartup] 4.050016ms
,2016-03-31 10:10:19.378 ThaliTest[2559:4700406] Resetting plugins due to page load.
,2016-03-31 10:10:20.666 ThaliTest[2559:4700406] Finished load of: file:///var/mobile/Containers/Bundle/Application/4036897F-38D6-4AF0-A9A7-C193AE3D40E7/ThaliTest.app/www/index.html
,2016-03-31 10:10:20.845 ThaliTest[2559:4700406] JXcore Cordova plugin initializing
,2016-03-31 10:10:20.926 ThaliTest[2559:4700538] JXcore instance initializing
Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-31 10:10:29.123 ThaliTest[2559:4700538] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-31 10:10:29.123 ThaliTest[2559:4700538] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-31 10:10:29.124 ThaliTest[2559:4,700538] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-31 10:10:29.125 ThaliTest[2559:4700538] jxcore: didRegisterToNativ,e incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4036897F-38D6-4AF0-A9A7-C193AE3D40E7/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4036897F-38D6-4AF0-A9A7-C193AE3D40E7/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4036897F-38D6-4AF0-A9A7-C193AE3D40E7/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4036897F-38D6-4AF0-A9A7-C193AE3D40E7/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4036897F-38D6-4AF0-A9A7-C193AE3D40E7/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4036897F-38D6-4AF0-A9A7-C193AE3D40E7/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4036897F-38D6-4AF0-A9A7-C193AE3D40E7/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4036897F-38D6-4AF0-A9A7-C193AE3D40E7/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4036897F-38D6-4AF0-A9A7-C193AE3D40E7/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4036897F-38D6-4AF0-A9A7-C193AE3D40E7/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4036897F-38D6-4AF0-A9A7-C193AE3D40E7/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4036897F-38D6-4AF0-A9A7-C193AE3D40E7/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4036897F-38D6-4AF0-A9A7-C193AE3D40E7/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4036897F-38D6-4AF0-A9A7-C193AE3D40E7/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4036897F-38D6-4AF0-A9A7-C193AE3D40E7/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4036897F-38D6-4AF0-A9A7-C193AE3D40E7/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4036897F-38D6-4AF0-A9A7-C193AE3D40E7/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4036897F-38D6-4AF0-A9A7-C193AE3D40E7/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4036897F-38D6-4AF0-A9A7-C193AE3D40E7/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4036897F-38D6-4AF0-A9A7-C193AE3D40E7/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4036897F-38D6-4AF0-A9A7-C193AE3D40E7/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4036897F-38D6-4AF0-A9A7-C193AE3D40E7/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-31 10:10:35.887 ThaliTest[2559:4700406] THREAD WARNING: ['JXcore'] took '6395.528809' ms. Plugin should use a background thread.
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 56512
,ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 56514
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
DEBUG createNativeListener: listening 56517
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: listening 56521
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,ok 7 Send/recvd #1 should be equal length
,ok 8 Send/recvd #1 should be same
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
DEBUG createNativeListener: listening 56526
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
,DEBUG createNativeListener: listening 56530
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,ok 14 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: incoming socket close
,ok 15 socket shouldn't close until after incoming
ok 16 incoming is cleaned up
# teardown
,# setup
,# 7. native server - closing outgoing socket cleans associated mux stream
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 56534
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
,DEBUG createNativeListener: listening 56538
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
DEBUG createNativeListener: listening 56542
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
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
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
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
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListene,r: new stream: 
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
,DEBUG createNativeListener: listening 56596
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
,DEBUG createNativeListener: listening 56600
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
,# 16. multiplex can send data
,ok 48 String should be length:200
,# teardown
,# setup
,# 17. enqueue and run in order
,ok 49 firstPromise setTimeout
ok 50 firstPromise result
ok 51 firstPromise testValue
,ok 52 secondPromise setTimeout
,ok 53 secondPromise result
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
,ok 66 fourth
,ok 67 second
,ok 68 secondPromise - in then
,ok 69 first
,ok 70 firstPromise - in catch
,ok 71 third
,ok 72 thirdPromise - in then
,ok 73 testingPromises
,# teardown
,# setup
,# 20. queues handled independently
,ok 74 all short operations completed before the long resolves
,# teardown
,# setup
,# 21. basic
,ok 75 sane
# teardown
,# setup
,# 22. another
,ok 76 sane
# teardown
,# setup
,# 23. can pass data in setup
,ok 77 test participant has uuid
ok 78 participant data matches
ok 79 test participant has uuid
ok 80 participant data matches
,ok 81 test participant has uuid
,ok 82 participant data matches
ok 83 own UUID is found from the participants list
# teardown
,# setup
,# 24. #startListeningForAdvertisements should fail if start not called
,ok 84 specific error should be returned
# teardown
,ok 85 error should be null
ok 86 error should be null
,# setup
,# 25. #startUpdateAdvertisingAndListening should fail if start not called
,ok 87 specific error should be returned
# teardown
,ok 88 error should be null
ok 89 error should be null
# setup
,# 26. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 56612
2016-03-31 10:13:05.444 ThaliTest[2559:4700538] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: ,{"advertisingActive":false,"discoveryActive":false}
2016-03-31 10:13:05.444 ThaliTest[2559:4700538] jxcore: stopListeningForAdvertisements: success
ok 90 error should be null
ok 91 error should be null
2016-03-31 10:13:05.446 ThaliTest[2559:4700538] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 10:13:05.447 ThaliTest[2559:4700538] jxcore: stopListeningForAdvertisements: succes,s
ok 92 error should be null
,ok 93 error should be null
# teardown
,2016-03-31 10:13:05.615 ThaliTest[2559:4700538] jxcore: stopAdvertisingAndListening
2016-03-31 10:13:05.615 ThaliTest[2559:4700538] THEMultipeerManager stopping peer
2016-03-31 10:13:05.615 ThaliTest[2559:4700538] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-31 10:13:05.615 ThaliTest[2559:4700538] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 10:13:05.616 ThaliTest[2559:4700538] jxcore: stopListeningForAdvertisements: success
ok 94 error should be null
ok 95 error should be null
# setup
,# 27. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 56614
2016-03-31 10:13:06.021 ThaliTest[2559:4700538] jxcore: startListeningForAdvertisements
,2016-03-31 10:13:06.023 ThaliTest[2559:4700538] multipeer manager: start client restart timer: 0x16ee8460
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 10:13:06.024 ThaliTest[2559:4700538] jxcore: startListeningForAdvertisements: success
,ok 96 error should be null
ok 97 error should be null
2016-03-31 10:13:06.034 ThaliTest[2559:4700538] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 10:13:06.035 ThaliTest[2559:4700538] jxcore: startListeningForAdvertisements: success
ok 98 error should be null
ok 99 error should be null
# teardown
,2016-03-31 10:13:06.797 ThaliTest[2559:4700538] jxcore: stopAdvertisingAndListening
2016-03-31 10:13:06.797 ThaliTest[2559:4700538] THEMultipeerManager stopping peer
2016-03-31 10:13:06.798 ThaliTest[2559:4700538] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-31 10:13:06.798 ThaliTest[2559:4700538] jxcore: stopListeningForAdvertisements
2016-03-31 10:13:06.798 ThaliTest[2559:4700538] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-31 10:13:06.799 ThaliTest[2559:4700538] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 100 error should be null
ok 101 error should be null
# setup
,# 28. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 56616
,2016-03-31 10:13:07.039 ThaliTest[2559:4700538] jxcore: startUpdateAdvertisingAndListening
,2016-03-31 10:13:07.040 ThaliTest[2559:4700538] server: starting 3F6A8788-1777-4148-9D5D-A7C8608DD267:1
,2016-03-31 10:13:07.042 ThaliTest[2559:4700538] multipeer manager: start client restart timer: 0x16ee8460
,2016-03-31 10:13:07.047 ThaliTest[2559:4700538] THEMultipeerManager initialized peer 3F6A8788-1777-4148-9D5D-A7C8608DD267:1
,2016-03-31 10:13:07.048 ThaliTest[2559:4700538] jxcore: startUpdateAdvertisingAndListening: success
,ok 102 error should be null
,ok 103 error should be null
,2016-03-31 10:13:07.083 ThaliTest[2559:4700538] jxcore: startUpdateAdvertisingAndListening
,2016-03-31 10:13:07.084 ThaliTest[2559:4700538] THEMultipeerManager stopping peer
,2016-03-31 10:13:07.086 ThaliTest[2559:4700538] multipeer manager: stop client timer
,2016-03-31 10:13:07.088 ThaliTest[2559:4700538] server: starting 3F6A8788-1777-4148-9D5D-A7C8608DD267:2
,2016-03-31 10:13:07.089 ThaliTest[2559:4700538] multipeer manager: start client restart timer: 0x16ee8460
,2016-03-31 10:13:07.093 ThaliTest[2559:4700538] THEMultipeerManager initialized peer 3F6A8788-1777-4148-9D5D-A7C8608DD267:2
,2016-03-31 10:13:07.094 ThaliTest[2559:4700538] jxcore: startUpdateAdvertisingAndListening: success
,ok 104 error should be null
,ok 105 error should be null
,# teardown
,2016-03-31 10:13:07.863 ThaliTest[2559:4700538] jxcore: stopAdvertisingAndListening
2016-03-31 10:13:07.863 ThaliTest[2559:4700538] THEMultipeerManager stopping peer
2016-03-31 10:13:07.863 ThaliTest[2559:4700538] multipeer manager: stop client timer
2016-03-31 10:13:07.863 ThaliTest[2559:4700538] jxcore: stopAdvertisingAndListening: success
2016-03-31 10:13:07.864 ThaliTest[2559:4700538] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-31 10:13:07.864 ThaliTest[2559:4700538] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 106 error should be null
ok 107 error should be null
# setup
,# 29. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 56621
2016-03-31 10:13:08.504 ThaliTest[2559:4700538] jxcore: stopAdvertisingAndListening
2016-03-31 10:13:08.504 ThaliTest[2559:4700538] THEMultipeerManager stoppi,ng peer
2016-03-31 10:13:08.504 ThaliTest[2559:4700538] jxcore: stopAdvertisingAndListening: success
ok 108 error should be null
ok 109 error should be null
2016-03-31 10:13:08.506 ThaliTest[2559:4700538] jxcore: stopAdvertisingAndListening
2016-03-31 10:13:08.506 ThaliTest[2559:4700538] THEMultipeerManager stopping peer
2016-03-31 10:13:08.506 ThaliTest[2559:4700538] jxcore: stopAdvertisingAndListening: success
,ok 110 error should be null
ok 111 error should be null
# teardown
,2016-03-31 10:13:08.612 ThaliTest[2559:4700538] jxcore: stopAdvertisingAndListening
2016-03-31 10:13:08.612 ThaliTest[2559:4700538] THEMultipeerManager stopping peer
2016-03-31 10:13:08.613 ThaliTest[2559:4700538] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-31 10:13:08.613 ThaliTest[2559:4700538] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 10:13:08.613 ThaliTest[2559:4700538] jxcore: stopListeningForAdvertisements: success
ok 112 error should be null
ok 113 error should be null
# setup
,# 30. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 56623
ok 114 first call should succeed
ok 115 first call should succeed
ok 116 specific error should be returned
# teardown
,2016-03-31 10:13:09.446 ThaliTest[2559:4700538] jxcore: stopAdvertisingAndListening
2016-03-31 10:13:09.447 ThaliTest[2559:4700538] THEMultipeerManager stopping peer
2016-03-31 10:13:09.447 ThaliTest[2559:4700538] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-31 10:13:09.447 ThaliTest[2559:4700538] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 10:13:09.448 ThaliTest[2559:4700538] jxcore: stopListeningForAdvertisements: success
ok 117 error should be null
ok 118 error should be null
# setup
,# 31. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 56625
2016-03-31 10:13:09.894 ThaliTest[2559:4700538] jxcore: startListeningForAdvertisements
2016-03-31 10:13:09.894 ThaliTest[2559:4700538] multipeer manager: sta,rt client restart timer: 0x16ee8460
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 10:13:09.896 ThaliTest[2559:4700538] jxcore: startListeningForAdvertisements: success
,2016-03-31 10:13:09.926 ThaliTest[2559:4700538] jxcore: startUpdateAdvertisingAndListening
2016-03-31 10:13:09.926 ThaliTest[2559:4700538] server: starting 3F6A8788-1777-4148-9D5D-A7C8608DD267:3
2016-03-31 10:13:09.927 ThaliTest[2559:4700538] THEMultipee,rManager initialized peer 3F6A8788-1777-4148-9D5D-A7C8608DD267:3
2016-03-31 10:13:09.927 ThaliTest[2559:4700538] jxcore: startUpdateAdvertisingAndListening: success
ok 119 called only once
ok 120 discovery state matches
ok 121 advertising state matches
# teardown
,2016-03-31 10:13:10.122 ThaliTest[2559:4700538] jxcore: stopAdvertisingAndListening
2016-03-31 10:13:10.122 ThaliTest[2559:4700538] THEMultipeerManager stopping peer
2016-03-31 10:13:10.123 ThaliTest[2559:4700538] jxcore: stopAdvertisingAndListening: success
2016-03-31 10:13:10.123 ThaliTest[2559:4700538] jxcore: stopListeningForAdvertisements
2016-03-31 10:13:10.123 ThaliTest[2559:4700538] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 10:13:10.124 ThaliTest[2559:4700538] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 122 error should be null
ok 123 error should be null
# setup
,# 32. does not send duplicate availability changes
,ok 124 should be called once
,ok 125 should not have been called more than once
,# teardown
,ok 126 error should be null
ok 127 error should be null
# setup
,# 33. can get the network status
,ok 128 network status should have certain non-empty properties
# teardown
,ok 129 error should be null
ok 130 error should be null
# setup
,# 34. wifi peer is marked unavailable if announcements stop
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
,ok 131 host address should match
ok 132 port should match
,ok 133 host address should be null
ok 134 port should should be null
,# teardown
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 135 error should be null
ok 136 error should be null
# setup
,# 35. Can call start/stopListeningForAdvertisements
,2016-03-31 10:13:44.673 ThaliTest[2559:4700538] jxcore: startListeningForAdvertisements
2016-03-31 10:13:44.673 ThaliTest[2559:4700538] multipeer manager: start client restart timer: 0x16ee8460
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 10:13:44.674 ThaliTest[2559:4700538] jxcore: startListeningForAdvertisements: success
ok 137 Can call startListeningForAdvertisements without error
2016-03-31 10:13:44.675 ThaliTes,t[2559:4700538] jxcore: stopListeningForAdvertisements
2016-03-31 10:13:44.675 ThaliTest[2559:4700538] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 10:13:44.676 ThaliTest[2559:4700538] jxcore: stopListeningForAdvertisements: success
ok 138 Can call stopListeningForAdvertisements without error
# teardown
,2016-03-31 10:13:44.926 ThaliTest[2559:4700538] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 10:13:44.928 ThaliTest[2559:4700538] jxcore: stopListeningForAdvertisements: success
,ok 139 Should be able to call stopListeningForAdvertisments in teardown
2016-03-31 10:13:44.929 ThaliTest[2559:4700538] jxcore: stopAdvertisingAndListening
2016-03-31 10:13:44.929 ThaliTest[2559:4700538] THEMultipeerManager stopping peer
2016-03-31 10:1,3:44.929 ThaliTest[2559:4700538] jxcore: stopAdvertisingAndListening: success
ok 140 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 36. Calling startListeningForAdvertisements twice is NOT an error
,2016-03-31 10:14:10.047 ThaliTest[2559:4700538] jxcore: startListeningForAdvertisements
2016-03-31 10:14:10.047 ThaliTest[2559:4700538] multipeer manager: start client restart timer: 0x16ee8460
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 10:14:10.048 ThaliTest[2559:4700538] jxcore: startListeningForAdvertisements: success
ok 141 Can call startListeningForAdvertisements without error
2016-03-31 10:14:10.049 ThaliTes,t[2559:4700538] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 10:14:10.049 ThaliTest[2559:4700538] jxcore: startListeningForAdvertisements: success
ok 142 Can call startListeningForAdvertisements twice without error
# teardown
,2016-03-31 10:14:19.886 ThaliTest[2559:4700538] jxcore: stopListeningForAdvertisements
2016-03-31 10:14:19.887 ThaliTest[2559:4700538] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisi,ngActive":false,"discoveryActive":false}
2016-03-31 10:14:19.887 ThaliTest[2559:4700538] jxcore: stopListeningForAdvertisements: success
ok 143 Should be able to call stopListeningForAdvertisments in teardown
2016-03-31 10:14:19.888 ThaliTest[2559:47005,38] jxcore: stopAdvertisingAndListening
2016-03-31 10:14:19.888 ThaliTest[2559:4700538] THEMultipeerManager stopping peer
2016-03-31 10:14:19.888 ThaliTest[2559:4700538] jxcore: stopAdvertisingAndListening: success
ok 144 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 37. Can call start/stopUpdateAdvertisingAndListening
,2016-03-31 10:14:51.877 ThaliTest[2559:4700538] jxcore: startUpdateAdvertisingAndListening
2016-03-31 10:14:51.877 ThaliTest[2559:4700538] server: starting 3F6A8788-1777-4148-9D5D-A7C8608DD267:4
2016-03-31 10:14:51.877 ThaliTest[2559:4700538] multipeer m,anager: start client restart timer: 0x16ee8460
2016-03-31 10:14:51.877 ThaliTest[2559:4700538] THEMultipeerManager initialized peer 3F6A8788-1777-4148-9D5D-A7C8608DD267:4
2016-03-31 10:14:51.878 ThaliTest[2559:4700538] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 145 Can call startUpdateAdvertisingAndListening without error
2016-03-31 10:14:51.878 ThaliTest[2559:4700538] jxcore: stopAdvertisingAndListening
2016-03-31 10:14:51.878 ThaliTest[2559:4700538] THEMultipeerManager stopping peer
,2016-03-31 10:14:51.879 ThaliTest[2559:4700538] multipeer manager: stop client timer
2016-03-31 10:14:51.883 ThaliTest[2559:4700538] jxcore: stopAdvertisingAndListening: success
ok 146 Can call stopAdvertisingAndListening without error
# teardown
,2016-03-31 10:15:01.363 ThaliTest[2559:4700538] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-31 10:15:01.365 ThaliTest[2559:4700538] jxcore: stopListeningForAdvertisements: success
ok 147 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-31 10:15:01.366 ThaliTest[2559:4700538] jxcore: stopAdvertisingAndListening
2016-03-31 10:15:01.366 ThaliTest[2559:4700538] THEMultipeerManager stopping peer
2016-03-31 10:15:01.366 ThaliTest[2559:4700538] jxcore: stopAdvertisingAndListening: success
ok 148 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-03-31 10:16:15.206 ThaliTest[2559:4700538] jxcore: startUpdateAdvertisingAndListening
2016-03-31 10:16:15.207 ThaliTest[2559:4700538] server: starting 3F6A8788-1777-4148-9D5D-A7C8608DD267:5
2016-03-31 10:16:15.207 ThaliTest[2559:4700538] multipeer manager: start client restart timer: 0x16ee8460
2016-03-31 10:16:15.207 ThaliTest[2559:4700538] THEMultipeerManager initialized peer 3F6A8788-1777-4148-9D5D-A7C8608DD267:5
2016-03-31 10:16:15.207 ThaliTest[2559:4700538] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 149 Can call startUpdateAdvertisingAndListening without error
2016-03-31 10:16:15.210 ThaliTest[2559:4700538] jxcore: startUpdateAdvertisingAndListening
2016-03-31 10:16:15.210 ThaliTest[2559:4700538] THEMultipeerManager stopping peer
2016-03-31 10:16:15.210 ThaliTest[2559:4700538] multipeer manager: stop client timer
2016-03-31 10:16:15.210 ThaliTest[2559:4700538] server: starting 3F6A8788-1777-4148-9D5D-A7C8608DD267:6
2016-03-31 10:16:15.211 ThaliTest[2559:4700538] multipeer man,a,ger: start client restart timer: 0x16ee8460
2016-03-31 10:16:15.214 ThaliTest[2559:4700538] THEMultipeerManager initialized peer 3F6A8788-1777-4148-9D5D-A7C8608DD267:6
2016-03-31 10:16:15.214 ThaliTest[2559:4700538] jxcore: startUpdateAdvertisingAndListening: success
ok 150 Can call startUpdateAdvertisingAndListening twice without error
# teardown
,2016-03-31 10:16:15.984 ThaliTest[2559:4700538] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-31 10:16:15.985 ThaliTest[2559:470053,8] jxcore: stopListeningForAdvertisements: success
ok 151 Should be able to call stopListeningForAdvertisments in teardown
2016-03-31 10:16:15.985 ThaliTest[2559:4700538] jxcore: stopAdvertisingAndListening
2016-03-31 10:16:15.985 ThaliTest[2559:4700538] THEMultipeerManager stopping peer
2016-03-31 10:16:15.986 ThaliTest[2559:4700538] multipeer manager: stop client timer
2016-03-31 10:16:15.986 ThaliTest[2559:4700538] jxcore: stopAdvertisingAndListening: success
ok 152 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 39. peerAvailabilityChange is called
,2016-03-31 10:16:16.481 ThaliTest[2559:4700538] jxcore: startUpdateAdvertisingAndListening
2016-03-31 10:16:16.481 ThaliTest[2559:4700538] server: starting 3F6A8788-1777-4148-9D5D-A7C8608DD267:7
2016-03-31 10:16:16.481 ThaliTest[2559:4700538] multipeer manager: start client restart timer: 0x16ee8460
2016-03-31 10:16:16.481 ThaliTest[2559:4700538] THEMultipeerManager initialized peer 3F6A8788-1777-4148-9D5D-A7C8608DD267:7
2016-03-31 10:16:16.481 ThaliTest[2559:4700538] jxcore: startUpdateAdvertisingAndListening: success
ok 153 Can call startUpdateAdvertisingAndListeningwithout error
2016-03-31 10:16:16.482 ThaliTest[2559:4700538] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertising,Active":true,"discoveryActive":true}
2016-03-31 10:16:16.483 ThaliTest[2559:4700538] jxcore: startListeningForAdvertisements: success
ok 154 Can call startListeningForAdvertisements without error
,2016-03-31 10:16:17.620 ThaliTest[2559:4700406] client: found new peer: 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:7
,ok 155 peers must be an array
ok 156 peers must not be zero-length
,ok 157 peer must have peerIdentifier
,ok 158 peerIdentifier must be a string
,ok 159 peer must have peerAvailable
,ok 160 peer must have pleaseConnect
,# teardown
,2016-03-31 10:16:18.162 ThaliTest[2559:4700406] client: found new peer: 2F92EB85-432C-485C-AE1C-D018859FD29C:7
,2016-03-31 10:16:18.356 ThaliTest[2559:4700538] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-31 10:16:18.357 ThaliTest[2559:470053,8] jxcore: stopListeningForAdvertisements: success
ok 161 Should be able to call stopListeningForAdvertisments in teardown
2016-03-31 10:16:18.358 ThaliTest[2559:4700538] jxcore: stopAdvertisingAndListening
2016-03-31 10:16:18.358 ThaliTest[2559:4700538] THEMultipeerManager stopping peer
2016-03-31 10:16:18.358 ThaliTest[2559:4700538] multipeer manager: stop client timer
2016-03-31 10:16:18.359 ThaliTest[2559:4700538] jxcore: stopAdvertisingAndListening: success
ok 162 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 40. Can connect to a remote peer
,2016-03-31 10:16:18.742 ThaliTest[2559:4700538] jxcore: startUpdateAdvertisingAndListening
2016-03-31 10:16:18.742 ThaliTest[2559:4700538] server: starting 3F6A8788-1777-4148-9D5D-A7C8608DD267:8
,2016-03-31 10:16:18.743 ThaliTest[2559:4700538] multipeer manager: start client restart timer: 0x16ee8460
2016-03-31 10:16:18.743 ThaliTest[2559:4700538] THEMultipeerManager initialized peer 3F6A8788-1777-4148-9D5D-A7C8608DD267:8
2016-03-31 10:16:18.744 ,ThaliTest[2559:4700538] jxcore: startUpdateAdvertisingAndListening: success
ok 163 Can call startUpdateAdvertisingAndListening without error
2016-03-31 10:16:18.745 ThaliTest[2559:4700538] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-31 10:16:18.745 ThaliTest[2559:4700538] jxcore: startListeningForAdvertisements: success
,ok 164 Can call startListeningForAdvertisements without error
,2016-03-31 10:16:19.537 ThaliTest[2559:4700406] client: found new peer: 2F92EB85-432C-485C-AE1C-D018859FD29C:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"2F92EB85-432C-485C-AE1C-D018859FD29C:7","pleaseConnect":0}]
,2016-03-31 10:16:19.539 ThaliTest[2559:4700538] jxcore: connect 2F92EB85-432C-485C-AE1C-D018859FD29C:7
2016-03-31 10:16:19.539 ThaliTest[2559:4700538] client session: connect
2016-03-31 10:16:19.540 ThaliTest[2559:4700538] client session: stateChange:0->1 2F92EB85-432C-485C-AE1C-D018859FD29C:7
,2016-03-31 10:16:19.715 ThaliTest[2559:4700406] client: found new peer: 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:7","pleaseConnect":0}]
,2016-03-31 10:16:19.969 ThaliTest[2559:4701258] client session: not connected 2F92EB85-432C-485C-AE1C-D018859FD29C:7
2016-03-31 10:16:19.970 ThaliTest[2559:4701258] client session: onLinkFailure: 2F92EB85-432C-485C-AE1C-D018859FD29C
2016-03-31 10:16:19.970 ThaliTest[2559:4701258] client session: disconnect
2016-03-31 10:16:19.970 ThaliTest[2559:4701258] client session: stateChange:1->0 2F92EB85-432C-485C-AE1C-D018859FD29C:7
2016-03-31 10:16:19.970 ThaliTest[2559:4701258] client session: fireConnectCallb,ack: 2F92EB85-432C-485C-AE1C-D018859FD29C
2016-03-31 10:16:19.970 ThaliTest[2559:4701258] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-31 10:16:22.983 ThaliTest[2559:4700538] jxcore: connect 2F92EB85-432C-485C-AE1C-D018859FD29C:7
2016-03-31 10:16:22.983 ThaliTest[2559:4700538] client session: connect
2016-03-31 10:16:22.984 ThaliTest[2559:4700538] client session: stateChange:0->,1 2F92EB85-432C-485C-AE1C-D018859FD29C:7
,2016-03-31 10:16:23.298 ThaliTest[2559:4701257] client session: not connected 2F92EB85-432C-485C-AE1C-D018859FD29C:7
,2016-03-31 10:16:23.300 ThaliTest[2559:4701257] client session: onLinkFailure: 2F92EB85-432C-485C-AE1C-D018859FD29C
2016-03-31 10:16:23.301 ThaliTest[2559:4701257] client session: disconnect
2016-03-31 10:16:23.301 ThaliTest[2559:4701257] client session: stateChange:1->0 2F92EB85-432C-485C-AE1C-D018859FD29C:7
2016-03-31 10:16:23.301 ThaliTest[2559:4701257] client session: fireConnectCallback: 2F92EB85-432C-485C-AE1C-D018859FD29C
2016-03-31 10:16:23.301 ThaliTest[2559:4701257] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-31 10:16:26.304 ThaliTest[2559:4700538] jxcore: connect 2F92EB85-432C-485C-AE1C-D018859FD29C:7
2016-03-31 10:16:26.304 ThaliTest[2559:4700538] client session: connect
2016-03-31 10:16:26.304 ThaliTest[2559:4700538] client session: stateChange:0->1 2F92EB85-432C-485C-AE1C-D018859FD29C:7
,2016-03-31 10:16:26.525 ThaliTest[2559:4701257] client session: not connected 2F92EB85-432C-485C-AE1C-D018859FD29C:7
2016-03-31 10:16:26.525 ThaliTest[2559:4701257] client session: onLinkFailure: 2F92EB85-432C-485C-AE1C-D018859FD29C
2016-03-31 10:16:26.525 ThaliTest[2559:4701257] client session: disconnect
2016-03-31 10:16:26.525 ThaliTest[2559:4701257] client session: stateChange:1->0 2F92EB85-432C-485C-AE1C-D018859FD29C:7
2016-03-31 10:16:26.525 ThaliTest[2559:4701257] client session: fireConnectCallb,ack: 2F92EB85-432C-485C-AE1C-D018859FD29C
2016-03-31 10:16:26.526 ThaliTest[2559:4701257] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-31 10:16:29.529 ThaliTest[2559:4700538] jxcore: connect 2F92EB85-432C-485C-AE1C-D018859FD29C:7
2016-03-31 10:16:29.529 ThaliTest[2559:4700538] client session: connect
2016-03-31 10:16:29.530 ThaliTest[2559:4700538] client session: stateChange:0->1 2F92EB85-432C-485C-AE1C-D018859FD29C:7
,2016-03-31 10:16:29.609 ThaliTest[2559:4701257] client session: not connected 2F92EB85-432C-485C-AE1C-D018859FD29C:7
2016-03-31 10:16:29.610 ThaliTest[2559:4701257] client session: onLinkFailure: 2F92EB85-432C-485C-AE1C-D018859FD29C
2016-03-31 10:16:29.610 ThaliTest[2559:4701257] client session: disconnect
2016-03-31 10:16:29.610 ThaliTest[2559:4701257] client session: stateChange:1->0 2F92EB85-432C-485C-AE1C-D018859FD29C:7
,2016-03-31 10:16:29.611 ThaliTest[2559:4701257] client session: fireConnectCallback: 2F92EB85-432C-485C-AE1C-D018859FD29C
,2016-03-31 10:16:29.611 ThaliTest[2559:4701257] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-31 10:16:32.618 ThaliTest[2559:4700538] jxcore: connect 2F92EB85-432C-485C-AE1C-D018859FD29C:7
2016-03-31 10:16:32.618 ThaliTest[2559:4700538] client session: connect
2016-03-31 10:16:32.618 ThaliTest[2559:4700538] client session: stateChange:0->,1 2F92EB85-432C-485C-AE1C-D018859FD29C:7
,2016-03-31 10:16:32.740 ThaliTest[2559:4701257] client session: not connected 2F92EB85-432C-485C-AE1C-D018859FD29C:7
2016-03-31 10:16:32.741 ThaliTest[2559:4701257] client session: onLinkFailure: 2F92EB85-432C-485C-AE1C-D018859FD29C
2016-03-31 10:16:32.7,41 ThaliTest[2559:4701257] client session: disconnect
2016-03-31 10:16:32.741 ThaliTest[2559:4701257] client session: stateChange:1->0 2F92EB85-432C-485C-AE1C-D018859FD29C:7
2016-03-31 10:16:32.741 ThaliTest[2559:4701257] client session: fireConnectCallb,ack: 2F92EB85-432C-485C-AE1C-D018859FD29C
2016-03-31 10:16:32.741 ThaliTest[2559:4701257] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-31 10:16:35.754 ThaliTest[2559:4700538] jxcore: connect 2F92EB85-432C-485C-AE1C-D018859FD29C:7
2016-03-31 10:16:35.754 ThaliTest[2559:4700538] client session: connect
2016-03-31 10:16:35.754 ThaliTest[2559:4700538] client session: stateChange:0->,1 2F92EB85-432C-485C-AE1C-D018859FD29C:7
,2016-03-31 10:16:35.876 ThaliTest[2559:4701262] client session: not connected 2F92EB85-432C-485C-AE1C-D018859FD29C:7
2016-03-31 10:16:35.877 ThaliTest[2559:4701262] client session: onLinkFailure: 2F92EB85-432C-485C-AE1C-D018859FD29C
2016-03-31 10:16:35.8,77 ThaliTest[2559:4701262] client session: disconnect
2016-03-31 10:16:35.878 ThaliTest[2559:4701262] client session: stateChange:1->0 2F92EB85-432C-485C-AE1C-D018859FD29C:7
2016-03-31 10:16:35.878 ThaliTest[2559:4701262] client session: fireConnectCallb,ack: 2F92EB85-432C-485C-AE1C-D018859FD29C
2016-03-31 10:16:35.878 ThaliTest[2559:4701262] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-31 10:16:38.745 ThaliTest[2559:4700406] multipeer manager: restart client
,2016-03-31 10:16:38.756 ThaliTest[2559:4700406] client: found updated peer: 2F92EB85-432C-485C-AE1C-D018859FD29C:8
2016-03-31 10:16:38.757 ThaliTest[2559:4700406] client: found updated peer: 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"2F92EB85-432C-485C-AE1C-D018859FD29C:8","pleaseConnect":0}]
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8","pleaseConnect":0}]
,2016-03-31 10:16:38.882 ThaliTest[2559:4700538] jxcore: connect 2F92EB85-432C-485C-AE1C-D018859FD29C:7
2016-03-31 10:16:38.882 ThaliTest[2559:4700538] client session: connect
2016-03-31 10:16:38.882 ThaliTest[2559:4700538] client session: stateChange:0->1 2F92EB85-432C-485C-AE1C-D018859FD29C:8
,2016-03-31 10:16:39.030 ThaliTest[2559:4701257] client session: not connected 2F92EB85-432C-485C-AE1C-D018859FD29C:8
,2016-03-31 10:16:39.031 ThaliTest[2559:4701257] client session: onLinkFailure: 2F92EB85-432C-485C-AE1C-D018859FD29C
2016-03-31 10:16:39.031 ThaliTest[2559:4701257] client session: disconnect
2016-03-31 10:16:39.031 ThaliTest[2559:4701257] client session: stateChange:1->0 2F92EB85-432C-485C-AE1C-D018859FD29C:8
2016-03-31 10:16:39.032 ThaliTest[2559:4701257] client session: fireConnectCallback: 2F92EB85-432C-485C-AE1C-D018859FD29C
2016-03-31 10:16:39.032 ThaliTest[2559:4701257] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-31 10:16:42.044 ThaliTest[2559:4700538] jxcore: connect 2F92EB85-432C-485C-AE1C-D018859FD29C:7
2016-03-31 10:16:42.044 ThaliTest[2559:4700538] client session: connect
2016-03-31 10:16:42.044 ThaliTest[2559:4700538] client session: stateChange:0->,1 2F92EB85-432C-485C-AE1C-D018859FD29C:8
,2016-03-31 10:16:42.177 ThaliTest[2559:4701322] client session: not connected 2F92EB85-432C-485C-AE1C-D018859FD29C:8
2016-03-31 10:16:42.177 ThaliTest[2559:4701322] client session: onLinkFailure: 2F92EB85-432C-485C-AE1C-D018859FD29C
2016-03-31 10:16:42.177 ThaliTest[2559:4701322] client session: disconnect
2016-03-31 10:16:42.177 ThaliTest[2559:4701322] client session: stateChange:1->0 2F92EB85-432C-485C-AE1C-D018859FD29C:8
2016-03-31 10:16:42.177 ThaliTest[2559:4701322] client session: fireConnectCallb,ack: 2F92EB85-432C-485C-AE1C-D018859FD29C
2016-03-31 10:16:42.177 ThaliTest[2559:4701322] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-31 10:16:45.192 ThaliTest[2559:4700538] jxcore: connect 2F92EB85-432C-485C-AE1C-D018859FD29C:7
2016-03-31 10:16:45.192 ThaliTest[2559:4700538] client session: connect
2016-03-31 10:16:45.192 ThaliTest[2559:4700538] client session: stateChange:0->,1 2F92EB85-432C-485C-AE1C-D018859FD29C:8
,2016-03-31 10:16:45.310 ThaliTest[2559:4701257] client session: not connected 2F92EB85-432C-485C-AE1C-D018859FD29C:8
2016-03-31 10:16:45.310 ThaliTest[2559:4701257] client session: onLinkFailure: 2F92EB85-432C-485C-AE1C-D018859FD29C
2016-03-31 10:16:45.310 ThaliTest[2559:4701257] client session: disconnect
2016-03-31 10:16:45.310 ThaliTest[2559:4701257] client session: stateChange:1->0 2F92EB85-432C-485C-AE1C-D018859FD29C:8
2016-03-31 10:16:45.310 ThaliTest[2559:4701257] client session: fireConnectCallback: 2F92EB85-432C-485C-AE1C-D018859FD29C
2016-03-31 10:16:45.311 ThaliTest[2559:4701257] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-31 10:16:48.317 ThaliTest[2559:4700538] jxcore: connect 2F92EB85-432C-485C-AE1C-D018859FD29C:7
2016-03-31 10:16:48.317 ThaliTest[2559:4700538] client session: connect
2016-03-31 10:16:48.317 ThaliTest[2559:4700538] client session: stateChange:0->1 2F92EB85-432C-485C-AE1C-D018859FD29C:8
,2016-03-31 10:16:48.514 ThaliTest[2559:4701258] client session: not connected 2F92EB85-432C-485C-AE1C-D018859FD29C:8
2016-03-31 10:16:48.515 ThaliTest[2559:4701258] client session: onLinkFailure: 2F92EB85-432C-485C-AE1C-D018859FD29C
2016-03-31 10:16:48.515 ThaliTest[2559:4701258] client session: disconnect
2016-03-31 10:16:48.515 ThaliTest[2559:4701258] client session: stateChange:1->0 2F92EB85-432C-485C-AE1C-D018859FD29C:8
2016-03-31 10:16:48.515 ThaliTest[2559:4701258] client session: fireConnectCallb,ack: 2F92EB85-432C-485C-AE1C-D018859FD29C
2016-03-31 10:16:48.515 ThaliTest[2559:4701258] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
WARN testThaliMobileNative: Too many connect retries!
,not ok 165 Connect failed!
  ---
,    operator: fail
,  ...
,# teardown
,2016-03-31 10:16:58.745 ThaliTest[2559:4700406] multipeer manager: restart client
,2016-03-31 10:16:58.755 ThaliTest[2559:4700406] client: found existing peer: 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8
2016-03-31 10:16:58.755 ThaliTest[2559:4700406] client: found existing peer: 2F92EB85-432C-485C-AE1C-D018859FD29C:8
,2016-03-31 10:17:18.745 ThaliTest[2559:4700406] multipeer manager: restart client
,2016-03-31 10:17:18.758 ThaliTest[2559:4700406] client: found existing peer: 2F92EB85-432C-485C-AE1C-D018859FD29C:8
2016-03-31 10:17:18.758 ThaliTest[2559:4700406] client: found existing peer: 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8
,2016-03-31 10:17:38.745 ThaliTest[2559:4700406] multipeer manager: restart client
,2016-03-31 10:17:38.757 ThaliTest[2559:4700406] client: found existing peer: 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8
2016-03-31 10:17:38.757 ThaliTest[2559:4700406] client: found existing peer: 2F92EB85-432C-485C-AE1C-D018859FD29C:8
,2016-03-31 10:17:58.745 ThaliTest[2559:4700406] multipeer manager: restart client
,2016-03-31 10:17:58.757 ThaliTest[2559:4700406] client: found existing peer: 2F92EB85-432C-485C-AE1C-D018859FD29C:8
2016-03-31 10:17:58.757 ThaliTest[2559:4700406] client: found existing peer: 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8
,2016-03-31 10:18:18.745 ThaliTest[2559:4700406] multipeer manager: restart client
,2016-03-31 10:18:18.755 ThaliTest[2559:4700406] client: found existing peer: 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8
,2016-03-31 10:18:18.756 ThaliTest[2559:4700406] client: found existing peer: 2F92EB85-432C-485C-AE1C-D018859FD29C:8
,2016-03-31 10:18:31.358 ThaliTest[2559:4700538] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-31 10:18:31.359 ThaliTest[2559:4700538] jxcore: stopListeningForAdvertisements: success
,ok 166 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-31 10:18:31.361 ThaliTest[2559:4700538] jxcore: stopAdvertisingAndListening
,2016-03-31 10:18:31.361 ThaliTest[2559:4700538] THEMultipeerManager stopping peer
,2016-03-31 10:18:31.361 ThaliTest[2559:4700538] multipeer manager: stop client timer
2016-03-31 10:18:31.361 ThaliTest[2559:4700538] jxcore: stopAdvertisingAndListening: success
ok 167 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 41. Can shift large amounts of data
,2016-03-31 10:18:31.758 ThaliTest[2559:4700538] jxcore: startUpdateAdvertisingAndListening
,2016-03-31 10:18:31.759 ThaliTest[2559:4700538] server: starting 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
,2016-03-31 10:18:31.760 ThaliTest[2559:4700538] multipeer manager: start client restart timer: 0x16ee8460
,2016-03-31 10:18:31.764 ThaliTest[2559:4700538] THEMultipeerManager initialized peer 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
,2016-03-31 10:18:31.765 ThaliTest[2559:4700538] jxcore: startUpdateAdvertisingAndListening: success
,ok 168 Can call startUpdateAdvertisingAndListening without error
,2016-03-31 10:18:31.767 ThaliTest[2559:4700538] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
,2016-03-31 10:18:31.768 ThaliTest[2559:4700538] jxcore: startListeningForAdvertisements: success
,ok 169 Can call startListeningForAdvertisements without error
,2016-03-31 10:18:32.472 ThaliTest[2559:4700406] client: found new peer: 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8
2016-03-31 10:18:32.473 ThaliTest[2559:4700538] jxcore: connect 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8
,2016-03-31 10:18:32.474 ThaliTest[2559:4700538] client: server will connect
2016-03-31 10:18:32.474 ThaliTest[2559:4700538] client session: reverseConnect
2016-03-31 10:18:32.474 ThaliTest[2559:4700538] client session: stateChange:0->1 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8
,2016-03-31 10:18:33.653 ThaliTest[2559:4700406] client: found new peer: 2F92EB85-432C-485C-AE1C-D018859FD29C:8
,2016-03-31 10:18:33.827 ThaliTest[2559:4701613] client session: not connected 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8
2016-03-31 10:18:33.828 ThaliTest[2559:4701613] client session: onLinkFailure: 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C
,2016-03-31 10:18:33.828 ThaliTest[2559:4701613] client session: disconnect
2016-03-31 10:18:33.829 ThaliTest[2559:4701613] client session: stateChange:1->0 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8
,2016-03-31 10:18:33.830 ThaliTest[2559:4701613] client session: no connect callback (server initiated)
,2016-03-31 10:18:33.888 ThaliTest[2559:4700406] multipeer session: reset timer
2016-03-31 10:18:33.888 ThaliTest[2559:4700406] server session: connect
2016-03-31 10:18:33.888 ThaliTest[2559:4700406] server session: stateChange:0->1 87D010AC-7D98-4E04-91F,C-9CBBC2D2DD5C:9
,2016-03-31 10:18:33.892 ThaliTest[2559:4700406] server: accepting invitation 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C
,2016-03-31 10:18:35.208 ThaliTest[2559:4700406] multipeer session: reset timer
2016-03-31 10:18:35.209 ThaliTest[2559:4700406] server: rejecting invitation from 2F92EB85-432C-485C-AE1C-D018859FD29C due to previous generation (3F6A8788-1777-4148-9D5D-A7C86,08DD267:9 != 3F6A8788-1777-4148-9D5D-A7C8608DD267:8)
,2016-03-31 10:18:36.324 ThaliTest[2559:4701613] server session: p2p link connected
,2016-03-31 10:18:36.337 ThaliTest[2559:4700406] server relay: connected (to port: 56645)
2016-03-31 10:18:36.338 ThaliTest[2559:4700406] server session: stateChange:1->2 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:9
2016-03-31 10:18:36.338 ThaliTest[2559:4700406] jxcore: connect: success
INFO testThaliMobileNative: 
INFO testThaliMobileNative: Reverse connection
,INFO testThaliMobileNative: reverseData
INFO testThaliMobileNative: reverseSend
,INFO testThaliMobileNative: reverseData
ok 170 received should match sent reverse
,# teardown
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,2016-03-31 10:18:46.866 ThaliTest[2559:4700406] multipeer session: reset timer
2016-03-31 10:18:46.866 ThaliTest[2559:4700406] server: disconnecting to refresh session (2F92EB85-432C-485C-AE1C-D018859FD29C)
2016-03-31 10:18:46.867 ThaliTest[2559:4700406], server: rejecting invitation from 2F92EB85-432C-485C-AE1C-D018859FD29C due to previous generation (3F6A8788-1777-4148-9D5D-A7C8608DD267:9 != 3F6A8788-1777-4148-9D5D-A7C8608DD267:8)
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,2016-03-31 10:18:51.765 ThaliTest[2559:4700406] multipeer manager: restart client
,2016-03-31 10:18:51.779 ThaliTest[2559:4700406] client: found existing peer: 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8
2016-03-31 10:18:51.780 ThaliTest[2559:4700406] client: found updated peer: 2F92EB85-432C-485C-AE1C-D018859FD29C:9
INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,2016-03-31 10:18:59.949 ThaliTest[2559:4700406] multipeer session: reset timer
INFO testThaliMobileNative: reverseData
2016-03-31 10:18:59.949 ThaliTest[2559:4700406] server: disconnecting to refresh session (2F92EB85-432C-485C-AE1C-D018859FD29C)
,2016-03-31 10:18:59.949 ThaliTest[2559:4700406] server: rejecting invitation from 2F92EB85-432C-485C-AE1C-D018859FD29C due to previous generation (3F6A8788-1777-4148-9D5D-A7C8608DD267:9 != 3F6A8788-1777-4148-9D5D-A7C8608DD267:8)
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,2016-03-31 10:19:11.765 ThaliTest[2559:4700406] multipeer manager: restart client
,INFO testThaliMobileNative: reverseData
,2016-03-31 10:19:11.783 ThaliTest[2559:4700406] client: found existing peer: 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8
2016-03-31 10:19:11.783 ThaliTest[2559:4700406] client: found existing peer: 2F92EB85-432C-485C-AE1C-D018859FD29C:9
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,2016-03-31 10:19:13.832 ThaliTest[2559:4700406] multipeer session: reset timer
,2016-03-31 10:19:13.832 ThaliTest[2559:4700406] server: disconnecting to refresh session (2F92EB85-432C-485C-AE1C-D018859FD29C)
2016-03-31 10:19:13.832 ThaliTest[2559:4700406] server: rejecting invitation from 2F92EB85-432C-485C-AE1C-D018859FD29C due to previous generation (3F6A8788-1777-4148-9D5D-A7C8608DD267:9 != 3F6A8788-1777-4148-9D5D-A7C8608DD267:8)
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,2016-03-31 10:19:25.957 ThaliTest[2559:4700406] multipeer session: reset timer
2016-03-31 10:19:25.957 ThaliTest[2559:4700406] server: disconnecting to refresh session (2F92EB85-432C-485C-AE1C-D018859FD29C)
2016-03-31 10:19:25.957 ThaliTest[2559:4700406] server: rejecting invitation from 2F92EB85-432C-485C-AE1C-D018859FD29C due to previous generation (3F6A8788-1777-4148-9D5D-A7C8608DD267:9 != 3F6A8788-1777-4148-9D5D-A7C8608DD267:8)
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
2016-03-31 10:19:31.765 ThaliTest[2559:4700406] multipeer manager: restart client
,2016-03-31 10:19:31.782 ThaliTest[2559:4700406] client: found existing peer: 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8
2016-03-31 10:19:31.783 ThaliTest[2559:4700406] client: found existing peer: 2F92EB85-432C-485C-AE1C-D018859FD29C:9
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,2016-03-31 10:19:39.146 ThaliTest[2559:4700406] multipeer session: reset timer
2016-03-31 10:19:39.146 ThaliTest[2559:4700406] server: disconnecting to refresh session (2F92EB85-432C-485C-AE1C-D018859FD29C)
,2016-03-31 10:19:39.146 ThaliTest[2559:4700406] server: rejecting invitation from 2F92EB85-432C-485C-AE1C-D018859FD29C due to previous generation (3F6A8788-1777-4148-9D5D-A7C8608DD267:9 != 3F6A8788-1777-4148-9D5D-A7C8608DD267:8)
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,2016-03-31 10:19:51.765 ThaliTest[2559:4700406] multipeer manager: restart client
,2016-03-31 10:19:51.778 ThaliTest[2559:4700406] client: found existing peer: 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8
2016-03-31 10:19:51.778 ThaliTest[2559:4700406] client: found existing peer: 2F92EB85-432C-485C-AE1C-D018859FD29C:9
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,2016-03-31 10:19:52.002 ThaliTest[2559:4700406] multipeer session: reset timer
2016-03-31 10:19:52.002 ThaliTest[2559:4700406] server: disconnecting to refresh session (2F92EB85-432C-485C-AE1C-D018859FD29C)
2016-03-31 10:19:52.003 ThaliTest[2559:4700406], server: rejecting invitation from 2F92EB85-432C-485C-AE1C-D018859FD29C due to previous generation (3F6A8788-1777-4148-9D5D-A7C8608DD267:9 != 3F6A8788-1777-4148-9D5D-A7C8608DD267:8)
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,2016-03-31 10:20:05.030 ThaliTest[2559:4700406] multipeer session: reset timer
2016-03-31 10:20:05.030 ThaliTest[2559:4700406] server: disconnecting to refresh session (2F92EB85-432C-485C-AE1C-D018859FD29C)
2016-03-31 10:20:05.031 ThaliTest[2559:4700406] server: rejecting invitation from 2F92EB85-432C-485C-AE1C-D018859FD29C due to previous generation (3F6A8788-1777-4148-9D5D-A7C8608DD267:9 != 3F6A8788-1777-4148-9D5D-A7C8608DD267:8)
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,2016-03-31 10:20:11.765 ThaliTest[2559:4700406] multipeer manager: restart client
,2016-03-31 10:20:11.779 ThaliTest[2559:4700406] client: found existing peer: 2F92EB85-432C-485C-AE1C-D018859FD29C:9
2016-03-31 10:20:11.779 ThaliTest[2559:4700406] client: found existing peer: 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,2016-03-31 10:20:18.073 ThaliTest[2559:4700406] multipeer session: reset timer
2016-03-31 10:20:18.073 ThaliTest[2559:4700406] server: disconnecting to refresh session (2F92EB85-432C-485C-AE1C-D018859FD29C)
2016-03-31 10:20:18.073 ThaliTest[2559:4700406] server: rejecting invitation from 2F92EB85-432C-485C-AE1C-D018859FD29C due to previous generation (3F6A8788-1777-4148-9D5D-A7C8608DD267:9 != 3F6A8788-1777-4148-9D5D-A7C8608DD267:8)
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,2016-03-31 10:20:31.049 ThaliTest[2559:4700406] multipeer session: reset timer
2016-03-31 10:20:31.049 ThaliTest[2559:4700406] server: disconnecting to refresh session (2F92EB85-432C-485C-AE1C-D018859FD29C)
2016-03-31 10:20:31.049 ThaliTest[2559:4700406] server: rejecting invitation from 2F92EB85-432C-485C-AE1C-D018859FD29C due to previous generation (3F6A8788-1777-4148-9D5D-A7C8608DD267:9 != 3F6A8788-1777-4148-9D5D-A7C8608DD267:8)
INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,2016-03-31 10:20:31.764 ThaliTest[2559:4700406] multipeer manager: restart client
,INFO testThaliMobileNative: reverseData
,2016-03-31 10:20:31.781 ThaliTest[2559:4700406] client: found existing peer: 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8
,2016-03-31 10:20:31.783 ThaliTest[2559:4700406] client: found existing peer: 2F92EB85-432C-485C-AE1C-D018859FD29C:9
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,2016-03-31 10:20:41.009 ThaliTest[2559:4700538] jxcore: stopListeningForAdvertisements
2016-03-31 10:20:41.010 ThaliTest[2559:4700406] server relay: socket disconnected
2016-03-31 10:20:41.010 ThaliTest[2559:4700406] server relay: 0x188b42e0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"disc,overyActive":false}
2016-03-31 10:20:41.011 ThaliTest[2559:4700538] jxcore: stopListeningForAdvertisements: success
ok 171 Should be able to call stopListeningForAdvertisments in teardown
2016-03-31 10:20:41.012 ThaliTest[2559:4700538] jxcore: stopAdvertisingAndListening
2016-03-31 10:20:41.012 ThaliTest[2559:4700538] THEMultipeerManager stopping peer
2016-03-31 10:20:41.012 ThaliTest[2559:4700538] server session: disconnect
2016-03-31 10:20:41.012 ThaliTest[2559:4700538] server session: stateChange:2,->0 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:9
,2016-03-31 10:20:41.020 ThaliTest[2559:4700538] multipeer manager: stop client timer
2016-03-31 10:20:41.021 ThaliTest[2559:4700538] jxcore: stopAdvertisingAndListening: success
ok 172 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2016-03-31 10:20:41.727 ThaliTest[2559:4700538] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-31 10:20:41.727 ThaliTest[2559:4700538] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-31 10:20:41.727 ThaliTest[2559:4700538] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-31 10:20:41.729 ThaliTest[2559:4700538] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 42. #startListeningForAdvertisements should fail if start not called
,ok 173 specific error should be returned
,# teardown
,ok 174 must be stopped
,# setup
,2016-03-31 10:20:44.789 ThaliTest[2559:4700538] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-31 10:20:44.790 ThaliTest[2559:4700538] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-31 10:20:44.790 ThaliTest[2559:4700538] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-31 10:20:44.791 ThaliTest[2559:4700538] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 43. #startUpdateAdvertisingAndListening should fail if start not called
,ok 175 specific error should be returned
# teardown
,ok 176 must be stopped
,# setup
,2016-03-31 10:20:45.818 ThaliTest[2559:4700538] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-31 10:20:45.819 ThaliTest[2559:4700538] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-31 10:20:45.819 ThaliTest[2559:4,700538] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-31 10:20:45.820 ThaliTest[2559:4700538] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 44. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 56654
2016-03-31 10:20:47.469 ThaliTest[2559:4700538] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 10:20:47.470 ThaliTest[2559:4700538] jxcore: stopListeningForAdvertisements: success
ok 177 no errors
,2016-03-31 10:20:47.471 ThaliTest[2559:4700538] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 10:20:47.472 ThaliTest[2559:4700538] jxcore: stopListeningForAdvertisements: success
ok 178 still no errors
# teardown
,2016-03-31 10:20:48.147 ThaliTest[2559:4700538] jxcore: stopAdvertisingAndListening
2016-03-31 10:20:48.147 ThaliTest[2559:4700538] THEMultipeerManager stopping peer
2016-03-31 10:20:48.147 ThaliTest[2559:4700538] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-31 10:20:48.147 ThaliTest[2559:4700538] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 10:20:48.148 ThaliTest[2559:4700538] jxcore: stopListeningForAdvertisements: success
ok 179 must be stopped
# setup
,2016-03-31 10:20:48.336 ThaliTest[2559:4700538] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-31 10:20:48.337 ThaliTest[2559:4700538] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-31 10:20:48.337 ThaliTest[2559:4,700538] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-31 10:20:48.338 ThaliTest[2559:4700538] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
# 45. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 56656
,2016-03-31 10:20:59.163 ThaliTest[2559:4700538] jxcore: startListeningForAdvertisements
2016-03-31 10:20:59.163 ThaliTest[2559:4700538] multipeer manager: start client restart timer: 0x16ee8460
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-31 10:20:59.164 ThaliTest[2559:4700538] jxcore: startListeningForAdvertisements: success
,2016-03-31 10:20:59.171 ThaliTest[2559:4700406] client: found new peer: 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8
ok 180 no errors
,2016-03-31 10:20:59.173 ThaliTest[2559:4700538] jxcore: startListeningForAdvertisements

```
