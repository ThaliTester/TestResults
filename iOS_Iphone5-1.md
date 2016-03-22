#### Test 63680118d4cb974_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/63680118d4cb974/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/6E292494-5FE2-4D5D-A5EC-CD91C7102318/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/6E292494-5FE2-4D5D-A5EC-CD91C7102318/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/63680118d4cb974/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/63680118d4cb974/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/325087AA-5812-4A7E-A690-3AF8ACBA8C34/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54794"
,(lldb)     command script import "/tmp/6E292494-5FE2-4D5D-A5EC-CD91C7102318/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-22 14:36:00.811 ThaliTest[1510:3587186] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/EF619B14-A068-489A-96BA-20ED5577CCCC/Library/Cookies/Cookies.binarycookies
,2016-03-22 14:36:01.380 ThaliTest[1510:3587186] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-22 14:36:01.382 ThaliTest[1510:3587186] Multi-tasking -> Device: YES, App: YES
,2016-03-22 14:36:01.402 ThaliTest[1510:3587186] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-22 14:36:03.710 ThaliTest[1510:3587186] Using UIWebView
,2016-03-22 14:36:03.714 ThaliTest[1510:3587186] [CDVTimer][handleopenurl] 0.424981ms
,2016-03-22 14:36:03.720 ThaliTest[1510:3587186] [CDVTimer][intentandnavigationfilter] 5.490005ms
2016-03-22 14:36:03.721 ThaliTest[1510:3587186] [CDVTimer][gesturehandler] 0.270009ms
2016-03-22 14:36:03.721 ThaliTest[1510:3587186] [CDVTimer][TotalPluginStartup] 7.273018ms
,2016-03-22 14:36:12.928 ThaliTest[1510:3587186] Resetting plugins due to page load.
,2016-03-22 14:36:16.867 ThaliTest[1510:3587186] Finished load of: file:///var/mobile/Containers/Bundle/Application/325087AA-5812-4A7E-A690-3AF8ACBA8C34/ThaliTest.app/www/index.html
,2016-03-22 14:36:17.075 ThaliTest[1510:3587186] JXcore Cordova plugin initializing
,2016-03-22 14:36:17.077 ThaliTest[1510:3587369] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-22 14:36:33.597 ThaliTest[1510:3587369] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-22 14:36:33.598 ThaliTest[1510:3587369] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-22 14:36:33.598 ThaliTest[1510:3587369] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-22 14:36:33.601 ThaliTest[1510:3587369] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/325087AA-5812-4A7E-A690-3AF8ACBA8C34/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/325087AA-5812-4A7E-A690-3AF8ACBA8C34/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/325087AA-5812-4A7E-A690-3AF8ACBA8C34/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/325087AA-5812-4A7E-A690-3AF8ACBA8C34/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/325087AA-5812-4A7E-A690-3AF8ACBA8C34/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/325087AA-5812-4A7E-A690-3AF8ACBA8C34/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/325087AA-5812-4A7E-A690-3AF8ACBA8C34/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/325087AA-5812-4A7E-A690-3AF8ACBA8C34/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/325087AA-5812-4A7E-A690-3AF8ACBA8C34/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/325087AA-5812-4A7E-A690-3AF8ACBA8C34/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/325087AA-5812-4A7E-A690-3AF8ACBA8C34/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/325087AA-5812-4A7E-A690-3AF8ACBA8C34/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/325087AA-5812-4A7E-A690-3AF8ACBA8C34/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/325087AA-5812-4A7E-A690-3AF8ACBA8C34/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/325087AA-5812-4A7E-A690-3AF8ACBA8C34/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/325087AA-5812-4A7E-A690-3AF8ACBA8C34/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/325087AA-5812-4A7E-A690-3AF8ACBA8C34/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/325087AA-5812-4A7E-A690-3AF8ACBA8C34/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/325087AA-5812-4A7E-A690-3AF8ACBA8C34/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/325087AA-5812-4A7E-A690-3AF8ACBA8C34/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-22 14:36:47.016 ThaliTest[1510:3587186] THREAD WARNING: ['JXcore'] took '12727.280762' ms. Plugin should use a background thread.
,2016-03-22 14:36:47.017 ThaliTest[1510:3587315] void SendDelegateMessage(NSInvocation *): delegate (webView:decidePolicyForNavigationAction:request:frame:decisionListener:) failed to return after waiting 10 seconds. main run loop mode: kCFRunLoopDefaultMode
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50802
,ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50804
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
,DEBUG createNativeListener: listening 50807
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
,DEBUG createNativeListener: listening 50811
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
,DEBUG createNativeListener: listening 50816
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
,DEBUG createNativeListener: listening 50820
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
,DEBUG createNativeListener: listening 50824
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
,DEBUG createNativeListener: listening 50828
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
,DEBUG createNativeListener: listening 50832
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
,DEBUG createNativeListener: listening 50884
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
,DEBUG createNativeListener: listening 50888
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
,# 14. multiplex can send data
,ok 47 String should be length:200
,# teardown
,# setup
,# 15. enqueue and run in order
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
,# 16. enqueueAtTop and run backwards
,ok 57 thirdPromise - first to run
,ok 58 thirdPromise - in resolve
,ok 59 secondPromise - second to run
,ok 60 secondPromise - in catch
,ok 61 firstPromise - third to run
,ok 62 firstPromise - in then
,ok 63 testing promises
,# teardown
,# setup
,# 17. mix enqueue and enqueueAtTop
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
,# 18. queues handled independently
,ok 73 all short operations completed before the long resolves
,# teardown
,# setup
,# 19. basic
,ok 74 sane
,# teardown
,# setup
,# 20. another
,ok 75 sane
,# teardown
,# setup
,# 21. can pass data in setup
,ok 76 test participant has uuid
,ok 77 participant data matches
,ok 78 test participant has uuid
,ok 79 participant data matches
,ok 80 test participant has uuid
,ok 81 participant data matches
,# teardown
,# setup
,# 22. #startListeningForAdvertisements should fail if start not called
,ok 82 specific error should be returned
,# teardown
,ok 83 error should be null
,ok 84 error should be null
,# setup
,# 23. #startUpdateAdvertisingAndListening should fail if start not called
,ok 85 specific error should be returned
,# teardown
,ok 86 error should be null
,ok 87 error should be null
,# setup
,# 24. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50900
,2016-03-22 14:39:15.036 ThaliTest[1510:3587369] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-22 14:39:15.038 ThaliTest[1510:3587369] jxcore: stopListeningForAdvertisements: success
,ok 88 error should be null
,ok 89 error should be null
,2016-03-22 14:39:15.042 ThaliTest[1510:3587369] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-22 14:39:15.043 ThaliTest[1510:3587369] jxcore: stopListeningForAdvertisements: success
,ok 90 error should be null
,ok 91 error should be null
,# teardown
,2016-03-22 14:39:15.232 ThaliTest[1510:3587369] jxcore: stopAdvertisingAndListening
2016-03-22 14:39:15.232 ThaliTest[1510:3587369] THEMultipeerManager stopping peer
2016-03-22 14:39:15.232 ThaliTest[1510:3587369] jxcore: stopAdvertisingAndListening: success
2016-03-22 14:39:15.233 ThaliTest[1510:3587369] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-22 14:39:15.234 ThaliTest[1510,:3587369] jxcore: stopListeningForAdvertisements: success
,ok 92 error should be null
,ok 93 error should be null
,# setup
,# 25. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50902
,2016-03-22 14:39:15.633 ThaliTest[1510:3587369] jxcore: startListeningForAdvertisements
,2016-03-22 14:39:15.635 ThaliTest[1510:3587369] multipeer manager: start client restart timer: 0x14ed3590
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-22 14:39:15.636 Th,aliTest[1510:3587369] jxcore: startListeningForAdvertisements: success
,ok 94 error should be null
ok 95 error should be null
2016-03-22 14:39:15.657 ThaliTest[1510:3587369] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-22 14:39:15.661 ThaliTest[1510:3587369] jxcore: startListeningForAdvertisements: success
,ok 96 error should be null
,ok 97 error should be null
,# teardown
,2016-03-22 14:39:15.954 ThaliTest[1510:3587369] jxcore: stopAdvertisingAndListening
2016-03-22 14:39:15.954 ThaliTest[1510:3587369] THEMultipeerManager stopping peer
2016-03-22 14:39:15.954 ThaliTest[1510:3587369] jxcore: stopAdvertisingAndListening: success
2016-03-22 14:39:15.955 ThaliTest[1510:3587369] jxcore: stopListeningForAdvertisements
2016-03-22 14:39:15.955 ThaliTest[1510:3587369] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-22 14:39:15.957 ThaliTest[1510:3587369] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 98 error should be null
,ok 99 error should be null
,# setup
,# 26. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50904
,2016-03-22 14:39:16.560 ThaliTest[1510:3587369] jxcore: startUpdateAdvertisingAndListening
2016-03-22 14:39:16.560 ThaliTest[1510:3587369] server: starting 46287C39-66D9-4C88-AB7B-A74C4F9B045C:1
2016-03-22 14:39:16.561 ThaliTest[1510:3587369] multipeer m,anager: start client restart timer: 0x14ed3590
2016-03-22 14:39:16.561 ThaliTest[1510:3587369] THEMultipeerManager initialized peer 46287C39-66D9-4C88-AB7B-A74C4F9B045C:1
2016-03-22 14:39:16.562 ThaliTest[1510:3587369] jxcore: startUpdateAdvertisingAndLi,stening: success
,ok 100 error should be null
,ok 101 error should be null
,2016-03-22 14:39:16.625 ThaliTest[1510:3587369] jxcore: startUpdateAdvertisingAndListening
2016-03-22 14:39:16.625 ThaliTest[1510:3587369] THEMultipeerManager stopping peer
2016-03-22 14:39:16.626 ThaliTest[1510:3587369] multipeer manager: stop client ti,mer
2016-03-22 14:39:16.626 ThaliTest[1510:3587369] server: starting 46287C39-66D9-4C88-AB7B-A74C4F9B045C:2
,2016-03-22 14:39:16.632 ThaliTest[1510:3587369] multipeer manager: start client restart timer: 0x14ed3590
,2016-03-22 14:39:16.638 ThaliTest[1510:3587369] THEMultipeerManager initialized peer 46287C39-66D9-4C88-AB7B-A74C4F9B045C:2
,2016-03-22 14:39:16.639 ThaliTest[1510:3587369] jxcore: startUpdateAdvertisingAndListening: success
,ok 102 error should be null
,ok 103 error should be null
,# teardown
,2016-03-22 14:39:17.060 ThaliTest[1510:3587369] jxcore: stopAdvertisingAndListening
2016-03-22 14:39:17.061 ThaliTest[1510:3587369] THEMultipeerManager stopping peer
2016-03-22 14:39:17.061 ThaliTest[1510:3587369] multipeer manager: stop client timer
2016-03-22 14:39:17.061 ThaliTest[1510:3587369] jxcore: stopAdvertisingAndListening: success
2016-03-22 14:39:17.062 ThaliTest[1510:3587369] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-22 14:39:17.063 ThaliTest[1510:3587369] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 104 error should be null
,ok 105 error should be null
,# setup
,# 27. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50909
,2016-03-22 14:39:18.642 ThaliTest[1510:3587369] jxcore: stopAdvertisingAndListening
2016-03-22 14:39:18.642 ThaliTest[1510:3587369] THEMultipeerManager stopping peer
2016-03-22 14:39:18.642 ThaliTest[1510:3587369] jxcore: stopAdvertisingAndListening: suc,cess
,ok 106 error should be null
,ok 107 error should be null
,2016-03-22 14:39:18.647 ThaliTest[1510:3587369] jxcore: stopAdvertisingAndListening
2016-03-22 14:39:18.647 ThaliTest[1510:3587369] THEMultipeerManager stopping peer
2016-03-22 14:39:18.647 ThaliTest[1510:3587369] jxcore: stopAdvertisingAndListening: success
ok 108 error should be null
,ok 109 error should be null
,# teardown
,2016-03-22 14:39:18.975 ThaliTest[1510:3587369] jxcore: stopAdvertisingAndListening
2016-03-22 14:39:18.975 ThaliTest[1510:3587369] THEMultipeerManager stopping peer
2016-03-22 14:39:18.976 ThaliTest[1510:3587369] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-22 14:39:18.976 ThaliTest[1510:3587369] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-22 14:39:18.977 ThaliTest[1510,:3587369] jxcore: stopListeningForAdvertisements: success
,ok 110 error should be null
,ok 111 error should be null
,# setup
,# 28. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50911
,ok 112 first call should succeed
,ok 113 first call should succeed
,ok 114 specific error should be returned
,# teardown
,2016-03-22 14:39:19.612 ThaliTest[1510:3587369] jxcore: stopAdvertisingAndListening
2016-03-22 14:39:19.612 ThaliTest[1510:3587369] THEMultipeerManager stopping peer
2016-03-22 14:39:19.612 ThaliTest[1510:3587369] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-22 14:39:19.612 ThaliTest[1510:3587369] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-22 14:39:19.613 ThaliTest[1510,:3587369] jxcore: stopListeningForAdvertisements: success
,ok 115 error should be null
,ok 116 error should be null
,# setup
,# 29. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50913
,2016-03-22 14:39:20.035 ThaliTest[1510:3587369] jxcore: startListeningForAdvertisements
2016-03-22 14:39:20.036 ThaliTest[1510:3587369] multipeer manager: start client restart timer: 0x14ed3590
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-22 14:39:20.037 ThaliTest[1510:3587369] jxcore: startListeningForAdvertisements: success
,2016-03-22 14:39:20.071 ThaliTest[1510:3587369] jxcore: startUpdateAdvertisingAndListening
2016-03-22 14:39:20.071 ThaliTest[1510:3587369] server: starting 46287C39-66D9-4C88-AB7B-A74C4F9B045C:3
2016-03-22 14:39:20.071 ThaliTest[1510:3587369] THEMultipee,rManager initialized peer 46287C39-66D9-4C88-AB7B-A74C4F9B045C:3
2016-03-22 14:39:20.071 ThaliTest[1510:3587369] jxcore: startUpdateAdvertisingAndListening: success
,ok 117 called only once
ok 118 discovery state matches
ok 119 advertising state matches
,# teardown
,2016-03-22 14:39:20.283 ThaliTest[1510:3587369] jxcore: stopAdvertisingAndListening
2016-03-22 14:39:20.283 ThaliTest[1510:3587369] THEMultipeerManager stopping peer
2016-03-22 14:39:20.283 ThaliTest[1510:3587369] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-22 14:39:20.284 ThaliTest[1510:3587369] jxcore: stopListeningForAdvertisements
2016-03-22 14:39:20.284 ThaliTest[1510:3587369] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-22 14:39:20.285 ThaliTest[1510:3587369] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 120 error should be null
,ok 121 error should be null
,# setup
,# 30. does not send duplicate availability changes
,ok 122 should be called once
,ok 123 should not have been called more than once
,# teardown
,ok 124 error should be null
ok 125 error should be null
,# setup
,# 31. can get the network status
,ok 126 network status should have certain non-empty properties
,# teardown
,ok 127 error should be null
,ok 128 error should be null
,# setup
,# 32. wifi peer is marked unavailable if announcements stop
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
,ok 129 host address should match
,ok 130 port should match
,ok 131 host address should be null
,ok 132 port should should be null
,# teardown
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 133 error should be null
,ok 134 error should be null
,# setup
,# 33. Can call start/stopListeningForAdvertisements
,2016-03-22 14:39:25.651 ThaliTest[1510:3587369] jxcore: startListeningForAdvertisements
2016-03-22 14:39:25.652 ThaliTest[1510:3587369] multipeer manager: start client restart timer: 0x14ed3590
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-22 14:39:25.653 ThaliTest[1510:3587369] jxcore: startListeningForAdvertisements: success
,ok 135 Can call startListeningForAdvertisements without error
2016-03-22 14:39:25.654 ThaliTest[1510:3587369] jxcore: stopListeningForAdvertisements
2016-03-22 14:39:25.655 ThaliTest[1510:3587369] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-22 14:39:25.657 ThaliTest[1510:3587369] jxcore: stopListeningForAdvertisements: success
,ok 136 Can call stopListeningForAdvertisements without error
# teardown
,2016-03-22 14:39:26.003 ThaliTest[1510:3587369] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-22 14:39:26.004 ThaliTest[1510:3587369] jxcore: stopListeningForAdvertisements: success
,ok 137 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-22 14:39:26.006 ThaliTest[1510:3587369] jxcore: stopAdvertisingAndListening
2016-03-22 14:39:26.007 ThaliTest[1510:3587369] THEMultipeerManager stopping peer
2016-03-22 14:39:26.007 ThaliTest[1510:3587369] jxcore: stopAdvertisingAndListening: success
ok 138 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 34. Calling startListeningForAdvertisements twice is NOT an error
,2016-03-22 14:39:26.520 ThaliTest[1510:3587369] jxcore: startListeningForAdvertisements
2016-03-22 14:39:26.520 ThaliTest[1510:3587369] multipeer manager: start client restart timer: 0x14ed3590
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-22 14:39:26.521 ThaliTest[1510:3587369] jxcore: startListeningForAdvertisements: success
,ok 139 Can call startListeningForAdvertisements without error
2016-03-22 14:39:26.523 ThaliTest[1510:3587369] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-22 14:39:26.524 ThaliTest[1510:3587369] jxcore: startListeningForAdvertisements: success
,ok 140 Can call startListeningForAdvertisements twice without error
,# teardown
,2016-03-22 14:39:26.641 ThaliTest[1510:3587369] jxcore: stopListeningForAdvertisements
2016-03-22 14:39:26.641 ThaliTest[1510:3587369] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-22 14:39:26.643 ThaliTest[1510:3587369] jxcore: stopListeningForAdvertisements: success
,ok 141 Should be able to call stopListeningForAdvertisments in teardown
2016-03-22 14:39:26.644 ThaliTest[1510:3587369] jxcore: stopAdvertisingAndListening
,2016-03-22 14:39:26.645 ThaliTest[1510:3587369] THEMultipeerManager stopping peer
2016-03-22 14:39:26.645 ThaliTest[1510:3587369] jxcore: stopAdvertisingAndListening: success
ok 142 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 35. Can call start/stopUpdateAdvertisingAndListening
,2016-03-22 14:39:30.259 ThaliTest[1510:3587369] jxcore: startUpdateAdvertisingAndListening
2016-03-22 14:39:30.260 ThaliTest[1510:3587369] server: starting 46287C39-66D9-4C88-AB7B-A74C4F9B045C:4
2016-03-22 14:39:30.260 ThaliTest[1510:3587369] multipeer m,anager: start client restart timer: 0x14ed3590
2016-03-22 14:39:30.260 ThaliTest[1510:3587369] THEMultipeerManager initialized peer 46287C39-66D9-4C88-AB7B-A74C4F9B045C:4
2016-03-22 14:39:30.261 ThaliTest[1510:3587369] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 143 Can call startUpdateAdvertisingAndListening without error
2016-03-22 14:39:30.264 ThaliTest[1510:3587369] jxcore: stopAdvertisingAndListening
2016-03-22 14:39:30.264 ThaliTest[1510:3587369] THEMultipeerManager stopping peer
2016,-03-22 14:39:30.264 ThaliTest[1510:3587369] multipeer manager: stop client timer
2016-03-22 14:39:30.264 ThaliTest[1510:3587369] jxcore: stopAdvertisingAndListening: success
ok 144 Can call stopAdvertisingAndListening without error
# teardown
,2016-03-22 14:39:31.112 ThaliTest[1510:3587369] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-22 14:39:31.113 ThaliTest[1510:3587369] jxcore: stopListeningForAdvertisements: success
,ok 145 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-22 14:39:31.115 ThaliTest[1510:3587369] jxcore: stopAdvertisingAndListening
2016-03-22 14:39:31.116 ThaliTest[1510:3587369] THEMultipeerManager stopping peer
2016-03-22 14:39:31.116 ThaliTest[1510:3587369] jxcore: stopAdvertisingAndListening: success
ok 146 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 36. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-03-22 14:39:33.294 ThaliTest[1510:3587369] jxcore: startUpdateAdvertisingAndListening
2016-03-22 14:39:33.294 ThaliTest[1510:3587369] server: starting 46287C39-66D9-4C88-AB7B-A74C4F9B045C:5
2016-03-22 14:39:33.294 ThaliTest[1510:3587369] multipeer m,anager: start client restart timer: 0x14ed3590
2016-03-22 14:39:33.295 ThaliTest[1510:3587369] THEMultipeerManager initialized peer 46287C39-66D9-4C88-AB7B-A74C4F9B045C:5
2016-03-22 14:39:33.295 ThaliTest[1510:3587369] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 147 Can call startUpdateAdvertisingAndListening without error
2016-03-22 14:39:33.296 ThaliTest[1510:3587369] jxcore: startUpdateAdvertisingAndListening
2016-03-22 14:39:33.296 ThaliTest[1510:3587369] THEMultipeerManager stopping pee,r
2016-03-22 14:39:33.296 ThaliTest[1510:3587369] multipeer manager: stop client timer
2016-03-22 14:39:33.297 ThaliTest[1510:3587369] server: starting 46287C39-66D9-4C88-AB7B-A74C4F9B045C:6
2016-03-22 14:39:33.297 ThaliTest[1510:3587369] multipeer mana,ger: start client restart timer: 0x14ed3590
2016-03-22 14:39:33.301 ThaliTest[1510:3587369] THEMultipeerManager initialized peer 46287C39-66D9-4C88-AB7B-A74C4F9B045C:6
2016-03-22 14:39:33.301 ThaliTest[1510:3587369] jxcore: startUpdateAdvertisingAndListening: success
ok 148 Can call startUpdateAdvertisingAndListening twice without error
# teardown
,2016-03-22 14:39:33.402 ThaliTest[1510:3587369] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-22 14:39:33.403 ThaliTest[1510:3587369] jxcore: stopListeningForAdvertisements: success
,ok 149 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-22 14:39:33.405 ThaliTest[1510:3587369] jxcore: stopAdvertisingAndListening
2016-03-22 14:39:33.405 ThaliTest[1510:3587369] THEMultipeerManager stopping peer
2016-03-22 14:39:33.406 ThaliTest[1510:3587369] multipeer manager: stop client timer
2016-03-22 14:39:33.406 ThaliTest[1510:3587369] jxcore: stopAdvertisingAndListening: success
ok 150 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 37. peerAvailabilityChange is called
,2016-03-22 14:39:34.220 ThaliTest[1510:3587369] jxcore: startUpdateAdvertisingAndListening
2016-03-22 14:39:34.220 ThaliTest[1510:3587369] server: starting 46287C39-66D9-4C88-AB7B-A74C4F9B045C:7
2016-03-22 14:39:34.221 ThaliTest[1510:3587369] multipeer m,anager: start client restart timer: 0x14ed3590
2016-03-22 14:39:34.221 ThaliTest[1510:3587369] THEMultipeerManager initialized peer 46287C39-66D9-4C88-AB7B-A74C4F9B045C:7
2016-03-22 14:39:34.221 ThaliTest[1510:3587369] jxcore: startUpdateAdvertisingAndListening: success
ok 151 Can call startUpdateAdvertisingAndListeningwithout error
,2016-03-22 14:39:34.223 ThaliTest[1510:3587369] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-22 14:39:34.225 ThaliTest[1510:3587369] jxcore: startListeningForAdvertisements: success
ok 152 Can call startListeningForAdvertisements without error
,2016-03-22 14:39:37.494 ThaliTest[1510:3587186] client: found new peer: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:7
ok 153 peers must be an array
ok 154 peers must not be zero-length
,ok 155 peer must have peerIdentifier
ok 156 peerIdentifier must be a string
ok 157 peer must have peerAvailable
ok 158 peer must have pleaseConnect
,# teardown
,2016-03-22 14:39:37.561 ThaliTest[1510:3587186] client: found new peer: E37C719D-F7A3-448B-B4C9-69FDBA30F0B4:7
,2016-03-22 14:39:38.101 ThaliTest[1510:3587369] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-22 14:39:38.102 ThaliTest[1510:3587369] jxcore: stopListeningForAdvertisements: success
ok 159 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-22 14:39:38.103 ThaliTest[1510:3587369] jxcore: stopAdvertisingAndListening
2016-03-22 14:39:38.104 ThaliTest[1510:3587369] THEMultipeerManager stopping peer
2016-03-22 14:39:38.104 ThaliTest[1510:3587369] multipeer manager: stop client timer
20,16-03-22 14:39:38.104 ThaliTest[1510:3587369] jxcore: stopAdvertisingAndListening: success
ok 160 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 38. Can connect to a remote peer
,2016-03-22 14:40:02.298 ThaliTest[1510:3587369] jxcore: startUpdateAdvertisingAndListening
2016-03-22 14:40:02.299 ThaliTest[1510:3587369] server: starting 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8
2016-03-22 14:40:02.299 ThaliTest[1510:3587369] multipeer m,anager: start client restart timer: 0x14ed3590
2016-03-22 14:40:02.299 ThaliTest[1510:3587369] THEMultipeerManager initialized peer 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8
2016-03-22 14:40:02.300 ThaliTest[1510:3587369] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 161 Can call startUpdateAdvertisingAndListening without error
2016-03-22 14:40:02.301 ThaliTest[1510:3587369] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisin,gActive":true,"discoveryActive":true}
2016-03-22 14:40:02.302 ThaliTest[1510:3587369] jxcore: startListeningForAdvertisements: success
ok 162 Can call startListeningForAdvertisements without error
,2016-03-22 14:40:03.117 ThaliTest[1510:3587186] client: found new peer: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8","pleaseConnect":0}]
,2016-03-22 14:40:03.120 ThaliTest[1510:3587369] jxcore: connect 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
2016-03-22 14:40:03.120 ThaliTest[1510:3587369] client: server will connect
2016-03-22 14:40:03.121 ThaliTest[1510:3587369] client session: reverseConnect
2016-03-22 14:40:03.124 ThaliTest[1510:3587369] client session: stateChange:0->1 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
,2016-03-22 14:40:04.027 ThaliTest[1510:3587850] client session: not connected 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
2016-03-22 14:40:04.028 ThaliTest[1510:3587850] client session: onLinkFailure: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA
2016-03-22 14:40:04.0,28 ThaliTest[1510:3587850] client session: disconnect
2016-03-22 14:40:04.028 ThaliTest[1510:3587850] client session: stateChange:1->0 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
2016-03-22 14:40:04.029 ThaliTest[1510:3587850] client session: no connect callb,ack (server initiated)
,2016-03-22 14:40:04.271 ThaliTest[1510:3587186] client: found new peer: E37C719D-F7A3-448B-B4C9-69FDBA30F0B4:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"E37C719D-F7A3-448B-B4C9-69FDBA30F0B4:8","pleaseConnect":0}]
,2016-03-22 14:40:08.351 ThaliTest[1510:3587186] multipeer session: reset timer
2016-03-22 14:40:08.351 ThaliTest[1510:3587186] server session: connect
2016-03-22 14:40:08.351 ThaliTest[1510:3587186] server session: stateChange:0->1 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
,2016-03-22 14:40:08.357 ThaliTest[1510:3587186] server: accepting invitation 4C3ACECD-4F82-43E7-BE78-A6DF083690BA
,2016-03-22 14:40:11.041 ThaliTest[1510:3587871] server session: p2p link connected
,2016-03-22 14:40:11.048 ThaliTest[1510:3587186] server relay: connected (to port: 50921)
,2016-03-22 14:40:11.050 ThaliTest[1510:3587186] server session: stateChange:1->2 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
2016-03-22 14:40:11.050 ThaliTest[1510:3587186] jxcore: connect: success
,INFO testThaliMobileNative: 
ok 163 Must have listeningPort
,ok 164 listeningPort must be a number
,ok 165 Connection must have clientPort
,ok 166 clientPort must be a number
,ok 167 Connection must have serverPort
,ok 168 serverPort must be a number
,ok 169 reverse connection must have clientPort != 0
,ok 170 reverse connection must have serverPort != 0
,# teardown
,2016-03-22 14:40:22.301 ThaliTest[1510:3587186] multipeer manager: restart client
,2016-03-22 14:40:22.325 ThaliTest[1510:3587186] client: found existing peer: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
2016-03-22 14:40:22.326 ThaliTest[1510:3587186] client: found existing peer: E37C719D-F7A3-448B-B4C9-69FDBA30F0B4:8
,2016-03-22 14:40:42.301 ThaliTest[1510:3587186] multipeer manager: restart client
,2016-03-22 14:40:42.324 ThaliTest[1510:3587186] client: found existing peer: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
2016-03-22 14:40:42.326 ThaliTest[1510:3587186] client: found existing peer: E37C719D-F7A3-448B-B4C9-69FDBA30F0B4:8
,2016-03-22 14:41:02.301 ThaliTest[1510:3587186] multipeer manager: restart client
,2016-03-22 14:41:02.322 ThaliTest[1510:3587186] client: found existing peer: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
2016-03-22 14:41:02.322 ThaliTest[1510:3587186] client: found existing peer: E37C719D-F7A3-448B-B4C9-69FDBA30F0B4:8
,2016-03-22 14:41:09.650 ThaliTest[1510:3587369] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-22 14:41:09.652 ThaliTest[1510:3587369] jxcore: stopListeningForAdvertisements: success
,ok 171 Should be able to call stopListeningForAdvertisments in teardown
2016-03-22 14:41:09.653 ThaliTest[1510:3587369] jxcore: stopAdvertisingAndListening
2016-03-22 14:41:09.653 ThaliTest[1510:3587369] THEMultipeerManager stopping peer
2016-03-22 14:4,1:09.654 ThaliTest[1510:3587369] server session: disconnect
2016-03-22 14:41:09.654 ThaliTest[1510:3587369] server session: stateChange:2->0 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
,2016-03-22 14:41:09.657 ThaliTest[1510:3587186] server relay: socket disconnected
2016-03-22 14:41:09.657 ThaliTest[1510:3587186] server relay: 0x1b31c3d0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2016-03-22 14:41:09.674 ThaliTest[1510:3587369] multipeer manager: stop client timer
2016-03-22 14:41:09.674 ThaliTest[1510:3587369] jxcore: stopAdvertisingAndListening: success
ok 172 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 39. Can shift large amounts of data
,2016-03-22 14:41:11.239 ThaliTest[1510:3587369] jxcore: startUpdateAdvertisingAndListening
,2016-03-22 14:41:11.239 ThaliTest[1510:3587369] server: starting 46287C39-66D9-4C88-AB7B-A74C4F9B045C:9
2016-03-22 14:41:11.240 ThaliTest[1510:3587369] multipeer manager: start client restart timer: 0x14ed3590
2016-03-22 14:41:11.241 ThaliTest[1510:35873,69] THEMultipeerManager initialized peer 46287C39-66D9-4C88-AB7B-A74C4F9B045C:9
2016-03-22 14:41:11.241 ThaliTest[1510:3587369] jxcore: startUpdateAdvertisingAndListening: success
ok 173 Can call startUpdateAdvertisingAndListening without error
2016-03-,22 14:41:11.242 ThaliTest[1510:3587369] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-22 14:41:11.244 ThaliTest[1510:3587369] jxcor,e: startListeningForAdvertisements: success
ok 174 Can call startListeningForAdvertisements without error
,2016-03-22 14:41:12.190 ThaliTest[1510:3587186] client: found new peer: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
2016-03-22 14:41:12.191 ThaliTest[1510:3587369] jxcore: connect 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
2016-03-22 14:41:12.192 ThaliTest[1510:3,587369] client: server will connect
2016-03-22 14:41:12.192 ThaliTest[1510:3587369] client session: reverseConnect
2016-03-22 14:41:12.192 ThaliTest[1510:3587369] client session: stateChange:0->1 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
,2016-03-22 14:41:12.427 ThaliTest[1510:3587186] multipeer session: reset timer
2016-03-22 14:41:12.427 ThaliTest[1510:3587186] server: rejecting invitation from 4C3ACECD-4F82-43E7-BE78-A6DF083690BA due to previous generation (46287C39-66D9-4C88-AB7B-A74C4,F9B045C:9 != 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8)
,2016-03-22 14:41:13.402 ThaliTest[1510:3587186] client: found new peer: E37C719D-F7A3-448B-B4C9-69FDBA30F0B4:8
,2016-03-22 14:41:13.493 ThaliTest[1510:3587997] client session: not connected 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
2016-03-22 14:41:13.493 ThaliTest[1510:3587997] client session: onLinkFailure: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA
2016-03-22 14:41:13.493 ThaliTest[1510:3587997] client session: disconnect
2016-03-22 14:41:13.493 ThaliTest[1510:3587997] client session: stateChange:1->0 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
,2016-03-22 14:41:13.495 ThaliTest[1510:3587997] client session: no connect callback (server initiated)
,2016-03-22 14:41:16.034 ThaliTest[1510:3587186] multipeer session: reset timer
2016-03-22 14:41:16.034 ThaliTest[1510:3587186] server: disconnecting to refresh session (4C3ACECD-4F82-43E7-BE78-A6DF083690BA)
2016-03-22 14:41:16.034 ThaliTest[1510:3587186] server: rejecting invitation from 4C3ACECD-4F82-43E7-BE78-A6DF083690BA due to previous generation (46287C39-66D9-4C88-AB7B-A74C4F9B045C:9 != 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8)
,2016-03-22 14:41:19.717 ThaliTest[1510:3587186] multipeer session: reset timer
2016-03-22 14:41:19.717 ThaliTest[1510:3587186] server: disconnecting to refresh session (4C3ACECD-4F82-43E7-BE78-A6DF083690BA)
2016-03-22 14:41:19.717 ThaliTest[1510:3587186], server: rejecting invitation from 4C3ACECD-4F82-43E7-BE78-A6DF083690BA due to previous generation (46287C39-66D9-4C88-AB7B-A74C4F9B045C:9 != 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8)
,2016-03-22 14:41:22.193 ThaliTest[1510:3587186] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-22 14:41:23.353 ThaliTest[1510:3587186] multipeer session: reset timer
2016-03-22 14:41:23.353 ThaliTest[1510:3587186] server: disconnecting to refresh session (4C3ACECD-4F82-43E7-BE78-A6DF083690BA)
2016-03-22 14:41:23.354 ThaliTest[1510:3587186], server: rejecting invitation from 4C3ACECD-4F82-43E7-BE78-A6DF083690BA due to previous generation (46287C39-66D9-4C88-AB7B-A74C4F9B045C:9 != 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8)
,2016-03-22 14:41:25.200 ThaliTest[1510:3587369] jxcore: connect 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
2016-03-22 14:41:25.201 ThaliTest[1510:3587369] client: server will connect
2016-03-22 14:41:25.201 ThaliTest[1510:3587369] client session: reverseConnect
2016-03-22 14:41:25.202 ThaliTest[1510:3587369] client session: stateChange:0->1 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
,2016-03-22 14:41:25.668 ThaliTest[1510:3587977] client session: not connected 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
2016-03-22 14:41:25.668 ThaliTest[1510:3587977] client session: onLinkFailure: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA
,2016-03-22 14:41:25.669 ThaliTest[1510:3587977] client session: disconnect
,2016-03-22 14:41:25.670 ThaliTest[1510:3587977] client session: stateChange:1->0 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
2016-03-22 14:41:25.671 ThaliTest[1510:3587977] client session: no connect callback (server initiated)
,2016-03-22 14:41:27.053 ThaliTest[1510:3587186] multipeer session: reset timer
2016-03-22 14:41:27.053 ThaliTest[1510:3587186] server: disconnecting to refresh session (4C3ACECD-4F82-43E7-BE78-A6DF083690BA)
2016-03-22 14:41:27.053 ThaliTest[1510:3587186], server: rejecting invitation from 4C3ACECD-4F82-43E7-BE78-A6DF083690BA due to previous generation (46287C39-66D9-4C88-AB7B-A74C4F9B045C:9 != 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8)
,2016-03-22 14:41:30.711 ThaliTest[1510:3587186] multipeer session: reset timer
2016-03-22 14:41:30.711 ThaliTest[1510:3587186] server: disconnecting to refresh session (4C3ACECD-4F82-43E7-BE78-A6DF083690BA)
2016-03-22 14:41:30.712 ThaliTest[1510:3587186], server: rejecting invitation from 4C3ACECD-4F82-43E7-BE78-A6DF083690BA due to previous generation (46287C39-66D9-4C88-AB7B-A74C4F9B045C:9 != 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8)
,2016-03-22 14:41:31.242 ThaliTest[1510:3587186] multipeer manager: restart client
,2016-03-22 14:41:31.264 ThaliTest[1510:3587186] client: found updated peer: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:9
2016-03-22 14:41:31.266 ThaliTest[1510:3587186] client: found updated peer: E37C719D-F7A3-448B-B4C9-69FDBA30F0B4:9
,2016-03-22 14:41:34.342 ThaliTest[1510:3587186] multipeer session: reset timer
2016-03-22 14:41:34.342 ThaliTest[1510:3587186] server: disconnecting to refresh session (4C3ACECD-4F82-43E7-BE78-A6DF083690BA)
2016-03-22 14:41:34.342 ThaliTest[1510:3587186] server: rejecting invitation from 4C3ACECD-4F82-43E7-BE78-A6DF083690BA due to previous generation (46287C39-66D9-4C88-AB7B-A74C4F9B045C:9 != 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8)
,2016-03-22 14:41:35.203 ThaliTest[1510:3587186] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-22 14:41:37.999 ThaliTest[1510:3587186] multipeer session: reset timer
2016-03-22 14:41:37.999 ThaliTest[1510:3587186] server: disconnecting to refresh session (4C3ACECD-4F82-43E7-BE78-A6DF083690BA)
2016-03-22 14:41:37.999 ThaliTest[1510:3587186] server: rejecting invitation from 4C3ACECD-4F82-43E7-BE78-A6DF083690BA due to previous generation (46287C39-66D9-4C88-AB7B-A74C4F9B045C:9 != 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8)
,2016-03-22 14:41:38.211 ThaliTest[1510:3587369] jxcore: connect 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
2016-03-22 14:41:38.211 ThaliTest[1510:3587369] client: server will connect
2016-03-22 14:41:38.212 ThaliTest[1510:3587369] client session: reverseConnect
2016-03-22 14:41:38.213 ThaliTest[1510:3587369] client session: stateChange:0->1 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:9
,2016-03-22 14:41:38.315 ThaliTest[1510:3588026] client session: not connected 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:9
2016-03-22 14:41:38.315 ThaliTest[1510:3588026] client session: onLinkFailure: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA
2016-03-22 14:41:38.3,15 ThaliTest[1510:3588026] client session: disconnect
2016-03-22 14:41:38.315 ThaliTest[1510:3588026] client session: stateChange:1->0 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:9
2016-03-22 14:41:38.316 ThaliTest[1510:3588026] client session: no connect callback (server initiated)
,2016-03-22 14:41:41.726 ThaliTest[1510:3587186] multipeer session: reset timer
2016-03-22 14:41:41.726 ThaliTest[1510:3587186] server: disconnecting to refresh session (4C3ACECD-4F82-43E7-BE78-A6DF083690BA)
2016-03-22 14:41:41.727 ThaliTest[1510:3587186], server: rejecting invitation from 4C3ACECD-4F82-43E7-BE78-A6DF083690BA due to previous generation (46287C39-66D9-4C88-AB7B-A74C4F9B045C:9 != 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8)
,2016-03-22 14:41:44.162 ThaliTest[1510:3587186] client: lost peer: E37C719D-F7A3-448B-B4C9-69FDBA30F0B4
2016-03-22 14:41:44.162 ThaliTest[1510:3587186] client session: onPeerLost: E37C719D-F7A3-448B-B4C9-69FDBA30F0B4
,2016-03-22 14:41:45.397 ThaliTest[1510:3587186] multipeer session: reset timer
2016-03-22 14:41:45.397 ThaliTest[1510:3587186] server: disconnecting to refresh session (4C3ACECD-4F82-43E7-BE78-A6DF083690BA)
2016-03-22 14:41:45.397 ThaliTest[1510:3587186] server: rejecting invitation from 4C3ACECD-4F82-43E7-BE78-A6DF083690BA due to previous generation (46287C39-66D9-4C88-AB7B-A74C4F9B045C:9 != 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8)
,2016-03-22 14:41:48.213 ThaliTest[1510:3587186] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-22 14:41:51.218 ThaliTest[1510:3587369] jxcore: connect 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
2016-03-22 14:41:51.219 ThaliTest[1510:3587369] client: server will connect
2016-03-22 14:41:51.219 ThaliTest[1510:3587369] client session: reverseConnect
2016-03-22 14:41:51.220 ThaliTest[1510:3587369] client session: stateChange:0->1 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:9
,2016-03-22 14:41:51.241 ThaliTest[1510:3587186] multipeer manager: restart client
,2016-03-22 14:41:51.271 ThaliTest[1510:3587186] client: found existing peer: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:9
2016-03-22 14:41:51.272 ThaliTest[1510:3587186] client: found existing peer: E37C719D-F7A3-448B-B4C9-69FDBA30F0B4:9
,2016-03-22 14:42:01.220 ThaliTest[1510:3587186] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-22 14:42:04.226 ThaliTest[1510:3587369] jxcore: connect 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
2016-03-22 14:42:04.226 ThaliTest[1510:3587369] client: already connect(ing/ed) to 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
2016-03-22 14:42:04.227 ThaliTest[1510:3587369] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-22 14:42:07.241 ThaliTest[1510:3587369] jxcore: connect 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
2016-03-22 14:42:07.242 ThaliTest[1510:3587369] client: already connect(ing/ed) to 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
2016-03-22 14:42:07.242 Thali,Test[1510:3587369] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-22 14:42:10.253 ThaliTest[1510:3587369] jxcore: connect 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
2016-03-22 14:42:10.254 ThaliTest[1510:3587369] client: already connect(ing/ed) to 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
2016-03-22 14:42:10.255 Thali,Test[1510:3587369] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-22 14:42:11.242 ThaliTest[1510:3587186] multipeer manager: restart client
,2016-03-22 14:42:11.263 ThaliTest[1510:3587186] client: found existing peer: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:9
2016-03-22 14:42:11.264 ThaliTest[1510:3587186] client: found existing peer: E37C719D-F7A3-448B-B4C9-69FDBA30F0B4:9
,2016-03-22 14:42:13.268 ThaliTest[1510:3587369] jxcore: connect 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
2016-03-22 14:42:13.268 ThaliTest[1510:3587369] client: already connect(ing/ed) to 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
2016-03-22 14:42:13.269 ThaliTest[1510:3587369] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-22 14:42:16.282 ThaliTest[1510:3587369] jxcore: connect 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
2016-03-22 14:42:16.282 ThaliTest[1510:3587369] client: already connect(ing/ed) to 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
2016-03-22 14:42:16.283 Thali,Test[1510:3587369] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-22 14:42:19.297 ThaliTest[1510:3587369] jxcore: connect 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
2016-03-22 14:42:19.298 ThaliTest[1510:3587369] client: already connect(ing/ed) to 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
2016-03-22 14:42:19.298 Thali,Test[1510:3587369] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,WARN testThaliMobileNative: Too many connect retries!
,not ok 175 Connect failed!
  ---
