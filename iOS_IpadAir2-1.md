#### Test 6480993629f6128_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/6480993629f6128/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/821E26D4-734E-43B6-B44A-FCC4ED661C5B/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/821E26D4-734E-43B6-B44A-FCC4ED661C5B/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/6480993629f6128/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/6480993629f6128/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/ABBB78C1-5F41-491A-B2A7-D024D5E45BD5/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50401"
,(lldb)     command script import "/tmp/821E26D4-734E-43B6-B44A-FCC4ED661C5B/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-04-01 23:47:26.165 ThaliTest[327:163918] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/41908AAB-C3DF-445F-82E4-540E66811E78/Library/Cookies/Cookies.binarycookies
,2016-04-01 23:47:26.577 ThaliTest[327:163918] Apache Cordova native platform version 4.1.0 is starting.
,2016-04-01 23:47:26.578 ThaliTest[327:163918] Multi-tasking -> Device: YES, App: YES
,2016-04-01 23:47:26.597 ThaliTest[327:163918] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-04-01 23:47:28.961 ThaliTest[327:163918] Using UIWebView
,2016-04-01 23:47:28.967 ThaliTest[327:163918] [CDVTimer][handleopenurl] 0.384986ms
,2016-04-01 23:47:28.974 ThaliTest[327:163918] [CDVTimer][intentandnavigationfilter] 7.012963ms
,2016-04-01 23:47:28.975 ThaliTest[327:163918] [CDVTimer][gesturehandler] 0.335991ms
,2016-04-01 23:47:28.976 ThaliTest[327:163918] [CDVTimer][TotalPluginStartup] 9.371996ms
,2016-04-01 23:47:37.193 ThaliTest[327:163918] Resetting plugins due to page load.
,2016-04-01 23:47:41.537 ThaliTest[327:163918] Finished load of: file:///var/mobile/Containers/Bundle/Application/ABBB78C1-5F41-491A-B2A7-D024D5E45BD5/ThaliTest.app/www/index.html
,2016-04-01 23:47:41.738 ThaliTest[327:163918] JXcore Cordova plugin initializing
2016-04-01 23:47:41.739 ThaliTest[327:164135] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-04-01 23:47:48.233 ThaliTest[327:164135] jxcore: didRegisterToNative peerAvailabilityChanged
2016-04-01 23:47:48.234 ThaliTest[327:164135] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-04-01 23:47:48.234 ThaliTest[327:164135] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-04-01 23:47:48.236 ThaliTest[327:164135] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-IpadAir2-1
WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/ABBB78C1-5F41-491A-B2A7-D024D5E45BD5/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/ABBB78C1-5F41-491A-B2A7-D024D5E45BD5/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/ABBB78C1-5F41-491A-B2A7-D024D5E45BD5/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/ABBB78C1-5F41-491A-B2A7-D024D5E45BD5/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/ABBB78C1-5F41-491A-B2A7-D024D5E45BD5/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/ABBB78C1-5F41-491A-B2A7-D024D5E45BD5/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/ABBB78C1-5F41-491A-B2A7-D024D5E45BD5/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/ABBB78C1-5F41-491A-B2A7-D024D5E45BD5/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/ABBB78C1-5F41-491A-B2A7-D024D5E45BD5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/ABBB78C1-5F41-491A-B2A7-D024D5E45BD5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/ABBB78C1-5F41-491A-B2A7-D024D5E45BD5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/ABBB78C1-5F41-491A-B2A7-D024D5E45BD5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/ABBB78C1-5F41-491A-B2A7-D024D5E45BD5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/ABBB78C1-5F41-491A-B2A7-D024D5E45BD5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/ABBB78C1-5F41-491A-B2A7-D024D5E45BD5/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/ABBB78C1-5F41-491A-B2A7-D024D5E45BD5/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/ABBB78C1-5F41-491A-B2A7-D024D5E45BD5/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/ABBB78C1-5F41-491A-B2A7-D024D5E45BD5/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/ABBB78C1-5F41-491A-B2A7-D024D5E45BD5/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/ABBB78C1-5F41-491A-B2A7-D024D5E45BD5/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/ABBB78C1-5F41-491A-B2A7-D024D5E45BD5/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/ABBB78C1-5F41-491A-B2A7-D024D5E45BD5/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-04-01 23:47:53.500 ThaliTest[327:163918] THREAD WARNING: ['JXcore'] took '4986.984863' ms. Plugin should use a background thread.
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50547
,ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50549
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
,DEBUG createNativeListener: listening 50552
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
,DEBUG createNativeListener: listening 50556
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
,DEBUG createNativeListener: listening 50561
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
,DEBUG createNativeListener: listening 50565
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
,DEBUG createNativeListener: listening 50569
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
,DEBUG createNativeListener: listening 50573
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
,DEBUG createNativeListener: listening 50577
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
,DEBUG createNativeListener: listening 50629
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
,DEBUG createNativeListener: listening 50633
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
,[{"uuid":"8f481545-2d3c-4c34-90c0-6602bf93a785","data":"custom data"},{"uuid":"7299c1cd-4325-4a34-90c1-c1db833eeee1","data":"custom data"},{"uuid":"c7e38397-c90d-4e48-845d-977d1574ba6e","data":"custom data"},{"uuid":"3559cc27-6402-432b-bcfd-c285802596a6","data":"custom data"}]
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
,DEBUG createNativeListener: listening 50643
,2016-04-01 23:50:20.100 ThaliTest[327:164135] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-01 23:50:20.101 ThaliTest[327:164135] jxcore: stopListeningForAdvertisements: success
,ok 91 error should be null
,ok 92 error should be null
,2016-04-01 23:50:20.105 ThaliTest[327:164135] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-01 23:50:20.107 ThaliTest[327:164135] jxcore: stopListeningForAdvertisements: success
,ok 93 error should be null
,ok 94 error should be null
,# teardown
,2016-04-01 23:50:20.198 ThaliTest[327:164135] jxcore: stopAdvertisingAndListening
,2016-04-01 23:50:20.198 ThaliTest[327:164135] THEMultipeerManager stopping peer
,2016-04-01 23:50:20.199 ThaliTest[327:164135] jxcore: stopAdvertisingAndListening: success
,2016-04-01 23:50:20.200 ThaliTest[327:164135] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-01 23:50:20.203 ThaliTest[327:164135] jxcore: stopListeningForAdvertisements: success
,ok 95 error should be null
,ok 96 error should be null
,# setup
,# 26. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50645
,2016-04-01 23:50:20.443 ThaliTest[327:164135] jxcore: startListeningForAdvertisements
,2016-04-01 23:50:20.444 ThaliTest[327:164135] multipeer manager: start client restart timer: 0x1567ce10
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-01 23:50:20.447 ThaliTest[327:164135] jxcore: startListeningForAdvertisements: success
,ok 97 error should be null
,ok 98 error should be null
,2016-04-01 23:50:20.469 ThaliTest[327:164135] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-01 23:50:20.471 ThaliTest[327:164135] jxcore: startListeningForAdvertisements: success
,ok 99 error should be null
,ok 100 error should be null
,# teardown
,2016-04-01 23:50:21.216 ThaliTest[327:164135] jxcore: stopAdvertisingAndListening
2016-04-01 23:50:21.217 ThaliTest[327:164135] THEMultipeerManager stopping peer
,2016-04-01 23:50:21.217 ThaliTest[327:164135] jxcore: stopAdvertisingAndListening: success
,2016-04-01 23:50:21.218 ThaliTest[327:164135] jxcore: stopListeningForAdvertisements
,2016-04-01 23:50:21.219 ThaliTest[327:164135] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 23:50:21.222 ThaliTest[327:164135] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 101 error should be null
,ok 102 error should be null
,# setup
,# 27. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50647
,2016-04-01 23:50:38.971 ThaliTest[327:164135] jxcore: startUpdateAdvertisingAndListening
,2016-04-01 23:50:38.972 ThaliTest[327:164135] server: starting 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:1
,2016-04-01 23:50:38.973 ThaliTest[327:164135] multipeer manager: start client restart timer: 0x1567ce10
2016-04-01 23:50:38.974 ThaliTest[327:164135] THEMultipeerManager initialized peer 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:1
,2016-04-01 23:50:38.975 ThaliTest[327:164135] jxcore: startUpdateAdvertisingAndListening: success
,ok 103 error should be null
,ok 104 error should be null
,2016-04-01 23:50:38.995 ThaliTest[327:164135] jxcore: startUpdateAdvertisingAndListening
,2016-04-01 23:50:38.996 ThaliTest[327:164135] THEMultipeerManager stopping peer
,2016-04-01 23:50:38.997 ThaliTest[327:164135] multipeer manager: stop client timer
2016-04-01 23:50:38.998 ThaliTest[327:164135] server: starting 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:2
2016-04-01 23:50:38.999 ThaliTest[327:164135] multipeer manager: start client restart timer: 0x1567ce10
2016-04-01 23:50:38.999 ThaliTest[327:164135] THEMultipeerManager initialized peer 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:2
2016-04-01 23:50:38.999 ThaliTest[327:164135] jxcore: startUpdateAdvertisingAndListening: success
,ok 105 error should be null
,ok 106 error should be null
,# teardown
,2016-04-01 23:50:39.205 ThaliTest[327:163918] client: found new peer: BC3134AD-A0D1-47B0-885A-5F5313680802:2
,2016-04-01 23:50:40.831 ThaliTest[327:163918] client: found new peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:2
,2016-04-01 23:50:40.902 ThaliTest[327:164135] jxcore: stopAdvertisingAndListening
,2016-04-01 23:50:40.903 ThaliTest[327:164135] THEMultipeerManager stopping peer
,2016-04-01 23:50:40.904 ThaliTest[327:164135] multipeer manager: stop client timer
2016-04-01 23:50:40.904 ThaliTest[327:164135] jxcore: stopAdvertisingAndListening: success
2016-04-01 23:50:40.905 ThaliTest[327:164135] jxcore: stopListeningForAdvertisem,ents
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 23:50:40.907 ThaliTest[327:164135] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 107 error should be null
,ok 108 error should be null
,# setup
,# 28. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50652
,2016-04-01 23:50:58.150 ThaliTest[327:164135] jxcore: stopAdvertisingAndListening
,2016-04-01 23:50:58.151 ThaliTest[327:164135] THEMultipeerManager stopping peer
,2016-04-01 23:50:58.151 ThaliTest[327:164135] jxcore: stopAdvertisingAndListening: success
,ok 109 error should be null
,ok 110 error should be null
,2016-04-01 23:50:58.157 ThaliTest[327:164135] jxcore: stopAdvertisingAndListening
2016-04-01 23:50:58.158 ThaliTest[327:164135] THEMultipeerManager stopping peer
,2016-04-01 23:50:58.159 ThaliTest[327:164135] jxcore: stopAdvertisingAndListening: success
,ok 111 error should be null
,ok 112 error should be null
,# teardown
,2016-04-01 23:50:58.364 ThaliTest[327:164135] jxcore: stopAdvertisingAndListening
2016-04-01 23:50:58.364 ThaliTest[327:164135] THEMultipeerManager stopping peer
,2016-04-01 23:50:58.365 ThaliTest[327:164135] jxcore: stopAdvertisingAndListening: success
,2016-04-01 23:50:58.366 ThaliTest[327:164135] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-01 23:50:58.368 ThaliTest[327:164135] jxcore: stopListeningForAdvertisements: success
,ok 113 error should be null
,ok 114 error should be null
,# setup
,# 29. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50654
,ok 115 first call should succeed
,ok 116 first call should succeed
,ok 117 specific error should be returned
,# teardown
,2016-04-01 23:50:58.933 ThaliTest[327:164135] jxcore: stopAdvertisingAndListening
,2016-04-01 23:50:58.934 ThaliTest[327:164135] THEMultipeerManager stopping peer
,2016-04-01 23:50:58.934 ThaliTest[327:164135] jxcore: stopAdvertisingAndListening: success
,2016-04-01 23:50:58.935 ThaliTest[327:164135] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-01 23:50:58.938 ThaliTest[327:164135] jxcore: stopListeningForAdvertisements: success
,ok 118 error should be null
,ok 119 error should be null
,# setup
,# 30. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50656
,2016-04-01 23:50:59.826 ThaliTest[327:164135] jxcore: startListeningForAdvertisements
,2016-04-01 23:50:59.828 ThaliTest[327:164135] multipeer manager: start client restart timer: 0x1567ce10
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-01 23:50:59.831 ThaliTest[327:164135] jxcore: startListeningForAdvertisements: success
,2016-04-01 23:50:59.851 ThaliTest[327:164135] jxcore: startUpdateAdvertisingAndListening
,2016-04-01 23:50:59.851 ThaliTest[327:164135] server: starting 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:3
,2016-04-01 23:50:59.853 ThaliTest[327:164135] THEMultipeerManager initialized peer 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:3
2016-04-01 23:50:59.853 ThaliTest[327:164135] jxcore: startUpdateAdvertisingAndListening: success
,ok 120 called only once
,ok 121 discovery state matches
,ok 122 advertising state matches
,# teardown
,2016-04-01 23:50:59.980 ThaliTest[327:164135] jxcore: stopAdvertisingAndListening
,2016-04-01 23:50:59.981 ThaliTest[327:164135] THEMultipeerManager stopping peer
,2016-04-01 23:50:59.981 ThaliTest[327:164135] jxcore: stopAdvertisingAndListening: success
,2016-04-01 23:50:59.983 ThaliTest[327:164135] jxcore: stopListeningForAdvertisements
2016-04-01 23:50:59.983 ThaliTest[327:164135] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-01 23:50:59.987 ThaliTest[327:164135] jxcore: stopListeningForAdvertisements: success
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
,2016-04-01 23:51:29.640 ThaliTest[327:164135] jxcore: startListeningForAdvertisements
,2016-04-01 23:51:29.641 ThaliTest[327:164135] multipeer manager: start client restart timer: 0x1567ce10
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-01 23:51:29.643 ThaliTest[327:164135] jxcore: startListeningForAdvertisements: success
,ok 138 Can call startListeningForAdvertisements without error
,2016-04-01 23:51:29.651 ThaliTest[327:164135] jxcore: stopListeningForAdvertisements
,2016-04-01 23:51:29.654 ThaliTest[327:164135] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-01 23:51:29.658 ThaliTest[327:164135] jxcore: stopListeningForAdvertisements: success
,ok 139 Can call stopListeningForAdvertisements without error
,# teardown
,2016-04-01 23:51:29.888 ThaliTest[327:164135] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-01 23:51:29.890 ThaliTest[327:164135] jxcore: stopListeningForAdvertisements: success
,ok 140 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-01 23:51:29.893 ThaliTest[327:164135] jxcore: stopAdvertisingAndListening
,2016-04-01 23:51:29.894 ThaliTest[327:164135] THEMultipeerManager stopping peer
,2016-04-01 23:51:29.894 ThaliTest[327:164135] jxcore: stopAdvertisingAndListening: success
,ok 141 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 35. Calling startListeningForAdvertisements twice is NOT an error
,2016-04-01 23:51:30.407 ThaliTest[327:164135] jxcore: startListeningForAdvertisements
,2016-04-01 23:51:30.408 ThaliTest[327:164135] multipeer manager: start client restart timer: 0x1567ce10
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-01 23:51:30.411 ThaliTest[327:164135] jxcore: startListeningForAdvertisements: success
,ok 142 Can call startListeningForAdvertisements without error
,2016-04-01 23:51:30.414 ThaliTest[327:164135] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-01 23:51:30.417 ThaliTest[327:164135] jxcore: startListeningForAdvertisements: success
,ok 143 Can call startListeningForAdvertisements twice without error
,# teardown
,2016-04-01 23:51:30.561 ThaliTest[327:164135] jxcore: stopListeningForAdvertisements
,2016-04-01 23:51:30.562 ThaliTest[327:164135] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 23:51:30.566 ThaliTest[327:164135] jxcore: stopListeningForAdvertisements: success
,ok 144 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-01 23:51:30.568 ThaliTest[327:164135] jxcore: stopAdvertisingAndListening
,2016-04-01 23:51:30.569 ThaliTest[327:164135] THEMultipeerManager stopping peer
,2016-04-01 23:51:30.569 ThaliTest[327:164135] jxcore: stopAdvertisingAndListening: success
,ok 145 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 36. Calling stopListeningForAdvertisements without calling start is NOT an error
,2016-04-01 23:51:42.078 ThaliTest[327:164135] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-01 23:51:42.081 ThaliTest[327:164135] jxcore: stopListeningForAdvertisements: success
,ok 146 Can call stopListeningForAdvertisements without error
,2016-04-01 23:51:42.083 ThaliTest[327:164135] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-01 23:51:42.085 ThaliTest[327:164135] jxcore: stopListeningForAdvertisements: success
,ok 147 Can call stopListeningForAdvertisements without error
,# teardown
,2016-04-01 23:51:51.926 ThaliTest[327:164135] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-01 23:51:51.929 ThaliTest[327:164135] jxcore: stopListeningForAdvertisements: success
,ok 148 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-01 23:51:51.932 ThaliTest[327:164135] jxcore: stopAdvertisingAndListening
2016-04-01 23:51:51.932 ThaliTest[327:164135] THEMultipeerManager stopping peer
,2016-04-01 23:51:51.932 ThaliTest[327:164135] jxcore: stopAdvertisingAndListening: success
,ok 149 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 37. Can call start/stopUpdateAdvertisingAndListening
,2016-04-01 23:51:54.229 ThaliTest[327:164135] jxcore: startUpdateAdvertisingAndListening
,2016-04-01 23:51:54.230 ThaliTest[327:164135] server: starting 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:4
,2016-04-01 23:51:54.232 ThaliTest[327:164135] multipeer manager: start client restart timer: 0x1567ce10
2016-04-01 23:51:54.232 ThaliTest[327:164135] THEMultipeerManager initialized peer 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:4
2016-04-01 23:51:54.232 ThaliTest[327:164135] jxcore: startUpdateAdvertisingAndListening: success
,ok 150 Can call startUpdateAdvertisingAndListening without error
,2016-04-01 23:51:54.235 ThaliTest[327:164135] jxcore: stopAdvertisingAndListening
2016-04-01 23:51:54.236 ThaliTest[327:164135] THEMultipeerManager stopping peer
,2016-04-01 23:51:54.237 ThaliTest[327:164135] multipeer manager: stop client timer
2016-04-01 23:51:54.238 ThaliTest[327:164135] jxcore: stopAdvertisingAndListening: success
ok 151 Can call stopAdvertisingAndListening without error
,# teardown
,2016-04-01 23:51:54.513 ThaliTest[327:164135] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-01 23:51:54.516 ThaliTest[327:164135] jxcore: stopListeningForAdvertisements: success
,ok 152 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-01 23:51:54.519 ThaliTest[327:164135] jxcore: stopAdvertisingAndListening
,2016-04-01 23:51:54.519 ThaliTest[327:164135] THEMultipeerManager stopping peer
,2016-04-01 23:51:54.520 ThaliTest[327:164135] jxcore: stopAdvertisingAndListening: success
,ok 153 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-04-01 23:51:55.112 ThaliTest[327:164135] jxcore: startUpdateAdvertisingAndListening
,2016-04-01 23:51:55.113 ThaliTest[327:164135] server: starting 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:5
,2016-04-01 23:51:55.114 ThaliTest[327:164135] multipeer manager: start client restart timer: 0x1567ce10
2016-04-01 23:51:55.114 ThaliTest[327:164135] THEMultipeerManager initialized peer 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:5
2016-04-01 23:51:55.115 Thal,iTest[327:164135] jxcore: startUpdateAdvertisingAndListening: success
ok 154 Can call startUpdateAdvertisingAndListening without error
,2016-04-01 23:51:55.118 ThaliTest[327:164135] jxcore: startUpdateAdvertisingAndListening
2016-04-01 23:51:55.118 ThaliTest[327:164135] THEMultipeerManager stopping peer
2016-04-01 23:51:55.118 ThaliTest[327:164135] multipeer manager: stop client timer
2,016-04-01 23:51:55.119 ThaliTest[327:164135] server: starting 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:6
2016-04-01 23:51:55.120 ThaliTest[327:164135] multipeer manager: start client restart timer: 0x1567ce10
2016-04-01 23:51:55.120 ThaliTest[327:164135] THE,MultipeerManager initialized peer 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:6
2016-04-01 23:51:55.120 ThaliTest[327:164135] jxcore: startUpdateAdvertisingAndListening: success
ok 155 Can call startUpdateAdvertisingAndListening twice without error
# teardown,
,2016-04-01 23:51:55.565 ThaliTest[327:164135] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-01 23:51:55.567 ThaliTest[327:164135] jxcore: stopListeningForAdvertisements: success
,ok 156 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-01 23:51:55.570 ThaliTest[327:164135] jxcore: stopAdvertisingAndListening
,2016-04-01 23:51:55.570 ThaliTest[327:164135] THEMultipeerManager stopping peer
,2016-04-01 23:51:55.571 ThaliTest[327:164135] multipeer manager: stop client timer
2016-04-01 23:51:55.572 ThaliTest[327:164135] jxcore: stopAdvertisingAndListening: success
ok 157 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,2016-04-01 23:51:56.143 ThaliTest[327:164135] jxcore: stopAdvertisingAndListening
,2016-04-01 23:51:56.144 ThaliTest[327:164135] THEMultipeerManager stopping peer
,2016-04-01 23:51:56.144 ThaliTest[327:164135] jxcore: stopAdvertisingAndListening: success
,ok 158 Can call startUpdateAdvertisingAndListening without error
,2016-04-01 23:51:56.147 ThaliTest[327:164135] jxcore: stopAdvertisingAndListening
,2016-04-01 23:51:56.147 ThaliTest[327:164135] THEMultipeerManager stopping peer
,2016-04-01 23:51:56.148 ThaliTest[327:164135] jxcore: stopAdvertisingAndListening: success
,ok 159 Can call stopAdvertisingAndListening without error
,# teardown
,2016-04-01 23:51:58.290 ThaliTest[327:164135] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-01 23:51:58.292 ThaliTest[327:164135] jxcore: stopListeningForAdvertisements: success
,ok 160 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-01 23:51:58.295 ThaliTest[327:164135] jxcore: stopAdvertisingAndListening
,2016-04-01 23:51:58.295 ThaliTest[327:164135] THEMultipeerManager stopping peer
,2016-04-01 23:51:58.296 ThaliTest[327:164135] jxcore: stopAdvertisingAndListening: success
,ok 161 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 40. cannot call connect when start listening for advertisements is not active
,2016-04-01 23:51:58.738 ThaliTest[327:164135] jxcore: connect foo
,2016-04-01 23:51:58.739 ThaliTest[327:164135] jxcore: connect: fail: Start browsing first
,not ok 162 got right error
,  ---
,    operator: equal
,    expected: 'startListeningForAdvertisements is not active'
,    actual:   'Start browsing first'
,  ...
,# teardown
,2016-04-01 23:51:58.876 ThaliTest[327:164135] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-01 23:51:58.878 ThaliTest[327:164135] jxcore: stopListeningForAdvertisements: success
,ok 163 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-01 23:51:58.881 ThaliTest[327:164135] jxcore: stopAdvertisingAndListening
,2016-04-01 23:51:58.881 ThaliTest[327:164135] THEMultipeerManager stopping peer
,2016-04-01 23:51:58.882 ThaliTest[327:164135] jxcore: stopAdvertisingAndListening: success
,ok 164 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 41. peerAvailabilityChange is called
,2016-04-01 23:51:59.924 ThaliTest[327:164135] jxcore: startUpdateAdvertisingAndListening
,2016-04-01 23:51:59.925 ThaliTest[327:164135] server: starting 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:7
,2016-04-01 23:51:59.926 ThaliTest[327:164135] multipeer manager: start client restart timer: 0x1567ce10
2016-04-01 23:51:59.926 ThaliTest[327:164135] THEMultipeerManager initialized peer 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:7
2016-04-01 23:51:59.926 ThaliTest[327:164135] jxcore: startUpdateAdvertisingAndListening: success
ok 165 Can call startUpdateAdvertisingAndListeningwithout error
,2016-04-01 23:51:59.930 ThaliTest[327:164135] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
,2016-04-01 23:51:59.936 ThaliTest[327:164135] jxcore: startListeningForAdvertisements: success
,ok 166 Can call startListeningForAdvertisements without error
,2016-04-01 23:52:01.941 ThaliTest[327:163918] client: found new peer: BC3134AD-A0D1-47B0-885A-5F5313680802:7
,2016-04-01 23:52:01.944 ThaliTest[327:163918] client: found new peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:7
2016-04-01 23:52:01.945 ThaliTest[327:163918] client: found new peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:7
ok 167 peers must be an array
,ok 168 peers must not be zero-length
ok 169 peer must have peerIdentifier
,ok 170 peerIdentifier must be a string
,ok 171 peer must have peerAvailable
,ok 172 peer must have pleaseConnect
,# teardown
,2016-04-01 23:52:07.001 ThaliTest[327:164135] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-01 23:52:07.004 ThaliTest[327:164135] jxcore: stopListeningForAdvertisements: success
,ok 173 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-01 23:52:07.007 ThaliTest[327:164135] jxcore: stopAdvertisingAndListening
2016-04-01 23:52:07.007 ThaliTest[327:164135] THEMultipeerManager stopping peer
,2016-04-01 23:52:07.008 ThaliTest[327:164135] multipeer manager: stop client timer
2016-04-01 23:52:07.009 ThaliTest[327:164135] jxcore: stopAdvertisingAndListening: success
,ok 174 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 42. Can connect to a remote peer
,2016-04-01 23:52:25.646 ThaliTest[327:164135] jxcore: startUpdateAdvertisingAndListening
,2016-04-01 23:52:25.647 ThaliTest[327:164135] server: starting 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
,2016-04-01 23:52:25.648 ThaliTest[327:164135] multipeer manager: start client restart timer: 0x1567ce10
2016-04-01 23:52:25.649 ThaliTest[327:164135] THEMultipeerManager initialized peer 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
,2016-04-01 23:52:25.649 ThaliTest[327:164135] jxcore: startUpdateAdvertisingAndListening: success
,ok 175 Can call startUpdateAdvertisingAndListening without error
2016-04-01 23:52:25.652 ThaliTest[327:164135] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-04-01 23:52:25.657 ThaliTest[327:164135] jxcore: startListeningForAdvertisements: success
ok 176 Can call startListeningForAdvertisements without error
,2016-04-01 23:52:25.665 ThaliTest[327:163918] client: found new peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:7
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"53FC597F-8F79-47DA-ABAE-0C427F412EFF:7","pleaseConnect":0}]
,2016-04-01 23:52:25.669 ThaliTest[327:164135] jxcore: connect 53FC597F-8F79-47DA-ABAE-0C427F412EFF:7
,2016-04-01 23:52:25.670 ThaliTest[327:164135] client: server will connect
,2016-04-01 23:52:25.671 ThaliTest[327:164135] client session: reverseConnect
,2016-04-01 23:52:25.671 ThaliTest[327:164135] client session: stateChange:0->1 53FC597F-8F79-47DA-ABAE-0C427F412EFF:7
,2016-04-01 23:52:26.721 ThaliTest[327:163918] client: found new peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:7
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"EEA4391C-4C5F-40D5-B71D-C147ED7B0517:7","pleaseConnect":0}]
,2016-04-01 23:52:28.411 ThaliTest[327:163918] multipeer session: reset timer
,2016-04-01 23:52:28.412 ThaliTest[327:163918] server session: connect
2016-04-01 23:52:28.412 ThaliTest[327:163918] server session: stateChange:0->1 53FC597F-8F79-47DA-ABAE-0C427F412EFF:8
,2016-04-01 23:52:28.419 ThaliTest[327:163918] server: accepting invitation 53FC597F-8F79-47DA-ABAE-0C427F412EFF
,2016-04-01 23:52:28.437 ThaliTest[327:164787] client session: not connected 53FC597F-8F79-47DA-ABAE-0C427F412EFF:7
2016-04-01 23:52:28.438 ThaliTest[327:164787] client session: onLinkFailure: 53FC597F-8F79-47DA-ABAE-0C427F412EFF
,2016-04-01 23:52:28.438 ThaliTest[327:164787] client session: disconnect
,2016-04-01 23:52:28.439 ThaliTest[327:164787] client session: stateChange:1->0 53FC597F-8F79-47DA-ABAE-0C427F412EFF:7
2016-04-01 23:52:28.440 ThaliTest[327:164787] client session: no connect callback (server initiated)
,2016-04-01 23:52:29.739 ThaliTest[327:163918] client: found new peer: BC3134AD-A0D1-47B0-885A-5F5313680802:8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"BC3134AD-A0D1-47B0-885A-5F5313680802:8","pleaseConnect":0}]
,2016-04-01 23:52:31.233 ThaliTest[327:164810] server session: p2p link connected
,2016-04-01 23:52:31.240 ThaliTest[327:163918] server relay: connected (to port: 50663)
,2016-04-01 23:52:31.242 ThaliTest[327:163918] server session: stateChange:1->2 53FC597F-8F79-47DA-ABAE-0C427F412EFF:8
,2016-04-01 23:52:31.243 ThaliTest[327:163918] jxcore: connect: success
,INFO testThaliMobileNative: 
,ok 177 Must have listeningPort
,ok 178 listeningPort must be a number
,ok 179 Connection must have clientPort
,ok 180 clientPort must be a number
,ok 181 Connection must have serverPort
,ok 182 serverPort must be a number
,ok 183 reverse connection must have clientPort != 0
,ok 184 reverse connection must have serverPort != 0
,# teardown
,2016-04-01 23:52:45.650 ThaliTest[327:163918] multipeer manager: restart client
,2016-04-01 23:52:45.675 ThaliTest[327:163918] client: found updated peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:8
,2016-04-01 23:52:45.676 ThaliTest[327:163918] client: found updated peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:8
,2016-04-01 23:52:45.679 ThaliTest[327:163918] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"EEA4391C-4C5F-40D5-B71D-C147ED7B0517:8","pleaseConnect":0}]
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"53FC597F-8F79-47DA-ABAE-0C427F412EFF:8","pleaseConnect":0}]
,2016-04-01 23:53:05.650 ThaliTest[327:163918] multipeer manager: restart client
,2016-04-01 23:53:05.680 ThaliTest[327:163918] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:8
2016-04-01 23:53:05.680 ThaliTest[327:163918] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:8
2016-04-01 23:53:05.680 ThaliTest[327:163918] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:8
,2016-04-01 23:53:25.650 ThaliTest[327:163918] multipeer manager: restart client
,2016-04-01 23:53:25.681 ThaliTest[327:163918] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:8
2016-04-01 23:53:25.681 ThaliTest[327:163918] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:8
2016-04-01 23:53:25.681 Th,aliTest[327:163918] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:8
,2016-04-01 23:53:36.225 ThaliTest[327:164135] jxcore: stopListeningForAdvertisements
2016-04-01 23:53:36.226 ThaliTest[327:163918] server relay: socket disconnected
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-01 23:53:36.227 ThaliTest[327:164135] jxcore: stopListeningForAdvertisements: success
2016-04-01 23:53:36.228 ThaliTest[327:163918] server relay: 0x174a0c40 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by re,mote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,ok 185 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-01 23:53:36.231 ThaliTest[327:164135] jxcore: stopAdvertisingAndListening
,2016-04-01 23:53:36.231 ThaliTest[327:164135] THEMultipeerManager stopping peer
,2016-04-01 23:53:36.232 ThaliTest[327:164135] server session: disconnect
2016-04-01 23:53:36.233 ThaliTest[327:164135] server session: stateChange:2->0 53FC597F-8F79-47DA-ABAE-0C427F412EFF:8
,2016-04-01 23:53:36.246 ThaliTest[327:164135] multipeer manager: stop client timer
2016-04-01 23:53:36.246 ThaliTest[327:164135] jxcore: stopAdvertisingAndListening: success
ok 186 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 43. Get error when trying to double connect to a peer
,2016-04-01 23:53:37.320 ThaliTest[327:164135] jxcore: startUpdateAdvertisingAndListening
,2016-04-01 23:53:37.321 ThaliTest[327:164135] server: starting 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-01 23:53:37.322 ThaliTest[327:164135] multipeer manager: start client restart timer: 0x1567ce10
2016-04-01 23:53:37.323 ThaliTest[327:164135] THEMultipeerManager initialized peer 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-01 23:53:37.323 ThaliTest[327:164135] jxcore: startUpdateAdvertisingAndListening: success
ok 187 Can call startUpdateAdvertisingAndListening without error
,2016-04-01 23:53:37.325 ThaliTest[327:164135] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-04-01 23:53:37.331 ThaliTest[327:164135] jxcore: startListeningForAdvertisements: success
ok 188 Can call startListeningForAdvertisements without error
,2016-04-01 23:53:37.372 ThaliTest[327:163918] client: found new peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:8
,2016-04-01 23:53:37.373 ThaliTest[327:163918] client: found new peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:8
,2016-04-01 23:53:37.375 ThaliTest[327:163918] client: found new peer: BC3134AD-A0D1-47B0-885A-5F5313680802:8
2016-04-01 23:53:37.376 ThaliTest[327:164135] jxcore: connect 53FC597F-8F79-47DA-ABAE-0C427F412EFF:8
2016-04-01 23:53:37.377 ThaliTest[327:164135,] client: server will connect
2016-04-01 23:53:37.377 ThaliTest[327:164135] client session: reverseConnect
,2016-04-01 23:53:37.378 ThaliTest[327:164135] client session: stateChange:0->1 53FC597F-8F79-47DA-ABAE-0C427F412EFF:8
,2016-04-01 23:53:38.055 ThaliTest[327:164939] client session: not connected 53FC597F-8F79-47DA-ABAE-0C427F412EFF:8
2016-04-01 23:53:38.055 ThaliTest[327:164939] client session: onLinkFailure: 53FC597F-8F79-47DA-ABAE-0C427F412EFF
2016-04-01 23:53:38.055 ThaliTest[327:164939] client session: disconnect
,2016-04-01 23:53:38.057 ThaliTest[327:164939] client session: stateChange:1->0 53FC597F-8F79-47DA-ABAE-0C427F412EFF:8
,2016-04-01 23:53:38.059 ThaliTest[327:164939] client session: no connect callback (server initiated)
,2016-04-01 23:53:38.657 ThaliTest[327:163918] multipeer session: reset timer
2016-04-01 23:53:38.658 ThaliTest[327:163918] server: rejecting invitation from EEA4391C-4C5F-40D5-B71D-C147ED7B0517 due to previous generation (0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9 != 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8)
,2016-04-01 23:53:38.708 ThaliTest[327:163918] multipeer session: reset timer
,2016-04-01 23:53:38.709 ThaliTest[327:163918] server: rejecting invitation from BC3134AD-A0D1-47B0-885A-5F5313680802 due to previous generation (0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9 != 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8)
,2016-04-01 23:53:41.780 ThaliTest[327:163918] multipeer session: reset timer
2016-04-01 23:53:41.780 ThaliTest[327:163918] server: disconnecting to refresh session (EEA4391C-4C5F-40D5-B71D-C147ED7B0517)
2016-04-01 23:53:41.781 ThaliTest[327:163918] serve,r: rejecting invitation from EEA4391C-4C5F-40D5-B71D-C147ED7B0517 due to previous generation (0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9 != 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8)
,2016-04-01 23:53:42.588 ThaliTest[327:163918] multipeer session: reset timer
,2016-04-01 23:53:42.588 ThaliTest[327:163918] server: disconnecting to refresh session (BC3134AD-A0D1-47B0-885A-5F5313680802)
,2016-04-01 23:53:42.588 ThaliTest[327:163918] server: rejecting invitation from BC3134AD-A0D1-47B0-885A-5F5313680802 due to previous generation (0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9 != 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8)
,2016-04-01 23:53:45.455 ThaliTest[327:163918] multipeer session: reset timer
2016-04-01 23:53:45.455 ThaliTest[327:163918] server: disconnecting to refresh session (EEA4391C-4C5F-40D5-B71D-C147ED7B0517)
2016-04-01 23:53:45.455 ThaliTest[327:163918] serve,r: rejecting invitation from EEA4391C-4C5F-40D5-B71D-C147ED7B0517 due to previous generation (0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9 != 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8)
,2016-04-01 23:53:47.379 ThaliTest[327:163918] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-04-01 23:53:47.500 ThaliTest[327:163918] multipeer session: reset timer
2016-04-01 23:53:47.501 ThaliTest[327:163918] server: disconnecting to refresh session (BC3134AD-A0D1-47B0-885A-5F5313680802)
,2016-04-01 23:53:47.501 ThaliTest[327:163918] server: rejecting invitation from BC3134AD-A0D1-47B0-885A-5F5313680802 due to previous generation (0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9 != 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8)
,2016-04-01 23:53:48.964 ThaliTest[327:163918] multipeer session: reset timer
,2016-04-01 23:53:48.965 ThaliTest[327:163918] server: disconnecting to refresh session (EEA4391C-4C5F-40D5-B71D-C147ED7B0517)
,2016-04-01 23:53:48.965 ThaliTest[327:163918] server: rejecting invitation from EEA4391C-4C5F-40D5-B71D-C147ED7B0517 due to previous generation (0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9 != 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8)
,2016-04-01 23:53:50.387 ThaliTest[327:164135] jxcore: connect 53FC597F-8F79-47DA-ABAE-0C427F412EFF:8
,2016-04-01 23:53:50.388 ThaliTest[327:164135] client: server will connect
,2016-04-01 23:53:50.389 ThaliTest[327:164135] client session: reverseConnect
2016-04-01 23:53:50.389 ThaliTest[327:164135] client session: stateChange:0->1 53FC597F-8F79-47DA-ABAE-0C427F412EFF:8
,2016-04-01 23:53:50.586 ThaliTest[327:163918] multipeer session: reset timer
2016-04-01 23:53:50.586 ThaliTest[327:163918] server: disconnecting to refresh session (BC3134AD-A0D1-47B0-885A-5F5313680802)
2016-04-01 23:53:50.586 ThaliTest[327:163918] serve,r: rejecting invitation from BC3134AD-A0D1-47B0-885A-5F5313680802 due to previous generation (0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9 != 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8)
,2016-04-01 23:53:50.644 ThaliTest[327:164939] client session: not connected 53FC597F-8F79-47DA-ABAE-0C427F412EFF:8
2016-04-01 23:53:50.645 ThaliTest[327:164939] client session: onLinkFailure: 53FC597F-8F79-47DA-ABAE-0C427F412EFF
2016-04-01 23:53:50.645 ThaliTest[327:164939] client session: disconnect
,2016-04-01 23:53:50.645 ThaliTest[327:164939] client session: stateChange:1->0 53FC597F-8F79-47DA-ABAE-0C427F412EFF:8
,2016-04-01 23:53:50.647 ThaliTest[327:164939] client session: no connect callback (server initiated)
,2016-04-01 23:53:52.103 ThaliTest[327:163918] multipeer session: reset timer
,2016-04-01 23:53:52.104 ThaliTest[327:163918] server: disconnecting to refresh session (EEA4391C-4C5F-40D5-B71D-C147ED7B0517)
2016-04-01 23:53:52.104 ThaliTest[327:163918] server: rejecting invitation from EEA4391C-4C5F-40D5-B71D-C147ED7B0517 due to previous generation (0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9 != 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8)
,2016-04-01 23:53:53.728 ThaliTest[327:163918] multipeer session: reset timer
2016-04-01 23:53:53.729 ThaliTest[327:163918] server: disconnecting to refresh session (BC3134AD-A0D1-47B0-885A-5F5313680802)
2016-04-01 23:53:53.729 ThaliTest[327:163918] serve,r: rejecting invitation from BC3134AD-A0D1-47B0-885A-5F5313680802 due to previous generation (0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9 != 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8)
,2016-04-01 23:53:55.303 ThaliTest[327:163918] multipeer session: reset timer
,2016-04-01 23:53:55.305 ThaliTest[327:163918] server: disconnecting to refresh session (EEA4391C-4C5F-40D5-B71D-C147ED7B0517)
2016-04-01 23:53:55.305 ThaliTest[327:163918] server: rejecting invitation from EEA4391C-4C5F-40D5-B71D-C147ED7B0517 due to previous generation (0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9 != 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8)
,2016-04-01 23:53:56.822 ThaliTest[327:163918] multipeer session: reset timer
2016-04-01 23:53:56.823 ThaliTest[327:163918] server: disconnecting to refresh session (BC3134AD-A0D1-47B0-885A-5F5313680802)
2016-04-01 23:53:56.823 ThaliTest[327:163918] serve,r: rejecting invitation from BC3134AD-A0D1-47B0-885A-5F5313680802 due to previous generation (0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9 != 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8)
,2016-04-01 23:53:57.324 ThaliTest[327:163918] multipeer manager: restart client
,2016-04-01 23:53:57.347 ThaliTest[327:163918] client: found updated peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-01 23:53:57.348 ThaliTest[327:163918] client: found updated peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-01 23:53:57.348 ThaliTest[327:163918] client: found updated peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-01 23:53:58.438 ThaliTest[327:163918] multipeer session: reset timer
2016-04-01 23:53:58.438 ThaliTest[327:163918] server: disconnecting to refresh session (EEA4391C-4C5F-40D5-B71D-C147ED7B0517)
2016-04-01 23:53:58.439 ThaliTest[327:163918] serve,r: rejecting invitation from EEA4391C-4C5F-40D5-B71D-C147ED7B0517 due to previous generation (0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9 != 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8)
,2016-04-01 23:53:59.974 ThaliTest[327:163918] multipeer session: reset timer
2016-04-01 23:53:59.974 ThaliTest[327:163918] server: disconnecting to refresh session (BC3134AD-A0D1-47B0-885A-5F5313680802)
2016-04-01 23:53:59.975 ThaliTest[327:163918] serve,r: rejecting invitation from BC3134AD-A0D1-47B0-885A-5F5313680802 due to previous generation (0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9 != 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8)
,2016-04-01 23:54:00.390 ThaliTest[327:163918] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-04-01 23:54:01.579 ThaliTest[327:163918] multipeer session: reset timer
2016-04-01 23:54:01.580 ThaliTest[327:163918] server: disconnecting to refresh session (EEA4391C-4C5F-40D5-B71D-C147ED7B0517)
2016-04-01 23:54:01.580 ThaliTest[327:163918] serve,r: rejecting invitation from EEA4391C-4C5F-40D5-B71D-C147ED7B0517 due to previous generation (0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9 != 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8)
,2016-04-01 23:54:03.397 ThaliTest[327:164135] jxcore: connect 53FC597F-8F79-47DA-ABAE-0C427F412EFF:8
,2016-04-01 23:54:03.398 ThaliTest[327:164135] client: server will connect
,2016-04-01 23:54:03.399 ThaliTest[327:164135] client session: reverseConnect
,2016-04-01 23:54:03.399 ThaliTest[327:164135] client session: stateChange:0->1 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
,2016-04-01 23:54:03.607 ThaliTest[327:163918] multipeer session: reset timer
2016-04-01 23:54:03.607 ThaliTest[327:163918] server: disconnecting to refresh session (BC3134AD-A0D1-47B0-885A-5F5313680802)
,2016-04-01 23:54:03.608 ThaliTest[327:163918] server: rejecting invitation from BC3134AD-A0D1-47B0-885A-5F5313680802 due to previous generation (0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9 != 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8)
,2016-04-01 23:54:03.778 ThaliTest[327:165084] client session: not connected 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
,2016-04-01 23:54:03.778 ThaliTest[327:165084] client session: onLinkFailure: 53FC597F-8F79-47DA-ABAE-0C427F412EFF
2016-04-01 23:54:03.779 ThaliTest[327:165084] client session: disconnect
,2016-04-01 23:54:03.779 ThaliTest[327:165084] client session: stateChange:1->0 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
,2016-04-01 23:54:03.782 ThaliTest[327:165084] client session: no connect callback (server initiated)
,2016-04-01 23:54:04.693 ThaliTest[327:163918] multipeer session: reset timer
2016-04-01 23:54:04.694 ThaliTest[327:163918] server: disconnecting to refresh session (EEA4391C-4C5F-40D5-B71D-C147ED7B0517)
2016-04-01 23:54:04.694 ThaliTest[327:163918] server: rejecting invitation from EEA4391C-4C5F-40D5-B71D-C147ED7B0517 due to previous generation (0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9 != 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8)
,2016-04-01 23:54:06.817 ThaliTest[327:163918] multipeer session: reset timer
,2016-04-01 23:54:06.818 ThaliTest[327:163918] server: disconnecting to refresh session (BC3134AD-A0D1-47B0-885A-5F5313680802)
,2016-04-01 23:54:06.818 ThaliTest[327:163918] server: rejecting invitation from BC3134AD-A0D1-47B0-885A-5F5313680802 due to previous generation (0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9 != 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8)
,2016-04-01 23:54:08.383 ThaliTest[327:163918] multipeer session: reset timer
,2016-04-01 23:54:08.384 ThaliTest[327:163918] server: disconnecting to refresh session (EEA4391C-4C5F-40D5-B71D-C147ED7B0517)
,2016-04-01 23:54:08.384 ThaliTest[327:163918] server: rejecting invitation from EEA4391C-4C5F-40D5-B71D-C147ED7B0517 due to previous generation (0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9 != 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8)
,2016-04-01 23:54:09.924 ThaliTest[327:163918] multipeer session: reset timer
,2016-04-01 23:54:09.925 ThaliTest[327:163918] server: disconnecting to refresh session (BC3134AD-A0D1-47B0-885A-5F5313680802)
,2016-04-01 23:54:09.925 ThaliTest[327:163918] server: rejecting invitation from BC3134AD-A0D1-47B0-885A-5F5313680802 due to previous generation (0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9 != 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8)
,2016-04-01 23:54:13.400 ThaliTest[327:163918] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-04-01 23:54:16.407 ThaliTest[327:164135] jxcore: connect 53FC597F-8F79-47DA-ABAE-0C427F412EFF:8
,2016-04-01 23:54:16.408 ThaliTest[327:164135] client: server will connect
,2016-04-01 23:54:16.409 ThaliTest[327:164135] client session: reverseConnect
2016-04-01 23:54:16.409 ThaliTest[327:164135] client session: stateChange:0->1 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
,2016-04-01 23:54:17.171 ThaliTest[327:165112] client session: not connected 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
,2016-04-01 23:54:17.172 ThaliTest[327:165112] client session: onLinkFailure: 53FC597F-8F79-47DA-ABAE-0C427F412EFF
2016-04-01 23:54:17.172 ThaliTest[327:165112] client session: disconnect
,2016-04-01 23:54:17.172 ThaliTest[327:165112] client session: stateChange:1->0 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
,2016-04-01 23:54:17.173 ThaliTest[327:165112] client session: no connect callback (server initiated)
,2016-04-01 23:54:17.324 ThaliTest[327:163918] multipeer manager: restart client
,2016-04-01 23:54:17.356 ThaliTest[327:163918] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-01 23:54:17.357 ThaliTest[327:163918] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-01 23:54:17.357 Th,aliTest[327:163918] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
,2016-04-01 23:54:26.410 ThaliTest[327:163918] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-04-01 23:54:29.422 ThaliTest[327:164135] jxcore: connect 53FC597F-8F79-47DA-ABAE-0C427F412EFF:8
,2016-04-01 23:54:29.423 ThaliTest[327:164135] client: server will connect
2016-04-01 23:54:29.424 ThaliTest[327:164135] client session: reverseConnect
2016-04-01 23:54:29.424 ThaliTest[327:164135] client session: stateChange:0->1 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
,2016-04-01 23:54:29.554 ThaliTest[327:165216] client session: not connected 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-01 23:54:29.555 ThaliTest[327:165216] client session: onLinkFailure: 53FC597F-8F79-47DA-ABAE-0C427F412EFF
,2016-04-01 23:54:29.555 ThaliTest[327:165216] client session: disconnect
2016-04-01 23:54:29.555 ThaliTest[327:165216] client session: stateChange:1->0 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-01 23:54:29.557 ThaliTest[327:165216] client session: no connect callback (server initiated)
,2016-04-01 23:54:37.324 ThaliTest[327:163918] multipeer manager: restart client
,2016-04-01 23:54:37.351 ThaliTest[327:163918] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-01 23:54:37.352 ThaliTest[327:163918] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-01 23:54:37.353 Th,aliTest[327:163918] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
,2016-04-01 23:54:39.425 ThaliTest[327:163918] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-04-01 23:54:42.431 ThaliTest[327:164135] jxcore: connect 53FC597F-8F79-47DA-ABAE-0C427F412EFF:8
,2016-04-01 23:54:42.432 ThaliTest[327:164135] client: server will connect
2016-04-01 23:54:42.433 ThaliTest[327:164135] client session: reverseConnect
,2016-04-01 23:54:42.434 ThaliTest[327:164135] client session: stateChange:0->1 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
,2016-04-01 23:54:43.083 ThaliTest[327:165084] client session: not connected 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-01 23:54:43.084 ThaliTest[327:165084] client session: onLinkFailure: 53FC597F-8F79-47DA-ABAE-0C427F412EFF
2016-04-01 23:54:43.084 ThaliTest[327:165084] client session: disconnect
,2016-04-01 23:54:43.084 ThaliTest[327:165084] client session: stateChange:1->0 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-01 23:54:43.085 ThaliTest[327:165084] client session: no connect callback (server initiated)
,2016-04-01 23:54:52.434 ThaliTest[327:163918] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-04-01 23:54:55.448 ThaliTest[327:164135] jxcore: connect 53FC597F-8F79-47DA-ABAE-0C427F412EFF:8
2016-04-01 23:54:55.448 ThaliTest[327:164135] client: server will connect
,2016-04-01 23:54:55.449 ThaliTest[327:164135] client session: reverseConnect
2016-04-01 23:54:55.450 ThaliTest[327:164135] client session: stateChange:0->1 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
,2016-04-01 23:54:55.708 ThaliTest[327:165346] client session: not connected 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-01 23:54:55.708 ThaliTest[327:165346] client session: onLinkFailure: 53FC597F-8F79-47DA-ABAE-0C427F412EFF
2016-04-01 23:54:55.708 T,haliTest[327:165346] client session: disconnect
2016-04-01 23:54:55.709 ThaliTest[327:165346] client session: stateChange:1->0 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-01 23:54:55.710 ThaliTest[327:165346] client session: no connect callback (server initiated)
,2016-04-01 23:54:57.324 ThaliTest[327:163918] multipeer manager: restart client
,2016-04-01 23:54:57.352 ThaliTest[327:163918] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-01 23:54:57.353 ThaliTest[327:163918] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-01 23:54:57.354 Th,aliTest[327:163918] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-01 23:55:05.450 ThaliTest[327:163918] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-04-01 23:55:08.465 ThaliTest[327:164135] jxcore: connect 53FC597F-8F79-47DA-ABAE-0C427F412EFF:8
,2016-04-01 23:55:08.465 ThaliTest[327:164135] client: server will connect
,2016-04-01 23:55:08.466 ThaliTest[327:164135] client session: reverseConnect
,2016-04-01 23:55:08.467 ThaliTest[327:164135] client session: stateChange:0->1 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
,2016-04-01 23:55:08.746 ThaliTest[327:165349] client session: not connected 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-01 23:55:08.747 ThaliTest[327:165349] client session: onLinkFailure: 53FC597F-8F79-47DA-ABAE-0C427F412EFF
,2016-04-01 23:55:08.748 ThaliTest[327:165349] client session: disconnect
2016-04-01 23:55:08.748 ThaliTest[327:165349] client session: stateChange:1->0 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
,2016-04-01 23:55:08.749 ThaliTest[327:165349] client session: no connect callback (server initiated)
,2016-04-01 23:55:17.324 ThaliTest[327:163918] multipeer manager: restart client
,2016-04-01 23:55:17.353 ThaliTest[327:163918] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
,2016-04-01 23:55:17.355 ThaliTest[327:163918] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-01 23:55:17.356 ThaliTest[327:163918] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-01 23:55:18.467 ThaliTest[327:163918] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-04-01 23:55:21.474 ThaliTest[327:164135] jxcore: connect 53FC597F-8F79-47DA-ABAE-0C427F412EFF:8
,2016-04-01 23:55:21.475 ThaliTest[327:164135] client: server will connect
,2016-04-01 23:55:21.475 ThaliTest[327:164135] client session: reverseConnect
,2016-04-01 23:55:21.476 ThaliTest[327:164135] client session: stateChange:0->1 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
,2016-04-01 23:55:21.833 ThaliTest[327:165349] client session: not connected 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-01 23:55:21.834 ThaliTest[327:165349] client session: onLinkFailure: 53FC597F-8F79-47DA-ABAE-0C427F412EFF
2016-04-01 23:55:21.834 ThaliTest[327:165349] client session: disconnect
,2016-04-01 23:55:21.834 ThaliTest[327:165349] client session: stateChange:1->0 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
,2016-04-01 23:55:21.836 ThaliTest[327:165349] client session: no connect callback (server initiated)
,2016-04-01 23:55:31.476 ThaliTest[327:163918] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-04-01 23:55:34.491 ThaliTest[327:164135] jxcore: connect 53FC597F-8F79-47DA-ABAE-0C427F412EFF:8
,2016-04-01 23:55:34.491 ThaliTest[327:164135] client: server will connect
2016-04-01 23:55:34.492 ThaliTest[327:164135] client session: reverseConnect
2016-04-01 23:55:34.492 ThaliTest[327:164135] client session: stateChange:0->1 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
,2016-04-01 23:55:34.954 ThaliTest[327:165476] client session: not connected 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
,2016-04-01 23:55:34.956 ThaliTest[327:165476] client session: onLinkFailure: 53FC597F-8F79-47DA-ABAE-0C427F412EFF
2016-04-01 23:55:34.956 ThaliTest[327:165476] client session: disconnect
,2016-04-01 23:55:34.957 ThaliTest[327:165476] client session: stateChange:1->0 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
,2016-04-01 23:55:34.957 ThaliTest[327:165476] client session: no connect callback (server initiated)
,2016-04-01 23:55:37.324 ThaliTest[327:163918] multipeer manager: restart client
,2016-04-01 23:55:37.357 ThaliTest[327:163918] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-01 23:55:37.357 ThaliTest[327:163918] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-01 23:55:37.358 ThaliTest[327:163918] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-01 23:55:44.493 ThaliTest[327:163918] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,WARN testThaliMobileNative: Too many connect retries!
,2016-04-01 23:55:57.324 ThaliTest[327:163918] multipeer manager: restart client
,2016-04-01 23:55:57.355 ThaliTest[327:163918] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-01 23:55:57.356 ThaliTest[327:163918] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-01 23:55:57.356 Th,aliTest[327:163918] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-01 23:56:17.324 ThaliTest[327:163918] multipeer manager: restart client
,2016-04-01 23:56:17.356 ThaliTest[327:163918] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-01 23:56:17.357 ThaliTest[327:163918] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-01 23:56:17.357 ThaliTest[327:163918] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-01 23:56:37.324 ThaliTest[327:163918] multipeer manager: restart client
,2016-04-01 23:56:37.353 ThaliTest[327:163918] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-01 23:56:37.353 ThaliTest[327:163918] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-01 23:56:37.355 ThaliTest[327:163918] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-01 23:56:57.324 ThaliTest[327:163918] multipeer manager: restart client
,2016-04-01 23:56:57.351 ThaliTest[327:163918] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-01 23:56:57.352 ThaliTest[327:163918] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-01 23:56:57.352 ThaliTest[327:163918] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
,2016-04-01 23:57:17.324 ThaliTest[327:163918] multipeer manager: restart client
,2016-04-01 23:57:17.354 ThaliTest[327:163918] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-01 23:57:17.354 ThaliTest[327:163918] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-01 23:57:17.355 ThaliTest[327:163918] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-01 23:57:37.324 ThaliTest[327:163918] multipeer manager: restart client
,2016-04-01 23:57:37.355 ThaliTest[327:163918] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-01 23:57:37.355 ThaliTest[327:163918] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-01 23:57:37.356 ThaliTest[327:163918] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-01 23:57:57.324 ThaliTest[327:163918] multipeer manager: restart client
,2016-04-01 23:57:57.356 ThaliTest[327:163918] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-01 23:57:57.357 ThaliTest[327:163918] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-01 23:57:57.358 ThaliTest[327:163918] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
,2016-04-01 23:58:17.324 ThaliTest[327:163918] multipeer manager: restart client
,2016-04-01 23:58:17.355 ThaliTest[327:163918] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-01 23:58:17.356 ThaliTest[327:163918] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-01 23:58:17.356 ThaliTest[327:163918] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-01 23:58:37.324 ThaliTest[327:163918] multipeer manager: restart client
,2016-04-01 23:58:37.356 ThaliTest[327:163918] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-01 23:58:37.356 ThaliTest[327:163918] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-01 23:58:37.357 ThaliTest[327:163918] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-01 23:58:57.324 ThaliTest[327:163918] multipeer manager: restart client
,2016-04-01 23:58:57.354 ThaliTest[327:163918] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-01 23:58:57.355 ThaliTest[327:163918] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-01 23:58:57.355 Th,aliTest[327:163918] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-01 23:59:17.324 ThaliTest[327:163918] multipeer manager: restart client
,2016-04-01 23:59:17.356 ThaliTest[327:163918] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-01 23:59:17.356 ThaliTest[327:163918] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-01 23:59:17.357 ThaliTest[327:163918] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-01 23:59:37.324 ThaliTest[327:163918] multipeer manager: restart client
,2016-04-01 23:59:37.355 ThaliTest[327:163918] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-01 23:59:37.355 ThaliTest[327:163918] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-01 23:59:37.356 Th,aliTest[327:163918] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-01 23:59:57.324 ThaliTest[327:163918] multipeer manager: restart client
,2016-04-01 23:59:57.354 ThaliTest[327:163918] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-01 23:59:57.355 ThaliTest[327:163918] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-01 23:59:57.356 ThaliTest[327:163918] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-02 00:00:17.324 ThaliTest[327:163918] multipeer manager: restart client
,2016-04-02 00:00:17.354 ThaliTest[327:163918] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-02 00:00:17.354 ThaliTest[327:163918] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
,2016-04-02 00:00:17.355 ThaliTest[327:163918] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-02 00:00:37.324 ThaliTest[327:163918] multipeer manager: restart client
,2016-04-02 00:00:37.354 ThaliTest[327:163918] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-02 00:00:37.354 ThaliTest[327:163918] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-02 00:00:37.355 ThaliTest[327:163918] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-02 00:00:57.324 ThaliTest[327:163918] multipeer manager: restart client
,2016-04-02 00:00:57.356 ThaliTest[327:163918] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-02 00:00:57.357 ThaliTest[327:163918] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-02 00:00:57.357 Th,aliTest[327:163918] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-02 00:01:17.324 ThaliTest[327:163918] multipeer manager: restart client
,2016-04-02 00:01:17.352 ThaliTest[327:163918] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-02 00:01:17.353 ThaliTest[327:163918] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-02 00:01:17.353 ThaliTest[327:163918] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
,2016-04-02 00:01:37.324 ThaliTest[327:163918] multipeer manager: restart client
,2016-04-02 00:01:37.355 ThaliTest[327:163918] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-02 00:01:37.355 ThaliTest[327:163918] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-02 00:01:37.356 ThaliTest[327:163918] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-02 00:01:57.324 ThaliTest[327:163918] multipeer manager: restart client
,2016-04-02 00:01:57.355 ThaliTest[327:163918] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-02 00:01:57.355 ThaliTest[327:163918] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-02 00:01:57.355 ThaliTest[327:163918] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-02 00:02:17.324 ThaliTest[327:163918] multipeer manager: restart client
,2016-04-02 00:02:17.355 ThaliTest[327:163918] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-02 00:02:17.356 ThaliTest[327:163918] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
,2016-04-02 00:02:17.358 ThaliTest[327:163918] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-02 00:02:37.324 ThaliTest[327:163918] multipeer manager: restart client
,2016-04-02 00:02:37.356 ThaliTest[327:163918] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-02 00:02:37.356 ThaliTest[327:163918] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-02 00:02:37.357 ThaliTest[327:163918] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-02 00:02:57.324 ThaliTest[327:163918] multipeer manager: restart client
,2016-04-02 00:02:57.355 ThaliTest[327:163918] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-02 00:02:57.355 ThaliTest[327:163918] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-02 00:02:57.356 Th,aliTest[327:163918] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-02 00:03:17.324 ThaliTest[327:163918] multipeer manager: restart client
,2016-04-02 00:03:17.355 ThaliTest[327:163918] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-02 00:03:17.356 ThaliTest[327:163918] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-02 00:03:17.356 ThaliTest[327:163918] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-02 00:03:37.324 ThaliTest[327:163918] multipeer manager: restart client
,2016-04-02 00:03:37.355 ThaliTest[327:163918] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-02 00:03:37.355 ThaliTest[327:163918] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-02 00:03:37.356 ThaliTest[327:163918] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-02 00:03:57.324 ThaliTest[327:163918] multipeer manager: restart client
,2016-04-02 00:03:57.356 ThaliTest[327:163918] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-02 00:03:57.356 ThaliTest[327:163918] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-02 00:03:57.356 Th,aliTest[327:163918] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
,2016-04-02 00:04:17.324 ThaliTest[327:163918] multipeer manager: restart client
,2016-04-02 00:04:17.357 ThaliTest[327:163918] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-02 00:04:17.358 ThaliTest[327:163918] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-02 00:04:17.359 ThaliTest[327:163918] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
,2016-04-02 00:04:37.324 ThaliTest[327:163918] multipeer manager: restart client
,2016-04-02 00:04:37.354 ThaliTest[327:163918] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-02 00:04:37.355 ThaliTest[327:163918] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-02 00:04:37.356 Th,aliTest[327:163918] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
,2016-04-02 00:04:57.324 ThaliTest[327:163918] multipeer manager: restart client
,2016-04-02 00:04:57.356 ThaliTest[327:163918] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-02 00:04:57.356 ThaliTest[327:163918] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-02 00:04:57.357 Th,aliTest[327:163918] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-02 00:05:17.324 ThaliTest[327:163918] multipeer manager: restart client
,2016-04-02 00:05:17.355 ThaliTest[327:163918] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-02 00:05:17.355 ThaliTest[327:163918] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-02 00:05:17.356 ThaliTest[327:163918] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-02 00:05:37.324 ThaliTest[327:163918] multipeer manager: restart client
,2016-04-02 00:05:37.355 ThaliTest[327:163918] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-02 00:05:37.355 ThaliTest[327:163918] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-02 00:05:37.357 ThaliTest[327:163918] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-02 00:05:57.324 ThaliTest[327:163918] multipeer manager: restart client
,2016-04-02 00:05:57.354 ThaliTest[327:163918] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-02 00:05:57.355 ThaliTest[327:163918] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-02 00:05:57.355 ThaliTest[327:163918] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
,2016-04-02 00:06:17.324 ThaliTest[327:163918] multipeer manager: restart client
,2016-04-02 00:06:17.354 ThaliTest[327:163918] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-02 00:06:17.355 ThaliTest[327:163918] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-02 00:06:17.356 ThaliTest[327:163918] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-02 00:06:37.324 ThaliTest[327:163918] multipeer manager: restart client
,2016-04-02 00:06:37.353 ThaliTest[327:163918] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-02 00:06:37.354 ThaliTest[327:163918] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-02 00:06:37.354 ThaliTest[327:163918] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-02 00:06:57.324 ThaliTest[327:163918] multipeer manager: restart client
,2016-04-02 00:06:57.355 ThaliTest[327:163918] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-02 00:06:57.355 ThaliTest[327:163918] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-02 00:06:57.356 ThaliTest[327:163918] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-02 00:07:17.324 ThaliTest[327:163918] multipeer manager: restart client
,2016-04-02 00:07:17.352 ThaliTest[327:163918] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-02 00:07:17.353 ThaliTest[327:163918] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-02 00:07:17.353 ThaliTest[327:163918] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-02 00:07:37.324 ThaliTest[327:163918] multipeer manager: restart client
,2016-04-02 00:07:37.352 ThaliTest[327:163918] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-02 00:07:37.352 ThaliTest[327:163918] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-02 00:07:37.352 ThaliTest[327:163918] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-02 00:07:57.324 ThaliTest[327:163918] multipeer manager: restart client
,2016-04-02 00:07:57.355 ThaliTest[327:163918] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-02 00:07:57.355 ThaliTest[327:163918] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-02 00:07:57.356 ThaliTest[327:163918] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
,2016-04-02 00:08:17.324 ThaliTest[327:163918] multipeer manager: restart client
,2016-04-02 00:08:17.353 ThaliTest[327:163918] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-02 00:08:17.354 ThaliTest[327:163918] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-02 00:08:17.354 Th,aliTest[327:163918] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-02 00:08:37.324 ThaliTest[327:163918] multipeer manager: restart client
,2016-04-02 00:08:37.356 ThaliTest[327:163918] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-02 00:08:37.356 ThaliTest[327:163918] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-02 00:08:37.356 ThaliTest[327:163918] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-02 00:08:57.324 ThaliTest[327:163918] multipeer manager: restart client
,2016-04-02 00:08:57.356 ThaliTest[327:163918] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-02 00:08:57.357 ThaliTest[327:163918] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-02 00:08:57.357 ThaliTest[327:163918] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9

```
