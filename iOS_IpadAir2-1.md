#### Test 625481245382a4d_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/625481245382a4d/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/648B2B53-9B46-410D-A0A6-839F141E8634/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/648B2B53-9B46-410D-A0A6-839F141E8634/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/625481245382a4d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/625481245382a4d/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/427199A5-49B6-478C-BEED-C15E743ABD34/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53223"
,(lldb)     command script import "/tmp/648B2B53-9B46-410D-A0A6-839F141E8634/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-20 12:39:04.033 ThaliTest[1864:3097744] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/BC28FC1F-BBAE-4AFB-BE90-985122564D3E/Library/Cookies/Cookies.binarycookies
,2016-03-20 12:39:04.413 ThaliTest[1864:3097744] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-20 12:39:04.414 ThaliTest[1864:3097744] Multi-tasking -> Device: YES, App: YES
,2016-03-20 12:39:04.433 ThaliTest[1864:3097744] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-20 12:39:06.371 ThaliTest[1864:3097744] Using UIWebView
,2016-03-20 12:39:06.379 ThaliTest[1864:3097744] [CDVTimer][handleopenurl] 0.479996ms
,2016-03-20 12:39:06.386 ThaliTest[1864:3097744] [CDVTimer][intentandnavigationfilter] 7.142007ms
,2016-03-20 12:39:06.388 ThaliTest[1864:3097744] [CDVTimer][gesturehandler] 0.374973ms
,2016-03-20 12:39:06.388 ThaliTest[1864:3097744] [CDVTimer][TotalPluginStartup] 9.961009ms
,2016-03-20 12:39:13.313 ThaliTest[1864:3097744] Resetting plugins due to page load.
,2016-03-20 12:39:17.201 ThaliTest[1864:3097744] Finished load of: file:///var/mobile/Containers/Bundle/Application/427199A5-49B6-478C-BEED-C15E743ABD34/ThaliTest.app/www/index.html
,2016-03-20 12:39:17.419 ThaliTest[1864:3097744] JXcore Cordova plugin initializing
,2016-03-20 12:39:17.421 ThaliTest[1864:3097999] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-20 12:39:23.885 ThaliTest[1864:3097999] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-20 12:39:23.886 ThaliTest[1864:3097999] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-20 12:39:23.886 ThaliTest[1864:3097999] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-20 12:39:23.887 ThaliTest[1864:3097999] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-IpadAir2-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/427199A5-49B6-478C-BEED-C15E743ABD34/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/427199A5-49B6-478C-BEED-C15E743ABD34/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/427199A5-49B6-478C-BEED-C15E743ABD34/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/427199A5-49B6-478C-BEED-C15E743ABD34/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/427199A5-49B6-478C-BEED-C15E743ABD34/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/427199A5-49B6-478C-BEED-C15E743ABD34/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/427199A5-49B6-478C-BEED-C15E743ABD34/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/427199A5-49B6-478C-BEED-C15E743ABD34/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/427199A5-49B6-478C-BEED-C15E743ABD34/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/427199A5-49B6-478C-BEED-C15E743ABD34/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/427199A5-49B6-478C-BEED-C15E743ABD34/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/427199A5-49B6-478C-BEED-C15E743ABD34/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/427199A5-49B6-478C-BEED-C15E743ABD34/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/427199A5-49B6-478C-BEED-C15E743ABD34/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/427199A5-49B6-478C-BEED-C15E743ABD34/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/427199A5-49B6-478C-BEED-C15E743ABD34/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/427199A5-49B6-478C-BEED-C15E743ABD34/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/427199A5-49B6-478C-BEED-C15E743ABD34/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/427199A5-49B6-478C-BEED-C15E743ABD34/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/427199A5-49B6-478C-BEED-C15E743ABD34/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-20 12:39:29.102 ThaliTest[1864:3097744] THREAD WARNING: ['JXcore'] took '4939.709717' ms. Plugin should use a background thread.
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49216
,ok 1 Should throw
,# setup
,# 2. emits incomingConnectionState
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49218
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
,DEBUG createNativeListener: listening 49222
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
,DEBUG createNativeListener: listening 49226
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
,DEBUG createNativeListener: listening 49231
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
,DEBUG createNativeListener: listening 49235
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
,DEBUG createNativeListener: listening 49239
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
,DEBUG createNativeListener: listening 49243
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
,DEBUG createNativeListener: listening 49247
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
,DEBUG createNativeListener: listening 49299
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
,DEBUG createNativeListener: listening 49303
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
,DEBUG createNativeListener: listening 49315
,2016-03-20 12:43:14.209 ThaliTest[1864:3097999] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-20 12:43:14.212 ThaliTest[1864:3097999] jxcore: stopListeningForAdvertisements: success
,ok 82 error should be null
,ok 83 error should be null
,2016-03-20 12:43:14.218 ThaliTest[1864:3097999] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-20 12:43:14.220 ThaliTest[1864:3097999] jxcore: stopListeningForAdvertisements: success
,ok 84 error should be null
,ok 85 error should be null
,# setup
,2016-03-20 12:43:14.328 ThaliTest[1864:3097999] jxcore: stopAdvertisingAndListening
2016-03-20 12:43:14.329 ThaliTest[1864:3097999] THEMultipeerManager stopping peer
,2016-03-20 12:43:14.329 ThaliTest[1864:3097999] jxcore: stopAdvertisingAndListening: success
,2016-03-20 12:43:14.331 ThaliTest[1864:3097999] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-20 12:43:14.333 ThaliTest[1864:3097999] jxcore: stopListeningForAdvertisements: success
,ok 86 error should be null
,ok 87 error should be null
,# 24. should be able to call #startListeningForAdvertisements many times
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49317
,2016-03-20 12:43:14.683 ThaliTest[1864:3097999] jxcore: startListeningForAdvertisements
,2016-03-20 12:43:14.684 ThaliTest[1864:3097999] multipeer manager: start client restart timer: 0x14e8bad0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-20 12:43:14.687 ThaliTest[1864:3097999] jxcore: startListeningForAdvertisements: success
,ok 88 error should be null
,ok 89 error should be null
,2016-03-20 12:43:14.713 ThaliTest[1864:3097999] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-20 12:43:14.716 ThaliTest[1864:3097999] jxcore: startListeningForAdvertisements: success
,ok 90 error should be null
,ok 91 error should be null
,# setup
,2016-03-20 12:43:15.031 ThaliTest[1864:3097999] jxcore: stopAdvertisingAndListening
2016-03-20 12:43:15.032 ThaliTest[1864:3097999] THEMultipeerManager stopping peer
,2016-03-20 12:43:15.032 ThaliTest[1864:3097999] jxcore: stopAdvertisingAndListening: success
,2016-03-20 12:43:15.033 ThaliTest[1864:3097999] jxcore: stopListeningForAdvertisements
,2016-03-20 12:43:15.034 ThaliTest[1864:3097999] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-20 12:43:15.037 ThaliTest[1864:3097999] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 92 error should be null
,ok 93 error should be null
,# 25. should be able to call #startUpdateAdvertisingAndListening many times
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49319
,2016-03-20 12:43:15.679 ThaliTest[1864:3097999] jxcore: startUpdateAdvertisingAndListening
,2016-03-20 12:43:15.680 ThaliTest[1864:3097999] server: starting F82F884A-9394-418C-8996-A62FEDB8DD77:1
,2016-03-20 12:43:15.682 ThaliTest[1864:3097999] multipeer manager: start client restart timer: 0x14e8bad0
,2016-03-20 12:43:15.684 ThaliTest[1864:3097999] THEMultipeerManager initialized peer F82F884A-9394-418C-8996-A62FEDB8DD77:1
2016-03-20 12:43:15.685 ThaliTest[1864:3097999] jxcore: startUpdateAdvertisingAndListening: success
,ok 94 error should be null
,ok 95 error should be null
,2016-03-20 12:43:15.717 ThaliTest[1864:3097999] jxcore: startUpdateAdvertisingAndListening
,2016-03-20 12:43:15.718 ThaliTest[1864:3097999] THEMultipeerManager stopping peer
,2016-03-20 12:43:15.721 ThaliTest[1864:3097999] multipeer manager: stop client timer
,2016-03-20 12:43:15.724 ThaliTest[1864:3097999] server: starting F82F884A-9394-418C-8996-A62FEDB8DD77:2
,2016-03-20 12:43:15.725 ThaliTest[1864:3097999] multipeer manager: start client restart timer: 0x14e8bad0
,2016-03-20 12:43:15.727 ThaliTest[1864:3097999] THEMultipeerManager initialized peer F82F884A-9394-418C-8996-A62FEDB8DD77:2
,2016-03-20 12:43:15.732 ThaliTest[1864:3097999] jxcore: startUpdateAdvertisingAndListening: success
,ok 96 error should be null
,ok 97 error should be null
,# setup
,2016-03-20 12:43:16.514 ThaliTest[1864:3097999] jxcore: stopAdvertisingAndListening
2016-03-20 12:43:16.514 ThaliTest[1864:3097999] THEMultipeerManager stopping peer
,2016-03-20 12:43:16.515 ThaliTest[1864:3097999] multipeer manager: stop client timer
2016-03-20 12:43:16.515 ThaliTest[1864:3097999] jxcore: stopAdvertisingAndListening: success
,2016-03-20 12:43:16.516 ThaliTest[1864:3097999] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-20 12:43:16.520 ThaliTest[1864:3097999] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 98 error should be null
,ok 99 error should be null
,# 26. should be able to call #stopAdvertisingAndListening many times
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49324
,2016-03-20 12:43:17.149 ThaliTest[1864:3097999] jxcore: stopAdvertisingAndListening
,2016-03-20 12:43:17.149 ThaliTest[1864:3097999] THEMultipeerManager stopping peer
,2016-03-20 12:43:17.150 ThaliTest[1864:3097999] jxcore: stopAdvertisingAndListening: success
,ok 100 error should be null
,ok 101 error should be null
,2016-03-20 12:43:17.156 ThaliTest[1864:3097999] jxcore: stopAdvertisingAndListening
,2016-03-20 12:43:17.157 ThaliTest[1864:3097999] THEMultipeerManager stopping peer
,2016-03-20 12:43:17.157 ThaliTest[1864:3097999] jxcore: stopAdvertisingAndListening: success
,ok 102 error should be null
,ok 103 error should be null
,# setup
,2016-03-20 12:43:17.881 ThaliTest[1864:3097999] jxcore: stopAdvertisingAndListening
2016-03-20 12:43:17.881 ThaliTest[1864:3097999] THEMultipeerManager stopping peer
,2016-03-20 12:43:17.882 ThaliTest[1864:3097999] jxcore: stopAdvertisingAndListening: success
,2016-03-20 12:43:17.883 ThaliTest[1864:3097999] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-20 12:43:17.885 ThaliTest[1864:3097999] jxcore: stopListeningForAdvertisements: success
,ok 104 error should be null
,ok 105 error should be null
,# 27. #start should fail if called twice in a row
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49326
,ok 106 first call should succeed
,ok 107 first call should succeed
,ok 108 specific error should be returned
,# setup
,2016-03-20 12:43:19.304 ThaliTest[1864:3097999] jxcore: stopAdvertisingAndListening
2016-03-20 12:43:19.304 ThaliTest[1864:3097999] THEMultipeerManager stopping peer
,2016-03-20 12:43:19.305 ThaliTest[1864:3097999] jxcore: stopAdvertisingAndListening: success
,2016-03-20 12:43:19.306 ThaliTest[1864:3097999] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-20 12:43:19.308 ThaliTest[1864:3097999] jxcore: stopListeningForAdvertisements: success
,ok 109 error should be null
,ok 110 error should be null
,# 28. does not emit duplicate discoveryAdvertisingStateUpdate
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49328
,2016-03-20 12:43:19.753 ThaliTest[1864:3097999] jxcore: startListeningForAdvertisements
,2016-03-20 12:43:19.753 ThaliTest[1864:3097999] multipeer manager: start client restart timer: 0x14e8bad0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-20 12:43:19.756 ThaliTest[1864:3097999] jxcore: startListeningForAdvertisements: success
,2016-03-20 12:43:19.774 ThaliTest[1864:3097999] jxcore: startUpdateAdvertisingAndListening
,2016-03-20 12:43:19.775 ThaliTest[1864:3097999] server: starting F82F884A-9394-418C-8996-A62FEDB8DD77:3
,2016-03-20 12:43:19.776 ThaliTest[1864:3097999] THEMultipeerManager initialized peer F82F884A-9394-418C-8996-A62FEDB8DD77:3
2016-03-20 12:43:19.776 ThaliTest[1864:3097999] jxcore: startUpdateAdvertisingAndListening: success
,ok 111 called only once
,ok 112 discovery state matches
,ok 113 advertising state matches
,# setup
,2016-03-20 12:43:20.106 ThaliTest[1864:3097999] jxcore: stopAdvertisingAndListening
,2016-03-20 12:43:20.106 ThaliTest[1864:3097999] THEMultipeerManager stopping peer
,2016-03-20 12:43:20.107 ThaliTest[1864:3097999] jxcore: stopAdvertisingAndListening: success
,2016-03-20 12:43:20.109 ThaliTest[1864:3097999] jxcore: stopListeningForAdvertisements
,2016-03-20 12:43:20.110 ThaliTest[1864:3097999] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-20 12:43:20.113 ThaliTest[1864:3097999] jxcore: stopListeningForAdvertisements: success
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
,2016-03-20 12:43:25.921 ThaliTest[1864:3097999] jxcore: startListeningForAdvertisements
,2016-03-20 12:43:25.922 ThaliTest[1864:3097999] multipeer manager: start client restart timer: 0x14e8bad0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-20 12:43:25.925 ThaliTest[1864:3097999] jxcore: startListeningForAdvertisements: success
ok 129 Can call startListeningForAdvertisements without error
,2016-03-20 12:43:25.928 ThaliTest[1864:3097999] jxcore: stopListeningForAdvertisements
,2016-03-20 12:43:25.929 ThaliTest[1864:3097999] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-20 12:43:25.934 ThaliTest[1864:3097999] jxcore: stopListeningForAdvertisements: success
,ok 130 Can call stopListeningForAdvertisements without error
,# setup
,2016-03-20 12:43:26.140 ThaliTest[1864:3097999] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-20 12:43:26.143 ThaliTest[1864:3097999] jxcore: stopListeningForAdvertisements: success
,ok 131 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-20 12:43:26.146 ThaliTest[1864:3097999] jxcore: stopAdvertisingAndListening
,2016-03-20 12:43:26.146 ThaliTest[1864:3097999] THEMultipeerManager stopping peer
,2016-03-20 12:43:26.147 ThaliTest[1864:3097999] jxcore: stopAdvertisingAndListening: success
,ok 132 Should be able to call stopAdvertisingAndListening in teardown
,# 33. Calling startListeningForAdvertisements twice is NOT an error
,# teardown
,2016-03-20 12:43:26.592 ThaliTest[1864:3097999] jxcore: startListeningForAdvertisements
,2016-03-20 12:43:26.593 ThaliTest[1864:3097999] multipeer manager: start client restart timer: 0x14e8bad0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-20 12:43:26.596 ThaliTest[1864:3097999] jxcore: startListeningForAdvertisements: success
,ok 133 Can call startListeningForAdvertisements without error
,2016-03-20 12:43:26.600 ThaliTest[1864:3097999] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-20 12:43:26.603 ThaliTest[1864:3097999] jxcore: startListeningForAdvertisements: success
,ok 134 Can call startListeningForAdvertisements twice without error
,# setup
,2016-03-20 12:43:26.834 ThaliTest[1864:3097999] jxcore: stopListeningForAdvertisements
,2016-03-20 12:43:26.835 ThaliTest[1864:3097999] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-20 12:43:26.838 ThaliTest[1864:3097999] jxcore: stopListeningForAdvertisements: success
,ok 135 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-20 12:43:26.841 ThaliTest[1864:3097999] jxcore: stopAdvertisingAndListening
,2016-03-20 12:43:26.842 ThaliTest[1864:3097999] THEMultipeerManager stopping peer
,2016-03-20 12:43:26.842 ThaliTest[1864:3097999] jxcore: stopAdvertisingAndListening: success
,ok 136 Should be able to call stopAdvertisingAndListening in teardown
,# 34. Can call start/stopUpdateAdvertisingAndListening
,# teardown
,2016-03-20 12:43:29.747 ThaliTest[1864:3097999] jxcore: startUpdateAdvertisingAndListening
,2016-03-20 12:43:29.748 ThaliTest[1864:3097999] server: starting F82F884A-9394-418C-8996-A62FEDB8DD77:4
,2016-03-20 12:43:29.749 ThaliTest[1864:3097999] multipeer manager: start client restart timer: 0x14e8bad0
2016-03-20 12:43:29.750 ThaliTest[1864:3097999] THEMultipeerManager initialized peer F82F884A-9394-418C-8996-A62FEDB8DD77:4
2016-03-20 12:43:29.750 ThaliTest[1864:3097999] jxcore: startUpdateAdvertisingAndListening: success
,ok 137 Can call startUpdateAdvertisingAndListening without error
2016-03-20 12:43:29.754 ThaliTest[1864:3097999] jxcore: stopAdvertisingAndListening
2016-03-20 12:43:29.754 ThaliTest[1864:3097999] THEMultipeerManager stopping peer
2016-03-20 12:43:29.754 ThaliTest[1864:3097999] multipeer manager: stop client timer
2016-03-20 12:43:29.755 ThaliTest[1864:3097999] jxcore: stopAdvertisingAndListening: success
ok 138 Can call stopAdvertisingAndListening without error
,# setup
,2016-03-20 12:43:29.947 ThaliTest[1864:3097999] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-20 12:43:29.950 ThaliTest[1864:3097999] jxcore: stopListeningForAdvertisements: success
,ok 139 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-20 12:43:29.952 ThaliTest[1864:3097999] jxcore: stopAdvertisingAndListening
,2016-03-20 12:43:29.953 ThaliTest[1864:3097999] THEMultipeerManager stopping peer
,2016-03-20 12:43:29.954 ThaliTest[1864:3097999] jxcore: stopAdvertisingAndListening: success
,ok 140 Should be able to call stopAdvertisingAndListening in teardown
,# 35. Calling startUpdateAdvertisingAndListening twice is NOT an error
,# teardown
,2016-03-20 12:43:30.458 ThaliTest[1864:3097999] jxcore: startUpdateAdvertisingAndListening
,2016-03-20 12:43:30.459 ThaliTest[1864:3097999] server: starting F82F884A-9394-418C-8996-A62FEDB8DD77:5
,2016-03-20 12:43:30.461 ThaliTest[1864:3097999] multipeer manager: start client restart timer: 0x14e8bad0
2016-03-20 12:43:30.461 ThaliTest[1864:3097999] THEMultipeerManager initialized peer F82F884A-9394-418C-8996-A62FEDB8DD77:5
2016-03-20 12:43:30.461 ,ThaliTest[1864:3097999] jxcore: startUpdateAdvertisingAndListening: success
ok 141 Can call startUpdateAdvertisingAndListening without error
,2016-03-20 12:43:30.465 ThaliTest[1864:3097999] jxcore: startUpdateAdvertisingAndListening
2016-03-20 12:43:30.465 ThaliTest[1864:3097999] THEMultipeerManager stopping peer
2016-03-20 12:43:30.466 ThaliTest[1864:3097999] multipeer manager: stop client ti,mer
2016-03-20 12:43:30.466 ThaliTest[1864:3097999] server: starting F82F884A-9394-418C-8996-A62FEDB8DD77:6
2016-03-20 12:43:30.467 ThaliTest[1864:3097999] multipeer manager: start client restart timer: 0x14e8bad0
2016-03-20 12:43:30.467 ThaliTest[1864:,3097999] THEMultipeerManager initialized peer F82F884A-9394-418C-8996-A62FEDB8DD77:6
2016-03-20 12:43:30.468 ThaliTest[1864:3097999] jxcore: startUpdateAdvertisingAndListening: success
ok 142 Can call startUpdateAdvertisingAndListening twice without error
,# setup
,2016-03-20 12:43:30.648 ThaliTest[1864:3097999] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-20 12:43:30.650 ThaliTest[1864:3097999] jxcore: stopListeningForAdvertisements: success
,ok 143 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-20 12:43:30.654 ThaliTest[1864:3097999] jxcore: stopAdvertisingAndListening
,2016-03-20 12:43:30.654 ThaliTest[1864:3097999] THEMultipeerManager stopping peer
,2016-03-20 12:43:30.655 ThaliTest[1864:3097999] multipeer manager: stop client timer
2016-03-20 12:43:30.655 ThaliTest[1864:3097999] jxcore: stopAdvertisingAndListening: success
,ok 144 Should be able to call stopAdvertisingAndListening in teardown
,# 36. peerAvailabilityChange is called
,# teardown
,2016-03-20 12:43:31.617 ThaliTest[1864:3097999] jxcore: startUpdateAdvertisingAndListening
2016-03-20 12:43:31.617 ThaliTest[1864:3097999] server: starting F82F884A-9394-418C-8996-A62FEDB8DD77:7
,2016-03-20 12:43:31.619 ThaliTest[1864:3097999] multipeer manager: start client restart timer: 0x14e8bad0
2016-03-20 12:43:31.619 ThaliTest[1864:3097999] THEMultipeerManager initialized peer F82F884A-9394-418C-8996-A62FEDB8DD77:7
2016-03-20 12:43:31.619 ,ThaliTest[1864:3097999] jxcore: startUpdateAdvertisingAndListening: success
ok 145 Can call startUpdateAdvertisingAndListeningwithout error
,2016-03-20 12:43:31.622 ThaliTest[1864:3097999] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
,2016-03-20 12:43:31.624 ThaliTest[1864:3097999] jxcore: startListeningForAdvertisements: success
ok 146 Can call startListeningForAdvertisements without error
,2016-03-20 12:43:33.655 ThaliTest[1864:3097744] client: found new peer: 5A342616-0ECA-48AE-829A-448F633DC8C8:7
,ok 147 peers must be an array
,ok 148 peers must not be zero-length
,ok 149 peer must have peerIdentifier
,ok 150 peerIdentifier must be a string
,ok 151 peer must have peerAvailable
,ok 152 peer must have pleaseConnect
,# setup
,2016-03-20 12:43:33.960 ThaliTest[1864:3097999] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-20 12:43:33.963 ThaliTest[1864:3097999] jxcore: stopListeningForAdvertisements: success
,ok 153 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-20 12:43:33.965 ThaliTest[1864:3097999] jxcore: stopAdvertisingAndListening
,2016-03-20 12:43:33.966 ThaliTest[1864:3097999] THEMultipeerManager stopping peer
,2016-03-20 12:43:33.967 ThaliTest[1864:3097999] multipeer manager: stop client timer
2016-03-20 12:43:33.968 ThaliTest[1864:3097999] jxcore: stopAdvertisingAndListening: success
,ok 154 Should be able to call stopAdvertisingAndListening in teardown
,# 37. Can connect to a remote peer
,# teardown
,2016-03-20 12:43:34.744 ThaliTest[1864:3097999] jxcore: startUpdateAdvertisingAndListening
2016-03-20 12:43:34.744 ThaliTest[1864:3097999] server: starting F82F884A-9394-418C-8996-A62FEDB8DD77:8
,2016-03-20 12:43:34.746 ThaliTest[1864:3097999] multipeer manager: start client restart timer: 0x14e8bad0
2016-03-20 12:43:34.746 ThaliTest[1864:3097999] THEMultipeerManager initialized peer F82F884A-9394-418C-8996-A62FEDB8DD77:8
2016-03-20 12:43:34.747 ,ThaliTest[1864:3097999] jxcore: startUpdateAdvertisingAndListening: success
,ok 155 Can call startUpdateAdvertisingAndListening without error
2016-03-20 12:43:34.750 ThaliTest[1864:3097999] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-20 12:43:34.751 ThaliTest[1864:3097999] jxcore: startListeningForAdvertisements: success
,ok 156 Can call startListeningForAdvertisements without error
,2016-03-20 12:43:35.093 ThaliTest[1864:3097744] client: found new peer: 5A342616-0ECA-48AE-829A-448F633DC8C8:7
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"5A342616-0ECA-48AE-829A-448F633DC8C8:7","pleaseConnect":0}]
,2016-03-20 12:43:35.098 ThaliTest[1864:3097999] jxcore: connect 5A342616-0ECA-48AE-829A-448F633DC8C8:7
,2016-03-20 12:43:35.099 ThaliTest[1864:3097999] client session: connect
2016-03-20 12:43:35.099 ThaliTest[1864:3097999] client session: stateChange:0->1 5A342616-0ECA-48AE-829A-448F633DC8C8:7
,2016-03-20 12:43:37.149 ThaliTest[1864:3097744] multipeer session: reset timer
,2016-03-20 12:43:37.150 ThaliTest[1864:3097744] server: rejecting invitation for lexical ordering 5A342616-0ECA-48AE-829A-448F633DC8C8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"5A342616-0ECA-48AE-829A-448F633DC8C8:8","pleaseConnect":1}]
,2016-03-20 12:43:37.213 ThaliTest[1864:3098500] client session: not connected 5A342616-0ECA-48AE-829A-448F633DC8C8:7
,2016-03-20 12:43:37.213 ThaliTest[1864:3098500] client session: onLinkFailure: 5A342616-0ECA-48AE-829A-448F633DC8C8
2016-03-20 12:43:37.214 ThaliTest[1864:3098500] client session: disconnect
2016-03-20 12:43:37.214 ThaliTest[1864:3098500] client session:, stateChange:1->0 5A342616-0ECA-48AE-829A-448F633DC8C8:7
,2016-03-20 12:43:37.215 ThaliTest[1864:3098500] client session: fireConnectCallback: 5A342616-0ECA-48AE-829A-448F633DC8C8
,2016-03-20 12:43:37.216 ThaliTest[1864:3098500] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-20 12:43:40.224 ThaliTest[1864:3097999] jxcore: connect 5A342616-0ECA-48AE-829A-448F633DC8C8:7
,2016-03-20 12:43:40.225 ThaliTest[1864:3097999] client session: connect
2016-03-20 12:43:40.225 ThaliTest[1864:3097999] client session: stateChange:0->1 5A342616-0ECA-48AE-829A-448F633DC8C8:7
,2016-03-20 12:43:40.677 ThaliTest[1864:3098536] client session: not connected 5A342616-0ECA-48AE-829A-448F633DC8C8:7
2016-03-20 12:43:40.677 ThaliTest[1864:3098536] client session: onLinkFailure: 5A342616-0ECA-48AE-829A-448F633DC8C8
2016-03-20 12:43:40.6,78 ThaliTest[1864:3098536] client session: disconnect
,2016-03-20 12:43:40.678 ThaliTest[1864:3098536] client session: stateChange:1->0 5A342616-0ECA-48AE-829A-448F633DC8C8:7
,2016-03-20 12:43:40.679 ThaliTest[1864:3098536] client session: fireConnectCallback: 5A342616-0ECA-48AE-829A-448F633DC8C8
2016-03-20 12:43:40.680 ThaliTest[1864:3098536] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-20 12:43:43.686 ThaliTest[1864:3097999] jxcore: connect 5A342616-0ECA-48AE-829A-448F633DC8C8:7
,2016-03-20 12:43:43.687 ThaliTest[1864:3097999] client session: connect
,2016-03-20 12:43:43.688 ThaliTest[1864:3097999] client session: stateChange:0->1 5A342616-0ECA-48AE-829A-448F633DC8C8:7
,2016-03-20 12:43:43.815 ThaliTest[1864:3098538] client session: not connected 5A342616-0ECA-48AE-829A-448F633DC8C8:7
2016-03-20 12:43:43.816 ThaliTest[1864:3098538] client session: onLinkFailure: 5A342616-0ECA-48AE-829A-448F633DC8C8
2016-03-20 12:43:43.8,16 ThaliTest[1864:3098538] client session: disconnect
2016-03-20 12:43:43.816 ThaliTest[1864:3098538] client session: stateChange:1->0 5A342616-0ECA-48AE-829A-448F633DC8C8:7
,2016-03-20 12:43:43.818 ThaliTest[1864:3098538] client session: fireConnectCallback: 5A342616-0ECA-48AE-829A-448F633DC8C8
2016-03-20 12:43:43.818 ThaliTest[1864:3098538] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-20 12:43:46.830 ThaliTest[1864:3097999] jxcore: connect 5A342616-0ECA-48AE-829A-448F633DC8C8:7
,2016-03-20 12:43:46.831 ThaliTest[1864:3097999] client session: connect
,2016-03-20 12:43:46.831 ThaliTest[1864:3097999] client session: stateChange:0->1 5A342616-0ECA-48AE-829A-448F633DC8C8:7
,2016-03-20 12:43:46.998 ThaliTest[1864:3098538] client session: not connected 5A342616-0ECA-48AE-829A-448F633DC8C8:7
2016-03-20 12:43:46.998 ThaliTest[1864:3098538] client session: onLinkFailure: 5A342616-0ECA-48AE-829A-448F633DC8C8
2016-03-20 12:43:46.999 ThaliTest[1864:3098538] client session: disconnect
,2016-03-20 12:43:47.000 ThaliTest[1864:3098538] client session: stateChange:1->0 5A342616-0ECA-48AE-829A-448F633DC8C8:7
,2016-03-20 12:43:47.001 ThaliTest[1864:3098538] client session: fireConnectCallback: 5A342616-0ECA-48AE-829A-448F633DC8C8
,2016-03-20 12:43:47.001 ThaliTest[1864:3098538] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-20 12:43:50.007 ThaliTest[1864:3097999] jxcore: connect 5A342616-0ECA-48AE-829A-448F633DC8C8:7
,2016-03-20 12:43:50.008 ThaliTest[1864:3097999] client session: connect
2016-03-20 12:43:50.008 ThaliTest[1864:3097999] client session: stateChange:0->1 5A342616-0ECA-48AE-829A-448F633DC8C8:7
,2016-03-20 12:43:50.575 ThaliTest[1864:3097744] multipeer session: reset timer
,2016-03-20 12:43:50.575 ThaliTest[1864:3097744] server: disconnecting to refresh session (5A342616-0ECA-48AE-829A-448F633DC8C8)
,2016-03-20 12:43:50.576 ThaliTest[1864:3097744] server: rejecting invitation for lexical ordering 5A342616-0ECA-48AE-829A-448F633DC8C8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"5A342616-0ECA-48AE-829A-448F633DC8C8:8","pleaseConnect":1}]
,2016-03-20 12:43:50.583 ThaliTest[1864:3098581] client session: not connected 5A342616-0ECA-48AE-829A-448F633DC8C8:7
2016-03-20 12:43:50.584 ThaliTest[1864:3098581] client session: onLinkFailure: 5A342616-0ECA-48AE-829A-448F633DC8C8
2016-03-20 12:43:50.5,84 ThaliTest[1864:3098581] client session: disconnect
2016-03-20 12:43:50.584 ThaliTest[1864:3098581] client session: stateChange:1->0 5A342616-0ECA-48AE-829A-448F633DC8C8:7
,2016-03-20 12:43:50.585 ThaliTest[1864:3098581] client session: fireConnectCallback: 5A342616-0ECA-48AE-829A-448F633DC8C8
2016-03-20 12:43:50.586 ThaliTest[1864:3098581] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-20 12:43:53.600 ThaliTest[1864:3097999] jxcore: connect 5A342616-0ECA-48AE-829A-448F633DC8C8:7
,2016-03-20 12:43:53.601 ThaliTest[1864:3097999] client session: connect
,2016-03-20 12:43:53.601 ThaliTest[1864:3097999] client session: stateChange:0->1 5A342616-0ECA-48AE-829A-448F633DC8C8:7
,2016-03-20 12:43:53.717 ThaliTest[1864:3098581] client session: not connected 5A342616-0ECA-48AE-829A-448F633DC8C8:7
,2016-03-20 12:43:53.718 ThaliTest[1864:3098581] client session: onLinkFailure: 5A342616-0ECA-48AE-829A-448F633DC8C8
2016-03-20 12:43:53.719 ThaliTest[1864:3098581] client session: disconnect
2016-03-20 12:43:53.719 ThaliTest[1864:3098581] client session: stateChange:1->0 5A342616-0ECA-48AE-829A-448F633DC8C8:7
,2016-03-20 12:43:53.720 ThaliTest[1864:3098581] client session: fireConnectCallback: 5A342616-0ECA-48AE-829A-448F633DC8C8
2016-03-20 12:43:53.720 ThaliTest[1864:3098581] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-20 12:43:54.748 ThaliTest[1864:3097744] multipeer manager: restart client
,2016-03-20 12:43:54.758 ThaliTest[1864:3097744] client: found updated peer: 5A342616-0ECA-48AE-829A-448F633DC8C8:8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"5A342616-0ECA-48AE-829A-448F633DC8C8:8","pleaseConnect":0}]
,2016-03-20 12:43:56.734 ThaliTest[1864:3097999] jxcore: connect 5A342616-0ECA-48AE-829A-448F633DC8C8:7
,2016-03-20 12:43:56.735 ThaliTest[1864:3097999] client session: connect
,2016-03-20 12:43:56.735 ThaliTest[1864:3097999] client session: stateChange:0->1 5A342616-0ECA-48AE-829A-448F633DC8C8:8
,2016-03-20 12:43:56.874 ThaliTest[1864:3098500] client session: not connected 5A342616-0ECA-48AE-829A-448F633DC8C8:8
2016-03-20 12:43:56.874 ThaliTest[1864:3098500] client session: onLinkFailure: 5A342616-0ECA-48AE-829A-448F633DC8C8
2016-03-20 12:43:56.875 ThaliTest[1864:3098500] client session: disconnect
,2016-03-20 12:43:56.875 ThaliTest[1864:3098500] client session: stateChange:1->0 5A342616-0ECA-48AE-829A-448F633DC8C8:8
,2016-03-20 12:43:56.876 ThaliTest[1864:3098500] client session: fireConnectCallback: 5A342616-0ECA-48AE-829A-448F633DC8C8
2016-03-20 12:43:56.876 ThaliTest[1864:3098500] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-20 12:43:59.892 ThaliTest[1864:3097999] jxcore: connect 5A342616-0ECA-48AE-829A-448F633DC8C8:7
,2016-03-20 12:43:59.893 ThaliTest[1864:3097999] client session: connect
,2016-03-20 12:43:59.894 ThaliTest[1864:3097999] client session: stateChange:0->1 5A342616-0ECA-48AE-829A-448F633DC8C8:8
,2016-03-20 12:44:00.017 ThaliTest[1864:3098500] client session: not connected 5A342616-0ECA-48AE-829A-448F633DC8C8:8
,2016-03-20 12:44:00.017 ThaliTest[1864:3098500] client session: onLinkFailure: 5A342616-0ECA-48AE-829A-448F633DC8C8
,2016-03-20 12:44:00.018 ThaliTest[1864:3098500] client session: disconnect
,2016-03-20 12:44:00.018 ThaliTest[1864:3098500] client session: stateChange:1->0 5A342616-0ECA-48AE-829A-448F633DC8C8:8
,2016-03-20 12:44:00.021 ThaliTest[1864:3098500] client session: fireConnectCallback: 5A342616-0ECA-48AE-829A-448F633DC8C8
2016-03-20 12:44:00.021 ThaliTest[1864:3098500] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-20 12:44:03.029 ThaliTest[1864:3097999] jxcore: connect 5A342616-0ECA-48AE-829A-448F633DC8C8:7
,2016-03-20 12:44:03.030 ThaliTest[1864:3097999] client session: connect
2016-03-20 12:44:03.030 ThaliTest[1864:3097999] client session: stateChange:0->1 5A342616-0ECA-48AE-829A-448F633DC8C8:8
,2016-03-20 12:44:03.170 ThaliTest[1864:3097744] multipeer session: reset timer
2016-03-20 12:44:03.170 ThaliTest[1864:3097744] server: disconnecting to refresh session (5A342616-0ECA-48AE-829A-448F633DC8C8)
2016-03-20 12:44:03.171 ThaliTest[1864:3097744], server: rejecting invitation for lexical ordering 5A342616-0ECA-48AE-829A-448F633DC8C8
2016-03-20 12:44:03.171 ThaliTest[1864:3098500] client session: not connected 5A342616-0ECA-48AE-829A-448F633DC8C8:8
2016-03-20 12:44:03.171 ThaliTest[1864:3098500] c,lient session: onLinkFailure: 5A342616-0ECA-48AE-829A-448F633DC8C8
,2016-03-20 12:44:03.172 ThaliTest[1864:3098500] client session: disconnect
,2016-03-20 12:44:03.174 ThaliTest[1864:3098500] client session: stateChange:1->0 5A342616-0ECA-48AE-829A-448F633DC8C8:8
,2016-03-20 12:44:03.176 ThaliTest[1864:3098500] client session: fireConnectCallback: 5A342616-0ECA-48AE-829A-448F633DC8C8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"5A342616-0ECA-48AE-829A-448F633DC8C8:8","pleaseConnect":1}]
,2016-03-20 12:44:03.176 ThaliTest[1864:3098500] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-20 12:44:06.192 ThaliTest[1864:3097999] jxcore: connect 5A342616-0ECA-48AE-829A-448F633DC8C8:7
,2016-03-20 12:44:06.193 ThaliTest[1864:3097999] client session: connect
,2016-03-20 12:44:06.194 ThaliTest[1864:3097999] client session: stateChange:0->1 5A342616-0ECA-48AE-829A-448F633DC8C8:8
,2016-03-20 12:44:06.297 ThaliTest[1864:3098536] client session: not connected 5A342616-0ECA-48AE-829A-448F633DC8C8:8
2016-03-20 12:44:06.297 ThaliTest[1864:3098536] client session: onLinkFailure: 5A342616-0ECA-48AE-829A-448F633DC8C8
2016-03-20 12:44:06.2,97 ThaliTest[1864:3098536] client session: disconnect
,2016-03-20 12:44:06.298 ThaliTest[1864:3098536] client session: stateChange:1->0 5A342616-0ECA-48AE-829A-448F633DC8C8:8
,2016-03-20 12:44:06.300 ThaliTest[1864:3098536] client session: fireConnectCallback: 5A342616-0ECA-48AE-829A-448F633DC8C8
,2016-03-20 12:44:06.300 ThaliTest[1864:3098536] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,WARN testThaliMobileNative: Too many connect retries!
,not ok 157 Connect failed!
,  ---
,    operator: fail
,  ...
,# setup
,2016-03-20 12:44:14.748 ThaliTest[1864:3097744] multipeer manager: restart client
,2016-03-20 12:44:14.760 ThaliTest[1864:3097744] client: found existing peer: 5A342616-0ECA-48AE-829A-448F633DC8C8:8
,2016-03-20 12:44:16.763 ThaliTest[1864:3097744] multipeer session: reset timer
,2016-03-20 12:44:16.764 ThaliTest[1864:3097744] server: disconnecting to refresh session (5A342616-0ECA-48AE-829A-448F633DC8C8)
,2016-03-20 12:44:16.764 ThaliTest[1864:3097744] server: rejecting invitation for lexical ordering 5A342616-0ECA-48AE-829A-448F633DC8C8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"5A342616-0ECA-48AE-829A-448F633DC8C8:8","pleaseConnect":1}]
,2016-03-20 12:44:30.072 ThaliTest[1864:3097744] multipeer session: reset timer
,2016-03-20 12:44:30.073 ThaliTest[1864:3097744] server: disconnecting to refresh session (5A342616-0ECA-48AE-829A-448F633DC8C8)
2016-03-20 12:44:30.073 ThaliTest[1864:3097744] server: rejecting invitation for lexical ordering 5A342616-0ECA-48AE-829A-448F633DC8C8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"5A342616-0ECA-48AE-829A-448F633DC8C8:8","pleaseConnect":1}]
,2016-03-20 12:44:34.748 ThaliTest[1864:3097744] multipeer manager: restart client
,2016-03-20 12:44:34.762 ThaliTest[1864:3097744] client: found existing peer: 5A342616-0ECA-48AE-829A-448F633DC8C8:8
,2016-03-20 12:44:42.435 ThaliTest[1864:3097744] multipeer session: reset timer
,2016-03-20 12:44:42.436 ThaliTest[1864:3097744] server: disconnecting to refresh session (5A342616-0ECA-48AE-829A-448F633DC8C8)
,2016-03-20 12:44:42.436 ThaliTest[1864:3097744] server: rejecting invitation for lexical ordering 5A342616-0ECA-48AE-829A-448F633DC8C8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"5A342616-0ECA-48AE-829A-448F633DC8C8:8","pleaseConnect":1}]
,2016-03-20 12:44:54.748 ThaliTest[1864:3097744] multipeer manager: restart client
,2016-03-20 12:44:54.761 ThaliTest[1864:3097744] client: found existing peer: 5A342616-0ECA-48AE-829A-448F633DC8C8:8
,2016-03-20 12:44:55.711 ThaliTest[1864:3097744] multipeer session: reset timer
2016-03-20 12:44:55.712 ThaliTest[1864:3097744] server: disconnecting to refresh session (5A342616-0ECA-48AE-829A-448F633DC8C8)
2016-03-20 12:44:55.712 ThaliTest[1864:3097744] server: rejecting invitation for lexical ordering 5A342616-0ECA-48AE-829A-448F633DC8C8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"5A342616-0ECA-48AE-829A-448F633DC8C8:8","pleaseConnect":1}]
,2016-03-20 12:45:08.221 ThaliTest[1864:3097744] multipeer session: reset timer
2016-03-20 12:45:08.221 ThaliTest[1864:3097744] server: disconnecting to refresh session (5A342616-0ECA-48AE-829A-448F633DC8C8)
2016-03-20 12:45:08.222 ThaliTest[1864:3097744] server: rejecting invitation for lexical ordering 5A342616-0ECA-48AE-829A-448F633DC8C8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"5A342616-0ECA-48AE-829A-448F633DC8C8:8","pleaseConnect":1}]
,2016-03-20 12:45:14.747 ThaliTest[1864:3097744] multipeer manager: restart client
,2016-03-20 12:45:14.761 ThaliTest[1864:3097744] client: found existing peer: 5A342616-0ECA-48AE-829A-448F633DC8C8:8
,2016-03-20 12:45:21.316 ThaliTest[1864:3097744] multipeer session: reset timer
,2016-03-20 12:45:21.316 ThaliTest[1864:3097744] server: disconnecting to refresh session (5A342616-0ECA-48AE-829A-448F633DC8C8)
,2016-03-20 12:45:21.317 ThaliTest[1864:3097744] server: rejecting invitation for lexical ordering 5A342616-0ECA-48AE-829A-448F633DC8C8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"5A342616-0ECA-48AE-829A-448F633DC8C8:8","pleaseConnect":1}]
,2016-03-20 12:45:34.434 ThaliTest[1864:3097744] multipeer session: reset timer
2016-03-20 12:45:34.435 ThaliTest[1864:3097744] server: disconnecting to refresh session (5A342616-0ECA-48AE-829A-448F633DC8C8)
2016-03-20 12:45:34.435 ThaliTest[1864:3097744] server: rejecting invitation for lexical ordering 5A342616-0ECA-48AE-829A-448F633DC8C8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"5A342616-0ECA-48AE-829A-448F633DC8C8:8","pleaseConnect":1}]
,2016-03-20 12:45:34.748 ThaliTest[1864:3097744] multipeer manager: restart client
,2016-03-20 12:45:34.763 ThaliTest[1864:3097744] client: found existing peer: 5A342616-0ECA-48AE-829A-448F633DC8C8:8
,2016-03-20 12:45:44.464 ThaliTest[1864:3097999] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-20 12:45:44.466 ThaliTest[1864:3097999] jxcore: stopListeningForAdvertisements: success
,ok 158 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-20 12:45:44.469 ThaliTest[1864:3097999] jxcore: stopAdvertisingAndListening
,2016-03-20 12:45:44.469 ThaliTest[1864:3097999] THEMultipeerManager stopping peer
,2016-03-20 12:45:44.470 ThaliTest[1864:3097999] multipeer manager: stop client timer
,2016-03-20 12:45:44.471 ThaliTest[1864:3097999] jxcore: stopAdvertisingAndListening: success
,ok 159 Should be able to call stopAdvertisingAndListening in teardown
,# 38. Can shift large amounts of data
,# teardown
,2016-03-20 12:45:45.477 ThaliTest[1864:3097999] jxcore: startUpdateAdvertisingAndListening
,2016-03-20 12:45:45.477 ThaliTest[1864:3097999] server: starting F82F884A-9394-418C-8996-A62FEDB8DD77:9
,2016-03-20 12:45:45.479 ThaliTest[1864:3097999] multipeer manager: start client restart timer: 0x14e8bad0
2016-03-20 12:45:45.479 ThaliTest[1864:3097999] THEMultipeerManager initialized peer F82F884A-9394-418C-8996-A62FEDB8DD77:9
2016-03-20 12:45:45.479 ,ThaliTest[1864:3097999] jxcore: startUpdateAdvertisingAndListening: success
ok 160 Can call startUpdateAdvertisingAndListening without error
,2016-03-20 12:45:45.483 ThaliTest[1864:3097999] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-20 12:45:45.484 ThaliTest[1864:3097999] jxcore: startListeningForAdvertisements: success
ok 161 Can call startListeningForAdvertisements without error
,2016-03-20 12:45:45.845 ThaliTest[1864:3097744] client: found new peer: 5A342616-0ECA-48AE-829A-448F633DC8C8:8
,2016-03-20 12:45:45.847 ThaliTest[1864:3097999] jxcore: connect 5A342616-0ECA-48AE-829A-448F633DC8C8:8
,2016-03-20 12:45:45.848 ThaliTest[1864:3097999] client session: connect
,2016-03-20 12:45:45.848 ThaliTest[1864:3097999] client session: stateChange:0->1 5A342616-0ECA-48AE-829A-448F633DC8C8:8
,2016-03-20 12:45:46.417 ThaliTest[1864:3097744] multipeer session: reset timer
2016-03-20 12:45:46.418 ThaliTest[1864:3097744] server: rejecting invitation from 5A342616-0ECA-48AE-829A-448F633DC8C8 due to previous generation (F82F884A-9394-418C-8996-A62FEDB8DD77:9 != F82F884A-9394-418C-8996-A62FEDB8DD77:8)
,2016-03-20 12:45:46.685 ThaliTest[1864:3098928] client session: not connected 5A342616-0ECA-48AE-829A-448F633DC8C8:8
2016-03-20 12:45:46.686 ThaliTest[1864:3098928] client session: onLinkFailure: 5A342616-0ECA-48AE-829A-448F633DC8C8
2016-03-20 12:45:46.6,86 ThaliTest[1864:3098928] client session: disconnect
2016-03-20 12:45:46.686 ThaliTest[1864:3098928] client session: stateChange:1->0 5A342616-0ECA-48AE-829A-448F633DC8C8:8
,2016-03-20 12:45:46.687 ThaliTest[1864:3098928] client session: fireConnectCallback: 5A342616-0ECA-48AE-829A-448F633DC8C8
2016-03-20 12:45:46.688 ThaliTest[1864:3098928] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-20 12:45:49.693 ThaliTest[1864:3097999] jxcore: connect 5A342616-0ECA-48AE-829A-448F633DC8C8:8
,2016-03-20 12:45:49.694 ThaliTest[1864:3097999] client session: connect
,2016-03-20 12:45:49.695 ThaliTest[1864:3097999] client session: stateChange:0->1 5A342616-0ECA-48AE-829A-448F633DC8C8:8
,2016-03-20 12:45:51.143 ThaliTest[1864:3098928] client session: not connected 5A342616-0ECA-48AE-829A-448F633DC8C8:8
2016-03-20 12:45:51.143 ThaliTest[1864:3098928] client session: onLinkFailure: 5A342616-0ECA-48AE-829A-448F633DC8C8
2016-03-20 12:45:51.1,44 ThaliTest[1864:3098928] client session: disconnect
2016-03-20 12:45:51.144 ThaliTest[1864:3098928] client session: stateChange:1->0 5A342616-0ECA-48AE-829A-448F633DC8C8:8
,2016-03-20 12:45:51.144 ThaliTest[1864:3098928] client session: fireConnectCallback: 5A342616-0ECA-48AE-829A-448F633DC8C8
,2016-03-20 12:45:51.145 ThaliTest[1864:3098928] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-20 12:45:54.158 ThaliTest[1864:3097999] jxcore: connect 5A342616-0ECA-48AE-829A-448F633DC8C8:8
,2016-03-20 12:45:54.159 ThaliTest[1864:3097999] client session: connect
,2016-03-20 12:45:54.159 ThaliTest[1864:3097999] client session: stateChange:0->1 5A342616-0ECA-48AE-829A-448F633DC8C8:8
,2016-03-20 12:45:54.278 ThaliTest[1864:3098928] client session: not connected 5A342616-0ECA-48AE-829A-448F633DC8C8:8
,2016-03-20 12:45:54.279 ThaliTest[1864:3098928] client session: onLinkFailure: 5A342616-0ECA-48AE-829A-448F633DC8C8
2016-03-20 12:45:54.281 ThaliTest[1864:3098928] client session: disconnect
2016-03-20 12:45:54.281 ThaliTest[1864:3098928] client session: stateChange:1->0 5A342616-0ECA-48AE-829A-448F633DC8C8:8
,2016-03-20 12:45:54.282 ThaliTest[1864:3098928] client session: fireConnectCallback: 5A342616-0ECA-48AE-829A-448F633DC8C8
2016-03-20 12:45:54.282 ThaliTest[1864:3098928] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-20 12:45:57.297 ThaliTest[1864:3097999] jxcore: connect 5A342616-0ECA-48AE-829A-448F633DC8C8:8
,2016-03-20 12:45:57.297 ThaliTest[1864:3097999] client session: connect
,2016-03-20 12:45:57.298 ThaliTest[1864:3097999] client session: stateChange:0->1 5A342616-0ECA-48AE-829A-448F633DC8C8:8
,2016-03-20 12:45:57.431 ThaliTest[1864:3098929] client session: not connected 5A342616-0ECA-48AE-829A-448F633DC8C8:8
2016-03-20 12:45:57.431 ThaliTest[1864:3098929] client session: onLinkFailure: 5A342616-0ECA-48AE-829A-448F633DC8C8
2016-03-20 12:45:57.4,32 ThaliTest[1864:3098929] client session: disconnect
2016-03-20 12:45:57.432 ThaliTest[1864:3098929] client session: stateChange:1->0 5A342616-0ECA-48AE-829A-448F633DC8C8:8
,2016-03-20 12:45:57.433 ThaliTest[1864:3098929] client session: fireConnectCallback: 5A342616-0ECA-48AE-829A-448F633DC8C8
2016-03-20 12:45:57.433 ThaliTest[1864:3098929] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-20 12:45:58.940 ThaliTest[1864:3097744] multipeer session: reset timer
2016-03-20 12:45:58.941 ThaliTest[1864:3097744] server: disconnecting to refresh session (5A342616-0ECA-48AE-829A-448F633DC8C8)
,2016-03-20 12:45:58.941 ThaliTest[1864:3097744] server: rejecting invitation from 5A342616-0ECA-48AE-829A-448F633DC8C8 due to previous generation (F82F884A-9394-418C-8996-A62FEDB8DD77:9 != F82F884A-9394-418C-8996-A62FEDB8DD77:8)
,2016-03-20 12:46:00.439 ThaliTest[1864:3097999] jxcore: connect 5A342616-0ECA-48AE-829A-448F633DC8C8:8
,2016-03-20 12:46:00.440 ThaliTest[1864:3097999] client session: connect
,2016-03-20 12:46:00.440 ThaliTest[1864:3097999] client session: stateChange:0->1 5A342616-0ECA-48AE-829A-448F633DC8C8:8
,2016-03-20 12:46:00.575 ThaliTest[1864:3098928] client session: not connected 5A342616-0ECA-48AE-829A-448F633DC8C8:8
2016-03-20 12:46:00.576 ThaliTest[1864:3098928] client session: onLinkFailure: 5A342616-0ECA-48AE-829A-448F633DC8C8
2016-03-20 12:46:00.5,76 ThaliTest[1864:3098928] client session: disconnect
,2016-03-20 12:46:00.577 ThaliTest[1864:3098928] client session: stateChange:1->0 5A342616-0ECA-48AE-829A-448F633DC8C8:8
,2016-03-20 12:46:00.578 ThaliTest[1864:3098928] client session: fireConnectCallback: 5A342616-0ECA-48AE-829A-448F633DC8C8
2016-03-20 12:46:00.579 ThaliTest[1864:3098928] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-20 12:46:03.588 ThaliTest[1864:3097999] jxcore: connect 5A342616-0ECA-48AE-829A-448F633DC8C8:8
,2016-03-20 12:46:03.589 ThaliTest[1864:3097999] client session: connect
2016-03-20 12:46:03.590 ThaliTest[1864:3097999] client session: stateChange:0->1 5A342616-0ECA-48AE-829A-448F633DC8C8:8
,2016-03-20 12:46:04.049 ThaliTest[1864:3098942] client session: not connected 5A342616-0ECA-48AE-829A-448F633DC8C8:8
2016-03-20 12:46:04.050 ThaliTest[1864:3098942] client session: onLinkFailure: 5A342616-0ECA-48AE-829A-448F633DC8C8
2016-03-20 12:46:04.050 ThaliTest[1864:3098942] client session: disconnect
2016-03-20 12:46:04.051 ThaliTest[1864:3098942] client session: stateChange:1->0 5A342616-0ECA-48AE-829A-448F633DC8C8:8
2016-03-20 12:46:04.051 ThaliTest[1864:3098942] client session: fireConnectCallb,ack: 5A342616-0ECA-48AE-829A-448F633DC8C8
2016-03-20 12:46:04.052 ThaliTest[1864:3098942] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-20 12:46:05.480 ThaliTest[1864:3097744] multipeer manager: restart client
,2016-03-20 12:46:05.496 ThaliTest[1864:3097744] client: found updated peer: 5A342616-0ECA-48AE-829A-448F633DC8C8:9
,2016-03-20 12:46:07.065 ThaliTest[1864:3097999] jxcore: connect 5A342616-0ECA-48AE-829A-448F633DC8C8:8
,2016-03-20 12:46:07.066 ThaliTest[1864:3097999] client session: connect
2016-03-20 12:46:07.066 ThaliTest[1864:3097999] client session: stateChange:0->1 5A342616-0ECA-48AE-829A-448F633DC8C8:9
,2016-03-20 12:46:07.479 ThaliTest[1864:3098928] client session: not connected 5A342616-0ECA-48AE-829A-448F633DC8C8:9
2016-03-20 12:46:07.479 ThaliTest[1864:3098928] client session: onLinkFailure: 5A342616-0ECA-48AE-829A-448F633DC8C8
2016-03-20 12:46:07.479 ThaliTest[1864:3098928] client session: disconnect
2016-03-20 12:46:07.480 ThaliTest[1864:3098928] client session: stateChange:1->0 5A342616-0ECA-48AE-829A-448F633DC8C8:9
,2016-03-20 12:46:07.480 ThaliTest[1864:3098928] client session: fireConnectCallback: 5A342616-0ECA-48AE-829A-448F633DC8C8
2016-03-20 12:46:07.481 ThaliTest[1864:3098928] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-20 12:46:10.491 ThaliTest[1864:3097999] jxcore: connect 5A342616-0ECA-48AE-829A-448F633DC8C8:8
,2016-03-20 12:46:10.491 ThaliTest[1864:3097999] client session: connect
2016-03-20 12:46:10.492 ThaliTest[1864:3097999] client session: stateChange:0->1 5A342616-0ECA-48AE-829A-448F633DC8C8:9
,2016-03-20 12:46:10.604 ThaliTest[1864:3098928] client session: not connected 5A342616-0ECA-48AE-829A-448F633DC8C8:9
,2016-03-20 12:46:10.605 ThaliTest[1864:3098928] client session: onLinkFailure: 5A342616-0ECA-48AE-829A-448F633DC8C8
,2016-03-20 12:46:10.606 ThaliTest[1864:3098928] client session: disconnect
,2016-03-20 12:46:10.606 ThaliTest[1864:3098928] client session: stateChange:1->0 5A342616-0ECA-48AE-829A-448F633DC8C8:9
,2016-03-20 12:46:10.607 ThaliTest[1864:3098928] client session: fireConnectCallback: 5A342616-0ECA-48AE-829A-448F633DC8C8
,2016-03-20 12:46:10.607 ThaliTest[1864:3098928] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-20 12:46:11.934 ThaliTest[1864:3097744] multipeer session: reset timer
2016-03-20 12:46:11.935 ThaliTest[1864:3097744] server: disconnecting to refresh session (5A342616-0ECA-48AE-829A-448F633DC8C8)
2016-03-20 12:46:11.935 ThaliTest[1864:3097744], server: rejecting invitation from 5A342616-0ECA-48AE-829A-448F633DC8C8 due to previous generation (F82F884A-9394-418C-8996-A62FEDB8DD77:9 != F82F884A-9394-418C-8996-A62FEDB8DD77:8)
,2016-03-20 12:46:13.614 ThaliTest[1864:3097999] jxcore: connect 5A342616-0ECA-48AE-829A-448F633DC8C8:8
,2016-03-20 12:46:13.615 ThaliTest[1864:3097999] client session: connect
,2016-03-20 12:46:13.615 ThaliTest[1864:3097999] client session: stateChange:0->1 5A342616-0ECA-48AE-829A-448F633DC8C8:9
,2016-03-20 12:46:13.702 ThaliTest[1864:3098928] client session: not connected 5A342616-0ECA-48AE-829A-448F633DC8C8:9
2016-03-20 12:46:13.703 ThaliTest[1864:3098928] client session: onLinkFailure: 5A342616-0ECA-48AE-829A-448F633DC8C8
2016-03-20 12:46:13.7,03 ThaliTest[1864:3098928] client session: disconnect
2016-03-20 12:46:13.704 ThaliTest[1864:3098928] client session: stateChange:1->0 5A342616-0ECA-48AE-829A-448F633DC8C8:9
,2016-03-20 12:46:13.706 ThaliTest[1864:3098928] client session: fireConnectCallback: 5A342616-0ECA-48AE-829A-448F633DC8C8
2016-03-20 12:46:13.706 ThaliTest[1864:3098928] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-20 12:46:16.717 ThaliTest[1864:3097999] jxcore: connect 5A342616-0ECA-48AE-829A-448F633DC8C8:8
,2016-03-20 12:46:16.718 ThaliTest[1864:3097999] client session: connect
,2016-03-20 12:46:16.719 ThaliTest[1864:3097999] client session: stateChange:0->1 5A342616-0ECA-48AE-829A-448F633DC8C8:9
,2016-03-20 12:46:16.824 ThaliTest[1864:3098929] client session: not connected 5A342616-0ECA-48AE-829A-448F633DC8C8:9
,2016-03-20 12:46:16.825 ThaliTest[1864:3098929] client session: onLinkFailure: 5A342616-0ECA-48AE-829A-448F633DC8C8
,2016-03-20 12:46:16.825 ThaliTest[1864:3098929] client session: disconnect
,2016-03-20 12:46:16.826 ThaliTest[1864:3098929] client session: stateChange:1->0 5A342616-0ECA-48AE-829A-448F633DC8C8:9
2016-03-20 12:46:16.828 ThaliTest[1864:3098929] client session: fireConnectCallback: 5A342616-0ECA-48AE-829A-448F633DC8C8
2016-03-20 1,2:46:16.828 ThaliTest[1864:3098929] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,WARN testThaliMobileNative: Too many connect retries!
,not ok 162 Connect failed!
  ---
