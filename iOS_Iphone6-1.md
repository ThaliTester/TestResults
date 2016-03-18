#### Test 62548124b8ccb9f_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/62548124b8ccb9f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/8B17B1C3-575C-4EA7-82BB-4E995AADD905/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/8B17B1C3-575C-4EA7-82BB-4E995AADD905/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/62548124b8ccb9f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/62548124b8ccb9f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0B7AA748-8ED4-4F40-AE62-19D4B2934671/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52756"
,(lldb)     command script import "/tmp/8B17B1C3-575C-4EA7-82BB-4E995AADD905/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-18 17:15:04.555 ThaliTest[1698:2767863] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/45D5176D-83D0-422D-A6F7-5F5BE888A023/Library/Cookies/Cookies.binarycookies
,2016-03-18 17:15:04.893 ThaliTest[1698:2767863] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-18 17:15:04.894 ThaliTest[1698:2767863] Multi-tasking -> Device: YES, App: YES
,2016-03-18 17:15:04.917 ThaliTest[1698:2767863] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-18 17:15:06.841 ThaliTest[1698:2767863] Using UIWebView
,2016-03-18 17:15:06.847 ThaliTest[1698:2767863] [CDVTimer][handleopenurl] 0.358999ms
,2016-03-18 17:15:06.855 ThaliTest[1698:2767863] [CDVTimer][intentandnavigationfilter] 7.389009ms
2016-03-18 17:15:06.856 ThaliTest[1698:2767863] [CDVTimer][gesturehandler] 0.392020ms
2016-03-18 17:15:06.857 ThaliTest[1698:2767863] [CDVTimer][TotalPluginS,tartup] 9.977996ms
,2016-03-18 17:15:14.036 ThaliTest[1698:2767863] Resetting plugins due to page load.
,2016-03-18 17:15:17.925 ThaliTest[1698:2767863] Finished load of: file:///var/mobile/Containers/Bundle/Application/0B7AA748-8ED4-4F40-AE62-19D4B2934671/ThaliTest.app/www/index.html
,2016-03-18 17:15:18.149 ThaliTest[1698:2767863] JXcore Cordova plugin initializing
2016-03-18 17:15:18.151 ThaliTest[1698:2768065] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-18 17:15:25.410 ThaliTest[1698:2768065] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-18 17:15:25.411 ThaliTest[1698:2768065] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-18 17:15:25.411 ThaliTest[1698:2768065] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-18 17:15:25.413 ThaliTest[1698:2768065] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone6-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0B7AA748-8ED4-4F40-AE62-19D4B2934671/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0B7AA748-8ED4-4F40-AE62-19D4B2934671/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0B7AA748-8ED4-4F40-AE62-19D4B2934671/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0B7AA748-8ED4-4F40-AE62-19D4B2934671/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0B7AA748-8ED4-4F40-AE62-19D4B2934671/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0B7AA748-8ED4-4F40-AE62-19D4B2934671/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0B7AA748-8ED4-4F40-AE62-19D4B2934671/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0B7AA748-8ED4-4F40-AE62-19D4B2934671/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0B7AA748-8ED4-4F40-AE62-19D4B2934671/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0B7AA748-8ED4-4F40-AE62-19D4B2934671/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0B7AA748-8ED4-4F40-AE62-19D4B2934671/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0B7AA748-8ED4-4F40-AE62-19D4B2934671/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0B7AA748-8ED4-4F40-AE62-19D4B2934671/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0B7AA748-8ED4-4F40-AE62-19D4B2934671/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0B7AA748-8ED4-4F40-AE62-19D4B2934671/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0B7AA748-8ED4-4F40-AE62-19D4B2934671/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0B7AA748-8ED4-4F40-AE62-19D4B2934671/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0B7AA748-8ED4-4F40-AE62-19D4B2934671/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0B7AA748-8ED4-4F40-AE62-19D4B2934671/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0B7AA748-8ED4-4F40-AE62-19D4B2934671/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-18 17:15:31.297 ThaliTest[1698:2767863] THREAD WARNING: ['JXcore'] took '5567.887939' ms. Plugin should use a background thread.
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 64201
,ok 1 Should throw
,# setup
,# 2. emits incomingConnectionState
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 64203
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
,DEBUG createNativeListener: listening 64206
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
,DEBUG createNativeListener: listening 64212
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
,DEBUG createNativeListener: listening 64217
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
,DEBUG createNativeListener: listening 64221
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
,DEBUG createNativeListener: listening 64225
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
,DEBUG createNativeListener: listening 64229
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
,DEBUG createNativeListener: listening 64233
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
,DEBUG createNativeListener: listening 64285
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
,DEBUG createNativeListener: listening 64289
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
,DEBUG createNativeListener: listening 64301
,2016-03-18 17:18:31.308 ThaliTest[1698:2768065] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-18 17:18:31.311 ThaliTest[1698:2768065] jxcore: stopListeningForAdvertisements: success
,ok 82 error should be null
,ok 83 error should be null
,2016-03-18 17:18:31.318 ThaliTest[1698:2768065] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-18 17:18:31.320 ThaliTest[1698:2768065] jxcore: stopListeningForAdvertisements: success
,ok 84 error should be null
,ok 85 error should be null
,# setup
,2016-03-18 17:18:31.416 ThaliTest[1698:2768065] jxcore: stopAdvertisingAndListening
2016-03-18 17:18:31.417 ThaliTest[1698:2768065] THEMultipeerManager stopping peer
2016-03-18 17:18:31.417 ThaliTest[1698:2768065] jxcore: stopAdvertisingAndListening: success
,2016-03-18 17:18:31.419 ThaliTest[1698:2768065] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-18 17:18:31.421 ThaliTest[1698:2768065] jxcore: stopListeningForAdvertisements: success
,ok 86 error should be null
,ok 87 error should be null
,# 24. should be able to call #startListeningForAdvertisements many times
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 64303
,2016-03-18 17:18:31.632 ThaliTest[1698:2768065] jxcore: startListeningForAdvertisements
,2016-03-18 17:18:31.635 ThaliTest[1698:2768065] multipeer manager: start client restart timer: 0x145f2640
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-18 17:18:31.637 ThaliTest[1698:2768065] jxcore: startListeningForAdvertisements: success
,ok 88 error should be null
,ok 89 error should be null
,2016-03-18 17:18:31.656 ThaliTest[1698:2768065] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-18 17:18:31.659 ThaliTest[1698:2768065] jxcore: startListeningForAdvertisements: success
ok 90 error should be null
,ok 91 error should be null
,# setup
,2016-03-18 17:18:31.932 ThaliTest[1698:2768065] jxcore: stopAdvertisingAndListening
2016-03-18 17:18:31.933 ThaliTest[1698:2768065] THEMultipeerManager stopping peer
2016-03-18 17:18:31.933 ThaliTest[1698:2768065] jxcore: stopAdvertisingAndListening: success
2016-03-18 17:18:31.934 ThaliTest[1698:2768065] jxcore: stopListeningForAdvertisements
,2016-03-18 17:18:31.934 ThaliTest[1698:2768065] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-18 17:18:31.938 ThaliTest[1698:2768065] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 92 error should be null
,ok 93 error should be null
,# 25. should be able to call #startUpdateAdvertisingAndListening many times
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 64305
,2016-03-18 17:18:32.426 ThaliTest[1698:2768065] jxcore: startUpdateAdvertisingAndListening
,2016-03-18 17:18:32.428 ThaliTest[1698:2768065] server: starting A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:1
,2016-03-18 17:18:32.429 ThaliTest[1698:2768065] multipeer manager: start client restart timer: 0x145f2640
2016-03-18 17:18:32.430 ThaliTest[1698:2768065] THEMultipeerManager initialized peer A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:1
,2016-03-18 17:18:32.432 ThaliTest[1698:2768065] jxcore: startUpdateAdvertisingAndListening: success
,ok 94 error should be null
,ok 95 error should be null
,2016-03-18 17:18:32.450 ThaliTest[1698:2768065] jxcore: startUpdateAdvertisingAndListening
2016-03-18 17:18:32.450 ThaliTest[1698:2768065] THEMultipeerManager stopping peer
2016-03-18 17:18:32.451 ThaliTest[1698:2768065] multipeer manager: stop client ti,mer
2016-03-18 17:18:32.451 ThaliTest[1698:2768065] server: starting A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:2
2016-03-18 17:18:32.452 ThaliTest[1698:2768065] multipeer manager: start client restart timer: 0x145f2640
2016-03-18 17:18:32.452 ThaliTest[1698:,2768065] THEMultipeerManager initialized peer A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:2
2016-03-18 17:18:32.453 ThaliTest[1698:2768065] jxcore: startUpdateAdvertisingAndListening: success
,ok 96 error should be null
,ok 97 error should be null
,# setup
,2016-03-18 17:18:33.101 ThaliTest[1698:2768065] jxcore: stopAdvertisingAndListening
2016-03-18 17:18:33.101 ThaliTest[1698:2768065] THEMultipeerManager stopping peer
2016-03-18 17:18:33.102 ThaliTest[1698:2768065] multipeer manager: stop client timer
2016-03-18 17:18:33.102 ThaliTest[1698:2768065] jxcore: stopAdvertisingAndListening: success
,2016-03-18 17:18:33.104 ThaliTest[1698:2768065] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-18 17:18:33.108 ThaliTest[1698:2768065] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 98 error should be null
,ok 99 error should be null
,# 26. should be able to call #stopAdvertisingAndListening many times
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 64310
,2016-03-18 17:18:34.210 ThaliTest[1698:2768065] jxcore: stopAdvertisingAndListening
2016-03-18 17:18:34.211 ThaliTest[1698:2768065] THEMultipeerManager stopping peer
2016-03-18 17:18:34.211 ThaliTest[1698:2768065] jxcore: stopAdvertisingAndListening: success
,ok 100 error should be null
,ok 101 error should be null
,2016-03-18 17:18:34.217 ThaliTest[1698:2768065] jxcore: stopAdvertisingAndListening
2016-03-18 17:18:34.218 ThaliTest[1698:2768065] THEMultipeerManager stopping peer
2016-03-18 17:18:34.218 ThaliTest[1698:2768065] jxcore: stopAdvertisingAndListening: success
ok 102 error should be null
ok 103 error should be null
,# setup
,2016-03-18 17:18:34.611 ThaliTest[1698:2768065] jxcore: stopAdvertisingAndListening
2016-03-18 17:18:34.611 ThaliTest[1698:2768065] THEMultipeerManager stopping peer
2016-03-18 17:18:34.611 ThaliTest[1698:2768065] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-18 17:18:34.612 ThaliTest[1698:2768065] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-18 17:18:34.615 ThaliTest[1698:2768065] jxcore: stopListeningForAdvertisements: success
,ok 104 error should be null
,ok 105 error should be null
,# 27. #start should fail if called twice in a row
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 64312
,ok 106 first call should succeed
,ok 107 first call should succeed
,ok 108 specific error should be returned
,# setup
,2016-03-18 17:18:35.121 ThaliTest[1698:2768065] jxcore: stopAdvertisingAndListening
2016-03-18 17:18:35.121 ThaliTest[1698:2768065] THEMultipeerManager stopping peer
2016-03-18 17:18:35.122 ThaliTest[1698:2768065] jxcore: stopAdvertisingAndListening: success
2016-03-18 17:18:35.122 ThaliTest[1698:2768065] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-18 17:18:35.125 ThaliTest[1698:2768065] jxcore: stopListeningForAdvertisements: success
,ok 109 error should be null
,ok 110 error should be null
,# 28. does not emit duplicate discoveryAdvertisingStateUpdate
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 64314
,2016-03-18 17:18:35.514 ThaliTest[1698:2768065] jxcore: startListeningForAdvertisements
,2016-03-18 17:18:35.516 ThaliTest[1698:2768065] multipeer manager: start client restart timer: 0x145f2640
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-18 17:18:35.518 ThaliTest[1698:2768065] jxcore: startListeningForAdvertisements: success
,2016-03-18 17:18:35.533 ThaliTest[1698:2768065] jxcore: startUpdateAdvertisingAndListening
2016-03-18 17:18:35.533 ThaliTest[1698:2768065] server: starting A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:3
2016-03-18 17:18:35.534 ThaliTest[1698:2768065] THEMultipeerManager initialized peer A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:3
2016-03-18 17:18:35.534 ThaliTest[1698:2768065] jxcore: startUpdateAdvertisingAndListening: success
,ok 111 called only once
,ok 112 discovery state matches
,ok 113 advertising state matches
,# setup
,2016-03-18 17:18:35.669 ThaliTest[1698:2768065] jxcore: stopAdvertisingAndListening
2016-03-18 17:18:35.669 ThaliTest[1698:2768065] THEMultipeerManager stopping peer
2016-03-18 17:18:35.670 ThaliTest[1698:2768065] jxcore: stopAdvertisingAndListening: success
,2016-03-18 17:18:35.673 ThaliTest[1698:2768065] jxcore: stopListeningForAdvertisements
2016-03-18 17:18:35.674 ThaliTest[1698:2768065] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-18 17:18:35.677 ThaliTest[1698:2768065] jxcore: stopListeningForAdvertisements: success
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
,2016-03-18 17:18:42.810 ThaliTest[1698:2768065] jxcore: startListeningForAdvertisements
2016-03-18 17:18:42.811 ThaliTest[1698:2768065] multipeer manager: start client restart timer: 0x145f2640
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-18 17:18:42.814 ThaliTest[1698:2768065] jxcore: startListeningForAdvertisements: success
,ok 129 Can call startListeningForAdvertisements without error
,2016-03-18 17:18:42.818 ThaliTest[1698:2768065] jxcore: stopListeningForAdvertisements
2016-03-18 17:18:42.818 ThaliTest[1698:2768065] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-18 17:18:42.823 ThaliTest[1698:2768065] jxcore: stopListeningForAdvertisements: success
,ok 130 Can call stopListeningForAdvertisements without error
,# setup
,2016-03-18 17:18:43.142 ThaliTest[1698:2768065] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-18 17:18:43.145 ThaliTest[1698:2768065] jxcore: stopListeningForAdvertisements: success
ok 131 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-18 17:18:43.148 ThaliTest[1698:2768065] jxcore: stopAdvertisingAndListening
2016-03-18 17:18:43.148 ThaliTest[1698:2768065] THEMultipeerManager stopping peer
2016-03-18 17:18:43.148 ThaliTest[1698:2768065] jxcore: stopAdvertisingAndListening: suc,cess
ok 132 Should be able to call stopAdvertisingAndListening in teardown
,# 33. Calling startListeningForAdvertisements twice is NOT an error
,# teardown
,2016-03-18 17:18:46.526 ThaliTest[1698:2768065] jxcore: startListeningForAdvertisements
2016-03-18 17:18:46.527 ThaliTest[1698:2768065] multipeer manager: start client restart timer: 0x145f2640
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-18 17:18:46.529 ThaliTest[1698:2768065] jxcore: startListeningForAdvertisements: success
,ok 133 Can call startListeningForAdvertisements without error
2016-03-18 17:18:46.533 ThaliTest[1698:2768065] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-18 17:18:46.538 ThaliTest[1698:2768065] jxcore: startListeningForAdvertisements: success
,ok 134 Can call startListeningForAdvertisements twice without error
,# setup
,2016-03-18 17:18:46.854 ThaliTest[1698:2768065] jxcore: stopListeningForAdvertisements
2016-03-18 17:18:46.855 ThaliTest[1698:2768065] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-18 17:18:46.857 ThaliTest[1698:2768065] jxcore: stopListeningForAdvertisements: success
,ok 135 Should be able to call stopListeningForAdvertisments in teardown
2016-03-18 17:18:46.861 ThaliTest[1698:2768065] jxcore: stopAdvertisingAndListening
2016-03-18 17:18:46.861 ThaliTest[1698:2768065] THEMultipeerManager stopping peer
2016-03-18 17:18:46.861 ThaliTest[1698:2768065] jxcore: stopAdvertisingAndListening: success
ok 136 Should be able to call stopAdvertisingAndListening in teardown
,# 34. Can call start/stopUpdateAdvertisingAndListening
,# teardown
,2016-03-18 17:18:47.442 ThaliTest[1698:2768065] jxcore: startUpdateAdvertisingAndListening
2016-03-18 17:18:47.443 ThaliTest[1698:2768065] server: starting A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:4
2016-03-18 17:18:47.444 ThaliTest[1698:2768065] multipeer m,anager: start client restart timer: 0x145f2640
2016-03-18 17:18:47.444 ThaliTest[1698:2768065] THEMultipeerManager initialized peer A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:4
2016-03-18 17:18:47.445 ThaliTest[1698:2768065] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 137 Can call startUpdateAdvertisingAndListening without error
,2016-03-18 17:18:47.447 ThaliTest[1698:2768065] jxcore: stopAdvertisingAndListening
2016-03-18 17:18:47.447 ThaliTest[1698:2768065] THEMultipeerManager stopping peer
2016-03-18 17:18:47.447 ThaliTest[1698:2768065] multipeer manager: stop client timer
,2016-03-18 17:18:47.448 ThaliTest[1698:2768065] jxcore: stopAdvertisingAndListening: success
,ok 138 Can call stopAdvertisingAndListening without error
# setup
,2016-03-18 17:18:47.819 ThaliTest[1698:2768065] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-18 17:18:47.821 ThaliTest[1698:2768065] jxcore: stopListeningForAdvertisements: success
,ok 139 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-18 17:18:47.824 ThaliTest[1698:2768065] jxcore: stopAdvertisingAndListening
2016-03-18 17:18:47.824 ThaliTest[1698:2768065] THEMultipeerManager stopping peer
2016-03-18 17:18:47.825 ThaliTest[1698:2768065] jxcore: stopAdvertisingAndListening: success
ok 140 Should be able to call stopAdvertisingAndListening in teardown
,# 35. Calling startUpdateAdvertisingAndListening twice is NOT an error
,# teardown
,2016-03-18 17:18:48.353 ThaliTest[1698:2768065] jxcore: startUpdateAdvertisingAndListening
,2016-03-18 17:18:48.354 ThaliTest[1698:2768065] server: starting A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:5
2016-03-18 17:18:48.354 ThaliTest[1698:2768065] multipeer manager: start client restart timer: 0x145f2640
2016-03-18 17:18:48.355 ThaliTest[1698:27680,65] THEMultipeerManager initialized peer A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:5
2016-03-18 17:18:48.355 ThaliTest[1698:2768065] jxcore: startUpdateAdvertisingAndListening: success
ok 141 Can call startUpdateAdvertisingAndListening without error
,2016-03-18 17:18:48.360 ThaliTest[1698:2768065] jxcore: startUpdateAdvertisingAndListening
2016-03-18 17:18:48.360 ThaliTest[1698:2768065] THEMultipeerManager stopping peer
2016-03-18 17:18:48.360 ThaliTest[1698:2768065] multipeer manager: stop client ti,mer
2016-03-18 17:18:48.361 ThaliTest[1698:2768065] server: starting A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:6
2016-03-18 17:18:48.362 ThaliTest[1698:2768065] multipeer manager: start client restart timer: 0x145f2640
2016-03-18 17:18:48.362 ThaliTest[1698:,2768065] THEMultipeerManager initialized peer A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:6
,2016-03-18 17:18:48.362 ThaliTest[1698:2768065] jxcore: startUpdateAdvertisingAndListening: success
ok 142 Can call startUpdateAdvertisingAndListening twice without error
# setup
,2016-03-18 17:18:48.934 ThaliTest[1698:2768065] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-18 17:18:48.937 ThaliTest[1698:2768065] jxcore: stopListeningForAdvertisements: success
ok 143 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-18 17:18:48.939 ThaliTest[1698:2768065] jxcore: stopAdvertisingAndListening
2016-03-18 17:18:48.940 ThaliTest[1698:2768065] THEMultipeerManager stopping peer
2016-03-18 17:18:48.940 ThaliTest[1698:2768065] multipeer manager: stop client timer
2016-03-18 17:18:48.941 ThaliTest[1698:2768065] jxcore: stopAdvertisingAndListening: success
ok 144 Should be able to call stopAdvertisingAndListening in teardown
,# 36. peerAvailabilityChange is called
,# teardown
,2016-03-18 17:18:49.480 ThaliTest[1698:2768065] jxcore: startUpdateAdvertisingAndListening
2016-03-18 17:18:49.481 ThaliTest[1698:2768065] server: starting A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:7
2016-03-18 17:18:49.482 ThaliTest[1698:2768065] multipeer m,anager: start client restart timer: 0x145f2640
2016-03-18 17:18:49.483 ThaliTest[1698:2768065] THEMultipeerManager initialized peer A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:7
2016-03-18 17:18:49.483 ThaliTest[1698:2768065] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 145 Can call startUpdateAdvertisingAndListeningwithout error
2016-03-18 17:18:49.485 ThaliTest[1698:2768065] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
,2016-03-18 17:18:49.489 ThaliTest[1698:2768065] jxcore: startListeningForAdvertisements: success
ok 146 Can call startListeningForAdvertisements without error
,2016-03-18 17:18:50.748 ThaliTest[1698:2767863] client: found new peer: BACBD9D1-23B6-4646-9351-582578E0DABC:7
,ok 147 peers must be an array
,ok 148 peers must not be zero-length
ok 149 peer must have peerIdentifier
,ok 150 peerIdentifier must be a string
,ok 151 peer must have peerAvailable
,ok 152 peer must have pleaseConnect
,# setup
,2016-03-18 17:18:51.044 ThaliTest[1698:2768065] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-18 17:18:51.046 ThaliTest[1698:2768065] jxcore: stopListeningForAdvertisements: success
,ok 153 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-18 17:18:51.049 ThaliTest[1698:2768065] jxcore: stopAdvertisingAndListening
,2016-03-18 17:18:51.050 ThaliTest[1698:2768065] THEMultipeerManager stopping peer
2016-03-18 17:18:51.051 ThaliTest[1698:2768065] multipeer manager: stop client timer
2016-03-18 17:18:51.051 ThaliTest[1698:2768065] jxcore: stopAdvertisingAndListening: success
,ok 154 Should be able to call stopAdvertisingAndListening in teardown
,# 37. Can connect to a remote peer
,# teardown
,2016-03-18 17:19:07.723 ThaliTest[1698:2768065] jxcore: startUpdateAdvertisingAndListening
2016-03-18 17:19:07.723 ThaliTest[1698:2768065] server: starting A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:8
2016-03-18 17:19:07.724 ThaliTest[1698:2768065] multipeer m,anager: start client restart timer: 0x145f2640
2016-03-18 17:19:07.725 ThaliTest[1698:2768065] THEMultipeerManager initialized peer A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:8
2016-03-18 17:19:07.725 ThaliTest[1698:2768065] jxcore: startUpdateAdvertisingAndLi,stening: success
,ok 155 Can call startUpdateAdvertisingAndListening without error
,2016-03-18 17:19:07.729 ThaliTest[1698:2768065] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
,2016-03-18 17:19:07.731 ThaliTest[1698:2768065] jxcore: startListeningForAdvertisements: success
,ok 156 Can call startListeningForAdvertisements without error
,2016-03-18 17:19:08.861 ThaliTest[1698:2767863] client: found new peer: BACBD9D1-23B6-4646-9351-582578E0DABC:8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"BACBD9D1-23B6-4646-9351-582578E0DABC:8","pleaseConnect":0}]
,2016-03-18 17:19:08.869 ThaliTest[1698:2768065] jxcore: connect BACBD9D1-23B6-4646-9351-582578E0DABC:8
2016-03-18 17:19:08.870 ThaliTest[1698:2768065] client: server will connect
2016-03-18 17:19:08.870 ThaliTest[1698:2768065] client session: reverseConnect
2016-03-18 17:19:08.870 ThaliTest[1698:2768065] client session: stateChange:0->1 BACBD9D1-23B6-4646-9351-582578E0DABC:8
,2016-03-18 17:19:10.223 ThaliTest[1698:2767863] multipeer session: reset timer
2016-03-18 17:19:10.224 ThaliTest[1698:2767863] server: rejecting invitation from BACBD9D1-23B6-4646-9351-582578E0DABC due to previous generation (A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:8 != A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:7)
,2016-03-18 17:19:10.581 ThaliTest[1698:2768507] client session: not connected BACBD9D1-23B6-4646-9351-582578E0DABC:8
2016-03-18 17:19:10.582 ThaliTest[1698:2768507] client session: onLinkFailure: BACBD9D1-23B6-4646-9351-582578E0DABC
2016-03-18 17:19:10.5,83 ThaliTest[1698:2768507] client session: disconnect
2016-03-18 17:19:10.583 ThaliTest[1698:2768507] client session: stateChange:1->0 BACBD9D1-23B6-4646-9351-582578E0DABC:8
2016-03-18 17:19:10.584 ThaliTest[1698:2768507] client session: no connect callback (server initiated)
,2016-03-18 17:19:13.374 ThaliTest[1698:2767863] multipeer session: reset timer
2016-03-18 17:19:13.375 ThaliTest[1698:2767863] server: disconnecting to refresh session (BACBD9D1-23B6-4646-9351-582578E0DABC)
2016-03-18 17:19:13.375 ThaliTest[1698:2767863], server: rejecting invitation from BACBD9D1-23B6-4646-9351-582578E0DABC due to previous generation (A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:8 != A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:7)
,2016-03-18 17:19:16.642 ThaliTest[1698:2767863] multipeer session: reset timer
2016-03-18 17:19:16.643 ThaliTest[1698:2767863] server: disconnecting to refresh session (BACBD9D1-23B6-4646-9351-582578E0DABC)
2016-03-18 17:19:16.643 ThaliTest[1698:2767863], server: rejecting invitation from BACBD9D1-23B6-4646-9351-582578E0DABC due to previous generation (A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:8 != A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:7)
,2016-03-18 17:19:18.871 ThaliTest[1698:2767863] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-18 17:19:20.121 ThaliTest[1698:2767863] multipeer session: reset timer
2016-03-18 17:19:20.121 ThaliTest[1698:2767863] server: disconnecting to refresh session (BACBD9D1-23B6-4646-9351-582578E0DABC)
2016-03-18 17:19:20.121 ThaliTest[1698:2767863], server: rejecting invitation from BACBD9D1-23B6-4646-9351-582578E0DABC due to previous generation (A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:8 != A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:7)
,2016-03-18 17:19:21.879 ThaliTest[1698:2768065] jxcore: connect BACBD9D1-23B6-4646-9351-582578E0DABC:8
2016-03-18 17:19:21.880 ThaliTest[1698:2768065] client: server will connect
2016-03-18 17:19:21.880 ThaliTest[1698:2768065] client session: reverseConn,ect
2016-03-18 17:19:21.881 ThaliTest[1698:2768065] client session: stateChange:0->1 BACBD9D1-23B6-4646-9351-582578E0DABC:8
,2016-03-18 17:19:23.253 ThaliTest[1698:2767863] multipeer session: reset timer
2016-03-18 17:19:23.253 ThaliTest[1698:2767863] server: disconnecting to refresh session (BACBD9D1-23B6-4646-9351-582578E0DABC)
2016-03-18 17:19:23.254 ThaliTest[1698:2767863] server: rejecting invitation from BACBD9D1-23B6-4646-9351-582578E0DABC due to previous generation (A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:8 != A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:7)
,2016-03-18 17:19:23.784 ThaliTest[1698:2768532] client session: not connected BACBD9D1-23B6-4646-9351-582578E0DABC:8
2016-03-18 17:19:23.785 ThaliTest[1698:2768532] client session: onLinkFailure: BACBD9D1-23B6-4646-9351-582578E0DABC
,2016-03-18 17:19:23.785 ThaliTest[1698:2768532] client session: disconnect
,2016-03-18 17:19:23.787 ThaliTest[1698:2768532] client session: stateChange:1->0 BACBD9D1-23B6-4646-9351-582578E0DABC:8
2016-03-18 17:19:23.788 ThaliTest[1698:2768532] client session: no connect callback (server initiated)
,2016-03-18 17:19:26.413 ThaliTest[1698:2767863] multipeer session: reset timer
2016-03-18 17:19:26.414 ThaliTest[1698:2767863] server: disconnecting to refresh session (BACBD9D1-23B6-4646-9351-582578E0DABC)
2016-03-18 17:19:26.414 ThaliTest[1698:2767863] server: rejecting invitation from BACBD9D1-23B6-4646-9351-582578E0DABC due to previous generation (A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:8 != A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:7)
,2016-03-18 17:19:27.726 ThaliTest[1698:2767863] multipeer manager: restart client
,2016-03-18 17:19:27.743 ThaliTest[1698:2767863] client: found existing peer: BACBD9D1-23B6-4646-9351-582578E0DABC:8
,2016-03-18 17:19:29.556 ThaliTest[1698:2767863] multipeer session: reset timer
2016-03-18 17:19:29.557 ThaliTest[1698:2767863] server: disconnecting to refresh session (BACBD9D1-23B6-4646-9351-582578E0DABC)
2016-03-18 17:19:29.557 ThaliTest[1698:2767863], server: rejecting invitation from BACBD9D1-23B6-4646-9351-582578E0DABC due to previous generation (A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:8 != A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:7)
,2016-03-18 17:19:31.882 ThaliTest[1698:2767863] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-18 17:19:32.768 ThaliTest[1698:2767863] multipeer session: reset timer
2016-03-18 17:19:32.769 ThaliTest[1698:2767863] server: disconnecting to refresh session (BACBD9D1-23B6-4646-9351-582578E0DABC)
2016-03-18 17:19:32.769 ThaliTest[1698:2767863], server: rejecting invitation from BACBD9D1-23B6-4646-9351-582578E0DABC due to previous generation (A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:8 != A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:7)
,2016-03-18 17:19:34.887 ThaliTest[1698:2768065] jxcore: connect BACBD9D1-23B6-4646-9351-582578E0DABC:8
2016-03-18 17:19:34.888 ThaliTest[1698:2768065] client: server will connect
2016-03-18 17:19:34.888 ThaliTest[1698:2768065] client session: reverseConn,ect
2016-03-18 17:19:34.888 ThaliTest[1698:2768065] client session: stateChange:0->1 BACBD9D1-23B6-4646-9351-582578E0DABC:8
,2016-03-18 17:19:35.347 ThaliTest[1698:2768532] client session: not connected BACBD9D1-23B6-4646-9351-582578E0DABC:8
2016-03-18 17:19:35.349 ThaliTest[1698:2768532] client session: onLinkFailure: BACBD9D1-23B6-4646-9351-582578E0DABC
2016-03-18 17:19:35.3,49 ThaliTest[1698:2768532] client session: disconnect
2016-03-18 17:19:35.349 ThaliTest[1698:2768532] client session: stateChange:1->0 BACBD9D1-23B6-4646-9351-582578E0DABC:8
2016-03-18 17:19:35.350 ThaliTest[1698:2768532] client session: no connect callb,ack (server initiated)
,2016-03-18 17:19:35.874 ThaliTest[1698:2767863] multipeer session: reset timer
2016-03-18 17:19:35.875 ThaliTest[1698:2767863] server: disconnecting to refresh session (BACBD9D1-23B6-4646-9351-582578E0DABC)
2016-03-18 17:19:35.875 ThaliTest[1698:2767863], server: rejecting invitation from BACBD9D1-23B6-4646-9351-582578E0DABC due to previous generation (A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:8 != A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:7)
,2016-03-18 17:19:39.017 ThaliTest[1698:2767863] multipeer session: reset timer
2016-03-18 17:19:39.018 ThaliTest[1698:2767863] server: disconnecting to refresh session (BACBD9D1-23B6-4646-9351-582578E0DABC)
2016-03-18 17:19:39.018 ThaliTest[1698:2767863], server: rejecting invitation from BACBD9D1-23B6-4646-9351-582578E0DABC due to previous generation (A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:8 != A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:7)
,2016-03-18 17:19:44.889 ThaliTest[1698:2767863] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-18 17:19:47.726 ThaliTest[1698:2767863] multipeer manager: restart client
,2016-03-18 17:19:47.744 ThaliTest[1698:2767863] client: found existing peer: BACBD9D1-23B6-4646-9351-582578E0DABC:8
,2016-03-18 17:19:47.900 ThaliTest[1698:2768065] jxcore: connect BACBD9D1-23B6-4646-9351-582578E0DABC:8
2016-03-18 17:19:47.900 ThaliTest[1698:2768065] client: server will connect
2016-03-18 17:19:47.901 ThaliTest[1698:2768065] client session: reverseConn,ect
2016-03-18 17:19:47.901 ThaliTest[1698:2768065] client session: stateChange:0->1 BACBD9D1-23B6-4646-9351-582578E0DABC:8
,2016-03-18 17:19:48.479 ThaliTest[1698:2768605] client session: not connected BACBD9D1-23B6-4646-9351-582578E0DABC:8
2016-03-18 17:19:48.479 ThaliTest[1698:2768605] client session: onLinkFailure: BACBD9D1-23B6-4646-9351-582578E0DABC
2016-03-18 17:19:48.4,79 ThaliTest[1698:2768605] client session: disconnect
,2016-03-18 17:19:48.480 ThaliTest[1698:2768605] client session: stateChange:1->0 BACBD9D1-23B6-4646-9351-582578E0DABC:8
2016-03-18 17:19:48.483 ThaliTest[1698:2768605] client session: no connect callback (server initiated)
,2016-03-18 17:19:57.902 ThaliTest[1698:2767863] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-18 17:20:00.918 ThaliTest[1698:2768065] jxcore: connect BACBD9D1-23B6-4646-9351-582578E0DABC:8
2016-03-18 17:20:00.919 ThaliTest[1698:2768065] client: server will connect
2016-03-18 17:20:00.919 ThaliTest[1698:2768065] client session: reverseConn,ect
2016-03-18 17:20:00.920 ThaliTest[1698:2768065] client session: stateChange:0->1 BACBD9D1-23B6-4646-9351-582578E0DABC:8
,2016-03-18 17:20:01.215 ThaliTest[1698:2768605] client session: not connected BACBD9D1-23B6-4646-9351-582578E0DABC:8
2016-03-18 17:20:01.215 ThaliTest[1698:2768605] client session: onLinkFailure: BACBD9D1-23B6-4646-9351-582578E0DABC
2016-03-18 17:20:01.2,15 ThaliTest[1698:2768605] client session: disconnect
2016-03-18 17:20:01.216 ThaliTest[1698:2768605] client session: stateChange:1->0 BACBD9D1-23B6-4646-9351-582578E0DABC:8
2016-03-18 17:20:01.217 ThaliTest[1698:2768605] client session: no connect callback (server initiated)
,2016-03-18 17:20:07.726 ThaliTest[1698:2767863] multipeer manager: restart client
,2016-03-18 17:20:07.742 ThaliTest[1698:2767863] client: found existing peer: BACBD9D1-23B6-4646-9351-582578E0DABC:8
,2016-03-18 17:20:10.921 ThaliTest[1698:2767863] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-18 17:20:13.928 ThaliTest[1698:2768065] jxcore: connect BACBD9D1-23B6-4646-9351-582578E0DABC:8
2016-03-18 17:20:13.928 ThaliTest[1698:2768065] client: server will connect
2016-03-18 17:20:13.929 ThaliTest[1698:2768065] client session: reverseConnect
2016-03-18 17:20:13.929 ThaliTest[1698:2768065] client session: stateChange:0->1 BACBD9D1-23B6-4646-9351-582578E0DABC:8
,2016-03-18 17:20:14.282 ThaliTest[1698:2768717] client session: not connected BACBD9D1-23B6-4646-9351-582578E0DABC:8
2016-03-18 17:20:14.283 ThaliTest[1698:2768717] client session: onLinkFailure: BACBD9D1-23B6-4646-9351-582578E0DABC
2016-03-18 17:20:14.2,83 ThaliTest[1698:2768717] client session: disconnect
2016-03-18 17:20:14.284 ThaliTest[1698:2768717] client session: stateChange:1->0 BACBD9D1-23B6-4646-9351-582578E0DABC:8
,2016-03-18 17:20:14.286 ThaliTest[1698:2768717] client session: no connect callback (server initiated)
,2016-03-18 17:20:23.930 ThaliTest[1698:2767863] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-18 17:20:26.938 ThaliTest[1698:2768065] jxcore: connect BACBD9D1-23B6-4646-9351-582578E0DABC:8
2016-03-18 17:20:26.939 ThaliTest[1698:2768065] client: server will connect
2016-03-18 17:20:26.940 ThaliTest[1698:2768065] client session: reverseConn,ect
2016-03-18 17:20:26.940 ThaliTest[1698:2768065] client session: stateChange:0->1 BACBD9D1-23B6-4646-9351-582578E0DABC:8
,2016-03-18 17:20:27.726 ThaliTest[1698:2767863] multipeer manager: restart client
,2016-03-18 17:20:27.746 ThaliTest[1698:2767863] client: found existing peer: BACBD9D1-23B6-4646-9351-582578E0DABC:8
,2016-03-18 17:20:36.941 ThaliTest[1698:2767863] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-18 17:20:39.951 ThaliTest[1698:2768065] jxcore: connect BACBD9D1-23B6-4646-9351-582578E0DABC:8
2016-03-18 17:20:39.952 ThaliTest[1698:2768065] client: already connect(ing/ed) to BACBD9D1-23B6-4646-9351-582578E0DABC:8
2016-03-18 17:20:39.952 Thali,Test[1698:2768065] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-18 17:20:42.972 ThaliTest[1698:2768065] jxcore: connect BACBD9D1-23B6-4646-9351-582578E0DABC:8
2016-03-18 17:20:42.973 ThaliTest[1698:2768065] client: already connect(ing/ed) to BACBD9D1-23B6-4646-9351-582578E0DABC:8
2016-03-18 17:20:42.973 ThaliTest[1698:2768065] jxcore: connect: fail: Already connect(ing/ed)
,INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-18 17:20:45.991 ThaliTest[1698:2768065] jxcore: connect BACBD9D1-23B6-4646-9351-582578E0DABC:8
2016-03-18 17:20:45.991 ThaliTest[1698:2768065] client: already connect(ing/ed) to BACBD9D1-23B6-4646-9351-582578E0DABC:8
2016-03-18 17:20:45.992 Thali,Test[1698:2768065] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
WARN testThaliMobileNative: Too many connect retries!
,not ok 157 Connect failed!
,  ---
,    operator: fail
,  ...
,# setup
,2016-03-18 17:20:46.223 ThaliTest[1698:2768065] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-18 17:20:46.226 ThaliTest[1698:2768065] jxcore: stopListeningForAdvertisements: success
,ok 158 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-18 17:20:46.229 ThaliTest[1698:2768065] jxcore: stopAdvertisingAndListening
2016-03-18 17:20:46.229 ThaliTest[1698:2768065] THEMultipeerManager stopping peer
2016-03-18 17:20:46.230 ThaliTest[1698:2768065] client session: disconnect
2016-03-18 1,7:20:46.230 ThaliTest[1698:2768065] client session: stateChange:1->0 BACBD9D1-23B6-4646-9351-582578E0DABC:8
2016-03-18 17:20:46.231 ThaliTest[1698:2768065] multipeer manager: stop client timer
2016-03-18 17:20:46.231 ThaliTest[1698:2768065] jxcore: stopA,dvertisingAndListening: success
ok 159 Should be able to call stopAdvertisingAndListening in teardown
,# 38. Can shift large amounts of data
,# teardown
,2016-03-18 17:20:48.564 ThaliTest[1698:2768065] jxcore: startUpdateAdvertisingAndListening
2016-03-18 17:20:48.565 ThaliTest[1698:2768065] server: starting A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:9
2016-03-18 17:20:48.565 ThaliTest[1698:2768065] multipeer manager: start client restart timer: 0x145f2640
2016-03-18 17:20:48.565 ThaliTest[1698:2768065] THEMultipeerManager initialized peer A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:9
2016-03-18 17:20:48.565 ThaliTest[1698:2768065] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 160 Can call startUpdateAdvertisingAndListening without error
2016-03-18 17:20:48.566 ThaliTest[1698:2768065] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-18 17:20:48.567 ThaliTest[1698:2768065] jxcore: startListeningForAdvertisements: success
ok 161 Can call startListeningForAdvertisements without error
,2016-03-18 17:20:49.261 ThaliTest[1698:2767863] client: found new peer: BACBD9D1-23B6-4646-9351-582578E0DABC:8
2016-03-18 17:20:49.263 ThaliTest[1698:2768065] jxcore: connect BACBD9D1-23B6-4646-9351-582578E0DABC:8
2016-03-18 17:20:49.264 ThaliTest[1698:2,768065] client: server will connect
2016-03-18 17:20:49.264 ThaliTest[1698:2768065] client session: reverseConnect
2016-03-18 17:20:49.264 ThaliTest[1698:2768065] client session: stateChange:0->1 BACBD9D1-23B6-4646-9351-582578E0DABC:8
,2016-03-18 17:20:50.653 ThaliTest[1698:2767863] multipeer session: reset timer
2016-03-18 17:20:50.654 ThaliTest[1698:2767863] server: rejecting invitation from BACBD9D1-23B6-4646-9351-582578E0DABC due to previous generation (A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:9 != A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:8)
,2016-03-18 17:20:51.143 ThaliTest[1698:2768794] client session: not connected BACBD9D1-23B6-4646-9351-582578E0DABC:8
2016-03-18 17:20:51.143 ThaliTest[1698:2768794] client session: onLinkFailure: BACBD9D1-23B6-4646-9351-582578E0DABC
2016-03-18 17:20:51.1,43 ThaliTest[1698:2768794] client session: disconnect
2016-03-18 17:20:51.144 ThaliTest[1698:2768794] client session: stateChange:1->0 BACBD9D1-23B6-4646-9351-582578E0DABC:8
,2016-03-18 17:20:51.147 ThaliTest[1698:2768794] client session: no connect callback (server initiated)
,2016-03-18 17:20:54.289 ThaliTest[1698:2767863] multipeer session: reset timer
2016-03-18 17:20:54.289 ThaliTest[1698:2767863] server: disconnecting to refresh session (BACBD9D1-23B6-4646-9351-582578E0DABC)
2016-03-18 17:20:54.290 ThaliTest[1698:2767863], server: rejecting invitation from BACBD9D1-23B6-4646-9351-582578E0DABC due to previous generation (A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:9 != A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:8)
,2016-03-18 17:20:57.612 ThaliTest[1698:2767863] multipeer session: reset timer
2016-03-18 17:20:57.613 ThaliTest[1698:2767863] server: disconnecting to refresh session (BACBD9D1-23B6-4646-9351-582578E0DABC)
2016-03-18 17:20:57.613 ThaliTest[1698:2767863], server: rejecting invitation from BACBD9D1-23B6-4646-9351-582578E0DABC due to previous generation (A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:9 != A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:8)
,2016-03-18 17:20:59.265 ThaliTest[1698:2767863] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-18 17:21:00.809 ThaliTest[1698:2767863] multipeer session: reset timer
2016-03-18 17:21:00.809 ThaliTest[1698:2767863] server: disconnecting to refresh session (BACBD9D1-23B6-4646-9351-582578E0DABC)
2016-03-18 17:21:00.809 ThaliTest[1698:2767863], server: rejecting invitation from BACBD9D1-23B6-4646-9351-582578E0DABC due to previous generation (A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:9 != A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:8)
,2016-03-18 17:21:02.280 ThaliTest[1698:2768065] jxcore: connect BACBD9D1-23B6-4646-9351-582578E0DABC:8
2016-03-18 17:21:02.281 ThaliTest[1698:2768065] client: server will connect
2016-03-18 17:21:02.281 ThaliTest[1698:2768065] client session: reverseConnect
2016-03-18 17:21:02.282 ThaliTest[1698:2768065] client session: stateChange:0->1 BACBD9D1-23B6-4646-9351-582578E0DABC:8
,2016-03-18 17:21:02.558 ThaliTest[1698:2768798] client session: not connected BACBD9D1-23B6-4646-9351-582578E0DABC:8
2016-03-18 17:21:02.558 ThaliTest[1698:2768798] client session: onLinkFailure: BACBD9D1-23B6-4646-9351-582578E0DABC
2016-03-18 17:21:02.559 ThaliTest[1698:2768798] client session: disconnect
,2016-03-18 17:21:02.559 ThaliTest[1698:2768798] client session: stateChange:1->0 BACBD9D1-23B6-4646-9351-582578E0DABC:8
,2016-03-18 17:21:02.563 ThaliTest[1698:2768798] client session: no connect callback (server initiated)
,2016-03-18 17:21:03.979 ThaliTest[1698:2767863] multipeer session: reset timer
2016-03-18 17:21:03.980 ThaliTest[1698:2767863] server: disconnecting to refresh session (BACBD9D1-23B6-4646-9351-582578E0DABC)
2016-03-18 17:21:03.980 ThaliTest[1698:2767863], server: rejecting invitation from BACBD9D1-23B6-4646-9351-582578E0DABC due to previous generation (A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:9 != A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:8)
,2016-03-18 17:21:07.139 ThaliTest[1698:2767863] multipeer session: reset timer
,2016-03-18 17:21:07.140 ThaliTest[1698:2767863] server: disconnecting to refresh session (BACBD9D1-23B6-4646-9351-582578E0DABC)
,2016-03-18 17:21:07.141 ThaliTest[1698:2767863] server: rejecting invitation from BACBD9D1-23B6-4646-9351-582578E0DABC due to previous generation (A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:9 != A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:8)
,2016-03-18 17:21:08.567 ThaliTest[1698:2767863] multipeer manager: restart client
,2016-03-18 17:21:08.584 ThaliTest[1698:2767863] client: found updated peer: BACBD9D1-23B6-4646-9351-582578E0DABC:9
,2016-03-18 17:21:10.652 ThaliTest[1698:2767863] multipeer session: reset timer
2016-03-18 17:21:10.652 ThaliTest[1698:2767863] server: disconnecting to refresh session (BACBD9D1-23B6-4646-9351-582578E0DABC)
2016-03-18 17:21:10.652 ThaliTest[1698:2767863], server: rejecting invitation from BACBD9D1-23B6-4646-9351-582578E0DABC due to previous generation (A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:9 != A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:8)
,2016-03-18 17:21:12.283 ThaliTest[1698:2767863] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-18 17:21:13.871 ThaliTest[1698:2767863] multipeer session: reset timer
2016-03-18 17:21:13.871 ThaliTest[1698:2767863] server: disconnecting to refresh session (BACBD9D1-23B6-4646-9351-582578E0DABC)
2016-03-18 17:21:13.871 ThaliTest[1698:2767863] server: rejecting invitation from BACBD9D1-23B6-4646-9351-582578E0DABC due to previous generation (A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:9 != A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:8)
,2016-03-18 17:21:15.300 ThaliTest[1698:2768065] jxcore: connect BACBD9D1-23B6-4646-9351-582578E0DABC:8
2016-03-18 17:21:15.301 ThaliTest[1698:2768065] client: server will connect
2016-03-18 17:21:15.302 ThaliTest[1698:2768065] client session: reverseConn,ect
2016-03-18 17:21:15.302 ThaliTest[1698:2768065] client session: stateChange:0->1 BACBD9D1-23B6-4646-9351-582578E0DABC:9
,2016-03-18 17:21:16.207 ThaliTest[1698:2768775] client session: not connected BACBD9D1-23B6-4646-9351-582578E0DABC:9
2016-03-18 17:21:16.208 ThaliTest[1698:2768775] client session: onLinkFailure: BACBD9D1-23B6-4646-9351-582578E0DABC
,2016-03-18 17:21:16.208 ThaliTest[1698:2768775] client session: disconnect
,2016-03-18 17:21:16.210 ThaliTest[1698:2768775] client session: stateChange:1->0 BACBD9D1-23B6-4646-9351-582578E0DABC:9
,2016-03-18 17:21:16.212 ThaliTest[1698:2768775] client session: no connect callback (server initiated)
,2016-03-18 17:21:17.078 ThaliTest[1698:2767863] multipeer session: reset timer
2016-03-18 17:21:17.079 ThaliTest[1698:2767863] server: disconnecting to refresh session (BACBD9D1-23B6-4646-9351-582578E0DABC)
2016-03-18 17:21:17.079 ThaliTest[1698:2767863], server: rejecting invitation from BACBD9D1-23B6-4646-9351-582578E0DABC due to previous generation (A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:9 != A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:8)
,2016-03-18 17:21:20.219 ThaliTest[1698:2767863] multipeer session: reset timer
2016-03-18 17:21:20.219 ThaliTest[1698:2767863] server: disconnecting to refresh session (BACBD9D1-23B6-4646-9351-582578E0DABC)
,2016-03-18 17:21:20.219 ThaliTest[1698:2767863] server: rejecting invitation from BACBD9D1-23B6-4646-9351-582578E0DABC due to previous generation (A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:9 != A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:8)
,2016-03-18 17:21:25.303 ThaliTest[1698:2767863] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-18 17:21:28.317 ThaliTest[1698:2768065] jxcore: connect BACBD9D1-23B6-4646-9351-582578E0DABC:8
2016-03-18 17:21:28.318 ThaliTest[1698:2768065] client: server will connect
2016-03-18 17:21:28.318 ThaliTest[1698:2768065] client session: reverseConnect
,2016-03-18 17:21:28.319 ThaliTest[1698:2768065] client session: stateChange:0->1 BACBD9D1-23B6-4646-9351-582578E0DABC:9
,2016-03-18 17:21:28.566 ThaliTest[1698:2767863] multipeer manager: restart client
,2016-03-18 17:21:28.589 ThaliTest[1698:2767863] client: found existing peer: BACBD9D1-23B6-4646-9351-582578E0DABC:9
,2016-03-18 17:21:38.319 ThaliTest[1698:2767863] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-18 17:21:41.331 ThaliTest[1698:2768065] jxcore: connect BACBD9D1-23B6-4646-9351-582578E0DABC:8
2016-03-18 17:21:41.332 ThaliTest[1698:2768065] client: already connect(ing/ed) to BACBD9D1-23B6-4646-9351-582578E0DABC:8
2016-03-18 17:21:41.332 Thali,Test[1698:2768065] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-18 17:21:44.343 ThaliTest[1698:2768065] jxcore: connect BACBD9D1-23B6-4646-9351-582578E0DABC:8
2016-03-18 17:21:44.343 ThaliTest[1698:2768065] client: already connect(ing/ed) to BACBD9D1-23B6-4646-9351-582578E0DABC:8
2016-03-18 17:21:44.344 Thali,Test[1698:2768065] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-18 17:21:47.356 ThaliTest[1698:2768065] jxcore: connect BACBD9D1-23B6-4646-9351-582578E0DABC:8
2016-03-18 17:21:47.357 ThaliTest[1698:2768065] client: already connect(ing/ed) to BACBD9D1-23B6-4646-9351-582578E0DABC:8
2016-03-18 17:21:47.357 Thali,Test[1698:2768065] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-18 17:21:48.567 ThaliTest[1698:2767863] multipeer manager: restart client
,2016-03-18 17:21:48.583 ThaliTest[1698:2767863] client: found existing peer: BACBD9D1-23B6-4646-9351-582578E0DABC:9
,2016-03-18 17:21:50.378 ThaliTest[1698:2768065] jxcore: connect BACBD9D1-23B6-4646-9351-582578E0DABC:8
2016-03-18 17:21:50.379 ThaliTest[1698:2768065] client: already connect(ing/ed) to BACBD9D1-23B6-4646-9351-582578E0DABC:8
2016-03-18 17:21:50.379 ThaliTest[1698:2768065] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-18 17:21:53.393 ThaliTest[1698:2768065] jxcore: connect BACBD9D1-23B6-4646-9351-582578E0DABC:8
2016-03-18 17:21:53.394 ThaliTest[1698:2768065] client: already connect(ing/ed) to BACBD9D1-23B6-4646-9351-582578E0DABC:8
2016-03-18 17:21:53.394 Thali,Test[1698:2768065] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-18 17:21:56.404 ThaliTest[1698:2768065] jxcore: connect BACBD9D1-23B6-4646-9351-582578E0DABC:8
2016-03-18 17:21:56.405 ThaliTest[1698:2768065] client: already connect(ing/ed) to BACBD9D1-23B6-4646-9351-582578E0DABC:8
2016-03-18 17:21:56.405 Thali,Test[1698:2768065] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,WARN testThaliMobileNative: Too many connect retries!
,not ok 162 Connect failed!
  ---
