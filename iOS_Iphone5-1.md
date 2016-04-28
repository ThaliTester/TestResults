#### Test 681021307227906_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/681021307227906/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/FF1C7267-2C35-4A44-AAFF-0A83C675C9E4/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/FF1C7267-2C35-4A44-AAFF-0A83C675C9E4/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/681021307227906/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/681021307227906/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/C77FC756-CA28-4B63-90E6-C48AC7220670/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55107"
,(lldb)     command script import "/tmp/FF1C7267-2C35-4A44-AAFF-0A83C675C9E4/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-04-28 21:24:34.120 ThaliTest[2813:9338054] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/98F8487A-4B5C-482D-91B0-82603EE5CD23/Library/Cookies/Cookies.binarycookies
,2016-04-28 21:24:34.232 ThaliTest[2813:9338054] Apache Cordova native platform version 4.1.1 is starting.
,2016-04-28 21:24:34.233 ThaliTest[2813:9338054] Multi-tasking -> Device: YES, App: YES
,2016-04-28 21:24:34.251 ThaliTest[2813:9338054] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-04-28 21:24:36.544 ThaliTest[2813:9338054] Using UIWebView
,2016-04-28 21:24:36.549 ThaliTest[2813:9338054] [CDVTimer][handleopenurl] 0.449002ms
,2016-04-28 21:24:36.555 ThaliTest[2813:9338054] [CDVTimer][intentandnavigationfilter] 5.164027ms
2016-04-28 21:24:36.555 ThaliTest[2813:9338054] [CDVTimer][gesturehandler] 0.258982ms
2016-04-28 21:24:36.556 ThaliTest[2813:9338054] [CDVTimer][TotalPluginS,tartup] 6.888032ms
,2016-04-28 21:24:45.095 ThaliTest[2813:9338054] Resetting plugins due to page load.
,2016-04-28 21:24:48.778 ThaliTest[2813:9338054] Finished load of: file:///var/mobile/Containers/Bundle/Application/C77FC756-CA28-4B63-90E6-C48AC7220670/ThaliTest.app/www/index.html
,2016-04-28 21:24:49.004 ThaliTest[2813:9338054] JXcore Cordova plugin initializing
,2016-04-28 21:24:49.006 ThaliTest[2813:9338251] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-04-28 21:25:05.685 ThaliTest[2813:9338251] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-04-28 21:25:05.685 ThaliTest[2813:9338251] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-04-28 21:25:05.687 ThaliTest[2813:9338251] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-04-28 21:25:05.690 ThaliTest[2813:9338251] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5-1
,WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C77FC756-CA28-4B63-90E6-C48AC7220670/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C77FC756-CA28-4B63-90E6-C48AC7220670/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C77FC756-CA28-4B63-90E6-C48AC7220670/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C77FC756-CA28-4B63-90E6-C48AC7220670/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C77FC756-CA28-4B63-90E6-C48AC7220670/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C77FC756-CA28-4B63-90E6-C48AC7220670/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C77FC756-CA28-4B63-90E6-C48AC7220670/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C77FC756-CA28-4B63-90E6-C48AC7220670/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C77FC756-CA28-4B63-90E6-C48AC7220670/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C77FC756-CA28-4B63-90E6-C48AC7220670/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C77FC756-CA28-4B63-90E6-C48AC7220670/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C77FC756-CA28-4B63-90E6-C48AC7220670/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C77FC756-CA28-4B63-90E6-C48AC7220670/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C77FC756-CA28-4B63-90E6-C48AC7220670/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C77FC756-CA28-4B63-90E6-C48AC7220670/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C77FC756-CA28-4B63-90E6-C48AC7220670/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C77FC756-CA28-4B63-90E6-C48AC7220670/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C77FC756-CA28-4B63-90E6-C48AC7220670/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C77FC756-CA28-4B63-90E6-C48AC7220670/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C77FC756-CA28-4B63-90E6-C48AC7220670/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C77FC756-CA28-4B63-90E6-C48AC7220670/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C77FC756-CA28-4B63-90E6-C48AC7220670/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-04-28 21:25:19.264 ThaliTest[2813:9338054] THREAD WARNING: ['JXcore'] took '12889.711182' ms. Plugin should use a background thread.
,2016-04-28 21:25:19.266 ThaliTest[2813:9338190] void SendDelegateMessage(NSInvocation *): delegate (webView:decidePolicyForNavigationAction:request:frame:decisionListener:) failed to return after waiting 10 seconds. main run loop mode: kCFRunLoopDefaultMode
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 61401
,ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 61403
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
,DEBUG createNativeListener: listening 61406
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
,DEBUG createNativeListener: listening 61410
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
,DEBUG createNativeListener: listening 61415
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
,DEBUG createNativeListener: listening 61419
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
,DEBUG createNativeListener: listening 61423
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
,DEBUG createNativeListener: listening 61427
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
,DEBUG createNativeListener: listening 61431
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
,DEBUG createNativeListener: listening 61483
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
,DEBUG createNativeListener: listening 61487
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
,[{"uuid":"12b0fe5c-5358-4bd1-a579-798f1c8d590d","data":"custom data"},{"uuid":"199e0e2c-9092-4104-af67-e71ad2ae16f8","data":"custom data"},{"uuid":"749167e2-4f0b-4861-8dc7-f1c6b8b47666","data":"custom data"},{"uuid":"76d70763-019d-486c-be48-b3480c768092",",data":"custom data"}]
ok 76 test participant has uuid
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
,DEBUG createNativeListener: listening 61497
,2016-04-28 21:27:54.255 ThaliTest[2813:9338251] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-28 21:27:54.257 ThaliTest[2813:9338251] jxcore: stopListeningForAdvertisements: success
,ok 91 error should be null
,ok 92 error should be null
,2016-04-28 21:27:54.261 ThaliTest[2813:9338251] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-28 21:27:54.263 ThaliTest[2813:9338251] jxcore: stopListeningForAdvertisements: success
,ok 93 error should be null
,ok 94 error should be null
,# teardown
,2016-04-28 21:27:54.367 ThaliTest[2813:9338251] jxcore: stopAdvertisingAndListening
2016-04-28 21:27:54.368 ThaliTest[2813:9338251] THEMultipeerManager stopping peer
2016-04-28 21:27:54.368 ThaliTest[2813:9338251] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-28 21:27:54.368 ThaliTest[2813:9338251] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-28 21:27:54.370 ThaliTest[2813:9338251] jxcore: stopListeningForAdvertisements: success
,ok 95 error should be null
,ok 96 error should be null
,# setup
,# 26. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 61499
,2016-04-28 21:27:54.597 ThaliTest[2813:9338251] jxcore: startListeningForAdvertisements
,2016-04-28 21:27:54.599 ThaliTest[2813:9338251] multipeer manager: start client restart timer: 0x146f4a60
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-28 21:27:54.601 ThaliTest[2813:9338251] jxcore: startListeningForAdvertisements: success
,ok 97 error should be null
,ok 98 error should be null
,2016-04-28 21:27:54.651 ThaliTest[2813:9338251] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-28 21:27:54.652 ThaliTest[2813:9338251] jxcore: startListeningForAdvertisements: success
,ok 99 error should be null
,ok 100 error should be null
,# teardown
,2016-04-28 21:27:54.868 ThaliTest[2813:9338251] jxcore: stopAdvertisingAndListening
2016-04-28 21:27:54.869 ThaliTest[2813:9338251] THEMultipeerManager stopping peer
2016-04-28 21:27:54.869 ThaliTest[2813:9338251] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-28 21:27:54.869 ThaliTest[2813:9338251] jxcore: stopListeningForAdvertisements
2016-04-28 21:27:54.869 ThaliTest[2813:9338251] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-04-28 21:27:54.871 ThaliTest[2813:9338251] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 101 error should be null
,ok 102 error should be null
,# setup
,# 27. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 61501
,2016-04-28 21:27:55.402 ThaliTest[2813:9338251] jxcore: startUpdateAdvertisingAndListening
2016-04-28 21:27:55.403 ThaliTest[2813:9338251] server: starting 337492EA-97B4-404F-B8FE-E0E7631E59C8:1
2016-04-28 21:27:55.404 ThaliTest[2813:9338251] multipeer m,anager: start client restart timer: 0x146f4a60
2016-04-28 21:27:55.404 ThaliTest[2813:9338251] THEMultipeerManager initialized peer 337492EA-97B4-404F-B8FE-E0E7631E59C8:1
2016-04-28 21:27:55.404 ThaliTest[2813:9338251] jxcore: startUpdateAdvertisingAndListening: success
,ok 103 error should be null
ok 104 error should be null
,2016-04-28 21:27:55.422 ThaliTest[2813:9338251] jxcore: startUpdateAdvertisingAndListening
2016-04-28 21:27:55.422 ThaliTest[2813:9338251] THEMultipeerManager stopping peer
2016-04-28 21:27:55.423 ThaliTest[2813:9338251] multipeer manager: stop client ti,mer
2016-04-28 21:27:55.423 ThaliTest[2813:9338251] server: starting 337492EA-97B4-404F-B8FE-E0E7631E59C8:2
2016-04-28 21:27:55.424 ThaliTest[2813:9338251] multipeer manager: start client restart timer: 0x146f4a60
,2016-04-28 21:27:55.427 ThaliTest[2813:9338251] THEMultipeerManager initialized peer 337492EA-97B4-404F-B8FE-E0E7631E59C8:2
2016-04-28 21:27:55.427 ThaliTest[2813:9338251] jxcore: startUpdateAdvertisingAndListening: success
,ok 105 error should be null
,ok 106 error should be null
,# teardown
,2016-04-28 21:27:55.628 ThaliTest[2813:9338251] jxcore: stopAdvertisingAndListening
2016-04-28 21:27:55.629 ThaliTest[2813:9338251] THEMultipeerManager stopping peer
2016-04-28 21:27:55.629 ThaliTest[2813:9338251] multipeer manager: stop client timer
20,16-04-28 21:27:55.629 ThaliTest[2813:9338251] jxcore: stopAdvertisingAndListening: success
2016-04-28 21:27:55.629 ThaliTest[2813:9338251] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-04-28 21:27:55.630 ThaliTest[2813:9338251] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 107 error should be null
,ok 108 error should be null
,# setup
,# 28. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 61506
,2016-04-28 21:27:56.685 ThaliTest[2813:9338251] jxcore: stopAdvertisingAndListening
2016-04-28 21:27:56.686 ThaliTest[2813:9338251] THEMultipeerManager stopping peer
2016-04-28 21:27:56.686 ThaliTest[2813:9338251] jxcore: stopAdvertisingAndListening: success
,ok 109 error should be null
,ok 110 error should be null
,2016-04-28 21:27:56.690 ThaliTest[2813:9338251] jxcore: stopAdvertisingAndListening
2016-04-28 21:27:56.690 ThaliTest[2813:9338251] THEMultipeerManager stopping peer
2016-04-28 21:27:56.690 ThaliTest[2813:9338251] jxcore: stopAdvertisingAndListening: success
,ok 111 error should be null
,ok 112 error should be null
,# teardown
,2016-04-28 21:27:57.494 ThaliTest[2813:9338251] jxcore: stopAdvertisingAndListening
2016-04-28 21:27:57.494 ThaliTest[2813:9338251] THEMultipeerManager stopping peer
2016-04-28 21:27:57.494 ThaliTest[2813:9338251] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-28 21:27:57.495 ThaliTest[2813:9338251] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-28 21:27:57.496 ThaliTest[2813,:9338251] jxcore: stopListeningForAdvertisements: success
,ok 113 error should be null
,ok 114 error should be null
,# setup
,# 29. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 61508
,ok 115 first call should succeed
,ok 116 first call should succeed
,ok 117 specific error should be returned
,# teardown
,2016-04-28 21:28:02.644 ThaliTest[2813:9338251] jxcore: stopAdvertisingAndListening
2016-04-28 21:28:02.644 ThaliTest[2813:9338251] THEMultipeerManager stopping peer
2016-04-28 21:28:02.644 ThaliTest[2813:9338251] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-28 21:28:02.644 ThaliTest[2813:9338251] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-28 21:28:02.647 ThaliTest[2813:9338251] jxcore: stopListeningForAdvertisements: success
,ok 118 error should be null
,ok 119 error should be null
,# setup
,# 30. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 61510
,2016-04-28 21:28:02.848 ThaliTest[2813:9338251] jxcore: startListeningForAdvertisements
,2016-04-28 21:28:02.849 ThaliTest[2813:9338251] multipeer manager: start client restart timer: 0x146f4a60
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-28 21:28:02.864 ThaliTest[2813:9338251] jxcore: startListeningForAdvertisements: success
,2016-04-28 21:28:02.904 ThaliTest[2813:9338251] jxcore: startUpdateAdvertisingAndListening
2016-04-28 21:28:02.905 ThaliTest[2813:9338251] server: starting 337492EA-97B4-404F-B8FE-E0E7631E59C8:3
2016-04-28 21:28:02.905 ThaliTest[2813:9338251] THEMultipeerManager initialized peer 337492EA-97B4-404F-B8FE-E0E7631E59C8:3
2016-04-28 21:28:02.905 ThaliTest[2813:9338251] jxcore: startUpdateAdvertisingAndListening: success
,ok 120 called only once
ok 121 discovery state matches
ok 122 advertising state matches
,# teardown
,2016-04-28 21:28:03.120 ThaliTest[2813:9338251] jxcore: stopAdvertisingAndListening
2016-04-28 21:28:03.120 ThaliTest[2813:9338251] THEMultipeerManager stopping peer
2016-04-28 21:28:03.120 ThaliTest[2813:9338251] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-28 21:28:03.121 ThaliTest[2813:9338251] jxcore: stopListeningForAdvertisements
2016-04-28 21:28:03.121 ThaliTest[2813:9338251] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-04-28 21:28:03.122 ThaliTest[2813:9338251] jxcore: stopListeningForAdvertisements: success
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
,2016-04-28 21:28:11.037 ThaliTest[2813:9338251] jxcore: startListeningForAdvertisements
2016-04-28 21:28:11.037 ThaliTest[2813:9338251] multipeer manager: start client restart timer: 0x146f4a60
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-28 21:28:11.038 ThaliTest[2813:9338251] jxcore: startListeningForAdvertisements: success
,ok 138 Can call startListeningForAdvertisements without error
,2016-04-28 21:28:11.040 ThaliTest[2813:9338251] jxcore: stopListeningForAdvertisements
,2016-04-28 21:28:11.040 ThaliTest[2813:9338251] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-28 21:28:11.042 ThaliTest[2813:9338251] jxcore: stopListeningForAdvertisements: success
,ok 139 Can call stopListeningForAdvertisements without error
,# teardown
,2016-04-28 21:28:11.352 ThaliTest[2813:9338251] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-28 21:28:11.353 ThaliTest[2813:9338251] jxcore: stopListeningForAdvertisements: success
,ok 140 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-28 21:28:11.355 ThaliTest[2813:9338251] jxcore: stopAdvertisingAndListening
2016-04-28 21:28:11.355 ThaliTest[2813:9338251] THEMultipeerManager stopping peer
2016-04-28 21:28:11.355 ThaliTest[2813:9338251] jxcore: stopAdvertisingAndListening: success
ok 141 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 35. Calling startListeningForAdvertisements twice is NOT an error
,2016-04-28 21:28:11.927 ThaliTest[2813:9338251] jxcore: startListeningForAdvertisements
2016-04-28 21:28:11.927 ThaliTest[2813:9338251] multipeer manager: start client restart timer: 0x146f4a60
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-28 21:28:11.928 ThaliTest[2813:9338251] jxcore: startListeningForAdvertisements: success
,ok 142 Can call startListeningForAdvertisements without error
,2016-04-28 21:28:11.930 ThaliTest[2813:9338251] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-28 21:28:11.932 ThaliTest[2813:9338251] jxcore: startListeningForAdvertisements: success
ok 143 Can call startListeningForAdvertisements twice without error
,# teardown
,2016-04-28 21:28:20.025 ThaliTest[2813:9338251] jxcore: stopListeningForAdvertisements
2016-04-28 21:28:20.026 ThaliTest[2813:9338251] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisi,ngActive":false,"discoveryActive":false}
,2016-04-28 21:28:20.027 ThaliTest[2813:9338251] jxcore: stopListeningForAdvertisements: success
,ok 144 Should be able to call stopListeningForAdvertisements in teardown
2016-04-28 21:28:20.028 ThaliTest[2813:9338251] jxcore: stopAdvertisingAndListening
2016-04-28 21:28:20.028 ThaliTest[2813:9338251] THEMultipeerManager stopping peer
2016-04-28 21:,28:20.029 ThaliTest[2813:9338251] jxcore: stopAdvertisingAndListening: success
ok 145 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 36. Calling stopListeningForAdvertisements without calling start is NOT an error
,2016-04-28 21:28:28.740 ThaliTest[2813:9338251] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-28 21:28:28.742 ThaliTest[2813:9338251] jxcore: stopListeningForAdvertisements: success
,ok 146 Can call stopListeningForAdvertisements without error
,2016-04-28 21:28:28.744 ThaliTest[2813:9338251] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-28 21:28:28.745 ThaliTest[2813:9338251] jxcore: stopListeningForAdvertisements: success
,ok 147 Can call stopListeningForAdvertisements without error
,# teardown
,2016-04-28 21:28:28.811 ThaliTest[2813:9338251] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-28 21:28:28.812 ThaliTest[2813:9338251] jxcore: stopListeningForAdvertisements: success
,ok 148 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-28 21:28:28.814 ThaliTest[2813:9338251] jxcore: stopAdvertisingAndListening
2016-04-28 21:28:28.814 ThaliTest[2813:9338251] THEMultipeerManager stopping peer
2016-04-28 21:28:28.814 ThaliTest[2813:9338251] jxcore: stopAdvertisingAndListening: suc,cess
ok 149 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 37. Can call start/stopUpdateAdvertisingAndListening
,2016-04-28 21:28:29.111 ThaliTest[2813:9338251] jxcore: startUpdateAdvertisingAndListening
2016-04-28 21:28:29.112 ThaliTest[2813:9338251] server: starting 337492EA-97B4-404F-B8FE-E0E7631E59C8:4
2016-04-28 21:28:29.112 ThaliTest[2813:9338251] multipeer manager: start client restart timer: 0x146f4a60
2016-04-28 21:28:29.113 ThaliTest[2813:9338251] THEMultipeerManager initialized peer 337492EA-97B4-404F-B8FE-E0E7631E59C8:4
2016-04-28 21:28:29.113 ThaliTest[2813:9338251] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 150 Can call startUpdateAdvertisingAndListening without error
2016-04-28 21:28:29.114 ThaliTest[2813:9338251] jxcore: stopAdvertisingAndListening
2016-04-28 21:28:29.114 ThaliTest[2813:9338251] THEMultipeerManager stopping peer
2016,-04-28 21:28:29.114 ThaliTest[2813:9338251] multipeer manager: stop client timer
,2016-04-28 21:28:29.117 ThaliTest[2813:9338251] jxcore: stopAdvertisingAndListening: success
ok 151 Can call stopAdvertisingAndListening without error
,# teardown
,2016-04-28 21:28:29.408 ThaliTest[2813:9338251] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-28 21:28:29.409 ThaliTest[2813:9338251] jxcore: stopListeningForAdvertisements: success
,ok 152 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-28 21:28:29.410 ThaliTest[2813:9338251] jxcore: stopAdvertisingAndListening
,2016-04-28 21:28:29.410 ThaliTest[2813:9338251] THEMultipeerManager stopping peer
,2016-04-28 21:28:29.411 ThaliTest[2813:9338251] jxcore: stopAdvertisingAndListening: success
,ok 153 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-04-28 21:28:33.143 ThaliTest[2813:9338251] jxcore: startUpdateAdvertisingAndListening
2016-04-28 21:28:33.143 ThaliTest[2813:9338251] server: starting 337492EA-97B4-404F-B8FE-E0E7631E59C8:5
2016-04-28 21:28:33.144 ThaliTest[2813:9338251] multipeer m,anager: start client restart timer: 0x146f4a60
2016-04-28 21:28:33.144 ThaliTest[2813:9338251] THEMultipeerManager initialized peer 337492EA-97B4-404F-B8FE-E0E7631E59C8:5
2016-04-28 21:28:33.144 ThaliTest[2813:9338251] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 154 Can call startUpdateAdvertisingAndListening without error
2016-04-28 21:28:33.145 ThaliTest[2813:9338251] jxcore: startUpdateAdvertisingAndListening
2016-04-28 21:28:33.145 ThaliTest[2813:9338251] THEMultipeerManager stopping pee,r
2016-04-28 21:28:33.146 ThaliTest[2813:9338251] multipeer manager: stop client timer
2016-04-28 21:28:33.146 ThaliTest[2813:9338251] server: starting 337492EA-97B4-404F-B8FE-E0E7631E59C8:6
2016-04-28 21:28:33.146 ThaliTest[2813:9338251] multipeer mana,ger: start client restart timer: 0x146f4a60
2016-04-28 21:28:33.148 ThaliTest[2813:9338251] THEMultipeerManager initialized peer 337492EA-97B4-404F-B8FE-E0E7631E59C8:6
2016-04-28 21:28:33.148 ThaliTest[2813:9338251] jxcore: startUpdateAdvertisingAndListe,ning: success
,ok 155 Can call startUpdateAdvertisingAndListening twice without error
# teardown
,2016-04-28 21:28:34.871 ThaliTest[2813:9338054] client: found new peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:6
,2016-04-28 21:28:35.527 ThaliTest[2813:9338054] client: found new peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:6
,2016-04-28 21:28:36.265 ThaliTest[2813:9338251] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-28 21:28:36.266 ThaliTest[2813:9338251] jxcore: stopListeningForAdvertisements: success
,ok 156 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-28 21:28:36.268 ThaliTest[2813:9338251] jxcore: stopAdvertisingAndListening
2016-04-28 21:28:36.269 ThaliTest[2813:9338251] THEMultipeerManager stopping peer
2016-04-28 21:28:36.269 ThaliTest[2813:9338251] multipeer manager: stop client timer
20,16-04-28 21:28:36.269 ThaliTest[2813:9338251] jxcore: stopAdvertisingAndListening: success
ok 157 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,2016-04-28 21:28:38.411 ThaliTest[2813:9338251] jxcore: stopAdvertisingAndListening
2016-04-28 21:28:38.412 ThaliTest[2813:9338251] THEMultipeerManager stopping peer
2016-04-28 21:28:38.412 ThaliTest[2813:9338251] jxcore: stopAdvertisingAndListening: success
ok 158 Can call startUpdateAdvertisingAndListening without error
,2016-04-28 21:28:38.413 ThaliTest[2813:9338251] jxcore: stopAdvertisingAndListening
2016-04-28 21:28:38.413 ThaliTest[2813:9338251] THEMultipeerManager stopping peer
2016-04-28 21:28:38.413 ThaliTest[2813:9338251] jxcore: stopAdvertisingAndListening: success
,ok 159 Can call stopAdvertisingAndListening without error
,# teardown
,2016-04-28 21:28:38.876 ThaliTest[2813:9338251] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-28 21:28:38.878 ThaliTest[2813:9338251] jxcore: stopListeningForAdvertisements: success
,ok 160 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-28 21:28:38.879 ThaliTest[2813:9338251] jxcore: stopAdvertisingAndListening
2016-04-28 21:28:38.879 ThaliTest[2813:9338251] THEMultipeerManager stopping peer
2016-04-28 21:28:38.880 ThaliTest[2813:9338251] jxcore: stopAdvertisingAndListening: success
ok 161 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 40. cannot call connect when start listening for advertisements is not active
,2016-04-28 21:28:56.983 ThaliTest[2813:9338251] jxcore: connect foo
2016-04-28 21:28:56.983 ThaliTest[2813:9338251] jxcore: connect: fail: Start browsing first
,not ok 162 got right error
  ---
