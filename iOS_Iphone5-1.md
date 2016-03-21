#### Test 625481240f1d9b8_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/625481240f1d9b8/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/5FA4B5CC-FA70-4270-829E-824CCE6AF067/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/5FA4B5CC-FA70-4270-829E-824CCE6AF067/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/625481240f1d9b8/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/625481240f1d9b8/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/447A7C4D-16DB-4E3D-965A-A8C3800B8941/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54439"
,(lldb)     command script import "/tmp/5FA4B5CC-FA70-4270-829E-824CCE6AF067/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-21 16:43:17.888 ThaliTest[1469:3444716] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/171E10A9-13AA-4B43-94D5-55F7424443E2/Library/Cookies/Cookies.binarycookies
,2016-03-21 16:43:18.467 ThaliTest[1469:3444716] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-21 16:43:18.469 ThaliTest[1469:3444716] Multi-tasking -> Device: YES, App: YES
,2016-03-21 16:43:18.487 ThaliTest[1469:3444716] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-21 16:43:20.779 ThaliTest[1469:3444716] Using UIWebView
,2016-03-21 16:43:20.784 ThaliTest[1469:3444716] [CDVTimer][handleopenurl] 0.454009ms
,2016-03-21 16:43:20.790 ThaliTest[1469:3444716] [CDVTimer][intentandnavigationfilter] 5.208015ms
2016-03-21 16:43:20.790 ThaliTest[1469:3444716] [CDVTimer][gesturehandler] 0.257015ms
2016-03-21 16:43:20.791 ThaliTest[1469:3444716] [CDVTimer][TotalPluginStartup] 7.001996ms
,2016-03-21 16:43:29.945 ThaliTest[1469:3444716] Resetting plugins due to page load.
,2016-03-21 16:43:33.747 ThaliTest[1469:3444716] Finished load of: file:///var/mobile/Containers/Bundle/Application/447A7C4D-16DB-4E3D-965A-A8C3800B8941/ThaliTest.app/www/index.html
,2016-03-21 16:43:33.949 ThaliTest[1469:3444716] JXcore Cordova plugin initializing
,2016-03-21 16:43:33.951 ThaliTest[1469:3444916] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-21 16:43:50.598 ThaliTest[1469:3444916] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-21 16:43:50.598 ThaliTest[1469:3444916] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-21 16:43:50.599 ThaliTest[1469:3,444916] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-21 16:43:50.602 ThaliTest[1469:3444916] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/447A7C4D-16DB-4E3D-965A-A8C3800B8941/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/447A7C4D-16DB-4E3D-965A-A8C3800B8941/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/447A7C4D-16DB-4E3D-965A-A8C3800B8941/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/447A7C4D-16DB-4E3D-965A-A8C3800B8941/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/447A7C4D-16DB-4E3D-965A-A8C3800B8941/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/447A7C4D-16DB-4E3D-965A-A8C3800B8941/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/447A7C4D-16DB-4E3D-965A-A8C3800B8941/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/447A7C4D-16DB-4E3D-965A-A8C3800B8941/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/447A7C4D-16DB-4E3D-965A-A8C3800B8941/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/447A7C4D-16DB-4E3D-965A-A8C3800B8941/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/447A7C4D-16DB-4E3D-965A-A8C3800B8941/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/447A7C4D-16DB-4E3D-965A-A8C3800B8941/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/447A7C4D-16DB-4E3D-965A-A8C3800B8941/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/447A7C4D-16DB-4E3D-965A-A8C3800B8941/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/447A7C4D-16DB-4E3D-965A-A8C3800B8941/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/447A7C4D-16DB-4E3D-965A-A8C3800B8941/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/447A7C4D-16DB-4E3D-965A-A8C3800B8941/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/447A7C4D-16DB-4E3D-965A-A8C3800B8941/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/447A7C4D-16DB-4E3D-965A-A8C3800B8941/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/447A7C4D-16DB-4E3D-965A-A8C3800B8941/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-21 16:44:04.196 ThaliTest[1469:3444716] THREAD WARNING: ['JXcore'] took '12895.928223' ms. Plugin should use a background thread.
,2016-03-21 16:44:04.198 ThaliTest[1469:3444866] void SendDelegateMessage(NSInvocation *): delegate (webView:decidePolicyForNavigationAction:request:frame:decisionListener:) failed to return after waiting 10 seconds. main run loop mode: kCFRunLoopDefaultMod,e
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50469
,ok 1 Should throw
,# setup
,# 2. emits incomingConnectionState
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50472
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
,DEBUG createNativeListener: listening 50475
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
,DEBUG createNativeListener: listening 50479
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
,DEBUG createNativeListener: listening 50484
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
,DEBUG createNativeListener: listening 50489
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
,DEBUG createNativeListener: listening 50493
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
,DEBUG createNativeListener: listening 50497
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
,DEBUG createNativeListener: listening 50501
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
,DEBUG createNativeListener: listening 50553
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
,DEBUG createNativeListener: listening 50557
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
,DEBUG createNativeListener: listening 50569
,2016-03-21 16:46:12.255 ThaliTest[1469:3444916] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 16:46:12.256 ThaliTest[1469:3444916] jxcore: stopListeningForAdvertisements: success
,ok 82 error should be null
,ok 83 error should be null
,2016-03-21 16:46:12.260 ThaliTest[1469:3444916] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-21 16:46:12.262 ThaliTest[1469:3444916] jxcore: stopListeningForAdvertisements: success
,ok 84 error should be null
,ok 85 error should be null
,# setup
,2016-03-21 16:46:12.377 ThaliTest[1469:3444916] jxcore: stopAdvertisingAndListening
2016-03-21 16:46:12.377 ThaliTest[1469:3444916] THEMultipeerManager stopping peer
2016-03-21 16:46:12.378 ThaliTest[1469:3444916] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-21 16:46:12.378 ThaliTest[1469:3444916] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-21 16:46:12.379 ThaliTest[1469,:3444916] jxcore: stopListeningForAdvertisements: success
,ok 86 error should be null
,ok 87 error should be null
,# 24. should be able to call #startListeningForAdvertisements many times
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50571
,2016-03-21 16:46:12.714 ThaliTest[1469:3444916] jxcore: startListeningForAdvertisements
,2016-03-21 16:46:12.716 ThaliTest[1469:3444916] multipeer manager: start client restart timer: 0x1658e1c0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-21 16:46:12.717 Th,aliTest[1469:3444916] jxcore: startListeningForAdvertisements: success
,ok 88 error should be null
,ok 89 error should be null
,2016-03-21 16:46:12.763 ThaliTest[1469:3444916] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-21 16:46:12.764 ThaliTest[1469:3444916] jxcore: startListeningForAdvertisements: success
,ok 90 error should be null
,ok 91 error should be null
,# setup
,2016-03-21 16:46:12.990 ThaliTest[1469:3444916] jxcore: stopAdvertisingAndListening
2016-03-21 16:46:12.991 ThaliTest[1469:3444916] THEMultipeerManager stopping peer
2016-03-21 16:46:12.991 ThaliTest[1469:3444916] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-21 16:46:12.991 ThaliTest[1469:3444916] jxcore: stopListeningForAdvertisements
2016-03-21 16:46:12.991 ThaliTest[1469:3444916] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-21 16:46:12.992 ThaliTest[1469:3444916] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 92 error should be null
,ok 93 error should be null
,# 25. should be able to call #startUpdateAdvertisingAndListening many times
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50573
,2016-03-21 16:46:13.517 ThaliTest[1469:3444916] jxcore: startUpdateAdvertisingAndListening
2016-03-21 16:46:13.517 ThaliTest[1469:3444916] server: starting 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:1
2016-03-21 16:46:13.518 ThaliTest[1469:3444916] multipeer m,anager: start client restart timer: 0x1658e1c0
2016-03-21 16:46:13.518 ThaliTest[1469:3444916] THEMultipeerManager initialized peer 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:1
2016-03-21 16:46:13.519 ThaliTest[1469:3444916] jxcore: startUpdateAdvertisingAndLi,stening: success
,ok 94 error should be null
,ok 95 error should be null
,2016-03-21 16:46:13.538 ThaliTest[1469:3444916] jxcore: startUpdateAdvertisingAndListening
2016-03-21 16:46:13.538 ThaliTest[1469:3444916] THEMultipeerManager stopping peer
2016-03-21 16:46:13.539 ThaliTest[1469:3444916] multipeer manager: stop client ti,mer
2016-03-21 16:46:13.539 ThaliTest[1469:3444916] server: starting 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:2
2016-03-21 16:46:13.540 ThaliTest[1469:3444916] multipeer manager: start client restart timer: 0x1658e1c0
2016-03-21 16:46:13.540 ThaliTest[1469:,3444916] THEMultipeerManager initialized peer 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:2
2016-03-21 16:46:13.541 ThaliTest[1469:3444916] jxcore: startUpdateAdvertisingAndListening: success
,ok 96 error should be null
,ok 97 error should be null
,# setup
,2016-03-21 16:46:13.738 ThaliTest[1469:3444916] jxcore: stopAdvertisingAndListening
2016-03-21 16:46:13.738 ThaliTest[1469:3444916] THEMultipeerManager stopping peer
2016-03-21 16:46:13.738 ThaliTest[1469:3444916] multipeer manager: stop client timer
20,16-03-21 16:46:13.738 ThaliTest[1469:3444916] jxcore: stopAdvertisingAndListening: success
2016-03-21 16:46:13.739 ThaliTest[1469:3444916] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 16:46:13.742 ThaliTest[1469:3444916] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 98 error should be null
ok 99 error should be null
,# 26. should be able to call #stopAdvertisingAndListening many times
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50578
,2016-03-21 16:46:14.560 ThaliTest[1469:3444916] jxcore: stopAdvertisingAndListening
2016-03-21 16:46:14.560 ThaliTest[1469:3444916] THEMultipeerManager stopping peer
2016-03-21 16:46:14.560 ThaliTest[1469:3444916] jxcore: stopAdvertisingAndListening: suc,cess
,ok 100 error should be null
ok 101 error should be null
,2016-03-21 16:46:14.564 ThaliTest[1469:3444916] jxcore: stopAdvertisingAndListening
2016-03-21 16:46:14.564 ThaliTest[1469:3444916] THEMultipeerManager stopping peer
2016-03-21 16:46:14.565 ThaliTest[1469:3444916] jxcore: stopAdvertisingAndListening: success
,ok 102 error should be null
ok 103 error should be null
,# setup
,2016-03-21 16:46:14.741 ThaliTest[1469:3444916] jxcore: stopAdvertisingAndListening
2016-03-21 16:46:14.741 ThaliTest[1469:3444916] THEMultipeerManager stopping peer
2016-03-21 16:46:14.741 ThaliTest[1469:3444916] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-21 16:46:14.741 ThaliTest[1469:3444916] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-21 16:46:14.742 ThaliTest[1469,:3444916] jxcore: stopListeningForAdvertisements: success
,ok 104 error should be null
,ok 105 error should be null
,# 27. #start should fail if called twice in a row
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50580
,ok 106 first call should succeed
,ok 107 first call should succeed
,ok 108 specific error should be returned
,# setup
,2016-03-21 16:46:15.726 ThaliTest[1469:3444916] jxcore: stopAdvertisingAndListening
2016-03-21 16:46:15.727 ThaliTest[1469:3444916] THEMultipeerManager stopping peer
2016-03-21 16:46:15.727 ThaliTest[1469:3444916] jxcore: stopAdvertisingAndListening: success
2016-03-21 16:46:15.727 ThaliTest[1469:3444916] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-21 16:46:15.728 ThaliTest[1469,:3444916] jxcore: stopListeningForAdvertisements: success
,ok 109 error should be null
,ok 110 error should be null
,# 28. does not emit duplicate discoveryAdvertisingStateUpdate
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50582
,2016-03-21 16:46:16.159 ThaliTest[1469:3444916] jxcore: startListeningForAdvertisements
2016-03-21 16:46:16.160 ThaliTest[1469:3444916] multipeer manager: start client restart timer: 0x1658e1c0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-21 16:46:16.161 ThaliTest[1469:3444916] jxcore: startListeningForAdvertisements: success
,2016-03-21 16:46:16.180 ThaliTest[1469:3444916] jxcore: startUpdateAdvertisingAndListening
2016-03-21 16:46:16.181 ThaliTest[1469:3444916] server: starting 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:3
2016-03-21 16:46:16.181 ThaliTest[1469:3444916] THEMultipee,rManager initialized peer 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:3
2016-03-21 16:46:16.181 ThaliTest[1469:3444916] jxcore: startUpdateAdvertisingAndListening: success
,ok 111 called only once
ok 112 discovery state matches
ok 113 advertising state matches
,# setup
,2016-03-21 16:46:16.323 ThaliTest[1469:3444916] jxcore: stopAdvertisingAndListening
2016-03-21 16:46:16.324 ThaliTest[1469:3444916] THEMultipeerManager stopping peer
2016-03-21 16:46:16.324 ThaliTest[1469:3444916] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-21 16:46:16.324 ThaliTest[1469:3444916] jxcore: stopListeningForAdvertisements
2016-03-21 16:46:16.324 ThaliTest[1469:3444916] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-21 16:46:16.325 ThaliTest[1469:3444916] jxcore: stopListeningForAdvertisements: success
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
,2016-03-21 16:46:21.490 ThaliTest[1469:3444916] jxcore: startListeningForAdvertisements
2016-03-21 16:46:21.490 ThaliTest[1469:3444916] multipeer manager: start client restart timer: 0x1658e1c0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-21 16:46:21.492 ThaliTest[1469:3444916] jxcore: startListeningForAdvertisements: success
,ok 129 Can call startListeningForAdvertisements without error
2016-03-21 16:46:21.493 ThaliTest[1469:3444916] jxcore: stopListeningForAdvertisements
,2016-03-21 16:46:21.494 ThaliTest[1469:3444916] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 16:46:21.496 ThaliTest[1469:3444916] jxcore: stopListeningForAdvertisements: success
,ok 130 Can call stopListeningForAdvertisements without error
# setup
,2016-03-21 16:46:21.861 ThaliTest[1469:3444916] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-21 16:46:21.863 ThaliTest[1469:3444916] jxcore: stopListeningForAdvertisements: success
,ok 131 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-21 16:46:21.864 ThaliTest[1469:3444916] jxcore: stopAdvertisingAndListening
2016-03-21 16:46:21.865 ThaliTest[1469:3444916] THEMultipeerManager stopping peer
2016-03-21 16:46:21.865 ThaliTest[1469:3444916] jxcore: stopAdvertisingAndListening: success
ok 132 Should be able to call stopAdvertisingAndListening in teardown
,# 33. Calling startListeningForAdvertisements twice is NOT an error
,# teardown
,2016-03-21 16:46:22.396 ThaliTest[1469:3444916] jxcore: startListeningForAdvertisements
2016-03-21 16:46:22.396 ThaliTest[1469:3444916] multipeer manager: start client restart timer: 0x1658e1c0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-21 16:46:22.397 ThaliTest[1469:3444916] jxcore: startListeningForAdvertisements: success
,ok 133 Can call startListeningForAdvertisements without error
2016-03-21 16:46:22.399 ThaliTest[1469:3444916] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-21 16:46:22.400 ThaliTest[1469:3444916] jxcore: startListeningForAdvertisements: success
,ok 134 Can call startListeningForAdvertisements twice without error
# setup
,2016-03-21 16:46:23.868 ThaliTest[1469:3444916] jxcore: stopListeningForAdvertisements
2016-03-21 16:46:23.869 ThaliTest[1469:3444916] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 16:46:23.870 ThaliTest[1469:3444916] jxcore: stopListeningForAdvertisements: success
,ok 135 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-21 16:46:23.871 ThaliTest[1469:3444916] jxcore: stopAdvertisingAndListening
2016-03-21 16:46:23.873 ThaliTest[1469:3444916] THEMultipeerManager stopping peer
2016-03-21 16:46:23.873 ThaliTest[1469:3444916] jxcore: stopAdvertisingAndListening: suc,cess
ok 136 Should be able to call stopAdvertisingAndListening in teardown
,# 34. Can call start/stopUpdateAdvertisingAndListening
,# teardown
,2016-03-21 16:46:24.577 ThaliTest[1469:3444916] jxcore: startUpdateAdvertisingAndListening
2016-03-21 16:46:24.578 ThaliTest[1469:3444916] server: starting 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:4
2016-03-21 16:46:24.578 ThaliTest[1469:3444916] multipeer manager: start client restart timer: 0x1658e1c0
2016-03-21 16:46:24.578 ThaliTest[1469:3444916] THEMultipeerManager initialized peer 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:4
2016-03-21 16:46:24.579 ThaliTest[1469:3444916] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 137 Can call startUpdateAdvertisingAndListening without error
,2016-03-21 16:46:24.580 ThaliTest[1469:3444916] jxcore: stopAdvertisingAndListening
2016-03-21 16:46:24.580 ThaliTest[1469:3444916] THEMultipeerManager stopping peer
2016-03-21 16:46:24.581 ThaliTest[1469:3444916] multipeer manager: stop client timer
20,16-03-21 16:46:24.581 ThaliTest[1469:3444916] jxcore: stopAdvertisingAndListening: success
,ok 138 Can call stopAdvertisingAndListening without error
,# setup
,2016-03-21 16:46:24.962 ThaliTest[1469:3444916] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-21 16:46:24.963 ThaliTest[1469:3444916] jxcore: stopListeningForAdvertisements: success
,ok 139 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-21 16:46:24.965 ThaliTest[1469:3444916] jxcore: stopAdvertisingAndListening
2016-03-21 16:46:24.965 ThaliTest[1469:3444916] THEMultipeerManager stopping peer
2016-03-21 16:46:24.965 ThaliTest[1469:3444916] jxcore: stopAdvertisingAndListening: success
,ok 140 Should be able to call stopAdvertisingAndListening in teardown
,# 35. Calling startUpdateAdvertisingAndListening twice is NOT an error
,# teardown
,2016-03-21 16:46:25.455 ThaliTest[1469:3444916] jxcore: startUpdateAdvertisingAndListening
2016-03-21 16:46:25.455 ThaliTest[1469:3444916] server: starting 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:5
2016-03-21 16:46:25.455 ThaliTest[1469:3444916] multipeer m,anager: start client restart timer: 0x1658e1c0
2016-03-21 16:46:25.456 ThaliTest[1469:3444916] THEMultipeerManager initialized peer 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:5
2016-03-21 16:46:25.456 ThaliTest[1469:3444916] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 141 Can call startUpdateAdvertisingAndListening without error
,2016-03-21 16:46:25.457 ThaliTest[1469:3444916] jxcore: startUpdateAdvertisingAndListening
2016-03-21 16:46:25.457 ThaliTest[1469:3444916] THEMultipeerManager stopping peer
2016-03-21 16:46:25.458 ThaliTest[1469:3444916] multipeer manager: stop client ti,mer
2016-03-21 16:46:25.458 ThaliTest[1469:3444916] server: starting 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:6
,2016-03-21 16:46:25.459 ThaliTest[1469:3444916] multipeer manager: start client restart timer: 0x1658e1c0
2016-03-21 16:46:25.459 ThaliTest[1469:3444916] THEMultipeerManager initialized peer 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:6
,2016-03-21 16:46:25.459 ThaliTest[1469:3444916] jxcore: startUpdateAdvertisingAndListening: success
ok 142 Can call startUpdateAdvertisingAndListening twice without error
# setup
,2016-03-21 16:46:25.632 ThaliTest[1469:3444916] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-21 16:46:25.633 ThaliTest[1469:3444916] jxcore: stopListeningForAdvertisements: success
,ok 143 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-21 16:46:25.635 ThaliTest[1469:3444916] jxcore: stopAdvertisingAndListening
2016-03-21 16:46:25.635 ThaliTest[1469:3444916] THEMultipeerManager stopping peer
2016-03-21 16:46:25.635 ThaliTest[1469:3444916] multipeer manager: stop client timer
2016-03-21 16:46:25.636 ThaliTest[1469:3444916] jxcore: stopAdvertisingAndListening: success
ok 144 Should be able to call stopAdvertisingAndListening in teardown
,# 36. peerAvailabilityChange is called
,# teardown
,2016-03-21 16:46:26.409 ThaliTest[1469:3444916] jxcore: startUpdateAdvertisingAndListening
2016-03-21 16:46:26.409 ThaliTest[1469:3444916] server: starting 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:7
2016-03-21 16:46:26.410 ThaliTest[1469:3444916] multipeer manager: start client restart timer: 0x1658e1c0
2016-03-21 16:46:26.410 ThaliTest[1469:3444916] THEMultipeerManager initialized peer 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:7
2016-03-21 16:46:26.410 ThaliTest[1469:3444916] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 145 Can call startUpdateAdvertisingAndListeningwithout error
,2016-03-21 16:46:26.412 ThaliTest[1469:3444916] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
,2016-03-21 16:46:26.413 ThaliTest[1469:3444916] jxcore: startListeningForAdvertisements: success
,ok 146 Can call startListeningForAdvertisements without error
,2016-03-21 16:46:27.327 ThaliTest[1469:3444716] client: found new peer: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:7
ok 147 peers must be an array
,ok 148 peers must not be zero-length
ok 149 peer must have peerIdentifier
,ok 150 peerIdentifier must be a string
,ok 151 peer must have peerAvailable
,ok 152 peer must have pleaseConnect
,# setup
,2016-03-21 16:46:29.757 ThaliTest[1469:3444916] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-21 16:46:29.758 ThaliTest[1469:3444916] jxcore: stopListeningForAdvertisements: success
,ok 153 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-21 16:46:29.759 ThaliTest[1469:3444916] jxcore: stopAdvertisingAndListening
,2016-03-21 16:46:29.759 ThaliTest[1469:3444916] THEMultipeerManager stopping peer
2016-03-21 16:46:29.760 ThaliTest[1469:3444916] multipeer manager: stop client timer
2016-03-21 16:46:29.760 ThaliTest[1469:3444916] jxcore: stopAdvertisingAndListening: su,ccess
ok 154 Should be able to call stopAdvertisingAndListening in teardown
,# 37. Can connect to a remote peer
,# teardown
,2016-03-21 16:46:31.286 ThaliTest[1469:3444916] jxcore: startUpdateAdvertisingAndListening
2016-03-21 16:46:31.287 ThaliTest[1469:3444916] server: starting 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:8
2016-03-21 16:46:31.287 ThaliTest[1469:3444916] multipeer m,anager: start client restart timer: 0x1658e1c0
2016-03-21 16:46:31.287 ThaliTest[1469:3444916] THEMultipeerManager initialized peer 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:8
2016-03-21 16:46:31.288 ThaliTest[1469:3444916] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 155 Can call startUpdateAdvertisingAndListening without error
,2016-03-21 16:46:31.289 ThaliTest[1469:3444916] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
,2016-03-21 16:46:31.291 ThaliTest[1469:3444916] jxcore: startListeningForAdvertisements: success
ok 156 Can call startListeningForAdvertisements without error
,2016-03-21 16:46:33.374 ThaliTest[1469:3444716] client: found new peer: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:7
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:7","pleaseConnect":0}]
,2016-03-21 16:46:33.377 ThaliTest[1469:3444916] jxcore: connect 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:7
2016-03-21 16:46:33.377 ThaliTest[1469:3444916] client: server will connect
2016-03-21 16:46:33.377 ThaliTest[1469:3444916] client session: reverseConn,ect
2016-03-21 16:46:33.378 ThaliTest[1469:3444916] client session: stateChange:0->1 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:7
,2016-03-21 16:46:33.678 ThaliTest[1469:3444716] multipeer session: reset timer
2016-03-21 16:46:33.678 ThaliTest[1469:3444716] server: rejecting invitation from 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1 due to previous generation (2EB617D0-DF93-4CC9-AB67-E3573,BAE44B5:8 != 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:7)
,2016-03-21 16:46:33.703 ThaliTest[1469:3445278] client session: not connected 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:7
,2016-03-21 16:46:33.703 ThaliTest[1469:3445278] client session: onLinkFailure: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1
2016-03-21 16:46:33.704 ThaliTest[1469:3445278] client session: disconnect
2016-03-21 16:46:33.705 ThaliTest[1469:3445278] client session: stateChange:1->0 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:7
2016-03-21 16:46:33.705 ThaliTest[1469:3445278] client session: no connect callback (server initiated)
,2016-03-21 16:46:37.279 ThaliTest[1469:3444716] multipeer session: reset timer
2016-03-21 16:46:37.279 ThaliTest[1469:3444716] server: disconnecting to refresh session (75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1)
2016-03-21 16:46:37.279 ThaliTest[1469:3444716], server: rejecting invitation from 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1 due to previous generation (2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:8 != 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:7)
,2016-03-21 16:46:40.953 ThaliTest[1469:3444716] multipeer session: reset timer
2016-03-21 16:46:40.953 ThaliTest[1469:3444716] server: disconnecting to refresh session (75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1)
2016-03-21 16:46:40.953 ThaliTest[1469:3444716] server: rejecting invitation from 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1 due to previous generation (2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:8 != 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:7)
,2016-03-21 16:46:43.379 ThaliTest[1469:3444716] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-21 16:46:44.569 ThaliTest[1469:3444716] multipeer session: reset timer
2016-03-21 16:46:44.570 ThaliTest[1469:3444716] server: disconnecting to refresh session (75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1)
2016-03-21 16:46:44.570 ThaliTest[1469:3444716], server: rejecting invitation from 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1 due to previous generation (2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:8 != 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:7)
,2016-03-21 16:46:46.391 ThaliTest[1469:3444916] jxcore: connect 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:7
2016-03-21 16:46:46.391 ThaliTest[1469:3444916] client: server will connect
2016-03-21 16:46:46.392 ThaliTest[1469:3444916] client session: reverseConnect
2016-03-21 16:46:46.392 ThaliTest[1469:3444916] client session: stateChange:0->1 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:7
,2016-03-21 16:46:47.233 ThaliTest[1469:3445293] client session: not connected 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:7
,2016-03-21 16:46:47.234 ThaliTest[1469:3445293] client session: onLinkFailure: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1
2016-03-21 16:46:47.234 ThaliTest[1469:3445293] client session: disconnect
2016-03-21 16:46:47.235 ThaliTest[1469:3445293] client session: stateChange:1->0 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:7
2016-03-21 16:46:47.235 ThaliTest[1469:3445293] client session: no connect callback (server initiated)
,2016-03-21 16:46:47.648 ThaliTest[1469:3444716] multipeer session: reset timer
2016-03-21 16:46:47.648 ThaliTest[1469:3444716] server: disconnecting to refresh session (75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1)
2016-03-21 16:46:47.648 ThaliTest[1469:3444716], server: rejecting invitation from 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1 due to previous generation (2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:8 != 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:7)
,2016-03-21 16:46:50.905 ThaliTest[1469:3444716] multipeer session: reset timer
2016-03-21 16:46:50.905 ThaliTest[1469:3444716] server: disconnecting to refresh session (75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1)
2016-03-21 16:46:50.905 ThaliTest[1469:3444716], server: rejecting invitation from 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1 due to previous generation (2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:8 != 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:7)
,2016-03-21 16:46:51.288 ThaliTest[1469:3444716] multipeer manager: restart client
,2016-03-21 16:46:51.302 ThaliTest[1469:3444716] client: found updated peer: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:8","pleaseConnect":0}]
,2016-03-21 16:46:54.008 ThaliTest[1469:3444716] multipeer session: reset timer
2016-03-21 16:46:54.008 ThaliTest[1469:3444716] server: disconnecting to refresh session (75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1)
2016-03-21 16:46:54.008 ThaliTest[1469:3444716], server: rejecting invitation from 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1 due to previous generation (2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:8 != 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:7)
,2016-03-21 16:46:56.393 ThaliTest[1469:3444716] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-21 16:46:57.194 ThaliTest[1469:3444716] multipeer session: reset timer
2016-03-21 16:46:57.194 ThaliTest[1469:3444716] server: disconnecting to refresh session (75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1)
2016-03-21 16:46:57.194 ThaliTest[1469:3444716] server: rejecting invitation from 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1 due to previous generation (2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:8 != 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:7)
,2016-03-21 16:46:59.400 ThaliTest[1469:3444916] jxcore: connect 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:7
2016-03-21 16:46:59.401 ThaliTest[1469:3444916] client: server will connect
2016-03-21 16:46:59.401 ThaliTest[1469:3444916] client session: reverseConnect
2016-03-21 16:46:59.402 ThaliTest[1469:3444916] client session: stateChange:0->1 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:8
,2016-03-21 16:46:59.692 ThaliTest[1469:3445293] client session: not connected 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:8
2016-03-21 16:46:59.692 ThaliTest[1469:3445293] client session: onLinkFailure: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1
2016-03-21 16:46:59.692 ThaliTest[1469:3445293] client session: disconnect
,2016-03-21 16:46:59.692 ThaliTest[1469:3445293] client session: stateChange:1->0 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:8
,2016-03-21 16:46:59.694 ThaliTest[1469:3445293] client session: no connect callback (server initiated)
,2016-03-21 16:47:00.344 ThaliTest[1469:3444716] multipeer session: reset timer
2016-03-21 16:47:00.344 ThaliTest[1469:3444716] server: disconnecting to refresh session (75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1)
2016-03-21 16:47:00.344 ThaliTest[1469:3444716], server: rejecting invitation from 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1 due to previous generation (2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:8 != 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:7)
,2016-03-21 16:47:03.456 ThaliTest[1469:3444716] multipeer session: reset timer
2016-03-21 16:47:03.456 ThaliTest[1469:3444716] server: disconnecting to refresh session (75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1)
2016-03-21 16:47:03.457 ThaliTest[1469:3444716], server: rejecting invitation from 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1 due to previous generation (2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:8 != 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:7)
,2016-03-21 16:47:09.402 ThaliTest[1469:3444716] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-21 16:47:11.288 ThaliTest[1469:3444716] multipeer manager: restart client
,2016-03-21 16:47:11.302 ThaliTest[1469:3444716] client: found existing peer: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:8
,2016-03-21 16:47:12.408 ThaliTest[1469:3444916] jxcore: connect 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:7
2016-03-21 16:47:12.409 ThaliTest[1469:3444916] client: server will connect
2016-03-21 16:47:12.409 ThaliTest[1469:3444916] client session: reverseConnect
2016-03-21 16:47:12.410 ThaliTest[1469:3444916] client session: stateChange:0->1 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:8
,2016-03-21 16:47:12.539 ThaliTest[1469:3445327] client session: not connected 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:8
2016-03-21 16:47:12.539 ThaliTest[1469:3445327] client session: onLinkFailure: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1
2016-03-21 16:47:12.5,39 ThaliTest[1469:3445327] client session: disconnect
2016-03-21 16:47:12.540 ThaliTest[1469:3445327] client session: stateChange:1->0 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:8
,2016-03-21 16:47:12.541 ThaliTest[1469:3445327] client session: no connect callback (server initiated)
,2016-03-21 16:47:22.410 ThaliTest[1469:3444716] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-21 16:47:25.417 ThaliTest[1469:3444916] jxcore: connect 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:7
2016-03-21 16:47:25.418 ThaliTest[1469:3444916] client: server will connect
2016-03-21 16:47:25.419 ThaliTest[1469:3444916] client session: reverseConn,ect
2016-03-21 16:47:25.419 ThaliTest[1469:3444916] client session: stateChange:0->1 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:8
,2016-03-21 16:47:25.703 ThaliTest[1469:3445493] client session: not connected 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:8
2016-03-21 16:47:25.703 ThaliTest[1469:3445493] client session: onLinkFailure: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1
2016-03-21 16:47:25.7,03 ThaliTest[1469:3445493] client session: disconnect
2016-03-21 16:47:25.703 ThaliTest[1469:3445493] client session: stateChange:1->0 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:8
2016-03-21 16:47:25.704 ThaliTest[1469:3445493] client session: no connect callback (server initiated)
,2016-03-21 16:47:31.288 ThaliTest[1469:3444716] multipeer manager: restart client
,2016-03-21 16:47:31.301 ThaliTest[1469:3444716] client: found existing peer: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:8
,2016-03-21 16:47:35.420 ThaliTest[1469:3444716] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-21 16:47:38.434 ThaliTest[1469:3444916] jxcore: connect 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:7
2016-03-21 16:47:38.435 ThaliTest[1469:3444916] client: server will connect
2016-03-21 16:47:38.435 ThaliTest[1469:3444916] client session: reverseConn,ect
2016-03-21 16:47:38.435 ThaliTest[1469:3444916] client session: stateChange:0->1 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:8
,2016-03-21 16:47:38.784 ThaliTest[1469:3445523] client session: not connected 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:8
2016-03-21 16:47:38.784 ThaliTest[1469:3445523] client session: onLinkFailure: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1
2016-03-21 16:47:38.784 ThaliTest[1469:3445523] client session: disconnect
,2016-03-21 16:47:38.786 ThaliTest[1469:3445523] client session: stateChange:1->0 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:8
2016-03-21 16:47:38.787 ThaliTest[1469:3445523] client session: no connect callback (server initiated)
,2016-03-21 16:47:48.436 ThaliTest[1469:3444716] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-21 16:47:51.288 ThaliTest[1469:3444716] multipeer manager: restart client
,2016-03-21 16:47:51.302 ThaliTest[1469:3444716] client: found existing peer: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:8
,2016-03-21 16:47:51.452 ThaliTest[1469:3444916] jxcore: connect 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:7
2016-03-21 16:47:51.453 ThaliTest[1469:3444916] client: server will connect
2016-03-21 16:47:51.454 ThaliTest[1469:3444916] client session: reverseConnect
2016-03-21 16:47:51.454 ThaliTest[1469:3444916] client session: stateChange:0->1 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:8
,2016-03-21 16:47:51.823 ThaliTest[1469:3445557] client session: not connected 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:8
2016-03-21 16:47:51.823 ThaliTest[1469:3445557] client session: onLinkFailure: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1
2016-03-21 16:47:51.8,23 ThaliTest[1469:3445557] client session: disconnect
2016-03-21 16:47:51.823 ThaliTest[1469:3445557] client session: stateChange:1->0 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:8
2016-03-21 16:47:51.824 ThaliTest[1469:3445557] client session: no connect callback (server initiated)
,2016-03-21 16:48:01.455 ThaliTest[1469:3444716] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-21 16:48:04.469 ThaliTest[1469:3444916] jxcore: connect 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:7
2016-03-21 16:48:04.469 ThaliTest[1469:3444916] client: server will connect
2016-03-21 16:48:04.470 ThaliTest[1469:3444916] client session: reverseConnect
2016-03-21 16:48:04.470 ThaliTest[1469:3444916] client session: stateChange:0->1 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:8
,2016-03-21 16:48:04.915 ThaliTest[1469:3445528] client session: not connected 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:8
2016-03-21 16:48:04.916 ThaliTest[1469:3445528] client session: onLinkFailure: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1
2016-03-21 16:48:04.9,16 ThaliTest[1469:3445528] client session: disconnect
2016-03-21 16:48:04.918 ThaliTest[1469:3445528] client session: stateChange:1->0 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:8
2016-03-21 16:48:04.918 ThaliTest[1469:3445528] client session: no connect callback (server initiated)
,2016-03-21 16:48:11.288 ThaliTest[1469:3444716] multipeer manager: restart client
,2016-03-21 16:48:11.301 ThaliTest[1469:3444716] client: found existing peer: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:8
,2016-03-21 16:48:14.471 ThaliTest[1469:3444716] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-21 16:48:17.483 ThaliTest[1469:3444916] jxcore: connect 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:7
2016-03-21 16:48:17.484 ThaliTest[1469:3444916] client: server will connect
2016-03-21 16:48:17.484 ThaliTest[1469:3444916] client session: reverseConnect
2016-03-21 16:48:17.485 ThaliTest[1469:3444916] client session: stateChange:0->1 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:8
,2016-03-21 16:48:17.979 ThaliTest[1469:3445670] client session: not connected 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:8
2016-03-21 16:48:17.980 ThaliTest[1469:3445670] client session: onLinkFailure: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1
2016-03-21 16:48:17.9,80 ThaliTest[1469:3445670] client session: disconnect
2016-03-21 16:48:17.980 ThaliTest[1469:3445670] client session: stateChange:1->0 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:8
,2016-03-21 16:48:17.982 ThaliTest[1469:3445670] client session: no connect callback (server initiated)
,2016-03-21 16:48:27.486 ThaliTest[1469:3444716] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-21 16:48:30.493 ThaliTest[1469:3444916] jxcore: connect 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:7
2016-03-21 16:48:30.494 ThaliTest[1469:3444916] client: server will connect
2016-03-21 16:48:30.494 ThaliTest[1469:3444916] client session: reverseConnect
2016-03-21 16:48:30.494 ThaliTest[1469:3444916] client session: stateChange:0->1 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:8
,2016-03-21 16:48:31.165 ThaliTest[1469:3445713] client session: not connected 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:8
2016-03-21 16:48:31.165 ThaliTest[1469:3445713] client session: onLinkFailure: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1
2016-03-21 16:48:31.1,66 ThaliTest[1469:3445713] client session: disconnect
2016-03-21 16:48:31.166 ThaliTest[1469:3445713] client session: stateChange:1->0 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:8
2016-03-21 16:48:31.166 ThaliTest[1469:3445713] client session: no connect callback (server initiated)
,2016-03-21 16:48:31.288 ThaliTest[1469:3444716] multipeer manager: restart client
,2016-03-21 16:48:31.303 ThaliTest[1469:3444716] client: found existing peer: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:8
,2016-03-21 16:48:40.495 ThaliTest[1469:3444716] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,WARN testThaliMobileNative: Too many connect retries!
,not ok 157 Connect failed!
  ---
