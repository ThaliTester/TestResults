#### Test 67111490059a058_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/67111490059a058/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/0608D0C7-F113-4DFF-B070-AEF8878FCD66/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/0608D0C7-F113-4DFF-B070-AEF8878FCD66/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/67111490059a058/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/67111490059a058/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/086803E5-ADAF-486A-B308-FDC1CB6E6EF4/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54005"
,(lldb)     command script import "/tmp/0608D0C7-F113-4DFF-B070-AEF8878FCD66/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-04-20 04:46:46.004 ThaliTest[2573:7921281] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0368818B-AB3A-4913-B262-CE1E88850B5E/Library/Cookies/Cookies.binarycookies
,2016-04-20 04:46:46.118 ThaliTest[2573:7921281] Apache Cordova native platform version 4.1.1 is starting.
,2016-04-20 04:46:46.120 ThaliTest[2573:7921281] Multi-tasking -> Device: YES, App: YES
,2016-04-20 04:46:46.140 ThaliTest[2573:7921281] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-04-20 04:46:48.514 ThaliTest[2573:7921281] Using UIWebView
,2016-04-20 04:46:48.521 ThaliTest[2573:7921281] [CDVTimer][handleopenurl] 0.334024ms
,2016-04-20 04:46:48.526 ThaliTest[2573:7921281] [CDVTimer][intentandnavigationfilter] 5.177975ms
2016-04-20 04:46:48.527 ThaliTest[2573:7921281] [CDVTimer][gesturehandler] 0.254989ms
2016-04-20 04:46:48.527 ThaliTest[2573:7921281] [CDVTimer][TotalPluginStartup] 6.799996ms
,2016-04-20 04:46:57.838 ThaliTest[2573:7921281] Resetting plugins due to page load.
,2016-04-20 04:47:02.425 ThaliTest[2573:7921281] Finished load of: file:///var/mobile/Containers/Bundle/Application/086803E5-ADAF-486A-B308-FDC1CB6E6EF4/ThaliTest.app/www/index.html
,2016-04-20 04:47:02.615 ThaliTest[2573:7921281] JXcore Cordova plugin initializing
,2016-04-20 04:47:02.617 ThaliTest[2573:7921477] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-04-20 04:47:19.752 ThaliTest[2573:7921477] jxcore: didRegisterToNative peerAvailabilityChanged
2016-04-20 04:47:19.752 ThaliTest[2573:7921477] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-04-20 04:47:19.753 ThaliTest[2573:7,921477] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-04-20 04:47:19.756 ThaliTest[2573:7921477] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5-1
,WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/086803E5-ADAF-486A-B308-FDC1CB6E6EF4/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/086803E5-ADAF-486A-B308-FDC1CB6E6EF4/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/086803E5-ADAF-486A-B308-FDC1CB6E6EF4/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/086803E5-ADAF-486A-B308-FDC1CB6E6EF4/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/086803E5-ADAF-486A-B308-FDC1CB6E6EF4/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/086803E5-ADAF-486A-B308-FDC1CB6E6EF4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/086803E5-ADAF-486A-B308-FDC1CB6E6EF4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/086803E5-ADAF-486A-B308-FDC1CB6E6EF4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/086803E5-ADAF-486A-B308-FDC1CB6E6EF4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/086803E5-ADAF-486A-B308-FDC1CB6E6EF4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/086803E5-ADAF-486A-B308-FDC1CB6E6EF4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/086803E5-ADAF-486A-B308-FDC1CB6E6EF4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/086803E5-ADAF-486A-B308-FDC1CB6E6EF4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/086803E5-ADAF-486A-B308-FDC1CB6E6EF4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/086803E5-ADAF-486A-B308-FDC1CB6E6EF4/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/086803E5-ADAF-486A-B308-FDC1CB6E6EF4/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/086803E5-ADAF-486A-B308-FDC1CB6E6EF4/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/086803E5-ADAF-486A-B308-FDC1CB6E6EF4/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/086803E5-ADAF-486A-B308-FDC1CB6E6EF4/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/086803E5-ADAF-486A-B308-FDC1CB6E6EF4/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/086803E5-ADAF-486A-B308-FDC1CB6E6EF4/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/086803E5-ADAF-486A-B308-FDC1CB6E6EF4/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-04-20 04:47:35.091 ThaliTest[2573:7921281] THREAD WARNING: ['JXcore'] took '14635.104004' ms. Plugin should use a background thread.
,2016-04-20 04:47:35.093 ThaliTest[2573:7921414] void SendDelegateMessage(NSInvocation *): delegate (webView:decidePolicyForNavigationAction:request:frame:decisionListener:) failed to return after waiting 10 seconds. main run loop mode: kCFRunLoopDefaultMode
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 60567
,ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 60569
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
,DEBUG createNativeListener: listening 60572
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
,DEBUG createNativeListener: listening 60576
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
,DEBUG createNativeListener: listening 60581
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
,DEBUG createNativeListener: listening 60585
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
,DEBUG createNativeListener: listening 60589
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
,DEBUG createNativeListener: listening 60593
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
,DEBUG createNativeListener: listening 60597
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
,DEBUG createNativeListener: listening 60649
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
,DEBUG createNativeListener: listening 60653
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
,[{"uuid":"bfdc7c82-3e48-4c76-97f8-19cc4d017af4","data":"custom data"},{"uuid":"193381e1-e38b-4d7e-b0af-8de5815cb621","data":"custom data"},{"uuid":"06642e6b-b55e-487b-9d1a-ac467e3aa68a","data":"custom data"},{"uuid":"da57b363-146c-4326-bcf1-87fd4d08657a","data":"custom data"}]
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
,DEBUG createNativeListener: listening 60663
,2016-04-20 04:50:07.046 ThaliTest[2573:7921477] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-20 04:50:07.048 ThaliTest[2573:7921477] jxcore: stopListeningForAdvertisements: success
,ok 91 error should be null
,ok 92 error should be null
,2016-04-20 04:50:07.052 ThaliTest[2573:7921477] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-20 04:50:07.054 ThaliTest[2573:7921477] jxcore: stopListeningForAdvertisements: success
,ok 93 error should be null
,ok 94 error should be null
,# teardown
,2016-04-20 04:50:07.168 ThaliTest[2573:7921477] jxcore: stopAdvertisingAndListening
2016-04-20 04:50:07.168 ThaliTest[2573:7921477] THEMultipeerManager stopping peer
,2016-04-20 04:50:07.168 ThaliTest[2573:7921477] jxcore: stopAdvertisingAndListening: success
2016-04-20 04:50:07.169 ThaliTest[2573:7921477] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"a,dvertisingActive":false,"discoveryActive":false}
2016-04-20 04:50:07.171 ThaliTest[2573:7921477] jxcore: stopListeningForAdvertisements: success
,ok 95 error should be null
,ok 96 error should be null
,# setup
,# 26. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 60665
,2016-04-20 04:50:07.367 ThaliTest[2573:7921477] jxcore: startListeningForAdvertisements
,2016-04-20 04:50:07.369 ThaliTest[2573:7921477] multipeer manager: start client restart timer: 0x145b3c40
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-20 04:50:07.372 ThaliTest[2573:7921477] jxcore: startListeningForAdvertisements: success
,ok 97 error should be null
,ok 98 error should be null
,2016-04-20 04:50:07.432 ThaliTest[2573:7921477] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-20 04:50:07.434 ThaliTest[2573:7921477] jxcore: startListeningForAdvertisements: success
,ok 99 error should be null
,ok 100 error should be null
,# teardown
,2016-04-20 04:50:07.694 ThaliTest[2573:7921477] jxcore: stopAdvertisingAndListening
2016-04-20 04:50:07.695 ThaliTest[2573:7921477] THEMultipeerManager stopping peer
2016-04-20 04:50:07.695 ThaliTest[2573:7921477] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-20 04:50:07.695 ThaliTest[2573:7921477] jxcore: stopListeningForAdvertisements
2016-04-20 04:50:07.695 ThaliTest[2573:7921477] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-04-20 04:50:07.697 ThaliTest[2573:7921477] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 101 error should be null
,ok 102 error should be null
,# setup
,# 27. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 60667
,2016-04-20 04:50:08.233 ThaliTest[2573:7921477] jxcore: startUpdateAdvertisingAndListening
,2016-04-20 04:50:08.234 ThaliTest[2573:7921477] server: starting FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:1
2016-04-20 04:50:08.235 ThaliTest[2573:7921477] multipeer manager: start client restart timer: 0x145b3c40
2016-04-20 04:50:08.235 ThaliTest[2573:79214,77] THEMultipeerManager initialized peer FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:1
2016-04-20 04:50:08.235 ThaliTest[2573:7921477] jxcore: startUpdateAdvertisingAndListening: success
,ok 103 error should be null
ok 104 error should be null
,2016-04-20 04:50:08.253 ThaliTest[2573:7921477] jxcore: startUpdateAdvertisingAndListening
2016-04-20 04:50:08.254 ThaliTest[2573:7921477] THEMultipeerManager stopping peer
2016-04-20 04:50:08.254 ThaliTest[2573:7921477] multipeer manager: stop client ti,mer
2016-04-20 04:50:08.255 ThaliTest[2573:7921477] server: starting FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:2
2016-04-20 04:50:08.255 ThaliTest[2573:7921477] multipeer manager: start client restart timer: 0x145b3c40
2016-04-20 04:50:08.256 ThaliTest[2573:,7921477] THEMultipeerManager initialized peer FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:2
2016-04-20 04:50:08.256 ThaliTest[2573:7921477] jxcore: startUpdateAdvertisingAndListening: success
,ok 105 error should be null
,ok 106 error should be null
,# teardown
,2016-04-20 04:50:09.663 ThaliTest[2573:7921281] client: found new peer: 98501501-ECD9-4428-8F6B-7983BCB3CA3C:2
2016-04-20 04:50:09.663 ThaliTest[2573:7921281] client: found new peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:2
,2016-04-20 04:50:11.216 ThaliTest[2573:7921281] client: lost peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1
2016-04-20 04:50:11.216 ThaliTest[2573:7921281] client session: onPeerLost: DF7D62F5-96D1-401F-B736-926B7A8C54F1
,2016-04-20 04:50:11.508 ThaliTest[2573:7921281] client: lost peer: 98501501-ECD9-4428-8F6B-7983BCB3CA3C
2016-04-20 04:50:11.509 ThaliTest[2573:7921281] client session: onPeerLost: 98501501-ECD9-4428-8F6B-7983BCB3CA3C
,2016-04-20 04:50:21.824 ThaliTest[2573:7921477] jxcore: stopAdvertisingAndListening
,2016-04-20 04:50:21.824 ThaliTest[2573:7921477] THEMultipeerManager stopping peer
2016-04-20 04:50:21.825 ThaliTest[2573:7921477] multipeer manager: stop client timer
2016-04-20 04:50:21.826 ThaliTest[2573:7921477] jxcore: stopAdvertisingAndListening: su,ccess
2016-04-20 04:50:21.826 ThaliTest[2573:7921477] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-20 04:50:21.827 ThaliTest[2573:7921477] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 107 error should be null
,ok 108 error should be null
,# setup
,# 28. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 60672
,2016-04-20 04:50:51.096 ThaliTest[2573:7921477] jxcore: stopAdvertisingAndListening
2016-04-20 04:50:51.097 ThaliTest[2573:7921477] THEMultipeerManager stopping peer
2016-04-20 04:50:51.097 ThaliTest[2573:7921477] jxcore: stopAdvertisingAndListening: success
ok 109 error should be null
,ok 110 error should be null
,2016-04-20 04:50:51.101 ThaliTest[2573:7921477] jxcore: stopAdvertisingAndListening
2016-04-20 04:50:51.101 ThaliTest[2573:7921477] THEMultipeerManager stopping peer
2016-04-20 04:50:51.101 ThaliTest[2573:7921477] jxcore: stopAdvertisingAndListening: success
,ok 111 error should be null
,ok 112 error should be null
,# teardown
,2016-04-20 04:50:51.203 ThaliTest[2573:7921477] jxcore: stopAdvertisingAndListening
2016-04-20 04:50:51.203 ThaliTest[2573:7921477] THEMultipeerManager stopping peer
2016-04-20 04:50:51.203 ThaliTest[2573:7921477] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-20 04:50:51.203 ThaliTest[2573:7921477] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-20 04:50:51.204 ThaliTest[2573,:7921477] jxcore: stopListeningForAdvertisements: success
,ok 113 error should be null
,ok 114 error should be null
,# setup
,# 29. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 60674
,ok 115 first call should succeed
,ok 116 first call should succeed
,ok 117 specific error should be returned
,# teardown
,2016-04-20 04:50:51.531 ThaliTest[2573:7921477] jxcore: stopAdvertisingAndListening
2016-04-20 04:50:51.531 ThaliTest[2573:7921477] THEMultipeerManager stopping peer
2016-04-20 04:50:51.532 ThaliTest[2573:7921477] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-20 04:50:51.532 ThaliTest[2573:7921477] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-20 04:50:51.533 ThaliTest[2573:7921477] jxcore: stopListeningForAdvertisements: success
,ok 118 error should be null
,ok 119 error should be null
,# setup
,# 30. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 60676
,2016-04-20 04:50:51.733 ThaliTest[2573:7921477] jxcore: startListeningForAdvertisements
2016-04-20 04:50:51.734 ThaliTest[2573:7921477] multipeer manager: start client restart timer: 0x145b3c40
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-20 04:50:51.735 ThaliTest[2573:7921477] jxcore: startListeningForAdvertisements: success
,2016-04-20 04:50:51.770 ThaliTest[2573:7921477] jxcore: startUpdateAdvertisingAndListening
2016-04-20 04:50:51.771 ThaliTest[2573:7921477] server: starting FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 04:50:51.771 ThaliTest[2573:7921477] THEMultipee,rManager initialized peer FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 04:50:51.771 ThaliTest[2573:7921477] jxcore: startUpdateAdvertisingAndListening: success
,ok 120 called only once
ok 121 discovery state matches
ok 122 advertising state matches
,# teardown
,2016-04-20 04:50:53.608 ThaliTest[2573:7921281] client: found new peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:2
,DEBUG createPeerListener: createPeerListener creating new server
,DEBUG createPeerListener: pleaseConnect= 0
,2016-04-20 04:50:55.121 ThaliTest[2573:7921281] client: found new peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,DEBUG createPeerListener: createPeerListener creating new server
,DEBUG createPeerListener: pleaseConnect= 0
,2016-04-20 04:51:11.735 ThaliTest[2573:7921281] multipeer manager: restart client
,2016-04-20 04:51:11.758 ThaliTest[2573:7921281] client: found updated peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 04:51:11.759 ThaliTest[2573:7921281] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,DEBUG createPeerListener: createPeerListener creating new server
,DEBUG createPeerListener: pleaseConnect= 0
,2016-04-20 04:51:31.735 ThaliTest[2573:7921281] multipeer manager: restart client
,2016-04-20 04:51:31.758 ThaliTest[2573:7921281] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
2016-04-20 04:51:31.759 ThaliTest[2573:7921281] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
,2016-04-20 04:51:51.735 ThaliTest[2573:7921281] multipeer manager: restart client
,2016-04-20 04:51:51.754 ThaliTest[2573:7921281] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
,2016-04-20 04:51:51.759 ThaliTest[2573:7921281] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 04:52:11.735 ThaliTest[2573:7921281] multipeer manager: restart client
,2016-04-20 04:52:11.757 ThaliTest[2573:7921281] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 04:52:11.757 ThaliTest[2573:7921281] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 04:52:31.735 ThaliTest[2573:7921281] multipeer manager: restart client
,2016-04-20 04:52:31.755 ThaliTest[2573:7921281] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
2016-04-20 04:52:31.755 ThaliTest[2573:7921281] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
,2016-04-20 04:52:51.735 ThaliTest[2573:7921281] multipeer manager: restart client
,2016-04-20 04:52:51.757 ThaliTest[2573:7921281] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 04:52:51.760 ThaliTest[2573:7921281] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 04:53:11.735 ThaliTest[2573:7921281] multipeer manager: restart client
,2016-04-20 04:53:11.757 ThaliTest[2573:7921281] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 04:53:11.757 ThaliTest[2573:7921281] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 04:53:31.735 ThaliTest[2573:7921281] multipeer manager: restart client
,2016-04-20 04:53:31.753 ThaliTest[2573:7921281] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 04:53:31.755 ThaliTest[2573:7921281] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 04:53:51.735 ThaliTest[2573:7921281] multipeer manager: restart client
,2016-04-20 04:53:51.757 ThaliTest[2573:7921281] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 04:53:51.758 ThaliTest[2573:7921281] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 04:54:11.735 ThaliTest[2573:7921281] multipeer manager: restart client
,2016-04-20 04:54:11.756 ThaliTest[2573:7921281] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 04:54:11.757 ThaliTest[2573:7921281] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 04:54:31.735 ThaliTest[2573:7921281] multipeer manager: restart client
,2016-04-20 04:54:31.756 ThaliTest[2573:7921281] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
,2016-04-20 04:54:31.760 ThaliTest[2573:7921281] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 04:54:51.735 ThaliTest[2573:7921281] multipeer manager: restart client
,2016-04-20 04:54:51.757 ThaliTest[2573:7921281] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 04:54:51.759 ThaliTest[2573:7921281] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 04:55:11.735 ThaliTest[2573:7921281] multipeer manager: restart client
,2016-04-20 04:55:11.757 ThaliTest[2573:7921281] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 04:55:11.758 ThaliTest[2573:7921281] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 04:55:31.735 ThaliTest[2573:7921281] multipeer manager: restart client
,2016-04-20 04:55:31.757 ThaliTest[2573:7921281] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 04:55:31.757 ThaliTest[2573:7921281] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 04:55:51.735 ThaliTest[2573:7921281] multipeer manager: restart client
,2016-04-20 04:55:51.756 ThaliTest[2573:7921281] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
2016-04-20 04:55:51.756 ThaliTest[2573:7921281] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
,2016-04-20 04:56:11.735 ThaliTest[2573:7921281] multipeer manager: restart client
,2016-04-20 04:56:11.756 ThaliTest[2573:7921281] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 04:56:11.758 ThaliTest[2573:7921281] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 04:56:31.735 ThaliTest[2573:7921281] multipeer manager: restart client
,2016-04-20 04:56:31.756 ThaliTest[2573:7921281] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
2016-04-20 04:56:31.757 ThaliTest[2573:7921281] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
,2016-04-20 04:56:51.735 ThaliTest[2573:7921281] multipeer manager: restart client
,2016-04-20 04:56:51.756 ThaliTest[2573:7921281] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 04:56:51.757 ThaliTest[2573:7921281] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 04:57:11.735 ThaliTest[2573:7921281] multipeer manager: restart client
,2016-04-20 04:57:11.755 ThaliTest[2573:7921281] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 04:57:11.757 ThaliTest[2573:7921281] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 04:57:31.735 ThaliTest[2573:7921281] multipeer manager: restart client
,2016-04-20 04:57:31.759 ThaliTest[2573:7921281] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 04:57:31.759 ThaliTest[2573:7921281] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 04:57:51.735 ThaliTest[2573:7921281] multipeer manager: restart client
,2016-04-20 04:57:51.757 ThaliTest[2573:7921281] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 04:57:51.758 ThaliTest[2573:7921281] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 04:58:11.735 ThaliTest[2573:7921281] multipeer manager: restart client
,2016-04-20 04:58:11.757 ThaliTest[2573:7921281] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 04:58:11.759 ThaliTest[2573:7921281] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 04:58:31.735 ThaliTest[2573:7921281] multipeer manager: restart client
,2016-04-20 04:58:31.755 ThaliTest[2573:7921281] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 04:58:31.757 ThaliTest[2573:7921281] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 04:58:51.735 ThaliTest[2573:7921281] multipeer manager: restart client
,2016-04-20 04:58:51.756 ThaliTest[2573:7921281] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
2016-04-20 04:58:51.756 ThaliTest[2573:7921281] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
,2016-04-20 04:59:11.735 ThaliTest[2573:7921281] multipeer manager: restart client
,2016-04-20 04:59:11.757 ThaliTest[2573:7921281] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
,2016-04-20 04:59:11.759 ThaliTest[2573:7921281] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 04:59:31.735 ThaliTest[2573:7921281] multipeer manager: restart client
,2016-04-20 04:59:31.757 ThaliTest[2573:7921281] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 04:59:31.758 ThaliTest[2573:7921281] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 04:59:51.735 ThaliTest[2573:7921281] multipeer manager: restart client
,2016-04-20 04:59:51.756 ThaliTest[2573:7921281] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
,2016-04-20 04:59:51.760 ThaliTest[2573:7921281] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 05:00:11.735 ThaliTest[2573:7921281] multipeer manager: restart client
,2016-04-20 05:00:11.756 ThaliTest[2573:7921281] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 05:00:11.757 ThaliTest[2573:7921281] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 05:00:31.735 ThaliTest[2573:7921281] multipeer manager: restart client
,2016-04-20 05:00:31.755 ThaliTest[2573:7921281] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 05:00:31.755 ThaliTest[2573:7921281] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 05:00:51.735 ThaliTest[2573:7921281] multipeer manager: restart client
,2016-04-20 05:00:51.757 ThaliTest[2573:7921281] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 05:00:51.757 ThaliTest[2573:7921281] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 05:01:11.735 ThaliTest[2573:7921281] multipeer manager: restart client
,2016-04-20 05:01:11.757 ThaliTest[2573:7921281] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 05:01:11.757 ThaliTest[2573:7921281] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 05:01:31.735 ThaliTest[2573:7921281] multipeer manager: restart client
,2016-04-20 05:01:51.735 ThaliTest[2573:7921281] multipeer manager: restart client
,2016-04-20 05:01:51.758 ThaliTest[2573:7921281] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
,2016-04-20 05:01:51.760 ThaliTest[2573:7921281] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 05:02:11.735 ThaliTest[2573:7921281] multipeer manager: restart client
,2016-04-20 05:02:11.755 ThaliTest[2573:7921281] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 05:02:11.758 ThaliTest[2573:7921281] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 05:02:31.735 ThaliTest[2573:7921281] multipeer manager: restart client
,2016-04-20 05:02:31.755 ThaliTest[2573:7921281] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 05:02:31.756 ThaliTest[2573:7921281] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 05:02:51.735 ThaliTest[2573:7921281] multipeer manager: restart client
,2016-04-20 05:02:51.757 ThaliTest[2573:7921281] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 05:02:51.758 ThaliTest[2573:7921281] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 05:03:11.735 ThaliTest[2573:7921281] multipeer manager: restart client
,2016-04-20 05:03:11.757 ThaliTest[2573:7921281] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 05:03:11.758 ThaliTest[2573:7921281] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 05:03:31.735 ThaliTest[2573:7921281] multipeer manager: restart client
,2016-04-20 05:03:31.755 ThaliTest[2573:7921281] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 05:03:31.756 ThaliTest[2573:7921281] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 05:03:51.735 ThaliTest[2573:7921281] multipeer manager: restart client
,2016-04-20 05:03:51.756 ThaliTest[2573:7921281] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
,2016-04-20 05:03:51.760 ThaliTest[2573:7921281] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 05:04:11.735 ThaliTest[2573:7921281] multipeer manager: restart client
,2016-04-20 05:04:11.755 ThaliTest[2573:7921281] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
,2016-04-20 05:04:11.756 ThaliTest[2573:7921281] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 05:04:31.735 ThaliTest[2573:7921281] multipeer manager: restart client
,2016-04-20 05:04:31.758 ThaliTest[2573:7921281] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 05:04:31.759 ThaliTest[2573:7921281] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 05:04:51.735 ThaliTest[2573:7921281] multipeer manager: restart client
,2016-04-20 05:04:51.758 ThaliTest[2573:7921281] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 05:04:51.759 ThaliTest[2573:7921281] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 05:05:11.735 ThaliTest[2573:7921281] multipeer manager: restart client
,2016-04-20 05:05:11.758 ThaliTest[2573:7921281] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 05:05:11.760 ThaliTest[2573:7921281] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 05:05:31.735 ThaliTest[2573:7921281] multipeer manager: restart client
,2016-04-20 05:05:31.755 ThaliTest[2573:7921281] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 05:05:31.757 ThaliTest[2573:7921281] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 05:05:51.735 ThaliTest[2573:7921281] multipeer manager: restart client
,2016-04-20 05:05:51.756 ThaliTest[2573:7921281] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 05:05:51.758 ThaliTest[2573:7921281] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 05:06:11.735 ThaliTest[2573:7921281] multipeer manager: restart client
,2016-04-20 05:06:11.757 ThaliTest[2573:7921281] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
,2016-04-20 05:06:11.759 ThaliTest[2573:7921281] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 05:06:31.735 ThaliTest[2573:7921281] multipeer manager: restart client
,2016-04-20 05:06:31.754 ThaliTest[2573:7921281] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
2016-04-20 05:06:31.754 ThaliTest[2573:7921281] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
,2016-04-20 05:06:51.735 ThaliTest[2573:7921281] multipeer manager: restart client
,2016-04-20 05:06:51.753 ThaliTest[2573:7921281] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
,2016-04-20 05:06:51.756 ThaliTest[2573:7921281] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 05:07:11.735 ThaliTest[2573:7921281] multipeer manager: restart client
,2016-04-20 05:07:11.758 ThaliTest[2573:7921281] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 05:07:11.759 ThaliTest[2573:7921281] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 05:07:31.735 ThaliTest[2573:7921281] multipeer manager: restart client
,2016-04-20 05:07:31.758 ThaliTest[2573:7921281] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 05:07:31.759 ThaliTest[2573:7921281] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 05:07:51.735 ThaliTest[2573:7921281] multipeer manager: restart client
,2016-04-20 05:07:51.759 ThaliTest[2573:7921281] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 05:07:51.760 ThaliTest[2573:7921281] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 05:08:11.734 ThaliTest[2573:7921281] multipeer manager: restart client
,2016-04-20 05:08:11.754 ThaliTest[2573:7921281] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 05:08:11.755 ThaliTest[2573:7921281] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 05:08:31.735 ThaliTest[2573:7921281] multipeer manager: restart client
,2016-04-20 05:08:31.764 ThaliTest[2573:7921281] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 05:08:31.764 ThaliTest[2573:7921281] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 05:08:51.735 ThaliTest[2573:7921281] multipeer manager: restart client
,2016-04-20 05:08:51.757 ThaliTest[2573:7921281] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 05:08:51.758 ThaliTest[2573:7921281] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3

```
