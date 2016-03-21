#### Test 625481246894564_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/625481246894564/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/58F48CDB-569F-4A5F-BCD6-D29760B7B2A4/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/58F48CDB-569F-4A5F-BCD6-D29760B7B2A4/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/625481246894564/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/625481246894564/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/4F30679D-ADD2-4890-AF0B-A25FBEAE6E10/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54166"
,(lldb)     command script import "/tmp/58F48CDB-569F-4A5F-BCD6-D29760B7B2A4/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-21 13:02:13.390 ThaliTest[1875:3186576] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0723A517-633A-4343-A78F-D7FB0E45CD1C/Library/Cookies/Cookies.binarycookies
,2016-03-21 13:02:13.805 ThaliTest[1875:3186576] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-21 13:02:13.806 ThaliTest[1875:3186576] Multi-tasking -> Device: YES, App: YES
,2016-03-21 13:02:13.830 ThaliTest[1875:3186576] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-21 13:02:15.723 ThaliTest[1875:3186576] Using UIWebView
,2016-03-21 13:02:15.733 ThaliTest[1875:3186576] [CDVTimer][handleopenurl] 0.537992ms
,2016-03-21 13:02:15.741 ThaliTest[1875:3186576] [CDVTimer][intentandnavigationfilter] 7.256985ms
2016-03-21 13:02:15.742 ThaliTest[1875:3186576] [CDVTimer][gesturehandler] 0.347018ms
2016-03-21 13:02:15.742 ThaliTest[1875:3186576] [CDVTimer][TotalPluginStartup] 9.838998ms
,2016-03-21 13:02:22.503 ThaliTest[1875:3186576] Resetting plugins due to page load.
,2016-03-21 13:02:25.955 ThaliTest[1875:3186576] Finished load of: file:///var/mobile/Containers/Bundle/Application/4F30679D-ADD2-4890-AF0B-A25FBEAE6E10/ThaliTest.app/www/index.html
,2016-03-21 13:02:26.179 ThaliTest[1875:3186576] JXcore Cordova plugin initializing
,2016-03-21 13:02:26.180 ThaliTest[1875:3186771] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-21 13:02:33.407 ThaliTest[1875:3186771] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-21 13:02:33.408 ThaliTest[1875:3186771] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-21 13:02:33.408 ThaliTest[1875:3,186771] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-21 13:02:33.410 ThaliTest[1875:3186771] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone6-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4F30679D-ADD2-4890-AF0B-A25FBEAE6E10/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4F30679D-ADD2-4890-AF0B-A25FBEAE6E10/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4F30679D-ADD2-4890-AF0B-A25FBEAE6E10/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4F30679D-ADD2-4890-AF0B-A25FBEAE6E10/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4F30679D-ADD2-4890-AF0B-A25FBEAE6E10/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4F30679D-ADD2-4890-AF0B-A25FBEAE6E10/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4F30679D-ADD2-4890-AF0B-A25FBEAE6E10/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4F30679D-ADD2-4890-AF0B-A25FBEAE6E10/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4F30679D-ADD2-4890-AF0B-A25FBEAE6E10/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4F30679D-ADD2-4890-AF0B-A25FBEAE6E10/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4F30679D-ADD2-4890-AF0B-A25FBEAE6E10/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4F30679D-ADD2-4890-AF0B-A25FBEAE6E10/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4F30679D-ADD2-4890-AF0B-A25FBEAE6E10/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4F30679D-ADD2-4890-AF0B-A25FBEAE6E10/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4F30679D-ADD2-4890-AF0B-A25FBEAE6E10/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4F30679D-ADD2-4890-AF0B-A25FBEAE6E10/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4F30679D-ADD2-4890-AF0B-A25FBEAE6E10/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4F30679D-ADD2-4890-AF0B-A25FBEAE6E10/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4F30679D-ADD2-4890-AF0B-A25FBEAE6E10/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4F30679D-ADD2-4890-AF0B-A25FBEAE6E10/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-21 13:02:39.257 ThaliTest[1875:3186576] THREAD WARNING: ['JXcore'] took '5535.791260' ms. Plugin should use a background thread.
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49195
,ok 1 Should throw
,# setup
,# 2. emits incomingConnectionState
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49197
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,ok 2 initial connection state should be CONNECTED
,DEBUG createNativeListener: incoming socket close
,ok 3 final connection state should be DISCONNECTED
,# setup
,# 3. emits routerPortConnectionFailed
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49200
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: 
,ok 4 tried to connect to right port
,ok 5 failed due to refused connection
,ok 6 routerPortConnectionFailed is emitted
,# setup
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,# 4. native server connections all up
,DEBUG createNativeListener: incoming socket close
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49205
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
,# setup
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,# 5. native server - closing incoming stream cleans outgoing socket
,DEBUG createNativeListener: incoming socket close
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49210
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,ok 12 socket shouldn't close until after stream
,ok 13 incoming remains open
,# setup
,DEBUG createNativeListener: mux close
,# 6. native server - closing incoming connection cleans outgoing socket
,DEBUG createNativeListener: incoming socket close
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49215
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
,# setup
,# 7. native server - closing outgoing socket cleans associated mux stream
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49219
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,ok 17 stream was closed
,ok 18 incoming should survive
,ok 19 mux should have no streams
,# setup
,DEBUG createNativeListener: mux close
,# 8. native server - closing the whole server cleans everything up
,DEBUG createNativeListener: incoming socket close
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49223
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
,# setup
,# 9. native server - we can get a ton of connections and data through and still clean up the server completely
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49227
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
,# setup
,# 10. native server - simulate mux failure, make sure everything is cleaned up
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49279
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
,# setup
,# 11. native server - timing out the incoming connection cleans everything up
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49283
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
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49295
,2016-03-21 13:04:33.326 ThaliTest[1875:3186771] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 13:04:33.329 ThaliTest[1875:3186771] jxcore: stopListeningForAdvertisements: success
,ok 82 error should be null
,ok 83 error should be null
,2016-03-21 13:04:33.335 ThaliTest[1875:3186771] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 13:04:33.337 ThaliTest[1875:3186771] jxcore: stopListeningForAdvertisements: success
,ok 84 error should be null
,ok 85 error should be null
,# setup
,2016-03-21 13:04:33.441 ThaliTest[1875:3186771] jxcore: stopAdvertisingAndListening
2016-03-21 13:04:33.442 ThaliTest[1875:3186771] THEMultipeerManager stopping peer
2016-03-21 13:04:33.442 ThaliTest[1875:3186771] jxcore: stopAdvertisingAndListening: success
,2016-03-21 13:04:33.444 ThaliTest[1875:3186771] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 13:04:33.446 ThaliTest[1875:3186771] jxcore: stopListeningForAdvertisements: success
,ok 86 error should be null
,ok 87 error should be null
,# 24. should be able to call #startListeningForAdvertisements many times
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49297
,2016-03-21 13:04:33.732 ThaliTest[1875:3186771] jxcore: startListeningForAdvertisements
,2016-03-21 13:04:33.735 ThaliTest[1875:3186771] multipeer manager: start client restart timer: 0x155c4fc0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-21 13:04:33.738 ThaliTest[1875:3186771] jxcore: startListeningForAdvertisements: success
,ok 88 error should be null
,ok 89 error should be null
,2016-03-21 13:04:33.765 ThaliTest[1875:3186771] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-21 13:04:33.768 ThaliTest[1875:3186771] jxcore: startListeningForAdvertisements: success
,ok 90 error should be null
,ok 91 error should be null
,# setup
,2016-03-21 13:04:34.052 ThaliTest[1875:3186771] jxcore: stopAdvertisingAndListening
2016-03-21 13:04:34.052 ThaliTest[1875:3186771] THEMultipeerManager stopping peer
2016-03-21 13:04:34.053 ThaliTest[1875:3186771] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-21 13:04:34.053 ThaliTest[1875:3186771] jxcore: stopListeningForAdvertisements
2016-03-21 13:04:34.054 ThaliTest[1875:3186771] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-21 13:04:34.058 ThaliTest[1875:3186771] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 92 error should be null
,ok 93 error should be null
,# 25. should be able to call #startUpdateAdvertisingAndListening many times
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49299
,2016-03-21 13:04:34.640 ThaliTest[1875:3186771] jxcore: startUpdateAdvertisingAndListening
2016-03-21 13:04:34.641 ThaliTest[1875:3186771] server: starting FE8F9526-AD74-40E1-9080-FD7FA9CC9893:1
2016-03-21 13:04:34.642 ThaliTest[1875:3186771] multipeer m,anager: start client restart timer: 0x155c4fc0
2016-03-21 13:04:34.643 ThaliTest[1875:3186771] THEMultipeerManager initialized peer FE8F9526-AD74-40E1-9080-FD7FA9CC9893:1
2016-03-21 13:04:34.643 ThaliTest[1875:3186771] jxcore: startUpdateAdvertisingAndLi,stening: success
,ok 94 error should be null
ok 95 error should be null
,2016-03-21 13:04:34.665 ThaliTest[1875:3186771] jxcore: startUpdateAdvertisingAndListening
2016-03-21 13:04:34.666 ThaliTest[1875:3186771] THEMultipeerManager stopping peer
2016-03-21 13:04:34.667 ThaliTest[1875:3186771] multipeer manager: stop client ti,mer
2016-03-21 13:04:34.667 ThaliTest[1875:3186771] server: starting FE8F9526-AD74-40E1-9080-FD7FA9CC9893:2
2016-03-21 13:04:34.668 ThaliTest[1875:3186771] multipeer manager: start client restart timer: 0x155c4fc0
2016-03-21 13:04:34.669 ThaliTest[1875:,3186771] THEMultipeerManager initialized peer FE8F9526-AD74-40E1-9080-FD7FA9CC9893:2
2016-03-21 13:04:34.669 ThaliTest[1875:3186771] jxcore: startUpdateAdvertisingAndListening: success
,ok 96 error should be null
,ok 97 error should be null
,# setup
,2016-03-21 13:04:35.145 ThaliTest[1875:3186771] jxcore: stopAdvertisingAndListening
2016-03-21 13:04:35.146 ThaliTest[1875:3186771] THEMultipeerManager stopping peer
,2016-03-21 13:04:35.146 ThaliTest[1875:3186771] multipeer manager: stop client timer
2016-03-21 13:04:35.148 ThaliTest[1875:3186771] jxcore: stopAdvertisingAndListening: success
2016-03-21 13:04:35.149 ThaliTest[1875:3186771] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-21 13:04:35.152 ThaliTest[1875:3186771] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 98 error should be null
,ok 99 error should be null
,# 26. should be able to call #stopAdvertisingAndListening many times
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49304
,2016-03-21 13:04:35.576 ThaliTest[1875:3186771] jxcore: stopAdvertisingAndListening
2016-03-21 13:04:35.577 ThaliTest[1875:3186771] THEMultipeerManager stopping peer
2016-03-21 13:04:35.577 ThaliTest[1875:3186771] jxcore: stopAdvertisingAndListening: success
,ok 100 error should be null
,ok 101 error should be null
,2016-03-21 13:04:35.585 ThaliTest[1875:3186771] jxcore: stopAdvertisingAndListening
2016-03-21 13:04:35.585 ThaliTest[1875:3186771] THEMultipeerManager stopping peer
2016-03-21 13:04:35.585 ThaliTest[1875:3186771] jxcore: stopAdvertisingAndListening: success
ok 102 error should be null
,ok 103 error should be null
,# setup
,2016-03-21 13:04:35.702 ThaliTest[1875:3186771] jxcore: stopAdvertisingAndListening
2016-03-21 13:04:35.702 ThaliTest[1875:3186771] THEMultipeerManager stopping peer
2016-03-21 13:04:35.703 ThaliTest[1875:3186771] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-21 13:04:35.703 ThaliTest[1875:3186771] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 13:04:35.706 ThaliTest[1875:3186771] jxcore: stopListeningForAdvertisements: success
,ok 104 error should be null
,ok 105 error should be null
,# 27. #start should fail if called twice in a row
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49306
,ok 106 first call should succeed
,ok 107 first call should succeed
,ok 108 specific error should be returned
,# setup
,2016-03-21 13:04:36.324 ThaliTest[1875:3186771] jxcore: stopAdvertisingAndListening
2016-03-21 13:04:36.324 ThaliTest[1875:3186771] THEMultipeerManager stopping peer
2016-03-21 13:04:36.324 ThaliTest[1875:3186771] jxcore: stopAdvertisingAndListening: success
2016-03-21 13:04:36.325 ThaliTest[1875:3186771] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 13:04:36.329 ThaliTest[1875:3186771] jxcore: stopListeningForAdvertisements: success
,ok 109 error should be null
,ok 110 error should be null
,# 28. does not emit duplicate discoveryAdvertisingStateUpdate
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49308
,2016-03-21 13:04:37.087 ThaliTest[1875:3186771] jxcore: startListeningForAdvertisements
2016-03-21 13:04:37.088 ThaliTest[1875:3186771] multipeer manager: start client restart timer: 0x155c4fc0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-21 13:04:37.091 ThaliTest[1875:3186771] jxcore: startListeningForAdvertisements: success
,2016-03-21 13:04:37.114 ThaliTest[1875:3186771] jxcore: startUpdateAdvertisingAndListening
,2016-03-21 13:04:37.115 ThaliTest[1875:3186771] server: starting FE8F9526-AD74-40E1-9080-FD7FA9CC9893:3
,2016-03-21 13:04:37.117 ThaliTest[1875:3186771] THEMultipeerManager initialized peer FE8F9526-AD74-40E1-9080-FD7FA9CC9893:3
,2016-03-21 13:04:37.122 ThaliTest[1875:3186771] jxcore: startUpdateAdvertisingAndListening: success
,ok 111 called only once
,ok 112 discovery state matches
,ok 113 advertising state matches
,# setup
,2016-03-21 13:04:37.285 ThaliTest[1875:3186771] jxcore: stopAdvertisingAndListening
,2016-03-21 13:04:37.287 ThaliTest[1875:3186771] THEMultipeerManager stopping peer
,2016-03-21 13:04:37.288 ThaliTest[1875:3186771] jxcore: stopAdvertisingAndListening: success
,2016-03-21 13:04:37.291 ThaliTest[1875:3186771] jxcore: stopListeningForAdvertisements
,2016-03-21 13:04:37.293 ThaliTest[1875:3186771] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 13:04:37.299 ThaliTest[1875:3186771] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
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
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
,ok 123 host address should match
,ok 124 port should match
,ok 125 host address should be null
,ok 126 port should should be null
,# setup
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 127 error should be null
,ok 128 error should be null
,# 32. Can call start/stopListeningForAdvertisements
,# teardown
,2016-03-21 13:04:42.253 ThaliTest[1875:3186771] jxcore: startListeningForAdvertisements
2016-03-21 13:04:42.253 ThaliTest[1875:3186771] multipeer manager: start client restart timer: 0x155c4fc0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-21 13:04:42.256 ThaliTest[1875:3186771] jxcore: startListeningForAdvertisements: success
,ok 129 Can call startListeningForAdvertisements without error
2016-03-21 13:04:42.260 ThaliTest[1875:3186771] jxcore: stopListeningForAdvertisements
2016-03-21 13:04:42.265 ThaliTest[1875:3186771] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-21 13:04:42.267 ThaliTest[1875:3186771] jxcore: stopListeningForAdvertisements: success
ok 130 Can call stopListeningForAdvertisements without error
,# setup
,2016-03-21 13:04:42.563 ThaliTest[1875:3186771] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 13:04:42.565 ThaliTest[1875:3186771] jxcore: stopListeningForAdvertisements: success
,ok 131 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-21 13:04:42.568 ThaliTest[1875:3186771] jxcore: stopAdvertisingAndListening
2016-03-21 13:04:42.568 ThaliTest[1875:3186771] THEMultipeerManager stopping peer
2016-03-21 13:04:42.568 ThaliTest[1875:3186771] jxcore: stopAdvertisingAndListening: success
ok 132 Should be able to call stopAdvertisingAndListening in teardown
,# 33. Calling startListeningForAdvertisements twice is NOT an error
,# teardown
,2016-03-21 13:04:43.021 ThaliTest[1875:3186771] jxcore: startListeningForAdvertisements
2016-03-21 13:04:43.021 ThaliTest[1875:3186771] multipeer manager: start client restart timer: 0x155c4fc0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-21 13:04:43.024 ThaliTest[1875:3186771] jxcore: startListeningForAdvertisements: success
,ok 133 Can call startListeningForAdvertisements without error
2016-03-21 13:04:43.028 ThaliTest[1875:3186771] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-21 13:04:43.030 ThaliTest[1875:3186771] jxcore: startListeningForAdvertisements: success
,ok 134 Can call startListeningForAdvertisements twice without error
,# setup
,2016-03-21 13:04:43.143 ThaliTest[1875:3186771] jxcore: stopListeningForAdvertisements
2016-03-21 13:04:43.144 ThaliTest[1875:3186771] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 13:04:43.145 ThaliTest[1875:3186771] jxcore: stopListeningForAdvertisements: success
,ok 135 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-21 13:04:43.150 ThaliTest[1875:3186771] jxcore: stopAdvertisingAndListening
2016-03-21 13:04:43.150 ThaliTest[1875:3186771] THEMultipeerManager stopping peer
2016-03-21 13:04:43.150 ThaliTest[1875:3186771] jxcore: stopAdvertisingAndListening: suc,cess
ok 136 Should be able to call stopAdvertisingAndListening in teardown
# 34. Can call start/stopUpdateAdvertisingAndListening
,# teardown
,2016-03-21 13:04:45.611 ThaliTest[1875:3186771] jxcore: startUpdateAdvertisingAndListening
2016-03-21 13:04:45.612 ThaliTest[1875:3186771] server: starting FE8F9526-AD74-40E1-9080-FD7FA9CC9893:4
2016-03-21 13:04:45.612 ThaliTest[1875:3186771] multipeer m,anager: start client restart timer: 0x155c4fc0
2016-03-21 13:04:45.613 ThaliTest[1875:3186771] THEMultipeerManager initialized peer FE8F9526-AD74-40E1-9080-FD7FA9CC9893:4
2016-03-21 13:04:45.613 ThaliTest[1875:3186771] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 137 Can call startUpdateAdvertisingAndListening without error
2016-03-21 13:04:45.615 ThaliTest[1875:3186771] jxcore: stopAdvertisingAndListening
2016-03-21 13:04:45.616 ThaliTest[1875:3186771] THEMultipeerManager stopping peer
2016,-03-21 13:04:45.617 ThaliTest[1875:3186771] multipeer manager: stop client timer
,2016-03-21 13:04:45.617 ThaliTest[1875:3186771] jxcore: stopAdvertisingAndListening: success
,ok 138 Can call stopAdvertisingAndListening without error
# setup
,2016-03-21 13:04:46.242 ThaliTest[1875:3186771] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 13:04:46.245 ThaliTest[1875:3186771] jxcore: stopListeningForAdvertisements: success
ok 139 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-21 13:04:46.248 ThaliTest[1875:3186771] jxcore: stopAdvertisingAndListening
2016-03-21 13:04:46.248 ThaliTest[1875:3186771] THEMultipeerManager stopping peer
2016-03-21 13:04:46.249 ThaliTest[1875:3186771] jxcore: stopAdvertisingAndListening: suc,cess
ok 140 Should be able to call stopAdvertisingAndListening in teardown
,# 35. Calling startUpdateAdvertisingAndListening twice is NOT an error
,# teardown
,2016-03-21 13:04:46.645 ThaliTest[1875:3186771] jxcore: startUpdateAdvertisingAndListening
2016-03-21 13:04:46.645 ThaliTest[1875:3186771] server: starting FE8F9526-AD74-40E1-9080-FD7FA9CC9893:5
2016-03-21 13:04:46.646 ThaliTest[1875:3186771] multipeer manager: start client restart timer: 0x155c4fc0
2016-03-21 13:04:46.646 ThaliTest[1875:3186771] THEMultipeerManager initialized peer FE8F9526-AD74-40E1-9080-FD7FA9CC9893:5
2016-03-21 13:04:46.647 ThaliTest[1875:3186771] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 141 Can call startUpdateAdvertisingAndListening without error
2016-03-21 13:04:46.649 ThaliTest[1875:3186771] jxcore: startUpdateAdvertisingAndListening
2016-03-21 13:04:46.650 ThaliTest[1875:3186771] THEMultipeerManager stopping pee,r
2016-03-21 13:04:46.650 ThaliTest[1875:3186771] multipeer manager: stop client timer
2016-03-21 13:04:46.650 ThaliTest[1875:3186771] server: starting FE8F9526-AD74-40E1-9080-FD7FA9CC9893:6
2016-03-21 13:04:46.651 ThaliTest[1875:3186771] multipeer mana,ger: start client restart timer: 0x155c4fc0
,2016-03-21 13:04:46.657 ThaliTest[1875:3186771] THEMultipeerManager initialized peer FE8F9526-AD74-40E1-9080-FD7FA9CC9893:6
2016-03-21 13:04:46.658 ThaliTest[1875:3186771] jxcore: startUpdateAdvertisingAndListening: success
ok 142 Can call startUpdateAdvertisingAndListening twice without error
# setup
,2016-03-21 13:04:46.751 ThaliTest[1875:3186771] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-21 13:04:46.753 ThaliTest[1875:3186771] jxcore: stopListeningForAdvertisements: success
,ok 143 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-21 13:04:46.756 ThaliTest[1875:3186771] jxcore: stopAdvertisingAndListening
2016-03-21 13:04:46.756 ThaliTest[1875:3186771] THEMultipeerManager stopping peer
2016-03-21 13:04:46.757 ThaliTest[1875:3186771] multipeer manager: stop client timer
20,16-03-21 13:04:46.757 ThaliTest[1875:3186771] jxcore: stopAdvertisingAndListening: success
ok 144 Should be able to call stopAdvertisingAndListening in teardown
,# 36. peerAvailabilityChange is called
,# teardown
,2016-03-21 13:04:49.726 ThaliTest[1875:3186771] jxcore: startUpdateAdvertisingAndListening
2016-03-21 13:04:49.726 ThaliTest[1875:3186771] server: starting FE8F9526-AD74-40E1-9080-FD7FA9CC9893:7
2016-03-21 13:04:49.727 ThaliTest[1875:3186771] multipeer m,anager: start client restart timer: 0x155c4fc0
2016-03-21 13:04:49.728 ThaliTest[1875:3186771] THEMultipeerManager initialized peer FE8F9526-AD74-40E1-9080-FD7FA9CC9893:7
2016-03-21 13:04:49.728 ThaliTest[1875:3186771] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 145 Can call startUpdateAdvertisingAndListeningwithout error
2016-03-21 13:04:49.730 ThaliTest[1875:3186771] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-21 13:04:49.735 ThaliTest[1875:3186771] jxcore: startListeningForAdvertisements: success
,ok 146 Can call startListeningForAdvertisements without error
,2016-03-21 13:04:50.833 ThaliTest[1875:3186576] client: found new peer: ACF08CBB-018B-4F78-A189-81A63854F007:7
,ok 147 peers must be an array
,ok 148 peers must not be zero-length
,ok 149 peer must have peerIdentifier
,ok 150 peerIdentifier must be a string
,ok 151 peer must have peerAvailable
,ok 152 peer must have pleaseConnect
,# setup
,2016-03-21 13:04:52.305 ThaliTest[1875:3186771] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-21 13:04:52.307 ThaliTest[1875:3186771] jxcore: stopListeningForAdvertisements: success
,ok 153 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-21 13:04:52.310 ThaliTest[1875:3186771] jxcore: stopAdvertisingAndListening
,2016-03-21 13:04:52.310 ThaliTest[1875:3186771] THEMultipeerManager stopping peer
,2016-03-21 13:04:52.311 ThaliTest[1875:3186771] multipeer manager: stop client timer
2016-03-21 13:04:52.312 ThaliTest[1875:3186771] jxcore: stopAdvertisingAndListening: success
ok 154 Should be able to call stopAdvertisingAndListening in teardown
,# 37. Can connect to a remote peer
,# teardown
,2016-03-21 13:04:55.944 ThaliTest[1875:3186771] jxcore: startUpdateAdvertisingAndListening
2016-03-21 13:04:55.944 ThaliTest[1875:3186771] server: starting FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8
,2016-03-21 13:04:55.945 ThaliTest[1875:3186771] multipeer manager: start client restart timer: 0x155c4fc0
2016-03-21 13:04:55.947 ThaliTest[1875:3186771] THEMultipeerManager initialized peer FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8
2016-03-21 13:04:55.948 ,ThaliTest[1875:3186771] jxcore: startUpdateAdvertisingAndListening: success
ok 155 Can call startUpdateAdvertisingAndListening without error
2016-03-21 13:04:55.950 ThaliTest[1875:3186771] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeW,rapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-21 13:04:55.951 ThaliTest[1875:3186771] jxcore: startListeningForAdvertisements: success
ok 156 Can call startListeningForAdvertisements without error
,2016-03-21 13:04:58.105 ThaliTest[1875:3186576] client: found new peer: ACF08CBB-018B-4F78-A189-81A63854F007:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"ACF08CBB-018B-4F78-A189-81A63854F,007:7","pleaseConnect":0}]
,2016-03-21 13:04:58.109 ThaliTest[1875:3186771] jxcore: connect ACF08CBB-018B-4F78-A189-81A63854F007:7
2016-03-21 13:04:58.110 ThaliTest[1875:3186771] client session: connect
2016-03-21 13:04:58.110 ThaliTest[1875:3186771] client session: stateChange:0->1 ACF08CBB-018B-4F78-A189-81A63854F007:7
,2016-03-21 13:04:58.438 ThaliTest[1875:3186576] multipeer session: reset timer
2016-03-21 13:04:58.438 ThaliTest[1875:3186576] server: rejecting invitation from ACF08CBB-018B-4F78-A189-81A63854F007 due to previous generation (FE8F9526-AD74-40E1-9080-FD7FA,9CC9893:8 != FE8F9526-AD74-40E1-9080-FD7FA9CC9893:7)
,2016-03-21 13:04:59.219 ThaliTest[1875:3187133] client session: not connected ACF08CBB-018B-4F78-A189-81A63854F007:7
2016-03-21 13:04:59.220 ThaliTest[1875:3187133] client session: onLinkFailure: ACF08CBB-018B-4F78-A189-81A63854F007
2016-03-21 13:04:59.2,20 ThaliTest[1875:3187133] client session: disconnect
2016-03-21 13:04:59.222 ThaliTest[1875:3187133] client session: stateChange:1->0 ACF08CBB-018B-4F78-A189-81A63854F007:7
2016-03-21 13:04:59.222 ThaliTest[1875:3187133] client session: fireConnectCallb,ack: ACF08CBB-018B-4F78-A189-81A63854F007
2016-03-21 13:04:59.223 ThaliTest[1875:3187133] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-21 13:05:02.230 ThaliTest[1875:3186771] jxcore: connect ACF08CBB-018B-4F78-A189-81A63854F007:7
2016-03-21 13:05:02.231 ThaliTest[1875:3186771] client session: connect
2016-03-21 13:05:02.231 ThaliTest[1875:3186771] client session: stateChange:0->1 ACF08CBB-018B-4F78-A189-81A63854F007:7
,2016-03-21 13:05:02.847 ThaliTest[1875:3187172] client session: not connected ACF08CBB-018B-4F78-A189-81A63854F007:7
2016-03-21 13:05:02.847 ThaliTest[1875:3187172] client session: onLinkFailure: ACF08CBB-018B-4F78-A189-81A63854F007
2016-03-21 13:05:02.8,47 ThaliTest[1875:3187172] client session: disconnect
2016-03-21 13:05:02.848 ThaliTest[1875:3187172] client session: stateChange:1->0 ACF08CBB-018B-4F78-A189-81A63854F007:7
2016-03-21 13:05:02.848 ThaliTest[1875:3187172] client session: fireConnectCallb,ack: ACF08CBB-018B-4F78-A189-81A63854F007
2016-03-21 13:05:02.849 ThaliTest[1875:3187172] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-21 13:05:05.861 ThaliTest[1875:3186771] jxcore: connect ACF08CBB-018B-4F78-A189-81A63854F007:7
2016-03-21 13:05:05.862 ThaliTest[1875:3186771] client session: connect
2016-03-21 13:05:05.862 ThaliTest[1875:3186771] client session: stateChange:0->,1 ACF08CBB-018B-4F78-A189-81A63854F007:7
,2016-03-21 13:05:07.059 ThaliTest[1875:3187177] client session: not connected ACF08CBB-018B-4F78-A189-81A63854F007:7
2016-03-21 13:05:07.059 ThaliTest[1875:3187177] client session: onLinkFailure: ACF08CBB-018B-4F78-A189-81A63854F007
2016-03-21 13:05:07.0,60 ThaliTest[1875:3187177] client session: disconnect
2016-03-21 13:05:07.060 ThaliTest[1875:3187177] client session: stateChange:1->0 ACF08CBB-018B-4F78-A189-81A63854F007:7
,2016-03-21 13:05:07.063 ThaliTest[1875:3187177] client session: fireConnectCallback: ACF08CBB-018B-4F78-A189-81A63854F007
,2016-03-21 13:05:07.064 ThaliTest[1875:3187177] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-21 13:05:10.071 ThaliTest[1875:3186771] jxcore: connect ACF08CBB-018B-4F78-A189-81A63854F007:7
2016-03-21 13:05:10.071 ThaliTest[1875:3186771] client session: connect
2016-03-21 13:05:10.072 ThaliTest[1875:3186771] client session: stateChange:0->1 ACF08CBB-018B-4F78-A189-81A63854F007:7
,2016-03-21 13:05:10.709 ThaliTest[1875:3187172] client session: not connected ACF08CBB-018B-4F78-A189-81A63854F007:7
2016-03-21 13:05:10.709 ThaliTest[1875:3187172] client session: onLinkFailure: ACF08CBB-018B-4F78-A189-81A63854F007
2016-03-21 13:05:10.709 ThaliTest[1875:3187172] client session: disconnect
2016-03-21 13:05:10.710 ThaliTest[1875:3187172] client session: stateChange:1->0 ACF08CBB-018B-4F78-A189-81A63854F007:7
,2016-03-21 13:05:10.712 ThaliTest[1875:3187172] client session: fireConnectCallback: ACF08CBB-018B-4F78-A189-81A63854F007
2016-03-21 13:05:10.712 ThaliTest[1875:3187172] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returne,d an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-21 13:05:11.129 ThaliTest[1875:3186576] multipeer session: reset timer
2016-03-21 13:05:11.129 ThaliTest[1875:3186576] server: disconnecting to refresh session (ACF08CBB-018B-4F78-A189-81A63854F007)
2016-03-21 13:05:11.130 ThaliTest[1875:3186576], server: rejecting invitation from ACF08CBB-018B-4F78-A189-81A63854F007 due to previous generation (FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8 != FE8F9526-AD74-40E1-9080-FD7FA9CC9893:7)
,2016-03-21 13:05:13.719 ThaliTest[1875:3186771] jxcore: connect ACF08CBB-018B-4F78-A189-81A63854F007:7
2016-03-21 13:05:13.720 ThaliTest[1875:3186771] client session: connect
2016-03-21 13:05:13.720 ThaliTest[1875:3186771] client session: stateChange:0->,1 ACF08CBB-018B-4F78-A189-81A63854F007:7
,2016-03-21 13:05:13.895 ThaliTest[1875:3187172] client session: not connected ACF08CBB-018B-4F78-A189-81A63854F007:7
2016-03-21 13:05:13.895 ThaliTest[1875:3187172] client session: onLinkFailure: ACF08CBB-018B-4F78-A189-81A63854F007
2016-03-21 13:05:13.8,95 ThaliTest[1875:3187172] client session: disconnect
2016-03-21 13:05:13.896 ThaliTest[1875:3187172] client session: stateChange:1->0 ACF08CBB-018B-4F78-A189-81A63854F007:7
2016-03-21 13:05:13.897 ThaliTest[1875:3187172] client session: fireConnectCallb,ack: ACF08CBB-018B-4F78-A189-81A63854F007
,2016-03-21 13:05:13.897 ThaliTest[1875:3187172] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-21 13:05:15.949 ThaliTest[1875:3186576] multipeer manager: restart client
,2016-03-21 13:05:15.967 ThaliTest[1875:3186576] client: found updated peer: ACF08CBB-018B-4F78-A189-81A63854F007:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"ACF08CBB-018B-4F78-A189-81A63854F007:8","pleaseConnect":0}]
,2016-03-21 13:05:16.911 ThaliTest[1875:3186771] jxcore: connect ACF08CBB-018B-4F78-A189-81A63854F007:7
2016-03-21 13:05:16.911 ThaliTest[1875:3186771] client session: connect
2016-03-21 13:05:16.912 ThaliTest[1875:3186771] client session: stateChange:0->1 ACF08CBB-018B-4F78-A189-81A63854F007:8
,2016-03-21 13:05:17.041 ThaliTest[1875:3187177] client session: not connected ACF08CBB-018B-4F78-A189-81A63854F007:8
2016-03-21 13:05:17.042 ThaliTest[1875:3187177] client session: onLinkFailure: ACF08CBB-018B-4F78-A189-81A63854F007
2016-03-21 13:05:17.0,42 ThaliTest[1875:3187177] client session: disconnect
2016-03-21 13:05:17.043 ThaliTest[1875:3187177] client session: stateChange:1->0 ACF08CBB-018B-4F78-A189-81A63854F007:8
2016-03-21 13:05:17.043 ThaliTest[1875:3187177] client session: fireConnectCallb,ack: ACF08CBB-018B-4F78-A189-81A63854F007
2016-03-21 13:05:17.043 ThaliTest[1875:3187177] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 4
,2016-03-21 13:05:20.052 ThaliTest[1875:3186771] jxcore: connect ACF08CBB-018B-4F78-A189-81A63854F007:7
2016-03-21 13:05:20.053 ThaliTest[1875:3186771] client session: connect
2016-03-21 13:05:20.053 ThaliTest[1875:3186771] client session: stateChange:0->,1 ACF08CBB-018B-4F78-A189-81A63854F007:8
,2016-03-21 13:05:20.139 ThaliTest[1875:3187177] client session: not connected ACF08CBB-018B-4F78-A189-81A63854F007:8
2016-03-21 13:05:20.141 ThaliTest[1875:3187177] client session: onLinkFailure: ACF08CBB-018B-4F78-A189-81A63854F007
2016-03-21 13:05:20.1,41 ThaliTest[1875:3187177] client session: disconnect
2016-03-21 13:05:20.141 ThaliTest[1875:3187177] client session: stateChange:1->0 ACF08CBB-018B-4F78-A189-81A63854F007:8
2016-03-21 13:05:20.142 ThaliTest[1875:3187177] client session: fireConnectCallb,ack: ACF08CBB-018B-4F78-A189-81A63854F007
2016-03-21 13:05:20.142 ThaliTest[1875:3187177] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-21 13:05:23.147 ThaliTest[1875:3186771] jxcore: connect ACF08CBB-018B-4F78-A189-81A63854F007:7
2016-03-21 13:05:23.148 ThaliTest[1875:3186771] client session: connect
2016-03-21 13:05:23.148 ThaliTest[1875:3186771] client session: stateChange:0->1 ACF08CBB-018B-4F78-A189-81A63854F007:8
,2016-03-21 13:05:23.323 ThaliTest[1875:3187135] client session: not connected ACF08CBB-018B-4F78-A189-81A63854F007:8
2016-03-21 13:05:23.323 ThaliTest[1875:3187135] client session: onLinkFailure: ACF08CBB-018B-4F78-A189-81A63854F007
2016-03-21 13:05:23.3,24 ThaliTest[1875:3187135] client session: disconnect
2016-03-21 13:05:23.324 ThaliTest[1875:3187135] client session: stateChange:1->0 ACF08CBB-018B-4F78-A189-81A63854F007:8
,2016-03-21 13:05:23.326 ThaliTest[1875:3187135] client session: fireConnectCallback: ACF08CBB-018B-4F78-A189-81A63854F007
2016-03-21 13:05:23.326 ThaliTest[1875:3187135] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-21 13:05:24.245 ThaliTest[1875:3186576] multipeer session: reset timer
2016-03-21 13:05:24.246 ThaliTest[1875:3186576] server: disconnecting to refresh session (ACF08CBB-018B-4F78-A189-81A63854F007)
2016-03-21 13:05:24.246 ThaliTest[1875:3186576], server: rejecting invitation from ACF08CBB-018B-4F78-A189-81A63854F007 due to previous generation (FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8 != FE8F9526-AD74-40E1-9080-FD7FA9CC9893:7)
,2016-03-21 13:05:26.332 ThaliTest[1875:3186771] jxcore: connect ACF08CBB-018B-4F78-A189-81A63854F007:7
2016-03-21 13:05:26.333 ThaliTest[1875:3186771] client session: connect
2016-03-21 13:05:26.333 ThaliTest[1875:3186771] client session: stateChange:0->1 ACF08CBB-018B-4F78-A189-81A63854F007:8
,2016-03-21 13:05:26.475 ThaliTest[1875:3187172] client session: not connected ACF08CBB-018B-4F78-A189-81A63854F007:8
2016-03-21 13:05:26.475 ThaliTest[1875:3187172] client session: onLinkFailure: ACF08CBB-018B-4F78-A189-81A63854F007
2016-03-21 13:05:26.4,76 ThaliTest[1875:3187172] client session: disconnect
,2016-03-21 13:05:26.476 ThaliTest[1875:3187172] client session: stateChange:1->0 ACF08CBB-018B-4F78-A189-81A63854F007:8
,2016-03-21 13:05:26.480 ThaliTest[1875:3187172] client session: fireConnectCallback: ACF08CBB-018B-4F78-A189-81A63854F007
2016-03-21 13:05:26.480 ThaliTest[1875:3187172] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returne,d an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-21 13:05:29.491 ThaliTest[1875:3186771] jxcore: connect ACF08CBB-018B-4F78-A189-81A63854F007:7
2016-03-21 13:05:29.492 ThaliTest[1875:3186771] client session: connect
2016-03-21 13:05:29.492 ThaliTest[1875:3186771] client session: stateChange:0->1 ACF08CBB-018B-4F78-A189-81A63854F007:8
,2016-03-21 13:05:29.609 ThaliTest[1875:3187172] client session: not connected ACF08CBB-018B-4F78-A189-81A63854F007:8
2016-03-21 13:05:29.610 ThaliTest[1875:3187172] client session: onLinkFailure: ACF08CBB-018B-4F78-A189-81A63854F007
2016-03-21 13:05:29.6,10 ThaliTest[1875:3187172] client session: disconnect
,2016-03-21 13:05:29.610 ThaliTest[1875:3187172] client session: stateChange:1->0 ACF08CBB-018B-4F78-A189-81A63854F007:8
2016-03-21 13:05:29.613 ThaliTest[1875:3187172] client session: fireConnectCallback: ACF08CBB-018B-4F78-A189-81A63854F007
2016-03-21 1,3:05:29.613 ThaliTest[1875:3187172] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
WARN testThaliMobileNative: Too many connect retries!
,not ok 157 Connect failed!
,  ---
,    operator: fail
,  ...
,# setup
,2016-03-21 13:05:35.949 ThaliTest[1875:3186576] multipeer manager: restart client
,2016-03-21 13:05:35.966 ThaliTest[1875:3186576] client: found existing peer: ACF08CBB-018B-4F78-A189-81A63854F007:8
,2016-03-21 13:05:37.476 ThaliTest[1875:3186576] multipeer session: reset timer
2016-03-21 13:05:37.478 ThaliTest[1875:3186576] server: disconnecting to refresh session (ACF08CBB-018B-4F78-A189-81A63854F007)
2016-03-21 13:05:37.478 ThaliTest[1875:3186576], server: rejecting invitation from ACF08CBB-018B-4F78-A189-81A63854F007 due to previous generation (FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8 != FE8F9526-AD74-40E1-9080-FD7FA9CC9893:7)
,2016-03-21 13:05:50.656 ThaliTest[1875:3186576] multipeer session: reset timer
,2016-03-21 13:05:50.657 ThaliTest[1875:3186576] server: disconnecting to refresh session (ACF08CBB-018B-4F78-A189-81A63854F007)
,2016-03-21 13:05:50.658 ThaliTest[1875:3186576] server: rejecting invitation from ACF08CBB-018B-4F78-A189-81A63854F007 due to previous generation (FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8 != FE8F9526-AD74-40E1-9080-FD7FA9CC9893:7)
,2016-03-21 13:05:55.949 ThaliTest[1875:3186576] multipeer manager: restart client
,2016-03-21 13:05:55.965 ThaliTest[1875:3186576] client: found existing peer: ACF08CBB-018B-4F78-A189-81A63854F007:8
,2016-03-21 13:06:03.195 ThaliTest[1875:3186576] multipeer session: reset timer
2016-03-21 13:06:03.195 ThaliTest[1875:3186576] server: disconnecting to refresh session (ACF08CBB-018B-4F78-A189-81A63854F007)
2016-03-21 13:06:03.196 ThaliTest[1875:3186576], server: rejecting invitation from ACF08CBB-018B-4F78-A189-81A63854F007 due to previous generation (FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8 != FE8F9526-AD74-40E1-9080-FD7FA9CC9893:7)
,2016-03-21 13:06:15.948 ThaliTest[1875:3186576] multipeer manager: restart client
,2016-03-21 13:06:15.966 ThaliTest[1875:3186576] client: found existing peer: ACF08CBB-018B-4F78-A189-81A63854F007:8
,2016-03-21 13:06:16.325 ThaliTest[1875:3186576] multipeer session: reset timer
2016-03-21 13:06:16.326 ThaliTest[1875:3186576] server: disconnecting to refresh session (ACF08CBB-018B-4F78-A189-81A63854F007)
2016-03-21 13:06:16.326 ThaliTest[1875:3186576], server: rejecting invitation from ACF08CBB-018B-4F78-A189-81A63854F007 due to previous generation (FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8 != FE8F9526-AD74-40E1-9080-FD7FA9CC9893:7)
,2016-03-21 13:06:30.400 ThaliTest[1875:3186576] multipeer session: reset timer
2016-03-21 13:06:30.400 ThaliTest[1875:3186576] server: disconnecting to refresh session (ACF08CBB-018B-4F78-A189-81A63854F007)
2016-03-21 13:06:30.401 ThaliTest[1875:3186576], server: rejecting invitation from ACF08CBB-018B-4F78-A189-81A63854F007 due to previous generation (FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8 != FE8F9526-AD74-40E1-9080-FD7FA9CC9893:7)
,2016-03-21 13:06:35.949 ThaliTest[1875:3186576] multipeer manager: restart client
,2016-03-21 13:06:35.968 ThaliTest[1875:3186576] client: found existing peer: ACF08CBB-018B-4F78-A189-81A63854F007:8
,2016-03-21 13:06:42.544 ThaliTest[1875:3186576] multipeer session: reset timer
2016-03-21 13:06:42.544 ThaliTest[1875:3186576] server: disconnecting to refresh session (ACF08CBB-018B-4F78-A189-81A63854F007)
2016-03-21 13:06:42.545 ThaliTest[1875:3186576], server: rejecting invitation from ACF08CBB-018B-4F78-A189-81A63854F007 due to previous generation (FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8 != FE8F9526-AD74-40E1-9080-FD7FA9CC9893:7)
,2016-03-21 13:06:55.636 ThaliTest[1875:3186576] multipeer session: reset timer
,2016-03-21 13:06:55.636 ThaliTest[1875:3186576] server: disconnecting to refresh session (ACF08CBB-018B-4F78-A189-81A63854F007)
,2016-03-21 13:06:55.638 ThaliTest[1875:3186576] server: rejecting invitation from ACF08CBB-018B-4F78-A189-81A63854F007 due to previous generation (FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8 != FE8F9526-AD74-40E1-9080-FD7FA9CC9893:7)
,2016-03-21 13:06:55.949 ThaliTest[1875:3186576] multipeer manager: restart client
,2016-03-21 13:06:55.968 ThaliTest[1875:3186576] client: found existing peer: ACF08CBB-018B-4F78-A189-81A63854F007:8
,2016-03-21 13:07:05.380 ThaliTest[1875:3186771] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-21 13:07:05.382 ThaliTest[1875:3186771] jxcore: stopListeningForAdvertisements: success
,ok 158 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-21 13:07:05.385 ThaliTest[1875:3186771] jxcore: stopAdvertisingAndListening
2016-03-21 13:07:05.386 ThaliTest[1875:3186771] THEMultipeerManager stopping peer
2016-03-21 13:07:05.386 ThaliTest[1875:3186771] multipeer manager: stop client timer
20,16-03-21 13:07:05.387 ThaliTest[1875:3186771] jxcore: stopAdvertisingAndListening: success
ok 159 Should be able to call stopAdvertisingAndListening in teardown
,# 38. Can shift large amounts of data
,# teardown
,2016-03-21 13:07:05.919 ThaliTest[1875:3186771] jxcore: startUpdateAdvertisingAndListening
,2016-03-21 13:07:05.919 ThaliTest[1875:3186771] server: starting FE8F9526-AD74-40E1-9080-FD7FA9CC9893:9
,2016-03-21 13:07:05.920 ThaliTest[1875:3186771] multipeer manager: start client restart timer: 0x155c4fc0
,2016-03-21 13:07:05.921 ThaliTest[1875:3186771] THEMultipeerManager initialized peer FE8F9526-AD74-40E1-9080-FD7FA9CC9893:9
2016-03-21 13:07:05.923 ThaliTest[1875:3186771] jxcore: startUpdateAdvertisingAndListening: success
,ok 160 Can call startUpdateAdvertisingAndListening without error
,2016-03-21 13:07:05.925 ThaliTest[1875:3186771] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
,2016-03-21 13:07:05.926 ThaliTest[1875:3186771] jxcore: startListeningForAdvertisements: success
,ok 161 Can call startListeningForAdvertisements without error
,2016-03-21 13:07:06.553 ThaliTest[1875:3186576] client: found new peer: ACF08CBB-018B-4F78-A189-81A63854F007:8
2016-03-21 13:07:06.555 ThaliTest[1875:3186771] jxcore: connect ACF08CBB-018B-4F78-A189-81A63854F007:8
2016-03-21 13:07:06.555 ThaliTest[1875:3,186771] client session: connect
2016-03-21 13:07:06.556 ThaliTest[1875:3186771] client session: stateChange:0->1 ACF08CBB-018B-4F78-A189-81A63854F007:8
,2016-03-21 13:07:07.202 ThaliTest[1875:3187575] client session: not connected ACF08CBB-018B-4F78-A189-81A63854F007:8
2016-03-21 13:07:07.203 ThaliTest[1875:3187575] client session: onLinkFailure: ACF08CBB-018B-4F78-A189-81A63854F007
,2016-03-21 13:07:07.203 ThaliTest[1875:3187575] client session: disconnect
2016-03-21 13:07:07.205 ThaliTest[1875:3187575] client session: stateChange:1->0 ACF08CBB-018B-4F78-A189-81A63854F007:8
2016-03-21 13:07:07.206 ThaliTest[1875:3187575] client sess,ion: fireConnectCallback: ACF08CBB-018B-4F78-A189-81A63854F007
2016-03-21 13:07:07.206 ThaliTest[1875:3187575] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-21 13:07:08.101 ThaliTest[1875:3186576] multipeer session: reset timer
2016-03-21 13:07:08.102 ThaliTest[1875:3186576] server: rejecting invitation from ACF08CBB-018B-4F78-A189-81A63854F007 due to previous generation (FE8F9526-AD74-40E1-9080-FD7FA9CC9893:9 != FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8)
,2016-03-21 13:07:10.213 ThaliTest[1875:3186771] jxcore: connect ACF08CBB-018B-4F78-A189-81A63854F007:8
2016-03-21 13:07:10.214 ThaliTest[1875:3186771] client session: connect
2016-03-21 13:07:10.214 ThaliTest[1875:3186771] client session: stateChange:0->1 ACF08CBB-018B-4F78-A189-81A63854F007:8
,2016-03-21 13:07:10.325 ThaliTest[1875:3187622] client session: not connected ACF08CBB-018B-4F78-A189-81A63854F007:8
2016-03-21 13:07:10.325 ThaliTest[1875:3187622] client session: onLinkFailure: ACF08CBB-018B-4F78-A189-81A63854F007
2016-03-21 13:07:10.326 ThaliTest[1875:3187622] client session: disconnect
,2016-03-21 13:07:10.328 ThaliTest[1875:3187622] client session: stateChange:1->0 ACF08CBB-018B-4F78-A189-81A63854F007:8
2016-03-21 13:07:10.329 ThaliTest[1875:3187622] client session: fireConnectCallback: ACF08CBB-018B-4F78-A189-81A63854F007
2016-03-21 1,3:07:10.329 ThaliTest[1875:3187622] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-21 13:07:13.340 ThaliTest[1875:3186771] jxcore: connect ACF08CBB-018B-4F78-A189-81A63854F007:8
2016-03-21 13:07:13.341 ThaliTest[1875:3186771] client session: connect
2016-03-21 13:07:13.341 ThaliTest[1875:3186771] client session: stateChange:0->1 ACF08CBB-018B-4F78-A189-81A63854F007:8
,2016-03-21 13:07:13.421 ThaliTest[1875:3187622] client session: not connected ACF08CBB-018B-4F78-A189-81A63854F007:8
2016-03-21 13:07:13.421 ThaliTest[1875:3187622] client session: onLinkFailure: ACF08CBB-018B-4F78-A189-81A63854F007
2016-03-21 13:07:13.4,22 ThaliTest[1875:3187622] client session: disconnect
,2016-03-21 13:07:13.422 ThaliTest[1875:3187622] client session: stateChange:1->0 ACF08CBB-018B-4F78-A189-81A63854F007:8
2016-03-21 13:07:13.425 ThaliTest[1875:3187622] client session: fireConnectCallback: ACF08CBB-018B-4F78-A189-81A63854F007
2016-03-21 1,3:07:13.425 ThaliTest[1875:3187622] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-21 13:07:16.438 ThaliTest[1875:3186771] jxcore: connect ACF08CBB-018B-4F78-A189-81A63854F007:8
2016-03-21 13:07:16.439 ThaliTest[1875:3186771] client session: connect
2016-03-21 13:07:16.439 ThaliTest[1875:3186771] client session: stateChange:0->,1 ACF08CBB-018B-4F78-A189-81A63854F007:8
,2016-03-21 13:07:16.615 ThaliTest[1875:3187417] client session: not connected ACF08CBB-018B-4F78-A189-81A63854F007:8
2016-03-21 13:07:16.615 ThaliTest[1875:3187417] client session: onLinkFailure: ACF08CBB-018B-4F78-A189-81A63854F007
2016-03-21 13:07:16.6,16 ThaliTest[1875:3187417] client session: disconnect
2016-03-21 13:07:16.616 ThaliTest[1875:3187417] client session: stateChange:1->0 ACF08CBB-018B-4F78-A189-81A63854F007:8
2016-03-21 13:07:16.617 ThaliTest[1875:3187417] client session: fireConnectCallb,ack: ACF08CBB-018B-4F78-A189-81A63854F007
2016-03-21 13:07:16.617 ThaliTest[1875:3187417] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-21 13:07:19.634 ThaliTest[1875:3186771] jxcore: connect ACF08CBB-018B-4F78-A189-81A63854F007:8
2016-03-21 13:07:19.635 ThaliTest[1875:3186771] client session: connect
2016-03-21 13:07:19.635 ThaliTest[1875:3186771] client session: stateChange:0->1 ACF08CBB-018B-4F78-A189-81A63854F007:8
,2016-03-21 13:07:19.815 ThaliTest[1875:3186576] multipeer session: reset timer
2016-03-21 13:07:19.815 ThaliTest[1875:3186576] server: disconnecting to refresh session (ACF08CBB-018B-4F78-A189-81A63854F007)
2016-03-21 13:07:19.815 ThaliTest[1875:3186576], server: rejecting invitation from ACF08CBB-018B-4F78-A189-81A63854F007 due to previous generation (FE8F9526-AD74-40E1-9080-FD7FA9CC9893:9 != FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8)
,2016-03-21 13:07:19.898 ThaliTest[1875:3187417] client session: not connected ACF08CBB-018B-4F78-A189-81A63854F007:8
2016-03-21 13:07:19.898 ThaliTest[1875:3187417] client session: onLinkFailure: ACF08CBB-018B-4F78-A189-81A63854F007
2016-03-21 13:07:19.8,98 ThaliTest[1875:3187417] client session: disconnect
2016-03-21 13:07:19.898 ThaliTest[1875:3187417] client session: stateChange:1->0 ACF08CBB-018B-4F78-A189-81A63854F007:8
,2016-03-21 13:07:19.903 ThaliTest[1875:3187417] client session: fireConnectCallback: ACF08CBB-018B-4F78-A189-81A63854F007
2016-03-21 13:07:19.903 ThaliTest[1875:3187417] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-21 13:07:22.912 ThaliTest[1875:3186771] jxcore: connect ACF08CBB-018B-4F78-A189-81A63854F007:8
2016-03-21 13:07:22.913 ThaliTest[1875:3186771] client session: connect
2016-03-21 13:07:22.913 ThaliTest[1875:3186771] client session: stateChange:0->,1 ACF08CBB-018B-4F78-A189-81A63854F007:8
,2016-03-21 13:07:23.946 ThaliTest[1875:3187572] client session: not connected ACF08CBB-018B-4F78-A189-81A63854F007:8
2016-03-21 13:07:23.948 ThaliTest[1875:3187572] client session: onLinkFailure: ACF08CBB-018B-4F78-A189-81A63854F007
2016-03-21 13:07:23.9,48 ThaliTest[1875:3187572] client session: disconnect
,2016-03-21 13:07:23.949 ThaliTest[1875:3187572] client session: stateChange:1->0 ACF08CBB-018B-4F78-A189-81A63854F007:8
2016-03-21 13:07:23.951 ThaliTest[1875:3187572] client session: fireConnectCallback: ACF08CBB-018B-4F78-A189-81A63854F007
2016-03-21 1,3:07:23.952 ThaliTest[1875:3187572] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-21 13:07:25.923 ThaliTest[1875:3186576] multipeer manager: restart client
,2016-03-21 13:07:25.940 ThaliTest[1875:3186576] client: found updated peer: ACF08CBB-018B-4F78-A189-81A63854F007:9
,2016-03-21 13:07:26.960 ThaliTest[1875:3186771] jxcore: connect ACF08CBB-018B-4F78-A189-81A63854F007:8
2016-03-21 13:07:26.961 ThaliTest[1875:3186771] client session: connect
2016-03-21 13:07:26.961 ThaliTest[1875:3186771] client session: stateChange:0->1 ACF08CBB-018B-4F78-A189-81A63854F007:9
,2016-03-21 13:07:27.095 ThaliTest[1875:3187572] client session: not connected ACF08CBB-018B-4F78-A189-81A63854F007:9
2016-03-21 13:07:27.096 ThaliTest[1875:3187572] client session: onLinkFailure: ACF08CBB-018B-4F78-A189-81A63854F007
,2016-03-21 13:07:27.098 ThaliTest[1875:3187572] client session: disconnect
2016-03-21 13:07:27.098 ThaliTest[1875:3187572] client session: stateChange:1->0 ACF08CBB-018B-4F78-A189-81A63854F007:9
2016-03-21 13:07:27.099 ThaliTest[1875:3187572] client sess,ion: fireConnectCallback: ACF08CBB-018B-4F78-A189-81A63854F007
2016-03-21 13:07:27.099 ThaliTest[1875:3187572] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-21 13:07:30.109 ThaliTest[1875:3186771] jxcore: connect ACF08CBB-018B-4F78-A189-81A63854F007:8
2016-03-21 13:07:30.109 ThaliTest[1875:3186771] client session: connect
2016-03-21 13:07:30.110 ThaliTest[1875:3186771] client session: stateChange:0->,1 ACF08CBB-018B-4F78-A189-81A63854F007:9
,2016-03-21 13:07:30.656 ThaliTest[1875:3187572] client session: not connected ACF08CBB-018B-4F78-A189-81A63854F007:9
2016-03-21 13:07:30.657 ThaliTest[1875:3187572] client session: onLinkFailure: ACF08CBB-018B-4F78-A189-81A63854F007
2016-03-21 13:07:30.658 ThaliTest[1875:3187572] client session: disconnect
,2016-03-21 13:07:30.658 ThaliTest[1875:3187572] client session: stateChange:1->0 ACF08CBB-018B-4F78-A189-81A63854F007:9
,2016-03-21 13:07:30.661 ThaliTest[1875:3187572] client session: fireConnectCallback: ACF08CBB-018B-4F78-A189-81A63854F007
,2016-03-21 13:07:30.661 ThaliTest[1875:3187572] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-21 13:07:32.852 ThaliTest[1875:3186576] multipeer session: reset timer
2016-03-21 13:07:32.853 ThaliTest[1875:3186576] server: disconnecting to refresh session (ACF08CBB-018B-4F78-A189-81A63854F007)
2016-03-21 13:07:32.853 ThaliTest[1875:3186576], server: rejecting invitation from ACF08CBB-018B-4F78-A189-81A63854F007 due to previous generation (FE8F9526-AD74-40E1-9080-FD7FA9CC9893:9 != FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8)
,2016-03-21 13:07:33.674 ThaliTest[1875:3186771] jxcore: connect ACF08CBB-018B-4F78-A189-81A63854F007:8
2016-03-21 13:07:33.674 ThaliTest[1875:3186771] client session: connect
2016-03-21 13:07:33.675 ThaliTest[1875:3186771] client session: stateChange:0->1 ACF08CBB-018B-4F78-A189-81A63854F007:9
,2016-03-21 13:07:33.759 ThaliTest[1875:3187575] client session: not connected ACF08CBB-018B-4F78-A189-81A63854F007:9
2016-03-21 13:07:33.759 ThaliTest[1875:3187575] client session: onLinkFailure: ACF08CBB-018B-4F78-A189-81A63854F007
2016-03-21 13:07:33.760 ThaliTest[1875:3187575] client session: disconnect
,2016-03-21 13:07:33.760 ThaliTest[1875:3187575] client session: stateChange:1->0 ACF08CBB-018B-4F78-A189-81A63854F007:9
,2016-03-21 13:07:33.764 ThaliTest[1875:3187575] client session: fireConnectCallback: ACF08CBB-018B-4F78-A189-81A63854F007
2016-03-21 13:07:33.764 ThaliTest[1875:3187575] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-21 13:07:36.774 ThaliTest[1875:3186771] jxcore: connect ACF08CBB-018B-4F78-A189-81A63854F007:8
2016-03-21 13:07:36.775 ThaliTest[1875:3186771] client session: connect
2016-03-21 13:07:36.775 ThaliTest[1875:3186771] client session: stateChange:0->1 ACF08CBB-018B-4F78-A189-81A63854F007:9
,2016-03-21 13:07:36.952 ThaliTest[1875:3187575] client session: not connected ACF08CBB-018B-4F78-A189-81A63854F007:9
2016-03-21 13:07:36.952 ThaliTest[1875:3187575] client session: onLinkFailure: ACF08CBB-018B-4F78-A189-81A63854F007
2016-03-21 13:07:36.9,53 ThaliTest[1875:3187575] client session: disconnect
2016-03-21 13:07:36.953 ThaliTest[1875:3187575] client session: stateChange:1->0 ACF08CBB-018B-4F78-A189-81A63854F007:9
2016-03-21 13:07:36.954 ThaliTest[1875:3187575] client session: fireConnectCallb,ack: ACF08CBB-018B-4F78-A189-81A63854F007
2016-03-21 13:07:36.954 ThaliTest[1875:3187575] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,WARN testThaliMobileNative: Too many connect retries!
,not ok 162 Connect failed!
,  ---
,    operator: fail
,  ...
,# setup
,2016-03-21 13:07:45.923 ThaliTest[1875:3186576] multipeer manager: restart client
,2016-03-21 13:07:45.939 ThaliTest[1875:3186576] client: found existing peer: ACF08CBB-018B-4F78-A189-81A63854F007:9
,2016-03-21 13:08:05.923 ThaliTest[1875:3186576] multipeer manager: restart client
,2016-03-21 13:08:05.939 ThaliTest[1875:3186576] client: found existing peer: ACF08CBB-018B-4F78-A189-81A63854F007:9
,2016-03-21 13:08:15.323 ThaliTest[1875:3186771] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-21 13:08:15.325 ThaliTest[1875:3186771] jxcore: stopListeningForAdvertisements: success
,ok 163 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-21 13:08:15.328 ThaliTest[1875:3186771] jxcore: stopAdvertisingAndListening
2016-03-21 13:08:15.328 ThaliTest[1875:3186771] THEMultipeerManager stopping peer
2016-03-21 13:08:15.329 ThaliTest[1875:3186771] multipeer manager: stop client timer
20,16-03-21 13:08:15.329 ThaliTest[1875:3186771] jxcore: stopAdvertisingAndListening: success
ok 164 Should be able to call stopAdvertisingAndListening in teardown
,# 39. #startListeningForAdvertisements should fail if start not called
,2016-03-21 13:08:15.428 ThaliTest[1875:3186771] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-21 13:08:15.429 ThaliTest[1875:3186771] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-21 13:08:15.430 ThaliTest[1875:3,186771] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-21 13:08:15.433 ThaliTest[1875:3186771] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,ok 165 specific error should be returned
,# setup
,# 40. #startUpdateAdvertisingAndListening should fail if start not called
,2016-03-21 13:08:15.906 ThaliTest[1875:3186771] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-21 13:08:15.906 ThaliTest[1875:3186771] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-21 13:08:15.908 ThaliTest[1875:3186771] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-21 13:08:15.910 ThaliTest[1875:3186771] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,ok 166 specific error should be returned
,# setup
,# 41. should be able to call #stopListeningForAdvertisements many times
,2016-03-21 13:08:16.435 ThaliTest[1875:3186771] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-21 13:08:16.436 ThaliTest[1875:3186771] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-21 13:08:16.437 ThaliTest[1875:3186771] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-21 13:08:16.440 ThaliTest[1875:3186771] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49352
,2016-03-21 13:08:16.565 ThaliTest[1875:3186771] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 13:08:16.569 ThaliTest[1875:3186771] jxcore: stopListeningForAdvertisements: success
,ok 167 no errors
,2016-03-21 13:08:16.573 ThaliTest[1875:3186771] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 13:08:16.575 ThaliTest[1875:3186771] jxcore: stopListeningForAdvertisements: success
,ok 168 still no errors
,# setup
,2016-03-21 13:08:16.690 ThaliTest[1875:3186771] jxcore: stopAdvertisingAndListening
,2016-03-21 13:08:16.691 ThaliTest[1875:3186771] THEMultipeerManager stopping peer
,2016-03-21 13:08:16.692 ThaliTest[1875:3186771] jxcore: stopAdvertisingAndListening: success
,2016-03-21 13:08:16.694 ThaliTest[1875:3186771] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 13:08:16.697 ThaliTest[1875:3186771] jxcore: stopListeningForAdvertisements: success
,# 42. should be able to call #startListeningForAdvertisements many times
,2016-03-21 13:08:16.789 ThaliTest[1875:3186771] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-21 13:08:16.791 ThaliTest[1875:3186771] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-21 13:08:16.793 ThaliTest[1875:3186771] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-21 13:08:16.796 ThaliTest[1875:3186771] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49354
,2016-03-21 13:08:17.073 ThaliTest[1875:3186771] jxcore: startListeningForAdvertisements
2016-03-21 13:08:17.073 ThaliTest[1875:3186771] multipeer manager: start client restart timer: 0x155c4fc0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-21 13:08:17.076 ThaliTest[1875:3186771] jxcore: startListeningForAdvertisements: success
,ok 169 no errors
,2016-03-21 13:08:17.084 ThaliTest[1875:3186771] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-21 13:08:17.086 ThaliTest[1875:3186771] jxcore: startListeningForAdvertisements: success
,ok 170 still no errors
,# setup
,2016-03-21 13:08:17.203 ThaliTest[1875:3186771] jxcore: stopAdvertisingAndListening
2016-03-21 13:08:17.203 ThaliTest[1875:3186771] THEMultipeerManager stopping peer
2016-03-21 13:08:17.203 ThaliTest[1875:3186771] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-21 13:08:17.204 ThaliTest[1875:3186771] jxcore: stopListeningForAdvertisements
2016-03-21 13:08:17.205 ThaliTest[1875:3186771] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
,2016-03-21 13:08:17.209 ThaliTest[1875:3186771] jxcore: stopListeningForAdvertisements: success
,# 43. should be able to call #startUpdateAdvertisingAndListening many times
,2016-03-21 13:08:17.422 ThaliTest[1875:3186771] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-21 13:08:17.423 ThaliTest[1875:3186771] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-21 13:08:17.424 ThaliTest[1875:3,186771] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-21 13:08:17.427 ThaliTest[1875:3186771] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49356
,2016-03-21 13:08:17.636 ThaliTest[1875:3186771] jxcore: startUpdateAdvertisingAndListening
2016-03-21 13:08:17.636 ThaliTest[1875:3186771] server: starting FE8F9526-AD74-40E1-9080-FD7FA9CC9893:10
2016-03-21 13:08:17.637 ThaliTest[1875:3186771] multipeer ,manager: start client restart timer: 0x155c4fc0
2016-03-21 13:08:17.638 ThaliTest[1875:3186771] THEMultipeerManager initialized peer FE8F9526-AD74-40E1-9080-FD7FA9CC9893:10
2016-03-21 13:08:17.638 ThaliTest[1875:3186771] jxcore: startUpdateAdvertisingAnd,Listening: success
ok 171 no errors
2016-03-21 13:08:17.640 ThaliTest[1875:3186771] jxcore: startUpdateAdvertisingAndListening
2016-03-21 13:08:17.641 ThaliTest[1875:3186771] THEMultipeerManager stopping peer
2016-03-21 13:08:17.641 ThaliTest[1875:3186,771] multipeer manager: stop client timer
2016-03-21 13:08:17.641 ThaliTest[1875:3186771] server: starting FE8F9526-AD74-40E1-9080-FD7FA9CC9893:11
2016-03-21 13:08:17.642 ThaliTest[1875:3186771] multipeer manager: start client restart timer: 0x155c4fc0
,2016-03-21 13:08:17.642 ThaliTest[1875:3186771] THEMultipeerManager initialized peer FE8F9526-AD74-40E1-9080-FD7FA9CC9893:11
2016-03-21 13:08:17.648 ThaliTest[1875:3186771] jxcore: startUpdateAdvertisingAndListening: success
ok 172 still no errors
# setup
,2016-03-21 13:08:17.813 ThaliTest[1875:3186771] jxcore: stopAdvertisingAndListening
,2016-03-21 13:08:17.814 ThaliTest[1875:3186771] THEMultipeerManager stopping peer
,2016-03-21 13:08:17.817 ThaliTest[1875:3186771] multipeer manager: stop client timer
,2016-03-21 13:08:17.819 ThaliTest[1875:3186771] jxcore: stopAdvertisingAndListening: success
,2016-03-21 13:08:17.821 ThaliTest[1875:3186771] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 13:08:17.826 ThaliTest[1875:3186771] jxcore: stopListeningForAdvertisements: success
,# 44. should be able to call #stopAdvertisingAndListening many times
,2016-03-21 13:08:18.521 ThaliTest[1875:3186771] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-21 13:08:18.522 ThaliTest[1875:3186771] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-21 13:08:18.522 ThaliTest[1875:3186771] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-21 13:08:18.525 ThaliTest[1875:3186771] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49360
,2016-03-21 13:08:18.747 ThaliTest[1875:3186771] jxcore: stopAdvertisingAndListening
,2016-03-21 13:08:18.748 ThaliTest[1875:3186771] THEMultipeerManager stopping peer
,2016-03-21 13:08:18.749 ThaliTest[1875:3186771] jxcore: stopAdvertisingAndListening: success
,ok 173 no errors
,2016-03-21 13:08:18.753 ThaliTest[1875:3186771] jxcore: stopAdvertisingAndListening
,2016-03-21 13:08:18.755 ThaliTest[1875:3186771] THEMultipeerManager stopping peer
,2016-03-21 13:08:18.756 ThaliTest[1875:3186771] jxcore: stopAdvertisingAndListening: success
,ok 174 still no errors
,# setup
,2016-03-21 13:08:19.058 ThaliTest[1875:3186771] jxcore: stopAdvertisingAndListening
,2016-03-21 13:08:19.059 ThaliTest[1875:3186771] THEMultipeerManager stopping peer
,2016-03-21 13:08:19.060 ThaliTest[1875:3186771] jxcore: stopAdvertisingAndListening: success
,2016-03-21 13:08:19.062 ThaliTest[1875:3186771] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 13:08:19.065 ThaliTest[1875:3186771] jxcore: stopListeningForAdvertisements: success
,# 45. can get the network status before starting
,2016-03-21 13:08:19.208 ThaliTest[1875:3186771] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-21 13:08:19.210 ThaliTest[1875:3186771] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-21 13:08:19.212 ThaliTest[1875:3186771] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-21 13:08:19.216 ThaliTest[1875:3186771] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,ok 175 network status should have certain non-empty properties
,# setup
,# 46. error returned with bad router
,2016-03-21 13:08:20.644 ThaliTest[1875:3186771] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-21 13:08:20.645 ThaliTest[1875:3186771] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-21 13:08:20.645 ThaliTest[1875:3,186771] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-21 13:08:20.649 ThaliTest[1875:3186771] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
,ok 176 specific error expected
,# setup
,# 47. all services are stopped when we call stop
,2016-03-21 13:08:21.392 ThaliTest[1875:3186771] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-21 13:08:21.395 ThaliTest[1875:3186771] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-21 13:08:21.397 ThaliTest[1875:3186771] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-21 13:08:21.400 ThaliTest[1875:3186771] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49362
,2016-03-21 13:08:21.554 ThaliTest[1875:3186771] jxcore: startListeningForAdvertisements
,2016-03-21 13:08:21.556 ThaliTest[1875:3186771] multipeer manager: start client restart timer: 0x155c4fc0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-21 13:08:21.563 ThaliTest[1875:3186771] jxcore: startListeningForAdvertisements: success
,2016-03-21 13:08:21.567 ThaliTest[1875:3186771] jxcore: startUpdateAdvertisingAndListening
,2016-03-21 13:08:21.568 ThaliTest[1875:3186771] server: starting FE8F9526-AD74-40E1-9080-FD7FA9CC9893:12
,2016-03-21 13:08:21.570 ThaliTest[1875:3186771] THEMultipeerManager initialized peer FE8F9526-AD74-40E1-9080-FD7FA9CC9893:12
,2016-03-21 13:08:21.573 ThaliTest[1875:3186771] jxcore: startUpdateAdvertisingAndListening: success
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,ok 177 connection to servers manager should succeed after starting
,ok 178 connection to router server should succeed after starting
,2016-03-21 13:08:21.626 ThaliTest[1875:3186771] jxcore: stopAdvertisingAndListening
,2016-03-21 13:08:21.627 ThaliTest[1875:3186771] THEMultipeerManager stopping peer
,2016-03-21 13:08:21.629 ThaliTest[1875:3186771] jxcore: stopAdvertisingAndListening: success
,2016-03-21 13:08:21.631 ThaliTest[1875:3186771] jxcore: stopListeningForAdvertisements
,2016-03-21 13:08:21.633 ThaliTest[1875:3186771] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 13:08:21.640 ThaliTest[1875:3186771] jxcore: stopListeningForAdvertisements: success
,DEBUG createNativeListener: mux close
,ok 179 is stopped after calling stop
,DEBUG createNativeListener: incoming socket close
,ok 180 connection to servers manager should fail after stopping
,ok 181 connection to router server should fail after stopping
,# setup
,# 48. make sure terminateConnection is properly hooked up
,2016-03-21 13:08:22.003 ThaliTest[1875:3186771] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-21 13:08:22.005 ThaliTest[1875:3186771] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-21 13:08:22.007 ThaliTest[1875:3186771] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-21 13:08:22.011 ThaliTest[1875:3186771] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,ok 182 called with right arguments
,# setup
,# 49. make sure terminateListener is properly hooked up
,2016-03-21 13:08:22.478 ThaliTest[1875:3186771] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-21 13:08:22.479 ThaliTest[1875:3186771] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-21 13:08:22.480 ThaliTest[1875:3,186771] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-21 13:08:22.482 ThaliTest[1875:3186771] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,ok 183 called with right arguments
,# setup
,# 50. make sure we actually call kill connections properly
,2016-03-21 13:08:22.803 ThaliTest[1875:3186771] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-21 13:08:22.806 ThaliTest[1875:3186771] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-21 13:08:22.808 ThaliTest[1875:3186771] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-21 13:08:22.811 ThaliTest[1875:3186771] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,2016-03-21 13:08:22.875 ThaliTest[1875:3186771] Native method killConnections not found.

```