,    operator: fail
,  ...
,# setup
,2016-03-18 17:21:56.510 ThaliTest[1698:2768065] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-18 17:21:56.512 ThaliTest[1698:2768065] jxcore: stopListeningForAdvertisements: success
ok 163 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-18 17:21:56.515 ThaliTest[1698:2768065] jxcore: stopAdvertisingAndListening
2016-03-18 17:21:56.515 ThaliTest[1698:2768065] THEMultipeerManager stopping peer
2016-03-18 17:21:56.516 ThaliTest[1698:2768065] client session: disconnect
2016-03-18 1,7:21:56.516 ThaliTest[1698:2768065] client session: stateChange:1->0 BACBD9D1-23B6-4646-9351-582578E0DABC:9
2016-03-18 17:21:56.517 ThaliTest[1698:2768065] multipeer manager: stop client timer
2016-03-18 17:21:56.517 ThaliTest[1698:2768065] jxcore: stopA,dvertisingAndListening: success
ok 164 Should be able to call stopAdvertisingAndListening in teardown
,# 39. #startListeningForAdvertisements should fail if start not called
,2016-03-18 17:21:57.208 ThaliTest[1698:2768065] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-18 17:21:57.209 ThaliTest[1698:2768065] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-18 17:21:57.210 ThaliTest[1698:2,768065] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-18 17:21:57.213 ThaliTest[1698:2768065] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,ok 165 specific error should be returned
,# setup
,# 40. #startUpdateAdvertisingAndListening should fail if start not called
,2016-03-18 17:21:58.612 ThaliTest[1698:2768065] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-18 17:21:58.613 ThaliTest[1698:2768065] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-18 17:21:58.614 ThaliTest[1698:2,768065] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-18 17:21:58.617 ThaliTest[1698:2768065] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,ok 166 specific error should be returned
,# setup
,# 41. should be able to call #stopListeningForAdvertisements many times
,2016-03-18 17:21:59.093 ThaliTest[1698:2768065] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-18 17:21:59.094 ThaliTest[1698:2768065] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-18 17:21:59.095 ThaliTest[1698:2768065] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-18 17:21:59.098 ThaliTest[1698:2768065] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 64357
,2016-03-18 17:21:59.262 ThaliTest[1698:2768065] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-18 17:21:59.264 ThaliTest[1698:2768065] jxcore: stopListeningForAdvertisements: success
,ok 167 no errors
,2016-03-18 17:21:59.267 ThaliTest[1698:2768065] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-18 17:21:59.269 ThaliTest[1698:2768065] jxcore: stopListeningForAdvertisements: success
,ok 168 still no errors
,# setup
,2016-03-18 17:21:59.510 ThaliTest[1698:2768065] jxcore: stopAdvertisingAndListening
,2016-03-18 17:21:59.512 ThaliTest[1698:2768065] THEMultipeerManager stopping peer
,2016-03-18 17:21:59.513 ThaliTest[1698:2768065] jxcore: stopAdvertisingAndListening: success
,2016-03-18 17:21:59.515 ThaliTest[1698:2768065] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-18 17:21:59.520 ThaliTest[1698:2768065] jxcore: stopListeningForAdvertisements: success
,# 42. should be able to call #startListeningForAdvertisements many times
,2016-03-18 17:21:59.610 ThaliTest[1698:2768065] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-18 17:21:59.611 ThaliTest[1698:2768065] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-18 17:21:59.612 ThaliTest[1698:2768065] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-18 17:21:59.615 ThaliTest[1698:2768065] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 64359
,2016-03-18 17:21:59.742 ThaliTest[1698:2768065] jxcore: startListeningForAdvertisements
,2016-03-18 17:21:59.744 ThaliTest[1698:2768065] multipeer manager: start client restart timer: 0x145f2640
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-18 17:21:59.752 ThaliTest[1698:2768065] jxcore: startListeningForAdvertisements: success
,ok 169 no errors
,2016-03-18 17:21:59.757 ThaliTest[1698:2768065] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-18 17:21:59.759 ThaliTest[1698:2768065] jxcore: startListeningForAdvertisements: success
,ok 170 still no errors
,# setup
,2016-03-18 17:21:59.862 ThaliTest[1698:2768065] jxcore: stopAdvertisingAndListening
,2016-03-18 17:21:59.864 ThaliTest[1698:2768065] THEMultipeerManager stopping peer
,2016-03-18 17:21:59.865 ThaliTest[1698:2768065] jxcore: stopAdvertisingAndListening: success
,2016-03-18 17:21:59.867 ThaliTest[1698:2768065] jxcore: stopListeningForAdvertisements
,2016-03-18 17:21:59.869 ThaliTest[1698:2768065] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-18 17:21:59.876 ThaliTest[1698:2768065] jxcore: stopListeningForAdvertisements: success
,# 43. should be able to call #startUpdateAdvertisingAndListening many times
,2016-03-18 17:22:00.132 ThaliTest[1698:2768065] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-18 17:22:00.134 ThaliTest[1698:2768065] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-18 17:22:00.136 ThaliTest[1698:2768065] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-18 17:22:00.140 ThaliTest[1698:2768065] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 64361
,2016-03-18 17:22:00.242 ThaliTest[1698:2768065] jxcore: startUpdateAdvertisingAndListening
,2016-03-18 17:22:00.243 ThaliTest[1698:2768065] server: starting A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:10
,2016-03-18 17:22:00.246 ThaliTest[1698:2768065] multipeer manager: start client restart timer: 0x145f2640
,2016-03-18 17:22:00.253 ThaliTest[1698:2768065] THEMultipeerManager initialized peer A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:10
,2016-03-18 17:22:00.255 ThaliTest[1698:2768065] jxcore: startUpdateAdvertisingAndListening: success
2016-03-18 17:22:00.257 ThaliTest[1698:2767863] client: found new peer: BACBD9D1-23B6-4646-9351-582578E0DABC:9
,ok 171 no errors
,2016-03-18 17:22:00.263 ThaliTest[1698:2768065] jxcore: startUpdateAdvertisingAndListening
,2016-03-18 17:22:00.264 ThaliTest[1698:2768065] THEMultipeerManager stopping peer
,2016-03-18 17:22:00.267 ThaliTest[1698:2768065] multipeer manager: stop client timer
,2016-03-18 17:22:00.269 ThaliTest[1698:2768065] server: starting A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:11
,2016-03-18 17:22:00.270 ThaliTest[1698:2768065] multipeer manager: start client restart timer: 0x145f2640
,2016-03-18 17:22:00.274 ThaliTest[1698:2768065] THEMultipeerManager initialized peer A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:11
,2016-03-18 17:22:00.278 ThaliTest[1698:2767863] client: found new peer: BACBD9D1-23B6-4646-9351-582578E0DABC:9
,2016-03-18 17:22:00.276 ThaliTest[1698:2768065] jxcore: startUpdateAdvertisingAndListening: success
,ok 172 still no errors
,# setup
,2016-03-18 17:22:00.541 ThaliTest[1698:2768065] jxcore: stopAdvertisingAndListening
2016-03-18 17:22:00.542 ThaliTest[1698:2768065] THEMultipeerManager stopping peer
2016-03-18 17:22:00.542 ThaliTest[1698:2768065] multipeer manager: stop client timer
2016-03-18 17:22:00.543 ThaliTest[1698:2768065] jxcore: stopAdvertisingAndListening: success
2016-03-18 17:22:00.544 ThaliTest[1698:2768065] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-18 17:22:00.547 ThaliTest[1698:2768065] jxcore: stopListeningForAdvertisements: success
,# 44. should be able to call #stopAdvertisingAndListening many times
,2016-03-18 17:22:00.730 ThaliTest[1698:2768065] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-18 17:22:00.732 ThaliTest[1698:2768065] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-18 17:22:00.734 ThaliTest[1698:2768065] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-18 17:22:00.738 ThaliTest[1698:2768065] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 64365
,2016-03-18 17:22:00.951 ThaliTest[1698:2768065] jxcore: stopAdvertisingAndListening
,2016-03-18 17:22:00.952 ThaliTest[1698:2768065] THEMultipeerManager stopping peer
,2016-03-18 17:22:00.953 ThaliTest[1698:2768065] jxcore: stopAdvertisingAndListening: success
,ok 173 no errors
,2016-03-18 17:22:00.957 ThaliTest[1698:2768065] jxcore: stopAdvertisingAndListening
,2016-03-18 17:22:00.959 ThaliTest[1698:2768065] THEMultipeerManager stopping peer
,2016-03-18 17:22:00.960 ThaliTest[1698:2768065] jxcore: stopAdvertisingAndListening: success
,ok 174 still no errors
,# setup
,2016-03-18 17:22:01.199 ThaliTest[1698:2768065] jxcore: stopAdvertisingAndListening
2016-03-18 17:22:01.200 ThaliTest[1698:2768065] THEMultipeerManager stopping peer
2016-03-18 17:22:01.200 ThaliTest[1698:2768065] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-18 17:22:01.201 ThaliTest[1698:2768065] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-18 17:22:01.203 ThaliTest[1698,:2768065] jxcore: stopListeningForAdvertisements: success
,# 45. can get the network status before starting
,2016-03-18 17:22:01.341 ThaliTest[1698:2768065] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-18 17:22:01.342 ThaliTest[1698:2768065] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-18 17:22:01.343 ThaliTest[1698:2,768065] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-18 17:22:01.346 ThaliTest[1698:2768065] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,ok 175 network status should have certain non-empty properties
,# setup
,# 46. error returned with bad router
,2016-03-18 17:22:01.816 ThaliTest[1698:2768065] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-18 17:22:01.819 ThaliTest[1698:2768065] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-18 17:22:01.821 ThaliTest[1698:2768065] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-18 17:22:01.824 ThaliTest[1698:2768065] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
,ok 176 specific error expected
,# setup
,# 47. can do HTTP requests between peers
,2016-03-18 17:22:03.384 ThaliTest[1698:2768065] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-18 17:22:03.385 ThaliTest[1698:2768065] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-18 17:22:03.386 ThaliTest[1698:2768065] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-18 17:22:03.390 ThaliTest[1698:2768065] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 64367
,2016-03-18 17:22:03.489 ThaliTest[1698:2768065] jxcore: startListeningForAdvertisements
2016-03-18 17:22:03.490 ThaliTest[1698:2768065] multipeer manager: start client restart timer: 0x145f2640
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-18 17:22:03.492 ThaliTest[1698:2768065] jxcore: startListeningForAdvertisements: success
,2016-03-18 17:22:03.496 ThaliTest[1698:2768065] jxcore: startUpdateAdvertisingAndListening
2016-03-18 17:22:03.496 ThaliTest[1698:2768065] server: starting A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:12
2016-03-18 17:22:03.497 ThaliTest[1698:2768065] THEMultipeerManager initialized peer A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:12
2016-03-18 17:22:03.499 ThaliTest[1698:2768065] jxcore: startUpdateAdvertisingAndListening: success
,2016-03-18 17:22:04.649 ThaliTest[1698:2767863] client: found new peer: BACBD9D1-23B6-4646-9351-582578E0DABC:9
,DEBUG createPeerListener: createPeerListener
,DEBUG createPeerListener: pleaseConnect= 0
,ok 177 found a peer! {"peerIdentifier":"BACBD9D1-23B6-4646-9351-582578E0DABC:9","portNumber":64369,"hostAddress":"127.0.0.1"}
,DEBUG createPeerListener: first connection
,2016-03-18 17:22:04.707 ThaliTest[1698:2768065] jxcore: connect BACBD9D1-23B6-4646-9351-582578E0DABC:9
2016-03-18 17:22:04.708 ThaliTest[1698:2768065] client: server will connect
2016-03-18 17:22:04.708 ThaliTest[1698:2768065] client session: reverseConn,ect
2016-03-18 17:22:04.708 ThaliTest[1698:2768065] client session: stateChange:0->1 BACBD9D1-23B6-4646-9351-582578E0DABC:9
,2016-03-18 17:22:05.762 ThaliTest[1698:2767863] multipeer session: reset timer
2016-03-18 17:22:05.763 ThaliTest[1698:2767863] server: rejecting invitation from BACBD9D1-23B6-4646-9351-582578E0DABC due to previous generation (A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:12 != A0B596A0-9D5B-4BB0-9F2D-C70AA0F20E28:9)
,2016-03-18 17:22:06.061 ThaliTest[1698:2768775] client session: not connected BACBD9D1-23B6-4646-9351-582578E0DABC:9
2016-03-18 17:22:06.063 ThaliTest[1698:2768775] client session: onLinkFailure: BACBD9D1-23B6-4646-9351-582578E0DABC
2016-03-18 17:22:06.0,63 ThaliTest[1698:2768775] client session: disconnect
2016-03-18 17:22:06.064 ThaliTest[1698:2768775] client session: stateChange:1->0 BACBD9D1-23B6-4646-9351-582578E0DABC:9
2016-03-18 17:22:06.064 ThaliTest[1698:2768775] client session: no connect callback (server initiated)
,not ok 178 Error: ESOCKETTIMEDOUT
,  ---
,    operator: fail
,  ...
,# setup
,2016-03-18 17:22:09.818 ThaliTest[1698:2768065] jxcore: stopAdvertisingAndListening
2016-03-18 17:22:09.818 ThaliTest[1698:2768065] THEMultipeerManager stopping peer
2016-03-18 17:22:09.819 ThaliTest[1698:2768065] jxcore: stopAdvertisingAndListening: success
2016-03-18 17:22:09.819 ThaliTest[1698:2768065] jxcore: stopListeningForAdvertisements
2016-03-18 17:22:09.820 ThaliTest[1698:2768065] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-18 17:22:09.823 ThaliTest[1698:2768065] jxcore: stopListeningForAdvertisements: success
,# 48. Can do requests between peers after start and stop
,2016-03-18 17:22:10.685 ThaliTest[1698:2768065] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-18 17:22:10.686 ThaliTest[1698:2768065] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-18 17:22:10.687 ThaliTest[1698:2,768065] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-18 17:22:10.690 ThaliTest[1698:2768065] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,ok 179 (unnamed assert)
,# setup
,# 49. We successfully receive and replay discoveryAdvertisingStateUpdate
,2016-03-18 17:22:11.299 ThaliTest[1698:2768065] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-18 17:22:11.300 ThaliTest[1698:2768065] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-18 17:22:11.301 ThaliTest[1698:2,768065] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-18 17:22:11.304 ThaliTest[1698:2768065] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,ok 180 (unnamed assert)
,# setup
,# 50. Test BEACONS_RETRIEVED_AND_PARSED locally
,# teardown
,ok 181 peerIdentifier should be hello
,ok 182 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 183 good beacon
,ok 184 good preAmble
,ok 185 public keys match!
,ok 186 must return null after successful call
,# setup
,# 51. Test HTTP_BAD_RESPONSE locally
,# teardown
,ok 187 Response should be HTTP_BAD_RESPONSE
,ok 188 must return null after successful call
,# setup
,# 52. Test NETWORK_PROBLEM locally
,2016-03-18 17:22:14.709 ThaliTest[1698:2767863] jxcore: connect: fail: Timed out awaiting reverse connection
,WARN createPeerListener: 
,DEBUG createPeerListener: failedConnection
,DEBUG createPeerListener: failed incoming connection because of mux promise failueTimed out awaiting reverse connection
,# teardown
,ok 189 Response should be NETWORK_PROBLEM
,ok 190 reject reason should be: Could not establish TCP connection
,# setup
,# 53. Test timeout locally
,# teardown
,ok 191 Should be NETWORK_PROBLEM caused by timeout
,ok 192 reject reason should be Could not establish TCP connection
,# setup
,# 54. Call the start two times
,# teardown
,ok 193 Call start once
,ok 194 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 195 must return null after successful call.
,# setup
,# 55. Call the kill before calling the start
,# teardown
,ok 196 Should be Killed
,ok 197 Start after killed
,# setup
,# 56. Call the kill immediately after the start
,# teardown
,ok 198 Should be KILLED
,ok 199 must return null after successful kill
,# setup
,# 57. Call the kill while waiting a response from the server
,# teardown
,ok 200 Should be KILLED
,ok 201 must return null after successful kill
,# setup
,# 58. Test to exceed the max content size locally
,# teardown
,ok 202 HTTP_BAD_RESPONSE should be response when content size is exceeded
,ok 203 must return null after successful call
,# setup
,# 59. Close the server socket while the client is waiting a response from the server. Local test.
,# teardown
,ok 204 Should be NETWORK_PROBLEM caused closing server socket
,ok 205 Should be Could not establish TCP connection
,# setup
,# 60. Close the client socket while the client is waiting a response from the server. Local test.
,# teardown
,ok 206 Should be NETWORK_PROBLEM caused closing client socket
,ok 207 Should be Could not establish TCP connection
,# setup
,# 61. #generatePreambleAndBeacons bad args
,# teardown
,ok 208 publicKeysToNotify cannot be null
,ok 209 ecdh for local device cannot be null
,ok 210 milliseconds cannot be less than 0
,ok 211 milliseconds cannot be 0
,ok 212 milliseconds cannot be greater than one_day
,# setup
,# 62. #generatePreambleAndBeacons empty keys to notify
,# teardown
,ok 213 should be equal
,# setup
,# 63. #generatePreambleAndBeacons multiple keys to notify
,# teardown
,ok 214 should be equal
ok 215 should be equal
,ok 216 (unnamed assert)
,ok 217 should be equal
,# setup
,# 64. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
,# teardown
,ok 218 should throw
,# setup
,# 65. #parseBeacons invalid expiration in beaconStreamWithPreAmble
,# teardown
,ok 219 Preamble expiration must be a 64 bit integer
,# setup
,# 66. #parseBeacons expiration out of range lower
,# teardown
,ok 220 Expiration out of range
,# setup
,# 67. #parseBeacons expiration out of range lower
,# teardown
,ok 221 Expiration out of range
,# setup
,# 68. #parseBeacons no beacons returns null
,# teardown
,ok 222 should be equal
,# setup
,# 69. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
,# teardown
,ok 223 Malformed encrypted beacon key ID
,# setup
,# 70. #parseBeacons addressBookCallback fails decrypt
,# teardown
,ok 224 should be equal
,# setup
,# 71. #parseBeacons addressBookCallback returns no matches
,# teardown
,ok 225 should be equal
ok 226 should be equal
,# setup
,# 72. #parseBeacons addressBookCallback returns spurious match
,# teardown
,ok 227 should be equal
,ok 228 should be equal
,# setup
,# 73. #parseBeacons addressBookCallback returns public key
,# teardown
,ok 229 right number of calls to address book
ok 230 good preAmble
,ok 231 good unencryptedKeyId
,ok 232 good beacon
,# setup
,# 74. validate generatePskIdentityField
,# teardown
,ok 233 decoded buffers match
,# setup
,# 75. validate generatePskSecret
,# teardown
,ok 234 secrets match
,# setup
,# 76. Start and stop ThaliNotificationServer
,# teardown
,ok 235 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
ok 236 ThaliMobile.StopAdvertisingAndListeningshould be called once
,# setup
,# 77. Pass an empty array to ThaliNotificationServer.start
,# teardown
,ok 237 StartUpdateAdvertisingAndListening should not be called
,ok 238 ThaliMobile.StopAdvertisingAndListening should be called once
,ok 239 no error
,ok 240 should be 204
,# setup
,# 78. Pass a string to ThaliNotificationServer.start
,# teardown
,ok 241 StartUpdateAdvertisingAndListening should not be called
,# setup
,# 79. Pass an empty parameter to ThaliNotificationServer.start
,# teardown
,ok 242 StartUpdateAdvertisingAndListening should not be called
,# setup
,# 80. Make an HTTP request to /NotificationBeacons
,# teardown
,ok 243 no error
ok 244 should be 200
,ok 245 should be equal
,ok 246 should be equal
,ok 247 (unnamed assert)
,ok 248 no error
,ok 249 should be 204
,# setup
,# 81. Make an HTTP request to /NotificationBeacons (no keys)
,# teardown
,ok 250 error should be null
,ok 251 should be 204
,# setup
,# 82. Make an HTTP request to /NotificationBeaconsbefore calling start
,# teardown
,ok 252 should be 404
,# setup
,# 83. #testThaliPeerAction - test getters
,# teardown
,ok 253 getPeerIdentifier
,ok 254 getConnectionType
,ok 255 getActionType
,ok 256 getActionState
,# setup
,# 84. #testThaliPeerAction - start and kill
,# teardown
,ok 257 initial state
,ok 258 after start
,ok 259 after kill
,# setup
,# 85. #testThaliPeerAction - double start
,# teardown
,ok 260 should be equal
,# setup
,# 86. #testThaliPeerAction - start after kill
,# teardown
,ok 261 clean kill
,ok 262 should be equal
,# setup
,# 87. #testThaliPeerAction - make sure ids are unique
,# teardown
,ok 263 should not be equal
,# setup
,# 88. Test PeerConnectionInformation basics
,# teardown
,ok 264 getHostAddress works
,ok 265 getPortNumber works
,ok 266 getSuggestedTCPTimeout works
,# setup
,# 89. Test PeerDictionary basic functionality
,# teardown
,ok 267 Entry counter must be 1
,ok 268 Size must be 1
,ok 269 Entry counter must be 2
,ok 270 Size must be 2
,ok 271 Entry2 should not be found
,ok 272 Size must be 1
,ok 273 Size must be 0
,ok 274 entry not found must be thrown
,# setup
,# 90. Test PeerDictionary with multiple entries.
,# teardown
,ok 275 Size must be100
,ok 276 Entries between 20 and MAXSIZE + 20 should exist
,ok 277 WAITING state entry should not be removed
,# setup
,# 91. RESOLVED entries are removed before WAITING state entry.
,# teardown
,ok 278 Entries between 6 and MAXSIZE + 4 should exist
ok 279 Size should be MAXSIZE
,ok 280 Size should be MAXSIZE+6
,# setup
,# 92. WAITING entries are removed before CONTROLLED_BY_POOL state entry.
,# teardown
,ok 281 WAITING state entry should not be removed
,ok 282 Waiting entries between 6 and MAXSIZE + 4 should exist
,ok 283 Size should be MAXSIZE
,ok 284 entryCounter should be MAXSIZE+6
,# setup
,# 93. When CONTROLLED_BY_POOL entry is removed and kill is called.
,# teardown
,ok 285 Kill should be called once
,ok 286 Size should be 100
,# setup
,# 94. #ThaliPeerPoolInterface - bad enqueues
,# teardown
,ok 287 null arg
,ok 288 wrong arg type
,ok 289 wrong state
,# setup
,# 95. #ThaliPeerPoolInterface - do not allow same object type
,# teardown
,ok 290 good enqueue
,ok 291 should be equal
,# setup
,# 96. #ThaliPeerPoolInterface - make sure we catch kill and dequeue
,# teardown
,ok 292 good enqueue
,ok 293 2nd good enqueue
,ok 294 we are in the pool
,ok 295 We are out of the pool
,ok 296 Action was killed
,ok 297 The original kill was called too
,ok 298 second item is still in queue
,# setup
,# 97. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
,# teardown
,ok 299 good enqueue
,ok 300 first kill
,ok 301 second NOOP kill
,# setup
,# 98. compareBufferArrays
,# teardown
,ok 302 should throw
,ok 303 should throw
,ok 304 (unnamed assert)
,ok 305 (unnamed assert)
,ok 306 (unnamed assert)
,ok 307 (unnamed assert)
,ok 308 (unnamed assert)
,# setup
,# 99. Call start twice and get error
,# teardown
,ok 309 should throw
,# setup
,# 100. Start and make sure it runs
,# teardown
,# setup
,# 101. Make sure getTimeWhenRun is right after start
,# teardown
,ok 310 (unnamed assert)
,# setup
,# 102. Make sure getTimeWhenRun is -1 after function is called
,# teardown
,ok 311 should be equal
,# setup
,# 103. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running
,# teardown
,ok 312 should be equal
,ok 313 should be equal
,ok 314 should throw
,# setup
,# 104. Test TransientState
,# teardown
,ok 315 should throw
,ok 316 should throw
,ok 317 should be equal
,ok 318 should be equal
,ok 319 should be equal
,ok 320 should be equal
,ok 321 (unnamed assert)
,ok 322 (unnamed assert)
,# setup
,# 105. No peers and empty database
,# teardown
,ok 323 verify failed
,ok 324 constructor called once
,ok 325 constructor called with right args
,ok 326 match start arg
,ok 327 start called once
,ok 328 stop called once
,ok 329 stop after start
,# setup
,# 106. One peer and empty DB
,# teardown
,DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
,ok 330 verify failed
,ok 331 constructor called once
,ok 332 constructor called with right args
,ok 333 match start arg
,ok 334 start called once
,ok 335 stop called once
,ok 336 stop after start
,# setup
,# 107. One peer with _Local set behind current seq
,# teardown
,DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
,ok 337 verify failed
,ok 338 constructor called once
,ok 339 constructor called with right args
,ok 340 match start arg
,ok 341 start called once
,ok 342 stop called once
,ok 343 stop after start
,# setup
,# 108. One peer with _Local set equal to current seq
,# teardown
,DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
,ok 344 verify failed
,ok 345 constructor called once
,ok 346 constructor called with right args
,ok 347 match start arg
,ok 348 start called once
,ok 349 stop called once
,ok 350 stop after start
,# setup
,# 109. One peer with _Local set ahead of current seq (and no this should not happen)
,# teardown
,DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
,ok 351 verify failed
,ok 352 constructor called once
,ok 353 constructor called with right args
,ok 354 match start arg
,ok 355 start called once
,ok 356 stop called once
,ok 357 stop after start
,# setup
,# 110. Three peers, one not in DB, one behind and one ahead
,# teardown
,DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 358 verify failed
,ok 359 constructor called once
,ok 360 constructor called with right args
,ok 361 match start arg
,ok 362 start called once
,ok 363 stop called once
,ok 364 stop after start
,# setup
,# 111. More than maximum peers, make sure we only send maximum allowed
,# teardown
,DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
,ok 365 verify failed
,ok 366 constructor called once
,ok 367 constructor called with right args
,ok 368 match start arg
,ok 369 start called once
,ok 370 stop called once
,ok 371 stop after start
,# setup
,# 112. two peers with empty DB, update the doc
,# teardown
,DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
,DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
,ok 372 verify failed
,ok 373 constructor called once
,ok 374 constructor called with right args
,ok 375 last start before stop
,ok 376 empty first start
,ok 377 full second start
,ok 378 only 2 timers
,# setup
,# 113. add doc and make sure tokens refresh when they expire
,# teardown
,DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
,DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
,DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
,ok 379 verify failed
,ok 380 constructor called once
,ok 381 constructor called with right args
,ok 382 start before stop
,ok 383 We got at least 3 calls to start
,ok 384 at least 3
,ok 385 default 1
,ok 386 1 run
,ok 387 default 2
,ok 388 2 run
,ok 389 default 3
,# setup
,# 114. start and stop and start and stop
,# teardown
,ok 390 start out null
,DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
,ok 391 back to null
,DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 392 still null
,ok 393 verify failed
,ok 394 constructor called once
,ok 395 constructor called with right args
,ok 396 first start before first stop
,ok 397 first stop before second start
,ok 398 second start before second stop
,# setup
,# 115. two identical starts in a row
,# teardown
,DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
,ok 399 verify failed
,ok 400 constructor called once
,ok 401 constructor called with right args
,ok 402 (unnamed assert)
,# setup
,# 116. two different starts in a row
,# teardown
,DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
,ok 403 verify failed
ok 404 constructor called once
,ok 405 constructor called with right args
,ok 406 (unnamed assert)
,ok 407 (unnamed assert)
,# setup
,# 117. two stops and a start and two stops
,# teardown
,DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
,ok 408 verify failed
,ok 409 constructor called once
,ok 410 constructor called with right args
,ok 411 start before stop
,# setup
,# 118. we properly enqueue requests so no then needed
,# teardown
,DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
,ok 412 verify failed
,ok 413 constructor called once
,ok 414 constructor called with right args
,ok 415 start before stop
,# setup
,# 119. test calculateSeqPointKeyId
,# teardown
,ok 416 should be equal
,ok 417 should be equal
,# setup
,# 120. can create servers manager
,# teardown
,ok 418 serversManager must not be null
,ok 419 serversManager must be an object
,# setup
,# 121. calling stop without start causes error
,# teardown
,ok 420 We need to call start first
,# setup
,# 122. can start/stop servers manager
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 64404
,ok 421 port must be in range
,# setup
,# 123. starting twice resolves with listening port
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 64405
,ok 422 second start should return same port
,# setup
,# 124. terminateIncomingConnection will terminate a connection
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 64407
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,ok 423 we should be connected
,DEBUG createNativeListener: incoming socket close
,ok 424 now we are disconnected
,# setup
,# 125. terminate an Outgoing connection will terminate the server
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 64409
,# setup
,# 126. terminate an Outgoing connection with wrong arguments is not harmful
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 64410
,# setup
,# 127. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted
,ok 425 should be in started state
,# teardown
,ok 426 peer identifier should match
,ok 427 host address should match
,ok 428 port should match
,ok 429 host address should be null
,ok 430 port should should be null
,# setup
,ok 431 should not be in started state
,# 128. #startUpdateAdvertisingAndListening should use different USN after every invocation
,ok 432 should be in started state
,# teardown
,ok 433 USN should have changed from the first one
,ok 434 when receiving the second byebye, the first USN should be already set
,# setup
,ok 435 should not be in started state
,# 129. messages with invalid location or USN should be ignored
,ok 436 should be in started state
,# teardown
,WARN thaliWifiInfrastructure: Failed to parse a valid port number from location: http://foo.bar:90000
,ok 437 should not have emitted with invalid port
,WARN thaliWifiInfrastructure: Received an invalid USN value: 
,ok 438 should not have emitted with invalid USN
,# setup
,ok 439 should not be in started state
,# 130. verify that Thali-specific messages are filtered correctly
,ok 440 should be in started state
,# teardown
,ok 441 irrelevant messages should be ignored
,ok 442 relevant messages should not be ignored
,ok 443 messages from this device should be ignored
,# setup
,ok 444 should not be in started state
,# 131. #startListeningForAdvertisements should fail if start not called
,ok 445 should be in started state
,# teardown
,ok 446 specific error should be returned
,# setup
,ok 447 should not be in started state
,# 132. #startUpdateAdvertisingAndListening should fail if start not called
,ok 448 should be in started state
,# teardown
,ok 449 specific error should be returned
,# setup
,ok 450 should not be in started state
,# 133. #start should fail if called twice in a row
,ok 451 should be in started state
,# teardown
,ok 452 specific error should be received
,# setup
,ok 453 should not be in started state
,# 134. should not be started after stop is called
,ok 454 should be in started state
,# teardown
,ok 455 should not be started
,ok 456 should not be listening
,ok 457 should not target listening
,ok 458 should not be advertising
,ok 459 should not target advertising
,# setup
,ok 460 should not be in started state
,# 135. #startUpdateAdvertisingAndListening should fail invalid router has been passed
,ok 461 should be in started state
,# teardown
,ERROR thaliWifiInfrastructure: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
,ok 462 specific error should be received
,# setup
,ok 463 should not be in started state
,# 136. #startUpdateAdvertisingAndListening should fail if router server starting fails
,ok 464 should be in started state
,# teardown
,ERROR thaliWifiInfrastructure: Router server emitted an error: Error: listen EADDRINUSE
,ok 465 specific error expected
,# setup
,ok 466 should not be in started state
,# 137. #startUpdateAdvertisingAndListening should start hosting given router object
,ok 467 should be in started state
,# teardown
,ok 468 server should respond with code 200
,# setup
,ok 469 should not be in started state
,# 138. #stop can be called multiple times in a row
,ok 470 should be in started state
,# teardown
,ok 471 should be in stopped state
,ok 472 should still be in stopped state
,# setup
,ok 473 should not be in started state
,# 139. #startListeningForAdvertisements can be called multiple times in a row
,ok 474 should be in started state
,# teardown
,ok 475 should be in listening state
,ok 476 should still be in listening state
,# setup
,ok 477 should not be in started state
,# 140. #stopListeningForAdvertisements can be called multiple times in a row
,ok 478 should be in started state
,# teardown
,ok 479 should not be in listening state
,ok 480 should still not be in listening state
,# setup
,ok 481 should not be in started state
,# 141. #stopAdvertisingAndListening can be called multiple times in a row
,ok 482 should be in started state
,# teardown
,ok 483 should not be in advertising state
,ok 484 should still not be in advertising state
,# setup
,ok 485 should not be in started state
,# 142. functions are run from a queue in the right order
,ok 486 should be in started state
,# teardown
,ok 487 call order must match
,# setup
,ok 488 should not be in started state
,# 143. #ThaliPeerPoolDefault - single action
,# teardown
,ok 489 is an agent
,ok 490 enqueue is fine
,ok 491 Everything should be off the queue
,# setup
,# 144. #ThaliPeerPoolDefault - multiple actions
,# teardown
,ok 492 is an agent
,ok 493 first enqueue is fine
,ok 494 is an agent
,ok 495 second enqueue is fine
,ok 496 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
,ok 497 Queue is empty
,Tests Complete
,Total: 0	Passed: 0	Failed: 0
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