,    operator: fail
,  ...
,# teardown
,2016-03-22 14:42:19.538 ThaliTest[1510:3587369] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-22 14:42:19.539 ThaliTest[1510:3587369] jxcore: stopListeningForAdvertisements: success
,ok 176 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-22 14:42:19.540 ThaliTest[1510:3587369] jxcore: stopAdvertisingAndListening
2016-03-22 14:42:19.541 ThaliTest[1510:3587369] THEMultipeerManager stopping peer
2016-03-22 14:42:19.541 ThaliTest[1510:3587369] client session: disconnect
2016-03-22 1,4:42:19.541 ThaliTest[1510:3587369] client session: stateChange:1->0 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:9
2016-03-22 14:42:19.542 ThaliTest[1510:3587369] multipeer manager: stop client timer
2016-03-22 14:42:19.542 ThaliTest[1510:3587369] jxcore: stopAdvertisingAndListening: success
,ok 177 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2016-03-22 14:42:20.421 ThaliTest[1510:3587369] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-22 14:42:20.421 ThaliTest[1510:3587369] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-22 14:42:20.422 ThaliTest[1510:3587369] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-22 14:42:20.423 ThaliTest[1510:3587369] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 40. #startListeningForAdvertisements should fail if start not called
,ok 178 specific error should be returned
,# teardown
,# setup
,2016-03-22 14:42:22.269 ThaliTest[1510:3587369] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-22 14:42:22.269 ThaliTest[1510:3587369] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-22 14:42:22.270 ThaliTest[1510:3,587369] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-22 14:42:22.271 ThaliTest[1510:3587369] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 41. #startUpdateAdvertisingAndListening should fail if start not called
,ok 179 specific error should be returned
,# teardown
,# setup
,2016-03-22 14:42:22.927 ThaliTest[1510:3587369] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-22 14:42:22.928 ThaliTest[1510:3587369] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-22 14:42:22.928 ThaliTest[1510:3587369] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-22 14:42:22.930 ThaliTest[1510:3587369] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 42. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50933
,2016-03-22 14:42:23.063 ThaliTest[1510:3587369] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-22 14:42:23.064 ThaliTest[1510:3587369] jxcore: stopListeningForAdvertisements: success
,ok 180 no errors
,2016-03-22 14:42:23.066 ThaliTest[1510:3587369] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-22 14:42:23.067 ThaliTest[1510:3587369] jxcore: stopListeningForAdvertisements: success
,ok 181 still no errors
,# teardown
,2016-03-22 14:42:23.468 ThaliTest[1510:3587369] jxcore: stopAdvertisingAndListening
2016-03-22 14:42:23.468 ThaliTest[1510:3587369] THEMultipeerManager stopping peer
2016-03-22 14:42:23.468 ThaliTest[1510:3587369] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-22 14:42:23.469 ThaliTest[1510:3587369] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-22 14:42:23.470 ThaliTest[1510,:3587369] jxcore: stopListeningForAdvertisements: success
,# setup
,2016-03-22 14:42:23.813 ThaliTest[1510:3587369] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-22 14:42:23.814 ThaliTest[1510:3587369] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-22 14:42:23.814 ThaliTest[1510:3587369] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-22 14:42:23.815 ThaliTest[1510:3587369] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 43. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50935
,2016-03-22 14:42:23.984 ThaliTest[1510:3587369] jxcore: startListeningForAdvertisements
,2016-03-22 14:42:23.985 ThaliTest[1510:3587369] multipeer manager: start client restart timer: 0x14ed3590
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-22 14:42:23.994 ThaliTest[1510:3587369] jxcore: startListeningForAdvertisements: success
,2016-03-22 14:42:24.003 ThaliTest[1510:3587186] client: found new peer: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:9
ok 182 no errors
2016-03-22 14:42:24.005 ThaliTest[1510:3587369] jxcore: startListeningForAdvertisements

```
