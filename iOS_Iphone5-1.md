#### Test 68102130f73255a_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/68102130f73255a/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/0217088A-33AD-42C9-976F-0D5B4C365150/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/0217088A-33AD-42C9-976F-0D5B4C365150/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/68102130f73255a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/68102130f73255a/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/6BDD7C80-F537-46A5-B2ED-111385EE4EA8/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55211"
,(lldb)     command script import "/tmp/0217088A-33AD-42C9-976F-0D5B4C365150/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-04-29 10:09:10.658 ThaliTest[2835:9425999] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/BD0A4C13-E19F-418F-B97D-A4D75AE4EBF9/Library/Cookies/Cookies.binarycookies
,2016-04-29 10:09:11.202 ThaliTest[2835:9425999] Apache Cordova native platform version 4.1.1 is starting.
,2016-04-29 10:09:11.204 ThaliTest[2835:9425999] Multi-tasking -> Device: YES, App: YES
,2016-04-29 10:09:11.227 ThaliTest[2835:9425999] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-04-29 10:09:13.524 ThaliTest[2835:9425999] Using UIWebView
,2016-04-29 10:09:13.529 ThaliTest[2835:9425999] [CDVTimer][handleopenurl] 0.474036ms
,2016-04-29 10:09:13.534 ThaliTest[2835:9425999] [CDVTimer][intentandnavigationfilter] 5.281031ms
2016-04-29 10:09:13.535 ThaliTest[2835:9425999] [CDVTimer][gesturehandler] 0.258982ms
2016-04-29 10:09:13.535 ThaliTest[2835:9425999] [CDVTimer][TotalPluginS,tartup] 7.050991ms
,2016-04-29 10:09:21.490 ThaliTest[2835:9425999] Resetting plugins due to page load.
,2016-04-29 10:09:24.743 ThaliTest[2835:9425999] Finished load of: file:///var/mobile/Containers/Bundle/Application/6BDD7C80-F537-46A5-B2ED-111385EE4EA8/ThaliTest.app/www/index.html
,2016-04-29 10:09:24.948 ThaliTest[2835:9425999] JXcore Cordova plugin initializing
,2016-04-29 10:09:24.950 ThaliTest[2835:9426201] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-04-29 10:09:41.714 ThaliTest[2835:9426201] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-04-29 10:09:41.715 ThaliTest[2835:9426201] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-04-29 10:09:41.716 ThaliTest[2835:9426201] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-04-29 10:09:41.720 ThaliTest[2835:9426201] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5-1
,WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6BDD7C80-F537-46A5-B2ED-111385EE4EA8/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6BDD7C80-F537-46A5-B2ED-111385EE4EA8/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6BDD7C80-F537-46A5-B2ED-111385EE4EA8/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6BDD7C80-F537-46A5-B2ED-111385EE4EA8/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6BDD7C80-F537-46A5-B2ED-111385EE4EA8/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6BDD7C80-F537-46A5-B2ED-111385EE4EA8/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6BDD7C80-F537-46A5-B2ED-111385EE4EA8/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6BDD7C80-F537-46A5-B2ED-111385EE4EA8/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6BDD7C80-F537-46A5-B2ED-111385EE4EA8/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6BDD7C80-F537-46A5-B2ED-111385EE4EA8/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6BDD7C80-F537-46A5-B2ED-111385EE4EA8/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6BDD7C80-F537-46A5-B2ED-111385EE4EA8/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6BDD7C80-F537-46A5-B2ED-111385EE4EA8/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6BDD7C80-F537-46A5-B2ED-111385EE4EA8/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6BDD7C80-F537-46A5-B2ED-111385EE4EA8/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6BDD7C80-F537-46A5-B2ED-111385EE4EA8/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6BDD7C80-F537-46A5-B2ED-111385EE4EA8/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6BDD7C80-F537-46A5-B2ED-111385EE4EA8/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6BDD7C80-F537-46A5-B2ED-111385EE4EA8/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6BDD7C80-F537-46A5-B2ED-111385EE4EA8/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6BDD7C80-F537-46A5-B2ED-111385EE4EA8/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6BDD7C80-F537-46A5-B2ED-111385EE4EA8/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-04-29 10:09:55.398 ThaliTest[2835:9425999] THREAD WARNING: ['JXcore'] took '12971.993896' ms. Plugin should use a background thread.
,2016-04-29 10:09:55.400 ThaliTest[2835:9426152] void SendDelegateMessage(NSInvocation *): delegate (webView:decidePolicyForNavigationAction:request:frame:decisionListener:) failed to return after waiting 10 seconds. main run loop mode: kCFRunLoopDefaultMode
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 61620
,ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 61622
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
,DEBUG createNativeListener: listening 61625
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
,DEBUG createNativeListener: listening 61629
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
,DEBUG createNativeListener: listening 61634
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
,DEBUG createNativeListener: listening 61638
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
,DEBUG createNativeListener: listening 61642
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
,DEBUG createNativeListener: listening 61646
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
ok 27 The mux stream should be closed
,DEBUG createNativeListener: incoming socket close
,# teardown
,# setup
,# 9. native server - we can get a ton of connections and data through and still clean up the server completely
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 61650
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
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
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
,DEBUG createNativeListener: listening 61702
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
,DEBUG createNativeListener: listening 61706
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
,[{"uuid":"831652d1-f5dc-4370-9bb4-e736119d075f","data":"custom data"},{"uuid":"b7ccdf89-53fb-4b69-acec-42a4f66f335f","data":"custom data"},{"uuid":"b7cd0fef-ad33-49c5-8781-858c9a5e3542","data":"custom data"},{"uuid":"f94a4309-984a-4df8-a677-f820db7183f0",",data":"custom data"}]
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
ok 87 error should be null
,# setup
,# 24. #startUpdateAdvertisingAndListening should fail if start not called
,ok 88 specific error should be returned
,# teardown
,ok 89 error should be null
,ok 90 error should be null
,# setup
,# 25. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 61716
,2016-04-29 10:12:44.027 ThaliTest[2835:9426201] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-29 10:12:44.028 ThaliTest[2835:9426201] jxcore: stopListeningForAdvertisements: success
,ok 91 error should be null
,ok 92 error should be null
,2016-04-29 10:12:44.033 ThaliTest[2835:9426201] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-29 10:12:44.034 ThaliTest[2835:9426201] jxcore: stopListeningForAdvertisements: success
,ok 93 error should be null
,ok 94 error should be null
,# teardown
,2016-04-29 10:12:44.275 ThaliTest[2835:9426201] jxcore: stopAdvertisingAndListening
2016-04-29 10:12:44.276 ThaliTest[2835:9426201] THEMultipeerManager stopping peer
2016-04-29 10:12:44.276 ThaliTest[2835:9426201] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-29 10:12:44.276 ThaliTest[2835:9426201] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-29 10:12:44.278 ThaliTest[2835:9426201] jxcore: stopListeningForAdvertisements: success
,ok 95 error should be null
,ok 96 error should be null
,# setup
,# 26. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 61718
,2016-04-29 10:12:44.620 ThaliTest[2835:9426201] jxcore: startListeningForAdvertisements
,2016-04-29 10:12:44.622 ThaliTest[2835:9426201] multipeer manager: start client restart timer: 0x175f3050
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-29 10:12:44.624 ThaliTest[2835:9426201] jxcore: startListeningForAdvertisements: success
,ok 97 error should be null
,ok 98 error should be null
,2016-04-29 10:12:44.673 ThaliTest[2835:9426201] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-29 10:12:44.675 ThaliTest[2835:9426201] jxcore: startListeningForAdvertisements: success
,ok 99 error should be null
,ok 100 error should be null
,# teardown
,2016-04-29 10:12:44.890 ThaliTest[2835:9426201] jxcore: stopAdvertisingAndListening
2016-04-29 10:12:44.891 ThaliTest[2835:9426201] THEMultipeerManager stopping peer
2016-04-29 10:12:44.891 ThaliTest[2835:9426201] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-29 10:12:44.891 ThaliTest[2835:9426201] jxcore: stopListeningForAdvertisements
2016-04-29 10:12:44.891 ThaliTest[2835:9426201] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-29 10:12:44.893 ThaliTest[2835:9426201] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 101 error should be null
,ok 102 error should be null
,# setup
,# 27. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 61720
,2016-04-29 10:12:45.449 ThaliTest[2835:9426201] jxcore: startUpdateAdvertisingAndListening
2016-04-29 10:12:45.450 ThaliTest[2835:9426201] server: starting 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:1
2016-04-29 10:12:45.451 ThaliTest[2835:9426201] multipeer m,anager: start client restart timer: 0x175f3050
2016-04-29 10:12:45.451 ThaliTest[2835:9426201] THEMultipeerManager initialized peer 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:1
2016-04-29 10:12:45.452 ThaliTest[2835:9426201] jxcore: startUpdateAdvertisingAndListening: success
,ok 103 error should be null
ok 104 error should be null
,2016-04-29 10:12:45.469 ThaliTest[2835:9426201] jxcore: startUpdateAdvertisingAndListening
2016-04-29 10:12:45.470 ThaliTest[2835:9426201] THEMultipeerManager stopping peer
2016-04-29 10:12:45.470 ThaliTest[2835:9426201] multipeer manager: stop client ti,mer
2016-04-29 10:12:45.471 ThaliTest[2835:9426201] server: starting 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:2
2016-04-29 10:12:45.471 ThaliTest[2835:9426201] multipeer manager: start client restart timer: 0x175f3050
,2016-04-29 10:12:45.472 ThaliTest[2835:9426201] THEMultipeerManager initialized peer 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:2
2016-04-29 10:12:45.474 ThaliTest[2835:9426201] jxcore: startUpdateAdvertisingAndListening: success
,ok 105 error should be null
,ok 106 error should be null
,# teardown
,2016-04-29 10:12:47.718 ThaliTest[2835:9426201] jxcore: stopAdvertisingAndListening
2016-04-29 10:12:47.719 ThaliTest[2835:9426201] THEMultipeerManager stopping peer
2016-04-29 10:12:47.719 ThaliTest[2835:9426201] multipeer manager: stop client timer
2016-04-29 10:12:47.719 ThaliTest[2835:9426201] jxcore: stopAdvertisingAndListening: success
2016-04-29 10:12:47.720 ThaliTest[2835:9426201] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-29 10:12:47.722 ThaliTest[2835:9426201] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 107 error should be null
,ok 108 error should be null
,# setup
,# 28. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 61725
,2016-04-29 10:13:03.688 ThaliTest[2835:9426201] jxcore: stopAdvertisingAndListening
2016-04-29 10:13:03.688 ThaliTest[2835:9426201] THEMultipeerManager stopping peer
2016-04-29 10:13:03.688 ThaliTest[2835:9426201] jxcore: stopAdvertisingAndListening: suc,cess
ok 109 error should be null
,ok 110 error should be null
,2016-04-29 10:13:03.692 ThaliTest[2835:9426201] jxcore: stopAdvertisingAndListening
2016-04-29 10:13:03.693 ThaliTest[2835:9426201] THEMultipeerManager stopping peer
2016-04-29 10:13:03.693 ThaliTest[2835:9426201] jxcore: stopAdvertisingAndListening: success
,ok 111 error should be null
,ok 112 error should be null
,# teardown
,2016-04-29 10:13:03.835 ThaliTest[2835:9426201] jxcore: stopAdvertisingAndListening
2016-04-29 10:13:03.835 ThaliTest[2835:9426201] THEMultipeerManager stopping peer
2016-04-29 10:13:03.836 ThaliTest[2835:9426201] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-29 10:13:03.836 ThaliTest[2835:9426201] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-29 10:13:03.837 ThaliTest[2835,:9426201] jxcore: stopListeningForAdvertisements: success
,ok 113 error should be null
,ok 114 error should be null
,# setup
,# 29. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 61727
,ok 115 first call should succeed
,ok 116 first call should succeed
,ok 117 specific error should be returned
,# teardown
,2016-04-29 10:13:04.336 ThaliTest[2835:9426201] jxcore: stopAdvertisingAndListening
2016-04-29 10:13:04.336 ThaliTest[2835:9426201] THEMultipeerManager stopping peer
2016-04-29 10:13:04.336 ThaliTest[2835:9426201] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-29 10:13:04.336 ThaliTest[2835:9426201] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-29 10:13:04.337 ThaliTest[2835,:9426201] jxcore: stopListeningForAdvertisements: success
,ok 118 error should be null
,ok 119 error should be null
,# setup
,# 30. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 61729
,2016-04-29 10:13:04.673 ThaliTest[2835:9426201] jxcore: startListeningForAdvertisements
2016-04-29 10:13:04.674 ThaliTest[2835:9426201] multipeer manager: start client restart timer: 0x175f3050
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-29 10:13:04.675 ThaliTest[2835:9426201] jxcore: startListeningForAdvertisements: success
,2016-04-29 10:13:04.691 ThaliTest[2835:9426201] jxcore: startUpdateAdvertisingAndListening
2016-04-29 10:13:04.692 ThaliTest[2835:9426201] server: starting 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:3
2016-04-29 10:13:04.692 ThaliTest[2835:9426201] THEMultipee,rManager initialized peer 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:3
2016-04-29 10:13:04.692 ThaliTest[2835:9426201] jxcore: startUpdateAdvertisingAndListening: success
,ok 120 called only once
ok 121 discovery state matches
,ok 122 advertising state matches
,# teardown
,2016-04-29 10:13:04.818 ThaliTest[2835:9426201] jxcore: stopAdvertisingAndListening
2016-04-29 10:13:04.818 ThaliTest[2835:9426201] THEMultipeerManager stopping peer
2016-04-29 10:13:04.818 ThaliTest[2835:9426201] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-29 10:13:04.819 ThaliTest[2835:9426201] jxcore: stopListeningForAdvertisements
2016-04-29 10:13:04.819 ThaliTest[2835:9426201] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-04-29 10:13:04.820 ThaliTest[2835:9426201] jxcore: stopListeningForAdvertisements: success
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
,2016-04-29 10:13:28.674 ThaliTest[2835:9426201] jxcore: startListeningForAdvertisements
2016-04-29 10:13:28.675 ThaliTest[2835:9426201] multipeer manager: start client restart timer: 0x175f3050
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-29 10:13:28.677 ThaliTest[2835:9426201] jxcore: startListeningForAdvertisements: success
ok 138 Can call startListeningForAdvertisements without error
2016-04-29 10:13:28.680 ThaliTest[2835:9426201] jxcore: stopListeningForAdvertisements
2016-04-29 10:13:28.680 ThaliTest[2835:9426201] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-29 10:13:28.683 ThaliTest[2835:9426201] jxcore: stopListeningForAdvertisements: success
,ok 139 Can call stopListeningForAdvertisements without error
,# teardown
,2016-04-29 10:13:28.937 ThaliTest[2835:9426201] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-29 10:13:28.938 ThaliTest[2835:9426201] jxcore: stopListeningForAdvertisements: success
,ok 140 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-29 10:13:28.940 ThaliTest[2835:9426201] jxcore: stopAdvertisingAndListening
2016-04-29 10:13:28.940 ThaliTest[2835:9426201] THEMultipeerManager stopping peer
2016-04-29 10:13:28.940 ThaliTest[2835:9426201] jxcore: stopAdvertisingAndListening: success
ok 141 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 35. Calling startListeningForAdvertisements twice is NOT an error
,2016-04-29 10:13:29.465 ThaliTest[2835:9426201] jxcore: startListeningForAdvertisements
2016-04-29 10:13:29.465 ThaliTest[2835:9426201] multipeer manager: start client restart timer: 0x175f3050
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-29 10:13:29.467 ThaliTest[2835:9426201] jxcore: startListeningForAdvertisements: success
ok 142 Can call startListeningForAdvertisements without error
2016-04-29 10:13:29.469 ThaliTest[2835:9426201] jxcore: startListeningForAdvertisements
DEBUG ,thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-29 10:13:29.471 ThaliTest[2835:9426201] jxcore: startListeningForAdvertisements: success
,ok 143 Can call startListeningForAdvertisements twice without error
,# teardown
,2016-04-29 10:13:29.561 ThaliTest[2835:9426201] jxcore: stopListeningForAdvertisements
2016-04-29 10:13:29.562 ThaliTest[2835:9426201] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-29 10:13:29.563 ThaliTest[2835:9426201] jxcore: stopListeningForAdvertisements: success
,ok 144 Should be able to call stopListeningForAdvertisements in teardown
2016-04-29 10:13:29.564 ThaliTest[2835:9426201] jxcore: stopAdvertisingAndListening
2016-04-29 10:13:29.565 ThaliTest[2835:9426201] THEMultipeerManager stopping peer
,2016-04-29 10:13:29.565 ThaliTest[2835:9426201] jxcore: stopAdvertisingAndListening: success
,ok 145 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 36. Calling stopListeningForAdvertisements without calling start is NOT an error
,2016-04-29 10:13:30.184 ThaliTest[2835:9426201] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-29 10:13:30.185 ThaliTest[2835:9426201] jxcore: stopListeningForAdvertisements: success
ok 146 Can call stopListeningForAdvertisements without error
,2016-04-29 10:13:30.187 ThaliTest[2835:9426201] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-29 10:13:30.188 ThaliTest[2835:9426201] jxcore: stopListeningForAdvertisements: success
,ok 147 Can call stopListeningForAdvertisements without error
,# teardown
,2016-04-29 10:13:46.700 ThaliTest[2835:9426201] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-29 10:13:46.701 ThaliTest[2835:9426201] jxcore: stopListeningForAdvertisements: success
,ok 148 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-29 10:13:46.703 ThaliTest[2835:9426201] jxcore: stopAdvertisingAndListening
2016-04-29 10:13:46.703 ThaliTest[2835:9426201] THEMultipeerManager stopping peer
2016-04-29 10:13:46.703 ThaliTest[2835:9426201] jxcore: stopAdvertisingAndListening: success
ok 149 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 37. Can call start/stopUpdateAdvertisingAndListening
,2016-04-29 10:13:47.047 ThaliTest[2835:9426201] jxcore: startUpdateAdvertisingAndListening
2016-04-29 10:13:47.047 ThaliTest[2835:9426201] server: starting 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:4
2016-04-29 10:13:47.048 ThaliTest[2835:9426201] multipeer m,anager: start client restart timer: 0x175f3050
2016-04-29 10:13:47.048 ThaliTest[2835:9426201] THEMultipeerManager initialized peer 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:4
2016-04-29 10:13:47.048 ThaliTest[2835:9426201] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 150 Can call startUpdateAdvertisingAndListening without error
2016-04-29 10:13:47.049 ThaliTest[2835:9426201] jxcore: stopAdvertisingAndListening
2016-04-29 10:13:47.050 ThaliTest[2835:9426201] THEMultipeerManager stopping peer
2016,-04-29 10:13:47.050 ThaliTest[2835:9426201] multipeer manager: stop client timer
2016-04-29 10:13:47.050 ThaliTest[2835:9426201] jxcore: stopAdvertisingAndListening: success
ok 151 Can call stopAdvertisingAndListening without error
,# teardown
,2016-04-29 10:13:47.358 ThaliTest[2835:9426201] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-29 10:13:47.359 ThaliTest[2835:9426201] jxcore: stopListeningForAdvertisements: success
,ok 152 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-29 10:13:47.361 ThaliTest[2835:9426201] jxcore: stopAdvertisingAndListening
2016-04-29 10:13:47.361 ThaliTest[2835:9426201] THEMultipeerManager stopping peer
2016-04-29 10:13:47.362 ThaliTest[2835:9426201] jxcore: stopAdvertisingAndListening: success
ok 153 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-04-29 10:13:47.868 ThaliTest[2835:9426201] jxcore: startUpdateAdvertisingAndListening
2016-04-29 10:13:47.868 ThaliTest[2835:9426201] server: starting 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:5
2016-04-29 10:13:47.869 ThaliTest[2835:9426201] multipeer m,anager: start client restart timer: 0x175f3050
2016-04-29 10:13:47.869 ThaliTest[2835:9426201] THEMultipeerManager initialized peer 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:5
2016-04-29 10:13:47.869 ThaliTest[2835:9426201] jxcore: startUpdateAdvertisingAndListening: success
ok 154 Can call startUpdateAdvertisingAndListening without error
,2016-04-29 10:13:47.871 ThaliTest[2835:9426201] jxcore: startUpdateAdvertisingAndListening
2016-04-29 10:13:47.871 ThaliTest[2835:9426201] THEMultipeerManager stopping peer
2016-04-29 10:13:47.871 ThaliTest[2835:9426201] multipeer manager: stop client ti,mer
2016-04-29 10:13:47.872 ThaliTest[2835:9426201] server: starting 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:6
,2016-04-29 10:13:47.872 ThaliTest[2835:9426201] multipeer manager: start client restart timer: 0x175f3050
2016-04-29 10:13:47.873 ThaliTest[2835:9426201] THEMultipeerManager initialized peer 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:6
2016-04-29 10:13:47.873 ,ThaliTest[2835:9426201] jxcore: startUpdateAdvertisingAndListening: success
ok 155 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,2016-04-29 10:13:48.013 ThaliTest[2835:9426201] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-29 10:13:48.014 ThaliTest[2835:9426201] jxcore: stopListeningForAdvertisements: success
,ok 156 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-29 10:13:48.016 ThaliTest[2835:9426201] jxcore: stopAdvertisingAndListening
2016-04-29 10:13:48.016 ThaliTest[2835:9426201] THEMultipeerManager stopping peer
2016-04-29 10:13:48.016 ThaliTest[2835:9426201] multipeer manager: stop client timer
20,16-04-29 10:13:48.017 ThaliTest[2835:9426201] jxcore: stopAdvertisingAndListening: success
ok 157 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,2016-04-29 10:14:01.439 ThaliTest[2835:9426201] jxcore: stopAdvertisingAndListening
2016-04-29 10:14:01.440 ThaliTest[2835:9426201] THEMultipeerManager stopping peer
2016-04-29 10:14:01.440 ThaliTest[2835:9426201] jxcore: stopAdvertisingAndListening: success
ok 158 Can call startUpdateAdvertisingAndListening without error
,2016-04-29 10:14:01.441 ThaliTest[2835:9426201] jxcore: stopAdvertisingAndListening
2016-04-29 10:14:01.441 ThaliTest[2835:9426201] THEMultipeerManager stopping peer
2016-04-29 10:14:01.442 ThaliTest[2835:9426201] jxcore: stopAdvertisingAndListening: success
,ok 159 Can call stopAdvertisingAndListening without error
,# teardown
,2016-04-29 10:14:05.623 ThaliTest[2835:9426201] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-29 10:14:05.624 ThaliTest[2835:9426201] jxcore: stopListeningForAdvertisements: success
,ok 160 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-29 10:14:05.626 ThaliTest[2835:9426201] jxcore: stopAdvertisingAndListening
2016-04-29 10:14:05.626 ThaliTest[2835:9426201] THEMultipeerManager stopping peer
2016-04-29 10:14:05.626 ThaliTest[2835:9426201] jxcore: stopAdvertisingAndListening: success
ok 161 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 40. cannot call connect when start listening for advertisements is not active
,2016-04-29 10:14:08.509 ThaliTest[2835:9426201] jxcore: connect foo
2016-04-29 10:14:08.509 ThaliTest[2835:9426201] jxcore: connect: fail: Start browsing first
,not ok 162 got right error
,  ---
,    operator: equal
,    expected: 'startListeningForAdvertisements is not active'
,    actual:   'Start browsing first'
,  ...
,# teardown
,2016-04-29 10:14:08.591 ThaliTest[2835:9426201] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-29 10:14:08.592 ThaliTest[2835:9426201] jxcore: stopListeningForAdvertisements: success
,ok 163 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-29 10:14:08.594 ThaliTest[2835:9426201] jxcore: stopAdvertisingAndListening
2016-04-29 10:14:08.594 ThaliTest[2835:9426201] THEMultipeerManager stopping peer
2016-04-29 10:14:08.594 ThaliTest[2835:9426201] jxcore: stopAdvertisingAndListening: suc,cess
ok 164 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 41. peerAvailabilityChange is called
,2016-04-29 10:14:08.932 ThaliTest[2835:9426201] jxcore: startUpdateAdvertisingAndListening
2016-04-29 10:14:08.932 ThaliTest[2835:9426201] server: starting 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:7
2016-04-29 10:14:08.932 ThaliTest[2835:9426201] multipeer manager: start client restart timer: 0x175f3050
2016-04-29 10:14:08.933 ThaliTest[2835:9426201] THEMultipeerManager initialized peer 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:7
2016-04-29 10:14:08.933 ThaliTest[2835:9426201] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 165 Can call startUpdateAdvertisingAndListeningwithout error
2016-04-29 10:14:08.934 ThaliTest[2835:9426201] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-04-29 10:14:08.935 ThaliTest[2835:9426201] jxcore: startListeningForAdvertisements: success
,ok 166 Can call startListeningForAdvertisements without error
,2016-04-29 10:14:10.934 ThaliTest[2835:9425999] client: found new peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:7
2016-04-29 10:14:10.935 ThaliTest[2835:9425999] client: found new peer: DB1392E4-24A2-460A-8746-25C82246EF25:7
2016-04-29 10:14:10.936 ThaliTes,t[2835:9425999] client: found new peer: EF331042-C426-4B67-BF95-35460DC67D54:7
,ok 167 peers must be an array
ok 168 peers must not be zero-length
ok 169 peer must have peerIdentifier
ok 170 peerIdentifier must be a string
,ok 171 peer must have peerAvailable
ok 172 peer must have pleaseConnect
,# teardown
,2016-04-29 10:14:13.175 ThaliTest[2835:9425999] client: lost peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
2016-04-29 10:14:13.176 ThaliTest[2835:9425999] client session: onPeerLost: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
,2016-04-29 10:14:13.725 ThaliTest[2835:9425999] client: lost peer: DB1392E4-24A2-460A-8746-25C82246EF25
2016-04-29 10:14:13.725 ThaliTest[2835:9425999] client session: onPeerLost: DB1392E4-24A2-460A-8746-25C82246EF25
,2016-04-29 10:14:15.295 ThaliTest[2835:9425999] client: lost peer: EF331042-C426-4B67-BF95-35460DC67D54
2016-04-29 10:14:15.295 ThaliTest[2835:9425999] client session: onPeerLost: EF331042-C426-4B67-BF95-35460DC67D54
,2016-04-29 10:14:16.686 ThaliTest[2835:9426201] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-29 10:14:16.687 ThaliTest[2835:9426201] jxcore: stopListeningForAdvertisements: success
,ok 173 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-29 10:14:16.688 ThaliTest[2835:9426201] jxcore: stopAdvertisingAndListening
,2016-04-29 10:14:16.689 ThaliTest[2835:9426201] THEMultipeerManager stopping peer
,2016-04-29 10:14:16.689 ThaliTest[2835:9426201] multipeer manager: stop client timer
2016-04-29 10:14:16.690 ThaliTest[2835:9426201] jxcore: stopAdvertisingAndListening: success
ok 174 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 42. Can connect to a remote peer
,2016-04-29 10:14:42.905 ThaliTest[2835:9426201] jxcore: startUpdateAdvertisingAndListening
,2016-04-29 10:14:42.906 ThaliTest[2835:9426201] server: starting 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:8
2016-04-29 10:14:42.906 ThaliTest[2835:9426201] multipeer manager: start client restart timer: 0x175f3050
2016-04-29 10:14:42.907 ThaliTest[2835:94262,01] THEMultipeerManager initialized peer 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:8
2016-04-29 10:14:42.907 ThaliTest[2835:9426201] jxcore: startUpdateAdvertisingAndListening: success
ok 175 Can call startUpdateAdvertisingAndListening without error
,2016-04-29 10:14:42.909 ThaliTest[2835:9426201] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-04-29 10:14:42.911 ThaliTest[2835:9426201] jxcore: startListeningForAdvertisements: success
ok 176 Can call startListeningForAdvertisements without error
,2016-04-29 10:14:42.930 ThaliTest[2835:9425999] client: found new peer: EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:14:42.932 ThaliTest[2835:9425999] client: found new peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
INFO testThaliMobileNative: Rece,ived peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"EF331042-C426-4B67-BF95-35460DC67D54:8","pleaseConnect":0}]
2016-04-29 10:14:42.934 ThaliTest[2835:9426201] jxcore: connect EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 1,0:14:42.934 ThaliTest[2835:9426201] client: server will connect
2016-04-29 10:14:42.935 ThaliTest[2835:9426201] client session: reverseConnect
2016-04-29 10:14:42.935 ThaliTest[2835:9426201] client session: stateChange:0->1 EF331042-C426-4B67-BF95-35460DC67D54:8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8","pleaseConnect":0}]
,2016-04-29 10:14:43.078 ThaliTest[2835:9425999] client: found new peer: DB1392E4-24A2-460A-8746-25C82246EF25:8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"DB1392E4-24A2-460A-8746-25C82246EF25:8","pleaseConnect":0}]
,2016-04-29 10:14:43.181 ThaliTest[2835:9426896] client session: not connected EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:14:43.181 ThaliTest[2835:9426896] client session: onLinkFailure: EF331042-C426-4B67-BF95-35460DC67D54
2016-04-29 10:14:43.1,81 ThaliTest[2835:9426896] client session: disconnect
2016-04-29 10:14:43.181 ThaliTest[2835:9426896] client session: stateChange:1->0 EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:14:43.182 ThaliTest[2835:9426896] client session: no connect callb,ack (server initiated)
,2016-04-29 10:14:52.936 ThaliTest[2835:9425999] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-04-29 10:14:55.953 ThaliTest[2835:9426201] jxcore: connect EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:14:55.953 ThaliTest[2835:9426201] client: server will connect
2016-04-29 10:14:55.954 ThaliTest[2835:9426201] client session: reverseConnect
2016-04-29 10:14:55.954 ThaliTest[2835:9426201] client session: stateChange:0->1 EF331042-C426-4B67-BF95-35460DC67D54:8
,2016-04-29 10:14:56.189 ThaliTest[2835:9428267] client session: not connected EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:14:56.189 ThaliTest[2835:9428267] client session: onLinkFailure: EF331042-C426-4B67-BF95-35460DC67D54
2016-04-29 10:14:56.1,89 ThaliTest[2835:9428267] client session: disconnect
,2016-04-29 10:14:56.190 ThaliTest[2835:9428267] client session: stateChange:1->0 EF331042-C426-4B67-BF95-35460DC67D54:8
,2016-04-29 10:14:56.193 ThaliTest[2835:9428267] client session: no connect callback (server initiated)
,2016-04-29 10:15:02.908 ThaliTest[2835:9425999] multipeer manager: restart client
,2016-04-29 10:15:02.924 ThaliTest[2835:9425999] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:8
,2016-04-29 10:15:02.938 ThaliTest[2835:9425999] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
,2016-04-29 10:15:02.941 ThaliTest[2835:9425999] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:8
,2016-04-29 10:15:05.955 ThaliTest[2835:9425999] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-04-29 10:15:08.967 ThaliTest[2835:9426201] jxcore: connect EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:15:08.967 ThaliTest[2835:9426201] client: server will connect
2016-04-29 10:15:08.968 ThaliTest[2835:9426201] client session: reverseConnect
2016-04-29 10:15:08.968 ThaliTest[2835:9426201] client session: stateChange:0->1 EF331042-C426-4B67-BF95-35460DC67D54:8
,2016-04-29 10:15:09.369 ThaliTest[2835:9428316] client session: not connected EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:15:09.369 ThaliTest[2835:9428316] client session: onLinkFailure: EF331042-C426-4B67-BF95-35460DC67D54
2016-04-29 10:15:09.369 ThaliTest[2835:9428316] client session: disconnect
,2016-04-29 10:15:09.369 ThaliTest[2835:9428316] client session: stateChange:1->0 EF331042-C426-4B67-BF95-35460DC67D54:8
,2016-04-29 10:15:09.372 ThaliTest[2835:9428316] client session: no connect callback (server initiated)
,2016-04-29 10:15:18.968 ThaliTest[2835:9425999] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-04-29 10:15:21.976 ThaliTest[2835:9426201] jxcore: connect EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:15:21.976 ThaliTest[2835:9426201] client: server will connect
2016-04-29 10:15:21.977 ThaliTest[2835:9426201] client session: reverseConnect
2016-04-29 10:15:21.977 ThaliTest[2835:9426201] client session: stateChange:0->1 EF331042-C426-4B67-BF95-35460DC67D54:8
,2016-04-29 10:15:22.442 ThaliTest[2835:9428316] client session: not connected EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:15:22.442 ThaliTest[2835:9428316] client session: onLinkFailure: EF331042-C426-4B67-BF95-35460DC67D54
2016-04-29 10:15:22.4,42 ThaliTest[2835:9428316] client session: disconnect
2016-04-29 10:15:22.442 ThaliTest[2835:9428316] client session: stateChange:1->0 EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:15:22.443 ThaliTest[2835:9428316] client session: no connect callback (server initiated)
,2016-04-29 10:15:22.908 ThaliTest[2835:9425999] multipeer manager: restart client
,2016-04-29 10:15:22.938 ThaliTest[2835:9425999] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:15:22.938 ThaliTest[2835:9425999] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
,2016-04-29 10:15:22.944 ThaliTest[2835:9425999] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:8
,2016-04-29 10:15:24.407 ThaliTest[2835:9425999] client: lost peer: DB1392E4-24A2-460A-8746-25C82246EF25
2016-04-29 10:15:24.408 ThaliTest[2835:9425999] client session: onPeerLost: DB1392E4-24A2-460A-8746-25C82246EF25
,2016-04-29 10:15:24.513 ThaliTest[2835:9425999] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"DB1392E4-24A2-460A-8746-25C82246EF25:8","pleaseConnect":0}]
,2016-04-29 10:15:31.978 ThaliTest[2835:9425999] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-04-29 10:15:34.985 ThaliTest[2835:9426201] jxcore: connect EF331042-C426-4B67-BF95-35460DC67D54:8
,2016-04-29 10:15:34.985 ThaliTest[2835:9426201] client: server will connect
2016-04-29 10:15:34.986 ThaliTest[2835:9426201] client session: reverseConnect
,2016-04-29 10:15:34.986 ThaliTest[2835:9426201] client session: stateChange:0->1 EF331042-C426-4B67-BF95-35460DC67D54:8
,2016-04-29 10:15:35.614 ThaliTest[2835:9428422] client session: not connected EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:15:35.614 ThaliTest[2835:9428422] client session: onLinkFailure: EF331042-C426-4B67-BF95-35460DC67D54
2016-04-29 10:15:35.6,14 ThaliTest[2835:9428422] client session: disconnect
2016-04-29 10:15:35.615 ThaliTest[2835:9428422] client session: stateChange:1->0 EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:15:35.615 ThaliTest[2835:9428422] client session: no connect callback (server initiated)
,2016-04-29 10:15:42.908 ThaliTest[2835:9425999] multipeer manager: restart client
,2016-04-29 10:15:44.988 ThaliTest[2835:9425999] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-04-29 10:15:47.999 ThaliTest[2835:9426201] jxcore: connect EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:15:47.999 ThaliTest[2835:9426201] client: server will connect
2016-04-29 10:15:48.000 ThaliTest[2835:9426201] client session: reverseConn,ect
2016-04-29 10:15:48.000 ThaliTest[2835:9426201] client session: stateChange:0->1 EF331042-C426-4B67-BF95-35460DC67D54:8
,2016-04-29 10:15:48.012 ThaliTest[2835:9425999] client: lost peer: EF331042-C426-4B67-BF95-35460DC67D54
2016-04-29 10:15:48.012 ThaliTest[2835:9425999] client session: onPeerLost: EF331042-C426-4B67-BF95-35460DC67D54
2016-04-29 10:15:48.012 ThaliTest[283,5:9425999] client session: onLinkFailure: EF331042-C426-4B67-BF95-35460DC67D54
2016-04-29 10:15:48.012 ThaliTest[2835:9425999] client session: disconnect
2016-04-29 10:15:48.013 ThaliTest[2835:9425999] client session: stateChange:1->0 EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:15:48.013 ThaliTest[2835:9425999] client session: no connect callback (server initiated)
,2016-04-29 10:15:58.000 ThaliTest[2835:9425999] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-04-29 10:16:01.013 ThaliTest[2835:9426201] jxcore: connect EF331042-C426-4B67-BF95-35460DC67D54:8
,2016-04-29 10:16:01.013 ThaliTest[2835:9426201] client: connect: unreachable EF331042-C426-4B67-BF95-35460DC67D54
2016-04-29 10:16:01.014 ThaliTest[2835:9426201] jxcore: connect: fail: Peer unreachable
INFO testThaliMobileNative: Connect returned an error: Peer unreachable
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-04-29 10:16:02.908 ThaliTest[2835:9425999] multipeer manager: restart client
,2016-04-29 10:16:02.928 ThaliTest[2835:9425999] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:8
2016-04-29 10:16:02.928 ThaliTest[2835:9425999] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:16:02.92,9 ThaliTest[2835:9425999] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"EF331042-C426-4B67-BF95-35460DC67D54:8","pleaseCon,nect":0}]
,2016-04-29 10:16:04.025 ThaliTest[2835:9426201] jxcore: connect EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:16:04.026 ThaliTest[2835:9426201] client: server will connect
2016-04-29 10:16:04.026 ThaliTest[2835:9426201] client session: reverseConnect
2016-04-29 10:16:04.026 ThaliTest[2835:9426201] client session: stateChange:0->1 EF331042-C426-4B67-BF95-35460DC67D54:8
,2016-04-29 10:16:04.330 ThaliTest[2835:9428471] client session: not connected EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:16:04.330 ThaliTest[2835:9428471] client session: onLinkFailure: EF331042-C426-4B67-BF95-35460DC67D54
2016-04-29 10:16:04.331 ThaliTest[2835:9428471] client session: disconnect
2016-04-29 10:16:04.331 ThaliTest[2835:9428471] client session: stateChange:1->0 EF331042-C426-4B67-BF95-35460DC67D54:8
,2016-04-29 10:16:04.332 ThaliTest[2835:9428471] client session: no connect callback (server initiated)
,2016-04-29 10:16:14.028 ThaliTest[2835:9425999] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-04-29 10:16:17.037 ThaliTest[2835:9426201] jxcore: connect EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:16:17.038 ThaliTest[2835:9426201] client: server will connect
2016-04-29 10:16:17.038 ThaliTest[2835:9426201] client session: reverseConnect
2016-04-29 10:16:17.039 ThaliTest[2835:9426201] client session: stateChange:0->1 EF331042-C426-4B67-BF95-35460DC67D54:8
,2016-04-29 10:16:17.553 ThaliTest[2835:9428518] client session: not connected EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:16:17.553 ThaliTest[2835:9428518] client session: onLinkFailure: EF331042-C426-4B67-BF95-35460DC67D54
2016-04-29 10:16:17.5,54 ThaliTest[2835:9428518] client session: disconnect
2016-04-29 10:16:17.555 ThaliTest[2835:9428518] client session: stateChange:1->0 EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:16:17.555 ThaliTest[2835:9428518] client session: no connect callback (server initiated)
,2016-04-29 10:16:22.908 ThaliTest[2835:9425999] multipeer manager: restart client
,2016-04-29 10:16:22.927 ThaliTest[2835:9425999] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:8
2016-04-29 10:16:22.927 ThaliTest[2835:9425999] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:16:22.928 ThaliTest[2835:9425999] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:8
,2016-04-29 10:16:27.040 ThaliTest[2835:9425999] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-04-29 10:16:30.050 ThaliTest[2835:9426201] jxcore: connect EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:16:30.051 ThaliTest[2835:9426201] client: server will connect
2016-04-29 10:16:30.052 ThaliTest[2835:9426201] client session: reverseConn,ect
2016-04-29 10:16:30.052 ThaliTest[2835:9426201] client session: stateChange:0->1 EF331042-C426-4B67-BF95-35460DC67D54:8
,2016-04-29 10:16:30.201 ThaliTest[2835:9428536] client session: not connected EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:16:30.201 ThaliTest[2835:9428536] client session: onLinkFailure: EF331042-C426-4B67-BF95-35460DC67D54
2016-04-29 10:16:30.2,02 ThaliTest[2835:9428536] client session: disconnect
2016-04-29 10:16:30.202 ThaliTest[2835:9428536] client session: stateChange:1->0 EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:16:30.203 ThaliTest[2835:9428536] client session: no connect callback (server initiated)
,2016-04-29 10:16:40.053 ThaliTest[2835:9425999] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,WARN testThaliMobileNative: Too many connect retries!
,not ok 177 Connect failed!
  ---