,    operator: fail
,  ...
,# setup
,2016-03-20 12:46:25.480 ThaliTest[1864:3097744] multipeer manager: restart client
,2016-03-20 12:46:25.494 ThaliTest[1864:3097744] client: found existing peer: 5A342616-0ECA-48AE-829A-448F633DC8C8:9
,2016-03-20 12:46:45.480 ThaliTest[1864:3097744] multipeer manager: restart client
,2016-03-20 12:46:45.496 ThaliTest[1864:3097744] client: found existing peer: 5A342616-0ECA-48AE-829A-448F633DC8C8:9
,2016-03-20 12:46:54.479 ThaliTest[1864:3097999] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-20 12:46:54.482 ThaliTest[1864:3097999] jxcore: stopListeningForAdvertisements: success
,ok 163 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-20 12:46:54.484 ThaliTest[1864:3097999] jxcore: stopAdvertisingAndListening
,2016-03-20 12:46:54.485 ThaliTest[1864:3097999] THEMultipeerManager stopping peer
,2016-03-20 12:46:54.486 ThaliTest[1864:3097999] multipeer manager: stop client timer
,2016-03-20 12:46:54.489 ThaliTest[1864:3097999] jxcore: stopAdvertisingAndListening: success
,ok 164 Should be able to call stopAdvertisingAndListening in teardown
,# 39. #startListeningForAdvertisements should fail if start not called
,2016-03-20 12:46:54.724 ThaliTest[1864:3097999] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-20 12:46:54.725 ThaliTest[1864:3097999] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-20 12:46:54.726 ThaliTest[1864:3097999] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-20 12:46:54.730 ThaliTest[1864:3097999] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,ok 165 specific error should be returned
,# setup
,# 40. #startUpdateAdvertisingAndListening should fail if start not called
,2016-03-20 12:46:55.430 ThaliTest[1864:3097999] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-20 12:46:55.432 ThaliTest[1864:3097999] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-20 12:46:55.433 ThaliTest[1864:3097999] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-20 12:46:55.435 ThaliTest[1864:3097999] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,ok 166 specific error should be returned
,# setup
,# 41. should be able to call #stopListeningForAdvertisements many times
,2016-03-20 12:46:55.914 ThaliTest[1864:3097999] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-20 12:46:55.915 ThaliTest[1864:3097999] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-20 12:46:55.916 ThaliTest[1864:3097999] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-20 12:46:55.919 ThaliTest[1864:3097999] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49370
,2016-03-20 12:46:56.050 ThaliTest[1864:3097999] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-20 12:46:56.052 ThaliTest[1864:3097999] jxcore: stopListeningForAdvertisements: success
,ok 167 no errors
,2016-03-20 12:46:56.056 ThaliTest[1864:3097999] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-20 12:46:56.058 ThaliTest[1864:3097999] jxcore: stopListeningForAdvertisements: success
,ok 168 still no errors
,# setup
,2016-03-20 12:46:56.271 ThaliTest[1864:3097999] jxcore: stopAdvertisingAndListening
,2016-03-20 12:46:56.272 ThaliTest[1864:3097999] THEMultipeerManager stopping peer
,2016-03-20 12:46:56.272 ThaliTest[1864:3097999] jxcore: stopAdvertisingAndListening: success
,2016-03-20 12:46:56.274 ThaliTest[1864:3097999] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-20 12:46:56.276 ThaliTest[1864:3097999] jxcore: stopListeningForAdvertisements: success
,# 42. should be able to call #startListeningForAdvertisements many times
,2016-03-20 12:46:56.400 ThaliTest[1864:3097999] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-20 12:46:56.401 ThaliTest[1864:3097999] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-20 12:46:56.402 ThaliTest[1864:3097999] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-20 12:46:56.405 ThaliTest[1864:3097999] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49372
,2016-03-20 12:46:56.691 ThaliTest[1864:3097999] jxcore: startListeningForAdvertisements
,2016-03-20 12:46:56.691 ThaliTest[1864:3097999] multipeer manager: start client restart timer: 0x14e8bad0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-20 12:46:56.694 ThaliTest[1864:3097999] jxcore: startListeningForAdvertisements: success
,ok 169 no errors
,2016-03-20 12:46:56.700 ThaliTest[1864:3097999] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-20 12:46:56.703 ThaliTest[1864:3097999] jxcore: startListeningForAdvertisements: success
,ok 170 still no errors
,# setup
,2016-03-20 12:46:56.830 ThaliTest[1864:3097999] jxcore: stopAdvertisingAndListening
,2016-03-20 12:46:56.831 ThaliTest[1864:3097999] THEMultipeerManager stopping peer
,2016-03-20 12:46:56.831 ThaliTest[1864:3097999] jxcore: stopAdvertisingAndListening: success
,2016-03-20 12:46:56.832 ThaliTest[1864:3097999] jxcore: stopListeningForAdvertisements
,2016-03-20 12:46:56.833 ThaliTest[1864:3097999] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-20 12:46:56.836 ThaliTest[1864:3097999] jxcore: stopListeningForAdvertisements: success
,# 43. should be able to call #startUpdateAdvertisingAndListening many times
,2016-03-20 12:46:56.985 ThaliTest[1864:3097999] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-20 12:46:56.986 ThaliTest[1864:3097999] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-20 12:46:56.988 ThaliTest[1864:3097999] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-20 12:46:56.991 ThaliTest[1864:3097999] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49374
,2016-03-20 12:46:57.139 ThaliTest[1864:3097999] jxcore: startUpdateAdvertisingAndListening
,2016-03-20 12:46:57.140 ThaliTest[1864:3097999] server: starting F82F884A-9394-418C-8996-A62FEDB8DD77:10
,2016-03-20 12:46:57.141 ThaliTest[1864:3097999] multipeer manager: start client restart timer: 0x14e8bad0
,2016-03-20 12:46:57.142 ThaliTest[1864:3097999] THEMultipeerManager initialized peer F82F884A-9394-418C-8996-A62FEDB8DD77:10
2016-03-20 12:46:57.142 ThaliTest[1864:3097999] jxcore: startUpdateAdvertisingAndListening: success
,ok 171 no errors
,2016-03-20 12:46:57.146 ThaliTest[1864:3097999] jxcore: startUpdateAdvertisingAndListening
2016-03-20 12:46:57.146 ThaliTest[1864:3097999] THEMultipeerManager stopping peer
2016-03-20 12:46:57.147 ThaliTest[1864:3097999] multipeer manager: stop client ti,mer
2016-03-20 12:46:57.148 ThaliTest[1864:3097999] server: starting F82F884A-9394-418C-8996-A62FEDB8DD77:11
,2016-03-20 12:46:57.149 ThaliTest[1864:3097999] multipeer manager: start client restart timer: 0x14e8bad0
,2016-03-20 12:46:57.151 ThaliTest[1864:3097999] THEMultipeerManager initialized peer F82F884A-9394-418C-8996-A62FEDB8DD77:11
,2016-03-20 12:46:57.151 ThaliTest[1864:3097999] jxcore: startUpdateAdvertisingAndListening: success
,ok 172 still no errors
# setup
,2016-03-20 12:46:57.488 ThaliTest[1864:3097999] jxcore: stopAdvertisingAndListening
,2016-03-20 12:46:57.489 ThaliTest[1864:3097999] THEMultipeerManager stopping peer
,2016-03-20 12:46:57.489 ThaliTest[1864:3097999] multipeer manager: stop client timer
2016-03-20 12:46:57.490 ThaliTest[1864:3097999] jxcore: stopAdvertisingAndListening: success
2016-03-20 12:46:57.491 ThaliTest[1864:3097999] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-20 12:46:57.494 ThaliTest[1864:3097999] jxcore: stopListeningForAdvertisements: success
,# 44. should be able to call #stopAdvertisingAndListening many times
,2016-03-20 12:46:57.795 ThaliTest[1864:3097999] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-20 12:46:57.796 ThaliTest[1864:3097999] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-20 12:46:57.798 ThaliTest[1864:3097999] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-20 12:46:57.801 ThaliTest[1864:3097999] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49378
,2016-03-20 12:46:58.037 ThaliTest[1864:3097999] jxcore: stopAdvertisingAndListening
2016-03-20 12:46:58.037 ThaliTest[1864:3097999] THEMultipeerManager stopping peer
,2016-03-20 12:46:58.038 ThaliTest[1864:3097999] jxcore: stopAdvertisingAndListening: success
,ok 173 no errors
,2016-03-20 12:46:58.041 ThaliTest[1864:3097999] jxcore: stopAdvertisingAndListening
,2016-03-20 12:46:58.042 ThaliTest[1864:3097999] THEMultipeerManager stopping peer
,2016-03-20 12:46:58.042 ThaliTest[1864:3097999] jxcore: stopAdvertisingAndListening: success
,ok 174 still no errors
,# setup
,2016-03-20 12:46:58.208 ThaliTest[1864:3097999] jxcore: stopAdvertisingAndListening
2016-03-20 12:46:58.209 ThaliTest[1864:3097999] THEMultipeerManager stopping peer
,2016-03-20 12:46:58.209 ThaliTest[1864:3097999] jxcore: stopAdvertisingAndListening: success
,2016-03-20 12:46:58.211 ThaliTest[1864:3097999] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-20 12:46:58.213 ThaliTest[1864:3097999] jxcore: stopListeningForAdvertisements: success
,# 45. can get the network status before starting
,2016-03-20 12:46:58.543 ThaliTest[1864:3097999] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-20 12:46:58.544 ThaliTest[1864:3097999] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-20 12:46:58.545 ThaliTest[1864:3097999] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-20 12:46:58.547 ThaliTest[1864:3097999] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,ok 175 network status should have certain non-empty properties
,# setup
,# 46. error returned with bad router
,2016-03-20 12:47:00.009 ThaliTest[1864:3097999] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-20 12:47:00.011 ThaliTest[1864:3097999] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-20 12:47:00.012 ThaliTest[1864:3,097999] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-20 12:47:00.017 ThaliTest[1864:3097999] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
,ok 176 specific error expected
,# setup
,# 47. can do HTTP requests between peers
,2016-03-20 12:47:00.638 ThaliTest[1864:3097999] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-20 12:47:00.640 ThaliTest[1864:3097999] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-20 12:47:00.640 ThaliTest[1864:3097999] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-20 12:47:00.643 ThaliTest[1864:3097999] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49380
,2016-03-20 12:47:00.871 ThaliTest[1864:3097999] jxcore: startListeningForAdvertisements
,2016-03-20 12:47:00.872 ThaliTest[1864:3097999] multipeer manager: start client restart timer: 0x14e8bad0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-20 12:47:00.875 ThaliTest[1864:3097999] jxcore: startListeningForAdvertisements: success
2016-03-20 12:47:00.877 ThaliTest[1864:3097999] jxcore: startUpdateAdvertisingAndListening
,2016-03-20 12:47:00.878 ThaliTest[1864:3097999] server: starting F82F884A-9394-418C-8996-A62FEDB8DD77:12
,2016-03-20 12:47:00.879 ThaliTest[1864:3097999] THEMultipeerManager initialized peer F82F884A-9394-418C-8996-A62FEDB8DD77:12
2016-03-20 12:47:00.880 ThaliTest[1864:3097999] jxcore: startUpdateAdvertisingAndListening: success
,2016-03-20 12:47:02.245 ThaliTest[1864:3097744] client: found new peer: 5A342616-0ECA-48AE-829A-448F633DC8C8:9
,DEBUG createPeerListener: createPeerListener
,DEBUG createPeerListener: pleaseConnect= 0
,ok 177 found a peer! {"peerIdentifier":"5A342616-0ECA-48AE-829A-448F633DC8C8:9","portNumber":49382,"hostAddress":"127.0.0.1"}
,DEBUG createPeerListener: first connection
,2016-03-20 12:47:02.278 ThaliTest[1864:3097999] jxcore: connect 5A342616-0ECA-48AE-829A-448F633DC8C8:9
,2016-03-20 12:47:02.278 ThaliTest[1864:3097999] client session: connect
,2016-03-20 12:47:02.279 ThaliTest[1864:3097999] client session: stateChange:0->1 5A342616-0ECA-48AE-829A-448F633DC8C8:9
,2016-03-20 12:47:03.666 ThaliTest[1864:3097744] multipeer session: reset timer
2016-03-20 12:47:03.667 ThaliTest[1864:3097744] server: rejecting invitation from 5A342616-0ECA-48AE-829A-448F633DC8C8 due to previous generation (F82F884A-9394-418C-8996-A62FE,DB8DD77:12 != F82F884A-9394-418C-8996-A62FEDB8DD77:9)
,2016-03-20 12:47:03.671 ThaliTest[1864:3099093] client session: not connected 5A342616-0ECA-48AE-829A-448F633DC8C8:9
2016-03-20 12:47:03.672 ThaliTest[1864:3099093] client session: onLinkFailure: 5A342616-0ECA-48AE-829A-448F633DC8C8
,2016-03-20 12:47:03.672 ThaliTest[1864:3099093] client session: disconnect
,2016-03-20 12:47:03.672 ThaliTest[1864:3099093] client session: stateChange:1->0 5A342616-0ECA-48AE-829A-448F633DC8C8:9
,2016-03-20 12:47:03.675 ThaliTest[1864:3099093] client session: fireConnectCallback: 5A342616-0ECA-48AE-829A-448F633DC8C8
,2016-03-20 12:47:03.675 ThaliTest[1864:3099093] jxcore: connect: fail: Peer disconnected
,WARN createPeerListener: 
,DEBUG createPeerListener: failedConnection
,DEBUG createPeerListener: failed incoming connection because of mux promise failuePeer disconnected
,not ok 178 Error: socket hang up -2
,  ---
,    operator: fail
,  ...
,# setup
,2016-03-20 12:47:13.084 ThaliTest[1864:3097999] jxcore: stopAdvertisingAndListening
2016-03-20 12:47:13.084 ThaliTest[1864:3097999] THEMultipeerManager stopping peer
,2016-03-20 12:47:13.085 ThaliTest[1864:3097999] jxcore: stopAdvertisingAndListening: success
2016-03-20 12:47:13.086 ThaliTest[1864:3097999] jxcore: stopListeningForAdvertisements
2016-03-20 12:47:13.086 ThaliTest[1864:3097999] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-20 12:47:13.089 ThaliTest[1864:3097999] jxcore: stopListeningForAdvertisements: success
,# 48. Can do requests between peers after start and stop
,2016-03-20 12:47:13.234 ThaliTest[1864:3097999] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-20 12:47:13.235 ThaliTest[1864:3097999] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-20 12:47:13.236 ThaliTest[1864:3097999] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-20 12:47:13.239 ThaliTest[1864:3097999] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,ok 179 (unnamed assert)
,# setup
,# 49. We successfully receive and replay discoveryAdvertisingStateUpdate
,2016-03-20 12:47:14.254 ThaliTest[1864:3097999] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-20 12:47:14.256 ThaliTest[1864:3097999] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-20 12:47:14.257 ThaliTest[1864:3097999] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-20 12:47:14.259 ThaliTest[1864:3097999] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
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
,ok 226 should be equal
,# setup
,# 72. #parseBeacons addressBookCallback returns spurious match
,# teardown
,ok 227 should be equal
ok 228 should be equal
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
,ok 244 should be 200
ok 245 should be equal
,ok 246 should be equal
,ok 247 (unnamed assert)
,ok 248 no error
ok 249 should be 204
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
,ok 279 Size should be MAXSIZE
ok 280 Size should be MAXSIZE+6
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
ok 286 Size should be 100
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
ok 324 constructor called once
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
ok 337 verify failed
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
ok 345 constructor called once
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
ok 399 verify failed
,ok 400 constructor called once
,ok 401 constructor called with right args
,ok 402 (unnamed assert)
,# setup
,# 116. two different starts in a row
,# teardown
,DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
,ok 403 verify failed
,ok 404 constructor called once
,ok 405 constructor called with right args
,ok 406 (unnamed assert)
,ok 407 (unnamed assert)
,# setup
,# 117. two stops and a start and two stops
,# teardown
,DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
,ok 408 verify failed
ok 409 constructor called once
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
,DEBUG createNativeListener: listening 49417
,ok 421 port must be in range
,# setup
,# 123. starting twice resolves with listening port
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49418
,ok 422 second start should return same port
,# setup
,# 124. terminateIncomingConnection will terminate a connection
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49420
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
,DEBUG createNativeListener: listening 49422
,# setup
,# 126. terminate an Outgoing connection with wrong arguments is not harmful
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49423
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
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
