#### Test 657450204f13c43_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/657450204f13c43/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/24598CD8-0A44-4449-8F56-54C57EA5F8D3/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/24598CD8-0A44-4449-8F56-54C57EA5F8D3/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/657450204f13c43/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/657450204f13c43/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/1E6CA46F-BEAC-4798-ABB0-FC80CBB99258/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51985"
,(lldb)     command script import "/tmp/24598CD8-0A44-4449-8F56-54C57EA5F8D3/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-04-08 09:29:35.359 ThaliTest[606:1017168] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/70FC0174-21B2-415B-9E86-F19ADBF270D7/Library/Cookies/Cookies.binarycookies
,2016-04-08 09:29:35.726 ThaliTest[606:1017168] Apache Cordova native platform version 4.1.1 is starting.
,2016-04-08 09:29:35.727 ThaliTest[606:1017168] Multi-tasking -> Device: YES, App: YES
,2016-04-08 09:29:35.746 ThaliTest[606:1017168] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-04-08 09:29:37.565 ThaliTest[606:1017168] Using UIWebView
,2016-04-08 09:29:37.572 ThaliTest[606:1017168] [CDVTimer][handleopenurl] 0.406981ms
,2016-04-08 09:29:37.579 ThaliTest[606:1017168] [CDVTimer][intentandnavigationfilter] 6.955028ms
,2016-04-08 09:29:37.580 ThaliTest[606:1017168] [CDVTimer][gesturehandler] 0.356972ms
2016-04-08 09:29:37.581 ThaliTest[606:1017168] [CDVTimer][TotalPluginStartup] 9.460986ms
,2016-04-08 09:29:43.913 ThaliTest[606:1017168] Resetting plugins due to page load.
,2016-04-08 09:29:47.184 ThaliTest[606:1017168] Finished load of: file:///var/mobile/Containers/Bundle/Application/1E6CA46F-BEAC-4798-ABB0-FC80CBB99258/ThaliTest.app/www/index.html
,2016-04-08 09:29:47.386 ThaliTest[606:1017168] JXcore Cordova plugin initializing
,2016-04-08 09:29:47.387 ThaliTest[606:1017360] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-04-08 09:29:53.847 ThaliTest[606:1017360] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-04-08 09:29:53.847 ThaliTest[606:1017360] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-04-08 09:29:53.847 ThaliTest[606:1017360] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-04-08 09:29:53.849 ThaliTest[606:1017360] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-IpadAir2-1
,WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1E6CA46F-BEAC-4798-ABB0-FC80CBB99258/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1E6CA46F-BEAC-4798-ABB0-FC80CBB99258/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1E6CA46F-BEAC-4798-ABB0-FC80CBB99258/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1E6CA46F-BEAC-4798-ABB0-FC80CBB99258/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1E6CA46F-BEAC-4798-ABB0-FC80CBB99258/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1E6CA46F-BEAC-4798-ABB0-FC80CBB99258/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1E6CA46F-BEAC-4798-ABB0-FC80CBB99258/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1E6CA46F-BEAC-4798-ABB0-FC80CBB99258/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1E6CA46F-BEAC-4798-ABB0-FC80CBB99258/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1E6CA46F-BEAC-4798-ABB0-FC80CBB99258/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1E6CA46F-BEAC-4798-ABB0-FC80CBB99258/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1E6CA46F-BEAC-4798-ABB0-FC80CBB99258/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1E6CA46F-BEAC-4798-ABB0-FC80CBB99258/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1E6CA46F-BEAC-4798-ABB0-FC80CBB99258/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1E6CA46F-BEAC-4798-ABB0-FC80CBB99258/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1E6CA46F-BEAC-4798-ABB0-FC80CBB99258/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1E6CA46F-BEAC-4798-ABB0-FC80CBB99258/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1E6CA46F-BEAC-4798-ABB0-FC80CBB99258/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1E6CA46F-BEAC-4798-ABB0-FC80CBB99258/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1E6CA46F-BEAC-4798-ABB0-FC80CBB99258/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1E6CA46F-BEAC-4798-ABB0-FC80CBB99258/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1E6CA46F-BEAC-4798-ABB0-FC80CBB99258/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-04-08 09:29:59.660 ThaliTest[606:1017168] THREAD WARNING: ['JXcore'] took '5535.740234' ms. Plugin should use a background thread.
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 52178
,ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 52180
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
,DEBUG createNativeListener: listening 52183
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
,DEBUG createNativeListener: listening 52187
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
,DEBUG createNativeListener: listening 52192
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
,DEBUG createNativeListener: listening 52196
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
,DEBUG createNativeListener: listening 52200
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
,DEBUG createNativeListener: listening 52204
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
,DEBUG createNativeListener: listening 52208
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
,DEBUG createNativeListener: listening 52260
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
,DEBUG createNativeListener: listening 52264
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
,[{"uuid":"6bac6588-a6e4-44a8-b2ac-e4b77439f88c","data":"custom data"},{"uuid":"281113d3-0e97-4786-a620-6936cd6b2a37","data":"custom data"},{"uuid":"981e6d0f-5d06-4f4c-bdce-22c4d8fdd816","data":"custom data"},{"uuid":"e825a612-6c5c-4d54-afc9-816449e93798","data":"custom data"}]
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
,DEBUG createNativeListener: listening 52274
,2016-04-08 09:32:23.766 ThaliTest[606:1017360] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-08 09:32:23.768 ThaliTest[606:1017360] jxcore: stopListeningForAdvertisements: success
,ok 91 error should be null
,ok 92 error should be null
,2016-04-08 09:32:23.772 ThaliTest[606:1017360] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-08 09:32:23.773 ThaliTest[606:1017360] jxcore: stopListeningForAdvertisements: success
,ok 93 error should be null
,ok 94 error should be null
,# teardown
,2016-04-08 09:32:23.851 ThaliTest[606:1017360] jxcore: stopAdvertisingAndListening
,2016-04-08 09:32:23.851 ThaliTest[606:1017360] THEMultipeerManager stopping peer
,2016-04-08 09:32:23.852 ThaliTest[606:1017360] jxcore: stopAdvertisingAndListening: success
,2016-04-08 09:32:23.853 ThaliTest[606:1017360] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-08 09:32:23.856 ThaliTest[606:1017360] jxcore: stopListeningForAdvertisements: success
,ok 95 error should be null
,ok 96 error should be null
,# setup
,# 26. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 52276
,2016-04-08 09:32:24.031 ThaliTest[606:1017360] jxcore: startListeningForAdvertisements
,2016-04-08 09:32:24.033 ThaliTest[606:1017360] multipeer manager: start client restart timer: 0x15e5e0c0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-08 09:32:24.035 ThaliTest[606:1017360] jxcore: startListeningForAdvertisements: success
,ok 97 error should be null
,ok 98 error should be null
,2016-04-08 09:32:24.061 ThaliTest[606:1017360] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-08 09:32:24.064 ThaliTest[606:1017360] jxcore: startListeningForAdvertisements: success
,ok 99 error should be null
,ok 100 error should be null
,# teardown
,2016-04-08 09:32:24.330 ThaliTest[606:1017360] jxcore: stopAdvertisingAndListening
,2016-04-08 09:32:24.330 ThaliTest[606:1017360] THEMultipeerManager stopping peer
,2016-04-08 09:32:24.331 ThaliTest[606:1017360] jxcore: stopAdvertisingAndListening: success
,2016-04-08 09:32:24.332 ThaliTest[606:1017360] jxcore: stopListeningForAdvertisements
,2016-04-08 09:32:24.333 ThaliTest[606:1017360] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-08 09:32:24.336 ThaliTest[606:1017360] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 101 error should be null
,ok 102 error should be null
,# setup
,# 27. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 52278
,2016-04-08 09:32:24.821 ThaliTest[606:1017360] jxcore: startUpdateAdvertisingAndListening
,2016-04-08 09:32:24.822 ThaliTest[606:1017360] server: starting C76D48A2-6720-4997-B51C-ADA808AA0AC0:1
,2016-04-08 09:32:24.824 ThaliTest[606:1017360] multipeer manager: start client restart timer: 0x15e5e0c0
2016-04-08 09:32:24.824 ThaliTest[606:1017360] THEMultipeerManager initialized peer C76D48A2-6720-4997-B51C-ADA808AA0AC0:1
2016-04-08 09:32:24.825 Th,aliTest[606:1017360] jxcore: startUpdateAdvertisingAndListening: success
,ok 103 error should be null
,ok 104 error should be null
,2016-04-08 09:32:24.863 ThaliTest[606:1017360] jxcore: startUpdateAdvertisingAndListening
,2016-04-08 09:32:24.864 ThaliTest[606:1017360] THEMultipeerManager stopping peer
,2016-04-08 09:32:24.865 ThaliTest[606:1017360] multipeer manager: stop client timer
,2016-04-08 09:32:24.868 ThaliTest[606:1017360] server: starting C76D48A2-6720-4997-B51C-ADA808AA0AC0:2
,2016-04-08 09:32:24.870 ThaliTest[606:1017360] multipeer manager: start client restart timer: 0x15e5e0c0
2016-04-08 09:32:24.870 ThaliTest[606:1017360] THEMultipeerManager initialized peer C76D48A2-6720-4997-B51C-ADA808AA0AC0:2
2016-04-08 09:32:24.870 Th,aliTest[606:1017360] jxcore: startUpdateAdvertisingAndListening: success
,ok 105 error should be null
,ok 106 error should be null
,# teardown
,2016-04-08 09:32:24.971 ThaliTest[606:1017360] jxcore: stopAdvertisingAndListening
,2016-04-08 09:32:24.971 ThaliTest[606:1017360] THEMultipeerManager stopping peer
,2016-04-08 09:32:24.972 ThaliTest[606:1017360] multipeer manager: stop client timer
,2016-04-08 09:32:24.973 ThaliTest[606:1017360] jxcore: stopAdvertisingAndListening: success
,2016-04-08 09:32:24.975 ThaliTest[606:1017360] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-08 09:32:24.979 ThaliTest[606:1017360] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 107 error should be null
,ok 108 error should be null
,# setup
,# 28. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 52283
,2016-04-08 09:32:30.734 ThaliTest[606:1017360] jxcore: stopAdvertisingAndListening
,2016-04-08 09:32:30.734 ThaliTest[606:1017360] THEMultipeerManager stopping peer
,2016-04-08 09:32:30.735 ThaliTest[606:1017360] jxcore: stopAdvertisingAndListening: success
,ok 109 error should be null
,ok 110 error should be null
,2016-04-08 09:32:30.741 ThaliTest[606:1017360] jxcore: stopAdvertisingAndListening
,2016-04-08 09:32:30.742 ThaliTest[606:1017360] THEMultipeerManager stopping peer
,2016-04-08 09:32:30.742 ThaliTest[606:1017360] jxcore: stopAdvertisingAndListening: success
,ok 111 error should be null
,ok 112 error should be null
,# teardown
,2016-04-08 09:32:55.408 ThaliTest[606:1017360] jxcore: stopAdvertisingAndListening
,2016-04-08 09:32:55.408 ThaliTest[606:1017360] THEMultipeerManager stopping peer
,2016-04-08 09:32:55.409 ThaliTest[606:1017360] jxcore: stopAdvertisingAndListening: success
,2016-04-08 09:32:55.410 ThaliTest[606:1017360] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-08 09:32:55.413 ThaliTest[606:1017360] jxcore: stopListeningForAdvertisements: success
,ok 113 error should be null
,ok 114 error should be null
,# setup
,# 29. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 52285
,ok 115 first call should succeed
,ok 116 first call should succeed
,ok 117 specific error should be returned
,# teardown
,2016-04-08 09:33:28.155 ThaliTest[606:1017360] jxcore: stopAdvertisingAndListening
2016-04-08 09:33:28.155 ThaliTest[606:1017360] THEMultipeerManager stopping peer
,2016-04-08 09:33:28.156 ThaliTest[606:1017360] jxcore: stopAdvertisingAndListening: success
,2016-04-08 09:33:28.157 ThaliTest[606:1017360] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-08 09:33:28.159 ThaliTest[606:1017360] jxcore: stopListeningForAdvertisements: success
,ok 118 error should be null
,ok 119 error should be null
,# setup
,# 30. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 52287
,2016-04-08 09:33:28.408 ThaliTest[606:1017360] jxcore: startListeningForAdvertisements
,2016-04-08 09:33:28.409 ThaliTest[606:1017360] multipeer manager: start client restart timer: 0x15e5e0c0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-08 09:33:28.412 ThaliTest[606:1017360] jxcore: startListeningForAdvertisements: success
,2016-04-08 09:33:28.437 ThaliTest[606:1017360] jxcore: startUpdateAdvertisingAndListening
,2016-04-08 09:33:28.438 ThaliTest[606:1017360] server: starting C76D48A2-6720-4997-B51C-ADA808AA0AC0:3
,2016-04-08 09:33:28.439 ThaliTest[606:1017360] THEMultipeerManager initialized peer C76D48A2-6720-4997-B51C-ADA808AA0AC0:3
2016-04-08 09:33:28.440 ThaliTest[606:1017360] jxcore: startUpdateAdvertisingAndListening: success
,ok 120 called only once
,ok 121 discovery state matches
,ok 122 advertising state matches
,# teardown
,2016-04-08 09:33:28.679 ThaliTest[606:1017360] jxcore: stopAdvertisingAndListening
,2016-04-08 09:33:28.680 ThaliTest[606:1017360] THEMultipeerManager stopping peer
,2016-04-08 09:33:28.681 ThaliTest[606:1017360] jxcore: stopAdvertisingAndListening: success
2016-04-08 09:33:28.682 ThaliTest[606:1017360] jxcore: stopListeningForAdvertisements
,2016-04-08 09:33:28.683 ThaliTest[606:1017360] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-08 09:33:28.687 ThaliTest[606:1017360] jxcore: stopListeningForAdvertisements: success
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
,2016-04-08 09:33:54.394 ThaliTest[606:1017360] jxcore: startListeningForAdvertisements
,2016-04-08 09:33:54.395 ThaliTest[606:1017360] multipeer manager: start client restart timer: 0x15e5e0c0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-08 09:33:54.399 ThaliTest[606:1017360] jxcore: startListeningForAdvertisements: success
ok 138 Can call startListeningForAdvertisements without error
2016-04-08 09:33:54.403 ThaliTest[606:1017360] jxcore: stopListeningForAdvertisements
,2016-04-08 09:33:54.403 ThaliTest[606:1017360] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-08 09:33:54.407 ThaliTest[606:1017360] jxcore: stopListeningForAdvertisements: success
,ok 139 Can call stopListeningForAdvertisements without error
,# teardown
,2016-04-08 09:33:54.665 ThaliTest[606:1017360] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-08 09:33:54.667 ThaliTest[606:1017360] jxcore: stopListeningForAdvertisements: success
,ok 140 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-08 09:33:54.670 ThaliTest[606:1017360] jxcore: stopAdvertisingAndListening
,2016-04-08 09:33:54.670 ThaliTest[606:1017360] THEMultipeerManager stopping peer
,2016-04-08 09:33:54.671 ThaliTest[606:1017360] jxcore: stopAdvertisingAndListening: success
,ok 141 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 35. Calling startListeningForAdvertisements twice is NOT an error
,2016-04-08 09:34:14.332 ThaliTest[606:1017360] jxcore: startListeningForAdvertisements
,2016-04-08 09:34:14.333 ThaliTest[606:1017360] multipeer manager: start client restart timer: 0x15e5e0c0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-08 09:34:14.336 ThaliTest[606:1017360] jxcore: startListeningForAdvertisements: success
ok 142 Can call startListeningForAdvertisements without error
2016-04-08 09:34:14.341 ThaliTest[606:1017360] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-08 09:34:14.343 ThaliTest[606:1017360] jxcore: startListeningForAdvertisements: success
,ok 143 Can call startListeningForAdvertisements twice without error
,# teardown
,2016-04-08 09:34:20.459 ThaliTest[606:1017360] jxcore: stopListeningForAdvertisements
,2016-04-08 09:34:20.460 ThaliTest[606:1017360] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-08 09:34:20.463 ThaliTest[606:1017360] jxcore: stopListeningForAdvertisements: success
,ok 144 Should be able to call stopListeningForAdvertisements in teardown
2016-04-08 09:34:20.466 ThaliTest[606:1017360] jxcore: stopAdvertisingAndListening
2016-04-08 09:34:20.467 ThaliTest[606:1017360] THEMultipeerManager stopping peer
,2016-04-08 09:34:20.467 ThaliTest[606:1017360] jxcore: stopAdvertisingAndListening: success
,ok 145 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 36. Calling stopListeningForAdvertisements without calling start is NOT an error
,2016-04-08 09:34:53.671 ThaliTest[606:1017360] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-08 09:34:53.674 ThaliTest[606:1017360] jxcore: stopListeningForAdvertisements: success
,ok 146 Can call stopListeningForAdvertisements without error
,2016-04-08 09:34:53.676 ThaliTest[606:1017360] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-08 09:34:53.679 ThaliTest[606:1017360] jxcore: stopListeningForAdvertisements: success
,ok 147 Can call stopListeningForAdvertisements without error
,# teardown
,2016-04-08 09:34:53.870 ThaliTest[606:1017360] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-08 09:34:53.872 ThaliTest[606:1017360] jxcore: stopListeningForAdvertisements: success
,ok 148 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-08 09:34:53.875 ThaliTest[606:1017360] jxcore: stopAdvertisingAndListening
,2016-04-08 09:34:53.875 ThaliTest[606:1017360] THEMultipeerManager stopping peer
,2016-04-08 09:34:53.876 ThaliTest[606:1017360] jxcore: stopAdvertisingAndListening: success
,ok 149 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 37. Can call start/stopUpdateAdvertisingAndListening
,2016-04-08 09:34:54.117 ThaliTest[606:1017360] jxcore: startUpdateAdvertisingAndListening
,2016-04-08 09:34:54.118 ThaliTest[606:1017360] server: starting C76D48A2-6720-4997-B51C-ADA808AA0AC0:4
,2016-04-08 09:34:54.119 ThaliTest[606:1017360] multipeer manager: start client restart timer: 0x15e5e0c0
2016-04-08 09:34:54.120 ThaliTest[606:1017360] THEMultipeerManager initialized peer C76D48A2-6720-4997-B51C-ADA808AA0AC0:4
2016-04-08 09:34:54.120 ThaliTest[606:1017360] jxcore: startUpdateAdvertisingAndListening: success
,ok 150 Can call startUpdateAdvertisingAndListening without error
,2016-04-08 09:34:54.130 ThaliTest[606:1017360] jxcore: stopAdvertisingAndListening
2016-04-08 09:34:54.131 ThaliTest[606:1017360] THEMultipeerManager stopping peer
2016-04-08 09:34:54.131 ThaliTest[606:1017360] multipeer manager: stop client timer
,2016-04-08 09:34:54.131 ThaliTest[606:1017360] jxcore: stopAdvertisingAndListening: success
,ok 151 Can call stopAdvertisingAndListening without error
,# teardown
,2016-04-08 09:34:54.208 ThaliTest[606:1017360] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-08 09:34:54.210 ThaliTest[606:1017360] jxcore: stopListeningForAdvertisements: success
,ok 152 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-08 09:34:54.213 ThaliTest[606:1017360] jxcore: stopAdvertisingAndListening
,2016-04-08 09:34:54.213 ThaliTest[606:1017360] THEMultipeerManager stopping peer
,2016-04-08 09:34:54.214 ThaliTest[606:1017360] jxcore: stopAdvertisingAndListening: success
,ok 153 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-04-08 09:34:54.542 ThaliTest[606:1017360] jxcore: startUpdateAdvertisingAndListening
,2016-04-08 09:34:54.543 ThaliTest[606:1017360] server: starting C76D48A2-6720-4997-B51C-ADA808AA0AC0:5
,2016-04-08 09:34:54.544 ThaliTest[606:1017360] multipeer manager: start client restart timer: 0x15e5e0c0
2016-04-08 09:34:54.545 ThaliTest[606:1017360] THEMultipeerManager initialized peer C76D48A2-6720-4997-B51C-ADA808AA0AC0:5
,2016-04-08 09:34:54.546 ThaliTest[606:1017360] jxcore: startUpdateAdvertisingAndListening: success
,ok 154 Can call startUpdateAdvertisingAndListening without error
2016-04-08 09:34:54.548 ThaliTest[606:1017360] jxcore: startUpdateAdvertisingAndListening
,2016-04-08 09:34:54.549 ThaliTest[606:1017360] THEMultipeerManager stopping peer
2016-04-08 09:34:54.550 ThaliTest[606:1017360] multipeer manager: stop client timer
2016-04-08 09:34:54.550 ThaliTest[606:1017360] server: starting C76D48A2-6720-4997-B51C-A,DA808AA0AC0:6
2016-04-08 09:34:54.551 ThaliTest[606:1017360] multipeer manager: start client restart timer: 0x15e5e0c0
2016-04-08 09:34:54.551 ThaliTest[606:1017360] THEMultipeerManager initialized peer C76D48A2-6720-4997-B51C-ADA808AA0AC0:6
2016-04-08 ,09:34:54.551 ThaliTest[606:1017360] jxcore: startUpdateAdvertisingAndListening: success
,ok 155 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,2016-04-08 09:34:54.667 ThaliTest[606:1017360] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-08 09:34:54.669 ThaliTest[606:1017360] jxcore: stopListeningForAdvertisements: success
,ok 156 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-08 09:34:54.671 ThaliTest[606:1017360] jxcore: stopAdvertisingAndListening
,2016-04-08 09:34:54.672 ThaliTest[606:1017360] THEMultipeerManager stopping peer
,2016-04-08 09:34:54.672 ThaliTest[606:1017360] multipeer manager: stop client timer
2016-04-08 09:34:54.673 ThaliTest[606:1017360] jxcore: stopAdvertisingAndListening: success
,ok 157 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,2016-04-08 09:34:55.667 ThaliTest[606:1017360] jxcore: stopAdvertisingAndListening
,2016-04-08 09:34:55.667 ThaliTest[606:1017360] THEMultipeerManager stopping peer
,2016-04-08 09:34:55.668 ThaliTest[606:1017360] jxcore: stopAdvertisingAndListening: success
,ok 158 Can call startUpdateAdvertisingAndListening without error
,2016-04-08 09:34:55.670 ThaliTest[606:1017360] jxcore: stopAdvertisingAndListening
,2016-04-08 09:34:55.671 ThaliTest[606:1017360] THEMultipeerManager stopping peer
,2016-04-08 09:34:55.671 ThaliTest[606:1017360] jxcore: stopAdvertisingAndListening: success
,ok 159 Can call stopAdvertisingAndListening without error
,# teardown
,2016-04-08 09:34:58.887 ThaliTest[606:1017360] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-08 09:34:58.889 ThaliTest[606:1017360] jxcore: stopListeningForAdvertisements: success
,ok 160 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-08 09:34:58.892 ThaliTest[606:1017360] jxcore: stopAdvertisingAndListening
,2016-04-08 09:34:58.892 ThaliTest[606:1017360] THEMultipeerManager stopping peer
,2016-04-08 09:34:58.893 ThaliTest[606:1017360] jxcore: stopAdvertisingAndListening: success
,ok 161 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 40. cannot call connect when start listening for advertisements is not active
,2016-04-08 09:35:17.783 ThaliTest[606:1017360] jxcore: connect foo
,2016-04-08 09:35:17.784 ThaliTest[606:1017360] jxcore: connect: fail: Start browsing first
,not ok 162 got right error
,  ---
,    operator: equal
,    expected: 'startListeningForAdvertisements is not active'
,    actual:   'Start browsing first'
,  ...
,# teardown
,2016-04-08 09:35:17.855 ThaliTest[606:1017360] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-08 09:35:17.858 ThaliTest[606:1017360] jxcore: stopListeningForAdvertisements: success
,ok 163 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-08 09:35:17.860 ThaliTest[606:1017360] jxcore: stopAdvertisingAndListening
,2016-04-08 09:35:17.861 ThaliTest[606:1017360] THEMultipeerManager stopping peer
,2016-04-08 09:35:17.861 ThaliTest[606:1017360] jxcore: stopAdvertisingAndListening: success
,ok 164 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 41. peerAvailabilityChange is called
,2016-04-08 09:35:18.026 ThaliTest[606:1017360] jxcore: startUpdateAdvertisingAndListening
,2016-04-08 09:35:18.027 ThaliTest[606:1017360] server: starting C76D48A2-6720-4997-B51C-ADA808AA0AC0:7
,2016-04-08 09:35:18.028 ThaliTest[606:1017360] multipeer manager: start client restart timer: 0x15e5e0c0
2016-04-08 09:35:18.028 ThaliTest[606:1017360] THEMultipeerManager initialized peer C76D48A2-6720-4997-B51C-ADA808AA0AC0:7
,2016-04-08 09:35:18.029 ThaliTest[606:1017360] jxcore: startUpdateAdvertisingAndListening: success
,ok 165 Can call startUpdateAdvertisingAndListeningwithout error
,2016-04-08 09:35:18.032 ThaliTest[606:1017360] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-04-08 09:35:18.034 ThaliTest[606:1017360], jxcore: startListeningForAdvertisements: success
ok 166 Can call startListeningForAdvertisements without error
,2016-04-08 09:35:19.050 ThaliTest[606:1017168] client: found new peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:7
,ok 167 peers must be an array
,ok 168 peers must not be zero-length
,ok 169 peer must have peerIdentifier
,ok 170 peerIdentifier must be a string
,ok 171 peer must have peerAvailable
,ok 172 peer must have pleaseConnect
,2016-04-08 09:35:19.073 ThaliTest[606:1017168] client: found new peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:7
2016-04-08 09:35:19.075 ThaliTest[606:1017168] client: found new peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:7
,# teardown
,2016-04-08 09:35:21.681 ThaliTest[606:1017360] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-08 09:35:21.683 ThaliTest[606:1017360] jxcore: stopListeningForAdvertisements: success
,ok 173 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-08 09:35:21.686 ThaliTest[606:1017360] jxcore: stopAdvertisingAndListening
,2016-04-08 09:35:21.687 ThaliTest[606:1017360] THEMultipeerManager stopping peer
,2016-04-08 09:35:21.688 ThaliTest[606:1017360] multipeer manager: stop client timer
2016-04-08 09:35:21.689 ThaliTest[606:1017360] jxcore: stopAdvertisingAndListening: success
,ok 174 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 42. Can connect to a remote peer
,2016-04-08 09:35:42.635 ThaliTest[606:1017360] jxcore: startUpdateAdvertisingAndListening
,2016-04-08 09:35:42.636 ThaliTest[606:1017360] server: starting C76D48A2-6720-4997-B51C-ADA808AA0AC0:8
,2016-04-08 09:35:42.637 ThaliTest[606:1017360] multipeer manager: start client restart timer: 0x15e5e0c0
2016-04-08 09:35:42.638 ThaliTest[606:1017360] THEMultipeerManager initialized peer C76D48A2-6720-4997-B51C-ADA808AA0AC0:8
2016-04-08 09:35:42.638 Th,aliTest[606:1017360] jxcore: startUpdateAdvertisingAndListening: success
,ok 175 Can call startUpdateAdvertisingAndListening without error
,2016-04-08 09:35:42.641 ThaliTest[606:1017360] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
,2016-04-08 09:35:42.646 ThaliTest[606:1017360] jxcore: startListeningForAdvertisements: success
ok 176 Can call startListeningForAdvertisements without error
,2016-04-08 09:35:44.742 ThaliTest[606:1017168] client: found new peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:8
2016-04-08 09:35:44.743 ThaliTest[606:1017168] client: found new peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:7
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"5401A4DE-2020-4411-800F-72E067EDFF0D:8","pleaseConnect":0}]
,2016-04-08 09:35:44.747 ThaliTest[606:1017360] jxcore: connect 5401A4DE-2020-4411-800F-72E067EDFF0D:8
,2016-04-08 09:35:44.748 ThaliTest[606:1017360] client session: connect
,2016-04-08 09:35:44.749 ThaliTest[606:1017360] client session: stateChange:0->1 5401A4DE-2020-4411-800F-72E067EDFF0D:8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:7","pleaseConnect":0}]
,2016-04-08 09:35:45.155 ThaliTest[606:1017168] client: found new peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:7
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"B29A2A64-B1EF-4545-BC19-F0DD94E05227:7","pleaseConnect":0}]
,2016-04-08 09:35:53.332 ThaliTest[606:1018294] client session: p2p link connected
,2016-04-08 09:35:53.338 ThaliTest[606:1018294] client session: stateChange:1->2 5401A4DE-2020-4411-800F-72E067EDFF0D:8
,2016-04-08 09:35:53.338 ThaliTest[606:1018294] client session: fireConnectCallback: 5401A4DE-2020-4411-800F-72E067EDFF0D
,2016-04-08 09:35:53.339 ThaliTest[606:1018294] jxcore: connect: success
,INFO testThaliMobileNative: 
,ok 177 Must have listeningPort
,ok 178 listeningPort must be a number
,ok 179 Connection must have clientPort
,ok 180 clientPort must be a number
,ok 181 Connection must have serverPort
,ok 182 serverPort must be a number
,ok 183 forward connection must have clientPort == 0
,ok 184 forward connection must have serverPort == 0
,# teardown
,2016-04-08 09:36:02.639 ThaliTest[606:1017168] multipeer manager: restart client
,2016-04-08 09:36:02.658 ThaliTest[606:1017168] client: found updated peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8
2016-04-08 09:36:02.659 ThaliTest[606:1017168] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:8
,2016-04-08 09:36:02.660 ThaliTest[606:1017168] client: found updated peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8","pleaseConnect":0}]
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"B29A2A64-B1EF-4545-BC19-F0DD94E05227:8","pleaseConnect":0}]
,2016-04-08 09:36:15.099 ThaliTest[606:1017360] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-08 09:36:15.101 ThaliTest[606:1017360] jxcore: stopListeningForAdvertisements: success
,ok 185 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-08 09:36:15.104 ThaliTest[606:1017360] jxcore: stopAdvertisingAndListening
,2016-04-08 09:36:15.104 ThaliTest[606:1017360] THEMultipeerManager stopping peer
,2016-04-08 09:36:15.106 ThaliTest[606:1017360] client session: disconnect
2016-04-08 09:36:15.106 ThaliTest[606:1017360] client session: stateChange:2->0 5401A4DE-2020-4411-800F-72E067EDFF0D:8
,2016-04-08 09:36:15.121 ThaliTest[606:1017360] multipeer manager: stop client timer
2016-04-08 09:36:15.121 ThaliTest[606:1017360] jxcore: stopAdvertisingAndListening: success
ok 186 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 43. Get error when trying to double connect to a peer
,2016-04-08 09:36:18.622 ThaliTest[606:1017360] jxcore: startUpdateAdvertisingAndListening
,2016-04-08 09:36:18.623 ThaliTest[606:1017360] server: starting C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:36:18.624 ThaliTest[606:1017360] multipeer manager: start client restart timer: 0x15e5e0c0
2016-04-08 09:36:18.625 ThaliTest[606:1017360] THEMultipeerManager initialized peer C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:36:18.625 Th,aliTest[606:1017360] jxcore: startUpdateAdvertisingAndListening: success
ok 187 Can call startUpdateAdvertisingAndListening without error
,2016-04-08 09:36:18.627 ThaliTest[606:1017360] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
,2016-04-08 09:36:18.630 ThaliTest[606:1017360] jxcore: startListeningForAdvertisements: success
,ok 188 Can call startListeningForAdvertisements without error
,2016-04-08 09:36:18.644 ThaliTest[606:1017168] client: found new peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:8
2016-04-08 09:36:18.645 ThaliTest[606:1017168] client: found new peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8
,2016-04-08 09:36:18.647 ThaliTest[606:1017360] jxcore: connect 5401A4DE-2020-4411-800F-72E067EDFF0D:8
2016-04-08 09:36:18.648 ThaliTest[606:1017360] client session: connect
2016-04-08 09:36:18.648 ThaliTest[606:1017360] client session: stateChange:0->1 5401A4DE-2020-4411-800F-72E067EDFF0D:8
,2016-04-08 09:36:20.847 ThaliTest[606:1017168] client: found new peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:8
,2016-04-08 09:36:20.903 ThaliTest[606:1018370] client session: not connected 5401A4DE-2020-4411-800F-72E067EDFF0D:8
2016-04-08 09:36:20.904 ThaliTest[606:1018370] client session: onLinkFailure: 5401A4DE-2020-4411-800F-72E067EDFF0D
,2016-04-08 09:36:20.905 ThaliTest[606:1018370] client session: disconnect
2016-04-08 09:36:20.906 ThaliTest[606:1018370] client session: stateChange:1->0 5401A4DE-2020-4411-800F-72E067EDFF0D:8
2016-04-08 09:36:20.906 ThaliTest[606:1018370] client session,: fireConnectCallback: 5401A4DE-2020-4411-800F-72E067EDFF0D
2016-04-08 09:36:20.906 ThaliTest[606:1018370] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-04-08 09:36:21.024 ThaliTest[606:1017168] multipeer session: reset timer
2016-04-08 09:36:21.024 ThaliTest[606:1017168] server: rejecting invitation for lexical ordering 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC
,2016-04-08 09:36:21.030 ThaliTest[606:1017168] multipeer session: reset timer
,2016-04-08 09:36:21.031 ThaliTest[606:1017168] server: rejecting invitation from B29A2A64-B1EF-4545-BC19-F0DD94E05227 due to previous generation (C76D48A2-6720-4997-B51C-ADA808AA0AC0:9 != C76D48A2-6720-4997-B51C-ADA808AA0AC0:8)
,2016-04-08 09:36:23.921 ThaliTest[606:1017360] jxcore: connect 5401A4DE-2020-4411-800F-72E067EDFF0D:8
,2016-04-08 09:36:23.922 ThaliTest[606:1017360] client session: connect
,2016-04-08 09:36:23.923 ThaliTest[606:1017360] client session: stateChange:0->1 5401A4DE-2020-4411-800F-72E067EDFF0D:8
,2016-04-08 09:36:24.206 ThaliTest[606:1018372] client session: not connected 5401A4DE-2020-4411-800F-72E067EDFF0D:8
,2016-04-08 09:36:24.206 ThaliTest[606:1018372] client session: onLinkFailure: 5401A4DE-2020-4411-800F-72E067EDFF0D
2016-04-08 09:36:24.208 ThaliTest[606:1018372] client session: disconnect
,2016-04-08 09:36:24.208 ThaliTest[606:1018372] client session: stateChange:1->0 5401A4DE-2020-4411-800F-72E067EDFF0D:8
,2016-04-08 09:36:24.209 ThaliTest[606:1018372] client session: fireConnectCallback: 5401A4DE-2020-4411-800F-72E067EDFF0D
,2016-04-08 09:36:24.209 ThaliTest[606:1018372] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-04-08 09:36:27.216 ThaliTest[606:1017360] jxcore: connect 5401A4DE-2020-4411-800F-72E067EDFF0D:8
2016-04-08 09:36:27.217 ThaliTest[606:1017360] client session: connect
,2016-04-08 09:36:27.217 ThaliTest[606:1017360] client session: stateChange:0->1 5401A4DE-2020-4411-800F-72E067EDFF0D:8
,2016-04-08 09:36:28.278 ThaliTest[606:1018372] client session: not connected 5401A4DE-2020-4411-800F-72E067EDFF0D:8
2016-04-08 09:36:28.279 ThaliTest[606:1018372] client session: onLinkFailure: 5401A4DE-2020-4411-800F-72E067EDFF0D
,2016-04-08 09:36:28.280 ThaliTest[606:1018372] client session: disconnect
,2016-04-08 09:36:28.280 ThaliTest[606:1018372] client session: stateChange:1->0 5401A4DE-2020-4411-800F-72E067EDFF0D:8
,2016-04-08 09:36:28.282 ThaliTest[606:1018372] client session: fireConnectCallback: 5401A4DE-2020-4411-800F-72E067EDFF0D
,2016-04-08 09:36:28.282 ThaliTest[606:1018372] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-04-08 09:36:31.297 ThaliTest[606:1017360] jxcore: connect 5401A4DE-2020-4411-800F-72E067EDFF0D:8
,2016-04-08 09:36:31.298 ThaliTest[606:1017360] client session: connect
,2016-04-08 09:36:31.299 ThaliTest[606:1017360] client session: stateChange:0->1 5401A4DE-2020-4411-800F-72E067EDFF0D:8
,2016-04-08 09:36:31.458 ThaliTest[606:1018372] client session: not connected 5401A4DE-2020-4411-800F-72E067EDFF0D:8
2016-04-08 09:36:31.458 ThaliTest[606:1018372] client session: onLinkFailure: 5401A4DE-2020-4411-800F-72E067EDFF0D
2016-04-08 09:36:31.458, ThaliTest[606:1018372] client session: disconnect
2016-04-08 09:36:31.459 ThaliTest[606:1018372] client session: stateChange:1->0 5401A4DE-2020-4411-800F-72E067EDFF0D:8
2016-04-08 09:36:31.460 ThaliTest[606:1018372] client session: fireConnectCallback: 5401A4DE-2020-4411-800F-72E067EDFF0D
,2016-04-08 09:36:31.460 ThaliTest[606:1018372] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-04-08 09:36:32.773 ThaliTest[606:1017168] multipeer session: reset timer
2016-04-08 09:36:32.773 ThaliTest[606:1017168] server: disconnecting to refresh session (B29A2A64-B1EF-4545-BC19-F0DD94E05227)
2016-04-08 09:36:32.773 ThaliTest[606:1017168] se,rver: rejecting invitation from B29A2A64-B1EF-4545-BC19-F0DD94E05227 due to previous generation (C76D48A2-6720-4997-B51C-ADA808AA0AC0:9 != C76D48A2-6720-4997-B51C-ADA808AA0AC0:8)
,2016-04-08 09:36:34.217 ThaliTest[606:1017168] multipeer session: reset timer
2016-04-08 09:36:34.217 ThaliTest[606:1017168] server: disconnecting to refresh session (9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC)
,2016-04-08 09:36:34.218 ThaliTest[606:1017168] server: rejecting invitation for lexical ordering 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC
,2016-04-08 09:36:34.474 ThaliTest[606:1017360] jxcore: connect 5401A4DE-2020-4411-800F-72E067EDFF0D:8
,2016-04-08 09:36:34.475 ThaliTest[606:1017360] client session: connect
,2016-04-08 09:36:34.476 ThaliTest[606:1017360] client session: stateChange:0->1 5401A4DE-2020-4411-800F-72E067EDFF0D:8
,2016-04-08 09:36:34.570 ThaliTest[606:1018372] client session: not connected 5401A4DE-2020-4411-800F-72E067EDFF0D:8
2016-04-08 09:36:34.571 ThaliTest[606:1018372] client session: onLinkFailure: 5401A4DE-2020-4411-800F-72E067EDFF0D
2016-04-08 09:36:34.571 ThaliTest[606:1018372] client session: disconnect
,2016-04-08 09:36:34.571 ThaliTest[606:1018372] client session: stateChange:1->0 5401A4DE-2020-4411-800F-72E067EDFF0D:8
2016-04-08 09:36:34.573 ThaliTest[606:1018372] client session: fireConnectCallback: 5401A4DE-2020-4411-800F-72E067EDFF0D
,2016-04-08 09:36:34.573 ThaliTest[606:1018372] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-04-08 09:36:37.589 ThaliTest[606:1017360] jxcore: connect 5401A4DE-2020-4411-800F-72E067EDFF0D:8
2016-04-08 09:36:37.590 ThaliTest[606:1017360] client session: connect
,2016-04-08 09:36:37.591 ThaliTest[606:1017360] client session: stateChange:0->1 5401A4DE-2020-4411-800F-72E067EDFF0D:8
,2016-04-08 09:36:37.765 ThaliTest[606:1018372] client session: not connected 5401A4DE-2020-4411-800F-72E067EDFF0D:8
,2016-04-08 09:36:37.766 ThaliTest[606:1018372] client session: onLinkFailure: 5401A4DE-2020-4411-800F-72E067EDFF0D
,2016-04-08 09:36:37.766 ThaliTest[606:1018372] client session: disconnect
,2016-04-08 09:36:37.767 ThaliTest[606:1018372] client session: stateChange:1->0 5401A4DE-2020-4411-800F-72E067EDFF0D:8
,2016-04-08 09:36:37.768 ThaliTest[606:1018372] client session: fireConnectCallback: 5401A4DE-2020-4411-800F-72E067EDFF0D
2016-04-08 09:36:37.768 ThaliTest[606:1018372] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-04-08 09:36:38.626 ThaliTest[606:1017168] multipeer manager: restart client
,2016-04-08 09:36:38.643 ThaliTest[606:1017168] client: found updated peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:36:38.644 ThaliTest[606:1017168] client: found updated peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:36:38.645 Th,aliTest[606:1017168] client: found updated peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:36:40.777 ThaliTest[606:1017360] jxcore: connect 5401A4DE-2020-4411-800F-72E067EDFF0D:8
,2016-04-08 09:36:40.778 ThaliTest[606:1017360] client session: connect
,2016-04-08 09:36:40.778 ThaliTest[606:1017360] client session: stateChange:0->1 5401A4DE-2020-4411-800F-72E067EDFF0D:9
,2016-04-08 09:36:40.917 ThaliTest[606:1018295] client session: not connected 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:36:40.917 ThaliTest[606:1018295] client session: onLinkFailure: 5401A4DE-2020-4411-800F-72E067EDFF0D
2016-04-08 09:36:40.917 ThaliTest[606:1018295] client session: disconnect
,2016-04-08 09:36:40.918 ThaliTest[606:1018295] client session: stateChange:1->0 5401A4DE-2020-4411-800F-72E067EDFF0D:9
,2016-04-08 09:36:40.918 ThaliTest[606:1018295] client session: fireConnectCallback: 5401A4DE-2020-4411-800F-72E067EDFF0D
2016-04-08 09:36:40.919 ThaliTest[606:1018295] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-04-08 09:36:43.924 ThaliTest[606:1017360] jxcore: connect 5401A4DE-2020-4411-800F-72E067EDFF0D:8
,2016-04-08 09:36:43.925 ThaliTest[606:1017360] client session: connect
2016-04-08 09:36:43.926 ThaliTest[606:1017360] client session: stateChange:0->1 5401A4DE-2020-4411-800F-72E067EDFF0D:9
,2016-04-08 09:36:44.002 ThaliTest[606:1018372] client session: not connected 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:36:44.002 ThaliTest[606:1018372] client session: onLinkFailure: 5401A4DE-2020-4411-800F-72E067EDFF0D
,2016-04-08 09:36:44.002 ThaliTest[606:1018372] client session: disconnect
,2016-04-08 09:36:44.003 ThaliTest[606:1018372] client session: stateChange:1->0 5401A4DE-2020-4411-800F-72E067EDFF0D:9
,2016-04-08 09:36:44.005 ThaliTest[606:1018372] client session: fireConnectCallback: 5401A4DE-2020-4411-800F-72E067EDFF0D
2016-04-08 09:36:44.006 ThaliTest[606:1018372] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-04-08 09:36:45.882 ThaliTest[606:1017168] multipeer session: reset timer
,2016-04-08 09:36:45.883 ThaliTest[606:1017168] server: disconnecting to refresh session (B29A2A64-B1EF-4545-BC19-F0DD94E05227)
,2016-04-08 09:36:45.883 ThaliTest[606:1017168] server: rejecting invitation from B29A2A64-B1EF-4545-BC19-F0DD94E05227 due to previous generation (C76D48A2-6720-4997-B51C-ADA808AA0AC0:9 != C76D48A2-6720-4997-B51C-ADA808AA0AC0:8)
,2016-04-08 09:36:47.017 ThaliTest[606:1017360] jxcore: connect 5401A4DE-2020-4411-800F-72E067EDFF0D:8
,2016-04-08 09:36:47.017 ThaliTest[606:1017360] client session: connect
2016-04-08 09:36:47.018 ThaliTest[606:1017360] client session: stateChange:0->1 5401A4DE-2020-4411-800F-72E067EDFF0D:9
,2016-04-08 09:36:47.193 ThaliTest[606:1018295] client session: not connected 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:36:47.194 ThaliTest[606:1018295] client session: onLinkFailure: 5401A4DE-2020-4411-800F-72E067EDFF0D
2016-04-08 09:36:47.195, ThaliTest[606:1018295] client session: disconnect
2016-04-08 09:36:47.195 ThaliTest[606:1018295] client session: stateChange:1->0 5401A4DE-2020-4411-800F-72E067EDFF0D:9
,2016-04-08 09:36:47.196 ThaliTest[606:1018295] client session: fireConnectCallback: 5401A4DE-2020-4411-800F-72E067EDFF0D
2016-04-08 09:36:47.196 ThaliTest[606:1018295] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-04-08 09:36:47.260 ThaliTest[606:1017168] multipeer session: reset timer
2016-04-08 09:36:47.261 ThaliTest[606:1017168] server: disconnecting to refresh session (9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC)
2016-04-08 09:36:47.261 ThaliTest[606:1017168] se,rver: rejecting invitation for lexical ordering 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC
,2016-04-08 09:36:50.205 ThaliTest[606:1017360] jxcore: connect 5401A4DE-2020-4411-800F-72E067EDFF0D:8
,2016-04-08 09:36:50.206 ThaliTest[606:1017360] client session: connect
,2016-04-08 09:36:50.207 ThaliTest[606:1017360] client session: stateChange:0->1 5401A4DE-2020-4411-800F-72E067EDFF0D:9
,2016-04-08 09:36:50.320 ThaliTest[606:1018295] client session: not connected 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:36:50.321 ThaliTest[606:1018295] client session: onLinkFailure: 5401A4DE-2020-4411-800F-72E067EDFF0D
2016-04-08 09:36:50.321 ThaliTest[606:1018295] client session: disconnect
,2016-04-08 09:36:50.321 ThaliTest[606:1018295] client session: stateChange:1->0 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:36:50.323 ThaliTest[606:1018295] client session: fireConnectCallback: 5401A4DE-2020-4411-800F-72E067EDFF0D
2016-04-08 09:36:50.323 ThaliTest[606:1018295] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,WARN testThaliMobileNative: Too many connect retries!
,2016-04-08 09:36:58.626 ThaliTest[606:1017168] multipeer manager: restart client
,2016-04-08 09:36:58.647 ThaliTest[606:1017168] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:36:58.649 ThaliTest[606:1017168] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:36:58.649 ThaliTest[606:1017168] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:36:59.589 ThaliTest[606:1017168] multipeer session: reset timer
2016-04-08 09:36:59.589 ThaliTest[606:1017168] server: disconnecting to refresh session (B29A2A64-B1EF-4545-BC19-F0DD94E05227)
2016-04-08 09:36:59.590 ThaliTest[606:1017168] se,rver: rejecting invitation from B29A2A64-B1EF-4545-BC19-F0DD94E05227 due to previous generation (C76D48A2-6720-4997-B51C-ADA808AA0AC0:9 != C76D48A2-6720-4997-B51C-ADA808AA0AC0:8)
,2016-04-08 09:37:00.732 ThaliTest[606:1017168] multipeer session: reset timer
2016-04-08 09:37:00.733 ThaliTest[606:1017168] server: disconnecting to refresh session (9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC)
2016-04-08 09:37:00.733 ThaliTest[606:1017168] server: rejecting invitation for lexical ordering 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC
,2016-04-08 09:37:00.735 ThaliTest[606:1017360] jxcore: connect 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:37:00.736 ThaliTest[606:1017360] client session: connect
,2016-04-08 09:37:00.737 ThaliTest[606:1017360] client session: stateChange:0->1 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:37:04.624 ThaliTest[606:1018490] client session: p2p link connected
,2016-04-08 09:37:04.627 ThaliTest[606:1018490] client session: stateChange:1->2 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:37:04.628 ThaliTest[606:1018490] client session: fireConnectCallback: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC
2016-04-08 09:,37:04.628 ThaliTest[606:1018490] jxcore: connect: success
,2016-04-08 09:37:04.645 ThaliTest[606:1017168] client: relay established
2016-04-08 09:37:04.646 ThaliTest[606:1017168] client: new accepted socket: 0x1811d2b0
2016-04-08 09:37:04.646 ThaliTest[606:1017360] jxcore: connect 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:37:04.647 ThaliTest[606:1017360] client: already connect(ing/ed) to 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:37:04.648 ThaliTest[606:1017360] jxcore: connect: fail: Already connect(ing/ed)
,ok 189 Expected error
,ok 190 Null connection as expected
,2016-04-08 09:37:04.651 ThaliTest[606:1017360] jxcore: connect 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:37:04.652 ThaliTest[606:1017360] client: already connect(ing/ed) to 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:37:04.653 ThaliTest[606:1017360] jxcore: connect: fail: Already connect(ing/ed)
,ok 191 Expected error
,ok 192 Null connection as expected
,# teardown
,2016-04-08 09:37:11.857 ThaliTest[606:1017168] multipeer session: reset timer
,2016-04-08 09:37:11.857 ThaliTest[606:1017168] server: disconnecting to refresh session (B29A2A64-B1EF-4545-BC19-F0DD94E05227)
,2016-04-08 09:37:11.858 ThaliTest[606:1017168] server: rejecting invitation from B29A2A64-B1EF-4545-BC19-F0DD94E05227 due to previous generation (C76D48A2-6720-4997-B51C-ADA808AA0AC0:9 != C76D48A2-6720-4997-B51C-ADA808AA0AC0:8)
,2016-04-08 09:37:18.626 ThaliTest[606:1017168] multipeer manager: restart client
,2016-04-08 09:37:18.655 ThaliTest[606:1017168] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:37:18.655 ThaliTest[606:1017168] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:37:18.656 ThaliTest[606:1017168] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:37:25.338 ThaliTest[606:1017168] multipeer session: reset timer
,2016-04-08 09:37:25.338 ThaliTest[606:1017168] server: disconnecting to refresh session (B29A2A64-B1EF-4545-BC19-F0DD94E05227)
,2016-04-08 09:37:25.339 ThaliTest[606:1017168] server: rejecting invitation from B29A2A64-B1EF-4545-BC19-F0DD94E05227 due to previous generation (C76D48A2-6720-4997-B51C-ADA808AA0AC0:9 != C76D48A2-6720-4997-B51C-ADA808AA0AC0:8)
,2016-04-08 09:37:38.385 ThaliTest[606:1017168] multipeer session: reset timer
2016-04-08 09:37:38.385 ThaliTest[606:1017168] server: disconnecting to refresh session (B29A2A64-B1EF-4545-BC19-F0DD94E05227)
2016-04-08 09:37:38.386 ThaliTest[606:1017168] se,rver: rejecting invitation from B29A2A64-B1EF-4545-BC19-F0DD94E05227 due to previous generation (C76D48A2-6720-4997-B51C-ADA808AA0AC0:9 != C76D48A2-6720-4997-B51C-ADA808AA0AC0:8)
,2016-04-08 09:37:38.626 ThaliTest[606:1017168] multipeer manager: restart client
,2016-04-08 09:37:38.657 ThaliTest[606:1017168] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:37:38.658 ThaliTest[606:1017168] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:37:38.658 ThaliTest[606:1017168] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:37:50.947 ThaliTest[606:1017168] multipeer session: reset timer
,2016-04-08 09:37:50.948 ThaliTest[606:1017168] server: disconnecting to refresh session (B29A2A64-B1EF-4545-BC19-F0DD94E05227)
,2016-04-08 09:37:50.948 ThaliTest[606:1017168] server: rejecting invitation from B29A2A64-B1EF-4545-BC19-F0DD94E05227 due to previous generation (C76D48A2-6720-4997-B51C-ADA808AA0AC0:9 != C76D48A2-6720-4997-B51C-ADA808AA0AC0:8)
,2016-04-08 09:37:58.626 ThaliTest[606:1017168] multipeer manager: restart client
,2016-04-08 09:37:58.658 ThaliTest[606:1017168] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:37:58.658 ThaliTest[606:1017168] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:37:58.659 ,ThaliTest[606:1017168] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:38:03.862 ThaliTest[606:1017168] multipeer session: reset timer
,2016-04-08 09:38:03.863 ThaliTest[606:1017168] server: disconnecting to refresh session (B29A2A64-B1EF-4545-BC19-F0DD94E05227)
2016-04-08 09:38:03.863 ThaliTest[606:1017168] server: rejecting invitation from B29A2A64-B1EF-4545-BC19-F0DD94E05227 due to pre,vious generation (C76D48A2-6720-4997-B51C-ADA808AA0AC0:9 != C76D48A2-6720-4997-B51C-ADA808AA0AC0:8)
,2016-04-08 09:38:16.879 ThaliTest[606:1017168] multipeer session: reset timer
,2016-04-08 09:38:16.879 ThaliTest[606:1017168] server: disconnecting to refresh session (B29A2A64-B1EF-4545-BC19-F0DD94E05227)
,2016-04-08 09:38:16.880 ThaliTest[606:1017168] server: rejecting invitation from B29A2A64-B1EF-4545-BC19-F0DD94E05227 due to previous generation (C76D48A2-6720-4997-B51C-ADA808AA0AC0:9 != C76D48A2-6720-4997-B51C-ADA808AA0AC0:8)
,2016-04-08 09:38:18.626 ThaliTest[606:1017168] multipeer manager: restart client
,2016-04-08 09:38:18.653 ThaliTest[606:1017168] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:38:18.653 ThaliTest[606:1017168] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:38:18.654 ,ThaliTest[606:1017168] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:38:38.626 ThaliTest[606:1017168] multipeer manager: restart client
,2016-04-08 09:38:38.655 ThaliTest[606:1017168] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:38:38.655 ThaliTest[606:1017168] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:38:38.656 ThaliTest[606:1017168] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:38:58.626 ThaliTest[606:1017168] multipeer manager: restart client
,2016-04-08 09:38:58.653 ThaliTest[606:1017168] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:38:58.654 ThaliTest[606:1017168] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:38:58.654 ,ThaliTest[606:1017168] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:39:18.626 ThaliTest[606:1017168] multipeer manager: restart client
,2016-04-08 09:39:18.656 ThaliTest[606:1017168] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:39:18.657 ThaliTest[606:1017168] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
,2016-04-08 09:39:18.658 ThaliTest[606:1017168] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:39:38.626 ThaliTest[606:1017168] multipeer manager: restart client
,2016-04-08 09:39:38.655 ThaliTest[606:1017168] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:39:38.656 ThaliTest[606:1017168] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:39:38.656 ,ThaliTest[606:1017168] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:39:58.626 ThaliTest[606:1017168] multipeer manager: restart client
,2016-04-08 09:39:58.658 ThaliTest[606:1017168] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:39:58.658 ThaliTest[606:1017168] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:39:58.658 ,ThaliTest[606:1017168] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:40:18.626 ThaliTest[606:1017168] multipeer manager: restart client
,2016-04-08 09:40:18.656 ThaliTest[606:1017168] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
,2016-04-08 09:40:18.658 ThaliTest[606:1017168] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:40:18.658 ThaliTest[606:1017168] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:40:38.626 ThaliTest[606:1017168] multipeer manager: restart client
,2016-04-08 09:40:38.658 ThaliTest[606:1017168] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:40:38.659 ThaliTest[606:1017168] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:40:38.659 ThaliTest[606:1017168] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
,2016-04-08 09:40:58.626 ThaliTest[606:1017168] multipeer manager: restart client
,2016-04-08 09:40:58.657 ThaliTest[606:1017168] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:40:58.658 ThaliTest[606:1017168] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:40:58.660 ThaliTest[606:1017168] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:41:18.626 ThaliTest[606:1017168] multipeer manager: restart client
,2016-04-08 09:41:18.656 ThaliTest[606:1017168] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:41:18.657 ThaliTest[606:1017168] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:41:18.658 ,ThaliTest[606:1017168] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:41:38.626 ThaliTest[606:1017168] multipeer manager: restart client
,2016-04-08 09:41:38.657 ThaliTest[606:1017168] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:41:38.658 ThaliTest[606:1017168] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:41:38.658 ,ThaliTest[606:1017168] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
,2016-04-08 09:41:58.626 ThaliTest[606:1017168] multipeer manager: restart client
,2016-04-08 09:41:58.654 ThaliTest[606:1017168] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:41:58.655 ThaliTest[606:1017168] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:41:58.658 ThaliTest[606:1017168] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:42:18.626 ThaliTest[606:1017168] multipeer manager: restart client
,2016-04-08 09:42:18.655 ThaliTest[606:1017168] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:42:18.655 ThaliTest[606:1017168] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:42:18.656 ,ThaliTest[606:1017168] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:42:38.626 ThaliTest[606:1017168] multipeer manager: restart client
,2016-04-08 09:42:38.656 ThaliTest[606:1017168] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:42:38.656 ThaliTest[606:1017168] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:42:38.657 ThaliTest[606:1017168] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
,2016-04-08 09:42:58.626 ThaliTest[606:1017168] multipeer manager: restart client
,2016-04-08 09:42:58.656 ThaliTest[606:1017168] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:42:58.656 ThaliTest[606:1017168] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:42:58.658 ThaliTest[606:1017168] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:43:18.626 ThaliTest[606:1017168] multipeer manager: restart client
,2016-04-08 09:43:18.657 ThaliTest[606:1017168] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:43:18.658 ThaliTest[606:1017168] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
,2016-04-08 09:43:18.660 ThaliTest[606:1017168] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:43:38.626 ThaliTest[606:1017168] multipeer manager: restart client
,2016-04-08 09:43:38.657 ThaliTest[606:1017168] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:43:38.657 ThaliTest[606:1017168] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:43:38.660 ThaliTest[606:1017168] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:43:58.626 ThaliTest[606:1017168] multipeer manager: restart client
,2016-04-08 09:43:58.655 ThaliTest[606:1017168] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:43:58.656 ThaliTest[606:1017168] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
,2016-04-08 09:43:58.659 ThaliTest[606:1017168] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:44:18.626 ThaliTest[606:1017168] multipeer manager: restart client
,2016-04-08 09:44:18.659 ThaliTest[606:1017168] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:44:18.659 ThaliTest[606:1017168] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:44:18.659 ThaliTest[606:1017168] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:44:38.626 ThaliTest[606:1017168] multipeer manager: restart client
,2016-04-08 09:44:38.655 ThaliTest[606:1017168] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
,2016-04-08 09:44:38.655 ThaliTest[606:1017168] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:44:38.656 ThaliTest[606:1017168] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:44:58.626 ThaliTest[606:1017168] multipeer manager: restart client
,2016-04-08 09:44:58.656 ThaliTest[606:1017168] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:44:58.657 ThaliTest[606:1017168] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:44:58.658 ,ThaliTest[606:1017168] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:45:18.626 ThaliTest[606:1017168] multipeer manager: restart client
,2016-04-08 09:45:18.657 ThaliTest[606:1017168] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:45:18.657 ThaliTest[606:1017168] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:45:18.658 ,ThaliTest[606:1017168] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:45:38.626 ThaliTest[606:1017168] multipeer manager: restart client
,2016-04-08 09:45:38.657 ThaliTest[606:1017168] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:45:38.657 ThaliTest[606:1017168] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:45:38.659 ThaliTest[606:1017168] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:45:58.626 ThaliTest[606:1017168] multipeer manager: restart client
,2016-04-08 09:45:58.655 ThaliTest[606:1017168] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:45:58.655 ThaliTest[606:1017168] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:45:58.656 ,ThaliTest[606:1017168] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:46:18.626 ThaliTest[606:1017168] multipeer manager: restart client
,2016-04-08 09:46:18.657 ThaliTest[606:1017168] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:46:18.657 ThaliTest[606:1017168] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:46:18.657 ThaliTest[606:1017168] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
,2016-04-08 09:46:38.626 ThaliTest[606:1017168] multipeer manager: restart client
,2016-04-08 09:46:38.658 ThaliTest[606:1017168] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:46:38.659 ThaliTest[606:1017168] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
,2016-04-08 09:46:38.661 ThaliTest[606:1017168] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:46:58.626 ThaliTest[606:1017168] multipeer manager: restart client
,2016-04-08 09:46:58.658 ThaliTest[606:1017168] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:46:58.658 ThaliTest[606:1017168] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:46:58.658 ,ThaliTest[606:1017168] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
,2016-04-08 09:47:18.626 ThaliTest[606:1017168] multipeer manager: restart client
,2016-04-08 09:47:18.658 ThaliTest[606:1017168] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:47:18.659 ThaliTest[606:1017168] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:47:18.659 ,ThaliTest[606:1017168] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:47:38.626 ThaliTest[606:1017168] multipeer manager: restart client
,2016-04-08 09:47:38.657 ThaliTest[606:1017168] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:47:38.657 ThaliTest[606:1017168] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
,2016-04-08 09:47:38.661 ThaliTest[606:1017168] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:47:58.626 ThaliTest[606:1017168] multipeer manager: restart client
,2016-04-08 09:47:58.657 ThaliTest[606:1017168] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:47:58.657 ThaliTest[606:1017168] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:47:58.659 ,ThaliTest[606:1017168] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:48:18.626 ThaliTest[606:1017168] multipeer manager: restart client
,2016-04-08 09:48:18.655 ThaliTest[606:1017168] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:48:18.655 ThaliTest[606:1017168] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
,2016-04-08 09:48:18.659 ThaliTest[606:1017168] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:48:38.626 ThaliTest[606:1017168] multipeer manager: restart client
,2016-04-08 09:48:38.655 ThaliTest[606:1017168] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:48:38.655 ThaliTest[606:1017168] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:48:38.657 ,ThaliTest[606:1017168] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:48:58.626 ThaliTest[606:1017168] multipeer manager: restart client
,2016-04-08 09:48:58.657 ThaliTest[606:1017168] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:48:58.657 ThaliTest[606:1017168] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:48:58.658 ThaliTest[606:1017168] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:49:18.626 ThaliTest[606:1017168] multipeer manager: restart client
,2016-04-08 09:49:18.659 ThaliTest[606:1017168] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:49:18.659 ThaliTest[606:1017168] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:49:18.659 ,ThaliTest[606:1017168] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
,2016-04-08 09:49:38.626 ThaliTest[606:1017168] multipeer manager: restart client
,2016-04-08 09:49:38.656 ThaliTest[606:1017168] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:49:38.657 ThaliTest[606:1017168] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:49:38.659 ThaliTest[606:1017168] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:49:58.626 ThaliTest[606:1017168] multipeer manager: restart client
,2016-04-08 09:49:58.654 ThaliTest[606:1017168] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:49:58.655 ThaliTest[606:1017168] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:49:58.656 ThaliTest[606:1017168] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:50:18.626 ThaliTest[606:1017168] multipeer manager: restart client
,2016-04-08 09:50:18.658 ThaliTest[606:1017168] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:50:18.659 ThaliTest[606:1017168] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:50:18.659 ThaliTest[606:1017168] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
,2016-04-08 09:50:38.625 ThaliTest[606:1017168] multipeer manager: restart client
,2016-04-08 09:50:38.655 ThaliTest[606:1017168] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:50:38.656 ThaliTest[606:1017168] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
,2016-04-08 09:50:38.658 ThaliTest[606:1017168] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:50:58.626 ThaliTest[606:1017168] multipeer manager: restart client
,2016-04-08 09:50:58.657 ThaliTest[606:1017168] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:50:58.658 ThaliTest[606:1017168] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:50:58.658 ,ThaliTest[606:1017168] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
,2016-04-08 09:51:18.626 ThaliTest[606:1017168] multipeer manager: restart client
,2016-04-08 09:51:18.657 ThaliTest[606:1017168] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:51:18.657 ThaliTest[606:1017168] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:51:18.657 ,ThaliTest[606:1017168] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9

```