,    operator: equal
,    expected: 'startListeningForAdvertisements is not active'
,    actual:   'Start browsing first'
,  ...
,# teardown
,2016-04-28 21:28:57.226 ThaliTest[2813:9338251] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-28 21:28:57.227 ThaliTest[2813:9338251] jxcore: stopListeningForAdvertisements: success
,ok 163 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-28 21:28:57.229 ThaliTest[2813:9338251] jxcore: stopAdvertisingAndListening
2016-04-28 21:28:57.229 ThaliTest[2813:9338251] THEMultipeerManager stopping peer
2016-04-28 21:28:57.230 ThaliTest[2813:9338251] jxcore: stopAdvertisingAndListening: success
ok 164 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 41. peerAvailabilityChange is called
,2016-04-28 21:29:00.353 ThaliTest[2813:9338251] jxcore: startUpdateAdvertisingAndListening
2016-04-28 21:29:00.354 ThaliTest[2813:9338251] server: starting 337492EA-97B4-404F-B8FE-E0E7631E59C8:7
2016-04-28 21:29:00.354 ThaliTest[2813:9338251] multipeer m,anager: start client restart timer: 0x146f4a60
2016-04-28 21:29:00.354 ThaliTest[2813:9338251] THEMultipeerManager initialized peer 337492EA-97B4-404F-B8FE-E0E7631E59C8:7
2016-04-28 21:29:00.354 ThaliTest[2813:9338251] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 165 Can call startUpdateAdvertisingAndListeningwithout error
2016-04-28 21:29:00.356 ThaliTest[2813:9338251] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertising,Active":true,"discoveryActive":true}
,2016-04-28 21:29:00.373 ThaliTest[2813:9338251] jxcore: startListeningForAdvertisements: success
,ok 166 Can call startListeningForAdvertisements without error
,2016-04-28 21:29:01.823 ThaliTest[2813:9338054] client: found new peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7
ok 167 peers must be an array
,ok 168 peers must not be zero-length
ok 169 peer must have peerIdentifier
ok 170 peerIdentifier must be a string
,ok 171 peer must have peerAvailable
,ok 172 peer must have pleaseConnect
,# teardown
,2016-04-28 21:29:01.926 ThaliTest[2813:9338054] client: found new peer: 30403743-C17E-454C-8124-9D59A7B25203:7
,2016-04-28 21:29:02.332 ThaliTest[2813:9338054] client: found new peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:7
,2016-04-28 21:29:03.404 ThaliTest[2813:9338251] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-28 21:29:03.405 ThaliTest[2813:9338251] jxcore: stopListeningForAdvertisements: success
,ok 173 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-28 21:29:03.407 ThaliTest[2813:9338251] jxcore: stopAdvertisingAndListening
2016-04-28 21:29:03.407 ThaliTest[2813:9338251] THEMultipeerManager stopping peer
2016-04-28 21:29:03.407 ThaliTest[2813:9338251] multipeer manager: stop client timer
20,16-04-28 21:29:03.407 ThaliTest[2813:9338251] jxcore: stopAdvertisingAndListening: success
ok 174 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 42. Can connect to a remote peer
,2016-04-28 21:29:05.327 ThaliTest[2813:9338251] jxcore: startUpdateAdvertisingAndListening
2016-04-28 21:29:05.327 ThaliTest[2813:9338251] server: starting 337492EA-97B4-404F-B8FE-E0E7631E59C8:8
2016-04-28 21:29:05.327 ThaliTest[2813:9338251] multipeer manager: start client restart timer: 0x146f4a60
2016-04-28 21:29:05.328 ThaliTest[2813:9338251] THEMultipeerManager initialized peer 337492EA-97B4-404F-B8FE-E0E7631E59C8:8
2016-04-28 21:29:05.328 ThaliTest[2813:9338251] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 175 Can call startUpdateAdvertisingAndListening without error
,2016-04-28 21:29:05.329 ThaliTest[2813:9338251] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
,2016-04-28 21:29:05.331 ThaliTest[2813:9338251] jxcore: startListeningForAdvertisements: success
ok 176 Can call startListeningForAdvertisements without error
,2016-04-28 21:29:05.388 ThaliTest[2813:9338054] client: found new peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"418CC5DB-B63A-41DA-9996-4D5D4125B76C:7","pleaseConnect":0}]
,2016-04-28 21:29:05.391 ThaliTest[2813:9338251] jxcore: connect 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7
2016-04-28 21:29:05.391 ThaliTest[2813:9338251] client: server will connect
2016-04-28 21:29:05.392 ThaliTest[2813:9338251] client session: reverseConnect
2016-04-28 21:29:05.392 ThaliTest[2813:9338251] client session: stateChange:0->1 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7
,2016-04-28 21:29:06.229 ThaliTest[2813:9338769] client session: not connected 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7
2016-04-28 21:29:06.230 ThaliTest[2813:9338769] client session: onLinkFailure: 418CC5DB-B63A-41DA-9996-4D5D4125B76C
2016-04-28 21:29:06.230 ThaliTest[2813:9338769] client session: disconnect
,2016-04-28 21:29:06.230 ThaliTest[2813:9338769] client session: stateChange:1->0 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7
,2016-04-28 21:29:06.234 ThaliTest[2813:9338769] client session: no connect callback (server initiated)
,2016-04-28 21:29:06.288 ThaliTest[2813:9338054] client: found new peer: 30403743-C17E-454C-8124-9D59A7B25203:7
,2016-04-28 21:29:06.292 ThaliTest[2813:9338054] client: found new peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"30403743-C17E-454C-8124-9D59A7B25203:7","pleaseConnect":0}]
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:7","pleaseConnect":0}]
,2016-04-28 21:29:15.393 ThaliTest[2813:9338054] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-04-28 21:29:18.405 ThaliTest[2813:9338251] jxcore: connect 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7
2016-04-28 21:29:18.405 ThaliTest[2813:9338251] client: server will connect
2016-04-28 21:29:18.406 ThaliTest[2813:9338251] client session: reverseConn,ect
2016-04-28 21:29:18.406 ThaliTest[2813:9338251] client session: stateChange:0->1 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7
,2016-04-28 21:29:18.872 ThaliTest[2813:9338836] client session: not connected 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7
2016-04-28 21:29:18.874 ThaliTest[2813:9338836] client session: onLinkFailure: 418CC5DB-B63A-41DA-9996-4D5D4125B76C
2016-04-28 21:29:18.8,74 ThaliTest[2813:9338836] client session: disconnect
2016-04-28 21:29:18.874 ThaliTest[2813:9338836] client session: stateChange:1->0 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7
2016-04-28 21:29:18.875 ThaliTest[2813:9338836] client session: no connect callback (server initiated)
,2016-04-28 21:29:25.329 ThaliTest[2813:9338054] multipeer manager: restart client
,2016-04-28 21:29:25.352 ThaliTest[2813:9338054] client: found updated peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:8
2016-04-28 21:29:25.353 ThaliTest[2813:9338054] client: found updated peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:29:25.353 ,ThaliTest[2813:9338054] client: found updated peer: 30403743-C17E-454C-8124-9D59A7B25203:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"418CC5DB-B63A-41DA-9996-4D5D4125B76C:8","pleaseConnec,t":0}]
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8","pleaseConnect":0}]
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"30403743-C17E-454C-8124-9D59A7B25203:8","pleaseConnect":0}]
,2016-04-28 21:29:28.407 ThaliTest[2813:9338054] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-04-28 21:29:30.080 ThaliTest[2813:9338054] client: lost peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF
2016-04-28 21:29:30.080 ThaliTest[2813:9338054] client session: onPeerLost: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF
,2016-04-28 21:29:31.418 ThaliTest[2813:9338251] jxcore: connect 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7
2016-04-28 21:29:31.418 ThaliTest[2813:9338251] client: server will connect
2016-04-28 21:29:31.419 ThaliTest[2813:9338251] client session: reverseConnect
2016-04-28 21:29:31.419 ThaliTest[2813:9338251] client session: stateChange:0->1 418CC5DB-B63A-41DA-9996-4D5D4125B76C:8
,2016-04-28 21:29:32.235 ThaliTest[2813:9338836] client session: not connected 418CC5DB-B63A-41DA-9996-4D5D4125B76C:8
2016-04-28 21:29:32.235 ThaliTest[2813:9338836] client session: onLinkFailure: 418CC5DB-B63A-41DA-9996-4D5D4125B76C
2016-04-28 21:29:32.2,36 ThaliTest[2813:9338836] client session: disconnect
2016-04-28 21:29:32.236 ThaliTest[2813:9338836] client session: stateChange:1->0 418CC5DB-B63A-41DA-9996-4D5D4125B76C:8
2016-04-28 21:29:32.238 ThaliTest[2813:9338836] client session: no connect callback (server initiated)
,2016-04-28 21:29:41.420 ThaliTest[2813:9338054] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-04-28 21:29:44.428 ThaliTest[2813:9338251] jxcore: connect 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7
2016-04-28 21:29:44.429 ThaliTest[2813:9338251] client: server will connect
2016-04-28 21:29:44.430 ThaliTest[2813:9338251] client session: reverseConnect
2016-04-28 21:29:44.430 ThaliTest[2813:9338251] client session: stateChange:0->1 418CC5DB-B63A-41DA-9996-4D5D4125B76C:8
,2016-04-28 21:29:44.883 ThaliTest[2813:9338890] client session: not connected 418CC5DB-B63A-41DA-9996-4D5D4125B76C:8
2016-04-28 21:29:44.883 ThaliTest[2813:9338890] client session: onLinkFailure: 418CC5DB-B63A-41DA-9996-4D5D4125B76C
2016-04-28 21:29:44.8,83 ThaliTest[2813:9338890] client session: disconnect
2016-04-28 21:29:44.883 ThaliTest[2813:9338890] client session: stateChange:1->0 418CC5DB-B63A-41DA-9996-4D5D4125B76C:8
,2016-04-28 21:29:44.885 ThaliTest[2813:9338890] client session: no connect callback (server initiated)
,2016-04-28 21:29:45.329 ThaliTest[2813:9338054] multipeer manager: restart client
,2016-04-28 21:29:45.353 ThaliTest[2813:9338054] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8","pleaseConnect":0}]
,2016-04-28 21:29:45.359 ThaliTest[2813:9338054] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:8
,2016-04-28 21:29:45.361 ThaliTest[2813:9338054] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:8
,2016-04-28 21:29:54.431 ThaliTest[2813:9338054] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-04-28 21:29:57.441 ThaliTest[2813:9338251] jxcore: connect 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7
2016-04-28 21:29:57.442 ThaliTest[2813:9338251] client: server will connect
2016-04-28 21:29:57.443 ThaliTest[2813:9338251] client session: reverseConnect
2016-04-28 21:29:57.443 ThaliTest[2813:9338251] client session: stateChange:0->1 418CC5DB-B63A-41DA-9996-4D5D4125B76C:8
,2016-04-28 21:29:57.672 ThaliTest[2813:9338842] client session: not connected 418CC5DB-B63A-41DA-9996-4D5D4125B76C:8
2016-04-28 21:29:57.673 ThaliTest[2813:9338842] client session: onLinkFailure: 418CC5DB-B63A-41DA-9996-4D5D4125B76C
2016-04-28 21:29:57.6,73 ThaliTest[2813:9338842] client session: disconnect
2016-04-28 21:29:57.673 ThaliTest[2813:9338842] client session: stateChange:1->0 418CC5DB-B63A-41DA-9996-4D5D4125B76C:8
2016-04-28 21:29:57.674 ThaliTest[2813:9338842] client session: no connect callback (server initiated)
,2016-04-28 21:30:05.328 ThaliTest[2813:9338054] multipeer manager: restart client
,2016-04-28 21:30:05.350 ThaliTest[2813:9338054] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:8
2016-04-28 21:30:05.350 ThaliTest[2813:9338054] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
,2016-04-28 21:30:05.360 ThaliTest[2813:9338054] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:8
,2016-04-28 21:30:06.480 ThaliTest[2813:9338054] client: lost peer: 30403743-C17E-454C-8124-9D59A7B25203
2016-04-28 21:30:06.481 ThaliTest[2813:9338054] client session: onPeerLost: 30403743-C17E-454C-8124-9D59A7B25203
,2016-04-28 21:30:07.444 ThaliTest[2813:9338054] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-04-28 21:30:08.771 ThaliTest[2813:9338054] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"30403743-C17E-454C-8124-9D59,A7B25203:8","pleaseConnect":0}]
,2016-04-28 21:30:10.460 ThaliTest[2813:9338251] jxcore: connect 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7
2016-04-28 21:30:10.461 ThaliTest[2813:9338251] client: server will connect
2016-04-28 21:30:10.461 ThaliTest[2813:9338251] client session: reverseConnect
2016-04-28 21:30:10.461 ThaliTest[2813:9338251] client session: stateChange:0->1 418CC5DB-B63A-41DA-9996-4D5D4125B76C:8
,2016-04-28 21:30:10.822 ThaliTest[2813:9338928] client session: not connected 418CC5DB-B63A-41DA-9996-4D5D4125B76C:8
2016-04-28 21:30:10.822 ThaliTest[2813:9338928] client session: onLinkFailure: 418CC5DB-B63A-41DA-9996-4D5D4125B76C
2016-04-28 21:30:10.8,23 ThaliTest[2813:9338928] client session: disconnect
2016-04-28 21:30:10.823 ThaliTest[2813:9338928] client session: stateChange:1->0 418CC5DB-B63A-41DA-9996-4D5D4125B76C:8
2016-04-28 21:30:10.823 ThaliTest[2813:9338928] client session: no connect callback (server initiated)
,2016-04-28 21:30:20.462 ThaliTest[2813:9338054] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-04-28 21:30:23.477 ThaliTest[2813:9338251] jxcore: connect 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7
2016-04-28 21:30:23.477 ThaliTest[2813:9338251] client: server will connect
2016-04-28 21:30:23.478 ThaliTest[2813:9338251] client session: reverseConnect
2016-04-28 21:30:23.478 ThaliTest[2813:9338251] client session: stateChange:0->1 418CC5DB-B63A-41DA-9996-4D5D4125B76C:8
,2016-04-28 21:30:23.807 ThaliTest[2813:9339036] client session: not connected 418CC5DB-B63A-41DA-9996-4D5D4125B76C:8
2016-04-28 21:30:23.807 ThaliTest[2813:9339036] client session: onLinkFailure: 418CC5DB-B63A-41DA-9996-4D5D4125B76C
,2016-04-28 21:30:23.807 ThaliTest[2813:9339036] client session: disconnect
2016-04-28 21:30:23.808 ThaliTest[2813:9339036] client session: stateChange:1->0 418CC5DB-B63A-41DA-9996-4D5D4125B76C:8
,2016-04-28 21:30:23.809 ThaliTest[2813:9339036] client session: no connect callback (server initiated)
,2016-04-28 21:30:25.329 ThaliTest[2813:9338054] multipeer manager: restart client
,2016-04-28 21:30:25.356 ThaliTest[2813:9338054] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:8
2016-04-28 21:30:25.357 ThaliTest[2813:9338054] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
,2016-04-28 21:30:25.360 ThaliTest[2813:9338054] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:8
,2016-04-28 21:30:33.479 ThaliTest[2813:9338054] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-04-28 21:30:36.485 ThaliTest[2813:9338251] jxcore: connect 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7
2016-04-28 21:30:36.486 ThaliTest[2813:9338251] client: server will connect
2016-04-28 21:30:36.486 ThaliTest[2813:9338251] client session: reverseConn,ect
2016-04-28 21:30:36.487 ThaliTest[2813:9338251] client session: stateChange:0->1 418CC5DB-B63A-41DA-9996-4D5D4125B76C:8
,2016-04-28 21:30:37.487 ThaliTest[2813:9338928] client session: not connected 418CC5DB-B63A-41DA-9996-4D5D4125B76C:8
,2016-04-28 21:30:37.489 ThaliTest[2813:9338928] client session: onLinkFailure: 418CC5DB-B63A-41DA-9996-4D5D4125B76C
2016-04-28 21:30:37.489 ThaliTest[2813:9338928] client session: disconnect
2016-04-28 21:30:37.489 ThaliTest[2813:9338928] client session:, stateChange:1->0 418CC5DB-B63A-41DA-9996-4D5D4125B76C:8
2016-04-28 21:30:37.490 ThaliTest[2813:9338928] client session: no connect callback (server initiated)
,2016-04-28 21:30:45.328 ThaliTest[2813:9338054] multipeer manager: restart client
,2016-04-28 21:30:45.358 ThaliTest[2813:9338054] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:8
2016-04-28 21:30:45.360 ThaliTest[2813:9338054] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:30:45.361 ThaliTest[2813:9338054] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:8
,2016-04-28 21:30:46.487 ThaliTest[2813:9338054] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-04-28 21:30:49.499 ThaliTest[2813:9338251] jxcore: connect 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7
,2016-04-28 21:30:49.500 ThaliTest[2813:9338251] client: server will connect
2016-04-28 21:30:49.500 ThaliTest[2813:9338251] client session: reverseConnect
2016-04-28 21:30:49.500 ThaliTest[2813:9338251] client session: stateChange:0->1 418CC5DB-B63A-41DA-9996-4D5D4125B76C:8
,2016-04-28 21:30:49.896 ThaliTest[2813:9339072] client session: not connected 418CC5DB-B63A-41DA-9996-4D5D4125B76C:8
2016-04-28 21:30:49.897 ThaliTest[2813:9339072] client session: onLinkFailure: 418CC5DB-B63A-41DA-9996-4D5D4125B76C
2016-04-28 21:30:49.8,97 ThaliTest[2813:9339072] client session: disconnect
2016-04-28 21:30:49.898 ThaliTest[2813:9339072] client session: stateChange:1->0 418CC5DB-B63A-41DA-9996-4D5D4125B76C:8
2016-04-28 21:30:49.898 ThaliTest[2813:9339072] client session: no connect callback (server initiated)
,2016-04-28 21:30:59.501 ThaliTest[2813:9338054] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-04-28 21:31:02.512 ThaliTest[2813:9338251] jxcore: connect 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7
2016-04-28 21:31:02.513 ThaliTest[2813:9338251] client: server will connect
2016-04-28 21:31:02.514 ThaliTest[2813:9338251] client session: reverseConnect
2016-04-28 21:31:02.514 ThaliTest[2813:9338251] client session: stateChange:0->1 418CC5DB-B63A-41DA-9996-4D5D4125B76C:8
,2016-04-28 21:31:03.051 ThaliTest[2813:9339109] client session: not connected 418CC5DB-B63A-41DA-9996-4D5D4125B76C:8
,2016-04-28 21:31:03.052 ThaliTest[2813:9339109] client session: onLinkFailure: 418CC5DB-B63A-41DA-9996-4D5D4125B76C
2016-04-28 21:31:03.053 ThaliTest[2813:9339109] client session: disconnect
2016-04-28 21:31:03.053 ThaliTest[2813:9339109] client session: stateChange:1->0 418CC5DB-B63A-41DA-9996-4D5D4125B76C:8
2016-04-28 21:31:03.053 ThaliTest[2813:9339109] client session: no connect callback (server initiated)
,2016-04-28 21:31:05.329 ThaliTest[2813:9338054] multipeer manager: restart client
,2016-04-28 21:31:05.346 ThaliTest[2813:9338054] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:8
,2016-04-28 21:31:05.360 ThaliTest[2813:9338054] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
,2016-04-28 21:31:05.364 ThaliTest[2813:9338054] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:8
,2016-04-28 21:31:12.515 ThaliTest[2813:9338054] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,WARN testThaliMobileNative: Too many connect retries!
,not ok 177 Connect failed!
  ---
