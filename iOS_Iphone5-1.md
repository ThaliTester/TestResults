#### Test 62548124ca582f4_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/62548124ca582f4/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/FA49BA26-2190-49DC-855C-CAA7CB6C3914/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/FA49BA26-2190-49DC-855C-CAA7CB6C3914/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/62548124ca582f4/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/62548124ca582f4/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/EA52830B-1F82-4052-849F-D6EB87D3C7E6/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52976"
,(lldb)     command script import "/tmp/FA49BA26-2190-49DC-855C-CAA7CB6C3914/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-19 11:43:38.603 ThaliTest[1348:3099792] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/76E06658-67FF-41CD-9F1D-54110ED3EFD4/Library/Cookies/Cookies.binarycookies
,2016-03-19 11:43:38.720 ThaliTest[1348:3099792] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-19 11:43:38.722 ThaliTest[1348:3099792] Multi-tasking -> Device: YES, App: YES
,2016-03-19 11:43:38.744 ThaliTest[1348:3099792] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-19 11:43:40.918 ThaliTest[1348:3099792] Using UIWebView
,2016-03-19 11:43:40.923 ThaliTest[1348:3099792] [CDVTimer][handleopenurl] 0.391960ms
,2016-03-19 11:43:40.928 ThaliTest[1348:3099792] [CDVTimer][intentandnavigationfilter] 5.383968ms
2016-03-19 11:43:40.929 ThaliTest[1348:3099792] [CDVTimer][gesturehandler] 0.285029ms
2016-03-19 11:43:40.929 ThaliTest[1348:3099792] [CDVTimer][TotalPluginS,tartup] 7.162988ms
,2016-03-19 11:43:49.553 ThaliTest[1348:3099792] Resetting plugins due to page load.
,2016-03-19 11:43:54.075 ThaliTest[1348:3099792] Finished load of: file:///var/mobile/Containers/Bundle/Application/EA52830B-1F82-4052-849F-D6EB87D3C7E6/ThaliTest.app/www/index.html
,2016-03-19 11:43:54.280 ThaliTest[1348:3099792] JXcore Cordova plugin initializing
,2016-03-19 11:43:54.282 ThaliTest[1348:3099972] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-19 11:44:11.017 ThaliTest[1348:3099972] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-19 11:44:11.018 ThaliTest[1348:3099972] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-19 11:44:11.018 ThaliTest[1348:3099972] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-19 11:44:11.021 ThaliTest[1348:3099972] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA52830B-1F82-4052-849F-D6EB87D3C7E6/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA52830B-1F82-4052-849F-D6EB87D3C7E6/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA52830B-1F82-4052-849F-D6EB87D3C7E6/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA52830B-1F82-4052-849F-D6EB87D3C7E6/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA52830B-1F82-4052-849F-D6EB87D3C7E6/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA52830B-1F82-4052-849F-D6EB87D3C7E6/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA52830B-1F82-4052-849F-D6EB87D3C7E6/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA52830B-1F82-4052-849F-D6EB87D3C7E6/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA52830B-1F82-4052-849F-D6EB87D3C7E6/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA52830B-1F82-4052-849F-D6EB87D3C7E6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA52830B-1F82-4052-849F-D6EB87D3C7E6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA52830B-1F82-4052-849F-D6EB87D3C7E6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA52830B-1F82-4052-849F-D6EB87D3C7E6/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA52830B-1F82-4052-849F-D6EB87D3C7E6/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA52830B-1F82-4052-849F-D6EB87D3C7E6/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA52830B-1F82-4052-849F-D6EB87D3C7E6/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA52830B-1F82-4052-849F-D6EB87D3C7E6/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA52830B-1F82-4052-849F-D6EB87D3C7E6/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA52830B-1F82-4052-849F-D6EB87D3C7E6/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA52830B-1F82-4052-849F-D6EB87D3C7E6/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-19 11:44:24.644 ThaliTest[1348:3099792] THREAD WARNING: ['JXcore'] took '12921.321045' ms. Plugin should use a background thread.
,2016-03-19 11:44:24.645 ThaliTest[1348:3099917] void SendDelegateMessage(NSInvocation *): delegate (webView:decidePolicyForNavigationAction:request:frame:decisionListener:) failed to return after waiting 10 seconds. main run loop mode: kCFRunLoopDefaultMode
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 64886
,ok 1 Should throw
,# setup
,# 2. emits incomingConnectionState
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 64888
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
,DEBUG createNativeListener: listening 64891
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
,DEBUG createNativeListener: listening 64895
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
,DEBUG createNativeListener: listening 64900
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
,DEBUG createNativeListener: listening 64904
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
,DEBUG createNativeListener: listening 64908
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
,DEBUG createNativeListener: listening 64912
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
,DEBUG createNativeListener: listening 64917
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
,DEBUG createNativeListener: listening 64969
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
,DEBUG createNativeListener: listening 64973
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
,DEBUG createNativeListener: listening 64985
,2016-03-19 11:47:58.267 ThaliTest[1348:3099972] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-19 11:47:58.268 ThaliTest[1348:3099972] jxcore: stopListeningForAdvertisements: success
,ok 82 error should be null
,ok 83 error should be null
,2016-03-19 11:47:58.272 ThaliTest[1348:3099972] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-19 11:47:58.274 ThaliTest[1348:3099972] jxcore: stopListeningForAdvertisements: success
,ok 84 error should be null
,ok 85 error should be null
,# setup
,2016-03-19 11:47:58.547 ThaliTest[1348:3099972] jxcore: stopAdvertisingAndListening
2016-03-19 11:47:58.548 ThaliTest[1348:3099972] THEMultipeerManager stopping peer
2016-03-19 11:47:58.548 ThaliTest[1348:3099972] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-19 11:47:58.548 ThaliTest[1348:3099972] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-19 11:47:58.549 ThaliTest[1348:3099972] jxcore: stopListeningForAdvertisements: success
,ok 86 error should be null
,ok 87 error should be null
,# 24. should be able to call #startListeningForAdvertisements many times
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 64987
,2016-03-19 11:47:58.945 ThaliTest[1348:3099972] jxcore: startListeningForAdvertisements
,2016-03-19 11:47:58.948 ThaliTest[1348:3099972] multipeer manager: start client restart timer: 0x1556de10
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-19 11:47:58.949 ThaliTest[1348:3099972] jxcore: startListeningForAdvertisements: success
,ok 88 error should be null
,ok 89 error should be null
,2016-03-19 11:47:58.998 ThaliTest[1348:3099972] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-19 11:47:59.000 ThaliTest[1348:3099972] jxcore: startListeningForAdvertisements: success
,ok 90 error should be null
,ok 91 error should be null
,# setup
,2016-03-19 11:47:59.352 ThaliTest[1348:3099972] jxcore: stopAdvertisingAndListening
2016-03-19 11:47:59.353 ThaliTest[1348:3099972] THEMultipeerManager stopping peer
2016-03-19 11:47:59.353 ThaliTest[1348:3099972] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-19 11:47:59.353 ThaliTest[1348:3099972] jxcore: stopListeningForAdvertisements
2016-03-19 11:47:59.353 ThaliTest[1348:3099972] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-19 11:47:59.355 ThaliTest[1348:3099972] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 92 error should be null
,ok 93 error should be null
,# 25. should be able to call #startUpdateAdvertisingAndListening many times
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 64989
,2016-03-19 11:47:59.872 ThaliTest[1348:3099972] jxcore: startUpdateAdvertisingAndListening
2016-03-19 11:47:59.872 ThaliTest[1348:3099972] server: starting BFF196CF-9326-4437-A343-829BABDB6CBC:1
2016-03-19 11:47:59.873 ThaliTest[1348:3099972] multipeer m,anager: start client restart timer: 0x1556de10
2016-03-19 11:47:59.873 ThaliTest[1348:3099972] THEMultipeerManager initialized peer BFF196CF-9326-4437-A343-829BABDB6CBC:1
2016-03-19 11:47:59.874 ThaliTest[1348:3099972] jxcore: startUpdateAdvertisingAndLi,stening: success
,ok 94 error should be null
,ok 95 error should be null
,2016-03-19 11:47:59.938 ThaliTest[1348:3099972] jxcore: startUpdateAdvertisingAndListening
2016-03-19 11:47:59.938 ThaliTest[1348:3099972] THEMultipeerManager stopping peer
2016-03-19 11:47:59.938 ThaliTest[1348:3099972] multipeer manager: stop client timer
2016-03-19 11:47:59.939 ThaliTest[1348:3099972] server: starting BFF196CF-9326-4437-A343-829BABDB6CBC:2
,2016-03-19 11:47:59.940 ThaliTest[1348:3099972] multipeer manager: start client restart timer: 0x1556de10
2016-03-19 11:47:59.941 ThaliTest[1348:3099972] THEMultipeerManager initialized peer BFF196CF-9326-4437-A343-829BABDB6CBC:2
,2016-03-19 11:47:59.941 ThaliTest[1348:3099972] jxcore: startUpdateAdvertisingAndListening: success
,ok 96 error should be null
ok 97 error should be null
,# setup
,2016-03-19 11:48:00.753 ThaliTest[1348:3099972] jxcore: stopAdvertisingAndListening
2016-03-19 11:48:00.754 ThaliTest[1348:3099972] THEMultipeerManager stopping peer
2016-03-19 11:48:00.754 ThaliTest[1348:3099972] multipeer manager: stop client timer
,2016-03-19 11:48:00.754 ThaliTest[1348:3099972] jxcore: stopAdvertisingAndListening: success
2016-03-19 11:48:00.755 ThaliTest[1348:3099972] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-19 11:48:00.756 ThaliTest[1348:3099972] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 98 error should be null
,ok 99 error should be null
,# 26. should be able to call #stopAdvertisingAndListening many times
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 64994
,2016-03-19 11:48:01.380 ThaliTest[1348:3099972] jxcore: stopAdvertisingAndListening
2016-03-19 11:48:01.380 ThaliTest[1348:3099972] THEMultipeerManager stopping peer
2016-03-19 11:48:01.380 ThaliTest[1348:3099972] jxcore: stopAdvertisingAndListening: success
,ok 100 error should be null
,ok 101 error should be null
,2016-03-19 11:48:01.384 ThaliTest[1348:3099972] jxcore: stopAdvertisingAndListening
2016-03-19 11:48:01.385 ThaliTest[1348:3099972] THEMultipeerManager stopping peer
2016-03-19 11:48:01.385 ThaliTest[1348:3099972] jxcore: stopAdvertisingAndListening: success
,ok 102 error should be null
ok 103 error should be null
,# setup
,2016-03-19 11:48:01.802 ThaliTest[1348:3099972] jxcore: stopAdvertisingAndListening
2016-03-19 11:48:01.802 ThaliTest[1348:3099972] THEMultipeerManager stopping peer
2016-03-19 11:48:01.802 ThaliTest[1348:3099972] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-19 11:48:01.803 ThaliTest[1348:3099972] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-19 11:48:01.804 ThaliTest[1348,:3099972] jxcore: stopListeningForAdvertisements: success
,ok 104 error should be null
,ok 105 error should be null
,# 27. #start should fail if called twice in a row
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 64996
,ok 106 first call should succeed
,ok 107 first call should succeed
,ok 108 specific error should be returned
,# setup
,2016-03-19 11:48:02.501 ThaliTest[1348:3099972] jxcore: stopAdvertisingAndListening
2016-03-19 11:48:02.501 ThaliTest[1348:3099972] THEMultipeerManager stopping peer
2016-03-19 11:48:02.501 ThaliTest[1348:3099972] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-19 11:48:02.502 ThaliTest[1348:3099972] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-19 11:48:02.503 ThaliTest[1348,:3099972] jxcore: stopListeningForAdvertisements: success
,ok 109 error should be null
,ok 110 error should be null
,# 28. does not emit duplicate discoveryAdvertisingStateUpdate
,# teardown
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 64998
,2016-03-19 11:48:02.962 ThaliTest[1348:3099972] jxcore: startListeningForAdvertisements
2016-03-19 11:48:02.962 ThaliTest[1348:3099972] multipeer manager: start client restart timer: 0x1556de10
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-19 11:48:02.964 ThaliTest[1348:3099972] jxcore: startListeningForAdvertisements: success
,2016-03-19 11:48:02.997 ThaliTest[1348:3099972] jxcore: startUpdateAdvertisingAndListening
2016-03-19 11:48:02.997 ThaliTest[1348:3099972] server: starting BFF196CF-9326-4437-A343-829BABDB6CBC:3
2016-03-19 11:48:02.998 ThaliTest[1348:3099972] THEMultipee,rManager initialized peer BFF196CF-9326-4437-A343-829BABDB6CBC:3
2016-03-19 11:48:02.998 ThaliTest[1348:3099972] jxcore: startUpdateAdvertisingAndListening: success
,ok 111 called only once
ok 112 discovery state matches
ok 113 advertising state matches
,# setup
,2016-03-19 11:48:03.307 ThaliTest[1348:3099972] jxcore: stopAdvertisingAndListening
2016-03-19 11:48:03.307 ThaliTest[1348:3099972] THEMultipeerManager stopping peer
2016-03-19 11:48:03.307 ThaliTest[1348:3099972] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-19 11:48:03.308 ThaliTest[1348:3099972] jxcore: stopListeningForAdvertisements
2016-03-19 11:48:03.308 ThaliTest[1348:3099972] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-19 11:48:03.309 ThaliTest[1348:3099972] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
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
,2016-03-19 11:48:08.539 ThaliTest[1348:3099972] jxcore: startListeningForAdvertisements
2016-03-19 11:48:08.540 ThaliTest[1348:3099972] multipeer manager: start client restart timer: 0x1556de10
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-19 11:48:08.541 ThaliTest[1348:3099972] jxcore: startListeningForAdvertisements: success
,ok 129 Can call startListeningForAdvertisements without error
,2016-03-19 11:48:08.543 ThaliTest[1348:3099972] jxcore: stopListeningForAdvertisements
2016-03-19 11:48:08.543 ThaliTest[1348:3099972] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-19 11:48:08.545 ThaliTest[1348:3099972] jxcore: stopListeningForAdvertisements: success
,ok 130 Can call stopListeningForAdvertisements without error
,# setup
,2016-03-19 11:48:08.690 ThaliTest[1348:3099972] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-19 11:48:08.691 ThaliTest[1348:3099972] jxcore: stopListeningForAdvertisements: success
,ok 131 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-19 11:48:08.693 ThaliTest[1348:3099972] jxcore: stopAdvertisingAndListening
2016-03-19 11:48:08.693 ThaliTest[1348:3099972] THEMultipeerManager stopping peer
2016-03-19 11:48:08.693 ThaliTest[1348:3099972] jxcore: stopAdvertisingAndListening: success
ok 132 Should be able to call stopAdvertisingAndListening in teardown
,# 33. Calling startListeningForAdvertisements twice is NOT an error
,# teardown
,2016-03-19 11:48:08.879 ThaliTest[1348:3099972] jxcore: startListeningForAdvertisements
2016-03-19 11:48:08.879 ThaliTest[1348:3099972] multipeer manager: start client restart timer: 0x1556de10
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-19 11:48:08.881 ThaliTest[1348:3099972] jxcore: startListeningForAdvertisements: success
,ok 133 Can call startListeningForAdvertisements without error
2016-03-19 11:48:08.882 ThaliTest[1348:3099972] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-19 11:48:08.884 ThaliTest[1348:3099972] jxcore: startListeningForAdvertisements: success
,ok 134 Can call startListeningForAdvertisements twice without error
# setup
,2016-03-19 11:48:09.266 ThaliTest[1348:3099972] jxcore: stopListeningForAdvertisements
2016-03-19 11:48:09.267 ThaliTest[1348:3099972] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisi,ngActive":false,"discoveryActive":false}
2016-03-19 11:48:09.268 ThaliTest[1348:3099972] jxcore: stopListeningForAdvertisements: success
,ok 135 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-19 11:48:09.270 ThaliTest[1348:3099972] jxcore: stopAdvertisingAndListening
2016-03-19 11:48:09.270 ThaliTest[1348:3099972] THEMultipeerManager stopping peer
,2016-03-19 11:48:09.270 ThaliTest[1348:3099972] jxcore: stopAdvertisingAndListening: success
ok 136 Should be able to call stopAdvertisingAndListening in teardown
# 34. Can call start/stopUpdateAdvertisingAndListening
,# teardown
,2016-03-19 11:48:09.757 ThaliTest[1348:3099972] jxcore: startUpdateAdvertisingAndListening
2016-03-19 11:48:09.757 ThaliTest[1348:3099972] server: starting BFF196CF-9326-4437-A343-829BABDB6CBC:4
2016-03-19 11:48:09.758 ThaliTest[1348:3099972] multipeer m,anager: start client restart timer: 0x1556de10
2016-03-19 11:48:09.758 ThaliTest[1348:3099972] THEMultipeerManager initialized peer BFF196CF-9326-4437-A343-829BABDB6CBC:4
2016-03-19 11:48:09.758 ThaliTest[1348:3099972] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 137 Can call startUpdateAdvertisingAndListening without error
2016-03-19 11:48:09.759 ThaliTest[1348:3099972] jxcore: stopAdvertisingAndListening
2016-03-19 11:48:09.760 ThaliTest[1348:3099972] THEMultipeerManager stopping peer
,2016-03-19 11:48:09.760 ThaliTest[1348:3099972] multipeer manager: stop client timer
2016-03-19 11:48:09.760 ThaliTest[1348:3099972] jxcore: stopAdvertisingAndListening: success
ok 138 Can call stopAdvertisingAndListening without error
# setup
,2016-03-19 11:48:10.119 ThaliTest[1348:3099972] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-19 11:48:10.120 ThaliTest[1348:3099972] jxcore: stopListeningForAdvertisements: success
,ok 139 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-19 11:48:10.122 ThaliTest[1348:3099972] jxcore: stopAdvertisingAndListening
2016-03-19 11:48:10.122 ThaliTest[1348:3099972] THEMultipeerManager stopping peer
2016-03-19 11:48:10.123 ThaliTest[1348:3099972] jxcore: stopAdvertisingAndListening: success
ok 140 Should be able to call stopAdvertisingAndListening in teardown
,# 35. Calling startUpdateAdvertisingAndListening twice is NOT an error
,# teardown
,2016-03-19 11:48:10.637 ThaliTest[1348:3099972] jxcore: startUpdateAdvertisingAndListening
2016-03-19 11:48:10.637 ThaliTest[1348:3099972] server: starting BFF196CF-9326-4437-A343-829BABDB6CBC:5
2016-03-19 11:48:10.637 ThaliTest[1348:3099972] multipeer m,anager: start client restart timer: 0x1556de10
2016-03-19 11:48:10.638 ThaliTest[1348:3099972] THEMultipeerManager initialized peer BFF196CF-9326-4437-A343-829BABDB6CBC:5
2016-03-19 11:48:10.638 ThaliTest[1348:3099972] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 141 Can call startUpdateAdvertisingAndListening without error
,2016-03-19 11:48:10.639 ThaliTest[1348:3099972] jxcore: startUpdateAdvertisingAndListening
2016-03-19 11:48:10.639 ThaliTest[1348:3099972] THEMultipeerManager stopping peer
2016-03-19 11:48:10.640 ThaliTest[1348:3099972] multipeer manager: stop client timer
,2016-03-19 11:48:10.640 ThaliTest[1348:3099972] server: starting BFF196CF-9326-4437-A343-829BABDB6CBC:6
2016-03-19 11:48:10.641 ThaliTest[1348:3099972] multipeer manager: start client restart timer: 0x1556de10
2016-03-19 11:48:10.642 ThaliTest[1348:30999,72] THEMultipeerManager initialized peer BFF196CF-9326-4437-A343-829BABDB6CBC:6
2016-03-19 11:48:10.642 ThaliTest[1348:3099972] jxcore: startUpdateAdvertisingAndListening: success
,ok 142 Can call startUpdateAdvertisingAndListening twice without error
# setup
,2016-03-19 11:48:10.769 ThaliTest[1348:3099972] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-19 11:48:10.770 ThaliTest[1348:3099972] jxcore: stopListeningForAdvertisements: success
,ok 143 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-19 11:48:10.772 ThaliTest[1348:3099972] jxcore: stopAdvertisingAndListening
2016-03-19 11:48:10.772 ThaliTest[1348:3099972] THEMultipeerManager stopping peer
2016-03-19 11:48:10.772 ThaliTest[1348:3099972] multipeer manager: stop client timer
2016-03-19 11:48:10.773 ThaliTest[1348:3099972] jxcore: stopAdvertisingAndListening: success
ok 144 Should be able to call stopAdvertisingAndListening in teardown
,# 36. peerAvailabilityChange is called
,# teardown
,2016-03-19 11:48:11.172 ThaliTest[1348:3099972] jxcore: startUpdateAdvertisingAndListening
2016-03-19 11:48:11.173 ThaliTest[1348:3099972] server: starting BFF196CF-9326-4437-A343-829BABDB6CBC:7
2016-03-19 11:48:11.173 ThaliTest[1348:3099972] multipeer m,anager: start client restart timer: 0x1556de10
2016-03-19 11:48:11.173 ThaliTest[1348:3099972] THEMultipeerManager initialized peer BFF196CF-9326-4437-A343-829BABDB6CBC:7
2016-03-19 11:48:11.173 ThaliTest[1348:3099972] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 145 Can call startUpdateAdvertisingAndListeningwithout error
2016-03-19 11:48:11.175 ThaliTest[1348:3099972] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertising,Active":true,"discoveryActive":true}
2016-03-19 11:48:11.176 ThaliTest[1348:3099972] jxcore: startListeningForAdvertisements: success
,ok 146 Can call startListeningForAdvertisements without error
,2016-03-19 11:48:12.534 ThaliTest[1348:3099792] client: found new peer: F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:7
ok 147 peers must be an array
ok 148 peers must not be zero-length
ok 149 peer must have peerIdentifier
ok 150 peerIdentifier must be a string
,ok 151 peer must have peerAvailable
,ok 152 peer must have pleaseConnect
,# setup
,2016-03-19 11:48:12.798 ThaliTest[1348:3099972] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-19 11:48:12.800 ThaliTest[1348:3099972] jxcore: stopListeningForAdvertisements: success
,ok 153 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-19 11:48:12.801 ThaliTest[1348:3099972] jxcore: stopAdvertisingAndListening
2016-03-19 11:48:12.802 ThaliTest[1348:3099972] THEMultipeerManager stopping peer
2016-03-19 11:48:12.802 ThaliTest[1348:3099972] multipeer manager: stop client timer
20,16-03-19 11:48:12.802 ThaliTest[1348:3099972] jxcore: stopAdvertisingAndListening: success
ok 154 Should be able to call stopAdvertisingAndListening in teardown
,# 37. Can connect to a remote peer
,# teardown
,2016-03-19 11:48:13.265 ThaliTest[1348:3099972] jxcore: startUpdateAdvertisingAndListening
2016-03-19 11:48:13.266 ThaliTest[1348:3099972] server: starting BFF196CF-9326-4437-A343-829BABDB6CBC:8
2016-03-19 11:48:13.266 ThaliTest[1348:3099972] multipeer m,anager: start client restart timer: 0x1556de10
2016-03-19 11:48:13.266 ThaliTest[1348:3099972] THEMultipeerManager initialized peer BFF196CF-9326-4437-A343-829BABDB6CBC:8
2016-03-19 11:48:13.267 ThaliTest[1348:3099972] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 155 Can call startUpdateAdvertisingAndListening without error
2016-03-19 11:48:13.268 ThaliTest[1348:3099972] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-19 11:48:13.271 ThaliTest[1348:3099972] jxcore: startListeningForAdvertisements: success
,ok 156 Can call startListeningForAdvertisements without error
,2016-03-19 11:48:15.710 ThaliTest[1348:3099792] client: found new peer: F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"F6111CA1-FBE0-4E62-AA40-FA3A5F578,2C5:7","pleaseConnect":0}]
,2016-03-19 11:48:15.714 ThaliTest[1348:3099972] jxcore: connect F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:7
,2016-03-19 11:48:15.714 ThaliTest[1348:3099972] client: server will connect
,2016-03-19 11:48:15.716 ThaliTest[1348:3099972] client session: reverseConnect
2016-03-19 11:48:15.716 ThaliTest[1348:3099972] client session: stateChange:0->1 F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:7
,2016-03-19 11:48:15.793 ThaliTest[1348:3099792] multipeer session: reset timer
2016-03-19 11:48:15.794 ThaliTest[1348:3099792] server: rejecting invitation from F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5 due to previous generation (BFF196CF-9326-4437-A343-829BA,BDB6CBC:8 != BFF196CF-9326-4437-A343-829BABDB6CBC:7)
,2016-03-19 11:48:15.973 ThaliTest[1348:3101089] client session: not connected F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:7
2016-03-19 11:48:15.974 ThaliTest[1348:3101089] client session: onLinkFailure: F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5
2016-03-19 11:48:15.974 ThaliTest[1348:3101089] client session: disconnect
2016-03-19 11:48:15.974 ThaliTest[1348:3101089] client session: stateChange:1->0 F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:7
,2016-03-19 11:48:15.975 ThaliTest[1348:3101089] client session: no connect callback (server initiated)
,2016-03-19 11:48:18.960 ThaliTest[1348:3099792] multipeer session: reset timer
2016-03-19 11:48:18.960 ThaliTest[1348:3099792] server: disconnecting to refresh session (F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5)
2016-03-19 11:48:18.961 ThaliTest[1348:3099792] server: rejecting invitation from F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5 due to previous generation (BFF196CF-9326-4437-A343-829BABDB6CBC:8 != BFF196CF-9326-4437-A343-829BABDB6CBC:7)
,2016-03-19 11:48:22.107 ThaliTest[1348:3099792] multipeer session: reset timer
2016-03-19 11:48:22.107 ThaliTest[1348:3099792] server: disconnecting to refresh session (F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5)
2016-03-19 11:48:22.107 ThaliTest[1348:3099792], server: rejecting invitation from F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5 due to previous generation (BFF196CF-9326-4437-A343-829BABDB6CBC:8 != BFF196CF-9326-4437-A343-829BABDB6CBC:7)
,2016-03-19 11:48:25.250 ThaliTest[1348:3099792] multipeer session: reset timer
2016-03-19 11:48:25.251 ThaliTest[1348:3099792] server: disconnecting to refresh session (F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5)
2016-03-19 11:48:25.251 ThaliTest[1348:3099792] server: rejecting invitation from F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5 due to previous generation (BFF196CF-9326-4437-A343-829BABDB6CBC:8 != BFF196CF-9326-4437-A343-829BABDB6CBC:7)
,2016-03-19 11:48:25.716 ThaliTest[1348:3099792] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-19 11:48:28.357 ThaliTest[1348:3099792] multipeer session: reset timer
2016-03-19 11:48:28.357 ThaliTest[1348:3099792] server: disconnecting to refresh session (F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5)
2016-03-19 11:48:28.358 ThaliTest[1348:3099792], server: rejecting invitation from F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5 due to previous generation (BFF196CF-9326-4437-A343-829BABDB6CBC:8 != BFF196CF-9326-4437-A343-829BABDB6CBC:7)
,2016-03-19 11:48:28.724 ThaliTest[1348:3099972] jxcore: connect F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:7
2016-03-19 11:48:28.724 ThaliTest[1348:3099972] client: server will connect
2016-03-19 11:48:28.725 ThaliTest[1348:3099972] client session: reverseConnect
2016-03-19 11:48:28.725 ThaliTest[1348:3099972] client session: stateChange:0->1 F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:7
,2016-03-19 11:48:28.863 ThaliTest[1348:3101123] client session: not connected F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:7
2016-03-19 11:48:28.863 ThaliTest[1348:3101123] client session: onLinkFailure: F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5
2016-03-19 11:48:28.8,64 ThaliTest[1348:3101123] client session: disconnect
2016-03-19 11:48:28.864 ThaliTest[1348:3101123] client session: stateChange:1->0 F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:7
2016-03-19 11:48:28.864 ThaliTest[1348:3101123] client session: no connect callb,ack (server initiated)
,2016-03-19 11:48:31.476 ThaliTest[1348:3099792] multipeer session: reset timer
,2016-03-19 11:48:31.477 ThaliTest[1348:3099792] server: disconnecting to refresh session (F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5)
2016-03-19 11:48:31.477 ThaliTest[1348:3099792] server: rejecting invitation from F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5 due to previous generation (BFF196CF-9326-4437-A343-829BABDB6CBC:8 != BFF196CF-9326-4437-A343-829BABDB6CBC:7)
,2016-03-19 11:48:33.267 ThaliTest[1348:3099792] multipeer manager: restart client
,2016-03-19 11:48:33.281 ThaliTest[1348:3099792] client: found updated peer: F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:8","pleaseConnect":0}]
,2016-03-19 11:48:34.711 ThaliTest[1348:3099792] multipeer session: reset timer
2016-03-19 11:48:34.711 ThaliTest[1348:3099792] server: disconnecting to refresh session (F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5)
2016-03-19 11:48:34.712 ThaliTest[1348:3099792], server: rejecting invitation from F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5 due to previous generation (BFF196CF-9326-4437-A343-829BABDB6CBC:8 != BFF196CF-9326-4437-A343-829BABDB6CBC:7)
,2016-03-19 11:48:38.290 ThaliTest[1348:3099792] multipeer session: reset timer
2016-03-19 11:48:38.290 ThaliTest[1348:3099792] server: disconnecting to refresh session (F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5)
2016-03-19 11:48:38.290 ThaliTest[1348:3099792], server: rejecting invitation from F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5 due to previous generation (BFF196CF-9326-4437-A343-829BABDB6CBC:8 != BFF196CF-9326-4437-A343-829BABDB6CBC:7)
,2016-03-19 11:48:38.726 ThaliTest[1348:3099792] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-19 11:48:41.488 ThaliTest[1348:3099792] multipeer session: reset timer
2016-03-19 11:48:41.488 ThaliTest[1348:3099792] server: disconnecting to refresh session (F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5)
2016-03-19 11:48:41.489 ThaliTest[1348:3099792], server: rejecting invitation from F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5 due to previous generation (BFF196CF-9326-4437-A343-829BABDB6CBC:8 != BFF196CF-9326-4437-A343-829BABDB6CBC:7)
,2016-03-19 11:48:41.731 ThaliTest[1348:3099972] jxcore: connect F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:7
2016-03-19 11:48:41.731 ThaliTest[1348:3099972] client: server will connect
2016-03-19 11:48:41.732 ThaliTest[1348:3099972] client session: reverseConnect
2016-03-19 11:48:41.732 ThaliTest[1348:3099972] client session: stateChange:0->1 F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:8
,2016-03-19 11:48:41.832 ThaliTest[1348:3101080] client session: not connected F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:8
,2016-03-19 11:48:41.834 ThaliTest[1348:3101080] client session: onLinkFailure: F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5
,2016-03-19 11:48:41.834 ThaliTest[1348:3101080] client session: disconnect
,2016-03-19 11:48:41.834 ThaliTest[1348:3101080] client session: stateChange:1->0 F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:8
,2016-03-19 11:48:41.835 ThaliTest[1348:3101080] client session: no connect callback (server initiated)
,2016-03-19 11:48:44.643 ThaliTest[1348:3099792] multipeer session: reset timer
2016-03-19 11:48:44.643 ThaliTest[1348:3099792] server: disconnecting to refresh session (F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5)
2016-03-19 11:48:44.643 ThaliTest[1348:3099792] server: rejecting invitation from F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5 due to previous generation (BFF196CF-9326-4437-A343-829BABDB6CBC:8 != BFF196CF-9326-4437-A343-829BABDB6CBC:7)
,2016-03-19 11:48:51.732 ThaliTest[1348:3099792] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-19 11:48:53.268 ThaliTest[1348:3099792] multipeer manager: restart client
,2016-03-19 11:48:54.748 ThaliTest[1348:3099972] jxcore: connect F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:7
2016-03-19 11:48:54.749 ThaliTest[1348:3099972] client: server will connect
2016-03-19 11:48:54.750 ThaliTest[1348:3099972] client session: reverseConn,ect
2016-03-19 11:48:54.751 ThaliTest[1348:3099972] client session: stateChange:0->1 F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:8
,2016-03-19 11:48:54.758 ThaliTest[1348:3099792] client: lost peer: F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5
2016-03-19 11:48:54.758 ThaliTest[1348:3099792] client session: onPeerLost: F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5
2016-03-19 11:48:54.759 ThaliTest[134,8:3099792] client session: onLinkFailure: F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5
2016-03-19 11:48:54.759 ThaliTest[1348:3099792] client session: disconnect
2016-03-19 11:48:54.759 ThaliTest[1348:3099792] client session: stateChange:1->0 F6111CA1-FBE0-4E62-,AA40-FA3A5F5782C5:8
2016-03-19 11:48:54.759 ThaliTest[1348:3099792] client session: no connect callback (server initiated)
,2016-03-19 11:49:04.751 ThaliTest[1348:3099792] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-19 11:49:07.759 ThaliTest[1348:3099972] jxcore: connect F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:7
2016-03-19 11:49:07.760 ThaliTest[1348:3099972] client: connect: unreachable F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5
2016-03-19 11:49:07.760 ThaliTest[1348:3099972] jxcore: connect: fail: Peer unreachable
INFO testThaliMobileNative: Connect returned an error: Peer unreachable
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-19 11:49:10.779 ThaliTest[1348:3099972] jxcore: connect F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:7
2016-03-19 11:49:10.779 ThaliTest[1348:3099972] client: connect: unreachable F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5
2016-03-19 11:49:10.780 ThaliTest[134,8:3099972] jxcore: connect: fail: Peer unreachable
INFO testThaliMobileNative: Connect returned an error: Peer unreachable
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-19 11:49:13.267 ThaliTest[1348:3099792] multipeer manager: restart client
,2016-03-19 11:49:13.275 ThaliTest[1348:3099792] client: found existing peer: F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:8","pleaseConnect":0}]
,2016-03-19 11:49:13.798 ThaliTest[1348:3099972] jxcore: connect F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:7
2016-03-19 11:49:13.799 ThaliTest[1348:3099972] client: server will connect
2016-03-19 11:49:13.800 ThaliTest[1348:3099972] client session: reverseConnect
2016-03-19 11:49:13.800 ThaliTest[1348:3099972] client session: stateChange:0->1 F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:8
,2016-03-19 11:49:14.268 ThaliTest[1348:3101304] client session: not connected F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:8
2016-03-19 11:49:14.268 ThaliTest[1348:3101304] client session: onLinkFailure: F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5
2016-03-19 11:49:14.2,68 ThaliTest[1348:3101304] client session: disconnect
2016-03-19 11:49:14.268 ThaliTest[1348:3101304] client session: stateChange:1->0 F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:8
2016-03-19 11:49:14.269 ThaliTest[1348:3101304] client session: no connect callback (server initiated)
,2016-03-19 11:49:23.800 ThaliTest[1348:3099792] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-19 11:49:26.806 ThaliTest[1348:3099972] jxcore: connect F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:7
2016-03-19 11:49:26.806 ThaliTest[1348:3099972] client: server will connect
2016-03-19 11:49:26.807 ThaliTest[1348:3099972] client session: reverseConnect
2016-03-19 11:49:26.807 ThaliTest[1348:3099972] client session: stateChange:0->1 F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:8
,2016-03-19 11:49:27.225 ThaliTest[1348:3101337] client session: not connected F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:8
2016-03-19 11:49:27.225 ThaliTest[1348:3101337] client session: onLinkFailure: F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5
2016-03-19 11:49:27.2,25 ThaliTest[1348:3101337] client session: disconnect
2016-03-19 11:49:27.226 ThaliTest[1348:3101337] client session: stateChange:1->0 F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:8
,2016-03-19 11:49:27.228 ThaliTest[1348:3101337] client session: no connect callback (server initiated)
,2016-03-19 11:49:33.267 ThaliTest[1348:3099792] multipeer manager: restart client
,2016-03-19 11:49:33.277 ThaliTest[1348:3099792] client: found existing peer: F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:8
,2016-03-19 11:49:36.808 ThaliTest[1348:3099792] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-19 11:49:39.821 ThaliTest[1348:3099972] jxcore: connect F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:7
2016-03-19 11:49:39.822 ThaliTest[1348:3099972] client: server will connect
2016-03-19 11:49:39.822 ThaliTest[1348:3099972] client session: reverseConn,ect
2016-03-19 11:49:39.823 ThaliTest[1348:3099972] client session: stateChange:0->1 F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:8
,2016-03-19 11:49:40.276 ThaliTest[1348:3101363] client session: not connected F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:8
2016-03-19 11:49:40.276 ThaliTest[1348:3101363] client session: onLinkFailure: F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5
,2016-03-19 11:49:40.277 ThaliTest[1348:3101363] client session: disconnect
,2016-03-19 11:49:40.277 ThaliTest[1348:3101363] client session: stateChange:1->0 F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:8
2016-03-19 11:49:40.278 ThaliTest[1348:3101363] client session: no connect callback (server initiated)
,2016-03-19 11:49:49.823 ThaliTest[1348:3099792] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-19 11:49:52.838 ThaliTest[1348:3099972] jxcore: connect F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:7
2016-03-19 11:49:52.839 ThaliTest[1348:3099972] client: server will connect
2016-03-19 11:49:52.839 ThaliTest[1348:3099972] client session: reverseConnect
2016-03-19 11:49:52.840 ThaliTest[1348:3099972] client session: stateChange:0->1 F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:8
,2016-03-19 11:49:53.267 ThaliTest[1348:3099792] multipeer manager: restart client
,2016-03-19 11:50:02.841 ThaliTest[1348:3099792] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,WARN testThaliMobileNative: Too many connect retries!
,not ok 157 Connect failed!
,  ---
,    operator: fail
,  ...
,# setup
,2016-03-19 11:50:03.976 ThaliTest[1348:3099972] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-19 11:50:03.977 ThaliTest[1348:3099972] jxcore: stopListeningForAdvertisements: success
,ok 158 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-19 11:50:03.978 ThaliTest[1348:3099972] jxcore: stopAdvertisingAndListening
2016-03-19 11:50:03.979 ThaliTest[1348:3099972] THEMultipeerManager stopping peer
2016-03-19 11:50:03.979 ThaliTest[1348:3099972] client session: disconnect
2016-03-19 1,1:50:03.980 ThaliTest[1348:3099972] client session: stateChange:1->0 F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:8
2016-03-19 11:50:03.980 ThaliTest[1348:3099972] multipeer manager: stop client timer
2016-03-19 11:50:03.981 ThaliTest[1348:3099972] jxcore: stopAdvertisingAndListening: success
,ok 159 Should be able to call stopAdvertisingAndListening in teardown
# 38. Can shift large amounts of data
,# teardown
,2016-03-19 11:50:04.732 ThaliTest[1348:3099972] jxcore: startUpdateAdvertisingAndListening
2016-03-19 11:50:04.732 ThaliTest[1348:3099972] server: starting BFF196CF-9326-4437-A343-829BABDB6CBC:9
2016-03-19 11:50:04.733 ThaliTest[1348:3099972] multipeer m,anager: start client restart timer: 0x1556de10
2016-03-19 11:50:04.733 ThaliTest[1348:3099972] THEMultipeerManager initialized peer BFF196CF-9326-4437-A343-829BABDB6CBC:9
2016-03-19 11:50:04.733 ThaliTest[1348:3099972] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 160 Can call startUpdateAdvertisingAndListening without error
2016-03-19 11:50:04.735 ThaliTest[1348:3099972] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisin,gActive":true,"discoveryActive":true}
2016-03-19 11:50:04.736 ThaliTest[1348:3099972] jxcore: startListeningForAdvertisements: success
ok 161 Can call startListeningForAdvertisements without error
,2016-03-19 11:50:05.104 ThaliTest[1348:3099792] client: found new peer: F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:8
2016-03-19 11:50:05.105 ThaliTest[1348:3099972] jxcore: connect F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:8
2016-03-19 11:50:05.105 ThaliTest[1348:3,099972] client: server will connect
2016-03-19 11:50:05.106 ThaliTest[1348:3099972] client session: reverseConnect
2016-03-19 11:50:05.106 ThaliTest[1348:3099972] client session: stateChange:0->1 F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:8
,2016-03-19 11:50:05.767 ThaliTest[1348:3101363] client session: not connected F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:8
2016-03-19 11:50:05.767 ThaliTest[1348:3101363] client session: onLinkFailure: F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5
2016-03-19 11:50:05.7,67 ThaliTest[1348:3101363] client session: disconnect
2016-03-19 11:50:05.767 ThaliTest[1348:3101363] client session: stateChange:1->0 F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:8
2016-03-19 11:50:05.768 ThaliTest[1348:3101363] client session: no connect callback (server initiated)
,2016-03-19 11:50:06.149 ThaliTest[1348:3099792] multipeer session: reset timer
2016-03-19 11:50:06.150 ThaliTest[1348:3099792] server: rejecting invitation from F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5 due to previous generation (BFF196CF-9326-4437-A343-829BA,BDB6CBC:9 != BFF196CF-9326-4437-A343-829BABDB6CBC:8)
,2016-03-19 11:50:09.501 ThaliTest[1348:3099792] multipeer session: reset timer
2016-03-19 11:50:09.502 ThaliTest[1348:3099792] server: disconnecting to refresh session (F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5)
2016-03-19 11:50:09.502 ThaliTest[1348:3099792], server: rejecting invitation from F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5 due to previous generation (BFF196CF-9326-4437-A343-829BABDB6CBC:9 != BFF196CF-9326-4437-A343-829BABDB6CBC:8)
,2016-03-19 11:50:13.163 ThaliTest[1348:3099792] multipeer session: reset timer
2016-03-19 11:50:13.164 ThaliTest[1348:3099792] server: disconnecting to refresh session (F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5)
2016-03-19 11:50:13.164 ThaliTest[1348:3099792] server: rejecting invitation from F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5 due to previous generation (BFF196CF-9326-4437-A343-829BABDB6CBC:9 != BFF196CF-9326-4437-A343-829BABDB6CBC:8)
,2016-03-19 11:50:15.107 ThaliTest[1348:3099792] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-19 11:50:16.824 ThaliTest[1348:3099792] multipeer session: reset timer
2016-03-19 11:50:16.824 ThaliTest[1348:3099792] server: disconnecting to refresh session (F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5)
2016-03-19 11:50:16.824 ThaliTest[1348:3099792], server: rejecting invitation from F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5 due to previous generation (BFF196CF-9326-4437-A343-829BABDB6CBC:9 != BFF196CF-9326-4437-A343-829BABDB6CBC:8)
,2016-03-19 11:50:18.120 ThaliTest[1348:3099972] jxcore: connect F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:8
2016-03-19 11:50:18.120 ThaliTest[1348:3099972] client: server will connect
2016-03-19 11:50:18.121 ThaliTest[1348:3099972] client session: reverseConnect
2016-03-19 11:50:18.121 ThaliTest[1348:3099972] client session: stateChange:0->1 F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:8
,2016-03-19 11:50:18.233 ThaliTest[1348:3101389] client session: not connected F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:8
2016-03-19 11:50:18.234 ThaliTest[1348:3101389] client session: onLinkFailure: F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5
2016-03-19 11:50:18.2,34 ThaliTest[1348:3101389] client session: disconnect
2016-03-19 11:50:18.234 ThaliTest[1348:3101389] client session: stateChange:1->0 F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:8
,2016-03-19 11:50:18.236 ThaliTest[1348:3101389] client session: no connect callback (server initiated)
,2016-03-19 11:50:20.458 ThaliTest[1348:3099792] multipeer session: reset timer
2016-03-19 11:50:20.459 ThaliTest[1348:3099792] server: disconnecting to refresh session (F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5)
2016-03-19 11:50:20.459 ThaliTest[1348:3099792], server: rejecting invitation from F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5 due to previous generation (BFF196CF-9326-4437-A343-829BABDB6CBC:9 != BFF196CF-9326-4437-A343-829BABDB6CBC:8)
,2016-03-19 11:50:24.230 ThaliTest[1348:3099792] multipeer session: reset timer
2016-03-19 11:50:24.236 ThaliTest[1348:3099792] server: disconnecting to refresh session (F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5)
2016-03-19 11:50:24.236 ThaliTest[1348:3099792] server: rejecting invitation from F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5 due to previous generation (BFF196CF-9326-4437-A343-829BABDB6CBC:9 != BFF196CF-9326-4437-A343-829BABDB6CBC:8)
,2016-03-19 11:50:24.734 ThaliTest[1348:3099792] multipeer manager: restart client
,2016-03-19 11:50:24.744 ThaliTest[1348:3099792] client: found updated peer: F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:9
,2016-03-19 11:50:28.122 ThaliTest[1348:3099792] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-19 11:50:31.130 ThaliTest[1348:3099972] jxcore: connect F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:8
2016-03-19 11:50:31.130 ThaliTest[1348:3099972] client: server will connect
2016-03-19 11:50:31.131 ThaliTest[1348:3099972] client session: reverseConn,ect
2016-03-19 11:50:31.131 ThaliTest[1348:3099972] client session: stateChange:0->1 F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:9
,2016-03-19 11:50:32.410 ThaliTest[1348:3101363] client session: not connected F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:9
,2016-03-19 11:50:32.412 ThaliTest[1348:3101363] client session: onLinkFailure: F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5
2016-03-19 11:50:32.412 ThaliTest[1348:3101363] client session: disconnect
2016-03-19 11:50:32.412 ThaliTest[1348:3101363] client session:, stateChange:1->0 F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:9
2016-03-19 11:50:32.412 ThaliTest[1348:3101363] client session: no connect callback (server initiated)
,2016-03-19 11:50:41.132 ThaliTest[1348:3099792] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-19 11:50:44.149 ThaliTest[1348:3099972] jxcore: connect F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:8
2016-03-19 11:50:44.149 ThaliTest[1348:3099972] client: server will connect
2016-03-19 11:50:44.150 ThaliTest[1348:3099972] client session: reverseConn,ect
2016-03-19 11:50:44.151 ThaliTest[1348:3099972] client session: stateChange:0->1 F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:9
,2016-03-19 11:50:44.733 ThaliTest[1348:3099792] multipeer manager: restart client
,2016-03-19 11:50:44.744 ThaliTest[1348:3099792] client: found existing peer: F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:9
,2016-03-19 11:50:54.151 ThaliTest[1348:3099792] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-19 11:50:57.161 ThaliTest[1348:3099972] jxcore: connect F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:8
2016-03-19 11:50:57.161 ThaliTest[1348:3099972] client: already connect(ing/ed) to F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:8
2016-03-19 11:50:57.162 ThaliTest[1348:3099972] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-19 11:51:00.170 ThaliTest[1348:3099972] jxcore: connect F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:8
2016-03-19 11:51:00.170 ThaliTest[1348:3099972] client: already connect(ing/ed) to F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:8
2016-03-19 11:51:00.171 Thali,Test[1348:3099972] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-19 11:51:03.190 ThaliTest[1348:3099972] jxcore: connect F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:8
2016-03-19 11:51:03.191 ThaliTest[1348:3099972] client: already connect(ing/ed) to F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:8
2016-03-19 11:51:03.191 Thali,Test[1348:3099972] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-19 11:51:03.556 ThaliTest[1348:3099792] multipeer session: reset timer
2016-03-19 11:51:03.556 ThaliTest[1348:3099792] server: disconnecting to refresh session (F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5)
2016-03-19 11:51:03.556 ThaliTest[1348:3099792], server: rejecting invitation from F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5 due to previous generation (BFF196CF-9326-4437-A343-829BABDB6CBC:9 != BFF196CF-9326-4437-A343-829BABDB6CBC:8)
,2016-03-19 11:51:04.734 ThaliTest[1348:3099792] multipeer manager: restart client
,2016-03-19 11:51:04.744 ThaliTest[1348:3099792] client: found existing peer: F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:9
,2016-03-19 11:51:06.202 ThaliTest[1348:3099972] jxcore: connect F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:8
2016-03-19 11:51:06.203 ThaliTest[1348:3099972] client: already connect(ing/ed) to F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:8
2016-03-19 11:51:06.203 ThaliTest[1348:3099972] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-19 11:51:06.827 ThaliTest[1348:3099792] multipeer session: reset timer
2016-03-19 11:51:06.827 ThaliTest[1348:3099792] server: disconnecting to refresh session (F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5)
2016-03-19 11:51:06.828 ThaliTest[1348:3099792], server: rejecting invitation from F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5 due to previous generation (BFF196CF-9326-4437-A343-829BABDB6CBC:9 != BFF196CF-9326-4437-A343-829BABDB6CBC:8)
,2016-03-19 11:51:09.219 ThaliTest[1348:3099972] jxcore: connect F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:8
2016-03-19 11:51:09.220 ThaliTest[1348:3099972] client: already connect(ing/ed) to F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:8
2016-03-19 11:51:09.220 Thali,Test[1348:3099972] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-19 11:51:10.262 ThaliTest[1348:3099792] multipeer session: reset timer
2016-03-19 11:51:10.262 ThaliTest[1348:3099792] server: disconnecting to refresh session (F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5)
2016-03-19 11:51:10.263 ThaliTest[1348:3099792], server: rejecting invitation from F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5 due to previous generation (BFF196CF-9326-4437-A343-829BABDB6CBC:9 != BFF196CF-9326-4437-A343-829BABDB6CBC:8)
,2016-03-19 11:51:12.239 ThaliTest[1348:3099972] jxcore: connect F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:8
2016-03-19 11:51:12.240 ThaliTest[1348:3099972] client: already connect(ing/ed) to F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:8
2016-03-19 11:51:12.240 ThaliTest[1348:3099972] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,WARN testThaliMobileNative: Too many connect retries!
,not ok 162 Connect failed!
  ---
