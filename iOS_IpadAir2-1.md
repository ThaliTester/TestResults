#### Test 6568167646f0d89_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/6568167646f0d89/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/1795319D-2E8C-4EA8-A0A2-88986FB0612C/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/1795319D-2E8C-4EA8-A0A2-88986FB0612C/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/6568167646f0d89/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/6568167646f0d89/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/7139B316-B3A4-4AE9-82C3-F32FDD757C47/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51865"
,(lldb)     command script import "/tmp/1795319D-2E8C-4EA8-A0A2-88986FB0612C/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-04-07 21:52:05.497 ThaliTest[572:949464] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0C385F4E-3967-4B79-8134-5BF943863078/Library/Cookies/Cookies.binarycookies
,2016-04-07 21:52:05.839 ThaliTest[572:949464] Apache Cordova native platform version 4.1.0 is starting.
,2016-04-07 21:52:05.840 ThaliTest[572:949464] Multi-tasking -> Device: YES, App: YES
,2016-04-07 21:52:05.858 ThaliTest[572:949464] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-04-07 21:52:07.644 ThaliTest[572:949464] Using UIWebView
,2016-04-07 21:52:07.651 ThaliTest[572:949464] [CDVTimer][handleopenurl] 0.532985ms
,2016-04-07 21:52:07.659 ThaliTest[572:949464] [CDVTimer][intentandnavigationfilter] 7.318020ms
,2016-04-07 21:52:07.660 ThaliTest[572:949464] [CDVTimer][gesturehandler] 0.340998ms
2016-04-07 21:52:07.660 ThaliTest[572:949464] [CDVTimer][TotalPluginStartup] 9.895027ms
,2016-04-07 21:52:13.989 ThaliTest[572:949464] Resetting plugins due to page load.
,2016-04-07 21:52:17.352 ThaliTest[572:949464] Finished load of: file:///var/mobile/Containers/Bundle/Application/7139B316-B3A4-4AE9-82C3-F32FDD757C47/ThaliTest.app/www/index.html
,2016-04-07 21:52:17.544 ThaliTest[572:949464] JXcore Cordova plugin initializing
,2016-04-07 21:52:17.545 ThaliTest[572:949678] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-04-07 21:52:24.012 ThaliTest[572:949678] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-04-07 21:52:24.013 ThaliTest[572:949678] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-04-07 21:52:24.013 ThaliTest[572:949678] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-04-07 21:52:24.015 ThaliTest[572:949678] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-IpadAir2-1
,WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7139B316-B3A4-4AE9-82C3-F32FDD757C47/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7139B316-B3A4-4AE9-82C3-F32FDD757C47/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7139B316-B3A4-4AE9-82C3-F32FDD757C47/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7139B316-B3A4-4AE9-82C3-F32FDD757C47/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7139B316-B3A4-4AE9-82C3-F32FDD757C47/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7139B316-B3A4-4AE9-82C3-F32FDD757C47/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7139B316-B3A4-4AE9-82C3-F32FDD757C47/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7139B316-B3A4-4AE9-82C3-F32FDD757C47/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7139B316-B3A4-4AE9-82C3-F32FDD757C47/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7139B316-B3A4-4AE9-82C3-F32FDD757C47/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7139B316-B3A4-4AE9-82C3-F32FDD757C47/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7139B316-B3A4-4AE9-82C3-F32FDD757C47/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7139B316-B3A4-4AE9-82C3-F32FDD757C47/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7139B316-B3A4-4AE9-82C3-F32FDD757C47/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7139B316-B3A4-4AE9-82C3-F32FDD757C47/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7139B316-B3A4-4AE9-82C3-F32FDD757C47/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7139B316-B3A4-4AE9-82C3-F32FDD757C47/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7139B316-B3A4-4AE9-82C3-F32FDD757C47/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7139B316-B3A4-4AE9-82C3-F32FDD757C47/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7139B316-B3A4-4AE9-82C3-F32FDD757C47/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7139B316-B3A4-4AE9-82C3-F32FDD757C47/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7139B316-B3A4-4AE9-82C3-F32FDD757C47/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-04-07 21:52:29.855 ThaliTest[572:949464] THREAD WARNING: ['JXcore'] took '5565.520996' ms. Plugin should use a background thread.
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51933
,ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51935
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
,DEBUG createNativeListener: listening 51938
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
,DEBUG createNativeListener: listening 51942
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
,DEBUG createNativeListener: listening 51947
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
,DEBUG createNativeListener: listening 51951
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
,DEBUG createNativeListener: listening 51955
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
,DEBUG createNativeListener: listening 51959
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
,DEBUG createNativeListener: listening 51963
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
,DEBUG createNativeListener: listening 52015
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
,DEBUG createNativeListener: listening 52019
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
,[{"uuid":"0a5569ba-1ed4-436a-9411-0f7974f7bbc6","data":"custom data"},{"uuid":"dcb5d381-cae6-4f05-8e4a-e2d4f542730f","data":"custom data"},{"uuid":"a01448f3-8faa-4a3b-be30-b4d35e539833","data":"custom data"},{"uuid":"6d9c6404-32a9-487f-ab25-46f5222cb94f","data":"custom data"}]
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
,DEBUG createNativeListener: listening 52029
,2016-04-07 21:54:37.134 ThaliTest[572:949678] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-07 21:54:37.136 ThaliTest[572:949678] jxcore: stopListeningForAdvertisements: success
,ok 91 error should be null
,ok 92 error should be null
,2016-04-07 21:54:37.140 ThaliTest[572:949678] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-07 21:54:37.142 ThaliTest[572:949678] jxcore: stopListeningForAdvertisements: success
,ok 93 error should be null
,ok 94 error should be null
,# teardown
,2016-04-07 21:54:37.220 ThaliTest[572:949678] jxcore: stopAdvertisingAndListening
,2016-04-07 21:54:37.220 ThaliTest[572:949678] THEMultipeerManager stopping peer
,2016-04-07 21:54:37.221 ThaliTest[572:949678] jxcore: stopAdvertisingAndListening: success
,2016-04-07 21:54:37.222 ThaliTest[572:949678] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-07 21:54:37.224 ThaliTest[572:949678] jxcore: stopListeningForAdvertisements: success
,ok 95 error should be null
,ok 96 error should be null
,# setup
,# 26. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 52031
,2016-04-07 21:54:37.411 ThaliTest[572:949678] jxcore: startListeningForAdvertisements
,2016-04-07 21:54:37.412 ThaliTest[572:949678] multipeer manager: start client restart timer: 0x15e79110
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-07 21:54:37.415 ThaliTest[572:949678] jxcore: startListeningForAdvertisements: success
,ok 97 error should be null
,ok 98 error should be null
,2016-04-07 21:54:37.438 ThaliTest[572:949678] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-07 21:54:37.441 ThaliTest[572:949678] jxcore: startListeningForAdvertisements: success
,ok 99 error should be null
,ok 100 error should be null
,# teardown
,2016-04-07 21:54:37.707 ThaliTest[572:949678] jxcore: stopAdvertisingAndListening
,2016-04-07 21:54:37.707 ThaliTest[572:949678] THEMultipeerManager stopping peer
,2016-04-07 21:54:37.708 ThaliTest[572:949678] jxcore: stopAdvertisingAndListening: success
,2016-04-07 21:54:37.709 ThaliTest[572:949678] jxcore: stopListeningForAdvertisements
2016-04-07 21:54:37.710 ThaliTest[572:949678] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-07 21:54:37.714 ThaliTest[572:949678] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 101 error should be null
,ok 102 error should be null
,# setup
,# 27. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 52033
,2016-04-07 21:54:38.202 ThaliTest[572:949678] jxcore: startUpdateAdvertisingAndListening
,2016-04-07 21:54:38.203 ThaliTest[572:949678] server: starting 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:1
,2016-04-07 21:54:38.204 ThaliTest[572:949678] multipeer manager: start client restart timer: 0x15e79110
2016-04-07 21:54:38.205 ThaliTest[572:949678] THEMultipeerManager initialized peer 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:1
,2016-04-07 21:54:38.205 ThaliTest[572:949678] jxcore: startUpdateAdvertisingAndListening: success
,ok 103 error should be null
,ok 104 error should be null
,2016-04-07 21:54:38.242 ThaliTest[572:949678] jxcore: startUpdateAdvertisingAndListening
,2016-04-07 21:54:38.243 ThaliTest[572:949678] THEMultipeerManager stopping peer
,2016-04-07 21:54:38.244 ThaliTest[572:949678] multipeer manager: stop client timer
2016-04-07 21:54:38.245 ThaliTest[572:949678] server: starting 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:2
,2016-04-07 21:54:38.248 ThaliTest[572:949678] multipeer manager: start client restart timer: 0x15e79110
2016-04-07 21:54:38.249 ThaliTest[572:949678] THEMultipeerManager initialized peer 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:2
2016-04-07 21:54:38.249 ThaliTest[572:949678] jxcore: startUpdateAdvertisingAndListening: success
,ok 105 error should be null
,ok 106 error should be null
,# teardown
,2016-04-07 21:54:38.371 ThaliTest[572:949678] jxcore: stopAdvertisingAndListening
,2016-04-07 21:54:38.371 ThaliTest[572:949678] THEMultipeerManager stopping peer
,2016-04-07 21:54:38.372 ThaliTest[572:949678] multipeer manager: stop client timer
2016-04-07 21:54:38.372 ThaliTest[572:949678] jxcore: stopAdvertisingAndListening: success
,2016-04-07 21:54:38.374 ThaliTest[572:949678] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:54:38.376 ThaliTest[572:949678] ,jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 107 error should be null
,ok 108 error should be null
,# setup
,# 28. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 52038
,2016-04-07 21:54:46.686 ThaliTest[572:949678] jxcore: stopAdvertisingAndListening
,2016-04-07 21:54:46.686 ThaliTest[572:949678] THEMultipeerManager stopping peer
,2016-04-07 21:54:46.687 ThaliTest[572:949678] jxcore: stopAdvertisingAndListening: success
,ok 109 error should be null
,ok 110 error should be null
,2016-04-07 21:54:46.693 ThaliTest[572:949678] jxcore: stopAdvertisingAndListening
,2016-04-07 21:54:46.694 ThaliTest[572:949678] THEMultipeerManager stopping peer
,2016-04-07 21:54:46.694 ThaliTest[572:949678] jxcore: stopAdvertisingAndListening: success
,ok 111 error should be null
,ok 112 error should be null
,# teardown
,2016-04-07 21:55:02.670 ThaliTest[572:949678] jxcore: stopAdvertisingAndListening
,2016-04-07 21:55:02.671 ThaliTest[572:949678] THEMultipeerManager stopping peer
,2016-04-07 21:55:02.672 ThaliTest[572:949678] jxcore: stopAdvertisingAndListening: success
,2016-04-07 21:55:02.673 ThaliTest[572:949678] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-07 21:55:02.675 ThaliTest[572:949678] jxcore: stopListeningForAdvertisements: success
,ok 113 error should be null
,ok 114 error should be null
,# setup
,# 29. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 52040
,ok 115 first call should succeed
,ok 116 first call should succeed
,ok 117 specific error should be returned
,# teardown
,2016-04-07 21:55:05.914 ThaliTest[572:949678] jxcore: stopAdvertisingAndListening
,2016-04-07 21:55:05.914 ThaliTest[572:949678] THEMultipeerManager stopping peer
,2016-04-07 21:55:05.915 ThaliTest[572:949678] jxcore: stopAdvertisingAndListening: success
,2016-04-07 21:55:05.916 ThaliTest[572:949678] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-07 21:55:05.918 ThaliTest[572:949678] jxcore: stopListeningForAdvertisements: success
,ok 118 error should be null
,ok 119 error should be null
,# setup
,# 30. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 52042
,2016-04-07 21:55:06.116 ThaliTest[572:949678] jxcore: startListeningForAdvertisements
,2016-04-07 21:55:06.117 ThaliTest[572:949678] multipeer manager: start client restart timer: 0x15e79110
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-07 21:55:06.120 ThaliTest[572:949678] jxcore: startListeningForAdvertisements: success
,2016-04-07 21:55:06.144 ThaliTest[572:949678] jxcore: startUpdateAdvertisingAndListening
,2016-04-07 21:55:06.145 ThaliTest[572:949678] server: starting 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:3
,2016-04-07 21:55:06.146 ThaliTest[572:949678] THEMultipeerManager initialized peer 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:3
2016-04-07 21:55:06.147 ThaliTest[572:949678] jxcore: startUpdateAdvertisingAndListening: success
,ok 120 called only once
,ok 121 discovery state matches
,ok 122 advertising state matches
,# teardown
,2016-04-07 21:55:06.376 ThaliTest[572:949678] jxcore: stopAdvertisingAndListening
,2016-04-07 21:55:06.376 ThaliTest[572:949678] THEMultipeerManager stopping peer
,2016-04-07 21:55:06.378 ThaliTest[572:949678] jxcore: stopAdvertisingAndListening: success
2016-04-07 21:55:06.378 ThaliTest[572:949678] jxcore: stopListeningForAdvertisements
,2016-04-07 21:55:06.380 ThaliTest[572:949678] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-07 21:55:06.382 ThaliTest[572:949678] jxcore: stopListeningForAdvertisements: success
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
,2016-04-07 21:55:56.964 ThaliTest[572:949678] jxcore: startListeningForAdvertisements
,2016-04-07 21:55:56.965 ThaliTest[572:949678] multipeer manager: start client restart timer: 0x15e79110
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-07 21:55:56.968 ThaliTest[572:949678] jxcore: startListeningForAdvertisements: success
,ok 138 Can call startListeningForAdvertisements without error
,2016-04-07 21:55:56.974 ThaliTest[572:949678] jxcore: stopListeningForAdvertisements
,2016-04-07 21:55:56.975 ThaliTest[572:949678] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-07 21:55:56.978 ThaliTest[572:949678] jxcore: stopListeningForAdvertisements: success
,ok 139 Can call stopListeningForAdvertisements without error
,# teardown
,2016-04-07 21:55:57.310 ThaliTest[572:949678] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-07 21:55:57.312 ThaliTest[572:949678] jxcore: stopListeningForAdvertisements: success
,ok 140 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-07 21:55:57.315 ThaliTest[572:949678] jxcore: stopAdvertisingAndListening
,2016-04-07 21:55:57.316 ThaliTest[572:949678] THEMultipeerManager stopping peer
,2016-04-07 21:55:57.316 ThaliTest[572:949678] jxcore: stopAdvertisingAndListening: success
,ok 141 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 35. Calling startListeningForAdvertisements twice is NOT an error
,2016-04-07 21:55:57.867 ThaliTest[572:949678] jxcore: startListeningForAdvertisements
,2016-04-07 21:55:57.868 ThaliTest[572:949678] multipeer manager: start client restart timer: 0x15e79110
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-07 21:55:57.871 ThaliTest[572:949678] jxcore: startListeningForAdvertisements: success
,ok 142 Can call startListeningForAdvertisements without error
,2016-04-07 21:55:57.874 ThaliTest[572:949678] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-07 21:55:57.877 ThaliTest[572:949678] jxcore: startListeningForAdvertisements: success
,ok 143 Can call startListeningForAdvertisements twice without error
,# teardown
,2016-04-07 21:55:57.966 ThaliTest[572:949678] jxcore: stopListeningForAdvertisements
,2016-04-07 21:55:57.967 ThaliTest[572:949678] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-07 21:55:57.971 ThaliTest[572:949678] jxcore: stopListeningForAdvertisements: success
,ok 144 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-07 21:55:57.974 ThaliTest[572:949678] jxcore: stopAdvertisingAndListening
,2016-04-07 21:55:57.974 ThaliTest[572:949678] THEMultipeerManager stopping peer
,2016-04-07 21:55:57.975 ThaliTest[572:949678] jxcore: stopAdvertisingAndListening: success
,ok 145 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 36. Calling stopListeningForAdvertisements without calling start is NOT an error
,2016-04-07 21:56:22.736 ThaliTest[572:949678] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-07 21:56:22.738 ThaliTest[572:949678] jxcore: stopListeningForAdvertisements: success
,ok 146 Can call stopListeningForAdvertisements without error
,2016-04-07 21:56:22.741 ThaliTest[572:949678] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-07 21:56:22.743 ThaliTest[572:949678] jxcore: stopListeningForAdvertisements: success
,ok 147 Can call stopListeningForAdvertisements without error
,# teardown
,2016-04-07 21:56:22.858 ThaliTest[572:949678] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-07 21:56:22.860 ThaliTest[572:949678] jxcore: stopListeningForAdvertisements: success
,ok 148 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-07 21:56:22.863 ThaliTest[572:949678] jxcore: stopAdvertisingAndListening
,2016-04-07 21:56:22.863 ThaliTest[572:949678] THEMultipeerManager stopping peer
,2016-04-07 21:56:22.864 ThaliTest[572:949678] jxcore: stopAdvertisingAndListening: success
,ok 149 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 37. Can call start/stopUpdateAdvertisingAndListening
,2016-04-07 21:56:23.182 ThaliTest[572:949678] jxcore: startUpdateAdvertisingAndListening
,2016-04-07 21:56:23.183 ThaliTest[572:949678] server: starting 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:4
,2016-04-07 21:56:23.184 ThaliTest[572:949678] multipeer manager: start client restart timer: 0x15e79110
2016-04-07 21:56:23.185 ThaliTest[572:949678] THEMultipeerManager initialized peer 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:4
2016-04-07 21:56:23.185 Thal,iTest[572:949678] jxcore: startUpdateAdvertisingAndListening: success
,ok 150 Can call startUpdateAdvertisingAndListening without error
,2016-04-07 21:56:23.189 ThaliTest[572:949678] jxcore: stopAdvertisingAndListening
,2016-04-07 21:56:23.193 ThaliTest[572:949678] THEMultipeerManager stopping peer
2016-04-07 21:56:23.194 ThaliTest[572:949678] multipeer manager: stop client timer
2016-04-07 21:56:23.195 ThaliTest[572:949678] jxcore: stopAdvertisingAndListening: success
,ok 151 Can call stopAdvertisingAndListening without error
,# teardown
,2016-04-07 21:56:23.436 ThaliTest[572:949678] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-07 21:56:23.438 ThaliTest[572:949678] jxcore: stopListeningForAdvertisements: success
,ok 152 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-07 21:56:23.440 ThaliTest[572:949678] jxcore: stopAdvertisingAndListening
,2016-04-07 21:56:23.441 ThaliTest[572:949678] THEMultipeerManager stopping peer
,2016-04-07 21:56:23.441 ThaliTest[572:949678] jxcore: stopAdvertisingAndListening: success
,ok 153 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-04-07 21:56:23.621 ThaliTest[572:949678] jxcore: startUpdateAdvertisingAndListening
,2016-04-07 21:56:23.621 ThaliTest[572:949678] server: starting 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:5
,2016-04-07 21:56:23.622 ThaliTest[572:949678] multipeer manager: start client restart timer: 0x15e79110
2016-04-07 21:56:23.623 ThaliTest[572:949678] THEMultipeerManager initialized peer 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:5
2016-04-07 21:56:23.623 Thal,iTest[572:949678] jxcore: startUpdateAdvertisingAndListening: success
ok 154 Can call startUpdateAdvertisingAndListening without error
,2016-04-07 21:56:23.626 ThaliTest[572:949678] jxcore: startUpdateAdvertisingAndListening
2016-04-07 21:56:23.627 ThaliTest[572:949678] THEMultipeerManager stopping peer
2016-04-07 21:56:23.627 ThaliTest[572:949678] multipeer manager: stop client timer
2,016-04-07 21:56:23.628 ThaliTest[572:949678] server: starting 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:6
,2016-04-07 21:56:23.629 ThaliTest[572:949678] multipeer manager: start client restart timer: 0x15e79110
2016-04-07 21:56:23.629 ThaliTest[572:949678] THEMultipeerManager initialized peer 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:6
2016-04-07 21:56:23.630 ThaliTest[572:949678] jxcore: startUpdateAdvertisingAndListening: success
ok 155 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,2016-04-07 21:56:24.034 ThaliTest[572:949678] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-07 21:56:24.036 ThaliTest[572:949678] jxcore: stopListeningForAdvertisements: success
,ok 156 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-07 21:56:24.039 ThaliTest[572:949678] jxcore: stopAdvertisingAndListening
,2016-04-07 21:56:24.040 ThaliTest[572:949678] THEMultipeerManager stopping peer
,2016-04-07 21:56:24.040 ThaliTest[572:949678] multipeer manager: stop client timer
2016-04-07 21:56:24.041 ThaliTest[572:949678] jxcore: stopAdvertisingAndListening: success
ok 157 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,2016-04-07 21:56:26.573 ThaliTest[572:949678] jxcore: stopAdvertisingAndListening
,2016-04-07 21:56:26.574 ThaliTest[572:949678] THEMultipeerManager stopping peer
,2016-04-07 21:56:26.574 ThaliTest[572:949678] jxcore: stopAdvertisingAndListening: success
,ok 158 Can call startUpdateAdvertisingAndListening without error
,2016-04-07 21:56:26.577 ThaliTest[572:949678] jxcore: stopAdvertisingAndListening
,2016-04-07 21:56:26.578 ThaliTest[572:949678] THEMultipeerManager stopping peer
,2016-04-07 21:56:26.578 ThaliTest[572:949678] jxcore: stopAdvertisingAndListening: success
,ok 159 Can call stopAdvertisingAndListening without error
,# teardown
,2016-04-07 21:56:54.261 ThaliTest[572:949678] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-07 21:56:54.264 ThaliTest[572:949678] jxcore: stopListeningForAdvertisements: success
,ok 160 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-07 21:56:54.267 ThaliTest[572:949678] jxcore: stopAdvertisingAndListening
,2016-04-07 21:56:54.267 ThaliTest[572:949678] THEMultipeerManager stopping peer
,2016-04-07 21:56:54.267 ThaliTest[572:949678] jxcore: stopAdvertisingAndListening: success
,ok 161 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 40. cannot call connect when start listening for advertisements is not active
,2016-04-07 21:57:12.977 ThaliTest[572:949678] jxcore: connect foo
,2016-04-07 21:57:12.977 ThaliTest[572:949678] jxcore: connect: fail: Start browsing first
,not ok 162 got right error
,  ---
,    operator: equal
,    expected: 'startListeningForAdvertisements is not active'
,    actual:   'Start browsing first'
,  ...
,# teardown
,2016-04-07 21:57:16.780 ThaliTest[572:949678] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-07 21:57:16.782 ThaliTest[572:949678] jxcore: stopListeningForAdvertisements: success
,ok 163 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-07 21:57:16.785 ThaliTest[572:949678] jxcore: stopAdvertisingAndListening
2016-04-07 21:57:16.785 ThaliTest[572:949678] THEMultipeerManager stopping peer
,2016-04-07 21:57:16.786 ThaliTest[572:949678] jxcore: stopAdvertisingAndListening: success
,ok 164 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 41. peerAvailabilityChange is called
,2016-04-07 21:57:17.129 ThaliTest[572:949678] jxcore: startUpdateAdvertisingAndListening
,2016-04-07 21:57:17.129 ThaliTest[572:949678] server: starting 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7
,2016-04-07 21:57:17.131 ThaliTest[572:949678] multipeer manager: start client restart timer: 0x15e79110
2016-04-07 21:57:17.131 ThaliTest[572:949678] THEMultipeerManager initialized peer 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7
2016-04-07 21:57:17.131 Thal,iTest[572:949678] jxcore: startUpdateAdvertisingAndListening: success
ok 165 Can call startUpdateAdvertisingAndListeningwithout error
,2016-04-07 21:57:17.134 ThaliTest[572:949678] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
,2016-04-07 21:57:17.140 ThaliTest[572:949678] jxcore: startListeningForAdvertisements: success
,ok 166 Can call startListeningForAdvertisements without error
,2016-04-07 21:57:18.164 ThaliTest[572:949464] client: found new peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:7
,ok 167 peers must be an array
,ok 168 peers must not be zero-length
,ok 169 peer must have peerIdentifier
,ok 170 peerIdentifier must be a string
,ok 171 peer must have peerAvailable
,ok 172 peer must have pleaseConnect
,# teardown
,2016-04-07 21:57:18.269 ThaliTest[572:949464] client: found new peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:7
,2016-04-07 21:57:18.321 ThaliTest[572:949464] client: found new peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:7
,2016-04-07 21:57:20.022 ThaliTest[572:949678] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-07 21:57:20.024 ThaliTest[572:949678] jxcore: stopListeningForAdvertisements: success
,ok 173 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-07 21:57:20.027 ThaliTest[572:949678] jxcore: stopAdvertisingAndListening
,2016-04-07 21:57:20.027 ThaliTest[572:949678] THEMultipeerManager stopping peer
,2016-04-07 21:57:20.028 ThaliTest[572:949678] multipeer manager: stop client timer
2016-04-07 21:57:20.029 ThaliTest[572:949678] jxcore: stopAdvertisingAndListening: success
,ok 174 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 42. Can connect to a remote peer
,2016-04-07 21:57:20.632 ThaliTest[572:949678] jxcore: startUpdateAdvertisingAndListening
,2016-04-07 21:57:20.633 ThaliTest[572:949678] server: starting 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8
,2016-04-07 21:57:20.634 ThaliTest[572:949678] multipeer manager: start client restart timer: 0x15e79110
2016-04-07 21:57:20.635 ThaliTest[572:949678] THEMultipeerManager initialized peer 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8
2016-04-07 21:57:20.636 ThaliTest[572:949678] jxcore: startUpdateAdvertisingAndListening: success
,ok 175 Can call startUpdateAdvertisingAndListening without error
,2016-04-07 21:57:20.639 ThaliTest[572:949678] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-04-07 21:57:20.641 ThaliTest[572:949678] j,xcore: startListeningForAdvertisements: success
ok 176 Can call startListeningForAdvertisements without error
,2016-04-07 21:57:21.635 ThaliTest[572:949464] multipeer session: reset timer
,2016-04-07 21:57:21.635 ThaliTest[572:949464] server: rejecting invitation from EA14B348-B7C0-4A23-9984-3BE67FDBCA34 due to previous generation (2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8 != 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7)
,2016-04-07 21:57:22.550 ThaliTest[572:949464] client: found new peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:7
,2016-04-07 21:57:22.553 ThaliTest[572:949464] client: found new peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:7
2016-04-07 21:57:22.553 ThaliTest[572:949464] client: found new peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:7
INFO testThaliMobileNative: Received, peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"EA14B348-B7C0-4A23-9984-3BE67FDBCA34:7","pleaseConnect":0}]
2016-04-07 21:57:22.555 ThaliTest[572:949678] jxcore: connect EA14B348-B7C0-4A23-9984-3BE67FDBCA34:7
2016-04-07 21:57:2,2.556 ThaliTest[572:949678] client: server will connect
2016-04-07 21:57:22.556 ThaliTest[572:949678] client session: reverseConnect
2016-04-07 21:57:22.557 ThaliTest[572:949678] client session: stateChange:0->1 EA14B348-B7C0-4A23-9984-3BE67FDBCA34:7
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:7","pleaseConnect":0}]
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"D42275B6-6BF0-48D7-8A46-E91B6C0E6559:7","pleaseConnect":0}]
,2016-04-07 21:57:22.758 ThaliTest[572:950360] client session: not connected EA14B348-B7C0-4A23-9984-3BE67FDBCA34:7
2016-04-07 21:57:22.758 ThaliTest[572:950360] client session: onLinkFailure: EA14B348-B7C0-4A23-9984-3BE67FDBCA34
,2016-04-07 21:57:22.759 ThaliTest[572:950360] client session: disconnect
2016-04-07 21:57:22.760 ThaliTest[572:950360] client session: stateChange:1->0 EA14B348-B7C0-4A23-9984-3BE67FDBCA34:7
2016-04-07 21:57:22.761 ThaliTest[572:950360] client session: n,o connect callback (server initiated)
,2016-04-07 21:57:23.217 ThaliTest[572:949464] multipeer session: reset timer
,2016-04-07 21:57:23.217 ThaliTest[572:949464] server: rejecting invitation from D42275B6-6BF0-48D7-8A46-E91B6C0E6559 due to previous generation (2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8 != 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7)
,2016-04-07 21:57:25.042 ThaliTest[572:949464] multipeer session: reset timer
2016-04-07 21:57:25.042 ThaliTest[572:949464] server: disconnecting to refresh session (EA14B348-B7C0-4A23-9984-3BE67FDBCA34)
,2016-04-07 21:57:25.043 ThaliTest[572:949464] server: rejecting invitation from EA14B348-B7C0-4A23-9984-3BE67FDBCA34 due to previous generation (2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8 != 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7)
,2016-04-07 21:57:27.336 ThaliTest[572:949464] multipeer session: reset timer
,2016-04-07 21:57:27.337 ThaliTest[572:949464] server: disconnecting to refresh session (D42275B6-6BF0-48D7-8A46-E91B6C0E6559)
2016-04-07 21:57:27.337 ThaliTest[572:949464] server: rejecting invitation from D42275B6-6BF0-48D7-8A46-E91B6C0E6559 due to previ,ous generation (2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8 != 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7)
,2016-04-07 21:57:28.254 ThaliTest[572:949464] multipeer session: reset timer
2016-04-07 21:57:28.254 ThaliTest[572:949464] server: disconnecting to refresh session (EA14B348-B7C0-4A23-9984-3BE67FDBCA34)
2016-04-07 21:57:28.254 ThaliTest[572:949464] serve,r: rejecting invitation from EA14B348-B7C0-4A23-9984-3BE67FDBCA34 due to previous generation (2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8 != 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7)
,2016-04-07 21:57:30.592 ThaliTest[572:949464] multipeer session: reset timer
,2016-04-07 21:57:30.593 ThaliTest[572:949464] server: disconnecting to refresh session (D42275B6-6BF0-48D7-8A46-E91B6C0E6559)
2016-04-07 21:57:30.593 ThaliTest[572:949464] server: rejecting invitation from D42275B6-6BF0-48D7-8A46-E91B6C0E6559 due to previ,ous generation (2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8 != 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7)
,2016-04-07 21:57:31.405 ThaliTest[572:949464] multipeer session: reset timer
2016-04-07 21:57:31.406 ThaliTest[572:949464] server: disconnecting to refresh session (EA14B348-B7C0-4A23-9984-3BE67FDBCA34)
2016-04-07 21:57:31.406 ThaliTest[572:949464] serve,r: rejecting invitation from EA14B348-B7C0-4A23-9984-3BE67FDBCA34 due to previous generation (2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8 != 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7)
,2016-04-07 21:57:32.558 ThaliTest[572:949464] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-04-07 21:57:34.126 ThaliTest[572:949464] multipeer session: reset timer
,2016-04-07 21:57:34.127 ThaliTest[572:949464] server: disconnecting to refresh session (D42275B6-6BF0-48D7-8A46-E91B6C0E6559)
,2016-04-07 21:57:34.127 ThaliTest[572:949464] server: rejecting invitation from D42275B6-6BF0-48D7-8A46-E91B6C0E6559 due to previous generation (2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8 != 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7)
,2016-04-07 21:57:34.558 ThaliTest[572:949464] multipeer session: reset timer
,2016-04-07 21:57:34.559 ThaliTest[572:949464] server: disconnecting to refresh session (EA14B348-B7C0-4A23-9984-3BE67FDBCA34)
2016-04-07 21:57:34.559 ThaliTest[572:949464] server: rejecting invitation from EA14B348-B7C0-4A23-9984-3BE67FDBCA34 due to previ,ous generation (2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8 != 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7)
,2016-04-07 21:57:35.574 ThaliTest[572:949678] jxcore: connect EA14B348-B7C0-4A23-9984-3BE67FDBCA34:7
,2016-04-07 21:57:35.575 ThaliTest[572:949678] client: server will connect
,2016-04-07 21:57:35.576 ThaliTest[572:949678] client session: reverseConnect
,2016-04-07 21:57:35.576 ThaliTest[572:949678] client session: stateChange:0->1 EA14B348-B7C0-4A23-9984-3BE67FDBCA34:7
,2016-04-07 21:57:35.672 ThaliTest[572:950361] client session: not connected EA14B348-B7C0-4A23-9984-3BE67FDBCA34:7
2016-04-07 21:57:35.673 ThaliTest[572:950361] client session: onLinkFailure: EA14B348-B7C0-4A23-9984-3BE67FDBCA34
2016-04-07 21:57:35.673 T,haliTest[572:950361] client session: disconnect
2016-04-07 21:57:35.673 ThaliTest[572:950361] client session: stateChange:1->0 EA14B348-B7C0-4A23-9984-3BE67FDBCA34:7
,2016-04-07 21:57:35.674 ThaliTest[572:950361] client session: no connect callback (server initiated)
,2016-04-07 21:57:37.489 ThaliTest[572:949464] multipeer session: reset timer
,2016-04-07 21:57:37.490 ThaliTest[572:949464] server: disconnecting to refresh session (D42275B6-6BF0-48D7-8A46-E91B6C0E6559)
2016-04-07 21:57:37.490 ThaliTest[572:949464] server: rejecting invitation from D42275B6-6BF0-48D7-8A46-E91B6C0E6559 due to previ,ous generation (2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8 != 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7)
,2016-04-07 21:57:37.687 ThaliTest[572:949464] multipeer session: reset timer
,2016-04-07 21:57:37.688 ThaliTest[572:949464] server: disconnecting to refresh session (EA14B348-B7C0-4A23-9984-3BE67FDBCA34)
,2016-04-07 21:57:37.688 ThaliTest[572:949464] server: rejecting invitation from EA14B348-B7C0-4A23-9984-3BE67FDBCA34 due to previous generation (2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8 != 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7)
,2016-04-07 21:57:40.636 ThaliTest[572:949464] multipeer manager: restart client
,2016-04-07 21:57:40.661 ThaliTest[572:949464] client: found updated peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8
2016-04-07 21:57:40.661 ThaliTest[572:949464] client: found updated peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:8
2016-04-07 21:57:40.662 Thal,iTest[572:949464] client: found updated peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8","pleaseConnect":0}],
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"D42275B6-6BF0-48D7-8A46-E91B6C0E6559:8","pleaseConnect":0}]
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8","pleaseConnect":0}]
,2016-04-07 21:57:40.834 ThaliTest[572:949464] multipeer session: reset timer
2016-04-07 21:57:40.834 ThaliTest[572:949464] server: disconnecting to refresh session (EA14B348-B7C0-4A23-9984-3BE67FDBCA34)
2016-04-07 21:57:40.835 ThaliTest[572:949464] serve,r: rejecting invitation from EA14B348-B7C0-4A23-9984-3BE67FDBCA34 due to previous generation (2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8 != 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7)
,2016-04-07 21:57:44.443 ThaliTest[572:949464] multipeer session: reset timer
2016-04-07 21:57:44.443 ThaliTest[572:949464] server: disconnecting to refresh session (EA14B348-B7C0-4A23-9984-3BE67FDBCA34)
,2016-04-07 21:57:44.444 ThaliTest[572:949464] server: rejecting invitation from EA14B348-B7C0-4A23-9984-3BE67FDBCA34 due to previous generation (2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8 != 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7)
,2016-04-07 21:57:45.576 ThaliTest[572:949464] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-04-07 21:57:47.589 ThaliTest[572:949464] multipeer session: reset timer
2016-04-07 21:57:47.590 ThaliTest[572:949464] server: disconnecting to refresh session (EA14B348-B7C0-4A23-9984-3BE67FDBCA34)
,2016-04-07 21:57:47.590 ThaliTest[572:949464] server: rejecting invitation from EA14B348-B7C0-4A23-9984-3BE67FDBCA34 due to previous generation (2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8 != 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7)
,2016-04-07 21:57:48.582 ThaliTest[572:949678] jxcore: connect EA14B348-B7C0-4A23-9984-3BE67FDBCA34:7
,2016-04-07 21:57:48.582 ThaliTest[572:949678] client: server will connect
,2016-04-07 21:57:48.583 ThaliTest[572:949678] client session: reverseConnect
,2016-04-07 21:57:48.584 ThaliTest[572:949678] client session: stateChange:0->1 EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
,2016-04-07 21:57:48.736 ThaliTest[572:950390] client session: not connected EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
2016-04-07 21:57:48.736 ThaliTest[572:950390] client session: onLinkFailure: EA14B348-B7C0-4A23-9984-3BE67FDBCA34
2016-04-07 21:57:48.737 ThaliTest[572:950390] client session: disconnect
,2016-04-07 21:57:48.737 ThaliTest[572:950390] client session: stateChange:1->0 EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
,2016-04-07 21:57:48.737 ThaliTest[572:950390] client session: no connect callback (server initiated)
,2016-04-07 21:57:50.801 ThaliTest[572:949464] multipeer session: reset timer
,2016-04-07 21:57:50.802 ThaliTest[572:949464] server: disconnecting to refresh session (EA14B348-B7C0-4A23-9984-3BE67FDBCA34)
,2016-04-07 21:57:50.802 ThaliTest[572:949464] server: rejecting invitation from EA14B348-B7C0-4A23-9984-3BE67FDBCA34 due to previous generation (2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8 != 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7)
,2016-04-07 21:57:58.584 ThaliTest[572:949464] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-04-07 21:58:00.636 ThaliTest[572:949464] multipeer manager: restart client
,2016-04-07 21:58:00.665 ThaliTest[572:949464] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8
2016-04-07 21:58:00.665 ThaliTest[572:949464] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
,2016-04-07 21:58:00.667 ThaliTest[572:949464] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:8
,2016-04-07 21:58:01.589 ThaliTest[572:949678] jxcore: connect EA14B348-B7C0-4A23-9984-3BE67FDBCA34:7
,2016-04-07 21:58:01.590 ThaliTest[572:949678] client: server will connect
,2016-04-07 21:58:01.590 ThaliTest[572:949678] client session: reverseConnect
,2016-04-07 21:58:01.591 ThaliTest[572:949678] client session: stateChange:0->1 EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
,2016-04-07 21:58:01.932 ThaliTest[572:950361] client session: not connected EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
2016-04-07 21:58:01.932 ThaliTest[572:950361] client session: onLinkFailure: EA14B348-B7C0-4A23-9984-3BE67FDBCA34
2016-04-07 21:58:01.932 ThaliTest[572:950361] client session: disconnect
,2016-04-07 21:58:01.933 ThaliTest[572:950361] client session: stateChange:1->0 EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
,2016-04-07 21:58:01.933 ThaliTest[572:950361] client session: no connect callback (server initiated)
,2016-04-07 21:58:11.592 ThaliTest[572:949464] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-04-07 21:58:14.598 ThaliTest[572:949678] jxcore: connect EA14B348-B7C0-4A23-9984-3BE67FDBCA34:7
,2016-04-07 21:58:14.599 ThaliTest[572:949678] client: server will connect
2016-04-07 21:58:14.600 ThaliTest[572:949678] client session: reverseConnect
,2016-04-07 21:58:14.600 ThaliTest[572:949678] client session: stateChange:0->1 EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
,2016-04-07 21:58:15.038 ThaliTest[572:950572] client session: not connected EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
,2016-04-07 21:58:15.039 ThaliTest[572:950572] client session: onLinkFailure: EA14B348-B7C0-4A23-9984-3BE67FDBCA34
2016-04-07 21:58:15.040 ThaliTest[572:950572] client session: disconnect
2016-04-07 21:58:15.040 ThaliTest[572:950572] client session: state,Change:1->0 EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
2016-04-07 21:58:15.041 ThaliTest[572:950572] client session: no connect callback (server initiated)
,2016-04-07 21:58:20.636 ThaliTest[572:949464] multipeer manager: restart client
,2016-04-07 21:58:20.664 ThaliTest[572:949464] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8
2016-04-07 21:58:20.665 ThaliTest[572:949464] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
2016-04-07 21:58:20.665 ThaliTest[572:949464] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:8
,2016-04-07 21:58:24.601 ThaliTest[572:949464] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-04-07 21:58:27.608 ThaliTest[572:949678] jxcore: connect EA14B348-B7C0-4A23-9984-3BE67FDBCA34:7
,2016-04-07 21:58:27.609 ThaliTest[572:949678] client: server will connect
2016-04-07 21:58:27.610 ThaliTest[572:949678] client session: reverseConnect
2016-04-07 21:58:27.610 ThaliTest[572:949678] client session: stateChange:0->1 EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
,2016-04-07 21:58:28.010 ThaliTest[572:950565] client session: not connected EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
,2016-04-07 21:58:28.011 ThaliTest[572:950565] client session: onLinkFailure: EA14B348-B7C0-4A23-9984-3BE67FDBCA34
,2016-04-07 21:58:28.013 ThaliTest[572:950565] client session: disconnect
,2016-04-07 21:58:28.013 ThaliTest[572:950565] client session: stateChange:1->0 EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
,2016-04-07 21:58:28.014 ThaliTest[572:950565] client session: no connect callback (server initiated)
,2016-04-07 21:58:37.611 ThaliTest[572:949464] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-04-07 21:58:40.622 ThaliTest[572:949678] jxcore: connect EA14B348-B7C0-4A23-9984-3BE67FDBCA34:7
,2016-04-07 21:58:40.623 ThaliTest[572:949678] client: server will connect
,2016-04-07 21:58:40.624 ThaliTest[572:949678] client session: reverseConnect
2016-04-07 21:58:40.625 ThaliTest[572:949678] client session: stateChange:0->1 EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
,2016-04-07 21:58:40.636 ThaliTest[572:949464] multipeer manager: restart client
,2016-04-07 21:58:40.679 ThaliTest[572:949464] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8
2016-04-07 21:58:40.679 ThaliTest[572:949464] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
2016-04-07 21:58:40.679 Th,aliTest[572:949464] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:8
,2016-04-07 21:58:50.625 ThaliTest[572:949464] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-04-07 21:58:53.639 ThaliTest[572:949678] jxcore: connect EA14B348-B7C0-4A23-9984-3BE67FDBCA34:7
,2016-04-07 21:58:53.640 ThaliTest[572:949678] client: already connect(ing/ed) to EA14B348-B7C0-4A23-9984-3BE67FDBCA34:7
2016-04-07 21:58:53.641 ThaliTest[572:949678] jxcore: connect: fail: Already connect(ing/ed)
,INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-04-07 21:58:56.652 ThaliTest[572:949678] jxcore: connect EA14B348-B7C0-4A23-9984-3BE67FDBCA34:7
,2016-04-07 21:58:56.653 ThaliTest[572:949678] client: already connect(ing/ed) to EA14B348-B7C0-4A23-9984-3BE67FDBCA34:7
,2016-04-07 21:58:56.654 ThaliTest[572:949678] jxcore: connect: fail: Already connect(ing/ed)
,INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-04-07 21:58:59.672 ThaliTest[572:949678] jxcore: connect EA14B348-B7C0-4A23-9984-3BE67FDBCA34:7
,2016-04-07 21:58:59.673 ThaliTest[572:949678] client: already connect(ing/ed) to EA14B348-B7C0-4A23-9984-3BE67FDBCA34:7
2016-04-07 21:58:59.674 ThaliTest[572:949678] jxcore: connect: fail: Already connect(ing/ed)
,INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,WARN testThaliMobileNative: Too many connect retries!
,not ok 177 Connect failed!
,  ---
,    operator: fail
,  ...
,# teardown
,2016-04-07 21:59:00.636 ThaliTest[572:949464] multipeer manager: restart client
,2016-04-07 21:59:00.666 ThaliTest[572:949464] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8
,2016-04-07 21:59:00.668 ThaliTest[572:949464] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
,2016-04-07 21:59:00.669 ThaliTest[572:949464] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:8
,2016-04-07 21:59:13.575 ThaliTest[572:950791] client session: not connected EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
2016-04-07 21:59:13.576 ThaliTest[572:950791] client session: onLinkFailure: EA14B348-B7C0-4A23-9984-3BE67FDBCA34
,2016-04-07 21:59:13.576 ThaliTest[572:950791] client session: disconnect
,2016-04-07 21:59:13.577 ThaliTest[572:950791] client session: stateChange:1->0 EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
,2016-04-07 21:59:13.578 ThaliTest[572:950791] client session: no connect callback (server initiated)
,2016-04-07 21:59:20.636 ThaliTest[572:949464] multipeer manager: restart client
,2016-04-07 21:59:20.666 ThaliTest[572:949464] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8
2016-04-07 21:59:20.667 ThaliTest[572:949464] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:8
2016-04-07 21:59:20.667 ThaliTest[572:949464] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
,2016-04-07 21:59:40.636 ThaliTest[572:949464] multipeer manager: restart client
,2016-04-07 21:59:40.666 ThaliTest[572:949464] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
,2016-04-07 21:59:40.670 ThaliTest[572:949464] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8
2016-04-07 21:59:40.670 ThaliTest[572:949464] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:8
,2016-04-07 22:00:00.636 ThaliTest[572:949464] multipeer manager: restart client
,2016-04-07 22:00:00.666 ThaliTest[572:949464] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8
2016-04-07 22:00:00.667 ThaliTest[572:949464] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
,2016-04-07 22:00:00.669 ThaliTest[572:949464] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:8
,2016-04-07 22:00:20.636 ThaliTest[572:949464] multipeer manager: restart client
,2016-04-07 22:00:20.665 ThaliTest[572:949464] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
2016-04-07 22:00:20.666 ThaliTest[572:949464] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8
2016-04-07 22:00:20.667 ThaliTest[572:949464] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:8
,2016-04-07 22:00:38.139 ThaliTest[572:949678] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-07 22:00:38.141 ThaliTest[572:949678] jxcore: stopListeningForAdvertisements: success
,ok 178 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-07 22:00:38.144 ThaliTest[572:949678] jxcore: stopAdvertisingAndListening
,2016-04-07 22:00:38.144 ThaliTest[572:949678] THEMultipeerManager stopping peer
,2016-04-07 22:00:38.145 ThaliTest[572:949678] multipeer manager: stop client timer
2016-04-07 22:00:38.146 ThaliTest[572:949678] jxcore: stopAdvertisingAndListening: success
,ok 179 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 43. Get error when trying to double connect to a peer
,2016-04-07 22:00:56.118 ThaliTest[572:949678] jxcore: startUpdateAdvertisingAndListening
,2016-04-07 22:00:56.119 ThaliTest[572:949678] server: starting 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
,2016-04-07 22:00:56.120 ThaliTest[572:949678] multipeer manager: start client restart timer: 0x15e79110
2016-04-07 22:00:56.121 ThaliTest[572:949678] THEMultipeerManager initialized peer 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:00:56.121 Thal,iTest[572:949678] jxcore: startUpdateAdvertisingAndListening: success
,ok 180 Can call startUpdateAdvertisingAndListening without error
,2016-04-07 22:00:56.125 ThaliTest[572:949678] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
,2016-04-07 22:00:56.130 ThaliTest[572:949678] jxcore: startListeningForAdvertisements: success
,ok 181 Can call startListeningForAdvertisements without error
,2016-04-07 22:00:56.139 ThaliTest[572:949464] client: found new peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8
2016-04-07 22:00:56.141 ThaliTest[572:949464] client: found new peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
,2016-04-07 22:00:56.143 ThaliTest[572:949678] jxcore: connect 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8
2016-04-07 22:00:56.144 ThaliTest[572:949678] client: server will connect
2016-04-07 22:00:56.144 ThaliTest[572:949678] client session: reverseConnect
2,016-04-07 22:00:56.145 ThaliTest[572:949678] client session: stateChange:0->1 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8
,2016-04-07 22:00:57.288 ThaliTest[572:949464] client: found new peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:8
,2016-04-07 22:00:58.023 ThaliTest[572:950886] client session: not connected 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8
2016-04-07 22:00:58.024 ThaliTest[572:950886] client session: onLinkFailure: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE
2016-04-07 22:00:58.024 T,haliTest[572:950886] client session: disconnect
2016-04-07 22:00:58.024 ThaliTest[572:950886] client session: stateChange:1->0 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8
2016-04-07 22:00:58.025 ThaliTest[572:950886] client session: no connect callback (serve,r initiated)
,2016-04-07 22:01:06.146 ThaliTest[572:949464] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-04-07 22:01:09.151 ThaliTest[572:949678] jxcore: connect 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8
,2016-04-07 22:01:09.152 ThaliTest[572:949678] client: server will connect
,2016-04-07 22:01:09.153 ThaliTest[572:949678] client session: reverseConnect
2016-04-07 22:01:09.154 ThaliTest[572:949678] client session: stateChange:0->1 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8
,2016-04-07 22:01:09.473 ThaliTest[572:951115] client session: not connected 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8
2016-04-07 22:01:09.474 ThaliTest[572:951115] client session: onLinkFailure: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE
2016-04-07 22:01:09.474 ThaliTest[572:951115] client session: disconnect
,2016-04-07 22:01:09.476 ThaliTest[572:951115] client session: stateChange:1->0 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8
2016-04-07 22:01:09.477 ThaliTest[572:951115] client session: no connect callback (server initiated)
,2016-04-07 22:01:16.122 ThaliTest[572:949464] multipeer manager: restart client
,2016-04-07 22:01:16.152 ThaliTest[572:949464] client: found updated peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:01:16.152 ThaliTest[572:949464] client: found updated peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:01:16.153 ThaliTest[572:949464] client: found updated peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
,2016-04-07 22:01:19.154 ThaliTest[572:949464] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-04-07 22:01:22.167 ThaliTest[572:949678] jxcore: connect 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8
,2016-04-07 22:01:22.168 ThaliTest[572:949678] client: server will connect
2016-04-07 22:01:22.169 ThaliTest[572:949678] client session: reverseConnect
,2016-04-07 22:01:22.169 ThaliTest[572:949678] client session: stateChange:0->1 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:01:22.562 ThaliTest[572:951156] client session: not connected 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:01:22.563 ThaliTest[572:951156] client session: onLinkFailure: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE
2016-04-07 22:01:22.563 T,haliTest[572:951156] client session: disconnect
2016-04-07 22:01:22.563 ThaliTest[572:951156] client session: stateChange:1->0 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:01:22.565 ThaliTest[572:951156] client session: no connect callback (server initiated)
,2016-04-07 22:01:32.170 ThaliTest[572:949464] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-04-07 22:01:35.176 ThaliTest[572:949678] jxcore: connect 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8
,2016-04-07 22:01:35.177 ThaliTest[572:949678] client: server will connect
2016-04-07 22:01:35.177 ThaliTest[572:949678] client session: reverseConnect
,2016-04-07 22:01:35.178 ThaliTest[572:949678] client session: stateChange:0->1 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:01:35.670 ThaliTest[572:951258] client session: not connected 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:01:35.671 ThaliTest[572:951258] client session: onLinkFailure: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE
2016-04-07 22:01:35.671 T,haliTest[572:951258] client session: disconnect
2016-04-07 22:01:35.671 ThaliTest[572:951258] client session: stateChange:1->0 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:01:35.672 ThaliTest[572:951258] client session: no connect callback (server initiated)
,2016-04-07 22:01:36.122 ThaliTest[572:949464] multipeer manager: restart client
,2016-04-07 22:01:36.151 ThaliTest[572:949464] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:01:36.151 ThaliTest[572:949464] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:01:36.152 Th,aliTest[572:949464] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:01:45.179 ThaliTest[572:949464] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-04-07 22:01:48.188 ThaliTest[572:949678] jxcore: connect 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8
,2016-04-07 22:01:48.188 ThaliTest[572:949678] client: server will connect
,2016-04-07 22:01:48.189 ThaliTest[572:949678] client session: reverseConnect
2016-04-07 22:01:48.190 ThaliTest[572:949678] client session: stateChange:0->1 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:01:48.328 ThaliTest[572:951294] client session: not connected 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:01:48.328 ThaliTest[572:951294] client session: onLinkFailure: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE
,2016-04-07 22:01:48.329 ThaliTest[572:951294] client session: disconnect
2016-04-07 22:01:48.330 ThaliTest[572:951294] client session: stateChange:1->0 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:01:48.331 ThaliTest[572:951294] client session: no connect callback (server initiated)
,2016-04-07 22:01:56.122 ThaliTest[572:949464] multipeer manager: restart client
,2016-04-07 22:01:56.152 ThaliTest[572:949464] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:01:56.153 ThaliTest[572:949464] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
,2016-04-07 22:01:56.153 ThaliTest[572:949464] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:01:58.190 ThaliTest[572:949464] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-04-07 22:02:01.200 ThaliTest[572:949678] jxcore: connect 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8
,2016-04-07 22:02:01.201 ThaliTest[572:949678] client: server will connect
,2016-04-07 22:02:01.201 ThaliTest[572:949678] client session: reverseConnect
2016-04-07 22:02:01.202 ThaliTest[572:949678] client session: stateChange:0->1 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:02:01.370 ThaliTest[572:951325] client session: not connected 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:02:01.371 ThaliTest[572:951325] client session: onLinkFailure: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE
2016-04-07 22:02:01.372 ThaliTest[572:951325] client session: disconnect
2016-04-07 22:02:01.372 ThaliTest[572:951325] client session: state,Change:1->0 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:02:01.373 ThaliTest[572:951325] client session: no connect callback (server initiated)
,2016-04-07 22:02:11.203 ThaliTest[572:949464] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-04-07 22:02:14.207 ThaliTest[572:949678] jxcore: connect 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8
,2016-04-07 22:02:14.208 ThaliTest[572:949678] client: server will connect
,2016-04-07 22:02:14.209 ThaliTest[572:949678] client session: reverseConnect
,2016-04-07 22:02:14.209 ThaliTest[572:949678] client session: stateChange:0->1 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:02:14.855 ThaliTest[572:951409] client session: not connected 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:02:14.855 ThaliTest[572:951409] client session: onLinkFailure: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE
2016-04-07 22:02:14.856 T,haliTest[572:951409] client session: disconnect
2016-04-07 22:02:14.856 ThaliTest[572:951409] client session: stateChange:1->0 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:02:14.857 ThaliTest[572:951409] client session: no connect callback (server initiated)
,2016-04-07 22:02:16.122 ThaliTest[572:949464] multipeer manager: restart client
,2016-04-07 22:02:16.153 ThaliTest[572:949464] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:02:16.153 ThaliTest[572:949464] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:02:16.153 Th,aliTest[572:949464] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
,2016-04-07 22:02:24.210 ThaliTest[572:949464] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-04-07 22:02:27.217 ThaliTest[572:949678] jxcore: connect 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8
,2016-04-07 22:02:27.218 ThaliTest[572:949678] client: server will connect
,2016-04-07 22:02:27.219 ThaliTest[572:949678] client session: reverseConnect
2016-04-07 22:02:27.219 ThaliTest[572:949678] client session: stateChange:0->1 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:02:27.623 ThaliTest[572:951443] client session: not connected 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:02:27.623 ThaliTest[572:951443] client session: onLinkFailure: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE
,2016-04-07 22:02:27.624 ThaliTest[572:951443] client session: disconnect
,2016-04-07 22:02:27.624 ThaliTest[572:951443] client session: stateChange:1->0 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:02:27.626 ThaliTest[572:951443] client session: no connect callback (server initiated)
,2016-04-07 22:02:36.122 ThaliTest[572:949464] multipeer manager: restart client
,2016-04-07 22:02:36.153 ThaliTest[572:949464] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:02:36.153 ThaliTest[572:949464] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:02:36.154 ThaliTest[572:949464] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
,2016-04-07 22:02:37.220 ThaliTest[572:949464] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-04-07 22:02:40.231 ThaliTest[572:949678] jxcore: connect 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8
,2016-04-07 22:02:40.232 ThaliTest[572:949678] client: server will connect
,2016-04-07 22:02:40.232 ThaliTest[572:949678] client session: reverseConnect
,2016-04-07 22:02:40.233 ThaliTest[572:949678] client session: stateChange:0->1 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:02:40.674 ThaliTest[572:951463] client session: not connected 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:02:40.675 ThaliTest[572:951463] client session: onLinkFailure: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE
,2016-04-07 22:02:40.676 ThaliTest[572:951463] client session: disconnect
,2016-04-07 22:02:40.676 ThaliTest[572:951463] client session: stateChange:1->0 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:02:40.677 ThaliTest[572:951463] client session: no connect callback (server initiated)
,2016-04-07 22:02:50.234 ThaliTest[572:949464] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-04-07 22:02:53.242 ThaliTest[572:949678] jxcore: connect 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8
,2016-04-07 22:02:53.243 ThaliTest[572:949678] client: server will connect
2016-04-07 22:02:53.243 ThaliTest[572:949678] client session: reverseConnect
,2016-04-07 22:02:53.244 ThaliTest[572:949678] client session: stateChange:0->1 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:02:56.121 ThaliTest[572:949464] multipeer manager: restart client
,2016-04-07 22:02:56.152 ThaliTest[572:949464] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:02:56.152 ThaliTest[572:949464] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:02:56.153 ThaliTest[572:949464] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
,2016-04-07 22:03:03.245 ThaliTest[572:949464] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,WARN testThaliMobileNative: Too many connect retries!
,2016-04-07 22:03:16.122 ThaliTest[572:949464] multipeer manager: restart client
,2016-04-07 22:03:16.152 ThaliTest[572:949464] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:03:16.153 ThaliTest[572:949464] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:03:16.153 ThaliTest[572:949464] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:03:26.241 ThaliTest[572:951539] client session: not connected 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:03:26.242 ThaliTest[572:951539] client session: onLinkFailure: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE
2016-04-07 22:03:26.242 T,haliTest[572:951539] client session: disconnect
2016-04-07 22:03:26.242 ThaliTest[572:951539] client session: stateChange:1->0 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:03:26.243 ThaliTest[572:951539] client session: no connect callback (serve,r initiated)
,2016-04-07 22:03:36.122 ThaliTest[572:949464] multipeer manager: restart client
,2016-04-07 22:03:36.152 ThaliTest[572:949464] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:03:36.153 ThaliTest[572:949464] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:03:36.153 ThaliTest[572:949464] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
,2016-04-07 22:03:56.122 ThaliTest[572:949464] multipeer manager: restart client
,2016-04-07 22:03:56.151 ThaliTest[572:949464] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:03:56.151 ThaliTest[572:949464] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:03:56.152 ThaliTest[572:949464] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
,2016-04-07 22:04:16.122 ThaliTest[572:949464] multipeer manager: restart client
,2016-04-07 22:04:16.154 ThaliTest[572:949464] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:04:16.154 ThaliTest[572:949464] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:04:16.155 ThaliTest[572:949464] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:04:36.122 ThaliTest[572:949464] multipeer manager: restart client
,2016-04-07 22:04:36.155 ThaliTest[572:949464] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:04:36.155 ThaliTest[572:949464] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:04:36.156 Th,aliTest[572:949464] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:04:56.122 ThaliTest[572:949464] multipeer manager: restart client
,2016-04-07 22:04:56.153 ThaliTest[572:949464] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:04:56.154 ThaliTest[572:949464] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
,2016-04-07 22:04:56.155 ThaliTest[572:949464] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
,2016-04-07 22:05:16.122 ThaliTest[572:949464] multipeer manager: restart client
,2016-04-07 22:05:16.153 ThaliTest[572:949464] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:05:16.154 ThaliTest[572:949464] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:05:16.154 Th,aliTest[572:949464] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:05:36.122 ThaliTest[572:949464] multipeer manager: restart client
,2016-04-07 22:05:36.155 ThaliTest[572:949464] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:05:36.156 ThaliTest[572:949464] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:05:36.156 Th,aliTest[572:949464] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:05:56.122 ThaliTest[572:949464] multipeer manager: restart client
,2016-04-07 22:05:56.150 ThaliTest[572:949464] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:05:56.150 ThaliTest[572:949464] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:05:56.151 Th,aliTest[572:949464] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:06:16.122 ThaliTest[572:949464] multipeer manager: restart client
,2016-04-07 22:06:16.151 ThaliTest[572:949464] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:06:16.152 ThaliTest[572:949464] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:06:16.152 ThaliTest[572:949464] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
,2016-04-07 22:06:36.122 ThaliTest[572:949464] multipeer manager: restart client
,2016-04-07 22:06:36.152 ThaliTest[572:949464] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:06:36.152 ThaliTest[572:949464] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:06:36.153 Th,aliTest[572:949464] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
,2016-04-07 22:06:56.122 ThaliTest[572:949464] multipeer manager: restart client
,2016-04-07 22:06:56.152 ThaliTest[572:949464] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:06:56.152 ThaliTest[572:949464] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:06:56.152 Th,aliTest[572:949464] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
,2016-04-07 22:07:16.122 ThaliTest[572:949464] multipeer manager: restart client
,2016-04-07 22:07:16.154 ThaliTest[572:949464] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:07:16.155 ThaliTest[572:949464] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:07:16.155 ThaliTest[572:949464] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
,2016-04-07 22:07:36.122 ThaliTest[572:949464] multipeer manager: restart client
,2016-04-07 22:07:36.152 ThaliTest[572:949464] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:07:36.152 ThaliTest[572:949464] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:07:36.153 Th,aliTest[572:949464] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
,2016-04-07 22:07:56.122 ThaliTest[572:949464] multipeer manager: restart client
,2016-04-07 22:07:56.154 ThaliTest[572:949464] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:07:56.155 ThaliTest[572:949464] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:07:56.155 Th,aliTest[572:949464] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:08:16.122 ThaliTest[572:949464] multipeer manager: restart client
,2016-04-07 22:08:16.152 ThaliTest[572:949464] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:08:16.152 ThaliTest[572:949464] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:08:16.153 ThaliTest[572:949464] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
,2016-04-07 22:08:36.121 ThaliTest[572:949464] multipeer manager: restart client
,2016-04-07 22:08:36.152 ThaliTest[572:949464] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:08:36.152 ThaliTest[572:949464] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:08:36.152 Th,aliTest[572:949464] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:08:56.122 ThaliTest[572:949464] multipeer manager: restart client
,2016-04-07 22:08:56.150 ThaliTest[572:949464] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:08:56.151 ThaliTest[572:949464] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:08:56.151 ThaliTest[572:949464] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:09:16.122 ThaliTest[572:949464] multipeer manager: restart client
,2016-04-07 22:09:16.152 ThaliTest[572:949464] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:09:16.153 ThaliTest[572:949464] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:09:16.154 ThaliTest[572:949464] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
,2016-04-07 22:09:36.122 ThaliTest[572:949464] multipeer manager: restart client
,2016-04-07 22:09:36.154 ThaliTest[572:949464] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:09:36.154 ThaliTest[572:949464] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:09:36.155 Th,aliTest[572:949464] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
,2016-04-07 22:09:56.122 ThaliTest[572:949464] multipeer manager: restart client
,2016-04-07 22:09:56.155 ThaliTest[572:949464] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:09:56.155 ThaliTest[572:949464] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:09:56.155 Th,aliTest[572:949464] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
,2016-04-07 22:10:16.122 ThaliTest[572:949464] multipeer manager: restart client
,2016-04-07 22:10:16.155 ThaliTest[572:949464] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:10:16.155 ThaliTest[572:949464] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:10:16.155 ThaliTest[572:949464] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:10:36.122 ThaliTest[572:949464] multipeer manager: restart client
,2016-04-07 22:10:36.154 ThaliTest[572:949464] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:10:36.154 ThaliTest[572:949464] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:10:36.155 Th,aliTest[572:949464] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
,2016-04-07 22:10:56.122 ThaliTest[572:949464] multipeer manager: restart client
,2016-04-07 22:10:56.154 ThaliTest[572:949464] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:10:56.155 ThaliTest[572:949464] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:10:56.155 Th,aliTest[572:949464] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
,2016-04-07 22:11:16.122 ThaliTest[572:949464] multipeer manager: restart client
,2016-04-07 22:11:16.151 ThaliTest[572:949464] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:11:16.151 ThaliTest[572:949464] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:11:16.151 ThaliTest[572:949464] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
,2016-04-07 22:11:36.122 ThaliTest[572:949464] multipeer manager: restart client
,2016-04-07 22:11:36.153 ThaliTest[572:949464] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:11:36.154 ThaliTest[572:949464] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:11:36.155 Th,aliTest[572:949464] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
,2016-04-07 22:11:56.122 ThaliTest[572:949464] multipeer manager: restart client
,2016-04-07 22:11:56.153 ThaliTest[572:949464] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:11:56.153 ThaliTest[572:949464] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:11:56.153 Th,aliTest[572:949464] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
,2016-04-07 22:12:16.122 ThaliTest[572:949464] multipeer manager: restart client
,2016-04-07 22:12:16.152 ThaliTest[572:949464] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:12:16.152 ThaliTest[572:949464] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:12:16.152 ThaliTest[572:949464] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
,2016-04-07 22:12:36.122 ThaliTest[572:949464] multipeer manager: restart client
,2016-04-07 22:12:36.152 ThaliTest[572:949464] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:12:36.152 ThaliTest[572:949464] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:12:36.153 Th,aliTest[572:949464] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:12:56.122 ThaliTest[572:949464] multipeer manager: restart client
,2016-04-07 22:12:56.153 ThaliTest[572:949464] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:12:56.154 ThaliTest[572:949464] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:12:56.154 ThaliTest[572:949464] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
,2016-04-07 22:13:16.122 ThaliTest[572:949464] multipeer manager: restart client
,2016-04-07 22:13:16.151 ThaliTest[572:949464] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:13:16.152 ThaliTest[572:949464] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:13:16.152 ThaliTest[572:949464] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
,2016-04-07 22:13:36.122 ThaliTest[572:949464] multipeer manager: restart client
,2016-04-07 22:13:36.153 ThaliTest[572:949464] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:13:36.154 ThaliTest[572:949464] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:13:36.154 ThaliTest[572:949464] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9

```