,    operator: fail
,  ...
,# teardown
,2016-04-28 21:31:17.982 ThaliTest[2813:9338251] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-04-28 21:31:17.983 ThaliTest[2813:9338251] jxcore: stopListeningForAdvertisements: success
,ok 178 Should be able to call stopListeningForAdvertisements in teardown
2016-04-28 21:31:17.985 ThaliTest[2813:9338251] jxcore: stopAdvertisingAndListening
2016-04-28 21:31:17.985 ThaliTest[2813:9338251] THEMultipeerManager stopping peer
2016-04-28 21:,31:17.985 ThaliTest[2813:9338251] multipeer manager: stop client timer
2016-04-28 21:31:17.986 ThaliTest[2813:9338251] jxcore: stopAdvertisingAndListening: success
ok 179 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 43. Get error when trying to double connect to a peer
,2016-04-28 21:31:19.813 ThaliTest[2813:9338251] jxcore: startUpdateAdvertisingAndListening
2016-04-28 21:31:19.814 ThaliTest[2813:9338251] server: starting 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:31:19.814 ThaliTest[2813:9338251] multipeer manager: start client restart timer: 0x146f4a60
,2016-04-28 21:31:19.814 ThaliTest[2813:9338251] THEMultipeerManager initialized peer 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:31:19.817 ThaliTest[2813:9338251] jxcore: startUpdateAdvertisingAndListening: success
,ok 180 Can call startUpdateAdvertisingAndListening without error
2016-04-28 21:31:19.819 ThaliTest[2813:9338251] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-04-28 21:31:19.821 ThaliTest[2813:9338251] jxcore: startListeningForAdvertisements: success
,ok 181 Can call startListeningForAdvertisements without error
,2016-04-28 21:31:20.165 ThaliTest[2813:9338054] client: found new peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:31:20.166 ThaliTest[2813:9338054] client: found new peer: 30403743-C17E-454C-8124-9D59A7B25203:8
,2016-04-28 21:31:20.168 ThaliTest[2813:9338251] jxcore: connect C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:31:20.168 ThaliTest[2813:9338251] client: server will connect
,2016-04-28 21:31:20.169 ThaliTest[2813:9338251] client session: reverseConnect
2016-04-28 21:31:20.169 ThaliTest[2813:9338251] client session: stateChange:0->1 C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
,2016-04-28 21:31:20.795 ThaliTest[2813:9339157] client session: not connected C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:31:20.796 ThaliTest[2813:9339157] client session: onLinkFailure: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF
2016-04-28 21:31:20.796 ThaliTest[2813:9339157] client session: disconnect
2016-04-28 21:31:20.796 ThaliTest[2813:9339157] client session: stateChange:1->0 C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
,2016-04-28 21:31:20.798 ThaliTest[2813:9339157] client session: no connect callback (server initiated)
,2016-04-28 21:31:20.930 ThaliTest[2813:9338054] multipeer session: reset timer
,2016-04-28 21:31:20.931 ThaliTest[2813:9338054] server: rejecting invitation from C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF due to previous generation (337492EA-97B4-404F-B8FE-E0E7631E59C8:9 != 337492EA-97B4-404F-B8FE-E0E7631E59C8:8)
,2016-04-28 21:31:22.340 ThaliTest[2813:9338054] client: found new peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:8
,2016-04-28 21:31:24.341 ThaliTest[2813:9338054] multipeer session: reset timer
2016-04-28 21:31:24.341 ThaliTest[2813:9338054] server: disconnecting to refresh session (C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF)
2016-04-28 21:31:24.341 ThaliTest[2813:9338054], server: rejecting invitation from C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF due to previous generation (337492EA-97B4-404F-B8FE-E0E7631E59C8:9 != 337492EA-97B4-404F-B8FE-E0E7631E59C8:8)
,2016-04-28 21:31:27.546 ThaliTest[2813:9338054] multipeer session: reset timer
2016-04-28 21:31:27.547 ThaliTest[2813:9338054] server: disconnecting to refresh session (C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF)
2016-04-28 21:31:27.547 ThaliTest[2813:9338054], server: rejecting invitation from C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF due to previous generation (337492EA-97B4-404F-B8FE-E0E7631E59C8:9 != 337492EA-97B4-404F-B8FE-E0E7631E59C8:8)
,2016-04-28 21:31:30.170 ThaliTest[2813:9338054] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-04-28 21:31:30.655 ThaliTest[2813:9338054] multipeer session: reset timer
2016-04-28 21:31:30.655 ThaliTest[2813:9338054] server: disconnecting to refresh session (C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF)
2016-04-28 21:31:30.655 ThaliTest[2813:9338054] server: rejecting invitation from C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF due to previous generation (337492EA-97B4-404F-B8FE-E0E7631E59C8:9 != 337492EA-97B4-404F-B8FE-E0E7631E59C8:8)
,2016-04-28 21:31:33.178 ThaliTest[2813:9338251] jxcore: connect C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:31:33.178 ThaliTest[2813:9338251] client: server will connect
2016-04-28 21:31:33.179 ThaliTest[2813:9338251] client session: reverseConnect
2016-04-28 21:31:33.179 ThaliTest[2813:9338251] client session: stateChange:0->1 C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
,2016-04-28 21:31:33.303 ThaliTest[2813:9339168] client session: not connected C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:31:33.303 ThaliTest[2813:9339168] client session: onLinkFailure: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF
,2016-04-28 21:31:33.304 ThaliTest[2813:9339168] client session: disconnect
2016-04-28 21:31:33.305 ThaliTest[2813:9339168] client session: stateChange:1->0 C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:31:33.305 ThaliTest[2813:9339168] client session: no connect callback (server initiated)
,2016-04-28 21:31:33.841 ThaliTest[2813:9338054] multipeer session: reset timer
2016-04-28 21:31:33.841 ThaliTest[2813:9338054] server: disconnecting to refresh session (C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF)
2016-04-28 21:31:33.842 ThaliTest[2813:9338054] server: rejecting invitation from C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF due to previous generation (337492EA-97B4-404F-B8FE-E0E7631E59C8:9 != 337492EA-97B4-404F-B8FE-E0E7631E59C8:8)
,2016-04-28 21:31:37.459 ThaliTest[2813:9338054] multipeer session: reset timer
2016-04-28 21:31:37.460 ThaliTest[2813:9338054] server: disconnecting to refresh session (C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF)
2016-04-28 21:31:37.460 ThaliTest[2813:9338054], server: rejecting invitation from C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF due to previous generation (337492EA-97B4-404F-B8FE-E0E7631E59C8:9 != 337492EA-97B4-404F-B8FE-E0E7631E59C8:8)
,2016-04-28 21:31:39.816 ThaliTest[2813:9338054] multipeer manager: restart client
,2016-04-28 21:31:39.841 ThaliTest[2813:9338054] client: found updated peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:31:39.841 ThaliTest[2813:9338054] client: found updated peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:31:39.843 ,ThaliTest[2813:9338054] client: found updated peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:31:40.676 ThaliTest[2813:9338054] multipeer session: reset timer
2016-04-28 21:31:40.676 ThaliTest[2813:9338054] server: disconnecting to refresh session (C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF)
,2016-04-28 21:31:40.676 ThaliTest[2813:9338054] server: rejecting invitation from C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF due to previous generation (337492EA-97B4-404F-B8FE-E0E7631E59C8:9 != 337492EA-97B4-404F-B8FE-E0E7631E59C8:8)
,2016-04-28 21:31:43.180 ThaliTest[2813:9338054] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-04-28 21:31:43.851 ThaliTest[2813:9338054] multipeer session: reset timer
2016-04-28 21:31:43.852 ThaliTest[2813:9338054] server: disconnecting to refresh session (C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF)
2016-04-28 21:31:43.852 ThaliTest[2813:9338054] server: rejecting invitation from C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF due to previous generation (337492EA-97B4-404F-B8FE-E0E7631E59C8:9 != 337492EA-97B4-404F-B8FE-E0E7631E59C8:8)
,2016-04-28 21:31:46.187 ThaliTest[2813:9338251] jxcore: connect C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:31:46.188 ThaliTest[2813:9338251] client: server will connect
2016-04-28 21:31:46.188 ThaliTest[2813:9338251] client session: reverseConn,ect
2016-04-28 21:31:46.188 ThaliTest[2813:9338251] client session: stateChange:0->1 C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:31:46.475 ThaliTest[2813:9339109] client session: not connected C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:31:46.476 ThaliTest[2813:9339109] client session: onLinkFailure: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF
2016-04-28 21:31:46.476 ThaliTest[2813:9339109] client session: disconnect
2016-04-28 21:31:46.476 ThaliTest[2813:9339109] client session: stateChange:1->0 C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:31:46.479 ThaliTest[2813:9339109] client session: no connect callback (server initiated)
,2016-04-28 21:31:46.948 ThaliTest[2813:9338054] multipeer session: reset timer
2016-04-28 21:31:46.948 ThaliTest[2813:9338054] server: disconnecting to refresh session (C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF)
2016-04-28 21:31:46.948 ThaliTest[2813:9338054], server: rejecting invitation from C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF due to previous generation (337492EA-97B4-404F-B8FE-E0E7631E59C8:9 != 337492EA-97B4-404F-B8FE-E0E7631E59C8:8)
,2016-04-28 21:31:50.089 ThaliTest[2813:9338054] multipeer session: reset timer
2016-04-28 21:31:50.089 ThaliTest[2813:9338054] server: disconnecting to refresh session (C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF)
2016-04-28 21:31:50.089 ThaliTest[2813:9338054] server: rejecting invitation from C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF due to previous generation (337492EA-97B4-404F-B8FE-E0E7631E59C8:9 != 337492EA-97B4-404F-B8FE-E0E7631E59C8:8)
,2016-04-28 21:31:56.189 ThaliTest[2813:9338054] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-04-28 21:31:59.195 ThaliTest[2813:9338251] jxcore: connect C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:31:59.196 ThaliTest[2813:9338251] client: server will connect
2016-04-28 21:31:59.196 ThaliTest[2813:9338251] client session: reverseConnect
2016-04-28 21:31:59.197 ThaliTest[2813:9338251] client session: stateChange:0->1 C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:31:59.816 ThaliTest[2813:9338054] multipeer manager: restart client
,2016-04-28 21:31:59.852 ThaliTest[2813:9338054] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:31:59.853 ThaliTest[2813:9338054] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:31:59.854 ThaliTest[2813:9338054] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:32:09.197 ThaliTest[2813:9338054] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-04-28 21:32:12.207 ThaliTest[2813:9338251] jxcore: connect C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:32:12.208 ThaliTest[2813:9338251] client: already connect(ing/ed) to C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:32:12.208 Thali,Test[2813:9338251] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-04-28 21:32:15.219 ThaliTest[2813:9338251] jxcore: connect C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:32:15.220 ThaliTest[2813:9338251] client: already connect(ing/ed) to C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:32:15.220 Thali,Test[2813:9338251] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-04-28 21:32:18.234 ThaliTest[2813:9338251] jxcore: connect C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:32:18.235 ThaliTest[2813:9338251] client: already connect(ing/ed) to C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:32:18.236 ThaliTest[2813:9338251] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-04-28 21:32:19.816 ThaliTest[2813:9338054] multipeer manager: restart client
,2016-04-28 21:32:19.836 ThaliTest[2813:9338054] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:32:19.848 ThaliTest[2813:9338054] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
,2016-04-28 21:32:19.853 ThaliTest[2813:9338054] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:32:21.244 ThaliTest[2813:9338251] jxcore: connect C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:32:21.245 ThaliTest[2813:9338251] client: already connect(ing/ed) to C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:32:21.246 Thali,Test[2813:9338251] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-04-28 21:32:24.255 ThaliTest[2813:9338251] jxcore: connect C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:32:24.256 ThaliTest[2813:9338251] client: already connect(ing/ed) to C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:32:24.256 ThaliTest[2813:9338251] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-04-28 21:32:27.275 ThaliTest[2813:9338251] jxcore: connect C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:32:27.276 ThaliTest[2813:9338251] client: already connect(ing/ed) to C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:32:27.276 Thali,Test[2813:9338251] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
WARN testThaliMobileNative: Too many connect retries!
,2016-04-28 21:32:32.200 ThaliTest[2813:9339360] client session: not connected C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:32:32.200 ThaliTest[2813:9339360] client session: onLinkFailure: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF
2016-04-28 21:32:32.2,01 ThaliTest[2813:9339360] client session: disconnect
2016-04-28 21:32:32.201 ThaliTest[2813:9339360] client session: stateChange:1->0 C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:32:32.202 ThaliTest[2813:9339360] client session: no connect callback (server initiated)
,2016-04-28 21:32:39.816 ThaliTest[2813:9338054] multipeer manager: restart client
,2016-04-28 21:32:39.845 ThaliTest[2813:9338054] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:32:39.845 ThaliTest[2813:9338054] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
2016-04-28 21:32:39.846 ThaliTest[2813:9338054] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
,2016-04-28 21:32:59.815 ThaliTest[2813:9338054] multipeer manager: restart client
,2016-04-28 21:32:59.844 ThaliTest[2813:9338054] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:32:59.846 ThaliTest[2813:9338054] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:32:59.847 ThaliTest[2813:9338054] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:33:19.816 ThaliTest[2813:9338054] multipeer manager: restart client
,2016-04-28 21:33:19.845 ThaliTest[2813:9338054] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:33:19.845 ThaliTest[2813:9338054] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:33:19.84,6 ThaliTest[2813:9338054] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:33:39.816 ThaliTest[2813:9338054] multipeer manager: restart client
,2016-04-28 21:33:39.833 ThaliTest[2813:9338054] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:33:39.846 ThaliTest[2813:9338054] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:33:39.848 ThaliTest[2813:9338054] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:33:59.815 ThaliTest[2813:9338054] multipeer manager: restart client
,2016-04-28 21:33:59.845 ThaliTest[2813:9338054] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:33:59.849 ThaliTest[2813:9338054] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:33:59.850 ThaliTest[2813:9338054] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:34:19.747 ThaliTest[2813:9338054] multipeer manager: restart client
,2016-04-28 21:34:19.777 ThaliTest[2813:9338054] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:34:19.779 ThaliTest[2813:9338054] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
2016-04-28 21:34:19.780 ThaliTest[2813:9338054] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
,2016-04-28 21:34:39.747 ThaliTest[2813:9338054] multipeer manager: restart client
,2016-04-28 21:34:39.776 ThaliTest[2813:9338054] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:34:39.777 ThaliTest[2813:9338054] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
,2016-04-28 21:34:39.779 ThaliTest[2813:9338054] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:34:59.746 ThaliTest[2813:9338054] multipeer manager: restart client
,2016-04-28 21:34:59.776 ThaliTest[2813:9338054] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:34:59.777 ThaliTest[2813:9338054] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:34:59.777 ThaliTest[2813:9338054] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:35:19.746 ThaliTest[2813:9338054] multipeer manager: restart client
,2016-04-28 21:35:19.778 ThaliTest[2813:9338054] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:35:19.779 ThaliTest[2813:9338054] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:35:19.78,0 ThaliTest[2813:9338054] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:35:39.746 ThaliTest[2813:9338054] multipeer manager: restart client
,2016-04-28 21:35:39.779 ThaliTest[2813:9338054] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:35:39.779 ThaliTest[2813:9338054] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:35:39.779 ThaliTest[2813:9338054] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:35:59.747 ThaliTest[2813:9338054] multipeer manager: restart client
,2016-04-28 21:35:59.778 ThaliTest[2813:9338054] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:35:59.779 ThaliTest[2813:9338054] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:35:59.77,9 ThaliTest[2813:9338054] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:36:19.747 ThaliTest[2813:9338054] multipeer manager: restart client
,2016-04-28 21:36:19.778 ThaliTest[2813:9338054] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:36:19.778 ThaliTest[2813:9338054] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:36:19.780 ThaliTest[2813:9338054] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:36:39.747 ThaliTest[2813:9338054] multipeer manager: restart client
,2016-04-28 21:36:39.774 ThaliTest[2813:9338054] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:36:39.779 ThaliTest[2813:9338054] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:36:39.780 ThaliTest[2813:9338054] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:36:59.747 ThaliTest[2813:9338054] multipeer manager: restart client
,2016-04-28 21:36:59.779 ThaliTest[2813:9338054] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:36:59.780 ThaliTest[2813:9338054] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:36:59.781 ThaliTest[2813:9338054] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:37:19.747 ThaliTest[2813:9338054] multipeer manager: restart client
,2016-04-28 21:37:19.776 ThaliTest[2813:9338054] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:37:19.779 ThaliTest[2813:9338054] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:37:19.780 ThaliTest[2813:9338054] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:37:39.747 ThaliTest[2813:9338054] multipeer manager: restart client
,2016-04-28 21:37:39.772 ThaliTest[2813:9338054] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:37:39.777 ThaliTest[2813:9338054] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
2016-04-28 21:37:39.778 ThaliTest[2813:9338054] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
,2016-04-28 21:37:59.747 ThaliTest[2813:9338054] multipeer manager: restart client
,2016-04-28 21:37:59.775 ThaliTest[2813:9338054] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:37:59.779 ThaliTest[2813:9338054] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
,2016-04-28 21:37:59.781 ThaliTest[2813:9338054] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:38:19.747 ThaliTest[2813:9338054] multipeer manager: restart client
,2016-04-28 21:38:19.773 ThaliTest[2813:9338054] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:38:19.777 ThaliTest[2813:9338054] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:38:19.778 ThaliTest[2813:9338054] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:38:39.746 ThaliTest[2813:9338054] multipeer manager: restart client
,2016-04-28 21:38:39.777 ThaliTest[2813:9338054] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:38:39.777 ThaliTest[2813:9338054] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:38:39.782 ThaliTest[2813:9338054] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:38:59.747 ThaliTest[2813:9338054] multipeer manager: restart client
,2016-04-28 21:38:59.778 ThaliTest[2813:9338054] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:38:59.778 ThaliTest[2813:9338054] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:38:59.77,9 ThaliTest[2813:9338054] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:39:19.747 ThaliTest[2813:9338054] multipeer manager: restart client
,2016-04-28 21:39:19.773 ThaliTest[2813:9338054] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:39:19.774 ThaliTest[2813:9338054] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
,2016-04-28 21:39:19.779 ThaliTest[2813:9338054] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:39:39.747 ThaliTest[2813:9338054] multipeer manager: restart client
,2016-04-28 21:39:39.776 ThaliTest[2813:9338054] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:39:39.778 ThaliTest[2813:9338054] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:39:39.779 ThaliTest[2813:9338054] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:39:59.747 ThaliTest[2813:9338054] multipeer manager: restart client
,2016-04-28 21:39:59.775 ThaliTest[2813:9338054] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:39:59.775 ThaliTest[2813:9338054] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:39:59.780 ThaliTest[2813:9338054] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:40:19.747 ThaliTest[2813:9338054] multipeer manager: restart client
,2016-04-28 21:40:19.778 ThaliTest[2813:9338054] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:40:19.780 ThaliTest[2813:9338054] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:40:19.78,1 ThaliTest[2813:9338054] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:40:39.747 ThaliTest[2813:9338054] multipeer manager: restart client
,2016-04-28 21:40:39.778 ThaliTest[2813:9338054] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:40:39.781 ThaliTest[2813:9338054] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
2016-04-28 21:40:39.782 ThaliTest[2813:9338054] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
,2016-04-28 21:40:59.747 ThaliTest[2813:9338054] multipeer manager: restart client
,2016-04-28 21:40:59.776 ThaliTest[2813:9338054] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:40:59.776 ThaliTest[2813:9338054] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
2016-04-28 21:40:59.776 ThaliTest[2813:9338054] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:41:19.746 ThaliTest[2813:9338054] multipeer manager: restart client
,2016-04-28 21:41:19.779 ThaliTest[2813:9338054] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:41:19.779 ThaliTest[2813:9338054] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
2016-04-28 21:41:19.780 ThaliTest[2813:9338054] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:41:39.747 ThaliTest[2813:9338054] multipeer manager: restart client
,2016-04-28 21:41:39.776 ThaliTest[2813:9338054] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:41:39.776 ThaliTest[2813:9338054] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:41:39.778 ThaliTest[2813:9338054] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:41:59.747 ThaliTest[2813:9338054] multipeer manager: restart client
,2016-04-28 21:41:59.779 ThaliTest[2813:9338054] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:41:59.780 ThaliTest[2813:9338054] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:41:59.781 ThaliTest[2813:9338054] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:42:19.747 ThaliTest[2813:9338054] multipeer manager: restart client
,2016-04-28 21:42:19.774 ThaliTest[2813:9338054] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:42:19.774 ThaliTest[2813:9338054] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:42:19.776 ThaliTest[2813:9338054] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:42:39.747 ThaliTest[2813:9338054] multipeer manager: restart client
,2016-04-28 21:42:39.779 ThaliTest[2813:9338054] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:42:39.781 ThaliTest[2813:9338054] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
,2016-04-28 21:42:39.783 ThaliTest[2813:9338054] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:42:59.747 ThaliTest[2813:9338054] multipeer manager: restart client
,2016-04-28 21:42:59.777 ThaliTest[2813:9338054] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:42:59.781 ThaliTest[2813:9338054] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
2016-04-28 21:42:59.782 ThaliTest[2813:9338054] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
,2016-04-28 21:43:19.747 ThaliTest[2813:9338054] multipeer manager: restart client
,2016-04-28 21:43:19.775 ThaliTest[2813:9338054] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:43:19.776 ThaliTest[2813:9338054] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
,2016-04-28 21:43:19.781 ThaliTest[2813:9338054] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:43:39.747 ThaliTest[2813:9338054] multipeer manager: restart client
,2016-04-28 21:43:39.777 ThaliTest[2813:9338054] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:43:39.778 ThaliTest[2813:9338054] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:43:39.77,9 ThaliTest[2813:9338054] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:43:59.746 ThaliTest[2813:9338054] multipeer manager: restart client
,2016-04-28 21:43:59.774 ThaliTest[2813:9338054] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:43:59.776 ThaliTest[2813:9338054] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
2016-04-28 21:43:59.776 ThaliTest[2813:9338054] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
,2016-04-28 21:44:19.747 ThaliTest[2813:9338054] multipeer manager: restart client
,2016-04-28 21:44:19.781 ThaliTest[2813:9338054] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:44:19.781 ThaliTest[2813:9338054] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:44:19.782 ThaliTest[2813:9338054] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:44:39.747 ThaliTest[2813:9338054] multipeer manager: restart client
,2016-04-28 21:44:39.775 ThaliTest[2813:9338054] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:44:39.778 ThaliTest[2813:9338054] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:44:39.779 ThaliTest[2813:9338054] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:44:59.747 ThaliTest[2813:9338054] multipeer manager: restart client
,2016-04-28 21:44:59.778 ThaliTest[2813:9338054] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:44:59.779 ThaliTest[2813:9338054] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:44:59.78,1 ThaliTest[2813:9338054] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:45:19.747 ThaliTest[2813:9338054] multipeer manager: restart client
,2016-04-28 21:45:19.775 ThaliTest[2813:9338054] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:45:19.775 ThaliTest[2813:9338054] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:45:19.778 ThaliTest[2813:9338054] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:45:39.747 ThaliTest[2813:9338054] multipeer manager: restart client
,2016-04-28 21:45:39.778 ThaliTest[2813:9338054] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:45:39.778 ThaliTest[2813:9338054] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:45:39.781 ThaliTest[2813:9338054] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:45:59.747 ThaliTest[2813:9338054] multipeer manager: restart client
,2016-04-28 21:45:59.776 ThaliTest[2813:9338054] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:45:59.776 ThaliTest[2813:9338054] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
,2016-04-28 21:45:59.779 ThaliTest[2813:9338054] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:46:19.747 ThaliTest[2813:9338054] multipeer manager: restart client
,2016-04-28 21:46:19.772 ThaliTest[2813:9338054] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:46:19.773 ThaliTest[2813:9338054] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:46:19.778 ThaliTest[2813:9338054] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:46:39.747 ThaliTest[2813:9338054] multipeer manager: restart client
,2016-04-28 21:46:39.774 ThaliTest[2813:9338054] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:46:39.775 ThaliTest[2813:9338054] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
,2016-04-28 21:46:39.779 ThaliTest[2813:9338054] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:46:59.747 ThaliTest[2813:9338054] multipeer manager: restart client
,2016-04-28 21:46:59.777 ThaliTest[2813:9338054] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:46:59.777 ThaliTest[2813:9338054] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:46:59.778 ThaliTest[2813:9338054] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9

```