,    operator: fail
,  ...
,# setup
,2016-03-19 11:51:12.550 ThaliTest[1348:3099972] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-19 11:51:12.551 ThaliTest[1348:3099972] jxcore: stopListeningForAdvertisements: success
,ok 163 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-19 11:51:12.553 ThaliTest[1348:3099972] jxcore: stopAdvertisingAndListening
2016-03-19 11:51:12.553 ThaliTest[1348:3099972] THEMultipeerManager stopping peer
2016-03-19 11:51:12.553 ThaliTest[1348:3099972] client session: disconnect
2016-03-19 1,1:51:12.554 ThaliTest[1348:3099972] client session: stateChange:1->0 F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:9
2016-03-19 11:51:12.554 ThaliTest[1348:3099972] multipeer manager: stop client timer
2016-03-19 11:51:12.554 ThaliTest[1348:3099972] jxcore: stopAdvertisingAndListening: success
,ok 164 Should be able to call stopAdvertisingAndListening in teardown
# 39. #startListeningForAdvertisements should fail if start not called
,2016-03-19 11:51:13.068 ThaliTest[1348:3099972] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-19 11:51:13.069 ThaliTest[1348:3099972] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-19 11:51:13.069 ThaliTest[1348:3,099972] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-19 11:51:13.071 ThaliTest[1348:3099972] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,ok 165 specific error should be returned
,# setup
,# 40. #startUpdateAdvertisingAndListening should fail if start not called
,2016-03-19 11:51:14.181 ThaliTest[1348:3099972] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-19 11:51:14.181 ThaliTest[1348:3099972] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-19 11:51:14.181 ThaliTest[1348:3,099972] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-19 11:51:14.183 ThaliTest[1348:3099972] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,ok 166 specific error should be returned
,# setup
,# 41. should be able to call #stopListeningForAdvertisements many times
,2016-03-19 11:51:15.175 ThaliTest[1348:3099972] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-19 11:51:15.175 ThaliTest[1348:3099972] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-19 11:51:15.176 ThaliTest[1348:3099972] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-19 11:51:15.178 ThaliTest[1348:3099972] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65029
,2016-03-19 11:51:15.320 ThaliTest[1348:3099972] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-19 11:51:15.322 ThaliTest[1348:3099972] jxcore: stopListeningForAdvertisements: success
,ok 167 no errors
,2016-03-19 11:51:15.324 ThaliTest[1348:3099972] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-19 11:51:15.325 ThaliTest[1348:3099972] jxcore: stopListeningForAdvertisements: success
,ok 168 still no errors
,# setup
,2016-03-19 11:51:16.824 ThaliTest[1348:3099972] jxcore: stopAdvertisingAndListening
2016-03-19 11:51:16.824 ThaliTest[1348:3099972] THEMultipeerManager stopping peer
2016-03-19 11:51:16.824 ThaliTest[1348:3099972] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-19 11:51:16.825 ThaliTest[1348:3099972] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-19 11:51:16.826 ThaliTest[1348,:3099972] jxcore: stopListeningForAdvertisements: success
,# 42. should be able to call #startListeningForAdvertisements many times
,2016-03-19 11:51:18.027 ThaliTest[1348:3099972] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-19 11:51:18.027 ThaliTest[1348:3099972] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-19 11:51:18.028 ThaliTest[1348:3099972] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-19 11:51:18.029 ThaliTest[1348:3099972] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65031
,2016-03-19 11:51:18.331 ThaliTest[1348:3099972] jxcore: startListeningForAdvertisements
,2016-03-19 11:51:18.332 ThaliTest[1348:3099972] multipeer manager: start client restart timer: 0x1556de10
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-19 11:51:18.338 ThaliTest[1348:3099792] client: found new peer: F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:9
2016-03-19 11:51:18.3,39 ThaliTest[1348:3099972] jxcore: startListeningForAdvertisements: success

```
