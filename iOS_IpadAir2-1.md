#### Test 656816764cf5745_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/656816764cf5745/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/67BA76FF-BE8B-4D92-9CE8-D77DFCDB3324/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/67BA76FF-BE8B-4D92-9CE8-D77DFCDB3324/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/656816764cf5745/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/656816764cf5745/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/61428247-7B66-4F66-99F0-E9FBEC6DADE4/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51800"
,(lldb)     command script import "/tmp/67BA76FF-BE8B-4D92-9CE8-D77DFCDB3324/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-04-07 21:23:08.399 ThaliTest[556:944746] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0DC52796-1C6E-4E92-A422-91FD505B6DC1/Library/Cookies/Cookies.binarycookies
,2016-04-07 21:23:08.797 ThaliTest[556:944746] Apache Cordova native platform version 4.1.0 is starting.
,2016-04-07 21:23:08.798 ThaliTest[556:944746] Multi-tasking -> Device: YES, App: YES
,2016-04-07 21:23:08.818 ThaliTest[556:944746] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-04-07 21:23:10.661 ThaliTest[556:944746] Using UIWebView
,2016-04-07 21:23:10.667 ThaliTest[556:944746] [CDVTimer][handleopenurl] 0.521004ms
,2016-04-07 21:23:10.676 ThaliTest[556:944746] [CDVTimer][intentandnavigationfilter] 7.479012ms
,2016-04-07 21:23:10.676 ThaliTest[556:944746] [CDVTimer][gesturehandler] 0.331998ms
,2016-04-07 21:23:10.677 ThaliTest[556:944746] [CDVTimer][TotalPluginStartup] 10.007024ms
,2016-04-07 21:23:17.625 ThaliTest[556:944746] Resetting plugins due to page load.
,2016-04-07 21:23:20.993 ThaliTest[556:944746] Finished load of: file:///var/mobile/Containers/Bundle/Application/61428247-7B66-4F66-99F0-E9FBEC6DADE4/ThaliTest.app/www/index.html
,2016-04-07 21:23:21.204 ThaliTest[556:944746] JXcore Cordova plugin initializing
,2016-04-07 21:23:21.205 ThaliTest[556:945007] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-04-07 21:23:27.726 ThaliTest[556:945007] jxcore: didRegisterToNative peerAvailabilityChanged
2016-04-07 21:23:27.726 ThaliTest[556:945007] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-04-07 21:23:27.727 ThaliTest[556:945007] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-04-07 21:23:27.728 ThaliTest[556:945007] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-IpadAir2-1
WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/61428247-7B66-4F66-99F0-E9FBEC6DADE4/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/61428247-7B66-4F66-99F0-E9FBEC6DADE4/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/61428247-7B66-4F66-99F0-E9FBEC6DADE4/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/61428247-7B66-4F66-99F0-E9FBEC6DADE4/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/61428247-7B66-4F66-99F0-E9FBEC6DADE4/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/61428247-7B66-4F66-99F0-E9FBEC6DADE4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/61428247-7B66-4F66-99F0-E9FBEC6DADE4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/61428247-7B66-4F66-99F0-E9FBEC6DADE4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/61428247-7B66-4F66-99F0-E9FBEC6DADE4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/61428247-7B66-4F66-99F0-E9FBEC6DADE4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/61428247-7B66-4F66-99F0-E9FBEC6DADE4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/61428247-7B66-4F66-99F0-E9FBEC6DADE4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/61428247-7B66-4F66-99F0-E9FBEC6DADE4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/61428247-7B66-4F66-99F0-E9FBEC6DADE4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/61428247-7B66-4F66-99F0-E9FBEC6DADE4/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/61428247-7B66-4F66-99F0-E9FBEC6DADE4/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/61428247-7B66-4F66-99F0-E9FBEC6DADE4/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/61428247-7B66-4F66-99F0-E9FBEC6DADE4/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/61428247-7B66-4F66-99F0-E9FBEC6DADE4/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/61428247-7B66-4F66-99F0-E9FBEC6DADE4/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/61428247-7B66-4F66-99F0-E9FBEC6DADE4/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/61428247-7B66-4F66-99F0-E9FBEC6DADE4/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-04-07 21:23:33.604 ThaliTest[556:944746] THREAD WARNING: ['JXcore'] took '5597.647949' ms. Plugin should use a background thread.
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51730
,ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51732
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
,DEBUG createNativeListener: listening 51735
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
,DEBUG createNativeListener: listening 51739
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
,DEBUG createNativeListener: listening 51744
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
,DEBUG createNativeListener: listening 51748
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
,DEBUG createNativeListener: listening 51752
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
,DEBUG createNativeListener: listening 51756
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
,DEBUG createNativeListener: listening 51760
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
,DEBUG createNativeListener: listening 51812
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
,DEBUG createNativeListener: listening 51816
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
,[{"uuid":"03445e62-5e92-48cc-8875-30b0fdcb1b59","data":"custom data"},{"uuid":"cc977dc9-3774-4da7-8114-07bc6d4a1955","data":"custom data"},{"uuid":"856d22a5-0926-412e-b7a9-ad2877c2c912","data":"custom data"},{"uuid":"1019d4f9-108b-42a3-b511-e8f2013d3ebb","data":"custom data"}]
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
,DEBUG createNativeListener: listening 51826
,2016-04-07 21:25:37.857 ThaliTest[556:945007] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-07 21:25:37.859 ThaliTest[556:945007] jxcore: stopListeningForAdvertisements: success
,ok 91 error should be null
,ok 92 error should be null
,2016-04-07 21:25:37.862 ThaliTest[556:945007] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-07 21:25:37.863 ThaliTest[556:945007] jxcore: stopListeningForAdvertisements: success
,ok 93 error should be null
,ok 94 error should be null
,# teardown
,2016-04-07 21:25:37.955 ThaliTest[556:945007] jxcore: stopAdvertisingAndListening
,2016-04-07 21:25:37.955 ThaliTest[556:945007] THEMultipeerManager stopping peer
,2016-04-07 21:25:37.956 ThaliTest[556:945007] jxcore: stopAdvertisingAndListening: success
,2016-04-07 21:25:37.958 ThaliTest[556:945007] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-07 21:25:37.960 ThaliTest[556:945007] jxcore: stopListeningForAdvertisements: success
,ok 95 error should be null
,ok 96 error should be null
,# setup
,# 26. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51828
,2016-04-07 21:25:38.160 ThaliTest[556:945007] jxcore: startListeningForAdvertisements
,2016-04-07 21:25:38.162 ThaliTest[556:945007] multipeer manager: start client restart timer: 0x1767afc0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-07 21:25:38.165 ThaliTest[556:945007] jxcore: startListeningForAdvertisements: success
,ok 97 error should be null
,ok 98 error should be null
,2016-04-07 21:25:38.189 ThaliTest[556:945007] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-07 21:25:38.191 ThaliTest[556:945007] jxcore: startListeningForAdvertisements: success
,ok 99 error should be null
,ok 100 error should be null
,# teardown
,2016-04-07 21:25:38.459 ThaliTest[556:945007] jxcore: stopAdvertisingAndListening
,2016-04-07 21:25:38.460 ThaliTest[556:945007] THEMultipeerManager stopping peer
,2016-04-07 21:25:38.460 ThaliTest[556:945007] jxcore: stopAdvertisingAndListening: success
,2016-04-07 21:25:38.462 ThaliTest[556:945007] jxcore: stopListeningForAdvertisements
,2016-04-07 21:25:38.463 ThaliTest[556:945007] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:25:38.466 ThaliTest[556:945007] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 101 error should be null
,ok 102 error should be null
,# setup
,# 27. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51830
,2016-04-07 21:25:39.084 ThaliTest[556:945007] jxcore: startUpdateAdvertisingAndListening
,2016-04-07 21:25:39.085 ThaliTest[556:945007] server: starting 750E93F7-2E92-4298-982A-D1BFBCF07378:1
,2016-04-07 21:25:39.087 ThaliTest[556:945007] multipeer manager: start client restart timer: 0x1767afc0
2016-04-07 21:25:39.088 ThaliTest[556:945007] THEMultipeerManager initialized peer 750E93F7-2E92-4298-982A-D1BFBCF07378:1
2016-04-07 21:25:39.089 Thal,iTest[556:945007] jxcore: startUpdateAdvertisingAndListening: success
,ok 103 error should be null
,ok 104 error should be null
,2016-04-07 21:25:39.121 ThaliTest[556:945007] jxcore: startUpdateAdvertisingAndListening
,2016-04-07 21:25:39.122 ThaliTest[556:945007] THEMultipeerManager stopping peer
,2016-04-07 21:25:39.123 ThaliTest[556:945007] multipeer manager: stop client timer
2016-04-07 21:25:39.123 ThaliTest[556:945007] server: starting 750E93F7-2E92-4298-982A-D1BFBCF07378:2
,2016-04-07 21:25:39.125 ThaliTest[556:945007] multipeer manager: start client restart timer: 0x1767afc0
2016-04-07 21:25:39.125 ThaliTest[556:945007] THEMultipeerManager initialized peer 750E93F7-2E92-4298-982A-D1BFBCF07378:2
2016-04-07 21:25:39.126 Thal,iTest[556:945007] jxcore: startUpdateAdvertisingAndListening: success
,ok 105 error should be null
,ok 106 error should be null
,# teardown
,2016-04-07 21:25:40.238 ThaliTest[556:944746] client: found new peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:2
,2016-04-07 21:25:40.240 ThaliTest[556:944746] client: found new peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:2
,2016-04-07 21:25:40.367 ThaliTest[556:944746] client: found new peer: BF68E1C5-762A-429C-BDD9-41F21131A115:2
,2016-04-07 21:25:41.125 ThaliTest[556:945007] jxcore: stopAdvertisingAndListening
,2016-04-07 21:25:41.126 ThaliTest[556:945007] THEMultipeerManager stopping peer
,2016-04-07 21:25:41.127 ThaliTest[556:945007] multipeer manager: stop client timer
2016-04-07 21:25:41.127 ThaliTest[556:945007] jxcore: stopAdvertisingAndListening: success
,2016-04-07 21:25:41.128 ThaliTest[556:945007] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-07 21:25:41.132 ThaliTest[556:945007] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 107 error should be null
,ok 108 error should be null
,# setup
,# 28. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51835
,2016-04-07 21:25:41.777 ThaliTest[556:945007] jxcore: stopAdvertisingAndListening
,2016-04-07 21:25:41.777 ThaliTest[556:945007] THEMultipeerManager stopping peer
,2016-04-07 21:25:41.777 ThaliTest[556:945007] jxcore: stopAdvertisingAndListening: success
,ok 109 error should be null
,ok 110 error should be null
,2016-04-07 21:25:41.784 ThaliTest[556:945007] jxcore: stopAdvertisingAndListening
,2016-04-07 21:25:41.785 ThaliTest[556:945007] THEMultipeerManager stopping peer
,2016-04-07 21:25:41.785 ThaliTest[556:945007] jxcore: stopAdvertisingAndListening: success
,ok 111 error should be null
,ok 112 error should be null
,# teardown
,2016-04-07 21:25:42.555 ThaliTest[556:945007] jxcore: stopAdvertisingAndListening
,2016-04-07 21:25:42.555 ThaliTest[556:945007] THEMultipeerManager stopping peer
,2016-04-07 21:25:42.556 ThaliTest[556:945007] jxcore: stopAdvertisingAndListening: success
,2016-04-07 21:25:42.557 ThaliTest[556:945007] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-07 21:25:42.559 ThaliTest[556:945007] jxcore: stopListeningForAdvertisements: success
,ok 113 error should be null
,ok 114 error should be null
,# setup
,# 29. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51837
,ok 115 first call should succeed
,ok 116 first call should succeed
,ok 117 specific error should be returned
,# teardown
,2016-04-07 21:25:43.060 ThaliTest[556:945007] jxcore: stopAdvertisingAndListening
,2016-04-07 21:25:43.061 ThaliTest[556:945007] THEMultipeerManager stopping peer
,2016-04-07 21:25:43.061 ThaliTest[556:945007] jxcore: stopAdvertisingAndListening: success
,2016-04-07 21:25:43.063 ThaliTest[556:945007] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-07 21:25:43.065 ThaliTest[556:945007] jxcore: stopListeningForAdvertisements: success
,ok 118 error should be null
,ok 119 error should be null
,# setup
,# 30. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51839
,2016-04-07 21:25:43.327 ThaliTest[556:945007] jxcore: startListeningForAdvertisements
,2016-04-07 21:25:43.328 ThaliTest[556:945007] multipeer manager: start client restart timer: 0x1767afc0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-07 21:25:43.331 ThaliTest[556:945007] jxcore: startListeningForAdvertisements: success
,2016-04-07 21:25:43.349 ThaliTest[556:945007] jxcore: startUpdateAdvertisingAndListening
,2016-04-07 21:25:43.350 ThaliTest[556:945007] server: starting 750E93F7-2E92-4298-982A-D1BFBCF07378:3
,2016-04-07 21:25:43.351 ThaliTest[556:945007] THEMultipeerManager initialized peer 750E93F7-2E92-4298-982A-D1BFBCF07378:3
2016-04-07 21:25:43.351 ThaliTest[556:945007] jxcore: startUpdateAdvertisingAndListening: success
,ok 120 called only once
,ok 121 discovery state matches
,ok 122 advertising state matches
,# teardown
,2016-04-07 21:25:43.651 ThaliTest[556:945007] jxcore: stopAdvertisingAndListening
,2016-04-07 21:25:43.652 ThaliTest[556:945007] THEMultipeerManager stopping peer
2016-04-07 21:25:43.652 ThaliTest[556:945007] jxcore: stopAdvertisingAndListening: success
,2016-04-07 21:25:43.653 ThaliTest[556:945007] jxcore: stopListeningForAdvertisements
2016-04-07 21:25:43.654 ThaliTest[556:945007] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:25:43.657 ThaliTest[556:945007] jxcore: stopListeningForAdvertisements: success
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
,2016-04-07 21:26:14.509 ThaliTest[556:945007] jxcore: startListeningForAdvertisements
,2016-04-07 21:26:14.510 ThaliTest[556:945007] multipeer manager: start client restart timer: 0x1767afc0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-07 21:26:14.513 ThaliTest[556:945007] jxcore: startListeningForAdvertisements: success
ok 138 Can call startListeningForAdvertisements without error
,2016-04-07 21:26:14.518 ThaliTest[556:945007] jxcore: stopListeningForAdvertisements
2016-04-07 21:26:14.519 ThaliTest[556:945007] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingAc,tive":false,"discoveryActive":false}
,2016-04-07 21:26:14.521 ThaliTest[556:945007] jxcore: stopListeningForAdvertisements: success
,ok 139 Can call stopListeningForAdvertisements without error
,# teardown
,2016-04-07 21:26:36.522 ThaliTest[556:945007] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-07 21:26:36.525 ThaliTest[556:945007] jxcore: stopListeningForAdvertisements: success
,ok 140 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-07 21:26:36.528 ThaliTest[556:945007] jxcore: stopAdvertisingAndListening
,2016-04-07 21:26:36.528 ThaliTest[556:945007] THEMultipeerManager stopping peer
,2016-04-07 21:26:36.529 ThaliTest[556:945007] jxcore: stopAdvertisingAndListening: success
,ok 141 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 35. Calling startListeningForAdvertisements twice is NOT an error
,2016-04-07 21:26:54.836 ThaliTest[556:945007] jxcore: startListeningForAdvertisements
,2016-04-07 21:26:54.837 ThaliTest[556:945007] multipeer manager: start client restart timer: 0x1767afc0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-07 21:26:54.840 ThaliTest[556:945007] jxcore: startListeningForAdvertisements: success
,ok 142 Can call startListeningForAdvertisements without error
2016-04-07 21:26:54.845 ThaliTest[556:945007] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-07 21:26:54.848 ThaliTest[556:945007] jxcore: startListeningForAdvertisements: success
,ok 143 Can call startListeningForAdvertisements twice without error
,# teardown
,2016-04-07 21:26:55.639 ThaliTest[556:945007] jxcore: stopListeningForAdvertisements
,2016-04-07 21:26:55.640 ThaliTest[556:945007] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:26:55.644 ThaliTest[556:945007] jxcore: stopListeningForAdvertisements: success
,ok 144 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-07 21:26:55.647 ThaliTest[556:945007] jxcore: stopAdvertisingAndListening
,2016-04-07 21:26:55.647 ThaliTest[556:945007] THEMultipeerManager stopping peer
,2016-04-07 21:26:55.648 ThaliTest[556:945007] jxcore: stopAdvertisingAndListening: success
,ok 145 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 36. Calling stopListeningForAdvertisements without calling start is NOT an error
,2016-04-07 21:27:21.385 ThaliTest[556:945007] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-07 21:27:21.388 ThaliTest[556:945007] jxcore: stopListeningForAdvertisements: success
,ok 146 Can call stopListeningForAdvertisements without error
,2016-04-07 21:27:21.391 ThaliTest[556:945007] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-07 21:27:21.393 ThaliTest[556:945007] jxcore: stopListeningForAdvertisements: success
,ok 147 Can call stopListeningForAdvertisements without error
,# teardown
,2016-04-07 21:27:21.567 ThaliTest[556:945007] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-07 21:27:21.570 ThaliTest[556:945007] jxcore: stopListeningForAdvertisements: success
,ok 148 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-07 21:27:21.572 ThaliTest[556:945007] jxcore: stopAdvertisingAndListening
,2016-04-07 21:27:21.573 ThaliTest[556:945007] THEMultipeerManager stopping peer
,2016-04-07 21:27:21.573 ThaliTest[556:945007] jxcore: stopAdvertisingAndListening: success
,ok 149 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 37. Can call start/stopUpdateAdvertisingAndListening
,2016-04-07 21:27:21.865 ThaliTest[556:945007] jxcore: startUpdateAdvertisingAndListening
,2016-04-07 21:27:21.866 ThaliTest[556:945007] server: starting 750E93F7-2E92-4298-982A-D1BFBCF07378:4
,2016-04-07 21:27:21.868 ThaliTest[556:945007] multipeer manager: start client restart timer: 0x1767afc0
2016-04-07 21:27:21.868 ThaliTest[556:945007] THEMultipeerManager initialized peer 750E93F7-2E92-4298-982A-D1BFBCF07378:4
2016-04-07 21:27:21.869 Thal,iTest[556:945007] jxcore: startUpdateAdvertisingAndListening: success
,ok 150 Can call startUpdateAdvertisingAndListening without error
,2016-04-07 21:27:21.872 ThaliTest[556:945007] jxcore: stopAdvertisingAndListening
2016-04-07 21:27:21.872 ThaliTest[556:945007] THEMultipeerManager stopping peer
2016-04-07 21:27:21.873 ThaliTest[556:945007] multipeer manager: stop client timer
2016-04-,07 21:27:21.875 ThaliTest[556:945007] jxcore: stopAdvertisingAndListening: success
ok 151 Can call stopAdvertisingAndListening without error
,# teardown
,2016-04-07 21:27:22.181 ThaliTest[556:945007] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-07 21:27:22.183 ThaliTest[556:945007] jxcore: stopListeningForAdvertisements: success
,ok 152 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-07 21:27:22.186 ThaliTest[556:945007] jxcore: stopAdvertisingAndListening
,2016-04-07 21:27:22.186 ThaliTest[556:945007] THEMultipeerManager stopping peer
,2016-04-07 21:27:22.187 ThaliTest[556:945007] jxcore: stopAdvertisingAndListening: success
,ok 153 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-04-07 21:27:22.660 ThaliTest[556:945007] jxcore: startUpdateAdvertisingAndListening
,2016-04-07 21:27:22.661 ThaliTest[556:945007] server: starting 750E93F7-2E92-4298-982A-D1BFBCF07378:5
,2016-04-07 21:27:22.662 ThaliTest[556:945007] multipeer manager: start client restart timer: 0x1767afc0
2016-04-07 21:27:22.662 ThaliTest[556:945007] THEMultipeerManager initialized peer 750E93F7-2E92-4298-982A-D1BFBCF07378:5
2016-04-07 21:27:22.663 Thal,iTest[556:945007] jxcore: startUpdateAdvertisingAndListening: success
ok 154 Can call startUpdateAdvertisingAndListening without error
,2016-04-07 21:27:22.665 ThaliTest[556:945007] jxcore: startUpdateAdvertisingAndListening
2016-04-07 21:27:22.666 ThaliTest[556:945007] THEMultipeerManager stopping peer
,2016-04-07 21:27:22.666 ThaliTest[556:945007] multipeer manager: stop client timer
,2016-04-07 21:27:22.667 ThaliTest[556:945007] server: starting 750E93F7-2E92-4298-982A-D1BFBCF07378:6
,2016-04-07 21:27:22.668 ThaliTest[556:945007] multipeer manager: start client restart timer: 0x1767afc0
2016-04-07 21:27:22.668 ThaliTest[556:945007] THEMultipeerManager initialized peer 750E93F7-2E92-4298-982A-D1BFBCF07378:6
2016-04-07 21:27:22.669 Thal,iTest[556:945007] jxcore: startUpdateAdvertisingAndListening: success
ok 155 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,2016-04-07 21:27:22.797 ThaliTest[556:945007] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-07 21:27:22.799 ThaliTest[556:945007] jxcore: stopListeningForAdvertisements: success
,ok 156 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-07 21:27:22.802 ThaliTest[556:945007] jxcore: stopAdvertisingAndListening
,2016-04-07 21:27:22.802 ThaliTest[556:945007] THEMultipeerManager stopping peer
,2016-04-07 21:27:22.803 ThaliTest[556:945007] multipeer manager: stop client timer
2016-04-07 21:27:22.805 ThaliTest[556:945007] jxcore: stopAdvertisingAndListening: success
,ok 157 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,2016-04-07 21:27:42.968 ThaliTest[556:945007] jxcore: stopAdvertisingAndListening
,2016-04-07 21:27:42.969 ThaliTest[556:945007] THEMultipeerManager stopping peer
,2016-04-07 21:27:42.969 ThaliTest[556:945007] jxcore: stopAdvertisingAndListening: success
,ok 158 Can call startUpdateAdvertisingAndListening without error
,2016-04-07 21:27:42.973 ThaliTest[556:945007] jxcore: stopAdvertisingAndListening
,2016-04-07 21:27:42.973 ThaliTest[556:945007] THEMultipeerManager stopping peer
,2016-04-07 21:27:42.974 ThaliTest[556:945007] jxcore: stopAdvertisingAndListening: success
,ok 159 Can call stopAdvertisingAndListening without error
,# teardown
,2016-04-07 21:27:55.477 ThaliTest[556:945007] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-07 21:27:55.480 ThaliTest[556:945007] jxcore: stopListeningForAdvertisements: success
,ok 160 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-07 21:27:55.483 ThaliTest[556:945007] jxcore: stopAdvertisingAndListening
,2016-04-07 21:27:55.483 ThaliTest[556:945007] THEMultipeerManager stopping peer
,2016-04-07 21:27:55.483 ThaliTest[556:945007] jxcore: stopAdvertisingAndListening: success
,ok 161 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 40. cannot call connect when start listening for advertisements is not active
,2016-04-07 21:27:55.933 ThaliTest[556:945007] jxcore: connect foo
,2016-04-07 21:27:55.934 ThaliTest[556:945007] jxcore: connect: fail: Start browsing first
,not ok 162 got right error
,  ---
,    operator: equal
,    expected: 'startListeningForAdvertisements is not active'
,    actual:   'Start browsing first'
,  ...
,# teardown
,2016-04-07 21:27:56.059 ThaliTest[556:945007] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-07 21:27:56.062 ThaliTest[556:945007] jxcore: stopListeningForAdvertisements: success
,ok 163 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-07 21:27:56.065 ThaliTest[556:945007] jxcore: stopAdvertisingAndListening
,2016-04-07 21:27:56.065 ThaliTest[556:945007] THEMultipeerManager stopping peer
,2016-04-07 21:27:56.065 ThaliTest[556:945007] jxcore: stopAdvertisingAndListening: success
,ok 164 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 41. peerAvailabilityChange is called
,2016-04-07 21:27:56.243 ThaliTest[556:945007] jxcore: startUpdateAdvertisingAndListening
,2016-04-07 21:27:56.243 ThaliTest[556:945007] server: starting 750E93F7-2E92-4298-982A-D1BFBCF07378:7
,2016-04-07 21:27:56.245 ThaliTest[556:945007] multipeer manager: start client restart timer: 0x1767afc0
2016-04-07 21:27:56.245 ThaliTest[556:945007] THEMultipeerManager initialized peer 750E93F7-2E92-4298-982A-D1BFBCF07378:7
2016-04-07 21:27:56.245 Thal,iTest[556:945007] jxcore: startUpdateAdvertisingAndListening: success
ok 165 Can call startUpdateAdvertisingAndListeningwithout error
,2016-04-07 21:27:56.248 ThaliTest[556:945007] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-04-07 21:27:56.251 ThaliTest[556:945007] jxcore: startListeningForAdvertisements: success
ok 166 Can call startListeningForAdvertisements without error
,2016-04-07 21:27:57.294 ThaliTest[556:944746] client: found new peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:7
,ok 167 peers must be an array
,ok 168 peers must not be zero-length
,ok 169 peer must have peerIdentifier
,ok 170 peerIdentifier must be a string
,ok 171 peer must have peerAvailable
,ok 172 peer must have pleaseConnect
,# teardown
,2016-04-07 21:27:57.388 ThaliTest[556:944746] client: found new peer: BF68E1C5-762A-429C-BDD9-41F21131A115:7
,2016-04-07 21:27:57.863 ThaliTest[556:944746] client: found new peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:7
,2016-04-07 21:28:00.833 ThaliTest[556:945007] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-07 21:28:00.835 ThaliTest[556:945007] jxcore: stopListeningForAdvertisements: success
,ok 173 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-07 21:28:00.838 ThaliTest[556:945007] jxcore: stopAdvertisingAndListening
,2016-04-07 21:28:00.838 ThaliTest[556:945007] THEMultipeerManager stopping peer
,2016-04-07 21:28:00.839 ThaliTest[556:945007] multipeer manager: stop client timer
2016-04-07 21:28:00.840 ThaliTest[556:945007] jxcore: stopAdvertisingAndListening: success
,ok 174 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 42. Can connect to a remote peer
,2016-04-07 21:28:31.165 ThaliTest[556:945007] jxcore: startUpdateAdvertisingAndListening
,2016-04-07 21:28:31.165 ThaliTest[556:945007] server: starting 750E93F7-2E92-4298-982A-D1BFBCF07378:8
,2016-04-07 21:28:31.167 ThaliTest[556:945007] multipeer manager: start client restart timer: 0x1767afc0
2016-04-07 21:28:31.167 ThaliTest[556:945007] THEMultipeerManager initialized peer 750E93F7-2E92-4298-982A-D1BFBCF07378:8
2016-04-07 21:28:31.167 Thal,iTest[556:945007] jxcore: startUpdateAdvertisingAndListening: success
ok 175 Can call startUpdateAdvertisingAndListening without error
,2016-04-07 21:28:31.169 ThaliTest[556:945007] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-04-07 21:28:31.172 ThaliTest[556:945007] jxcore: startListeningForAdvertisements: success
ok 176 Can call startListeningForAdver,tisements without error
,2016-04-07 21:28:32.310 ThaliTest[556:944746] client: found new peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:7
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:7","pleaseConnect":0}]
,2016-04-07 21:28:32.314 ThaliTest[556:945007] jxcore: connect E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:7
,2016-04-07 21:28:32.315 ThaliTest[556:945007] client: server will connect
,2016-04-07 21:28:32.316 ThaliTest[556:945007] client session: reverseConnect
,2016-04-07 21:28:32.316 ThaliTest[556:945007] client session: stateChange:0->1 E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:7
,2016-04-07 21:28:32.769 ThaliTest[556:944746] client: found new peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:7
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:7","pleaseConnect":0}]
,2016-04-07 21:28:34.580 ThaliTest[556:944746] client: found new peer: BF68E1C5-762A-429C-BDD9-41F21131A115:8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"BF68E1C5-762A-429C-BDD9-41F21131A115:8","pleaseConnect":0}]
,2016-04-07 21:28:35.540 ThaliTest[556:944746] multipeer session: reset timer
,2016-04-07 21:28:35.541 ThaliTest[556:944746] server: rejecting invitation from 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499 due to previous generation (750E93F7-2E92-4298-982A-D1BFBCF07378:8 != 750E93F7-2E92-4298-982A-D1BFBCF07378:7)
,2016-04-07 21:28:35.797 ThaliTest[556:944746] multipeer session: reset timer
,2016-04-07 21:28:35.798 ThaliTest[556:944746] server: rejecting invitation from BF68E1C5-762A-429C-BDD9-41F21131A115 due to previous generation (750E93F7-2E92-4298-982A-D1BFBCF07378:8 != 750E93F7-2E92-4298-982A-D1BFBCF07378:7)
,2016-04-07 21:28:36.141 ThaliTest[556:945765] client session: not connected E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:7
2016-04-07 21:28:36.141 ThaliTest[556:945765] client session: onLinkFailure: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9
2016-04-07 21:28:36.141 ThaliTest[556:945765] client session: disconnect
,2016-04-07 21:28:36.143 ThaliTest[556:945765] client session: stateChange:1->0 E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:7
2016-04-07 21:28:36.144 ThaliTest[556:945765] client session: no connect callback (server initiated)
,2016-04-07 21:28:39.070 ThaliTest[556:944746] multipeer session: reset timer
,2016-04-07 21:28:39.070 ThaliTest[556:944746] server: disconnecting to refresh session (BF68E1C5-762A-429C-BDD9-41F21131A115)
,2016-04-07 21:28:39.071 ThaliTest[556:944746] server: rejecting invitation from BF68E1C5-762A-429C-BDD9-41F21131A115 due to previous generation (750E93F7-2E92-4298-982A-D1BFBCF07378:8 != 750E93F7-2E92-4298-982A-D1BFBCF07378:7)
,2016-04-07 21:28:42.316 ThaliTest[556:944746] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-04-07 21:28:43.193 ThaliTest[556:944746] multipeer session: reset timer
2016-04-07 21:28:43.194 ThaliTest[556:944746] server: disconnecting to refresh session (BF68E1C5-762A-429C-BDD9-41F21131A115)
2016-04-07 21:28:43.194 ThaliTest[556:944746] serve,r: rejecting invitation from BF68E1C5-762A-429C-BDD9-41F21131A115 due to previous generation (750E93F7-2E92-4298-982A-D1BFBCF07378:8 != 750E93F7-2E92-4298-982A-D1BFBCF07378:7)
,2016-04-07 21:28:45.330 ThaliTest[556:945007] jxcore: connect E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:7
,2016-04-07 21:28:45.331 ThaliTest[556:945007] client: server will connect
,2016-04-07 21:28:45.332 ThaliTest[556:945007] client session: reverseConnect
,2016-04-07 21:28:45.332 ThaliTest[556:945007] client session: stateChange:0->1 E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:7
,2016-04-07 21:28:46.543 ThaliTest[556:945791] client session: not connected E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:7
,2016-04-07 21:28:46.544 ThaliTest[556:945791] client session: onLinkFailure: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9
,2016-04-07 21:28:46.545 ThaliTest[556:945791] client session: disconnect
,2016-04-07 21:28:46.545 ThaliTest[556:945791] client session: stateChange:1->0 E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:7
,2016-04-07 21:28:46.546 ThaliTest[556:945791] client session: no connect callback (server initiated)
,2016-04-07 21:28:46.865 ThaliTest[556:944746] multipeer session: reset timer
2016-04-07 21:28:46.866 ThaliTest[556:944746] server: disconnecting to refresh session (BF68E1C5-762A-429C-BDD9-41F21131A115)
,2016-04-07 21:28:46.866 ThaliTest[556:944746] server: rejecting invitation from BF68E1C5-762A-429C-BDD9-41F21131A115 due to previous generation (750E93F7-2E92-4298-982A-D1BFBCF07378:8 != 750E93F7-2E92-4298-982A-D1BFBCF07378:7)
,2016-04-07 21:28:46.983 ThaliTest[556:944746] multipeer session: reset timer
,2016-04-07 21:28:46.984 ThaliTest[556:944746] server: disconnecting to refresh session (3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499)
,2016-04-07 21:28:46.984 ThaliTest[556:944746] server: rejecting invitation from 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499 due to previous generation (750E93F7-2E92-4298-982A-D1BFBCF07378:8 != 750E93F7-2E92-4298-982A-D1BFBCF07378:7)
,2016-04-07 21:28:50.531 ThaliTest[556:944746] multipeer session: reset timer
2016-04-07 21:28:50.531 ThaliTest[556:944746] server: disconnecting to refresh session (BF68E1C5-762A-429C-BDD9-41F21131A115)
2016-04-07 21:28:50.531 ThaliTest[556:944746] serve,r: rejecting invitation from BF68E1C5-762A-429C-BDD9-41F21131A115 due to previous generation (750E93F7-2E92-4298-982A-D1BFBCF07378:8 != 750E93F7-2E92-4298-982A-D1BFBCF07378:7)
,2016-04-07 21:28:51.168 ThaliTest[556:944746] multipeer manager: restart client
,2016-04-07 21:28:51.189 ThaliTest[556:944746] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:8
2016-04-07 21:28:51.189 ThaliTest[556:944746] client: found updated peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:8","pleaseConnect":0}]
,2016-04-07 21:28:51.494 ThaliTest[556:944746] client: found updated peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8","pleaseConnect":0}]
,2016-04-07 21:28:54.220 ThaliTest[556:944746] multipeer session: reset timer
,2016-04-07 21:28:54.221 ThaliTest[556:944746] server: disconnecting to refresh session (BF68E1C5-762A-429C-BDD9-41F21131A115)
,2016-04-07 21:28:54.221 ThaliTest[556:944746] server: rejecting invitation from BF68E1C5-762A-429C-BDD9-41F21131A115 due to previous generation (750E93F7-2E92-4298-982A-D1BFBCF07378:8 != 750E93F7-2E92-4298-982A-D1BFBCF07378:7)
,2016-04-07 21:28:55.333 ThaliTest[556:944746] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-04-07 21:28:57.483 ThaliTest[556:944746] multipeer session: reset timer
,2016-04-07 21:28:57.483 ThaliTest[556:944746] server: disconnecting to refresh session (BF68E1C5-762A-429C-BDD9-41F21131A115)
,2016-04-07 21:28:57.483 ThaliTest[556:944746] server: rejecting invitation from BF68E1C5-762A-429C-BDD9-41F21131A115 due to previous generation (750E93F7-2E92-4298-982A-D1BFBCF07378:8 != 750E93F7-2E92-4298-982A-D1BFBCF07378:7)
,2016-04-07 21:28:58.349 ThaliTest[556:945007] jxcore: connect E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:7
,2016-04-07 21:28:58.349 ThaliTest[556:945007] client: server will connect
,2016-04-07 21:28:58.350 ThaliTest[556:945007] client session: reverseConnect
,2016-04-07 21:28:58.351 ThaliTest[556:945007] client session: stateChange:0->1 E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
,2016-04-07 21:28:58.549 ThaliTest[556:945763] client session: not connected E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
,2016-04-07 21:28:58.550 ThaliTest[556:945763] client session: onLinkFailure: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9
2016-04-07 21:28:58.551 ThaliTest[556:945763] client session: disconnect
2016-04-07 21:28:58.551 ThaliTest[556:945763] client session: stateChange:1->0 E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
,2016-04-07 21:28:58.552 ThaliTest[556:945763] client session: no connect callback (server initiated)
,2016-04-07 21:29:00.260 ThaliTest[556:944746] multipeer session: reset timer
2016-04-07 21:29:00.261 ThaliTest[556:944746] server: disconnecting to refresh session (3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499)
2016-04-07 21:29:00.261 ThaliTest[556:944746] serve,r: rejecting invitation from 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499 due to previous generation (750E93F7-2E92-4298-982A-D1BFBCF07378:8 != 750E93F7-2E92-4298-982A-D1BFBCF07378:7)
,2016-04-07 21:29:01.084 ThaliTest[556:944746] multipeer session: reset timer
,2016-04-07 21:29:01.085 ThaliTest[556:944746] server: disconnecting to refresh session (BF68E1C5-762A-429C-BDD9-41F21131A115)
,2016-04-07 21:29:01.085 ThaliTest[556:944746] server: rejecting invitation from BF68E1C5-762A-429C-BDD9-41F21131A115 due to previous generation (750E93F7-2E92-4298-982A-D1BFBCF07378:8 != 750E93F7-2E92-4298-982A-D1BFBCF07378:7)
,2016-04-07 21:29:04.286 ThaliTest[556:944746] multipeer session: reset timer
,2016-04-07 21:29:04.286 ThaliTest[556:944746] server: disconnecting to refresh session (BF68E1C5-762A-429C-BDD9-41F21131A115)
,2016-04-07 21:29:04.286 ThaliTest[556:944746] server: rejecting invitation from BF68E1C5-762A-429C-BDD9-41F21131A115 due to previous generation (750E93F7-2E92-4298-982A-D1BFBCF07378:8 != 750E93F7-2E92-4298-982A-D1BFBCF07378:7)
,2016-04-07 21:29:07.635 ThaliTest[556:944746] multipeer session: reset timer
,2016-04-07 21:29:07.636 ThaliTest[556:944746] server: disconnecting to refresh session (BF68E1C5-762A-429C-BDD9-41F21131A115)
,2016-04-07 21:29:07.636 ThaliTest[556:944746] server: rejecting invitation from BF68E1C5-762A-429C-BDD9-41F21131A115 due to previous generation (750E93F7-2E92-4298-982A-D1BFBCF07378:8 != 750E93F7-2E92-4298-982A-D1BFBCF07378:7)
,2016-04-07 21:29:08.351 ThaliTest[556:944746] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-04-07 21:29:11.168 ThaliTest[556:944746] multipeer manager: restart client
,2016-04-07 21:29:11.193 ThaliTest[556:944746] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
2016-04-07 21:29:11.194 ThaliTest[556:944746] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:8
,2016-04-07 21:29:11.195 ThaliTest[556:944746] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:8
,2016-04-07 21:29:11.357 ThaliTest[556:945007] jxcore: connect E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:7
,2016-04-07 21:29:11.358 ThaliTest[556:945007] client: server will connect
,2016-04-07 21:29:11.359 ThaliTest[556:945007] client session: reverseConnect
2016-04-07 21:29:11.360 ThaliTest[556:945007] client session: stateChange:0->1 E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
,2016-04-07 21:29:11.963 ThaliTest[556:945791] client session: not connected E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
,2016-04-07 21:29:11.965 ThaliTest[556:945791] client session: onLinkFailure: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9
,2016-04-07 21:29:11.966 ThaliTest[556:945791] client session: disconnect
,2016-04-07 21:29:11.966 ThaliTest[556:945791] client session: stateChange:1->0 E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
,2016-04-07 21:29:11.967 ThaliTest[556:945791] client session: no connect callback (server initiated)
,2016-04-07 21:29:13.076 ThaliTest[556:944746] multipeer session: reset timer
,2016-04-07 21:29:13.076 ThaliTest[556:944746] server: disconnecting to refresh session (3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499)
,2016-04-07 21:29:13.077 ThaliTest[556:944746] server: rejecting invitation from 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499 due to previous generation (750E93F7-2E92-4298-982A-D1BFBCF07378:8 != 750E93F7-2E92-4298-982A-D1BFBCF07378:7)
,2016-04-07 21:29:21.360 ThaliTest[556:944746] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-04-07 21:29:24.375 ThaliTest[556:945007] jxcore: connect E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:7
,2016-04-07 21:29:24.375 ThaliTest[556:945007] client: server will connect
,2016-04-07 21:29:24.376 ThaliTest[556:945007] client session: reverseConnect
2016-04-07 21:29:24.377 ThaliTest[556:945007] client session: stateChange:0->1 E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
,2016-04-07 21:29:25.010 ThaliTest[556:945964] client session: not connected E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
2016-04-07 21:29:25.010 ThaliTest[556:945964] client session: onLinkFailure: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9
2016-04-07 21:29:25.011 T,haliTest[556:945964] client session: disconnect
2016-04-07 21:29:25.011 ThaliTest[556:945964] client session: stateChange:1->0 E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
,2016-04-07 21:29:25.012 ThaliTest[556:945964] client session: no connect callback (server initiated)
,2016-04-07 21:29:26.181 ThaliTest[556:944746] multipeer session: reset timer
,2016-04-07 21:29:26.181 ThaliTest[556:944746] server: disconnecting to refresh session (3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499)
,2016-04-07 21:29:26.182 ThaliTest[556:944746] server: rejecting invitation from 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499 due to previous generation (750E93F7-2E92-4298-982A-D1BFBCF07378:8 != 750E93F7-2E92-4298-982A-D1BFBCF07378:7)
,2016-04-07 21:29:31.168 ThaliTest[556:944746] multipeer manager: restart client
,2016-04-07 21:29:31.201 ThaliTest[556:944746] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
2016-04-07 21:29:31.202 ThaliTest[556:944746] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:8
2016-04-07 21:29:31.202 ThaliTest[556:944746] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:8
,2016-04-07 21:29:34.378 ThaliTest[556:944746] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-04-07 21:29:37.389 ThaliTest[556:945007] jxcore: connect E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:7
,2016-04-07 21:29:37.390 ThaliTest[556:945007] client: server will connect
,2016-04-07 21:29:37.390 ThaliTest[556:945007] client session: reverseConnect
2016-04-07 21:29:37.391 ThaliTest[556:945007] client session: stateChange:0->1 E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
,2016-04-07 21:29:38.229 ThaliTest[556:946009] client session: not connected E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
,2016-04-07 21:29:38.229 ThaliTest[556:946009] client session: onLinkFailure: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9
,2016-04-07 21:29:38.231 ThaliTest[556:946009] client session: disconnect
,2016-04-07 21:29:38.231 ThaliTest[556:946009] client session: stateChange:1->0 E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
,2016-04-07 21:29:38.232 ThaliTest[556:946009] client session: no connect callback (server initiated)
,2016-04-07 21:29:39.049 ThaliTest[556:944746] multipeer session: reset timer
,2016-04-07 21:29:39.049 ThaliTest[556:944746] server: disconnecting to refresh session (3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499)
,2016-04-07 21:29:39.049 ThaliTest[556:944746] server: rejecting invitation from 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499 due to previous generation (750E93F7-2E92-4298-982A-D1BFBCF07378:8 != 750E93F7-2E92-4298-982A-D1BFBCF07378:7)
,2016-04-07 21:29:47.391 ThaliTest[556:944746] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-04-07 21:29:50.402 ThaliTest[556:945007] jxcore: connect E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:7
,2016-04-07 21:29:50.402 ThaliTest[556:945007] client: server will connect
,2016-04-07 21:29:50.403 ThaliTest[556:945007] client session: reverseConnect
,2016-04-07 21:29:50.403 ThaliTest[556:945007] client session: stateChange:0->1 E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
,2016-04-07 21:29:51.004 ThaliTest[556:946040] client session: not connected E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
2016-04-07 21:29:51.004 ThaliTest[556:946040] client session: onLinkFailure: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9
2016-04-07 21:29:51.004 T,haliTest[556:946040] client session: disconnect
2016-04-07 21:29:51.005 ThaliTest[556:946040] client session: stateChange:1->0 E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
2016-04-07 21:29:51.006 ThaliTest[556:946040] client session: no connect callback (serve,r initiated)
,2016-04-07 21:29:51.168 ThaliTest[556:944746] multipeer manager: restart client
,2016-04-07 21:29:51.194 ThaliTest[556:944746] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:8
2016-04-07 21:29:51.194 ThaliTest[556:944746] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
,2016-04-07 21:29:51.195 ThaliTest[556:944746] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:8
,2016-04-07 21:29:52.043 ThaliTest[556:944746] multipeer session: reset timer
2016-04-07 21:29:52.044 ThaliTest[556:944746] server: disconnecting to refresh session (3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499)
2016-04-07 21:29:52.044 ThaliTest[556:944746] serve,r: rejecting invitation from 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499 due to previous generation (750E93F7-2E92-4298-982A-D1BFBCF07378:8 != 750E93F7-2E92-4298-982A-D1BFBCF07378:7)
,2016-04-07 21:30:00.404 ThaliTest[556:944746] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-04-07 21:30:03.414 ThaliTest[556:945007] jxcore: connect E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:7
,2016-04-07 21:30:03.414 ThaliTest[556:945007] client: server will connect
,2016-04-07 21:30:03.415 ThaliTest[556:945007] client session: reverseConnect
2016-04-07 21:30:03.416 ThaliTest[556:945007] client session: stateChange:0->1 E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
,2016-04-07 21:30:03.653 ThaliTest[556:946073] client session: not connected E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
2016-04-07 21:30:03.653 ThaliTest[556:946073] client session: onLinkFailure: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9
2016-04-07 21:30:03.654 T,haliTest[556:946073] client session: disconnect
2016-04-07 21:30:03.654 ThaliTest[556:946073] client session: stateChange:1->0 E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
,2016-04-07 21:30:03.656 ThaliTest[556:946073] client session: no connect callback (server initiated)
,2016-04-07 21:30:05.035 ThaliTest[556:944746] multipeer session: reset timer
,2016-04-07 21:30:05.035 ThaliTest[556:944746] server: disconnecting to refresh session (3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499)
,2016-04-07 21:30:05.036 ThaliTest[556:944746] server: rejecting invitation from 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499 due to previous generation (750E93F7-2E92-4298-982A-D1BFBCF07378:8 != 750E93F7-2E92-4298-982A-D1BFBCF07378:7)
,2016-04-07 21:30:11.168 ThaliTest[556:944746] multipeer manager: restart client
,2016-04-07 21:30:11.195 ThaliTest[556:944746] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:8
2016-04-07 21:30:11.195 ThaliTest[556:944746] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
2016-04-07 21:30:11.195 ThaliTest[556:944746] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:8
,2016-04-07 21:30:13.416 ThaliTest[556:944746] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-04-07 21:30:16.423 ThaliTest[556:945007] jxcore: connect E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:7
,2016-04-07 21:30:16.424 ThaliTest[556:945007] client: server will connect
,2016-04-07 21:30:16.424 ThaliTest[556:945007] client session: reverseConnect
,2016-04-07 21:30:16.425 ThaliTest[556:945007] client session: stateChange:0->1 E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
,2016-04-07 21:30:16.699 ThaliTest[556:946075] client session: not connected E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
,2016-04-07 21:30:16.700 ThaliTest[556:946075] client session: onLinkFailure: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9
,2016-04-07 21:30:16.700 ThaliTest[556:946075] client session: disconnect
,2016-04-07 21:30:16.700 ThaliTest[556:946075] client session: stateChange:1->0 E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
,2016-04-07 21:30:16.701 ThaliTest[556:946075] client session: no connect callback (server initiated)
,2016-04-07 21:30:17.998 ThaliTest[556:944746] multipeer session: reset timer
,2016-04-07 21:30:17.998 ThaliTest[556:944746] server: disconnecting to refresh session (3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499)
,2016-04-07 21:30:17.999 ThaliTest[556:944746] server: rejecting invitation from 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499 due to previous generation (750E93F7-2E92-4298-982A-D1BFBCF07378:8 != 750E93F7-2E92-4298-982A-D1BFBCF07378:7)
,2016-04-07 21:30:26.426 ThaliTest[556:944746] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-04-07 21:30:29.439 ThaliTest[556:945007] jxcore: connect E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:7
,2016-04-07 21:30:29.440 ThaliTest[556:945007] client: server will connect
,2016-04-07 21:30:29.440 ThaliTest[556:945007] client session: reverseConnect
2016-04-07 21:30:29.441 ThaliTest[556:945007] client session: stateChange:0->1 E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
,2016-04-07 21:30:29.738 ThaliTest[556:946043] client session: not connected E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
,2016-04-07 21:30:29.738 ThaliTest[556:946043] client session: onLinkFailure: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9
2016-04-07 21:30:29.740 ThaliTest[556:946043] client session: disconnect
,2016-04-07 21:30:29.740 ThaliTest[556:946043] client session: stateChange:1->0 E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
,2016-04-07 21:30:29.741 ThaliTest[556:946043] client session: no connect callback (server initiated)
,2016-04-07 21:30:31.168 ThaliTest[556:944746] multipeer manager: restart client
,2016-04-07 21:30:31.199 ThaliTest[556:944746] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:8
2016-04-07 21:30:31.199 ThaliTest[556:944746] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
,2016-04-07 21:30:31.201 ThaliTest[556:944746] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:8
,2016-04-07 21:30:39.442 ThaliTest[556:944746] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,WARN testThaliMobileNative: Too many connect retries!
,not ok 177 Connect failed!
,  ---
,    operator: fail
,  ...
,# teardown
,2016-04-07 21:30:42.283 ThaliTest[556:945007] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-07 21:30:42.285 ThaliTest[556:945007] jxcore: stopListeningForAdvertisements: success
,ok 178 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-07 21:30:42.288 ThaliTest[556:945007] jxcore: stopAdvertisingAndListening
,2016-04-07 21:30:42.288 ThaliTest[556:945007] THEMultipeerManager stopping peer
,2016-04-07 21:30:42.290 ThaliTest[556:945007] multipeer manager: stop client timer
2016-04-07 21:30:42.292 ThaliTest[556:945007] jxcore: stopAdvertisingAndListening: success
ok 179 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 43. Get error when trying to double connect to a peer
,2016-04-07 21:30:46.097 ThaliTest[556:945007] jxcore: startUpdateAdvertisingAndListening
,2016-04-07 21:30:46.097 ThaliTest[556:945007] server: starting 750E93F7-2E92-4298-982A-D1BFBCF07378:9
,2016-04-07 21:30:46.099 ThaliTest[556:945007] multipeer manager: start client restart timer: 0x1767afc0
2016-04-07 21:30:46.099 ThaliTest[556:945007] THEMultipeerManager initialized peer 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:30:46.100 Thal,iTest[556:945007] jxcore: startUpdateAdvertisingAndListening: success
ok 180 Can call startUpdateAdvertisingAndListening without error
2016-04-07 21:30:46.102 ThaliTest[556:945007] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
,2016-04-07 21:30:46.109 ThaliTest[556:945007] jxcore: startListeningForAdvertisements: success
,ok 181 Can call startListeningForAdvertisements without error
,2016-04-07 21:30:46.203 ThaliTest[556:944746] client: found new peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
,2016-04-07 21:30:46.207 ThaliTest[556:945007] jxcore: connect E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
,2016-04-07 21:30:46.208 ThaliTest[556:945007] client: server will connect
,2016-04-07 21:30:46.209 ThaliTest[556:945007] client session: reverseConnect
,2016-04-07 21:30:46.210 ThaliTest[556:945007] client session: stateChange:0->1 E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
,2016-04-07 21:30:50.418 ThaliTest[556:944746] client: found new peer: BF68E1C5-762A-429C-BDD9-41F21131A115:8
,2016-04-07 21:30:50.702 ThaliTest[556:944746] multipeer session: reset timer
,2016-04-07 21:30:50.702 ThaliTest[556:944746] server: rejecting invitation from 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499 due to previous generation (750E93F7-2E92-4298-982A-D1BFBCF07378:9 != 750E93F7-2E92-4298-982A-D1BFBCF07378:8)
,2016-04-07 21:30:50.759 ThaliTest[556:944746] client: found new peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:8
,2016-04-07 21:30:52.164 ThaliTest[556:944746] multipeer session: reset timer
,2016-04-07 21:30:52.165 ThaliTest[556:944746] server session: connect
,2016-04-07 21:30:52.165 ThaliTest[556:944746] server session: stateChange:0->1 BF68E1C5-762A-429C-BDD9-41F21131A115:9
,2016-04-07 21:30:52.172 ThaliTest[556:944746] server: accepting invitation BF68E1C5-762A-429C-BDD9-41F21131A115
,2016-04-07 21:30:55.320 ThaliTest[556:946165] server session: p2p link connected
,2016-04-07 21:30:55.461 ThaliTest[556:944746] server relay: connected (to port: 51862)
,2016-04-07 21:30:55.462 ThaliTest[556:944746] server session: stateChange:1->2 BF68E1C5-762A-429C-BDD9-41F21131A115:9
,2016-04-07 21:30:56.210 ThaliTest[556:944746] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-04-07 21:30:56.340 ThaliTest[556:944746] client: lost peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9
2016-04-07 21:30:56.341 ThaliTest[556:944746] client session: onPeerLost: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9
2016-04-07 21:30:56.341 ThaliTest[556:944,746] client session: onLinkFailure: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9
2016-04-07 21:30:56.341 ThaliTest[556:944746] client session: disconnect
2016-04-07 21:30:56.341 ThaliTest[556:944746] client session: stateChange:1->0 E1F1EF18-2DA6-44FB-A6A3-9631A,97782C9:8
2016-04-07 21:30:56.342 ThaliTest[556:944746] client session: no connect callback (server initiated)
,2016-04-07 21:30:59.226 ThaliTest[556:945007] jxcore: connect E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
,2016-04-07 21:30:59.227 ThaliTest[556:945007] client: connect: unreachable E1F1EF18-2DA6-44FB-A6A3-9631A97782C9
,2016-04-07 21:30:59.228 ThaliTest[556:945007] jxcore: connect: fail: Peer unreachable
,INFO testThaliMobileNative: Connect returned an error: Peer unreachable
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-04-07 21:31:02.245 ThaliTest[556:945007] jxcore: connect E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
,2016-04-07 21:31:02.246 ThaliTest[556:945007] client: connect: unreachable E1F1EF18-2DA6-44FB-A6A3-9631A97782C9
,2016-04-07 21:31:02.246 ThaliTest[556:945007] jxcore: connect: fail: Peer unreachable
,INFO testThaliMobileNative: Connect returned an error: Peer unreachable
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-04-07 21:31:03.282 ThaliTest[556:944746] multipeer session: reset timer
,2016-04-07 21:31:03.283 ThaliTest[556:944746] server: disconnecting to refresh session (3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499)
,2016-04-07 21:31:03.283 ThaliTest[556:944746] server: rejecting invitation from 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499 due to previous generation (750E93F7-2E92-4298-982A-D1BFBCF07378:9 != 750E93F7-2E92-4298-982A-D1BFBCF07378:8)
,2016-04-07 21:31:05.259 ThaliTest[556:945007] jxcore: connect E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
,2016-04-07 21:31:05.260 ThaliTest[556:945007] client: connect: unreachable E1F1EF18-2DA6-44FB-A6A3-9631A97782C9
2016-04-07 21:31:05.260 ThaliTest[556:945007] jxcore: connect: fail: Peer unreachable
,INFO testThaliMobileNative: Connect returned an error: Peer unreachable
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-04-07 21:31:06.101 ThaliTest[556:944746] multipeer manager: restart client
,2016-04-07 21:31:06.120 ThaliTest[556:944746] client: found updated peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
,2016-04-07 21:31:06.122 ThaliTest[556:944746] client: found updated peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
,2016-04-07 21:31:08.273 ThaliTest[556:945007] jxcore: connect E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
,2016-04-07 21:31:08.273 ThaliTest[556:945007] client: connect: unreachable E1F1EF18-2DA6-44FB-A6A3-9631A97782C9
,2016-04-07 21:31:08.274 ThaliTest[556:945007] jxcore: connect: fail: Peer unreachable
,INFO testThaliMobileNative: Connect returned an error: Peer unreachable
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-04-07 21:31:11.286 ThaliTest[556:945007] jxcore: connect E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
,2016-04-07 21:31:11.287 ThaliTest[556:945007] client: connect: unreachable E1F1EF18-2DA6-44FB-A6A3-9631A97782C9
,2016-04-07 21:31:11.288 ThaliTest[556:945007] jxcore: connect: fail: Peer unreachable
,INFO testThaliMobileNative: Connect returned an error: Peer unreachable
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-04-07 21:31:14.300 ThaliTest[556:945007] jxcore: connect E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
,2016-04-07 21:31:14.301 ThaliTest[556:945007] client: connect: unreachable E1F1EF18-2DA6-44FB-A6A3-9631A97782C9
2016-04-07 21:31:14.302 ThaliTest[556:945007] jxcore: connect: fail: Peer unreachable
,INFO testThaliMobileNative: Connect returned an error: Peer unreachable
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-04-07 21:31:16.251 ThaliTest[556:944746] multipeer session: reset timer
,2016-04-07 21:31:16.251 ThaliTest[556:944746] server: disconnecting to refresh session (3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499)
,2016-04-07 21:31:16.251 ThaliTest[556:944746] server: rejecting invitation from 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499 due to previous generation (750E93F7-2E92-4298-982A-D1BFBCF07378:9 != 750E93F7-2E92-4298-982A-D1BFBCF07378:8)
,2016-04-07 21:31:17.322 ThaliTest[556:945007] jxcore: connect E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
,2016-04-07 21:31:17.323 ThaliTest[556:945007] client: connect: unreachable E1F1EF18-2DA6-44FB-A6A3-9631A97782C9
2016-04-07 21:31:17.323 ThaliTest[556:945007] jxcore: connect: fail: Peer unreachable
,INFO testThaliMobileNative: Connect returned an error: Peer unreachable
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-04-07 21:31:20.343 ThaliTest[556:945007] jxcore: connect E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
,2016-04-07 21:31:20.344 ThaliTest[556:945007] client: connect: unreachable E1F1EF18-2DA6-44FB-A6A3-9631A97782C9
,2016-04-07 21:31:20.344 ThaliTest[556:945007] jxcore: connect: fail: Peer unreachable
,INFO testThaliMobileNative: Connect returned an error: Peer unreachable
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-04-07 21:31:23.363 ThaliTest[556:945007] jxcore: connect E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
,2016-04-07 21:31:23.364 ThaliTest[556:945007] client: connect: unreachable E1F1EF18-2DA6-44FB-A6A3-9631A97782C9
,2016-04-07 21:31:23.364 ThaliTest[556:945007] jxcore: connect: fail: Peer unreachable
,INFO testThaliMobileNative: Connect returned an error: Peer unreachable
,WARN testThaliMobileNative: Too many connect retries!
,2016-04-07 21:31:26.101 ThaliTest[556:944746] multipeer manager: restart client
,2016-04-07 21:31:26.117 ThaliTest[556:944746] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
,2016-04-07 21:31:26.118 ThaliTest[556:944746] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
,2016-04-07 21:31:29.486 ThaliTest[556:944746] multipeer session: reset timer
,2016-04-07 21:31:29.487 ThaliTest[556:944746] server: disconnecting to refresh session (3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499)
2016-04-07 21:31:29.487 ThaliTest[556:944746] server: rejecting invitation from 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499 due to previ,ous generation (750E93F7-2E92-4298-982A-D1BFBCF07378:9 != 750E93F7-2E92-4298-982A-D1BFBCF07378:8)
,2016-04-07 21:31:30.669 ThaliTest[556:944746] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
,2016-04-07 21:31:30.671 ThaliTest[556:945007] jxcore: connect E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
,2016-04-07 21:31:30.671 ThaliTest[556:945007] client: server will connect
,2016-04-07 21:31:30.672 ThaliTest[556:945007] client session: reverseConnect
,2016-04-07 21:31:30.673 ThaliTest[556:945007] client session: stateChange:0->1 E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
,2016-04-07 21:31:30.869 ThaliTest[556:944746] multipeer session: reset timer
2016-04-07 21:31:30.869 ThaliTest[556:944746] server session: connect
2016-04-07 21:31:30.870 ThaliTest[556:944746] server session: stateChange:0->1 E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:31:30.876 ThaliTest[556:944746] server: accepting invitation E1F1EF18-2DA6-44FB-A6A3-9631A97782C9
,2016-04-07 21:31:31.118 ThaliTest[556:946382] client session: not connected E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
2016-04-07 21:31:31.118 ThaliTest[556:946382] client session: onLinkFailure: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9
2016-04-07 21:31:31.118 ThaliTest[556:946382] client session: disconnect
,2016-04-07 21:31:31.120 ThaliTest[556:946382] client session: stateChange:1->0 E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
2016-04-07 21:31:31.120 ThaliTest[556:946382] client session: no connect callback (server initiated)
,2016-04-07 21:31:34.148 ThaliTest[556:946306] server session: p2p link connected
,2016-04-07 21:31:34.164 ThaliTest[556:944746] server relay: connected (to port: 51862)
,2016-04-07 21:31:34.165 ThaliTest[556:944746] server session: stateChange:1->2 E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:31:34.165 ThaliTest[556:944746] jxcore: connect: success
,2016-04-07 21:31:42.197 ThaliTest[556:944746] multipeer session: reset timer
,2016-04-07 21:31:42.197 ThaliTest[556:944746] server: disconnecting to refresh session (3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499)
,2016-04-07 21:31:42.198 ThaliTest[556:944746] server: rejecting invitation from 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499 due to previous generation (750E93F7-2E92-4298-982A-D1BFBCF07378:9 != 750E93F7-2E92-4298-982A-D1BFBCF07378:8)
,2016-04-07 21:31:46.101 ThaliTest[556:944746] multipeer manager: restart client
,2016-04-07 21:31:46.124 ThaliTest[556:944746] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:31:46.124 ThaliTest[556:944746] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:31:46.125 Th,aliTest[556:944746] client: found updated peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:31:46.127 ThaliTest[556:945007] jxcore: connect E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
2016-04-07 21:31:46.128 ThaliTest[556:945007] client: server already connected
,2016-04-07 21:31:46.128 ThaliTest[556:945007] jxcore: connect: success
,2016-04-07 21:31:55.179 ThaliTest[556:944746] multipeer session: reset timer
,2016-04-07 21:31:55.180 ThaliTest[556:944746] server: disconnecting to refresh session (3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499)
,2016-04-07 21:31:55.180 ThaliTest[556:944746] server: rejecting invitation from 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499 due to previous generation (750E93F7-2E92-4298-982A-D1BFBCF07378:9 != 750E93F7-2E92-4298-982A-D1BFBCF07378:8)
,2016-04-07 21:32:06.101 ThaliTest[556:944746] multipeer manager: restart client
,2016-04-07 21:32:06.126 ThaliTest[556:944746] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:32:06.127 ThaliTest[556:944746] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:32:06.127 ThaliTest[556:944746] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:32:08.225 ThaliTest[556:944746] multipeer session: reset timer
,2016-04-07 21:32:08.225 ThaliTest[556:944746] server: disconnecting to refresh session (3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499)
,2016-04-07 21:32:08.226 ThaliTest[556:944746] server: rejecting invitation from 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499 due to previous generation (750E93F7-2E92-4298-982A-D1BFBCF07378:9 != 750E93F7-2E92-4298-982A-D1BFBCF07378:8)
,2016-04-07 21:32:21.252 ThaliTest[556:944746] multipeer session: reset timer
,2016-04-07 21:32:21.253 ThaliTest[556:944746] server: disconnecting to refresh session (3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499)
,2016-04-07 21:32:21.253 ThaliTest[556:944746] server: rejecting invitation from 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499 due to previous generation (750E93F7-2E92-4298-982A-D1BFBCF07378:9 != 750E93F7-2E92-4298-982A-D1BFBCF07378:8)
,2016-04-07 21:32:26.101 ThaliTest[556:944746] multipeer manager: restart client
,2016-04-07 21:32:26.123 ThaliTest[556:944746] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:32:26.124 ThaliTest[556:944746] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:32:26.124 ThaliTest[556:944746] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:32:34.226 ThaliTest[556:944746] multipeer session: reset timer
,2016-04-07 21:32:34.227 ThaliTest[556:944746] server: disconnecting to refresh session (3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499)
2016-04-07 21:32:34.227 ThaliTest[556:944746] server: rejecting invitation from 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499 due to previ,ous generation (750E93F7-2E92-4298-982A-D1BFBCF07378:9 != 750E93F7-2E92-4298-982A-D1BFBCF07378:8)
,2016-04-07 21:32:46.101 ThaliTest[556:944746] multipeer manager: restart client
,2016-04-07 21:32:46.128 ThaliTest[556:944746] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:32:46.128 ThaliTest[556:944746] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:32:46.129 Th,aliTest[556:944746] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:32:47.485 ThaliTest[556:944746] multipeer session: reset timer
,2016-04-07 21:32:47.486 ThaliTest[556:944746] server: disconnecting to refresh session (3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499)
,2016-04-07 21:32:47.486 ThaliTest[556:944746] server: rejecting invitation from 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499 due to previous generation (750E93F7-2E92-4298-982A-D1BFBCF07378:9 != 750E93F7-2E92-4298-982A-D1BFBCF07378:8)
,2016-04-07 21:33:06.101 ThaliTest[556:944746] multipeer manager: restart client
,2016-04-07 21:33:06.127 ThaliTest[556:944746] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:33:06.128 ThaliTest[556:944746] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:33:06.129 ThaliTest[556:944746] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:33:26.101 ThaliTest[556:944746] multipeer manager: restart client
,2016-04-07 21:33:26.130 ThaliTest[556:944746] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:33:26.131 ThaliTest[556:944746] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
,2016-04-07 21:33:26.133 ThaliTest[556:944746] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:33:46.101 ThaliTest[556:944746] multipeer manager: restart client
,2016-04-07 21:33:46.126 ThaliTest[556:944746] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:33:46.126 ThaliTest[556:944746] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
,2016-04-07 21:33:46.129 ThaliTest[556:944746] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:34:06.100 ThaliTest[556:944746] multipeer manager: restart client
,2016-04-07 21:34:06.129 ThaliTest[556:944746] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
,2016-04-07 21:34:06.132 ThaliTest[556:944746] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:34:06.132 ThaliTest[556:944746] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:34:26.086 ThaliTest[556:944746] multipeer manager: restart client
,2016-04-07 21:34:26.120 ThaliTest[556:944746] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:34:26.121 ThaliTest[556:944746] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
2016-04-07 21:34:26.121 ThaliTest[556:944746] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
,2016-04-07 21:34:46.086 ThaliTest[556:944746] multipeer manager: restart client
,2016-04-07 21:34:46.120 ThaliTest[556:944746] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:34:46.121 ThaliTest[556:944746] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
2016-04-07 21:34:46.121 ThaliTest[556:944746] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
,2016-04-07 21:35:06.086 ThaliTest[556:944746] multipeer manager: restart client
,2016-04-07 21:35:06.116 ThaliTest[556:944746] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:35:06.116 ThaliTest[556:944746] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
,2016-04-07 21:35:06.118 ThaliTest[556:944746] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:35:26.086 ThaliTest[556:944746] multipeer manager: restart client
,2016-04-07 21:35:26.118 ThaliTest[556:944746] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:35:26.118 ThaliTest[556:944746] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
,2016-04-07 21:35:26.120 ThaliTest[556:944746] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:35:46.086 ThaliTest[556:944746] multipeer manager: restart client
,2016-04-07 21:35:46.111 ThaliTest[556:944746] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:35:46.112 ThaliTest[556:944746] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
,2016-04-07 21:35:46.113 ThaliTest[556:944746] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:36:06.086 ThaliTest[556:944746] multipeer manager: restart client
,2016-04-07 21:36:06.117 ThaliTest[556:944746] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:36:06.118 ThaliTest[556:944746] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
2016-04-07 21:36:06.118 ThaliTest[556:944746] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
,2016-04-07 21:36:26.086 ThaliTest[556:944746] multipeer manager: restart client
,2016-04-07 21:36:26.112 ThaliTest[556:944746] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:36:26.112 ThaliTest[556:944746] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
2016-04-07 21:36:26.112 Th,aliTest[556:944746] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
,2016-04-07 21:36:46.086 ThaliTest[556:944746] multipeer manager: restart client
,2016-04-07 21:36:46.117 ThaliTest[556:944746] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:36:46.117 ThaliTest[556:944746] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
,2016-04-07 21:36:46.120 ThaliTest[556:944746] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:37:06.086 ThaliTest[556:944746] multipeer manager: restart client
,2016-04-07 21:37:06.117 ThaliTest[556:944746] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:37:06.118 ThaliTest[556:944746] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
2016-04-07 21:37:06.118 ThaliTest[556:944746] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
,2016-04-07 21:37:26.086 ThaliTest[556:944746] multipeer manager: restart client
,2016-04-07 21:37:26.118 ThaliTest[556:944746] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:37:26.118 ThaliTest[556:944746] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
,2016-04-07 21:37:26.119 ThaliTest[556:944746] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
,2016-04-07 21:37:46.086 ThaliTest[556:944746] multipeer manager: restart client
,2016-04-07 21:37:46.117 ThaliTest[556:944746] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:37:46.118 ThaliTest[556:944746] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:37:46.118 Th,aliTest[556:944746] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:38:06.086 ThaliTest[556:944746] multipeer manager: restart client
,2016-04-07 21:38:06.116 ThaliTest[556:944746] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
2016-04-07 21:38:06.116 ThaliTest[556:944746] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:38:06.118 Th,aliTest[556:944746] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
,2016-04-07 21:38:26.085 ThaliTest[556:944746] multipeer manager: restart client
,2016-04-07 21:38:26.117 ThaliTest[556:944746] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
2016-04-07 21:38:26.117 ThaliTest[556:944746] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:38:26.118 Th,aliTest[556:944746] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
,2016-04-07 21:38:46.086 ThaliTest[556:944746] multipeer manager: restart client
,2016-04-07 21:38:46.116 ThaliTest[556:944746] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
2016-04-07 21:38:46.117 ThaliTest[556:944746] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:38:46.117 ThaliTest[556:944746] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
,2016-04-07 21:39:06.086 ThaliTest[556:944746] multipeer manager: restart client
,2016-04-07 21:39:06.115 ThaliTest[556:944746] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:39:06.115 ThaliTest[556:944746] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:39:06.116 Th,aliTest[556:944746] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:39:26.086 ThaliTest[556:944746] multipeer manager: restart client
,2016-04-07 21:39:26.117 ThaliTest[556:944746] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:39:26.117 ThaliTest[556:944746] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:39:26.118 ThaliTest[556:944746] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:39:46.086 ThaliTest[556:944746] multipeer manager: restart client
,2016-04-07 21:39:46.118 ThaliTest[556:944746] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:39:46.118 ThaliTest[556:944746] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
2016-04-07 21:39:46.119 Th,aliTest[556:944746] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
,2016-04-07 21:40:06.086 ThaliTest[556:944746] multipeer manager: restart client
,2016-04-07 21:40:06.115 ThaliTest[556:944746] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:40:06.115 ThaliTest[556:944746] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:40:06.117 ThaliTest[556:944746] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:40:26.085 ThaliTest[556:944746] multipeer manager: restart client
,2016-04-07 21:40:26.115 ThaliTest[556:944746] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:40:26.116 ThaliTest[556:944746] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:40:26.116 Th,aliTest[556:944746] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:40:46.086 ThaliTest[556:944746] multipeer manager: restart client
,2016-04-07 21:40:46.116 ThaliTest[556:944746] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:40:46.117 ThaliTest[556:944746] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
,2016-04-07 21:40:46.118 ThaliTest[556:944746] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:41:06.086 ThaliTest[556:944746] multipeer manager: restart client
,2016-04-07 21:41:06.117 ThaliTest[556:944746] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:41:06.118 ThaliTest[556:944746] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
2016-04-07 21:41:06.118 Th,aliTest[556:944746] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
,2016-04-07 21:41:26.086 ThaliTest[556:944746] multipeer manager: restart client
,2016-04-07 21:41:26.115 ThaliTest[556:944746] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
,2016-04-07 21:41:26.116 ThaliTest[556:944746] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
,2016-04-07 21:41:26.117 ThaliTest[556:944746] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:41:46.086 ThaliTest[556:944746] multipeer manager: restart client
,2016-04-07 21:41:46.115 ThaliTest[556:944746] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:41:46.116 ThaliTest[556:944746] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
,2016-04-07 21:41:46.118 ThaliTest[556:944746] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:42:06.086 ThaliTest[556:944746] multipeer manager: restart client
,2016-04-07 21:42:06.115 ThaliTest[556:944746] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:42:06.115 ThaliTest[556:944746] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:42:06.115 Th,aliTest[556:944746] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:42:26.086 ThaliTest[556:944746] multipeer manager: restart client
,2016-04-07 21:42:26.116 ThaliTest[556:944746] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:42:26.117 ThaliTest[556:944746] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:42:26.118 ThaliTest[556:944746] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:42:46.086 ThaliTest[556:944746] multipeer manager: restart client
,2016-04-07 21:42:46.117 ThaliTest[556:944746] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:42:46.118 ThaliTest[556:944746] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
,2016-04-07 21:42:46.120 ThaliTest[556:944746] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:43:06.086 ThaliTest[556:944746] multipeer manager: restart client
,2016-04-07 21:43:06.117 ThaliTest[556:944746] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
2016-04-07 21:43:06.118 ThaliTest[556:944746] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:43:06.118 ThaliTest[556:944746] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
,2016-04-07 21:43:26.086 ThaliTest[556:944746] multipeer manager: restart client
,2016-04-07 21:43:26.114 ThaliTest[556:944746] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
,2016-04-07 21:43:26.116 ThaliTest[556:944746] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:43:26.117 ThaliTest[556:944746] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:43:46.086 ThaliTest[556:944746] multipeer manager: restart client
,2016-04-07 21:43:46.117 ThaliTest[556:944746] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
2016-04-07 21:43:46.118 ThaliTest[556:944746] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:43:46.118 Th,aliTest[556:944746] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
,2016-04-07 21:44:06.086 ThaliTest[556:944746] multipeer manager: restart client
,2016-04-07 21:44:06.116 ThaliTest[556:944746] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:44:06.116 ThaliTest[556:944746] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:44:06.118 ThaliTest[556:944746] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:44:26.086 ThaliTest[556:944746] multipeer manager: restart client
,2016-04-07 21:44:26.115 ThaliTest[556:944746] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
,2016-04-07 21:44:26.116 ThaliTest[556:944746] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
,2016-04-07 21:44:26.118 ThaliTest[556:944746] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:44:46.086 ThaliTest[556:944746] multipeer manager: restart client
,2016-04-07 21:44:46.116 ThaliTest[556:944746] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
2016-04-07 21:44:46.116 ThaliTest[556:944746] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:44:46.116 ThaliTest[556:944746] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9

```