,    operator: fail
,  ...
,# setup
,2016-03-21 16:48:40.795 ThaliTest[1469:3444916] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-21 16:48:40.796 ThaliTest[1469:3444916] jxcore: stopListeningForAdvertisements: success
,ok 158 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-21 16:48:40.798 ThaliTest[1469:3444916] jxcore: stopAdvertisingAndListening
2016-03-21 16:48:40.798 ThaliTest[1469:3444916] THEMultipeerManager stopping peer
2016-03-21 16:48:40.799 ThaliTest[1469:3444916] multipeer manager: stop client timer
2016-03-21 16:48:40.799 ThaliTest[1469:3444916] jxcore: stopAdvertisingAndListening: success
ok 159 Should be able to call stopAdvertisingAndListening in teardown
,# 38. Can shift large amounts of data
,# teardown
,2016-03-21 16:48:42.478 ThaliTest[1469:3444916] jxcore: startUpdateAdvertisingAndListening
2016-03-21 16:48:42.478 ThaliTest[1469:3444916] server: starting 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:9
2016-03-21 16:48:42.478 ThaliTest[1469:3444916] multipeer m,anager: start client restart timer: 0x1658e1c0
2016-03-21 16:48:42.479 ThaliTest[1469:3444916] THEMultipeerManager initialized peer 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:9
2016-03-21 16:48:42.479 ThaliTest[1469:3444916] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 160 Can call startUpdateAdvertisingAndListening without error
,2016-03-21 16:48:42.481 ThaliTest[1469:3444916] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
,2016-03-21 16:48:42.483 ThaliTest[1469:3444916] jxcore: startListeningForAdvertisements: success
,ok 161 Can call startListeningForAdvertisements without error
,2016-03-21 16:48:42.587 ThaliTest[1469:3444716] client: found new peer: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:8
2016-03-21 16:48:42.588 ThaliTest[1469:3444916] jxcore: connect 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:8
2016-03-21 16:48:42.589 ThaliTest[1469:3,444916] client: server will connect
2016-03-21 16:48:42.589 ThaliTest[1469:3444916] client session: reverseConnect
2016-03-21 16:48:42.590 ThaliTest[1469:3444916] client session: stateChange:0->1 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:8
,2016-03-21 16:48:44.787 ThaliTest[1469:3445740] client session: not connected 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:8
2016-03-21 16:48:44.788 ThaliTest[1469:3445740] client session: onLinkFailure: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1
2016-03-21 16:48:44.7,88 ThaliTest[1469:3445740] client session: disconnect
2016-03-21 16:48:44.788 ThaliTest[1469:3445740] client session: stateChange:1->0 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:8
2016-03-21 16:48:44.788 ThaliTest[1469:3445740] client session: no connect callback (server initiated)
,2016-03-21 16:48:52.591 ThaliTest[1469:3444716] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-21 16:48:55.597 ThaliTest[1469:3444916] jxcore: connect 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:8
2016-03-21 16:48:55.598 ThaliTest[1469:3444916] client: server will connect
2016-03-21 16:48:55.598 ThaliTest[1469:3444916] client session: reverseConnect
2016-03-21 16:48:55.599 ThaliTest[1469:3444916] client session: stateChange:0->1 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:8
,2016-03-21 16:48:55.787 ThaliTest[1469:3445715] client session: not connected 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:8
2016-03-21 16:48:55.787 ThaliTest[1469:3445715] client session: onLinkFailure: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1
2016-03-21 16:48:55.7,87 ThaliTest[1469:3445715] client session: disconnect
,2016-03-21 16:48:55.788 ThaliTest[1469:3445715] client session: stateChange:1->0 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:8
2016-03-21 16:48:55.789 ThaliTest[1469:3445715] client session: no connect callback (server initiated)
,2016-03-21 16:49:02.480 ThaliTest[1469:3444716] multipeer manager: restart client
,2016-03-21 16:49:02.494 ThaliTest[1469:3444716] client: found updated peer: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:9
,2016-03-21 16:49:03.130 ThaliTest[1469:3444716] multipeer session: reset timer
2016-03-21 16:49:03.131 ThaliTest[1469:3444716] server session: connect
2016-03-21 16:49:03.131 ThaliTest[1469:3444716] server session: stateChange:0->1 75CF4C6C-ED3C-4F8C-A62,3-CB08A4F1A8F1:9
,2016-03-21 16:49:03.137 ThaliTest[1469:3444716] server: accepting invitation 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1
,2016-03-21 16:49:05.599 ThaliTest[1469:3444716] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-21 16:49:05.740 ThaliTest[1469:3445715] server session: p2p link connected
,2016-03-21 16:49:06.084 ThaliTest[1469:3444716] server relay: connected (to port: 50604)
,2016-03-21 16:49:06.085 ThaliTest[1469:3444716] server session: stateChange:1->2 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:9
,2016-03-21 16:49:08.608 ThaliTest[1469:3444916] jxcore: connect 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:8
2016-03-21 16:49:08.609 ThaliTest[1469:3444916] client: server already connected
2016-03-21 16:49:08.609 ThaliTest[1469:3444916] jxcore: connect: success
INFO testThaliMobileNative: 
,INFO testThaliMobileNative: Reverse connection
,2016-03-21 16:49:22.479 ThaliTest[1469:3444716] multipeer manager: restart client
,2016-03-21 16:49:22.494 ThaliTest[1469:3444716] client: found existing peer: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:9
,2016-03-21 16:49:42.480 ThaliTest[1469:3444716] multipeer manager: restart client
,2016-03-21 16:49:42.494 ThaliTest[1469:3444716] client: found existing peer: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:9
,2016-03-21 16:50:02.480 ThaliTest[1469:3444716] multipeer manager: restart client
,2016-03-21 16:50:02.494 ThaliTest[1469:3444716] client: found existing peer: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:9
,2016-03-21 16:50:22.479 ThaliTest[1469:3444716] multipeer manager: restart client
,2016-03-21 16:50:22.492 ThaliTest[1469:3444716] client: found existing peer: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:9
,2016-03-21 16:50:42.480 ThaliTest[1469:3444716] multipeer manager: restart client
,2016-03-21 16:50:42.494 ThaliTest[1469:3444716] client: found existing peer: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:9
,2016-03-21 16:51:02.480 ThaliTest[1469:3444716] multipeer manager: restart client
,2016-03-21 16:51:02.493 ThaliTest[1469:3444716] client: found existing peer: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:9
,2016-03-21 16:51:22.480 ThaliTest[1469:3444716] multipeer manager: restart client
,2016-03-21 16:51:22.496 ThaliTest[1469:3444716] client: found existing peer: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:9
,2016-03-21 16:51:42.480 ThaliTest[1469:3444716] multipeer manager: restart client
,2016-03-21 16:51:42.492 ThaliTest[1469:3444716] client: found existing peer: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:9
,2016-03-21 16:52:02.480 ThaliTest[1469:3444716] multipeer manager: restart client
,2016-03-21 16:52:02.495 ThaliTest[1469:3444716] client: found existing peer: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:9
,2016-03-21 16:52:22.480 ThaliTest[1469:3444716] multipeer manager: restart client
,2016-03-21 16:52:22.494 ThaliTest[1469:3444716] client: found existing peer: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:9
,2016-03-21 16:52:42.480 ThaliTest[1469:3444716] multipeer manager: restart client
,2016-03-21 16:52:42.492 ThaliTest[1469:3444716] client: found existing peer: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:9
,2016-03-21 16:53:02.480 ThaliTest[1469:3444716] multipeer manager: restart client
,2016-03-21 16:53:02.494 ThaliTest[1469:3444716] client: found existing peer: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:9
,2016-03-21 16:53:22.480 ThaliTest[1469:3444716] multipeer manager: restart client
,2016-03-21 16:53:22.493 ThaliTest[1469:3444716] client: found existing peer: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:9
,2016-03-21 16:53:42.480 ThaliTest[1469:3444716] multipeer manager: restart client
,2016-03-21 16:53:42.494 ThaliTest[1469:3444716] client: found existing peer: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:9
,2016-03-21 16:54:02.480 ThaliTest[1469:3444716] multipeer manager: restart client
,2016-03-21 16:54:02.494 ThaliTest[1469:3444716] client: found existing peer: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:9
,2016-03-21 16:54:22.480 ThaliTest[1469:3444716] multipeer manager: restart client
,2016-03-21 16:54:22.494 ThaliTest[1469:3444716] client: found existing peer: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:9
,2016-03-21 16:54:42.480 ThaliTest[1469:3444716] multipeer manager: restart client
,2016-03-21 16:54:42.494 ThaliTest[1469:3444716] client: found existing peer: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:9
,2016-03-21 16:55:02.480 ThaliTest[1469:3444716] multipeer manager: restart client
,2016-03-21 16:55:02.493 ThaliTest[1469:3444716] client: found existing peer: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:9
,2016-03-21 16:55:22.480 ThaliTest[1469:3444716] multipeer manager: restart client
,2016-03-21 16:55:22.493 ThaliTest[1469:3444716] client: found existing peer: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:9
,2016-03-21 16:55:42.480 ThaliTest[1469:3444716] multipeer manager: restart client
,2016-03-21 16:56:02.480 ThaliTest[1469:3444716] multipeer manager: restart client
,2016-03-21 16:56:02.488 ThaliTest[1469:3444716] client: found existing peer: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:9
,2016-03-21 16:56:22.480 ThaliTest[1469:3444716] multipeer manager: restart client
,2016-03-21 16:56:22.489 ThaliTest[1469:3444716] client: found existing peer: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:9
,2016-03-21 16:56:42.480 ThaliTest[1469:3444716] multipeer manager: restart client
,2016-03-21 16:56:42.490 ThaliTest[1469:3444716] client: found existing peer: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:9
,2016-03-21 16:57:02.480 ThaliTest[1469:3444716] multipeer manager: restart client
,2016-03-21 16:57:02.490 ThaliTest[1469:3444716] client: found existing peer: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:9
,2016-03-21 16:57:22.480 ThaliTest[1469:3444716] multipeer manager: restart client
,2016-03-21 16:57:22.489 ThaliTest[1469:3444716] client: found existing peer: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:9
,2016-03-21 16:57:42.480 ThaliTest[1469:3444716] multipeer manager: restart client
,2016-03-21 16:57:42.490 ThaliTest[1469:3444716] client: found existing peer: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:9
,2016-03-21 16:58:02.480 ThaliTest[1469:3444716] multipeer manager: restart client
,2016-03-21 16:58:02.489 ThaliTest[1469:3444716] client: found existing peer: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:9
,2016-03-21 16:58:22.480 ThaliTest[1469:3444716] multipeer manager: restart client
,2016-03-21 16:58:22.490 ThaliTest[1469:3444716] client: found existing peer: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:9
,2016-03-21 16:58:42.480 ThaliTest[1469:3444716] multipeer manager: restart client
,2016-03-21 16:58:42.489 ThaliTest[1469:3444716] client: found existing peer: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:9
,2016-03-21 16:59:02.480 ThaliTest[1469:3444716] multipeer manager: restart client
,2016-03-21 16:59:02.489 ThaliTest[1469:3444716] client: found existing peer: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:9
,2016-03-21 16:59:22.480 ThaliTest[1469:3444716] multipeer manager: restart client
,2016-03-21 16:59:42.479 ThaliTest[1469:3444716] multipeer manager: restart client
,2016-03-21 16:59:42.489 ThaliTest[1469:3444716] client: found existing peer: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:9
,2016-03-21 17:00:02.480 ThaliTest[1469:3444716] multipeer manager: restart client
,2016-03-21 17:00:02.488 ThaliTest[1469:3444716] client: found existing peer: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:9
,2016-03-21 17:00:22.480 ThaliTest[1469:3444716] multipeer manager: restart client
,2016-03-21 17:00:22.489 ThaliTest[1469:3444716] client: found existing peer: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:9
,2016-03-21 17:00:42.480 ThaliTest[1469:3444716] multipeer manager: restart client
,2016-03-21 17:00:42.490 ThaliTest[1469:3444716] client: found existing peer: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:9
,2016-03-21 17:01:02.480 ThaliTest[1469:3444716] multipeer manager: restart client
,2016-03-21 17:01:02.490 ThaliTest[1469:3444716] client: found existing peer: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:9
,2016-03-21 17:01:22.480 ThaliTest[1469:3444716] multipeer manager: restart client
,2016-03-21 17:01:22.490 ThaliTest[1469:3444716] client: found existing peer: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:9
,2016-03-21 17:01:42.480 ThaliTest[1469:3444716] multipeer manager: restart client
,2016-03-21 17:01:42.492 ThaliTest[1469:3444716] client: found existing peer: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:9
,2016-03-21 17:02:02.479 ThaliTest[1469:3444716] multipeer manager: restart client
,2016-03-21 17:02:02.490 ThaliTest[1469:3444716] client: found existing peer: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:9
,2016-03-21 17:02:22.480 ThaliTest[1469:3444716] multipeer manager: restart client
,2016-03-21 17:02:22.490 ThaliTest[1469:3444716] client: found existing peer: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:9
,2016-03-21 17:02:42.480 ThaliTest[1469:3444716] multipeer manager: restart client
,2016-03-21 17:02:42.489 ThaliTest[1469:3444716] client: found existing peer: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:9
,2016-03-21 17:03:02.480 ThaliTest[1469:3444716] multipeer manager: restart client
,2016-03-21 17:03:02.489 ThaliTest[1469:3444716] client: found existing peer: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:9
,2016-03-21 17:03:22.480 ThaliTest[1469:3444716] multipeer manager: restart client
,2016-03-21 17:03:22.491 ThaliTest[1469:3444716] client: found existing peer: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:9
,2016-03-21 17:03:42.480 ThaliTest[1469:3444716] multipeer manager: restart client
,2016-03-21 17:03:42.490 ThaliTest[1469:3444716] client: found existing peer: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:9
,2016-03-21 17:04:02.480 ThaliTest[1469:3444716] multipeer manager: restart client
,2016-03-21 17:04:02.490 ThaliTest[1469:3444716] client: found existing peer: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:9
,2016-03-21 17:04:22.480 ThaliTest[1469:3444716] multipeer manager: restart client
,2016-03-21 17:04:22.489 ThaliTest[1469:3444716] client: found existing peer: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:9
,2016-03-21 17:04:42.479 ThaliTest[1469:3444716] multipeer manager: restart client
,2016-03-21 17:04:42.489 ThaliTest[1469:3444716] client: found existing peer: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:9
,2016-03-21 17:05:02.479 ThaliTest[1469:3444716] multipeer manager: restart client
,2016-03-21 17:05:02.489 ThaliTest[1469:3444716] client: found existing peer: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:9
,2016-03-21 17:05:22.480 ThaliTest[1469:3444716] multipeer manager: restart client
,2016-03-21 17:05:22.488 ThaliTest[1469:3444716] client: found existing peer: 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:9

```