,    operator: fail
  ...
,# teardown
,2016-04-29 10:16:40.241 ThaliTest[2835:9426201] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-29 10:16:40.242 ThaliTest[2835:9426201] jxcore: stopListeningForAdvertisements: success
,ok 178 Should be able to call stopListeningForAdvertisements in teardown
2016-04-29 10:16:40.243 ThaliTest[2835:9426201] jxcore: stopAdvertisingAndListening
2016-04-29 10:16:40.244 ThaliTest[2835:9426201] THEMultipeerManager stopping peer
2016-04-29 10:,16:40.244 ThaliTest[2835:9426201] multipeer manager: stop client timer
2016-04-29 10:16:40.244 ThaliTest[2835:9426201] jxcore: stopAdvertisingAndListening: success
ok 179 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 43. Get error when trying to double connect to a peer
,2016-04-29 10:16:42.996 ThaliTest[2835:9426201] jxcore: startUpdateAdvertisingAndListening
,2016-04-29 10:16:42.997 ThaliTest[2835:9426201] server: starting 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:16:42.998 ThaliTest[2835:9426201] multipeer manager: start client restart timer: 0x175f3050
2016-04-29 10:16:42.998 ThaliTest[2835:9426201] THEMultipeerManager initialized peer 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:16:42.998 ,ThaliTest[2835:9426201] jxcore: startUpdateAdvertisingAndListening: success
ok 180 Can call startUpdateAdvertisingAndListening without error
,2016-04-29 10:16:43.000 ThaliTest[2835:9426201] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-04-29 10:16:43.002 ThaliTest[2835:9426201] jxcore: startListeningForAdvertisements: success
ok 181 Can call startListeningForAdvertisements without error
,2016-04-29 10:16:43.024 ThaliTest[2835:9425999] client: found new peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:16:43.028 ThaliTest[2835:9425999] client: found new peer: DB1392E4-24A2-460A-8746-25C82246EF25:8
2016-04-29 10:16:43.028 ThaliTes,t[2835:9425999] client: found new peer: EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:16:43.030 ThaliTest[2835:9426201] jxcore: connect DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:16:43.030 ThaliTest[2835:9426201] client: server will conn,ect
2016-04-29 10:16:43.030 ThaliTest[2835:9426201] client session: reverseConnect
2016-04-29 10:16:43.030 ThaliTest[2835:9426201] client session: stateChange:0->1 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
,2016-04-29 10:16:44.143 ThaliTest[2835:9428536] client session: not connected DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:16:44.145 ThaliTest[2835:9428536] client session: onLinkFailure: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
2016-04-29 10:16:44.1,45 ThaliTest[2835:9428536] client session: disconnect
2016-04-29 10:16:44.145 ThaliTest[2835:9428536] client session: stateChange:1->0 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:16:44.145 ThaliTest[2835:9428536] client session: no connect callb,ack (server initiated)
,2016-04-29 10:16:53.031 ThaliTest[2835:9425999] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-04-29 10:16:56.039 ThaliTest[2835:9426201] jxcore: connect DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:16:56.040 ThaliTest[2835:9426201] client: server will connect
2016-04-29 10:16:56.040 ThaliTest[2835:9426201] client session: reverseConnect
2016-04-29 10:16:56.041 ThaliTest[2835:9426201] client session: stateChange:0->1 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
,2016-04-29 10:16:56.341 ThaliTest[2835:9428536] client session: not connected DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:16:56.342 ThaliTest[2835:9428536] client session: onLinkFailure: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
2016-04-29 10:16:56.342 ThaliTest[2835:9428536] client session: disconnect
,2016-04-29 10:16:56.342 ThaliTest[2835:9428536] client session: stateChange:1->0 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:16:56.344 ThaliTest[2835:9428536] client session: no connect callback (server initiated)
,2016-04-29 10:17:02.999 ThaliTest[2835:9425999] multipeer manager: restart client
,2016-04-29 10:17:03.014 ThaliTest[2835:9425999] client: found updated peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:17:03.017 ThaliTest[2835:9425999] client: found updated peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:17:03.018 ThaliTest[2835:9425999] client: found updated peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
,2016-04-29 10:17:06.041 ThaliTest[2835:9425999] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-04-29 10:17:09.048 ThaliTest[2835:9426201] jxcore: connect DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:17:09.049 ThaliTest[2835:9426201] client: server will connect
2016-04-29 10:17:09.049 ThaliTest[2835:9426201] client session: reverseConnect
2016-04-29 10:17:09.050 ThaliTest[2835:9426201] client session: stateChange:0->1 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:17:09.326 ThaliTest[2835:9428597] client session: not connected DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:17:09.328 ThaliTest[2835:9428597] client session: onLinkFailure: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
2016-04-29 10:17:09.3,28 ThaliTest[2835:9428597] client session: disconnect
2016-04-29 10:17:09.329 ThaliTest[2835:9428597] client session: stateChange:1->0 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:17:09.329 ThaliTest[2835:9428597] client session: no connect callback (server initiated)
,2016-04-29 10:17:19.051 ThaliTest[2835:9425999] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-04-29 10:17:22.064 ThaliTest[2835:9426201] jxcore: connect DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:17:22.064 ThaliTest[2835:9426201] client: server will connect
2016-04-29 10:17:22.066 ThaliTest[2835:9426201] client session: reverseConnect
2016-04-29 10:17:22.066 ThaliTest[2835:9426201] client session: stateChange:0->1 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:17:22.681 ThaliTest[2835:9428685] client session: not connected DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:17:22.681 ThaliTest[2835:9428685] client session: onLinkFailure: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
2016-04-29 10:17:22.6,81 ThaliTest[2835:9428685] client session: disconnect
2016-04-29 10:17:22.681 ThaliTest[2835:9428685] client session: stateChange:1->0 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:17:22.682 ThaliTest[2835:9428685] client session: no connect callb,ack (server initiated)
,2016-04-29 10:17:22.999 ThaliTest[2835:9425999] multipeer manager: restart client
,2016-04-29 10:17:23.019 ThaliTest[2835:9425999] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:17:23.020 ThaliTest[2835:9425999] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:17:23.02,0 ThaliTest[2835:9425999] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:17:32.067 ThaliTest[2835:9425999] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-04-29 10:17:35.081 ThaliTest[2835:9426201] jxcore: connect DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:17:35.081 ThaliTest[2835:9426201] client: server will connect
2016-04-29 10:17:35.082 ThaliTest[2835:9426201] client session: reverseConn,ect
2016-04-29 10:17:35.082 ThaliTest[2835:9426201] client session: stateChange:0->1 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:17:35.593 ThaliTest[2835:9428685] client session: not connected DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:17:35.594 ThaliTest[2835:9428685] client session: onLinkFailure: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
2016-04-29 10:17:35.594 ThaliTest[2835:9428685] client session: disconnect
,2016-04-29 10:17:35.595 ThaliTest[2835:9428685] client session: stateChange:1->0 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:17:35.596 ThaliTest[2835:9428685] client session: no connect callback (server initiated)
,2016-04-29 10:17:42.999 ThaliTest[2835:9425999] multipeer manager: restart client
,2016-04-29 10:17:43.019 ThaliTest[2835:9425999] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:17:43.019 ThaliTest[2835:9425999] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:17:43.02,0 ThaliTest[2835:9425999] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
,2016-04-29 10:17:45.083 ThaliTest[2835:9425999] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-04-29 10:17:48.098 ThaliTest[2835:9426201] jxcore: connect DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
,2016-04-29 10:17:48.098 ThaliTest[2835:9426201] client: server will connect
2016-04-29 10:17:48.099 ThaliTest[2835:9426201] client session: reverseConnect
2016-04-29 10:17:48.099 ThaliTest[2835:9426201] client session: stateChange:0->1 DB4A2C0F-6E10-427C,-8BF8-66B1948D1539:9
,2016-04-29 10:17:48.784 ThaliTest[2835:9428766] client session: not connected DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:17:48.785 ThaliTest[2835:9428766] client session: onLinkFailure: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
,2016-04-29 10:17:48.785 ThaliTest[2835:9428766] client session: disconnect
,2016-04-29 10:17:48.786 ThaliTest[2835:9428766] client session: stateChange:1->0 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:17:48.787 ThaliTest[2835:9428766] client session: no connect callback (server initiated)
,2016-04-29 10:17:58.100 ThaliTest[2835:9425999] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-04-29 10:18:01.109 ThaliTest[2835:9426201] jxcore: connect DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:18:01.110 ThaliTest[2835:9426201] client: server will connect
2016-04-29 10:18:01.110 ThaliTest[2835:9426201] client session: reverseConnect
2016-04-29 10:18:01.110 ThaliTest[2835:9426201] client session: stateChange:0->1 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:18:01.599 ThaliTest[2835:9428801] client session: not connected DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:18:01.599 ThaliTest[2835:9428801] client session: onLinkFailure: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
2016-04-29 10:18:01.5,99 ThaliTest[2835:9428801] client session: disconnect
2016-04-29 10:18:01.599 ThaliTest[2835:9428801] client session: stateChange:1->0 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:18:01.599 ThaliTest[2835:9428801] client session: no connect callback (server initiated)
,2016-04-29 10:18:02.999 ThaliTest[2835:9425999] multipeer manager: restart client
,2016-04-29 10:18:03.017 ThaliTest[2835:9425999] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:18:03.018 ThaliTest[2835:9425999] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:18:03.018 ThaliTest[2835:9425999] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:18:11.111 ThaliTest[2835:9425999] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-04-29 10:18:14.121 ThaliTest[2835:9426201] jxcore: connect DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:18:14.121 ThaliTest[2835:9426201] client: server will connect
2016-04-29 10:18:14.122 ThaliTest[2835:9426201] client session: reverseConnect
2016-04-29 10:18:14.123 ThaliTest[2835:9426201] client session: stateChange:0->1 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:18:14.318 ThaliTest[2835:9428889] client session: not connected DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:18:14.320 ThaliTest[2835:9428889] client session: onLinkFailure: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
2016-04-29 10:18:14.3,21 ThaliTest[2835:9428889] client session: disconnect
2016-04-29 10:18:14.321 ThaliTest[2835:9428889] client session: stateChange:1->0 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:18:14.321 ThaliTest[2835:9428889] client session: no connect callback (server initiated)
,2016-04-29 10:18:22.999 ThaliTest[2835:9425999] multipeer manager: restart client
,2016-04-29 10:18:24.122 ThaliTest[2835:9425999] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-04-29 10:18:27.133 ThaliTest[2835:9426201] jxcore: connect DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:18:27.134 ThaliTest[2835:9426201] client: server will connect
2016-04-29 10:18:27.134 ThaliTest[2835:9426201] client session: reverseConn,ect
2016-04-29 10:18:27.134 ThaliTest[2835:9426201] client session: stateChange:0->1 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:18:27.143 ThaliTest[2835:9425999] client: lost peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
2016-04-29 10:18:27.143 ThaliTest[2835:9425999] client session: onPeerLost: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
2016-04-29 10:18:27.143 ThaliTest[283,5:9425999] client session: onLinkFailure: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
2016-04-29 10:18:27.143 ThaliTest[2835:9425999] client session: disconnect
2016-04-29 10:18:27.143 ThaliTest[2835:9425999] client session: stateChange:1->0 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:18:27.144 ThaliTest[2835:9425999] client session: no connect callback (server initiated)
,2016-04-29 10:18:37.135 ThaliTest[2835:9425999] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-04-29 10:18:40.141 ThaliTest[2835:9426201] jxcore: connect DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:18:40.141 ThaliTest[2835:9426201] client: connect: unreachable DB4A2C0F-6E10-427C-8BF8-66B1948D1539
2016-04-29 10:18:40.142 ThaliTest[283,5:9426201] jxcore: connect: fail: Peer unreachable
INFO testThaliMobileNative: Connect returned an error: Peer unreachable
WARN testThaliMobileNative: Too many connect retries!
,2016-04-29 10:18:42.999 ThaliTest[2835:9425999] multipeer manager: restart client
,2016-04-29 10:18:43.020 ThaliTest[2835:9425999] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:18:43.020 ThaliTest[2835:9425999] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:18:43.02,1 ThaliTest[2835:9425999] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:18:43.021 ThaliTest[2835:9426201] jxcore: connect DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:18:43.022 ThaliTest[2835:9426201] client: s,erver will connect
2016-04-29 10:18:43.022 ThaliTest[2835:9426201] client session: reverseConnect
2016-04-29 10:18:43.022 ThaliTest[2835:9426201] client session: stateChange:0->1 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:18:43.214 ThaliTest[2835:9429005] client session: not connected DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:18:43.214 ThaliTest[2835:9429005] client session: onLinkFailure: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
2016-04-29 10:18:43.2,14 ThaliTest[2835:9429005] client session: disconnect
2016-04-29 10:18:43.214 ThaliTest[2835:9429005] client session: stateChange:1->0 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:18:43.215 ThaliTest[2835:9429005] client session: no connect callback (server initiated)
,2016-04-29 10:18:43.330 ThaliTest[2835:9425999] multipeer session: reset timer
2016-04-29 10:18:43.331 ThaliTest[2835:9425999] server session: connect
2016-04-29 10:18:43.331 ThaliTest[2835:9425999] server session: stateChange:0->1 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:18:43.336 ThaliTest[2835:9425999] server: accepting invitation DB4A2C0F-6E10-427C-8BF8-66B1948D1539
,2016-04-29 10:18:45.097 ThaliTest[2835:9429007] server session: p2p link connected
,2016-04-29 10:18:45.328 ThaliTest[2835:9425999] server relay: connected (to port: 61746)
,2016-04-29 10:18:45.328 ThaliTest[2835:9425999] server session: stateChange:1->2 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:18:45.329 ThaliTest[2835:9425999] jxcore: connect: success
,2016-04-29 10:19:02.999 ThaliTest[2835:9425999] multipeer manager: restart client
,2016-04-29 10:19:03.017 ThaliTest[2835:9425999] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
,2016-04-29 10:19:03.020 ThaliTest[2835:9425999] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:19:03.020 ThaliTest[2835:9425999] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:19:22.999 ThaliTest[2835:9425999] multipeer manager: restart client
,2016-04-29 10:19:23.019 ThaliTest[2835:9425999] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
,2016-04-29 10:19:23.020 ThaliTest[2835:9425999] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:19:23.021 ThaliTest[2835:9425999] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
,2016-04-29 10:19:42.999 ThaliTest[2835:9425999] multipeer manager: restart client
,2016-04-29 10:19:43.019 ThaliTest[2835:9425999] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:19:43.019 ThaliTest[2835:9425999] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:19:43.02,0 ThaliTest[2835:9425999] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
,2016-04-29 10:20:02.999 ThaliTest[2835:9425999] multipeer manager: restart client
,2016-04-29 10:20:03.022 ThaliTest[2835:9425999] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:20:03.022 ThaliTest[2835:9425999] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:20:03.023 ThaliTest[2835:9425999] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:20:22.999 ThaliTest[2835:9425999] multipeer manager: restart client
,2016-04-29 10:20:42.999 ThaliTest[2835:9425999] multipeer manager: restart client
,2016-04-29 10:20:43.016 ThaliTest[2835:9425999] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:20:43.017 ThaliTest[2835:9425999] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:20:43.017 ThaliTest[2835:9425999] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
,2016-04-29 10:21:02.999 ThaliTest[2835:9425999] multipeer manager: restart client
,2016-04-29 10:21:03.012 ThaliTest[2835:9425999] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:21:03.012 ThaliTest[2835:9425999] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:21:03.01,3 ThaliTest[2835:9425999] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
,2016-04-29 10:21:22.999 ThaliTest[2835:9425999] multipeer manager: restart client
,2016-04-29 10:21:23.017 ThaliTest[2835:9425999] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
,2016-04-29 10:21:23.021 ThaliTest[2835:9425999] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:21:23.024 ThaliTest[2835:9425999] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:21:42.999 ThaliTest[2835:9425999] multipeer manager: restart client
,2016-04-29 10:21:43.016 ThaliTest[2835:9425999] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
,2016-04-29 10:21:43.019 ThaliTest[2835:9425999] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:21:43.019 ThaliTest[2835:9425999] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
,2016-04-29 10:22:02.999 ThaliTest[2835:9425999] multipeer manager: restart client
,2016-04-29 10:22:03.020 ThaliTest[2835:9425999] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:22:03.020 ThaliTest[2835:9425999] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:22:03.021 ThaliTest[2835:9425999] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
,2016-04-29 10:22:22.998 ThaliTest[2835:9425999] multipeer manager: restart client
,2016-04-29 10:22:23.019 ThaliTest[2835:9425999] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:22:23.020 ThaliTest[2835:9425999] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:22:23.02,0 ThaliTest[2835:9425999] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
,2016-04-29 10:22:43.000 ThaliTest[2835:9425999] multipeer manager: restart client
,2016-04-29 10:22:43.016 ThaliTest[2835:9425999] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:22:43.016 ThaliTest[2835:9425999] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:22:43.01,6 ThaliTest[2835:9425999] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
,2016-04-29 10:23:02.998 ThaliTest[2835:9425999] multipeer manager: restart client
,2016-04-29 10:23:03.012 ThaliTest[2835:9425999] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
,2016-04-29 10:23:03.018 ThaliTest[2835:9425999] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:23:03.019 ThaliTest[2835:9425999] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
,2016-04-29 10:23:22.999 ThaliTest[2835:9425999] multipeer manager: restart client
,2016-04-29 10:23:23.021 ThaliTest[2835:9425999] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:23:23.021 ThaliTest[2835:9425999] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:23:23.022 ThaliTest[2835:9425999] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
,2016-04-29 10:23:42.998 ThaliTest[2835:9425999] multipeer manager: restart client
,2016-04-29 10:23:43.019 ThaliTest[2835:9425999] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:23:43.020 ThaliTest[2835:9425999] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:23:43.020 ThaliTest[2835:9425999] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
,2016-04-29 10:24:02.999 ThaliTest[2835:9425999] multipeer manager: restart client
,2016-04-29 10:24:03.020 ThaliTest[2835:9425999] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
,2016-04-29 10:24:03.022 ThaliTest[2835:9425999] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:24:03.023 ThaliTest[2835:9425999] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
,2016-04-29 10:24:22.999 ThaliTest[2835:9425999] multipeer manager: restart client
,2016-04-29 10:24:23.022 ThaliTest[2835:9425999] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:24:23.023 ThaliTest[2835:9425999] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:24:23.023 ThaliTest[2835:9425999] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
,2016-04-29 10:24:42.999 ThaliTest[2835:9425999] multipeer manager: restart client
,2016-04-29 10:24:43.020 ThaliTest[2835:9425999] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:24:43.020 ThaliTest[2835:9425999] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:24:43.021 ThaliTest[2835:9425999] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:25:02.998 ThaliTest[2835:9425999] multipeer manager: restart client
,2016-04-29 10:25:03.018 ThaliTest[2835:9425999] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
,2016-04-29 10:25:03.020 ThaliTest[2835:9425999] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:25:03.021 ThaliTest[2835:9425999] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:25:22.998 ThaliTest[2835:9425999] multipeer manager: restart client
,2016-04-29 10:25:23.018 ThaliTest[2835:9425999] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:25:23.018 ThaliTest[2835:9425999] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:25:23.01,9 ThaliTest[2835:9425999] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:25:42.999 ThaliTest[2835:9425999] multipeer manager: restart client
,2016-04-29 10:25:43.020 ThaliTest[2835:9425999] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:25:43.020 ThaliTest[2835:9425999] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:25:43.021 ThaliTest[2835:9425999] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:26:02.999 ThaliTest[2835:9425999] multipeer manager: restart client
,2016-04-29 10:26:03.017 ThaliTest[2835:9425999] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:26:03.018 ThaliTest[2835:9425999] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:26:03.023 ThaliTest[2835:9425999] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
,2016-04-29 10:26:22.999 ThaliTest[2835:9425999] multipeer manager: restart client
,2016-04-29 10:26:23.021 ThaliTest[2835:9425999] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:26:23.021 ThaliTest[2835:9425999] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:26:23.022 ThaliTest[2835:9425999] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
,2016-04-29 10:26:42.999 ThaliTest[2835:9425999] multipeer manager: restart client
,2016-04-29 10:26:43.022 ThaliTest[2835:9425999] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:26:43.023 ThaliTest[2835:9425999] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:26:43.023 ThaliTest[2835:9425999] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:27:02.999 ThaliTest[2835:9425999] multipeer manager: restart client
,2016-04-29 10:27:03.019 ThaliTest[2835:9425999] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:27:03.019 ThaliTest[2835:9425999] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:27:03.020 ThaliTest[2835:9425999] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:27:22.999 ThaliTest[2835:9425999] multipeer manager: restart client
,2016-04-29 10:27:23.021 ThaliTest[2835:9425999] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:27:23.021 ThaliTest[2835:9425999] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:27:23.022 ThaliTest[2835:9425999] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
,2016-04-29 10:27:42.999 ThaliTest[2835:9425999] multipeer manager: restart client
,2016-04-29 10:27:43.018 ThaliTest[2835:9425999] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:27:43.019 ThaliTest[2835:9425999] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:27:43.01,9 ThaliTest[2835:9425999] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
,2016-04-29 10:28:02.999 ThaliTest[2835:9425999] multipeer manager: restart client
,2016-04-29 10:28:03.020 ThaliTest[2835:9425999] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:28:03.020 ThaliTest[2835:9425999] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:28:03.021 ThaliTest[2835:9425999] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
,2016-04-29 10:28:22.999 ThaliTest[2835:9425999] multipeer manager: restart client
,2016-04-29 10:28:23.020 ThaliTest[2835:9425999] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
,2016-04-29 10:28:23.021 ThaliTest[2835:9425999] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:28:23.022 ThaliTest[2835:9425999] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
,2016-04-29 10:28:42.999 ThaliTest[2835:9425999] multipeer manager: restart client
,2016-04-29 10:28:43.021 ThaliTest[2835:9425999] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:28:43.021 ThaliTest[2835:9425999] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:28:43.02,1 ThaliTest[2835:9425999] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:29:02.999 ThaliTest[2835:9425999] multipeer manager: restart client
,2016-04-29 10:29:22.998 ThaliTest[2835:9425999] multipeer manager: restart client
,2016-04-29 10:29:23.019 ThaliTest[2835:9425999] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:29:23.019 ThaliTest[2835:9425999] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:29:23.019 ThaliTest[2835:9425999] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:29:42.999 ThaliTest[2835:9425999] multipeer manager: restart client
,2016-04-29 10:29:43.019 ThaliTest[2835:9425999] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:29:43.019 ThaliTest[2835:9425999] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
,2016-04-29 10:29:43.020 ThaliTest[2835:9425999] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:30:02.999 ThaliTest[2835:9425999] multipeer manager: restart client
,2016-04-29 10:30:03.019 ThaliTest[2835:9425999] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:30:03.019 ThaliTest[2835:9425999] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:30:03.02,0 ThaliTest[2835:9425999] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
,2016-04-29 10:30:22.999 ThaliTest[2835:9425999] multipeer manager: restart client
,2016-04-29 10:30:23.019 ThaliTest[2835:9425999] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:30:23.020 ThaliTest[2835:9425999] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
,2016-04-29 10:30:23.023 ThaliTest[2835:9425999] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
,2016-04-29 10:30:42.999 ThaliTest[2835:9425999] multipeer manager: restart client
,2016-04-29 10:30:43.022 ThaliTest[2835:9425999] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:30:43.022 ThaliTest[2835:9425999] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:30:43.02,3 ThaliTest[2835:9425999] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
,2016-04-29 10:31:02.999 ThaliTest[2835:9425999] multipeer manager: restart client
,2016-04-29 10:31:03.017 ThaliTest[2835:9425999] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:31:03.021 ThaliTest[2835:9425999] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:31:03.021 ThaliTest[2835:9425999] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
,2016-04-29 10:31:22.999 ThaliTest[2835:9425999] multipeer manager: restart client
,2016-04-29 10:31:23.022 ThaliTest[2835:9425999] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:31:23.022 ThaliTest[2835:9425999] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:31:23.023 ThaliTest[2835:9425999] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9

```
